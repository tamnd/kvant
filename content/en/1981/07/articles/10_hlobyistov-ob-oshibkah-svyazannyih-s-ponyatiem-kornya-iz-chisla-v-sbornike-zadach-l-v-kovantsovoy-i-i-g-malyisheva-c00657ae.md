---
id: 1981-7-hlobyistov-ob-oshibkah-svyazannyih-s-ponyatiem-kornya-iz-chisla-v-sbornike-zadach-l-v-kovantsovoy-i-i-g-malyisheva-c00657ae
issue: kvant_1981_7
year: 1981
number: "7"
title: '[On errors associated with the concept of a root of a number, in the collection of problems by L. V. Kovantsova and I. G. Malyshev]'
authors:
  - Хлобыстов В.
rubric: smes
page_first: 36
page_last: 36
page_labels: "34"
tag: 0VW8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 104a66536a3f189e4ffbd297a9bcae9cc534ba2f06a50d47566397ca0966e311
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/10_hlobyistov-ob-oshibkah-svyazannyih-s-ponyatiem-kornya-iz-chisla-v-sbornike-zadach-l-v-kovantsovoy-i-i-g-malyisheva-c00657ae.md
source_content_sha256: d113138dc17144c62c82846204751a92317f397678c71df80acaeec6351795fd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

but slowly along the inclined plane (we consider the mass of the matrix to be much less than the mass of the cart). We will assume that the transition from the horizontal surface to the inclined plane is very smooth and the time of movement of the cart along the rounded one is much less than the period of oscillation of the matrix, so that almost instantly the suspension point of the matrix begins to move up the inclined plane with an initial speed $v_0$ and an acceleration equal in abscute value to $b = g \sin \alpha$ and a downward direction along the inclined plane. Relative to the cart, the matrix at the initial moment has a speed of $v_0(1 - \cos \alpha)$; the relative velocity vector is perpendicular (we assume that the parallel component of the velocity is canceled out). The new acceleration due to gravity is $|\vec{g} - \vec{b}| = g \cos \alpha$. The equipotential equations of energy, as is easy to see, are parallel to the inclined plane.

The maximum angle $\phi'_0$ of the matrix deviation relative to the new position is equal to

$$\frac{m(v_0(1 - \cos \alpha))^2}{2} + mgl \cos \alpha \cdot (1 - \cos \alpha) = mg \cos \alpha \cdot l(1 - \cos \phi'_0),$$

where

$$\cos \phi'_0 = \cos \alpha - \frac{v_0^2}{2gl \cos \alpha} (1 - \cos \alpha)^2 = \cos \alpha - \frac{v_0^2 2 \sin^2 \frac{\alpha}{2}}{gl \cos \alpha},$$

$$\phi'_0 = \arccos \left( \cos \alpha - \frac{2v_0^2 \sin^2 \frac{\alpha}{2}}{gl \cos \alpha} \right).$$

S. Krotov

Several years ago, «Kvant» published a note “What is $0,5\sqrt{4}$ equal to?” (1976, no. 11), which examined errors associated with determining the root of a number. In mathematics, this definition is fulfilled unambiguously: “The root of the equation $x^n = a$, where $n$ is a natural number, is called the root of the $n$th degree $u_3 a$” (“Algebra 8”, 1980, paragraph 24). Applicants often forget about the words “where $n$ is a natural number.” So, if the equation contains $\sqrt{a}$, then in the proposed answers you can find numbers such as 0.5, -3, etc.

Unfortunately, this kind of error occurs not only in the responses of applicants. Let's look at two examples from the book by L. V. Kovantsov and I. G. Malyshev “Collection of problems in mathematics” (Kyiv, “Vishsha Shkola”, 1980).

Us. 101 provides the following “solution” to the inequality

$$\log x \sqrt{x} > 10x^4. \tag{1}$$

“Let us write the inequality in the form

$$\frac{1}{x^{\lg x}} > 10x^4. \tag{2}$$

Now it is good to see that the range of acceptable values ​​is $x > 0$, $x \neq 1$. Let's continue

both sides of the inequality based on base 10 (the inequality sign will remain):

$$\frac{1}{\lg x} \cdot \lg x > 1 + 4 \lg x \Leftrightarrow \Leftrightarrow \lg x < 0 \Rightarrow 0 < x < 1.$$

Answer. $X = ]0; 1[$

The answer is not correct, since for $x \in ]0; 1[$ the number $\lg x$ (the root exponent in (1)!) is not a natural number. Where is the mistake? The answer given in the book is the correct answer for inequality (2), but inequalities (1) and (2) are not equal. True, the set $\{10^n\} (n \in \mathbb{N})$ is the region of admissible values ​​of inequality (1), they are equal. Taking this into account, we get the answer: $\emptyset$.

On page 97 the answer to the system of equations

$$\begin{cases} x^2 + xy + y^2 = a^2, \\ \log_x \sqrt{a} + \log_y \sqrt{b} = \frac{a}{\sqrt{3}} \end{cases}$$

written as “At $a > 0$, $b > 0$, $a, b \neq 1$:

$$\left( \frac{a}{\sqrt{3}} \frac{a}{\sqrt{3}} \right),$$

which is also very, very wrong.

Similar inaccuracies are essentially contained in the solution of examples No. 153 and No. 183.

V. Khlobistov

Amendment

In «Kvant» No. 6 in task «Kvant» there are inaccuracies. In assignment **M686** there should be $[\sqrt{\sqrt{x}}]$ on the left side of the equation. In problem **M688** the sum $a_1 + a_2 + \dots + a_n$ is even. The deadline for sending solutions to these problems is extended until October 1, 1981.
