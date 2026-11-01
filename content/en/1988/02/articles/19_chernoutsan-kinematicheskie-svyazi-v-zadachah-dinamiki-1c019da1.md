---
id: 1988-2-chernoutsan-kinematicheskie-svyazi-v-zadachah-dinamiki-1c019da1
issue: kvant_1988_2
year: 1988
number: "2"
title: Kinematic connections in dynamics problems
authors:
  - Черноуцан А. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 59
page_last: 64
page_labels: 57-62
tag: JSBZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: ab774182896302df249607cf2d6bc2d8fa9d1b449b5275f08a4e11b3ff63cc82
prompt_sha256: draft-1
translated_from: content/ru/1988/02/articles/19_chernoutsan-kinematicheskie-svyazi-v-zadachah-dinamiki-1c019da1.md
source_content_sha256: 91347c2003eb69c4ed56421a5ffb65c6cc464e31bb713c943761596f0a15223a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

Kinematic connections in dynamic problems

Candidate of Physical and Mathematical Sciences
A. I. CHERNOUTSAN

In problems in mechanics, a situation often arises when the movement of a body is not free. Constraints can be created by hard surfaces, inextensible threads, rigid rods, etc. In the simplest cases, we take such constraints into account automatically, often without even stipulating their existence. For example, we direct the acceleration of a body on a plane along the plane (taking into account the presence of a solid surface), we consider the speeds of the tug and barge to be the same (taking into account the presence of an unbreakable cable), etc. However, sometimes it becomes necessary to express these restrictions in the form of a special control, which we will call “kinematic coupling”. Let's start with this task.

Problem 1. Find the accelerations of a prism with mass $m_1$ and a cube with mass $m_2$, shown in figure 1, ​​a. Third example.

Let's write down Newton's second law for each body (in projection onto the direction coinciding with the corresponding acceleration):

$$m_1 g - N \sin \alpha = m_1 a_1,$$

$$N \cos \alpha = m_2 a_2.$$

We taught that according to Newton's third law, $\vec{N}_{12} = -\vec{N}_{21}$, i.e. $N_{12} = N_{21} = N$. The two equations written contain three unknowns. The third equation, the kinematic relationship between $a_1$ and $a_2$, should reflect the fact that the cube and prism remain in contact with each other at all times. This can be done in several ways.

1) Let us consider two close positions of the system, separated by a time interval $\Delta t$ (Fig. 1, 6). In triangle $ABC$, side $AB$ is equal to the prism variable $\Delta x_1$, and side $BC$ is equal to

⟦folio 58⟧

moving the cube $\Delta x_2$. We have
$$\Delta x_2 = \Delta x_1 \text{tg} \alpha.$$
Dividing both sides of the equality by $\Delta t$, we get
$$v_2 = v_1 \text{tg} \alpha.$$
Since this correspondence is valid for an arbitrary moment in time, the desired correspondence follows from it
$$a_2 = a_1 \text{tg} \alpha.$$ (3)
We will call this approach to obtaining the kinematic connection the direct method.
2) Another way to obtain the necessary connection is based on switching to the current report system, where the contact condition becomes trivial. In the reporting system associated with the recognition (see Fig. 1, 6), the speed of the cube $\vec{v}_{\text{отн}}$ is directed along its surface, i.e. at an angle $\alpha$ to the vertical. Writing the law of addition of velocities
$$\vec{v}_2 = \vec{v}_{\text{отн}} + \vec{v}_1$$
from the corresponding vector triangle we obtain
$$v_2 = v_1 \text{tg} \alpha, \text{и } a_2 = a_1 \text{tg} \alpha.$$
We solve equations (1)—(3) together and find
$$a_1 = \frac{m_1}{m_1 + m_2 \text{tg}^2 \alpha} g,$$
$$a_2 = \frac{m_1 \text{tg} \alpha}{m_1 + m_2 \text{tg}^2 \alpha} g.$$
In this problem, the second method looks somewhat artificial. However, in some cases, it is the correct choice of the reporting system that can significantly simplify the problem of kinematic communication. Here's an example.
Problem 2. A wedge of height $h$ with an angle of inclination $\alpha$ stands on a flat horizontal plane (Fig. 2). Wedge mass $m_1$. Start from the top of the wedge

