---
layout: default
title: Path to Herd Immunity - COVID-19 Vaccine Projections
permalink: /path-to-herd-immunity/
---

# Path to Herd Immunity: 2021 Outlook of COVID-19 in the US
By: [Youyang Gu](https://youyanggu.com)
<br>December 9, 2020 *(Last Updated: January 14, 2021; CDC plots updated every weekday)*

**January 14 Update:** We decoupled CDC's data for "Doses Administered" into 1st and 2nd doses.

**January 12 Update:** We added vaccination plots to the infections page for every US state (and nationally) based on the latest [CDC data](https://covid.cdc.gov/covid-data-tracker/#vaccinations). For example, see the vaccination progress for [California](/infections/us-ca). To find another state, [click here](/#view-us-infections-estimates). See a map of the vaccination progress for all 50 states [here](/maps-infections).

*January 11 Update:* In response to the [new COVID-19 variant](https://www.nytimes.com/live/2021/01/01/world/covid-19-coronavirus-updates) (preliminary study [here](https://cmmid.github.io/topics/covid19/uk-novel-variant.html)), we increased our herd immunity threshold from 60%+ to 70%+. We have also increased our total infections estimates (30% -> 35-40%) and deaths estimates (500k -> 600k ±100k) in response to this new strain and a slower-than-expected vaccination rollout. We are in the process of gathering more data to better incorporate this strain into our modeling.

*January 5 Update:* We added a plot of daily US vaccinations based on [CDC data](https://covid.cdc.gov/covid-data-tracker/#vaccinations) (see below).

*December 24 Update:* We added a plot of the most up-to-date information on doses distributed and people vaccinated, based on [CDC data](https://covid.cdc.gov/covid-data-tracker/#vaccinations) (scroll down to see). To track global vaccination progress, see the [Bloomberg Vaccine Tracker](https://www.bloomberg.com/graphics/covid-vaccine-tracker-global-distribution/?srnd=premium).

With the availability of the COVID-19 vaccine, we present our best estimate of the path to COVID-19 herd immunity in the United States. Herd immunity will be reached through immunity from two sources: vaccination and natural infection. On this page, we provide the latest COVID-19 vaccine projections.

## Table of Contents
* [Summary](#summary)
* [Relevant Twitter Threads](#relevant-twitter-threads)
* [Disclaimers](#disclaimers)
* [Assumptions](#assumptions)
* [Corollaries](#corollaries)
* [Questions? Comments? Feedback?](#questions-comments-feedback)
{% include iframe_vaccination.html %}
*Note:* Our infections estimates include all new infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. As of January 2021, we estimate the true number of infected individuals in the US to be roughly 2-4x higher than the reported cases (25-50% detection rate). See our writeup, [Estimating True Infections](/estimating-true-infections-revisited), for a more detailed look into this subject.

[Back to Top](#top)

## Summary
- We estimate COVID-19 herd immunity (>70% of population immune) will be reached in the US during summer 2021 (Jun-Aug 2021). At a high level, [herd immunity](https://jamanetwork.com/journals/jama/fullarticle/2772168) is a concept in which a population can be protected from a virus if enough people possess immunity.
- At the time herd immunity is reached, roughly half of the immunity will be achieved through natural infection, and the other half will be achieved through vaccination.
- New infections may become minimal before herd immunity is reached. But due to imported cases and localized clusters, it is unlikely that new infections will drop to zero until at least 2022.
- Deaths may drop to low levels even earlier (May-Jul 2021), in part due to a vaccine distribution strategy that initially prioritizes high-risk individuals. Once deaths fall to minimal levels, we may see a relaxation of restrictions.
- Summarizing the above findings, our best estimate of a complete "return to normal" in the US is mid-summer 2021 (June/July 2021).
- We estimate roughly 80-85% of the US population (~275 million) will receive at least one dose of the vaccine by the end of 2021, with children and adolescents being the last group to receive it (late summer to fall 2021).
- We estimate around 35-40% of the US population (~125 million) will have been infected by the SARS-CoV-2 virus by the end of 2021. That is an additional 60 million infections since mid-December 2020.
- This translates to a final US COVID-19 death toll of roughly 600,000 (±100,000) reported deaths, or ~300,000 additional deaths since mid-December 2020.

[Back to Top](#top)

## Relevant Twitter Threads
- [Initial release](https://twitter.com/youyanggu/status/1337147909955964929) - Dec 10
- [Potential ways to speed up herd immunity](https://twitter.com/youyanggu/status/1337506967095369728) - Dec 11
- [Vaccine side effects](https://twitter.com/youyanggu/status/1338587017966284800) - Dec 14
- [Vaccine misinformation](https://twitter.com/youyanggu/status/1338952594492813312) - Dec 15
- [Vaccination rollout](https://twitter.com/youyanggu/status/1343675401436971008) - Dec 28
- [Jan 11 Update](https://twitter.com/youyanggu/status/1348723790017007617) - Jan 11

[Back to Top](#top)

## Disclaimers

- The author is a data scientist and is not an epidemiologist, an immunologist, or a public health expert.
- This writeup has not been peer-reviewed in an academic journal.
- Only publicly available data are used.
- There is a very high amount of uncertainty with any model that makes outlooks for 6-12 months out. We fully acknowledge the possibility that these results may not reflect reality. The results presented here are merely estimates based on a set of assumptions (listed below), so please use caution when utilizing the results.
- For the majority of the assumptions, the exact numerical values have relatively minor impacts on the final results (e.g. changing vaccine efficacy from 85% to 90% results in a 10-day shift in when herd immunity is reached).
- If any of the assumptions used to generate these estimates do not hold, then the results may be drastically different.
- These are the best estimates given what is known in mid-December 2020, but are subject to change based on new data/evidence. For example, if vaccine rollout and uptake is quicker than estimated, then we may reach herd immunity sooner. If rollout and uptake is slower than estimated, we may reach herd immunity later.
- From [*'Herd Immunity': A Rough Guide*](https://academic.oup.com/cid/article/52/7/911/299077): "[We must] be wary of target thresholds for vaccination, insofar as thresholds are based on assumptions that greatly simplify the complexity of actual populations. In most circumstances, the sensible public health practice is to aim for 100% coverage, with all the doses recommended, recognizing that 100% is never achievable, hoping to reach whatever is the 'real' herd immunity threshold in the population concerned."

[Back to Top](#top)

## Assumptions

The underlying assumptions behind our estimates are presented below:

### Basic Assumptions

- We assume immunity can be achieved through either natural infection or vaccination. We assume this immunity can be lost over time.
- We assume herd immunity is achieved when at least 70% of the population possess immunity from the SARS-CoV-2 virus (HIT = 70%). This corresponds to 230 million individuals in the US. Due to population heterogeneity, variation in susceptibility and/or pre-existing immunity, it is possible that the herd immunity threshold (HIT) can be lower. But HIT can also be higher due to the targeted approach of vaccine distribution (e.g. individuals with the greatest impact on transmission are vaccinated last).
- **Important:** We only count the immunity that was acquired first (e.g. if an individual has both immunity from natural infection and immunity from vaccination, we only count the immunity from infection).
- We assume states will continue to impose varying degrees of restrictions and interventions until herd immunity is reached.
- We define "normality" as the removal of all COVID-19-related restrictions and interventions.
- Herd immunity is not permanent. It can be lost due to waning immunity, both from infection and vaccination.
- For the purpose of estimating new infections, we do not differentiate between immunity acquired from infection and immunity acquired from vaccination.

[Back to Top](#top)

### Vaccination Assumptions

- We count an individual as vaccinated after they receive their first dose. We assume it takes 21 days for an individual to gain immunity.
- **Important:** We currently only model the rollout of two vaccines: Pfizer and Moderna. More vaccines will be approved in 2021 (e.g. Johnson & Johnson, AstraZeneca), but the exact timelines are still unclear. The rollouts of additional vaccines in early 2021 will likely increase vaccine uptake.
- We are estimating how many individuals gain immunity after being vaccinated, not how many vaccine doses are distributed. The difference is subtle, but significant.
- We assume roughly 80-85% of the US population (~275 million) will take at least one dose of the vaccine by the end of 2021. This is higher than the ~50% vaccine coverage for the common flu.
- We assume the majority of individuals (but not all) will receive the second dose.
- We assume the general population will begin receiving vaccinations in late spring/early summer (Apr-Jun 2021).
- We assume children and adolescents will begin receiving vaccinations in late summer/early fall (Aug-Oct 2021).
- We assume a 85% vaccine efficacy. While the trial data demonstrate >90% efficacy, we believe that the efficacy in the general population will be slightly lower due to the fact that a sizable proportion of the population may miss the second vaccine dose.
- We assume that if effective, the vaccine will provide individuals immunity through at least 2021.
- While it is still unclear if the vaccine provides sterilizing immunity, we assume that the vaccine, if effective, can provide functional immunity for the individual and significantly reduce their likelihood of being infectious for at least the duration of 2021. Pfizer expects to report data on whether or not its vaccine stops virus transmission in the first quarter of 2021.
- We assume vaccinations will begin in mid-December following the FDA Emergency Use Authorization (EUA) approval. Due to distribution issues, constraints with storage, and vaccine hesitancy, we believe the initial rollout will be slower than what Operation Warp Speed estimates.
- Many of the assumptions in this writeup come from the [December 10 FDA Briefing Document](https://www.fda.gov/media/144245/download) for the Pfizer vaccine.
- We assume a smooth but conservative vaccine rollout, with no major issues or halts. If rollout and uptake is quicker than estimated, then we may reach herd immunity sooner. If rollout and uptake is slower than estimated, we may reach herd immunity later.
- We assume that at its peak, around 2 million doses will be given per day (enough for innoculate ~1.25 million people). This is slightly lower than the peak vaccine distribution for influenza (~3 million doses per day).
- We assume a proportion of the vaccinated population already possesses immunity via infection. For simplicity, we assume individuals who already possess immunity from natural infection will get vaccinated at the same rate as susceptible individuals. If an individual possesses immunity from both vaccination and infection, we only count this individual as "immune via infection".
- We compute the population "immune via vaccination" by taking the total vaccinated, subtracting the estimated number of individuals who already possess immunity via infection, and multiplying the resulting number by the vaccine efficacy (85%).

[Back to Top](#top)

### Infection Assumptions

- We assume roughly 65 million people in the US (20% of the population) have already been infected by the time the first COVID-19 vaccine is authorized in mid-December 2020 (based on our latest [covid19-projections.com](/) model). We assume ~99.9% of these individuals possess immunity as of mid-December 2020.
- We assume a small proportion (10-15%) of the infected population will lose their immunity by the end of 2021. The longer the time from infection, the higher the likelihood of immunity being lost. While it's still unclear if prior infection confers long-term immunity, recent research ([here](https://www.nejm.org/doi/full/10.1056/NEJMoa2034545?s=09) and [here](https://science.sciencemag.org/content/early/2021/01/06/science.abf4063)) indicates that short-term reinfections are rare.
- If an individual loses immunity but has already been vaccinated, his/her status is moved from "immune via infection" to "immune via vaccination".
- We assume that the infection rate will fall as the number of individuals who are inoculated/vaccinated increases.
- We assume new infections will undergo a steady decrease from mid-December 2020 to March 2021. We account for the possibility of another wave of infections in late winter/early spring (March/April) as states relax restrictions from the fall wave. This final wave may not happen if vaccine rollout is quicker than expected.
- To simplify the modeling, we count an individual as "immune via infection" when they are first infected with the virus. Though in reality, it takes roughly 2-3 weeks after infection to develop antibodies.
- We use a basic SEIR model to estimate infections over time.
- We factor in seasonality to a small extent.
- We assume a small number of imported cases per day. Due to the possible high number of imported cases, daily infections in the US will likely not reach zero in 2021, even if herd immunity is reached.
- We compute the population "immune via infection" by taking the total number of infected individuals and subtracting the estimated number of individuals who lost their immunity.

[Back to Top](#top)

## Corollaries

- Our estimates show that roughly 35-40% of the US population (~125 million) will have been infected by the SARS-CoV-2 virus by the end of 2021. That is an additional 60 million infections since mid-December 2020.
- A 35-40% prevalence estimate translates to a final US COVID-19 death toll of roughly 500,000 to 700,000 reported deaths, with 600,000 deaths being the best estimate. Given a mid-December 2020 death toll of 300,000, that is an additional 300,000 deaths. This estimate may change if the assumptions presented above are no longer true (e.g. deaths will be lower if vaccine rollout is faster than expected; deaths will be higher if the efficacy is lower than expected or if the virus is more transmissible).
- Due to the high prevalence, a targeted approach for vaccination that prioritizes individuals who are more likely to be susceptible may improve the time to reach herd immunity.
- Due to possible low vaccine acceptance/uptake and waning immunity from natural infection, it is possible that the US will not reach immunity levels above 80%. In most scenarios, even 50-80% immunity could be sufficient to prevent large outbreaks.
- Due to the seasonality of the virus, the herd immunity threshold may be higher in the winter. Furthermore, herd immunity can be lost due to waning immunity. Therefore, it is important that we continue to vaccinate individuals even after herd immunity has been reached.

[Back to Top](#top)

## Questions? Comments? Feedback?

You can reach out to Youyang Gu via the [Contact](/contact) page.
