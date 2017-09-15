# RETAILER POS MAGENTO 2
(Version 1.1)

*Confidential Information Notice* 

*Copyright 2017 All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

## 	INTRODUCTION
Magento 2 Retailer POS is a point-of-sale app for iOS. With an iPad on hand, sales staff can process easy and fast transactions either on the go or at the counter. Natively build for Magento retail business, this POS allows automatic data synchronization between the app and your Magento store. You can apply custom discounts in cart, accept split payment, note shipping details for each order from your iPad. Ready to sell your products 10 times faster?
## 	HOW TO CONFIGURE
Before using Retailer POS to check out, admin needs to configure it in backend first. Please read the user guide carefully to know how to configure information you want
### 	How to enable a payment method for Retailer POS
To set up payment method for Retailer POS, go to **Sales > Web POS > Settings > Payment for POS**. Then, you will be able to see: 

![RetailerPOS](./Retailer%20POS%20image/image004.png)

>> 	**Applicable payments**: 

•	If you want to apply all payments, choose **All Allowed Payments**

•	If you want to apply some particular payment methods only, choose **Specific Payments**. Then in **Specific Payments** field, select payment method as your preference. Hold Shift + Click to choose more than one.
>>	**Default Payment Method**: You can choose any payment method as default payment method for POS

If you want to set Cash on Delivery (COD) to be the default payment method for instance, you first have to choose it in Specific Payments field. Then, select option Web POS – Cash on Delivery in Default Payment Method field.

![RetailerPOS](./Retailer%20POS%20image/image005.png)

### 	How to set up a shipping method for Retailer POS
To set up Shipping Methods for Retailer POS, go to **Sales > Web POS > Settings > Shipping Methods**, the following page will be shown as below:

![RetailerPOS](./Retailer%20POS%20image/image006.png)

- 	**Applicable shipping methods**: 

•	If you want to apply all shipping methods, choose **All Allowed Shipping**

•	If you want to apply some particular shipping methods only, choose **Specific Shipping**. Then in **Specific Shipping field**, select shipping method as your preference. Hold Shift + Click to choose more than one.

- 	**Default Shipping Method**: You can choose one of three shipping methods supported to set as default payment method for POS

If you want to set Flat Rate - Fixed to be the default shipping method for instance, you first have to choose it in Specific Shipping field. Then, select option Flat Rate - Fixed in Default Shipping Method field.
- 	**Enable "Mark as shipped" by default**: choose Yes if you want to mark items as shipped.

After finishing, click on Save Config button to save your work.
### 	What is default customer & how to configure Default Guest Checkout
#### 	What is default customer
**Default customer** is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically. 
#### 	How to configure Default Guest Checkout
To configure Default Guest Checkout, go to **Sales > Web POS > Settings > Default Guest Checkout**. You will see the configuration page as below: 

![RetailerPOS](./Retailer%20POS%20image/image007.png)

Fill in all information as you want to use as default, including **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone and Email**.
After finishing, click on **Save** or **Save and Continue Edit** button to save your work.
### 	How to change logo of Retailer POS
To change logo of Retailer POS, go to **Sales > Web POS > Settings > Web POS Logo**. In this tab, you can see configuration as follows:

![RetailerPOS](./Retailer%20POS%20image/image008.png)

- **Allow synchronizing from Web POS if there are out-of-stock items**: If you want to show out-of-stock products in search results, choose “Yes”. If not, select “No”.
- **Web POS logo: Upload your logo here**. Please note that recommended size is 250x50px & supported files are jpeg, png
After finishing, click on **Save** or **Save And Continue Edit** button to save your work.

### 	How to add a Retailer POS user
To add new user using Retailer POS, go to **Sales > Web POS > Manage Staff**. Here you can see a list of users that have been created. 

![RetailerPOS](./Retailer%20POS%20image/image009.png)

You can also export user list to csv/xml file or add new Retailer POS user.

- 	Click on **Add User** button then you will be directed to the following page:
 
![RetailerPOS](./Retailer%20POS%20image/image010.png)

Fill in all information of the user, including **User Name, Password, Password Confirmation, Display Name, Email Address, PIN code**. Then, click **Save** or **Save And Continue Edit**.

![RetailerPOS](./Retailer%20POS%20image/image011.png)

