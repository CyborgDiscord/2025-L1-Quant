# LOS f Normal Distribution (properties)

> **Learning Outcome**
> 
> - *explain the key properties of the normal distribution*

---

### Page **`37-8`**

---

### Page **`38-9`**

<aside>
<img src="https://www.notion.so/icons/report_gray.svg" alt="https://www.notion.so/icons/report_gray.svg" width="40px" />

### Reminder: Variance, Skewness, and Kurtosis

---

### **Variance**

- **Definition**: Measures how spread out the data is from the mean.
- **Interpretation**:
    - **Low variance**: Data points are close to the mean.
    - **High variance**: Data points are more spread out.
- **Use**: Helps assess risk or volatility in investments and other fields.

---

### **Skewness**

- **Definition**: Measures the asymmetry of a distribution.
- **Types**:
    - **Right (Positive) Skew**: Tail on the right side is longer. Mean > Median. Extreme positive values are pulling the distribution.
    - **Left (Negative) Skew**: Tail on the left side is longer. Mean < Median. Extreme negative values are pulling the distribution.
- **Use**: Indicates the direction of extreme values in the data. Helps understand potential for large positive or negative outcomes.

---

### **Kurtosis**

- **Definition**: Measures the "tailedness" of a distribution. How extreme or rare the outliers are.
- **Types**:
    - **Mesokurtic**: Normal distribution. Moderate peak and tails.
    - **Leptokurtic**: Higher peak, heavier tails (more extreme values).
    - **Platykurtic**: Flatter peak, lighter tails (fewer extreme values).
- **Use**: Helps understand the likelihood of extreme events. High kurtosis indicates more risk of extreme outcomes.

![image.png](LOS%20f%20Normal%20Distribution%20(properties)%201782adf9873a80929dbed4854b3f8ff6/image.png)

</aside>

<aside>
<img src="https://www.notion.so/icons/mathematics_gray.svg" alt="https://www.notion.so/icons/mathematics_gray.svg" width="40px" />

### $X \sim \mathcal{N}(\mu, \sigma^2)$

---

- $X$: Random variable
- $\sim$: "is distributed as"
- $\mathcal{N}$: Indicates a normal distribution
- $\mu$: Mean of the distribution
- $\sigma^2$: Variance of the distribution

---

For example, if $X \sim \mathcal{N}(0, 1)$, it means $X$ follows a normal distribution with a mean of 0 and variance of 1.

</aside>

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Characteristics: Point 3

---

A **linear combination** of random variables means that you create a new random variable by adding or subtracting weighted versions of two or more existing random variables.

When we're dealing with **normal random variables**, an interesting property is that any linear combination of these normal variables will **also be normally distributed**.

---

### What is a linear combination?

A **linear combination** of two random variables $X_1$ and $X_2$ could look something like this:

$$
Z = aX_1 + bX_2
$$

where:

- $a$ and $b$ are constants (called weights or coefficients).
- $X_1$ and $X_2$ are random variables.

---

### Normal Distribution Property

If $X_1 \sim \mathcal{N}(\mu_1, \sigma_1^2)$ and $X_2 \sim \mathcal{N}(\mu_2, \sigma_2^2)$, then the random variable $Z = aX_1 + bX_2$ will also follow a normal distribution. The mean and variance of $Z$ can be calculated as:

- **Mean of $Z$**:
    
    $$
    \mu_Z = a\mu_1 + b\mu_2
    $$
    
- **Variance of $Z$**:
    
    $$
    \sigma_Z^2 = a^2\sigma_1^2 + b^2\sigma_2^2 + 2ab \text{Cov}(X_1, X_2)
    $$
    
    where $\text{Cov}(X_1, X_2)$ is the covariance between $X_1$ and $X_2$.
    

---

### Why is this important?

1. **Univariate Normal Distribution**: When you're dealing with a single normal distribution (one random variable), it’s called univariate. For example, if you have $X \sim \mathcal{N}(\mu, \sigma^2)$, you can model the behavior of one variable.
2. **Multivariate Normal Distribution**: When you're dealing with multiple normal random variables (e.g., $X_1, X_2, \dots, X_n$), it’s called multivariate. In this case, each of those variables could be correlated with the others, but the key point is that any linear combination of them will still result in a normal distribution.
    - For example, if you have two correlated normal variables $X_1 \sim \mathcal{N}(\mu_1, \sigma_1^2)$ and $X_2 \sim \mathcal{N}(\mu_2, \sigma_2^2)$, and you form the linear combination $Z = aX_1 + bX_2$, $Z$ will still follow a normal distribution even if $X_1$ and $X_2$ are correlated.

---

### Real-life Example:

Imagine you are modeling the returns of two different stocks, $X_1$ and $X_2$, which both follow normal distributions. You then create a new portfolio by combining these two stocks, such as:

$$
Z = 0.6 \cdot X_1 + 0.4 \cdot X_2
$$

This new portfolio's return $Z$ will also follow a normal distribution, and you can calculate its mean and variance using the formula above. This property is super helpful in finance and other fields when dealing with risk and combining different variables.

---

### Summary

- A linear combination of normal random variables is **always normally distributed**.
- The mean and variance of the combination depend on the coefficients $a$ and $b$, as well as the means, variances, and covariance of the original random variables.
</aside>

---