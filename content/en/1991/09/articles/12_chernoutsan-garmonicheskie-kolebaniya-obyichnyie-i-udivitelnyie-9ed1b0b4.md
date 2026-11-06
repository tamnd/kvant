---
id: 1991-9-chernoutsan-garmonicheskie-kolebaniya-obyichnyie-i-udivitelnyie-9ed1b0b4
issue: kvant_1991_9
year: 1991
number: "9"
title: Harmonic vibrations - ordinary and surprising
authors:
  - Черноуцан А. И.
rubric: shkola-v-kvante
page_first: 38
page_last: 40
page_labels: 36-38
lang: en
source: kvant_digital
extraction: vision
content_sha256: 692e34554b0c6fb1a4b576d27a0106cb1232074d64ff12588034df7be2210b61
prompt_sha256: draft-1
translated_from: content/ru/1991/09/articles/12_chernoutsan-garmonicheskie-kolebaniya-obyichnyie-i-udivitelnyie-9ed1b0b4.md
source_content_sha256: 85aab76189d39707434b4c6e813125e5e538db6871baf4e55c08155e140dbbc7
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 36⟧

Harmonic vibrations - common and surprising

When and how is it best to study oscillations? All oscillatory processes - both mechanical and electrical - together, as it was in the school course before? Or should mechanical vibrations be discussed together with other mechanical phenomena, and electrical vibrations with electrical ones, as is done now?

Probably, each method has both its reasons and its disadvantages. The fact is that all types of vibrations are similar to each other, as close as they are in different clothes - they are all described by exactly the same mathematical equations. Only where in mechanics there is a change of point, in electrical there should be a charge of the capacitor, and where the speed of the point is the current strength in the circuit, etc. That’s why, from our point of view, it is very convenient to study electrical vibrations by analogy, comparing electrical concepts with mechanical ones.

So, when starting to study electrical vibrations, it is useful to remember about mechanical vibrations. Without pretending to be a complete repetition (it’s easier to pick up a textbook), we will discuss several issues that often arise in student agreements.

You probably noticed that we were talking exclusively about harmonic oscillations, i.e. oscillations that occur according to the law of cosine (or sine)

$$x = A \cos (\omega t + \varphi_0),$$

where $x$ is the change of point, $A$ is the amplitude, $\omega$ is the cyclic frequency, $\varphi_0$ is the initial phase of the oscillations. What's the matter? Maybe it’s because cosine is the simplest periodic function in appearance? No, the main reason is different. It turns out that there is no need to specially invent a mechanical system that would perform harmonic oscillations. Such oscillations are characteristic of almost all systems. (Why “almost” - more on that a little later.) You just need to establish any system in a state of stable equilibrium, and then you should “push”.

Question one: what is stable equilibrium and do all systems have an equilibrium? It is clear that once it decides about equilibrium, the resulting force in this state must necessarily be equal to zero. Stability means that when deviating from equilibrium, a restoring force will arise, that is, a force directed back towards equilibrium. But it’s even better to formulate the same thing in the language of energy. The fact is that energy is a concept for physics that is more and more important than force, and what is said in this language in one area is easily transferred to others. So, stable equilibrium corresponds to

⟦folio 37⟧

---
running_head:
folio:
---

corresponds to a minimum of potential energy. It is clear that any system that has potential energy has such a minimum. Otherwise, by reducing the potential energy to infinity, you can force the system to do as much work as you like, i.e., get a perpetual motion machine.

The simplest system that performs harmonious oscillation is an external weight, obeying Hooke's law $F_{\text{упр}} = -kx$. Having written Newton's second law for this load, we obtain the equation

$$x'' + \frac{k}{m} x = 0,$$

where $x''$ is the second arbitrary mixture in time, i.e. acceleration. And the solution to such an equation is precisely function (1), i.e., a harmonic oscillation with a frequency $\omega = \sqrt{k/m}$ or a period $T = 2\pi/\omega = 2\pi\sqrt{m/k}$. How can you be sure of this? Yes, just substitute this function into equation (2). And here schoolchildren (especially instructive ones) often have the following question.

Question two: how do we know that equation (2) does not have some other solution? In other words, is it possible not to guess the solution, but to get it directly from the equation? Of course, this can be done, but only if you already know how to interpret and solve simple equations with arbitrary ones (they are called differential equations). However, in this case there is no need for this. It is enough to use the following statement: if the forces acting on the point and its position and speed at the initial moment (initial conditions) are known, then the movement of the point is completely determined. In other words, there is only one solution to the equation that satisfies the initial conditions. And now - a little more detail.

