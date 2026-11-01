---
id: 1982-5-tihomirov-aerodinamicheskaya-zadacha-nyutona-8cb1bbc2
issue: kvant_1982_5
year: 1982
number: "5"
title: Newton's aerodynamic problem
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 13
page_last: 20
page_labels: 11, 12, 13, 15, 16, 18
tag: XRGN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 884c6197624f082b710f50155b51b26fcc11891eb739481b6a63710753687eb8
prompt_sha256: draft-1
translated_from: content/ru/1982/05/articles/06_tihomirov-aerodinamicheskaya-zadacha-nyutona-8cb1bbc2.md
source_content_sha256: 34da1702781813b1374252679f69c6c67da865ac3f561fcd467bed2070eb1ddc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 11⟧

V. Tikhomirov

Newton's aerodynamic problem

Do geniuses make mistakes? Usually, when asking such a question, they assume an affirmative answer. There is something affirming in the awareness that even geniuses tend to get lost - they write about the mistakes of geniuses with great enthusiasm. Here's an example. L. Yang, a remarkable mathematician who made a significant contribution to the development of mathematical analysis, authored the book “Lectures on the calculus of variations and the theory of optimal control”, M., “Mir”, 1974. This is a very interesting and original book *). It contains the author's philosophical arguments, addressing many topics, sometimes remote from mathematics. To the question “Do geniuses make mistakes?” Young responds with a fiery affirmative to Newton. Us. 42 of the mentioned book, he writes: “Newton formulated the variation problem of a rotating body experiencing the least resistance in a gas. The law of physical resistance that he likes is absurd, as a result of which the problem he posed has no solution (the more notched the profile, the less resistance)... If Newton’s conclusions were at least approximately correct, then we would not need expensive experiments in wind tunnels.”

What kind of task is this, and how true are the above words? This will be discussed further.

Newton's aerodynamic problem

In 1687, Newton published his “Mathematical Principles of Natural Physics”. It is unlikely that any work of scientific literature can be compared with this book - in it Newton was destined to discover the system of the world. Lagrange called this work “great

*) Not intended, placed for schoolchildren. (Editor's note)

⟦folio 12⟧

the greatest of the works of the human mind."
Discussing issues related to the resistance exerted on material objects by the environment in which they move, Newton, as if at a minimum, threw out the following phrase: “When the figure DNFG is a curve of such a kind that if from any point N of it we lower the redistribution axis NM and from a given point G draw a straight line GR parallel to the tangent to the curve at point N and intersecting the axis at point R, then the proportion takes place MN:GR=GR²:(4BR·GB²), then the body formed by reversing this curve about the axis AB, when moving in the above-mentioned rare medium in the direction from A to B, will experience less resistance than any other rotating body described on the same line and width"*) (Fig. 1).

Newton's phrase attracted the attention of his contemporaries only after I. Bernoulli posed his famous problem about the brachistochrone in 1696 (see, for example, «Kvant», 1975, No. 12 or G. N. Berman’s book “Cyclonda”, M., “Nauka”, 1980). The problem of the brachistochrone, and not Newton's problem, was intended to become the founder of a new direction in mathematics that would use the named variant of calculus.

In connection with the brachistochrone, Newton's problem took the position of an unfortunate Cinderella: it was somehow avoided, rarely remembered, and only then, as a rule, to tell about the error of a genius. But, like Cinderella, Newton’s task had its own way.

*) Newoton’s original text is reproduced in the book “Optimal Control” by V. M. Alekseev, V. M. Tikhomirov, S. V. Fomin. (M., “Nauka”, 1979). The translation of “Mathematical Called” was published in the collected works of Academician A. N. Krylov. (M. - Leningrad, Publishing House of the USSR Academy of Sciences, 1937, vol. 7). The passage quoted is on p. 430. We adjusted it a little. Figure 1 is a copy of figure from “Mathematical Called”. True, we arranged it “from top to bottom”, and not “from left to right”; In addition, on figure 1 there are additional colorful lines and letters painted by us; we come across them later.

Fig. 1.

Let's try to understand Newton's plan.

When designing ships, shells, torpedoes or missiles, there will naturally be a desire to give them a fluid shape so that they experience less resistance during their movement. Newton writes: “You can compare the resistance of bodies with each other and find those that are most connected to the continuation of their motion in a resisting medium.” But, if, say, a ship cannot have too much symmetry in its hull, then it is natural to make the heads of missiles, shells and torpedoes round in cross section; in other words, it is reasonable to give them the shape of bodies of rotation. But which one exactly - spherical, conches, spindle-shaped or something else? Such a question cannot be answered without calculation, without solving some mathematical problem of maximum and minimum. This is exactly the problem that Newton poses (and solves in the above phrase).

