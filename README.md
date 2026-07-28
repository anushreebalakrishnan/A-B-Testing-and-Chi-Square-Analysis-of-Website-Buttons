# A/B Testing and Chi Square Analysis of Website Buttons

## 📌 Project Overview

This project investigates the performance of four website button variants using the **Chi-Square Test of Independence**. The goal was to determine whether different button designs influenced users' click behavior and identify which variant performed best based on statistical evidence and user engagement metrics.

---

## 🎯 Objectives

- Compare the performance of four website button variants.
- Determine whether differences in click-through rates (CTR) are statistically significant.
- Apply statistical hypothesis testing to support data-driven decisions.
- Analyze additional engagement metrics to better understand user behavior.

---

## 🧪 Button Variants

| Variant | Button Design |
|---------|---------------|
| **A** | White **"SHOP NOW"** |
| **B** | Red **"SHOP NOW"** |
| **C** | White **"SEE DEALS"** |
| **D** | Red **"SEE DEALS"** |

---

## 📊 Metrics Analyzed

### Click-Through Rate (CTR)

The primary metric used to evaluate button performance.

**CTR = Total Clicks / Total Visits**

A higher CTR indicates that the button is more effective at encouraging users to click.

### Drop-Off Rate

Measures the percentage of users who leave the conversion process after clicking the button.

A lower drop-off rate indicates stronger user engagement.

### Homepage Return Rate (HRR)

Measures how often users return to the homepage after clicking a button.

A lower HRR suggests that users are finding relevant content after clicking.

---

## 🔬 Methodology

- Cleaned and explored the experimental dataset.
- Performed a **Chi-Square Test of Independence** to compare click-through rates across the four button variants.
- Conducted **post-hoc pairwise comparisons** using the **Bonferroni correction** to identify statistically significant differences between individual variants.
- Interpreted the results alongside engagement metrics to provide business recommendations.

---

## 📈 Key Findings

- Versions **A** and **C** achieved the highest click-through rates and showed **no statistically significant difference** in CTR.
- Version **C** attracted more initial clicks but experienced a higher drop-off rate after users clicked.
- Version **A** provided the most balanced performance by combining a strong CTR with better post-click engagement.
- Version **D** consistently underperformed compared to the other variants.

---

## 💡 Conclusion

The statistical analysis did not identify a single dominant winner based solely on click-through rate. However, **Versions A and C emerged as the strongest-performing variants**.

When both click performance and user engagement are considered, **Version A** appears to offer the best overall user experience, while **Version C** is more effective at attracting clicks but less successful at retaining user engagement.
---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy (`chi2_contingency`)
- Jupyter Notebook
- Statistical Hypothesis Testing

---

## 📚 Skills Demonstrated

- A/B Testing
- Chi-Square Test of Independence
- Hypothesis Testing
- Post-hoc Analysis
