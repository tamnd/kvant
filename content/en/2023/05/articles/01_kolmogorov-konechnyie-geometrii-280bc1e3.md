---
id: 2023-5-kolmogorov-konechnyie-geometrii-280bc1e3
issue: kvant_2023_5
year: 2023
number: "5"
title: Finite geometries
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 5
page_last: 29
page_labels: 3, 5, 11, 13, 18, 21, 24, 27
tag: TF3Y
lang: en
source: kvant_digital
extraction: native
content_sha256: 0d2d4772a98353503189ba778141c3aa325c8d88f409bdf96562c763b420c5f2
prompt_sha256: draft-1
translated_from: content/ru/2023/05/articles/01_kolmogorov-konechnyie-geometrii-280bc1e3.md
source_content_sha256: 1a898faf572817ebd2238352218d140f2f05fe711a3523c0eced2729262d5488
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

FINITE GEOMETRY

We, mathematics students and graduate students participating in the work of the mathematical school, discussed in detail Andrei Nikolaevich’s lectures and the specific mathematical problems accompanying them, let schoolchildren solve them, and also came up with our own, completely new problems, adding to the original (not very large) list of problems on this topic, proposed by Andrei Nikolaevich before the start of his lectures. Towards the end of school, Andrei Nikolaevich began to talk about the idea of ​​discrete time: what if time flows not continuously, but discretely, from point to point, and is the same straight line of a finite number of points, like all straight planes, and what happens if this straight line is added to the existing ones? However, this extended program of research into finite geometries was not actually started: the month of summer school ended very quickly. As a result of processing the notes of A.N. Kolmogorov’s lectures by the author of these lines and further work on problems on finite geometries, an article appeared that is offered to readers «Kvant» and which in a concentrated form conveys the spirit of the Pushchino Summer Mathematical School of 1972. G. Galperin

Finite geometries

A. KOLMOGOROV

A.N. Kolmogorov gives a lecture

CURRENTLY GEOMETRY has several branches. The first step towards a new geometry was made by Renaissance artists who struggled with

⟦column⟧

giving an accurate image of what the eye sees. Since real paintings are three-dimensional, and paintings made by artists are two-dimensional, it may seem that it is impossible to paint realistically. Artists based their solutions to this problem on visual perception. Let's imagine a person looking out of the window with one eye at some real scene. He sees it because the light rays emitted by various points of this “picture” reach his eye. A collection of such light rays is called a projecting beam. And since the rays pass through the glass, we are able to mark on it the point through which each ray passes. The set of all such points is called a projection. Artists are responsible for the discovery that the eye perceives this projection in the same way as the real scene itself. The use of the projection method put on the agenda a fundamental geometric question, which was first considered by artists and then taken up by mathematicians. What are the common

⟦folio 5⟧

FINITE GEOMETRY

P3. There are four non-collinear points (i.e. any three of them are non-collinear). Exercise 1. Check that the completion of the affine plane given above actually defines the projective plane. Examples: 1. By completing the affine plane of Euclidean geometry, we obtain the real projective plane ¡ $P^{2}. 2.$ By completing the affine plane of four points to the projective one, we obtain a projective plane of seven points and seven lines (Fig. 2).

⟦figure⟧

Fig. 2

3. Let's build another model of an infinite projective plane. Let $¡^{3}$ be an ordinary three-dimensional Euclidean space and O be some point in it. Let us denote by 3 the set of all lines passing through O. A point in 3 is any of the drawn lines, and a line is the set of lines passing through O and lying in a certain plane. Set 3 will satisfy axioms P1 – P3 (check this!), therefore, it is a projective plane. From Example 2 it is clear that in one particular case of finite projective geometry the number of points is equal to the number of lines. There are infinitely many finite affine geometries (which will be clarified below in the problems), and all of them can be completed in the same way as was done in the case of four points. Will the number of points and lines coincide? The answer to this question is given by the following sentence. Proposition 1. Let 3 be the projective plane. Then the set &, element-

⟦column⟧

