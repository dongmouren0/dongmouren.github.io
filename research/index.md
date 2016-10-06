---
layout: default
title: Research
navigation_weight: 2
---

## {{ page.title }}

### Papers/Preprints

{% for paper in site.data.papers %}
<div class="papers">
**{{ paper.title }}**{% if paper.with %} (with {{ paper.with }}){% endif %}{% if paper.comment %}<br/> *{{ paper.comment | capitalize }}.*{% endif %}

{% for link in paper.links %} [\[{{ link[0] }}\]]({{ link[1] }}) {% endfor %}
</div>
{% endfor %}


<!-- 

<div class="bibliography">

| :-----                                                                                                                                              | :----                                                                                                                                           |
| The Strong Topological Monodromy Conjecture for Coxeter Hyperplane Arrangements (with Robin Walters), _to appear in Mathematical Research Letters_. | [[pdf](papers/bapat-walters-2015.pdf)]                                                                                                          |
| The Bernstein-Sato $$b$$-function of the Vandermonde determinant (with Robin Walters)                                                               | [[arXiv](http://arxiv.org/abs/1503.01055)]                                                                                                      |
| Torus actions and tensor products of intersection cohomology, _Pacific Journal of Mathematics 276 (1):19--34, 2015_                                 | [[pdf](papers/bapat-2015.pdf)], [[arXiv](http://arxiv.org/abs/1309.0859)], [[journal](http://dx.doi.org/10.2140/pjm.2015.276.19)]               |
| Lower central series of free algebras in symmetric tensor categories (with David Jordan), _Journal of Algebra 373:299--311, 2013_                   | [[pdf](papers/bapat-jordan-2013.pdf)], [[arXiv](http://arxiv.org/abs/1001.1375)], [[journal](http://dx.doi.org/10.1016/j.jalgebra.2012.10.001)] |
| Equivariant cohomology and the localization theorem, topic proposal (expository).                                                                   | [[pdf](papers/topic-proposal.pdf)]                                                                                                              |

</div>

### Expository

-->
