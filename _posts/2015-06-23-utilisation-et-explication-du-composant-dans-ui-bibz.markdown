---
layout: post
title: "Utilisation Et Explication Du Composant Dans Ui Bibz"
modified:
categories: [Ui Bibz]
excerpt: "Le composant, dit Component, est au centre de l'expérience du
framework Ui Bibz. Tous les éléments de la librairie sont basés et calqués
sur ce modèle."
tags: []
image:
  feature: portfolio/ui-bibz/logo.gif
date: 2015-06-23T14:06:54+02:00
---

## Explication

Le composant, dit ```Component```, est au centre de l'expérience du
framework **Ui Bibz**. Tous les éléments de la librairie sont basés et calqués
sur ce modèle.

Un ```component``` accepte en arguments :

* le contenu attribué par **variable** ou par **block**
* les options du composant (hash)
* les options html du composant (hash)

## Utilisation

Celui-ci se configure simplement comme ci-dessous :

{% highlight ruby %}
  Component.new(content, options = {}, html_options = {}, &block)
{% endhighlight %}

Ce qui signifie que vous pouvez l'appeler de ces 2 manières :

{% highlight ruby %}
Component.new('Mon exemple 1', { state: :success }, { class: 'exemple 1'} ).render

Component.new({ glyph: 'eye' }, { style: 'width: 100%' }) do
  Mon exemple 2
end.render
{% endhighlight %}

Vous pouvez remarquer que la méthode ```render``` est appelée à la fin du
composant. Cela permet de générer le code HTML de l'élément.
Vous pouvez vous apercevoir que certaines options sont déjà implémentées dans
l'élément de base ```component``` comme :

* le glyph (icone Awesome Font)
* l'état (_:success, :danger, :warning, :info, :primary, :default_)

Le glyph est élément un peu particulier de Ui Bibz et j'évoquerai son
utilisation un peu plus tard dans un prochain article.

<br/>

Une fois que vous connaissez le ```component```, vous connaissez le comportement
utilisé dans la casi totalité des éléments du framework.