whose elements are lines in 3, called points in &, is a projective plane, if we call bundles of lines in 3 straight lines in &. The plane & is called dual to 3 (since in fact the points and lines in 3 swapped places and it turned out &). Proof. Let us check the fulfillment of the axioms of the projective plane. X1. Let A and B be two different points in &; then there is a unique line from & containing A and B. But in terms of 3 this means that for two distinct lines from 3 there is a pencil containing both of these lines, and this follows from A2. X2. Any two lines from & have a common point, which follows from A1. X3. We need to show that there are 4 points, no three of which are collinear at &. This is the same as showing that in 3 there are 4 lines, no three of which lie in the same bundle. Let's take 4 non-collinear points from 3 (there are such points according to P3) and from all the straight lines passing through them, select the four we need. Thus, the proposition is proven. Consequence. If K is some statement in 3, deduced from axioms P1–P3, then the statement K obtained from K by a dual substitution (such as straight lines correspond to points, etc.) can be deduced from the same axioms. Proof. It is clear that K is the same statement K, only in geometry &. But the axioms of geometry & follow from the axioms of geometry 3, which is what was required. Now it is clear why the number of points and lines in projective geometry is the same - because of the principle of duality. If we construct the dual plane * from the plane & in a similar way, then it turns out that the planes 3 and * are “isomorphic”. However, the planes 3 and & are not always isomorphic. Examples can be constructed using finite planes on which Desarte's axiom does not hold (see below). (One such example is the Hall plane of order 9, consisting of 91 points. – Ed.)

⟦folio 11⟧

FINITE GEOMETRY

Fig. 42

Fig. 43

to show the failure of P2, we can take an arbitrary affine geometry. The case when P3 does not hold is shown in figure 43. 9. Prove that if a line is removed from the projective plane, then an affine plane is obtained. Solution. Let us remove straight line a from projective plane 3. Let us prove that axioms A1–A3 are satisfied in the resulting plane. Indeed, let us take points A and B in the new plane and let A c and B c be the same points in the projective plane 3. It is clear that A c and B c do not belong to a. According to A1, there is a unique straight line l c such that A c, B c l c. According to the previous one, l c z a, which means that l c will go into some non-empty set l . Since A c, B c l c, then A, B l. Since l c is the only one, it means that l is the only one, since we removed a. So, A1 is done. Let's check A2. Take an arbitrary straight line l and a point X l in. Suppose that when straight line a is removed, line lc goes to l, and point X c goes to X. It is clear that l c z a and X c a. Hence, by A2, there is a unique M c l c a. By A1, there is a unique straight line m c such that X c, M c m c. If X c l c, then m c l c and, therefore, m c l c M c. Since the removal of a removes M c, then m l , where m and l are the images of m c and l c in the plane. This means that m is parallel to l, and since X c m c, then X m. In addition, m c is unique, which means that m is also unique, and therefore A2 holds. If X l, then X c l c, which means m c l c. Exactly one point M c is removed from m c and from l c, so m l can be written as m P l. Since m c is unique, therefore m is also unique, and a line parallel to the given one passes through a point on a line in a unique way. Thus, A2 is completely proven. Let's check A3. According to P3, we select 4 non-collinear points. We are interested in the case when two of them lie on the remote line, since in other cases A3 is satisfied (since there cannot be more than two of them on the remote line

⟦column⟧

four points). Let A, B, C, D be 4 points and A, B a. Let's carry out direct AC and BD. By A2, there is a unique point M AC BD and M z A, B, C, D. Moreover, M a, since otherwise AC a and BD a. In addition, C, D and M do not lie on the same line, since otherwise there would be two lines passing through M and C. When a is removed, points C, D and M remain, since none of them belonged to a. This means that axiom A3 is satisfied. 10. Construct an affine plane of 16 points. The solution is depicted at figure 44.

⟦figure⟧

Fig. 44

