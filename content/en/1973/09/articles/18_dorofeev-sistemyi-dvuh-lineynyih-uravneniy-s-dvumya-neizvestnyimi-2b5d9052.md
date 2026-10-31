---
id: 1973-9-dorofeev-sistemyi-dvuh-lineynyih-uravneniy-s-dvumya-neizvestnyimi-2b5d9052
issue: kvant_1973_9
year: 1973
number: "9"
title: Systems of two linear equations with two unknowns
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 65
page_last: 69
page_labels: 63-67
tag: PQL5
lang: en
source: kvant_digital
extraction: vision
content_sha256: eb204a71f1460321204b0b5a583bbedcb4cef7931d07df301db35abf83475aab
prompt_sha256: draft-1
translated_from: content/ru/1973/09/articles/18_dorofeev-sistemyi-dvuh-lineynyih-uravneniy-s-dvumya-neizvestnyimi-2b5d9052.md
source_content_sha256: 2db3ebbad99c476662d5b1e358262d61ad69d9dcf8aa717e523b287249c56f89
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 63⟧

When preparing for entrance exams in mathematics, future applicants often focus their attention almost exclusively on solving problems, especially those offered in previous years’ exams at their chosen university. And they devote much less time to theoretical preparation. Many even leave the theory “for later”, hoping that they managed to master it in a few days between the written and oral exams. Such a “practical” bias, of course, does not justify itself.

First of all, the fact is that during oral exams the theoretical preparation of applicants is tested in great depth, in all the subtleties that are provided in any mathematical theory. And of course, all sorts of “pitfalls” in the proofs of theorems must only be seen in advance, but also learned to be avoided. But - and this, of course, is the most important thing - theory is necessary precisely for solving problems. Of course, there are problems that can be solved using some templates or algorithms, even if you have the vaguest idea of ​​theory. However, there are few such tasks, and it is difficult to understand more complex, non-teaching examples without proper theoretical knowledge.

One of the most important and most difficult points for applicants in the entrance exam program in mathematics is solving a system of two linear equations with two unknowns. One can immediately offer objections: how can such a system be solved? Nothing could be simpler. You need to express y in terms of x from one equation, substitute it into the second equation, find x, and then y. And indeed, everything would be very simple if I decided only to solve specific systems with numerical coefficients. However, in practice - both in “training” problems and in tasks where systems are used as an auxiliary apparatus - it is necessary to consider systems with letter coefficients, that is, with parameters. And this is already a significant condition of the task. And in general, solving problems with a parameter is the Achilles heel of multi-characteristics.

In theory, the most general case is considered, when the system has arbitrary coefficients, and the solution to such a system is the solution to a problem with six parameters! However, mastery of this theory serves as a guarantee of its correct application in particular cases.

Let's start from the beginning, that is, with definitions. What is a system of two linear equations in two unknowns? Unfortunately, the definition given in the textbook*) is not very good. The fact is that the word “set” when applied to an equation has recently ceased to be synonymous with the words “set”, “on-

*) See E. S. Kochetkov, E. S. Kochetkova “Algebra and elementary functions”, part I, § 26.

⟦folio 64⟧

boron”, but acquired a different meaning, such that the term “equation system” and “set of equations” have completely different meanings.

Namely, if there are several equations, then they are said to form a system if it is necessary to find the values ​​of the unknowns for which all these equations are satisfied. If you need to find the values ​​of the unknowns for which at least one of these equations is satisfied, then they say that these equations form a set. Thus, several equations form a system or set depending on the task at hand.

These arguments apply to arbitrary, not necessarily linear, systems of equations. Thus, we see that even the approach to defining a system of two linear equations with two unknowns requires preliminary careful thought.

During the oral exam, you can give the following definition: a system of two linear equations with two unknowns x, y is called a system of equations of the form

$$\begin{align*}
a_1x + b_1y &= c_1, \\
a_2x + b_2y &= c_2,
\end{align*}$$

food $a_1, b_1, c_1, a_2, b_2, c_2$ - arbitrary (real, or even complex - why not?) numbers.

In this definition, and it is important to emphasize, a system of two equations with two unknowns is distinguished as a special case of the general concept—a system of k equations with n unknowns. In this case, it is not necessary to give a general definition of the system of equations, but you need to know it (for example, in the form indicated earlier) and, if necessary, be able to formulate it.

A common drawback among applicants is that, having given the correct definition, the applicant is lost when considering “strange” special cases, such as

$$\begin{align*}
2x + y &= 5 \\
2x + y &= 5 \\
x + y &= 1 \\
x + y &= 2.
\end{align*}$$

