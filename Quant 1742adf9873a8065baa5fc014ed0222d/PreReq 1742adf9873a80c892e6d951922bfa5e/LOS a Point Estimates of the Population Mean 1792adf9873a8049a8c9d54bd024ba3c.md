# LOS a Point Estimates of the Population Mean

> **Learning Outcome**
> 
> - *identify and describe desirable properties of an estimator*

---

pg 43-1

---

pg 43-2

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### SE = Standard Error

---

**Definition**:
The **standard error (SE)** is a statistical measure that estimates the variability or dispersion of a sample statistic (e.g., sample mean or sample proportion) relative to its true population parameter. It reflects how much the sample statistic is expected to vary if the same sampling process is repeated multiple times.

---

### Key Points:

1. **Purpose**:
    - The standard error helps measure the accuracy of a sample statistic in estimating the corresponding population parameter.
    - A smaller SE indicates that the sample statistic is likely closer to the population parameter.
2. **Formula**:
    - For the sample mean ($x̄$):
        
        $$
        SE_{\bar{x}} = \frac{s}{\sqrt{n}}
        
        $$
        
        Where:
        
        - $s$: Sample standard deviation.
        - $n$: Sample size.
    - For the sample proportion ($p̂$):
        
        $$
        SE_p̂ = \sqrt{\frac{p̂(1 - p̂)}{n}}
        
        $$
        
        Where:
        
        - $p̂$: Sample proportion.
3. **Relation to Standard Deviation**:
    - While the **standard deviation** measures variability within a dataset, the **standard error** measures variability in the sample statistic across repeated samples.
4. **Influence of Sample Size**:
    - As sample size ($n$) increases, the standard error decreases. This is because larger samples provide more precise estimates of the population parameter.
5. **Applications**:
    - Used in hypothesis testing to calculate test statistics (e.g., $z$-scores or $t$-scores).
    - Helps construct confidence intervals to estimate population parameters.
6. **Why is it an Estimator?**
    - The true variability in the sampling distribution (i.e., $\frac{σ}{\sqrt{n}}$) is unknown because the population standard deviation ($σ$) is typically unknown.
    - The standard error uses the sample standard deviation ($s$) as an **estimate** for $σ$, making it an estimator.

---

### Example:

Suppose we take a sample of 100 students to estimate the average height of all students in a school.

- Sample mean ($x̄$): 160 cm.
- Sample standard deviation ($s$): 10 cm.

The standard error of the mean is:

$$
SE_{\bar{x}} = \frac{s}{\sqrt{n}} = \frac{10}{\sqrt{100}} = 1 \text{ cm.}
$$

This means the sample mean is expected to vary by about 1 cm from the true population mean if we were to repeat the sampling process.

---

### Summary:

The standard error is a crucial tool in statistics for understanding the reliability of sample-based estimates. It quantifies uncertainty and provides a foundation for making inferences about the population.

</aside>

<aside>

### EXAMPLE 7

---

### *(EXAMPLE 1)* [Link](https://study.cfainstitute.org/app/cfa-program-level-i-prerequisite-readings-for-2025#read/section/point-estimates-of-the-population-mean-1)

---

[Exhibit 4](LOS%20a%20Point%20Estimates%20of%20the%20Population%20Mean%201792adf9873a8049a8c9d54bd024ba3c.md) plots several sampling distributions of an estimator for the population mean, and the vertical dash line represents the true value of population mean.

Which of the following statements *best* describes the estimator’s properties?

**A.** The estimator is unbiased.

**B.** The estimator is biased and inconsistent.

**C.** The estimator is biased but consistent.

<aside>

### Exhibit 4

**Sampling Distributions of an Estimator**

---

![CFA0128-R-EXH13.jpg](LOS%20a%20Point%20Estimates%20of%20the%20Population%20Mean%201792adf9873a8049a8c9d54bd024ba3c/CFA0128-R-EXH13.jpg)

n = 1,000 is a steeper bell shaped curve skewed towards left, intersected by less steep, n = 200 curve, skewed towards left. n = 50 curve is flatter curve, skewed towards left. Peak of n = 50 is on left tail of n = 200 and peak of n = 200 is on left tail of n = 1,000.

</aside>

- [Show Solution](LOS%20g%20Measures%20of%20Central%20Tendency%201762adf9873a805c94b8c8279334c867/Geometric%20Mean%201762adf9873a80e4a50ae209c3e05a78.md)
    
    <aside>
    
    C is correct. The chart shows three sampling distributions of the estimator at different sample sizes (*n* = 50, 200, and 1,000). We can observe that the means of each sampling distribution—that is, the expected value of the estimator—deviate from the population mean, so the estimator is biased. As the sample size increases, however, the mean of the sampling distribution draws closer to the population mean with smaller variance. So, it is a consistent estimator.
    
    </aside>
    
</aside>

---