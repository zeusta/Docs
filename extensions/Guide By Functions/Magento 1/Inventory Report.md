# INVENTORY REPORT - MAGENTO 1

**Version 1.0**

Confidential Information Notice

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

----------------------
## Introduction


Magestore Inventory Report module for Magento provides you with a detailed overview of your sales, stock, warehouse, suppliers. You get access to 11 types of report which are divided into 2 categories of **Sales** and **Inventory report**. They help you easily keep track your inventory system as well as your business performance.

**Note**: Magestore Inventory Management module is required to make Inventory Report module work properly.

To view Sales and Inventory report, you go to tab **Retailer Report**, then choose **Manage Report**. All 11 types of report can be exported as CSV file.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image004.jpg)

-----------------------------
## Sales Reports

Sales Reports are shown with 6 types of report including: Product report, Warehouse report, Shipping method report, Payment method report, Order Status and Customer report.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image006.jpg)


Then click to open the report you want to show. To run report with real-time statistics, you need to pay attention to these 3 factors:

-	**Factor 1: Real-time statistics**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image008.jpg)


If you do not set Auto update for sales report (read 4. Settings), you need to refresh the latest data when running report. On the left side of each sales report, there is a notice about the last update and the latest statistics, click **Here** to refresh data.

-	**Factor 2: Time period**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image010.jpg)

You have different options for your tracking period. You can use custom range to set the specific time you want to view report. Then click on **Apply**.

-	**Factor 3: Warehouse(s)**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image012.jpg)

Choose one or all the warehouses then click on Show Report to run the report.

### Product Report

The Product report helps Magento store owners answer these all questions:

-	Which product is the best-seller today/ yesterday/ last week/ last month?

-	Which products is generating the largest benefit?

-	View orders' information (ID, status, Actual Sold Quantity, Potential Sold Quantity, discount, tax, profit, Cost of Goods Sold, total sales).

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image014.jpg)


When viewing each product SKU, you see orders’ details of that product SKU.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image016.jpg)

**Main metrics:**

-	Actual Sold Quantity: Quantity of products transferred to customers (the products that have been shipped).

-	Potential Sold Quantity: Quantity of products sold to customers (the products that haven't been shipped).

-	Cost of Goods Sold: The direct costs attributable to the production of the goods sold

-	Tax: Total tax of the whole products

-	Total Sales: The total value of actual and potential sold quantity.

-	Profit: The total value of actual and potential profit.


**Note:** Go to part 5. List of inventory metrics to better understand the meaning & calculating format of each metrics.

**Secondary metrics:**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image018.jpg)


Click on **Select Columns** to add more metrics to your product report.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image020.jpg)


For example, when you tick on Payment Method, the product report additionally shows the payment information.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image022.jpg)

You can add more dimension and metrics to get more details from the report. The secondary metrics is available for all 6 types of Sales report.

### Warehouse Report

This report answers these questions:

-	Which is my top warehouse/ sales location?

-	Which warehouse sells more products? Create more sales

-	View data of each warehouse (order ID, status, actual sold quantity, potential sold quantity, discount, tax, profit, cost of goods sold, sales)

Similar to Product report, you can use secondary dimensions/ metrics to get more details.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image024.jpg)

**Main metrics:** Actual sold quantity; potential sold quantity; cost of goods sold; tax; total sales; profit.

### Shipping method Report

This report provides a breakdown of your sales value by shipping method within a given period. It helps you answer the question: What is the most common shipping method that customers use? It also allows you to view details of each shipping methods.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image026.jpg)

Click on **View** to see order list of each shipping methods.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image028.jpg)

**Main metrics:** Shipping method; Actual sold quantity; Potential sold quantity; Cost of goods sold; Tax; Total sales; Profit.


### Payment method Report

This report shows you which the most used payment methods is and the details of each payment methods (order ID, order status, etc.)

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image030.jpg)

Click on **View** to see list of order using each payment methods in details.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image032.jpg)

**Main metrics:** Payment method; Actual sold quantity; Potential sold quantity; Cost of goods sold; Tax; Total Sales; Profit.

### Order status

Store owner can view the structure of orders by status and view details of each status (Order ID, sold quantity,...) with the Order status report.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image034.jpg)

**Main metrics:** Order status; Actual sold quantity; Potential sold quantity; Cost of goods sold; Tax; Total sales; Profit.

### Customer

The Customer report shows you your loyal customers and allows to view details of each customers (orders' ID, status, etc.).

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image036.jpg)

