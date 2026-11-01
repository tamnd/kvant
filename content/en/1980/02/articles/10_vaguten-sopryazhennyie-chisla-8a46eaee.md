---
id: 1980-2-vaguten-sopryazhennyie-chisla-8a46eaee
issue: kvant_1980_2
year: 1980
number: "2"
title: Conjugate numbers
authors:
  - Вагутен Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 33
page_labels: 26, 28, 29, 30, 31
tag: 23LY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 45fb091cf9501ac68f4ed4b01e59370d3d2ff6e6d5adac21610333e2d6fb15d3
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/10_vaguten-sopryazhennyie-chisla-8a46eaee.md
source_content_sha256: b885f798700a8cb8eeb774054181a25b6237201c2c555d529864a38f089532a8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Math circle

N. Vaeuten

Number conjugation

You can read this article (or conduct a math circle lesson based on it) in different ways. The simplest way is to analyze the solutions to the problems proposed in it, skipping the fine print, and then consolidate the demonstrated techniques and redo the exercises suggested at the end of the article. But if you are interested in this or that problem or series of problems, you can do it differently: carefully read the text placed after it in small print and, using the additional literature indicated by the author, more deeply understand the essence of the issues raised.

The reader is probably aware at first glance of some difficult geometric problems that are instantly solved if one given point is replaced by another that is symmetrical to it relative to some straight line. Symmetric messages are also very important in algebra.

In this article we will consider a number of situations in which it is useful to replace a number of the form $a+b\sqrt{d}$ with its conjugate $a-b\sqrt{d}$. We'll see how this simple trick of changing the sign in front of a radial helps in solving a variety of algebra and analysis problems - from unlived assessments and transformations to difficult olympid problems and the ingenious inventions of competitive exam writers.

Most of our examples can serve as a first acquaintance with global mathematical theories (in some places we indicate articles and books to continue the acquaintance). Among the problems included in the article, two are from Problem Book «Kvant» and several are from letters from readers who have already experienced the satisfaction of tricks with radials and irons and share them with others.

Pairs of conjugate numbers appear quite naturally when we solve a quadratic equation without taking the discriminate root: say, the equation $\lambda^2-\lambda-1=0$ has a pair of “conjugate” roots: $\lambda_1=\frac{1-\sqrt{5}}{2}$ and $\lambda_2=\frac{1+\sqrt{5}}{2}$. We will return to this later, but let’s start with examples of a different kind: dealing with “transfers”...

⟦folio 28⟧

(here, of course, we were lucky: the difference of squares $(2n+1)^2-4n(n+1)$ is equal to 1)
$$\leq \frac{1}{(2\sqrt{n}+\sqrt{n})(2n+2n)} = \frac{1}{16n\sqrt{n}}.$$

Note that this estimate is also very accurate. But it is better to verify this (and generally study the behavior of a function with polyimpalas) not using algebraic transformations, but by means of analysis - replacing the variable $n$ with $h$ $1/n$ and using Taylor’s formula $\sqrt{1+h} = 1+h/2 - h^2/8 + \dots$ (See [6]).

Replace flat with minus

We have already talked about the use of symmetry in geometric problems. A kind of symmetry in algebra is replacing a plane with a minus.

Thus, if any expression from $\sqrt{d}$ is equal to $p+q\sqrt{d}$ and we replace $\sqrt{d}$ with $-\sqrt{d}$ throughout this expression, then it is natural to expect that the new expression turns out to be equal to the conjugate number $p-q\sqrt{d}$. We will use the following obvious special case of this property ($a$ and $b$ are rational, $\sqrt{d}$ are not):

$$(a+b\sqrt{d})^n = p+q\sqrt{d} \Rightarrow (a-b\sqrt{d})^n = p-q\sqrt{d}.$$

5. Prove that the equation

$$(x+y\sqrt{5})^4+(z+t\sqrt{5})^4 = 2+\sqrt{5}$$

has no solutions in rational numbers $x, y, z, t$.

You can, of course, find a separate sum of the terms on the left side that do not contain $\sqrt{5}$ (it should be equal to 2), and separately the coefficient of $\sqrt{5}$ (it should be equal to 1). But what to do with the resulting cumbersome system is unclear. Instead, let's use (4) and replace the flat before $\sqrt{5}$ with a minus!

$$(x-y\sqrt{5})^4+(z-t\sqrt{5})^4 = 2-\sqrt{5}.$$

