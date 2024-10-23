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
1. Business Understanding : The Business Understanding phase focuses on understanding the objectives and requirements of the project

2. Data Understanding : Next is the Data Understanding phase. Adding to the foundation of Business Understanding, it drives the focus to identify, collect, and analyze the data sets that can help you accomplish the project goals. This phase also has four tasks:
  
3. Data Preparation : This phase, which is often referred to as “data munging”, prepares the final data set(s) for modeling. It has five tasks:
       
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

Pclass and Fare have a negative correlation, the lower the Pclass, the higher the Fare

The feature that has the most influence on Survived is Pclass

