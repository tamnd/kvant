---
id: 1977-6-lodkin-funktsionalnoe-uravnenie-na-sfere-62f2ac8d
issue: kvant_1977_6
year: 1977
number: "6"
title: Functional equation on a sphere
authors:
  - Лодкин А. А.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 60
page_labels: 57-58
tag: EK09
lang: en
source: kvant_digital
extraction: vision
content_sha256: d0757ce58728cd008cacede11ec75b86a2fb0df4a33eb0d8aafb31b6b7a67d97
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/14_lodkin-funktsionalnoe-uravnenie-na-sfere-62f2ac8d.md
source_content_sha256: 1e36c50f100705fe5d4f7edcd3a66919f10c370331b4ffd6a9b1dff26563173b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

A. Lodkin

Functional equation on a sphere

In this note we will solve a problem that was presented to tenth-class students at the second (research) type X of the All-Union Olympiad in Mathematics. This problem was placed in the “Assignment to Kvanta” («Kvant», 1976, No. 10, M410). Let us recall its formulation.

On a sphere of radius 1 a great circle is drawn, which we will call an equamore. It will be convenient for us to use other geographical terms: stripes, meridian, parallel.

a) Let us define a function f on this sphere that assigns to each point on the sphere the square of the distance from this point to the equatorial plane. Check that this function has the following properties:

if $M_1, M_2, M_3$ are the ends of three mutually perpendicular radii of the sphere, then $f(M_1) + f(M_2) + f(M_3) = 1$. (*)

In all the following paragraphs, f is an arbitrary non-negative function on the sphere, which vanishes at all points of the equamore and has properties (*).

b) Let M and N be points of the same meridian located between the northern stripe and equamore. Let us prove that if point M is further from the equamor plane than point N, then $f(M) \geq f(N)$.

c) Let M and N be arbitrary points of the sphere. Let us prove that if a point M is further from the equamor plane than N, then $f(M) \geq f(N)$.

2) Prove that the function f coincides with the function described in part a).

Solution to problem a)

Problem a) is actually in the school textbook “Geometry 10” (§ 43, problem 14). Here's her solution. Let us be given a rectangular basis (frame) $\vec{OM}_1, \vec{OM}_2, \vec{OM}_3$. Consider the vector $\vec{OP}$, where P are the stripes of the sphere. Let F (M) denote the square of the scalar product of the vector $\vec{OM}$ by $\vec{OP}: F(M) = (\vec{OM} \cdot \vec{OP})^2$. It is clear that F is the same function referred to in part a). The coordinates of the vector $\vec{OP}$ in the basis $\vec{OM}_1, \vec{OM}_2, \vec{OM}_3$, very indo, are equal to the distances from the point $M_1, M_2, M_3$ to the equamor plane. But the scalar square of the vector $\vec{OP}$ is equal to one. This gives us a correspondence function on the sphere, equal to zero at all points of the equamore and having properties (*).

Solving problems b) and c)

It is obvious that point b) of the problem follows from c); Therefore, we immediately prove the statement of point b).

Fig. 1.

⟦folio 58⟧

From condition (*) it follows that the function $f$ takes the same values ​​at diametrically opposite points of the sphere. Therefore, it is enough for us to consider the value of the function only for points in the northern hemisphere.

So, let $M$ and $N$ be two points in the northern hemisphere. Let us prove that if $M$ are further from the equatorial plane than $N$, then $f(M) \geq f(N)$.

Proof. The distance is the circumference of a great circle whose northernmost point is $M$. Let $\Gamma_M$ be the part of this circle lying in the northern hemisphere.

Let us first assume that $N$ also lies on $\Gamma_M$. Let us also denote by $N'$ the point of the soul $\Gamma_M$ that $[ON'] \perp [ON]$, and by $M'$ one of the two points of intersection of the soul $\Gamma_M$ with the equator. Then from (*) the equality $f(N) + f(N') = f(M) + f(M')$ follows, since $[OM] \perp [OM']$ and points $M, M', N, N'$ lie in the same plane, so for points $M, M'$ and $N, N'$ the “third” point will be the same: the end of the radius perpendicular to the plane of the circle $\Gamma_M$. Since $f(M') = 0$, then $f(M) \geq f(N)$.

Let now the point $N$ be in the region of the northern hemisphere lying south of $\Gamma_M$. Then find a point $Q$ on $\Gamma_M$ such that the arc of the great circle $\Gamma_Q$ passes through $N$ (Fig. 2). Applying the previous calculation to the parameter of the point $M$ and $Q$, $N$, we obtain inequalities $f(M) \geq f(Q) \geq f(N)$.

If $N$ lies to the north of $\Gamma_M$, then it may take more than two steps to “descent” from $M$ to $N$. Let us divide the angle $\lambda$ between the meridian planes $m$ and $n$, passing through the points $M$ and $N$, respectively, into $k$ equal parts of the meridian plane $m_1, \dots, m_{k-1}$ (Fig. 3). Let's leave $M$ along the arc $\Gamma_M$ and at the point $M_1$ of the intersection of this arc with the meridian $m_1$ we turn onto the arc $\Gamma_{M_1}$. Having reached the point $M_2$ of intersection $\Gamma_{M_1}$ with $m_2$, we turn to $\Gamma_{M_2}$, etc. The last point of our journey will be point $M_h$ at $n$. You, very indo, noticed that the larger the $k$, the “flat” the descent trajectory. It is not difficult to prove that the latitude $\varphi(M_h)$ of point $M_h$ can suitably approach $\varphi(M)$ (note that $tg\varphi(M_h) = tg\varphi(M_{k-1})\cos \frac{\lambda}{k} = \dots = tg\varphi(M)$) with the help of $M_h$, if $k$ is large enough, it will turn out to be north of $N$. The descent from $M_h$ to $N$ will take more than two steps.

Function $f(M)$ depends only on latitude

Let us denote the parallel located at a distance $Vx$ from the equatorial plane by $\Pi_x$. To solve problem $r$, we will come across one like this.

Lemma. If $x+y+z=1$, we can construct a straight line
