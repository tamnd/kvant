---
id: 1985-4-stasenko-o-funktsiyah-raspredeleniya-849d122c
issue: kvant_1985_4
year: 1985
number: "4"
title: About distribution functions
authors:
  - Стасенко А. Л.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8-10
tag: 7VLW
lang: en
source: kvant_digital
extraction: vision
content_sha256: b1a0982235c561d5eb8fa652819905baa2ebf155a44c2e2a2bb93375ef4d4986
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/04_stasenko-o-funktsiyah-raspredeleniya-849d122c.md
source_content_sha256: 7a055a0f4da95b36e0dfa87fd47e0bd1582365a43159fec3f012b0c16764a2da
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

About distribution functions

(or How to water a garden with the help of the wind)

Doctor of Technical Sciences
A. L. STASENKO

“On the platform, at the end of the train, passengers should be distributed evenly along the length of the train...”
(From the “Rules for using the Moscow Metro named after V.I. Lenin”)

The phrase from the epigraph, the “everyday” meaning of which is completely clear, brings to mind the concept of a distribution function, widespread in physics. We come into contact with distribution functions when solving theoretical and practical problems in which systems with a large number of particles are considered. To draw an analogy between the requirement of the “Rules” and the concept of the distribution function, let us “translate” the epigraph into the language of mathematics.

Let us divide the platform (more precisely, that part of it near which the train stops) sequentially into sections of length $\Delta x_1$, $\Delta x_2$, ..., $\Delta x_k$, ..., $\Delta x_m$. Let us denote the number of passengers waiting for the train at each section by $\Delta n_1$, $\Delta n_2$, ..., $\Delta n_k$, ..., $\Delta n_m$. Then the "Rules" require that the ratio of $\Delta n_i$ to $\Delta x_i$ be the same for any $i=1, 2, ..., k, ..., m$, that is

$$\frac{\Delta n_i}{\Delta x_i} = f_0 = \text{const.}$$

We denoted this relation with the letter $f$ to emphasize that, in fact, it could also be some kind of function of $x$; but in this case, if citizens behave well on the platform, this function should be permanent ($f_0$). On figure 1 its graph is shown - a straight line.

But then the train arrived, and even before the doors of the varons open, “loads” of citizens gather around them. Then their distribution along the platform is no longer uniform, and it can be qualitatively represented in the form of a curve $f(x)$, as in figure 1. If the number of citizens has not changed while waiting for the train, this fact should somehow be reflected in these two graphs. Indeed, while waiting at each section $\Delta x_i$ of the platform, according to (1), the number of citizens was equal to

$$\Delta n_i = f_0 \cdot \Delta x_i;$$

This means that to find the total number of passengers on the entire platform, you need to add up their number on each section. We get

$$N = \sum_{i=1}^{m} \Delta n_i = \sum_{i=1}^{m} f_0 \cdot \Delta x_i = f_0 \sum_{i=1}^{m} \Delta x_i = f_0 \cdot L,$$

where $L$ is the length of the platform. As can be seen from figure 1, $f_0$ L is the area of ​​direct motion $f_0$ and length $L$. And this is the total number of passengers $N$. When, after the train arrived, the distribution on the platform changed and became some function $f(x)$, the sum of all values ​​$f(x_i) \cdot \Delta x_i$ is also the area under the curve $f(x)$ and is still the total number of citizens $N$:

$$\sum_i f(x_i) \cdot \Delta x_i = N.$$

It’s just that the equation $f(x)$ was a constant $f_0$, and in formula (2) we took it out as the sum sign, but now this should not be possible - in each section $\Delta x_i$

⟦folio 9⟧

their number of citizens (they were redistributed).

“Bah! - the mathematician will exclaim (he is simply obliged to exclaim so), - but what is written in (1), in the limit, when the segments $\Delta x_i$ become smaller and smaller, turns into what is called the derivative of $n$ by $x$:

$$f(x_i) = \lim_{x_i \to 0} \frac{\Lambda n_i}{\Lambda x_i} = \frac{dn}{dx},$$

and what is written in (3) is included in the integral of $f(x)$ over the entire length $L$ of the platform:

$$N = \lim_{x_i \to 0} \sum_{i=1}^{m} f(x_i) \Delta x_i = \int_0^L f(x) dx.$$

And if he exclaims like that, he will be absolutely right.

So, the distribution of citizens along the platform while waiting for a train can be described by the function $f(x) = \frac{dn}{dx}$, which is naturally called the function of distribution of passengers along the length of the platform.

Now, perhaps, the reader will exclaim: “Why, in this way the most general velocity of a material point, that is, the derivative of the displacement in time, can be