To a very first approximation, the problem is formulated as follows.

Problem. Find a body of rotation of a given length and a given width that experiences the name of resistance when moving in a certain medium.

Explanations. Each of the terms involved in the formation (length, width, movement and media

⟦folio 13⟧

yes), requires a full description. Newton imagines a body of rotation to be the same from behind and in front, that is, symmetrical with respect to a plane passing through the middle of the axis of rotation and perpendicular to this axis. Thus, the diinana of a body is its length along the axis of rotation, and the radius of the middle section is the width of the body. Consequently, at all distances we can limit ourselves to only half the body, which is what we do next. We will assume, following Newton, that the motion performed by a body is uniform motion with a constant speed $v$.

Now - about the environment - this is the most subtle and accepting question. The medium described by Newton is somewhat unusual; he calls it rare. Newton imagines a rare medium “consisting of equal parts, freely located at equal distances from each other.” Stationary particles have a fixed mass $m$ and are absolutely elastic balls. Newton also considers the body itself to be absolutely elastic, so that each ball, colliding with a moving body, rebounds from it according to the law “the angle of incidence is equal to the angle of reflection.”

After the above explanations, we could immediately formulate and begin to solve the general problem, but we will first study a simpler one. By the way, Newton himself begins with this simpler problem.

The problem of a successful end. Given the base and height of a successful cone, find the one that will experience the least resistance when moving in a rare environment.

Formalization of the problem of a successful end

The task has just been formulated verbally, without formulas. We must now carry out its transition from the common language to the language of mathematics. This transition is called formalization.

So let the successful cone have height equal to $H$ and radius

Fig. 2.

upper base $R$ (Fig. 2)*.

Newton writes: “Since the action of the medium on the body is the same... whether the body moves in a medium at rest or whether the particles of the medium strike with the same speed on the body at rest, we will consider the body at rest.” We will do the same: leaving the cone motionless, we will assume that the medium is “moving” onto it from the bottom up at a speed of $v$.

The surface of the cone that has experienced collisions with the balls of the medium consists of its lower base and side surface. First, let's calculate the resistance experienced by the lower base. Let's denote its radius by $x$. In unit time, balls that were initially in a cylinder with a base equal to the lower base and a height equal to $v$ will collide with this base. The volume of this cylinder $V_0$ is equal to $\pi x^2 v$. Let $q$ be the density of the medium. Then the number of particles hitting the lower base in a unit time will be equal to $N_0 = \frac{\rho}{m} V_0 = \frac{\rho}{m} \pi x^2 v$. Each particle, after moving away from the lower base, will change its speed to the opposite, that is, it will receive an increment in momentum equal to -2mv. According to Newton's third law, the cone will receive the opposite increment

*) Frequent figure 2, made in black, is contained in “Mathematical Principles”.

⟦folio 15⟧

Now we try to find the necessary $m$ and $\hat{z}$. If the inequality $az^2+2bz+c \geq 0$ holds for all $\hat{z}$ and also $\hat{a}^2+2b\hat{z}+c=0$, then it follows that $D=b^2-ac=0$ and $z=-b/a$ (think this through!). We have $a=(1-m)$, $b=-H$, $c=H^2+R^2(1-m)$. Equation $D=0$ results in the correspondence
$$D=H^2-(1-m)(H^2+R^2(1-m)) \Rightarrow (R^2m^2-(2R^2+H^2)m+R^2)=0,$$
where
$$m=\frac{2R^2+H^2-H\sqrt{4R^2+H^2}}{2R^2}.$$
The + sign has been discarded, or the $m$ we are looking for must, as has been established, be less than one. Next,
$$\hat{z}=-b/a=H/(1-m) = \sqrt{R^2+(H/2)^2}+H/2(>H).$$
(5)
As a result, we found $m<1$ and $\hat{z}>H$ such that the discriminant of the equation $z^2(1-m)-2zH+H^2+R^2(1-m)=0$ is equal to zero, and it has a single root $\hat{z} \geq H$, that is, $h(z) \geq m, h(\hat{z})=m$. Problem 1' solutions.
Let us present the answer to the problem of a truncated cone in the form that Newoton gave it: “If on a circular base CEBH (Fig. 2), described from the center $O$ with a radius $OC$, it is required to build such a truncated cone CBFG with a height $OD$, some resistance would be less than the resistance of any other truncated cone built on the same base and height and moving along the axis $OD$ towards $D$, then dividing the height $OD$ at point $Q$ in half, continue $OQ$ to $S$ so that it is $QS=QC$. $S$ and will be the vertex of the desired cone, which is truncated.”
It is easy to verify that the geometric shape given to Newoton's answer exactly corresponds to the similar shape contained in formula (5).
Discussion. It turned out that the cone of least resistance is actually truncated, blunt, and not pointed. Newton goes even further. It directs the height $H$ to zero. In this case, $\hat{z}$ rushes towards $R$ and the angle, when the cone is truncated, rushes towards $45^\circ$.

