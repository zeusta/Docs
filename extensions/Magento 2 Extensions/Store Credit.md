# **STORE CREDIT MAGENTO 2**
(Version 2.0.0)

*Confidential Information Notice*
*Copyright 2016 All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

## INTRODUCTION
Keep the Customers around, that’s what store owners care about! Magento Store Credit extension for Magento 2 allows you to enhance the interaction with your Customers by many activities such as adding credit or refunding Customers by credit. 
Customers can use the credit to make purchases on your store or even share with their friends. 
With Magento Store Credit extension for Magento 2, credit can be used as a convenient and time-saving payment method. Customers just need to recharge their credit accounts one time and then use for many future purchases.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image003.png)

## HOW TO USE (Frontend)
This section will show you how Customers can make use of **Store Credit extension for Magento 2** in Frontend.
### Buy Credit Product
After Customers login to your website, they can access the Store Credit Products page in two ways:

•	**Option 1**: on the top navigation bar, click to **Buy Store Credit** 

•	**Option 2**: click on the **Store Credit** on the left navigation of the **Account Dashboard** page

In this second way, they will be navigated to the **My Credit** page on which they just need to click on the **Buy store credit** button

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image004.png)

After that, the **Store Credit** page will be shown as follows:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image005.png)

As you can see, this page lists all **Credit Products** of your website. There are three types of credit products for Customers to choose:

•	**Fixed Value**: These credit products have fixed value. 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image006.png)

•	**Drop-down Values**: With this type, Customers can select a specific value in the drop-down list.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image007.png)

•	**Range of Values**: With this type, Customers can choose a desired credit amount within the range configured by admin in backend. 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image008.png)

After selecting credit products they like, Customers can add them to cart and checkout normally.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image009.png)

When the order is complete, our module will auto-add that credit amount to the Customer’s credit balance.
Customers can also send Credits to their friends by ticking **Send credit to friend** checkbox and enter all the required fields:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image010.png)

•	**Recipient name**: the name of the recipient 

•	**Recipient email address**: the email address of the recipient. The system will send an email to this address

•	**Custom message**: the message that recipient will receive

When the order is completed, there will be two cases happening based on signup status of the recipient email address.

•	**Case 1**: if the recipient do not have an account in the system, an email as below will be sent 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image011.png)

•	**Case 2**: if the recipient has already had an account in the system, the system will automatically add that credit amount to the Recipient’s credit balance

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image012.png)

In both cases, the sender always gets email notifications as below:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image013.png)

###  Manage Credit on My Credit page
In order to access the **My Credit** page, Customers can click on the **Store Credit** tab on the left navigation.
#### Manage Credit Balance
On the **My Credit** page, Customers can view information about their current credit balances and transaction history.
In the section **Transaction History**, our module shows Customers all of their credit transactions with a lot of information including **date, type, details, added/deducted value in transaction** and **credit balance**.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image014.png)

####  Send Credit to Friends
First, Customers should click on the **Send Credit** tab on the left navigation to go to the **Send Credit to Friends** page.
This page has 2 parts including **Send Credit to Friends** and **Credit Code List**.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image015.png)

•	**Send Credit to Friends**: allows Customers to send credit to their friends by filling in all required information

•	**Credit Code List**: shows all information about the credit codes that Customers sent to their friends including **code, recipient’s email, amount, sent date** and **status of code**. Credit codes are not displayed fully for security purpose. When Customers click on, they will be shown clearly.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image016.png)

Please note that our module allows you to configure whether to require your Customers to verify their credit sharing or not. We will consider the two cases separately.
>>**a.	Case 1: Customers are not required to verify their credit sharing**.

In order to send credit to friends, Customers should enter the recipient’s email and credit amount in the text fields. Our module will check that email address and show notification to Customers.

•	**If the recipient’s email has not been registered on the website**: 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image017.png)

In this case, our module will show a notification for the Customer that his friend will receive the credit code via that email. The Customer can enter a message and click on the **Send** button. After that, the sender’s credit balance will be deducted immediately and an email will be auto-sent to the recipient’s email address.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image018.png)

