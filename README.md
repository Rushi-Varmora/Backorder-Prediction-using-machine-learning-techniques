# Backorder-Prediction-using-machine-learning-techniques


What Is a Backorder?
•	A backorder is an order for goods or services that cannot be fulfilled at the current time due to a lack of availability. The item may not be held in the company's available inventory but could still be in production, or the company may need to continue manufacturing more of the product.
•	A backorder indicates that demand for a company's product outweighs its supply. They may also be known as the company's backlog. Also, companies cannot overstock every product in their inventory to avoid such a situation, as it will add an extra cost to companies.

# Problems with Backorders
•	If a company's operations are regularly seeing products on backorder, it could be interpreted as a symptom that its operations are far too lean. It may also mean the company is losing out on business by not providing the products demanded by its customers. If a consumer notices that a product is backordered on a regular basis, they may opt to cancel their orders, causing the company to give refunds and suffer bad marketing.

# Data Description
•	There must be a way for the company to know for which products they may face a backorder problem. So, the company has shared a data file with different input features for each product, and it hopes to find a pattern inside this data that can give them some insight.
 

The dataset contains 23 columns including 22 features and one target column.
To model and predict the target, we’ll use the features columns, which are:


The dataset contains 23 columns where 22 cloumns contains features and one target column.

To model and predict the target, we’ll use the features columns, which are:

sku – Random ID for the product

national_inv – Current inventory level for the part

lead_time – Transit time for product (if available)

in_transit_qty – Amount of product in transit from source

forecast_3_month – Forecast sales for the next 3 months

forecast_6_month – Forecast sales for the next 6 months

forecast_9_month – Forecast sales for the next 9 months

sales_1_month – Sales quantity for the prior 1 month time period

sales_3_month– Sales quantity for the prior 3 month time period

sales_6_month – Sales quantity for the prior 6 month time period

sales_9_month – Sales quantity for the prior 9 month time period

min_bank – Minimum recommend amount to stock

potential_issue – Source issue for part identified

pieces_past_due – Parts overdue from source

perf_6_month_avg – Source performance for prior 6 month period

perf_12_month_avg – Source performance for prior 12 month period

local_bo_qty – Amount of stock orders overdue

deck_risk – Part risk flag

oe_constraint – Part risk flag

ppap_risk – Part risk flag

stop_auto_buy – Part risk flag

rev_stop – Part risk flag

went_on_backorder – Product actually went on backorder. This is the target value.
