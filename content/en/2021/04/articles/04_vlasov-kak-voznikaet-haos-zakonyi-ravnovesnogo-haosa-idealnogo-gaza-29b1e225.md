---
id: 2021-4-vlasov-kak-voznikaet-haos-zakonyi-ravnovesnogo-haosa-idealnogo-gaza-29b1e225
issue: kvant_2021_4
year: 2021
number: "4"
title: How chaos arises. Laws of equilibrium chaos of an ideal gas
authors:
  - Власов А. И.
rubric: fizicheskiy-fakultativ
rubric_sub: Физический факультатив
page_first: 32
page_last: 39
page_labels: 33, 34, 37
tag: WP2G
lang: en
source: kvant_digital
extraction: native
content_sha256: 2a3145b075ae591ea93b5fddb461f08209fb1649513ad88f45bcae5877f07a4f
prompt_sha256: draft-1
translated_from: content/ru/2021/04/articles/04_vlasov-kak-voznikaet-haos-zakonyi-ravnovesnogo-haosa-idealnogo-gaza-29b1e225.md
source_content_sha256: 9ab4a19431349b3e229fca6e1e0be63048b90e357aff8e828ac47880799cac9c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

PHYSICS ELECTIVE

How chaos arises. Laws of equilibrium chaos of an ideal gas

A. VLASOV

IN SEPTEMBER 1859, AT A MEETING OF THE British Scientific Association, J. Maxwell reported on his research in the field of molecular kinetic theory of gases. In this report, the statistical law of molecular velocity distribution was presented for the first time. With this work, probability appears in the kinetic theory of gases, and the formation of statistical physics begins. Here it is appropriate to quote from the book by L.D. Landau and E.M. Lifshitz “Static Physics”: “The subject of statistical physics... is the study of a special type of laws that govern the behavior and properties of macroscopic bodies, i.e. bodies consisting of a colossal number of individual particles - atoms and molecules... At first glance, one could conclude from this that with an increase in the number of particles the complexity and intricacy of the properties of a mechanical system should increase unimaginably and that we cannot find traces of any regularity in the behavior of a macroscopic body. However, this is not so, and we will see later that with a very large number of particles, new peculiar patterns appear. These so-called statistical laws... cannot in any way be reduced to purely mechanical laws.” Let us immediately note that we will limit ourselves to the study of the simplest classical ideal systems. Let us try to trace how, as the number of particles composing a system increases, a limiting statistical order arises in it. Naturally, it won’t be beautiful here (but incomprehensible to a schoolchild)

DOI: https://doi.org/10.4213/kvant20210403

⟦column⟧

mathematics, however, we cannot do without formulas in which the order of chaos is embodied. The computer will answer the questions posed (of course, we will provide it with the appropriate program). Let's start by refining the ideal gas model.

Ideal gas model From the school textbook it is known that an ideal gas is a system of non-interacting material points. But in such a model there is no main thing - there is no possibility of the emergence of chaos and, accordingly, there is no possibility of the emergence of a probabilistic order. It is obvious that chaos in a closed (isolated) system of non-interacting particles can only arise as a result of their collisions. Collisions are only possible between particles that have a size. If we consider gas molecules to be elastic balls, then the problem of “excluded” volume arises. A gas of solid balls is no longer an ideal gas, and its equilibrium state no longer obeys the Clapeyron–Mendeleev equation. But the situation can be corrected by proposing a special – virtual – collision mechanism. At the moment of a virtual collision, changes in speeds are determined (calculated), but these changes are temporarily “postponed”. The balls continue to move, and only at the moment of the shortest distance between their centers does the delayed change in speed “turn on.”

Maxwell's distribution and the law of uniform distribution Here we cannot do without the concept of probability. Let us make a short digression into the area of ​​elementary probability theory. Physical processes can be deterministic or random. Accordingly, the parameters (physical quantities) characterizing these processes are deterministic or random. The nature of the processes and their parameters is determined during repeated measurements. For deterministic quantities, repeated measurements give consistent results (within the measurement error). For random variables, repeated measurements lead to a set (spectrum) of values. Probability is a characteristic of a random process. Her “mathematics” is based on the idea

⟦folio 33⟧

PHYSICAL

particle coordinates are calculated using the formulas $x_{i} x_{i}^{v} i$ dt, where dt is a very short period of time. When the spheres of the balls overlap, the impact phase occurs. The new velocities of the encountered molecules are calculated, and the movement continues. Throughout the computer experiment, the necessary information about the physical state of the system is collected. In our case, these are statistics of the speed and energy of molecules. figure 4 shows the probabilistic spectrum of gas molecule velocities. The computer of this car-

OPTIONAL

⟦column⟧

⟦figure⟧

Fig. 5

⟦figure⟧

Fig. 4

Teen gets this way. The entire possible range of molecular speeds is divided into small cells. After each step of movement, 1 is added to the corresponding cells (those cells in which the speed of the molecule falls). Upon completion of a sufficiently long experiment, the contents of the cells are divided by the number of steps (number of trials). It is clear that by this division we determine the probability of the speed of molecules in a given interval. The resulting graph proves the discrete nature of the molecular velocity spectrum. There are 36 states in total. It can be noted that there is a fairly clear symmetry in the spectrum. And, most importantly, this spectrum depends on the initial conditions. This is confirmed by a repeated graph of the system with different initial conditions (Fig. 5). It is interesting that the number of states remains the same, but the picture of the spectrum changes significantly. And there is a completely unexpected (for such a small system, only 2 particles) equality of the average energies of light and heavy particles. In two implementations, the ratio of average energies is quite close to unity (0.988 and 1.139).

⟦figure⟧

Fig. 6

