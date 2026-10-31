---
id: 1976-7-obschiy-vid-i-shema-schyotnoy-mashinyi-b-paskalya-663e5cca
issue: kvant_1976_7
year: 1976
number: "7"
title: General view and diagram of B. Pascal's calculating machine
rubric: smes
page_first: 2
page_last: 10
page_labels: 1, 4, 5, 6, 7, 8
tag: WY0R
lang: en
source: kvant_digital
extraction: vision
content_sha256: a81cfe2e9f57954416e11daa942b6121634cc2f21bd3877ab58176c37273ffe5
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/02_obschiy-vid-i-shema-schyotnoy-mashinyi-b-paskalya-663e5cca.md
source_content_sha256: 7547cd568b6ab3ca5ea9012ca40ecf69f4a13f8a17b9d8d2dcc6c3a2194827e1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

This page shows a general view and diagram of a summing machine designed by one of the most significant people in human history - Blaise Pascal (1623-1662). His portrait is on the left. Pascal, his life, numerous scientific achievements, discoveries, ideas and inventions have already been described in «Kvant» (1973, No. 8, p. 4). It also told about the car he built (pp. 10-11). Pascal's contemporaries called it the "Pascalian wheel". About computers, the history of their invention, the structure (logical and physical) of modern computers and their applications are described in detail in the intersecting book by R. S. Guter and Yu. L. Polunov “Mathematical Machines,” published by the publishing house “Prosveshcheniye” in 1975. I advise you to read it. You can find the solution to this book at p. 50 of this issue of the magazine.

⟦folio 1⟧

Editor-in-Chief
Academician I. K. Kikoin
First Deputy
editor-in-chief
Academician A. N. Kolmogorov

Editorial collection:
M. I. Bashmakov
S. T. Belyaev
V. G. Boltyansky
N. B. Vasiliev
Yu. N. Efremov
V. G. Zubov
P. L. Kapitsa
V. A. Kirillin
A. I. Klimanov
(main artist)
S. M. Kozel
V. A. Leshkovtsev
(deputy editor-in-chief)
L. G. Makar-Limanov
A. I. Markushevich
N. A. Patrikeeva
I. S. Petrakov
N. Kh. Rozov
A. P. Savin
I. Sh. Slobodetsky
M. L. Smolyansky
(deputy editor-in-chief)
Y. A. Smorodinsky
V. A. Fabrikant
A. T. Tsvetkov
M. P. Shaskolskaya
S. I. Schwartzburg
A. I. Shirshov

Editorial:
V. N. Berezin
A. N. Vilenkin
I. N. Klumova
T. M. Makarova
(art editor)
T. S. Petrova
V. A. Tikhomirova
L. V. Chernova
(editorial manager)

IN THE ROOM:
2 B. Aleynikov, P. Buzitsky, M. Dubson. Simplex method
9 E. Ghazaryan, R. Sahakyan. About one method for solving a problem in electrostatics
14 A. Dozorov. Why does a transformer need a core?

Laboratory «Kvant»
18 M. Head. Gaidingar figure
Math circle
21 E. Gottman. Proof problems
25 Ya. Ponarin. Calculation of areas
Problem book «Kvant»
28 Problems M391—M395; F403—F407
30 Solutions to problem M351 - M353; F358 — F361

Applicant's workshop
37 Donetsk State University
38 Moscow Institute of Management named after. S. Ordzhonikidze
39 Moscow Institute of Electrical Wiring and Mechanical Engineering
40 Belarusian Institute of Railway Transport Engineers
41 Donetsk Political Institute
43 Mari Political Institute named after. M. Gorky
43 Yaroslavl Political Institute
44 Moscow State Pedagogical Institute named after. V. I. Lenina
45 Moscow Regional Pedagogical Institute named after. N. K. Krupskaya

X All-Union Olympiad for Schoolchildren
48 V. Berezin, V. Tikhomirova. Moscow City Olympiad for Schoolchildren

