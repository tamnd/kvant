---
id: 1985-1-lyashko-pochemu-ne-umenshitsya-soprotivlenie-9d51048f
issue: kvant_1985_1
year: 1985
number: "1"
title: Why won't the resistance decrease?
authors:
  - Ляшко О. В.
rubric: osnovnye-stati
page_first: 12
page_last: 17
page_labels: 10, 11, 13, 14, 15
tag: 55GE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 079be923d900aaccdd694f145378668f2cd0c68804e33e88e4d82ee7ed23db2b
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/04_lyashko-pochemu-ne-umenshitsya-soprotivlenie-9d51048f.md
source_content_sha256: 8ff88522a92b22f7f2f8924674afcef022b83df6172725a72d17c36a209532a0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

Why won't the resistance decrease?

Candidate of Physical and Mathematical Sciences
O. V. LYASHKO

Although this article solves a purely physical problem, you are faced with a mathematical problem. To understand it, no server knowledge of physics is required; The article does not set itself the goal of describing in detail how deep physical phenomena are. As is often the case in applications of mathematical science, here a mathematical model of the situation under consideration is built and a mathematical apparatus is developed, the use of which provides a simple solution to the original problem, and also allows us to answer many other questions, not only in physics, but also in economics and geometry.

Consider an electrical target consisting of resistors and change the total resistance $R$ of the circuit between its two points $A$ and $B$. Let us now assume that one of the resistors has burned out and its resistance has increased *). Let us again change the resistance $R$ between $A$ and $B$. Do you think it might then turn out that the resistance $R$ 1) has increased? 2) remained unchanged? 3) has it decreased?

1) It is clear that resistance may increase. For example, if the target consists of one or more resistors connected in series, then the total resistance of the circuit is equal to the sum of the resistances included in the circuit; therefore, if one of the terms increases, the sum (Fig. 1) will also be returned.

2) After thinking a little, you can probably come up with an example where the total resistance does not change. Two circuits are also shown at figure 2. In both circuits, increasing the resistance $R_0$ does not change the total resistance (think about why).

3) But attempts to give an example when the overall resistance decreases do not lead to success. So could it be?

“Of course not,” a sane reader will answer correctly (that’s how all my signs answer, in any case). But to the question of why this cannot be, I did not hear an exact answer from them. This is not surprising. The answer to this question, that is, a strict mathematical proof that when one of the resistances of any resistor circuit increases, its total resistance decreases.

⟦folio 11⟧

It can’t be sewn, it’s not at all simple. It is based on one deep principle, which can be called the principle of minimum action).

Its essence is this: many physical processes occur in such a way that some quantities take on a minimum value. So, for example, a soap film stretched over a wire circuit in space selects from all possible formats the one with the minimum area. A ray of light in a medium with a variable refractive index selects from all possible trajectories the one at which its travel time is minimal (“Fermat’s principle”). A proper drop flowing down from a convex mountain chooses the path between given levels whose length is the shortest, etc.

Therefore, in order to solve the corresponding problem (find the shape of a film, or the trajectory of a ray, or the path of a drop), you need to find the minimum of the corresponding function (area, or time, or length). This is, of course, where mathematics is needed: a mathematical formulation of the principle of minimal mathematical techniques for its use.

I think the reader will be interested not so much in establishing the fact itself, but in these techniques and principles. However, a curious reader will probably already ask himself the following question: how can one give a “rigorous mathematical proof” of a fact (in this case a physical one) that has nothing to do with mathematics?

Fig. 3.

wearing? Let's try, looking ahead, to first outline the answer to this question.

When a mathematician takes on solving an applied problem, he usually begins by constructing a mathematical model of it. To do this, he must identify the basic concepts necessary to describe the problem and discard those aspects of the phenomenon that are not essential for solving it. As a result, an abstract description of the problem will arise, in which it is implemented and replaced by mathematical abstractions (points, lines, numbers, functions), and the laws that govern these phenomena are expressed in the form of equations. Thus, our electrical circuit will turn into a “strained graph”, resistances will become numbers, Ohm’s law and Kirchhoff’s rules will be written in the form of a “basic system of equations”. We will forget that the insulation of the wires is made of yellow plastic, that the conductors and resistors are made of some kind of metal, that the current is “running electrons”: all this will become equally insignificant for us. But I probably got too ahead of myself. First things first.

A strained graph (or electrical circuit)

