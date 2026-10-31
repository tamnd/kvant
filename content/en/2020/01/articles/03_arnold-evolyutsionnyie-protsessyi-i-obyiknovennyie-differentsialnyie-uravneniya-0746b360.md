---
id: 2020-1-arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-0746b360
issue: kvant_2020_1
year: 2020
number: "1"
title: Evolutionary processes and ordinary differential equations
authors:
  - Арнольд В. И.
rubric: osnovnye-stati
page_first: 31
page_last: 43
page_labels: 30, 41
tag: JIJ9
lang: en
source: kvant_digital
extraction: native
content_sha256: 8981f3b88e948090608052f9494f3fc6a2302ee90654185b9e311a606cfc1446
prompt_sha256: draft-1
translated_from: content/ru/2020/01/articles/03_arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-0746b360.md
source_content_sha256: 67cf87b65ede8212b0a7f56c54b66555a281c86feb63fd127b2b9e0be593b565
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Evolutionary processes and ordinary differential equations

V. ARNOLD

The equation was very complex, but the professor, with his characteristic modesty, called it ordinary. From a newspaper interview with a mathematician

DIFFERENTIAL EQUATIONS are one of the main tools of mathematical science. They were invented by Isaac Newton (1642–1727). Problems that essentially lead to differential equations appeared before Newton. However, only such geniuses as the President of the French Academy of Sciences X. Huygens (1629–1695) and Newton’s teacher, mathematician and theologian, preacher of the English king I. Barrow (1630–1677) were able to solve them. After Newton, any students and even schoolchildren solve them. Newton considered his invention so important that he encrypted it in the form $анаграммы^{1}$, the meaning of which in modern times is

1 6accdael3eff7i3l9n4o4qrr4s9tl2vx. Explanation: data aequatione quot cunque fluentes quantitates invuolvente fluxiones invenire et vice versa, i.e. “for a given equation containing any number of functions, find the derivative and vice versa.” This anagram is contained in Newton's famous “second letter” to Oldenburg, secretary of the Royal Society (English Academy of Sciences), dated October 24, 1676. The letter was intended for Leibniz (1646–1716) and contained a message about the invention of mathematical analysis. Newton conducted correspondence with Leibniz, who lived in Germany, through Oldenburg (who was later imprisoned in the Tower for contacts with foreigners).

Published in «Kvant» No. 2, 1986.

⟦column⟧

In practical terms, it can be loosely expressed as follows: it is “useful” to solve differential equations (since they express the laws of nature). In another, longer anagram, Newton also encrypted the recipe he invented for solving all equations, including differential ones. The theory of differential equations transforms questions of natural science into geometric problems about curves defined by vector fields (see below), just as Cartes' method of coordinates turns questions about algebraic equations into problems about lines and surfaces.

Process states

To study any process, you must first of all be able to describe the many possible states of this process. Let's see how this is done with examples. 1. Movement of a point in a straight line. Experience shows that to determine the movement

Fig. 1. Movement in a straight line

⟦folio 30⟧

KVANT 2020/№1

To move a material point along a straight line in the absence of external forces, it is enough to set its speed and position on the straight line at the initial moment. Therefore, the mathematician identifies the set of all its states with the coordinate plane s; v: each point on this plane corresponds to a material point moving with speed v and occupying a position with coordinate s, and vice versa - each state corresponds to its own point on the plane (Fig.1). 2. Oscillations of the pendulum. The state of a flat pendulum is also described by two parameters, for example, the angle of deviation T from the vertical and the angular velocity Z of the pendulum (Fig.2). Therefore, many

⟦figure⟧

Fig. 2. Oscillations of the pendulum

What state of the pendulum will again be a plane? Not really. The fact is that when the angle T changes by 2S, the pendulum returns to its previous position. Therefore, the set of states here is a cylindrical surface (see Fig.2). 3. Position of carts on two roads. Cities A to B are connected by two non-intersecting roads, on each of which there is a cart; we are interested in their relative position. The position of the cart on the first road (Fig.3) can be determined by the number -

Fig. 3. Problem of two carts on two roads

⟦column⟧

