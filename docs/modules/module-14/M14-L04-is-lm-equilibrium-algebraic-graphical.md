# Lesson M14.L04: IS-LM Equilibrium: Graphical and Algebraic Analysis

**Module:** The IS-LM Model Part I
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Solve for IS-LM equilibrium income and interest rate using simultaneous equations.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023)

---

## Explanation

The IS-LM model determines simultaneous equilibrium in the **goods market** (IS curve) and the **money market** (LM curve). The unique intersection gives equilibrium output Y\* and equilibrium interest rate i\*.

**IS curve** (from M14.L01):

> i = A/b_inv − [(1 − b + m)/b_inv] × Y      ...(IS)

where A = a − bT̄ + Ī + Ḡ + X̄ is total autonomous spending, b = MPC, m = import propensity, and b_inv = interest sensitivity of investment.

**LM curve** (from M14.L03):

> i = (k/h)Y − M̄/(Ph)      ...(LM)

**Solving simultaneously:** Set IS = LM:

> A/b_inv − [(1 − b + m)/b_inv] × Y = (k/h)Y − M̄/(Ph)

Collect Y terms:

> A/b_inv + M̄/(Ph) = Y × [(1 − b + m)/b_inv + k/h]

Solve for Y\*:

$$Y^* = \frac{A/b_{inv} + \bar{M}/(Ph)}{(1-b+m)/b_{inv} + k/h}$$

Equivalently (multiplying numerator and denominator by b_inv × h):

$$Y^* = \frac{Ah + \bar{M}b_{inv}/P}{h(1-b+m) + kb_{inv}}$$

Substitute Y\* back into either IS or LM to solve for i\*.

**Uniqueness.** The IS curve has a negative slope in (Y, i) space; the LM curve has a positive slope. Two lines with opposite slopes always intersect at exactly one point — guaranteeing a unique equilibrium. This is the key structural property of the IS-LM model.

---

## Worked Example

**Parameters:**
- IS: A = 700, b_inv = 500, b = 0.8, m = 0.1 (so 1 − b + m = 0.3)
- LM: k = 0.25, h = 5,000, M̄ = 500, P = 1

**IS equation:**

> i = 700/500 − (0.3/500)Y = 1.4 − 0.0006Y      ...(IS)

**LM equation:**

> i = (0.25/5,000)Y − 500/(1 × 5,000) = 0.00005Y − 0.1      ...(LM)

**Step 1 — Set IS = LM:**

> 1.4 − 0.0006Y = 0.00005Y − 0.1
> 1.4 + 0.1 = 0.00005Y + 0.0006Y
> 1.5 = 0.00065Y
> Y\* = 1.5 / 0.00065

**Step 2 — Compute Y\*:**

> Y\* = 1.5 / 0.00065 = **2,307.7 ≈ $2,308bn**

**Step 3 — Substitute Y\* into LM to find i\*:**

> i\* = 0.00005 × 2,307.7 − 0.1 = 0.11538 − 0.1 = **0.01538 ≈ 1.54% (i\* = 0.0154)**

**Step 4 — Verify using IS:**

> i = 1.4 − 0.0006 × 2,307.7 = 1.4 − 1.38462 = **0.01538 ≈ 1.54% ✓** (matches LM)

**Interpretation:** The IS-LM equilibrium is approximately Y\* = $2,308bn and i\* ≈ 1.54% (expressed as a decimal: 0.0154). At this combination, both the goods market and the money market clear simultaneously. The equilibrium interest rate of 1.54% is consistent with a realistic Australian short-run rate, confirming that both curves are now calibrated in the same units (i expressed as a decimal, where 0.0154 = 1.54%).

---

## Common Misconception

**Misconception:** In the IS-LM model, the interest rate is determined only by the money market, and output is determined only by the goods market.

**Correction:** Both Y\* and i\* are determined *jointly* by the simultaneous intersection of IS and LM. The IS curve alone cannot determine Y without knowing i (because investment depends on i). The LM curve alone cannot determine i without knowing Y (because money demand depends on Y). The interaction between markets is the defining feature: a change in the goods market (e.g., fiscal expansion shifts IS) affects the money market (higher Y raises money demand, raising i), which in turn feeds back to investment. Partial equilibrium analysis of either market in isolation gives an incorrect answer.

---

## Practice Prompts

1. Explain why the IS-LM model necessarily produces a unique equilibrium. What would happen geometrically if both curves had the same sign slope?
   → **Answer:** Uniqueness follows from the IS curve having a negative slope (goods market) and the LM curve having a positive slope (money market). Two lines with opposite slopes always cross exactly once. If both curves had positive slopes, they could be parallel (no intersection), coincide (infinite intersections), or cross once — none of which guarantees a unique, stable equilibrium. The opposite slopes arise from distinct economic logic: IS reflects the investment-income multiplier (negative: higher i → lower Y), while LM reflects money demand-supply balancing (positive: higher Y → higher i). The sign difference is not a coincidence but a structural feature of the two markets.

