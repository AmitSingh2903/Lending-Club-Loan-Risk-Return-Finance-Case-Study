# 💳 Credit Risk Insights from LendingClub Loan Data (SQL Case Study)

![Finance Banner](https://images.unsplash.com/photo-1559526324-593bc073d938?auto=format&fit=crop&w=1350&q=80)

> A comprehensive **data-driven financial case study** exploring how **borrower credit grade, loan purpose, and income** influence **interest rates** and **default probabilities**.  
> Developed using **SQL (Python: Pandas & Matplotlib)** to demonstrate the **risk–return tradeoff** in consumer lending.

---

## 📘 Project Overview

This project analyzes real **LendingClub consumer loan data (2007–2018)** to understand the **relationship between borrower risk and return** in personal lending.  
By blending **financial theory** and **data analytics**, this study highlights how creditworthiness and affordability shape both interest rates and repayment behavior.

**Core Financial Question:**  
> How do borrower characteristics — credit grade, purpose, and income — affect the cost of borrowing and the risk of default?

---

## 🎯 Objectives

1. Quantify the **risk–return relationship** using credit grades (A–G).  
2. Identify **high-risk loan purposes** with elevated default rates.  
3. Examine **income-driven default trends** to measure borrower affordability.  

---

## 🧠 Financial Concept — The Risk–Return Tradeoff

In finance, **risk and return are inseparable**.  
Lenders expect **higher returns (interest)** from borrowers who carry **higher default risk**.  
This balance is at the core of credit markets:  

- Safer borrowers → lower rates → lower risk  
- Riskier borrowers → higher rates → higher default potential  

This project uses **SQL queries and Python visualization** to **quantify** this principle with real data.

---

## 🧩 Dataset Details

**Source:** [LendingClub Loan Data (Kaggle)](https://www.kaggle.com/datasets/wordsforthewise/lending-club)  
**Records:** ~2.6 million loans  
**Period Covered:** 2007 – 2018  
**Key Fields Used:**  
- Borrower credit grade (`grade`, `sub_grade`)  
- Loan details (`loan_amount`, `interest_rate`, `term`)  
- Borrower profile (`annual_inc`, `dti`)  
- Loan outcome (`status`)  
- Loan purpose (`purpose`)

---

## 📊 Analysis 1 — Interest Rate vs Credit Grade

**Goal:**  
To understand how a borrower’s **credit grade** affects their **interest rate**.

**Insight:**  
- Interest rates increase steadily from Grade **A (~7%)** to Grade **G (~21%)**.  
- This confirms the **risk–return tradeoff** — lenders charge higher interest to compensate for higher credit risk.  

**Financial Meaning:**  
The grading system effectively prices risk; lower-grade borrowers pay more due to higher probability of default.

---

## 💣 Analysis 2 — Default Rate by Loan Purpose

**Goal:**  
To find which loan purposes show higher default tendencies.

**Insight:**  
- **Small business** and **renewable energy** loans exhibit the highest default rates (~18–22%).  
- **Credit card** and **debt consolidation** loans perform better (~12–13%).  

**Financial Meaning:**  
Different loan types carry varying levels of systemic and personal risk.  
This helps lenders identify **risky sectors** and improve **portfolio diversification**.

---

## 💰 Analysis 3 — Income vs Default Risk (Affordability)

**Goal:**  
To measure how **annual income** influences a borrower’s **likelihood of defaulting**.

**Insight:**  
- Borrowers earning **< $40K** default at ~16%.  
- Borrowers earning **> $200K** default at ~5%.  
- Default rates fall consistently as income rises.

**Financial Meaning:**  
Higher income implies better repayment capacity and lower credit risk —  
confirming that **affordability is a key determinant of default behavior**.

---

## 📈 Combined Findings

| Factor | Trend | Financial Interpretation |
|:-------|:------|:--------------------------|
| **Credit Grade** | Interest rates rise from A → G | Riskier borrowers are charged more |
| **Loan Purpose** | Business loans default most | Enterprise loans carry volatility |
| **Income Level** | Defaults fall as income increases | Affordability reduces credit risk |

**Overall:**  
Borrowers with weaker credit grades, lower income, or riskier loan purposes are **charged higher interest** and are **more likely to default** — illustrating the **core principle of risk-adjusted lending**.

---

## 🧾 Conclusion

This study demonstrates how **data analytics can quantify financial theory**.  
The LendingClub dataset validates that:

> **Higher risk → Higher return → Higher probability of loss**

Through SQL-based aggregation and Python visualization, the project connects raw data to core **credit risk management principles**, showing how banks and lenders **balance profit and protection**.

---

## 🧰 Skills Demonstrated

- SQL (aggregation, CASE logic, GROUP BY, filtering)  
- Python (Pandas, SQLite, Matplotlib)  
- Financial domain knowledge (credit risk, affordability, risk–return tradeoff)  
- Data storytelling and visualization for decision-making

## 🧠 Key Takeaway

> “In finance, **risk** and **return** are two sides of the same coin —  
> but with **data**, we can measure, understand, and optimize that balance.”

![Finance Insight](https://images.unsplash.com/photo-1569025690938-a00729c9e1b9?auto=format&fit=crop&w=1350&q=80)

---

