---
id: 1986-5-veselov-o-matematike-garmonicheskih-kolebaniy-531569eb
issue: kvant_1986_5
year: 1986
number: "5"
title: About the mathematics of harmonic vibrations
authors:
  - Веселов А. П.
rubric: raznoe
page_first: 11
page_last: 15
page_labels: 9-13
tag: MBOG
lang: en
source: kvant_digital
extraction: vision
content_sha256: ee388192c3ced9e4415e985aa01018f71fcc124582dd466229832b4d7ad142d0
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/05_veselov-o-matematike-garmonicheskih-kolebaniy-531569eb.md
source_content_sha256: fd89bae33704b5286362fdc625a10065e1cb0886f9c67f048c71e95c2ed6ac8e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

About the mathematics of harmonic vibrations

Candidate of Physical and Mathematical Sciences
A. P. VESELOV

Oscillations and waves are the main means of understanding the real world, according to the theoretical physicist. Everything can fluctuate - any objects, gases; light, sound, nerve impulses are ultimately types of vibrations.

Academician S. P. Novikov

Soft clocks, ocean waves, swings, the change of day and night, seasonal changes in nature - each of you can add to this list many other examples of oscillatory phenomena. Like many evolutionary processes *), they can be described in the mathematical language of differential equations. Environments of differential equations describing vibrations of one or another

*)Cm. article by V.I. Arnold in «Kvant» No. 2 of this year.

In a different system, the simplest (and therefore the most important) is the equation of a linear oscillator (from the Latin oscillatio - oscillations) (or harmonic oscillator, or harmonic oscillations, or small oscillations of the matrix):

$$\ddot{x} + \omega^2 x = 0.$$

Here $\ddot{x}$ denotes the second product $\ddot{x} = x''(t)$ in time $t$ of the function $x = x(t)$, which describes the deviation of the system from the equilibrium position, and $\omega^2$ is some (of course, positive) parameter.

We will dissect here where and how the equation of a linear oscillator is obtained - although tenth-graders already know about this from the physics course (Physics 10, paragraph 4) - and then we will study it from a mathematical point of view.

Where does the linear oscillator equation appear?

Wherever this equation appears! Judge for yourself.

1. Small vibrations of the matrix. Let a small weight of mass $m$ be suspended on a thin inextensible thread of length $l$, the dimensions of which (a are

⟦folio 10⟧

response and air resistance) can be neglected. Such a system is called a mathematical matrix. Let us consider its swings for small deviations of the thread from the vertical, that is, small α (Fig. 1). Let us denote by x the length of the arc BA: x=lα (α is the value of the angle BOA in radians). Then, decomposing the force of gravity and P=mg into two components T and F (see Fig. 1), we find that the value of F is equal to mgsin α, and the equation of motion according to Newton’s law gives

$$m l \ddot{\alpha} = - mg \sin \alpha,$$

or

$$\ddot{\alpha} = - \frac{g}{l} \sin \alpha.$$

We obtain a (nonlinear) equation regarding the deviation α=α(t). Let us now take advantage of the smallness of α, the limit lim (sin α/α)=1 and replace sin α on the right side with α, that is, we carry out linearization. As a result, we obtain a (linear) equation of the form (*) with ω=\sqrt{g/l}.

2. External body (Fig. 2). When deviating from the equilibrium position by a certain x, the body experiences, according to Hooke’s law, a force F = -kx from the side of the spring, where k is a quantity called the stiffness of the spring. The equation of motion coincides with (*) at ω=\sqrt{k/m}. Of course, here too the expression for the force (and therefore equation (*)) will be accurate only for not very large deviations from the equilibrium position.

3. An oscillatory circuit (Fig. 3), consisting of a capacitor of capacitance C and inductance L. The charge of the capacitor q changes in the absence of active resistance according to the law L\ddot{q}+\frac{1}{C}q=0 (“Physics 10”, paragraph 15), which corresponds to equation (*) for ω=1/\sqrt{LC}.

