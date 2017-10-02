
# USER GUIDE FOR IT ADMIN
-----

*Confidential Information Notice.* 

***Copyright 2017**. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.* 

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

---------


### 3.Web POS


#### 3.1.Default Guest Checkout


Path: **Sale > Web POS** section > **Setting > Default Guest Checkout**

Default customer is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically.

![](./img102/it_img021.png?raw=true)
	
Fill in all information as you want to use as default, including **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**. After finishing, click on **Save Config** button to save your work.


#### 3.2.	How Web POS works with peripheral devices


MageStore Web POS module can connect with Barcode readers, Card swiper & Receipt printers. 

1)	**Barcode readers:** are any devices that can connect with iPad/Laptop/PC (including USB Port, Wifi or Bluetooth). The scanner can read barcodes & fill encoded information into Web POS search box.

2)	**Card swiper:** only devices connected through USB port (supports Authorize.Net & Stripe).

3)	**Receipt printers:** any devices that connect with iPad/laptop/PC

### 4.	Loyalty program


#### 4.1.	Catalog Price Rule


Path: **Marketing > Promotions** Section **> Catalog Price Rule**


##### 4.1.1.	Manage Catalog Price Rule

![](./img102/it_img022.png?raw=true)

(1)	Click Add New Rule to create a new catalog price rules.

(2)	Fill out the blank with a value to search, after click Search.

(3)	Search catalog price rules information with keyword. View or edit a rule’s detail by clicking on each line.

##### 4.1.2.	Type of Pricing Rule

| Type of pricing rule | Description|
| ---| ---|
| Apply as percentage of original | Discount item by subtracting a percentage from the original price|
| Apply as fixed amount | Discounts item by subtracting a fixed amount from original price. |
|Adjust final price to this percentage| Discount item by defining the final price based on percentage.| Adjust final price to discount value | Sets the price to a fixed amount.


##### 4.1.3.	Create a new Catalog Price Rule

![](./img102/it_img023.png?raw=true)

Click on **Add New Rule**

![](./img102/it_img024.png?raw=true)

**Rule Information**

(1)	Fill in the **Rule Name** *(required)*

(2)	Fill in **description of the rule**

(3)	Select **Active**

(4)	Select **websites** where the rule is to be applied

(5)	Select **Customer Groups** to which rules are applied. 

(6)	Set the **From** and **To** date range for the promotion.

(7)	Choose **Priority** (a number that indicates the priority of this rule in relation to others. The highest priority is number 1)

![](./img102/it_img025.png?raw=true)

**Conditions**
Click the small green button to add conditions.

![](./img102/it_img026.png?raw=true)

**Action**

-	Select type of pricing rule what you want.
-	Enter the **Discount Amount** to apply.
-	Set **Yes** to stop processing other rules. This prevents customers from receiving multiple discounts for the same product. 
To finish, click **Save**

#### 4.2.	Cart Price Rule

***Note: Cart price rules** apply discounts to items in the shopping cart, based on a set of conditions. When applied, the discount appears in the cart under the subtotal. A cart price rule can be used as needed for a season or promotion by changing its status and date range.*

##### 4.2.1.	Manage Cart Price Rule

Path: **Marketing > Promotion** section **> Cart Price Rule**

![](./img102/it_img027.png?raw=true)

(1)	Click **Add New User** to create a new cart price rules.

(2)	Fill in the blank with a value to search, after click **Search**.

(3)	**Search** cart price rules information with keyword. View or edit a rule’s detail by clicking on each line.


##### 4.2.2.	Type of Account

| Type of pricing rule | Description|
| ---| ---|
| Percent of product price discount| Discounts item by subtracting a percentage from the original price. The discount applies to each qualifying item in the cart. For example: Enter 10 in Discount Amount for an updated price that is 10% less than the original price.|
|Fixed amount discount| Discounts item by subtracting a fixed amount from original price. The discount applies to each qualifying item in the cart. For example: Enter 10 in Discount Amount for an updated price that is $10 less than the original price.|
|Fixed amount discount for whole cart|Discount the entire cart by subtracting a percentage from the cart total. For example: Enter 10 in Discount Amount to subtract 10% from the cart total.|
|Buy X get Y free|Defines a quantity that the customer must purchase to receive a quantity for free (The Discount Amount is Y)


