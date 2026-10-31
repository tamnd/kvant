---
id: 1973-1-gindikin-zolotaya-teorema-168a18b1
issue: kvant_1973_1
year: 1973
number: "1"
title: Golden Theorem
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 4, 5, 6, 7, 9
tag: ULO8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3ea6068fcba95620a838ec039b2f439c9d73ad6a6fa640fad7645ae52a87ab28
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/03_gindikin-zolotaya-teorema-168a18b1.md
source_content_sha256: 6515880b0f7a449014f9747245d48d98ddee1c0e3dafa3e559527adb65523d64
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Golden Theorem

S. G. Gindikin

“The properties of numbers known today were, for the most part, discovered by observation and discovery long before their truth was confirmed by hard evidence. There are even many properties of numbers with which we are very familiar, but which we are still not able to prove."

L. Euler

We will take an excursion to the origins of modern number theory - a branch of mathematics that studies natural numbers. At that time, mathematicians noticed amazingly simple and beautiful patterns in the world of natural numbers. But often the intuitive simplicity of the formulations turned into an inaccessible solution. Frontal attacks were not successful; we had to come up with workarounds and create a completely new device.

We have discussed here one such problem*), the formulation of which is understandable to a schoolchild who knows what a prime number is. But solving this problem is far from easy, and the great Euler did not immediately manage to take the first step towards its solution. Langgrange and Legendre are trying to prove the hypothesis formulated by Euler (but not proven by him); Nineteen-year-old Gauss managed to do this. This was his second job **).

Gauss called the theorem he proved the “golden theorem.” It talks about what the remainders can be when dividing the squares of integers by prime numbers. We will not present the full formulation of the statement proved by Gauss, postponing this until page 5. Now we will present the formulation of the problem, introduce some terms and consider in detail the special case of the “golden theorem” proved by Euler.

The various conditions necessary for a number to be a square are well known. For example, such a number can only be 0, 1, 4, 5, 6 or 9. Another commonly used property is that the square of an integer is either divisible by 3 or, when divided by 3, leaves a remainder of 1 (proof). The first property can be formulated in the same terms as the second, noting that the last digit is the remainder when divided by 10.

Everywhere below we will propose that $p$ is a prime number, and $p \neq 2$. You can divide integers “with a deficit” or “with an excess.” In other words, residuals can be considered positive or negative. Conditions: select the remainder with the smallest absolute value.

It is not difficult to prove that if $p$ is odd, then every integer $n$ can be uniquely represented in the form

$$n = pq + r, \quad |r| \leq \frac{p-1}{2},$$

where $q$ and $r$ are integers.

⟦folio 4⟧

fixed $p$ our statement is not true).

Further, it is very necessary that 0 and 1 are colors in all constructions. As for the remaining stoltsy, the pattern according to which red numbers appear in them is not immediately visible. Let's start with $a = -1$. It is red at $p = 5, 13, 17, \dots$ and black at $p = 3, 7, 11, \dots$. You may have noticed that the prime numbers of the first group when divided by 4 give a remainder of 1, and the second - a remainder of 1 (note that prime numbers $p \neq 2$ cannot have any other remainders at all). So, we can propose that - 1 is a square residue for primes of the form $p = 4l + 1$ and a square non-residue for $p = 4l - 1$. Fermat (1601-1665) was the first to notice this pattern, but left it without proof. Try to find the proof yourself! You will see that the main difficulty is that it is not clear how to use the simple $p$, and without this sentence the statement becomes false.

The first proof, after several unsuccessful attempts, was found in 1847 by Euler (1707-1783). In 1855, Euler found another, very elegant proof using Fermat's little theorem: If $p$ is a prime number, for every integer $a$, $0 < |a| < p$: $a^{p-1} \equiv 1 \pmod p$. (2)

There are many different proofs of this theorem. However, some of them are given in the ITF. Here we present another proof, similar in concept to other considerations in this article.

