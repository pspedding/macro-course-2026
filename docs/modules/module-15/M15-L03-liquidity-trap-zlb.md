# Lesson M15.L03: The Liquidity Trap and the Zero Lower Bound

**Module:** The IS-LM Model Part II
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Explain why monetary policy becomes ineffective when the economy is in a liquidity trap.
**Data as of:** 2024
**Provenance:** [Reserve Bank of Australia](https://www.rba.gov.au) | [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

## Explanation

A **liquidity trap** occurs when the nominal interest rate falls to its **zero lower bound (ZLB)** — the point at which bonds and money become near-perfect substitutes. At *r = 0* (or very close to it), individuals are indifferent between holding money and holding bonds: bonds offer no return above zero, so there is no opportunity cost to holding money. Money demand becomes **perfectly interest-elastic**: any increase in the money supply is absorbed without affecting the interest rate.

In the IS-LM diagram, this condition manifests as a **flat (horizontal) LM curve** at *r = 0*. When the central bank expands the money supply — shifting the LM curve rightward — the economy simply moves along the flat portion: *r* cannot fall below zero, and *Y* remains unchanged. **Monetary policy is ineffective.**

Keynes described this as "pushing on a string" — the central bank can create money, but it cannot force spending.

**Fiscal policy**, by contrast, regains its **full Keynesian cross power** in the liquidity trap. An increase in *G* shifts IS rightward, and because the LM is horizontal, the interest rate does not rise. There is zero crowding out.

**Unconventional monetary tools** emerged because of ZLB constraints:
- **Quantitative easing (QE):** Large-scale asset purchases to lower long-term yields.
- **Forward guidance:** Commitment to keep rates low into the future to shift expectations.
- **Yield Curve Control (YCC):** Targeting a specific bond yield at a specified maturity.

**Japan (1990s–2010s):** The archetypal liquidity trap — the Bank of Japan held rates near zero for over two decades with limited effect on output.

**Australia (2020–21):** The RBA lowered the cash rate to **0.10%** (November 2020), implemented YCC targeting 3-year government bond yields at 0.10%, and introduced the **Term Funding Facility (TFF)** offering 3-year loans to banks at 0.10%. These unconventional tools aimed to ease financial conditions beyond what conventional rate cuts could achieve.

**Notation:** *r* = interest rate; *M* = money supply; *P* = price level; *M/P* = real money balances; *Y* = real output; *r_ZLB* = zero lower bound interest rate.

## Worked Example

**Setup — Liquidity trap scenario:**

- IS curve: *Y = 1400 − 200r* (r in %)
- LM at ZLB: *r = 0%* (horizontal — money demand is infinitely elastic)
- Full-employment output: *Y* = 1200

**Step 1 — Equilibrium in the liquidity trap:**

At *r = 0*:
```
Y_IS = 1400 − 200(0) = 1400
```

But suppose the IS curve is depressed (e.g., a financial crisis reduces autonomous spending):

- Depressed IS: *Y = 1000 − 200r*
- At *r = 0*: *Y = 1000*

Equilibrium output = **1000**, which is below full employment of 1200. Recessionary gap = **200**.

**Step 2 — Attempt monetary expansion (LM shifts right):**

The RBA expands *M/P*. The normal LM would shift right, but since *r* is already at 0% and cannot fall further, the new LM is still horizontal at *r = 0%*.

```
New IS = LM: Y_IS = 1000 − 200(0) = 1000
```

**Result: ΔY = 0. Monetary policy is ineffective.**

**Step 3 — Fiscal expansion (IS shifts right):**

Government raises spending by ΔG = 100 with multiplier k = 2. IS shifts right by 200.

New IS: *Y = 1200 − 200r*

At *r = 0*:
```
Y = 1200 − 200(0) = 1200
```

**Result: ΔY = +200. Full Keynesian multiplier effect — zero crowding out because r stays at 0%.**

**Step 4 — Summary table:**

| Policy | Δ*r* | Δ*Y* | Effective? |
|---|---|---|---|
| Monetary expansion (M↑) | 0 | 0 | ✗ No |
| Fiscal expansion (G↑) | 0 | +200 | ✓ Yes |

## Common Misconception

**Misconception:** The ZLB means the interest rate cannot go negative; once it hits zero, the central bank can do nothing.

**Correction:** The ZLB is a lower bound on **nominal** rates under conventional policy, not an absolute barrier. Several central banks (ECB, Bank of Japan, Swiss National Bank) have implemented **negative interest rates** (e.g., −0.5% to −0.75%) by charging banks for holding excess reserves. Additionally, unconventional tools such as QE, YCC, and forward guidance can still ease financial conditions even at the ZLB. The RBA avoided negative rates but used YCC and TFF as substitutes. The effectiveness of these tools remains debated.

## Practice Prompts

1. **Conceptual:** What feature of the IS-LM diagram characterises the liquidity trap, and why does a rightward LM shift fail to raise output in this situation?
   → **Answer:** In a liquidity trap, the **LM curve is horizontal** at *r = 0* (or the ZLB). Money demand is perfectly interest-elastic — people hold any additional money supplied without requiring a lower interest rate. A rightward shift of the LM curve moves along this flat segment: *r* remains at zero and there is no stimulus to investment or output. The transmission channel from money → lower *r* → higher *I* → higher *Y* is broken at the first step.

2. **Numerical:** Suppose the economy is at the ZLB with IS: *Y = 1000 − 200r* and *r = 0%*. The government increases spending by ΔG = 50 with a multiplier of k = 2. (a) By how much does IS shift? (b) What is the new equilibrium Y?
   → **Answer:**
   ```
   (a) IS shifts right by k × ΔG = 2 × 50 = 100.
       New IS: Y = 1100 − 200r

   (b) At r = 0% (ZLB):
       Y = 1100 − 200(0) = 1100

   ΔY = +100 (full multiplier, no crowding out)
   ```

3. **Application:** Japan experienced near-zero interest rates from the late 1990s onward yet struggled to escape deflation and stagnation. What does this suggest about the limits of the liquidity trap framework, and what additional tools did Japan eventually deploy?
   → **Answer:** Japan's experience highlighted that even **fiscal policy** at the ZLB faces limits: high government debt levels created concerns about fiscal sustainability, constraining further expansion. Structurally weak demand (ageing population, deflation expectations) kept the IS curve depressed despite fiscal stimulus. Japan eventually deployed **Abenomics** (2013): a "three arrows" strategy combining (i) massive QE by the Bank of Japan, (ii) fiscal stimulus, and (iii) structural reforms. YCC was introduced in 2016. The episode illustrated that escaping a liquidity trap requires a coordinated, multi-instrument approach — no single tool suffices.

## Further Resources

- 📺 **[Intro Econ: The Liquidity Trap and Quantitative Easing](https://www.youtube.com/watch?v=5a6N3aUQGSA)** — Marginal Revolution University (10 min)
- 📺 **[Liquidity Trap – Zero Lower Bound Explained](https://www.youtube.com/watch?v=OK_SuFkaBW0)** — Economics Explained (8 min)
- 📚 **[RBA Explainer: Unconventional Monetary Policy](https://www.rba.gov.au/education/resources/explainers/unconventional-monetary-policy.html)** — RBA overview of YCC and TFF in Australia
