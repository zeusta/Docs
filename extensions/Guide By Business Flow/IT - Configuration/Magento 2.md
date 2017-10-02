
# USER GUIDE FOR IT ADMIN
-----

*Confidential Information Notice.* 

*Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.* 

*This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

---------

## I. INTRODUCTION
This guide will help you – an IT Manager – to configure a successful strong system for the retailers and support you to activate the most suitable features for the business.    Through the guide, you will understand how Omni-channel company will be built and work with MageStore packages. Moreover, you will get basic knowledge about how you can decentralize roles, users and staffs for your company.

------
## II. HOW TO INSTALL


### 1.	Generate License Certificate

After purchasing an module, you will receive an email that includes the link to access **My License Certificates** on Magestore website.

![](./img102/it_img001.png?raw=true)

If you don’t receive the email, you can directly log in to your account dashboard at Magestore then go to **My Account/My License Certificates**.

![](./img102/it_img002.png?raw=true)

Here you will select your Order number and a corresponding Product then type the **back-end domain of your live site**. It is optional to add your Development Domains right away or later.

Click on the **Generate Certificate** button to get your License Certificate.

***Note:*** *License Certificate is a PDF document that contains your **License Information** including:*

1)	Product Name
2)	License Serial
3)	License Type
4)	Registered Domain
5)	Activation Date
6)	Expiration Date

Your **License Serial** is unique and can only be used once for one module.

You also can go to **MageStore Check License Information** page, enter your License Serial to check your license status.

You **do not need to insert this license serial into your module back-end**. Simply provide it in your ticket/ email when you request for our support.


### 2.Download Solution Package

Go to **My Downloadable Products**. Click on the version of that you want to install to download it. The file that you download is normally a zip file.

Here you also can find related documents, such as user guide.

![](./img102/it_img003.png?raw=true)


### 3.	Install the Package Downloaded

If you are new to Magento 2, you probably need a little help to get started before installing an module:

1)	Is the Magento software installed already?
2)	What’s a terminal, command prompt, or Secure Shell (ssh)?
3)	Where’s my Magento server and how do I access it?

Please note that we take Gift Card as our example in this Installation guide.

**Step 1: Verify your prerequisites**

Use the following table to verify you have the correct prerequisites to install the Magento software.

| Prerequisite | How to check | For more information|
| --- | ----| ----|
|Magento version Starter Edition| Go to admin page, you can see version of Magento 2 at left bottom page|Download Magento version Growth Plus|

**Step 2: Install and verify the installation**

Unzip the module package downloaded. When you have completed, you will have a folder named “app” containing all files of this module:

Now, please connect to your FTP by using FileZilla or other FTP Application to upload the files to your server:

![](./img102/it_img004.png?raw=true)

After uploading all the files to your server, please login to your SSH by using Putty or SSH command line. Them, please use “cd” command to change the directory to Magento 2 root folder:

***cd [magento 2 root folder]***

Run the setup:upgrade command line:

***php bin/magento setup:upgrade***

Wait a second to complete installation process:

![](./img102/it_img005.png?raw=true)

If your website is in the Production mode, you should re-run the Magento compile command. Please enter the command:

***php bin/magento setup:di:compile*** 

![](./img102/it_img006.png?raw=true)

After that, if your website is in the Default or the Production mode, please type the command line to deploy the static content:

***php bin/magento setup:static-content:deploy***

![](./img102/it_img007.png?raw=true)

Then, if your website enabled the cache, please enter this command:

***php bin/magento cache:flush***

Finally, coming back to Magento 2 admin to check if the module is installed properly. 

***Note:*** *In case that you have followed all above steps but couldn’t make the module work properly, to make your website function as normal, please contact us at support@magestore.com or support.magestore.com, our supporters will assist you in resolving any issues within 24 hours.*

--------

## III.	HOW TO CONFIGURE

### 1.	Multi-companies (Coming soon)

### 2.	Inventory

#### 2.1.	Stock Control Configuration

Path: **Stores > Settings** section> **Configuration > MageStore Module > Inventory Management Configuration**

![](./img102/it_img008.png?raw=true)

(1)	**Link stocks in Warehouse to Front Store View**: choose **Yes** to activate the visibility of Stocks in Warehouse on the Front Store View 

(2)	**Adjust Stock by entering the change Qty.**: if you choose **Yes**, when you enter the change Qty. of products, the system will automatically reset for you to the right 

