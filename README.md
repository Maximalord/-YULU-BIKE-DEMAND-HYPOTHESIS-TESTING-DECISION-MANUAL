# 🚲 Yulu Ride Data Analysis – Hypothesis Testing & Business Insights  

## 📊 Project Overview  
This project performs a **statistical analysis of Yulu ride data** to uncover how various factors such as working days, seasons, and weather influence the number of rides.  
We apply **core hypothesis testing techniques** — including **t-tests, ANOVA, and Chi-square tests** — to derive actionable business insights for operational and strategic decisions.  

---

## 🎯 Objectives  
- Determine if average rides differ between **working days and non-working days** using a 2-sample t-test.  
- Check if **season** or **weather** significantly affects average ride counts using ANOVA.  
- Examine dependency between **season** and **weather** using a Chi-square test.  
- Translate statistical results into **business recommendations** for demand forecasting and resource allocation.  

---

## 🧠 Statistical Tests Used  

### 1. Two-Sample t-test  
**Goal:** Check if the mean number of rides differs between working and non-working days.  
- **Assumptions checked:**  
  - Normality → Shapiro-Wilk test + visual inspection  
  - Equal variances → Levene’s test  
- **Interpretation:**  
  - p < 0.05 → Significant difference in means.  
  - p ≥ 0.05 → No significant difference.

---

### 2. ANOVA  
**Goal:** Test whether the average number of rides differs across:  
- Seasons  
- Weather conditions  

**Interpretation:**  
- p < 0.05 → At least one group mean differs significantly.  
- p ≥ 0.05 → No evidence of difference in means.

---

### 3. Chi-Square Test  
**Goal:** Test if **season** and **weather** are dependent.  
- **H₀:** Season and weather are independent.  
- **H₁:** Season and weather are dependent.  
- **Interpretation:**  
  - p < 0.05 → Significant dependency between season and weather.  
  - p ≥ 0.05 → No dependency detected.

---

## 📈 Business Insights  

| Test | Insight | Business Impact |
|------|----------|----------------|
| 2-Sample t-test | Compare working vs non-working days | Plan fleet allocation around office hubs and weekdays |
| ANOVA (Season) | Demand variation by season | Schedule maintenance and promotions seasonally |
| ANOVA (Weather) | Weather impact on rides | Integrate forecasts into dynamic pricing |
| Chi-Square | Dependency between season & weather | Use season as a proxy for weather in predictive models |

---

## 💡 Recommendations  
1. Increase fleet near **transit hubs** during working days.  
2. Run **seasonal promotions** during low-demand periods.  
3. Use **weather forecasting** to adjust pricing dynamically.  
4. Build a **demand prediction model** using significant predictors (e.g., workingday, temp, humidity, season, weather).  

---

## 🧩 Tools & Technologies  
- **Language:** Python 🐍  
- **Libraries:** pandas, numpy, scipy.stats, matplotlib, seaborn  
- **Notebook:** Jupyter / VS Code  

---