##### 4.2.3.	Create a Cart Price Rule

![](./img102/it_img028.png?raw=true)

Click **Add New Rule** to create a new Cart Price Rule

![](./img102/it_img029.png?raw=true)

**Add a New Rule**

(1)	Enter a **rule name** 

(2)	Enter the **description**

(3)	If you do not want the rule to go into effect immediately, set **Active** to **No**.

(4)	Select the **websites** where the promotion is to be available.

(5)	Select **customer groups** to which the promotion applies. For the promotion to be available only to registered customers, do not select the **NOT LOGGED IN** option.

(6)	To associate a coupon with the price rule, set Coupon to **Specific Coupon**. Then, do the following:

![](./img102/it_img030.png?raw=true)

(7)	Enter a numeric **Coupon Code** that the customer must enter to receive the discount.

(8)	Limit the number of times the **coupon code** can be used. If there is no limit, leave the field blank.

(9)	Limit the number of times the coupon code can be used by the same registered customer who belongs to any of the selected customer groups. The setting does not apply to guest shoppers who are members of the *NOT LOGGED IN* customer group, or to customers who shop without logging in to their accounts. If there is no limit, leave the field blank.

(10)	 Set the **From** and **To** date range for the promotion.

(11)	Enter a number to determine the **Priority** of this price rule in relation to the Action settings of other price rules that might be active at the same time. (Number 1 has the highest priority.)

(12)	To apply the rule to published listings in RSS feeds, set Public In RSS Feed to **Yes**.

![](./img102/it_img031.png?raw=true)

**Conditions**

Click  the small green button to add conditions.


<<img32>>

**Define the Actions**

The shopping cart price rule actions describe how prices are updated when the conditions are met.

(1)	**Apply:** Select one of the following discount options:
•	Percent of product.
•	Fixed amount discount.
•	Fixed amount discount for whole cart.
•	Buy X get Y free.

(2)	**Discount Amount:** Based on the discount option selected, the number might indicate a percentage, a fixed amount or a quantity of items.

(3)	**Maximum Qty. Discount is Applied:** Enter the maximum quantity of the same product that can qualify for the discount in the same purchase.

(4)	**Discount Qty. Step (Buy X):** For a **Buy X get Y Free** discount, enter a quantity that the customer must purchase to receive the discount.
5)	**Apply to Shipping Amount**: If you choose **Yes** - Applies the discount amount to the subtotal and shopping amounts separately. Vice versa, applies the discount amount only to the subtotal.

(6)	**Discard Subsequent Rules:** Stop processing other rules after this rule is applied.

(7)	**Free Shipping:**

•	Choose **No**: free shipping is not available.

•	Choose **For matching items only**, then free shipping is available only for items that match the conditions of rule.

•	Choose **For shipment with matching items**, then free shipping is available for any shipment that includes matching item(s).

(8)	Define as many additional conditions as needed for the action. When complete, click **Save and Continue Edit.**

![](./img102/it_img033.png?raw=true)

**The labels**

The label appears on the order below the subtotal to identify the discount. You can enter a default label for all store views, or enter a different label for each view.

(1)	**Default Rule Label for All Store Views:** this label will appear on the order below the subtotal.

(2)	**Default Store View:** If your store has multiple views, or multiple websites with multiple view, enter the appropriate label text for each.


##### 4.2.4.	Create a Specific Coupon

![](./img102/it_img034.png?raw=true)

Follow the instructions to **Create a Cart Price Rule**.

On the **General Information** page, set Coupon to **Specific Coupon.**

(1)	Enter a **Coupon Code** to be used with the promotion. 

(2)	Limit the number of times the coupon can be used. For unlimited use, leave these fields blank.

(3)	Limit the number of times the coupon can be used by same customer.

