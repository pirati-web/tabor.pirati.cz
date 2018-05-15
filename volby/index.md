---
title: komunální volby 2018
layout: page
published: true
description: 'Rozcestník informací týkajících se komunálních voleb v Táboře'
keywords: piráti, tábor, volby
---

Chceme, aby Tábor byl městem, kde je radost žít.
A nejen dnes, ale také v budoucnosti.
K tomu je třeba, aby se rozvíjel na základě koncepce, která vznikne ve spolupráci odborníků a občanů města.

Zde je devět kapitol, které obsahují nápady a opatření, jak toho dosáhnout:

<ol>
  {% include program/list.html %}
</ol>

#### [Kompletní program ...](program/)

<a name="kandidatka"></a>
## Kandidátka

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

## #Pusťte nás na ně!

#### [Kompletní kandidátka ...](kandidatka/)
