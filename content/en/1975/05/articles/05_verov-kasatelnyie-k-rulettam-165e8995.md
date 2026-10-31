---
id: 1975-5-verov-kasatelnyie-k-rulettam-165e8995
issue: kvant_1975_5
year: 1975
number: "5"
title: Tangents to roulettes
authors:
  - Веров С. Г.
rubric: osnovnye-stati
page_first: 24
page_last: 32
page_labels: 22-30
tag: WZMA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8293a776432181ae554453b2ec7f0099c5184126569ed5ae0a7261e94c0a06c9
prompt_sha256: draft-1
translated_from: content/ru/1975/05/articles/05_verov-kasatelnyie-k-rulettam-165e8995.md
source_content_sha256: dc0e4540596e02e587f9d648f4edd72e41f22d1de43dabe6ccb5b7cb0193ecbd
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

First, let's talk about the technique developed by Torrielli (1608-1647) and Roberval (1602-1675); This technique is based on the addition of speeds.

Let's consider the movement of a material point. If at the moment of time $t_0$ the action of forces stops, then the point will stop or begin to move uniformly along a tangent to the trajectory (the speed of the resulting uniform motion is called the exchangeable vector speed of the original motion at $t = t_0$). This statement follows from Newton's laws. But one can, as mathematicians often did in the 17th century, take it as a cinematic definition of a tangent, making sure that it is consistent with observations of the simplest movements (primarily rotational). Taking this view, we can construct tangents to many interesting curves using only simple facts about speed.

We will consider only plane motion. Let us fix the point $O$ on the plane—the origin. If a moving point at time $t$ occupies position $A_t$, then by $r(t)$ we denote the vector $\vec{O A_t}$. Specifying vectors $r(t)$ for all values ​​$t$ completely defines the motion. We denote the instantaneous vector velocity at time $t$ by $r(t)$; Let us recall that the vector $r(t)$ is directed tangentially to the trajectory of motion. Its length $|r(t)|$ is called the velocity. If the movement occurs along a fixed straight line on which the coordinates are given, then the vectors $r(t)$

⟦folio 23⟧

and $\dot{\mathbf{r}}(t)$ are directed along this line, and they can be characterized by the coordinates $s(t)$ and $\dot{s}(t)$.

Example 1. Galileo showed that for rectilinear motion $s(t)=\dfrac{gt^2}{2}$, the speed will be equal to $\dot{s}(t)=gt$.

Example 2. Let a point located at a distance $R$ from a point $O$ uniformly rotate around $O$. Then the vector $\dot{\mathbf{r}}(t)$ is directed tangent to the circle along which the point moves, in the direction corresponding to the direction of rotation, and $|\dot{\mathbf{r}}(t)|=\dfrac{2\pi R}{T}$, where

$T$ — rotation period (full rotation time). In particular, for $T=2\pi$ we have

$$|\dot{\mathbf{r}}(t)|=|\mathbf{r}(t)|=R.$$

## Law of addition of speeds

Let there be two movements $\mathbf{r}_1(t)$ and $\mathbf{r}_2(t)$. Let's call them *sum* movement for which $\mathbf{r}(t)=\mathbf{r}_1(t)+\mathbf{r}_2(t)$, where the vector sum is on the right. The law of addition of speeds states that the speed of movement $\mathbf{r}(t)$ is equal to $\dot{\mathbf{r}}_1(t)+\dot{\mathbf{r}}_2(t)$, that is, the sum of the (vector) speeds of the component movements. The law of addition of speeds is easy to establish for the sum of movements with constant speeds; the general case is obtained from this particular case by passing to the limit.

Any movement $\mathbf{r}(t)$ can be represented as the sum of two rectilinear movements. To do this, it is enough to introduce any Cartesian coordinate system so that $O=(0,0)$ and consider the change in time of the coordinates $x(t)$, $y(t)$ of the vector $\mathbf{r}(t)$. It is obvious that the initial movement $\mathbf{r}(t)$ will be the sum of movements $x(t)$ and $y(t)$ along the coordinate axes. The velocities of these movements $\dot{x}(t)$ and $\dot{y}(t)$ are components of the vector $\dot{\mathbf{r}}(t)$ (due to the law of addition of velocities).