2. Using IS: i = 2.0 − 0.0008Y and LM: i = 0.004Y − 8, solve for Y\* and i\*.
   → **Answer:**
   - Set IS = LM: 2.0 − 0.0008Y = 0.004Y − 8
   - 2.0 + 8 = 0.004Y + 0.0008Y
   - 10 = 0.0048Y
   - Y\* = 10/0.0048 = **$2,083.3bn**
   - i\* = 0.004 × 2,083.3 − 8 = 8.333 − 8 = **0.333% (i\* = 0.00333)**
   - Verify via IS: i = 2.0 − 0.0008 × 2,083.3 = 2.0 − 1.667 = **0.333% ✓**

3. In the IS-LM model, suppose a negative demand shock (e.g., a fall in consumer confidence) reduces autonomous spending A by $100bn. Using the IS equation i = A/b_inv − [(1−b+m)/b_inv]Y, explain qualitatively (without full algebra) how the new equilibrium Y\* and i\* compare to the original, and what this implies for policy.
   → **Answer:** A fall in A shifts the IS curve leftward: at every income level, the interest rate consistent with goods market equilibrium is lower (less autonomous spending → lower Y needed at any i). The IS curve shifts left. Moving along the LM curve to the new intersection, both Y\* and i\* fall: output declines (recession) and the interest rate drops. The lower i provides a partial automatic offset (higher investment partially cushions the demand shock) — this is the "crowding in" effect in reverse. Policy implications: fiscal expansion (increase G or cut T) shifts IS rightward back toward the original position; or monetary expansion (increase M̄) shifts LM rightward, lowering i further and partially restoring Y via the investment channel. The appropriate mix depends on how interest-sensitive investment is (b_inv) and the fiscal multiplier magnitude.

## Visual — IS-LM Equilibrium and a Negative Demand Shock

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1100 420" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 16px Arial, sans-serif; fill: #222; }
    .small { font: 13px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>

  <text x="550" y="28" text-anchor="middle" class="title">IS-LM equilibrium in (Y, i) space</text>
  <line x1="90" y1="340" x2="1010" y2="340" class="axis" />
  <line x1="90" y1="340" x2="90" y2="60" class="axis" />
  <text x="550" y="390" text-anchor="middle" class="label">Output / income, Y</text>
  <text x="35" y="205" transform="rotate(-90 35 205)" text-anchor="middle" class="label">Interest rate, i</text>

  <line x1="170" y1="130" x2="760" y2="300" class="curve" stroke="#d62728" />
  <line x1="270" y1="90" x2="860" y2="260" class="curve" stroke="#ff9896" />
  <line x1="240" y1="300" x2="760" y2="110" class="curve" stroke="#1f77b4" />

  <circle cx="566" cy="180" r="5" fill="#222" />
  <circle cx="466" cy="216" r="5" fill="#222" />
  <line x1="566" y1="180" x2="566" y2="340" class="guide" />
  <line x1="90" y1="180" x2="566" y2="180" class="guide" />
  <line x1="466" y1="216" x2="466" y2="340" class="guide" />
  <line x1="90" y1="216" x2="466" y2="216" class="guide" />

  <text x="640" y="305" class="label">IS: i = A/b_inv − [(1−b+m)/b_inv]Y</text>
  <text x="705" y="262" class="small">IS′ after A falls</text>
  <text x="635" y="110" class="label">LM: i = (k/h)Y − M̄/(Ph)</text>
  <text x="576" y="174" class="label">E₀</text>
  <text x="476" y="210" class="label">E₁</text>
  <text x="547" y="360" class="small">Y₀</text>
  <text x="447" y="360" class="small">Y₁</text>
  <text x="64" y="186" class="small">i₀</text>
  <text x="64" y="222" class="small">i₁</text>

  <line x1="545" y1="195" x2="492" y2="210" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="610" y="225" class="small">Negative demand shock shifts IS left:</text>
  <text x="645" y="243" class="small">equilibrium Y and i both fall.</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: The IS and LM curves intersect once, giving unique equilibrium output and interest rate. A negative demand shock reduces autonomous spending, shifts the IS curve left, and moves the economy to lower output and a lower interest rate.*

## Further Resources
- 📺 **[Macroeconomics: The IS-LM Model](https://www.youtube.com/watch?v=e_3clidGpfE)** — Economics in Many Lessons (15 min)
- 📺 **[Macroeconomics: The IS Curve](https://www.youtube.com/watch?v=g6aba0V6ifo)** — Economics in Many Lessons (15 min)
- 📚 **[RBA — Monetary Policy Explainer](https://www.rba.gov.au/education/resources/explainers/monetary-policy.html)** — IS-LM equilibrium and its application to Australian monetary and fiscal policy analysis

