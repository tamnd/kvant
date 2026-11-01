---
id: 1987-7-hilkevich-zaytseva-kak-postroit-traektoriyu-0026def0
issue: kvant_1987_7
year: 1987
number: "7"
title: How to build a trajectory?
authors:
  - Хилькевич С. С.
  - Зайцева О. А.
rubric: raznoe
page_first: 28
page_last: 32
page_labels: 26, 28, 29, 30
tag: DGVW
lang: en
source: kvant_digital
extraction: vision
content_sha256: e7a7ec295611730ff9076c6cf6695b1bf89327404c0331b6d2a229a15c307506
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/07_hilkevich-zaytseva-kak-postroit-traektoriyu-0026def0.md
source_content_sha256: 6abe958734e9192f4001adcf90e72d762fc3d895ad872f9e453f928e5148c886
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

HOW TO BUILD A TRAJECTORY?

The need to calculate the trajectory of a particular human movement is encountered very often. This problem arises both before an Australian aborigine sneaking up on a flock of birds with a boomerang, and before a mathematician calculating the location of a spaceship.

In this article we want to talk about one method for approximate construction of trajectories of complex movements, illustrate it with specific examples and offer the reader several games that are based on this method.

Let's start from the beginning

Not afraid to start, and I’m still finishing.
Before you finish reading a fairy tale, don’t point.
V. Dal. Proverbs of the Russian people

The main idea of ​​the method is very simple and is based on the well-known relationship connecting the displacement vector of a material point with the vector of its average speed. Let us recall that the average speed $\vec{v}_{\text{cp}}$ of uneven movement is called a physical quantity equal to the ratio of the movement $\vec{s}$ of the body over a certain period of time $\Delta t$ to the duration of this interval:

$$\vec{v}_{\text{cp}} = \frac{\vec{s}}{\Delta t}.$$

From here

$$\vec{s} = \vec{v}_{\text{cp}} \Delta t.$$

Both average speed and displacement are vector quantities, so in the figures they are depicted as directed segments. In this case, the directions of both vectors are the same, but the lengths differ by $\Delta t$ times. Obviously, with an appropriate choice of scale, it is possible to make the directed segments depicting the average speed and displacement coincide

$$\vec{v}_0$$

Fig. 1.

completely - both in direction and in length. It is this circumstance that makes it possible to quickly and somewhat construct, of course, approximation, various trajectories.

Let us first consider the simplest case—uniform rectilinear motion. Let at the initial moment of time the body be at point $A_0$ and have speed $\vec{v}_0$ (Fig. 1). Since (as we agreed) the displacement vector over the time interval $\Delta t$ coincides with the velocity vector, then after this interval the body finds itself at point $A_1$, at which the initial velocity vector $\vec{v}_0$, delayed from $A_0$, appears. Depositing another vector $\vec{v}_0$ from point $A_1$, we obtain point $A_2$, at which the body ends up after two intervals $\Delta t$. Continuing this procedure, we obtain a sequence of points $A_n$ at which the body will be located after $n$ selected time intervals from the beginning of the movement. Taking, passing through these points is the trajectory of uniform rectilinear motion.

Method generalization ideas

They were the first to consider a generalization of CRA to the case of a “multi-handed player,” i.e., a player with more than two hands.

From the collection “Mathematical Flower Garden”

The case of uniform rectilinear motion discussed above is the simplest, but the main idea of ​​the method remains unchanged in more complex situations.

The idea of ​​the method is as follows.

To approximate the construction of the trajectory, we divide the entire time of movement of the body into small intervals *),

*) Depending on the conditions of motion, the duration of a “small” interval can vary from fractions of microseconds to billions of years. It is only important that it be much less than the duration of the process in question.

⟦folio 28⟧

point $A_3$. The body will end up in it after the interval $\Delta t$ after passing the point $A_2$, etc. The construction gives an approximate trajectory - a broken line, which is similar to the well-known parabola, which is the true trajectory.

The solution to this problem does not seem particularly special, since the answer was known in advance from a school physics course. Moreover, comparing the obtained result with a known one allows you to check the method, and verification is always useful.