Reviews, bibliography
50 E. Belaga. "Mathematical machines"
51 L. Karmazina, N. Meller. "ALGOL 60"
52 I. Klumova, M. Smolyansky. New books
«Kvant» for younger students
54 Problems
55 A. Orlov. Ponsk subject
58 Answers, directions, solutions
Mixture (p. 47)

© Main editorial office of physical and mathematical literature of the publishing house “Nuka”, «Kvant», 1976 200

⟦folio 4⟧

The solution $x_1^0, x_2^0, \ldots, x_n^0$ of system (1) is called an admissible solution of the OLP if the numbers $x_1^0, x_2^0, \ldots, x_n^0$ are non-negative. We will call optimal the one of the feasible solutions that turns the objective function (2) to a minimum.

A specific OPLP may not have a solution: system (1) may be inconsistent, that is, it may not have a solution at all; it may be consistent, but has no admissible solutions; finally, it may even have admissible solutions, but among them there may not be an optimal one: function (2) may not be limited to the set of admissible solutions. However, all these descriptions will support us only in specially invented tasks; In the natural possibility of practical problems, a solution, as a rule, exists.

Let us assume that system (1) is consistent and its equations are linearly independent, that is, none of them can be derived from the others. It can be proven that then $m \leq n$.

Let us first consider the case when the number of equations $m$ is equal to the number of variables $n$. In linear algebra it is proven that in this case system (1) has a unique solution. If this solution is feasible, it will automatically be optimal.

The case of interest is when $m < n$ (in practice this corresponds to the possibility of choosing different action plans). Let's denote $n - m$ by $k$. In linear algebra, it is proven that some $m$ variables (they are called basic) can be expressed in terms of the remaining $k$ variables (they are called free). System (1) considers the case of an infinite number of solutions: by assigning arbitrary values ​​to the free variables and calculating the correspondence of the basic variables, we will each time obtain a new solution to system (1). Some solution of system (1) is called *reference* if the values ​​of at least $k$ variables are equal to zero. In linear programming theory, it is proven that the optimal solution is the reference one.

From this last theorem the following plan for solving the OLP follows: somehow choose $k$ free variables; we resolve the system with respect to $m$ the remaining basic variables; setting free variables equal to zero, we find the reference solution; We calculate the corresponding value of the objective function. Having gone through all the possibilities for choosing free variables, we will see on which of the support solutions the objective function will take the smallest value - this will be the desired optimal solution.

For simple problems in which the number of variables $n$ is incredible, this solution method—“blind” search—is in principle suitable. However, in problems that arise in practice, the number of variables and the number of imposed restrictions $m$ are usually very large - on the order of hundreds and even thousands. For such problems, simple enumeration is practically impossible: the number of possible ways to select free variables becomes enormous!

Since then, in the theory of linear programming, various methods have been developed that allow us to find the optimal solution not by “blind” search, but in such a way that each subsequent choice of free variables brings us closer to the solution.

The oldest and most famous of them is the *simplex method*, created in the late forties by the American mathematician J. Dantz.

**Simplex-method**

Let, for example, let the variables $k$ variables $x_1, x_2, \ldots, x_k$ be chosen as free variables, and the remaining $m$ variables expressed through

⟦folio 5⟧

them:

$$\begin{align*}
x_{k+1} &= \alpha_{k+1,1} x_1 + \alpha_{k+1,2} x_2 + \\
&\quad + \dots + \alpha_{k+1,k} x_k + \beta_{k+1}, \\
x_{k+2} &= \alpha_{k+2,1} x_1 + \alpha_{k+2,2} x_2 + \\
&\quad + \dots + \alpha_{k+2,k} x_k + \beta_{k+2}, \\
x_n &= \alpha_{n,1} x_1 + \alpha_{n,2} x_2 + \\
&\quad + \dots + \alpha_{n,k} x_k + \beta_n.
\end{align*}$$

Setting all free variables equal to zero, we obtain the following systems (1):

