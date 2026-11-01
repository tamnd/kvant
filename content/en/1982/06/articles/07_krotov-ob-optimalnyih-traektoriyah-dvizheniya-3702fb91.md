---
id: 1982-6-krotov-ob-optimalnyih-traektoriyah-dvizheniya-3702fb91
issue: kvant_1982_6
year: 1982
number: "6"
title: About optimal movement trajectories
authors:
  - Кротов С. С.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 35
page_labels: 30, 31, 33
tag: 4GXT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8d67748cafffa5e03bfd8fc1dcd9260c5caf06fb34948d3b4d6e04fede204d41
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/07_krotov-ob-optimalnyih-traektoriyah-dvizheniya-3702fb91.md
source_content_sha256: d3e9762232b5b8ef2613e129c54b438b5031802c3507ece9caa7f611f9c2c1f3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

S. Krotov

About optimal trajectory movements

Many of you have had to solve problems to determine optimal movement trajectories - problems like “determine the trajectory along which, given the conditions of movement, you can get from point A to point B in the minimum time.” At the present time, we are discussing a method that allows a given task of this kind to be approached with only one.

Let's start with a simple task. Let's imagine a boy who finds himself at some moment of time $t_0$ of the average field at point A. We know that from this point A he can move with a speed $v$ in any direction (we mean that the conditions for the boy’s movement from point A are the same in all directions). Let us pose the following question: where might the boy end up after a short interval of time $\Delta t$?

We will assume that on the opposite side of this time interval the boy who started

⟦folio 31⟧

does not change course, and its speed remains unchanged. In this case, the answer is very clear: the boy can end up at any point on the circle with the center at the initial position - at the point $A$ - and with radius $v \cdot \Delta t$.

Let us now assume that a boy in the process of movement can at any moment in time at any point of his trajectory instantly change the direction of speed in an arbitrary manner, keeping it unchanged in magnitude (in this case we will have to endow the boy with supernatural power). And in this case, the answer to the question of the problem is quite simple: since the lengths of all possible trajectories of the boy are equal to $v \cdot \Delta t$, the end of an arbitrary trajectory can end up at any point of a circle of radius $v \cdot \Delta t$ with a center at point $A$. This follows from the fact that the boy’s movement, that is, the distance between the beginning and the end of an arbitrary trajectory in a straight line, along the abscid value, is not greater than the length of the trajectory itself, equal to $v \cdot \Delta t$. Thus, the reachable region (let’s call it the set of points in the field where the boy may be by time $t_0 + \Delta t$) will be a circle of radius $v \cdot \Delta t$.

Let us pay attention to the fact that for any internal point of the reachability region (for example, the point $B$ on figure 1), we can specify an infinite number of trajectories along which the boy could get to it. For any point on the boundary of the reachability region (for example, point $C$ on figure 1), there is a single trajectory of “hitting” (to point $C$ - along the radius $AC$).

If in the future (at $t > t_0 + \Delta t$) the conditions for the boy’s movement across the field remain the same, then at subsequent times the boundaries of the reachable region will also be circles (with the center at point $A$). The boundaries of the area of ​​reachability by the front of all possible movements, or simply by the front. In the previous discussion, the front was a circle, the radius of which increased at a rate of $v$. This simple shape of the front was due to the fact that the conditions for the boy’s movement from point $A$ (and from any point in the area 过剩ness) in all directions were the same. It is easy to see that in the more general case of movement, the front has the following properties:

1) sooner or later the front will pass through any point (meaning points where it is generally possible to get to);

2) with no method of forwarding it is possible to be further than the front in accordance with the moment of time;

3) for each point of the front, you can indicate, as a rule, a single trajectory that ends up in it;

4) when determining the front at subsequent moments of time (that is, when determining the change in the front over time), all points of the original front will simultaneously act as point $A$, so that at any moment of time the front will be an envelope of a set of circles, the centers of which lie on the original front, and the radius is determined by the conditions of “running away” from the corresponding points of the front (Fig. 2);

5) Let us take two positions of the front - $M$ and $M'$, separated by a time interval $\Delta t$ (see Fig. 2). For any point $E$ of front $M$ there is a single point $E'$ of front $M'$ at which one can add at time $\Delta t$; there is only one trajectory of movement. All other points of the front $M'$ can be added from point $E$ only over long times.

The method outlined above for considering motion by constructing a front moving over time can be successfully applied when solving the problem of determining optimal motion trajectories. If

1) we know how the front changes over time, that is, we can build it at each moment in time,

2) to reduce from the entire set of motion trajectories the one that leads to an arbitrary point of the front, then the problem of determining the optimal path of movement is solved as follows: we establish the type of the front over time, determine the moment of time when the front reaches the point within our range, and build a trajectory that realizes hitting exactly this point of the front.

To use the above, consider one auxiliary problem.

