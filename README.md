# CAPSTONE-KMS-PROJECT-DOCUMENTATION

## Project Title:

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

### Key Insight

  •	Highest Sales: Technology category led in overall revenue
  
  •	Top Region: Abuja topped the sales charts; Ibadan performed the lowest.
  
  •	Shipping Cost Insight: First Class shipping incurred the highest cost; switch high-volume non-urgent orders to Standard Class or Truck.
  
  •	Customer Growth Plan: Offer loyalty programs or tailored promotions to bottom 10 customers.
  
  •	Customer Insights: Most valuable customers consistently purchased high-margin items like office chairs and IT equipment.


 ### Analysis
 
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
 
## Case Scenario I

## QUESTION 1:


Based on the analysis of KMS’s order data from 2009 to 2012, the product category with the highest total sales is: Technology

This category consistently outperformed others in terms of total revenue generated, indicating strong customer demand for tech products such as printers, laptops, and accessories.

 ### OPERATIONAL IMPACT

High sales in the Technology category reflect:

•	Strong customer interest and purchasing power in tech.

 
•	Potential for higher profit margins due to premium pricing.

 
•	High repeat purchase rate, especially among corporate clients and businesses.


### STRATEGIC STEPS FOR KMS

1.	Segment Customers by Tech Purchases
Identify top customers who frequently purchase technology products — are they consumers, small businesses, or corporate clients?

2.	Analyze Product-Level Performance
Drill down into which specific tech items (e.g., printers, routers, laptops) are leading the sales to focus stocking and promotions.
	
 3.	Check Profitability
Ensure that high sales are also yielding healthy profit margins — not just volume.

### Recommendations 

1.	Double Down on High-Demand Tech Products
Expand inventory for best-selling items in the Technology category, especially those with consistent demand.
	
 2.	Create Bundle Offers or Packages
Offer product bundles (e.g., printers + ink, laptop + accessories) to increase average order value.
	
 3.	Targeted Marketing Campaigns
Run digital ads or email promotions focused on tech deals — especially to repeat or business customer



### RESULT



<img width="344" alt="sq 1" src="https://github.com/user-attachments/assets/b5418d5b-7676-4f56-9289-4cfa3bbf3335" />



## QUESTION 2: 

Analysis of KMS’s 2009–2012 sales data reveals the following:

 Top 3 Regions by Sales:
 
Abuja

Lagos

Port Harcourt

These regions consistently contributed the highest total sales across all product categories.

 Bottom 3 Regions by Sales:
 
 Ibadan
 
  Kano 
  
  Benin

These areas recorded the lowest sales volumes, indicating weaker customer activity or market penetration.


### Operational Impact

Understanding regional sales performance highlights where the company is thriving and where it’s underperforming.
	
 •	High-performing regions like Abuja and Lagos are likely benefiting from:
 
 •	Larger population and commercial presence
 
 •	Greater demand for office and tech supplies
 
 •	Better logistics and delivery coverage
 
 •	Low-performing regions may face
 
•	Poor brand awareness

•	Supply chain issues

This insight enables data-driven regional planning and resource optimization.


 ### Recommendation

 For Top Regions:

Double Down on Investment
Increase inventory, staffing, and promotional activities to maintain momentum.


Offer Premium Services
Consider loyalty programs, faster delivery options, or volume discounts to corporate clients.


Study What Works
Analyze what’s driving sales in these regions — customer preferences, marketing channels, or top-selling products — and replicate the strategy in other areas.


 For Bottom Regions:
 
Investigate the Root Causes
Use surveys or local feedback to understand low engagement such as pricing, delivery delays, or product mismatch


Localized Marketing Campaigns
Run geo-targeted ads, offer region-specific discounts, or host awareness campaigns to grow visibility.


 Partnerships or Outreach
 with local businesses or retailers to distribute products and build presence.



### RESULTS 



<img width="296" alt="sq 2b" src="https://github.com/user-attachments/assets/c04388ec-127a-424e-a805-1a4827dc9de0" />
<img width="310" alt="sq 2" src="https://github.com/user-attachments/assets/c84a22dc-13fb-4520-a2be-e99c704b225e" />


