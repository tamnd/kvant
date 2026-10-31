---
id: 1974-1-dorofeev-pereformulirovka-zadachi-5d048ca7
issue: kvant_1974_1
year: 1974
number: "1"
title: Reframing the problem
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 61
page_labels: 53-59
tag: V6VY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8dd8c0f93e3875fc4576788a5f46ff741b14bdca5f17d89b37048e0a464a3b0a
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/13_dorofeev-pereformulirovka-zadachi-5d048ca7.md
source_content_sha256: 570131f4828c245f412af66ce8e29f1f87df671e7b05417381776d6417fdcf6a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

G. V. Dorofeev

Reframing the problem

One of the significant shortcomings in the mathematical preparation of schoolchildren, which very often and clearly manifests itself in entrance exams to higher education, is excessive directness in the approach to solving a problem. In most cases, applicants are so attached to this condition, to this formulation of the problem, that they do not agree to look at the problem a little differently, on the other hand, try to formulate its conditions in other terms, in short, to find a solution method that does not lie on the surface.

Meanwhile, it is precisely the reformulation of the problem, its formulation in a new way, that often illuminates its true meaning and is a direct path to a solution. Moreover, the applicant’s ability to consider a problem from different angles, in different interpretations, is one of the most important signs of his mathematical (and often general) development and one of the conditions for his further study at a university. It must be emphasized that what has been said concerns not only mathematics.

Of course, schoolchildren are adequately proficient in the basic, or more precisely, the most natural, techniques for reformulating problems, since these techniques are part of general school practice. Thus, the majority of applicants are quite capable of solving so-called “technical” problems, but the basis for solving such a problem is a typical reformulation: the problem is given in the form of a certain set of conditions written in a general, “everyday” language, and the solver, as a rule, draws up some equations, sometimes inequalities, that is, translates these conditions into mathematical language, after which the problem is solved in purely mathematical ways. Remember, for comparison, that in the lower grades such problems are solved directly, with rather cunning reasoning, but without any algebraic relations, and it is also much more difficult to come up with a solution.

Another example is solving geometric problems. If the problem can be translated into the language of equations, if correspondences between data and unknown elements of the geometric configuration are easily written out, then, as a rule, the problem can be solved without difficulty. On the contrary, if this approach to the problem is not applicable, then it will be much more difficult - you need to come up with purely geometric ideas, and this is a completely different matter - along with calculation techniques, you need good geometric intuition, geometric understanding, and more active geometric knowledge.

What does it mean to reframe the problem? It is clear that it is, strictly speaking, impossible to give an exact answer to this question. But fate is that the conditions of the problem formulation

⟦folio 54⟧

is written in another language, in other, more or less similar terms. Reformulation techniques are so diverse that it is almost impossible to list and describe them in a reasonable way, and you can only master them in practice, solving a sufficient number of examples.

One of the most important methods of reformulating problems, the application of which, roughly speaking, is the practical, applied side of mathematics, is the “translation” of a real, life situation into a formal language, into the language of exact mathematical statements. In school mathematical practice, in the practice of entrance exams, “translation” of words into formulas and conciseness also often occurs.

Thus, to prove the statement “function $y = \cos x$ kills on the interval $0 \leq x \leq \pi$” it should be reformulated as “Given: $0 \leq x_1 < x_2 \leq \pi$; prove that $\cos x_1 > \cos x_2$". And the complex definition of “the logarithm of a number $N$ to base $a$ is a number $\alpha$ such that $a^\alpha = N$” is reformulated as “$a^{\log_a N} = N$”, so the basic logarithmic proof is simply a formal notation of the definition of a logarithm. And if all this is well understood, then “tricky” questions like “Why $(\sqrt{a})^2 = a?$”, “Why sin (arcsin $x$) = $x$?” etc.

On the other hand, “reverse translation” is also important - the ability to see in some proof of formal equality its complex expression. For example, reading the formula $\sqrt[n]{a^m} = \left( \sqrt[n]{a} \right)^m$ as the statement “$\left( \sqrt[n]{a} \right)^m$ is the root of degree $n$ of $a^m$” we immediately, by defining the root, obtain by proving this formula:

$$\left( \sqrt[n]{a} \right)^m = \left( \sqrt[n]{a} \right)^m = a^m.$$

The basic formulas for logarithms can be proven in the same way. In general, all kinds of properties of inverse functions - roots, logarithms, inverse trionometric functions - are proven precisely by translating the corresponding “direct” functions into the language.