Enter all information of the user settings such as **Customer Group, Location, Roles, Status, POS**

Please note that to select the role for user, you need to add a role first. Please go to the section: **_2.6. How to differentiate access permissions of Retailer POS users_** for more details.

- To edit a user, click on the **Edit** link in **Staff manager** page. 

![RetailerPOS](./Retailer%20POS%20image/image012.png)

You can edit which information you want here:

![RetailerPOS](./Retailer%20POS%20image/image013.png)

After finishing, click on **Save User** or **Save And Continue Edit** button to save your work.

### 	How to differentiate access permissions of Retailer POS users
- 	To grant different permission for Retailer POS user, go to **Sales > Web POS > Manage Roles**. The **Role Manager** page will be shown. You can export role user list to csv/xml file: 

![RetailerPOS](./Retailer%20POS%20image/image014.png)

- 	To add a new role, click on **Add Role** button in the top right corner. You will see the **Add Role** page. Here there are three tabs, including **General, Permission** and **Staff List**.
    -In **General** tab, please make sure you fill in enough Role information

![RetailerPOS](./Retailer%20POS%20image/image015.png)

~    - **Role Name**: Enter a specific name for the role in order to find it easily

~    - **Maximum discount percent**: limit the highest discount percent that each user role can offer customers

~    - **Description**: Enter text that describes the role

~    - **Status**: Remember to set Status as Active if you want to enable it
    
~    -In **Permission** tab, choose which all or specific permissions you want to grant for this role. Use Shift + Click to choose more than one
    
  ![RetailerPOS](./Retailer%20POS%20image/image016.png)
    
~    -In **Staff List** tab, tick on users who will have corresponding permission in Retailer POS system.
    
   ![RetailerPOS](./Retailer%20POS%20image/image017.png)
    
After finishing, click on Save or Save And Continue Edit button to save your work.
- To edit a current role, click on "Edit" link on Role Manager page, then you will be redirected to **Edit Role** page: 

![RetailerPOS](./Retailer%20POS%20image/image018.png)

When finishing editing, please click on **Save** or **Save And Continue Edit** button to save the change.
### 	How to add a new POS and assign it to a cashier
- To add a new POS, go to **Sales > Web POS > Manage POS**. The **POS Manager** page will be shown. Click to **Add POS** to create a new POS

![RetailerPOS](./Retailer%20POS%20image/image019.png)

>> Fill enough information for new POS such as **POS Name, Location, Store View, Current Staff, Status, Available for other staff**

![RetailerPOS](./Retailer%20POS%20image/image020.png)


~    - **POS Name**: You enter the name of your point of sales<br/>  
    - **Location**: Select location to set POS. Each location may have a lot of POS<br/>    
    - **Store View**: Select Store view from your list<br/>    
    - **Current Staff**: Staff is working on the POS<br/>    
    - **Status**: Enable or Disable.<br/>   
    - **Available for other staff**: When checked: another staff can use the POS when it is available. 
    
Then, click **Save** or **Save And Continue Edit**.

- To edit a POS, click on the **Edit** link in **POS manager** page. 

![RetailerPOS](./Retailer%20POS%20image/image021.png)

You can edit information of POS here:

![RetailerPOS](./Retailer%20POS%20image/image022.png)

After finishing, click on **Save POS** or **Save And Continue Edit** button to save your work.

- To assign POS to a cashier, go to **Sales > Web POS > Manage Staffs > Edit Staff > POS**. Here you can assign several POS to a staff

![RetailerPOS](./Retailer%20POS%20image/image023.png)

After finishing, click on **Save POS** or **Save and Continue Edit** button to save your work.
### 	How to connect Retailer POS with peripheral devices
Magestore Retailer POS extension can connect with **Barcode readers, Card Swipe, Wireless Cash Drawer & Receipt printers**

•	Card Swipe (via Audio jack)

•	Receipt printer 

•	Barcode scanner (connected via Bluetooth device/iPad camera)

•	Wireless Cash Drawer

## 	HOW TO USE
You have finished settings for Magento 2 Retailer POS, now please move to the part of HOW TO USE Retailer POS for checkout
### 	How a Retailer POS user logs in & manages his account
**After downloading and installing the app in your iPad, open the app and you will see a login screen. User needs to fill in domain, an account & password to continue**:

![RetailerPOS](./Retailer%20POS%20image/image024.png)

To manage his account, the user should tab the menu icon at the top left of the screen >>> **Settings**:

![RetailerPOS](./Retailer%20POS%20image/image025.png)

Then, click on **My Account** tab and the user can see his information. He can also change his password if he wants

![RetailerPOS](./Retailer%20POS%20image/image026.png)

### 	How to switch between cashiers with PIN code
Each staff will be set restrictions based on staff roles and responsibilities. Limit who can make a discount or give a refund. However, with Retailer POS app, you can flexibly switch between cashiers in the middle of transaction just with a PIN code (4 digital) which is added to when creating a POS user. In order to change cashier, you can follow the step below:

- On the left top of the screen click on “change” icon.

![RetailerPOS](./Retailer%20POS%20image/image027.png)

- 	Choose the POS user

![RetailerPOS](./Retailer%20POS%20image/image028.png)

- 	You will have to insert the user's PIN code to be able to continue.

![RetailerPOS](./Retailer%20POS%20image/image029.png)

Now you can see that the cashier has changed.

### 	How to filter & search products quickly

In backend, you can configure to search products by going to **Sales > Web POS > Settings**
- **In General Configuration** section: Enable **Allow synchronizing order from Web POS** if there are out-of-stock items by choosing Yes option.

![RetailerPOS](./Retailer%20POS%20image/image030.png)

- 	**Product Search** section: 

![RetailerPOS](./Retailer%20POS%20image/image031.png)

~   - 	**Product Attribute(s) for Search**: Select attributes by which you want to search products. The default attributes are Name & SKU. If you want to search quickly by barcode, choose barcode attribute. Hold Shift + Click to pick more than one.<br/> 
    -	**Barcode Attributes**: Choose SKU to search products quickly<br/> 
In frontend, you can search products by 3 ways, which are **categories, product attributes and barcode**
- 	Use categories: In frontend, you can click on All Categories link to quickly search products by categories. Choose the corresponding categories as you prefer.

![RetailerPOS](./Retailer%20POS%20image/image032.png)

Besides normal categories, you can select search by Recently Added Products & Frequently Added Products: 

   -	**Recently Added Products**: A list of products that have been newly added to cart. 

    -	**Frequently Added Products**: A list of products that have most often been added to cart 
- 	Use product attributes

To search by product attributes, click on Search icon, then a search bar will be shown. Enter your search terms and matching products will display right away. 

![RetailerPOS](./Retailer%20POS%20image/image033.png)

### 	How to add products to cart
#### 	Add products to cart: 
-	With simple products, you just need 1 tap to add them to cart
-	With configurable, bundle, grouped products, after clicking, you will see a popup shown to choose your option. Then, tap on **Done** button. 

![RetailerPOS](./Retailer%20POS%20image/image034.png)

#### 	Edit products in cart
After adding products to cart, you can edit the quantity of each product by selecting the product that needs editing. A popup will display with edit option for **Qty**. 

![RetailerPOS](./Retailer%20POS%20image/image035.png)

To edit Qty., just enter a wanted number or tap on +/-. The number of products will be adjusted in the cart right away. 
#### 	Remove products in cart
- To remove products in cart one by one, edit the quantity of it back to 0. 

![RetailerPOS](./Retailer%20POS%20image/image036.png)

To clear all cart, tap on “trash” icon on the menu:

![RetailerPOS](./Retailer%20POS%20image/image037.png)

### 	How to add a custom sale item to cart
#### 	What is custom sale item & what it is for
Custom sale item is the item that Retailer POS user creates when checkout. It is used when the product hasn’t been added to the system or Retailer POS user cannot find it in the product list. 
#### 	How to add Custom Sale to cart
In frontend, select Custom Sale button if you want to add the custom product to cart

![RetailerPOS](./Retailer%20POS%20image/image038.png)

A screen will be shown for you to configure this custom product
-	**Name**: Enter the name of custom product
-	**Shippable**: If choose whether this product will be shipped or not by turning on or off this option
-	**Price**: Enter the price of this product

After finishing configuration, tap **Add to Cart** button and check out as normal. Please note that this custom sale product will not be saved for the next checkout. 