We often hear that in the first case there is only one equation, in the second there is only one unknown, and the third “cannot exist at all.” Meanwhile, all three systems will satisfy this definition, in which there are no operations on the coefficients of x, y and free terms.

This situation sometimes causes a psychological protest: why is it necessary to consider such unreasonable systems? However, let us remember once again that systems with parameters are usually solved, and for certain values ​​of the parameters the most “unnatural” cases can occur.

The solution to a system of two linear equations with two unknowns is discussed in detail in the Kochetkovs’ school textbook. However, it should be borne in mind that applicants are often unable to give a compact formulation and corresponding proof of the main theorem on the solution of systems of the type under consideration. We also note that in the table of results given in the Kochetkovs’ textbook (§ 33), the case when all coefficients for the unknowns are equal to zero is omitted. Despite all the apparent “unnaturalness” of this case, it can come true (remember the parameters!) and therefore should be included in the results list.

This basic theorem can be formulated as the following diagram.

Theorem. Let the bottom system of equations

$$\begin{align*}
a_1x + b_1y &= c_1, \\
a_2x + b_2y &= c_2.
\end{align*}$$

Let us introduce the following notation:

$$\Delta = \begin{vmatrix}
a_1 & b_1 \\
a_2 & b_2
\end{vmatrix} = a_1b_2 - a_2b_1,$$

$$\Delta_x = \begin{vmatrix}
c_1 & b_1 \\
c_2 & b_2
\end{vmatrix} = c_1b_2 - c_2b_1,$$

$$\Delta_y = \begin{vmatrix}
a_1 & c_1 \\
a_2 & c_2
\end{vmatrix} = a_1c_2 - a_2c_1.$$

⟦folio 65⟧

Toeda

$$\frac{\Delta = 0}{\downarrow \Delta} \rightarrow \text{система определения*}$$

(dot),

$$\frac{\Delta_x = \Delta_y = 0}{\downarrow \Delta} \rightarrow \text{система несовместная,}$$

$$\frac{a_1 = b_1 = a_2 = b_2}{\downarrow \Delta} \rightarrow \text{система неопределения (прямая),}$$

$$\frac{c_1 = c_2 = 0}{\downarrow \Delta} \rightarrow \text{система несовместная (плоскость).}$$

This diagram should be understood as follows. First of all, the question is asked: $\Delta = 0$? If not, the determination system (has a unique solution); if yes, then the question is asked: $\Delta_x = \Delta_y = 0$? If not, then the system is incompatible; if yes, then we ask the next question, and so on. The words “point”, “straight line”, “plane” refer to the geometric interpretation of the corresponding case.

It should be additionally noted that in the first case $x = \frac{\Delta_x}{\Delta}$, $y = \frac{\Delta_y}{\Delta}$, and in the third case (that is, when $\Delta = \Delta_x = \Delta_y = 0$, but not all coefficients of the unknowns are equal to zero), the system is equivalent to one equation - the one in which there is a non-zero coefficient.

This formulation makes it possible to easily derive necessary and sufficiently conditional conditions of this type: the system is a definite model and a model when $\Delta \neq 0$; the system is inconsistent model and molko model when either $\Delta = 0$, but $\Delta_x \neq 0$ or $\Delta_y \neq 0$, or all coefficients of the unknowns are equal to 0, and at least one of the free terms is not equal to 0.

*) Unfortunately, the textbook does not contain the terms “definition” and “non-definition” of a system. A system is called determinate if it has exactly one solution, and indefinite if it has more than one solution. These terms are convenient for use, but, of course, not required.

Let us consider several typical examples of the application of this theorem.

Problem 1 (MSU, Faculty of Geography, 1970). At what values ​​of parameter a does the system of equations

$$\begin{cases} ax - 4y = a + 1, \\ 2x + (a + 6)y = a + 3 \end{cases}$$

has no solution?

We note right away that the condition for the incompatibility of the system given above is somewhat cumbersome, and in practice it is often advisable not to apply this condition “in any case”, but to work with only the necessary conditions of incompatibility $\Delta = 0$. This allows us not to count the determinants $\Delta_x$ and $\Delta_y$.

We have: $\Delta = a^2 + 6a + 8$; therefore, $\Delta = 0$ at $a = -2$ and at $a = -4$. Substituting $a_1 = -2$ into this system, we obtain the system

$$\begin{cases} -2x - 4y = -1, \\ 2x + 4y = 1, \end{cases}$$

which, obviously (or based on the third case of the theorem), has an infinite number of solutions. For $a_2 = -4$ we have the system

