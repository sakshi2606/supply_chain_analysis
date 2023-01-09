# Supply Chain Analysis
## Problem Statement

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.
AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service.

Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ‘On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.
The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

The aim is to create a dashboard to show some important key metrics and come to a reason about why the key customers have not renewed the contracts.

## Data Model

![Supply Chain Data Model](https://user-images.githubusercontent.com/66999147/211290263-87803c27-6927-4e97-aaf6-b7392ec837b9.png)

## Dashboard 

![Supply _Chain_Dashboard](https://user-images.githubusercontent.com/66999147/211292752-d5b81e79-c287-43e5-abe2-250214f83403.jpg)

- The colors added in customer analysis part is using conditional formatting based on the gap between goal and target value of the respective metric.
- ADDD used is the Average Delayed Delivery Date.

## Key Insights
-	All the key metrics On-Time (OT), In-Full(IF), OnTime-InFull (OTIF) are far behind than the target.
-	Lotus Mart, Acclaimed Stores, Vijay Store, Rel Fresh and Propel Mart are the top 5 customers with highest number of orders and are the key customers.
-	Dairy Products are the most ordered products (around 60%) compared to Food and other Beverages.
-	Orders getting delivered late are delivered 1.69 days late on an average.
-	Butter, Ghee, Milk are the most delayed to delivery products
-	There is a huge difference in In-Full (IF %) and Target. This has to be addressed. It might be because of higher number of orders than expected or low production of the products.

