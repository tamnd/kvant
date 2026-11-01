---
id: 1979-6-resheniya-zadach-m515-f527-f529-9ac62eae
issue: kvant_1979_6
year: 1979
number: "6"
title: Problem solutions M515; F527—F529
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 19
page_last: 25
page_labels: 17, 18, 21, 22, 23
tag: OUOZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 73750691e23eb6e4afb030d3c358660b4e77334242ca5f30eac165ca3b3521d6
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/08_resheniya-zadach-m515-f527-f529-9ac62eae.md
source_content_sha256: cac3f27e74224000546fe7936380ab359611fca053057bebb504df54bf6cc0a3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

lα formed by the rod on one side of this angle, the acceleration of the core of the rod (point C), if end B of the rod moves with a constant speed v?

F579. In the circuit shown at figure 2, $R_1 = 10$ Ohm, $R_2 = 20$ Ohm, $R_3 = 15$ Ohm, the direction in the alternating current network is $U = 10$ V. Determine the power that is allocated to resistors with resistances $R_2$ and $R_3$.

G. Komkin

F580. In the circuit shown in figure 3, the emf of the battery is $\&$, its internal resistance is $r$, and the resistance of the resistor is $R$. When the key $K_1$ is closed, the galvanometer needle $G$ deviates by an angle $\alpha$. At what angle does the galvanometer needle deviate if key $K_1$ is closed when key $K_2$ is closed? The deflection of the needle is proportional to the charge passing through the galvanometer.

F581. A man stands in front of a mirror with one eye closed. He covers the image of a closed eye in the mirror by pecking a piece of paper onto the mirror. What will a person see if he opens his closed eye and closes his open one?

F582. A body floats in water such that $2/3$ of its volume is immersed in water. What part of the volume of the body will be under water if a vessel with water is moved by acceleration $a$ in the upper direction?

Problem solutions
M515; F527—F529

In this problem we study the following operation on an arbitrary figure (set of points) Ф:

$$W(\Phi) = \bigcup_{M \in \Phi} S_M(\Phi)$$

— symmetrical images of the figure Ф relative to different points $M \in \Phi$ are considered and their union is taken (over all points $M$). Obviously always $W(\Phi) \supset \Phi$ and

$$\text{ если } \Phi \subset \Phi', \text{ то } W(\Phi) \subset W(\Phi').$$

Clarification of specific questions posed in conditions for a sequence of the form

$$\Phi, W(\Phi), W^2(\Phi) = W(W(\Phi)), \dots, W^n(\Phi) = W(W^{n-1}(\Phi))$$,

obtained by repeated application of the operation $W$ to some finite set $\Phi$, we will include in a small study, during which we will, in essence, learn to find the convex hull of the figure $W^n(\Phi)$ - the smallest convex set containing $W^n(\Phi)$ - for an arbitrary figure $\Phi$, and note a number of interesting properties of the operation $W$.

⟦folio 18⟧

6) Let $K_0$ consist of three vertices of a regular triangle of area 1. Find the area of ​​the smallest convex polygon containing the sets $K_n$ ($n=1,2,\dots$).

In the next three paragraphs, $K_0$ is the set of four vertices of a regular metrahedron of volume 1.

8) Distance of the smallest convex polygon containing all points of the set $K_1$. How many and what boundaries does this polygon have?

e) What is the volume of this polygon?

d) Find the volume of the smallest convex polygon containing the sets $K_n$ ($n=2,3,\dots$).

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

Before reading the solution below, draw the figures $W(\Phi)$ and $W^2(\Phi)$ if $\Phi$ is a pair of points; segment; rectangle; four straight/lib vertices; three vertices of a triangle. What is $W(\Phi)$ if $\Phi$ is a cube? eight vertices of a cube?

Let's start with the “one-dimensional” case, when the figure $\Phi$ lies on a line. This case is needed to solve problem a), but, as we will see, it is also useful in more difficult problems.

