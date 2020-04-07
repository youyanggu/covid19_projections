There are many existing models out there that attempt to make COVID-19 projections, but there are shortcomings in those models that could be improved upon. Here we present a model that uses machine learning to project COVID-19 peak and total deaths in the US. 

#### Projection for US
Peak: **1,351** deaths on **April 4, 2020** | Total: **29,070** deaths (by June 30, 2020)

{% include iframe.html %}

### Select a state or country below to see the projections

| [United States](US.html) |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Alabama](AL.html) | [Guam](GU.html) | [Massachusetts](MA.html) | [New York](NY.html) | [Tennessee](TN.html) |
| [Alaska](AK.html) | [Hawaii](HI.html) | [Michigan](MI.html) | [North Carolina](NC.html) | [Texas](TX.html) |
| [Arizona](AZ.html) | [Idaho](ID.html) | [Minnesota](MN.html) | [North Dakota](ND.html) | [Utah](UT.html) |
| [Arkansas](AR.html) | [Illinois](IL.html) | [Mississippi](MS.html) | [Ohio](OH.html) | [Vermont](VT.html) |
| [California](CA.html) | [Indiana](IN.html) | [Missouri](MO.html) | [Oklahoma](OK.html) | [Virgin Islands](VI.html) |
| [Colorado](CO.html) | [Iowa](IA.html) | [Montana](MT.html) | [Oregon](OR.html) | [Virginia](VA.html) |
| [Connecticut](CT.html) | [Kansas](KS.html) | [Nebraska](NE.html) | [Pennsylvania](PA.html) | [Washington](WA.html) |
| [Delaware](DE.html) | [Kentucky](KY.html) | [Nevada](NV.html) | [Puerto Rico](PR.html) | [West Virginia](WV.html) |
| [District Of Columbia](DC.html) | [Louisiana](LA.html) | [New Hampshire](NH.html) | [Rhode Island](RI.html) | [Wisconsin](WI.html) |
| [Florida](FL.html) | [Maine](ME.html) | [New Jersey](NJ.html) | [South Carolina](SC.html) | [Wyoming](WY.html) |
| [Georgia](GA.html) | [Maryland](MD.html) | [New Mexico](NM.html) | [South Dakota](SD.html) |


# COVID-19 Projections Using Machine Learning

As the graph above shows, while other models project 80-250k+ deaths in the US, our model is projecting a much lower estimate of 30-40k deaths. We expect that the other models will lower their estimates in the upcoming days/weeks.

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/projections). Because the model factors in new data data, it will be more accurate over time. You can also view the projections in a chart format below (currently US states only).

Feel free to reach out to me on Twitter via [@youyanggu](https://twitter.com/youyanggu) with any questions/insights/feedback. You can also find me [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

_Note_: While we attempt to predict the _official_ death total, the true death total may be higher due underreporting at various levels.

## About the model

Our COVID-19 prediction model has an underlying simulator that simulates the COVID-19 epidemic in a given region. The parameters of the simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional cross-validation techniques to minimize overfitting, we use the learned parameters to simulate the future and make projections.

We believe overfitting is a major issue when making these projections, which is why other models consistently over-project the severity during the initial phases of the virus spread. While we attempt our best to minimize overfitting, no model is perfect, so we urge everyone to use caution when interpreting these projections.

## Updates

2020-04-05
* Launch [covid19-projections.com](https://covid19-projections.com/)
* Add graphs

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