Now we are ready to consider a more complex problem, not studied in school, about the movement of a body in a gravity field in the presence of air resistance. Let at the initial moment of time the body be at point $A_0$ and have a speed $\vec{v}_0$ (Fig. 4), and the air resistance force $\vec{F}_c$ is related to the body velocity vector $v$ by correspondence $\vec{F}_c = -\alpha \vec{v}$ (α is a constant coefficient). It is necessary to establish what the trajectory of the body will be in this case.

The acceleration $\vec{a}$, caused by two fusions - gravity and resistance, can be determined from Newton's second law. However, for construction it is more convenient to represent acceleration $\vec{a}$ as the sum of two components: acceleration $a_t = g$, imparted by gravity, and acceleration $\vec{a}_c = \vec{F}_c / m = -(\alpha / m)\vec{v}$. If you depict the dependence of $a_c$ on $v$ in the form of a graph, then from it it is easy to determine the magnitude of the acceleration $\vec{a}_c$ for any value of the body speed. For example, this acceleration is always opposite to the direction of the velocity vector $\vec{v}$.

Let's start building the trajectory. After a short period of time $\Delta t$ after the body began to move from point $A_0$ (see Fig. 4), it ends up at point $A_1$. To construct the velocity vector in the next step, you need to turn off the initial velocity vector $\vec{v}_0$ from point $A_1$ and add the acceleration vector $\vec{a} = \vec{g} + \vec{a}_c$ to it (we already know how to construct vectors $\vec{g}$ and $\vec{a}_c$ separately). As a result of the construction, we obtain point $A_2$ - the new velocity vector will be directed to it. Thus, after two periods of time after the start of the body’s movement, it will end up at point $A_2$.

Repeating this procedure, we get the point $A_3$, at which the body will end up after another interval, then the points $A_4$, $A_5$, etc. Note that the acceleration $\vec{a} = \vec{g} + \vec{a}_c$ after each period of time must be determined again, since the component $\vec{a}_c$ depends on the speed and therefore does not remain constant during the movement.

The broken line passing through the points $A_0$, $A_1$, $A_2$, ..., represents an approximate flight trajectory of the body in the presence of air resistance. The peculiarity of this curve is that, unlike a parabola (see Fig. 3), it is not symmetrical relative to the vertical passing through the point of flight: the outgoing branch of the trajectory is more circular than the ascending one. Now look at the mockup we made from the badminton textbook*) figure 5, which shows the flight paths of the wave for various serves. Do you see?

Almost all trajectories have a noted feature - they are asymmetrical. This is used very widely in sports basimenton. A high serve, for example, is usually served as high as the height of the ceiling and the strength of the player allows—at the same time, on the back line of the opponent’s field, the shuttlecock falls almost vertically, and a returning shuttlecock cannot be hit back strongly, since the plumage gets in the way.

Now the conditions of condensation are natural, adding, for example, another force acting on the body. Providing

*) Rybakov D. P., Shtilman M. I. Fundamentals of sports base. (M., Physical Culture and Sports, 1978.)

⟦folio 29⟧

It turns out that this allows us to consider a very beautiful problem about...

Here we advise the reader to stop reading for a few minutes, fold a piece of paper into an “airplane” and show the tricks it does in the air when it is launched at different speeds and at different angles to the horizon. Firstly, this gives you the opportunity to relax a little, and secondly, after such experiments you will be much more interested in reading what is written next.

How does a paper airplane fly?

Nothing can be said here in advance. And this, of course, is the most interesting!

A. A. Mill. Vinits-Pooh and all-all-all

The experiments carried out have probably convinced you that a paper airplane behaves in flight in a much more complex and interesting way than a thrown stone or a badminton shuttlecock. Then throw it strictly horizontally all the time, then, depending on the initial speed, it either dives almost vertically to the floor, or soars up to the ceiling. It is almost impossible to guess the trajectory of its flight in advance, but this does not mean that the behavior of a wallet tumbling in the air cannot be analyzed.

The problem of the flight of a paper airplane is part of a more general problem of the uncontrolled flight of a non-motorized aircraft. This problem was first posed and decided to be replaced by the Russian scientist, founder of aerodynamics N. E. Zhukovsky (1847-1921). Here we will analyze only that version of the problem, which Zhukovsky himself called the “glider problem.”