Based on this, Newton makes the remark that the oval body should be replaced with a blunt one, that is, a flat round platform should be made in front, forming an angle from the straight coils to the surface of the platform equal to $135^\circ$. “I believe that this remark,” says Newton, “may be of some use in the construction of ships.”

Newton's problem for a broken line
Let us take one more, penultimate step towards solving the general Newoton problem. We will not consider any curved expressions, but only broken lines. To do this, divide the segment $[0, R]$ of the $Ox$ axis into $N$ equal parts using division points
$$x_0=0, x_1=\frac{R}{N}, x_2=\frac{2R}{N}, \dots, x_N=R$$
and denote the coordinates of the corresponding vertices of the broken line by $y_0, y_1, \dots, y_N$ (Fig. 4). We will propose that the broken line begins at point $(x_0, y_0)=(0,0)$, then can go along the axis $Ox$ (that is, $y_0=y_1=\dots=y_s=0$ for some $s$, $0 \leq s \leq N$), then monotonically rises upward
$$y_s<y_s+1 \leq y_s+2 \leq \dots \leq y_N$$
and comes to point $(x_N, y_N)=(R, H)$. Lines that satisfy these requirements are called admissible.
Asking why the monotism condition (6) was required. If it is violated, expressions form “notches” in the surface, from which neoctor balls will be repeatedly reflected, increasing the resistance force (and hopelessly truncating its calculation).
Let us now find the resistance force of the medium $F$ for the surface, ob-

⟦folio 16⟧

a permissible fault, developed by rotation. To do this, applying formula (1) to each of its links, we express cosφк through the coordinates of the vertices (xk,yk), (xk+1,yk+1) (see Fig. 4) and sum. It turns out

$$F_{\pi} = 2K \sum_{k=1}^{N-1} \frac{x_k+x_{k+1}}{2} \cdot \frac{\Delta x_k}{1 + \left( \frac{\Delta y_k}{\Delta x_k} \right)^2},$$

where we denote $K = 2\pi qv^2$, $\Delta y_k = y_{k+1} - y_k$ and $\Delta x_k = x_{k+1} - x_k = \frac{R}{N}$.

We will not solve the problem of minimizing links (7), although this requires only the means of differential calculus known to you - the solution is technically complex, and for what follows we only care about the formulation of the problem and formula (7) itself.

Formalization of Newton's problem

Now we can approach Newton’s problem in the general case, when the surface of rotation is formed not by a segment, not by a broken line, but by a curve $y=f(x)$. What curves can we consider? Of course, the curve must start at the point (0,0), then can go along the $Ox$ axis to some point (b, 0) (where $b \geq 0$), then rises monotically upward and ends at the point (R, H). In addition, we will require that the function $f$ be differentiable at all points $x \in [0,R]$, except for the point $b$, where the angle of contact of the curve with the horizontal section must be equal to $135^\circ$ (remember Newton’s remark “not useful in building ships”). Then the monotonicity condition can be written as

$$f'(x) \geq 0 \quad x \in [0,R], \quad x \neq b.$$

We will call curves $y=f(x)$ satisfying these conditions admissible.

Let us find the resistance force of the medium for the body obtained by rotating the admissible curve $y=f(x)$ about the axis $Oy$. Let's take a sufficiently larger number $N$ and construct an admissible broken line by putting $y_k=f(x_k)$. This broken line will differ little from our curve, so we exclude the use of $F$ and it will differ little from the previously found reference $F_\pi$ (see (7)).

Let us now recall the integral sum and noticing that $\Delta y_k / \Delta x_k \approx f'(x_k)$, it is not difficult to believe that with an unlimited increase in the number $N$ the sum (7) tends to the integral