Let us set the initial coordinate $x_0$ and the initial velocity $v_0$ and show that there is a solution (1) to equation (2) that satisfies these conditions. In other words, let’s find the parameters $A$ and $\varphi_0$ that provide this. Substituting $t=0$ into equality (1) and into the expression for speed $v=x' = -\omega A \sin(\omega t + \varphi_0)$, we obtain the system of equations

$$x_0 = A \cos \varphi_0,$$

$$v_0 = -\omega A \sin \varphi_0.$$

Solving it, we find

$$tg \varphi_0 = -v_0 / (\omega x_0), \quad A^2 = x_0^2 + v_0^2 / \omega^2.$$

Function (1) with such $A$ and $\varphi_0$ and $\omega = \sqrt{k/m}$ satisfies both equation (2) and the initial conditions. This means that it describes the only solution.

Well, okay, we sorted out the external weight. But not all systems are described by force $F = -kx$ and potential energy $E_p = kx^2 / 2$. And it was said that any system (almost!) will perform a harmonious oscillation. No, not really. We said that the body needs to be slightly “push.” Not any, but small fluctuations around the equilibrium position should be harmonious. This is easy to understand by looking at a graph of an arbitrary dependence of forces on mixing (Fig. 1). At $x=0$ $F=0$, and a sufficiently small section of the curve around this point can be approximately considered rectilinear (the smaller the section, the less we will make a mistake). This means that in a small neighborhood of the point $x=0$ the force can be written in the form $F = -k\varphi_0 x$, and the corresponding potential energy in the form $E_p = k\varphi_0 x^2 / 2$, where the “effective stiffness” $k\varphi_0$ is

⟦folio 38⟧

---
running_head:
folio:
---

nothing more than the tangent of the angle $\alpha$ of the inclination of the graph to the axis $X$ at $x=0$. For any dependence $F=F(x)$, small oscillations of the point are indistinguishable from external oscillations with rigidity $k_{\alpha\phi}$, i.e., they occur according to the harmonic law with a period $T=2\pi\sqrt{m/k_{\alpha\phi}}$. (Check for yourself, for example, that for the mathematical matrix $k_{\alpha\phi}=mg/l$.)
An attentive and “attentive” student immediately formulates another question.

Question three: what if potential energy has a different form, for example $E_p=\gamma x^4/4$? In this case, the force is $F=-\gamma x^3*$, and at point $x=0$ the angle $\alpha$ of the graph $F=F(x)$ is zero (Fig. 2). What will be the fluctuations of such a system? Harmonious or not? It turns out that in this case, fluctuations, even small ones, will occur according to a completely different law. (With precisely such cases in mind, we said: “almost always” harmonic.)

What systems satisfy the given dependence of potential energy on mixing? Let's give two examples. First, you can carefully hollow out a hole, the cross-section of which has the form $y=\beta x^4/4$. then the potential energy for motion in such a hole is $E_p=mgy=(mg\beta)x^4/4$. Another example: if you attach to the middle of an undeformed spring with fixed ends

*) By definition, work is equal to the change in potential energy, taken with the opposite sign. For small $\Delta x$ we have

$$F\Delta x=-\Delta E_p, \text{ т. е. } F=-\Delta E_p/\Delta x=E'_p(x).$$

weight (Fig. 3), then for small transverse vibrations the force will be proportional to the third, and the energy - to the fourth degree of mixing. Note that if the spring is stretched, then the oscillation will be harmonic!

What will we see in these cases? Is it possible to distinguish harmonic oscillations from non-harmonic ones by eye? It turns out that there is a very important difference between harmonic oscillations and any others: their frequency depends on the parameters of the system, but does not depend on the amplitude of the oscillations. We are so accustomed to this that we are not at all surprised when we are asked to find out the period of small oscillations, without saying anything about their amplitude. But this is not a very special property at all, and it holds only for the force $F=-kx$. Let us explain this using dimension messages. The dimension of rigidity $k$ does not contain the length: $[k]=\mathrm{H/m}=\mathrm{kr/c^2}$, therefore the period of oscillations, which can only depend on $k$, $\omega$ and $A$, must be expressed through the combination $\sqrt{m/k}$, which has the dimension of time, and cannot depend on the amplitude $A$. The case is completely different when $F=-\gamma x^3$. The dimension $\gamma$ contains the length: $[\gamma]=\mathrm{kr/(m^2\cdot c^2)}$, and to obtain the time dimension for the oscillation period, it is necessary to make the combination $(m/\gamma A^2)^{1/2}=(1/A)\sqrt{m/\gamma}$. This is exactly what the answer for the oscillation period should look like (up to a dimensionless factor) - the greater the amplitude, the shorter the period. If, for example, a weight on an undeformed spring is deflected to the side once by 1 cm, and another time by 2 mm, then in the second case the period will be 5 times longer, which, of course, is easy to notice with the naked eye.

A. Chernochan
