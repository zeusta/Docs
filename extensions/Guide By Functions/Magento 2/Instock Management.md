# INSTOCK MANAGEMENT - MAGENTO 2


*Confidential Information Notice*<br/>
*Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

------

## INTRODUCTION

If you are looking for a simple solution to manage a warehouse and all stocks within, this Magento inventory management module is exactly what you need: Reduce time wasted on actually visiting your warehouses, now you can view and adjust all information of stock on-hand on your computer; Minimize mistakes in manual counting with step-by-step Stock Taking; Save more cost with accurate Supply Need Forecast and automatic Low Stock Alert. It's time to spend less time on stock management & more time on selling them.

------

## HOW TO CONFIGURE
### Stock Control Configuration

- *Path*: **Stock Management > Settings** section > **Configuration** 

![](./instockimages/anh%201.png?raw=true)

(1)	**Link stocks in Warehouse to Front Store View:** choose **Yes** to activate the visibility of Stocks in Warehouse on the Front Store View

(2)	**Adjust Stock by entering the change Qty:** 

-  If you choose **Yes**, when you enter the difference quantity (either a positive or negative figure), the system will calculate the final balance in warehouse by adding/ subtracting the entered value.
- 	If you choose **No**, you need to enter the exact quantity of stock in warehouse and the system will recognize this figure as the latest available quantity of product.

(3)	Click **Save Config** to finish

## HOW TO USE

### Stock listing

#### Stock in Warehouse

*Path:* **Stock Management > Stock Listing** section **> Stocks in Warehouse**

Admin can have overview of Stock in the Warehouse and view stock details within the warehouse.
These details include **Available Qty, Qty to Ship** and **Total Qty** and **Shelf Location** of each product in the warehouse.


![](./instockimages/anh%202.png?raw=true)

You can easily edit Qty of products in-line within a few steps:

1) Mark the checkbox to select products
2) Edit product quantity in line
3) Input product location in the physical warehouse
4) Click on **Update Stock** to save changes

#### Non-warehouse product

When a product is newly created and not assigned to any warehouse yet, it will be automatically allocated in Non-warehouse. 

![](./instockimages/anh%203.png?raw=true)

From here admin can 

(1) Select the product b y clicking on the checkbox

(2) Add it into warehouse by clicking on its Add to Warehouse column

#### Warehouse

After installation, the system will automatically provide a **Primary Warehouse**. This warehouse cannot be deleted and can only be edited. All the existing products with stocks level of your website will be automatically allocated in this warehouse.

##### View Warehouse's detail information

The **Warehouse** menu allows you to control your warehouse with 6 tabs:

![](./instockimages/anh%204.png?raw=true)

On the right side of each master data tab, click on the **Arrow button** to access the data:

(1) **General Information** about the Warehouse

(2) **Stock On-hand** displays the amount of goods that the warehouse has available at that time.
Here, you can update each product's **Qty in Warehouse(s)** and its **Shelf Location** in-line.

(3) **Stock Movement** shows the changes in stock quantities. Click on each record to view more details.

(4) **Order** record detail information of each order incuding status, order ID, purchase date, customer that the order has been billed-to/shipped-to, order value.

(5) **Warehouse Permission** manages staff access to the warehouse. Detailed guide is given in the next section ***Warehouse permissions***  

(6) **Dashboard** contains reports that are illustrated as table and lines diagrams as below.

![](./instockimages/anh%205.png?raw=true)
![](./instockimages/anh%206.png?raw=true)

##### Warehouse Permissions

- *Path:* **Stock Management > Stock Listing** section **> Warehouse > Warehouse Permissions**

In this section, Admin can give different warehouse access permissions to different (admin) users.
Click on **View** to see the warehouse’s detail information

![](./instockimages/anh%207.png?raw=true)

(1) On the right hand side of the  **Warehouse Permission** tab, click on **Assign Staff** to give different warehouse access permissions.

Then will be a new pop-up screen shown as below:

 ![](./instockimages/anh%208.png?raw=true)

Select Staff users to assign permission

1) Select Staff by marking the checkbox

2) Click on **Filters** to search Staff information (if any)

3) Click on **Add Selected Staff**

 ![](./instockimages/anh%209.png?raw=true)

4) Then click on **Save Staff Permissions**


### Stock Control

#### Stock Adjustment & Stock Adjustment History

**-	Link stocks in Warehouse to Front Store View:**

As mentioned in section **Stock Control Configuration**, you can link products and stock data by choosing **Yes** on the **Link stocks in Warehouse to Front Store View** section

![](./instockimages/anh%210.png?raw=true)

To link multiple Store View to a Warehouse, go to **Inventory Management > Warehouse > General Information > Magento Store View**. Here, you can change the store view that links to the warehouse or select multiple store views as needed.

![](./instockimages/anh%211.png?raw=true)

**-	Add new Stock Adjustment**

