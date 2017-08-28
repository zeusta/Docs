# ORDER FULFILLMENT - MAGENTO 2
**Version 1.0.0**


*Confidential Information Notice*<br/>
*Copyright2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*


**Tip:** To discover all functions more easily, turn on your **Bookmark bar** in PDF reader software (View → Navigation Panels → Bookmarks) to view the navigation of this manual.

![Bookmark bar](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img1.png)


## Introduction

Have high volume of sales orders & worry about messy shipments? You should have an effective order management strategy in order to save costs and gain profits. 

Order Fulfillment is one extension for Magento 2, which helps you easily keep track of order-fulfilling process in the backend. With default Order Fulfillment, tons of your orders can be managed easily. In addition, this Magento 2 extension is:

•	Compatible with Magento CE 2.1.0 - 2.1.1 - 2.1.2

•	Open source 100%

•	License Certificate valid for 1 live Magento installation and unlimited test Magento installations (No license key required)

•	Easy to install and configure

•	User-friendly interface


## How to check order fulfillment

Have high volume of sales orders & worry about messy shipments? Then Order Fulfillment for Magento 2 is the perfect solution for your problem! From now on, you can easily prepare shipments in 5 simple steps:

1. Verify orders
2. Check stock availability
3. Pick items
4. Pack items
5. Delivery packages


### Order fulfillment dashboard


To have an overview of your order fulfillment process, you go to Fulfillment > Dashboard. On the Overview Dashboard, you can see 5 charts which offer you the summary of Order Fulfillment. They are:

•	Orders by status report

•	Orders by day report

•	Orders by carriers report

•	Picked requests by day report

•	Packed requests by day report

With this Magento 2 extension, you can custom time range, print or download each report in multiple forms: PNG image, JPEG image, PDF document and SVG vector image.

![Custom time range](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img2.png)


### Five steps to manage order fulfillment


Order Fulfillment allows you to create new orders right in this extension by going to **Fulfillment > All Orders** (in Order Listing section). Choose **Create a new order** button then enter required information to create new orders.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img3.png)

After a new order is created, you can go to Fulfillment tab to manage that order shipment according to 5 default steps.


####  Verify order


Go to the Verify Orders tab. This page will list all orders that need to be verified. This verification step allows you to verify, hold or cancel orders. This step is optional so if it is not useful for your business, you can turn it off by going to **Fulfillment > Order Configuration** and choose ***No*** in **Enable Verify Order Step** field.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img4.png)

Click on **Process Verify** button of each order you want to verify, contact customers to double check all information, then choose **Mark as verified** button like the screenshot below: 

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img5.png)

You can also hold this order if it cannot be verified at this time. After that, the order will be moved to next step so that you can prepare for fulfillment before picking and packing items. Go to the next step by clicking on the **Prepare Fulfillment** tab.

There are many extra options helping you verify orders better:

•	Batch:

Users can create batches to mark orders they are verifying. Staffs are not allowed to see orders in the batch created by others. They see orders in the batch they create and orders which are not in any batches.

Admin has permission to check orders information and staff in batches.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img6.png)

Choose **Process Verify** button to add each order to a batch or add orders to a batch in mass.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img7.png)

Order Batch in this number can be kept the same as in Prepare Fulfillment step. To configure this option, go to **Fulfillment > Order Configuration** and choose ***Yes/No*** in **Keep Order Batch Number** after verified field.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img8.png)

•	Tag:

Many orders may have the same situation and you can save time on verifying them by Tag options. Each tag can be modified to fit your business model (including color and title for each tag. Go to **Fulfillment > Order Configuration** and follow the image below:

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img9.png)

There are 2 ways to add tags for an order: Enter tags in line or Add tags via **Process Verify** button. Adding tags for orders in mass is also allowed.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img10.png)

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img11.png)

•	Notes:

In this system, you can clarify orders by noting extra information. As usual, notes can be added right in line or via **Process Verify** button. 

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img12.png)

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img13.png)

Orders with notes have highlighted icons: ![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img14.png)

•	Filter:

This step allows you to find orders easily by filtering them on Total value, Created date, ID, Recipient, Status, Batch & Tags

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img15.png)

•	Print:

In this step, you can print the list of orders which need to be verified. Tick to choose orders and select **Print** in mass actions

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img16.png)


#### Prepare Fulfillment


After being verified, order will be moved to this step – Prepare Fulfillment. This verification step allows you to separate orders into 2 groups based on inventory availability: The ones that have all items in stock (Request pick from warehouses) & the ones that lack some of items (Back order). Thus, you can know the priority of which orders can be fulfilled first. Follow these steps to prepare fulfillment for your orders

