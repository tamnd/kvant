---
id: 1989-12-mukushev-metod-graficheskih-otsenok-37efb00d
issue: kvant_1989_12
year: 1989
number: "12"
title: Graphical assessment method
authors:
  - Мукушев Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 58
page_labels: 52-56
tag: SET2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 41061ea8e6d2331a2a8be63aa81cde962a255ab14a75077a760a2d6dae5d2dec
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/13_mukushev-metod-graficheskih-otsenok-37efb00d.md
source_content_sha256: b037b061a486b0569bc111e8f48a4b36eb5f6c90b5eccfc3a4f74eda99155478
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Graphical assessment method

V. A. MUKUSHEV

There are many different methods in the study of physical phenomena and processes. One of them is the graphical assessment method. It is also used in solving specific physical problems.

The graphical method, on the one hand, makes the various stages of solving the problem clear, and on the other hand, makes it possible to quickly evaluate the resulting solution, which is especially important in the case of a cumbersome analytical solution or when it is impossible.

Since the graphical method is an approximate calculation method, the results are not accurate. However, accuracy can always be increased using tables, microcalculators, and computers. By constructing the appropriate graphs, you can quickly get an approximate result and check how real it is and whether it makes physical sense.

The problems proposed in the article are unlikely to be given in university entrance exams, although you may undoubtedly encounter similar problems that have a cumbersome analytical solution.

Problem 1. A toy “Vanka-Vstanka” (Fig. 1) is placed on top of a fixed step with radius R. The lower surface of the toy is spherical with radius r, the center of gravity of the toy - point C - is located in the middle of the radius of the sphere. To what maximum angle β_max can the toy be deflected so that it returns to its initial position if R/r=4?

⟦folio 53⟧

When the toy deviates, for example, to the right, the center of gravity shifts (see Fig. 1). If at the same time it turns out to be to the left of the vertical $AB$, passing through the fulcrum point $A$, then the moment of gravity will return the toy to the equilibrium position. If the center of gravity is to the right $AB$, the toy will fall.

Let us denote $\alpha$ as the angle of rotation of the toy, $\beta$ as the angle of rotation of the radius $O'A$. Others $LA$ and $KA$ are equal (no slippage), i.e. $\alpha r = \beta R$, hence $\alpha = \beta \frac{R}{r}$.

From triangle $OAB$ we have

$$\frac{OB}{\sin \beta} = \frac{AO}{\sin (\pi - \alpha - \beta)} = \frac{r}{\sin (\alpha + \beta)} = \frac{r}{\sin (\beta (1 + R/r))},$$

or

$$OB = \frac{r \sin \beta}{\sin (\beta (R/r + 1))}.$$

The toy will return to its original position if $OC = \frac{1}{2} r > OB$, i.e.

$$\frac{1}{2} r > \frac{r \sin \beta}{\sin (\beta (R/r + 1))},$$

or, taking into account the relation $R/r = 4$, $\sin 5\beta > 2 \sin \beta$.

To find the limiting angle $\beta_{\max}$, we have to solve the trionometric equation

$$\sin 5\beta_{\max} = 2 \sin \beta_{\max}.$$

To do this, we will construct graphs of the function $y = \sin 5\beta$ and $y = 2 \sin \beta$ and from the intersection of these graphs (Fig. 2) we will find

$$\beta_{\max} \approx 0,42 \text{ рад} \approx 23,9^\circ.$$

This means that at $-23,9^\circ < \beta < 23,9^\circ$ the toy returns to its initial position.

Problem 2. A cube of mass $m$ resting on the main surface, connected to the wall by a spring, is hit from the right by a second cube of mass $M$ (Fig. 3). An absolutely elastic impact occurs, after which the first cube begins to vibrate. What part of the flask period will pass until the moment

