---
id: 1984-10-danilin-peredacha-elektroenergii-na-rasstoyanie-a996e035
issue: kvant_1984_10
year: 1984
number: "10"
title: Transmission of electricity over a distance
authors:
  - Данилин В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 57
page_labels: 53-55
tag: LNR9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 868a965e8c72e5380f3fbd223ca234d298cd69273b4081c9115a0272cdf2944f
prompt_sha256: draft-1
translated_from: content/ru/1984/10/articles/20_danilin-peredacha-elektroenergii-na-rasstoyanie-a996e035.md
source_content_sha256: 38949b1f7ae99ab7748c9fa094d03cf7a1d6e76dc69d2c420d66f4ff5f32d47a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

Transmitting electricity over a distance

Candidate of Physical and Mathematical Sciences
V. A. DANILIN

Currently, the transfer of electrical energy from the generator to the consumer occurs mainly through wires using alternating current. In this case, energy losses necessarily occur, primarily due to heating of the wires. Losses can be reduced by reducing the current in the power line, that is, by increasing the voltage at the output from the generator (so that the transmitted power remains unchanged).

For direct use of electrical energy by the consumer, the voltage at the end of the line, that is, at the input to the consumer, must be lowered.

In the case of alternating current, the voltage is increased and decreased using transformers.

How does an alternator work? What is the operating principle of a transformer? What determines the losses in a power line? These and similar questions may arise from applicants in connection with the repetition of the topic “Production, transmission and use of electrical energy”. We will discuss some of them using the example of several specific tasks. Almost all of them were at one time offered for advanced examinations at the Moscow Institute of Physics and Technology.

Problem 1. A transformer that increases the voltage from $U_1=100$ V to $U_2=3300$ V has a closed core in the form of a ring (Fig. 1). A wire is passed through the barbed wire, the ends of which are connected to a voltmeter. The voltmeter shows a voltage of $U=0,5$ V. How many turns are there in each winding of the transformer?

In a closed ring core, where practically the entire magnetic field is concentrated, the magnetic flux is the same in all its sections. In any turn placed on the core, no matter which winding it belongs to, the instantaneous value of the induced emf is the same, since, according to the law of electromagnetic induction, it is determined by the rate of change of the magnetic flux in the core: $e=-\frac{\Delta\Phi}{\Delta t}$.

If the transformer windings contain $n_1$ and $n_2$ turns, then the induced emf in these windings is equal to the corresponding $e_1=n_1e$ and $e_2=n_2e$.

Obviously the active resistance of the transformer windings is small and can be ignored. The same can be said about the wire to which the voltmeter is connected. Then at any moment of time the equality $u=-e, u_1=-e_1, u_2=-e_2$ is valid.

Here $u$ is the instantaneous voltage value at the ends of the wire, $u_1$ is the voltage on the primary winding and $u_2$ is on the open secondary winding of the transformer.

Since all EMF occurs in the same phases, their ratio can be replaced by the ratio of the corresponding effective values, and therefore, taking into account the previous equalities, by the ratio of the effective voltage values:

$$\frac{e_1}{e} = \frac{\varepsilon_1}{\varepsilon} = \frac{U_1}{U}, \frac{e_2}{e} = \frac{\varepsilon_2}{\varepsilon} = \frac{U_2}{U}.$$

From here we find the number of turns in each winding:

$$n_1 = \frac{e_1}{e} = \frac{U_1}{U} = 200,$$

$$n_2 = \frac{e_2}{e} = \frac{U_2}{U} = 6600.$$

⟦folio 54⟧

Task 2. Electricity from the generator is transmitted to the consumer via wires. Wire resistance $r$, load resistance $R$, generator voltage $U$. Determine the efficiency of the transmission line, that is, the ratio of the power supplied to the load to the total power supplied by the generator. At what load resistance is the maximum useful power?

According to Ohm's law for a complete circuit, the current in the line

$$I = \frac{U}{r + R}.$$

Generator power

$$P = UI = \frac{U^2}{r + R},$$

power allocated to the load,

$$P_H = I^2 R = \frac{U^2 R}{(r + R)^2}.$$

Efficiency coefficient

$$\eta = \frac{P_H}{P} = \frac{U^2 R(r + R)}{(r + R)^2 U^2} = \frac{R}{r + R}.$$

When $R$ decreases to zero and when $R$ increases indefinitely, the value $P_H$ drops to zero. This means that at some intermediate value $R = R_M$ the useful power should reach its maximum value.

Let us examine the function $P_H(R)$ to its maximum. To do this, we find and equate to zero the derivative of $P_H(R)$ with respect to $R$:

$$P'_H(R) = U^2 \frac{(r - R)}{(r + R)^3} = 0.$$

From this we obtain that the power allocated to the load is maximum if $R = r$. At the same time $P_{H\max} = U^2/(4r)$. The line efficiency in this case is $\eta = 1/2$ - half of the generator power is wasted uselessly.

Task 3. The power line can operate at two different generator voltages $U_1$ and $U_2$ and corresponding load resistances $R_1$ and $R_2$. The power demand ratio on the supply wires for these junctions is $\alpha$. Determine the ratio $U_2/U_1$, provided that the power of the generator in both mergers is the same.

Let the resistance of the supply wires be equal to $r$ - this value does not change. The total power delivered by the generator is

$$P = UI = \frac{U^2}{r + R},$$

where $I$ is the current in the circuit. Heat loss power

