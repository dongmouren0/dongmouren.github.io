---
layout: default
title: Home
navigation_weight: 1
---

<div class="intro">

![Asilata Bapat](assets/asilata-bapat.jpg){:#mypicture}

<div>

[Mathematical Sciences Institute](http://maths.anu.edu.au/)  
The Australian National University  
Canberra, ACT, 2601, Australia


**Email:** `asilata.bapat` at `anu` dot `edu` dot `au`  
**Office:** [John Dedman](http://www.anu.edu.au/maps#show=28977) 2145  
**Phone:** +61 2 6125 4141

</div>

</div>

### Research interests and background

My research focuses on problems in representation theory and algebraic geometry. 
I am most interested in the topology and geometry of algebraic varieties arising from representation theory.
Specific topics of interest include perverse sheaves, quiver varieties, equivariant cohomology, and Bernstein--Sato polynomials.
My papers and preprints are on my [research page](/research), and my CV is available [here](assets/bapat-cv.pdf).

I completed my PhD at the [University of Chicago](http://math.uchicago.edu/) in June 2016 under the supervision of Victor Ginzburg.
I was an undergraduate at [MIT](http://web.mit.edu).

### Teaching
Older teaching is listed on my [teaching page](teaching/).

### Current and upcoming activities

{% capture currenttime %}{{ site.time }}{% endcapture %}
{% assign activities = site.data.activities | where_exp: "activity", "activity.date > currenttime" | sort: 'date' %}
<ul>
{% for activity in activities %}
<li>
{% unless activity.current == true %}
<strong>{% if activity.display-date %}{{ activity.display-date | markdownify | strip | remove: '<p>' | remove: '</p>' }}{% else %}{{ activity.date | date: "%b %Y" }}{% endif %}:</strong>
{% endunless %}
{{ activity.content | markdownify | strip | remove: '<p>' | remove: '</p>'}}{% if activity.location %}, {{ activity.location | remove: '<p>' | remove: '</p>'}}{% endif %}
</li>
{% endfor %}
</ul>

Older activities are listed on my [activities page](activities/).

