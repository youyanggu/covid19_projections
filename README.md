# COVID-19 Projections

I used machine learning to develop a model that attempts to project COVID-19 deaths in the US. There are a lot of existing models out there already, but I believe that there are flaws in those models that could be improved upon. I want to utilize a data-heavy approach to this problem, rather than an epidemiologic approach. I will upload my daily projections for all US 50 states. The projections will be updated daily based on new data.

Feel free to reach out to me on Twitter via @youyanggu with any questions/insights/feedback.

_Note_: We attempt to predict the _official_ death total. The true death total may be higher due underreporting on various levels. To compute the total number of people infected (including those not reported), we can simply divide the death total by the approximate mortality rate (1%). Due to testing limitations that prevent us from accurately utilize the reported cases data, I believe this is the best way to estimate the impact of COVID-19.

{% include iframe.html %}

## Updates

2020-04-05
* Add graphs

2020-04-04
* Separate global data from US data

2020-04-03
* Add 10 international countries for projections

2020-04-02
* Add lower and upper bounds to projections; also project date of peak deaths
* Incorporate international data and add projections for Italy

2020-04-01
* Incorporate US states data and add projections for every state

2020-03-31
* Add first projections for NY and CA
