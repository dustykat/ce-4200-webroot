# 📘 Work it out … Engineering Economics

---

## 🔧 EUAC of a Tractor

**Problem:**  
A tractor costs $6,000. After 8 years it has a salvage value of $4,000. Maintenance costs are $250 per year. If the interest rate is 6%, the equivalent uniform annual cost is most nearly:

### 🎯 What Are We Being Asked?

We want the **Equivalent Uniform Annual Cost (EUAC)** — a way to express all the costs of owning the tractor as an equal yearly amount over its useful life.

### 🧰 Step-by-Step Breakdown

**1. Understand the Components**

- Initial cost (P) = $6,000  
- Salvage value (F) = $4,000  
- Maintenance cost (A_M) = $250/year  
- Interest rate (i) = 6%  
- Life (n) = 8 years

\[
\text{EUAC} = \text{Capital Recovery} + \text{Annual Maintenance Cost}
\]

**2. Compute Capital Recovery**

\[
\text{Capital Recovery} = P(A/P, i, n) - F(A/F, i, n)
\]

Use:

- (A/P, 6%, 8) = 0.162745  
- (A/F, 6%, 8) = 0.093573

\[
\text{Capital Recovery} = 6000 \cdot 0.162745 - 4000 \cdot 0.093573 = 602.18
\]

**3. Add Annual Maintenance**

\[
\text{EUAC} = 602.18 + 250 = \boxed{852.18}
\]

### ✅ Final Answer

\[
\boxed{\$852}
\]

---

## 🔧 Monthly Loan Payment

**Problem:**  
A company borrows $150,000 today at 6% nominal annual interest. The monthly payment of a 5-year loan is most nearly:

### 🎯 What Are We Being Asked?

We’re calculating the **monthly payment** on a **monthly-compounded loan**.

### 🧰 Step-by-Step Breakdown

- P = $150,000  
- i = 6%/12 = 0.5% = 0.005  
- n = 5 × 12 = 60

\[
A = P \cdot \frac{i(1+i)^n}{(1+i)^n - 1}
\]

\[
A = 150,000 \cdot \frac{0.005(1.005)^{60}}{(1.005)^{60} - 1} \approx \boxed{2,901}
\]

### ✅ Final Answer

\[
\boxed{\$2,900}
\]

---

## 🔧 Payback Period for Automation

**Problem:**  
Compare hand tools ($1,500 + $1.75/unit) vs automation ($17,500 + $0.75/unit). At 3,000 units/year, find the payback period (neglect interest).

### 🧰 Step-by-Step Breakdown

- Cost difference = 17,500 - 1,500 = $16,000  
- Unit savings = $1.75 - $0.75 = $1.00  
- Annual savings = 3,000 × $1.00 = $3,000  

\[
\text{Payback Period} = \frac{16,000}{3,000} = \boxed{5.33}
\]

### ✅ Final Answer

\[
\boxed{5.3 \text{ years}}
\]

---

## 🔧 Present Worth Comparison

**Problem:**  
Choose between 4 pieces of equipment, all 8-year life. Use given costs and salvage values. Interest rate = 10%.

### 🧰 Step-by-Step Breakdown

Formula:

\[
PW = -P + F(P/F, i, n), \quad (P/F, 10\%, 8) = 0.4665
\]

Example:

- A = -10,000 + 2,000 × 0.4665 = -9,067  
- Compare all four and assume best are:  
  - C = -8,534  
  - B = -8,833  
  - Difference = $299

### ✅ Final Answer

\[
\boxed{C \text{ and } B; \text{ difference } \approx \$299}
\]

---

## 🔧 Risk Analysis – Insurance

**Problem:**  
Buy insurance for $2,000/year with $1,000 deductible?  
- 85% chance no accident  
- 12% chance small accident ($800)  
- 3% chance total loss ($100,000)

### 🧰 Step-by-Step Breakdown

**With Insurance:**

\[
E = 0.85 \cdot 2000 + 0.12 \cdot 2800 + 0.03 \cdot 3000 = 2,126
\]

**Without Insurance:**

\[
E = 0.12 \cdot 800 + 0.03 \cdot 100,000 = 3,096
\]

\[
\text{Savings} = 3,096 - 2,126 = \boxed{970}
\]

### ✅ Final Answer

\[
\boxed{\text{Purchase insurance; save } \$970}
\]