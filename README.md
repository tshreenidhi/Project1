# Project1
Project 1 Team Member Wes Chiang, Thotadamoole Shreenidhi, Ryan Sambila, Karan Dogra, Desarae Mcglauflin

Initial Questions:

1. What is the ratio of crime between male/female in California?
2. What is the distribution of Crime in California?
3. How did the years of Covid19 affect the Crimes in California?
4. What was the percentage of Crimes in each city?



Question 1 (Process)
1. Retrieve and Downloaded the Data from Crime Data Explorer - Federal Bureau of Investigation for Crime Types happening between 2020-2022
2. Load all 3 years of data in Jupyter
3. Visualize data accuracy with print
4. Correcting Data Type from Object to Int (Getting the , Comma was disrupting python to read the format accurately)
5. Remove the Total Column to ensure data is presented in a better visualized format
6. Create Bar Chart and Pie Graphs Based on the information with the data provided in file.


Result:


Top 5 Crime Types-
1. Crime Against Person
2. Assault Offenses
3. Crime Aganist Property
4. Crime Aganist Society
5. Drug/Narcotic Offenses


Gender with Crime Type Ratio-
Consistent throughout 2020-2022 despite the change in numbers, ratio is staying the same.
_______________________________________________________________
Question 2 (Process)

Result:

_______________________________________________________________
Question 3 (Process)
1. Retrieve and download the hate crime and the covid hopitalization csv files
2. Using pandas load into Jupyter Notebote
3. Created smaller hate crime dataframe to look at indiviual biases.
4. Biasas are muiliple, so replace bias to be a single type  to be able to do better analysis.  Example: Anti-Lesbian to replace with Anti-Gay
5. Review top biasas and look at indiviually also.
6. Create line chart by year to look at hate crimes vs covid hospializations correlation
7. Create scatter chart by month to look at hate crimes vs covid hospializations correlation
Result:
- Hate crimes did significanlty increase during covid on all biasas.
- Anti-Asian Hate crime was the only one that by data you can say became inflated from the influence of covid.  In the last year had a large decrease
- Need to follow a few more years of data to see if other biasas decrease also
- Missing 2023 CA hate crime data to be able to add additional year to data set.  
_______________________________________________________________
Question 4 (Process)
1. Looked for population data to be able to give a hate crime rate in percentage of population.
2. Population data was foudn to be difficult to pair up with crime data to give an accurate percenage

- No Results
