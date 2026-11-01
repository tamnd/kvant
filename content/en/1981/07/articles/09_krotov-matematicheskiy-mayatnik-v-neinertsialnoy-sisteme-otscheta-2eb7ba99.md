---
id: 1981-7-krotov-matematicheskiy-mayatnik-v-neinertsialnoy-sisteme-otscheta-2eb7ba99
issue: kvant_1981_7
year: 1981
number: "7"
title: Mathematical pendulum in a non-inertial frame of reference
authors:
  - Кротов С. С.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 35
page_labels: 32-33
tag: TIZ9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 76eafaf149eae282d2f2285ee3c394fcc90224e26b99599be087dddbb0a97315
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/09_krotov-matematicheskiy-mayatnik-v-neinertsialnoy-sisteme-otscheta-2eb7ba99.md
source_content_sha256: 3568fd55c17289ba1272bd3a0eb3bd92177ff5c05f08f4de4ee5bf8d8d4ab7f5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 32⟧

There should be much less than the change $\Delta v$ of velocity along the tangent, that is
$$\Delta v_r \approx a_r \Delta t = \left( \frac{e v_{cp} B}{m} \right) \Delta t = \frac{e \cdot \Delta v \cdot B \cdot \Delta t}{2m} \ll \Delta v.$$
Hence the constraint for $\Delta t$:
$$\Delta t \ll \frac{2m}{eB}.$$
So, for $B = 10^{-4}$ T
$$\Lambda t \ll \frac{2 \cdot 9 \cdot 10^{-31}}{1,6 \cdot 10^{-19} \cdot 10^{-4}} \approx 10^{-7} \text{ с}.$$
At $r = 10^{-2}$ m
$$\Delta v = \frac{1,6 \cdot 10^{-19} \cdot 10^{-4} \cdot 10^{-2}}{2 \cdot 9 \cdot 10^{-31}} \approx 10^{5} \text{ м/c} \ll c.$$
A. Zilberman

Mathematical math book in a non-inertial reporting system

What is the task of describing the movement of a mathematical matrix - a small load on a weightless nit? We must, knowing the initial position and initial speed of the load, be able to determine its position at any subsequent time. In other words, we must determine the explicit form of the dependence $x = x(t)$ and $y = y(t)$, where $x$ and $y$ are the coordinates that determine the position of the weight in the plane of its motion.

Let us consider the equation that describes the movements of a mathematical matrix of length $l$ when its suspension point is stationary relative to the ground. Let us choose the coordinate axes $OX$ and $OY$ as indicated in figure 1. Let at some point in time during the motion of the matrix, the thread makes a vertical angle $\varphi$ (the angle $\varphi$ is absent from the axis $OY$ counterclockwise). Equation of load motion - equation P of Newton's law
$$m \vec{a} = m \vec{g} + \vec{T} \tag{1}$$
($\vec{T}$ is the tension force of the threads) in projections on the axes $OX$ and $OY$ has the form
$$m a_x = -T \sin \varphi, \tag{2}$$
$$m a_y = m g - T \cos \varphi. \tag{3}$$
Since the nit length matrix is ​​unchanged during movement, there is a correspondence between the coordinates $x$ and $y$ (kinematic connection)
$$x^2 + y^2 = l^2,$$
and to describe the motion of the matrix it is enough to know the time dependence of any one coordinate.

A more natural coordinate that describes the motion of the matrix is ​​the angle $\varphi$.

