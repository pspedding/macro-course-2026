# Lesson M15.L05: The Policy Mix: Fiscal and Monetary Coordination

**Module:** The IS-LM Model Part II
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Evaluate how the fiscal-monetary policy mix determines the composition of aggregate demand.
**Data as of:** 2024
**Provenance:** [Reserve Bank of Australia](https://www.rba.gov.au) | [OpenStax Macroeconomics 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

## Explanation

Policymakers have **two main instruments** to influence macroeconomic outcomes:

1. **Fiscal policy** (government): controls *G* (spending) and *T* (taxes), which shift the IS curve.
2. **Monetary policy** (central bank): controls *M* or the interest rate target *r*, which shifts the LM curve.

With two instruments, policymakers can pursue **two targets simultaneously** — a target level of output *Y* and a target composition of demand (the split between private investment *I* and public/consumption spending). This is the **Tinbergen Principle**: one instrument per target.

**Four canonical policy mixes:**

| Fiscal | Monetary | Effect on Y | Effect on r | Composition |
|---|---|---|---|---|
| Expansionary (↑G) | Tight (↓M) | Ambiguous / moderate | Higher r | Low investment, more government |
| Expansionary (↑G) | Expansionary (↑M) | Strongly higher Y | Smaller r rise | Balanced expansion |
| Tight (↓G) | Expansionary (↑M) | Ambiguous / moderate | Lower r | Investment-friendly, less government |
| Tight (↓G) | Tight (↓M) | Strongly lower Y | Higher r | Contraction |

**Key insight:** To reach a *given Y target* while changing the **composition** of demand, mix the instruments:

- Want higher investment? → Loosen monetary (lower *r*), tighten fiscal (offset Y with lower G).
- Want to crowd in public services? → Loosen fiscal, tighten monetary (higher *r* reduces I, but G rises).

**Australia COVID-19 (2020):** Both arms were expansionary simultaneously. Fiscal stimulus reached ~15% of GDP; the RBA cut to 0.10%. Result: large positive Y impulse with historically low *r*, minimal crowding out, and investment supported.

**Australia 2022–23:** As inflation peaked at 7.8% (Q4 2022), the policy mix reversed: the RBA raised the cash rate 13 times (0.10% → 4.35% by November 2023) while fiscal consolidation reduced the deficit. Both arms tightened, producing a sharp cooling of aggregate demand and eventual easing of inflation.

**Notation:** *G* = government spending; *M* = nominal money supply; *r* = interest rate; *Y* = equilibrium output; *I = Ī − b_r × r* = investment; *C* = consumption.

## Worked Example

**Setup:**

- IS curve: *Y = A − 100r*, where *A* is autonomous spending
- LM curve: *Y = B + 100r*, where *B* depends on *M/P*
- Investment: *I = 400 − 60r*
- Target output: *Y* = 900

**Scenario A — Expansionary fiscal + tight monetary (high-r mix):**

Suppose policymakers want *Y = 900* but at a **high** interest rate (e.g., to reduce investment pressure on the current account), achieved by raising *G* and tightening *M/P*.

Let *A = 1200* (IS shifted right by ΔG: IS: *Y = 1200 − 100r*) and *B = 500* (tight LM: *Y = 500 + 100r*).

Equilibrium:
```
1200 − 100r = 500 + 100r
700 = 200r → r_A = 3.5%
Y_A = 1200 − 100(3.5) = 850... 
```
Adjust *A = 1300*:
```
1300 − 100r = 500 + 100r
800 = 200r → r_A = 4%
Y_A = 1300 − 100(4) = 900 ✓
```

Investment: *I_A = 400 − 60(4) = 400 − 240 = **160***

**Scenario B — Tight fiscal + expansionary monetary (low-r mix):**

Same *Y = 900* target, but with **low** *r* to encourage investment. Reduce *G* (A = 1000, IS: *Y = 1000 − 100r*) and expand *M/P* (B = 800, LM: *Y = 800 + 100r*).

Equilibrium:
```
1000 − 100r = 800 + 100r
200 = 200r → r_B = 1%
Y_B = 1000 − 100(1) = 900 ✓
```

Investment: *I_B = 400 − 60(1) = 400 − 60 = **340***

**Comparison:**

| Scenario | Y | r (%) | Investment I |
|---|---|---|---|
| A: Loose fiscal + tight monetary | 900 | 4.0 | 160 |
| B: Tight fiscal + loose monetary | 900 | 1.0 | 340 |

**Both achieve the same output level (Y = 900), but the composition is radically different.** Scenario B delivers more than double the private investment (340 vs 160) — investment-led growth — while Scenario A delivers government-led growth with suppressed private investment.

## Common Misconception

**Misconception:** Fiscal and monetary policy always work in the same direction — if one is expansionary, the other must also be expansionary to maintain output.

**Correction:** Fiscal and monetary policy are independent instruments that can be combined in any configuration. The classic Mundell (1962) insight is that the **mix** determines the *composition* of output, not just its level. A government wishing to raise output while keeping interest rates low (to avoid exchange-rate appreciation in an open economy, or to encourage capital formation) can loosen monetary policy while keeping fiscal policy neutral. Conversely, a tight fiscal–loose monetary mix (Scenario B above) produces the same Y with a very different investment-consumption composition.

## Practice Prompts

1. **Conceptual:** Using the IS-LM diagram, illustrate how a simultaneous rightward shift in both IS and LM results in higher output *Y* with an ambiguous effect on *r*. What determines whether *r* rises or falls?
   → **Answer:** IS shifts right (from ↑G) and LM shifts right (from ↑M). Both push *Y* up. The interest rate effect depends on the **relative magnitudes** of the shifts: if LM shifts more than IS, *r* falls; if IS shifts more, *r* rises; if they shift equally, *r* is unchanged. In Australia's COVID response, the aggressive monetary expansion (LM shift) relative to the fiscal shift kept *r* near zero.

2. **Numerical:** Using the model above, find the equilibrium (Y, r) when both instruments are moderately expansionary: A = 1100 (IS: Y = 1100 − 100r) and B = 700 (LM: Y = 700 + 100r). What is investment at this equilibrium?
   → **Answer:**
   ```
   IS = LM: 1100 − 100r = 700 + 100r
   400 = 200r → r = 2%
   Y = 1100 − 100(2) = 900
   I = 400 − 60(2) = 400 − 120 = 280
   ```
   **Y = 900, r = 2%, I = 280.** The same output as Scenarios A and B, but with an intermediate interest rate and investment level — confirming the policy mix determines composition, not just the level of Y.

3. **Application:** In 2022–23, the RBA raised rates 13 times while the federal government moved toward fiscal surplus. Using the IS-LM framework, trace the effects of this combined tightening on (i) equilibrium output, (ii) the interest rate, and (iii) private investment.
   → **Answer:** (i) Fiscal consolidation (↓G) shifts IS **leftward**, reducing *Y* at any given *r*. Monetary tightening (↓M or ↑r target) shifts LM **leftward**, raising *r* and reducing *Y* further. Combined, both shifts reduce equilibrium *Y* substantially — consistent with Australian GDP growth slowing from ~3.5% in 2022 to ~1.5% in 2023. (ii) *r* rises strongly from the monetary tightening (the LM effect dominates). (iii) Higher *r* reduces private investment via *I = Ī − b_r × r* — consistent with a sharp fall in dwelling investment and business investment in 2023.

## Further Resources

- 📺 **[IS-LM: Fiscal & Monetary Policy](https://www.youtube.com/watch?v=XBkGZ1mA43E)** — Jacob Clifford Economics (12 min)
- 📺 **[IS-LM Model Diagrams – The Effect of Policy Mixes](https://www.youtube.com/watch?v=ZA66asJE0ew)** — Economics in Many Lessons (11 min)
- 📚 **[RBA Statement on Monetary Policy – November 2023](https://www.rba.gov.au/publications/smp/2023/nov/)** — Context for the 2022–23 tightening cycle
