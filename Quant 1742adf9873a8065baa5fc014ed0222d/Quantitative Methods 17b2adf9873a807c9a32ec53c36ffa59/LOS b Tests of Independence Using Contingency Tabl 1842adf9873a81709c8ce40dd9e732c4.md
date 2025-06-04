# LOS b Tests of Independence Using Contingency Table Data

> **Learning Outcome**
> 
> - *explain tests of independence based on contingency table data*

---

pg 47-3 to 48-5 (formulas not in formula sheet)

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### **Chi-Square Test of Independence**

---

The **Chi-Square Test of Independence** is a statistical method used to determine if there is a significant association between two categorical variables. Let's break down each part of your question for clarity:

---

### **1. What does independent and dependent mean in this context?**

- **Independent**: Two variables are independent if the occurrence of one variable does not influence the occurrence of the other. For example, in a survey of people, their gender and their preference for a type of movie might be independent.
- **Dependent**: Two variables are dependent if the occurrence of one variable is related to the occurrence of the other. For instance, gender might influence movie preferences in some way (e.g., males preferring action and females preferring romance).

The Chi-Square Test checks whether there is enough evidence to conclude that the two variables are **not independent** (i.e., they are dependent).

---

### **2. What are we calculating, and to prove what?**

- We calculate the **Chi-Square statistic** (), which measures the discrepancy between the observed frequencies and the expected frequencies under the assumption of independence.
    
    χ2\chi^2
    
- The goal is to determine whether the differences between observed and expected frequencies are large enough to suggest that the two variables are dependent.

### **Steps in the test:**

1. **Observed frequencies** (OO): These are the actual counts in each category of the two variables.
2. **Expected frequencies** (EE): These are the counts we would expect if the two variables were independent, calculated as:
    
    E=(row total)×(column total)grand totalE = \frac{\text{(row total)} \times \text{(column total)}}{\text{grand total}}
    
3. Compute the Chi-Square statistic:
    
    χ2=∑(O−E)2E\chi^2 = \sum \frac{(O - E)^2}{E}
    
4. Compare the calculated χ2\chi^2 value to a critical value from the Chi-Square distribution table (based on degrees of freedom and significance level) to decide whether to reject the null hypothesis.

### **Null hypothesis (H0H_0):**

- The two variables are independent (no association).

### **Alternative hypothesis (HAH_A):**

- The two variables are dependent (an association exists).

---

### **3. What does standardized residuals mean?**

Standardized residuals help us understand which specific cells in the table contribute most to the Chi-Square statistic.

### Formula for standardized residuals:

Standardized Residual=O−EE\text{Standardized Residual} = \frac{O - E}{\sqrt{E}}

- **Interpretation**:
    - A standardized residual shows how much the observed frequency differs from the expected frequency in standard deviation units.
    - Values far from 0 (e.g., greater than 2 or less than -2) indicate cells where the observed count deviates significantly from the expected count, suggesting that these categories are particularly contributing to the dependency.

### Example:

If you are studying gender and movie preferences, and the standardized residual for males preferring action movies is 3.5, this suggests that males are much more likely to prefer action movies than expected under independence.

---

### **Summary**

- The Chi-Square Test of Independence checks whether two categorical variables are associated or independent.
- Independence means the variables do not influence each other, while dependence indicates a relationship.
- We calculate the  statistic by comparing observed and expected frequencies.
    
    χ2\chi^2
    
- Standardized residuals reveal which specific categories (cells) are most responsible for the relationship (if one exists).

If you’d like, I can provide a simple example with numbers to clarify this further!

</aside>

[EXAMPLE 4](https://study.cfainstitute.org/app/cfa-program-level-i-for-august-2025#read/section/tests-of-independence-using-contingency-table-data-1) + [Question Set](https://study.cfainstitute.org/app/cfa-program-level-i-for-august-2025#read/section/tests-of-independence-using-contingency-table-data-1)

---

Comments

Ans 1. Let’s take an example: In a survey of movie preferences, we calculate how many males prefer action movies compared to what we'd expect if gender and preference were independent. 

A positive residual (more than expected) means more males prefer action movies. A negative residual (less than expected) means more males avoid or do not prefer action movies. Both deviations indicate dependence, showing that gender affects movie preference, rather than the two being independent.

---

Ans 2. Without standardizing, residuals may be harder to interpret. Standardizing adjusts for differences in expected values, allowing us to compare across categories. It puts deviations on the same scale, making it easier to identify significant differences.

---