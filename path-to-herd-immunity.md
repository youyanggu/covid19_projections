---
layout: default
title: Path to Herd Immunity
permalink: /path-to-herd-immunity/
---

# Path to Herd Immunity: 2021 Outlook of COVID-19 in the US
By: [Youyang Gu](https://youyanggu.com)
<br>December 9, 2020 *(Last Updated: December 11, 2020)*

With the availability of the COVID-19 vaccine in the near horizon, we present our best estimate of the path to COVID-19 herd immunity in the United States. Herd immunity will be reached through immunity from two sources: vaccination and natural infection.

## Table of Contents
* [Summary](#summary)
* [Disclaimers](#disclaimers)
* [Assumptions](#assumptions)
* [Corollaries](#corollaries)
* [Questions? Comments? Feedback?](#questions-comments-feedback)

## Summary
- We estimate COVID-19 herd immunity (>60% of population immune) will be reached in the US during summer 2021 (Jun-Aug 2021). At a high level, herd immunity is a concept in which a population can be protected from a virus if enough people possess immunity.
- At the time herd immunity is reached, roughly half of the immunity will be achieved through natural infection, and the other half will be achieved through vaccination.
- New infections may become minimal before herd immunity is reached. But due to imported cases and localized clusters, it is unlikely that new infections will drop to zero until at least 2022.
- Deaths may drop to low levels even earlier (May-Jul 2021), in part due to a vaccine distribution strategy that initially prioritizes high-risk individuals. Once deaths fall to minimal levels, we may see a relaxation of restrictions.
- Summarizing the above findings, our best estimate of a complete "return to normal" in the US is mid-summer 2021 (June/July 2021).
- We estimate roughly two-thirds of the US population (~220 million) will receive at least one dose of the vaccine by the end of 2021, with children and adolescents being the last group to receive it (Aug-Nov 2021).
- We estimate around one-third of the US population (~105 million) will have been infected by the SARS-CoV-2 virus by the end of 2021. That is an additional 40 million infections since mid-December 2020.
- This translates to a final US COVID-19 death toll of roughly 500,000 (+/-100k) reported deaths, or ~200,000 additional deaths since mid-December 2020.
{% include iframe_vaccination.html %}
[Back to Top](#top)

## Disclaimers

- The author is not an epidemiologist.
- The author is not a public health expert.
- This writeup has not been peer-reviewed in an academic journal.
- Only publicly available data are used.
- The results presented here are merely estimates based on a set of assumptions, so please use caution when utilizing the results.
- For the majority of the assumptions, the exact numerical values have relatively minor impacts on the final results (e.g. changing vaccine efficacy from 85% to 90% results in a 10-day shift in when herd immunity is reached).
- If any of the assumptions used to generate these estimates do not hold, then the results may be drastically different.
- These estimates are subject to change based on new data/evidence.

[Back to Top](#top)

## Assumptions

The underlying assumptions behind our estimates are presented below:

### Basic Assumptions

- We assume immunity can be achieved through either natural infection or vaccination.
- We assume herd immunity is achieved when at least 60% of the population possess immunity from the SARS-CoV-2 virus (HIT = 60%). This corresponds to 200 million individuals in the US. Due to population heterogeneity, variation in susceptibility and/or pre-existing immunity, it is possible that the herd immunity threshold (HIT) can be lower. But HIT can also be higher due to the targeted approach of vaccine distribution (e.g. individuals with the greatest impact on transmission are vaccinated last).
- **Important:** We only count the immunity that was acquired first (e.g. if an individual has both immunity from natural infection and immunity from vaccination, we only count the immunity from infection).
- We assume states will continue to impose varying degrees of restrictions and interventions until herd immunity is reached.
- We define "normality" as the removal of all COVID-19-related restrictions and interventions.
- Herd immunity is not permanent. It can be lost due to waning immunity, both from infection and vaccination.

[Back to Top](#top)

### Vaccination Assumptions

- **Important:** We are estimating how many individuals gain immunity after being vaccinated, not how many vaccine doses are distributed. The difference is subtle, but significant.
- We assume an individual has been vaccinated after they receive the first of two doses. We assume it takes two weeks for an individual to begin gaining immunity.
- We currently model the initial rollout of two vaccines: Pfizer and Moderna. More vaccines will be approved in 2021 (e.g. Johnson & Johnson, AstraZeneca), but by then we do not believe supply will be the bottleneck. Hence, we do not believe that the introduction of additional vaccines in 2021 will significantly affect vaccine uptake rates.
- We assume roughly two-thirds of the US population will take at least one dose of the vaccine by the end of 2021. This is slightly higher than the ~50% vaccine coverage for the common flu.
- We assume the majority of individuals (but not all) will receive the second dose.
- We assume the general population will begin receiving vaccinations in late spring/early summer (Apr-Jun 2021).
- We assume children and adolescents will begin receiving vaccinations in late summer/early fall (Aug-Oct 2021).
- We assume a 85% vaccine efficacy. While the trial data demonstrate >90% efficacy, we believe that the efficacy in the general population will be slightly lower due to the fact that a sizable proportion of the population may miss the second vaccine dose.
- While it is still unclear if the vaccine provides sterilizing immunity, we assume that the vaccine, if effective, can prevent individuals from becoming infectious.
- We assume vaccinations will begin in mid-December following the FDA Emergency Use Authorization (EUA) approval.
- Many of the assumptions in this writeup come from the [December 10 FDA Briefing Document](https://www.fda.gov/media/144245/download) for the Pfizer vaccine.
- We assume a smooth vaccine rollout (no major issues or halts).
- We assume that at its peak, around 2.5 million doses will be given per day (enough for innoculate 1.25 million people). This is close to the peak vaccine distribution for influenza (~3 million doses per day).
- We assume a proportion of the vaccinated population already possess immunity via infection. For simplicity, we assume individuals who already possess immunity from natural infection will get vaccinated at the same rate as susceptible individuals. If an individual possesses immunity from both vaccination and infection, we only count this individual as "immune via infection".
- We compute the population "immune via vaccination" by taking the total vaccinated, subtracting the estimated number of individuals who already possess immunity via infection, and multiplying the resulting number by the vaccine efficacy (85%).

[Back to Top](#top)

### Infection Assumptions

- We assume roughly 63 million people in the US (19% of the population) have already been infected by the time the first COVID-19 vaccine is authorized in mid-December 2020 (based on our latest [covid19-projections.com](/) model). We assume ~99.9% of these individuals possess immunity as of mid-December 2020.
- We assume a small proportion (~10%) of the infected population will lose their immunity by the end of 2021. The longer the time from infection, the higher the likelihood of immunity being lost.
- If an individual loses immunity but gets vaccinated, they are counted as "immune via vaccination".
- We assume that the infection rate will fall as the number of individuals who are inoculated/vaccinated increases.
- We assume new infections will undergo a steady decrease from mid-December 2020 to March 2021. We account for the possibility of another wave of infections in late winter/early spring (March/April) as states relax restrictions from the fall wave. This final wave may not happen if vaccine rollout is quicker than expected.
- We use a basic SEIR model to estimate infections over time.
- We factor in seasonality to a small extent.
- We assume a small number of imported cases per day. Due to the possible high number of imported cases, daily infections in the US will likely not reach zero in 2021, even if herd immunity is reached.
- We compute the population "immune via infection" by taking the total number of infected individuals and subtracting the estimated number of individuals who lost their immunity.

[Back to Top](#top)

## Corollaries

- Our estimates show that roughly one-third of the US population (~105 million) will have been infected by the SARS-CoV-2 virus by the end of 2021. That is an additional 40 million infections since mid-December 2020.
- A 30% prevalence estimate translates to a final US COVID-19 death toll of roughly 400,000 to 600,000 reported deaths, with 500,000 deaths being the best estimate. Given a mid-December 2020 death toll of 300,000, that is an additional 200,000 deaths. This estimate may change if the assumptions presented above are no longer true (e.g. deaths will be lower if vaccine rollout is faster than expected; deaths will be higher if the efficacy is lower than expected).
- Due to the high prevalence, a targeted approach for vaccination that prioritizes individuals who are more likely to be susceptible may improve the time to reach herd immunity.
- Due to possible low vaccine acceptance/uptake and waning immunity from natural infection, it is possible that the US will not reach immunity levels above 70%. In most scenarios, even 50-70% immunity should be sufficient to prevent new outbreaks.
- Due to the seasonality of the virus, the herd immunity threshold may be higher in the winter. Furthermore, herd immunity can be lost due to waning immunity. Therefore, it is important that we continue to vaccinate individuals even after herd immunity has been reached.

[Back to Top](#top)

## Questions? Comments? Feedback?

You can reach out to Youyang Gu via the [Contact](/contact) page.
