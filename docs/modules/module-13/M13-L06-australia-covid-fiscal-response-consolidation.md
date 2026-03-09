# Lesson M13.L06: Australia's COVID Fiscal Response and Fiscal Consolidation

**Module:** National Accounting, Keynesian Income-Expenditure Model and Fiscal Policy
**Level:** intermediate
**Duration:** 30 minutes
**Learning Objective:** Evaluate Australia's COVID fiscal response using the IS-multiplier framework.
**Data as of:** 2024
**Provenance:** [RBA](https://www.rba.gov.au) | [ABS National Accounts](https://www.abs.gov.au/statistics/economy/national-accounts) | [OpenStax Macro 3e](https://socialsci.libretexts.org/Bookshelves/Economics/Macroeconomics/Principles_of_Macroeconomics_3e_(OpenStax))

---

## Explanation

Australia's COVID-19 fiscal response (2020–21) was among the largest peacetime fiscal expansions in the country's history, totalling approximately **$300bn** across federal and state governments.

**Key measures:**

| Programme | Cost |
|---|---|
| JobKeeper wage subsidy | $89bn (final audited; initial estimate $70bn) |
| JobSeeker supplement (doubled rate) | ~$14bn |
| HomeBuilder grant | ~$2.5bn |
| Early superannuation access | ~$36bn (not counted as budget cost but reduced household saving) |
| Other health, business, state measures | ~$160bn |

**IS-multiplier framework.** Each dollar of fiscal stimulus shifts the IS curve to the right (or, in Keynesian cross terms, raises autonomous expenditure). The income effect is:

> ΔY = k_G × ΔG + k_T × (−ΔT)

where a tax reduction (ΔT < 0) raises disposable income. With a multiplier k ≈ 0.9 (Treasury mid-range) and total discretionary stimulus of ~$200bn (net of automatic stabilisers):

> ΔY ≈ 0.9 × 200 = **~$180bn GDP support** (approximately 9% of 2019 GDP)

Australia's economy contracted by only −2.4% in FY2020 (vs. OECD average of around −5%), partly attributable to this fiscal support and successful health containment.

**Fiscal consolidation (2022–23).** As economic recovery took hold, the structural deficit narrowed sharply. The FY2023 federal budget recorded a surplus of approximately **$22bn** — the first surplus since 2018-19 — driven by strong labour market outcomes, commodity price windfalls, and bracket creep.

**Medium-term fiscal pressures.** Despite the surplus, Australia faces structural spending increases from:
- **NDIS:** Growing at ~14% per annum, projected to reach $50bn+ annually by the late 2020s.
- **Defence:** Commitment to 2%+ of GDP; AUKUS submarine programme (>$200bn over decades).
- **Interest costs:** Higher debt levels and rising interest rates have increased debt servicing.
- **Ageing population:** Intergenerational Report (2023) projects health and aged care spending to rise substantially as a share of GDP.

---

## Worked Example

**Scenario:** Evaluate the GDP impact of JobKeeper ($89bn) as a direct income transfer/wage subsidy. Assume MPC b = 0.8, import propensity m = 0.1, so multiplier k = 1/(1 − 0.8 + 0.1) = 1/0.3 = 3.33.

**However:** JobKeeper was a transfer (wage subsidy), not direct government consumption. Transfers affect GDP indirectly through household consumption:

**Step 1 — First-round consumption effect:**

> ΔC = b × ΔTransfer = 0.8 × 89 = **$71.2bn**

**Step 2 — Apply multiplier to this first-round consumption increase:**

> ΔY = ΔC × k_G = 71.2 × 3.33 = **$237.2bn**

Wait — this double-counts. The correct approach is to treat the transfer as increasing disposable income, applying the tax multiplier:

> ΔY = |k_T| × ΔTransfer = (b/(1 − b + m)) × 89 = (0.8/0.3) × 89 = 2.67 × 89 = **$237.3bn**

**Step 3 — Interpret.** This $237bn estimate is an upper bound assuming no crowding out, no leakage to savings beyond MPC, and the full multiplier applies. The actual Treasury estimate using a fiscal multiplier of ~0.9 gives:

> ΔY ≈ 0.9 × 89 = **~$80bn GDP impact from JobKeeper alone**

The lower real-world estimate reflects partial Ricardian equivalence, import leakage, and the fact that some JobKeeper went to firms that would have survived anyway (deadweight).

---

## Common Misconception

**Misconception:** Australia's FY2023 budget surplus means the government has eliminated its fiscal challenges and debt is no longer a concern.

**Correction:** The surplus reflected largely cyclical and windfall factors (low unemployment, high commodity prices, inflation-driven bracket creep) rather than structural fiscal reform. Gross Commonwealth debt remains above $900bn. Medium-term structural spending pressures from NDIS, defence, interest costs, and an ageing population mean the Intergenerational Report (2023) projects sustained structural deficits unless revenue or structural spending is addressed. A single surplus year does not resolve a structural imbalance.

---

## Practice Prompts

1. What is the theoretical difference between a government spending multiplier and a transfer payment multiplier? Why is the transfer multiplier smaller?
   → **Answer:** A government spending multiplier (k_G = 1/(1 − b + m)) applies when the government directly purchases goods and services — each dollar enters aggregate expenditure at full face value. A transfer payment (e.g., JobKeeper) gives income to households, who then spend only a fraction b (MPC) on domestic goods. The effective multiplier for transfers is k_T_transfer = b/(1 − b + m) = b × k_G < k_G. With b < 1, the transfer multiplier is always smaller because the first-round injection is partially saved.

2. Using a transfer multiplier of b/(1 − b + m) with b = 0.75 and m = 0.10, estimate the total GDP impact of the early superannuation release ($36bn). Compare this to a direct government spending equivalent.
   → **Answer:**
   - Denominator: 1 − 0.75 + 0.10 = **0.35**
   - Transfer multiplier: 0.75/0.35 = **2.143**
   - GDP impact (transfer): 36 × 2.143 = **$77.1bn**
   - Government spending multiplier: 1/0.35 = **2.857**
   - GDP impact (direct spending): 36 × 2.857 = **$102.9bn**
   - Difference: $102.9 − $77.1 = **$25.8bn less from the transfer approach**
   The superannuation release generated ~25% less GDP stimulus than an equivalent direct spending programme, because households saved 25 cents of every dollar released.

3. Australia's medium-term fiscal position faces structural pressures from NDIS growth, defence commitments, and an ageing population. Using the sectoral balances identity, explain what domestic and external adjustments would be required if the government's structural deficit widens significantly without offsetting private sector saving.
   → **Answer:** Sectoral balances identity: (S − I) + (T − G) + (M − X) = 0. If (T − G) deteriorates (government deficit widens) and private sector surplus (S − I) is unchanged, then (M − X) must increase — i.e., the current account deficit widens (more foreign borrowing). Alternatively, private saving could rise (e.g., precautionary saving in response to fiscal uncertainty), partially offsetting the government deficit without a larger external deficit. In practice, Australia already runs structural current account deficits, so wider government deficits would likely require increased foreign capital inflows, raising Australia's net foreign liability position and long-run debt servicing costs.

## Further Resources
- 📺 **[Fiscal Policy and Stimulus: Crash Course Economics #8](https://www.youtube.com/watch?v=otmgFQHbaDo)** — Crash Course (12 min)
- 📺 **[The 2008 Financial Crisis: Crash Course Economics #12](https://www.youtube.com/watch?v=GPOv72Awo68)** — Crash Course (12 min)
- 📚 **[RBA — The COVID-19 Pandemic and the Australian Economy](https://www.rba.gov.au/publications/annual-reports/rba/2020/australian-economy.html)** — Australia's COVID-19 fiscal response: JobKeeper, stimulus payments, and consolidation path
