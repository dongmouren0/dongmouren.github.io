---
layout: default
title: Math 113 (Winter 2015)
---


# {{ page.title }}

### Recent announcements
{% for post in site.categories.113win15 limit: 3 %}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>'}}
{% endfor %}
Older announcements are [here](#older-announcements). Homeworks are [here](#homeworks).

----

### Course information

<div class="infotable">

| ------:       | :-----                                                       |
| Time/place:   | MWF 11:30am to 12:20pm in Kent 106                           |
| Instructor:   | Asilata Bapat (`asilata` at `math` dot `uchicago` dot `edu`) |
| Office hours: | W 2:30pm to 3:30pm and Th 3pm to 4pm                         |
| Tutor:        | Sasha Ayvazov (`sayvazov` at `uchicago` dot `edu`)           |

[ms]: https://maps.uchicago.edu/?location=Math-Stat+Building

</div>

### Syllabus
The class plan is tentative and will be filled in as the quarter goes by. 

<div class="classplan">

| Date  | Topic                                     | Section          | Homework/Documents    |
| :---  | :---                                      | :---             | :---                  |
| 01/05 | Introduction to Geometry                  | 9                |                       |
| 01/07 | Symmetry group (equilateral triangle)     | 11.1             |                       |
| 01/09 | Symmetry group (triangle and square)      | 11.1,11.2        | **[HW 1](#hw-1) due** |
| 01/12 | Basics of Euclidean geometry              | 10.1, Appendix A | [Notes][eg]           |
| 01/14 | Ruler-compass constructions, circumcircle |                  |                       |
| 01/16 | Orthocenter, incenter, centroid           |                  | **[HW 2](#hw-2) due** |
| 01/19 | **Martin Luther King, Jr. Day**           |                  |                       |
| 01/21 | Ceva's theorem and applications           |                  |                       |
| 01/23 | The nine-point circle                     |                  | **[HW 3](#hw-3) due** |
| 01/26 |                                           |                  |                       |
| 01/28 |                                           |                  |                       |
| 01/30 | **Midterm 1**                             |                  |                       |
| 02/02 |                                           |                  |                       |
| 02/04 |                                           |                  |                       |
| 02/06 |                                           |                  |                       |
| 02/09 |                                           |                  |                       |
| 02/11 |                                           |                  |                       |
| 02/13 | **College break**                         |                  |                       |
| 02/16 |                                           |                  |                       |
| 02/18 |                                           |                  |                       |
| 02/20 |                                           |                  |                       |
| 02/23 |                                           |                  |                       |
| 02/25 |                                           |                  |                       |
| 02/27 | **Midterm 2**                             |                  |                       |
| 03/02 |                                           |                  |                       |
| 03/04 |                                           |                  |                       |
| 03/06 |                                           |                  |                       |
| 03/09 |                                           |                  |                       |
| 03/11 |                                           |                  |                       |
| 03/13 | **Reading Period**                        |                  |                       |

[eg]: eucl-geom-notes.pdf

</div>

### Homeworks

#### HW 1
1. Draw a tiling of the plane that has only translational symmetry.
1. Draw a tiling of the plane that has only translational and rotational symmetry.
1. How many different symmetries does the following "bow-tie" shape (&#x22c8;) have? Write out its multiplication table.
1. Exercise 11.1.

#### HW 2
1. Exercise 11.2
1. Exercise 11.9
1. Draw a figure that has _exactly_ 5 symmetries.
1. Draw a figure that has _exactly_ 6 rotational symmetries and no reflectional symmetry. Write out the multiplication table of its symmetry group. Is there any way to match this up (as you did in Ex 11.1) with the multiplication table of $D_6$?
1. Exercise 10.1
1. Exercise 10.2
1. Exercise 10.6
1. Given any triangle, explain how to construct (with a straightedge and compass) a point whose perpendicular distances from each of the three sides are equal. How many such points are there?

#### HW 3
1. Read Appendix A carefully.
1. Let $ABC$ be a triangle with altitudes $AD$, $BE$, and $CF$. Let $H$ be the orthocenter. Find (with proof) at least one pair of similar triangles in this figure. Now try to find (with proof) three distinct triangles in this figure that are all similar.
1. Sketch a triangle, together with the perpendicular bisectors of its sides, such that the circumcenter lies outside the triangle. Make sure your sketch is convincing!
1. Sketch a triangle, together with the altitudes on each side, such that the orthocenter lies outside the triangle. Make sure your sketch is convincing!
1. (Not to be handed in) Is it possible to have triangles whose centroid or incenter lies outside the triangle? Either try to find such triangles, or try to give an argument that this is not possible. This problem is tricky, so try your best!
1. Consider a circle with center $O$. Suppose that $AC$ is any one diameter of the circle, and that $B$ is any other point on the circle. Prove that the angle $ABC$ equals $90$ degrees. (Hint: extend $BO$ so that intersects the circle again at $B'$, and try to show that $ABCB'$ is a rectangle.)
1. Let $ABC$ be a triangle with medians $AD$, $BE$, and $CF$ and centroid $G$.
    1. Prove that the triangles $ABD$ and $ADC$ have the same area.
    1. Prove that the triangles $GBD$ and $GDC$ have the same area.
    1. Prove that each of the six small triangles ($GBD$, $GDC$, $GCE$, $GEA$, $GFA$, $GFB$) have the same area. (Hint: first compare the areas of triangles $ABD$ and $CFB$ take away the common area.)
    1. Finally, this shows that the area of triangle $ABG$ is twice the area of triangle $BGD$. Conclude that the ratio of the lengths of $AG$ to $GD$ is $2:1$. (Similar results will be true for the other two medians.)

#### Midterm 1 Practice
1. Read all the sections that we covered so far from the book.
1. Read the geometry notes that I uploaded.
1. Review what a group is, especially in the context of symmetries: given a shape, you should be able to write down the multiplication table of its symmetry group.
1. List all the subgroups of $D_6$.
1. Draw a shape that is not an equilateral triangle, but which has the same symmetry group $D_6$.
1. Draw a shape that has the symmetry group $\mathbb{Z}/4\mathbb{Z}$.
1. Consider a triangle $ABC$. Let $D$, $E$, $F$ be the midpoints and $P$, $Q$, $R$ be the feet of the altitudes of $BC$, $CA$, and $AB$ respectively. Let $P'$ on $BC$ be the reflection of $P$ across $D$. Construct $Q'$ and $R'$ in an analogous way on $CA$ and $AB$. Prove that $AP'$, $BQ'$, $CR'$ are concurrent.
1. Let $r$ be the _inradius_ of a triangle $ABC$, that is the radius of the incircle. Let $s = (BC + CA + AB)/2$. Prove that the area of triangle $ABC$ equals $s\cdot r$. (Hint: Draw the lines $AI$, $BI$, and $CI$.)

----
### Older announcements
{% for post in site.categories.113win15 offset: 3%}
* **{{ post.date | date: "%a %b %d" }}:** {{ post.content | remove: '<p>' | remove: '</p>' }}
{% endfor %}
