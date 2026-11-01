---
id: 1988-7-resheniya-zadach-m1091-m1095-f1103-f1107-f36cf0fd
issue: kvant_1988_7
year: 1988
number: "7"
title: Solutions to problems M1091—M1095; F1103—F1107
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 45
page_labels: 36, 37, 38, 39, 41, 42, 43
tag: FV99
lang: en
source: kvant_digital
extraction: vision
content_sha256: 97c0a7d717350b294d6d0c733f2e04b5ccb3fcca51d028b218decec633324636
prompt_sha256: draft-1
translated_from: content/ru/1988/07/articles/09_resheniya-zadach-m1091-m1095-f1103-f1107-f36cf0fd.md
source_content_sha256: 99a4f4e221cd8e8954b5b7e5ff832f6ae0b3c6f3f6d17bb2f4c7e1a2a140e1e8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Problem solutions

M1091. Let us say that a natural number is successful if the digits in its decimal notation can be divided into two groups so that the sums of the digits in these groups are equal.
a) Find the smallest number a such that the numbers a and a+1 are lucky.
b) Is there such a such that the numbers a, a+1 and a+2 are lucky?

M1092. A convex polygon cut out of paper is folded 10 times (peppering along some straight lines) and then cut in a straight line. What is the largest number of pieces that can be obtained?

Answer: a=549. Obviously, the sum of the digits of any number is even. Therefore, if a and a+1 are lucky numbers, then a turns out to be 9 (otherwise the digits of these two numbers have different parities). It is clear that a cannot have two values ​​(99+1=100). If the number a is three-digit, i.e. a=xy9 (the bar means decimal notation), then y<9 and a+1=x(y+1)0. Therefore, x+y=9, x=y+1. Hence x=5, y=4.

6) Answer: does not exist. As can be seen from the solution to problem a), both numbers - a and a+1 - should be on 9, but this is impossible.

N. I. Zilberer

Answer: 1025. Let's solve the problem immediately in the general case for n stibs. Let us draw an arbitrary segment AB inside the polygon and mark on it the points C₁, C₂, ..., Cₙ+1 and also that CₙB=2⁻k·AB (see figure). Through each point Cₙ we draw a straight line lₖ perpendicular to AB. We sequentially bend the polygon along the straight lines l₁, l₂, ..., lₙ from left to right n times (we assume that initially point A lies to the left of B) and cut it along the straight line lₙ+1. Segment AB will be folded into segment CₙB, on which the folded figure has 2ⁿ layers. To the left of the cut, each layer is connected to another slice through the bend lₙ, so we get 2ⁿ−1 pieces of words. To the right of the cut, the layers are also connected in pairs, with the exception of the two single bottom words - the edges of the original figure. Therefore, on the right there will be 2ⁿ−1+1 pieces, and in total there will be 2ⁿ+1 pieces.

Let us show by indication of the number of bends n that the number of pieces cannot be more than 2ⁿ+1. For n=0 this statement is obvious. Let it be true for n inflections. Let's bend the polygon n+1 times. After the first bend, two interconnected partially overlapping polygonal layers are obtained. In the future, each of these words can be considered separately: it will be bent n times and cut, which, according to the assumption of the indication, will be 2ⁿ+1 pieces. Since at least two pieces from different words must be connected through an inflection, the total number of pieces does not exceed 2(2ⁿ+1)-1=2ⁿ−1+1.

Thus, the maximum number of pieces is 2ⁿ+1; in particular, with n=10 we get 2¹⁰+1=1025 pieces.

S. V. Kazakov

Answer in problem a): n−k+1.
a), 6) Let’s divide the points into “series”, each of which begins with two and includes next

⟦folio 37⟧

but at all points the following transformations are made: each number 2 is replaced by 0, and then to the next one along the cylindrical numerical arrow equals $k \ge 1$.

a) After how many transformations will there certainly not be a single two remaining?

b) Let, in addition, at $n-k$ the remaining points initially contain ones. Prove that in the end there will be $k$ ones and $n-k$ zeros left.

(clockwise) units. If the series begins at the point $A_1$, it ends before the point $A_2$ (where there is a two or a zero - on figure 1 this is indicated by a star)

Daughter) and includes $m \ge 0$ units, then after $m+1$ steps at $m$ points following $A_1$ there will be $m$ zeros, and at point $A_2$ there will be one. Figures 2, a, b, c depict the evolution of one series for $m=0$, $m=1$ and $m=4$ ($\emptyset$ means 0 or 1). This evolution occurs simultaneously with all series. Thus, if at the beginning there were $k$ twos at points $A_1$, $A_2$, ..., $A_k$ and the longest series contained $m \le n-k$ ones, exactly after $m+1$ transformations there will not be a single two left. If at the same time there were ones at the remaining $n-k$ points, then after all the transformations there will be zeros in their places, and at $k$ points $A_1$, $A_2$, ..., $A_k$ - ones.

N. V. Vasiliev

M1094. Let $a, b, c$ be non-negative numbers.
a) Prove that from inequality $a^4+b^4+c^4 \le 2(a^2b^2+b^2c^2+c^2a^2)$ (1)
the inequality $a^2+b^2+c^2 \le 2(ab+bc+ca)$ follows. (2)
b) Is the converse true: inequality (2) implies inequality (1)?

a) Transform the difference between the right and left sides of (1):
$$D=2(a^2b^2+b^2c^2+c^2a^2)-(a^4+b^4+c^4)=4a^2b^2-(a^2+b^2)^2+2c^2(a^2+b^2)-c^4=(2ab)^2-(a^2+b^2-c^2)^2.$$
If $D \ge 0$, then $2ab \ge |a^2+b^2-c^2|$. Since the letters $a, b, c$ are included in the condition of a perfect symmetrical manner, we can assume $a \ge b \ge c$. Then $a^2+b^2+c^2=|a^2+b^2-c^2|+2c^2 \le 2ab+2c^2 \le 2(ab+bc+ca)$.
6) Answer: not true. (Example: $a=4$, $b=c=1$.)
Note that, continuing the transformation of the difference $D$, we can decompose it into linear factors:
$$D=(a+b+c)(a+b-c)(a+c-b)(b+c-a).$$
Here only one parenthesis (in which the largest of the numbers $a, b, c$ is subtracted) can be negative. Thus, (1) is equivalent to the condition that each of the numbers $a, b, c$ is not greater than the sum of the other two. Likewise, (2) is equivalent to saying that each of the numbers $\sqrt{a}, \sqrt{b}, \sqrt{c}$ is not greater than the sum of the other two. From here it is easy to obtain another solution to problem a): after all, if $b+c \ge a$, then $(\sqrt{b}+\sqrt{c})^2 \ge b+c \ge a$ and $\sqrt{b}+\sqrt{c} \ge \sqrt{a}$.
The expression $D$ appears in Heron’s formula for the area of ​​a triangle with sides $a, b, c$ (this area is equal to $\sqrt{D}/4$); such a triangle exists if $D > 0$.

⟦folio 38⟧

M1095*. On the plane, given a circle with center O and two points A, B (different from O) such that line AB passes through point O. Construct a chord MN of this circle, which is visible from point A at a given angle α and a) parallel to line AB; b) passes through point B. (If B lies outside the circle, then the continuation of the chord MN must pass through B.)

Fig. 1.

Fig. 2.

For any line passing through an arbitrary given point P and intersecting a given circle, PX $\times$PY = $|d^2 - R^2|$, where X and Y are the points of intersection, d = PO is the distance from P to the center O of the circle, R is the radius of the circle. (From the similarity of triangles PXX1 and PY1Y it follows that PX $\cdot$PY = PX1 $\times$PY1 = $(d + R)|d - R|$).

According to what has been proven, the resulting segment MM1 will have the required length. Now, using the fact that for the original chord MN the angle MN1N is known (it is equal to α) and the distance ON=OM=R, we can construct a segment equal to this chord. To do this, it is enough to draw a ray at an angle α to the already constructed segment MM1 from its end M1 and mark the points of intersection of this ray with the given circle. There can be 0, 1 or 2 such points (Fig. 3). The segments connecting these points with M give the possible value of the length of the original chord. It remains to construct in a given circle a chord of known length parallel to the given straight line AB. Since this known length takes 0, 1, or 2 values, our problem can have 0, 2, or 4 solutions. (The reader will independently show that the problem can have 4 solutions if point A lies outside the given circle; an example of such a situation is given in figure 4.)

6) Let us again assume that the desired chord MN is constructed (Fig. 5). Let us draw a circle AMN and denote it by lines AB and MO ($C \neq A, M_1 \neq M$). It still turns out

⟦folio 39⟧

That the length of the segment $MM_1$ does not depend on the given angle. To prove it, you need to apply the theorem above (Fig.2) several times:
$$BC \cdot BA = BM \cdot BN = BE \cdot BF,$$
where $E$ and $F$ are the points of intersection of the original circle with $AB$; this means that the position of the point $C$ does not depend on the given angle, and again

$$OM_1 \cdot OM = OA \cdot OC.$$

Further, the solution is almost no different from the solution to problem a), only this time it is necessary to construct not a chord of a given length, parallel to a given line, but a chord of a given length, the extension of which passes through a given point. It should also be noted that for some locations of points $A$ and $B$ (see, for example, Fig. 6), the angle $MM_1N$ may turn out to be equal to $\pi - \alpha$, and not $\alpha$.

Fig. 4.

You can avoid enumerating cases if you use the concept of a “directional angle”: the angle from straight line $AM$ to straight line $AN$, absent, say, counterclockwise, will always be equal to the angle from $M_1M$ to $M_1N$, absent in the same direction. The problem still has 0, 2 or 4 solutions.

R. O. Burdin

F1103. A mathematical math book of length $l$ is shown at point $A$ on a cone with a distance angle $2\beta$ (Fig. 1). How far will the matnik go before it breaks away from the surface of the cone, if the matnik is gently pushed out of its equilibrium position? The angle of inclination of the cone to the surface of the earth is $\alpha$, the surface of the cone is considered smooth.

Since the upper end of the thread is fixed, the matnik will move in a circle until it separates from the surface of the cone. The plane of this circle is inclined at an angle $(\pi/2 - \alpha)$ to the horizon, its radius is $r = l \sin \beta$. As it contracts from the cone, the speed of point $A$ increases, which means that its centripetal acceleration must also increase. At some moments, the forces acting on the mat may not be “enough” to continue moving around the circle, and then the point $A$ will be separated from the surface of the cone.

Let us consider the forces acting on the point $A$ as it moves along a cone. These are the gravitational force $m\vec{g}$, the thread tension force $\vec{T}$ and the ground reaction force $\vec{N}$ (Fig. 2). At the moment of separation, the cilia of the reaction becomes zero. This will be used to answer the question in the problem.

Let's introduce a coordinate system as shown in figure 2: direct the $X$ axis along the radius to the center of the circle, the $Y$ axis - along the tangent to the circle and the $Z$ axis -

⟦folio 41⟧

Let's draw from point $E$ straight $EF \parallel DN$. The condition for the occurrence is equivalent to the condition for the formation of a triangle from segments $ME$ and $EF=DN$ (equal in length of the threads) and segment $MF=|MN|-ED$ (equal to the difference in the lengths of the rods):

$$MF > |EM|-DN|.$$

Thus, if the difference in the lengths of the rods is greater than the difference in the lengths of the threads, then the rods are parallel, otherwise the threads are parallel. In particular, if the rods are equal, then the threads are parallel; if the threads are equal, then the rods are parallel. If the differences in the lengths of the rods and threads are the same, then both the rods and the threads lie on the vertical $OA$.

V. T. Karpetyan

F1105. A metal disk with a radius of $r=10$ cm is processed in a horizontal plane at a speed of $v=60$ rpm. From a height of $H=10$ cm a flat block falls onto it, the mass of which is much less than the mass of the disk. The lower edge of the block is always parallel to the plane of the disk, the friction coefficient between the metal and the plane is $\mu=0,1$. At what distance from the axis must the block fall so that when it is re-attached it falls outside the disk? Assume that after the rebound the block rises to its previous height; Neglect the dimensions of the block.

Let the block, when first applied, hit the disk at point $A$, located from the center of the disk at a distance $x$ (see figure). During an impact, two forces act on the block from the side of the disk - the vertical direction, the support reaction force $\vec{N}$, and the horizontal direction, the friction force $\vec{F}_{\text{тр}}$. Assuming that during the entire collision the speed of the block relative to the disk is less than the linear speed $v_A = \omega x = 2\pi vx$ of the point $A$ disk, we obtain that all the time $F_{\text{тр}} = \mu N$. Then the impulse transmitted by the disk to the block in the horizontal direction is related to the impulse transmitted to the block in the horizontal direction, respectively.

$$P_r = \mu P_B.$$

On the other side,

$$P_r = mv,$$

where $m$ is the mass of the block, $v$ is its horizontal speed after the collision,

$$P_B = 2mv_0,$$

where $v_0 = \sqrt{2gh}$ is the vertical velocity of the block immediately before the impact. From here is

$$v = 2\mu v_0 = 2\mu \sqrt{2gh}.$$

During the time interval $\tau = 2t_{\text{пяд}} = 2\sqrt{2h/g}$ between the first and second collisions, the block will fly a horizontal distance

$$l = v\tau = 8\mu h.$$

According to the conditions of the task, compliance must be fulfilled

$$l > \sqrt{r^2 - x^2},$$

i.e.

$$x > \sqrt{r^2 - l^2} = \sqrt{r^2 - (8\mu h)^2} = 6 \text{ см.}$$

Let's check whether the condition $v < v_A$ will be satisfied:

$$v = 2\mu \sqrt{2gh} \approx 28 \text{ см/c},$$

$$v_A = 2\pi vx \approx 38 \text{ см/c} > v.$$

So, the block must first fall onto the disk at a distance of at least 6 cm from its center.

L. A. Zakrevsky

⟦folio 42⟧

F1106. A few words about northern guides. Northern conductors have the property of pushing out a magnetic field (the so-called Meissner effect), thanks to which they can float above a magnet. This feature of northern conductors is supposed to be used to create northern high-speed trains on “magnetic levitation”, prototypes of which have already been tested. And now the task itself. In the northern direction, a sample of mass m, hovering above a permanent magnet, is placed on a load of exactly the same mass. How many times must the magnetic induction of the field created by the magnet be increased in order for the northern conductor with the load to float at the same distance from the magnet?

F1107. Freshly fallen fluffy snow artificially in the sun. Estimate the characteristic distance between individual “sparks”.

We will assume that the snow patches in the snow cover are randomly oriented flat mirrors with the same area of ​​about 10 mm².

Each snowflake mirror reflects light in the form of a diverging beam. The divergence angle is equal to the angular size of the Sun $a \approx 0,5^\circ$. The probability $q$ that reflected light from a randomly oriented snowfield hits a given point $A$ (see figure) is equal to the ratio of the area of ​​the base of the light beam cone to the area of ​​the hemisphere passing through points $A$ (the center of the hemisphere is on the snowfield). Considering that the height of the light cone is almost equal to the radius of the hemisphere, we find

$$q = \frac{\pi r^2}{\pi R^2} = \frac{\pi R^2 \text{tg}^2 \alpha/2}{\pi R^2} = \text{tg}^2 \alpha/2 \approx \frac{\alpha^2}{4},$$

where $R$ is the radius of the hemisphere, or the distance from the snowfield to the observed one, $r$ is the radius of the base of the light beam.

On one square meter of snow cover north there are $n \approx 10^5$ snowflakes, and the light from $qn$ particles will hit point $A$.

To estimate the characteristic distance between individual “sparks,” we will assume that the luminous snow patches are located on the surface of the light surface, for example, on the centers of close-packed hexagons. Then the area of ​​one is six

⟦folio 43⟧

The angle $S_0$ and the characteristic distance between the sparks $d$ are related to the relations

$$S_0 = \frac{\sqrt{3}}{2} d^2,$$

where is it from?

$$d \approx 60 \text{ см.}$$

When observing snowflakes in practice, one must take into account the biocularity of human vision. At short distances it is observed: the diameter of the light beam is less than the distance between the pupils, and each eye sees “its own” spark. At a large distance ($R > 30$ m), the diameter of the light beam from an individual snowflake becomes an order of magnitude larger than the distance between the pupils, and the “precise observer” model can be used, as done above.

Note that sparkling snow can be observed not only during the day, but also at night, for example, in the light of street lights. Remember A. A. Fet:

The creak of footsteps along the white street.
Lights in the distance.
On the frozen walls
Crystal sparkles.

E. N. Yunosov, I. V. Yaminsky

Orders accepted...

(For the beginning, see p. 22)

The purpose of the book is to introduce the non-specialist reader to the basic facts of quantum physics and the history of their discovery.

95. Tarbeev Yu. V. Physical quantities. Edinet. Standards. Constants. 1 rub. 10 k.

The basic metrological concepts, names and practices of designating physical quantities, the most accurate and reliable values ​​of physical quantities, and units of physical quantities are presented in a concise and accessible form.

96. Yavorsky B. M., Seleznev Yu. A. A reference guide to physics for university applicants and self-education. 1 rub. 90 k.

The manual contains information on all sections of physics that are studied in secondary schools and secondary specialized educational institutions.

108. Butikov E. I., Bykov A. A., Kondratiev A. S. Physics in examples and problems. 1 rub.

The authors’ goal is to teach the reader to reason, to bring him to a deep understanding of the phenomena under consideration. The new edition reflects the latest changes in the content of secondary school physics courses and competitive university examination programs.

109. Gursky I.P. Elementary physics with examples of problem solving. 1 rub. 10 k.

The entire elementary physics course is consistently and briefly reviewed. The author's goal is to help applicants repeat the physics course with a minimum investment of time.

110. Meledin G.V. Physics in problems: Examination problems with solutions. 70 k.

Contains a summary of 500 problems offered in the written entrance exam in physics at Novosibirsk State University.