4. Communicating vessels. If in a tube shaped like the letter U (Fig. 4), the level of a liquid (for example, mercury) is deviated by a certain amount from the equilibrium position, then the liquid begins to alternately rise (and fall) in each of the vertical sections of the tube. If the initial deviation is small (as is the case), the deviation x=x(t) of the liquid level obeys the equation (*).

5. Hydrometer (Fig. 5). If this device, used to measure the density of a liquid, is deviated slightly in depth from the equilibrium position, then, as a result of Archimedes’ law, it begins to oscillate upwards and outwards. These oscillations are also described quite accurately by equation (*) (in any case, until the training begins to take its toll).

Controls (for physics lovers). Find the derivation of equation (*) for the penultimate example (4), expressing ω in terms of suitable parameters.

What do all the examples above have in common? The state of the system is described by one parameter x, which changes around its equilibrium position x=0; on the action system, the force F(x) depends only on the parameter x. Neglecting the energy potential, the change in parameter, according to Newton’s second law, has the form $\ddot{x}=F(x)$. In this case, F(0)=0, since x=0 is the equilibrium position. If the function F(x) has

⟦folio 11⟧

THERE IS A NON-ZERO DERIVATIVE AT ZERO: $F'(0) = \lim_{x \to 0} (F(x)/x) = a$, then for small $x$ we can replace the right-hand side of $(F(x))$ with $ax$. In this case, $a$ must be negative, otherwise no oscillations in the vicinity of zero are possible! Thus, we arrive at the linear equation (*), where $\omega = \sqrt{-a} = \sqrt{-F'(0)}$.

The specified linearization procedure, of course, leads to a nonequivalent differential equation, which nevertheless correctly describes the qualitative picture of the movement towards the equilibrium position. This is bound universally by the linear oscillator equation (*), as well as its name.

Existence and the only solution

It is easy to check that equation (*) satisfies the functions $x = \cos \omega t$ and $x = \sin \omega t$, and therefore their linear combinations, that is, expressions of the form

$$x(t) = a \cos \omega t + b \sin \omega t$$

(check it out!) *. Let us show that this equation has no other solutions.

Let us take advantage of the fact that during the movement the following quantities are conserved

$$E = \frac{1}{2} (\dot{x}^2 + \omega^2 x^2) = \text{const}$$

(law of conservation of energy).

Indeed, $\dot{E} = \dot{x} \dot{x} + \omega^2 x \dot{x} = \dot{x} (\dot{x} + \omega^2 \dot{x}) = 0$, which implies that $E = \text{const}$.

Let us now consider the product of equation (*): $x = x_1(t)$ and its initial data $a = x_1(0)$ and $\beta = \dot{x}_1(0)$. Let us select the coefficients $a$ and $b$ in the expression $x_2 = a \cos \omega t + b \sin \omega t$, so that $x_2(0) = a$, $x_2(0) = \beta$. To do this, just put $a = a$, $b = \beta/\omega$. Let us now make the difference $x(t) = x_1(t) - x_2(t)$, which will be the solution to (*) (check this). Its initial data will be zero: $x(0) = \dot{x}(0) = 0$. Due to the law of conservation of energy

$$E = \frac{1}{2} (\dot{x}^2 + \omega^2 x^2) = \frac{1}{2} (\dot{x}^2(0) + \omega^2 x^2(0)) = 0,$$

where $\dot{x}(t) \equiv x(t) \equiv 0$ comes from, that is

$$x_1(t) \equiv x_2(t) \equiv \alpha \cos \omega t + \frac{\beta}{\omega} \sin \omega t.$$

We have shown that any solution $x_1(t)$ has the form (**), where $a$ and $b$ are uniquely determined by the initial data: In the process of proof, we also obtained a formula for the solution in terms of the initial data.

Running in circles on the phase plane

