# Statistical Hypothesis Testing in Python

This Jupyter notebook demonstrates a complete **statistical hypothesis testing workflow** using both **synthetic** and **real-world datasets**, covering **parametric** and **non-parametric** tests.

---

## Objective

To apply and interpret various statistical hypothesis tests through a practical, step-by-step approach involving:

- Dataset preparation (synthetic + real)
- Assumption checking (normality, homogeneity)
- Hypothesis formulation
- Test selection (based on assumptions)
- Statistical result interpretation
- Visualization for better understanding

---

## Structure of the Notebook

| Section | Description |
|--------|-------------|
| **1. Introduction** | Overview of statistical testing workflow. |
| **2. Dataset Preparation** | - `marketing_data`: A synthetic dataset for marketing spend. <br> - `iris_df`: Real-world Iris dataset from sklearn. |
| **3. Assumption Checking** | - **Shapiro-Wilk Test** for normality<br> - **Levene’s Test** for homogeneity of variance |
| **4. Parametric Tests** | - Independent t-test<br> - Paired t-test<br> - One-way ANOVA<br> - Pearson Correlation |
| **5. Non-Parametric Tests** | - Mann-Whitney U Test<br> - Wilcoxon Signed-Rank Test<br> - Kruskal-Wallis Test |
| **6. Chi-Square Tests** | - Test of Independence<br> - Goodness of Fit |
| **7. Visualizations** | Plots for distributions, group comparisons, and correlations (added for clarity and insight). |
| **8. Conclusion** | Summary of methods, assumptions, and best practices. |

---

## Visualizations Included

- Boxplots & Violin plots for group comparisons
- Pairplot of Iris dataset features
- Correlation heatmap for continuous variables
- Chi-square contingency visualization (optional)

---

## Dependencies

Make sure to install the following libraries before running the notebook:

```bash
pip install pandas numpy scipy seaborn matplotlib scikit-learn
```

---

## Tests Implemented

| Test | Use Case |
|------|----------|
| Shapiro-Wilk | Test for normality |
| Levene's Test | Test for equal variances |
| t-test (independent & paired) | Compare means |
| ANOVA | Compare means across >2 groups |
| Pearson Correlation | Check linear relationships |
| Mann-Whitney U | Non-parametric test for independent groups |
| Wilcoxon | Non-parametric test for paired data |
| Kruskal-Wallis | Non-parametric ANOVA |
| Chi-Square | Test for independence and distribution fit |

---

## Key Learnings

- Always check assumptions before applying statistical tests.
- Parametric tests offer more power but require normality and homogeneity.
- Use non-parametric tests when assumptions are violated.
- Interpret results with both **statistical** and **practical** significance in mind.
- Visualization enhances interpretability.

---

## How to Run

1. Clone or download this repo
2. Install required packages
3. Open the notebook in Jupyter or VSCode
4. Run cells step-by-step and observe results
5. Try tweaking data or testing other hypotheses

---

## 📧 Author

Notebook by: Md. Sadman Hasan Talukder  
