# Lesson M16.L02: The Natural Rate of Unemployment (NAIRU)

**Module:** The Labour Market and Phillips Curve
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the NAIRU from the WS-PS equilibrium condition.
**Data as of:** 2024
**Provenance:** [Reserve Bank of Australia](https://www.rba.gov.au) | [ABS Labour Force, Australia](https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia)

## Explanation

The **Natural Rate of Unemployment** — or **NAIRU** (Non-Accelerating Inflation Rate of Unemployment) — is the unemployment rate at which the labour market is in a stable equilibrium: actual prices equal expected prices (*P = P^e*), so there is no tendency for inflation to accelerate or decelerate.

**Formal derivation:** Starting from:

- WS (real, with *P = P^e*): *W/P = 1 − αu + z*
- PS (real): *W/P = 1/(1 + μ)*

At equilibrium, set WS = PS:

```
1 − αu_n + z = 1/(1 + μ)
```

Solve for *u_n*:

```
αu_n = 1 + z − 1/(1 + μ)
u_n = [1 + z − 1/(1 + μ)] / α
```

**Comparative statics:**

| Parameter change | Effect on u_n | Intuition |
|---|---|---|
| ↑ z (higher benefits, stronger unions) | ↑ u_n | WS shifts up; equilibrium unemployment rises |
| ↑ μ (higher markup, less competition) | ↑ u_n | PS shifts down (lower real wages); WS-PS gap widens |
| ↑ α (steeper WS) | ↓ u_n | Wages are more sensitive to unemployment; small ↑u_n restores equilibrium |

**Australian NAIRU estimates (RBA):**

The RBA regularly publishes NAIRU estimates. Over recent decades:

- **Pre-2012:** NAIRU ≈ **5.0%** — reflecting higher structural unemployment
- **Mid-2010s:** NAIRU ≈ **4.5%** — improved job matching, reduced union density
- **Post-COVID (2023):** NAIRU ≈ **4.0–4.25%** — tighter labour markets, faster job matching

The post-COVID downward revision reflects reduced long-term unemployment, better skills matching, and strong aggregate demand. The RBA's actual unemployment rate reached **3.5% in January 2023** (ABS) — below the NAIRU — consistent with the subsequent surge in wage inflation (WPI reached 4.2% in 2023).

**Key distinction:** The NAIRU is *not* zero unemployment. It reflects frictional unemployment (workers between jobs) and structural unemployment (skill/geographic mismatches). Attempts to push unemployment below the NAIRU cause accelerating inflation — the central lesson of the Phillips curve literature.

**Notation:** *u_n* = NAIRU; *z* = institutions parameter; *μ* = markup; *α* = wage-unemployment sensitivity; *W/P* = real wage.

## Worked Example

**Setup:**

- WS: *W/P = 1 − 5u + z*
- PS: *W/P = 1/(1 + μ)*
- Baseline: *z = 0.05*, *μ = 0.25*, *α = 5*

**Step 1 — Derive NAIRU formula:**

Set WS = PS:

```
1 − 5u_n + 0.05 = 1/1.25
1.05 − 5u_n = 0.80
5u_n = 0.25
u_n = 0.05 = 5%
```

Equilibrium real wage: *W/P* = 0.80.

**Step 2 — Effect of higher unemployment benefits (↑z = 0.15):**

```
1 − 5u_n + 0.15 = 0.80
1.15 − 5u_n = 0.80
5u_n = 0.35
u_n = 0.07 = 7%
```

More generous benefits raise workers' reservation wage (their outside option), shifting WS up. NAIRU rises from 5% to 7%.

**Step 3 — Effect of more competitive product markets (↓μ = 0.10):**

Return to baseline *z = 0.05*:

```
PS: W/P = 1/1.10 ≈ 0.909

1.05 − 5u_n = 0.909
5u_n = 0.141
u_n ≈ 2.8%
```

Lower markup raises the PS real wage (firms can afford to pay more relative to prices), shifting PS up. WS and PS intersect at lower unemployment.

**Step 4 — Post-COVID Australian scenario (lower u_n):**

Suppose improved job-matching technology (digital labour platforms) reduces structural unemployment equivalent to a reduction in *z* from 0.05 to 0.02:

```
1 − 5u_n + 0.02 = 0.80
1.02 − 5u_n = 0.80
5u_n = 0.22
u_n = 0.044 = 4.4%
```

The RBA's revised NAIRU of ~4.0–4.25% is consistent with improvements in job matching efficiency and reduced long-term unemployment following pandemic-era labour market tightening.

## Common Misconception

**Misconception:** The NAIRU is fixed and does not change over time.

**Correction:** The NAIRU is **time-varying** and depends on structural features of the labour market. Changes in unemployment benefit generosity, union density, minimum wage legislation, labour market matching efficiency (e.g., digital job platforms), and product market competition all shift the NAIRU. In Australia, the RBA explicitly revised its NAIRU estimate downward from ~5% to ~4.0–4.25% after the post-COVID labour market tightening demonstrated that unemployment could fall much further than previously thought without causing runaway inflation. Treating the NAIRU as fixed can lead to premature monetary tightening.

## Practice Prompts

1. **Conceptual:** In the WS-PS diagram, explain geometrically what the NAIRU represents and what happens if actual unemployment falls below it.
   → **Answer:** In the (*u*, *W/P*) diagram, the **WS curve** slopes downward (higher *u* → lower *W/P*) and the **PS curve** is horizontal (independent of *u*). The NAIRU *u_n* is the unemployment rate at the intersection. If *u < u_n*, the WS curve gives a real wage **above** the PS curve: workers' wage demands exceed what firms can pay given their markup. Firms raise prices (*P* rises above *P^e*), eroding real wages temporarily until inflation expectations adjust upward — triggering the expectation-price spiral described in M16.L04.

2. **Numerical:** Using α = 5, z = 0.08, μ = 0.20, derive the NAIRU. Then calculate the new NAIRU if the government cuts unemployment benefits so that z falls to 0.03.
   → **Answer:**
   ```
   PS: W/P = 1/(1.20) = 0.833

   Baseline (z = 0.08):
   WS: 1.08 − 5u_n = 0.833
   5u_n = 0.247 → u_n = 0.0494 ≈ 4.9%

   After cuts (z = 0.03):
   WS: 1.03 − 5u_n = 0.833
   5u_n = 0.197 → u_n = 0.0394 ≈ 3.9%
   ```
   Reducing unemployment benefits lowers the NAIRU from ~4.9% to ~3.9%, consistent with the RBA's post-2020 downward revision of its NAIRU estimate.

3. **Application:** Between 2012 and 2019, Australia's unemployment rate fluctuated between 5% and 5.5% while wage growth remained stuck near 2%. Using the NAIRU framework, what does this imply about the relationship between actual unemployment and the NAIRU during this period?
   → **Answer:** Stable, low wage inflation while unemployment was 5–5.5% implies that actual unemployment was **at or above the NAIRU**. Workers lacked bargaining power to push wages above the PS real wage. This is consistent with an estimated NAIRU of ~4.5–5% for that period. The puzzle was that unemployment did not fall below the NAIRU for sustained periods — structural factors (underemployment, casualisation) may have suppressed effective labour market tightness even when headline unemployment appeared moderate.

## Further Resources

- 📺 **[Economics of the NAIRU – Extended Phillips Curve](https://www.youtube.com/watch?v=f7a3NSzERRw)** — Economics Explained (14 min)
- 📺 **[The NAIRU 1: The Non-Accelerating Inflation Rate of Unemployment](https://www.youtube.com/watch?v=72HhG_3F6sw)** — Macroeconomics Tutorials (10 min)
- 📚 **[RBA Research Discussion Paper – Estimating the NAIRU](https://www.rba.gov.au/publications/rdp/)** — RBA empirical estimates for Australia