![RetailerPOS](./Retailer%20POS%20image/image039.png)

### 	How to apply a coupon code or a cart discount
After adding products to cart, to apply a coupon code or discount on the whole cart, tap on **Discount** button. Then, a popup will display as below:

![RetailerPOS](./Retailer%20POS%20image/image040.png)

You can choose between using **Custom Discount** or **Coupon Code**
- In **Custom Discount** tab:
    -	**Name**: Enter a name for this discount as you will easily check it again
    -	**Discount Type**: Select discount by fixed amount or percentage
    -	**Amount**: Fill in discount value as you offer for your customers. 

Then, the cart will be updated automatically after you click on **Apply** button. 

- In **Coupon Code** tab:

Just fill in available coupon you want to offer for your customers. The cart will be updated automatically after you click on **Apply** button.

![RetailerPOS](./Retailer%20POS%20image/image041.png)

### 	How to apply a custom discount or custom price to a product
After adding products to cart, besides editing the quantity of each product (refer to section **3.4.2. Edit products in cart** for more details), you can click on the product to edit other information. A popup will display with edit option for **Custom Price, Discount**. Remember that you can only change information by Custom Price **OR** Discount, not both of them at a time for a product. 

![RetailerPOS](./Retailer%20POS%20image/image042.png)

- 	You can set custom price for products by tap **Custom Price** button. 
In the popup, please choose type you want to adjust for the price, according to fixed number or percentage. 
    - 	If you edit fixed price, the price will be changed to the price you have entere
    - 	If you edit by percentage, the price will be decrease by the percent you have entered (it is similar to Discount by percentage)
Then, products in cart will be updated with the price you edit
 
- Editing discount for each product is similar to edit by Custom Price. Click on **Discount** button and choose types of discount–fixed discount or percentage–you want to adjust.

![RetailerPOS](./Retailer%20POS%20image/image043.png)

### 	How to handle customer information at checkout
#### 	Customer Checkout
To use **Customer Checkout**, add customer by clicking on **Add Customer** link. You will see a screen as below:

![RetailerPOS](./Retailer%20POS%20image/image044.png)

- earch customers: 

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list. 

The information of customer in the system will be auto updated in checkout step. To edit it, please click on name of customer: 

![RetailerPOS](./Retailer%20POS%20image/image045.png)

In the popup, just edit which information you want. 
- Create new customer

If customer hasn’t been added in your system before, instead of searching, click on **Create New Customer** button.

![RetailerPOS](./Retailer%20POS%20image/image046.png)

Fill enough information of the customer such as **First Name, Last Name, Email, Phone, Group of Customer**. Remember to tap **Save** button to save the customer information for the next checkout. 
- Fill in the information for Shipping Address such as Phone, Street, City, etc

![RetailerPOS](./Retailer%20POS%20image/image047.png)

- Fill enough information of Billing Address such as Phone, Street, City, etc
#### 	Guest Checkout
When you use Guest Checkout, the default customer that you configure in backend will be used (Please hover to the section **2.3.1 What is default customer & how to configure Default Guest Checkout** to get more details). At checkout, all fields will be auto-filled with that default information.

![RetailerPOS](./Retailer%20POS%20image/image048.png)

### 	How to add comments to an order
#### 	When you need to add comments
In some special situations, to remember about your order, you can add comment to it so that you will easily check it later. The comments on order are used internally. 
#### 	How to add comments
Click on **Add Order Comment** icon in the top right corner. In the **Order Comment** box, type the content that reminds you of this order. Then, save it.

![RetailerPOS](./Retailer%20POS%20image/image049.png)

#### 	How to check order comment
- In Retailer POS screen

To view comment of order, you can go to **Orders** tab in Retailer POS screen, choose an order then scroll down to see Comment History

![RetailerPOS](./Retailer%20POS%20image/image050.png)

- In Magento backend

Go to Sales > Orders > click on a specific order. In order details page, scroll down to **Comment History** tab to check whether it has any notes or not. 

![RetailerPOS](./Retailer%20POS%20image/image051.png)

### 	How to process at checkout for a customer
You have been through steps to add products to cart and add customer, let’s move to checkout process. 
- When products are added to cart, select **Checkout** button at the end of the cart page

