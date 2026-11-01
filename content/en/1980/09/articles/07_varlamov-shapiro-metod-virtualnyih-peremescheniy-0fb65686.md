---
id: 1980-9-varlamov-shapiro-metod-virtualnyih-peremescheniy-0fb65686
issue: kvant_1980_9
year: 1980
number: "9"
title: Virtual movement method
authors:
  - Варламов А. А.
  - Шапиро А. И.
rubric: osnovnye-stati
page_first: 11
page_last: 15
page_labels: 9-13
tag: YBF1
lang: en
source: kvant_digital
extraction: vision
content_sha256: c96258cfceba0b56b597a1cc3120f3261f219714c9b66c2a820dcb9b71190bfc
prompt_sha256: draft-1
translated_from: content/ru/1980/09/articles/07_varlamov-shapiro-metod-virtualnyih-peremescheniy-0fb65686.md
source_content_sha256: c4829fef5e1acb0ff5f8253eb8d6e44ed3316b8cbe8a766b6e4ab1a8c7278f60
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

Virtual movement method
(about one consequence of the law of conservation of energy)

In 1717, Johann Bernoulli introduced a new method for solving static problems - the method of virtual displacements. This method is simple and elegant; it allows one to calculate the equilibrium conditions of complex mechanical systems without resorting to cumbersome calculations; with its help it is possible to solve both hydrostatic problems and electrostatic problems. It is based on the property of bond reaction forces arising from the law of conservation of energy: with a small deviation of the system from the equilibrium position, the total work of the bond reaction forces is zero.

In this article, using the example of specific problems, we will try to show the reader what beautiful results this consequence of the law of conservation of energy leads to.

Problem 1
Electric charge Q is uniformly distributed over a thin, absolutely rigid metal sphere of radius R. What force F acts on a unit surface area from the rest of the charge?

By condition, the sphere is assumed to be completely rigid, so its actual radius R cannot change. However, let’s imagine that as a result of the repulsion of the same electric charges of the sphere, the amount increased slightly - by an infinitesimal amount δR. In other words, imagine that each point of the sphere has made an infinitesimal movement δR in the direction perpendicular to the surface. We emphasize that the change in radius δR is purely imaginary; however, with the help of this imaginary, mental movement of the points of the sphere, we were able to solve the problem very simply, and at the same time, δR, of course, will not be included in the answer.

What happens when the radius of the sphere increases by δR? A charged sphere has the property of a capacitor - it retains the charge imparted to it. The surface potential of a sphere is related to the charge of the sphere by the correspondence φ = Q/4πε₀εR. On the other hand, according to the definition of capacitance φ = Q/C. Therefore, the capacity of the charged sphere is C = 4πε₀εR. The energy of such a capacitor is W = Q²/2C = Q²/8πε₀εR. As the radius of the sphere increases, the energy decreases: W′ = Q²/8πε₀ε(R + δR).

Thus, the energy of the capacitor sphere, as a result of increasing the radius of the sphere by δR values, decreases by δR values.

ΔW = W − W′ = Q² · δR / 8πε₀εR(R + δR).

According to the law of conservation of energy, this change in energy is equal to the total work A of the electrostatic repulsion force acting between the individual elements of the charged surface. If F is the force acting per unit area of ​​the sphere, then A = 4πR²F δR. Hence,

4πR²F · δR = Q² · δR / 8πε₀εR(R + δR).

Considering that δR ≤ R, from this equality we find F = Q² / 32π²ε₀εR⁴.

The idea of ​​making an infinite small mental movement, which is called virtual, used in the process of solving the problem lies at the basis of the method of virtual movements.

⟦folio 10⟧

Typically, the equilibrium conditions of a system in statics are written as the sum of all forces and the sum of the moments of all forces applied to each point of the system being equal to zero. At the same time, the connections existing in the system (supports, rods, threads, etc.) characterize the error that occurs in them by reaction forces. The need to take into account reaction forces when writing equilibrium conditions in the case of systems consisting of several bodies leads to cumbersome calculations. However, it is possible to avoid considering these forces altogether.

An important property of reaction forces is the fact that their total work for a small deviation of the system from the equilibrium position is equal to zero. This property of reaction forces is associated with the law of conservation of energy: since maintaining connections in an equilibrium position does not require energy consumption (reaction forces are applied, but there is no understanding of the points of the system), then as a result of the action of connections there is no gain or expenditure of work. Thus, we come to the statement that for any small deviation of the system from equilibrium that occurs, the total work done by the reaction forces is zero.

