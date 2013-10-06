---
layout: default
title: Math 151 (Autumn 2013)
---

# Math 151 (Autumn 2013)

### Recent announcements
{% for post in site.categories.151aut13 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}
Older announcements are [here](#older-announcements).

----

### Course information
<div class="infotable">

| ---------------:     | :-----------------------------------------------------------                                             |
| Time/place:          | Tuesday/Thursday, 10:30am to 11:50am in SS 108                                                           |
| Instructor:          | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`)                                             |
| Office hours:        | Monday 1:30pm to 2:30pm, Wednesday 4pm to 5pm, and any other time by appointment, in [Math/Stat][ms] 015 |
| Problem session:     | Tuesday 6pm to 7pm (tentative) in TBA                                                                    |
| VCA:                 | Mike Fosco (`mfosco` at `uchicago` dot `edu`)                                                            |
| Mike's office hours: | Monday 6:30pm to 7:30pm in Harper cafe                                                                   |

[ms]: http://maps.uchicago.edu/eastquad/statmath.html

</div>

Additionally, please read the Course Information Sheet ([PDF](courseinformationsheet.pdf)) carefully.

### Syllabus
The class plan is tentative and will be updated as the quarter goes by. You will get more out of each class if you read the relevant sections of the textbook beforehand.

<div class="classplan">

| Date  | Topic                                                   | Section       | Homework/Documents    |
| :---- | :-----------------------------                          | :---------    | :-------------------  |
| 10/01 | Review, inequalities                                    | 1.3, 1.6      |                       |
| 10/03 | Review, proofs and induction                            | 1.6, 1.8      | **[HW 0](#hw-0) due** |
| 10/08 | Induction, introduction to limits                       | 1.8, 2.1      |                       |
| 10/10 | Limits: introduction and definitions                    | 2.1, 2.2      | **[HW 1](#hw-1) due** |
| 10/15 | Some limit theorems                                     | 2.3           |                       |
| 10/17 | Limit theorems, pinching theorem                        | 2.3, 2.5      | **HW 2 due**          |
| 10/22 | **Midterm 1**                                           |               |                       |
| 10/24 | Trigonometric limits, continuity                        | 2.5, 2.4      |                       |
| 10/29 | Intermediate and extreme value theorems, the derivative | 2.6, 3.1      | **HW 3 due**          |
| 10/31 | Differentiation formulas, rates of change               | 3.2, 3.3, 3.4 |                       |
| 11/05 | The chain rule, differentiation trigonometric functions | 3.5, 3.6      | **HW 4 due**          |
| 11/07 | Implicit differentiation, rational powers               | 3.7           |                       |
| 11/12 | **Midterm 2**                                           |               |                       |
| 11/14 | Rolle's theorem, mean-value theorem                     | 4.1           | **HW 5 due**          |
| 11/19 | Increasing and decreasing functions                     | 4.2           |                       |
| 11/21 | Extreme values                                          | 4.3, 4.4      | **HW 6 due**          |
| 11/26 | Extreme values, max-min problems                        | 4.4, 4.5      |                       |
| 11/28 | **Thanksgiving Vacation**                               |               |                       |
| 12/03 | More max-min, catchup                                   | 4.5, 4.9 (?)  | **HW 7 due**          |
| 12/05 | **Reading Period**                                      |               |                       |
| 12/10 | **Final Examination**                                   |               |                       |

</div>

### Homework
Homework will be due _before class_ on the day indicated on the syllabus. Late homework will not be accepted. The lowest percentage homework score will be dropped.

#### HW 0
This homework will not count towards your final grade, but please turn it in anyway. Numbered problems are from the textbook.

* Solve 1.3.1, 1.3.2, 1.3.6, 1.3.14, 1.3.32

#### HW 1

Only the problems marked "turn in" are to be turned in.

* **Turn in:** 1.6 (1, 3, 6, 10, 64, 67), 1.8 (6, 8, 10), 2.1 (2, 4), 2.2 (21, 22, 24, 26)
* Read [_How to write proofs_](proofguide.pdf) by Eugenia Cheng.
* **Practice:** 1.3 (14, 16, 28, 44, 53), 1.6 (11, 12)
* **Challenge:** Suppose $a$, $b$, $c$ are real numbers such that $(a+b+c)$, $(ab+bc+ca)$ and $abc$ are all integers. Prove that for every $n\in \mathbb{N}$, the number $(a^n + b^n + c^n)$ is an integer.

----
### Older announcements
{% for post in site.categories.151aut13 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | strip_html }}
{% endfor %}

