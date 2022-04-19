## Models

- [AIpert](#AIpert)
- [Auquan Data Science](#Auquan)
- [Berkeley Yu Group](#Yu_Group)
- [Bob Pagano](#BPagano)
- [Carnegie Mellon University](#CMU)
- [Center for Disease Dynamics, Economics & Policy](#CDDEP)
- [Columbia University](#Columbia)
- [Columbia University and University of North Carolina](#Columbia-UNC)
- [Covid-19 Simulator Consortium](#Covid19Sim)
- [Covid Act Now](#CAN)
- [Discrete Dynamical Systems](#DDS)
- [Facebook AI Research](#Facebook)
- [Federal Reserve Bank of San Francisco/Wilson](#FRBSF-Wilson)
- [Georgia Institute of Technology, Center for Health and Humanitarian Systems](#GT-CHHS)
- [Georgia Institute of Technology, College of Computing](#GT-DeepCOVID)
- [Google and Harvard School of Public Health](#Google-HSPH)
- [The Hong Kong University of Science and Technology](#HKUST-DNN)
- [IEM](#IEM)
- [Imperial College, London](#Imperial)
- [Institute for Business Forecasting](#IBF)
- [Institute of Health Metrics and Evaluation](#IHME)
- [Iowa State University](#ISU)
- [IQVIA Analytics Center of Excellence](#IQVIA)
- [John Burant](#JCB)
- [Johns Hopkins University, Applied Physics Lab](#JHU-APL)
- [Johns Hopkins University, Applied Physics Lab](#JHUAPL-Gecko)
- [Johns Hopkins University, Center for Systems Science and Engineering](#JHU-CSSE)
- [Johns Hopkins University, Infectious Disease Dynamics Lab](#JHU-IDD)
- [Johns Hopkins University, the University of North Carolina, and Google](#JHU-UNC-Google)
- [Karlen Working Group](#Karlen)
- [Lehigh University Computational Uncertainty Lab](#LUcompUncertLab)
- [LockNQuay](#LNQ)
- [Loïc Pottier](#Prolix)
- [London School of Hygiene and Tropical Medicine](#LSHTM)
- [Los Alamos National Laboratory](#LANL)
- [Los Alamos National Laboratory and Northern Arizona University](#LANL_NAU)
- [Masaryk University](#Masaryk)
- [Massachusetts Institute of Technology, Cassandra](#MIT-Cassandra)
- [Massachusetts Institute of Technology, COVID-19 Policy Alliance](#MIT-CovAlliance)
- [Massachusetts Institute of Technology, Institute for Data, Systems, and Society](#MIT-ISOLAT)
- [Massachusetts Institute of Technology, Laboratory for Computational Physiology](#MIT-LCP)
- [Massachusetts Institute of Technology, Operations Research Center](#MIT-ORC)
- [Microsoft AI](#Microsoft)
- [Northeastern](#MOBS)
- [Notre Dame University](#NotreDame)
- [Oliver Wyman](#OliverWyman)
- [OneQuietNight](#OneQuietNight)
- [Pandemic Central](#PandemicCentral)
- [Predictive Science Inc.](#PSI)
- [Predictive Science Inc.](#PSI-DICE)
- [Qi-Jun Hong](#QJHong)
- [Rensselaer Polytechnic Institute and University of Washington](#RPI-UW)
- [Robert Walraven](#ESG)
- [SignatureScience](#SignatureScience)
- [State University of New York, Upstate Medical University & Syracuse University](#UpstateSU)
- [Steve Hortman](#STH)
- [Steve McConnell](#CovidComplete)
- [Texas Tech University](#TTU)
- [University of Arizona](#UA)
- [University of California, Los Angeles](#UCLA)
- [University of California, Merced](#UCM)
- [University of California, San Diego and Northeastern University](#UCSD-NEU)
- [University of California, Santa Barbara](#UCSB)
- [University of Central Florida](#UCF)
- [University of Chicago](#UChicago)
- [University of Colorado Boulder](#CUBoulder)
- [University of Georgia, Center for the Ecology of Infectious Disease](#UGA-CEID)
- [University of Geneva / Swiss Data Science Center](#Geneva)
- [University of Massachusetts, Amherst](#UMass)
- [University of Michigan](#UM)
- [University of Southern California](#USC)
- [University of Texas, Austin](#UT)
- [US Army Engineering Research and Development Center](#ERDC)
- [Wadhwani AI](#Wadhwani)
- [Walmart Labs Data Science Team](#Walmart)
- [Youyang Gu (COVID-Projections)](#YYG)


## Model Descriptions

### [AIpert](https://github.com/QuocTran/COVID-19/) <a name="AIpert"/>

**Model name:** AIpert

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.  

**Methods:** Piecewise log linear regression model

**Forecasts submitted:** Deaths


### [Auquan Data Science](https://covid19-infection-model.auquan.com/) <a name="Auquan"/>

**Model name:** Auquan

**Intervention assumptions:** These projections do not make specific assumptions about which interventions have been implemented or will remain in place.  

**Methods:** Fitted SEIR model

**Forecasts submitted:** Deaths


### [Berkeley Yu Group](https://covidseverity.com/) <a name="Yu_Group"/>

**Model name:** Yu_Group

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.  

**Methods:** Ensemble of combined linear and exponential predictors (CLEP)

**Forecasts submitted:** Cases


### [Bob Pagano](https://bobpagano.com/)<a name="BPagano"/>

**Model name:** BPagano

**Intervention assumptions:** These projections assume that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** SIR model

**Forecasts submitted:** Deaths


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

**Intervention assumptions:** This model assumes that contact rates will increase 5% during the first week of the forecast period. Following week 1, the reproductive number is then set to 1.0.

**Hospitalization assumptions:** The model uses state-specific hospitalization data, when available. In states without hospitalization data, the model uses the national average value for hospitalization data.

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Columbia University and University of North Carolina](https://github.com/COVID19BIOSTAT/covid19_prediction) <a name="Columbia-UNC"/>

**Model name:** Columbia-UNC

**Intervention assumptions:** This model assumes that transmission intensity will peak in early July and then gradually decline.

**Methods:** Statistical survival-convolutional model

**Forecasts submitted:** Cases, deaths


### [Covid-19 Simulator Consortium](https://www.covid19sim.org/) <a name="Covid19Sim"/>

**Model name:** Covid19Sim

**Intervention assumptions:** This model is based on assumptions about how levels of social distancing will change in the future.

**Hospitalization assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Covid Act Now](https://covidactnow.org/) <a name="CAN"/>

**Model name:** CAN

**Intervention assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Fitted SEIR model

**Forecasts submitted:** Hospitalizations, deaths


### [Discrete Dynamical Systems](https://dds-covid19.github.io/index.html) <a name="DDS"/>

**Model name:** DDS

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Bayesian hierarchical model

**Forecasts submitted:** Cases, deaths


### [Facebook AI Research](https://ai.facebook.com/research/publications/neural-relational-autoregression-for-high-resolution-covid-19-forecasting/)<a name="Facebook"/>

**Model name:** Facebook

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** A machine learning model, combined with an auto-regressive model

**Forecasts submitted:** Cases


### [Federal Reserve Bank of San Francisco/Wilson](https://www.frbsf.org/economic-research/indicators-data/covid-19-forecasts-by-county/) <a name="FRBSF-Wilson"/>

**Model name:** FRBSF-Wilson

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward. 

**Methods:** An SIR-derived econometric county panel data model with transmission rate assumed to be function of weather and mobility

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

**Forecasts submitted:** Hospitalizations, deaths


### [Google and Harvard School of Public Health](https://cloud.google.com/blog/products/ai-machine-learning/google-cloud-is-releasing-the-covid-19-public-forecasts/)<a name="Google-HSPH"/>

**Model name:** Google-HSPH

**Intervention assumptions:** These forecasts implement changes to future population mobility in order to predict COVID-19 transmission intensity.

**Methods:**  SEIR model fit with machine learning

**Forecasts submitted:** Cases, hospitalizations, deaths


### [The Hong Kong University of Science and Technology](https://cfong32.github.io/HKUST-DNN/)<a name="HKUST-DNN"/>

**Model name:** HKUST-DNN

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:**  Deep neural networks trained on observed deaths, cases, and hospitalizations to forecast state-level cumulative deaths

**Forecasts submitted:** Deaths


### [IEM](https://iem-modeling.com/)<a name="IEM"/>

**Model name:** IEM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SEIR model with machine learning.

**Forecasts submitted:** Cases


### [Imperial College, London](https://mrc-ide.github.io/covid19-short-term-forecasts/index.html) <a name="Imperial"/>

**Model name:** Imperial

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Ensembles of mechanistic transmission models, fit to different parameter assumptions

**Forecasts submitted:** Deaths


### [Institute for Business Forecasting](http://demand-planning.com/2020/05/01/coronavirus-forecasts-2/)<a name="IBF"/>

**Model name:** IBF

**Intervention Assumptions:** These projections do not make specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Combination of a mechanistic disease transmission model and a curve-fitting approach

**Forecasts submitted:** Cases, deaths


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

**Forecasts submitted:** Cases, deaths


### [IQVIA Analytics Center of Excellence](https://www.iqvia.com/landing/analytics-center-of-excellence/)<a name="IQVIA"/>

**Model name:** IQVIA

**Intervention Assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Spatiotemporal attention network model

**Forecasts submitted:** Cases


### [John Burant](https://github.com/JohnBurant/COVID19-PRM/) <a name="JCB"/>

**Model name:** JCB

**Intervention Assumptions:** The incidence of COVID-19 in the population determines the strength of and resulting impact of control measures in the future.

**Methods:** Phenomenological statistical model

**Forecasts submitted:** Deaths


### [Johns Hopkins University, Applied Physics Lab](https://buckymodel.com/) <a name="JHU-APL"/>

**Model name:** JHU-APL

**Intervention Assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Johns Hopkins University, Applied Physics Lab](https://github.com/reichlab/covid19-forecast-hub/blob/master/data-processed/JHUAPL-Gecko/metadata-JHUAPL-Gecko.txt) <a name="JHUAPL-Gecko"/>

**Model name:** JHUAPL-Gecko

**Intervention Assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** SARIMA time series model (1,1,0)x(1,1,0,7) with anomaly detector applied to confirmed hospital admissions since 09/01/2020. 

**Forecasts submitted:** Hospitalizations


### [Johns Hopkins University,  Center for Systems Science and Engineering](https://systems.jhu.edu/research/public-health/predicting-covid-19-risk/) <a name="JHU-CSSE"/>

**Model name:** JHU-CSSE

**Intervention Assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Machine learning

**Forecasts submitted:** Cases, deaths


### [Johns Hopkins University, Infectious Disease Dynamic Lab](https://github.com/HopkinsIDD/COVIDScenarioPipeline/) <a name="JHU-IDD"/>

**Model name:** JHU-IDD

**Intervention Assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Hospitalization Assumptions:** Daily hospitalizations are estimated from predictions of daily cases. A standard proportion is applied to all states.

**Methods:** Metapopulation SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Johns Hopkins University, University of North Carolina, and Google](https://github.com/HopkinsIDD/EpiForecastStatMech/) <a name="JHU-UNC-Google"/>

**Model name:** JHU-UNC-Google

**Intervention Assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** This forecast is an ensemble of two different models: A multiplicative growth model and a curve fitting model.

**Forecasts submitted:** Cases, deaths


### [Karlen Working Group](https://pypm.github.io/home/) <a name="Karlen"/>

**Model name:** Karlen

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Hospitalization assumptions:** The model uses state-specific hospitalization data. New hospitalizations are estimated from these data, or from the estimated number of new infections that will occur in each location.

**Methods:** Discrete time difference equations

**Forecasts submitted:** Cases, hospitalizations, deaths


### [LockNQuay](https://www.kaggle.com/sasrdw/locknquay) <a name="LNQ"/>

**Model name:** LNQ

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Machine learning

**Forecasts submitted:** Cases, deaths


### [Loïc Pottier](https://cp.lpmib.fr/medias/covid19/_synthese.html) <a name="Prolix"/>

**Model name:** Prolix

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Offsets obtained by correlations, best linear approximation of reproduction rates (using vaccination  approximation) by least euclidean distance, and linear prediction. 

**Forecasts submitted:** Cases, hospitalizations, and deaths


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


### [Los Alamos National Laboratory and Northern Arizona University](https://github.com/lanl/COVID-19-Predictions) <a name="LANL_NAU"/>

**Model name:** LANL_NAU

**Intervention assumptions:** This model assumes interventions in place on the first day of the forecast will remain in place for the next four weeks. 

**Hospitalization Assumptions:** None

**Methods:** Compartmental model consisting of ordinary differential equations (ODEs) describing the dynamics of 40 populations (state variables). The model quantified the impact of non-pharmaceutical interventions on COVID-19 transmission dynamics, and captures vaccination of susceptible and recovered persons and infected non-quarantined persons without symptoms at a time-varying per capita rate.

**Forecasts submitted:** Cases

### [Lehigh University Computational Uncertainty Lab](https://github.com/computationalUncertaintyLab) <a name='LUcompUncertLab'/>

**Model name:** LUcompUncertLab

**Intervention assumptions:** None

**Hospitalization Assumptions:** None

**Methods:** A Bayesian Vector Auto Regression model

**Forecasts submitted:** Hospitalizations, deaths


### [Masaryk University](https://krausstat.shinyapps.io/covid19global/) <a name='Masaryk'/>

**Model name:** Masaryk

**Intervention assumptions:** The projections assume that current interventions will remain in place indefinitely. 

**Methods:** An auto-regressive model

**Forecasts submitted:** Cases, deaths


### [Massachusetts Institute of Technology, Cassandra](https://github.com/oskali/mit_cassandra/) <a name="MIT-Cassandra"/>

**Model name:** MIT-Cassandra

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** This forecast is an ensemble of four different models: a Markov Decision Processes model, two different time series models, and C-SEIRD model

**Forecasts submitted:** Cases


### [Massachusetts Institute of Technology, COVID-19 Policy Alliance](https://www.covidalliance.com/) <a name="MIT-CovAlliance"/>

**Model name:** MIT-CovAlliance

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** SIR model 

**Forecasts submitted:** Cases, deaths 


### [Massachusetts Institute of Technology, Institute for Data, Systems, and Society](https://covidpredictions.mit.edu/) <a name="MIT-ISOLAT"/>

**Model name:** MIT-ISOLAT

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** Mixture model

**Forecasts submitted:** Cases, deaths 


### [Massachusetts Institute of Technology, Laboratory of Computational Physiology](https://github.com/sakethsundar/covid-forecaster/) <a name="MIT-LCP"/>

**Model name:** MIT-LCP

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** Machine learning

**Forecasts submitted:** Deaths


### [Massachusetts Institute of Technology, Operations Research Center](https://www.covidanalytics.io/projections) <a name="MIT-ORC"/>

**Model name:** MIT-ORC

**Intervention Assumptions:** The projections assume that interventions will be reinstated if transmission reaches certain thresholds.

**Methods:** SEIR model 

**Forecasts submitted:** Cases, deaths


### [Microsoft AI](https://www.microsoft.com/en-us/ai/ai-for-health/) <a name="Microsoft"/>

**Model name:** Microsoft (formerly: MSRA)

**Intervention Assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SEIR model on a spatiotemporal network

**Forecasts submitted:** Cases, deaths


### [Northeastern University, Laboratory for the Modeling of Biological and Socio-technical Systems](https://covid19.gleamproject.org/) <a name="MOBS"/>

**Model name:** MOBS

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Metapopulation, age-structured SLIR model

**Forecasts submitted:** Hospitalizations, deaths


### Notre Dame University <a name="NotreDame"/>

**Model names:** 
  
- [NotreDame-Mobility](https://github.com/TAlexPerkins/covid19_NDmobility_forecasting/)
- [NotreDame-FRED](https://github.com/confunguido/covid19_ND_forecasting/)

**Intervention assumptions:** These forecasts assume that population-level mobility is a reliable proxy for adherence to social distancing, and that recent trends in mobility will continue over the coming weeks.

**Methods:** 
  
- NotreDame-Mobility: SEIR model fit to data on deaths, test positivity, and population mobility
- NotreDame-Fred: Agent-based model

**Forecasts submitted:** Deaths


### [Oliver Wyman](https://pandemicnavigator.oliverwyman.com/) <a name="OliverWyman"/>

**Model name:** Oliver Wyman

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Time-dependent SIR model for detected and undetected cases

**Forecasts submitted:** Cases, deaths


### [OneQuietNight](https://github.com/One-Quiet-Night/COVID-19-forecast/)<a name="OneQuietNight"/>

**Model name:** OneQuietNight

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Machine learning models.

**Forecasts submitted:** Cases


### [Pandemic Central](https://itsonit.com) <a name="PandemicCentral"/>

**Model name:** PandemicCentral

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Random forest machine learning model

**Forecasts submitted:** Cases


### [Predictive Science Inc.](https://github.com/predsci/DRAFT) <a name="PSI"/>

**Model name:** PSI

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Stochastic SEIRX model

**Forecasts submitted:** Deaths


### [Predictive Science Inc.](https://github.com/predsci/DICE4) <a name="PSI-DICE"/>

**Model name:** PSI-DICE

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SEIR model

**Forecasts submitted:** Hospitalizations


### [Qi-Jun Hong](https://qjhong.github.io/) <a name="QJHong"/>

**Model name:** QJHong

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Machine learning using case data and mobility data

**Forecasts submitted:** Cases, deaths


### [Rensselaer Polytechnic Institute and University of Washington](http://medrxiv.org/content/10.1101/2020.07.25.20162016v1) <a name="RPI-UW"/>

**Model name:** RPI-UW

**Intervention assumptions:** These projections calibrate the rate of transmission to the average rate of population mobility since the start of the epidemic and assume that this relationship will not change in the next four weeks.

**Methods:** SIR model fit to mobility data

**Forecasts submitted:** Deaths


### [Robert Walraven](http://rwalraven.com/COVID19/) <a name="ESG"/>

**Model name:** ESG

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Fitting reported data to multiple skewed gaussian distributions

**Forecasts submitted:** Cases, deaths


### [Signature Science](http://www.signaturescience.com/)<a name="SignatureScience"/>

**Model name:** SignatureScience

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Autoregressive time-series model

**Forecasts submitted:** Cases, deaths


### [State University of New York, Upstate Medical University & Syracuse University](https://ylzhang29.github.io/UpstateSU-GRU-Covid/)<a name="UpstateSU"/> 

**Model name**: UpstateSU

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Machine learning

**Forecasts submitted:** Cases, deaths


### [Steve Horstman](https://public.tableau.com/profile/covid19model#!/vizhome/COVID-19DeathProjections/LatestUSStateCOVID-19DeathModels/) <a name="STH"/>

**Model name:** STH

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Statistical growth model

**Forecasts submitted:** Deaths


### [Steve McConnell](https://stevemcconnell.com/covidcomplete/)<a name="CovidComplete"/>

**Model name:** CovidComplete

**Intervention assumptions:**  This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Statistical prediction model

**Forecasts submitted:** Deaths


### [Texas Tech University](https://github.com/fvbttu/squider/)<a name="TTU"/>

**Model name:** TTU

**Intervention assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** SIR model

**Forecasts submitted:** Cases


### [University of Arizona](https://jocelinelega.github.io/EpiGro/) <a name="UA"/>

**Model name:** UA

**Intervention assumptions:** This model assumes that current interventions will remain in effect for at least four weeks after the forecasts are made.

**Methods:** SIR model with data assimilation

**Forecasts submitted:** Deaths


### [University of California, Los Angeles](https://covid19.uclaml.org/) <a name="UCLA"/>

**Model name:** UCLA

**Intervention assumptions:** This model assumes that contact rates will increase as states reopen. The increase in contact rates is calculated for each state.

**Hospitalization Assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** Modified SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [University of California, Merced](https://mechatronics.ucmerced.edu/covid19) <a name="UCM"/>

**Model name:** UCM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:**  SEIR model

**Forecasts submitted:** Deaths


### [University of California, San Diego and Northeastern University](https://sites.google.com/view/yianma/epidemiology/)<a name="UCSD-NEU"/>

**Model name:** UCSD-NEU

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Age-structured metapopulation model with deep learning

**Forecasts submitted:** Deaths


### [University of California, Santa Barbara](https://github.com/Gandor26/covid-open/)<a name="UCSB"/>

**Model name:** UCSB

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Hospitalization Assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** An attention mechanism (deep learning) time series model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [University of Central Florida](https://github.com/UCF-AEM/UCF-AEM)<a name="UCF"/>

**Model name:** UCF

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SEIR model informed with with ensemble neural networks 

**Forecasts submitted:** Cases


### [University of Chicago](https://github.com/cobeylab/covid_IL) (forecasts for Illinois only) <a name="UChicago"/>

**Model name:** UChicago

**Intervention assumptions:** These forecasts assume that transmission rate will increase by 10% when stay-at-home policies are lifted.

**Methods:** SEIR model

**Forecasts submitted:** Deaths


### [University of Colorado Boulder](https://geohai.github.io/covid-lstm/) <a name="CUBoulder"/>

**Model name:** CUBoulder

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Our model is a stacked LSTM deep learning-based model using a multivariate time series input with a temporal lag of 9 weeks.

**Forecasts submitted:** Cases


### [University of Georgia, Center for the Ecology of Infectious Disease](https://github.com/e3bo/random-walks) <a name="UGA-CEID"/>

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

**Model names:** UMass-MB, Ensemble, UMass-TE

**Intervention assumptions:**
-	UMass-MB: These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.
-	Ensemble: The ensemble forecasts include all submitted forecasts, derived from models that assume certain social distancing measures will continue and models that assume those measures will not continue. 
-	UMass-TE: These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:**
-	UMass-MB: Mechanistic Bayesian compartment model
-	Ensemble: The ensemble is a combination of 4 to 20 models, depending on the availability of forecasts for each location. To ensure consistency, the ensemble includes only models with 4 week-ahead forecasts.
-	UMass-TE: Trends Ensemble model

**Forecasts submitted:** Cases, deaths


### [University of Michigan](https://gitlab.com/sabcorse/covid-19-collaboration) <a name="UM"/>

**Model name:** UM

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Ridge regression

**Forecasts submitted:** Cases, deaths


### [University of Southern California](https://scc-usc.github.io/ReCOVER-COVID-19/#/) <a name="USC"/>

**Model name:** USC

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Hospitalization assumptions:** The number of new hospitalizations per day are estimated from the number of infections.

**Methods:** SIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [University of Texas, Austin](https://covid-19.tacc.utexas.edu/projections/) <a name="UT"/>

**Model name:** UT

**Intervention assumptions:** This model estimates the extent of social distancing using geolocation data from mobile phones and assumes that the extent of social distancing does not change during the period of forecasting. The model is designed to predict confirmed COVID-19 deaths resulting from only a single wave of transmission.

**Methods:** Nonlinear Bayesian hierarchical regression with a negative-binomial model for daily variation in death rates

**Forecasts submitted:** Deaths


### [University of Virginia](https://biocomplexity.virginia.edu/)<a name="UVA"/>

**Model name:** UVA

**Intervention assumptions:** There are two different assumptions influencing this ensemble model. Two of the three models assume that the effects of interventions are reflected in the observed data and will continue going forward, while the third model assumes that interventions will change in the future.

**Methods:** This forecast is an ensemble of three different models: An auto-regressive model, a machine learning (long short-memory) model, and a SEIR model.

**Forecasts submitted:** Cases


### [US Army Engineering Research and Development Center](https://github.com/erdc-cv19/seir-model/) <a name="ERDC"/>

**Model name:** ERDC

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Hospitalization assumptions:** The number of new hospitalizations per day are estimated from the number of infections, using state-specific hospitalization rates.

**Methods:** SEIR model

**Forecasts submitted:** Cases, hospitalizations, deaths


### [Walmart Labs Data Science Team](https://github.com/ivan-ji-walmart/covid19-forecast-hub) <a name="Walmart"/>

**Model name:** Walmart

**Intervention assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Logistic growth

**Forecasts submitted:** Deaths


### [Wadhwani AI](https://www.wadhwaniai.org/)<a name="Wadhwani"/>

**Model name:** Wadhwani

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Bayesian SEIR model

**Forecasts submitted:** Cases, deaths


### [Youyang Gu (COVID-Projections)](www.covid19-projections.com/) <a name="YYG"/>

**Model name:** YYG

**Intervention assumptions:** The model accounts for individual state-by-state re-openings and responses to increasing cases and their impact on infections and deaths.

**Methods:** SEIR model with machine learning for parameter estimation

**Forecasts submitted:** Deaths

