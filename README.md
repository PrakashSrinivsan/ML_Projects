![Project Overview](images/logoBlu-Unina.jpg)

# NEST WEIGHT PREDICTION & FORECASTING

Welcome to the **Nest Weight Prediction & Forecasting** project! This repository contains code and resources for predicting and forecasting the weight of insect colonies using various time series forecasting techniques. Insect colonies play a crucial role in ecosystems and agricultural systems, and accurate weight predictions can offer valuable insights for better management and research.

## Problem Statement

The objective of this project is to develop forecasting models that can accurately predict the weight of an insect colony based on colony and environmental data. We aim to leverage exploratory data analysis, feature engineering, and advanced time series forecasting techniques to achieve this goal.

## Table of Contents

1. **Exploratory Data Analysis**
   - Data Inspection
   - Descriptive Statistics
   - Data Visualization
   - Missing Data Analysis
   - Outlier Detection
   - Correlation Analysis

2. **Feature Engineering**
   - KRUSKAL-WALLIS & WILCOXON RANK-SUM TEST
   - Feature Selection
   - RECURSIVE FEATURE ELIMINATION (RFE)
   - AUGMENTED DICKEY-FULLER (ADF) TEST

3. **Modeling, Prediction & Forecasting**
   - FORECASTING THE NEST WEIGHT (ARIMA - MULTIVARIATE)
   - SEASONAL AUTOREGRESSIVE MOVING AVERAGE (SARIMA) - MULTIVARIATE
   - Comparison of ARIMA & SARIMA with Different Approaches

4. **Conclusion**
   - Performance Evaluation Metrics
   - Comparison of ARIMA and SARIMA
   - Preferred Model Selection

## Exploratory Data Analysis

We began by thoroughly examining the provided data, including data inspection, summary statistics, and visualization. We addressed missing data and outliers, ensuring the data's quality for further analysis.

## Feature Engineering

To enhance the predictive power of our models, we performed feature engineering techniques such as Kruskal-Wallis and Wilcoxon Rank-Sum tests for feature selection. Additionally, we employed Recursive Feature Elimination (RFE) and the Augmented Dickey-Fuller (ADF) test for identifying and selecting relevant features.

## Modeling, Prediction & Forecasting

We utilized two distinct approaches for predicting and forecasting Nest Weight:
- **ARIMA (AutoRegressive Integrated Moving Average) Model**: We applied differencing to transform non-stationary time series data and employed the ARIMA model for prediction and forecasting.
- **SARIMA (Seasonal ARIMA) Model**: Leveraging the inherent pattern and trend in the Nest Weight data, we used the SARIMA model without differencing.

We compared the performance of both models using evaluation metrics including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

### Performance Results

- ARIMA Model:
  - MSE: 4.124
  - RMSE: 2.030
  - MAE: 1.281

- SARIMA Model:
  - MSE: 1.309
  - RMSE: 1.144
  - MAE: 0.066

## Acknowledgments

**Author:**
- Prakash Srinivasan
  - Master's in Data Science
  - University Of Naples Federico II

We would like to express our sincere gratitude to the following individuals for their valuable contributions to this project:

**Supervisors:**
- Professor. Flora Amato
  - University Of Naples Federico II
- Professor. Mattia Fonisto
  - University Of Naples Federico II

Their guidance, expertise, and insights have been instrumental in shaping the direction and outcomes of this project.

## Usage Instructions

1. **Clone the Repository**: Begin by cloning this repository to your local machine using the following command:
   git clone https://github.com/PrakashSrinivsan/Nest-Weight-Forecasting.git
2. **Navigate to Project Directory**: Change your working directory to the project folder by executing the following command:
   cd Nest-Weight-Forecasting

3. **Explore the Colab Notebook**: The main analysis and code implementation can be found in the `Nest Weight Prediction & Forecasting.ipynb` Colab Notebook. Open this notebook using your preferred Colab environment to dive into the code, methodology, and visualizations used in the project.
4. **Install Dependencies**: If necessary, install the required Python dependencies by running the following command:
   pip install -r requirements.txt

5. **Run the Notebook**: Launch your Colab Notebook environment and open the `Nest Weight Prediction & Forecasting.ipynb` notebook to interact with the code. You can execute individual cells or run the entire notebook to replicate the analyses.
6. **Contribute**: If you find any issues or opportunities for improvement, we welcome your contributions! Feel free to fork the repository, make your changes, and submit a pull request.

## Contact

If you have any questions, suggestions, or feedback regarding this project, please feel free to contact the project author Prakash Srinivasan at psrinivasan028@gmail.com.
Thank you for your interest in our project! We hope you find the provided Jupyter Notebook insightful and valuable for your research and projects.