Let's look at a few examples that show the effectiveness of reformulation - sometimes directed, sometimes unexpected.

First, a few problems related to the quadratic trinomial.

Problem 1. For what a are the roots of the equation $x^2 + ax + a = 0$ greater than 1?

Most applicants conscientiously find the roots to solve this problem

$$x_1 = \frac{-a + \sqrt{a^2 - 4a}}{2},$$

$$x_2 = \frac{-a - \sqrt{a^2 - 4a}}{2}$$

and solve a system of inequalities - sometimes two ($D \geq 0, x_2 > 1$), if they agree that $x_2$ is a smaller root, and it is enough that it is greater than 1, and more often than not three inequalities: $D \geq 0, x_1 > 1, x_2 > 1$.

If there is a good technical solution to irrational inequalities, this path, of course, leads to the goal. However, if you step aside a little and apply Vieta’s theorem, it will immediately become clear that the required values ​​of $a$ do not exist: the product $a$ of such roots must be greater than 1, and their sum $(-a)$ will then also be positive.

It is interesting to note that if in this problem you ask: for which a the roots are positive, then a lot of people agree to apply Vieta’s theorem - after all, this is its standard application!

⟦folio 55⟧

Task 2. For what a does the inequality $1 < x \leq 2$ imply the inequality $x^2 - 2ax + a < 0$?

The condition of the problem obviously means that the trinomial $f(x) = x^2 - 2ax + a$ is negative on the segment $1 < x \leq 2$, and this is equivalent to the condition that the segment $1 < x \leq 2$ lies between the roots of this trinomial (since the coefficient of $x^2$ is positive). But the last condition is equivalent to the fact that the ends of the segment lie between the roots, and it remains, finally, to report that this condition is equivalent to the system of inequalities $f(1) \leq 0, f(2) < 0$, or
$$\begin{cases} 1 - a \leq 0, \\ 4 - 3a < 0, \end{cases}$$
whence $a > 4/3$.

Task 3. Prove that the equation $f(x) = (x - a)(x - b) + (x - a)(x - c) + (x - b) \times (x - c) = 0$ for any $a, b$, c has real roots.

It is easy to imagine that the “direct” solution to this problem - opening the brackets and proving that the discriminant of the resulting quadratic trinomial is positive - is associated with great computational difficulties, and we will use the fact that a quadratic trinomial (with a positive leading coefficient) has real roots if and only if it takes a negative or zero value at at least one point. It is natural to look at its values ​​at points $a, b, c$ - then of the three terms only one remains.

We have
$$f(c) = (c - a)(c - b);$$
the sign of the resulting product depending on the relative position of the point $a, b, c$ on the numerical axis, and this product is negative if $c$ lies between $a$ and $b$. But one of these three numbers lies between the other two, and we get the solution: let, for definition, $a \leq b \leq c$; then $f(b) = (b - a)(b - c) \leq 0$, and therefore the trinomial takes a negative or zero value at the point $b$, and therefore has real roots.

In the three examples considered, the problem conditions clearly contained a quadratic trinomial, and therefore the reformulation of the problem is not too far from its conditions. Let's look at a few other examples.

Task 4 (MSU, Faculty of Psychology, 1969). Prove that $x^2 + 19y^2 + 6z^2 - 8xy - 4xz + 12yz > 0$ if $x^2 + y^2 + z^2 > 0$.

An attempt at grouping at random, without definitions, can hardly lead to success here, but it is enough to see on the left side the square trinomial with respect to $x$ (with “parameters” $y$ and $z$), and the method of grouping becomes completely clear - isolating a complete square. If we also note that after this transformation the “free term” will be a quadratic trinomial with respect to $y$ (with the “parameter” $z$), then the problem can be considered actually solved.

So the left side of the equation can be rewritten as
$$x - 4y - 2z)^2 + 3y^2 + 2z^2 - 4yz =
(x - 4y - 2z)^2 + 3\left(y - \frac{2}{3}z\right)^2 + \frac{2}{3}z^2,
$$
and therefore non-negative for all values ​​of $x, y, z$.

Can it be zero? This will obviously happen only when all three terms are equal to 0, that is, when the equalities are simultaneously satisfied
$$x - 4y - 2z = 0, y - \frac{2}{3}z = 0, z = 0.$$

But from these equalities it immediately follows that $x = y = z = 0$, which contradicts the conditions $x^2 + y^2 + z^2 > 0$. Thus, the statement is completely proven.

