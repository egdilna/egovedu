---
title: Index
layout: home
nav_order: 1
---

EGOVEDU.cz

EGOVernment EDUkace

Vzdělávání v eGovernmentu


### Co je tady nového

<ul>
{% for novinka in site.data.novinky %}
<li>{{ novinka.datum }}: {{ novinka.text }}</li>
{% endfor %}
</ul>

Mimochodem, víme, že máme problém s propagací HTTPS na doméně. Není to naše chyba, ale chyba na GitHubu, nahlášeno a prý na tom pracují...
