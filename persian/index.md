--- 
title: Mā fārsi balad-im
layout: default
---

{% marginnote 'iimage' '![](Pictures/10000201000003DD0000038B553D6F4147967406.png)' %}

# MĀ FĀRSI BALAD‐IM!

Be kušeš‐e Hamid Farroukh

{% assign units=site.pages | where: "layout", "unit" | sort: "order" %}

{% for unit in units %}{% assign line=site.data.units | where: "order", unit.order | first %}{{line["order"]}}. [{{site.data.lexicons[line["category"]]}}{% if line["id"] %} {{line["id"]}}{% endif %}{% if line["title"] %}. {{line["title"] }}{% endif %}]({{unit.url}})
{% endfor %}
