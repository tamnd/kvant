---
id: 1986-4-yaglom-genetika-populyatsiy-i-geometriya-ce323c18
issue: kvant_1986_4
year: 1986
number: "4"
title: Population genetics and geometry
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8-10
tag: VTK7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 363140cf0da8d7b739cef633e3efd6c165ea395619313c383d04bd0576f6d1c0
prompt_sha256: draft-1
translated_from: content/ru/1986/04/articles/05_yaglom-genetika-populyatsiy-i-geometriya-ce323c18.md
source_content_sha256: 24e2b59760121aacd7cea509a557ee74ac09be60f1f9d488e11bfa03a1e8b773
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

Crossing with "hybrids". Let now the individuals of the population $P = P(d, h, r)$ cross only with hybrid individuals H. Reasoning as in the first example, we obtain that half of the offspring will receive the gene $G$ from the hybrid parent, and the other half - $g$, and in each of these halves the individuals whose second gene (inherited from the parent from the population $P$) will be $G$, will make up the share $\Gamma$, and individuals with the second gene $g$ will make up the share $\gamma$. Therefore, for the ancestral population $P'(d', h', r')$ we have

$$d' = \frac{\Gamma}{2} = \frac{d}{2} + \frac{h}{4}, \quad h' = \frac{\Gamma}{2} + \frac{\gamma}{2} = \frac{1}{2}, \quad r' = \frac{\gamma}{2} = \frac{r}{2} + \frac{h}{4}.$$

Comparing the coordinates of points $P'(\Gamma/2, 1/2, \gamma/2)$ and $P_0(\Gamma, 0, \gamma)$, we are convinced that point $P'$ is obtained from $P$ with the center $H$ and coefficient 1/2 (Fig. 4). This means that the transformation $f_2$, which translates $P$ into $P'$, can be represented as a composition of projection in the direction $h$ onto a straight line connecting the midpoints $M$ and $N$ side DH and HR of our triangle, and a geometry with the center in the midpoint $T$ of the segment MN and the coefficient 1/2.

From this representation it is immediately clear that the hereditary transformation $f_2$ immediately transforms the triangle DHR (the set of all populations) into the middle line MN (the set of populations half consisting of hybrids) and has a single fixed point (a stable population that retains its composition) - the point $T$ (1/4,

![Graph](image)

Fig. 4.

Successive generations $P'$, $P'' = f_2(P')$, ... are represented by points of the line MN; each of them goes into the next step with center $T$ and coefficient 1/2 (of course, there is no need to design them anymore). Therefore, populations $P'$, $P''$, ... indefinitely approach the stable population $T$.

Problem 3. Let $f_{abc}$ be a hereditary transformation resulting in the crossing of population $P(d, h, r)$ with a fixed population $P(a, b, c)$ (of course, $a,b,c \geq 0$ and $a+b+c=1$); for example, $f_{100}$ and $f_{010}$ are the transformations $f_1$ and $f_2$ discussed in the text. Write down the formulas for the transformation $f_{abc}$ and find out its geometric meaning, find stable populations. What happens when the transformation $f_{abc}$ is repeated many times?

Panmixia.
Hardy-Weinberg law

