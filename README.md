# data-v-project
Data Vizualization WS2021
Introduction 
Covid-19 has sparked various institution to come up with their own prediction.

Models predicting the potential spread of the COVID-19 pandemic have become a fixture of life. Yet each model tells a different story about the loss of life to come, making it hard to know which one is “right.” These models provide us with bunch of precise possibilities. 

Sources:
Data is extracted from verified source such as git hub, health data gov, etc. 

  1. git repository - https://github.com/PaulFenton/usa-geojson/tree/master/data
  2. Health data is taken from  HealthData.gov https://healthdata.gov/dataset/united-states-covid-19-cases-and-deaths-state-over-time
  3. File translation - https://filezilla-project.org/
  4.Us states.topojason - https://www.jsdelivr.com/

 
 Licences: 
 1. https://github.com/PaulFenton/usa-geojson/blob/master/LICENSE
 2. https://www.usa.gov/government-works


Models implemented in development 
COVIDAnalytics-DELPHI 
This model predicts based on an SEIR model augmented with under detection  and interventions. Projections account for reopening and assume interventions would  be re-enacted if cases continue to climb.

covidhub-esemble
An ensemble, or model average, of submitted forecasts to the COVID-19 Forecast  Hub.

Epiforecasts-ensemble1
A deaths forecast using a mean ensemble of three different models: An Rt  based forecast, a timeseries forecast using deaths only and a timeseries forecast  using deaths and cases.

Notredame-mobility
This is an ensemble of nine models that are identical except that they are  driven by different mobility indices from Apple and Google. The model underlying  each is a deterministic, SEIR-like model.

OliverWyman-Navigator
Oliver Wyman's Pandemic Navigator provides forecasts & scenario analysis  for Detected and Undetected cases and death counts following a compartmental formulation  with non-stationary transition rates.

Additional references
https://github.com/youyanggu/covid19-forecast-hub-evaluation/tree/master/global
https://github.com/youyanggu/covid19-forecast-hub-evaluation
https://github.com/reichlab/covid19-forecast-hub/tree/master/data-processed
http://www.healthdata.org/covid/data-downloads
https://epiforecasts.io/covid/posts/national/germany/ https://datahub.io/core/covid-19#data


