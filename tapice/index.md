---
title: Táborské Pirátské Centrum (TaPiCe)
layout: page
description: Stránka věnovaná speciálně pirátskému centru.
keywords: pice, centrum, základna
---

## Adresa

Budějovická 1997/12, 390 02 Tábor

### Program akcí

{% for item in site.data.tapiceprogram %}
  <div class="text">
    <h4><b>{{item.cas}}</b>: {{item.name}}</h4>
    <p>
      {{item.desc}}
      {% if item.fbevent %}
      <a href="{{item.fbevent}}" target="_blank">facebook událost zde.</a>
      {% endif %}
    </p>
  </div>
{% endfor %}




