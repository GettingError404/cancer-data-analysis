# Global Exploratory and Inferential Analysis of Cancer Outcomes (2015–2024)

This project presents a **structured exploratory and inferential analysis** of a global cancer dataset containing **50,000 patient records** collected between **2015 and 2024**.

The primary focus is on **statistical reasoning, interpretability, and hypothesis-driven analysis**, rather than predictive accuracy or black-box modeling. The objective is to understand **what the data supports**, including weak and null effects, and to make assumptions and limitations explicit.

---

## 🔍 Research Questions Explored

This analysis investigates the following questions:

- How do demographic, lifestyle, genetic, and environmental factors relate to cancer severity?
- Are early-stage diagnoses evenly distributed across different cancer types?
- Does higher treatment cost correlate with longer survival?
- Do advanced cancer stages lead to higher treatment costs or reduced survival?
- Does genetic risk amplify the effect of smoking on cancer severity?

---

## 📊 Dataset Overview

- **Number of records:** 50,000 cancer patients  
- **Time span:** 2015–2024  
- **Geographic scope:** Multiple countries (global coverage)

### Key variables include:
- **Demographics:** age, gender, country/region, year of diagnosis  
- **Risk factors:** genetic risk, smoking, alcohol use, obesity level, air pollution  
- **Clinical variables:** cancer type, cancer stage  
- **Economic factors:** treatment cost (USD)  
- **Outcomes:** survival years, target severity score  

---

## 🧠 Methodology (High-Level)

The analysis follows a principled, step-by-step approach:

- Exploratory Data Analysis (EDA) to understand distributions, balance, and structure
- Correlation analysis using **Pearson** and **Spearman** coefficients
- Formal hypothesis testing (correlation tests, Kruskal–Wallis tests)
- Linear regression models, including interaction terms
- Tree-based models (Random Forest) used **exploratorily** for feature importance, not as final predictors

All results are interpreted with careful attention to **assumptions**, **effect sizes**, and the **constraints of observational healthcare data**.

---

## 📌 Key Findings (Summary)

- Individual lifestyle and environmental risk factors show **weak linear relationships** with cancer severity when analyzed in isolation.
- Early-stage diagnosis rates are relatively consistent across cancer types, typically ranging between **38–41%**.
- **Treatment cost is not associated with longer survival**, despite common assumptions.
- Cancer stage does not exhibit statistically significant differences in average treatment cost or survival years in this dataset.
- No statistically significant interaction effect was found between **genetic risk and smoking** on cancer severity.

Importantly, null and weak results are treated as **meaningful analytical outcomes**, not discarded.

---

## ⚠️ Limitations

This study has several important limitations:

- The dataset is **observational**, so no causal claims are made
- Some variables may be synthetically balanced or normalized
- Linear models may fail to capture nonlinear or latent dynamics
- Survival data may be simplified and not fully censored
- Results should be interpreted as **population-level associations**, not individual predictions

---

## 📁 Repository Structure

├── data/
│ └── global_cancer_patients_2015_2024.csv
├── notebooks/
│ └── Cancer data Analysis.ipynb
├── visuals/
├── README.md
└── requirements.txt

yaml
Copy code

---

## ▶️ How to Run the Analysis

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
Launch Jupyter Notebook:

bash
Copy code
jupyter notebook
Open the notebook located in the notebooks/ directory.

🔮 Future Directions
Potential extensions of this work include:

Multivariate and causal modeling approaches

Survival analysis using Cox proportional hazards models

Bayesian inference for uncertainty-aware analysis

Reinforcement learning–based decision simulations

Robust sensitivity and uncertainty analysis
