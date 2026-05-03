# Lesson M16.L03: The Original Phillips Curve

**Module:** The Labour Market and Phillips Curve
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Interpret the empirical Phillips curve as a stable short-run inflation-unemployment trade-off.
**Data as of:** 2024
**Provenance:** [ABS Labour Force, Australia](https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia) | [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

## Explanation

In 1958, A.W. **Phillips** published a landmark paper documenting a stable, downward-sloping relationship between **unemployment** and **wage inflation** in the United Kingdom from 1861 to 1957. Samuelson and Solow (1960) reformulated this relationship for the United States using **price inflation** in place of wage inflation, making it directly policy-relevant.

The original Phillips curve offers policymakers an apparent **menu of choice**: a lower unemployment rate can be achieved at the cost of higher inflation, and vice versa. The short-run Phillips curve (SRPC) can be written:

> **π = π̄ − α(u − u_n)**

where:
- *π* = actual inflation rate
- *π̄* = baseline inflation (the inflation rate when *u = u_n*)
- *α* = slope parameter (how much inflation rises per percentage point fall in unemployment)
- *u* = actual unemployment rate
- *u_n* = natural rate of unemployment (NAIRU)

When *u < u_n* (labour market is tight), inflation rises above *π̄*. When *u > u_n*, inflation falls below *π̄*.

**Okun's Law** provides the bridge between output gaps and unemployment: a 1 percentage point rise in unemployment is associated with approximately 2% fall in output relative to potential — so the PC can also be expressed in terms of the output gap (*Y − Y*).

**Australia 1960s–70s:** Australia experienced the classic Phillips curve trade-off. Unemployment was held near 2% through the 1960s, associated with inflation of 3–4%. The 1970s wage explosion and oil shocks broke the stable relationship — foreshadowing Friedman and Phelps's critique (M16.L04).

**Important caveat:** The original stable Phillips curve was an *empirical regularity* under conditions of **stable inflation expectations**. When expectations became unanchored (1970s), the curve broke down. The original formulation implicitly assumed *π̄* was fixed — an assumption demolished by the stagflation of the 1970s.

**Notation:** *π* = inflation; *π̄* = baseline inflation; *u* = unemployment rate; *u_n* = NAIRU; *α* = Phillips curve slope; *Y* = real output; *Y** = potential output.

## Worked Example

**Setup:**

- Phillips curve: *π = 3 − 0.5(u − 5)*  [*π̄* = 3%, *u_n* = 5%, *α* = 0.5]

**Step 1 — Compute inflation at various unemployment rates:**

| Unemployment *u* (%) | *u − u_n* | *π = 3 − 0.5(u − 5)* (%) |
|---|---|---|
| 3 | −2 | 3 − 0.5(−2) = **4.0** |
| 4 | −1 | 3 − 0.5(−1) = **3.5** |
| 5 | 0 | 3 − 0 = **3.0** |
| 6 | +1 | 3 − 0.5(1) = **2.5** |
| 7 | +2 | 3 − 0.5(2) = **2.0** |

**Step 2 — Policy trade-off:**

Suppose a government wants to reduce unemployment from 5% to 3% (a stimulus policy):

```
Δu = 3% − 5% = −2 percentage points
Δπ = −α × Δu = −0.5 × (−2) = +1 percentage point
```

Inflation rises from 3% to **4%**. The cost of 2 pp lower unemployment is 1 pp higher inflation.

**Step 3 — Okun's Law connection:**

Okun's Law: a 1 pp fall in *u* ↔ ≈ 2% rise in *Y* above potential.

If unemployment falls from 5% to 3% (Δu = −2 pp):

```
ΔY/Y* ≈ −2 × (−2) = +4%
```

Output rises approximately 4% above potential when unemployment is 2 pp below the NAIRU.

**Step 4 — Reading the diagram:**

The Phillips curve plots points (*u*, *π*):
- (3%, 4%): tight labour market, high inflation
- (5%, 3%): at NAIRU, stable inflation
- (7%, 2%): slack labour market, low inflation

Policymakers can pick any point on this curve by adjusting aggregate demand.

## Common Misconception

**Misconception:** The Phillips curve is a structural (permanently stable) relationship that policymakers can exploit indefinitely.

**Correction:** The original Phillips curve was stable only because inflation expectations were **anchored** (agents expected roughly constant low inflation). Once policymakers exploited the curve repeatedly, workers and firms learned to incorporate higher inflation into their expectations. This shifted the curve upward (as Friedman and Phelps predicted — see M16.L04). The 1970s stagflation — simultaneously high inflation and high unemployment — destroyed the view of the original PC as a permanent policy menu. The curve exists only as a **short-run** relationship, conditional on fixed inflation expectations.

## Practice Prompts

1. **Conceptual:** Phillips (1958) plotted **wage** inflation against unemployment, while Samuelson and Solow (1960) used **price** inflation. Why is the distinction important for policy?
   → **Answer:** Wage inflation and price inflation are related but not identical: prices depend on wages **and** labour productivity. If productivity growth is 2% per year, firms can pay wages 2% faster without raising prices. Price inflation better captures the central bank's mandate (inflation targeting). The Samuelson-Solow reformulation to price inflation made the trade-off directly usable for monetary policymakers whose instrument is the interest rate aimed at price stability.

2. **Numerical:** Using the Phillips curve *π = 3 − 0.5(u − 5)*: (a) At what unemployment rate is inflation exactly zero? (b) If the government wants to achieve exactly 2% inflation, what unemployment rate is required?
   → **Answer:**
   ```
   (a) Set π = 0:
       0 = 3 − 0.5(u − 5)
       0.5(u − 5) = 3
       u − 5 = 6
       u = 11%
       (Inflation = 0 requires unemployment of 11% — very high)

   (b) Set π = 2:
       2 = 3 − 0.5(u − 5)
       0.5(u − 5) = 1
       u − 5 = 2
       u = 7%
   ```
   To achieve 2% inflation along this curve, unemployment must be 7%.

3. **Application:** In the 1960s, Australian unemployment averaged around 1.5–2%, significantly below the later NAIRU estimates of 4–5%. Using the Phillips curve framework, what would this imply about inflation during that decade, and is this consistent with what actually happened?
   → **Answer:** If *u_n* ≈ 5% and actual *u* ≈ 2%, then *u − u_n* = −3, and the Phillips curve predicts inflation well above baseline. Indeed, Australian CPI inflation averaged approximately 3–4% in the 1960s — elevated relative to the post-1990s period but manageable at the time. The stable relationship held for roughly a decade before the 1970s oil shocks and wage explosion broke it. This is consistent with the "Golden Age" of low unemployment and moderate inflation predicted by an unexploited Phillips curve trade-off.

## Visual — The Original Phillips Curve

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1050 420" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 16px Arial, sans-serif; fill: #222; }
    .small { font: 13px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>

  <text x="525" y="28" text-anchor="middle" class="title">Original Phillips curve: short-run inflation-unemployment trade-off</text>
  <line x1="90" y1="340" x2="980" y2="340" class="axis" />
  <line x1="90" y1="340" x2="90" y2="60" class="axis" />
  <text x="535" y="388" text-anchor="middle" class="label">Unemployment rate, u (%)</text>
  <text x="35" y="200" transform="rotate(-90 35 200)" text-anchor="middle" class="label">Inflation, π (%)</text>

  <path d="M 230 140 Q 400 205 610 245 Q 760 275 860 295" class="curve" stroke="#d62728" />
  <line x1="490" y1="70" x2="490" y2="340" class="guide" />
  <circle cx="330" cy="160" r="5" fill="#222" />
  <circle cx="490" cy="205" r="5" fill="#222" />
  <circle cx="650" cy="250" r="5" fill="#222" />

  <text x="344" y="154" class="label">(3%, 4%)</text>
  <text x="504" y="199" class="label">(5%, 3%)</text>
  <text x="664" y="244" class="label">(7%, 2%)</text>
  <text x="500" y="88" class="label">uₙ = 5%</text>
  <text x="585" y="183" class="label">slope α = 0.5</text>
  <text x="780" y="305" class="label">Phillips curve</text>

  <line x1="680" y1="270" x2="360" y2="175" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <text x="675" y="170" class="small">Expansionary policy:</text>
  <text x="675" y="188" class="small">move up/left to lower u, higher π</text>
  <text x="675" y="220" class="small">Contractionary policy:</text>
  <text x="675" y="238" class="small">move down/right to higher u, lower π</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: The original Phillips curve shows an apparent short-run trade-off between unemployment and inflation. Moving leftward along the curve lowers unemployment but raises inflation; the dashed vertical line marks the NAIRU at 5%.*

## Further Resources

- 📺 **[The Phillips Curve – Inflation vs Unemployment](https://www.youtube.com/watch?v=55hpwVWwdnw)** — Enhance Tuition Economics (9 min)
- 📺 **[Macro Problem – Trade-Off Between Inflation, Unemployment and GDP](https://www.youtube.com/watch?v=q3Uey9ladUg)** — Economics in Many Lessons (12 min)
- 📚 **[OpenStax Macro 3e – Chapter 25: The Phillips Curve](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))** — Free textbook chapter with Australian-relevant examples

