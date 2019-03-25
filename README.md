# price_change_notification_bot
The bot is developed to check on the price change of the products available in the cart that the user has added for future price slope.If the cart does'nt have any product, the bot terminates automatically.Now the price monitoring is done correspondingly. Once the product descends, the bot notifies with a voice message followed by a notification followed by an e-mail invitation along with the product link to purchase. In case of a price hike ,the voice message with a notification is sent to the customer.


# Module Split-up
Data-Scrapping the product on the Cart/Wish-List 
Excel Automation 
Monitoring the price change 
Comparing the price with the previous day price
Notification and voice message 
E-mail Automation (Purchase-link)


# Task Split-up
# Jayapooja R
# Data-Scrapping the product on the Cart/Wish-List 
In this module, the products that the customer adds into the cart are being scrapped. Here we use data scrapping tool available in the UiPath software. Once the product has been added to the cart the bot automatically scrape the available product in the cart. In this process we scrape the product name and price only for each and every product available in the cart.
# Excel Automation
In the Excel Automation, once the products and their respective prices are being scrapped, the data are fetched into the excel sheet. Excel automation is done by using the Excel Application Scope activity comprising of Write Range activity. The data are arranged as product name, link and price correspondingly. This enables us to monitor on the price change.

# Krishna Divya P
# Monitoring the price change 
In this section the Price Scanning is done by contrasting the product price on the day it has been added to the cart with the subsequent price changes made by the e-Commerce site further. This helps the bot to send notification, Voice Message followed by an Email Invitation further more. Similarly we create an Excel Sheet based on the expected price of the customer. This also helps the bot to make the comparison where the price may be assigned within the range approximately.	
# Comparing the price with the previous day price
The price of the product will be compared with the previous day price. Here the price will be overwrited every day accordinlgy once we run the bot. Thus the changes in the price change will be fetched and notified accordingly.

# Janani R C
# Notification and voice message 
In the Notification and Voice Message module, the customer receives with a notification via message box activity from the UiPath. Once the message notification is being sent, the customer also receives with a voice message from a text-to-speech activity. Here we also send the message for both price hike and price drop since the customer should be aware of the hike as well as drop to buy the products respectively. The two activities being involved are message box and text-to-speech.
# E-mail Automation (Purchase-link)
The E-mail automation is being generated in case when there is only the price drop/descend. This automation consists of the product purchase link in case of price drop which enables us to purchase the product. Here the mail is generated to the customer’s registered mail ID with the e-Commerce site. 



# Proposed System
Automatically the bot monitors on the price change. 
Sends a notification message along with a voice message to make the customer aware. 
In case of price drop ,it sends an email invitation to purchase the product with that product-purchase link No manual checking for price drop/ Time consumption

# Future Enhancement
SMS service for the user who created account using their mobile number.
SMS service is not given access in India at present by Uipath community


# Demo Video
https://www.youtube.com/watch?v=X1yes27uWnE&feature=youtu.be

# Team Members
Janani R C 15CSA23 (711715104023) 
Jayapooja R 15CSA25 (711715104025) 
Krishna Divya P 15CSA32 (711715104032)


# Project Status
Completed (100%)# Price_Change_Notification_Bot
The bot is developed to check on the price change of the products available in the cart that the user has added for future price slope.If the cart does'nt have any product, the bot terminates automatically.Now the price monitoring is done correspondingly. Once the product descends, the bot notifies with a voice message followed by a notification followed by an e-mail invitation along with the product link to purchase. In case of a price hike ,the voice message with a notification is sent to the customer. 


# Module Split-up
1.	Data-Scrapping the product on the Cart/Wish-List
2.	Excel Automation
3.	Monitoring  the price change
4.  Comparing the price with the previous day price
5.	Notification and voice message
6.	E-mail Automation (Purchase-link)


# Task Split-up
# Jayapooja R
# Data-Scrapping the product on the Cart/Wish-List 
In this module, the products that the customer adds into the cart are being scrapped. Here we use data scrapping tool available in the UiPath software. Once the product has been added to the cart the bot automatically scrape the available product in the cart. In this process we scrape the product name and price only for each and every product available in the cart.
# Excel Automation
In the Excel Automation, once the products and their respective prices are being scrapped, the data are fetched into the excel sheet. Excel automation is done by using the Excel Application Scope activity comprising of Write Range activity. The data are arranged as product name, link and price correspondingly. This enables us to monitor on the price change.

# Krishna Divya P
# Monitoring the price change 
In this section the Price Scanning is done by contrasting the product price on the day it has been added to the cart with the subsequent price changes made by the e-Commerce site further. This helps the bot to send notification, Voice Message followed by an Email Invitation further more. Similarly we create an Excel Sheet based on the expected price of the customer. This also helps the bot to make the comparison where the price may be assigned within the range approximately.	
# Comparing the price with the previous day price
The price of the product will be compared with the previous day price. Here the price will be overwrited every day accordinlgy once we run the bot. Thus the changes in the price change will be fetched and notified accordingly.


# Janani R C
# Notification and voice message 
In the Notification and Voice Message module, the customer receives with a notification via message box activity from the UiPath. Once the message notification is being sent, the customer also receives with a voice message from a text-to-speech activity. Here we also send the message for both price hike and price drop since the customer should be aware of the hike as well as drop to buy the products respectively. The two activities being involved are message box and text-to-speech.
# E-mail Automation (Purchase-link)
The E-mail automation is being generated in case when there is only the price drop/descend. This automation consists of the product purchase link in case of price drop which enables us to purchase the product. Here the mail is generated to the customer’s registered mail ID with the e-Commerce site. 


# Advantages
Automatically the bot monitors on the price change.
Sends a notification message along with a voice message to make the customer aware.
In case of price drop ,it sends an email invitation to purchase the product with that product-purchase link
No manual checking for price drop/ Time consumption


# Team Members
1. Janani R C                   15CSA23 (711715104023)
2. Jayapooja R                  15CSA25 (711715104025)
3. Krishna Divya P              15CSA32 (711715104032)


# Project Status
Completed (100%)