(4)	Use **Calendar** to set the **From** and **To** date range for the promotion. If you leave the date range empty, the rule will never expire.

Click **Save** to finish.

##### 4.2.5.	Generate a Batch of Coupons

![](./img102/it_img035.png?raw=true)

Under **Coupon** tab, mark the **Use Auto Generation** checkbox. 

To limit the number of times each customer can use the coupon, enter the number of **Uses per Customer**. To limit the number of times a person uses per coupon, enter the number of **Uses per Coupon**

![](./img102/it_img036.png?raw=true)

Scroll down  and expand the Manage Coupon Codes section. 

Then, 

(1)	Enter the number of coupons that you want to generate. ***(required)***

(2)	**Code Length**: Not including the prefix, suffix, or separators. ***(required)***

(3)	Select the Code Format

•	Alphanumeric

•	Alphabetical

•	Numeric

(4)	Enter **Code prefix** which can be added to the beginning of the code.

(5)	Enter **Code suffix** which can be added to the end of the code.

(6)	Enter the number of characters, between each dash. For example, if the code is twelve characters long, and there is a dash every four characters, it will look like this: xxxx-xxxx-xxxx.

![](./img102/it_img037.png?raw=true)

When complete, click **Generate**. The list of generated codes appears below it.


#### 4.3.	Free Gift Promotions (Coming soon)

#### 4.4.	Gift Card


##### 4.4.1.	Setting


Path: **Marketing > Gift Card** section **> Settings**

To configure default configurations and settings of the module, please log in to backend screen, and then do the following stages as below: 

![](./img102/it_img038.png?raw=true)

**GENERAL**

**Gift code**

(1)	Select **Yes** in the dropdown list to **enable Gift Card**

(2)	Configure the **pattern** to auto-generate gift codes for Gift Card products when customers purchase in WebPOS frontend

(3)	Enter the number of **prefix characters** which are shown in a voucher code

(4)	Enter one **letter to replace hidden characters**

![](./img102/it_img039.png?raw=true)

**Gift Card Usage**

(1)	Enter the term of validity that Gift Cards can be used after being activated.

(2)	Enter the **maximum time(s)** that allows users to enter gift code incorrectly.

(3)	Enter the **maximum number of users per gift code**.

(4)	Select **Yes** to allow customer to apply gift card for shipping fee

(5)	Select **Yes** to allow customers to use both Gift Card codes and Coupon codes at once. 

(6)	 Select **Yes** to allow customers to check status of Gift Cards after entering Gift Codes, and vice versa.

(7)	Select **Yes** to show the expiration date of Gift Cards on website, and vice versa.


![](./img102/it_img040.png?raw=true)

**Tax Configuration**

(1)	Select:

•	**After Tax:** to allow applying Gift Card after the tax is applied

•	**Before Tax:**  to allow applying Gift Card w/o tax

![](./img102/it_img041.png?raw=true)

**ON PRODUCT PAGE**

**Gift Card Value**

(1)	Enter the default gift card value *(follow the below instruction)*

(2)	Enter the description of gift card value *(follow the below instruction)*

![](./img102/it_img042.png?raw=true)

**Gift Card Template**

-	Select **Yes** to allow customers to change the image inserted in the template

-	Limit the maximum size of images uploaded by customers to 500KB

**Gift Card Shipping Information**
-	Select **Yes**: Gift card can be sent through the post office

-	Choose **5** means that after Customers order Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within 5 days

-	Limit the maximum length of a custom message on Gift Card. Select **Yes** to allow users to schedule gift card delivery date.


![](./img102/it_img043.png?raw=true)

**ON SHOPPING CART PAGE**

(1)	Select **Yes** to Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.

(2)	Select the data to display on shopping cart page

(3)	Select **Yes** to allow showing Gift Card printout preview as product image on shopping cart page

![](./img102/it_img044.png?raw=true)

**ON CHECKOUT PAGE**

Select **Yes** to show Gift Card box on the checkout page

![](./img102/it_img045.png?raw=true)

**EMAIL NOTIFICATION**
 
**General**

(1)	Select **Yes** to allow sending notification emails to customers and recipients

