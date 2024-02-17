# Search Volume Analysis

## Overview
This project analyzes search volume data across various search engines. The goal is to understand search behavior, identify trends, and make predictions on future search volumes for each search engine for keyword_rank equal 1.

## Data
The dataset contains the following columns:
- `keyword_id`: Unique identifier for the search keyword.
- `keyword_rank`: Ranking of the keyword.
- `date`: Date of the search data.
- `searches`: Number of searches for the keyword.
- `search_engine`: Identifier for the search engine.
- Additional columns derived from `keyword_rank`.

## Analysis
Main analyses were conducted:
1. Total and average searches per search engine.
2. Time series analysis to understand search patterns over time.
3. Transofrmation of keyword_rank to better fit linear models
4. Analyze correlation map

Adjustments were made to account for outlier days with unusually high search volumes.

## Models
Multiple machine learning models were explored, including:
- Random Forest Regressor
- Ridge Regression

Models were evaluated using RMSE as the performance metric.

## Usage
To run the analysis, ensure you have the required libraries installed:

```bash
pip install -r requirements.txt
```

## Requirements
- pandas
- matplotlib
- seaborn
- numpy
- scipy
- scikit-learn
- jupyter
- ipykernel

##  License
This analysis is provided under the MIT license.

## Contact
For any additional questions or feedback, please contact the repository owner.
