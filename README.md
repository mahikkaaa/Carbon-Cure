
# CARBON CURE :  Analyzing and Predicting Carbon Emissions from Electricity Generation

![carbon-dioxide-emissions-from-electricity-photo-of-factory-smoke](https://github.com/mahikkaaa/Carbon-Cure/assets/80638498/995e6ec5-d6b6-4e68-b09b-0844f738c8e2)



## Introduction

Climate change and environmental concerns make it essential to understand and predict CO2 emissions. This project aims to analyze the monthly CO2 emissions dataset and build an LSTM model to predict future emissions trends. The analysis includes data visualization, trend exploration, and a deep learning approach to capture patterns in the time series data.
The goal of this project is to analyze and predict carbon emissions from electricity generation using machine learning techniques. The project leverages a comprehensive dataset to gain insights into the factors influencing carbon emissions and develop a predictive model to forecast future emissions.

## Dataset
The dataset used in this project is the Monthly Energy Review (MER) dataset obtained from the EIA. It includes information about CO2 emissions from various energy sources, such as coal, natural gas, and geothermal energy.
The dataset contains information on carbon emissions from electricity generation, including key features such as energy source code, year and month, carbon emission values, and metadata columns (column order, description, and unit of measurement). The target variable for prediction is the "Value" column.

- **MSN:** Energy source code
- **YYYYMM:** Year and month
- **Value:** Carbon emissions
- **Column_Order:** Order of the column
- **Description:** Description of the column
- **Unit:** Unit of measurement

### Data Retrieval and Visualization

The initial steps involve retrieving the dataset, converting it into a time series format, and visualizing CO2 emissions trends over time. Python libraries such as Pandas and Matplotlib are used for data manipulation and visualization.

### Data Preprocessing

Data preprocessing includes handling missing values, converting data types, and scaling the data for the LSTM model. The dataset is split into training and test sets, and MinMax scaling is applied to ensure the model's effectiveness.

### LSTM Model

The core of the project involves building an LSTM model using the TensorFlow and Keras libraries. The model is trained on the training set, and predictions are made for the test set. Mean Squared Error (MSE) is used as a metric to evaluate the model's performance.


## Objectives

### Exploratory Data Analysis (EDA)

- Perform a detailed exploration of the dataset, understanding its structure, summary statistics, and carbon emission distribution.
- Visualize temporal trends to identify patterns and seasonality.
- Explore correlations between carbon emissions and relevant features such as electricity generation sources and environmental factors.

### Data Preprocessing

- Handle missing data and outliers.
- Convert data types and ensure the dataset is suitable for machine learning.
- Perform feature engineering, extracting additional information from date columns if necessary.

### Machine Learning Modeling

- Split the dataset into training and testing sets.
- Select appropriate machine learning algorithms for regression tasks.
- Train the model using historical data, with a focus on predicting carbon emissions.
- Evaluate model performance using metrics like Mean Absolute Error, Mean Squared Error, and R-squared.

### Feature Importance Analysis

- Identify the most influential features contributing to carbon emissions.
- Visualize and interpret feature importance scores obtained from the machine learning model.

### How to Use

To use this code, follow these steps:

1. Clone the repository: `git clone https://github.com/mahikkaaa/Carbon-Cure.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python script for step-by-step analysis.

### Dependencies

- Python 3.x
- Pandas
- Matplotlib
- NumPy
- TensorFlow
- Keras
- Scikit-learn


### Project Coordinators:
- Mahika Agrawal - 20BAI10101
- Sneha Tiwari - 20BAI10153
- Sahil Arora - 20BAI10264
- Nikhil - 20BAI10275
- Areena Khan - 20BAI10285

Feel free to customize this README further based on the specific details of your project, such as adding sections for results, recommendations, or acknowledgments.

For any questions or issues, please open an [issue](https://github.com/mahikkaaa/Carbon-Cure/issues).
