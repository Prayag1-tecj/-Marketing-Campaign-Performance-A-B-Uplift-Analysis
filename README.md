# A/B Testing Analysis: Facebook Ads vs Google AdWords Campaigns

## 📌 Project Overview

This project analyzes and compares the performance of two digital advertising campaigns — **Facebook Ads** and **Google AdWords Ads** — conducted throughout the year **2019**.  

---

## 🎯 Business Problem

As a marketing analytics team, we want to answer the following questions:

- Which advertising platform performs better overall?
- Which campaign generates higher engagement and conversions?
- Which platform is more cost-effective?
- Are observed performance differences statistically meaningful?
---
## 📊 Dataset Description

The dataset contains **daily performance data for the year 2019** (365 rows), comparing two advertising platforms:

- **Facebook Ad Campaign**
- **Google AdWords Ad Campaign**

Each row represents **one day of campaign activity**.

### Key Features

- **Date** – Calendar date of campaign performance
- **Ad Views** – Number of impressions
- **Ad Clicks** – Number of clicks received
- **Ad Conversions** – Number of successful conversions
- **Cost per Ad** – Cost incurred for running the ad
- **Click-Through Rate (CTR)** – Clicks ÷ Views
- **Conversion Rate** – Conversions ÷ Clicks
- **Cost per Click (CPC)** – Cost ÷ Clicks

---

## 🧪 Analysis Approach

The analysis follows a structured data analytics workflow:

1. **Data Cleaning & Preparation**
   - Checked for missing values
   - Verified data consistency and date coverage
   - Created derived metrics such as CTR, Conversion Rate, and CPC

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis of clicks, conversions, and cost
   - Time-based trends across the year
   - Comparison of campaign performance using visualizations

3. **Campaign Comparison**
   - Facebook Ads vs AdWords Ads
   - CTR comparison
   - Conversion efficiency
   - Cost effectiveness (CPC and cost per conversion)

4. **A/B Testing & Statistical Comparison**
   - Evaluated whether performance differences are meaningful
   - Compared average metrics across campaigns
   - Focused on business impact rather than only statistical significance

---

## 📈 Key Insights & Findings

- One campaign consistently showed **higher engagement (CTR)** compared to the other.
- Conversion patterns differed, indicating **platform-level behavioral differences**.
- Cost efficiency varied across platforms, highlighting trade-offs between:
  - Higher reach vs higher conversion quality
- Certain days showed **outliers in conversions**, which were investigated during EDA.
- Overall results suggest that **campaign choice should depend on business goals**:
  - Awareness vs conversion-driven objectives

> The analysis demonstrates that higher clicks do not always translate to higher conversions, emphasizing the importance of multi-metric evaluation.

---

## 🧠 Business Interpretation

- A/B testing is not only about identifying a “winner”, but about understanding **how and why campaigns behave differently**.
- Marketing decisions should consider:
  - Cost per conversion
  - Conversion efficiency
  - Campaign consistency over time
- The insights from this analysis can directly inform **budget allocation and channel strategy**.

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Visualization
- **Jupyter Notebook** – Analysis workflow


---

## 📌 Key Learning Outcomes

- Hands-on experience with A/B testing in a real marketing context
- Improved understanding of campaign performance metrics
- Ability to translate data insights into business recommendations
- Strong foundation in exploratory data analysis and comparative analytics

---

## 🔮 Future Enhancements

- Apply formal statistical hypothesis testing (t-test / non-parametric tests)
- Segment analysis by time periods or campaign intensity
- Extend analysis with predictive modeling for conversions
- Dashboarding using Power BI or Tableau

---

## 🧾 Conclusion

This project demonstrates how **data-driven analysis and A/B testing** can be used to evaluate marketing campaign effectiveness and guide business decisions.  
It highlights the importance of combining **statistical reasoning with business context** when interpreting marketing performance.