$$\vec{v} = \frac{\vec{ds}}{dt} = \lim_{t \to 0} \frac{\Delta s}{\Delta t},$$

- called the distribution of point displacements in time; acceleration -

$$\vec{a} = \frac{\vec{dv}}{dt} = \lim_{t \to 0} \frac{\Delta v}{\Delta t}$$

— distribution of speeds over time; and the total density of a substance, that is, the derivative of mass by volume -

$$\varrho = \frac{dm}{dV} = \lim_{V \to 0} \frac{\Delta m}{\Delta V},$$

— distribution of mass by volume!?” All this is true, and yet the word “distribution” carries its own meaning in physics and in everyday life. They talk, for example, about the distribution of gas molecules according to the velocity modulus ($\frac{dn}{dv} \frac{\text{молекул}}{\text{м/с}}$); about the distribution of products among the population ($\frac{dm}{dn} \frac{\text{кг}}{\text{человек}}$), and not about the derivative of the mass of products by the number of citizens; on the distribution of schoolchildren by age ($\frac{dn}{dt} \frac{\text{школьников}}{\text{лет}}$). Probably, somewhere in the 10th grade, this last distribution has the form shown in figure 2: the maximum of the function $f(t)$ corresponds to (approximately) 17 years; is unlikely to occur in the 10th grade of someone (hereinafter very capable) from kindergarten or at retirement age - so the distribution function tends to zero quite quickly on either side of the maximum value.

A very interesting function (especially, probably, for tenth-graders) is the distribution function of applicants according to the number of problems they solved in the entrance exams. As a rule, this graphical function can be represented by either curve I or curve II at figure 3. If it is curve I, then its minimum at point A easily allows one to set the “price” of a satisfactory assessment - everyone who traces from point A does not pass. If this is curve II, then the examiner has to think about how many solved problems are considered sufficient for a satisfactory assessment.

The importance of distribution functions in physics is supported by the fact that

⟦folio 10⟧

That many of them are associated with the changes of wonderful scientists: there are, for example, the Bolshman and Maxwell distributions (gas molecules by speed), the Planck distribution (quantum radiation by their frequencies), the Fermi distribution (electron energy).

Now, having learned to understand the meaning of distribution functions, we will solve one useful problem. Suppose we need to evenly water a horizontal plot of land, say, a large vegetable garden or field. Of course, this can be done with the help of buckets or watering cans, as they say, “on foot”; You can drive between the hailstones on a tractor, the base is a special unit - a transverse pipe with holes and nozzles in which water is supplied (this is how “frigates” are constructed, which can often be seen in the fields). But we will try to use the wind, which almost always blows in large open spaces.

Let's place a horizontal tube equipped with nozzles at a height $h$ above the ground. Through this pipe, water is supplied under pressure, which is “sprayed” into droplets flying in all directions. The radii of the drops can be different, and we can control the set of drops, that is, the function of their distribution over their own radii ($f(r) = \frac{dn}{dr}$).

Our task is to find what function $f(r)$ should be so that the irrigated area is watered evenly (that is, equal masses of water fall on any areas of identical areas).

