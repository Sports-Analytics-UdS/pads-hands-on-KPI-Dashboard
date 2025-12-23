# KPI metrics——Dashboard Task (Exemplar)

This repository contains a team-level KPI metrics from all Big-Five league clubs for the 2024/25 season. Each observation represents the aggregated performance of a single team within one league and season. This dataset is made available through an official collaboration between Saarland University and Statsbomb.

ℹ️ Due to current technical issues encountered during making requests to _Statsbomb API_, only data from season 2024/25 is provided in the exemplar dataset.

ℹ️ A larger dataset containing five-season KPI data is expected to be uploaded by _9 January, 2025_.


## Contents
- [Technical Glossary](#technical-glossary)
- [Variables](#variables)
- [Data Source and Licensing](#data-source-and-licensing)
- [Intended Use ](#intended-use)
- [Citation](#citation)



---

## Technical Glossary

Statsbomb provides the [definition](https://classic.statsbomb.hudl.com/help/sbdata-glossary) of each metric included in this dataset (Statsbomb log-in credentials required).

---

## Variables

### Identifiers
- `Season` – Competition season (e.g. 2024/25)
- `League` – League name (Premier League, La Liga, Serie A, Bundesliga, Ligue 1)
- `Team` – Team name

### Match Exposure & Outcomes
- `Minutes` – Total minutes played
- `Goals` – Goals scored
- `Goals Conceded` – Goals conceded

### Expected Goals
- `xG` – Expected goals created
- `xG Faced` – Expected goals conceded
- `Cumulative xG` – Total accumulated xG
- `Open Play xG` – xG generated from open play

### Shooting & Attacking Activity
- `Shots`
- `Non Penalty Shots`
- `Shots Outside Box`
- `Touches in box`
- `Non Penalty Shots Faced`

### Passing & Possession
- `Passes`
- `Non Throw-in Key Passes`
- `Box Cross%`

### Set Pieces & Goalkeeping
- `Corners`
- `Goalkeeper Long Ball%`

---

## Data Source and Licensing

This dataset consists of **aggregated, derived team-level statistics**. It does **not** contain raw event data, tracking data, or proprietary identifiers.

---

## Intended Use

This dataset is used for teaching in Sports Analytics at Saarland University.
- Comparative league analysis
- Team performance profiling

Not intended for commercial redistribution of proprietary raw data.

---

## Citation

If you use this dataset for academic or teaching purposes, please cite the repository and state the data source as **StatsBomb**.

