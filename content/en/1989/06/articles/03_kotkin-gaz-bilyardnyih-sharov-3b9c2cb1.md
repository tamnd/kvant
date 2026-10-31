---
id: 1989-6-kotkin-gaz-bilyardnyih-sharov-3b9c2cb1
issue: kvant_1989_6
year: 1989
number: "6"
title: Billiard ball gas
authors:
  - Коткин Г. Л.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: Q010
lang: en
source: kvant_digital
extraction: vision
content_sha256: 04283fc60099dd2afe4dcd43d8c13c3138c8db4a80f744f710ed66a31eb37554
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/03_kotkin-gaz-bilyardnyih-sharov-3b9c2cb1.md
source_content_sha256: 89fb66d221aab4242dc9005cbcbd24d06aa13229086169e8850612d892685fec
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Among the many uses of computers in science and technology, one of the most important and widespread is modeling. Computer models of airplanes and sea currents, planetary movements and economic relations between countries will be created...

This article will discuss one of the simplest gas models. This is “ideal billiards”: absolutely smooth and elastic balls play the role of gas molecules, the sides of the billiard table play the role of the walls of the vessel, the surface of the table is absolutely smooth. Such an ideal billiards does not exist, but you can “create” it using a computer and observe the “life” of the balls on a graphic display screen.

Perhaps the “ideal billiards” will seem to you to be a very simple gas model. In principle, on a computer it is possible to “construct” a more realistic model - move to the movement of balls in space, and not on a plane, introduce the interaction of balls-molecules, etc. However, “billiards” is an object not only for educational, student, but also server scientific research.

It is clear that the motion of ideal balls is completely determined by the laws of mechanics. Meanwhile, the movement of the parts that make up the gas can be considered chaotic, random*).

In this article we will describe experiments with the “ideal billiards” model, which allow us to observe how the movement becomes xaotic, and try to figure out why

*) The picture of the emergence of “molecular xaosa” in the gas of spheres was studied by the Soviet physicist N. S. Krylov (1950). The Soviet mathematician Ya. G. Sinai conducted a similar study to a level of rigor that satisfied mathematicians (1963). There are a lot of scientific works using the computer model of “ball gas”.

Fig. 1.

⟦folio 3⟧

rub it against the wall) - these will be new initial data - and we will repeat the calculation.

We will set the positions of the balls using the Cartesian coordinates of their centers, and the velocities using their projections on the same axes (Fig. 1):

$$\vec{r} = (x, y), \quad \vec{v} = (v_x, v_y).$$

The calculation formulas turn out to be quite simple. Let the Y axis coincide with the left side of the billiards. Then the time before the ball collides with this side is

$$t = -(x-a)/v_x \quad (a \text{ — радиус шара}),$$

and the collision occurs only if $v_x < 0$. Let this collision be the solution itself. During a collision, the projection $v_y$ remains unchanged, but the projection $v_x$ changes sign:

$$v_x \rightarrow -v_x, \quad v_y \rightarrow v_y.$$

Moving each ball in time $t$ —

$$\vec{r}_{it} = \vec{r}_i + \vec{v}_i t,$$

i.e. $x_{it} = x_i + v_{ix} t, \quad y_{it} = y_i + v_{iy} t$. The calculations for the case of balls colliding, although somewhat more complicated, are also “school” ones. We suggest you check them yourself (see tasks at the end of the article).

A description of the complete program that simulates the motion of $N$ balls on a graphical display is given in the article “Gas on the Display” (see p. 61).

What is the speed of calculations using a similar scheme? Computers used in student practice at the Physics Faculty of Novosibirsk State University are able to count at such a speed that the frames on the display change as quickly as in a cartoon (if there are no more than ten balls; with an increase in the number of balls, the calculation time for each frame of the “cartoon” is quickly calculated)*.

Our computer carries out all calculations with 7-8 digits.

*) The calculation goes to the Elektronka-60 computer, included in the Terminal System Manual (TEVUS - developed by Novosibirsk State University).

Fig. 2.

⟦folio 4⟧

The ry - first one, and then the rest - “lost their way” and came to a completely different place from where they embroidered. Thus, the movement of the balls turns out to be “wrong”. Why?

The entire calculation is carried out using exact formulas, so the only possible cause of “incorrectness” is the rounding of numbers during the calculation process. But the deviation associated with rounding has a relative value of $10^{-7} - 10^{-8}$ (as we said, the computer works with 7-8 digit values), and on the screen by time $2t_0$ the balls have completely “forgot” their original positions. Can this “forgetfulness” be explained by rounding?

Deviation estimates

To obtain quantitative estimates, let us imagine that, due to rounding, the direction of movement of one of the balls has deviated by an angle of $\varphi_0 \sim 10^{-7}$, and further movement is calculated exactly.