There is a non-negative number on the left, a negative number on the right.

6. Prove that there are infinitely many pairs of $(x; y)$ natural numbers for which $x^2$ differs from $2y^2$ by 1:

$$|x^2-2y^2| = 1.$$

Several such pairs with small $(x; y)$ are easy to find by selection: these are $(1; 2)$, $(3; 2)$, $(7; 5)$, $(17; 12)$, ... (Fig. 1). How to continue this set? Is it possible to write down a general formula for these solutions?

Fig. 1. Can these hyperbolas be encoded through an infinite number of knots of checkered paper?

The number $1+\sqrt{2}$ will help us find answers to these questions. A pattern that allows you to obtain all new solutions $(x; y)$, indicating in the table:

$$\begin{array}{c|c|c|c|c|c}
n & (1+\sqrt{2})^n & x_n & y_n & x_n^2-2y_n^2 & (1-\sqrt{2})^n \\
1 & 1+\sqrt{2} & 1 & 1 & 1-2=-1 & 1-\sqrt{2} \\
2 & 3+2\sqrt{2} & 3 & 2 & 9-8=1 & 3-2\sqrt{2} \\
3 & 7+5\sqrt{2} & 7 & 5 & 49-50=-1 & 7-5\sqrt{2} \\
4 & 17+12\sqrt{2} & 17 & 12 & 289-288=1 & 17-12\sqrt{2} \\
5 & 41+29\sqrt{2} & 41 & 29 & 1681-1682=-1 & 41-29\sqrt{2} \\
\dots & \dots & \dots & \dots & \dots & \dots \\
\end{array}$$

What will the sixth line be?

It can be seen that the coefficients $x_n, y_n$ in the number $x_n+y_n\sqrt{2} = (1+\sqrt{2})^n$ will give the desired pair. A table of conjugate numbers will help prove this (we again use (4)):

$$x_n-y_n\sqrt{2} = (1-\sqrt{2})^n.$$

Variable the last two equalities, we get

$$x_n^2-2y_n^2 = (1+\sqrt{2})^n(1-\sqrt{2})^n = \\
= ((1+\sqrt{2})(1-\sqrt{2}))^n = (-1)^n,$$

and the expression we are interested in is alternately equal to either 1 or - 1. Adding and subtracting these same two equalities, we obtain an explicit expression for $x_n$ and $y_n$:

$$x_n = ((1+\sqrt{2})^n + (1-\sqrt{2})^n)/2$$

$$y_n = ((1+\sqrt{2})^n - (1-\sqrt{2})^n)/2\sqrt{2}.$$

⟦folio 29⟧

Is it possible to solve this problem about integers without the irrational numbers $1 + \sqrt{2}$ and $1 - \sqrt{2}$? Now, knowing the answer, we can easily express $(x_{n+1}; y_{n+1})$ in terms of the previous pair $(x_n; y_n)$ from $x_{n+1} + y_{n+1}\sqrt{2} = (x_n + y_n\sqrt{2}) (1 - \sqrt{2})$ follows

$$x_{n+1} = x_n + 2y_n, \quad y_{n+1} = x_n + y_n.$$ (6)

Before this recurrence relation it was possible, apparently, to agree on several first solutions, and then check that

$$|x_n^2 - 2y_n^2| = |x_{n+1}^2 - 2y_{n+1}^2|.$$

By adding the initial condition $x_1 = 1, y_1 = 1$, from here (by induction) we could conclude that $|x_n^2 - 2y_n^2| = 1$ for any $n$. Further, by expressing $(x_n; y_n)$ back through $(x_{n+1}; y_{n+1})$, the “descent method” ([8]) we can prove that the found series exhausts all solutions of equation (5) in natural numbers $(x; y)$. Any “Pell equation” $x^2 - dy^2 = c$ can be solved in a similar way (and any quadratic equation in integers $x, y$ can be applied to an equation of this type of property), but the original equation can have several solved series ([7]).

Recurrence relations of type (6) arise not only in number theory, but also in various problems of analysis and probability theory. Here is a typical example of a combinatorial problem of this type (it was proposed at the last international optimization in London):

7(M595). At the top $A$ of the correct vosmtsuolnika sits a frog. From any vertex of the vertex, except for vertex $E$, opposite $A$, it can go to any of the two neighboring vertices. Once in $E$, the frog stops and remains there. Find co-

