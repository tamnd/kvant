---
id: 1986-2-arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-22320a02
issue: kvant_1986_2
year: 1986
number: "2"
title: Evolutionary processes and ordinary differential equations
authors:
  - Арнольд В. И.
rubric: osnovnye-stati
page_first: 15
page_last: 22
page_labels: 13, 14, 15, 16, 17, 18, 20
tag: 0QWV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 26dc922924f41ff7a93dbd3bdaf1def5c0bebd42317485b76fb2260250301207
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/06_arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-22320a02.md
source_content_sha256: 54ad80249d699506ab76d4913feee74b8542eb7ba80fa65e6abc89b489286767
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

Evolutionary processes and ordinary differential equations

V. I. ARNOLD

“The equation was very complex, but the processor, with his characteristic modesty, called it ordinary.”

From a newspaper interview with a mathematician.

Differential equations are one of the main tools of mathematical natural naming. They were invented by Isaac Newton (1642-1727). Problems essentially leading to differential equations appeared before Newton. However, only such geniuses as the president of the French Academy of Sciences X. Heugens (1629-1695) and Newton's teacher, mathematician and theologian, preacher of the English king I. Barrou (1630-1677) were able to solve them. After Newoton, any students and even schoolchildren can solve them.

Newton considered his invention so important that he defended it in the form of an angram*), the meaning of which in modern terms can be expressed as follows: it is “useful” to solve differential equations (since they express the laws of nature).

In another, longer angram, Newton also defended the solution he invented to solve all equations, including differential ones.

The theory of differential equations reworks questions of natural

*) bassdae13eff7i3l9n4o4qrr4s9t12vx. Explanation: Data aequatione quot unque fluentes quantitates involvente fluxiones invenire et vice versa, that is, “for a given equation containing some functions, find the derivative and vice versa.” This angram is contained in the famous “second letter” of Newton to the secretary of the Royal Society (English Academy of Sciences) Oldenberg dated October 24, 1676. The letter was intended for Leibniz (1646-1716) and contained a message about the invention of mathematical analysis. Newton conducted correspondence with Leibniz, who lived in Germany, through Oldenburg (who was subsequently imprisoned in the Tower for contacts with foreigners).

Knowledge of geometric problems about curves defined by vector fields (see below) is similar to how Cartesian coordinate method turns questions about algebraic equations into problems about lines and surfaces.

Process states

To study any process, you must first of all be able to describe the set of all possible states of this process. Let's see how this is done with examples.

1. Movement of a point in a straight line. Experience shows that to determine the motion of a material point along a straight line in the absence of external forces, it is enough to set its speed and position on the straight line at the initial moment. Therefore, the set of all states is mathematically plotted with the coordinate plane (s; v): each point on this plane is associated with a matrix point moving with speed v and occupying a position with coordinate s, and vice versa - each state corresponds to the properties of a point in the plane (Fig. 1).

2. Matrix fluctuations. The state of a flat matrix is ​​also described by two parameters, for example, the angle of deviation θ from the vertical and the angular velocity ω of the matrix (Fig. 2). Would the set of states of the matrix be a plane again? Not really. The fact is that when the angle θ changes by 2π, the matrix returns to its previous position. Therefore, the state set here is a cylindrical surface (Fig. 2).

3. The position is returned on two roads. Cities A and B are connected by two non-intersecting roads, on each of which there is a return; we are interested in their relative position. The position of the return on the first road (Fig. 3) can be determined by a number - the fraction of the distance from A to B (along the first road) enclosed between A and the return; similarly, the return should be determined by the same share along the second road. Therefore, the set of states that interests us is described by points (x; y) of the unit square (0≤x≤1, 0≤y≤1).

The state sets of a process in the theory of differential equations are called phase spaces.

⟦folio 14⟧

So, each point of phase space (phase point) depicts the state of the process. And the very flow of a particular process is depicted by lines in phase space; these lines are called phase trajectories.

The introduction of the phase space of a process geometrizes the theory - questions about the progress of the process turn into questions about the behavior of phase trajectories. Receiving geometry problems can be difficult. However, it also happens that the mere introduction of phase space allows one to solve a difficult problem.

