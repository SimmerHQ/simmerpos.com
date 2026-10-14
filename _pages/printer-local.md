---
layout: page
title: Local printers
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; <a href="/printer/">Printers</a> &gt; Local printers
</nav>

# Local printers

1. [Add printer from the Simmer dashboard](#1-add-printer-from-the-simmer-dashboard)
2. [Select the printer type "Local printer (Shopify POS Connected)"](#2-select-the-printer-type-local-printer-shopify-pos-connected)
3. [Enter the printer's device name (Optional)](#3-enter-the-printers-device-name-optional)
4. [From within the Simmer POS extension click "Send" on the ticket you want to print](#4-from-within-the-simmer-pos-extension-click-send-on-the-ticket-you-want-to-print)

Print directly to the receipt printer connected to your Shopify POS device, with no extra print dialog.

<div class="note-box">
<strong>Note:</strong> This printing method prints to the receipt printer set up within Shopify POS (Connectivity &gt; Receipt printer). If you don't have a POS-connected receipt printer, Simmer will fall back to the device's system print dialog (for example AirPrint on iOS or the Android print service).
</div>

### 1. Add printer from the Simmer dashboard:

<img src="/assets/epson-admin/add-printer.png" alt="Add printer" class="support-image">

### 2. Select the printer type "Local printer (Shopify POS Connected)"

<img src="/assets/local-printer/select-printer-type.png" alt="Select printer type" class="support-image">

### 3. Enter the printer's device name (Optional)

Enter the printer's <b>Device name</b> exactly as it appears on Shopify POS under <b>Connectivity</b> &gt; <b>Receipt printer</b> &gt; <b>Device name</b> (for example "Star TSP143" or "Front Counter Printer").

If more than one receipt printer is connected to the device, the device name ensures tickets are sent to the correct one. If left blank, the first available printer is used.

### 4. From within the Simmer POS extension click "Send" on the ticket you want to print.

<img src="/assets/local-printer/send-to-printer.png" alt="Send ticket" class="support-image">

The ticket will print straight to your connected receipt printer.
