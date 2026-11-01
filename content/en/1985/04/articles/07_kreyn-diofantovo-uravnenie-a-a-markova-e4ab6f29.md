---
id: 1985-4-kreyn-diofantovo-uravnenie-a-a-markova-e4ab6f29
issue: kvant_1985_4
year: 1985
number: "4"
title: Diophantine equation of A. A. Markov
authors:
  - Крейн М. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 15
page_last: 18
page_labels: 13-16
tag: ZV53
lang: en
source: kvant_digital
extraction: vision
content_sha256: c1d5d215f9a00d62f77e80ad20fc43a10f1210156fd7a6b35b70adfb5cba71a8
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/07_kreyn-diofantovo-uravnenie-a-a-markova-e4ab6f29.md
source_content_sha256: 8a14d7184dc4f8ed2f7488d25436257a3fbbe05c5ae92d1af5a72537d0047f62
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

Diophantine equation
A. A. Markova

Corresponding Member of the USSR Academy of Sciences M. G. KREIN

This article tells the story of one equation in even numbers and provides its solution. The solution uses only the simplest properties of numbers and Vieta's theorem for the square trinomial, and therefore it is possible to use the mathematical round one. It is based on a number of “proof” problems, the analysis of which we will form the subject of a mathematical lesson. (Detailed evidence can be found at the end of the next issue of the magazine.)

In 1879, at St. Petersburg University, a 23-year-old young man completed his master’s thesis entitled “On binary square forms of the positive determinant.” It solved the most difficult questions in number theory and defined a new direction in this theory. Its author was the future famous academician Andrei Andreevich Markov (1856-1922).

The dissertation was based on two of his articles published in Germany in 1879 and 1880 in one of the most famous mathematical journals in the world - "Mathematische Annalen". Despite this, more than 30 years passed before Markov’s work was “discovered” in the West. In 1913, the great German mathematician Georg Frobenius (1849–1917) published a topic entitled “On Markov Numbers.” In the preface to it, he wrote that questions about the fact that A. A. Markov’s research is “extremely replaceable and important”, they apparently remained little known. G. Frobenius explained the complexity of their presentation (A. A. Markov systematically used the apparatus of continued fractions, which was unpopular for that time in these matters)*.

Of course, this article does not aim to give at least some idea of ​​the global research of A. A. Markov. But the fact is that in his constructions A. A. Markov unexpectedly came to an auxiliary Diophantine equation (now called we have it), which has the form

$$x^2 + y^2 + z^2 = 3xyz.$$

And now - a sensation! A. A. Markov obtained a description of all solutions to equation (1), using only the means of school mathematics (among them, Vieta’s theorem for the quadratic trinomial played a role). But before analyzing the solution to equation (1), it is worth saying a few words in general:

About Diophantine equations

As is known, a Diophantine equation for integer variables $x, y, ..., w$ is an equation that can be reduced to the form

$$P(x, y, ..., w) = 0,$$

where $P$ is some polynomial in the indicated variables with integer coefficients.

Sometimes relatively simple questions lead to Diophantine equations. For example, solving the question of how an amount of $n$ kopecks can be divided into coins in denominations of 1, 2, 3 and 5 kopecks, we arrive at the Diophantine equation:

$$x + 2y + 3z + 5w = n^*$$.

Apparently, back in Ancient Babylon, the problem of constructing a right triangle with pairwise proportionate sides was born. The commensurability of the sides means that one will find a scale in which the catemts and hypotenuse will be expressed by the natural numbers $x, y$ and $z$, but then

$$*) О непрерывных (или целых) дробях можно прочитать в «Кванте», 1983, № 5, c. 16 и № 6, c. 26.
**) О решении этого уравнения см. «Кванте», 1984, № 5, c. 11.$$

⟦folio 14⟧

$$x^2 + y^2 = z^2.$$

Thus, the Babylonian problem consists of constructing all triples of natural numbers $x, y, z$ satisfying the previous equation. The Pythagoreans found a way to construct all its solutions. But perhaps this method was found even earlier in Babylon and India. One way or another, solutions $(x, y, z)$ of equation $x^2 + y^2 = z^2$ are usually called *Pythagorean triples*).

The problem of finding all the solutions to even a seemingly simple Diophantine equation is usually difficult. It is known that there is no uniform way (general algorithm) for finding out even whether a Diophantine equation has a solution in integers or not**). The search for solutions to specific Diophantine equations continues to this day; here, with the help of the complex apparatus of modern algebraic geometry, significant conditions have been available in recent years ***). However, what is more interesting to us is that Markov’s equation (1) is solved in an elementary way - let’s return to it.

**Family tree of the Markov equation**

An ordered triple of integers $(a, b, c)$ is called a *solution of a Diophantine equation with variables $x, y, z$ if this equation becomes a true numerical equality as $x=a, y=b, z=c$. The numbers $a, b, c$ of the solution $(a, b, c)$ will be called *coordinates* of the solution. For the Markov equation (1), we agree to consider only those solutions that do not have zero coordinates, in other words, we will exclude the triple $(0, 0, 0)$ from the solutions (it is easy to see that if one of the coordinates of the solution to equation (1) is zero, then the remaining coordinates of the solution are equal to zero).