allows a block of mass $m_2$ to slide without friction. Find the acceleration of the wedge and the sliding time of the block.
Let's start with Newton's second law. Let’s write it down for the wedge in projection onto the horizontal direction, and for the bar for now in vector form:
$$N \sin \alpha = m_1 a_1,$$
$$\vec{N}_{21} + m_2 \vec{g} = m_2 \vec{a}_2.$$ (5)
As before, $\vec{N}_{12} = -\vec{N}_{21}, N_{12} = N$. The choice of the direction of the axes for the block is associated with the solution of the issue of kinematic connection.
The kinematic relationship between accelerations should reflect the fact that during the movement the block remains on the surface of the wedge all the time. Writing this down as a straight equation turns out to be difficult. Instead, let's go to the reporting system associated with the wedge. In this system, the speed of the block $\vec{v}_{\text{отн}}$ and its acceleration $\vec{a}_{\text{отн}}$ are directed along the wedge. Then from the law of addition of velocities
$$\vec{v}_2 = \vec{v}_{\text{отн}} + \vec{v}_1$$ we obtain the law of addition of acceleration (see Fig. 2)
$$\vec{a}_2 = \vec{a}_{\text{отн}} + \vec{a}_1.$$ (6)
From this we can see that it is more convenient to move from the unknowns $a_1$ and $a_2$ to the unknowns $a_1$ and $a_{\text{отн}}$, thereby solving the problem of kinematic connection. Substituting equality (6) into equation (5) and projecting this equation onto the directions along the wedge surface and perpendicular to it, we obtain
$$m_2 g \sin \alpha = m_2 (a_{\text{отн}} - a_1 \cos \alpha),$$
$$N - m_2 g \cos \alpha = -m_2 a_1 \sin \alpha.$$ (5′′)
From equation (4), (5′′) we find
$$a_1 = \frac{m_2 \sin \alpha \cos \alpha}{m_1 + m_2 \sin^2 \alpha} g,$$
$$a_{\text{отн}} = \frac{(m_1 + m_2) \sin \alpha}{m_1 + m_2 \sin^2 \alpha} g.$$

⟦folio 59⟧

To answer the second question of the problem, we do not need to look for $a_2$, since the sliding time is expressed precisely in terms of $a_{\text{отн}}$:

$$\frac{a_{\text{отн}} t^2}{2} = \frac{h}{\sin \alpha}.$$

From here is

$$t = \sqrt{\frac{2h}{a_{\text{отн}} \sin \alpha}} = \sqrt{\frac{2h(m_1 + m_2 \sin^2 \alpha)}{(m_1 + m_2) \sin^2 \alpha g}}.$$

As already mentioned, the restriction on movement can be determined not only by the direct contact of the bodies under consideration, but also by the presence in the system of connected elements - rods, threads, etc. In most cases, even if this is not specified in the conditions, the connected elements are considered ideal, i.e. threads - weightless and non-stretchable, rods - weightless and absolutely rigid, for blocks, in addition to weightlessness, the absence of friction is also assumed axes. (In fact, the word “weightless” means that the mass of a given element is negligible compared to the masses of other bodies of the system, the word “non-massive” means that the removal of an element is small compared to the movements of the bodies of the system, etc.) Before looking at specific examples, let’s find out what follows from the ideal connected elements. Let's consider three special cases.

1. Weightlessness of the thread. Let's write Newton's second law for a section of thread with mass $\Delta m_{\text{н}}$ (Fig. 3, a):

$$T - T' = \Delta m_{\text{н}} a.$$

Since $\Delta m_{\text{н}} = 0$, then $T = T'$, i.e. the tension force does not change along the thread.

2. Weightlessness of the moving block and absence of friction on its axis. To unwind a weightless block in which there is no friction, no torque is needed. It follows from this that the tension of the same thread on both sides of the block is the same (Fig. 3, b), in addition $T' - 2T = 0$, i.e. $T' = 2T$.

3. Weightlessness of the rod. This condition means that the sum of forces and the sum of moments of forces acting on the rod are equal to zero. For example, if two forces are applied to a rod, then they are equal in modulo, opposite in direction and act along the rod (Fig. 3, c). (Unlike a thread, a rod can be not only stretched, but also bent.)

The inextensibility and rigidity of threads and rods leads to the appearance of kinematic connections, which we will analyze separately in the following tasks.

Problem 3. Find the acceleration of loads of mass $m_1$ and $m_2$ after cutting the upper thread (Fig. 4). The threads and block are considered ideal.

Let's choose the positive direction of the vertical axis down and write Newton's second law for the body:

$$T + m_1 g = m_1 a_1,$$

$$m_2 g - 2T = m_2 a_2$$

(we learned the properties of block and thread described above).

⟦folio 60⟧