$$\begin{align*}
x_1^0 &= x_2^0 = \dots = x_k^0 = 0, \\
x_{k+1}^0 &= \beta_{k+1}, x_{k+2}^0 &= \beta_{k+2}, \dots \\
\dots, x_n^0 &= \beta_n.
\end{align*}$$

If all free terms $\beta_{k+1}, \beta_{k+2}, \dots, \beta_n$ are non-negative, solution (6) is admissible.

To check whether it is optimal, we express the objective function $L$ in terms of the free variables $x_1, x_2, \dots, x_k$, substituting the expressions for $x_{k+1}, x_{k+2}, \dots, x_n$ from (5) into (2):

$$L(x_1, x_2, \dots, x_n) = d_0 + d_1 x_1 + d_2 x_2 + \dots + d_k x_k.$$

From (6) it follows that $L(x_1^0, x_2^0, \dots, x_n^0) = d_0$. Let's see if we can decrease the value of the objective function $L$ by increasing the values ​​of the free variables $x_1, x_2, \dots, x_k$ (we cannot decrease them, since in solution (6) they are equal to zero, and we are looking for an admissible solution).

If all the coefficients $d_1, d_2, \dots, d_k$ in equality (7) are non-negative, then by increasing the values ​​of the free variables, we will decrease the value of the function $L$, i.e. we will incriminate the solution. In this case, the solution is not optimal for us.

Let, for example, in equality (7) the coefficient $d_1$ be negative. If in system (5) all coefficients for $x_1$ are non-negative, then any increase in the value of the variable $x_1$ will leave the values ​​of the variables $x_{k+1}, x_{k+2}, \dots, x_n$ non-negative and we will not leave the region of feasible solutions. The value of the function $L$ will decrease without limit. Thus, in this case there are also equations of system (5) in which the coefficient of $x_1$ is negative. For variables on the left-hand sides of these equations, increasing the value of the variable $x_1$ is described: it can make them negative.

If, for example, $\alpha_{k+1,1} < 0$, then, obviously, the value of the variable $x_1$ can only be reduced to $-\frac{\beta_{k+1}}{\alpha_{k+1,1}}$. (For $x_1^0 = -\frac{\beta_{k+1}}{\alpha_{k+1,1}}$, $x_2^0 = \dots = x_k^0 = 0$ we get $x_{k+1}^0 = 0$.)

The averages of the variables for which the increase in the value of the variable $x_1$ is described, we choose the one that most likely goes to zero, that is, the one for which the increase in $-\frac{\beta_l}{\alpha_l,1}$ is the least.

Let this “most threatened” variable be $x_r$.

Let us now remove $x_1$ from the number of free variables and transfer them together to the group of free variables $x_r$, i.e., we resolve system (1) with respect to the basic variables

$$x_1, x_{k+1}, \dots, x_{r-1}, x_{r+1}, \dots, x_n.$$

Then everything is repeated: setting all free variables $x_2, \dots, x_k, x_r$ equal to zero, we find the corresponding solution; Let's express the objective function $L$ in terms of new free variables; if all the coefficients of the variables in the resulting expression

⟦folio 6⟧

For $L$ are non-negative, the solution found is optimal; otherwise, the process of selecting basis variables and improving the solution continues.

The described algorithm is called the simplex method. (Did you, reader, notice that in our presentation of the algorithm one “hole” was left: one possibility was not considered?)

Two examples

Let us first consider a general school problem.

Problem 1. Three cyclists want to get to a forest lake located 20 km from the house. They have one two-seater moped that can travel at a speed of 36 km/h. Each cyclist can walk at a speed of 4 km/hour. How to organize traffic so that everyone can get to the lake faster? What is the shortest time in which this can be done?

Obviously, multiple changes of passengers at sea cannot provide any time benefit compared to a single change. Therefore, we will draw up the following plan for organizing the movement: at the initial moment of time, a schoolchild simultaneously leaves house $\Delta$ for moredev and a third schoolchild leaves on foot. At the intermediate point $T$ the moreda driver expresses his definition $t_1 = t_2$.

