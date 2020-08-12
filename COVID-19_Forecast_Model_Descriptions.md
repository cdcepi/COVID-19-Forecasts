## Models

- [Auquan Data Science](#Auquan)
- [Berkeley Yu Group](#Yu_Group)
- [Carnegie Mellon University](#CMU)
- [Center for Disease Dynamics, Economics & Policy](#CDDEP)
- [Columbia University](#Columbia)
- [Columbia University and University of North Carolina](#Columbia-UNC)
- [Covid-19 Simulator Consortium](#Covid19Sim)
- [Covid Act Now](#CAN)
- [Discrete Dynamical Systems](#DDS)
- [Georgia Institute of Technology, Center for Health and Humanitarian Systems](#GT-CHHS)
- [Georgia Institute of Technology, College of Computing](#GT-DeepCOVID)
- [Imperial College, London](#Imperial)
- [Institute of Health Metrics and Evaluation](#IHME)
- [Iowa State University](#ISU)
- [John Burant](#JCB)
- [Johns Hopkins University, Infectious Disease Dynamics Lab](#JHU)
- [Karlen Working Group](#Karlen)
- [LockNQuay](#LNQ)
- [London School of Hygiene and Tropical Medicine](#LSHTM)
- [Los Alamos National Laboratory](#LANL)
- [Massachusetts Institute of Technology, COVID-19 Policy Alliance](#MIT-CovAlliance)
- [Massachusetts Institute of Technology, Operations Research Center](#MIT-ORC)
- [Northeastern](#MOBS)
- [Notre Dame University](#NotreDame)
- [Oliver Wyman](#OliverWyman)
- [Pandemic Central](#PandemicCentral)
- [Predictive Science Inc.](#PSI)
- [Qi-Jun Hong](#QJHong)
- [Rensselaer Polytechnic Institute and University of Washington](#RPI-UW)
- [Robert Walraven](#ESG)
- [Steve Hortman](#STH)
- [University of Arizona](#UA)
- [University of California, Los Angeles](#UCLA)
- [University of Chicago](#UChicago)
- [University of Georgia, Center for the Ecology of Infectious Disease](#UGA-CEID)
- [University of Geneva / Swiss Data Science Center](#Geneva)
- [University of Massachusetts, Amherst](#UMass)
- [University of Michigan](#UM)
- [University of Southern California](#USC)
- [University of Texas, Austin](#UT)
- [University of California, Los Angeles](#UCLA)
- [US Army Engineering Research and Development Center](#ERDC)
- [Youyang Gu (COVID-Projections)](#YYG)


## Model Descriptions

### [Auquan Data Science](https://covid19-infection-model.auquan.com/) <a name="Auquan"/>

**Model name:** Auquan

**Intervention assumptions:** These projections do not make specific assumptions about which interventions have been implemented or will remain in place.  

**Methods:** Fitted SEIR model

**Forecasts submitted:** Deaths


### [Berkeley Yu Group](covidseverity.com) <a name="Yu_Group"/>

**Model name:** Yu_Group

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.  

**Methods:** Ensemble of combined linear and exponential predictors (CLEP)

**Forecasts submitted:** Cases


### [Carnegie Mellon University](https://delphi.cmu.edu/) <a name="CMU"/>

**Model name:**  CMU

**Intervention Assumptions:**  These projections do not make specific assumptions about which interventions have been implemented or will remain in place.

**Methods:**  Autoregressive time-series model

**Forecasts submitted:** Cases, deaths


### [Center for Disease Dynamics, Economics & Policy](https://cddep.org/) <a name="CDDEP"/>

**Model name:**  CDDEP

**Intervention Assumptions:**  This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:**  Bayesian SEIR model

**Forecasts submitted:** Cases


### [Columbia University](https://columbia.maps.arcgis.com/apps/webappviewer/index.html?id=ade6ba85450c4325a12a5b9c09ba796c) <a name="Columbia"/>

**Model name:** Columbia

**Intervention assumptions:** This model assumes that contact rates will increase 5% per week over the next two weeks. The reproductive number is then set to 1 for the remainder of the projection period.

**Hospitalization assumptions:** The model uses state-specific hospitalization data, when available. In states without hospitalization data, the model uses the national average value for hospitalization data.

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Columbia University and University of North Carolina](https://github.com/COVID19BIOSTAT/covid19_prediction) <a name="Columbia-UNC"/>

**Model name:** Columbia-UNC

**Intervention assumptions:** This model assumes that transmission intensity will peak in early July and then gradually decline.

**Methods:** Statistical survival-convolutional model

**Forecasts submitted:** Cases, deaths


### [Covid-19 Simulator Constorium](https://www.covid19sim.org/) <a name="Covid19Sim"/>

**Model name:** Covid19Sim

**Intervention assumptions:** This model is based on assumptions about how levels of social distancing will change in the future.

**Hospitalization assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Discrete Dynamical Systems](https://dds-covid19.github.io/index.html) <a name="DDS"/>

**Model name:** DDS

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Bayesian hierarchical model

**Forecasts submitted:** Cases, deaths, hospitalizations


### [Covid Act Now](https://covidactnow.org/) <a name="CAN"/>

**Model name:** CAN

**Intervention assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Fitted SEIR model

**Forecasts submitted:** Deaths


### [Discrete Dynamical Systems](https://dds-covid19.github.io/index.html) <a name="DDS-NBDS"/> 

**Model name:** DDS-NBDS

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Bayesian hierarchical model

**Forecasts submitted:** Cases


### [Georgia Institute of Technology, Center for Health and Humanitarian Systems](https://github.com/pkeskinocak/COVID19GA) <a name="GT-CHHS"/>

**Model name:** GT-CHHS

**Intervention Assumptions:** This model assumes that that once stay-at-home orders are lifted, contact rates will gradually increase. It also assumes that some households containing symptomatic cases will self-quarantine.

**Methods:** Agent-based model

**Forecasts submitted:** Deaths


### [Georgia Institute of Technology, College of Computing](https://deepcovid.github.io/) <a name="GT-DeepCOVID"/>

**Model name:** GT-DeepCOVID (formerly: GA_Tech)

**Intervention Assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Hospitalization Assumptions:** Daily hospitalizations are predicted from publicly available, state-level data sources.

**Methods:** Deep learning

**Forecasts submitted:** Deaths, and hospitalizations


### [Imperial College, London](https://mrc-ide.github.io/covid19-short-term-forecasts/index.html) <a name="Imperial"/>

**Model name:** Imperial

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Ensembles of mechanistic transmission models, fit to different parameter assumptions

**Forecasts submitted:** Deaths


### [Institute of Health Metrics and Evaluation](https://covid19.healthdata.org/united-states-of-america) <a name="IHME"/>

**Model name**: IHME

**Intervention Assumptions:** Projections are adjusted to reflect differences in aggregate population mobility and community mitigation policies.

**Hospitalization assumptions:** Daily hospitalizations are estimated from predictions of daily deaths, using state hospitalization rates, where available.

**Methods:** Combination of a mechanistic disease transmission model and a curve-fitting approach

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Iowa State University](https://covid19.stat.iastate.edu/) <a name="ISU"/>

**Model name:** ISU

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Nonparametric spatiotemporal model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [John Burant](https:/github.com/JohnBurant/COVID19-PRM) <a name="JCB"/>

**Model name:** JCB

**Intervention Assumptions:** The incidence of COVID-19 in the population determines the strength of and resulting impact of control measures in the future.

**Methods:** Phenomenological statistical model

**Forecasts submitted:** Deaths


### [Johns Hopkins University](https:/github.com/HopkinsIDD/COVIDScenarioPipeline) <a name="JHU"/>

**Model name:** JHU

**Intervention Assumptions:** This model assumes that the effectiveness of interventions is reduced after shelter-in-place orders are lifted.

**Hospitalization Assumptions:** Daily hospitalizations are estimated from predictions of daily cases. A standard proportion is applied to all states.

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Karlen Working Group](https://pypm.github.io/home/) <a name="Karlen"/>

**Model name:*** Karlen

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Hospitalization assumptions:** The model uses state-specific hospitalization data. New hospitalizations are estimated from these data, or from the estimated number of new infections that will occur in each location.

**Methods:** Discrete time difference equations

**Forecasts submitted:** Cases, hospitalizations, deaths


### [LockNQuay](https://www.kaggle.com/sasrdw/locknquay) <a name="LNQ"/>

**Model name:** LNQ

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Machine learning

**Forecasts submitted:** Cases, deaths


### [London School of Hygiene and Tropical Medicine](https://github.com/epiforecasts/covid-us-forecasts) <a name="LSHTM"/>

**Model name:** LSHTM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** This forecast is an ensemble of three different models: A time-varying reproductive number-base model, a time series model based on numbers of deaths, and a time series model based on numbers of cases and deaths. 

**Forecasts submitted:** Deaths


### [Los Alamos National Laboratory](https://covid-19.bsvgateway.org/) <a name="LANL"/>

**Model name:** LANL

**Intervention assumptions:** This model assumes interventions in place on the first day of the forecast will remain in place for the next four weeks. 

**Hospitalization Assumptions:** State demographics and age-group symptomatic case hospitalization rates are used to estimate the daily number of hospitalizations, based on estimates of the total number of infections.

**Methods:** Statistical dynamical growth model accounting for population susceptibility

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Massachusetts Institute of Technology, COVID-19 Policy Alliance](https://www.covidalliance.com/) <a name="MIT-CovAlliance"/>

**Model name:** MIT-CovAlliance

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** SIR model 

**Forecasts submitted:** Cases, deaths 


### [Massachusetts Institute of Technology, Operations Research Center](https://www.covidanalytics.io/projections) <a name="MIT-ORC"/>

**Model name:** MIT-ORC

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** SEIR model 

**Forecasts submitted:** Cases, deaths


### [Northeastern University, Laboratory for the Modeling of Biological and Socio-technical Systems](https://covid19.gleamproject.org/) <a name="MOBS"/>

**Model name:** MOBS

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Metapopulation, age-structured SLIR model

**Forecasts submitted:** Deaths


### [Notre Dame University](https://github.com/confunguido/covid19_ND_forecasting) <a name="NotreDame"/>

**Model names:** 
  
- NotreDame-Mobility
- NotreDame-FRED

**Intervention assumptions:** These forecasts assume that population-level mobility is a reliable proxy for adherence to social distancing, and that recent trends in mobility will continue over the coming weeks.

**Methods:** 
  
- NotreDame-Mobility: SEIR model fit to data on deaths, test positivity, and population mobility
- NotreDame-Fred: Agent-based model

**Forecasts submitted:** Deaths


### [Oliver Wyman](https://pandemicnavigator.oliverwyman.com/) <a name="OliverWyman">

**Model name:** Oliver Wyman

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Time-dependent SIR model for detected and undetected cases

**Forecasts submitted:** Cases, deaths


### [Pandemic Central](https://itsonit.com) <a name="PandemicCentral">

**Model name:** PandemicCentral

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Random forest machine learning model

**Forecasts submitted:** Cases


### [Predictive Science Inc.](https://github.com/predsci/DRAFT) <a name="PSI">

**Model name:** PSI

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Stochastic SEIRX model

**Forecasts submitted:** Deaths


### [Qi-Jun Hong](https://qjhong.github.io/) <a name="QJHong">

**Model name:** QJHong

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Machine learning using case data and mobility data

**Forecasts submitted:** Cases, deaths


### [Rensselaer Polytechnic Institute and University of Washington](http://medrxiv.org/content/10.1101/2020.07.25.20162016v1) <a name="RPI-UW">

**Model name:** RPI-UW

**Intervention assumptions:** These projections calibrate the rate of transmission to the average rate of population mobility since the start of the epidemic and assume that this relationship will not change in the next four weeks.

**Methods:** SIR model fit to mobility data

**Forecasts submitted:** Deaths


### [Robert Walraven](http://rwalraven.com/COVID19/) <a name="ESG">

**Model name:** ESG

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Fitting reported data to multiple skewed gaussian distributions

**Forecasts submitted:** Cases, deaths


### [Steve Horstman](http://public.tableau.com/profile/covid19model#!/vizhome/COVID-19DeathProjections/USDeaths) <a name="STH">

**Model name:** STH

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Statistical growth model

**Forecasts submitted:** Deaths


### [University of Arizona](https://jocelinelega.github.io/EpiGro/) <a name="UA"/>

**Model name:** UA

**Intervention assumptions:** This model assumes that current interventions will remain in effect for at least four weeks after the forecasts are made.

**Methods:** SIR mechanistic model with data assimilation

**Forecasts submitted:** Deaths


### [University of California, Los Angeles](https://covid19.uclaml.org/) <a name="UCLA"/>

**Model name:** UCLA

**Intervention assumptions:** This model assumes that contact rates will increase as states reopen. The increase in contact rates is calculated for each state.

**Hospitalization Assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** Modified SEIR model

**Forecasts submitted:** Cases, deaths


### [University of California, Merced](https://mechatronics.ucmerced.edu/covid19) <a name="UCM"/>

**Model name:** UCM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:**  SEIR model

**Forecasts submitted:** Deaths


### [University of Chicago](https://github.com/cobeylab/covid_IL) (forecasts for Illinois only) <a name="UChicago"/>

**Model name:** UChicago

**Intervention assumptions:** These forecasts assume that transmission rate will increase by 10% when stay-at-home policies are lifted.

**Methods:** SEIR model

**Forecasts submitted:** Deaths


### [University of Georgia, Center for the Ecology of Infectious Disease](https://https://github.com/e3bo/random-walks) <a name="UGA-CEID"/>

**Model name:** UGA-CEID

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Statistical random walk model

**Forecasts submitted:** Cases and deaths




### [University of Geneva / Swiss Data Science Center](https://renkulab.shinyapps.io/COVID-19-Epidemic-Forecasting/) (one-week ahead forecasts only) <a name="Geneva"/>

**Model name:** Geneva

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Exponential and linear statistical models fit to the recent growth rate of cumulative deaths

**Forecasts submitted:** Cases, deaths


### [University of Massachusetts, Amherst](https://reichlab.io/) <a name="UMass"/>

**Model names:** UMass-MB, Ensemble

**Intervention assumptions:**
-	UMass-MB: These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.
-	Ensemble: The ensemble forecasts include all submitted forecasts, derived from models that assume certain social distancing measures will continue and models that assume those measures will not continue. 

**Methods:**
-	UMass-MB: Mechanistic Bayesian compartment model
-	Ensemble: The ensemble is a combination of 4 to 20 models, depending on the availability of forecasts for each location. To ensure consistency, the ensemble includes only models with 4 week-ahead forecasts.

**Forecasts submitted:** Cases, deaths


### [University of Michigan](https://gitlab.com/sabcorse/covid-19-collaboration) <a name="UM">

**Model name:** UM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Ridge regression

**Forecasts submitted:** Cases, deaths


### [University of Southern California](https://scc-usc.github.io/ReCOVER-COVID-19/#/) <a name="USC">

**Model name:** USC

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SIR model

**Forecasts submitted:** Cases, deaths


### [University of Texas, Austin](https://covid-19.tacc.utexas.edu/projections/) <a name="UT"/>

**Model name:** UT

**Intervention assumptions:** This model estimates the extent of social distancing using geolocation data from mobile phones and assumes that the extent of social distancing does not change during the period of forecasting. The model is designed to predict confirmed COVID-19 deaths resulting from only a single wave of transmission.

**Methods:** Nonlinear Bayesian hierarchical regression with a negative-binomial model for daily variation in death rates

**Forecasts submitted:** Deaths


### [University of Virginia](https://biocomplexity.virginia.edu/)<a name="UVA">

**Model name:** UVA

**Intervention assumptions:** There are two different assumptions influencing this ensemble model. Two of the three models assume that the effects of interventions are reflected in the observed data and will continue going forward, while the third model assumes that interventions will change in the future.

**Methods:** This forecast is an ensemble of three different models: An auto-regressive model, a machine learning (long short-memory) model, and a SEIR model.

**Forecasts submitted:** Cases


### [US Army Engineering Research and Development Center](https://github.com/erdc-cv19/covid19-forecast-hub) <a name="ERDC"/>

**Model name:** ERDC

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Hospitalization assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Youyang Gu (COVID-Projections)](https://covid19-projections.com/about/) <a name="YYG"/>

**Model name:** YYG

**Intervention assumptions:** The model accounts for individual state-by-state re-openings and responses to increasing cases and their impact on infections and deaths.

**Methods:** SEIS mechanistic model

**Forecasts submitted:** Deaths

