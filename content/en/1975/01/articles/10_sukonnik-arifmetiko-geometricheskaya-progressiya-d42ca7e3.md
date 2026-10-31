---
id: 1975-1-sukonnik-arifmetiko-geometricheskaya-progressiya-d42ca7e3
issue: kvant_1975_1
year: 1975
number: "1"
title: Arithmetic-geometric progression
authors:
  - Суконник Я. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 40
page_labels: 36-38
tag: PPLZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: b50f96b855d123eb0ea74e5476d0f72daeb7f742c6fbac4f4a525dc83e600ba2
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/10_sukonnik-arifmetiko-geometricheskaya-progressiya-d42ca7e3.md
source_content_sha256: 6b0588f272ef65c305545680949173fb6cbee224cc9251557178811ee51f78bc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦rubric⟧ MATHEMATICAL CIRCLE

## Arithmetic-geometric progression
Y. N. Sukonnik

Mathematics can be studied in different ways. You can listen to lectures or take a thick book and read it in a row: definitions, theorems, proofs. Or you can act more actively: read the definitions and statements of the theorems, put the book aside and come up with proofs yourself. The first method makes it possible to move faster at first. But only the second method allows you to deeply understand mathematical theory, remember it for a long time and learn to apply it. Therefore, it is this method—the independent discovery of old truths—that is often used in mathematical seminars, schools, and clubs.

It is precisely this kind of active work of readers that the articles published in the “Mathematics Circle” section are designed for. Typically, these articles are a series of problems united by a common topic or solution method. Some of them are solved in the text, but most - both easy and difficult - are left for the reader to decide on their own. Sometimes short solutions to these problems (or instructions and answers) are placed in the same issue, but more often - in one of the next issues of the magazine on the last pages.

As a rule, our “Math Club” is available to students in grades 8-9, and sometimes even 7. Please send letters with comments and suggestions regarding this section with the note “Mathematics Circle” on the envelope.

Many participants in the All-Union Olympiad maintain regular correspondence with the Mathematical Circle.

⟦column⟧

This article examines one sequence that can be roughly called *arithmetic-geometric progression*; it is given by the following recurrence relation:

$$u_1 = a_1, \quad u_{n+1} = qu_n + d, \qquad (1)$$

where $q$ and $d$ are constant parameters. Putting $q = 1$ in (1), we get an *arithmetic* progression

$$u_1 = a_1, \quad u_{n+1} = u_n + d,$$

putting $d = 0$, - *geometric*:

$$u_1 = a_1, \quad u_{n+1} = qu_n.$$

(This explains why we called sequence (1) an arithmetic-geometric progression. By analogy, we will say that $q$ is the denominator, and $d$ is the difference of the arithmetic-geometric progression.)

Examples of arithmetic-geometric progressions

a) $1, \ \dfrac{3}{2}, \ \dfrac{7}{4}, \ \dfrac{15}{8}, \ \dfrac{31}{16}, \ \cdots$

$$\left(u_1 = 1, \ q = \frac{1}{2}, \ d = 1\right);$$

b) $-1, \ \dfrac{3}{2}, \ \dfrac{1}{4}, \ \dfrac{7}{8}, \ \dfrac{9}{16}, \ \cdots$

$$\left(u_1 = -1, \ q = -\frac{1}{2}, \ d = 1\right).$$

The idea to talk about such sequences was prompted by problem M97, which was published in «Kvant» No. 8 for 1971 (in the “Problem Book «Kvant»”). Here is her condition (slightly modified):

⟦folio 36⟧

*In the trapezoid $AA_1B_1B$ with bases $AB = a$ and $A_1B_1 = a_1$ $(a < a_1)$ a segment $A_2B_2$ is drawn connecting the midpoints of the diagonals. In the resulting trapezoid $AA_2B_2B$, the segment $A_3B_3$ is again drawn, connecting the midpoints of the diagonals, and so on. Find the length of the segment $A_{n+1}B_{n+1}$.*

