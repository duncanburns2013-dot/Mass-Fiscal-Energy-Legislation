# 🚨 H.5151 EXPOSED — The $9 Billion Illusion

**Interactive dashboard analyzing Massachusetts House Bill H.5151 (Energy Affordability Act)**

🔗 **Live Dashboard:** [duncanburns2013-dot.github.io/Mass-Fiscal-Energy-Legislation](https://duncanburns2013-dot.github.io/Mass-Fiscal-Energy-Legislation/)

---

## What Is This?

On February 24, 2026, the MA House Ways & Means Committee dropped an 85-section energy bill claiming "$9 billion in savings over 10 years." Representatives got **24 hours** to read it and file amendments. Full House vote in **48 hours**.

We read every section. The math doesn't add up.

---

## Key Findings

**The $9B claim is fantasy math.** $9B ÷ 2.9M households ÷ 10 years = $310/yr per home. Realistic near-term relief: **~$150/yr**. That closes just **15%** of the gap between MA and the US average.

**MA electricity: 79% above the national average.** EIA data (December 2025): Massachusetts residential rate is 30.88¢/kWh vs. the US average of 17.24¢/kWh. Your monthly bill at 600 kWh: **$185** vs. the national average of **$103**.

**They cut branches but fertilized the root.** Mass Save trimmed $1B. ACP rebates return 70% temporarily. But the 2030/2050 climate mandates driving $377/yr in policy charges? Untouched. New 10 GW offshore wind and 10 GW solar mandates? Added.

**24 hours to read 85 sections.** Healey's original bill was 45 sections with 90 days for amendments and 6 hours of public hearings. H.5151 is 89% larger with 99% less review time.

---

## Data Sources

| Source | What | Date |
|--------|------|------|
| [EIA Electric Power Monthly, Table 5.6.A](https://www.eia.gov/electricity/monthly/epm_table_5_6_a.html) | State residential rates | December 2025 |
| [H.5151 Full Bill Text](https://malegislature.gov/Bills/194/H5151) | All 85 sections | February 2026 |
| Eversource Verified Bill | Rate component breakdown (Supply/Distribution/Policy/Transmission) | 2025 |
| [CommonWealth Beacon](https://commonwealthbeacon.org) | Michlewitz quotes, legislative timeline | February 2026 |
| [US Census / ACS](https://data.census.gov) | ~2.9M MA households | 2024 |

---

## What's In The Dashboard

| Tab | Content |
|-----|---------|
| **01 — The Math** | $982/yr overpayment vs. $310 claim vs. $150 reality. Savings breakdown by provision. |
| **02 — Cut vs Kept** | Side-by-side: what they trimmed (~$150/yr) vs. what they kept + added ($377+/yr in mandates). |
| **03 — Speed Run** | 85 sections, 24hr amendments, 48hr vote vs. Healey's 90-day process. What's buried inside. |
| **04 — Your Bill** | Current $185/mo → $173/mo after. Still 68% above the US average. New future costs itemized. |

---

## Verified Bill Provisions (Section References)

- **Mass Save budget cut** — $1B from $4.5B → Section 69
- **ACP rebates 70% returned** — Temporary, 3-year sunset → Section 7
- **Net metering reform** — $380M/10yr, new large facilities only → Section 7
- **10 GW offshore wind by 2040** — EXPANDED from current targets → Section 22c
- **10 GW solar by 2040** — NEW mandate → Section 22c
- **Division of Clean Energy Procurement** — New state bureaucracy → Section 22a
- **Central Procurement Fund** — Tariff-funded, 30-year contract authority → Section 22a
- **Supplier bond requirements** — $5M surety bonds → Section 22
- **Penalty structure** — $100K per violation, $10M cap → Section 24
- **2030/2050 climate mandates** — UNTOUCHED

---

## Related Repositories

- [Mass-Energy-Exposed](https://github.com/duncanburns2013-dot/Mass-Energy-Exposed) — MA electricity rate analysis vs. national average
- [MA-Energy-Exposed-Dashboard](https://github.com/duncanburns2013-dot/MA-Energy-Exposed-Dashboard) — Interactive rate comparison dashboard
- [MA-Energy-Policy-exposed](https://github.com/duncanburns2013-dot/MA-Energy-Policy-exposed) — Policy mandate cost analysis

---

## Deploy

This is a single-file static site. Enable GitHub Pages:

1. **Settings** → **Pages** → **Deploy from branch** → `main` → `/ (root)`
2. Live at: `https://duncanburns2013-dot.github.io/Mass-Fiscal-Energy-Legislation/`

---

## Author

**[@DuncanBurnsMA](https://x.com/DuncanBurnsMA)** · Haverhill, MA

**#mapoli** · **#energycosts** · **#h5151**

---

*Built with Chart.js. No frameworks. No dependencies. One HTML file. Read the bill yourself — you have 24 hours. That's the point.*
