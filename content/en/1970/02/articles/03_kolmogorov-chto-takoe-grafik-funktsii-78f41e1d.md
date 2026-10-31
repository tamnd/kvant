---
id: 1970-2-kolmogorov-chto-takoe-grafik-funktsii-78f41e1d
issue: kvant_1970_2
year: 1970
number: "2"
title: What is a graph of a function
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 5
page_last: 15
page_labels: 3, 4, 5, 6, 7, 8, 9, 10, 12, 13
tag: 669V
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0737daedbc05671d5da2bc968a416e19dc741dbccab19d87c94a8fbaba704b69
prompt_sha256: draft-1
translated_from: content/ru/1970/02/articles/03_kolmogorov-chto-takoe-grafik-funktsii-78f41e1d.md
source_content_sha256: cf759b539caa753e6caf65358e60375dffa5bb27cc2f769097e18b383331a0c9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

WHAT IS A FUNCTION SCHEDULE

A. N. KOLMOGOROV

Here the presentation of the new
more general point of view
well known from school concepts -
function and its graph.
The beginning of this presentation was in the article
"What is a function"
published in the first issue of Quaent.
To understand this article
it is necessary to master the concepts that are defined in the first article

1. REMINDER AND SMALL ADDITIONS

In the first issue of the magazine, under the article “What is a function,” you became acquainted with the modern general understanding of the word function: a function is a perfect arbitrary mapping of a certain set $E$ onto another set $M$. The set $E$ is called the domain of definition of the function, and the set $M$ is the set of its values. To define a function with domain $E$, you need to specify for each element $x$ of this set

1* 3

⟦folio 4⟧

$$y = f(x).$$

Whichever way we do this, we get a function with domain $E$. If the set $E$ consists of students in your class, then you can, for example, for any student $x$ take the second letter of his name as $y = f(x)$ (assuming that there are no students in the class whose name consists of a single letter - although I knew a girl Olya, which was simply “O”).

When specifying a function in this way, the set of its values ​​$M$ will be determined by itself; this is the set of all those objects $y$ for which there is at least one element $x$ the set $E$ for which

$$f(x) = y.$$

Pozny, when describing the meaning of the term function, does not have to explicitly talk about the set of meanings in the description. It would be correct, for example, to simply say that “a function is a law according to which each element $x$ of some set $E$ is put in correspondence in the complete definitions of the object $y = f(x)$.” We support, however, that it is better not to consider all these descriptions to be defined by them. If we really wanted to define the concept of a function through the concept of “law,” then we would be required to precisely define the meaning of the term “law,” etc. We will consider the concept of a function to be one of the basic concepts of mathematics, the meaning of which is only explained, and not given by a formal definition.

At school you are used to dealing only with numbers, the domain of which consists of numbers and the values ​​of which are numbers. The meaning of the expression “numeric function of a numeric argument” is not completely defined. After all, the very concept of number in school is constructed and generalized. We will stick to the system of all actions of them and villages, which schoolchildren become familiar with in the ninth grade. Real functions of a real argument are studied primarily in high schools. You can draw their graphs on the “number plane”.

In school textbooks they write that the “numerical plane” is a plane on which coordinates are introduced in a neotropic, definite way. If you take the textbook literally, there are a lot of number planes. Wires on the chalkboard coordinate axes, the teacher turns the plane of this board into a “number plane”; Students create new “number planes” on the pages of their terradis, sometimes several on one page!

In paragraph 3 of this article, you learned which number plane mathematicians actually deal with. But first I would like to make one additional remark to the presentation of the article “What is a function”.

In the school algebra course, they most often deal with functions defined “analytically” using a formula. The domain of definition of such a function, unless nothing else is said, is considered to be the set of all those values ​​of the argument for which all the prescribed formulas for operations on numbers are feasible. Let us, for example, as is customary in school, consider

*) From the first article you know that the values ​​of a function can be not only numbers, but also dynamins, boys or girls, in general any objects, or, as they say, “objects”.