(2)	Select **Active**, only a gift card which is activated can be sent to a friend

(3)	Set the default sender of notification emails as General Contact 

(4)	Select **Yes** to allow sending a copy of gift card via email if customers choose to ship through post office.

![](./img102/it_img046.png?raw=true)

**Notification email sent to purchasers**

(1)	Select the email template **sent to purchasers after buying Gift Card** successfully. 

(2)	Select the email template **sent to purchasers when recipients receive Gift Cards.** 

**Notification email sent to recipient**

(3)	Select **Yes** to allow email notification being sent to recipient when sender refunds Gift Card.

(4)	Select the email template **sent to the gift card’s recipient.** 

(5)	Choose the email template **sent to recipient when gift card is refunded.** 

(6)	Enable auto reminder email **sent to Customers before Gift card expires** 

(7)	Enter the **number of days** to **send notification to customers before the expiration date of a Gift card.** 

![](./img102/it_img047.png?raw=true)

**GIFT CARD PRINTOUT**

Click **Choose File** to upload an image used as a logo when Gift Cards are printed or sent via email. 

##### 4.4.2.	Manage Gift Card Templates

**-	Add new template**

Path: **Marketing > Gift Card** section **> Manage Gift Card Templates**

![](./img102/it_img048.png?raw=true)

(1)	Click **Add New Template**

![](./img102/it_img049.png?raw=true)

*On the popup screen*

(1)	Enter the template’s **name**

(2)	Choose a **design pattern** in dropdown list *(optional)*

(3)	Enter notes or description about the gift card template *(if any)*

(4)	Choose **text color**

(5)	Choose **link/ special text color**

![](./img102/it_img050.png?raw=true)

(6)	Upload a **background image**. 

(7)	Click **Save and Continue** or **Save**

**-	Preview Existing Template**

Path: **Marketing > Gift Card** section > **Manage Gift Card Templates**

![](./img102/it_img051.png?raw=true)

Click **Preview** to see the gift card template

**-	Edit and Delete Existing Template**

Path: **Marketing > Gift Card** section **> Manage Gift Card Templates**

![](./img102/it_img052.png?raw=true)

(1)	Mark the template checkbox

(2)	Tab the action label, select **Delete** to remove templates. 

(3)	Click **Edit** to update templates data

![](./img102/it_img053.png?raw=true)

*On the popup screen*

(4)	Edit templates data

(5)	Click **Save** to finish

(6)	*Additional guidance:* Click **Delete** to remove template

##### 4.4.3.	Generate Gift Code

Path: **Marketing > Gift Card** section **> Generate Gift Code**

![](./img102/it_img054.png?raw=true)

(1) Click on **Add Gift Code Pattern** to create new pattern code

![](./img102/it_img055.png?raw=true)

![](./img102/it_img056.png?raw=true)

*On the popup screen*

(2)	Enter the pattern name

(3)	Follow the example mentioned below and set a format for the gift code  

(4)	Enter the Gift code value

(5)	Select a currency

(6)	Select an expiration date

(7)	Select a gift card template

(8)	Enter the quantity of gift code issued

(9)	Select store views

(10)	Click on:

•	**Save and Generate** to save and generate the gift code at the same time

•	**Save** to finish

![](./img102/it_img057.png?raw=true)

A status ***The pattern has been generated successfully*** would be shown on the pop-up screen

![](./img102/it_img058.png?raw=true)

A list a generated Gift Codes would be shown at the bottom of the pop-up screen

##### 4.4.4.	Manage Gift Codes

**1/	Create a new Gift Code**

Path: **Marketing > Gift Card** section **> Manage Gift Code**

![](./img102/it_img059.png?raw=true)

(1)	Click on **Add Gift Code** to create a new gift code

Moreover, click on I**mport Gift Codes** to import data from your device to the system.

![](./img102/it_img060.png?raw=true)

![](./img102/it_img061.png?raw=true)

*On the popup screen:*

(2)	Follow the example mentioned under the tab to set a format for the gift code  

(3)	Enter the **Gift code value**