Consider example 2 with $R=1$, $T=2\pi$, and let the vector $\mathbf{r}(0)$ be directed along the positive direction of the $x$ axis. Then $\mathbf{r}(t)=(\cos t,\sin t)$, $\dot{\mathbf{r}}(t)=(-\sin t,\cos t)$, and we get that $\dot{s}(t)=-\sin t$ if $s(t)=\cos t$, and $\dot{s}(t)=\cos t$ if $s(t)=\sin t$. The reader familiar with differentiation will certainly notice that a very simple kinematic meaning of the formulas for *derivatives* $\sin t$ and $\cos t$ has emerged.

⟦column⟧

## Kinematic definition of a tangent to a parabola

Galileo (1564-1642) discovered that if a body is thrown at an angle to the horizon, it flies in a parabola. When proving this fact, Galileo proceeded from the assumption that such motion is the sum of uniform motion by inertia and free fall. However, Galileo did not use his calculations to construct the tangent to the parabola. Torricelli did it. Its result is formulated in Problems 1 and 2 below.

Problem 1. Prove that the tangent drawn at point $A_t$ of the trajectory of a horizontally thrown body: $A_t=(x(t),y(t))=(vt,-gt^2/2)$ connects this point with point $(0,-y(t))=(0,gt^2/2)$.

All calculations are easily generalized to the case of a body thrown at an angle to the horizon with a speed $(u,v)$. In this case, the movement is divided into movement $\{x_1(t)=ut,\;y_1(t)=vt\}$ with a constant speed $(u,v)$ and free fall $\{x_2(t)=0,\;y_2(t)=-gt^2/2\}$. Therefore, the resulting movement is written as follows: $\{x(t)=ut,\,y(t)=vt-gt^2/2\}$ (when adding vectors with a beginning at $O$, the coordinates of their ends are added).

Problem 2. Prove that the tangent to the parabola along which a body flies, thrown with a speed of $(u,v)$, connects the point of tangency $(x(t),y(t))$ with the point $(0,-y_2(t))=(0,gt^2/2)$.

Note that the method indicated by Torricelli for constructing tangents to a parabola was known before; however, its kinematic interpretation is certainly instructive.

## Tangent to a cycloid

*Cycloid* Galileo called the curve described by a point lying on the boundary of a circle rolling along a straight line (Fig. 1); The name means “coming from a circle.”

23

⟦folio 24⟧

Fig. 1. Cyclonda.

In France, the cyclone, independent of Gaul, was discovered by Mersenne (1588-1648); here it was called roulette or trochoid. The greatest scientists of both Italy and France (Torriceli, Vivanni (1622-1703), Fermat (1601-1665), Descartes (1596-1650), Roberval) solved various problems about the cyclonde. It was probably Vivanni who built the first tangent to the cyclonde. However, since the cyclonde was defined kinematically, it was natural to find a way to construct a tangent to it that would come from kinematic messages. This was done by Roberval and Torricelli.

Let at the initial moment of time $(t=0)$ $O$ be the center of the generating (rolling) circle, and the observed point $A$ be the point at which the generating circle touches the directing line $l$. It is obvious that the movement of the point $A$ is periodic; therefore, it is enough to watch it only until it again falls on the straight line $l$. Let, further, at the moment $t$ the observed point occupies position $A_t = K$ (Fig. 3). Vector $\dot{r}_1(t)$ is directed tangentially to the boundary of the generating circle, vector $\dot{r}_2(t)$ is horizontal; their lengths are the same. According to the rules of parallelogram

$\cdot$ We have $c = \frac{2\pi R}{T}$, where $R$ is the radius of the generating circle, $T$ is the time of its full revolution. In particular, if $T=2\pi$, then $c=R$.

⟦folio 25⟧

Fig. 4.

