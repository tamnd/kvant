---
id: 1976-11-perevalov-graficheskoe-zadanie-funktsii-3ad44dbf
issue: kvant_1976_11
year: 1976
number: "11"
title: Graphical function assignment
authors:
  - Перевалов Г. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 54
page_labels: 47-52
tag: 756I
lang: en
source: kvant_digital
extraction: vision
content_sha256: 716803f754437e2918724fda1aa5d194d76306c7fd5364974677ea8ab4c4db73
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/16_perevalov-graficheskoe-zadanie-funktsii-3ad44dbf.md
source_content_sha256: 789fa17069032a3728ddab6e763449f0e46260d41100e7dfe6f5f4b9c7ce4552
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Graphical function tasks

This summer, during the entrance oral exam in mathematics, in one of the calls, the following conversation took place between the examiner (E) and the applicant (A).

E. What methods of solving functions do you know?

A. There are three ways to solve a function: analytical, tabular and graphical.

E. Give an example of a function specified graphically.

A (after some conversations). Is it necessary to construct a graph of a function? What function?

E. We are not talking about constructing a graph of a function specified, for example, using a formula, but about specifying the function itself using a graph. After all, you just said that the function can be specified graphically. So you need to set, define some graphic function.

A... (silent).

E. Remember what it means to define a function.

A. To define a function, you need to take two sets—set X and set Y—and indicate a correspondence between them such that each x ∈ X is associated with one and only one element from set Y.

E. Okay. Now take a coordinate plane - draw a rectangular coordinate system on the face of the paper and mark the unit of measurement on each axis. Next, take some segment on the Ox axis - this will be the set X, and on the Oy axis - another segment - the set Y. To determine the function, all that remains is to determine the correspondence between this set. How can this be done?

A. The correspondence can be specified using a formula.

E. How about graphic ones? Nazhe is interested in this particular method.

Ah... (silent).

Let's not continue this conversation. The stated task turned out to be overwhelming for the applicant. Difficulties for applicants were also caused by other “graphical” questions, i.e. questions related to graphs of functions - description of the properties of functions according to its graph (research of functions), construction of graphs of functions by transforming a given graph, etc. Discussion of such issues is the purpose of this article.

Some directions

We will need two definitions that you are familiar with. Let us recall them and make a few comments.

Let's take the first one from a school textbook*).

Definition 1. The correspondence between a set X and a set Y, in which each element of the set X corresponds to one and only one element of the set Y, is called a function. A set X is called the domain of definition of a function.

The second is from an article by A. N. Kolmogorov**).

*) Algebra. Textbook for the 6th grade of the middle scale, edited by A. I. Marekshevich (M., “Prosveshchenie”, 1976, p. 69).

**) A. N. Kolmogorov. What is the graph of a function, «Kvant», 1970, No. 2.

⟦folio 48⟧

Definition 2. Let the set $X$ be given a function $y = f(x)$. The graph of a function $y = f(x)$ is the set of all pairs $(x, y)$ such that:

1) the first element $x$ of the pair $(x, y)$ belongs to the domain $X$ of the function $y = f(x)$;
2) the second element $y$ of the pair $(x, y)$ is the value of the function $y = f(x)$ at point $x$.

Thus, for the function $f(x)$ given by the table

$$\begin{array}{c|c|c|c|c|c|c}
x & a & b & c & d & e \\
f(x) & 2 & 1 & 3 & 2 & 1 & 5
\end{array}$$

there will be many graphs
$$\Gamma_f = \{(a, 2), (6, 1), (b, 3), (r, 2), (d, 1), (e, 5)\}.$$

For a function with an infinite domain of definition, it is naturally impossible to write down all pairs $(x, f(x))$. Therefore, we have to describe these pairs differently. For example, for the function $y = f(x) = x^2$, $x \in R$ the graph consists of all possible pairs of real numbers of the form $(x, x^2)$, i.e., from all pairs $(x, y)$ for which the condition $y = x^2$ is satisfied. Using set theory notation, the definition of the graph of the function $y = x^2$ can be written as the formula
$$\Gamma_f = \{(x, y) \mid x \in R, y = x^2\}.$$
And the general definition of the graph of the function $y = f(x)$, $x \in X$ can be written as the following formula:
$$\Gamma_f = \{(x, y) \mid x \in X, y = f(x)\}.$$
In what follows we will restrict ourselves to numerical functions. For numerical functions $y = f(x)$ the domain consists of real numbers, the values ​​of these functions are also real numbers, and the graph consists of all pairs $(x, y)$ of real numbers $x$ and $y$ for which the condition $y = f(x)$ is satisfied.

