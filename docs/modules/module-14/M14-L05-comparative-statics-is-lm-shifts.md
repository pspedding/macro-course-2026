# Lesson M14.L05: Comparative Statics: Shifts in IS and LM

**Module:** The IS-LM Model Part I
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Predict the direction of output and interest rate changes following IS and LM shifts.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023) | [RBA](https://www.rba.gov.au)

---

## Explanation

Comparative statics in the IS-LM model traces the new equilibrium (Y\*, i\*) after an exogenous shock shifts one or both curves. There are four canonical cases:

**Case 1: IS shifts right** (e.g., ΔḠ > 0, ΔT̄ < 0, ΔX̄ > 0, Δa > 0)

Higher autonomous spending → IS moves right → at the old i, goods market wants higher Y → higher Y raises money demand → i rises until money market re-equilibrates. **Result: Y↑, i↑.**

*Partial crowding out:* The rise in i reduces investment (I = Ī − b_inv·i), offsetting some of the fiscal expansion. Y rises by less than the pure Keynesian multiplier (ΔA/( 1−b+m)) because higher i crowds out private investment. Full crowding out occurs only with a vertical LM (classical case, h = 0).

**Case 2: IS shifts left** (e.g., ΔḠ < 0, ΔX̄ < 0 — negative demand shock)

Lower autonomous spending → IS moves left → Y↓, i↓. The fall in i provides partial automatic offset via higher investment (crowding in), but Y still falls.

**Case 3: LM shifts right** (e.g., ΔM̄ > 0 — monetary expansion, or ΔP < 0)

Higher real money supply → excess money supply at old (Y, i) → i falls → lower i stimulates investment → Y rises. **Result: Y↑, i↓.**

*Monetary transmission:* Central bank expands M̄ → LM right → i falls → I rises (via IS) → Y rises via multiplier. The full chain links the money market to real output through the investment channel.

**Case 4: LM shifts left** (e.g., ΔM̄ < 0 — monetary tightening, or ΔP > 0 — price level rise)

Lower real money supply → excess money demand → i rises → investment falls → Y falls. **Result: Y↓, i↑.** This is the standard mechanism by which RBA rate hikes reduce inflation and output.

**Summary table:**

| Shock | IS/LM | ΔY | Δi |
|---|---|---|---|
| Fiscal expansion (ΔG↑) | IS → right | ↑ | ↑ |
| Fiscal contraction (ΔG↓) | IS → left | ↓ | ↓ |
| Monetary expansion (ΔM̄↑) | LM → right | ↑ | ↓ |
| Monetary tightening (ΔM̄↓) | LM → left | ↓ | ↑ |

**Australian policy context.** During 2022–2023, the RBA tightened monetary policy aggressively (LM shifted left), raising i\* and reducing Y\* — deliberately slowing demand to reduce inflation. Simultaneously, fiscal policy was contractionary at the margin (surplus emerging), shifting IS left. Both shocks pushed Y down, which was the policy intention. The key risk was over-tightening causing a recession.

---

## Worked Example

**Starting IS-LM equilibrium:** IS: i = 1.4 − 0.0006Y; LM: i = 0.00005Y − 0.1; initial Y\* = $2,307.7bn, i\* = 1.54% (i\* = 0.0154).

**Fiscal expansion: ΔḠ = +$50bn.** Autonomous spending A rises by 50. Using the IS equation:

> New A = 700 + 50 = 750
> New IS: i = 750/500 − (0.3/500)Y = 1.5 − 0.0006Y

**Step 1 — Find new Y\*:**

> Set new IS = LM: 1.5 − 0.0006Y = 0.00005Y − 0.1
> 1.5 + 0.1 = 0.00005Y + 0.0006Y
> 1.6 = 0.00065Y
> Y\* = 1.6/0.00065 = **$2,461.5bn**

**Step 2 — Find new i\*:**

> i\* = 0.00005 × 2,461.5 − 0.1 = 0.12308 − 0.1 = **0.02308 ≈ 2.31% (0.0231)**

**Step 3 — Quantify partial crowding out:**

- Pure Keynesian multiplier (no crowding out): ΔY_pure = 50 × (1/0.3) = 50 × 3.33 = $166.7bn
- Actual ΔY = 2,461.5 − 2,307.7 = **$153.8bn**
- Crowding out = 166.7 − 153.8 = **$12.9bn** of the potential stimulus is offset

The interest rate rise from 1.54% to 2.31% (Δi = 0.77 pp = 0.0077 decimal) reduces investment (ΔI = −b_inv × Δi = −500 × 0.0077 = −$3.85bn), which feeds through the multiplier (×1/0.3 ≈ 3.33) to reduce Y by $12.8bn ≈ $12.9bn relative to the pure Keynesian case. ✓

**Note:** The modest crowding-out ratio here reflects the large h = 5,000, meaning money demand is quite interest-sensitive (the LM is relatively flat). A flatter LM implies smaller interest rate increases from IS shifts, hence less crowding out. In practice, the degree of crowding out depends on the relative slopes of IS and LM (how interest-sensitive investment and money demand are).

---

## Common Misconception

**Misconception:** Fiscal expansion (IS right) always raises output by the full Keynesian multiplier amount in the IS-LM model.

**Correction:** The full multiplier (1/(1 − b + m)) applies only in the Keynesian cross model where the interest rate is held constant. In IS-LM, the rightward IS shift raises Y, which increases money demand, pushing up i\*. The higher i reduces investment, partially crowding out the fiscal expansion. The actual ΔY\* is strictly less than the Keynesian multiplier × ΔG unless the LM is horizontal (liquidity trap, where Δi = 0 and no crowding out occurs). The size of crowding out increases with the LM slope k/h.

---

## Practice Prompts

1. Using the IS-LM framework, compare the effects on (Y, i) of: (a) a pure fiscal expansion with constant money supply; and (b) a coordinated fiscal expansion with monetary accommodation (M̄ also increases to keep i constant). Which generates a larger increase in Y?
   → **Answer:**
   (a) **Fiscal expansion alone (IS right, LM fixed):** Y↑ and i↑. The interest rate rise partially crowds out investment, limiting the increase in Y.
   (b) **Fiscal expansion with monetary accommodation (IS right + LM right):** The central bank increases M̄ to prevent i from rising. With i fixed, there is no crowding out via the investment channel. The IS shift generates the full Keynesian multiplier effect without the partial offset. Y increases by more in case (b). The RBA implicitly accommodated fiscal policy in 2020 by holding rates at the lower bound, ensuring maximum fiscal multiplier effectiveness.

2. Starting from IS: i = 2.0 − 0.001Y and LM: i = 0.006Y − 14, find the new equilibrium Y\* and i\* after a monetary expansion shifts LM to: i = 0.006Y − 16. What are ΔY\* and Δi\*?
   → **Answer:**
   **Original equilibrium:**
   - 2.0 − 0.001Y = 0.006Y − 14 → 16 = 0.007Y → Y\* = 16/0.007 = **$2,286bn**
   - i\* = 0.006 × 2,286 − 14 = 13.714 − 14 = **−0.286%** *(near ZLB)*

   **New equilibrium:**
   - 2.0 − 0.001Y = 0.006Y − 16 → 18 = 0.007Y → Y\* = 18/0.007 = **$2,571bn**
   - i\* = 0.006 × 2,571 − 16 = 15.429 − 16 = **−0.571%** *(below ZLB)*

   - ΔY\* = 2,571 − 2,286 = **+$285bn**
   - Δi\* = −0.571% − (−0.286%) = **−0.286 pp** (interest rate falls, as expected from LM right shift)

3. In 2022–2023, the RBA raised the cash rate from 0.10% to 4.35% while the federal government moved toward a budget surplus. Describe this joint policy mix using IS-LM and assess the risk it posed for the Australian economy.
   → **Answer:** The policy mix combined a **leftward LM shift** (monetary tightening: higher i, lower Y) and a **leftward IS shift** (fiscal consolidation: lower G or higher T reduces autonomous spending, lower Y at any i). Both shocks point in the same direction: **Y↓ and i↑ (monetary dominates) or i ambiguous (if both shift left together)**. Specifically, LM left → Y↓, i↑; IS left → Y↓, i↓. The net effect on i depends on which shift dominates; the net effect on Y is unambiguous — **output falls**. The risk was over-tightening: combined contractionary fiscal and monetary policy could push Y below potential, causing unemployment to rise above NAIRU (estimated 4.0–4.25% post-COVID per RBA). The RBA and Treasury faced the challenge of calibrating the pace of tightening to achieve a "soft landing" — reducing inflation (requiring LM left) without triggering a recession (requiring IS to remain sufficiently expansionary to sustain near-potential output).

## Further Resources
- 📺 **[Macroeconomics: The IS-LM Model](https://www.youtube.com/watch?v=e_3clidGpfE)** — Economics in Many Lessons (15 min)
- 📺 **[LM part of the IS-LM model](https://www.youtube.com/watch?v=yro2jLBfyDQ)** — Khan Academy (8 min)
- 📚 **[RBA — Statement on Monetary Policy](https://www.rba.gov.au/publications/smp/)** — Quarterly RBA analysis applying IS-LM-style reasoning to current Australian conditions
