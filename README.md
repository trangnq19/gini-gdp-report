# Are Richer Countries More Equal?

A reproducible HTML report on income inequality (Gini coefficient) and GDP per capita across countries.

- `report.Rmd`: source of the report (knit to HTML in RStudio)
- `Data/gini_gdp.csv`: processed data from Our World in Data (149 countries, 5 variables)
- `Image/`: screenshot used in Section 4

Data source: https://ourworldindata.org/grapher/gini-coefficient-vs-gdp-per-capita-pip
Processing: removed aggregate rows (World, income groups, urban/rural splits), kept each country's most recent year between 2015 and 2024 with both Gini and GDP per capita available, and kept 5 variables.
