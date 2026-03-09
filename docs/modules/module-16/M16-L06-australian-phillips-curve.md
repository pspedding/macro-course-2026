# Lesson M16.L06: The Australian Phillips Curve: Empirical Evidence

**Module:** The Labour Market and Phillips Curve
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Assess the empirical evidence for a flat Phillips curve in Australia using post-2012 labour market data.
**Data as of:** 2024
**Provenance:** [ABS Labour Force, Australia](https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia) | [Reserve Bank of Australia](https://www.rba.gov.au)

## Explanation

From approximately **2012 to 2019**, Australia exhibited a puzzling labour market pattern that challenged the standard Phillips curve: unemployment fell gradually from ~5.5% to ~5.0%, yet **wage inflation** (as measured by the ABS Wage Price Index, WPI) remained stubbornly near **2%** — far below what the EAPC would predict given a NAIRU of ~4.5–5.0%.

This **flat Phillips curve episode** has several candidate explanations:

1. **Globalisation and import competition:** Increased competition from low-wage economies suppressed price and wage inflation globally, shifting the PC downward.

2. **Casualisation and underemployment:** Even as headline unemployment fell, the **underemployment rate** remained elevated at **8–9%** (part-time workers who wanted more hours). The ABS labour underutilisation rate (unemployment + underemployment) was 13–15%, better capturing effective slack in the labour market than headline unemployment alone.

3. **Anchored inflation expectations:** Following the 1990 disinflation, RBA inflation targeting kept *π^e* firmly near 2.5%. Low *π^e* means the PC is centred at low inflation regardless of *u*.

4. **Weak enterprise bargaining:** Enterprise bargaining agreement (EBA) coverage fell over this period, and many EBAs were settled at minimal increases. Decentralised wage-setting reduced the pass-through from tight labour markets to wages.

**Post-COVID structural shift (2020–2023):**

The dynamic changed sharply after 2020. Unemployment fell from ~7.5% (mid-2020 peak) to a trough of **3.5% (January 2023, ABS)** — well below the NAIRU of ~4.0–4.25%. WPI growth accelerated from a trough of ~**1.9% (2020)** to **4.2% (2023, ABS)**. The Phillips curve appeared to **steepen**: a similar proportional change in unemployment now produced much larger wage responses.

**Slope comparison:**
- 2012–2019: Δu ≈ −0.5 pp, ΔWage inflation ≈ +0.2 pp → implied α ≈ 0.4
- 2020–2023: Δu ≈ −4.0 pp (7.5% → 3.5%), ΔWage inflation ≈ +2.3 pp (1.9% → 4.2%) → implied α ≈ 0.58

The curve steepened significantly. This is consistent with a tighter labour market finally exhausting slack (casual pool, underemployed workers) and activating stronger wage dynamics.

**Notation:** *u* = unemployment rate; *π_w* = WPI growth (wage inflation); *u_n* = NAIRU; *α* = PC slope; *z* = underemployment rate; *π^e* = inflation expectations.

## Worked Example

**Setup:** Estimate the implied Phillips curve slope using two data points from the ABS.

**Data Point 1 (2019 average):**
- Unemployment: *u₁* = 5.2%
- WPI growth: *π_{w1}* = 2.3%

**Data Point 2 (2023 peak labour tightness):**
- Unemployment: *u₂* = 3.5%
- WPI growth: *π_{w2}* = 4.2%

**Step 1 — Compute the implied slope (α) of the PC:**

Using the Phillips curve: *π_w = π̄ − α(u − u_n)*

The change in wage inflation per change in unemployment:

```
Δπ_w = π_{w2} − π_{w1} = 4.2 − 2.3 = +1.9 pp
Δu = u₂ − u₁ = 3.5 − 5.2 = −1.7 pp
```

Implied slope:

```
α = −Δπ_w / Δu = −(1.9) / (−1.7) ≈ 1.12
```

**Step 2 — Why the naive slope calculation misleads:**

Using 2014–2019 data: unemployment fell from 5.2% to 5.0% **and** wages also fell from 2.5% to 2.3% WPI. Both moved in the same direction — this reflects a *demand-side* story (weak aggregate demand suppressed both employment and wages simultaneously). Calculating a two-point slope here gives α ≈ 1.0, which looks steep but is spurious: it's measuring a demand shock confound, not the structural PC relationship.

The correct way to see the "flatness" is to note that unemployment was **above** the estimated NAIRU of ~4.5–5.0% throughout 2014–2019. Standard EAPC theory predicts wages should have been rising (u < u_n → positive wage pressure). Instead, wages *fell* — that's the puzzle.

**Step 3 — The puzzle stated using EAPC:**

**Step 4 — The puzzle stated algebraically:**

With EAPC: *π_w = π^e − α(u − u_n)*, assume *π^e = 2.5%*, *u_n = 4.5%*, *α = 0.5*:

```
Predicted at u = 5.0%: π_w = 2.5 − 0.5(5.0 − 4.5) = 2.5 − 0.25 = 2.25%
```

Actual WPI ≈ 2.3% — close to the prediction. So the curve was not entirely flat; it simply responded weakly to a small unemployment gap. The "puzzle" was that unemployment *should* have been below the NAIRU, yet wages barely moved — suggesting either the NAIRU was higher than 4.5% at the time, or hidden slack (underemployment) held wages down.

**Post-COVID (2023):** With *u = 3.5%* and *u_n* revised to 4.25%:

```
Predicted: π_w = 2.5 − 0.5(3.5 − 4.25) = 2.5 + 0.375 = 2.875%
Actual: 4.2%
```

The gap (actual 4.2% vs predicted 2.875%) reflects the supply shock component and the fact that hidden slack was exhausted — the curve steepened structurally.

## Common Misconception

**Misconception:** The post-2012 flat Phillips curve means the relationship between unemployment and wages no longer exists in Australia.

**Correction:** The flat PC of 2012–2019 reflected *high effective labour market slack* (underemployment ~8–9%) that the headline unemployment rate masked. Once that slack was absorbed — as occurred from 2021 onward — the standard unemployment-wage relationship reasserted itself. The post-COVID experience (unemployment falling to 3.5%, wages rising to 4.2%) demonstrates the PC was **latent, not dead**. The relationship steepened rather than disappeared, consistent with theoretical predictions when effective unemployment falls below the NAIRU.

## Practice Prompts

1. **Conceptual:** List three structural features of the Australian labour market that may have contributed to the flat Phillips curve observed between 2012 and 2019.
   → **Answer:** (i) **High underemployment** (~8–9%): part-time workers wanting more hours provided a large pool of effective labour supply without showing up in headline unemployment. (ii) **Globalisation**: import price competition suppressed domestic inflationary pressure even when unemployment fell. (iii) **Weakening enterprise bargaining**: declining EBA coverage and low settlement outcomes reduced wage-growth transmission from tight labour conditions to actual pay rises. Anchored inflation expectations (*π^e* ≈ 2.5%) also constrained the baseline level of the curve.

2. **Numerical:** Using the EAPC *π_w = 2.5 − α(u − 4.25)*, and the following two observations, estimate the implied *α* for each sub-period:
   - Period A: u = 5.2%, π_w = 2.3%
   - Period B: u = 3.5%, π_w = 4.2%

   → **Answer:**
   ```
   Period A: 2.3 = 2.5 − α(5.2 − 4.25)
   2.3 = 2.5 − 0.95α
   0.2 = 0.95α
   α_A ≈ 0.21  (flat PC)

   Period B: 4.2 = 2.5 − α(3.5 − 4.25)
   4.2 = 2.5 + 0.75α
   1.7 = 0.75α
   α_B ≈ 2.27  (steep PC)
   ```
   The implied slope more than **ten-fold** between the pre-COVID and post-COVID periods — a dramatic steepening of the Australian Phillips curve.

3. **Application:** In 2023, Australia's unemployment rate sat at approximately 3.7–4.0%, above its January 2023 trough of 3.5%, while WPI growth was 4.2%. The RBA's NAIRU estimate was 4.0–4.25%. Using the EAPC, assess whether wage inflation was consistent with the labour market being at or above the NAIRU.
   → **Answer:** With *u ≈ 3.9%* (mid-2023) and *u_n ≈ 4.1%* (midpoint of RBA range):
   ```
   Unemployment gap: u − u_n = 3.9 − 4.1 = −0.2 pp (still below NAIRU, but barely)
   ```
   With *α ≈ 0.5* and *π^e ≈ 3%* (RBA near-term survey expectations):
   ```
   Predicted π_w = 3 − 0.5(−0.2) = 3 + 0.1 = 3.1%
   ```
   Actual WPI = 4.2% exceeds this prediction, suggesting: (i) the supply shock term ε remains positive (cost of living adjustments feeding into wage demands); (ii) the PC slope α may be higher than 0.5 in the current regime; or (iii) inflation expectations were drifting above 3%. This residual gap is consistent with the RBA maintaining a restrictive stance into 2024.

## Further Resources

- 📺 **[Economics of the NAIRU – Extended Phillips Curve](https://www.youtube.com/watch?v=f7a3NSzERRw)** — Economics Explained (14 min)
- 📺 **[The Phillips Curve Explained: Why Inflation and Unemployment Don't Always Trade Off](https://www.youtube.com/watch?v=cqsh5SgGxWc)** — Michael Raviv Economics Lectures (15 min)
- 📚 **[ABS Wage Price Index – September Quarter 2023](https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/wage-price-index-australia)** — Official WPI data series for Australia
