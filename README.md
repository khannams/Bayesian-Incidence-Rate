# Bayesian-Incidence-Rate

This repo contains the program code for fitting a possion model to estimate the incidence rate under interval censored data. 
The true time-to-event is hard to estimate under interval cesored data. The Bayesian model follows the recommendation from Vandormael et. al (Vandormael A, Tanser F, Cuadros D, Dobra A. Estimating trends in the incidence rate with interval censored data and time-dependent covariates. Stat Methods Med Res. 2020 Jan;29(1):272–81. https://doi.org/10.1177/0962280219829892) for estimating the incidence rate by imputing the time-to-event randomly from the last interval of follow-up. The Bayesian model also provides the opportunity to include prior knowledge on event to imputation. 

Two models are included: Random imputation of time-to-event from last interval under non-informative uniform prior
                         Random imputation of time-to-event from last interval under informative prior

Models are implemented in JAGS (Plummer, Martyn. (2003). JAGS: A Program for Analysis of Bayesian Graphical Models using Gibbs Sampling. 3rd International Workshop on Distributed Statistical Computing (DSC 2003); Vienna, Austria. 124.)

The model is used to estimate the incidence of COVID-19 among dental hygienists in the upcomming manuscript. 
