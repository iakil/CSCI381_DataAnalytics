# Building a Machine Learning Algorithm to predict the HIV impact on certain ethnicity or areas

<br>

# Introduction

Some facts about HIV in the USA are HIV/AIDS is a big problem in our country and HIV is not the same as AIDS, HIV tests are reliable and HIV can not be cured. It is very unfortunate that about 13% of people living with HIV in the US do not know they are infected. AIDS is the most serious stage of HIV, and it leads to death over time. Without treatment, it usually takes about 10 years for someone with HIV to develop AIDS. Treatment slows down the damage the virus causes and can help people stay healthy for several decades. Using ML algorithms, our goal is to analyze our data and predict the output values within an acceptable range.

<br>

# Research Question and Data:
How does HIV impact on certain ethnicity or areas?

Our Data Set represents HIV/AIDS Diagnoses by Neighborhood, Sex, and Race/Ethnicity. This dataset includes data on new diagnoses of HIV and AIDS in NYC for the calendar years 2010 through 2013. Reported cases and case rates (per 100,000 population) are stratified by age group, race/ethnicity, and United Hospital Fund (UHF) neighborhood. The study in our dataset was conducted on both males and females and returns the total number of diagnoses and shows the impact based on the location and the ethnicity.  Rates marked "NA" cannot be calculated because the underlying population size is unknown.
Tables or charts may contain suppressed data: cells representing 1-5 person(s) with an underlying denominator of < 500 persons, or non-zero cells with a denominator <= 100 as per Intercensal 2014 estimates, are marked with an asterisk (*). In our dataset, we have 2928 rows and 10 attributes with integer, float, and object datatypes. 


| Attributes Name | Description |
| --- | ----------- |
|1- YEAR| Calendar year of report (2010 - 2013)|
|2- Neighborhood (U.H.F)| United Hospital Fund neighborhood of residence |
|3- SEX| Male or Female|
|4- RACE/ETHNICITY| Race or Ethnicity|
|5- TOTAL NUMBER OF HIV DIAGNOSES|TOTAL NUMBER OF HIV DIAGNOSES|
|6- HIV DIAGNOSES PER 100,000 POPULATION|HIV DIAGNOSES PER 100,000 POPULATION|
|7- TOTAL NUMBER OF CONCURRENT HIV/AIDS DIAGNOSES|TOTAL NUMBER OF CONCURRENT HIV/AIDS DIAGNOSES|
|8- PROPORTION OF CONCURRENT HIV/AIDS DIAGNOSES AMONG ALL HIV DIAGNOSES|PROPORTION OF CONCURRENT HIV/AIDS DIAGNOSES AMONG ALL HIV DIAGNOSES|
|9- TOTAL NUMBER OF AIDS DIAGNOSES|TOTAL NUMBER OF AIDS DIAGNOSES|
|10- AIDS DIAGNOSES PER 100,000 POPULATION|AIDS DIAGNOSES PER 100,000 POPULATION|

<br>

# Data To be Used:
> For our final project I used [NYC OpenData](https://data.cityofnewyork.us/Health/HIV-AIDS-Diagnoses-by-Neighborhood-Sex-and-Race-Et/ykvb-493p) , where I have around 3000 rows with 10 attributes.

<br>

# Approach:
The data will be managed by reading into the GitHub raw data link and performing necessary data preparation, cleaning, and scaling operations. We plan to do an entire EDA that includes searching for relationships among variables, testing for multicollinearity, and independence, showing charts, regressions, models, and much more.