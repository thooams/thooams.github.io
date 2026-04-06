---
title: "Ui Bibz V3 (Framework)"
subtitle: "Bootstrap Framework with Ruby on Rails"
description: "Ui bibz is an interface framework for building an interface very quickly and simply using Ruby on Rails 6 and Bootstrap 5."
image: "/images/pic01.jpg"
weight: 2
doc_label: "Ui Bibz"
doc_url: "/ui-bibz/index.html"
cta:
  heading: "To see More"
  text: ""
  links:
    - label: "Documentation"
      url: "http://hummel.link/ui-bibz/index.html"
      external: true
    - label: "Github source code"
      url: "https://github.com/thooams/Ui-Bibz"
      external: true
---

{{< section-content >}}
### One component to rule them all

<img src="/images/portfolio/ui-bibz/ui-bibz-logo-without-border.gif" alt="Ui Bibz logo" class="img-left" style="border: 20px solid white;" />

Library **Ui Bibz** is based on one component. All components inherit from `component` element. No need to write **HTML**, **CSS** or **Javascript**. Components are based on [Bootstrap](http://getbootstrap.com/) and all new versions are managed by Ui Bibz. The framework is written with [Ruby](https://www.ruby-lang.org/) for [Ruby on Rails](http://rubyonrails.org/).

A component will always write the same way even if HTML, CSS or Javascript code change. You can find all components of Bootstrap 5 and more.
{{< /section-content >}}

{{< section-accent >}}
## Ui

Core Framework

Alerts, inputs, breadcrumbs, cards, cols, buttons, dropdowns and +30 components are available right now.
{{< /section-accent >}}

{{< section-content >}}
### Content, options, html_options

Ui Bibz component is based on Ruby on Rails [link_to](http://api.rubyonrails.org/classes/ActionView/Helpers/UrlHelper.html#method-i-link_to) method with some specificity.

```ruby
def component content = nil, options = nil, html_options = nil, &block
end
```

<img src="/images/portfolio/ui-bibz/components-computer.png" alt="Components" class="img-left" />

The content can be inserted inline on the **content** variable or by **block**. **Options** and **html_options** are hashes present to configure the component or its html.

**That's All!**

All components are based on this fundamental principle. Some elements are variants but copy the same model.

### Simple and efficient

Library is organized by namespace like `UiBibz::Ui::Buttons::ButtonLink` and to facilitate and improve use of Ui Bibz, helpers are created for calls rendering of components very easily with simple methods: cols, dropdown, button_link...

All input components are compatible with [simple_form](https://github.com/plataformatec/simple_form) to create forms very easily.

### Tested, Gemified, Installed

<img src="/images/portfolio/ui-bibz/rubygems.jpg" alt="Rubygems" class="img-left" />

All components are tested with unit tests (Minitest). Library follows the latest version of Ruby on Rails, Bootstrap or FontAwesome and is updated monthly.

Library is downloadable as gem on [Rubygem](https://rubygems.org/gems/ui_bibz) or as the source code on [Github](https://github.com/thooams/Ui-Bibz).
{{< /section-content >}}

{{< section-dark >}}
## Ux

Extension for Users

Ux interface with complex components created by developers for developers.
{{< /section-dark >}}

{{< section-content >}}
### An extensible library

<img src="/images/portfolio/ui-bibz/table-card-computer.png" alt="Table card" class="img-left" />

Ui Bibz library is extensible with complex components. Usually, there are mixed components like `card_table` (table in card) with a search engine, pagination and sortable columns.

Components can contain Javascript, Html and CSS but the philosophy of the library for the user is to configure a component without writing HTML, Javascript or CSS code.
{{< /section-content >}}

{{< section-accent >}}
## And After

Future developments

Library Open Source ready to be forked.
{{< /section-accent >}}

{{< section-content >}}
### Open Source and forkable

The goal of the library is to help developers to build interfaces very quickly and easily without writing html, javascript or css. Ui Bibz is Open Source (MIT licence) and all people can fork the code to create new components.

**Technology:** Ruby on Rails / Javascript (Vanilla) / HTML and CSS (SASS)
{{< /section-content >}}