Task 5 (MSU, faculty, 1972). At what real x value
$$t = \frac{\sqrt{x^2 + 16}}{3} - \frac{x}{5}$$
take the smallest value?

In problems of this kind, as a rule, it is easy to first find the smallest

⟦folio 56⟧

first determine the value of a given expression, a given function, and only then the value of the argument at which it is achieved. And sometimes it is possible to find the smallest value by solving a more general problem - finding the entire range of values ​​of a function and taking the smallest number in it.

You can find the smallest value of the function if you reformulate the problem. The fact that the number $A$ belongs to the range of the function $y = f(x)$, in terms of the equation, shows that the equation $f(x) = A$ has at least one solution.

In this problem, we note first of all that the function $t = t(x)$, given by formula (1), takes its smallest value for the same value of the argument as the function $s = 15 t(x)$, and to simplify the calculations we will consider precisely the function

$$s = 5\sqrt{x^2 + 16} - 3x.$$

Equation

$$5\sqrt{x^2 + 16} - 3x = A$$

or

$$5\sqrt{x^2 + 16} = 3x + A$$

(2)

after squaring both parts, it becomes the equation

$$16x^2 - 6Ax + 400 - A^2 = 0.$$

Equation (2) has a solution if and only if equation (3) has a root $x$ satisfying the condition $3x + A \geq 0$. But this is equivalent to the discriminant of equation (3) being non-negative and the larger root of equation (3) being greater than or equal to $-A/3$. Thus we arrive at a system of least names

$$\begin{cases} 25A^2 - 6400 \geq 0 \\ 3A + \sqrt{25A^2 - 6400} \geq -\frac{A}{3}. \end{cases}$$

This system can be solved in the usual way, resulting in $A \geq 16$. Therefore, the smallest value of $A$ is 16, and the value of equation (3) has a single root $x = 3$, which is the root of equation (2). Thus, the smallest value of $y$ is $-4$ and is achieved

⟦folio 57⟧

at $x^2 - 7x = -8$, that is, at two points:

$$x_1 = \frac{7 + \sqrt{17}}{2}; \quad x_2 = \frac{7 - \sqrt{17}}{2}.$$

Problem 7 (MSU, Faculty of Economics, 1973).

The graph of the function $y = \frac{2+x}{x}$ intersects at two points with a line forming an angle $\alpha$ with the x-axis. The name of the geometric between the lengths of the segments connecting the origin of coordinates with the projections of the intersection points on the Ox axis.

In this problem, the most important thing is the exact concept of its conditions and expressing it in the language of formulas.

The graph of the function $y = 1 + 2/x$ is a hyperbola (graph it!). Therefore, the line discussed in the problem statement is inclined (that is, $\alpha \neq \pi/2, \alpha \neq 0$) and this hyperbola cannot intersect with a vertical or horizontal line at two points. In other words, the equation of a straight line has the form

$$y = x \mathrm{tg} \alpha + b,$$

$\mathrm{tg} \alpha \neq 0$. The fact that a hyperbola and a line intersect at two points means that the equation

$$\frac{2+x}{x} = x \mathrm{tg} \alpha + b,$$

or, what is the same, equation $x^2 + x (b - 1) \mathrm{tg} \alpha - 2 \mathrm{tg} \alpha = 0$ (4) has two different real roots (since $x = 0$ is not a root of equation (4)). The problem statement states that this fact occurs.

If the roots of equation (4) are denoted by $x_1$ and $x_2$, then the lengths of the segments connecting the origin of coordinates with the projections of the points of intersection of the straight line and the hyperbola on the Ox axis are equal to the corresponding $|x_1|$ and $|x_2|$. Therefore, we need to calculate the quantities

$$\sqrt{|x_1| \cdot |x_2|} = \sqrt{|x_1 x_2|},$$

where $x_1$ and $x_2$ are the roots of equation (4). And this is easy to do using Vieta’s theorem:

$$\sqrt{|x_1 x_2|} = \sqrt{2 |\mathrm{ctg} \alpha|}.$$

Let us now consider several examples not related to the quadratic trinomial.

In a number of examples related to the model of real and complex numbers, the geometric interpretation of the model provides significant assistance: $|x - y|$ is the distance between the points that form the complex numbers, and in particular, the real numbers $x$ and $y$.

Problem 8. Solve the equation $|x + 2| + |x - 3| = 5$ ($x - \text{дейстимелевое число}$).