**Main metrics:** Customer; Customer group; Actual sold quantity; Potential sold quantity; Cost of goods sold; Tax; Total sales; Profit.

------------------------------
## Inventory Report


To access Inventory Report, you go to tab **Manage Report**, there are 5 types of reports displayed. Click to view the report you want to access.
![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image038.jpg)

**Note:** You need to choose the warehouse (one or all warehouses) before running report.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image040.jpg)

### Value of Stock-on-hand

This report identifies the value of stock-on-hand of each warehouse or the whole system. You will get an overview of your inventory (Manage the total quantity, the inventory value, retail value, & profit value, etc.)

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image042.jpg)

You can choose to remove fields from report. Click on **Select Columns** then untick the fields that you don’t want to show on the report.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image044.jpg)

**Main metrics:**

-	Qty in Warehouse: the real quantity of a product in warehouse.

-	MAC (Moving Average Cost): A moving average (unit) cost is an inventory costing method wherein after each goods acquisition, the average unit cost of the item is recomputed. This helps properly count the product quantity & compute the new selling price.

-	Selling price: The price at which product is currently sold. It does not include tax, discount, etc.

-	Inventory value: The total value of product in warehouse (Quantity in Warehouse x MAC)

-	Potential revenue: The total selling value (Quantity in Warehouse x Selling price)

-	Potential profit: Potential revenue minus inventory value.

-	Profit margin: Potential profit in percentage.

**Note:** Go to part 5. List of inventory metrics to better understand the meaning & calculating format of each metrics.


### Stock Quantity

The Stock Quantity report provides store owners details of each product quantities (quantity in warehouse, quantity to ship, quantity on purchase order, etc.) It helps you answer these questions: Which products are available to be kept selling? Which products need supply?

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image046.jpg)

**Main metrics:** Quantity in warehouse; Supplier; Quantity to ship; Available quantity; Quantity on purchase order; Shelf location.

### Compare by warehouse

This report allows you to compare stock metrics in multiple locations by each product. You need to choose the warehouse and the metric that you want to compare, then click on **Show report.**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image048.jpg)

The report will be displayed as below:

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image050.jpg)

**Main metrics to compare:** Available quantity; Quantity to ship; Quantity in warehouse; Incoming stock; Inventory value; Retail value; Profit value; Profit margin.

### Incoming Stock

This report provides store owners details of incoming stock by each product SKU.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image052.jpg)

**Main metrics:** Supplier; Purchase Order; Quantity in warehouse; Incoming stock; Overdue incoming stock; Total cost of incoming stock.


### History

You can view inventory statistics of each warehouse by day and keep the reports in a specific period of time (last 7 days, last 30 days or last 3 months as you set up in Settings). The inventory operating activities are recorded to daily generate a report which you can download as a CSV file.

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image054.jpg)

----------------
## Settings


In Magento backend, you go to tab **Retail Report**, then choose **Settings** to configure settings of Inventory Report module.

-	**Sales Report Configuration**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image056.jpg)
      - Use cron to auto update: Choose **Yes** if you want to auto update data from Magento to Sales Report every minute. Otherwise, you need to go to **System >Index Management > Report Success** to generate and view report manually.

**Note:** It takes time when you synchronize data from Magento to Inventory Report the first time.

-	**Inventory Report History Configuration**

