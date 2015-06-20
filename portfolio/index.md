---
layout: portfolio-index
title: Portfolio
excerpt: "Portfolio of Thomas HUMMEL"
tags: [ruby development, rails development, ruby portfolio, ruby on rails
portfolio]
image:
  feature: sample-image-3.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

{% include _toc.html %}

{% for portfolio in site.portfolio %}
# {{ portfolio.title }}
{{ portfolio.image }}
{{ portfolio.description }}
{% endfor %}