(in this case it is a rhombus) we find the required speed $\dot{r}(t)$, and therefore the tangent to the cyclone.

Problem 3. Prove that the tangent to the cyclone at point $K$ connects this point with the upper point $D$ of the generating circle at its corresponding position.

(To solve the problem, you only need to prove a simple geometric fact: the vector $\dot{r}(t)$ is directed along the straight line $KD$.)

Note that the value of the speed $|\dot{r}(t)|$ is not constant: it is maximum when the point has taken the most position (in this case, the vectors $\dot{r}_1(t)$ and $\dot{r}_2(t)$ lie on the same straight line and coincide in direction), and is equal to zero when the point falls on the straight line $l$ (in this case, the vectors $\dot{r}_1(t)$ and $\dot{r}_2(t)$ are opposite (Fig. 4)).

It can be shown that the equality of velocity to zero at the points of contact of the circle and the straight line at all times is equivalent to the earlier definition of rolling without sliding.

So, we find that where the cyclone is pointed, the speed of the observed point becomes zero. It turns out that, in general, whatever the trajectory, at the pointed points the speed is always zero. It is sometimes said that a trajectory cannot “break” at non-zero speed. It is commonly believed that curves have no tangents at their sharp points. Everything said here requires serious clarification, but we will not do this.

The normal to the curve at the point $A$ is the line passing through $A$ perpendicular to the tangent at that point.

Fig. 5.

From task 3 it follows that the normal to the cyclone passes through the lower point of the generating circle (point $E$ on figure 3; angle $DKE$ is a straight line, since it rests on the diameter).

Shortened cyclones

So far we have only followed one (fixed) boundary point of the productive circle; however, it is clear that other boundary points will move along the same cyclones, only aligned along the straight line $l$ (Fig. 5). Let us now follow the trajectories of the inner points of the circle. The resulting curves are called shortened cyclones (Fig. 6); they are characterized by the ratio $k = \frac{\rho}{R}$, where $R$ is the radius of the generating circle, $\rho$ is the distance from the center

Fig. 6. Shortened cyclone.

⟦folio 26⟧

Circle to the observed point. For $k=0$ we obtain a straight line along which the center of the circle moves, and for $k=1$ we obtain a cyclonde.

Problem 4. Prove that the normal to the shortened cyclonde passes through the lower point of the generating circle.

Note that a point moving along a shortened cyclonde does not have zero speed anywhere. At the bottom point, the speed is directed horizontally and its magnitude is equal to $R-\rho$. This means that sliding at a speed of $R-\rho$ (translational motion) is added to the rolling motion of a circle of radius $\rho$.

Extended cyclones

Let's use its outer points as a circle (one can imagine that a wheel moving on a rail has a rim on it). These points move along curves called extended cyclones (Fig. 7). All the arguments that were given for shortened cyclones are carried over verbatim to extended ones. There's only $k=\frac{\rho}{R}>1$ here. We only note that at the bottom point of the elongated cyclonde the speed is directed in the direction opposite to the movement of the circle ($|\dot{r}_1|=\rho, |\dot{r}_2|=R, \rho>R$).

Have you noticed that the bottom of the carriage wheel rim moves backwards?

Instantaneous center of rotation

So, we included all the points of the plane as a circle along a straight line. Each point moves along its own trajectory, but all these trajectories agree, since the moving points constitute a rigid body. The characteristic properties of a rigid body from the point of view of kinematics are that when moving, the distances between all its points remain unchanged. We will limit ourselves here to considering only those movements of solid plates that can be performed without removing the plates from the plane (it is forbidden, for example, to turn them over). We will be interested in what restrictions on the speed of a point on a plate are the condition of rigidity (note that the question of the motion of three-dimensional rigid bodies is much more complicated than the plane problem we are considering).

Here are some patterns of movement of solid plates.

Principles of involvement. The movement of a solid plate is uniquely determined by the movements of any two of its lobes. The movement of two different lobes, in which the distance between them is maintained, can, in a unique way, be continued to the movement of the entire plane as a solid plate. This statement is purely geometric in nature. We will not provide evidence of it, limiting ourselves to

