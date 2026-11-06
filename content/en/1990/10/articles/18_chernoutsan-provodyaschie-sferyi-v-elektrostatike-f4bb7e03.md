---
id: 1990-10-chernoutsan-provodyaschie-sferyi-v-elektrostatike-f4bb7e03
issue: kvant_1990_10
year: 1990
number: "10"
title: Conducting spheres in electrostatics
authors:
  - Черноуцан А. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 58
page_labels: 52-56
lang: en
source: kvant_digital
extraction: vision
content_sha256: 43b155fe1e22548e58379b8665317e94eeef6c5451b93dcbca1f363fc01e3f98
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/18_chernoutsan-provodyaschie-sferyi-v-elektrostatike-f4bb7e03.md
source_content_sha256: c5f64315426903d3706e5b98d8221bd0b8e391d99ec8c3ff3e00dd62db64ce1f
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 52⟧

---
running_head:
folio:
---

Sphere wires in electrostatics

Candidate of Physical and Mathematical Sciences
A. CHERNOUTSAN

The electrostatics of conductors occupies an insignificant place in the school physics course, and for many students, behind somewhat simple problems, the beauty and non-trivial nature of this topic remain forever hidden.

At first glance, the behavior of conductors in an electrostatic field is simple and unambiguous. And indeed. There are always free charges in any conductor. Under the influence of an electrostatic field, when free charges move into motion, an electric current arises. In the case of electrostatics - and this is what we will be interested in - the charges on the conductor are in equilibrium. This means that the field voltage at all points of the conductor is zero, and the potential of all points of the conductor is the same (it is called the potential of the conductor).

From the condition of electrostatic equilibrium it also follows that in equilibrium only the surface of the conductor is charged, and there are no charges in the volume of the conductor (meaning uncompensated charges), that the lines of force of the electrostatic field are perpendicular to the surface of the conductor, and some other properties of conductors.

However, the simplicity of all these statements is deceptive. Think about it: they say nothing about exactly how the charges are distributed over the surface of the conductor. It is only known that the charges must be distributed so that the field voltage in the conductor is zero. It is not the equilibrium arrangement of charges itself that is determined, but the “end result” of such an arrangement.

The need to analyze “by the end result” (so effective in economics) creates serious difficulties in studying and understanding the electrostatics of conductors. True, schoolchildren are usually safely saved from these problems by introducing them mainly to problems where the location of charges is known in advance. But... one step to the side (for example, on an oral entrance exam) - and the applicant often gets into trouble.

To help you avoid such, as they now say, “emergency” situations, when analyzing all tasks - both simple and more complex - special attention will be paid to the substantiation of all statements and answers to questions that arise. For this purpose, some problems, in addition to the “Solution” section, contain an additional section -

⟦folio 53⟧

---
running_head:
folio:
---

One of the goals of this section is to summarize the results obtained and show the possibilities of their application.

Problem 1. A metal ball of radius $R$ is charged $q$. Find the potential of the ball, as well as the voltage and potential of the electric field at all points in space.

Solution. In this problem, the question does not arise about how exactly the charge is distributed on the surface of the ball - from the reports it is symmetrical that it is distributed uniformly with the surface with density $\sigma = q/(4\pi R^2)$.

Let's start by calculating the field voltage. Inside the conducting ball, the voltage is zero, and in external space it is the same as that of the field of an exact charge placed at the center of the ball:

at $r \leqslant R$ $E = 0$,

at $r > R$ $E = \frac{1}{4\pi \varepsilon_0} \frac{q}{r^2}$. (1)

Statement (1) uses estimator broadly. (And not only for the electric field, but also for the gravitational field. Remember, for example: bodies gravitate to the Earth as if all its mass is concentrated in its center.) Qualitative errors can be given in the language of force lines: since the pictures of the radial diverging force lines for the fields of the ball and the exact charge coincide, then the fields themselves should be the same. A rigorous proof can be found in the article “Lines of Field and Gauss’s Theorem” in the third issue of Kvanat for this year.

Since the voltage of the ball's field in the entire external space - from $R$ to infinity - is the same as that of the field of the exact charge, and at infinity the potential of the general fields is taken equal to zero, then the potential of the ball's field coincides with the potential of the field of the exact charge:

at $r > R$ $\varphi = \frac{1}{4\pi \varepsilon_0} \frac{q}{r}$. (2)

Putting $r = R$, we obtain the potential on the surface of the ball, i.e., the potential of the ball itself (the potential of all its points is the same):

at $r \leqslant R$ $\varphi_{\text{шар}} = \frac{1}{4\pi \varepsilon_0} \frac{q}{R}$. (3)

Everything that we said about the voltage and potential of the ball’s field is graphically depicted in figure 1. Note that this answer is also suitable for a thin conducting spherical shell (think about why).

Discussion 1) Sometimes schoolchildren have the following question: “If there is no field inside the ball, then why is the field potential in this area not equal to zero?” The fact is that we have already taken the fields at infinity to be the user. In order not to potentially lose a point on the ball, it is necessary to calculate the work of the field to transfer a unit positive charge from this point to infinity; with such a transfer we must pass through the entire external region - from $R$ to infinity, and in this region the field voltage is no longer equal to zero.

2) When calculating the potential of the ball, we used expression (2) for the potential of the outer region. However, you can go the other way and calculate the potential at the center of the ball using the superposition principle. Divide the surface of the ball into small sections - exact charges $\Delta q_i$, find the contribution of each section and sum it up:

$$\varphi_{\text{шар}} = \sum_i \frac{1}{4\pi \varepsilon_0} \frac{\Delta q_i}{R} = \frac{1}{4\pi \varepsilon_0} \frac{\sum_i \Delta q_i}{R} = \frac{1}{4\pi \varepsilon_0} \frac{q}{R}.$$

Here we used a replacement property of the center of the ball: that it lies at the same distance $R$ from all points of the surface.

⟦folio 54⟧

---
running_head:
folio:
---

3) The field voltage reaches its maximum value at the surface of the ball. Let's express it through the potential of the ball:

$$E(R) = \frac{1}{4\pi\varepsilon_0} \frac{q}{R^2} = \frac{\varphi_m}{R}.$$

It can be seen that at the same potential the field voltage is greater at the surface of the small ball. (This means, for example, that near a small ball, air breakdown occurs at a lower potential.)

In addition, the field voltage at the surface of the conductor depends only on the surface charge density $\sigma$:

$$E(R) = \frac{1}{\varepsilon_0} \frac{q}{4\pi R^2} = \frac{\sigma}{\varepsilon_0}.$$

This correspondence is valid for a conductor of any shape - the number of power lines starting at a certain section of conductivity is proportional to the charge of this section. (In particular, it holds for the field of a flat capacitor. Since this field is created by two plates, the field of one plate, i.e., a uniformly charged plane, is equal to $\sigma/(2\varepsilon_0)$.)

4) Note that the potential of the ball turns out to be proportional to its charge (formula (3)). The same statement is true for a single conductor of arbitrary shape:

$$\varphi \sim q, \quad \varphi = \frac{1}{C} q,$$

where $C$ is the electrical capacity (capacitance) of the conductor, which depends on the shape and size of the conductor. (The capacity of a sphere, for example, is $C = 4\pi\varepsilon_0R$.)

To prove the proportionality of $\varphi$ and $q$, we use the uniqueness theorem - a very important theorem, truly a “magic wand” for a power plant. It states that only one equilibrium distribution of charges on conductors is essential, i.e., a distribution in which $\vec{E} = 0$ is inside all conductors (provided that either the charges of all conductors or their potentials are given). (It’s not for nothing that free charges almost instantly find their equilibrium position - after all, they are not faced with a painful choice!)

Let the only conductor, when a charge $q$ is given to it, acquires a potential $\varphi$. Let us additionally apply the same charge $q$ to this conductor and make sure that the potential of the conductor doubles. If the second portion of the charge is distributed over the surface in exactly the same way as the first, then the voltage inside the conductor remains equal to zero (the contribution of each portion is zero). This is exactly how it will be compared - after all, there is only a “good” distribution! This means that a new portion of charge creates the same potential $\varphi$ on the conductor, and the resulting potential will be equal to $2\varphi$.

Problem 2. Two distant other conducting balls, whose radii are $R_1$ and $R_2$, carry charges $q_1$ and $q_2$, respectively. What will be the potentials and charges of the balls after they are connected by wire?

