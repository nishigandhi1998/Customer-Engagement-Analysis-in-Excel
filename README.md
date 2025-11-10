# 📊 Customer Engagement Analysis in Excel  
**A Practical Data-Driven Approach to Evaluating Student Engagement Metrics**  

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-green?logo=microsoft-excel&logoColor=white)
![Analysis Type](https://img.shields.io/badge/Type-Customer%20Engagement-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Year](https://img.shields.io/badge/Period-Q4%202021%20–%20Q4%202022-lightgrey)

---

## 🧭 Project Overview  
In 2022, **365 Company** launched several new gamified features — **XP points**, **leaderboards**, **in-app coins**, **streaks**, and an **expanded course library** — aimed at increasing student engagement on its learning platform.

This project analyses whether those enhancements effectively improved **customer engagement** between **Q4 2021** and **Q4 2022**, using **Excel-based statistical analysis and visualisation**.

---

## 🎯 Objective  
To determine if new platform features led to **higher engagement** and to identify how engagement trends differ between **paid and free users**.

---

## 🧩 Dataset Summary  
**Source:** 365 Company internal engagement logs (anonymised)  
**Period:** Q4 2021 vs Q4 2022  
**File:** `Engagement_project.xlsx`  

| Column | Description |
|---------|--------------|
| `student_id` | Unique identifier for each student |
| `student_country` | Country of the student |
| `Paid` | 1 = Paid plan, 0 = Free plan |
| `minutes_watched_21` | Minutes watched in Q4 2021 |
| `minutes_watched_22` | Minutes watched in Q4 2022 |

---

## ⚙️ Methodology  

1. **Descriptive Statistics** – Mean, Median, and Standard Deviation to measure central tendency and variability.  
2. **Distribution Analysis** – Skewness & Kurtosis to understand outliers and distribution shape.  
3. **Confidence Intervals (95%)** – To estimate true population averages.  
4. **Hypothesis Testing (t-Test)** – To test if 2022 engagement > 2021 engagement.  
5. **Regional Comparison (US vs India)** – To identify localization opportunities.  

All analyses were completed in **Microsoft Excel** using formulas, PivotTables, and the **Data Analysis ToolPak**.

---

## 📈 Key Results  

### **1️⃣ Paid-Plan Users**
| Metric | Q4 2021 | Q4 2022 | Change |
|---------|---------|---------|---------|
| Mean Minutes | 33.8 | 273.0 | ▲ +707% |
| Median Minutes | 26.3 | 40.3 | ▲ +53% |
| Std Dev | 28.2 | 854.6 | Large increase |

**Insight:** Paid users who were low-engagement in 2021 became far more active in 2022, showing that premium features encouraged sustained participation.

---

### **2️⃣ Free-Plan Users**
| Metric | Q4 2021 | Q4 2022 | Change |
|---------|---------|---------|---------|
| Mean Minutes | 25.4 | 117.6 | ▲ +363% |
| Median Minutes | 14.2 | 11.8 | ▼ –17% |
| Std Dev | 26.2 | 468.9 | Large increase |

**Insight:** Mean increased but median fell — engagement improved only for a small group of power users while typical free users watched less content.

---

### **3️⃣ Distribution Analysis**
| Group | Year | Skewness | Kurtosis | Interpretation |
|-------|------|-----------|-----------|----------------|
| Paid | 2021 | 0.63 | –0.85 | Near-normal |
| Paid | 2022 | 7.07 | 58.48 | Highly right-skewed |
| Free | 2021 | 1.17 | 0.36 | Moderate skew |
| Free | 2022 | 15.06 | 315.76 | Extremely skewed |

**Conclusion:** Engagement distributions became **highly right-skewed** in 2022 — only a few students drove most of the growth.

---

### **4️⃣ Confidence Intervals (95%)**
| Group | Q4 2021 CI | Q4 2022 CI | Direction |
|--------|-------------|-------------|------------|
| Paid Users | 316.25 – 348.76 | 351.91 – 384.72 | 📈 Increase |
| Free Users | 129.92 – 137.95 | 67.71 – 70.59 | 📉 Decrease |

---

### **5️⃣ Hypothesis Testing (Two-Sample t-Test)**  
- **Paid Users:** p < 0.05 → Reject H₀ → Engagement significantly increased.  
- **Free Users:** p > 0.05 → Fail to Reject H₀ → No significant increase.  

---

### **6️⃣ Regional Comparison (US vs India)**  
- **Result:** Indian students watched significantly more minutes than US students in 2022.  
- **Insight:** Platform features resonate more with Indian audiences → opportunity for localisation in the US market.  

---

## 💡 Analytical Insights  

| Observation | Implication |
|--------------|-------------|
| Paid users’ engagement surged | Premium features deliver measurable value. |
| Free users’ median fell | Need targeted re-engagement strategies. |
| Rising skewness & kurtosis | Engagement driven by a few hyper-active users. |
| India > US engagement | Optimize content & UX for US learners. |

---

## 🧠 Recommendations  

1. **Personalise Engagement Mechanisms:** Tailor streaks, challenges, and XP rewards for different user groups.  
2. **Target Free Users:** Offer short trial access to paid features to build retention habits.  
3. **Measure Feature Impact:** Instrument metrics by feature (XP, leaderboard, streaks).  
4. **Shift KPIs:** Use **median watch time**, **90th percentile**, and **% users > 100 min** instead of mean-based averages.  
5. **Localisation Strategy:** Invest in region-specific content to boost U.S. engagement.

---

## 📋 Conclusion  
The analysis confirms that **paid users’ engagement increased significantly**, while **free users showed limited or no improvement**.  
The new platform features succeeded in deepening engagement for paying subscribers but failed to scale motivation across the free-user base.  
Future success depends on **personalisation, regional targeting, and incentive-driven engagement strategies**.

---

## 💬 Executive Takeaway  
> *2022’s engagement features boosted retention among paid subscribers but not free users.  
> To achieve sustainable growth, 365 Company must move from generic gamification to personalised, data-driven engagement experiences.*

---

## 🧾 Project Highlights  
**Tools:** Excel (PivotTables, SKEW, KURT, t-Test, CI Formulas)  
**Techniques:** Descriptive Statistics, Hypothesis Testing, Data Visualisation  
**Focus:** Customer Engagement Analysis – Paid vs Free Cohorts  
**Key Metrics:** Revenue CAGR (Engagement CAGR), Median Minutes, Skewness, Kurtosis  
**Result:** Significant increase for Paid Users; no significant change for Free Users  

---

## 🔒 License & Privacy Notice 
This project uses publicly available data for educational purposes only.  
No proprietary or confidential company information is shared.
Credit: 365 DATA SCIENCE

---

### ⭐ If you found this project interesting  
Give it a ⭐ on GitHub and connect with me to discuss Data analytics and Excel automation!


## 🤝 For more details or collaboration opportunities, feel free to connect with me on 
👤 **Nishi** — *Data Analyst | Excel | SQL | Tableau | Python*  
🔗 [LinkedIn](https://www.linkedin.com/in/nishigandhianalyst/) | [Email](nishigandhi1998@gmail.com)

---

© 2025 Nishi | Customer Engagement Analysis in Excel Project