⟦folio 5⟧

table the sign $V$ is the sign of the “arithmetic” square root. It is clear that the formula

$$y = f(x) = (\sqrt{x})^2$$

(1)

allows you to calculate the corresponding value $y$ from a given $x$ only if $x$ is non-negative (otherwise the square root is “not extracted”).

For non-negative $x$

$$y = f(x) = x.$$

(2)

Formula (2) is simpler than formula (1), and we would like to consider it a formula that defines our function. But the domain of definition of the function given by formula (2) consists not of only non-negative numbers $x$, but of all numbers $x$. If we want to give a new definition of the very function that is defined by formula (1), we need to write

$$y = f(x) = \begin{cases} x \text{ при } x \geq 0, \\ \text{ не определена при } x < 0. \end{cases}$$

(3)

Similarly, the function $g(x) = \frac{x^3 - 1}{x - 1}$ can be written as follows:

$$g(x) = \begin{cases} x^2 + x + 1 \text{ при } x \neq 1, \\ \text{ не определена при } x = 1. \end{cases}$$

(4)

In school and university exams, complete accuracy is required in such matters.

2. FUNCTION SCHEDULE

Consider the following duty schedule (see No. 1 «Kvant», p. 29):

| | Mon | W | Wed | Thu | Fri | Sat | Sun |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Petya | | | | | | | |
| Kolya | | | | | | | |
| Sasha | | | | | | | |
| Voloda | | | | | | | |

We already know that this is a graph of a function: the name of the attendant can be considered a function of the day of the week. Since there are a network of days of the week, and there are four boys, we drew

$$7 \times 4 = 28$$

cells, but only seven of these cells were painted red. If the boys had decided to alphabetize their names, the table would have been the one shown on page 6. It looks different, but shows the same distribution of duties - the same function.

⟦folio 6⟧

In both tables, 28 cells correspond to 28 possible pairs (day of the week, boy).

Of these 28 pairs, seven pairs were identified
(Mon, Petya), (Tue, Kolya), (cp, Sasha), (Thu, Voloda),
(Fri, Petya), (Sat, Kolya), (Sun, Sasha),

i.e. all pairs in which the day of the week is connected to the day of the week for this day:
(day of the week, day for this day),

or abstractly: pairs of the form
$(x, f(x))$.

Only the choice of these pairs is essential for specifying functions.
After this example, you may not think this definition is necessary:
The graph of the function $f$ is the set of all such pairs $*$
$(x, y)$,
that: 1) the first element of the pair $x$ belongs to the domain of definition of the function,
2) second element of the pair
$$y = f(x).$$

| | Mon | W | Wed | Thu | Fri | Sat | Sun |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Voloda | | | | | | | |
| Kolya | | | | | | | |
| Petya | | | | | | | |
| Sasha | | | | | | | |

In our example, the graph of the function $f$:
$$\Gamma_f = \{(пн, Петя), (вт, Коля), (cp, Саша), (чт, Волода), (пт, Петя), (сб, Коля), (вс, Саша)\}.$$
For functions specified by the table

| $x$ | $f_1$ | $f_2$ | $f_3$ | $f_4$ |
| :--- | :--- | :--- | :--- | :--- |
| $A$ | $A$ | $B$ | $A$ | $B$ |
| $B$ | $A$ | $B$ | $B$ | $A$ |

*) Throughout this article we mean “ordered pairs”. The pair (1,2) is different from the pair (2,1). The first and second elements of a pair may coincide: (1,1) or (2,2) are also pairs.

⟦folio 7⟧

in accordance with these definitions we obtain graphs

$$\Gamma_1 = \{(A, A), (B, A)\}, \quad \Gamma_2 = \{(A, B), (B, B)\},
\quad \Gamma_3 = \{(A, A), (B, B)\}, \quad \Gamma_4 = \{(A, B), (B, A)\}.$$

