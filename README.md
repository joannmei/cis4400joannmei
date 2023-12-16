# cis4400joannmei

Overview
This project is part of the Big Data course (CIS 4130 CMWA) conducted in Fall 2023 and provides an insightful analysis of the New York City Uber Ride Dataset from 2019 to 2022. The main objective is to develop a Linear Regression model to predict tipping behavior in Uber rides across New York City.

Data Source
The dataset, sourced from Kaggle, includes comprehensive information about Uber rides in New York City. It covers details such as TLC license numbers, timestamps of pick-ups and drop-offs, locations, fares, tolls, tips, and other related fees. The data is stored in parquet files to facilitate efficient handling of large-scale data.

Objective
The primary goal of this project is to predict tips for Uber rides using various attributes from the dataset. This prediction model is essential for enhancing customer service and optimizing driver incentives through a better understanding of tipping patterns.

Methodology
Data Acquisition and Preparation: Python, along with libraries like Pandas, PyArrow, and AWS Wrangler, was used for downloading, extracting, and processing the dataset, focusing on large file handling and data transformation.
Exploratory Data Analysis (EDA): Performed using Python libraries such as Seaborn and Matplotlib to uncover trends, correlations, and outliers in the data.
Feature Engineering: The data was cleaned and enhanced with new features, such as the ratio of tips to base fare, using PySpark and Python.
Linear Regression Modeling: Employed PySpark's machine learning libraries to develop a linear regression model for tip prediction. The model was trained and evaluated on a subset of the data, focusing on metrics like Root Mean Squared Error (RMSE) for performance assessment.
Visualization: Python and Seaborn were utilized for visualizing the relationship between actual and predicted tips, demonstrating the model's effectiveness and the data distribution.
Challenges and Learning
The project was challenging in terms of managing large datasets, refining the prediction model, and addressing data inconsistencies. These challenges provided invaluable experience in handling big data and practical data analysis.

Repository Structure
/data: Includes both the original and processed datasets.
/notebooks: Contains Jupyter notebooks that detail the exploratory data analysis and modeling process.
/src: Source code for data processing, model building, and evaluation.
/visualizations: Consists of plots and insights from the visualization efforts.

Future Work
This project lays the groundwork for further analysis, such as examining the effects of external factors like COVID-19 on ride-hailing patterns and exploring more complex modeling techniques for enhanced prediction accuracy. There is still so much more to be done.
