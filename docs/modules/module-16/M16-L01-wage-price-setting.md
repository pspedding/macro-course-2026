# Lesson M16.L01: Wage Setting and Price Setting Equations

**Module:** The Labour Market and Phillips Curve
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the equilibrium real wage from the WS-PS labour market framework.
**Data as of:** 2024
**Provenance:** [Reserve Bank of Australia](https://www.rba.gov.au) | [ABS Labour Force, Australia](https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia)

## Explanation

!!! info "Key Diagram"
    ![Figure 6: The Phillips Curve. Short-run curves shift with inflation expectations; the long-run curve is vertical at the NAIRU (~4.25% for Australia). The 2023 Australian data point shows inflation above target with unemployment below NAIRU.](../../assets/diagrams/06-phillips-curve.png)  
    *Figure 6: The Phillips Curve. Short-run curves shift with inflation expectations; the long-run curve is vertical at the NAIRU (~4.25% for Australia). The 2023 Australian data point shows inflation above target with unemployment below NAIRU.*


The labour market in Blanchard's intermediate macroeconomics framework is characterised by **imperfect competition** on both the goods and labour sides. Equilibrium is determined by two equations: the **wage-setting (WS)** relationship and the **price-setting (PS)** relationship.

**Wage-Setting (WS):** Workers and firms bargain over nominal wages *W*, taking the expected price level *P^e* as given. Higher expected prices require higher nominal wages to maintain real purchasing power. The real wage workers can negotiate depends on:

- *u* = unemployment rate (higher unemployment → weaker bargaining power → lower *W*)
- *z* = a catch-all for labour market institutions (unemployment benefits, union coverage, minimum wages — higher *z* → higher *W*)
- *α* = sensitivity of wages to unemployment

The WS equation (in real terms, when *P^e = P*):

> **W/P = 1 − αu + z**

**Price-Setting (PS):** Firms set prices as a markup *μ* over unit labour costs. If the nominal wage is *W* and labour is the only input (unit cost = *W*):

> **P = (1 + μ)W → W/P = 1/(1 + μ)**

This is the PS real wage — it does not depend on unemployment. A higher markup *μ* (more market power) → lower real wage firms can afford to pay.

**Equilibrium:** Where WS = PS. Setting WS = PS gives the **natural (equilibrium) unemployment rate** and the equilibrium real wage — covered in M16.L02.

**Australian context:** The **Fair Work Commission (FWC)** sets the National Minimum Wage annually, directly shifting the *z* parameter. Enterprise Bargaining Agreements (EBAs) cover approximately **35%** of the workforce, another institutional *z* shifter. In 2023, the FWC awarded a 5.75% increase in the minimum wage (effective 1 July 2023), one of the largest in recent history — shifting the WS curve upward.

**Notation:** *W* = nominal wage; *P* = actual price level; *P^e* = expected price level; *u* = unemployment rate; *z* = labour market institutions parameter; *α* = wage sensitivity to unemployment; *μ* = price markup; *W/P* = real wage.

## Worked Example

**Setup:**

- WS (real): *W/P = 1 − 5u + z*, with *z = 0.05* and *α = 5*
- PS (real): *W/P = 1/(1 + μ)*, with *μ = 0.25*

**Step 1 — Compute PS real wage:**

```
W/P_PS = 1/(1 + 0.25) = 1/1.25 = 0.80
```

The PS real wage is constant at **0.80** regardless of unemployment.

**Step 2 — Write WS real wage:**

```
W/P_WS = 1 − 5u + 0.05 = 1.05 − 5u
```

**Step 3 — Find equilibrium unemployment (set WS = PS):**

```
1.05 − 5u = 0.80
5u = 0.25
u* = 0.05 = 5%
```

**Step 4 — Confirm equilibrium real wage:**

```
W/P* = 1.05 − 5(0.05) = 1.05 − 0.25 = 0.80 ✓
```

Equilibrium real wage = **0.80**, equilibrium unemployment = **5%**.

**Step 5 — Policy shift: FWC raises minimum wage (↑z to 0.15):**

```
W/P_WS = 1 − 5u + 0.15 = 1.15 − 5u

Set WS = PS: 1.15 − 5u = 0.80
5u = 0.35
New u* = 0.07 = 7%
```

A rise in *z* (better minimum wages/benefits) shifts the WS curve **up**, raising equilibrium unemployment from 5% to 7%. The WS-PS model predicts a trade-off: better worker institutions raise wages but also increase structural unemployment.

## Common Misconception

**Misconception:** The real wage that workers receive is determined only by what workers demand (the WS curve).

**Correction:** The real wage is determined by **both** the WS and PS equations simultaneously. Firms set prices based on their markup over wages — the PS curve acts as a constraint on how high real wages can be. Workers may successfully negotiate higher nominal wages, but if firms respond by raising prices proportionally (maintaining their markup *μ*), the real wage is unchanged: *W/P = 1/(1+μ)*. Only if the markup falls or labour productivity rises can real wages sustainably increase above the PS line. This is why wage bargaining in isolation cannot guarantee real wage gains without productivity growth.

## Practice Prompts

1. **Conceptual:** Explain why the PS real wage is independent of unemployment while the WS real wage is decreasing in unemployment.
   → **Answer:** Firms set prices as a fixed markup over wages: *P = (1+μ)W*. Rearranging, *W/P = 1/(1+μ)* — a constant that depends only on market power (μ), not on labour market conditions. Workers' bargaining power, however, depends on how easy it is to find alternative work. Higher unemployment weakens their threat point, so WS is decreasing in *u*.

2. **Numerical:** Using the model above (α = 5, z = 0.05, μ = 0.25), suppose firms face increased international competition that lowers their markup to μ = 0.10. Calculate the new equilibrium real wage and unemployment rate.
   → **Answer:**
   ```
   New PS: W/P_PS = 1/(1 + 0.10) = 1/1.10 ≈ 0.909

   WS: W/P_WS = 1.05 − 5u

   Set WS = PS:
   1.05 − 5u = 0.909
   5u = 0.141
   u* = 0.0282 ≈ 2.8%

   W/P* = 0.909
   ```
   Lower markup → PS curve shifts **up** → equilibrium unemployment falls from 5% to 2.8% and real wages rise from 0.80 to 0.91. Greater product market competition benefits workers.

3. **Application:** Fair Work Commission decisions on the minimum wage affect the *z* parameter in the WS equation. Using the WS-PS diagram, explain whether a 5.75% minimum wage increase (as granted in 2023) necessarily raises unemployment.
   → **Answer:** A higher minimum wage raises *z*, shifting the WS curve upward. In the WS-PS framework, this **increases equilibrium unemployment** (*u_n* rises). However, the actual effect depends on: (i) whether the minimum wage was binding — if most workers earn above the minimum, the WS shift is small; (ii) whether the markup *μ* absorbs the cost rather than prices rising; and (iii) demand-side effects (higher low-wage incomes may stimulate consumption). Empirical evidence from Australia and other countries suggests minimum wage rises have smaller disemployment effects than the model predicts, possibly because labour markets are monopsonistic rather than competitive.

## Further Resources

- 📺 **[Labor Market: Wage and Price Setting](https://www.youtube.com/watch?v=yHDMdxvNFpM)** — IMF/Blanchard Macroeconomics Tutorial (9 min)
- 📺 **[Labour Market: Wage Setting Relationship](https://www.youtube.com/watch?v=WgfDB21mJP4)** — Macroeconomics Tutorials (7 min)
- 📚 **[Fair Work Commission – Minimum Wage Decision 2023](https://www.fwc.gov.au/documents/sites/wagereview2023/decisions/pr748615.pdf)** — Full text of the 5.75% minimum wage determination
