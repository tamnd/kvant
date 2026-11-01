---
id: 1985-10-zilberman-povtorim-kolebaniya-7dd2bf21
issue: kvant_1985_10
year: 1985
number: "10"
title: Let's repeat the vibrations
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: KVTB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2cb5d2349ab569c95cce90d35bebd513e2a573f69899196131317abe6c230b62
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/20_zilberman-povtorim-kolebaniya-7dd2bf21.md
source_content_sha256: c1b79c24ae83a6678c9e53d696e70ac94fcd01570e9289d6ad365bc723105f44
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Let's repeat the vibrations

A. R. ZILBERMAN

Oscillations occur in a system removed from a state of stable equilibrium. In many practical important cases, if the force returning to the equilibrium position is linearly dependent on the mixing, a harmonic oscillation is obtained. Usually these are “small” fluctuations, when the balance is slightly disturbed.

The simplest example is the oscillations of a mathematical matrix at small angles of deviation from the vertical. Another example is the oscillation of a load under the action of the elastic force of a spring in the absence of other forces. It is interesting because the vibrations turn out to be harmonic, even if they are not small - as long as the spring obeys the condition (Hooke's law) $F=-kx$, where $x$ is the elongation of the spring (displacement of the load from the equilibrium position), $k$ is the stiffness of the spring, $F$ is the elastic force of the spring.

Let's look at this example in more detail. Let the mass be attached to a horizontal spring, the second end of which is fixed, and placed on a smooth horizontal surface. The equation of Newton's second law for a load has the form

$$mx''=-kx,$$

or

$$x''+\frac{k}{m}x=0$$

(1)

(here $m$ is the mass of the load, $x''$ is its acceleration, more precisely, the projection of acceleration on the horizontal axis $X$). The solution to such an equation is the function

$$x=x_m \cos(\sqrt{\frac{k}{m}}t+\varphi_0)=$$

$$=x_m \cos(\omega_0 t+\varphi_0),$$

(2)

where $x_m$ is the amplitude, $\omega_0=\sqrt{k/m}$ is the natural frequency, $\varphi_0$ is the initial phase of oscillations. The frequency is determined by the parameters of the oscillating system $(k$ and $m)$, and the amplitude and initial phase depend on how exactly the system was brought out of equilibrium, that is, the initial moments of time $t_0=0$ are determined:

$$x_0=x(t_0)=x_m \cos(\sqrt{\frac{k}{m}}t+\varphi_0)=$$

$$=x_m \cos \varphi_0,$$

$$v_0=v(t_0)=x'(t_0)=$$

$$=-x_m \sqrt{\frac{k}{m}} \sin(\sqrt{\frac{k}{m}}t_0+\varphi_0)=$$

$$=-x_m \sqrt{\frac{k}{m}} \sin \varphi_0.$$

Dividing the second equation by the first, we find $\varphi_0$:

$$tg \varphi_0=-\sqrt{\frac{m}{k}} \frac{v_0}{x_0}, \varphi_0=\arctg\left(-\sqrt{\frac{m}{k}} \frac{v_0}{x_0}\right).$$

The easiest way to find the value $x_m$ is by excluding trionometric functions using the usual method of squaring and adding the equation:

$$x_0^2+\frac{m}{k}v_0^2=x_m^2, \quad x_m=\sqrt{x_0^2+\frac{m}{k}v_0^2}.$$

You can set coordinates $x(t_1)$ and $x(t_2)$ as “convenient” time moments $t_1$ and $t_2$, or speeds $v(t_1)$ and $v(t_2)$, or coordinate $x(t_1)$ and speed $v(t_2)$, etc. It is only important that time moments $t_1$ and $t_2$ were not separated by an integer number of half-periods.

Thus, knowing the equation of motion of the system (equation (2)) and two additional data, we will completely describe the motion. The same can be said, for example, about pro-gravity-accelerated motion - acceleration by determining forces, and together with the initial coordinates and speed, this allows us to know absolutely everything about such motion.

Equations similar to equation (1) are obtained in many vibration problems—you just need to choose the right variable. Let's illustrate this with several conditions of the problem about an outdoor load.

⟦folio 49⟧

Task 1. The load - a scale cup with mass $M$ - increases the external rigidities $k$, and vibrations occur when a weight with mass $m$ is put into the cup (it travels the path $h$ before the impact and adheres to the cup). Describe the movement of the cup.

Let us direct the coordinate axis $X$ and choose the origin of coordinates 0 as shown in figure 1. Considering that at the beginning the cup was in equilibrium, we write

$$Mg - k(l - l_0) = 0$$

($l$ is the length of the spring with a suspended cup, $l_0$ is without it). When deviating by $x$ from the initial position, when the weight is already stuck to the cup, the equation of motion of the system will be:

$$(M + m)g - k(l - l_0 + x) = (M + m)x''.$$

Opening the brackets and taking into account the first equation, we get

$$x'' + \frac{k}{M + m}x = \frac{mg}{M + m}.$$

This equation is very similar to equation (1), only the right part interferes - it is not equal to zero. It is clear why this happened: we took the origin of coordinates in the wrong place, because the equilibrium position of the heavier cup moved downward by a distance $\Delta x = mg/k$. If we introduce a new variable

$$x_1 = x - \Delta x = x - \frac{mg}{k},$$

then the equation for $x_1$ will be almost the same as (1):

$$x_1'' + \frac{k}{M + m}x_1 = 0$$

(recall that with such a change of variable, arbitrary ones from $x_1$ are the same as from $x$).

We will not solve the problem here

Fig. 1.

Fig. 2.

to the end, we have done the main thing - we have obtained the equation of oscillations. From it we immediately find the oscillation frequency:

$$\omega_0 = \sqrt{\frac{k}{M + m}}.$$

To fully describe the motion of the system, you must first solve the problem of an inelastic impact of a load on a cup, and then find the amplitude and initial phase of the oscillations. Do this yourself (the answer is given at the end of the issue on p. 59).

The frequency of harmonic oscillations of the system can also be found from energy messages. Let's show this using the example of an ideal oscillatory circuit (without losses).

Let us denote the maximum loader (amplitude of load oscillations) by $q_m$, and the maximum current through the coil (amplitude of current oscillations) by $I_m$. The current is the first arbitrary load of the plates in time, therefore for harmonic oscillations the relation is valid

$$I_m = q_m\omega_0.$$

At the moment when the load is maximum ($q = q_m$), the current is zero, and at $i = I_m$ the load vanishes to zero. Let us find the energies of the circuit at the indicated times and equate them:

$$\frac{q_m^2}{2C} = \frac{LI_m^2}{2},$$

or $$\frac{q_m^2}{2C} = \frac{Lq_m^2\omega_0^2}{2},$$

where $C$ is the capacitance of the continuator, $L$ is the inductance of the coil. From here

$$\omega_0 = \frac{1}{\sqrt{LC}}.$$

For an example of the application of the energy solution method, there are two problems.

Task 2. Find the period of vertical oscillations of a load with mass $m$ in the system shown in figure 2. Consider the mass of the block $M$ concentrated in its axis. The spring has a stiffness of $k$, the thread is inextensible.

Let us equate the energies of the system in the equilibrium position and in the extreme position, when the speed of the load becomes zero. But first, a little static. Denoting the length of the unstretched spring by $l_0$, and its length in the equilibrium position by $l$, we write

$$k(l - l_0) = Mg + 2mg$$

(down on the block the action of sweating the threads is equal to the weight of the load).

⟦folio 50⟧

Let the maximum displacement of the block axis down from the equilibrium position be $x_m$, then the total energy of the system in the extreme position

$$W_1 = \frac{k(l-l_0+x_m)^2}{2} - Mgx_m - mg(2x_m).$$

Denoting the speed of the block axis when passing through the equilibrium position through $v_m$, we find an expression for the total energy of the system at this moment:

$$W_2 = \frac{k(l-l_0)^2}{2} + \frac{1}{2} Mv_m^2 + \frac{1}{2} m(2v_m)^2.$$

For harmonic vibrations in this case $v_m = x_m\omega_0$. Therefore, equating the energies $W_1$ and $W_2$, after simple transformations we obtain

$$\frac{kx_m^2}{2} = \frac{Mx_m^2\omega_0^2}{2} + 2mx_m^2\omega_0^2,$$

where

$$\omega_0 = \sqrt{\frac{k}{M+4m}}.$$

This problem can be solved with a different distribution of masses in the block; to do this, you only need to add the energy of its rotation to the energy of the translational motion of the block. If, for example, the mass $M$ is not concentrated in the axis, but is distributed along a circle of radius $r$ centered on the axis, then the total kinetic energy

$$W_k = \frac{Mv^2}{2} + \frac{M(vr/R)^2}{2},$$

where $R$ is the radius of the block.

Task 3. The system of self-inductive sorting is used. The inductor $L$ is connected to the battery with voltage $U_0$ (Fig. 3), and when the current reaches the value $I_0$, the circuit is opened. In parallel, the coil connects a spark gap $P$ (“short-circuit spark plug”), into which a spark leaks when voltage $U(U \gg U_0)$ is reached. What important parameter did we not set? At what relationships between all parameters will the system work?

An important parameter here is the capacitance $C$ (capacitor capacitor $C$ in the diagram is connected in parallel to the arrester). It consists of the spark gap capacitance, the capacitance between the supply wires and the capacitance between the turns of the coil.

Let's do the calculation. If there were no spark gap, oscillations would arise in the circuit consisting of a coil and a capacitor, in which the maximum voltage on the capacitor is obtained when the coil is also equal to zero. This voltage can be found from the law of conservation of energy:

$$\frac{LI_0^2}{2} = \frac{CU_m^2}{2}, \quad U_m = I_0 \sqrt{\frac{L}{C}}.$$

The digit will skip under the condition $U \leq U_m$, that is

$$U \leq I_0 \sqrt{\frac{L}{C}}, \quad I_0 \geq U \sqrt{\frac{C}{L}}.$$

There is one subtlety to this task. No matter how the switch is designed, it cannot operate instantly. During the opening process, the active resistance of the circuit changes from zero (at the beginning) to a very large value (when the circuit is open), and heat is generated in the circuit. Here again the important resistance $T = 2\pi/\omega_0 = 2\pi \sqrt{L/C}$, then the amount of heat released in comparison with the energy stored in the coil can be claimed.

Sometimes an “oscillatory” equation will arise in problems that are clearly not oscillatory. Let's look at an example.

Task 4. A thin single-pod block of length $l$ slides first along an Eladian horizontal table, and then falls on a rough area with a friction coefficient $u$. The block stops, having decayed halfway there. Find the initial speed of the block and the braking time.

Let there be a part of a block of length $x < l/2$ on a rough surface. Assuming that the normal reaction forces are distributed uniformly along the block, we find the friction force:

$$F_{\text{тр}} = -\mu mg \frac{x}{l}$$

and acceleration of the block:

$$a = x'' = \frac{F_{\text{тр}}}{m} = -\mu g \frac{x}{l}.$$

We got a familiar equation

$$x'' + \frac{\mu g}{l} x = 0.$$

⟦folio 51⟧

Braking begins at the moment when $x=0$, and ends at speed $v=0$, which corresponds to exactly a quarter of the period of “oscillations”; therefore the braking time

$$\tau = \frac{1}{4} T = \frac{1}{4} \frac{2\pi}{\omega_0} = \frac{\pi}{2} \sqrt{\frac{l}{\mu g}}.$$

Of course, there will be no real oscillations - the block will not be pushed back after stopping (in the absence of slipping, the force of tremiya will drop to zero).

It is now easy to write down an expression for the coordinate $x$:

$$x = \frac{l}{2} \sin \sqrt{\frac{\mu g}{l}} t \quad (\text{при } 0 \leq t \leq \tau)$$

and for speed $v$:

$$v = x' = \frac{l}{2} \sqrt{\frac{\mu g}{l}} \cos \sqrt{\frac{\mu g}{l}} t$$

(at $0 \leq t \leq \tau$).

From here we find the initial speed

$$v = v (t=0) = \frac{1}{2} \sqrt{\mu g l}.$$

This task can be used by increasing the speed so that the entire block is cut onto the rough part of the table - then after the “harmonic” braking, normal braking will occur. The trick is that now the “harmonic” part will no longer occupy a quarter of the period, but less. Calculate the braking time at $v_0 = 2\sqrt{\mu g l}$ yourself (the answer is given on p. 59).

Now let's discuss the problem of weakly damped oscillations in a circuit.

Problem 5. An inductance coil $L=1$ Gi, having an active resistance $R=1$ Ohm, and a capacitor with a capacity $C=1$ µF forms an oscillatory circuit. At some moments, the direction to the capacitor is $U_1=0,1$ V, and the current is maximum. What is this current? Find the approximation of energy loss in the circuit over one period. After what period of time does the charge on the capacitor become zero?

Hint: due to the unevenness of the motor shaft, shocks occur - once per revolution of the shaft. Resonance is described here.

3. At some points in the circuit shown at figure 4, the key $K$ is closed. Draw graphs of $U_c(t), I_{L1}(t)$ and $I_{L2}(t)$. Diodes are considered ideal.
