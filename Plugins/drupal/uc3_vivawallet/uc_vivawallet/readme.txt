INSTALLATION:
-If applies, uninstall previous installed Vivawallet Payment module (admin/modules)
-Upload (ftp/ssh) the uc_vivawallet directory with its content to:
(drupal installation)\sites\all\modules\ubercart\payment\
-Enable the Vivawallet payment module (admin/modules)
-Enable and configure the Vivawallet payment module (store/configuration/payment methods)
-Set a new source in the Vivawallet backoffice with following success / fail links:

Success page: 
cart/vivawallet/complete?success

Failure page: 
cart/vivawallet/error?fail
-------------------------------------------------------------------------------------------
Vivawallet setup:
You can find your Merchant ID and API Key when you login your business account under Settings - API Access.

To connect the plugin with your e-commerce platform and Vivawallet you would have to create a new Payment Source in your Vivawallet business account, use the generated source code (usually a four digit number) in the plugin settings.

You can create a new Payment Source from the menu My Sales - Payment Sources - New Website/App.
Code - use this code in your plugin
Source Name - provide a logic name here
Linked Wallet - link the payment source to the wallet you want to use with it
Protocol - in case your e-commerce platform uses SSL on the checkout select https, otherwise use https
Integration method - redirection
Company Logo - your png company logo to display on the Vivawallet payment page
Success URL - as described in the plugin instructions
Failure URL - as described in the plugin instructions
Advanced Configuration - usually no need to make any changes here

Wait until Vivawallet has activated your newly created Payment Source before activating the plugin in your e-commerce platform.