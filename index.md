---
layout: default
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: organizace,transparence,politika
---

<div class="callout">
  <div class="container">
    <div class="row">
      <div class="col-sm-4 offset-lg-8" id="calltext">
        <h1>JSME <br />PIRÁTI TÁBOR</h1>
        <h2>A máme <br />odvahu dělat věci správně</h2>
        <p><a class="btn btn-primary btn-lg" href="/program/" role="button">
          Chci vědět víc &raquo;</a>
        </p>
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
      <!--
      <section id="kraj" class="pb-3">
        <a href="https://jihocesky.pirati.cz/volby/" target="_blank">
          <img src="/static/media/300x900.jpg"
            alt="jde o kraj - banner s odkazem na krajské volby" />
        </a>
      </section>
      -->

      <div markdown="1">
## Komunální politika

### <i class="fas fa-users"></i> [zastupitelský klub](/zastupitele/)

### <i class="fas fa-book"></i>&nbsp;&nbsp; [komunální program](/program/)

</div>

<hr />


{% assign eventz = site.data.akce | where:"published","true" %}

<section id="akce" class="mt-3 dark">
  <h2>nejbližší akce</h2>

  {% for item in eventz limit:3 %}
  {% include shared/eventsummary.html item=item %}
  {% endfor %}

</section>

<hr />

<div markdown="1">

## sleduj nás
- <i class="fab fa-facebook"></i> [Piráti Tábor na facebooku]({{ site.facebookurl }})
- <i class="fab fa-youtube"></i> [Piráti Tábor na youtube]({{ site.data.links.sidebar.youtube.channel }})
- <i class="fas fa-angle-up"></i> <a href="https://jihocesky.pirati.cz" target="_blank"><b>Krajská</b> organizace (JČK)</a>
- <i class="fas fa-angle-up"></i> <a href="https://www.pirati.cz" target="_blank"><b>Piráti</b> celostát</a>
</div>

  </div>

</div>
