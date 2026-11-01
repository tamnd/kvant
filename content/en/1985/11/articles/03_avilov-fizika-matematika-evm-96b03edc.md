---
id: 1985-11-avilov-fizika-matematika-evm-96b03edc
issue: kvant_1985_11
year: 1985
number: "11"
title: Physics + Mathematics + Computers
authors:
  - Авилов В. В.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2-6
tag: HA75
lang: en
source: kvant_digital
extraction: vision
content_sha256: 86d59584d721d5a8b138df195c13cceefc8d41e8fb939dee5000651f0096c162
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/03_avilov-fizika-matematika-evm-96b03edc.md
source_content_sha256: 53a844f697ca4c482bcaa4bde2d88500d37f17c54289484be7baaa8764af5cc2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Physics Mathematics Computers

Candidate of Physical and Mathematical Sciences
V. V. AVILOV

This article will focus on computational physics, a new science born at the intersection of physics and applied mathematics. As soon as high-speed computers appeared, they began to be used in all areas of physics. Here we will leave aside the role of computers in modern physical experiments, which are now often simply impossible without the use of computers, and will turn to their use in theoretical research.

Monte-Carlo calculation of the properties of a binary alloy using the Ising model. The computer scatters atoms of type A (light squares on the screen) across a flat 16x16 lattice, leaving the remaining spaces for atoms of type B (dark squares), and now counts how many times atoms of different types collide.

Currently, there are two main directions in the use of computers in theoretical physics. In the first approach, the physicist tries to go as far as possible in solving the problem before turning to a computer. The machine is used only for calculating intervals, sums, and for finding solutions to complex equations that cannot be obtained analytically (in the form of formulas). Another approach is what is called machine modeling. Supporters of this direction base their calculations only on the basic physical laws and, examining the calculation results, try

⟦folio 3⟧

draw new physical conclusions. In many ways, such activities are close to physical experiments; sometimes the name “numerical experiment” is even used. Let's look first at the first approach.

If you need computer help

Initially, physicists were not allowed to use computers. The calculations were performed by programs. This was due to the fact that on first-generation computers, programs were compiled in so-called machine codes, which were different for each type of computer. It was very difficult for a non-programming major to write and debug the program. There was a clear division of labor: the physicist wrote the formulas, the mathematician-programmer calculated from them. A large number of problems were solved in this way, but at the same time the disadvantages of this method were also identified. For many problems, this approach failed to obtain correct solutions. First of all, this was due to the fact that the computer carries out calculations with finite accuracy; the implementation of each action leads to a rounding error. For most computers, relative to the calculations of each action lies in the interval $10^{-8} - 10^{-16}$. It would seem that this is very high accuracy. But due to the fact that a computer performs up to $10^8$ operations per second, calculation errors can quickly accumulate.

If the same quantity can be calculated in different ways, then we speak of different numerical processes. These numerical processes may or may not be robust to the accumulation of rounding errors. There are even processes where the accumulation of rounding process makes the calculation method inapplicable after just a few steps. This means that a physicist who wants to carry out numerical calculations using his formulas must understand numerical processes and imagine what methods of applied mathematics he can use in his work. It became clear that physicists and mathematicians must interact with each other at all stages - starting from the formulation of the problem and ending with the numerical process. This circumstance contributed to the emergence of a specialty - computational physics.

Let us also note that the possibility of such a unification of specialties is also associated with the development of programming languages ​​that have made it easier to “communicate” with a machine. Convenient displays*) have simplified the user’s contact with the computer. You or program libraries have been created; Now it is necessary to re-compile a program each time to solve a standard problem, rather than use a library of standard programs during the process. Special journals have also appeared that publish works on computational physics. At the first stages, magazines simply printed the texts of the program. It soon became clear that this could only be done with the simplest programs. The fact is that when typing in a printing house, and then when “transferring” the program from a magazine to a computer, errors inevitably appear. Therefore, now only a description of the calculation method is published; the program itself is stored in a special library and sent to the user upon request.

In the early 70s, at one of the conferences on methods for calculating electron-optical systems, employees of the computer center of the Siberian Branch of the USSR Academy of Sciences demonstrated the work of the program complex created by IMM. Half a day before the report, they asked the non-Falcon speakers to format the tasks that were being solved in their work. At the evening meeting, together with the speakers, the CC staff introduced everyone to their solution to these problems, obtained on a computer using a program complex. It became clear that problems that previously took several months to solve could be solved within a few hours. Such a vivid demonstration of the capabilities of computers forced a lot of cunning in their attitude towards them.

Today, many similar complexes have appeared, oriented

*) This is the name of the screen and keyboard complex in a modern computer, with the help of which a dialogue between a scientist and a machine is conducted. The program is reproduced and processed in the computer on the display, and the calculation results are also displayed on it.

⟦folio 4⟧

for a certain range of tasks. A physicist who is going to work with such a complex does not need to program to study numerical processes for stability. The machine will do this itself; you just need to write the basic equations and set the initial conditions. At the output, the user receives the original solution in the form of tables and graphs. If necessary, the complex will even make a color film based on the counting results. A physicist, sitting at the display, can control the solution, change parameter values, and carry out various initial conditions. Of course, the creation of each program complex is preceded by the hard work of specialists in physics and applied mathematics.

Numerical experiment

Do six pins go horizontally on a taxi pacesetax, when the physics of the phenomenon under study is understood even before turning to the computer. The results of these pacesets are needed for practical purposes.