The number of $e_m$ different ways that a frog can get from top $A$ to $E$ in exactly $m$ jumps.

If you color the vertices of the jumper one after another in black and white (Fig. 2), it immediately becomes clear that $c_{2k-1} = 0$ for any $k$: the color of the vertices changes with each jump. Let us denote by $a_n$ and $c_n$ the number of ways that a frog can, in $2n$ jumps, get from vertex $A$, respectively, to vertex $A$ and to one of the vertices $C$ (from the symmetry messages it is clear that in each of the vertices designated on figure by the letter $C$, you can get there in the same number of ways). How to easily check (see Fig. 2a, b, c, f)),

$$a_1 = 2, \quad c_1 = 1;$$

$$a_{n+1} = 2a_n + 2c_n,$$

$$c_{n+1} = a_n + 2c_n.$$ (7)

And the number we are interested in $e_{2n}$ is equal, very much, $2c_{n-1}$ (Fig. 2d).

How can we find an explicit formula for $a_n$ and $c_n$? Let us write our recurrence relation (7) as follows:

$$a_{n+1} + c_{n+1}\sqrt{2} = (a_n + c_n\sqrt{2}) (2 + \sqrt{2})$$ (8)

and - as you have already proven, of course - also like this:

$$a_{n+1} - c_{n+1}\sqrt{2} = (a_n - c_n\sqrt{2}) (2 + \sqrt{2}).$$ (9)

From here, by induction, obtaining (7),

Fig. 2. a) From $A$ V $C$ There is only one way to get there in two jumps: $c_1 = 1$.

b) There are two ways to get from $A$ to $A$ in two jumps: $a_1 = 2$.

c) $A$ can be reached from $C$ in two ways

⟦folio 30⟧

We beam:

$$a_n + c_n \sqrt{2} = (2 + \sqrt{2})^{n-1} (a_1 + c_1 \sqrt{2}) = (2 + \sqrt{2})^n;$$

$$a_n - c_n \sqrt{2} = (2 - \sqrt{2})^{n-1} (a_1 - c_1 \sqrt{2}) = (2 - \sqrt{2})^n.$$

Therefore $c_n = [(2 + \sqrt{2}) - (2 - \sqrt{2})^n] : 2\sqrt{2}$, and since $e_{2n} = 2c_{n-1}$, we finally get

$$e_{2n} = [(2 + \sqrt{2})^{n-1} - (2 - \sqrt{2})^{n-1}] / \sqrt{2}; \quad e_{2n-1} = 0.$$

Solution problem. It is only unclear how in this problem (and in the previous problem 6) it was possible to reach formulas containing $\pm \sqrt{2}$ - in the solve problem we are talking about integers! (For Olympiad participants and readers «Kvant» task 7 was made easier by the fact that the wording indicated the answer - «Kvant», 1979, No. 11, M595).

However, “conjugated numbers” would arise completely automatically if we knew the beginning of linear algebra (see [12]) and applied the standard rules of this science to solving equations (7). These rules propose to first find out which geometric progressions ($a_n = a_0 \lambda^n$, $c_n = c_0 \lambda^n$) satisfy a given recurrence relation. Values ​​for which progression also exists - they are called characteristic values ​​or eigenvalues ​​- are determined from a certain equation (it is also called characteristic). For (7), the characteristic equation has the form $\lambda^2 + 2 - 4\lambda = 0$, its roots are just $2 + \sqrt{2}$ and $2 - \sqrt{2}$. Taking these roots into account, we can obtain any solution to the recurrence relation as a “linear combination” of the corresponding geometric progressions ([11]). The “initial condition” (in our case $a_1 = 2$, $c_1 = 1$) uniquely determines the solution we need.

It is immovable that even the simplest recurrent integer sequences, for which the characteristic equations are quadratic with integer coefficients (examples are the same (6) and (7) or the Fibonacci sequence 1, 1, 2, 3, 5, 8,..., $\Phi_{n+1} = \Phi_n + \Phi_{n-1}$ - see [9], [10]), are expressed as a function of number, using “arranged” square irisizations.

Note that large characteristic numbers determine the growth rate of the sequence: for large $n$ in problem $7e_n \approx (2 + \sqrt{2})^n / \sqrt{2}$. You can also say it this way: $\lim_{n \to \infty} (e_{n+1}/e_n) = 2 + \sqrt{2}$.