the fraction of the distance from A to B (along the first road) enclosed between A and the cart; similarly, the load on the second road is determined by the same share on the second road. Therefore, the set of states that interests us is described by points x; y unit square ( 0 d x d 1, 0 d y d 1 ). Sets of process states in the theory of differential equations are called phase spaces. So, each point of phase space (phase point) depicts the state of the process. And the flow of a particular process itself is depicted by a line in phase space; these lines are called phase trajectories. The introduction of the phase space of the process geometrizes the theory - questions about the course of the process turn into questions about the behavior of phase trajectories. The resulting geometry problems can be difficult. However, it also happens that the mere introduction of phase space allows one to solve a difficult problem. Problem (N.N. Konstantinov). Two non-intersecting roads lead from city A to city B. It is known that two cars traveling along different roads from A to B and connected by a rope of some length less than 2l were able to drive from A to B without breaking the rope. Can two round carts of hay of radius l, the centers of which are moving towards each other along these roads, pass without touching? The phase space here is the unit square. The initial position of the cars (in city A) corresponds to the lower left corner of the square, and the movement of cars from A to B is depicted by a curve leading to the opposite corner (see Fig.3). In the same way, the initial position of the carts corresponds to the lower right corner of the square, and the movement of the carts is depicted by a curve leading to the opposite corner of the square (upper left). But any two curves in a square connecting different pairs of opposite vertices intersect. Therefore, no matter how the carts move, a moment will come when a pair of carts will take the position in which the pair of cars was at some point in time. This

⟦folio 41⟧

PROBLEM WORKER

a graph of the voltage across the load to which the source is closed versus the load resistance. Let's connect a resistor with resistance R to the source. The voltage across the load is related to the current by a simple ratio: $U_{н} RI$. On the same figure, where the dependence U I of the source voltage on the current through it is depicted, we will draw a straight line $U_{н} RI$. The intersection point of the graph U I and straight line $U_{н} RI$ will give us the required current and voltage. For a conventional source, in which the voltage at the terminals is lower, the higher the current, no more problems arise - there is only one intersection point and the result is determined unambiguously. But for an unusual source, in which in a certain area the voltage increases with increasing current, there is a range of values ​​of R in which there are as many as three intersection points. It is clear that the current cannot have three values ​​at the same time; This means that this area needs to be dealt with separately - a convenient graphical method for finding the current in a circuit is clearly not suitable here. Let's first connect a resistor with a very high resistance to the source, and then gradually reduce the resistance. The initial current in the circuit will be very small, and as the resistance decreases, it will increase. On

⟦figure⟧

Fig. 2

figure 2 this mode corresponds to the section ab, in which the values ​​of U and I U ​​change from $U_{a} = 20$ V, $I_{a} = 0$ to $U_{b} | 10$ V, $I_{b} | 120$ mA. Each point of this section corresponds to a stable

"QUANTA"

⟦column⟧

state (small changes in current in a circuit lead to changes in voltage, which tend to compensate for changes in current; this is typical for all “normal” circuits). With a further decrease in R, the mode changes abruptly from $U_{b}, I_{b}$ to $U_{c} | 22$ V, $I_{c} | 260$ mA, and then again to the “stable” mode (to the right of point c along the U I curve). If we start with small resistor resistances, then as R increases we will reach point d (Fig.3), then there will be a jump from $U_{d} | 23$ V, $I_{d} | 210$ mA to $U_{e} | 8$ V, $I_{e} | 80$ mA and again along the U I curve to point a.

⟦figure⟧

Fig. 3

But what if you take a resistor whose resistance lies in the region of 80 Ohms < < R < 100 Ohms (the value of R | 80 Ohms corresponds to points b and c on figure 2, the value of R | 100 Ohms corresponds to points e and d on figure 3), and connect it to the source? What will be the voltage and current in the circuit? To answer this question, you need to know such circuit parameters as the inductance of the wires and the capacitance between the resistor terminals. If, for example, the inductance of the wires is large (long wires), and the capacitance between the wires is small, then at the moment the resistor is connected to the source, the current will be small (the influence of inductance), and then it will increase - the mode in the circuit will be established in accordance with figure 2. If the capacitance between the wires connected to the source is large, and the inductance of the wires is small, then at the first moment the current will be large and will become