First of all, we need to figure out how the drops flying out of the pipe will move. Of course, they all have some kind of initial speed; but if the drops are small enough, they will quickly decelerate in the air and, in the absence of wind, will fall under the pipe itself onto a narrow strip of earth parallel to the pipe. To clarify what has been said, consider a drop of radius $r$ ejected from a vertical whizz tube. The movement of the drop subsequently occurs under the influence of gravity $mg$ and the resistance force $f_c$ from the air. The resistance force $f_c$ depends on the speed of the drop and its radius - it is greater, the larger $v$ and the larger $r$, in particular, for small drops $f_c = bvr$, where $b$ is a certain proportionality coefficient. (This force is called the Stokes force - after the English physicist and mathematician of the 19th century J. Stokes, who studied the motion of bodies in a liquid medium. This dependence $f_c(v, r)$ is true precisely for very low conditions with changes by remarkable scientists: there are, for example, the Bolshman and Maxwell distributions (of gas molecules by velocities), the Planck distribution (quantum radiation by their frequencies), the Fermi distribution (electron by energies).

Now, having learned to understand the meaning of distribution functions, we will solve one useful problem. Suppose we need to evenly water a horizontal plot of land, say, a large vegetable garden or field. Of course, this can be done with the help of buckets or watering cans, as they say, “on foot”; You can drive between the hailstones on a tractor, the base is a special unit - a transverse pipe with holes and nozzles in which water is supplied (this is how “frigates” are constructed, which can often be seen in the fields). But we will try to use the wind, which blows almost entirely for the first time in large open spaces.

Let's place a horizontal tube equipped with nozzles at a height $h$ above the ground. Through this pipe, water is supplied under pressure, which is “sprayed” into droplets flying in all directions. The radii of the drops can be different, and we can control the set of drops, that is, the function of the same areas falling into the same masses of water).

First of all, we need to figure out how the drops flying out of the pipe will move. Of course, they all have some kind of initial speed; but if the drops are small enough, they will quickly decelerate in the air and, in the absence of wind, will fall under the pipe itself onto a narrow strip of earth parallel to the pipe. To clarify what has been said, consider a drop of radius $r$ ejected from a vertical whizz tube. The movement of the drop subsequently occurs under the influence of gravity $mg$ and the resistance force $f_c$ from the air. The resistance force $f_c$ depends on the speed of the drop and its radius - it is greater, the larger $v$ and the larger $r$, in particular, for small drops $f_c = bvr$, where $b$ is a certain proportionality coefficient. (This force is called the Stokes force - after the English physicist and mathematician of the 19th century J. Stokes, who studied the motion of bodies in a liquid medium. This dependence $f_c(v, r)$ is true precisely for low conditions with changes by remarkable scientists: there are, for example, the Bolshman and Maxwell distributions (of gas molecules by speed), the Planck distribution (quantum radiation by their frequencies), the Fermi distribution (electron by energy).

Now, having learned to understand the meaning of distribution functions, we will solve one useful problem. Suppose we need to evenly water a horizontal plot of land, say, a large vegetable garden or field. Of course, this can be done with the help of buckets or watering cans, as they say, “on foot”; You can drive between the hailstones on a tractor, the base is a special unit - a transverse pipe with holes and nozzles in which water is supplied (this is how “frigates” are constructed, which can often be seen in the fields). But we will try to use the wind, which blows almost entirely for the first time in large open spaces.

Let's place a horizontal tube equipped with nozzles at a height $h$ above the ground. Through this pipe, water is supplied under pressure, which is “sprayed” into droplets flying in all directions. The radii of the drops can be different, and we can control the set of drops, that is, the function of the same areas falling into the same masses of water).

First of all, we need to figure out how the drops flying out of the pipe will move. Of course, they all have some kind of initial speed; but if the drops are small enough, they will quickly decelerate in the air and, in the absence of wind, will fall under the pipe itself onto a narrow strip of earth parallel to the pipe. To clarify what has been said, consider a drop of radius $r$ ejected from a vertical whizz tube. The movement of the drop subsequently occurs under the influence of gravity $mg$ and the resistance force $f_c$ from the air. The resistance force $f_c$ depends on the speed of the drop and its radius - it is greater, the larger $v$ and the larger $r$, in particular, for small drops $f_c = bvr$, where $b$ is a certain proportionality coefficient. (This force is called the Stokes force - after the English physicist and mathematician of the 19th century J. Stokes, who studied the motion of bodies in a liquid medium. This dependence $f_c(v, r)$ is true precisely for low conditions with changes by remarkable scientists: there are, for example, the Bolshman and Maxwell distributions (of gas molecules by speed), the Planck distribution (quantum radiation by their frequencies), the Fermi distribution (electron by energy).

Now, having learned to understand the meaning of distribution functions, we will solve one useful problem, with a constant speed $u$. It can be shown that in this case, whatever the initial speed of the ejected small drops, they are all quickly drawn into the horizontal speed $u$ and the vertical speed $v = a r^2$. Since both movements of the drop - falling and being carried by the wind - are uniform, all drops will move in straight lines (figure 4).

The travel time to the ground is longer, the smaller the radius of the drop: $t(r) = \frac{h}{v(r)} = \frac{h}{a r^2}$, so small drops (radius $r_1$) will fall to the ground for this source than larger ones (radius $r_2 > r_1$):

$$x(r) = u \cdot t(r) = u \frac{h}{a r^2}.$$ (4)

On what area $\Delta x$ will all drops fall, the radii of which differ from the given one $r$ by a small amount $\Delta r$? Since, as can be seen from (4), $\Delta x / \Delta r = -\left(u \frac{2h}{a}\right) \frac{1}{r^3}$ (we have continued to differentiate the function $x(r)$),

$$\Delta x = -\left(u \frac{2h}{a}\right) \frac{1}{r^3} \cdot \Delta r$$

(the minus sign prepares for a fact we already know: if the radius of the drop is greater than $r$ ($\Delta r > 0$), it will fall closer to the source ($\Delta x < 0$), and vice versa).
