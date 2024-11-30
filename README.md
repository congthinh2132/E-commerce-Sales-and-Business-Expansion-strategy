# [POWER BI] E-commerce Sales and Business Expansion strategy
## I. Introduction
### 1. Dataset:
* The dataset comprises order records from a global skincare and beauty e-store, covering the period from 2020 to 2023.
* It includes one table containing the order data and another table providing descriptions of the column names.

* Table description:

| Field               | Description                                       | Type of Field |
|---------------------|---------------------------------------------------|---------------|
| Row ID             | Unique ID of the row                              | Dimension     |
| Order ID           | ID of the order (one order can have multiple items)| Dimension     |
| Order Date         | Date when order was made                          | Measure     |
| Customer ID        | ID of the customer (one customer can make multiple orders) | Dimension     |
| Segment            | Customer segment                                  | Dimension     |
| City               | Order city                                        | Dimension     |
| State              | Order state (where applicable)                   | Dimension     |
| Country            | Order country                                    | Dimension     |
| Country latitude   | Geographic coordinates of the order country       | Measure   |
| Country longitude  | Geographic coordinates of the order country       | Measure   |
| Region             | Region to which the order belongs                | Dimension     |
| Market             | Market to which the order belongs                | Dimension  |
| Subcategory        | Product subcategory                               | Dimension     |
| Category           | Product category                                  | Dimension     |
| Product            | Product name                                     | Dimension     |
| Quantity           | Number of products purchased per order            | Measure   |
| Sales              | Total sales in $                                  | Measure   |
| Discount           | Discount applied to the order                    | Measure |
| Profit             | Total profit for each order after discount       | Measure  |
### 2. Business questions:
- Provide a clear overview of the business performance in international markets for the marketing team and senior management.
- Highlight key metrics to assist senior managers in making informed decisions about market expansion and identifying suitable products for each target market.
## II. Design thinking:
Here is the five steps of desgin thinking:
### 1. Empathize:
![image](https://github.com/user-attachments/assets/a7000b05-d530-408b-b4f3-1d26d11e035c)
### 2. Define:
![image](https://github.com/user-attachments/assets/eaa8db51-f954-4ce1-afc4-786674ebdf7b)
### 3. Ideate:
![image](https://github.com/user-attachments/assets/5857df35-d9d7-4903-8b2a-4e12b314f63b)
### 4. Prototype:
![image](https://github.com/user-attachments/assets/ae067ae9-3064-429e-9ff2-7e13ba7ed78c)
### 5. Review:
![image](https://github.com/user-attachments/assets/f1692884-ffb4-4cfb-ab6e-66dfe4222eef)
## III. Visualizations:
### 1. Overview:
![image](https://github.com/user-attachments/assets/366d8eae-d365-4c64-931c-998edc7f142b)
### 2. Markets:
![image](https://github.com/user-attachments/assets/b6f78014-96bb-4fcc-8911-3b79172d134c)
### 3. Customers:
![image](https://github.com/user-attachments/assets/e84ba958-9e64-42a0-bd64-73ef26aad1e2)
### 4. Products:
![image](https://github.com/user-attachments/assets/8feb9b16-0d46-4ad7-bc7e-deb590577e2a)
## IV. Insights:
Overview:
- Revenue overall: Revenue has been steadily increasing over the past few years. The current year (CY) is showing a significant increase compared to the previous year (PY). 
- Profit overall: Profit has also increased, but it followed by the decrease in the current year(2023). Along with that, the profit margin has decreased compared to the previous year. 
- Quantity & Orders: The number of orders and quantities sold have also increased year-over-year.

Region and Country:
- Western Europe is the highest revenue-generating region, followed by Others. 
- The United States is the top revenue-generating country, followed by France and Australia.

Markets: 
- Asia Pacific was the highest revenue-generating market overall. 
- Europe was the most profitable market between 2020 and 2023.

Customers:
- Corporate customers contribute the most to revenue and profit, followed by consumers and self-employed individuals. 
- The number of customers according to Market are Asia Pacific > EU > LATAM > USCA > Africa.

Products:
- Body care is the highest revenue-generating category, followed by make-up and home & accessories.
- Body care is the highest profit-generating category, followed by make-up. In the other hand, home & accessories did not make any profit although revenue in the second place.
## V. Recommendations:
Market expansion strategy and key products:
### 1. Aggressive Expansion in High-Revenue Markets:
- Invest heavily in the Asia Pacific region, leveraging its high revenue potential.
- Build strong distribution networks and tailor marketing campaigns to regional preferences.
### 2. Strengthen Operations in Specific Regions:
- Focus on Western Europe and the United States, which offer substantial revenue contributions.
### 3. Diversify Product Offerings: 
- Launch tailored product lines in high-demand categories like Body Care and Make-up to match customer preferences.
- Address profitability issues in Home & Accessories through supply chain improvements or rebranding strategies.
### 4. Customer Segment Focus:
- Prioritize Corporate and Consumer segments for maximum revenue and profit impact.
### 5. Leverage Technology for Scale
- Use advanced data analytics and customer relationship management systems for better market insights.
- Expand e-commerce platforms to enhance shopping experiences globally.












