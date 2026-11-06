---
id: 1991-11-gornshteyn-polonskiy-yakir-neobhodimyie-usloviya-i-zadachi-s-parametrami-753b6424
issue: kvant_1991_11
year: 1991
number: "11"
title: Necessary conditions and tasks with parameters
authors:
  - Горнштейн П. И.
  - Полонский В. Б.
  - Якир М. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 51
page_labels: 44-49
lang: en
source: kvant_digital
extraction: vision
content_sha256: b284ab253a4aab9be5f5cac16c11ffd8d4ab58933a996183514eb3d8bde53972
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/16_gornshteyn-polonskiy-yakir-neobhodimyie-usloviya-i-zadachi-s-parametrami-753b6424.md
source_content_sha256: 71b6257ea0f0819e56a10e04346559705d6091d67916b493ab7cffb34b5f2460
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 44⟧

---
running_head:
folio:
---

Necessary conditions and tasks with parameters

P. GORNITEIN, V. POLONSKY, M. YAKIR

Fans of detective stories are familiar with the standard scheme: the circle of suspects gradually narrows, and, finally, the great Cape Puar discovers a representative. It turns out that a similar plot is implemented in a whole class of mathematical problems. Here's an example.

We need to solve the equation $f(x)=g(x)$. First, the entire set of real numbers is suspected of being the roots of the equation. Let's exclude those that have a very strong alibi: the roots of our equation cannot occur outside the domain of definition of the function $f$ and $g$.

If it has been possible to establish that all the roots of the equation lie in a certain set $M$, a necessary condition appears under which the equality $f(x)=g(x)$ is realized: if $x$ is the root of the equation, then $x \in M$. We will call problems solved by this method problems with necessary conditions in Japanese.

Let us illustrate what has been said with specific examples.

Problem 1 (MSU, 1983). Solve the inequality

$$\left( \sqrt{x^2}-5x+6+1 \right) \log_3 \frac{2x}{5} + \frac{1}{x} \sqrt{10x-2x^2-12} \leq 0.$$

The domain of this inequality is the two-element set {2; 3}. Checking shows that only $x=2$ satisfies the inequality.

Problem 2. At what values ​​of parameter a is the system of equation

$$\begin{cases} a(x^4+1)=y+1-|x|, \\ x^2+y^2=1 \end{cases}$$

has a unique solution.

Obviously, if $(x_0; y_0)$ is a solution to the system, then $(-x_0; y_0)$ is also its solution. Therefore, condition $x=0$ is necessary for the existence of a unique solution. Note that it is not worthy: our system may have several solutions of the form $(0; y_0)$ or no solution at all.

Let's put $x=0$. Then

$$\begin{cases} a=y+1, \\ y^2=1. \end{cases}$$

Hence $a=0$ or $a=2$.

So, to find the commme value of the parameter, we must select it from the set {0; 2}. For $a=0$ we get:

$$\begin{cases} y+1-|x|=0, \\ x^2+y^2=1, \end{cases}$$

where

$$\begin{cases} |x|=y+1, \\ y^2+2y+1+y^2=1, \end{cases}$$

pose

$$\begin{cases} x=1, \\ y=0, \end{cases}$$

or

$$\begin{cases} x=-1, \\ y=0, \end{cases}$$

⟦folio 45⟧

---
running_head:
folio:
---

