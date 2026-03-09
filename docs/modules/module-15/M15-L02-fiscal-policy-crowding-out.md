# Lesson M15.L02: Fiscal Policy in the IS-LM Model and Crowding Out

**Module:** The IS-LM Model Part II
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the crowding-out effect of fiscal expansion on private investment in the IS-LM model.
**Data as of:** 2024
**Provenance:** [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [Reserve Bank of Australia](https://www.rba.gov.au)

## Explanation

In the Keynesian cross, a rise in government spending *G* raises output by the full multiplier: *ΔY = ΔG / (1 − c₁)*, where *c₁* is the marginal propensity to consume. The IS-LM framework reveals why this overstates the stimulus: **crowding out**.

When *G* rises, the IS curve shifts **rightward** by the Keynesian multiplier amount (Δ*Y_IS* = multiplier × Δ*G*). At the unchanged interest rate, this raises *Y*. Higher income raises **money demand** (*L = kY − hr*). With a fixed money supply, the money market can only clear at a **higher interest rate** *r*. The LM curve is unchanged, so the new equilibrium involves both higher *Y* and higher *r*.

The higher *r* **reduces private investment**: *I = Ī − b_r × r*. This offsets part of the fiscal stimulus. The net increase in output, *ΔY_IS-LM*, is smaller than the Keynesian cross prediction.

**Key determinants of crowding-out magnitude:**
- Steeper LM (less interest-elastic money demand *h* low) → more crowding out.
- Steeper IS (investment less sensitive to *r*, i.e., *b_r* low) → less crowding out.
- **Complete crowding out** requires a vertical LM (classical case: fixed *Y*, any *G* rise is fully offset by *I* fall).
- **Zero crowding out** occurs at the ZLB (horizontal LM), where *r* cannot rise — fiscal policy regains its full Keynesian cross power.

**Australia COVID-19 (2020):** With the RBA holding the cash rate at 0.10% (effective ZLB), fiscal stimulus of approximately $314 billion (over 15% of GDP) faced near-zero crowding out. The RBA's Yield Curve Control kept 3-year government bond yields pinned at 0.10%, preventing the rise in *r* that would have reduced private investment.

**Notation:** *G* = government spending; *I = Ī − b_r × r* (investment demand); *c₁* = MPC; multiplier *k = 1/(1 − c₁)*; *h* = interest sensitivity of money demand; *M/P* = real money supply.

## Worked Example

**Setup:**

- IS curve: *Y = A − 100r*, where *A* is autonomous spending
- Goods market multiplier: *k = 2* (i.e., MPC *c₁ = 0.5*)
- LM curve: *Y = 600 + 100r* (unchanged throughout)
- Investment: *I = 300 − 50r*
- Initial autonomous spending: *A₀ = 1000*

**Step 1 — Initial equilibrium:**

```
IS = LM: 1000 − 100r = 600 + 100r
400 = 200r
r₁ = 2%
Y₁ = 1000 − 100(2) = 800
```

Initial investment: *I₁ = 300 − 50(2) = 200*

**Step 2 — Government raises spending by ΔG = 50:**

IS shifts right by multiplier × ΔG = 2 × 50 = 100.

New IS: *Y = 1100 − 100r*

**Step 3 — Keynesian cross prediction (ignoring LM):**

At unchanged *r = 2%*: *Y = 1100 − 200 = 900*. Predicted Δ*Y* = +100.

**Step 4 — Actual IS-LM equilibrium:**

```
1100 − 100r = 600 + 100r
500 = 200r
r₂ = 2.5%
Y₂ = 1100 − 100(2.5) = 850
```

**Step 5 — Investment after:**

*I₂ = 300 − 50(2.5) = 175*

**Step 6 — Crowding-out calculation:**

| Measure | Value |
|---|---|
| Keynesian cross ΔY prediction | +100 |
| IS-LM ΔY actual | +50 |
| Δr | +0.5 pp |
| ΔI (crowded out) | 200 − 175 = −**25** |

The fiscal multiplier in IS-LM is **0.5** compared to **1.0** in the Keynesian cross — half the output gain is offset by crowded-out investment. The shortfall (−25 in investment) partially explains the gap.

## Common Misconception

**Misconception:** In the IS-LM model, fiscal expansion always fully offsets private investment (complete crowding out).

**Correction:** Complete crowding out only occurs with a **vertical LM curve** (the classical case, where money demand is completely interest-inelastic). In the standard Keynesian IS-LM with an upward-sloping LM, the interest rate rises but does not rise enough to eliminate the output gain entirely. Crowding out is **partial**: output rises and investment falls, but by less than the fiscal impulse. At the ZLB (horizontal LM), there is **zero** crowding out.

## Practice Prompts

1. **Conceptual:** Why does the IS-LM fiscal multiplier always fall short of the Keynesian cross multiplier (except at the ZLB)?
   → **Answer:** In IS-LM, higher *G* raises *Y*, which raises money demand. With fixed *M/P*, the interest rate must rise to restore money market equilibrium. The higher *r* reduces private investment *I*, partially offsetting the fiscal stimulus. The Keynesian cross ignores this money-market feedback, overstating the multiplier.

2. **Numerical:** Using the model above, suppose government spending rises by ΔG = 100 instead of 50. Show all steps and calculate the new equilibrium *Y*, *r*, and the amount of investment crowded out.
   → **Answer:**
   ```
   IS shifts by k × ΔG = 2 × 100 = 200.
   New IS: Y = 1200 − 100r

   IS = LM: 1200 − 100r = 600 + 100r
   600 = 200r → r₂ = 3%

   Y₂ = 1200 − 100(3) = 900

   I₂ = 300 − 50(3) = 150
   ΔI = 150 − 200 = −50 (crowded out)

   Keynesian cross: ΔY = 200; IS-LM: ΔY = 100.
   ```
   Output rises by 100, but investment falls by 50. The IS-LM multiplier = 1.0 (not 2.0).

3. **Application:** During the COVID-19 pandemic, Australia deployed massive fiscal stimulus while the RBA held the cash rate at 0.10% and implemented Yield Curve Control. Using the IS-LM diagram, explain why crowding out was minimal.
   → **Answer:** With the RBA maintaining the cash rate at the ZLB and pinning 3-year bond yields at 0.10% via YCC, the LM curve was effectively **horizontal** at *r = 0.10%*. When the IS curve shifted right (due to fiscal stimulus), the interest rate could not rise, so private investment was not crowded out. The fiscal multiplier approximated the full Keynesian cross value. This is the "liquidity trap" case — monetary policy was constrained but fiscal policy was fully effective.

## Further Resources

- 📺 **[Fiscal Policy & Crowding Out in IS-LM Model](https://www.youtube.com/watch?v=f65Ns74C3p8)** — Yamini Mam Economics (18 min)
- 📺 **[Crowding Out | AP Macroeconomics](https://www.youtube.com/watch?v=4lBmOfNtYLE)** — Khan Academy (8 min)
- 📚 **[OpenStax Macro 3e, Chapter 26 – The IS-LM Model](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))** — Free textbook with worked examples
