---
id: 2024-5-6-ashkinazi-kto-nas-hranit-0c0e192e
issue: kvant_2024_5-6
year: 2024
number: 5-6
title: Who protects us
authors:
  - Ашкинази Л. А.
rubric: osnovnye-stati
page_first: 4
page_last: 12
page_labels: 3, 3, 4, 6, 7, 10
lang: en
source: kvant_digital
extraction: vision
content_sha256: c555f96444cb26e217482a7c73186f907e1b5a0f0df5944a15611492bef3c64d
prompt_sha256: draft-1
translated_from: content/ru/2024/05-06/articles/03_ashkinazi-kto-nas-hranit-0c0e192e.md
source_content_sha256: 1a96643ebe7b4b33637a45a121fd81bb6d3919b16dbcbd01e4541ed258e3eae9
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

L.ASHKINAZI

Why are fuses needed?

The considered physics of the operation of technical devices is useful - we see the practical application and connection of various physical laws. This makes it easier to study and remember both physics itself and its practical applications. However, with this approach, it is advisable to observe three restrictions. The devices that we will consider should be at least somewhat familiar to us. The physics we will use should be mostly school level; higher levels are possible, but there should be little of it. When analyzing the operation of any device, we can get to too complex material, and (if only simply because the volume of articles is limited) we will either have to stay in this place or take some of the author’s statements on faith. But even in these cases, the boundary between what we understood and what we simply believed must be clearly indicated.

Let's start with an item we all have at home - an electrical fuse. This is a device that breaks the power circuit when the current consumption increases significantly, i.e. disconnects us from the electrical network. Let’s assume that one of our electrical appliances has broken down, so much so that it begins to consume significantly more current from the network than it should. The consequence is that it began to consume significantly more power (under what conditions will this occur?), and this is almost certainly associated with further destruction of the device itself, as well as heat generation and, possibly, a fire. In addition, abnormally increased consumption may be harmful for some devices,

DOI: https://doi.org/10.4213/kvant20240501

which are connected to the network before the fuse. So the fuse will indirectly protect them too.

Fuses are used both in everyday life and in industry, and they can be divided into two groups. Some of them are located in a specific device and protect only that device. Others are located closer to the power source, and there are several more devices behind them. For example, in everyday life these are fuses that protect an apartment or part of it, or the entire entrance to a house. The parameters of the fuse depend on who it protects, and it is clear that the fuse protecting the entrance is rated for a higher current than the quartile fuse. The principles of its operation and its physics depend on the parameters of the fuse. At least six options are known - some we will consider in detail, some we will only mention.

The main characteristic of a fuse is the dependence of the time it takes for it to break the circuit on the current that flows through it. It would seem that the ideal situation is that there is a certain nominal current value that it can pass for an infinite time, and at any excess it must equalize the circuit, and as quickly as possible. However, this is not so - there are loads with “inrush current”, when the current when the load is turned on for the first instant is greater than the set value, and the fuse must treat this with help. For example, in an incandescent lamp, the tungsten filament in operating mode is hotter than before it was turned on, and has a resistance greater than when it is cold. Therefore, when turned on, there is an active current surge, but it lasts for milliseconds. (You can estimate this time by considering that

⟦folio 3⟧

---
running_head:
folio:
---

the power consumption is constant and all the energy goes to heating, and then think about how to refine this estimate.)

Electric motors also have an inrush of current when turned on, in which the starting current (unless special measures are taken to reduce it) is 3-7 times greater than the stationary current, but it lasts longer - until the motor spins up. But an electric kettle does not have a surge of current when turned on, although there is a heater there and in operating mode its temperature (naturally, in Kelvin) is several times higher than when it is turned off. (Why do you think?) Of course, this does not mean the body of the heater, which is in contact with water, but the nichrome spiral, which is located deep in the heater. It is separated from the heater body by high temperature magnesium oxide MgO insulation.

But this is a situation related to the load, and the network power parameters may also be significant for the operation of the fuse. For example, if the energy source has a high inductance, then you should not cut off the current very abruptly. According to the formula $\mathcal{E} = L(\Delta I/\Delta t)$, when you try to sharply change the current, high voltage will arise with all sorts of bad consequences, including breakdown of insulation or the occurrence of an electric arc. In electrical engineering, this effect is called “extra-opening current.” The bottom line is that it would be nice to be able to open the circuit with a fuse not as quickly as possible, but exactly as needed in each specific case.

