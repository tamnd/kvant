---
id: 1991-3-solovev-ogyusten-lui-koshi-i-matematicheskaya-induktsiya-d59001a7
issue: kvant_1991_3
year: 1991
number: "3"
title: Augustin Louis Cauchy and mathematical induction
authors:
  - Соловьёв Ю. П.
rubric: osnovnye-stati
page_first: 15
page_last: 16
page_labels: 13-14
lang: en
source: kvant_digital
extraction: vision
content_sha256: b0e7d962841ed674a0abcddd7da2ba631d5bdd6c4218624c814a0c38721cde4e
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/03_solovev-ogyusten-lui-koshi-i-matematicheskaya-induktsiya-d59001a7.md
source_content_sha256: 86fafd5bbe02ce1b27659e76d97ff1b8d2db42a7cf73964a9faabc1e3e22a067
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 13⟧

---
running_head:
folio:
---

AUGUSTIN
LOUIS CAUCHY AND
MATHEMATICAL
INDUCTION

Doctor of Physical and Mathematical Sciences
Y. SOLOVEV

The arithmetic mean of positive numbers is not less than their geometric mean:

$$\frac{x_1+x_2+\ldots+x_n}{n} \geq \sqrt[n]{x_1x_2\ldots x_n}.$$

This value of equality, which belonged to the French mathematician O. Cauchy, was published in 1821. Since then, it has traditionally been considered one of the most difficult numerical inequalities. Over the course of a century and a half, several dozen different proofs of this inequality have appeared. The tradition was started by Cauchy himself. His proof took several pages of complex calculations. I invite the reader to get acquainted with the simplest proof I know of. In my opinion, it is as beautiful as it is respectful. But first we need to reformulate Cauchy's inequality somewhat.

Why reformulate the same problem? Ordinary mathematicians know that this activity is not at all as useless as it seems... Simple proofs of complex theorems usually consist of numerous reformulations.

First of all, in our inequality the dreaded $n$th root on the right side adds up. Let's divide both parts by it. The unit will remain on the right, and the trace will be the arithmetic mean of the numbers.

$$y_1 = \frac{x_1}{\sqrt[n]{x_1x_2\ldots x_n}}, \ldots, y_n = \frac{x_n}{\sqrt[n]{x_1x_2\ldots x_n}}.$$

⟦folio 14⟧

---
running_head:
folio:
---

Under conditions
$$y_1 > 0, \dots, y_n > 0,$$
$$y_1 y_2 \dots y_n = 1$$

it is necessary to prove that
$$\frac{y_1 + y_2 + \dots + y_n}{n} \geqslant 1.$$ (*)

Now let's think about mathematical indexation. We will prove Cauchy's inequality step by step, each time increasing $n$ by one. For $n = 1$ it is obvious (and turns into a strict equality). Let's assume that we managed to prove the inequality for some $n$. So, now we need to output it for $n + 1$.

Indicative step
It is necessary to prove that if
$$z_1 > 0, \dots, z_n > 0, z_{n+1} > 0,$$
$$z_1 z_2 \dots z_n z_{n+1} = 1,$$
then $z_1 + \dots + z_n + z_{n+1} \geqslant n + 1$. Let us use inequality (*), which we consider proven for $n$ numbers. Let $y_1 = z_1, \dots, y_{n-1} = z_{n-1}, y_n = z_n, z_{n+1}$. Then both conditions are satisfied
$$y_1 > 0, \dots, y_n > 0,$$
$$y_1 y_2 \dots y_n = 1,$$

And we assume that the inequality $y_1 + \dots + y_n \geqslant n$ has been proven, i.e.
$$z_1 + z_2 + \dots + z_{n-1} + z_n \cdot z_{n+1} \geqslant n.$$

Note that so far we have been concerned only with reformulations. But where is the proof itself? Here it is.

If necessary, we will resize the numbers $z_1, \dots, z_{n+1}$ so that $z_n > 1, z_{n+1} < 1$ are satisfied. (It is clear that if the numbers $z_i$ are not simultaneously equal to 1, then among them there are two such numbers.) Now in the last formula we note the product of $z_n \cdot z_{n+1}$ by the sum $z_n + z_{n+1}$. To do this, we need to show that $z_n + z_{n+1} \geqslant z_n \cdot z_{n+1} + 1$, or $z_n + z_{n+1} - z_n \cdot z_{n+1} - 1 \geqslant 0$.

Let's factorize the left side:
$$z_n (1 - z_{n+1}) - (1 - z_{n+1}) = (z_n - 1) (1 - z_{n+1}) \geqslant 0.$$

After this, the inequality is obvious, since $z_n > 1, z_{n+1} < 1$. The proof is legal.

And now a few words about this proof. The only place that is not completed is the choice of numbers $z_n, z_{n+1}$. In general, elementary reformulations and mathematical induction worked for us.

Meanders
(See beginning on p. 11)

3. Numerous figure mean-drov can be found in Anri Poincaré's last work “On a geometric theorem”, where he tries to prove with their help that the processing of a ring into itself, preserving areas and shifting ασ boundary circles in different directions, has at least two fixed points. Poincaré's theorem was proved by Bircroft in 1913 using a different method, but its generalization to mappings of a sphere with handles was proved by Y. M. Elishberr in 1978 using mean-drov (the number of fixed points, counting with multiplicities, is not less than 2g+2, where $g$ is the number of handles).

The following theorems also follow from the mean-drop theory:

(1) An irreducible non-self-intersecting principal closed curve on the projective plane has at least three crossing points.

(2) A closed plane curve has at least 4 vertices (extremal points of curvature).

(3) Let's call the river section between two places positive if the number of the next place (along the highway) is greater. Prove that the number of river crossing points is not less than the number of conservation signs in the sequence of section signs (mean-ds with 4 places on figure 2 have the sequences (+++), (+ -), (- +)).
