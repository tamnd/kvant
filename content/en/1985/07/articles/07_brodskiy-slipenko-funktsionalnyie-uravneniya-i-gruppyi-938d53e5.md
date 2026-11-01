---
id: 1985-7-brodskiy-slipenko-funktsionalnyie-uravneniya-i-gruppyi-938d53e5
issue: kvant_1985_7
year: 1985
number: "7"
title: Functional equations and groups
authors:
  - Бродский Я. С.
  - Слипенко А. К.
rubric: osnovnye-stati
page_first: 25
page_last: 27
page_labels: 23-25
tag: 7Y9R
lang: en
source: kvant_digital
extraction: vision
content_sha256: b193c9dfa50bd5c089a595cbfc056ccd5a961724d58a5de78ce4095aa7c4ba1e
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/07_brodskiy-slipenko-funktsionalnyie-uravneniya-i-gruppyi-938d53e5.md
source_content_sha256: d97218f3c456cbd397ee38b966ee5b298380d9b201cee247934f6f3136c929a5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

Functional equations and groups

Y. S. BRODSKY, A. K. SLIPENKO

You are probably familiar with functional equations, although you may not know that they are called that. Thus, it is the functional equations $f(x)=f(-x), f(-x)=-f(x), f(x+a)=f(x)$ that define such properties of functions as evenness, oddness, and periodicity.

In general, a functional equation is a certain correspondence from which you need to find an unknown function.

For example, $f(x+1)+f(x)=x,$
$2f(1-x)+1=xf(x),$
$xf(x)+f\left(\frac{4}{2-x}\right)=x$.

Mathematicians began to study functional equations more than two hundred years ago, when problems of mechanics were brought to them. O. Cauchy (1789-1857) made a great contribution to the study of such equations. On the pages of our journal we have already considered the functional equation $f(x+y)=f(x)+f(y)$, which bears his name*). In this article we will consider one of the methods for solving functional equations, using the most important concept of modern algebra - the concept of group.

Composition of functions

You, of course, have noticed that the number of initial, basic functions studied in a school mathematics course is relatively small. These include, for example, linear, power, exponential, and trigonometric functions. Other functions can be obtained from the main ones using compositions and algebraic operations.

Thus, the function $f(x)=\sin(2x+1)$ is a composition of the linear function $g(x)=2x+1$ and the trigonometric function $h(x)=\sin x$, i.e. $f(x)=h(g(x))=(h\circ g)(x)$.

The function $f(x)=\lg \arcsin x$ is obtained as a result of the composition of the functions $g(x)=\arcsin x$ and $h(x)=\lg x$. Note that the domain of composition definition $h\circ g$ includes those values ​​$x$ of $D(g)$ for which $g(x)\in D(h)$. In the last example $D(g)=[-1; 1], D(h)=] 0; \infty$. [. Since $\arcsin x>0$ is at $x\in] 0; 1]$, then $D(f)=] 0; 1]$.

If we take the composition of these same functions in reverse order, that is, the function $f(x)=\arcsin \lg x$, we get $D(f)=\left[\frac{1}{10}; 10\right]$.

The composition of fractional linear functions $g(x)=\frac{-2x+1}{3x+2}$ and $h(x)=\frac{3x-2}{-x+4}$ are functions $f(x)=h(g(x))=$
$$\frac{3\cdot\frac{-2x+1}{3x+2}-2}{-\frac{2x+1}{3x+2}+4}=\frac{-12x-1}{14x+7}, x\neq-\frac{2}{3}.$$
Here $D(f)=R\left\{-\frac{2}{3},-\frac{1}{2}\right\}$.

Typically $f\circ g\neq g\circ f$. At the same time for any functions
$(f\circ g)\circ h=f\circ(g\circ h)$,

what is not represented is derived from the definition of composition.

Battles

1. Find compositions $f_1\circ f_2$ and $f_2\circ f_1$ of the following functions:
$f_1=\frac{x-2}{3x+4}, f_2=\frac{2x+3}{5x-1}$.

2. Find the composition domain of $1-x^2$ and $\sqrt{x}$.

3. Let $f(x)=\frac{x}{\sqrt{1-x^2}}$. Find $f\circ f\circ f\cdots f$.

Functional equations