Let first our figure be a segment $\Pi=[AB]$ of length $d$ with its midpoint at point $O$. Then $\Phi(\Pi)=[A_1B_1]$ is a segment of length $3d$ with its midpoint at the same point $O$. It immediately follows that $\Phi^2(\Pi)=[A_2B_2]$, where $|A_2B_2|=9d$, and in general $\Phi^n(\Pi)=[A_nB_n]$, where $|A_nB_n|=3^n d$, and all segments $[A_nB_n]$ have a midpoint at the same point $O$ (Fig. 1).

In what follows we will represent the figures $\Phi$, which has a center of symmetry $O$, and in tomothenia with coefficient $k$ and center $O$ denoted by $k\Phi$. We found out that if $\Pi$ is a segment, then $W(\Pi)=3\Pi$ and in general $W^n(\Pi)=3^n\Pi$.

Looking ahead, we note that this is true for any centrally symmetric convex figure $\Pi$. But first, let’s answer question a) according to the law in the one-dimensional case.

a) Let $K_0=\{A,B\}$, $|AB|=1$. According to (2), where $\Phi=\{A,B\}$, $\Pi=\Phi'=[AB]$,

$$K_n=\Phi^n(K_0)\subset\Phi^n(\Pi)=3^n\Pi.$$

It is clear that $K_n$ contains all points of the segment $[A_nB_n]=3^n\Pi$, located at an integer distance from the point $A$, and the extreme points $\{A_n,B_n\}=3^n\{A,B\}$ are located from $A$ at distances $(3^n-1)/2$ and $(3^n+1)/2$ (Fig. 2). Since these numbers (Fig. 3) are greater than 10,000 at $n\geqslant10$, the answer to question a is $n=10$.

In solving plane and spatial problems about the operation $W$, its following property is very useful: if $\Phi_l$ is the projection of the figure $F$ onto the line $l$, then

$$W(\Phi_l)=(W(\Phi))_l$$

(the projection of $W(\Phi)$ onto the line $l$ is the same as the result of applying $W$ to the projection $\Phi_l$) *. This immediately follows from the definition of $W$ and the fact that in the projection, points symmetrical with respect to the point $M$ fall into points symmetrical with respect to its projection $M_l$ (Fig. 4).

It follows from this that if $\Pi$ is a strip, and $3^n\Pi$ is its image under tomotomination with the coefficient $3^n$ relative to the center of symmetry (any point on the middle line), then the correspondence $\Pi$ is fulfilled - the set of points enclosed between two planes.

From (2), (3), (5) and the solution to problem a) it also follows that if we enclose the figure $F$ in a supporting strip $\Pi$ of any direction - such a strip $\Pi\supset\Phi$, the edges of which contain all points from $\Phi$, - then the strip $3^n\Pi\supset W^n(\Phi)$ will be the supporting strip for $W^n(\Phi)$ (Fig. 5). This message, generalizing (4), allows us to find the convex hull $W(\Phi)$ for any figure $F$.

Let's look at specific examples.

6) Let $K_0=\{A,B,C\}$ be the vertices of a regular triangle, $K_n=W^n(K_0)$, $n=1,2,\dots$(Fig. 6). Let us prove that for any $n\geqslant1$ the convex hull of the set $K_n$ is obtained as follows: we need to take the ends of the segments $3^n[AB]$, $3^n[BC]$ and $3^n[AC]$ and construct a convex hexagon $\Sigma_n$ with vertices at these points.

*) The projection of a spatial figure $F$ onto a line $l$ is the set of points $M\in l$ such that the plane, the projection through the points $M$ and perpendicular to $l$, intersects $\Phi$.

⟦folio 21⟧

F527. In the circuit shown in figure 8, the emf of the battery is $G=100$ V, its internal resistance is $r=100$ Ohm, the capacitance of the capacitor is $C=200$ uF and the resistance of the cutter is $R=10$ Ohm. Key K switches between condensates a and b with a frequency of $f=10$ times per second. When connecting it to terminal a, the capacitor is fully charged, and when connected to terminal b, it is fully charged. What is the efficiency of the circuit? How many times is it higher than when the cutter is connected directly to the battery? What power is released at resistance $R$?

Fig. 8.

