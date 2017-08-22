**STORE LOCATOR - MAGENTO 1** 
----------
**Version 3.0**
Confidential Information Notice. Copyright 2016 All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.

## Introduction 
----------
You have multiple physical stores and don’t know how to give your Customers chances to select their closest one? If so, no need to look any further as our Magento Store Locator extension is exactly the right solution for you. With various search fields and a friendly user interface, Customers can easily locate the most convenient store, such as the one within 5 kilometers of their homes for instance, and then get instant directions on Google map. In particular, Magento Store Locator extension can help promote your stores effectively by allowing Customers to view and give Facebook comments on the store.
(image1)
**OUTSTANDING FEATURES**
###For Customer
Search for stores easily with various criteria

 - View the list of all stores with custom pin icon on Google map
 - Filter stores by tags
 - Search stores by distance
 - Search stores by country, state/ province, city & zip code
 - Get instant directions from a location to any store
 - Choose the preferable view between map, satellite
 - See store logo on store list page

Access store info in 1 click

 - Access store's official website or social channels such as Facebook
 - View contact details of each store including address, phone, email
 - Know opening hours, days off & special working days
 - Explore store via many photos & Street View mode
 - View and give comments on Facebook
###For admin###
 - Import stores & locations in mass from CSV files
 - Provide store details such as address, contact info, website, tags, images etc.
 - Promote stores with custom pin, banner, embedded form... (HTML & WYSIWYG supported)
 - Edit store's meta info for better SEO
 - Set store's open times & days off flexibly
 - Choose default search criteria for better experience of customers
 - Change color & map style to fit your theme

###Other###
 - Responsive Magento Store Locator extension (Hot)
 - Compatible to Google Map & Facebook API
 - Magento Store Locator extension is 100% Open source
 - License Certificate valid for 1 live Magento installation and unlimited test Magento installations (No license key required)
 - Easy to install and configure
 - User-friendly interface

##HOW TO USE##
----------
This section shows you how Customers can make use of the Store Locator extension in frontend. The module creates a separate page listing all stores and detailed pages for each store. 
To go to the **Store Listing** page, Customers can click on **Account** → **Store Locator**, then click the **Account** button on the top right corner.
(Image2)
###Store Listing Page###
(image3)
As can be seen, this page contains 2 main parts: **Search** and **Store List**.

 - **Search**: In this section, Customers can search for stores either by distance from a specific location or by store location such as country, city, etc. After Customers fill in search criteria and click on the **Search** button, all matching results will be shown. Clicking button **Reset** will return Customers to the list of all stores.
For example, if a Customer wants to search for stores within a 100-mile radius of his location, such as London, United Kingdom, he simply fills corresponding information into the **Search by Distance** fields. With Google Suggest integrated, when the Customer enters some first characters into **Your Location**, a list of matching locations is shown in the drop-down so he can conveniently pick a suitable one. 
After Customers click on the **Search** button, the results are shown on both G-map and store list as below:
(Image4)
Customers can also get directions to each store by entering a specific location and clicking on the **Go** button. The detailed directions are as follows:
(Image5)
Moreover, customers can see the real street that the store locates in by clicking on **Street View** link:

(Image6)

 - **Store List**: This part shows all stores of your site on both list and G-map. Each store is shown with name, address, **Street View, Direction** link and store image, etc. Customers can click on any store they want to know more in details, then they will be redirected to a **Store Detailed** page.
In addition, store’s information can include a link if you provide it in backend. It can be the official website URL, store Facebook fan page URL, etc. so that Customers can view more information about the store. 
(image7)
When Customers click on a store on the list, its location is marked on the map by a colored pin. For example, after a Customer selects the Cameratek Durban store, the extension will show its location on the map as below:
(image8)
Then Customers can zoom in/ out the map to have a clearer view. Information of a store can be displayed on the map as a tooltip. Customers can turn the tooltip off if they want.
 - Another helpful feature is the **Filter by Tags** bar at the bottom of the **Store Listing** page, which allows Customers to narrow down their choice of stores. When Customers click on any tag as preferred, the extension shows stores tagged with that label. This will certainly save much time for Customers from scrolling up and down on the list, especially when the list of stores is too long.

(image9)
###Store Detailed Page###
Customers will be navigated to the **Store Detailed** page if they click on the store name they want.
(image10)
On this page, Customers can see store address, opening time, special days, holidays and store images. Besides, Customers not only can view comments about the store but also can give their own comments to discuss with others on Facebook.
Similar to the **Store Listing** page, Customers can get directions to a store by entering their location and clicking on **Get Directions** to see instructions:

(image 11)

