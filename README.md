# Blinkit Grocery Sales Analysis

## Project Summary
This project presents a comprehensive sales analysis of Blinkit grocery data, focusing on item characteristics, outlet features, and sales patterns. Using Python's data analysis libraries, we extract key business insights and visualize relationships to support strategic decision-making.

## Dataset Overview
- **Source:** Blinkit Grocery Sales (CSV format)  
- **Size:** 8,523 records × 12 columns  
- **Key Fields:**  
  - Item Fat Content  
  - Item Type  
  - Outlet Establishment Year  
  - Outlet Location Type  
  - Sales, Rating, Item Visibility, Item Weight  

## Technologies Used
- Python 3  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`  

## Execution Workflow

### 1. Data Loading & Initial Exploration
- Loaded dataset using pandas.
- Explored first/last rows, data shape, columns, and data types.

### 2. Data Cleaning
- Standardized inconsistent values in **Item Fat Content** (e.g., "LF", "low fat" → "Low Fat").
- Verified unique values after cleaning.

### 3. Key Performance Indicators (KPIs)
- **Total Sales:** $1,201,681  
- **Average Sales:** $141  
- **Number of Items Sold:** 8,523  
- **Average Rating:** 4.0  

### 4. Visual Analysis & Charts
- **Sales Insights:**  
  - Pie Chart: Total sales by item fat content.  
  - Bar Chart: Total sales by item type.  
  - Bar Chart: Outlet tier vs. fat content sales.  
  - Line Chart: Total sales over outlet establishment years.  
  - Pie Chart: Total sales by outlet size.  
  - Bar Chart: Total sales by outlet location.  

- Visuals include customized formatting (rotated x-axis labels, annotated bars, adjusted figure sizes).

## Insights Derived
- "Low Fat" items dominate sales volume.  
- Snack foods and fruits/vegetables have higher total sales.  
- Outlets established after 2015 show significant sales growth.  
- Tier 3 outlet locations contribute the most to total sales.  

## Future Improvements
- Predictive modeling using regression or machine learning for sales forecasting.  
- Customer segmentation based on buying patterns.  
- Deployment using Streamlit or Flask for interactive dashboarding.