But in addition to the forces of reaction to the points of the action system and external forces. What is their work with the same small displacement from the equilibrium position? Since the system of the first one ends in a similar way, for any movement of the system it is necessary to do some positive work. In principle, this work can be performed by external forces and bond reaction forces. But, as we already know, the total work done by all reaction forces is zero. Therefore, in order for the system to leave the state of equilibrium, the total work of external forces for any displacement that occurs must be positive. Consequently, we can formulate the conditions for the impossibility of movement, that is, the conditions of equilibrium, as the requirement that the total work of external forces be non-positive for any virtual displacement that occurs: $\Delta A \leq 0$.

Let us assume that with displacements $\vec{\Delta r}_1, \vec{\Delta r}_2, \dots, \vec{\Delta r}_N$ the sum of the work of external forces turns out to be $\Delta A_1$. What happens if the system makes movements $-\vec{\Delta r}_1, -\vec{\Delta r}_2, \dots, -\vec{\Delta r}_N$? These movements arise in the same way as the first ones; however, the work of external forces will now change sign: $\Delta A_2 = -\Delta A_1$. (In the problem with a sphere, such a procedure would correspond not to a stretch, but to a sloping sphere.) Reasoning similarly to the previous case, we will come to the conclusion that now the equilibrium conditions have the form $\Delta A_1 \geq 0$, that is, the work of external forces must be non-negative. The only way to “reconcile” these two contradictory conditions is to require the exact equality to zero of the total work of external forces for any virtual displacement of the system from the equilibrium position: $\Delta A = 0$.

In this form, we will use the principle of virtual movements in further problem solving. It is usually formulated as follows:

For the equilibrium of any mechanical system with ideal connections, it is necessary and sufficient that the sum of the elements of work acting on the system of forces for any virtual displacement that occurs is equal to zero.

The significance of the principle of virtual displacements lies, first of all, in the fact that in order to find equilibrium conditions using this principle, there is no need to consider a large number of reaction forces of connections that ensure the equilibrium of complex systems. There is no need to delve into the mechanism for making these connections at all. It is enough to have the necessary displacements that allow the established constraints, calculate the corresponding total work of external forces and equate it to zero.

A special case of the principle of virtual movements is

⟦folio 11⟧

Let's imagine that the dream application point $\vec{F}$ moves vertically downward to a distance $\delta H$. In this case, the load $m$ will move upward by a distance $\delta h = \frac{1}{4} \delta H$ (this result is very similar to figure 1). According to the principle of virtual movements
$$|\vec{F}| \delta H = |\vec{mg}| \delta h = (4 |\vec{F}| - |\vec{mg}|) \delta h = 0.$$
From here
$$|\vec{F}| = |\vec{mg}| / 4.$$
(When solving this problem, we did not write down the conditions for the equality of forces in the equilibrium position; this demonstrates the disorderly superiority of the method of virtual displacements.)

Problem 3
Box K (figure 2) contains a transmission mechanism of unknown design. When turning handle P vertically, screw B rises smoothly. With one full revolution (turn radius $r$), the screw moves upward a distance $h$.
A mass load $m$ is placed on the screw. What number must be applied to the handle to keep the system with the load in balance?
Let us assume that the system is in equilibrium when a force equal in absolute value to $f$ is applied to the handle.
Let's imagine that the handle makes an infinitesimal rotation through an angle $\delta \varphi$. The work done by force $f$ is equal to
$$\delta A_1 = f \frac{2\pi r}{2\pi} \delta \varphi = fr \cdot \delta \varphi.$$
The load $m$ rises to a height $\delta h = \frac{h}{2\pi} \cdot \delta \varphi$. Force mg does work
$$\delta A_2 = -mg \frac{h \cdot \delta \varphi}{2\pi}.$$
According to the principle of virtual movements
$$\delta A_1 + \delta A_2 = fr \cdot \delta \varphi - mg \frac{h \cdot \delta \varphi}{2\pi} =$$
$$= (fr - mg \frac{h}{2\pi}) \delta \varphi = 0,$$

⟦folio 12⟧

Fig. 3.

where do we find $f$:

$$f = mg \frac{h}{2\pi r}.$$

(The problem in this formulation cannot be solved at all by general statistical methods, since nothing is known about the transmission mechanism hidden in the box.)

Problem 4

A loop of cymbal heavy chain of mass $m$ is placed on the main straight circular cone, the height of which is $H$, and the radius of the base is $R$ (figure 3). The chain sways in a horizontal plane. Find the chain tension $T$.

Let the radius of the circle formed by the chain be $r$. Let us perform a virtual movement of the chain as a vertical whole downward to a distance $\delta H$. The decrease in the potential energy of the chain is equal to $mg\delta H$. The radius of the chain with such movement increased by $\delta r$. The increase in the radius of the chain and its mixing are related by the relation $\delta r/\delta H = R/H$.