⟦folio 27⟧

lacking in visual explanations. Firstly, the movement of a rectilinear rod is completely characterized by the movement of its two points, and, secondly, if a triangle is composed of rigid rods, then the movement of one of them uniquely sets the entire triangle in motion. As a result, the movement of two points, $A$, $B$, can involve the line $AB$, and then any point $C$ outside $AB$.

Principle of hierarchy. If no external forces act on the plate (but only internal forces that ensure rigidity), then it makes a uniform rectilinear or uniform medical movement.

When considering arbitrary motions of plates, we need one fundamental principle of mechanics. The speed cannot change interchangeably (it takes non-zero time to change the speed). In particular, if at the moment of time $t_0$ the forces acting on the moving point are changed, then the speed $r(t_0)$ will not change, which means that if $r(t_0) \neq 0$, the tangent to the trajectory at the moment $t_0$ will not change (although the trajectory itself may become different from this moment).

Let at the moment of time $t_0$ external forces cease to act on the moving triangular plate. Then, on the one hand, the velocities of the point at the moment of time $t_0$ remain the same, and, on the other hand, the movement must obey the formulated principle of inertia. Therefore, when the triangular plate moves, at each moment of time $t$ can change only one of two possibilities:

a) the velocities of all points are equal (as vectors);
b) there is a single point $O_t$ at which the speed is zero; at an arbitrary point $A$ of the plate, the speed is directed perpendicular to the vector $O_tA$, and its magnitude is proportional to the distance from $A$ to $O_t$. (The proportionality factor depends only on time $t$ and does not depend on $A$.)

From the fact that the speed cannot change instantly, it is easy to deduce that the transition from situation $a$ to $b$ and vice versa is possible only at those moments when the plate stops (the velocities of all points are equal to zero). Therefore, in the intervals between stops, either the situation $a$ or the situation $b$ takes place. It can be shown that in the case of $a$ the trajectory of any point $A$ is obtained from the trajectory of some point $B$ by parallel translation to the vector $BA$. We will consider the case $b$ (that is, assume that at each moment of time there is a single point $O_t$ with zero speed). We will call $O_t$ the exchange center of rotation at the moment $t$. (In the example of a circle rolling along a straight line, the instantaneous center of rotation is the point of contact of the circle with the directing straight line).

If the instantaneous center of rotation $O_t$ is known, then the normals to the trajectories at time $t$ (techniques $O_tA_t$), and therefore the tangents, are constructed automatically. On the contrary, if at the moment $t$ the velocities of two points of the plate are known, then taking the point of intersection of the normal to these velocities, we obtain the instantaneous center of rotation $O_t$.

Now let the triangular plate move along a fixed plane. Let us consider on this plane the curve $L$, composed of instantaneous centers of rotation at all moments of time; the curve $L$ is called the fixed center; we'll call it a "rail". On the other hand, consider a curve $C$ on the plane, composed of all such points that turn out to be instantaneous centers of rotation at some instants of time; $C$ is called the moving center; we'll call $C$ "wheel". The introduced “unsevere” terms probably told you that the source

⟦folio 28⟧

This motion can be obtained if we consider the rolling without sliding of our curved “wheel” along a curved “rail” and involve the remaining points in this rolling (Fig. 8).

We will assume that the absence of sliding means that the instantaneous velocities at the points of contact of the “wheel” and the guide “rail” are equal to zero at all times (this is consistent with the definition of the instantaneous center of rotation).

From here we can deduce the equality of the length of the arc of the “wheel” and the corresponding arc of the guide “rail” (on which this arc of the “wheel” rolled). In this case, it is allowed for the “wheels” to intersect the “rail” when rolling.

Often, rolls are understood as trajectories that describe points of the plane during its motion as a solid plate with conditions (6) at all times, that is, with some rolling. For all rolls, we learned how to draw normals and tangents. It turned out that you don’t even need to be able to draw tangents to the “wheel” and “rail” (this would be necessary if you use the addition of velocities).

