---
title: Zastupitelský klub táborských Pirátů
layout: page
published: true
description: 'Dlouhodobá koncepce: Tábor jako moderní město, které se dívá do budoucnosti'
keywords: zastupitele, piráti, tábor
---

<div class="row">
  {% for item in site.data.zastupitele %}
    <div class="kandidatka col-sm-12 col-md-3">
      <img src="{{item.img}}" alt="foto: {{item.name}}, {{item.age}}" />
      <div class="text">
        <h4>{{item.name}}</h4>


        <div>
          <a href="{{item.facebook}}" target="_blank">Facebook</a>
        </div>

        {% if item.web %}
        <div>
          <a href="{{item.web}}" target="_blank">Web</a>
        </div>
        {% endif %}

        {% if item.calendar %}
        <div>
          <a href="{{item.calendar}}" target="_blank">Veřejný kalendář</a>
        </div>
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>
