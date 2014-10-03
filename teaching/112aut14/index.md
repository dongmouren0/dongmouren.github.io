---
layout: default
title: Math 112 (Autumn 2014)
---

# {{ page.title }}

### Recent announcements
{% for post in site.categories.112aut14 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>'}}
{% endfor %}
Older announcements are [here](#older-announcements). Homeworks are [here](#homeworks).

----

### Course information

<div class="infotable">

| ------:             | :-----                                                                  |
| Time/place:         | MWF 11:30am to 12:20pm in Eck 203                                       |
| Instructor:         | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`)            |
| Office:             | [Math-Stat 015](https://maps.uchicago.edu/?location=Math-Stat+Building) |
| Office hours:       | TBA                                                                     |
| Abigail's tutorial: | TR 12:00pm to 1:20pm in HGS 108 (`ashearrow` at `uchicago` dot `edu`)   |
| Victor's tutorial:  | TR 3:00pm to 4:20pm in E 207 (`zhangvict` at `uchicago` dot `edu`)      |
| Sasha's tutorial:   | TR 4:30pm to 5:50pm in C 203 (`sayvazov` at `uchicago` dot `edu`)       |

</div>

### Syllabus
The class plan is tentative and will be filled in as the quarter goes by. 

<div class="classplan">

| Date  | Topic                                   |  Section | Homework/Documents    |
| :---  | :---                                    |     :--- | :---                  |
| 09/29 | Introduction and the triangle game      |        0 |                       |
| 10/01 | Triangle game, numbers, sets, functions |      1.1 |                       |
| 10/03 | Numbers, sets, functions                |      1.1 | **[HW 1](#hw-1) due** |
| 10/06 | Rules of arithmetic                     |      1.2 |                       |
| 10/08 | Rules of arithmetic                     | 1.2, 1.3 |                       |
| 10/10 | One's digit arithmetic                  |      1.4 |                       |
| 10/13 |                                         |          |                       |
| 10/15 |                                         |          |                       |
| 10/17 |                                         |          |                       |
| 10/20 |                                         |          |                       |
| 10/22 |                                         |          |                       |
| 10/24 | **Midterm 1**                           |          |                       |
| 10/27 |                                         |          |                       |
| 10/29 |                                         |          |                       |
| 10/31 |                                         |          |                       |
| 11/03 |                                         |          |                       |
| 11/05 |                                         |          |                       |
| 11/07 |                                         |          |                       |
| 11/10 |                                         |          |                       |
| 11/12 |                                         |          |                       |
| 11/14 | **Midterm 2**                           |          |                       |
| 11/17 |                                         |          |                       |
| 11/19 |                                         |          |                       |
| 11/21 |                                         |          |                       |
| 11/24 |                                         |          |                       |
| 11/26 |                                         |          |                       |
| 11/28 | **Thanksgiving vacation**               |          |                       |
| 12/01 |                                         |          |                       |
| 12/03 |                                         |          |                       |
| 12/05 | **Reading Period**                      |          |                       |
| 12/08 | **Final Examination**                   |          |                       |

</div>

### Homeworks
Problems marked as "Tutorial" will typically be discussed in tutorial, and are not to be handed in.

#### HW 1
1. Exercise 0.1
1. Exercise 1.4
1. Exercise 1.5
1. Exercise 1.9
1. Can you completely cover a $5\times 5$ chessboard with non-overlapping $1\times 2$ dominoes? Explain why or why not.
1. (Tutorial) Exercise 0.13
1. (Tutorial) Exercise 1.11

----
### Older announcements
{% for post in site.categories.112aut14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