On figure 1 the trapezoid $AA_nB_nB$ is depicted - here $AB = a$, $CD$ is the middle line of the trapezoid, $A_{n+1}$ and $B_{n+1}$ are the midpoints of the diagonals $A_nB$ and $AB_n$. It is clear that points $A_{n+1}$ and $B_{n+1}$ lie on $CD$. Denoting the lengths of the segments $A_nB_n$ and $A_{n+1}B_{n+1}$ by $a_n$ and $a_{n+1}$, we obtain

$$a_{n+1} = |A_{n+1}B_{n+1}| =$$
$$= |A_{n+1}D| - |B_{n+1}D| = \frac{1}{2}\,a_n - \frac{1}{2}\,a,$$

and, therefore, the lengths of the segments $A_nB_n$ form precisely an *arithmetic-geometric progression*.

An arithmetic-geometric progression has features of both arithmetic and geometric progressions. Let us derive the formula for its general term.

Let in relation (1) $q \neq 1$ (and $d \neq 0$). Adding the expression $\dfrac{d}{q-1}$ to both sides of (1), we obtain

$$u_{n+1} + \frac{d}{q-1} = q\left(u_n + \frac{d}{q-1}\right).$$

Considering that this relation is recurrent, we write similar equalities for $k = n+1, n, \ldots, 2$:

$$u_{n+1} + \frac{d}{q-1} = q\left(u_n + \frac{d}{q-1}\right),$$

$$u_2 + \frac{d}{q-1} = q\left(a_1 + \frac{d}{q-1}\right).$$

By multiplying the written equalities and reducing the same factors, we obtain *the formula for the general term of the arithmetic-geometric progression*

$$\boxed{u_{n+1} = q^n\left(a_1 + \frac{d}{q-1}\right) + \frac{d}{1-q}.}\qquad(2)$$

⟦column⟧

⟦figure⟧
Fig. 1.

In problem M97 $a_{n+1} = \dfrac{1}{2}\,a_n - \dfrac{1}{2}\,a$, that is $q = \dfrac{1}{2}$, $d = -\dfrac{1}{2}\,a$; That's why

$$a_{n+1} = |A_{n+1}B_{n+1}| = \frac{1}{2^n}\,(a_1 + a) - a.$$

Let us now formulate some basic properties of the arithmetic-geometric progression (we leave their proofs to the readers).

$1^\circ$. Arithmetic-geometric progression (1) is a *second-order recurrent sequence*\*) and is given by the equation

$$u_{n+1} = (q+1)\,u_n - qu_{n-1}.\qquad(3)$$

In particular, for $q = 1$ we obtain the characteristic property of the arithmetic progression

$$u_n = \frac{u_{n-1} + u_{n+1}}{2}.$$

Corollary: The denominator $q$ of an arithmetic-geometric progression is determined by the formula

$$q = \frac{u_{n+1} - u_n}{u_n - u_{n-1}}.\qquad(4)$$

$2^\circ$. The difference $d$ of an arithmetic-geometric progression is defined

---

\*) The sequence $u_1, u_2, \ldots, u_n, \ldots$ is called a *return sequence of $k$th order* if there is a natural number $k$ and numbers $a_1, a_2, \ldots, a_k$ such that, starting from some number $N$ and for all subsequent numbers $m \geqslant N$
$$u_{m+k} = a_1u_{m+k-1} + a_2u_{m+k-2} + \ldots + a_ku_m.$$
The last relation is called *reciprocal equation of $k$th order*.

⟦folio 37⟧

according to the formula

$$d = \frac{u_n^2 - u_{n-1}\cdot u_{n+1}}{u_n - u_{n-1}}. \qquad (5)$$

In particular, if $d = 0$ (and $q \neq 1$), we obtain the characteristic property of the geometric progression

$$u_n = \sqrt{u_{n-1}\cdot u_{n+1}}.$$

$3^\circ$ (*characteristic property of arithmetic-geometric progression*). The sequence $\{a_n\}$, where $a_n = u_{n+1} - u_n$, is a geometric progression with the same denominator $q$, that is

$$|u_{n+1} - u_n| =$$
$$= \sqrt{|u_n - u_{n-1}|\cdot|u_{n+2} - u_{n+1}|}. \qquad (6)$$