The left-hand side of (1) is positive for any solution $(a, b, c)$, so either all $a, b, c$ are positive or two

*) On Pythagorean triplets and on the solution of some other Diophantine equations, see: A. O. Gelfond. Solving Equations in Integers, 4th Ed. - M.: Nauka, 1973. O. Ore. Invitation to number theory. - M.: Nauka, 1980. - (Series: Library *Quantum*).
**) See *Kvant*, 1970, No. 7, p. 39.
***) See *Kvant*, 1983, No. 3, p. 19.

of which are negative. In the latter case, the transition from $(a, b, c)$ to $(|a|, |b|, |c|)$ leads to the solution of equation (1) with positive coordinates. Conversely, if all coordinates of the solution $(a, b, c)$ are positive, then by changing the sign of any two coordinates, we will again obtain a solution. Therefore, in what follows, without loss of generality, we will consider only solutions $(a, b, c)$ with positive coordinates.

From the symmetric equation (1) it follows that if $(a, b, c)$ is a solution to equation (1), then the solutions will be:

$$(a, b, c), (c, a, b), (b, c, a),$$
$$(b, a, c), (a, c, b), (c, b, a),$$

that is, together with the $(a, b, c)$ solutions there will be all triples obtained by various permutations of the coordinates of a given solution.

In view of this, we can agree that all six solutions of the Markov equation, obtained from each other by permutations, are considered one solution, that is, we assume that for the solution of existence there are only values ​​of the coordinates, and not their order.

The Markov equation has an obvious solution (1, 1, 1). Now we will find out how, knowing a solution, we can find other solutions. If $(a, b, c)$ is a solution to the Markov equation, then we can say that a is the root of the quadratic equation

$$\Phi_a(x) = x^2 + b^2 + c^2 - 3bcx = 0.$$

But according to Vieta’s theorem, this equation will have one more root $x=a'$, such that

$$a + a' = 3bc, \quad aa' = b^2 + c^2.$$

Obviously, $a' > 0$ and $(a', b, c)$ are also solutions to equation (1). It is called *neighboring solution along coordinate a*. Obviously, if $(a', b, c)$ is a neighboring solution for $(a, b, c)$, then $(a, b, c)$ is a neighboring solution for $(a', b, c)$ along the coordinate $a'$.

Solutions that are adjacent in coordinate 1 to solutions $(1, 1, 1)$ are introduced similarly. To do this you need to solve the quadratic equation

⟦folio 15⟧

$$x^2 + 1^2 + 1^2 - 3 \cdot 1 \cdot 1 \cdot x = 0.$$

In addition to the root $x=1$, this equation also has a root $x=2$. Thus, another solution (2, 1, 1) is obtained.
In what follows, the solution (1, 1, 1) and (2, 1, 1) will play a significant role. Let us call them, following Markov, singular.

Singular solutions are distinguished from the set of all solutions by the following property.

Problem 1. If the solution $(a, b, c)$ of the Markov equation has two equal coordinates, then in this and only this case the solution is singular. Prove it.

The first singular solution (1, 1, 1) has only one neighboring solution. The second singular solution has two neighboring ones: one of them is (1, 1, 1), the other (neighboring along coordinate 1) is obtained from the equation

$$2^2 + y^2 + 1^2 = 3 \cdot 2 \cdot y \cdot 1$$

and has the form (2, 5, 1). In turn, the solution (2, 5, 1) has three neighbors: one, naturally (2, 1, 1) and two new ones - (13, 5, 1) and (2, 5, 29). In general, every non-singular solution $(a, b, c)$ generates three neighboring

