# Used Cars EDA 🚗📊

**Exploratory Data Analysis of Used Cars: Visualizing Prices, Outliers, and Key Features**

---

## 📌 Project Overview

In this project, I explored a dataset of used cars listed for sale in the United States. The goal was to clean the data, detect anomalies, and visualize relationships between car characteristics and price categories.  

This analysis helps to understand pricing patterns, highlight outliers, and identify key features that influence car prices.  

---

## 🗂 Dataset

The dataset used in this project is stored in `data/vehicles_dataset_upd.csv` and contains the following columns:

- `id` – record identifier  
- `price` – vehicle price  
- `year` – year of manufacture  
- `manufacturer` – car manufacturer  
- `model` – car model  
- `condition` – condition of the car  
- `cylinders` – number of cylinders  
- `fuel` – fuel type  
- `odometer` – mileage in miles  
- `transmission` – transmission type  
- `drive` – drive type  
- `size` – car size  
- `type` – body type  
- `paint_color` – color  
- `price_category` – low, medium, or high price category  
...and other relevant features.

---

## 🔍 Analysis Steps

1. **Data Cleaning and Outlier Detection**  
   - Identified anomalous prices using histograms, boxplots, and IQR method.  
   - Removed outliers to focus on the main data distribution.

2. **Price vs Year Analysis**  
   - Explored the relationship between vehicle price and year of manufacture.  
   - Visualized trends with scatter and line plots.  
   - Calculated Pearson correlation coefficient to quantify linear relationship.

3. **Price Category Analysis**  
   - Visualized distribution of prices for low, medium, and high categories.  
   - Used scatter plots to examine price and year by category.

4. **Categorical Feature Visualization**  
   - Analyzed car manufacturers and transmission types.  
   - Created bar charts and pie charts to visualize categorical distributions.

---

## 📊 Key Visualizations

- Histogram of vehicle prices  
- Boxplot for price outliers  
- Scatter and line plots: price vs year  
- Price distributions by price category  
- Bar chart of manufacturers  
- Pie chart of transmission types  

---

## 💻 Technologies & Tools

- Python 3.x  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

## 🔗 Conclusion

- There is a **strong positive correlation** between vehicle age and price: newer cars are generally more expensive.  
- Outliers mostly represent special cases: premium manufacturers or very low mileage vehicles.  
- Visualizations reveal patterns in price distribution, manufacturer contribution, and transmission type popularity.  

This project demonstrates my ability to perform **data cleaning, exploratory analysis, and insightful visualizations** using Python.  

---

---

## 📌 Author

Lada Bahdanovich
