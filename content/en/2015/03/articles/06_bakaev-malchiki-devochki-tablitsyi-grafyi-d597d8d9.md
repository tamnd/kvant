---
id: 2015-3-bakaev-malchiki-devochki-tablitsyi-grafyi-d597d8d9
issue: kvant_2015_3
year: 2015
number: "3"
title: Boys, girls, tables, graphs...
authors:
  - Бакаев Е. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 55
page_labels: 52-53
tag: 4H1S
lang: en
source: kvant_digital
extraction: native
content_sha256: 24484df89bc9fa861a39d47a7e5bc424359b78c0d84fb8e2234f257ada4ead03
prompt_sha256: draft-1
translated_from: content/ru/2015/03/articles/06_bakaev-malchiki-devochki-tablitsyi-grafyi-d597d8d9.md
source_content_sha256: 49455be1045bfe0bc10bbdf04cacfffa6e39068713a87130619928520f9afe93
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

Boys, girls, tables, graphs...

⟦column⟧

silver and gold coins, respectively), corresponds to the possible position on the table (number of silver and gold coins) (Fig.1). With each action, a point corresponding to

E.BAKAEV

IN THIS ARTICLE WE WILL TRY TO COMBINE several beautiful combinatorial problems into ONE plot. Let's start with this: Problem 1. There are m boys and d girls in a row in some order. Each boy was asked how many girls there were to his right, and each girl was asked how many boys were to her left. Prove that the sum of the numbers named by the boys is equal to the sum of the numbers named by the girls. Solution. Let all the boys look to the right and all the girls look to the left. Then if a boy sees a girl, then this girl sees him. Thus, the sum of all numbers named by boys and the sum of all numbers named by girls is the same quantity: the number of boy-girl pairs seeing each other. We will meet this problem at the heart of several subsequent ones. Task 2 (XXXVI Tournament of Cities, 2014). There was a pile of silver coins on the table. Each action either added one gold coin and wrote down the number of silver coins on the first piece of paper, or removed one silver coin and wrote down the number of gold coins on the second piece of paper. As a result, only gold coins remained on the table. Prove that at this moment the sum of all the numbers on the first sheet was equal to the sum of all the numbers on the second. First decision. In parallel with the actions with coins, we will write out a sequence of letters C and Z: when adding a gold coin, we will write the letter Z, when removing a silver coin, we will write the letter C. Now, instead of counting coins, we can count the letters in the resulting line. When we wrote the next letter C, we wrote down on a piece of paper the number of gold coins that were already on the table, i.e. the number of letters Z to the left of this letter S. And when they wrote the next Z, they wrote down on a piece of paper the number of silver coins that were still lying on the table and that had to be removed - i.e. the number of letters C to the right of this letter Z in the final line. Let us now replace the string of letters C and Z with a row of boys and girls - and we get exactly problem 1. It remains to paraphrase its solution: if a silver coin is counted when a gold one is added, then this gold one is counted when this silver one is removed, i.e. the silver coin was removed after the gold coin was added. Thus, the sum of the numbers on both sheets of paper is the number of such “silver coin - gold coin” pairs that were both on the table at some point. Second solution. Let's consider a coordinate plane on which the vertical axis corresponds to the number of silver coins, and the horizontal axis to the number of gold coins. Each integer point lying in the rectangle S ¥ G (where S and G are the largest possible number

⟦figure⟧

Fig. 1

corresponding to the current position is shifted either by a unit segment down (when we remove a silver coin) or by a unit segment to the right (when we add a gold coin), the initial position corresponds to the point (0, S) on the vertical axis, and the final position – (G, 0) on the horizontal (Fig.2).

⟦figure⟧

Fig. 2

When we go from point (x, y) to the right along the segment, the first coordinate increases, and we write y on the first sheet, i.e. the number of cells under this segment. Similarly, when we go from (x, y) down, we write x on the second sheet - the number of cells to the left of the segment. It turns out that we will count each cell under the polyline twice: once on the first sheet when we pass over it, and once on the second sheet when we pass to the right of it (Fig.3). This means that the sums of the numbers on the sheets of paper will be the same and will be equal to the number of cells under the broken line.

⟦figure⟧

Fig. 3

The main idea of ​​the second solution is to consider the set of all possible positions of the system; in this article we will use this technique more than once. In mathematics, such a set is called the phase space of the system. (But usually this term is used in a different context.) Problem 3. There are m boys and d girls in a row in some order. Each child was asked how many children of the other sex stood to his left. What is the sum of the numbers named by the children? Answer: md.

⟦folio 52⟧

KVANT 2015/№3

At what angle $\alpha$ between the rod and the wall will the rod detach from the vertical wall and what will be the velocities of the ends of the rod along the wall and along the floor at this moment? 2. From a cylinder with radius r = 2 cm, a fluid paste (Fig.6) is squeezed out with a piston. It spreads across the surface

⟦figure⟧

Fig. 6

layer h = 2 mm thick, forming a circular spot. The piston speed is u = 6 cm/s. What is the speed v of expansion of the spot boundary for a spot radius R = 30 cm? 3. In a room with volume $V = 75 м^{3}$ the air temperature is the same as outside, i.e. $t_{1} = - 20 ^\circ C$. The electric fireplace is turned on, and it slowly warms the air in the room to $t_{2} = + 23 ^\circ C$. Some of the air escapes through a tightly closed window. Find the change in internal energy of the air in the room and the work done by the air as it expands outward. Take atmospheric pressure equal to $p_{a} = 10^{5}$ Pa. 4. Plot a graph of the resistance of the circuit shown in figure 7 versus the resistance r of each of one pair of resistors. The resistance of another pair of resistors

⟦figure⟧

Fig. 7

tori is unchanged and equal to R = 50 Ohm for each. Consider the diode ideal, i.e. its resistance in the forward direction is negligible, and in the reverse direction it is very high. 5. A weight hanging on a thread of length L = 1.1 m, tied to a nail, was pushed so that it rose and then hit the nail. What is its speed at the moment it hits the nail? Gravity acceleration g. 6. At noon, through a small window on the southern wall of a dark room, a beam of sunlight enters it, parallel to the western and eastern walls. After reflection from a flat mirror lying on a horizontal table, the beam falls on the north wall. What area of ​​shadow will be cast on the northern wall by an opaque circle of radius r = 10 cm standing vertically on the mirror, if the plane of the mirror is parallel to the southern wall? 7. A proton, accelerated by a potential difference U = 500 kV, flies through a transverse uniform magnetic field with induction B = 0.51 T (Fig.8). The thickness of the region with the field is d = 10 cm. Find the displacement and angle of deviation of the proton velocity from the original direction at the exit from this region.

Fig. 8

History of scientific ideas and discoveries

Mathematics

⟦column⟧

1. The twentieth sentence of Book IX of Euclid’s Elements states: “There are more first numbers than any proposed number of them.” Formulate this statement in modern terms and prove it. 2. Archimedes, Euclid, Apollonius of Perga and other great mathematicians of antiquity called a parabola the geometric locus of points equally distant from a given point and a given line. Make sure that the graph of the function $y = x^{2}$ is a parabola. 3. In 1202, Leonardo of Pisa (Fibonacci) in his “Book of Abacus” considered a sequence, each member of which is equal to the sum of the previous two, i.e. sequence $\phi_{1} = \phi_{2} = 1, \phi_{n} +_{2} = \phi_{n} +_{1} + \phi_{n}$ at $n \ge 1$. Subsequently, Fibonacci numbers often appeared in various branches of mathematics - number theory, algebra, combinatorics, mathematical logic, etc. Many remarkable properties of these numbers were discovered. For example, one can prove that for any positive integer m there is a Fibonacci number divisible by m. Find out whether any Fibonacci number can be a power of 7. 4. One of the greatest world-famous mathematicians, L. Euler, in 1752 proved a theorem that is considered the first in the history of one of the most profound branches of mathematics - topology. Euler's theorem states that the number of vertices B, the number of edges P and the number of faces G of an arbitrary convex polyhedron satisfy the equality B - P + + G = 2. Using this theorem, find out whether there is a convex polyhedron all of whose faces are hexagons. 5. Another brilliant mathematician K.F. Gauss proved the remarkable “index theorem”: if p is a prime number, then there is a natural number g such that its powers $g, g^{2}$, …, $g^{p} -^{1}$ give different remainders when divided by p, and $g^{p} -^{1} - 1$ is divisible by p (Fermat’s little theorem); and thus in the written sequence of powers there are numbers that give all possible remainders from division by p. For example, for p = 17 we can take g = 3, since, writing out sequentially the remainders of the powers of three when dividing by 17, we have

3, 9, 10, 13, 5, 15, 11, 16, 14, 8, 7, 4, 12, 2, 6, 1

– all residues are different. Using Gauss's theorem, prove that for every prime number p there is a natural number x such that the product $x^{2} - 2 x^{2} - 3 x^{2} - 6$ is divisible by p.

(

)(

)(

)

Physics

1. The 1904 Nobel Prize was awarded "for his studies of the densities of the most common gases and for the discovery of argon in the course of these studies." The scientist who received this prize was an English aristocrat. He studied at Trinity College. After J.C. Maxwell's death, he became the second Cavendish Professor and director of the Cavendish Laboratory. He was Secretary of the Royal Society of London and President of Cambridge University. His main works relate to the theory of oscillations, of which he is one of the founders. He studied the vibrations of strings, rods, plates, and shells. In 1873 he formulated a number of fundamental theorems

⟦folio 53⟧

OLYMPICS

linear theory of oscillations, allowing one to make qualitative conclusions about the natural frequencies of oscillatory systems. In his fundamental work “The Theory of Sound,” a unified approach to the study of oscillatory and wave processes of different physical natures was clearly revealed for the first time. He considered the addition of oscillations with random phases and obtained a frequency distribution function for the resulting amplitude. This distribution function took his name. It turned out that the distribution of the energy density of a completely black body over wavelengths is also described by this function (this distribution bears both the name of this scientist and his colleague D. Jeans, who independently obtained this result in 1905). His major discovery was the theory of surface elastic waves (which received his name) - elastic disturbances propagating in a solid body along its free boundary and damping with depth. He explained the difference between group and phase velocities, established relationships between them, laid the foundations for the theory of molecular light scattering (while explaining the blue color of the sky), and created a theory of the resolving power of optical instruments. In all these branches of physics there are formulas, processes and theories named after him. a) Who is this scientist? b) Name other physical instruments, model numbers and criteria not mentioned in the text, named after this scientist. 2. In the third century BC. An outstanding experiment was carried out - for the first time in human history, the radius of the Earth was measured. In the measures of length adopted at that time, it amounted to 252 thousand stadia. Unfortunately, the author of the study did not indicate whether he used the Greek stage or the stage adopted for measurements in the country where he was born and worked. Depending on this, the measurement error, according to modern estimates, was either 1.5% or 10% (a smaller error value is obtained under the assumption that the scientist used the “native” stage for him). a) Name the scientist who was the first in human history to measure the radius of the Earth. b) In what country did this scientist live and work? c) In which cities did the scientist take measurements and what feature of the geographical location of these cities made it possible to conduct this elegant experiment? 3. In the third century BC. a very important law of hydrostatics was discovered. The discovery of the law was preceded by a lot of work to find out whether the royal crown was made entirely of gold or whether the jewelers mixed silver into the crown. History has preserved the name of not only the author of the discovery, but also the customer of the work - the king (or, to be precise in the titles, a tyrant, then this word did not carry a negative connotation) Hiero. Whether silver was found in the crown or not, there is no exact data. And for the history of science this is not so important. a) Name the scientist and formulate the law that received his name. b) Name the city and territory where the described events took place. c) Estimate the absolute measurement error. Could a scientist, using the measuring instruments of that time, obtain a reliable result? 4. There is a well-known story that an Italian scientist, who lived and worked in the 16th–17th centuries, threw balls from the Leaning Tower of Pisa to prove the hypothesis that the speed of a freely falling body was independent of its mass. However, both he and we now understand that this experiment has limited accuracy. The scientist performed a series of more subtle experiments and obtained an experimental

