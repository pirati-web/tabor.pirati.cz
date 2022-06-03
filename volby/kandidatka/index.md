---
title: Kandidátka 2022
layout: page
published: true
image: /static/media/top11.jpg
description: 'Kandidátka do komunálních voleb 2022 v Táboře'
keywords: piráti, tábor, volby, kandidátka
---

<div class="row">
  {% for item in site.data.kandidatka limit:3 %}
    <div class="kandidatka col-sm-12 col-md-4">
      <img src="{{item.img}}" alt="foto: {{item.name}}, {{item.age}}" />
      <div class="text">
        <h4>{{item.name}}</h4>
        <p>{{item.age}} let, {{item.desc}}</p>
      </div>
    </div>
  {% endfor %}
</div>

<div class="row">
  {% for item in site.data.kandidatka offset:33 %}
    <div class="kandidatka col-sm-6 col-md-3">
      {% if item.img %}
      <img src="{{item.img}}" alt="foto: {{item.name}}, {{item.age}}" />
      {% else %}
      <img src="https://svgsilh.com/png-512/2026758-ffc107.png" alt="foto: zastupne foto" />
      {% endif %}
      <div class="text">
        <h3>{{item.name}}</h3>
        <p>{{item.age}} let, {{item.desc}}</p>
      </div>
    </div>
  {% endfor %}
</div>

## #odvaha dělat věci správně
