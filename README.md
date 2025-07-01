# CAPSTONE-KMS-PROJECT-DOCUMENTATION

Project Title:

Business Intelligence Analysis for KMS: Sales, Shipping, and Customer Insights (2009–2012)


 ## Project Overview
This repository showcases my capstone project, which centers on Kultra Mega Stores (KMS), headquartered in Lagos, Nigeria, specializes in the retail and wholesale distribution of office supplies and furniture. Its customer segments include:
	•	Individual consumers (Consumer)
	•	Small businesses (Retail)
	•	Large corporate organizations (Wholesale)

KMS operates across multiple regions in Nigeria and is seeking data-driven insights to optimize performance, particularly in its Abuja division.

### Objective
The management of KMS engaged you as a Business Intelligence Analyst to:
	•	Analyze sales, customer, and shipping data from 2009 to 2012
	•	Identify performance trends and inefficiencies
	•	Provide actionable recommendations to enhance revenue and reduce revenue
 
### Tools Used

• Sql ( for quering, aggregating ,flitering large database)

• Github for buildiing portfolio

###  Key Insight
  •	Highest Sales: Technology category led in overall revenue
  
  •	Top Region: Abuja topped the sales charts; Ibadan performed the lowest.
  
  •	Shipping Cost Insight: First Class shipping incurred the highest cost; switch high-volume non-urgent orders to Standard Class or Truck.
  
  •	Customer Growth Plan: Offer loyalty programs or tailored promotions to bottom 10 customers.
  
  •	Customer Insights: Most valuable customers consistently purchased high-margin items like office chairs and IT equipment.


####  Analysis
The analysis was conducted usingStructured Query Language -SQL and it was used for Querying, joins, aggregations, subqueries, analytics, following a series of steps outlined below:

Uploading the Dataset into SQL Database: The KMS Superstore dataset was imported into a relational database system (e.g., Microsoft SQL Server).

A new table (e.g., KMS_Superstore_Data) was created

Data types were defined for each column (e.g., Sales as FLOAT, Order_Date as DATE).

Any import errors (e.g., due to NULL values or formatting issues) were resolved before proceeding.

Verifying the Structure and Contents of the Table.

Exploring the Dataset (Exploratory SQL Checks).

Cleaning or Handling Missing Values: Replaced NULL values with appropriate placeholders (e.g., 0 for numeric fields, or excluded them from calculations).

Writing SQL Queries to Answer Each Business Question

Interpreting Query Results: Query outputs were analyzed to extract meaningful insights.

Numeric results (like total sales, shipping cost, number of orders) were compared across groups.

Patterns and anomalies (e.g., extremely low sales in certain regions) were noted.

Documenting and Communicating the Insights: Each result was translated into a business insight (e.g., “Technology is the top-selling category”).

Recommendations were generated based on patterns observed.

These insights were grouped under each case scenario to align with business objectives.

 ### SQL QUERIES
Case Scenario I
Question 1: Which product category had the highest sales?
	•	Group by Product Category
	•	Sum the Sales values
	•	Sort in descending order

 ```sqlSELECT TOP 1 [Product_Category],SUM(Sales) AS Total_Sales
FROM [dbo].[KMS sql Case Study]
GROUP BY [Product_Category]
ORDER BY Total_Sales DESC;
```
KEY INSIGHT

Based on the analysis of KMS’s order data from 2009 to 2012, the product category with the highest total sales is:
 Technology

This category consistently outperformed others in terms of total revenue generated, indicating strong customer demand for tech products such as printers, laptops, and accessories.

OPERATIIONAL IMPACT

High sales in the Technology category reflect:
	•	Strong customer interest and purchasing power in tech.
	•	Potential for higher profit margins due to premium pricing.
	•	High repeat purchase rate, especially among corporate clients and businesses.

STRATEGIC STEPS FOR KMS
1.	Segment Customers by Tech Purchases
Identify top customers who frequently purchase technology products — are they consumers, small businesses, or corporate clients?

2.	Analyze Product-Level Performance
Drill down into which specific tech items (e.g., printers, routers, laptops) are leading the sales to focus stocking and promotions.
	
 3.	Check Profitability
Ensure that high sales are also yielding healthy profit margins — not just volume.

 Recommendation
	1.	Double Down on High-Demand Tech Products
Expand inventory for best-selling items in the Technology category, especially those with consistent demand.
	
 2.	Create Bundle Offers or Packages
Offer product bundles (e.g., printers + ink, laptop + accessories) to increase average order value.
	
 3.	Targeted Marketing Campaigns
Run digital ads or email promotions focused on tech deals — especially to repeat or business customer

 

RESULTS


<img width="344" alt="sq 1" src="https://github.com/user-attachments/assets/b5418d5b-7676-4f56-9289-4cfa3bbf3335" />