$4^\circ$. Subsequence

$$S_1 = u_1, \quad S_2 = u_1 + u_2, \quad \ldots,$$
$$S_n = u_1 + \ldots + u_n,$$
$$S_{n+1} = S_n + u_{n+1}, \quad \ldots$$

*partial sums* of terms of an arithmetic-geometric progression is a third-order reciprocal sequence and is given by the following equation:

$$S_{n+1} = (q+2)\,S_n -$$
$$- (2q+1)\,S_{n-1} + qS_{n-2}. \qquad (7)$$

$5^\circ$. If the sequence of partial sums $S_1$, $\ldots$, $S_n$, $\ldots$ is an arithmetic-geometric progression, then the sequence $u_1, \ldots, u_n \ldots$ is a geometric progression.

Remark. From the formula for the general term of the arithmetic-geometric progression (see formula (2)) it follows that

a) for $|q| < 1$ the arithmetic-geometric progression *converges* (and for $0 \leqslant q < 1$ - *monotonically*) to the number

$$A = \lim_{n \to \infty} u_n = \frac{d}{1-q};$$

b) at $|q| \geqslant 1$ the arithmetic-geometric progression *diverges*.

In particular, by directing the number $n$ in problem M97 to infinity, we obtain that in the limit

$$b = \lim_{n \to \infty}|A_{n+1}B_{n+1}| = \left|\frac{-\dfrac{1}{2}\,a}{1 - \dfrac{1}{2}}\right| = a.$$

⟦column⟧

(Interestingly, if in problem M97 instead of the condition $a < a_1$ we require $a > a_1$, then

$$|A_{n+1}B_{n+1}| = -\frac{1}{2}\,a_n + \frac{1}{2}\,a,$$

that is

$$|A_{n+1}B_{n+1}| = \left(-\frac{1}{2}\right)^n\left(a_1 - \frac{a}{3}\right) + \frac{a}{3},$$

And

$$b = \lim_{n \to \infty} A_{n+1}B_{n+1} = \frac{a}{3}\Bigg).$$

Familiarity with the arithmetic-geometric progression sometimes helps in solving some geometric problems. Consider, for example, the following problem:

*The altitudes of the acute triangle $A_1B_1C_1$ are extended until they intersect with the circumcircle at points $A_2$, $B_2$, $C_2$, respectively, which serve as the vertices of the acute triangle $A_2B_2C_2$. The altitudes of the triangle $A_2B_2C_2$ are extended to the intersection with the circumcircle at points $A_3$, $B_3$, $C_3$, respectively, which serve as the vertices of the acute triangle $A_3B_3C_3$, and so on - up to the triangle $A_{n+1}B_{n+1}C_{n+1}$ inclusive. Find the angles of triangle $A_{n+1}B_{n+1}C_{n+1}$, assuming the angles of triangle $A_1B_1C_1$ are known.*

Solution. figure 2 shows a circle and the acute triangles $A_nB_nC_n$ and $A_{n+1}B_{n+1}C_{n+1}$ inscribed in it. Let's express the angle $A_{n+1}$ through the angle $A_n$:

$$\angle A_{n+1} = \angle B_{n+1}A_{n+1}C_{n+1} =$$
$$= \angle B_{n+1}A_{n+1}A_n + \angle A_nA_{n+1}C_{n+1} =$$
$$= \angle B_{n+1}B_nA_n + \angle A_nC_nC_{n+1} =$$
$$= \left(\frac{\pi}{2} - \angle A_n\right) +$$
$$+ \left(\frac{\pi}{2} - \angle A_n\right) = \pi - 2\angle A_n,$$

that is

$$\angle A_{n+1} = -2\angle A_n + \pi$$

and the sequence of angles $A_1$, $A_2$, $\ldots$, $A_{n+1}$ forms an arithmetic-geometric progression. Using formula (2) we find

$$\angle A_{n+1} = (-2)^n\cdot\left(\angle A_1 - \frac{\pi}{3}\right) + \frac{\pi}{3}.$$

⟦folio 38⟧