Problem (N. N. Konstantinov). Two non-intersecting roads lead from city A to city B. It is known that two cars traveling along different roads from A to B and connected by a rope of some length, less than 2l, could travel from A to B without breaking the rope. Can two large carts of radius l, the centers of which move along these roads towards each other, pass each other without touching?

The phase space here is a unit square. The initial position of the cars (in city A) corresponds to the lower left corner of the square, and the movement of cars from A to B is depicted by a curve leading to the opposite corner of the square (upper left). But any two curves in a square connecting different pairs of opposite vertices intersect. Therefore, no matter how the carts move, a moment will come when the pair will completely replace the raspberries in which the pair was at some point in time. At this moment, the distance between the centers of the carts will be less than 2l. So, it’s impossible to catch up.

Differential equations were not involved in the consideration of the problem, but the course of reasoning is close to what we will do further: describing the course of a process as a line of approach to phase space often turns out to be extremely useful.

The general scheme of the theory of differential equations is as follows. Since the initial state of the processes we are considering determines their future course, it also determines the rate of change of state, that is, the speed of movement of the phase point. The dependence of the speed of movement of a phase point on its position (or the local law of the evolution of the process) is precisely expressed, according to Newoton, by a differential equation. Geometrically, this equation depicts the vector phase velocity field (see for example figure 5.11 below). The theory of differential equations should describe the course of the process using a vector field, that is, finding the trajectory of movement of phase points, answer questions about the characteristics of their movement (for example, the following questions: will the trajectories be limited? Do they return to the starting point?). The significance of these questions for studying the process is very convenient.

Math matrix equation

According to the laws of mechanics, the angular acceleration of the matrix is ​​proportional to the moment of gravity (Fig. 4)

Fig. 1. Movement in a straight line. Fig. 2. Matrix oscillations.

Fig. 3. The problem of two carts on two roads.

⟦folio 15⟧

$$I\ddot{\theta} = -mgl \sin \theta,$$

where $m$ is mass, $l$ is length, $\theta$ is deflection angle; the dot on top means the time derivative $t$ (here and below), two dots mean the second derivative*), $I = ml^2$ is the moment of inertia. The minus sign in the equation is explained by the fact that the thruster's moment reduces the deviation. The latter we get $\ddot{\theta} = -k \sin \theta$, where $k = g/l$. The factor $k$ can be made equal to 1 by a suitable choice of time scale (dividing $t$ by $\sqrt{k}$). Then the equation of the mathematical matrix will take the form

$$\ddot{\theta} = -\sin \theta.$$

(1)

The phase space of the matrix is ​​a cylinder ($\theta; \omega$), where $\omega = \dot{\theta}$ is the angular velocity. We can write equation (1) as a system

$$\dot{\theta} = \omega, \dot{\omega} = -\sin \theta,$$

(2)

which includes only the first derivatives of the unknowns $\theta$ and $\omega$. This system expresses the local law of evolution of the matrix state: the rate of change is expressed through the state itself.

It turns out that solving equation (1) (or system (2)) is not so easy. If we limit ourselves to small angles $\theta$ (small vibrations), then $\sin \theta \approx \theta$. Therefore, for small $\theta$ one uses together with (1) the approximate equation $\ddot{\theta} = -\theta$. It is called the equation of small vibrations of the matrix. You know its solutions $\theta = C \sin (t + \varphi)$ from the physics course: at small angles of deviation, a flat mathematical matrix forms a harmonic (sinusoidal) periodic oscillation. The question of how much this choice changes when moving to the true matrix equation (1) requires special research.

Let us use the phase space of system (2)—the cylinder ($\theta; \omega$). At each point of the phase space, we will construct a phase velocity vector, that is, a vector with coordinates ($\dot{\theta}; \dot{\omega}$)=(ω; —sin $\theta$) - the geometric equivalent of the law of nature (1). The resulting map—the phase velocity field—is depicted in figure 5 (for clarity, we cut the cylinder along the generatrix and turned it around).

In this picture you can see the following. At two points the phase velocity is zero. Point $A$ obtue is the lower (stable) equilibrium position, point $B$ is the upper (unstable) equilibrium position. At small values ​​of $\theta$, $\dot{\theta}$ it is clear that the points of the phase space move along closed curves, let us put them on a circle (small oscillations), with an increase in $\theta$ the closed curves increase and stretch into something like ellipses (oscillations of large amplitude)*). A special role is played by the trajectories placed in red

