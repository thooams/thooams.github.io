---
title: "Chronicle (GMP Software)"
subtitle: "GMP Manufacturing Automation Software"
description: "Chronicle is a GMP-compliant digital platform by Cytiva designed to automate and monitor complex cell therapy manufacturing operations, from process development to commercial production."
image: "/images/pic07.jpg"
weight: 2
doc_label: "Chronicle"
doc_url: "https://www.cytivalifesciences.com/en/us/products/items/chronicle-gmp-manufacturing-automation-software-p-09959"
cta:
  heading: "To Resume"
  text: "Chronicle is a fit-for-purpose Manufacturing Execution System (MES) for cell therapy. It bridges process development and commercial GMP manufacturing through a unified digital platform, reducing manual errors and accelerating time to release."
  links:
    - label: "Chronicle on Cytiva"
      url: "https://www.cytivalifesciences.com/en/us/products/items/chronicle-gmp-manufacturing-automation-software-p-09959"
      external: true
---

{{< section-content >}}
### Automating Cell Therapy Manufacturing

**Chronicle** is a GMP-compliant, fit-for-purpose digital solution developed by [Cytiva](https://www.cytivalifesciences.com/) to optimize complex cell therapy process development and manufacturing.

It connects Cytiva and third-party cell therapy instruments through a unified platform, supporting the full journey from early process development through commercial GMP manufacturing.

The platform provides electronic batch records, instrument scheduling, deviation management, and supply chain traceability - all independently audited against **GAMP5** standards and compliant with **21 CFR Part 11** (FDA) and **EU Annex 11** (EMA).

#### My role

I contributed to the front-end development of Chronicle, building key interfaces for instrument management, facility monitoring, and electronic standard operating procedures (eSOPs).
{{< /section-content >}}

{{< section-accent >}}
## Unified Dashboard

One central view for your entire manufacturing operation

Chronicle's home dashboard aggregates real-time data across all connected instruments, customer trials, pre-GMP and GMP organisations, and remaining credit usage - giving operations teams instant situational awareness.
{{< /section-accent >}}

{{< section-content >}}
### Instruments Overview

<img src="/images/portfolio/chronicle/Screen%20Shot%202020-04-10%20at%2020.20.17.png" alt="Chronicle dashboard" class="img-right" />

The main dashboard displays all connected instruments across two categories:

- **Cytiva Instruments**: Xuri Wave, Sofia, Sepax, AKTA Avant, AKTA Pure, VIA Freeze Quad, VIA Freeze Duo, VIA Freeze, VIA Thaw CB1000, GE Shipper
- **3rd Party Instruments**: Incubator, Fridge, Bio safety cabinet, Cell Counter, Monitoring device, Flow Cytometer, Storage Freezer, HPLC

Each instrument card shows its current unit count in real time. The header bar provides a summary of customer trials, pre-GMP organisations, GMP organisations, and total credits remaining - giving managers an instant overview of capacity.

### Equipment List

<img src="/images/portfolio/chronicle/Screen%20Shot%202020-04-10%20at%2020.21.40.png" alt="Chronicle equipment list" class="img-left" />

The equipment list provides a sortable, searchable table of every registered instrument across all demo pools and organisations. Each row surfaces:

- Instrument name and nickname
- Device type
- Serial number
- Organisation and instance
- Current status (e.g. `ready_to_use`)

This centralised registry eliminates spreadsheet-based asset tracking and provides a single source of truth for all lab instruments.
{{< /section-content >}}

{{< section-dark >}}
## Equipment Details and Connectivity

Full instrument traceability with remote access capabilities

Each instrument record captures cumulative runtime, data points, service history, and live alarm counts - along with direct links to ServiceMax and remote login access.
{{< /section-dark >}}

{{< section-content >}}
### Instrument Detail View

<img src="/images/portfolio/chronicle/Screen%20Shot%202020-04-10%20at%2020.21.58.png" alt="Chronicle equipment detail" class="img-right" />

The equipment detail page aggregates all data related to a single instrument:

- **Cumulative runtime** counter
- **Data** points collected
- **Service records** with last serviced date
- **Alarms** with delta over the last 3 months
- Serial number, device type, organisation, software version, and creation date

Operators can trigger a **ServiceMax** ticket, open a **Remote Login** session to the instrument directly, or switch the instance to GMP mode - all from the same screen.

A **Connectivity** panel shows authentication tokens and the Chronicle Gateway folder path, making it easy to diagnose integration issues without leaving the UI.
{{< /section-content >}}

{{< section-accent >}}
## Work Queue and Activity Stream

Coordinating multi-step workflows across teams and instruments

The work queue surfaces all in-progress and pending eSOPs alongside a live activity stream, so nothing falls through the cracks between shifts.
{{< /section-accent >}}

{{< section-content >}}
### Real-time Operations View

<img src="/images/portfolio/chronicle/Screen%20Shot%202020-04-10%20at%2020.22.22.png" alt="Chronicle work queue and activity stream" class="img-left" />

The home screen for GMP operators combines three panels:

- **Map view**: displays the physical location of the manufacturing facility, providing geographical context for multi-site deployments
- **Work queue**: lists all active and pending eSOPs with start dates, allowing operators to pick up tasks and track progress
- **Activity stream**: a live feed of instrument connection events and status changes across all registered devices

New shipments can be initiated directly from this screen, and eSOPs can be started with a single click - reducing the friction between planning and execution.
{{< /section-content >}}

{{< section-dark >}}
## Facility Dashboard

A visual floor plan of your manufacturing environment

The facility dashboard overlays real-time instrument data onto a floor plan, making it immediately clear which instruments are in alert state and where they are physically located.
{{< /section-dark >}}

{{< section-content >}}
### Floor Plan Monitoring

<img src="/images/portfolio/chronicle/Screen%20Shot%202020-04-10%20at%2020.23.01.png" alt="Chronicle facility dashboard" class="img-right" />

The facility dashboard renders a floor plan of the manufacturing space with each connected instrument pinned to its physical location. Instruments in a warning state are highlighted in orange with a warning banner at the top of the screen.

Each pin displays live sensor readings (temperature, CO₂ levels) and current status, allowing facility managers to spot environmental deviations at a glance without walking the floor.

This view integrates with the alarm and deviation management system, so clicking a warning pin opens the relevant deviation workflow directly.

### Electronic Standard Operating Procedures (eSOPs)

<img src="/images/portfolio/chronicle/Screen%20Shot%202020-04-10%20at%2020.23.43.png" alt="Chronicle eSOPs" class="img-left" />

Chronicle replaces paper SOPs with guided, digital step-by-step procedures. Each eSOPs task:

- Locks steps sequentially to enforce correct execution order
- Embeds photographic references of instrument displays to guide operators
- Records completion timestamps and operator identity for audit trail
- Supports deviation notes per task

This approach ensures every operator follows the exact same procedure every time, regardless of experience level, and produces a complete electronic record compliant with GMP requirements.
{{< /section-content >}}

{{< section-content >}}
### Chronicle, it is

- A GMP-compliant Manufacturing Execution System (MES) for cell therapy
- Electronic batch records audited against **GAMP5**
- Compliance with **21 CFR Part 11** and **EU Annex 11**
- Integration with Cytiva and third-party instruments
- Instrument scheduling, deviation management, and supply chain traceability
- Real-time facility monitoring via interactive floor plans
- Guided eSOPs with full audit trail

**Technology:** Ruby on Rails / React / PostgreSQL / Docker / REST APIs
{{< /section-content >}}
