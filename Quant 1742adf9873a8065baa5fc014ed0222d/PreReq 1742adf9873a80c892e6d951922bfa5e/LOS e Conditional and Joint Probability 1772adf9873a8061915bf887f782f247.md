# LOS e Conditional and Joint Probability

> **Learning Outcome**
> 
> - *demonstrate the application of the multiplication and addition rules for probability*

---

![image.png](LOS%20e%20Conditional%20and%20Joint%20Probability%201772adf9873a8061915bf887f782f247/image.png)

### [EXAMPLE 3](https://study.cfainstitute.org/app/cfa-program-level-i-prerequisite-readings-for-2025#read/section/conditional-and-joint-probability-2)

---

![image.png](LOS%20e%20Conditional%20and%20Joint%20Probability%201772adf9873a8061915bf887f782f247/image%201.png)

<aside>
<img src="https://www.notion.so/icons/thought_gray.svg" alt="https://www.notion.so/icons/thought_gray.svg" width="40px" />

### **Interpretation**

---

| $P(B|A)$ | Probability of being a Year 2 Winner, given they were a Year 1 Winner | 0.66 |
| --- | --- | --- |
| $P(B^C|A)$ | Probability of being a Year 2 Loser, given they were a Year 1 Winner | 0.34 |
| $P(B|A^C)$ | Probability of being a Year 2 Winner, given they were a Year 1 Loser | 0.34 |
| $P(B^C|A^C)$ | Probability of being a Year 2 Loser, given they were a Year 1 Loser | 0.66 |

---

| $P(AB)$ | Probability of being a **Year 1 Winner** and a **Year 2 Winner** | 0.33 |
| --- | --- | --- |
| $P(AB^C)$ | Probability of being a **Year 1 Winner** and a **Year 2 Loser** | 0.17 |
| $P(A^CB)$ | Probability of being a **Year 1 Loser** and a **Year 2 Winner** | 0.17 |
| $P(A^CB^C)$ | Probability of being a **Year 1 Loser** and a **Year 2 Loser** | 0.33 |
</aside>

---

![image.png](LOS%20e%20Conditional%20and%20Joint%20Probability%201772adf9873a8061915bf887f782f247/image%202.png)

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Why $P(A \cap B) = P(B)$ in This Scenario

---

In the given context, $B$  (price dropping to $9.75) can only occur if $A$  (price dropping to $10) has already occurred. This means $B$ is entirely dependent on $A$ ), or equivalently, $B$  is a subset of $A$ . Mathematically, this relationship can be expressed as:

$$

P(A \cap B) = P(B)

$$

### Key Reason:

- $B$ happening implies $A$ has already happened. Therefore, the joint probability of $A$ and $B$ occurring together is simply the probability of $B$ itself, since $B$ cannot occur without $A$.

---

This is an important concept in dependent events where one event (here, $B$) is entirely contained within another event (here, $A$).

</aside>

<aside>
❌

### **Joint Probability $P(A \cap B)$ Explanation:**

---

In this scenario, event $A$ is the stock dropping to $10, and event $B$ is the stock dropping to $9.75. We need to calculate the joint probability $P(A \cap B)$, which represents the probability that both events occur — i.e., the stock first drops to $10, and then further drops to $9.75.

- **$P(A)=0.35$** is the probability of the stock dropping to $10.
- **$P(B∣A)=0.25$** is the conditional probability of the stock dropping to $9.75, given that it has already dropped to $10.

---

**Why $P(A∩B)=0.25$:**

1. **Conditional Nature of $B$**: The event $B$ (stock dropping to $9.75) can only occur if $A$ (stock dropping to $10) has already occurred. Therefore, $B$ is conditional on $A$.
2. **Conditional Probability**: The probability $P(B∣A)$ (the probability of dropping to $9.75 after dropping to $10) is already provided as 0.25.
3. **Joint Probability and Conditional Probability**: Normally, for joint probability $P(A∩B)$, we would use the formula:
    
    
    $P(A∩B)=P(A)×P(B∣A)$
    
    However, in this case, $P(B∣A)=0.25$ is already the probability of both events happening (first dropping to $10, then dropping to $9.75). There is no need to multiply it by $P(A)$ because $P(B∣A)$ inherently includes the dependency of $B$ on $A$. So, the joint probability is **0.25**, not the product of $P(A)$ and $P(B∣A)$.
    

---

**Key Takeaways:**

- **Conditional probability** $P(B∣A)$ is used to represent the likelihood of $B$ occurring given that $A$ has occurred.
- Since $P(B∣A)=0.25$ already accounts for the probability of both events occurring, the joint probability $P(A∩B)$ is **0.25**, not the product of individual probabilities.

---

Thus, we didn’t multiply $P(A)$ and $P(B∣A)$ because $P(B∣A)$ already represents the joint occurrence of both events.

</aside>

---