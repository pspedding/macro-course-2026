# Lesson M16.L04: The Expectations-Augmented Phillips Curve

**Module:** The Labour Market and Phillips Curve
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the vertical long-run Phillips curve from the expectations-augmented model.
**Data as of:** 2024
**Provenance:** [Reserve Bank of Australia](https://www.rba.gov.au) | [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

## Explanation

Milton **Friedman** (1968) and Edmund **Phelps** (1968) independently showed that the stable, exploitable Phillips curve of the 1960s rested on a crucial assumption: that workers and firms had **fixed (non-adaptive) inflation expectations**. Once expectations are allowed to adjust, the long-run trade-off between inflation and unemployment disappears.

**Derivation from the WS-PS framework:**

Starting from the nominal wage-setting (WS) and price-setting (PS) relations:

$$W = P^e(1 - \alpha u + z)$$

$$P = (1 + \mu)W$$

Substitute WS into PS:

$$P = (1 + \mu)P^e(1 - \alpha u + z)$$

Taking percentage changes (approximation for small changes):

$$\pi \approx \pi^e + \text{(percentage change in } [1 - \alpha u + z] \times (1 + \mu)\text{)}$$

In the linearised version commonly used at intermediate level:

$$\pi = \pi^e - \alpha(u - u_n)$$

where:
- *π* = actual inflation
- *π^e* = expected inflation
- *α* = slope of PC (sensitivity of inflation to unemployment gap)
- *u − u_n* = unemployment gap (negative when labour market is tight)

**Key results:**

1. **Short run** (*π^e* fixed): standard downward-sloping PC — lower *u* → higher *π*. Same as the original PC for a given *π^e*.

2. **Long run** (*π^e = π*): substituting into the EAPC:
   $$\pi = \pi - \alpha(u - u_n) \Rightarrow 0 = -\alpha(u - u_n) \Rightarrow u = u_n$$
   The long-run PC is **vertical at u = u_n**. In the long run, output cannot be permanently held above (or below) the natural rate.

**Adaptive expectations:** Friedman assumed agents update expectations based on past inflation:

$$\pi^e_t = \pi_{t-1}$$

(simple adaptive expectations)

This means any inflationary shock (or policy-induced fall in *u* below *u_n*) eventually shifts the short-run PC upward.

**Australia 1990:** The RBA deliberately caused a recession (cash rate reached 17.5% in January 1990) to break entrenched high inflation expectations. Unemployment rose to ~10.8% (1992) — well above *u_n* — shifting inflation expectations sharply downward. By 1993, inflation was below 2% and the RBA introduced its 2–3% target band. **Anchored expectations** are the legacy of this painful adjustment.

**Notation:** *π* = actual inflation; *π^e* = expected inflation; *u* = unemployment; *u_n* = NAIRU; *α* = PC slope.

## Worked Example

**Setup:**

- EAPC: *π = π^e − 0.5(u − 5)*  [α = 0.5, u_n = 5%]
- Adaptive expectations: *π^e_t = π_{t-1}*
- Policy: government holds *u = 3%* indefinitely starting in Period 1

**Period 0 — Baseline (u = 5%, stable inflation):**

```
π^e₀ = 2% (initial anchored expectations)
π₀ = 2 − 0.5(5 − 5) = 2%
u = u_n: stable equilibrium.
```

**Period 1 — Expansionary policy drives u = 3%:**

```
π^e₁ = π₀ = 2%  (adaptive: expect last period's inflation)
π₁ = 2 − 0.5(3 − 5) = 2 − 0.5(−2) = 2 + 1 = 3%
```

Output is above potential, inflation rises to 3%.

**Period 2 — Expectations catch up:**

```
π^e₂ = π₁ = 3%  (expectations adjust upward)
π₂ = 3 − 0.5(3 − 5) = 3 + 1 = 4%
```

Inflation rises again to 4%, even though *u* is still at 3%.

**Period 3 — Expectations adjust again:**

```
π^e₃ = π₂ = 4%
π₃ = 4 − 0.5(3 − 5) = 4 + 1 = 5%
```

Inflation is now 5% — and accelerating. **As long as u < u_n, inflation keeps rising.**

**Summary table:**

| Period | *u* (%) | *π^e* (%) | *π* (%) |
|---|---|---|---|
| 0 (baseline) | 5 | 2 | 2 |
| 1 | 3 | 2 | 3 |
| 2 | 3 | 3 | 4 |
| 3 | 3 | 4 | 5 |

**Interpretation:** Holding *u* below *u_n* causes **accelerating inflation**. The only way to stabilise inflation is to return *u* to *u_n* (the NAIRU), which is why the NAIRU is the *Non-Accelerating Inflation* rate. The short-run PC shifts upward each period as *π^e* adjusts.

**Long-run result:** If the government eventually abandons the policy and *u* returns to 5%, inflation will stabilise at 5% (not back to 2%) — disinflation requires a period of *u > u_n*.

## Common Misconception

**Misconception:** Because the long-run PC is vertical, monetary policy has no effect on output even in the short run.

**Correction:** The vertical **long-run** PC only says that **permanently** holding *u < u_n* is infeasible — it generates accelerating inflation. In the **short run**, while expectations are adjusting, monetary expansion *does* reduce unemployment and raise output. The EAPC framework says nothing about the **speed** of expectation adjustment. If expectations are slow to adjust (sticky), monetary policy has real effects for an extended period. This is the Keynesian-monetarist synthesis: real effects in the short run, purely nominal in the long run.

## Practice Prompts

1. **Conceptual:** Using the EAPC diagram with multiple short-run Phillips curves, show what happens to inflation and unemployment when the central bank maintains *u < u_n* for three consecutive periods.
   → **Answer:** Start on SRPC₁ at (*u_n*, π̄). Period 1: move left along SRPC₁ to (*u < u_n*, *π₁ > π̄*). Expectations adjust: SRPC shifts up to SRPC₂. Period 2: at the same *u*, we are now on SRPC₂ at a higher inflation rate (*π₂ > π₁*). SRPC shifts up again to SRPC₃. Period 3: inflation rises further to *π₃ > π₂*. Each period, the SRPC shifts upward by the amount *π^e* increases. Inflation is continuously rising — consistent with the numerical example above.

2. **Numerical:** Using the EAPC *π = π^e − 0.5(u − 5)* with adaptive expectations (*π^e_t = π_{t-1}*), suppose the government drives *u* to 4% starting from a stable equilibrium at *π₀ = π^e₀ = 3%*. Compute *π₁*, *π₂*, and *π₃*.
   → **Answer:**
   ```
   Period 1: π^e₁ = 3%
   π₁ = 3 − 0.5(4 − 5) = 3 + 0.5 = 3.5%

   Period 2: π^e₂ = 3.5%
   π₂ = 3.5 − 0.5(4 − 5) = 3.5 + 0.5 = 4.0%

   Period 3: π^e₃ = 4.0%
   π₃ = 4.0 + 0.5 = 4.5%
   ```
   Inflation accelerates: 3% → 3.5% → 4.0% → 4.5%. Each period inflation rises by 0.5 pp.

3. **Application:** The RBA raised the cash rate to 17.5% in 1990, causing unemployment to rise above 10% and anchoring inflation expectations. Using the EAPC, explain the disinflation mechanism and why anchored expectations are now seen as a key advantage for central banks.
   → **Answer:** By pushing *u > u_n*, the 1990 recession moved the economy **right** along the SRPC. With *u − u_n > 0*, the EAPC gives *π < π^e*: actual inflation falls below expected. With adaptive expectations, *π^e* adjusts downward each period. The SRPC shifts *down* until expectations stabilise at the new lower inflation rate. Once inflation expectations are anchored near 2–3%, the short-run trade-off becomes much more favourable: small rises in unemployment produce proportionately larger reductions in inflation. The 2022–23 RBA tightening cycle benefited from this anchoring — even with 13 rate hikes, long-run inflation expectations remained near 2.5–3%, limiting the SRPC upward drift.

## Visual — Expectations-Augmented Phillips Curves and the Vertical Long Run

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1150 430" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 16px Arial, sans-serif; fill: #222; }
    .small { font: 13px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>

  <text x="575" y="28" text-anchor="middle" class="title">Expectations-augmented Phillips curve</text>
  <line x1="90" y1="350" x2="1080" y2="350" class="axis" />
  <line x1="90" y1="350" x2="90" y2="60" class="axis" />
  <text x="585" y="398" text-anchor="middle" class="label">Unemployment rate, u (%)</text>
  <text x="35" y="205" transform="rotate(-90 35 205)" text-anchor="middle" class="label">Inflation, π (%)</text>

  <line x1="550" y1="70" x2="550" y2="350" class="curve" stroke="#111" />
  <text x="563" y="86" class="label">LRPC at u = uₙ = 5%</text>

  <path d="M 230 225 Q 390 245 690 300" class="curve" stroke="#2ca02c" />
  <path d="M 230 170 Q 390 190 690 245" class="curve" stroke="#ff7f0e" />
  <path d="M 230 115 Q 390 135 690 190" class="curve" stroke="#d62728" />
  <text x="710" y="303" class="label">SRPC₁: πᵉ = 2%</text>
  <text x="710" y="248" class="label">SRPC₂: πᵉ = 3%</text>
  <text x="710" y="193" class="label">SRPC₃: πᵉ = 4%</text>

  <circle cx="550" cy="280" r="5" fill="#222" />
  <circle cx="390" cy="195" r="5" fill="#222" />
  <circle cx="390" cy="140" r="5" fill="#222" />
  <circle cx="390" cy="85" r="5" fill="#222" />
  <text x="562" y="286" class="small">Period 0</text>
  <text x="402" y="201" class="small">Period 1</text>
  <text x="402" y="146" class="small">Period 2</text>
  <text x="402" y="91" class="small">Period 3</text>

  <line x1="540" y1="273" x2="405" y2="201" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <line x1="390" y1="188" x2="390" y2="147" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />
  <line x1="390" y1="133" x2="390" y2="92" stroke="#555" stroke-width="2" marker-end="url(#arrow)" />

  <text x="150" y="92" class="small">As expectations adjust upward,</text>
  <text x="150" y="110" class="small">the SRPC shifts up and the economy</text>
  <text x="150" y="128" class="small">moves from Period 0 → 1 → 2 → 3.</text>
  <text x="150" y="150" class="small">Holding u &lt; uₙ causes accelerating inflation.</text>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#555" />
    </marker>
  </defs>
</svg>
</div>

*Figure: With fixed expectations, each short-run Phillips curve is downward sloping. If policymakers keep unemployment below the natural rate, expectations rise, the SRPC shifts upward, and inflation accelerates while the long-run Phillips curve remains vertical at the NAIRU.*

## Further Resources

- 📺 **[Video Tutorial: Expected Inflation and the Phillips Curve](https://www.youtube.com/watch?v=j6YXY3zNmsM)** — Macroeconomics Tutorials (11 min)
- 📺 **[The Expectations Augmented Phillips Curve Ousts the Keynesian Consensus](https://www.youtube.com/watch?v=M9HFtyVlCQw)** — Economics in Context (13 min)
- 📚 **[RBA Explainer: Inflation Target](https://www.rba.gov.au/inflation/inflation-target.html)** — History and rationale for Australia's 2–3% inflation target

