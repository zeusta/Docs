**STORE CREDIT - MAGENTO 1**
==============
**Version 2.0**
Confidential Information Notice. Copyright 2016 All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
## Introduction



How to engage your Customers more in one’s business is a regular question in store-owners’ minds! With Magento Store Credit extension, you can enhance the interaction with your Customers by many activities such as adding credit or refunding Customers by credit. After that, Customers can use the credit to make purchases on your store or even share with their friends. Also with Magento Store Credit extension, credit can be used as a convenient and time-saving payment method when it just requires your Customers to recharge their credit accounts one time and then use for many future purchases.

![enter image description here](./Magento%201%20Extensions/image_Store%20Credit%20M1/image001.png?raw=true)

## How to use 



### Buy Credit Product
After Customers login to your website, they can access the **Store Credit** page in two ways.

Firstly, clicking on the **My Account** link, they can choose **Buy Store Credit** in the dropdown list. 
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image002.png?raw=true)

Secondly, they can click on the **My Credit** tab on the left navigation on the **My Account** page.

In this second way, they will be navigated to the **My Credit** page on which they just need to click on the **Buy store credit** button:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image003.png?raw=true)

After that, the **Store Credit** page will be shown as follows:
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image004.png?raw=true)

As you can see, this page lists all credit products of your website. There are three types of credit products for Customers to choose:

 - ***Fixed Value***: These credit products have fixed value.
 
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image005.png?raw=true)

 - ***Option Value:*** With this type, Customers can select a value option in the drop-down list box.
 
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image006.png?raw=true)

 - ***Range Value***: With this type, Customers can choose a desired credit amount within the range configured by admin in backend.
 
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image007.png?raw=true)

 After selecting credit products they like, Customers can add them to cart and checkout normally.
 
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image008.png?raw=true)

When the order is complete, our module will auto-add that credit amount to the Customer’s credit balance.

Customers can also send Credits to their friends by ticking **Send credit to friend** checkbox and enter all the required fields:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image009.png?raw=true)

 - **Recipient name**: the name of the recipient
 - **Recipient email address**: the email address of the recipient. The
   system will send an email to this address.
 - **Custom message**: the message that recipient will receive

When the order is complete, if the recipient do not have an account in the system will receive an email as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image010.png?raw=true)

If the recipient has an account in the system, our module will auto-add that credit amount to the Recipient’s credit balance.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image011.png?raw=true)

The sender always gets email notifications as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image012.png?raw=true)

### Manage Credit on My Credit page
In order to access the **My Credit** page, Customers can click on the **My Credit** tab on the left navigation.
#### Manage Credit Balance
On the **My Credit** page, Customers can view information about their current credit balances and transaction history.

In the section **Transaction History**, our module shows Customers all of their credit transactions with a lot of information including ***date, type, details, added/deducted value in transaction*** and ***credit balance.***

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image013.png?raw=true)

#### Send Credit to Friends
First, Customers should click on the **Send Credit** tab on the left navigation to go to the **Send Credit to Friends** page.

This page has 2 parts including **Send Credit To Friends** and **Credit Code List**.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image014.png?raw=true)

•	***Send Credit to Friends***: In this section, Customers can send credit to their friends.

•	***Credit Code List***: This section shows all information about the credit codes that Customers sent to their friends including ***code, recipient email, amount, sent date*** and ***status of code***. Credit codes are not displayed in full for security purpose. When Customers click on, they will be shown clearly.

Please note that our module allows you to configure whether to require your Customers to verify their credit sharing or not. We will consider the two cases separately.

**Case 1: Customers are not required to verify their credit sharing.**

In order to send credit to friends, Customers should enter the recipient’s email and credit amount in the text fields. Our module will check that email address and show notification to Customers.
 	
 - **If the recipient’s email has not been registered on the website:**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image015.png?raw=true)

In this case, our module will show a notification for the Customer that his friend will receive the credit code via that email. The Customer can enter a message and click on the **Send** button. 
After that, his credit balance will be deducted immediately and an email will be auto-sent to the recipient’s email address:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image016.png?raw=true)

As you can see, this email informs the recipient about the credit amount, message and a credit code which can be used to redeem credit to his balance.

At the same time, the sender can also see the sent credit code in the **Credit Code List** section as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image017.png?raw=true)