11. A line in the projective plane 3 contains n 1 points. How many points are there in 3? How many lines? Solution. Let us take a line a in plane 3 with points $A_{1}, A_{2}$, … $, A_{n} 1$. By axiom P3, there is a point B such that B a. Let's carry out $BA_{1}, BA_{2}$, … $, BA_{n} 1$. In this case, all points will be involved. Indeed, if, for example, C does not belong to a, then BC intersects with a at one of the points $A_{k}$ and, therefore, point C is already taken into account. So, in total we get n 1 1 n 1 1 n 2 n 1 points in 3. Since through each point (as well as through B) there are n 1 straight lines, and each straight line is taken into account n 1 times in this calculation (there are n 1 points on it), then there will be n 2 n 1 n 1 straight lines

, n 1 i.e. as many as points. This was to be expected, since it occurs

⟦folio 13⟧

FINITE GEOMETRY

⟦figure⟧

Fig. 48

ramie (Fig. 48 from left). Let's call straight lines that have one of the directions shown in figure and pass through the grid nodes. (You can imagine as a model the mesh cylinder shown in figure 48 on the right.) Let us prove that at most one straight line passes through point 1 and any other point. On the contrary, let two straight lines pass through points 1 and X, where X is a point in the k-th row. The distance between the points of intersection of these lines with the first line is n p. Then the distance between the grid nodes denoting point X through which these lines pass is equal to kn. Since p is a prime, k p, n p, then kn is not divisible by p, so these two nodes are not one point. Lines passing through point 1 also pass through all other points. Indeed, through point 1 there are p 1 straight lines, on each of them, except for point 1, there are p 1 more points, no two of all the points coincide, there are $p 1 p 1 p^{2} 1$ points in total. Q.E.D. If we draw all straight lines through any point of the plane, we get the same picture as for point 1. Thus, A1 is checked. There are p points on a line. Consider point B outside this line; p 1 straight lines pass through it. Of these, p straight lines intersect a given line at p points, but one cannot intersect it, since only one straight line can be drawn through this point and any other. Consequently, through each point it is possible to draw exactly one straight line parallel to the given one, which means that axiom A2 is satisfied. Axiom A3 is also satisfied, since there are 3 non-collinear points. Therefore, the constructed plane is affine.

⟦column⟧

16. Prove that a plane in an affine space is affine. Proof. Axiom A1 automatically follows from AC1 and AC2. Let's check the execution of A2. Take a straight line a in the plane D. According to AC6, there is a point A D such that A a. According to AC5 there is b P a, A b. Let us prove that b D. Consider the plane E containing a and b (such a plane exists by the definition of parallel). In plane E and in plane D there are three non-collinear points A, B, C; B and C belong to line a. But then, according to AC3, planes D and E coincide. Axiom A3 follows from AC6. 17. There are n points on a line in affine space. How many points are there in space? How many lines? How many planes? Solution. As already proven in Problem 16, every plane is affine, and in every affine plane there are $n^{2}$ points. Let's take one of the planes D. There is another point A in space (why?). Through point A and point C on plane D we draw a straight line with n points on it. Through each point of these n there passes a plane parallel to the given one, at each of which there are $n^{2}$ points. Therefore, the total number of points in space is $n^{3}$. You can prove that there are no more points in the same way as was done in problem 6. Let's count the number of lines. Let there be k straight lines through each point. Each of them has n 1 points; they all pass through $n^{3} 1$ points. So, $k n 1 n^{3} 1$, therefore, $k n^{2} n 1$. Total points $n^{3}$, each line passes through n points, which means total lines

k  $n^{3} n$

$n^{2} n^{2} n 1$

$n^{4} n^{3} n^{2}$.

⟦folio 18⟧

K VA N $T_{2023/№5}$