Proof. For $p = 2$ the statement is obvious, and we can consider $p$ odd. Let's consider $p$ numbers $0, \pm a, \pm 2a, \pm 3a, \dots, \pm ka; k = \frac{p-1}{2}$. All these numbers when divided by $p$ give different remainders, since otherwise $r_1 a - r_2 a, r_1 > r_2, |r| \leq k, |r_2| \leq k$ is divisible by $p$, but $a$ is not divisible by $p$ and $r_1 - r_2$ is not divisible by $p$, since $0 < r_1 - r_2 < p$. Variables are those of the numbers in question that are different from zero; we get $(-1)^k (k!)^2 a^{p-1}$. Since the remainder of the factor contains all zero residues and taking into account the correct calculation of the remainder of the product, we find that the product has the same residue as $(-1)^k (k!)^2$, that is, $(k!)^2 (a^{p-1} - 1)$ is divided by $p$. Since $k!$ is not divisible by $p$ ($0 < k < p$), then $p$ is divisible by $a^{p-1} - 1$, and the proof is complete.

Corollary (Euler's criterion for the squareness of a residue). Vycem $b \neq 0$ is a square moeda and milk moeda, koeda

$$b^k \equiv 1 \pmod p, \quad k = \frac{p-1}{2}. \quad (3)$$

The proof of condition (3) is easy to establish. If $a^2 \equiv b \pmod p$, $0 < a < p$, then $a^{2k} = a^{p-1}$ and $b^k$ must have the same residues, equal, by virtue of (2), 1. It is enough to seem more complicated. We will derive it from the following lemma, proven in the ITF.

Lemma 1. If $P(x)$ is a polynomial of strategy $l$, $p$ is a prime number, and there are more than $l$ different residues $r$ modulo $p$ for which

$$P(r) \equiv 0 \pmod p, \quad (4)$$

mo (4) holds for all residues.

Let us apply the lemma to the polynomial $P(x) = x^k - 1$. Then correspondence (4) satisfies $k$ non-zero square residues. However, it has a residue $(r = 0)$, which does not satisfy (4); This means, according to the lemma, all square residues must not satisfy (4) and, therefore, condition (3) is sufficient.

Sweeping. For the square non-residue $b$ we have: $b^{\frac{p-1}{2}} \equiv -1 \pmod p$. Indeed, if $b^{\frac{p-1}{2}} \equiv r \pmod p$, then $r^2 \equiv 1 \pmod p$, hence $r = -1$. (The comparison $r^2 \equiv 1 \pmod p$ satisfies only the residue: $r \equiv 1 \pmod p$, $r \equiv -1 \pmod p$).

Euler's criterion allows us to instantly resolve the question of for which $p$ the residue - 1 is square. Substituting $b = -1$ into (3), we find that for $p = 4l + 1$ (3) $(k - \text{четно})$ is satisfied, and for $p = 4l - 1$ (3)

⟦folio 5⟧

not fulfilled ($k$ - odd). The hypothesis formulated above became a theorem.

Problem 1. Prove that if $p \neq 2$ is a prime divisor of the number $n^2 + 1$, then $p = 4l + 1$.

So, we have proven that $-1$ is a square residue for $p = 4l + 1$ and a square non-residue for $p = 4l - 1$.

Let us discuss some features of the proof presented. This statement has two parts: a negative statement for $p = 4l - 1$ and a positive statement for $p = 4l + 1$. In the first case, one naturally tries to find a neokotores property that square residues satisfy, but $-1$ does not, which is what Euler did. The found property turns out to be characteristic, that is, at the same time it was possible to prove the second part of the hypothesis. If you failed to prove this part of the statement yourself, you believe that you were trying to explicitly construct from $p = 4l + 1$ the number $n^2$, which gives a remainder $-1$ when divided by $p$. Euler's proof is ineffective in the sense that it does not provide an explicit construction for the number $n$ by $p$, but only asserts its existence. In other words, it is guaranteed that if we go through the numbers $1,2,...,2l$, square them, take the remainders from dividing the squares by $p$, then sooner or later we will get $-1$. The question remains whether it is possible to indicate a more explicit construction $n$ to $p$ that does not use enumeration procedures. A positive answer was given by Langgange (1736-1813) in 1773, using the following theorem.

Wilson's theorem*). If $p = 2k + 1$ is a prime number, then $(-1)^k (k!)^2 \equiv -1 (\bmod p)$.

To prove this theorem, we will use Lemma 1. Let us set $P(x) = (x^2 - 1)(x^2 - 4) \ldots (x^2 - k^2), Q(x) = x^{2k} - 1$. Then $R(x) = P(x) - Q(x)$ is a polynomial of degree at most $2k - 1$, which at $x = \pm 1, \pm 2, \ldots, \pm k$ is divisible by $p$ ($P$ and $Q$ have this property). By Lemma $R(x) \equiv 0 (\bmod p)$ for all $x$. Actually, the only new factor is that $R(0) \equiv 0 (\bmod p)$. Since $R(0) = (-1)^k (k!)^2 + 1$, we obtain (5).

Lagrange's corollary. For $p = 4l + 1$ we have: $[(2l)!]^2 \equiv -1 (\bmod p)$.

Problem 2. Prove that if (5) is true, then $p$ is a prime number.

This problem gives reason to note that in Lagrange's construction the simplicity $p$ exists.

*) Wilson (1741-1793) - lawyer who studied mathematics at Cambridge.

