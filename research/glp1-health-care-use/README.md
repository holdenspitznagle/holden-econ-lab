# GLP-1s and health care use: do the drugs create demand for more care?

**Paper 1 (decided 2026-11-05; swapped ahead of the exercise paper).** Companion
piece: the GLP-1 economy memo (`../glp1-economy-memo/`).

**Why it went first:** Holden is more interested in it, and the data is free and
public, with no faculty signature needed.

## The question
When someone starts a GLP-1, do they see doctors more, get more lab tests and
fill more prescriptions? Or does weight loss eventually mean *less* care (fewer
visits for diabetes, blood pressure and joint pain)?

## The economics
- **Complements in medical care:** a GLP-1 needs a prescriber, check-ins, dose
  changes and blood work. Starting one may pull in more visits and tests at first.
- **Substitutes over time:** if weight and blood sugar improve, people may need
  fewer visits and other drugs later. Short run vs. long run may differ, which is
  the puzzle.
- **Grossman (1972):** medical care is one input into health; a new input changes
  demand for the others.
- **Why it matters:** insurers and employers deciding coverage weigh the drug's
  price against what it adds or saves in other care.

## Data: Medical Expenditure Panel Survey (MEPS), free and public
- **Who's in it:** a nationally representative US household survey. Each panel is
  followed for about two years, so people can be seen **before and after** they start.
- **Finding GLP-1 users:** the prescribed medicines file. Published work identifies
  them with Multum therapeutic class code 373 (incretin mimetics) (JMCP 2026).
- **Outcomes:** office-based visits file, lab and other event files, spending in the
  full-year file.
- **Years:** 2024 full-year file released Aug 2026; 2024 office visits June 2026;
  the 2024 prescribed medicines file usually comes in October (confirm it's out).
- **Easier access:** IPUMS MEPS (https://meps.ipums.org), free account.
- **Scale check:** about 6.07 million US people were prescribed GLP-1s in 2022 in
  MEPS (Hooper 2025, Pharmacotherapy). Survey counts of *new starters in the same
  panel* will be much smaller. **That number decides the design** (Dec 1 checkpoint).

## What already exists (and the gap)
- Utilization and cost studies using MEPS, mostly adults with type 2 diabetes and
  mostly one-year snapshots (PMC12467763; JMCP 2026). One notes it can't separate
  new from existing users.
- **The gap:** following **new starters** before vs. after, including weight-loss
  users, compared with similar non-starters. Needs a proper literature check first.

## Method sketch
Same people before vs. after starting, vs. similar people who never start
(difference-in-differences / event study) within MEPS panels. Splits: diabetes vs.
weight loss (where identifiable), insurance type, age.

## Limits
- Small numbers of new starters per panel; pooling panels may be needed.
- Self-reported events; 2020 office visits under-reported in one round (AHRQ note).
- People start drugs when health changes, so "linked to," not "caused by."

## Next steps
1. Create an IPUMS MEPS account; confirm the 2024 prescribed medicines file is out.
2. Literature check: Google Scholar for MEPS + GLP-1 + utilization.
3. Count new GLP-1 starters per panel (the go / no-go number).

## Sources
- Hooper 2025: https://accpjournals.onlinelibrary.wiley.com/doi/10.1002/phar.70007?af=R
- JMCP 2026: https://www.jmcp.org/doi/10.18553/jmcp.2026.32.2.166
- PMC12467763: https://pmc.ncbi.nlm.nih.gov/articles/PMC12467763/
- IPUMS MEPS record notes: https://meps.ipums.org/meps/userNotes_conditioneventpmed.shtml
- 2024 full-year file (HC-256): https://meps.ahrq.gov/mepsweb/data_stats/download_data_files_detail.jsp?cboPufNumber=HC-256
