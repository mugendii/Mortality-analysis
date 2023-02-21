# Mortality-analysis
The dataset contains information about deaths as a result of covid-19 as well as excess deaths.

1) Create a DataFrame that consists of the following columns: (1) location; (2) deaths in 2020; (3)deaths in 2019; (4) the difference between deaths in 2020 and 2019. The location column should include the name of the respective country.
2) Find all the countries showing excess deaths. Excess deaths is defined as the difference between the deaths occurred in a specific week in 2020 vs 2019. Hint: the diff between 2020 and 2019 has to be greater than 0.
3) For every country, find the top-5 weeks with the highest number of excess deaths.
4) For each country, find which year had the lowest mortality.
5) For each country, find which months had the highest mortality. You can assume that a month consists of all the rows that contain a date of that month (even if the measurements refer to theprevious month). 
For instance, 2020-02-02 should be considered as containing data for February. Note that the format is year-month-day