It is clear that for a function with a finite domain of definition, the number of elements of the graph (i.e., the number of pairs included in the graph) is equal to the number of elements of the domain of definition of the function. For a function with an infinite domain of definition, all pairs

$$(x, f(x))$$

cannot be written out. We have to describe these pairs using their properties. For example, for the function

$$y = f(x) = \sqrt{1-x^2}$$

the graph consists of all pairs $(x, y)$ for which two conditions are met

$$x^2 + y^2 = 1 \text{ и } y \geq 0.$$

This definition of the graph of a function can be written as

$$\Gamma_f = \{(x, y) | x^2 + y^2 = 1, \ y \geq 0\}.$$

The very general definition of the graph of the function $f$ can be written in the form of the following formula *):

$$\Gamma_f = \{(x, y) | y = f(x)\}.$$

By defining the graph of a function as a set of pairs, each of which consists of an argument value and a function value corresponding to this argument value, we have freed the concept of a graph from everything random. In this abstract understanding, each function has one single graph.

3. NUMERICAL PLANE

Let us turn to the most general real functions of a real variable in school. At school you learned that the graph of such a function $f$ is the set of those points $P(x, y)$ of the number plane whose coordinates $x$ and $y$ satisfy the equality

$$y = f(x).$$

This formulation and the general definition of a schedule given above in paragraph 2 are similar, but slightly different. Section 2 talks about the set of pairs $(x, y)$, and in the general school definition - about the set of points $P$ with coordinates $x$ and $y$. But is it possible to bring these two formulations into complete agreement?

*) We use the standard notation adopted in set theory.

$$\{x | A(x)\}$$

denotes the set of all objects $x$ satisfying the condition $A(x)$. For example, $\{x | x^2 = 1\}$ is the set of all $x$ for which $x^2 = 1$, i.e. the set of two numbers: $\{1, -1\}$.

⟦folio 8⟧

It turns out it's very simple. This simple solution has become widespread in modern scientific literature. By definition, the number plane is considered to be the set of all pairs of real numbers. The number plane is denoted $R^2$. Its definition can be written symbolically

$$R^2 = \{x, y \mid x \in R, y \in R\}.$$

After thinking a little, you will see for yourself that with this definition of the number plane, the usually school definition of the graph of a real function of a real variable becomes part of the general definition given in paragraph 2.

The notation $P(x, y)$ for a point with coordinates $x$ and $y$ is now redundant. The points of the number plane in the new understanding are simple сaml pairs of numbers $(x, y)$. We can simply talk about “point $(0, 0)$” (the origin), about points $(1, 2), (-2, -1)$, etc.

It is worth noting that the term “number line” must now be given a new meaning: the number line is simply the set of real numbers $R$ itself. Naturally, the points of the number line must be considered as simple real numbers. Obviously this is not said directly in school textbooks, but is often used in geometric language when applied to numbers: a set of numbers

$$[a, b] = \{x \mid a \leqslant x \leqslant b\}$$

called a “segment”, they say that “point” 2 belongs to the “segment” [1, 3], etc.

We will call any set of points on the number plane a geometric figure located on the number plane. Such, for example, is a circle with center $(0, 0)$ and radius one: this is a set of points, i.e. pairs of numbers $(x, y)$, for which

$$x^2 + y^2 = 1.$$

Naturally, points and geometric figures of the number plane can be visually depicted in the drawing. To do this, coordinate axes are selected on a real plane (sheet of paper or chalkboard) and the point of the numerical plane $(x, y)$ is depicted as a real point with coordinates $x$ and $y$. Of course, such an image can only be approximate. Graphs drawn on paper or a chalkboard are only approximate images of “real” graphs of functions, which in our understanding are a simple subset of the number plane. These “real” graphs include the statement that a function is completely determined by its graph.

Let there be a set of pairs

$$M = \{(x, y)\}.$$

Such a set, for example, is any “figure” on the number plane. What additional requirement should be required for this set of pairs to be the graph of some function?

