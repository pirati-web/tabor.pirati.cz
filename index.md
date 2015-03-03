---
layout: page
title: Město ?
section: blog
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
					<a href="/lide" class="primary button">Kontaktuj nás →</a>
				</div>
			</div>

		</div>
	</div>
</section>


## Aktuality <i class="fa fa-newspaper-o"></i>

{% for post in site.posts limit:20 %}  
<article>
	<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
	<h6>{{ post.date | date_to_string }}</h6>
	{% if post.splash %}<img src="{{ post.splash }}"/>{% endif %}
	{{ post.excerpt }}
</article>
{% endfor %}  
