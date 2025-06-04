# LOS e The Role of p-Values

> **Learning Outcome**
> 
> - *explain and interpret the p-value as it relates to hypothesis testing*

---

- pg 51-7
    
    <aside>
    <img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />
    
    ### $p$-Value is the lowest $\alpha$ at which the null can be rejected
    
    ---
    
    ### **1. What is Alpha (α)?**
    
    - **Alpha (α)** is the significance level you set before performing a hypothesis test.
    - It represents the probability of rejecting the null hypothesis when it’s actually true (Type I error).
    - Typically, **alpha is set to 0.05**, which means a 5% chance of making a Type I error.
    
    ### **2. What is the P-Value?**
    
    - The **p-value** is the probability of observing a test statistic as extreme (or more extreme) than the one you actually observed, assuming the null hypothesis is true.
    - The smaller the p-value, the stronger the evidence against the null hypothesis.
    
    ### **3. The Key Relationship Between P-Value and Alpha**
    
    - In hypothesis testing, you **reject the null hypothesis** if the **p-value is smaller than or equal to alpha** (α).
    - The p-value tells you the **smallest alpha level** at which you can reject the null hypothesis.
    
    ### **4. Breaking It Down**
    
    - **The p-value is the smallest level of alpha at which you would reject the null hypothesis**.
        - If you get a **p-value of 0.03**, it means you can reject the null hypothesis at an alpha level of **0.03 or higher**. But if you had set **alpha to 0.05**, you would still reject the null because 0.03 < 0.05.
        - If the **p-value is 0.10**, you **cannot reject** the null hypothesis at **alpha = 0.05**, because 0.10 > 0.05.
    
    ### **5. Simple Example**
    
    - Imagine you’re conducting a test with an alpha level of 0.05.
    - After performing the test, you get a p-value of 0.03.
        - This means **the lowest alpha at which you can reject the null hypothesis is 0.03**.
        - Since 0.03 is less than your alpha of 0.05, you reject the null hypothesis.
    - Now imagine the p-value you get is 0.08.
        - This means the **lowest alpha at which you can reject the null hypothesis is 0.08**, but since your alpha was 0.05, **you fail to reject the null hypothesis**.
    
    ### **6. Why Is This Important?**
    
    - The p-value helps you determine **how strong the evidence is** against the null hypothesis.
    - The **lower the p-value**, the more evidence you have to reject the null hypothesis.
    
    ---
    
    ### **Summary**
    
    The p-value is the **smallest alpha level** at which you can reject the null hypothesis. If your p-value is smaller than your alpha, you reject the null. If it’s larger, you fail to reject the null. This relationship helps you decide whether your results are statistically significant.
    
    </aside>
    
    > *If your p-value is smaller than alpha (α), you reject the null hypothesis; if it’s larger, you don’t reject it.*
    > 
    > 
    > <aside>
    > <img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />
    > 
    > ### Simplified
    > 
    > ---
    > 
    > ### **What is the P-value?**
    > 
    > - The **p-value** tells you how likely it is to get your test result (or something more extreme) **if the null hypothesis is true**.
    > - A **small p-value** means it's very unlikely that the result you got happened by chance, assuming the null hypothesis is true.
    > - A **large p-value** means it's more likely your result could have happened by chance, so you don't have strong evidence to reject the null hypothesis.
    > 
    > ### **What is Alpha (α)?**
    > 
    > - **Alpha** is a number you choose before the test (like 0.05 or 5%).
    > - It’s the level of risk you're willing to accept for making a **Type I error**—which means rejecting the null hypothesis when it is actually true.
    > - If alpha is 0.05, you're saying, "I’m okay with a 5% chance of rejecting the null hypothesis incorrectly."
    > 
    > ### **How Does P-value Help?**
    > 
    > - The p-value shows you the **smallest alpha** at which you can reject the null hypothesis.
    > - If your p-value is **smaller than alpha**, you reject the null hypothesis.
    > - If your p-value is **larger than alpha**, you **do not** reject the null hypothesis.
    > 
    > ---
    > 
    > ### **Why Is P-value the Lowest Alpha for Rejection?**
    > 
    > - Imagine you set alpha to 0.05, which means you’re willing to accept a 5% chance of making a mistake by rejecting the null hypothesis when it’s true.
    > - If the p-value is **0.03**, this means there is a **3% chance** of getting your result (or something more extreme) if the null hypothesis is true.
    > - Since **0.03 < 0.05**, it’s a **small enough p-value** to reject the null hypothesis at **alpha = 0.05**.
    > - The p-value tells you **the smallest alpha** at which you can reject the null hypothesis. In this case, it's 0.03, so you could reject the null hypothesis even at a stricter alpha (say 0.01), but **not at 0.05**.
    > 
    > ---
    > 
    > ### **Simple Example:**
    > 
    > - You perform a test and calculate the p-value as 0.02.
    > - You’ve set alpha to 0.05 before the test.
    >     - Since 0.02 is **smaller** than 0.05, you **reject the null hypothesis**.
    > - If the p-value were 0.08, you **would not reject** the null hypothesis because 0.08 is **larger** than 0.05.
    > 
    > ---
    > 
    > ### **In Short:**
    > 
    > - The **p-value** helps you decide whether the evidence is strong enough to **reject the null hypothesis**.
    > - It shows the **smallest alpha level** where you could reject the null hypothesis. If your p-value is smaller than alpha, you reject the null hypothesis; if it’s larger, you don’t reject it.
    > </aside>
    > 
    > <aside>
    > <img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />
    > 
    > ### Simplified 2 (Better explained)
    > 
    > ---
    > 
    > If the **p-value** is lower than the **alpha** value, it implies there is even **less risk** than you initially set (**α**) for rejecting the null hypothesis. 
    > 
    > ---
    > 
    > Here's a more detailed breakdown:
    > 
    > ### Here's how to think about it:
    > 
    > - **Alpha (α)** is the threshold you set before conducting the test, representing the risk (probability) you're willing to take in making a mistake by rejecting the null hypothesis when it is actually true.
    > - **P-value** is the probability of observing the test results (or more extreme results) if the null hypothesis is true. Essentially, it's how likely your result is under the assumption that the null hypothesis is correct.
    > 
    > ---
    > 
    > ### So, when:
    > 
    > - **p-value < alpha**: The probability of obtaining the observed result is lower than the threshold you originally set (alpha). This means you have strong evidence against the null hypothesis, so you **reject the null hypothesis**. In this case, the risk of making an error (rejecting a true null hypothesis) is smaller than what you were willing to accept.
    > - **p-value > alpha**: The observed result is more likely under the null hypothesis, and you fail to reject the null hypothesis. The risk of making an error is higher than the threshold you set, so you don't reject the null.
    > 
    > ---
    > 
    > ### Example:
    > 
    > - If **alpha = 0.05** (5%) and you get a **p-value of 0.02**, the p-value is less than alpha, meaning your result is less likely to happen by chance (there's only a 2% chance of seeing this result if the null hypothesis is true). This would lead you to **reject the null hypothesis**.
    > 
    > In summary:
    > 
    > - A **lower p-value** than **alpha** means you're even more confident that the null hypothesis is not true, implying **less risk of making a wrong decision** in rejecting it.
    > </aside>
    > 
    > ---
    > 
    
    <aside>
    <img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />
    
    ### Alpha ($\alpha$)
    
    ---
    
    ### **Why Do We Use Alpha?**
    
    - **Alpha (α)** is a threshold we set before conducting a hypothesis test to control the risk of making a **Type I error**, which is rejecting a true null hypothesis (i.e., calling something false when it is actually true).
    - By setting **alpha**, we decide how much risk we are willing to accept in making that error.
    
    ---
    
    ### **Reducing Alpha to Minimize Errors**
    
    - If we set **alpha = 0.05**, we’re saying there’s a **5% chance** of rejecting the null hypothesis when it’s actually true (Type I error).
    - If we reduce **alpha** (for example, to **0.01**), we are **reducing the risk** of rejecting the null hypothesis incorrectly (i.e., calling something false when it is true). This means we are being more **conservative** in making our decision.
    
    ---
    
    ### **Key Point**
    
    - **By lowering alpha**, we make it **harder to reject the null hypothesis**, which reduces the chances of making a Type I error. However, this also increases the chances of making a **Type II error** (failing to reject a false null hypothesis).
    - So, it's all about finding a **balance** between being careful not to reject something true and not missing out on rejecting something false.
    
    ---
    
    ### Summary
    
    Yes, by reducing **alpha**, we minimize the chances of making a Type I error, but we also need to keep in mind the possibility of **Type II errors** (which is rejecting a false null hypothesis when we should). The choice of alpha is about how much risk we’re willing to take in each direction.
    
    </aside>
    

---

pg 51-8

<aside>

### [EXAMPLE 5](https://study.cfainstitute.org/app/cfa-program-level-i-prerequisite-readings-for-2025#read/section/the-role-of-p-values-1)

---

### **Making a Decision Using *p*-Values**

---

An analyst is testing the hypotheses $*H_0: σ^2 = 0.01*$ versus $*H_a: σ^2 ≠ 0.01*$. Using software, she determines that the *p*-value for the test statistic is 0.03, or 3%. Which of the following statements is correct?

**A. ****Reject the null hypothesis at both the 1% and 5% levels of significance.

**B.** Reject the null hypothesis at the 5% level but not at the 1% level of significance.

**C.** Fail to reject the null hypothesis at both the 1% and 5% levels of significance.

- Show Solution
    
    <aside>
    
    B is correct. Rejection of the null hypothesis requires that the *p*-value be less than the level of significance. On the basis of this requirement, the null is rejected at the 5% level of significance but not at the 1% level of significance.
    
    </aside>
    
</aside>

---