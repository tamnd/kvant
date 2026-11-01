---
id: 1980-1-vyishenskiy-perestyuk-samoylenko-pogovorim-o-differentsialnyih-uravneniyah-00ce43dc
issue: kvant_1980_1
year: 1980
number: "1"
title: Let's talk about differential equations
authors:
  - Вышенский В. А.
  - Перестюк Н. А.
  - Самойленко А. М.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10-14
tag: WSJ1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3747394bbdd23f44551394ad083e335a5db804d4ab5c06776f85ba699281e394
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/05_vyishenskiy-perestyuk-samoylenko-pogovorim-o-differentsialnyih-uravneniyah-00ce43dc.md
source_content_sha256: f985762ec236d5b2cecd90e2c7ee7fdc38aadb691a1f9eed88c22b652b1ad899
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

Let's talk about differential equations

If in ordinary equations solved at school you need to find the numerical values ​​of a certain variable, then in differential equations the required function is the required one, and the equation includes the product of this function. You are familiar with simple differential equations from your school textbook. This is the exponential growth (or decay) equation

$$y' = ky,$$

(1)

where $y = y(x)$ is an unknown function, $k \neq 0$ is a given constant (“Algebra and Elements of Analysis 10”, p. 110), and the equation of harmonic oscillations

$$y'' = -\omega^2 y,$$

(2)

where $y$ is again an unknown function, $\omega > 0$ is a constant (ibid., paragraph 80).

In various areas of human activity, problems associated with differential equations arise. The nature of these problems and the method for solving them can be described approximately as follows. We are studying some process - physical, biological, etc. We are interested in the change over time of some characteristic of this process, that is, a certain quantity (temperature, pressure, mass, etc.). If we have a lot of information about the course of this process, we can try to build a mathematical model of it. In many cases, it is impossible to obtain information about the rate of change of the quantity $y = y(t)$ depending on time $t$, that is, about the derivative $y' = y'(t)$, from experimental data or from physical and other laws. This information can usually be written as a differential equation with an unknown function $y = y(t)$. The resulting equation precisely describes our process from the point of view of its characteristic $y$. Having found all the solutions to the differential equation—in itself this is a purely mathematical problem—we find all possible options for changing the value $y$.

Note that in a mathematical description (such a description is called a model), one always has to make some simplified proposals, avoid certain side effects, accept “ideal” conditions - in a word, abstract from specific details. This leads to known limitations in the application of the constructed model.

The experience of the development of various sciences shows that many different data on the content of the problem lead to the same or similar differential equations. Therefore, it is natural to develop methods for solving such equations regardless of the problems that are given or can lead to them. This is exactly what the mathematical theory of differential equations deals with.

If any problem is related to a differential equation, the methods for solving which are already known, then this problem can be considered solved. In this case, the creative part of the solution ends with the compilation of a differential equation, while the second stage - finding a solution to the equation - will be an important, but purely technical task. There is a complete analogy here with problems related to general algebraic equations.

In this article we will illustrate what has been said using an example of a problem related to differential equations (1) and (2) from school

⟦folio 11⟧

course. Let's start with some filling
ny.

1. Linear differential
equations

The equation $y' = ky$ is called linear-
nom because the function is unknown
$y$ and its product $y'$ are included in it
linear way. As is known from
textbook, any solution to this equation
The opinion is written in the form

$$y = Ae^{kx},$$

(3)

where $A$ is an arbitrary constant.

It turns out that if on the coordinates
on the plane to depict graphs
these decisions under all possible
values ​​$A$, then they will cover the entire
plane, and through each
the plane point will pass exactly
one of the graphs. The plane of the eye is
is called as if “woven” from graphite
fics $y = Ae^{kx}$ (Fig. 1).

Let's prove it, why find it
among functions of the form (3) all those
whose fics go through this
point $(x_0; y_0)$ of the coordinate plane. To determine the constant $A$ we obtain the equation

$$Ae^{kx_0} = y_0,$$