$$\lim_{x \to 0} \frac{\sin tg x - tg \sin x}{x - 0} = \arcsin \arctg x - \arctg \arcsin x$$

instantly from geometric messages (rarely do any modern mathematicians manage to calculate this limit in an hour).

⟦folio 16⟧

arrows: the matrix, which has fallen from a position of unstable equilibrium, makes a full revolution and again freezes in the upper position. This trajectory separates the oscillations from the (uneven) rotations that the matrix makes if its speed at $\theta = 0$ exceeds the number 2 in our dimensionless units.

Crucian carp (normal reproduction)

Crucian carp are bred in the big mine. Crucian carp do not interfere with each other when they have enough. How will the number of crucian carp $x(t)$ change over time $t$? The growth rate of crucian carp under these conditions is proportional to the number of individuals; so we can write

$$\dot{x} = kx, \quad k > 0.$$

(3)

This equation is called the differential equation of normal or Maltese reproduction*). (Recall that $\dot{x}$ denotes the time derivative.)

Existence theorem. Any function of the form $x = Ce^{kt}$, where $C$ is a constant, is a solution to equation (3).

Proof: Substitute into equation.

From the proven theorem it follows

Uniqueness theorem. Equation (3) has no other solutions.

Proof. Any function can be written as $x(t) = C(t)e^{kt}$. Then $\dot{x} = Ce^{kt} + kx$. Therefore, for the equality $\dot{x} = kx$ to hold, it is necessary and sufficient that $C = 0$, that is, that $C$ be a constant.

Graphs of solutions to an equation are called integral curves. These curves lie in space-time, that is, on a plane with coordinates $(t; x)$. For drawing integral curves, a blank is useful, which is called a directional equation field and consists of small segments applied at each point in space-time at an angle to the time axis, the tangent of which is equal to the right side of the equation.

*) In some cases, the rate of reproduction turns out to be proportional not to the number of individuals, but to the number of pairs. Such anomalous urban reproduction is slower usually at low population densities (for example, whales of certain species have difficulty finding mates). For example, for large $x$, reproduction at a rate proportional to $x^2$ leads to an “explosion” in a finite time: the graph $x(t)$ has a vertical asymptote (why?). This situation is realized in the equation of chemical kinetics, where the reaction rate is proportional to the amount of each reactant.

Fig. 6. Field of the directed normal reproduction equation $\dot{x} = kx$ and the solution passing through the initial point $(t_0, x_0)$.

($kx$ for equation (3), see Fig. 6). The interval curve at each point touches the corresponding segment and, conversely, the curve tangent to our segments will be the graph of the solution (this is the geometric meaning of the differential equation).

We have just proved that through each point in space-time there passes exactly one integral curve $x = Ce^{kt}$ of equation (3). This formula expresses the law of normal reproduction: to equalize the number of crucian carp it always takes the same time, regardless of their number. The period of the Earth's population equation is currently about 40 years. Consequently, the number of people living is greater than the number of all people who have ever died if the growth rate did not change. The time of human existence is then about 2000 years; therefore, the population growth rate would be less than 1/v(x). Along the integral curve (if it is nowhere parallel to the $t$ axis), $t$ can be expressed as a function of $x$. Denoting the derivative with respect to $x$ by shrikh, we obtain $t' = 1/v(x)$. This means that $t$ is the antiderivative of

⟦folio 17⟧

Fig. 7. Directional field and graphs of solutions to the logical equation $x=(1-x)x$. Solutions $x=1$ and $x=0$ are a positive source of unstable equilibrium.

1/v. This allows you to express $t$ in terms of $x$, and then $x$ in terms of $t$. (Of course, direct space-times, where $v(x)=0$, comes to be thrown out so as not to divide by zero.) For $v(x)=kx$ we get $t'=1/kx$, $kt=\ln|x|+const$, $x=Ce^{kl}$.