tori will not work - although dielectrics conduct current, their resistivity is too high (at school it is considered infinitely high). Semiconductors have a lower resistivity, and it would be convenient for production, controllable, i.e. with small changes in composition it will change significantly. However, it strongly depends on temperature, and this is obviously bad - any equipment must be operational when operating conditions change, primarily the ambient temperature. And the easier it is to ensure the stability of the equipment, the more stable the parameters of the elements, including resistors. But semiconductors can be used as thermometers; we will return to this issue later. Conductors remain, but their resistivity, on the contrary, is low. Resistors with small resistances can be made from ordinary conductors, but what if you need high resistance? The R U L S formula says that there are two ways to solve a problem - long and thin, but not a path, but a guide. A kilometer-long conductor is inconvenient; micron wire can be made, but working with it is also difficult, and the resistance is not high enough. But you can make a small cross-section not only with wire; there are two more methods - thin films and cermets. Let's start with films. True, it is difficult to make films micro- and nanometer-thick and inconvenient to work with. But when people in physics and engineering say “thin film,” they almost always mean on a substrate. For example, a thin film of conductor deposited on a dielectric substrate makes an excellent resistor. A film of any thickness can be deposited in a vacuum or in a gas discharge. However, at very small thicknesses, electrons begin to scatter not only on lattice ions, but also on the surfaces of the film, and at even smaller thicknesses, the film can lose, as they say, continuity, turn into separate piles of atoms (island film) and electrons will jump from island to island. But getting big

⟦column⟧

⟦figure⟧

Fig. 6. Fixed resistors

The resistance of the resistors does not interfere with all these miracles. By the way, the expression “loose films” is used for thin films without substrates. It's time for us to look at the object of our story. In the photo at figure 6 there are several different film resistors. In the first row are resistors, the resistance of which is determined with very high accuracy, it is written on them. In the second row on the left is an exotic resistance, and the question is: why is there an accordion there? Moreover, the obvious answer is incorrect. This obvious answer is true for the resistance on the right, on which the conductive coating is cut through in a spiral. In the third row there are several resistors, the resistance of which was changed (they say “adjusted”) after painting. In the next picture (Fig. 7) there are ultra-high resistance resistors (upper $–^{10}$ GOhm), resistive film - carbon, the manufacturer soldered them into glass, since the resistance of the paint (connected essentially in parallel with the entire resistor) would not be high enough. Pay attention to the white terminal panel on the left - it is made of Teflon or PTFE-4, a dielectric with a record high resistivity. By the way, regarding these resistors and paint, there is another problem. For simplicity, let the thickness of the resistive film and paint be the same. How many times the resistivity

⟦folio 21⟧

P R O B L E

However, the only widely used method is strain gauging. To measure deformations, a wire is glued to the object we are examining and its resistance is measured. When the size of an object changes, the length of the wire, its cross-section and the resistivity of its material change. Therefore, the resistance that we measure changes. To measure pressures in gases, liquids and solids, a wire is placed in the medium under study or inside the object... you already know the rest. And don't forget to electrically isolate the wire from the object. As for our main reason for resistor instability, i.e. dependence of resistivity on temperature, then in school they usually say that this dependence is linear, and they also mention superconductivity. The real situation is much more complicated, and therefore more interesting. The dependence of resistance on temperature is not linear, and in addition there may be jumps at temperatures when the lattice is rearranged. figure 8 shows a graph of the thermal expansion of iron. The arrows indicate the Curie point (loss of ferromagnetic

Fig. 8. How iron expands

RESPONSE HISTORY

⟦column⟧

properties), two lattice rearrangements and a melting point. The table shows a list of iron phases and transformation temperatures (bcc - body-centered cube, fcc - face-centered cube). The temperature range is given because different sources have slightly different data. Either the impurities were different, or the rate of temperature change, or hysteresis... polymorphism is a delicate matter! The character in the film “White Sun of the Desert” also thought so. And something else interesting is depicted on figure in the lower right corner, there is something exotic, hexagonal, densely packed. But what should we do with the dependence of resistance on temperature? Resistor developers are not too interested in whether the dependence of resistivity on temperature is linear or non-linear; it is important for them to weaken this dependence. The method is known, it is even mentioned in some school textbooks - you need to use alloys, not metals. In metals, electrons are scattered by vibrations of lattice ions, and the resistance depends on temperature because the amplitude of these vibrations increases with temperature. In alloys, additional electron scattering occurs on lattice inhomogeneities, so the resistance increases and becomes less dependent on temperature. But what should you do if you want the resistance to change with temperature not as weakly as has been achieved today, but

⟦folio 24⟧

K VA N $T_{2023/№5}$