## QUESTION 3: 


### RESULT 

<img width="377" alt="sq 3" src="https://github.com/user-attachments/assets/049084f0-4094-4332-ae3e-2db9c5f8670a" />




### Key Insight

Appliance sales in Ontario are moderate to low, suggesting either:
	•	Weak customer demand for this product type in the region, or
	•	A possible lack of product availability, marketing, or awareness.

It also may indicate that customers in Ontario prioritize other categories like technology or office supplies over appliances.


 ### Operational Impact

This insight can inform product and regional strategy decisions:

For Inventory & Distribution

•	Reduce or optimize appliance stock levels in Ontario to prevent overstocking.

•	Focus warehouse space and logistics on higher-demand products for the region.

 For Marketing & Sales Strategy
 
 •	Run targeted promotions or bundles to improve appliance sales in Ontario.
 
 •	Investigate local competitors’ offerings — KMS may be losing market share due to pricing, availability, or brand preference.



 ### Recommendation

 •	Conduct a market survey in Ontario to understand low appliance uptake. are customers aware? Is pricing an issue? Are delivery times too long?
 
 •	Bundle appliances with tech or furniture products to drive interest.


## QUESTION 4: 

### Key Insight

The bottom 10 customers contribute the least revenue over the 4-year period. These could be:

One-time buyers

Inactive or infrequent customers

Customers with low-value orders

They represent untapped growth potential.

### Operational Insight
Increasing revenue from these customers is often more cost-effective than acquiring new ones.

They already know the brand they just need the right incentives or engagement to spend more.

### Proposing Action Plans

1. Customer Segmentation & Profiling
Identify which segment these customers belong to: Consumer, Small Business (Retail), or Corporate.

Understand their purchase history — what did they buy? How often? At what price point?

2. Personalized Promotions
Offer targeted discounts or bundles based on their previous purchases.

Example: If a customer bought office chairs, offer a 10% discount on matching desks or accessories.

Use email or SMS to deliver exclusive time-limited deals.

 3. Loyalty & Referral Programs
Introduce a basic loyalty program that rewards repeat purchases.

Offer referral bonuses for recommending new customers or placing bulk orders.

4. Account Manager Follow-up
Assign a sales rep to contact these customers directly.

Understand why they stopped ordering.

Offer personalized support or a special deal to win them back.

5. Product Education & Awareness
Send out product guides, catalogues, or tutorials to show how KMS products meet their needs.


###  Recommendation
To boost revenue from the bottom 10 customers, KMS should:

Re-engage them with personalized communication and offers

Build trust and convenience through tailored service

Monitor their response and adjust strategies accordingly

This approach not only increases revenue but can reactivate dormant customers into long-term buyers.

### Result
<img width="386" alt="sq 4" src="https://github.com/user-attachments/assets/d0d3c7b4-ae0e-4468-aa3e-72caabdc88cf" />


## QUESTION 5:

After analyzing the shipping data from 2009 to 2012, the shipping method with the highest cumulative shipping cost was

<img width="401" alt="sq 5" src="https://github.com/user-attachments/assets/1f184e23-4b8f-4e0b-9837-6ab2b53dad4d" />

### Key Insight
This method, while potentially faster or preferred by high-value customers, is also driving up logistics costs significantly.

It may be:

Overused even for low-value or non-urgent orders.

The default option for specific customer types (e.g., corporate clients).

In need of stricter qualification criteria (e.g., minimum order value).


 ### Operational Impact
 
 Cost Efficiency
High cumulative shipping costs eat into profit margins, especially if not offset by order size or product value.
Overuse of expensive shipping methods without revenue justification can lead to unnecessary overhead.

 
 Profit Margin Management
Some products may become unprofitable when paired with high-cost shipping (especially low-margin items).
There is a need to balance speed with cost, particularly for non-urgent deliveries.

Policy & Automation
KMS may lack a shipping policy that assigns methods based on order value, urgency, or customer tier.
The company may also benefit from automating shipping selection in their ordering system.

