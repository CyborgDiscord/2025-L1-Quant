# LOS e Binomial Distribution

> **Learning Outcome**
> 
> - *describe the properties of a Bernoulli random variable and a binomial random variable, and calculate and interpret probabilities given the binomial distribution function*

---

### Page **`35-4`**

---

### Page **`36-5` to** `36-6`

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Binomial Probability Formula

---

### Binomial Distribution Overview

A binomial distribution models the number of **successes** (denoted as **X**) in a fixed number of **independent trials** (denoted as **n**), each with the same probability of success (**p**). The two key parameters are:

- **n**: Number of trials (fixed)
- **p**: Probability of success in each trial

---

### Key Concept: **"Number of Ways" and "Probability"**

The probability of a specific outcome in a binomial distribution depends on two things:

1. **The number of ways you can get a certain number of successes** (this is often calculated using combinations).
2. **The probability of each specific outcome occurring** (success or failure in each trial).

Now, let's break this into parts:

---

### 1. **Number of Ways to Get X Successes**: (Combinatorics)

The first part of the formula calculates **how many different ways** you can achieve exactly **X successes** in **n trials**. This is the **combinatorics** part of the binomial formula, and it is calculated using combinations. Combinations tell you how many ways you can select a certain number of items (in this case, successes) from a larger group (in this case, all the trials).

The formula for combinations is:

- $\binom{n}{x} = \frac{n!}{x!(n - x)!}$

This gives you the number of different ways you can select **X successes** from **n trials**.

### 2. **Probability of Each Outcome**: (Multiplying Probabilities)

Next, you need to calculate the **probability of any specific outcome** where you have **X successes** and **n - X failures**:

- For **each success**, the probability is $p$.
- For **each failure**, the probability is $(1−p)$.

So, for a specific sequence of outcomes (for example, a success, a failure, a success, etc.), the probability is:

- $p^X \times (1 - p)^{(n - X)}$

This gives the probability of a specific sequence where there are **X successes** and **n - X failures**.

---

### Combining Both Parts:

To find the total probability of getting exactly **X successes** out of **n trials**, you multiply the **number of ways** to get **X successes** by the **probability** of each specific outcome:

$P(X = x) = \binom{n}{x} \cdot p^x \cdot (1 - p)^{n - x}$

This formula combines the combinatorics (to count the number of ways) and the probabilities (to account for the chance of each outcome) to give you the total probability.

---

### Why This Makes Sense:

- **The number of ways** is important because there are multiple possible sequences of trials that can result in exactly **X successes**. For example, in 3 trials, you can have the following sequences of successes (denoted by "S") and failures (denoted by "F"):
    - S, S, F
    - S, F, S
    - F, S, S

All of these represent 2 successes and 1 failure, and we need to count all such possible sequences.

- **The probability** is important because each specific sequence of successes and failures has a certain chance of occurring. For instance, in the sequence **S, S, F**, the probability is $p×p×(1−p)$. For each of the other possible sequences, you multiply the probabilities in the same way.

---

### Example:

If you have 3 trials, and the probability of success is 0.5 (i.e., $p = 0.5$), and you want to find the probability of getting **2 successes**:

1. **Number of ways to get 2 successes**: This is calculated by the combination formula $\binom{3}{2} = 3$. There are 3 ways to get 2 successes in 3 trials.
2. **Probability of each sequence with 2 successes**: The probability for each specific sequence with 2 successes and 1 failure is:
    - $p^2 \times (1 - p)^{1} = 0.5^2 \times 0.5 = 0.125$
3. **Total probability**: Multiply the number of ways (3) by the probability of each sequence (0.125):
    - $3 \times 0.125 = 0.375$.

So, the probability of getting exactly 2 successes in 3 trials is 0.375.

---

### Why Not Just Probability Alone?

If you were to use just the probability, without considering how many ways those successes can occur, you'd only be looking at a single specific sequence. But there are multiple sequences that can give you the same result, and you need to account for all of them to get the total probability.

---

### Summary:

- The **number of ways** (combinations) is calculated to account for all the different possible sequences of successes and failures.
- The **probability** of each sequence is calculated based on the chance of success and failure in each trial.
- By multiplying both together, you get the total probability of having exactly **X successes** in **n trials**.

---

This way, you understand that the probability of a binomial distribution isn't just about one sequence, but about all possible sequences that could lead to the same number of successes.

</aside>

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Why Binomial Distribution Uses Combinations and Not Permutations?

---

In binomial distribution, we are interested in the number of successes (and failures) over a fixed number of trials, but **the order in which the successes occur does not matter**. This is a key distinction from permutation problems, where order is important.

### Key Point:

- **In a binomial experiment**, the number of successes is all that matters. We want to count how many ways we can achieve a specific number of successes in a set number of trials, **regardless of the order** in which those successes occur.

### Why Combinations (C) are Used:

- Since the order of the successes doesn't matter, we're only concerned with how many ways we can choose 2 successes out of 5 trials, without caring about where they occur in the sequence. This is exactly what combinations do: they count how many ways we can select a subset of items (in this case, successes) from a larger set (the total trials), ignoring the order of selection.

### Why Not Permutations (P):

- **Permutations** would be used if the order mattered, as they count the number of distinct arrangements of the successes in the trials. In a binomial experiment, however, the number of arrangements doesn't change the outcome; we simply need to know how many successes occurred, regardless of when they happened in the sequence.
</aside>

---

### Page **`36-6`**

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Explanation for Different Probabilities:

---

In binomial distribution, the shape of the graph depends on the **probability of success (p)** and the number of trials (**n**). The binomial distribution models the number of successes in a fixed number of trials, where each trial has two possible outcomes (success or failure), and the probability of success remains constant across trials.

---

1. **When $p=0.5$ (Symmetrical Distribution):**
    - The graph is symmetrical because the probability of success is equal to the probability of failure (0.5).
    - This symmetry happens because, when $p=0.5$, the distribution is balanced, meaning that the number of successes and failures are equally likely to occur.
    - For example, if we have 5 trials, the probabilities of having 0, 1, 2, 3, 4, or 5 successes are evenly distributed around the middle (2.5 successes). In this case, we tend to get an equal chance for success or failure in any given trial, so the graph looks like a bell curve.
2. **When $p = 0.1$ (Skewed to the Right):**
    - The graph is skewed to the left because the probability of success is much smaller than the probability of failure (0.1 vs. 0.9).
    - This means that failures are more likely to occur than successes, so the distribution has a higher probability of getting fewer successes, especially close to 0.
    - In the case of 5 trials, the probability of 0 successes is the highest, and the probability decreases as we move towards 5 successes. Hence, the distribution is **right-skewed**, with most of the probability mass concentrated around the lower numbers of successes.
3. **When $p=0.9$ (Skewed to the Left):**
    - The graph is skewed to the left because the probability of success is much larger than the probability of failure (0.9 vs. 0.1).
    - Here, successes are much more likely to occur than failures, so the distribution is more likely to show a higher number of successes.
    - In the case of 5 trials, the probability of getting 5 successes is the highest, and the probability decreases as we move towards 0 successes. Therefore, the distribution is **left-skewed**, with most of the probability mass concentrated around the higher numbers of successes.

---

### Summary:

- **Symmetrical ($p=0.5$):** Equal probability of success and failure results in a balanced, bell-shaped curve.
- **Right-skewed ($p=0.1$):** A higher likelihood of failures compared to successes results in most of the probability being concentrated near the lower number of successes.
- **Left-skewed ($p=0.9$):** A higher likelihood of successes compared to failures results in most of the probability being concentrated near the higher number of successes.

In essence, the graph's shape is determined by the balance between the likelihood of successes and failures. The closer $p$ is to 0 or 1, the more skewed the distribution becomes. When $p=0.5$, the distribution is perfectly symmetrical.

---

*Here's the visualization of the binomial distribution for $n=5$ trials with different probabilities of success ($p = 0.1, 0.5, 0.9$):*