As you can see, three solutions to the system were found, which means that $a=0$ does not satisfy the conditions of the problem.
For $a=2$ we get:
$$\begin{cases} 2x^4 + |x| = y - 1, \\ x^2 + y^2 = 1. \end{cases}$$
Obviously $2x^4 + |x| \geq 0$. From the first equation we have $y \geq 1$, from the second - $y \leq 1$. Therefore, $y=1$ means $x=0$. Checking shows that the pair (0; 1) is a solution, and due to the restriction for the variable $y(y \geq 1$ and $y \leq 1)$ it is unique.
Answer: $a=2$.
Problem 3 (MSU, 1990). For what values ​​of the parameter c does equation $x^2 - 2c \sin(\cos x) + 2 = 0$ have a unique solution?
Obviously, $x=0$ is a necessary condition for the existence of a single root of this equation.
For $x=0$ we have
$$c = \frac{1}{\sin 1}.$$
Let us prove that this parameter value is exceptional.
Indeed, for $c = \frac{1}{\sin 1}$ we obtain
$$x^2 + 2 = \frac{2}{\sin 1} \sin(\cos x).$$
(1)
Obviously $x^2 + 2 \geq 2$. Consider the function $f(t) = \sin t$. For $t \in [-1; 1] \subset [-\pi/2; \pi/2]$, the function $f$ returns. Therefore, $\sin(\cos x) \leq \sin 1$. From here
$$\frac{2 \sin(\cos x)}{\sin 1} \leq \frac{2 \sin 1}{\sin 1} = 2.$$
This means that equation (1) is equivalent to the system
$$\begin{cases} x^2 + 2 = 2, \\ \frac{2 \sin(\cos x)}{\sin 1} = 2, \end{cases}$$
having a unique solution $x=0$.
Answer: $c = \frac{1}{\sin 1}$.
Problem 4 (MSU, 1988). Find all values ​​of the parameter $a$, for which

many equivalent systems
$$\begin{cases} x + 2y = 2 - a, \\ -x + ay = a - 2a^2 \end{cases}$$
(2)
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2x^2 + y^2 + (a^2 + 2a - 11)x + 12 - 6a = 0. \end{cases}$$
(3)
System (2) consists of two linear equations with two variables. It has a unique solution if $a \neq -2$.
By direct verification we establish that for $a=-2$ system (2) does not have a solution.
System (3) at $a=-2$ becomes:
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2x^2 + y^2 - 11x + 24 = 0. \end{cases}$$
The second equation contains a quadratic trinomial with respect to $x: 2x^2 - 11x + 24$. Its discriminant is imprinted, so the second equation does not.
Thus, $a=-2$ satisfies the conditions of the problem.
Let now $a \neq -2$. In this case, the first system has a unique solution, therefore, for systems (2) and (3) to be equivalent, it is necessary that the second system also has a unique solution. (Note that a sufficient condition for their equivalence is the coincidence of the solution.)
Here, as in Problem 1, the conditions $y=0$ are necessary for the existence of a unique solution to system (3) (check it!). For $y=0$ the second system takes the form
$$\begin{cases} x^2 - 4x + 3 = 0, \\ 2x^2 + (a^2 + 2a - 11)x + 12 - 6a = 0. \end{cases}$$
From here
$$\begin{cases} x = 1, \\ a^2 - 4a + 3 = 0, \end{cases}$$
or
$$\begin{cases} x = 3, \\ a^2 = 1. \end{cases}$$
Consequently, the required values ​​of the parameter $a$, if they exist, belong to the set {-1; 1; 3}. For $a=-1$ system (2) also:
$$\begin{cases} x + 2y = 3, \\ -x - y = -3. \end{cases}$$

⟦folio 46⟧

---
running_head:
folio:
---

