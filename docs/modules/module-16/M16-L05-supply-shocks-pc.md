# Lesson M16.L05: Supply Shocks and the Phillips Curve

**Module:** The Labour Market and Phillips Curve
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Explain how an adverse supply shock causes stagflation by shifting the Phillips curve upward.
**Data as of:** 2024
**Provenance:** [ABS Consumer Price Index, Australia](https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/consumer-price-index-australia) | [Reserve Bank of Australia](https://www.rba.gov.au)

## Explanation

The standard EAPC, *π = π^e − α(u − u_n)*, assumes all inflation comes from demand pressure (the unemployment gap). An **adverse supply shock** — such as an oil price spike, a drought, or a global supply chain disruption — adds a direct cost-push component. The augmented PC is:

> **π = π^e − α(u − u_n) + ε**

where **ε** (epsilon) is the **supply shock term**:
- *ε > 0*: adverse shock (raises inflation for any given unemployment and expectations)
- *ε < 0*: favourable shock (lowers inflation)

**Why adverse shocks cause stagflation:** A positive *ε* raises the price level directly (firms face higher input costs and pass them through). At any given unemployment rate and inflation expectations, inflation jumps upward — the SRPC shifts up by *ε*. If the central bank does not accommodate (i.e., does not cut rates), aggregate demand falls as real incomes decline, pushing unemployment higher. The result is **stagflation**: *simultaneously high inflation and high unemployment* — the nightmare scenario for policymakers.

**Policy trilemma (three options for the central bank):**

| Option | Action | Result |
|---|---|---|
| **Accommodate** | ↑ M to keep Y constant | Higher π, u stays at u_n; π^e rises permanently |
| **Fight (tighten)** | ↑ r to reduce π to target | Higher u (recession), π returns to target |
| **Supply-side** | Structural reforms to reduce ε | Lower ε, curve shifts back; avoids recession |

**Historical episodes:**

**1973–74 oil shock (OPEC I):** Oil prices quadrupled. US, UK, and Australia experienced simultaneous surges in inflation and unemployment — stagflation. Australia's CPI jumped from ~5% to over 15% by 1975. The initial policy response was accommodating, embedding higher inflation expectations.

**Australia 2021–23:** COVID supply chain disruptions, the Russian invasion of Ukraine (February 2022, raising energy and food prices), and domestic demand stimulus combined to produce the largest inflationary episode in three decades. Australian CPI reached **7.8% in Q4 2022** (ABS). The RBA chose the **fight path**: 13 consecutive rate hikes (November 2020: 0.10% → November 2023: 4.35%), deliberately raising unemployment to bring inflation back toward target.

**Notation:** *π* = inflation; *π^e* = expected inflation; *u* = unemployment; *u_n* = NAIRU; *α* = PC slope; *ε* = supply shock term; *r* = cash rate.

## Worked Example

**Setup:**

- EAPC: *π = π^e − 0.5(u − 5) + ε*  [α = 0.5, u_n = 5%]
- Initial stable equilibrium: *π^e = 3%*, *u = 5%*, *ε = 0*

**Step 1 — Pre-shock equilibrium:**

```
π₀ = 3 − 0.5(5 − 5) + 0 = 3%
```

Economy is at (*u = 5%*, *π = 3%*): stable, at NAIRU.

**Step 2 — Adverse supply shock: ε = 2% (e.g., energy price spike):**

At unchanged *u = 5%* and *π^e = 3%*:

```
π₁ = 3 − 0.5(5 − 5) + 2 = 5%
```

Inflation jumps to 5%. But unemployment has not yet changed — **stagflation begins** if the shock also reduces aggregate supply (firms cut output due to higher input costs), which pushes *u* up too.

Suppose the shock also raises *u* to 6%:

```
π₁ = 3 − 0.5(6 − 5) + 2 = 3 − 0.5 + 2 = 4.5%
```

**Result after shock: u = 6%, π = 4.5%** (both above their target/natural values) — stagflation.

**Step 3 — RBA chooses to fight inflation (tighten monetary policy):**

Target: *π = 3%*. Assumptions: *π^e = 3%* (well-anchored), *ε = 2%* (shock persists).

Solve for required *u*:

```
3 = 3 − 0.5(u − 5) + 2
0 = −0.5(u − 5) + 2
0.5(u − 5) = 2
u − 5 = 4
u = 9%
```

To return inflation to 3% while the supply shock persists, unemployment must rise to **9%**. This is the **sacrifice ratio** — the output/employment cost of fighting inflation.

**Step 4 — Accommodation comparison:**

If instead the RBA accommodates (expands *M* to hold *u = 5%*):

```
π = 3 − 0.5(5 − 5) + 2 = 5%
```

Inflation stabilises at 5%, but: adaptive expectations → *π^e* rises to 5% next period → next period's PC shifts up → inflation rises again if *u* is held at 5% or falls below it.

**Step 5 — Australia 2022–23 calibration:**

Australia's inflation peaked at 7.8% in Q4 2022 vs. the 2–3% target. With *u_n* ≈ 4.25% and *u* ≈ 3.5% (below NAIRU) in early 2023, the simultaneous demand overheating (negative unemployment gap) **and** supply shocks (ε > 0) stacked up:

```
π ≈ π^e + 0.5(4.25 − 3.5) + ε_total ≈ 3 + 0.375 + 4.4 ≈ 7.8%
```

The supply shock component (energy, food, supply chains) accounts for the bulk of the excess inflation — consistent with RBA analysis distinguishing demand-driven from supply-driven inflation.

## Common Misconception

**Misconception:** A supply shock that raises both inflation and unemployment demonstrates that the Phillips curve has no trade-off.

**Correction:** A supply shock does not destroy the Phillips curve trade-off — it **shifts** the curve upward (by ε). Along the new, higher SRPC, the standard trade-off between inflation and unemployment still exists: for a given *ε*, lower unemployment still means higher inflation. The stagflation puzzle is not that the trade-off disappeared, but that it now occurred at **worse combinations** — higher inflation at every unemployment level. The response requires choosing *which point on the new SRPC* to accept, or using supply-side policy to shift the curve back down.

## Practice Prompts

1. **Conceptual:** In the (u, π) diagram, show what an adverse supply shock of size ε does to the short-run Phillips curve and the long-run Phillips curve.
   → **Answer:** The **short-run PC shifts upward** by ε (every point on the curve now has inflation ε higher for the same *u*). The **long-run PC remains vertical** at *u = u_n* — in the long run, prices and wages fully adjust, and the shock is eventually absorbed. However, if the shock is **permanent** (e.g., a permanently higher oil price), the LRPC may shift as the natural rate of unemployment changes (e.g., if higher energy costs reduce potential output permanently). Temporary shocks shift SRPC temporarily; permanent shocks may shift both.

2. **Numerical:** Using *π = π^e − 0.5(u − 5) + ε* with *π^e = 2%* and an adverse shock *ε = 3%*, calculate the inflation rate at *u = 5%* and the unemployment rate required to keep inflation at 2%.
   → **Answer:**
   ```
   (a) At u = 5%:
       π = 2 − 0.5(5 − 5) + 3 = 2 + 3 = 5%

   (b) Set π = 2%:
       2 = 2 − 0.5(u − 5) + 3
       0 = −0.5(u − 5) + 3
       0.5(u − 5) = 3
       u − 5 = 6
       u = 11%
   ```
   Keeping inflation at 2% during a shock of ε = 3% requires unemployment to rise to 11% — an enormous sacrifice.

3. **Application:** Between 2021 and 2023, Australia's CPI peaked at 7.8% (Q4 2022). The RBA hiked rates 13 times (0.10% → 4.35%). Decompose this inflation episode into demand-side and supply-side components, and evaluate the RBA's choice of the "fight" path.
   → **Answer:** Demand side: unemployment fell to 3.5% in early 2023, below the NAIRU of ~4.0–4.25%, creating demand-pull inflation (negative unemployment gap). Supply side: global energy prices spiked following the Ukraine war (2022), global food prices rose, and supply chains remained disrupted post-COVID. The RBA's "fight" path accepted higher unemployment (rising to ~4.1% by end-2023) to bring inflation back toward target. The anchored expectations (π^e remained near 2.5–3%) reduced the sacrifice ratio — compared with 1990, far fewer rate hikes were needed relative to the inflation overshoot. By Q2 2024, trimmed-mean inflation had fallen to ~3.9%, still above target but trending down.

## Further Resources

- 📺 **[How Do Supply Shocks Trigger Stagflation?](https://www.youtube.com/watch?v=spnLWO6eswE)** — Learn About Economics (10 min)
- 📺 **[Ch15-Supply Shocks and Phillips Curve](https://www.youtube.com/watch?v=n-ByHIPVT10)** — Macroeconomics Lecture Series (14 min)
- 📚 **[ABS Consumer Price Index – December Quarter 2022](https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/consumer-price-index-australia/latest-release)** — Official data for CPI peak of 7.8%
