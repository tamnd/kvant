---
id: 1976-11-gutenmaher-ivlev-rabbot-slozhenie-garmonicheskih-kolebaniy-c618dc27
issue: kvant_1976_11
year: 1976
number: "11"
title: Addition of harmonic vibrations
authors:
  - Гутенмахер В. Л.
  - Ивлев Б. М.
  - Раббот Ж. М.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 46
page_last: 48
page_labels: 44-46
tag: LOL2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4d6b6be470289758dc8dcb277fb49ceaa0736c02373bd08a0663a31558100ee1
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/15_gutenmaher-ivlev-rabbot-slozhenie-garmonicheskih-kolebaniy-c618dc27.md
source_content_sha256: 7882e6961e1e51619536163b024a756f6eee190fc988bb29795da4711f0ae1e1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

Addition of harmonic vibrations

In paragraph 80 of § 16 of the textbook “Algebra and Principles of Analysis 10,” the concept of harmonic oscillation is introduced using the example of the motion of a ball attached to two horizontal springs (Fig. 1). We will not talk here about physical processes in which harmonious vibrations naturally arise. Our goal is to understand the addition of harmonic oscillations of the same frequency.

As we have already noted (Fig. 1), a harmonic oscillation can be represented as an oscillation of the origin point O along the Ox axis. The graph of this movement is the same as that of the function

$$x(t) = A \cos(\omega t + \varphi).$$

The largest deviation of the point x(t) from the point O during the oscillation process is, of course, equal to the number |A| and is called the amplitude of oscillation. The period of oscillation is equal to $$\frac{2\pi}{|\omega|}.$$ Value |ω| called the oscillation frequency. The initial position of the point x(t) (at time t=0) is specified by the value A cos φ.

Of course, the same harmonic oscillation can be given by different formulas.

Using the example of the movement of oscillating points, we apply them, which means the addition of two harmonic oscillations. If one point x₁ with an initial position on the Ox axis A₁cos φ₁ oscillates according to the law x₁(t) = A₁cos(ω₁t + φ₁), and another point x₂ with an initial position A₂cos φ₂ - according to the law x₂(t) = A₂(cos ω₂t + φ₂), then the sum of these oscillations will be the oscillation of a certain point x with the initial position A₁cos φ₁ + A₂cos φ₂ according to the law x(t) = A₁cos(ω₁t + φ₁) + A₂cos(ω₂t + φ₂). It turns out that if points x₁ and x₂ oscillate with the same frequency ω₁ = ω₂ = ω, then their sum will also be a harmonic oscillation of the same frequency ω. This fact in paragraph 82 § 16 of the textbook is derived from the fact that the sum of two solutions to the differential equation y'' = -ω²y is again a solution to this equation (and all its solutions have the form y = A cos(ωt + φ). Is it possible to obtain this result in a simpler way, without knowing differential equations?

You can try to add harmonious vibrations graphically. figure 2 shows graphs of two functions with the same period: y = 2cos(2t + π/3) and y = cos(2t + π/6). From these two graphs it is not at all clear that their sum y = 2cos(2t + π/3) + cos(2t + π/6) will be a harmonic oscillation. So, as we can see, this is not very convenient.

Fig. 1.

⟦folio 45⟧

In the case where $\omega_1 = \omega_2 = \omega$, it is much easier to illustrate the addition of harmonic oscillations using their vector diagrams. Let's explain what it is.

First of all, the conditions for harmonic vibration are written as $A \cos(\omega t + \varphi)$, where $A > 0$, $\omega > 0$ and $\varphi \in [0, 2\pi]$. We can bring any harmonious vibration to this form. Let us now consider some coordinate system $XOY$ and take a circle of radius $A$ with center $O$ at the origin (recall that $A$ is chosen to be positive). Suppose that a certain point $P(t)$ moves counterclockwise along this circle - its position depends on the time $t$ - so that the vector $\vec{OP}(t)$ rotates uniformly, passing $\omega$ radians per unit time ($\omega$ is chosen positive). Let us assume that at the initial moment of time $(t = 0)$ the vector $\vec{OP}(0)$ makes an angle $\varphi$ ($\varphi \in [0, 2\pi]$) with the positive direction of the axis $OX$, that is, that the coordinates of the point $P(0)$ are $(A\cos\varphi; A\sin\varphi)$. Then the angle that the vector $\vec{OP}(t)$ makes with the positive direction of the axis $OX$ at time $t$ is equal to $\omega t + \varphi$, so the coordinates of the vector $\vec{OP}(t)$ are $(A\cos(\omega t + \varphi); A\sin(\omega t + \varphi))$, and we get that the projection of the point $P(t)$ onto the axis $OX$ and the projection of the point $P(t)$ on axis $OY$ perform harmonic vibrations that have the same amplitudes and frequencies! Therefore, a harmonic oscillation of a point, for example, on the $OX$ axis, can be interpreted as an oscillation of the projection of some vector $\vec{OP}(t)$, uniformly rotating around the $O$ point, onto the $OX$ axis. The initial position of the vector $\vec{OP}(t)$, that is $\vec{OP}(0)$, determines the amplitude of the oscillation (it is equal to the length of the vector $\vec{OP}(0)$) and the initial phase $\varphi = (\vec{OP}(0), \vec{OX})$; - only the frequency is missing. The vector $\vec{OP}(0)$ is called the vector diagram of a harmonic oscillation with an amplitude $A$ and an initial phase $\varphi$.

Task 1. Draw vector diagrams of the following harmonic oscillations:

a) $-3\cos\left(2t + \frac{\pi}{3}\right)$; b) $3\cos\left(2t + \frac{4\pi}{3}\right)$; c) $3\cos\left(-2t + \frac{2\pi}{3}\right)$; d) $3\sin\left(2t + \frac{\pi}{3}\right)$; e) $3\sin\left(-2t + \frac{\pi}{3}\right)$.