Let us associate with each electrical circuit a strained graph, that is, a finite collection of points on a plane or space (they are called vertices) and some set of points connecting each other (the edges of the graph), on which numbers are written (the strained edges). For example, the electrical circuits on figure 2 are associated with the graphs shown on figure 3; a more complex example of a graph is shown in figure 4.

We number the vertices with numbers from 1 to n; the vertex with number i will be denoted by ⟨i⟩. We will consider

⟦folio 13⟧

to the first vertex $\langle 1 \rangle$, $\varphi_1 - \varphi_n$ is the potential difference at the input and output, therefore, according to Ohm’s law, $R$ is the total resistance of the circuit.

Existence of harmonic potential (or resistor circuit calculation)

The mathematical problem of calculating a resistor circuit energized is as follows. Given a graph Г with loads $R_{ij}$ and selected potential values ​​$\varphi_1, \varphi_n$ at the input and output; it is required to find a harmonic potential with these given values ​​at the input and output, that is, solve the basic system (1) with respect to the unknowns $\varphi_2, \varphi_3, \dots, \varphi_{n-1}$ with given $\varphi_1, \varphi_n$.

Physicists know from practice that Kirchhoff’s first rule (that is, system (1)) is enough to calculate any resistor circuits. For mathematicians, of course, this is not enough - they need a corresponding general theorem. And there it is:

Theorem 1. For any graph Г with positive loads $R_{ij}$ and any values ​​of the potential $\varphi_1, \varphi_n$ at the input and output there is a harmonic potential $\varphi$.

I do not give a direct proof of the theorem using two techniques. Questions, we won’t need it in the future. Secondly, for a rigorous proof, some concepts from “linear algebra” are needed, a discipline not studied in a regular high school. The idea of ​​the proof is that the main system has only $n-2$ unknowns $\varphi_2, \varphi_3, \dots, \varphi_{n-1}$ and the same number of (linear) equations, moreover, these equations are independent, and therefore have a unique solution.

Battles
1. Find another proof of Theorem 1 based on the main theorem (see p. 14).

2. Check that in the case of graphs $2,a$ and $2,6$ the current is real odd along the edges with resistance $R_0$ (that is, the potential difference at the ends of these edges is zero).

3. Prove in the general case that at $\varphi_1 = \varphi_n$ the total current (see formula 2)) is zero.

4. Create a basic system of equations for the graph on figure 4 and estimate how much time it will take to solve it manually. If you have to program, think about how to connect your computer to this task.

5. Double one of the resistances on the graph $2,a$ and count how much its total resistance is notified.

6. Prove that equation (1), (2) and Ohm’s law imply (2).

For any loaded graph (electric circuit) Г with vertices $\langle 1 \rangle, \langle 2 \rangle, \dots, \langle n \rangle$ and positive loads (resistances) $R_{ij}$ on the edges, we know that we can calculate the harmonic potential $\varphi$ of this graph, that is, for arbitrary values ​​of the potential $\varphi_1, \varphi_n$ at the input and output, find the remaining values ​​of the $\varphi_2, \varphi_3, \dots, \varphi_{n-1}$ potential by solving the system of equation (1). Next, substituting the obtained potential values ​​in accordance with (2), we can find the total resistance of the circuit $R$. To make the circuit more specific, it is always possible to indicate whether the overall resistance decreased when one of the $R_{ij}$s was notified or not. But this is not enough for us - we want to prove a general fact, to establish that when one resistance is applied, the total resistance does not decrease in any way, regardless of the specific choice of circuit.

Unfortunately, it was not possible to prove this fact using equation (1) and formula (2) (!). As they say, you need an idea!

Square function (or circuit thermal power)

This idea is suggested to us not by mathematical intuition, but by one of those minimal principles discussed at the beginning of the article: the direction in a resistor electrical circuit is distributed according to such principles. It turns out that he is so “lazy”: from all possible options of behavior, he chooses the one at which his energy consumption (the power released on the conductors of the electrical circuit) is minimal. Let us assume that when passing through a conductor with resistance $R_{ij}$

⟦folio 14⟧

such $I_{ij}$, corresponding to the potential difference $U_{ij} = \varphi_i - \varphi_j$, thermal power (that is, the amount of heat per unit time) equal to $q_{ij} = R_{ij} I_{ij}^2 = U_{ij} I_{ij} = U_{ij}^2 / R_{ij}$ is allocated for conducting $\langle i, j \rangle$, and on the entire circuit - power $Q = \Sigma q_{ij}$, where the sum is taken over all edges $\langle i, j \rangle$ of our graph. The total power $Q$ depends on the values ​​of the potentials $\varphi_1, \varphi_2, \dots, \varphi_n$; Therefore, we will write the total power as $Q[\varphi]$.