*Step 1:* Click on **Fulfill** button of the order you want to prepare fulfillment then the request will appear. 

*Step 2:* Choose the suitable Shipping Channel (Request pick from warehouses / Back order) and select **Add Products to Request** button. 

*Step 3:* Products in this order will automatically listed. Tick to choose product and enter the order Qty. After that, click on **Add Selected Product(s) to Request** button. In case, there are both available and out-of-stock items, choose **Add Fulfillment Request** to create another request for the order.

*Step 4:* Do not forget to save all your work.

In Prepare Fulfillment step, you can use batch, tag and note as in Verify Orders step. In case, some orders need to be re-verified, you can get them back to Verify Orders step.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img17.png)

As for Print option, you should print documents for the next step, including invoices, packing slips, credit memos & shipping labels. It is allowed to print all kinds of document with only one click.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img18.png)


####  Picking Items


On the Picking Items dashboard, you have a picking list and pick all items of these orders easily. Just follow 3 following steps: 

- Select the warehouse to pick items
- Choose one or many orders to pick items
- Pick items for each order

***Step 1: Select the warehouse to pick items***

Each staff is assigned to warehouse. Firstly, you need choose the warehouse you are about to work with.

***Step 2: Choose order(s) to pick items***

After being fulfillment-prepared, orders will be directly moved to this tab. You can view detail of each order and pick items for it. Another way to choose orders is that scanning the pick ID: Click on **Scan Picked Orders** button and scan the pick ID to get orders. After the order is found, products in this order will be shown with Qty to pick.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img19.png)

***Step 3: Pick items for each order***

Picking List is able to be printed in this step. There are 2 options of Picking List: Group by Pick # & Group by Product. You can pick items for many orders at once by selecting multiple orders when printing picking list.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img20.png)

Pick items and scan their barcode to keep Picked Qty is the same as Qty To Pick. Although it is not recommended, you can manually click on plus buttons or **Mark as Picked / Mark Picked All Items** to finish picking items for an order. After that, the order will be automatically moved to **Pack Items** step.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img21.png)

If you have a product barcode attribute, you can select it as the product barcode. To configure this, go to **Fulfillment > Fulfillment Configuration** and configure Product Attribute.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img22.png)

In Pick Items step, you can use batch as in Verify Orders step. In case, some orders need to be re-verified, you can get them back to Verify Orders step.


#### Packing Items


In the dashboard of packing items, each order will be packed with its items. Follow these 4 steps to manage this:

- Select the warehouse to pack items
- Choose one or many orders to pack items
- Recheck item Qty of each order
- Pack items into package

***Step 1: Select the warehouse to pack items***

Each staff is assigned to warehouse. Firstly, you need choose the warehouse you are assigned.

***Step 2: Choose order(s) to pack items***

After you complete picking items, orders will be directly moved to this tab. You can view detail of each order and pack items for it. Another way to choose orders is that scanning the pick ID. After the order is found, its pack request information will be shown.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img23.png)

***Step 3: Recheck item Qty of each order***

To keep everything work in the right way, you should recheck item Qty of each order. You can do this quickly by scanning item barcode or manage this step manually by select plus buttons.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img24.png)

***Step 4: Pack items for each order***

After recheck items of each order, you need to pack all into package(s). It is allowed to create multiple packages for an order: Click on **Pack** button then choose **Add Products to Package**. Now you need to select products and enter some additional information. If you want to divide an order into multiple, select **Add Package** button to pack a new package.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img25.png)

If you want to use Magento default ship, go to **Fulfillment > Order Configuration** to configure this.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img26.png)

Order Fulfillment for Magento 2 allows you to take picture of the packages after they are created. Go to **Fulfillment > Fulfillment Configuration** to enable this.

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img27.png)


#### Delivery Packages


In the last step, all shipped orders will be shown here with details, including the information of items in the packages, shipping information, & tracking number from your shipping carrier for you to check back anytime you want. 

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img28.png)


## Order listing

In this dashboard, orders will be classified into 5 types: Awaiting Payment, Back Orders, Hold Orders, Complete Orders & Canceled Orders. Order Listing is designed to help you manage all orders better than Magento default system. 

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img29.png)


## Report 

There are 4 types of reports which record how many orders have been picked and packed. They are

-	Fulfillment  by ware house
-	Fulfillment by warehouse (daily)
-	Fulfillment by staff 
-	Fulfillment by staff (daily)

![](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/OF%20Images/of-img30.png)

