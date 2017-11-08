
# IT CONFIGURATION - USER GUIDE FOR MAGENTO 2

---------

## INTRODUCTION

This guide will help you – an IT Manager – to configure a successful and strong system for the retailers and support you to activate the most suitable features for the business. Through the guide, you will understand work with modules included in Magestore's [Omnichannel Solution](https://www.magestore.com/omnichannel-retail). Moreover, you will get basic knowledge about how you can decentralize roles, users and staffs for your company.

------
## HOW TO INSTALL

[How to install](./img102/it_img031.png?raw=true)



### Generate License Certificate


After purchasing an module, you will receive an email that includes the link to access **My License Certificates** on Magestore website.

![generate license certificate](./img102/it_img001.png?raw=true)

If you don’t receive the email, you can directly log in to your account dashboard at Magestore then go to **My Account/My License Certificates**.

![generate license certificate](./img102/it_img002.png?raw=true)

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



### Download Solution Package


Go to **My Downloadable Products**. Click on the version of that you want to install to download it. The file that you download is normally a zip file.

Here you also can find related documents, such as user guide.

![Download Solution Package](./img102/it_img003.png?raw=true)



### Install the Package Downloaded


If you are new to Magento 2, you probably need a little help to get started before installing an module:

1)	Is the Magento software installed already?

2)	What’s a terminal, command prompt, or Secure Shell (ssh)?

3)	Where’s my Magento server and how do I access it?

Notice that,we take *Growth Plus* as the example

**Step 1: Verify your prerequisites**

Use the following table to verify you have the correct prerequisites to install the Magento software.

| Prerequisite | How to check | For more information|
| --- | ----| ----|
|Magento version Starter Edition| Go to admin page, you can see version of Magento 2 at left bottom page|Download Magento version Growth Plus|

**Step 2: Install and verify the installation**

Unzip the module package downloaded. When you have completed, you will have a folder named “app” containing all files of this module:

Now, please connect to your FTP by using FileZilla or other FTP Application to upload the files to your server:

![Install the Package Downloaded](./img102/it_img004.png?raw=true)

After uploading all the files to your server, please login to your SSH by using Putty or SSH command line. Them, please use **cd** command to change the directory to Magento 2 root folder:

***cd [magento 2 root folder]***

Run the setup:upgrade command line:

***php bin/magento setup:upgrade***

Wait a second to complete installation process:

![Install the Package Downloaded](./img102/it_img005.png?raw=true)

If your website is in the Production mode, you should re-run the Magento compile command. Please enter the command:

***php bin/magento setup:di:compile*** 

![Install the Package Downloaded](./img102/it_img006.png?raw=true)

After that, if your website is in the Default or the Production mode, please type the command line to deploy the static content:

***php bin/magento setup:static-content:deploy***

![Install the Package Downloaded](./img102/it_img007.png?raw=true)

Then, if your website enabled the cache, please enter this command:

***php bin/magento cache:flush***

Finally, coming back to Magento 2 admin to check if the module is installed properly. 

***Note:*** *In case that you have followed all above steps but couldn’t make the module work properly, to make your website function as normal, please contact us at support@magestore.com or support.magestore.com, our supporters will assist you in resolving any issues within 24 hours.*

--------

## HOW TO CONFIGURE


### Multi-companies (Coming soon)


### Inventory Management


#### Stock Control Configuration


Path: **Stores > Settings** section> **Configuration > MageStore Module > Inventory Management Configuration**

![Stock Control Configuration](./img102/it_img008.png?raw=true)

(1)	**Link stocks in Warehouse to Front Store View**: choose **Yes** to activate the visibility of Stocks in Warehouse on the Front Store View 

(2)	**Adjust Stock by entering the change Qty.**: if you choose **Yes**, when you enter the change Qty. of products, the system will automatically reset for you to the right 

(3)	Click **Save Config** to finish


#### Pricelist Configuration


***Note: Pricelist** is a list of current prices of items on sale*

Path: **Stores > Settings** section **> Configuration > MageStore Module > Supplier Configuration**

![Stock Control Configuration](./img102/it_img009.png?raw=true)

(1)	Select **Yes** to allow using and importing supplier pricelist, and vice versa.

(2)	Click **Save Config**.


#### Stock Option

Path: **Stores > Settings** section **> Configuration > Catalog > Inventory**

***Note:*** *If you want to configure based on your own features, then unmark box* ***Use System value***.


##### Stock Option


![Stock Option](./img102/it_img010.png?raw=true)

(1)	Select **Yes** in the dropdown list to adjust the quantity on hand when an order is placed.

(2)	Select **Yes** in the dropdown list to return items to stock if an order is cancelled.

(3)	Select **Yes** in the dropdown list to continue to display products in the catalogue that are no longer in stock. 

(4)	Enter the number in the blank to display the message: **Only x left** on website when the quantity in stock reaches the threshold.  

(5)	Select **Yes** in dropdown list to display an **In Stock** or **Out of Stock** message on the product page.

(6)	Tap **Save** to finish. 


##### Product Stock Options


Path: **Stores > Settings** section **> Configuration > Catalog > Inventory**

![Product Stock Options](./img102/it_img011.png?raw=true)

(1)	Select Yes to activate inventory control for your catalog. 

(2)	Set Backorders to one of the following status: 

•	**No Backorders Allow Qty. Below 0:** To reject backorders when product is out of stock.

•	**Allow Qty. Below 0:** To accept backorders when the quantity falls below zero. 

•	**Notify Customer:** To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

(3)	Enter the **Maximum Qty.** allowed in Shopping Cart.

(4)	Enter the quantity for Item's Status to become out of stock.

(5)	Enter the **Minimum Qty.** allowed in Shopping Cart.

Next, 

![Product Stock Options](./img102/it_img012.png?raw=true) 

(6)	Enter the stock level that generate notification showing the item is out of stock.

(7)	Select **Yes** to activate quantity increments for the product. Then in the **Qty. Increments** field, enter the number of the items that must be purchased to meet the requirement mentioned above.

(8)	Select **Yes** to return the item to inventory by default when a credit memo is issued for the item.
Finally, click on **Save Config** to save changes.


#### Low Stock Notification Rules


***Note: Low Stock Alert** is when a type of product is on the verge of low-stock, Low Stock Alert will alert the Inventory manager to import more items. This feature avoids lack of items to supply for stores.* 

Path: **Inventory Management > Prediction** section **> Low Stock Rules**

![Product Stock Options](./img102/it_img013.png?raw=true)

(1)	Click Add new rule to create a new low stock notification rule

![Product Stock Options](./img102/it_img014.png?raw=true)

(2)	Enter the low stock rule name

(3)	Add a brief about the rule (optional)

(4)	Select Active to enable the rule

(5)	Use Calendar to choose From and To date for a term of validity (optional)

![Product Stock Options](./img102/it_img015.png?raw=true)

(6)	Select an **update time**:

•	Daily

•	Monthly

The system periodically check stock availability and automatically send email notifications admin and warehouse managers.

(7)	**Select hours** the warning message will be sent

![Product Stock Options](./img102/it_img016.png?raw=true)

On the **Conditions Tab**:

There are 2 types of low stock rule: 

***Type 1: Availability Qty.***

***Availability Qty.:*** you can select Qty. threshold that the system will notify to import. 

(8)	Select **Availability Qty.**

(9)	Set the number of **threshold** quantity

(10)	 Select **Both Warehouse and Global** for notification scope

(11)	 Select **Warehouses** for those rules will be applied

![Product Stock Options](./img102/it_img017.png?raw=true)

**Type 2: Availability Days**

***Availability Days:*** you can select Day Threshold that system can notify you to import items. You do not need to enter the Qty. here because the system will automatically calculate the selling rate based on the sale period you provided and the real Qty. in your warehouse and (store)

(12)	Select **Availability Days**

(13)	Set the number of **threshold days**

(14)	Set the number of **sales period days**

(15)	Select **Both Warehouse and Global** for notification scope

(16)	Select **warehouses** for those rules will be applied

![Product Stock Options](./img102/it_img018.png?raw=true)

On **Actions** Tab:

(17)	Enter an **email list** to send the low stock notifications to

(18)	Enter content of the **warning message** 

![Product Stock Options](./img102/it_img019.png?raw=true)

(19)	Click **Save** or **Save and Apply** to finish

•	**Save and Continue Edit**: to save the process and continue edit on the current page. 

•	**Save and Apply**: you can apply rule immediately

•	**Save**: you can save the rule but it will not be applied, in case you need to ask for permission before applying or double-check with other people. 

***Note:** You can edit the rule that you **Save and Apply** or **Save** by going to **Inventory Management > Prediction** section **> Low Stock Rules >** clicking on **Edit***

![](./img102/it_img020.png?raw=true)



### Web POS


#### Default Guest Checkout


Path: **Sale > Web POS** section > **Setting > Default Guest Checkout**

Default customer is the customer whose information will be used for Guest Checkout or when customer information is not enough, default value will be filled automatically.

![Default Guest Checkout](./img102/it_img021.png?raw=true)
	
Fill in all information as you want to use as default, including **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**. After finishing, click on **Save Config** button to save your work.


#### How Web POS works with peripheral devices


MageStore Web POS module can connect with Barcode readers, Card swiper & Receipt printers. 

1)	**Barcode readers:** are any devices that can connect with iPad/Laptop/PC (including USB Port, Wifi or Bluetooth). The scanner can read barcodes & fill encoded information into Web POS search box.

2)	**Card swiper:** only devices connected through USB port (supports Authorize.Net & Stripe).

3)	**Receipt printers:** any devices that connect with iPad/laptop/PC

### Loyalty program


#### Catalog Price Rule


Path: **Marketing > Promotions** Section **> Catalog Price Rule**


##### Manage Catalog Price Rule

![Manage Catalog Price Rule](./img102/it_img022.png?raw=true)

(1)	Click **Add New Rule** to create a new catalog price rules.

(2)	Fill out the blank with a value to search, after click **Search**.

(3)	Search catalog price rules information with keyword. View or edit a rule’s detail by clicking on each line.

##### Type of Pricing Rule

| Type of pricing rule | Description|
| ---| ---|
| Apply as percentage of original | Discount item by subtracting a percentage from the original price|
| Apply as fixed amount | Discounts item by subtracting a fixed amount from original price. |
|Adjust final price to this percentage| Discount item by defining the final price based on percentage.| Adjust final price to discount value | Sets the price to a fixed amount.


##### Create a new Catalog Price Rule

![Create a new Catalog Price Rule](./img102/it_img023.png?raw=true)

Click on **Add New Rule**

![Create a new Catalog Price Rule](./img102/it_img024.png?raw=true)

**Rule Information**

(1)	Fill in the **Rule Name** *(required)*

(2)	Fill in **description of the rule**

(3)	Select **Active**

(4)	Select **websites** where the rule is to be applied

(5)	Select **Customer Groups** to which rules are applied. 

(6)	Set the **From** and **To** date range for the promotion.

(7)	Choose **Priority** (a number that indicates the priority of this rule in relation to others. The highest priority is number 1)

![Create a new Catalog Price Rule](./img102/it_img025.png?raw=true)

**Conditions**

Click the small green button to add conditions.

![Create a new Catalog Price Rule](./img102/it_img026.png?raw=true)

**Action**

-	Select type of pricing rule that you want.
-	Enter the **Discount Amount** to apply.
-	Set **Yes** to stop processing other rules. This prevents customers from receiving multiple discounts for the same product. 
To finish, click **Save**

#### Cart Price Rule

***Note: Cart price rules** apply discounts to items in the shopping cart, based on a set of conditions. When applied, the discount appears in the cart under the subtotal. A cart price rule can be used as needed for a season or promotion by changing its status and date range.*

##### Manage Cart Price Rule

Path: **Marketing > Promotion** section **> Cart Price Rule**