To find out when $a = -1$ is a square residue, Euler, using enormous numerical material (his table is much larger than the second table above), tries to find similar conditions for the other $a$. He notes that with $a = 2$ everything depends on the remainder when dividing $p$ by 8; 2 turns out to be a square residue for primes $p = 8l \pm 1$ and a non-residue for $p = 8l \pm 3$ (a prime number when divided by 8 can give remainders $\pm 1, \pm 3$). Further, 3 is a square residue at $p = 12l \pm 1$ and a square non-residue at $p = 12l \pm 5$. Euler conjectures that in the general case everything is determined by the remainder of the division of $p$ by 4a.

Euler's hypothesis*). The number a is simultaneously either a square residue or a square non-residue for all prime numbers included in the arithmetic proresection $4aq + r$, $q = 0, 1, 2, \ldots, 0 < r < 4a$.

It is clear that if $4a$ and $r$ have a common divisor $s > 1$, then there will not be a single prime number in arithmetic progression. If the first term and the difference of proresection are co-prime, then, as Dirichlet’s theorem (1805-1859) states, in this proresection there is an infinite number of prime numbers (a generalization of the theorem about the infinity of the number of prime numbers in the natural series).

Let's return to Euler's hypothesis. It turned out that the Euler criterion, which served us well at $a = -1$, failed already at $a = 2$. Euler failed to sort out this case. He managed to prove his hypothesis, not counting $a = -1$, only for $a = 3$. Then Lagrange, who we have already mentioned, proved the conjecture at $a = 2, 5, 7$; Legendre (1752-1833) in 1785 proposed a proof of the conjecture for the general servant, which, however, contained significant problems.

*) Gauss, who proved this conjecture, called it the “golden theorem”.

⟦folio 6⟧

Application

Let us now move on to the second part of our story, from which the most pure readers learned the proof of Euler’s conjecture.

On March 30, 1796, nineteen-year-old Gauss proved the possibility of constructing a regular seventeen-sided triangle with a compass and ruler. From this day Gauss's diary will begin - a chronicle of his amazing discoveries. The second entry in the diary appeared on April 8. It reported that a rigorous proof of the “golden” theorem had been found—that’s what Gauss called Euler’s hypothesis. He rediscovered it while still studying at the Brunswick hypnasium, when the works of Euler, Lagrange, Legendre, whom he became acquainted with only after moving to Göttingen in 1795, were not available to him. First, like his predecessors, he notices the statement for $a=-1$, then, having already smoothed out the result for the general case, he sequentially breaks down case by case, moving further than the others: he considered $a=\pm 2$, $\pm 3$, $\pm 5$, $\pm 7$. Finally, on April 8, 1796, he finds a general proof, which Kronecker (1823-1891) very aptly called “a breakdown of the forces of Gaussian genius.” The proof is carried out by double indication on $a$ and $p$; Gauss comes up with significantly different messages for considering eight (!) different cases. It was necessary to have not only considerable ingenuity, but also amazing courage not to remain on this path. Later, Gauss found six more proofs of the “golden” theorem (now about fifty of them are known). As often happens, after the theorem is proven, it is possible to find proofs much simpler than the original one. We will give here a proof that differs little from Gauss's third proof. It is based on a key lemma proven by Gauss no earlier than 1808.