In the geometric language of this problem, it can be formed as follows: find all points on the number line for which the sum of the distances to the points $-2$ and $3$ is equal to 5. This translation instantly solves the problem: in fact, any point on the segment $-2 \leq x \leq 3$ has this property, and for any point outside the segment the sum of the distances is greater than 5.

Thus, the solutions to this equation are all $x$ from the segment $-2 \leq x \leq 3$.

Problem 9. Solve the inequality $\left| \frac{2x - 3}{2x + 5} \right| > 1$.

Using the property of the model $\left| \frac{a}{b} \right| = \frac{|a|}{|b|}$, we rewrite these inequalities in the form $|2x - 3| > |2x + 5|$, $2x + 5 \neq 0$, and formulate the problem as follows: find points $x$ for which $2x$ is closer to $-5$ than $k = 3$, and $x \neq -2, 5$. This condition is equal to the fact that $2x < -1$, $x \neq -2, 5$, that is, $x < -2, 5$; $-2, 5 < x < 0, 5$. This is the solution to this inequality.

Problem 10. Where on the complex plane there are points $M$ for which the sum of squared distances

⟦folio 58⟧

up to the given points $A = (1, 0)$ and $B = (0, 1)$ is equal to 2? Having completed the triangle $AMB$ to the parallelogram $AMBN$, we apply the well-known relationship connecting the lengths of the side and the diagonals of the parallelogram:
$$AB^2 + MN^2 = 2AM^2 + 2MB^2 = 4.$$
Hence $MN^2 = 4 - AB^2$, and since in our case $AB^2 = 2$, then $MN = \sqrt{2}$, and therefore the points $M$ lie on a circle of radius $\frac{1}{2}MN = \frac{\sqrt{2}}{2}$ with center in the middle of the segment $AB$.

Finally, let's look at a few examples where reformulation plays an important role.

Problem 11 (MSU, Faculty of Psychologists, 1971). Find all values ​​of $x$ such that
$$\min \{2x - x^2, x - 1\} > -\frac{1}{2}.$$
The use of the expression $A = \min \{2x - x^2, x - 1\}$ in the formulation of the problem, as is known, is understood in the following sense: for any fixed $x = x_0$ A means the lesser of two numbers $2x_0 - x_0^2$ and $x_0 - 1$.

A “direct” solution to this problem requires consideration of two mergers: $2x - x^2 \leq x - 1$ and $x - 1 < 2x - x^2$. In each of these merges, you will need to solve the quadratic inequality and display its solution, satisfying the conditions $2x - x^2 > -1/2$ and $x - 1 > -1/2$, respectively.

Meanwhile, it is not difficult to report that the minimum of two expressions is greater than $-1/2$ in the case when these expressions are greater than $-1/2$, and thus, the condition of the problem is equivalent to a system of inequalities
$$\begin{cases} 2x - x^2 > -\frac{1}{2}, \\ x - 1 > -\frac{1}{2}, \end{cases}$$
the solution of which does not seem difficult. The result will be the answer: $\frac{1}{2} < x < \frac{2 + \sqrt{6}}{2}$.

Problem 12 (MSU, Faculty of Psychologists, 1972). Find all integer solutions to the inequality
$$x - 1 < \log_6 (x + 3).$$
The ODZ inequalities only include $x > -3$, and it is easy to verify indefinitely that the numbers $-2, -1, 0$ and 1 are its solutions. Substituting the following integer values ​​$x$, we see that they are not solutions, and it is easy to notice that “the further, the worse” - as $x$ increases, the difference between the left and right sides of the equation is equal. Therefore, all that remains is to prove this statement strictly.

In other words, we received the following task: to prove that the function
$$f(x) = x - \log_6 (x + 3)$$ - returning. This task, however, is quite difficult, but we are only interested in the integer values ​​of the argument, so we just need to make sure that this function returns when increased by 1. We have
$$f(x + 1) - f(x) = (x + 1) - \log_6 (x + 4) - x + \log_6 (x + 3) = \log_6 \frac{x + 3}{x + 4} + 1,$$
so the inequality $f(x + 1) - f(x) > 0$ is equivalent to the inequality $\frac{x + 3}{x + 4} > \frac{1}{6}$, which, as is easy to see, is obviously satisfied for positive $x$.

Consequently, our inequality does not hold for any integer $x$ greater than 1, and the values ​​obtained above are the solutions to the problem.

Problem 13. Find the sum of the coefficients of the polynomial
$$(x^3 + 2x - 8)^{73} (x^2 - 4x + 3)^{37},$$
obtained after opening the parentheses.

