# BMW Car Pricing & Sales Analysis (MySQL)

A SQL project analyzing BMW car pricing and sales performance across regions, years, and fuel types.

## Dataset
- Source: Internal (BMW_Car_Sales.csv)
- Columns: Model, Year, Region, Color, Fuel_Type, Transmission, Engine_Size, Mileage_KM, Price_USD, Sales_Volume, Sales_Classification
- <a href="https://github.com/abinesh8838/Data_analysis_project/blob/main/SQL_Project/BMW_Car_Sales.csv"> Dataset view</a>

## Tech
- MySQL 8.x
- MySQL Workbench

## How to Reproduce
1. CREATE DATABASE BMW_db
2. CREATE TABLE BMW_car
3. USE bmw_db
4. Import data/BMW_car.csv.
5. Run cleaning scripts in cleaning/.
6. Create views from views/.
7. Run analysis queries from analysis/.

## Key Questions Answered
- Average Price by Fuel Type
- Top 5 Most Expensive Cars in Each Sales Classification
- Total Sales Volume by Region and Year
- Count of Cars Sold by Transmission Type
- Average Mileage by Transmission
- List Models Sold in All Regions
- Top 5 Best-Selling Regions (by Total Sales Volume)
- Count Diesel Cars Sold Each Year
- Most Popular Car Colors Across All Regions
- Average Price by Engine Size
- Max number of cars sold per year
- Region wise fuel type cars sold, order by region ascending and total volume descending.


