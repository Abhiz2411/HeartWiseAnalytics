# 🫀 UCI Heart Disease Analysis

This project performs an in-depth **statistical analysis** of the [UCI Heart Disease dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data/), focusing on identifying key health indicators and patterns related to cardiovascular disease.

---

## 📌 Project Objective

Cardiovascular disease remains one of the top global health threats. Through statistical exploration, we aim to:
- Identify **key risk factors** and **group-level differences**.
- Uncover **significant relationships** between variables (e.g., age vs. heart rate).
- Use **inferential statistics** to validate medical hypotheses.
- Provide **data-driven evidence** for early detection and prevention.

---

## 📊 Dataset Overview

- **Source**: UCI Heart Disease via Kaggle
- **Features analyzed**: Age, Cholesterol, Blood Pressure, Chest Pain Type, Heart Rate, etc.
- **Target variable**: Presence or absence of heart disease

---

## 🔬 Statistical Techniques Applied

| Test / Method             | Purpose                                                 | Example in Project                                 |
|--------------------------|---------------------------------------------------------|----------------------------------------------------|
| **Descriptive Statistics** | Summarize central tendencies, variation               | Age, cholesterol, blood pressure                   |
| **Correlation Analysis**   | Find relationships between numerical variables        | Age ↔ Max heart rate (negative correlation)        |
| **One-Sample T-Test**      | Compare sample mean to population mean                | Is avg. cholesterol ≠ 200 mg/dL?                   |
| **Two-Sample T-Test**      | Compare two group means                               | Heart rate: disease vs. no disease (p < 0.001)     |
| **ANOVA**                  | Compare more than two group means                     | Cholesterol by chest pain type (p < 0.001)         |
| **Chi-Square Test**        | Test association between categorical variables        | Chest pain vs. disease presence (p < 2.2e-16)      |
| **Simple Linear Regression** | Predict one variable from another                   | Cholesterol ~ Age (R² = 0.0074)                    |

---

## 📈 Key Findings

- **Max heart rate is significantly lower** in patients with heart disease.
- **Chest pain type** is a strong predictor of disease presence.
- **Age negatively impacts cholesterol** slightly, though model has low predictive power.
- **Statistical methods** bring clarity to patterns not immediately obvious from raw data.

---

## 📎 Files Included

- `Heart_Disease.Rmd`: Complete R code for analysis and plots.
- `Heart_Disease_Report_verify.docx`: Polished report with explanations and interpretations.
- *(Optional)* `Heart_Disease.csv`: Dataset used (if included).

---

## 🔧 Requirements

To run the analysis:
- R (version ≥ 4.0)
- R packages:
  - `ggplot2`
  - `dplyr`
  - `tidyverse`
  - `readr`
  - `knitr`
  - `stats`

Install all with:
```r
install.packages(c("ggplot2", "dplyr", "tidyverse", "readr", "knitr"))
```

---

## 📚 References

- UCI Heart Disease Dataset: [Kaggle Link](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data/)
- Montgomery & Runger (2014). *Applied Statistics and Probability for Engineers*
- Moore, McCabe, & Craig (2017). *Introduction to the Practice of Statistics*
- [R Documentation](https://www.rdocumentation.org/)

---

## 👨‍🔬 Project Team

- Abhijit Zende
- Saksham Agrawal
- Sharvin Shinde

**Under the guidance of:**
- Prof. M.V. Yugandhar
- T.A. Nikita Divay

---

## 💡 Conclusion

This project highlights how **statistical methods in R** can aid in **real-world health insights**, supporting early detection and personalized healthcare interventions through evidence-based analysis.
