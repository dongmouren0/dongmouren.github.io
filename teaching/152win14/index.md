---
layout: default
title: Math 152 (Winter 2014)
---

# {{ page.title }}

### Recent announcements
{% for post in site.categories.152win14 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html}}
{% endfor %}
Older announcements are [here](#older-announcements).

----

### Course information
<div class="infotable">

| ---------------:     | :-----------------------------------------------------------                                                       |
| Time/place:          | Tuesday/Thursday, 10:30am to 11:50am in SS 108                                                                     |
| Instructor:          | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`)                                                       |
| Office hours:        | Mondays 11:30am--12:30pm, Wednesdays 6pm--7pm and by appointment on Tuesdays 5pm--6pm or Thursdays 12:30pm--1:30pm |
| Problem session:     | Tuesdays 6pm to 7pm in Ry 358                                                                                      |
| VCA:                 | Mike Fosco (`mfosco` at `uchicago` dot `edu`)                                                                      |
| Mike's office hours: | Wednesdays 3:30pm--4:30pm in Harper Cafe                                                                           |

</div>

Additionally, please read the [Course Information Sheet](courseinformationsheet.pdf) carefully.

### Syllabus
The class plan is tentative and will be updated as the quarter goes by. You will get more out of each class if you read the relevant sections of the textbook beforehand.
<div class="classplan">

| Date  | Topic                                             | Section         | Homework/Documents      |
| :---- | :-----------------------------                    | :---------      | :-------------------    |
| 01/07 | Review, asymptotes, cusps                         | 4.7             |                         |
| 01/09 | Curve sketching, related rates, Newton-Raphson    | 4.8, 4.10, 4.12 |                         |
| 01/14 | Definite integrals                                | 5.2             |                         |
| 01/16 | Definite integrals, antiderivatives               | 5.2, 5.3        | **[HW 1](#hw-1) due**   |
| 01/21 | Antiderivatives, fundamental theorem of calculus  | 5.3, 5.4        |                         |
| 01/23 | Fundamental theorem, some area calculations       | 5.4, 5.5        | **[HW 2](#hw-2) due**   |
| 01/28 | Indefinite integrals, techniques of integration   | 5.6, 5.7        |                         |
| 01/30 | **Midterm 1**                                     |                 | [Practice problems][p1] |
| 02/04 | Techniques of integration, properties of integral | 5.7, 5.8        |                         |
| 02/06 | Mean-value theorems for the integral              | 5.9             | **[HW 3](#hw-3) due**   |
| 02/11 | More area computations, volumes                   | 6.1, 6.2        |                         |
| 02/13 | Volumes by cross-section and shells               | 6.2, 6.3        | **[HW 4](#hw-4) due**   |
| 02/18 | Pappus' theorem on volumes, one-one functions     | 6.4, 7.1        |                         |
| 02/20 | **Midterm 2**                                     |                 | [Practice problems][p2] |
| 02/25 | The logarithm function                            | 7.2, 7.3        |                         |
| 02/27 | Log, integrating secant, logarithmic derivatives  | 7.3             | **HW 5 due**            |
| 03/04 | The exponential function, arbitrary powers/bases  | 7.4, 7.5        |                         |
| 03/06 | Arbitrary powers, exponential growth and decay    | 7.5, 7.6        | **HW 6 due**            |
| 03/11 | Exponential growth and decay, Recap               | 7.6             |                         |
| 03/13 | **Reading Period**                                |                 |                         |
| 03/18 | **Final Examination**                             |                 |                         |

[p1]: #midterm-1-practice-problems
[p2]: #midterm-2-practice-problems

</div>

### Homework
Homework will be due _before class_ on the day indicated on the syllabus. Late homework will not be accepted. The lowest percentage homework score will be dropped.

#### HW 1
* **Read:** Sections 4.7 and 4.8, and material from Math 151 as needed.
* **Turn in:** 4.7 (2, 4, 19, 26), 4.8 (8, 9, 55), 4.10 (3, 14, 13, 16), 4.12 (2, 5, 7, 13; you may use a calculator)
* **Practice:** 4.7 (1, 7, 43, 44), 4.10 (18, 22, 37)

#### HW 2
* **Turn in:** 5.2 (3, 6, 10, 12, 16, 25, 26), 5.3 (2, 4, 6, 7, 8, 17, 18, 20)

#### Midterm 1 Practice Problems

* Read all sections of the syllabus from the textbook and go over homework before you attempt the practice problems.
* 4.7 (4, 6, 25, 27), 4.8 (11, 18, 33, 34, 56), 4.10 (1, 5, 10, 19, 28), 4.12 (13, 14, 15, 17)
* 5.2 (5, 7, 8, 11, 17, 18, 24), 5.3 (1, 3, 13, 22, 24), 5.4 (practice integrating lots of different expressions), 5.5 (practice computing lots of different areas)

#### HW 3
* **Turn in:** 5.4 (62), 5.5 (3, 28, ~~40~~), 5.6 (3, 8, 36, 50), 5.7 (6, 20, 31, 35, 68, 71, 78)
* **Practice:** 5.4 (7, 9, 11, 54), 5.7 (10, 23, 30, 67, 83)

#### HW 4
* **Turn in:** 5.8 (16, 17, 24, 28, 35, 36), 5.9 (2, 9, 14, 18, 22, 25), 6.1 (16, 20, 28)
* **Practice:** 5.8 (7--15, 32), 5.9 (6, 13, 16, 26, 29), 6.1 (3, 7, 27, 29, 33)

#### Midterm 2 Practice Problems
* Read all the sections from the textbook first.
* 5.6 (15, 25, 27, 35, 40, 53), 5.7 (7, 38, 39, 56, 85), 5.8 (1--6, 19, 20, 32, 38), 5.9 (3, 8, 13, 19, 25, 31, 34)
* 6.1 (2, 15, 21, 29, 37), 6.2 (9, 11, 27, 30, 33, 37, 42), 6.3 (1, 16, 24, 25, 33, 34)

----
### Older announcements
{% for post in site.categories.152win14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}

