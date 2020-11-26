---
title:	Mā fārsi balad-im
layout: unit
order: 00
---


{% for word in site.data.dictionary %}{% if word.chapter==1 %}<strong>{{ word.farsi }}</strong> {{ word.exactr }} &emsp; {% endif %}{% endfor %}



