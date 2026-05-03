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

## Visual — Money Market Equilibrium and Shifts

<div style="overflow-x: auto; margin: 1rem 0;">
<svg viewBox="0 0 1200 420" width="100%" xmlns="http://www.w3.org/2000/svg">
  <style>
    .axis { stroke: #333; stroke-width: 2; }
    .curve { fill: none; stroke-width: 3; }
    .guide { stroke: #777; stroke-width: 1.5; stroke-dasharray: 6 5; }
    .label { font: 16px Arial, sans-serif; fill: #222; }
    .small { font: 13px Arial, sans-serif; fill: #444; }
    .title { font: 18px Arial, sans-serif; font-weight: 700; fill: #222; }
  </style>

  <!-- Panel 1 -->
  <text x="190" y="28" text-anchor="middle" class="title">Baseline equilibrium</text>
  <line x1="70" y1="340" x2="330" y2="340" class="axis" />
  <line x1="70" y1="340" x2="70" y2="60" class="axis" />
  <text x="200" y="385" text-anchor="middle" class="label">Real money balances (M/P, L)</text>
  <text x="22" y="205" transform="rotate(-90 22 205)" text-anchor="middle" class="label">Interest rate, i</text>
  <line x1="250" y1="80" x2="250" y2="320" class="curve" stroke="#1f77b4" />
  <line x1="110" y1="90" x2="310" y2="290" class="curve" stroke="#d62728" />
  <circle cx="250" cy="230" r="5" fill="#222" />
  <line x1="250" y1="230" x2="250" y2="340" class="guide" />
  <line x1="70" y1="230" x2="250" y2="230" class="guide" />
  <text x="257" y="78" class="label">M̄/P</text>
  <text x="128" y="104" class="label">L = kY − hi</text>
  <text x="258" y="224" class="label">E</text>
  <text x="48" y="235" class="label">i*</text>

  <!-- Panel 2 -->
  <text x="600" y="28" text-anchor="middle" class="title">Income rises: Y↑ shifts money demand right</text>
  <line x1="480" y1="340" x2="740" y2="340" class="axis" />
  <line x1="480" y1="340" x2="480" y2="60" class="axis" />
  <text x="610" y="385" text-anchor="middle" class="label">Real money balances (M/P, L)</text>
  <text x="432" y="205" transform="rotate(-90 432 205)" text-anchor="middle" class="label">Interest rate, i</text>
  <line x1="660" y1="80" x2="660" y2="320" class="curve" stroke="#1f77b4" />
  <line x1="510" y1="110" x2="710" y2="310" class="curve" stroke="#d62728" />
  <line x1="540" y1="80" x2="740" y2="280" class="curve" stroke="#ff7f0e" />
  <circle cx="660" cy="260" r="5" fill="#d62728" />
  <circle cx="660" cy="200" r="5" fill="#ff7f0e" />
  <line x1="480" y1="260" x2="660" y2="260" class="guide" />
  <line x1="480" y1="200" x2="660" y2="200" class="guide" />
  <text x="668" y="78" class="label">M̄/P</text>
  <text x="528" y="116" class="small">L(Y₀)</text>
  <text x="560" y="74" class="small">L(Y₁ &gt; Y₀)</text>
  <text x="456" y="265" class="small">i₀</text>
  <text x="456" y="205" class="small">i₁</text>
  <text x="560" y="365" class="small">With fixed supply, higher Y raises i.</text>

  <!-- Panel 3 -->
  <text x="1010" y="28" text-anchor="middle" class="title">Money supply rises: M̄↑ shifts supply right</text>
  <line x1="890" y1="340" x2="1150" y2="340" class="axis" />
  <line x1="890" y1="340" x2="890" y2="60" class="axis" />
  <text x="1020" y="385" text-anchor="middle" class="label">Real money balances (M/P, L)</text>
  <text x="842" y="205" transform="rotate(-90 842 205)" text-anchor="middle" class="label">Interest rate, i</text>
  <line x1="930" y1="90" x2="1130" y2="290" class="curve" stroke="#d62728" />
  <line x1="1030" y1="80" x2="1030" y2="320" class="curve" stroke="#1f77b4" />
  <line x1="1080" y1="80" x2="1080" y2="320" class="curve" stroke="#17becf" />
  <circle cx="1030" cy="190" r="5" fill="#1f77b4" />
  <circle cx="1080" cy="240" r="5" fill="#17becf" />
  <line x1="890" y1="190" x2="1030" y2="190" class="guide" />
  <line x1="890" y1="240" x2="1080" y2="240" class="guide" />
  <text x="938" y="102" class="label">L = kY − hi</text>
  <text x="1010" y="78" class="small">M̄₀/P</text>
  <text x="1060" y="78" class="small">M̄₁/P</text>
  <text x="864" y="195" class="small">i₀</text>
  <text x="864" y="245" class="small">i₁</text>
  <text x="952" y="365" class="small">With fixed demand, higher M̄/P lowers i.</text>
</svg>
</div>

*Figure: The money market equilibrium is where real money demand intersects the exogenous real money supply. A rise in income shifts money demand right and raises the equilibrium interest rate; a rise in the real money supply shifts the vertical supply line right and lowers the equilibrium interest rate.*

## Further Resources
- 📺 **[The Money Market (1 of 2) - Macro Topic 4.5](https://www.youtube.com/watch?v=vc7wmTT8m0M)** — ACDC Economics (10 min)
- 📺 **[LM part of the IS-LM model](https://www.youtube.com/watch?v=yro2jLBfyDQ)** — Khan Academy (8 min)
- 📚 **[RBA — How the RBA Implements Monetary Policy](https://www.rba.gov.au/education/resources/explainers/how-rba-implements-monetary-policy.html)** — Money market mechanics and how the RBA targets the cash rate