Let's solve the following problem.
Problem 1. Find all functions $y=f(x)$ such that
$$2f(1-x)+1=xf(x).$$

⟦folio 24⟧

Solution. Let us assume that there is a function $f(x)$ that satisfies this equation. Replacing $x$ with $1-x$, we get

$$2f(x) + 1 = (1 - x)f(1 - x).$$

From (1) we find $f(1 - x) = \frac{1}{2}(xf(x) - 1)$.

Substituting the value $f(1 - x)$ and equation (2), we obtain

$$2f(x) + 1 = (1 - x) \cdot \frac{1}{2} \cdot (xf(x) - 1),$$

whence $f(x) = \frac{x - 3}{x^2 - x + 4}$.

By direct verification we are convinced that the resulting function satisfies equation (1).

In the equation considered, the subsign of the unknown function is the function $f_1 = x$ and $f_2 = 1 - x$. Replacing $x$ with $1 - x$ maps the function $f_1$ and $f_2$ to each other. Substituting $x \rightarrow 1 - x$ yields another equation containing $f(x)$ and $f(1 - x)$. We reduced the solution of the functional equation to the solution of a system of two linear equations with two unknowns.

Let's now consider a more complex problem.

Task 2. Solve the equation

$$xf(x) + 2f\left(\frac{x - 1}{x + 1}\right) = 1.$$

Solution. Let's try to act in the same way as in the first case. Let's replace $x \rightarrow \frac{x - 1}{x + 1}$. We get

$$\frac{x - 1}{x + 1}f\left(\frac{x - 1}{x + 1}\right) + 2f\left(-\frac{1}{x}\right) = 1.$$

Along with the expressions $f(x)$ and $f\left(\frac{x - 1}{x + 1}\right)$ we now have a new “unknown” $-f\left(-\frac{1}{x}\right)$. Let's try to apply one more substitution to (3): $x \rightarrow -\frac{1}{x}$. We have

$$-\frac{1}{x}f\left(-\frac{1}{x}\right) + 2f\left(\frac{x + 1}{1 - x}\right) = 1.$$

In addition to $f\left(-\frac{1}{x}\right)$, the “unknown” expression $f\left(\frac{x + 1}{1 - x}\right)$ appeared in the equation. Well, let's try to perform the substitution $x \rightarrow \frac{x + 1}{1 - x}$ into (3). And finally, we delete it. We get

$$\frac{x + 1}{1 - x}f\left(\frac{x + 1}{1 - x}\right) + 2f(x) = 1,$$

where new unknowns have not arisen, a system of four linear equations (3) - (6) with four unknowns $f(x)$, $f\left(\frac{x - 1}{x + 1}\right)$, $f\left(-\frac{1}{x}\right)$ and $f\left(\frac{x + 1}{1 - x}\right)$ is constructed. We sequentially exclude $f\left(\frac{x - 1}{x + 1}\right)$, $f\left(-\frac{1}{x}\right)$, $f\left(\frac{x + 1}{1 - x}\right)$, and find $f(x) = \frac{4x^2 - x + 1}{5x(x - 1)}$ ($x \neq -1, x \neq 0, x \neq 1$).

As when solving equation (1), we assumed that a function satisfying (3) exists. Check shows that $f$ satisfies equation (3).

Groups appear

Let's try to figure out why we were able to solve the equation of the previous paragraph.

Let's consider another equation

$$f(x + 1) + f(x) = x.$$

It looks no more “scary” than equation (3), but all attempts to solve it in the same way are futile: when replacing $x \rightarrow x + 1$, the “unknown” $f(x + 2)$ appears, and so on. The chain is not replaceable: we will never get a linear system.

Recall that when solving the first equation, we performed the substitution $x \rightarrow 1 - x$. At the same time $1 - x \rightarrow x$. That is, two functions $g_1(x) = x$ and $g_2(x) = 1 - x$ with respect to the composition operation behave like $g_1 \circ g_2 = g_2 \circ g_1 = g_2$, $g_2 \circ g_2 = g_1$, $g_1 \circ g_1 = g_1$.

Consider the “multiplication” table (at the intersection of the row numbered $i$ and the column numbered $j$ there is $g_i \circ g_j$).

Each row and column of this table contains both $g_1$ and $g_2$.

Let's now say that we need

⟦folio 25⟧

solve the equation