First, consider the case when there is only one ball and the deflection occurs when it hits the wall. The trajectory of the center of the ball is depicted in figure 3, and several constructions are also given there to facilitate the calculation. The square on side $(b - 2a)$ is the area accessible to the center of the ball $(b - \text{dлина стононы бильярного стола})$. The length of the trajectory $1 \rightarrow 2 \rightarrow 3 \rightarrow 4 \rightarrow 5 \rightarrow \dots$ is equal to the length of the beam $1 \rightarrow 2 \rightarrow 3' \rightarrow 4' \rightarrow 5' \rightarrow \dots$. If at point 1, as a result of rounding the value $v_x$, the direction of the ball’s velocity after the impact deviated from the exact direction by a small angle $\varphi_0$, then on a path of length $L$ the deviation of the ball’s center will “accumulate” by a distance $\Delta \sim L\varphi_0$. Limiting ourselves to the time $T$, during which $v_1 = 1000$ collides with the wall, we obtain a deviation $\Delta_1 \sim v_1 b\varphi_0 \sim 10^{-4}b$. For our graphic displays, the line thickness on the screen is approximately $0,004b$. So during the time $T$ the accumulated deviation cannot be replaced - it is less than the thickness of the line on the screen. By a noticeable distance equal to, say, the diameter of the ball $2a$, the center of the ball will deviate through $v_2 \sim 2a/b\varphi_0$ collided. The time it takes for such a number of impacts on the walls to occur is estimated at 100 (!) hours.

Obviously, rounding when calculating impacts on walls cannot be attributed to the “incorrect” movement of the balls in our experiment.

Let's see how rounding of numbers affects the calculation of collisions of balls. Let us again assume that the direction of motion of one of the balls has deviated by an angle $\varphi_0 \sim 10^{-7}$, and we will study how the angle of deviation during collisions will be smaller. In this case, we will limit ourselves to the group’s estimates. We will keep in mind that between collisions the ball moves in a straight line and passes along the average path $l$, much larger than the radius of the ball $(l \gg a)$. During the time between two successive collisions, the center of the ball will shift by a distance $OO' \sim l\varphi_0$ (Fig. 4). At the same time, the displacement of the point of contact of the balls upon impact is also in order. The surface area of ​​the second ball in the vicinity of the point of contact plays the role of a “mirror” during impact. This “mirror” itself was moving before the impact; upon impact, it rebounds, so the direction in which our ball bounces is not determined by the rule “the angle of incidence is equal to the angle of reflection.” However, turning the “mirror” small

⟦folio 5⟧

angle α leads to a change in the direction of movement of the rebounded ball by an angle φ₁ ~ α (maybe one and a half to two times more or less - this level of accuracy in this case is STRAIGHT). Since α ~ (AA'/a) ~ (lφ₀/a), we obtain

φ₁ ~ (l/a) φ₀ >> φ₀

— upon impact, the speed deviation increased sharply. After k so new φₖ ~ (l/a) k φ₀.

If (l/a) ~ 10, then 8-10 so new is enough for φₖ ~ 1 to become and the direction of the ball’s motion ceases to have any relation to the correct one.

CONTROL EXPERIMENT

The estimates made look convincing, and yet we will test them using a computer experiment. To do this, we will carry out two “launches” of balls with almost identical initial conditions, only slightly changing the second time the initial speed (or initial position) of one of the balls.*) We will “order” the computer to remember the coordinates of a ball at equal time intervals Δt; during the second run, we will mark the coordinates of the same ball at the same moments tₖ = k Δt, and then we will determine how the “divergence” of the trajectories of this ball changes with time

Δrₖ = √((xₖ - x'ₖ)² + (yₖ - y'ₖ)²),

where xₖ, yₖ are the coordinate values ​​at moments tₖ at the first launch, and x'ₖ, y'ₖ at the second. Taking into account the expected dependence, it is convenient to use a logarithmic scale along the Δrₖ axis, i.e., plot the log (Δrₖ) values ​​along this axis. A dependence of the form φₖ ~ (l/a) k φ₀ should lead to a straight-line graph

lg (Δrₖ) ~ lg φ₀ + (t/tₖ) lg (l/a).

The results of the experiments are shown in figure 5. One graph shows the points obtained at different deviations in the initial conditions. The expected straight section of the graph is visible quite clearly. After time ℭ, the value of Δrₖ grows to the limit set by the size of the table, and then the chaotic changes, but, in general, not millions of times (as in the area t < ℭ), so that on a logarithmic scale the points at t > ℭ do not deviate even from the straight line lg (Δrₖ) ~ log l.

This computer experiment demonstrates the reasonableness of earlier estimates.

*) Of course, when restarted with the same initial conditions, the calculated movement will be exactly repeated.
