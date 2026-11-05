# How this paper gets made (process and resources)

*Set 2026-11-05. Roughly 5–8 hours a week, Nov–Feb.*

## The steps

| # | Step | What you actually do | When | Done when |
|---|---|---|---|---|
| 1 | **Access** | Professor signs; register for UAS; download NHIS 2024 as backup | Nov | You can open the data |
| 2 | **Read the literature** | 8–12 papers: ENDO 2026, GLP-1 economics papers (NBER), statin offsetting papers, Grossman. One note per paper in `reading/` | Nov–Dec | You can say in 3 sentences what's known and what isn't |
| 3 | **Explore the data** | Read the codebook; find GLP-1, activity and smartwatch variables; count users with activity data | Nov–Dec | **The sample-size answer** (decides go / no-go, Dec 1 checkpoint) |
| 4 | **Clean and build** | Merge the three waves; define who started, who never did; build the activity measure | Dec | One tidy file, one row per person per wave |
| 5 | **Describe** | Averages for starters vs. never-users, before and after. The one striking chart | Dec | A chart you could post |
| 6 | **Main analysis** | Difference-in-differences / event study; then splits (reason for use, access channel, prior habits) | Dec–Jan | A results table you can explain in one sentence |
| 7 | **Check it** | Robustness: different activity measures, drop people who stopped, seasonality | Jan | The result survives |
| 8 | **Write** | Abstract, intro, what's known, data, method, results, limits, conclusion. 10–15 pages | Jan | Full draft |
| 9 | **Feedback** | Send to the professor; revise | Jan–Feb | Second draft |
| 10 | **Share** | Post the working paper; content; email cited authors; FIU conference | Feb–Apr | It's public |

Hardest parts for a first paper: step 3 (codebooks are long), step 4 (merging waves
is where most errors happen), step 6 (learning the method). Writing is easier than
expected once results exist.

**Tools:** R or Python (free) or Stata (check whether FIU provides it). Claude can
help write and debug the code; you need to understand every line.

## Data links

- **NHIS 2024:** https://www.cdc.gov/nchs/nhis/documentation/2024-nhis.html
  (questionnaires, documentation, files). Easier version: IPUMS NHIS, https://nhis.ipums.org
  (free account). 2025 files also out: https://www.cdc.gov/nchs/blog/posts/2026/09/new-2025-national-health-interview-survey-public-use-files.html
- **All of Us:** https://www.researchallofus.org · register: https://www.researchallofus.org/register/
  · check whether FIU has signed the agreement on the Registered Institutions page
  (linked from the register page). Public data can be browsed without registering.
- **UAS:** https://uasdata.usc.edu/page/Create+new+account

## Learn the method (videos)

- **Mastering Econometrics with Josh Angrist** (Marginal Revolution University, MIT
  Nobel laureate): https://learn.mru.org/courses/mastering-econometrics
  Watch in order: The Path from Cause to Effect → Ceteris Paribus → Selection Bias →
  Introduction to Randomized Trials → How to Read Economics Research Papers →
  **Introduction to Differences-in-Differences**
  (https://mru.org/courses/mastering-econometrics/introduction-differences-differences).
  Bonus: "If I Master Econometrics, What Jobs Can I Get?"

## Learn the process (short reads; better than the videos found)

- Pischke, "How to get started on research in economics?" (LSE, a few pages):
  https://econ.lse.ac.uk/staff/spischke/phds/How%20to%20start.pdf
- Mascarenhas & Crouter, guide to economics term papers (written for undergrads):
  https://www.whitman.edu/documents/academics/majors/economics/Crouter/Mascarenhas%20and%20Crouter,%20Guide%20to%20Writing%20Economics%20Term%20Papers.pdf
- Bellemare, "How to Write Applied Papers in Economics" (longer; use when writing):
  https://marcfbellemare.com/wordpress/wp-content/uploads/2020/09/BellemareHowToPaperSeptember2020.pdf