As you can see, this email informs the recipient about the credit amount, message and a credit code which can be used to redeem credit to his balance.
At the same time, the sender can also see the sent credit code in the **Credit Code List** section as below:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image019.png)

In this section, Customers can follow the status of the credit codes they sent. While the recipient has not redeemed a credit code, Customers are allowed to cancel it by clicking on the **Cancel** link in the **Action** column. After the cancellation, the recipient cannot redeem that credit code any more.
Otherwise, once the credit code has been redeemed, the status will be updated and the **Cancel** link will be disabled. Please refer to the section **2.2.3. Redeem** Credit for more information.
Customers can check their current balances and transactions of sharing credit in the **Transaction History** section.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image020.png)

•	**If the recipient’s email has been registered on the website**: 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image021.png)

If the recipient’s email address has been registered on your website, our module will send credit directly to his credit balance instead of sending credit code to his email.
Customers can check their current balances and transactions in the **Transaction History** section.


![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image022.png)

At the same time, recipients can get information about this transaction:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image023.png)

>>**b.	Case 2: Customers are required to verify their credit sharing**.

If you configure that Customers have to verify before sharing credit, after clicking on the **Send** button, they will receive an email as below:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image024.png)

At the same time, they will be navigated to the **Verify** page:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image025.png)

On this page, our module shows them a notification about the verification requirement. In the **Credit Code List**, that code is put under the “**Awaiting verification**” status with a Verify link. 

To verify, Customers just enter the verification code they received in their emails and then click on the **Submit Code** button.

After Customers finish verifying, our module will send credit to the recipient.

####  Redeem Credit
In order to go to the **Redeem Credit** page, Customers can click on the **Redeem Credit** tab on the left navigation.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image026.png)

On this page, Customers can redeem the credit code they received to their credit balance by entering the code in the text field before clicking on the **Redeem** button. Another way is just to click on the link in the email.

After redeeming code, Customers can check their current balance and transaction in the **Transaction History** section.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image027.png)

### Checkout by Credit
Customers can use credit to checkout on both **Shopping Cart** and **Checkout page**.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image028.png)

On the **Shopping Cart** page, our module will add **Apply Credit Discount** block for Customers to use their credit balances to checkout.

To use a credit amount, Customers can first enter that number in the field and then click on the **Apply** button. Our module will auto-update and calculate the grand total of order.

Please note that Customers cannot use credit to buy credit products. If their carts have one or more credit products, our module will show a notification in the **Customer Credit** block as below:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image029.png)

On the **Checkout** page, in the **Payment Information** tab, Customers can also use credit to check out by ticking on the checkbox and then enter a credit amount they want.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image030.png)

When Customers click on the **Continue** button, our module will auto-update the order’s Grand Total.

After order has been placed, Customers’ credit balances will be updated immediately. They can check the current balances and transactions in the **Transaction History** section.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image031.png)

##  HOW TO CONFIGURE
### Manage Customers Using Credit
Go to **Store Credit > Manage Customers Using Credit**

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image032.png)

Then the **Customers Using Credit Manager** page will be displayed as below:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image033.png)

This page shows a list of all Customers using credit and their information such as name, email, credit balance, telephone, etc.

In order to view more details about a Customer, you can click on the **Edit** link in the **Action** column.

Then, you will be navigated to the **Customer Information** page. By selecting **Store Credit** tab, you can view all of that Customer’s transaction history and credit balance:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image034.png)

Besides, you can change the Customer’s credit balance by entering an integer (a positive or negative number) and a comment in text fields as below:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image035.png)

Our module will auto send email to Customer to announce about this transaction if you tick on **Send email to customer** checkbox. The email will be sent to the customer as bellow: 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image036.png)

After you save, our module will auto update the Customer’s credit balance, send an email to that Customer and create a transaction as follows:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image037.png)

### Manage Credit Products
Go to **Store Credit > Manage Credit Products**

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image038.png)

Then the **Credit Product Manager** page will be shown:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image039.png)

This page shows you all credit products with a lot of information such as **product ID, name, SKU, quantity, status**, etc.

In order to add a new credit product, you can click on the **Add Credit Product** button on the right top of the page.

