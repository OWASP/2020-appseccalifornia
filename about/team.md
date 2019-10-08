---
title: The conference team
layout: multisection
---


<section class="team-list">
	<h2>Organizing Committee</h2>
	<ul >
	{% for member in site.data.team.conferenceteam %}
	<li>
	<div style="background-image: url(../assets/images/team/richard.jpg)" alt="Richard Greenberg"></div>
 <h4>Richard Greenberg</h4>
 <span class="role">Co-Chair of AppSec California</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/team/{{member.image | default: 'owasp_logo.png'}})" alt="{{member.name}} {{member.role}}"></div>
		<h4>{{member.name}}</h4>
		<span class="role">{{member.role}}</span>
	</li>
	{% endfor %}
	</ul>
</section>

