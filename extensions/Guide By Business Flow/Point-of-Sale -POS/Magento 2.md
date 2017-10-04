# Point-of Sale (POS) - Magento 2 


----------
Confidential Information Notice 

Copyright 2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

 


----------
## Introduction 
It’s so true to claim that POS System’s the revolution for Retailer. This system allows your online as well as offline stores to synchronize product data. Thus,  all the selling process becomes increasingly convenient in a blink for both staff and customer. 

And in those following sections of this materials, the detailed explanation about using POS will be provided to you in the most simple way to get and to do. 
All those steps in using process and  POS functions will be divided into logical parts according to Businees workflow. We hope that under this approaching aspect, users could quickly get familiar, adapt to this amazing system soon. 

With the latest upgraded version and its convenience and the amount of time saved, we hope that you would enjoy and feel exhilarated when experience this newest ones. 

Thanks and Best regards,
Magestore Team 

## Business Workflow ##
### General Process ##

![](./Image%20shadow/image002.png?raw=true)



### POS Order ##
![](./Image%20shadow/image004.png?raw=true)


### POS Return Order ##
![](./Image%20shadow/image006.png?raw=true)


----------
## Permission Matrix ##
The working process of POS System from Magestore is divided into 3 sections:

* General Sales Process
* POS Order
* POS Return Order

In each part, the responsibility for each position in your store is different. 
Here is the detailed assignment: 

### Inventory Staff ##
Inventory Staffs will take charge of these missions: 

* In the step of “Session Management”: not involved
* In the step of “POS Order”:
	 - Check product and quantity on hand
	 - Delivery Product
* In the step of “POS Return Order”:
	 - Receive Product
* In the step of “POS Report”: not involved

### Store Manager ##
This position takes part in almost actions on this POS Sytem throughout 4 steps: 

* In the step of “Sesstion Management”: involved in all the actions
* In the step of “POS Order”: involved in all the actions except Select Customer, Apply Store Credit & Delivery Product.
* In the step “POS Return Order”: involved in all the actions of this step except  “Receive the product”.
* In the “POS Order”: Involved in all the actions.

### Store Saler
This position will undertake those tasks: 

* In the step of  “Session Management” : not involved
 
* In the step of “POS Order”:

	- Search Product and check quantity on hand
	- Create Order
	- Apply Promotion
	- Apply Coupon Code
	- Apply Gift Card
	- Apply Reward Point
	- Select Shipping Method

 - In the Step of “POS Return Order”
	 - Search old orders and check return rules
	 - Create return order
 - In the step of “POS Report”: not involved

### Store Cashier ##
Store Cashier will take the following tasks: 

 - In the step of “Session Management”: involved in all the actions.
 
 - In the step of “POS Order”: involved in all the actions except
   “Delivery Product”
   
 - In the step of “POS Return Order”:
	 - Check old order and return rules
	 - Create Return Order
	 - Check out and Payment
 - In the “POS Report”:
	 - X Report
	 - Z Report

![](./Image%20shadow/image008.png?raw=true)


----------
## How to use  ##
The general workflow of POS System includes 3 parts: 

 - General Sale Process
 - POS Order
 - POS Return Order

And here are the detailed instruction for each section which could help users adapt to this system quickly and effectively. 

### General Sales Process ##
We will explain this workflow according to the timing circle: Opening the store, running and finally, closing.  

-	When first ship of the day started, POS Manager will open session in order to create the Opening Balance - the amount of cash in your store at that time. 

	Those numbers will be saved in the system, so POS could provide you information about daily revenue after a working day. 

	Particularly, when you log in to any POS, a window of opening session will pop-up automatically. 

	![](./Image%20shadow/image010.png?raw=true)
	
	(1) Name of the staff in this session 
	
	(2) Location of POS 
	
	(3) Opening Balance before starting new session
	
	(4) Value of the currency contrbuting to Opening Balance (such as: $100 ) 

	(5) Number of the currency unit (for example : 2) 
	
	(6) Subtotal (you will have: $100 * 2 = $200) 
	
	(7) After checking all the information above, click this button to Open New Session

	 Type the **coin/bill value** > Put in **the number** of those
	   coins/bills  > Click “**Open Session**”

	In case you logged in to POS but no window pop-up automatically like the picture above, then you need to make some change in the back-end system. 
Here is the instruction: 

![](./Image%20shadow/image012.png?raw=true)

Go to “**Store**” > “**Configuration**” > Select “**Magestore Extension**” > **WebPOS**
Select “**Yes**” on this  red frame and please don’t forget to click “**Save Config**” to make it work 

- Next step, after the Opening Balance was saved by POS Manager, Cashiers now are able to create orders and they start running cash flow in your store. 

	They receive the payment from customers and then put the change back to them. Those actions happen in turn, again and again, so your store will have cash in as well as cash out. 


	On the screen of POS System, it will be displayed like this
	
![](./Image%20shadow/image014.png?raw=true)

- Finally, at the end of the day, POS Managers must undertake mission to create Closing Balance, which means they have to confirm the amount of cash in store after all transactions on that day. Then, the system would be able to provide Session Report for Manager. It reflects two things: Cash and Payment Slip

![](./Image%20shadow/image016.png?raw=true)

