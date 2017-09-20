# **GIFT CARD - MAGENTO 2**


**Version 2.0.1**


*Confidential Information Notice
Copyright2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

**Table of Terminologies**

No|Terms|Explanation
---|---|---
1| Gift code|Gift codes are not only generated from Gift Card products but can also be added by Admin:<br/> - Gift codes of Gift Card products are generated in **Settings**<br> - You can import/add gift codes in **Manage Gift Code**s, or auto generate random gift codes in Generate Gift codes
2|Gift code pattern|Template to auto-generate random gift codes 
3|Gift Card product|Gift Card can be created as a product in your store. Like other products, it will have details like: Product page, Price, Weight…
4|Gift Card value|The value of Gift Card that can be used to purchase products at your store. For example: Customer may buy a Gift Card whose value is $100 at just $90. His friend later can buy a product of $100 in your store. 
5|Gift Card order, Product order|Gift Card order is the order purchasing Gift Card at your store.Product order is the order using gift codes to purchase products at your store.
6|Gift Card Product page|The detailed page of a Gift Card where Customers can choose options like: sending Gift Card to friend, filling recipient’s information, sending Gift Card via emails/PO, adding message, scheduling day to send…
7|Credit Balance|When **Gift Card Credit Balance** function is enabled, Customers may redeem their gift codes to a credit balance and use the balance to pay for orders at your store. 
-------------

## **INTRODUCTION**
More and more Customers go online to find gifts for their friends and families, instead of wandering from shop to shop to buy the best gift. Why not join this trend by creating Gift Card/ Gift Voucher as a 1-size-fits-all gift? With this extension, Customers can purchase Gift Cards to present others and then recipients can use them to buy products at your store. It’s a great idea for helping you increase customer satisfaction.

![Gift Card for Magento 2](./GC2%20Image/image004.jpg)

## 	**HOW TO USE**
This section demonstrates how Customers can use Gift Cards in frontend.  
### **Purchase a Gift Card Product**
- Gift Card can be ordered as a normal product. Customers can enter or choose the value and quantity of Gift Card they want to order, then click on **Add to Cart** button.

![Purchase a Gift Card online](./GC2%20Image/image006.jpg)

- The price of Gift Card product may differ from Gift Card value. It depends on Admin‟s configuration in the backend, which could be a fixed value or a percentage of Gift Card value. If the „price type‟ is “percentage”, Customers will see the corresponding Gift Card prices when they choose different Gift Card values.
- After choosing a preferred template, Customers can select 1 out of available background images. It is possible for Customers to personalize their Gift Card by uploading their own image as well. The recommended size for images to upload is 600x365px for the Top layout or 744x455px for the Amazon layout. 3 file types are supported including .GIF, .JPG and .PNG.
If Customers upload an image with an unsupported file type or the image is larger than the maximum file size configured by Admin, the system will auto-show an alert message to notify Customers.
Customers can also see the expiration date of the Gift Card on Gift Card image.
- For Gift Card products that have **usage conditions**, the conditions will NOT be displayed below the product name as in Magento 1 version. However, the admin can write the conditions in the description if it is necessary for customers to see. If anyone want to redeem the gift cards (enter the gift code to purchase one or many products) but does not meet the condition(s), then the system will show an 'Invalid' notice.
-  	Customers can also send Gift Cards to their friends by ticking **Send Gift Card to friend** checkbox and enter all the required fields: 

![send Gift Cards to friends](./GC2%20Image/image008.jpg)<br/>

   -**Recipient name**: the name of the recipient
  <br/>
     - **Recipient email address**: the email address of the recipient. The system will send an email which contains a Gift Card code to this address.
   <br/>
     - **Custom message**: the message is delivered along with the Gift Card code.
     <br/>
     - **Day to send**: Customers can set up the date and time zone that a Gift Card will be sent.
     <br/>
     - If Customers want a Gift Card to be sent through a post office, they need to tick **Send through post office** checkbox. Gift Card product will be shipped as normal products.
     <br/>
     - If Customers want to get the notification email when their friend receives Gift Card, they need to tick the **Get notification email when your friend receives Gift Card** checkbox.
     <br/>
     - To preview how the Gift Card actually looks like when recipients receive, Customers can click on the Gift Card thumbnail image or the **Preview Gift Card** button. A popup of Gift Card interface will be shown as below:

![ Preview Gift Card](./GC2%20Image/image010.jpg)
     
- 	After Customers add a Gift Card to cart, they can go to shopping cart page to review the cart by clicking on the **cart icon** on top right corner, then choose **View and edit cart**. Customer can edit and update the quantity of the gift card right on the Add to cart popup. 

![ Add to cart popup](./GC2%20Image/image012.jpg)
<br/>
     - The details of Gift Card when Customers send the Gift Card to their friend

![Gift Card details when sending to friends](./GC2%20Image/image014.jpg)
<br/>
     - 	The details of Gift Card when Customers buy the Gift Card for themselves:
     

![Gift Card details when buying for self](./GC2%20Image/image016.jpg)

- Then Gift Cards products can be checked out as normal products. Customers will receive a Gift Card code if they buy for themselves. In case Customers purchase the Gift Card to send to their friends, the code will be delivered to their friends’ email with the following form:

![Gift card email form](./GC2%20Image/image018.jpg)

If the Sender has ticked the checkbox **Get notification email when your friend receives Gift Card**, a notification will be sent to his email address immediately after the Gift Card is delivered to the friend’s email as below:

![notification to sender](./GC2%20Image/image020.jpg)

If Customers purchase Gift Card for themselves, the notification email that they receive is as below:

![notification email when buying for self](./GC2%20Image/image022.jpg)

###  Use Gift Card as a discount method
When Customers have Gift Card codes, they can use them as a discount coupon when ordering a product at the Checkout page:

![Use Gift Card as discount on Checkout page](./GC2%20Image/image024.jpg)

Customers can choose to use Gift Cards and enter the amount of money as on
**Shopping Cart** page. Then click on **Add Gift Card** button to apply.

***Note**: Gift Card codes cannot be used to purchase Gift Card products but they can be spent on shipping fee, depending on Admin‟s settings.
## 	HOW TO CONFIGURE
***Important Note**: If you use a different theme from the default theme of Magento, you need to move template, skin and layout files into your theme folder: 
-  app/design/frontend/base/default/....
- skin/frontend/base/default/css/magestore/...

###  Settings
To configure default configurations and settings of the extension, please log in to **backend**, and then choose **Gift Card** menu→ **Setting**. Administrators can change parameters as follows:

•	**General** tab :

![General tab](./GC2%20Image/image026.jpg)

![Gift card usage tab](./GC2%20Image/image028.jpg)


No.|Field|Sample|Description
---|---|---|---
 ||Enable Gift Card|Yes|Enable Gift Card module on your site
 |          **Gift code**    |
 1|Gift code pattern|GIFT-[A.4]-[AN.6]|Configure the pattern to auto-generate gift codes for Gift Card products when Customers purchase in frontend.<br/>[A.8] : 8 alpha character<br/>[N.4] : 4 numeric characters<br/>[AN.6] : 6 alphanumeric characters<br/>If you enter GIFT-[A.4]-[AN.6] as the sample, the system will auto-create a bunch of gift codes matching this pattern, GIFT-ADFA-12NF0O for example.
 2|The number of prefixes shown|4|The number of prefix characters which are shown in a voucher code is 4, for example: 1234-XXXX.
 3|Replace hidden characters by|X|All hidden characters in a voucher code are replaced by “X”, for example: 1234-XXXX.
 **Gift Card usage**|
 4|Gift Cards codes expire after|365|Gift Card can be used within 365 days after being activated.
 5|Maximum time(s) allow to enter gift code incorrectly|5|Customers can just enter a code incorrectly for 5 times.
 6| Maximum number of users per one gift code|1|You can limit that just 1 user can use a gift code.
 7|Allow customers to redeem Gift Cards with usage conditions|Yes|Allow customers to redeem Gift Cards with usage conditions
 8|Use Gift Card for shipping fee|Yes|Gift code or Gift Card credit can be spent for shipping fee, even when ordering Gift Card product.