When a capacitor is connected to a battery, it charges to voltage $U=\mathcal{E}$, receiving charge $q=CU=\mathcal{C}\mathcal{E}$. The energy of the capacitor becomes equal to $W=\frac{1}{2}C\mathcal{E}^2$.

The battery does work $A=\mathcal{E}q=\mathcal{C}\mathcal{E}^2$. Consequently, the amount of heat $Q$ released in the circuit is equal to $A-W=\frac{1}{2}C\mathcal{E}^2$. The battery is connected in series with the heated one, and at any given time the same current flows through them. Consequently, heat is distributed between them in proportion to their resistances, that is, heat is released on heating $R$

$$Q_1=(A-W)\frac{R}{R+r}=\frac{C\mathcal{E}^2}{2}\frac{R}{R+r}.$$

When the capacitor is closed on the heater (keys $K$ in position $6$), the capacitor is fully charged and its energy $W$ turns into heat released on the heater:

$$Q_2=W=\frac{C\mathcal{E}^2}{2}.$$

So, in one full cycle you heat up the heat

$$Q=Q_1+Q_2=\frac{C\mathcal{E}^2}{2}\frac{R}{R+r}+\frac{C\mathcal{E}^2}{2}=\frac{C\mathcal{E}^2}{2}\left(\frac{2R+r}{R+r}\right).$$

The circuit efficiency is

$$\eta_1=\frac{Q}{A}=\frac{C\mathcal{E}^2}{2}\frac{2R+r}{R+r}=\frac{2R+r}{2(R+r)}=\frac{6}{11}.$$

When connected directly to the battery, the efficiency of the circuit is equal to

$$\eta_2=\frac{R}{R+r}=\frac{1}{11}.$$

Thus, $\eta_1/\eta_2=6$.

Let's find the power $P$ released by heating. In 1 second, $n=f/2$ complete key switching cycles $K$ occur. Hence,

$$P=nQ=\frac{f}{2}\frac{C\mathcal{E}^2}{2}\left(\frac{2R+r}{R+r}\right)\approx 5,5\text{ Вт.}$$

At.mechane. In the conditions of the problem, it is proposed to assume that the capacitor succeeds in completely recharging in a time of $t=1/f=0,1$ seconds. Let's check how correct this assumption is.

When a capacitor is connected to a battery, the resulting current is $I=\mathcal{E}/(R+r)$. During the time $t$, after which the capacitor is charged to voltage $U=\mathcal{E}$, a full charge $q=C\mathcal{E}$ passes through the battery. Therefore, at current $I=\mathcal{E}/(R+r)$ the capacitor is charged in time $t=q/I=C\mathcal{E}/(R+r)/\mathcal{E}=C(R+r)=2,2\cdot 10^{-2}\text{ c}$. In reality, as the voltage across the capacitor increases, the current will decrease, and the capacitor will not be charged at all to voltage $U=\mathcal{E}$. However, since $t\gg t$, the approximation can be considered that the capacitor succeeds in being fully charged.

A. Zilberman

◆

The power $P$ released by the light bulb is equal to $U_\pi I$, where $U_\pi$ is the voltage on the light bulb, $I$ is the current in the circuit. Possible relationships between $U_\pi$ and $I$ are determined by the current-voltage characteristic of the light bulb (Fig. 9). On the other hand, the voltage across the light bulb is determined by the corresponding

⟦folio 22⟧

a constant direction nick $U=10B$ in series with a resistor with resistance $R=4\Omega$. Determine the power of the light bulb.

![Graph](image)

Fig. 9.

F529. Using the formula made for an advertising poster (Fig. 10), determine: 1) the focal length of the photo camera object; 2) at what distance from the palms of the hands was the lens located when formulating; 0) the size of the fish caught by the fisherman; 4) diameter of the object (assuming that the size of the image details on the formula does not exceed 0.2 mm). The formula lens is treated as a monocular lens.

Sheniem

$$U_{\pi}=U-U_R=U-IR,$$

where $U_R$ is the voltage across the resistor. Consequently, for a given value of resistance $R$ $U_{\pi}$ and $I$ are determined by the point of intersection of straight line $U-IR=10-4I$ (it is called the load straight line) with the current-voltage characteristic of the light bulb. Drawing the load straight line on the graph, we find the values ​​$U_{\pi}$ and $I$ corresponding to point $A$:

$$U_{\pi}\approx 5,5\ B, \ I\approx 1,2\ A.$$

Therefore, the power released by the light bulb is equal to

$$P=U_{\pi}I\approx 6,6\ Bt.$$

I. Slobodetsky

The perspective in the photograph is greatly distorted. Various details of the object (the fisherman's face, the palms of the hands, etc.) are formed at different magnifications.

Magnification is usually called the ratio of the dimensions of the image and the object, equal to the ratio of the distances from the line to the image plane (that is, to the photographic film) and from the object to the line. In our case, the magnification of all parts is less than one. A noticeable difference in the magnification of the face and hands could only be obtained when formulated at close range.

A technique for estimating that the size of the fisherman’s face is $l_1\approx 20$ cm, the width of the palms of his hands is $l_2\approx 10$ cm, and the distance from the face to the palms of his outstretched arms is $a\approx 50$ cm. Let us denote the distance from the palms of the hands to the object by $x$, and the distance from the object to the photographic film by $y$. On the formula, the size of the face is $h_1\approx 1,5$ cm, the width of the palms is $h_2\approx 1,5$ cm. The magnifications $\Gamma_1$ and $\Gamma_2$ of these details are expressed relative to our

$$\Gamma_1=\frac{h_1}{l_1}=\frac{y}{x+a}, \ \Gamma_2=\frac{h_2}{l_2}=\frac{y}{x},$$

where

$$x=\frac{l_2}{h_2}\ y, \ y=\frac{ah_1h_2}{l_1h_2-l_2h_1}.$$

From these expressions after substituting numeric values

$$x\approx 50\ cm, \ y\approx 7,5\ cm.$$

⟦folio 23⟧

Since in the photograph the distance between the palms is $h \approx 8$ cm, we can conclude that the size of the glade fish is

$$l = \frac{h}{\Gamma_2} = \frac{h l_2}{h_2} \approx 53 \text{ см.}$$

To determine the formula distance $F$ of an object and its diameter $D$, it is necessary to take into account that the object being formulated in our case has a significant size along the optical axis (depth). The near point (palm) is located at a distance of about 50 cm from the object, and the far point (face) is at a distance of about 100 cm. It is clear that the lens cannot give a simultaneous clear image of both of these points (and all intermediate ones) on photographic film, which is located at a distance of $y \approx 7,5$ cm behind the lens. As the rays travel from the far (A) and closest (B) points of the object, only some intermediate point $C$ appears, lying somewhere between the closest and far points. Clear images of points $A$ and $B$ lie in front and behind the photographic film, respectively, and on the film their images are obtained in the form of spots of size $\Delta$, which, according to the conditions of the problem, do not exceed 0.2 mm. Assuming for estimation that the shaping point $C$ is located at a distance of $x + a/2 \approx 75$ cm in front of the lens, we write using the linear formula,

$$\frac{1}{x + a/2} + \frac{1}{y} = \frac{1}{F}.$$

From here, after substituting the numerical values, $F \approx 6,8$ cm is found. As can be seen from figure 11, in order for the sharpness of the image of all details to be sufficiently high at a significant depth of the object, the camera lens must be strongly re-frammed, that is, the diameter $D$ of the open part of the object must be sufficiently small. Determining the position of the image $B_1$ of the nearest point $B$ using the linear formula -

$$\frac{1}{x} + \frac{1}{d_1} = \frac{1}{F}$$

- and making an estimated proportion

$$\frac{D}{d_1} = \frac{\Delta}{d_1 - y},$$

we find after substituting numerical values: $d_1 \approx 7,9$ cm; $D \approx 4$ mm. (Of course, the image position of the farthest point $A$ could be used to estimate the object's diameter.)

So, our estimates give:

1) formula: camera object distance $F \approx 6,8$ cm; 2) when formulating the object, it was located at a distance of $x \approx 50$ cm from the palms; 3) the fish managed to try a fish measuring about 53 cm; 4) the camera lens was apertured to 4 mm.

S. Kozel
