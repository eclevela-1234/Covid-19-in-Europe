![image](https://user-images.githubusercontent.com/79372665/134965605-787e84e3-b9ae-45f6-aa78-70b4e84506ab.png)

# Team GEM Project

## Team Members
* Gina Freed, Eliot Cleveland, Marc Leslie

## Presentation
[Download Powerpoint](https://github.com/eclevela-1234/Covid-19-in-Europe/blob/main/Covid-19%20Presentation%20Team%20GEM.pptx)

## Project Questions
* What national-level factors correlate with rates of COVID-19 infections, deaths, and vaccinations?  
* And when those national-level factors don't really work out so well, what _else_ can we look at that may correlate?

## Dependent Variables
* COVID-19 cases per million population
* COVID-19 deaths per million population
* Persons vaccinated per hundred population
* Total population
* (Data Source: https://ourworldindata.org/coronavirus)

## Independent Variables
* **GDP**: monetary measure of the market value of all the goods and services produced in a country in a year
* **Human Development Index (HDI)**: Published by United Nations Development Programme (http://hdr.undp.org/en/content/human-development-index-hdi), an index that combines life expectancy at birth, expected years of schooling, mean years of schooling, and GNI per capita
* **The Corruptions Perception Index**: Published by Transparency International (https://www.transparency.org) which ranks and scores 180 countries by their "perceived levels of public sector corruption."
* **Quality of Life Index**: Published by Numbeo (https://www.numbeo.com/quality-of-life/rankings_by_country.jsp) this index scores countries by measures such as health care access and quality, cost of living, and purchasing power. 

## First Steps (or - how our hopes were dashed)
1. Data set cleaned to remove certain columns and to create a cumulative number of COVID cases and deaths.
2. We realized that the vaccination data is not adequate for analysis - very few countries reporting the data and just not enough information to work with.
3. Scatterplots were run to see if our independent variables correlated with our dependent variables.  This did not yield enough fruit to keep this line of analysis going.
4. We realized that the level of analysis is just too _big_.  GDP is too broad a measure; cases or deaths by country 

## Now what?
It felt like it was time to drill down to a smaller unit of geography.  Europe had the most normal distribution of cases, and Europe also has a large number of countries with a variety of socio-economic factors that may correlate with COVID cases or deaths.  

## Europe
### Independent Variables
* Much like our analysis with all countries, we found little to no correlation with GDP, HDI, or the Corruptions Perception Index.
### Schengen Regions
* We hoped that dividing Europe into Schengen Regions (where free travel access is and is not permitted) may find some correlation, but it did not (p-value of .516).
### Quality of Life Index
* Surely factors such as health care access, cost of living, and overall quality of life would impact COVID cases or deaths, right?  They did not.  
### Geo-political Regions
* We separated Europe into four geo-political regions: Northern, Southern, Eastern, and Western.  
* This analysis showed that Northern Europe indeed had less COVID cases and deaths (even with Sweden as an outlier) than other areas of Europe.

## Conclusions/Further Research
* There are differences between countries regarding COVID cases and deaths - the challenge is finding the right level of analysis.
* It seems logical that there is a link between wealth and health outcomes, but this correlation does not show up when comparing nations against each other, nor for extremely broad factors such as GDP.
* A lingering issue is the reliability of data - reporting on COVID cases and deaths has a wide variability due to circumstances like access to testing, access to accurate cause of death determination, and government efforts to hide the total number of cases.
* While vaccine data was not substantial in this dataset, this research will be possible as more countries vaccinate and report this data.

