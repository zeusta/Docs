# INSTOCK MANAGEMENT - MAGENTO 2


*Confidential Information Notice*<br/>
*Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

------

## INTRODUCTION

If you are looking for a simple solution to manage a warehouse and all stocks within, this Magento inventory management module is exactly what you need: Reduce time wasted on actually visiting your warehouses, now you can view and adjust all information of stock on-hand on your computer; Minimize mistakes in manual counting with step-by-step Stock Taking; Save more cost with accurate Supply Need Forecast and automatic Low Stock Alert. It's time to spend less time on stock management & more time on selling them.

------

## HOW IT WORKS

### Stock listing

#### Stock in Warehouse

Admin can have overview of Stock in all Warehouses and select a warehouse to view stocks of that warehouse only.

It can show Available Qty, Qty to Ship and total Qty in each warehouse and Shelf Location of that product in the warehouse.

After selecting the warehouse, admin can easily update stock and shelf location right on the Inventory grid just by selecting the products, fill the updated Total Qty/Shelf location and click “Update Stock”.

![](./instockimages/instock_1.jpg)

Moreover, you can easily edit Qty of products in-line within a few steps:

![](./instockimages/instock_2.png)

1) Selectthe Products
2) Edit product quantity in line
3) Input product location in the physical warehouse
4) Click on **Update Stock** to save changes

#### Non-warehouse product

When a product is newly created and not assigned to any warehouse yet, it will be automatically allocated in Non-warehouse. From here admin can select the product and add it into warehouse.

![](./instockimages/im7.png)

#### Warehouse

After installation, the system will automatically provide a **Primary Warehouse**. This warehouse cannot be deleted and can only be edited. All the existing products with stocks level of your website will be automatically allocated in this warehouse.

The *Warehouse* menu allows you to control your warehouse with 5 tabs:

![](./instockimages/instock_3.png)

* **General Information**: contains basic information of the warehouse including Total SKU, total Qty, contact email, telephone, street, city, country and status
* **Stock On-hand**: view all products and quantity of each product in the warehouse
* **Stock Movement**: records stock changes
* **Warehouse Permission**: view roles & assigned staff of the warehouse
* **Dashboard**: summarises stock status in various ways as below:

![](./instockimages/instock_4.png)
![](./instockimages/instock_5.png)

### Stock Control

#### Stock Adjustment & Stock Adjustment History

**-	Link stocks in Warehouse to Front Store View:**

With the newest version, you can link products and stock data by choosing “Yes” on the **Link stocks in Warehouse to Front Store View** section

![](./instockimages/im11.png)

To link multiple Store View to a Warehouse, go to **Inventory Management > Warehouse > select a specific warehouse**. Here, you can change the store view that links to the warehouse or select multiple store views as needed.

![](./instockimages/im12.png)

**-	Add new Stock Adjustment**

Under menu “Stock Control”, you can create new Stock Adjustment for a specific warehouse chosen from Drop down list. Fill the reason, then **Start Adjust Stock**.

From here you now go to Product List to **Add products to adjust stocks** or **Import products**, fill in the Qty you want to update and Save the Stock Adjustment. The Qty here can be “Change Qty” or “Adjusted Qty”, depending on how you configure in Store   Configuration: 

![](./instockimages/im13.png)

If you fill the Change Qty, you are allowed to add or subtract the change by filling positive or negative number. If you fill in Adjusted Qty, you will fill the final calculation to update the final qty. After being saved, this stock adjustment’s status is now **Pending**.

![](./instockimages/im14.png)

To change Stock Adjustment status to “completed”, you need to hit button “Adjust Stock”. Stock is updated in the warehouse. Once the Adjustment is Complete, there is no way to edit it.

![](./instockimages/im15.png)

Stock level will be updated instantly in the corresponding warehouse.

**-	View Stock Adjustment History**

You can view all Stock Adjustment History under Stock Control -> Stock Adjustment History with information including Time created, staff created, warehouse and status…Click to each Adjustment, you can see stock adjustment details

![](./instockimages/im16.png)

#### Stock Taking & Stock Taking History

Physical Stocktaking acts can be used at any time to double-check and correct inventory discrepancy amounts in Inventory Management vs. physical inventory in your warehouses. These consist of:

-	A count, in which warehouse staff records the actual number of products in stock at the time of inspection & a manager can rely on it to update inventory in the system later

-	Then a confirmation of that count performed by a warehouse manager to officially update the correct number of products in stock (Adjust Stock)

There are 5 steps in Stock taking using Inventory Management:

1.	**Fill General information:** After finishing this step, Stock taking status is **Pending**

2.	**Prepare products before doing stock take:** Select or import products to prepare before doing stock take. Stock taking status will change to **Processing**

3.	**Do Stock take:** Fill in the Qty of product. Now status is changed to **Verified**

4.	**Complete data entry:** Save the data that has been stock taken and waiting for admin’s approval.

5.	**Complete Stock take:** When admin does this, Stock taking status will be changed to Complete. Qty is adjusted in the warehouse. Similar to Adjust Stock, stock taking cannot be edited after status is Complete.
After doing stock take, admin can easily view and export the difference between real stock in the warehouse and the stock level updated by the system

Or you can directly adjust stock by choosing **New Stock Adjustment** on Stock Control, then fill 3 basic information about **Warehouse, Adjustment Code** and **Reason**.

![](./instockimages/imnew1.png)
![](./instockimages/imnew2.png)

#### Stock Movement

The module records all the movements of stocks in warehouse. These movements are reflected in Stock Movement report under Stock Control submenu.

The table shows SKU of the products added or subtracted from warehouse, the changed Qty, Warehouse name, Date and Reference number to see the details on a click. Admin can easily exports Stock Movement details into CSV or Excel XML.

![](./instockimages/im17.png)

Admin can also filter the data basing on the variables in the table

![](./instockimages/im18.png)

### Prediction

#### Supply Needs

This feature predicts how many inventory items a warehouse need for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past. The **Forecast Supply Needs** feature will be automatically shown on the section **Supply Needs** your supply needs is zero. Or else, you can click on **Show Supply Needs** button. Admin can select Base On Sales to use to calculate data for supply need, fill in **Forecast Supply Needs** to the date that you want to get supply needs then it will give a product list with following information:

- Qty Sold/day: average Qty of product sold per day 

- Total Sold: total qty of product that were sold in Base On Sales 

- Current Qty

- Availability date 

- Supply needs

The Supply Need Forecast can be exported to CSV or XML file and printed into PDF file.

#### Low Stock Notifications

Low Stock notifications listing displays warning messages about the products which are nearly out of stock in warehouses. It shows all notification with information including Sent at, Update Type, Email received, Recipients and Action. Each notification log can show details of all products that have been low stock including Name, SKU, Image, Qty Notified and Time Notified.

#### Low Stock Rules

Admin can create unlimited rules to notify low stock. One rule contains: Rule information, Condition and Action.

-	**Rule information:** You can fill in Rule name, description, status, validation date, time that you want to get notification.

-	**Condition:** There are 2 rule types for you to select: Available Days and Available Qty.

With Available Days selection, the system will base on sales history of an item to predict how many days left till it will be out of stock. You can configure Sales period (history time to base on and get sale data) and Threshold day (the days before the product runs out of stock). So if you configure Threshold day as 5, system will send notification to you 5 days before this item is predicted to be out of stock so that you can prepare to purchase more stocks.

![](./instockimages/im9.png)

Besides, you can add more conditions about Product attribute for example product SKU, color, category…

-	**Action:** You can fill in the emails that you want to send the low stock notification to and warning message.



