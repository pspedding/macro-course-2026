# Lesson M13.L04: Fiscal Multipliers: Algebra and Policy Implications

**Module:** National Accounting, Keynesian Income-Expenditure Model and Fiscal Policy
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the government spending multiplier algebraically from the Keynesian cross.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [RBA](https://www.rba.gov.au) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023)

---

## Explanation

Starting from the equilibrium condition derived in M13.L02:

$$Y^* = \frac{a - b\bar{T} + \bar{I} + \bar{G} + \bar{X}}{1 - b + m}$$

**Government spending multiplier (k_G):** Differentiate with respect to Ḡ, holding all else constant:

$$k_G = \frac{\partial Y^*}{\partial \bar{G}} = \frac{1}{1 - b + m}$$

With b = 0.8, m = 0.1: k_G = 1/0.3 ≈ **3.33**.

**Tax multiplier (k_T):** Differentiate with respect to T̄:

$$k_T = \frac{\partial Y^*}{\partial \bar{T}} = \frac{-b}{1 - b + m}$$

With b = 0.8, m = 0.1: k_T = −0.8/0.3 ≈ **−2.67**.

The tax multiplier is smaller in absolute value than the spending multiplier because a tax cut of $1 raises disposable income by $1, but households save a fraction (1 − b) — only b dollars flow into consumption. A spending increase of $1 enters the expenditure stream directly.

**Balanced Budget Multiplier (BBM).** If ΔḠ = ΔT̄ = ΔB (equal increase in spending and taxes):

$$\Delta Y = k_G \cdot \Delta B + k_T \cdot \Delta B = \left(\frac{1}{1-b+m} + \frac{-b}{1-b+m}\right)\Delta B = \frac{1-b}{1-b+m} \cdot \Delta B$$

- **Closed economy** (m = 0): BBM = (1 − b)/(1 − b) = **1 exactly** (Haavelmo theorem).
- **Open economy** (m > 0): BBM = (1 − b)/(1 − b + m) < 1. With b = 0.8, m = 0.1: BBM = 0.2/0.3 = **0.67** — import leakage reduces the balanced budget multiplier below unity.

**Empirical estimates.** Australian Treasury estimates fiscal multipliers in the range of **0.6–1.2**, with higher values in recessions (when spare capacity is present and monetary policy is constrained at the lower bound). These are considerably below the textbook theoretical maximum due to crowding out, Ricardian equivalence effects, and import leakage in Australia's open economy.

---

## Worked Example

**Parameters:** b = 0.8, m = 0.1. The government increases spending by $10bn (ΔḠ = 10) while simultaneously raising taxes by $10bn (ΔT̄ = 10) — a balanced budget expansion.

**Step 1 — Government spending effect:**

> ΔY_G = k_G × ΔḠ = [1/(1 − 0.8 + 0.1)] × 10 = (1/0.3) × 10 = **$33.33bn**

**Step 2 — Tax effect:**

> ΔY_T = k_T × ΔT̄ = [−0.8/(0.3)] × 10 = −2.667 × 10 = **−$26.67bn**

**Step 3 — Net (balanced budget) effect:**

> ΔY_net = 33.33 + (−26.67) = **$6.67bn**

**Step 4 — Verify BBM:**

> BBM = ΔY_net / ΔB = 6.67 / 10 = **0.667**

This confirms BBM = (1 − b)/(1 − b + m) = 0.2/0.3 = 0.667 < 1 in the open economy.

**Contrast with closed economy:** If m = 0, BBM = 0.2/0.2 = **1.0 exactly**. A $10bn balanced budget expansion raises income by exactly $10bn.

---

## Common Misconception

**Misconception:** The balanced budget multiplier is always equal to 1.

**Correction:** The BBM = 1 result (Haavelmo theorem) holds exactly only in a **closed** economy where all spending stays domestic. In an open economy, some of each additional dollar of income is spent on imports rather than domestic goods, creating an additional leakage. The open-economy BBM = (1 − b)/(1 − b + m) < 1 whenever m > 0. Students must specify whether they are working with a closed or open economy model.

---

## Practice Prompts

1. Why is the government spending multiplier always larger in absolute value than the tax multiplier? Explain the mechanism in terms of how each policy instrument enters the expenditure stream.
   → **Answer:** A $1 increase in G enters aggregate expenditure directly and fully ($1 of spending). A $1 tax cut raises disposable income by $1, but consumers save a fraction (1 − b) and only spend b dollars domestically (and a fraction m of that is on imports). So the tax cut generates less first-round domestic spending than an equivalent direct expenditure increase. Formally: |k_G| = 1/(1 − b + m) > b/(1 − b + m) = |k_T| since b < 1.

2. With b = 0.75 and m = 0.05, calculate: (a) the government spending multiplier, (b) the tax multiplier, and (c) the balanced budget multiplier.
   → **Answer:**
   - Denominator: 1 − 0.75 + 0.05 = **0.30**
   - (a) k_G = 1/0.30 = **3.33**
   - (b) k_T = −0.75/0.30 = **−2.50**
   - (c) BBM = (1 − 0.75)/0.30 = 0.25/0.30 = **0.833**
   Note: BBM < 1 because m = 0.05 > 0.

3. During Australia's COVID-19 response, the government deployed approximately $300bn in fiscal stimulus. If the Treasury's mid-range fiscal multiplier of 0.9 applies, what is the estimated total impact on GDP? Why might the actual multiplier have been at the higher end of the 0.6–1.2 range during 2020?
   → **Answer:** Estimated GDP impact = $300bn × 0.9 = **$270bn**. The multiplier was likely at the higher end in 2020 because: (1) there was substantial spare capacity in the economy (deep recession), so extra spending did not crowd out private investment; (2) the RBA held interest rates near zero (cash rate at 0.1%), preventing monetary offset (crowding out via higher rates); (3) the stimulus was targeted at low-income households with high MPCs (JobSeeker, supplemented welfare) who spend a larger fraction of transfers. These conditions align with scenarios where Keynesian multipliers are maximised.

## Further Resources
- 📺 **[Keynesian cross and the multiplier](https://www.youtube.com/watch?v=aSY8XPGChAU)** — Khan Academy (8 min)
- 📺 **[Fiscal Policy and Stimulus: Crash Course Economics #8](https://www.youtube.com/watch?v=otmgFQHbaDo)** — Crash Course (12 min)
- 📚 **[RBA — Fiscal Policy Explainer](https://www.rba.gov.au/education/resources/explainers/fiscal-policy.html)** — Empirical estimates of fiscal multipliers and Australian fiscal policy design