It has a unique solution (3; 0). The second system takes the form
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2x^2 + y^2 - 12x + 18 = 0, \end{cases}$$
or
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2(x - 3)^2 + y^2 = 0. \end{cases}$$
Hence $x = 3, y = 0$. Since the solution to the system coincided, $a = -1$ satisfies the conditions of the problem.
For $a = 1$ it is easy to establish that system (2) has a unique solution $- (1; 0)$, and system (3) has two solutions $- (1; 0)$, $(3; 0)$.
For $a = 3$, system (2) has a unique solution $\left(\frac{27}{5}; -\frac{16}{5}\right)$, which does not satisfy system (3).
Answer: $a = -2$ or $a = -1$.
Problem 5 (KPI, 1989). For what negative integers $n$ does the function $f(x) = \cos nx \sin \frac{15x}{n^2}$ satisfy the condition $f(x + 5\pi) = f(x)$ for all $x \in R$.
According to the conditions of the problem, the equality
$$\cos n(x + 5\pi) \sin \frac{15x}{n^2} (x + 5\pi) =
= \cos nx \sin \frac{15x}{n^2}$$
must hold for any real $x$, and therefore also for $x = 0$.
In this case we have
$$\cos 5\pi n \cdot \sin \frac{75\pi}{n^2} = 0.$$
Since $\cos 5\pi n \neq 0$, then $\sin \frac{75\pi}{n^2} = 0$, i.e. $\frac{75}{n^2} = k$, where $k$ is an integer. Hence $n^2 = 1$ or $n^2 = 25$. The area of ​​interest has only negative values ​​$n$, so solutions to the problem should be sought in the set $-1; -5$. Checking shows that for both $n = -1$ and $n = -5$ our equality holds for all real $x$.
Answer: $n = -1$ or $n = -5$.
The reader, of course, will ask why we substituted exactly $x = 0$ in our equality? You can, of course, substitute some other sign
value $x$: after all, equality must hold for any $x$. But $x = 0$ is much easier to use and does not produce cumbersome formulas. In such cases, the choice of the most beneficial variable values ​​is often based on intuition and personal experience.
Problem 6 (MSU, 1989). Find everything with also that for any $b$ system
$$\begin{cases} (1 + 3x^2)^c + (b^2 - 4b + 5)^y = 2, \\ x^2y^2 - (2 - b)xy + c^2 + 2c = 3. \end{cases}$$
has at least one solution.
This system must have at least one solution for any $b$, and therefore for $b = 2$. In this case
$$\begin{cases} (1 + 3x^2)^c = 1, \\ x^2y^2 + c^2 + 2c = 3, \end{cases}$$
where
$$\begin{cases} x = 0, \\ c^2 + 2c = 3 \end{cases}$$ or $$\begin{cases} c = 0, \\ x^2y^2 = 3. \end{cases}$$
The range of “suspected” values ​​for the variable $c$ is essentially $-3; 0; 1$.
For $c = -3$ we get
$$\frac{1}{(1 + 3x^2)^3} + (b^2 - 4b + 5)^y = 2,$$
$$x^2y^2 - (2 - b)xy = 0.$$
Obviously, this system has a solution $(0; 0)$ for any $b$.
At $c = 0$
$$\begin{cases} (b^2 - 4b + 5)^y = 1, \\ x^2y^2 - (2 - b)xy = 3. \end{cases}$$
If $b \neq 2$, then the solution to the first equation $y = 0$ does not satisfy the second equation. But according to the condition, the system must have a solution for any $b$, which means that $c = 0$ will have to be excluded from the list of “suspects”.
At $c = 1$
$$\begin{cases} 3x^2 + (b^2 - 4b + 5)^y = 1, \\ x^2y^2 - (2 - b)xy = 0. \end{cases}$$
Obviously, this system has a solution $(0; 0)$ for any $b$.
Answer: $c = 1$ or $c = -3$.
Problem 7 (MAI, 1989). For what $x$ for any $y$ there exists $z$ also, that

⟦folio 47⟧

---
running_head:
folio:
---

$$\sin(x + y + z) = \cos\left(2x + \frac{\pi}{3}\right)\left|y + \frac{1}{2}\right| + \frac{|y - 3/2|}{2\cos x}$$

Let's substitute $y = -1/2$ into the equation. Then
$$\sin\left(x + z - \frac{1}{2}\right) = \frac{1}{\cos x},$$