9|Use Gift Cards with coupon codes|Yes|Customers can use Gift Cards codes and credit balance with system coupon codes to get discount.
 10|Show link to check Gift Card on website|Yes|Enable Customer to check status of Gift Cards after entering gift codes.
 11|Show Gift Card expiry date on website|Yes|Allow showing the expiration date of the Gift Card on frontend
 **Tax Configuration**|
 12|Apply Gift Card discount|Before Tax|Apply Gift Card discount to Customers’ order value (tax excluded).
 
 •	**Gift Card Product page** tab:
 
![Gift Card Product page tab](./GC2%20Image/image030.jpg)

 No.|Field|Sample|Description
---|---|---|---
**Gift Card Value**|
1|Default Gift Card value|25,75,100|Set default Gift Card dropdown values as 25, 75, and 100 in case admin didn’t specify when creating Gift Cards.<br/>***Note**: this configure is only applied to Gift Cards created in previous versions of the extension. Starting from version 4.0, each Gift Card product must have its own value(s) when being created.
2|Description of Gift Card value|The value of Gift Card|Description of Gift Card value shown on **Gift product details** page to explain for Customers (only applied to Gift Cards in versions below 4.0).
**Gift Card template**|
3|Allow customers to change the image inserted into template|Yes|Enable customers to change the image inserted into Gift Card template by uploading their preferred picture.
4|Maximum size of images uploaded by customers |400|Limit the maximum size of images uploaded by customers to 400KB
**Gift Card shipping information**|
5|Allow shipping Gift Card |Yes|Gift Cards can be sent through post office.
6| Minimum days for store owner to send Gift Card through post office|5|After Customers order Gift Cards for friends and choose Send through post office option, Gift Cards will be sent to recipients within 5 days. 
7| Message max length |240| Customers can write a custom message within 240 letters
8|Enable scheduling Gift card delivery| Yes|Allow Customers to set dates to send Gift Cards

![Gift Card template tab](./GC2%20Image/image032.jpg)

No.|Field|Sample|Description
---|---|---|---
1|Show Gift Card box on shopping cart page|Yes|Enable a Gift Card box for customers to apply gift codes right on the shopping cart page.
2|Information displayed on shopping cart page| Gift Card value<br/>Gift Card template<br/>Recipient name| Show selected information of Gift Card on shopping cart page
3|Show Gift Card image as product image in shopping cart|Yes| Allow showing Gift Card printout preview as product image on shopping cart page
4|Show Gift Card box in the Payment section|Yes|Show Gift Card box for customers to apply gift codes right on the Payment Method section at checkout


![On Shopping Cart Page tab](./GC2%20Image/image034.jpg)

No.|Field|Sample|Description
---|---|---|---
**General**|
1| Enable email notification| Yes| Allow sending notification emails to Customers and recipients. 
2|Send Gift Card to friends when Gift Card status is| Active|Gift Card will be sent to friends via email when its status is **Active**
3|Sender of email notification|General Contact|Set the default sender of notification emails as **General Contact**
4|Gift Card notes|<p>{conditions} </p>.| Notes displayed in Gift Card delivery email.
5|Send Gift Card copy via email|Yes| Allow sending a copy of Gift Card via email if Customers choose to ship through post office
6|Attach printable PDF files to Emails|Yes|Allow attaching the printable PDF of the Gift code in the email
**Notification email sent to purchaser**|
7|Send-to-Purchaser email template||Choose the email template sent to purchasers after buying Gift Card successfully.
8|Send-to-purchaser email template when recipient receives Gift Card||Choose the email template sent to purchasers when recipients receive Gift Cards.
**Notification email sent to recipient**|
9|Send-to-recipient email template||Choose the email template sent to Gift Card‟s recipient.
10|Send notification email to recipient when purchaser refunds Gift Card|Yes|Enable email notification sent to recipient when sender refunds Gift Card.
11|Send-to-recipient email template when Gift Card is refunded||Choose the email template sent to recipient when Gift Card is refunded.
12|Auto-send reminder email before Gift Card expires|Yes|Enable auto reminder email sent to Customers before Gift card expires
13|Auto-send reminder email before|5| The number of days to send notification to Customers before the expiration date of a Gift card.

