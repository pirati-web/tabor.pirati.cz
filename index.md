---
layout: default
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: organizace,transparence,politika
---

<section class="callout large">
	<div class="row">
		<div class="small-12 faded medium-8 columns">
			<h1>Piráti Tábor</h1>
      <h2 class="subheader">oficiální web táborské organizace</h2>
		</div>
	</div>
</section>

<section>
  <div class="row small-up-1 medium-up-2">
  {% for post in site.posts limit:2 %}
    <div class="column">
    {% include shared/articlesumary.html %}
    </div>
  {% endfor %}
  </div>
</section>

<section>
  <div class="row">
    <div class="columns small-12">
      <h3><a href="/clanky/">Ostatní články ...</a></h3>
    </div>
  </div>
</section>
