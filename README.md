# Restaurant Sales & Customer Analysis  

## Project Overview  
This project aims to analyze restaurant sales data to **optimize revenue, understand customer behavior patterns, and improve marketing strategies**.  

By processing and visualizing data, we can gain valuable insights into **sales trends, customer preferences, and menu performance**, helping restaurant owners make data-driven decisions.

## **This is the actual dataset I used for analysis when I worked at a restaurant four years ago** .

---

## Process Breakdown  

### 1️ Data Preprocessing  
- Handling missing values & outliers  
- Converting time data & calculating visit duration  
- Splitting multiple menu items into separate rows (`explode()`)  

### 2️ Data Analysis  
- **Customer behavior analysis** (visiting time, spending patterns)  
- **Sales analysis** (daily & hourly sales trends, top-selling items)  
- **Menu performance analysis** (high & low revenue items)  

### 3️ Data Visualization (Seaborn & Matplotlib)  
- **Revenue trends** (heatmaps, line charts)  
- **Customer behavior** (visits per time slot)  
- **Menu sales distribution** (bar charts, pie charts)  

### 4️ Power BI Visualization  
To enhance data presentation and **create interactive dashboards**, we also utilize **Power BI** for visualizations, including:  
- **Dynamic Sales Dashboard** (filterable by date, time, and menu category)  
- **Revenue Breakdown by Menu** (interactive bar & pie charts)  
- **Customer Visit Trends** (heatmaps and line charts)  

---

## Why Use Two Datasets?  
This project uses **two datasets** for different analysis purposes:

1️ **Original Dataset (`df`)** → **Customer & Order-Based Analysis**  
   - Customer count (`Customers`), total order revenue (`Price`), visit time analysis  
   - Used for **sales trends & customer behavior insights**  

2️ **Exploded Dataset (`df_exploded`)** → **Menu-Based Analysis**  
   - Individual menu item sales (`Menu_Price`), top-selling items  
   - Used for **menu performance & revenue contribution analysis**  

By separating the datasets, we avoid **duplicate revenue calculations** and ensure **accurate insights**.

---

## Files in This Repository  
- **`restaurant_analysis.ipynb`** → Full preprocessing, analysis & visualization in Python  
- **`Final_Original_Restaurant.csv`** → Processed dataset for further analysis
- **`Final_Exploded_Restaurant.csv`** → Processed dataset for further analysis
- **`restaurant_dashboard.pbix`** → Power BI interactive dashboard file  
- **`README.md`** → Project documentation  

 **This project provides a complete workflow from data processing to interactive visualization, helping restaurants make better business decisions!**



```python

```