You can add a credit product just in a similar way to adding a normal product. You should pay attention to these following tabs:

•	**Prices Tab**:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image040.png)

In this tab, you can configure the value of the credit product. There are three types of credit products including **fixed value, range of values** and **drop-down value**.

•	**Inventory Tab**:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image041.png)

In this tab, by default, our module sets up the field **Manage Stock** as **Yes**. It means that you need to manage the quantity of credit products.

Besides the **Credit Product Manager** page, you can also create a new credit product by clicking on the **Add Product** button on the **Manage Product** page:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image042.png)

Then you will be navigated to the **New Product** page. In the **Settings** tab, you need to select **Credit Product** for the **Product Type** field before going on to configure the product as above.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image043.png)

###  Manage Credit Transactions and Report Charts
####  Credit Transactions
Go to **Store Credit > Manage Credit Transactions**

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image044.png)

Then the **Credit Transactions** page will be shown: 

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image045.png)

This page shows all credit-related transactions with a lot of information such as **type, detail, customer name/email, added/deducted credit, credit balance after transaction**.

You can search any transaction by using filter boxes in each column.

If you click on a Customer’s email, you will be navigated to the **Customer Information** page.
#### Credit Report Charts
Go to **Store Credit > Customer Credit Report**

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image046.png)

Then the **Report Charts** page will be shown as follows:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image047.png)

This page can be divided into two main sections including **Life-time Reports and Period-of-time Report Charts**.

•	**Life-time Reports**: There are 2 types of reports.
-  	**Customer Credit Statistics** with the total credit, the total spent credit and the number of Customers with credit in your system.
-	**Top 5 Customers with The Greatest Credit Balances** with their names and current balances in your system.

•	**Period-of-time Report Charts**: This chart shows you the total spent credit and received credit of all Customers per day in your chosen time range such as **last 24 hours, last 7 days, current month**, etc.

### Using Credit to checkout in backend:

On the **Create Order** page on backend, our module allows you to use credit when creating orders for Customers.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image048.png)

You just need to enter a credit amount and click on the **Gray Arrow** button. Our module will auto-update and calculate the grand total of the order.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image049.png)

After submitting the order, the Customer’s credit balance will also auto updated and you can check the transaction on the **Credit Transaction** page.

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image050.png)

###  Refund Orders into Credit Balance
When Customers want to refund an order, our module allows you to transfer the order value to his credit balance. In that way, Customers can use the credit for future purchases and you do not have to lose money for the refund at the same time.

After clicking on the **Credit Memo** button, our module shows a text field for you to enter the amount you want to refund into credit:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image051.png)

After that, when you click on the **Refund Offline** button, the amount you entered as well as the credit that the Customer used for paying for the order will be refunded to his current credit balance. 

For any order that includes only Credit Product, the option **Refund Order to Credit** is not available.

Once the refund is finished, you can check the transaction on the **Manage Transaction** page:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image052.png)

### Settings
Go to **Store Credit > Settings**

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image053.png)

•	**General Configuration** Tab:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image054.png)

Title|	If you choose|	Result will be
--|-|-
Enable|	Yes	|Store Credit is enabled on your site
Allow sending credit|	Yes	|Your Customers can send credit to their friends
Verify before sending credit|	Yes|	Your Customers are required to verify before sending credit to friends
Groups can use credit|	General	|Only General Customers can use credit

•	**Spend Credit On** Tab

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image055.png)

Title|	If you choose|	Result will be|
-|-|-
Apply Customer Credit|	After tax|	Apply Customer credit discount to Customer’s order value after tax calculated
Shipping Fee|	No	|Credit balance cannot be used to pay for Shipping Fee

•	**Email Configuration** Tab:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image056.png)

•	**Adjust time for Customer credit reports on total used and total received credit** Tab:

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image057.png)

•	**Style Configuration** tab: on this tab, you will be able to change background and color of Title

![Storecredit](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/SC%20Image/image058.png)

*This is the end of the Store Credit User Guide. We hope that this manual is helpful for you to use the extension effectively. If you have any question, feel free to contact us at support@magestore.com, we would be glad to assist you!*
       












 



















