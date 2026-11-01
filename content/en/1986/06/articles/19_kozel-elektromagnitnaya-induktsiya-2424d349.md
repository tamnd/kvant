---
id: 1986-6-kozel-elektromagnitnaya-induktsiya-2424d349
issue: kvant_1986_6
year: 1986
number: "6"
title: Electromagnetic induction
authors:
  - Козел С. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 49, 51
tag: LFFO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 870c25c8c3b0b7ab802dff40093585932f78b94ddbe897356fa425958bdb8883
prompt_sha256: draft-1
translated_from: content/ru/1986/06/articles/19_kozel-elektromagnitnaya-induktsiya-2424d349.md
source_content_sha256: ca739d772a104d30ddda126f983d8f3d458d7c656de56e9704af2869bb09dca7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Electromagnetic induction

Doctor of Physical and Mathematical Sciences
S. M. KOZEL

The phenomenon of electromagnetic induction was discovered by Faraday in 1831. This discovery showed that there is a communication technology between the electric and magnetic fields - a magnetic field that changes over time generates an electric one. About 30 years later, Maxwell was able to show that a changing electric field in turn generates a magnetic field. In these two great discoveries, centuries later, essentially all modern science about electromagnetic fields is contained. They made it possible to predict the existence of radio waves, revealing the electromagnetic nature of light.

As a result of numerous and varied experiments, Faraday established a quantitative relationship between the induced emf $E_{\text{ind}}$ and the rate of change of magnetic flux $\Phi$, its arbitrarily closed loop (Faraday’s law):

$$E_{\text{ind}} = -\frac{\Delta \Phi}{\Delta t}.$$

In a more rigorous mathematical notation, $E_{\text{ind}}$ is expressed through the first arbitrary magnetic flux in time: $E_{\text{ind}} = -\Phi'(t)$.

The works on electromagnetic induction put forward by Faraday can be divided into two groups. The first group includes experiments with conductors moving in a magnetic field. In this case, an induced emf will occur due to the action of the Lorentz force. When a conductor moves, its free charges move with it. The Lorentz force acting on these charges causes them to move relative to the conductor.

figure 1 shows a diagram of one such experiment. In the magnetic field of a permanent magnet there is a closed wiring frame, in the circuit of which the galvanometer G is included. The frame moves away at a speed of $\vec{v}$ from the southern flange of the magnet, and its plane remains perpendicular to the axis of the magnet. When moving within the frame, an induction current will occur. Faraday's formula allows you to find the direction of the induction current.

Question 1. What is the physical meaning of the “—” sign in the formula for $E_{\text{ind}}$?

To determine the direction of the induction current we need

⟦folio 48⟧

first of all, set the positive direction of the current in the frame and the direction of the positive normal to the plane of the frame (which determines the sign of the magnetic flux). These two directions must be coordinated according to the rule of the right vinata (gimlet). So, if at figure 1 we select the direction of the positive normal $n$ to the plane of the frame from left to right, then the positive direction of the current should be chosen counterclockwise (if you look at the frame in a magnetic state). With this choice, the magnetic flux of an arbitrary frame contour is $\Phi > 0$, but as the frame moves away from the magnet, the flux decreases and, therefore, $\Delta \Phi / \Delta t < 0$. From Faraday's law it follows that $\mathcal{E}_{\text{инд}} > 0$.

If the frame has active resistance $R$, then the induced current is $I = \mathcal{E}_{\text{инд}} / R > 0$. This means that the current will flow counterclockwise.

The rule of signs discussed here often eludes applicants. Meanwhile, the “—” sign in Faraday’s law ensures the fulfillment of the law of conservation of energy. In our example, each element of the frame through which the induction current flows will be acted upon by the Ampere force $F$. The horizontal component of this force is directed against the movement of the frame. Thus, in accordance with the law of conservation and transformation of energy, the frame will experience braking, and a Joule body will be released in the frame itself.

An induced current in the frame will arise not only when it moves forward, but also when the frame rotates or deforms in a magnetic field. It is only important that the magnetic flux changes in an arbitrary frame.

