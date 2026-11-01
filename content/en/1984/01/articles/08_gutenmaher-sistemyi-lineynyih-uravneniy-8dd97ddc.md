---
id: 1984-1-gutenmaher-sistemyi-lineynyih-uravneniy-8dd97ddc
issue: kvant_1984_1
year: 1984
number: "1"
title: Systems of linear equations
authors:
  - Гутенмахер В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 31
page_labels: 24-29
tag: 8U8G
lang: en
source: kvant_digital
extraction: vision
content_sha256: 21b8d6cd3ba6a6a68a26ef6daca576981dd1d36faa601d64f15c1a83127fecd1
prompt_sha256: draft-1
translated_from: content/ru/1984/01/articles/08_gutenmaher-sistemyi-lineynyih-uravneniy-8dd97ddc.md
source_content_sha256: 73ff2afb36f83408da75fd427b77eadef4c593ee4838cdd495e4b314c07ce9ac
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Systems of linear equations
Candidate of Physical and Mathematical Sciences
V. L. GUTENMACHER

Systems of linear equations are often found in various applications of mathematics (for example, physics, chemistry, economics). The article talks about the simplest ways to solve such systems and about the universal method - the Gauss method.

Variable exclusion

The best way to understand the method is with an example. Let's consider the system
$$\begin{cases} 2x + 3y = 5 \\ 7x + 5y = 1. \end{cases}$$

To solve it, we use the first equation to eliminate the variable $x$ from the second equation. For this purpose, let us prepare both equations so that the coefficients for $x$ are the same. Multiplying the first equation by 7 and the second by 2, we get
$$\begin{cases} 14x + 21y = 35 \\ 14x + 10y = 2. \end{cases}$$

Now let's leave the first equation untouched, and replace the second with the difference between the first and second equations:
$$\begin{cases} 14x + 21y = 35 \\ 11y = 33. \end{cases}$$

Let us now give the first equation its original form, and divide the second by 11:
$$\begin{cases} 2x + 3y = 5 \\ y = 3. \end{cases}$$

Substituting the value $y=3$ into the first equation, we find
$$\begin{cases} x = -2 \\ y = 3. \end{cases}$$

⟦folio 25⟧

The answer is received, the equation system has a unique solution - a pair of numbers (-2; 3).

Tasks
1. System Decision Variable Elimination Method
   a) $\begin{cases} 2x+3y=4 \\ 3x-2y=5 \end{cases}$
   b) $\begin{cases} \frac{3}{4}x-\frac{5}{6}y=1 \\ \frac{5}{6}x-\frac{3}{4}y=2. \end{cases}$
2. Two points move along the number axis at a speed of $u=-12$ km/h and $v=12$ m/s. At first their abscissas were $a=3$ km and $b=-500$ m. Where and when will they meet?

Replacing variables
One of the basic techniques of algebra is the replacement of one variable with another. This technique allows you to make tasks simpler. Let, for example, we need to solve a system of non-linear equations
   $$\begin{cases} \frac{2}{x}+\frac{3}{y}=5. \\ \frac{7}{x}+\frac{5}{y}=1. \end{cases}$$
By fielding $u=\frac{1}{x}, v=\frac{1}{y}$, we obtain a linear system with new variables $u, v$:
   $$\begin{cases} 2u+3v=5 \\ 7u+5v=1. \end{cases}$$
Solving it, we find $u=-2, v=3$. We now return to the old variables: $\frac{1}{x}=-2, \frac{1}{y}=3$, from where $x=-\frac{1}{2}, y=\frac{1}{3}$.

Problem 3. Method for replacing system solution variables
   a) $$\begin{cases} \frac{1}{2x+3y-5}+\frac{7}{5x-8y+12}=1 \\ \frac{4}{2x+3y-5}-\frac{14}{5x-8y+12}=1 \end{cases}$$
   b) $$\frac{x^2+xy=5}{3x^2+5xy=23}$$
   c) $$\frac{xy}{3x+2y}=\frac{1}{5}, \frac{xy}{5x+7y}=1.$$