(3)	Click **Save Config** to finish

#### 2.2.	Pricelist Configuration

***Note: Pricelist** is a list of current prices of items on sale*

Path: **Stores > Settings** section **> Configuration > MageStore Module > Supplier Configuration**

![](./img102/it_img009.png?raw=true)

(1)	Select **Yes** to allow using and importing supplier pricelist, and vice versa.

(2)	Click **Save Config**.


#### 2.3.	Stock Option

Path: **Stores > Settings** section **> Configuration > Catalog > Inventory**

***Note:** If you want to configure based on your own features, then unmark box **Use System value**.*

##### 2.3.1.	Stock Option

![](./img102/it_img010.png?raw=true)

(1)	Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.

(2)	Select **Yes** in the dropdown list to return items to stock if an order is cancelled.

(3)	Select **Yes** in the dropdown list to continue to display products in the catalogue that are no longer in stock. 

(4)	Enter the number in the blank to display the message: **Only x left** on website when the quantity in stock reaches the threshold.  

(5)	Select **Yes** in dropdown list to display an **In Stock** or **Out of Stock** message on the product page.

(6)	Tap **Save** to finish. 

##### 2.3.2.	Product Stock Options

Path: **Stores > Settings** section **> Configuration > Catalog > Inventory**

![](./img102/it_img011.png?raw=true)

(1)	Select Yes to activate inventory control for your catalog. 

(2)	Set Backorders to one of the following status: 

•	**No Backorders Allow Qty. Below 0:** To reject backorders when product is out of stock.

•	**Allow Qty. Below 0:** To accept backorders when the quantity falls below zero. 

•	**Notify Customer:** To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

(3)	Enter the **Maximum Qty.** allowed in Shopping Cart.

(4)	Enter the quantity for Item's Status to become out of stock.

(5)	Enter the **Minimum Qty.** allowed in Shopping Cart.

Next, 

![](./img102/it_img012.png?raw=true) 

(6)	Enter the stock level that generate notification showing the item is out of stock.

(7)	Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.

(8)	Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.
Finally, click on **Save Config** to save changes.

#### 2.4.	Low Stock Notification Rules

***Note: Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.* 

Path: **Inventory Management > Prediction** section **> Low Stock Rules**

![](./img102/it_img013.png?raw=true)

(1)	Click Add new rule to create a new low stock notification rule

![](./img102/it_img014.png?raw=true)

(2)	Enter the low stock rule name

(3)	Add a brief about the rule (optional)

(4)	Select Active to enable the rule

(5)	Use Calendar to choose From and To date for a term of validity (optional)

![](./img102/it_img015.png?raw=true)

(6)	Select an **update time**:

•	Daily

•	Monthly

The system periodically check stock availability and automatically send email notifications admin and warehouse managers.

(7)	**Select hours** the warning message will be sent

![](./img102/it_img016.png?raw=true)

On the **Conditions Tab**:

There are 2 types of low stock rule: 

***Type 1: Availability Qty.***

***Availability Qty.:*** you can select Qty. threshold that the system will notify to import. 

(8)	Select **Availability Qty.**

(9)	Set the number of **threshold** quantity

(10)	 Select **Both Warehouse and Global** for notification scope

(11)	 Select **Warehouses** for those rules will be applied

![](./img102/it_img017.png?raw=true)

**Type 2: Availability Days**

***Availability Days:*** you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store)

(12)	Select **Availability Days**

(13)	Set the number of **threshold days**

(14)	Set the number of **sales period days**

(15)	Select **Both Warehouse and Global** for notification scope

(16)	Select **warehouses** for those rules will be applied

![](./img102/it_img018.png?raw=true)

On **Actions** Tab:

(17)	Enter an **email list** to send the low stock notifications to

(18)	Enter content of the **warning message** 

![](./img102/it_img019.png?raw=true)

(19)	Click **Save** or **Save and Apply** to finish

•	**Save and Continue Edit**: to save the process and continue edit on the current page. 

•	**Save and Apply**: you can apply rule immediately

•	**Save**: you can save the rule but it will not be applied, in case you need to ask for permission before applying or double-check with other people. 

***Note:** You can edit the rule that you **Save and Apply** or **Save** by going to **Inventory Management > Prediction** section **> Low Stock Rules >** clicking on **Edit***

![](./img102/it_img020.png?raw=true)
