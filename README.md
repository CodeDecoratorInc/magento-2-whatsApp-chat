# Magento 2 WhatsApp Chat Extension

## Introduction
The **Magento 2 WhatsApp Chat** extension by CodeDecorator enables seamless communication between store owners and customers via WhatsApp. This extension allows users to initiate real-time chat directly from the store, improving customer engagement and boosting sales. By integrating a WhatsApp floating chat button, customers can quickly ask queries, seek support, and receive instant responses.

## How It Works - Magento 2 WhatsApp Chat
The **Magento 2 WhatsApp Chat** extension adds a floating WhatsApp chat button to your Magento store. Customers can click the button to start a conversation on WhatsApp, either through the web version or mobile app. Admins can customize the button’s position, text, and default phone number from the backend settings. Additionally, the extension supports multiple WhatsApp numbers, allowing different departments to handle inquiries efficiently.

## Key Features
- **Floating WhatsApp Button** – Add a floating WhatsApp chat icon to your store for easy customer support.
- **Multiple WhatsApp Numbers** – Assign different numbers for various departments or agents.
- **Customizable Settings** – Modify button text, position, and default messages from the admin panel.
- **Device Compatibility** – Works seamlessly on both desktop and mobile devices.

## Floating WhatsApp Button
The extension provides a sticky WhatsApp button that stays visible across all pages, making it easy for customers to reach out anytime.

## Multiple WhatsApp Numbers
Admins can configure multiple WhatsApp numbers, directing customer queries to different departments such as Sales, Support, or Billing.

## Customizable Button and Messages
The extension allows store owners to customize the button’s text, default WhatsApp message, and placement on the website.

## Responsive Design
The WhatsApp Chat extension ensures a smooth user experience on both desktop and mobile devices, making communication seamless.

## Extension Installation
To install the **Magento 2 WhatsApp Chat** extension, follow these steps:

### Step 1: Install the extension using Composer
```bash
composer require codedecorator/module-whatsapp-chat
```
For a specific version:
```bash
composer require codedecorator/module-whatsapp-chat:version
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run Magento setup commands
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 WhatsApp Chat Extension

### Step 1: Navigate to Admin Panel
Go to **Stores > Configuration > CodeDecorator > WhatsApp Chat**.

### Step 2: Enable the Extension
Set **Enable WhatsApp Chat** to **Yes**.

### Step 3: Configure WhatsApp Settings
- Enter the **WhatsApp Number** to receive customer messages.
- Customize the **Button Text** and **Default Message**.
- Adjust the **Button Position** (left or right of the screen).

### Step 4: Save Configuration
Click **Save Config** and clear the cache using:
```bash
php bin/magento cache:flush
```

## Download Our [Magento 2 WhatsApp Chat](https://codedecorator.com/magento-2-whatsapp-chat.html) Extension
