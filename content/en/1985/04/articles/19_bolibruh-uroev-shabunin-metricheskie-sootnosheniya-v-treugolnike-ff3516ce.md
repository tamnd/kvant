---
id: 1985-4-bolibruh-uroev-shabunin-metricheskie-sootnosheniya-v-treugolnike-ff3516ce
issue: kvant_1985_4
year: 1985
number: "4"
title: Metric ratios in a triangle
authors:
  - Болибрух А. А.
  - Уроев В. М.
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 52
page_labels: 48-50
tag: TSKU
lang: en
source: kvant_digital
extraction: vision
content_sha256: bb2ff469ad92d6ff0cf0851c49f38227c4a7b8c78a9c6b0a75cc0bc69a97221f
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/19_bolibruh-uroev-shabunin-metricheskie-sootnosheniya-v-treugolnike-ff3516ce.md
source_content_sha256: 080d977e5b4ed50150a1c47669504e70d0aabd66f5300868419c35d35be82cbf
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Metric ratios in a triangle

Candidate of Physical and Mathematical Sciences A. A. BOLIBRUKH,
Candidate of Physical and Mathematical Sciences V. M. UROEV,
Professor M. I. SHABUNIN

The experience of conducting university exams shows that many applicants do not have sufficient skills in solving geometric problems. The simplest planimetric problems sometimes become a stumbling block even for those applicants who successfully cope with questions in algebra and trigonometry. Moreover, this applies not only to problems for which it is necessary to show a certain ingenuity, but also to problems solved using standard theorems and formulas of the school course, such as the cosine theorem, the sine theorem, formulas for the area of ​​a triangle, etc.

Currently, problems are being considered, in the main proposal in different years for the entrance exams at MIPT. From a large material, the authors selected problems, the solution of which uses the basic metric relationships between the elements of the triangle.

Let us write down these relations. The distance is triangle ABC and introduce the following notations: $a = |BC|$, $b = |AC|$, $c = |AB|$, $R$ - the radius of the circumscribed circle about triangle ABC, $r$ - the radius of the inscribed circle, $h_a$ - the length of the height dropped to side BC, $S$ - the area of ​​the triangle. Then

$$\frac{a}{\sin \hat{A}} = \frac{b}{\sin \hat{B}} = \frac{c}{\sin \hat{C}} = 2R$$

(sine theorem), (I)

$$a^2 = b^2 + c^2 - 2bc \cos \hat{A}$$

(cosine theorem), (II)

$$S = \frac{1}{2} h_a a,$$

(III)

$$S = \frac{1}{2} bc \sin \hat{A},$$

(IV)

$$S = \frac{1}{2} (a + b + c) r.$$

(V)

The applicant must know these formulas, be able to prove them, and also apply them when solving problems. There are other formulas, the knowledge of which is no longer provided by the programmer for constructing them, but which are often useful in solving problems. For example, Heron's formula

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

(VI)

where $p = (a + b + c)/2$ is the meter of the triangle or the formula

$$S = \frac{abc}{4R},$$

(VII)

which is easily obtained by substituting the value of sin $\hat{A}$, found from the sine theorem (I), into formula (IV).

Let's start with a problem using the sine theorem.

1. In equilateral triangle ABC ($|AB| = |BC|$), the median AD and the bisector CE are perpendicular. Determine the angle ADB.

Solution. Let $\alpha$ be the desired angle, $O$ be the intersection point of the segments AD and CE (Fig. 1). In the $\triangle ADC$ bisector CO is also an altitude, which means $\triangle ADC$ is equilateral and $D\hat{AC} = A\hat{DC} = \pi - \alpha$, $\hat{A} = \hat{C} = 2\alpha - \pi$, $B\hat{AD} = \hat{A} - D\hat{AC} = 3\alpha - 2\pi$. In triangle ABD according to conditions $|BD| = 1/2 |AB|$. Applying the theorem of sines, we obtain $\frac{|AB|}{\sin \alpha} = \frac{|BD|}{\sin (3\alpha - 2\pi)}$, from which $\frac{1}{\sin \alpha} = \frac{1}{2 \sin 3\alpha}$, $2 \sin 3\alpha = \sin \alpha$, $2 \sin \alpha (3 - 4 \sin^2 \alpha) = \sin \alpha$, $\sin^2 \alpha = 5/8$. But from the conditions of the problem it follows that $D\hat{CO} = \alpha - \pi/2 > 0$, on the other hand, $\alpha < \pi$, that is, $\pi/2 < \alpha < \pi$, therefore $\sin \alpha = \sqrt{10}/4$, $\alpha = \pi - \arcsin \sqrt{10}/4$.

Answer: $\pi - \arcsin \sqrt{10}/4$.

2. In an equilateral triangle ABC, the length of the altitude BD, lowered to the base, is equal to h, and the radius of the circumscribed circle is equal to r. Find the radius of the circle circumscribed about this triangle.

⟦folio 49⟧

Solution. Let $O$ be the center of the inscribed circle, $E$ the point of tangency of the circle with the segment $AB$, $|AC| = b$ (Fig. 2). According to the law of sines, the radius $R$ of the circumscribed circle is $\frac{b}{2 \sin \hat{B}}$. From $\triangle BOE$ there is $\sin \frac{\hat{B}}{2} = \frac{|OE|}{|OB|} = \frac{r}{h-r}$. On the other hand, $\tg \frac{\hat{B}}{2} = \frac{|AD|}{|BD|} = \frac{b}{2h}$, from here
$$b = 2h \text{ tg} \frac{\hat{B}}{2} \text{ и } R = \frac{h \text{ tg} \frac{\hat{B}}{2}}{\sin \hat{B}} = \frac{h}{2 \cos^2 \frac{\hat{B}}{2}} = \frac{(h-r)^2}{2(h-2r)}$$
Answer: $\frac{(h-r)^2}{2(h-2r)}$.

3. The angles at the vertices $A$ and $C$ of triangle $ABC$ are respectively $\pi/4$ and $\pi/6$. Find the angle between the height $BD$ and the median $BE$ of this triangle.

Solution. Let's denote $|AB| = c$, $|AC| = b$, $DBE = \varphi$ (Fig. 3). Then $|AD| = c \cos \hat{A} = c \sqrt{2}/2$, $|DE| = |BD| \times \text{tg} \varphi = (c \sqrt{2} \text{ tg} \varphi)/2$. Therefore, $b/2 = |AE| = |AD| + |DE| = c \sqrt{2} \times (1 + \text{tg} \varphi)/2$. By the sine theorem for $\triangle ABC$ we obtain $\frac{c}{\sin \hat{C}} = \frac{b}{\sin \hat{B}}$, where
$$\sin \hat{B} = \sin (\pi - \hat{A} - \hat{C}) = \sin (\hat{A} + \hat{C}) = \sin \frac{\pi}{6} \cos \frac{\pi}{4} + \cos \frac{\pi}{6} \sin \frac{\pi}{4} = \frac{\sqrt{2}}{4} \times (1 + \sqrt{3}).$$
From here is
$$\frac{c}{1/2} = \frac{4c(1 + \text{tg} \varphi)}{1 + \sqrt{3}}, \text{tg} \varphi = \frac{\sqrt{3} - 1}{2}.$$
Answer: $\arctg \frac{\sqrt{3} - 1}{2}$.

The following problems use the cosine theorem.

4. Bisectors $AD$ and $CF$ of triangle $ABC$ intersect sides $BC$ and $AB$ at points $D$ and $F$ respectively. Find the length of the segment $FD$ if $|AC| = 6$, $|AF| = 2$, $|CD| = 3$.

Solution. Let us denote $|BD| = x$, $|BF| = y$ (Fig. 4). Let's use an important property of the bisector: the bisector divides the side of the triangle into parts proportional to the lengths of the adjacent sides. Thus, $|AB|/|AC| = x/3$, $|BC|/|AC| = y/2$ or $(2+y)/6 = x/3$, $(x+3)/6 = y/2$, whence $x=9/5$, $y=8/5$, $|AB|=18/5$, $|BC|=24/5$. To calculate $|DF|$ we use the cosine theorem for $\triangle FBD$.

