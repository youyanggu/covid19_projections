---
layout: default
title: Path to Herd Immunity - COVID-19 Vaccine Projections
permalink: /path-to-herd-immunity/
---

# Path to ~~Herd Immunity~~ Normality : 2021 Outlook of COVID-19 in the US
By: [Youyang Gu](https://youyanggu.com)
<br>Last Updated: March 8, 2021 (*First posted December 9, 2020; CDC plots updated daily)*

With the availability of the COVID-19 vaccine, we present our best estimate of the path to COVID-19 herd immunity / normality in the United States. Immunity against the SARS-CoV-2 virus comes from two sources: vaccination and natural infection. On this page, we provide the latest COVID-19 vaccine projections and current vaccination progress.

**March 8 Update:** We have ended our daily updates for *covid19-projections.com* and hence are no longer be updating this page. Read Youyang's [One Year Later](https://youyanggu.com/blog/one-year-later) blog post for a detailed explanation and for a list of alternate resources. You can view the latest vaccination trends on the [CDC website](https://covid.cdc.gov/covid-data-tracker/#vaccination-trends). Thank you for your support over the past year.

**February 24 Update:** See our [latest thoughts](https://twitter.com/youyanggu/status/1364627872233750543) on when to expect a return to normal. [Older updates](#updates)
{% include_relative vaccination-last-updated.md %}
{% include iframe_vaccination.html %}
*Note:* Our infections estimates include all new infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. As of January 2021, we estimate the true number of infected individuals in the US to be roughly 2-4x higher than the reported cases (25-50% detection rate). See our writeup, [Estimating True Infections](/estimating-true-infections-revisited), for a more detailed look into this subject.

### We stopped updating CDC vaccination data on March 8. For the latest time series, visit the [CDC website](https://covid.cdc.gov/covid-data-tracker/#vaccination-trends). See our old plots through March 8 [here](/vaccination_cdc).

[Back to Top](#top)

## Table of Contents
* [Summary](#summary)
* [Relevant Twitter Threads](#relevant-twitter-threads)
* [Disclaimers](#disclaimers)
* [Data](#data)
* [Assumptions](#assumptions)
* [Corollaries](#corollaries)
* [Helpful Data Sources](#helpful-data-sources)
* [Questions? Comments? Feedback?](#questions-comments-feedback)

[Back to Top](#top)

## Summary
- Every adult who wants to get a vaccine will be able to get a vaccine by May/June 2021.
- The US will be near COVID-19 herd immunity by summer 2021 (Jun-Aug 2021). At a high level, [herd immunity](https://jamanetwork.com/journals/jama/fullarticle/2772168) is a concept in which a population can be protected from a virus if enough people possess immunity. Current accepted estimates for the herd immunity threshold range from [60-90%](https://www.nytimes.com/2020/12/24/health/herd-immunity-covid-coronavirus.html) of the population.
- Due to vaccine hesitancy and the later arrival of a children's vaccine, it is possible that we do not reach the levels required for herd immunity in 2021. Nevertheless, herd immunity is not a hard threshold, and being close to herd immunity may be sufficient to prevent large outbreaks.
- At the time herd immunity is near, roughly half of the immunity will be achieved through natural infection, and the other half will be achieved through vaccination.
- New infections may become minimal before herd immunity is reached. But due to imported cases and localized clusters, it is unlikely that new infections will drop to zero until at least 2022.
- Deaths may drop to low levels even earlier (May-Jul 2021), in part due to a vaccine distribution strategy that initially prioritizes high-risk individuals. Once deaths fall to minimal levels, we may see a relaxation of restrictions.
- Summarizing the above findings, our best estimate of a "return to normal" in the US is summer 2021 (June-August 2021). We define this as the removal of all restrictions for the majority of US states.
- We estimate roughly 60-70% of the US population (~220 million) will receive at least one dose of the vaccine by the end of 2021, with children being the last group to receive it (starting in summer 2021 or later).
- We estimate around 30-35% of the US population (100-120 million) will have been infected by the SARS-CoV-2 virus by the end of 2021. That is an additional ~50 million infections since mid-December 2020.
- This translates to a final US COVID-19 death toll of roughly 600,000 (±100,000) reported deaths by end of 2021, or ~300,000 additional deaths since mid-December 2020.

[Back to Top](#top)

## Relevant Twitter Threads
### News / Findings / Thoughts

- [Initial release](https://twitter.com/youyanggu/status/1337147909955964929) - Dec 10
- [Potential ways to speed up herd immunity](https://twitter.com/youyanggu/status/1337506967095369728) - Dec 11
- [Vaccine side effects](https://twitter.com/youyanggu/status/1338587017966284800) - Dec 14
- [Vaccine misinformation](https://twitter.com/youyanggu/status/1338952594492813312) - Dec 15
- [Vaccination rollout](https://twitter.com/youyanggu/status/1343675401436971008) - Dec 28
- [CDC data error](https://twitter.com/youyanggu/status/1349817775909269505) - Jan 14
- [State-by-state vaccination progress](https://twitter.com/youyanggu/status/1352720306108919809) - Jan 22
- [Over-emphasis on herd immunity](https://twitter.com/youyanggu/status/1359941463757516802) - Feb 11
- [Misconceptions around variants](https://twitter.com/youyanggu/status/1362476060907077636) - Feb 18
- [CDC methodology change](https://twitter.com/youyanggu/status/1363618681142575105) - Feb 21
- [NYT model unrealistic assumptions](https://twitter.com/youyanggu/status/1364274753851305984) - Feb 23
- [Return to normal by summer?](https://twitter.com/youyanggu/status/1364627872233750543) - Feb 24
- [Equitable vaccine distribution](https://twitter.com/youyanggu/status/1370067926703767553) - Mar 11

### Weekly Updates

- [Jan 11 Update](https://twitter.com/youyanggu/status/1348723790017007617) - Jan 11
- [Jan 20 Update](https://twitter.com/youyanggu/status/1352008093652066304) - Jan 20
- [Jan 27 Update](https://twitter.com/youyanggu/status/1354488024726290439) - Jan 27
- [Feb 3 Update](https://twitter.com/youyanggu/status/1357045475526991873) - Feb 3
- [Feb 10 Update](https://twitter.com/youyanggu/status/1359599383105466369) - Feb 10
- [Feb 16 Update](https://twitter.com/youyanggu/status/1361847534562467841) - Feb 16
- [Feb 25 Update](https://twitter.com/youyanggu/status/1365005143813537797) - Feb 25
- [Mar 3 Update](https://twitter.com/youyanggu/status/1367202710471249920) - Mar 3

[Back to Top](#top)

## Disclaimers

- The author is a data scientist and is not an epidemiologist, an immunologist, or a public health expert.
- This writeup has not been peer-reviewed in an academic journal.
- Only publicly available data are used.
- There is a very high amount of uncertainty with any model that makes outlooks for 6-12 months out. We fully acknowledge the possibility that these results may not reflect reality. The results presented here are merely estimates based on a set of assumptions (listed below), so please use caution when utilizing the results.
- For the majority of the assumptions, the exact numerical values have relatively minor impacts on the final results.
- If any of the assumptions used to generate these estimates do not hold, then the results may be drastically different.
- These are the best estimates given what is known at the time this was written, but are subject to change based on new data/evidence. For example, if vaccine rollout and uptake is quicker than estimated, then we may reach herd immunity sooner. If rollout and uptake is slower than estimated, we may reach herd immunity later.
- While we have estimates for when we expect a "return to normal", the ultimate decision to relax restrictions lies in the hands of the local, state, and federal governments. Therefore, it is likely that restrictions may be relaxed sooner or later than the estimates.
- From [*'Herd Immunity': A Rough Guide*](https://academic.oup.com/cid/article/52/7/911/299077): "[We must] be wary of target thresholds for vaccination, insofar as thresholds are based on assumptions that greatly simplify the complexity of actual populations. In most circumstances, the sensible public health practice is to aim for 100% coverage, with all the doses recommended, recognizing that 100% is never achievable, hoping to reach whatever is the 'real' herd immunity threshold in the population concerned."

[Back to Top](#top)

## Data

We use vaccination data from the [Centers for Disease Control and Prevention (CDC)](https://covid.cdc.gov/covid-data-tracker/#vaccinations). We upload the raw and adjusted CDC vaccination time series datafor download [on GitHub](https://github.com/youyanggu/covid19-cdc-vaccination-data). It contains every CDC vaccination update since they started releasing data on Dec 20, 2020 through March 7, 2021.

While we release daily [past infections estimates](https://github.com/youyanggu/covid19-infection-estimates-latest) for every state and county, we are currently not releasing our vaccination and infections forecasts. This is due to 1) the limitations and noisiness in the existing data 2) the high degree of uncertainty for the future and 3) the reliance on numerous assumptions (outlined below). As a result, we believe these projections are best suited to be viewed in the context of everything outlined on this page, and should best not be used independently. Without all the necessary context/assumptions, the results can easily be misinterpreted.

[Back to Top](#top)

## Assumptions

The underlying assumptions behind our estimates are presented below:

### Basic Assumptions

- **Important:** The only SARS-CoV-2 variant we are currently modeling is the B.1.1.7 variant that was first detected in the UK (see Jan 11 update [below](#updates)). If other variants become more prevalent in the US, these estimates may no longer hold. We are monitoring for more data regarding the other variants.
- We assume immunity can be achieved through either natural infection or vaccination. We assume this immunity can be lost over time.
- We assume herd immunity is near when at least 60-80% of the population possess immunity from the SARS-CoV-2 virus. This corresponds to roughly 200-260 million individuals in the US. Due to population heterogeneity, variation in susceptibility and/or pre-existing immunity, it is possible that the herd immunity threshold (HIT) can be lower. But HIT can also be higher due to a higher transmissibility of virus variants and the targeted approach of vaccine distribution (e.g. individuals with the greatest impact on transmission are vaccinated last).
- We assume states will continue to impose varying degrees of restrictions and interventions until hospitalizations and deaths drop to low levels. The exact thresholds will depend on each state.
- We define "normality" as the removal of all COVID-19-related restrictions and interventions.
- Herd immunity is not permanent. It can be lost due to waning immunity, both from infection and vaccination.
- For the purpose of estimating new infections, we do not differentiate between immunity acquired from infection and immunity acquired from vaccination.

[Back to Top](#top)

### Vaccination Assumptions

- We count an individual as vaccinated after they receive the first dose. We assume it takes three weeks after the first dose for an individual to gain immunity.
- Our initial model factors in the rollout of two vaccines: Pfizer and Moderna. In February, we began also factoring in the rollout of the single-dose Johnson & Johnson vaccine beginning in March. More vaccines may be approved in 2021 (e.g. AstraZeneca), but the exact timelines are still unclear. We will incorporate additional vaccines as more data becomes available.
- We assume a proportion of the vaccinated population already possesses immunity via infection. For simplicity, we assume individuals who already possess immunity from natural infection will get vaccinated at the same rate as susceptible individuals.
- We assume roughly 60-70% of the US population (~220 million) will take at least one dose of the vaccine by the end of 2021. This is based on [recent surveys](https://civiqs.com/results/coronavirus_vaccine). This is higher than the ~50% vaccine coverage for the common flu.
- We assume the majority of individuals (but not all) will receive the second dose.
- We assume the general population will begin receiving vaccinations in late spring (Apr-May 2021).
- We assume children will begin receiving vaccinations in summer or fall 2021. It is possible that a vaccine for the youngest age group (ages 0-5) will not be available in 2021.
- We assume a 85% vaccine efficacy (changed from 90% on Feb 4, 2021 and 85% on Jan 21, 2021). Hence, if 100 individuals are vaccinated, we assume 85 will develop immunity and 15 will not. While the trial data for Pfizer and Moderna demonstrate ~95% efficacy, we believe that the efficacy in the general population will be slightly lower, mainly due to the fact that a non-insignificant proportion of the population may miss the second vaccine dose. We are also workign to better incorporate the efficacy of the J&J vaccine, pending more data.
- We assume the vaccine is effective on the new B.1.17 SARS-CoV-2 variant (preliminary research [here](https://www.biorxiv.org/content/10.1101/2021.01.18.426984v1) and [here](https://www.biorxiv.org/content/10.1101/2021.01.15.426911v1)).
- We assume that if effective, the vaccine will provide individuals immunity through at least 2021.
- While it is still unclear to the extent to which the vaccine provides sterilizing immunity, we assume that the vaccine, if effective, can provide functional immunity for the individual and significantly reduce their likelihood of being infectious for at least the duration of 2021 (preliminary research from AstraZeneca [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3777268) and Pfizer [here](https://www.medrxiv.org/content/10.1101/2021.02.06.21251283v1) or [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3790399)).
- We assume vaccinations will begin in mid-December following the FDA Emergency Use Authorization (EUA) approval. Due to distribution issues, constraints with storage, and vaccine hesitancy, we believe the initial rollout will be slower than Operation Warp Speed's estimates of 20 million doses by end of 2020.
- Many of the assumptions in this writeup come from the [December 10 FDA Briefing Document](https://www.fda.gov/media/144245/download) for the Pfizer vaccine.
- We assume a smooth but conservative vaccine rollout, with no major issues or halts. If rollout and uptake is quicker than estimated, then we may reach herd immunity sooner. If rollout and uptake is slower than estimated, we may reach herd immunity later.
- We assume that at its peak, around 3 million doses will be given per day (enough for innoculate ~2 million people). This is roughly equal to the peak vaccine distribution for influenza (~3 million doses per day).

[Back to Top](#top)

### Infection Assumptions

- **Important:** The only SARS-CoV-2 variant we are currently modeling is the B.1.1.7 variant that was first detected in the UK (see Jan 11 update [below](#updates)). There is a high amount of uncertainty with our estimates that is not reflected in the chart. While we are showing our best estimate, is possible that true infections curve can be dramatically different (e.g. a fourth wave in March).. We are monitoring for more data regarding the other variants.
- We assume roughly 65 million people in the US (20% of the population) have already been infected by the time the first COVID-19 vaccine is authorized in mid-December 2020 (based on our latest [covid19-projections.com](/) model).
- At the start of the vaccine rollout in mid-December 2020, we assume ~99% of individuals who were previously infected still possess immunity. Over time, we assume a proportion of the infected population (~30%, increased from 10-20% on Feb 18) will lose their immunity by the end of 2021. The longer the time from infection, the higher the likelihood of immunity being lost. While it's still unclear if prior infection confers long-term immunity, recent research ([here](https://www.nejm.org/doi/full/10.1056/NEJMoa2034545?s=09) and [here](https://science.sciencemag.org/content/early/2021/01/06/science.abf4063)) indicates that short-term reinfections are rare.
- We assume that the infection rate will fall as the number of individuals who are inoculated/vaccinated increases.
- We assume new infections will undergo a steady decrease from mid-December 2020 to March 2021. We account for the possibility of another wave of infections in late winter/early spring (March/April) as virus variants become more predominant and states relax restrictions from the fall wave. This final wave may not happen if a quick vaccine rollout can dampen the effects.
- To simplify the modeling, we count an individual as "immune via infection" the moment they are infected with the virus. In reality, it takes roughly 2-3 weeks after infection to develop antibodies.
- We use a basic SEIR model to estimate infections over time. This incorporates a reduction in the susceptible pool of individuals (and hence a lower infection rate) as the number of immune individuals increases.
- We factor in seasonality to a small extent.
- We assume a small number of imported cases per day. Due to a combination of imported cases and community spread, we believe daily infections in the US will likely not reach zero in 2021, even if herd immunity is reached.

[Back to Top](#top)

## Corollaries

- Our estimates show that roughly one third of the US population (~110 million) will have been infected by the SARS-CoV-2 virus by the end of 2021. That is an additional ~50 million infections since mid-December 2020.
- A one third prevalence estimate translates to a final US COVID-19 death toll of roughly 500,000 to 700,000 reported deaths by end of 2021, with 600,000 deaths being the best estimate. Given a mid-December 2020 death toll of 300,000, that is an additional ~300,000 deaths. While reported deaths are useful, [excess deaths](https://www.cdc.gov/nchs/nvss/vsrr/covid19/excess_deaths.htm) may be a better metric for the true death toll.
- Due to the high prevalence, a targeted approach for vaccination that prioritizes individuals who are more likely to be susceptible may improve the time to reach herd immunity.
- Due to possible low vaccine acceptance/uptake and waning immunity from natural infection, it is possible that the US will not reach immunity levels above 70%. In most scenarios, even 50-70% immunity could be sufficient to prevent large outbreaks.
- Due to the seasonality of the virus, the herd immunity threshold may be higher in the winter. Furthermore, herd immunity can be lost due to waning immunity. Therefore, it is important that we continue to vaccinate individuals even after herd immunity has been reached.

[Back to Top](#top)

## Helpful Data Sources

Below you will find a list of helpful vaccination data sources and dashboards. While we do not directly use them in our modeling, we highly recommend giving them a look.

### Vaccine Rollout Tracker

- [Bloomberg](http://bloomberg.com/graphics/covid-vaccine-tracker-global-distribution)
- [Our World in Data](https://ourworldindata.org/covid-vaccinations)
- [New York Times](https://www.nytimes.com/interactive/2020/us/covid-19-vaccine-doses.html)

### Vaccine Development Tracker

- [New York Times](https://www.nytimes.com/interactive/2020/science/coronavirus-vaccine-tracker.html)
- [Milken Institute](https://www.covid-19vaccinetracker.org/)

## Questions? Comments? Feedback?

You can reach Youyang Gu via the [Contact](/contact) page.

[Back to Top](#top)

## Updates

* *February 21:* There appears to be a methodology change for how the CDC reports vaccinations. Some clarifications [via Bloomberg](https://www.bloomberg.com/news/live-blog/2021-01-21/methodology-and-analysis-for-the-covid-19-vaccine-tracker#60319089B2240006). 
* *February 11:* We changed the page title from "Path to Herd Immunity" to "Path to Normality". Our modeling suggests that it is increasingly unlikely that we will reach theoretical herd immunity in 2021. See [our latest thoughts](https://twitter.com/youyanggu/status/1359941463757516802) on why the recent attention to herd immunity is overblown, and why we should shift our focus away towards normality instead.
* *February 5:* We lowered our vaccine efficacy estimate from 90% to 85% to account for [new variants](https://www.bmj.com/content/372/bmj.n296) and a [lower efficacy](https://www.jnj.com/johnson-johnson-announces-single-shot-janssen-covid-19-vaccine-candidate-met-primary-endpoints-in-interim-analysis-of-its-phase-3-ensemble-trial) of the Johnson & Johnson vaccine. Due to vaccine hesitancy and the later arrival of a children vaccine, it is possible that we do not reach the levels required for herd immunity in 2021. Nevertheless, herd immunity does not have a hard threshold, and being close to herd immunity may be sufficient to prevent large outbreaks. We are actively working to incorporate the new variants into our modeling.
* *January 28:* We are releasing raw and adjusted CDC vaccination time series data for download [on GitHub](https://github.com/youyanggu/covid19-cdc-vaccination-data). It contains every CDC vaccination update since they started releasing data on Dec 20, 2020. They will be updated daily. In addition, we separated our Path to Herd Immunity plot into three categories: immunity from vaccination only, immunity from vaccination & past infection, and immunity from past infection only. Previously, we assigned immunity to the one that was acquired first (either prior infection or vaccination).
* *January 26:* We are factoring in rollout of the single-dose Johnson & Johnson vaccine starting in late February/early March. In the past week, over 1 million doses were administered per day. Given no unforeseen supply issue from Pfizer/Moderna, we now estimate that the general public can receive the vaccine by April, and over 60% of the US adult population will be fully vaccinated by June. We also estimate that over 200 million doses will be administered in the first 100 days of the new presidential administration, more than double the administratoin's original "100 million shots in 100 days" goal. Our timeline for a "return to normal" remains unchanged (June-August 2021).
* *January 14:* We separated CDC data for vaccine doses into 1st and 2nd doses. As complete data is not available, we applied interpolation and heuristics to fill in any missing data.
* *January 12:* We added vaccination plots to the infections page for every US state (and nationally) based on the latest [CDC data](https://covid.cdc.gov/covid-data-tracker/#vaccinations). For example, see the vaccination progress for [California](/infections/us-ca). To find another state, [click here](/#view-us-infections-estimates). See maps of the vaccination progress for all 50 states [here](/maps-infections).
* *January 11:* In response to the [new COVID-19 B.1.1.7 variant](https://www.nytimes.com/live/2021/01/01/world/covid-19-coronavirus-updates) (preliminary study [here](https://cmmid.github.io/topics/covid19/uk-novel-variant.html)), we increased our herd immunity threshold from 60%+ to 70%+. We have also increased our total infections estimates (30% -> 35-40%) and deaths estimates (500k -> 600k ±100k) in response to this new strain and a slower-than-expected vaccination rollout. We are in the process of gathering more data to better incorporate this variant into our modeling (e.g. [Jan 15 CDC modeling](https://www.cdc.gov/mmwr/volumes/70/wr/mm7003e2.htm)).
* *January 5:* We added a plot of daily US vaccinations based on [CDC data](https://covid.cdc.gov/covid-data-tracker/#vaccinations).
* *December 24:* We added a plot of the most up-to-date information on doses distributed and people vaccinated, based on [CDC data](https://covid.cdc.gov/covid-data-tracker/#vaccinations). To track global vaccination progress, see the [Bloomberg Vaccine Tracker](https://www.bloomberg.com/graphics/covid-vaccine-tracker-global-distribution/?srnd=premium).