With the help of vector diagrams, it is already easy to understand the addition of harmonic oscillations. Let's draw vector diagrams of two harmonic oscillations (of the same frequency!): vectors $\vec{OP}_1$ and $\vec{OP}_2$ (Fig. 3). Then the vector diagram of the sum of these oscillations will be the vector $\vec{OP} = \vec{OP}_1 + \vec{OP}_2$. In fact,

⟦folio 46⟧

Fig. 3.

the projections of vectors $\vec{OP}_1(t)$ and $\vec{OP}_2(t)$ onto the axis $OX$ are written as follows:
$$x_1 = A_1 \cos(\omega t + \varphi_1),$$
where $A_1 = |\vec{OP}_1|$, $\varphi_1 = (\vec{OP}_1, \vec{OX})$;
$$x_2 = A_2 \cos(\omega t + \varphi_2),$$
where $A_2 = |\vec{OP}_2|$, $\varphi_2 = (\vec{OP}_2, \vec{OX})$.
The projection onto the $OX$ axis of their sum $\vec{OP}(t) = \vec{OP}_1(t) + \vec{OP}_2(t)$ is equal to $x_1 + x_2$, that is, $A_1 \cos(\omega t + \varphi_1) + A_2 \cos(\omega t + \varphi_2)$, so the vector $\vec{OP}$ is in fact a vector diagram for the sum of the lowest harmonic vibrations.

Note now that the vector $\vec{OP}(t)$ is the diagonal of the parallelogram from the sides $OP_1(t)$ and $OP_2(t)$ (see Fig. 3). Since vectors $\vec{OP}_1(t)$ and $\vec{OP}_2(t)$ rotate with the same angular velocity, the entire parallelogram rotates as a rigid figure. Therefore, its diagonal rotates with the same angular speed $\omega$, so that the projection of the vector $\vec{OP}(t)$ onto the axis $OX$ (abscissa of the point $P(t)$) performs a harmonic oscillation with the same frequency $\omega$ as the projections of the vectors $\vec{OP}_1(t)$ and $\vec{OP}_2(t)$ onto the axis $OX$ (abscissas of points $P_1(t)$ and $P_2(t)$).

It is clear how to calculate the amplitude and initial phase of this sum (the amplitude is the diagonals of the parallelogram, and the initial phase is the angle that this diagonal makes with the $OX$ axis - see problem No. 260 on p. 59 of the textbook).

Task 2. Draw vector diagrams of the sum of oscillations $a$ and $b$, d) and e) from task 1 and find their amplitudes and initial phases.

Using vector diagrams, one more important statement can be proven, namely, that any harmonic oscillation can be represented by the formula $f(t) = a \cos \omega t - b \sin \omega t$. Let's look at this in more detail.

Let us have a harmonic oscillation $A$ cos $(\omega t + \varphi)$ with frequency $\omega$, and let $\vec{OP}(0) = (A \cos \varphi; A \sin \varphi)$ be its vector diagram in the coordinate system $XOY$. Let $\vec{i}$ and $\vec{j}$ be mutually perpendicular unit vectors, given the coordinate system $XOY$ (see paragraph 70 § 14 of the textbook “Algebra and principles of analysis, 9”). Then $\vec{OP}(0) = A \cos \varphi \cdot \vec{i} + A \sin \varphi \cdot \vec{j}$. Let us now assume that the vectors $\vec{i}$ and $\vec{j}$ rotate uniformly and simultaneously with the vector $\vec{OP}(t)$ around the point $O$ with the same angular velocity $\omega$ as the vector $\vec{OP}(t)$. Then $\vec{i}(t) = (\cos \omega t; \sin \omega t), \vec{j}(t) = (-\sin \omega t; \cos \omega t)$. Since the vectors $\vec{OP}(t)$, $\vec{i}(t)$ and $\vec{j}(t)$ rotate like a rigid figure, and at the initial moment of time $\vec{OP}(0) = a \cdot \vec{i} + b \cdot \vec{j}$ ($a = A \cos \varphi, b = A \sin \varphi$), then at the moment of time $t$ the x-th coordinate, that is, the number $A \cos (\omega t + \varphi)$, of the vector $\vec{OP}(t)$ will be equal to the sum $x-x$ coordinates of vectors $a \cdot \vec{i}(t)$ and $b \cdot \vec{j}(t)$, that is $A \cos (\omega t + \varphi) = a \cos \omega t - b \sin \omega t$.

Thus, we presented the harmonic oscillation $A$ cos $(\omega t + \varphi)$ as the sum of two also harmonic oscillations of the same frequency $\omega : a \cos \omega t - b \sin \omega t$ (after all, the sine graph is a cosine graph shifted in phase by a quarter of the period.