- *Path:* **Stock Management > Stock Control** section **> New Stock Adjustment**

 ![](./instockimages/anh%212.png?raw=true)

Under menu **Stock Control**, you can create new Stock Adjustment in a few steps:

(1)	Name of the warehouse. With the Starter Package, you can only choose Primary Warehouse (also set as default) 

(2)	Adjustment code is automatically generated. All adjustments are saved in **Stock Management > Stock Control** section **> Adjust Stock History**

(3)	Fill the reason

(4)	Then click button **Start Adjust Stock**

![](./instockimages/anh%213.png?raw=true)

From here you have 2 options:

(1)	Go to product list and **Add products to adjust stocks** or **Import products** via CSV file

(2)	**Save** the Stock Adjustment. After being saved, this stock adjustment’s status is now **Pending**. To change Stock Adjustment status to **Completed**, you need to hit button **Adjust**.

*Note that the Qty here can be “Change Qty” or “Adjusted Qty”, depending on how you configure in Store Configuration (please refer to section **Stock Control Configuration***

Stock is updated in the warehouse. Once the Adjustment is Complete, there is no way to edit it.

![](./instockimages/anh%214.png?raw=true)

Stock level will be updated instantly in the corresponding warehouse.

**-	View Stock Adjustment History**

- *Path:* **Stock Management > Stock Control** section **> Stock Adjustment History**

![](./instockimages/anh%215.png?raw=true)

You can view all records of Stock Adjustments in this page with information including Time created, staff created, warehouse and status… Click on each Adjustment, you can see stock adjustment details.

If you click on a **Completed** adjustment, you will be able to export the product list of that specific adjustment by clicking the button **Export Products**.

![](./instockimages/anh%216.png?raw=true)

#### Stock Taking & Stock Taking History

Physical Stocktaking acts can be used at any time to double-check and correct inventory discrepancy amounts in Inventory Management vs. physical inventory in your warehouses. These consist of:

-	A count, in which warehouse staff records the actual number of products in stock at the time of inspection & a manager can rely on it to update inventory in the system later

-	Then a confirmation of that count performed by a warehouse manager to officially update the correct number of products in stock (Adjust Stock)

##### Stocktaking process

- *Path:* **Stock Management > Stock Control** section **> New Stocktaking**

 ![](./instockimages/anh%217.png?raw=true)

There are 5 steps in Stock taking using Instock Management module:

- **Step 1: Fill General information:** After finishing this step, Stock taking status is **Pending**

![](./instockimages/anh%218.png?raw=true)

(1)	Fill in the reason for stocktaking. You can also fill in the participants and the time of the action but it is optional

(2)	Choose the products to be stock taken by clicking the **Prepare Product List** button (Stage 2) at the top right of the page. Alternatively, you can skip it to go straight to Stage 3 by clicking the **Start Stocktaking** button


- **Step 2: Prepare products before doing stock take:** Select or import products to prepare before doing stock take. Stock taking status will change to **Processing**

![](./instockimages/anh%219.png?raw=true)

(1)	Click on **Add Products to Stocktake** to select products from your product list or **Import products** from CSV file (template provided)

(2)	Selected products will be displayed in the grid here

(3)	Click **Save** to stay with your selected products for further edits, or click **Start Stocktake** to proceed Stage 3.

- **Step 3: Do Stock take:** Fill in the Qty of product. Now status is changed to **Verified**

 ![](./instockimages/anh%220.png?raw=true)

(1)	Enter the product quantity that you have recently counted and the reason why there is quantity difference.

(2)	Either click **Complete Data Entry** to proceed to Stage 4 and have a review of the changes; click **Complete Stocktake** to finish the process; or **Save** to continue editing.

- **Step 4:	Complete data entry:** Save the data that has been stock taken and waiting for admin’s approval.

 ![](./instockimages/anh%221.png?raw=true)

This Stage allows you to have a final review of your recent quantity counts. Click either **Re-entry Data** to edit the quantity or **Complete Stocktaking** to move to Stage 5. If you are not an admin, your counting results will be submitted to the admin/ manager for approval before the new quantity is officially updated and the process is marked **Completed**.

- **Step 5:	Complete Stock take:** When admin does this, Stock taking status will be changed to **Complete**.

 ![](./instockimages/anh%222.png?raw=true)

Qty is adjusted in the warehouse. Similar to Adjust Stock, stock taking cannot be edited after status is Complete.
After doing stock take, admin can easily view and export the difference between real stock in the warehouse and the stock level updated by the system

##### Stocktaking History

- *Path:* **Stock Management > Stock Control** section **> Stocktaking History**

 ![](./instockimages/anh%223.png?raw=true)

(1)	All Stocktaking details are listed here. Click on each record to view all details of the process. Different status shows to which stage the stocktaking process is done:

- Status **Pending** means Stage 1: **General Information** is done
- Status **Processing** means Stage 2: **Prepare Products** is done
- Status **Verified** means Stage 3: **Stock Counting** is done
- Status **Completed** means the whole stocktaking process is done

(2)	You can also click on **Add Stocktaking** button to start a new stocktaking process from here.


#### Stock Movement

- *Path:* **Stock Management > Stock Control** section **> Stock Movement History**

The module records all the movements of stocks in warehouse. These movements are reflected in **Stock Movement** report under **Stock Control** submenu.

![](./instockimages/anh%224.png?raw=true)

(1)	The table shows SKU of the products added or subtracted from warehouse, the changed Qty, Warehouse name, Date and Reference number to see the details on a click. 

(2)	Admin can filter the data basing on the variables in the table.

(3)	Admin can also easily exports Stock Movement details into CSV or Excel XML.

### Prediction

#### Supply Needs
This feature predicts how many inventory items your warehouse needs for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past. 

![](./instockimages/anh%225.png?raw=true) 

(1)	To process a prediction, select the warehouse (in Instock Management module, you can only select 01 warehouse i.e. Primary Warehouse) 

(2)	Time range to collect sales data, based on which the system will calculate data for supply need

(3)	Pick the date that you want to see forecast results.

(4)	Click to **Show Supply Needs** button to finally view the prediction.

The forecast data will be shown in the table as below:

![](./instockimages/anh%226.png?raw=true) 

(1)	The table displays supply needs information as below:

- Qty Sold/day: average quantity sold per day of the product during the chosen sales period 
- Total Sold: total quantity of product that were sold during the chosen sales period
- Current Qty: the product quantity that you currently have in the warehouse
- Availability date: the system predicts your stock is enough to be sold until this date. After this date, your product is estimated to run out of stock.
- Supply needs: the quantity of product that expected to be sold until the time stamp you set. 

(2)	The Supply Need Forecast can be exported to CSV or XML file by hitting **Export** button.

(3)	You can start another prediction by expanding and editting criteria for supply forecast and hit **Show Supply Needs** again to refresh the prediction result. 


#### Low Stock Rules

- *Path:* **Stock Management > Prediction** section **> Low Stock Rules**

***Note: Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.*

![](./instockimages/anh%227.png?raw=true) 

(1)	Select an existing rule to edit or click **Add New Rule** button at top right of the page. Admin can create unlimited rules to notify low stock status. One rule contains: **Rule Information, Conditions & Action**. There is no limitation in the quantity of rules set.

-	**On the Rule information tab:** 

 ![](./instockimages/anh%228.png?raw=true)

(2)	Enter the low stock rule name

(3)	Add a brief about the rule *(optional)*

(4)	Select **Active** to enable the rule

(5)	Use **Calendar** to choose **From** and **To** date for a term of validity *(optional)*

![](./instockimages/anh%229.png?raw=true) 

(6)	Select an **update time**:

- Daily
- Monthly

The system periodically check stock availability and automatically send email notifications admin and warehouse managers. 

(7)	**Select hours** the warning message will be sent


-	**On the Conditions tab:** 

 ![](./instockimages/anh%230.png?raw=true)

There are **2 types** of low stock rule:

 ![](./instockimages/anh%231.png?raw=true)

***Type 1: Availability Qty**.
**Availability Qty.**: you can select Qty. threshold that the system will notify to import*. 

(8)	Select **Availability Qty**.

(9)	Set the number of **threshold** quantity

(10) Select **Both Warehouse and Global** for notification scope

(11) Select **Warehouses** for those rules will be applied

 ![](./instockimages/anh%232.png?raw=true)

***Type 2: Availability Days**
**Availability Days**: you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store)*

