---
layout: page
title: Online ordering
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; Online store
</nav>

# Online store setup

- [Enable online store within Simmer](#enable-online-store-within-simmer)
- [Add a full address to your store location](#add-a-full-address-to-your-store-location)
- [Add store opening times](#add-store-opening-times)
- [Add pickup shipping method](#add-pickup-shipping-method)
- [Add products to the online store channel](#add-products-to-the-online-store-channel)
- [Add products to Simmer collections](#add-products-to-simmer-collections)
- [Add modifier selection theme block to product page](#add-modifier-selection-theme-block-to-product-page)
- [Add delivery method and date picker to cart page](#add-delivery-method-and-date-picker-to-cart-page)
- [QR code ordering setup (optional)](#qr-code-ordering-setup-optional)
  - [Enable the Simmer app theme block](#enable-the-simmer-app-theme-block)
  - [Add dine in shipping method](#add-dine-in-shipping-method)
- [Limitations](#limitations)
  - [Accelerated checkout](#accelerated-checkout)
  - [Drawer cart](#drawer-cart)
  - [Troubleshooting](#troubleshooting)

## Enable online store within Simmer

From the Simmer Admin, navigate to **Settings** > **Online store**. Then click **Enable**.

## Add a full address to your store location

Your pickup location must have a full address added to it in order for the pickup in store option to be work correctly.

From the Shopify Admin, navigate to **Settings** > **Locations** and select the location that you want to add the address to.

## Add store opening times

From the Simmer Admin, navigate to **Online store** and add your store opening times by selecting each of your locations.

<img src="/assets/online/edit-opening-hours.png" alt="Store opening times" class="support-image">

## Add pickup shipping method

From the Shopify Admin, navigate to **Settings** > **Shipping and delivery** and select the shipping profile that you want to add the pickup shipping method to, by default this is called **General shipping rates**.

<img src="/assets/online/shipping-delivery.png" alt="Add pickup shipping method" class="support-image">

Then click **Add rate**

<img src="/assets/online/add-rate.png" alt="Add rate" class="support-image">

Then enter a custom rate name, this must be called exactly **Pickup in store** and click **Done**. This is required for Simmer to identify the pickup shipping method.

<img src="/assets/online/rate-modal.png" alt="Rate modal" class="support-image">

Then click **Save** at the top of the page.

## Add products to the online store channel

Add your food and drink products to the **Online Store sales channel**.

<img src="/assets/online/online-store-sales-channel.png" alt="Add products" class="support-image">

## Add products to Simmer collections

You'll need to add each of the food and drinks products you wish to offer online to at least one of the Simmer collections, such as "Simmer: Products" or your Simmer folder collections.

You must also ensure that any Simmer Collections that you plan to use on the online store are also added to the **Online Store sales channel**, this includes the **"Simmer: Modifiers"** collection if you plan to use modifiers on your products.

This helps Simmer determine which are regular products and which are food and drinks, or modifiers so we can exclude them from standard postal shipping.

## Add modifier selection theme block to product page

Next you'll need to add the **Product Modifiers** block to the product page.

<div class="note-box">
You'll need to add the Product Modifiers block even if your products don't have any modifiers.
</div>

From the Shopify Admin, navigate to **Online Store** > **Themes** and select **Customize** for the theme you want to add the block to.

Then navigate to the **Product page** section.

<img src="/assets/online/theme-product-page.png" alt="Product page" class="support-image">

Add the **Simmer - Modifiers** block.

<img src="/assets/online/add-theme-block.png" alt="Add modifier selection block" class="support-image">

## Add delivery method and date picker to cart page

From the Shopify Admin, navigate to **Online Store** > **Themes** and select **Customize** for the theme you want to add the block to.

Then navigate to the **Cart page** section.

<img src="/assets/online/navigate-to-cart.png" alt="Navigate to cart page" class="support-image">

Then add the Simmer **Delivery Options** cart block to the **Subtotal** section of the cart page.

<img src="/assets/online/add-cart-block.png" alt="Add cart block" class="support-image">

## QR code ordering setup (optional)

You can use our QR code ordering feature to allow customers to make dine in orders via the online store. The QR code must contain the following components:

- **simmer_location** - the ID of the Shopify location that you want the tickets associated with, you can find this in **Shopify Admin** > **Settings** > **Locations**, select the location you'd like to use, then you will find the ID in the URL, e.g. `.../settings/locations/1234567890` where `1234567890` is the ID.
- **simmer_name** - this is used to populate the "Name" field of the resulting Simmer ticket, you can use this to identify the table. E.g. "T1"

The complete URL to be encoded as a QR code would look something like this:

- `https://<YOUR_ONLINE_STORE_DOMAIN>?simmer_location=1234567890&simmer_name=T1`

QR code ordering requires enabling the **Simmer app theme block** and **adding a dine in shipping method**, instructions for these steps below.

### Enable the Simmer app theme block

From the Shopify Admin, navigate to **Simmer** > **Online store** and scroll down to the bottom of the page where you will find a sections titled **Simmer app theme block**, click **Activate in theme**.

<img src="/assets/online/app-embed-block.png" alt="Enable the Simmer app theme block" class="support-image">

You will be taken to your currently active online store theme where you will be able to toggle on/off the **Simmer app theme block**. There are two options here:

- **QR code parameter parser**: enable this on to use QR code ordering.
- **Process all orders as tickets**: enable this if you'd like all orders that come in via your online store to be process by Simmer and turned into tickets.

### Add dine in shipping method

From the Shopify Admin, navigate to **Settings** > **Shipping and delivery** and select the shipping profile that you want to add the dine in shipping method to, by default this is called **General profile**.

<img src="/assets/online/shipping-delivery.png" alt="Add pickup shipping method" class="support-image">

Then click **Add shipping option**

<img src="/assets/online/add-rate.png" alt="Add rate" class="support-image">

Enter a custom shipping option name, this must be called exactly **Dine in** and click **Done**. This is required for Simmer to identify the dine in shipping method.

<img src="/assets/online/add-dine-in-shipping-option.png" alt="Add dine in shipping method" class="support-image">

Then click **Save** at the top of the page.

## Limitations

### Accelerated checkout

**Accelerated checkout** is not supported for online store orders as this bypasses the Simmer theme blocks.

- Go to your Shopify Admin
- Click **Online Store** > **Themes**
- Click **Edit theme** next to your live theme
- Go to the Product page template in the theme editor
- Click on the **Product Information** section
- Expand the **Buy buttons** section and hide the **Accelerated checkout** button
- Click **Save**

<img src="/assets/online/accelerated-checkout.png" alt="Add cart block" class="support-image">

This also includes the **Quick add** option on Product cards which also bypasses the Simmer theme blocks by adding products directly to the cart.

- Go to your Shopify Admin
- Click **Online Store** > **Themes**
- Click **Edit theme** next to your live theme
- Click **Theme settings** in the top right
- Expand the **Product cards** section
- Disable the **Quick add** option
- Click **Save**

<img src="/assets/online/quick-add.png" alt="Add cart block" class="support-image">

### Drawer cart

The drawer cart is not supported because it is not possible to add the Simmer delivery block to it.

<img src="/assets/online/cart-page.png" alt="Drawer cart" class="support-image">

### Troubleshooting

If you're having trouble with the online store, please email [help@simmerpos.com](mailto:help@simmerpos.com).
