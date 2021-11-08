--- 
title:	lexicon
layout: default
---

{% for word in site.data.dictionary %}{% if word.chapter=='1' %}<strong>{{ word.farsi }}</strong> {{ word.exactr }} &emsp; {% endif %}<br>{% endfor %}

