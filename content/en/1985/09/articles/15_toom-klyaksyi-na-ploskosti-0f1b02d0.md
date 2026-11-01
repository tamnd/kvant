---
id: 1985-9-toom-klyaksyi-na-ploskosti-0f1b02d0
issue: kvant_1985_9
year: 1985
number: "9"
title: Blots on a plane
authors:
  - Тоом А. Л.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 49
page_last: 50
page_labels: 47-48
tag: C0NQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9ce5224f7d16a153fc339f362fbeec09502ee922c01e227bc26d3474dd4ab8a8
prompt_sha256: draft-1
translated_from: content/ru/1985/09/articles/15_toom-klyaksyi-na-ploskosti-0f1b02d0.md
source_content_sha256: 96275b3abbc8284bb83d3546b85948351d1c8520894edc3c28f528678e672575
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

F937. A person “height” $h=20$ cm is directed on a vertical wall, the person’s head is at a height of $H=2$ m above the floor. Using a line with a focal length of $F=0,1$ m, an image of a person on the floor is obtained. These sizes provide the clearest images.

The image on the floor can be obtained at different positions of the lens, and the magnification will depend on the position of the lens. The clearest image will be in the case when the “center” of the source (point $A$ on figure) and the corresponding image point (point $A'$) lie on the main optical axis of the lens. It is easy to show that the plane in which the lens lies passes through the vertex $O$ of the right angle $AOA'$ (see figure).

Let's write down the lens formula:

$$\frac{1}{F} = \frac{1}{d} + \frac{1}{f} = \frac{1}{|AO'|} + \frac{1}{|O_1A'|}.$$

Assuming that $|OA| = H - h/2 = H_1$, we get $|AO'| = H_1 \cos \alpha$, $|O'A'| = |OA'| \sin \alpha = H_1 \text{tg} \alpha \cdot \sin \alpha$, and

$$\frac{1}{H_1 \cos \alpha} + \frac{1}{H_1 \text{tg} \alpha \cdot \sin \alpha} = \frac{1}{F},$$

where

$$\sin^2 \alpha \cdot \cos \alpha = \frac{F}{H_1} = \frac{F}{H - h/2}.$$

From this equation we can find the angle $\alpha$. It can be approximately assumed (the angle $\alpha$ is small) that $\cos \alpha \approx 1$; Then

$$\sin \alpha \approx \sqrt{\frac{F}{H - h/2}} \approx 0,233 \text{ и } \alpha \approx 0,231.$$

Let's now calculate the image size. If the source and image lay in a plane perpendicular to the main optical axis of the lens, then the magnification would be equal to

$$\Gamma = \frac{|O'A'|}{|AO'|} = \frac{H_1 \text{tg} \alpha \cdot \sin \alpha}{H_1 \cos \alpha} = \text{tg}^2 \alpha.$$

In our case, the magnification is equal to the ratio of the length of the projections of the image and the source onto these planes; This means the image size is

$$h' = h \Gamma \text{tg} \alpha = h \text{tg}^3 \alpha \approx 0,25 \text{ см.}$$

A. R. Zilberman

Blots on a plane

Imagine a geographic map that shows the area where a plant species or epidemic is located. The part of the map corresponding to this territory is painted in a certain color, the rest is left white. To study the location diagram of a species or epidemic, a sequence of such maps corresponding to different points in time is compiled and an attempt is made to obtain patterns of change in the shaded part. If a child is about an epidemic, we naturally want it to go away. If the child is about some valuable species, we want it to be preserved. In both cases, it is important for us whether the painted part disappears or not. Such messages lead to problems similar to the one that was published in the 5th issue of our magazine for this year in the “Quaita Problem Book” (M925). We will present its solution and several other related problems.

M925. On the white plane there is a singra $K_0$. From it a new singra figure $K_1$ is obtained according to the following rule, applying simultaneous application to all points $M$ of the plane: if at least a pole of the area of ​​a circle of radius 1 with a center at point $M$ is occupied with a color, then the points $M$ become blue, and if less poles, then white. At the next step, from the resulting singra figure $K_1$, according to the same rules, a figure $K_2$ is obtained, then from it $K_3$, etc. Prove that: a) for an arbitrary limited figure $K_0$, starting from a certain step, if the plane becomes white; b) if $K_0$ is a round 100, then this will happen no later than in a million steps.

Let us denote by the letter $F$ the rule by which each figure produces the next one. It is monotonous in the following sense: from a smaller figure, according to rules $F$, a smaller one is obtained; more formally it can be written like this:

$$K \subset K' \Rightarrow F(K) \subset F(K').$$

Thanks to this monotony, it is enough for us to consider as initial figures

⟦folio 48⟧

gur only circles. Indeed, every limited figure lies in a certain circle, and even if this circle, under the influence of our rule, turns into an empty set, then the figure containing it, even more so. Circles are convenient because under the influence of $F$ they turn into circles. More precisely:

a) if $K$ is a circle of radius greater than or equal to $1/\sqrt{2}$ (that is, an area greater than or equal to $\pi/2$), then $F(K)$ is also a circle (smaller radius);

6) if $K$ is a circle of radius less than $1/\sqrt{2}$, then $F(K)$ is the empty set.

Consider the function $f(R)$, which defines for $R$ greater than $1/\sqrt{2}$, as follows: if $R$ is the radius of the circle $K$, then $f(R)$ is the radius of the circle $F(K)$. The graph of function $f$ is shown in figure 1. As $R$ increases from $1/\sqrt{2}$ to infinity, function $f(R)$ monotonically increases from $1-1/\sqrt{2}$ to infinity, with its graph remaining all the time below the bissertrix of the coordinate angle $(R-f(R))>0$. It is not difficult to prove that the difference $R-f(R)$ is a monotonically decreasing function of $R$ (tending to zero at $R \rightarrow \infty$). The broken line at figure 1 shows how the radii $R_0$, $R_1=f(R_0)$, $R_2=f(R_1)$, ... behave (at figure 1 it is already $R_3<1/\sqrt{2}$, so at the next stage the result will be an empty set). In the general case, the monotonicity of $R-f(R)$ implies:

$$R_0-R_1<R_1-R_2<R_2-R_3<\dots$$

Hence, denoting $R_0-R_1=d>0$, we obtain that $R_n<R_0-nd$. This means that for some values ​​of $n$ (no more than $R_0/d+1$) the figure $K_n$ will be empty. This proves statement a). (In this proof, the non-ctoral details are only outlined, but in the course of the solution to Problem 6 given below) we will obtain another solution a.).

To cope with point 6), it is necessary to numerically estimate the value at which the radius $R$ of the circle $K$ decreases under the action of the rule $F$. If inside the circle $K$ there is less than a part of our “standard” circle $D$ of radius 1 with the center at the point $M$, then this point is not included in $F(K)$, and, therefore, $f(R)<OM$, where $O$ is the center of the circle $K$. As can be seen from figure 2, this will be the case, for example, when the circumference of a circle $K$ intersects the diameter $AA_1$ of a circle $D$ at the midpoints $B$ and $B_1$ of radii $MA$ and $MA_1$ in this case the area of the segment is $BB_1G$ less than the areas of curvilinear triangles $ABL$ and $A_1B_1L_1$, so the area of intersection of the circle $D$ and $K$ is less than half the area of the circle $D$. Moreover, $OM^2=OB^2-MB^2=R^2-1/4$, thus,

$$f(R)^2<OM^2=R^2-1/4$$

(for any $R>1/\sqrt{2}$), that is, $R_n^2<R_n^{n-1}-1/4$.

From here we conclude by induction that for $R_{n-1}>1/\sqrt{2}$

$$R_n^2<R_n^2-n/4$$

Consequently, a circle of arbitrary radius $R_0$ will disappear in a finite number of steps (which proves statement a)), and this number is not greater than $4R_0^2+1$. For $R_0=100$ it is complete in less than a million, which is what needs to be proven in problem 6).

Tasks 1.

1. Let $N(R)$ be the number of applications of rule $F$ that turn circles of radius $R$ into the empty set. We have proven that $N \leqslant 4R^2+1$. Prove, on the other hand, that $N \geqslant cR^2$, where $c$ is a non-actor positive constant.

2. Let's consider another rule $H$ for transforming figures on a plane. Let us introduce the coordinate system $Oxy$. If a figure $K$ is given, then the new figure $H(K)$ consists of all points $T(x; y)$ for which the intersection of $K$ and a triangle with vertices $(x; y), (x+1; y), (x; y+1)$ has an area of ​​at least half the area of ​​this triangle. Prove that any bounded figure under repeated action $H$ turns into an empty set in a finite number of steps $N$, and for a circle of radius $R$

$$c_1 \cdot R \leqslant N \leqslant c_2 \cdot (R+1),$$

where $c_1$ and $c_2$ are non-actor positive constants.

3. On a white sphere of diameter $d>1$ there is a blue figure $K_0$. Let us associate each point $M$ of the spherer with its “neighborhood” $D_M$ - part of a sphere enclosed in a ball of diameter 1 with center $M$, and a new blue figure $K_1$ is formed from those and only those points $M$ for which the intersection area $D_M$ and $K_0$ is not less than half the area of the neighborhood $D_M$. Similarly, from $K_1$ we get $K_2$, etc.

a) Prove that if the original figure $K_0$ is contained in a ball of diameter less than $d$, then after a finite number of steps the entire sphere will become white.

6) Prove that for any $\varepsilon>0$ it is possible to indicate such a $d$ and such a blue figure $K_0$ of area no greater than $\varepsilon d^2$ on a white sphere of diameter $d$ such that after a finite number of described transformations the entire sphere becomes blue.

b) Are there figures $K_0$ other than the hemisphere for which $K_1$ coincides with $K_0$?

A. L. TOOM