$$\begin{cases} -4x - 4y = -3, \\ 2x + 2y = -1, \end{cases}$$

which is obviously (or based on the second case of the theorem) inconsistent.

Answer: $a = -4$.

Problem 2 (MSU, Faculty of Biology, 1970). The numbers $a, b, c$ are supposed to be a system of equations,

$$\begin{cases} ax - by = 2a - b, \\ (c + 1)x + cy = 10 - a + 3b \end{cases}$$

has an infinite number of solutions, and $x = 1$, $y = 3$ is one of these solutions. Find the numbers $a, b, c$.

Let us immediately note that in the second equation of the system, for no $c$, the coefficients of the unknowns simultaneously turn to 0. Therefore, for this system the third case of the theorem occurs. The determinants $\Delta, \Delta_x, \Delta_y$ look rather cumbersome here, and to simplify the calculations we will first use the additional conditions of the problem. Since the pair of numbers $x = 1$,

⟦folio 66⟧

$$y = 3 \text{ является решением системы, то } \begin{cases} a - 3b = 2a - b, \\ c + 1 + 3c = 10 - a + 3b. \end{cases}$$

Hence $a = -2b, c = (5b + 9)/4$. Next we find: $\Delta = ac + bc + b = (-5b^2 - 5b)/4 = 0$, from where $b_1 = 0, b_2 = -1$. Then $a_1 = 0, c_1 = \frac{9}{4}; a_2 = 2, c_2 = 1$.

In these two cases the following systems are also obtained:

$$\begin{cases} 0x + 0y = 0, \\ \frac{13}{4}x + \frac{9}{4}y = 10, \\ 2x + y = 5, \\ 2x + y = 5. \end{cases}$$

Both systems satisfy the conditions of the problem.

Answer: $a_1 = 0, b_1 = 0, c_1 = \frac{9}{4}; a_2 = 2, b_2 = -1, c_2 = 1$.

Problem 3. At what values ​​of $a$ the system

$$\begin{cases} (a^2 - 1)x + (a + 1)y = a^2 - 2, \\ (a + 1)x + 2ay = 2a + 1 \end{cases}$$

do we have infinitely many solutions?

The determinant of this system is equal to $\Delta = 2a^3 - a^2 - 4a - 1$, and we have no formulas for solving the equation $2a^3 - a^2 - 4a - 1 = 0$ *. Therefore, it is important to use the main theorem in its entirety. The system is uncertain if and only if either $\Delta = \Delta_x = \Delta_y = 0$, but not all coefficients of the unknowns are equal to 0, or all coefficients of the system are equal to 0. However, the coefficients of $y$ cannot become 0 simultaneously, so it remains to consider only the first case.

*) True, you can notice that this equation has a root $a = -1$. Knowing one root of a cubic equation, we can decompose the left side of the equation into a linear factor (type $x - x_0$, where $x_0$ is the found root) and a polynomial of the second degree, the roots of which we know how to find. By finding the roots of the equation in this way, we can solve the resulting systems. However, we will give a simpler solution to the problem.

We have

$$\Delta_x = \begin{cases} a^2 - 2 & a + 1 \\ 2a + 1 & 2a \end{cases} = 2a^3 - 2a^2 - 7a - 1.$$

If the equations $\Delta = 0$ and $\Delta_x = 0$ have a common root $a_0$, then subtracting the second from the first equation we get $a_0^2 + 3a_0 = 0$, whence $a_0$ is either 0 or -3, but neither of these numbers is the root of the equation $\Delta = 0$, so we get a contradiction.

Consequently, the equation $\Delta = 0$ and $\Delta_x = 0$ do not have common roots, and therefore this system cannot be indeterminate.

Answer: for any $a$ the system does not have infinitely many solutions.

Now consider several problems whose conditions do not coincide with the systems of equation.

Problem 4. Prove that if the equation

$$ax^2 + bx + c = 0$$

and $px^2 + qx + r = 0$ have a common root, then $(ar - cp)^2 = (aq - bp) (br - cq)$.

Let these equations have a common root $x_0$. Then the system of equations

$$\begin{cases} au + bv = -c, \\ pu + qv = -r \end{cases}$$

has a solution $u = x_0^2, v = x_0$, and the equality to be proved takes the form $\Delta_v^2 = \Delta \cdot \Delta_u$. If the determinant $\Delta$ of system (1) is nonzero, then we correct Cramer and find a unique solution:

$$x_0^2 = \frac{\Delta_u}{\Delta}, \quad x_0 = \frac{\Delta_v}{\Delta}.$$