Lemma 2. Let $p=2k+1$ be a prime number, $a$ an integer, $0<|a| \leq 2k$; $r_1, r_2, \dots, r_k$-calculated numbers $a, 2a, \dots, ka$; $v$ is a negative number

$a^k \equiv (-1)^v (\text{mod } p)$. (6)

Applying Euler's criterion, we obtain the following corollary:

Gaussian criterion for quadratic residue. Vyts are a square mode and a molko mode when the number $v$ in Lemma 2 is valuable.

Proof of Lemma 2. Note that all residues $r_1, \dots, r_k$ are different in absolute value. This follows from the fact that the sum and difference of any two of them is not divisible by $p: r_i \pm r_j = (i \pm j) a$, $i \neq j$; $|i \pm j| < p$, $|a| < p$. Thus, the pattern set $|r_1|, \dots, |r_k|$ is the numbers 1, 2, . . . , $k$ in some order. As a result, the product $a \cdot 2a \dots ka = a^k k!$ when divided by $p$ gives the same remainder as $r_1 \dots r_k = (-1)^v k!$. Considering that $k!$ is not divisible by the prime number $p$, we obtain (6).

Proof of Euler's conjecture. Note that the argument below no longer uses the simplicity of $p$—it is fully used in Gauss’s lemma. Let us mark on the numerical axis the points (Fig. 1, $a, \delta$) $m \frac{p}{2}$ if $a > 0$, and $-m \frac{p}{2}$ if $a < 0$; $m = 0$, $1, 2, \dots, |a|$ - blue dots ($m$ - their numbers). Let us number the intervals with ends at these points according to the numbers of the left ends (in the figures the numbers of the intervals are red). Let us now note $a, 2a, \dots, ka$—the green of the dot; since $a$ is an integer that does not add to $p$, the blue dots cannot coincide.

⟦folio 7⟧

Fig. 2.

with greens, and all the greens of the point will fall into some of the constructed intervals $\left(|a| \frac{p}{2} \geq |a| k\right)$. It is easy to see that the number $v$ appearing in the lemma is the number of green points that fall into intervals with odd numbers (prove!).

Let us now subject our picture to a similarity transformation with a coefficient $\frac{1}{a}$ (Fig. 1 will go into Fig. 2).

In this case, the blue dots will go into points dividing the segment $\left[0, \frac{p}{2}\right]$ into $|a|$ equal parts, and the green dots will go into integer points 1, 2, ..., $k$.

The numbering of intervals will now depend on the sign of $a$: for $a > 0$ they are numbered with the numbers of the left ends, for $a < 0$ - with the numbers of the right ends; $v$ is the number of integer points in intervals with odd numbers. If we increase $p$ by 4l, then exactly 2l integer points will be added to each interval. This follows from the fact that when an interval is shifted by an integer, the number of integer points in it does not change, and on any segment of integer length $n$ or interval of length $n$ with odd endpoints there are exactly $n$ integer points (proof!). So, when changing $p$ to $p + 4ал$ the value $v$ will change to an even number, but $(-1)^v$ will not change. This means that for all $p$ in the arithmetic progression $p = 4aq + r$ the value $(-1)^v$ is the same, and Euler’s conjecture is proven.

At the same time, some way is indicated to find out whether $a$ is a square residue for $p$. You need to take the remainder $r$ from division $p$ by 4a (positive for convenience); divide $\left(0, \frac{r}{2}\right)$ into $|a|$ parts, numbered by their numbers of left (right) ends, if $a$ is positive (negative); count the number $v$ of integer points falling into intervals with odd numbers; $a$ is a square residue if and only if $v$ is even.

Let's do these calculations for $a = 2$ to confirm Euler's observations discussed on page 5. Let $a = 2$; then it is sufficient to consider $r = 1, 3, 5, 7$, since in other cases the arithmetic progression will not contain prime numbers. As can be seen from Fig. 3, the number 2 is a square residue for

