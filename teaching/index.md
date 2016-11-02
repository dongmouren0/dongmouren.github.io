---
layout: default
title: Teaching
navigation_weight: 3
---

## {{ page.title }}

### University of Georgia
{% assign uga = site.data.teaching | where: "location", "University of Georgia" | sort: 'date' | reverse %}
<ul>
{% for class in uga %}
<li>
<strong>{{ class.display-date }}:</strong>
{{ class.description }}
</li>
{% endfor %}
</ul>

### University of Chicago
{% assign uchicago = site.data.teaching | where: "location", "University of Chicago" | sort: 'date' | reverse %}
<ul>
{% for class in uchicago %}
<li>
<strong>{{ class.display-date | markdownify | strip | remove: '<p>' | remove: '</p>' }}:</strong>
{{ class.description | markdownify | strip | remove: '<p>' | remove: '</p>' }}
</li>
{% endfor %}
</ul>

### Canada/USA Mathcamp
{% assign mathcamp = site.data.teaching | where: "location", "Canada/USA Mathcamp" | sort: 'date' | reverse %}
<ul>
{% for class in mathcamp %}
<li>
<strong>{{ class.display-date | markdownify | strip | remove: '<p>' | remove: '</p>' }}:</strong>
{{ class.description | markdownify | strip | remove: '<p>' | remove: '</p>' }}
{{ class.comment | markdownify | strip | remove: '<p>' | remove: '</p>' }}
</li>
{% endfor %}
</ul>
