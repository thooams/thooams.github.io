---
title: "EIME (Web App)"
subtitle: "Perform Life Cycle Assessments App"
description: "Eime is a referential that lets you easily perform Life Cycle Assessments (LCA) and eco-design projects in compliance with international programmes."
image: "/images/pic06.jpg"
weight: 8
doc_label: "EIME"
doc_url: "http://beta.codde.fr/nos-logiciels/eime/presentation-eime/"
cta:
  heading: "To Resume"
  text: "Other interfaces (database, administration, project manager) are under development and will take the functionalities already present in the existing interfaces."
  links:
    - label: "EIME website"
      url: "http://beta.codde.fr/nos-logiciels/eime/presentation-eime/"
      external: true
---

{{< section-content >}}
### Environmental Improvement Made Easy

<img src="/images/portfolio/eime/eime-logo.gif" alt="EIME logo" class="img-left" />

**EIME** is a referential that allows easily perform Life Cycle Assessments (LCA) and eco-design projects in accordance with international programmes and standards.

In addition to facilitate decision-making and allow a clear environmental communication, speed of its handling and ergonomics guarantee an optimum working efficiency.

#### Technology

Eime is developed in [Ruby on Rails](http://rubyonrails.org/) in its core and in [ExtJS](http://www.sencha.com/products/extjs/) for FrontOffice.
{{< /section-content >}}

{{< section-accent >}}
## Back office

Ruby Core programation

Eime has data versioning in the core application. Mixed with many formulas and a huge database, Eime allows very little time, thanks to these optimized applications (postgresql), analyzing the product created by the user in the software in record time.
{{< /section-accent >}}

{{< section-content >}}
### Notification Center

<img src="/images/portfolio/eime/notification-center-computer.png" alt="Notification center" class="img-right" />

For long operations:

- .xls export
- .xls import
- analyse export
- design export
- multi copy/cut/paste

Eime will launch in the background intensive actions in time and process so the user can continue to browse without any latency.

Of course, a percentage display of each action is available in real time in the notification center. In addition, a web notification system (Chrome / Firefox) allows to be informed of the purpose of the process.

<img src="/images/portfolio/eime/notification-chrome.png" alt="Notification center Chrome" class="img-left" />

The technology of the notification center is based on a background job system ([Delayed Job](https://github.com/collectiveidea/delayed_job)) and a pubsub system ([Faye](http://faye.jcoglan.com/)).

The notification center provides a historic of copy / cut / paste to choose one of the last 3 actions in force.

### Multi copy/cut/paste

<img src="/images/portfolio/eime/copy-paste-computer.png" alt="Copy cut paste" class="img-left" />

The system of multi copy / cut / paste is used in several interfaces within the application. Eime is a software including the logic of "container / item", so it is natural that a simple and effective method is implemented to move many projects, folders, boxes study, containers, modules flow.
{{< /section-content >}}

{{< section-dark >}}
## Front office

ExtJS developments

ExtJS (javascript) allows to render the application more dynamic with notifications, copy/paste with progression in real time.
{{< /section-dark >}}

{{< section-content >}}
### Analysis/graphs/calculation Interface

<img src="/images/portfolio/eime/analysis-values-computer.png" alt="Analysis values" class="img-right" />

The **Analysis** part includes two distinct parts:

- Table of values
- Graphics

Some calculations are optimized through database queries to a performance gain. A tab management was created in order to compare the results of calculations.

<img src="/images/portfolio/eime/analysis-graphs-computer.png" alt="Analysis graphs" class="img-left" />

**Graphics** exploit previous values to offer the most appropriate chart (pie, bar, column...). It is possible to refine the results of graphics in real time and also to set these through the 3d or changing scales.

<hr/>

### Design Interface

<img src="/images/portfolio/eime/design-computer.png" alt="Design" class="img-right" />

The design part includes several distinct elements:

- Tab
- Tree
- Overview
- Breadcrumb
- Database

A case study contains phases represented by a tab system. These tabs contain a tree on the left, an overview with a search engine, an interactive breadcrumb and information panels.

The database with integrated search engine includes an information panel. Each element inserted in the overview includes all different rights depending on where the item is located. Visual information indicates in real time if the insertion is possible to achieve.

The copy / cut / paste is also present. A window opens indicating in real time (as in modern OS) the progress of the current action.

### Main Search (spotlight)

<img src="/images/portfolio/eime/main-search-computer.png" alt="Main search" class="img-left" />

The Main research is a kind of spotlight (like Apple spotlight) and allows to find any information in the application through a search window.

### Project Interface

<img src="/images/portfolio/eime/project-computer.png" alt="Project" class="img-right" />

The Project part provides a project tree on the left, an overview at the center and a retail panel on the right. The copy / cut / paste is also active as well as the right click allowing more actions.
{{< /section-content >}}

{{< section-content >}}
### EIME, it is

- More than 20 servers running on Docker with:
  - a pubsub server Faye (nginx)
  - a background job server Delayed Job (thin)
  - a postgres database (AWS RDS)
- A strong application with Ruby on Rails (Ruby) for the Core
- A flexible application with ExtJS (Javascript) for the View
- A dynamic application with PubSub

**Technology:** Docker / Ruby on Rails / Coffeescript and ExtJS / HTML and CSS
{{< /section-content >}}
