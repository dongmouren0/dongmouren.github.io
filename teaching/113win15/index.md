---
layout: default
title: Math 113 (Winter 2015)
---


# {{ page.title }}

### Recent announcements
{% for post in site.categories.113win15 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>'}}
{% endfor %}
Older announcements are [here](#older-announcements). Homeworks are [here](#homeworks).

----

### Course information

<div class="infotable">

| ------:       | :-----                                                       |
| Time/place:   | MWF 11:30am to 12:20pm in Eck 203                            |
| Instructor:   | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`) |
| Office hours: | TBA                                                          |
| Tutorials:    | TBA                                                          |

[ms]: https://maps.uchicago.edu/?location=Math-Stat+Building

</div>

### Syllabus
The class plan is tentative and will be filled in as the quarter goes by. 

<div class="classplan">

| Date  | Topic                           | Section | Homework/Documents |
| :---  | :---                            | :---    | :---               |
| 01/05 |                                 |         |                    |
| 01/07 |                                 |         |                    |
| 01/09 |                                 |         |                    |
| 01/12 |                                 |         |                    |
| 01/14 |                                 |         |                    |
| 01/16 |                                 |         |                    |
| 01/19 | **Martin Luther King, Jr. Day** |         |                    |
| 01/21 |                                 |         |                    |
| 01/23 |                                 |         |                    |

</div>

### Homeworks

----
### Older announcements
{% for post in site.categories.113win15 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
