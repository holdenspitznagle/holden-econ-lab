# How the trades paper gets made (process and resources)

*Set 2026-11-05. Nov–Jan: ~20% of research time. From the internship (spring):
main focus. Write over the summer.*

**Working question:** *Who owns Miami-Dade's HVAC market, and how fast is private
equity consolidating it?* (Q1, ownership and concentration, no prices.)
**Side piece:** the valuation gap from listings (Q3), as a section or a separate memo.

## The steps

| # | Step | What you actually do | When | Done when |
|---|---|---|---|---|
| 1 | **Read** | FTC/DOJ roll-up inquiry (2024); the Totter SSRN case study on HVAC PE (closest work, read first); 2023 Merger Guidelines on concentration (HHI); a few buy-and-build papers. One note each in `reading/` | Nov–Jan | You can say what's known nationally and what nobody has measured locally |
| 2 | **Listings log** | ~20 min a week into `listings.csv` | Nov onward | Months of listings nobody else saved |
| 3 | **Build the universe** | Download DBPR construction licensee files; keep air-conditioning contractor licenses in Miami-Dade | Jan | A list of every licensed HVAC contractor in the county |
| 4 | **Map ownership** | For each company: independent or part of a platform? Use deal trackers, platform press releases ("a portfolio company of…"), and Sunbiz (Florida corporate records: officers, addresses, name changes) | Feb–Mar | Each firm tagged independent / PE-backed, with acquisition date where known |
| 5 | **Define the market** | Choose the area unit (zip codes, county regions) and a size measure (permits, review counts, employees) | Feb–Mar | A defensible "market" and "size" you can explain in a paragraph |
| 6 | **Measure** | Share of firms PE-owned; concentration (HHI) by area; change over time using acquisition dates | Mar–Apr | The map and the one striking chart |
| 7 | **Valuation piece** | From listings: asking multiples by size, recurring revenue, owner dependence; compare with reported platform multiples | Apr | A table and a clear explanation of the gap |
| 8 | **Interviews** (internship) | Ask owners about exit plans, offers received, why sell or close. With permission; anonymize | Spring | 5–10 conversations, notes kept |
| 9 | **Write** | Paper (10–15 pages) + a 2-page strategy memo version for owners and PE (ends with recommendations) | Summer 2027 | Full draft |
| 10 | **Feedback and share** | IO or finance professor; post; share the map with owners; content | Summer–Fall | It's public |

**Hardest parts:** step 4 (platforms often keep local brand names, so ownership is
detective work), step 5 (what counts as a "market" is a judgment call a professor
will push on), and size (no public revenue data, so shares are approximate).

**Honest limits:** no price data, so the paper describes concentration rather than
proving harm; license counts and proxies are not revenue shares. Say so up front.

**Tools:** a spreadsheet is enough through step 4; Python or R for steps 5–6. Claude
can help with matching and code.

## Links

- **Florida DBPR construction licensee files:** https://www2.myfloridalicense.com/?p=11565
  (read the ReadMe and column list first; look for the Construction Industry
  Licensing Board certified and registered files)
- **Sunbiz** (Florida corporate records): https://search.sunbiz.org
- **Deal trackers:** Dealseam HVAC tracker https://dealseam.com/hvac-pe-rollup-tracker-2026 · PrivSource · Mergr
- **Listings:** BizBuySell, BizQuest
- **Miami-Dade permits:** check the county's open data portal for building permits

## Read first

- **Totter, "The U.S. HVAC Private-Equity Consolidation Cycle (2018–2026)," SSRN.**
  Closest existing work: a national case study of platforms and multiples, not local
  concentration. Your edge: a measured local market.
  https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6942519
- **FTC/DOJ request for information on serial acquisitions and roll-ups (May 2024):**
  https://search.ftc.gov/news-events/news/press-releases/2024/05/ftc-doj-seek-info-serial-acquisitions-roll-strategies-across-us-economy
- **ProMarket, "An explainer on how market concentration is measured" (HHI):**
  https://promarket.org/2024/06/24/an-explainer-on-how-market-concentration-is-measured/
- Context (Tier B, via WSJ citing PitchBook): PE bought nearly 800 HVAC, plumbing and
  electrical companies from 2022 to October 2024. Verify against the WSJ article before using.
- Treat industry blogs' price claims (e.g., "15–25% higher prices") as unverified.

## Videos

No strong verified videos found for this topic (HHI, roll-ups). Search YouTube for
"HHI antitrust merger calculation" and check the channel before trusting it. The
Angrist "Selection Bias" video still applies.
