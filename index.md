---
layout: page
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: piráti, tábor, organizace, transparentnost, politika
---


<section class="hero callout large primary">
	<div class="row">
		<div class="small-8 columns">
			<ul>
				<li>Není ti lhostejné veřejné dění v Táboře?</li>
				<li>Máš kuráž a taky chceš transparentnější a modernější radnici?</li>
				<li>Je ti blízký pirátský program / ideje?</li>
			</ul>

			<h3>
				<a href="mailto:vaclav.klecanda@pirati.cz" class="primary">Ozvi se →</a> a buď táborský pirát!
			</h3>

		</div>

		<div class="small-4 columns">
			<img src="/static/budpirat-small.png" alt="buď pirát - ucle sam grafika" title="buď pirát" />
		</div>
	</div>
</section>


## Vybrané články <i class="fi-page-multiple"></i>

{% for post in site.posts limit:20 %}  
{% include articlesumary.html %}
{% endfor %}  
