---
layout: default
title: Model Details
permalink: /model-details/
---

# Model details

## SEIS Model

Our COVID-19 prediction model has an underlying simulator based on an elaboration of the classic SIR model used in epidemiology: the SEIS (susceptible-exposed-infected-susceptible) model. We added an exposed (E) period due to the reported incubation period of COVID-19 during which individuals are not yet infectious. We also changed the last step from recovered (R) to susceptible (S) to account for the possibility of re-infection, a phenomnenon that has already been reported in several countries. With that said, we assume that a recovered individual is less likely to be infected again.

To quickly summarize how an SEIS model works, at each time period, an individual in a population is in one of three states: susceptible (S), exposed (E), and infectious (I). If an individual is in the susceptible state, we can assume they are healthy. If they are in the exposed state, they have been infected with the virus but are not infectious. If they are infectious, they can actively transmit the disease. An individual who is infected ultimately either recovers or dies. We can model the movement of individuals through these various states at each time period. The model's exact specifications depend on its parameters, which we describe in the next section.

## Assumptions

Please see the [About](/about#assumptions) page to read about the assumptions in our model.

## Parameters

For our SEIS model, there are basic inputs/parameters that must be set to begin simulation. [covid19-scenarios.org](https://covid19-scenarios.org/) developed by the University of Basel provides a good visualization of sample inputs/parameters into a simulation. We chose a set of parameters that we think are important for the accuracy of the simulation. We divide the parameters into two categories:

### Category 1: Fixed parameters

Fixed parameters are those that are fixed for this particular COVID-19 epidemic and likely do not fluctuate significantly across countries/states/regions. These include the following:
- Latency period
- Infections period
- Time between illness onset to hospitalization
- Time between illness onset to death
- Hospital stay time
- Time to recovery

We use various reports and publications to determine the best values for these fixed parameters. Most of these sources reference studies from Wuhan, China, where the epidemic first began in December 2019. While it is possible that the exact values may fluctuate slightly from region to region, we believe that the impacts these fluctuations have are minimal compared to the variable parameters.

### Category 2: Variable parameters

Variable parameters are those that may change depending on the country/state/region. Some examples are the following:
- R<sub>0</sub> - the basic reproduction number
- Mortality rate
- Imports of positive cases per day
- Mitigation effects (i.e. post-mitigation R)
- Lifting of shelter-at-home orders (i.e. post-reopening R)
- Population
- Hospital beds per 1000

Note that variable parameters such as population and hospital beds per 1000 are easily computable from a simple lookup. However, the other parameters are not easily retrievable. We will allocate the majority of our resources towards estimating the most sensible values for these parameters for each region.

To model the effects of shelter-at-home/lockdown orders, we assign an R value for post-lockdown and a separate R value for post-reopening. These R values are unknown ahead of time, and will be learned by the model. We assume that post-mitigation R is less than 1 to account for the decrease in cases, and that the post-reopening R is on average less than the initial R<sub>0</sub>.

## Parameter Search using Machine Learning

As described in the previous section, determining the best values for variable parameters such as R<sub>0</sub>, the mortality rate, post-mitigation R, and post-reopening R will help us determine how COVID-19 will progress in a region. If we know what the "true" values of those parameters are, we can accurately simulate what is happening in the real world using our SEIS model. To determine these values, we use hyperparameter optimization.

### Hyperparameter Optimization

We found that a brute-force search method that iterates through the entire parameter space is the most effective in finding an optimal set of parameters. We use grid search to iterate through the parameter space. So if we have 10 values for R<sub>0</sub> and 10 values for the mortality rate, then there are 100 different parameter combinations for those two parameters. To optimize computation time, we prune unrealistic parameters (e.g. R<sub>0</sub> > 20).

To measure the error of a parameter set, we use a loss function that minimizes the error between our projected daily deaths and the actual daily deaths. We find that an ensemble loss function that minimizes both absolute daily deaths and total daily deaths works well. For parameters where we do not have the data to estimate (e.g. we do not know the post-reopening R for regions that have not reopened), we consider all values equally, resulting in a wider confidence interval.

While we do not have much out-of-sample data to work with, we try our best to take advantage of the data from countries such as China, Italy, and Iran, whose progression is much further along than regions such as the US.

## Putting it All Together

For each region, we run our optimizer on the data to score each set of parameters. After some additional validation techniques to minimize overfitting, we aggregate the forecasts generated by each set of parameter, giving higher preference to parameters that have a lower error. We now have our projections.

