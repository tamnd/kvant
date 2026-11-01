---
id: 1980-6-vertgeym-metod-nepodvizhnyih-tochek-64ae7a4f
issue: kvant_1980_6
year: 1980
number: "6"
title: Fixed point method
authors:
  - Вертгейм Б. А.
rubric: osnovnye-stati
page_first: 7
page_last: 11
page_labels: 5-9
tag: YFXT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6973db409608c096aacd5d0a69d2dcb9ed2c894cb156cdea53767e6c09bf881b
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/04_vertgeym-metod-nepodvizhnyih-tochek-64ae7a4f.md
source_content_sha256: a6910bcdace299ea28f5d178ae5b978332b1cdaf2664d6020491b6d872f06469
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

B. Werheim

Method
stationary
points

When we are looking for a solution to an equation, it is good to know in advance that it has a solution - because if not, then why waste time? This message becomes serious when it comes to solving complex equations and systems on powerful computers with expensive computer time. Therefore, the so-called existence theorems and, which guarantee in advance the existence of a solution, play a very important role. One of them, Brouwer’s fixed point theorem, which is interesting and useful even at the school level, is discussed in this article.

Walk
Nanhem from a walk, remembering the benefits and eternity of movement; along the way there will be both fixed points and equations.

Putnikovoevoe one goes from point $a$ to point $b$, the other walks all the time on the road $ab$. Obviously, their meeting is inevitable: the paths would like to be equal once (to be at the same point at the same time). Let's describe this in more detail (Fig. 1).

Let $x$ be the coordinate of the first ($a \leqslant x \leqslant b$) path and let its speed be constant; $y$ is the coordinate of the second ($a \leqslant y \leqslant b$). Each value $x$ (the position of the first path) corresponds to a single value $y$ (the position of the second path at the same time); so we have the function $y = f(x)$. Equation

$$f(x) = x$$

determines the meeting place.

Example 1. Let $a = 0$, $b = 1000$ m, $y = 100 + 0,7x$. If $x = 0$, then $y = 100$; if $x = 1000$, then $y = 800$ - the first one went around! Equation 100+

Fig. 1

⟦folio 6⟧

+0.7x = x gives the coordinate x = 333 1/3 m - here the first one will catch up with the second one.

If the movement of the second is the last, then both the function f and the meeting equation will be more necessary, but it is still very unlikely that at least one meeting will occur.

However, this “obviously” does not STRAIN us as mathematicians; Before we go further, we will clarify the mathematical formulation of the problem and prove the existence of the meeting.

Suppose (as in Example 1) that the function f displays the segment [a; b] into itself, that is, for all x ∈ [a; b] we have a ≤ f(x) ≤ b. Then every solution of the equation f(x) = x is called a fixed point of the mapping f. (In our example, the fixed point is precisely the meeting point.) When does it exist?

Theorem. For any continuous function f representing the segment [a; b] into itself, there is a fixed point.

In the theorem, both the continuity of the function f and the fact that we are talking about a segment are essential.

Exercise 1. Give an example of a discontinuous function f representing [a; b] into itself, without a fixed point.

