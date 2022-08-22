# Nigeria COVID-19 Data Analysis Using Python

This project was undertaken to understand the impact Coronavirus had on Nigeria. I achieved this through thorough data analysis and visualisation.

## Project Steps

### Step 1 - Data Collection

*I scraped data off the NCDC website to give an up-to-date information on the statistics of the virus as at the time of the project, reshaped it with numpy, and converted it into a dataframe.

*I imported external data off John Hopkin's GitHub repository and converted it into a dataframe.

*I imported some external data(real gdp, budget data etc.) that reflects the impact of covid-19 on Nigeria's economy.

*I derived basic information from the above collected data using the .info() and .head() methods to help understand what I'm dealing with.

### Step2 - Data Cleaning and Exploratory Data Analysis

*I renamed the covid data column and Covid_Recovered_Cases columns, reshaped the DataFrame and added a new column.
*I inspected and converted date object to DateTime format.
*I reset the Covid_Recovered_Cases columns index and retrieved the country Nigeria using the .loc() method.
*I wrote a functions to rename columns, replace subregion Nan with empty space, to reshape the data so that the dates (which are columns in the original data) will be transposed into values, reorder columns and sort rows, to get and clean up the covid-19 datasets.
*I confirmed the length of  functions returned dataset and dropped unnecessary columns.
*I merged certain columns usiung specific columns, using the .melt() method.
*I examined variables: confirmed, dead and recovered.
*I examined missing values and created DataFrame for confirmed, recovered and dead variables.


### Step3 - Data Visualization

*I visualized Nigeria's top 10 states with infections: confirmed, death and discharged cases.
*I plotted a line graph to visualise the number of confirmed. eath and dischrged cases amongst people.
*I assigned a  new cases column to the covid DataFrame and visualised the amount of new cases.
*I visualized the amount of new cases with repective dates.
*I merged the covid_data dataframe and the covid_external dataframe to external_data using the .melt() method with states and visualized two columns in a single chart to weigh covid-19 effects on different areas.
*I visualized a regression plot(regplot) between confirmed cases ans the population index to understand what percentage of the population had been confirmed to have the virus.
*I visualized more charts between columns from the external_data.
*I reshaped the realGDP dataframe using the .melt() method to make it easier to visualize the respective years and quaters on subplots wich I later visualized.
*I compared the different initial budgets to the revised budgets caused by covid-19 within a few Nigerian States

### Suggestions on future work/Improvement plans

*I would love to compare the effects of covid-19 cases in Nigeria to that of other countries and see how it affects the livelihood of people and the economy of nations.