⟦folio 9⟧

The answer is not complicated: for this it is necessary and sufficient that in the set $M$ it is impossible to find two pairs $(x, y_1)$ and $(x, y_2)$ with a common first element $x$ and different second elements $y_1 \neq y_2$. (Do the proof yourself.) On Fig. 1, the red curve is the graph of the function, but the black curve is not the graph.

The set of pairs $(x, y)$, in which there are no two pairs of the form $(x, y_1), (x, y_2), y_1 \neq y_2$, can be called a functional graph. Please note that we have now defined a “functional graph” without using the concept of “function”. Is it possible, from this point of view, to give a formulaic definition of the very concept of function, which we considered basic, that is, not subject to formal definition? I don't want to answer this question here. It's not entirely simple. In our journal we will have occasion to return both to modern ideas about the concept of function and to its history.

4. GEOMETRIC TRANSFORMATIONS

To free ourselves from a broad general understanding of the term “function,” let’s consider some more simple geometic transformations.

To rotate a flat funkru around the point $O$ (Fig. 2), you can transfer the contours of the function to a tracing paper placed on the drawing plane, secure the tracing paper with a pin at point $O$ and, rotate the tracing paper, transfer the contours of a copy of the function from the tracing paper to the drawing plane (for example, using carbon paper). When rotating, all funcra points rotate around $O$ in the same direction by the same angle.

Let's denote

$$Q = R_0^\alpha(P)$$ (1)

position of point $P$ after rotation by angle $\alpha$ counterclockwise. If the point $O$ and the angle $\alpha$ are given, then each point $P$ according to formula (1) corresponds to the complete definition of the point $Q$. It is clear that in the sense of our definition, $R_0^\alpha$ is a function. Its domain of definition is a multi-line point of the plane $P$.

Rotation angles are indicated with a sign. On Fig. 3 points $Q_2$ are obtained from point $P$ by turning to $120^\circ$, and points $Q_1$ by turning to $-120^\circ$ (or turning to $240^\circ$). If point $Q$ is obtained from point $P$ by rotating $\alpha$ degrees, then point $P$ can be obtained by rotating $Q$ by $-\alpha$ degrees: if

$$Q = R_0^\alpha(P),$$

⟦folio 10⟧

$$P = R^{-\alpha} o(Q).$$

We see that the rotation $R_0^\alpha$ is always an invertible function.

When applied to rotations, people often talk about “mappings.” The inverse of rotation $R_0^\alpha$ is rotation $R_0^{-\alpha}$. Symbolically we can write:

$$R_0^{-\alpha} (R_0^\alpha(P)) = P,$$
$$(R_0^\alpha)^{-1} = R_0^{-\alpha}.$$

A rotation maps a set of plane points onto itself. If we assume that a plane is nothing more than a set of its points (this is what is done in the modern presentation of geometry), then we can say that rotation is a reversible mapping of the plane onto itself.

Invertible mappings of a plane onto itself are called geometric transformations of the plane. You have repeatedly encountered geometric transformations on the pages of our magazine. For now, we will give just one more example of a geometric transformation of a plane. Parallel translation is the mapping of a plane onto itself

$$P \rightarrow Q = T(P),$$

in which all points $P$ move the same distance and in the same direction (Fig. 4).

5. VECTORS

Although it turned out that you have already established from acquaintance with new concepts and unusual interpretations that you already know, we will make another successful one. Let's try to understand what a parallel transfer graph $P \rightarrow Q = T(P)$ is. By general definition, this is the set of all such pairs of points

$$(A, B),$$

for which

$$B = T(A).$$

⟦folio 12⟧

3. What additional condition should be added to the formula?
$$f(x) = 1,$$
to get certain functions
$$f_4(x) = (\sqrt{x})^2 + (\sqrt{1-x})^2?$$

Note e. In problems 1-3, the sign $V$ is understood as an “arithmetic” square root, i.e., a non-negative number.

2. Graph of a function