$$p = 8q + 1, \quad p = 8q + 7,$$

that is, $p = 8q \pm 1$.

In the right. Show that - 2 is a square residue for $p = 8q + 1, \quad p = 8q + 3$.

The case $a = \pm 3$ is treated similarly. Here are the results of the calculations (table for $v$):

Fig. 3. $r = 1, a = 2, v = 0; r = 3, a = 2, v = 1; r = 5, a = 2, v = 1; r = 7, a = 2, v = 2$.

⟦folio 9⟧

There is a difference between the questions about when $p$ is a square residue modulo $q$ and when $q$ is a square residue modulo $p$.

Proof. Always either $p-q=4a$ or $p+q=4a$.

I case. Let $p-q=4a$, that is, $p$ and $q$ have the same remainders when divided by 4. Then $\left(\frac{p}{q}\right) = \left(\frac{q+4a}{q}\right) = \left(\frac{4a}{q}\right) = \left(\frac{a}{q}\right)$ (we will use (9), (8), and the fact that $\left(\frac{4}{q}\right) = 1$ for all $q$). Next, $\left(\frac{q}{p}\right) = \frac{p-4a}{p} = \left(\frac{-4a}{p}\right) = \left(\frac{-1}{p}\right)\left(\frac{a}{p}\right)$. By virtue of the already proven Euler hypothesis, $\left(\frac{a}{p}\right) = \left(\frac{a}{q}\right)$, that is, $\left(\frac{p}{q}\right) = \left(\frac{q}{p}\right)$ for $\left(\frac{-1}{p}\right) = 1$, and $\frac{p}{q} = -\left(\frac{q}{p}\right)$ for $\left(\frac{-1}{p}\right) = -1$. It remains to remember that $\left(\frac{-1}{p}\right) = 1$ with $p=4l+1$, $\left(\frac{-1}{p}\right) = -1$ with $p=4l+3$.

II case. Let $p+q=4a$, that is, $p$ and $q$ have different remainders when divided by 4. We have $\left(\frac{p}{q}\right) = \left(\frac{4a-q}{q}\right) = \left(\frac{a}{q}\right)$. Same as $\left(\frac{q}{p}\right) = \left(\frac{a}{p}\right)$. By virtue of the complement to Euler's hypothesis, $\left(\frac{a}{q}\right) = \left(\frac{a}{p}\right)$, that is, $\left(\frac{p}{q}\right) = \left(\frac{q}{p}\right)$. The proof is over.

It is easy to see that the above reasoning can be reversed and the Euler hypothesis and its complement can be derived from the square law of reciprocity (do this!). Let us also note that formulas (8)–(10) provide a method for calculating $\left(\frac{p}{q}\right)$ essential that is simpler than the combinatory method described above. Let's illustrate this with an example: $\left(\frac{59}{269}\right) = \left(\frac{269}{59}\right) = -1$,

because
$\left(\frac{3}{59}\right) = -\left(\frac{59}{3}\right) = -\left(\frac{2}{3}\right) = 1$;
$\left(\frac{11}{59}\right) = -\left(\frac{59}{11}\right) = -\left(\frac{4}{11}\right) = -1$.

It is easy to show that the evaluation of the Legendre symbol can always be reduced to the case where $p$ or $q$ equals 2.

Exercise. Count $\left(\frac{37}{557}\right)$, $\left(\frac{43}{991}\right)$.

In conclusion, we note that the problem of quadratic residues served as the starting point for a large and fruitful mathematical activity. Gauss's numerous attempts to obtain new proofs of the quadratic reciprocity law were not primarily dictated by the desire to simplify the proofs. Gauss was haunted by the thought that he had not truly discovered the deep laws that result in the law of reciprocity. This was fully achieved only later, within the framework of the theory of algebraic numbers. Gauss spent a lot of effort generalizing the quadratic law to the cubic and biquadratic cases, obtaining remarkable results. These studies were continued, and the study of various reciprocity laws remained one of the central issues in number theory to this day.
