# Exploratory Data Analysis (EDA) on Flipkart Data
![Flipkart-logo](https://github.com/user-attachments/assets/b791c1e7-2cb5-4230-bbdc-12e40da060b3)


## Introduction
This project involves  an Exploratory Data Analysis (EDA) on a sales dataset  from Flipkart. The goal of this analysis is to uncover insights related to customer demographics, purchasing behavior, and sales trends.

## Dataset

The dataset used in this analysis is `Flipkart.csv`, which contains the following columns:

- **User_ID**: Unique identifier for each user
- **Cust_name**: Customer name
- **Product_ID**: Unique identifier for each product
- **Gender**: Gender of the customer
- **Age Group**: Age group of the customer
- **Age**: Age of the customer
- **Marital_Status**: Marital status of the customer (0: Single, 1: Married)
- **State**: State where the customer is located
- **Zone**: Zone where the customer is located
- **Occupation**: Occupation of the customer
- **Product_Category**: Category of the product purchased
- **Orders**: Number of orders made by the customer
- **Amount**: Total amount spent by the customer
- **Status**: Unused column
- **unnamed1**: Unused column

## Data Processing

The dataset undergoes several data cleaning steps, including:

1. **Removing Unrelated Columns**: Columns `Status` and `unnamed1` are removed as they are not relevant to the analysis.
2. **Handling Missing Values**: Rows with missing values in the `Amount` column are dropped.
3. **Data Type Conversion**: The `Amount` column is converted to integer type for consistency.

## Exploratory Data Analysis (EDA)

### Gender

The analysis of the `Gender` column reveals the distribution of orders and total amount spent by gender. The data shows trends in purchasing power and preferences between male and female customers.

### Age

Examining the `Age Group` and `Age` columns provides insights into the age distribution of customers and how it correlates with purchasing behavior and total expenditure.

### State

The `State` column is analyzed to identify the top states based on the number of orders and total sales. This helps in understanding regional sales performance and identifying key markets.

### Marital Status

The `Marital_Status` column is evaluated to assess the impact of marital status on purchasing patterns. The analysis highlights differences in spending between single and married customers.

### Occupation

Insights are drawn from the `Occupation` column to determine the prevalent occupations among buyers and their spending patterns. This helps in understanding which professional groups contribute most to sales.

### Product Category

The `Product_Category` column is analyzed to identify the most popular product categories and their sales performance. This provides insights into consumer preferences and product demand.

## Conclusion
- Maximum orders are placed by females aged between 26-35 years.

- Maximum orders are placed from UP, Maharashtra, and Karnataka.

- The majority of customers are from the IT sector, healthcare, and aviation.

- Top product categories are clothing, food, and electronics."



