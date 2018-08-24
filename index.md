---
layout: default
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: organizace,transparence,politika
---

<div class="callout">
  <div class="container">
    <div class="row">
      <div class="col-sm-7 offset-lg-1">
        <h1>JSME PIRÁTI TÁBOR</h1>
        <h2>A POMÁHÁME NAŠEMU MĚSTU</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12 col-lg-4 offset-lg-1">
        <p id="calloutpopis">
          Naším cílem je obec, kde může každý člověk prožít svůj život svobodně a naplno.
          Klíčem k prosperitě naší společnosti je otevřenost,
          kvalitní vzdělání a veřejné služby,
          použití nových technologií a zapojení občanů do rozhodování.
        </p>
        <!-- <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more &raquo;</a></p> -->
      </div>
    </div>
  </div>
</div>

<div class="container">

  <div class="row">
    <div class="col-sm-12 col-lg-8">
      <section id="posts">
      {% for post in site.posts limit:3 %}
        <div class="column">
        {% include shared/articlesumary.html %}
        </div>
      {% endfor %}
        <h4><a href="/clanky/">Ostatní články ...</a></h4>
      </section>
    </div>

    <div class="col-sm-12 col-lg-4">
      <div markdown="1">
## Volební program

- ### Zjednodušíme fungování pomocí technologií

- ### Odstraníme komunikační bariéry

- ### Pohlídáme toky městských financí

- ### Zatraktivníme město pro všechny

### [více v sekci volby ...](/volby/)

</div>

<hr />

<section id="akce" class="mt-3 dark" style="background: #eee;">
  <h2>nejbližší akce</h2>

  {% for item in site.data.akce limit:3 %}
  {% include shared/eventsummary.html item=item %}
  {% endfor %}

</section>

<hr />

<div markdown="1">

## sleduj nás
- <i class="fab fa-facebook"></i> [Piráti Tábor na facebooku]({{ site.facebookurl }})
- <i class="fab fa-youtube"></i> [Piráti Tábor na youtube]({{ site.data.links.sidebar.youtube.channel }})

</div>

  </div>

</div>
