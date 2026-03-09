# Lesson M15.L01: Monetary Policy in the IS-LM Model

**Module:** The IS-LM Model Part II
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Trace the short-run effect of an RBA cash rate cut on equilibrium output in the IS-LM model.
**Data as of:** 2024
**Provenance:** [Reserve Bank of Australia](https://www.rba.gov.au) | [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

## Explanation

The IS-LM model describes short-run equilibrium in the goods and money markets simultaneously. The **IS curve** (Investment-Saving) gives combinations of the interest rate *r* and output *Y* where the goods market clears. The **LM curve** (Liquidity-Money) gives combinations where the money market clears: real money demand *L(r, Y) = kY − hr* equals the real money supply *M/P*.

**Monetary policy** in this framework operates through the LM curve. When the RBA cuts the **cash rate** — its operational target for the overnight interbank rate — it increases the money supply *M* or targets a lower *r* directly. An increase in *M* raises *M/P* (given a fixed price level *P* in the short run), shifting the LM curve **rightward** (downward in r-Y space).

The transmission follows two sequential effects:

1. **Liquidity effect:** On impact, the increase in money supply makes money more abundant relative to bonds. Individuals sell bonds, bond prices rise, and *r* falls immediately.
2. **Income effect:** Lower *r* stimulates investment spending (*I = Ī − b_r × r*), raising *Y*. As *Y* rises, money demand *kY* increases, partially offsetting the fall in *r* — the new equilibrium has a somewhat higher *r* than the initial liquidity-effect low.

In Australia, the RBA made **three consecutive cash rate cuts in 2019** (June, July, October), lowering the target from 1.50% to **0.75%**. The aim was to lift output and employment toward capacity. By 2020, the cash rate hit its **effective lower bound (ZLB)** of 0.10% (November 2020), limiting further conventional monetary stimulus — a topic explored in M15.L03.

**Notation summary:**
- *Y* = real GDP; *r* = real interest rate; *M* = nominal money supply; *P* = price level; *M/P* = real money balances
- *k* = income sensitivity of money demand; *h* = interest sensitivity of money demand
- *b_r* = interest sensitivity of investment; *Ī* = autonomous investment

## Worked Example

**Setup:** The economy is described by:

- IS curve: *Y = 1000 − 100r*
- LM curve: *Y = 2(M/P) + 200r*

Initial money supply gives *M/P = 300*, so LM: *Y = 600 + 200r*.

**Step 1 — Initial equilibrium:**

Set IS = LM:

```
1000 − 100r = 600 + 200r
400 = 300r
r* = 4/3 ≈ 1.33%
```

Substitute back into IS:

```
Y* = 1000 − 100(1.33) = 1000 − 133 = 867
```

Initial equilibrium: **r₁ = 1.33%, Y₁ = 867**.

**Step 2 — RBA expands money supply:** *M/P* rises from 300 to 350.

New LM: *Y = 2(350) + 200r = 700 + 200r*

**Step 3 — New equilibrium:**

Set IS = new LM:

```
1000 − 100r = 700 + 200r
300 = 300r
r* = 1.00%
```

```
Y* = 1000 − 100(1.00) = 900
```

New equilibrium: **r₂ = 1.00%, Y₂ = 900**.

**Step 4 — Interpret:**

| | r (%) | Y |
|---|---|---|
| Before monetary expansion | 1.33 | 867 |
| After monetary expansion | 1.00 | 900 |
| Change | −0.33 pp | +33 |

The LM shift lowers *r* by 0.33 percentage points and raises output by 33 units. Note that *r* falls by **less** than the full liquidity-effect amount because the income effect (Y rising → money demand rising) partially pushes *r* back up.

## Common Misconception

**Misconception:** A cash rate cut directly and fully lowers all interest rates in the economy by the same amount as the RBA's announced cut.

**Correction:** The cash rate is the overnight rate at which banks lend to each other. Its pass-through to lending rates (mortgages, business loans) is partial and varies with bank margins, credit risk premiums, and competitive dynamics. In the IS-LM model, the income effect of rising *Y* partially offsets the fall in *r*, so the equilibrium interest rate falls by **less** than the initial liquidity-effect shift. Australian banks passed through RBA cuts by only 0.19–0.25 percentage points in some 2019 cycles.

## Practice Prompts

1. **Conceptual:** In the IS-LM diagram, which curve shifts when the RBA cuts the cash rate, and in which direction?
   → **Answer:** The LM curve shifts **rightward** (or downward). A cut in the cash rate is implemented by expanding the money supply, raising *M/P* and shifting LM right, which reduces *r* and raises *Y*.

2. **Numerical:** Using the model above, suppose *M/P* rises from 300 to 400 instead of 350. Calculate the new equilibrium *r* and *Y*.
   → **Answer:**
   ```
   New LM: Y = 2(400) + 200r = 800 + 200r
   Set IS = LM: 1000 − 100r = 800 + 200r
   200 = 300r → r* = 2/3 ≈ 0.67%
   Y* = 1000 − 100(0.67) = 933
   ```
   **r₂ = 0.67%, Y₂ = 933.** The larger expansion in money supply produces a bigger fall in *r* and a larger rise in *Y*.

3. **Application:** In June–October 2019, the RBA cut the cash rate three times from 1.50% to 0.75%. Using the IS-LM framework, explain why the resulting stimulus to output may have been limited.
   → **Answer:** Even though the LM shifted right, several factors dampened the income effect: (a) imperfect pass-through from the cash rate to lending rates reduced the IS-curve response; (b) weak consumer and business confidence meant the IS curve itself was relatively flat (inelastic investment); (c) with rates already low, the liquidity effect was compressed. The RBA's own assessment noted that monetary policy alone was insufficient and called for fiscal support.

## Further Resources

- 📺 **[IS-LM Model & Diagram – LM Curve Shift from a Monetary Shock](https://www.youtube.com/watch?v=b28lsOUFOtw)** — Economics in Many Lessons (12 min)
- 📺 **[Intermediate Macroeconomics 5/8: The IS-LM Model](https://www.youtube.com/watch?v=72tKKgw2eCM)** — Marginal Revolution University (15 min)
- 📚 **[RBA Explainer: Monetary Policy Implementation](https://www.rba.gov.au/education/resources/explainers/monetary-policy-implementation.html)** — How the RBA targets the cash rate

[VISUAL NEEDED: Two-panel IS-LM diagram showing (1) initial equilibrium at (Y₁, r₁) and (2) LM shifting right to new equilibrium at (Y₂, r₂), with arrows indicating liquidity effect (r falls on impact) and income effect (r partially recovers as Y rises). Label both effects clearly.]