In our mechanical examinations we have embroidered beyond the 17th century; It was replaced, however, that the method of carrying out the normal to general rolls was discovered by Descartes, who defined them with the help of rolling (without knowing, of course, how general the movements generated by rolling are).

Epicyclopdas

Let us now consider the rolls obtained by rolling a circle in a circle. Let a circle of radius $r$ roll along the outer side of a circle of radius $R$. The trajectories of the boundary points of a rolling circle (“wheel”) are called epicyclopes. Their appearance depends on $k = \frac{R}{r}$ (Fig. 9). If $k$ is an integer, then the movable circle, having rolled once along the border of the fixed one, will make $k$ revolutions and the epicyclope will have $k$ points and $k$ arches. An epicyclope with $k = 1$ is called a cardioid (it resembles a stylized image of a heart). If $k = \frac{p}{q}$ is an irreducible fraction, then the movable circle, having made $q$ revolutions, will roll over the stationary circle $p$ times. If $k$ is an irational number, then there will be no periodicity, and the observed point will never return to its original position.

It can be proven that the infinite trajectory resulting in this case fills the ring ($R \leqslant OA \leqslant R + r$), approaching every point of it as closely as possible, but not hitting every point.

Tangents to epicyclopes are easily constructed using the instantaneous center of rotation - the point of contact of the circle. Prove that the tangent to the epicyclope (at some points) will pass through the point of the corresponding movable circle, diametrically opposite to the point of contact with the fixed one.

Comment. When constructing an epicyclope and solving problems, you need to remember the following. If $A$ is the initial position of the observed point (Fig. 10), and at some instant of time the moving circle touches the fixed one at point $B$, then the epicyclope belongs to a point of its boundaries $C$ such that the arc $BA$ is equal in length to the arcs $BC$; taking into account the difference in radii, we get

$$\frac{BC}{BA} = \frac{R}{r} = k.$$

The trajectories of movement of the internal (respectively, external) points of the moving circle during the considered rolling are called rooted (respectively, studded) epicyclopes (Fig. 11; we limit to integers $k$).

⟦folio 29⟧

⟦figure⟧
Fig. 9. Epicycloids.

⟦folio 30⟧

Hypocyclops

Rolls obtained by rolling a circle of radius $r$ along the inner side of a circle of radius $R > r$ are called hypocyclopses (longened and shortened, respectively).

If $r > R$, then as an analogue of such a movement we can consider the rolling of a hoop of radius $r$, the inner side touching the boundary of a stationary circle of radius $R$. The corresponding rolls are called pericyclopdes. But it turns out that they coincide with epicyclopds (see «Kvant», 1975, No. 1, problem M261).

The type of hypocyclops depends on the arithmetic nature of $k = \frac{R}{r}$, and the reader can easily figure this out on his own by analogy with epicyclops.

Problem 5'. Let the rotations described in Problem 5 occur in opposite directions (one in a clockwise direction, and the other in a counterclockwise direction). What trajectories will point $A$ move along?

Let me emphasize in conclusion that we did not set out to strictly prove all the results we obtained from kinematic messages. In some cases this is easy to do: mechanical reasoning is replaced by mathematical reasoning. Almost automatically (for this it turns out that it is enough to replace the speed with derivatives). In other cases, "substitutes" are more difficult to find (for example, where the movement of plates is considered, or forces change). However, purely mathematical considerations cannot completely replace mechanical interpretation, which in many cases makes it possible to see a simple and clear answer.

Fig. 11. Shortened and elongated epicyclops.

Problem 5. Let the point $A$ rotate uniformly around the point $O_1$, in turn uniformly rotate around the point $O; |OO_1| = r_2, |O_1A| = r_1$. Let both rotations occur clockwise; $v_1$ and $v_2$ are the values ​​of linear speeds. Show that the movement of point $A$ will occur along some kind of epicyclopedia (perhaps shortened or extended). What relationships determine the nature of the curve?
