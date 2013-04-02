---
layout: default
title: Math 153 (Spring 2013)
---

# Math 153 (Spring 2013)

### Recent announcements
{% for post in site.categories.153spr13 limit: 5 %}
* _({{ post.date | date: "%a %b %d" }})_ {{ post.content | strip_html }}
{% endfor %}
Older announcements are [here](#older-announcements).

----
### Course Information
**Time/place:** Tuesday/Thursday, 9am to 10:30am in Eck 203.  
**Instructor:** Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`)  
**Office hours:** Tuesdays 3pm to 4pm, Wednesdays 5pm to 6pm, Thursdays 1pm to 2pm, and any other time by appointment  
**VCA:** Yo Joong Choe  
**YJ's office hours:** TBA  
**Problem session:** Tuesdays, 5pm to 6pm in Eck 203.  
**Textbook:** _Calculus_ by Salas, Hille, Etgen, 10th edition.  

Grades will be based on homework, two midterms and a final exam. The grade distribution for the class will be as follows.

* Homework: 10%
* Higher-scoring midterm: 30%
* Lower-scoring midterm: 20%
* Final examination: 40%

### Class Plan and Homework
Homework will be due _before class_ on the day indicated each week. Late homework will not be accepted. The lowest homework score will be dropped.

The class plan is tentative and will be updated as the quarter goes by. You will get more out of each class if you read the relevant sections of the textbook before you come to class.

<table class="classplan">
<tr>
<th>Date</th>
<th>Topic</th>
<th>Section</th>
<th>Homework</th>
</tr>

<tr>
<td>Apr 02</td>
<td>Inverse trigonometric functions</td>
<td>7.7</td>
<td></td>
 </tr>

 <tr>
 <td>Apr 05</td>
 <td>Hyperbolic sine and cosine</td>
 <td>7.8</td>
 <td>HW 1: 7, 13, 14, 24, 31, 52 from Ch 7 review exercises, 7.7.16, 7.7.25, 7.7.31, 7.7.35</td>
</tr>

<tr>
<td>Apr 09</td>
<td>Integration by parts, powers/products of trig functions</td>
<td>8.2, 8.3</td>
<td></td>
</tr>

<tr>
<td>Apr 11</td>
<td>Integrating $\sqrt{a^2 - x^2}$ etc and rational functions</td>
<td>8.4, 8.5</td>
<td>HW 2: TBA</td>
</tr>

<tr>
<td>Apr 16</td>
<td>Integrating partial fractions</td>
<td>8.5</td>
<td></td>
</tr>

<tr>
<td>Apr 18</td>
<td>Some differential equations, Catchup</td>
<td>9.1, 9.2</td>
<td>HW 3: TBA</td>
</tr>

<tr>
<td>Apr 23</td>
<td><em>Midterm 1</em></td>
<td></td>
<td></td>
</tr>

<tr>
<td>Apr 25</td>
<td>The least-upper-bound axiom, sequences of real numbers</td>
<td>11.1, 11.2</td>
<td>HW 4: TBA</td>
</tr>

<tr>
<td>Apr 30</td>
<td>The limit of a sequence, some important limits</td>
<td>11.3, 11.4</td>
<td></td>
</tr>

<tr>
<td>May 02</td>
<td>Indeterminate forms: $(0/0)$, $(\infty/\infty)$</td>
<td>11.5, 11.6</td>
<td>HW 5: TBA</td>
</tr>

<tr>
<td>May 07</td>
<td>Indeterminate forms</td>
<td>11.6</td>
<td></td>
</tr>

<tr>
<td>May 09</td>
<td>Improper integrals</td>
<td>11.7</td>
<td>HW 6: TBA</td>
</tr>

<tr>
<td>May 14</td>
<td>Sigma notation, Infinite series</td>
<td>12.1</td>
<td></td>
</tr>

<tr>
<td>May 16</td>
<td>Tests for convergence, Catchup</td>
<td>12.3, 12.4</td>
<td>HW 7: TBA</td>
</tr>

<tr>
<td>May 21</td>
<td><em>Midterm 2</em></td>
<td></td>
<td></td>
</tr>

<tr>
<td>May 23</td>
<td>Absolute and conditional convergence, alternating series</td>
<td>12.5</td>
<td>HW 8: TBA</td>
</tr>

<tr>
<td>May 28</td>
<td>Taylor polynomials and Taylor series</td>
<td>12.6, 12.7</td>
<td></td>
</tr>

<tr>
<td>May 30</td>
<td>Taylor polynomials and Taylor series, power series</td>
<td>12.7, 12.8</td>
<td>HW 9: TBA</td>
</tr>

<tr>
<td>Jun 04</td>
<td>Differentiation and integration of power series</td>
<td>12.9</td>
<td></td>
</tr>

<tr>
<td>Jun 06</td>
<td><em>Reading Period</em></td>
<td></td>
<td></td>
</tr>

<tr>
<td>Jun 11</td>
<td><em>Final Examination</em></td>
<td></td>
<td></td>
</tr>
</table> 

### Older Announcements
{% for post in site.categories.153spr13 offset: 5%}
* ({{ post.date | date: "%a %b %d" }}) {{ post.content | strip_html }}
{% endfor %}