To find the kinematic connection between $a_1$ and $a_2$ we apply, as we called it, the direct method. Let us write the length of the thread in the form
$$l = x_2 + \pi R + (x_2 - x_1),$$
where $x_1$ is the coordinate of a load with mass $m_1$, $x_2$ is the coordinate of the center of the block, $R$ is its radius, and taking into account that the length of the thread does not change when the loads move. Then for the movement of goods we obtain the correspondence
$$2\Delta x_2 - \Delta x_1 = 0,$$
where
$$2v_2 - v_1 = 0,$$
$$2a_2 - a_1 = 0.$$ (9)
Solving equation (7)–(9) jointly, we find
$$a_1 = 2a_2 = \frac{2(m_2 + 2m_1)}{m_2 + 4m_1} g.$$
(Notice that $a_1 > g$. Think about why you got that answer.)
Problem 4. A weightless rod with identical loads of mass $m$ at the ends is hinged on an axis that divides its length in the ratio 2:1 (Fig. 5). The rod is held in a horizontal position and at some point released. Find the acceleration of the masses immediately after this, as well as the pressure of the rod on the axle at this moment.

Let's write down Newton's second law for loads, choosing the positive directions of the axes in the direction of the corresponding accelerations:
$$mg - N_1 = ma_1,$$
$$N_2 - mg = ma_2,$$ (10)
where $N_1$ and $N_2$ are the forces acting on the loads from the side of the rod. Since the sum of the moments of forces acting on the weightless rod is equal to zero, then
$$N_1 \frac{2}{3} l - N_2 \frac{1}{3} l = 0,$$
where $l$ is the length of the rod. From here
$$N_2 = 2N_1.$$ (12)
It remains to write down the kinematic relationship between $a_1$ and $a_2$. To do this, let us depict on figure 5 the position of the rod after a short period of time $\Delta t$ after the start of movement. From the similarity we get

Fig. 5.
Fig. 6.
$$x_1 = 2x_2,$$
where
$$v_1 = 2v_2,$$
$$a_1 = 2a_2.$$ (13)
Solving equations (10)–(13) together, we find
$$a_1 = 2a_2 = \frac{2}{5} g,$$
$$N_2 = 2N_1 = \frac{6}{5} mg.$$
Since the sum of the forces acting on the weightless rod is equal to zero, the reaction force of the axis (equal in magnitude to the pressure force on the axis) is equal to
$$N = N_1 + N_2 = \frac{9}{5} mg.$$
* * *

In many problems designed to apply the law of conservation of energy, it is required to find the velocities of bodies at a certain point in time. In this case, it is necessary to establish a kinematic connection not between accelerations, but between the velocities of bodies. When solving such problems, it is useful to use the fact that the total work done by any ideal connecting element is zero. The physical reason for this is that no energy can be stored in such an element - not kinetic (its mass is zero),

⟦folio 61⟧

nor potential (the element is not deformed).

The last statement requires commitment. It can be shown that even with a small deformation of a very rigid rod (or other element), the potential energy of its deformation $E_p = kx^2/2$ can be large - after all, it is proportional to the rigidity of the rod $k$. But if we take into account that the force $F = kx$ arising during deformation remains finite at $k \rightarrow \infty$ (it is determined by the motion of bodies attached to the rod), then the potential energy $E_p = F^2/(2k)$ at large $k$ turns out to be very small.

Task 5*). A load of mass $M$ is first held at the level of the blocks and then released (Fig. 6). Assuming that the threads and blocks are ideal, the sizes of the blocks are small compared to the distance 2l between them, and the mass $m$ of the weights at the ends of the threads is known, find the speed of the load at the moment when the threads make an angle $\alpha$ with the vertical. Examine the answer you receive.

At the moment under consideration, a load with a mass of $M$ is carried at $H = l$ sttg $\alpha$, and loaders with a mass of $m$ have risen by $h = l/\sin \alpha - l$ each. According to the law of conservation of energy,

$$\frac{MV^2}{2} + 2\frac{mv^2}{2} - MgH + 2mgh = 0.$$ (14)

In order to find the connection between $v$ and $V$, you can, for example, use the direct method. From figure 6

$$l^2 + H^2 = L^2.$$