Geometric meaning of linear equation
To find the equation of the straight line $y=kx+b$, passing through points with coordinates (1; 2) and (3; 1), we substitute the coordinates of the point data into the equation $y=kx+b$ instead of $x$ and $y$. We'll get the system
   $$\begin{cases} 2=k+b \\ 1=3k+b. \end{cases}$$
Solving it, we find $k=-\frac{1}{2}, b=\frac{5}{2}$.
Thus, the correct equation is $y=-\frac{1}{2}x+\frac{5}{2}$.
But it may happen that the corresponding system of equations has no solution. Let, for example, these points have coordinates (1; 2) and (1; 3). Substituting these values ​​into the equation $y=kx+b$, we obtain the system
   $$\begin{cases} 2=k+b \\ 3=k+b, \end{cases}$$
having no solution (after all, $2=3$ follows from the equation of the system). At first glance, this is a little surprising - after all, a straight line always passes through two points. It turns out that the equation of the line passing through the points (1; 2) and (1; 3) is not written in the form $y=kx+b$ - its equation is $x=1$.
Thus, we found out the reason for the misunderstanding - the problem was poorly formulated: in the conditions it was assumed that the equation of a line on the coordinate plane always has the form $y=kx+b$, but for lines parallel to the ordinat axis, this is not the case. In this regard, we leave the equation of an arbitrary line written in the form $ax+by=c$. This view allows you to cover all the straight lines on the coordinate plane. For example, if we put $a=\frac{1}{2}, b=1, c=\frac{5}{2}$, we get the equation of the first straight line, and if we take $a=1, b=0, c=1$, we get the equation of the second straight line.
Let us now consider the system
   $$\begin{cases} x+\sqrt{2}y=\sqrt{3} \\ \sqrt{2}x+2y=\sqrt{6}. \end{cases}$$
To solve it, in geometric language, means to find the common points of the lines given by the equations $x+\sqrt{2}y=\sqrt{3}, \sqrt{2}x+2y=\sqrt{6}$. Let's solve this system by eliminating the variable: multiply the first equation by $\sqrt{2}$ and subtract it from the second:

⟦folio 26⟧

$$\begin{cases} \sqrt{2}x + 2y = \sqrt{6} \\ \sqrt{2}x + 2y = \sqrt{6} \end{cases} \quad 0 = 0.$$

As a result, only one equation remains. This means that the system has an infinite number of solutions and the lines coincide. In the process of solving, we discovered that the second equation is the first one multiplied by $\sqrt{2}$, which might not have been immediately noticed.

In the analyzed problems, we encountered all possible situations: the system has a unique solution, has no solution, has an infinite number of solutions. The same is true in the general case. A system of $n$ linear equations with $n$ unknowns, as a rule, has a unique solution. But when one of its equations is a "linear combination" of the other equations or contradicts them, it has an infinite number of solutions or none at all.

Tasks

4. Find the equation of the line passing through points a) (1; 5) and (2; 3); b) (6; 1) and (6; 5).

5. For what $k$ and $b$ do the lines $y - kx = 2$ and $2y - 6x = b$ coincide? b) do not intersect?

6. At what $a$ systems

$$\begin{cases} 2x + (9a^2 - 2)y = 3a \\ x + y = 1 \end{cases}$$

doesn't have a solution?

7. Prove that the system

$$\begin{cases} a_1x + b_1y = c_1 \\ a_2x + b_2y = c_2 \end{cases}$$

has a unique solution if and only if $a_1b_2 - a_2b_1 \neq 0$. (The number $a_1b_2 - a_2b_1$ is called definite of the system.)

Rounding errors

When solving a problem on a computer, surprising situations can arise. A classic illustration of this is solving the system

$$\begin{cases} x + \sqrt{2}y = \sqrt{3} \\ \sqrt{2}x + 2y = \sqrt{6}. \end{cases}$$

This system, as we have already seen, has an infinite number of solutions. However, if you solve it on a computer, it will have... a unique solution! This happens because the computer does not have the ability to operate with numbers of the form $\sqrt{2}$ - they are replaced in it by decimal (or double) approximations.