We need to find a $x$ for which the function $t = \max (t_1, t_2)$ takes the smallest value. In addition, we need to find the value of the function $max (t_1, t_2)$ with $x$, i.e. the number ($\max (t_1, t_2)$). From figure 2 (on it the graph of the function $t_1(x)$ is drawn in red, in black - the function $t_2(x)$, in blue - the function $max (t_1, t_2)$) it is immediately clear that the desired $x$ is determined from the equation $t_1 = t_2$.

However, to illustrate the general method, we pose and solve this problem as a linear programming problem. Let us reformulate it this way: find the smallest $t$ for which both $t \geq t_1$ and $t \geq t_2$. So, we need to find non-negative values ​​of the variables $x$ and $t$ that would satisfy the system of inequalities

$$\begin{cases} t \geq \frac{x}{36} + \frac{20-x}{4}, \\ t \geq \frac{5}{9} + \frac{2}{45} x \end{cases}$$

⟦folio 7⟧

and minimized the function $L$:
$$L(x, t) = 0 \cdot x + 1 \cdot t = t. \tag{9}$$
We have a linear programming problem. Let's reduce it to OZLP.
System (8) is equivalent to system
$$\begin{cases} 2x + 9t - 45 \geq 0, \\ -2x + 45t - 25 \geq 0. \end{cases} \tag{10}$$

Let us denote $2x + 9t - 45$ by $y_1$, $-2x + 45t - 25$ by $y_2$. Then $2x + 9t - 45 = y_1$, $-2x + 45t - 25 = y_2$ and $y_1 \geq 0, y_2 \geq 0$. We can now formulate our task as follows: find non-negative values ​​of the variables $x, t, y_1, y_2$ that would satisfy the system of equations
$$\begin{cases} 2x + 9t - y_1 = 45, \\ -2x + 45t - y_2 = 25 \end{cases} \tag{11}$$

and minimized the objective function $L(x, t, y_1, y_2) = t$. And this is already an OZLP. Let's solve it using the simplex method.

Let us choose $y_1$ and $y_2$ as basic variables (system (11) is easiest to solve with respect to them) and express them in terms of free variables $x, t$:
$$\begin{cases} y_1 = 2x + 9t - 45, \\ y_2 = -2x + 45t - 25. \end{cases} \tag{12}$$

Setting the free variables equal to zero, we obtain a solution to system (12) and (11):
$$x^{(1)} = t^{(1)} = 0, y_1^{(1)} = -45, y_2^{(1)} = -25.$$
This solution is not valid.

Let us now choose two other variables as basis variables, for example $t$ and $y_2$. (In the theory of linear programming, there is a method that indicates how to choose new free variables so as to approach the region of feasible solutions. We do not present this method here.) Let us resolve system (11) with respect to them:
$$\begin{cases} t = -\frac{2}{9}x + \frac{1}{9}y_1 + 5, \\ y_2 = -12x + 5y_1 + 200. \end{cases} \tag{13}$$

Setting free variables equal to zero, we obtain a solution to system (13) and (11):
$$x^{(2)} = y_1^{(2)} = 0, t^{(2)} = 5, y_2^{(2)} = 200. \tag{14}$$

Solution (14) is already admissible. To check whether it is optimal, we express the objective function $L$ in terms of the free variables $x$ and $y_1$. From (9) and (13)
$$L(x, t, y_1, y_2) = -\frac{2}{9}x + \frac{1}{9}y_1 + 5. \tag{15}$$

The value of the objective function $L$ on solution (14) is equal to 5.

Since the coefficient of $x$ in (15) is negative, solution (14) is not optimal: by increasing the value of the variable $x$, we will decrease the value of the objective function $L$.