which has a unique solution
$A = y_0e^{-kx_0}$. Therefore, one and only one of the graphs (3) passes through our point - this is

$$y = \left(y_0e^{-kx_0}\right) \cdot e^{kx} = y_0e^{k(x-x_0)}.$$

(4)

The fact we have often received
formulates as follows:
differential equation $y' = ky$ has a unique solution satisfying the initial value

Fig. 1.

condition $y(x_0) = y_0$; this is the solution
is given by formula (4).

More general linear differential
the cial equation is written in the form

$$y' = ky + a,$$

(5)

where $a$ (like $k$) is a constant. Eq.
(5) easily coincides with the already used
following equation (1): if
the right side is written as

$$ky + a = k\left(y + \frac{a}{k}\right)$$

(recall that we consider $k \neq 0$) and denote the function $y + a/k$ by $z$, then

$$z' = \left(y + \frac{a}{k}\right)' = y' = ky + a = kz.$$

Thus, the function $z(x) = y(x) + a/k$ satisfies the equation
nyu $z' = kz$, therefore $z = Ae^{kx}$, that is $y + a/k = Ae^{kx}$, whence

$$y(x) = -\frac{a}{k} + Ae^{kx}.$$

The value of the constant $A$ is again
is uniquely determined if
the initial condition $y(x_0) = y_0$ is given.

This, in essence, is the entire mathematical theory of linear differential equations of the first order, that is, equations, including only their first arbitrary function of an unknown function.

2. Linear Applications
differential equations

Discussed in a school textbook
a number of processes studied by
ry properties to linear differentials
fundamental equation, that is, to the principle
changing the theory stated in paragraph 1.
These are processes of radioactive dis-
pada, posta population and body metabolism. We will look at three more examples from other areas of science.
Let us remind you that the main thing for us is
reduce the problem to a differential equation.

(A) Population growth model
tions of bacteria. Let $N(t)$ be the size of the breeding bacterial population at time $t$. Under ideal conditions $\Delta N(t) = N(t + \Delta t)$ - $N(t)$ during the time from $t$ to $t + \Delta t$ for
many types of bacteria can be considered

⟦folio 12⟧

tabularly proportional number of bacteria having $t$ bacteria at the moment of time; in addition, for small $\Delta t$ the increment $\Delta N(t)$ should be approximately proportional to $\Delta t$.
Thus, with the assumptions made, we can write
$$\Delta N(t) \approx kN(t)\Delta t,$$
where $k > 0$ is a coefficient depending on the type of bacterium. So,
$$\frac{\Delta N(t)}{\Delta t} \approx kN(t).$$
Abstracting from the fact that the number can only change in integers, we will assume that $N(t)$ changes continuously over time. Considering that the last equality should be more accurate, the smaller $\Delta t$ (think about it), after passing to the preposition in it as $\Delta t$ tending to 0, we obtain a differential equation of the form (1):
$$N'(t) = kN(t).$$
Therefore (see point 1),
$$N(t) = Ae^{kt},$$
so the population increases according to an exponential law. If the initial population size is known, that is, the initial condition $N(0) = N_0$, then, following formula (4), we can write
$$N(t) = N_0e^{kt}.$$
(B) Free fall with friction (parachute model). Let a body of mass $m$ fall vertically down from a certain height, and, along with the gravitational force $F_\tau = mg$, it is acted upon by a friction force directed opposite to the velocity, proportional to the magnitude of the velocity: $F_{\tau p} = -\alpha v$, where $\alpha > 0$ is the friction coefficient. Let us determine the dependence of speed on time.
In this case, the differential equation is obtained immediately from Newton’s second law: $ma = F = F_\tau + F_{\tau p}$, that is, $mv' = mg - av$. Dividing both sides by $m$, we again arrive at a linear differential equation, but this time of the form (5):
$$v' = -\frac{\alpha}{m}v + g.$$

IZ (6)
$$v(t) = \frac{mg}{\alpha} + Ae^{-\frac{\alpha}{m}t}.$$
In the case where $v(0) = 0$, we find $A = -\frac{mg}{\alpha}$ and
$$v(t) = \frac{mg}{\alpha}\left(1 - e^{-\frac{\alpha}{m}t}\right).$$