The work of tension forces $T$ during the considered virtual movement of the chain (virtual work) is equal to

$$\delta A_1 = (2\pi(r + \delta r) - 2\pi r)T = 2\pi \cdot \delta r T.$$

The virtual work done by gravity is equal to

$$\delta A_2 = -mg \cdot \delta H.$$

From the condition

$$\delta A_1 + \delta A_2 = 2\pi \cdot \delta r \cdot T - mg \cdot \delta H = 0$$

we find

$$T = \frac{mg}{2\pi} \frac{\delta H}{\delta r} = \frac{mgH}{2\pi R}.$$

Problem 5

There is a chain containing $n$ identical weightless links, hinged (figure 4). Neglecting friction, determine what tension the thread connecting points 1 and 2 should withstand if a mass $m$ is suspended from the chain.

Let's imagine that the load $m$ has dropped to a distance $\delta h$. From the messages of the symmetrina it is clear that in this case the diagonal of each of the links lengthened by $\delta h/n$. Therefore, the virtual extension of the thread between points 1 and 2, equal to the virtual displacement of point 2, is also equal to $\delta h/n$.

Let us write down the condition for the virtual work to be equal to zero:

$$T \cdot \delta h/n - mg \cdot \delta h = 0$$

(T is the tension force of the thread). From here

$$T = nmg.$$

In the examples discussed above, we used the virtual displacement method to solve mechanics problems. However, as we have already said, the field of applicability of this city method is wider. For example, the formula for excess pressure inside a spherical bubble is

$$p = \frac{4\sigma}{r}$$ - can be easily deduced

⟦folio 13⟧

using the virtual displacement method.

Let a soap bubble of radius $r$ be in equilibrium. Let's give its radius a virtual increment $\delta r$. Then the virtual work of the excess pressure forces is equal to $\delta A_1 = F_{n36} \cdot \delta r = 4\pi r^2 p_{n36} \delta r$ (the force $F_{n36}$ of the excess pressure is directed normal to the surface of the bubble). the virtual work of surface tension forces is equal to the change in surface energy:

$$\delta A_2 = 2\sigma \cdot 4\pi (r^2 - (r + \delta r)^2) = -16\pi \sigma r \delta r$$

(a soap bubble has two surfaces).

According to the principle of virtual movements

$$\delta A_1 + \delta A_2 = 4\pi r^2 p_{n36} \delta r - 16\pi \sigma r \delta r = 0.$$

From here

$$p_{n36} = \frac{4\sigma}{r}.$$

Problem 6

Let's use the method of virtual displacements to solve the problem of a power machine.

A liquid with dielectric constant $e$ is poured into a larger container. Two vertical parallel plates touch the surface of the liquid (figure 5). Distance between plates $d$. The plates are connected to a source with a potential difference $U$. What will be the height of the $h$ column between the plates after equilibrium is established?

Let us consider the system in an equilibrium position. Let the size of the plate be $a \times b$. Let's make a virtual change in the height of the liquid column by $\delta h$. Then the work of gravity forces is $\delta A_1 = -mg \cdot \delta h/2 = -\rho g hdb \cdot \delta h/2$.

(We neglect the change in the mass of the liquid column due to the “drawing” of liquid from the vessel into the space between the plates, since the corresponding work of gravity to raise this mass to a height $\delta h$ is proportional to $(\delta h)^2$.)

The work of the electric field forces is equal to the change in the energy of the capacitor formed by the plates with a virtual change in the column height by $\delta h$:

$$\delta A_2 = \delta E = \delta \frac{CU^2}{2} = \frac{U^2}{2} \cdot \delta C$$

(since $U = \text{const.}$).

Considering the filling and the independent part of the capacitor as two parallel-connected capacitors, for the total capacitance we obtain the expression

$$C = \frac{S_1}{4\pi d} + \frac{\varepsilon S_2}{4\pi d} = \frac{(a-h)b}{4\pi d} + \frac{\varepsilon hb}{4\pi d} = \frac{ab}{4\pi d} + \frac{(\varepsilon-1)hb}{4\pi d}.$$

Hence,

$$\delta C = \frac{(\varepsilon-1)b \cdot \delta h}{4\pi d}.$$

Thus,

$$\delta A_2 = \frac{U^2(\varepsilon-1)b \cdot \delta h}{8\pi d}.$$

The principle of virtual movements gives

$$\frac{U^2(\varepsilon-1)b \cdot \delta h}{8\pi d} - \rho g hbd \frac{\delta h}{2} = 0.$$

From here

$$h = \frac{U^2(\varepsilon-1)}{4\pi gd^2}.$$

In conclusion, so that you can check how well you have mastered the virtual movement method, we suggest you solve two problems:

(For the end see p. 26)
