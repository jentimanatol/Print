# MAT 181 - Chapter 8 Practice Problems with Full Solutions

Welcome to the extended and creative breakdown of Chapter 8 from MAT 181! This file goes in-depth into the hypothesis testing problems you've encountered, providing solutions, explanations, and formulae visualized in LaTeX-style for clarity.

---

## 🔍 Problem 1: Production Process Control
**Claim:** The defect rate exceeds 3%.  
**Sample:** 85 items, 5.9% defective  
**Significance Level:** $\alpha = 0.01$

### Hypotheses:
- $H_0: p = 0.03$
- $H_1: p > 0.03$

### Formula Used:
$z = \frac{\hat{p} - p_0}{\sqrt{\frac{p_0 (1 - p_0)}{n}}}$

### Calculation:
$\hat{p} = 0.059$, $p_0 = 0.03$, $n = 85$  
$z = \frac{0.059 - 0.03}{\sqrt{(0.03)(0.97)/85}} \approx 2.35$

**P-value:** 0.0094  
**Decision:** Reject $H_0$  
**Conclusion:** There is strong evidence that the process is out of control.

---

## 🗳️ Problem 2: Voter Preference
**Claim:** At least 50% prefer the Democrat.  
**Sample:** 1068 people, 48% Democrat  
**$\alpha = 0.05$

### Hypotheses:
- $H_0: p \geq 0.5$
- $H_1: p < 0.5$

### Calculation:
$z = \frac{0.48 - 0.5}{\sqrt{(0.5)(0.5)/1068}} \approx -1.23$  
**P-value:** 0.1093  
**Conclusion:** Fail to reject $H_0$. No evidence fewer than 50% prefer Democrat.

---

## 🧑‍⚖️ Problem 3: Support for Incumbent
**Claim:** True support is 53%.  
**Sample:** 100 people, 45% support  
**$\alpha = 0.10$

### Hypotheses:
- $H_0: p = 0.53$
- $H_1: p \neq 0.53$

### Calculation:
$z = \frac{0.45 - 0.53}{\sqrt{(0.53)(0.47)/100}} \approx -1.60$  
**P-value:** 0.1096  
**Conclusion:** Fail to reject $H_0$. The support is not significantly different.

---

## 🩺 Problem 4: Medical Specialty Interest
**Claim:** More than 28% go into general practice.  
**Sample:** 130 students, 32% GP  

### Hypotheses:
- $H_0: p = 0.28$
- $H_1: p > 0.28$

### Calculation:
$z = \frac{0.32 - 0.28}{\sqrt{(0.28)(0.72)/130}} \approx 1.02$  
**P-value:** $P(Z > 1.02) \approx 0.1539$

---

## 😷 Problem 5: Asthma in Children
**Claim:** 11% of all kids have asthma.  
**Sample:** 88 children, 8 with asthma  

### Hypotheses:
- $H_0: p = 0.11$
- $H_1: p \neq 0.11$

### Calculation:
$\hat{p} = 8/88 = 0.0909$  
$z = \frac{0.0909 - 0.11}{\sqrt{(0.11)(0.89)/88}} \approx -0.567$  
**P-value:** 0.5686  
**Conclusion:** Fail to reject $H_0$.

---

## 🧾 Problem 6: Defective Fax Machines
**Claim:** Less than 6% are defective.  
**Sample:** 97 machines, 5% defective  

### Hypotheses:
- $H_0: p \geq 0.06$
- $H_1: p < 0.06$

### Calculation:
$z = \frac{0.05 - 0.06}{\sqrt{(0.06)(0.94)/97}} \approx -0.415$  
**P-value:** 0.3409  
**Conclusion:** Fail to reject $H_0$.

---

## ⚖️ Problem 7: Female Weight (Extreme SD)
**Claim:** Mean weight is 132 lb.  
**Sample:** $\bar{x} = 137$, $s = 142$, $n = 20$, $\alpha = 0.10$

### Hypotheses:
- $H_0: \mu = 132$
- $H_1: \mu \neq 132$

### Formula Used:
$t = \frac{\bar{x} - \mu_0}{s/\sqrt{n}}$

### Calculation:
$t = \frac{137 - 132}{142/\sqrt{20}} \approx 0.157$  
**df:** 19, **P-value:** 0.8764  
**Conclusion:** Fail to reject $H_0$.

---

## 💼 Problem 8: Average Salary
**Claim:** Mean salary is $30,000.  
**Sample:** $\bar{x} = 22,298$, $s = 14,200$, $n = 17$, $\alpha = 0.05$

### Hypotheses:
- $H_0: \mu = 30000$
- $H_1: \mu \neq 30000$

### Calculation:
$t = \frac{22298 - 30000}{14200/\sqrt{17}} \approx -2.238$  
**df:** 16, **P-value:** 0.0412  
**Conclusion:** Reject $H_0$. Salaries differ from $30,000.

---

## 🧍‍♀️ Problem 9: Female Student Weight (Refined)
**Claim:** Mean is 132 lb.  
**Sample:** $\bar{x} = 137$, $s = 14.2$, $n = 20$, $\alpha = 0.10$

### Hypotheses:
- $H_0: \mu = 132$
- $H_1: \mu \neq 132$

### Calculation:
$t = \frac{137 - 132}{14.2/\sqrt{20}} \approx 1.574$  
**df:** 19, **P-value:** 0.1312  
**Conclusion:** Fail to reject $H_0$.

---

## 📌 Summary
You have now reviewed and solved 9 real-world hypothesis testing scenarios! Each case sharpened your understanding of:

- Proportion vs mean testing
- z-statistic vs t-statistic usage
- One- vs two-tailed tests
- How to compute and interpret P-values



