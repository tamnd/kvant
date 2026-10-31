---
id: 1974-5-zaytsev-elektricheskie-mashinyi-postoyannogo-toka-baf0d7bc
issue: kvant_1974_5
year: 1974
number: "5"
title: DC Electrical Machines
authors:
  - Зайцев И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 66
page_last: 70
page_labels: 64-68
tag: MZLE
lang: en
source: kvant_digital
extraction: vision
content_sha256: b1dc8a210112d7683222a745edfaf1c3411e78cee2739e4f48ccf61fba21f8a4
prompt_sha256: draft-1
translated_from: content/ru/1974/05/articles/14_zaytsev-elektricheskie-mashinyi-postoyannogo-toka-baf0d7bc.md
source_content_sha256: 0038d8c4a7547aac9041880b0cfecb52f5d36ad34eaf19fc08dba8fa20b520ad
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 64⟧

DC Electrical Machines

In this article we will not discuss in detail the structure of various electrical machines. We will look at the operation of an electric motor and a diamo machine (a diamo machine is the old name for an induction generator of electric current), using two basic laws - Ohm's law and the law of conservation of energy.

The flock consists mainly of questions and answers. When working on articles, before reading the answer, try to answer the question yourself. Further, you will not be able to do this; thinking about the question will bring an undoubted role, thanks to which it is better to remember the correct answer.

Electric motors

All electric motors (or, in other words, electric motors) necessarily have the same basic parts. This is, first of all, an inductor and an anchor. The inductor is a source of magnetic field. When an electric current is passed through the armature winding, the armature, located in a magnetic field, begins to rotate. Thus skips the conversion of electrical energy into mechanical energy. If, for example, a motor shaft is connected to a machine tool, the machine can be set in motion.

Question. Let's consider a direct current motor with independent excitation (in it the inductor is either a permanent magnet or an electromagnet, and has components independent of the armature object). How is Ohm's law written for the armature circuit of a motor connected to a direct current source?

Answer. In the electric circuit of the armature there are two electromotive forces - the direction of the current source $U$ and e. d.s. induction $E_\pi$, which arises in the armature winding when it rotates in the magnetic field of the inductor. Moreover, e. d.s. induction, according to Lenz's rule, is opposite in sign to the direction of the current source. Therefore, Ohm's law will be written like this:

$$U - E_\pi = IR,$$

where $I$ is the current in the circuit, and $R$ is the total resistance of the armature winding and lead wires.

Question. How is the law of conservation of energy written for this circuit?

Answer. The energy $W_\pi = UIt$ consumed from the source is spent on Joule heat, which is released at the resistance $R$, and on performing useful work $A$. Therefore, according to the law of conservation of energy

$$UIt = I^2Rt + A,$$

or for capacities

$$UI = I^2R + P.$$

From equalities (I) and (II) many important consequences can be obtained.

Question. What is the useful power $P$?

⟦folio 65⟧

Answer. Multiplying both sides of equality (I) by the current I, we obtain
$$UI - E_n I = I^2 R,$$
or
$$UI = I^2 R + E_n I.$$
Comparing the resulting equality with equality (II), one can immediately notice that
$$P = E_n I,$$
that is, the useful power of the motor is equal to the product of the emf. induction per current.
Question. Having received any result, it is always useful to analyze the possibility of special cases. We can assume that the useful power of the motor is equal to $E_n I$. Let's see under what conditions the motor will not perform mechanical work, that is, $P = 0$. What happens in the armature circuit?
Answer. The product $E_n I$ can be zero if $E_n = 0$ or $I = 0$.
Whatever uh. d.s. induction was equal to zero, the magnetic flux passing through the turns of the armature winding should not change. This is possible if the armature motor is locked, that is, it does not rotate. In this case, current flows through the winding of the clamped armature
$$I = \frac{U}{R}.$$
Motor does not do any work in one more case, when $I = 0$. This is possible not only when the motor is not connected to a power source. It follows from Ohm’s law that $I = 0$ also in the case when
$$E_n = U,$$
that is, the motor rotates at such a speed that e.g. d.s. induction is equal in absolute value to the direction of the current source. In this case, the motor does not consume electricity from the source: since $I = 0$, then the power consumption is $P_\pi = UI = 0$. The armature motor rotates by inertia*).

*) This also follows from the fact that at $I = 0$ the forces acting in the magnetic field of the inductor on the armature winding are also equal to zero.

Fig. 1.

