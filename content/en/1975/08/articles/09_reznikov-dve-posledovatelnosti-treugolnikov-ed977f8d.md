---
id: 1975-8-reznikov-dve-posledovatelnosti-treugolnikov-ed977f8d
issue: kvant_1975_8
year: 1975
number: "8"
title: Two sequences of triangles
authors:
  - Резников А. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 49
page_labels: 46-47
tag: QXB0
lang: en
source: kvant_digital
extraction: vision
content_sha256: d5e783782ed006986dc8d1bd73ba376ed45f42f359d2a014801010097e81459a
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/09_reznikov-dve-posledovatelnosti-treugolnikov-ed977f8d.md
source_content_sha256: 898b0404e7e7d6dd6e003ed598110b739f67650461693980d35a87a29f5169e3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Consider an arbitrary triangle $ABC$. By $A_1B_1C_1$ we denote a triangle whose vertices are the points of contact of the circle inscribed in $ABC$ with its sides (Fig. 1). Similarly, for triangle $A_1B_1C_1$ we define triangle $A_2B_2C_2$, etc. Thus, we obtain a sequence of triangles inscribed into each other

$$ABC, A_1B_1C_1, A_2B_2C_2, \dots$$

(1)

We define another sequence of triangles as follows: by $A^{(1)}B^{(1)}C^{(1)}$ we denote a triangle whose vertices are the points of intersection of the bisectors of the triangle $ABC$ with the circumscribed circle. Similarly, for triangle $A^{(1)}B^{(1)}C^{(1)}$ we define triangle $A^{(2)}B^{(2)}C^{(2)}$, etc. Thus, we obtain a sequence of triangles

$$ABC, A^{(1)}B^{(1)}C^{(1)}, A^{(2)}B^{(2)}C^{(2)}, \dots$$

(2)

In this note we will study some properties of sequences (1) and (2). Many of our statements

Fig. 1.

We don’t prove it. We hope you will do this on your own.

1. It is easy to express the angles of triangle $A_1B_1C_1$ in terms of the angles of the original triangle. For example, $\hat{A}_1 = 90^\circ - \frac{1}{2}\hat{A}$. Likewise, $\hat{A}_2 = 90^\circ - \frac{1}{2}\hat{A}_1$ and in general $\hat{A}_n = 90^\circ - \frac{1}{2}\hat{A}_{n-1}$.

In other words, the sequence of angles $A, A_1, A_2, \dots, A_n, \dots$ will process the arithmetic-geometric progression. Such progressions are described in the article by Ya. N. Sukonika in «Kvant» No. 1 for this year. Using the result of this article, we get the following expression:

$$\hat{A}_n = 60^\circ + \left(-\frac{1}{2}\right)^n (\hat{A} - 60^\circ).$$

(3)

The angles of triangle $A^{(1)}B^{(1)}C^{(1)}$ are equal to the corresponding angles of triangle $A_1B_1C_1$ (check!). This means that sequences (1) and (2) are sequences of similar triangles.

From formula (3) it follows that if $A \neq 60^\circ$, then all $\hat{A}_n \neq 60^\circ$, and $\lim_{n \to \infty} \hat{A}_n = 60^\circ$. Likewise $\lim_{\hat{B}_n \to 60^\circ} \hat{B}_n = 60^\circ$ and the same is true for angles $\hat{A}^{(n)}, \hat{B}^{(n)}, \hat{C}^{(n)}$.

2. Let $p_n, S_n R_n, r_n$ be the half-perimeter, area, and circumscribed and inscribed circle radii of the triangle $A_nB_nC_n$, respectively. The values ​​$p^{(n)}, S^{(n)}, R^{(n)}, r^{(n)}$ for a triangle are determined similarly

⟦folio 47⟧

$A^{(n)}B^{(n)}C^{(n)}$ and $p_0, S_0, R_0, r_0$ for the original triangle $ABC$. Obviously $R^{(n)}=R_0, R_n=r_{n-1}$.

