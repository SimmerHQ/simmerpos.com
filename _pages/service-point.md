---
layout: page
title: Service points
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; <a href="/table-service/">Table service</a> &gt; Service points
</nav>

# Table management

- [Service points](#service-points)
- [Service point groups](#service-point-groups)
- [How to setup table management](#how-to-setup-table-management)
- [How to use table management](#how-to-use-table-management)

Table management is a flexible feature that can be used for buzzers, flags and more.

There are two concepts:

### Service points

Used to define the name of the table. E.g. “Table 1” or “Flag 1”.

### Service point groups

Used to group service points. E.g. “Indoor tables”, “Flags” or “Buzzers”.

## How to setup table management

First step is to create service points groups:

<img src="/assets/table-service/add-service-point-group.png" alt="Service point group" class="support-image">

Then create service points:

<img src="/assets/table-service/add-service-point.png" alt="Service point" class="support-image">

## How to use table management

Once the service points and groups have been created, you can use them in the Simmer POS extension when editing a ticket or via the **Service Points** tile on the Simmer Grid:

<img src="/assets/table-service/pos-service-points-tile.png" alt="POS grid service points tile" class="support-image">
<img src="/assets/table-service/pos-service-points.png" alt="POS grid service points page" class="support-image">

Selecting an occupied service point (<span class="service-point">◼</span>) will make the ticket associated with the service point the currently active ticket.

Selecting an unoccupied service point (<span class="service-point">◻</span>) will create a ticket and make it the currently selected ticket.

Service points will be cleared as tickets are closed out - either by adding them to cart and accepting payment, or by cancelling the ticket.