When the number of particles increases to 4 (two pairs of particles light - heavy), the probability function changes sharply (Fig. 6). It becomes almost continuous. The number of states exceeds 400 (the number of speed cells). The graph shows that all the speed cells are already filled, and the accuracy of the calculations no longer allows us to identify discreteness. Changing the initial states practically does not change the spectrum and therefore, with a further increase in the number of particles, one can move on to probability density functions. To do this, the interval probability should be divided by the size of the interval. The graph at figure 7 shows the probability density function of the velocity projection for 3 pairs of particles. Dots (crosses) – computer experiment, the blue continuous line corresponds to the theoretical Maxwell function for the case of a one-dimensional ideal gas

$mv^{2}$

U v

m  $e^{2} kT. 2 S kT$

⟦folio 34⟧

KVAN T 2021/№4

⟦figure⟧

Fig. 7

⟦column⟧

Two-dimensional ideal gas model Here everything is much more interesting. Gas models of the second and third dimensions must have a continuous spectrum of velocities (with a small number of particles there will no longer be a discrete spectrum). This is determined by the continuity of the angular parameter that determines the change in velocities during collisions. Now let's see how the velocity spectrum changes as the number of particles increases. figure 10 shows a graph for 2 particles. A very unexpected and beautiful result is a linear probability density function (for a system of two particles, the presence of maximum speed is the most probable). This is very far from the Maxwell function. But as soon as one particle is added, the system begins to “correct” (Fig. 11). With a further increase in the number of particles, the system very quickly “converges” along the velocity spectrum to the Maxwell function (Fig. 12 for 16 particles). Here it is appropriate to provide (for programming enthusiasts) additional information

⟦figure⟧

Fig. 8

⟦figure⟧

Fig. 10

⟦figure⟧

Fig. 9

The graph shows that already for 3 pairs (6 particles) there is a fairly clear correlation with the Maxwell function. The following graph (Figure 8) corresponds to a system of 10 pairs (20 particles). Here the theoretical curve practically coincides with the experimental one; differences are visible (small fluctuations) only in the region of zero velocities. Finally, the plot at figure9 for 50 pairs (100 particles) illustrates that experiment and theory are in perfect agreement.

Fig. 11

⟦folio 37⟧

EXAMINATION

A was done if, during rotation, the rods deviated by an angle D 45 q? Take the free fall acceleration equal to g 10 m $с^{2}$, the dimensions of the loads can be neglected. 2. The oscillatory system consists of a load $массой^{m,} лежаще-_{Рис.} 4$ on a smooth horizontal plane, a weightless smooth block, two weightless, inextensible threads and three weightless springs $жесткостью_{1}^{k} 2 3$ N cm $,_{2}^{k} 1 2$ N cm $и_{3}^{k} 1$ N cm, respectively, connected as shown in figure 5. The center of mass of the load lies on one horizontal with a thread attached to it and a spring axis $жесткостью_{1}^{k}$. In the equilibrium position, all springs are stretched. Assuming that the threads remain $натянутыми,^{Рис.} 5$ all the time, determine the circular frequency Z of small harmonic oscillations of the load. 3. A fully filled cylinder with a volume of $V_{0} 5$ l holds $m_{0} 2,5$ kg of liquefied propane $( C_{3} H_{8} ).$ If part of the propane from the cylinder is released outside, then liquid propane and its saturated vapor will be in equilibrium. Find the mass $m_{1}$ of propane in the gaseous state in the cylinder when D (%) of the initially contained propane is released from this cylinder, if the temperature of the propane is maintained constant and equal to t 17 q C. The saturated vapor pressure of propane at this temperature is p 0.8 MPa. The molar mass of propane is 0 44 g mol, the universal gas constant R is 8.31 J mol K. 4. Two oppositely charged particles are located on the x-axis of the Cartesian coordinate system at a distance of l 3 cm from each other (Fig.6). While holding one particle motionless, the second particle was moved in the direction of the y axis at a distance of $l_{1} 4$ cm. In this case, $A_{1}$ of work was done. Fig. 6

MATERIALS

⟦column⟧

What work $A_{2}$ will need to be done in order to then move the second particle a distance $l_{2} 2$ cm in the direction of the x axis? 5. There is a flat mirror on the horizontal bottom of the aquarium. A person leaning over the water and looking vertically down sees the image of his eye in the mirror at a distance of l 50 cm. Determine the thickness of the layer H of water in the aquarium if the eye is located at a distance of h 10 cm from its surface. Consider the refractive index of water to be equal to n 4 3. Please note that for small values ​​of the argument M, given in radians, we can assume tan M | sin M | M.

Final stage

The final stage of the Olympiad was held on February 25–27, 2021 in a remote format on the portal https: exam.distant.msu.ru. To participate in this stage, certain technical requirements were imposed on the test subject’s workplace (these can be found on the Olympiad website). The assignment for students in grades 7–9 consisted of four problems on topics studied as part of the physics program for the basic secondary school. The tasks for students in grades 10–11 were compiled in full accordance with the 2021 Unified State Exam Codifier in Physics and covered the main sections of the Codifier, namely: 1) mechanics, 2) molecular physics and thermodynamics, 3) electrodynamics and 4) optics. The typical assignment consisted of four different sections, including problems and clarifying questions on the theory. 4 astronomical hours (240 minutes) were allotted for completing tasks for all classes.

Grades 7–9 1. While performing laboratory work in physics, the student had at his disposal three springs, the stiffness of two of which turned out to be $равными_{1}^{k} 10$ N m $и_{2}^{k} 20$ N m, respectively, and the stiffness of the third was unknown. As instructed by the teacher, the student connected all three springs in series and stretched the resulting composite spring by applying a force F 1 N (Fig.7) to each of its free ends. By measuring the total elongation ' l co-
