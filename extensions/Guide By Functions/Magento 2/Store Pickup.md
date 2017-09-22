# STORE PICKUP MAGENTO 2
(Version 1.1.0)
 
Confidential Information Notice 
 
Copyright 2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. 

This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

## INTRODUCTION
According to ComScore, 61% of shoppers would rather use free in-store pickup than pay for shipping. Thus, 72% of retailers start allowing Customers to purchase online before coming to a store and receive purchased products. If there is a chain of stores available, undoubtedly Customers will choose the nearest one as well as an appropriate time to arrive. How can the store-owner make that happen? The answer is Magento 2 Store Pickup extension – the most professional Magento shipping extension, which allows setting up multiple Magento stores, showing addresses and opening time of each store for the Customers’ convenience.

![SP](./Store%20Pickup%20Image/image003.png)

## HOW TO USE
Many times customers want to visit your physical store to pick up products ordered so they can test the quality as well as save the shipping fee. Below, let us introduce you how customers exploit all the usefulness when your store is integrated with the **Store Pickup** module.
### View Store Information
Store Pickup module creates a separated page to list all of your stores in the front-end. Customers can access this page by clicking on **arrow button** on Top-Link (the top right of the page)

![SP](./Store%20Pickup%20Image/image004.png)

The Store Listing page includes 4 sections: **Store list**, **Search form**, **Google Map** and **Tags list**.

![SP](./Store%20Pickup%20Image/image005.png)

•	The list of all stores is shown on the bottom of Google Map. Customers can view store names and base images on this list. 

•	Store locations are displayed on Google Map. Customers can zoom in/ zoom out and choose view mode as map/ satellite as preferred. Customers can also view store address or get direction by clicking on the pin icon of any store.

•	Switch the tab to search stores by distance or area.

•	Besides, customers can also filter by tags. Customers just have to click on tags they want to search. Then, list of stores which admin add these tags to will be shown.

When customers click on a store on the map, they can instantly view the store location along with its name, address, phone number and store manager’s email address. Customers can also get direction on this box.

![SP](./Store%20Pickup%20Image/image006.png)

For more details of a store, customers can click on its name link to be navigated to the detailed page.

![SP](./Store%20Pickup%20Image/image007.png)

As you can see, this page shows all details that customers want to know about a store before arriving, such as location, contact info, working time, description and store images. 
They can also view list of special days & holidays in **Special day** & **Holiday information** tab. They can conveniently give comment to stores by filling in the Facebook comment box:

![SP](./Store%20Pickup%20Image/image008.png)

### Use Store Pickup at Checkout

The main function of Store Pickup module is allowing customers to select a preferred store at checkout to arrive and pick up their ordered products. This section will show you how the module works for customers. 

•	In the **Shipping method** tab at checkout, customers can select **Store Pickup** as their shipping option. Then customers can select a store from the dropdown list: 

![SP](./Store%20Pickup%20Image/image009.png)

or select on Google map as bellow:

![SP](./Store%20Pickup%20Image/image010.png)

On the G-Map popup, customer needs to select a store on store list or search store that they want, after that click on the Apply button to apply or click on Close button to cancel.

•	After selecting a store, customers need to choose a specific shipping date and time for arrival, and then check out as usual by clicking on the Continue button.

If the shipping date is one of store’s holidays, customers won’t be able to choose that on the calendar. Thus, they can avoid arriving on the store’s days off. You can refer to section 3.2 to know how to set up these holidays.

![SP](./Store%20Pickup%20Image/image011.png)

•	In the **Payment Information** tab, applicable payment methods for **In-store Pickup** are shown as your configuration.

![SP](./Store%20Pickup%20Image/image012.png)

•	Before placing order, customers can also review the store address, shipping date and time along with other order information.

### View Orders
To view their orders with store pickup information, customers can go to **My Account** on Top-Link > **My Orders** tab > **View Order**.

![SP](./Store%20Pickup%20Image/image013.png)

