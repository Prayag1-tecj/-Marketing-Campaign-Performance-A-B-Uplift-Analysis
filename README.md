# Marketing Campaign Performance & A/B Uplift Analysis

This repository contains a complete A/B testing analytics project comparing **Campaign A vs Campaign B** to measure uplift in conversions, CTR, acquisition cost efficiency, and overall campaign ROI impact.  
Using Python-driven hypothesis testing and marketing KPI evaluation, the project determines which campaign should be scaled based on statistically validated uplift.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `AB Testing (Marketing Campaigns).ipynb` | Main Python notebook with cleaning, KPI extraction, hypothesis testing, uplift metrics & visualization |
| `marketing_campaign.csv` | Source dataset containing impressions, clicks, spend, conversions, revenue data |

---

## Objective

- Compare performance of **two campaign variants** (A vs B)
- Calculate uplift in:
  - Conversion Rate
  - Click-Through Rate (CTR)
  - Revenue Per User
  - Cost Per Acquisition (CAC)
  - Return on Marketing Spend (ROMS)
- Validate uplift using statistical significance testing

---

## 📊 Key KPIs Calculated

| KPI | Formula | Purpose |
|------|---------|---------|
| Conversion Rate (CVR) | `Conversions / Clicks` | Measures conversion efficiency |
| CTR | `Clicks / Impressions` | Measures ad engagement |
| Lift % | `(B - A) / A * 100` | Quantifies improvement |
| CPC | `Spend / Clicks` | Click cost efficiency |
| CAC | `Spend / Conversions` | Acquisition efficiency |
| ROMS | `Revenue / Spend` | Revenue generated per ₹ spent |

---

## 🧪 Statistical Methods Used

- **Two-proportion Z-test**
- **p-value significance validation**
- **Confidence interval comparison**
- **Proportional uplift validation**

Decision rule: If p-value < 0.05 → Campaign B uplift is statistically significant


---

## 🔍 Findings & Insights

- **Campaign B outperformed Campaign A** across conversion, CTR, and cost-efficiency KPIs.
- **A/B Testing & Hypothesis Validation: Conducted a daily A/B test (365 days) comparing Facebook and AdWords
    campaigns; used a T-Test (T = 46.85) to statistically prove Facebook conversions were significantly higher
    (p < 0.05) than AdWords conversions.
- **• Campaign Efficacy & Forecasting: Demonstrated Facebook’s superior conversion efficacy with a strong
      correlation (r = 0.87) between Clicks and Conversions; developed a Linear Regression model achieving
  R2 = 76.35% to accurately forecast future sales

- p-value < 0.05 confirms **uplift is not due to randomness**, supporting full-scale rollout.
- Increased engagement and stronger targeting match indicated optimized audience fit.

> Replace `XX%` with your actual notebook outputs.

---

## 🧠 Business Recommendations

- Scale **Campaign B** budget allocation for next cycle.
- Retarget high-intent audience segments observed in B performance layer.
- Deploy A/B variant learnings into future campaign creatives (copy, timing, placement).
- Track long-term retention impact if dataset is extended.

---

## 📦 Tech Stack

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib / Seaborn
- Scikit-learn (if used)
- Jupyter Notebook

---






