---
id: 1991-3-o-itak-zadacha-polnostyu-reshena-eb73030e
issue: kvant_1991_3
year: 1991
number: "3"
title: '...So, the problem is completely solved'
authors:
  - О. М.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 32
page_labels: 29-30
lang: en
source: kvant_digital
extraction: vision
content_sha256: e9ae5a14d02dd09462e5ca8aec386ab8f0a331ccbb4a370e9154eaca643f1be3
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/07_o-itak-zadacha-polnostyu-reshena-eb73030e.md
source_content_sha256: 1e1ebbb14d8ec6cb0049d3c0fcd06ddc6e5e9e4d84e761e39478202e63ea752a
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 29⟧

---
running_head:
folio:
---

where $k = \alpha/\beta$ is also a proportionality coefficient. Let's write this equation for different values ​​of $v$ and $U$:

$$v_1^2 = kU_1^2(v_0 - v_1),$$
$$v_2^2 = kU_2^2(v_0 - v_2),$$

where $v_0 = 50$ Hz, $v_1 = 1800/60$ Hz = 30 Hz, $U_1 = 220$ V, $U_2 = 127$ V. Substituting these values ​​and excluding $k$, we obtain the equation of the relative required part $v_2$:

$$v_2^2 + 15v_2 - 750 = 0,$$

where

$$v_2 = 21$$ Hz.

Thus, after connecting to the network through the proprietary formatter, the fan blades will rotate at a speed

$$n_2 = 21 \cdot 60 \text{ об/min} \approx 1260 \text{ об/min}.$$

O. Fatyanov

...So, the problem is completely solved (no letters to the reader)

After the publication of the solution to problem M1194 («Kvant» No. 4, 1990, p. 34), the editor received several letters from readers in which the hypothesis $E$ was proven. Golberg (Leningrad), which refines the statement of this problem. Let us remind you what we are talking about. Here is the formulation of the first (essential for us) point of the problem, compiled by A. Azamov:

M1194. a) From point $M$ inside the straight blade $ABCD$ of area $S$ bissertis MF, MG, MH, ME of triangles AMB, BMC, CMD, DMA are drawn. Prove that the area $S_0$ of the quadrilateral EFGH satisfies the following inequalities:

$$\frac{3}{8} S < S_0 \leq \frac{1}{2} S.$$

E. Golberg proved that $S_0/S = 1 - A/2$, where

$$A = \frac{a^2}{(a+b)(d+a)} + \frac{b^2}{(b+c)(a+b)} + \frac{c^2}{(c+d)(b+c)} + \frac{d^2}{(d+a)(c+d)},$$

and the numbers $a, b, c, d$ are equal to the distances from $M$ to the vertices $A, B, C, D$ of a given straight blade, and, to use this representation, that $S_0/S > 0,4$. His assumption is that the exact infimum for the relative $S_0/S$ is $\sqrt{2} - 1 = 0,41$..., the value achieved when $ABCD$ is a square and $M$ is one of its vertices.

We received the first proof of this proposal from V. Curtoaje (Romania). Using the equality $a^2 + c^2 = b^2 + d^2$ (a consequence of the fact that $ABCD$ is a rectangle), he derived the elegant formula $A = 1 + (a - b + c - d)^2 / (ac + bd)$. From here, using the trigonometric substitution $a = l \sin \alpha$, $b = l \sin \beta$, $c = l \cos \alpha$, $d = l \cos \beta$ (here $l = a^2 + c^2 = b^2 + d^2$), he obtained the estimate $A \leq (2 + c - 1/c) / (1 + c) \leq 2(2 - \sqrt{2})$, where $c = ctg(|\alpha - \beta|/2)$, from which the desired inequality follows. Readers are invited to restore the details of his pictorial point transformations.