$$a(x)f(x) + b(x)f(1-x) = c(x),$$

(*)

where $a, b, c$ are some functions. It is clear that by substituting $x \rightarrow 1-x$ we obtain the equation

$$a(1-x)f(1-x) + b(1-x)f(x) = c(1-x),$$

(**)

which together with equation (*) forms a linear system of relative functions $f(x)$ and $f(1-x)$. Further, the solution will be developed in the same way as in solving Problem 1.

In the second example, we made substitutions

$$x \rightarrow \frac{x-1}{x+1}, x \rightarrow -\frac{1}{x}, x \rightarrow \frac{x+1}{1-x},$$

that is, names deal with functions

$$g_1(x) = x, g_2(x) = \frac{x-1}{x+1},$$

$$g_3(x) = -\frac{1}{x}, g_4(x) = \frac{x+1}{1-x}.$$

Let's see how functions $g_1, g_2, g_3, g_4$ behave in relation to the composition operation. Let's compose table 2, similarly to table 1 (at the intersection of the $i$th row and $k$th column we write $g_i \circ g_k$).

This table is symmetrical about its diagonal (this means that $g_i \circ g_k = g_k \circ g_i$ for any $k$ and $i$). Moreover, all functions $g_i$ occur in every row and every column equally once, and finally it is easy to notice that $g_3 = g_2^2, g_4 = g_3^2, g_1 = g_2^4$. Here $g_i^2 = g_2 \circ g_2 \circ \dots \circ g_2$.

Thus, the system of function $G = \{g_1, g_2, g_3, g_4\}$ has the following properties: a) it is closed under compositions; b) among these functions there is an identical mapping $g_1(x) = x$; c) each of the functions $g_i$ has an inverse $g_i^{-1}: g_1^{-1} = g_1, g_2^{-1} = g_4, g_3^{-1} = g_3, g_4^{-1} = g_2$.

The system of function $G = \{g_1, g_2\}$ from Example 1 has the same properties.

If we were now asked to solve any functional equation of the form

$$a(x)f(x) + b(x)f\left(\frac{x-1}{x+1}\right) + c(x)f\left(-\frac{1}{x}\right) + d(x)f\left(\frac{x+1}{1-x}\right) = h(x),$$

(***)

we would do this by making the substitutions $x \rightarrow g_2(x), x \rightarrow g_3(x), x \rightarrow g_4(x)$, after which we would arrive at a linear system. For example, let’s write down what comes out of (***) after replacing $x \rightarrow g_2(x)$.

Moreover, $g_2(x) \rightarrow g_3(x), g_3(x) \rightarrow g_4(x), g_4(x) \rightarrow g_1(x)$, so we get the equation

$$a\left(\frac{x-1}{x+1}\right)f\left(\frac{x-1}{x+1}\right) + b\left(\frac{x-1}{x+1}\right)f\left(-\frac{1}{x}\right) + c\left(\frac{x-1}{x+1}\right) \cdot f\left(\frac{x+1}{1-x}\right) + d\left(\frac{x-1}{x+1}\right)f(x) = h\left(\frac{x-1}{x+1}\right).$$

Now we give the following definition.

About the limit. An arbitrary set $G$ of a function defined on some set $M$ is called *epynnoi* with respect to the operation $\circ$ if it has the same properties as the system $(g_1, g_2, g_3, g_4)$, that is

1. For any two functions $f \in G, g \in G$, their composition $f \circ g$ also belongs to $G$.
2. The function $e(x) = x$ belongs to $G$.
3. For every function $f \in G$ there is an inverse function $f^{-1}$ which belongs to $G$.

This definition is a special case of the general definition of the concept of a group - one of the most important concepts of modern mathematics. The basic concepts of group theory are presented in detail and popularly in the book by P. S. Aleksandrov “Introduction to Group Theory” (Library «Kvant», issue 7, M.: Nauka, 1980).

We have already seen two examples of function groups. Let's give a few more examples.

a) Set $G$ of linear functions $f(x) = ax + b$, ($a \neq 0, b \in R$);

b) $G = \{x, \frac{1}{1-x}, \frac{x-1}{x}\} \in R\{0, 1\}$;

b) $G = \{x, \frac{1}{1-x}, \frac{x-1}{x}\} \in R\{0, 1\}$;