R – resistance, k – naturally, Boltzmann’s constant, T – temperature, ‘ f – frequency range. Now you know why radio telescope receivers are cooled. This formula is universal, and it seems that all resistors under the same conditions should make the same noise. Meanwhile, the noise of resistors is standardized, they are indicated in the technical specifications, and there are low-noise resistors. The fact is that there is another source of noise. Noise is a chaotic process, its source is random events. What random events are there in a resistor? Firstly, the coordinates of electrons are precisely the source of thermal noise. Secondly, these are the coordinates of atoms, and this is a source of resistance that can change and fluctuate. Please note that this source also depends on temperature, but it only appears in the presence of current (voltage requires current in addition to resistance). Further, both in the electronic and atomic subsystems there can be group movements and waves. Waves in the electronic subsystem are called charge density waves, waves in the atomic subsystem are sound vibrations (phonons), dislocation movements and movement of boundaries between crystals (if the object is not single-crystal). If these factors are random, then they can be a source of noise. The resistivity of a homogeneous conductor depends on the concentration and mobility of electrons (you know this from school), and fluctuations in these quantities cause fluctuations in resistivity and, therefore, noise - but only when current is passed through. And lastly, if the resistor material is not homogeneous, if these are separate conductive particles happily in contact with each other, then these contacts can appear and disappear, and this will certainly cause resistance fluctuations, which, naturally, appear only in the presence of current. All such noise is called current noise, although it still depends on temperature.

⟦column⟧

And now you will learn something terrible that relates to all physics. When studying a phenomenon, we try to separate influences, factors, ways of interaction - as we have done now. Noises were divided by sources and mechanisms. We did the right thing, but... but somewhere in the depths of our consciousness a “yellow light” (or rather, an LED) should be burning - a signal of alertness. Separate, we separated them beautifully, but don’t they interact? Don't they influence each other? In our case, we can give an obvious example of influence. Do some waves influence each other, is Auguste Coulomb involved here? The next problem is electrotransfer, or electromigration. Electrons in a conductor are accelerated by the field and decelerated by the lattice ions, which means they transfer momentum to the ions. In addition, when current flows in a conductor, there is an electric field, and it acts on ions and electrons. However, neither the impulse transmitted by electrons to the ions, nor the field acting directly on the ions causes the movement of the conductor as a whole - because the conductor as a whole is neutral. But the effect on different ions may be different, and this is significant in at least two cases - if we are dealing with an alloy or with contact of two different metals. In electronics, both are not found at every step, but more often - at every pin of every part and every microcircuit. Because the output is made of one metal, covered with another, we solder it third to the track, which is also made of something. The consequence is that at the contact of two metals, ions can creep from one metal to another, the cross-section of the conductors changes, and where it is smaller, overheating occurs. And the end comes - i.e. end of service life. The situation is aggravated by the fact that even in pure metal the ions are not exactly the same. First, there are isotopes. Secondly, some ions are located inside crystals, others are at the boundaries between them. Thirdly, some are on the surface, others are inside. And any of these differences can lead to electrical

⟦folio 27⟧

P R O B L E

RESPONSE HISTORY

⟦column⟧

⟦figure⟧

Fig. 16. The resistive element is movable, but the contact does not crawl from turn to turn, but slides along the wire

⟦figure⟧

Fig. 14. Unusual variable resistor

The resistor is at $рисунке^{14}$ to increase the control range, i.e. to expand the control range in the area of ​​small values, the resistive element is made of three parts, with different dependences of resistance on the angle of rotation. The first section is made of copper tape, the second is made of resistive tape of a smaller cross-section, and the third is made of resistive wire of a smaller cross-section. The next two $рисунка,^{15} и^{16,}$ illustrate the relativity of motion. Usually the resistive element is stationary, in these two cases, on the contrary, it is movable, and in the second case the movement is organized in such a way that the discreteness of the turns does not matter, since the contact slides along the wire. This last option can be considered the forerunner of multi-turn potentiometers, in which, however, the resistive element was stationary.

⟦figure⟧

Fig. 17

And in conclusion - a little about beauty $(рис.^{17).}$

Fig. 15. The resistive element is moving
