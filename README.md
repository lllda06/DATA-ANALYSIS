📊 Data Analysis — Used Cars Dataset (EDA & Cleaning)
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA), data cleaning, and feature preparation of a dataset containing used vehicles listed for sale in the United States.

The goal is to transform raw automotive data into a clean and structured dataset ready for machine learning tasks, including price category prediction and further modeling.

🎯 Objectives

The main goals of this project are:

Perform data cleaning and preprocessing
Handle missing values and incorrect data types
Detect and remove outliers
Explore relationships between key variables
Prepare features for machine learning models
Analyze factors influencing vehicle pricing
🗂 Dataset

The dataset includes information about used cars such as:

price — vehicle price
year — year of manufacture
manufacturer — brand
model — car model
condition — condition of the vehicle
cylinders — number of cylinders
fuel — fuel type
odometer — mileage
transmission — transmission type
drive — drive type
size, type, paint_color — categorical features
price_category — low / medium / high price class
🔍 Project Workflow
1. Data Cleaning
Removal and treatment of missing values
Correction of inconsistent data types
Processing of duplicates and anomalies
2. Outlier Detection
Identified using boxplots and IQR method
Removed extreme price and mileage values
3. Exploratory Data Analysis
Price distribution analysis
Relationship between price and vehicle age
Correlation analysis (Pearson coefficient)
Manufacturer and transmission analysis
4. Feature Analysis
Identification of important variables using feature importance
Removal of features with zero or low importance
Preparation of dataset for modeling
📊 Key Insights
Newer cars are significantly more expensive (strong negative correlation with age)
Outliers often represent luxury vehicles or rare cases
Manufacturer and mileage strongly influence price
Price categories clearly separate market segments (low / medium / high)
🧠 Technologies Used
Python
Pandas
Matplotlib
Jupyter Notebook
Scikit-learn
🚗 Results

The dataset was successfully cleaned and prepared for machine learning tasks.
EDA revealed meaningful patterns in pricing behavior and key factors influencing vehicle value.

👩‍💻 Author

Lada Bahdanovich
