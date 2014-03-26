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

| ---------------:     | :----------------------------------------------------------- |
| Time/place:          | Tuesday/Thursday, 10:30am to 11:50am in SS 108               |
| Instructor:          | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`) |
| Office hours:        | TBD                                                          |
| Problem session:     | TBD                                                          |
| VCA:                 | Mike Fosco (`mfosco` at `uchicago` dot `edu`)                |
| Mike's office hours: | TBD                                                          |

</div>

Additionally, please read the [Course Information Sheet](courseinformationsheet.pdf) carefully.

### Syllabus
The class plan is tentative and will be updated as the quarter goes by. You will get more out of each class if you read the relevant sections of the textbook beforehand.

<div class="classplan">

| Date  | Topic                 | Section | Homework/Documents |
| :---  | :---                  | :---    | :---               |
| 04/01 |                       |         |                    |
| 04/03 |                       |         |                    |
| 04/08 |                       |         |                    |
| 04/10 |                       |         |                    |
| 04/15 |                       |         |                    |
| 04/17 | **Quiz 1**            |         |                    |
| 04/22 |                       |         |                    |
| 04/24 |                       |         |                    |
| 04/29 |                       |         |                    |
| 05/01 |                       |         |                    |
| 05/06 | **Quiz 2**            |         |                    |
| 05/08 |                       |         |                    |
| 05/13 |                       |         |                    |
| 05/15 |                       |         |                    |
| 05/20 |                       |         |                    |
| 05/22 | **Quiz 3**            |         |                    |
| 05/27 |                       |         |                    |
| 05/29 |                       |         |                    |
| 06/03 |                       |         |                    |
| 06/05 | **Reading Period**    |         |                    |
| 06/12 | **Final Examination** |         |                    |


</div>

----
### Older announcements
{% for post in site.categories.153spr14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}