Problem. The boy lives on the shore of OR Bay MOR (Fig. 3). The shores of the bay form a hub. The boy's house is at point $A$. The distance from the house to the shore is $h$, and the distance from the house to the point $O$ (see Fig. 3) is $l$. The boy loves fish from the shore of OM. At what distance from point $O$ should he choose a place for the fish in order to reach this place from home in the minimum time? Why

⟦folio 33⟧

Fig. 6.

historical from which to the point $A$ is equal to $|AE| = v \cdot \Delta t_1$ ($|AE| = |AE'|$). It is easy to verify that by time $\Delta t$ the front will be a curve $M'K'KM$, where $M'K'$ and $KM$ are tangents to a semicircle of radius $u \cdot \Delta t$. centered at $A$. These tangents make an angle $\alpha$ with the shore such that $\sin \alpha = u/v$. (In the future, the front will be a curve $M'K'KM$ and a circle of radius $AM$ ($AM'$) with a center at point $A$, lying on the shore. But we are only interested in that part of the front that lies in the “river” region. At any other moment in time, the front will be similar to the front $M'K'KM$ we have constructed.

Now it is clear how to find the optimal impact trajectory (that is, the impact trajectory in the shortest time) from point $A$ to point $B$ of the river, located at a distance $h$ from the shore. This trajectory will be a broken line ACB (see Fig. 5), the segment CB of which is perpendicular to the front passing through the point $B$. Point $C$ is the point of the shore from which the small one should begin to melt. If the distance along the coast from point $A$ to point $B$ is $|AD| = l$, then $|AC| = |AD| - |CD| = l - h$ tg $\alpha = l - h \frac{u}{\sqrt{v^2 - u^2}}$.

Now let us take into account that, according to the conditions of the problem, the speed of the river flow is $w \neq 0$. What will the front look like after time $\Delta t$ from the start of movement? Obviously, the point $M$ of the front (see Fig. 5) will remain in place; the center of the semicircle of radius $u \cdot \Delta t$ will shift from point $A$ to the left (in the direction $w$) to a distance $|AO| = w \cdot \Delta t$. The front in the “river” region will be curve $M'N'NM$ (at figure 6 the NM part of the front is shown); the tangent $MN$ makes an angle $\alpha_1$ with the shore such that

$$\sin \alpha_1 = u/(w + v).$$

Essentially, we divide the construction of points of the section $MN$ of the front into two stages: for each point $M_i$ of the bank, in which the small one ends up after time $\Delta t_i$, we build an “auxiliary front” - the boundary of that area of ​​the river in which the small one can end up after time $\Delta t - \Delta t_i$. This boundary is a semicircle of radius $u \cdot (\Delta t - \Delta t_i)$ centered at point $M_i$. We then move these semicircles to the left (in the $w$ direction) by a distance equal to $w \cdot (\Delta t - \Delta t_i)$. the tangent to all such displaced semicircles is the section $MN$ of the front.

Therefore, in order to get from point $A$ to point $B$ in the least time, the small one must melt from that point $C_1$ of the shore, which is located to the right of the point $C$ (see Fig. 6) at a distance $|CC_1| = w\tau$, where $\tau$ is the time during which the small one will melt. (It is clear that the segment $C_1B$ of the optimal trajectory must be parallel to the segment $AN$.) The distance between points $A$ and $C_1$ is

$$x = |AC_1| = |AD| + |DC_1| = l + |DC_1|.$$

Let's find the length of the segment $DC_1$:

$$|DC_1| = |CC_1| - |CD| = w\tau - h \ tg \alpha_1;$$

of $\Delta BDC$ is located

$$\frac{h}{u\tau} = \cos \alpha_1 \Rightarrow \tau = \frac{h}{u \cos \alpha_1} =$$

$$= \frac{h}{u} \frac{(w + v)}{\sqrt{(w + v)^2 - u^2}}$$

(recall that $\sin \alpha_1 = u/(w + v)$ $\cos \alpha_1 = \sqrt{1 - \sin^2 \alpha_1}$); Thus

$$|DC_1| = \frac{hw}{u \cos \alpha_1} - \frac{h \sin \alpha_1}{\cos \alpha_1} =$$

$$= \frac{h(w^2 - u^2 + wv)}{u \sqrt{(w + v)^2 - u^2}}.$$

So, to get to buoy $B$ in the least amount of time, the small one must melt from point $C_1$, at a distance

$$x = l + h \frac{(w^2 - u^2 + wv)}{u \sqrt{(w + v)^2 - u^2}}.$$

The method we considered for solving the kinematic problem by constructing the front of all possible movements is based on the well-known physical picture of the distribution of possibilities in the environment; the front in this case is the real boundary of the region where the disturbance should be at a given point in time. It is easy to see that when searching for optimal trajectories, we took advantage of the theoretical relationship that exists between the front and the rays, namely the fact that the ray is linear along which the disturbance propagates in the shortest time. The principle of constructing a front, which we proposed, is nothing more than the Heugen principle - a method of constructing the front of propagation of a wave possibility.