##HOW TO CONFIGURE##
----------
You have seen how Store Locator works in front-end for customers. The following part will guide you through how to configure and manage the extension in back-end.
***New release**: One of the most important Google Maps APIs Standard Plan updates implemented on June 22, 2016 was **that required future product updates are only available for** **_requests made with an API key_**. 
This means active domains created before June 22, 2016, continue to be able to access the Google Maps JavaScript API, Static Maps API, and Street View Image API without an API key. They are not affected by keyless access being unavailable for new domains. However, Google Maps APIs Standard Plan advises all developers to use a key in order to guarantee their quality of service. Applications that continue to make keyless requests may experience some periodic service degradation if other keyless applications' usage spikes and draws down the global unchanged quota.  
In order to get API key, follow these steps as follows: 
**Step 1**: Visit APIs Console at https://console.developers.google.com/apis/library and log into your Google Account.  Then, click **Create project** button on top of the menu. 

(IMAGE 12) 

**Step 2**: Fill in the project name and click Create button

(Image 13)

**Step 3**: On the menu at the left side, you will see the **Credentials** Tab. Click this tab and after that, a box will appear with **"API key"** on it. It is where you should click in order to create API key for your browser apps.


(image 14)

After that you will see a box with a number of choices specifying which kind of key you would like to create. **Choose Browser** key.

(image 15)

**Step 4**: Fill in your name and domain and then click create

(image 16)

**Step 5**: Get the key and paste it in your page

(image 17)

**Step 6**: Last but not least, in Library tab, let’s enable the APIs in red frame as below 

(image 18)

###Manage store###
To set up stores with location, opening time and other information, go to **Store Locator → Manage Stores.**

(image 19)

On this **Store Manager** page, you can view a list that shows information of all stores in your site such as n**ame, address, city, country, zip code and status.**
You can use the mass action to delete or change status of stores. Besides, you can also export the list of stores to CSV or XML files.
####Add store####
To add a new store, click on the **Add Store** button. The new **Store Information** page includes 3 tabs: **General Information, Google Map and Time Schedule.** 

 - **General Information** tab:
There are 4 fields in this tab including: **General Info, Location Info, Contact Info, Meta Info.**
- **General Info**: in this tab you can provide a lot of detailed information about your store to help your Customer locate it easier. 

(image 20)
Besides important information such as Store name, Description, Status, here are some extra fields you should use to optimize user experience:

  ✓ **Store’s link**: enter a link to the store’s official website or social channel such as Facebook fan page.
  ✓ **Store's Tag(s)**: enter any tags related to the store, such as product category, so that Customers can use them to filter stores and narrow down their option.
  ✓ **Sort order**: Sort the display order of store on the store listing page. The store with higher sort order will be shown first. This value will be used as the Default option of "List Store by" in Settings.
  ✓ **Store Image(s)**: upload as many store images as you want. The base image will be shown in the store list. 
 
 (image21)
 
- **Location Info**: fill your store’s address in this field, remember to click on the **Save Store** or **Save And Continue Edit** button to save your work. After that, store’s location will be updated automatically on Google Map.
(image 22)

- **Contact Info**: fill in with the following information about the store in order to allow Customers to contact with store owners or store assistants easier.
(image 23)

- **Meta Info**: allows you to optimize search information in each store's detail page. 

(image 24)

 - **Google Map** tab: 

(image25)

There are 4 fields in this tab including **Zoom Level, Store Latitude, Longitude** and **Store Icon**. 

 ✓ **Zoom Level**: It is used when previewing the store’s location on Google Map in backend and on the Store Listing page in frontend. The higher number you set, the higher zoom-in level is.
✓	**Store Latitude** and **Store Longitude**: You do not need to fill them out if you do not remember your store’s coordinates. After you save, the extension will automatically provide these figures corresponding to the store address you enter in the General Information tab.
✓	**Store Icon**: You can upload an icon to use as store’s marker on G-map instead of the default pin icon. 

 - **Timer Schedule** tab:
 
 This tab allows you to set opening time for a store. Let us take Monday for example:
- If your store opens on Monday, choose Yes for Open.
- If your store opens from 8 am to 10 pm, set Open Time as 8:00 and Close Time as 22:00.
- The extension also allows you to set break time for each store if you want. 
Similarly, you can set opening hours for each remaining day of the week. To quickly set up, click on the **Apply to other days** button on the top right corner of the **Monday** section. Other days will have the same working time as Monday.

(image 26)

After entering all the necessary data, remember to click on the **Save** or **Save and Continue Edit** button to save your work.
####Import Stores####
Click on the Import **Store button** on the top right corner of the **Store Manager** page. You will be navigated to the **Import File** page.

 - **CSV file structure**
You can download the sample “stores.csv” file to view its structure. The columns are attribute values of the store and each row corresponds to one store. The title row (first row) contains the attribute name. Please note that you cannot edit it (important!) because the system reads data from CSV files based on the name. If the attribute value of any stores is null, you don’t have to fill data into it.
 -  Import file
✓	Create a CSV file with information of your stores following the sample file structure
✓	Click on button **Browse** to select your CSV file
✓	Select **Import** to import the CSV file

