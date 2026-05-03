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

## Visual — Monetary Expansion in the IS-LM Model

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1200 420" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 16px Arial, sans-serif; fill: #222; }
    .small { font: 13px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>

  <!-- Panel 1 -->
  <text x="300" y="28" text-anchor="middle" class="title">1. Initial IS-LM equilibrium</text>
  <line x1="80" y1="340" x2="520" y2="340" class="axis" />
  <line x1="80" y1="340" x2="80" y2="60" class="axis" />
  <text x="300" y="388" text-anchor="middle" class="label">Output, Y</text>
  <text x="28" y="205" transform="rotate(-90 28 205)" text-anchor="middle" class="label">Real interest rate, r</text>
  <line x1="150" y1="120" x2="470" y2="290" class="curve" stroke="#d62728" />
  <line x1="180" y1="300" x2="430" y2="100" class="curve" stroke="#1f77b4" />
  <circle cx="310" cy="205" r="5" fill="#222" />
  <line x1="310" y1="205" x2="310" y2="340" class="guide" />
  <line x1="80" y1="205" x2="310" y2="205" class="guide" />
  <text x="412" y="291" class="label">IS</text>
  <text x="385" y="110" class="label">LM₁</text>
  <text x="319" y="200" class="label">E₁</text>
  <text x="292" y="360" class="small">Y₁</text>
  <text x="58" y="210" class="small">r₁</text>

  <!-- Panel 2 -->
  <text x="895" y="28" text-anchor="middle" class="title">2. RBA expands money supply: LM shifts right</text>
  <line x1="670" y1="340" x2="1120" y2="340" class="axis" />
  <line x1="670" y1="340" x2="670" y2="60" class="axis" />
  <text x="895" y="388" text-anchor="middle" class="label">Output, Y</text>
  <text x="618" y="205" transform="rotate(-90 618 205)" text-anchor="middle" class="label">Real interest rate, r</text>
  <line x1="740" y1="120" x2="1060" y2="290" class="curve" stroke="#d62728" />
  <line x1="770" y1="300" x2="1020" y2="100" class="curve" stroke="#1f77b4" />
  <line x1="840" y1="300" x2="1090" y2="100" class="curve" stroke="#6baed6" />
  <circle cx="900" cy="205" r="5" fill="#222" />
  <circle cx="972" cy="243" r="5" fill="#222" />
  <circle cx="900" cy="252" r="4" fill="#6baed6" />
  <line x1="900" y1="205" x2="900" y2="340" class="guide" />
  <line x1="972" y1="243" x2="972" y2="340" class="guide" />
  <line x1="670" y1="205" x2="900" y2="205" class="guide" />
  <line x1="670" y1="243" x2="972" y2="243" class="guide" />
  <line x1="670" y1="252" x2="900" y2="252" class="guide" />
  <text x="1002" y="291" class="label">IS</text>
  <text x="978" y="110" class="label">LM₁</text>
  <text x="1044" y="110" class="label">LM₂</text>
  <text x="908" y="200" class="label">E₁</text>
  <text x="980" y="238" class="label">E₂</text>
  <text x="879" y="360" class="small">Y₁</text>
  <text x="951" y="360" class="small">Y₂</text>
  <text x="648" y="210" class="small">r₁</text>
  <text x="648" y="248" class="small">r₂</text>
  <text x="648" y="257" class="small">rL</text>

  <line x1="900" y1="214" x2="900" y2="247" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="928" y="214" class="small">Liquidity effect:</text>
  <text x="928" y="231" class="small">r falls on impact</text>

  <line x1="908" y1="250" x2="965" y2="235" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="995" y="198" class="small">Income effect:</text>
  <text x="995" y="215" class="small">Y rises, r partly recovers</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: Monetary expansion shifts LM right. The immediate liquidity effect pushes the interest rate down; then stronger output raises money demand, so the interest rate partially recovers as the economy moves to the new equilibrium with higher Y and lower r than initially.*

## Further Resources

- 📺 **[IS-LM Model & Diagram – LM Curve Shift from a Monetary Shock](https://www.youtube.com/watch?v=b28lsOUFOtw)** — Economics in Many Lessons (12 min)
- 📺 **[Intermediate Macroeconomics 5/8: The IS-LM Model](https://www.youtube.com/watch?v=72tKKgw2eCM)** — Marginal Revolution University (15 min)
- 📚 **[RBA Explainer: Monetary Policy Implementation](https://www.rba.gov.au/education/resources/explainers/monetary-policy-implementation.html)** — How the RBA targets the cash rate

