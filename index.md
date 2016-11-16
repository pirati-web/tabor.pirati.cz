---
layout: page
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: piráti, tábor, organizace, transparentnost, politika
---

<section class="callout large">
	<div class="row">
		<div class="small-12 faded medium-8 columns">
			<h1>Piráti Tábor</h1>
      <h2 class="subheader">táborská politika očima pirátů</h2>
			<ul>
				<li>není ti lhostejné veřejné dění v Táboře?</li>
				<li>máš kuráž a taky chceš transparentnější a modernější radnici?</li>
				<li>je ti blízký pirátský program / ideje?</li>
			</ul>

			<h3>
				<a href="mailto:vaclav.klecanda@pirati.cz" class="primary">ozvi se →</a> a buď táborský pirát!
			</h3>

		</div>
	</div>
</section>


## Vybrané články <i class="fi-page-multiple"></i>

{% for post in site.posts limit:20 %}  
{% include articlesumary.html %}
{% endfor %}  
