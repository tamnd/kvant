---
id: 1991-12-gurevich-malkov-kak-obmanut-integral-ceb93e27
issue: kvant_1991_12
year: 1991
number: "12"
title: How to cheat the integral
authors:
  - Гуревич Б.
  - Малков Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86eb3afc5dbb434a95a465c19c0a8ba88435b22c27b01f14f391b67242f4c203
prompt_sha256: draft-1
translated_from: content/ru/1991/12/articles/14_gurevich-malkov-kak-obmanut-integral-ceb93e27.md
source_content_sha256: 2c7d261bf8f2499ce92fb8a1554ea757071561109c0c3e8338130b7e097806a8
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 45⟧

---
running_head:
folio:
---

How to cheat the integral

V. GUREVICH, R. MALKOV

At competitions, and sometimes at entrance exams in physics, there are problems that seem impossible to solve without going beyond the scope of school mathematics. But often the keys to the solution are contained in the problem statement itself, and the result of cumbersome calculations is “hidden” in the initial data, which significantly simplifies the situation. Here's an example.

Problem 1. Two tourists are walking along a straight road to overtake each other at a speed of 5 km/h each. When the distance between them was 10 km, a fly took off from the shoulder of the one-eyed tourist and flew forward at a speed of 20 km/h. Having met the second one, she turned and flew back at the same speed. So she flew between the two

Rastas before they meet. What distance does she fly?

At first glance, here it is necessary to sequentially add the lengths of straight segments of the fly’s trajectory. But the problem can be solved without being able to sum up the series if you notice that the fly flew for 1 hour (the time before meeting the tourists) at a speed of 20 km/h, so its path is 20 km.

Already using the example of this simple and well-known task, it is clear that it is not always necessary to describe the process in detail. Now let's look at some more complex problems.

Problem 2. A boat of mass m, standing in calm water, was pushed with a speed v₀. How far will it travel before it stops, if the force of resistance to movement is proportional to the speed: F = - αv?

At any moment of motion, the acceleration of the boat, according to Newton's second law, is equal to

a = - α/m v,

⟦folio 46⟧

---
running_head:
folio:
---

where $v$ is the speed of the boat at this moment. This is an example of movement with variable acceleration (the lower the speed, the slower it decreases), in which, if the conditions of the problem are ideally fulfilled, the boat will move indefinitely (albeit very slowly at the end). However, this does not mean that the braking distance will be infinite. How to find him?

Let us multiply both sides of the previous equation by a short period of time $\Delta t$, beyond which the changes $v$ and $a$ can be neglected:

$$a\Delta t = -\frac{\alpha}{m}v\Delta t.$$

Now note that $a\Delta t$ is the increment in speed $\Delta v$ in time $\Delta t$, and $v\Delta t$ is the increment in path $\Delta l$ in the same time. Since the moment of time was chosen completely arbitrarily, we can conclude that in order for the speed to change to $\Delta v$, the boat must travel a distance

$$\Delta l = -\frac{m}{\alpha}\Delta v$$

(the minus in the expression is explained by the fact that $\Delta v$ is negative). From the condition it is clear that over a sufficiently long time the speed of the boat decreases from the initial value $v_0$ to almost zero. Then the entire distance traveled is equal to

$$l = \frac{m}{\alpha}v_0.$$

The next electrical problem is solved in exactly the same way.

Problem 3. What kind of mystery will pass through the resistor in the circuit shown in figure 1 after the switch is closed, if there was no current closure in the coils? All parameters of the circuit are known.

Let, some time after closing the key, the current flowing from point $A$ to point $B$ through the inductance coil $L_1$ be equal to $I_1$, and through the coil inductance $L_2 - I_2$. Then for any moment of time, in accordance with Ohm’s law, we can write

$$L_1\Delta I_1 = L_2\Delta I_2 + RI_2\Delta t,$$

where $\Delta I_1$ and $\Delta I_2$ current increments, $I_2\Delta t$ is the increment of the desired charge $q$ for a short period of time $\Delta t$. From here we get

$$\Delta q = \frac{1}{R}(L_1\Delta I_1 - L_2\Delta I_2).$$

Immediately after closing the key, both points are equal to zero, and in the set mode

$$I_1 = \frac{\mathcal{F}}{r}, I_2 = 0.$$

As a result of summing all charge increments, we find

$$q = \frac{L_1\mathcal{F}}{Rr}.$$

A more detailed substantiation of the correctness of our reasoning will be carried out when solving the next problem.

Problem 4. A washer (Fig. 2) lies on an inclined plane with an angle of inclination $a$. It is entirely given a speed $v_0$ along the horizontal plane. After what time will the washer stop if the coefficient of friction on the plane is $\mu$, and $\mu > tg\alpha$?

⟦folio 47⟧

---
running_head:
folio:
---

Most importantly, we note that over time the speed of the puck changes both in magnitude and in direction. In the plane of motion, two forces act on the puck: the friction force $\vec{F}_1$, the direction is opposite to the speed and is equal to

$$F_1 = \mu mg \cos \alpha,$$

and the component $\vec{F}_2$ of gravity, perpendicular to the initial velocity and is equal to

$$F_2 = mg \sin \alpha.$$

Let at some moment of time the speed be equal to $v$ and directed at an angle $\beta$ to the initial one. From Newton’s second law it follows that in a short period of time $\Delta t$ the speed of the puck will change by the amounts

$$\Delta v = \frac{1}{m} (-F_1 + F_2 \sin \beta) \Delta t.$$

In this case, the change in its projection to the direction of force $\vec{F}_2$ will be equal to

$$\Delta (v \sin \beta) = \frac{1}{m} (-F_1 \sin \beta + F_2) \Delta t.$$

(**)