![image.png](LOS%20e%20Binomial%20Distribution%201782adf9873a80bab62dea0fd76f41be/image.png)

</aside>

<aside>
<img src="https://www.notion.so/icons/help-alternate_gray.svg" alt="https://www.notion.so/icons/help-alternate_gray.svg" width="40px" />

### Calculation of Different Probabilities:

---

To calculate the probability of getting exactly **1 success** in **5 trials** (n = 5) with different probabilities of success **(p = 0.5, 0.1, 0.9)**, we will use the **binomial probability formula**:

---

### Binomial Probability Formula:

$$
P(X = k) = \binom{n}{k} \cdot p^k \cdot (1 - p)^{n - k}
$$

Where:

- $n$ = number of trials (in this case, 5)
- $k$ = number of successes (in this case, 1)
- $p$ = probability of success (given as 0.5, 0.1, 0.9)
- $(1−p)$ = probability of failure (the complement of success)

---

### Step 1: Find the number of ways to get exactly 1 success out of 5 trials using the combination formula:

$$
\binom{n}{k} = \binom{5}{1} = 5
$$

---

### Step 2: Now, calculate the probability for each value of **p**.

### Case 1: **p = 0.5**

$$
P(X = 1) = \binom{5}{1} \cdot 0.5^1 \cdot (1 - 0.5)^{5 - 1}
$$

$$
P(X = 1) = 5 \cdot 0.5 \cdot 0.5^4 = 5 \cdot 0.5 \cdot 0.0625 = 0.15625
$$

### Case 2: **p = 0.1**

$$
P(X = 1) = \binom{5}{1} \cdot 0.1^1 \cdot (1 - 0.1)^{5 - 1}
$$

$$
P(X = 1) = 5 \cdot 0.1 \cdot 0.9^4 = 5 \cdot 0.1 \cdot 0.6561 = 0.32805
$$

### Case 3: **p = 0.9**

$$
P(X = 1) = \binom{5}{1} \cdot 0.9^1 \cdot (1 - 0.9)^{5 - 1}
$$

$$
P(X = 1) = 5 \cdot 0.9 \cdot 0.1^4 = 5 \cdot 0.9 \cdot 0.0001 = 0.00045
$$

---

### Final Answers:

- When **p = 0.5**, the probability of exactly 1 success is **0.15625**.
- When **p = 0.1**, the probability of exactly 1 success is **0.32805**.
- When **p = 0.9**, the probability of exactly 1 success is **0.00045**.
</aside>

---

### Page **`37-7`**

### [EXAMPLE 3](https://study.cfainstitute.org/app/cfa-program-level-i-prerequisite-readings-for-2025#read/section/binomial-distribution-3)

<aside>
<img src="https://www.notion.so/icons/star_yellow.svg" alt="https://www.notion.so/icons/star_yellow.svg" width="40px" />

### **Why a Fair Price Implies 50% Probability of a Profitable Trade?**

---

In a fair market, the price you pay for an asset is balanced, meaning there's no inherent advantage or disadvantage to either side of the trade. Since price changes are assumed to be random and unbiased, half of the time the price will go up (profit), and half the time it will go down (loss). Therefore, the probability of a profitable trade is **50%**, as there's an equal chance of the price increasing or decreasing.

</aside>

<aside>
<img src="https://www.notion.so/icons/thought_gray.svg" alt="https://www.notion.so/icons/thought_gray.svg" width="40px" />

### **Interpretation (Page 37-7, Q:3A)**

---

> *“It means:
if this block trader was giving us a fair deal,
so that we would have no bias to see wins and no bias to see losses,
we would only see 3 profitable trades out of 12,
7.3% of the time.”*
> 

> *“There's only 7.3% probability,
that if you're giving me a fair deal,
that I would be losing this badly.”*
> 
</aside>

---

### Page **`37-8`**

**Formula:**

|  | Mean | Variance |
| --- | --- | --- |
| Bernoulli | $p$ | $p(1-p)$ |
| Binomial | $np$ | $np(1-p)$ |

---