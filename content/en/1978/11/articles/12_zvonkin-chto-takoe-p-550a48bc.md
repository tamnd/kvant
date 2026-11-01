---
id: 1978-11-zvonkin-chto-takoe-p-550a48bc
issue: kvant_1978_11
year: 1978
number: "11"
title: What is pi?
authors:
  - Звонкин А. К.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 30
page_last: 32
page_labels: 28-30
tag: WWWW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8e3cb99205bd7c73c56038747fcb796d76ba94fa6c409b50995c376522c5000e
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/12_zvonkin-chto-takoe-p-550a48bc.md
source_content_sha256: 2ce234aa08060ceba7e3b12d8dd85bdbc33951503b8778c40e4a7873b7f0dca0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

A. Zvonkin

What is pi?

The number π first appears in school in the 5th grade - in the textbook “Matematika 5” (p. 59), it is discussed in the textbook “Geometry 8” (p. 118) and in the textbook “Algebra and the beginnings of analysis 9” (p. 33). However, there is no proof of the existence of the number π in these textbooks. We present it in this article.

Section length

The length of a segment is the distance between its ends (“Geometry 6”, paragraph 7).

In practice, the lengths of segments are measured using a measuring device - a ruler, tape measure, etc. Theoretical analysis of this process leads to a mathematical construction called the measurement process, and the wave deserves a separate statistic.

In short, the measurement process is as follows:

1) an arbitrary segment is selected - a unit of length;
2) a unit of length is postponed in the measured segment as many times as possible;
3) if at the same time a remainder remains from the measured segment, then the unit of length is divided into equal parts and the resulting part of the unit is deposited in the remainder;
4) and so on.

The most interesting thing here is hidden in the fourth paragraph. It turns out that the measurement process can end in a finite number of steps (in this case, the measured segment and the unit of length are called commensurate), or it can continue indefinitely.

Thus, even when measuring the length of a segment, the passage to the limit may occur. It is quite natural that we will need it when determining the circumference. In this case, we will assume that we already know what the length of a segment is and, thereby, the period of a polygon.

The reader may ask: is it possible to measure the circumference of a circle in the following way - wrap it with thread, then unroll the thread and attach it to a ruler? Unfortunately, turning this practical method of measurement into a strictly mathematical construct requires rather sophisticated mathematical tools that go beyond the scope of the school curriculum.

Bad definitions
circumference

A theorem can be true or false—a definition can be neither true nor false. A definition may be against you (if there are no objects that satisfy it), incorrect (if it does not define what we wanted), and unsatisfying.

We now give several definitions of the circumference of a circle. All definitions will be constructed according to the same scheme: in one way or another, a sequence (Πn) of polygons inscribed in a circle will be selected and the length of the circle will be called $L = \lim_{n \to \infty} P_n$, where $P_n$ is the perimeter of the polygon $\Pi_n$. The definitions will differ from each other by different choices sequentially ($\Pi_n$).

Let's first give some bad definitions.

“On the limit” 1. $L = \lim_{n \to \infty} P_n$, where ($\Pi_n$) is the product

⟦folio 29⟧

Fig. 1.

a free sequence of inscribed polygons.

This definition is in no way suitable. For example, if for all $n$ the polygon $\Pi_n$ is the same square inscribed in a circle, then $(P_n)$ is a constant sequence, and as the length of the circle we get the perimeter of the inscribed square. If the sequence $(\Pi_n)$ contains squares and regular triangles in turn, then the sequence $(P_n)$ has no limit (prove!).

Let us denote by $\varphi(n)$ the number of sides of the polygon $\Pi_n$, and by $\psi(n)$ the length of its longest side.

《Definition》2. $L = \lim_{n \to \infty} P_n$, where $(\Pi_n)$ is a sequence such that $\lim_{n \to \infty} \varphi(n) = +\infty$*).

It turns out that this definition is non-oretic. figure 1 shows a sequence $(\Pi_n)$ that satisfies “definition” 2 and such that $\lim_{n \to \infty} P_n$ does not coincide with what we would like to think of as the circumference. It is also not difficult to construct an example of the sequence $(\Pi_n)$ satisfying the “definition”*

*) That is, $\varphi(n)$ standard as large as possible.

