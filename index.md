---
layout: home
title: Home
landing-title: Hola, estos son algúnos de mis trabajos
description: En esta web podrás ver algunos de mis trabajos como desarrollador (y algunos offtopic que me gustan)
image: https://s.gravatar.com/avatar/6a886422955cee09542d1048ca16abca?s=800
author: Emanuel Farfaro Ruiz
nav-menu:
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="https://about.me/manufarfaro" class="button next scrolly">Acerca de Mi</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Un poco acerca de mi...</h2>
		</header>
		<p>
		Fanático de la Música, las artes marciales, y por aprender nuevas tecnologías. Loco por la ciencia,
me encanta estudiar y mi materia favoríta hasta ahora fué álgebra. Tanto en mi profesión como en mis otras actividades me consideran un Nerd innato. Me encanta viajar y el Software Libre.Mi S.O. para todo es Linux.
		</p>
		<ul class="actions">
			<li><a href="{{ site.aboutme_url }}" class="button next">Acerca de mi</a></li>
		</ul>
	</div>
</section>

</div>
