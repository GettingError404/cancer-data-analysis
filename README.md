# Global Exploratory and Inferential Analysis of Cancer Outcomes (2015–2024)

This project presents a structured exploratory and inferential analysis of a global cancer dataset
containing 50,000 patient records collected between 2015 and 2024.

The focus is on **statistical reasoning, interpretability, and hypothesis-driven analysis**, rather than
predictive performance or black-box modeling.

---

## 🔍 Key Questions Explored

- How do demographic, lifestyle, genetic, and environmental factors relate to cancer severity?
- Are early-stage diagnoses evenly distributed across cancer types?
- Does higher treatment cost correlate with longer survival?
- Do advanced cancer stages lead to higher costs or reduced survival?
- Does genetic risk amplify the effect of smoking on cancer severity?

---

## 📊 Dataset Overview

- Records: 50,000 cancer patients
- Time span: 2015–2024
- Countries: Multiple (global coverage)
- Features include:
  - Demographics (age, gender, country, year)
  - Risk factors (genetic risk, smoking, alcohol use, obesity, air pollution)
  - Clinical variables (cancer type, stage)
  - Economic factors (treatment cost)
  - Outcomes (survival years, severity score)

---

## 🧠 Methodology (High-Level)

- Exploratory Data Analysis (EDA)
- Correlation analysis (Pearson & Spearman)
- Hypothesis testing (Kruskal–Wallis, correlation tests)
- Linear regression with interaction terms
- Tree-based models for exploratory feature importance (Random Forest)

All results are interpreted with attention to assumptions and limitations of observational data.

---

## 📌 Key Findings (Summary)

- Individual risk factors show **weak linear relationships** with cancer severity when analyzed in isolation.
- Early-stage diagnosis rates are relatively consistent across cancer types (~38–41%).
- **Treatment cost is not associated with longer survival**, contrary to common intuition.
- Cancer stage does not show statistically significant differences in average treatment cost or survival.
- No significant interaction effect was found between genetic risk and smoking on severity.

---

## ⚠️ Limitations

- Observational dataset (no causal claims)
- Potential synthetic balancing of variables
- Linear models may not capture nonlinear dynamics
- Survival data may be simplified or uncensored

---

## 📁 Repository Structure

