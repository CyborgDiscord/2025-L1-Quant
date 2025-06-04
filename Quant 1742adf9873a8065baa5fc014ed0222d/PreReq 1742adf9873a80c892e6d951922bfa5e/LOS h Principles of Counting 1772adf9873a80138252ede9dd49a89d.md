# LOS h Principles of Counting

> **Learning Outcome**
> 
> - *identify the most appropriate method to solve a particular counting problem and analyze counting problems using factorial, combination, and permutation concepts*

---

![image.png](LOS%20h%20Principles%20of%20Counting%201772adf9873a80138252ede9dd49a89d/image.png)

![image.png](LOS%20h%20Principles%20of%20Counting%201772adf9873a80138252ede9dd49a89d/image%201.png)

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### **Explanation: Each analyst is assigned to exactly one industry**

---

This is a permutation problem as described earlier. There are $3!=6$ ways to assign analysts to industries:

1. Analyst 1 → Industry A, Analyst 2 → Industry B, Analyst 3 → Industry C.
2. Analyst 1 → Industry A, Analyst 2 → Industry C, Analyst 3 → Industry B.
3. Analyst 1 → Industry B, Analyst 2 → Industry A, Analyst 3 → Industry C.
4. Analyst 1 → Industry B, Analyst 2 → Industry C, Analyst 3 → Industry A.
5. Analyst 1 → Industry C, Analyst 2 → Industry A, Analyst 3 → Industry B.
6. Analyst 1 → Industry C, Analyst 2 → Industry B, Analyst 3 → Industry A.
</aside>

![image.png](LOS%20h%20Principles%20of%20Counting%201772adf9873a80138252ede9dd49a89d/image%202.png)

<aside>
<img src="https://www.notion.so/icons/star_yellow.svg" alt="https://www.notion.so/icons/star_yellow.svg" width="40px" />

### NOTE

---

### $k = 1$: **Factorial**

- **Meaning**: You are arranging all items in a single group.
- **Formula**: $n!$ (factorial of $n$).
- **Example**: If there are 5 books, how many ways can they be arranged on a shelf? The answer is $5!=120$.
- **Why $k=1$**: There's just one group to arrange, so the factorial represents all possible arrangements of the items.

---

### $k=2$: **Combination or Permutation**

- **Meaning**: You are selecting or arranging items between two groups (e.g., chosen vs. not chosen, selected vs. unselected).
    - **Combination**: Order does *not* matter.
    - **Permutation**: Order *does* matter.
- **Formulas**:
    - Combination: $\binom{n}{r} = \frac{n!}{r!(n-r)!}$
    - Permutation: $P(n, r) = \frac{n!}{(n-r)!}$
- **Example**:
    - Combination: Selecting 2 people out of 5 for a committee (order doesn’t matter).
    - Permutation: Assigning 2 positions (e.g., president and VP) from 5 people (order matters).
- **Why $k=2$**: The items are divided into two groups—those selected and those not selected.

---

### $k \geq 3$: **Multinomial**

- **Meaning**: You are dividing items into three or more distinct groups.
- **Formula**:
    
    $\text{Multinomial coefficient} = \frac{n!}{n_1! \cdot n_2! \cdot \ldots \cdot n_k!}$
    
    Where $n = n_1 + n_2 + \ldots + n_k$.
    
- **Example**: You have 10 balls, and you want to divide them into 3 groups with 3, 4, and 3 balls in each group. The number of ways to do this is:
    
    $\frac{10!}{3! \cdot 4! \cdot 3!}$
    
- **Why $k \geq 3$**: The items are distributed into three or more groups, requiring the multinomial formula.

---

### Summary:

- The value of $k$ determines the principle:
    - $k=1$: Factorial (arranging all items).
    - $k=2$: Permutation or combination (dividing into two groups or selecting items).
    - $k \geq 3$: Multinomial (dividing into three or more groups).
</aside>

<aside>
⭐

### NOTE

---

- **n** is the **total number of items** or elements available to choose from.
- **r** is the **number of items** you are selecting or choosing.
</aside>

---

<aside>

### EXAMPLE 17

---