Fig. 2.

2, for which $\lim_{n \to \infty} P_n$ does not exist (construct it!).

《Definition》3. $L = \lim_{n \to \infty} P_n$, where $(\Pi_n)$ is a sequence such that $\lim_{n \to \infty} \varphi(n) = +\infty$ and $\lim_{n \to \infty} \psi(n) = 0$.

Unfortunately, this option is not suitable either. On figure 2 there is a sequence $(\Pi_n)$ satisfying “definition” 3 and such that $\lim_{n \to \infty} P_n = 0$. As in “definition” 1, 2, it is easy to construct a $(\Pi_n)$ such that $\lim_{n \to \infty} P_n$ does not exist.

Good definitions
circumference

Definition 4. $L = \lim_{n \to \infty} P_n$, where $(\Pi_n)$ is a sequence such that for all $n$ the center of the circle lies inside $\Pi_n$ and $\lim_{n \to \infty} \varphi(n) = +\infty$, $\lim_{n \to \infty} \psi(n) = 0$.

It can be proven that for any $(\Pi_n)$ satisfying “definition” 4, $\lim_{n \to \infty} P_n$ exists, and it does not depend on the choice of the original sequence $(\Pi_n)$. However, this is very difficult to prove. Therefore definition 4 is inconvenient. In addition, it is not clear: there are a lot of heterogeneous requirements in it.

⟦folio 30⟧

Definition 5. $L = \lim_{n \to \infty} P_n$, where $\Pi_n$ is a regular inscribed $n$-gon (cf. “Algebra and the beginnings of analysis 9”, paragraph 33).

Unlike definitions 1-3, in this case the real limit exists. Let's prove it.

Theorem. The sequence $(P_n)$ returns and is limited.

We will divide the proof into a number of steps, which we will present as problems. When solving them, it is important to do without trigonometry, since the definition of trigonometric functions is based on the concept of circumference.

Task 1.

1. Right triangles $ABC$ and $ADC$ have a common square $AC$ and $BAC < DAC$. Prove that $|AB| < |AD|$.

2. For right triangles, $ABC$ and $A_1B_1C_1$ have hypotenuses $AB$ and $A_1B_1$ congruent and $BAC < B_1A_1C_1$. Prove that $|A_1C_1| < |AC|$.

3. The acute central angle $AOB$ is divided by radii $OM_1, OM_2, \dots, OM_{k-1}$ into $k$ congruent parts (Fig. 3). Point $C$ is the projection of point $A$ onto $[OB]$, point $N_i$ is the projection of point $M_i$ onto $[AC]$ ($i = 1, 2, \dots, k - 1$). Prove that $|AN_1| < |N_1N_2| < \dots < |N_{k-1}C|$.

4. Prove that $P_{n+1} > P_n$.

5. Prove that if one convex polygon lies inside another, then the perimeter inside it is smaller than the perimeter of the outside one. Show that without the convexity condition this statement is false.

So, the sequence $(P_n)$ returns (problem 4) and is bounded (for any $n$ the perimeter $P_n$ is less than the perimeter of the described square - problem 5). According to the Weierstrass theorem*) it has a limit. This means that Definition 5 is correct: every circle has a (unique) length.

Number π

Let us denote the length of the circle by $L$, its diameter by $d$, the radius by $r$, and the side length of a regular inscribed $n$-gon by $a_n$.

Theorem. The relation $\frac{L}{d}$ is the same for all circles.

Since

$$\frac{L}{d} = \lim_{n \to \infty} \frac{P_n}{d} = \lim_{n \to \infty} \frac{na_n}{2r} = \frac{1}{2} \lim_{n \to \infty} \left( \frac{a_n}{r} \right),$$

it is enough to prove that the relation $\frac{a_n}{r}$ is the same for all circles, and this follows from the similarity of triangles, images on figure 4.

It is this very ratio of the circumference to the diameter that is usually denoted in Greek by the letter π.

The letter π is the first letter of the Greek word περιphera (“circle”). This notation was first used in 1706 by the English mathematician W. Jones, but it became generally accepted after L. Euler began to systematically use it (starting in 1736).

*) “Algebra and principles of analysis 9”, paragraph 32.

Fig. 3.

Fig. 4.