If, for example, the numbers $\sqrt{2}, \sqrt{3}, \sqrt{6}$ are replaced by their decimal approximations with one digit after the decimal point: $\sqrt{2} \approx 1.4; \sqrt{3} \approx 1.7; \sqrt{6} \approx 2.4$, the system will take the form

$$\begin{cases} x + 1.4y = 1.7 \\ 1.4x + 2y = 2.4. \end{cases}$$

Having solved it, we get one solution: $x = 1; y = 0.5$.

If we leave four decimal places, we get the system

$$\begin{cases} x + 1.4142y = 1.7320 \\ 1.4142x + 2y = 2.4494 \end{cases}$$

which also has one (but completely different) solution: $x = 0,3178; y = 1$.

It is interesting that, no matter what decimal approximations we replace the number $\sqrt{2}$, we will always get a unique solution.

Let's prove it. Replacing $\sqrt{2}$ in system (1) with the letter $a$, we obtain

$$\begin{cases} x + ay = \sqrt{3} \\ ax + 2y = \sqrt{6}. \end{cases}$$

Let us show that for $a^2 \neq 2$ the system has a unique solution. If $a = 0$, it's obvious. Let now $a \neq 0$. Multiplying the first equation by $a$ and subtracting the second from it, we reduce the system to the form

$$\begin{cases} x + ay = \sqrt{3} \\ (a^2 - 2)y = a\sqrt{3} - \sqrt{6}. \end{cases}$$

Since $a^2 \neq 2$, $y$ takes a single value $\frac{a\sqrt{3} - \sqrt{6}}{a^2 - 2}$. Substituting it into the first equation, we find the only value $x$. Thus, if as $a$ we take not the number $\sqrt{2}$ itself, but some approximation of it, then $a^2 \neq 2$ means that the system has a unique solution.

It remains to be reminded (“Algebra 7,” p. 28) that the number $\sqrt{2}$ itself cannot be represented as a finite decimal fraction (or even in the form of any fraction $\frac{p}{q}$, where $p$ and $q$ are integers).

Because of this, we got a paradox associated with solving system (1) on a computer.

Let us pay attention to the fact that even in the case when all the coefficients of a given system are finite decimal fractions, when they are rounded, the solution of the system can greatly change. Thus, system (2) is obtained by rounding the coefficients of system (3), and at the same time their solutions are completely different. In a system with a large number of variables, errors that occur during rounding can even lead to significantly altered solutions.

Estimating the error and specifying a solution process that guarantees the smallest error is an important and far from simple task. At the beginning of the last century, the great mathematician Gauss began to study it, and significant further advances in this direction were made only in the last decimal years. Due to Gauss's seminal contributions to the field, a simple and universal method of eliminating variables is named after him.

Gauss method

Sequential elimination of variables is the most convenient way to solve a system of linear

⟦folio 27⟧

Equation on a computer. Let us demonstrate it using the example of a system of three equations with three variables

$$\begin{cases}
x_1 + x_2 + 2x_3 = -1 \\
2x_1 - x_2 + 2x_3 = -4 \\
4x_1 + x_2 + 4x_3 = -2.
\end{cases}$$

The first step is that, using the first equation, the variable $x_1$ is excluded from the remaining equations: the first equation is left unchanged; from the second equation we subtract the first one; from the third equation we subtract quadruple the first; we get

$$\begin{cases}
x_1 + x_2 + 2x_3 = -1 \\
-3x_2 - 2x_3 = -2 \\
-3x_2 - 4x_3 = 2.
\end{cases}$$

The second step is that, using the new second equation, the variable $x_2$ is eliminated from the third equation: the first two equations are left unchanged; subtract the second from the third equation; we get

$$\begin{cases}
x_1 + x_2 + 2x_3 = -1 \\
-3x_2 - 2x_3 = -2 \\
-2x_3 = 4.
\end{cases}$$

Now from the last equation we find $x_3 = -2$. Substituting this value into the previous equation, we find $x_2 = 2$. Substituting $x_2 = 2$ and $x_3 = -2$ into the first equation, we find $x_1 = 1$. So, we have the answer ready: $(1; 2; -2)$.

You can solve any system of linear equations in a similar way. Roughly speaking, the Gaussian method is as follows:

Using the first equation, the variable $x_1$ is excluded from the remaining equations. The new second equation then removes the variable $x_2$ from all subsequent equations. Then, using a new third equation, the variable $x_3$ is eliminated. And so on until we get the value of the last variable in the last equation. After this, we find the variables in reverse order, substituting their known values ​​into the equation.

We see that this is an almost ready-made computer program. But for this method to compare, it is necessary that at the $k$th step the new $k$th equation contains the $k$th variable (after all, with its help we need to exclude this variable from the remaining equations). If it turns out that this is not so, it comes to rearranging (re-measuring) the equations or variables.

It may also be that from some point the last equations turn into numerical equalities of the form $0 = b$. If at least one of these equalities is false ($b \neq 0$), then the system has no solutions. If all these equalities are true, then the system has an infinite number of solutions. (All are also considered provided by the use of a computer program.)

Note that it is not equations that are entered into the computer, but tables of coefficients—the so-called system matrices. For example, the system we just solved is associated with the matrix

$$\begin{pmatrix}
1 & 1 & 2 & -1 \\
2 & -1 & 2 & -4 \\
4 & 1 & 4 & -2
\end{pmatrix}$$

The two steps of the Gaussian method that we took to solve the problem can be depicted as follows:

$$\begin{pmatrix}
1 & 1 & 2 & -1 \\
2 & -1 & 2 & -4 \\
4 & 1 & 4 & -2
\end{pmatrix} \rightarrow \\
\begin{pmatrix}
1 & 1 & 2 & -1 \\
0 & -3 & -2 & -2 \\
0 & -3 & -4 & -2
\end{pmatrix} \rightarrow \\
\begin{pmatrix}
1 & 1 & 2 & -1 \\
0 & -3 & -2 & -2 \\
0 & 0 & -2 & 4
\end{pmatrix}$$

By the way, it was said that when systems with a tray and a large number of variables are solved manually, and not on a computer, it is also more convenient to work with matrices - there is less chance of making mistakes.

Problem 8. Solve the system proposed by the seven-classicists at the 2nd type XV of the Moscow region:

$$\begin{align*}
x_1 + 2x_2 + 2x_3 + 2x_4 + 2x_5 &= 1 \\
x_1 + 3x_2 + 4x_3 + 4x_4 + 4x_5 &= 2 \\
x_1 + 3x_2 + 5x_3 + 6x_4 + 6x_5 &= 3 \\
x_1 + 3x_2 + 5x_3 + 7x_4 + 8x_5 &= 4 \\
x_1 + 3x_2 + 5x_3 + 7x_4 + 9x_5 &= 5.
\end{align*}$$

Miscellaneous tasks

9. The mathematician went out for a walk - at first he took a flat road, then went up the mountain, turned back and came home the same way.

⟦folio 28⟧

Fig. 1. Fig. 2. Fig. 3.

Expensive. He knew that he had been walking for only 5 hours, that his speed on a level road was 4 km/h, uphill - 3 km/h and when going downhill - 6 km/h. Sitting down at the table and composing one equation with two variables: $x$ - the distance traveled at both ends and $y$ - the length of the inclined section, the mathematician was surprised to find that he could find $x$. Find $x$.

10. 4 gnomes are sitting at a round table. Before each stop there is a mug of milk. One of the dwarves pours $\frac{1}{4}$ of his milk to the neighbor on the right. Then the neighbor does the same. Then the next neighbor does the same and, finally, the fourth gnome $\frac{1}{4}$ pours the milk he has for the first one. All mugs together contain 2 liters of milk. How much milk was initially in the mugs, if
a) in the end all the gnomes had as much milk as they had at the beginning?

11. Define the numbers $a, b$ and $c$ so that the function $y = ax^2 + bx + c$ has a table of values

Solution. Substituting sequentially the given values ​​$x$ and $y$ into the formula $y = ax^2 + bx + c$, we obtain $1 = a \cdot 0 + b \cdot 0 + c, 2 = a \cdot 1 + b \cdot 1 + c, 2 = a \cdot 2^2 + b \cdot 2 + c$. Having solved this system of equations, we find $c = 1$, $a = -\frac{1}{2}, b = \frac{3}{2}$. Therefore, the function has the form
$$y = -\frac{1}{2}x^2 + \frac{3}{2}x + 1.$$

