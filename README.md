# ecommerce-olist-analysis

What is the business?

Olist is an e-commerce marketplace connecting customers and sellers, relying on timely delivery and customer satisfaction.

What’s the pain?

Revenue depends on repeat purchases and good reviews; delays and poor experience reduce ratings and future sales.

What do we want to achieve?

Identify drivers of revenue and low ratings, and recommend actions to improve delivery performance and customer satisfaction.

## project Scope
-Revenue & orders trends
-Category performance
-Region performance
-delivery delays & on-time rate
-Reviews and satisfaction drivers
-Repeat customers
-Payment types

## out of Scope
-Profit margins
-Marketing spend / adds ROI
-Inventory analysis

## Business Definations & KPIs

### Sales Metrics

#### Total Revenue
The total monetary value of all products sold.
Formula:
Total Revenue= SUM(order_items.price)
(Note: Shipping fee is excluded  to avoid logistics distortion)

#### Total Orders
Number of unique completed orders.
Formula:
Total Orders =COUNT(DISTINCT order_id)

#### Average Order Value(AOV)
Average amount spent per order.
Formula:
AOV= Total Revenue?Total Orders

#### Montly Revenue Growth (%)
Percentage change in revenue compared to previous month.
Formula:
(Revenue_This_month-Revenue_last_month)/Revenue_last_month

### Operations Metrics

#### Delivery Time (Days)
Time taken from order purchase to customer delivery.
Formula:
Delivery Date − Purchase Date

#### Delivery Delay (Days)

Difference between actual and estimated delivery.
Formula:
Delivery Date − Estimated Delivery Date

#### On-Time Delivery Rate

Percentage of orders delivered on or before the estimated date.
Formula:
Orders where Delivered ≤ Estimated / Total Orders

### ⭐ Customer Experience Metrics

#### Average Review Score

Mean rating given by customers.
Formula:
AVG(review_score)

#### Low Rating Rate

Percentage of reviews that indicate dissatisfaction.
Formula:
Reviews with score ≤ 2 / Total Reviews

#### Repeat Customer Rate

Proportion of customers who placed more than one order.
Formula:
Customers with >1 order / Total Customers