![Manage Cart Price Rule](./img102/it_img027.png?raw=true)

(1)	Click **Add New User** to create a new cart price rules.

(2)	Fill in the blank with a value to search, after click **Search**.

(3)	**Search** cart price rules information with keyword. View or edit a rule’s detail by clicking on each line.


##### Type of Account

| Type of pricing rule | Description|
| ---| ---|
| Percent of product price discount| Discounts item by subtracting a percentage from the original price. The discount applies to each qualifying item in the cart. For example: Enter 10 in Discount Amount for an updated price that is 10% less than the original price.|
|Fixed amount discount| Discounts item by subtracting a fixed amount from original price. The discount applies to each qualifying item in the cart. For example: Enter 10 in Discount Amount for an updated price that is $10 less than the original price.|
|Fixed amount discount for whole cart|Discount the entire cart by subtracting a percentage from the cart total. For example: Enter 10 in Discount Amount to subtract 10% from the cart total.|
|Buy X get Y free|Defines a quantity that the customer must purchase to receive a quantity for free (The Discount Amount is Y)


##### Create a Cart Price Rule

![Create a Cart Price Rule](./img102/it_img028.png?raw=true)

Click **Add New Rule** to create a new Cart Price Rule

![Create a Cart Price Rule](./img102/it_img029.png?raw=true)

**Add a New Rule**

(1)	Enter a **rule name** 

(2)	Enter the **description**

(3)	If you do not want the rule to go into effect immediately, set **Active** to **No**.

(4)	Select the **websites** where the promotion is to be available.

(5)	Select **customer groups** to which the promotion applies. For the promotion to be available only to registered customers, do not select the **NOT LOGGED IN** option.

(6)	To associate a coupon with the price rule, set Coupon to **Specific Coupon**. Then, do the following:

![Create a Cart Price Rule](./img102/it_img030.png?raw=true)

(7)	Enter a numeric **Coupon Code** that the customer must enter to receive the discount.

(8)	Limit the number of times the **coupon code** can be used. If there is no limit, leave the field blank.

(9)	Limit the number of times the coupon code can be used by the same registered customer who belongs to any of the selected customer groups. The setting does not apply to guest shoppers who are members of the *NOT LOGGED IN* customer group, or to customers who shop without logging in to their accounts. If there is no limit, leave the field blank.

(10)	 Set the **From** and **To** date range for the promotion.

(11)	Enter a number to determine the **Priority** of this price rule in relation to the Action settings of other price rules that might be active at the same time. (Number 1 has the highest priority.)

(12)	To apply the rule to published listings in RSS feeds, set Public In RSS Feed to **Yes**.

![Create a Cart Price Rule](./img102/it_img031.png?raw=true)

**Conditions**

Click  the small green button to add conditions.


![Create a Cart Price Rule](./img102/it_img032.png?raw=true)

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

(5)	**Apply to Shipping Amount**: If you choose **Yes** - Applies the discount amount to the subtotal and shopping amounts separately. Vice versa, applies the discount amount only to the subtotal.

(6)	**Discard Subsequent Rules:** Stop processing other rules after this rule is applied.

(7)	**Free Shipping:**

•	Choose **No**: free shipping is not available.

•	Choose **For matching items only**, then free shipping is available only for items that match the conditions of rule.

•	Choose **For shipment with matching items**, then free shipping is available for any shipment that includes matching item(s).

(8)	Define as many additional conditions as needed for the action. When complete, click **Save and Continue Edit.**

![Create a Cart Price Rule](./img102/it_img033.png?raw=true)

**The labels**

The label appears on the order below the subtotal to identify the discount. You can enter a default label for all store views, or enter a different label for each view.

(1)	**Default Rule Label for All Store Views:** this label will appear on the order below the subtotal.

(2)	**Default Store View:** If your store has multiple views, or multiple websites with multiple view, enter the appropriate label text for each.


##### Create a Specific Coupon

![Create a Specific Coupon](./img102/it_img034.png?raw=true)

Follow the instructions to **Create a Cart Price Rule**.

On the **General Information** page, set Coupon to **Specific Coupon.**

(1)	Enter a **Coupon Code** to be used with the promotion. 

(2)	Limit the number of times the coupon can be used. For unlimited use, leave these fields blank.

(3)	Limit the number of times the coupon can be used by same customer.

(4)	Use **Calendar** to set the **From** and **To** date range for the promotion. If you leave the date range empty, the rule will never expire.

Click **Save** to finish.

##### Generate a Batch of Coupons

![Generate a Batch of Coupons](./img102/it_img035.png?raw=true)

Under **Coupon** tab, mark the **Use Auto Generation** checkbox. 

To limit the number of times each customer can use the coupon, enter the number of **Uses per Customer**. To limit the number of times a person uses per coupon, enter the number of **Uses per Coupon**

![Generate a Batch of Coupons](./img102/it_img036.png?raw=true)

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

![Generate a Batch of Coupons](./img102/it_img037.png?raw=true)

When complete, click **Generate**. The list of generated codes appears below it.


#### Free Gift Promotions (Coming soon)

#### Gift Card


##### Setting


Path: **Marketing > Gift Card** section **> Settings**

To configure default configurations and settings of the module, please log in to backend screen, and then do the following stages as below: 

![Free Gift Promotions](./img102/it_img038.png?raw=true)

**GENERAL**

**Gift code**

(1)	Select **Yes** in the dropdown list to **enable Gift Card**

(2)	Configure the **pattern** to auto-generate gift codes for Gift Card products when customers purchase in WebPOS frontend

(3)	Enter the number of **prefix characters** which are shown in a voucher code

(4)	Enter one **letter to replace hidden characters**

![Gift code](./img102/it_img039.png?raw=true)

**Gift Card Usage**

(1)	Enter the term of validity that Gift Cards can be used after being activated.

(2)	Enter the **maximum time(s)** that allows users to enter gift code incorrectly.

(3)	Enter the **maximum number of users per gift code**.

(4)	Select **Yes** to allow customer to apply gift card for shipping fee

(5)	Select **Yes** to allow customers to use both Gift Card codes and Coupon codes at once. 

(6)	 Select **Yes** to allow customers to check status of Gift Cards after entering Gift Codes, and vice versa.

(7)	Select **Yes** to show the expiration date of Gift Cards on website, and vice versa.


![Gift Card Usage](./img102/it_img040.png?raw=true)

**Tax Configuration**

(1)	Select:

•	**After Tax:** to allow applying Gift Card after the tax is applied

•	**Before Tax:**  to allow applying Gift Card w/o tax

![Tax Configuration](./img102/it_img041.png?raw=true)

**ON PRODUCT PAGE**

**Gift Card Value**

(1)	Enter the default gift card value *(follow the below instruction)*

(2)	Enter the description of gift card value *(follow the below instruction)*

![Gift Card Value](./img102/it_img042.png?raw=true)

**Gift Card Template**

(1) Select **Yes** to allow customers to change the image inserted in the template

(2) Limit the maximum size of images uploaded by customers to 500KB

**Gift Card Shipping Information**

(3) Select **Yes**: Gift card can be sent through the post office

(4) Choose **5** means that after Customers order Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within 5 days

(5) Limit the maximum length of a custom message on Gift Card. Select **Yes** to allow users to schedule gift card delivery date.


![Gift Card Shipping Information](./img102/it_img043.png?raw=true)

**ON SHOPPING CART PAGE**

(1)	Select **Yes** to Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.

(2)	Select the data to display on shopping cart page

(3)	Select **Yes** to allow showing Gift Card printout preview as product image on shopping cart page

![ON SHOPPING CART PAGE](./img102/it_img044.png?raw=true)

**ON CHECKOUT PAGE**

Select **Yes** to show Gift Card box on the checkout page

![ON CHECKOUT PAGE](./img102/it_img045.png?raw=true)

**EMAIL NOTIFICATION**
 
**General**

(1)	Select **Yes** to allow sending notification emails to customers and recipients

(2)	Select **Active**, only a gift card which is activated can be sent to a friend

(3)	Set the default sender of notification emails as General Contact 

(4)	Select **Yes** to allow sending a copy of gift card via email if customers choose to ship through post office.

![EMAIL NOTIFICATION](./img102/it_img046.png?raw=true)

**Notification email sent to purchasers**

(1)	Select the email template **sent to purchasers after buying Gift Card** successfully. 

(2)	Select the email template **sent to purchasers when recipients receive Gift Cards.** 

**Notification email sent to recipient**

(3)	Select **Yes** to allow email notification being sent to recipient when sender refunds Gift Card.

(4)	Select the email template **sent to the gift card’s recipient.** 

(5)	Choose the email template **sent to recipient when gift card is refunded.** 

(6)	Enable auto reminder email **sent to Customers before Gift card expires** 

(7)	Enter the **number of days** to **send notification to customers before the expiration date of a Gift card.** 

![Notification email sent to recipient](./img102/it_img047.png?raw=true)

**GIFT CARD PRINTOUT**

Click **Choose File** to upload an image used as a logo when Gift Cards are printed or sent via email. 

##### Manage Gift Card Templates

**-	Add new template**

Path: **Marketing > Gift Card** section **> Manage Gift Card Templates**

![Add new template](./img102/it_img048.png?raw=true)

(1)	Click **Add New Template**

![Add new template](./img102/it_img049.png?raw=true)

*On the popup screen*

(1)	Enter the template’s **name**

(2)	Choose a **design pattern** in dropdown list *(optional)*

(3)	Enter notes or description about the gift card template *(if any)*

(4)	Choose **text color**

(5)	Choose **link/ special text color**

![Add new template](./img102/it_img050.png?raw=true)

(6)	Upload a **background image**. 

(7)	Click **Save and Continue** or **Save**

**-	Preview Existing Template**

Path: **Marketing > Gift Card** section > **Manage Gift Card Templates**

![Preview Existing Template](./img102/it_img051.png?raw=true)

Click **Preview** to see the gift card template

**-	Edit and Delete Existing Template**

Path: **Marketing > Gift Card** section **> Manage Gift Card Templates**

![Edit and Delete Existing Template](./img102/it_img052.png?raw=true)

(1)	Mark the template checkbox

(2)	Tab the action label, select **Delete** to remove templates. 

(3)	Click **Edit** to update templates data

![Edit and Delete Existing Template](./img102/it_img053.png?raw=true)

*On the popup screen*

(4)	Edit templates data

(5)	Click **Save** to finish

(6)	*Additional guidance:* Click **Delete** to remove template

##### Generate Gift Code

Path: **Marketing > Gift Card** section **> Generate Gift Code**

![Generate Gift Code](./img102/it_img054.png?raw=true)

(1) Click on **Add Gift Code Pattern** to create new pattern code

![Generate Gift Code](./img102/it_img055.png?raw=true)

![Generate Gift Code](./img102/it_img056.png?raw=true)

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

![Generate Gift Code](./img102/it_img057.png?raw=true)

A status ***The pattern has been generated successfully*** would be shown on the pop-up screen

![Generate Gift Code](./img102/it_img058.png?raw=true)

A list a generated Gift Codes would be shown at the bottom of the pop-up screen

##### Manage Gift Codes

**1/	Create a new Gift Code**

Path: **Marketing > Gift Card** section **> Manage Gift Code**

![Manage Gift Codes](./img102/it_img059.png?raw=true)

(1)	Click on **Add Gift Code** to create a new gift code

Moreover, click on I**mport Gift Codes** to import data from your device to the system.

![Manage Gift Codes](./img102/it_img060.png?raw=true)

![Manage Gift Codes](./img102/it_img061.png?raw=true)

*On the popup screen:*

(2)	Follow the example mentioned under the tab to set a format for the gift code  

(3)	Enter the **Gift code value**

(4)	Select a **currency**

(5)	Select a **gift code template**

