---
id: 1976-5-vorobev-troyantsyi-b74d12c9
issue: kvant_1976_5
year: 1976
number: "5"
title: Trojans
authors:
  - Воробьёв И. И.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11, 12, 13, 16
tag: XJGK
lang: en
source: kvant_digital
extraction: vision
content_sha256: ae03ad574a8114af12a1b03cbc6103fdcc12f17cd0eac6d6bea198d161a59c2a
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/03_vorobev-troyantsyi-b74d12c9.md
source_content_sha256: a4644791de4d402ba056c9c82c204fca65911506c8bec7fcc75965771eb1701a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Is it possible to understand how bodies that interact according to the law of universal gravitation move? For example, how do planets move? Suppose that at some initial moments of time we know the exact coordinates of the $n$ planets, their velocities, and it is known that each of the planets is affected only by gravitational forces from the remaining ($n-1$) planets. Based on these initial conditions, it is necessary to determine the movement of the planets in the future.

The laws governing this movement are the familiar Newton's second law and the law of universal gravitation. Using immi, you can imagine the movement of the planets. For a system consisting of two bodies ($n=2$), this problem was first solved by Newton. In this case, it is possible, based on the initial conditions, to determine the state of the system (coordinates of bodies, their velocities, etc.) at any time with any accuracy.

But when scientists began to study a system consisting of several bodies, they encountered enormous difficulties in purely mathematical characterization. Already for the case $n=3$ it was not possible to obtain an exact solution of the problem in the general case. And until midday, despite two hundred and fifty years of efforts by mathematicians around the world, it was not possible to accurately solve this problem using known mathematical means. That is why the “problem $n$ bodies” - as this problem in mechanics is called - has attracted the attention of mathematicians.

Another incentive is the enormous importance of the problem of $n$ bodies for celestial mechanics and astronautics. It is not surprising, therefore, that the total number of works related to it reaches two thousand, and 15-20 new studies appear annually.

⟦folio 12⟧

Now there are a number of methods for approximate solution of the problem of $n$ bodies, allowing for each specific system of bodies with a given specific initial conditions to construct motion trajectories with any accuracy necessary for practice for any limited period of time.

The effectiveness and reliability of these methods have not been tested many times, in particular, when calculating the trajectories of spacecraft and interplanetary stations.

Using precisely these methods, Adams and Le Verrier were able to discover the planet Neptune “at the tip of their pen.”
- Excuse me, but what does difficulty have to do with it? - the reader will be surprised. It’s just that astronomers are big fans of mythology, and a group of astroids with such a common name is connected with the topic of the articles in the following way. But we’ll talk about the Trojans a little later, but for now let’s continue talking about the problem $n$ tel.

Lagrange problem

So, exactly the solution to the problem $n$ has no bodies. But for the partial case $n = 3$ under some “special” initial conditions, exact solutions were found 200 years ago by the remarkable French mathematician Lagrange.

Its solutions—they are called Lagrangian solutions to the $n$body problem—are the only exact solutions of this problem currently known.

In this article we will consider the simplest part of the Lagrange problem.

Let three bodies not lying on the same straight line rotate in concentric circles lying in the same plane with equal angular velocities. That is, these bodies can be considered as points of an imaginary triangular body, rotating a moving axis around it (very

Fig.1.
it is clear that this axis passes through the center of concentric circles - the “orbits” of bodies).

At what arrangement of masses is this possible? At what speed should this imaginary triangular body rotate so as not to “scatter” into parts? This is how Lagrange set his task.

So, let's try to follow Lagrange to solve this problem.

Mass triangle

Let three bodies with masses $m_1, m_2, m_3$ rotate in concentric circles, the center of which is at point $O$ (see Fig. 1). The radii of the orbits of the bodies are $r_1, r_2$ and $r_3$, respectively, the distances $R_1, R_2, R_3$ between the bodies are much larger than the sizes of the bodies. The centripetal acceleration of each point is imparted by the gravitational forces acting on it from its neighbors, i.e., a force equal to the sum (vector!) of these forces. Let us write down the equation of motion of the body:

$$\begin{align*}
F_{12} + F_{13} &= m_1 a_1, \\
F_{21} + F_{23} &= m_2 a_2, \\
F_{31} + F_{32} &= m_3 a_3.
\end{align*}$$

Here $|F_{ij}| = \gamma \frac{m_i m_j}{r_{ij}^2}$ is the value of the Newtonian force with which body $m_j$ acts on body $m_i$. Since all bodies rotate with the same angular velocity $\omega$ (according to the conditions of the problem), then

$$a_1 = -\omega^2 r_1, \quad a_2 = -\omega^2 r_2, \quad a_3 = -\omega^2 r_3,$$

⟦folio 13⟧

Fig. 2.
where $r_i$ is the radius vector of point $m_i$ relative to the center of rotation $O$. (The distances between the bodies are much larger than the sizes of the bodies, so the bodies can be considered points).

All our further reasoning will be purely “arithmetic”, and it may seem at first that they are not relevant to the problem. But it is they who will lead us to the solution of the problem (or rather, the first part of it) - they will allow us to determine the configuration of the bodies.

Let us add the equalities from system (1) term by term:

