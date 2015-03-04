---
layout: page
section: blog
description: Výhozí stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: piráti, tábor, organizace, transparence, politika
---


<section class="hero">
	<div class="row">
		<div class="small-12 columns">

			<div data-alert class="alert-box secondary">
				<p>
					Není ti lhostejné veřejné dění?
					Je ti blízký pirátský program?
					A chceš pomoct pirátům v Táboře?
				</p>

				<div>
					<a href="/lide/" class="primary button test">Kontaktuj nás →</a>
				</div>
			</div>

		</div>
	</div>
</section>


## Aktuality <i class="fa fa-newspaper-o"></i>

{% for post in site.posts limit:20 %}  
{% include articlesumary.html %}
{% endfor %}  