For problem 6 we see something similar:

$$\lim_{n \to \infty} (x_n/y_n) = \sqrt{2}$$ - shows that both numbers $x_n$ and $y_n$ for large $n$ are practically equal to each other. We see an interesting extension of this fact in the following problem with a large number of “conjugate” irizations.

We change all the signs one by one

8 (M520). Let $(1 + \sqrt{2} \Phi' \sqrt{3})^n = q_n + r_n \sqrt{2} + s_n \sqrt{3} + t_n \sqrt{6}$, where $q_n, r_n, s_n$ and $t_n$ be integers. Find the limit $\lim_{n \to \infty} r_n/q_n$, $\lim_{n \to \infty} s_n/q_n$, $\lim_{n \to \infty} t_n/q_n$.

Of course, here we can express $(q_{n+1}; r_{n+1}; s_{n+1}; t_{n+1})$ in terms of $(q_n; r_n; s_n; t_n)$, resulting in $q_{n+1} + r_{n+1} \sqrt{2} + s_{n+1} \sqrt{3} + t_{n+1} \sqrt{6} = (1 + \sqrt{2} + \sqrt{3}) (q_n + r_n \sqrt{2} + s_n \sqrt{3} + t_n \sqrt{6}) = (1 + \sqrt{2} + 3)^n$.

It is not difficult to tell what others will be like. Let us consider, together with this number $\lambda_1 = 1 + \sqrt{2} + \sqrt{3}$, three more “arranged” ones: $\lambda_2 = 1 - \sqrt{2} + \sqrt{3}$, $\lambda_3 = 1 + \sqrt{2} - \sqrt{3}$, $\lambda_4 = 1 - \sqrt{2} - \sqrt{3}$.

We can express $q_n, r_n, s_n, t_n$ in terms of $\lambda_1, \lambda_2, \lambda_3, \lambda_4$:

$$q_n = (\lambda_1^2 + \lambda_2^2 + \lambda_3^2 + \lambda_4^2) / 4,$$

$$r_n = (\lambda_1^2 - \lambda_2^2 + \lambda_3^2 - \lambda_4^2) / 4\sqrt{2},$$

$$s_n = (\lambda_1^2 + \lambda_2^2 - \lambda_3^2 - \lambda_4^2) / 4\sqrt{3},$$

$$t_n = (\lambda_1^2 - \lambda_2^2 - \lambda_3^2 + \lambda_4^2) / 4\sqrt{6}.$$

Now note that $\lambda_1 > |\lambda_2|$, $\lambda_1 > |\lambda_4|$. Let's think about $\lim_{n \to \infty} r_n/q_n = \lim_{n \to \infty} s_n/q_n = 1/\sqrt{6}$.

We said above that conjugate numbers $a \pm b\sqrt{d}$ arise as roots of a quadratic equation with integer coefficients. In connection with the last task, this desire:

9. Write an equation with integer coefficients, one of whose roots is equal to $1 + \sqrt{2} + \sqrt{3}$.

A suspicion arises that along with this number $λ_1$ the equation with integer coefficients is also satisfied by the conjugates, which in the solution of the previous problem we denoted $\lambda_2, \lambda_3, \lambda_4$. The required equation can be written as follows:

$$(x - \lambda_1)(x - \lambda_2)(x - \lambda_3)(x - \lambda_4) = 0;$$

that is

$$(x - 1 - \sqrt{2} - \sqrt{3})(x - 1 + \sqrt{2} - \sqrt{3}) \times (x - 1 - \sqrt{2} + \sqrt{3}) \times (x - 1 + \sqrt{2} + \sqrt{3}) = 0;$$

⟦folio 31⟧

after transformation we get

$$((x-1)^2-5-2\sqrt{6}) (x-1)^2-5+2\sqrt{6}) = 0,$$
$$(x^2-2x-4)^2-24 = 0,$$
$$x^4-4x^3-4x^2-16x-8 = 0.$$

This is exactly the equation that turned out to be a characteristic one if we applied the one mentioned in small print on p. 30 general theory to the study of the linear transformation ($q_n; r_n; s_n; t_n) \rightarrow (q_{n+1}; r_{n+1}; s_{n+1}; t_{n+1}$) in the previous problem. Note also that we have actually obtained an equation of least degree (with coefficients in mind) with the root $\lambda_1 = 1 + \sqrt{2} + \sqrt{3}$. Try to prove it!