$$Mv_0 = mv_1 + Mv_2, \quad \frac{Mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{Mv_2^2}{2},$$

where

$$v_1 = v_0 \frac{2}{1 + \gamma}, \quad v_2 = v_0 \frac{1 - \gamma}{1 + \gamma}.$$

⟦folio 54⟧

After the collision, the second cube will move uniformly, and its coordinate will change over time according to the law

$$x_2 = v_2 t = v_0 \frac{1-\gamma}{1+\gamma} t.$$

The very first cube begins to oscillate according to the law

$$x_1 = x_m \sin \omega t.$$

Harmonic frequency

$$\omega = \sqrt{\frac{k}{m}},$$

where $k$ is the spring stiffness. We find the amplitude of oscillations $x_m$ from the law of conservation of energy:

$$\frac{m v_1^2}{2} = \frac{k x_m^2}{2} \Rightarrow x_m = \frac{v_1}{\omega} = \frac{2 v_0}{(1+\gamma) \omega}.$$

Thus,

$$x_1 = \frac{2 v_0}{(1+\gamma) \omega} \sin \omega t.$$

The second collision of the cubes will occur under the condition $x_1 = x_2$, i.e.

$$\frac{2 v_0}{(1+\gamma) \omega} \sin \omega t = v_0 \frac{1-\gamma}{1+\gamma} t.$$

From here

$$2 \sin \omega t = (1-\gamma) \omega t,$$

or

$$2 \sin \left(2 \pi \frac{t}{T}\right) = (1-\gamma) 2 \pi \frac{t}{T},$$

where $T = 2 \pi/\omega$ is the oscillation period, $t/T$ is the desired frequency of the period.

Let's denote it by $\pi t/T = z$. Then the previous equation takes the form

$$\sin 2z = (1-\gamma) z.$$

For $\gamma = 1/2$ we get

$$\sin 2z = \frac{z}{2}.$$

Let us draw the graphs of the functions $y = \sin 2z$ and $y = z/2$ (Fig. 4) and from their intersection we find

$$z \approx 1,24$$ glad, $\pi \frac{t}{T} \approx 1,24$, $\frac{t}{T} \approx 0,39$.

If $m \ll M$, i.e. $\gamma \to 0$, then we obtain the equation

$$\sin 2z = z.$$

His solution will be (see Fig. 4)

$$z \approx 0,95$$ glad, or $\frac{t}{T} \approx 0,30$.

A second collision of the cubes will not occur if their coordinates no longer coincide, that is, speaking in the language of graphs, if the straight line expressing the graph of the coordinates of the second cube versus time does not intersect the sinusoid a second time. This corresponds to all straight lines emerging from the point $O$ and the location of the shielded area between the lines $I$ and $II$. Line $I$ corresponds to case $m/M \to \infty$ (the mass of the incident cube is very small). It remains to find $\gamma$ for the line $II$—the tangent to the sinusoid. As can be seen from figure 4, this line corresponds to the value $z \approx 2,24$ rad. From here

$$\gamma = 1 - \frac{\sin 2z}{z} \approx 1,44.$$

So, in order for a second collision to not occur, the condition must be fulfilled

$$1,44 < \gamma < \infty.$$

Problem 3. The piston pump captures a certain volume of air with each swing. When pumping air out of the vessel, the pump performed four swings. The initial pressure inside the vessel was equal to atmospheric pressure $p_0$. Then this pump began to apply air into the vessel from the atmosphere and also performed four swings. At the same time, the pressure in the vessel became

⟦folio 55⟧

2 times more than atmospheric. Find the correspondence between the working volume of the pump and the volume of the vessel.

When pumping air from the vessel after the first pumping, the pressure in the vessel will become equal

$$p_1 = p_0 \frac{V}{V + V_0},$$

where $V$ is the volume of the vessel, $V_0$ is the working volume of the piston pump; after the second swing -

$$p_2 = p_1 \frac{V}{V + V_0} = p_0 \left( \frac{V}{V + V_0} \right)^2$$

etc. After four swings, the pressure in the vessel will be

$$p' = p_0 \left( \frac{V}{V + V_0} \right)^4.$$

When air is pumped into a vessel after four swings, pressure is established in the vessel

$$p = p' + \frac{4p_0V_0}{V} = p_0 \left( \left( \frac{V}{V + V_0} \right)^4 + 4 \frac{V_0}{V} \right) = p_0 \left( \left( \frac{1}{1 + V_0/V} \right)^4 + 4 \frac{V_0}{V} \right).$$

On the other hand, according to the conditions of the problem $p = 2p_0$.

We get the equation

$$2p_0 = p_0 \left( \frac{1}{1 + V_0/V} \right)^4 + 4 \frac{V_0}{V}),$$

or

$$2 - 4x = \left( \frac{1}{1 + x} \right)^4,$$

where $x = V_0/V$. Let's build graphs of functions (Fig. 5)

$$y = 2 - 4x \text{ и } y = \frac{1}{(1 + x)^4}$$

and from their intersection we find

$$x \approx 0,44, \text{ т. е. } \frac{V_0}{V} \approx 0,44.$$

Problem 4. To determine the capacitance of the unknown capacitor $C_x$, the circuit shown in figure 6 was assembled. The capacitance of capacitor $C_o$ is known. Capacitor $C_o$ using key $K_1$ using key $K_2$ it turns out to be $U_4$. Since the current through the milliampere is odd, it is easy to establish that

$$\frac{U_2}{R_2} = \frac{U_4}{R_1},$$

where $U_2$ is the voltage drop across resistance $R_2$. On the other side,

$$U_2 = U_0 - U_4.$$

⟦folio 56⟧

From here

$$\frac{U_4}{U_0} = \frac{R_1}{R_1 + R_2}.$$

Initially, the capacitor $C_x$ had a charge $q_x = C_x U_0$. At the first inclination of $K_1$ to position 3, this charge is distributed between $C_x$ and $C_0$, and the voltage on the common capacitors becomes equal

$$U_1 = \frac{q_x}{C_x + C_0} = \frac{C_x U_0}{C_x + C_0}.$$

After tilting $K_2$ to position 5, capacitor $C_0$ is completely discharged, and a charge remains on capacitor $C_x$

$$q_1 = C_x U_1 = \frac{C_x^2 U_0}{C_x + C_0}.$$

After the second tilt of $K_2$ to position 4, the voltage on the capacitors turns out to be

$$U_2 = \frac{q_1}{C_x + C_0} = U_0 \left( \frac{C_x}{C_x + C_0} \right)^2,$$

and after four inclinations -

$$U_4 = U_0 \left( \frac{C_x}{C_x + C_0} \right)^4.$$

Let us denote $\beta = C_x / (C_x + C_0)$, then

$$\frac{U_4}{U_0} = \beta^4.$$

After swapping the resistors and repeating the whole process, you can write an equation similar to equations (1) and (2):

$$\frac{U_3}{U_0} = \frac{R_2}{R_1 + R_2},$$

$$\frac{U_3}{U_0} = \beta^3,$$

where $U_3$ is the voltage on capacitor $C_x$ after three inversions $K_2$. From equations (1) and (3) we obtain

$$\frac{U_4}{U_0} + \frac{U_3}{U_0} = \frac{R_1}{R_1 + R_2} + \frac{R_2}{R_1 + R_2} = 1,$$

Means,

$$\beta^4 + \beta^3 = 1.$$

Let's plot the function (Fig. 7)

$$y = \beta^4 \text{ и } y = 1 - \beta^3$$

and from their intersection we find

$$\beta \approx 0,82.$$

Then finally

$$C_x = \frac{\beta}{1 - \beta} C_0 \approx \frac{0,82}{1 - 0,82} \times 100 \text{ мкФ} \approx 450 \text{ мкФ}.$$

Exercises

1. A thread wrapped around a stationary disk of radius $r$ forms a semicircle (Fig. 8). One end of the thread is fixed at point $A$, a weight is attached to the second end of the thread, which is held at point $B$ (points $A$ and $B$ are on the same vertical). At some points the weight is released in contact with the disc when the weight reaches its highest position? The third one is neglectful.

2. A doxa lies on a fixed circular half-silidron of radius $R$ (Fig. 9). Doxy thickness $h$, length $2l$, $R = h$. Up to what maximum angle ($\varphi_{\pi p}$) can the doxa be disconnected from the horizontal position so that it returns to its initial state? The friction is high. Assuming that the half-silider is on an infinite horizontal plane and that $2l/R = 4$, find out whether the doxa returns to its initial state at the maximum deviation from the horizontal position.