![Magento Inventory Report](https://github.com/Magestore/Docs/blob/master/extensions/Guide%20By%20Functions/Magento%201/Image_Inventory%20Report/image058.jpg)
      -    Duration: The period in which your Inventory reports are recorded (last 7 days, last 30 days, last 3 months). To store the report, you should download it in zip file before the period times out as the report is deleted.
      -	Use Cron to auto update: Choose **Yes** if you want to auto update data from Magento to Inventory Report History every minute. Otherwise, you need to go to **System > Index Management > Report Success** to generate and view report manually.
      -	Auto Update Time: Set a specific time when the history report is auto generated.

------------------
## List of inventory metrics


No.|	Metrics |		Sign|	Equation|	Explain|
---|---|---|---|---|
**O. Metric Units**|				
1|	Actual Sold	|actual_sold_qty|	min (qty_shipped, (qty_ordered -qty_canceled -qty_refunded)) |Quantity of products transferred to customers (shipped orders).|
2 |	Potential Sold Quantity |potential_sold_qty	Max (0, qty_ordered -qty_shipped -qty_canceled -qty_refunded)| Quantity of products sold to customers (unshipped orders)|
3|	Purchase cost calculated by average MAC value| unit_cost | Get data from field **base_cost** in the table **order_item** (from Magento backend) |
4|	Average price per unit product	|unit price|	base price	|
5|	Tax of a product unit	|	unit_tax |	base_price x tax_percent|	
6|	Discount value discount_percent	|	unit_discount|	base_price x discount_percent	|
7|	Profit value of a discount_percent|		unit_profit	| base_price - unit_cost -unit_tax - unit_discount|
**I. Sales Report**	|			
1|	Cost of goods sold|		COGS|	actual_cogs + potential_cogs |	COGS = cost of purchase x quantity of sold items|
2| Actual cost of goods sold |	actual_cogs |	unit_cost x actual_sold_qty | Actual discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are not invoiced yet.|
3 |	Potential Cost of goods sold|	potential_cogs|	unit_cost x potential_sold_qty| Potential discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are not invoiced yet.|
4|	Purchasing cost calculated by the MAC (Moving average cost)|unit_cost| total cost after Purchase Order / total Qty after Purchase Order|Cost of purchase is calculated in average cost method. MAC = total cost / quantity that have been transferred into warehouse (based on the current purchase order status)|
5|	Profit|	Profit|	actual_profit + potential_profit |	Profit = total revenue -total COGS
6|	Actual Profit|	actual_profit|	unit_profit x actual_sold_qty| Actual discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are already Invoiced|
7|	Potential Profit|	potential_profit|	unit profit x potential_sold_qty | Projected discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are not invoiced yet|
8|	Tax|	Tax	|actual_tax + potential_tax|	Tax of an item on order
9|	Actual Tax|	actual_tax|	unit_tax x actual_sold_qty|	Actual discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are already invoiced|
10|	Potential Tax|	potential_tax|unit_tax x potential_sold_qty |	Potential discount value (based on the product's current order status) is shown in row_invoiced. This value is calculatedfor items that are not invoiced yet|
11|	Discount|	Discount|	actual_discount + potential_discount|Discount value of an item on an order
12|	Actual Discount| actual_discount | unit_discount x actual_sold_qty|Actual discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are already invoiced
13|	Potential Discount |potential_disco unit| unit_discount x potential_sold_qty |Potential discount value (based on the product's current order status) is shown in row_invoiced. This value is calculated for items that are not invoiced ye
14|	Total sales|	Total sales|	COGS + Profit|Total sales = total COGS + total profit = (actualCOGS + potential COGS) + (actual profit + potential profit)
**II. Inventory report**|			
1|Moving Average Cost| MAC = unit_cost | total cost after Purchase Order / total Qty after Purchase Order / total Qty after Purchase Order| A = COGS of current unsold products (exclusive incoming stock in this Purchase Order) If COGS = 0, A = current cost on Purchase OrderB = total cost of products on the new Purchase Order (= cost x quantity of products on Purchase Order) MAC = A + B / (total product quantity of A & B)|
2|	Inventory Value|Inventory Value|MAC x Qty|Total potential costs of unsold products
3|	Selling Price|	Selling Price|	Product Price|	Product price which is set in Magento core (exclusive tax and discount)
4|	Potential Revenue| Potential Revenue| price x Qty| Total price of unsold products (the estimate - the actual amount depends on actual sales)
5|	Potential Profit	|	Potential Profit|	Potential Revenue - Inv Value = (price x Qty) -(MAC x Qty)| Total potential profit ofunsold products
6|	Profit margin	|	Profit margin| 	Potential Profit / Potential Revenue x 100 / Potential Profit of unsold products in percentage
7|	On Purchase Order (Incoming Stock)|Incoming Stock | qty_ordered - qty_refund - qty_tranfer|  The quantity of stock in pending/ processing Purchase Orders (i.e. excluding completed and canceled POs) that have not been transferred into warehouse.  **Note:** this value is the same in reports in all warehouses, since these stocks have not been assigned to any warehouse yet
8| Overdue Incoming Stock| Overdue Incoming Stock|qty_ordered - qty_refund - qty_tranfer|Quantity of stock in overdue Purchase Orders that have not been transferred to warehouse (the current date has passed the expected due date on Purchase Order)
9|	Total cost of incoming stock| Total cost of incoming stock| (qty_ordered - qty_refund - qty_tranfer) x cost| Total cost


		
				