2. The uniqueness theorem, which states that interval curves do not coincide and do not intersect, is an extremely surprising fact that contradicts visual evidence and physical experience. For example, the interval curves of equation (3) for $k=1$ passing through the points (0; 0) and (0; 1) for $t=-5$ are indistinguishable by eye, and for $t=-30$ the atoms between them do not decrease. Nevertheless, mathematicians consider them to be non-intersecting even for $t=-10^{10}$.

3. In recent physical literature, Newot's derivation of Kepler's laws from the law of universal theoteny (indicated to him by Hooke in a letter dated January 6, 1680) by Newot in 1684 has been questioned: this conclusion does not use the uniqueness theorem for the equation of motion, which Newot did not prove. In reality, however, the only thing that follows is the existence of a solution whose dependence on the initial point is expressed by a differentiable function. The proof of uniqueness in this case is similar to that given above for the diversity equation, but Newoton presented the required solution. In a letter to Halley about his discussion with Hooke, Newton describes the differences between the approaches of mathematicians (Newton) and physicists (Hooke) to the natural sciences, which remains relevant today: “Mathematicians, who discover and establish everything and do all the work, must be content with the role of dry calculators and menial workers; the other, who merely grasps everything and lays claim to everything, appropriates to himself the inventions of both his followers and his predecessors.” Hooke's duties as curator of the Royal Society included proving 2 or 3 new laws of nature using experiments on the society's daily plantings, which he did for 40 years. Provable laws can be discovered by others, but Hooke counts up to 500 laws that were discovered only by him. Naturally, he did not have time to justify everything mathematically.

Let us return, however, to our punishments. After a while there will be so many caramels that they will not have enough food and they will become cramped; further growth will no longer satisfy equation (3).

Crucian carp with a shortage of food (logistic curve)

If our product with caramels is not VELik, or if the number of caramies in a large product has increased greatly, competition for food leads to a decrease in the growth rate. The simplest assumption is that the coefficient $k$ depends linearly on the number of caramies, that is, $k=a-bx$ (for $x$ that is not too large, any smooth function can be approximated by a linear one). We thus arrive at the reproduction equation taking into account competition: $\dot{x}=(a-bx)x$. The coefficients $a$ and $b$ can be converted into units by choosing the scales $t$ and $x$. We get the so-called logistic equation

$$\dot{x}=(1-x)x.$$ (4)

The directional field of equation (4) in space-time is shown on figure 7, and next to it, on figure 7, b, graphs of solutions are shown. S-shaped interval curves in the band $0<x<1$ are called logistic curves. We see that 1) the process has two equilibrium positions: $x=0$ and $x=1$;
2) between straight lines $x=0$ and $x=1$ the field is directed upward from 0 to 1, and at $x>1$ - downward to 1.

Thus, equilibrium position 0 is unstable (once the population of karamas appears begins to spread), and equilibrium position 1 is stable (less population spreads, more population decreases). Whatever the initial number of caramies $x>0$, over time the process reaches a stable state of equilibrium $x=1$. Each pond, therefore (other conditions being constant), has its own “correct” number of caramels, and any population of caramels will tend to this number.

⟦folio 18⟧

Fishing for crucian carp

Until now, we have considered a free population of crucian carp, developing according to its own internal laws. Let's now assume that we catch crucian carp (let's say the collective farm pond regularly supplies the local fish store with live fish). Let us assume that the capture rate is constant. We arrive at the differential trapping equation
$$\dot{x} = (1-x)x-c.$$ (5)

The value $c$ characterizes the permissible catching rate and is called kvata.

figure 8 shows three types of graphs for solving equation (5) for three different $c$.

We see (Fig. 8, a) that if the catching speed is not too high ($0<c<1/4$), there are two equilibrium positions ($x=A$ and $x=B$ on figure). The lower equilibrium position $A$ is unstable. If for some reason (overfishing, disease) at some point in time the population size $x$ is below $A$, then in the future the entire population will disappear in a finite time. The upper equilibrium position $B$ stable is the Stationary regime to which the population reaches with constant catching $c$. Naturally, the equilibrium population of a pond in which fishing is carried out is smaller than in a pond in which fishing is not carried out.

If $c > 1/4$ (Fig. 8, b), then there are no equilibria and all crucian carp will be caught in a finite time (an inflated plan for selling live fish to a store will lead to its death; a historical example of this kind is the extermination of the Steller’s cow).

