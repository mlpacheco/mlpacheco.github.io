---
title: "M.L. Pacheco - Publications"
layout: gridlay
excerpt: "M.L. Pacheco -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

{% for publi in site.data.publist %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br />
  <em>{{ publi.venue }}</em> <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %}