Solution. After connection, the two balls together with the wiring form a single conductor. Therefore, in a state of equilibrium, the potentials of the balls must be equal to each other:

$$\varphi'_1 = \varphi'_2 = \varphi'$$, or $$\frac{1}{4\pi\varepsilon_0} \frac{q'_1}{R_1} = \frac{1}{4\pi\varepsilon_0} \frac{q'_2}{R_2},$$

that is, the charges of the balls are proportional to their radii (the charges and potentials of the balls after connection are offset by the strokes). Since the charge only moves along the wiring from ball to ball, but does not enter the system from the outside and does not leave it, the law of conservation of charge is satisfied:

$$q_1 + q_2 = q'_1 + q'_2$$

(we neglect the charge on the wiring). Solving the resulting equations, we find

$$q'_1 = (q_1 + q_2) \frac{R_1}{R_1 + R_2}, q'_2 = (q_1 + q_2) \frac{R_2}{R_1 + R_2},$$

$$\varphi' = \frac{1}{4\pi\varepsilon_0} \frac{q_1 + q_2}{R_1 + R_2}.$$

Discussion 1) The solution to the problem of connecting by wiring two conductors of arbitrary shape remote from each other, having capacitances $C_1$ and $C_2$, looks exactly the same:

$$q'_1 = (q_1 + q_2) \frac{C_1}{C_1 + C_2}, q'_2 = (q_1 + q_2) \frac{C_2}{C_1 + C_2},$$

$$\varphi' = \frac{q_1 + q_2}{C_1 + C_2}.$$

It can be seen that the capacitance of an isolated system of two conductors distant from each other, connected by wiring, is equal to $C_1 + C_2$. If $C_1 \ll C_2$, then $q'_1 \ll q'_2$, i.e. on the conductor of a small

⟦folio 55⟧

---
running_head:
folio:
---

capacitance (for example, on a wire) there is a negligible charge. On the contrary, the charge and potential of a conductor with a very large capacitance almost does not change when connected. So, when they say: “connected to a conductor of a given potential,” they mean a conductor of very high capacity. In particular, the word “grounding” means a connection to a conductor of very large capacity (ground) of zero potential; after grounding $\varphi' = 0$.

2) Note that although a larger charge ($q'_1/q'_2 = R_1/R_2$) is concentrated on a ball of large radius, the surface charge density is larger, on the contrary, on a small ball ($\sigma'_1/\sigma'_2 = R_2/R_1$). This illustrates the well-known fact that the surface charge density (and therefore the direction) is large in those areas of the conductor where the surface curvature is large (for example, at the tip).

Problem 3. A conducting ball with radius $R_1$ was surrounded by thin conductor with a large radius $R_2$. The charge of the ball is $q_1$, the charge of the shell is $q_2$. Find the potentials of the conductors, as well as the directionality and potential at all points in space. How will the potential of the ball change if the shell is grounded?

Solution. In accordance with the principle of superposition, the directionality (and potential) at each point in space can be calculated as the sum of the directions (potentials) created at this point by the ball and the shell. Let's look again at figure 1: for both directionality and potential, the answer depends on whether we are inside or outside the charged sphere. If, for example, the point is located between the ball and the shell (Fig. 2), then we obtain

$$E(r) = \frac{1}{4\pi\varepsilon_0} \frac{q_1}{r^2} + 0,$$

$$\varphi(r) = \frac{1}{4\pi\varepsilon_0} \frac{q_1}{r} + \frac{1}{4\pi\varepsilon_0} \frac{q_2}{R_2}$$

($R_1 < r < R_2$).

In these equalities, the first term characterizes the field of the ball, the second - the field of the shell. For $r = R_1$ we get the answer for the ball potential, for $r = R_2$ for the shell potential:

$$\varphi_{\text{ш}} = \frac{1}{4\pi\varepsilon_0} \left( \frac{q_1}{R_1} + \frac{q_2}{R_2} \right),$$

$$\varphi_{\text{о6}} = \frac{1}{4\pi\varepsilon_0} \frac{q_1 + q_2}{R_2}.$$

At $r < R_1$ the potential is constant and equal to the potential of the ball, and the directionality is zero. For $r > R_2$ we obtain the field of the exact charge ($q_1 + q_2$):

