# Black Friday Sales Analysis

## Project Overview
This project aims to generate meaningful insights from Black Friday sales data. It involves creating a data warehouse, using Apache Airflow for ETL processes, and developing SQL reports and dashboards for business intelligence using Power BI.

## Objectives
- Extract, Transform, and Load (ETL) data using Apache Airflow.
- Analyze overall sales performance.
- Understand customer demographics.
- Identify popular products and categories.
- Examine sales trends and customer purchase behavior.

## Tools and Technologies
- Apache Airflow
- MySQL
- Power BI Desktop
- Python (Pandas, Matplotlib)
- GitHub

## ETL Process with Apache Airflow
The ETL process is managed using Apache Airflow. The `processed_sales_data` table is generated through this workflow, ensuring data is clean and ready for analysis.

### Airflow DAG
The ETL workflow is defined in an Airflow DAG:
- **Extract**: Load raw data from the source.
- **Transform**: Clean and process the data.
- **Load**: Insert processed data into the MySQL database.

## Database Schema
- **Tables**: `black_friday_sales`, `processed_sales_data`
- **Views**: `vw_age_distribution`, `vw_city_category_distribution`, `vw_clv_analysis`, `vw_gender_distribution`, `vw_marital_status_distribution`, `vw_most_purchased_products`, `vw_number_of_transactions`, `vw_occupation_distribution`, `vw_product_categories_cross_analysis`, `vw_product_categories_highest_sales`, `vw_product_categories_popularity`, `vw_purchase_behavior_stay_city_years`, `vw_purchase_correlation_age_gender`, `vw_purchases_across_product_categories`, `vw_sales_amount_by_city_category`, `vw_sales_trend`, `vw_total_sales_amount`

## Data Analysis
### Overall Sales Analysis
1. Total Sales Amount
2. Number of Transactions

### Customer Demographics
1. Distribution of Gender
2. Age Distribution
3. Marital Status Distribution
4. Distribution of Occupations

### Product Analysis
1. Most Purchased Products
2. Product Categories with the Highest Sales
3. Distribution of Purchases Across Product Categories

### City Analysis
1. Distribution of Customers Across Different City Categories
2. Sales Amount by City Category

### Purchase Behavior
1. Analysis of Purchase Behavior Based on Stay in Current City Years
2. Correlation Between Purchase Amount and Other Factors (e.g., Age, Gender)

### Product Categories
1. Analysis of Product Categories and Their Popularity
2. Cross-Analysis of Product Categories with Other Factors (e.g., Gender, Age)

### Customer Lifetime Value (CLV)
1. CLV Analysis Based on Various Customer Segments (Age, Gender, City Category)

### Trend Analysis
1. Sales Trend Over Time

## Visualizations
Visualizations created using Power BI Desktop are divided into 8 pages, each focusing on different aspects of the analysis.

## How to Use This Repository
1. Clone the repository: `git clone <repository-url>`
2. Set up Apache Airflow and load the provided DAG.
3. Load the provided SQL scripts to set up the database and views.
4. Open the Power BI file to explore the visualizations.

## Contributing
Contributions are welcome! Please create a pull request or submit issues for any suggestions or improvements.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact [Your Name] at [Your Email].

