# 🔐 Authentication System Evaluation

This document outlines the calculation of **False Acceptance Rate (FAR)** and **False Rejection Rate (FRR)** based on a sample of 50 login attempts.

---

## 📊 Test Summary

| Category               | Count |
|------------------------|-------|
| Total login attempts   | 50    |
| Unauthorized users     | 10    |
| Authorized users       | 40    |
| False acceptances (FAR) | 2     |
| False rejections (FRR) | 6     |

---

## ✅ Definitions

- **False Acceptance Rate (FAR)**: Percentage of unauthorized users incorrectly granted access.
- **False Rejection Rate (FRR)**: Percentage of authorized users incorrectly denied access.

---

## 🧮 Calculations

### False Acceptance Rate (FAR)

\[
\text{FAR} = \frac{\text{False Acceptances}}{\text{Total Unauthorized Attempts}} = \frac{2}{10} = 0.2 = \boxed{20\%}
\]

### False Rejection Rate (FRR)

\[
\text{FRR} = \frac{\text{False Rejections}}{\text{Total Authorized Attempts}} = \frac{6}{40} = 0.15 = \boxed{15\%}
\]

---

## 📌 Key Insight

Although the raw count of false rejections (6) is greater than false acceptances (2), the **rate** is lower because it’s calculated relative to a larger group (40 authorized users vs. 10 unauthorized users).

---

## 🧠 Analogy

> A class of 10 students with 2 failures has a 20% failure rate.  
> A class of 40 students with 6 failures has a 15% failure rate.  
> More failures ≠ higher rate — it depends on the group size.

---

## 📁 Repository Use

This `.md` file can be used for:

- 📘 Documentation of system performance
- 🧪 Benchmarking authentication accuracy
- 📊 Visual reference in README or Wiki
- 🛠️ Integration with testing dashboards

---