![RetailerPOS](./Retailer%20POS%20image/image052.png)

You will be redirected to the next page with information of Shipping & Payment Method

![RetailerPOS](./Retailer%20POS%20image/image053.png)

- In Shipping method tab:
    -	Need to Ship: Turn on to add Shipping Address
    -	Choose Shipping method 
    -	Select Delivery date
- In Payment method tab:

For Retailer POS checkout, you can choose among payment methods that are applicable. There are several payment methods for Retailer POS checkout, which you can configure in backend:

![RetailerPOS](./Retailer%20POS%20image/image054.png)

After that, click on **Place Order** button to complete checkout process. There will be a notification as below: 

![RetailerPOS](./Retailer%20POS%20image/image055.png)

### 	Split Payment with Retailer POS
**How to make payment via Retailer POS using multiple methods**

You can use more than 1 payment method for split payments when checkout with Retailer POS. Let me give you an example. 

**Customer’s order value is $125.00**
-	Your customer wants to pay $25 in cash. Then, you fill in the blank space **Retailer POS - Cash-in** with the value of $25. 
-	For the remaining ($68.29), your customer wants to pay by Credit Card. So, at this time, you fill in the amount at the blank space next to **Retailer POS – Credit Card**. 

**_Notes_**: 
-	Support multiple payment methods for one order
-	Not require Cash in method as compulsory
### 	How to create multi-orders for different customers
Retailer POS allows you to create multi-orders for different customers and keep orders open until customers end up transaction. That means you can open multiple orders to serve lots of different customers at the same time. For example someone is paying for something in your shop and they decide to go and get another product, so you can keep this order open while you still can carry on serving the next customer.

![RetailerPOS](./Retailer%20POS%20image/image056.png)

You may select **Continue Processing** whenever customer is willing to take final action for payment or you may **Cancel** it if it is not effective anymore.

![RetailerPOS](./Retailer%20POS%20image/image057.png)

### 	How to print receipt and email order information
You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions. 

![RetailerPOS](./Retailer%20POS%20image/image058.png)

The receipt will look like the screenshot below:

![RetailerPOS](./Retailer%20POS%20image/image059.png)

### 	How to review orders 
In POS screen, you can review orders by choosing **Orders** tab from sidebar. Here you can see the **order list** and **order details**

![RetailerPOS](./Retailer%20POS%20image/image060.png)

- 	Order status

In order list, the status of order is distinguished by color<br/>
    -	Complete: Green<br/>
    -	Processing: Blue<br/>
    -	Pending: Orange<br/>
    -	Canceled: Gray<br/>
    - 	Order searching<br/>

To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![RetailerPOS](./Retailer%20POS%20image/image061.png)

### 	How to create shipment or issue refund for an order
#### 	 How to create shipment
There are two ways to create shipment using Retailer POS: **before placing an order** and **when reviewing order**
- Before placing an order

Before an order is created by clicking **Place Order**, you can create shipment by turn it on as below:

![RetailerPOS](./Retailer%20POS%20image/image062.png)

After verifying shipment method, the system will automatically load to Successful Order Page:

![RetailerPOS](./Retailer%20POS%20image/image058.png)

- When reviewing an order

Another way is to go to **Orders History** tab in Retailer POS screen. Choose the order you want to create shipment, then click on **Ship** button. 

![RetailerPOS](./Retailer%20POS%20image/image063.png)

There will be a message shown to notify you that shipment is created successfully. Please note that to use this way, you need to have permission and be in online mode. 
- Partial Shipment

If you chose to enable Partial Shipment, a box of Items to Ship will appear when you tap **Ship** in **Order** tab. Enter the quantity of each product customers want to ship, select **Ship**.

![RetailerPOS](./Retailer%20POS%20image/image064.png)

#### 	 How to issue refund
Some certain staffs have permission to issue refund by cash (which is set by admin in backend. See **2.6. How to differentiate access permissions of Retailer POS users** for more details).

To issue refund, go to **Orders** tab in POS screen, you choose the order that is required to refund. Tap on **Refund** button in the end. 

![RetailerPOS](./Retailer%20POS%20image/image065.png)

A popup will display so that you can fill in the information before making refund. Tick **Return to stock** if you want to return those items back to your stock.

