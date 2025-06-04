# LOS d Demonstrate (Retirement Income)

- **Step 1** (Calculate $FV_{15}$)
    
    ```jsx
    N = 15
    I/Y = 8
    PV = 0
    PMT = 2000
    CPT -> FV
    
    STO -> 1
    ```
    
    ---
    
- **Step 2** (Calculate $PV_{40}$)
    
    *Ordinary annuity*
    
    ```jsx
    N = 20
    I/Y = 8
    PMT = 100,000
    FV = 0
    CPT -> PV
    
    STO -> 2
    ```
    
    ---
    
- **Step 3** (Calculate `PMT`)
    
    ```jsx
    N = 25 (t=15 to t=40)
    I/Y = 8
    PV = FV15 (RCL 1)
    FV = PV40 (RCL 2)
    CPT -> PMT
    ```
    
    ---
    

*Alternatively,* (Timestamp [1:27:32](https://www.markmeldrum.com/courses/2025-level-i/lessons/2025-l1-quantitative-methods/topic/2025-l1-qm-prereq1-interest-rates-present-value-and-future-value/))

![Screenshot (54).png](LOS%20d%20Demonstrate%20(Retirement%20Income)%201742adf9873a804da9f9cebe776a282c/Screenshot_(54).png)

---