# Analysis-of-the-American-Community-Survey-Data
Every Year the US Census Bureau conducts a nationwide American Community Survey. Demographic and Housing data is collected to allow local and federal authorities to obtain information on education, healthcare, socio-economics, etc.
This report makes use of the Public Use Micro Data Sample file(PUMS), which contains around 5% of the actual survey data collected by the American Community Survey over a five year period(2012-2016). The variables present cover the questions asked in the survey. Some of the variables are coded to preserve privacy of those participating in the survey. Each record is a weighted as some records were selected more often than others. The variable Principl Earninng has been adjusted for inflation.
The dataset used in this report contains variables from the population characteristics of the PUMS.It consists of 26 variables and 15681927 weighted records records.Some of the variables include Age, Race, Gender, Income, Earnings, Education Attainment, State, Occupation, Citizenship Status, etc.

This is an R based project which covers:

Data Preprocessing: Adjusting for inflation in the income variable for each year.Mapping categorical features to factors.
 
Exploratory Analysis: Various variables are compared and visualized.

Statistical Analysis: An Analysis of Covariance(ANCOVA) test is run to check if there is a statistically significant difference in the mean earnings of individuals based on their level of proficiency in English.

