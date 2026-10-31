---
id: 1974-8-torondzhadze-bendukidze-krivyie-peano-507e9795
issue: kvant_1974_8
year: 1974
number: "8"
title: Peano curves
authors:
  - Торонджадзе М. С.
  - Бендукидзе А. Д.
rubric: osnovnye-stati
page_first: 15
page_last: 18
page_labels: 13-16
tag: 91QG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 67644f7edd539c56da98f9303c62a836bafaa81eed6d6ad31b4a4461381cb4c1
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/02_torondzhadze-bendukidze-krivyie-peano-507e9795.md
source_content_sha256: 423750f3ae5e5cd5c9c44df81889c8bddc1a9b852cf030a8ede0f1fdef7b3ffb
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

From March 26 to March 30, 1974, the second scientific conference of students of the Tbilisi Physics and Mathematics Secondary Boarding School named after V. M. Komarov took place in Tbilisi. At this conference, Georgian schoolgirl Medea Toronjadze read a report “Peano Curves”, prepared under the leadership of A.D. Bendukidze. The report was presented in the form of an article, which we bring to the attention of readers. It talks about how certain lines were distributed, and about the curve due to which this certain one had to be changed. You will find the final defined lines (more precisely, the dimensions of the exact set) in the article by Academician P. S. Aleksandrov (see p. 3).

What is a line?

Probably, many of those who are asked this question will shrug their shoulders in bewilderment and answer: “Line? Yes, it's very simple! Run the point of a well-sharpened pencil across the paper and you get a line.”

It seems that they are right, because when we talk about a line, we actually imagine something that looks like a tall, thin stroke, for example, on a sheet of paper.

And yet they will not be right! The reason is very simple: they are not intended to be definite, but to indicate what should be understood by a line. However, one can hardly blame them, since giving an exact mathematical definition of a line is not as easy as it might seem at first glance. It took mathematicians about 2200 years to do this!

The first who tried to define the line was Euclid's French mathematician René De-

Medea Toronjadze reads a report “Peano Curves” at a conference of students of physics and mathematics boarding schools in Tbilisi

⟦folio 14⟧

names of which satisfy some equation of the form $F(x, y) = 0$.

This was a fairly general and good definition of the lines. It was good in that it made it possible to reduce the study of lines to the study of the equation $F(x, y) = 0$ that defines it. But later it turned out that often the function $F(x, y)$ has a rather complex form.

For example, if a circle of radius $R$ is given by the equation

$$x^2 + y^2 - R^2 = 0$$

(here $F(x, y) = x^2 + y^2 - R^2$), then the Archimedes spiral cannot be specified by such a simple equation. An Archimedes spiral is a curve described by a point moving uniformly along a ray, which at the same time rotates uniformly around a fixed point (Fig. 1). This curve is easier to study geometrically without resorting to an equation.

Descartes' definition had one more drawback: if you do not impose any restrictions on the form of the function $F(x, y)$, then any set on the plane according to Descartes is linear (it is enough to define the function $F(x, y)$ like this: on a given set of pairs $(x, y)$ this function is equal to zero, at all other points of the plane $F(x, y) = 1$). For example, a single square according to Descartes is a “line”, it is given by the equation

$$|x| + |x-1| + |y| + |y-1| - 2 = 0$$

here is the function

$$F(x, y) = |x| + |x-1| + |y| + |y-1| - 2$$

further continuous!

In the second half of the 19th century, another French mathematician, Camille Jordan (1838–1922), developed the concept of lines proposed by Descartes. Jordan defined a plane line as a set of points in a plane whose coordinates are $x$ and $y$ given by the equations

$$x = \varphi(t), y = \psi(t)$$

food $\varphi(t)$ and $\psi(t)$ are functions that are continuous on the interval [0, 1].

Fig. 1.

Now this method of defining lines is called parametric (with the parameter $t$).

For example, the parametric equation of a circle of radius $R$ is

$$x = R \cos 2\pi t, \quad y = R \sin 2\pi t.$$

The Archimedes spiral (more precisely, a piece of it) is given by simple equations

$$x = vt \cos \omega t, \quad y = vt \sin \omega t.$$

Some times it seemed that a successful definition of lines had finally been found, in which the square would certainly not fall into the “lines”. No matter how it is!

In 1890, the Italian mathematician Giuseppe Peano (1858-1932) constructed an example of a curve that runs around all the points of a square, and at the same time satisfies Jordan's definition of lines! Subsequently, other examples of similar “lines” were found. Now the “lines” are also called “Peano curves”. We will present the construction of one of the Peano curves at the end of the article.

The Peano curves show that Jordan's definition is too broad. It is difficult to consider a linear curve that fills an entire square. At the same time, it is too narrow - essentially Linney, it does not fit this definition.

⟦folio 15⟧

So, what is tench? In the case of plane lines, the final answer to this question was given by one of the greatest mathematicians of the late 19th - early 20th centuries, Georg Cantor (1845-1918). Without stopping at the exact formulation of this definition, we present one interesting example of line cantors, constructed by the famous user Waszlaw Sierpinski.

Let's take a square. Let's divide it into two congested squares and remove the internal points of the central square from it. We divide each of the remaining eight squares into two congested squares and in each of them we again remove the internal points of the central square. Continuing this process indefinitely, we will obtain the required value. It is called a Sierpinski carpet (the first page of the cover shows the figure that is obtained when constructing a Sierpinski carpet after the third step). Please note that no matter how close to any of the remaining points (the Sierpinski carpet) there is a point thrown out of the original square.

