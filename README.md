# Beer Consumption vs. Cancer Correlation
Does beer consumption affect your chance of getting cancer?

## Project Description
Cancer is a disease of genetic mutation and also that environment can play a huge role, e.g. food consumption, life habits, etc. In this project, I would like to understand if there is a correlation between beer consumption and chance of getting cancer. Will a person who drinks beer more than average have a higher chance of getting cancer? I will analyze global cancer data by country compared with beer consumption to see if we can find correlation that might support the claim.

## Data Description
1. The CI5 database from the World Health Organization contains incidence rates from 443 cancer registries in 65 countries for cancers diagnosed from 2008 to 2012, for all cancers and 28 major types. There is one with population metrics, and one for the cancer cases reported. Population data includes columns for Registry (reporting location), Year, Sex, Total population, and remaining columns are the breakdowns by age range (every 5 years). The Case files include columns to indicate the Registry, Year, Sex, Cancer type code, and the same 5 year age range counts.
2. The Our World in Data site provides a chart and downloadable .csv of the beer consumption per person data from 189 countries from 1960 to 2015. It contains average annual per capita beer consumption which measured in liters of pure alcohol. Beer contains around 5% of pure alcohol per volume so that one liter of beer contains 0.05 liters of pure alcohol. This means that 5 liters of pure alcohol equals 100 liters of beer.

## Prepare the Data
1. Cancer statistics are reported reginally by "registry". The "registry" contains combination of areas, race, states and time frame which were seperated by coma, semicolon and asterisk. The data set was cleaned to only include national level data with standerdized format.
2. The cancer data set is aggregated from 2008-2012, so the cases of cancer was divided by 5 for an annual average for this time period.
3. Beer consumption per person was aggregated by country for 2008.
4. Weighted averages were used for the cancer incidence rate by population sample size.

### Sample Data



### After transformation