When freely falling without friction ($v' = g$), the value of the return speed is linear: $v(t) = gt$. In the presence of friction, the speed of return nevertheless tends to a constant: with the return of $t$, the value of $e^{-\frac{\alpha}{m}t}$ tends to 0, therefore $v(t)$ tends to the limiting value $v_{\text{np}} = mg/\alpha$ (the graph of the speed value is shown in Fig. 2).

(B) Barometric formula. It is well known that the higher you go, the thinner the air - atmospheric pressure decreases with height. Let's try to determine the dependence of $p = p(h)$ pressure $p$ on altitude $h$ above sea level.

Let us recall that the atmospheric pressure values ​​are taken to be the weight of a vertical column of air with a flat surface.

Fig. 2.
Fig. 3.

⟦folio 13⟧

section $S = 1$ cm$^2$. Therefore, the difference

$$p(h) - p(h + \Delta h) = -\Delta p(h)$$

is numerically equal to the weight of the impact column from height $h$ to height $h + \Delta h$ (Fig. 3), that is

$$-\Delta p(h) = \Delta mg,$$

where $\Delta m$ is the mass of this stolnik. The volume of the stolnik is equal to $\Delta V = S\Delta h = \Delta h$, therefore, if the average impact density in the stolnik is $\rho_{cp}$, then $\Delta m = \rho_{cp}\Delta h$, hence $-\Delta p(h) = g\rho_{cp}\Delta h$ and, finally,

$$\frac{\Delta p(h)}{\Delta h} = -g\rho_{cp}.$$

Let us denote the impact density at height $h$ by $\rho(h)$; then as $\Delta h$ tends to 0, the average density of $\rho_{cp}$ tends to $\rho(h)$, and from the last correspondence we obtain the differential equation

$$p'(h) = -g\rho(h),$$

in which, however, the function $\rho(h)$ is also unknown.

Let us now assume that the temperature of influence is the same in all layers of the atmosphere. Then it is easy to deduce from the Boyle-Mariotte law or from the equation of gas state that pressure is proportional to density$^*$:

$$p(h) = b\rho(h).$$

From this and the previous equalities we obtain the final differential equation

$$p'(h) = -\frac{g}{b}p(h)$$

- it again looks like (1)! Applying the theory from point 1, we find

$$p(h) = p_0 e^{-\frac{g}{b}h},$$

where $p_0$ is atmospheric pressure at sea level, that is, at $h = 0$.

So, pressure kills with height according to the exponential law, in accordance with the obtained so-called

$$*) pV = RT,$$

whence $p = \frac{RT}{V} = \frac{RT}{M} \times \frac{M}{V} = b\rho$, where $b = \frac{RT}{M}$, $R$ is the universal gas constant, $M$ is the molar mass of the gas.

using the barometric formula. The formula we obtained “fails” at altitudes comparable in magnitude to the radius of the Earth. And this is due not only to the fact that we neglected the change in temperature with height, but also to the change in the acceleration of free fall.

Note that in this case the differential equation does not describe a physical process, but simply a change in one physical quantity ($p$) depending on another ($h$).

3. About harmonic oscillations

Let us now dwell on the second of the differential equations studied in school - the equations of harmonic oscillations

$$y'' = -\omega^2 y.$$

As is known from the school course, any solution to this equation is written in the form

$$y(t) = A \cos (\omega t + \varphi),$$

where $A$ and $\varphi$ are arbitrary constants, and we can assume that $A \geq 0$, $\varphi \in [0; 2\pi]$. Under these restrictions, the constants $A$ and $\varphi$ are uniquely determined by the initial conditions, which in this case already require two: $y(t_0) = y_0$ and $y'(t_0) = v_0$.

Note that in this case, through each point $(t_0; y_0)$ of the coordinate plane there are infinitely many graphs of the form (7). However, the graph is determined uniquely if you also specify a tangent to the graph at a given point (explanation). This is due to the fact that equation (2) is of second order, that is, it includes a second arbitrary function of interest.