Exercise 2. Give examples of continuous functions that map into themselves without fixed points: a) the union of two segments [a; b] ∪ [c; d]; b) * integral ]a; b[.

To prove the theorem, we will arm ourselves with red pencils and photographs. Before we use them, let us denote

$$\varphi(x) = f(x) - x.$$

It is clear that c ∈ [a; b] will be a fixed point for f if and only if c is the root of the equation $\varphi(x) = f(x) - x = 0$. Therefore, we will look for the root of this equation. Note that from the condition a ≤ x ≤ b, a ≤ f(x) ≤ b, $\varphi(a) ≥ 0$ and $\varphi(b) ≤ 0$ immediately follow. We will assume that both inequalities are strict (otherwise it is a solution problem). Let us now divide the segment [a; b] into 10 equal parts and color red all the segments for which the value

$$\cos x^3 - x = 0?$$

The cos x³ function is continuous; it maps the segment [−π/2, π/2] into itself (further into the segment [−1, 1]); This means that by the theorem there is a solution c ∈ [−π/2, π/2].

⟦folio 7⟧

Note that the numbers $a_n, \delta_n$ are approximations to the root, and that the segment can be divided not into 10, but, say, into 2 parts; This technique (the Bolshano method, named after the Czech mathematician) is actually used along with other algorithms for approximate solution of the equation.

In addition, our theorem says nothing about the number of fixed points: it is clear that there can be many of them.

Cup of coffee

And now - a cup of coffee! Placing it with smooth circular movements, we will see a fixed point in the center. For some movements the picture is more complicated, but if you consider the positions of the part at two different moments in time, you can find a particle that is motionless in the sense that it is both times - not, perhaps, not all the time! - is in the same place. This is very true if you accept the physical condition of the immobility of a part near the walls due to friction, and not very good - but true! - and without such a condition, as long as there is continuity of the corresponding mapping (that is, “close” particles would not diverge too far).

To “mathematicize” the situation under consideration, we will need some definitions.

Let $M$ be a set of points (for example, part of a line, plane or space); $f$ is a mapping of the set $M$ into itself: it assigns to each point $x \in M$ its image $y = f(x) \in M$. Such a mapping is called continuous if for any point $x_0 \in M$ and any $E > 0$ there is a $\delta > 0$ such that for all points $x \in M$ removed from $x_0$ by a distance less than $\delta$, the distance between their images $f(x_0)$ and $f(x)$ is less than $\varepsilon$.

For the case when $M$ lies on the number line, the distance between the points is $|x_0 - x|$, between their images - $|f(x_0) - f(x)|$, so that our definition essentially coincides with the definition of a continuous function (“Algebra and the beginnings of analysis 9”, paragraph 38).

The visual meaning of the definition is that the continuous map $f$ should not have discontinuities - very close points cannot move too far away from each other.

As before, we call the point $x \in M$ a fixed point of the mapping $f$ from the set $M$ into itself if $f(x) = x$.

When does the mapping $f$ necessarily have a fixed point? The answer to this question is given by

Brouwer's theorem
about a fixed point

This famous theorem was rigorously proven not so long ago - in 1911*). Together with numerous generalizations, it plays a leading role in a number of areas of modern mathematics. Theorems about fixed points are important both in theory and for applications: they are used to calculate airplane wings, and to analyze optimal strategies and equilibrium states in games, and in mathematical economic models.

Brouwer's theorem. Every continuous mapping $f$ of the circle $M$ (together with its boundary) into itself has a continuous point.

This theorem is true not only for the circle $M$, but for any convex bounded set containing its boundary, for example, for a right angle, a triangle or a generally convex polygon on a plane, for a cube or a ball in space.

*) L. E. Ya. Brouwer - Dutch mathematician; before him, the theorem was used by the Latvian mathematician P. Bol, and it is also called the Bol-Brauer theorem.

⟦folio 8⟧

Fig. 4.

However, it is not true for every $M$:

Exercise 3. Give an example of a bounded set $M$ on the plane and its continuous mapping into itself without a fixed point.

Exercise 4*. Construct a continuous map of a circle without a boundary into itself that has no fixed point.

Exercise 5. Construct a discontinuous mapping of a circle (with boundary $M$) into itself without a fixed point.

We will not prove Browser's theorem in the most general situation, but will consider the case when $M$ is an equilateral triangle. To prove it, we need to require colored pencils, but now there are three: red, blue and green. (In space it would take four!) They will be needed to prove one auxiliary statement known as

Sperer's Lemma

figure 4 shows a “net” for catching points in a regular triangle $ABC$ from side $a$. Nodes are marked with circles, 3 lines (edges) emanate from each node, connecting it to neighboring nodes. The network cells are regular hexagons on the $b$ side. The sides of the triangle are divided into $n$ equal parts, the division points are the centers of the boundary cells. $nb\sqrt{3} = a$ and $(n+1)(n+2)/2$ are the total number of cells.

Each internal vertex belongs to those, and the border vertex belongs to two cells.

Let us now mark with the number 1 all the cells except the last one side, the number 2 - the cells of the second, and the number 3 - the cells of the third (Fig. 4). We will place the remaining (internal) cells with the numbers 1, 2, 3 completely arbitrarily. Color cells of type 1, 2 and 3 green, blue and red, respectively. Let's call a vertex complete if it is contained in cells of all three colors.

Lemma. There is a complete vertex*).

Proof. We build a broken line step by step, composing it from edges of “type 1-2” adjacent to cells with numbers 1 and 2. Let’s start from the edge where, by condition, there is only one such “two-color” edge $p_0p_1$, and in a finite number of steps we arrive at a complete vertex: if an edge of type 1-2 $p_{k-1}p_k$, $k=1, 2, \dots$, led us to an incomplete vertex $p_k$, then there is another edge of type 1-2 emanating from node $p_k$ (Fig. 5), it gives vertex $p_{k+1} \neq p_k$. This path, obviously, does not return either to the edge or to the traversed peaks (why?). Since the set of vertices is finite, the broken line will necessarily end at a complete vertex.

