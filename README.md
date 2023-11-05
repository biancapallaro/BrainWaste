# Brain Waste in Europe:

This repository has data and visualizations supporting my hypothesis: "Non-EU citizens are more affected by brain waste than citizens of other EU countries, particularly women" 
The analysis was completed on November 5, 2023. 

## Data

The analysis explores the following datasets from Eurostat, the statistical office of the European Union:

- [Unemployment rates by sex, age and citizenship (%)](https://ec.europa.eu/eurostat/databrowser/view/lfsa_urgan__custom_8307744/default/table?lang=en)
- [Employment rates by sex, age and citizenship (%)](https://ec.europa.eu/eurostat/databrowser/view/lfsa_ergan__custom_8308004/default/table?lang=en)
- [Unemployment rates by sex, age, migration status, citizenship and educational attainment level](https://ec.europa.eu/eurostat/databrowser/view/lfsa_urganedm__custom_8309847/default/table?lang=en)
- [Over-qualification rates by citizenship](https://ec.europa.eu/eurostat/databrowser/view/lfsa_eoqgan/default/table?lang=en)
- [Foreign-born population by main obstacle to get a suitable job, sex, age, country of birth and educational attainment level](https://ec.europa.eu/eurostat/databrowser/view/lfso_21obst01/default/table?lang=en)

## Analysis
I used Pandas built-in functions and the Altair-viz library to examine the datasets. I limited my analysis to age group 20–64 years following the steps of the EU Action Plan on Integration and Inclusion 2021–2027, and used the most updated data available. Most of the analysis focuses solely on EU27 countries (from 2020) except the reporting country, Reporting country, Non-EU27 countries (from 2020) nor reporting country, sex, and educational attainment. 

Please find the rendered version of the Jupyter notebook [here](https://nbviewer.org/github/biancapallaro/BrainWaste/blob/main/Brain%20Waste%20in%20Europe.ipynb) and the raw data [here](https://tinyurl.com/5n8nbpjb)