In this section, Customers can follow the status of the credit codes they sent. When a recipient has not redeemed a credit code, Customers are allowed to cancel it by clicking on the **Cancel** link in the **Action** column. After the cancellation, the recipient cannot redeem that credit code any more.

Otherwise, once the credit code has been redeemed, the status will be updated and the Cancel link will be disabled. Please refer to the section **Redeem Credit** for more information.

Customers can check their current balances and transactions of sharing credit in the **Transaction History** section.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image018.png?raw=true)

 - **If the recipient’s email has been registered on the website:**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image019.png?raw=true)

If the recipient’s email address has been registered on your website, our module will send credit directly to his credit balance instead of sending credit code to his email.
Customers can check their current balances and transactions in the **Transaction History** section.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image020.png?raw=true)

At the same time, recipients can get information about this transaction:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image021.png?raw=true)

**Case 2: Customers are required to verify their credit sharing.**

If you configure that Customers have to verify before sharing credit, after clicking on the **Send** button, they will receive an email as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image022.png?raw=true)

At the same time, they will be navigated to the **Verify** page:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image023.png?raw=true)

On this page, our module shows them a notification about the verification requirement. In the **Credit Code List**, that code is put under the “**Awaiting verification**” status with a **Verify** link. 

To verify, Customers just enter the verification code they received in their emails and then click on the **Submit Code** button.

After Customers finish verifying, our module will send credit to the recipient.

#### Redeem Credit

In order to go to the **Redeem Credit** page, Customers can click on the **Redeem Credit** tab on the left navigation.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image024.png?raw=true)

On this page, Customers can redeem the credit code they received to their credit balance by entering the code in the text field before clicking on the **Redeem** button. Another way is just to click on the link in the email.
After redeeming code, Customers can check their current balance and transaction in the **Transaction History** section.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image025.png?raw=true)


### Checkout by Credit

Customers can use credit to checkout on both **Shopping Cart** and **Checkout page**.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image026.png?raw=true)

On the **Shopping Cart** page, our module will add a **Customer Credit** block for Customers to use their credit balances to checkout.
To use a credit amount, Customers can first enter that number in the field and then click on the **Apply** button. Our module will auto-update and calculate the grand total of order.
Please note that Customers cannot use credit to buy credit products. If their carts have one or more credit products, our module will show a notification in the **Customer Credit** block as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image027.png?raw=true)

On the **Checkout page**, in the **Payment Information** tab, Customers can also use credit to check out by ticking on the checkbox and then enter a credit amount they want.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image028.png?raw=true)

When Customers click on the **Continue** button, our module will auto-update the Grand Total of the order.
After order has been placed, Customers’ credit balances will be updated immediately. They can check the current balances and transactions in the **Transaction History** section.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image029.png?raw=true)

## HOW TO CONFIGURE
### Manage Customers Using Credit
Go to **Store Credit > Manage Customers Using Credit**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image030.png?raw=true)

Then the **Customers Using Credit Manager** page will be displayed as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image031.png?raw=true)

This page shows a list of all Customers using credit and their information such as name, email, credit balance, telephone, etc.
In order to view more details about a Customer, you can click on the **Edit** link in the **Action** column.

Then you will be navigated to the **Store Credit** tab on the **Customer Manage** page that shows you all of that Customer’s transaction history and credit balance:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image032.png?raw=true)

Besides, you can change the Customer’s credit balance by entering an integer (a positive or negative number) and a comment in text fields as below:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image033.png?raw=true)

Our module will auto send email to Customer to announce about this transaction if you tick on **Send email to customer** checkbox. The email will be sent to the customer as bellow: 

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image034.png?raw=true)

After you save, our module will auto update the Customer’s credit balance, send an email to that Customer and create a transaction as follows:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image035.png?raw=true)

### Manage Credit Products
Go to **Store Credit > Manage Credit Products**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image036.png?raw=true)

Then the **Credit Product Manager** page will be shown:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image037.png?raw=true)


This page shows you all credit **products with a lot of information such as product ID, name, SKU, quantity, status,** etc.
In order to add a new credit product, you can click on the **Add Credit Product** button on the right top of the page.
You can add a credit product just in a similar way to adding a normal product. You should pay attention to these following tabs: 


 - **Prices** Tab:
 
![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image038.png?raw=true)