In the 20s of our century, the accomplished mathematician P. S. Uryso generalized Cantor’s definition and gave a general definition of lines *).

Construction of the Peano curve

1. Let σ be the unit segment [0,1]. Let's divide it into four congestion segments:

$$\sigma_{1}^{(1)} = \left[ 0, \frac{1}{4} \right], \quad \sigma_{2}^{(1)} = \left[ \frac{1}{4}, \frac{1}{2} \right], \quad \sigma_{3}^{(1)} = \left[ \frac{1}{2}, \frac{3}{4} \right], \quad \sigma_{4}^{(1)} = \left[ \frac{3}{4}, 1 \right].$$

*) This is described in detail in the article by Academician P. S. Alexandrov “Pavel Samulovich Uryson” (see p. 3). See also A. S. Parkhomenko “What is a line”, M., Gostekhidat, 1954.

Let's call these segments segments of the first run. Dividing each of them into four congested segments, we obtain 16 segments of the second run $\sigma_{i}^{(2)}$ ($i = 1, 2, \dots, 16$). Continuing the division process, we obtain segments of the third, fourth and large wounds. In this case, the segments of the $r$-th wound will look like:

$$\sigma_{i}^{(r)} = \left[ \frac{i - 1}{4^r}, \frac{i}{4^r} \right] \quad (i = 1, 2, \dots, 4^r).$$

Let us now take some point $t_0 \in \sigma$.

If it does not coincide with any division point, then there is exactly one segment of each wound containing it. Let $\sigma_{i}^{(1)}, \sigma_{i}^{(2)}, \sigma_{i}^{(3)}, \dots$ be like that. Let us correspond to the point $t_0$ with an infinite sequence of natural numbers $i_1, i_2, i_3, \dots$ and write it like this:

$$t_0 = (i_1, i_2, i_3, \dots).$$

Example. $1/3 = (2, 6, 22, 85, \dots)$.

If the point $t_0$ coincides with any point of division, that is, has the form $m/4^n$, then starting from the segments of the $n$th wound it will contain two adjacent segments of each wound. Let us associate with it two sequences of natural numbers ($i_1, i_2, i_3, \dots$), in which $1 \leq i_1 \leq 4$, $4i_k - 3 \leq i_{k+1} \leq 4i_k$. Conversely, each such sequence determines a unique point of the segment $\sigma$ (prove it!).

2. Let us carry out a similar construction for the unit square Q. Dividing it into four congested squares, we obtain the squares of the first run: $Q_{1}^{(1)}, Q_{2}^{(1)}, Q_{3}^{(1)}, Q_{4}^{(1)}$. Dividing each of these squares into four congestion squares gives the second rana squares and so on. In general, dividing each square of the $r$th run $Q_{i}^{(r)}$ into four congested squares yields four squares of the $(r+1)$th run: $Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}$ ($i = 1, 2, \dots, 4^r$). We number the squares so that:

1) the first square of any run contained the point (0, 0);

2) it was possible from the square $Q_{i}^{(r)}$ to bypass the successive square $Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}$ and exit in the square $Q_{i+1}^{(r)}$, intersecting only the sides (but not the vertices!) of the rana squares $(r+1)$.

⟦folio 16⟧

Fig. 2.

We invite the reader to prove that such numbering is always possible. On figure 2 the squares of the first three ranks are shown, and the red broken line indicates the path along which the squares are numbered (starting from the lower left square).

Continuing the reasoning, we are convinced that for each point $(x_0, y_0)$ the square $Q$ can be assigned to one or several (how many?) sequences of natural numbers, we write it like this:

$$(x_0, y_0) = [i_1, i_2, i_3, \dots]$$
$$(1 \leq i_1 \leq 4, 4i_k - 3 \leq i_k + 1 \leq 4i_k).$$

Examples: $(1/3, 1/3) = [1, 3, 9, \dots]$;
$(1/2, 1/3) = [1, 3, 10, \dots] = [1, 14, 56, \dots]$;
$(1/2, 1/2) = [1, 3, 11, \dots] = [2, 8, 32, \dots] = [3, 9, 33, \dots] = [4, 14, 54, \dots].$

And here we can prove that each such sequence determines a unique point $(x_0, y_0)$ from $Q$.

3. Writing the points of the segment $\sigma$ and the square $Q$ as infinite sequences of natural numbers makes it possible to map $\sigma$ onto $Q$.

Indeed, the path $t_0$ is an arbitrary point $\sigma$ and

$$t_0 = (i_1, i_2, i_3, \dots).$$

The last sequence uniquely determines the point $(x_0, y_0)$, which corresponds to the sequence $[i_1, i_2, i_3, \dots]$. Even if $t_0$ is representable as two sequences, then both of them lead to the same point $(x_0, y_0)$. This is easy to prove if we take into account that the lengths of the sides of a square tend to zero as their rank increases. So, each $t_0$ corresponds to a single $(x_0, y_0)$.

Now let the point $(x_0, y_0) \in Q$ be arbitrary and $[i_1, i_2, i_3, \dots]$ be one of the representations of this point. Taking $t_0 = (i_1, i_2, i_3, \dots)$, we make sure that in our mapping, each point of the square $Q$ corresponds to at least one point of the segment $\sigma$. This means that $\sigma$ is mapped to $Q$. Note that this mapping is not one-to-one; the non-mapping $Q$ corresponds to two, those or even four points $\sigma$.
