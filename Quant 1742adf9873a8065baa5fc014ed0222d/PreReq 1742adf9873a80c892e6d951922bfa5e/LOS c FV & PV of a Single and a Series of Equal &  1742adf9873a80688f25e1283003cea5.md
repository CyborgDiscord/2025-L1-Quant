# LOS c FV & PV of a Single and a Series of Equal & Unequal CFs

<aside>

**CONTENT**

---

- [Annuity](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5.md)
- [Perpetuity](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5.md)
- [Solve for `$r$`, `$N$` or `$PMT$`](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5.md)
</aside>

---

### **(FV) Future Value of a Series of Cash Flows**

- **Annuity:** a *****finite* set of level sequential cash flows
    - **ordinary:** first cash flow at t=1
        
        ![Screenshot (29).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(29).png)
        
        ---
        
    - **due:** first cash flow at t=0
        
        ```jsx
        **BGN Mode:** 2nd → PMT (BGN) → 2nd → ENTER (SET)
        ```
        
        <aside>
        💡
        
        Instead of switching modes back and forth, calculate *ordinary annuity* and multiply by `$1+rₛ = 1.05$ (where $rₛ$ **= 5%**)`
        
        </aside>
        
        ![Screenshot (31).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(31).png)
        
        ---
        
- **Unequal cash flows:**
    
    <aside>
    ❌
    
    **Can’t be solved using TVM keys**
    
    </aside>
    
    <aside>
    ✅
    
    **How to solve using CF keys:**
    
    ```jsx
    CF **→** {CFo = 0 ↓
    			C01 = 0 (ENTER); F01 = 1 ↓
    			C02 = -1000; F02 = 1 ↓
    			C03 = -2000; F03 = 1 ↓
    			C04 = -4000; F04 = 1 ↓
    			C05 = -5000; F05 = 1 ↓
    			C06 = -6000; F06 = 1} **→**
    NPV **→ I = 5 ↓
    		→ (NPV= *SKIP*) ↓
    		→ (NFV= *CPT(COMPUTE)*)**
    ```
    
    </aside>
    
    ![Screenshot (32).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(32).png)
    

---

### **(PV) Present Value of a Single Cash Flow**

![Screenshot (35).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(35).png)

---

### **(PV) Present Value of a Series of Cash Flows**

- Present value of a series of cash flows
    
    PMT = $1,000 $rₛ$ = 12% N = 5 years
    
    - **Ordinary annuity**
        
        ```jsx
        N = 5
        I/Y = 12
        PMT = 1000
        FV = 0
        CPT → PV
        ```
        
    - **Annuity due** (Timestamp 56:04)
        
        ```jsx
        **BGN Mode:** 2nd → PMT (BGN) → 2nd → ENTER (SET)
        
        N = 5
        I/Y = 12
        PMT = 1000
        FV = 0
        CPT → PV
        ```
        
    
    ![Screenshot (36).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(36).png)
    
    ---
    
- **IMPORTANT** (Timestamp 1:02:07)
    
    <aside>
    
    **CONTEXT**
    
    ---
    
    $t=0$: Right now (Present moment)
    
    $t=1$: End of first year (Beginning of 2nd *period* i.e. `$t=1$` to `$t=2$`)
    
    </aside>
    
    - **Question**
        
        PMT = $1M $r_s$ = 5%
        
        - PMT will not occur until 10 years from now (`$t=10$`)
            
            <aside>
            
            1st year `$t=0$ to $t=1$`
            2nd year `$t=1$ to $t=2$`
            3rd year `$t=2$ to $t=3$`
            4th year `$t=3$ to $t=4$`
            5th year `$t=4$ to $t=5$`
            6th year `$t=5$ to $t=6$`
            7th year `$t=6$ to $t=7$`
            8th year `$t=7$ to $t=8$`
            9th year `$t=8$ to $t=9$`
            10th year `$t=9$ to $t=10$`
            
            First payment `$t=10$`
            
            </aside>
            
        
        Once payments begin, they will extend until `$t=39$` for a total of 30 payments.
        
        - [Show Solution](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5.md)
            
            *The $1M annuity (30 years) can either be viewed as:*
            
            - **Ordinary annuity:** `$t=9$` to `$t=39$` (First payment at the end of `$t=9$` i.e. `$t=10$`)
                
                > This will solve for $PV₉$ , and to calculate $PV₀$ , $N$ should be taken as 9
                > 
            - **Annuity due:** `$t=10$` to `$t=40$` (First payment on the beginning of `$t=10$`)
                
                > This will solve for $PV₁₀$ , and to calculate $PV₀$ , $N$ should be taken as 10
                > 
            
            ![Screenshot (40).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(40).png)
            
    
    ---
    
- [**Unequal cash flows**](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5.md)

---

### **(PV) Present Value of a Perpetuity**

- **Perpetuity** *(infinite)***:** an [annuity](../PreReq%201742adf9873a80c892e6d951922bfa5e.md) that never ends
    
    $PV = A/rₛ$ `(where A = annuity, $rₛ$ = discount rate)` 
    
    ![Screenshot (42).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(42).png)
    

---

### **(PV) Present Value of a Series of Unequal Cash Flows**

<aside>
✅

[**How to solve using CF keys:](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5.md)** Compute `NPV` instead of `NFV`

</aside>

![Screenshot (43).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(43).png)

---

### Solve for `$r$`, `$N$` or `$PMT$`

Input the known values into their respective `TVM` keys and compute `CPT` the unknown variable.

![Screenshot (51).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(51).png)

![Screenshot (52).png](LOS%20c%20FV%20&%20PV%20of%20a%20Single%20and%20a%20Series%20of%20Equal%20&%20%201742adf9873a80688f25e1283003cea5/Screenshot_(52).png)

<aside>
<img src="https://www.notion.so/icons/star_yellow.svg" alt="https://www.notion.so/icons/star_yellow.svg" width="40px" />

- **NOTE**
    
    ---
    
    - A **mortgage** represents the **present value (PV)** in `TVM` calculations.
    - **Why?**
        
        > *It reflects the lump sum (loan amount) received upfront that is repaid over time.*
        > 
    - **Future Value (FV**) is typically **zero** in mortgage calculations since the goal is to fully repay the loan by the end of the term.
    - Remember: `PV` = Loan amount, `PMT` = Repayments, `FV` = $0 (fully paid).
</aside>

---