(6)	Select **Active** to enable/ activate the gift code

(7)	Select an **expiration date**

(8)	Select **store views**

(9)	Write a comment *(optional)*

![Manage Gift Codes](./img102/it_img063.png?raw=true)

![Manage Gift Codes](./img102/it_img064.png?raw=true)

*Scroll down, on the **Message Information** tab, click  to expand:*

(1)	Enter the **sender nam**e and **email**

(2)	Enter the **recipient name** and **email**

(3)	Enter the **Recipient Address**

(4)	Enter the **message to the recipient**


![Manage Gift Codes](./img102/it_img065.png?raw=true)

*Finally, scroll up, tab the arrow on the right hand-side of **Save** button:* 

(1)	Select **Save & Send Email** to save and send Gift Codes via emails to both sender and recipient

(2)	Select **Save & Continue Edit** to finish.


**2/	Manage Gift Card History per customer**

Path: **Customers > All Customers**

![Manage Gift Card History per customer](./img102/it_img066.png?raw=true)

(1)	Click **Edit** to view an existing customer’s detailed information 

![Manage Gift Card History per customer](./img102/it_img067.png?raw=true)

*On the popup screen:*

(2)	Click on **Gift Card History** tab to view all transactions in which gift cards were applied

##### Apply Gift code when create new order

Path: **Customers > All Customers**

On **Create New Order** page, after selecting a customer and adding a product to an order, the system will show the Gift Card box, which allowing you to use Gift Card credit balance or Gift Card code(s) of the Customer to pay for this order. Select the method(s) as you want and then remember to click on **Apply Gift Card** button. 

![Apply Gift code when create new order](./img102/it_img068.png?raw=true)

(1)	Mark the check box to use gift card to checkout

(2)	Enter the **Gift card code**

(3)	Click on the arrow to apply the gift code

![Apply Gift code when create new order](./img102/it_img069.png?raw=true)

Scroll down to view **Order Totals** label, then click on (4)** Submit Order** to finish.


##### Refund Orders

Path: **Sales > Operations**  section **> Orders**

![Refund Orders](./img102/it_img070.png?raw=true)

(1)	On the dashboard screen of admin, click **Sales > Orders**

![Refund Orders](./img102/it_img071.png?raw=true)

(2)	Click **View**

![Refund Orders](./img102/it_img072.png?raw=true)

(3)	On the **Order View** tab, click on **Credit Memos** to refund

![Refund Orders](./img102/it_img073.png?raw=true)

(4)	Enter the number of money to refund to gift credit 

(5)	Click on **Refund Offline** to finish.

##### History

Path: **Marketing > Gift Card** section **> Gift Code History**

![History](./img102/it_img074.png?raw=true)

On **Gift Card History** page, you will know when Gift Cards were created/ updated/ redeemed/ spent/ refunded and by whom as well as their values and status. 

You can filter data with the above criteria to get more accurate reports. Information can be exported to .CSV or .XML files for your convenience. 

#### Reward Point

##### Add new rate

![Add new rate](./img102/it_img075.png?raw=true)

(1)	Click on **Reward Points**

(2)	Click on **Spending rates** 

(3)	Click on **Add new spending rate**

![Add new rate](./img102/it_img076.png?raw=true)

Fill all the data needed in the boxes

![Add new rate](./img102/it_img077.png?raw=true)

Click on **Save spending rate** after finishing filling in all the boxes

![Add new rate](./img102/it_img078.png?raw=true)

The new earning rate will be shown as the beside image

##### Edit existing rate 

Path: **Reward Point > Spending** section **> Spending Rates**

![Edit existing rate](./img102/it_img079.png?raw=true)

Click on **Edit** on action column of the rate needed to be edited

![Edit existing rate](./img102/it_img080.png?raw=true)

Edit the rate, then click **Save** spending rate, or **Delete** it

##### Manage transaction

Path: **Reward points > Transactions** 

![Manage transaction](./img102/it_img081.png?raw=true)

Click on **Add new transaction** to add new transaction

![Manage transaction](./img102/it_img082.png?raw=true)

Fill in the required information and click on **Save**

##### Manage point balances of customers

Path: **Customers > All customers**

![Manage point balances of customers](./img102/it_img083.png?raw=true)

Click on **Edit** of the customer needed to be managed

![Manage point balances of customers](./img102/it_img084.png?raw=true)

Click on reward points to manage the customer’s balance by filling the change balance, change title, points expire on box.

Also, update points subscription and expire transaction subscription can be configured in reward points

Click on **Save customer** to save the changes

![Manage point balances of customers](./img102/it_img085.png?raw=true)

All transactions of a customer are also listed in reward points


##### Change point balance

Path: **Reward points > Manage points balances**

There are two ways to change the point balance of a customer. 	

The first way is to enter the **Change Balance** in the **Reward Points** session as mentioned above.

The second way to change points, which can be done to many customers at the same time, is illustrated below:

![Change point balance](./img102/it_img086.png?raw=true)

A list of customers will be shown with point balance column

![Change point balance](./img102/it_img087.png?raw=true)

Click on **Import** to import from computer

![Change point balance](./img102/it_img088.png?raw=true)

(1)	Click on **Choose file** to upload file

(2)	Click on **Import** to import it

![Change point balance](./img102/it_img089.png?raw=true)

The list of customers in **Reward Point Balances** Information page can also be exported by clicking on **Export**


##### Create an Order

Path: **Sales > Orders**

![Create an Order](./img102/it_img090.png?raw=true)

(1)	Click on **Sales**

(2)	Choose **Orders**

(3)	Click on **Create new order**

![Create an Order](./img102/it_img091.png?raw=true)

Select customer from the list

![Create an Order](./img102/it_img092.png?raw=true)

Click on **Add products** to add products to the order

![Create an Order](./img102/it_img093.png?raw=true)

Click on the product and enter the quantity, then click on **add selected product(s) to order**

![Create an Order](./img102/it_img094.png?raw=true)

Set the number of point customer will use in the order in the use customer reward points

![Create an Order](./img102/it_img095.png?raw=true)

Fill in the required fields, click on submit order to finish creating new order

##### Refund Orders

Path: **Sales > Operations** section **> Orders** 

![Refund Orders](./img102/it_img096.png?raw=true)

(1)	Click on **View** to see the details of an order 

![Refund Orders](./img102/it_img097.png?raw=true)

(2) On the top bar, click on **Credit Memo** label to create a refund order 

![Refund Orders](./img102/it_img098.png?raw=true)

*On the pop-up screen named **New Memo**, scroll down, then:*

(3)	Enter the earned points that will be refunded to customer’s balance

(4)	Click on **Refund Online** to finish

![Refund Orders](./img102/it_img099.png?raw=true)

*After the credit memo has been created:*

(5)	Click on **Credit Memo** tab on the left hand-side to view credit memos data

#### Store Credit

##### Manage Customers Using Credit

Path: **Store Credit > Manage Customers Using Credit**

![Manage Customers Using Credit](./img102/it_img100.png?raw=true)

Then the **Customers Using Credit Manager** page will be displayed as below:

![Manage Customers Using Credit](./img102/it_img101.png?raw=true)

This page shows a list of all Customers using credit and their information such as name, email, credit balance, telephone, etc.

To view more details about a Customer, you can click on the **Edit** link in the **Action** column.

Then, you will be navigated to the **Customer Information** page. By selecting **Store Credit** tab, you can view all Customer’s transaction history and credit balance:

![Manage Customers Using Credit](./imgpart2/it_img102.png?raw=true)

Besides, you can change the Customer’s credit balance by entering an integer (a positive or negative number) and a comment in text fields as below:

![Manage Customers Using Credit](./imgpart2/it_img103.png?raw=true)

The module will automatically send email to Customer to announce about this transaction if you tick on **Send email to customer** checkbox. The email will be sent to the customer as bellow: 

![Manage Customers Using Credit](./imgpart2/it_img104.png?raw=true)


After you save, our module will auto update the Customer’s credit balance, send an email to that Customer and create a transaction as follows:

![Manage Customers Using Credit](./imgpart2/it_img105.png?raw=true)


##### Manage Credit Products

Path: **Store Credit > Manage Credit Products**

![Manage Credit Products](./imgpart2/it_img106.png?raw=true)

Then the **Credit Product Manager** page will be shown:

![Manage Credit Products](./imgpart2/it_img107.png?raw=true)

This page shows you all credit products with a lot of information such as **product ID, name, SKU, quantity, status,** etc.

To add a new credit product, you can click on the **Add Credit Product** button on the right top of the page.

You can add a credit product just in a similar way to adding a normal product. You should pay attention to these following tabs:

**a)**	**Prices** Tab:

![Manage Credit Products](./imgpart2/it_img108.png?raw=true)

In this tab, you can configure the value of the credit product. There are three types of credit products including **fixed value, range of values and drop-down value.**

**b)**	**Setting** Section:

![Manage Credit Products](./imgpart2/it_img109.png?raw=true)

(1)	**Enable Product:** activate the Store Credit 

![Manage Credit Products](./imgpart2/it_img110.png?raw=true)

(2)	**Attribute Set:** select default or any attributes available to purchase by Store Credit

(3)	**Product name:** enter the name 

(4)	**SKU:** enter the SKU of your store credit

(5)	**Quantity:** enter the number of store credit cards you can give *(optional)*

(6)	**Stock Status:** select the current availability of the Store Credit

![Manage Credit Products](./imgpart2/it_img111.png?raw=true)

(7)	**Categories:** select the categories that you sell this Store Credit. In case, you do not have fitted category. Click on **New Category**

![Manage Credit Products](./imgpart2/it_img112.png?raw=true)

(8)	**Visibility:** choose where it will be visible to customers

(9)	**Set product as new from:** choose active date of the Store Credit

(10)	**Visible on Web POS:** activate the Store Credit on the Web POS

**c)**	**Advanced Inventory**

Path: **New Product > Quantity > Advanced Inventory**

![Manage Credit Products](./imgpart2/it_img113.png?raw=true)

![Manage Credit Products](./imgpart2/it_img114.png?raw=true)

(1)	**Manage Stock:** our module sets up the field as **Yes**. It means that you need to manage the Qty.. of Credit Products. You can edit it by uncheck box **Use Config Settings.**

(2)	**Qty.:** it is synchronized with the **Qty.** on **New Product** Section

(3)	**Out-of-stock Threshold:** our module sets up the field as **0**. It means the product will be notified **Out-of-stock** when the number of items is **0**. You can edit it by uncheck box **Use Config Settings**

(4)	**Minimum Qty. Allowed in Shopping Cart:** our modules set up the field as **1**. It means a customer must have at least 1 product in a single order to purchase Store Credit Product. You can edit it by non- checking box **Use Config Settings**.

(5)	**Maximum Qty. Allowed in Shopping Cart:** as mentioned in No.4

![Manage Credit Products](./imgpart2/it_img115.png?raw=true)

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

![Manage Credit Products](./imgpart2/it_img116.png?raw=true)

##### Manage Credit Transactions and Report Charts

**a) Credit Transactions**

Path: **Store Credit > Credit Transactions** Section **> Manage Credit Transactions**

![Manage Credit Transactions](./imgpart2/it_img117.png?raw=true)

Then the **Credit Transactions** page will be shown: 

![Manage Credit Transactions](./imgpart2/it_img118.png?raw=true)

This page shows all credit-related transactions with a lot of information such as **type, detail, customer name/email, added/deducted credit, credit balance** after transaction.

You can search any transaction by using filter boxes in each column.

If you click on a Customer’s email, you will be navigated to the **Customer Information** page.

**b)** **Credit Report Charts**

Path: **Store Credit > Credit Transactions** Section **> Customer Credit Report**

![Manage Report Charts](./imgpart2/it_img119.png?raw=true)

Then the **Report Charts** page will be shown as follows:

![Manage Report Charts](./imgpart2/it_img120.png?raw=true)

This page can be divided into two main sections including **Life-time Reports** and **Period-of-time Report Charts.**

•	**Life-time Reports:** There are 2 types of reports.

-	***Customer Credit Statistics*** *with the total credit, the total spent credit and the number of Customers with credit in your system.*

-	***Top 5 Customers with The Greatest Credit Balances** with their names and current balances in your system.*

•	**Period-of-time Report Charts:** This chart shows you the total spent credit and received credit of all Customers per day in your chosen time range such as **last 24 hours, last 7 days, current month,** etc.


##### Using Credit to checkout in backend:

Path: **Sales > Operations** Section **> Orders >** enter numbers on **Customer Credit** tab

On the **Create Order** page on backend, our module allows you to use credit when creating orders for Customers.

![Using Credit to checkout in backend](./imgpart2/it_img121.png?raw=true)

You just need to enter a credit amount and click on the **Gray Arrow** button. Our module will auto-update and calculate the grand total of the order.

![Using Credit to checkout in backend](./imgpart2/it_img122.png?raw=true)

After submitting the order, the Customer’s credit balance will also auto update and you can check the transaction on the **Credit Transaction** page.

![Using Credit to checkout in backend](./imgpart2/it_img123.png?raw=true)

##### Refund Orders into Credit Balance

When Customers want to refund an order, our module allows you to transfer the order value to his credit balance. In that way, Customers can use the credit for future purchases and you do not have to lose money for the refund at the same time.

After clicking on the **Credit Memo** button, our module shows a text field for you to enter the amount you want to refund into credit:

![Refund Orders into Credit Balance](./imgpart2/it_img124.png?raw=true)

After that, when you click on the **Refund Offline** button, the amount you entered as well as the credit that the Customer used for paying for the order will be refunded to his current credit balance. 

For any order that includes only Credit Product, the option **Refund Order to Credit** is not available.

Once the refund is finished, you can check the transaction on the **Manage Transaction** page:

![Refund Orders into Credit Balance](./imgpart2/it_img125.png?raw=true)


##### Settings

Path: **Store Credit > Settings**

![Settings](./imgpart2/it_img126.png?raw=true)

**a)**	**General Configuration** Tab:

Path: **Magento Extension > Store Credit**

![General Configuration](./imgpart2/it_img127.png?raw=true)

(1)	**Enable Store Credit:** to activate Store Credit on your site

(2)	**Allow sending Credit:** allow customers to send credit to their friends

(3)	**Groups can use edit:** allow only general/wholesaler/retailer or all customers able to use credits

**b)**	**Spend Credit On** Tab

![Spend Credit On](./imgpart2/it_img128.png?raw=true)

(1)	**Apply Customer Credit:** If you choose **After tax**, it means the Customer Credit Discount will be applied to order value including tax

(2)	**Shipping fee:** If you choose **No**, credit balance cannot be used to pay for Shipping Fee

**c)**	**Email Configuration** Tab:

![Email Configuration](./imgpart2/it_img129.png?raw=true)

(1)	**Email template with credit code sent to recipients:** default

(2)	**Email template with verification code sent to credit sender:** default

(3)	**Email template notifying customers:** default

(4)	**Send-to-customer email template when recipient receives credit:** default

**d)**	**Adjust time for Customer credit reports on total used and total received credit** Tab:

![Adjust time for Customer credit reports on total used and total received credit](./imgpart2/it_img130.png?raw=true)

(1)	**Select start time for current year:** choose Month, then Date

(2)	**Select date for current month:** choose Date

**e)**	**Style configuration** tab: on this tab, you will be able to change background and color of Title

![Style configuration](./imgpart2/it_img131.png?raw=true)

(1)	**Background of Title:** enter Hexadecimal code

(2)	**Color of Title:** enter Hexadecimal code

#### Wallet (Coming Soon)


#### Membership (Coming Soon)


### Store Pickup


#### Setting


Path: **Store Pickup > Settings > Magento Extensions** Tab **> Store Pickup**

![Setting](./storepickup/i1.png?raw=true)

The configuration is divided into 3 groups including **General, Service API,**  and **Store Search** 

•	**General** 

![Setting](./storepickup/i2.png?raw=true)

(1)	Choose **Yes** if you want to enable the module on your site

(2)	Choose **Yes** to show **Store Pickup** link on the top link in frontend 

(3)	Select one of these three options:

**+ Default:** Stores are listed based on Sort Order of each store

**+ Distance:** Stores are listed based on the distance between customers’ location and stores. If customers don’t enter their location, stores will be listed by **Default (Sort Order)**

**+ Alphabetical order:** Stores are listed based on alphabetical order of store name

(4)	Enter the title of your page. Store listing page and store detailed are displayed as the **Page Title**

(5)	Enter the **number of days** to show Store's holidays and special days within this period in frontend.

(6)	Enter the **maximum number of stores** that will be shown in list store when paging at frontend.

(7)	Enter the **maximum number of images** for each store when uploading image 

•	**Service API**

![Service API](./storepickup/i3.png?raw=true)

(1)	To integrate **Google API** or **Facebook API** in your site, fill your Google Map API and Facebook API key into the relevant field. You can get this key by clicking on **here** under **Google Map API Key** tab or **Facebook API Key** tab. Or else, you can go to **Store Pickup > Guide** 

(2)	Choose **Yes** to enable **Facebook comment** for your stores. 

•	**Store Search**

![Service API](./storepickup/i4.png?raw=true)

(1)	Select which c**riteria customers** can search for stores by area

(2)	Enter the **radius value** that you want **Google Suggest** automatically show your stores to customers within the radius you enter 

(3)	Select the **unit** to measure radius

#### Manage Store

Path: **Store Pickup > Manage Store**

The **Store Manager** grid shows all stores created in your system with their address and status. To add new stores, you can add them manually and import from **CSV files.**

![Manage Store](./storepickup/i5.png?raw=true)

#####	Add store

![Add store](./storepickup/i6.png?raw=true)

There are two ways to add new store: **Import Store** or **Add New Store**

###### **Import Stores**

![Import Stores](./storepickup/i7.png?raw=true)

Click on **Choose file** to upload **CSV file**. 

Then to finish, click on **Import Stores** button on your right hand.

###### **Add new store**

Path: **Store Pickup > Manage Store > Add New Store**

You will be navigated to the **Add Store** page, which includes 7 tabs: **General Information, Google Map Location, Image Gallery, Store’s Schedule, Store’s Tag, Store’s Holiday, Store’s Special Days**

•	**General Information**

Path: **Add New Store > Store Information** section **> General Information** 

There are 4 sessions: **General Information, Contact Information, Owner Information** and **Meta Information**

![General Information](./storepickup/i8.png?raw=true)

Fill **Store Name, Description, Status, Store link** and **Sort order** in **General Information** session. 

Besides important information such as **Store name, Description, Status,** here are some extra fields you should use to optimize user experience:

**+ Store’s Link:** enter a link to the store’s official website or social channel such as Facebook fan page.

**+ Sort Order:** Sort the display order of store on the store listing page. The store with higher sort order will be shown first. This value will be used as the Default option of List Store by in Settings.

![General Information](./storepickup/i9.png?raw=true)

**Contact Information:** customers can contact to the store whenever they have any questions/problems.

**Owner Information:** an auto email will be sent to owner whenever customers want to pick up order in store. 

![General Information](./storepickup/i10.png?raw=true)

Fill in **URL key, Meta Title, Meta Keywords,** and **Meta Description** for better SEO. It can help your customers find your store website easier. 

•	**Google Map Location**

Path: **Add New Store > Store Information** section **> Google Map Location**
 
![Google Map Location](./storepickup/i11.png?raw=true)

Fill your store’s address in this field or pin from the map, remember to click on the **Save Store** or **Save And Continue Edit** button to save your work. After that, store’s location will be updated automatically on Google Map.

There are 4 fields you need to notice in this tab 

**+ Zoom Level:** It is used when previewing the store’s location on Google Map in backend and on the Store Listing page in frontend. The higher number you set, the higher zoom-in level is.

**+ Store Latitude** and **Store Longitude:** You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically.

**+ Marker Icon:** You can upload an icon to use as store’s marker on G-map instead of the default pin icon. 

***Note:***  When a store is created manually, the system will automatically get the coordinates based on the store address by using Google API. However, in some cases, this way may be not completely accurate. Therefore, the **Google Map Location** tab allows you to edit store coordinates manually.

You can see it at the left upper. Click on this tab, the Google map will be displayed. You can reset store position by clicking on specific point on the map, then select **Save Store**.

By clicking **Apply to Form** before saving, the store coordinates & the store address will be auto-updated regarding the address of the location you pinned on the map. You can also change the marker icon which presents the pinned location on the map.

•	**Image Gallery**

![Image Gallery](./storepickup/i12.png?raw=true)

Upload as many store images as you want. 

Click on **Make Base** on the picture to choose the picture as a base image.

The base image will be shown in the store list.

•	**Store’s Schedule**

Path: **Add New Store > Store Information** section **> Store’s Schedule**

![Store’s Schedule](./storepickup/i13.png?raw=true)

**[1]**	Click on **Click here** to create new schedule

You will be linked to a new page named **New Schedule**

![Store’s Schedule](./storepickup/i14.png?raw=true)

(1)	Enter **Schedule Name**

(2)	Choose time and status of the store on each day (from Monday to Sunday)

(3)	Click on **Apply to all** if you the time does not change during the week

(4)	**Save Schedule** to save the change.


**[2]**	Select a schedule that you have created for your store. For example: 

![Store’s Schedule](./storepickup/i15.png?raw=true)

After selecting **Store in January**, a timetable will be shown below the tab.  

•	**Store’s Tag**

![Store’s Tag](./storepickup/i16.png?raw=true)

For easier search, you can tag each store in multiple categories. Choose tags for each in this tab by search for the tag and select suitable ones. Please note that one store can belongs to more than one tag.

•	**Store’s Holiday**

![Store’s Holiday](./storepickup/i17.png?raw=true)

Select **Holidays** to be applied for this store by searching/filtering and select Holiday(s) that you set up before.

•	**Store’s Special days**

![Store’s Special days](./storepickup/i18.png?raw=true)

Select **Special days** to be applied for this store by searching/filtering and select Special day(s) that you set up before.

After all, if you finish everything, you can

![Store’s Special days](./storepickup/i19.png?raw=true)

**+ Save Store:**  save all changes and come back the Manage Store page

**+ Save and New:** save all changes and create another new store

**+ Save and Continue Edit:** save what you have changed and keep editing the store

**+ Reset:** delete all and start all over again

**+ Back:** come back to the Manage Store page without saving anything

##### Edit store

To edit a specific store, go to **Manage Store >** select Action **(Edit)**. 

![Edit store](./storepickup/i20.png?raw=true)


#### Manage Tag

Path: **Store Pickup > Manage Tag** 

![Manage Tag](./storepickup/i21.png?raw=true)

This tab manages all tags that are used to filter stores. Click on the **Add New Tag** button to create new one.

![Manage Tag](./storepickup/i22.png?raw=true)

**General Information:** Choose a suitable **Tag Name**, write a description and upload Icon to make it pop out on store listing page.

![General Information](./storepickup/i23.png?raw=true)

**Stores of Tag:** Select stores from the list to be shown up when Customers click on the tab you have created. Then **Save Tag** to save changes and come back the main page.

#### Manage Schedule

Path: **Store Pickup > Manage Schedule** 

![Manage Schedule](./storepickup/i30.png?raw=true)

You can see schedule that had been created in this tab and quickly edit some, or create a new one by hitting the button **Add New Schedule.**

![Manage Schedule](./storepickup/i31.png?raw=true)

(1)	Enter **Schedule Name**

(2)	Choose time and status of the store on each day (from Monday to Sunday)

