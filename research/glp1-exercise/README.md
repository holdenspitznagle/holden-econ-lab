# GLP-1 drugs and exercise: substitutes or complements?

**Puzzle:** a 2026 study of 1,950 adults with fitness-tracker data (ENDO 2026)
found steps fell from 5,047 to 4,487 a day after starting a GLP-1, while industry
surveys say users spend more on fitness. Do the drugs replace exercise or make it
easier? Economists have studied GLP-1s and jobs, groceries and mental health,
apparently not exercise (needs a proper literature check).

## Data: Understanding America Study (checked 2026-10-26)

**Access**
- Free for research. Register at https://uasdata.usc.edu/page/Create+new+account
  with a school email (not Gmail), then return a data user agreement.
- **Students must name an advisor, professor or mentor who signs** to guarantee
  safe data handling. UAS checks with them before approving. Reply in about 3
  business days.
- Collaborators each need their own account.
- Restricted files (location, occupation codes, Medicare links) sit in a
  separate enclave that needs IRB approval, a CV and an institutional signature.
  Probably not needed for this question.
- No-login preview: the UAS Interactive Data Explorer.
- Note: the registration page says the repository is "under review for potential
  modification in compliance with Administration directives." Access terms may change.

**What's in it** (Tier B, from the preprint at
https://sciety.org/articles/activity/10.64898/2026.08.28.26361368, data statement
on medRxiv: "available online at uasdata.usc.edu for research purposes upon
signing a Data Use Agreement")
- Three GLP-1/GIP waves: March 2024, December 2024, October 2025.
- 9,150 respondents in at least one wave; 1,274 current or former users.
- Use status, main reason (diabetes, weight loss, other), and where they got it
  (about 1 in 3 through compounding, online or foreign pharmacies).
- Weighted use rose from 8.2% (Mar 2024) to 12.0% (Oct 2025).
- Smartwatch measures: resting heart rate, HRV, max activity heart rate, steps,
  sleep.

**Unknowns to resolve**
- [ ] Are the smartwatch files in the standard download, or restricted?
- [ ] How many smartwatch users are also GLP-1 users? (Could be small.)
- [ ] Does UAS have self-reported exercise questions in nearby waves?
- [ ] Literature check: has anyone already done GLP-1s and exercise?

## Why a faculty signature?
UAS gives data only to accounts with someone accountable behind them. A student
isn't an employee, so a faculty member vouches for safe handling. It is a
signature, not a promise to advise. Any professor at the school can sign.

Draft ask: *"I'm writing an independent paper using a free USC survey dataset.
Students need a faculty member to sign the data agreement confirming I'll handle
it safely. Would you be willing?"*

## The economics (set 2026-11-04)

**Question:** are GLP-1s and exercise substitutes (the drug replaces exercise) or
complements (the drug makes exercise easier)? Theory allows both, so it's an
empirical question. Working title: *Pills or Push-ups?*

**Framework:** Grossman (1972). Health is a stock built with inputs: medical care,
own time (exercise), diet. A GLP-1 is a new input. How does it change use of the others?

**Substitutes, why activity might fall**
- Lower payoff to exercise when the drug delivers weight loss (offsetting
  behavior; Peltzman 1975 on seatbelts).
- Precedent: statin users gained weight and ate more (Kaestner, Darden & Lakdawalla
  2014; Sugiyama et al. 2014).
- Early data: steps fell from 5,047 to 4,487 a day after starting (ENDO 2026,
  conference abstract, not peer-reviewed).

**Complements, why activity might rise**
- Weight loss lowers the cost of moving (less pain, fatigue, self-consciousness).
- Hypothesis (untested): the drug works like a commitment device for eating,
  freeing effort for exercise.
- Visible progress builds momentum.
- Doctors push strength training to protect muscle.

**Identification**
- Problem: selection. Starters are heavier, sicker, or just got bad news.
- Design: same people over time. Activity before vs. after starting, compared with
  never-users over the same months (difference-in-differences / event study) across
  the Mar 2024, Dec 2024, Oct 2025 waves.
- Threats: starting right after a health dip; seasonality; people who stop the drug.
- Language: mostly "linked to."

**Heterogeneity (where it gets interesting)**
- Reason for use: diabetes vs. weight loss.
- Access: prescription vs. compounding or online (about 1 in 3).
- Prior habits: exercisers vs. non-exercisers (cf. Charness & Gneezy 2009).

**So what:** insurer and employer coverage decisions (if substitutes, pair the drug
with exercise programs); muscle loss risk; a repeatable one-line finding.

**What could sink it:** too few GLP-1 users with smartwatch data; no activity
measures for non-users in the same waves.

## Next step
1. Browse the UAS Interactive Data Explorer (no login) for GLP-1 and activity items.
2. Ask a professor to sign; register with a school email.
3. First data check: how many GLP-1 users have smartwatch data.