Thus, we introduced into consideration the functions

$$Q[\varphi] = \Sigma q_{ij}, \quad \text{где } q_{ij} = \frac{(\varphi_i - \varphi_j)^2}{R_{ij}},$$

which we will call square. (The sum in expression (3) is taken over all edges $\langle i, j \rangle$ of our graph.)

We emphasize that from a mathematical point of view we simply need to define some function $Q$ on the set of all potentials $\varphi$ of the graph $\Gamma$ and (based on physical considerations) we are interested in its minimum.

The square function $Q$ itself does not depend on a numerical variable, but on another function - the potential $\varphi$. Mathematicians call such “functions of functions” functional. The search for their extrema is one of the important problems of varzation calculus, a replacement branch of mathematics that originated in the works of J. Bernoulli, Euler and Lagrange.

Exercise 7. Write down the square function $Q$ for the graph on figure 4. Think about whether you have methods for finding its minimum.

Note. The function $Q$ depends on $\varphi_2, \varphi_3, \dots, \varphi_{11} (= \varphi_{n-1})$, that is, on several variables. At school they only study methods for finding extrema of functions of one variable, so finding the minimum $Q$ is not yet a task available to you.

Minimum principle (or principles of least action)

Our immediate goal is to find the minimum of the quadratic function $Q$. But does she have a minimum? Let's start by answering this question. Our reader, of course, guessed that the answer is positive (these are also “physical assessments”). Those who are ready to accept this statement on faith can skip the proof of the following theorem.

Theorem 2. For the function $Q$ there is a set of values ​​of the variables $\varphi_2, \dots, \varphi_{n-1}$ at which it reaches its minimum value.

Proof. Without loss of generality, we can assume that $\varphi_1 \geqslant \varphi_n$. Let us denote by $M$ the set of values ​​of the variables $\varphi_2, \dots, \varphi_{n-1}$ satisfying the conditions $\varphi_1 \geqslant \varphi_i \geqslant \varphi_n$ for all $i$. Let's consider some set of values ​​($\varphi_2', \dots, \varphi_{n-1}$) $M$ and construct a new set of values ​​($\varphi_2'', \dots, \varphi_{n-1}$) $M$ from it, replacing all values ​​greater than $\varphi_1$ with $\varphi_1$, and all values ​​less than $\varphi_n$ with $\varphi_n$. In this case, as is easy to see, the value of the function $Q$ will decrease:

$$Q(\varphi_2', \dots, \varphi_{n-1}) \leqslant Q(\varphi_2', \dots, \varphi_n).$$

Thus, the smallest value is $Q$ on the set of values ​​$Q$ on the entire set of potentials. This is an agreement on Weierstrass's theorem from analysis, which states that a continuous function ($Q$) on a closed bounded set ($M$) reaches its minimum value. (This theorem is not taught in school: a precise explanation of the understandable continuity, closedness and limitation that is used in it, the completion of us is too far, so we will not deal with it here.)

The proof—typical of a mathematical “existence theorem”—gives us neither a way to find the minimum interaction nor a way to describe it in any way. However, a theorem follows, expressing the minimum principle for our situation, characterizing the exclusive minimum.

Main theorem. The potential at which the minimum value of the function $Q$ is achieved is harmonic.

Proof. Let $\varphi^0$ be the potential at which the minimum value is achieved. We need to prove that the numbers $\varphi_1^0, \varphi_2^0, \varphi_3^0, \dots, \varphi_{n-1}^0, \varphi_n^0$, where $\varphi_1^0 = \varphi_1, \varphi_n^0 = \varphi_n$, are a solution to the system of equations (1). Let's fix all the variables except one - $\varphi_j$. Then the function

$$Q(\varphi_2^0, \dots, \varphi_{j-1}^0, \varphi_j, \varphi_j^0+1, \varphi_j^0-1)$$

of one variable $\varphi_j$ also reaches a minimum at $\varphi_j = \varphi_j^0$.

This function is a square three-fold in $\varphi_j$: $Q = a\varphi_j^2 + b\varphi_j + c$, and the coefficients $a$ and $b$ lie above, opening the brackets in expression (3):

$$a = \sum \frac{1}{R_{ij}}, \quad b = -2\sum \frac{\varphi_i^0}{R_{ij}}$$

(here the sums are taken over all $i$ for which $\langle i \rangle \in S_j$).