- 	And now, it’s time for Managers checked Closing Balance. 2 situations could happen in this step: 
	- If the Theory and Real Balance are the same, Managers could directly move to the step of Set Closing Balance, then end this workflow (Session Management) 


	![](./Image%20shadow/image018.png?raw=true)

	-	If the Theory and Real Balance are not the same, Managers have 2 options below to solve this problem; 
				If accept the difference, Manager has to accept the Profit or Loss (with reason) 
				![](./Image%20shadow/image020.png?raw=true)
				
				Otherwise, Staffs have to Put the money in or Take Money out (with reason) 
				
				![](./Image%20shadow/image022.png?raw=true)
				
	(1)	Amount of cash that staff will put in

	(2)	Reason

	(3)	Name of Staff will do this action**

	![](./Image%20shadow/image024.png?raw=true)

	(1)	Amount of cash that staff will take out

	(2)	Reason

	(3)	Name of Staff will do this action


After all, when the Theory Balance’s equal to the Real one, POS Managers are able to “Set Closing Balance”. Then, it ends of the “General Sale Process” Workflow. 

![](./Image%20shadow/image026.png?raw=true)

(1)	The value of currency in the drawer

(2)	Number of those 

(3)	Click “Confirm” to agree with the information displayed above 

### POS Order  ##
Like the flow we explain above, this section is also instructed according to the timing circle. Particularly, it is the customer buying process. 

 - Initially, Customers select products to buy and bring them to Cashier
   to pay.

 

 - Then, Cashier could add them to carts.
 
 	![](./Image%20shadow/image028.png?raw=true)
 	
	![](./Image%20shadow/image030.png?raw=true)
	
 Anyway, one thing to remind retailers is that having a customer card system is extremely necessary for sales strategy. So, it exists a demand from POS System: make sure all of the shoppers, even when they are not regular consumers, have member cards at your store. 
 
- If this buyer were a brand new customer, Cashier would create a new one.  Here is the detailed instruction:
   
![](./Image%20shadow/image032.png?raw=true)
	
![](./Image%20shadow/image034.png?raw=true)

Tap the human icon > “Create Customer”
  
- Otherwise, Cashier could search and create order based on customer history data. All the staffs need to do is typing the customer information (such as: phone number, email, address,..)

 - After adding products to carts, Cashiers would push sales by applying Promotion and Loyalty Program – which are available functions when retailers install specialized extensions for their own POS System. For instance, they are Coupon Code, Gift Card, Reward Point and Store Credit.
   
    ![](./Image%20shadow/image036.png?raw=true)
    ![](./Image%20shadow/image038.png?raw=true)
    ![](./Image%20shadow/image040.png?raw=true)

 - Next step, Cashier must select shipping method:
	 -	Customers would receive goods at store if they buy in-store. 
	 -	The other option is shipping to customer’s address. 

 - Then, Cashiers have to choose payment method
	 - In this step, if customers require invoice, Cashiers will take the output of Customer Invoice. 
	 
	 ![](./Image%20shadow/image042.png?raw=true)
	![](./Image%20shadow/image044.png?raw=true)
	![](./Image%20shadow/image046.png?raw=true)

	

 - After that, Cashier need to validate this POS order to make sure this
   transaction is available.
	 - If this transaction is confirmed as a good delivery, then it will be accomplished in the next few seconds. 
	 - 	Otherwise, Cashier may cancel this order, back to the previous step to serve another customer.
 - Finally, as customers open their wallets to pay for orders, cash flow
   will be created (Cashier will receive money and put the change back).
   It appears the cash-in and out.
   Obviously, all of these cash flows are recorded in the system. 
	- If Cashiers put money in Cash Drawer, Cash-in will be saved with reason.
	- If Cashiers take money out Cash Drawer, Cash-out will be also saved with reason. 

![](./Image%20shadow/image048.png?raw=true)

It is the end of “POS Order” workflow. 

### POS Return Order ##
In case Consumers want to return products, here is the process your staffs need following to deal with the change in data system. 

From the history data of POS Order, Cashiers are able to **check the return rule.** 
If this Return Order is valid, all those steps below need accomplishing: 

 - Cashier will create Return Order 
 - Then, Good Receipt is allowed and the system is available to receive product
 - After that, Customer will be refunded
 
 Here is step-by-step instruction: 

* **Step 1**: Check Refund Policy
 
	- From the history data of POS Order, Cashiers/Sales Staffs are able to check the return rule. If the order meets the refund condition, then POS staffs go to the next process of refunding. 
 
	- NOTE: Some certain staffs have permission to issue refund by cash/credits (which is set by admin in the backend). 


* **Step 2**: Implement Refund Process 
 
	- To issue refund, go to Orders tab in POS screen, choose Orders History, select the order that is required to refund.  Tap on Refund button at the end of the popup.

	![](./Image%20shadow/image050.png?raw=true)


	- A popup will display so that you can fill in the information before making refund.  Tick “Return to stock” if you want to return those items back to your stock.

	![](./Image%20shadow/image052.png?raw=true)

	[1]  Name of the refund product
	[2]  Adjust Refund:
	[3] Adjust Fee:
	[4] Refund by Credits.

	- Instead of refund by cash, you can refund for customer a certain amount of credits to keep them around your store and purchase next time. 
 
	- Hit “**Submit Refund**”. After that, you will get the message informing that credit memo is created successfully.  Please make sure you have permission to issue refund.
 
* **Step 3**: Exchange the product in the order
 
	- If the customer want to exchange the product, create a refund like the same steps above at Make Order(s).  Then create the same order, with the exchange product. After that,  proceed with the order and check out.  

	- End the exchange product.
