---
layout: page
title: Study - Sustainability in Open Source Projects
date: 2020-06-27 15:52
tags: software-sustainability
---

# Current status

To view the (entirely anonymous) aggregated stats/datavis/data exploration for the study, visit: [https://yochannah.github.io/sustainable-communities-tracker/](https://yochannah.github.io/sustainable-communities-tracker/)

The source code for the above analyses is here: [https://github.com/yochannah/sustainable-communities-tracker](https://github.com/yochannah/sustainable-communities-tracker)

Note that some of the pages have had to be removed as they would too easily reveal which github repos were participants. 

# History 

The thesis is in; preprint & publication will be forthcoming. The TL;DR of this study is: don't use GitHub metrics without context, as similar looking projects may have vastly different reasons for the same github metrics. 

## Update May 2023

Thesis due in one month. All hands on decks! 

## Update Nov 2022 

Data analysis in progress, survey dataset is pseudonymised and [deposited on Zenodo](https://doi.org/10.5281/zenodo.7347763). 

Still todo: 

- [x] Finalise Analyses
- [ ] Pseudonymise GitHub metrics
- [x] Write up (as a thesis chapter...)
- [ ] Deposit preprint
- [ ] Send to publisher (who?!)

## Update JUNE 2022: 

Final surveys have been sent out to participants (40 in total), and write-up/data analysis is in progress.

## Update NOV 2021: 

THIS SURVEY IS NOW CLOSED** Interested in participating? Please visit [this survey](https://www.qualtrics.manchester.ac.uk/jfe/form/SV_3xuFqrkbUcvQ9vg) for more info and to get started. It takes around 15 minutes to complete. Alternatively, you can download a PDF copy of the [participant information sheet](assets/PIS_sustainable_software.pdf) (the sheet is also shown in the survey if you are an eligible participant).

## About the study

Research software is often abandoned or shut down, for one reason or another. While some reasons may be straightforward, e.g. a sole maintainer has moved on, or grant funding has ceased - some projects are able to withstand these barriers and may remain active and maintained despite adversity.

I'm running a study where I plan to monitor open source projects over the period of a year, measuring common performance indicators, to see if any indicators are common to projects that remain sustainable and active.

During this period, I'll be doing the following:

1. Running an initial survey, where I gather info about the project age, leadership, and GitHub URLs. Participants will be asked to add [a short notice to their readme](readme_notice).
2. After the initial survey, I'll also gather information about the GitHub projects - this is info such as number of contributors, number of PRs, time taken to close/merge these PRs, and issues closed. Some of this info will be gathered using scripts, such as tools from [GrimoireLab](https://chaoss.github.io/grimoirelab/) and other parts will be gathered manually. An example of this is the Code of Conduct - while I can programmatically check for the _existence_ of CodeOfConduct.md, I can't easily check for enforcement contacts without manual checks.
3. 6 months [Nov/Dec 2021] and 12 months after the initial survey [May/June 2022], I'll send out a follow-up survey and run follow up GitHub checks, to see changes in projects over time.
