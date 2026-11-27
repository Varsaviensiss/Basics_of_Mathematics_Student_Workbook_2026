# Solution to Problem 14: Applied Microeconomics & Marginal Analysis (Enrichment)

## 1. Problem Statement

### 1.1 Curriculum Structure Note
In accordance with the official course syllabus (`exercises/3_Calculus/05_applications_en.md`), the core required problem set for module **05. Applications of Differential and Integral Calculus** concludes at **Problem 12** (*Complete Model and Computer Verification*). 

To preserve uniform 15-problem coverage across the student workbook repository and to provide rigorous preparation for engineering economics and applied management exams, this file presents an advanced capstone application: **Optimal Production, Marginal Revenue vs. Marginal Cost Dynamics, and Price Elasticity of Demand**.

---

### 1.2 Problem Formulation
A digital enterprise provides enterprise cloud computing licenses. Market research indicates that the inverse demand function relating the price per monthly license $p$ (in $\mathrm{PLN}$) to the sales volume $q$ (in thousands of licenses) is:
$$
p(q) = 100 - 2q, \qquad q \in [0, 50].
$$

The enterprise's total monthly operational and infrastructure cost function $C(q)$ (in thousands of $\mathrm{PLN}$) is modeled by the cubic polynomial:
$$
C(q) = q^3 - 12q^2 + 68q + 50, \qquad q \ge 0.
$$

Complete the following economic and calculus analyses:
1. Formulate the Total Revenue function $R(q)$ and derive the Marginal Revenue function $MR(q) = R'(q)$.
2. Derive the Marginal Cost function $MC(q) = C'(q)$.
3. Formulate the Total Profit function $\Pi(q) = R(q) - C(q)$ and determine the production quantity $q^*$ that maximizes total profit.
4. Verify the second-order sufficiency condition for profit maximization.
5. Determine the profit-maximizing price $p^*$, the total revenue $R^*$, the total cost $C^*$, and the maximum profit $\Pi^*$.
6. Calculate the price elasticity of demand $\varepsilon(p^*)$ at the optimal operating point and interpret the market condition.

---

## 2. Theoretical Background and Concepts

### 2.1 Revenue, Cost, and Profit in Differential Calculus
Let $q$ denote output quantity.
- **Total Revenue:** $R(q) = q \cdot p(q)$.
- **Marginal Revenue:** $MR(q) = \frac{dR}{dq}$ measures the additional revenue gained by producing and selling an infinitesimal additional unit.
- **Marginal Cost:** $MC(q) = \frac{dC}{dq}$ measures the instantaneous rate of increase in total cost.
- **Total Profit:** $\Pi(q) = R(q) - C(q)$.

### 2.2 First- and Second-Order Conditions for Profit Maximization
- **First-Order Necessary Condition (FONC):**
  $$
  \Pi'(q) = 0 \iff R'(q) - C'(q) = 0 \iff MR(q) = MC(q).
  $$
  Profit is maximized when marginal revenue equals marginal cost.
- **Second-Order Sufficient Condition (SOSC):**
  $$
  \Pi''(q^*) < 0 \iff R''(q^*) - C''(q^*) < 0 \iff \left.\frac{d(MR)}{dq}\right|_{q^*} < \left.\frac{d(MC)}{dq}\right|_{q^*}.
  $$
  The marginal cost curve must cut the marginal revenue curve from below.

### 2.3 Price Elasticity of Demand
The point price elasticity of demand $\varepsilon$ is defined by:
$$
\varepsilon(p) = \frac{p}{q} \cdot \frac{dq}{dp}.
$$
- If $|\varepsilon| > 1$, demand is **elastic** (percentage change in quantity exceeds percentage change in price).
- If $|\varepsilon| = 1$, demand is **unit elastic**.
- If $|\varepsilon| < 1$, demand is **inelastic**.

---

## 3. Detailed Step-by-Step Solution

### Step 1: Revenue and Marginal Revenue Functions
Given the inverse demand function $p(q) = 100 - 2q$, the Total Revenue function is:
$$
R(q) = q \cdot p(q) = q(100 - 2q) = 100q - 2q^2\quad [\text{thousands of PLN}].
$$
The Marginal Revenue function is the first derivative of $R(q)$:
$$
MR(q) = R'(q) = \frac{d}{dq}(100q - 2q^2) = 100 - 4q\quad [\text{PLN/license}].
$$

### Step 2: Marginal Cost Function
The Total Cost function is $C(q) = q^3 - 12q^2 + 68q + 50$. Differentiating:
$$
MC(q) = C'(q) = \frac{d}{dq}(q^3 - 12q^2 + 68q + 50) = 3q^2 - 24q + 68\quad [\text{PLN/license}].
$$

### Step 3: Total Profit Function and First-Order Condition
The Total Profit function $\Pi(q)$ is:
$$
\Pi(q) = R(q) - C(q) = (100q - 2q^2) - (q^3 - 12q^2 + 68q + 50).
$$
Grouping like powers of $q$:
$$
\Pi(q) = -q^3 + 10q^2 + 32q - 50.
$$

We set the derivative $\Pi'(q) = MR(q) - MC(q) = 0$:
$$
(100 - 4q) - (3q^2 - 24q + 68) = 0,
$$
$$
-3q^2 + 20q + 32 = 0 \iff 3q^2 - 20q - 32 = 0.
$$

