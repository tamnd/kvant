---
id: 1988-11-12-gorodetskiy-garmonicheskie-kolebaniya-ad0b1956
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Harmonic vibrations
authors:
  - Городецкий Е. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 66
page_last: 69
page_labels: 64, 65, 67
tag: CGCS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 40345ccf2cb9f5d6b9a49a8af1801a3f5f9d882c39b0b7e8c234a4db6df96187
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/21_gorodetskiy-garmonicheskie-kolebaniya-ad0b1956.md
source_content_sha256: 8dac022000be44baddba29443b853d8519904fe7a3e140f93170d1b4279e82e7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 64⟧

Harmonic vibrations

Candidate of Physical and Mathematical Sciences
E. E. GORODETSKY

The mechanism for the occurrence of free harmonic oscillations in any mechanical system is always the same. This emergence arose for the purpose of moving the system away from a stable equilibrium position. This article will focus only on harmonic oscillations. Although nature arose referring to each specific case may be different, the equations of motion that describe the vibrations are the same.

Most oscillation problems look something like this. A certain system is given that can oscillate around its position.

naya balance. The method for generating oscillations is known, i.e., the initial conditions are specified. Question one: find the frequency (or period) of oscillations. Question two: find their amplitude and initial phase and write down the dependence of the oscillating value on time. Question three: find after what time (or what fraction of a period) the oscillating quantity takes on a given value. We will illustrate the answers to these questions by finding a well-known example of the attached matrix. We formulate a general algorithm for solving problems of this type.

Problem 1. Given the system shown in figure 1. Body mass m, spring stiffness k. The body was displaced from the equilibrium position on the right by an amount x₀ and pushed to the left, giving it a speed v₀. Find the frequency, amplitude, and initial phase of the oscillations. There is no friction.

Let us write Newton’s second law for the body in projections onto the X axis:

⟦folio 65⟧

$$F_{\text{упр}} = ma,$$
where $F_{\text{упр}}$ is the elastic force acting on the body from the spring, $a$ is the acceleration of the body. If the deviation of the body from the equilibrium position at an arbitrary moment of time $t$ is equal to $x$, then according to Hooke’s law $F_{\text{упр}} = -kx$. Acceleration of a body along a certain second arbitrary coordinate in time: $a = x''$. Now the equation of body motion can be written in the form $mx'' + kx = 0$.

This equation, like the equation of any other oscillations, is the sum of two terms: one of them includes an unknown function of time (in this case $x$), and the other - a second arbitrary function of this time ($x''$).

As is known, the solution to such an equation is the harmonic function

$$x = x_m \sin(\omega t + \varphi_0).$$

Here $x_m$ is the amplitude, $\omega$ is the frequency (more precisely, the cyclic frequency), $\varphi_0$ is the initial phase of the oscillations. By directly substituting the solution into the equation it is easy to find the oscillation frequency:

$$\omega = \sqrt{\frac{k}{m}}.$$

Note (and this is very important) that the received answer is a special case of the general rule. It is as follows. If the equation of oscillations is obtained, then the square of the oscillation frequency is equal to the ratio of the coefficient of the unknown function (in this case $x(t))$ to the coefficient of the second arbitrary function in time ($x''(t))$.

What about the amplitude $x_m$ and the initial phase $\varphi_0$? To determine these quantities, let's return again to the conditions: the body was shifted by $x_0$ to the right and pushed with a speed of $v_0$ to the left. Here

$$\text{Puc. 1.}$$

we are talking about exactly how the oscillations were excited, i.e., about the initial conditions. In different tasks they can be specified in different ways, but their meaning is always the same: for the initial moment of time, specific values ​​of some quantities are specified. In our case, the values ​​of mixing the body and its velocity (more precisely, the projection of the velocity onto the $X$ axis) are given:

at $t = 0$ $x = x_0$ and $v = -v_0$.

Since we already know the dependence of mixing on time:

$$x = x_m \sin(\omega t + \varphi_0),$$

it is not difficult to find the speed:

$$v = x' = x_m \omega \cos(\omega t + \varphi_0).$$

Let us put $t = 0$ in these expressions:

$$x_0 = x_m \sin \varphi_0,$$

$$-\frac{v_0}{\omega} = x_m \cos \varphi_0.$$

These are two equations with two unknowns: $x_m$ and $\varphi_0$. Dividing one equation by another, we get

$$tg \varphi_0 = -\frac{x_0 \omega}{v_0},$$

or

$$\varphi_0 = \arctg \left(-\frac{x_0}{v_0} \sqrt{\frac{k}{m}}\right).$$

By squaring both equations and adding them, we find

$$x_m^2 = x_0^2 + \frac{v_0^2}{\omega^2},$$

or

$$x_m = \sqrt{x_0^2 + \frac{mv_0^2}{k}}.$$

Problem 2. The body (see Problem 1), located in the equilibrium position, was given a right-directed speed $v_0$. Find: a) after what part of the period the potential energy of the system first becomes three times greater than the kinetic energy, b) after what time the speed of the body first turns into a field.

a) When the body oscillates externally, the system has a reserve of potential energy equations

$$W_p = \frac{kx^2}{2} = \frac{kx_m^2 \sin^2(\omega t + \varphi_0)}{2}$$

and kinetic energy

$$W_k = \frac{mv^2}{2} = \frac{mx_m^2 \omega^2 \cos^2(\omega t + \varphi_0)}{2}.$$

At the desired moment $t$

⟦folio 67⟧

In the equilibrium position, the depth of the body’s penetration into water $l_0$ is determined by the equality of the force of gravity $mg$ and the buoyant force $F = \rho_B Sl_0 g$ (here $\rho_B$ is the density of water):

$$mg = \rho_B Sl_0 g.$$

During oscillations, for example, at the moment when the depth of the body is equal to $l_0 + y$, Newton’s second law is written as:

$$mg - \rho_B S(l_0 + y)g = ma,$$

where $a = y''$. Subtracting the first from the second equation, we get

$$- \rho_B Sgy = my''.$$

or

$$y'' + \frac{\rho_B Sg}{m} y = 0.$$

This is the equation of oscillations already familiar to you. His solution looks like:

$$y = y_m \sin(\omega t + \varphi_0),$$

where $\omega = \sqrt{\frac{\rho_B Sg}{m}}$.

To determine the amplitude and initial phase, we turn to the initial conditions:

at $t = 0$ $y = 0$ and $v = v_0$.

Since $v = y' = y_m \omega \cos(\omega t + \varphi_0)$, we get

$$y_m \sin \varphi_0 = 0$$ and $y_m \omega \cos \varphi_0 = v_0$.

From here

$$\varphi_0 = 0$$ and $y_m = \frac{v_0}{\omega} = v_0 \sqrt{\frac{m}{\rho_B Sg}}$.

Problem 5. The cylindrical method with gas is closed by a piston with mass $m$ and cross-sectional area $S$ (Fig. 4). At equilibrium, the piston is at a height of $l$ from the bottom of the vessel. At some point, the piston is moved from the equilibrium position downward by amounts $h_0$ and released. Determine the frequency, initial phase and amplitude of the oscillations:

$$\omega = \sqrt{\frac{mg + p_a S}{ml}},$$

$\varphi_0 = \frac{\pi}{2},$ $y_m = h_0$.

Problem 6. Find the vibration frequency of the liquid poured into the U-shaped tube (Fig. 5). Liquid mass $m$, density $\rho$, cross-sectional area of ​​the tube $S$.

Here it is easiest to use energy considerations.
