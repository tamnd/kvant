---
id: 1980-9-gegeliya-printsip-szhimayuschih-otobrazheniy-df86cf81
issue: kvant_1980_9
year: 1980
number: "9"
title: The principle of contraction mappings
authors:
  - Гегелия Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 30
page_last: 34
page_labels: 28-32
tag: W3RC
lang: en
source: kvant_digital
extraction: vision
content_sha256: bf92812a3834c0d26697d7fcced91384b3014087e60db87887ee762046078194
prompt_sha256: draft-1
translated_from: content/ru/1980/09/articles/12_gegeliya-printsip-szhimayuschih-otobrazheniy-df86cf81.md
source_content_sha256: 350ee970db584c7690ad54c9e32b3b587e69524045dd64d5633f87a9ff5701d2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

Sights of skimming displays

(From the NOU chronicle)

This article is based on a report given by its author, then a tenth-grader, at the “Mathematics Festival” in Batumi. It talks about one important theorem, which in our part is used when solving large systems on a computer, but can also be used to approximately find the roots of “typical school” equations.

Fixed points

Let $f$ be a mapping of an arbitrary set $A$ into itself. A point $x \in A$ is called a fixed point $f$ of a mapping $f$ if

$$f(x) = x. \tag{1}$$

When $A \subset R$ (that is, when $f$ is a general numerical function), finding the fixed point of the map $f$ simply means solving equation (1). Conversely, if a given equation is $g(x) = 0$, then its solution will be a fixed point of the mapping $f$, where

$$f(x) = g(x) + x. \tag{2}$$

Let's look at a few examples.

1) Rotation of the plane by a non-zero angle near a given point has a single fixed point (the center of rotation).

2) The parallel translation of a plane to a non-zero vector has no fixed point.

*) Fixed points are also discussed in the article by B. Wertheim («Kvant», 1980, No. 6).

3) The symmetry of a plane relative to a straight line has an infinite number of fixed points (all points of this straight line).

4) The mapping $x \rightarrow ax^2 + bx + c$, where $a \neq 0$, has two, one, or no fixed points depending on the sign of the expression

$$\Delta = (b - 1)^2 - 4ac.$$

Task 1. Construct a map of the plane onto itself that has exactly $n$ fixed points ($n \in \mathbb{N}$).

Compressive display

As we noted above, solving any equation of the form $g(x) = 0$ by a simple technique (by adding $x$ to the left side of the equation) will result in finding a fixed point of some mapping. It is very important for Pozny to know the conditions under which a fixed point exists, and also to be able to find the fixed point itself. We are now specifying this condition.

Let this mapping be $f: A \rightarrow A$, where the distance between points is defined in the set $A$: $d(x, y)$; (for example, $A$ is a subset of a line, plane or space). The mapping $f$ is called skimming if there is a number $a < 1$ such that for any point $x, y$ $A$

$$ad(x, y) \geq d(f(x), f(y)). \tag{3}$$

In other words, the distance between the images of a point is less than the distance between the points themselves, and it decreases by at least $a$ “times”, where $a < 1$. The number $a$ is called the skimming coefficient. Examples:

1) A homothety of a plane with coefficient $0 < k < 1$ will be a skimming map (with coefficient $k$).

2) Rotating a plane is not a skimming display. The following theorem shows why the concept of a skimming map is needed.

Theorem (principle of skimming mappings on a line). All-

⟦folio 29⟧

Fig. 1.

some contraction mapping $f$:
$|a; b| \rightarrow |a; b|$ of the integral into itself has a single fixed point.

The single-walledness of a fixed point is obvious: if there were two of them, then the distance between them should change (according to condition (3)), while it actually remains unchanged (because the points themselves do not move).

The proof of existence is based on a simple but important method of integration: take any point $x_0 \in |a; b|$ and apply $f$ to it repeatedly:

$$x_0, x_1 = f(x_0), x_2 = f(x_1), \dots, x_n = f(x_{n-1}), \dots$$

then the sequence $x_1, x_2, \dots, x_n$ ... converges to using a fixed point.

Before justifying this method (that is, completing the proof of the theorem), we illustrate it with a simple example:

Let $f: ] - 1; 1[ \rightarrow ] - 1; 1[$ be the mapping given by $f(x) = \dot{x}^2$ (Fig. 1). Let's take point $x_0 = 0,1$. Then

$$x_1 = (0,1)^2 = 0,01,$$
$$x_2 = (0,01)^2 = 0,0001,$$

Obviously $\lim_{k \to \infty} x_k = 0$. Point 0 is really stationary, or $0^2 = 0$.

(By the way, we solved the equation $x^2 - x = 0, x \ni 1$; 1[] in this way).

Returning to the proof of the theorem, we denote sequence (4) by $(x_n)$. Let us show that this sequence has the following properties.

(K) For any $\varepsilon > 0$ there is a number $n_0$ such that for all large numbers $n, m > n_0$ the inequality

$$d(x_n, m) < \varepsilon.$$

In other words, points of the sequence with sufficiently large numbers are arbitrarily close.

To prove this, we apply inequality (3) $k$ times; we get

$$d(x_k, x_{k+1}) \leq \alpha^{k-1} d(x_1, x_2).$$

Because

$$d(x_n, x_{n+p}) \leq d(x_n, x_{n+1}) + d(x_{n+1}, x_{n+2}) + \dots + d(x_{n+p-1}, x_{n+p}) \leq \alpha^{n-1} + \alpha^n + \dots + \alpha^{n+p-2} d(x_1, x_n) = \frac{\alpha^{n-1}(1-\alpha)^p}{1-\alpha} d(x_1, x_n) \leq \frac{\alpha^{n-1}}{1-\alpha} d(x_1, x_2).$$

Now for any given $\varepsilon > 0$ we can take as $n_0$

$$n_0 = \log_a \frac{\varepsilon(1-\alpha)}{d(x_1, x_2)}.$$

Then, for any $n, m > n_0$, inequality (6) immediately implies the required

⟦folio 30⟧

Fig. 2.

we need inequality (5) (check!). Property (K) has been proven.

Using property (K), we now prove the convergence of the sequence $(x_n)$. For the number $\varepsilon = 1/2$, by property (K), there is a number $n_1$ such that for $m > n_1$ $d(x_m, x_{n_1}) < 1/2$ is satisfied, that is, $x_m \in ]a_1; b_1[$, where $a_1 = x_{n_1} - 1/2$, $b_1 = x_{n_1} + 1/2$. The further distance is the number $\varepsilon = 1/4$ and similarly we find a number $n_2$ such that for $m > n_2$ $x_m \in ]a_2; b_2[$ is satisfied, where $a_2 = x_{n_2} - 1/2$, $b_2 = x_{n_2} + 1/2$. If one of the points $a_2, b_2$ does not lie in $]a_1; b_1[$, then we will replace it with $a_1$ (corresponding to $b_1$), keeping the designation $]a_2; b_2[$ for the constructed segment. And so on (see Fig. 2).

We obtain a sequence of integrals

$$]a_1; b_1[ \supset ]a_2; b_2[ \supset ... \supset ]a_n; b_n[ \supset ...$$

the length of the $n$-th integral does not exceed $1/2^{n-1}$, and for each of them there is a number such that all $x_i$ with large numbers lie in this integral.

Consider the sequence $(a_n)$ of the left ends of our integrals. It is increasing and bounded from above (for example, by the number $b_1$) and, therefore (see “Algebra and the beginnings of analysis 9”, paragraph 32), has a limit $x = \lim_{n \to \infty} a_n$. Let us show that the same number $x$ is the limit of the sequence $(x_n)$. Really,

$$d(x, x_n) \leq d(x, a_n) + d(a_n, x_n);$$

both terms on the right side are angularly small (for sufficiently large $n$), then $d(x, x_n)$ becomes angularly small (for sufficiently large $n$), that is, $x = \lim_{n \to \infty} x_n$.

All we have to do is prove that $x$ is a fixed point of the mapping $f$. We have

$$0 \leq d(x, f(x)) \leq d(x, x_n) + d(x_n, f(x)) = d(x, x_n) + d(f(x_{n-1}), f(x)) \leq d(x, x_n) + a d(x_{n-1}, x).$$

The last two terms are angularly small (for sufficiently large $n$), which means $d(x, f(x)) = 0$, that is, $f(x) = x$, which is what needed to be proven.

It is easy to see that the theorem will remain true if we replace the integral $]a; b[$ with a segment, a ray, or even the entire straight line $R$. Moreover, it remains true on the plane.

Task 2. Form and prove the principles of skim mappings for a circle on a plane.

Note. Use the coordinates.

If you have done this exercise, it is, of course, clear to you that our aim will remain true for a receive or strip and even in space - say, for a ball. It is natural to ask: how to formulate this principle in order to cover as many cases as possible? How to find the most general formulation?

Having posed this question, we found ourselves in a situation characteristic of the creative work of a research mathematician. And now we'll see

How does a mathematician reason?

A professional mathematician here would think something like this:

We need to find a formulation that generalizes the theorem proved above. To do this, let's look at exactly what properties of this situation were actually required in the proof.

First, we used the definition of skim mapping (3). This means that the set $A$ must contain the distance $d(x, y)$ between points $x, y$ in a straight line - this is the number

$$d(x, y) = |x - y|.$$

But is it important that it is asked exactly this way? Probably not: after all, on the plane $d(x, y)$ is defined differently, but the proof still works. So, you need to look at which distance properties are actually used. Let's see.

⟦folio 31⟧

At the end of the proof, we used the fact that two points located at zero distance coincide. Let's write it like this:

$$d(x, y) = 0 \iff x = y.$$  (I)

Next we needed (where?) to

$$d(x, y) = d(y, x)$$  (II)

(for any $x, y \in A$).

Finally, we have repeatedly (for example, when proving inequality (6)) used the triangle inequality:

$$d(x, z) \leq d(x, y) + d(y, z)$$  (III)

(for any $x, y, z \in A$).

Now let's think - did we need any other properties of distance? Let's look at the proof again; no, nothing more is required from the distance. Thus, we only need general distance aximons.

Let's move on. Let us see how the convergence of sequence (4) with property (K) was proved. Quite clever, using specific properties of intervals on a line. It is difficult to understand which general properties are used here. There is only one way out: “remove the difficulty into the axiom,” that is, the answer was that every sequence with property (K) converges. After all, this is very easy to do—it’s enough to orient yourself to those sets $A$ for which convergence follows from conditions (K)!

Let's summarize. The proof passes for a skimming map if there is a distance in $A$ that satisfies conditions (I)–(III), and any sequence of points in $A$ that has property (K) converges to a point in $A$.

Formulation in the general case

To formulate the theorem we need, let's start with formal definitions. The reader who understands the reasoning of our fictitious professional mathematician will immediately understand why these definitions are the way they are.

The set $A$, on which each pair of points $x, y \in A$ is associated with the number $d(x, y) \in \mathbb{R}$, is called a metric space if conditions (I) - (III) are satisfied for $d$; in this case, the number $d(x, y)$ is called the distance between the points $x$ and $y$.

A sequence of points $x_1, x_2, \dots, x_k$, ... of the metric space $A$ is called functional (or Cauchy sequence) if for any $\varepsilon > 0$ there is a number $n_0$ such that

$$n, m > n_0 \Rightarrow d(x_n, x_m) < \varepsilon.$$

A sequence ($x_n$) in the metric space $A$ is said to be convergent if there exists a point $x$ such that for any $\varepsilon > 0$ there is a number $n_0$ for which

$$n > n_0 \Rightarrow d(x_n, x) < \varepsilon.$$

The point $x$ in this case is called the limit of the sequence $x_n$. Designation: $\lim_{n \to \infty} x_n = x$.

Finally, a metric space is called complete if any function sequence in it converges.

Theorem (general principle of adding mappings). Any skimming map of a complete metric space into itself has a unique fixed point.

The proof is essentially no different from the proof of the first theorem, only the end of the process: from the fact that the sequence (4) is functional (that is, it has property (K)), and from the cavity of the space $A$, by definition it follows that (4) converges.

Task 3. Write the proof in detail.

In fact, the principle of skimming mapping, which is usually associated with the names of Picard and Banach, is not formulated above in the most general form. A more subtle analysis of the proof brought by the mathematician S. Banach to the concept of a complete normed linear space (or, as they say now, a Banach space), for which he proved the theorem. The advantage of this formulation is that the “points” of such a space can be functions, so that the principle becomes applicable to solving, for example, differential equations.

⟦folio 32⟧

How does a computer work?
We have already noted that the integration method gives us a way to approximately find a fixed point:
since the sequence $x_0, x_1 = f(x_0), x_2 = f(x_1)$, ... converges to $x$, the point $x$ can be obtained with a given precision $\varepsilon$ by choosing the number $n$ so that $|x_n - x| < \varepsilon$.

This can be done very well by a computer following the algorithm shown in figure (the so-called “block diagram” of the algorithm). Look at it carefully and try how this algorithm works.

It is clear that under the conditions of the theorem on skim maps, the machine, after a finite number of iterations, prints out the number $x_n$ satisfying the condition $|x_n - x| < \varepsilon$, that is, an approximate (with a given accuracy $\varepsilon$) value $x$. If these conditions are not met, the machine can “work forever” (unless it breaks down without giving us an answer).

In order not to waste expensive computer time, it is advisable, before running the algorithm, to check the fulfillment of the conditions of the theorem on skim maps.

Task 4. Apply the algorithm described above to approximately solve the equation
$$g(x) = x^3 + 3x + x \cos^2 x - \sin(\cos x) = 0,$$

Fig. 4.