Let us pay attention to the following circumstances that are worthy of surprise. The perfect number $n$ unexpectedly turns out to be hidden in equation (*), although there was no talk of any circle in the statement of the problem. In fact, all solutions of equation (*) (with the exception of $x(t) \equiv 0$) turn out to be periodic functions of time, and the product of their period by $\omega$ is equal to $2\pi$. Since the number $n$ has appeared, let’s try to look for a circle.

Where to look for it? We will look for it on the phase plane, that is, on the plane with coordinates $(u; v)$, where $u = x$, $v = \dot{x}$. The points $(u; v)$ of this plane are called phase points; they describe the state of the system: coordinate $u = x$ indicates the deviation of the system from the equilibrium position, and coordinate $v = \dot{x}$ indicates the speed of its movement at a given moment in time. Over time, the position of the phase point $(u; v) = (x(t); \dot{x}(t))$ changes, and it describes a certain line on the phase plane, called the phase trajectory. Which one?

⟦folio 12⟧

The quick-witted reader probably thought - isn’t it a circle?

Let's not get ahead of things. So far we only have an ellipse - the energy level line $E = \text{const}$, that is, the line

$$\omega^2 u^2 + v^2 = 2E$$

(1)

(we multiplied by two so as not to bother with unnecessary fractions), shown on figure 6. Due to the law of conservation of energy, the phase point $N(t) = (x(t); \dot{x}(t))$, which at the moment of time $t$ has the energy $E$, will always remain on the ellipse (1), that is, it will move along the ellipse.

Let's construct a circle on its horizontal axis as a diameter and draw a straight line through the phase point $N(t)$, parallel to the axis $Ov$, until it intersects with the circle at point $M(t)$. Then the coordinate along the $x$ axis of the point $N(t)$ will coincide with the coordinate along the $x$ axis of the point $M(t)$, that is, it will be equal to $x(t)$.

Let us transform the expression (**) for $x(t)$, resulting in the formula for an additional argument:

$$x(t) = a \cos \omega t + b \sin \omega t = \sqrt{a^2 + b^2} \cos(\omega t + \varphi),$$

where $\varphi$ is determined from the condition

$$\cos \varphi = \frac{a}{\sqrt{a^2 + b^2}}, \sin \varphi = \frac{-b}{\sqrt{a^2 + b^2}}.$$

By denoting $A = \sqrt{a^2 + b^2}$, we can see that $A = \sqrt{a^2 + b^2} = \sqrt{a^2 + \beta^2/\omega^2} = \frac{1}{\omega} \sqrt{\beta^2 + \omega^2 a^2} = \frac{1}{\omega} \sqrt{\dot{x}^2(0) + \omega^2 x^2(0)} = \sqrt{2E/\omega}$.

Therefore $x(t)$ can be written as

$$x(t) = \frac{2E}{\omega} \cos(\omega t + \varphi).$$

The value $A = \sqrt{2E/\omega}$, characterizing the

max harmonic oscillations is called amplitude, $\omega$ - cyclic frequency, $T = 2\pi/\omega$ - period, $\varphi$ - phase.

Now it is easy to establish that point $M(t)$ will rotate uniformly with angular velocity $\omega$ around a circle with center $O$ of radius $A$. Indeed, if $\varphi$ denotes the angle $uOM$ at the moment of time $t=0$, then the angle $uOM(t)$ is equal to $\omega t + \varphi$ due to the fact that the projection onto the axis $Ou$ of the point $M(t)$ is given by formula (4). We have established that harmonic oscillations are a projection onto a straight line of uniform rotation in a circle, the radius of which is equal to the amplitude of the oscillation, and the angular velocity of rotation is equal to the cyclic frequency.

The equivalent smoothness is that the harmonic oscillation is one of the coordinates of a uniformly rotating vector (in this case $-\vec{OM}$). The length of this vector coincides with the amplitude, and the initial position is determined by the phase. This representation of the vibration is called its vector diagram and is often useful. Try using it to solve the following problems.

Task 1. Prove that the sum of two non-zero harmonic oscillations is a harmonic oscillation if and only if they have the same frequency (or, as they say, the coordinate along the $x$ axis of the point $M(t)$, that is, it will be equal to $x(t)$).

Task 2. Prove that the sum of three harmonic oscillations of the same amplitude and frequency, the phases of which are $\varphi$, $\varphi + (2\pi/3)$ and $\varphi + (4\pi/3)$, is equal to zero.

The latter circumstance plays an important role when using three-phase current, since it is precisely such oscillations that a three-phase alternating current generator produces. By the way, on the vector diagram you will find general reasons for relating standard directions

⟦folio 13⟧

Zhenya 220 volts and 127 volts are approximately equal to $\sqrt{3}$.

Problem 3. How many roots does the equation have on the segment [0, 2]

$$\cos x + \frac{1}{2} \cos(x+a_1) + \frac{1}{4} \cos(x+a_2) + \dots + \frac{1}{2^n} \cos(x+a_n) = 0$$

($a_1, \dots, a_n$ are arbitrary parameters)?

The result of our study of equation (*) is figure 7. Such figure mathematicians call phase portraits or phase diagrams of a differential equation. Our diagram shows that each phase point takes its own ellipse (corresponding to its energy level), while the deviation from the equilibrium position $x(t)$ changes periodically, as well as the speed $\dot{x}(t)$, reaching its maximum values ​​in the equilibrium position. Let us pay attention to the following remarkable property of a harmonic oscillator: the period of its oscillations does not depend on the amplitude! This property is exceptional, which can be seen already in the example of a mathematical matrix, to which we will move on.

About the mathematics of the mathematical matrix

Let us dwell on the theory of the mathematical matrix, now abandoning the assumption of small oscillations (but still assuming that there is no friction). We already know the equation of motion in this case:

$$\ddot{x} + \omega^2 \sin x = 0.$$

Although the form of equation (*) is not very different from equation (*) of a linear oscillator, it is no longer linear, and solving it is not at all so simple. Moreover, it is generally impossible to write down its solution using functions known in school; this requires special functions called elliptic ones. What should I do?

You can get an idea of ​​the solution to equation (*) and the behavior of the mathematical matrix using its phase portrait (Fig. 8), which is constructed using the law of conservation of energy. Let's look at this portrait.

When bold points on the $Ox$ axis correspond to the equilibrium positions - stable (origin of coordinates) and unstable

Fig. 8.

(point $A$ ($\pi; 0$)), that is, the lowest and highest positions of the matrix. The expanding ovals near the point $O$ of stable equilibrium correspond to different modes of matrix oscillation (with different amplitudes); near the point $O$ they are not visually different from the ellipses - the phase trajectories of equation (*)). A walk around such an oval (large or small) reflects the whole oscillation of the matrix, its intersection with the $Ox$ axis is a passage through the source equilibrium position with maximum speed, the intersection with the $Ox$ axis is the extreme deviation of the matrix (zero speed). The wavy trajectories in the lower and upper parts of figure are uneven expressions of the matrix, which, when further push of the present is realized, means that the matnik reaches the upper equilibrium position with a non-zero speed, skips it and continues to rotate, reaching extreme speed values ​​while passing the equilibrium position. The trajectories that separate oscillatory movements from rotational ones are shown in red. These trajectories correspond to motion with an energy level $E_0$ equal to the potential energy of the matrix in the upper (unstable) equilibrium position $A(\pi; 0)$. With this movement, the matrix passes the lower equilibrium position $B(0; v_0)$ with a maximum speed $v_0 = \sqrt{2E_0/m}$ and, gradually slowing down, approaches the upper equilibrium position; it can be proven that it reaches (at a non-left speed) only in an infinite period of time.

Conclusion

We learned a little about the properties of linear and nonlinear oscillators. Please, the most amazing thing about the oscillator is its multilogical and universal requirements: it is difficult to list all those simple and diverse physical systems that are described by equations (*) and (****). The oscillator is part of many systems. For example,

(For the end see p. 43)
