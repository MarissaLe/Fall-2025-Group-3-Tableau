# Fall-2025-Group-3-Project-2

## Team Name:

# Project 2: NCHS Leading Cause of Deaths

## Dataset Description

Our data is the leading cause of deaths that we had obtained from https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states. The data is based on information from all resident death certificates filed in the 50 states and the District of Columbia utilizing demographic and medical characteristics. The dataset contains 10,868 rows and 6 columns, combining both descriptive and quantitative variables. There are a variety of dimensions and data types that are captured. Beginning with the Year dimension which is a number dataset, switched to a date type in Tableau, this represents the years of recorded deaths and the years of the age-adjusted deaths. The following dimensions are State, Cause Name and 113 Cause Name which are string data types. States inform the analysts of the different states of each recorded death. Cause Name is the simplified version of the cause for each death, such as Heart disease or Kidney disease, while 113 Cause Name gives the full name for each cause along with the ICD-10 codes. Lastly the dataset also contains the Deaths and Age-adjusted Death Rate and these are number data types. Death is depicted in whole number form indicating the total number of deaths that are recorded and Age-adjusted Death Rate reflects the death rate per 100,000 people, adjusted for differences in age distribution across populations. After July 1, 2010 population used to compute death rates are estimated based on the 2010 census.

## Question 1:
How do deaths and age-adjusted death rates vary across U.S. states, and which states show the highest and lowest rate? For the states with the highest and lowest age-adjusted death rates, what were the leading causes of death in 1999, 2005, 2011, and 2017?

This is an important question because it digs deeper into the public health inequality and risk factors across the U.S and it also narrows down the states with the highest and lowest age-adjusted deaths. By comparing the death rates of the highest and lowest over time we can see how the states are either improving or worsening. Comparing data for 1999, 2005, 2011, and 2017 enables us to see long-term progress or decline. This question also goes into the economical impact that might be required after analyzing this data. We visualized this in Tableau with a map to see the highest and lowest rates that could assist policymakers decide cost-effective interventions and effective health policies. 

<p align="center">
<img width="626" height="387" alt="Screenshot 2025-11-21 at 1 53 49 PM" src="https://github.com/user-attachments/assets/14cdff9c-9243-49b4-a338-f308137a78e9" />
<img width="619" height="376" alt="Screenshot 2025-11-21 at 1 54 23 PM" src="https://github.com/user-attachments/assets/281bcfb1-fa72-4a78-bc6f-d0042c4bda63" />

*ANALYSIS*: 

*Data Manipulation*: There was no data manipulation necessary for this question. The question used the minimal and standard data preparation steps that are given to us by Tableau. The data is filtered to only use the specific years 1999, 2005, 2011, and 2017 as well as filtering Hawaii and Mississippi as the lowest and highest age-adjusted death rates states. The data was also aggregated using the SUM functions in order to compare overall death counts and age-adjusted rates across the states. 

## Question 2:
