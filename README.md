# DataCleaning_Python_Project

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Data Cleaning Techniques](#data-cleaning-techniques)
- [Features](#features)
- [Visualizing Outliers](#visualizing-outliers)
- [Usage](#usage)
- [References](#references)

## Overview
- This project focuses on data cleaning using Python and aims to enhance the quality and reliability of a dataset. By applying various data cleaning techniques, the project preprocesses the data to handle missing values and outliers effectively. The ultimate goal is to improve the integrity of the dataset, enabling more accurate analysis and modeling.

## Installation
- To run this project, the following libraries are required:

-pandas

-numpy

-scikit-learn

You can install these libraries using the following command:

   ```shell
  pip install pandas numpy scikit-learn

   ```
## Features
- The main features of this project include:

Missing Value Imputation: The project implements the imputation of missing values using the mean of columns for males and females separately. This approach takes into account the gender-specific characteristics, resulting in more accurate estimates. Additionally, for certain columns, missing values are imputed with the mode (most frequent values) to capture the dominant patterns.

Predicting Missing Values: The project utilizes the K-nearest neighbors (KNN) algorithm to predict missing values of categorical variables. By training the KNN model on the available data, it can make informed predictions for the missing values based on similarities with neighboring data points.

Outlier Detection and Removal: The project includes visualization techniques, such as scatter plots, to identify outliers. Outliers are data points that deviate significantly from the majority. By visualizing and detecting these outliers, appropriate actions can be taken, such as removing them from the dataset. This step helps eliminate potential noise and enhances the overall quality of the data.

## Data Cleaning Techniques
- The data cleaning techniques employed in this project include:

Missing Value Imputation: Missing values are imputed using the mean of columns for males and females separately. The imputation process considers gender-specific characteristics, resulting in more accurate estimations. For certain columns, missing values are imputed with the mode (most frequent values) to capture the dominant patterns.

KNN Prediction: The K-nearest neighbors (KNN) algorithm is applied to predict missing values of categorical variables. The KNN model is trained on the available data and can make informed predictions for the missing values based on similarities with neighboring data points.

## Visualization
- This project utilizes various visualization techniques to aid in data analysis and cleaning. Scatter plots are employed to visualize outliers, which are data points deviating significantly from the majority. The project identifies these outliers and takes appropriate actions, such as removing them from the dataset, to eliminate potential noise and enhance the overall quality of the data.

## Usage

1. **Notebook**: The Python notebook `DSproject1cleaning.ipynb` contains the code for data cleaning and analysis. Open the notebook in Jupyter Notebook or Jupyter Lab to view and run the code. Make sure to have the required dependencies installed (see the "Installation" section).

2. **Data Files**: The project includes the following data files:
   - `yrbss.csv`: This file contains the raw data that was used for analysis.
   - `DSprocessed1.csv`: This file contains the cleaned and processed data after applying data cleaning techniques.

3. **Running the Notebook**: To run the notebook, follow these steps:
   - Open the notebook in Jupyter Notebook or Jupyter Lab.
   - Set the file paths for the raw and processed data files according to your local directory structure.
   - Execute each cell in the notebook to perform the data cleaning and analysis steps.

4. **Interacting with the Data**: You can explore the processed data by loading the `processed_data.csv` file into your preferred data analysis tool or library, such as Pandas. Use the data for further analysis, visualization, or modeling.

Note: Before running the notebook, make sure to have the required dependencies installed (see the "Installation" section) and update the file paths if necessary.


## References
- Explored through various datasets from websites like: https://vincentarelbundock.github.io/Rdatasets/datasets.html
This project makes use of Python libraries such as pandas, numpy, and scikit-learn. The main purpose is to clean and preprocess the data, handle missing values, predict missing values using KNN, and visualize and remove outliers. For more detailed information and code implementation, please refer to the comments provided in the Python notebook.