In the general equations of system (13), the coefficients of $x$ are negative. Therefore, the increase in the value of the variable $x$ is described for both $t$ and $y_2$. This increase can make them negative. From the first equation of system (13) it follows that the value of the variable $x$ can be increased to $-5 / \left(-\frac{2}{9}\right) = \frac{45}{2} = 22 \frac{1}{2}$ (with this value $x$ and with $y_1 = 0$ we obtain $t = 0$; with a further increase in $x$ the value of the variable $t$ becomes negative); from the second - up to $-\frac{200}{12} = \frac{50}{3} = 16 \frac{2}{3}$. Thus, as the value of the variable $x$ increases, the variable $y_2$ will also go to zero: it is in a “more threatened” position than $t$.

⟦folio 8⟧

Let us now remove $x$ from the number of free variables and transfer it instead to the group of free variables $y_2$, i.e., resolve system (11) with respect to the basis variables $x$ and $t$:

$$\begin{cases}
x = \frac{5}{12} y_1 - \frac{1}{12} y_2 + \frac{50}{3}, \\
t = \frac{1}{54} y_1 + \frac{1}{54} y_2 + \frac{35}{27}.
\end{cases}$$

Setting the free variables equal to zero, we obtain a solution to system (16) and (11):

$$y_1^{(3)} = y_2^{(3)} = 0, \quad x^{(3)} = \frac{50}{3}, \\
t^{(3)} = \frac{35}{27}.$$

Let us express the objective function $L$ in terms of $y_1$ and $y_2$. From (9) and (16)

$$L(x, t, y_1, y_2) = \frac{1}{54} y_1 + \frac{1}{54} y_2 + \frac{35}{27}.$$

The value of the objective function $L$ on solution (17) is equal to $\frac{35}{27}$.

Since all coefficients of the variables in (18) are non-negative, solution (17) is optimal. So, the solution problem: the passenger needs to drop off the passenger at a distance $x^{(3)} = \frac{50}{3} = 16\frac{2}{3}$ (km); the shortest time in which you can get to the lake is $t^{(3)} = \frac{35}{27} = 1\frac{8}{27}$ (hour).

Let us now present a typical practical problem, which naturally became a linear programming problem. This is the so-called “diet problem” or “diet problem”.

Task 2. The director of the canteen needs to create a menu. He has 5 types of products at his disposal: bread, vegetables, fruits, meat, fish.

It is known that a kilogram of bread costs $c_1$ rubles, a kilogram of vegetables costs $c_2$ rubles, etc. It is also known that a kilogram of bread contains $a_{11}$ ke proteins, $a_{12}$ ke fats and $a_{13}$ ke carbohydrates, etc. (the content of proteins, fats and carbohydrates in a kilogram of each type of product is indicated in the table on figure 3). A maximum menu is required so that it contains at least $b_1$k proteins, at least $b_2$k fats and at least $b_3$k carbohydrates, and its cost is minimal.

Let us denote by $x_1$ the amount of bread that will be included in the menu, by $x_2$ the number of vegetables, etc. The total cost of the menu $L$ will obviously be expressed by the equality

$$L(x_1, x_2, x_3, x_4, x_5) = \sum_{i=1}^{5} c_i x_i.$$

Restrictions on the nutritional value of the menu are expressed by a system of inequalities

$$\begin{cases}
a_{11}x_1 + a_{21}x_2 + a_{31}x_3 + a_{41}x_4 + \\
+ a_{51}x_5 \geq b_1, \\
a_{12}x_1 + a_{22}x_2 + a_{32}x_3 + a_{42}x_4 + \\
+ a_{52}x_5 \geq b_2, \\
a_{13}x_1 + a_{23}x_2 + a_{33}x_3 + a_{43}x_4 + \\
+ a_{53}x_5 \geq b_3.
\end{cases}$$

Our task took the form: find non-negative values ​​of the variables $x_1, x_2, x_3, x_4, x_5$ that would satisfy the system of inequalities (20) and minimize the function $L$ from (19). This is a linear programming problem.
