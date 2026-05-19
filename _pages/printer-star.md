---
layout: page
title: Star Micronics printer support Shopify KDS
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; <a href="/printer/">Printers</a> &gt; Star Micronics
</nav>

# Star Micronics printer guide

- [Create a ticket printer](#create-a-ticket-printer)
  1. [Add printer from the Simmer dashboard](#1-add-printer-from-the-simmer-dashboard)
  2. [Give your printer a name, brand and select the Shopify location you want to use it in](#2-give-your-printer-a-name-brand-and-select-the-shopify-location-you-want-to-use-it-in)
  3. [Use the printer's credentials in the following guide on how to configure the printer](#3-use-the-printers-credentials-in-the-following-guide-on-how-to-configure-the-printer)
- [Configure the Star Micronics printer](#configure-the-star-micronics-printer)
  1. [Navigate to your printer's LAN address](#1-navigate-to-your-printers-lan-address)
  2. [Click Login](#2-click-login)
  3. [Enter your user name and password](#3-enter-your-user-name-and-password)
  4. [Click CloudPRNT](#4-click-cloudprnt)
  5. [Enter the URL, ID, and Password provided by Simmer](#5-enter-the-url-id-and-password-provided-by-simmer)
  6. [Click Submit](#6-click-submit)
  7. [Click Execute](#7-click-execute)
  8. [Wait for your printer to restart](#8-wait-for-your-printer-to-restart)
- [Print tickets](#print-tickets)

Simmer currently supports Star Micronics printers with **CloudPRNT**.

If you are unsure if your printer supports **CloudPRNT** visit the Star Micronics <a href="https://star-emea.com/products/cloudprnt/" target="_blank">website</a> or contact <a href="mailto:help@simmerpos.com">help@simmerpos.com</a>.

## Create a ticket printer

### 1. Add printer from the Simmer dashboard:

<img src="/assets/epson-admin/add-printer.png" alt="Add printer" class="support-image">

### 2. Give your printer a name, brand and select the Shopify location you want to use it in:

<img src="/assets/star-admin/create-printer-star.png" alt="Create printer" class="support-image">

### 3. Use the printer's credentials in the following guide on how to configure the printer:

<img src="/assets/epson-admin/printer-credentials.png" alt="credentials printer" class="support-image">

## Configure the Star Micronics printer

<div class="note-box">
<strong>Note:</strong> The instructions are for Star Micronics TSP143IV. The interface may vary slightly for other Star Micronics printers.
</div>

### 1. Navigate to your printer's LAN address:

How to find your printer's LAN address:

- Ensure printer is turned off
- Hold down the feed button
- Turn printer on while holding the feed button
- Release feed button once it starts printing

Your printer should print out a receipt with your printer's LAN address. Enter this into your browser to navigate to the printer's settings page, e.g `http://192.168.1.100`. (replace with your printer's actual IP address).

### 2. Click **Login**

<img src="/assets/star-admin/1.png" alt="Advanced Settings" class="support-image-large">

### 3. Enter your user name and password

<img src="/assets/star-admin/2.png" alt="Administrator Login" class="support-image-large">

### 4. Click **CloudPRNT**

<img src="/assets/star-admin/3.png" alt="Printer Serial No." class="support-image-large">

### 5. Enter the URL, ID, and Password provided by Simmer

<img src="/assets/star-admin/4.png" alt="Printer credentials" class="support-image-large">

### 6. Click **Submit**

<img src="/assets/star-admin/5.png" alt="Submit" class="support-image-large">

### 7. Click **Execute**

<img src="/assets/star-admin/6.png" alt="Execute" class="support-image-large">

### 8. Wait for your printer to restart

<img src="/assets/star-admin/7.png" alt="Restart" class="support-image-large">

## Print tickets

You can now print tickets from the Simmer POS tile by going to the ticket and clicking **Send**:

<img src="/assets/epson-admin/send-to-printer.png" alt="Send to printer" class="support-image-large">
