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
