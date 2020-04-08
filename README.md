There are many existing models out there that attempt to make COVID-19 projections, but there are shortcomings in those models that could be improved upon. Here we present a model that uses machine learning to project COVID-19 peak and total deaths in the US. 

### Projection for US:
Peak: **1,943** deaths on **April 7, 2020** | Total: **41,689** deaths (by June 30, 2020) {% include iframe.html %}
# COVID-19 Projections Using Machine Learning

As the graph above shows, while other models project 80-250k+ deaths in the United States, our model is projecting a much lower estimate of 30-40k deaths. We expect that the other models will lower their estimates in the upcoming days/weeks. Below you can find our projections for every US state and 37 countries (including all EU countries).

### View Projections

| [United States](us) |  |  |
| --- | --- | --- |
| [Alabama](us-al) | [Kentucky](us-ky) | [Ohio](us-oh) |
| [Alaska](us-ak) | [Louisiana](us-la) | [Oklahoma](us-ok) |
| [Arizona](us-az) | [Maine](us-me) | [Oregon](us-or) |
| [Arkansas](us-ar) | [Maryland](us-md) | [Pennsylvania](us-pa) |
| [California](us-ca) | [Massachusetts](us-ma) | [Puerto Rico](us-pr) |
| [Colorado](us-co) | [Michigan](us-mi) | [Rhode Island](us-ri) |
| [Connecticut](us-ct) | [Minnesota](us-mn) | [South Carolina](us-sc) |
| [Delaware](us-de) | [Mississippi](us-ms) | [South Dakota](us-sd) |
| [District Of Columbia](us-dc) | [Missouri](us-mo) | [Tennessee](us-tn) |
| [Florida](us-fl) | [Montana](us-mt) | [Texas](us-tx) |
| [Georgia](us-ga) | [Nebraska](us-ne) | [Utah](us-ut) |
| [Guam](us-gu) | [Nevada](us-nv) | [Vermont](us-vt) |
| [Hawaii](us-hi) | [New Hampshire](us-nh) | [Virgin Islands](us-vi) |
| [Idaho](us-id) | [New Jersey](us-nj) | [Virginia](us-va) |
| [Illinois](us-il) | [New Mexico](us-nm) | [Washington](us-wa) |
| [Indiana](us-in) | [New York](us-ny) | [West Virginia](us-wv) |
| [Iowa](us-ia) | [North Carolina](us-nc) | [Wisconsin](us-wi) |
| [Kansas](us-ks) | [North Dakota](us-nd) | [Wyoming](us-wy) |
<br />

| Countries |  |  |
| --- | --- | --- |
| [Austria](austria) | [Greece](greece) | [Philippines](philippines) |
| [Belgium](belgium) | [Hungary](hungary) | [Poland](poland) |
| [Brazil](brazil) | [India](india) | [Portugal](portugal) |
| [Bulgaria](bulgaria) | [Indonesia](indonesia) | [Romania](romania) |
| [Canada](canada) | [Iran](iran) | [Slovakia](slovakia) |
| [Croatia](croatia) | [Ireland](ireland) | [Slovenia](slovenia) |
| [Cyprus](cyprus) | [Italy](italy) | [Spain](spain) |
| [Czechia](czechia) | [Latvia](latvia) | [Sweden](sweden) |
| [Denmark](denmark) | [Lithuania](lithuania) | [Switzerland](switzerland) |
| [Estonia](estonia) | [Luxembourg](luxembourg) | [Turkey](turkey) |
| [Finland](finland) | [Malta](malta) | [United States](us) |
| [France](france) | [Mexico](mexico) | [United Kingdom](united-kingdom) |
| [Germany](germany) | [Netherlands](netherlands) |

## About the model

Our COVID-19 prediction model has an underlying simulator that simulates the COVID-19 epidemic in a given region. The parameters of the simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional cross-validation techniques to minimize overfitting, we use the learned parameters to simulate the future and make projections.

The **only** COVID-19 data we use to make these projections is the daily death total provided by [The Covid Tracking Project](https://covidtracking.com/) (for US projections) and [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) (for international projections).

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/projections). Because the model factors in new data data, it will be more accurate over time. You can also view the projections in a chart format below (currently US states only).

We believe overfitting is a major issue when making these projections, which is why other models consistently over-project the severity during the initial phases of the virus spread. While we attempt our best to minimize overfitting, no model is perfect, so we urge everyone to use caution when interpreting these projections.

Feel free to reach out to me on Twitter via **[@youyanggu](https://twitter.com/youyanggu)** with any questions/insights/feedback. You can also find me [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

_Note_: While we attempt to predict the _official_ death total, the true death total may be higher due underreporting at various levels.

## Model Comparison
Below we compare our model with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/):

| Date | Our prediction | IHME prediction | Current US deaths
| --- | --- | --- | --- |
| 2020-04-01 | 34,270 | 93,400 | 4,700
| 2020-04-02 | 38,030 | 93,400 | 5,784
| 2020-04-03 | 44,566 | 93,400 | 6,962
| 2020-04-04 | 40,632 | 93,400 | 8,314
| 2020-04-05 | 41,387 | 81,766 | 9,498
| 2020-04-06 | 29,316 | 81,766 | 10,680
| 2020-04-07 | 41,689 | 81,766 | 12,621

## Updates

2020-04-07
* Add projections for all EU countries and 10 non-EU countries

2020-04-05
* Launch [covid19-projections.com](https://covid19-projections.com/)
* Add graphs for each state

2020-04-04
* Separate global data from US data

2020-04-03
* Add 9 international countries for projections

2020-04-02
* Add lower and upper bounds to projections; also project date of peak deaths
* Incorporate international data and add projections for Italy

2020-04-01
* Incorporate US states data and add projections for every state

2020-03-31
* Add first projections for NY and CA

2020-03-30
* Begin project