Hence $\frac{\Delta_u}{\Delta} = \frac{\Delta_v^2}{\Delta^2}$, hence $\Delta_v^2 = \Delta \cdot \Delta_u$, which is what needed to be proved.

If $\Delta = 0$, then system (1), being consistent, is indeterminate, and therefore, in it $\Delta_x = \Delta_y = 0$, that is, the equality being proved is again satisfied.

Those who wish can try to prove the required equality of indefinite

⟦folio 67⟧

and compare your solution with the one given.

Task 5. Under what condition can one check the parabolic graph of a square triangle through three points with pairwise different abscissas?

These points lie on the graph of the function $y = ax^2 + bx + c$ if and only if the system of equations is consistent

$$\begin{cases} ax_1^2 + bx_1 + c = y_1, \\ ax_2^2 + bx_2 + c = y_2, \\ ax_3^2 + bx_3 + c = y_3 \end{cases}$$

with unknowns $a, b, c$ and parameters $x_i, y_i$ ($i = 1, 2, 3$).

System (2) has three unknowns, and therefore our theory is not directly applicable to it. However, excluding the unknown $c$ from this system, we obtain a system with two unknowns:

$$\begin{cases} a(x_1^2 - x_2^2) + b(x_1 - x_2) = \\ a(x_1^2 - x_3^2) + b(x_1 - x_3) = \end{cases}$$

If system (3) is consistent, then, obviously, system (2) will be consistent (the converse is also true).

The determinant of system (3) is easy to calculate:

$$\Delta = \begin{cases} x_1^2 - x_2^2 & x_1 - x_2 \\ x_1^2 - x_3^2 & x_1 - x_3 \end{cases} = (x_1 - x_2)(x_1 - x_3)(x_2 - x_3).$$

The numbers $x_1, x_2, x_3$ are all different, therefore $\Delta \neq 0$, that is, system (3), and with it system (2), has a unique solution. Consequently, the graph of a function of the form $y = ax^2 + bx + c$ always passes through three points with pairwise different abscissas.

However, for this function to be the graph of a square triangle, there must be $a \neq 0$, that is, in system (3)

$$\Delta_a = \begin{cases} y_1 - y_2 & x_1 - x_2 \\ y_1 - y_3 & x_1 - x_3 \end{cases} \neq 0.$$

Thus, in the process of solving we received the following statements: if three points have pairwise different abscissas, then

$$\begin{cases} y_1 - y_2 & x_1 - x_2 \\ y_1 - y_3 & x_1 - x_3 \end{cases} = 0$$

they lie on the same straight line;

$$\begin{cases} y_1 - y_2 & x_1 - x_2 \\ y_1 - y_3 & x_1 - x_3 \end{cases} \neq 0$$

they lie on the same parabola.

In addition, through any three points with pairwise distinct abscissas that do not lie on the same line, one can check the unique parabolic $y = ax^2 + bx + c$.

Emphasizing

1. Can a system of two linear equations in two unknowns have equal even solutions?

2. What is the difference between solutions to the equation $x = 1$ and solutions to the system

$$\begin{cases} x + 0y = 1, \\ x + 0y = 1 \end{cases}$$

3. (MSU, Binofak, 1969). Find all values ​​of $a$ for which the system of equation

$$\begin{cases} 2x + (9a^2 - 2)y = 3a, \\ x + y = 1 \end{cases}$$

has no solution.

4. (MSU, Faculty of Geography, 1970). At what values ​​of the parameter $a$ does the system of equation

$$\begin{cases} 2x + ay = a + 2, \\ (a + 1)x + 2ay = 2a + 4 \end{cases}$$

has infinitely many solutions?

5. (MSU, Binofak, 1970). The numbers $a$ and $b$ are such that the system of equation

$$\begin{cases} a^2x - ay = 1 - a, \\ bx + (3 - 2b)y = 3 + a \end{cases}$$

has a unique solution $x = 1, y = 1$. Find $a$ and $b$.

6. What complete numbers can we represent as $\frac{c + di}{c - di}$?

7. Solve system equation

$$\begin{cases} 2x^3y = 5, \\ 3x^8y = 12 \end{cases}$$

8. Under what conditions do the points $(x_1, y_1)$ and $(x_2, y_2)$ lie on the graph of some paraboly of the form $y = x^2 + px + q$?

9. Solve system equation

$$\begin{cases} ax + y + z = 1, \\ x + ay + z = 1, \\ x + y + az = 1 \end{cases}$$

10. For what $a$ do points with coordinates $(-1, -3 - a), (3, 3a + 1), (4 - a, 2a + 2)$ lie on the same line?
