# covid19---project
Covid COVID-19 dataset has been taken and visualized 
COVID-19 vaccine is a vital preventive step that could aid in the end of the COVID-19 pandemic. COVID-19 vaccinations are now widely accessible in the United States, and the CDC advises that all individuals aged 12 and older be immunized against COVID-19. We sought answers on how COVID-19 vaccination affected individuals.
![image](https://github.com/Sushmitham99/covid19---project/assets/36356157/6d3f9f5a-9848-48d5-8b34-fd1e0069787f)

The Primary Dataset has information regarding COVID19 county-wise vaccination data for the state of Texas. We approached this data to prove five hypotheses using the tool Tableau. The sheets are:
About The Data - explains every column and every unique heading in the data to understand the data better 

By county - 15 columns that segregates data as per doses administered, health condition, age, health care worker, resident and other uniqueness 

By Age, Gender, Race - explains data by gender, age group, race/ethnicity, and doses administered

By Age, Day - number of doses administered per day in all counties by age group 

By County, Age - Vaccines administered at county, age and doses number level 

By County, Race - Break-up of data by race/ethnicity, county, and dose number 
By Vaccination Date - Break-up of data by vaccination date and doses administered
![image](https://github.com/Sushmitham99/covid19---project/assets/36356157/49fd3bc3-aacd-4565-b61c-df4698b1d20d)

The data was cleaned using Excel and Python. Pandas library in python was mainly used for cleaning and Excel’s built-in function was used to remove duplicates. Our original primary dataset consists of information on COVID-19 vaccine data by County. We’ve preprocessed the data and used only the information that was needed for our visualizations and our hypothesis. 
For the booster vaccination doses records after July 2021 were imputed as 0 since the booster shots have started in the month of August,2021.The COVID 19 vaccine data by County dataset records have the count of the people who received booster doses and immunocompromised people who received additional doses.
Median value has been substituted wherever appropriate when the values were missing as this would not affect the distribution of the data. 
![image](https://github.com/Sushmitham99/covid19---project/assets/36356157/2b812c39-2fa9-4ae4-bece-fa8a9a815a3e)

The data consists of 4 major ethnic groups: Asian, Hispanic, Black, and White. With the visualization, we can reject the null hypothesis as we see that the Asian ethnicity has received the least number of booster shots– 427,753. 