(3)	Click on **Apply to all** if you the time does not change during the week

(4)	**Save Schedule** to save the change.

![Manage Schedule](./storepickup/i32.png?raw=true)

And to apply this schedule to various stores, navigate to **Stores of Schedule** to check all stores that you want to add.


#### Manage Holiday

Path: **Store Pickup > Manage Holiday.** 

![Manage Holiday](./storepickup/i24.png?raw=true)

You will be navigated to the **Manage Holiday** page listing all holidays created. Click on **Add Holiday** button to create a new one.

![Manage Holiday](./storepickup/i25.png?raw=true)

(1)	Enter the **Holiday name**

(2)	Use **Calendar** to set the holiday date range

(3)	Enter the **holiday comment** *(optional)*

![Manage Holiday](./storepickup/i26.png?raw=true)

Select store(s) that apply this holiday.

Click **Save Holiday** to save the changes


####  Manage Special Day

***Note:*** *Special days have the highest priority compared with holidays and other days. If a specific date is assigned as both store’s special day and holiday, it will be counted as special working day. The store still opens for pickup on that date but with special opening hours as you configured.*

Path: **Store Pickup > Manage Special Days.** 

![Manage Special Day](./storepickup/i27.png?raw=true)

You will be navigated to the **Manage Special Day** page listing all special days created. 

Click on the **Add Special Day** button to create a new one.  

![Manage Special Day](./storepickup/i28.png?raw=true)

(1)	Enter the **name**

(2)	Use **Calendar** to set the date range

(3)	Select open time and close time applied to **Special Day** *(optional)*

(4)	Enter **comment** *(optional)*

![Manage Special Day](./storepickup/i29.png?raw=true)

Tick all stores that you want this special day to be applied, then **Save Special Day**


#### View Pickup Orders

To view pickup orders in backend:

Path: **Sales > Operation** section **> Orders** 

![View Pickup Orders](./storepickup/i33.png?raw=true)

Click on **View** to see more detail about selling information

In the **Information** tab, you can see the information about shipping address changed to the address of pickup store and attached with a map location as below:

![View Pickup Orders](./storepickup/i34.png?raw=true)

![View Pickup Orders](./storepickup/i35.png?raw=true)


### Shipment method

Path: **Stores > Settings** Section **> Configuration > Sales > Setting > Shipping for POS**


![Shipment method](./imgpart2/it_img132.png?raw=true)

![Shipment method](./imgpart2/it_img133.png?raw=true)

If you want to apply all shipping methods, choose **All Allowed Payments in Applicable Shipping Methods** field.

![Shipment method](./imgpart2/it_img134.png?raw=true)

If you want to apply some typical payment methods only, choose **Specific Shipping.** Then in **Specific Shipping Methods** field, select payment method as your preference. Hold **Ctrl + Click** to choose more than one.

![Shipment method](./imgpart2/it_img135.png?raw=true)

**Default Payment Method:** Choose the payment method that you would want to set as default payment method. This payment method must be in **Specific Shipping Methods.**

![Shipment method](./imgpart2/it_img136.png?raw=true)

You can enable **Mark as shipped** by default.

![Shipment method](./imgpart2/it_img137.png?raw=true)

Click **Save Config** to complete the process.


### Payment 

Path: **Stores > Settings** Section **> Configuration > Sales > Setting > Shipping for POS**

![Payment ](./imgpart2/it_img138.png?raw=true)

![Payment ](./imgpart2/it_img139.png?raw=true)

If you want to apply all shipping methods, choose **All Allowed Payments in Applicable Shipping Methods** field.

![Payment ](./imgpart2/it_img140.png?raw=true)

If you want to apply some payment methods only, choose **Specific Shipping**. Then in Specific Shipping Methods field, select payment method as your preference. Hold **Ctrl + Click** to choose more than one.

![Payment ](./imgpart2/it_img141.png?raw=true)

**Default Payment Method:** Choose the payment method that you would want to set as default payment method. This payment method must be in **Specific Shipping Methods.**


### Magento – Odoo connector (Coming soon)

----------
## HOW TO MANAGE USER PERMISSION

 ![HOW TO MANAGE USER PERMISSION](./imgpart2/it_img401.png?raw=true)
 
**Only admin accessing Web POS can set up Staff permission**

###	How to manage User Roles and Users

**Note**: *Users are the one who get permission to access in the Backend*    

####	Decentralize User Roles

   Path: **System > Permission** section > **User Roles**
   	
#####	 **Manage user role**
 
![Manage user role](./imgpart2/it_img402.png?raw=true)
 
(1)	Click **Add New Role** to create new user role.

(2)	Fill out the blank with a value to search, after click **Search.**

(3)	Search user role information with keyword.

View or edit a role’s detail by clicking on each line.

#####	**Create a new user role**
 
![Create a new user role](./imgpart2/it_img403.png?raw=true)

Click **Add New Role**
 
![Create a new user role](./imgpart2/it_img404.png?raw=true)

In tab **Role Info**

Fill in all required fields 
![Create a new user role](./imgpart2/it_img406.png?raw=true)

In tab **Role Resources**

(1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

(2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

Click **Save** to complete the process.

####	Decentralize Users

#####	Manage user
 
![Manage user](./imgpart2/it_img407.png?raw=true)

(1)	Click **Add New User** to create new user.

(2)	Fill out the blank with a value to search, after click **Search**.

(3)	Search user information with keyword.

View or edit a user’s detail by clicking on each line.

#####	Create a new user
 
![Create a new user](./imgpart2/it_img408.png?raw=true)

To create new user, click **Add New User**

 
![Create a new user](./imgpart2/it_img409.png?raw=true)

In tab **User Info**, fill in the blank:

(1)	**User Name** (required)

(2)	**First Name** (required)

(3)	**Last Name** (required)

(4)	**Email** (required)

(5)	**Password** (required)

(6)	**Password Confirmation** (required)

(7)	**Interface Locale**: you can select different location.

(8)	**This account is**: Active or Inactive.

(9)	**Your Password**: fill out your password. (required).

 
![Create a new user](./imgpart2/it_img410.png?raw=true)

In tab **User Role**, select a role for user.
 
![Create a new user](./imgpart2/it_img411.png?raw=true)

In tab Warehouse, click **Assign Warehouses** to assign warehouses to this user.
 
![Create a new user](./imgpart2/it_img412.png?raw=true)

Click **Save User** to complete the process.

###	How to manage staff

####	Decentralize access permission of Web POS users

Path: **Sales > Web POS** section **> Manage Roles**

#####	Manage role
 
![Manage role](./imgpart2/it_img413.png?raw=true)

(1)	**Add Role**: Click to add a new role.

(2)	**Filters**: You can find role information by click it and fill out values.

(3)	**Action**: If you want to delete a role record, you need choose a role, then click Action and select Delete.

(4)	**Edit**: You can view role’s details (edit) by click Edit or click each line.

#####	Add a new role
 
![Add a new role](./imgpart2/it_img414.png?raw=true)

Click **Add Role** to add a new role.
 
![Add a new role](./imgpart2/it_img415.png?raw=true)

In **General** tab, fill out the blank.

(1)	**Role Name**: Enter a name for the role. (required)

(2)	**Maximum discount percent (%)**: Limit the highest discount percent that each user role can offer customers.

(3)	**Description**: Enter text that describes the role.

 
![Add a new role](./imgpart2/it_img416.png?raw=true)

In **Permission** tab.

(1)	**Resource Access**: You can choose **Custom** or **All**. Choose **All** if you want users having this role will have access to all resources, click on **Save** or **Save And Continue Edit** button to save your work.

(2)	If you choose **Custom**, you can tick to assign specific permissions for that role.

####	Decentralize staff

#####	Manage Staff

Path: **Sales > Web POS** section **> Manage Staff**
 
![Manage Staff](./imgpart2/it_img417.png?raw=true)

(1)	Click **Add Staff** to create a new staff.

(2)	Click **Filters** to search staff information.

(3)	If you want to **Delete** or **Change status** a staff, first select a staff, then click **Actions**: choose **Delete** or **Change status**.

Click **Detail** to view a staff’s details or edit.

#####	Create a new staff

Path: **Sales > Web POS** section **> Manage Staff**
 
![Create a new staff](./imgpart2/it_img418.png?raw=true)

Click **Add Staff**.
 
![Create a new staff](./imgpart2/it_img419.png?raw=true)

Fill out all the required fields or select: 

(1)	**User Name**.

(2)	**Password.**

(3)	**Password Confirmation**.

(4)	**Display Name**.

(5)	**Email Address.**

(6)	**PIN Code (App only)**.
 
![Create a new staff](./imgpart2/it_img420.png?raw=true)

(7)	**Customer Group**.

(8)	**Location**: Hold **Ctrl + Click** to choose more than one
 
![Create a new staff](./imgpart2/it_img421.png?raw=true)

(9)	**Role**.

(10)	**Status**: You can **Enabled** or **Disabled** this staff.

(11)	**POS**: Assign POS for user. To choose more than one, hold **Ctrl + Click.** 

Finally, click **Save** to complete the process.

**Brief**: IT Admin can create a new role and decentralize for all admins and staffs.
Other admins (which can be called as business managers) can only create and decentralize staffs on Sales Section (a Default Feature from Web POS). 
 
![Create a new staff](./imgpart2/it_img422.png?raw=true)

Moreover, **if** IT admin activates the **Permissions** button on **Role Resources** these admins (managers) can create roles and users within their permission. 
 
![](./imgpart2/it_img423.png?raw=true)

*Notice that: Roles on Sales Section and Roles on System Section ARE NOT synchronized.* 

**For more basic details how to set up role – user and role-staff, you can read the section below:**  

###	Basic role for each admin in the System

**Note**: For reference only! With each business feature has different roles for users. 

####	Store Manager

 
![Store Manager](./imgpart2/it_img425.png?raw=true)

Moreover, Store Manager can access to **Sales** Tab and decentralize roles for Sale Staff

####	Inventory Manager
 
![Inventory Manager](./imgpart2/it_img426.png?raw=true)

Moreover, Inventory Manager can access to **Sales** Tab and decentralize Inventory Staff

####	Purchase Manager
 
![Purchase Manager](./imgpart2/it_img427.png?raw=true)

Moreover, Purchase Manager can access to **Sales** Tab and decentralize Purchase Staff

####	eCommerce Manager
 
![eCommerce Manager](./imgpart2/it_img428.png?raw=true)

####	Accountant
 
![Accountant](./imgpart2/it_img429.png?raw=true)

---------

## HOW TO MANAGE MASTER DATA

### Product

#### Attribute

Path: **Stores > Attributes** section **> Product**

##### Manage attribute
 
![Manage attribute](./imgpart2/it_img501.png?raw=true)

(1)	Click **Add New Attribute** to create new user.

(2)	Fill out the blank with a value to search, after click **Search**.

(3)	Search attribute information with keyword.

You can view or edit attribute’s details by clicking on each line.

##### Create a new attribute

Attributes can be created while working on a product, or from the Product **Attributes** pages. The following example show how to create attributes from the Stores menu. Any attribute that is used as a drop-down list of values for a configurable product must have the following properties:


|Property|	Value| 
|---|--| 
|Catalog Input Type for Store Owner|	Dropdown|
|Scope|	Global|

 
![Create a new attribute](./imgpart2/it_img502.png?raw=true)

Click **Add New Attribute**
 
![Create a new attribute](./imgpart2/it_img503.png?raw=true)

**Basic Properties**

(1)	Enter a **Default Label** to identify the attribute

(2)	Set **Catalog Input Type** for Store Owner to the type in input control to be used for data entry

3)	Select **Yes** to require the customer choose an attribute value option

For Dropdown and Multiple Select input types, do the following:

 - Under Manage Options, click **Add Option**. 
 - Enter the first value that you want to appear in the list.
	 - Enter one value for the **Admin**, and a translation of the value for each store view.
	 - Enter only the Admin value, if you have only one store view, you can enter only the Admin value.	
 - Click **Add Option** and repeat the previous step for each option that
   you want to include in the list.
 - Select **Is Default** to use the option as the default value.

 
![Create a new attribute](./imgpart2/it_img506.png?raw=true)

**Advanced Properties** (if needed).

(1)	Enter a unique **Attribute Code** in lowercase characters, and without space.

(2)	Set **Scope** to indicate where in your store system the attribute can be used.

(3)	If you want to prevent duplicate values from being entered, set **Unique Value** to **Yes**

(4)	To run a validity test of any data entered in the text field, set **Input Validation for Store Owner** to the type of data that the field should contain. This field is not available for input types with values that are selected. The test can validate any of the following:

 - Decimal Number. 
 - Integer Number. 
 - Email.  
 - URL.  
 - Letters.  
 - Letters (a-z, A-Z) or Numbers (0-9).

(5)	**Add to Column Options**: Include the attribute as a column in the Products grid.

(6)	**Use in Filter Option**: Adds a filter a control to the column header in the Products grid.
 
![Advanced Properties](./imgpart2/it_img507.png?raw=true)

**Input Validation**.
 
![Input Validation](./imgpart2/it_img508.png?raw=true)

In tab **Manage Labels**: Enter a **Title** to be used as a label for the field. If your store is available in different languages, you can enter a translated title for each view.
 
![Input Validation](./imgpart2/it_img509.png?raw=true)

In tab **Storefront Properties**

(1)	If the attribute is to be available for search, set Use in Search to **Yes** 

(2)	To include the attribute in Product Compare, set Comparable on Storefront to **Yes**

For dropdown, multiple select and price fields, do the following: 

(3)	To use the attribute as a filter in layered navigation, set **Use in Layered Navigation** to **Yes**

(4)	To use the attribute in layered navigation on search results pages, set **Use in Search Results Layered Navigation** to **Yes**

(5)	In the **Position** field, enter a number to indicate the relative position of the attribute in the layered navigation block.

(6)	Set **Use for Promo Rule Conditions** to **Yes** to use the attribute in price rule.

(7)	To allow the text to be formatted with HTML, set **Allow HTML Tags on Frontend** to **Yes**. This setting makes the WYSIWYG editor available for the field. 

(8)	To include the attribute in catalog page listings, set **Visible on Catalog Pages on Storefront** to **Yes**

(9)	Complete the following settings if supported by your theme:

 - To include the attribute on the product detail page, set Visible on
   Catalog Pages on Storefront to **Yes**
 - To include the attribute in product listings, set Used in Product
   Listing to **Yes**

To use attribute as a sort parameter for product listings, set Used for Sorting in Product Listing to **Yes**

 
![Input Validation](./imgpart2/it_img510.png?raw=true)

When complete, click **Save Attribute**.

#### Attribute set

Path: **Stores > Attributes** section **> Attribute set**

##### Manage attribute set
 
![Manage attribute set](./imgpart2/it_img511.png?raw=true)

(1)	Click **Add Attribute Set** to create new attribute set.

(2)	Fill out the blank with a value to search, after click **Search.**

(3)	Search attribute set information with keyword.

You can view or edit details of attribute set by clicking on each line.

##### Create a new attribute set
 
![Create a new attribute set](./imgpart2/it_img512.png?raw=true)

Click **Add Attribute Set** to create new attribute set.
 
![Create a new attribute set](./imgpart2/it_img513.png?raw=true)

(1)	In the **Name** field, enter a name for the attribute set (required)

(2)	In the **Based On** field, select an existing attribute set to be used as a template:

-	Bag
-	Bottom
-	Default
-	Downloadable	
-	Gear
-	Sprite Static Ball
-	Sprite Yoga Strap
-	Top

(3)	Click **Save** button and continue

![Create a new attribute set](./imgpart2/it_img514.png?raw=true)

To add a new attribute to the set, drag the attribute from the Unassigned Attribute list to the appropriate folder in the General group.

Click **Save** to complete the process.

#### Categories

Path: **Products > Categories**

##### Manage categories

When selecting a category on the left, all the information will be displayed on the left.
 
![Manage categories](./imgpart2/it_img515.png?raw=true)

##### Create a new category

 
![Create a new category](./imgpart2/it_img516.png?raw=true)

**Create a Category**
 
![Create a new category](./imgpart2/it_img517.png?raw=true)

Path: **Products > Inventory** section **> Categories**

Set Store View to determine where the new category is to be available. In the category tree, tap the parent category of the new category. The parent is one level above the new category.

If you’re starting from the beginning without any data, there might be only two categories in the list: **Default Category**, which is the root, and an **Example Category**. 

Click **Add Sub-category** to add a new category.
 
![Create a new category](./imgpart2/it_img518.png?raw=true)

**Complete the Basic information**

(1)	If you want the category to be immediately available in the store, set **Enable Category** to the **Yes** position.

(2)	To include the category in the top navigation, set Include in Menu to the **Yes** position.

(3)	Enter the **Category Name**.

(4)	Click **Save**.
 
![Create a new category](./imgpart2/it_img519.png?raw=true)

Complete the Category Content

(1)	To display a Category Image at the top of the page, tap **Upload**. Then, choose the image that you want to represent the category.

(2)	In the **Description** box, enter the text that you want to appear on the category landing page. Then, format the text as needed.

(3)	To include a content block on the category landing page, choose the CMS Block that you want to appear. 

(4)	Click **Save**.
 
![Create a new category](./imgpart2/it_img520.png?raw=true)

Complete the **Display Settings**

Expand the **Display Settings** section.

(1)	Set Display Mode to one of the following:

 - Products Only.
 - Static Block Only.
 - Static Block and Products.

(2)	If you want the category page to include the **Filter by Attribute** section of layered navigation, set Anchor to the **Yes** position.

(3)	To change the Available Product Listing Sort By options, do the following: 
 - Clear the **Use All checkbox**. 
 - Select one or more of the available values to be available for customers to sort the list. By default, all available values are included. For example, the values might include:
 - Position.
 - Product Name.
 - Price 5
 
(4)	To set the default sort order for the category, choose the **Default Product Listing Sort By value**.

(5)	To change the default layered navigation price step setting, do the following:
-	Clear the **Use Config Settings** checkbox.
-	Enter the value to be used as an incremental price step for layered navigation.

6)	Click **Save**.
 
