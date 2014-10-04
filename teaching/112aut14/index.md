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

| ------:       | :-----                                                                  |
| Time/place:   | MWF 11:30am to 12:20pm in Eck 203                                       |
| Instructor:   | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`)            |
| Office:       | [Math-Stat 015](https://maps.uchicago.edu/?location=Math-Stat+Building) |
| Office hours: | TBA                                                                     |
| Tutorials:    | TBA                                                                     |
| Tutors:       | Sasha Ayvazov, Abigail Shearrow, and Victor Zhang                       |

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
| 10/10 | One's digit arithmetic                  |      1.4 | **[HW 2](#hw-2) due** |
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

#### HW 2
1. 1.12
1. 1.15
1. 1.20
1. 1.25
1. 1.28
1. The numbers 1 through 10 are written in a row. The game is to try and place either $+$ or $-$ signs between consecutive numbers so that the resulting sum is zero. Can you win? (Hint: Use the ideas of Section 1.3)
1. Read section 1.4 on one's digit arithmetic, and answer the following.
    1. What are the square numbers in one's digit arithmetic?
    1. Which of the above numbers have two different square-roots?
1. Solve the following puzzle, such that each letter stands for a different digit between 0 and 9.  
<pre>
  FORTY
    +   TEN
    +   TEN
    -------
    = SIXTY
    </pre>
1. (Tutorial) Consider the set $\{e, a, b\}$. Come up with an abelian group structure on this set such that $e$ is the identity element, and write out the addition table. Is there more than one possible structure? How about on the set $\{e, a, b, c\}$?

----
### Older announcements
{% for post in site.categories.112aut14 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