About the quantity $y$, which changes in time according to the law (7), they say that it performs harmonic oscillations with a frequency $\omega$. It is important to note that the frequency does not depend on the initial conditions, but is determined only by the coefficient in the original equation.

Equations of the form (2) are found in the description of polygonal oscillatory

⟦folio 14⟧

systems, and not only mechanical ones. The textbook examines an example of external vibrations of a ball: if the mass of the ball is $m$, the stiffness coefficient of the spring is $k$, the displacement of the ball from the equilibrium position is $x$, then according to Newton’s second law it is $mx'' = -kx$, hence $x'' = -\omega^2 x$, where $\omega = \sqrt{\frac{k}{m}}$.

Let's look at another example.

Small vibrations of the matrix. Let a ball of mass $m$ be fixed at the end $M$ of a weightless rod $OM$ suspended by a Sharirino at point $O$ so that a matrix (Fig. 4) swings in one plane. It is convenient to change the deviation of the matrix $OM$ from the equilibrium position $OM_0$ by the value $x$ of the angle $M_0OM$, taken in radians.

Two forces act on the ball: the vertical downward direction of the gravity force $F_\tau = -mg$ and the radial direction $MO$ the reaction force of the rod $N$.

Let's write Newton's second law in projections onto the tangent:

$$m(lx)'' = -mg \sin x,$$

that is

$$x'' = -\frac{g}{l} \sin x$$

We will consider only small vibrations of the matrix, that is, we will consider the value $x$ small. Then sin $x$ can be replaced by $x$ (remember that

$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

- “Algebra and principles of analysis 10”, paragraph 78) and from the resulting differential equilibrium we come to the equilibrium of harmonic oscillations

$$x'' = -\frac{g}{l} x,$$

or $x'' = -\omega^2 x$,

where $\omega = \sqrt{\frac{g}{l}}$.

Consequently, for small deviations from the equilibrium position, the oscillations of the matrix will be almost harmonic, with a frequency $\omega = \sqrt{g/l}$, independent of the mass $m$ and the initial conditions, as long as $x_0$ and $v_0$ are sufficiently small.

Of course, the whole variety of natural processes and phenomena cannot be reduced only to the control of two different types. The world of differential equilibria is almost as rich as the real world. The experience of science shows that the use of differential equilibria as mathematical models is very fruitful - of course, if we do not forget about the limited scope of application of any kind of model.

Exercises and tasks

1. Find a solution to the differential equilibrium $y' = -2y + 4$ that satisfies the initial condition $y(0) = 5$.

2. There is a certain amount of radioactive material. It is known that after 30 days, 50% of this substance disintegrates. After how many days will 1% of the initial amount of the substance remain?

3. A body heated to $100^\circ$ was placed in an environment with a constant temperature $20^\circ$. After 10 minutes, the body temperature dropped to $60^\circ$. After what time will the body temperature become $25^\circ$?

(Instructions for tasks 2 and 3. Use examples 1 and 3 from paragraph 110 of the textbook.)

4. 12 hours after the start of the experiment, a certain population of bacteria increased threefold. How many times will the number of bacteria increase in 24 hours?

5. The value of the constant $b$ in the barometric formula for the total effect is $7,7 \cdot 10^4 \text{ m}^2/\text{c}^2$. How high do you need to go to reduce the pressure by half?

6. The boat slows down due to the resistance of the boat. The initial speed of the boat is 2 m/s, and its speed after 4 s is 1 m/s. After how many seconds will the speed of the boat be 0.25 m/s? How far can the boat travel before stopping?

7. A girl swings on a swing. The maximum deviation from the equilibrium position is 1 m, the maximum acceleration is 4 m/s². Assuming the oscillations are harmonic, find their period. Determine the height of the swing.

8. Find the general form of the solution to the differential equilibrium $y'' = -\omega^2 y + a(\omega > 0)$ and $a$ are constants.
