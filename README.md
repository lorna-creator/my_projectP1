# Comprehensive Aircraft Risk Assessment for Startup Business Operations

## Description
This project aims to conduct a comprehensive analysis of various aircraft models to identify those with the lowest risks, thus facilitating a strategic entry into the aviation industry. As the company diversifies its business portfolio by acquiring aircraft for both commercial and private operations, it is critical to ensure that these investments are sound and minimize potential risks.

By leveraging data-driven insights, the project seeks to evaluate the probable risks associated with different aircraft models and make informed recommendations for acquisition. This analysis will ultimately support better decision-making, enhance operational efficiency, ensure regulatory compliance, and improve customer satisfaction.

## Problem Statement
The company is venturing into the aviation sector with little prior experience, presenting challenges that require thorough risk assessment. Identifying low-risk aircraft is essential to ensure financial stability and operational success as the business expands.

## Goals
Identify the safest aircraft models for acquisition.
Provide business recommendations based on findings.

## Objectives
Identify the lowest-risk aircraft to be purchased by the company.
Minimize potential financial losses and ensure profitability.

## Limitations
The company is relatively new to the aviation sector and lacks in-depth knowledge about market navigation and low-risk aircraft models.

### Data Source
The dataset utilized for this analysis was gathered from Kaggle, originating from the National Transportation Safety Board (NTSB) aviation accident database. This database has documented civil aviation accidents and selected incidents in the United States since 1962. It provides preliminary reports of accidents, which are updated as investigations progress. The goal of this dataset is to enhance the quality and safety of air travel through incident analysis.

### Data Overview
In this project, we will apply our analytical skills to identify the safest aircraft options for the company's expansion into the aviation sector. We will analyze the aviation_data.csv dataset, sourced from the National Transportation Safety Board, which contains aviation accident records spanning from 1962 to 2023.

Shape: The dataset contains 88,889 entries and 30 columns.
Data Types: The data types listed represent the structure of the dataset related to aviation accidents. Each row corresponds to an individual accident, and the columns capture various attributes of these incidents.

i)object: Indicates categorical or string data, such as accident details

ii) float64: Represents numerical values with decimal points, often used for continuous data'

#### Import the Relevant Libraries and read the data

`python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
df = pd.read_csv('Aviation_Data.csv', dtype={6: 'object', 7: 'object', 28: 'object'})
df.head()
`