$$F_{12} + F_{13} + F_{21} + F_{23} + F_{31} + F_{32} = m_1 a_1 + m_2 a_2 + m_3 a_3 = -\omega^2 (m_1 r_1 + m_2 r_2 + m_3 r_3).$$

The left side of this equality is equal to zero - after all, according to Newton’s III law, the sum of all internal forces in a closed system is equal to zero. (The left side can be written like this:

$$\sum_{i,j=1}^{3} F_{ij} + \sum_{i,j=1}^{3} F_{ji} = 0, \text{ так как } F_{ij} = -F_{ji}.$$

So we have

$$m_1 r_1 + m_2 r_2 + m_3 r_3 = 0$$

(since $\omega \neq 0$). Equality (2) essentially specifies the position of the center of rotation: it is located at such a point $O$ that the radius vectors of bodies $m_1, m_2, m_3$ relative to this point must satisfy conditions (2).

Let us introduce the vectors $R_2$ and $R_3$ as shown in figure 2. Then

$$r_1 = r_2 + R_3,$$

$$r_1 = r_3 + R_2.$$

Fig. 3.
Let us express the vector $r_1$ in terms of the vectors $R_2$ and $R_3$. To do this, multiply the first equality from (3) by $m_2$, and the second by $m_3$ and add the resulting equalities term by term:

$$m_2 r_1 + m_3 r_1 = m_2 r_2 + m_3 r_3 = -m_1 r_1$$

(this follows from (2)), we have:

$$(m_1 + m_2 + m_3) r_1 = m_2 R_3 + m_3 R_2.$$

From here

$$r_1 = \frac{m_2}{m_1 + m_2 + m_3} R_3 + \frac{m_3}{m_1 + m_2 + m_3} R_2$$

Thus, the vector $r_1$ is the sum of the vectors $\rho_2 = \frac{m_3}{m_1 + m_2 + m_3} R_2$ and $\rho_3 = \frac{m_2}{m_1 + m_2 + m_3} R_3$ parallel to the sides $R_2$ and $R_3$ of the mass triangle.

Now let’s depict on the diagram of the mass triangle the vectors of forces acting on the body $m_1$ (see Fig. 3). $F_{12}$ is the force acting from the body $m_2$, $F_{13}$ is the force acting from the body $m_3$. These forces are directed along the sides $R_3$ and $R_2$ of the mass triangle. Their result is directed along vector $r_1$ to point $O$ (body acceleration vector $m_1$ is directed to the center of rotation). But this means that the parallelogram of force and the parallelogram built on the vectors $\rho_2$ and $\rho_3$ are similar! Then

$$|F_{12}|:|\rho_3| = |F_{13}|:|\rho_2|,$$

⟦folio 16⟧

equilateral triangles with the base Earth - Moon; vast clouds of cosmic dust. Here, the role of the Trojans is played by myriads of dust particles captured by the compatible attraction of the Earth and the Moon.

Thus, the solutions published by Lagrange in 1772, which the author himself considered only an interesting theoretical problem, turned out to be connected with later astronomical discoveries.

Motion stability

But have we found all the configurations of the three bodies? No, we have not analyzed the case of a rectilinear arrangement of bodies; There is also a similar configuration of three bodies that can rotate as one. It turns out that this configuration is unstable. As soon as you “move” a little from the straight line, the coordination of forces is immediately disrupted, and the deviation begins to increase.

Is the triangular configuration stable? Not always. In 1843, Gachot first determined the conditions for the stability of the Lagrange triangle. He showed that the configuration will be stable if the masses of large bodies (lying at the base of the triangle) are such that their ratio (the ratio of the smaller mass to the larger mass) is sufficiently small and the conditions are met

$$\frac{(m_1 + m_2)^2}{m_1 m_2} > 27.$$

If a cosmic particle, the mass of which is much less than $m_1$ and $m_2$, moving at a relatively low speed, accidentally hits the vertex of an equilateral triangle, at the base of which lie the masses $m_1$ and $m_2$, then it finds itself “trapped”. In this case, the particle can describe a very intricate trajectory near the top

Langrangian triangle, but the entire configuration will rotate as one.

The mass of Jupiter is a thousand times less than the mass of the Sun. Compared to any of them, the total mass of the Trojans is negligible. The stability condition is fulfilled with a large margin. The inequality is also true for the Earth-Moon system: the masses differ by a factor of 81.

How to derive this condition? There may be a simple conclusion, but this problem is still complex and, in any case, requires a special discussion.

Exercises

1. The article does not calculate the angular velocity of rotation of the triangle of masses. Prove that $\omega^2 = \gamma \frac{m_1 + m_2 + m_3}{R^3}$, where $R$ is the distance between the masses.

2. We considered the triangle of masses to be “rigid”. But it turns out that if the velocity vectors are proportional in magnitude to the distances to the center of rotation and are all directed at the same angle to the segments connecting the bodies to the center, then the configuration of the body remains similar to the initial one at any time. An equilateral triangle, rotating, will stretch or contract. Try to prove it.

From the editor

We apologize to our readers for the mistake made in the third issue of the magazine. In the background on the second cover page, the signature of Niels Bohr is followed by the signature not of Felix Klein, but of the physicist Auguste Klein, a great friend of Niels Bohr.