Circuits come in direct and alternating current, the latter being of different voltages and different frequencies. For example, the current in such a network depends on time according to a sinusoidal law. And if a short circuit occurs at a time when the voltage and current are low, the fuse should not wait 5 ms for the current to increase to the maximum with the maximum position, it should break the circuit earlier. Of course, you understand where the number 5 ms comes from? Yes, depending on the network frequency, from 50 Hz.

Fig. 1. Fuses in the apartment

The fuse has other important parameters. Some types of fuses need to be replaced after blowing (we will look at this one first), some have the ability to be restored after blowing (press a button and everything turns on). An important parameter is the operating voltage, i.e. one in which at the moment the circuit breaks, when all the voltage is applied to the gap in the fuse, an arc will not light up in it (which will close the target and most likely destroy the fuse). It is convenient if the fact that the fuse has been blown is visible from the outside (Fig. 1; the white button is high) and there is no need to guess which of several has blown. And, of course, they have general parameters - cost, size, weight, reliability, service life...

Probably the oldest

This is the so-called “fuse”. Often this is just a wire, the diameter of which is chosen so that it passes a current that is normal for this network and this load, but melts from the current that we consider unacceptable, and in the time we need. It is clear that these two parameters are related and any combination cannot be obtained. However, it is difficult to obtain it by calculation using several kipini.

The first thing you want to do is multiply the power by the time and equate it to the energy required to heat until melting. However, a difficulty arises -

⟦folio 3⟧

---
running_head:
folio:
---

dependence of resistance, and therefore power, on temperature. But we know this dependence, so we can cope. It is more difficult to take into account heat transfer into the air and structural elements. For some controlled conditions, for example, for a horizontal or vertical thread, there are ready-made formulas, but the thread can also be inclined... Further, the surrounding air can circulate freely, or structural elements can interfere with its movement. In practice, it uses wires located both in a free atmosphere and in a relatively thin tube, and sometimes not even wires are used, but tapes, which are not in the air, but immersed in loose powder of silicon oxide SiO₂ or aluminum Al₂O₃. Such a medium is used as an “arc extinguisher” - to prevent the ignition of others with comparative protection, i.e. broken wiring. And it’s not at all clear how to take into account the fact that for comparative fuses the wiring needs to not only heat up, but also melt, and it’s not necessary for the entire wiring to melt. In practice, they use empirical data; figure 2 shows data for one of the fuse types. Two curves connected by vertical arrows show the range of dependence for different copies of the fuse of the same type, designed to protect against currents significantly greater than 100 A, 250 A and 400 A, respectively. It can be seen that the spread in comparative time is of the order of magnitude.

There are clever tricks for rooting a comparative fuse. For example, you can tighten the wiring with a spring or weight, this will accelerate the increase in distance when the wiring breaks and make it difficult for others to ignite. Another technique is to use not wiring, but plates with narrow jumpers (Fig. 3). When overloaded, thin jumpers heat up more quickly, because the rest of the part does not have time to respond with heat from them.

⟦folio 4⟧

---
running_head:
folio:
---

Bimetallic,
those. made of two metals

The term bimetal is used in technology for materials consisting of two metals, and sometimes for structural elements made from such materials. For example, bimetallic foil is a foil made of any metal on which a layer of another metal is deposited.

Let's take two rods of the same length $L$ from metals with different coefficients of thermal expansion $k_1$ and $k_2$, connect them at the ends (or along the entire length) and change the temperature (the same for common rods) to $\Delta T$ (Fig. 4). If they were not connected, they would change their lengths differently. Now they cannot do this and are forced to change their length by some intermediate value, and one turns out to be slightly stretched, and the other is stretched in the same way (according to Newton’s third law). If we know the design of rods $S_1$ and $S_2$, the Young model $E_1$ and $E_2$, then the final elongation $\Delta L$ turns out to be equal to $L\Delta T\left(k_1S_1E_1+k_2S_2E_2\right)/\left(S_1E_1+S_2E_2\right)$. In this case, mechanical stresses will appear in the rods (they are shown by arrows on figure). But bimetallic structures have another solution - they bend. True, in this case it is not possible to get rid of the mechanical stresses, and they will become inconsistent - the “back” of each rod will be stretched, and the “belly” of the stingray will be stretched. But the stress model will decrease, which means that the potential strain energy will also decrease, since the energy includes the square of stress and strain. (You can calculate the radius along which the bimetal will bend yourself. To control the calculated one, use such a model - each rod consists of two halves, and in each half of each rod the stresses are uniform. This technique - replacing a continuous function with a discrete one - generally often leads to a solution, naturally, an approximation.) Well, what follows is, it seems, simple - bending or turning opens the contact.