- **Gift Card Printout** tab:

![Gift Card Printout tab](./GC2%20Image/image036.jpg)

No.|Field|Sample|Description
---|---|---|---
1|Logo for PDF Printouts|Default/logo_print.png| Store‟s logo used when Gift Cards are printed or sent via email.
2|Show barcode on Gift Card| Yes|Show barcode on Gift Cards when they are printed or sent via email
3|Type of Barcode|QR code|Show QR code on Gift Cards when they are printed or sent via email.
4|Gift Card notes|Converting to cash is not allowed| The notes shown on Gift Cards when they are printed or sent via email.

###  Manage Gift Card Templates
After installing the module, you can start with Gift Card templates. This function helps you create unlimited templates for Gift Card with different titles, designs, images and notes. You can flexibly customize Gift Cards for different purposes, such as X-mas Gift Card or Birth Day Gift Card, offering Customers a wide range of choices.
To access **Gift Card Template Manager** page, go to **Gift Card** menu → **Manage Gift Card Templates**.

![Manage Gift Card Templates tab](./GC2%20Image/image038.jpg)

The **Gift Card Template Manager** page will be displayed as below:

![Gift Card Template Manager page](./GC2%20Image/image040.jpg)

As you can see, this page lists all available templates in the system. You can add/edit/delete a template and export the list of templates to .CSV/.XML files. If you want to change status /delete templates in mass, simply select  multiple rows, apply an action then click on **Submit** button.
There are 3 default Gift Card templates with 3 different design styles for you to select:
<br/>
    - **Default template 1**: picture aligns with the **left** of Gift Card
<br/>
    - **Default template 2**: picture aligns with the **top** of Gift Card
<br/>
    - **Default template 3**: picture aligns with the **center** of Gift Card
    
![Default Gift Card template 1](./GC2%20Image/image042.jpg)
**Default template 1**
![Default Gift Card template 2](./GC2%20Image/image044.jpg)
 **Default template 2**
 ![Default Gift Card template 3](./GC2%20Image/image046.jpg)
        **Default template 3**
    
If you want to create new Gift Card templates, select **Add Gift Card Template** button and finish the form as below:<br/>
- **General Information** tab:

![General Information tab](./GC2%20Image/image048.jpg)
![General Information tab](./GC2%20Image/image050.jpg)

No.|Field|Sample|Description
---|---|---|---
1|Template name| Gift Card for Xmas| Name of the Gift Card template 
2|Status| Active|Enable this template to be chosen when creating Gift Card product
3| Template design |Left| The image will be aligned with the left of Gift Card.
4|Title|Xmas Gift Voucher| Set the title of Gift Cards using this template as “Xmas Gift Voucher‟ instead of the default title “Gift Card”.
5|Style color| #FFFFFF |Choose color of texts in fields including Title (“Xmas Gift Voucher”), Value and Card number.
6 |Text color| #A9A7A7 |Choose color of other texts (fields‟ name, message, notes, etc.).
7| Background image|| Upload an image to use as a background of Gift Card. Please follow the recommended size for the best result:<br/>- “Top” Template: 600x175 px<br/>- “Left” Template: 350x365 px<br/>- “Center” Template: not available<br/>***Note**: Customers will not be able to change the background image. 
8 |Notes |Converting to cash is not allowed. You can use the Gift card code or redeem it to credit balance to pay for your order|Add notes, such as usage conditions, for Gift Card.|

You can click on **Preview** button at the top right corner to see how Gift Cards using this template will look like. All changes in title, template design, style color and text color will be shown in a popup. If you want to view the background image applied on a Gift Card, click **Save and Continue Edit** button and then preview as above.

