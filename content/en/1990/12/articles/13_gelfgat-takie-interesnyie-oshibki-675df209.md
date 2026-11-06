---
id: 1990-12-gelfgat-takie-interesnyie-oshibki-675df209
issue: kvant_1990_12
year: 1990
number: "12"
title: Such interesting errors...
authors:
  - Гельфгат И. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 44
page_last: 47
page_labels: 42, 44, 45
lang: en
source: kvant_digital
extraction: vision
content_sha256: b8d6e9e614b7ead121d9637d8ff9e235b4c4464ffa75c4fd4a8b73e499a150d0
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/13_gelfgat-takie-interesnyie-oshibki-675df209.md
source_content_sha256: 1cbf6ab1415fc7551f82ec9a9a590ae17c3a5d648c339e9e7834bbdbb0c271d6
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

Such interesting errors...

Candidate of Physical and Mathematical Sciences
I. GELFGAT

Let's talk about mistakes? Although many of you are probably tired of this conversation in school, we will try to show that it can also be interesting. Traditionally, it will have to end with a moral, but we will try to make the moral not too long and boring.

Let's start with a problem from the well-known and frequently reprinted collection*):

*) Vukhovtsev V.V., Krivchenko V.D., Myakishev G.Ya., Saraeva I.M. Collection of problems in elementary physics. (M., Nauka, 1987.) Problem No. 650.

At the ends of a weightless rod $d=1$ m long, two small balls weighing $m=1$ g each are fixed. The rod is suspended on a hinge so that it can rotate without friction about the vertical axis, passing through its middle. On one spice with a rod two large balls weighing $M=20$ kg each are fixed. The distance between the centers of the large and small balls is $L=16$ cm (Fig. 1). Calculate the period of small oscillations of the described round soft.

At this point we invite you to stop reading and solve the problem yourself. Decided? Now introduce the solution proposed by the authors of the collection:

Each half of the rod with a ball at the end represents a mathematical matrix of length $d/2$, which oscillates in the gravitational field of a large ball. The mathematical matrix in the Earth's gravitational field has a period of small oscillations $T_0=2\pi\sqrt{l/g}$. According to the law of universal gravitation, $mg=GmM_3/R^2$; therefore, $T_0=2\pi\sqrt{lR^2/(GM_3)}$, where $G$ is the gravitational constant, $M_3$ is the mass of the Earth, $R$ is the distance from the matrix to the center of the Earth. Accordingly, in the gravitational field of a large ball, the period of small oscillations of the mathematical matrix of length $l=d/2$ will be equal to $T=2\pi\sqrt{dL^2/(2GM)}\approx 5,4$ h.

It would seem that there could be no better solution. The use of analogues makes it short and graceful. The validity of this analogy is at first

⟦folio 44⟧

---
running_head:
folio:
---

for triangles $OAB_1, OAB_2$:
$$R_{1,2}^2 = (d/2)^2 + (d/2+L)^2 \pm d(d/2+L) \times \cos \varphi.$$

Considering that for small $\varphi$ cos $\varphi = 1 - \varphi^2/2$, we obtain
$$W_p = -GmM(1/(d+L)+1/L) + GmMd(d+2L)(1/L^3 - 1/(L+d)^3)\varphi^2/8.$$
So, in our case
$$W_0 = -GmM(1/(d+L)+1/L),$$
$$\mu = md^2/4,$$
$$k = GmMd(d+2L)(1/L^3 - 1/(L+d)^3)/4.$$
From here we get
$$T_3 = 2\pi \sqrt{\frac{L^3(d+L)^3}{GM(d+2L)(d^2+3dL+3L^2)}}.$$

So which of the answers $-T_2$ or $T_3$ is correct?! Or maybe there is also a fourth, fifth? The clue comes from comparing the two solutions. Which ones? It makes no sense to compare, say, the answers $T_3$ and $T_1$, since in $T_3$ the attraction of common large balls is taken into account, and in $T_1$ only one. But if in formula (3) we discard the term $c R_1$, i.e., we also limit ourselves to taking into account the attraction of the nearby large ball, then, it would seem, we again have to accept $T_1$ for the answer. We advise you to do this calculation yourself - and you will really get the answer, but... the fourth one does not coincide with any of the previous ones:

$$T_4 = 2\pi L \sqrt{\frac{dL}{GM(d+2L)}}.$$

Somehow I don’t respect you again. Why? Let's compare this answer with $T_1$:
$$T_4/T_1 = \sqrt{2L/(d+2L)}$$
Note that this relation tends to

Fig. 3.

s to unity at $L \gg d$. Maybe that's what it's all about? Indeed, for the general matrix near the Earth’s surface, condition $L \gg d$ is satisfied with a huge margin (by $L$ we should then understand the radius of the Earth). Therefore (and only because of this!) during vibrations, the force field can also be considered homogeneous. But when the small ball deviates from the equilibrium position in our problem, both the direction and the magnitude of the gravitational force acting on it changes (although you can check for yourself that the change in the model of the gravitational force is just insignificant - it’s all about changing its direction).

We have already been wrong so many times that to be completely sure it is worth checking the results again. To do this, you can solve the problem based on formula (1), and not on the expression for energy. In this case, we limit ourselves to taking into account the attraction of the nearest large ball. It would be nice to get the expression $T_4$ for the period of the kolbans...

Let the rod deviate from the equilibrium position by a small angle $\varphi$ (Fig. 3). The role of the restoring force is played by the projection of the gravitational force $F$ onto the axis $X$, which coincides with the tangent to the trajectory. The equation of motion has the form
$$ma_x = -F \cos \beta.$$
Considering that $a_x = x''$ and $\beta = 90^\circ - \varphi - \gamma$, we get
$$mx'' = -F \sin (\varphi + \gamma) = -\frac{GmM}{L^2}(\varphi + \gamma).$$

Here we used the fact that for small deviations $R_2 \approx L$ and $\sin (\varphi + \gamma) \approx \varphi + \gamma$. In a uniform gravitational field of the Earth, the term $\gamma$ on the right side of the equation would not appear (compare this with the derivation of the formula for the period of the mathematic matrix in the school textbook). This means that the reality is all about the inhomogeneity of the gravitational field!

Applying the sine theorem to the triangle $OAB_2$ (taking into account the smallness of the angles): $\gamma/\varphi = d/(2L)$, after substituting $\gamma$ into the equation of motion we obtain

⟦folio 45⟧

---
running_head:
folio:
---

$$x'' = -\frac{GM}{L^2} \left(1 + \frac{d}{2L}\right) \varphi = -\frac{GM(d+2L)}{dL^3} x,$$
where $\varphi \approx 2x/d$. From this equation of type (1) a vibration is found that completely coincides with $T_4$. Now there is no longer any doubt that the correct answer for the original problem, taking into account the acceptance of both large balls, is $T_3$. With the values ​​$d$ and $L T_3 \approx 2,7$ h specified in the conditions. The correct answer differs from $T_1$ by half!

The mistake made in the first proposed solution turned out to be, perhaps, even the problem itself. Let us recall that it did not take into account the acceptance of a “distant” large ball (which is permissible only for $d \gg L$) and the inhomogeneity of the gravitational field (which is permissible, on the contrary, for $d \ll L$). As a result, the resulting answer $T_1$ for any values ​​$d$ and $L$ turned out to be incorrect!

Morality. Firstly, solving a good school problem (as well as a scientific problem) does not end with obtaining the final formula and substituting numerical values ​​into it. The result must be tested “for strength” in as many ways as possible, and be treated very strictly. Even great scientists are not protected from mistakes, and the problem may turn out to be deeper than even its author thinks.

Secondly, the analytical method is an excellent method, but it must be handled with care. Sometimes the fundamental differences between tasks are not as striking as the similarities between them.

In a word, if you have slight doubts about the correctness of the solution or the meaning of the result is unclear, try solving the problem in a different way and compare the results.