But we went through a lot of two more service problems, one of which has a solution. This is the “loss of stability” problem. The fact that the curved position is energetically favorable does not mean that the bend begins immediately, as soon as we start heating, it will appear abruptly. The famous problem of the loss of stability of a pitched rod was solved by none other than Leonhard Euler himself. And the second problem, which, as you already understand, the furnace is not solving, is the problem of heating the rods. They can be heated by a separate heater through which current flows, but more often the current can flow through the rods themselves. However, in any case, it is difficult to calculate the temperature - it depends, as for a fuse, on many factors.

However, it is very important that this is a slow fuse - the heating of relatively massive rods is slower than the melting of thin wires. The second important difference is the resettable fuse. After cooling, the fuse contact is restored, and if the fault in the load is eliminated, then everything returns to normal.

Now - electronit

If you are asked in an exam what happens when a current flows, answer that heat is released. There are situations when the tello does not stand out. But a magnetic field always appears, and you can take advantage of it. You, of course, know the formula for the magnetic field induction of an infinite forward current, and in the school textbook it is grayer

⟦folio 6⟧

---
running_head:
folio:
---

there will also be a formula for the field on the axis of the ring -
of the next turn. And it’s easy to get out of it
formula for the field on the solenoid axis. On
this is where the simple ends, because on the axis
solenod there is a piece of iron, it
magnetizes and is drawn into the salty
id, simultaneously clicking on contacts and un-
connecting the current circuit. In this case, the current disappears and
contacts must be closed again -
but after opening they are held
latch in the open position. What-
to close them, it is necessary (previously
having understood what was going on and eliminating the accident,
situation) click on the corresponding
the first button (the white button on the second right
va fuse in the first picture).

Such fuses act quickly
faster than thermal ones, but slower than melting.
And they are recovering. However, myself
such a fuse contains salt-
id, which means it has a small but noticeable
new inductance. From some traces
We will now get acquainted with the result of this.

Spark gap

The current introduced increased and
ry had to be cut off, until what point
was associated with faults on the side
consumer, on the load side. This
tok can increase greatly, but still
limited speed. At least because
that wires go to the consumer, and they have
There is resistance and inductance. WHO-
it is possible, however, a completely different situation,
when nothing καταstrophic happened
on the energy source side, on the side
generator For example, I hit the line
lightning. In this case, the current increases
so fast that the inductance of the magnetic fuse is enough for such a voltage to arise on it that a breakdown will occur in the air. Accordingly, the arc will light up, the fuse will blow
will protect (the arc will protect
solenod), and he himself will unimaginably come out of
standing up To prevent this from happening, a fuse is essentially used, but
ny is the “spark gap”, i.e.
gap between wire and ground or between
wires, designed so that when
serious overvoltage

the gap was broken and the charge flowed into the ground.

By the way, such “fuses” were used at the beginning of the last century, not in electrical engineering, but in radio engineering - to protect radio equipment when lightning struck the antenna. At figure 5 left
shows the antenna switch of those years,
on the right are installation instructions, the “spark gap” is the gap between the teeth.

Spark gaps are also used
now (in case you're interested)
use lightning protection). Situation-
tion is actually quite complex, and it’s
it comes to the point that the power supply circuits of devices are protected not by just one fuse, but by systems of two or three fuses of different types,
than with the agreed parameters. A
some companies develop special
alical fuses specifically for such
applications. There are three reasons for these difficulties.
Firstly, in many cases it is necessary to
sew an object from a lightning strike, but not
turning off the power. Secondly, more
The number of lightning strikes is multiple, on average it is
five pulses after 60-70 ms, and protection -
The circuit must withstand all this and, thirdly, not fail on its own.

Self-healing,
but slowly

The next fuse is a quiet, small and leisurely “self-healing”
becoming a fuse,” that’s what they call it. From an external point of view, it is observed that this is a resistance that remains constant up to a certain current, but if it exceeds it, then after some time the resistance will increase greatly and this will limit the current in the circuit. The increase in resistance is accompanied by heating of the fuse to approximately 80 °C. This fuse is made of a polymer that does not conduct current and carbon particles. When cold, the polymer crystallizes and carbon particles form chains. If too much current begins to flow through the fuse, it begins to heat up, at some temperature the polymer becomes amorphous