At $c = 1/4$ (Fig. 8, b) there is one unstable equilibrium state $(A=B=1/2)$. Catching at such a rate with a sufficiently large initial population is mathematically possible for an arbitrarily long time, however, an arbitrarily small amount of the size of the established equilibrium population down (see point $F$) leads to the complete capture of crucian carp in a finite time (catching plan $c = 1/4$ for the “Fish” store is also not suitable).

Thus, although any quota up to the maximum ($c \leq 1/4$) is theoretically acceptable, the maximum quota $c = 1/4$ leads to instability and is unacceptable*. Moreover, kvs close to $1/4$ are practically unacceptable, since at them the dangerous threshold $A$ is close to the steady state $B$ (small random deviations poison the population below the threshold $A$, after which it dies).

It turns out that it is still possible to organize catching in such a way as to consistently obtain catches at a rate of $c = 1/4$. Let's see how it's done.

Introduction of feedback

We fix together the absolute rate of capture relative to, that is, we fix the share of the existing population for the person being caught per unit of time:

$$\dot{x} = (1-x)x - px.$$ (6)

figure 9 shows the space-time for equation (6) (at $p < 1$) and graphs of some solutions. It can be seen that the lower, unstable equilibrium position is now at point $x = 0$, the second equilibrium position is $B$

*) An important conclusion for economics from mathematical economics: the desire to maximize profits, income or the amount of production through/to the emergence of system instability.

Fig. 8. Solutions of the trapping equation $\dot{x} = (1-x)x - c$ for different values ​​of the trapping quota $c$. At $c < 1/4$ any population tends to a stable equilibrium $x = A$, at $c = 1/4$ the equilibrium position is unstable, at $c > 1/4$ any population dies out.

⟦folio 20⟧

The multiplication of crucian carp will lead to the fact that over time I am looking for nanunt to multiply.

But will we return to point A? In other words, will the oscillation process be repeated periodically? The answer to this question depends on the choice of the starting point A (as well as on the value of the system parameters). We will return to this issue in one of the next issues of the magazine.

Tasks
1. Find the equation of the logistic curve.
2. Are the integral curves of equation (5) and (6) distance logistic curves?
3. Prove that the integral curves of equations (5) and (6), the non-strip distance between A and B, have vertical asymptotes.

Cities for electrons

(See beginning on p. 6)

After the wiring and contacts have been formed, the LSIs are ready. Each of them is carefully tested for performance directly on the plate. A control machine, controlled by a computer, lowers precise needle-contacts onto the LSI and sends a series of test current pulses into the circuit (as they say, “nicknaming” the circuit). If the circuit contains a million elements, then the number of test pulses is up to ten thousand. The answer from the circuit being examined is received by the computer. If the LSI does not respond as it should or is silent, the control machine places it with a drop of magnetic paint. After the silicon wafer is divided into hundreds of finished chips (this is done with a diamond cutter or a laser beam), the electromagnet will select the least rejected circuits.

And now all that remains is to place the serviceable, ready-made LSIs into the housing. A small box made of ceramic, metal or plastic should protect the microcircuit from external damage, exposure to the atmosphere, random electric fields, and ensure cooling of the operating microcircuit. Therefore, despite the external
In reality, the design of the hull is carefully thought out and calculated. In some types of microcircuits, the cost of the housing and “packaging” work reaches third all sides of the LSI.

Now that the chip manufacturing process is over, the analogy with urban planning ends. No new building city is subjected to tests for resistance to extreme heat and frost of -60 °C, to an earthquake of magnitude 9, to the impact of falling from a three-meter height; add testing for leaks in sea fog, for maintaining maximum operating conditions, etc. If the LSI can withstand all this, it can be transferred to the consumer.

* * *

Microelectronics is a union of many sciences: materials science, precision mechanics, quantum optics, electrophysics, photochemistry, cybernetics,... It cannot be said that what is important here and what is secondary. The technology for producing microchips is better than what science and technology have today. We have considered only the most typical and relatively simple technical elements to understand. But both they and other technical options and technically close prospects for LSI are always reliable in the fact that the pinnacle of microelectronic technology is still far ahead.