Since the minimum of the function $a\varphi_j^2 + b\varphi_j + c$ ($a > 0$) is achieved at the point $\varphi_j^0$, which satisfies the equation $a\varphi_j^0 + b/2 = 0$, we obtain, by substituting into it the expressions for the coefficients $a$ and $b$,

⟦folio 15⟧

Σφ₁ᵢ/Rᵢᵢ — Σφ₁ᵢ/Rᵢᵢ = Σ(φ₁ᵢ−φ₁ᵢ)/Rᵢᵢ = 0.
Thus, φ₁ᵢ, φ₂ᵢ, ..., φₙᵢ−1, φₙᵢ is a solution to system (1), which is what needed to be proven.

And finally, the last question we will answer: what is the minimum value of the function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - amazing significant function Q. How to what? - electrical circuit resistance error.

Proof. Let φ₂, ..., φₙ−1 be a set of numbers on which the minimum of the function Q is accessible. Then, according to the main theorem, this is a solution to the system of equation (1). Therefore, we need to show that (φ₁−φₙ)²/R = (φ₁−φₙ)I is equal to the expression

Σ(φ₁−φₙ)Iᵢᵢ (sum over all edges〈ij〉), where the magnitudes of the currents I and Iᵢᵢ obey Kirchhoff’s first rule (1), (2). Let's open the brackets in (1) and calculate the coefficient for φ₁. The potential value φ₁ is multiplied by the values ​​of all currents Iᵢᵢ passing along the edges〈i, j〉 emerging from the vertex〈i〉 (if the number j is less than the number i, then φ₁ is multiplied by −Iᵢᵢ=Iᵢᵢ). Therefore, the coefficient for φ₁ is equal to

ΣIᵢᵢ (sum over〈j〉 ∈ Sᵢᵢ)
and, therefore, is equal to zero for all i≠1, n, from (1). The coefficients for φ₁ and φₙ are equal to the correspondence of I and −I from (2) and (2′), therefore, we sum over all edges,

Σ(φ₁−φₙ)Iᵢᵢ = φ₁·I + φₙ(-I) = (φ₁−φₙ)I.

Solution of the original problem

Let us notify one (or non-tortic) of the edge resistance: Rᵢᵢ′ ≥ Rᵢᵢ. Then for the function Q = Σ(φ₁−φₙ)²/Rᵢᵢ′ and Q′ = Σ(φ₁−φₙ)²/Rᵢᵢ′ (summation over all edges〈ij〉 of our graph), the following inequality is true: Q′[φ] ≤ Q[φ] for any potential φ, with data φ₁ and φ₂ at the input and output. Obviously, this inequality is also true for their minimum values:

min Q′ = (φ₁−φₙ)²/R′ ≤ min Q = (φ₁−φₙ)²/R′,
which means R′ ≤ R′, which is what needed to be proved.

Other uses
our mathematical model

Is the game worth the candle? - the reader may ask. Is it necessary to develop such a mathematical formula for the sake of a problem that is already physically very interesting?

Mathematical models are created not only to make it more convenient for mathematicians to work. Discarding the specific specification of an applied task, one often arrives at models that turn out to be applicable to completely different problems, from completely different areas of human activity. The study of such models allows, figuratively speaking, to kill many birds with one stone.

Here we will limit ourselves to listing some situations in which our loaded graph apparatus (or its modifications) works successfully.

1) A network of rubber bands on a straight line. In a system of n points on a straight line, the pairs are connected by elastic bands of known stiffness; the end points are stretched (known forces are applied to them); it is required to determine the equilibrium position of the point.

2) Kirchhoff's second rule and Euler's formula. This rule (see p. 27 in this issue) is also convenient to use when calculating electrical circuits. It turns out that the corresponding mathematical theory is related to Euler's formula B−P+Γ=1, where B, P, Γ are the numbers of vertices, edges and areas bounded by a planar graph.

3) Transport flows. The Plok graph can depict a network of roads (airlines, railways) between cities, loads - certain aspects of transportation between neighboring cities; it is required to find the minimum cost distribution of flow transportation. It is interesting that in practice such economic problems are solved by modeling network transportation using an electrical network: the operator enters data on the quantity of transported goods and the cost of transportation, puts himself under voltage and reads the answer with the corresponding ampere!

4) Perfect straight-liners. This is the name for rectilinear lines that can be divided into a finite number of squares of different sizes. Oddly enough, all perfect straight lines are found by constructing and calculating some loaded graphs!

This list could be continued, but «Kvant» hopes to return to these questions soon.
