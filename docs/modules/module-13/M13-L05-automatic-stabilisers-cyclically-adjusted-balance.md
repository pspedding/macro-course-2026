# Lesson M13.L05: Automatic Stabilisers and the Cyclically-Adjusted Budget Balance

**Module:** National Accounting, Keynesian Income-Expenditure Model and Fiscal Policy
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Calculate the cyclically-adjusted budget balance to distinguish structural from cyclical deficits.
**Data as of:** 2024
**Provenance:** [ABS National Accounts](https://www.abs.gov.au/statistics/economy/national-accounts) | [RBA](https://www.rba.gov.au) | [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

---

## Explanation

**Automatic stabilisers** are features of the fiscal system that reduce output fluctuations without requiring active policy decisions. Two key mechanisms operate:

1. **Progressive taxation:** As income falls in a recession, tax revenue falls more than proportionally (because households drop into lower brackets). This reduces the tax burden automatically, supporting disposable income and consumption. Conversely, in booms, rising income pushes households into higher brackets, withdrawing purchasing power.

2. **Transfer payments (unemployment benefits):** Government spending on unemployment benefits rises automatically in recessions (more eligible recipients) and falls in expansions. This supports household income when it is most needed.

**Cyclically-Adjusted Budget Balance (CABB)**, also called the structural budget balance, strips out these automatic cyclical movements to reveal the underlying discretionary fiscal stance:

> CABB = Actual Balance − Cyclical Component

The **cyclical component** measures how much the actual balance differs from what it would be at potential output (Y_P):

> Cyclical Component = ε × (Y − Y_P)/Y_P = ε × Output Gap (%)

where ε is the budget balance sensitivity (typically estimated around 0.3–0.4 for Australia by the OECD — meaning a 1% output gap changes the budget balance by 0.3–0.4% of GDP).

**Output gap:** (Y − Y_P)/Y_P × 100, expressed as a percentage. Negative output gap = recession (Y < Y_P); positive = boom.

**Interpretation:** A large actual deficit during a recession may reflect mostly *cyclical* factors (automatic stabilisers doing their job) rather than reckless discretionary spending. Policymakers use the CABB to judge whether consolidation is needed or whether apparent deficits are self-correcting.

**Australian example (FY2020):** The actual budget deficit was approximately $213bn (including COVID spending). With a deep negative output gap, the cyclical component was large — but the structural component (discretionary COVID stimulus) was also substantial, including JobKeeper and supplements.

---

## Worked Example

**Given:**
- Potential GDP: Y_P = $2,000bn
- Actual GDP: Y = $1,900bn (recession; output gap = −5%)
- Budget sensitivity: ε = 0.35
- Actual budget balance: −$60bn (deficit of $60bn)

**Step 1 — Compute the output gap:**

> Output gap = (Y − Y_P)/Y_P = (1,900 − 2,000)/2,000 = −100/2,000 = **−0.05 (−5%)**

**Step 2 — Compute the cyclical component:**

> Cyclical component = ε × output gap × Y_P
> = 0.35 × (−0.05) × 2,000
> = 0.35 × (−100)
> = **−$35bn**

(The cyclical component is −$35bn, meaning the recession automatically worsened the budget by $35bn.)

**Step 3 — Compute the CABB:**

> CABB = Actual Balance − Cyclical Component
> = −60 − (−35)
> = −60 + 35
> = **−$25bn**

**Interpretation:** Of the $60bn actual deficit, $35bn is cyclical (automatic stabilisers) and $25bn is structural (discretionary policy stance). Even if the economy returned to potential, a $25bn structural deficit would remain without policy action.

**Step 4 — Structural deficit as % of GDP:**

> −25/2,000 × 100 = **−1.25% of GDP** (structural deficit)

---

## Common Misconception

**Misconception:** A large budget deficit always indicates irresponsible fiscal policy.

**Correction:** During a recession, automatic stabilisers mechanically push the budget toward deficit — tax revenues fall and welfare spending rises — even without any new discretionary spending decisions. The cyclically-adjusted (structural) balance isolates the discretionary component. A government may be running a large actual deficit while maintaining a balanced structural position, meaning no new net stimulus has been added. Judging fiscal policy requires examining the CABB, not just the headline deficit.

---

## Practice Prompts

1. What are the two main types of automatic stabilisers, and through what mechanism does each reduce the amplitude of the business cycle?
   → **Answer:** (1) **Progressive taxation:** In recessions, falling income reduces tax revenue (and effective tax rates), boosting household disposable income and consumption relative to what a flat tax would imply. In booms, rising incomes are taxed more heavily, dampening consumption growth. (2) **Unemployment benefits:** In recessions, more workers qualify for benefits, increasing transfer payments and supporting aggregate demand automatically. In expansions, falling unemployment reduces benefit outlays. Both mechanisms act as built-in demand stabilisers without requiring legislative action.

2. Suppose Y_P = $2,500bn, actual Y = $2,625bn (a boom), ε = 0.40, and the actual budget balance = +$30bn. Calculate the cyclically-adjusted budget balance.
   → **Answer:**
   - Output gap = (2,625 − 2,500)/2,500 = 125/2,500 = **+0.05 (+5%)**
   - Cyclical component = 0.40 × 0.05 × 2,500 = 0.40 × 125 = **+$50bn**
   (The boom has automatically improved the budget by +$50bn.)
   - CABB = Actual Balance − Cyclical Component = 30 − 50 = **−$20bn**
   **Interpretation:** Despite a headline surplus of $30bn, the structural position is actually a **deficit of $20bn**. The apparent surplus is entirely driven by the cyclical boom; underlying discretionary policy is expansionary.

3. Why might the Australian government's FY2023 budget surplus of approximately $22bn overstate the underlying structural improvement in the budget position? What cyclical factors were at play?
   → **Answer:** The FY2023 surplus (~$22bn) reflected an unusually strong cyclical position: (1) the unemployment rate fell below 4% — well below NAIRU (~4.0–4.25% post-COVID per RBA estimates) — generating above-trend tax revenue from wages and corporate profits; (2) record commodity prices (iron ore, coal, LNG) boosted company tax receipts from resource exporters; (3) high inflation raised nominal incomes into higher tax brackets (fiscal drag). All three are cyclical/windfall factors. The structural budget position was likely still close to balance or slightly in deficit, meaning the surplus was not fully indicative of a sustainably improved discretionary stance.

## Further Resources
- 📺 **[Fiscal Policy and Stimulus: Crash Course Economics #8](https://www.youtube.com/watch?v=otmgFQHbaDo)** — Crash Course (12 min)
- 📺 **[Keynesian cross and the multiplier](https://www.youtube.com/watch?v=aSY8XPGChAU)** — Khan Academy (8 min)
- 📚 **[Australian Government Budget — Budget Papers](https://budget.gov.au/)** — Commonwealth Budget papers including underlying cash balance and structural balance estimates
