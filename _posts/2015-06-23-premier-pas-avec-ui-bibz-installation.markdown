---
layout: post
title: "Premier Pas Avec Ui Bibz v1 : Installation"
modified:
categories: [Ui-Bibz]
excerpt: "Ui Bibz est un framework d’interface développé en Ruby on Rails permettant de créer une
interface complète avec Bootstrap sans le moindre code HTML.
Cela permet de maintenir plus facilement son code en le mettant à jour plus
rapidement.
La librairie comporte des élements simples (alert, button,...) mais aussi éléments plus complexes (table + recherche + pagination)."
tags: [Ui Bibz, Ui Bibz installation]
image:
  feature: portfolio/ui-bibz/logo.gif
date: 2015-06-23T00:22:03+02:00
---

## Préambule

<img src="https://github.com/thooams/Ui-Bibz/raw/master/doc/images/ui-bibz-logo-without-border.gif" style="float: left; margin: 15px" />
Ui Bibz est un [framework d'interface](https://fr.wikipedia.org/wiki/Framework_d'interface)
développé en [Ruby on Rails](http://rubyonrails.org/) permettant de créer une interface
complète avec [Bootstrap](http://getbootstrap.com/) sans le moindre code HTML.
Cela permet de maintenir plus facilement son code en le mettant à jour plus
rapidement.
La librairie comporte des élements simples (alert, button,...) mais aussi éléments plus
complexes (table + recherche + pagination).

## Installation

Dans un premier temps, il nous faut récupérer la gem **Ui Bibz** et l'installer sur votre
application Rails. Pour ce faire, vous devez copier cette ligne ci-dessous et
l'ajouter dans votre fichier ```Gemfile```.

{% highlight ruby %}
  gem "ui_bibz", '~> 1.0.0'
{% endhighlight %}

Ensuite lancer la commande : ```bundle install```

<br/>

Une fois installée, nous devons ajouter les dépendences aux assets
correspondantes à la librairie.

{% highlight ruby %}
# /app/assets/stylesheets/applications.css

*= require ui_bibz
{% endhighlight %}

{% highlight ruby %}
# /app/assets/javascripts/applications.js

//= require ui_bibz
{% endhighlight %}


Puis dans le layout principal, nous allons ajouter le helper ```ui_bibz_meta_links```. Celui-ci
va placer les balises ```meta``` correspondantes à **Bootstrap 3** et **Font Awesome 4**.

<br/>

Concernant la version 1 de Ui Bibz, les librairies Boostrap et Font awesome sont chargées
par CDN. Dans une prochaine version, le développeur aura le choix entre CDN ou
librairie Interne. En attendant, vous devez placer cette ligne entre les balises ```<head>``` et ```</head>```.

{% highlight ruby %}
# /app/views/layouts/application.rb

= ui_bibz_meta_links
{% endhighlight %}


And voilà !, il n'y a plus qu'à utiliser les composants de Ui Bibz afin de créer
simplement un interface.

<br/>

Dans le prochain article, je vous montrerais comment
appeler un composant dans une vue et je vous expliquerai la base du
composant Ui Bibz qui est présent dans tous les éléments du framework.