$$2K \int_0^R \frac{xdx}{1 + (f'(x))^2} = F,$$

which expresses the power of resistance to the desired one. Thus, we came to the formulation of Newton’s general problem:

Among all admissible functions $y=f(x)$ find one for which the integral

$$\int_0^R \frac{xdx}{1 + u^2}$$

(minimalen if $u = f'(x) \geq 0$).

Solution to Newton's problem

Of course, you haven’t seen problems like this in a school textbook. We'll start, therefore, with a simpler auxiliary problem:

Among all admissible functions $y=f(x)$ find one for which the expression

$$\frac{x}{1 + u^2} + 2cu$$

(minimal (for all $x \in [0,R]$), if $u = f'(x)$ and $c > 0$ are constant).

Why solve this problem? But why: if its solution $y=f(x)$, $\bar{u} = f'(x)$ is found, then for any other admissible function $y=f(x)$ the inequality holds (for all $x \in [0,R]$)

$$\frac{x}{1 + u^2} + 2cu \geq \frac{x}{1 + \bar{u}^2} + 2c\bar{u},$$

integrating shorter by $[0,R]$, taking into account that $u = f'(x)$, we get

$$\int_0^R udx = \int_0^R \bar{u} dx = H,$$

where

$$\int_0^R \frac{xdx}{1 + u^2} \geq \int_0^R \frac{xdx}{1 + \bar{u}^2};$$

which means that $\bar{f}(x)$ (a solution to the auxiliary problem (9)) is also a solution to Newton’s problem (8)!

And the auxiliary problem, as you probably agreed, is not so difficult to solve. The answer will be a line going along the axis $Ox$ to the break point $b=4c$ and then along the curve, the point $(x; y)$ of which is expressed by the formula

⟦folio 18⟧

Fig. 6.

At the time, it was believed that it was related to the calculus of variations: for example, A.N. Krylov, citing Newton’s phrase read at the beginning, accompanies it with the following words: “This statement of Newton always applies to the calculus of variations.” Next, he formalizes Newton’s problem (a little differently than we do - he only moves the choice, like Newton’s, and ours - downwards) and arrives (if in his expression we replace $y$ with $x$ and $x$ with $y$) to the problem of minimizing the integral

$$\int_0^R \frac{xdx}{1 + (f'(x))^2}$$

taking into account the initial conditions $f(0) = 0$, $f(R) = H$. Minimizing such an integral, indeed, belongs to the calculus of variations, but without the additional condition $f'(x) \geq 0$ to minimize this integral value. This was noted by Legendre 100 years after the release of “Principles.” Indeed, let us choose as $f$ a broken line composed of very large links (like the one shown in figure 6). Then $(f'(x))^2$ will be very large, and integral (13) will be small; In general, it can be made as small as desired. It turns out, indeed, as according to Young: “the more notched the profile, the less resistance!” But we have already noted that in the Newtonian formulation of the problem it is necessary to require that $f$ be monotonic, that is, that the correspondence $f'(x) \geq 0$ be satisfied.

Minimization of integral (13) under condition (14) does not relate to the calculus of variations. Constraints of type (14), imposed on the task of minimizing integrals of type (13), were covered by theory only in the middle of the 20th century.

So, Newton's problem, not the first given problem in expressed calculus, turns out to be the first given problem of a new branch of mathematics - optimal control theory.

4. Criticism and apologia of Newton. We have already identified two accusations against Newton: it is false that Newton’s problem does not have a solution (he found it), it is false that “the more notched the profile, the less resistance” - this fact does not follow from Newton’s assumptions. But perhaps it is still true that “the law of physics he accepted is absurd?” What is this rare medium? Does such an environment exist? Isn't it absurd that the body of least resistance is blunt? Who has ever seen torpedoes or packages with blunt heads?

To be fair, it must be said that neither water, nor the air around us, nor any other gaseous or liquid medium familiar to us have the properties of Newton’s rare medium. However, Newton's physical assumptions and his aerodynamic problem itself were at the very forefront of modern science in the mid-fifties, when the era of supersonic and ultra-high-altitude aircraft began. “Up there,” the environment turned out to be “rare.” And Newton’s replacement about blunted horses turned out to be so “useless” in the construction of ships, namely, space ships. finally,

5. Are geniuses wrong? Of course they are wrong. But, finally, I was able to convince you that the formulation and solution of the aerodynamic problem was not a mistake of a genius, but a product of his genius, which allowed him to touch our lives and our problems three centuries later. This is worth pondering.

In a word, let’s not trade: maybe the article is that the thought of the Genius, which seems to us to be his delusion, bears the imprint of a truth that has not yet been revealed to us.
