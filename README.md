# EDA_-Cafe-Sales-Data
This dataset contains 10,000 rows across 8 columns of synthetic data representing sales transactions in a cafe.
Transaction ID: Unique identifier for each transaction.

Item: The product purchased (e.g., Coffee, Cake, Sandwich).

Quantity: The number of units purchased.

Price Per Unit: The price of a single unit of the product.

Total Spent: The total amount spent in the transaction.

Payment Method: Method used for payment (e.g., Digital Wallet, Credit Card).

Location: The location where the purchase occurred (e.g., Takeaway, In-store).

Transaction Date: The timestamp of when the transaction occurred.

Activity Objectives
The objective of this case study is to perform a thorough exploratory data analysis (EDA) and gain insights into the cafe's sales data. The key activities involved include:

1. Data Cleaning :
Handle Missing Values: Identifying missing data and deciding whether to drop or impute missing values based on the context.

Standardize Data Formats: Ensuring consistency in categorical variables (such as product names and payment methods) and converting date columns into a standardized format for easier analysis.

2. Outlier Detection :
Detect Outliers: Identifying anomalies in sales data (e.g., extremely high or low quantities or spending) using statistical methods like Z-score or IQR.

Treat Outliers: Deciding on the appropriate treatment for the detected outliers, such as capping, transformation, or removal, based on their potential impact on the analysis.

3. Data Visualization :
Sales Trends: Creating line plots to visualize sales trends over time and bar charts to explore sales by product category.

Customer Behavior: Using pie charts to understand the distribution of purchases among customer segments and heatmaps to identify peak sales hours or days.

4. Feature Engineering :
Create New Features: Deriving new features like "Total Sale" by multiplying quantity and unit price. Also, extracting the "Day of Week" and "Hour" from the timestamp to analyze temporal patterns.

Encode Categorical Variables: Applying one-hot encoding to categorical features to prepare the data for machine learning analysis.
