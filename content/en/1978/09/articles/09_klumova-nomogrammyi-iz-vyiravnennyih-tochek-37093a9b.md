---
id: 1978-9-klumova-nomogrammyi-iz-vyiravnennyih-tochek-37093a9b
issue: kvant_1978_9
year: 1978
number: "9"
title: Nomograms from aligned points
authors:
  - Клумова И. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 32
page_last: 33
page_labels: 30-31
tag: P5CH
lang: en
source: kvant_digital
extraction: vision
content_sha256: d24c403e356060525920583423c1d737715f72f79520605d192bf20d5b437c37
prompt_sha256: draft-1
translated_from: content/ru/1978/09/articles/09_klumova-nomogrammyi-iz-vyiravnennyih-tochek-37093a9b.md
source_content_sha256: b152c4927633b82917bfad892256829f315cf6429fd9ef3fc4afb434d5c3a738
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Nomograms from point alignments

The article by V. Vavilov (p. 22) talks about the approximate solution of equations of the second and third steps using grid nomograms. Us. 83 of “Four-digit mathematical tables” by V. M. Bradis also shows a nomogram for the approximate solution of equations $x^2 + px + q = 0$ (Table XXII). However, this is not a grid nomogram, but a so-called point alignment nomogram. What it is, how it is obtained and how to use such a nomogram is discussed in this note.

Let's draw two vertical parallel straight lines - axis $p$ with the beginning of the cut-off $A$ and axis $q$ with the start of the cut-off $B$ (Fig. 1; on this figure the segment $AB$ was redistributed by the axis $p$, $q$, but this is not at all necessary).

Let's take arbitrary numbers $\alpha$, $\beta$ and a positive number $a$. On the $p$ axis we take the point $C$ with the coordinate $-a^{\alpha-\beta}$, on the $q$ axis - the point $D$ with the coordinate $-a^\alpha$. Let $[AD]\cap \bigcap[BC] = E$.

Let us draw through $E$ an arbitrary straight line that is not parallel to the axes $p$, $q$. Let us denote the coordinate of the intersection $M$ of this line with the axis $p$ by $p_0$, and the intersection of $N$ with the axis $q$ by $q_0$. Then

$$a^\alpha + p_0 a^\beta + q_0 = 0,$$

(1)

i.e. the number a is the root of the equation

$$x^\alpha + p_0 x^\beta + q_0 = 0.$$

(2)

Line $MN$ can intersect with axes $p$, $q$ in one of three ways: $p_0 < 0$, $q_0 > 0$ (Fig. 1); $p_0 > 0$, $q_0 < 0$ (Fig. 2); $p_0 < 0$, $q_0 < 0$ (Fig. 3). Let us prove equality (1) for the case depicted in figure 1 (the other two cases are treated similarly).

From the similarity of triangles $AEC$ and $BED$ we have $$\frac{|BD|}{|AC|} = \frac{|DE|}{|AE|},$$ whence $$\frac{|DE|}{|AE|} = \frac{a^\alpha}{a^{\alpha-\beta}} = a^\beta.$$ Further, from the similarity of triangles $AEM$ and $NED$ it follows $$\frac{|DN|}{|AM|} = \frac{|DE|}{|AE|},$$ that is $$\frac{a^\alpha + q_0}{-p_0} = a^\beta$$ (Fig. 1), which gives (1).

Let us fix arbitrary $\alpha$, $\beta$ and consider all possible equations.

⟦folio 31⟧

Fig. 3.

opinions

$$x^\alpha + px^\beta + q = 0.$$ (3)

The nomograph for finding positive roots of such equations is drawn as follows: the parameter $a$ belongs to each positive one and for each of them the point $E$ is constructed as described above; the resulting points, placed by the corresponding parameter values, are connected by a smooth curve $\Gamma$ (Fig. 4).

If we now want to use this nomograph to approximately find the positive roots of a particular equation $x^\alpha + p_0 x^\beta + q_0 = 0$, we need to take point $M$ with coordinate $p_0$ on axis $p$, and point $N$ with coordinate $q_0$ on axis $q$ and draw a straight line $MN$. Each point of intersection of the straight line $MN$ with the curve $\Gamma$ gives, by virtue of (1), a positive root of equation (2).

Now it is clear why a nomograph constructed in this way is called a nomogram of expressed points: the points corresponding to the coefficients $p, q$ of the equation and the points corresponding to the desired positive root of the equation $x^\alpha + px^\beta + q = 0$ lie on the same straight line.

Exercises
1. Construct nomograms from expressed points to find the positive roots of the equation

$$x^m + px^n + q = 0$$

if $m = 3, n = 2; m = 4, n = 1; m = 4, n = 2; m = 4, n = 3.$