Swan, cancer and shuka

Let us now prove Browser’s theorem for the case when $M$ is correct

*) This lemma is only a partial case of the signs of the lemma due to the German mathematician Sperer.

Fig. 5.

⟦folio 9⟧

triangle $ABC$ (Fig. 4). Let's mark the point $A$ with the number 1, $B$ with the number 2, $C$ with the number 3 and write these numbers in the corresponding three cells. Next, in cells with centers on the side $AB$ we write 1, on $BC$ - 2; on $CA$ - 3. Each internal point $x$ we assign a label - one of the numbers 1, 2, 3 - according to the following rule: number 1, if the distance from the point $x$ to the side $AB$ is not greater than the distance from the point $y=f(x)$ to $AB$ (point $x$ is not "decreases" when $f$ is displayed); if this is not the case, then the number is 2 when point $x$ does not approach $BC$ (the distance from $x$ to $BC$ is not greater than the distance from $y$ to $BC$); in other cases we take 3 - in this case the point $x$ moves away from the side $CA$ (see on figure 4 areas for $\vec{x}y$, which correspond to marks 1, 2, 3). Let us write down the mark of its center at each internal point. Using Spernan’s lemma, we find the complete vertex $x_0$ and recall the meanings of Krylov’s fable:

...The swan rushes into the clouds,
Cancer is moving backwards
and the tsiuka is pulled into the water -
Yes, but things are still there!
We are just looking for a fixed point: similar to this cart from the fable, there are cells with numbers 1, 2, 3 associated with the full vertex $x_0$. (This vertex is “almost motionless” - with a sufficiently small $b$ it approaches $AB$, $BC$ and $CA$ little, i.e. it moves little.)

Let us now take a sequence of numbers $b_1, b_2, ..., b_k$, ... tending to zero, and for each $k$ we find its complete vertex $x_k$. We get a sequence of points

$$x_1, x_2, ..., x_k, ...$$

First case. If this sequence converges*) to the point $\bar{x} = \lim_{k \to \infty} x_k$, then $\bar{x}$ is a fixed point of this mapping. (Its immobility follows from the fact that $\bar{x}$ does not approach any of the three sides of the triangle.)

Exercise 6. Prove that the point $\bar{x}$ is fixed.

Second case. If the sequence $x_1, x_2, ..., x_k$, ... does not converge, then we can choose a sequence of numbers $n_1 < n_2 < ... < n_k < ...$ so that the sequence of points

$$x_{n_1}, x_{n_2}, ..., x_{n_k}, ...$$

converged to some point $\bar{x}' = \lim_{k \to \infty} x_{n_k}$.

Exercise 7. Prove the existence of such a sequence of numbers $n_1, n_2, ..., n_k, ...$ and the immobility of the point $\bar{x}'$.

Development of the fixed point method

Browser's theorem, which we proved for a segment and for a triangle, generalizes not only to three-dimensional space (as stated above), but also to “a space of any number of dimensions.” Moreover, the user mathematician J. Schauder generalized it to the case of “infinite-dimensional” spaces. This direction was further developed in the work of Academician A. N. Tikhonov. The Polish mathematician S. Banach proved an important theorem on the scaling of spaces, which enriched the method of fixed points. Recently, constructions similar to figure 4 have been used for computer calculations of approximations to fixed points and for solving multi-faceted problems.

Exercises

8. Applying Browser's theorem (for a segment) show that the following equation has a solution: a) $x - \cos x = 0$; b) $\cos (\sin x) - x = 0$.

9. The mapping $f:(x, y) \rightarrow (x', y')$, where $x' = x^2 + 1, 5xy, y' = 0, 5xy + y^2$, has a fixed point on the segment $S = \{(x, y) | x \geq 0, y \geq 0, x + y = 1\}$. Prove this using Browser's theorem and also by solving the system $x = x^2 + 1, 5xy; y = 0, 5xy + y^2$.

10. Show that the system

$$\begin{cases} x = \sin(x + y), \\ y = 0, 5(x^2 + xy^3) \end{cases}$$

has a solution.

11. Explore the system

$$\begin{cases} x_1 = x_2^2 + 2x_2x_3 + x_1x_2, \\ x_2 = x_3^2 + x_3x_1, \\ x_3 = x_1^2 + x_1(x_2 + x_3) \end{cases}$$

for the existence of a non-zero solution (by Browser’s theorem). Solve it with basic means.
