# LOS b Tests of Return and Risk in Finance

> **Learning Outcome**
> 
> - *construct hypothesis tests and determine their statistical significance, the associated Type I and Type II errors, and power of the test given a significance level*

---

[video 18:09](https://www.markmeldrum.com/courses/2025-level-i/lessons/2025-l1-quantitative-methods/topic/2025-l1-qm-lm8-video/)

[EXAMPLE 1 to 3](https://study.cfainstitute.org/app/cfa-program-level-i-for-august-2025#read/section/tests-of-return-and-risk-in-finance-1) [Question Set](https://study.cfainstitute.org/app/cfa-program-level-i-for-august-2025#read/section/tests-of-return-and-risk-in-finance-1)

---

An analyst examines 30 paired monthly returns for two stock indexes. To determine if the mean difference of the returns is zero, the number of degrees of freedom of the *t*-test is:

1. A.28.
2. B.29.
3. C.58.

**Solution**
1. Incorrect because the *t*-statistic for a paired comparisons test has *n* – 1 degrees of freedom, not *n* – 2 degrees of freedom, where *n* is the number of pairs of observations. When *n* = 30, the number of degrees of freedom is 30 – 1 = 29, not 30 – 2 = 28.
2. **Correct** because the *t*-statistic for a paired comparisons test has *n* – 1 degrees of freedom, where *n* is the number of pairs of observations. When *n* = 30, the number of degrees of freedom is 30 – 1 = 29.
3. Incorrect because this is the number of degrees of freedom of the *t*-statistic for a hypothesis test concerning the equality of the population means of two independent samples, which is *n*1 + *n*2 − 2. When both *n*1 and *n*2 is 30, the number of degrees of freedom of the *t*-statistic for a hypothesis test concerning the equality of the population means of two independent samples is 30 + 30 − 2 = 58.

---

Given a large random sample, which of the following types of data are *least* appropriately analyzed with nonparametric tests?

1. A.Signed data (e.g., number of positives and negatives)
2. B.Ranked data (e.g., 1st, 3rd)
3. C.Numerical values (e.g., 28.43, 79.11)

**Solution**
1. Incorrect. Nonparametric tests can be used on grouped or counted data.
2. Incorrect. Nonparametric tests can be used on ranked data.
3. **Correct**. Nonparametric tests are primarily concerned with ranks, signs, or groups, and they are used when numerical parameters are not known or do not meet assumptions about distributions. Even if the underlying distribution is unknown, parametric tests can be used on numerical data if the sample is large.

---