Tenth-grader from Leningrad School No. 76 I. Egorova chose the analytical path of proof. She presented an expression for $S_0/S$, similar to those above, as a function of two variables: $x = d/c$ and $t = b/c$ (recall that $a^2 = b^2 + d^2 - c^2$) and explored it for a minimum using arbitrary ones. Space does not allow this rather painstaking research to be reproduced here.

Let us dwell in more detail on two geometric solutions. Both of them are based on the equality $S_0/S = (1 - s/S)/2$, where $s$ is the area of ​​the straight blade $A_1B_1C_1D_1$ (Fig. 1), bounded by straight lines drawn parallel to the sides $ABCD$ through the bases of the bissertis $E, F, G, H$ (this equality was given in the published solution of the problem). And in general solutions it is shown that the ratio $s/S$ can be increased by placing the point $M$ at the vertex of a straight blade, after which it is not at all difficult to prove that in this particular case it will be maximum for a square.

⟦folio 30⟧

---
running_head:
folio:
---

One of the original authors of the “Problem Book «Kvant»” A. Mikhailov (Aizkraukle, Latvia) reasoned differently: he changed not the point, but the rectangle. Namely, assuming that $a \leq b \leq c \leq d$, he replaced the original rectangle ABCD with the rectangle MNCK (see Fig. 2), leaving the point $M$ unchanged. Then the areas $S$, $S_0$ and $s$ are replaced, respectively, by $S' = S_{MNCK}$, $S_0' = S_{\Delta MPQ}$, where MP and MQ are the bisserris of the angles NMC and CMK and $s' = NP \cdot KQ$ (at figure 2 the rectangle of the area $s'$ corresponding to $A_1B_1C_1D_1$ is not shown). We must prove that $S_0/S > S_0'/S'$, i.e. that $s/S < s'/s'$. In the published solution to the problem, it was found that $AE \leq BG$ and $AF \leq DH$. Therefore, $LF \leq NG$, $IF \leq KH$. Hence $NP \geq NG \geq NG - LE = A_1D_1$, $KQ \geq KH \geq KH - IF = A_1B_1$, which means

$$\frac{s'}{S'} = \frac{NP \cdot KQ}{S_{MNCK}} \geq \frac{A_1D_1 \cdot A_1B_1}{S_{ABCD}} = \frac{s}{S'}$$

which is exactly what we needed.

So, it remains to consider that part of the problem when the given point is at the vertex of the rectangle (Fig. 3). This is no longer difficult. Let us present the calculations of A. Mikhailov

$$\frac{S_0'}{S'} = \frac{S_{\Delta MPQ}}{S_{MNCK}} = \frac{MP \cdot MQ \cdot \sin \angle PMQ}{2 \cdot MN \cdot MK} = \frac{\sin \pi/4}{2 \cos(\pi/4 - \alpha/2)} = \frac{1/\sqrt{2}}{\cos \pi/4 + \cos(\pi/4 - \alpha)} = \frac{1}{1 + \sqrt{2} \cos(\pi/4 - \alpha)} \geq \frac{1}{1 + \sqrt{2}} = \sqrt{2} - 1,$$

where $\alpha = \angle CMK$. Equality is achieved only for $\alpha = \pi/4$, i.e., when MNCK is a square.

It is easy to prove that the ratio $s/S$ for the rectangle ABCD and the point $A$ is greater than the analogous value for the embedded ABCD rectangle MNCK and the point $M$. It follows that for a fixed rectangle the minimum $S_0/S$ is achieved when the point $M$ is at its vertex (which, incidentally, was proved by G. Khotsanyan), and is equal, as we have seen, to $1/(1 + \sqrt{2} \cos(\pi/4 - \alpha))$.

O. M.

Amendment
In the conditions of task M1258 (see «Kvant» No. 12 for 1990) in paragraph 6) there was an inaccuracy. Here is the correct wording.
6) Prove that for any set of $n$ numbers on the circle whose sum is positive, one can obtain one and only one set of $n$ non-negative numbers.
The deadline for submitting a solution to this problem has been extended until May 15.
