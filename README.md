# TrueCar-Used-Car-Price-Prediction-and-Analysis-Private
This project aims to perform predictive analysis on used car prices using data from TrueCar and build insightful Power BI dashboards to visualize the findings.
## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Predictive Modeling](#predictive-modeling)
- [Model Evaluation](#model-evaluation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Tableau Dashboard](#tableau-dashboard)
- [Conclusions](#conclusions)
- [Future Work](#future-work)
- [How to Use](#how-to-use)
- [References](#references)
  
## Project Overview

This project involves analyzing used car prices and predicting future prices using data from TrueCar. TrueCar is an online automotive pricing and information platform that provides transparency in vehicle pricing. The project aims to extract insights from the data and develop a predictive model using machine learning techniques. Additionally, interactive dashboards will be created using Power BI and Tableau for better visualization and analysis of key metrics.

## Dataset

The dataset used in this project is obtained from TrueCar, containing details of used cars listed on their platform. Key features in the dataset include:

[Dataset Link](https://drive.google.com/file/d/1r3bGRxxIB_qwB15SnaMynDLXs20Iu-Hk/view?usp=sharing)

- **Car Make and Model**
- **Year of Manufacture**
- **Mileage**
- **Price**
- **Condition**
- **Location**
- **Transmission Type**
- **Fuel Type**

## Data Preprocessing

Data preprocessing steps include:

1. **Data Cleaning**: Handling missing values, duplicates, and outliers.
2. **Feature Engineering**: Creating new features like 'Car Age' from 'Year of Manufacture,' converting categorical variables to numerical, etc.
3. **Data Transformation**: Normalization and scaling of numerical features.
4. **Encoding Categorical Variables**: Using one-hot encoding or label encoding for categorical features.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis is conducted to understand the data distribution and relationships between features. Key steps include:

- **Descriptive Statistics**: Summarizing the central tendency, dispersion, and shape of the dataset’s distribution.
- **Correlation Analysis**: Identifying relationships between different variables.
- **Visualization**: Creating plots like histograms, scatter plots, box plots, and heatmaps to understand data patterns and distributions.

## Predictive Modeling

A predictive model is developed to estimate the prices of used cars. The modeling steps include:

1. **Data Splitting**: Dividing the data into training and testing sets.
2. **Model Selection**: Trying different machine learning algorithms such as Linear Regression, Random Forest, Gradient Boosting, etc.
3. **Hyperparameter Tuning**: Optimizing the model parameters for the best performance.
4. **Feature Selection**: Identifying the most important features that affect car prices.

## Model Evaluation

The model's performance is evaluated using metrics such as:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared (R²) Score**

These metrics help in determining the accuracy and reliability of the model.

## Power BI Dashboard

A Power BI dashboard is created to visualize key metrics and insights derived from the data. The dashboard includes:

- **Price Distribution by Make and Model**
- **Top Car Brands by Average Price**
- **Price Trends Over Time**
- **Mileage vs. Price Analysis**
- **Filter and Slicer Options**: Allowing dynamic exploration of data based on filters like car make, model year, mileage, etc.

## Tableau Dashboard

A Tableau dashboard is created to provide interactive visualizations for in-depth analysis. The dashboard includes:

- **Geographical Distribution of Used Cars**
- **Price vs. Mileage Analysis**
- **Scatter Plot for Price Prediction**
- **Heatmap of Average Prices by Car Type and Year**
- **Dynamic Filtering Options**

## Conclusions

Summarize the key findings from the predictive analysis and dashboard visualizations. Discuss the impact of different variables on used car prices and the effectiveness of the predictive model.

## Future Work

Suggestions for future work might include:

- Adding more features such as dealer location, car color, etc., for better prediction accuracy.
- Using advanced machine learning techniques or deep learning models.
- Incorporating data from other car-selling platforms to improve model generalization.

## How to Use

1. Clone the repository to your local machine.
2. Follow the steps in the Jupyter notebooks for data preprocessing, EDA, and predictive modeling.
3. Open Power BI and Tableau files to explore the interactive dashboards.
4. Install necessary Python libraries as listed in `requirements.txt`.

## References

- TrueCar Data Source: [TrueCar Website](https://www.truecar.com)
- Machine Learning Algorithms: [Scikit-Learn Documentation](https://scikit-learn.org/)
- Data Visualization Tools: [Power BI](https://powerbi.microsoft.com/) | [Tableau](https://www.tableau.com/)

---

Thank You



























