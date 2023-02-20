# Mass shootings in the US: On the rise and deadlier

This project tracks mass shootings in the US from 2014 to 2022. The data for the project was obtained by scraping
the website of [Gun Violence Archive](https://www.gunviolencearchive.org/) which defines mass shooting as an incident where four or more people
have been killed or injured.

*  `scraping.ipynb`: This notebook contains the code used to scrape Gun Violence Archive. Playwright and Beautiful Soup were used for the scraping.
*  `cleaning.ipynb`: This notebook cleans the data obtained via the scraping to make searchable dataframes using pandas.
*  `plotting.ipynb`: This notebook is for exploratory data analysis using pandas and making charts on ggplot2. 

## Findings

The number of mass shootings have almost doubled since 2014 and the incidents have become deadlier. 

## Limitations

Mass shootings can depend on a number of factors such as state demographics (population, age, race, ethnicity, income), state-wise gun laws 
and gun ownership, and several other variables. The analysis does not take these into account because it is difficult to make a methodological choice and 
ajust for one variable (or a few) and leave out others. The analysis has on absolute national and state-wise numbers. And in one case, percentage change. 

## Further 

Data analysis can only achieve so much and the project needs traditional reporting - talking to experts - that makes sense of the trends.