- **Images** tab:

![Images tab](./GC2%20Image/image052.jpg)

In this tab, you can create a list of images for Customers to select when buying Gift Card in frontend. Just click on **Add** button and choose image files to upload. 

***Note**: You should use images with the following recommended sizes for better display:<br/>
    -  Template style is “Top”: 600x190px.<br/>    
    - Template style is “Left”: 250x365px.<br/>    
    - Template style is “Center”: 600x365px.
    
Click **Preview** under each image to see how Gift Card will look like. When you finish, remember to click on **Save** or **Save and Continue Edit** to save your work. 
###  Create/Edit a Gift Card Products
There are two ways to create a Gift Card product: on **Manage Gift Card Products** page and on **Manage Products** page.<br/>
- Create Gift Card on **Manage Gift Card Products** page:

Go to **Gift Card** menu→ **Manage Gift Card Products**

![Manage Gift Card Products in menu](./GC2%20Image/image054.jpg)

Click on **Add Gift Card Product** button
You should pay attention to the following tabs:
<br/>
-  **General** tab:
    
![General tab](./GC2%20Image/image056.jpg)
Different from normal products, there is another required field, **Select Gift Card template**, allowing you to choose templates for **Gift Card product**. You can add more templates to this field in Manage Gift Card Templates (please refer to section **3.1** for more details).

![Select Gift Card template](./GC2%20Image/image058.jpg)

After filling in general information, you should pay attention to Advanced Settings to configure Price & Conditions for Gift Card Products
<br/>
        -  **Avanced Pricing** tab:
In **Avanced Pricing** tab, Admin can configure prices and values of a Gift Card Product. 

![Avanced Pricing tab](./GC2%20Image/image060.jpg)

The extension provides 3 **types of Gift Card value**, including **fixed value, range of values** and **dropdown values**. You can base on the type chosen to set Gift Card value(s) accordingly such as 50-100 (USD) for the **range of values type**


The next step you need to do is selecting the type of **Gift Card price**, which could be 1 in 3 following options:
<br/>
    + **Default**: Gift Card price is the same as Gift Card value by default.
<br/>
    + **Fixed number**: Gift Card price is a fixed number as you configure in the next field
<br/>
    + **Percent of Gift Card value**: Gift Card price is a percentage of Gift Card value asyou configure in the next field.
    
If you choose the type of Gift Card price as **Fixed number** or **Percent of Gift Card value**, remember to fill in the next field **Price/ Percentage** to set the price for your Gift Card product.

The following example will help you have better understanding about these
configurations.
<br/>
    + **Type of Gift Card value**: Dropdown values
<br/>
    +**Gift Card values**: 20,30,40
<br/>
    +**Type of Gift Card price**: Percent of Gift Card value
<br/>
    +**Percentage**: 90,90,90

So Customers only have to pay 90% of Gift Card value, which means $36 for a $40 Gift Card for instance.
Remember to click on **Save** button to save your work. After saving, the Gift Card product which you have just created will be shown on **Manage Gift Products** page as below:

![Manage Gift Products page](./GC2%20Image/image062.jpg)
- Create Gift Card on **Catalog Manager** page:
    - Go to **Products** menu → **Catalog**
    
![Catalog tab under Product submenu](./GC2%20Image/image064.jpg)
<br/>
    - In **Add Product** button, click on dropdown menu to select Product Type to be Gift Card as the following screenshot:
    
![dropdown in Add Product button](./GC2%20Image/image066.jpg)
<br/>
    - Click on **Gift Card** for Product Type you want to create and enter information as in **Manage Gift Card Products** page.
<br/>
    -  After saving, Gift Card product which you have just created is shown on both **Manage Products** page and **Manage Gift Products** page as below:
    
![Manage Products page & Manage Gift Products page](./GC2%20Image/image068.jpg)


In order to edit any Gift product, you need to click on corresponding row or link **Edit**.Remember to click on **Save** button after editing to save your work.
###  Generate Gift Codes
This function helps you generate a wide range of synchronous Gift Card codes, then you can print and give them to your Customers.
Go to **Gift Card** menu→ **Generate Gift Codes**, you will be navigated to **Gift Code Pattern Manager** page.

