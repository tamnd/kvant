---
id: 1991-10-tihomirov-teorema-ferma-eylera-o-dvuh-kvadratah-a400cd4d
issue: kvant_1991_10
year: 1991
number: "10"
title: Fermat–Euler theorem on two squares
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 10, 12
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1e64e28347afa227e6d0fca00247ea35f7734484bfd8a9b456ab84b289b98e5b
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/03_tihomirov-teorema-ferma-eylera-o-dvuh-kvadratah-a400cd4d.md
source_content_sha256: f2c42058d30b0dc8450494c18bf7542f7e4a752c482d237dbd8cea153e034f41
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 10⟧

---
running_head:
folio:
---

Fermat-Euler's theorem
ABOUT TWO SQUARE

Doctor of Physical and Mathematical Sciences
V. TIKHOMIROV

Take a look at the first few prime numbers: 3, 5, 7, 11, 13, 17, 19...
The numbers 5, 13 and 17 can be represented as the sum of two squares:
$$5 = 1^2 + 2^2, 13 = 2^2 + 3^2, 17 = 1^2 + 4^2,$$
and the remaining written numbers (3, 7, 11, 19) cannot be represented in this way. Can any explanation be given for this observation? It turns out that it is possible, namely the following is true:

Theorem. In order for a prime number to be representable as the sum of two squares, it is necessary and sufficient that when divided by even numbers it leaves a remainder of one.
(Indeed, $5 = 4 \cdot 1 + 1, 13 = 4 \cdot 3 + 1, 17 = 4 \cdot 4 + 1,$ whereas $3 = 4 \cdot 0 + 3, 7 = 4 \cdot 1 + 3, 11 = 4 \cdot 2 + 3,$...)

A little history

Who and when first discovered this phenomenon? There is evidence that this result at the end of last year could have added its trispotidestic value. For on Christmas Day 1640 (in a letter dated December 25, 1640), the great Pierre Fermat (1601-1665) informed the famous Mersen, a faithful friend of Descartes and the main intermediary in the correspondence of scientists of his time, that “Every prime number that, when divided by four, gives one, can only be represented as the sum of two squares.”

At that time, mathematical journals did not yet exist; information was exchanged in letters and, as a rule, the results were only announced and not accompanied by proofs.

True, almost 20 years after the letter to Mersenne, in a letter to Carcavi sent in August 1659, Fermat reveals the idea of ​​​​proving the theorem formulated above. He writes that the main idea of ​​the proof is the method of descent, which allows us from the assumption that for some prime number of the form $4n + 1$ the conclusion of the theorem is false, to obtain that it is also false for the changing number, etc., until we get to the number five, when we finally come to a contradiction.

The first proofs were found by Euler (1707–1783) between 1742 and 1747. Moreover, wanting to confirm the priority of Fermat, for whom he had a feeling of deep respect, Euler came up with a proof that corresponds to Fermat’s remark described above. Paying tribute to both great scientists, we call this theorem the Fermat-Euler theorem.

There is a property that is inherent in almost every beautiful mathematical result (as well as in almost every insignificant and beautiful mountain peak): it can be added to in different ways, it can be joked with in different ways, and all paths give pleasure to those who are not afraid to follow them.

I want to demonstrate all this using the example of the Fermat-Euler theorem.

To the top, discovered in the 17th century, we will take three different routes. One of them was discovered in the 18th century, the other in the 19th century, and the third already in the 20th century.

⟦folio none⟧

---
running_head:
folio:
---

that is, applied twice it brings us back. Let's do this again for (1).