$$(a', b, c), (a, b', c), (a, b, c')$$

where (compare with (2))

$$a' = 3bc - a, b' = 3ac - b, c' = 3ab - c.$$

Problem 2. If the solution $(a, b, c)$ is nonsingular, then one of its neighboring solutions has a smaller maximum coordinate, and the other two have a larger one. Prove it.

Markov's theorem. Any solution to equation (1) is contained by an integer of neighboring solutions with a singular solution (1, 1, 1).

Proof. Let $(a, b, c)$ be a non-singular solution to the Markov equation. Then it has a neighboring solution $(a_1, b_1, c_1)$ with a smaller maximum coordinate (Problem 2). If this solution is also nonsingular, then it generates a solution $(a_2, b_2, c_2)$ with a smaller maximum coordinate, and so on. Since it is impossible to designate an infinite decreasing sequence of natural numbers, this process must end when we come to some solution $(a_n, b_n, c_n)$, which has equal coordinates, that is (problem 1) to a singular one. If it is (1, 1, 1), then the theorem is proven, but if this solution is (2, 1, 1), then it remains to remember that the neighboring solution for (2, 1, 1) along coordinate 2 will be (1, 1, 1). The theorem has been proven.

From Markov's theorem it follows that, starting from the singular solution (1, 1, 1), and successively moving to neighboring solutions with a large maximum of coordinates, we obtain all solutions to the Markov equation. This produces the following table - a family tree (see figure). This table allows, for a given $N (\geqslant 1)$ finite number of actions, to find all solutions of the Markov equation whose coordinates do not exceed $N$.

Problem 3. Prove that each solution of the Markov equation has pairwise coprime coordinates.

Exceptional Markov equation

Let us pose the following question, which, at first glance, may seem to countries. If the sum of the squares of three natural numbers is divided by their product, then what can the quotient be?

This question is equivalent to the following: for what natural $k$ Diophantines does the equation

$$X^2 + Y^2 + Z^2 = kXYZ$$

(3)

⟦folio 16⟧

has a non-zero solution? For $k=3$ this equation coincides with the Markov equation. It is easy to see that for $k=1$ equation (3) has a solution, for example (3, 3, 3). After analyzing equation (3), Hurwitz and Frobenus came to a striking result: equation (3) has a solution only for $k=3$ and $k=1$. This result can also be obtained by elementary means.

Let's start with case $k=1$. In this case, it turns out that finding a solution to equation (3) for $k=1$ coincides with finding a solution to the Markov equation.

Problem 4. Let $A, B, C$ be natural numbers. Then the remainder of dividing the number $A^2+B^2+C^2$ by 3 is equal to the number of Wednesday numbers $A, B, C$ not divisible by 3, if there are less than three of them, and is equal to zero otherwise. Prove it.

Problem 5. All solutions of the $(A, B, C)$ equation

$$X^2+Y^2+Z^2=XYZ$$

are obtained by formulas

$$A=3a, B=3b, C=3c,$$

where $(a, b, c)$ is an arbitrary solution to the Markov equation

$$x^2+y^2+z^2=3xyz.$$

Prove it.

Let us turn to case $k=2$.

Problem 6. Let $A, B, C$ be natural numbers. Then the remainder of dividing the number $A^2+B^2+C^2$ by 4 is equal to the number of non-dividing numbers of the medium $A, B, C$. Prove it.

Problem 7. Prove that equation (3) has no solution for $k=2$.

Theorem. Equation (3) has a non-zero solution only for $k=1$ and $k=3$.

Proof. For $k=1$ the solution is found in accordance with problem 5. For $k=2$ equation (3) has no solution due to problem 7. It remains to consider the case $k>3$.

Let us assume that for some $k>3$ equation (3) has a solution $(a, b, c)$. Let us show that the coordinates $a, b, c$ of this solution are pairwise different. Let, for example, $b=c$; then $a^2=kab^2-2b^2=(ka-2)b^2$, so $a=bd$, where $d$ is an integer. Hence $b^2d^2=(kbd-2)b^2$, $d^2=kbd-2$, $2=d(kb-d)$. Thus, 2 is divisible by $d$ and, therefore, $d=1$ or 2. In both cases, $kb=3$, which contradicts the condition $k>3$.

So, any solution to equation (3) with $k>3$ has pairwise different coordinates. Without limitation, we can generally assume that $a>b>c$. To solve $(a, b, c)$ using the quadratic trinomial

$$\Psi_a(x)=x^2+b^2+c^2-kxbc$$

forms a solution $(a', b, c)$ neighboring along the coordinate $a$. Because

$$\Psi_a(b)=2b^2+c^2-kb^2c<3b^2-kb^2<0,$$

we see that $b$ lies between the roots $a$ and $a'$ of the polynomial $\Psi_a(x)$, that is, $a>b>a'$. Therefore, solution $(a', b, c)$ has a maximum coordinate less than the maximum coordinate of solution $(a, b, c)$. So, for each solution $(a, b, c)$ we can construct a solution $(a_1, b_1, c_1)$ with a smaller maximum coordinate. This construction can be repeated, obtaining a solution $(a_2, b_2, c_2)$ with an even smaller maximum coordinate. Since each solution has pairwise different coordinates, this process can be continued indefinitely and obtain an infinite sequence of solutions to equation (3) with smaller and smaller maximum coordinates. But this is impossible, since the coordinates are natural numbers. The theorem has been proven.

Consequence. For any solution $(a, b, c)$ of the Markov equation, the numbers $a, b, c$ are pairwise coprime.

Proof. If, for example, $a$ and $b$ have a common divisor $d$ ($>1$), then by virtue of equation (1), the number $d$ will also be a divisor of the number $c$. Consequently, there are natural numbers $X, Y, Z$ that also equal $a=dX, b=dY, c=dZ$, and by (1) will have $X^2+Y^2+Z^2=3dXYZ$, and this contradicts the theorem just proved.

A direct generalization of the Markov equation to the case of $n$ variables ($n \geqslant 3$) is the equation

$$x_1^2+x_2^2+\dots+x_n^2=nx_1x_2\dots x_n.$$

It is easy to see that a number of the stated propositions carry over to this case (there is a singular solution $x_1=1, x_2=1, \dots, x_n=1$, for every solution there are neighboring solutions, etc.). However, the author is not aware that a complete substation theory of equation (7) has been presented anywhere. The search for such a theory could become the basis of a small independent study.
