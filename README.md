# LearnTech - Exploratory Data Analysis

## Welcome to the Data Practice exploratory data analysis repo
This repository contains the following
- Instructions for setup
- Data files
- Slides from the day

## Goals
This Learn Tech day aims to offer some insight into the process of exploratory data analysis. Often when placed on a project, clients will see the word "Data" and instantly hear "analyst" or "scientist". This then leads to them asking for insights to or analysis of their data. This repository will hopefully contain enough information and worked examples that anyone with a basic understanding of python will be able to work through some basic analysis steps and be able to produce some meaningful visualisations in order to drive some discussion. 

### We will cover
- What is exploratory data analysis?
- Why do we do it?
- Presenting missing data
- Presenting time series data 
- Data types 
- Univariate analysis
- Bi-variate analysis
- Multi-variate analysis
- Tips on data visualisations

A code of the slide dec can be found [here](Introduction_to_Exploratory_Data_Analysis.pdf).

## Useful links and resources
- [ONS Government visualisation guidance](https://analysisfunction.civilservice.gov.uk/policy-store/data-visualisation-colours-in-charts/)
- [Graph gallery](https://www.python-graph-gallery.com)
- [What is Exploratory Data Analysis?](https://medium.com/towards-data-science/exploratory-data-analysis-8fc1cb20fd15)
- [Fraud credit card transaction dataset: Feature Engineering & Exploratory Data Analysis](https://medium.com/quant-ai-lab/fraud-credit-card-transaction-dataset-feature-engineering-exploratory-data-analysis-63001299d429)

## Setup 
Navigate to your target directory and clone the repo:
```
git clone https://github.com/JimmySunDance/learntech-exploratory-data-analysis.git
```
Create a virtual environment:
```
cd learntech-exploratory-data-analysis
python -m venv .venv
```
Start virtual environment:
```
source .venv/bin/activate
```
Install the repo requirements:
```
pip install -r requirements.txt 
```
Once you are finished working, close your virtual environment using:
```
deactivate
```

## Data Sets
These datasets were taken from [Kaggle](https://www.kaggle.com).
- [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview)
- [Retail Data Analytics](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)
- [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)
- [Car Features and MSRP](https://www.kaggle.com/datasets/CooperUnion/cardataset)
