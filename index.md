---
layout: page
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: piráti, tábor, organizace, transparentnost, politika
---


<section class="hero alert-box secondary">
	<div class="row">
		<div class="small-8 columns">
			<p>
				Není ti lhostejné veřejné dění v Táboře?<br/>
				Je ti blízký pirátský program / ideje?<br/>
				Máš kuráž a taky chceš transparentnější a modernější radnici?<br/>
				Tak buď táborský pirát!
			</p>

			<a href="/lide/" class="primary button test">Ozvi se nám →</a>

		</div>

		<div class="small-4 columns">
			<img src="/static/budpirat-small.png" alt="buď pirát - ucle sam grafika" />
		</div>
	</div>
</section>


## Aktuality <i class="fa fa-newspaper-o"></i>

{% for post in site.posts limit:20 %}  
{% include articlesumary.html %}
{% endfor %}  