(image 27)

####Edit Store####
In order to edit a store, you can click on the **Edit** link of any store row on the **Store Manager** grid. Besides existing fields as when you add a new store, you should pay attention to the **Google Map** tab. When a store is imported or created manually, the system will automatically get the coordinates based on the store address by using Google API. However, in some cases, this way may be not completely accurate. Therefore, the **Google Map** tab allows you to edit store coordinates manually.

(image 28)

If the pin on the map is not in the right place, you can drag and drop it to where you want to set a new location.

(image 29)

After editing, remember to click on the **Save** or **Save and Continue Edit** button to save your work.
Note: When you edit the store address (street, city or state/province) in **General Information**, the store coordinates will be auto-updated after being saved. You also can click the **Renew Google Map** button to update the store’s new location.
###Manage Holidays###
To set days off for your stores, go to **Store Locator → Manage Holidays** on the menu in backend. You will be navigated to the **Holiday Manager** page listing all holidays created. Holidays within a specific period, which is set in **Settings**, will be shown in the **Store Information** tab on the **Store Detailed** page. 
Click on **Add Holiday** to create a new one. 

(image 30)

On the **Add Holiday** page:

 - Select store(s) to apply holiday from the list
 - Select the start date and end date of holiday
 - Fill in the **Comment** field if needed

Remember to click on the **Save Item** button after entering required fields to save your work.
###Manage Special Days###
To set days with special working time for your stores, go to **Store Locator → Manage Special Days** on the menu in backend. You will be navigated to the **Special Day Manager** page listing all special days created. Days within a specific period, which is set in **Settings**, will be shown in the **Store Information** tab on the **Store Detailed** page.
Click on the **Add Special Day** button to create a new one.

(image 31)

On the **Add Special Day** page:

 - Select store(s) to apply special working days from the list
 - Select the start date and end date of special days
 - Choose open and closing time applied to these special days

Remember to click on the **Save Item** button to save your work. 
 * **Note**: Special days have the highest priority compared with holidays and other days. If a specific date is assigned as both store’s special day and holiday, it will be counted as special working day. The store still opens on that date but with special opening hours as you configured.
###Setting##
To configure the Store Locator extension, go to **Store Locator → Settings** on the menu in backend. The configurations here are divided into 4 groups including **General, Google, Facebook** and **Store Search**.
 
 * **General:**
 (Image 32)
 |No.  | Fields          | Sample | Result|
 |-----|----------------|----------------|------------------------------------------------|
 |1| Enable| Yes| Store Locator extension is enabled on your site.| 
 |2| List Store by| Alphabetical order | Store full list and store search result list are sorted by alphabetical order. |
 || | Distance| If Customers search stores by distance, the result list is sorted from the nearest to the furthest ones. ***Note**: this configuration is not applied to **Search by Area** and the store full list since Customers do not enter a specific location. | 
 || | Default| Store list is sorted based on Sort Order of each store.|
 |3| Page Title| Store Locator| The title of Store Listing and Store detailed pages in frontend is “Locate Store”.|
 |4| Display holidays and special days in the next| 30| Stores’ holidays and special days within the next 30 days will be shown on Store Detailed pages.| 


 - **Googles:** 

 (image 33)
 
To integrate Google API in your site, fill your Google Map API key into this field. You can get this key by following the guide link or going to **Store Locator → Guide** on the menu in backend.

 * **Facebook:** 
 
(image 34)

 |**No.**  | Fields          | Sample | Result|
 |-----|----------------|----------------|------------------------------------------------|
|1| Allow Facebook comment| Yes | On Store Detailed page, Customers can see comments of other users about a store on Facebook and make their own comments.|
|2| Language for Facebook comment|English|Customers can use English to comment on Store detailed pages.|
|3|Facebook API key| | To integrate Facebook social plugin in your site, you must enter Facebook API key into this field. To register this key, please follow the guide link.|


 * **Store Search:**
 
 (image 35)

|No.  | Fields          | Sample | Result|
 |-----|----------------|----------------|------------------------------------------------|
|1|Search criteria|Country, Zip Code| Customers can search for stores by area using Country and Zip Code criteria.|
|2|Default Radius for search| 10| When searching for stores by distance, if Customers do not specify a radius, the system auto uses the default value and shows stores within the radius of 10 kilometers (or miles).| 
|3|Default Country| United States| The default country for searching and showing the list of stores is United States. |
|4| Distance unit| Kilometers| The unit to measure radius is Kilometer.| 


 -  **Style Configuration:**
 
 (image 36)

In this part of configuration, you can choose to use map styles, change color of elements on Store Locator page such as **Active Search Tab – Background, Page Title – Background, Active Search Tab – Font, etc.** 
Now, if you are here, in the last line of our guide, you have completely finished studying our Store Locator extension with all of its striking features! Hope you find this manual useful.