Let's prove that

$$S_n = \frac{1}{2} \frac{R_n}{R_{n-1}} S_{n-1}. \tag{4}$$

It is enough to prove that

$$S_1 = \frac{1}{2} \cdot \frac{r_0}{R_0} S_0. \tag{4'}$$

Proof. It is easy to see (see Fig. 1) that

$$S_{A_1OB_1} = \frac{1}{2} r_0^2 \sin B_1OA_1 = \frac{1}{2} r_0^2 \sin \hat{C},$$

$$S_{B_1OC_1} = \frac{1}{2} r_0^2 \sin \hat{A},$$

$$S_{C_1OA_1} = \frac{1}{2} r_0^2 \sin \hat{B}.$$

Therefore $S_1 = \frac{1}{2} r_0^2 (\sin \hat{A} + \sin \hat{B} + \sin \hat{C})$. But according to the theorem of sines $AB = 2R_0 \sin \hat{C}, BC = 2R_0 \sin \hat{A}, CA = 2R_0 \sin B$. Therefore, $\sin \hat{A} + \sin \hat{B} + \sin \hat{C} = p_0/R_0$. Thus,

$$S_1 = \frac{1}{2} r_0^2 \cdot \frac{p_0}{R_0} =$$

$$= \frac{1}{2} \cdot \frac{r_0}{R_0} r_0 p_0 = \frac{1}{2} \frac{r_0}{R_0} S_0.$$

3. Let us prove that the sequence $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ is age-dependent.

Because

$$S_0 = 2 R_0^2 \sin \hat{A} \sin \hat{B} \sin \hat{C},$$

$$S^{(1)} = 2 R_0^2 \cos \frac{\hat{A}}{2} \cos \frac{\hat{B}}{2} \cos \frac{\hat{C}}{2}^*),$$

then the inequality $S^{(1)} \geq S_0$ is equivalent to the inequality

$$\sin \frac{A}{2} \sin \frac{\hat{B}}{2} \sin \frac{\hat{C}}{2} \leq \frac{1}{8}. \tag{5}$$

Let us prove inequality (5). Using what

$$\hat{C} = 180^\circ - (\hat{A} + \hat{B}),$$

Let's transform (5) like this:

$$\cos \hat{A} + \cos \hat{B} - \cos (\hat{A} + \hat{B}) \leq \frac{3}{2}$$

or

$$2 \cos \frac{\hat{A} + \hat{B}}{2} \cos \frac{\hat{A} - \hat{B}}{2} - 2 \cos^2 \frac{\hat{A} + \hat{B}}{2} -$$

$$-\frac{1}{2} \leq 0,$$

$$-2 \left( \cos \frac{\hat{A} + \hat{B}}{2} - \frac{1}{2} \cos \frac{\hat{A} - \hat{B}}{2} \right)^2 -$$

$$-\frac{1}{2} \left( 1 - \cos^2 \frac{\hat{A} - \hat{B}}{2} \right) \leq 0. \tag{5'}$$

The last inequality is obvious. From (5') it follows that the equality in (5) occurs only in the case when all angles of the triangle are equal to $60^\circ$. Since triangles $A_1B_1C_1$ and $A^{(1)}B^{(1)}C^{(1)}$ are similar and the similarity coefficient is $\frac{R_0}{r_0}$, then

$$S^{(1)} = \frac{1}{2} \frac{R_0}{r_0} S_0 \tag{6}$$

(see formula 4'). But since $S^{(1)} \geq S_0$, this implies the well-known inequality $R_0 \geq 2r_0$.

Since the sequence $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ is age-related,

Since the sequence $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ is age-related,

4. It can be proven that for the sequence of half-perimeters $p_0, p_1, p_2, \ldots$ the following inequality holds:

$$p_n \leq \frac{1}{2} p_{n-1}. \tag{7}$$

As before, it is enough to prove (7) for $n=1$:

$$p_1 \leq \frac{1}{2} p_0. \tag{7'}$$
