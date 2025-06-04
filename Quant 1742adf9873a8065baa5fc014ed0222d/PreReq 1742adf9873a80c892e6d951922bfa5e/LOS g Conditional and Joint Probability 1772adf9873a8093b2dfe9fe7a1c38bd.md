# LOS g Conditional and Joint Probability

> **Learning Outcome**
> 
> - *calculate and interpret an unconditional probability using the total probability rule*

---

![image.png](LOS%20g%20Conditional%20and%20Joint%20Probability%201772adf9873a8093b2dfe9fe7a1c38bd/image.png)

<aside>

### EXAMPLE 9

---

### ***BankCorp’s Earnings per Share (2)***

---

You are continuing your investigation into whether you can predict the direction of changes in BankCorp’s quarterly EPS. You define four events:

| **Event** | **Probability** |
| --- | --- |
| $*A*$ = *Change in sequential EPS is positive next quarter* | 0.55 |
| $*A^C*$ = *Change in sequential EPS is 0 or negative next quarter* | 0.45 |
| $*S*$ = *Change in sequential EPS is positive in the prior quarter* | 0.55 |
| $*S^C*$ = *Change in sequential EPS is 0 or negative in the prior quarter* | 0.45 |

---

On inspecting the data, you observe some persistence in EPS changes: Increases tend to be followed by increases, and decreases by decreases. The first probability estimate you develop is P(change in sequential EPS is positive next quarter | change in sequential EPS is 0 or negative in the prior quarter) = $P(A | S^C)$ = 0.40. The most recent quarter’s EPS (2Q:Year 1) is announced, and the change is a positive sequential change (the event *S*). You are interested in forecasting EPS for 3Q:Year 1.

1. **Write this statement in probability notation: “the probability that the change in sequential EPS is positive next quarter, given that the change in sequential EPS is positive the prior quarter.”**
    - Show Solution
        
        <aside>
        
        In probability notation, this statement is written $*P(\text{A | S}).*$
        
        </aside>
        
2. **Calculate the probability in Part 1. (Calculate the probability that is consistent with your other probabilities or beliefs.)**
    - Show Solution
        
        <aside>
        
        The probability is 0.673 that the change in sequential EPS is positive for 3Q:Year 1, given the positive change in sequential EPS for 2Q:Year 1, as shown below.
        
        According to Equation 5, *P*(*A*) = *P*(*A* | *S*)*P*(*S*) + *P*(*A* | *S*C)*P*(*S*C). The values of the probabilities needed to calculate *P*(*A* | *S*) are already known: *P*(*A*) = 0.55, *P*(*S*) = 0.55, *P*(*S*C) = 0.45, and *P*(*A* | *S*C) = 0.40. Substituting into Equation 5,0.55 = *P*(*A* | *S*)(0.55) + 0.40(0.45) Solving for the unknown, *P*(*A* | *S*) = [0.55 − 0.40(0.45)]/0.55 = 0.672727, or 0.673.
        
        You conclude that *P*(*change in sequential EPS is positive next quarter* | *change in sequential EPS is positive the prior quarter*) = 0.673. Any other probability is not consistent with your other estimated probabilities. Reflecting the persistence in EPS changes, this conditional probability of a positive EPS change, 0.673, is greater than the unconditional probability of an EPS increase, 0.55.
        
        </aside>
        

---

![image.png](LOS%20g%20Conditional%20and%20Joint%20Probability%201772adf9873a8093b2dfe9fe7a1c38bd/image%201.png)

</aside>

---