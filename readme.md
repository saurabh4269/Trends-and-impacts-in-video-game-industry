# Trends & Impacts in Video Game Industry

## Overview
This project analyzes key trends and impacts in the video game industry using a comprehensive dataset of 16,928 entries, focusing on how various factors influence global game sales. The goal of the project is to provide insights into optimizing game development and marketing strategies through data-driven analysis.

## Key Objectives
- Analyze the trends in the video game industry and their impacts on global game sales.
- Apply statistical techniques and machine learning algorithms to extract insights and predict future sales.
- Provide actionable recommendations for game development and marketing strategies.

## Methodology
- **Exploratory Data Analysis (EDA)**: Conducted an initial exploration of the dataset to identify trends, correlations, and outliers.
- **Predictive Modeling**: Used machine learning algorithms to predict game sales based on various features such as genre, publisher, and release year.
  - **Linear Regression**: Applied to predict continuous sales figures.
  - **Random Forest**: Used for more complex, non-linear predictions.
- **Dimensionality Reduction**: Employed **Principal Component Analysis (PCA)** to reduce the dataset’s complexity while retaining key information.
- **Clustering and Time Series**: Implemented **K-means clustering** to group games with similar characteristics and applied **time series analysis** to examine trends in game sales over time.

## Technologies Used
- **Python**:
  - **Pandas**, **NumPy**: For data manipulation and numerical analysis.
  - **Matplotlib**, **Seaborn**: For data visualization.
  - **Scikit-learn**: For machine learning models like Linear Regression, Random Forest, and PCA.
  - **Statsmodels**: For statistical analysis.
  - **K-means Clustering**: For grouping similar games.
  - **Time Series Analysis**: To analyze trends over time.

## Data
The dataset used contains **16,928 entries** of video games, including features such as:
- Game Title
- Genre
- Publisher
- Release Year
- Platform
- Sales in different regions (Global, NA, EU, JP)
- Game ratings and more.

## Key Findings
- Identified trends in global game sales over the years, focusing on popular genres and platforms.
- Analyzed how specific game features, such as genre and publisher, affect global sales.
- Clustering results revealed key characteristics of top-selling games.
- Predicted the impact of release timing and marketing on game sales.

## Predictive Models
- **Linear Regression**: Used for forecasting global sales based on numerical predictors.
- **Random Forest**: Applied to predict sales using complex, non-linear relationships.
- **Principal Component Analysis (PCA)**: Reduced dimensionality while keeping the most important features for sales prediction.

## Conclusion
This project provides valuable insights into the video game industry, helping to identify the factors that drive game sales. By utilizing various machine learning algorithms, we were able to predict future sales and offer recommendations for game development and marketing strategies.