Experience shows that if the frame is left stationary and the magnet is moved, then induction phenomena occur in exactly the same way as when the frame moves. The induced current depends only on the relative movement of the frame and the magnet. Faraday's law also applies in this case, but the explanation of the phenomenon now turns out to be completely different. In stationary circuits, the Lorentz force cannot cause the movement of charges along the conductors. Responsible for the occurrence of $\mathcal{E}_{\text{инд}}$ in this case is the electric field that arises when the magnetic field changes. This field is called a vortex field because, unlike the electrostatic field, its lines of force can be closed.

Question 2. What is the connection between the vortex electric field and $\mathcal{E}_{\text{инд}}$?

By definition, the electrifying force is equal to the work of the forces acting on a unit positive charge as it moves along a closed path. In an electrostatic field, this work is always zero (such fields are called potential). In a vortex electric field it can be different from zero. This work is equal to $\mathcal{E}_{\text{инд}}$.

As an example, consider the magnetic field between the positions of the electromagnet (Fig. 2). Let us assume, for simplicity, that they are cylindrical, so that the magnetic field in the region close to the axis can be considered unipodemic. If the magnetic field changes with time, then a vortex electric field will appear in the vortex of the electromagnet, the force lines of which are concentrated

⟦folio 49⟧

tric circle. Select a circle with radius $r$. The work of the vortex electric field when moving a unit positive charge along this circle can be written in the form

$$E(r) \cdot 2\pi r = \mathcal{E}_{\text{инд}} = -\frac{\Delta \Phi}{\Delta t} = -\frac{\Delta B}{\Delta t} \pi r^2.$$

From here

$$E(r) = -\frac{r}{2} \frac{\Delta B}{\Delta t}.$$

The direction of linear strength $\vec{E}$ of the vortex electric field on figure 2 is shown for the case when the indication $\vec{B}$ of the magnetic field returns with time.

The concept of a vortex electric field was introduced by Maxwell. According to Maxwell, the existence of electromagnetic induction consists in the emergence of a vortex electric field, which may not necessarily return in conductors. It can also occur in space where there are no conductors. A vortex electric field generated by a changing magnetic field can act on individual charged particles in a vacuum, such as, for example, an electric locomotive accelerator - a betatron (see problem 4).

Let us now consider a number of problems on induction phenomena in moving and stationary conductors.

Problem 1. A rod CD, length $l=10$ cm and mass $m=10$ g (Fig. 3), slides along two vertical parallel slats, closed at the top through a resistor with resistance $r=1,1$ Ohm and a battery with emf $E=1$ V, without friction. System of being in a uniform magnetic field with induction $B=1$ T. Vector $\vec{B}$ is perpendicular to the drawing plane and is directed towards the reader. Find the steady speed of the rod. At what correspondence between the parameters of the problem will the steady velocity be directed upward?

Consider the contour ACDK, shaded at figure 3. When the rod moves, $\mathcal{E}_{\text{инд}}$ will appear in it. For the positive direction of the current in this circuit, we choose the counterclockwise direction. Then the positive normal to the contour plane is directed towards the reader and, therefore, the magnetic flux

$$\Phi > 0.$$ When the Vism rod moves, the magnetic flux through the circuit increases: $\Delta \Phi/\Delta t > 0$. If the speed of fall is denoted by $v$, then $\mathcal{E}_{\text{инд}} = -\Delta \Phi/\Delta t = -vlB$.

Let us now write Ohm's law for the ACDK circuit:

$$Ir = -\mathcal{E} + \mathcal{E}_{\text{инд}} = -\mathcal{E} - vlB.$$

To this equation it is necessary to add the conditions of constant speed: during steady motion, the force of the rod $m\vec{g}$ is compensated by the ampere force $\vec{F}$ acting on the rod from the side of the magnetic field. Applying the left-hand rule, it is easy to verify that the amperator force will be directed upward when the current in the rod flows from right to left, that is, at $I < 0$. Hence,

$$mg = F = -IBl.$$

From here

$$v = \frac{1}{BL} \left( \frac{mgr}{Bl} - \mathcal{E} \right).$$

Substituting numerical data, we find: $v = 1$ m/s > 0 - the rod of the effective movement.

In order for the steady speed to be directed upward, the condition must be satisfied

$$\mathcal{E} > \frac{mgr}{Bl} = 1,1$$ V.

Let us pay attention to the fact that a very important energy relationship follows from the written formulas:

$$I^2r = -\mathcal{E}I - vlBI = -\mathcal{E}I + mgv.$$

