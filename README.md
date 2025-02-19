# Spotify-User-Growth-Premium-Subscription-Analysis

## Overview

This repository contains code for analyzing Spotify user behavior, focusing on understanding user willingness to adopt premium subscriptions and identifying patterns related to device preferences based on music listening moods. The analysis involves data cleaning, exploratory data analysis, and the application of supervised machine learning models and K-Means clustering.

## Features

-   **Data Cleaning and Preprocessing**: Handles missing values and prepares the dataset for analysis.
-   **Exploratory Data Analysis (EDA)**: Conducts visual analysis to understand user demographics, subscription preferences, and listening habits.
-   **Supervised Machine Learning**: Implements various machine learning models to predict user willingness to adopt premium subscriptions.
-   **K-Means Clustering**: Identifies patterns in device preferences based on music listening moods.
-   **Interactive Visualizations**: Utilizes Plotly to create dynamic and interactive charts.

## Requirements

To run this project, you need:

-   Python 3.x
-   Libraries:

    -   Pandas
    -   Seaborn
    -   Matplotlib
    -   Plotly
    -   Scikit-learn
    -   XGBoost
-   Install the required libraries using pip:

```bash
pip install pandas seaborn matplotlib plotly scikit-learn xgboost
```

## Getting Started

### Dataset

The dataset used in this project, `Spotify_data.xlsx`, should be placed in the same directory as the Python scripts. Ensure the dataset is properly formatted for the application to function correctly.

### Running the Code

1.  Clone the repository:

```bash
git clone https://github.com/yourusername/Spotify-User-Growth-Premium-Subscription-Analysis.git
cd Spotify-User-Growth-Premium-Subscription-Analysis
```

2.  Navigate to the directory containing the analysis scripts.
3.  Run the Python scripts in a Jupyter Notebook or any Python environment.

## Code Explanation

### Data Cleaning and Preprocessing

The code includes steps to handle missing values by imputing them with appropriate placeholders ('None' for categorical columns, 'No Preference' where suitable) to ensure no data is lost during analysis.

### Exploratory Data Analysis (EDA)

The code uses Plotly to create interactive visualizations such as bar charts, pie charts, and histograms to explore distributions, relationships, and trends within the dataset.

### Machine Learning

The code outlines the intended approach for using supervised machine learning models (e.g., KNeighborsClassifier, SVC, GaussianNB, DecisionTreeClassifier, RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, XGBClassifier) to predict user willingness to adopt premium subscriptions.

### Clustering

The code prepares for K-Means clustering to identify patterns in device preferences based on users' music listening moods.

## Conclusion

This project aims to provide insights into Spotify user behavior by exploring factors influencing the adoption of premium subscriptions and understanding how user preferences for listening devices vary with their mood. The analysis combines data cleaning, EDA, machine learning, and clustering techniques to offer a comprehensive view of user behavior, ultimately helping in strategic decision-making related to user acquisition and engagement.
