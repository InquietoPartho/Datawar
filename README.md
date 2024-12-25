# Sales Data Analysis

This project performs comprehensive sales data analysis using a dataset containing order details. The analysis covers exploratory data analysis (EDA), sales performance analysis, product-specific analysis, customer insights, and time-based trends.

## Dataset

The dataset includes the following columns:

- Order ID
- Product
- Quantity Ordered
- Price Each
- Order Date
- Purchase Address

## Analysis Criteria

### Exploratory Data Analysis (EDA)

1. **Data Overview**

   - Number of unique products
   - Range of order dates
   - Handling missing or null values
   - Identifying and removing duplicate rows

2. **Basic Statistics**

   - Average quantity ordered for each product
   - Total revenue generated from all sales
   - Minimum, maximum, and average price of products sold

3. **Data Cleaning**
   - Cleaning invalid data in the Order Date column
   - Extracting useful information from Order Date (month, day, hour)
   - Splitting Purchase Address into city, state, and ZIP code

### Sales Performance Analysis

4. **Best Month for Sales**

   - Identifying the month with the highest sales revenue
   - Visualizing sales revenue by month

5. **Best Time for Display Advertisement**

   - Analyzing hours with the highest number of orders
   - Suggesting the best time to display advertisements

6. **Most Product-Selling City**
   - Identifying the city with the highest sales revenue
   - Visualizing city-wise sales

### Product-Specific Analysis

7. **Most Sold Products**

   - Identifying the top 5 most sold products by quantity
   - Discussing possible reasons for their popularity

8. **Products Most Often Sold Together**

   - Finding product pairs frequently sold together
   - Suggesting potential bundling strategies

9. **Price vs. Quantity Relationship**
   - Analyzing the relationship between product price and quantity ordered
   - Determining if lower-priced items are sold in higher quantities

### Customer Insights

10. **Most Active Customers**

    - Identifying customers with the highest number of purchases or revenue
    - Calculating the revenue contribution of the top 10% of customers

11. **City-Wise Product Preferences**
    - Identifying popular products in different cities
    - Analyzing city-specific trends

### Time-Based Trends

12. **Weekly and Daily Patterns**
    - Identifying weekly and daily sales patterns
    - Determining the busiest days of the week for sales

## Visualizations

The analysis includes various visualizations to help understand the data better, such as:

- Bar plots for sales revenue by month and city
- Line charts for order patterns by hour and day
- Scatter plots for price vs. quantity relationship
- Bar plots for most sold products and product pairs

## Requirements

To run the analysis, you'll need Python and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/InquietoPartho/Datawar.git

   ```

2. Navigate to the project directory:

   ```bash
   cd Datawar
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook containing the analysis:

   ```bash
   jupyter notebook sales_data_analysis.ipynb
   ```

## Conclusion

This project provides insights into sales performance, product popularity, customer behavior, and time-based trends, helping to make data-driven decisions for improving sales strategies.
