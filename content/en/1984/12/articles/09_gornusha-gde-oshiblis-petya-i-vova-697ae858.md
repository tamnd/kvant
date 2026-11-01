---
id: 1984-12-gornusha-gde-oshiblis-petya-i-vova-697ae858
issue: kvant_1984_12
year: 1984
number: "12"
title: Where did Petya and Vova go wrong?
authors:
  - Горнуша П. П.
rubric: shkola-v-kvante
page_first: 24
page_last: 24
page_labels: "22"
tag: 1C4F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5f962264b47b6c61dca25f92376c0a681f873bddae2197d46c69cf61f3c1be8d
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/09_gornusha-gde-oshiblis-petya-i-vova-697ae858.md
source_content_sha256: 5330ec7836970cc4d8aac0f4d4dd873132606387113f113b28a5781a3b6e83a4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Mathematics
8, 9, 10

The article published below “Where did Petya and Vova go wrong?” is intended for 8th grade, “Geometry helps to solve equations” - 9th grader and trihedral streets - 10th grader. This division is to some extent arbitrary, since each of these notes can be useful not only for students in the specified classes.

Where did Petya and Vova go wrong?

Two friends, Petya and Vova, were solving for the optimal system of equations
$$\begin{cases}
(x^2 - xy + y^2)(x - y) = 1 + y^3, \\
(x^2 + xy + y^2)(x + y) = 1 - y^3.
\end{cases}$$

Petya replaced the second equation with a product of equations:
$$\begin{cases}
(x^2 - xy + y^2)(x - y) = 1 + y^3, \\
(x^3 - y^3)(x^3 + y^3) = 1 - y^6,
\end{cases}$$

that is
$$\begin{cases}
(x^2 - xy + y^2)(x - y) = 1 + y^3, \\
x^6 - y^6 = 1 - y^6.
\end{cases}$$

From the second equation $x = \pm 1$, I open it and got the answer: $(1; 0); (-1; -1)$.

Vova replaced the first equation with a product of equations:
$$\begin{cases}
x^6 - y^6 = 1 - y^6, \\
(x^2 + xy + y^2)(x + y) = 1 - y^3,
\end{cases}$$

where
$$\begin{cases}
x = \pm 1, \\
(x^2 + xy + y^2)(x + y) = 1 - y^3.
\end{cases}$$

This gives the answer: $(1; 0); (-1; 1)$.

After the Olympics they drilled down the answers and were very surprised. Who was wrong?
P. P. Gornusha

Geometry helps solve equations

In some cases, instead of transforming the equation, you can do the following: translate the problem into geometric language, and then write the resulting geometric condition in a different way; RESULTS: A SIMPLE EQUATION RESULTS. Now we will consider two such examples, and in each of them the original equation is equivalent to the condition “some points lie on the same line”; By appropriately writing this condition, we obtain a simpler equation, which we will solve.

Problem 1. Solve the equation $\sqrt{15 - 12\cos x} + \sqrt{7 - 4\sqrt{3}\sin x} = 4$, where $0^\circ < x < 90^\circ$.

Solution. Let's give the equation the form:
$$\sqrt{(\sqrt{12})^2 + (\sqrt{3})^2 - 2\cdot\sqrt{12}\cdot\sqrt{3}\cos x} + \sqrt{(\sqrt{3})^2 + 2^2 - 2\cdot\sqrt{3}\cdot2\cdot\cos(90^\circ - x)} = 4.$$ (1)

figure 1 shows a rectangle containing $|AC| = \sqrt{12}, |BC| = 2, ACD = x, DCB = 90^\circ - x; |CD| = \sqrt{3}, |AB| = 4$. The first term on the left side of (1) is equal to $|AD|$, the second is $|DB|$. But since $|AD| + |DB| = |AB|$, it means $D \in [AB]$. Therefore, this equation can be replaced by equation $\sqrt{12}\cdot\sqrt{3}\sin x + \sqrt{3}\cdot2\cdot\sin(90^\circ - x) = 2\cdot\sqrt{12}$ (2)

(since $S_{ACD} + S_{DCB} = S_{ACB}$), or
$$6\sin x + 2\sqrt{3}\cos x = 4\sqrt{3},$$

which is easier to solve than the original one.

We have: $\frac{\sqrt{3}}{2}\sin x + \frac{1}{2}\cos x = 1$, that is $\sin(x + 30^\circ) = 1$, whence $x = 60^\circ$.

Then other things. Strictly speaking, it is required to prove that equation (2) implies equation (1). Let's show it. From equation (2) it follows that $S_{ACD} + S_{DCB} = S_{ACB}$, therefore $|AD| + |DB| = |AB|$, and this is written in equation (1).

Fig. 1.
Fig. 2.
