# LOS a Data Types

> **Learning Outcomes**
> 
> - *identify and compare data types*
> - *describe how data are organized for quantitative analysis*

---

### Numerical vs. Categorical

![Screenshot (61).png](LOS%20uni%201762adf9873a80d5bcc3f4ddbd150792/Screenshot_(61).png)

<aside>

### EXAMPLE 1

---

### *Identifying Data Types (I)*

Identify the data type for each of the following kinds of investment-related information:

---

- ***Number of coupon payments for a corporate bond.***
    
    <aside>
    
    - **Discrete** `integer`
        
        Number of coupon payments is discrete data. For example, a newly-issued 5-year corporate bond paying interest semi-annually (quarterly) will make 10 (20) coupon payments during its life. In this case, coupon payments are limited to a finite number of values; so, they are discrete.
        
    </aside>
    

---

- ***Cash dividends per share paid by a public company.***
    
    <aside>
    
    - **Continuous** `ratio`
        
        Cash dividends per share are continuous data since they can take on any non-negative values.
        
    </aside>
    

---

- ***Credit ratings for a corporate bond issues.***
    
    <aside>
    
    - **Ordinal**
        
        Credit ratings are ordinal data. A rating places a bond issue in a category, and the categories are ordered with respect to the expected probability of default. But arithmetic operations cannot be done on credit ratings, and the difference in the expected probability of default between categories of highly rated bonds, for example, is not necessarily equal to that between categories of lowly rated bonds.
        
    </aside>
    

---

- ***Hedge fund classification types.***
    
    <aside>
    
    - **Nominal**
        
        Hedge fund classification types are nominal data. Each type groups together hedge funds with similar investment strategies. In contrast to credit ratings for bonds, however, hedge fund classification schemes do not involve a ranking. Thus, such classification schemes are not ordinal data.
        
    </aside>
    

---

</aside>

---

### Cross-sectional vs. Time-series vs. Panel Data

- **Cross-sectional**
    
    ---
    
    **Stock Price**
    
    **Company 1**
    
    $10.00
    
    **Company 2**
    
    $12.00
    
    **Company 3**
    
    $14.00
    
    ---
    
- **Time-series**
    
    ---
    
    *Year 1*
    
    *Year 2*
    
    *Year 3*
    
    **Company 1**
    
    $10.00
    
    $12.00
    
    $14.00
    
    ---
    
- **Panel Data**
    
    ---
    
    *Year 1*
    
    *Year 2*
    
    *Year 3*
    
    **Company 1**
    
    $10.00
    
    $12.00
    
    $14.00
    
    **Company 2**
    
    $12.00
    
    $14.00
    
    $16.00
    
    **Company 3**
    
    $14.00
    
    $16.00
    
    $18.00
    
    ---
    

![Screenshot (64).png](LOS%20a%20Data%20Types%201742adf9873a8078823ad5e11092fdcd/Screenshot_(64).png)

---

### Structured vs. Unstructured Data

![Screenshot (65).png](LOS%20a%20Data%20Types%201742adf9873a8078823ad5e11092fdcd/Screenshot_(65).png)

---

<aside>

### EXAMPLE 2

---

### *Identifying Data Types (II)*

---

- Which of the following is *most* *likely* to be structured data?
    
    **A.** Social media posts where consumers are commenting on what they think of a company’s new product?
    
    **B.** Daily closing prices during the past month for all companies listed on Japan’s Nikkei 225 stock index.
    
    **C.** Audio and video of a CFO explaining her company’s latest earnings announcement to securities analysts.
    
    - [Show Solution](LOS%20a%20Data%20Types%201742adf9873a8078823ad5e11092fdcd.md)
        
        <aside>
        
        B is correct as daily closing prices constitute structured data. A is incorrect as social media posts are unstructured data. C is incorrect as audio and video are unstructured data.
        
        </aside>
        

---

- Which of the following statements describing panel data is *most accurate*?
    
    **A.** It is a sequence of observations for a single observational unit of a specific variable collected over time at discrete and equally spaced intervals.
    
    **B.** It is a list of observations of a specific variable from multiple observational units at a given point in time.
    
    **C.** It is a mix of time-series and cross-sectional data that are frequently used in financial analysis and modeling.
    
    - [Show Solution](LOS%20a%20Data%20Types%201742adf9873a8078823ad5e11092fdcd.md)
        
        <aside>
        
        C is correct as it most accurately describes panel data. A is incorrect as it describes time-series data. B is incorrect as it describes cross-sectional data.
        
        </aside>
        

---

- Which of the following data series is *least likely* to be sortable by values?
    
    **A.** Daily trading volumes for stocks listed on the Shanghai Stock Exchange.
    
    **B.** EPS for a given year for technology companies included in the S&P 500 Index.
    
    **C.** Dates of first default on bond payments for a group of bankrupt European manufacturing companies.
    
    - [Show Solution](LOS%20a%20Data%20Types%201742adf9873a8078823ad5e11092fdcd.md)
        
        <aside>
        
        C is correct as dates are ordinal data that can be sorted by chronological order but not by value. A and B are incorrect as both daily trading volumes and earnings per share (EPS) are numerical data, so they can be sorted by values.
        
        </aside>
        

---

- Which of the following best describes a time series?
    
    **A.** Daily stock prices of the XYZ stock over a 60-month period.
    
    **B.** Returns on four-star rated Morningstar investment funds at the end of the most recent month.
    
    **C.** Stock prices for all stocks in the FTSE100 on 31 December of the most recent calendar year.
    
    - [Show Solution](LOS%20a%20Data%20Types%201742adf9873a8078823ad5e11092fdcd.md)
        
        <aside>
        
        A is correct since a time series is a sequence of observations of a specific variable (XYZ stock price) collected over time (60 months) and at discrete intervals of time (daily). B and C are both incorrect as they are cross-sectional data.
        
        </aside>
        

---

</aside>

---