Here it is absolutely clear that calculating the sum of the coefficients “in any” is a hopeless matter, and the only possibility is to report that the sum of the coefficients of a polynomial can be obtained if

⟦folio 59⟧

substitute 1 into the polynomial together $x$.
And this can be done without opening parentheses in this polynomial: at $x = 1$ we get 0, so the sum of the coefficients of this polynomial is equal to 0.

Problem 14. Prove equality
$$1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots + \frac{1}{199} - \frac{1}{200} = \frac{1}{101} + \frac{1}{102} + \dots + \frac{1}{200}.$$
It should not be difficult to realize that the number 200 is not so “outstanding” that such an elegant equality can be found in its names alone, and therefore one can suspect that this equality is of a more universal nature. Thus, we can make the hypothesis that for any fourREM $n = 2k$ the equality is true
$$1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots + \frac{1}{2k-1} - \frac{1}{2k} = \frac{1}{k+1} + \frac{1}{k+2} + \dots + \frac{1}{2k}.$$
Indeed, this equality is true, and it is not difficult to prove by induction.

Have a womanized
1. For what values ​​of $a$ is one of the roots of the equation $x^2 - 2ax - a = 0$ greater than 1 and the other less than 1?
2. Prove that if exactly one of the numbers $c$, $d$ lies between the numbers $a$, $b$, then the equation $(x-a)(x-b) + \alpha(x-c)(x-d) = 0$ for any $\alpha$ has real roots.
3. Let the equation $ax^2 + bx + c = 0$ have no real roots and $a+b+c < 0$. Find the sign of the number $c$.
4. Does the line $y = 2$ intersect the graph of the function $y = \frac{x+1}{x^2-2x+3}$?
5. Find the range of values ​​of the function $y = \frac{2x-3}{x^2+2x+2}$.
6. Prove that if the expression $\frac{4}{x^2+ax-3a+1}$ is not equal to -2 for any value of $x$, then $a > -13$ ($x, a$ are real numbers).
7. For what $a$ do the parabolas $y = x^2 + ax - a$ and $y = 2x^2 - x + a$ not have common points?

8. (MSU, Faculty of Psychology, 1969). Prove that $2x^2 + 5y^2 + 3z^2 - 6xy - 2xz + 5yz > 0$ if $x^2 + y^2 + z^2 > 0$.
9. (UDN, 1973). Find all real values ​​of $x, y, z$ satisfying equation $2x^2 + y^2 + 2z^2 - 2xy + 2xz - 2xz + 1 = 0$.
10. (MSU, Faculty of Economics, 1969). At what real value $x$ does the expression $\frac{2x-1}{2x-x^2-4}$ take its smallest value?
11. (MSU, philology. faculty, 1972). At what positive $x$ does the expression $2x + \frac{3}{8} + \frac{1}{x+1}$ take on its minimum value?
12. (MSU, Faculty of Economics, 1973). The graph of the function $y = 2x^2 - x$ intersects at two points with the inclined line passing through the axis point $y$ with ordinate $b$. Find the geometric mean between the lengths of the segments connecting the origin of coordinates with the projections of the intersection points on the abscissa axis.
13. (MSU, Faculty of Economics, 1973). The graph of the function $y = \frac{1}{1-x}$ intersects at two points with the inclined line passing through the axis point $x$ with the abscissa $a$. Calculate the abscissa of the midpoint of the segment connecting the projections of the intersection points on the $x$ axis.
14. (MSU, mechanism, 1963). Solve equation $|x^2 - 4| + |x^2 - 9| = 5$.
15. (MSU, Faculty of Computational Mathematics and Cybernetics, 1970). Solve equation $|4 + \log_{1/7}x| = 2 + |2 + \log_{1/7}x|$.
16. (MSU, Faculty of Psychology, 1971). Find all values ​​of $x$ for which $\min \left\{1 - x^2, \frac{1-x}{2}\right\} > \frac{1}{2}$.
17. (MSU, Faculty of Psychology, 1972). Find all integer solutions to the inequality
$$2x + 1 < 2\log_2(x + 3).$$
18. Prove inequality
$$1 \cdot 2 \cdot 3 \dots 1973 < 987^{1973}.$$
19. According to the rigid graph of the function $y = \log_2 x$ the ball rolls. Will it linger between the rigid ordinat axis and the given graph or will it fall to infinity? Same question for function $y = \log_2 (x - 0,01)$ and $y = \log_2 (x + 0,01)$.
