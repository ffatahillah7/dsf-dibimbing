# DSF-Dibimbing 
Data Science Fair 3.0 Dibimbing Portofolio - Analyctics and Learning from titanic dataset

Download Dataset file : https://www.kaggle.com/competitions/titanic

# How To Learn with Cross-Industry Standard Process for Data Mining (CRISP-DM)
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

# Start Working

Download Libary that you need for analytics

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

## Read Data
used pandas library to read the data that we want to learn and analysis. Then, store it to data frame.

df = pd.read_csv("/kaggle/input/titanic/train.csv")

df #Show data frame from csv file

## Statistik deskriptif dari data

## Check value yang kosong

## Data Preprocessing

### Isi data kosong pada Kolom Age dengan Median

### Isi data kosong pada Kolom Embarked dengan Modus

### Drop kolom Cabin karena banyak yang kosong

### Check hasil setelah di preprocess

## EDA

### Import library untuk EDA

### Analisis Kolom Age

### Analisis Kolom Fare

### Analisis Kolom Pclass

### Analisis Kolom Sex

### Correlation Matrix

Pclass dan Fare memiliki korelasi negativ, semakin rendah Pclass maka semakin tinggi Fare-nya

Fitur yang paling berpengaruh terhadap Survived adalah Pclass