Question. Let's return to formula (II). It follows from this that the useful power of the motor is equal to
$$P = UI - I^2 R.$$
How does a graph of P versus moka I follow?
Answer. This is a parabola intersecting the I axis at points $I = 0$ and $I = \frac{U}{R}$ (Fig.1). From the messages of symmetrina it is very indo that the useful power of the motor is maximum at $I = U/2R$ and is equal to
$$P_{\max} = \frac{U^2}{4R}.$$
Question. What is the efficiency of a motor with independent excitation, provided that the developed power is maximum?
Answer. As we have seen, the mechanical (useful) power of the motor is maximum at $I = \frac{U}{2R}$ and is equal to
$$P_{\max} = \frac{U^2}{4R}$$. The power consumed by the motor from the source is equal to
$$P_\pi = UI = \frac{U^2}{2R}.$$
Consequently, the efficiency in the case under consideration
$$\eta = \frac{P_{\max}}{P_\pi} = \frac{U^2 2R}{4R U^2} = \frac{1}{2}.$$
Question. It is interesting to note that for the same value of useful power, the maximum power corresponds to

⟦folio 66⟧

Fig. 2.

Let's put two meanings together. Thus, the power is equal to $P_0$ at currents $I_1$ and $I_2$ (Fig. 1).
Let's see what this is connected with.
Answer. The useful power depends on the emf. induction arising in the armature, and from the current flowing through its winding:
$$P = E_n I.$$
At constant $U$ and $R$ the current value depends on the emf. induction:
$$I = \frac{U - E_n}{R}.$$
From the law of electromagnetic induction it follows that emf. The induction generated in the armature winding is proportional to the rate of change of magnetic flux $\frac{\Delta \Phi}{\Delta t}$ through this winding:
$$E_n \sim \frac{\Delta \Phi}{\Delta t}.$$
In turn, the rate of change of the magnetic flux is proportional to the angular speed of rotation of the armature $\omega$. Thus
$$E_n \sim \omega,$$
or
$$E_n = k \omega,$$
where $k$ is the coefficient of proportionality.
A plot of $E_n$ versus $\omega$ is shown in figure 2.
Now let's see how the current in the armature circuit and the forward power of movement depend on $\omega$. From Ohm's law
$$I = \frac{U - E_n}{R} = \frac{U - k \omega}{R},$$

Fig. 3.
and from the law of conservation of energy
$$P = UI - I^2 R = E_n I = \frac{kU \omega - (k \omega)^2}{R}.$$
Graphs of the dependence of $I$ and $P$ on $\omega$ are shown in Figures 3 and 4.
So, each value of the angular velocity $\omega$ corresponds to certain values ​​of the emf. induction $E_n$ and current $I$. Moreover, as $\omega$ increases, the value $E_n$ increases, and the value $I$ decreases. In this case, the utility developed by the motor turns out to be the same at two different values ​​of the armature rotation speed.
Question. In turn, the effective speed of rotation of the anchor depends on the external movement. How?
Answer. The electric forces acting on the armature in the magnetic field of the inductor are proportional to the current inducted through the winding. Proportional currents and moments of these forces, that is
$$M_0 = k_1 I,$$
where the proportionality coefficient $k_1$ depends on the design of the movement. Because
$$I = \frac{U - k \omega}{R},$$
That
$$M_0 = k_1 \frac{U - k \omega}{R}.$$
That is, the total moment of electrical forces acting on the armature depends linearly on the angular speed of rotation of the armature. At low angular speed of rotation of the armature, the moment of force

⟦folio 67⟧

large, with increasing angular velocity it decreases and becomes equal to zero at

$$\omega = \frac{U}{k}.$$

On the other hand, a moment of mechanical forces, the so-called load moment $M$, acts on the motor shaft. For example, if the engine uniformly lifts a load on a rope, then the load moment is equal to the product of the tension force of the rope, which is equal to the weight of the load, and the radius of the shaft. In steady state, the motor armature rotates at a speed $\omega$ at which the moment of the electrical forces acting on the armature is equal to the load moment. Indeed, let, for example, the speed of rotation of the armature be less than $\omega$. In this case, the moment of electrical forces is greater than the load moment, so the angular speed of rotation of the armature will increase. If the angular speed of rotation of the armature is greater than $\omega$, then the moment of electrical forces is less than the load moment. This will result in a decrease in the armature rotation speed to $\omega$.

Thus, such an angular speed of rotation of the armature is established at which

$$M_3 = M,$$

that is

$$k_1 \frac{U - k \omega}{R} = M.$$

where

$$\omega = \frac{k_1 U - MR}{k_1 k}.$$

