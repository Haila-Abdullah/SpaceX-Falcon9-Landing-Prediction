# SpaceX Falcon 9 First Stage Landing Prediction 🚀

## Project Overview
In this capstone project, we aim to predict whether the Falcon 9 first stage will land successfully using machine learning models. SpaceX advertises the cost of launching a Falcon 9 rocket at $62 million, significantly lower than the costs charged by other providers ($165 million+). This cost reduction is primarily due to SpaceX's ability to reuse the first stage of the rocket. By predicting the likelihood of a successful landing, we can assess launch costs more accurately and provide insights for competitive pricing if another company were to bid against SpaceX.

## Learning Objectives
By the end of this project, you will have gained the following skills:

- **Data Manipulation**: Develop Python code to manipulate data in a Pandas DataFrame.
- **Data Conversion**: Convert JSON files into Pandas DataFrames.
- **Data Collection**: Collect data using SpaceX’s API and web scraping techniques.
- **Exploratory Data Analysis (EDA)**: Visualize and analyze the dataset to find key patterns.
- **Data Visualization**: Create interactive dashboards and maps using Plotly Dash and Folium.
- **Machine Learning**: Build predictive models using classification algorithms such as SVM, Classification Trees, and Logistic Regression to predict Falcon 9 landing success.

## Overview

### Data Collection and Preparation
- **Objectives**: Collect data using RESTful API and web scraping, and convert it into a Pandas DataFrame.
- **Activities**: Data wrangling to clean and prepare the dataset for analysis.

### Exploratory Data Analysis (EDA)
- **Objectives**: Visualize data with scatter plots and bar charts.
- **Activities**: Conduct data analysis using Pandas to explore relationships in the dataset. Perform SQL queries to filter and sort data.

### Data Visualization
- **Objectives**: Build an interactive dashboard to analyze launch records.
- **Activities**: Create visualizations using Plotly Dash and Folium for analyzing launch site proximity.

### Machine Learning Model Development
- **Objectives**: Train and evaluate machine learning models.
- **Activities**: Split data into training and testing sets, apply classification models (SVM, Classification Trees, Logistic Regression), and perform hyperparameter optimization to find the best model.

## Dataset
The dataset used for this project includes detailed information on Falcon 9 launches, such as:

- Flight Number
- Launch Site
- Class (Success/Failure)
- Payload Mass (kg)
- Booster Version
- Booster Version Category

Data was collected using SpaceX’s API and supplemented with web scraping techniques to ensure comprehensiveness and currentness.

## Files and Directories

- `01_spacex-data-collection-api.ipynb`: Jupyter notebook for data collection via SpaceX API.
- `02_spacex-web-scraping.ipynb`: Jupyter notebook for collecting additional data using web scraping techniques.
- `03_spacex_data_wrangling.ipynb`: Jupyter notebook for cleaning and wrangling the dataset.
- `04_spacex-eda-sql-sqllite.ipynb`: Jupyter notebook for exploratory data analysis (EDA) with SQL queries on the dataset.
- `05_spacex-eda-dataviz-v2.ipynb`: Jupyter notebook for visualizing data through scatter plots and bar charts.
- `06_launch-site-location.ipynb`: Jupyter notebook for analyzing the geographical locations of the launch sites.
- `07_spacex-dashboard.ipynb`: Jupyter notebook for building an interactive dashboard to visualize launch records.
- `08_spacex-machine-learning-prediction.ipynb`: Jupyter notebook for building and evaluating machine learning models to predict Falcon 9 landing success.
- **SpaceX_Falcon_9_Landing_Prediction_Presentation.pdf:** PowerPoint presentation in PDF format summarizing the project and key findings.

## Conclusion
This project demonstrates how data science and machine learning can be used to predict the success of Falcon 9 first-stage landings, providing valuable insights into SpaceX’s launch operations. The predictive models developed in this project can assist in optimizing pricing strategies, improving operational efficiency, and offering a competitive edge against other companies in the space industry.

## Presentation
The PowerPoint presentation for this project is available in PDF format. You can view the presentation by downloading the following file:

[**SpaceX_Falcon_9_Landing_Prediction_Presentation.pdf**](./SpaceX_Falcon_9_Landing_Prediction_Presentation.pdf)


