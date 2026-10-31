---
id: 1975-1-ratner-otsenka-fizicheskoy-velichinyi-5a259a0b
issue: kvant_1975_1
year: 1975
number: "1"
title: Estimation of physical quantity
authors:
  - Ратнер Б. С.
rubric: osnovnye-stati
page_first: 24
page_last: 25
page_labels: 22-23
tag: VM3Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7ef9d9f84cd98a6111cce7d4ae9fb18c64e5a6399debb308005830d52b533304
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/06_ratner-otsenka-fizicheskoy-velichinyi-5a259a0b.md
source_content_sha256: 910df5be6c9483fae9dd29a7472b792517925992cd234975bfbcb6b5ae9552ce
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## Estimation of physical quantity
B.S. Ratner

In physics, as well as in other sciences, the values ​​of various quantities obtained as a result of calculations or experiments are determined with unequal accuracy. In some cases, it is important to know the value of a physical quantity with the greatest accuracy, in other cases it is enough to estimate its approximate value. The accuracy of such estimates can vary from an order of magnitude to several percent.

As an example of an estimated, imprecise calculation, we will find the oscillation period $T$ of a mathematical pendulum in a somewhat unusual way. It is known from the school physics course that for small angles of deviation of the pendulum thread from the vertical, the value $T$ is found with great accuracy from the formula $T = 2\pi \sqrt{\dfrac{l}{g}}$, where $l$ is the length of the pendulum thread and $g$ is the acceleration of free fall. Our example is therefore purely

⟦figure⟧
Fig. 1.

⟦folio 22⟧

⟦column⟧

illustrative - no one in real conditions will approximately estimate a value that is already known exactly. But we will immediately know how close to the truth the resulting estimate is.

Let at the initial moment the pendulum be at point $A$ - the point of maximum distance from the equilibrium position $B$, while the thread makes a small angle $\alpha$ (Fig. 1) with the vertical. The period of oscillation $T$ is quadruple the time period $t$, during which the pendulum will describe the arc $AB$:

$$T = 4t = 4\,\frac{\smile AB}{v_{\mathrm{ср}}},$$

where $v_{\mathrm{ср}}$ is the average speed in this section.

Since the angle $\alpha$ is small, the arc $\smile AB$ can be replaced by the chord $AB$. From right triangles $ACO$ and $ACB$

$$AC^2 = l^2 - (l-h)^2$$

And

$$AC^2 = AB^2 - h^2,$$

hence,

$$AB = \sqrt{2lh}.$$

Let's assume that

$$v_{\mathrm{ср}} = \frac{v_0 + v_t}{2} = \frac{0 + \sqrt{2gh}}{2}.$$

Here $v_0$ is the speed at the initial moment of time, and $v_t$ is the speed of the pendulum when passing through the equilibrium position. The inaccuracy of such an assumption is obvious, since it corresponds to uniformly accelerated motion, that is, motion under the influence of a constant force. In our case, the ball is acted upon by a time-varying force—the tangential component of gravity. Unfortunately, it is impossible to obtain a value $v_{\mathrm{ор}}$ that is closer to the true value using elementary mathematics.

Let us substitute the values ​​for $\smile AB$ and $v_{\mathrm{ср}}$ into the expression for the oscillation period $T$ and obtain

$$T = 8 \sqrt{\frac{l}{g}}.$$

⟦figure⟧
Fig. 2.

⟦figure⟧
Fig. 3.

The oscillation period value obtained by estimation is approximately 27% greater than the true value. What causes this discrepancy? Basically, with the value of the average speed we have chosen, replacing the arc with a chord is of little importance. figure 2 shows graphs of force versus displacement for two cases: harmonic oscillation, when force $F_2$ decreases linearly as it approaches the equilibrium position, and used in estimating uniformly accelerated motion, when force $F_1$ is constant. The areas under the graphs, equal to the energy of motion, must naturally be equal. Let's now try to compare the

⟦column⟧

the time intervals spent in both cases. For this we use the dependence $v = v(t)$ (Fig. 3). With uniformly accelerated motion, the graph $v = v_1(t)$ is a straight line. With harmonic oscillation, the curve $v = v_2(t)$ initially goes higher (the tangent of the slope of the curve at $t = 0$ is twice as large as the tangent of the straight line), in the middle of the path the slopes of the curves are approximately the same, and at the end the tangent of the slope of the curve $v_2(t)$ is equal to zero. But the areas under both curves must be equal, since they are equal to the path. Therefore, $t_1 > t_2$, which corresponds to the sign of the discrepancy in the value of the oscillation period.
