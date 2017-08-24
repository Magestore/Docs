
**BARCODE MANAGEMENT - MAGENTO 2**
=================================

**Version 1.0.0**


*Confidential Information Notice
Copyright2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited.
This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.*


## Introduction


Barcode by definition is the small image of lines (bars) and spaces that is affixed to retail store items, identification cards, and postal mail to identify a particular product number, person, or location. The code uses a sequence of vertical bars and spaces to represent numbers and other symbols. Barcode is a reliable method for cutting costs and saving time for business.

Barcode management extension from Magestore provides your business with a handful solution to generate barcode, print barcode label and scan barcode, all in one.


## How it works


### 1. Barcode Listing


Barcode listing is a view to display all barcodes of all products saved in Inventory Management. It contains Barcode, SKU, Supplier and Purchased Time.

From this screen, admin can easily Import barcode or Generate Barcode with 2 buttons on the top right.

![Admin can easily import/generate barcode with buttons](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img1.png)

Admin can also view details of each product and barcode.

![Admin can also view details](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img2.png)

From barcode detailed page, admin can configure barcode printing and print barcode directly. 

Product information is shown including Image, name, price and its availability in each warehouse.


### 2. Generate barcode


Inventory Management gives you 2 modes to generate barcode:

-	One barcode per product sku

-	Multiple barcode per product sku

This can be configured in Barcode Settings.

![Configuration in Barcode Settings](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img3.png)

-	If you set “One barcode per product sku” as “Yes”, then the system will allow you to generate one barcode for one product sku only.

Now to generate barcode, you go to Generate Barcodes tab. From here you can select the product that you want to generate barcode, fill in the Supplier (optional) then generate.

![Fill in the Supplier](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img4.png)

-	If you set “One barcode per product sku” as “No”, then it opens up 2 options to generate barcode when you go to Generate Barcodes tab.

![Generate Barcode Tab](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img5.png)

These 2 options are: Generate barcode per item or Generate barcode per purchase.

“Generate barcode per item” means each item will have its own identified barcode although they have the same SKU.

“Generate barcode per purchase” means items will be identified by the time it is purchased. Although you take 10 items with same SKU in one time purchasing from supplier, these 10 items will have the same barcode. But in another time of purchase, they will have different barcode.

After selecting the option you want to proceed with, you can continue selecting product, fill the product Qty. , supplier and  purchased time (optional) then generate.

Admin can configure the barcode pattern to generate. Barcodes generated will be saved in Barcode listing page & Barcode created history.

![Admin can configure the barcode pattern to generate](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img6.png)


### 3. Import barcode


When your products already have a pre-generated barcode, you will not need to use Generate barcode feature. Instead, you can import barcode directly into the system using Import barcode feature of Inventory Management. 
The system provides a sample import file including SKU, Barcode, Qty. and Supplier & Purchase time (optional).

![The system provides a sample import file](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img7.png)

After preparing the file, now you can upload the file, fill the reason and start to Import.


### 4. Barcode template


You can create your own barcode template by adding new template. There are also 3 most used templates as default templates in the extension: A4, jewelry and standard for you to select.

![You can create your own barcode template](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img8.png)

You can configure paper width and height, label width and height, font size…and preview the template before saving.

![You can configure paper width and height](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img9.png)


### 5. Print barcode


In Barcode configuration, admin can select the barcode template from the templates created before to print. 

![Admin can select the barcode template](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img10.png)

Admin can select multiple barcodes to print at once. Or click to View under Details column to print one barcode multiple times.

![View under Details column to print](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img11.png)


### 6. Scan barcode


In Inventory Management extension, you need to use a Barcode scanner which is able to connect with your computer. Then you can scan to read product information or update stock Qty. when doing Stock taking (Stock taking is a feature available in Inventory Management extension).

- When going to Scan Barcode, you can read barcode information and product information.

![When going to Scan Barcode](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img12.png)

- In Stock-taking, there are 5 steps: 1- General information, 2-Prepare product, 3-Stock take, 4-Complete data entry, 5-Complete Stock take. Scanning can be applied at step 2: Prepare product before Stock take. From this step, there is an option to import products and sample files are provided. You can use a barcode scanner to scan product with Qty. into an excel/csv file. Then upload the file with Qty. counted by barcode scanner into the system to update Stock take Qty. About detailed steps of Physical Stock taking, please refer to Inventory Management user guide.

![Stock-taking](https://github.com/Magestore/Docs/blob/master/extensions/Magento%202%20Extensions/Barcode%20Management/Images/BM-img13.png)
