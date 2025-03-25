# Magento 2 Pre-Order Extension

## Introduction
Magento 2 Pre-Order Extension allows store owners to sell upcoming or out-of-stock products as pre-orders. This feature enhances customer experience by enabling them to reserve products in advance, ensuring they don't miss out once items are available. With flexible settings, automated notifications, and a seamless checkout process, this extension optimizes inventory management and boosts sales.

## How It Works
Magento 2 Pre-Order Extension replaces the default "Add to Cart" button with a "Pre-Order" option for selected products. Customers can place orders for items that are out of stock or yet to be released. Store admins can configure pre-order messaging, set availability dates, and notify customers upon product release. This extension is compatible with simple, configurable, and grouped products, ensuring a smooth purchasing experience.

## Key Features
- Enable pre-order for out-of-stock or upcoming products
- Customizable pre-order messages on product pages
- Automated email notifications for product availability
- Supports simple, configurable, and grouped products

## Pre-Order Button Customization
Store admins can personalize the pre-order button text to match their branding. This ensures a seamless shopping experience and better engagement with customers.

## Automated Email Notifications
Once a pre-ordered item is back in stock, customers automatically receive an email notification. This feature helps boost conversions by reminding users about their reserved products.

## Flexible Payment Options
Customers can choose to pay in full or leave a deposit at checkout. This flexibility enhances user experience and increases pre-order sales.

## Analytics & Reporting
Store owners can track pre-orders, analyze customer behavior, and optimize their marketing strategies accordingly.

## Extension Installation

### Step 1: Install the extension using Composer:
```bash
composer require vendor/magento2-preorder
```
For a specific version:
```bash
composer require vendor/magento2-preorder:version
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run the following commands
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Pre-Order Extension

### Step 1: Navigate to the Admin Panel
Go to **Stores > Configuration > Pre-Order Settings**.

### Step 2: Enable the Extension
Toggle the option to **Enable Pre-Order** and configure the settings as required.

### Step 3: Customize Pre-Order Messages
Modify the pre-order text displayed on product pages and checkout.

### Step 4: Set Product-Specific Pre-Orders
Navigate to **Catalog > Products**, select a product, and enable the **Pre-Order** option.

### Step 5: Save and Apply Settings
Click **Save Config** and refresh the cache.

## Download Our [Magento 2 Pre-Order](https://codedecorator.com/magento-2-preorder.html) Extension