⟦folio 7⟧

---
running_head:
folio:
---

WHO KEEPS US

7

Fig. 5. Fuse with arrester
condition, while it increases in size and breaks carbon chains. As a result, the resistance increases so much that the device limits the current. After turning off the power supply to the device for some time and reducing its resistance, the device will restore itself.

The strong point of this device is, naturally, self-healing. Of all the fuses, only arresters have this property, which are usually not considered fuses (they still have a narrow scope of application). Weaknesses - relatively slow comparison, very strong dependence of parameters on ambient temperature and short service life - not in hours, but in comparative quantity. However, as you understand, the soft fuse is smaller.

And finally - the digital kingdom
You’ve probably been wanting to ask for a long time – why not do everything “digitally”. A digital circuit can react to excess current as intelligently as desired and in any time. Yes, of course. But, firstly, electrical engineering arose a century and a half ago, and the transistor appeared only in the middle of this period. And even on Mars, when you land there and create a new civilization, you will start not from scratch, but from the level already available on Earth. Secondly, semiconductor digital technology of the same level that is available with classical solutions is today ten or hundreds of times more expensive. But there is also a trette, a fundamental objection. It is possible to process the signal “digitally” and process it intelligently. But who will break the target?

There are two solutions - a vacuum tube and a semiconductor device. The first solution is effective in the region of high voltages, but not too high currents. Semiconductors are more promising in this sense, but they have voltage limitations. In general, the current situation is this: electronic fuses are produced by many companies, their strengths are the ability to operate at low currents and self-healing, both automatically and in response to an external signal. Over time, the scope of application will probably expand little by little. But the goal is something “analog”.

"Cherry on the Cake"
Of course, you know what a Tokamak is. Well, yes, an international project, ITER, is being built in France, unlimited energy, a bright future... Do you know that its coils are protected by a fuse, and of the first type we examined? Only the comparative ribbons will not melt, but evaporate! This small but necessary miracle is described in detail, for example, in the journal “Instruments and Technical Experiments” (2023, No. 3, p. 46).

⟦folio none⟧

---
running_head:
folio:
---

Let's also call the chromatic number of the hypergraph $H$ of value $\chi(H)$, equal to the smallest number of colors in which all vertices (elements of the set $R$) can be shown so that all edges are undercolored. It is clear that the chromatic number has no meaning if the hypergraph has edges from the same vertex or - horror of horrors! - empty ribs. Therefore, for the sake of justice, we consider that $|A| \geq 2$ for any $A \in M$. Also, the coloring is not affected by multiple edges, and we will not consider them. In new terms, Statement 1 sounds like this: If in a given hypergraph $H$ each two edges have at least two common vertices, then $\chi(H) \leq 2$. Or rather, $\chi(H) = 2$, because we are interested in dealing with a hypergraph in which there is not a single edge at all.

Finally, recall that a hypergraph is said to be $n$-homogeneous if each of its vertices has $n$ edges. An objective graph is a 2-homogeneous hypergraph.

Intersecting hypergraph

We already know that if a hypergraph's edges intersect strongly enough (at two or more vertices), then its chromatic number is two. What if the edges simply intersect in pairs? Such a hypergraph is usually called intersecting. It turns out that an intersecting hypergraph has a chromatic number of at most three!

Statement 2. If the hypergraph $H = (R, M)$ is intersecting, then $\chi(H) \leq 3$.

Now we will prove it by generalizing the idea of ​​proving Statement 1.

Proof of Statement 2. First proceed in exactly the same way as in the proof of Statement 1. Numerum an arbitrary image of the vertices from $R$. We paint the last vertex of each edge red. We make the remaining vertices blue. It is clear that there are no entirely blue ribs. But now there may be entirely red ribs. Let's recolor the last vertex of each such edge green. It is clear that there are still no blue ribs and no red ribs have disappeared either. But what if there is a green edge $A$? Let's look then at his first peak. It is green because there is an edge $B$, which at first turned out to be entirely red and in which this vertex is the last. In turn, the first vertex of the edge $B$ is red first because it is the last in some edge $C$. As a result, we obtain figure 2, from which it is clear that $A$ and $C$ do not intersect. But every two edges have a non-empty intersection. A contradiction arises, and, therefore, in $M$ the green edge is missing. Statement 2 has been proven.

