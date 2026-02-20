# Global Cars – Exploratory Data Analysis (EDA)

## Objective
The goal of this project is to perform exploratory data analysis (EDA) on global car data to understand pricing patterns, identify top brands and manufacturing countries, compare categories (fuel/body type), and explore trends over manufacture years.

## Dataset
The dataset `global_cars_enhanced (1).csv` contains car records with the following columns:
- Car_ID
- Brand
- Manufacture_Year
- Body_Type
- Fuel_Type
- Transmission
- Engine_CC
- Horsepower
- Mileage_km_per_l
- Price_USD
- Manufacturing_Country
- Car_Age
- Price_Category
- HP_per_CC
- Age_Category
- Efficiency_Score

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

## Data Cleaning
- Stripped column names to avoid spacing issues.
- Converted numeric fields (e.g., Price_USD, Horsepower, Engine_CC, Mileage_km_per_l) to numeric types.
- Removed missing/invalid values in key columns needed for analysis (Price_USD, Manufacture_Year).

## Analysis Performed
- Summary statistics and missing value checks
- Total/average/median price analysis
- Top brands by total price
- Top manufacturing countries by total price
- Category comparisons (Fuel Type, Body Type)
- Time-based trend by manufacture year
- Price distribution visualization
- Relationship analysis (Price vs Horsepower)
- Correlation heatmap for numeric variables

## Key Insights
- The top brand and top manufacturing country contribute the highest total price (USD).
- Higher horsepower generally corresponds to higher price.
- Fuel type and body type show different total sales values across categories.
- Total price varies across manufacture years, showing changes in market patterns over time.

## Conclusion
This EDA highlights key drivers of car pricing and differences across brands, countries, and categories. The results can support decisions related to market targeting, inventory focus, and understanding factors influencing car prices.