The last two equalities (*) and (**) are rather complex differential equations, by solving which one can, in principle, obtain the required time of movement of the puck. But this goes far beyond the scope of school mathematics. So we'll do it differently.

Note that through the definition of time, both the speed $v$ and its projection $v \sin \beta$ will become zero. This circumstance, obvious from the conditions of the problem, can be used to bypass the difficulties of solving the equation. Mathematically it is expressed like this:

$$\Sigma \Delta v = -v_0 \text{ и } \Sigma \Delta (v \sin \beta) = 0.$$

Here and below, the sign $\Sigma$ will denote the sum of the values ​​of the quantity under this sign for all small periods of time into which the process is divided. In particular, the required time for the puck to move before stopping is equal to

$$t = \Sigma \Delta t.$$

Let's divide both sides of the equation (*) and (**) by $F_2$ and $F_1$, respectively, and add the resulting equalities. We'll get

$$\frac{1}{F_2} \Delta v + \frac{1}{F_1} \Delta (v \sin \beta) = \frac{1}{m} \left( \frac{F_2}{F_1} - \frac{F_1}{F_2} \right) \Delta t,$$

or

$$\Delta t = m \left( \frac{F_1}{F_2} - \frac{F_1}{F_2} \right) \Delta v + \frac{F_2}{F_2} \Delta (v \sin \beta).$$

Substituting here the values ​​for $F_1$ and $F_2$ and summing both sides of the equality, we find the required time:

$$t = \frac{v_0}{g} \frac{\mu \cos \alpha}{\mu^2 \cos^2 \alpha - \sin^2 \alpha}.$$

Now, finally, you can formulate the main idea of ​​​​the solution. It consists in the fact that an equation is derived, on the left side of which there is an instantaneous increment of the desired value at an arbitrary moment of the process, and on the right side there is a linear combination of increments of the value, the initial and final values ​​of which are known or expressed through the desired value. The summation of all the values ​​of the right and left sides of this equation for all small periods of time into which the process is divided gives an algebraic equation for the desired value. For convenience, we will summarize this method by the method of sampling sums. Its peculiarity lies in the fact that in some cases it is more convenient for a system to converge not to an equation with one variable, but to an equation with many variables, but with selected definitions.

The possibilities for using the sum sampling method are not always the same. Thus, in problems 2 and 3, the increment of the desired value, expressed through increments of the value with known limits of change, is obtained directly from the original system. In Problem 4, to isolate the desired increment, a number of algebraic transformations are required. But in the next problem algebraic transformations alone cannot be used.

⟦folio 48⟧

---
running_head:
folio:
---

Task 5. In the circuit shown in figure 3, at first the switches are open and there is no charge on the capacitor. Find the amount of heat released by the resistor with resistance $R_2$ after the switch is closed. All parameters of the circuit are known.

Let at some instant of time after closing the key from point $A$ to point $B$ a current $I_1$ flows through the first resistor, $I_2$ through the second, and the charge of the capacitor is $q$. Over a short period of time $\Delta t$ the increment of the original value is

$$\Delta Q = I_2^2 R_2 \Delta t,$$

and increasing the capacitor charge -

$$\Delta q = I_2 \Delta t.$$

Hence,

$$\Delta Q = I_2 R_2 \Delta q.$$

In the last equation there is no linear combination of increments of a quantity whose initial and final values ​​are known, since the coefficient in front of $\Delta q$ is a variable quantity. But from the conditions of the problem it is easy to find the limit of the change in currents, so we will try to express $\Delta Q$ through their instantaneous increments $\Delta I_1$ and $\Delta I_2$. We follow this using Ohm's law:

$$\mathcal{E} - r (I_1 + I_2) = R_1 I_1,$$

$$R_1 I_1 = \frac{q}{C} + R_2 I_2,$$

or

$$- r (\Delta I_1 + \Delta I_2) = R_1 \Delta I_1,$$

$$R_1 \Delta I_1 = \frac{\Delta q}{C} + R_2 \Delta I_2.$$

Expressing $\Delta q$ from here in terms of $\Delta I_2$, we get

$$\Delta Q = - \frac{R_2 C}{2} \left( R_2 + \frac{R_1 r}{R_1 + r} \right) \Delta (I_2^2).$$

So through the second resistor immediately after closing the key it is equal to

$$I_2 = \frac{\mathcal{E} R_1}{R_1 r + R_2 r + R_1 R_2},$$

and its final value is zero. Therefore, summing the expression for $\Delta Q$ gives the required amount of heat:

$$Q = \frac{\mathcal{E}^2 R_1 R_2 C}{2 (R_1 + r) (R_1 r + R_2 r + R_1 R_2)}.$$

The result obtained can, if desired, be generalized for an arbitrary initial charge of the capacitor.

As can be seen from the above examples, the proposed method in some cases allows for a significant compaction of mathematical calculations and eliminates the need to solve differential equations. On the other hand, the authors, who are former applicants themselves, sincerely hope that the members of the application commissions do not have the cunning to include such tasks in the entrance exam program. But - who knows?

At the right
1. In the conditions of problem 4, find the path taken by the puck.
2. In crossed homogeneous electrostatic (with intensity $\vec{E}$) and magnetic (with induction $\vec{B}$) fields ($\vec{E} \perp \vec{B}$) a particle with mass $m$ and charge $q$ is kept at rest. At some point in time the particle is released. Find the distance between the line of established motion and the initial position of the particle if it is acted upon by a viscous friction force $\vec{F} = -\beta \vec{v}$.
3. In the conditions of problem 3, find the amount of heat released by the resistor after the switch is closed.
4. In the circuit shown at figure 4, first the switch is open, then there is no voltage through the coil and the capacitor is not charged. How much heat will be released in the resistor after the switch is closed? All parameters of the circuit are known.
