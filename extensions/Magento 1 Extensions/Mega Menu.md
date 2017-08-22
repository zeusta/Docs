**MEGA MENU**
==============
**Version 3.1**
Confidential Information Notice. Copyright 2016 All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
## Introduction
----------
Do you know how long customers stay on web pages? Surprisingly, it’s only 10-20s on average (NNGroup, 2011) whereas you have a variety of products and categories to show. So as not to let customers leave soon, tell them the shortest way to what they are looking for. 

 - Magento Mega Menu extension (a.k.a Magento Navigation Menu) is your solution to create the best sitemap right on the main navigation. 
 - No technical knowledge required! You can flexibly set up your wanted menu with different content showing-off.  
 - One more thing, you don’t need to worry about running site with “turtle speed”. Magento Mega Menu extension doesn’t affect your site speed for sure. 
Let’s take a look at listed Features below! In the next Part “How to use” and “How to configure”, we will go into details of each feature.

## How to use and configure
----------
This section will show you how to configure Mega Menu extension to create your own menu. It is very fast and easy!
There are three tabs in back-end: **Menu Items Management, Menu Cache Management and Settings.**

(image 1)

### Menu Items Management
In this tab, you can:

 - Create Menu items, such as: Home, Categories, Contact, etc.
 - Edit Menu items: after creating you can easily edit your menu. It is unnecessary to have your Developer edit for you like before. 
 - Find Menu items you want with given filters.
 - View the list of menu items or export to CSV/XML file.

#### Create new Top Menu Item
Go to **Back-end > Mega Menu > Menu Items Management**, click on the **Add Menu Item** button, you will be redirected to **Add Menu Item** page. This is the guide to fill in data:

 - **General Information** tab:
(image 2)
-	**Name**: Title of the menu item, such as Home or Contact
-	**Store View**:  Select store(s) that you want to show this menu item.
-	**Link**: The address of the landing page when Customers click on the menu item. You can leave blank if the menu item doesn’t lead to any page. For example, “Contact” menu item allows Customers to fill in contact form right in the menu without directing Customers to go anywhere.
-	**Sort Order**: The order of the menu item on menu bar.
-	**Menu Item Icon**: This field allows you to upload image for menu items. Supported file types are .jpeg, .jpg, .gif, .png with recommended size to be 15x15px.
-	**Menu Type**: Select the position that you want to show this menu. To create Top menu item, please select Top menu for this field
-	**Status**: You can enable or disable the menu.

*Your menu will be shown as bellow:*

(image 3)

 - **Content** tab:
 
In this tab, you can configure the form and detailed information of the menu item.  
The detailed information of the menu item includes 4 content blocks: **Main content, Feature content, Header and Footer.**

**General configuration** section:
Before configuring the content, you need to select **Width** and **Alignment Type** for menu information in this section.

(image 4)

There are 4 alignment types for the menu content to appear.
For example: 
If you select **From left menu,** your menu content will appear from the left of menu bar to the right:

(image 5)

If you select **From right menu**, your menu content will appear from the right of menu bar to the left:

(image 6) 

If you select **From left item**, your menu content will appear from the left of menu item that you are adding:

(image 7)

If you select **From right item**, your menu content will appear from the right of menu item that you are adding:

(image 8) 

 - Main Content:
	
Our extension gives you 7 types of main content, including: **Anchor Text, Static Category Listing, Dynamic Category Listing, Default Category Listing, Product Listing, Product Grid,** and **Content.**

(image 9)

Now, let’s move on to each type of menu:
- **“Anchor text”** type allows you to create a simple menu item. When Customers click on the menu title, they will be redirected to the page linked to the title. 
- **Static Category Listing**
If you choose Static Category Listing, you need to fill enough information required in backend: 

(image 10)

Especially, you need to configure **Arrange Category Items by** field to **list all items of each category in one column** or **automatically arrange items of category in columns equally.** The menu will be shown in frontend as following: 

(image 11)
- **Dynamic Category Listing (New)**
In version 3.1, a new menu type is added that allows you to flexible design your own menu. Configure it in backend:

(image 12)

Then, the menu will be shown in frontend as below:

(image 13)
- **Default Category Listing**
With this type of menu, you just need to choose categories you want to show:

(image 14)

It will be shown in frontend as below: 

(image 15)
- With **“Product listing”** types, you need to enter the column number you want to show, Products Box Title, after that you select products list in the **Products** field:
(image 16)

And your menu will be shown in frontend as bellow:

(image 17)
- With **“Product Grid”** type, configuration for this type is similar to Product Listing type but on menu content this type will show products list you select with more information such as product image, product name and price:

(image 18)
- If you choose **“Content”** type, **Menu Content** field will be shown for you to enter the information you want to show in main content part.

(image 19)

 - Featured Content section:
 
In this section, you must to select width of featured content in menu content.
For example: If menu content width is 100%, width of featured content is 60%, so width of main content will be 40%.