Let $x < y - z$, then $x' = 2z + x$, $y' = z$, $z' = y - z$, from which $x' = x + 2z > y' - z' = 2z + x - y$ and, therefore, $B(x'; y'; z')$ must be calculated according to rules (3):

$$x'' = x' - 2y' = x + 2z - 2z = x,$$
$$y'' = x' - y' - z' =$$
$$= x + 2z - z + y - x - z = y,$$
$$z'' = y' = z.$$

And in other cases everything is similar.

Now suppose that $p$ is a prime number of the form $4n + 1$. Then, firstly, the equation $x^2 + 4yz = p$ is solvable in at least two ways: $x = 1$, $y = n$, $z = 1$ or $x = y = 1$, $z = n$. And secondly, this equation has a finite number of solutions. If we assume that among its solutions there are no such solutions for which $y = z$ (after all, if there is such a thing, then there is nothing to prove: $p = x^2 + (2y)^2$), we obtain that the transformation $B$ splits all solutions into pairs $((x; y; z); B(x; y; z))$, unless $(x; y; z) \neq B(x; y; z)$. Let's see whether such pairs exist or, as they say, whether the transformation $B$ has fixed points.

It is very easy to understand by looking at formulas (1)–(3) that the fixed points $y$ $B$ are those for which $x = y$. But for $x = y > 1$ the equation $x^2 + 4yz = p$ has no solutions (since $p$ is not divisible by $y$). This means there is only one fixed point $(1; 1; n)$. From all that has been said, it follows that the number of solutions to the equation $x^2 + 4yz = p$ is odd: the fixed point is $(1; 1; n)$, and the remaining solutions are divided into pairs.

However, there is one more transformation, let's call it $J$, which swaps $y$ and $z$: $J(x; y; z) = (x; z; y)$. It is, of course, also involute. Let's see which triples (from our solutions to the equation $x^2 + 4yz = p$) it leaves in place, i.e., what are those $(x; y; z)$ and $(x; y; z) = (x; z; y)$.

We stipulated earlier that $y \neq z$.

But then there are no fixed points! This means that all solutions are divided into pairs. That is, the number of solutions is even! But we just stated that the number of solutions is odd. It turned out to be a contradiction. This means that there must be a solution to the equation $x^2 + 4yz = p$, where $y = z$, i.e. $p$ is the sum of two squares. The theorem has been proven.

Third proof

The slightly modified Minkowski proof, which we will now discuss, please, is even more imaginative. Unfortunately, it is a little bit non-elementary, namely, it requires knowledge of what an ellipiss is and the formula for the area of ​​an elipiss.

It all starts with one result of Minkowski, which, it would seem, has no special relation to the Fermat-Euler theorem.

Theorem. Let $a, b$ and $c$ be integers, and let $a > 0$ and $ac - b^2 = 1$ be integers. Then there is an integer solution to the equation $ax^2 + 2bxy + cy^2 = 1$.

Proof. Let us take the Cartesian rectangular coordinate of the system on the plane and define in it the scalar product of the formula:

$((x; y); (x'; y')) = axx' + bxy' + bx'y + cyy'$.

This scalar product gives rise to the “distance” from the origin to the point $(x; y)$:

$$d((0; 0), (x; y)) = \sqrt{((x; y), (x; y))} = (ax^2 + 2bxy + cy^2)^{1/2}.$$

⟦folio 12⟧

---
running_head:
folio:
---

from the origin of coordinates to any point of the integer lattice other than the point (0; 0) $(m; n)$ $(m$ and $n$ are integers). Let this distance be equal to $\hat{d}$ and it is achieved at the lattice point $(\hat{m}; \hat{n})$ so that
$$a\hat{m}^2 + 2b\hat{m} + c\hat{n}^2 = \hat{d}^2.$$ (4)

The set of points $(x; y)$ of the plane satisfying the inequality
$$ax^2 + 2bxy + cy^2 \leq \hat{d}^2,$$
is an ellipse. It follows from our construction that if this ellipse is preparing to be compressed twice, and then expands this “compressed” ellipse (parallel to itself) with the center into points of an integer lattice, then all the resulting ellipses, if they intersect, will only be at boundary points.

It is not difficult to understand (see figure) that the area occupied by the intersection of ellipses with a triangle with vertices $(0; 0), (1; 0)$ and $(1; 1)$ is equal to half the area of ​​the entire ellipse. And it - this area - is equal to
$$\frac{\pi \hat{d}^2}{4} \det \binom{a}{b} = \frac{\pi \hat{d}^2}{4} (ac - b^2) = \frac{\pi \hat{d}^2}{4}$$

Our reader Ya. Grozensky, studying the sequence of squares of integers, obtained that
$$x^2 = 2(x - 1)^2 - (x - 2)^2 + 2.$$
Then for cubes he found that
$$x^3 = 3(x - 1)^3 - 3(x - 2)^3 + (x - 3)^3 + 6,$$
and for quadruple powers -
$$x^4 = 4(x - 1)^4 - 6(x - 2)^4 + 4(x - 3)^4 - (x - 4)^4 + 24.$$
In his letter he asks whether there is a general dependence

$$x^n = n(x - 1)^n + A_1(x - 2)^n + \dots + A_k(x - k)^n + \dots + A_n(x - n)^n + n!$$

Such a formula actually exists:
$$x^n - C_1^n(x - 1)^n + C_2^n(x - 2)^n - \dots + (-1)^k C_k^n(x - k)^n + \dots + (-1)^n(x - 1)^n = n!$$
where $C_k^n$ are bioplar coefficients
$$\left( C_k^n = \frac{n!}{k!(n - k)!} \right).$$
Try to prove it.
