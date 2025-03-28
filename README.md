# Customer-Churn-Analysis
## Overview
This project analyzes customer churn data to uncover patterns and identify actionable strategies for improving customer retention. The analysis uses Python and Jupyter Notebook to preprocess data, explore insights, and visualize churn-related factors.

## Features
- **Data Preprocessing**: Replaced blanks with `0` for tenure and total charges. Converted binary values for senior citizens into a more intuitive Yes/No format.
- **Exploratory Analysis**:
  - Pie chart: Shows that 26.54% of customers have churned.
  - Churn by senior citizen status: Higher churn among senior citizens.
  - Tenure analysis: Longer-tenured customers are less likely to churn, while those with 1-2 months tenure churn more frequently.
  - Contract type: Month-to-month contracts exhibit higher churn compared to 1 or 2-year contracts.
  - Service usage: Customers with services like PhoneService, InternetService (DSL), and OnlineSecurity enabled tend to churn less, whereas lack of OnlineBackup, TechSupport, or StreamingTV increases churn.

## Key Insights
- Senior citizens have a significantly higher churn rate.
- Early-tenure customers are more likely to churn.
- Month-to-month contracts correlate strongly with higher churn.
- Service bundles with OnlineSecurity and DSL Internet help reduce churn.

## Visualizations
- Pie charts and bar plots were used to highlight churn distribution across customer categories.
- Tenure trends and service adoption were visualized to correlate with churn rates.

## Technologies Used
- **Python**: For data preprocessing and analysis.
- **Jupyter Notebook**: For interactive coding and visualization.
- **Matplotlib/Seaborn**: For creating insightful visualizations.
