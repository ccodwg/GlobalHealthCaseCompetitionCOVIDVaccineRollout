# Global Health Case Competition: Canada's COVID-19 Vaccine Rollout

## How to download these data

To download all the datasets in this repository, click the big green "Code" button, then click "Download ZIP". Save it to the location of your choice and unzip the contents. All of the CSV files containing the data can be opened using your spreadsheet software or statistical package of choice.

## Included datasets

The following datasets are included in this repository:

* Cases by province (`cases_prov.csv`) and health region (`cases_hr.csv`)

![daily_cases](https://user-images.githubusercontent.com/31170087/130306790-b8848a43-cae1-4bf4-a4ea-09eb19fd7865.png)

* Mortality by province (`mortality_prov.csv`) and health region (`mortality_hr.csv`)

![daily_mortality](https://user-images.githubusercontent.com/31170087/130306797-43cc34c9-cfcd-44b5-8233-e22f87ad5b37.png)

* Tests completed by province (`tests_completed_prov.csv`)

![daily_tests](https://user-images.githubusercontent.com/31170087/130306805-658ba4c8-f55b-4ecb-9ecc-6480298c5f3e.png)

* Hospitalizations (ICU and non-ICU) by province (`hosp_prov.csv`)

![hosp](https://user-images.githubusercontent.com/31170087/130306809-6d0179ad-88f0-4eb1-9f4e-3f1c481d053c.png)

* ICU occupancy by province (`icu_prov.csv`)

![icu](https://user-images.githubusercontent.com/31170087/130306815-814e2c9e-8df5-4897-adfe-1ad6769a43ba.png)

With the exception of hospitalization and ICU numbers, both the cumulative values (`value`) and the daily differences (`value_daily`) are given for each date where data are available.

## Detailed description of data sources

### Cases & mortality

| Province/territory | Data sources                                                                                                                                                                                                                 |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AB                 | - [Government of Alberta](https://www.alberta.ca/stats/covid-19-alberta-statistics.htm) (cases)<br>- [COVID-19 Canada Open Data Working Group](https://opencovid.ca/) (deaths)                                               |
| BC                 | - [Government of British Columbia](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data) (cases)<br>- [COVID-19 Canada Open Data Working Group](https://opencovid.ca/) (deaths)                                         |
| MB                 | - [COVID-19 Canada Open Data Working Group](https://opencovid.ca/)                                                                                                                                                           |
| NB                 | - [COVID-19 Canada Open Data Working Group](https://opencovid.ca/)                                                                                                                                                           |
| NL                 | - [COVID-19 Canada Open Data Working Group](https://opencovid.ca/)                                                                                                                                                           |
| NS                 | - [COVID-19 Canada Open Data Working Group](https://opencovid.ca/)                                                                                                                                                           |
| NT                 | - [Public Health Agency of Canada](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html)                                                                                                   |
| NU                 | - [Public Health Agency of Canada](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html)                                                                                                   |
| ON                 | - [Government of Ontario](https://data.ontario.ca/dataset/status-of-covid-19-cases-in-ontario-by-public-health-unit-phu)                                                                                                     |
| PE                 | - [Public Health Agency of Canada](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html)                                                                                                   |
| QC                 | - [Institut Nationale De Santé Publique Du Québec](https://www.inspq.qc.ca/covid-19/donnees)                                                                                                                                 |
| SK                 | - [Government of Saskatchewan](https://dashboard.saskatchewan.ca/health-wellness/covid-19/cases) (August 4, 2020 and onward)<br>- [Jean-Paul R. Soucy](https://data.gripe/covid-19-in-saskatchewan/) (before August 4, 2020) |
| YT                 | - [Public Health Agency of Canada](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html)                                                                                                   |

### Hospitalizations & ICU

| Province/territory | Data sources                                                                                                                                                                                                 |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AB                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| BC                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| MB                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| NB                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| NL                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| NS                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| NT                 | - These data are not reported by the territory                                                                                                                                                               |
| NU                 | - These data are not reported by the territory                                                                                                                                                               |
| ON                 | - [Government of Ontario](https://data.ontario.ca/dataset/covid-19-cases-in-hospital-and-icu-by-ontario-health-region)                                                                                       |
| PE                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| QC                 | - [Institut Nationale De Santé Publique Du Québec](https://www.inspq.qc.ca/covid-19/donnees) (April 10, 2020 and beyond)<br>- [COVID-19 Tracker Canada](https://covid19tracker.ca) (prior to April 10, 2020) |
| SK                 | - [COVID-19 Tracker Canada](https://covid19tracker.ca)                                                                                                                                                       |
| YT                 | - These data are not reported by the territory                                                                                                                                                               |

### Tests completed

All data on completed COVID-19 tests is from the [Public Health Agency of Canada](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html).

