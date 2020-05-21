## Models

- [Auquan Data Science](#Auquan)
- [Columbia University](#Columbia)
- [Covid Act Now](#CAN)
- [Georgia Institute of Technology](#GT)
- [Imperial College, London](#Imperial)
- [Institute of Health Metrics and Evaluation](#IHME)
- [Iowa State University](#ISU)
- [Johns Hopkins University](#JHU)
- [Los Alamos National Laboratory](#LANL)
- [Massachusetts Institute of Technology](#MIT)
- [Northeastern](#MOBS)
- [Notre Dame University](#NotreDame)
- [University of California, Los Angeles](#UCLA)
- [University of Chicago](#UChicago)
- [University of Geneva / Swiss Data Science Center](#Geneva)
- [University of Massachusetts, Amherst](#UMass)
- [University of Texas, Austin](#UT)
- [US Army Engineering Research and Development Center](#ERDC)
- [Youyang Gu (COVID-Projections)](#YYG)

## Model Descriptions

### [Auquan Data Science](https://covid19-infection-model.auquan.com/) (state-level forecasts only) <a name="Auquan"/>

**Model name:** Auquan

**Intervention assumptions:** These projections do not make specific assumptions about which interventions have been implemented or will remain in place.  

**Methods:** Fitted SEIR model

### [Columbia University](https://columbia.maps.arcgis.com/apps/webappviewer/index.html?id=ade6ba85450c4325a12a5b9c09ba796c) <a name="Columbia"/>

**Model name:** Columbia

**Intervention assumptions:** This model is based on assumptions about how levels of social distancing will change in the future. It assumes a 20% reduction in contact rates for each week that stay-at-home orders remain in place or are expected to remain in place. Once a state has re-opened, contact rates are assumed to increase by 5% each week.

**Methods:** Metapopulation SEIR model

### [Covid Act Now](https://covidactnow.org/) (state-level forecasts only) <a name="CAN"/>
**Model name:** CAN

**Intervention assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Fitted SEIR model

### [Georgia Institute of Technology](https://cse.gatech.edu/people/b-aditya-prakash) <a name="GT"/>

**Model name:** GA_Tech

**Intervention Assumptions:** This model assumes that the effects of interventions are reflected in the observed data and will continue going forward.

**Methods:** Deep learning

### [Imperial College, London](https://mrc-ide.github.io/covid19-short-term-forecasts/index.html) <a name="Imperial"/>

**Model name:** Imperial

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Ensembles of mechanistic transmission models, fit to different parameter assumptions.

### [Institute of Health Metrics and Evaluation](https://covid19.healthdata.org/united-states-of-america) <a name="IHME"/>

**Model name**: IHME

**Intervention Assumptions:** Projections are adjusted to reflect differences in aggregate population mobility and community mitigation policies.

**Methods:** Combination of a mechanistic disease transmission model and a curve-fitting approach.

### [Iowa State University](http:/www.covid19dashboard.us) <a name="ISU"/>

**Model name:** ISU

**Intervention Assumptions:** These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.

**Methods:** Nonparametric spatiotemporal model

### [Johns Hopkins University](https:/github.com/HopkinsIDD/COVIDScenarioPipeline) <a name="JHU"/>

**Model name:** JHU

**Intervention Assumptions:** This model assumes that the effectiveness of interventions is reduced after shelter-in-place orders are lifted.

**Methods:** Stochastic metapopulation SEIR model

### [Los Alamos National Laboratory](https://covid-19.bsvgateway.org/) <a name="LANL"/>

**Model name:** LANL

**Intervention assumptions:** This model assumes that currently implemented interventions and the corresponding reductions in transmission will continue, resulting in an overall decrease in COVID-19 deaths.

**Methods:** Statistical dynamical growth model accounting for population susceptibility

### [Massachusetts Institute of Technology](https://www.covidanalytics.io/projections) <a name="MIT"/>

**Model name:** MIT

**Intervention Assumptions:** The projections assume that current interventions will remain in place indefinitely.

**Methods:** SEIR model fit to reported death and case counts

### [Northeastern](https://covid19.gleamproject.org/) <a name="MOBS"/>

**Model name:** MOBS (Laboratory for the Modeling of Biological + Socio-technical Systems)

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Metapopulation, age-structured SLIR model

### [Notre Dame University](https://github.com/confunguido/covid19_ND_forecasting) (state-level forecasts only) <a name="NotreDame"/>

**Model name:** NotreDame

**Intervention assumptions:** The model accounts for each  state’s school-closure and stay-at-home policies.

**Methods:** Agent-based model

### [University of California, Los Angeles](https://covid19.uclaml.org/) <a name="UCLA"/>

**Model name:** UCLA

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** Modified SEIR model

### [University of Chicago](https://github.com/cobeylab/covid_IL) (forecasts for Illinois only) <a name="UChicago"/>

**Model name:** UChicago

**Intervention assumptions:** These forecasts assume that transmission rate will increase by 10% when stay-at-home policies are lifted.

### [University of Geneva / Swiss Data Science Center](https://renkulab.shinyapps.io/COVID-19-Epidemic-Forecasting/) (one-week ahead forecasts only) <a name="Geneva"/>

**Model name:** Geneva

**Intervention assumptions:** The projections assume that social distancing policies in place at the date of calibration are extended for the future weeks.

**Methods:** Exponential and linear statistical models fit to the recent growth rate of cumulative deaths.

### [University of Massachusetts, Amherst](https://reichlab.io/) <a name="UMass"/>

**Model names:** UMass-MB, Ensemble

**Intervention assumptions:**
-	UMass-MB: These projections do not make any specific assumptions about which interventions have been implemented or will remain in place.
-	Ensemble: The national- and state-level ensemble forecasts include models that assume certain social distancing measures will continue and models that assume those measures will not continue.  

**Methods:**
-	UMass-MB: Mechanistic Bayesian compartment model
-	Ensemble: Equal-weighted combination of 2 to 8 models, depending on the availability of national and state-level forecasts. To ensure consistency, the ensemble includes only models with 4 week-ahead forecasts and models that do not assign a significant probability to there being fewer cumulative deaths than have already been reported.

### [University of Texas, Austin](https://covid-19.tacc.utexas.edu/projections/) <a name="UT"/>

**Model name:** UT

**Intervention assumptions:** This model estimates the extent of social distancing using geolocation data from mobile phones and assumes that the extent of social distancing does not change during the period of forecasting. The model is designed to predict confirmed COVID-19 deaths resulting from only a single wave of transmission.

**Methods:** Nonlinear Bayesian hierarchical regression with a negative-binomial model for daily variation in death rates.

### [US Army Engineering Research and Development Center](https://github.com/erdc-cv19/covid19-forecast-hub) <a name="ERDC"/>

**Model name:** ERDC

**Intervention assumptions:** These projections assume that current interventions will not change during the forecasted period.

**Methods:** SEIR mechanistic model

### [Youyang Gu (COVID-Projections)](https://covid19-projections.com/about/) <a name="YYG"/>

**Model name:** YYG

**Intervention assumptions:** The projections assume that strong social distancing policies will remain in place through the projected period.

**Methods:** SEIS mechanistic model.