![Generate Gift Codes tab](./GC2%20Image/image070.jpg)

To add a new template to generate gift codes, click on Add Gift Code Pattern button and configure information as below:<br/>
- **General Information** tab:

![General Information tab](./GC2%20Image/image072.jpg)

No.|Field|Sample|Description
---|---|---|---
1|Template name|Gift Card for Christmas|Name of the template to generate gift codes 
2| Gift code pattern |NOEL-[A.4]-[AN.6] |Configure the pattern to generate gift codes in mass as the following example:<br/>[A.8] : 8 alpha characters<br/>[N.4] : 4 numeric characters<br/>[AN.6] : 6 alphanumeric characters<br/>If you enter GIFT-[A.4]-[AN.6] as the sample, the system will auto-create a bunch of gift codes matching this pattern, GIFT-ADFA-12NF0O for example.
3| Gift code value| 50| The fixed value for each gift code generated is $10.
4 |Currency| US Dollar|The currency unit for gift code value is US Dollar.
5| Expired on| 25/12/15| The expiration date for gift codes is December 25th 2015
6| Template ||image Select template image for gift code
7| Gift code Qty.| 10| The number of gift codes generated based on the pattern above is 10.
8| Store View| All Store Views |Customers can use the gift code in all store views.

- **Conditions** tab:

![Conditions tab](./GC2%20Image/image074.jpg)
In this tab, you can set special conditions applied to shopping carts when Customers use gift codes generated to check out.
After setting up, click on **Save Pattern, Save and Continue Edit** or **Save And Generate** button, the template created will be shown in the **Gift Code Pattern Manager** grid as below:

![Gift Code Pattern Manager grid](./GC2%20Image/image076.jpg)
When you click on **Save And Generate** button, gift codes will be auto-generated. After that, **Gift Codes Information** page will show a new tab as below:<br/>
- **Gift Codes Information** tab:

![Gift Codes Information tab](./GC2%20Image/image078.jpg)

Besides viewing details and status of gift codes generated, you can export the list of Gift Card codes to .CSV or .XML file by clicking on the drop-down list **Export to**, choose one of the options provided and then click on **Export** button.

![Export button](./GC2%20Image/image080.jpg)
###  Manage Gift Codes 
Our module enables you to manage gift codes with ease. Go to **Gift Card** menu → **Manage Gift Codes**, you will be navigated to **Gift Code Manager** page.

![Manage Gift Codes in menu](./GC2%20Image/image082.jpg)
![Manage Gift Codes page](./GC2%20Image/image084.jpg)
This page gives you a detailed list of all gift codes in your system, including gift codes created from Gift Card orders in front-end and gift codes created/ generated in back-end. Each gift code is provided with essential information, such as the Initial Value, the Current Balance and gift code‟s status, etc. To help save much time in managing, our module allows you to select multiple gift codes and apply the following action(s) in mass.
<br/>
        - Export the list of gift codes to CSV/XML files
<br/>
        - Change status/send email/delete/print gift codes. Please note that gift codes without recipient email address cannot be sent.
        
![Action button in Manage Gift Codes page](./GC2%20Image/image086.jpg)

Besides, you can add new gift codes manually, import gift codes in bulk from CSV files and edit each gift code by clicking on **Edit** link at the end of each corresponding row.
- If you want to create a new gift code manually, select **Add Gift Code** and finish the form as below:<br/>
   -  **General Information** tab:
         
![General Information tab](./GC2%20Image/image088.jpg)

