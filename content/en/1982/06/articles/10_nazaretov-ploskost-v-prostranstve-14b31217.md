---
id: 1982-6-nazaretov-ploskost-v-prostranstve-14b31217
issue: kvant_1982_6
year: 1982
number: "6"
title: Plane in space
authors:
  - Назаретов А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 41
page_labels: 38-39
tag: PQ64
lang: en
source: kvant_digital
extraction: vision
content_sha256: ed85da63525dfcdcc999f6e0265b94e2ed67fbfd0a81c95949f417ac6b58b6b9
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/10_nazaretov-ploskost-v-prostranstve-14b31217.md
source_content_sha256: 6defcf130fd5ae6cf8c1ce87316714793a5352a86d729e394d8f421e183bbe60
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Flatness in space

In § 45 of the textbook “Geometry 9-10” it is proved that the graph of any equation of the first degree*) $ax+by+cz+d=0$ is a plane perpendicular to the vector with coordinates $(a; b; c)$.

It follows that the planes defined by the equations

$$a_1x+b_1y+c_1z+d_1=0 \quad (1)$$
$$a_2x+b_2y+c_2z+d_2=0 \quad (2)$$

are parallel if and only if there exists a $\lambda$ such that $a_2=\lambda a_1$, $b_2=\lambda b_1$, $c_2=\lambda c_1$.

Obviously, the planes with equations (1), (2) coincide if and only if there exists a $\lambda$ such that $a_2=\lambda a_1$, $b_2=\lambda b_1$, $c_2=\lambda c_1$, $d_2=\lambda d_1$.

Underlining again. The transition from an equation of the first degree to a plane (its graph) is unambiguous: each equation of the first degree is a graph of a unique plane that fulfills a certain plane. (They say “a plane with equations $ax+by+cz+d=0$” or even “a plane $ax+by+cz+d=0$”.) The reverse transition - from a plane (in coordinate space) to an equation - is not at all unambiguous: each plane can be given an infinite set of equations; if the plane $\Delta$ is the graph of the equation

py $ax+by+cz+d=0$, then it is also the graph of any equation $(\lambda a)x+(\lambda b)y+(\lambda c)z+(\lambda d)=0$. Each of these equations is called the $\Delta$ plane equation.

In the same paragraph of the manual it is proved that in the coordinate space of each plane there is a graph of a certain first-degree equation.

In particular, the equation of the plane passing through the point $M(x_1; y_1; z_1)$ and perpendicular to the (non-zero) vector $\vec{n}=(a; b; c)$ is $a(x-x_1)+b(y-y_1)+c(z-z_1)=0$.

If the solution to problem 28 in the same paragraph, set out in the manual, is repeated “in general form”, we obtain that the distance from the point $K(x_0; y_0; z_0)$ to the plane $ax+by+cz+d=0$ is equal to

$$\frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}.$$

Task 1 (MGMI, 1981). Write an equation of the plane perpendicular to the axis $Ox$, perpendicular to the vector with coordinates $(1; 0; 0)$. Therefore, the required equation has the form $1(x-3)+0(y-2)+0(z-4)=0$ or $x-3=0$, $x=3$. However, the last form of the answer can be communicated without presentation.

Task 2 (MIET, 1981). Find the distance between parallel planes $x-y+2z-4=0$ and $x-y+2z-10=0$.

The required distance is obviously equal to the distance from an arbitrary point of the plane $x-y+2z-4=0$, for example from the point $K(0; 0; 2)$, to the plane $x-y+2z-10=0$. Using the ready-made formula, we get the answer $\sqrt{6}$.

Task 3 (MIIVT, 1980). Find the equation of the plane passing through the points $M(0; 1; 0)$, $N(1; 1; 1)$ and $K(0; 0; 1)$.

Let $ax+by+cz+d=0$ be the original equation. Substituting the coordinates of the point $M, N, K$ into it, we obtain a system of three equations with four

⟦folio 39⟧

Fig. 1.

Fig. 2.

Fig. 3.

unknown:

$$\begin{cases}
b+d=0 \\
a+b+c+d=0 \\
c+d=0
\end{cases}$$

Hence $b=-d, c=-d, a=d$. This means that the required equation has the form $dx-dy-dz+d=0$ or (since $a, b$ and $c$ are not equal to $0, d \neq 0$ at the same time) $x-y-z+1=0$.

Problem 4 (MGMI, 1981). Write an equation for the plane passing through Ox and the point M(3; 2; 4).

The plane passing through Ox contains, for example, the points (1; 0; 0) and (2; 0; 0) - the problem has been reduced to the previous one. We can, however, immediately report that the equation of the plane passing through Ox has the form $by+cz=0$.

Problem 5 (MEPhI, 1978). Point A(1; 0; 3), B(-1; 3; 4) and C(1; 2; 1) belong to the plane α. For what value of k does the point M(k; 2; 5) also belong to the plane α?

We find the equation of the ABC plane (problem 3) and substitute the coordinates of the point M into it. Somewhat shorter, using the coplanarity of the vectors $\vec{AB}, \vec{AC}$ and $\vec{AM}$, expand the vector $\vec{AM}$ into the vectors $\vec{AB}$ and $\vec{AC}$: $\vec{AM}=\mu \vec{AB}+\nu \vec{AC}$; Having rewritten this vector equality in coordinate form, we obtain a system of three equations with the third variables μ, ν, k.

Problem 6 (MIHM, 1981). Find the uelem between planes $-3y+z+2=0$ and $2y+z-5=0$.

We will find the required angle α using the angle β between vectors perpendicular to these planes. Angles α and β may not coincide. By definition (Geometry 9-10, § 38) $0^\circ \leq \alpha \leq 90^\circ$. The angle β between vectors, by definition (“Geometry 9-10”, § 24), is contained between $0^\circ$ and $180^\circ$. Obviously (Fig. 1), $\alpha=\beta$ or $\alpha=180^\circ-\beta$. Therefore $\cos \alpha=|\cos \beta|$.

Task 7 (MISIS, 1980). Find a plane between the plane passing through the points A(0; 0; 0), B(1; 1; 1) and C(3; 2; 1), and the plane passing through the points A(0; 0; 0), B(1; 1; 1) and D(3; 1; 2).

First, we find the equation of the planes ABC and ABD (problem 3), then we find the equation for them (problem 5).

Problem 8 (MIIVT, 1981). For a right four-level notch, the ratio of the length of the side edge and the side of the base is equal to 2. Find the diagonal BD$_1$ of the notch and the plane BC$_1$D.

Let us introduce a coordinate system as shown in Fig. 2 and set $|AB|=a$. Next, we successively find the coordinates of point B, C$_1$ and D, the equation of the plane BC$_1$D (problem 3), the coordinates of point D$_1$ and vector $\vec{BD}_1$.
