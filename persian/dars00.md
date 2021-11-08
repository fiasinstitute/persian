--- 
title:	Lexicon
layout: default
---

# Lexicon

{% for word in site.data.dictionary %}<strong>{{ word.farsi }}</strong> {{ word.exactr }} &emsp; <br>{% endfor %}