![RetailerPOS](./Retailer%20POS%20image/image066.png)

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund.
### 	How to run sales report: based on staff, location or payment method
#### 	 Based on Staff
In backend, go to **Sales > Report**. To view reports by staff, please choose **Staff Report**

![RetailerPOS](./Retailer%20POS%20image/image067.png)

The report with information of **Period, Staff, Sales Total** will be show in the table as follows. You can also export it to csv/xml files. 

![RetailerPOS](./Retailer%20POS%20image/image068.png)

#### 	 Based on sale location
Similar to run reports based on staff, go to **Sales > Web POS > Report**. Choose **Location Report** view it in different types. The report will be shown with the information of **Period, Location and Total Sales**. 

Please go to section **3.16.1. Based on Staff** to know more details. 
####  	 Based on payment method
Similar to run reports based on staff and location, go to **Sales > Web POS > Report**. Choose **Payment Report** view it in different types. The report will be shown with the information of **Period, Payment method and Total Sales**. All payment methods will be listed down with the record of Grand Total in details respectively

![RetailerPOS](./Retailer%20POS%20image/image069.png)

### 	How to run reports from Staff account
- Session Management Report

The Z-report will be refreshed to serve new shift/working day after you select **Close Store**. Particularly, your cash drawer will be reset to 0 or to the certain amount

![RetailerPOS](./Retailer%20POS%20image/image060.png)

- Daily Report on POS Orders 

This report contains data of all orders which is similar to your backend but via POS system only by going to **Sales > Web POS > Z-Report**. Want to export data? You can choose 1 of 2 options including csv or excel xml. 

![RetailerPOS](./Retailer%20POS%20image/image071.png)

### 	How to use Session Management
#### 	 What is Session Management
Session Management is a place where records cash flow after each cashier’s shift. You have frequent cash in/out beside normal order transactions like paying electrical bills, balancing cash amount in hand, etc? Retailer POS system records deposits and withdrawals from your working shift then compare them with actual cash amount (counted in notes) after cashier’s shift ends up.
You can easily set up it in Back-end by going to **Sales > Web POS > Settings > Need to create session before working**:

![RetailerPOS](./Retailer%20POS%20image/image072.png)

#### 	 How to create a session
After you choose “Yes” in Back-end to require to open a session before working, the following pop-up will be shown as below:

![RetailerPOS](./Retailer%20POS%20image/image073.png)

Cashiers will carry out to open a new session before getting started their shift. Fill in necessary information for each session
- Responsible: Role of POS user (Cashier, Order management, etc)
- Point of sales: Select POS you are working
- pening Balance: Enter the total amount of cash at the beginning of a new session in your drawer

Then clicking **Open Session** to begin your shift. 

#### 	 How to Record Cash in and Cash out 

After you start a new session, you will see basic information on the current session and may make adjustment of cash in/out during your shift, record deposits and withdrawals from your cash drawer. Cash in and out appears in the drawer history on the iPad, with both the description you enter and the total amount in the drawer.
- Put Money In: Enter the cash amount you add to your drawer and a description

![RetailerPOS](./Retailer%20POS%20image/image074.png)

- Take Money Out: Enter the cash amount you remove from your drawer and a description

![RetailerPOS](./Retailer%20POS%20image/image075.png)

#### 	 How to End a Session 
After your your shift is ended, you can close your session. The popup following will be shown with information of **Opening Balance, Transaction, Theoretical Closing Balance, Real Closing Balance, Difference**:

![RetailerPOS](./Retailer%20POS%20image/image076.png)

You can make adjustment of money in/out and set Closing Balance for your drawer by click “**Set Closing Balance**” button. Enter information such **Coin/Bill value, Number of Coins/Bills, Subtotal** to easily manage the amount of money in your cash drawer 

![RetailerPOS](./Retailer%20POS%20image/image077.png)

Tap **“Confirm”** and Close Session. The popup following will be shown to ensure that you want to close your session at the moment.

![RetailerPOS](./Retailer%20POS%20image/image078.png)

Click to **“Validate”** to close session and view Z-report. The Current Balance will be shown in the Z-report, which will be automatically reset to 0 or certain amount set after you close store.

![RetailerPOS](./Retailer%20POS%20image/image070.png)




