# Lesson M15.L04: IS-LM and the Aggregate Demand Curve

**Module:** The IS-LM Model Part II
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the aggregate demand curve from the IS-LM model by varying the price level.
**Data as of:** 2024
**Provenance:** [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02 Principles of Macroeconomics](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023/)

## Explanation

The IS-LM model assumes a **fixed price level** *P* in the short run. The **aggregate demand (AD) curve** relaxes this assumption by asking: *what happens to equilibrium output Y as P varies?* Tracing IS-LM equilibria across different values of *P* traces out the AD curve.

**The mechanism:** The LM curve depends on **real money balances** *M/P*. For a given nominal money supply *M*:

- If *P* **rises** → *M/P* falls → LM shifts **left** → *r* rises → investment falls → equilibrium *Y* falls.
- If *P* **falls** → *M/P* rises → LM shifts **right** → *r* falls → investment rises → equilibrium *Y* rises.

This inverse relationship between *P* and equilibrium *Y* — holding *M*, *G*, and all other autonomous components constant — defines the **downward-sloping AD curve** in (*Y, P*) space. Each point on the AD curve corresponds to a specific IS-LM equilibrium.

**AD shifts (non-price shifts):** The AD curve shifts when anything other than *P* changes the IS or LM:

| Shift factor | AD effect |
|---|---|
| ↑ Government spending *G* | IS shifts right → AD shifts right |
| ↑ Nominal money supply *M* | LM shifts right → AD shifts right |
| ↑ Autonomous investment *Ī* | IS shifts right → AD shifts right |
| ↑ Consumer confidence (↑ *c₀*) | IS shifts right → AD shifts right |

**Connection to AD-AS:** The AD curve derived here feeds directly into the AD-AS model. Short-run equilibrium occurs at the intersection of AD and the Short-Run Aggregate Supply (SRAS) curve; long-run equilibrium involves SRAS adjusting to the LRAS. Understanding that the AD curve is grounded in IS-LM is essential for understanding *why* policy shifts AD and by how much.

**Notation:** *P* = price level; *M* = nominal money supply; *M/P* = real money balances; *r* = interest rate; *Y* = real output; IS: *Y = a − b_r × r*; LM: *M/P = kY − hr* → *Y = (M/P)/k + (h/k)r*.

## Worked Example

**Setup:**

- IS curve: *Y = 1200 − 200r* (r in %)
- LM curve derived from money market: *M/P = 0.5Y − 100r* → *Y = 2(M/P) + 200r*
- Nominal money supply: *M = 500* (fixed)

**Step 1 — Solve for equilibrium Y as a function of P:**

Substitute LM into IS to eliminate *r*:

From LM: *r = [Y − 2(M/P)] / 200*

Substitute into IS:
```
Y = 1200 − 200 × [Y − 2(M/P)] / 200
Y = 1200 − [Y − 2(M/P)]
Y = 1200 − Y + 2(M/P)
2Y = 1200 + 2(M/P)
Y = 600 + M/P
```

With *M = 500*: **Y = 600 + 500/P**

This is the **AD equation**: output falls as P rises (downward sloping).

**Step 2 — Compute two points on the AD curve:**

| Price Level *P* | *M/P = 500/P* | Equilibrium *Y = 600 + 500/P* | Interest rate *r* |
|---|---|---|---|
| P₁ = 1.0 | 500 | **1100** | See Step 3 |
| P₂ = 2.0 | 250 | **850** | See Step 3 |

**Step 3 — Find r at each price level:**

At *P₁ = 1* (M/P = 500):
```
LM: Y = 1000 + 200r
IS = LM: 1200 − 200r = 1000 + 200r
200 = 400r → r₁ = 0.5%
```

At *P₂ = 2* (M/P = 250):
```
LM: Y = 500 + 200r
IS = LM: 1200 − 200r = 500 + 200r
700 = 400r → r₂ = 1.75%
```

**Step 4 — Interpret:**