![Create a new category](./imgpart2/it_img521.png?raw=true)

Complete the **Search Engine Optimization Settings**

Expand the Search Engine Optimization Settings section.

(1)	Enter a URL Key for the category, or let the system automatically create one that is based on the category name.

Complete the following meta data for the category:

(2)	Meta Title.
(3)	Meta Keywords.
(4)	Meta Description.

Click **Save**.
 
![Create a new category](./imgpart3/it_img522.png?raw=true)

Choose the **Products** in **Category**
Expand the Products in Category section. Then, use one of the following methods to add products to the category. 

To find the products:

(1)	Fill out the blank with a value.

(2)	Click Search to find the products.

To include a product in the category. 

(3)	Mark the checkbox of each product, in the first column.

(4)	Click **Save**.

#### Product types

Path: **Products > Catalog**

#####	Product Types

|Product Types|	Description|
|----|---|
|Simple Product|	A simple product is a physical item with a single SKU. Simple products have a variety of pricing and of input controls which makes it possible to sell variations of the product. Simple products can be used in association with grouped, bundle, and configurable products.|
|Configurable Product|	A configurable product appears to be a single product with lists of options for each variation. However, each option represents a separate, simple product with a distinct SKU, which makes it possible to track inventory for each variation.|
|Grouped Product|	A grouped product presents multiple, standalone products as a group. You can offer variations of a single product, or group them for a promotion. The products can be purchased separately, or as a group.|
|Virtual Product|	Virtual products are not tangible products, and are typically used for products such as services, memberships, warranties, and subscriptions. Virtual products can be used in association with grouped and bundle products.|
|Bundle Product|	A bundle product let customers “build their own” from an as sort of options. The bundle could be a gift basket, computer, or any things else that can be customized. Each item in the bundle is a separate, standalone product.|
|Downloadable Product|	A digitally downloadable product that consists of one or more files that are downloaded. The files can reside on your server or be provided as URLs to any other server.|


##### Manage products

Path: **Products > Catalog**
 
![Manage products](./imgpart3/it_img523.png?raw=true)

**Workspace Controls**

(1) **Add Product**: Initiates the process to create a new simple product. 

To choose a specific product type, click the down arrow. 

There are two options: **Simple Product** and **Configurable Product** (Grouped Product, Virtual Product,Bundle Product,Downloadable Product)

(2) **Action**:	Lists all actions that can be applied to selected products in the list. To apply an action to a product or group of products, mark the check box in the first column of each product. Options:	**Delete, Change,  Status, Update Attributes**

(3) **Filters**:Initiates a catalog search based on the current filters.

(4) **Edit**: Opens the product in edit mode or view product’s detail. You can accomplish the same thing by clicking any where on the row.

 

#####	Create a new product

**a/ Simple product**

![Add Simple Product](./imgaddition/im1.png?raw=true)

In the upper-right corner on the **Add Product** menu, choose **Simple Product**.

![Choose attribute set](./imgaddition/im2.png?raw=true)

Choose the attribute set that is used as a template for the product.


![Fill in required setting](./imgaddition/im3.png?raw=true)

**Complete the required setting**

(1)	Enter **Product Name** (required)

(2)	The default **SKU** that is based on the product name, or enter another.

(3)	**Price** - enter the product price.

Then, Click **Save** to continue.

![Complete New Product basic settings](./imgaddition/im4.png?raw=true)

**Complete the basic settings**