Finding the dependence of $\varphi(t)$, we thereby determine the time dependence of coordinates $x$ and $y$:
$$x(t) = l \sin (\varphi(t)),$$
$$y(t) = l \cos (\varphi(t)).$$
Let us rewrite equations (2) and (3), substituting in them the values
$$a_x = v'_x = x'' = -l(\varphi')^2 \sin \varphi + l\varphi'' \cos \varphi,$$
$$a_y = v'_y = y'' = -l(\varphi')^2 \cos \varphi - l\varphi'' \sin \varphi$$
and multiplying (2) by $\cos \varphi$ and (3) by $\sin \varphi$. We get
$$l\varphi'' \cos^2 \varphi - l(\varphi')^2 \sin \varphi \cos \varphi + \frac{T}{m} \sin \varphi \cos \varphi = 0, \tag{2}$$
$$-l\varphi'' \sin^2 \varphi - l(\varphi')^2 \sin \varphi \cos \varphi + \frac{T}{m} \sin \varphi \cos \varphi - g \sin \varphi = 0. \tag{3}$$
Subtracting $(3')$ from $(2')$, we obtain a differential equation that satisfies the function $\varphi(t)$:
$$\varphi'' + \frac{g}{l} \sin \varphi = 0. \tag{4}$$
In the case of small deviations of the nit matrix from the vertical sin $\varphi \approx \varphi$, and equation (4) becomes the equation
$$\varphi'' + \frac{g}{l} \varphi = 0,$$
which is the equation of harmonic oscillations with frequency $\omega = \sqrt{\frac{g}{l}}$. The general solution to such an equation has the form
$$\varphi = \varphi_0 \cos \left( \sqrt{\frac{g}{l}} t + \Phi \right),$$
where $\varphi_0$ is the oscillation amplitude, $\Phi$ is the initial phase. The quantities $\varphi_0$ and $\alpha_0$ are determined uniquely on the initial conditions.

Let now the suspension point of the mathematical matrix of motion be accelerated $\vec{b}$ relative to the stationary - inertial reporting system (Fig. 2). The acceleration $\vec{a}$ of the weight (point $A$) relative to this system can be

⟦folio 33⟧

but represent it as a vector sum
$$\vec{a} = \vec{a}' + \vec{b},$$
where $\vec{a}'$ is the acceleration of point $A$ relative to the non-inertial reporting frame, which moves with acceleration $\vec{b}$ relative to the non-inertial reporting frame. Equation (1) will now be written as follows:
$$m\vec{a}' + m\vec{b} = m\vec{g} + \vec{T}.$$
From here
$$m\vec{a}' = m\vec{g} + \vec{T} - m\vec{b} = m(\vec{g} - \vec{b}) + \vec{T}.$$
Equation (5) differs in form from equation (1) by the presence of a constant vector $m(-\vec{b})$, which has the dimension of force. Thus, if we want to use Newton’s PN law in a non-inertial reporting system moving relative to the inertial system with constant acceleration $\vec{b}$, then to the real forces acting on the weight - the weight force $m\vec{g}$ and the tension force of the thread $\vec{T}$, we must add a constant vector $m(-\vec{b})$. This vector is called the inertial force. In equations (5) we combined the vector $m(-\vec{b})$ with the force vector $m\vec{g}$. In this notation, (5) represent the equation of the PJ of Newton’s law for a weight on which the tension forces of the thread $T$ and the force $m(\vec{g} - \vec{b})$, which plays the role of the weight forces, act. The introduction of such a new “gravity force” $m(\vec{g} - \vec{b})$ gives us a new direction of the “horizontal” - perpendicular to the new vertical.

The transformations that are given from equation (1) to equation (4) are also applied to equation (5). You just need to remember that the equilibrium position of the matrix in a non-inertial reporting frame is given by the direction of the new vertical; The angle of deviation of the matrix from the equilibrium position is also measured from this vertical; the speed of the matrix (weight) is its speed relative to the reporting system moving with acceleration $\vec{b}$.

Fig. 1.

Fig. 2

When using energy relations (the law of conservation of mechanical energy) in a non-inertial reporting system, we can use the formula notation
$$m\vec{g}'h' + \frac{m(v')^2}{2} = \text{const},$$
where $g' = |\vec{g} - \vec{b}|$, $h'$ is the height, the absence of the pendulum along the new vertical, $v'$ is the speed of the body relative to the non-inertial reporting frame. The planes perpendicular to the vector $\vec{g} - \vec{b}$ now become equivalent surfaces.

Let us now move on to the solution problem F663 from Problem Book «Kvant». Let us recall its conditions.

F663. A heavy cart moves with speed $v_0$ along a horizontal plane and drives onto an inclined plane making an angle a with the horizontal. Transition between swimming planes. A ball is hanging on a thread on a thread $l$ long. What will be the amplitude of the oscillating ball when the cart is brought onto the inclined plane?

We must, very much, consider the motion of the matrix relative to a non-inertial reporting system - a cart moving equal to
