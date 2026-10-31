---
id: 1989-5-gornshteyn-trigonometriya-pomogaet-algebre-1acbe271
issue: kvant_1989_5
year: 1989
number: "5"
title: Trigonometry helps algebra
authors:
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 70
page_last: 72
page_labels: 68-70
tag: 3LYN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1aece525da7316874c02c524d9418d7dca9077502a39bcf1b0fb0507d8adfc74
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/15_gornshteyn-trigonometriya-pomogaet-algebre-1acbe271.md
source_content_sha256: 04bb695f633d7528b2f9d576aa9f87905c02ccc4522cccdc152ebd9d97cd9c77
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 68⟧

Trigonometry
helps algebra

P. I. GORNSTEIN

Often, when solving algebraic problems, it is convenient to replace a variable (or variables, if there are several of them) with a trigonometric function and thereby reduce the algebraic problem to a trigonometric one. Such substitutions—trigonometric substitutions—sometimes significantly simplify the solution. The choice of one or another function depends on the type of equation, system of equation or algebraic expression that needs to be simplified. For example, if it follows from the condition that the admissible values ​​of the variable $x$ are determined by the inequality $|x| \leq 1$, then the replacements $x=\sin \alpha$, $\alpha \in \left[-\frac{\pi}{2}; \frac{\pi}{2}\right]$, or $x=\cos \alpha$, $\alpha \in [0; \pi]$ are convenient, and which one to choose depends on the specific problem.

In the case where a variable can take any value, the substitutions $x=\mathrm{tg} \alpha$, $\alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$ and $x=\mathrm{ctg} \alpha$, $\alpha \in (0; \pi)$ are used.

Let's look at a few examples.

Task 1 (LPI, 1976). Solve the equation

$$\sqrt{1-x^2}=4x^3-3x.$$

Solution. In this case $|x| \leq 1$. Putting $x=\cos \alpha$, $\alpha \in [0; \pi]$, we arrive at the equation $$\sqrt{1-\cos^2 \alpha}=4\cos^3 \alpha-3\cos \alpha$$ or $|\sin \alpha|=\cos 3\alpha$, but in our case $\sin \alpha \geq 0$, so $\sin \alpha=\cos 3\alpha$, or

$$\cos 3\alpha-\cos\left(\frac{\pi}{2}-\alpha\right)=0.$$

Solving the last equation, we get

$$\alpha=\frac{\pi}{8}+\frac{\pi k}{2}, k \in Z$$

⟦folio 69⟧

or

$$\alpha = \frac{3}{4} \pi + \pi n, \ n \in \mathbb{Z}.$$

The condition $0 \leqslant \alpha \leqslant \pi$ is satisfied by three values

$$\alpha_1 = \frac{\pi}{8}, \ \alpha_2 = \frac{5\pi}{8} \text{ и } \alpha_3 = \frac{3\pi}{4},$$

therefore

$$x_1 = \cos \frac{\pi}{8} = \sqrt{\frac{1 + \cos \frac{\pi}{4}}{2}} =$$

$$= \sqrt{\frac{1 + \frac{\sqrt{2}}{2}}{2}} = \frac{1}{2} \sqrt{2 + \sqrt{2}};$$

$$x_2 = \cos \frac{5\pi}{8} = -\sqrt{\frac{1 + \cos \frac{5\pi}{4}}{2}} =$$

$$= -\sqrt{\frac{1 - \cos \frac{\pi}{4}}{2}} = -\frac{1}{2} \sqrt{2 - \sqrt{2}};$$

$$x_3 = \cos \frac{3\pi}{4} = -\cos \frac{\pi}{4} = -\frac{\sqrt{2}}{2}.$$

