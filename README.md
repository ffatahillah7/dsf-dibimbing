# DSF-Dibimbing 
Data Science Fair 3.0 Dibimbing Portofolio - Analysis and Learning from titanic dataset

The purpose of this project is to master the exploratory data analysis (EDA) in titanic crash with Pandas framework.

Download Dataset file : https://www.kaggle.com/competitions/titanic

## Goals of the Project:
1.  Explore a titanic accident dataset with Pandas framework.
2.  Build pivot tables.
3.  Visualize the dataset with various plot types.

## Outline
1.  Materials and methods
2.  General Part : Data Preprocessing, Data Cleaning, Data Visualization
3.  Tasks

## Materials and Methods

### How To Learn with Cross-Industry Standard Process for Data Mining (CRISP-DM)
1. Business Understanding : The Business Understanding phase focuses on understanding the objectives and requirements of the project. In this project, we should know about what's happening, why it's happening and who is involved in Titanic Accident.

2. Data Understanding : Next is the Data Understanding phase. Adding to the foundation of Business Understanding, it drives the focus to identify, collect, and analyze the data sets that can help you accomplish the project goals. The data is consist of Name of Passengers, Age, Sex, Fare, Embarked, Class of ticket (Pclass) and so on.
  
3. Data Preparation : This phase, which is often referred to as “data munging”, prepares the final data set(s) for modeling. In this methods , we cleaning the data from anomali, null, not correlation data and any others missed from the data source.
       
4. Modeling : What is widely regarded as data science’s most exciting work is also often the shortest phase of the project. Here you’ll likely build and assess various models based on several different modeling techniques.
   
5. Evaluation : Whereas the Assess Model task of the Modeling phase focuses on technical model assessment, the Evaluation phase looks more broadly at which model best meets the business and what to do next
   
6. Deployment : A model is not particularly useful unless the customer can access its results. The complexity of this phase varies widely

### Start Working

Download Libary that you need for analytics

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

### Read Data
used pandas library to read the data that we want to learn and analysis. Then, store it to data frame.

df = pd.read_csv("/kaggle/input/titanic/train.csv")

df #Show data frame from csv file

### Statistik deskriptif dari data

### Check Null value

### Data Preprocessing

### Fill Blank data on Age Columns with Median

### Fill Blank data on Embarked Columns with Modus

### Drop Cabin's Columns because too much empty value

### Check null value as well

## EDA

### Import library for EDA

### Analysis for Age Columns

### Analysis for Fare Columns

### Analysis for Pclass Columns

### Analysis for Sex Columns

### Correlation Matrix

# Conclusion

-  Children under 10 years have a better chance of surviving, perhaps because they are prioritized for rescue using lifeboats

-  Pclass and Fare have a negative correlation, the lower the Pclass, the higher the Fare

-  The feature that has the most influence on Survived is Pclass
-  Passengers with high costs have a better chance of surviving than those with low costs
-  The percentage of survivors in Pclass = 1 is greater than in Pclass 2 and 3
-  The percentage of survivors in Sex = female is higher than male