4. How many functions exist with domain 1, 2, 3 whose graphs are subsets of the set of pairs
$$\{(1,1), (1,2), (2,1), (2,2), (2,3), (3,3)\}$$

(cm. Fig. 6)?
How many of these functions have an inverse?

5. Show that the graph of the inverse function $f^{-1}$ is given by
$$\Gamma_{f^{-1}} = \{(x, y) | (y, x) \in \Gamma_f\}.$$
(Naturally, the function $f$ is assumed to have an inverse.)

3. Number plane

6. Describe the structure of the graph of the Dirichlet function:
$$D(x) = \begin{cases} 1, если x рационально, \\ 0, если x irrationalно. \end{cases}$$

7*) Number $x$ from the segment [0; 1] decomposes into an infinite track fraction
$$x = 0, x_1 x_2 x_3 \dots (x_n = 0, 1, 2).$$

The value of the function $y = C(x)$ is determined by the double fraction
$$y = 0, y_1 y_2 y_3 \dots (y_n = 0, 1)$$
as follows:
if $x_n = 0$ then $y_n = 0$,
if $x_n = 1$ or $x_n = 2$, then:
$$y_n = 1$$ provided that there were no ones among the digits $x_1, x_2, \dots, x_{n-1}$,
$$y_n = 0$$ provided that among the digits $x_1, x_2, \dots, x_{n-1}$ one unit has already been encountered.

Try to graph this function. Prove that it contains an infinite number of horizontal segments. If you are familiar with understandable function continuity, try to prove that our function is continuous.

Note e. In this problem we do not avoid ternary fractions, in which all signs, starting from some, are twos, and double fractions, in which all signs, starting from some, are ones. For example, we write in the ternary system
$$0,2222 \dots = 1; 0,1222 \dots = 0,200000 \dots$$

and in the dual system we believe that
$$0,1111111 \dots = 1; 0,01011111 \dots = 0,01100000 \dots$$

*) This is a difficult task (see § 15 in the book: S.V. Fomin “Number Systems”, 1968.

⟦folio 13⟧

4. Geometric transformations

8. Describe in geometric terms transformations of the number plane that are similar to formulaic problems:

a) $(x, y) \rightarrow (-y, x)$,
b) $(x, y) \rightarrow (x, -y)$,
c) $(x, y) \rightarrow (y, -x)$,
d) $(x, y) \rightarrow (x+1, y)$,
e) $(x, y) \rightarrow (x+a, y+a)$.

9. Prove the formula for rotations around the center $O$

$$R_O^\alpha [R_O^\beta (P)] = R_O^{\alpha+\beta}(P).$$

(1)

10. Prove that for any centers $O_1$ and $O_2$ the transformation

$$F(P) = R_O^\alpha [R_O^{-\alpha}(P)]$$

will be a parallel transfer. How far and in what direction?

5. Vectors

11. Prove the formula

$$T_a [T_b(P)] = T_{a+b}(P).$$

(2)

12. Show that the transformation

$$F(P) = T_a [R_O^\alpha(P)]$$

is a rotation through angle $\alpha$. Around what center?

Comment. Formulas (1) and (2) are written in short

$$R_O^\alpha R_O^\beta = R_O^{\alpha+\beta},$$

$$T_a T_b = T_{a+b}.$$

Taking a function from functions is similar to multiplication in many ways. But this is a special topic, the development of which is not decreasing in this country. We will use this short notation for functions of functions (compositions of mappings) in Problems 13 and 14.

13. Prove that you always

$$T_a T_b = T_b T_a$$

And

$$R_O^\alpha R_O^\beta = R_O^\beta R_O^\alpha$$

when turning around the center. Show with an example that, in general,

$$R_O^\alpha R_O^\beta \neq R_O^\beta R_O^\alpha$$

when turning around centers $O_1, O_2$.

14. Find out fully the question of when

$$R_O^\alpha R_O^\beta = R_O^\beta R_O^\alpha.$$
