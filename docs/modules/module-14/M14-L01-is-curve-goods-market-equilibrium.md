# Lesson M14.L01: The IS Curve: Goods Market Equilibrium

**Module:** The IS-LM Model Part I
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the IS curve by tracing goods market equilibrium across different interest rates.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023) | [RBA](https://www.rba.gov.au)

---

## Explanation

!!! info "Key Diagram"
    ![Figure 5: The IS-LM Model. The IS curve (goods market) and LM curve (money market) intersect at equilibrium output Y* and interest rate i*.](../../assets/diagrams/05-is-lm.png)  
    *Figure 5: The IS-LM Model. The IS curve (goods market) and LM curve (money market) intersect at equilibrium output Y* and interest rate i*.*


The IS curve maps all combinations of output (Y) and the interest rate (i) at which the **goods market is in equilibrium** (planned expenditure equals output). It is derived by embedding the interest-sensitive investment function into the Keynesian cross.

**Setup.** Introduce I = Ī − bi (from M13.L03) into the Keynesian cross:

> Y = C + I + G + NX
> Y = (a + b_c(Y − T̄)) + (Ī − bi) + Ḡ + (X̄ − mY)

*Note: to avoid symbol clash, let b_c = MPC and b_i = interest sensitivity of investment. In what follows b_c is written as b and the investment sensitivity as b_inv, consistent with standard notation where context distinguishes them.*

Using b for MPC throughout and b_inv for interest sensitivity of investment:

> Y(1 − b + m) = a − bT̄ + Ī − b_inv·i + Ḡ + X̄

Solving for Y:

$$Y = \frac{a - b\bar{T} + \bar{I} - b_{inv}\cdot i + \bar{G} + \bar{X}}{1 - b + m}$$

To express as the IS curve, rearrange for i as a function of Y:

> (1 − b + m)Y = a − bT̄ + Ī + Ḡ + X̄ − b_inv·i
> b_inv·i = a − bT̄ + Ī + Ḡ + X̄ − (1 − b + m)Y
> i = [a − bT̄ + Ī + Ḡ + X̄ − (1 − b + m)Y] / b_inv

Define autonomous spending A = a − bT̄ + Ī + Ḡ + X̄:

$$i = \frac{A}{b_{inv}} - \frac{(1-b+m)}{b_{inv}} Y$$

**Slope:** The IS curve has a **negative slope** in (Y, i) space: di/dY = −(1 − b + m)/b_inv < 0.

**Steepness:** The curve is steeper when (1 − b + m)/b_inv is large — i.e., when b (MPC) is lower (more leakage to saving), m is higher (more import leakage), or b_inv is smaller (investment less responsive to interest rates).

**Shifts:** IS shifts **right** (more output at given i) when G↑, T̄↓, X̄↑, or a↑ (any rise in autonomous spending). IS shifts **left** when G↓, T̄↑, X̄↓.

---

## Worked Example

**Parameters:** a = 200, b = 0.8 (MPC), T̄ = 100, Ī = 150, Ḡ = 250, X̄ = 180, m = 0.1, b_inv = 500 (interest sensitivity of investment).

**Step 1 — Compute autonomous spending A:**

> A = a − bT̄ + Ī + Ḡ + X̄
> = 200 − (0.8)(100) + 150 + 250 + 180
> = 200 − 80 + 150 + 250 + 180 = **700**

**Step 2 — Write the IS curve (Y as function of i):**

> Y = (700 − 500i) / (1 − 0.8 + 0.1) = (700 − 500i) / 0.3

**Step 3 — Find Y\* when i = 0.04 (4%):**

> Y = (700 − 500 × 0.04) / 0.3 = (700 − 20) / 0.3 = 680 / 0.3 = **$2,267bn**

**Step 4 — Find Y\* when i = 0.07 (7%):**

> Y = (700 − 500 × 0.07) / 0.3 = (700 − 35) / 0.3 = 665 / 0.3 = **$2,217bn**

**Step 5 — Compute the IS slope (i as function of Y):**

> i = 700/500 − (0.3/500)Y = 1.4 − 0.0006Y

A 1-unit increase in Y reduces i by 0.0006 percentage points; equivalently, a 1 percentage point rise in i reduces Y by 1/0.0006 ≈ **$1,667bn** (the horizontal shift in Y for a given Δi).

---

## Common Misconception

**Misconception:** The IS curve slopes downward because lower interest rates directly stimulate consumer spending on goods.

**Correction:** In the standard model, the interest rate affects the goods market *through investment*, not directly through consumption. Lower i → higher I (via I = Ī − b_inv·i) → higher autonomous spending → higher equilibrium Y via the multiplier. The consumption function C = a + b(Y − T̄) responds to income, not directly to i (in the basic model). The IS curve's negative slope is entirely the investment-multiplier channel.

---

## Practice Prompts

1. List three exogenous shocks that would shift the IS curve to the right, and explain the channel through which each operates.
   → **Answer:** (1) **Government spending increase (ΔḠ > 0):** Raises autonomous spending directly; at any given interest rate, equilibrium Y is higher. (2) **Tax cut (ΔT̄ < 0):** Raises household disposable income, boosting consumption (ΔC = b × |ΔT̄|), shifting IS right. (3) **Export boom (ΔX̄ > 0):** Raises autonomous net exports, increasing aggregate expenditure at every i; Y* rises via multiplier. All three increase A, the numerator of the IS equation, shifting IS rightward.

2. Using b = 0.8, m = 0.15, T̄ = 150, a = 180, Ī = 200, Ḡ = 220, X̄ = 160, b_inv = 400, compute equilibrium Y when i = 0.05 (5%) and when i = 0.10 (10%). What is ΔY from the interest rate rise?
   → **Answer:**
   - A = 180 − (0.8)(150) + 200 + 220 + 160 = 180 − 120 + 200 + 220 + 160 = **640**
   - Denominator: 1 − 0.8 + 0.15 = **0.35**
   - At i = 0.05: Y = (640 − 400 × 0.05)/0.35 = (640 − 20)/0.35 = 620/0.35 = **$1,771bn**
   - At i = 0.10: Y = (640 − 400 × 0.10)/0.35 = (640 − 40)/0.35 = 600/0.35 = **$1,714bn**
   - ΔY = 1,714 − 1,771 = **−$57bn** (a 5pp interest rate rise reduces output by $57bn)

3. During 2022–2023, the RBA raised the cash rate from 0.10% to 4.35% — a rise of 425 basis points. Using the IS framework, explain through which channels this would have reduced Australian GDP, and why the effect may have been larger than a simple model predicts.
   → **Answer:** Via the IS channel: higher i reduces investment (I = Ī − b_inv·i falls), shifting the economy up the IS curve (or equivalently, reducing autonomous expenditure, lowering Y* via the multiplier). Additional channels beyond the basic model: (1) **Mortgage cash flow:** Australia has a high proportion of variable-rate mortgages; rate rises rapidly increased mortgage repayments, directly reducing household disposable income and consumption — equivalent to a tax increase. (2) **Consumer confidence:** Rate rises signalled future tightening, reducing autonomous consumption a. (3) **Housing investment collapse:** Rising rates decimated new housing construction (dwelling investment fell ~15% in 2023). These amplifying channels made the RBA's tightening more powerful than the basic model's investment-only channel implies.

## Visual — The IS Curve: Movements and Shifts

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

  <text x="300" y="28" text-anchor="middle" class="title">Movement along the IS curve</text>
  <line x1="80" y1="340" x2="520" y2="340" class="axis" />
  <line x1="80" y1="340" x2="80" y2="60" class="axis" />
  <text x="300" y="388" text-anchor="middle" class="label">Output, Y</text>
  <text x="28" y="205" transform="rotate(-90 28 205)" text-anchor="middle" class="label">Interest rate, i</text>
  <line x1="140" y1="120" x2="470" y2="290" class="curve" stroke="#d62728" />
  <circle cx="240" cy="171" r="5" fill="#222" />
  <circle cx="360" cy="233" r="5" fill="#222" />
  <line x1="240" y1="171" x2="240" y2="340" class="guide" />
  <line x1="360" y1="233" x2="360" y2="340" class="guide" />
  <line x1="80" y1="171" x2="240" y2="171" class="guide" />
  <line x1="80" y1="233" x2="360" y2="233" class="guide" />
  <text x="388" y="292" class="label">IS</text>
  <text x="180" y="104" class="label">intercept = A/b_inv</text>
  <text x="272" y="197" class="label">slope = −(1−b+m)/b_inv</text>
  <text x="219" y="166" class="small">(Y₁, i₁)</text>
  <text x="339" y="228" class="small">(Y₂, i₂)</text>
  <line x1="252" y1="177" x2="347" y2="226" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="130" y="314" class="small">Higher i reduces planned investment and lowers Y.</text>

  <text x="895" y="28" text-anchor="middle" class="title">Fiscal expansion shifts IS right</text>
  <line x1="670" y1="340" x2="1120" y2="340" class="axis" />
  <line x1="670" y1="340" x2="670" y2="60" class="axis" />
  <text x="895" y="388" text-anchor="middle" class="label">Output, Y</text>
  <text x="618" y="205" transform="rotate(-90 618 205)" text-anchor="middle" class="label">Interest rate, i</text>
  <line x1="730" y1="140" x2="1050" y2="300" class="curve" stroke="#d62728" />
  <line x1="790" y1="110" x2="1110" y2="270" class="curve" stroke="#ff9896" />
  <line x1="670" y1="205" x2="950" y2="205" class="guide" />
  <circle cx="850" cy="205" r="5" fill="#222" />
  <circle cx="910" cy="205" r="5" fill="#222" />
  <line x1="850" y1="205" x2="850" y2="340" class="guide" />
  <line x1="910" y1="205" x2="910" y2="340" class="guide" />
  <text x="1000" y="300" class="label">IS₀</text>
  <text x="1060" y="270" class="label">IS₁</text>
  <text x="832" y="225" class="small">Y₀</text>
  <text x="892" y="225" class="small">Y₁</text>
  <line x1="860" y1="190" x2="900" y2="190" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="760" y="156" class="small">ΔḠ &gt; 0 raises autonomous spending</text>
  <text x="760" y="174" class="small">and shifts the IS curve right.</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: The IS curve is downward sloping because higher interest rates reduce investment and equilibrium output. A fiscal expansion raises autonomous demand and shifts the whole IS curve to the right.*

## Further Resources
- 📺 **[Macroeconomics: The IS Curve](https://www.youtube.com/watch?v=g6aba0V6ifo)** — Economics in Many Lessons (15 min)
- 📺 **[Macroeconomics: The IS-LM Model](https://www.youtube.com/watch?v=e_3clidGpfE)** — Economics in Many Lessons (15 min)
- 📚 **[RBA — Monetary Policy Explainer](https://www.rba.gov.au/education/resources/explainers/monetary-policy.html)** — Goods market equilibrium and how the IS curve underpins RBA modelling
