# How the trades paper gets made (process and resources)

*Reshaped 2026-11-05. Nov–Jan: ~20% of research time. Spring: main focus. Write
over the summer.*

**Working title:** *What Is a Trades Business Worth? Recurring Revenue, Owner
Dependence and the Exit Gap*

## The steps

| # | Step | What you actually do | When | Done when |
|---|---|---|---|---|
| 1 | **Read** | Totter (SSRN, HVAC PE cycle); FTC/DOJ roll-up inquiry; small-business valuation basics (earnings multiples, seller's discretionary earnings); owner-exit reports | Nov–Jan | You can explain how small businesses are priced and why platforms pay more |
| 2 | **Collect listings** | ~20 min a week, national, HVAC/plumbing/electrical, into `listings.csv` | Nov–Apr | **300+ listings** (enough to compare groups) |
| 3 | **Code the features** | From each description: recurring revenue or service agreements? Owner works in the field or manages? Years, employees, commercial vs. residential, trade, region | Ongoing | Every listing has the same fields filled |
| 4 | **Describe** | Median asking multiple overall and by group | Feb–Mar | **The one striking chart:** multiples by recurring revenue and owner dependence |
| 5 | **Analyze** | Regression: asking multiple on features (size, recurring revenue, owner role, trade, region) | Mar–Apr | A table you can explain in one sentence |
| 6 | **The gap** | Compare typical listing multiples with reported platform multiples; estimate the value a typical shop leaves on the table | Apr | A number people can repeat |
| 7 | **Check** | Drop outliers; size groups; trades separately; listings that later disappear vs. linger (a rough sign of selling) | Apr–May | Results hold |
| 8 | **Write** | Paper (10–15 pages) + a 2-page owner memo: "What raises what your trades business is worth" | Summer 2027 | Full draft |
| 9 | **Build the hook** | Optional: a simple online "what drives your business's value" tool from the results | Summer | Something owners can use |
| 10 | **Feedback and share** | Finance or entrepreneurship professor; post the paper; memo to owners, brokers, PE; content | Summer–Fall | It's public |

**Hardest parts:** step 3 (listing descriptions are messy and inconsistent, so you
need clear rules for coding "recurring revenue" and "owner dependence"), and
getting enough listings with real financials.

**Tools:** spreadsheet through step 4; Python or R for step 5. Claude can help
code features from descriptions and write the analysis; check its work by hand.

## Links and reading
- **Totter, "The U.S. HVAC Private-Equity Consolidation Cycle (2018–2026)," SSRN:**
  https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6942519
- **FTC/DOJ request for information on serial acquisitions (May 2024):**
  https://search.ftc.gov/news-events/news/press-releases/2024/05/ftc-doj-seek-info-serial-acquisitions-roll-strategies-across-us-economy
- **Dealseam HVAC PE tracker (platform deals):** https://dealseam.com/hvac-pe-rollup-tracker-2026
- Listings: BizBuySell, BizQuest (check terms of use).
- Treat industry blogs' numbers as unverified until checked (`CLAUDE.md` §8).
