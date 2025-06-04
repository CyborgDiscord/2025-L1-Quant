# LOS b Point Estimate vs. Confidence Interval

> **Learning Outcome**
> 
> - *contrast a point estimate and a confidence interval estimate of a population parameter*

---

pg 43-2 to 44-3

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Point Estimate vs. Confidence Interval

---

### **Point Estimate**

A **point estimate** is a single value calculated from sample data that serves as a best guess for an unknown population parameter.

### Key Features:

- **Single Value**: It provides a specific estimate (e.g., the sample mean for the population mean).
- **Example**: If a sample mean is 50, then 50 is the point estimate for the population mean.
- **Simplicity**: It's straightforward but lacks information about its reliability or variability.

### Common Point Estimates:

- Sample mean ($x̄$) for population mean ($μ$).
- Sample proportion ($p̂$) for population proportion ($P$).

---

### **Confidence Interval**

A **confidence interval (CI)** is a range of values, derived from sample data, that is likely to contain the population parameter with a certain level of confidence.

### Key Features:

- **Interval Format**: It provides an upper and lower limit, offering a range of plausible values for the population parameter.
- **Level of Confidence**: A 95% confidence interval means that if the same sampling process were repeated many times, 95% of the intervals would contain the true population parameter.
- **Formula**:
For a population mean:
    
    $$
    CI = \text{Point Estimate} \pm (\text{Critical Value} \times SE)
    $$
    
    Where:
    
    - Critical Value depends on the confidence level (e.g., 1.96 for 95% confidence).
    - SE is the standard error of the estimate.

---

### **Contrast Between Point Estimate and Confidence Interval**

| **Aspect** | **Point Estimate** | **Confidence Interval** |
| --- | --- | --- |
| **Definition** | A single value used to estimate a parameter. | A range of values likely to contain the parameter. |
| **Nature** | Precise but lacks reliability information. | Provides a range with a confidence level. |
| **Uncertainty** | Does not account for variability. | Reflects variability and sampling error. |
| **Example** | Sample mean = 50. | 95% CI = [47, 53]. |
| **Usage** | Best guess for the population parameter. | Indicates reliability of the estimate. |

---

### **Example**

1. **Point Estimate**:
    
    A sample mean of 160 cm is the point estimate for the average height of a population.
    
2. **Confidence Interval**:
    
    If the standard error is 2 cm, a 95% confidence interval would be:
    
    $$
    CI = 160 \pm (1.96 \times 2) = [156.08, 163.92]
    $$
    
    This means we are 95% confident that the true population mean lies between 156.08 cm and 163.92 cm.
    

---

### **Summary**

- A point estimate is simple and precise but lacks information about variability.
- A confidence interval complements the point estimate by providing a range that accounts for uncertainty, making it a more informative tool in decision-making.
</aside>

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Population Parameter

---

A **population parameter** is a numerical value that describes a characteristic or measure of an entire population. Unlike a **sample statistic**, which is derived from a subset of the population, a population parameter is a value that represents the entire population's characteristics.

---

### Example:

If we are studying the heights of all students in a school, the **population mean** would be the average height of every single student in the school. However, this population mean is typically unknown because it's not feasible to measure every student, so we use sample statistics (like the sample mean) to estimate it.

---

### Summary:

A population parameter is a value that describes a feature of the whole population, such as the population mean or population proportion. It is usually unknown, and we use sample statistics to estimate it.

</aside>

---