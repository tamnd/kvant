---
id: 1990-1-slobodetskiy-elektricheskie-mashinyi-postoyannogo-toka-4e58ac9e
issue: kvant_1990_1
year: 1990
number: "1"
title: DC Electrical Machines
authors:
  - Слободецкий И. Ш.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 65
page_last: 69
page_labels: 63-67
lang: en
source: kvant_digital
extraction: vision
content_sha256: 11db8f2006922d75374c20ecce5c0feb5035aef5d65e0399fe21396aac473365
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/15_slobodetskiy-elektricheskie-mashinyi-postoyannogo-toka-4e58ac9e.md
source_content_sha256: b636f0363049ec98f9b4ad7cacdbc3548c9b66487d86b613515a9e6d713354f2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 63⟧

---
running_head:
folio:
---

Electrical
cars
DC
Candidate of Physical and Mathematical Sciences
I. SLOVODETSKY

In this article we will not discuss in detail the structure of various electrical machines. We will look at the operation of an electric motor and a dynamo (a dynamo is the old name for an induction generator of electric current), using two basic laws - Ohm's law and the law of conservation of energy.

The article consists mainly of questions and answers. When working on an article, before reading the answer, try to answer the question yourself. Further, you will not be able to do this; thinking about the question will play an undoubted role, thanks to which it is better to fill in the correct answer.

Electric motors

All electric motors (or, in other words, electric motors) necessarily have the same basic parts. This is, first of all, an inductor and an anchor. The inductor is a source of magnetic field. When an electric current is passed through the armature winding, the armature, located in a magnetic field, rotates. In this way, electrical energy is converted into mechanical energy. If, for example, a motor shaft is connected to a machine tool, the machine can be set in motion.

This article was published in «Kvant» No. 5, 1974, under the pseudonym I. A. Zaitsev.

⟦folio 64⟧

---
running_head:
folio:
---

Question. A direct current motor with independent excitation (in it the inductor is either a permanent magnet or an electromagnet, the winding of which is powered independently of the armature winding). How is Ohm's law written for the armature circuit of such a motor connected to a DC source?

Answer. In the electric circuit of the armature, there are two electromotive forces - the direction of the current source $U$ and the induced emf $E_n$, which arises in the armature winding when it rotates in the magnetic field of the inductor. Moreover, the induced emf, according to Lenz’s rules, is opposite in sign to the direction of the current source. Therefore, Ohm's law will be written like this:

$$U - E_n = IR,$$

(I) where $I$ is the current in the circuit, and $R$ is the total resistance of the armature winding and lead wires.

Question. How is the law of conservation of energy written for such a circuit?

Answer. The energy $W_n = UIt$ consumed from the source is spent on Joule heat, which is released at the resistance $R$, and on performing useful work $A$. Therefore, according to the law of conservation of energy,

$$UIt = I^2Rt + A,$$

or for capacities

$$UI = I^2R + P.$$

(II) From equalities (I) and (II) many important consequences can be obtained.

Question. What is the useful power $P$?

Answer. Multiplying both sides of equality (I) by the current $I$, we obtain

$$UI - E_n I = I^2R,$$

or

$$UI = I^2R + E_n I.$$

Comparing the resulting equality with equality (II), one can immediately notice that

$$P = E_n I,$$

i.e., the useful power of the motor is equal to the product of the induced emf and the current.

At constant $U$ and $R$ the current value depends on the induced emf:

$$I = \frac{U - E_n}{R}.$$

From the law of electromagnetic induction it follows that the induced emf arising in the armature winding is proportional to the rate of change of the magnetic flux $\Delta \Phi/\Delta t$ through this winding:

$$E_n \sim \frac{\Delta \Phi}{\Delta t}.$$

In turn, the rate of change of the magnetic flux is proportional to the angular speed of rotation of the armature $\omega$. Thus,

$$E_n \sim \omega,$$

$$E_n = k\omega,$$

where $k$ is the proportionality coefficient. A graph of $E_n$ versus $\omega$ is shown in figure 1.

Now let's see how the current in the armature circuit and the useful power of movement depend on $\omega$. From Ohm's law

$$I = \frac{U - E_n}{R} = \frac{U - k\omega}{R}$$

and from the law of conservation of energy

$$P = UI - I^2R = E_n I = \frac{kU\omega - (k\omega)^2}{R}.$$

⟦folio 65⟧

---
running_head:
folio:
---

Graphs of the dependence of $I$ and $P$ on $\omega$ are shown in Figures 2 and 3.

So, each value of angular velocity $\omega$ corresponds to certain values ​​of the induction emf $E_n$ and current $I$. Moreover, as $\omega$ increases, the value $E_n$ increases, and the value $I$ decreases. In this case, the useful power developed by the motor turns out to be the same at two different values ​​of the armature rotation speed.