When P doubles from 1 to 2, real money balances halve, the LM shifts left, *r* rises from 0.5% to 1.75%, and equilibrium *Y* falls from 1100 to 850. The AD curve slopes downward.

**Step 5 — AD shift example (fiscal expansion):**

If *G* rises so that autonomous spending increases by 100 (IS shifts right to *Y = 1400 − 200r*):

```
New AD: Y = 700 + 500/P
```

At *P = 1*: new *Y = 1200* (up from 1100). AD curve shifts **rightward**.

## Common Misconception

**Misconception:** The aggregate demand curve slopes downward for the same reason as a microeconomic demand curve — because goods become cheaper when the price level falls.

**Correction:** The AD curve does **not** slope down because of the substitution or income effects that apply to individual goods markets. It slopes down through a **macroeconomic mechanism**: a lower price level raises real money balances *M/P*, which shifts the LM curve right, reducing the interest rate and stimulating investment and output. This is the **Keynes interest rate effect** (and, to a lesser extent, the wealth effect via real balances). Knowing the correct mechanism matters for policy: it means AD can be shifted by monetary or fiscal policy, not just by price changes.

## Practice Prompts

1. **Conceptual:** Using the IS-LM model, explain step-by-step why the AD curve slopes downward.
   → **Answer:** A rise in *P* → reduces real money balances *M/P* → LM curve shifts left → at any given *Y*, money market clears at a higher *r* → higher *r* reduces investment → lower *Y*. So higher *P* is associated with lower equilibrium *Y*, giving a downward-sloping AD curve.

2. **Numerical:** Using the model above (M = 500, IS: *Y = 1200 − 200r*), suppose P = 1.25. Calculate the equilibrium Y and r.
   → **Answer:**
   ```
   M/P = 500/1.25 = 400
   LM: Y = 2(400) + 200r = 800 + 200r
   IS = LM: 1200 − 200r = 800 + 200r
   400 = 400r → r = 1%
   Y = 1200 − 200(1) = 1000
   ```
   **At P = 1.25: Y = 1000, r = 1%.**

3. **Application:** The RBA's 2022–23 rate hikes raised the cash rate from 0.10% to 4.35%. In the IS-LM/AD framework, how do rising interest rates affect the AD curve, and what was the intended macroeconomic goal?
   → **Answer:** Higher interest rates effectively shift the **LM curve leftward** (or, in a model where the RBA targets *r* directly, can be thought of as shifting the AD curve leftward). For each price level, equilibrium *Y* is lower. This shifts the AD curve **left**, reducing aggregate demand and, with an upward-sloping SRAS, reducing inflationary pressure. The RBA's intent was to cool demand to bring CPI inflation (which peaked at 7.8% in Q4 2022) back toward its 2–3% target band.

