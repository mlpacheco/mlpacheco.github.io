---
title: "M.L. Pacheco - Publications"
layout: gridlay
excerpt: "M.L. Pacheco -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## 2022

{% for publi in site.data.publist_2022 %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br />
  <em>{{ publi.venue }}</em> <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %}

## 2021

{% for publi in site.data.publist_2021 %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br />
  <em>{{ publi.venue }}</em> <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %}

## 2016-2020

{% for publi in site.data.publist %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br />
  <em>{{ publi.venue }}</em> <br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  <a href="{{ publi.code.url }}">{{ publi.code.display }}</a>

{% endfor %}
