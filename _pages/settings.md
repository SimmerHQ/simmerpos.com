---
layout: page
title: Settings
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; Settings
</nav>

# Simmer's Settings

- [Auto send](#auto-send)
- [Staff attribution](#staff-attribution)
- [Quick add](#quick-add)
- [Folder pinning](#folder-pinning)
- [Inventory checks](#inventory-checks)
- [Ignore zero cost modifiers](#ignore-zero-cost-modifiers)
- [Customer name](#customer-name)
- [Verify publication status](#verify-publication-status)
- [Default customer](#default-customer)
- [Search tile](#search-tile)
- [Ticket permissions](#ticket-permissions)

The **Settings** page can be accessed in **Shopify Admin** > **Simmer** > **Settings**.

Where you will find the following options:

## Auto send

Enables automatic sending of Simmer tickets to your kitchen displays and printers upon payment completion or adding to cart.

- **On cart** - sends a ticket when the **Add to cart** or **Pay** button is clicked.
- **On payment** - sends a ticket when payment has been processed.

<div class="note-box">
  This can be particularly useful when using the <b>Simmer: Quick Service</b> extension as it lacks the ability to send tickets manually.
</div>

## Staff attribution

Enables automatic staff attribution of your products within Simmer tickets that are added to the cart.

<div class="note-box">
  The staff member attributed to the sale will be the currently keyed in staff member on the POS device.
</div>

## Quick add

Enables single variant products with no modifiers to be added to the ticket / cart with one tap.

## Folder pinning

Prevents staff from being able to pin/unpin folders in Simmer POS. If you have already pinned folders, they will remain pinned.

<div class="note-box">
  This is useful for creating specialised POS devices, that only show the products in a <b>pinned folder</b> when Simmer is launched, rather than the typical grid.
</div>

## Inventory checks

Enables inventory checks and warnings for tracked, out of stock products and modifiers in Simmer POS.

## Ignore zero cost modifiers

Ignores zero cost modifiers when adding tickets to the cart in **Simmer: Full Service**.

<div class="note-box">
  Useful for hiding free modifiers from customer sales receipts. Currently only available for <b>Simmer: Full Service</b>.
</div>

## Customer name

Enables collection of the customer name on the product page in **Simmer: Full Service**.

<div class="note-box">
  The customer name is stored on the ticket and shown on printed tickets and kitchen displays, making it useful for table, name-based or takeaway orders.
</div>

## Verify publication status

Verifies that **Products**, **Collections** and **Product Variants** are present in the Shopify **Point of Sale** sales channel before they are visible in Simmer POS.

<div class="note-box">
  When enabled, products that are not published to the Point of Sale sales channel are hidden from the POS grid. This can be useful for keeping products that are only sold through your online store out of Simmer POS.
</div>

## Default customer

Automatically sets the selected customer when adding Simmer tickets to the Shopify POS cart.

Search for and select the customer to use, or use the remove button next to the customer ID to clear the selected customer.

<div class="note-box">
  This is useful for setting a default customer when stores require that a customer be selected at checkout.
</div>

## Search tile

Enables the **Search** tile in the Simmer POS product grid.

<div class="note-box">
  The Search tile is the only way to search products in Simmer POS, so disable this only if you navigate by folders and collections only.
</div>

## Ticket permissions

Requires a PIN before staff can delete line items from an existing ticket or cancel a ticket in **Simmer: Full Service**.

Use **Set PIN** to enable the setting, **Change PIN** to replace the existing PIN, or **Remove PIN** to disable it. The PIN must be 4 to 8 digits.

<div class="note-box">
  The PIN is stored securely and can't be viewed after it has been saved. Staff are prompted for it on the POS PIN pad when deleting a line item or cancelling a ticket. Currently only available for <b>Simmer: Full Service</b>.
</div>