(12)	Select **Availability Days**

(13)	Set the number of **threshold days**

(14)	Set the number of **sales period days**

(15)	Select **Both Warehouse and Global** for notification scope

(16)	Select **warehouses** for those rules will be applied

-	**On Actions tab:** 

 ![](./instockimages/anh%233.png?raw=true)

(17)	Enter an **email list** to send the low stock notifications to

(18)	Enter content of the **warning message**

![](./instockimages/anh%234.png?raw=true)

(19)	Click **Save** or **Save and Apply** to finish

- **Save and Continue Edit**: to save the process and continue edit on the current page. 
- **Save and Apply**: you can apply rule immediately
- **Save**: you can save the rule but it will not be applied, in case you need to ask for permission before applying or double-check with other people. 

***Note***: *You can edit the rule that you **Save and Apply** or **Save** by going to **Stock Management > Prediction** section **> Low Stock Rules >** clicking on Edit*

 ![](./instockimages/anh%235.png?raw=true)

#### Low Stock Notifications

- *Path:* **Stock Management > Prediction** section **> Low Stock Notifications**

![](./instockimages/anh%236.png?raw=true) 

**Low Stock notifications** displays warning messages about the products which are nearly out of stock in warehouses. It shows all notifications with information including Sent at, Update Type, Email received, Recipients and Action. Click *view* action on each notification log to see details of products that have been low stock including Name, SKU, Image, Qty Notified and Time Notified.


