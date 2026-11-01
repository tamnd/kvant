---
id: 1987-8-konyushkov-neravenstvo-koshi-bunyakovskogo-c4a495a8
issue: kvant_1987_8
year: 1987
number: "8"
title: Cauchy–Bunyakovsky inequality
authors:
  - Конюшков А. А.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
tag: 9S4C
lang: en
source: kvant_digital
extraction: vision
content_sha256: 33f0a1128f337d924df82a3ceecadcf0f2047a73be1f2dca73c4b7d338aac4b6
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/12_konyushkov-neravenstvo-koshi-bunyakovskogo-c4a495a8.md
source_content_sha256: da1ea376f5fccc06ff2e420b1232a1bb3228632e2c31c8d2ba1c18c647c72829
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

which our diagram of space does not demonstrate explicitly.

Problem 3. Inscribe a parallelogram similar to the given one into another given parallelogram so that on each side of the described parallelogram lies one vertex of the inscribed one.

Let ABCD be the given circumscribed parallelogram, and KLMN the desired inscribed one (Fig. 4). Their centers must coincide, since with central symmetry relative to the center of the parallelogram KLMN, the parallelogram ABCD must transform into itself. Consequently, the center O of the desired parallelogram is known to us; $\angle KOL = \alpha$ and the relation $LO:KO = k$ are also known, since the parallelogram shape KLMN is given. This means that we can apply our scheme by taking the straight lines AB and BC as $M_1$ and $M_2$, the ready-made rotary $H_0^\circ R_0^\alpha$ as F, and the required points K and L ($L = F(K)$) as X and Y. No further explanation is needed. We only note that in this problem it is interesting to conduct a complete study.

Problem 4. Construct triangle ABC if the length of its bisserline AD and the side lengths AB and AC are known.

Let's construct a segment AD and draw circles β and γ of radii AB and AC with center A (Fig. 5). This will be the set M1 and M2, and points B and C are points X and Y in our diagram. What will be the transformation F? According to the bissergris theorem (see, for example, «Kvant» No. 2 of 1985, p. 29), the ratio $k = CD:DB$, in which the side CB is divided by the base of the bissergris, is equal to the ratio AC:AB of the sides of the triangle, and therefore we know. And since $C = H_D^{-k}(B)$, we can take the ready-made $H_D^{-k}$ as F, i.e. C is the intersection point of circles γ and $H_D^{-k}(\beta)$.

Problems to solve independently

1. Construct a triangle using the bissergris and the segments into which the base of the bissergris divides the side of the triangle.
2. Construct a circle with a given center so that one of the segments connecting its points of intersection with the sides of a given angle is parallel to the given line.
3. At two of the known moments in time with cows, the angles between the directions of two lighthouses marked on the map were measured. The direction and speed of the cow's movement are also known. How to find the position of the cow on the map at these moments?
4. Construct triangle ABC using media AA1 and BB1 and angle C.
5 (for readers familiar with inversion). Inscribe a rhombus of given area in a given parallelogram so that one vertex of the rhombus lies on each side of the parallelogram.

V. N. Dubrovsky

Cauchy-Bunyakovsky inequality

The Cauchy-Bunyakovsky inequality can safely be considered one of the most popular in mathematics. It has appeared more than once on the pages of our magazine (see, for example, «Kvant», 1986, No. 12, p. 31). The Cauchy-Bunyakovsky inequality looks like this:

$$\begin{align*}
|a_1b_1 + a_2b_2 + \dots + a_nb_n| &\leq \\
\leq \sqrt{a_1^2 + a_2^2 + \dots + a_n^2} \cdot \sqrt{b_1^2 + b_2^2 + \dots + b_n^2}.
\end{align*}$$

However, there is little proof of it. Here we give one very simple proof of the Cauchy-Bunyakovsky inequality, discuss its geometric meaning and, with its help, once again solve one problem proposed in 1984

⟦folio 43⟧

in «Kvant» (see No. 5, p. 37, Selected school problems, task 15). Along the way, we will discuss the question of the “accuracy” of the inequality.

So, if at least one of the radicals, for example $\sqrt{a_1^2+a_2^2+\dots+a_n^2}$, is equal to zero, then $a_1=a_2=\dots=a_n=0$, the left-hand side in (1) is also equal to zero and the inequality is true. Let both roots be positive and empty

$$A = \sqrt{a_1^2+a_2^2+\dots+a_n^2},$$
$$B = \sqrt{b_1^2+b_2^2+\dots+b_n^2}.$$

Let us rewrite inequality (1) in the form

$$\frac{|a_1b_1+a_2b_2+\dots+a_nb_n|}{AB} \leq 1.$$

Taking advantage of the fact that $|x+y| \leq \leq |x|+|y|$ and $|xy| \leq \frac{1}{2}(x^2+y^2)$, we write the integer inequality:

$$\frac{|a_1b_1+a_2b_2+\dots+a_nb_n|}{AB} \leq \frac{|a_1b_1|}{AB} +$$
$$+ \frac{|a_2b_2|}{AB} +\dots+\frac{|a_nb_n|}{AB} =$$
$$= \frac{|a_1|}{A} \cdot \frac{|b_1|}{B} +\frac{|a_2|}{A} \cdot \frac{|b_2|}{B} +\dots$$
$$\dots \frac{|a_n|}{A} \cdot \frac{|b_n|}{B} \leq \frac{1}{2}\left(\frac{a_1}{A}\right)^2+\left(\frac{b_1}{B}\right)^2)+$$
$$+ \frac{1}{2}\left(\left(\frac{a_2}{A}\right)^2+\left(\frac{b_2}{B}\right)^2\right)+\dots+\frac{1}{2}\left(\left(\frac{a_n}{A}\right)^2+\left(\frac{b_n}{B}\right)^2\right)+$$
$$+ \frac{1}{2}\left(\left(\frac{a_1}{B}\right)^2+\left(\frac{b_2}{B}\right)^2\right)=1$$

— inequality (1) has been proven. Note that we have proven a stronger inequality: $|a_1b_1|+\dots+|a_nb_n| \leq AB$. Equality in it is achieved when

$$\frac{|a_1|}{A} = \frac{|b_1|}{B}, \frac{|a_2|}{A} = \frac{|b_2|}{B}, \dots, \frac{|a_n|}{A} = \frac{|b_n|}{B},$$

i.e., for $\left|\frac{a_1}{b_1}\right| = \left|\frac{a_2}{b_2}\right| = \dots = \left|\frac{a_n}{b_n}\right|$ (if $a_i, b_i$ are different from zero; if some $b_i=0$, then the corresponding $a_i=0$). In (1) equality is achieved when, in addition, the product $a_1b_1$, ..., $a_nb_n$ is of the same sign, i.e. when

$$\frac{a_1}{b_1} = \frac{a_2}{b_2} = \dots = \frac{a_n}{b_n}.$$

For $n=3$ the Cauchy–Bunyakovsky inequality takes the form

$$|a_1b_1+a_2b_2+a_3b_3| \leq$$
$$\leq \sqrt{a_1^2+a_2^2+a_3^2} \cdot \sqrt{b_1^2+b_2^2+b_3^2},$$

(1') and it is not difficult to understand its geometric meaning. Consider two vectors $\vec{a}(a_1, a_2, a_3)$ and $\vec{b}(b_1, b_2, b_3)$. Then on the left side of (1') the absolute value is written

the rank of the scalar product of the vectors $\vec{a}$ and $\vec{b}$, and on the right side the product of their length $\|\vec{a}\|=\sqrt{a_1^2+a_2^2+a_3^2}, \|\vec{b}\|=\sqrt{b_1^2+b_2^2+b_3^2}$. But the scalar product of vectors is equal to the product of the length of the vectors and the cosine of the angle between them; since $\|\cos(\vec{a}, \vec{b})\| \leq 1$, we obtain inequality (1').

In the case of an arbitrary $n$, the Cauchy–Bunyakovsky inequality has the same geometric meaning in a space of dimension $n$, where the vector, the length of the vector and the scalar product of vectors are defined similarly to how it is done in three-dimensional space:

$$\vec{a} = (a_1, a_2, \dots, a_n),$$
$$\vec{a}\vec{b} = a_1b_1+a_2b_2+\dots+a_nb_n,$$
$$|\vec{a}|=\sqrt{a_1^2+a_2^2+a_3^2};$$
$$a\cos(\vec{a}, \vec{b})=\frac{\vec{a}\vec{b}}{|\vec{a}| \cdot |\vec{b}|}.$$

Now let's take «Kvant», 1984, No. 5 and look at problem 15 from “Selected School Problems”:

a) Let $a+b+c=1$. Prove that $a^2+b^2+c^2 \geq 1/3$.

b) Let $a+b+c=1$ and $k$ also be known that $a, b, c$ are the lengths of the sides of a certain triangle. Prove that $a^2+b^2+c^2 < 1/2$.

Solution a) By the Cauchy-Bunyakovsky inequality

$$1=a \cdot 1+b \cdot 1+c \cdot 1 \leq \sqrt{a^2+b^2+c^2} \times \sqrt{1^2 \cdot 1^2 \cdot 1^2}=\sqrt{3} \cdot \sqrt{a^2+b^2+c^2}.$$

Hence $a^2+b^2+c^2 \geq 1/3$.

If $a=b=c=1/3$, then $a+b+c=1$ and $a^2+b^2+c^2=1/3$. This means that our inequality is exact.

The question of the accuracy of the inequality is of great importance. Therefore, we give the formation a definition.

Let inequality

$$f(x_1, x_2, \dots, x_n) \geq c$$

satisfied for all valid values ​​of $x_1, x_2, \dots, x_n$. A constant $c$ on the right-hand side is said to be exact if it cannot be increased, i.e., there is no $k>c$ such that the inequality holds for all admissible values ​​of $x_1, x_2, \dots, x_n$.

$$f(x_1, \dots, x_n) \geq k.$$

We project a similar $c$ on the right side of the inequality

$$b(x_1, x_2, \dots, x_n) \leq c,$$

valid for all admissible $x_1, x_2, \dots, x_n$, it is said to be exact if it cannot be increased.

Let's return to our task. Let us prove 6) in a slightly more general formulation: let $a, b, c$ ($a \neq 0, b \neq 0, c \neq 0$) be the lengths of vectors $\vec{a}, \vec{b}, \vec{c}$ such that $\vec{a}+\vec{b}+\vec{c}=\vec{0}$ and $a+b+c=1$. Then $a^2+b^2+c^2 < 1/2$.
