---
title: "M.L. Pacheco - Publications"
layout: gridlay
excerpt: "M.L. Pacheco -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %}