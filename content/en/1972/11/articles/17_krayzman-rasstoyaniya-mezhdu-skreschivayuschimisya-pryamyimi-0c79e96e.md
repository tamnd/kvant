---
id: 1972-11-krayzman-rasstoyaniya-mezhdu-skreschivayuschimisya-pryamyimi-0c79e96e
issue: kvant_1972_11
year: 1972
number: "11"
title: Distances between crossing lines
authors:
  - Крайзман М. Л.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 59
page_labels: 52, 53, 55, 56, 57
tag: LCTW
lang: en
source: kvant_digital
extraction: vision
content_sha256: c05242adbcea35437a85dbd056a767dfda673577f12338c364cd22ff0e734bb3
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/17_krayzman-rasstoyaniya-mezhdu-skreschivayuschimisya-pryamyimi-0c79e96e.md
source_content_sha256: 0cb9ee8930dec4a6307f3d7eb919f56b7f2c1743de70493d810d69dc5dd922db
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Considering the mechanism of crossing straight lines

M.L.Kreizman

When solving problems of calculating the distance between intersecting lines, it is useful to distinguish between two cases:

1) crossing straight perpendiculars;
2) crossing straight lines and not perpendiculars.

If the crossing lines $a$ and $b$ are perpendiculars (1st case), then the easiest way to check through one of the crossing lines is the plane $\alpha$, perpendicular to another line (Fig. 1; from an arbitrary point $M$ on the line $a$ the perpendicular is dropped $OM$ to the line $b$, the plane $\alpha$ is determined by two intersecting lines $a$ and $MO$, because $b \perp a$ by condition and $b \perp OM$ by construction, therefore, $b \perp \alpha$ by generalization of the perpendicularity of the line and the plane). Then, from the point $O$ of intersection of the plane $\alpha$ and the straight line $b$, it is necessary to lower the perpendicular $ON$ onto the straight line $a$, $ON$—excluding the distance.

Example 1. Determine the distance between the diagonal of a cube with edge $a$ and the diagonal of the face that intersects it.

Solution. We will determine the distance between $B_1D$ and $D_1C$ (Fig. 2). Since $D_1C \perp DC_1$ and $DC_1$ are the projection of $B_1D$ onto the plane $DD_1C_1C$, then $D_1C \perp B_1D$ (by the generalized theorem on three perpendiculars). From the correspondence of $D_1C \perp DC_1$ and $D_1C \perp B_1D$ it follows (based on the perpendicularity of the line and the plane) that $D_1C \perp DB_1C_1$. Let $O$ be the intersection point of $D_1C$ and $DC_1$. Let us drop from the point $O$ the perpendicular $OK$ to $B_1D$, $OK$ - eliminating the distance of the crossing lines $B_1D$ and $D_1C$. Let's find him. To do this, we replace that right triangles $OKD$ and $B_1DC_1$ are similar to $OK: B_1C_1 = OD: B_1D$. From here

$$OK = \frac{a\sqrt{6}}{6}.$$

⟦folio 53⟧

Before moving on to the next examples, we prove a theorem expressing the relationship between the angles of a triangular angle in which two faces are mutually redistributed.

Theorem 1. If two faces of a triangular angle are mutually redistributed, then the cosine of the plane angle of the face lying opposite the right two-dimensional angle is equal to the product of the cosines of the plane angles of the face that are opposite the right two-dimensional angle.

Proof. At figure 3 pl. ASB ⊥ pl. BSC, ⇒ ASC = α, ⇒ ASB = β, ⇒ BSC = γ. We want to prove that cos α = cos β · cos γ. To do this, from the point M on the edge SA we drop the redistributions MO to BS and MN to SC. Let us connect the points N and O. According to the theorem on three redistributors, SC ⊥ NO. From △SMO and △SON is

$$\cos \beta = \frac{SO}{SM}, \quad \cos \gamma = \frac{SN}{SO}.$$

The variables are these equalities: cos β · cos γ = $\frac{SN}{SM}$, and we find cos α from △SNM: cos α = $\frac{SN}{SM}$. Hence cos α = cos β · cos γ. The theorem is proven.

Example 2. Each edge of a triangular prism is equal to α. However, from the side edges it forms angles with the sides of the base, each of which is equal to α. Determine the distance between this edge and the sides of the base that intersect with it.

Solution. It is required to determine the distance between AA₁ and BC (Fig. 4). It is known that if the inclined line emanating from the vertex of the angle

$$\text{Рис. 3.}$$

forms equal angles on the sides of this angle, then the inclined projection onto the plane of the angle will be its bicsectrix. Therefore AO is the bicsectrix of angle BAC. But △ABC is correct, the continuation of the AD bicsectrix will be the height of this triangle and therefore AD ⊥ BC. By the generalized theorem on three redistributors BC ⊥ AA₁, and based on the generalized criterion for the redistribution of a straight line and a plane BC ⊥ pl. DAA₁. Let us drop from point D the redistributor DK to AA₁; DK is the required distance between BC and AA₁. Let ⇒ A₁AO = x; applying Theorem 1 to the triangular angle AA₁DC, we obtain: cos ⇒ A₁AC = cos ⇒ A₁AD · cos ⇒ DAC; cos α = cos x cos 30°. From here

$$\cos x = \frac{\cos \alpha}{\cos 30^\circ} = \frac{2\sqrt{3}\cos \alpha}{3}.$$

It remains to find KD from △AKD:

$$KD = AD \cdot \sin x = \frac{a\sqrt{3}}{2}\sqrt{1 - \cos^2 x} = \frac{a\sqrt{3}}{2}\sqrt{1 - \frac{4}{3}\cos^2 \alpha} = \frac{a}{2}\sqrt{3 - 4\cos^2 \alpha} = \frac{a}{2}\sqrt{3 - 4\cos^2 \alpha},$$

and $\frac{\pi}{6} < \alpha < \frac{5\pi}{6}$.

Now let us consider the case when the intersecting lines do not redefine each other. Since in the given calculations there is no need to construct a redefinition to

⟦folio 55⟧

between intersecting straight lines. One of these methods is based on the theorem on the volume of a triangular rectangle.

Theorem 2. The volume of a triangular straight line is equal to one-sixth of the product of the length of any two of its intersecting edges by the distance between them and by the sine of the angle between them.

Proof. From an arbitrary vertex ($B_1$) of the parallelepid $AC_1$ we draw the diagonals $B_1A$, $B_1D_1$, $B_1C$ of the faces converging at this vertex (Fig. 9). Let's connect the ends of these diagonals to each other. We obtain a parallelepid $B_1AD_1C$, which is called inscribed in a parallelepid, and a parallelepid, on the contrary, described around this parallelid (it can be easily constructed by drawing pairs of parallel planes through the opposite edges of the parallelid).

The volume of the parallelepid is:

$$V_{AC_1} = V_{B_1AD_1C} + V_{D_1ADC} + V_{B_1ABC} + V_{AA_1B_1D_1} + V_{CB_1C_1D_1}.$$

Because

$$V_{D_1ADC} = V_{B_1ABC} = V_{AA_1B_1D_1} = V_{CB_1C_1D_1}.$$

(the bases of these parallelepids are equal to the position of the area of ​​the base of the parallelepid, and their heights are equal to the height $h$ of the parallelepid), then

$$V_{B_1AD_1C} = V_{AC_1} - 4V_{D_1ADC} = V_{AC_1} - 4 \cdot \frac{1}{3} \cdot \frac{1}{2} Sh = V_{AC_1} - \frac{2}{3} Sh = \frac{1}{3} V_{AC_1}.$$

So, the volume of an inscribed triangular parallelepid is one third

volume of the described parallelepid, or after transformation,

$$V_{B_1AD_1C} = \frac{1}{3} V_{AC_1} = \frac{1}{3} Sh = \frac{1}{3} \left( \frac{1}{2} AC \cdot BD \cdot \sin \varphi \right) \cdot h = \frac{1}{6} AC \cdot B_1D_1 \cdot h \cdot \sin \varphi.$$

When solving problems of finding the distance between intersecting straight lines, you can use the features of the described parallelepid depending on the properties of the vertical triangular parallelid. For example, try to prove on your own that if there are two crossing edges in a paramid:

a) are equal, then the faces of the described parallelepid in which these edges lie will be rectangles;
b) are equal and perpendicular, then the corresponding faces will be squares.

Example 5. In a triangular paramid, the opposite (crossing) edges are pairwise equal to each other and the corresponding ones are equal to a, b and c. Find consideration between them.

Solution. The opposite faces of the described parallelepid are a right angle, and therefore the parallelepid itself will be a right angle (Fig. 10). The required distances between the crossing edges will be equal to the distance between the opposite faces, that is, the edges of a right parallelepid.

⟦folio 56⟧

Let's create a system of equations:

$$x^2 + y^2 = a^2,$$
$$x^2 + z^2 = b^2,$$
$$y^2 + z^2 = c^2.$$

Adding them term by term and dividing by 2, we get

$$x^2 + y^2 + z^2 = \frac{a^2 + b^2 + c^2}{2},$$

and subtracting each of the system equations from the last equation and taking the square root, we find

$$x = \frac{1}{2} \sqrt{2(a^2 + b^2 - c^2)},$$
$$y = \frac{1}{2} \sqrt{2(a^2 + c^2 - b^2)},$$
$$z = \frac{1}{2} \sqrt{2(b^2 + c^2 - a^2)}.$$

Example 6. The two promiscuous ribs of the corresponding triangular paramid are 6 cm and 8 cm, and each of the other four ribs is 13 cm. Determine the distance between the crossing ribs of this paramid.

Solution. Since $AB_1 = B_1C = AD_1 = D_1C$ (Fig. 11), then all the lateral faces of the parallelepid $AC_1$ are equal rectangles. Consequently, the base is a rhombus $ABCD$, and the parallelepid itself is straight. Hence $d(AC; B_1D_1) = BB_1$, $d(AD_1; B_1C) = d(AB_1; D_1C) = h$, where $h$ is the height of the rhombus $ABCD$. Next, it’s easy to find that $h = 4,8$ cm, $BB_1 = 12$ cm (do it yourself).

The algebraic method for solving the problem of determining the distance between crossing lines is based on the following theorem.

Theorem 3. Let the data cross the lines $a$ and $b$. Points $A_1, A_2, A_3$ are taken on line $a$ and perpendiculars $A_1B_1, A_2B_2, A_3B_3$ are dropped from these points to line $b$. Then $A_1A_2:A_2A_3 = B_1B_2:B_2B_3$.

Proof. Let us draw through the line $b$ an arbitrary plane $\alpha$ (Fig. 12) and consider the orthogonal projection of the line $a$ onto this plane; the projections of the point $A_1, A_2, A_3$ are denoted by $A'_1, A'_2, A'_3$, respectively. From the properties of parallel projection we have

$$A_1A_2:A_2A_3 = A'_1A'_2:A'_2A'_3.$$

The last point is $A'_1, A'_2, A'_3$, respectively, from the point $B_1, B_2, B_3$. From the three perpendicular theorem it follows that $A'_1B_1 \perp b, A'_2B_2 \perp b, A'_3B_3 \perp b$, therefore $A'_1B_1 \parallel A'_2B_2 \parallel A'_3B_3$. According to the theorem about the intersection of two lines next to parallel lines, we can write:

$$A'_1A'_2:A'_2A'_3 = B_1B_2:B_2B_3.$$

From equalities (1) and (2) of non-presiding it follows:

$$A_1A_2:A_2A_3 = B_1B_2:B_2B_3.$$

Example 7. At the base of the paramid SABC lies a right vertical triangle $ABC$ with a sinomenuse $AB = c$ and an acute angle $BAC$ equal to $30^\circ$. Side edge passing through

⟦folio 57⟧

stone AC, is perpendicular to the plane of the base, and the other two form an angle with it, also equal to 30°. Determine the distance between SB and AC.

Solution. Let us find the projection of the segment SB onto the segment AC. To do this, from the points S and B we lower the perpendiculars SO and BC to AC (Fig. 13), and SK to AB; then Pr_ACSB = OC. Let's find the ratio $\frac{OC}{SB}$. From equalities $\Rightarrow SKO = \Rightarrow SCO = 30^\circ$ it follows that OK=OC and OB are the bisserris of angle ABC. Next we find: $BC = AB \cdot \sin 30^\circ = \frac{1}{2}c$,

$$OC = BC \cdot \mathrm{tg} 30^\circ = \frac{c \sqrt{3}}{6},$$

$$SC = OC \cdot \cos 30^\circ = \frac{1}{3}c,$$

$$SB = \sqrt{SC^2 + BC^2} = \frac{c \sqrt{13}}{6}.$$

Hence,

$$\frac{OC}{SB} = \frac{c \sqrt{3}}{6} : \frac{c \sqrt{13}}{6} = \sqrt{\frac{3}{13}}.$$

From an arbitrary point P taken on SB, drop a perpendicular PQ to AC; then the projections of PB onto AC will be QC. According to Theorem 3, OC:SB = QC:PB, whence $\frac{QC}{PB} = \sqrt{\frac{3}{13}}$; let $QC = x \sqrt{3}, PB = x \sqrt{13}$. Let us apply the cosine theorem to the triangle CPB:

$$PC^2 = \frac{c^2}{4} + 13x^2 - 2\frac{c}{2} \cdot x \sqrt{13} \cos \Rightarrow CBP.$$

Fig. 13.

From $\triangle SCB$ we find

$$\cos \Rightarrow CBS = \frac{CB}{SB} = \frac{c}{2} : \frac{c \sqrt{13}}{6} = \frac{3}{\sqrt{13}},$$

and substitute in (3):

$$PC^2 = \frac{c^2}{4} + 13x^2 - cx \sqrt{13} \cdot \frac{3}{\sqrt{13}} = 13x^2 - 3cx + \frac{c^2}{4}.$$

Next, from $\triangle QPC$ we have

$$QP^2 = CP^2 - QC^2 = 13x^2 - 3cx + \frac{c^2}{4} - 3x^2 = 10x^2 - 3cx + \frac{c^2}{4}.$$

The smallest value $QP^2$ will be equal to the square of the distance between the crossing lines; let's find him. If $QP^2 = ax^2 + bx + c$, then

$$x_{\min} = -\frac{b}{2a} = \frac{3c}{20}; \quad (QP^2)_{\min} = 10 \cdot \frac{9c^2}{400} - 3c \cdot \frac{3c}{20} + \frac{c^2}{4} = \frac{c^2}{40};$$

$(QP)_{\min} = \frac{c \sqrt{10}}{20}.$

Exercises

1. At the base of the paramid SABC lies a right triangle ABC ($\Rightarrow C = 90^\circ$) with a quadrat BC = a and an enclosing acute angle α. The lateral ribs are inclined to the base plane at an angle β. Determine the distance between the hypotenuse AB and the lateral edge SC that intersects it.

2. The side of the base of a regular triangular paramid is equal to a. Determine the distance between the apthema of the paramida and the side of the base that intersects with it, if the angle of inclination of the lateral edge to the plane of the base is 60°.

3. The side of the base of a regular quadrangular paramid SABCD is equal to a, and the plane angle at the vertex is equal to α. Determine the distance between the crossing edges of this paramid.