(image 20)
With Product type, it will be shown as bellow:

(image 21)

With **Category** type, it will be shown as bellow:

(image 22)


If you select **“Content”** type, it is similar to **Content** type of **Main Content** section. It will show you the **Featured Content** field to enter the information you want to show on your menu:

(image 23)

 - **Add content for header, footer** 
 
You can configure the information in Header & Footer Content section or make a quick configuration for content of menu item by clicking on each part of the sample layout (Header content, Main content, Footer content) and you will be immediately navigated to its configuration part to add content.

(image 24)

In the text editor form, you can add text and image.
Fill out data you want to show and save your changes. You can see the Menu item is added to the list in Menu Manager Page as below:

(image 25)

The menu item which is successfully added will be displayed in front-end as follows:

(image 26)

#### Create new Left Menu Item
Similar to **Create new Top Menu**, you also must to configure all required fields in **General Information** tab and **Content** tab. Please refer **2.1.1. Create new Top Menu** for details.
* **Notes:** With left menu, the **Alignment Type** just has 2 options for you to select. They are **From top menu** (the menu content will appear from the top of menu bar down) and **From top item** (the menu content will appear from the top of menu item you are creating). And the width of left menu item is from the right of menu bar to the right of the page.
On you website, the left menu will be shown as bellow:

(image 27)

#### Edit Menu Item:

(image 28)

If you want to edit any menu item, you just need to click on its row or link **Edit** in **Action** column. The **Edit Menu** page will be shown for you edit the field in General Information tab and Content tab:

(image 29)

 After editing, please remember to save your work by clicking on **Save Menu** button or **Save And Continue Edit** button.

### Menu Cache Management

**Refresh Cache** is an innovation in our Mega Menu extension. While many other Menu extensions interact with database directly, thus slowing your site, Magestore Mega menu uses generated HTML code of your menu, so it wouldn't affect your site performance. In case your site has any change in product or category, the system will show a notification for you to re-index the menu.

(image 30)

You can click on link **Reindex** in the notification or go to **Mega Menu > Menu Cache Management**. You will be navigated to Refresh cache page.

(image 31)

You just need to click on the **Refresh** button; the system will refresh cache automatically. 

### Settings

Go to **Back-end > Mega Menu > Settings**. This page has 5 sections, including: **General Configuration, Top Menu Configuration, Left Menu Configuration, Mobile Version Configuration** and **Implement Code**.

 - General Configuration:
 (image 32)
-	**Enable Mega Menu**: allow you to enable/ disable the extension.
-	**Menu Effect**: allow you to configure the effect of menu. There are three types:
-- **Hover**: menu item will be displayed immediately when you hover on menu title.
-- **Animate**: this effect is similar to Hover but menu item will be displayed more slowly
-- **Toggle**: menu item will only be displayed when you click on menu title
- **Menu type**: allow you to configure for the right device: PC, Mobile or both of them. 


 - **Top Menu Configuration** 
(image 33)
This section includes configurations for the top menu.
- **Top Menu alignmen**t:  allow you to choose the way to display the top menu bar. There are three types for you to choose:
-- **Left**: your top menu items will be arranged from the left of your site to the right.
(image 34)
-- **Right**: your top menu items will be arranged from the right of your site to the left.
(image 35)
-- **Justify**: menu items will be justified both to the right & left.
(image 36)

- **Size to change menu to Mobile version**: if the device size is lower than the number you enter into this field, the menu will be changed to Mobile version.
-	**Menu Item height**: allow you to configure the height of the top menu bar.
-	**The other configurations**: allow you to customize your menu items style to fit with your site, including: menu item size, menu background color, submenu background color, active menu item background color, menu item color, active menu text color, submenu box title color, submenu main text color, submenu link color and text label.

 - **Left Menu Configuration:**
(image 37)

Similar to Top menu configuration, left menu enables you to customize the left menu items styles except Menu alignment filed and Menu item height field. Please refer to **Top Menu Configuration** part for details.

 - **Mobile Version Configuration:**

(image 38)

In this section, you can customize you menu item style when the menu is changed into mobile version.
This section allows you to flexibly configure mobile menu such as anchor background color, anchor color, mobile item font size, text label, mobile item text color, mobile item background color, active mobile item background color, submenu box title color, mobile submenu main text color, mobile submenu main link color. 
Besides, in **Mobile Effect** field, you can configure how to display the menu on mobile version. There are two options for you to choose: Blind and Slide.

On mobile, your menu bar will be shown as bellow:

(image 39)

When you click on your menu item, it will be displayed:

(image 40)

 - **Implement Code:**
We provide this part which is just recommended for developers. This part enables to show Mega Menu in different places.

(image 41)

Remember to click on the **Save Config** button to save your work. 
We hope that you will find this user guide helpful during using Magestore Mega Menu extension. 

> Written with [StackEdit](https://stackedit.io/).
