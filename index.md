---
layout: default
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: organizace,transparence,politika
---

<section class="callout">
	<div class="row">
		<div class="small-12 faded medium-8 columns">
			<h1>JSME <b>PIRÁTI TÁBOR</b></h1>
      <h2 class="subheader">A POMÁHÁME NAŠEMU MĚSTU</h2>
      <p>
      Naším cílem je obec, kde může každý člověk prožít svůj život svobodně a naplno. Klíčem k prosperitě naší společnosti je otevřenost, kvalitní vzdělání a veřejné služby, použití nových technologií a zapojení občanů do rozhodování.
      </p>
		</div>
	</div>
</section>

<div class="row">
  <section class="small-12 medium-6 columns">
  {% for post in site.posts limit:2 %}
    <div class="column">
    {% include shared/articlesumary.html %}
    </div>
  {% endfor %}
    <h3><a href="/clanky/">Ostatní články ...</a></h3>
  </section>

  <section id="program" class="small-12 medium-6 columns">
    <h3><a href="/program/">Komunální program</a></h3>
    {% capture my_include %}{% include program/list.md %}{% endcapture %}
    {{ my_include | markdownify }}

    <h3><a href="/program/">PODROBNÝ PROGRAM ...</a></h3>
  </section>
