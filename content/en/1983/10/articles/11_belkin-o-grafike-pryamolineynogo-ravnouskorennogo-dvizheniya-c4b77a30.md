---
id: 1983-10-belkin-o-grafike-pryamolineynogo-ravnouskorennogo-dvizheniya-c4b77a30
issue: kvant_1983_10
year: 1983
number: "10"
title: About the graph of rectilinear uniformly accelerated motion
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 35
page_last: 36
page_labels: 33-34
tag: TSP4
lang: en
source: kvant_digital
extraction: vision
content_sha256: f37791b0113d01256676bcb43679d2e44e759c3a2efda108c1d93ca70abcfb56
prompt_sha256: draft-1
translated_from: content/ru/1983/10/articles/11_belkin-o-grafike-pryamolineynogo-ravnouskorennogo-dvizheniya-c4b77a30.md
source_content_sha256: 6046b82a6c2c4415072de5db5685b86403cf4ba95131bc58cb7f7ff3c43c3129
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

Thus,

$$\Delta s_1 = v_0 \Delta t,$$
$$\Delta s_2 = v_0 \Delta t + a (\Delta t)^2,$$
$$\Delta s_3 = v_0 \Delta t + 2a (\Delta t)^2,$$
$$\Delta s_4 = v_0 \Delta t + 3a (\Delta t)^2,$$
$$\Delta s_n = v_0 \Delta t + (n-1) a (\Delta t)^2,$$

where $n$ is the number of intervals over which we divided the movement time $t$. Since the intervals $\Delta t$ are small, $n$ is large, therefore, on the right side of the last equality we can neglect unity compared to $n$ and assume that

$$\Delta s_n = v_0 \Delta t + na (\Delta t)^2.$$

The total displacement $s$ is equal to the sum of all small displacements $\Delta s_i$:

$$s = \Delta s_1 + \Delta s_2 + \Delta s_3 + \ldots + \Delta s_n,$$

or

$$s = nv_0 \Delta t + a \Delta t^2 (1 + 2 + 3 + \ldots + n).$$

The sum of consecutive natural numbers is equal to the resulting extreme terms multiplied by their number:

$$1 + 2 + 3 + \ldots + n = \frac{1+n}{2} n.$$

Neglecting unity compared to $n$, we get

$$1 + 2 + 3 + \ldots + n = \frac{n^2}{2}.$$

From here

$$s = v_0 n \Delta t + \frac{a (n \Delta t)^2}{2}.$$

But $n \Delta t = t$, and $(n \Delta t)^2 = t^2$, then finally

$$s = v_0 t + \frac{at^2}{2}.$$

About the graph of rectilinear uniformly accelerated motion

When studying mechanical motion, he widely uses graphs showing the dependence of the coordinates of a body on time (motion graph) and the speed of a body on time (velocity graph). The graphs, like the corresponding formulas, fully describe the movements, that is, they allow you to determine the coordinates and speed at any time. But the graph has the advantage of clarity (by constructing a graph of a function, you can “see” the function).

The textbook “Physics 8” provides graphs of motion and velocity for rectilinear uniform motion, as well as velocity graphs for rectilinear uniformly accelerated motion. Using the last graph, a formula was obtained for the displacement $s$, and therefore for the coordinate $x$ of a body moving uniformly accelerated:

$$s = v_0 t + \frac{at^2}{2}, \quad x = x_0 + v_0 t + \frac{at^2}{2}.$$

These formulas, however, can also be obtained by direct calculation (see, for example, the note “Movement during rectilinear uniformly accelerated motion”). No graphs of the movement of this case are given, but it appears to be of considerable interest. This is what we will talk about in this article.

As can be seen from the last formula, the expression for the coordinate during uniformly accelerated motion is a quadratic trinomial. In the general case, the coefficients of $t$ and $t^2$ and the free term are not equal to zero. A graph expressing such a function is called a parabola. Its type and location relative to the coordinate axes depends on three constants - $x_0$, $v_0$ and $a$. figure 1, for example, shows a parabola corresponding to the equation

$$x = 3 + 12t + 3t^2.$$

It describes rectilinear uniformly accelerated motion with an initial speed $v_0 = 12$ m/s and acceleration $a = 6$ m/s². The origin of time is the moment in time when the coordinate $x$ of the body (initial coordinate) was equal to $x_0 = 3$ m. The graph of such movement, strictly speaking, is only the right part of the curve, shown at figure 1 by a solid line.

But if a body of motion along the same straight line and with the same acceleration and up to the moment of time was taken as the origin, then the graph of its motion would be the left part of the curve too (it is shown on figure 1 by the dashed line).

As another example, the consideration of motion presented by

⟦folio 34⟧

Formula

$$x = 2 + 20t - 5t^2.$$

It describes the movement of a body, which at the initial moment of time $t = 0$, when its coordinate was equal to $x_0 = 2$ m, had an initial speed of $v_0 = 20$ m/s and which subsequently moves with a constant acceleration $a = -10$ m/s². This motion is very close to the motion of a body thrown vertically upward (the $X$ axis is directed there) with an initial speed of 20 m/s from a height of 2 m above the Earth. We just, for simplicity, assumed the acceleration of gravity to be equal not to 9.8 m/s², but to 10 m/s². The graph of this movement is shown on figure 2 solid red line.

From figure 2 it is very clear (clearer than from the corresponding formula) how the body moves. First it rises, quickly moving away from the Earth. After 2 seconds it reaches a maximum height of 22 m, after which it begins to move down (fall). The upward movement corresponds to the left branch of the parabola, and the downward movement corresponds to the right branch. In general, a parabola (with two branches) always depicts a “back and forth” movement. The blue line on figure2 shows a graph of the same equal acceleration movement, but with the opposite direction of acceleration.

In mathematics it is proven that a parabola expressing a quadratic trinomial of the form

$$x = x_0 + v_0 t + \frac{at^2}{2},$$

by parallel translation of the coordinate axes can be transformed into a parabola expressing the formula

$$x = \frac{a}{2} t^2.$$

In relation to our case, it is necessary to move the $t$ axis along the $X$ axis to a distance equal to $x_0 - v_0^2/2a$, and the $X$ axis to move along the $t$ axis to a distance equal to $-v_0/a$. In Figures 1 and 2, the axes crossed according to this rule are shown with dashed lines.

This transfer of axes means that the moment when the speed of the body is zero is now taken as the origin of time (when moving “back and forth” such a moment must exist), and the point at which the body is located at that moment is chosen as the origin of the coordinate. After the translation of the axes, the parabola becomes symmetrical to the relative axis $X$. The values ​​of the coordinate $x$ at the moment of time $t$ and $-t$ are the same now, since only $t^2$ is included in the formula and replacing $t$ with $-t$ does not change anything.

Using such a parabola (in new axes) it is easy to find the acceleration. It is clear that the ordinate of the paraboles point corresponding to the moment of time $t = 1$ is equal to $a/2$, from which we find $a$. Acceleration $a$ can be found in another way. If we plot the dependence of $x$ not on $t$, but on $t^2$, then from the formula $x = at^2/2$ it is clear that
