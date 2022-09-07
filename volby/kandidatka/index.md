---
title: Kandidátka 2022
layout: page
published: true
image: /static/media/top11.jpg
description: 'Kandidátka do komunálních voleb 2022 v Táboře'
keywords: piráti, tábor, volby, kandidátka
---

<div class="row">
  {% for item in site.data.kandidatka limit:9 %}
    <div class="kandidatka col-sm-12">
      <img src="{{item.img}}" alt="foto: {{item.name}}, {{item.age}}"
            style="width: 400px; float: right; margin: 0 0 2em 2em;" />
      <h2>{{item.name}}</h2>
      <h4>{{item.age}} let, {{item.desc}}</h4>
      {{ item.bio | markdownify }}
    </div>
  {% endfor %}
</div>

<div class="row my-5">
  {% for item in site.data.kandidatka offset:9 %}
    <div class="col-sm-12">
      <h4>{{item.name}}</h4>
      <p>{{item.age}} let, {{item.desc}}</p>
    </div>
  {% endfor %}
</div>

## #odvaha dělat věci správně
