
===== LatitudePay and Genoapay Integrations for OpenCart 2.3 ===== 

Version: 1.0.5
Compatibility: OpenCart 2.3.0.2

Author: Latitude Financial Services
Link: https://www.latitudepay.com

===== Description =====

Accept LatitudePay (AUD) and Genoapay (NZD) on your OpenCart store.
This extension integrates OpenCart with LatitudePay and Genoapay, allowing e-commerce owners to accept payments using LatitudePay and Genoapay.

The latest installation and configuration guide can be accessed here: https://resources.latitudefinancial.com/docs/latitude-pay/opencart2/

===== Installation =====

1 Go to Admin >> Extensions >> Installer to upload the extension .ocmod.zip file.
2 Proceed to Extensions >> Extensions and select Payments. Then, install LatitudePay/Genoapay.
3 Configure payment extension accordingly. Please read the configuration section below for more information on configuring the extension.

===== Configuration =====

1 Retrieve your API Key and API Secret LatitudePay/Genoapay Merchant Portal and paste the information into the respective fields in the OpenCart extension on your website.
2 Enable the sandbox mode if you are using the sandbox key.
3 (IMPORTANT) Configure the order status mapping in the "Order Status" tab.
4 Save when done.

===== Changelog =====

1.0.5 (13 April 2022)
Add compatibility with Collect Payment Later
Improve payment status assignment

1.0.4 (20 October 2021)
Improve debug logging

1.0.3 (19 October 2021)
Add Pending status
Improve Order History to include Payment Plan ID

1.0.2 (23 August 2021)
Removed callback->fail scenario

1.0.1 (22 July 2021)
Fixed multiline shippingMethod name that breaks JSON formatting

1.0.0 (14 July 2021)
Initial version released for LatitudePay and Genoapay