Let a symmetrical glider (Fig.6) fly in the air. Three forces act on it: gravity

$$\vec{F}_T$$, drag force $$\vec{F}_c$$ and lift force $$\vec{F}_n$$. The force of gravity $$\vec{F}_T = m\vec{g}$$ is variable in magnitude and is always directed vertically downwards. The drag force of the connection with speed $$\vec{v}$$ corresponds to $$\vec{F}_c = -\alpha \vec{v}$$, i.e. exactly the same as in the previous case. The lifting force lies in the vertical plane and is directed perpendicular to the velocity vector, and its magnitude, according to the so-called. Zhukovsky's theorem is related to speed by the correspondence $$\vec{F}_n = \beta v^2$$. All three forces are applied at the center of mass, which is located in the vertical plane of the symmetrical airframe. The question is, what will the flight trajectory be if the glider is launched from point A₀ with an initial speed $$\vec{v}_0$$ at an angle φ to the horizon (Fig. 7)?

The trajectory is constructed in exactly the same way as before, only now to find the total acceleration you will have to add not two vectors, but three: $$\vec{g}, \vec{a}_c$$ and $$\vec{a}_n$$, where the acceleration $$\vec{a}_c = \vec{F}_n/m$$ caused by the lifting force is directed perpendicular to the velocity vector $$\vec{v}$$ and is equal to ($\beta/m)v^2$ in magnitude. To simplify the construction, it is useful to use those given in figure 7 graphs of the dependence of $$a_c$$ and $$a_n$$ on $$\vec{v}$$.

Constructing the glider trajectory, as you can see, although cumbersome, is not complicated. Look at what an amazing curve we got! Our glider described a real “dead loop”! In this case, there is only one loop, but in principle the glider can describe several such loops, after which it goes into the characteristic “fluttering” loop mode: it either falls down, then gains altitude again and, gradually reducing the amplitude of such “dips,” levels out its flight and moves evenly along a certain inclined straight line.

⟦folio 30⟧

So, we have constructed a trajectory and obtained a description of the most characteristic features of the flight of a symmetrical glider, despite the fact that it is impossible to translate the exact solution of the glider problem (the solution of a complex system of differential equations) into a language understandable to a schoolchild.

The observant reader will probably notice that the paper airplane differs in some respects from the ideal glider we considered. For example, an airplane may not be perfectly symmetrical: it may have different gravity, lift and air resistance forces acting on the right and left wings. This leads to the fact that in the flight of one wing of the aircraft will be located higher than the other, and the plane begins, as if on an inclined plane, to “slide” towards the lowered wing.

With such a transverse “slip”, the nose and tail of the aircraft will experience unequal air resistance forces, so the plane begins to turn around a vertical axis, i.e., it will not fly straight forward, but turning to the right or left. In short, in addition to our consideration of the “tumbling” and “fluttering” of the glider in the vertical plane, we add turns to the right or left.

Since different types of forces acting on an airplane depend differently on speed, the radius of the turn and even its direction will also depend on speed. The behavior of airplanes that turn to the right at high speeds and to the left at low speeds turns out to be especially interesting. Launch several of these airplanes of different types, get used to their flight - and you will see that much of their behavior will now be more understandable to you.

In principle, using the described method, even more complex problems associated with the improvement of aircraft can be considered. For example, an airplane flight. To do this, just remember that an airplane is the same glider, only with an engine. Therefore, adding to the forces trem considered in the problem of a glider, a constant in magnitude of the thrust forces moving $\vec{F}$, directed along the velocity vector, we will be able to construct the flight path of the aircraft. If we imagine that a pilot sits in the cockpit of this aircraft and controls the engine and elevator (i.e., changes the values ​​$\vec{F}$ and the parameter $\beta$), then we can even simulate the rise of the aircraft in controlled flight. By periodically turning on and off the engine of such an aircraft, a patient reader can relatively easily ensure that the aircraft goes into a wave-like flight mode, reminiscent of the flight of tits, swifts and other small birds. And by changing the mass $m$ in this mode and increasing the parameters $\alpha$ and $\beta$, you can obtain trajectories that will quite accurately reproduce the xaotic possibility.