## Visual — Deriving the Aggregate Demand Curve from IS-LM

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1400 430" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 15px Arial, sans-serif; fill: #222; }
    .small { font: 12px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>

  <!-- Left panel -->
  <text x="220" y="28" text-anchor="middle" class="title">Price level P₁</text>
  <line x1="70" y1="340" x2="370" y2="340" class="axis" />
  <line x1="70" y1="340" x2="70" y2="60" class="axis" />
  <text x="220" y="385" text-anchor="middle" class="label">Output, Y</text>
  <text x="22" y="205" transform="rotate(-90 22 205)" text-anchor="middle" class="label">Interest rate, r</text>
  <line x1="110" y1="120" x2="330" y2="290" class="curve" stroke="#d62728" />
  <line x1="120" y1="290" x2="320" y2="120" class="curve" stroke="#1f77b4" />
  <circle cx="216" cy="200" r="5" fill="#222" />
  <line x1="216" y1="200" x2="216" y2="340" class="guide" />
  <line x1="70" y1="200" x2="216" y2="200" class="guide" />
  <text x="302" y="291" class="label">IS</text>
  <text x="282" y="118" class="label">LM(P₁)</text>
  <text x="224" y="194" class="label">E₁</text>
  <text x="205" y="360" class="small">Y₁</text>
  <text x="48" y="205" class="small">r₁</text>

  <!-- Centre panel -->
  <text x="700" y="28" text-anchor="middle" class="title">Higher price level P₂ &gt; P₁</text>
  <line x1="550" y1="340" x2="850" y2="340" class="axis" />
  <line x1="550" y1="340" x2="550" y2="60" class="axis" />
  <text x="700" y="385" text-anchor="middle" class="label">Output, Y</text>
  <text x="502" y="205" transform="rotate(-90 502 205)" text-anchor="middle" class="label">Interest rate, r</text>
  <line x1="590" y1="120" x2="810" y2="290" class="curve" stroke="#d62728" />
  <line x1="610" y1="290" x2="800" y2="120" class="curve" stroke="#1f77b4" />
  <line x1="560" y1="290" x2="760" y2="120" class="curve" stroke="#6baed6" />
  <circle cx="666" cy="225" r="5" fill="#222" />
  <line x1="666" y1="225" x2="666" y2="340" class="guide" />
  <line x1="550" y1="225" x2="666" y2="225" class="guide" />
  <text x="782" y="291" class="label">IS</text>
  <text x="741" y="118" class="label">LM(P₁)</text>
  <text x="701" y="118" class="label">LM(P₂)</text>
  <text x="674" y="219" class="label">E₂</text>
  <text x="655" y="360" class="small">Y₂</text>
  <text x="529" y="230" class="small">r₂</text>

  <!-- Right panel -->
  <text x="1140" y="28" text-anchor="middle" class="title">Aggregate demand in (Y, P) space</text>
  <line x1="960" y1="340" x2="1310" y2="340" class="axis" />
  <line x1="960" y1="340" x2="960" y2="60" class="axis" />
  <text x="1135" y="385" text-anchor="middle" class="label">Output, Y</text>
  <text x="912" y="205" transform="rotate(-90 912 205)" text-anchor="middle" class="label">Price level, P</text>
  <line x1="1030" y1="120" x2="1250" y2="290" class="curve" stroke="#2ca02c" />
  <circle cx="1200" cy="155" r="5" fill="#222" />
  <circle cx="1085" cy="245" r="5" fill="#222" />
  <line x1="1200" y1="155" x2="1200" y2="340" class="guide" />
  <line x1="960" y1="155" x2="1200" y2="155" class="guide" />
  <line x1="1085" y1="245" x2="1085" y2="340" class="guide" />
  <line x1="960" y1="245" x2="1085" y2="245" class="guide" />
  <text x="1236" y="287" class="label">AD</text>
  <text x="1208" y="149" class="label">(Y₁, P₁)</text>
  <text x="1093" y="239" class="label">(Y₂, P₂)</text>
  <text x="1188" y="360" class="small">Y₁</text>
  <text x="1073" y="360" class="small">Y₂</text>
  <text x="938" y="160" class="small">P₁</text>
  <text x="938" y="250" class="small">P₂</text>

  <line x1="240" y1="180" x2="1020" y2="150" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <line x1="690" y1="220" x2="1095" y2="240" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="470" y="150" class="small">IS-LM equilibrium at P₁ maps to point (Y₁, P₁) on AD.</text>
  <text x="770" y="272" class="small">Higher P shifts LM left, giving lower Y and a point lower-left on AD.</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: Changing the price level changes real money balances and therefore the LM curve. A higher price level shifts LM left, raises the interest rate, lowers output, and traces out a downward-sloping aggregate demand curve in (Y, P) space.*

## Further Resources

- 📺 **[Deriving Aggregate Demand from IS-LM](https://www.youtube.com/watch?v=dH-V9fgDimY)** — Economics Tutorials (14 min)
- 📺 **[IS-LM Equations – Deriving the Aggregate Demand Equation](https://www.youtube.com/watch?v=5EPvwarCqDA)** — Economics in Many Lessons (10 min)
- 📚 **[MIT OCW 14.02 Lecture Notes – IS-LM and AD](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023/)** — Problem sets and lecture slides covering this derivation

