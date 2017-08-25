Magento Barcode Management
===================
Version 1.0

Confidential Information Notice 

Copyright 2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.


## 1. INTRODUCTION
-------------

Barcode by definition is the small image of lines (bars) and spaces that is affixed to retail store items, identification cards, and postal mail to identify a particular product number, person, or location. The code uses a sequence of vertical bars and spaces to represent numbers and other symbols. Barcode is a reliable method for cutting costs and savingtime for business.

Barcode management extension from Magestore provides your business with a handful solution to generate barcode, print barcode label and scan barcode, all in one.

## 2. How it works
-------------------

### 2.1. Barcode listing

Barcode listing is a view to display all barcodes of all products saved in Inventory Management. It contains Barcode, SKU, Supplier and Purchased Time.

From this screen, admin can instantly take actions like importing or generating barcode with 5 buttons on the top right.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image001.png?raw=true)

Admin can also view details of each product and barcode. 

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image002.png?raw=true)

From barcode detailed page, admin can configure barcode printing and print barcode directly. Product information is shown including Image, name, price and its availability in each warehouse.

### 2.2. Generate barcode


Inventory Management gives you 2 modes to generate barcode:
- One barcode per product SKU
- Multiple barcodes per product SKU
This can be configured in Barcode Settings.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image003.png?raw=true)

- If you set “One barcode per product SKU” as “Yes”, then the system will allow you to generate only one barcode for one product SKU.
Now to generate barcode, you go to Generate Barcodes tab. From here you can select the product that you want to generate barcode, fill in the Supplier (optional) then generate.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image004.png?raw=true)

If you set “One barcode per product SKU” as “No”, then it opens up 2 options to generate barcode when you go to Generate Barcodes tab.

- Generate Barcode

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image005.png?raw=true)

These 2 options are: Generate barcode per item or Generate barcode per purchase.
“Generate barcode per item” means each item will have its own identified barcode although they have the same SKU.

“Generate barcode per purchase” means items will be identified by the time it is purchased. Although you take 10 items with same SKU in one time purchasing from supplier, these 10 items will have the same barcode. But in another time of purchase, they will have different barcode.

After selecting the option you want to proceed with, you can continue selecting product, fill the product Qty., supplier and purchased time (optional) then generate. 

Admin can configure the barcode pattern to generate. Barcodes generated will be saved in Barcode listing page &amp; Barcode creating history.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image006.png?raw=true)

### 2.3. Import barcode

When you generate barcodes in mass, you will not need to use Generate barcode feature. Instead, you can import barcode directly into the system using the **Import barcode** feature of Inventory Management.

The system provides a sample import file including SKU, Barcode, Qty. and Supplier &amp; Purchase time (optional).

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image007.png?raw=true)

After preparing the file as in the sample file, now you can upload the file, fill the reason and start to import.

### 2.4. Barcode label template

You can create your own barcode template by adding new template. There are also 3 most used templates as default templates in the extension: **A4**, **Jewelry** and **Standard** for you to select.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image008.png?raw=true)

You can configure paper width and height, label width and height, font size…and preview the template before saving. 

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image009.png?raw=true)

### 2.5. Print barcode

In Barcode configuration, admin can select the barcode template from the templates created before to print. 

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image010.png?raw=true)

Admin can select multiple barcodes to print at once. Or click to **View** under Action column to print one barcode multiple times.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image011.png?raw=true)

### 2.6. Scan barcode

In Inventory Management extension, you need to use a Barcode scanner which is able to connect with your computer. Then you can scan to read product information or update stock Qty. when doing Stock taking (Stock taking is a feature available in Inventory Management extension) or managing purchase orders (Magestore Barcode management extension is totally compatible with Magestore Inventory Management &amp; Purchase Management extension.)

- When going to Scan Barcode, you can read barcode information and product information.

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image012.png?raw=true)

- In Stock-taking, there are 5 steps: *1- General information*, *2-Prepare products*, *3-Stock counting*, *4-Complete data entry*, *5-Complete Stocktaking*. You can scan barcode to choose products in step 2-Prepare products and count stock quantity in step 3-Stock counting. (For more details of Physical Stock taking, please refer to Inventory Management user guide.)

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image013.png?raw=true)

![enter image description here](https://github.com/Magestore/Docs/blob/master/extensions/Magento%201%20Extensions/Image_Barcode/image014.png?raw=true)

This is the end of Magento Barcode Management user guide, we hope this manual is useful for you. If you have any further question, feel free to send us email at **_support@magestore.com_** to receive best assistance!