(4)	Select a **currency**

(5)	Select a **gift code template**

(6)	Select **Active** to enable/ activate the gift code

(7)	Select an **expiration date**

(8)	Select **store views**

(9)	Write a comment *(optional)*

![](./img102/it_img063.png?raw=true)

![](./img102/it_img064.png?raw=true)

*Scroll down, on the **Message Information** tab, click  to expand:*

(1)	Enter the **sender nam**e and **email**

(2)	Enter the **recipient name** and **email**

(3)	Enter the **Recipient Address**

(4)	Enter the **message to the recipient**


![](./img102/it_img065.png?raw=true)

*Finally, scroll up, tab the arrow on the right hand-side of **Save** button:* 

(1)	Select **Save & Send Email** to save and send Gift Codes via emails to both sender and recipient

(2)	Select **Save & Continue Edit** to finish.

**2/	Manage Gift Card History per customer**

Path: **Customers > All Customers**

![](./img102/it_img066.png?raw=true)

(1)	Click **Edit** to view an existing customer’s detailed information 

![](./img102/it_img067.png?raw=true)

*On the popup screen:*

(2)	Click on **Gift Card History** tab to view all transactions in which gift cards were applied

##### 4.4.5.	Apply Gift code when create new order

Path: **Customers > All Customers**

On **Create New Order** page, after selecting a customer and adding a product to an order, the system will show the Gift Card box, which allowing you to use Gift Card credit balance or Gift Card code(s) of the Customer to pay for this order. Select the method(s) as you want and then remember to click on **Apply Gift Card** button. 

![](./img102/it_img068.png?raw=true)

(1)	Mark the check box to use gift card to checkout

(2)	Enter the **Gift card code**

(3)	Click on the arrow to apply the gift code

![](./img102/it_img069.png?raw=true)

Scroll down to view **Order Totals** label, then click on (4)** Submit Order** to finish.


##### 4.4.6.	Refund Orders

Path: **Sales > Operations**  section **> Orders**

![](./img102/it_img070.png?raw=true)

(1)	On the dashboard screen of admin, click **Sales > Orders**

![](./img102/it_img071.png?raw=true)

(2)	Click **View**

![](./img102/it_img072.png?raw=true)

(3)	On the **Order View** tab, click on **Credit Memos** to refund

![](./img102/it_img073.png?raw=true)

(4)	Enter the number of money to refund to gift credit 

(5)	Click on **Refund Offline** to finish.

##### 4.4.7.	History

Path: **Marketing > Gift Card** section **> Gift Code History**

![](./img102/it_img074.png?raw=true)

On **Gift Card History** page, you will know when Gift Cards were created/ updated/ redeemed/ spent/ refunded and by whom as well as their values and status. 

You can filter data with the above criteria to get more accurate reports. Information can be exported to .CSV or .XML files for your convenience. 

#### 4.5.	Reward Point

##### 4.5.1.	Add new rate

![](./img102/it_img075.png?raw=true)

(1)	Click on **Reward Points**
(2)	Click on **Spending rates** 
(3)	Click on **Add new spending rate**

![](./img102/it_img076.png?raw=true)

Fill all the data needed in the boxes

![](./img102/it_img077.png?raw=true)

Click on **Save spending rate** after finishing filling in all the boxes

![](./img102/it_img078.png?raw=true)

The new earning rate will be shown as the beside image

##### 4.5.2.	Edit existing rate 

Path: **Reward Point > Spending** section **> Spending Rates**

![](./img102/it_img079.png?raw=true)

Click on **Edit** on action column of the rate needed to be edited

![](./img102/it_img080.png?raw=true)

Edit the rate, then click **Save** spending rate, or **Delete** it

##### 4.5.3.	Manage transaction

Path: **Reward points > Transactions** 

![](./img102/it_img081.png?raw=true)

Click on **Add new transaction** to add new transaction

![](./img102/it_img082.png?raw=true)

Fill in the required information and click on **Save**

##### 4.5.4.	Manage point balances of customers

Path: **Customers > All customers**

