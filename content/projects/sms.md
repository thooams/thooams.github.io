---
title: "SMS (SaaS)"
subtitle: "Stock Management System for Stockoss"
description: "SMS is the back-office Stock Management System powering Stockoss, a B2B logistics platform. It centralizes warehouse references, orders, entities, taxonomies, and inventory across a network of 20+ logistics partners."
image: "/images/pic10.jpg"
weight: 3
doc_label: "SMS"
doc_url: "https://www.stockoss.com/"
cta:
  heading: "To Resume"
  text: "SMS is the operational backbone of the Stockoss logistics platform, handling tens of thousands of references, orders, and warehouse entities in real time across multiple clients and partner warehouses."
  links:
    - label: "Stockoss website"
      url: "https://www.stockoss.com/"
      external: true
---

{{< section-content >}}
### The back-office powering a logistics platform

<img src="/images/portfolio/sms/Screenshot%202026-04-06%20at%2021.49.11.png" alt="SMS dashboard" class="img-right" width="3332" height="2100" />

**SMS** (Stock Management System) is the internal back-office platform built to operate [Stockoss](https://www.stockoss.com/), a French B2B SaaS logistics solution trusted by clients including Christian Louboutin, LVMH, ASUS, and Stellantis.

The dashboard gives operations teams a real-time overview of the entire platform: active warehouses, references, orders, deliveries, collections, taxonomies, users, specifications, and entities - all in one place.

At a glance the platform manages:
- **21,000+ active warehouses**
- **95,000+ references** across all inventories
- **22,000+ orders** (deliveries and collections)
- **6,300+ taxonomies** and **90+ active users**

#### Technology

SMS is built full stack with [Ruby on Rails](https://rubyonrails.org/), using [Hotwire Turbo](https://turbo.hotwired.dev/) for real-time interface updates, [PostgreSQL](https://www.postgresql.org/) for data storage, and deployed on [AWS](https://aws.amazon.com/) infrastructure.
{{< /section-content >}}

{{< section-accent >}}
## Order Management

End-to-end order tracking from creation to delivery

Each order is tracked through its full lifecycle: progression, status, warehouse assignment, preparation deadline, and route date - with instant filtering across 32,000+ commands.
{{< /section-accent >}}

{{< section-content >}}
### Orders list

<img src="/images/portfolio/sms/Screenshot%202026-04-06%20at%2021.48.55.png" alt="SMS orders list" class="img-left" width="3334" height="2074" />

The orders list provides a dense, sortable table covering all deliveries and collections across every client and warehouse. Each row exposes:

- **Batch** and order number
- **Type**: Delivery or Collect
- **Progression** bar with percentage
- **Status** with color-coded badges (including overdue alerts)
- Inventory name, warehouse, creation date, and preparation deadline
- Route date, requested references, managed references, and ordered quantities

Filters can be stacked by client, warehouse, status, or date range. New collections and deliveries can be initiated directly from this view without navigating away.
{{< /section-content >}}

{{< section-dark >}}
## Reference Catalog

A centralized product database shared across all warehouses and clients

Each reference is linked to its warehouse locations, inventory names, specifications, and commercial information - forming a single source of truth across the entire logistics network.
{{< /section-dark >}}

{{< section-content >}}
### References list

<img src="/images/portfolio/sms/Screenshot%202026-04-06%20at%2021.49.28.png" alt="SMS references list" class="img-right" width="3324" height="2100" />

The references list aggregates all 95,000+ product references across every client account. Each row shows the client designation, catalog code, description, quantity in warehouse, associated warehouses, inventory names, creation and update dates, and active status.

References are filterable by quantity, allowing warehouse operators to quickly surface low-stock or out-of-stock items. Product photos are displayed inline for fast visual identification.

### Reference detail

<img src="/images/portfolio/sms/Screenshot%202026-04-06%20at%2021.49.46.png" alt="SMS reference detail" class="img-left" width="3326" height="2100" />

The reference detail page centralizes all data attached to a single product:

- Client designation, main category, and subcategory
- Stock quantity in warehouse and available quantity (excluding active orders)
- PCB (pack configuration), picking path sorter, and inventory names
- Thresholds and active status
- **Specifications panel**: custom attributes per product (color, size, material...)
- **Commercial information**: catalog code and catalogue reference
- Product photos with inline preview

Specifications are fully dynamic: operators can add new attributes without any code change, adapting the catalog schema to each client's requirements.
{{< /section-content >}}

{{< section-accent >}}
## Entity Tracking

Granular stock location down to the pallet, shelf, and bin level

Entities represent physical stock units located inside a warehouse. Each entity links a reference to a precise location identifier, quantity, and inventory - enabling accurate picking and replenishment.
{{< /section-accent >}}

{{< section-content >}}
### Entities and linked orders

<img src="/images/portfolio/sms/Screenshot%202026-04-06%20at%2021.50.10.png" alt="SMS entities and orders" class="img-right" width="3324" height="2100" />

The entity view lists every physical stock unit for a given reference: location code, warehouse, inventory, quantity, creation and update timestamps, and active status.

Below the entity table, all linked orders (deliveries and collections) are displayed with their batch number, type, progression, status, inventory, route date, and creation date.

This three-panel structure (entities, orders, order items) gives warehouse managers full traceability from a physical stock location all the way back to the client order that generated the movement.
{{< /section-content >}}

{{< section-content >}}
### SMS, it is

- A multi-tenant back-office platform serving 200+ active clients
- Real-time order management across 20+ warehouse partners and 50+ transporters
- 95,000+ references with dynamic specification schemas per client
- Granular entity tracking down to warehouse location level
- Fully integrated OMS and WMS in a single Ruby on Rails application
- Deployed and operated on OVH cloud infrastructure

**Technology:** Ruby on Rails / Hotwire Turbo / PostgreSQL / AWS
{{< /section-content >}}
