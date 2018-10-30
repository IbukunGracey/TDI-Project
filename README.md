# TDI-Project

### PROPOSED CAPSTONE PROJECT -THE DATA INCUBATOR
This repository contains project proposed for the data incubator programme. The project is focused on the identification of trends and the prediction of the outbreak of diseases all across the globe.

#### PROJECT TITLE: ANALYSIS AND PREDICTION OF DISEASE OUTBREAK  ACROSS THE GLOBE

### BACKGROUND
*According to the  World Health Organisation,a disease outbreak is the occurrence of cases of disease in excess of what normally should be expected in a defined community, geographical area or season. Over the years concerns is been raised by the populace whenever there is an epidemic of disease in a community, country or continent. Mortality rate increases and it affects growth and development in such communities. This work aims to address the prevalence of disease around the globe using machine learning approach. This will provide a platform for health experts and enthusiasts to identify which disease would affect a particular country and what season of the year it will occur. If a disease breakout is known or identified before occurence, the society, governments and general populace will be well prepared for it and combact it at its early stage before a complete breakout*

### MOTIVATION
To build a community free from diseases and to help the populace prepare early in the advent of an epidemic, i propose to develop a system that helps to identify trends based on existing data and make predictions of an occurrence of future diseases and also identify how the possibility of the effect of a spread to neighboring countries. 

### ANALYSIS TO BE PERFORMED
The following questions that will be addressed by this analysis are:
1.	What is driving multiple outbreak of diseases across the globe? Examples are Ebola, Lassa Fever, Cholera etc 
2.	Which location are they predominantly in.
3.	What time or season do they invade or are they likely to invade a particular territory?
4.	What can be done to prevent the spread of these diseases.

### APPROACH AND RESULT
I used a python library called beautiful soup to extract data of all diseases across all countries from 1996 - 2018. This data was obtained for the website of World Health Organisation. 

I carried out an exploratorty data analysis on these datasets by starting with data cleaning, to data visualization and data manipulation. I studied the features which are Name of disease, where it occurred and date of occurence. Also i had to manipulate the data to get desired resuts. In this work,, i used Ebola as a case study.

During the course of the analysis the following were identified:

1. Comparing 49 diseases spread across 56 countries, the most prevelent out break is Middle East respiratory syndrome coronavirus (MERS-CoV), followed by Ebola and then Human infection with avian influenza A(H7N9) virus. 

2. The countries with the largest number of disease outbreak is Congo, China and Saudi Arabia. See Figure 1

3. Picking Ebola as a case study, it was observed from Figure 2, Ebola's outbreak season spans from  May to October, also the breakout is higher in May and August.

4. Similarly in Figure 3., Middle East respiratory syndrome coronavirus (MERS-CoV) occurs all year round with high breakout in April and June.


### Further work
1. Futher analysis will be carried out using Machine learning algorithms to predict what disease will be prevalent at a particular time, in a specific country.
2. Also the dataset will be increased to include other factors that could contribute to the spread of a particular disease.
3. The system will be implemented as a web interface so that people can interact with it.

###### Data Sources
1. WHO: Emergency, Preparedness and Response http://www.who.int/csr/don/en/
2. Disease Outbreak by year http://www.who.int/csr/don/archive/year/2018/en/
3. Archive by Disease outbreak http://www.who.int/csr/don/archive/country/en/
4. Scraped data: https://github.com/IbukunGracey/TDI-Project.git
