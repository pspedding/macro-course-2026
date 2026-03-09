# Lesson M13.L02: Keynesian Cross Model: Formal Treatment

**Module:** National Accounting, Keynesian Income-Expenditure Model and Fiscal Policy
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Solve for equilibrium income in the Keynesian cross model with all four sectors.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023)

---

## Explanation

The Keynesian cross model determines equilibrium output (Y\*) as the level at which aggregate expenditure (AE) equals output (Y). With all four sectors, expenditure is:

> AE = C + I + G + NX

**Consumption function:** C = a + b(Y − T̄), where a > 0 is autonomous consumption, b ∈ (0,1) is the marginal propensity to consume (MPC), Y is national income, and T̄ is lump-sum net taxes (autonomous).

**Investment:** I = Ī (autonomous, fixed in this model — we relax this in M13.L03).

**Government spending:** G = Ḡ (autonomous/exogenous).

**Net exports:** NX = X̄ − mY, where X̄ is autonomous exports and m > 0 is the marginal propensity to import. As Y rises, imports rise proportionally; exports are exogenous.

**Equilibrium condition:** Y = AE. Substituting:

> Y = a + b(Y − T̄) + Ī + Ḡ + X̄ − mY
> Y = a − bT̄ + bY + Ī + Ḡ + X̄ − mY
> Y − bY + mY = a − bT̄ + Ī + Ḡ + X̄
> Y(1 − b + m) = a − bT̄ + Ī + Ḡ + X̄

$$Y^* = \frac{a - b\bar{T} + \bar{I} + \bar{G} + \bar{X}}{1 - b + m}$$

The denominator (1 − b + m) is the leakage rate: saving (1 − b) and imports (m) are both withdrawals from the expenditure circular flow. The numerator is total autonomous spending net of tax-induced consumption reduction.

**45-degree diagram logic:** The AE line has slope (b − m) < 1 (since b < 1 and m > 0). Equilibrium is where the AE line crosses the 45° line (Y = AE). An upward shift in any autonomous component (G, I, X, a) shifts AE up, raising Y\* by the multiplied amount.

---

## Worked Example

**Parameters:** a = 200, b = 0.8, T̄ = 100, Ī = 150, Ḡ = 250, X̄ = 180, m = 0.1

**Step 1 — Compute the numerator (autonomous spending net of taxes):**

> a − bT̄ + Ī + Ḡ + X̄
> = 200 − (0.8)(100) + 150 + 250 + 180
> = 200 − 80 + 150 + 250 + 180
> = **700**

**Step 2 — Compute the denominator (leakage rate):**

> 1 − b + m = 1 − 0.8 + 0.1 = **0.3**

**Step 3 — Solve for Y\*:**

> Y\* = 700 / 0.3 = **$2,333.3bn** (rounded to $2,333bn)

**Step 4 — Verify by computing AE at Y = 2,333:**

> C = 200 + 0.8(2,333 − 100) = 200 + 0.8(2,233) = 200 + 1,786.4 = 1,986.4
> I = 150
> G = 250
> NX = 180 − 0.1(2,333) = 180 − 233.3 = −53.3
> AE = 1,986.4 + 150 + 250 − 53.3 = 2,333.1 ✓ (rounding difference)

---

## Common Misconception

**Misconception:** In the open-economy Keynesian cross, the equilibrium formula is Y\* = (a + bT̄ + Ī + Ḡ + X̄)/(1 − b + m) — i.e., taxes enter with a positive sign in the numerator.

**Correction:** Taxes enter with a *negative* sign because higher taxes reduce disposable income (Y − T̄), which reduces consumption. The correct numerator term is −bT̄ (not +bT̄). A tax increase of ΔT̄ reduces Y\* by bΔT̄/(1 − b + m), which is negative — an intuitive result.

---

## Practice Prompts

1. In the Keynesian cross model with four sectors, what are the two sources of leakage from the expenditure stream, and how do they appear in the multiplier denominator?
   → **Answer:** The two leakages are (1) saving, captured by (1 − b) — the fraction of each additional dollar of income not consumed — and (2) imports, captured by m — the fraction of each additional dollar of income spent on foreign goods. Together they form the denominator (1 − b + m), which reduces the multiplier effect.

2. Using b = 0.75, m = 0.15, T̄ = 200, a = 100, Ī = 120, Ḡ = 180, X̄ = 140, calculate equilibrium income Y\*.
   → **Answer:**
   - Numerator: 100 − (0.75)(200) + 120 + 180 + 140 = 100 − 150 + 120 + 180 + 140 = **390**
   - Denominator: 1 − 0.75 + 0.15 = **0.40**
   - Y\* = 390 / 0.40 = **$975bn**

3. In the model above, if autonomous exports X̄ increase by $20bn (e.g., due to stronger Chinese demand for Australian iron ore), by how much does Y\* increase? Interpret this in the context of Australia's resource export dependence.
   → **Answer:** ΔY\* = ΔX̄ × 1/(1 − b + m) = 20 × (1/0.40) = 20 × 2.5 = **$50bn**. The $20bn export boost is multiplied 2.5 times. This illustrates Australia's structural sensitivity to commodity export demand: a sharp rise in iron ore exports to China amplifies through domestic consumption, creating a sizeable income effect well beyond the direct export revenue.

## Further Resources
- 📺 **[Keynesian cross and the multiplier](https://www.youtube.com/watch?v=aSY8XPGChAU)** — Khan Academy (8 min)
- 📺 **[Fiscal Policy and Stimulus: Crash Course Economics #8](https://www.youtube.com/watch?v=otmgFQHbaDo)** — Crash Course (12 min)
- 📚 **[RBA — Fiscal Policy Explainer](https://www.rba.gov.au/education/resources/explainers/fiscal-policy.html)** — Keynesian cross mechanics and the formal derivation of the spending multiplier

[VISUAL NEEDED: 45-degree Keynesian cross diagram showing AE = C + I + G + NX line with slope (b − m), intersecting the Y = AE line at equilibrium Y*. Indicate the autonomous spending intercept (a − bT̄ + Ī + Ḡ + X̄) and label the multiplier gap between a demand shock and the resulting income change.]
