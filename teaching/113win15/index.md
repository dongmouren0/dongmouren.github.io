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

| Date  | Topic                                    | Section    | Homework              |
| :---  | :---                                     | :---       | :---                  |
| 01/05 | Introduction to Geometry                 | 9          |                       |
| 01/07 | Symmetry group (equilateral triangle)    | 11.1       |                       |
| 01/09 | Symmetry group (triangle and square)     | 11.1,11.2  | **[HW 1](#hw-1) due** |
| 01/12 | Impossible motions, symmetries of n-gons | 11.2,11.3  |                       |
| 01/14 | Groups and permutations                  | 12.1       |                       |
| 01/16 | Permutations                             | 12.1, 12.2 |                       |
| 01/19 | **Martin Luther King, Jr. Day**          |            |                       |
| 01/21 | Symmetric group                          | 12.2, 12.3 |                       |
| 01/23 |                                          |            |                       |
| 01/26 |                                          |            |                       |
| 01/28 |                                          |            |                       |
| 01/30 | **Midterm 1**                            |            |                       |
| 02/02 |                                          |            |                       |
| 02/04 |                                          |            |                       |
| 02/06 |                                          |            |                       |
| 02/09 |                                          |            |                       |
| 02/11 |                                          |            |                       |
| 02/13 | **College break**                        |            |                       |
| 02/16 |                                          |            |                       |
| 02/18 |                                          |            |                       |
| 02/20 |                                          |            |                       |
| 02/23 |                                          |            |                       |
| 02/25 |                                          |            |                       |
| 02/27 | **Midterm 2**                            |            |                       |
| 03/02 |                                          |            |                       |
| 03/04 |                                          |            |                       |
| 03/06 |                                          |            |                       |
| 03/09 |                                          |            |                       |
| 03/11 |                                          |            |                       |
| 03/13 | **Reading Period**                       |            |                       |

</div>

### Homeworks

#### HW 1
1. Draw a tiling of the plane that has only translational symmetry.
1. Draw a tiling of the plane that has only translational and rotational symmetry.
1. How many different symmetries does the following "bow-tie" shape (&#x22c8;) have? Write out its multiplication table.
1. Exercise 11.1.

----
### Older announcements
{% for post in site.categories.113win15 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
