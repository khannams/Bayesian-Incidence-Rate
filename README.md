# Bayesian-Incidence-Rate

This repo contains the program code for fitting a possion model to estimate the incidence rate under interval censored data. 
The true time-to-event is hard to estimate under interval cesored data. The Bayesian model follows the recommendation from Vandormael et. al () for estimating the incidence rate by imputing the time-to-event randomly from the last interval of follow-up. The Bayesian model also provides the opportunity to include prior knowledge on event to imputation. 
Two models are included: Random imputation of time-to-event from last interval under non-informative uniform prior
                         Random imputation of time-to-event from last interval under informative prior
                         
The model is used to estimate the incidence of COVID-19 among dental hygienists in the upcomming manuscript. 