Answer: $\left\{ -\frac{\sqrt{2}}{2}; -\frac{1}{2} \sqrt{2 - \sqrt{2}}; \right.$

$\frac{1}{2} \sqrt{2 + \sqrt{2}}$.

Let's consider a slightly more complex problem.

Task 2 (LPI, 1976). Solve the equation

$$\sqrt{1 - x} = 2x^2 - 1 + 2x\sqrt{1 - x^2}.$$

Solution. And this is the equation $|x| \leqslant 1$. Let, as in the previous example, $x = \cos \alpha$, where $\alpha \in [0; \pi]$. Perform the substitution and given that $\sin \frac{\alpha}{2} \geqslant 0$, $\sin \alpha \geqslant 0$, we obtain the equation

$$\sqrt{2} \sin \frac{\alpha}{2} = \cos 2\alpha + \sin 2\alpha,$$

which is converted to the form

$$\sin \left( \frac{3\alpha}{4} + \frac{\pi}{8} \right) \cos \left( \frac{5\alpha}{4} + \frac{\pi}{8} \right) = 0,$$

from where either $\alpha = -\frac{\pi}{6} + \frac{4\pi k}{3}$, $k \in \mathbb{Z}$, or $\alpha = \frac{3\pi}{10} + \frac{4\pi n}{5}$, $n \in \mathbb{Z}$.

Of the obtained values ​​$\alpha$, only one $\alpha = \frac{3\pi}{10}$ lies in the interval (0; $\pi$). So, $x = \cos \frac{3\pi}{10}$.

The answer can be left in trionometric form, but it can also be expressed in radicals using the formula $\sin 18^\circ = \frac{\sqrt{5} - 1}{4}$, which is derived from the next equality: $\sin 36^\circ = \cos 54^\circ$.

Answer: $\left\{ \cos \frac{3\pi}{10} = \frac{1}{4} \sqrt{10 - 2\sqrt{5}} \right\}$.

An even more complex situation arises in the next problem.

Problem 3 (MSU, Faculty of Biology, 1985). How many roots are there on the segment [0; 1] has the equation

$$8x(1 - 2x^2)(8x^4 - 8x^2 + 1) = 1?$$

Solution. This is an equation of the seventh degree, so attempts to solve it using algebraic methods are hopeless. However, the presence of factors $1 - 2x^2$ suggests the idea of ​​making a trionometric substitution $x = \cos \varphi$, $\varphi \in (0; \pi/2)$ (obviously $x \neq 0$, $x \neq 1$).

Replacing $x$ with $\cos \varphi$ on the left side of this equation, we get

$$8 \cos \varphi(1 - 2 \cos^2 \varphi) \times$$

$$\times (8 \cos^4 \varphi - 8 \cos^2 \varphi + 1) =$$

$$= 8 \cos \varphi(-\cos 2\varphi) \times$$

$$\times (8 \cos^2 \varphi(\cos^2 \varphi - 1) + 1) =$$

$$= -8 \cos \varphi \cos 2\varphi(-2 \sin^2 2\varphi + 1),$$

where

$$-8 \cos \varphi \cos 2\varphi \cos 4\varphi = 1.$$

Now multiply both sides (*) by $\sin \varphi(\varphi \neq 0!)$:

$$-8 \sin \varphi \cos \varphi \cos 2\varphi \cos 4\varphi = \sin \varphi,$$

or

$$-\sin 8\varphi = \sin \varphi,$$

$$\sin 8\varphi + \sin \varphi = 0,$$

$$2 \sin \frac{9}{2} \varphi \cdot \cos \frac{7}{2} \varphi = 0,$$

from where either $\varphi = \frac{2}{9} \pi k$, $k \in \mathbb{Z}$, or $\varphi = \frac{\pi}{7} + \frac{2\pi n}{7}$, $n \in \mathbb{Z}$. From the first series, the interval $(0; \frac{\pi}{2})$ contains two

⟦folio 70⟧

values: $\varphi_1 = \frac{2\pi}{9}, \varphi_2 = \frac{4\pi}{9}$, in the second series there are also two such values: $\varphi_3 = \frac{\pi}{7}, \varphi_4 = \frac{3\pi}{7}$.

Answer: the original equation has on the interval [0; 1]exactly four roots.

Let's give another example with a rather unexpected change of variable of the form $x = \text{tg} \alpha, \alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$.

Problem 4 (GDR Olympics, 1980). Determine all trices of real numbers $(x, y, z)$ that satisfy the system
$$\begin{cases} 2x + x^2y = y, \\ 2y + y^2z = z, \\ 2z + z^2x = x. \end{cases}$$
Solution. It is easy to verify that the system
$$\begin{cases} y = \frac{2x}{1-x^2}, \\ z = \frac{2y}{1-y^2}, \\ x = \frac{2z}{1-z^2} \end{cases}$$ (*)
equal to using the original one.

We know the formula $tg 2\alpha = \frac{2tg \alpha}{1-tg^2 \alpha}$. This suggests performing a trionometric substitution $x = \text{tg} \alpha$, where $\alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$, $\alpha \neq -\frac{\pi}{4}$, $\alpha \neq \frac{\pi}{4}$.

From system (*) we obtain $x = \text{tg} \alpha$, $y = \text{tg} 2\alpha$, $z = \text{tg} 4\alpha$, $x = \text{tg} 8\alpha$.

So, $tg 8\alpha = \text{tg} \alpha$, $tg 8\alpha - \text{tg} \alpha = 0$, $\frac{\sin 7\alpha}{\cos 8\alpha \cos \alpha} = 0$, $\sin 7\alpha = 0$, $\alpha = \frac{\pi n}{7}$, $n \in \mathbb{Z}$.

Determining the sum of digits of a number on a computer
(For the beginning, see p. 66)

Topics of computational experiments

Install on the computer the algorithms described above for calculating the sum of the digits of the number $n$, the sum of the digits of all numbers from 1 to $n$ by the addition method and the calculation method using the formulas $fk(n)$. Test them for school textbook page numbers. Determine $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$ in each case.

The check shows that for $n \in \{-3; -2; -1; 0; 1; 2; 3\}$ the resulting 7 sets of numbers are different and indeed satisfy the original system.

Of course, all the previously discussed examples are artificial and, as it were, specially selected for applicants and participants of competitions.

In conclusion, we recommend that you solve the following exercises on your own.

Exercise
1. (POI, 1976). Solve the equation
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. Solve the equation
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. (MSU, Faculty of Economics, 1981). Find all solutions to the equation
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. (Leningrad Olympics, 1985). Solve the system of equations
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. (MSU, Faculty of Biology, 1985). How many roots are there on the segment [0; 1] has the equation
$$8x(2x^2 - 1)(8x^4 - 8x^2 + 1) = 1?$$
6. (MSU, Faculty of Economics, 1985). Among all solutions $(x, y, z, v)$ system
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
find those for which the expression $x + z$ takes on the most meaning.

Determining the sum of digits of a number on a computer
(For the beginning, see p. 66)

Topics of computational experiments

Install on the computer the algorithms described above for calculating the sum of the digits of the number $n$, the sum of the digits of all numbers from 1 to $n$ by the addition method and the calculation method using the formulas $fk(n)$. Test them for school textbook page numbers. Determine $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$ in each case.

The check shows that for $n \in \{-3; -2; -1; 0; 1; 2; 3\}$ the resulting 7 sets of numbers are different and indeed satisfy the original system.

Of course, all the previously discussed examples are artificial and, as it were, specially selected for applicants and participants of competitions.

In conclusion, we recommend that you solve the following exercises on your own.

Exercise
1. (POI, 1976). Solve the equation
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. Solve the equation
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. (MSU, Faculty of Economics, 1981). Find all solutions to the equation
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. (Leningrad Olympics, 1985). Solve the system of equations
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. (MSU, Faculty of Economics, 1985). Among all solutions $(x, y, z, v)$ system
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
find those for which the expression $x + z$ takes on the most meaning.

Determining the sum of digits of a number on a computer
(For the beginning, see p. 66)

Topics of computational experiments

Install on the computer the algorithms described above for calculating the sum of the digits of the number $n$, the sum of the digits of all numbers from 1 to $n$ by the method of addition and the method of calculation by formulas $fk(n)$. Test them for school textbook page numbers. Determine $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$ in each case.

The check shows that for $n \in \{-3; -2; -1; 0; 1; 2; 3\}$ the resulting 7 sets of numbers are different and indeed satisfy the original system.

Of course, all the previously discussed examples are artificial and, as it were, specially selected for applicants and participants of competitions.

In conclusion, we recommend that you solve the following exercises on your own.

Exercise
1. (POI, 1976). Solve the equation
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. Solve the equation
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. (MSU, Faculty of Economics, 1981). Find all solutions to the equation
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. (Leningrad Olympics, 1985). Solve the system of equations
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. (MSU, Faculty of Economics, 1985). Among all solutions $(x, y, z, v)$ system
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
find those for which the expression $x + z$ takes on the most meaning.