$$E(r) = \frac{1}{4\pi\varepsilon_0} \frac{q_1 + q_2}{r^2},$$

$$\varphi(r) = \frac{1}{4\pi\varepsilon_0} \frac{q_1 + q_2}{r}.$$

After the shell is grounded, its potential becomes zero, where the shell shard is located:

$$q'_2 = -q_1$$

and the new ball potential:

$$\varphi'_{\text{ш}} = \frac{1}{4\pi\varepsilon_0} q_1 \left( \frac{1}{R_1} - \frac{1}{R_2} \right).$$

Discussion. When the shell was grounded, the total charge of the system turned out to be zero ($q_1 = q, q_2 = -q$). Such a system is called a spherical capacitor. Since the potential of the external cloud is zero, the direction to the capacitor is equal to the potential of the internal one, positive charging of the cloud (ball). From here we find the capacitance of the spherical capacitor:

$$C = 4\pi\varepsilon_0 \frac{R_1 R_2}{R_2 - R_1}.$$

If the outer shell increases indefinitely ($R_2 \rightarrow \infty$), then the capacitance of the spherical capacitor turns into the capacitance of a solitary

⟦folio 56⟧

---
running_head:
folio:
---

th ball, and the direction on the capacitor is to the potential of the solitary ball, which have already been mentioned. In the same way, any single conductor with capacity $C$ can be considered the plate of a capacitor with capacitance $C$, the second plate of which is an infinite remote closed shell. Why is this necessary?
Of course, to use the given formulas for capacitors in problems with single conductors. For example, for the energy of a solitary conductor we immediately obtain the formulas $W=q\varphi/2=C\varphi^2/2=q^2/(2C)$.

Problem 4. Point zagad $q$ is located at a distance $L$ from the center of a thin conducting sphere of radius $R$ carrying zagad $Q$. Find the potential of the conducting sphere. The distance is the case of $L>R$ and $L<R$.

Solution. In this problem there is no spherical symmetry, and therefore the distribution of riddles on the sphere is unknown. A complete solution to the problem of the electric field in all space is beyond the scope of this article (it can be found, for example, by the method of power station images - see «Kvant», 1987, No. 3, p. 39). Surprisingly, thanks to the geometric properties of the sphere, its potential can already be found without complex calculations.

Let us first distance the case $L>R$ (Fig. 3). Although there is no shell inside

Fig. 3.

conductor, directed 止痛 in the cavity (not containing riddles!) will be equal to zero and the potential of all internal points will be the same. We will look for the potential of the center. It is created by the exact riddle $q$ and riddle $Q$, distributed - no one knows how! — along the surface of the sphere. However, due to the fact that the distance to all points along

Fig. 4.

surfaces are the same, the result of calculating the potential does not depend on the distribution of the riddle over the sphere:

$$\varphi_{o6} = \frac{1}{4\pi\varepsilon_0} \frac{q}{L} + \sum_i \frac{1}{4\pi\varepsilon_0} \frac{\Delta Q_i}{R} = \frac{1}{4\pi\varepsilon_0} \frac{q}{L} + \frac{1}{4\pi\varepsilon_0} \frac{Q}{R}.$$

(To avoid misunderstandings, it is symmetry that there is only one distribution of riddles in which all points inside the sphere will have the same potential as the center of the sphere.)

Let us now distance the case $L<R$ (Fig. 4). With this distribution of the riddle $q$ directionally 止痛 in the internal cavity is not zero. This means that the potential of the center of the sphere, for which the expression found above remains true, is not equal to the themeric potential of the conducting shell. But another advantage will help us out: it turns out that the field is in the outer region ($r>R$) does not depend on the position of the riddle $q$ and coincides with the field of an imaginary riddle ($q+Q$), placed at the center of the sphere. For the shell potential we obtain:

$$\varphi_{o6} = \frac{1}{4\pi\varepsilon_0} \frac{q+Q}{R}.$$

How to prove that the field in the outer region does not depend on the position of the riddle $q$? Here again we have to use theory to help us. Let's invent such a distribution of riddles over the inner and outer surfaces of the shell, in which the field in the conductor will be equal to zero. Let's start with the inner surface. Let's distribute the riddle on it - $q$ the way it would be distributed in an imaginary spherical cavity created in space, completely filled with a conductor (Fig. 5). It is clear that with this