12. Define the numbers $a, b$ and $c$ so that the function $y = a + b(x-1) + c(x-1)(x-2)$ has a table of values

Solution. From figure 1 the system is obtained

$\cdot$ Since this article is primarily intended for seventh-class students, hereinafter the notations from A. V. Pogorelov’s textbook “Geometry 6-10” are used.

⟦folio 29⟧

Fig. 4. Fig. 5.

$$x + y = c, y + z = a, z + x = b.$$

It, of course, can be easily solved by any of the above methods, but it is more beautiful and easier to do otherwise. Let's add all three equations. We get $2x + 2y + 2z = a + b + c$, from where $x + y + z = \frac{a + b + c}{2}$. Subtracting each of the system equations from this equation, we find $x = \frac{b + c - a}{2}, y = \frac{a + c - b}{2}, z = \frac{a + b - c}{2}$.

16. Based on $AB$ of equilateral triangle $ABC$, point $E$ is taken. The triangle $ACE$ and $ECB$ contain inscribed circles that touch the segment $CE$ at points $K$ and $H$. respectively. Find the length of the segment $KH$ if $AE = a, EB = b$.

17. (Memoirs were offered at the XXIII Ukrainian Olympid in 1983) The rectangle is divided into squares as shown in figure 2. It is known that the side of the protected square is equal to 1. Find the sides of the remaining squares.

Solution. Let us denote the required sides by $x, y, z, u$ (see Fig. 2). Then $MN = y = u + 1, AB = x = y + 1, KL = z = x + 1$. Substituting $y = u + 1$ into the second match, we find $x = u + 2$. Substituting $x = u + 2$ into the third correspondence, we find $z = u + 3$. Now let’s write down the equality of opposite sides of the rectangle: $x + z = y + 2u$; substituting $x, y$ and $z$ here, we get $(u + 2) + (u + 3) = (u + 1) + 2u$, hence $u = 4$. Now we find $x = 6, y = 5, z = 7$.

18. The rectangle is divided into squares as shown in figure 3. It is known that the side of the protected square is 2. Find the sides of the remaining squares.

The next two problems deal with branched electrical circuits made up of conductors of unit resistance. Each circuit is connected to the source at two points (poles). Toki obey Kirchhoff's right laws, which for the considered circuits can be formulated as follows:

1) The sum of the currents entering any node is equal to the sum of the currents leaving it (the pole is not considered a node).

2) In any closed circuit, the sum of the currents flowing clockwise is equal to the sum of the currents flowing counterclockwise $^*$).

19. figure 4 shows an electrical circuit with poles $A, C$ and nodes $B, D$. Find the currents in all conductors of this circuit if it is known that the current in conductor $DB$ is equal to 1. (The arrows indicate the directions of the currents.)

20. figure 5 shows electrical circuits with poles $A$ and $C$. Find the currents in their conductors, if it is known that in each circuit the current in the conductor $CD$ is equal to 1. Some currents turn out to be zero and imprinted, what does this mean?

21. Two people play a game like this: in the system
$$\begin{cases} x + y = * \\ x + y = * \end{cases}$$
They take turns putting some number together with an asterisk; the first wants the resulting system to have a solution, and the second wants the system to have no solutions. Who will win if played correctly? And who will win if, on the contrary, the first wants the resulting system to have no solutions, and the second wants it to have?

22. (It was offered in the eighth and tenth grades at the XXIII All-Union Olympid and was included in the “Kvaンタ” task under the number M578; see the solution in the “Answers, instructions, solutions” section.) Solve the system $(a$ and $b$ - given numbers)
$$\frac{x - y \sqrt{x^2 - y^2}}{\sqrt{1 - x^2 + y^2}} = a, \quad \frac{y - x \sqrt{x^2 - y^2}}{\sqrt{1 - x^2 + y^2}} = b.$$

$^*)$ It is more correct to say that the same sums of direction drops, but since all conductors have unit resistance, we can talk about currents.
