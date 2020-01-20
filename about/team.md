---
title: The conference team
layout: multisection
---


<section class="team-list">
	<h2>Organizing Committee</h2>
	<ul >
	{% for member in site.data.team.conferenceteam %}
	<li>
		<div style="background-image: url(../assets/images/team/{{member.image | default: 'owasp_logo.png'}})" alt="{{member.name}} {{member.role}}"></div>
		<h4>{{member.name}}</h4>
		<span class="role">{{member.role}}</span>
	</li>
	{% endfor %}
	</ul>
	
	<h2>Chapters</h2>
	AppSec California is made possible by many more unlisted planners in the organization commitee. Here's the chapters involved.
	<ul>
	<li>
		<div style="background-image: url(../assets/images/owaspla.jpg)" alt=""></div>
		<h4>Los Angeles</h4>
		<span class="role">Chapter</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/owasp_logo_r_icon.png)" alt=""></div>
		<h4>Santa-Barbara</h4>
		<span class="role">Chapter</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/OWASP_OC_v2b_notext.png)" alt=""></div>
		<h4>Orange County</h4>
		<span class="role">Chapter</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/owasp_logo_r_icon.png)" alt=""></div>
		<h4>San Diego</h4>
		<span class="role">Chapter</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/bayarea.png)" alt=""></div>
		<h4>Bay Area</h4>
		<span class="role">Chapter</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/owasp_logo_r_icon.png)" alt=""></div>
		<h4>Inland Empire</h4>
		<span class="role">Chapter</span>
	</li>
	<li>
		<div style="background-image: url(../assets/images/San-Fernando-Valley.jpg)" alt=""></div>
		<h4>San Fernando Valley</h4>
		<span class="role">Chapter</span>
	</li>
	</ul>
</section>

