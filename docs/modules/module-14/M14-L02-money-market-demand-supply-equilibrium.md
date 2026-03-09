# Lesson M14.L02: The Money Market: Demand, Supply, and Equilibrium

**Module:** The IS-LM Model Part I
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Derive money market equilibrium from the Keynesian money demand function.
**Data as of:** 2024
**Provenance:** [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax)) | [MIT OCW 14.02](https://ocw.mit.edu/courses/14-02-principles-of-macroeconomics-spring-2023) | [RBA](https://www.rba.gov.au)

---

## Explanation

The money market brings together the demand for real money balances (L) and the exogenously fixed real money supply (M/P) to determine the equilibrium interest rate.

**Money Demand.** Keynes identified two motives for holding money rather than interest-bearing assets:

1. **Transaction motive:** Households and firms hold money to carry out everyday transactions. This demand rises with income Y: more transactions require more money. Transaction demand = kY, where k > 0 is the income velocity of money demand (inverse of velocity).

2. **Speculative (asset) motive:** Money competes with bonds as an asset. When the interest rate i is high, bonds are attractive (high opportunity cost of holding money) → less money demanded for speculation. When i is low, bonds are unattractive → money held as a store of value. Speculative demand = −hi, where h > 0 is the interest sensitivity of money demand.

**Keynesian Money Demand Function:**

> L = kY − hi

where L is real money demand, k > 0, h > 0.

**Money Supply:** The central bank (RBA) controls the nominal money supply M̄. The real money supply is M̄/P, where P is the price level (fixed in the short run). The real money supply is treated as **exogenous** (a vertical supply curve in (L, i) space):

> M^S/P = M̄/P

**Equilibrium condition:** Real money demand = real money supply:

> kY − hi = M̄/P

**Solving for the equilibrium interest rate:**

> hi = kY − M̄/P
> i = (kY − M̄/P) / h = (kY)/h − M̄/(Ph)

**Interpretation:**
- Higher Y → higher transaction demand → money market clears only at higher i (demand curve shifts right, rate rises).
- Higher M̄/P → greater real money supply → rate falls (supply shifts right, rate falls).
- Higher h (more interest-sensitive demand) → flatter demand curve → smaller interest rate change for a given shift.

---

## Worked Example

**Parameters:** k = 0.25 (income sensitivity), h = 5,000 (interest sensitivity), M̄ = 500 (nominal money stock in $bn), P = 1.0 (price index = 1), Y = 2,000 ($bn).

**Step 1 — Real money supply:**

> M̄/P = 500/1.0 = **$500bn**

**Step 2 — Set demand equal to supply and solve for i:**

> kY − hi = M̄/P
> 0.25 × 2,000 − 5,000 × i = 500
> 500 − 5,000i = 500
> 5,000i = 500 − 500 = 0
> i = **0% (equilibrium rate at this income level)**

**Step 3 — Now suppose Y rises to 2,400:**

> 0.25 × 2,400 − 5,000i = 500
> 600 − 5,000i = 500
> 5,000i = 100
> i = 100/5,000 = **0.02 = 2%**

**Interpretation:** As income rises from $2,000bn to $2,400bn (+20%), the equilibrium interest rate rises from 0% to 2%, because higher income drives up transaction demand for money, and with a fixed money supply, the interest rate must rise to reduce speculative demand and restore equilibrium.

**Step 4 — Effect of a money supply increase to M̄ = 600 (at Y = 2,400):**

> 0.25 × 2,400 − 5,000i = 600/1.0
> 600 − 5,000i = 600
> 5,000i = 0
> i = **0%**

The RBA's money expansion (from 500 to 600) fully offsets the income-driven rate increase, returning i to 0%.

---

## Common Misconception

**Misconception:** Money demand only depends on income — people hold money solely to buy things.

**Correction:** Keynes's liquidity preference framework includes both a transaction motive (L = kY) and a speculative motive (L = −hi). The speculative motive arises because money competes with bonds as a portfolio asset. At very low interest rates, bonds offer little return and people prefer money (liquidity trap region). Ignoring the speculative motive implies h → 0, which gives a vertical LM curve — the Classical case — and is empirically unrealistic for most short-run analyses. The full function L = kY − hi captures both motives.

---

## Practice Prompts

1. Define the transaction motive and the speculative motive for holding money. Why does the speculative motive make money demand negatively related to the interest rate?
   → **Answer:** The **transaction motive** arises because money is needed as a medium of exchange for everyday purchases; demand rises with income (kY). The **speculative motive** arises because money is an asset competing with interest-bearing bonds: when i is high, bonds offer attractive returns, so households shift from money to bonds (money demand falls); when i is low, bonds offer poor returns and money is preferred as a store of value (money demand rises). The opportunity cost of holding money is the interest rate forgone — hence money demand falls (rises) as i rises (falls): speculative demand = −hi.

2. Using k = 0.20, h = 80, M̄ = 600, P = 1, find the equilibrium interest rate when: (a) Y = 2,000 and (b) Y = 2,500. What is Δi?
   → **Answer:**
   - Real money supply = 600/1 = **600**
   - Formula: i = (kY − M̄/P)/h
   - (a) i = (0.20 × 2,000 − 600)/80 = (400 − 600)/80 = **−200/80 = −2.5%**
   *(A negative equilibrium rate implies the model requires i ≥ 0 in practice — the zero lower bound. This indicates money supply is very high relative to transaction demand at this income level.)*
   - (b) i = (0.20 × 2,500 − 600)/80 = (500 − 600)/80 = **−100/80 = −1.25%**
   - Δi = −1.25% − (−2.5%) = **+1.25 percentage points** (rate rises by 1.25pp as Y increases by $500bn)

3. In 2020, central banks globally (including the RBA) massively expanded their balance sheets through quantitative easing (QE), increasing M̄. Using the money market diagram, explain the predicted effect on interest rates. Why might this have been less effective at stimulating borrowing than the model predicts?
   → **Answer:** An increase in M̄ (with P fixed) shifts the real money supply M̄/P rightward. At the existing income level Y and interest rate i, there is now excess money supply — people hold more money than desired. To rebalance portfolios, they buy bonds, bidding bond prices up and interest rates down. The new equilibrium is at lower i. This is the standard channel from monetary expansion to lower rates. However, in the liquidity trap region (near the zero lower bound, as in 2020), h becomes very large — demand for money is extremely interest-elastic (the speculative demand becomes horizontal). Any increase in money supply is simply absorbed as precautionary/speculative balances without further reducing i (which was already near 0%). QE effectiveness was limited not by the money market mechanics but by the zero lower bound and the fact that banks were unwilling (or corporates/households were unwilling) to borrow even at near-zero rates.

## Further Resources
- 📺 **[The Money Market (1 of 2) - Macro Topic 4.5](https://www.youtube.com/watch?v=vc7wmTT8m0M)** — ACDC Economics (10 min)
- 📺 **[LM part of the IS-LM model](https://www.youtube.com/watch?v=yro2jLBfyDQ)** — Khan Academy (8 min)
- 📚 **[RBA — How the RBA Implements Monetary Policy](https://www.rba.gov.au/education/resources/explainers/how-rba-implements-monetary-policy.html)** — Money market mechanics and how the RBA targets the cash rate

[VISUAL NEEDED: Money market diagram with real money supply M̄/P as vertical line and money demand L = kY − hi as downward-sloping line. Show equilibrium at (M̄/P, i*). Illustrate two panels: (1) an income increase shifts L right, raising i*; (2) a money supply increase shifts M̄/P right, reducing i*.]