In this tab, you can configure the price of the credit product. There are three kinds of credit products you can use including **fixed price**, **option price** and **range price.**


 - **Inventory** Tab:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image039.png?raw=true)

In this tab, by default, our module sets up the field **Manage Stock** as **No**. It means that you do not need to manage the quantity of credit products.
Besides the **Credit Product Manager** page, you can also create a new credit product by clicking on the **Add Product** button on the **Manage Product** page:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image040.png?raw=true)

Then you will be navigated to the **New Product** page. In the **Settings** tab, you need to select **Customer Credit** for the **Product Type** field before going on to configure the product as above.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image041.png?raw=true)

### Manage Credit Transactions and Report Charts
#### Credit Transactions
Go to **Store Credit > Credit Transactions > Credit Transactions**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image042.png?raw=true)

Then the **Credit Transactions** page will be shown: 

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image043.png?raw=true)

This page shows all credit-related transactions with a lot of information such as **type, detail, customer name/email, added/deducted credit, credit balance** after transaction and **transaction time**.
You can search any transaction by using filter boxes in each column.
If you click on a Customer’s email, you will be navigated to the Customer Manager page.

#### Credit Report Charts
Go to **Store Credit > Credit Transactions > Credit Report Charts**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image044.png?raw=true)

Then the **Report Charts** page will be shown as follows:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image045.png?raw=true)

This page can be divided into two main sections including **Life-time Reports** and **Period-of-time Report Charts.**



 - **Life-time Reports**: There are 2 types of reports.
 
	-***Customer Credit Statistics*** with the total credit, the total spent credit and the number of Customers with credit in your system.
 	
 	-***Top 5 Customers with The Greatest Credit Balances*** with their names and current balances in your system.	
  
 
 - **Period-of-time Report Charts:** This chart shows you the total spent credit and received credit of all Customers per day in your
   chosen time range such as **last 24 hours, last 7 days, current
   month,** etc.

### Using Credit to checkout in backend:
On the **Create Order** page on backend, our module allows you to use credit when creating orders for Customers.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image046.png?raw=true)

You just need to enter a credit amount and click on the **Use Credit** button. Our module will auto-update and calculate the grand total of the order.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image047.png?raw=true)

After submitting the order, the Customer’s credit balance will also auto updated and you can check the transaction on the **Credit Transaction** page.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image048.png?raw=true)

### Refund Orders into Credit Balance

When Customers want to refund an order, our module allows you to transfer the order value to his credit balance. In that way, Customers can use the credit for future purchases and you do not have to lose money for the refund at the same time.
After clicking on the **Credit Memo** button, our module shows a text field for you to enter the amount you want to refund into credit:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image049.png?raw=true)

After that, when you click on the **Refund Offline** button, the amount you entered as well as the credit that the Customer used for paying for the order will be refunded to his current credit balance. 
Once the refund is finished, you can check the transaction on the **Manage Transaction** page:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image050.png?raw=true)

### Settings
Go to **Store Credit > Settings**

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image051.png?raw=true)

 - **General Configuration** Tab:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image052.png?raw=true)

|Title     | If you choose        | Result will be |
|----------------------------------|-------------------|----------------------------|
|Enable|Yes|The module is enabled on your site.|
|Allow sending credit|Yes| Your Customers can send credit to their friends. | 
|Verify before sending credit|Yes| Your Customers are required to verify before sending credit to friends.| 
|Groups can use credit| General| Only General Customers can use credit.| 

 - **Spend Credit On** Tab
 
 ![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image053.png?raw=true) 

|Title     | If you choose        | Result will be |
|-------------------------------------|---------------------|----------------------------|
|Apply Customer Credit|After tax|Apply Customer credit discount to Customer’s order value after tax calculated|
|Shipping Fee|No| Credit balance cannot be used to pay for Shipping Fee. | 
	

 - **Email Configuration** Tab:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image054.png?raw=true)


 - **Adjust time for Customers credit reports on total used and total received credit** Tab:

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image055.png?raw=true)


 - **Style Configuration** tab: on this tab, you will be able to change background and color of Title

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/image_Store%20Credit%20M1/image056.png?raw=true)

This is the end of Store Credit User Guide. We hope this manual is helpful for you to use the extension effectively. If you have any question, please contact us at support@magestore.com , we would be glad to assist you!
