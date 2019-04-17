# AutoInvoiceAndShipment-Magento2

# Overview

Auto Invoice & Shipment extension for Magento 2 has been developed by the product team at RLTSquare. Store owners used to spend a lot of time generating the invoice and shipment in your store. This extension helps in reducing the time and manual labor required in generating the invoice and the shipment in your store. It also generates shipment receipts and an email notification to the customers. It makes the whole process of managing orders and contacting customers easier and efficient. 
If the extension is enabled in the back-end and a user places an order, it automatically creates the configured status. This extension will automate the whole invoicing and shipment process. It will help in accelerating the order processing. It will increase customer satisfaction by offering quick confirmation of their payments which result in a better user experience and builds trust among the customers. This increased trust will make your customers more loyal to your store and end up increasing the conversion rates.

Here are some of the salient features for the extension:

```
1. Enable/Disable the extension
2. Enable/Disable automatic invoice generation
3. Enable/Disable automatic shipment generation
4. Enable/Disable automatic invoice emails
5. Enable/Disable automatic shipment emails
6. Send an invoice email automatically after the customer places an order
7. Send shipment email automatically after the customer places an order
8. Allow Admins to create invoice/shipment based on payment method selected by customer
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/auto-invoice-and-shipment
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/AutoInvoiceShipment
    ```

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_AutoInvoiceShipment
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.2 and 2.3 versions. Tested on versions 2.2.6 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/auto-invoice-and-shipment-magento-2-extension/