### *Permutations and Combinations for Two Out of Four Outcomes ****(EXAMPLE 10)*

---

There are four balls numbered 1, 2, 3, and 4 in a basket. You are running a contest in which two of the four balls are selected at random from the basket. To win, a player must have correctly chosen the numbers of the two randomly selected balls. Suppose the winning numbers are numbers 1 and 3. If the player must choose the balls in the same order in which they are drawn, she wins if she chose 1 first and 3 second. On the other hand, if order is not important, the player wins if the balls drawn are 1 and then 3 or if the balls drawn are 3 and then 1. The number of possible outcomes for permutations and combinations of choosing 2 out of 4 items is illustrated in [Exhibit 8](LOS%20h%20Principles%20of%20Counting%201772adf9873a80138252ede9dd49a89d.md). If order is not important, for choosing 2 out of 4 items, the winner wins twice as often.

<aside>

### Exhibit 8:

**Permutations and Combinations for Choosing 2 out of 4 Items**

---

<aside>

**Permutations: Order matters**

---

List of all possible outcomes:

(1 2) (2 1) (3 1) (4 1)

(1 3) (2 3) (3 2) (4 2)

(1 4) (2 4) (3 4) (4 3)

---

Number of permutations:

$_nP_r=\frac{n!}{(n−r)!}$

$_4P_2=\frac{4!}{(4−2)!}$

$=\frac{4×3×2×1}{2×1}=12$

**Combinations: Order does not matter**

---

List of all possible outcomes:

(1 2) (2 3) (3 4)

(1 3) (2 4)

(1 4)

---

Number of combinations:

$_nC_r=\frac{n!}{(n−r)!r!}$

$_4C_2=\frac{4!}{(4−2)!2!}$

$=\frac{4×3×2×1}{2×1×2×1}=6$

</aside>

</aside>

If order is important, the number of permutations (possible outcomes) is much larger than the number of combinations when order is not important.

</aside>

<aside>

### EXAMPLE 18

---

### *Reorganizing the Analyst Team Assignments ****(EXAMPLE 11)*

---

Gehr-Flint Investors classifies the stocks in its investment universe into 11 industries and is assigning each research analyst one or two industries. Five of the industries have been assigned, and you are asked to cover two industries from the remaining six.

---

How many possible pairs of industries remain?

**A.** 12

**B.** 15

**C.** 36

- Show Solution
    
    <aside>
    
    B is correct. The number of combinations of selecting two industries out of six is equal to
    
    $_𝑛𝐶_𝑟=[\frac{n}{r}]=\frac{𝑛!}{(𝑛−𝑟)!𝑟!}=\frac{6!}{4!2!}=15$
    
    The number of possible combinations for picking two industries out of six is 15.
    
    </aside>
    
</aside>

<aside>

### EXAMPLE 19

---

### ***Australian Powerball Lottery** (EXAMPLE 12)*

---

To win the Australian Powerball jackpot, you must match the numbers of seven balls pulled from a basket (the balls are numbered 1 through 35) plus the number of the Powerball (numbered 1 through 20). The order in which the seven balls are drawn is not important.

- Show Solution
    
    <aside>
    
    The number of combinations of matching 7 out of 35 balls is
    
    $_nC_r=[\frac{n}{r}]=\frac{n!}{(n−r)!r!}=\frac{35!}{28!7!}=6,724,520$
    
    The number of combinations for picking the Powerball, 1 out of 20, is
    
    $_nC_r=[\frac{n}{r}]=\frac{n!}{(n−r)!r!}=\frac{20!}{19!1!}=20$
    
    The number of ways to pick the seven balls plus the Powerball is
    
    $_{35}C_7×_{20}C_1=6,724,520×20=134,490,400$
    
    Your probability of winning the Australian Powerball with one ticket is **1** in **134,490,400**.
    
    </aside>
    
</aside>

<aside>

### Exhibit 9:

**Summary of Counting Methods**

---

![CFA0126-R-EXH23_1.jpg](LOS%20h%20Principles%20of%20Counting%201772adf9873a80138252ede9dd49a89d/CFA0126-R-EXH23_1.jpg)

</aside>

---