To print orders, customers can click on **Print Order** on the top right. The following page will be shown:

![SP](./Store%20Pickup%20Image/image014.png)

## HOW TO CONFIGURE
 You have seen how Store Pickup works in front-end for customers. The following part will guide you through how to configure and manage the module in back-end.<br/> 
***Tips**: For quick instructions on where to set up each function and how to get Google Map API Key, you can go to the **Stores > Settings > Configuration > Magestore > Store Pickup**. Under **Service API** section, click on the link for Google Map API Key Registration Guide

![SP](./Store%20Pickup%20Image/image015.png)
![SP](./Store%20Pickup%20Image/image016.png)
<br/>
***New release**:One of the most important Google Maps APIs Standard Plan updates implemented on June 22, 2016 was that **required future product updates are only available for [requests made with an API key](https://developers.google.com/maps/faq#using-google-maps-apis)**.

This means active domains created before June 22, 2016, continue to be able to access the Google Maps JavaScript API, Static Maps API, and Street View Image API without an API key. They are not affected by keyless access being unavailable for new domains.

However, Google Maps APIs Standard Plan advises all developers to use a key in order to guarantee their quality of service. Applications that continue to make keyless requests may experience some periodic service degradation if other keyless applications' usage spikes and draws down the global unchanged quota.

In order to get the API key, follow the steps listed **[here](https://docs.google.com/viewer?url=https://www.magestore.com/media/productfile/g/o/google_map_api_creation_instruction.pdf)**. 
### Manage Stores
In the back-end, go to **Store Pickup** > **Manage Stores**. The **Store Manager** grid shows all stores created in your system with their address and status. To add new stores, you can add them manually and import from CSV files.

![SP](./Store%20Pickup%20Image/image017.png)
#### Add Store
Click on the **Add Store** button on the top right corner of the **Store Manager** page. You will be navigated to the **Add Store** page, which includes 7 tabs: **General Information, Google Map Location, Image Gallery, Store’s Schedule, Store’s Tag, Store’s Holiday, Store’s Special Days**<br/>
- **General Information** tab: 

This tab has 3 sessions: **General Information, Contact Information** and **Meta Information**.<br/>
    - Fill store’s name, status, store link, sort order and description in **General Information** session.
    
Besides important information such as Store name, Description, Status, here are some extra fields you should use to optimize user experience:<br/>
→ Store’s link: enter a link to the store’s official website or social channel such as Facebook fan page.<br/>
→ Sort order: Sort the display order of store on the store listing page. The store with higher sort order will be shown first. This value will be used as the Default option of “List Store by” in Settings.

![SP](./Store%20Pickup%20Image/image018.png)

**Tips**: You can input content for the **Description field** in HTML for better display in frontend, such as customized format, attached links, etc.<br/>
    - In **Contact Information** session, it allows you to enter information of store’s manager such as email address, phone number, etc. so customers will know how to contact if needed. You can configure to enable automatic emails sent to the store manager when pickup orders’ status is changed.<br/>
    - **Meta Information** session, you can fill in URL key, meta title, meta keywords, meta description for better SEO<br/>
- **Google Map Location** tab: 

Fill your store’s address in this field or pin from the map, remember to click on the **Save Store** or **Save And Continue Edit** button to save your work. After that, store’s location will be updated automatically on Google Map.

There are 4 fields in this tab including **Zoom Level, Store Latitude, Longitude** and **Store Icon**. <br/>
    - **Zoom Level**: It is used when previewing the store’s location on Google Map in backend and on the Store Listing page in frontend. The higher number you set, the higher zoom-in level is.<br/>
    - **Store Latitude** and **Store Longitude**: You do not need to fill them out if you do not remember your store’s coordinates. If you pin a store directly from G-map, these fields will be filled automatically.<br/>
    - **Store Icon**: You can upload an icon to use as store’s marker on G-map instead of the default pin icon. 
    
![SP](./Store%20Pickup%20Image/image019.png)

- **Image Gallery** Tab: 

Upload as many store images as you want. The base image will be shown in the store list. 

![SP](./Store%20Pickup%20Image/image020.png)

- **Store’s Schedule** Tab: 

This tab allows you to choose a Schedule from a list to apply for this store. Let us take Monday for example:<br/>
    - If your store opens on Monday, choose Yes for Open.<br/>
    - If your store opens from 8 am to 10 pm, set Open Time as 8:00 and Close Time as 22:00.<br/>
    - The module also allows you to set break time for each store if you want. <br/>
Similarly, you can set opening hours for each remaining day of the week. To quickly set up, click on the Apply to other days button on the top right corner of the Monday section. Other days will have the same working time as Monday.

![SP](./Store%20Pickup%20Image/image021.png)

After entering all the necessary data, remember to click on the Save or Save and Continue Edit button to save your work.<br/>
- **Store’s Tags** Tab: 

For easier search, you can tag each store in multiple categories. Choose tags for each in this tab by search for the tag and select suitable ones. Please note that one store can belongs to more than one tag.

![SP](./Store%20Pickup%20Image/image022.png)

- **Store’s Holidays** Tab: 

Select Holidays to be applied for this store by searching/filtering and select Holiday(s) that you set up before.

![SP](./Store%20Pickup%20Image/image023.png)

- **Store’s Special Days** Tab: 
Select Special days to be applied for this store by searching/filtering and select Special day(s) that you set up before.

![SP](./Store%20Pickup%20Image/image024.png)

#### Edit Store
To edit a specific store, go to **Manage Store** > select **Action (Edit)**.

![SP](./Store%20Pickup%20Image/image025.png)

**Note**: When a store is created manually, the system will automatically get the coordinates based on the store address by using Google API. However, in some cases, this way may be not completely accurate. Therefore, the **Google Map Location** tab allows you to edit store coordinates manually.

You can see it at the left upper. Click on this tab, the Google map will be displayed. You can reset store position by clicking on specific point on the map, then select **Save Store**.

By clicking **Apply to Form** before saving, the store coordinates & the store address will be auto-updated regarding the address of the location you pinned on the map. You can also change the marker icon which presents the pinned location on the map.

![SP](./Store%20Pickup%20Image/image026.png)

###	Manage Tags
Click on **Store Pickup > Manage Tags** to access **Tag Manager**. This tab manages all tags that are used to filter stores. Click on the **Add New Tag** button to create new one.<br/>
- **General Information**

![SP](./Store%20Pickup%20Image/image027.png)

Choose a suitable Tag Name, write a description and upload Icon to make it pop out on store listing page.<br/>
- **Stores of Tag**

Select stores from the list to be shown up when Customers clicking on “Coffee” tab. Then Save Tag.

![SP](./Store%20Pickup%20Image/image028.png)

### Manage Holidays
To set days off for your stores, go to **tore Pickup > Manage Holidays**. You will be navigated to the **Holiday Manager** page listing all holidays created. Click on **Add Holiday** button to create a new one.

![SP](./Store%20Pickup%20Image/image029.png)

On the **General Information** page:<br/>
    - Set the Holiday Name<br/>
    - Select the start date and end date of holiday<br/>
    - Fill in the Comment field if needed<br/>
Remember to click on the **Save and continue edit** button after entering required fields to save your work.
On the **Stores of Holiday** page: tick all stores that you want this holiday to be applied, then Save Holiday

![SP](./Store%20Pickup%20Image/image030.png)

### Manage Special Days
To set days with special working time for your stores, go to **Store Pickup** > **Manage Special Days**. You will be navigated to the **Special Day Manager** page listing all special days created. Click on the Add Special Day button to create a new one.  

![SP](./Store%20Pickup%20Image/image031.png)

On the **Add Special Day** page:<br/>
•	Enter special day name.<br/>
•	Select store(s) to apply special working days from the list<br/>
•	Select the start date and end date of special days<br/>
•	Set interval between shipping time options shown to customers at checkout, such as 15 minutes.<br/>
•	Choose opening and closing time applied to these special days.<br/>

![SP](./Store%20Pickup%20Image/image032.png)

Remember to click on the **Save Item** button to save your work.<br/>
**Note**: Special days have the highest priority compared with holidays and other days. If a specific date is assigned as both store’s special day and holiday, it will be counted as special working day. The store still opens for pickup on that date but with special opening hours as you configured.

On the **Stores of Holiday** page: tick all stores that you want this special day to be applied, then Save Special Day

![SP](./Store%20Pickup%20Image/image033.png)
### Manage Schedule
Set up all store’s schedules in **Store Pickup > Manage Schedule** tab.
You can see a number of schedule that had been created in this tab and quickly edit some, or create a new one by hitting the button **Add New Schedule**.

![SP](./Store%20Pickup%20Image/image034.png)

Quickly set up open/close time, break time of each day from Mon to Sun.

![SP](./Store%20Pickup%20Image/image035.png)

And to apply this schedule to various stores, navigate to **Stores of Schedule** to check all stores that you want to add.

![SP](./Store%20Pickup%20Image/image036.png)

### View Pickup Orders
To view pickup orders in backend:<br/>
•	Go to **Sales > Orders** on the menu, choose the order in which the shipping name is the same as the pickup store’s name.<br/>
•	In the **Information tab**, you can see the information about shipping address changed to the address of pickup store and attached with a map location.<br/>
When there is an order using store pickup, notification email will be sent to store owner & administrator.

![SP](./Store%20Pickup%20Image/image037.png)

### Settings
To configure settings of the Store Pickup module, go to **Store Pickup > Settings**

The configuration is divided into 3 groups including **General, Service API, Store Search**<br/>
- **General**:

![SP](./Store%20Pickup%20Image/image038.png)

No.|	Field|	Sample	|Result 
-|-|-|-
1	|Enable Store Pickup|	Yes	|Enable this module on your site
2|	Display top link|	Yes|	Show Store Pickup link on the top link in frontend or not
3|	List stores by|	Default|	Stores are listed based on Sort Order of each store
|||	Distance|Stores are listed based on the distances between customers' location & stores. If customers don't enter their location, stores will be listed by Default (Sort Order).
|||	Alphabetical order	|Stores are listed based on alphabetical order of store name.
4|	Page Title|	Store Pickup	|Store listing page and store detailed are displayed as Store Pickup
5|	Display holidays and special days in the next|	10	|All holidays and special days in the next 10 days of stores will be shown.
6|	List store page size|	10	|The maximum number of stores that will be shown in store listing page is 10
7|	Image gallery|	3|	Each store can be uploaded with maximum of 3 images in gallery

- **Service API**: 

![SP](./Store%20Pickup%20Image/image039.png)<br/>
    - To integrate Google API in your site, fill your Google Map API key into this field. You can get this key by following the guide link or going to Store Pickup → Guide on the menu in backend. <br/>
    - Choose Yes to enable Facebook comment for your stores. To integrate Facebook social plugin in your site, you must enter Facebook API key into this field. To register this key, please follow the guide link.<br/>
- **Store Search**:

![SP](./Store%20Pickup%20Image/image040.png)

No.	|Field	|Sample	|Result 
-|-|-|-
1|	Search criteria	|Country, Zip Code|	Customers can search for stores by area using Country and Zip Code criteria.
2|	Default Radius for search|	100	|When searching for stores by distance, if Customers do not specify a radius, the system auto uses the default value and shows stores within the radius of 100 kilometers (or miles).
3|	Distance unit|	Kilometers	|The unit to measure radius is Kilometer.

*Now, if you are here, in the last line of our guide, you have completely finished studying our Store Pickup module with all of its striking features! Hope you find this manual useful.*










