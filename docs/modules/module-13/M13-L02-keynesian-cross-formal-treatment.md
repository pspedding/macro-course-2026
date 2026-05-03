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

## Visual — Keynesian Cross and the Multiplier

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1100 430" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 16px Arial, sans-serif; fill: #222; }
    .small { font: 13px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>
  <text x="550" y="28" text-anchor="middle" class="title">The Keynesian cross</text>
  <line x1="90" y1="350" x2="1030" y2="350" class="axis" />
  <line x1="90" y1="350" x2="90" y2="60" class="axis" />
  <text x="560" y="398" text-anchor="middle" class="label">Output / income, Y</text>
  <text x="34" y="205" transform="rotate(-90 34 205)" text-anchor="middle" class="label">Aggregate expenditure, AE</text>

  <line x1="120" y1="320" x2="980" y2="90" class="curve" stroke="#444" />
  <line x1="120" y1="285" x2="900" y2="160" class="curve" stroke="#d62728" />
  <line x1="120" y1="245" x2="980" y2="105" class="curve" stroke="#ff9896" />

  <circle cx="612" cy="189" r="5" fill="#222" />
  <circle cx="762" cy="149" r="5" fill="#222" />
  <line x1="612" y1="189" x2="612" y2="350" class="guide" />
  <line x1="90" y1="189" x2="612" y2="189" class="guide" />
  <line x1="762" y1="149" x2="762" y2="350" class="guide" />
  <line x1="90" y1="149" x2="762" y2="149" class="guide" />

  <text x="884" y="93" class="label">45° line: Y = AE</text>
  <text x="792" y="164" class="label">AE₀</text>
  <text x="878" y="110" class="label">AE₁</text>
  <text x="126" y="278" class="small">Intercept = a − bT̄ + Ī + Ḡ + X̄</text>
  <text x="126" y="238" class="small">Autonomous-demand increase shifts AE upward</text>
  <text x="620" y="183" class="label">E₀</text>
  <text x="770" y="143" class="label">E₁</text>
  <text x="600" y="370" class="small">Y₀</text>
  <text x="750" y="370" class="small">Y₁</text>
  <text x="790" y="194" class="label">slope = b − m</text>

  <line x1="1020" y1="149" x2="1020" y2="189" stroke="#555" stroke-width="2" marker-start="url(#arrowRev)" marker-end="url(#arrow)" />
  <text x="1034" y="174" class="small">Multiplier gap</text>
  <line x1="140" y1="282" x2="140" y2="242" stroke="#555" stroke-width="2" marker-start="url(#arrowRev)" marker-end="url(#arrow)" />
  <text x="150" y="266" class="small">ΔA</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
    <marker id="arrowRev" markerWidth="10" markerHeight="10" refX="1" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M9,0 L9,6 L0,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: The AE line crosses the 45° line where planned expenditure equals output. A rise in autonomous spending shifts AE upward and increases equilibrium income by more than the initial shift — the multiplier effect.*

## Further Resources
- 📺 **[Keynesian cross and the multiplier](https://www.youtube.com/watch?v=aSY8XPGChAU)** — Khan Academy (8 min)
- 📺 **[Fiscal Policy and Stimulus: Crash Course Economics #8](https://www.youtube.com/watch?v=otmgFQHbaDo)** — Crash Course (12 min)
- 📚 **[RBA — Fiscal Policy Explainer](https://www.rba.gov.au/education/resources/explainers/fiscal-policy.html)** — Keynesian cross mechanics and the formal derivation of the spending multiplier
