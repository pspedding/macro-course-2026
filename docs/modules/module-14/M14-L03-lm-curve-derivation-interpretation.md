# Lesson M14.L03: The LM Curve: Derivation and Interpretation

**Module:** The IS-LM Model Part I
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive the LM curve from money market equilibrium and explain its positive slope.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023) | [RBA](https://www.rba.gov.au)

---

## Explanation

The LM curve maps all combinations of output (Y) and the interest rate (i) at which the **money market is in equilibrium** (real money demand equals real money supply).

**Derivation.** Starting from the money market equilibrium condition (M13/M14.L02):

> M̄/P = kY − hi

Rearranging to express i as a function of Y:

> hi = kY − M̄/P
> i = (k/h)Y − M̄/(Ph)

This is the **LM curve equation**: a positive linear relationship between Y and i.

$$i = \frac{k}{h}Y - \frac{\bar{M}}{Ph}$$

**Slope:** di/dY = k/h > 0. The LM curve slopes **upward** in (Y, i) space.

**Intuition for positive slope:** Higher income Y increases transaction demand for money (kY rises). With a fixed money supply, this excess demand for money is eliminated only if the interest rate rises (reducing speculative demand −hi until equilibrium is restored). Hence each higher Y is associated with a higher i on the LM curve.

**Shifts in the LM curve:**

- **LM shifts right** (more output at given i) when: M̄ increases (central bank expands money supply) or P falls (real money supply M̄/P rises). Both create excess money supply at the existing (Y, i) → rate falls → LM moves right.
- **LM shifts left** when: M̄ decreases (central bank tightens) or P rises (inflation erodes real money supply).

**Special cases:**

1. **Liquidity trap (horizontal LM):** When h → ∞, money demand is infinitely interest-elastic (a tiny drop in i induces huge money demand). The LM curve is horizontal — the slope k/h → 0. Monetary policy is ineffective: any increase in M̄ is absorbed without changing i. This approximates conditions near the zero lower bound (2009, 2020–2021 globally).

2. **Classical case (vertical LM):** When h → 0, money demand has no speculative component. The LM curve is vertical: i = (k/h)Y → ∞ for finite Y, meaning only one level of Y is consistent with money market equilibrium at any interest rate. Monetary policy is maximally effective; fiscal policy causes complete crowding out.

---

## Worked Example

**Parameters:** k = 0.25, h = 5,000, M̄ = 500, P = 1.

**Step 1 — Write the LM equation:**

> i = (k/h)Y − M̄/(Ph)
> i = (0.25/5,000)Y − 500/(1 × 5,000)
> i = 0.00005Y − 0.1

**Step 2 — Find i when Y = 2,000:**

> i = 0.00005 × 2,000 − 0.1 = 0.1 − 0.1 = **0% (i = 0)**

**Step 3 — Find i when Y = 2,400:**

> i = 0.00005 × 2,400 − 0.1 = 0.12 − 0.1 = **0.02 (i = 2%)**

Consistent with M14.L02 worked example.

**Step 4 — Effect of an RBA money supply increase to M̄ = 600:**

New LM: i = 0.00005Y − 600/5,000 = 0.00005Y − 0.12

At Y = 2,400: i = 0.00005 × 2,400 − 0.12 = 0.12 − 0.12 = **0%**

The LM curve shifts down/right: at the same income Y = 2,400, the interest rate falls from 2% to 0%. Alternatively, at the same interest rate i = 2%, Y would be higher.

**Step 5 — Find Y when i = 2% (i = 0.02) under new LM:**

> 0.02 = 0.00005Y − 0.12 → 0.00005Y = 0.14 → Y = 0.14/0.00005 = **$2,800bn**

The rightward shift in LM supports $2,800bn of income at i = 2% (vs. $2,400bn before).

---

## Common Misconception

**Misconception:** The LM curve shifts when income changes.

**Correction:** A change in Y is a *movement along* the LM curve, not a shift. The LM curve already incorporates how i responds to changes in Y (via the money market). A shift in the LM curve occurs only when an *exogenous* variable changes — specifically the real money supply (M̄/P). A change in Y (e.g., due to a fiscal policy shock) moves the economy along a fixed LM curve to a new (Y, i) combination. Students must distinguish endogenous movements along curves from exogenous shifts of curves.

---

## Practice Prompts

1. Explain intuitively why the LM curve has a positive slope, and contrast this with why the IS curve has a negative slope.
   → **Answer:** **LM positive slope:** Higher income raises transaction demand for money. With fixed money supply, the interest rate must rise to reduce speculative demand and restore money market equilibrium. The i–Y relationship is positive. **IS negative slope:** Higher interest rates raise the cost of investment, reducing investment spending and (via the multiplier) equilibrium income. The i–Y relationship is negative. The two curves capture different markets (money vs. goods) and are positively/negatively sloped for distinct, logical reasons.

2. Using k = 0.30, h = 60, M̄ = 720, P = 1, write the LM equation and find: (a) i when Y = 1,800; (b) i when Y = 2,400; (c) Y when i = 0.03.
   → **Answer:**
   - LM: i = (0.30/60)Y − 720/(60) = **0.005Y − 12**
   - (a) i = 0.005 × 1,800 − 12 = 9 − 12 = **−3%** *(below zero lower bound; in practice i = 0)*
   - (b) i = 0.005 × 2,400 − 12 = 12 − 12 = **0%**
   - (c) 0.03 = 0.005Y − 12 → 0.005Y = 12.03 → Y = **$2,406bn**

3. During the COVID pandemic (2020–2021), the RBA implemented quantitative easing and held the cash rate at 0.10%. Using the LM framework, describe what this implies about the shape of the LM curve in that period and what it means for the relative effectiveness of fiscal versus monetary policy.
   → **Answer:** Near the zero lower bound (cash rate at 0.10%), the LM curve approaches horizontal (approaching a liquidity trap). With h very large (money demand highly interest-elastic), any additional money supply is absorbed into speculative balances without reducing i further. Monetary policy loses traction: further expansion of M̄ does not lower i or stimulate investment. Fiscal policy (IS shifts) becomes relatively more effective because the horizontal LM means a rightward IS shift raises Y without generating much offsetting interest rate increase (minimal crowding out). This explains why Australia's government relied heavily on fiscal stimulus (JobKeeper, etc.) during 2020 rather than relying solely on the RBA — the RBA had exhausted conventional monetary policy space.

## Further Resources
- 📺 **[LM part of the IS-LM model](https://www.youtube.com/watch?v=yro2jLBfyDQ)** — Khan Academy (8 min)
- 📺 **[Macroeconomics: The IS-LM Model](https://www.youtube.com/watch?v=e_3clidGpfE)** — Economics in Many Lessons (15 min)
- 📚 **[RBA — How the RBA Implements Monetary Policy](https://www.rba.gov.au/education/resources/explainers/how-rba-implements-monetary-policy.html)** — LM curve derivation and the role of money demand in Australian monetary analysis

[VISUAL NEEDED: LM curve diagram in (Y, i) space showing the upward-sloping LM curve. Label slope k/h. Show rightward LM shift from M̄ increase. Include inset diagrams showing the two special cases: horizontal LM (liquidity trap, h → ∞) and vertical LM (classical case, h → 0).]