No.|Field|Sample|Description
---|---|---|---
1 |Gift Code Pattern |GIFT-[A.4]-[AN.6]| Configure the pattern to generate a gift code as the following example:<br/>[A.8] : 8 alpha characters<br/>[N.4] : 4 numeric characters<br/>[AN.6] : 6 alphanumeric characters<br/>If you enter GIFT-[A.4]-[AN.6] as the sample, the system will auto-create a gift code matching this pattern, GIFT-ADFA-12NF0O for example.
2| Gift Code Value| 10 |The fixed value for the gift code is $10.
3| Currency| US Dollar|The currency unit for gift code value is US Dollar
4 |Template| Default Template 1|Gift Card‟s default template 1is used for the gift code generated, in case it is sent to Customers by email or post office.<br/>You can add/ edit templates on **Gift Card Template Manager** page (please refer to section **3.1.** for more details).
5| Template image||Show the image used with the Gift Card template chosen above. You can edit this image on **Gift Card Template Manager** page (please refer to section **3.1.** for more details).
6 |Status| Active| When the gift code‟s status is „active‟, Customers can use it in frontend
7| Expired on| 03/8/16 |The expiration date for the gift code is March 8th, 2016
8 |Store View| All Store Views |Customers can use the gift code in all store views.
9 |Last Comments|| Add Admin‟s notes if needed


   -  **Message Information** tab:
     
If you intend to send the gift code to a specific person, a Customer for example, this tab allows you to add information about the Customer, the recipient and a custom message.
        
![Message Information tab](./GC2%20Image/image090.jpg)
After entering all data, remember to click on **Save**, **Save And Send Email** or **Save and Continue Edit** to save your work.<br/>
- Moreover, you can add new gift codes by importing voucher codes from a CSV file. You need to click on **Import Gift Code** button on the top right corner of the **Gift Code Manager** page.

![Import Gift Code button on the top right corner](./GC2%20Image/image092.jpg)
The **Import Gift Code** page will be shown as below for you to browse a CSV file. And then, click on **Import** or **Import and Print** button

![Import & Import and Print buttons](./GC2%20Image/image094.jpg)
###  Manage Gift Card Credit Balance
- Go to **Customers** menu → **All Customers**
-   Click on any row
- Choose **Gift Card Credit** tab

![Gift Card Credit tab](./GC2%20Image/image096.jpg)
On this page, you can view current Gift Card credit balance and Balance History of a Customer.
In order to change Customers‟ Gift Card balance, you need to enter the amount of money into **"Change Balance"** text field and click on **Save Customer** or **Save and Continue Edit** button. The balance will be updated and the change will be added to **Balance History** grid as below:

![Gift Card credit information page](./GC2%20Image/image098.jpg)
###  Create New Order
On **Create New Order** page, after selecting a Customer and adding a product to an order, the system will show the Gift Card box, which allowing you to use Gift Card credit balance or Gift Card code(s) of the Customer to pay for this order. Select the method(s) as you want and then remember to click on **Apply Gift Card** button.

![Apply Gift Card to new order](./GC2%20Image/image100.jpg)
After applying, the discount from Credit Balance/Gift Card Code will be subtracted from the Subtotal as below:

![Order Totals tab](./GC2%20Image/image102.jpg)
###  Refund Orders
When Customers request for refunding their Product orders which Gift Card credit/ gift code was used as a payment method, the system will show a box to enter the amount of money which will be refunded into Customers‟ credit balance or Gift Card code.
If Customers have their own account on your site, this amount will be refunded into their Gift Card credit balance by default even if they use either their credit balance or Gift Card code to check out.
If Customers don‟t have accounts on your site, this amount will be refunded into their Gift Card codes.

![Refund totals preview](./GC2%20Image/image104.jpg)
***Note**: Once Gift Card is used (redeemed or used to buy other products), it cannot be refunded to cash.
###  History
All actions related to Gift Card such as: **Create, Update, Mass Update, Spend on order, Refund** and **Redeem** are recorded on **Gift Card History** page. Go to **Gift Card** menu → **History** to access this page.
On Gift Card History page, you will know when Gift Cards were created/ updated/ redeemed/ spent/ refunded and by whom as well as their values and status.
You can filter data with the above criteria to get more accurate reports. Information can be exported to .CSV or .XML files for your convenience.

![Export Gift Card History](./GC2%20Image/image106.jpg)