Recall that the set of all pairs $(x, y)$ of real numbers $x$ and $y$ is called the number plane and is denoted by the symbol $R^2$, and any subset of points on the number plane is called a geometric figure. The geometric figure will be, for example, the axis $Ox$, i.e. a set of points
$$\{(x, y) \mid x \in R, y = 0\}.$$
The graph of the number function $y = f(x)$ will also be a figure on the number plane $R^2$.

Points and geometric figures of the numerical plane (in particular, graphs of numerical functions) can be visually depicted in the drawing. To do this, we construct a coordinate plane and on it, by a point with coordinates $x, y$, we depict the point $(x; y)$ of the number plane.

According to Definition 1, each element $x \in X$ corresponds to one and only one element $y$ from the set $Y$, therefore the set $\Gamma_f$ - the graph of the function $y = f(x)$ - should not contain two pairs with common first elements and different second ones, i.e. on the graph of a numerical function there should not be two points with the same abscissa and different ordinates. Let us formulate this fact in the form of a theorem.

Theorem 1. If the set $\Gamma_f$ is the graph of a numerical function $y = f(x)$, then which line parallel to the axis $Oy$ must have more than one common point with the set $\Gamma_f$.

After these preliminary remarks, let us turn to the questions posed at the beginning.

Graphical way of specifying functions
Let us take the point $(x; y)$ on the coordinate plane. We will assume that the point $(x; y)$ corresponds to the number $x$ - the abscissa of the point - with the number $y$ - the ordinate of the point.

Now on the coordinate plane we take some exact set $M$, i.e., the set of pairs $(x; y)$ of real numbers $x$ and $y$. Set of all abscissas $x$ points $(x; y) \in M$

⟦folio 49⟧

Fig. 1.

Let us denote by $X = \{x\}$, the set of all coordinates $y$ of these points by $Y = \{y\}$. We will assume that the set $M$ assigns to the number $x \in X$ all those numbers $y \in Y$ that are the ordinates of the points $(x; y) \in M$ (i.e. points having the same abscissa equal to $x$). Then we say that the set $M$ defines a correspondence $f$ between the sets $X$ and $Y$. The set $M$ itself is called the correspondence graph $f$.

For example, on figure 1 the set $M$ is a circle of radius 5 with center at the origin. This circle specifies the correspondence between the segment [—5; 5] on the $Ox$ axis and the segment [—5; 5] on axis $Oy$. Point 3 on the $Ox$ axis corresponds to 4 and -4 on the $Oy$ axis, point 5 on the $Ox$ axis corresponds to point 0 on the $Oy$ axis, etc.

When will the correspondence $f$, a given set $M$ on the coordinate plane, be a function? To answer this question, let's look at the definition of a function. It immediately follows that the correspondence $f$, defined by the set $M$, will be a function if each abscissa $x \in X$ corresponds to a unique ordinata $y \in Y$. We obtain the theorem converse to Theorem 1.

Theorem 2. If the set of sets $M$ on the coordinate plane has the maxim that every line parallel to the axis $Oy$ intersects it at most at one point, then the set $M$ is the graph of some function $y = f(x)$.

Combining Theorems 1 and 2, we obtain the following theorem.

Theorem 3. In order for the set $M$ on the coordinate plane to be the graph of some function (to define a function), it is necessary and sufficient that each straight line parallel to the axis $Oy$ intersects it no more than once (has at most one common point with $M$).

Now we see that the set $M$ on figure 1 does not define a function - a straight line parallel to the axis $Oy$ and passing through the point (3,0) intersects the set $M$ at two points; the same is true for all other points in the interval - 5; 5].

But the correspondence $f$ between the set $X = [1; 5]$ on the axis $Ox$ and $Y = [1; 3]$ on the axis $Oy$, the defined set $M$ on figure 2, is a function—each straight line parallel to the axis $Oy$ intersects the set $M$ in at most one point.

⟦folio 50⟧

Fig. 4.

Note that for the given set $X \subset (Ox)$, $Y \subset (Oy)$ one can construct infinitely many functions with domain $X$ that take values ​​in $Y$. Thus, on figure 3 each of the three curves is a graph of some function with a domain of definition $|a; b| \subset (Ox)$ taking values ​​in $|c; d| \subset (Oy)$, i.e., each of them defines a graph function.

Here's roughly what an applicant should know about the issue of graphically assigning functions.

Function Research

Let the function $y = f(x)$ be given by its graph. It needs to be explored.

This means the following.

