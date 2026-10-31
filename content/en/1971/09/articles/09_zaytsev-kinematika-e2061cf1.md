---
id: 1971-9-zaytsev-kinematika-e2061cf1
issue: kvant_1971_9
year: 1971
number: "9"
title: Kinematics
authors:
  - Зайцев И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 51
page_labels: 47, 49
tag: RNGQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 40ee2d5296521e97beff88ec00343c762434ea11aab681cdf3277ca0f6967c5e
prompt_sha256: draft-1
translated_from: content/ru/1971/09/articles/09_zaytsev-kinematika-e2061cf1.md
source_content_sha256: 3b910c4278b37d6fd6347890b8ddacdbc4e67ddfae0f40d3c48a94c2cd35a986
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

How do you solve kinematics problems? How many formulas do you remember? 5? 10? 15? Very often, solving a problem begins with writing out a large number of formulas - a formula for the path traveled by a body in the $n$ second, a formula for the ratio of the paths traveled by a body over successive periods of time, a formula for the difference in the squares of the body's velocity, and so on. Then they try to substitute these formulas into each other, divide, multiply... In this way they manage to find the answer. But most often, kinematics problems are an insurmountable obstacle. This is perhaps one of the most difficult sections for applicants. Although there must be one of the simplest. Let's look into it.

We will first talk about the primolinear motion of the body. If the straight line along which it moves is taken as the coordinate axis $OX$ (point $O$ is the origin), then the position of the body is determined by its coordinate $x$. When moving with constant acceleration, the coordinate of the body changes with time according to the law

$$x = x_0 + v_0 t + \frac{at^2}{2},$$

(*)

where $x_0$ is the initial coordinate of the body (at $t=0$), $v_0$ is its initial velocity and $a$ is the acceleration. Equation (*) is the kinematic equation of body motion. Of course, equation (*) is a projection onto the axis $x$ of the vector equation for the radius vector $r$, which determines the position of the center of mass of the body (Fig. 1). Therefore, the projection onto the $OX$ axis of those vector quantities that are directed in the same way as the $OX$ axis is positive, and those that are directed in the opposite direction are negative. This must be taken into account when substituting these values ​​into equation (*).

Let us emphasize again: equation (*) is an equation for the coordinates of the body, and not for the path taken by it. Path is a positive scalar that cannot decrease. At the same time, the body coordinate can behave in any way. For example, if $v_0$ is positive and $a=-a_0$ is negative (velocity vector $v_0$ is directed in the same direction)

⟦folio 49⟧

that is, at the moment of falling to the ground, the speed of the stone is equal to the initial one, but directed in the opposite direction.

Equation (**) makes it easy to find the time $t_\pi$ for lifting the stone. Since at the point of maximum rise the speed of the stone is zero, then

$$0 = v_0 - gt_n.$$

Hence $t_\pi = \frac{v_0}{g}$. The time it takes to lift the stone is half the flight time.

We see that two equations - for coordinates and for speed - allow us to obtain an answer to any question regarding the movement of a stone. These are the ones that should always be remembered.

Let's solve one more problem.

Problem 2. A freely falling body has passed $1/3$ of its path in the last second. How many seconds ($n$) and from what height ($h$) did the body move?

We take the throwing point as the origin of coordinates, and direct the coordinate axis vertically downwards. Then the coordinate of the body depends on time according to the law

$$x = \frac{gt^2}{2}$$

($v_0 = 0, x_0 = 0, a = g$). If the body lodged $n$ seconds, the fall time is $n \cdot \tau$ ($\tau = 1$ sec), and

$$h = \frac{gn^2\tau^2}{2}.$$

(1)

After time $(n-1)\tau$ after the start of movement, the coordinate of the body was equal to $\frac{2}{3}h$. That's why

$$\frac{2}{3}h = \frac{g(n-1)^2\tau^2}{2}.$$

(2)

Solving equations (1) and (2) together, we find,

$$n = \frac{\sqrt{3}}{\sqrt{3} - \sqrt{2}} \approx 5,45, \quad h \approx 145 \text{ м}.$$

It was possible to choose another coordinate system, for example, one associated with the earth and an upward coordinate axis. Then the equation of motion of the body would be:

$$x = h - \frac{gt^2}{2} \left( x_0 = h, v_0 = 0, a = -g \right).$$

Here at $t=n\tau$ $x=0$, and at $t=(n-1)\tau$ $x=\frac{1}{3}h$.

You can choose one more coordinate system - with the origin at the throwing point and the axis directed upward. In this system

$$x = -\frac{gt^2}{2};$$

at $t=n\tau$ $x=-h$, at $t=(n-1)\tau$ $x=-\frac{2}{3}h$.

In this problem, the choice of coordinate system is not very important, but often, successfully choosing a coordinate system can significantly simplify the solution.

Let's solve, for example, the following problem.

Problem 3. With what time interval $\tau$ did two djedish drops come off the roof, if after a time $t_0$ after the second drop began to fall, the distance between the drops was equal to $l$?

This problem can, of course, be solved in a roof-related coordinate system (do it yourself).

But it is more convenient to go to the coordinate system associated with the second drop. Since the drops fall with the same acceleration relative to the ground, their relative acceleration is zero: the drops are uniformly relative to each other. Their relative speed is equal to the speed of the first drop relative to the ground at the moment of separation of the second drop $v_0=g\tau$. The equation of motion of the first drop in the coordinate system associated with the second one looks like this:

$$x = v_0 t + x_0,$$

where $x_0 = \frac{gt^2}{2}$. At $t=t_0$ $x=l$, that is

$$l = g\tau t_0 + \frac{gt^2}{2}.$$

Solving this equation, we get the answer:

$$\tau = \sqrt{t_0^2 + \frac{l}{g}} - t_0.$$

Let's solve another problem.
