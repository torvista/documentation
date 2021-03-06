---
title: New Listing - Featured Listing - All Listing configuration settings
description: Configuration for New Products, Featured Products and All Products pages 
category: template 
weight: 10
---

The New Products, Featured Products, and All Products pages 
are [listing pages](/user/storefront_pages/listing_pages/).  

They are all configured using the same kinds of settings, but each one 
has its own configuration settings page; the pages are under Admin > Configuration, and are named
[New Listing](/user/admin_pages/configuration/configuration_newlisting/),
[Featured Listing](/user/admin_pages/configuration/configuration_featuredlisting/), and 
[All Listing](/user/admin_pages/configuration/configuration_alllisting/).

For example, Admin > Configuration > Featured Listing, the top settings are:

![Featured Products Settings](/images/featured_products_settings.png) 

Note that each setting has a four digit value; each digit or combination of digits controls a separate setting. 

The first digit controls whether that piece of the listing, say the product name, will show or not. You have to chose either a 1 or a 2 in order for it to show on the listing. Product name has a value of 2101, indicating it is to be shown. If that value was changed to 3101, it disappears from the page. 

The first digit also determines whether the item is located on the left or right as in the image below where the 2101 was changed to 1101. Use "2" for right (as in the upper image) and "1" for left. 

![Featured Change Name Number](/images/featured_product_settings2.png) 

The second and third digit taken together determines the sort order of the items in the display. For example, changing the model number from 2101 to 2311 places it below the manufacturer name that has a number of 2302. 

![Featured Change Model Number](/images/featured_product_settings3.png) 

The fourth number determines the spacing between fields. If we just change the manufacturer number above from 2302 to 2301, the space between the manufacturer and model number disappears. Peeking under the hood, this setting controls how many line breaks are present, i.e, one, two or however many you may want. 

![Featured Change Manufacturer Spacing](/images/featured_product_settings4.png) 

The behavior of the Buy Now button on listing pages is discussed in [add to cart](/user/storefront_pages/add_to_cart/). 