⟦column⟧

proof of this hypothesis. He also formulated the principle on which all classical mechanics is based. a) Who is this scientist? b) What experiments did he perform to prove the hypothesis? c) Formulate the principle specified in the condition. 5. In 1818, at one of the meetings of the French Academy, work on the diffraction of light was considered. One of the members of the Academy, a famous scientist, doubted the legitimacy of considering light as a wave process. The chairman of the meeting proposed conducting an experiment and predicted a paradoxical result, which would clearly indicate in favor of the wave theory of light. The experiment was carried out. The predicted diffraction pattern was obtained, which was named after the doubting opponent. a) Who was the author of the work? b) What result was obtained? c) Whose name was the result named after? d) Who chaired the meeting of the Academy?

III International Mathematical Tournament named after M.V. Lomonosov for students in grades 5–8

Oral team round

5–6 grades

1. How many four-digit numbers are there, written as 1 and 2? 2. What angle do the hour and minute hands of a clock make at 10 o'clock 12 minutes? 3. There were 10,000 one-cent coins in the piggy bank. Every month, 30% of the contents of the piggy bank is spent. How many coins will be left in the piggy bank after four months? 4. In a square ABCD, point K is the midpoint of side AB, point L is the midpoint of side AD, segments CL and DK intersect at point M. Prove that triangle BCM is isosceles.

Penalty problems

Ш1. Add two digits to the right to the number 987 so that the resulting five-digit number is divisible by 5, 6, 7. Ш2. Find two natural numbers whose square difference is 37. Ш3. It takes a tourist 6 hours to climb uphill at a constant speed, and 2 hours to descend at a constant speed. How long after the start of the climb will the tourist return to the base of the mountain if he begins to descend 4 hours after the start of the climb? Ш4. Find the area of ​​$фигуры,_{Рис.} 9$ shown in figure 9.

7–8 grades

1. Find the smallest natural number n for which the product ( n + 1 )( n + 2 )( n + 3 )( n + 4 ) is divisible by 1000. 2. A square is inscribed in a right triangle with legs a and b, one of whose vertices coincides with the vertex of the right angle of the triangle, and the opposite vertex of the square lies on the hypotenuse of the triangle. Find the area of ​​the square. 3. Can a four-digit number of the form aabb be the square of an integer?
