We present a new, simple nowcasting model that estimates true infections in the US. We have estimates for all US states and all 3,000+ US counties.
{% include iframe_home_first_map.html %}For more maps, including county-level views, visit the [Maps](/maps-infections) page.

Jump to section:
* [US summary](#us-infections-estimates-updated-daily)
* [State-level infection estimates](#view-us-infections-estimates)
* [County-level infection estimates](#us-counties-infections-estimates)

## Recent Updates

For regular updates and insights, follow Youyang Gu on Twitter: <a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

* **November 27:** Please have a safe Thanksgiving. Note that reporting will be light due to the extended holiday. Hence, we urge caution in interpreting the latest results. There will likely be a large spike in reported cases and deaths in the following week.
* **November 25:** We have released an initial draft of our methodology: [Estimating True Infections Revisited: A Simple Nowcasting Model to Estimate Prevalent Cases in the US](/estimating-true-infections-revisited).
* *November 23:* We released detailed county-by-county estimates for every US county. You can view them [below](#us-counties-infections-estimates). You can view maps of these estimates on the new [Maps](/maps-infections) page.
* *November 18:* We are re-launching this website with nowcasting of infections estimates in the US (what has happened/is happening). You can download all of our estimates [here](https://github.com/youyanggu/covid19_projections/tree/master/infection_estimates).

[Back to Top](#top)

## US Infections Estimates (Updated Daily)
{% include_relative infections/summary.md %}{% include iframe_infections.html %}

Our infections estimates include all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. As of November, we estimate the true number of infected individuals in the US to be roughly 2-5x higher than the reported cases (20-50% detection rate). See our revised November 2020 writeup, [Estimating True Infections](/estimating-true-infections-revisited), for a more detailed look into this subject. Because not all currently *infected* individuals are *infectious*, we recommend dividing the *"currently infected"* estimate by 2-4 to get a sense of the number of currently infectious individuals.

[Back to Top](#top)

## View US Infections Estimates

Below, we have infection estimates for all 50 states, DC, and 4 US territories. For county-level estimates, see the next section.

| [United States](/infections/us) |  |  |
| --- | --- | --- |
| [Alaska](/infections/us-ak) | [Louisiana](/infections/us-la) | [Oklahoma](/infections/us-ok) |
| [Alabama](/infections/us-al) | [Massachusetts](/infections/us-ma) | [Oregon](/infections/us-or) |
| [Arkansas](/infections/us-ar) | [Maryland](/infections/us-md) | [Pennsylvania](/infections/us-pa) |
| [Arizona](/infections/us-az) | [Maine](/infections/us-me) | [Puerto Rico](/infections/us-pr) |
| [California](/infections/us-ca) | [Michigan](/infections/us-mi) | [Rhode Island](/infections/us-ri) |
| [Colorado](/infections/us-co) | [Minnesota](/infections/us-mn) | [South Carolina](/infections/us-sc) |
| [Connecticut](/infections/us-ct) | [Missouri](/infections/us-mo) | [South Dakota](/infections/us-sd) |
| [District of Columbia](/infections/us-dc) | [Northern Mariana Islands](/infections/us-mp) | [Tennessee](/infections/us-tn) |
| [Delaware](/infections/us-de) | [Mississippi](/infections/us-ms) | [Texas](/infections/us-tx) |
| [Florida](/infections/us-fl) | [Montana](/infections/us-mt) | [Utah](/infections/us-ut) |
| [Georgia](/infections/us-ga) | [North Carolina](/infections/us-nc) | [Virginia](/infections/us-va) |
| [Guam](/infections/us-gu) | [North Dakota](/infections/us-nd) | [Virgin Islands](/infections/us-vi) |
| [Hawaii](/infections/us-hi) | [Nebraska](/infections/us-ne) | [Vermont](/infections/us-vt) |
| [Iowa](/infections/us-ia) | [New Hampshire](/infections/us-nh) | [Washington](/infections/us-wa) |
| [Idaho](/infections/us-id) | [New Jersey](/infections/us-nj) | [Wisconsin](/infections/us-wi) |
| [Illinois](/infections/us-il) | [New Mexico](/infections/us-nm) | [West Virginia](/infections/us-wv) |
| [Indiana](/infections/us-in) | [Nevada](/infections/us-nv) | [Wyoming](/infections/us-wy) |
| [Kansas](/infections/us-ks) | [New York](/infections/us-ny) |
| [Kentucky](/infections/us-ky) | [Ohio](/infections/us-oh) |

[Back to Top](#top)

## US Counties Infections Estimates

We have infections estimates for all 3,000+ US counties (and county equivalents). Click on a state to view the counties in that state. You can then select the county to view detailed infection estimates.

| US Counties |  |  |
| --- | --- | --- |
| [Alaska](/infections/counties/ak/) | [Kentucky](/infections/counties/ky/) | [New York](/infections/counties/ny/) |
| [Alabama](/infections/counties/al/) | [Louisiana](/infections/counties/la/) | [Ohio](/infections/counties/oh/) |
| [Arkansas](/infections/counties/ar/) | [Massachusetts](/infections/counties/ma/) | [Oklahoma](/infections/counties/ok/) |
| [Arizona](/infections/counties/az/) | [Maryland](/infections/counties/md/) | [Oregon](/infections/counties/or/) |
| [California](/infections/counties/ca/) | [Maine](/infections/counties/me/) | [Pennsylvania](/infections/counties/pa/) |
| [Colorado](/infections/counties/co/) | [Michigan](/infections/counties/mi/) | [Rhode Island](/infections/counties/ri/) |
| [Connecticut](/infections/counties/ct/) | [Minnesota](/infections/counties/mn/) | [South Carolina](/infections/counties/sc/) |
| [District of Columbia](/infections/counties/dc/) | [Missouri](/infections/counties/mo/) | [South Dakota](/infections/counties/sd/) |
| [Delaware](/infections/counties/de/) | [Mississippi](/infections/counties/ms/) | [Tennessee](/infections/counties/tn/) |
| [Florida](/infections/counties/fl/) | [Montana](/infections/counties/mt/) | [Texas](/infections/counties/tx/) |
| [Georgia](/infections/counties/ga/) | [North Carolina](/infections/counties/nc/) | [Utah](/infections/counties/ut/) |
| [Hawaii](/infections/counties/hi/) | [North Dakota](/infections/counties/nd/) | [Virginia](/infections/counties/va/) |
| [Iowa](/infections/counties/ia/) | [Nebraska](/infections/counties/ne/) | [Vermont](/infections/counties/vt/) |
| [Idaho](/infections/counties/id/) | [New Hampshire](/infections/counties/nh/) | [Washington](/infections/counties/wa/) |
| [Illinois](/infections/counties/il/) | [New Jersey](/infections/counties/nj/) | [Wisconsin](/infections/counties/wi/) |
| [Indiana](/infections/counties/in/) | [New Mexico](/infections/counties/nm/) | [West Virginia](/infections/counties/wv/) |
| [Kansas](/infections/counties/ks/) | [Nevada](/infections/counties/nv/) | [Wyoming](/infections/counties/wy/) |

[Back to Top](#top)

<br>
##################################################################################################

The below sections are from our old COVID-19 projections model, and are no longer being updated. But we will leave them here for your reference.

## COVID-19 Projections (Not Actively Updated)

We present an intuitive COVID-19 model that adds machine learning techniques on top of a classic infectious disease model to make projections for infections and deaths for the US and 70 other countries. The countries our projections cover encompass 6.4 billion people and account for more than 95% of all global reported COVID-19 deaths.

## Old Updates

* *November 2:* Our final October 5 projections estimated 231,000 (221-245k) US deaths by November 1, 2020. The true November 1 death toll was 230,995 (as reported by Johns Hopkins University). See how our final forecasts tracked the true results [here](/about/#comparison-of-october-us-projections). See our updated historical performance [here](/about/#historical-performance).
* *October 5:* We have released our final update. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later) to read more about this decision. See our [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1313564063679614982). Thank you for your support over the past six months.
* *August 27:* See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries).

[Back to Top](#top)

### US

| [United States](/us) |  |  |
| --- | --- | --- |
| [Alaska](/us-ak) | [Louisiana](/us-la) | [Oklahoma](/us-ok) |
| [Alabama](/us-al) | [Massachusetts](/us-ma) | [Oregon](/us-or) |
| [Arkansas](/us-ar) | [Maryland](/us-md) | [Pennsylvania](/us-pa) |
| [Arizona](/us-az) | [Maine](/us-me) | [Puerto Rico](/us-pr) |
| [California](/us-ca) | [Michigan](/us-mi) | [Rhode Island](/us-ri) |
| [Colorado](/us-co) | [Minnesota](/us-mn) | [South Carolina](/us-sc) |
| [Connecticut](/us-ct) | [Missouri](/us-mo) | [South Dakota](/us-sd) |
| [District of Columbia](/us-dc) | [Northern Mariana Islands](/us-mp) | [Tennessee](/us-tn) |
| [Delaware](/us-de) | [Mississippi](/us-ms) | [Texas](/us-tx) |
| [Florida](/us-fl) | [Montana](/us-mt) | [Utah](/us-ut) |
| [Georgia](/us-ga) | [North Carolina](/us-nc) | [Virginia](/us-va) |
| [Guam](/us-gu) | [North Dakota](/us-nd) | [Virgin Islands](/us-vi) |
| [Hawaii](/us-hi) | [Nebraska](/us-ne) | [Vermont](/us-vt) |
| [Iowa](/us-ia) | [New Hampshire](/us-nh) | [Washington](/us-wa) |
| [Idaho](/us-id) | [New Jersey](/us-nj) | [Wisconsin](/us-wi) |
| [Illinois](/us-il) | [New Mexico](/us-nm) | [West Virginia](/us-wv) |
| [Indiana](/us-in) | [Nevada](/us-nv) | [Wyoming](/us-wy) |
| [Kansas](/us-ks) | [New York](/us-ny) |
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
