---
title: "Fathome - Real estate ads by route"
subtitle: "Real Estate Ads by route"
description: "The real estate ads site that allows you to scrap pro and home sites linked with google maps to search an ad by route, distance or duration."
image: "/images/pic04.jpg"
weight: 5
doc_label: "Fathome"
cta:
  heading: "To Resume"
  text: "Fathome is a clever mix between a Ruby on Rails multi site scrapper and an ergonomic javascript interface allowing the setting of favorite ads, as well as a history. Its strength is of course its powerful search that allows searching by area for all ads."
  links: []
---

{{< section-content >}}
### Search a real estate ad by route, duration or distance

<img src="/images/portfolio/fathome/fathome-large.gif" alt="Fathome logo" class="img-left" width="370" height="368" />

**Fathome** is a real estate advertisements website allowing you to find professional and private properties according to itinerary, duration and distance.

Fathome browse the largest French real estate ad sites and indexes each property in a database to provide an exhaustive list of results. When the user clicks on a link of an ad, he is directly brought to the site concerned. Fathome has the particularity of not hosting ads. The ads viewed by the user are recorded in his browser and it is possible to share the list of selected properties in the bookmarks.

#### Technology

Fathome is developed in [Ruby on Rails](http://rubyonrails.org/), [Ui Bibz](https://ui-bibz-documentation.herokuapp.com/) and [Google Maps](https://www.google.com/maps) for FrontOffice.
{{< /section-content >}}

{{< section-accent >}}
## Scraper in background

Ruby Core programation

A scraper is implemented in ruby and linked to a cron job to retrieve the thousands of ads on the largest sites of French classifieds.
{{< /section-accent >}}

{{< section-content >}}
### Automation and adaptability

<img src="/images/portfolio/fathome/multi-screen.jpg" alt="Fathome multi screen" class="img-right" width="748" height="529" />

Every day the Fathome site will scan all the ads from a dozen ad sites. All this data is stored in the database in order to be accessed more quickly later. I use the **decorator** pattern to scan the different pages of each website correctly.

**Rake** tasks are launched through several **crons** tasks in order to automatize the scrapping of sites as much as possible.
{{< /section-content >}}

{{< section-dark >}}
## Search by route, duration or distance

Each ad is integrated into Fathome's database to interconnect the concept of distance and duration with the Google Map API.
{{< /section-dark >}}

{{< section-content >}}
### Search results

When the user makes a search, he can specify:

- The exact address
- The search area (in km)
- The type of property
- The type of sale
- The price

<img src="/images/portfolio/fathome/inside.gif" alt="Fathome Inside" class="img-left" width="683" height="413" />

Once the searching is done, the fathome site will request the **Google Maps API** in order to have the exact address details. Then these data will be included in the ads corresponding to the search. Once this data is collected, the fathome site will request the Google Maps API for these results in order to complete the distance, itinerary and duration information and ultimately display them into a list on the website interface.

This web interface is structured in 2 main parts:

- A list of ads on the left side
- A map of the search location with interactive ad pointers on the right side

Each ad is interconnected between the right and left parts. The selected left-hand ads are also displayed on the map as "popin". Same if an ad is selected on the right part, the list on the left will then automatically be positioned at the level of the corresponding ad.

<hr/>

### Sharing and History

<img src="/images/portfolio/fathome/fathome-search.gif" alt="Design" class="img-right" width="880" height="459" />

The user can put ads in his bookmarks without having to identify himself on the site. These actions are developed in **javascript** through browser **LocalStorage** variables, which has the benefit of avoiding the user's connection to a server-side database.

It is possible to share the list of ads as bookmark. A **base64** encoder url allows the sharing the favorites.

During a search, the displayed ads become transparent during the visit to remind the user of the history of viewed ads. As such, it is possible to find them in a page dedicated to the history of visits.
{{< /section-content >}}

{{< section-content >}}
### Fathome, it is

- A strong application with Ruby on Rails (Ruby) for the Core
- A flexible application with (Javascript) for the View
- An integration with the browser (save of ads, history)

**Technology:** Docker / Ruby on Rails / Javascript / Google Maps / Ui Bibz / HTML and CSS
{{< /section-content >}}