Question. In turn, the catching speed of rotation of the anchor depends on the engine load. How?

Answer. The electric forces acting on the armature in the magnetic field of the inductor are proportional to the current flowing through the winding. The moments of these forces are also proportional to the current, i.e. $M_s = k_1 I$,

where the proportionality factor $k_1$ depends on the motor design. Because

$$I = \frac{U - k \omega}{R},$$

That

$$M_s = k_1 \frac{U - k \omega}{R},$$

that is, the total moment of electrical forces acting on the armature depends linearly on the angular speed of rotation of the armature. At a low angular speed of rotation of the armature, the moment of force is large; with increasing angular speed, it decreases and becomes equal to zero at

$$\omega = \frac{U}{k}.$$

On the other hand, a moment of mechanical forces, the so-called load moment $M$, acts on the motor shaft. For example, if the engine uniformly lifts a load on a rope, then the load moment is equal to the product of the tension force of the rope, which is equal to the weight of the load, and the radius of the shaft. In the set mode, the motor armature rotates very quickly at such a speed $\omega$ at which the moment of the electrical forces acting on the armature is equal to the load moment. Indeed, let, for example, the speed of rotation of the anchor be less than $\omega$. In this case, the moment of the electronic forces is greater than the load moment, so the angular velocity of rotation of the armature will increase. If the angular speed of rotation of the armature is greater than $\omega$, then the moment of electrical forces is less than the load moment. This will lead to a decrease in the speed of rotation of the anchor to $\omega$.

Thus, the angular speed of rotation of the anchor is also established, at which

$$M_s = M,$$

or

$$k_1 \frac{U - k \omega}{R} = M,$$

where

$$\omega = \frac{k_1 U - MR}{k_1 k},$$

i.e., the angular velocity of rotation of the armature linearly depends on the load moment.

So, the load determines the current in the armature winding and the angular speed of its rotation.

Let's consider this problem.

Task 1. An electric blower is connected to a constant voltage source. At a speed of $n_1 = 1000$ rpm, the current in the armature circuit is equal to $I_1 = 10$ A, and at a speed of $n_2 = 900$ rpm it is equal to $I_2 = 15$ A. Find the number of engine revolutions when cold (without load).

Since $I = (U - k \omega) / R$ and $\omega = 2\pi n$, then

$$I_1 = \frac{U - 2\pi n_1}{R}$$

And

$$I_2 = \frac{U - 2\pi n_2}{R}.$$

In cold mode $I_3 = 0$, so

$$U - 2\pi n_3 = 0.$$

Solving these equations together, we find

$$n_3 = \frac{I_2 n_1 - I_1 n_2}{I_2 - I_1} = \frac{15 \cdot 1000 - 10 \cdot 900}{5} \frac{\text{об}}{(\text{мин})} = 1200 \text{ об/мин}.$$

⟦folio 66⟧

---
running_head:
folio:
---

Reversibility of electric machines
All direct current machines are imaginable. If a constant voltage is applied to the terminals of the machines, the armature will rotate, performing mechanical work, i.e. we will get an electric motor. On the other hand, if you rotate the armature with the help of another machine, then the electric machine will work as a diamo machine producing current.

Question. Suppose the same machine rotates at the same speed, working once as a diamo machine and another time as a motor. What can be said about the induced emf that arose in the armature in both cases?

Answer. Since the induced emf depends only on the design of the armature and the angular speed of rotation of the armature, the induced emf in both cases will be the same.

Question. What if the catch rotation speeds of the diamo machine and the motor are different?

Answer. In this case, the ratio of the electromotive forces of induction will be equal to the ratio of the angular velocities of rotation of the armature.

Question. We have already talked about Ohm's law and the law of conservation of energy for a motor and wrote down the corresponding equalities (I) and (II). What would similar equalities look like for a diamo machine?

Answer. Let the resistance of the diamo machine circuit be equal to R. Then, according to Ohm’s law,

$$E_{\pi} = I_{\pi} R,$$

where $E_{\pi}$ is the induced emf of the diamo-machine and $I_{\pi}$ is the current. Further, if we neglect energy losses (for example, during training), then we can write the law of conservation of energy as follows:

$$P_{\pi} = E_{\pi} I_{\pi}.$$

Here $P_{\pi}$ is the mechanical power expended on armature rotation, $E_{\pi} I_{\pi}$ is the electrical power developed by the diamo-machine.

Let us now solve several problems.

Problem 2. A direct current electric motor with independent excitation, connected to a battery circuit with a voltage of U = 24 V, with a total circuit resistance of R = 20 Ohm, makes $n_1 = 600$ rpm at a current in the circuit I = 0.2 A. What EMF will the same motor develop, operating as a diamo-machine, at $n_2 = 1400$ rpm?