![](./img102/it_img083.png?raw=true)

Click on **Edit** of the customer needed to be managed

![](./img102/it_img084.png?raw=true)

Click on reward points to manage the customer’s balance by filling the change balance, change title, points expire on box.

Also, update points subscription and expire transaction subscription can be configured in reward points

Click on **Save customer** to save the changes

![](./img102/it_img085.png?raw=true)

All transactions of a customer are also listed in reward points


##### 4.5.5.	Change point balance

Path: **Reward points > Manage points balances**

There are two ways to change the point balance of a customer. 	

The first way is to enter the **Change Balance** in the **Reward Points** session as mentioned above.

The second way to change points, which can be done to many customers at the same time, is illustrated below:

![](./img102/it_img086.png?raw=true)

A list of customers will be shown with point balance column

![](./img102/it_img087.png?raw=true)

Click on **Import** to import from computer

![](./img102/it_img088.png?raw=true)

(1)	Click on **Choose file** to upload file

(2)	Click on **Import** to import it

![](./img102/it_img089.png?raw=true)

The list of customers in **Reward Point Balances** Information page can also be exported by clicking on **Export**


##### 4.5.6.	Create an Order

Path: **Sales > Orders**

![](./img102/it_img090.png?raw=true)

(1)	Click on **Sales**
(2)	Choose **Orders**
(3)	Click on **Create new order**

![](./img102/it_img091.png?raw=true)

Select customer from the list

![](./img102/it_img092.png?raw=true)

Click on **Add products** to add products to the order

![](./img102/it_img093.png?raw=true)

Click on the product and enter the quantity, then click on **add selected product(s) to order**

![](./img102/it_img094.png?raw=true)

Set the number of point customer will use in the order in the use customer reward points

![](./img102/it_img095.png?raw=true)

Fill in the required fields, click on submit order to finish creating new order

##### 4.5.7.	Refund Orders

Path: **Sales > Operations** section **> Orders** 

![](./img102/it_img096.png?raw=true)

(1)	Click on **View** to see the details of an order 

![](./img102/it_img097.png?raw=true)

(2) On the top bar, click on **Credit Memo** label to create a refund order 

![](./img102/it_img098.png?raw=true)

*On the pop-up screen named **New Memo**, scroll down, then:*

(3)	Enter the earned points that will be refunded to customer’s balance

(4)	Click on **Refund Online** to finish

![](./img102/it_img099.png?raw=true)

*After the credit memo has been created:*

(5)	Click on **Credit Memo** tab on the left hand-side to view credit memos data

#### 4.6.	Store Credit

##### 4.6.1.	 Manage Customers Using Credit

Path: **Store Credit > Manage Customers Using Credit**

![](./img102/it_img100.png?raw=true)

Then the **Customers Using Credit Manager** page will be displayed as below:

![](./img102/it_img101.png?raw=true)

This page shows a list of all Customers using credit and their information such as name, email, credit balance, telephone, etc.

To view more details about a Customer, you can click on the **Edit** link in the **Action** column.

Then, you will be navigated to the **Customer Information** page. By selecting **Store Credit** tab, you can view all Customer’s transaction history and credit balance:

![](./imgpart2/it_img102.png?raw=true)

Besides, you can change the Customer’s credit balance by entering an integer (a positive or negative number) and a comment in text fields as below:

![](./imgpart2/it_img103.png?raw=true)

The module will automatically send email to Customer to announce about this transaction if you tick on **Send email to customer** checkbox. The email will be sent to the customer as bellow: 

![](./imgpart2/it_img104.png?raw=true)


After you save, our module will auto update the Customer’s credit balance, send an email to that Customer and create a transaction as follows:

![](./imgpart2/it_img105.png?raw=true)


##### 4.6.2.	 Manage Credit Products

Path: **Store Credit > Manage Credit Products**

![](./imgpart2/it_img106.png?raw=true)

Then the **Credit Product Manager** page will be shown:

![](./imgpart2/it_img107.png?raw=true)

This page shows you all credit products with a lot of information such as **product ID, name, SKU, quantity, status,** etc.

