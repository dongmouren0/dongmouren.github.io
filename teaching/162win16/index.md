---
layout: teaching
title: Math 162 (Winter 2016)
---


# {{ page.title }}

### Recent announcements
{% for post in site.categories.162win16 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>'}}
{% endfor %}
Older announcements are [here](#older-announcements). Course materials are [here](#course-materials).

----

### Course information

<div class="infotable">

| ------:         | :-----                                                                                                                                                                                                                                                                                                    |
| Time/place:     | TuTh 11:30am to 12:20pm in [Ryerson][ry] 358                                                                                                                                                                                                                                                              |
| Instructors:    | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`), office hours Tu 17:00--18:00, Th 9:00--10:00 and by appointment in [Eckhart][eck] 2A<br/>Matthew Creek (`mcreek` at `math` dot `uchicago` dot `edu`), office hours Tu 9:00--10:00, W 16:00--17:00, and by appointment in [Eckhart][eck] 306 |
| College fellow: | Anthony Wang (`ayw` at `uchicago` dot `edu`), office hours M 16:00--17:00, F 16:00--17:00, and by appointment in [Woodlawn][wood] 5E, problem session M 18:00--19:00 in [Ryerson][ry] 358                                                                                                                                           |


[eck]: https://maps.uchicago.edu/?location=Eckhart+Hall
[wood]: https://maps.uchicago.edu/?location=5720+South+Woodlawn+Avenue
[ry]: https://maps.uchicago.edu/?location=Ryerson+Laboratory

</div>

### Class plan

<div class="classplan">

| Date  | Topic                                                  | Preparation Assignment                                                          | Homework Assignment | Additional Information |
| :---  | :---                                                   | :---                                                                            | :---                | :---                   |
| 01/05 | Compactness                                            | Script #4, up to and including Theorem 4.26                                     |                     |                        |
| 01/07 | Compactness, Heine-Borel                               | Script #4, up to and including Theorem 4.36 (through the end)                   |                     |                        |
| 01/12 | Heine-Borel, Bolzano-Weierstrass, Continuous functions | Script #4 (through the end) and Script #5, up to and including Proposition 5.11 |                     |                        |
| 01/14 |                                                        |                                                                                 |                     |                        |
| 01/19 |                                                        |                                                                                 |                     |                        |
| 01/21 |                                                        |                                                                                 |                     |                        |
| 01/26 |                                                        |                                                                                 |                     |                        |
| 01/28 |                                                        |                                                                                 |                     |                        |
| 02/02 |                                                        |                                                                                 |                     |                        |
| 02/04 |                                                        |                                                                                 |                     |                        |
| 02/09 |                                                        |                                                                                 |                     |                        |
| 02/11 |                                                        |                                                                                 |                     |                        |
| 02/16 |                                                        |                                                                                 |                     |                        |
| 02/18 |                                                        |                                                                                 |                     |                        |
| 02/23 |                                                        |                                                                                 |                     |                        |
| 02/25 |                                                        |                                                                                 |                     |                        |
| 03/01 |                                                        |                                                                                 |                     |                        |
| 03/03 |                                                        |                                                                                 |                     |                        |
| 03/08 |                                                        |                                                                                 |                     |                        |
| 03/10 | **Reading period**                                     |                                                                                 |                     |                        |
| 03/15 |                                                        |                                                                                 |                     |                        |
| 03/17 | **Written final examination**                          |                                                                                 |                     |                        |

</div>

### Course materials

* [Course information sheet](documents/courseinfosheet.pdf)
* [IBL primer](documents/ibl.pdf)
* [Script #0](scripts/script_0_161.pdf) ([source code](scripts/script_0_161.tex))
* [Script #1](scripts/script_1_161.pdf) ([source code](scripts/script_1_161.tex))
* [Script #2](scripts/script_2_161.pdf) ([source code](scripts/script_2_161.tex))
* [Script #3 original](scripts/script_3_161_original.pdf) ([source code](scripts/script_3_161_original.tex))
* [Script #3 updated](scripts/script_3_161_updated.pdf) ([source code](scripts/script_3_161_updated.tex))
* [Script #4](scripts/script_4_161.pdf) ([source code](scripts/script_4_161.tex))
* [Script #5](scripts/script_5_161.pdf) ([source code](scripts/script_5_161.tex))

----
### Older announcements
{% for post in site.categories.162win16 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