The emf developed by the diamo-machine is equal to

$$E_{\pi} = \frac{n_2}{n_1} E_{\pi},$$

where $E_{\pi}$ is the induced emf generated in the armature winding of the motor at a rotation speed of $n_1 \neq 600$ rpm. It can be found from Ohm's law:

$$E_{\pi} = U - IR.$$

Because

$$E_{\pi} = \frac{n_2}{n_1} (U - IR) = \frac{1400}{600} (24 - 0,2 \cdot 20) B \approx 46,7 B.$$

Problem 3. A load of mass m is suspended on a thread wound on the axis of an armature of a diamo-machine with independent excitation. The thread unwinds from the axis so that the load descends at a constant speed $v_1$. The diamo-machine is closed to resistance R. At what speed $v_2$ will the same load rise upward if the diamo-machine is connected as an electric motor in a direct current circuit with voltage U and the same circuit resistance R?

The power of a motor lifting a load of mass m with a speed $v_2$ is equal to $mgv_2$. From Ohm's law and the law of conservation of energy it follows that

$$U - E_{\pi} = IR$$

And

$$UI = I^2 R + mgv_2,$$

where I is the current and $E_{\pi}$ is the induced emf in the armature winding. This EMF is related to the induced EMF of the diamo-machine by the relation

$$\frac{E_{\pi}}{E_{\pi}} = \frac{v_2}{v_1}.$$

Let us now write down Ohm’s law and the law of conservation of energy for a diamo machine:

$$E_{\pi} = I_{\pi} R$$

⟦folio 67⟧

---
running_head:
folio:
---

$$E_{\pi} I_{\pi} = mg v_1.$$
From here
$$E_{\pi} = \sqrt{mg v_1 R},$$
and from correspondence (3)
$$E_{\pi} = \frac{v_2}{v_1} E_{\pi} = \frac{v_2}{v_1} \sqrt{mg v_1 R}.$$
Substituting the resulting expression for $E_{\pi}$ into equation (1) and then solving equations (1) and (2) together, we find
$$v_2 = \frac{\sqrt{mg v_1 RU} - mg v_1 R}{mg R} = U \sqrt{\frac{v_1}{mg R}} - v_1.$$
Problem 4. A DC electric motor with independent excitation (with a permanent magnet) lifts a load at a speed $v_1$ using a thread wound around the motor axis. In the absence of a load, the inconsistent thread rises at speed $v_0$. At what speed $v_2$ will the same load be lowered if a short circuit occurs in the armature circuit, as a result of which the armature winding becomes short-circuited? Neglect friction in the bearings.

After the winding is short-circuited, the motor will turn into a dynamo, and the current $I$ in the armature of the dynamo will be the same as it was when the machine worked as an electric motor. Indeed, in both cases the same load moves (rises or falls) uniformly. Therefore, the moment of forces acting on the armature from the magnetic field of the inductor and proportional to the magnitude of the current is equal to the moment of gravity of the load. When lifting an incompatible thread (in idle mode), the load torque is zero, and therefore the current $I_0 = 0$. Let's write Ohm's law for all three cases:

when lifting a load using a motor
$$U - E_{\pi} = IR,$$
where $U$ is the voltage at the motor terminals;
when lowering the load, when the motor works like a dynamo,
$$E_{\pi} = IR;$$

when the motor is idling,
$$U - E_{\pi}' = 0.$$
For three emfs $E_{\pi}$, $E_{\pi}'$ and $E_{\pi}$ the following correspondences can be written:
$$E_{\pi} = \frac{v_1}{v_2} E_{\pi}$$
And
$$E_{\pi}' = U = \frac{v_0}{v_2} E_{\pi}.$$
Finally located
$$v_2 = v_0 - v_1.$$
Exercises
1. The electric motor makes $n_1 = 1000$ rpm without load, and with some load - $n_2 = 700$ rpm. What will the rotation speed be if the load torque increases by 20%?
2. The electric motor is connected to a voltage source $U = 500$ V. Knowing that at a current $I_1 = 10$ A the motor develops a power of $P_1 = 4$ kW, find its power at a current $I_2 = 20$ A (this changes due to changes in the load).
3. The angular speed of rotation of the armature of a dynamo with a permanent magnet increased by 10%. By what percentage did the useful power of the dynamo increase?
4. The resistance of the motor armature winding is $R_1$, and the inductor winding is $R_2$. If the armature and inductor windings are connected in series and connected to the same current source, they speak of a motor with series excitation, or a serial motor. If the windings are connected in parallel, they speak of a parallel-excited motor, or a jester motor. In which case will the maximum net power be greater? What are the efficiency coefficients of the jester and serial engines? The voltage at the motor terminals is $U$.
