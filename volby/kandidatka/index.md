---
title: Kandidátka 2018
layout: page
published: true
description: 'Kandidátka do komunálních voleb 2018 v Táboře'
keywords: piráti, tábor, volby, kandidátka
---

<div class="row">
  {% for item in site.data.kandidatka limit:3 %}
    <div class="kandidatka col-sm-12 col-md-4">
      <img src="{{item.img}}" alt="foto: {{item.name}}, {{item.age}}" />
      <div class="text">
        <h4>{{item.name}}, {{item.age}}</h4>
        <p>{{item.desc}}</p>
      </div>
    </div>
  {% endfor %}
</div>

<div class="row">
  {% for item in site.data.kandidatka offset:3 %}
    <div class="kandidatka col-sm-6 col-md-3">
      <img src="{{item.img}}" alt="foto: {{item.name}}, {{item.age}}" />
      <div class="textsm">
        <h3>{{item.name}}, {{item.age}}</h3>
        <p>{{item.desc}}</p>
      </div>
    </div>
  {% endfor %}
</div>

## #Pusťte nás na ně!