To add a new credit product, you can click on the **Add Credit Product** button on the right top of the page.

You can add a credit product just in a similar way to adding a normal product. You should pay attention to these following tabs:

a)	**Prices** Tab:

![](./imgpart2/it_img108.png?raw=true)

In this tab, you can configure the value of the credit product. There are three types of credit products including **fixed value, range of values and drop-down value.**

b)	**Setting** Section:

![](./imgpart2/it_img109.png?raw=true)

(1)	**Enable Product:** activate the Store Credit 

![](./imgpart2/it_img110.png?raw=true)

(2)	**Attribute Set:** select default or any attributes available to purchase by Store Credit

(3)	**Product name:** enter the name 

(4)	**SKU:** enter the SKU of your store credit

(5)	**Quantity:** enter the number of store credit cards you can give *(optional)*

(6)	**Stock Status:** select the current availability of the Store Credit

![](./imgpart2/it_img111.png?raw=true)

(7)	**Categories:** select the categories that you sell this Store Credit. In case, you do not have fitted category. Click on **New Category**

![](./imgpart2/it_img112.png?raw=true)

(8)	**Visibility:** choose where it will be visible to customers

(9)	**Set product as new from:** choose active date of the Store Credit

(10)	**Visible on Web POS:** activate the Store Credit on the Web POS

c)	**Advanced Inventory**

Path: **New Product > Quantity > Advanced Inventory**

![](./imgpart2/it_img113.png?raw=true)

![](./imgpart2/it_img114.png?raw=true)

(1)	**Manage Stock:** our module sets up the field as **Yes**. It means that you need to manage the Qty.. of Credit Products. You can edit it by uncheck box **Use Config Settings.**

(2)	**Qty.:** it is synchronized with the **Qty.** on **New Product** Section

(3)	**Out-of-stock Threshold:** our module sets up the field as **0**. It means the product will be notified **Out-of-stock** when the number of items is **0**. You can edit it by uncheck box **Use Config Settings**

(4)	**Minimum Qty. Allowed in Shopping Cart:** our modules set up the field as **1**. It means a customer must have at least 1 product in a single order to purchase Store Credit Product. You can edit it by non- checking box **Use Config Setting**s.

(5)	**Maximum Qty. Allowed in Shopping Cart:** as mentioned in No.4

![](./imgpart2/it_img115.png?raw=true)

(6)	**Qty. Uses Decimals:** select **No** if the Qty. is not a decimal value

(7)	**Allow Multiple Boxes for Shipping:** select **NO** if the Qty. purchased CAN NOT be shipping in separate boxed

(8)	**Backorders:** **Backorder** means funds are still authorized or captured immediately when the order is placed, regardless of whether the product is in stock. Product will be shipped as they become available
•	**No backorders:** Do not accept backorders when product is out stock
•	**Allow Qty. below 0:** Accept backorders when the Qty. falls below zero
•	**Allow Qty. below 0 and notify customer:** accept backorders when the Qty. falls below zero, but notifies customers that orders can still be placed

(9)	**Use Deferred Stock Updated**

(10)	**Notify for Qty. below:** determine the stock level at which the system will notify the inventory is below the threshold

(11)	**Enable Qty. Increments:** select if the product can be sold in quantity increments (**Qty. increments** –the number of products that must be purchased at the same time)

(12)	**Stock Status:** it is synchronized with the **Qty.** on **New Product Section**


Besides the **Credit Product Manager** page, you can also create a new credit product by clicking on **Products > Inventory** Section **> Catalog**

![](./imgpart2/it_img116.png?raw=true)

##### 4.6.3.	Manage Credit Transactions and Report Charts

**a) Credit Transactions**

Path: **Store Credit > Credit Transactions** Section **> Manage Credit Transactions**

![](./imgpart2/it_img117.png?raw=true)

Then the **Credit Transactions** page will be shown: 

![](./imgpart2/it_img118.png?raw=true)

This page shows all credit-related transactions with a lot of information such as **type, detail, customer name/email, added/deducted credit, credit balance** after transaction.

