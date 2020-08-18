# COVID Data Analysis and Visualization - April 2020

## Prompt: How are different countries affected by the spread of the virus?

## Sub-prompt: Is there a relationship between countries' healthcare system development and their management of COVID 19?

## Data Sources

 - WHO COVID 19 Global Data Cases - April 19
 - WHO GDP % Expenditure on Health by Country 2005-2015
 - WHO Health Care Professsionals to 10,000 Population by Country 2020
 - WHO Child Immunization Estimates 2018
 - WHO Human Development Index by Country 2020

## Disclaimer

- In the WHO GDP % expenditure on health database, the assumption is that the numbers have not changed significantly between 2015 to present.
- In all databases, null values are ignored.
- The COVID 19 data covers January through April 20, 2020. No data prior to this timeframe has been analyzed. 

## Exploratory Analysis - 19/4/20

### Sum of Confirmed and Death Cases in Countries 

In the first glance, the ratio of death to confimred cases do not seem to be the same across countries. For instance this ratio is much higher in countries like Spain and Italy compared to Germany.

![Maps.png](https://github.com/spogoff/COVID_data_analysis_Apr20/blob/master/Assets/Maps.png?raw=true)

### Growth Patterns of Confimred and Death Cases in Countries with Most Cases

While most countries with highest reported cases follow the same pattern of growth in their total numbers, China and Iran seem to have flattened their curves much more quickly than the rest. This could potentially indicate a drop in testing and/or reporting rather than controling the spread of the virus.

![Running_sum_death_confirmed.png](https://github.com/spogoff/COVID_data_analysis_Apr20/blob/master/Assets/Running_sum_death_confirmed.png?raw=true)

 
