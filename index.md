---
layout: default
title: COVID-19 Projections Using Machine Learning
permalink: /
---
## Announcement: We made our last daily update on March 7, 2021. Read more [here](https://youyanggu.com/blog/one-year-later).

We present a new, simple nowcasting model that estimates true infections in the US. We have estimates for all US states and all 3,000+ US counties. For our projections for the upcoming months, see our [**Path to Normality**](/path-to-herd-immunity) page.

### For our historical maps, including county-level views, visit the [Maps](/maps-infections) page.

Jump to section:
* [US summary](#us-infections-estimates)
* [State-level infection estimates](#view-us-infections-estimates)
* [County-level infection estimates](#us-counties-infections-estimates)

## Recent Updates

For regular updates and insights, follow Youyang Gu on Twitter:&nbsp; <a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

* **July 1:** See the accuracy of our model - [4 months later](https://twitter.com/youyanggu/status/1410662881591451648).
* **June 24:** See our new [COVID-19 Population Immunity Calculator](https://coda.io/@youyanggu/covid-19-population-immunity-calculator). This calculator estimates the true proportion of a population that have immunity against COVID-19, factoring both immunity from vaccination and natural infection.
* **June 22:** See [our thread](https://twitter.com/youyanggu/status/1407418434955005955) on the single best predictor of total COVID-19 deaths by state: income inequality.
* **May 25:** Is containing COVID-19 a requirement for preserving the economy? Our latest analysis suggests: [probably not](https://twitter.com/youyanggu/status/1397230156301930497).
* **May 13:** See our [analysis](https://twitter.com/youyanggu/status/1392901207811887104) on estimating current excess deaths in the US.
* **May 11:** See our [analysis](https://twitter.com/youyanggu/status/1392179091839848448) comparing states that kept vs dropped mask mandates.
* *May is Asian American and Pacific Islander (AAPI) Heritage Month*. *Read [Youyang's Tweet](https://twitter.com/youyanggu/status/1394698562991181826) about COVID-19 and the model minority myth. See how [systemic racism](https://www.usatoday.com/in-depth/news/nation/2020/10/18/coronavirus-asian-americans-racism-death-rates-san-francisco/5799617002/) is driving high COVID-19 death rates in the Asian American community. Also learn about [rising Asian hate in America](https://www.nytimes.com/2021/03/18/nyregion/asian-hate-crimes.html) and how you can [help combat it](https://stopaapihate.org/).*
* **April 26:** [Click here](/path-to-herd-immunity#comparison-projected-vs-actual) to see a comparison of our final vaccination/infection projections from March 5 to what actually happened.
* **March 24:** We've been working on indexing our work from the past year. [Click here](/sitemap) to see a sitemap of all of the pages on this site. We also compiled a list of all of our COVID-19-related Tweets [here](/twitter-threads/). Over the past year, we have posted quite a bit of original research on Twitter, so feel feel to take a look and give them a read.
* **March 8:** We made our last daily update on March 7 (containing infections estimates through February 21, 2021). Read Youyang Gu's [One Year Later](https://youyanggu.com/blog/one-year-later) blog post for a detailed explanation and for a list of alternate resources. Follow [@youyanggu](https://twitter.com/youyanggu) on Twitter for continued COVID-19 insights. Thank you for your support over the past year. See our downloadable data [on GitHub](https://github.com/youyanggu/covid19-infection-estimates-latest).

See all of our past updates [here](/past-updates).

[Back to Top](#top)

## US Infections Estimates
[More details](/infections/us) | [Detailed methodology](/estimating-true-infections-revisited)

{% include_relative infections/summary.md %}{% include iframe_infections.html %}

Our infections estimates include all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. As of early 2021, we estimate the true number of infected individuals in the US to be roughly 2-4x higher than the reported cases (25-50% detection rate). See our writeup, [Estimating True Infections](/estimating-true-infections-revisited), for a more detailed look into this subject. Because not all currently *infected* individuals are *infectious*, we recommend dividing the *"currently infected"* estimate by 2-4 to get a sense of the number of currently infectious individuals.

[Back to Top](#top)

## View US Infections Estimates

Below, we have infection and vaccination estimates for the US, all 50 states, DC, and 4 US territories. For county-level estimates, see the next section.

| [United States](/infections/us) |  |  |
| --- | --- | --- |
| [Alabama](/infections/us-al) | [Louisiana](/infections/us-la) | [Oklahoma](/infections/us-ok) |
| [Alaska](/infections/us-ak) | [Maine](/infections/us-me) | [Oregon](/infections/us-or) |
| [Arizona](/infections/us-az) | [Maryland](/infections/us-md) | [Pennsylvania](/infections/us-pa) |
| [Arkansas](/infections/us-ar) | [Massachusetts](/infections/us-ma) | [Puerto Rico](/infections/us-pr) |
| [California](/infections/us-ca) | [Michigan](/infections/us-mi) | [Rhode Island](/infections/us-ri) |
| [Colorado](/infections/us-co) | [Minnesota](/infections/us-mn) | [South Carolina](/infections/us-sc) |
| [Connecticut](/infections/us-ct) | [Mississippi](/infections/us-ms) | [South Dakota](/infections/us-sd) |
| [Delaware](/infections/us-de) | [Missouri](/infections/us-mo) | [Tennessee](/infections/us-tn) |
| [District of Columbia](/infections/us-dc) | [Montana](/infections/us-mt) | [Texas](/infections/us-tx) |
| [Florida](/infections/us-fl) | [Nebraska](/infections/us-ne) | [Utah](/infections/us-ut) |
| [Georgia](/infections/us-ga) | [Nevada](/infections/us-nv) | [Vermont](/infections/us-vt) |
| [Guam](/infections/us-gu) | [New Hampshire](/infections/us-nh) | [Virgin Islands](/infections/us-vi) |
| [Hawaii](/infections/us-hi) | [New Jersey](/infections/us-nj) | [Virginia](/infections/us-va) |
| [Idaho](/infections/us-id) | [New Mexico](/infections/us-nm) | [Washington](/infections/us-wa) |
| [Illinois](/infections/us-il) | [New York](/infections/us-ny) | [West Virginia](/infections/us-wv) |
| [Indiana](/infections/us-in) | [North Carolina](/infections/us-nc) | [Wisconsin](/infections/us-wi) |
| [Iowa](/infections/us-ia) | [North Dakota](/infections/us-nd) | [Wyoming](/infections/us-wy) |
| [Kansas](/infections/us-ks) | [Northern Mariana Islands](/infections/us-mp) |
| [Kentucky](/infections/us-ky) | [Ohio](/infections/us-oh) |

[Back to Top](#top)

## US Counties Infections Estimates

We have infections estimates for all 3,000+ US counties (and county equivalents). Click on a state to view the counties in that state. You can then select the county to view detailed infection estimates. Or you can use our county-level [summary page](/infections/summary-counties) for fast lookup of specific counties.

| US Counties ([Summary](/infections/summary-counties)) |  |  |
| --- | --- | --- |
| [Alabama](/infections/counties/al/) | [Kentucky](/infections/counties/ky/) | [North Dakota](/infections/counties/nd/) |
| [Alaska](/infections/counties/ak/) | [Louisiana](/infections/counties/la/) | [Ohio](/infections/counties/oh/) |
| [Arizona](/infections/counties/az/) | [Maine](/infections/counties/me/) | [Oklahoma](/infections/counties/ok/) |
| [Arkansas](/infections/counties/ar/) | [Maryland](/infections/counties/md/) | [Oregon](/infections/counties/or/) |
| [California](/infections/counties/ca/) | [Massachusetts](/infections/counties/ma/) | [Pennsylvania](/infections/counties/pa/) |
| [Colorado](/infections/counties/co/) | [Michigan](/infections/counties/mi/) | [Rhode Island](/infections/counties/ri/) |
| [Connecticut](/infections/counties/ct/) | [Minnesota](/infections/counties/mn/) | [South Carolina](/infections/counties/sc/) |
| [Delaware](/infections/counties/de/) | [Mississippi](/infections/counties/ms/) | [South Dakota](/infections/counties/sd/) |
| [District of Columbia](/infections/counties/dc/) | [Missouri](/infections/counties/mo/) | [Tennessee](/infections/counties/tn/) |
| [Florida](/infections/counties/fl/) | [Montana](/infections/counties/mt/) | [Texas](/infections/counties/tx/) |
| [Georgia](/infections/counties/ga/) | [Nebraska](/infections/counties/ne/) | [Utah](/infections/counties/ut/) |
| [Hawaii](/infections/counties/hi/) | [Nevada](/infections/counties/nv/) | [Vermont](/infections/counties/vt/) |
| [Idaho](/infections/counties/id/) | [New Hampshire](/infections/counties/nh/) | [Virginia](/infections/counties/va/) |
| [Illinois](/infections/counties/il/) | [New Jersey](/infections/counties/nj/) | [Washington](/infections/counties/wa/) |
| [Indiana](/infections/counties/in/) | [New Mexico](/infections/counties/nm/) | [West Virginia](/infections/counties/wv/) |
| [Iowa](/infections/counties/ia/) | [New York](/infections/counties/ny/) | [Wisconsin](/infections/counties/wi/) |
| [Kansas](/infections/counties/ks/) | [North Carolina](/infections/counties/nc/) | [Wyoming](/infections/counties/wy/) |

[Back to Top](#top)

<br>
##################################################################################################

The below sections are from our old COVID-19 projections model, and are no longer being updated. But we will leave them here for your reference.

## COVID-19 Projections (Not Actively Updated)

**Note: We ended our death forecasting project on October 5, 2020. See our blog post [here](https://youyanggu.com/blog/six-months-later). You can find the old project below.**

We present an intuitive COVID-19 model that adds machine learning techniques on top of a classic infectious disease model to make projections for infections and deaths for the US and 70 other countries. The countries our projections cover encompass 6.4 billion people and account for more than 95% of all global reported COVID-19 deaths.

## Old Updates

See our old updates [here](/past-updates#old-updates).

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries). For reproduction number estimates, you can see also visit our [Infections Tracker](/infections-tracker) page.

[Back to Top](#top)

### US

| [United States](/us) |  |  |
| --- | --- | --- |
| [Alabama](/us-al) | [Louisiana](/us-la) | [Oklahoma](/us-ok) |
| [Alaska](/us-ak) | [Maine](/us-me) | [Oregon](/us-or) |
| [Arizona](/us-az) | [Maryland](/us-md) | [Pennsylvania](/us-pa) |
| [Arkansas](/us-ar) | [Massachusetts](/us-ma) | [Puerto Rico](/us-pr) |
| [California](/us-ca) | [Michigan](/us-mi) | [Rhode Island](/us-ri) |
| [Colorado](/us-co) | [Minnesota](/us-mn) | [South Carolina](/us-sc) |
| [Connecticut](/us-ct) | [Mississippi](/us-ms) | [South Dakota](/us-sd) |
| [Delaware](/us-de) | [Missouri](/us-mo) | [Tennessee](/us-tn) |
| [District of Columbia](/us-dc) | [Montana](/us-mt) | [Texas](/us-tx) |
| [Florida](/us-fl) | [Nebraska](/us-ne) | [Utah](/us-ut) |
| [Georgia](/us-ga) | [Nevada](/us-nv) | [Vermont](/us-vt) |
| [Guam](/us-gu) | [New Hampshire](/us-nh) | [Virgin Islands](/us-vi) |
| [Hawaii](/us-hi) | [New Jersey](/us-nj) | [Virginia](/us-va) |
| [Idaho](/us-id) | [New Mexico](/us-nm) | [Washington](/us-wa) |
| [Illinois](/us-il) | [New York](/us-ny) | [West Virginia](/us-wv) |
| [Indiana](/us-in) | [North Carolina](/us-nc) | [Wisconsin](/us-wi) |
| [Iowa](/us-ia) | [North Dakota](/us-nd) | [Wyoming](/us-wy) |
| [Kansas](/us-ks) | [Northern Mariana Islands](/us-mp) |
| [Kentucky](/us-ky) | [Ohio](/us-oh) |

[Back to Top](#top)

### US Counties

| US Counties |  |  |
| --- | --- | --- |
| [AZ - Maricopa](/us-az-maricopa) | [FL - Orange](/us-fl-orange) | [NY - Nassau](/us-ny-nassau) |
| [CA - Alameda](/us-ca-alameda) | [FL - Palm Beach](/us-fl-palm-beach) | [NY - New York City](/us-ny-new-york-city) |
| [CA - Los Angeles](/us-ca-los-angeles) | [IL - Cook](/us-il-cook) | [NY - Suffolk](/us-ny-suffolk) |
| [CA - Orange](/us-ca-orange) | [LA - Orleans](/us-la-orleans) | [NY - Westchester](/us-ny-westchester) |
| [CA - Riverside](/us-ca-riverside) | [MA - Middlesex](/us-ma-middlesex) | [PA - Philadelphia](/us-pa-philadelphia) |
| [CA - Sacramento](/us-ca-sacramento) | [MA - Suffolk](/us-ma-suffolk) | [TX - Bexar](/us-tx-bexar) |
| [CA - San Bernardino](/us-ca-san-bernardino) | [MI - Wayne](/us-mi-wayne) | [TX - Dallas](/us-tx-dallas) |
| [CA - San Diego](/us-ca-san-diego) | [NJ - Bergen](/us-nj-bergen) | [TX - Harris](/us-tx-harris) |
| [CA - Santa Clara](/us-ca-santa-clara) | [NJ - Essex](/us-nj-essex) | [TX - Tarrant](/us-tx-tarrant) |
| [FL - Broward](/us-fl-broward) | [NJ - Hudson](/us-nj-hudson) | [WA - King](/us-wa-king) |
| [FL - Hillsborough](/us-fl-hillsborough) | [NV - Clark](/us-nv-clark) |
| [FL - Miami-Dade](/us-fl-miami-dade) | [NV - Washoe](/us-nv-washoe) |

[Back to Top](#top)

### Global Projections

| [Canada](/canada) |  |
| --- | --- |
| [Alberta](/canada-alberta) | [Ontario](/canada-ontario) |
| [British Columbia](/canada-british-columbia) | [Quebec](/canada-quebec) |

[Back to Top](#top)

| Europe |  |  |
| --- | --- | --- |
| [Austria](/austria) | [Greece](/greece) | [Poland](/poland) |
| [Belarus](/belarus) | [Hungary](/hungary) | [Portugal](/portugal) |
| [Belgium](/belgium) | [Iceland](/iceland) | [Romania](/romania) |
| [Bulgaria](/bulgaria) | [Ireland](/ireland) | [Serbia](/serbia) |
| [Croatia](/croatia) | [Italy](/italy) | [Slovakia](/slovakia) |
| [Cyprus](/cyprus) | [Latvia](/latvia) | [Slovenia](/slovenia) |
| [Czechia](/czechia) | [Lithuania](/lithuania) | [Spain](/spain) |
| [Denmark](/denmark) | [Luxembourg](/luxembourg) | [Sweden](/sweden) |
| [Estonia](/estonia) | [Malta](/malta) | [Switzerland](/switzerland) |
| [Finland](/finland) | [Moldova](/moldova) | [Ukraine](/ukraine) |
| [France](/france) | [Netherlands](/netherlands) | [United Kingdom](/united-kingdom) |
| [Germany](/germany) | [Norway](/norway) |

[Back to Top](#top)

| Rest of World |  |  |
| --- | --- | --- |
| [Algeria](/algeria) | [Ecuador](/ecuador) | [Nigeria](/nigeria) |
| [Argentina](/argentina) | [Egypt](/egypt) | [Pakistan](/pakistan) |
| [Australia](/australia) | [Honduras](/honduras) | [Panama](/panama) |
| [Bangladesh](/bangladesh) | [India](/india) | [Peru](/peru) |
| [Bolivia](/bolivia) | [Indonesia](/indonesia) | [Philippines](/philippines) |
| [Brazil](/brazil) | [Iran](/iran) | [Russia](/russia) |
| [Canada](/canada) | [Israel](/israel) | [Saudi Arabia](/saudi-arabia) |
| [Chile](/chile) | [Japan](/japan) | [South Africa](/south-africa) |
| [China](/china) | [Kuwait](/kuwait) | [South Korea](/south-korea) |
| [Colombia](/colombia) | [Malaysia](/malaysia) | [Turkey](/turkey) |
| [Cuba](/cuba) | [Mexico](/mexico) | [United Arab Emirates](/united-arab-emirates) |
| [Dominican Republic](/dominican-republic) | [Morocco](/morocco) |
