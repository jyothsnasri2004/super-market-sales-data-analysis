# super-market-sales-data-analysis
# Introduction:

This project presents the analysis of supermarket sales data. The primary goal is to extract actionable insights into the Product and store performance, Customer behaviour, Sales trends by exploring various aspects of the dataset, such as product line popularity, customer demographics, and payment methods, this analysis aims to identify key factors that drive sales and profitability. The findings from this project help’s in making data-driven decisions for marketing strategies, inventory management, and improving the customer experience.

# Data-set:

The dataset used for this analysis is sales.csv, which contains detailed transaction records from a supermarket. Each record represents a single sale and includes the following attributes:
* **Invoice ID: A unique identifier for each transaction.
* **Branch: The branch of the supermarket (A, B, or C).
* **City: The location of the branch (Banglore, Vizag, Hyderabad).
* **Customer type: Type of customer (Member or Normal).
* **Gender: Gender of the customer (Male or Female).
* **Product line: The category of the product purchased.
* **Unit price: The price of a single unit of the product.
* **Quantity: The number of units of the product purchased.
* **Tax 5%: The 5% tax applied to the transaction.
* **Total: The total cost of the transaction (Unit price * Quantity + Tax 5%).
* **Date: The date of the transaction.
* **Time: The time of the transaction.
* **Payment: The payment method used (Ewallet, Cash, Credit Card).
* **cogs: Cost of goods sold.
* **gross margin percentage: The gross margin percentage.
* **gross income: The gross income from the sale.
* **Rating: Customer rating of the shopping experience (out of 10).


# Exploratory Data Analysis (EDA):


The core of this project is the exploratory data analysis, where we ask and answer key questions about the sales data.
Key Questions Addressed:
1.	Product Performance: Which product lines are the most popular and which generate the most revenue?
2.	Sales by Location: How do sales compare across different branches and cities?
3.	Customer Insights: What are the purchasing patterns of different customer types (Member vs. Normal), genders and cities?
4.	Payment Methods: What is the most frequently used payment method across different cities and customer types?
5.	Customer Satisfaction: Is there a correlation between customer rating and other variables like total spending or product line?


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