That is, the angular speed of rotation of the armature depends linearly on the load torque.

So, the load determines the current in the armature winding and the angular speed of its rotation.

Let's consider this problem.

Exercise. The electric converter is connected to a constant voltage source. At the number of revolutions $n_1 = 1000$ rpm the current in the armature circuit is equal to $I_1 = 10$ and at the number of revolutions $n_2 = 900$ rpm it is equal to $I_2 = 15$ a. Find the number of revolutions dwiz of the blizzard at idle speed (without load).

Since $I = \frac{U - k \omega}{R}$ and $\omega = 2\pi n$, then

$$I_1 = \frac{U - 2\pi n_1}{R}$$

And

$$I_2 = \frac{U - 2\pi n_2}{R}.$$

In clap mode $I_3 = 0$, so

$$n_3 = \frac{I_2 n_1 - I_1 n_2}{I_2 - I_1} = \frac{15 \cdot 1000 - 10 \cdot 900}{5} = 1200 \text{ (об/мин)}$$.

Reversibility of electric machines

All DC machines are figurative. If a constant voltage is applied to the terminals of the machine, the armature will rotate, performing mechanical work, that is, we will get an electric motor. On the other hand, if you rotate the armature with the help of another machine, then the electric machine will work like a diamo machine, too much.

Question. Suppose the same machine rotates with the same

⟦folio 68⟧

increase speed, working once as a dynamo and another time as a motor. What can you say about e. d.s. induction that occurs in the anchor in both cases?

Answer. Since e. d.s. induction depends only on the design of the armature and the angular speed of rotation of the armature, then e. d.s. the induction in both cases will be the same.

Question. What if the catch speeds of rotation of the dynamo and the motor are different?

Answer. In this case, the ratio of the electromotive forces of induction will be equal to the ratio of the angular velocities of rotation of the armature.

Question. We have already talked about Ohm's law and the law of conservation of energy for a motor and wrote down the corresponding equalities (I) and (II). How will similar equalities look like for a dynamo?

Answer. Let the resistance of the dynamo circuit be equal to R. Then, according to Ohm's law

$$E_{\pi} = I_{\pi} R,$$

where $E_{\pi}$ is e. d.s. induction of the dynamo and $I_{\pi}$ - current.

Further, if we neglect energy losses (for example, during training), then we can write the law of conservation of energy as follows:

$$P_{\text{м}} = E_{\pi} I_{\pi}.$$

Here $P_{\text{м}}$ is the mechanical power expended on rotating the armature, $E_{\pi} I_{\pi}$ is the electrical power expended by the dynamo.

Let us now solve several problems.

Problem 1. A constant electric motor with independent excitation, connected to a battery circuit with a voltage of U = 24 V, with a total resistance of the circuit R = 20 from we do $n_1 = 600$ rpm with a possible in the circuit of I = 0.2 a. Which e. d.s. Let's develop the motor, working as a dynamo, at $n_2 = 1400$ rpm?

The e.m.f. developed by the dynamo is equal to

$$E_{\pi} = \frac{n_2}{n_1} E_{\pi},$$

where $E_{\pi}$ is e. d.s., arising in the armature winding of the motor at a rotation speed of $n_1 = 600$ rpm. It can be found from Ohm's law:

$$E_{\pi} = U - IR.$$

Pozotomu

$$E_{\pi} = \frac{n_2}{n_1} (U - IR) = \frac{1400}{600} (24 - 0,2 \cdot 20) \approx 46,7 (\beta).$$

Problem 2. A load of mass m is suspended on a thread wound on the armature axis of a dynamo with independent excitation. Then we unwind from the axis so that the load falls at a constant speed $v_1$. The dynamo is closed to resistance R. At what speed will $v_2$ rise in this constant moka with voltage U and the same circuit resistance R?

The power of a motor lifting a load of mass m with a speed $v_2$ is equal to $mgv_2$. From Ohm's law and the law of conservation of energy it follows that

$$U - E_{\pi} = IR$$

And

$$UI = I^2 R + mgv_2,$$

where I is current and $E_{\pi}$ is e. d.s. induction in the armature winding. This e. d.s. associated with e. d.s. induction dynamo matching

$$\frac{E_{\pi}}{E_{\pi}} = \frac{v_2}{v_1}.$$

Let us now write down Ohm’s law and the law of conservation of energy for a dynamo:

$$E_{\pi} = I_{\pi} R$$

And

$$E_{\pi} I_{\pi} = mgv_1.$$

From here

$$E_{\pi} = \sqrt{mgv_1 R},$$