The hereditary transformations $f_1$ and $f_2$ discussed above are primarily of an educational nature. The hereditary transformation $P' = f(P)$ plays much greater significance for population genetics, where the population of descendants $P'$ is obtained in the proposition of a purely random formation of pairs from the population $P$ - this method of formation of mating pairs is biologically called *panmixey* (complete mixing of individuals of the population). In this case, it is believed that in the female and male parts of the population $P(d, h, r)$ the proportions of individuals of each type D, H, R are the same (and, of course, equal to $d, h, r$). It is clear that the scientific selection of mating pairs and the subsequent selection of a pair of genes transmitted to the descendant (one gene from the parent) can be replaced by a direct random selection of a pair of genes from the genophone of the population $P$. In this case, the frequency with which pairs $GG$ will arise (that is, the proportion of $d'$ dominant individuals in the hereditary population $P'$) will be equal to $\Gamma^2$, the frequency of pairs $Gg$ and $gG$ (the proportion of $h$ hybrid individuals) will be $2\Gamma\gamma$, and pairs $gg$ (proportion of $r'$ resess individuals) - $\gamma^2$. So,

$$d' = \Gamma^2 = (d + h/2)^2, \quad h' = 2\Gamma\gamma = 2(d + h/2)(h/2 + r), \quad r' = \gamma^2 = (h/2 + r)^2$$

(note that $d' + h' + r' = (\Gamma + \gamma)^2 = 1$).

The formulas in the framework express one of the basic laws of population

⟦folio 9⟧

genetics - the so-called Hardy-Weinberg law, with which literally any presentation of this discipline, which is so important today, begins; they show how the composition of the population changes under the condition of “true mixing” - in the absence of any additional factors regulating the formation of mating pairs.

Let us find out the geometric meaning of the transformation $f$ (that is, the Hardy-Weinberg law). Let us note, first of all, that the composition of the gene pool of the population $P'$ and $P$ is the same, since $\Gamma' = d' + h'/2 = \Gamma^2 + \Gamma\gamma = \Gamma(\Gamma + \gamma) = \Gamma$.

As we already know, this means that the points $P$ and $P'$ lie on a straight line perpendicular to the side $DR$. Let us now put $DP_0 = x$ (Fig. 5), then $\gamma = r_0 = x \sin 60^\circ = x\sqrt{3}/2$, therefore,

$$h' = 2\Gamma\gamma = 2(1 - \gamma)\gamma = \sqrt{3}x(1 - x\sqrt{3}/2).$$

As is known, in the usual (rectangular) coordinate system (Fig. 5) this equation for $0 \leq x \leq DR = 2/\sqrt{3}$ defines another P paraboles; Note that in our “coordinates relative to the triangle $DHR$” it has the equation $h^2 = 4dr$ (since $h'^2 = 4\Gamma^2\gamma^2 = 4d'r'$). It is easy to check that this parabola passes through the points $D, R$ and $T$ (the middle of the midline $MN$) and touches the lines $DH, RH$ and $MN$ at these points.

Thus, the point $P' = f(P)$ lies at the intersection of the perpendicular $DR$ drawn through $P$ and the indicated paraboles, in other words,

$$\begin{array}{c}
H \\
M \\
T \\
R \\
P'
\end{array}$$

Fig. 5.

the transformation $f$ is a parallel projection of the triangle $DHR$ onto the arc $\Pi$ parabolas in the direction $h$.

Hence, P are immediately fixed, that is, all populations $P$ ($d, h, r$) are such that $h^2 = 4dr$ are stable under the hereditary transformation $f$. The latter result, in a certain sense, is paradoxical: it follows that in a sufficiently large population, in the absence of mutation and (artificial or natural) selection, evolution always occurs in one step. Further crossing of individuals under such conditions does not change the relative composition of the population: if $P' = f(P)$, $P'' = f(P')$, etc., then $P' = P'' = \dots$ However, as a result of life, idealized conditions for crossing never take place: they are always fulfilled only more or less approximately. Therefore, the Hardy-Weinberg law specifies only a first approximation to the implementation of the crossing conditions, which cannot be achieved with the help of further conditions of the mathematical model (see, for example, problem 4). Of course, the results obtained with their help must be compared each time with those observed over nature.

Problem 4. Let the boundaries of the pair in the population $P$ form purely by chance (as in panmixini), but the mushrooms differ in the life of the hereditary population, only the $k$ part will remain alive (with $k > 1$ this means that only the $(1/k)$ part of individuals of types $D$ and $R$ will be preserved). Describe the corresponding geometric transformation of triangle $DHR$. How does it work at $k = 0$ (complete extinction of mushrooms) and at $k = \infty$ (complete extinction of individuals $D$ and $R$)?

The Hardy-Weinberg law was independently discovered in 1908 in Cambridge by the young English mathematician Godfrey Harold Hardy and in Vienna by the physician Wilhel Weinberg. (Glorious historians of science have established that five years ago the same law - in several other forms - was indicated by the English biologist W. E. Castle, whose work, one

⟦folio 10⟧

however, it was not replaced in any way.) It is interesting to note that the outstanding specialist in the field of number theory G.H. Hardy is a militant adept of “number” science: in his scientific authorography “Apology of a Mathematician” (unfortunately, this interesting book has not been translated into Russian) he temperamentally proves the superiority of bright and rich in ideas “number” mathematics over “applied” science, completely undeservedly seemed boring to him; Well, Hardy's course in mathematical analysis is provocatively called “A Course in Numeracy.” However, today more than 90% of all mentions of Hardy’s name in scientific and educational literature are associated not with his outstanding works of theoretical content, but with his only youthful “sin” - with the applied work performed in his youth on population genetics, the content of which we have just outlined.

Let's talk about the future

Above we looked at the simplest genetic scheme, when some trait, manifested in two variants, is determined by a pair of genes, each of which can be of two types. However, the number of genes, and the number of their different types, and the laws of their external manifestation may be different. We will now briefly talk about one of these more complex systems for the transmission of hereditary characteristics.

There are known hereditary characteristics that occur much less frequently in women than in men. These include, for example, hemophilia (incoagulability of the blood) and color blindness (inability to distinguish between certain colors, most often red and green). The second of these more_NEW was first described by the famous English chemist J. Dalton (1766-1844); After his name, it was later called “color blindness.” Dalton himself believed that it was more_NEW for men. Here he was wrong, which is not surprising: according to statistics, it is 8% among men and only 0.5% among women. The reason for this difference is explained in the so-called X chromosome. This chromosome, together with another - the Y-chromosome - determines the sex of a person*): in the cells of the female body it has two

*) The same is true for other mammals and neoctors of insects.