You can search any transaction by using filter boxes in each column.

If you click on a Customer’s email, you will be navigated to the **Customer Information** page.

b) **Credit Report Charts**

Path: **Store Credit > Credit Transactions** Section **> Customer Credit Report**

![](./imgpart2/it_img119.png?raw=true)

Then the **Report Charts** page will be shown as follows:

![](./imgpart2/it_img120.png?raw=true)

This page can be divided into two main sections including **Life-time Reports** and **Period-of-time Report Charts.**

•	**Life-time Reports:** There are 2 types of reports.

-	***Customer Credit Statistics*** *with the total credit, the total spent credit and the number of Customers with credit in your system.*

-	***Top 5 Customers with The Greatest Credit Balances** with their names and current balances in your system.*

•	**Period-of-time Report Charts:** This chart shows you the total spent credit and received credit of all Customers per day in your chosen time range such as **last 24 hours, last 7 days, current month,** etc.


##### 4.6.4.	Using Credit to checkout in backend:

Path: **Sales > Operations** Section **> Orders >** enter numbers on **Customer Credit** tab

On the **Create Order** page on backend, our module allows you to use credit when creating orders for Customers.

![](./imgpart2/it_img121.png?raw=true)

You just need to enter a credit amount and click on the **Gray Arrow** button. Our module will auto-update and calculate the grand total of the order.

![](./imgpart2/it_img122.png?raw=true)

After submitting the order, the Customer’s credit balance will also auto update and you can check the transaction on the **Credit Transaction** page.

![](./imgpart2/it_img123.png?raw=true)

##### 4.6.5.	 Refund Orders into Credit Balance

When Customers want to refund an order, our module allows you to transfer the order value to his credit balance. In that way, Customers can use the credit for future purchases and you do not have to lose money for the refund at the same time.

After clicking on the **Credit Memo** button, our module shows a text field for you to enter the amount you want to refund into credit:

![](./imgpart2/it_img124.png?raw=true)

After that, when you click on the **Refund Offline** button, the amount you entered as well as the credit that the Customer used for paying for the order will be refunded to his current credit balance. 

For any order that includes only Credit Product, the option **Refund Order to Credit** is not available.

Once the refund is finished, you can check the transaction on the **Manage Transaction** page:

![](./imgpart2/it_img125.png?raw=true)


##### 4.6.6.	Settings

Path: **Store Credit > Settings**

![](./imgpart2/it_img126.png?raw=true)

a)	**General Configuration** Tab:

Path: **Magento Extension > Store Credit**

![](./imgpart2/it_img127.png?raw=true)

(1)	**Enable Store Credit:** to activate Store Credit on your site

(2)	**Allow sending Credit:** allow customers to send credit to their friends

(3)	**Groups can use edit:** allow only general/wholesaler/retailer or all customers able to use credits

b)	**Spend Credit On** Tab

![](./imgpart2/it_img128.png?raw=true)

(1)	**Apply Customer Credit:** If you choose **After tax**, it means the Customer Credit Discount will be applied to order value including tax

(2)	**Shipping fee:** If you choose **No**, credit balance cannot be used to pay for Shipping Fee

c)	**Email Configuration** Tab:

![](./imgpart2/it_img129.png?raw=true)

(1)	**Email template with credit code sent to recipients:** default

(2)	**Email template with verification code sent to credit sender:** default

(3)	**Email template notifying customers:** default

(4)	**Send-to-customer email template when recipient receives credit:** default

d)	**Adjust time for Customer credit reports on total used and total received credit** Tab:

![](./imgpart2/it_img130.png?raw=true)

(1)	**Select start time for current year:** choose Month, then Date

(2)	**Select date for current month:** choose Date

e)	**Style configuration** tab: on this tab, you will be able to change background and color of Title

![](./imgpart2/it_img131.png?raw=true)

(1)	**Background of Title:** enter Hexadecimal code

(2)	**Color of Title:** enter Hexadecimal code

#### 4.7.	Wallet (Coming Soon)


#### 4.8.	Membership (Coming Soon)



