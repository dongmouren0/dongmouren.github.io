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

| Date  | Topic                                             | Section         | Homework/Documents    |
| :---- | :-----------------------------                    | :---------      | :-------------------  |
| 01/07 | Review, asymptotes, cusps                         | 4.7             |                       |
| 01/09 | Curve sketching, related rates, Newton-Raphson    | 4.8, 4.10, 4.12 |                       |
| 01/14 | Definite integrals                                | 5.2             |                       |
| 01/16 | Definite integrals, antiderivatives               | 5.2, 5.3        | **[HW 1](#hw-1) due** |
| 01/21 | Antiderivatives, fundamental theorem of calculus  | 5.3, 5.4        |                       |
| 01/23 | Fundamental theorem, some area calculations       | 5.4, 5.5        | **HW 2 due**          |
| 01/28 | Indefinite integrals, techniques of integration   | 5.6, 5.7        |                       |
| 01/30 | **Midterm 1**                                     |                 |                       |
| 02/04 | Techniques of integration, properties of integral | 5.7, 5.8        | **HW 3 due**          |
| 02/06 | Mean-value theorems for the integral              | 5.9             | **HW 4 due**          |
| 02/11 | More area computations, volumes                   | 6.1, 6.2        |                       |
| 02/13 | Volumes by cross-section and shells               | 6.2, 6.3        | **HW 5 due**          |
| 02/18 | Pappus' theorem on volumes, one-one functions     | 6.4, 7.1        |                       |
| 02/20 | **Midterm 2**                                     |                 |                       |
| 02/25 | The logarithm function                            | 7.2, 7.3        | **HW 6 due**          |
| 02/27 | Log, integrating secant, logarithmic derivatives  | 7.3             | **HW 7 due**          |
| 03/04 | The exponential function, arbitrary powers/bases  | 7.4, 7.5        |                       |
| 03/06 | Arbitrary powers, exponential growth and decay    | 7.5, 7.6        | **HW 8 due**          |
| 03/11 | Exponential growth and decay, Recap               | 7.6             |                       |
| 03/13 | **Reading Period**                                |                 |                       |
| 03/18 | **Final Examination**                             |                 |                       |

</div>

### Homework
Homework will be due _before class_ on the day indicated on the syllabus. Late homework will not be accepted. The lowest percentage homework score will be dropped.

#### HW 1
* **Read:** Sections 4.7 and 4.8, and material from Math 151 as needed.
* **Turn in:** 4.7 (2, 4, 19, 26), 4.8 (8, 9, 55), 4.10 (3, 14, 13, 16), 4.12 (2, 5, 7, 13; you may use a calculator)
* **Practice:** 4.7 (1, 7, 43, 44), 4.10 (18, 22, 37)

----
### Older announcements
{% for post in site.categories.152win14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}

