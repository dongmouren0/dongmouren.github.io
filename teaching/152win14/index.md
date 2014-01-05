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

| ---------------:     | :----------------------------------------------------------- |
| Time/place:          | Tuesday/Thursday, 10:30am to 11:50am in SS 108               |
| Instructor:          | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`) |
| Office hours:        | TBA                                                          |
| Problem session:     | TBA                                                          |
| VCA:                 | Mike Fosco (`mfosco` at `uchicago` dot `edu`)                |
| Mike's office hours: | TBA                                                          |

</div>

Additionally, please read the [Course Information Sheet](courseinformationsheet.pdf) carefully.

### Syllabus
The class plan is tentative and will be updated as the quarter goes by. You will get more out of each class if you read the relevant sections of the textbook beforehand.
<div class="classplan">

| Date  | Topic                          | Section    | Homework/Documents   |
| :---- | :----------------------------- | :--------- | :------------------- |
| 01/07 | Review                         |            |                      |

</div>

### Homework
Homework will be due _before class_ on the day indicated on the syllabus. Late homework will not be accepted. The lowest percentage homework score will be dropped.

----
### Older announcements
{% for post in site.categories.152win14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}