Differentiating with respect to time (and taking into account that $l' = 0$), we find

$$2H \cdot H' = 2L \cdot L'.$$

Since $L' = v$, $H' = V$, and $H/L = \cos \alpha$, we obtain the required connection

$$v = V \cos \alpha.$$ (15)

However, it is easier to get this match from the following messages. Since the consideration $L$ from a load of mass $M$ to the block at the moment under consideration increases with a speed $v$ (at this speed the thread is pulled out), then the projection of the speed $\vec{V}$ of this load on the direction of the thread should be equal to $v$. Considering that the speed $\vec{V}$ is directed vertically, we obtain

$$\dots$$

(*) This and the following tasks are somewhat beyond the level of tasks usually offered at university entrance exams. However, getting to know them is not useless for applicants.

Equation (15).

From equations (14) and (15) we find

$$V = \sqrt{2gl \frac{M \cos \alpha + 2m(\sin \alpha - 1)}{\sin \alpha (M + 2m \cos^2 \alpha)}}.$$

Let's find out whether the central weight will always fall (we consider the threads to be very long) or at some $\alpha$ it will stop and begin to rise. Equation $V = 0$ (stopping condition) is transformed to the form

$$tg \frac{\alpha}{2} = \frac{2m - M}{2m + M},$$

i.e., stopping and reverse movement of goods occurs only at $M < 2m$. If $M > 2m$, then the central load will constantly change and its speed will increase indefinitely ($V \rightarrow \infty$ with $\alpha \rightarrow 0$ - check this yourself). If $M = 2m$, then when the central load is lowered, the system approaches equilibrium, the accelerations of the loads tend to zero, and their speeds tend to the limiting value $V_\infty = \sqrt{gl}$ (check this for yourself).

I would like to draw your attention to the fact that when using the law of conservation of energy, the tension force of the thread was not included in the calculations at all.

The last example illustrates methods for obtaining kinematic connections when moving solid rods (or other solid connections). For example, that when a rigid body moves, the distance between any two of its points does not change.

Problem 6. A weightless rod of length $l$ with weights of mass $m$ at the ends slides along the sides of a right two-legged angle (Fig. 7, a). Find the speed of the loads at the moment when the rod makes an angle $\alpha$ with the horizon. There is no friction. In the initial

⟦folio 62⟧

moment the rod was in a vertical position.

From the law of conservation of energy we obtain

$$mg(l-y) = \frac{mv_1^2}{2} + \frac{mv_2^2}{2},$$

(16)

where $y = l \sin \alpha$ is the coordinate of the second load at a distance of moment. To obtain the kinematic connection, you can use the direct method, as was done in the previous task (do it yourself). Faster and smoother kinematic communication is obtained from such messages. Since the distance between the loads remains unchanged, then at each moment the speed with which the first load “moves away” from the second is equal to the speed with which the second load “approaches” the first. In other words, the projections of the velocities of the loads on the rod at any moment of time are the same (see Fig. 7, a):

$$v_1 \cos \alpha = v_2 \sin \alpha.$$

(17)

Substituting (17) into (16), we find

$$v_1 = \sqrt{2gl \sin^2 \alpha (1 - \sin \alpha)},$$

$$v_2 = \sqrt{2gl \cos^2 \alpha (1 - \sin \alpha)}.$$

In rigid body kinematics, the “decomposition” of complex motion into translational and rotational is often used. To demonstrate this method, we apply it to obtain the kinematic relation (17). In the reference frame associated with the first load, the rod performs a purely rotational motion. This means that in this system the speed of the second load $v_{0\mathrm{T}}$ is directed perpendicular to the rod. Applying the law of addition of speeds $v_2 = v_{0\mathrm{T}} + v_1$ (see Fig. 7, b), we obtain correspondence (17).

It may seem that the found expressions for the velocities provide a complete solution to the problem. However, this problem contains a reciprocal approach, which we will analyze in detail.

The solution would be complete if the second weight could not be torn off the vertical wall. (To do this, it would be possible, for example, to place weights on smooth hoses, and the rod should be hingedly attached to them). However, in our version of the problem (see Fig. 7, a) at some angle the second load will separate from the vertical wall, after which the found answer will not be applicable. The fact is that the horizontal momentum of the system is determined only by the movement of the first load, the speed of which, in accordance with the expression for $v_1$, increases up to a certain angle, and then begins to decrease. This means that at some point the external horizontal force acting on the system must change direction. But there is only one horizontal force - the reaction force of the vertical wall, which cannot change its direction. Thus, at the moment when the reaction of the wall becomes zero, the second load is separated from the wall. Differentiating the expression for $v_1$ with respect to time, we find that $v_1$ is maximum at $\sin \alpha = 2/3$. At an angle of $\alpha = \arcsin (2/3)$ the rod will detach from the vertical wall.

Battles
1. Find the accelerations of the rod and wedge shown at figure 8. There is no friction.
2. Find the thread tension in the system shown in figure 9.
3. (for lovers of tricks and traps). What are the accelerations of the loads in the system shown in figure 10?
4. Find the acceleration of the wedge at figure 11. There is no friction. Note. Apply the method used to solve problem 2 in the article.