Algebraic sequential

We've looked at several examples that touch on borderline issues in algebra, calculus, and number theory. (Each direction that we have outlined could be devoted to a more detailed article in «Kvant»!) In conclusion, we will also show how you can look at the main characters of the article - “conjugate numbers” - from a purely algebraic point of view.

Let's assume that we have a set of $P$ numbers (or expressions with letters, or some other elements) from which we can perform even arithmetic operations in compliance with general arithmetic rules. Such a set is called a *field* (for the exact definition, see the list on page 18); fields form, for example, rational and real numbers. If, say, the equation $x^2-d=0$ is not solvable in the field $P$, then we can expand it by considering elements of the form $p+q\sqrt{d}$, where $p, q \in P$, and $\sqrt{d}$ is a new symbol, which when multiplied by itself gives $d$, i.e. $\sqrt{d}\sqrt{d}=d$, so that $(p+q\sqrt{d})(p'+q'\sqrt{d})=(pp'+qq'd)+(pq'+qp')\sqrt{d}$. This construction, for $d=2$ and $d=-1$, is described in detail in the article by S. Ashmanov in this issue «Kvant». In the second case, that is, for $d=-1$, we expand the field of real numbers and obtain complex numbers. We will return to them in the next issues «Kvant».

The new field $P_1$—the “square extension” of the field $P$—has an interesting mapping $\lambda=p+q\sqrt{d} \rightarrow \lambda=p-q\sqrt{d}$ (a kind of “algebraic symmetry”) called *conloading*, with the following properties:

1°. All elements of the old field $P$ are transferred to themselves;
2°. All equalities containing arithmetic operations are preserved in this mapping:

$$\lambda+\mu=\bar{\lambda}+\mu; \quad \lambda\mu=\lambda \cdot \mu.$$

This mapping is part of the case of so-called *Galois automorphisms* of the extension $P_1$ of the field $P$.

In Problems 8 and 9 we saw an example of a “double” extension—the addition of $\sqrt{2}$ and then $\sqrt{3}$—which resulted in a field with a large number of automatic Galois: in addition to the points of the action mapping, there are already three of them $(\sqrt{2} \rightarrow -\sqrt{2}, \sqrt{3} \rightarrow \sqrt{3}, \sqrt{2} \rightarrow \sqrt{2}, \sqrt{3} \rightarrow -\sqrt{3})$, and their “interaction” is arranged in the same way as in the set of self-alignments of a rectangle.

It turns out that the roots of any algebraic equation can be added to the main field. Automorphisms of a new field that arose - one of the most beautiful branches of algebra of the 19th-20th centuries, Galois theory, which allows, in particular, to study the question of the solvability of an equation in radics ([13], [14]).

We will end this article with a set of problems, basically a continuation of topics already touched upon, but sometimes requiring new messages, and we will provide a list of references.

Exercises

1. Which is greater: $\sqrt{1979} + \sqrt{1980}$ or $\sqrt{1978} + \sqrt{1981}$?
2. Find that for all positive $x$
$$|\sqrt{x^2+1}-x-1/2x| < 1/8x^3.$$
3. Graph the function $y=\sqrt{x^2-1}$ and prove that for $|x| \ge 1$
$$0 < |x| - \sqrt{x^2-1} < 1/|x|.$$
4. In the formula $\sqrt{2}=1+\frac{1}{\sqrt{2}+1}$ we replace $\sqrt{2}$, which is on the right side (in the denominator), using the same formula:
$$\sqrt{2}=1+\frac{1}{2+\frac{1}{\sqrt{2}+1}}.$$
In this formula, again change the lower $\sqrt{2}$ to $1+\frac{1}{\sqrt{2}+1}$, and so on $n$ times. If we now change to 1 or 2, we get two rational numbers $p_n, q_n$. Prove that $\sqrt{2}$ lies between them and $\lim_{n \to \infty} q_n=\sqrt{2}$. (Aren't we going to build this number into one of the tasks?)
5. Prove that the equations a) $x^2-3y^2=1$, b) $x^2-3y^2=2$ have an infinite number of solutions in integers.
6. Prove that the function $y=\ln(\sqrt{1+x^2}+x)$ is odd and graph it.
7. a) Prove that for any natural number $n$