$$P_n = I^2 r = \frac{U^2}{(R + r)^2} r.$$

The ratio of power consumption for different values ​​of $U$ and $R$ is equal to

$$\frac{U_1^2}{(R_1 + r)^2} r : \frac{U_2^2}{(R_2 + r)^2} r = \alpha.$$

According to the conditions of the problem, in both mergers the generator produces the same power:

$$\frac{U_1^2}{R_1 + r} = \frac{U_2^2}{R_2 + r}.$$

From the last two correspondences it follows

$$\frac{U_1^2(R_2 + r)^2}{U_2^2(R_1 + r)^2} = \alpha, \frac{U_1^2}{U_2^2} = \frac{R_1 + r}{R_2 + r}.$$

Where

$$\frac{U_2}{U_1} = \sqrt{\alpha}.$$

Using this problem as an example, one can see how great the influence of the voltage under which energy is transferred is on the magnitude of heat losses in the power transmission line. It is enough to increase the voltage by $\alpha$ times, and the losses will decrease by $\alpha^2$ times.

* * *

It is important to be able to evaluate the currents and voltages that arise in power lines during transient processes. Such as, for example, shutdowns or rapid load changes. If we take into account that the voltage under which modern lines operate is of the order of $10^6$ V, then it is possible that the voltage may increase, the so-called overvoltage, which can lead to an electrical breakdown in the line. However, from the diagrams, or constructing the transition of processes, is presented in the following problem.

Task 4. The transformer winding, which has an inductance $L = 0,1$ Gi, and a capacitor with a capacity of $C = 0,1$ μF connected in parallel to it through switches $K$ are connected to a source with an emf $\delta$ and internal resistance.

⟦folio 55⟧

$r=100$ Ohm (Fig. 2). After establishing a stationary mode, the keys are opened. Find the amplitude of the voltage appearing at the ends of the winding in relation to the emf of the source.

In steady state, a constant current flows through the transformer winding

$$I = \frac{\varepsilon}{r},$$

the voltage on the winding, and therefore on the capacitor, is zero.

When the key $K$ is opened, a change in the magnetic flux occurs, which creates a voltage at the ends of the winding. Its amplitude can be found by considering the oscillations in a circuit composed of an inductor $L$ and a capacitor embone $C$. The energy stored in the coil during the flow of direct current will, after a quarter of the oscillation period, be converted into the energy of a charged capacitor:

$$\frac{LI^2}{2} = \frac{CU_m^2}{2}.$$

Hence the voltage amplitude on the capacitor, and consequently at the ends of the transformer winding, is equal to

$$U_m = \sqrt{\frac{L}{Cr}} \varepsilon = 100 \varepsilon.$$

As you can see, the weight overload is large. In practice, it always occurs when the current flowing through the coils is switched off at low values ​​of the capacitance of the capacitor connected to it.

Exercises

1. The secondary winding of the transformer, having $n=100$ turns, is produced by a magnetic flux that changes with time according to the law $\Phi=0,01$ cos $314t$ (in SI units). Write a formula expressing the dependence of the indication EMF in the secondary winding on time, and find the effective value of this EMF.

2. When transmitting electricity over a long distance, a step-up transformer is used, loaded to a rated power of $P=1000$ kW. At the same time, the difference in the readings of electricity meters installed at the output of the transformer substitution and at the receiving point increases annually by $\Delta W_n=215$ kWh. How many times must the output voltage be increased so that when transmitting electricity, losses do not exceed 0.1%?

3. Determine the mass of copper needed to install a two-wire line $l=5$ km long. The voltage on the station buses is $U=2400$ V, the power transmitted by the consumer is $P=60$ kW, the permissible consumption in the wiring is $U_n=0,08U$. Copper density $D=8,9 \cdot 10^3$ kg/m$^3$, resistivity $\varphi=0,017 \cdot 10^{-6}$ Ohm m.

Selected School Problems

(For the beginning, see p. 33)

connecting the silvers of the bases is equal to the length of the segment connecting the silvers of its diagonals.

8 (8-10). In triangle $ABC$, the angle at vertex $C$ is equal to $120^\circ$. Prove that segments of length $a+b,b,c$ can be used to form a triangle. Here are $a=|BC|$, $b=|AC|$, $c=|AB|$.

9 (10). When the numbers are successive terms of some geometric progression. If you add 2 to the second number, they will form an arithmetic progression. If you then add 2 to the third number, they will form an arithmetic progression. If you then add 16 to the third number, they will again form a geometric progression. Find these numbers.

10 (8-10). The perimeter of some 1982-pleaser is less than 2000. Prove that among the triangles with vertices at neighboring vertices this 1982-pleaser will find a triangle whose area is less than 1.

Tenth grade

11 (10). Solve the equation $\sin^4 x+\cos^4 x=0,5$.

12 (10). On the coordinate plane, I will draw the points of the parabolas close to the point $M(0; a)$.

13 (10). Find a polynomial (not necessarily of degree two) with integer coefficients for which the number $\sqrt{3}+\sqrt{7}$ is a root.

14 (9-10). Prove that for any real $x$ the inequality $\cos(\sin x)>\sin(\cos x)$ holds.

15 (8-10). In triangle $ABC$, extrastrias $BP$ and $CT$ intersect at point $O$. It is known that points $A, P, O$ and $T$ lie on the same circle. Find the angle $A$.

The publication was prepared by E. I. Khukhro
