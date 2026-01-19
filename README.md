# Bike Sales Demographic & Behavior Analysis Dashboard

## Project Overview
This project involves a comprehensive analysis of consumer behavior for a bike retail dataset. I developed an interactive Excel dashboard that cleans and transforms raw data into actionable insights, focusing on how demographic factors like income, age, and commute distance influence purchasing decisions.

## Key Insights & Data Metrics
* **Income Benchmarking:** Identified that the average income for customers who purchased a bike is significantly higher, peaking at **$60,124** for males and **$55,774** for females.
* **Age Demographics:** Successfully segmented the customer base into three brackets, revealing that **Middle Age** individuals are the primary drivers of sales with **383 purchases**.
* **Commute Correlation:** Discovered a strong inverse relationship between commute distance and sales; customers with a **0-1 mile commute** account for **200 purchases**, while those commuting over 10 miles drop to only 33 purchases.
* **Target Segment:** The data indicates the "sweet spot" for marketing is middle-aged professionals with short commutes and an income exceeding $55,000.

## Technical Features
### 1. Data Transformation
* **Age Bracketing:** Used nested `IF` statements or VLOOKUPs to categorize raw ages into "Adolescent," "Middle Age," and "Old" for clearer trend visualization.
* **Commute Normalization:** Standardized commute distance strings to ensure logical sorting (e.g., ensuring "1-2 Miles" follows "0-1 Miles").

### 2. Interactive Visualization
* **Dynamic Slicers:** Integrated 5 interactive filters including **Marital Status**, **Region**, **Education**, **Gender**, and **Children** to allow for real-time data drilling.
* **Pivot Charting:** Utilized a combination of Clustered Bar Charts for income comparison and Line Charts for trend analysis over age and distance.

## Dashboard Components
| Component | Visual Type | Insights Provided |
| :--- | :--- | :--- |
| **Average Income** | Clustered Bar Chart | Compares purchasing power between genders. |
| **Customer Age Trend** | Line Chart with Markers | Identifies the peak purchasing lifecycle stage. |
| **Customer Commute** | Line Chart | Correlates geographic proximity to work with bike ownership. |
| **Demographic Slicers** | Slicer Panels | Enables granular analysis by region (Europe, North America, Pacific). |

## How to Use
1.  **Global Filtering:** Use the left-hand slicer panel to filter the entire dashboard by region or education level.
2.  **Comparative Analysis:** Compare the blue lines (No Purchase) against the orange lines (Purchase) to identify segments with the highest conversion potential.