Now we will talk about another direction of computational physics - about machine modeling. As already mentioned, the machine modeling method is characterized by the fact that only the basic patterns that describe the system are specified.

For example, if this method is used to study the properties of a gas, liquid, plasma, galaxy or other system consisting of many particles, then the law of their interaction and the initial coordinates and velocities of the particles are specified. Next, they compose equations of motion (*), and solve them using a computer.

Observing the evolution of the system and comparing the behavior of the system, we obtain

*) In classical mechanics, the equation of motion for each particle is found in the form of Newton's second law. If the accumulation of particles cannot be assumed to be small compared to the speed of light, then the corresponding equations of the theory of relative equations of quantum mechanics should be used as the equation of motion.

⟦folio 5⟧

expected as a result of such a numerical experiment, with the available experimental data or with what is predicted by approximate analytical methods, scientists try to identify the patterns of its development.

In many respects, the machine modeling method is similar to a physical experiment; with this method one tries to reproduce, “copy” nature. The advantage of modeling is that it allows us to consider systems for which experimental data cannot yet be obtained (processes at ultra-high pressures, temperatures, particle energies).

The possibilities of this method are not unlimited. In order to describe the behavior of molecules in 1 cm³ of real liquid, it is necessary to monitor the movement of about 10²² molecules. Further, for a modern mainframe computer this number is too large. So far, systems consisting of no more than 10⁶ particles are available for calculations. However, even when considering such a “limited” number of particles, in many cases patterns are revealed that are characteristic of a particular system of a large number of particles.

Machine modeling methods work better the more powerful the computer on which the program is implemented. In recent years, special computers have begun to be created, each of which is suitable for solving only one series of problems, perhaps with some modifications, but this is the series that such a computer can solve well.

There are many examples when computer modeling led to discoveries that significantly improved our views of the physical world.

Thus, in 1954, Enrico Fermi and his colleagues used a computer to simulate the propagation of vibrations in a one-dimensional chain of interacting atoms. Thus, they wanted to understand how thermal equilibrium is established in solids. In order to model the interaction, it was assumed that neighboring atoms are connected by bonds. From a preliminary theoretical consideration it was known that in the case when the tension force F must be supported by the atoms, is associated with a change in its length Δx by the general linear law F = -k·Δx, thermal equilibrium in the system is never established. At the same time, it was believed that it was enough to introduce any nonlinearity into the law of interaction of atoms (that is, consider F(Δx) as a nonlinear function) - and thermal equilibrium would be established in such a system in a finite time.

In their work, Fermi and his co-workers reduced the simplest nonlinearity by adding a term proportional to (Δx)² to the expression for the force F. Numerical calculations have shown that in this case thermal equilibrium in the system is actually established, but extremely slowly. The characteristic time of this process is many times greater than the estimates that gave significant results in terms of theory. This surprising result stimulated further numerical and analytical studies. It has been proven that for some types of nonlinear dependence of the tension force on the distance Δx, warm equilibrium in the system will never be established.

Currently, hundreds, if not thousands of articles have been published in which numerical and analytical studies are also carried out on systems. The results of these studies do not find

⟦folio 6⟧

mediocre application in a wide range of problems in plasma physics, hydrodynamics, optics, etc.

When Fermi and his collaborators began their work, they realized that the chain model they had chosen was far from a real solid. Real crystals have a complex three-dimensional lattice; not only the nearest neighbors interact in them, and the law of interaction of city atoms is more complex than was assumed in this work. Nevertheless, a simple model of a one-dimensional chain allows possible consequences of the NON-LINE law of interaction of atoms.

Ising model and random number generator

Not all problems, however, are suitable for the numerical solution of the equation of motion. For a number of problems, such an important computer modeling method as the Monte Carlo method is used. Let's get acquainted with it using the example of studying phase transitions. But first, let's say a few words about the problem of phase transition itself, which for many years, due to its complexity, physicists could not fully understand.

Phase transitions also include well-known phenomena such as melting and boiling, as well as many less familiar ones - the transition of a metal into a superconducting state, and a gel into a superfluid state, ordering of alloys, etc. All these, at first glance, dissimilar phenomena, have one common property - as a system approaches the transition, the interaction of an increasing number of its particles becomes significant, which complicates the use of general methods of theoretical physics. This is where the computer comes to the rescue, allowing you to calculate the behavior of the phase transition detection system. However, first you need to come up with a suitable model - simple, and at the same time reflecting the basic properties of the system.

This is how, for example, we can describe the phase transition from a gaseous to a liquid state. Consider a flat lattice containing $N$ nodes containing $m$ ($m < N$) atoms. It is known that the interaction between atoms quickly decreases with increasing distance between them, so it can be roughly assumed that atoms in a lattice interact only if they find themselves in neighboring lattice nodes. This model is called the Ising model of lattice gas with nearest neighbor interaction.

At high temperatures, atoms are distributed on average evenly throughout the lattice. However, at sufficiently low temperatures, thanks to the attraction between atoms, they form together, filled with neocotropic lattice volumes. Thus, as the temperature decreases, water vapor first becomes saturated and then condenses into liquid droplets.

In order to find out the temperature at which the “condensation” of a lattice gas occurs (phase transition), or, for example, to find out how the heat of phase transition behaves, it is necessary to be able to calculate the energy of the system of interaction of atoms for each method of their arrangement along the lattice (configuration). The main difficulty is that the number of ways to arrange atoms at a lattice node very quickly returns to $N$ as the number of nodes increases. If, for example,
