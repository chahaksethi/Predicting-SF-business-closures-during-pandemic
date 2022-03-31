# Distributed Data Analytics Framework for Predicting Business Closures in SF during the Pandemic

## Overview

1) Integrated and preprocessed  Covid-19, crime, and business closure data in different San Francisco neighborhoods using Apache Spark on Databricks and      stored in MongoDB.
2) Developed various ML models including Random Forests, Decision Tree, Logistic Regression, and Ensemble models to predict business closures in San          Francisco’s neighborhoods using Spark and H2O ML libraries.

## Details

### Analytical Goals

1) Combine different data sources to understand the influence of crime incidents, Geography, covid cases, vaccinations on business closures at a location      in San Francisco.
2) Build Machine Learning Models using Apache Spark to predict whether a business at a location will closedown in the next six months based on different      attributes described above.

### Data

1. Police_Department_Incident_Reports: Date wise, Geography wise crime incidents reported
2. COVID-19_Cases_by_Geography_and_Date:
3. Registered businesses: Geography wise Business name, description, business start date and permanent closer date etc
4. Area Walk scores

### Results

1) The main factors affecting the business activity in San Francisco are :
    - Nature of the business: Retail, Food services, and accommodations businesses were impacted negatively during Covid.
    - Age of the Business: More Older(5+yrs) businesses have closed during the 2018-21 time period.
    - Crime rates in an area is a significant predictor of business closure.
2) Active covid cases, vaccination rates did not have a significant impact on closing of a business.
