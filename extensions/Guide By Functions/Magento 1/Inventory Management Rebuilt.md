**INVENTORY MANAGEMENT - MAGENTO 1**
----------

**Version 2.1.0**

Confidential Information Notice. Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

-------------

## Introduction

Inventory cost is generally between 20% and 30% of the cost to purchase inventory (http://www.investopedia.com). For many SMEs, this is counted as the major expense whether having online stores or not. As the result, it is vital to have an effective inventory management strategy for saving costs & gaining profits.

![enter image description here](./image_IM%20Rebuilt/image001.png)

The rebuilt **Inventory Management** for Magento 1 has been released to replace the former one. No more complicated pricing plan, the rebuilt version includes mainly features of the **Professional edition** (in old Inventory Management) as well as **new additional features**.
Together with Magento 1 upcoming extensions: Barcode Management, Purchase Management, Order Fulfillment, Dropship & Reports, **Inventory Management** rebuilt is the critical element in **Order Success combo**. Everything in stock is under control, plus, all operations such as add, adjust, transfer stocks are simplified to be completed within the shortest of time! 

## Terminologies and principles

----------

|Terminology| Description| Reference|
|-----------|-------------|-------------|
|Quantity in warehouse(s)| The real quantity of a product in the physical warehouse. It equals the sum of Available Qty and Qty to Ship| 1.1. Stock in Warehouse|
|Available Quantity|The quantity of each product which shows up in Virtual Catalog (front store). It’s also the quantity remaining that are available to be sold| 1.1. Stock in Warehouse|
|Quantity to ship| The number of items has been ordered but not been shipped yet. This number will be returned to Avail Qty & Qty in Warehouse(s) if the shipment is cancelled| 1.1. Stock in Warehouse|
|Shelf Location| Insert the detailed area in the shelf where the product is located. This is how you can support your staff in finding the product efficiently in the physical warehouse| 1.3. Warehouses|
| Warehouse| A “warehouse” in Inventory Management represents for a physical place where you keep your stock. Stocks can be moved between warehouses, purchased for a Warehouse and shipped from a Warehouse. Employees (with different admin accounts) can be restricted to handling only warehouse(s) with which they work| 1.3. Warehouses|
| Primary Warehouse| Primary Warehouse is automatically created after the extension is installed which contains all products in your catalog. This warehouse cannot be deleted to make sure that there is always at least one warehouse consisting of your inventory| 1.3. Warehouses|
|Warehouse Pemission| Assign and manage a staff account permission level in controlling a specific warehouse. Base on Roles Assigned, an user who has full authorities will have permission to create new role & set up new user with specific permissions| 1.3. Warehouses|
|Stock Adjustment|Adjust Stock action is used to correct/ update inventory levels of your products and records them in Stock Adjustment History. This will change the Qty. In Warehouse(s) in the Stock in Warehouse grid of Inventory Management module. After that, the system will update Available Qty. accordingly (or the quantity in default Catalog Products) after subtracting Qty allocated in sales orders from the new Qty in Warehouse(s)|2.1.1. New stock Adjustment|
|Stock Adjustment History | Stock Adjustment History records all inventory corrections/ updates when there are some differences between stock levels of physical and virtual warehouses|2.1.2. Stock Adjustment History|
| Stocktaking| Stocktaking is performed to double-check and prevent any mismatch between the recorded product quantities and the actual inventory in your physical warehouses. The process includes 5 stages containing stock counting and admin’s approval before actually updating the Qty in the system| 2.2.1. New Stocktaking|
|Stocktaking History| Stocktaking History records all stocktaking acts and their process status| 2.2.2. Stocktaking History| 
|Stock Movement History|Stock Movements are records of inward &outward stock transfers of a warehouse| 2.3. Stock Movement History| 
|Supply Needs|Supply Need is the system’s prediction about how many inventory items you need for each product within a future period. The system will calculate this number based on your sales history in the corresponding period in the past| 3.1. Supply Needs| 
|Available Date| Based on the sales history in the chosen sales period, the system will estimate the day which a product is sold out and need to be restocked| 3.1. Supply Needs|
|Low-stock Threshold Type|To get notification about the out-of-stock product, you will have to define how the system process. There are 2 methods: by Available Days or by Available Quantity| 3.2. Low Stock Notification| 
|Threshold (days)| If you insert 3 in this field, the low stock notification will appear 3 days before the product is out of stock. The  sold out day is estimated based on sales history of the chosen sales period|3.2. Low Stock Notification|
|Sales Period (days)|If you insert 30 in this field, the threshold days will be estimated based on sales history in 30 days up to now|3.2. Low Stock Notification|
|Threshold (quantity)|If you insert 5 in this field, the low stock notification will appear when there are only 5 items of the product in stock|3.2. Low Stock Notification|
|Low Stock Notifications| Low Stock Notification shows all notifications following Low Stock Rules set up in the system. You can track the detail of a notification such as Warning Message, Low Stock Threshold Type, Notification Recipients here|3.2. Low Stock Notification|
|Transfer Stock|Transfer Stock is used to manage inventory movements between warehouses or between a warehouse and another location. There are 4 types of Stock Transfers: Send Stock and Request Stock, Transfer to External Location & Transfer from External Location. Inventory is moved & Qty. is changed upon saving these actions|4.1. Stock Transfer|
|Send Stock|This action lets you move inventory from a warehouse to another warehouse| 4.1.1. Send Stock|
| Request Stock|This action lets you request stock for a warehouse from another warehouse|4.1.2. Request Stock|
|Transfer to External Location|This action lets you move inventory from a warehouse to an external location| 4.1.3. Transfer from/to External Location|
|Transfer from External Location|This action lets you move inventory from an external location to a warehouse|T4.1.3. Transfer from/to External Location|
|Stock Sending History|Record all stock sending which is created and note the status of the transfer|4.2. Stock Transfer History|
|Stock Request History|Record all stock requests which are created and note the status of the transfer|4.2. Stock Transfer History|
|History of Stock Transfer to External Location|Record all stock transfers from a warehouse to an external location which are created and note the status of the transfer|4.2. Stock Transfer History|
|History of Stock Transfer from External Location|Record all stock transfers from an external location to a warehouse which are created and note the status of the transfer|4.2. Stock Transfer History|


## How to configure 


----------

### 1. Stock Listing

After installation, the system will automatically provide a Primary Warehouse. This Primary Warehouse cannot be deleted but can only be edited. All the existing products will be automatically synced from your website to this warehouse before you can assign to another warehouse. 
This function consists of 3 tabs to help you manage your inventory successfully:

 - **Stock in Warehouse**: provides an overview of stocks in all warehouses or in a specific warehouse
 - **Non-warehouse Products**: lists out a newly-created product which has not been assigned to any warehouse
 - **Warehouses**: allows you to view and edit details of your warehouses

#### 1.1. Stock in Warehouse

This tab provides an overview of stocks in all warehouses. Here you can view stock SKU, Name, Price, Qty in Warehouse(s), Qty to Ship, Available Qty, Products in Warehouse(s), Stock Movement and Product Status. 
The extension provides an in-depth control over your **composite products** (configurable, bundle and grouped products).  You can see 3 quantity types of each variation or component of the composite product in a specific warehouse. 
For example, if you have a configurable product whose root SKU is Pwt007, you can see the quantities of each available size. If you sell products which often have different sizes and colors like clothing, this is an efficient way to control your inventory. 

![enter image description here](./image_IM%20Rebuilt/image002.png)

Note that there are 3 types of quantity shown:

 - **Qty in Warehouse(s)**: total amount of products in physical warehouses;
 - **Qty to ship**: the number of products which has been ordered and is ready to be shipped;
 - Available Qty: the amount of products left in the virtual catalog which is available to sell.
 
Note that **Qty in Warehouse(s) = Qty to Ship + Available Qty**

You can select a warehouse in the drop-down list and the stock details in that particular warehouse will be displayed. 

![enter image description here](./image_IM%20Rebuilt/image003.png)

Update the total quantity and Shelf Location easily on the Inventory grid in only 3 steps:

 - **Step 1**: Select the product(s);
 - **Step 2**: Input the new Qty in Warehouse(s) and/or Shelf Location;
 - **Step 3**: Click “Update Stock”.

![enter image description here](./image_IM%20Rebuilt/image004.png)

**Shelf Allocation** is a useful information to find the product in the physical stock quickly, especially in fulfilling customer’s order.
In addition, you can edit available qty of products in each Warehouse & Global by accessing to **Catalog > Manage Products**

![enter image description here](./image_IM%20Rebuilt/image005.png)

Then, click on Products you want to edit available Qty, go to **Inventory > Qty** > Tick on **Force edit**

![enter image description here](./image_IM%20Rebuilt/image006.png)

#### 1.2. Non-warehouse Products

When a product is newly-created and has not been assigned to any warehouse yet, it will automatically be allocated in this Non-warehouse list. From here, you can select a product and add it into a specific warehouse.

![enter image description here](./image_IM%20Rebuilt/image007.png)

#### 1.3. Warehouses

The **Warehouses** page displays each warehouse’s details such as its ID, name, total SKUs and total product quantities in each warehouse, contact email/ tel./ address. 
The **Inventory Management** rebuilt allows synchronization between the warehouse and its Magento front store. This means when you edit information or product quantity of a warehouse, this information will automatically be updated in that warehouse’s front store and visible to customers. 
You can enable this function in **Settings.**

![enter image description here](./image_IM%20Rebuilt/image008.png)

You can assign multiple Magento store views to one Warehouse by clicking on “**Mapping Location – Warehouses**” button

![enter image description here](./image_IM%20Rebuilt/image009.png)

You can also create unlimited new warehouses by hitting the “**Add a New Warehouse**” button.

![enter image description here](./image_IM%20Rebuilt/image010.png)

In addition, by clicking on each warehouse, you can access 5 tabs as below:

 - **General Information**: records basic details of the warehouse such as Name, Code, Contact Email, Address, etc. If you enable the “**Link warehouse to Magento front store view**” setting above, this is where you can select the warehouse’s linked front store.
 
![enter image description here](./image_IM%20Rebuilt/image011.png)

 - **Stock On Hand**: lists out all existing products in the warehouse. Clicking on each product will let you promptly revise its total Qty in the specific Warehouse and its Shelf Location. 

On this section, if you click on any warehouses, there will have “**Export**” button along with CSV/Excel XML file.

![enter image description here](./image_IM%20Rebuilt/image012.png)

If you want to add a product into a warehouse, you should go to **Catalog > Manage Product** in your Magento core backend.

![enter image description here](./image_IM%20Rebuilt/image013.png)

 - **Stock Movement**: provides stock changing record of the warehouse. Information includes added/ subtracted quantity, product SKU, movement type, movement date and reference number to access further details by a click.
 - **Warehouse Permission**: lets you assign and manage staff account permission. Here you can set staff permission by clicking at the “Assign Staffs” button at the right of the page. 
![enter image description here](./image_IM%20Rebuilt/image014.png)
An **Assign Staff** window will appear as in the screenshot below. Just select the staff and his/her role, click “**Add Selected Staff**” button and you are done!
![enter image description here](./image_IM%20Rebuilt/image015.png)
You can also select to edit/delete staff permission directly on the **Warehouse Permission** menu.
Finally, do not forget to save your recent changes.

![enter image description here](./image_IM%20Rebuilt/image016.png)

**ADDITIONAL GUIDE: Manage User/ Staff Roles and Permissions**
If you want to create and/or edit user roles and permissions in different sections in the Inventory Management, go to the “**Permission**” submenu under the “**System**” menu of the Magento core backend.

![enter image description here](./image_IM%20Rebuilt/image017.png)

The “**User**” tab lists out all users with details like ID, Username, First name, Last name, Email and Status of the account. Create a new user by clicking a button at the top right of the page.

![enter image description here](./image_IM%20Rebuilt/image018.png)

Admin can view, edit and remove staff permission by clicking on each user. Admin can also assign a warehouse to a user here.

![enter image description here](./image_IM%20Rebuilt/image019.png)

The “**Roles**” tab lets you see a  list  of  role  and  create  a  new  role  for  users. 

![enter image description here](./image_IM%20Rebuilt/image020.png)

In “**Role Info**” tab, you need to input the role name, verify the admin’s password. Then select the checkbox of the role’s permissions in the drop-down list, or select “**All**” in the “**Resource Access**” option to grant full permission to the role. When done, hit “**Save Role**” to finish.

![enter image description here](./image_IM%20Rebuilt/image021.png)

 - **Dashboard** (NEW): demonstrates summarized **sales data** of the warehouse in the last 30 days. You can view data of the warehouse’s sales, best sellers and stock on hand. 

![enter image description here](./image_IM%20Rebuilt/image022.png)

Manage each warehouse’s sales status at a glance with visual charts. You can also print these charts or download with 4 different options of either PNG, JPEG, PDF or SVG vector by opening a menu next to each chart.

### 2. Stock Control

This extension is a powerful assistance to help you keep track of any changes in the existing stock. It combines 5 functions in 1:

 - **New Stock Adjustment**: manually adjusts stock quantity;
 - **New Stocktaking**: assists in a complete stocktaking process;
 - **Stock Adjustment History**: records details of all stock adjustments;
 - **Stocktaking History**: records details of all stocktaking;
 - **Stock Movement History**: records all movements of stock in the warehouses

#### 2.1. New Stock Adjustment and Stock Adjustment History

##### 2.1.1. New Stock Adjustment

Sometimes your recorded product quantity does not match the actual physical number. Then, this function is exactly what you need to make changes quickly. To make a new stock adjustment, you need to select the warehouse which stores the product to be adjusted, fill in the reason for the adjustment and click “**Start to Adjust**” at the top right of the page.

![enter image description here](./image_IM%20Rebuilt/image023.png)

The next window allows you to select whatever product you want to adjust its quantity and type in the new figure. Alternatively, you can import product quantities via a CSV file with a provided sample. This means you can adjust quantities of several products at once.

![enter image description here](./image_IM%20Rebuilt/image024.png)

Then you have 3 options to enable your changes:

 - **Save**: temporarily save the adjustment in Pending status. You will automatically transferred to the Stock Adjustment History page. 
 - **Save and continue to edit**: temporarily save the adjustment in Pending status. You continue to stay on a page with your products to continue any further edits. 
 - **Adjust**: immediately activate the quantity changes. Once you hit this button, there is no way to undo it unless you carry out another stock adjustment. The adjustment is marked Completed on the History page.

![enter image description here](./image_IM%20Rebuilt/image025.png)

##### 2.1.2. Stock Adjustment History 

The Stock Adjustment History page shows details of each adjustment including date of the adjustment, staff who made the adjustment, warehouse name and status.

![enter image description here](./image_IM%20Rebuilt/image026.png)

All adjustments, whether in Pending or Completed status, are recorded on the Stock Adjustment History page. 

![enter image description here](./image_IM%20Rebuilt/image027.png)

Clicking on each adjustment will transfer you to a page where you can see more information of an adjustment including adjusted product ID, Name, SKU, old Qty and Adjusted Qty. For an adjustment with Pending status, this is the page where you have left the unfinished adjustment. Complete it by clicking “**Adjust**”. 

![enter image description here](./image_IM%20Rebuilt/image028.png)

#### 2.2. New Stocktaking and Stocktaking History

##### 2.2.1.	New Stocktaking

This tool will help you carry out a stocktaking successfully to prevent any mismatch between the recorded product quantities and the actual inventory in your physical warehouses. 

![enter image description here](./image_IM%20Rebuilt/image029.png)

This process consists of 5 easy-to-follow stages:

 - Stage 1: **General Information**
In this Stage, you select the warehouse you want to stock take, the reason for stocktaking. You can also fill in the participants and the time of the action but it is optional.
Next, you can choose the products to be stock taken by clicking the “**Prepare Product List**” button (Stage 2) at the top right of the page. Alternatively, you can skip it to go straight to Stage 3 by clicking the “**Start Stocktaking**” button.

![enter image description here](./image_IM%20Rebuilt/image030.png)

 - Stage 2: **Prepare Products**
You can select the products you want to stock take here or import products using a CSV file.

![enter image description here](./image_IM%20Rebuilt/image031.png)

**Save** to stay with your selected products for further edits, or click “**Start Stocktaking**” to proceed Stage 3.

 - Stage 3: **Stock Counting**

Select and type in the product quantity that you have recently counted. 
Click “**Complete Data Entry**” to proceed to Stage 4 and have a review of the changes, click “**Complete Stocktaking**” to finish the process or “**Save**” to continue editing.

![enter image description here](./image_IM%20Rebuilt/image032.png)

 - Stage 4: **Complete Data Entry**
This Stage allows you to have a final review of your recent quantity counts. Click either “**Re-entry Data**” or “**Complete Stocktaking**” to move to Stage 5. If you are not an admin, your counting results will be submitted to the admin/ manager for approval before the new quantity is officially updated and the process is marked Completed. 

![enter image description here](./image_IM%20Rebuilt/image033.png)

 - Stage 5: **Complete Stocktaking**
This page shows you all details of the stocktaking process including the product quantity before and after the stocktaking process. Make a **New Stock Adjustment** by hitting the “**Adjust Stock**” button or download a CSV copy of the grid using the “**Download Difference List**”.

![enter image description here](./image_IM%20Rebuilt/image034.png)

##### 2.2.2.	Stocktaking History

All Stocktaking details are listed here. Different status shows to which stage the stocktaking process is done:

 - Status “Pending” means Stage 1: General Information is done
 - Status “Processing” means Stage 2: Prepare Products is done
 - Status “Verified” means Stage 3: Stock Counting is done

![enter image description here](./image_IM%20Rebuilt/image035.png)

Click on each stocktaking record to view all details of the process.

#### 2.3. Stock Movement History

This menu records all movements of the stock in each warehouse. The table shows the number of products added/subtracted from the warehouse, product SKU, product movement type, warehouse name, reference number, movement date. Filtering a SKU will help you track the product’s movements and changed quantity in each warehouse in no time.

![enter image description here](./image_IM%20Rebuilt/image036.png)

Clicking on each movement item will open up its further details. 
You also have options to export the stock movement data to CSV or Excel XML file.

### 3.	Prediction

#### 3.1. Supply Needs (FEATURED)

There’s no need an assistant to analyze and show you whether you should order additional items for a specific product in the next Order Purchasing or not. **Inventory Management rebuilt** allows you to get the prediction of supply needs until the certain time stamp.
To process a prediction, choose the warehouse(s) you would like to analyze, select the time range to collect sales data and then pick the date that you want to see forecast results. Click to **Show Supply Needs** button to finally view the prediction.

![enter image description here](./image_IM%20Rebuilt/image037.png)

The forecast data will be shown in the table as below:

![enter image description here](./image_IM%20Rebuilt/image038.png)

Here, you can view the average quantity sold per day of the product during the chosen sales period. The prediction will show you **Available Date** which performs the forecast day of product’s running out of stock. The **Supply Needs** column demonstrates the quantity of product that expected to be sold until the time stamp you set.
For instance, the product msj000 has been sold 6 items in total during the last 30 days. It is estimated that the remaining quantity will be enough to be sold until 9/7/2017. It also suggests you to add further 11 items if you want to meet the customers’ demand until 31/8/2017.
To export the supply needs file, you can choose to export into CSV or XML file and click to Export. To start another prediction, you may edit criteria for supply forecasting and hit Show Supply Needs again to refresh the prediction result.

#### 3.2. Low Stock Rules & Low Stock Notification

**Low Stock Notifications** are as its name, system emails or notifications to inform admin, warehouse managers when some products are going to be out of stock. To have Low Stock Notification, you need to set up rules in the **Low Stock Rules** section. 

##### 3.2.1.	Low Stock Rules

Admin can create unlimited rules to notify low stock status. One rule contains: Rule Information, Conditions & Action. There is no limitation in the quantity of rules set.

 - **Rule Information**: includes general data such as Rule Name, Status, and Update Time. You can set up the period of time in which the Low Stock Notification is activated.

![enter image description here](./image_IM%20Rebuilt/image039.png)

 - **Condition**: allows you to set up Product Conditions & Low Stock Condition. In the Product Conditions section, you can set the limitation for applying rules. For example, the Low Stock Rule is applied for category Decorative Accents or a specific product.
As for Low Stock Condition, there are 2 rule types for you to select: Available Days and Available Quantity. With **Available Days** option, the system will estimate how many days the product is available for purchasing based on its sales history. 

![enter image description here](./image_IM%20Rebuilt/image040.png)

For instant, if you set sales period equals to 30 and the threshold day is 3, the notification will appear 3 days before the product is out of stock which are predicted following the sales history in 30 days up to now.
With **Available Quantity** option, it only request for threshold quantity that you would like to receive low stock notification. If you set the threshold is 5, the system will notify you when the quantity of product(s) reach that number. 

![enter image description here](./image_IM%20Rebuilt/image041.png)

 - **Action**: confirms who will receive the low stock notification by listing the email in Notification recipient list and the message which will appear.
 
![enter image description here](./image_IM%20Rebuilt/image042.png)

Remember to select **Save and Apply** to start running the Low Stock Rule

##### 3.2.2.	Low Stock Notifications

The list displays all notification following the low stock rules. Notifications are noted with Created Date, Warning Message, Notification recipients. Click to **Action > View** to access the detail.

![enter image description here](./image_IM%20Rebuilt/image043.png)

Each notification allows you to track the low stock products’ information such as SKU, Name, and Current Qty.
The Low Stock Notification will be sent to recipients’ email as well as be displayed on the Inventory Management panel.

![enter image description here](./image_IM%20Rebuilt/image044.png)

### 4.	Stock Transfer & Stock Transfer History

#### 4.1. Stock Transfer

There are **four major operations** in Stock Transfer section: Send Stock, Request Stock, and Transfer to External Location & Transfer from External Location. All actions leads to the same purpose: to move stock immediately. This is helpful if you want to update the quantity in the system:

 - Quickly without going through a step-by-step process
 - Or following closely to the process and allowing the admin in destination warehouse check how the quantity is transferred in reality.

##### 4.1.1. Send Stock 
You can use Send Stock to move items from one warehouse to another warehouse. The quantity will be updated in each warehouse after you complete sending stock while the total quantity in the inventory is unchanged. 
To start sending stock, go to **Inventory > Transfer Stock > Send Stock.** 

 - Choose a **Source Warehouse** and a **Destination Warehouse**
 - Fill in the **Reason(s) for sending stock** field. It is required for reviewing the transfer later.
You can also change the **Transfer Code** as preferred.

![enter image description here](./image_IM%20Rebuilt/image045.png)

 - Click on Prepare Product List
 - You can import the product list via CSV files following the sample format.

![enter image description here](./image_IM%20Rebuilt/image046.png)

Or, you can select products to send manually

![enter image description here](./image_IM%20Rebuilt/image047.png)

 - Once finished, click on **Direct Transfer** to start the stock sending instantly. The transfer will be recorded as **completed** if you choose to Direct Transfer. The transfer will be recorded as **pending** if you only click to **Save**.
 - Or, you can keep track on the transfer process by clicking on **Start** **Sending**. The transfer will move to **processing** status if you start sending.
Here, the admin staff in Destination Warehouse can check the quantity that they actual receive. For some reasons (the shipping is delayed, some products in broken, incorrect counting before sending…), the quantity that destination warehouse received is less than the quantity sent. In that case, the admin notes down the actual quantity and select Save Receiving.

![enter image description here](./image_IM%20Rebuilt/image048.png)

The admin can keep updating the receiving quantity until all quantity is sent completely. 
Then, complete the transfer by select **Mark as Completed**. Please note whatever the status of the transfer is, they are all listed in **Stock Sending History.**

![enter image description here](./image_IM%20Rebuilt/image049.png)

##### 4.1.2. Request Stock

A warehouse can place a request stock for another warehouse. When the request is marked as completed, the quantity will be updated automatically in both warehouse and the total quantity in Inventory remains unchanged.
You can assign a user to have the right to Send/Request Stock by setting up in the Permission section. 
To create new Stock Request, go to **Transfer Stock > Request Stock**

 - Choose a **Source Warehouse** and a **Destination Warehouse**. Source Warehouse is where you would like to send the request to.
 - Fill in the **Reason(s) for sending stock** field. It is required for reviewing the transfer later. You can also change the **Transfer Code** as preferred.
 
![enter image description here](./image_IM%20Rebuilt/image050.png)
 - Click on Prepare Product List
 - You can import the product list via CSV files following the sample format. Or, you can select products for requesting manually.

![enter image description here](./image_IM%20Rebuilt/image051.png)

 - Once finished, click on **Start Request** to start the stock requesting. The transfer will be recorded as **pending** if you only click to **Save**.

Here, the admin staff in Source Warehouse can check the quantity that they send in the **Delivery History.**

![enter image description here](./image_IM%20Rebuilt/image052.png)

For some reasons (e.g. shortage of quantity…), the quantity that source warehouse send might be less than the quantity requested. In that case, the admin notes down the actual quantity for sending and select **Save Delivery.**

![enter image description here](./image_IM%20Rebuilt/image053.png)

The admin in Source Warehouse can keep updating the sending quantity until all quantity is sent completely.

![enter image description here](./image_IM%20Rebuilt/image054.png)

Meanwhile, the admin in Destination Warehouse can track the quantity that they receive in **Receiving History** tab. Then, complete the transfer by select **Mark as Completed.** 

![enter image description here](./image_IM%20Rebuilt/image055.png)

Please note whatever the status of the transfer is, they are all listed in **Stock Request History.**

##### 4.1.3. Transfer from/to External Location

 - **Transfer stock to External Location**: this feature allows you to note all transactions sending stock from a warehouse to other destinations (not warehouse). 
 - **Transfer stock from External Location**: this feature allows you to note all transactions receiving stock from a location (not warehouse) to a specific warehouse.

Both of these actions can be processed by 3 steps: select product list, insert quantity for transferring and click on Start Transferring.

![enter image description here](./image_IM%20Rebuilt/image056.png)

All transfer relating to external location are recorded in H**istory of Stock Transfer to External Location or History of Stock Transfer from External Location.**

### 4.2. Stock Transfer History

The record of stock transfer is separated into 4 lists corresponding to 4 operations of stock transfer as mentioned above. For example, **Stock Request History** will show you a list of all stock requests created in the system.

![enter image description here](./image_IM%20Rebuilt/image057.png)

## Settings 

Go to **Settings** tab, the configuration page contains several criteria as below:


![enter image description here](./image_IM%20Rebuilt/image058.png)

| Settings| Description| Example|
|---------|--------------|--------------------|
|Link Warehouse to Magento front store view|Allows admin to set corresponding store front to a specific warehouse|Link **English Store View** to **Primary Warehouse** |
|Adjust Stock by entering the change Qty|Instead of insert new quantity of the products, this setting allow the admin to insert its change quantity| Change Quantity of msj777 is 5 meaning that you add 5 more items to the current quantity when adjusting the stock of msj777| 