$$|DF|^2 = x^2 + y^2 - 2xy \cos \hat{B},$$
where $\cos \hat{B}$, in turn, is found from the correspondence $|AC|^2 = |AB|^2 + |BC|^2 - 2|AB| \cdot |BC| \cos \hat{B}$. Substituting the

⟦folio 50⟧

Given the lengths of side $\triangle ABC$, we obtain $36 = \frac{18^2}{25} + \frac{24^2}{25} - \frac{2 \cdot 18 \cdot 24}{25} \times \cos \hat{B}$, from which $\cos \hat{B} = 0$, $\hat{B} = \pi/2$, $|DF| = \sqrt{145}/5$.

Answer: $\sqrt{145}/5$.

5. In triangle $ABC$: $\hat{B} = \arccos \frac{7}{8}$, $|AC| = b$, and the height dropped from vertex $B$ is equal to the sum of the other two heights. Find the area of ​​triangle $ABC$.

Solution. Let $|AB| = x, |BC| = y$ (Fig. 5). Then by the cosine theorem $b^2 = x^2 + y^2 - 2xy \cos \hat{B} = x^2 + y^2 - \frac{7}{4}xy$.

(3)

Next, $h_b = \frac{2S}{b}$, $h_x = \frac{2S}{x}$, $h_y = \frac{2S}{y}$, where $S$ is the area of ​​$\triangle ABC$, and $h_b, h_x, h_y$ is its height. Since according to the conditions of the problem $h_b = h_x + h_y$, then $\frac{1}{b} = \frac{1}{x} + \frac{1}{y}$ or $x + y = \frac{xy}{b}$, hence $x^2 + y^2 = \frac{(xy)^2}{b^2} - 2xy$. From here and from equation (3) we obtain the equation for $z = xy$:

$$b^2 = \frac{z^2}{b^2} - 2z - \frac{\tau}{4}z,$$

whence $z = xy = 4b^2$. Therefore $S = \frac{xy \sin \hat{B}}{2} = \sqrt{15}/4 b^2$.

Answer: $\frac{\sqrt{15}}{4} b^2$.

A note on the cosine theorem. Using the cosine theorem, it is easy to obtain a formula expressing the length of the median in terms of the length of the side of the triangle. Let us denote $|AB| = c$, $|AC| = b$, $|BC| = a$, the length of the median $AD$ by $m_a$, $BDA = \varphi$ (Fig. 6). Using the cosine theorem for triangles $ABD$ and $ADC$ we obtain:

$$a^2/4 + m_a^2 - am_a \cos \varphi = c^2,$$
$$a^2/4 + 2m_a^2 - am_a \cos (\pi - \varphi) = b^2.$$

Adding these equations and using what is $\cos (\pi - \varphi) = -\cos \varphi$, we find $a^2/2 + 2m_a^2 = c^2 + b^2$, from where

$$m_a = \frac{1}{2} \sqrt{2(b^2 + c^2) - a^2}.$$

6. In the triangle $ABC$ the sides of the related relations $|BC|^2 + |AC|^2 = 5|AB|^2$ are long. Find the angle between medinas $AM$ and $BN$.

Solution. Let's denote $|AB| = c$, $|BC| = a$, $|AC| = b$, $NOM = \varphi$, $AM| = m_a$, $BN| = m_b$ (Fig. 7). Since at the intersection point the medians are divided in a ratio of 2:1, counting from the vertex, then according to formula (4), we obtain:

$$|OM| = \frac{m_a}{3} = \frac{1}{6} \sqrt{2(b^2 + c^2) - a^2},$$
$$ON = \frac{m_b}{3} = \frac{1}{6} \sqrt{2(a^2 + c^2) - b^2}.$$

Fig. 10. Fig. 11. Fig. 12.