1. Name of the function definition.
2. Name of function values; find out if the function is limited.
3. Find out whether the function has the most and least value.
4. Determine whether the function is even (odd) or periodic.
5. The name of the intervals on which the function is positive is negative; find out where the function goes to zero.
6. The name of the intervals of return, decrease, constancy of the function.

Fig. 5.

⟦folio 51⟧

For such a study, functions require well-known definitions: an even (odd) function, a returning (decreasing) function in the interval, a bounded function, and so on. All these definitions are usually used to study a function given by a formula (analytic), but they are suitable for studying any numerical function, no matter how it is specified. Therefore, all definitions will “work” for functions specified graphically. (You just need to take into account that each image of a function graph - say, with a pencil on paper - is approximate and gives only a general idea of ​​the function, not allowing you to accurately determine the value of the function at a given point.) Let's look at one example.

Function $y = f(x)$ is assigned to figure 4. Let's explore it according to the given diagram.

1. Domain of the function $f: X = [-1; 4]$.
2. The set of values ​​of the function $f: Y = [-1; 2]$. The function $f$ is limited, since for all $x \in X$ there will be $|f(x)| \leq 2$.
3. The function $f$ takes its greatest value at the point $x = 4$, $f(4) = 2$, the smallest at the point $x = -1$, $f(-1) = -1$.
4. The function $f$ is neither even nor odd, since its domain of definition $X$ is not symmetric about the origin (however, this conclusion does not change if the restriction of the function $y = f(x)$ by $a$ units upward (along the $Oy$ axis) is transferred to the graph of the function $y = f(x)$ $a$ units to the left (along the axis $Ox$) compression of the graph of function $y = f(x)$ to axis $Ox$ in relation to $1/k$

$y = f(x) (k > 0)$
reflection of the graph of the function $y = f(x)$ relative to the axis $Ox$

$y = f(kx) (k > 0)$
compression of the graph of the function $y = f(x)$ to the axis $Oy$ in relation to $1:(1/k)$

$y = f(-x)$
reflection of the graph of the function $y = f(x)$ relative to the axis $Oy$

$y = |f(x)|$
reflection relative to the $Ox$ axis of the part of the graph of the function $y = f(x)$ lying below the $Ox$ axis

⟦folio 52⟧

reduce the domain of definition of the functions $f$ to the interval $[-1; 1]$, since $f(-1)=-1$, $f(1)=0$, and $f(1)\neq f(-1)$, $f(1)\neq -f(-1)$. The function $f$ is non-periodic, since its domain of definition is limited.

5. The function $f$ is positive in the intervals $[-1; -\frac{1}{2}]$ and $[1; 3]$; $3[$. At points $x=-\frac{1}{2}$, $x=1$ and $x=3$ the function vanishes.

6. The function $f$ increases in the intervals $[-1; 0]$ and $[2; 4]$ and decreases in the interval $[0; 2]$.

This is how functions are studied according to their graph.

Plotting function graphs by transforming a given graph

By transforming the graph of functions $y=\sin x$, in grade 10 you received graphs of functions $y=A\sin(kx+\theta)$, where $A$, $k$, $\theta$ are real numbers. In the same way, by transforming the graph of functions $y=f(x)$, you can build graphs of a number of other functions. Let the function $y=f(x)$ be given by its graph. Using this graph, the applicant must be able to construct graphs of the following functions: $y=f(x)+a$, $y=f(x+a)$, $y=kf(x)$, $y=f(kx)$, $y=|f(x)|$ ($a$, $k$ are real numbers), as well as graphs of functions obtained with various combinations of these transformations (such as $y=kf(x+a)$ and etc.). Geometric transformations of the graph of functions $y=f(x)$, which produce graphs of the above functions, are collected in the table (see p. 51 and Fig. 5).

The reader can find a description of methods for constructing function graphs in textbooks on mathematics, for example: G. V. Dorofeev, M. K. Potapov, N. Kh. Rozov. Mathematics manual. M., “Science”, 1976.

Exercises

1. Investigate the function $y=f(x)$ given graphically (Fig. 6).
2. The graph of the function $y=f(x)$ (Fig. 7) is given. Construct graphs of the function: a) $y=f(x)-2$; b) $y=f(x)+2$; c) $y=-f(x)$; d) $y=2f(x)$; l) $y=f(2x)$; e) $y=|f(x)|$; g) $y=f(-x)$.
3. Graphs $y=f(x)$ are given. Construct graphs of the functions listed in Exercise 2 if: a) $f(x)=x^2$; b) $f(x)=10^x$; c) $f(x)=\lg x$; d) $f(x)=\sin x$.
