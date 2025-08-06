# 📈 A/B Testing Project: Email Newsletter Signup Optimization

## 🧪 Overview

This project aims to optimize email newsletter signups by testing whether a new **Call-To-Action (CTA) button design** performs better than the original button using A/B testing and statistical hypothesis testing methods.

---

## 🗂️ Project Details

- **Project ID:** 1  
- **Title:** Email Newsletter Signup Optimization  
- **Method:** Two-sample Z-test for proportions  
- **Data Type:** Binary (0 = No Signup, 1 = Signup)  
- **Time Spent:** 2–3 hours  
- **Difficulty Level:** Beginner

---

## 🎯 Objective

To determine if the new CTA button increases signup conversions compared to the original.

---

## 📊 Hypotheses

- **Null Hypothesis (H₀):** Signup rates are the same between the original and new CTA button.
- **Alternative Hypothesis (H₁):** The new CTA button increases signup rates.
- **Type I Error Rate (α):** 0.05
- **Test Type:** Right-tailed Z-test (one-tailed)

---

## 🧰 Tools & Libraries

- Python  
- NumPy  
- Pandas  
- `statsmodels.stats.proportion` (for z-test)

---

## 📁 Dataset Structure

Simulated binary data:
- `group`: Either `control` or `treatment`
- `signup`: 1 if the user signed up, 0 otherwise

```plaintext
| group     | signup |
|-----------|--------|
| control   | 1      |
| control   | 0      |
| ...       | ...    |
| treatment | 1      |
| treatment | 0      |
```

---

## 📈 Results

Performed a proportions z-test between two independent samples.

Used `alternative='larger'` to test if the treatment group outperformed the control.

Interpreted the p-value to either reject or fail to reject H₀.

---

## 📚 Key Concepts Learned

- A/B testing fundamentals
- Binary data simulation
- Z-test for proportions
- Hypothesis testing (one-tailed vs two-tailed)
- Interpreting statistical significance

---

## 🔗 References


- [Trustworthy Online Controlled Experiments - Ron Kohavi](https://www.scribd.com/document/711189937/Kohavi-Diane-Tang-Xu-Trustworthy-Online-Controlled-Experiments-A-Practical-Guide-to-AB-Testing-2020)
- [Practical Statistics for Data Scientists]()
- [Statsmodels Proportions Z-Test Documentation](https://www.statsmodels.org/stable/generated/statsmodels.stats.proportion.proportions_ztest.html)


---

## 🚀 Next Steps

- Try different sample sizes and conversion rates
- Visualize results with bar charts or confidence intervals
- Apply this method on real user behavior datasets
