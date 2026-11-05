# Research agenda: GLP-1s and health behavior

*Set 2026-11-04. A map of related projects, not a plan to do them all at once.
One paper, one question.*

## The umbrella

**How a drug that replaces part of a health behavior reshapes everything around it.**

GLP-1 drugs change demand for the goods and services that go with health, as
**substitutes** (less of it) or **complements** (more of it). Every project below
asks that question about one thing.

## The projects

| # | Project | Substitute or complement? | Format | Data | Status |
|---|---|---|---|---|---|
| 1 | **GLP-1s and health care use** (doctor visits, blood tests) | Complement at first; maybe substitute later | **Paper 1** | Medical Expenditure Panel Survey (free, public) | **Active (swapped 2026-11-05).** `glp1-health-care-use/` |
| 2 | **GLP-1s and exercise** | Unknown, which is the puzzle | Paper 2 / backup | Understanding America Study (faculty signature) | On hold. `glp1-exercise/` |
| 3 | **Muscle and bone loss** | The cost if exercise falls | "Why it matters" in paper 1; content | Clinical literature | Use in paper 1 intro |
| 4 | **The GLP-1 economy: protein supplements** | Complement: eating less, needing protein | **Companion memo to paper 1** | Earnings calls, Google Trends, product launches, Cornell study | Planned. `glp1-economy-memo/` |
| 5 | **The new blood-test market** | Complement | Memo or content | Company reports, industry news | Idea |
| 6 | **Where the average person's health is headed** | All of the above | Essay | Built from 1–5 | After papers 1 and 2 |

## Exercise vs. health care use (set 2026-11-05; order swapped the same day: health care use is now paper 1)

| | **Paper 1: exercise** | **Paper 2: health care use** |
|---|---|---|
| Question | Do GLP-1 users exercise less or more? | Do GLP-1 users see doctors and get lab tests more? |
| Economics idea | Substitutes vs. complements in **personal behavior** (Grossman, offsetting behavior) | Complements in **medical care**: does a drug create demand for monitoring and follow-ups? |
| Outcome | Steps, activity minutes, self-reported exercise | Office visits, lab tests, prescriptions, spending |
| Main data | Understanding America Study (faculty signature) | Medical Expenditure Panel Survey (free, public). Check: how far files lag; whether drug names are detailed enough. Also check whether UAS asks about doctor visits |
| Method | Same people before vs. after starting, vs. never-users | Same idea; MEPS follows people for about two years |
| Audience | Gyms, fitness, insurers, employers, the public | Insurers, health systems, policymakers, health tech, lab-testing companies |
| Professor type | Health or behavioral economist | Health economist (health care use and costs) |
| When | Nov 2026 – spring 2027 (FIU) | Fall 2027 onward (new school); possible honors thesis |

**Keep them separate:** paper 1 doesn't study doctor visits; paper 2 doesn't study
exercise. Each has one question and one main dataset.

**How they connect:** paper 1 asks how people change; paper 2 asks how the health
system responds. Together: "GLP-1s change behavior and health care use." Paper 1
builds the skills (data cleaning, before/after design) that paper 2 reuses, so
paper 2 goes faster.

## Notes on each

**1. Exercise.** The core paper. Full breakdown in `glp1-exercise/README.md`.

**2. Health care use.** Do people who start a GLP-1 see doctors and get lab tests
more often? The Medical Expenditure Panel Survey is free and lists prescribed
drugs, office visits and spending. **To check:** how far the files lag (usually a
year or two) and whether drug names are detailed enough in recent years.

**3. Muscle and bone loss.** A medical question; economists can't measure bone
density here. Its job is to make paper 1 matter: *"If GLP-1s replace exercise, the
cost may show up later as weaker muscles and bones."* Source each clinical claim
before using it (`CLAUDE.md` §8).

**4. Protein supplements.** Store purchase data (e.g., NielsenIQ) is mostly behind
paywalls, so this fits the applied-strategy pillar better than research: "Are
GLP-1s good for protein brands?" Economists have already studied GLP-1s and grocery
spending; cite and build on it. Prices: expect new products and demand shifts more
than big price moves in a competitive market. That's a hypothesis to check.

**5. Blood tests.** Direct-to-consumer testing is growing, but separating the GLP-1
effect from wellness trends is hard. Good business story, weak causal question.

**6. The big essay.** A forecast, not a testable question. It's the conclusion of
the agenda, written once there are results to stand on.

## Content episodes this feeds

- "Your weight-loss shot might cost you muscle"
- "Why protein brands love Ozempic"
- "The pill-as-permission problem" (statins, seatbelts, GLP-1s)
- "Pills or push-ups?" (paper 1's finding)

## Why this shape

A clear specialty, *the economics of GLP-1s and health behavior*, is easier for
professors and employers to remember than five unrelated projects. Each piece feeds
the next: paper 1's result becomes content, paper 2 extends it, the memo turns it
into strategy, and the essay ties it together.