Joule heat $I^2r$, released per unit time at resistance $r$, is equal to the sum of the battery work - $\mathcal{E}I$ (this work is positive, since $I < 0$) and the gravity force $mgv$ during the same time. The magnetic field does not work!

⟦folio 51⟧

Task 4. Accelerate the electrons - in the betatron - the role of the accelerating field is played by the vortex electric field, excited by a change in the magnetic flux that produces the orbit of the electrons. Assuming the radius of the electron orbit to be unchanged, determine the correspondence necessary for this at a given time between the average magnetic field $B_{cp}$, which produces the electron orbit, and the magnetic field in the orbit $B$. The magnetic field is parallel to the symmetry axis of the betatron vacuum chamber.

The physics of this problem is that the vortex electric field $E$ and the speed $v$ imparted by this field to the electron are determined by the change in the average value of the magnetic field producing the orbit, and the Lorentz force holding the electron depends on the magnetic field in the orbit itself.

Using the same reasoning as when solving the previous problem, we write down

$$|E| = \frac{r}{2} \frac{\Delta B_{cp}}{\Delta t}, \quad v(t) = \frac{er}{2m} B_{cp}(t).$$

From the condition of electron motion in orbit $evB = mv^2/r$ we obtain

$$B(t) = \frac{mv(t)}{er} = \frac{B_{cp}(t)}{2}.$$

Thus, for stable operation of the betatron it is necessary that the average magnetic field inside the orbit at any time be twice as large as the field in the orbit. Therefore, the magnetic field in the central part of the orbit should be greater than in the orbit itself. This is achieved by a special choice of magnet configuration.

Finally, let's look at an interesting application of the law of electromagnetic induction to superconducting coils. Superconductors are widely used to create strong electromagnets. In a closed superconducting winding, current can circulate for a long time without an energy source.

Let's assume that we have a short-circuited loop made of a superconductor. Let the current in the frame be zero. Let us introduce the frame into an external uniform magnetic field with induction $B$ directed perpendicular to the plane of the frame.

Question 4. What magnetic flux penetrates the frame?

It must be answered that many applicants answer this question this way: the magnetic flux is equal to the product $BS$, where $S$ is the area of ​​the frame. This answer is incorrect. The correct answer is that the magnetic flux producing the electron orbit and the magnetic field in the $B$ orbit. The magnetic field is parallel to the symmetry axis of the betatron vacuum chamber.

The physics of this problem is that the vortex electric field $E$ and the speed $v$ imparted by this field to the electron are determined by the change in the average value of the magnetic field producing the orbit, and the Lorentz force holding the electron depends on the magnetic field in the orbit itself. This result follows from Faraday's law. Indeed, for a superconducting closed circuit, Ohm's law is written in the form $0 = -\Delta \Phi/\Delta t$. On the left side of this correspondence is the voltage drop at zero resistance of the superconductor, on the right side is the induced emf. It follows that $\Phi = const$. Thus, a closed superconducting circuit is a magnetic shelf conservator. It preserves the magnetic flux that permeates the circuit at the moment of transition to the superconducting state. This flow cannot be changed by any external fields (as long as superconductivity is maintained).

The physical mechanism that ensures the conservation of flux is that when the external magnetic shelf changes, an induced current appears in the circuit, the magnetic field of which completely compensates for the change in the external magnetic shelf.

Task 5. By what amount does the current change in a circular loop of a superconductor if you put it on a long solenoid, which is connected to a battery with emf $\mathcal{E}$, as shown in figure 5? The total resistance of the solenode circuit is $r$, the loop inductance is $L$, the inductance of the solenode is $L_0$, its number of turns is $N$.

Let $I_0$ and $I$ be the initial and final values ​​of the current in the loop. Note that the current into the solenode does not change and remains equal to $\mathcal{E}/r$, so the self-magnetic flux of the solenode is equal to $L_0\mathcal{E}/r$. In this case, each turn of the solenode registers a magnetic flux $L_0\mathcal{E}/(rN)$. The same flow (external to the loop) also flows through the loop placed on the solenoid. But the total magnetic flux in the loop must remain unchanged. That's why

$$LI \pm L_0\mathcal{E}/(rN) = LI_0,$$

or

$$I_0 - I = \pm L_0\mathcal{E}/(LrN).$$

The ambiguity in these formulas is due to