(1)	Set **Tax Class** to one of the following: **Taxable Goods**/**None**

(2)	Enter the **Quantity** of the product that is currently in stock. 

(3)	By default, **Stock Status** is set to **In Stock**

(4)	Enter the **Weight** of the product.

(5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click on **New Category**

(6)	Accept the default Visibility setting, **Catalog, Search**

(7)	Mark the Set Product as **New checkbox** to add the product in the list of new products.

(8)	Choose the **Country of Manufacture**.

(9)	**Enable** On Web POS

Then, click **Save** to continue

![List of product information](./imgaddition/im5.png?raw=true)

**Complete the product information**

Scroll down and complete the information in the following sections as needed:

 * Content
 
 * Configurations
 
 * Images and Videos
 
 * Search Engine Optimization
 
 * Related Products, Up-Sells, and Cross-Sells
 
 * Customizable Options
 
 * Products in Websites
 
 * Design
 
 * Schedule Design Update 
 
 * Downloadable Information 
 
 * Barcode
 
 * Suppliers

**b/Configurable product**

Create a new configurable product

![Add Configurable Product](./imgaddition/im6.png?raw=true)

In the upper-right corner on the **Add Product** menu, choose **Configurable Product**

![Choose the attribute set](./imgaddition/im7.png?raw=true)

Choose the attribute set that is used as a template for the product.

![Complete Product Name, SKU and Price](./imgaddition/im8.png?raw=true)

**Complete the required setting**

(1)	Enter **Product Name**. (required)

(2)	The **default SKU** that is based on the product name, or enter another.

(3)	Enter the product **Price**.

(4)	Click **Save** to continue.

![Complete basic setting](./imgaddition/im9.png?raw=true)

**Complete the basic settings**

(1)	Set **Tax Class** to one of the following:

 - **None**.
 
 -  **Taxable Goods**.

(2)	Enter the **Quantity** of the product that is currently in stock. 

(3)	By default, **Stock Status** is set to **In Stock**.

(4)	Enter the **Weight** of the product.

(5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click **New Category**

(6)	Accept the default Visibility setting, **Catalog, Search**

(7)	To feature Mark the Set Product as **New checkbox** to add the product in 
the list of new products.

(8)	Choose the **Country of Manufacture**.

(9)	**Enable** on Web POS

Then, click **Save to continue**.

![List of Product Information](./imgaddition/im10.png?raw=true)

Complete the product information.

**Adding configurations**

![Configuration Explanation](./imgaddition/im11.png?raw=true)

After creating a product, scroll down the **Configuration** section > Click **Create Configurations**

![Product Configuration Creation](./imgaddition/im12.png?raw=true)

**Choose the attributes**

(1)	Mark the checkbox of each attribute that you want to include as a configuration.

(2)	Add a new attribute.

(3)	Click **Next** to continue.

![Product Configuration Creation Step 2](./imgaddition/im13.png?raw=true)

For each attribute, mark the checkbox of the values that apply to the product.

Click **Next** to continue

![Product Configuration Creation Step 3](./imgaddition/im14.png?raw=true)

Configure the **Images**, **Price**, and **Quantity**.

Click **Next** to continue.

You will see list product.

![Product Configuration Creation Step 4](./imgaddition/im15.png?raw=true)

Click **Next** to finish the process.

**c/Grouped product**

In the upper-right corner on the **Add Product**   menu, choose **Grouped Product**.

![Grouped Product Listing](./imgaddition/im16.png?raw=true)

Choose the attribute set that is used as a template for the product.

![Fill required information](./imgaddition/im17.png?raw=true)

**Complete the required setting**

(1)	Enter **Product Name** (required)

(2)	The default **SKU** that is based on the product name, or enter another.

(3)	Enter the **Quantity** of the product that is currently in stock 

Then, Click **Save to continue**.

![Basic Settings for Grouped Product](./imgaddition/im18.png?raw=true)

**Complete the basic settings**

(1)	By default, Stock Status is set to **In Stock**

(2)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by click **New Category**

(3)	Accept the default Visibility setting, **Catalog, Search**.

(4)	To feature Mark the Set Product as **New checkbox** to add the product in the list of new products.

(5)	Choose the **Country of Manufacture**.

(6)	**Enable** on Web POS

Then, click **Save to continue**.

**Add products to Group**

![Add Products to group Explanation](./imgaddition/im19.png?raw=true)

![Add Selected Products](./imgaddition/im20.png?raw=true)

(1)	Select **product** that you want to include in the group.

(2)	Click **Add Selected Products** to add them to group.

![Grouped Products Action Button](./imgaddition/im21.png?raw=true)

(1)	Enter a **quantity**.

(2)	**Remove** a product from group.

Click **Save** to finish the process.

![List of Product Information](./imgaddition/im22.png?raw=true)

Complete the product information

**d/Virtual product**

Aside from the absence of the **Weight** field, the process is as mentioned above.

**e/Bundle product**

![Add Bundle Product](./imgaddition/im23.png?raw=true)

In the upper-right corner on the **Add Product**   menu, choose **Bundle  Product**

![Fill required fields in attribute setting](./imgaddition/im24.png?raw=true)

Choose the attribute set that is used as a template for the product

![Fill required setting](./imgaddition/im25.png?raw=true)

**Complete the required setting**

(1)	Enter **Product Name**. (required)

(2)	The default **SKU** that is based on the product name, or enter another.

(3)	Enter the product **Price**.

Then, Click **Save to continue**.

![Fill basic setting for Bundle Product](./imgaddition/im26.png?raw=true)

**Complete the basic settings**

(1)	Enable **Dynamic Price**

(2)	Set **Tax Class** to one of the following:

•	**None**

•	**Taxable Goods**

(3)	Enter the **Quantity** of the product that is currently in stock. 

(4)	By default, Stock Status is set to **In Stock**

(5)	Enter the **Dynamic Weight** of product.

(6)	Assign **Categories** to the product. Tap the **Select** to select available category or you can create new category by clicking on  **New Category**

(7)	Accept the default **Visibility** setting, **Catalog, Search**

(8)	To feature Mark the **Set Product as New** checkbox to add the product in the list of new products.

(9)	Choose the **Country of Manufacture**.

(10)	**Enable** on Web POS

Finally, click **Save** to continue.

![Ship Bundle Items](./imgaddition/im27.png?raw=true)

Add **Bundle items**

Scroll down to the **Bundle Items** section. Then, set **Ship Bundle Items** one of the following:

1.	**Separately**

2.	**Together**

Click **Add Option**

![Bundle Item Information](./imgaddition/im28.png?raw=true)

(1)	**Option Title** to be used field label.

(2)	Set **Input Type** to one of the following:

•	Drop-down.

•	Radio buttons.

•	Checkbox.

•	Multiple Select.

(3)	Mark to make the field a **required** entry.

(4)	Tap **Add Products to Option**, then mark the checkbox of each product that you want to include in this option.

![Add Selected Products](./imgaddition/im29.png?raw=true)

Mark the checkbox of each product.

Click **Add Selected Products**, you will see.

![Enter the default quantity](./imgaddition/im30.png?raw=true)

(1)	Mark the checkbox of a product that you want it is default.

(2)	Enter **Default Quantity**.

Finally, click **Save**.

![List of Bundle Product](./imgaddition/im31.png?raw=true)

Complete products information

**f/Downloadable product**

![Add Downloaded Products](./imgaddition/im32.png?raw=true)

In the upper-right corner on the **Add Product**   menu, choose **Downloadable Product**.


![Choose Attribute Set](./imgaddition/im33.png?raw=true)

Choose **Downloadable** as the **attribute set**

![Fill in required setting](./imgaddition/im34.png?raw=true)

**Complete the required setting**

(1)	Enter **Product Name** (required)

(2)	The default **SKU** that is based on the product name, or enter another

(3)	Enter the product **Price**

Then, Click **Save** to continue.

![Complete basic settings](./imgaddition/im35.png?raw=true)

**Complete the basic settings**

(1)	Set **Tax Class** to one of the following:

•	None.

•	Taxable Goods

(2)	Enter the **Quantity** of the product that is currently in stock. 

(3)	By default, **Stock Status** is set to **Out of Stock**.

(4)	The **Weight** is not used, because downloadable products are not 
shipped.

(5)	Assign Categories to the product. Tap the **Select** to select available category or you can create new category by clicking on  **New Category**

(6)	Accept the default Visibility setting, **Catalog, Search**.

(7)	To feature Mark the Set Product as **New checkbox** to add the product in 
the list of new products.

(8)	**Enable** on Web POS

Then, click **Save** to continue.

![Downloadable Information](./imgaddition/im36.png?raw=true)

**Complete downloadable product**.

(1)	Mark the checkbox **Is this downloadable product**

(2)	Enter the **Title** - to use as a heading for the download links.

(3)	Click **Add Link**, then:
          
 Enter **Title** and **Price**. For both **File** and **Sample files**, choose:

•	**Upload File**: To upload the the distribution file to the server. Browse to the file, and select it for upload.

•	**URL**: To access the distribution file from a URL. Enter the full URL to the download file.

![Sample Setting](./imgaddition/im37.png?raw=true)

**Complete the Sample**

(1) Enter the **Title** - to use as a heading for the samples.

(2) Enter the **Title** of the individual sample.

(3) Choose **distribution methods**.

(4) Click **Add Link** to add another sample.

When complete, click **Save**.

![List of product information](./imgaddition/im38.png?raw=true)

Complete the product information


##### Product settings

**a)	Content**
 
![Product settings](./imgpart3/it_img563.png?raw=true)

(1)	Click on **Products**

(2)	Click on **Catalog**

(3)	Click on **Edit**
 
![Product settings](./imgpart3/it_img564.png?raw=true)

Scroll down to **Content**, and click on  , then write the description for the product, and the click **Save** on top right of the screen

**b)	Images and Videos**
 
![Product settings](./imgpart3/it_img565.png?raw=true)

 - Click on **products**
 - Click on **catalog**
 - Click on **edit** of product

![Product settings](./imgpart3/it_img566.png?raw=true)

Scroll down to **Images And Videos**, and click on  , then click on **Browse to find or drag image here to upload new image**
 
![Product settings](./imgpart3/it_img567.png?raw=true)

Click on **Add Video** to add new video
 
![Product settings](./imgpart3/it_img568.png?raw=true)

Fill in the box and the click on **Choose File** to upload new video
 
**c)	Search Engine Optimization**
 
![Search Engine Optimization](./imgpart3/it_img569.png?raw=true)

 - Click on **Products**
 - Click on **Catalog**
 - Click on **Edit** of product

![Search Engine Optimization](./imgpart3/it_img570.png?raw=true)

Scroll down to search **Engine Optimization,** and click on  , then fill in the box

**d)	 Related Products, Up-sells and Cross-sells** 
 
! [Related Products, Up-sells and Cross-sells](./imgpart3/it_img571.png?raw=true)

o	Click on respectively
1.	**Add Related Products**
2.	**Add Up-sell Products**
3.	**Add Cross-sell Products**

 
![Related Products, Up-sells and Cross-sells](./imgpart3/it_img572.png?raw=true)

(2)Mark the checkbox to select products

(3)Click on **Add Selected Product**
 
![Related Products, Up-sells and Cross-sells](./imgpart3/it_img573.png?raw=true)

Click on **Save** to finish

 
**e)	Customizable Options**
 
![Customizable Options](./imgpart3/it_img574.png?raw=true)

This function allows users to set and manage extra price for each product's variant separately.

Users can simply set the extra price to be applied on a product's variant, regardless of its attribute and attribute value.

(1)	Click on **Add Option**

(2)	Enter the **option tittle**

(3)	Select an **option type** 

(4)	Mark the checkbox to require 

(5)	Click on **Add Value**

(6)	Enter a title for the value

(7)	Enter an **extra price**

(8)	Select a **price type**

(9)	Enter an **SKU** for each product’s variant

To remove a value, click  on the right hand-side of the column 

**f)	Gift Option**
 
![Gift Option](./imgpart3/it_img575.png?raw=true)

 - Click on **Products**
 - Click on **Catalog**
 - Click on **Edit of a product**

 
![Gift Option](./imgpart3/it_img576.png?raw=true)

Scroll down to **Gift Option**, and click  on  , then set the allow gift massage to **Yes**

**g)	Downloadable Information**
 
![Downloadable Information](./imgpart3/it_img577.png?raw=true)

(1)	Mark the checkbox

(2)	Enter a title for the download link

(3)	Mark the checkbox (if applicable)

(4)	Click “**Add Link**”, then do the following:

(5)	Enter a title for the download

(6)	Enter a number as a price for the download

(7)	Select an upload method for a file **(Upload File/ Use URL)**

(8)	Select an upload method for a file **(Upload File/ Use URL)**

(9)	Select a label in the dropdown list: 

 - **No**: to requires customers to log in to their accounts to access the
   download link.
 - **Yes**: Sends the link by email, which customers can share with others.

**Uses Config**: Uses the method that is specified in the Dowloadable Product Options configuration. 

(10)	Enter the number of **Max. downloads** to limit downloads per customer. 

Otherwise, to allow unlimited downloads, mark the **Unlimited checkbox**

**h)	Barcode**
 
![Barcode](./imgpart3/it_img578.png?raw=true)

-	Enter barcode 
-	Select a barcode template and see the preview as below 
-	Enter the quantity to print out
-	Click on **Save** to finish

**i)	Suppliers**
 
![Suppliers](./imgpart3/it_img579.png?raw=true)

 
![Suppliers](./imgpart3/it_img580.png?raw=true)

(1)	Click on **Add Supplier**

(2)	Mark the checkbox to select suppliers

(3)	Click on **Add Selected Supplier**
 
![Suppliers](./imgpart3/it_img581.png?raw=true)

(4)	Enter the **Supplier SKU, Cost, Tax**

(5)	Click **Save** to finish

### Customers

#### How to manage customers

Path: **Customer > All customers**

##### 	Manage customers

![Manage customers](./imgpart3/it_img582.png?raw=true)

(1)	Click **Add New Customer** to create new customer.

(2)	Click **Filters** or fill out key word to search customer information.

(3)	**Action:** First, select a customer, then you can:
•	Delete
•	Subscribe to Newsletter.
•	Unsubscribe from Newsletter.
•	Assign a Customer Group.
•	Edit

(4)	Click **Edit** to view customer’s details and edit.


#### Create a new customer

![Create a new customer](./imgpart3/it_img583.png?raw=true)

Click **Add New Customer.**

![Create a new customer](./imgpart3/it_img584.png?raw=true)

Fill out all the required fields with information of a customer.

•	Associate to Website.

•	Group.

•	First Name.

•	Last Name.

•	Email.

![Create a new customer](./imgpart3/it_img585.png?raw=true)

Click **Save Customer** to complete the process.

### Partner (Vendor/Delivery)

#### How to manage supplier

##### How to create a new supplier

Path: **Purchase Management > Supplier** section **> Manage Suppliers**

![How to create a new supplier](./imgpart3/it_img586.png?raw=true)

*On the screen listing suppliers:*

(1)	Click on **Add New Suppliers** to create a new supplier’s contact

![How to create a new supplier](./imgpart3/it_img587.png?raw=true)

(2)	Fill in all the required fields, including: 

•	**Supplier Code** (self-customized)

•	**Supplier Name**

•	**Contact Person** (who represents the supplying firm)

•	 **Supplier’s Email**

(3)	Choose **Enable** to activate the suppliers.

![How to create a new supplier](./imgpart3/it_img588.png?raw=true)

*Scroll down to fulfil the following stages:*

(4)	Fill in detailed information of supplier in **Supplier Address** tab.

(5)	If you enable Drop-ship function in Settings, the **Password Management** section will be automatically synchronised and shown in the **New Password** blank. You can set password and **email it to the supplier.** The supplier can use his email address and this password to log in on the **Supplier** page in frontend to update drop shipments’ status.

(6)	Click on **Save** to finish.


##### 	Add products to suppliers 

![Add products to suppliers](./imgpart3/it_img589.png?raw=true)

On the extended screen named **Products**:

(1)	Click on **Add Product** to select and assign specific products to suppliers.

(2)	Besides that, you can either Click on **Import Product** to sync your products data with Magento systems.

(3)	Enter **Supplier SKU** for each product line.

(4)	Enter **Cost** – purchase cost from the suppliers.

(5)	Enter **Tax** *(if any)*

(6)	Click on **Delete** to remove unexpected products

(7)	Click on **Save** to finish


##### Edit an existing supplier

Path:  **Purchase Management > Supplier** section **> Manage Suppliers**

![Edit an existing supplier](./imgpart3/it_img590.png?raw=true)

Click on **View** to access the supplier’s detailed information. Then start editing.


##### Manage Pricelist 

Path: **Purchase Management > Supplier** section **> Manage Pricelist**

Pricelist Management provides users lots of benefits mentioned as below:

•	Easily keep track of all users’ prices

•	Create group pricelists 

•	Create pricelists for each supplier

•	Special prices are applied when creating purchase orders

•	Create pricelists in multiple currencies

![Manage Pricelist](./imgpart3/it_img591.png?raw=true)

(1)	Click on **Add Pricelist** to make a document listing multiple prices.

***Note:** You also can prepare a Pricelist on your device then import it to system by tabbing **Import Pricelist.***

![Manage Pricelist](./imgpart3/it_img592.png?raw=true)

(2)	Select a supplier (require)

(3)	Click on **Select Product** then on the pop-up screen, choose which products you want to manage pricelist

(4)	Enter the Minimal Quantity 

(5)	Enter the cost for each product line

(6)	Set a specific opening and closing date (term of validity)

(7)	Click on **Add Selected Product(s)** to finishing

***Note:*** *Before completing, you can click on “Remove” to scratch out unexpected products.*


##### Edit a pricelist 

Path: **Purchase Management > Supplier** section **> Manage Pricelist**

![Edit a pricelist](./imgpart3/it_img593.png?raw=true)

(1)	Make double clicks on the label **Product SKU**

(2)	Edit the data you want to re-new

(3)	Click on **Save** to finalize


#### How to manage delivery partner 

Path: **Stores > Setting** section > **Configuration > Sales > Shipping Method**

![How to manage delivery partner](./imgpart3/it_img594.png?raw=true)

Click on the button and start to configure the data needed (flat rate, delivery partners, …)

![How to manage delivery partner](./imgpart3/it_img595.png?raw=true)

Edit each line in **flat rate**, then click on the box next to that line after finishing (E.g: choose **Yes** in the first line to enable flat rate, change the price in the fifth line)

![How to manage delivery partner](./imgpart3/it_img596.png?raw=true)

Edit each line in **web POS shipping**, (E.g: choose **Yes** in the first line to enable web POS shipping, change the price in the bottom line)

 ![How to manage delivery partner](./imgpart3/it_img597.png?raw=true)

Edit each line in **free shipping**, then click on the box next to that line after finishing (E.g: choose **Yes** in the first line to enable flat rate, Choose the country to apply free shipping in the 6th and 7th  line)

![How to manage delivery partner](./imgpart3/it_img598.png?raw=true)

Edit each line in the **table rate**, then click on the box next to that line after finishing. 
Eg: choose **Yes** in the first line to active the function

![How to manage delivery partner](./imgpart3/it_img599.png?raw=true)

Edit each line of the session of each Delivery partner ( UPS, UPSS, FedEx, DHL)

![How to manage delivery partner](./imgpart3/it_img600.png?raw=true)

Click on **Save Config** to save all the changes and configurations

### Warehouse

#### How to create a new warehouse 

Path: **Inventory Management > Stock Listing** section **> Warehouses**

![How to create a new warehouse](./imgpart3/it_img601.png?raw=true)

The admin user with full **access permissions** in Role Resources 
**(System → Permissions →Roles)** creates new warehouses.

Click on **Add a new warehouse** at the top-right corner

![How to create a new warehouse](./imgpart3/it_img602.png?raw=true)

![How to create a new warehouse](./imgpart3/it_img603.png?raw=true)

**General Information**

Fill in all the required fields with information of a warehouse.

•	Fill in the **Warehouse Name**

•	Fill in the **Warehouse Code** to distinguish your current warehouse from other Warehouses created before. 

•	Choose:

(1)	**Create a new location** to link POS Location to a warehouse.

(2)	And vice versa **Don’t associate to Location** 

Click on the **Arrow Button**, then choose **Save and Continue**

![General Informatio](./imgpart3/it_img604.png?raw=true)

*On the pop-up screen:*

•	Click on **Delete Warehouse** to delete the warehouse (only applied for inactive warehouse)

•	Click on **Back** to go back to previous page

### Warehouse Master Data

Path: **Inventory Management > Stock Listing** section **> Warehouses**

![Warehouse Master Data](./imgpart3/it_img605.png?raw=true)

Admin Users want to check the master data. 

Follow the path then on the pop-up screen, click on **View** to see the warehouse’s detailed information.

![Warehouse Master Data](./imgpart3/it_img606.png?raw=true)

On the right side of each master data tab, click on the Arrow button 
to access the data:

(1) **General information** about the Warehouse

(2) Illustrating the amount of goods that the warehouse has available at that time.

(3) Showing the opening and closing data between dates, such as: purchases made, sales order totals, external transfer and internal transfer (send stock) and returned items.

(4) Managing the warehouse permission 

(5) Reports are illustrated as table and lines diagrams.

#### Warehouse Permission

Path: **Inventory Management > Stock Listing** section **> Warehouses**

![Warehouse Permission](./imgpart3/it_img607.png?raw=true)

After created a warehouse, Admin Users give different warehouse access permissions to different (admin) users.

Click on **View** to see the warehouse’s detail information 

![Warehouse Permission](./imgpart3/it_img608.png?raw=true)

(9) On the right side of **the   Warehouse Permission** tab, click on **(0) Assign Staff** to give different warehouse access permissions.

*Then will be a new pop-up screen shown as below:*

![Warehouse Permission](./imgpart3/it_img609.png?raw=true)

Select Staff users to assign permission

(1)Select Staff by marking the checkbox

(2)Click on **Filters** to search Staff information *(if any)*

(3)Click on **Add Selected Staff**

![Warehouse Permission](./imgpart3/it_img610.png?raw=true)

(4)Then click on **Save Staff Permissions**


### Location

#### Add a new location

Path: **Sales > Web POS** section > **Manage Locations**

![Add a new location](./imgpart3/it_img611.png?raw=true)

(1)Click on **Add Location** to create new locations

(2)*Additional Guidance:* Click on **Edit** to amend existing locations’ information.

![Add a new location](./imgpart3/it_img612.png?raw=true)

*On the pop-up screen:*

 - Fill in the Location Name (required) 
 - Fill in the location Address field 
 - Fill in the location Description field
 - Choose the corresponsive Warehouse
 - *Additional Guidance:* In the 4th stage, you can either choose an existing warehouse or create a new warehouse.

Click on **Save**

#### Mapping Locations – Warehouses

Path: **Sales > Web POS** section **> Manage Locations**

In this phase, you can change the link between your current locations and current warehouses by mapping your locations to other warehouses.

![Mapping Locations – Warehouses](./imgpart3/it_img613.png?raw=true)

On the pop-up screen, click on **Mapping Locations – Warehouses**

![Mapping Locations – Warehouses](./imgpart3/it_img614.png?raw=true)

(1)Click on **Choose Location**

![Mapping Locations – Warehouses](./imgpart3/it_img615.png?raw=true)

*On the pop-up screen:*

(2)Use **Filters** to search location data.

(3)Select the location by mark the checkbox.

(4)Click on **Add Selected Locations**

![Mapping Locations – Warehouses](./imgpart3/it_img616.png?raw=true)

(5)Select an appropriate Warehouse

(6)Click on **Remove** to delete the location

(7)Finally, **Save** all the changed information

### Store (POS)

#### Create a new Web POS

![Create a new Web POS](./imgpart3/it_img617.png?raw=true)

Click **Add POS**

![Create a new Web POS](./imgpart3/it_img618.png?raw=true)

Fill out or select all the required fields.

(1)**POS Name:** POS’s name. *(required)*

(2)**Location:** POS’s location. *(required)*. Here, admin can choose the location created and mapped to Warehouse. So that, the admin can control both warehouse and location easily.

(3)**Store View:** *(required)*

(4)**Current Staff:** Staff is working on the POS.

(5)**Status:** you Enable or Disable this POS

(6)**When checked:** another staff can use the POS when it is available.

![Create a new Web POS](./imgpart3/it_img619.png?raw=true)

Click **Save** to complete the process.

***Note:*** *Even when you set the warehouse to a certain location, with online store, admin can see clearly any warehouse information in any locations. HOWEVER, with offline store, only Sale Manager can view the warehouse information only in the mapped location.*

*IT Admin can give other admin permission to view the Inventory information in any location by going to System > User Roles > Add new role or Edit role > Role Resource, then choosing Order Success > Inventory Management > View Warehouse Information (this is the most basic step. With each business, the process will be expanded)*


#### Manage Web POS

Path: **Sale > Web POS** section **> Manage POS**

![Manage Web POS](./imgpart3/it_img620.png?raw=true)

(1)	Click **Add POS** to create new POS.

(2)	Click **Filters** to search POS information.

(3)	If you want to delete a POS, first select a POS, then click **Actions: choose Delete.**

(4)	Click **Detail** to view a POS’s details or edit.

--------------
**_Confidential Information Notice_** 

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
