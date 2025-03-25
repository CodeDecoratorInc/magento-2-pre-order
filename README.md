# Magento 2 Disable Compare Extension

## Introduction
The **Magento 2 Disable Compare Extension** by CodeDecorator helps store owners remove the **Add to Compare** feature from their Magento store. This extension enhances user experience by eliminating unnecessary options, streamlining the shopping process, and improving store navigation. It is lightweight, easy to install, and works seamlessly with Magento 2 themes.

## How It Works
The **Magento 2 Disable Compare Extension** disables the **Add to Compare** button across the store, including product pages, category pages, and search results. With a simple backend configuration, admins can enable or disable this feature as per their store requirements. The extension ensures that the compare functionality does not interfere with other Magento features.

## Key Features
- **Remove Compare Feature** – Eliminates the **Add to Compare** button from product and category pages.
- **Easy Backend Configuration** – Admins can enable or disable the compare feature with a single setting.
- **Seamless Integration** – Works with all Magento 2 themes without conflicts.
- **Performance Optimized** – The extension is lightweight and does not affect store speed.

## Key Feature 1: Remove Compare Button
The extension completely removes the **Add to Compare** button from all store pages, including product listings and detailed pages.

## Key Feature 2: Backend Toggle Option
Admins can easily enable or disable the **Compare Products** feature from the Magento 2 backend, providing flexibility in store management.

## Key Feature 3: Theme Compatibility
The extension works smoothly with all Magento 2 themes, ensuring no UI or functionality conflicts.

## Key Feature 4: No Performance Impact
Designed to be lightweight, the extension does not affect store speed or functionality, keeping performance optimal.

## Extension Installation

### Step 1: Install the Extension Using Composer
```sh
composer require codedecorator/magento2-disable-compare
```
For a specific version:
```sh
composer require codedecorator/magento2-disable-compare:<version>
```
*Note: You may need authentication keys from Magento Marketplace or the vendor.*

### Step 2: Run Setup Commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 Disable Compare Extension

### Step 1: Navigate to Admin Panel
Go to **Stores > Configuration > CodeDecorator > Disable Compare**.

### Step 2: Enable/Disable Extension
Set **Enable Compare Feature** to **Yes** or **No** based on your preference.

### Step 3: Save Configuration
Click **Save Config** and refresh the cache for changes to take effect.

## Download Our [Magento 2 Disable Compare](https://codedecorator.com/magento-2-disable-compare.html) Extension
