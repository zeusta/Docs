# WEB POS - MAGENTO 1

**Version 3.0.5**

---------------
## INTRODUCTION

Running a quick service, retail store or restaurant? Then you know how important it is to have an effective POS to cut the long queue of customers waiting to check out. For most of the time, your shop assistants have to carry out the checkout procedures for Customers, either in physical stores or when receiving orders through phone or email. So, wouldn't it be great if this process could be hastened, helping save time for more profitable actions! With Magestore’s **Magento POS** integration module, you will be able to create orders quickly and conveniently from an admin panel on just a single one page! Try now and you will be fascinated by its convenience and the amount of time saved.

Magento [Web-based Point-of-Sale](https://www.magestore.com/webpos) is one module in our [Omnichannel solution](https://www.magestore.com/omnichannel-retail) for Magento retailers.

---------------

## HOW TO CONFIGURE

Before using Web POS to check out, admin needs to configure it in backend first. Please read the user guide carefully to know how to configure information you want.

### How to change logo of Web POS

To change logo of Web POS, go to **Sales > Web POS > Settings > General Configuration.** In this tab, you can see configuration as below:

![configure webPOS logo](./Image_Web%20POS/image007.jpg)


-	**Web POS logo**: Upload your logo here. Please note that recommended size is 260*120px and supported files are jpeg & png.

-	**Web POS color**: Enter the color code to change Web POS color.

After finishing, click on **Save or Save And Continue Edit** button to save your work.

### How to set up a shipping method for Web POS
<a name="p5"> </a>

To set up Shipping Methods for Web POS, go to **System > Configuration > Shipping for POS**, the following page will be shown as below:
![Shipping for POS panel](./Image_Web%20POS/image009.jpg)

-	**Offline Shipping Methods**: Hold Shift + Click to choose the payment methods used for POS.

-	**Default Shipping Methods**: Choose the shipping methods you want to set as default for POS.

### How to enable a payment method for Web POS

To set up payment method for Web POS, go to **Web POS > Settings > Payment for POS**. Then, you will be able to see:

![Payment for POS panel](./Image_Web%20POS/image011.jpg)

-	Applicable payments:

     -	If you want to apply all payments, choose **All Allowed Payments**
     -	If you want to apply some particular payment methods only, choose **Specific Payments**. Then in **Specific Payments** field, select payment method as your preference. Hold Shift + Click to choose more than one.

-	**Default Payment Method**: Choose the payment method that you would want to set as Default payment method.

If you want to set Cash In to be the default payment method for instance, you first have to choose it in **Specific Payments** field. Then, select option **Cash In** in **Default Payment Method** field.

![Set Default Payment Method](./Image_Web%20POS/image013.jpg)

Magestore WebPOS well integrates with Pay.nl payment gateway, allowing more flexible payment methods for customers.

### How to disable inactive categories
<a name="p4"> </a> 

To set up payment method for Web POS, go to **Web POS > Settings > Product Search**.Then, you will be able to see:

![Product Search panel](./Image_Web%20POS/image015.jpg)

-	If you want to show inactive categories on the website, you choose **Yes**.
-	If you want to hide inactive categories on your website, you choose **No**.

### What is default customer & how to configure Default Guest Checkout

#### What is default customer

**Default customer** is the customer whose information will be used for Guest Checkout or if customer information is not enough, default value will be filled automatically.

#### How to configure Default Guest Checkout

To configure Default Guest Checkout, you go to **Web POS > Settings > Default Guest Checkout**. You will see the configuration page as below

![Default Guest Checkout page](./Image_Web%20POS/image017.jpg)

Fill in all information as you want to use as default, including **Default Customer ID, First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**.

After finishing, click on **Save** or **Save And Continue Edit** button to save your work.

### How to enable offline mode

Offline mode is when there is no Internet Connection. When you are in offline mode, you can still check out as normally and then, the data will be saved as offline order. After the system can connect to the Internet, the order can be synced & completed.

To enable offline mode, you go to **Web POS > Settings >General** then choose tab **Checkout**. You choose **Yes** option to use online mode and choose **No** to use offline mode.

The promotion rule auto check can be applied for offline mode only, choose **Yes/ No** to activate/ turn off this function. See the screenshot below:
![enable/disable offline mode](./Image_Web%20POS/image019.jpg)

### How to add a Web POS user

To add new user using Web POS, go to **Web POS > Web POS Permissions > POS Users**. Here you can see a list of users who have been created.
![POS Users page](./Image_Web%20POS/image021.jpg)

You can also export user list to CSV/ XML file or add new Web POS user.
-	Click on **Add User** button then you will be directed to the following page:

![User Information page](./Image_Web%20POS/image023.jpg)

Fill in all information of the user in **User Information & User Settings** then, click **Save** or **Save And Continue** Edit.

Please note that to select the role for user, you need to add a role first. Please go to the section: **How to differentiate access permissions of Web POS users for more details**.

-	To edit a user, click on the **Edit** link in **POS Users** manager page.
![POS Users manager page](./Image_Web%20POS/image025.jpg)

You can edit information here. After finishing, you click on **Save** to save the changes.

### How to differentiate access permissions of Web POS users

To grant different permission for Web POS user, go to **Web POS > Web POS Permissions > POS Roles**. The **Role Manager** page will be shown. You can export role user list to csv/xml file:
![Role Manager page](./Image_Web%20POS/image027.jpg)

To add a new role, click on **Add Role** button in the top right corner. You will see the Add page. Here, there are two tabs: **Role Information** and **User List**.

-	In **Role Information** tab, please make sure you fill in enough information
![Role Information tab](./Image_Web%20POS/image029.jpg)

     -	**Role Name**: Enter a specific name for the role in order to find it easily
     -	**Permissions**: Choose which all or specific permissions you want to grant for this role. Use Shift + Click to choose more than one
     -	**Maximum discount percent**: Limit the highest discount percent that each user role can offer customers.
     -	**Description**: Enter text that describes the role
     -	**Status**: Remember to set Status as Active if you want to enable it

-	In **User List** tab, there is a list of users who will have corresponding permission in Web POS system. You can delete/ enable users right on this board. After finishing, click on **Save** or **Save And Continue Edit** button to save your work.
![User List tab](./Image_Web%20POS/image031.jpg)

     -	To edit a current role, click on "Edit" link on Role Manager page, then you will be redirected to **Edit Role** page. When finishing editing, please click on **Save** or **Save and Continue Edit** Button to save the change.

![ Edit Role page](./Image_Web%20POS/image033.jpg)

### How to connect Web POS with peripheral devices

Magestore Web POS module can connect with **Barcode readers, Card swiper, Receipt printer & Customer pole display.**

-	Barcode readers: any devices that connect with iPad/laptop/PC (no matter through usb port, wifi or bluetooth) - as long as the scanner can read barcodes & fill encoded information into Web POS search box.

-	Card readers: only devices connected through USB port.

-	Receipt printers: any devices that connect with iPad/laptop/PC (no matter through usb port, wifi or bluetooth).

-	Pole display:

**How to integrate Customer pole display with Magento Web POS**

You should install customer pole display’s driver if your device has driver before taking the following steps.

Firstly, you need to enable Pole display function in Web POS settings. Go to Magento backend, choose **Sales > Web POS > Settings**, then choose **Yes** in field **“Integrate with Pole Display device”**.

![Integrate with Pole Display device field](./Image_Web%20POS/image035.jpg)

Secondly, you need to install the desktop application to connect your PC/ Laptop with the pole. After purchasing Web POS, you can download the Pole Display integration file which contains these following files & folders:

![Pole Display integration files and folders](./Image_Web%20POS/image037.jpg)

Then follow these steps:

-	**Step 1**: Install the .NET Framework 4.5.2

     +	Open the folder .NET Framework 4.5.2
     +	Run NDP452-KB2901907-x86-x64-AllOS-ENU.exe file and install it to your computer.

-	**Step 2**: Intall the USB to Serial COM setup:

     +	Open the folder USB to Serial COM
     +	Run CDM21224_Setup.exe and install it to your computer

-	**Step 3**: Run the Pole Integration.exe file:

![Pole Integration run file](./Image_Web%20POS/image039.jpg)

You need to open this program when using Web POS to use customer pole display.

--------------------

## HOW TO USE

You have finished settings for Web POS, now please move to the part of How to use Web POS for checkout.

### How a Web POS user logs in & manages his account

After you create user with specific permission in using Web POS, you can send him Web POS checkout link or guide him to access from Web POS backend by going to **Web POS ->	Web POS Checkout**. Then, a login form will appear. User needs to choose store (if website has multi store views) then fill in your account & password to continue:

![user chooses store view](./Image_Web%20POS/image041.jpg)

To manage his account, the user should go to Settings tab > My Account:
![Account tab in left menu](./Image_Web%20POS/image043.jpg)

Then, click on **My Account** link and the user can see his information. He can also change his password if he wants.
![My Account panel](./Image_Web%20POS/image045.jpg)

### How a Web POS user deletes/ reloads data in local manually
<a name="p7"> </a>

-	**When to use:**

In the first time a user log in to Web POS Checkout screen, the module will load data like products, customers, tax calculations, etc. to his local. Then the system will automatically update new data about products, customers... when having any changes in admin panel.

In some cases, a user's local data is not 100% synced with data in the back-end. If the user notices any discrepancy, he can delete and reload data manually.

-	**How to use**:

To reload data, go to **Setting > Synchronization** then choose **Reload** (to reload each category) or **Reload All** (to reload all data).
![Sync Data tab](./Image_Web%20POS/image047.jpg)

-	**_Notes_**:

For data storage, in case the user closes his browser or restarts the system, Web POS still keeps all previous data so he can continue working without any problem.

### How to filter & search products quickly

You can configure to search products by going to Settings > General

-	In Catalog tab: Enable **Display out-of-stock products in search results (online mode)** by choosing **Yes** option. If you choose **No** option, out-of-stock products will not display in search results.

**Note**: This function is available for online mode only.
![Enable Display out-of-stock products in search results (online mode) function](./Image_Web%20POS/image049.jpg)
<a name="p3"> </a>

**Product Search** section: You go **Web POS ->Setting** and choose tab **Product Search**.

![Product Search section](./Image_Web%20POS/image051.jpg)

   -	**Product Attribute(s) for Search**: Select attributes by which you want to search products. The default attributes are Name & SKU. If you want to search quickly by barcode, choose barcode attribute. Hold Shift + Click to pick more than one.

In frontend, you can search products in 3 ways - **categories**, **product attributes** and **barcode.**

-	Use categories: In frontend, you can click on All Categories link to quickly search products by categories. Choose the corresponding categories as you prefer.

![All Categories link at top right of the page](./Image_Web%20POS/image053.jpg)

-	Use product attribute

To search by product attributes, click on Search icon, then a search bar will be shown. Enter your search terms and matching products will display right away.

![Search bar](./Image_Web%20POS/image055.jpg)

-	Use barcode

     -	Connect Web POS with barcode reader devices (Please refer to **How to connect Web POS with peripheral devices for more details**)
     -	Scan barcode and then the barcode attribute will be filled automatically in the search box (To set barcode attribute, go to **How to filter & search products** quickly to know more)
     -	The matching product will be shown in the list.

### How to add products to cart

#### Add products to cart:

-	With simple products, you just need 1 click to add them to cart

-	With configurable, bundle, grouped products, after clicking, you will see a popup shown to choose your option. Then, click on **Add to cart** button.

![Add products to cart window](./Image_Web%20POS/image057.jpg)

#### Edit products in cart

After adding products to cart, you can edit the quantity of each product by clicking on the product that needs editing. A popup will display with edited option for **Qty**.

![Quantity editing popup](./Image_Web%20POS/image059.jpg)

To edit Qty., just enter a wanted number or click on +/-. The number of products will be adjusted in the cart right away.

#### Remove products in cart

To remove products in cart one by one, click on **“x”** button of the corresponding product. After that, the cart will be updated immediately. Or you can click on the waste basket icon to clear cart.

### How to add a custom sale item to cart

#### What is custom sale item and what it is for

Custom sale item is the item that Web POS user creates when checkout. It is used when the product hasn’t been added to the system or Web POS user cannot find it in the product list.

#### How to add Custom Sale to cart

In frontend, click on **Custom Sale** button if you want to add the custom product to cart

![Custom Sale button at bottom right of the page](./Image_Web%20POS/image062.jpg)

A screen will be shown for you to configure this custom product.

![Custom sale configuration window](./Image_Web%20POS/image064.jpg)

-	**Name**: Enter the name of custom product

-	**Price**: Enter the price of this product

-	**None/ Taxable goods**: Choose whether the product is subject to tax or not

-	**Shippable**: Choose whether the product will be shipped or not by turning on/off this option

After finishing configuration, click on **Add to Cart** button and check out as normally.
Please note that this custom sale product will not be saved for the next checkout.

### How to apply a coupon code or a cart discount

After adding products to cart, to apply a coupon code or discount on the whole cart, click on **Add Cart Discount** link.

![apply a coupon code or a cart discount on cart](./Image_Web%20POS/image066.jpg)

Then, a popup will display as below:

![discount popup](./Image_Web%20POS/image068.jpg)

You can choose between using **Discount** or **Promotion**

-	In Discount tab:
      -	Name: Enter a name for this discount as you will easily check it again
     -	Discount Type: Select discount by fixed amount or percentage    
     -	Amount: Fill in discount value as you offer for your customers.

Then, the cart will be updated automatically after you click on **Apply** button.

-	In Promotion tab:

Just fill in available coupon you want to offer for your customers. The cart will be updated automatically after you click on **Apply** button.

![Promotion tab](./Image_Web%20POS/image070.jpg)

### How to apply a custom discount or custom price to a product

After adding products to cart, besides editing the quantity of each product (refer to section **Edit products in cart** for more details), you can click on the product to edit other information. A popup will display with edit option for **Custom Price, Discount**. Remember that you can only change information by Custom Price **OR** Discount, instead of both at once for a product.

![Custom Price OR Discount popup](./Image_Web%20POS/image072.jpg)

-	You can set custom price for products by click on **Custom Price** button. The next popup will be shown as below:

![Custom Price button](./Image_Web%20POS/image074.jpg)

In this popup, please choose type you want to adjust for the price, according to fixed number or percentage.

   •	If you edit fixed price, the price will be changed to the price you have entered.     
   •	If you edit by percentage, the price will be shown by the percent you have entered (it is similar to Discount by percentage)

Then, products in cart will be automatically updated with the price you edit.

![product's price in cart is updated after a custom price is applied](./Image_Web%20POS/image076.jpg)

Editing discount for each product is similar to edit by Custom Price. Click on **Discount** button and choose types of discount–fixed discount or percentage–you want to adjust:

![applying discount](./Image_Web%20POS/image078.jpg)

   •	If you edit discount by fixed number, the price will decrease by the exact value you have entered
   
   •	If you edit by percentage, the price will decrease by the percent you have entered (it is similar to Custom Price by percentage).

Then, the product price will be updated in the cart.

![product's price in cart is updated after a discount is applied](./Image_Web%20POS/image080.jpg)

### How to handle customer information at checkout

#### Customer Checkout

To use Customer Checkout, add customer by clicking on **Customer** icon on the right corner. You will see a screen as below:

![Customer Checkout panel](./Image_Web%20POS/image082.jpg)

-	Search customers:

In the search box, you can quickly find the customer by entering his name, email, phone or address. Choose customer from suggested results in dropdown list.

The information of customer in the system will be auto updated in checkout step. To edit it, please click on name of customer. In the popup, just edit the pieces of information you want to change.

![Customer Info window](./Image_Web%20POS/image084.jpg)

-	Create customer

If customer hasn’t been added in your system before, instead of searching, click on **Create Customer** button.

![Create new customer panel](./Image_Web%20POS/image086.jpg)

Fill enough information of the customer such as **First Name, Last Name, Email, Group, Shipping & Billing Address,** etc. You can choose whether Billing Address is similar to Shipping Address or not. Remember to click on **Save** button to save the customer information for the next checkout.

#### Guest Checkout

When you use Guest Checkout, the default customer that you configure in backend will be used (Please hover to the section **What is default customer & how to configure Default Guest Checkout** to get more details). At checkout, all fields will be auto-filled with that default information.


### How to add comments to an order

#### When you need to add comments

In some special situations, to remember about your order, you can add comment to it so that you will easily check it later. The comments on order are used internally.

#### How to add comments

Click on **Add Order Comment** icon in the top right corner. In the **Order Comment** box, type the content that reminds you of this order. Then, save it.

![Add Order Comment icon](./Image_Web%20POS/image088.jpg)

### How to check order comment

-	In Web POS screen

To view comment of order, you can go to **Orders** tab in Web POS screen, choose an order then scroll down to see Comment History.

![Comment History section in Orders tab](./Image_Web%20POS/image090.jpg)

-	In Magento backend

Go to Sales > Orders > click on a specific order. In order details page, scroll down to **Comment History** tab to check whether it has any notes or not.

![Comment History tab in backend](./Image_Web%20POS/image092.jpg)

### How to process at checkout for a customer

You have been through steps to add products to cart and add customer, let’s move to the checkout process.

-	When products are added to cart, click on **Checkout** button at the end of the cart page
![Checkout button](./Image_Web%20POS/image094.jpg)

You will be redirected to the next page with information of Shipping & Payment Method

![Shipping & Payment Method page](./Image_Web%20POS/image096.jpg)

![edit shipping and payment fields](./Image_Web%20POS/image098.jpg)

-	**Credit Card**: Magestore Web POS supports Authorize.net & Stripe. Sale staff can fill in card information manually or swipe card (if the POS system is connected with a card swiper). For more information about how to connect, please go to section **How to connect Web POS with peripheral devices**.

-	**Split Payment**: For more information about Split Payment, please go to section

### Split Payment with Web POS

-	**2 Custom Payment option**: You can change name of payment option as you desire, for example: change Web POS – Custom Payment 1 into Bank transfer.

After choosing payment method, click on Place Order button to complete checkout process. There will be a notification as is shown below:

![Place Order completed notification](./Image_Web%20POS/image100.jpg)

### Split & Partial Payment with Web POS

**How to make payment via Web POS using multiple methods (split payment)**
You can use more than 1 payment method for split payments when checkout with Web POS. Let me give you an example.

**Customer’s order value is $606.04**

-	Your customer wants to pay $400 in Cash In. Then, you fill in the blank space **Cash In** with the value of $400.
     
![Cash in & Remain money fields](./Image_Web%20POS/image102.jpg)

-	For the remaining ($206.04), your customer wants to pay by Custom payment 1. So, at this time, you click on the **Add Payment** button and choose **Custom payment 1**. The remaining amount ($206.04) will be automatically filled in the box.
<a name="p6"> </a>

![Add another payment](./Image_Web%20POS/image104.jpg)

**_Notes_**:

-	Support multiple payment methods for one order
-	Not require Cash in method as compulsory
-	You can save payment method code to order if you do not use split payment (updated)

**Process part of order payment (partial payment)**

With Web POS, you can also apply partial payment that allows customers to pay part of the order value. For example, your customer wants to reserve the good before it will be launched. His order value is $606.04. He pays $300 as reservation.

-	When processing payment, choose **Cash In** with the value of $300. Then, instead of filling the remained values in other payment methods, you click on button **Mark as partial**.

![Hold order](./Image_Web%20POS/image106.jpg)

-	After finishing creating order, in the next step, when customers come back to pay the rest of order value, you open that order’s details in **Order History** tab.

![Hold order](./Image_Web%20POS/image108.jpg)

-	You can check the total due is $306.04 and the total paid is $300. To complete the order payment, you click on **Take payment** button. Tick to choose the payment option or pay with multiple ones.

![Hold order](./Image_Web%20POS/image110.jpg)
-	After filling in the due amount, click on **Submit** button to complete the payment action. Then the total paid is equal to the whole order’s value.

### How to keep orders on hold for further processing

Your customers can't make up their minds yet, or are unable to make a payment meanwhile? They may want to purchase items that are for pre-order or currently out of stocks? You don't want to lose those potential customers, don't you? Then, Web POS's new feature can put these orders on hold - no limit in time - until they are ready to continue processing!

After adding products to cart, you can choose **Hold** to put the order into **On-hold Orders** section. A **Note for holding order** will appear for inserting any comment that you would like to keep, for example, “Waiting for payment”.

![holding order button](./Image_Web%20POS/image112.jpg)

To check orders that have been put on hold, select **On-hold Orders** section. List of on-hold orders is recorded with certain note for each order. You may select **Continue Processing** whenever customer is willing to take final action for payment or you may **Cancel** it if it is not effective anymore.

![On Hold status on top right of the Order](./Image_Web%20POS/image114.jpg)

### How to print receipt and email order information

You can print receipt or email order information right after creating an order. Remember that you must be online and have permission to do these actions.

![Receipt Printing button](./Image_Web%20POS/image116.jpg)

The receipt will look like the screenshot below:

![receipt preview](./Image_Web%20POS/image118.jpg)

And here is the email of order information:

![email sample of order info](./Image_Web%20POS/image120.jpg)

### How to review orders
<a name="p2"> </a>
In POS screen, you can review orders by choosing **Order History** tab. Here you can see the order list and order details:

![Order History tab](./Image_Web%20POS/image122.jpg)

-	**Order status**: 
In order list, the status of order is distinguished by color
     -	Complete: Green (When you ship order AND create invoice
     -	Processing: Blue (When you  ship order OR create invoice)
     -	Pending: Orange (When you create order successfully but have not shipped order and created invoice)
     -	Canceled: Gray (When you cancel the order)
     -	Not synced: Red (When order’s data has not been synced to the system)
     -	Closed: Black (When order has been refunded)

- **Order searching**

To quickly find an order to review, you can search it by Order ID or Customer’s Name/Email

![Search bar](./Image_Web%20POS/image124.jpg)

-	**View order information**

To view detailed information, click on your wanted order. Please make sure that you have permission to check it. The detailed order will be shown like this

![order information window](./Image_Web%20POS/image126.jpg)

### How to issue invoice for an order

The order can’t be complete if you haven’t issued invoice for customer. After the order is created successfully, you will find order’s details on tab Order History then click on tab **Invoice**.

![Invoice button](./Image_Web%20POS/image130.jpg)

A pop-up will appear so you can enter the quantity of item or the order amount to be invoiced. Then you click on button **Submit invoice** to complete the action. You can choose whether to send invoice to customer’s email or not.

![invoice popup](./Image_Web%20POS/image132.jpg)

**_Note_**: From version 3.0.4, WebPOS module is well integrated with Magestore PDF Invoice module. This helps store owners create invoice much more easily and faster.

### How to create shipment or issue refund for an order

#### How to create shipment

There are two ways to create shipment using Web POS: **before placing an order and when reviewing order**

-	**Before placing order**

Before an order is created by clicking Place Order, you can create shipment by turn it on as below:

![Marked as ship function](./Image_Web%20POS/image134.jpg)

After verifying shipment method, the system will automatically load to Successful Order Page. There will be a message shown to notify you that shipment is created successfully. Please note that to use this way, you need to have permission and be in online mode.

-	**After placing order**

When order has been created successfully but hasn’t been shipped, you can go to Order History and create shipment for that order.

![Ship function in the hamburger menu](./Image_Web%20POS/image136.jpg)

-	**Partial shipment**:

If customers want the orders to be shipped in 2 or more consignments, sales staff can enable Partial Shipment function. When you create order, remember to turn of button “Mark as shipped”.

After placing order successfully, you find that order in Order History. Then you click on the icon on the right corner and choose Ship. A pop-up then appears so you can enter the number of items to be shipped of each product.

**Note**: Only orders that have been synced can be shipped.

![Enter Quantity to ship](./Image_Web%20POS/image138.jpg)

#### How to issue refund

Some certain staffs have permission to issue refund (which is set by admin in backend. See **How to differentiate access permissions of Web POS users** for more details). Customers can get refund in either Store Credits, points or in cash. To enable refund by **Store Credit** and **Reward Points**, these two modules must be installed in your website.

To issue refund, go to Orders tab in POS screen, you choose the order that is required to refund. Click on **Refund** button in the end.

![Refund button in the hamburger menu](./Image_Web%20POS/image143.jpg)

A popup will display so that you can fill in the information before making refund. Tick **Return to stock** if you want to return those items back to your stock.

![Enter quantity to refund](./Image_Web%20POS/image145.jpg)

After that, you will get the message informing that credit memo is created successfully. Please make sure you have permission to issue refund and you are in online mode. 

**Adjustment Refund**: The fee customers might have to pay for your store when requesting refund.

**Adjustment Fee**: The compensation customers get from your store if they have to request refund.

### How to view reports

Magento Web POS provides you 10 types of reports which help you get deeper into your business performance. To view reports, you choose tab Sales/ Report on Magento backend. There will display 10 types of report as on the image below:
<a name="p1"> </a>

![Report panel](./Image_Web%20POS/image147.jpg)

**Note**:

   -	You can export each report into Excel XML or CSV file.
   -	You can view report in any custom time period.

#### Staff Report

On Staff report row, there are 3 types of reports: Sales by staff, Sales by staff (Daily) and Order list for staff. The Sales by staff report shows the number of orders and total sales created by each sale staff in any custom period.

![Sale by staff report](./Image_Web%20POS/image149.jpg)

The Sales by staff (Daily) expresses the number of order and total sales created by each staff each day in the time period that you choose.

![Sales by staff (Daily) report](./Image_Web%20POS/image151.jpg)

In the Order list for sale staff, you can view all order information including ID, value, history and status of each order created by any or each specific sale staff.

![Order list for a staff panel](./Image_Web%20POS/image153.jpg)

#### Location report

Similar to Staff report, the Location report has 3 different reports including Sales by location, Sales by location (Daily) and Order list for location.

The Sales by location report shows the number of orders and sales created in each location, in any custom time period.
![Sales by location report](./Image_Web%20POS/image155.jpg)

The Sales by location (Daily) report shows the number of orders and sales created in each location by each day.

![Sales by location (Daily) report](./Image_Web%20POS/image157.jpg)

In the Order list for location, you can view all order information including ID, value, history and status of each order created by all or each specific sale location.
![Order list for location report](./Image_Web%20POS/image159.jpg)

#### Payment Report

The section of Payment Report has 4 different types of report including Sales by payment method, Sales by payment method (Daily), Order list for payment method and Sales by payment method for location.

The Sales by payment method displays the number of orders and sales paid by each payment method in a custom time period.
![Sales by payment method report](./Image_Web%20POS/image161.jpg)

The Sales by payment (Daily) report shows the number of orders and sales created by each payment method by each day.

![Sales by payment (Daily) report](./Image_Web%20POS/image163.jpg)

In the Order list for payment method, you can view all order information including ID, value, history and status of each order created by all or each specific payment method.

![Order list for payment method panel](./Image_Web%20POS/image165.jpg)

The Sales by payment method for location displays the number of orders and sales created by each payment in each sale location.

![Sales by payment method for location panel](./Image_Web%20POS/image167.jpg)

### How to manage cash drawer


#### Manage cash flow into cash drawer

To manage cash drawer, you go to tab Cash Drawer on Web POS checkout screen.

As you see on the below image, there is a list of orders paid in cash on the left screen (cash transactions). The total value of cash transactions equals to the balance in cash drawers. The amounts paid with other payment methods are displayed on Sales by Payments section.

![Cash Drawer tab](./Image_Web%20POS/image169.jpg)

You have frequent cash in/out beside normal order transactions like paying electrical bills, balancing cash amount in hand, etc? Web POS system records deposits and withdrawals from your cash drawer then compare them with actual cash amount (counted in notes) after each cashier’s shift.

![Cash in/Cash out buttons](./Image_Web%20POS/image171.jpg)

When your cashier’s shift ends, you count the cash amount on cash drawers and compared with the one recorded by the system. You can also record the amount of cash left for the next shift and add some notes.

![Enter Cash counted/ Cash left fields](./Image_Web%20POS/image173.jpg)


#### Z-report

Z-report shows the cash drawer balance in a certain time like a shift or a working day. All payment methods will be listed down with the record of Grand Total in details respectively. If there is no customer use Cash on Delivery method to purchase orders, it will not appear in the Payment Method section.

![Z-report](./Image_Web%20POS/image175.jpg)

The Z-report will be refreshed to serve new shift/working day after you select Close Store. Particularly, your cash drawer will be reset to 0 or to the certain amount that you set up in Cash Left. Each Z-report is automatically saved in Magento backend so you can check it back (go to Sales > Web POS > Web POS Z-report)

---------------
## Release Note 
### Version 3.1.0 (released on Oct 5th, 2017)

### Version 3.0.5 (released on Jun 20th, 2017)
Integrate with Pay.nl payment

<a href="#p7">Allow to sync orders from Webpos by manual</a>

Add more labels to translation file

### Version 3.0.4 (updated on May 23th, 2017)

<a href="#p6">Save payment method code to Order when do not use split payment</a>

<a href="#p5">Provide more custom shipping method</a>

### Version 3.0.3 (updated on Apr 28th, 2017)
Hide Reward point, gift card discount field when checkout without using point or gift card

<a href="#p3">Always show view product information icon in tablet</a>

Reload order list & order detail after finished an action (cancel, ship, refund, invoice & take payment)

Integration with module Aitoc_Aitoptionstemplate

Display order creation date by timezone of current Store view

### Version 3.0.2 (updated on Apr 13th, 2017)

Add missing translation labels in .html file

### Version 3.0.1 (updated on Mar 20th, 2017)

<a href="#p4">Do not show disabled categories in Webpos</a>

Optimize product image size in Webpos

### Version 3.0.0 (updated on January 23, 2017)
Save & store data in IndexedDB browser

Being updated with new design & interface

<a href="#p3">Quick view product description</a>

Support partial payment - pay part of the order value & pay the due amount later

Enable partial shipment - ship in 1, 2 or more consignments

Being compatible with customer pole display 

<a href="#p1">Show sales reports by staff, sales location or by payment method</a>

### Version 2.3.2 (updated on April 22, 2016)

New API key to connect with Retailer POS app for iOS

<a href="#p2">View customers’ order history</a>

Enable reload orders: add to cart items from an old order

<a href="#p1">View sales report from Web POS screen</a>

----------
**_Confidential Information Notice_**

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
