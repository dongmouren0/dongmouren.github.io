---
layout: default
title: Math 153 (Spring 2014)
---

# {{ page.title }}

### Recent announcements
{% for post in site.categories.153spr14 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html}}
{% endfor %}
Older announcements are [here](#older-announcements).

----

### Course information
<div class="infotable">

| ---------------:     | :-----------------------------------------------------------                                                   |
| Time/place:          | Tuesday/Thursday, 10:30am to 11:50am in SS 108                                                                 |
| Instructor:          | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`)                                                   |
| Office hours:        | Mondays 12:30pm--1:30pm, Wednesdays 4pm--5pm and by appointment on Tuesdays 5pm--6pm or Fridays 4:30pm--5:30pm |
| Problem session:     | Tuesdays 6pm--7pm in Eck 308                                                                                   |
| VCA:                 | Mike Fosco (`mfosco` at `uchicago` dot `edu`)                                                                  |
| Mike's office hours: | TBD                                                                                                            |

</div>

Additionally, please read the [Course Information Sheet](courseinformationsheet.pdf) carefully.

### Syllabus
The class plan is tentative and will be updated as the quarter goes by. You will get more out of each class if you read the relevant sections of the textbook beforehand.

<div class="classplan">

| Date  | Topic                                                   | Section       | Homework/Documents    |
| :---  | :---                                                    | :---          | :---                  |
| 04/01 | Inverse trig functions, hyperbolic sine and cosine      | 7.7, 7.8      |                       |
| 04/03 | Integration by parts, powers/products of trig functions | 8.2, 8.3      |                       |
| 04/08 | Integration techniques, partial fractions               | 8.3, 8.4, 8.5 |                       |
| 04/10 | Integration techniques, partial fractions               | 8.4, 8.5      | **[HW 1](#hw-1) due** |
| 04/15 | Some differential equations, catchup                    | 9.1, 9.2      |                       |
| 04/17 | **Quiz 1**                                              |               |                       |
| 04/22 | The least-upper-bound principle, sequences, examples    | 11.1, 11.2    |                       |
| 04/24 | The limit of a sequence, examples                       | 11.3          |                       |
| 04/29 | Some important limits                                   | 11.3, 11.4    |                       |
| 05/01 | Indeterminate forms                                     | 11.5, 11.6    |                       |
| 05/06 | **Quiz 2**                                              |               |                       |
| 05/08 | Improper integrals                                      | 11.7          |                       |
| 05/13 | Infinite series: introduction and examples              | 12.1, 12.2    |                       |
| 05/15 | Convergence tests                                       | 12.3, 12.4    |                       |
| 05/20 | Convergence tests, conditional convergence              | 12.4, 12.5    |                       |
| 05/22 | **Quiz 3**                                              |               |                       |
| 05/27 | Taylor polynomials and Taylor series                    | 12.6, 12.7    |                       |
| 05/29 | Taylor series and power series                          | 12.7, 12.8    |                       |
| 06/03 | Differentiation/integration of power series, catchup    | 12.9          |                       |
| 06/05 | **Reading Period**                                      |               |                       |
| 06/12 | **Final Examination**                                   |               |                       |

</div>

### Homeworks

#### HW 1
* 7.7 (1, 9, 14, 22, 26, 35)
* 7.8 (4, 20, 26, 32, 52)
* 8.2 (2, 12, 28, 38, 44)
* 8.3 (5, 6, 27, 35)

----
### Older announcements
{% for post in site.categories.153spr14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}



