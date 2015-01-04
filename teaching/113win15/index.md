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
| Time/place:   | MWF 11:30am to 12:20pm in Kent 106                           |
| Instructor:   | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`) |
| Office hours: | TBA                                                          |
| Tutorials:    | TBA                                                          |

[ms]: https://maps.uchicago.edu/?location=Math-Stat+Building

</div>

### Syllabus
The class plan is tentative and will be filled in as the quarter goes by. 

<div class="classplan">

| Date  | Topic                                    |    Section | Homework |
| :---  | :---                                     |       :--- | :---     |
| 01/05 | Introduction to Geometry                 |          9 |          |
| 01/07 | Polygons, regular polygons               |       10.1 |          |
| 01/09 | Ruler-compass constructions              |       10.2 |          |
| 01/12 | Ruler-compass constructions              |       10.2 |          |
| 01/14 | Symmetry group (equilateral triangle)    |       11.1 |          |
| 01/16 | Symmtrey group (triangle and square)     | 11.1, 11.2 |          |
| 01/19 | **Martin Luther King, Jr. Day**          |            |          |
| 01/21 | Impossible motions, symmetries of n-gons | 11.2, 11.3 |          |
| 01/23 | Groups and permutations                  |       12.1 |          |
| 01/26 | Permutations                             | 12.1, 12.2 |          |
| 01/28 | Symmetric group                          | 12.2, 12.3 |          |
| 01/30 | **Midterm 1**                            |       13.1 |          |
| 02/02 | Regular polyhedra (introduction)         |       13.2 |          |
| 02/04 | Euler's formula                          |       13.3 |          |
| 02/06 | Symmetries of regular polyhedra          |       13.3 |          |
| 02/09 | Symmetries of regular polyhedra          |       13.4 |          |
| 02/11 | Symmetries of regular polyhedra          |       14.1 |          |
| 02/13 | Introduction to graphs                   |            |          |
| 02/16 | **College break**                        |       14.2 |          |
| 02/18 | Graph colorability                       |       14.2 |          |
| 02/20 | Graph colorability                       |            |          |
| 02/23 |                                          |            |          |
| 02/25 |                                          |            |          |
| 02/27 | **Midterm 2**                            |            |          |
| 03/02 |                                          |            |          |
| 03/04 |                                          |            |          |
| 03/06 |                                          |            |          |
| 03/09 |                                          |            |          |
| 03/11 |                                          |            |          |
| 03/13 | **Reading Period**                       |            |          |

</div>

### Homeworks

----
### Older announcements
{% for post in site.categories.113win15 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