We solve this quadratic equation using the discriminant:
$$
\Delta = (-20)^2 - 4(3)(-32) = 400 + 384 = 784.
$$
Since $\sqrt{784} = 28$, the roots are:
$$
q_1 = \frac{20 + 28}{2(3)} = \frac{48}{6} = 8, \qquad q_2 = \frac{20 - 28}{6} = -\frac{8}{6} = -\frac{4}{3}.
$$
Because production volume must be non-negative ($q \ge 0$), the negative root $q_2 = -4/3$ is discarded. The unique physically feasible critical point is:
$$
q^* = 8\quad [\text{thousands of licenses}].
$$

### Step 4: Verification of the Second-Order Condition
We compute the second derivative of the profit function:
$$
\Pi''(q) = \frac{d}{dq}(-3q^2 + 20q + 32) = -6q + 20.
$$
Evaluating at $q^* = 8$:
$$
\Pi''(8) = -6(8) + 20 = -48 + 20 = -28 < 0.
$$
Since $\Pi''(8) = -28 < 0$, the profit function is strictly concave in the neighborhood of $q^* = 8$, establishing that $q^* = 8\,000$ licenses yields a strict local maximum.

Furthermore, on the feasible boundary $q = 0$:
$$
\Pi(0) = -50\quad (\text{fixed overhead loss of } 50\,000\ \mathrm{PLN}).
$$
And at the capacity boundary $q = 50$:
$$
\Pi(50) = -(50)^3 + 10(50)^2 + 32(50) - 50 = -125\,000 + 25\,000 + 1\,600 - 50 < 0.
$$
Thus, $q^* = 8$ is the strict global maximum on $[0, 50]$.

### Step 5: Optimal Economic Indicators
1. **Optimal Price:**
   $$
   p^* = p(8) = 100 - 2(8) = 100 - 16 = 84\ \mathrm{PLN/license}.
   $$
2. **Total Revenue:**
   $$
   R(8) = 8 \times 84 = 672\quad [\text{thousand PLN}].
   $$
3. **Total Cost:**
   $$
   C(8) = 8^3 - 12(8^2) + 68(8) + 50 = 512 - 768 + 544 + 50 = 338\quad [\text{thousand PLN}].
   $$
4. **Maximum Total Profit:**
   $$
   \Pi^* = R(8) - C(8) = 672 - 338 = 334\quad [\text{thousand PLN}].
   $$
   Equivalently:
   $$
   \Pi(8) = -(8)^3 + 10(8)^2 + 32(8) - 50 = -512 + 640 + 256 - 50 = 334\ \mathrm{kPLN}.
   $$

### Step 6: Price Elasticity of Demand Analysis
We express quantity as a function of price:
$$
p = 100 - 2q \implies 2q = 100 - p \implies q(p) = 50 - \frac{1}{2}p.
$$
The derivative with respect to price is:
$$
\frac{dq}{dp} = -\frac{1}{2} = -0.5.
$$
At the optimal price $p^* = 84$ and quantity $q^* = 8$:
$$
\varepsilon(p^*) = \frac{p^*}{q^*} \cdot \left.\frac{dq}{dp}\right|_{p=84} = \frac{84}{8} \cdot (-0.5) = 10.5 \cdot (-0.5) = -5.25.
$$

**Economic Interpretation:**
- The price elasticity is $\varepsilon = -5.25$, with absolute value $|\varepsilon| = 5.25 > 1$.
- Demand is highly **elastic** at this operating point. A $1\%$ increase in license price will result in an estimated $5.25\%$ decrease in quantity demanded.
- In monopoly theory, an optimizing firm always chooses an operating point in the elastic region of the demand curve ($|\varepsilon| > 1$), where $MR > 0$. Here, $MR(8) = 100 - 4(8) = 68 > 0$, perfectly validating microeconomic theory.

---

## 4. Verification and Consistency Checks

### 4.1 Numerical Neighborhood Verification
We evaluate the revenue, cost, and profit functions for quantities surrounding $q^* = 8$:

| Output $q$ ($10^3$) | Price $p$ ($\mathrm{PLN}$) | Revenue $R(q)$ ($\mathrm{kPLN}$) | Cost $C(q)$ ($\mathrm{kPLN}$) | Profit $\Pi(q)$ ($\mathrm{kPLN}$) | Marginal Profit $\Pi'(q)$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $6$ | $88$ | $528$ | $242$ | $286$ | $+44$ |
| $7$ | $86$ | $602$ | $281$ | $321$ | $+25$ |
| **$8$** | **$84$** | **$672$** | **$338$** | **$334$** | **$0$ (MAXIMUM)** |
| $9$ | $82$ | $738$ | $419$ | $319$ | $-31$ |
| $10$ | $80$ | $800$ | $530$ | $270$ | $-68$ |

The table confirms that profit strictly peaks at $q = 8$ with $\Pi = 334\ \mathrm{kPLN}$ and decreases for any under-production or over-production.

### 4.2 Marginal Revenue and Marginal Cost Equivalence
At $q^* = 8$:
- $MR(8) = 100 - 4(8) = 68\ \mathrm{PLN}$.
- $MC(8) = 3(8)^2 - 24(8) + 68 = 3(64) - 192 + 68 = 192 - 192 + 68 = 68\ \mathrm{PLN}$.

Because $MR(8) = MC(8) = 68\ \mathrm{PLN}$, the marginal profit $\Pi'(8) = MR(8) - MC(8) = 0$ is rigorously confirmed.
