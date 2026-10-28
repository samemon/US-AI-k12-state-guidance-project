# RQ2 — State characteristics and guidance priorities

**Research question.** Are state characteristics of demographics (e.g., percentage of
rural populations, English language learners), fiscal and infrastructural capacities
(e.g., broadband access, state education funding), and political leanings indicative of
patterns in state priorities identified in the guidance documents?

## Covariates
- **Demographics** — e.g., rural population share, English language learners (ELL),
  American Indian/Alaska Native share, students with disabilities (IEP).
- **Fiscal / infrastructural capacity** — e.g., broadband access, free/reduced-price
  lunch (FRL) share, per-pupil education spending.
- **Political leaning** — Democratic share of state legislative seats.

## Approach
Each covariate is split at its median; guidance-priority dimensions (coded in RQ1) are
compared across the two groups with Mann–Whitney U tests, reporting group medians and
p-values (effect sizes via rank-biserial correlation). Hypotheses are grouped into
pre-specified families (demographics, capacity, partisan).

## Contents
_(to be added)_
- `data/` — covariate tables (Census ACS, Ballotpedia, F-33 finance) or pointers to `../../data/`.
- notebooks / scripts — per-family tests and figures.

## Reproduce
_(to be added: environment, data sources with years, run order)_
