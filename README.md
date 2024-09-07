# customer-segmentation

## Project Overview
This project aims to analyze customer data to better understand different customer segments. By performing customer personality analysis, businesses can tailor their products and marketing strategies to the specific needs and behaviors of their customers. This allows for targeted marketing, optimizing product offerings, and improving customer satisfaction by focusing efforts on high-potential customer segments.

## Problem Statement
Customer personality analysis enables businesses to modify products based on their target customers from various customer segments. For example, instead of marketing a product to every customer in a company’s database, businesses can analyze which customer segment is most likely to buy the product. This project focuses on performing clustering to identify customer segments, allowing businesses to market products more effectively.

## Dataset
The dataset used for this analysis contains information about customers, their demographics, purchasing behavior, and responses to marketing campaigns. Below are the key attributes:

### Attributes

#### People
- **ID**: Unique identifier for each customer
- **Year_Birth**: Customer's birth year
- **Education**: Education level of the customer
- **Marital_Status**: Marital status of the customer
- **Income**: Yearly household income
- **Kidhome**: Number of children in the household
- **Teenhome**: Number of teenagers in the household
- **Dt_Customer**: Date the customer enrolled with the company
- **Recency**: Number of days since the customer's last purchase
- **Complain**: Whether the customer complained in the last 2 years (1 = Yes, 0 = No)

#### Products
- **MntWines**: Amount spent on wine in the last 2 years
- **MntFruits**: Amount spent on fruits in the last 2 years
- **MntMeatProducts**: Amount spent on meat in the last 2 years
- **MntFishProducts**: Amount spent on fish in the last 2 years
- **MntSweetProducts**: Amount spent on sweets in the last 2 years
- **MntGoldProds**: Amount spent on gold in the last 2 years

#### Promotion
- **NumDealsPurchases**: Number of purchases made with a discount
- **AcceptedCmp1**: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
- **AcceptedCmp2**: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
- **AcceptedCmp3**: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
- **AcceptedCmp4**: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
- **AcceptedCmp5**: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
- **Response**: 1 if the customer accepted the offer in the last campaign, 0 otherwise

#### Place
- **NumWebPurchases**: Number of purchases made through the company’s website
- **NumCatalogPurchases**: Number of purchases made using a catalog
- **NumStorePurchases**: Number of purchases made directly in stores
- **NumWebVisitsMonth**: Number of visits to the company’s website in the last month

## Objective
The goal of this project is to perform clustering on the dataset to summarize customer segments. This will help identify patterns and group customers with similar purchasing behaviors and responses to promotions, providing insights for more efficient marketing strategies.

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of key variables and customer behaviors.
3. **Clustering**: Applying clustering algorithms (such as K-Means) to group customers based on their similarities.
4. **Analysis of Segments**: Interpreting the results of clustering to identify key customer segments and their characteristics.
5. **Conclusion & Recommendations**: Providing actionable insights for targeted marketing strategies.

