# LOS c Confidence Interval (calculate, interpret)

> **Learning Outcome**
> 
> - *calculate and interpret a confidence interval for a population mean, given a normal distribution with 1) a known population variance, 2) an unknown population variance, or 3) an unknown population variance and a large sample size*

---

pg 44-3 to 44-4

---

pg 45-5

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Why the Z-Value is Used in Confidence Intervals Only When Population Variance is Known?

---

The **Z value** is used in constructing **confidence intervals** when the **population variance (or standard deviation) is known** because it assumes that the sampling distribution of the sample mean follows a normal distribution. This assumption holds more accurately when the population variance is known, allowing us to calculate the standard error of the mean precisely.

Here's why this condition is important:

### 1. **Known Population Variance**:

- When the **population variance (σ²)** is known, we can calculate the **standard error (SE)** of the sample mean using the formula:

where **σ** is the population standard deviation, and **n** is the sample size.
    
    $$
    SE = \frac{\sigma}{\sqrt{n}}
    $$
    
- Since the population variance is known, we are confident that the **sampling distribution of the sample mean** is **normally distributed** (or approximately normal if the sample size is large, thanks to the Central Limit Theorem).
- In this case, we can use the **Z-distribution** (standard normal distribution) to determine critical values for a given confidence level, such as 1.96 for a 95% confidence level.

### 2. **Central Limit Theorem (CLT)**: Page 37-8

- The **Central Limit Theorem** states that for large sample sizes, the sampling distribution of the sample mean will be approximately normally distributed, even if the population distribution is not normal.
- When the population variance is known, we can use the **Z-distribution** directly because it relies on the assumption that the underlying population has a known variance and the sample size is sufficiently large.

### 3. **When Population Variance is Unknown**:

- If the population variance is **unknown**, you cannot use the exact standard deviation (σ) to calculate the standard error.
- Instead, you estimate the population variance using the sample variance (s²). This introduces some **uncertainty** because the sample variance may not perfectly reflect the population variance, especially for small sample sizes.
- As a result, you use the **t-distribution** instead of the Z-distribution. The **t-distribution** accounts for this added variability by being wider (with thicker tails), reflecting the increased uncertainty when the population variance is not known.

---

### Summary of the Difference:

- **Z-Distribution**: Used when the population variance is **known** because it provides an accurate estimate of the standard error of the sample mean, and the sampling distribution can be assumed to be normal.
- **T-Distribution**: Used when the population variance is **unknown** and must be estimated from the sample. The t-distribution adjusts for the added uncertainty by being more conservative (wider tails), particularly with small sample sizes.

---

### Conclusion:

The **Z value** is used in confidence intervals when the population variance is known because it provides a precise calculation of the standard error. When the population variance is unknown, the **t-distribution** is used instead, as it better accounts for the variability introduced by estimating the population parameter.

</aside>

![image.png](LOS%20c%20Confidence%20Interval%20(calculate,%20interpret)%201792adf9873a80de905fe6a958b7a5dc/image.png)

![CFA0128-R-EXH16.jpg](LOS%20c%20Confidence%20Interval%20(calculate,%20interpret)%201792adf9873a80de905fe6a958b7a5dc/CFA0128-R-EXH16.jpg)

---