
# USER GUIDE FOR IT ADMIN
-----

*Confidential Information Notice.* 

*Copyright 2017. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.* 

*This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*

---------

## I. INTRODUCTION
This guide will help you – an IT Manager – to configure a successful strong system for the retailers and support you to activate the most suitable features for the business.    Through the guide, you will understand how Omni-channel company will be built and work with MageStore packages. Moreover, you will get basic knowledge about how you can decentralize roles, users and staffs for your company.

------
## II. HOW TO INSTALL


### 1.	Generate License Certificate

After purchasing an module, you will receive an email that includes the link to access **My License Certificates** on Magestore website.

![](./img102/it_img001.png?raw=true)

If you don’t receive the email, you can directly log in to your account dashboard at Magestore then go to **My Account/My License Certificates**.

![](.img102/img002.png)

Here you will select your Order number and a corresponding Product then type the **back-end domain of your live site**. It is optional to add your Development Domains right away or later.

Click on the **Generate Certificate** button to get your License Certificate.

***Note:*** *License Certificate is a PDF document that contains your **License Information** including:*

1)	Product Name
2)	License Serial
3)	License Type
4)	Registered Domain
5)	Activation Date
6)	Expiration Date

Your **License Serial** is unique and can only be used once for one module.

You also can go to **MageStore Check License Information** page, enter your License Serial to check your license status.

You **do not need to insert this license serial into your module back-end**. Simply provide it in your ticket/ email when you request for our support.


###2.	Download Solution Package

Go to **My Downloadable Products**. Click on the version of that you want to install to download it. The file that you download is normally a zip file.

Here you also can find related documents, such as user guide.

![](.img102/img003.png)


###3.	Install the Package Downloaded

If you are new to Magento 2, you probably need a little help to get started before installing an module:

1)	Is the Magento software installed already?
2)	What’s a terminal, command prompt, or Secure Shell (ssh)?
3)	Where’s my Magento server and how do I access it?

Please note that we take Gift Card as our example in this Installation guide.

**Step 1: Verify your prerequisites**

Use the following table to verify you have the correct prerequisites to install the Magento software.

| Prerequisite | How to check | For more information|
| --- | ----| ----|
|Magento version Starter Edition| Go to admin page, you can see version of Magento 2 at left bottom page|Download Magento version Growth Plus|

**Step 2: Install and verify the installation**

Unzip the module package downloaded. When you have completed, you will have a folder named “app” containing all files of this module:

Now, please connect to your FTP by using FileZilla or other FTP Application to upload the files to your server:

![](.img102/img004.png)

After uploading all the files to your server, please login to your SSH by using Putty or SSH command line. Them, please use “cd” command to change the directory to Magento 2 root folder:

***cd [magento 2 root folder]***

Run the setup:upgrade command line:

***php bin/magento setup:upgrade***

Wait a second to complete installation process:

![](.img102/img005.png)

If your website is in the Production mode, you should re-run the Magento compile command. Please enter the command:

***php bin/magento setup:di:compile*** 

![](.img102/img006.png)

After that, if your website is in the Default or the Production mode, please type the command line to deploy the static content:

***php bin/magento setup:static-content:deploy***

![](.img102/img007.png)

Then, if your website enabled the cache, please enter this command:

***php bin/magento cache:flush***

Finally, coming back to Magento 2 admin to check if the module is installed properly. 

***Note:*** *In case that you have followed all above steps but couldn’t make the module work properly, to make your website function as normal, please contact us at support@magestore.com or support.magestore.com, our supporters will assist you in resolving any issues within 24 hours.*
