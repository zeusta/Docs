#  IT CONFIGURATION - USER GUIDE FOR MAGENTO 1


--------

## INTRODUCTION


This guide will help you – an IT Manager – to configure a successful strong system for the retailers and support you to activate the most suitable features for the business. Through the guide, you will understand how Omni-channel company will be built and work with MageStore packages. Moreover, you will get basic knowledge about how you can decentralize roles, users and staffs for your company.

With this guide, hope that you can transform your business into a true [Omnichannel Retail](https://www.magestore.com/omnichannel-retail?) business easily and quickly. 

--------

## HOW TO INSTALL


1.	After purchasing a module, you will receive an email that includes the link to access **My License Certificates** on MageStore website. If you don’t receive the email, you can directly login to your account dashboard at MageStore then go to **My Account/My License Certificates**. Here you will select your **Order number** and a corresponding **Product** then type the **back-end domain of your live site**. It is optional to add your Development Domains right or later. Click on the **Generate Certificate** button to get your **License Certificate.**

***Note:*** **License Certificate** is a PDF document that contains your License Information including your Product Name, License Serial, License Type, Registered Domain, Expiration date, etc. Your **License Serial** is unique and can only be used once for one module. You can go to MageStore **Check License Information** page, enter your License Serial to check your license status. You can also view your License Information in back-end when your module installation is finished.

2.	Go to **My Downloadable Products**. Choose the version of the module then download it. The file that you download is normally a zip file.

3.	It’s required to enable cache in the administration panel of your site. Go to **System/Cache Management**. Choose all caches and click on **Enable** then submit.

4.	Use FTP client (such as Filezilla, WinSCP, cuteFtp) to upload or copy all folders in the zip package to your Magento site root folder. This will not overwrite any existing file; just add new files to the folder structure.

5.	After uploading is done, log in your Magento administration panel to refresh cache. Go to **System/Cache Management**. Select all caches and take action **Refresh** then submit.

6.	Navigate to **System/Configuration**. If you can see the module tab, it is installed properly.

7.	Now if you get access denied error when click on the module tab, you need to log out admin panel and log in again.

8.	Go to front-end and try to process, make sure that everything is OK.

***Note:*** In the case that you have followed all above steps but couldn’t make the module work properly, to make your website function as normal, you can delete the file or change the module’s filename module in **app/etc/magestore_module_name.xml** (for example, change **Magestore_Affiliateplus.xml** to **Magestore_Affiliateplus.xml.bka** ). Then please contact us at support@magestore.com, our supporters will assist you in resolving any issues within 24 hours.

-----


## HOW TO CONFIGURE


### Multi-companies (Coming soon)


### Inventory Management 


Path: **Inventory Management > Settings**

![Inventory Management Path](./imgpart1/i1.png?raw=true)

Then you will access to a page as below:

![Stock Control Configuration](./imgpart1/i2.png?raw=true)

(1)	**Link warehouse  to Magento Front Store View**: The Inventory Management module allows synchronization between the warehouse and its Magento front store. It means when you edit information or product quantity of a warehouse, the information will automatically be updated in that warehouse’s front store and visible to customers.

![Link warehouse to front-store view](./imgpart1/i3.png?raw=true)

After enabling this setting, you can link the warehouse to one or multiple store view in **Stock Listing > Warehouses >** Click **View > Warehouse Information** section **> General Information > Magento Store View**

(2) **Adjust Stock by entering the change qty:** 

- If this feature is **enabled**, when adjusting stock, you can enter the difference quantity and the system will calculate the final balance in warehouse.

-  If this feature is **disabled**, you need to enter the exact quantity of stock in warehouse and the system will receive this figure as the latest available quantity of product.


### Web POS

![Web POS Path](./imgpart1/i4.png?raw=true)

(1)	If you want to find the taskbar **Magento Admin Panel**, you can click on that black button

(2)	Path: **Sales > Web POS > Settings**


#### General Configuration


![POS General Configuration](./imgpart1/i5.png?raw=true)

(1)	**Web POS logo:** Click on **Choose File** to upload your Website Logo. 
Recommended image size: 260x120 px and supported file: jpeg, png

(2)	**Web POS Color:** Enter the **Hex Code** of your Web color

(3)	**Enable Cash Drawers:** Choose **Yes** to enable **Cash Drawers** 

(4)	**Enable Delivery Date:** Choose **Yes** to enable **Delivery Date**

(5)	**Allow to sync orders out-of-stock items:** Choose **Yes** to sync orders of out-of-stock items

(6)	**Session Timeout:** Enter the number of seconds

(7)	**Integrate with Pole Display device:** Choose **Yes** to integrate with 
**Pole Display** Device. You should install Customer Pole Display’s Driver. After that, you need to install the desktop application to connect your PC/ Laptop with the pole. 

***Notes:*** after purchasing Magento Omni-channel Module, you can download the Pole Display integration file which contains these following files & folders:


![POS Connection Files](./imgpart1/i6.png?raw=true)

Then follow these steps:

•	**Step 1:** Install the .NET Framework 4.5.2

-	Open the folder .NET Framework 4.5.2

-	Run NDP452-KB2901907-x86-x64-AllOS-ENU.exe file and install it to your 
computer.

•	**Step 2:** Install the USB to Serial COM setup:

-	Open the folder USB to Serial COM

-	Run CDM21224_Setup.exe and install it to your computer

•	**Step 3:** Run the Pole Integration.exe file:

![POS Run File](./imgpart1/i7.png?raw=true)

You need to open this program when using Web POS to use Customer Pole Display.

(8)	**Default Website:** Choose your **Default Website**

(9)	**Need to confirm before deleting order (App only):** If you use Web POS App on mobile or tablet, choose **Yes** to allow a **Confirmation Pop-up** that you want to delete order

(10)	**Need to create session before working (App only):** With Web POS App 
users, chose **Yes** to activate creating session before working

(11)	**Active Key for using App:** Enter your **activation code** to use Web POS App


#### Shipping for POS


![Shipping for POS](./imgpart1/i8.png?raw=true)

(1)	**Offline shipping Methods:** Choose **Offline shipping methods** that you offer for your customer, including: **Fixed Flat Rate, Free Shipping, Store Pickup, Custom Method**

(2)	**Default Shipping Method:** Choose **Default Shipping Method.** There are various options for you to choose. If you don’t have any, choose **None**


#### Payment for POS


![Payment for POS](./imgpart1/i9.png?raw=true)

(1)	**Applicable Payments:** If you choose 

-	**Specific Payments**, a **Specific Payments** field will appear for you to choose your preferred payments. 

-	**All Allowed Payments**, then you allow all payments on the POS (the **Specific Payments** field will NOT appear)

(2)	**Default Payment Method:** Choose **Default Payment Method**. If you don’t have any, choose **None** 
If you also use **Web POS App** on mobile and tablet, notice these steps:

(3)	**Allow Customer pay via PayPal:**

-	If you choose **No**, then your customers cannot pay via PayPal service

-	If you choose **Yes**, then

![PayPal Integration App Only](./imgpart1/i10.png?raw=true)

[1] Enter your application **Client ID** and your **Application Client Secret**

[2] Choose **Yes** to activate **Sandbox Mode** for better security

[3] Choose **Yes** to allow **PayPal Here** on Web POS

(4) **Redirect URL:** redirect your byers back to your website after completing the payment.

You need to sign in your PayPal account.  Then, select **Profile > Profile and Settings > My setting tools >** click **Update** next to **Website Preferences** > Select **On** next to **Auto Return >** In the **Return URL** field, enter the URL where you want to send your payer after payment is completed *(you can copy and paste the link we provide to test).* 

(5) **Allow customer pay via authorize.net:** Choose **Yes** if you want to allow customer to pay via **authorize.net**

(6) **Allow customer pay via Stripe:** Choose **Yes** if you want to allow customer to pay via **Stripe**


#### Product Search


![Product Search](./imgpart1/i11.png?raw=true)

(1)	**Product Attribute(s) for Search:** Select your preferred **Product Attribute(s) for Search.** 

***Notes:**** Only select necessary attributes, or else the loading speed will be slow

(2)	**Barcode Attributes:** Select **Barcode Attributes.** You can only change this configuration if you already have a barcode attribute

(3)	**Show inactive categories:** Choose **No** to hide inactive categories for your **Web POS Store View**


#### Default Guest Checkout


![Default Guest Checkout](./imgpart1/i12.png?raw=true)

Fill in the **Default Customer ID.** 

OR ELSE, you can set the field blank to create automatically a new customer with information fields below it. Then, you fill in **First Name, Last Name, Street, Country, State/Province, City, Zip/Postal Code, Telephone** and **Email**


#### Default Email Configuration


![Default Email configuration](./imgpart1/i13.png?raw=true)

(1)	**Orders**

-	Choose **Yes** to activate automatic Order Confirmation Email

-	The Email Template is set as the **Store’s Default Template**

(2)	**Invoices** 

-	Choose **Yes** to activate automatic Invoice Email

-	The Email Template is set as the **Store’s Default Template**

(3)	**Shipments**

-	Choose **Yes** to activate automatic Shipment Email

-	The Email Template is set as the **Store’s Default Template**

(4)	**Credit  Memos**

-	Choose **Yes** to automatically send your customers email about their **Store Credit Transaction**

-	The Email Template is set as the **Store’s Default Template**


#### Receipt Printing Configuration


![Receipt Pricing Configuration](./imgpart1/i14.png?raw=true)

(1)	Choose **Yes** to activate **Auto-print Receipt After Placing Order.** 

***Notes:*** The function cannot work if your browser blocks automatic pop-up. 

(2)	**Content:**

-	Choose **fonts**: Monospace or Sans-serif

-	With **Footer** and **Header** Text, you can fill in the content and choose simple HTML tags.

(3)	**Optional Fields:**

-	Choose **Yes** to show **Web POS logo, Cashier name, Comment** and **Barcode**  *(encode order increment ID)* 


#### Z – Report and Counting Drawer Configuration


![Z-report and counting drawer configuration](./imgpart1/i15.png?raw=true)

(1)	**Custom Note Values:** Note Values are separated by comma. Multiplied Values and Notes are separated by colon. For example, $5 notes: 5, $10 note: 10, 1 cent: 0.01

(2)	**Default Starting Cash:** The default cash amount will be kept in Cash Drawer after closing store. It’s also the starting amount of the next shift and can be modified when creating Z-report


### Loyalty Program


#### Promotions


##### Catalog Price Rule

![Catalog Price Rule Path](./imgpart1/i16.png?raw=true)

Path: **Promotions > Catalog Price Rule > Add New Rule**

•	**Rule Information**

![Catalog Price Rule Information](./imgpart1/i17.png?raw=true)

(1)	**Rule Name** and **Description:** Enter the **Rule name**, and **Rule Description** – if you have

(2)	**Status:**

-	**Inactive:** if you do not want to apply the rule yet

-	**Active:** if you are ready to apply the rule

(3)	**Websites:** Choose which **websites** you want to apply the rule. And, select which **Customer Groups** can use the rule. 

(4)	**From Date** and **To Date:** Use Calendar to select the **Rule Date**

(5)	**Priority:** Enter the **Priority** (a number that indicates the priority of this rule in relation to others. The highest priority is number 1). 

•	**Conditions**

![Catalog Price Rule Condition](./imgpart1/i18.png?raw=true)

Click on the plus button, and Condition Options will appear. You can select each seperated conditions or you can select **Condition Combination** 

•	**Actions:**

![Catalog Price Rule Actions](./imgpart1/i19.png?raw=true)

(1)	**Apply:** Select the **Price Rule** that you want to apply, including one of these:

-	**By Percentage of the Original Price:** Discount by subtracting a percentage from the original price

-	**By Fixed Amount:** Discount by subtracting a fixed amount from the original price

-	**To Percentage of the Original Price:** Discount by subtracting up to a particular percentage from the orignal price 

-	**To Fixed Amount:** Discount by subtracting up to a particular fixed amount from the original price

(2)	**Discount Amount:** Enter the **Discount Amount** that you want to apply

(3)	**Enable Discount to Subproducts:** Choose **Yes** if you want to enable discount to sub-products

**Sub-products** are items on the **Product Set** (in other word, **Configurable Product*)

(4)	**Stop Further Rules Processing:** Choose **Yes** if you want to stop further rules processing

**Stop Further Rules Processing** means that if the system reaches a rule with the Stop Further Rules Processing, it will stop going through any lower priority rules (only activate if you select priority for rules). 


##### Cart Price Rule


![Cart Price Rule Path](./imgpart1/i20.png?raw=true)

Path: **Promotions > Shopping Cart Price Rules > Add New Rule**

•	**Rule Information**

![Cart Price Rule Information](./imgpart1/i21.png?raw=true)

**Rule Name, Description, Websites,** and **Customer Groups:** similar to 

**Catalog Price Rule**

![Cart Price Rule Information part 2](./imgpart1/i22.png?raw=true)

(1)	**Coupon:** Select whether you want to create coupon:

-	**No Coupon:** Do not create

-	**Specific Coupon:** Create

(2)	**Coupon Code:** enter the coupon code, tick on **Use Auto Generation** if you want to generate multiple coupon codes

(3)	**Uses per Coupon:** Enter the times a coupon can be used and the times a logged-in customer can use coupon

(4)	**Uses per Customer:** Use Calendar to select the Rule Date Range

(5)	**From Date** and **To Date:** Select the prirority value for the rule

(6)	**Public in RSS Feed:**

**RSS (really simple syndication)** is an XML-based data format that is used to distribute information online, including promotions, product information to shopping aggregation sites, and newsletters. A link to all the RSS feeds that you publish is in the footer of your store.
If you choose **Yes**, any additions to products, specials, categories, and coupons in your store are automatically sent to the subscribers of each feed. 


#### Free Gift Promotions (Coming Soon)

#### Gift Card

Path: **Gift Card > Settings**

##### General

![Gift Card General](./imgpart1/i23.png?raw=true)

**Enable Gift Card:** Choose **Yes** if you want to enable Gift Card. Otherwise, choose **No**.

•	**Gift Code**

![Gift Card Code](./imgpart1/i24.png?raw=true)

(1)	**Gift Code Pattern:** Configure the **pattern** to auto-generate gift codes for Gift Card products when customers purchase in Web POS frontend

(2)	**The number of prefixes shown:** Enter the number of **prefix characters** which are shown in a voucher code

(3)	**Replace Hidden Characters by:** Enter one letter to **replace hidden characters**

•	**Gift Card Usage**

![Gift Card Usagel](./imgpart1/i25.png?raw=true)

(1) **Gift Cards codes expire after:** Enter the term of validity that Gift Cards can be used after being activated.

(2) **Maximum time(s) to enter gift code incorrectly:** Enter the **maximum time(s)** that allows users to enter gift code incorrectly.

(3) **Maximum number of users per gift code:** Enter the **maximum number of users per gift code.**

(4) **Enable customer’s Gift Card credit balance:** Choose **Yes** to enable customer’s Gift Card Credit Balance. Then, customers can redeem their gift code for credit balance

(5) **Allow customers to redeem Gift Cards with usage conditions:** Select **Yes** to allow customers to redeem Gift Cards with usage conditions 

(6) **Use Gift Cards for shipping fee:** Choose **Yes** to allow customer to apply gift card for shipping fee

(7) **Use Gift Cards with coupon codes:** Select **Yes** to allow customers to use both Gift Card codes and Coupon codes at once. 

(8) **Show the link to check Gift Cards codes on website:** Choose **Yes** to allow customers to check status of Gift Cards after entering Gift Codes, and vice versa.

(9) **Show Gift Card expiry date on website:** Select **Yes** to show the expiration date of Gift Cards on website, and vice versa.

•	**Tax Configuration**

![Gift Card Tax Configl](./imgpart1/i26.png?raw=true)


**Apply Gift Card Discount:** Here, you have two options to apply: 

-	**After Tax:** to allow applying Gift Card after the tax is applied

-	**Before Tax:** to allow applying Gift Card before the tax is applied


##### On Prodcut Page


•	**Gift Card Value**

![Gift Card Value](./imgpart1/i27.png?raw=true)


(1) **Default Gift Card value:** Enter the default gift card value 

(2) **Description of Gift Card value:** Enter the description of gift card value 

•	**Gift Card Template**

![Gift Card Template](./imgpart1/i28.png?raw=true)

(1) **Gift Card template:** Select **Yes** to allow customers to change the image inserted in the template

(2) **Maximum size of image(s):** Limit the maximum size of images uploaded by customers to 500KB


•	**Gift Card Shipping Information**

![Gift Card Shipping Information](./imgpart1/i29.png?raw=true)

(1) **Allow shipping Gift Card:** Select **Yes**, then Gift card can be sent through the post office

(2) **Minimum days for store owner to send Gift Card through post office:** Choose **the number of days** that after Customers order Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within that number of days

(3) **Message max length:** Limit the maximum length of a custom message on Gift Card. Select **Yes** to allow users to schedule gift card delivery date.

(4) **Enable scheduling Gift Card delivery:** Select **Yes** to enable scheduling Gift Card Delivery. It helps customer flexibly choose their preferred date to send the Gift Card to others 


##### On Shopping Cart Page


![Shopping Cart Page](./imgpart1/i30.png?raw=true)

(1) **Show Gift Card box on shipping cart page:** Select **Yes** to Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.

(2) **Information displayed on shipping cart page:** Select the data to display on shopping cart page

(3) **Show Gift Card image as product image in shopping cart:** Select **Yes** to allow showing Gift Card printout preview as product image on shopping cart page


##### On Checkout Page


![Checkout Page](./imgpart1/i31.png?raw=true)

**Show Gift Card box in the Payment action:** Select **Yes** to show Gift Card box on the checkout page


##### Email Notification


•	**General**

![Email Notification General Information](./imgpart1/i32.png?raw=true)

(1) **Enable email notification:** Select **Yes** to allow sending notification emails to customers and recipients

(2) **Send Gift Card to friend when Gift Card status is:** Select **Active**, only a gift card which is activated can be sent to a friend

(3) **Sender of email notification:** Set the default sender of notification emails as **General Contact** 

(4) **Gift Card notes:** Enter the notes displayed in Gift Card Delivery Email 

(5) **Send Gift Card copy via email:** Select **Yes** to allow sending a copy of 
gift card via email if customers choose to ship through post office.

•	**Notification Email send to Purchaser**

![Email Notification to Purchaser](./imgpart1/i33.png?raw=true)

(1) **Send-to-purchaser email template:** Select the email template **sent to purchasers after buying Gift Card** successfully. 

(2) **Send-to-purchaser email template when recipient receives Gift Card:** Select the email template **sent to purchasers when recipients receive Gift Cards.**

•	**Notification Email send to Receiver**

![Email Notification to Recipient](./imgpart1/i34.png?raw=true)

(1) **Send – to – recipient email template:** Select **Yes** to allow sending email notification to recipient when sender refunds Gift Card.

(2) **Send notification email to recipient when purchaser refunds Gift Card:** Select the email template **sent to the gift card’s recipient.**

(3) **Send-to-recipient email template when Gift Card is refunded:** Choose the email template **sent to recipient when gift card is refunded.**

(4) **Auto-send reminder email before Gift Card expires:** Enable auto reminder email **sent to Customers before Gift card expires**

(5) **Auto-send reminder email before:** Enter the **number of days** to **send notification to customers before the expiration date of a Gift card.**

##### Gift Card Printout

![Gift Card Printout](./imgpart1/i35.png?raw=true)

(1)	**Logo on PDF Printouts:** Click on **Choose File** to upload your Logo image. 

***Notes:*** this image is used in PDF and HTML, recommended sixe is 17x63 px and the supported format is jpeg, jpg and png

(2)	**Show barcode on Gift Card:** Choose **Yes** to show barcode on Gift Card

(3)	**Type of Barcode:** Select **type of barcode** shown on Gift Card (if you choose Yes on step 2)

(4)	**Gift Card notes:** Enter **Gift Card Notes** 

(5)	**Gift Card fold paper note:** Enter **Gift Card fold paper note** (recommed to use HTML)

##### Gift Card Template

Path: **Gift Card > Manage Gift Card Template > Add Gift Card Template**

•	**General Information**

![Gift Card Template General Information](./imgpart1/i36.png?raw=true)

(1) **Template Name:** Enter the template’s **name**

(2) **Status:** Select the **Status** of Gift Card: active or inactive 

(3) **Template Design:** Choose a template design for the gift card. We provide these options:

Amazon-gift-card

Left-gift-card

Simple-gift-card

Top-gift-card

Center-gift-card

(4)	**Title:** Enter the **title** of gift card using this template

(5)	**Style Color:** Choose a **style color** used in Title, Value and Gift Code fields

(6)	**Text Color:** Choose **text color**

(7)	**Background Image:** Click on **Choose File** to upload **Background image**

(8)	**Notes:** Enter **notes** for the gift card

•	**Images**

![Gift Card Upload Images](./imgpart1/i37.png?raw=true)


##### Gift Code Pattern


•	**General Information**

![Gift Card Pattern General Information](./imgpart1/i38.png?raw=true)

(1)	**Pattern name:** Enter the **Pattern Name**

(2)	**Gift Code pattern:** Enter **Gift Code pattern**

(3)	**Gift code value:** Enter the **value** of Gift Code

(4)	**Currency:** Enter the **Currency** of the Gift Card

(5)	**Expired on:** Use Calendar to set the **expired date**

(6)	**Template:** Select a **template** for your gift code

(7)	**Gift code Qty:** Enter number of **available quantities** for your gift code

(8)	**Store view:** Choose **which stores** can view this Gift Code

•	**Conditions**

![Gift Card Conditions](./imgpart1/i39.png?raw=true)

Add Conditions for the gift code


#### Reward Points


Path: **Reward Points > Settings**


##### General Configuration

![Reward Points Configuration](./imgpart1/i40.png?raw=true)

(1)	**Enable Reward Points extension:** Choose **Yes** to enable Reward Points Extension on the Module

(2)	**Label for Point:** Enter the **Point Label**. If you leave it empty, the default label *“Point” * will be used.
For example, if you enter *“P” * on this field, then instead of showing *“1 Point”*, it will show *“1 P”*.  

(3)	**Label for Points:**  Enter the **Point label (plural)**. (similar as step 2)

(4)	**Reward Points Image: Choose File** to upload Reward Point Image. Notice that: the recommended sixe is 18x18px. If you leave it blank, the image on template will be used instead.

(5)	**Use Reward Policy page:** Choose **Yes** if you want to use Reward Policy page

(6)	**Use Reward Welcome page:** Choose **Yes** to show Reward Welcome Page


##### Earning Points Configuration


![Earning Points Configuration](./imgpart1/i41.png?raw=true)

(1)	**Rounding Method:** You have three options to choose: 

- Normal:  for example, 10.2 points generated from an order can be rounded to 10, and 10.8 points generated from an order can be rounded to 11.

- Up: for example, 10.2 points generated from an order can be rounded up to 11

- Down: for example, 10.2 points generated from an order can be rounded down to 10

If you finish editing the field, remember to reindex **Catalog Earning Rules**, as below:

![Reindex Points after Configuration](./imgpart1/i42.png?raw=true)

Path: **Reward Points > Earning > Catalog Earning Rules** 

(2)	**Points expire after:** Enter the **expiration date** of the Points

(3)	**Number of points in balance allowed:** Enter the **maximum number** of points allowed in Customer’s balance. If you leave it blank, there will be no limitation. 

(4)	**Earn points from tax:** Choose **Yes** to allow customers to earn point from tax

(5)	**Earn points from shopping fee:** Choose **Yes** to allow customers to earn point from using your shipping service

(6)	**Allow using points when using points to spend:** Choose **Yes** to allow customers to earn point after spending points.

(7)	**Allow receiving points when invoice is created:** If you choose **Yes**, customers can receive points right after they create an invoice (even when the invoice is incomplete)

(8)	**Hold point transaction for:** Enter the number of days to hold transaction


##### Spending Points Configuration


![Spending Points Configuration](./imgpart1/i43.png?raw=true)

(1)	**Minimum redeemable points:** Enter the **minimum number of points** in Customer’s Balance is permitted to redeem. If you leave it blank, there will be no limitation

(2)	**Maximum spending points per order:** Enter the **maximum number of points** that customers can redeem in an order. If you leave it blank, there will be no limitation

(3)	**Use maximum points at checkout by default:** Choose **Yes** if you allow customers to spend maximum points at checkout by default

(4)	**Allow using points for Shipping Fee:** Choose **Yes** to allow using points for **Shipping Fee**


##### Display Configuration


![Display Configuration](./imgpart1/i44.png?raw=true)

(1)	**Show total point balance next to My Account link:** Choose **Yes** to show total point balance next to My Account link

(2)	**On Product Page:** Choose **Yes** to display collectible Points on **Product Page**

(3)	**On Minicart:** Choose **Yes** to display collectible points on **Mini cart**

(4)	**On Product Listing Page:** Choose **Yes** to display collectible points on **Product listing page**


##### Email Configuration


![Email Configuration](./imgpart1/i45.png?raw=true)

(1)	**Enable notification email:** Choose **Yes** to enable notification email

(2)	**Sender:** Choose the **name of the Sender** who can send email about Balance Updates and Expiration Notifications to customers:

-	General Contact

-	Sale Representative

-	Customer Support

-	Customer Email 1

-	Customer Email 2

(3)	**Template of email sent to Customer when point balance is updated:** Choose **Email Template** sent to customer before a transaction expires 

(4)	**Send reminder email before a transaction expires:** Enter **number of days** before a transaction empires so that your customer can receive a Reminder Email before the expiration date. 

##### Loyalty Level Configuration


![Loyalty Level Configuration](./imgpart1/i46.png?raw=true)

(1)	**Enable Loyalty Level plugin:** Choose **Yes** to enable Loyalty Level Plugin

(2)	**Send email before level expires:** Choose **Yes** to send email before level expires


##### Rules Plugin Configuration


![Rules Plugin Configuration](./imgpart1/i47.png?raw=true)

(1)	**Enable Rules Plugin:** Choose **Yes** to enable Rules plugin

(2)	**Show Earning rule on Shopping Cart Page:** Choose **Yes** to show Earning Rule on Shopping Cart Page


##### Earning Rates


![Earning Rates Configuration](./imgpart1/i48.png?raw=true)

(1)	**Amount of money spent:** Enter **amount of money spent** to earn points. 

(2)	**Earning point(s):** Enter the **number of points** customer can earn when they spent the above amount of money. For example, when the **Amount of money spent** is 10, the **earning point(s)** will be 1. 

(3)	**Status:** Select the status of the Earning Rate:  **Active** or **Inactive**

(4)	**Websites:** If you have more than 1 website, you can select **which websites** can apply this Earning rate

(5)	**Customer groups:** Choose **which customer groups** can apply this Earning Rate

(6)	**Priority:** Enter the **priority** of the Rate. Notice that: the higher priority rate will be applied first


##### Spending Rates


![Spending Rates Configuration](./imgpart1/i49.png?raw=true)

(1)	**Spending point(s):** Enter the **number of points** a customer must spend to receive discount

(2)	**Discount received:** Enter the **amount of discount** a customer can receive when spend a particular number of points mentioned above.

(3)	**Status:** Choose the **Status** of this Spending Rate

(4)	**Limit spending points based on:** Select the type of limit spending points: 

-	**None:** customer can spend unlimited points per order.

![Limit value allowed to spend points at](./imgpart1/i50.png?raw=true)

-	**A fixed amount of Total Order Value**, then on the field **Limit Value allowed to spend points at**, you will have to enter the highest amount of money a customer can spend by Reward Points for each order. For example, 1 point = $2. If you set the **Limit Value** is $100, it means a customer can use maximum = 50 points for the order. 

-	**A percentage of Total Order Value**, then on the **Limit Value allowed to spend points at**,  you will have to enter the highest percentage of money counted from Total Order Value that a customer can spend by Reward Points. For example, 1 point = $2, you set the **Limit Value**  is 50% and the Total Order Value (Customer Bill) is $500. Then, a customer can use at most $250 = 125 points. 

(5)	**Websites:** If you have more than 1 website, you can select **which websites** can apply this Earning rate

(6)	**Customer groups:** Choose **which customer groups** can apply this Earning Rate

(7)	**Priority:** Enter the **priority** of the Rate. Notice that: the higher priority rate will be applied first


#### Store Credit


Path: **Store Credit > Settings**


![Store Credit Path](./imgpart1/i51.png?raw=true)


##### General Configuration


![Store Credit General Configuration](./imgpart1/i52.png?raw=true)

(1)	**Enable:** Choose **Yes** to **enable**/activate Store Credit on your site

(2)	**Allow sending credit:** Choose **Yes** to allow customers to send credit to their friends

(3)	**Groups can use edit:** allow only **General/Wholesaler/Retailer** or all customers able to use credits

##### Spend Credit On

![Store Credit Spend Credit On Configuration](./imgpart1/i53.png?raw=true)

(1)	**Apply Customer Credit:** you have to options – **After Tax** and **Before Tax**

If you choose **After tax**, it means the Customer Credit Discount will be applied to order value including tax

(2)	**Shipping Fee:** Choose **Yes** to allow using customer credit for Shipping Fee

##### Email Configuration

![Store Credit Email Configuration](./imgpart1/i54.png?raw=true)

(1)	**Email template with credit code sent to recipients:** default

(2)	**Email template with verification code sent to credit sender:** default

(3)	**Email template notifying customers:** default

(4)	**Send-to-customer email template when recipient receives credit:** default

##### Adjust time for Customer Credit reports on total used and total received credit

![Store Credit Time Configuration](./imgpart1/i55.png?raw=true)

(1)	**Select start time for current year:** choose **Month**, then **Date**

(2)	**Select date for current month:** choose **Date**

##### Style Configuration

![Store Credit Style Configuration](./imgpart1/i56.png?raw=true)

(1)	**Background of Title:** enter **Hexadecimal code**

(2)	**Color of Title:** enter **Hexadecimal code** or choose a **color** as above.

(3)	**Default Font Size:** enter a font size


#### Membership (Coming Soon)


#### Wallet (Coming Soon)


### Store Pickup


#### Settings


Path: **Store Pickup > Settings** 


##### General

![Store Pickup General Configuration](./imgpart1/i57.png?raw=true)

(1)	**Enable Store pickup:** choose **Yes** to activate Store Pickup for your store

(2)	**Store List link shown in frontend:** choose the position of the Store List link (**Top Link, Footer Link** or **Not Shown**)

(3)	**Google Map key:** To integrate **Google API**  for your site, fill your Google Map API key into this field. You can get this key by clicking on **here** under Google Map API Key tab. Or else, you can go to **Store Pickup > Guide**


##### Store List

![Store Pickup List Configuration](./imgpart1/i58.png?raw=true)

(1)	**Description:** enter description for the store list
***Notes:*** you write in **HTML** for better display in frontend

(2)	**Search Tab:** select the search tab for your store (**Search by Distance** or **Search by Area**)

(3)	**Store Search:** select how your customers can search your store (by **Country, State, City, Store Name** or **zipcode**)

(4)	**Maximum Radius:** enter the highest distance range to find your store

(5)	**Unit of distance:** select which unit used to measure distance between store and customer.


##### Checkout

![Store Pickup Checkout Configuration](./imgpart1/i59.png?raw=true)

(1)	**Carrier Title:** this will shown in Shipping Method stage at checkout

(2)	**Method Title:** this will be shown in Shipping Method stage at checkout

(3)	**Sort Order:** enter a number to determine the position in the listing of shipping methods during checkout process, the higher number means the higher priority in display

(4)	**Defaul store at checkout:** choose the **default pick-up stores**

(5)	**Display pickup time/date:** choose **Yes** to allow customers to select pick up date and time.

(6)	**Time format:** set format of shipping time and store’s working time

(7)	**Applicable payment method(s):** select which **payment methods** will be applied to Store Pickup


##### Email Template

![Store Pickup Email Template](./imgpart1/i60.png?raw=true)

(1)	**To store owner when pickup order is created:** default

(2)	**To admin when pickup order is created:** default

(3)	**To store-owner and web-ship admin when customers contact:** default

(4)	**To store owner when pickup order status is changed:** default


#### Store Configuration


Path: **Store Pickup > Manage Stores**

![Store Configuration](./imgpart1/i61.png?raw=true)


**Case 1** - If you choose **Import Store**, then:

![Store Configuration Case 1](./imgpart1/i62.png?raw=true)

**Choose file** to import/upload **CSV File**. If you don’t have any CSV File, click on **Here** to get the CSV Sample


**Case 2** - If you choose **Add Store**, then:


##### Store Information

![Store Information](./imgpart1/i63.png?raw=true)

Fill information in these fields. Notice that:

-	Necessary fields: **Store Name, Shipping Fee ($)** – the cost of shipment service, **Address, City, Country, State/Province, Zip Code**

-	Optional fields: **Status, Tags, Description**.

In **Description** field, you can use **HTML** for better display on front end **OR** click on **Show/Hide Editor**, then you can edit content as below:

![Store Description](./imgpart1/i64.png?raw=true)


##### Contact Information


![Contact Information](./imgpart1/i65.png?raw=true)


Fill in **Store Manager, Phone Number, Email Address,** and optional fields such as **Fax Number, Receive email when order status is changed, Store Image(s)**


##### Google Map

![Google Map Configuration](./imgpart1/i66.png?raw=true)

Fill in coordinates and set color of the store’s pin shown on Google map, which is very helpful as you can highlight any store from others just with a different pin color.

You have seen how Store Pickup works in front-end for customers. The following part will guide you through how to configure and manage the extension in back-end.

***New release:*** One of the most important Google Maps APIs Standard Plan updates implemented on June 22, 2016 was that required future product updates are only available for requests made with an API key.

This means active domains created before June 22, 2016, continue to be able to access the Google Maps JavaScript API, Static Maps API, and Street View Image API without an API key. They are not affected by keyless access being unavailable for new domains. 

However, Google Maps APIs Standard Plan advise all developers to use a key to guarantee their quality of service. Applications that continue to make keyless requests may experience some periodic service degradation if other keyless applications' usage spikes and draws down the global unchanged quota.
To get API key, follow these steps as follows: 

**Step 1:** Visit APIs Console at https://console.developers.google.com/apis/library and log into your Google Account.  Then, click Create project button on top of the menu. 


![Google Map Configuration 1](./imgpart1/i67.png?raw=true)


**Step 2:** Fill in the project name and click Create button

![Google Map Configuration 2](./imgpart1/i68.png?raw=true)

**Step 3:** On the menu at the left side, you will see the **Credentials** Tab. 

Click this tab and after that, a box will appear with **API key** on it. It is where you should click to create API key for your browser apps.

![Google Map Configuration 3](./imgpart1/i69.png?raw=true)

After that you will see a box with number of choices specifying which kind of key you would like to create. Choose **Browser key** 

![Google Map Configuration 32](./imgpart1/i70.png?raw=true)

**Step 4:** Fill in your name and domain and then click create

![Google Map Configuration 4](./imgpart1/i71.png?raw=true)

**Step 5:** Get the key and paste it in your page 

![Google Map Configuration 5](./imgpart1/i72.png?raw=true)

**Step 6:** After all, in **Library** tab, enable the APIs in red frame as below 

![Google Map Configuration 6](./imgpart1/i73.png?raw=true)



#### Holiday Setting 


Path: **Store Pickup > Manage Holidays >** click on **Add Holiday**

![Adding Holiday](./imgpart1/i74.png?raw=true)

(1)	Fill in **Holiday Name, Store, Starting Date, End Date** and **Comment** - which is shown as notification to customers

(2)	Remember to click **Save Item** if you’ve done or **Save and Continue Edit** to avoid losing what you’ve written. 

OR ELSE, you can click on **Reset** to delete all you’ve created or **Back** to delete all and come back to the Manage Holiday Page.


#### Special Day Setting


Path: **Store Pickup > Manage Special Days >** click on **Add Special Day**

![Special Day Configuration](./imgpart1/i75.png?raw=true)

(1)	Fill in **Special Day Name** and select **Store, Starting Date, End Date**

(2)	**Timer Interval:** Set Time Interval between 2 shipping times

(3)	**Opening Time** and **Closing Time:** choose working time for special day

(4)	**Comment:** enter comment which will be shown as notification to your customers. 

Remember to click **Save** to finish

#### Tag Setting

Path: **Store Pickup > Manage Tags >** click on **Add Tag**

![Tag Information](./imgpart1/i76.png?raw=true)

(1)	**Name:** Enter the name

(2)	**Tag Icon: Choose File** to upload Icon

(3)	**Status:** choose **Enabled** to activate the tag

### Shipment Method

Path: **System > Configuration > Sales > Shipping Methods > Web POS Shipping**

![Web POS Shipping](./imgpart1/i77.png?raw=true)

(1)	You can edit these fields as below:

-	**Enabled:** choose **Yes** to activate Web POS Shipping

-	**Carrier title:** enter the carrier title

-	**Method title:** enter the method title

-	**Price:** enter the price of this method/service (Once you edit, the price will be default)

(2)	**Custome Methods:**

You can have another option for Web POS Shipping by creating as below:

-	**Custom Method Title: ** enter the name of method title

-	**Custom Method Price: ** enter the price of the Custom Method. (Once you 
edit, the price will be default)

Or you can leave it blank, and edit sections below, such as: **Flat Rate, Free Shipping, Table Rates, Store Pickup, UPS, USPS, FedEx, DHL (deprecated) ** and **DHL**


### Payment Method


Path: **System > Configuration > Sales > Payment Method**

##### Web POS – Multiple Payments

![Web POS Multi Payments](./imgpart1/i78.png?raw=true)

-	**Payment methods use to split:** select more than one methods that you want to use in split

-	**Title:** name it


##### Web POS – Cash On Delivery

![Web POS Cash On Delivery](./imgpart1/i79.png?raw=true)

-	**Enabled:** choose **Yes** to activate **Cash On Delivery**

-	**Title:** enter the name of the method that allow customer pay Cash on Delivery

-	**Use Reference Number:** choose **Yes** if you want to use this

-	**Allow Paying Later:** choose **Yes** to allow customers to pay after receiving products.


##### Web POS - Cash

![Web POS Cash](./imgpart1/i80.png?raw=true)

-	**Enabled:** choose **Yes** to activate Cash paying method

-	**Title:** name the tile of this method

-	**Use Reference Number:** choose **Yes** if you want to refer number

-	**Alllow Paying Later:** choose **Yes** if you want to allow customer after receiving products


##### Web POS – Credit Card

![Web POS Credit Card](./imgpart1/i81.png?raw=true)

-	**Enabled:** choose **Yes** to activate paying by Credit Card

-	**Title:** name the tile of this method

-	**Use Reference Number:** choose **Yes** if you want to refer number

-	**Alllow Paying Later:** choose **Yes** if you want to allow customer after receiving products


##### Web POS – Custom Payment

![Web POS Custom Payment](./imgpart1/i82.png?raw=true)

Besides all suggested paying method, you can customize two more **Payment Methods** by yourself.


### Magento – Odoo (Coming soon)

--------

## HOW TO MANAGE USER


### Roles


Path: **System > Permissions > Roles**


#### Manage Roles

![Manage Roles](./imgpart02/img1.png?raw=true)

(1)	You can click on

-	**Add New Role:** add new role for your business

-	**Reset Roles:** after you add a new role, or reload page to update roles

(2)	Role Management Field

-	Management Table:

+ **Role Name:** type the role name that you want to search

+ **ID:** you can search the roles by ID

-	**Search:** after you type Role Name or ID, you can click on **Search**, or tap 
**Enter** on your keyboard

-	**Reset Filter:** if you want to come back to the whole role management, click on **Reset Filter**. 

Besides, to edit Roles, you just need to click on the Role Name that you want to edit. Example below:

![Example](./imgpart02/img2.png?raw=true)

You can edit **Role Name, Role Resources** and check which Users are using this Role on **Role Users**

![Role Users](./imgpart02/img3.png?raw=true)

Remember to **Save Role** to finish


#### Create Roles


Path: **System > Permissions > Roles > Add New Role**

##### Role Info

![Role Info](./imgpart02/img4.png?raw=true)

(1)	**Role Name:** enter Role Name

(2)	**Current Admin Password:** Enter the Role Creator’s Password (for example, IT Admin creates the Role, so enter IT Admin Password)

##### Role Resources

![Role Resources](./imgpart02/img5.png?raw=true)

(1)	**Resource Access:** you have two options:

-	**All:** allow the Role to access all resources of the business

-	**Custom:** choose which resource that the Role can access

(2)	**Resources:** if you choose Custom on (1), then the **Resources** tab will appear. You need to tick on which resources you allow the Role to access.

Remember to click on **Save Role** to finish


### Users


Path: **System > Permissions > Users**


#### Manage Users

![Manage Users](./imgpart02/img6.png?raw=true)

(1)	User Management Field:

You can search Users by **ID, User Name, First Name, Last Name, Email** and **Roles**

After you enter the search word, remember to tap **Enter** to find or click on **Search**. After that, to come back the whole user management field, you have to click on **Reset Filter**.  

(2)	**Add New User:** to add new user

Besides, you can edit User Info by choosing the User you want to edit.

![Edit User](./imgpart02/img7.png?raw=true)

Then, you can allow warehouse permission for that Users (only for existed Users) by ticking on which warehouses they can access, then click on **Save Warehouse Permissions.**

In addition, you can also assign warehouses, by clicking on **Assign Warehouses**.  A pop-up will appear as below: 

![Add Warehouse Permissions](./imgpart02/img8.png?raw=true)

(1)	Tick on the **warehouse(s)** you want to assign 

(2)	**Add Warehouse Permission:** to save the ticked warehouse
Remember to click on **Save User** to finish


#### Create Users


Path: **System > Permissions > Users > Add New User**


##### User Info

![User Info](./imgpart02/img9.png?raw=true)

(1)	Enter **User Name, First Name, Last Name** and **User email**

(2)	**Current Admin Password:** Enter the Role Creator’s Password (for example, IT Admin creates the Role, so enter IT Admin Password)

(3)	**Password** and **Password Confirmation:** enter the User Password. 

**Note:** enter at least 7 characters. The password must include numbers and alphabets

(4)	**The password is: active** or **inactive**


##### User Role

![User Role](./imgpart02/img10.png?raw=true)

All existed roles will be displayed. You can leave it blank or tick on roles that you want to assign to the New User.

You can type the **Role Name** and click on **Search/** tap **Enter** to find Role. Then click on **Reset Filter**, to come back the whole Role Management Display. 


##### REST Role

![REST Role](./imgpart02/img11.png?raw=true)

REST Role is used for API Web POS on mobile app only. 

You can assign REST-Role by ticking on the list. 

Only Admin can manage and add new REST role by going to **System > Web Services > REST – Roles**. There are two default REST role (unable to delete): Guest and Customer

Remember to click on **Save User** to finish


### Staffs (for Web POS only)


Path: **Sales > Web POS > Web POS Permissions** 


#### Manage Staffs


##### Roles


Path: **Sales > Web POS > Web POS Permissions > POS Roles**

![Manage Staffs Roles](./imgpart02/img1101.png?raw=true)

POS Role management will be shown in grid, including columns **named ID, Display Name, Description, Active** and **Action**. You can search for Roles here.

##### Users


Path: **Sales > Web POS > Web POS Permissions > POS Users**

![Manage Staffs Users](./imgpart02/img12.png?raw=true)

POS User Management will be shown in grid, including columns named **ID, User Name. Email, Display, Location** (the store users are taking charge), **Role, Status,** and **Action**. You can search for Users here. 


#### Create Staffs


##### Roles


Path: On **POS Roles** page, click on **Add Role**


###### Role Information

![Create Staffs Roles](./imgpart02/img13.png?raw=true)

(1)	**Role Name:** Enter the name

(2)	**Permission:** Choose Permissions that the Role can access

(3)	**Maximum Discount Percent (%):** Choose the highest discount this Role can apply for each customer.

(4)	**Description:** write the description of the Role (if have)

(5)	**Status:** determine if the Role is **Active** or **Inactive** 


###### User List

![Create Staffs User List](./imgpart02/img14.png?raw=true)

Select which Users will take charge of this Role

After all, remember to click **Save Role** or **Save And Continue Edit** 


##### Users

###### User Information

![Create Staffs User](./imgpart02/img15.png?raw=true)

(1)	**User Name:** enter the Name

(2)	**Password** and **Password Confirmation:** enter the User Password (at least 7 characters, including numbers and alphabetic characters)

(3)	**Display name:** enter the name Display on Frontend

(4)	**Email Address:**  enter the email address of the User

(5)	**PIN Code (App only):** enter 4 numbers for PIN Code


###### User Settings

![Create Staffs User Settings](./imgpart02/img16.png?raw=true)

(1)	**Customer Group:** choose which groups the User will take charge of

(2)	**Location:** choose where the User will work (warehouse or which stores)

(3)	**Role:** choose the Role applied for User

(4)	**Status:** choose **Enabled** to activate the User

Click **Save User** or **Save And Continue to Edit** to finish this phase

------

## HOW TO MANAGE MASTER DATA


### Customers


#### Manage Customers


Path: **Customers > Manage Customers** 

![Manage Customers](./imgpart02/img17.png?raw=true)

(1)	The Manage Customers Table will be shown in grid, including columns named **ID, Name, Email, Group, Telephone, Zip, Country, State/Province, Customer Since, Website** and **Action**

You can edit Action by ticking on Customer(s) and choose Action on **Actions** Field, then clicking **Submit** as below:

![Action Option](./imgpart02/img18.png?raw=true)

(2)	**Add New Customer:** if you have not known how to add New customer, you can read the Magento Guide by clicking on **Get help for this page**

![Get help for this page](./imgpart02/img19.png?raw=true)

Besides, you can edit Customers’ Information by clicking on the Customer you want to edit.

#### Customer Groups

![Customer Groups](./imgpart02/img20.png?raw=true)

(1)	The Customer Groups will be shown in grid, including columns named **ID, Group Name** and **Tax Class**. 

(2)	**Add New Customer Group:**

![Add New Customer Group](./imgpart02/img21.png?raw=true)

**1/ Group Name:** enter the name (less than 32 symbols)

**2/ Tax Class:** choose the tax class

![Tax Class](./imgpart02/img22.png?raw=true)

Then, click on **Save Customer Group** to finish


### Supplier


#### Manage Suppliers


Path: **Supplier > Manage Suppliers**  

![Manage Suppliers](./imgpart02/img23.png?raw=true)

(1)	The Supplier Management will be shown in grid, including columns named **ID, Supplier, Supplier Code, Contact Email, Status** and **Action**

(2)	**Add New Supplier**


#### Add New Supplier


##### Supplier Information

![Suppliers Information](./imgpart02/img24.png?raw=true)

(1)	**Supplier Name:** enter the name

(2)	**Supplier Code:** enter the code. It can be Commercial and Government Entity (CAGE) code of supplier, or supplier number, or supplier code, etc.

(3)	**Contact Person:** enter the name of the contact person

(4)	**Email:** enter the supplier email to contact

(5)	**Status:** enabled or disabled this supplier

(6)	**Description:** enter the description about supplier (if have)


##### Mailing Address

![Mailing Address](./imgpart02/img25.png?raw=true)

Fill in **Telephone, Fax, Street Address, City, Country, State/Provice** and **Zip/Postal Code**


##### Product List

![Mailing Address](./imgpart02/img26.png?raw=true)

Tick on which product(s) the supplier provide


##### Pricelist

![Pricelist](./imgpart02/img27.png?raw=true)

Tick on which pricelist(s) the supplier provide

After all, click **Save** to complete the phase


#### Manage Pricelist

![Pricelist Management](./imgpart02/img28.png?raw=true)

(1)	The Pricelist Management will be shown in grid, including columns named **ID, Product SKU, Product Name, Supplier, Maximum Qty, Purcahse Price (USD), Start Date, End Date** and **Action**

(2)	You can click on

-	**Mass Remove:** to remove all pricelist

-	**Mass Update:** to update what you have editted

-	**Import Pricelist:** to import the pricelist. If you click on this, a pop-up will be shown as below:

![Import Pricelist](./imgpart02/img29.png?raw=true)

**Choose file** and upload a **CSV File** to import

If you do not have it, click on **Download sample file** to get the sample of CSV

After you finish uploading, click on **Import** to complete this phase


### Product


#### Attributes


Path: **Catalog > Attributes > Manage Attributes**

![Attributes](./imgpart02/img30.png?raw=true)

(1)	The Management Tab will be shown in grid, including columns named **Attribute Code, Attribute Label, Required, System, Visible, Scope, Searchable, Used in Layered Navigation**, and **Comparable**. 

(2)	**Add New Attribute:** If you do not know how to fill in required fields, click on 

![Get help for this page](./imgpart02/img31.png?raw=true)


#### Attribute Sets


Path: **Catalog > Attributes > Manage Attribute Sets**

![Attribute Sets](./imgpart02/img32.png?raw=true)

(1)	The Attribute Sets will be shown in table

(2)	**Add New Set:** If you do not know how to fill in required fields, click on 

![Get help for this page](./imgpart02/img33.png?raw=true)


#### Categories


Path: **Catalog > Manage Categories**

![Categories](./imgpart02/img34.png?raw=true)

When selecting a category on the left, all the information will be displayed on the right.

You can easily edit any Category Information. Remember to click on **Save Category** to complete it. 

Or else, you can delete Category from your store by click on **Delete Category** button. 

![Categorie button](./imgpart02/img35.png?raw=true)

(1)	**Add Root Category** and **Add Subcategory:** click on the button

(2)	**Get help for this page:** if you are not clear how to fill in required fields, click to read guidelines

(3)	**Reset** and **Save Category:** to save the new category, click on **Save Category**. To delete what you have created, click on **Reset**

#### Products 
##### Types

•	**Simple Product**

A simple product is a physical item with a single SKU. Simple products have a variety of pricing and of input controls which makes it possible to sell variations of the product. Simple products can be used in association with grouped, bundle, and configurable products.

•	**Grouped Product**

A grouped product presents multiple, standalone products as a group. You can offer variations of a single product, or group them for a promotion. The products can be purchased separately, or as a group.

•	**Configurable Product**

A configurable product appears to be a single product with lists of options for each variation. However, each option represents a separate, simple product with a distinct SKU, which makes it possible to track inventory for each variation.

•	**Virtual Product**

Virtual products are not tangible products, and are typically used for products such as services, memberships, warranties, and subscriptions. Virtual products can be used in association with grouped and bundle products.

•	**Bundle Product**

A bundle product let customers “build their own” from an as sort of options. The bundle could be a gift basket, computer, or any things else that can be customized. Each item in the bundle is a separate, standalone product.

•	**Downloadable Product**

A digitally downloadable product that consists of one or more files that are downloaded. The files can reside on your server or be provided as URLs to any other server.

•	**Custom Sale**

A custom sale product is a special product that can be ordered personally or customized along Customer Demand. This product will only be shown in POS.

•	**Store Credit**
 
A store credit helps customer save and earn credit after purchasing a product, or or refund products “without using money”. Besides, Store Credit can be used in purchasing. 

•	**Gift Card**

A gift card is a prepaid stored-value money product. Customer can use gift card as an alternative to cash for purchases within a particular store or related business.



### Warehouse


Path: **Inventory Management > Stock Listing > Warehouses**

![Warehouse Listing](./imgpart02/img36.png?raw=true)

Inventory Information will be shown in grid, inlcuding columns as **ID, Warehouses, Total SKU, Total Qty, Contact Email, Telephone, Street, City, Country** and **Action**


#### New Warehouse

Click on **Add a New Warehouse**

![Add New Warehouse](./imgpart02/img37.png?raw=true)

Fill basic information about the new Warehouse. 


***Notes:*** You are required to fill **Warehouse Name** and **Warehouse Code**


#### Warehouse Management

![Warehouse Management](./imgpart02/img38.png?raw=true)

The grid shows Warehouse basic information such as **ID, Warehouse Name, Total SKUs, Total Qty, Contact Email, Telephone, Street, City, Country**, and **Action**

Click on **View** 

![Warehouse Information](./imgpart02/img39.png?raw=true)
Here, you can edit Warehouse information, including **General Information, Stock On Hand, Stock Movement, Warehouse Permission**, and **Dashboard:**

•	**General Information:** name,code, email and location

•	**Stock On Hand:** illustrate the Qty of products that are availble in the warehouse at the moment. 

•	**Stock Movement:** show the opening and closing data between dates, such as: purchases made, sales order totals, external transfer and internal transfer (send stock) and returned items. 

•	**Warehouse Permission:** manage and decentralize warehouse permission

•	**Dashboard:** show Inventory Report in lines and tables. 
Then, remember to click **Save General Information** to save what you have edited. 

Or you can click on **Delete Warehouse** to delete the warehouse.

Or click on **Back**, to get back the Management Page.


#### Warehouse Permission


After having created a warehouse, Admin Users can give different warehouse access permissions to different (admin) users.

Click on **View** to see the warehouse’s detail information 

![Warehouse Permission](./imgpart02/img40.png?raw=true)

If you want to edit **Warehouse Roles**,

(1)	Tick on the staff you want to edit roles

(2)	Click on tab to select role. For example:

![Warehouse Roles Options](./imgpart02/img41.png?raw=true)

(3)	Click on **Delete** if you want to delete the staff completely.
If you want to add new staff(s), 

(4)	Click on **Assign Staffs**. 

Then a pop-up will be shown as below:

![Assign Staffs](./imgpart02/img42.png?raw=true)

(1)	Tick on the staff you want to add

(2)	Click on tab to select **Admin Role** or **Staff Role** or both

(3)	Click on **Add Selected Staff** to finish this phase. 


### Location


Path: **Sales > Web POS > Manage Locations**


#### Add new Location

![Add New Location](./imgpart02/img43.png?raw=true)

Click on **Add New Location** to add a new one. Then you will have to fill in two sections:


##### Location Information

![Location Information](./imgpart02/img44.png?raw=true)

(1)	**Display Name** and **Address:** these are required fields

(2)	**Description:** fill in description about the warehouse

(3)	**Warehouse:** select one of these options:

![Warehouse List Option](./imgpart02/img45.png?raw=true)

-	**Don’t link to any warehouse:** if the warehouse works separatedly

-	**Create a new Warehouse:** if you are creating the location for the new warehouse

-	**List of warehouses: ** Select one warehouse that you want to add new location


##### User List

![User List](./imgpart02/img46.png?raw=true)

(1)	Tick on which user you want to edit

(2)	Click on the tab in the **Status** Column to edit **Status** of the User. 

After all, remember to click **Save Location** to complete the new Location


#### Maping Locations – Warehouses


Path: **Sales > Web POS > Manage Locations > Maping Locatons – Warehouses**

Or 

Path: **Inventory Management > Stock Listing > Warehouses > Maping Locations-Warehouses**

![Maping Warehouse and Location](./imgpart02/img47.png?raw=true)

(1)	Tick on the **Location** you want to edit. 

Here, you can also edit the Status of the Location. 

-	**Yes:** Available

-	**No:** Inavailable

(2)	**Warehouses:** select the warehouse you want to link to the location
Besides, you can search for location by filling in the tab on **Locations** Column.


### Store (POS) : Coming soon

-----

**_Confidential Information Notice_** 

Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

