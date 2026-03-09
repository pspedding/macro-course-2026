# Lesson M13.L03: The Investment Function and Determinants of Investment

**Module:** National Accounting, Keynesian Income-Expenditure Model and Fiscal Policy
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Model investment as a function of the interest rate using I = Ī − bi.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [RBA](https://www.rba.gov.au) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023)

---

## Explanation

Investment (I) is the most volatile component of aggregate expenditure. The standard intermediate model specifies:

> I = Ī − bi

where **Ī > 0** is autonomous investment (driven by expectations, technology, and animal spirits independent of the current interest rate), **b > 0** is the interest rate sensitivity of investment, and **i** is the nominal interest rate (or, more precisely, the real interest rate in long-run contexts).

**Intuition:** A higher interest rate raises the cost of borrowing for firms (and raises the hurdle rate for internally funded projects). This reduces the number of profitable investment projects, so I falls as i rises. The parameter b captures the slope of the investment demand curve.

**Autonomous vs induced investment.** Autonomous investment (Ī) is unrelated to current income. Induced (accelerator) investment responds to *changes* in output: ΔI = v × ΔY, where v > 0 is the accelerator coefficient. Rapidly growing economies attract more investment as firms expand capacity to meet rising demand.

**Tobin's q.** An alternative theory posits investment depends on the ratio q = market value of installed capital / replacement cost of capital. If q > 1, it is profitable to invest (market rewards new capital above its cost); if q < 1, investment is discouraged. Tobin's q links financial markets to real investment decisions.

**Australian evidence.** Australia's business investment-to-GDP ratio rose sharply from ~14% to ~19% during the mining investment boom (2010–2014), driven by record commodity prices and Chinese demand. The subsequent bust (2014–2017) saw mining investment halve as projects completed and commodity prices fell. Housing investment has been equally cyclical, peaking with low interest rates in 2021 and declining sharply after the RBA's rapid tightening cycle (2022–2023).

---

## Worked Example

**Given:** Ī = $300bn, b = 50, i = 0.04 (4% nominal interest rate).

**Step 1 — Compute investment:**

> I = Ī − bi = 300 − 50 × 0.04 = 300 − 2 = **$298bn**

**Step 2 — Effect of a rate rise.** The RBA raises i from 4% to 5% (Δi = 0.01):

> ΔI = −b × Δi = −50 × 0.01 = **−$0.5bn**

New investment: I = 300 − 50 × 0.05 = 300 − 2.5 = **$297.5bn**

**Step 3 — Multiplier effect on income.** Using the Keynesian cross multiplier from M13.L02 with b_mpc = 0.8, m = 0.1:

> ΔY = ΔI × 1/(1 − b_mpc + m) = −0.5 × 1/(0.3) = −0.5 × 3.33 = **−$1.67bn**

*Note: b used in the investment function (interest sensitivity = 50) is distinct from b used for MPC (= 0.8). Context determines which b is meant — always define notation explicitly.*

**Step 4 — Accelerator check.** If GDP grows by $100bn (ΔY = 100) and v = 0.3:

> ΔI_induced = v × ΔY = 0.3 × 100 = **$30bn** additional investment from accelerator.

---

## Common Misconception

**Misconception:** The parameter b in the investment function I = Ī − bi is the same as the MPC b in the consumption function C = a + b(Y − T).

**Correction:** These are entirely different parameters that happen to share the conventional letter b. In the investment function, b is the *interest rate sensitivity* of investment (units: $bn per percentage point of interest rate). In the consumption function, b is the *marginal propensity to consume* (dimensionless, bounded between 0 and 1). Always define your notation explicitly to avoid this confusion.

---

## Practice Prompts

1. Explain the accelerator principle and how it differs from the interest-rate investment function I = Ī − bi. In which phase of the business cycle would the accelerator amplify a downturn most severely?
   → **Answer:** The accelerator links investment to *changes* in output (ΔI = v × ΔY): when output grows rapidly, firms invest heavily to expand capacity; when output growth slows or turns negative, investment collapses. This differs from the interest-rate model, which links investment to borrowing cost. The accelerator amplifies downturns most severely when output *falls* after a period of rapid growth — induced investment drops sharply, reducing aggregate demand further, creating a recessionary spiral. This was evident in Australia's mining bust (2014–2017).

2. Using I = Ī − bi with Ī = $250bn and b = 40, calculate investment when i = 3% and when i = 6%. What is the change in investment?
   → **Answer:**
   - At i = 0.03: I = 250 − 40 × 0.03 = 250 − 1.2 = **$248.8bn**
   - At i = 0.06: I = 250 − 40 × 0.06 = 250 − 2.4 = **$247.6bn**
   - ΔI = 247.6 − 248.8 = **−$1.2bn** (investment falls by $1.2bn when rate doubles from 3% to 6%)

3. What does Tobin's q predict about business investment during a period of falling share prices (e.g., ASX correction)? How does this relate to the I = Ī − bi model?
   → **Answer:** Falling share prices reduce the market value of installed capital, lowering q below 1. This signals that the market values existing capital less than its replacement cost, discouraging new investment. In the I = Ī − bi model, this effect is captured through a reduction in autonomous investment Ī (animal spirits, expected profitability) rather than via the interest rate channel. Both models predict falling investment, but through different mechanisms — q links financial market sentiment to real investment, while I = Ī − bi emphasises the cost of funding.

## Further Resources
- 📺 **[Macro 4.1 - Money Market and FED Tools (Monetary Policy)](https://www.youtube.com/watch?v=_dNIDo8UFSc)** — ACDC Economics (10 min)
- 📺 **[Keynesian cross and the multiplier](https://www.youtube.com/watch?v=aSY8XPGChAU)** — Khan Academy (8 min)
- 📚 **[RBA — Business Investment Explainer](https://www.rba.gov.au/education/resources/explainers/investment.html)** — Determinants of business investment and their role in Australian economic cycles
