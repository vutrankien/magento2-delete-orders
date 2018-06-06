# Magento 2 Delete Orders Extension
Magento 2 delete single or multiple order.

## Compatible With:
Magento ver 2.2.x

## Available Features:
* Multiple or Single order delete from backend order gird using massaction.
* Automatically remove/delete order invoice if exists.
* Automatically remove/delete order shipment if exists.
* Automatically remove/delete credit memo comments and others data along with orders.

## Installation
##### Step 1 - Manually (not recommended)
 * Download DeleteOrders Extension
 * Unzip the magento2-delete-orders-master.zip file
 * Create a folder {Magento 2 root}/app/code/Magebay/DeleteOrders
 * Copy all files and folder to DeleteOrders folder

#### Step 2 - Enable/Install via command line
 * php bin/magento setup:upgrade
 * php bin/magento setup:static-content:deploy -f
 * php bin/magento indexer:reindex
 * php bin/magento cache:flush