whence $\cos x = 1$ or $\cos x = -1$. When $\cos x = 1$, i.e. $x = 2\pi k$, $k$ is an integer, we get
$$\sin(2\pi k + y + z) = \cos\left(4\pi k + \frac{\pi}{3}\right)\left|y + \frac{1}{2}\right| + \frac{|y - 3/2|}{2\cos x},$$
follow,
$$\sin(y + z) = \frac{|y + 1/2|}{2} + \frac{|y - 3/2|}{2}.$$
We have
$$|\sin(y + z)| \leq 1,$$
But
$$\frac{|y + 1/2|}{2} + \frac{|y - 3/2|}{2} \geq 1.$$
At figure 1 there is a graph of the function
$$f(x) = \frac{|y + 1/2|}{2} + \frac{|y - 3/2|}{2}.$$
It is clear that the equality from the problem conditions for $x = 2\pi k$ is not satisfied for all $y$, but only for $y \in [-1/2; 3/2].$

When $\cos x = -1$, i.e. $x = \pi + 2\pi k$, $k$ is an integer, we get
$$\sin(\pi + 2\pi k + y + z) = \cos\left(2\pi + 4\pi k + \frac{\pi}{3}\right)\left|y + \frac{1}{2}\right| + \frac{|y - 3/2|}{2\cos(\pi + 2\pi k)},$$

where
$$2\sin(y + z) = |y - 3/2| - |y + 1/2|.$$
Since
$$|2\sin(y + z)| \leq 2,$$
then the inequality must be satisfied
$$||y - 3/2| - |y + 1/2|| \leq 2.$$
figure 2 shows the graph of the function
$$f(y) = \left||y - \frac{3}{2}| - |y + \frac{1}{2}| \right|.$$
In this case, for any $y$ one can choose $z$ such that equality (4) is satisfied.

Answer: $x = \pi + 2\pi k$, $k \in \mathbf{Z}$.
Problem 8 (MAI, 1988). At what values ​​of the parameter $a$ the equations
$$\sin 2x + a = \sin x + 2a \cos x$$
u
$$2\cos 2x + a^2 = 5a \cos x - 2$$
are they equivalent?
It is easy to see that $x = \frac{\pi}{3}$ is the root of the first equation for any $a$. For

⟦folio 48⟧

---
running_head:
folio:
---

Equivalence of the equation requires that it also be the root of the second equation.

For $x = \frac{\pi}{3}$ we get
$$-1 + a^2 = \frac{5a}{2} - 2,$$
hence the contenders for the answer are $a = 2$ and $a = 1/2$.

At $a = 2$ the first equation takes the form
$$\sin 2x + 2 = \sin x + 4 \cos x,$$
and the second -
$$\cos 2x - 5 \cos x + 3 = 0.$$

The reader can easily see for himself that each of the last two equations is equivalent to the equation $\cos x = 1/2$.

At $a = 1/2$ the first equation becomes:
$$\sin 2x + 1/2 = \sin x + \cos x,$$
and the second one is like this:
$$2 \cos 2x + \frac{1}{4} = \frac{5}{2} \cos x - 2.$$

Obviously, the root of the first of them $x = -\frac{\pi}{3}$ is not the root of the second.

Answer: $a = 2$.

In all previous problems, sufficient conditions for excluding a parameter were established as a result of verification. However, another approach is also possible.

Since every sufficient condition is necessary, but not every necessary condition is sufficient, it is clear that consistent

Any successful necessary condition can ultimately be reduced to a sufficient one.

In conclusion, we give an example that reflects the above.

Problem 9 (MSU, 1988). For what values ​​of the parameters $a$ and $b$ the equation

$$|x + \cos^2 4a - 2 \sin a \cos^4 4a| + |x + \sin^2 a| = b \left(a + \frac{3\pi}{2}\right)$$

has a single solution?

Consider the function $f(x) = |x - c| + |x - d| + e (c, d$ and $e$ - some numbers). Without losing the generality of the argument, we set $d > c > 0, e > 0$. The graph considered by the function is schematically depicted in figure 3.

It is obvious that the equation $f(x) = A$ has a single root at $c = d$ (Fig. 4).

For Pozny, in order for the equation $f(x) = 0$ to have a single root, it is sufficient to satisfy the conditions $c = d$ and $e = 0$ (Fig. 5).

So, to find the initial values ​​of the parameters $a$ and $b$ we need to solve the system

