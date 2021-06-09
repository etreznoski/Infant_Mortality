### Team Name: Delightful Street Artists
### Team Members: Isabelle DeMartin, Elizabeth Sanchez & Chelsea Chaussee

#### Tableau Public: https://public.tableau.com/app/profile/chelsea.chaussee/viz/InfantMortality2015-2019/OurAnalysis

In this project we examine infant mortality data in the United States and explore the relationship between infant mortality rates and socio-economic and demographic factors including poverty, education and race.

According to the CDC infant mortality is defined as the death of an infant before their first birthday. Infant mortality rate is the number of infant deaths for every 1,000 live births.*
We chose to study infant mortality in the US because despite the fact that the infant mortality rate has shown a consistent downward trend since the early 1900s, compared to other developed nations the US still has a higher infant mortality rate. For example, in 2015 among all OECD countries, the US ranked 31sd out of 36 countries and in 2018 the US ranked 33rd with only Chile, Turkey and Mexico ranking lower.** OECD is the Organization for Economic Cooperation and Development and generally consists of countries with high-income economies and are regarded as developed countries.

Initially we wanted to investigate infant mortality from a global perspective but we were not able to find appropriate data sources. Instead we sourced data from the CDC to pull infant mortality data by state from 2015-2019 and used the census API to extract demographic and socio-economic data. We used jupyter notebooks for our ETL and machine learning processes. We used a Tableau Public story to display our data.

*https://www.americashealthrankings.org/learn/reports/2018-annual-report/findings-international-comparison
**https://www.cdc.gov/reproductivehealth/maternalinfanthealth/infantmortality.htm

Data Sources:

CDC infant mortality data: https://www.cdc.gov/nchs/pressroom/sosmap/infant_mortality_rates/infant_mortality.htm

Demographic and socio-economic data:
See: https://github.com/datamade/census for library documentation
See: https://gist.github.com/afhaque/60558290d6efd892351c4b64e5c01e9b for labels

State names and abbreviations csv: https://worldpopulationreview.com/states/state-abbreviations