### Strategic Recommendation
Revise Shipping Policy
Only allow premium shipping methods (e.g., First Class, Express Air) for:

High-value orders

Urgent deliveries

Premium customers (corporate or VIP)

Introduce Shipping Thresholds
Offer free or discounted shipping only if the order exceeds a certain value.

Promote Economical Options
Encourage Standard or Truck delivery for regular customers through discounts or extended delivery windows.

## Case Scenario II 

##  QUESTION 6:

 ### Insight:
 
Top customers are mostly corporate clients, and they consistently purchase technology and office furniture—high-value items that drive most of KMS’s revenue.


### Recommendation:
Offer VIP loyalty perks or account management to retain them.

Upsell premium or bundled products based on their buying patterns.

### Result

<img width="409" alt="sq 6" src="https://github.com/user-attachments/assets/d7c78c18-a2ee-4ee6-a94f-8647a9cdd1f7">


## QUESTION 7:

 ### Insight:
The highest-spending small business customer shows strong loyalty. They may rely on KMS for operational needs like printers, desks, or bulk stationery.

### Recommendation:
Provide business-specific deals and reorder options.

Introduce monthly or quarterly subscriptions for their most-used items.

### Result

 <img width="359" alt="sq 7" src="https://github.com/user-attachments/assets/fb60e1df-36b3-4b1e-b193-973d51e7ba78" />

## QUESTION 8:

### Insight:
This customer values reliability and convenience over one time bulk orders—they place frequent orders, which makes them ideal for contract-based sales.

###  Recommendation:
Offer priority processing or dedicated account support.

Consider volume-based pricing tiers or yearly supply contracts.

### Result
<img width="505" alt="sq 8" src="https://github.com/user-attachments/assets/d3cbfdf1-2c0f-41cd-9752-1e150574c768" />

## QUESTION 9:

### Insight:
This customer may frequently buy mid- to high value items without discount codes or returns making them more profitable than those with higher sales but lower margins.

### Recommendation:
Identify and replicate what drives this customer’s behavior (e.g., product choices, order frequency).

Offer referral bonuses or appreciation incentives to encourage repeat business.

### Result

<img width="372" alt="sq 9" src="https://github.com/user-attachments/assets/38b389cf-4d42-4559-bb93-903e5980593f" />

## QUESTION 10:

### Insight:
Returns might be more common among consumer or retail customers, possibly due to order errors or dissatisfaction.

 ### Recommendation:
Improve product descriptions and order confirmation steps.

For segments with higher return rates, offer live chat support or pre-shipping confirmations.

### Result

<img width="445" alt="sq 10" src="https://github.com/user-attachments/assets/d4cb98f7-c0bd-4af2-8835-78c359896650" />


## QUESTION 11:
<img width="413" alt="sq 11" src="https://github.com/user-attachments/assets/06fb6877-3574-49ba-ac37-35708387446d" />

 
  ### Key Insight
There are several mismatches where low-priority orders used expensive Express Air, and critical orders were shipped with slow Delivery Truck.

This indicates:

Lack of a rule-based shipping selection process

Potential customer dissatisfaction for late critical orders

Unnecessary costs incurred on low-priority deliveries

### Operational Impact
Overuse of Express Air raises logistics costs without boosting revenue or satisfaction.

Using Delivery Truck for urgent items risks losing high-value clients due to late delivery.

Inconsistency suggests there’s no automated shipping logic in place.

###  Recommendation
Set Automated Shipping Rules

Express Air → only for Critical or High priority orders

Delivery Truck → only for Medium or Low priority

Monitor Monthly Shipping Reports
Flag mismatches between order priority and shipping mode.

Train Sales & Logistics Teams
Ensure they understand the cost vs priority implications.

Customer Communication
Let customers choose speed vs cost when placing orders.

### Summary 
No, the company did not always spend shipping costs appropriately based on order priority. There's evidence of inefficiency and misalignment that can be corrected through automated policies and better oversight.