$$\begin{cases} \sin^2 a = 2 \sin a \cos^4 4a - \cos^2 4a, \\ b \left(a + \frac{3\pi}{2}\right) = 0. \end{cases}$$

Let's consider the first of its equations:

$$\sin^2 a - 2 \sin a \cos^4 4a = -\cos^2 4a.$$

Let's add $\cos^8 4a$ to both of its parts:

⟦folio 49⟧

---
running_head:
folio:
---

$$\sin^2 a - 2 \sin a \cos^4 4a + \cos^8 4a = \cos^8 4a - \cos^2 4a.$$
Then
$$(\sin a - \cos^4 4a)^2 = \cos^8 4a - \cos^2 4a.$$
The right side of the resulting equation is non-positive:
$$\cos^8 4a - \cos^2 4a = \cos^2 4a(\cos^6 4a - 1) \leq 0,$$
This means that the equation has a solution only for
$$\begin{cases} \sin a = \cos^4 4a, \\ \cos 4a = 0 \end{cases}$$
or
$$\begin{cases} \sin a = \cos^4 4a, \\ \cos^6 4a = 1. \end{cases}$$
The first of these systems gives
$$a = \frac{\pi}{2} + 2\pi k, k - целое.$$
From the second we obtain that, on the one hand, $a = \frac{\pi}{8} + \frac{\pi k}{4}$, and on the other, $a = \pi k$, but for integer $k$ this cannot be.
Then we have
$$\begin{cases} a = \frac{\pi}{2} + 2\pi k, \\ b \left( a + \frac{3\pi}{2} \right) = 0, \text{ т. е.} \end{cases}$$
or
$$\begin{cases} a = \frac{\pi}{2} + 2\pi k, \\ b = 0 \end{cases}$$
or
$$\begin{cases} a = \frac{\pi}{2} + 2\pi k, \\ a = -\frac{3\pi}{2}, \\ b - целое. \end{cases}$$
Answer: $b = 0, a = \frac{\pi}{2} + 2\pi k, k - целое, или $a = -\frac{3\pi}{2}, b is a real integer.

Problems to solve independently
1 (MSU, 1990). For what values ​​of the parameter $b$ the equation
$$2x^2 - b \mathrm{tg} \cos x + b^2 = 0$$
has a single solution?
2 (MSU, 1987). Find all values ​​of the parameter $a$ for which the system
$$\begin{cases} 3 \cdot 2^{|x|} + 5 |x| + 4 = 3y + 5x^2 + 3a, \\ x^2 + y^2 = 1 \end{cases}$$
has a unique solution.
3 (MIREA, 1983). For what values ​​of the parameter $a$ does the system of inequalities
$$\begin{cases} y \geqslant (x + y)^2 - x - 2y - a, \\ x \geqslant (y - x)^2 - 3y + 2x + a \end{cases}$$
has a single solution?
4 (MAI, 1989). For what real values ​​of $x$, for any real $y$, is there a $z$ such that
$$\cos (2x - y + z) = |y^3 - 1| \cos \left( \frac{4\pi}{3} - 2x \right) + \frac{|y^3 + 1|}{2 \sin x} ?$$
5 (MSU, 1978). Find the set of all pairs of numbers $(a; b)$, for each of which, for all $x$, the following equality holds:
$$a \sin x + b = \sin (ax + b).$$
6 (Ural State University, 1976). Find such values ​​of the parameter $a$, for each of which the inequality
$$\sqrt{x^2 + 4x + 7} \leq x + 3$$
and equation
$$2^{x+2} - |2^{x+1} - a| = 2^{x+1} + 1$$
are equivalent.
7 (MSU, 1974). Find all real values ​​$\alpha$, for each of which there are even integers $(x, y, u, v)$ satisfying the equalities
$$x^2 + y^2 = (107 - \alpha)(\alpha - 91),$$
$$54(u^2 - v^2) = \alpha(15u + 3v - \alpha).$$
