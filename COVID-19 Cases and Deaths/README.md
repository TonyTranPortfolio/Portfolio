# COVID-19 Cases and Deaths

You can visit my Public Tableau Dashboard featuring the data from these notebooks at the following [link](https://public.tableau.com/app/profile/tony.tran2362/viz/COVID-19Data_16637479536980/ReportedCOVID-19CasesandDeathsIntheUnitedStatesTracker).

![COVID-19 Dashboard](Image/Dashboard.png)

## Introduction
Coronavirus (COVID-19) is an infectious respiratory disease caused by the SARS-CoV-2 virus. The virus, being highly infectious, sparked a global pandemic and caused mandatory quarantines around the globe. By the end of 2020, vaccines were approved for administration and over time, have proven to decrease the chance of infection and the severity of the symptoms. However, COVID-19 is still an issue to this day and we have seen sporatic spikes in COVID-19 contraction since. COVID-19 has over 6 million world wide confirmed deaths and over 569 million cases of the disease, recorded in July 2022, over the two years the disease has been prevalent. The United States, covered in this project, has over 1 million of those deaths.

This project aims to explore COVID-19 data collected from the CDC and healthdata.gov to analyze previous COVID-19 data, interpret trends between state data, and accurately forecast future cases and deaths in the United States. This notebook, when run, will extract the data straight from the site, updating the model each time it is run. It will also update the Tableau dashboard with its new information, creating an up to date analysis of data each time the notebook it run.

## Data Wrangling and Exploratory Data Analysis
### Data Source

The three datasets are as follows:
- [Covid-19 Reported Patient Impact and Hospital Capacity by State Timeseries collected from healthdata.gov](https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh)
- [Vaccine Distribution and Administration by State collected from the CDC](https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc)
- [Covid Cases and Deaths Over Time collected from the CDC](https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36)

## Modeling

I use a library called [darts](https://unit8co.github.io/darts/) to aid in timeseries forecasting.

![forecast](Image/CasePredictions.png)