It turns out that for a non-empty intersecting hypergraph the chromatic number can take only two values: 2 or 3. A natural question arises: are there any structural differences between intersecting hypergraphs with a chromatic number equal to 2 and intersecting hypergraphs with a chromatic number equal to 3? Intuitively it might seem that, for example, the number of edges should include the complexity of painting. However, in some cases the picture is the opposite! Indeed, consider a hypergraph in which all edges contain exactly one common vertex, the back flower (Fig. 3). Obviously, you can build as many edge petals as you like, but the chromatic number will always be two. It turns out that the question is that hypergraphs with clique chromatic number 3 cannot have many edges. We'll talk about this in the rest of the stats. And here we also add that, generalizing the proofs of statements 1 and 2, the reader can independently prove the following remarkable sign that the chromatic number of a hypergraph is not greater than a certain number $r$.

⟦folio 10⟧

---
running_head:
folio:
---

Sign of being painted. If there is a numbering of the vertices of the hypergraph $H = (\mathbb{R}, \mathbb{M})$ such that it does not contain an integer edge $A_1, \dots, A_r$ in which the vertex numbers of the edge $A_i$ are less than the common vertex number of the edges $A_i$ and $A_{i+1}$, and the vertex numbers of the edge $A_{i+1}$ are greater than the common vertex number of the edges $A_i$ and $A_{i+1}$ (Fig. 4), mo $\chi(H) \leq r$.

Fig. 4

This sign is, in fact, a criterion, i.e. the opposite is also true. Try to prove it.

Upper bound on the number of edges

It is more convenient and clearer to work with homogeneous hypergraphs. In fact, if we understand how they are structured, we will get some idea about an arbitrary hypergraph, because the set of its edges can always be divided into subsets in which the edges have the same cardinality (number of vertices). Let us prove the following theorem.

Theorem 1. Let $H = (\mathbb{R}, \mathbb{M})$ be an intersecting n-homogeneous hypergraph with chromatic number 3. Then the number of its edges is at most $n^n$.

Proof of Theorem 1. Assume the opposite: $|M| > n^n$. Consider any edge $A \in \mathbb{M}$. Of course, $|A| = n$ and all other edges intersect with $A$. By the Dirichlet principle, find a vertex in $A$ that is contained in more than $n^{n-1}$ edges. Let's take this established fact as the base of induction for the following statement: if $i \leq n$, then find vertices $x_1, \dots, x_i \in \mathbb{R}$ that are simultaneously included in more than $n^{n-i}$ edges. It is immediately clear that if we prove this statement, a contradiction will arise, because with $i = n$ we get $n$ vertices that form more than 1 edge (and we do not have multiple edges). Well, let's make an induction assumption and implement its step. Let for some $i < n$ (here the sign of strict inequality, since this is an induction assumption and this will be important below) such vertices $x_1, \dots, x_i$ and edges $A_1, \dots, A_s$, $s > n^{n-i}$ are found such that for any $k \in \{1, \dots, s\}$ $\{x_1, \dots, x_i\} \subset A_k$ (Fig. 5) is satisfied. Let us show that there is an edge $B$ that does not intersect the set $\{x_1, \dots, x_i\}$. Indeed, otherwise all edges of the hypergraph would have a non-empty intersection with $\{x_1, \dots, x_i\}$. But then we could color the vertices from $\{x_1, \dots, x_i\}$ red and all the other vertices blue. Each edge would have red vertices, since it intersects $\{x_1, \dots, x_i\}$, and each edge would have blue vertices, since $i < n$ and any edge intersecting $\{x_1, \dots, x_i\}$ also have vertices outside $\{x_1, \dots, x_i\}$. Contradiction with what $\chi(H) = 3$. So, there is an edge $B$ satisfying the condition $B \cap \{x_1, \dots, x_i\} = \emptyset$. Like any other edge of a hypergraph, it intersects with all other edges. In particular, it intersects with edges $A_1, \dots, A_s$. Let us again use the Dirichlet principle, according to which we will find a vertex $x_{i+1}$ from $B$ that belongs to at least $s/n > n^{n-i-1}$ edges from the set $A_1, \dots, A_s$. All these edges already contained the set $\{x_1, \dots, x_i\}$, which means that together with the new vertex $x_{i+1}$ they also contain the set $\{x_1, \dots, x_{i+1}\}$. The induction step is done, and Theorem 1 is proven.
