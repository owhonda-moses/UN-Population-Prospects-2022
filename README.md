# UN World Population Prospects 2022
##### _by Owhonda Moses_


## INTRODUCTION

> This data set contains 20,596 UN annual population estimates from the year 1950 to date as well as
22,598 medium projections for World population up to the year 2100. Included in the dataset are
64 demographic indicators as of July 2022 for 236 countries, including Total population, Natural change,
Net Migration rate, Population density, Life expectancy among others. The dataset can be found on the website
of the Population Division of the United Nations Department of Economic and Social Affairs
[here](https://population.un.org/wpp/Download/Standard/MostUsed/) along with feature documentation.
I split the dataset into two in Microsoft Excel - one for projected population and another for historical
population, and carried out preliminary wrangling using Python. After cleaning the datasets and subsetting
by country, the data was trimmed down to 38 variables with 16,992 annual estimates and 18,644 medium
projections.
>> The clean datasets were stored in CSV format and imported into Tableau for analysis using maps. Key indicators
of interest include `Total Population`, `Natural Change`, `Population Density`, `Net Migration Rate`,
`Population Sex Ratio`, `Population Growth Rate`, `Total Fertility Rate`, `Life Expectancy at Birth`,
`Crude Birth Rate` and `Crude Death Rate`.


## Key Insights for Interactive Dashboards

After combining both datasets in Tableau, I built interactive [dashboards](https://public.tableau.com/views/UNWorldPopulationProspects2022/TotalPopulation?:language=en-US&:display_count=n&:origin=viz_share_link)
to visualize key indicators of interest by region types for each year between 1950 and 2100.
Scatterplots were used to present `Total Fertility Rate`, `Life Expectancy at Birth`,
`Crude Birth Rate` and `Crude Death Rate`, while maps were used for other key demographic indicators.
Few other indicators were introduced using tooltip.

I made sure to use simple and perspicuous color palettes for color legends of each quality variable for good
readabilty.
>_According to projections, India would have become the most populous country
in the World by the end of the decade, and China's population will continuously reduce to about half of it's
current population by the end of the century._


#### PACKAGES USED:

- Jupyter notebook
- Python _(pandas)_
- Tableau
- Excel

_Notable references for this project include -_

- https://www.iban.com/country-codes
- https://www.un.org/ohrlls/
- https://unctad.org/topics
- http://data.un.org/Glossary.aspx
- https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups
- https://community.tableau.com/s/explore-forums
- https://stackoverflow.com/
