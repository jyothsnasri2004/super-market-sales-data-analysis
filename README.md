# super-market-sales-data-analysis

This project presents the analysis of supermarket sales data. The primary goal is to extract actionable insights into the Product and store performance, Customer behaviour, Sales trends by exploring various aspects of the dataset, such as product line popularity, customer demographics, and payment methods, this analysis aims to identify key factors that drive sales and profitability. The findings from this project help’s in making data-driven decisions for marketing strategies, inventory management, and improving the customer experience.

## Project Goal

The main objective is to analyze the sales data to understand the different factors that contribute to revenue. This involves exploring the data to answer questions such as:

  * Which product lines are the most successful?
  * Which branch generates the most revenue?
  * What are the purchasing patterns of different customer types?
  * How do sales trends vary over time?

## The Dataset

The dataset used for this analysis represents sales transactions from three different supermarket branches. It includes the following key columns:

  * `Branch`: The store location (A, B, or C).
  * `Customer type`: Type of customer (Member or Normal).
  * `Gender`: Gender of the customer.
  * `Product line`: The general category of the product.
  * `Unit price`: The price of a single unit of the product.
  * `Quantity`: The number of units purchased.
  * `Total`: The total price of the transaction.
  * `Payment`: The payment method used (Cash, Ewallet, Credit card).
  * `Rating`: The customer's satisfaction rating for the transaction.

## Analysis and Key Findings

The analysis was conducted in the `super-market-sales-analysis.ipynb` Jupyter Notebook. The key steps included data cleaning, feature engineering (extracting month and day), and visualization.

**Key insights include:**

  * **Top Product Line:** "Fashion accessories" and "Food and beverages" are among the top-selling product lines across all branches.
  * **Branch Performance:** Branch 'A' consistently recorded the highest total sales revenue compared to branches 'B' and 'C'.
  * **Customer Insights:** While both genders contribute similarly to revenue, customers who are part of the membership program tend to have slightly higher average transaction values and provide higher ratings.
  * **Popular Payment Method:** 'Ewallet' and 'Cash' are the most frequently used payment methods by customers.
  * **Sales Trends:** The analysis of sales by month indicated fluctuations, suggesting potential seasonality in purchasing behavior.

## Technologies Used

  * **Language:** Python
  * **Libraries:** Pandas, Matplotlib, Seaborn
  * **IDE:** Jupyter Notebook

 
# Conclusion & Recommendations:

This analysis of the supermarket sales data revealed several key insights that can inform strategic decisions.

Key Findings:
•	Branch Performance: The Vizag branch generated the highest total revenue that is closely followed by Bangalore and Hyderabad. This indicates a strong market presence in Vizag that could be studied and replicated.

•	Product Line Popularity:
o	In Bangalore, the "Home and Lifestyle" product line was the most purchased.
o	In Vizag, "Food and Beverages" was the top-selling category.
o	In Hyderabad, "Health and Beauty" products were the most popular.

•	Customer Behaviour: There is a near-even split in gross income generated from Members ($7820.16) versus Normal customers ($7559.21), suggesting that both segments are almost equally valuable to the business.

•	Gender-Based Preference
•	Bangalore
Females in Bangalore most frequently purchase Fashion accessories.
Males in Bangalore show the strongest preference for Home and lifestyle products.
•	Vizag
Females in Vizag have a clear preference for Food and beverages.
Males in Vizag purchase Health and Beauty products more than any other category.
•	Hyderabad
Females in Hyderabad most often buy Fashion accessories.
Males in Hyderabad also show the highest preference for Health and Beauty products.
•	Overall: 
Female customers purchased more "Fashion Accessories" and "Food and Beverages".
Male customers showed a higher preference for "Health and Beauty" products.



Actionable Recommendations:
1. Targeted Marketing: Launch city-specific marketing campaigns based on product line popularity. Like For example, promote "Home and Lifestyle" products in Hyderabad and Vizag, and introduce targeted offers on   "Food and Beverages" in Bangalore to boost the sales in those categories.
2. Enhance Member Program: Since the gross income from Members and Normal customers is comparable, there is an opportunity to grow the loyalty program. Introduce exclusive benefits for members, such as     additional discounts or early access to sales, to encourage more sign-ups and increase their purchase frequency.
3. Gender-Specific Promotions: Tailor promotions to gender preferences. For instance, create bundled offers on "Health and Beauty" products for male customers and run special promotions on "Fashion Accessories"   for female customers to drive higher engagement and sales.

