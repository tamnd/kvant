---
id: 1975-5-matiyasevich-formulyi-dlya-prostyih-chisel-b3a758a3
issue: kvant_1975_5
year: 1975
number: "5"
title: Formulas for prime numbers
authors:
  - Матиясевич Ю. В.
rubric: osnovnye-stati
page_first: 7
page_last: 15
page_labels: 5-13
tag: TTX4
lang: en
source: kvant_digital
extraction: vision
content_sha256: bafb7645b8240f69476570ca7077a0e62c4e920e5cbf087dc942453f28b495e2
prompt_sha256: draft-1
translated_from: content/ru/1975/05/articles/03_matiyasevich-formulyi-dlya-prostyih-chisel-b3a758a3.md
source_content_sha256: ec6cff0c3f6cfd56b0c70b5480dd1d8a7b8b05addf2bed8fd3707f3b60f25d6c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 5⟧

What is required?

Prime numbers are scattered in the natural series in a very whimsical manner, and it is not surprising that the products of mathematicians sought to find a “formula for prime numbers.” In this way, we can name formulas that have different properties, and here it is very important to understand what we actually need.

The simplest formula for prime numbers seems to be:

$$p = p_n,$$

(1)

where $p_n$ denotes the $n$th prime number. Why doesn't this formula establish us? The fact is that the right part of this equality is calculated using the image - try, for example, to find $p_{1975}$ yourself! We want to get a similar formula with the simplest possible way to calculate the right side (however, as we see, ease of calculation is not a very concept at all). This is, so to speak, a maskimut program.

For the sake of simplicity of the formula, one can abandon the requirement of explicit dependence on the number $n$ and look for formulas that give prime numbers, perhaps out of order. Further, you can refuse the desire to specify all prime numbers at once with one formula and demand only that the formula give an infinitely many prime numbers. Finally, it can be assumed that this formula gives, along with infinitely many prime numbers, also non-finite composite numbers. This is a minimum program.

The formulas, which seem to be very simple, may not be the best formulas (1). It is to such examples that we now turn.

Theorema E. M. Wright

In 1947, W. H. Mill published the following result:

There is a real number $\lambda$ such that for any $n=1, 2, \dots$ the number

$$[\lambda^{3^n}]$$

(2)

is simple *).

Subsequently, a number of formulas of the same type appeared. However, these were all results for which the formulation looks tempting and promising, but the proof is disappointing. For anyone who wants to understand why this is so, we suggest looking at the proof of the following theorem by E. M. Wright:

There is a real number $\mu$ such that every number of the form

$$[2^2 \cdot 2^{\mu}]$$

(3)

is simple.

The key point in the proof of Wright's theorem is the so-called Bertrand postulate. According to this postulate, at $x \geq 4$ there is always between $x$ and $2x-2$

*) Here and below [$\alpha$] denotes the integer part of the number $\alpha$, that is, the most integer number does not exceed $\alpha$.

⟦folio 6⟧

prime number. This hypothesis was first expressed by the French mathematician Bertrand: he could not prove it, and therefore used it in his reasoning as an unprovable construction. The proof of Bertrand's conjecture was subsequently found by the outstanding Russian mathematician P. L. Chebyshev *).

To find the required number μ, we first choose a sequence of prime numbers $q_1, q_2, \dots$ such that for any $n=1, 2, \dots$
$$2^q < q_{n+1} < 2^{q+1} - 1. \quad (4)$$
(Any prime number can be taken as $q_1$; an unlimited continuation of the sequence $\{q_n\}$ is possible, subject to inequality (4), which guarantees Bertrand’s construction.)

For brevity, let us denote the number
$$2^2,$$
where we take $n$ exponentiations, through $\exp^n \alpha$, and the inverse function,
$$\log_2 \log_2 \dots \log_2 \beta - \text{через } \log_2^n \beta.$$

Let's try to choose the number μ so that at $n=1, 2, \dots$
$$[\exp^n \mu] = q_n. \quad (5)$$
According to the definition of the integer part of a number, equality (5) is equivalent to the inequality
$$q_n \leqslant \exp^n \mu < q_n + 1.$$

Propagating it $n$ times in base 2, we obtain another double inequality equivalent to (5):
$$\log_2^n q_n \leqslant \mu < \log_2^n (q_n + 1). \quad (6)$$

Check for yourself what follows from (4)
$$\log_2^1 q_1 < \log_2^2 q_2 < \dots < \log_2^n q_n < \log_2^{n+1} q_{n+1} < \dots < \log_2^{n+1} (q_{n+1} + 1) < \log_2^n (q_n + 1) < \dots < \log_2^2 (q_2 + 1) < \log_2^1 (q_1 + 1).$$

So the sequence
$$\log_2^1 q_1, \log_2^2 q_2, \dots, \log_2^n q_n, \dots$$
strictly increases and limited scope; therefore it has a limit. We will take this as the number μ; prove that the chosen μ satisfies an even stronger inequality than (6)
$$\log_2^n q_n < \mu < \log_2^n (q_n + 1), \quad (7)$$
and, therefore, equality (5) is true. Wright's theorem has been proven.

The main disadvantage of formulas (2) and (3) is that they (more precisely, their proofs) do not give any

*) You can read about this proof in the article by M. I. Bashmakov, «Kvant», 1971, No. 5.

method of finding prime numbers, or to calculate any prime number using formulas (2) or (3), the required number λ and μ should be known with sufficient accuracy. Thus, formulas (2) and (3) in some senses are just disguised (and worse) versions of formula (1). In addition, the form of formulas (2) and (3) actually says almost nothing specifically about the set of prime numbers. From the proof of Wright's theorem it is clear that formulas similar to (2), (3) can be specified for any “sufficiently dense” set.

The disadvantages of formulas (2) and (3) arise from the fact that they include real numbers λ and μ, which are specified in some indirect way. In what follows, we will only consider formulas that include only integer coefficients. Such formulas have an important advantage: they can (in principle) be written out explicitly:

Mersenne and Fermat primes
The formulas of Millas, Wright and other similar formulas remained isolated facts that did not lead to new results. However, in other cases, the ability to represent some prime numbers in one or another special form has unexpected and profound consequences.

Let us now consider two formulas that have a compatible simple form:
$$p = 2^n - 1, \quad (8)$$
$$p = 2^n + 1. \quad (9)$$

Obviously, formula (8) does not always give prime numbers; for example, if $n$ is a composite number, $n = kl, k > 1, l > 1$, then $p$ is divisible by $2^k - 1$ and $2^l - 1$. But even with a simple $n$ obtained from formula (8), the number may turn out to be composite:
$$2^{11} - 1 = 2047 = 23 \cdot 89.$$

Prime numbers obtained by formula (8) are called Mersenne numbers in the Marin Mer-

⟦folio 7⟧

Senna, who back in 1664 indicated all prime values ​​of $n$ not exceeding 257, for which, in his opinion, formula (8) gives prime numbers. However, Mersenne did not provide proof; it was later discovered that his prediction was partly wrong.

Interest in Mersenne numbers is caused by their connection with the so-called perfect numbers - numbers equal to the sum of all their divisors, different, of course, from the number itself. Euclid also proved (the proof and you) that if the prime number $p$ has the form indicated in formula (8), then the number $p \cdot (p+1)/2$ is perfect. For example,

$$3 = 2^2 - 1, \quad 7 = 2^3 - 1$$

are prime numbers, and accordingly

$$6 = (3 \cdot 4)/2 = 1 + 2 + 3, \quad 28 = (7 \cdot 8)/2 = 1 + 2 + 4 + 7 + 14$$

- perfect numbers. Several centuries later, Leonhard Euler proved (try his hand here too) that all even perfect numbers have the form indicated by Euclid. Thus, the question of whether the set of four perfect numbers is finite or infinite has been reduced to the question of whether the set of Mersenne primes is finite or infinite, that is, to the question of whether formula (8) implements our minimum program. The answer to this question is still unknown *).

Formula (9) also does not always give prime numbers, for example, if $n$ has a simple odd divisor $m$, then $p$ is divisible by $2^{m/2} + 1$, and if $n$ itself is odd, then $p$ is divisible by 3. Thus, instead of $n$ in formula (9) it makes sense to substitute only 0 and the power of the number 2. For $n=0, 2^0, 2^1, 2^2, 2^3$ and $2^4$ formula (9) indeed gives prime numbers, and Pierre

*) You can read about the history and current state of research on perfect numbers and Mersenne primes in the article by I. Ya. Depman, «Kvant», 1971, No. 8.

Form, who lived in the 17th century, proposed that for any $n$ of the form $2^k$ formula (9) gives a prime number; among them, prime numbers of the form $2^{2k} + 1$ are called Fermat numbers. Fermat's conjecture was refuted by Euler, who pointed out that the number $2^{25} + 1$ is divisible by 641. Currently, several values ​​of $n$ of the form $2^k$ are known, at which composite numbers are obtained using formula (9), but not a single new prime Fermat number has been found, different from those indicated above.

Fermat primes reveal an unexpected connection with geometry. The outstanding German mathematician Carl Friedrich Gauss proved that a regular $p$-gon can be constructed with a cyclel and a ruler for a prime $p$ if and only if $p$ is a Fermat number*). A more general result is this: a regular $m$-gon can be constructed by a cyclel and a straightedge if and only if $m=2^s \cdot p_1p_2 \dots p_l$, where $p_1, p_2, \dots, p_l$ are pairwise distinct Fermat primes.

Ulama tablecloth

Formulas (8) and (9) contain exponentiation. Isn’t it possible to cover the tasks of an infinite multiplicity of tasks only with addition, subtraction and multiplication? Let's look for the answer to this question.

Let's start by considering polynomials in one variable with natural coefficients; Let's see which polynomials will be properties and in what quantity.

Let us first take polynomials of the first degree (that is, linear polynomials). Obviously, the reduced polynomial $x$ defines an infinite number of polynomials, moreover, all prime numbers, but this is an uninteresting case. What can we say about the polynomial $ax + b$ (where $a, b$ and $x$ are natural numbers)? It is clear that if $a$ and $b$ have a common divisor, different

*) This discovery of the then very young Gauss is described in more detail in the article by S. G. Gindikna, «Kvant», 1972, No. 1.

⟦folio 8⟧

Fig. 1.

from 1, then the value of the polynomial $ax + b$ is a composite number that is a multiple of this divisor. The case when $a$ and $b$ are relatively prime is much less appreciated.

The French mathematician Legendre (who lived in the 18th century) hypothesized that if $a$ and $b$ are coprime, then in an arithmetic program with the first term $b$ and the difference $a$ there are infinitely many prime numbers. This hypothesis was proven only last century by the German mathematician Lejeune Dirichlet.

Let us now move on to quadratic polynomials. Among them there are “record holders”, for example, the polynomial $x^2 + x + 41$ - it was studied by Leonard Euler. This polynomial takes prime values ​​at $x = 1,2,...,40$. When $x=41$ its value is composite.

It has been proven that no polynomial (other than a construct, of course) can have only prime numbers as values, but it is still not known whether there is a polynomial (other than a linear one) among whose values ​​there are infinitely many prime numbers.

⟦folio 9⟧

Pris. 2

Pris. 3.

Interest in representing prime numbers as values ​​of quadratic polynomials has recently arisen in connection with a necessary observation by S. M. Ulam*). Having begun to mark prime numbers on a spiral of all natural numbers (Fig. 1), Ulam was surprised to discover that prime numbers were arranged along diagonals, forming quite long chains. (Prove that the numbers located along any diagonal within the limits bounded by figure 1 by the red lines are the values ​​of some quadratic polynomial with integer coefficients). Even more surprising was that this pattern was also observed when the spiral was extended (with the help of a computer) to large numbers - on figure 2 light dots mark prime numbers on the spiral from the first 10,000 numbers. The pattern chosen at figure 2 was called the “Ulam tablecloth”.

For the noted pattern to appear, it is not necessary to start the spiral with a unit. For example, the values ​​of the polynomial $x^2 + x + 41$ line up along the diagonals of the spiral starting with the number 41 (Fig. 3). It is possible that readers of «Kvant», with ingenuity and due patience, will be able to find new red “geometric” patterns for the arrangement of prime numbers among the pluralities of all numbers.

The phenomenon of prime numbers tending to form chains along the diagonals was discovered relatively recently and has not yet received any mathematical explanation.

We will talk about representing prime numbers using polynomials in many variables at the end of the article.

Julia Robinson exponential polynomial

Exponential polynomials differ from ordinary ones in that their exponents can be not only specific natural numbers, but also linear polynomials in variables with natural coefficients, that is, polynomials of the form $a_1x_1 + a_2x_2 + \ldots + a_kx_k + b$, where $a_1, a_2, \ldots, a_k, b$ are non-negative integers.

The simplest examples of exponential polynomials in the variable $n$ are the rules of the part of formulas (8) and (9).

In the future, we will always imagine that all the variables we encounter take on positive integer values.

In 1952, American mathematician Julia Robinson*) published the following result:

*) This is how this observation was made, M. Gardner colorfully tells in “Mathematical Leisure”, M., “Mir”, 1972.

⟦folio 10⟧

There is an exponential polynomial $R(x_0, \dots, x_h)$ such that any positive value of it for positive integer values ​​of the variables is a prime number; Any prime number can be represented in this form.

The result is the following “formula for prime numbers”:

$$p = R(x_0, \dots, x_h).$$

This formula is replaced by this. Firstly, it includes only integers, and therefore, unlike the formulas of Mills, Wright and the like, the Julia Robinson formula can be written out explicitly. Secondly, it specifies all prime numbers, and not just some selected ones, unlike all the formulas discussed above. Thirdly, although formula (10) specifies not only prime numbers, we have a very simple way of filtering out “extra” numbers: each non-prime value $R$ for positive integer values ​​of the unknowns does not exceed zero. In this way, Julia Robinson's formula compares favorably with formulas (8) and (9), as well as with the full-omial formulas just considered *).

Julia Robinson's proof is quite elementary. Its main ideas are outlined below; We leave the task of bringing the proof to formal rigor to the reader: all intermediate results are formulated in the form of five lemmas, and these are the ones that need to be proven. As we will see, these lemmas imply not only the existence of the exponential polynomial $R$, but also its explicit form.

What should we do?

To prove Julia Robinson's theorem, we obviously must specify an exponential polynomial $R$ such that equation (10) is solvable

*) A full formula is a formula given by a polynomial.

in natural numbers with respect to variables $x_0, \dots, x_h$ if and only if the following condition is satisfied:

$$p - \text{простое число.}$$

This is an example of a condition on the variable $p$.

Here are a few more examples of conditions on a set of variables:

$$\lambda_1, \dots, \lambda_n, x_0, \dots, x_h.$$

If we require that the set of numbers (11) satisfy a system of equations of the form

$$F_i(\lambda_1, \dots, \lambda_n, x_0, \dots, x_h) = 0$$

($i=1, \dots, s$), (11'')

or let’s assume a verbal description like: “all $\lambda_i$ are prime numbers,” or “$\lambda_1$ is a prime number, $ax_0, \dots, x_h$ are integers,” etc., then from the set of all sets (11'') we will select some that subordinate conditions to them.

We will not determine exactly what type of conditions are acceptable for us. The given description of examples of equations to determine the method of action that we will use in the future.

In the following presentation, we will distinguish between variables, calling some of them parameters, so the division of variables into parameters and unknowns is purely conditional.

If all the left-hand sides of the system of equation (11'') are exponential polynomials in $\lambda_1, \dots, \lambda_n, x_0, \dots, x_h$, and solutions to this system are sought in positive integers, then such a system is called exponentially Diophantine; if $F_i$ are general polynomials, then the system of equation (11'') is simply called Diophantine.

Equation (10) is an example of an exponential Diophantine equation with respect to the variables $p, x_0, \dots, x_h$.

We will say that two systems of equations having the same parameters are equivalent to another with respect to these parameters if the set of those parameter values ​​for which we have a solution to one of these systems coincides with the set of those parameter values ​​for which we have a solution to the other system. (Note that we are not saying anything in this definition.)

⟦folio 11⟧

It is about the connection between the values ​​of the unknowns—for our purposes this is unimportant; systems that are equivalent in our understanding may not have common unknowns at all.)

An example of equivalent conditions for the parameter $\lambda$ can be the inequality

$$2^n < \lambda < 2^{n+1}$$

and equality

$$\lambda = (2x_0 + 1) \cdot x_1.$$

It is clear that each of these conditions has a solution if and only if the parameter $\lambda$ belongs to the set of numbers that are not integers of power 2.

In this terminology, our goal is formulated as follows: to find an equivalent polynomial $R(x_0, \dots, x_h)$ such that condition (10) is equivalent to condition (11) with respect to the parameter $p$.

However, the requirement that the parameter $p$ appear only on the left side of equality (10) is, as we will now see, unnecessarily strict.

Let satisfying this: find an equivalent polynomial $Q(p, x_1, \dots, x_h)$ such that the Diophantine equation is equivalent (condition on $p, x_1, \dots, x_h$)

$$Q(p, x_1, \dots, x_h) = 0$$

(12) is equivalent to condition (11).

Let's put

$$R(x_0, \dots, x_h) = x_0 \cdot (1 - Q^2(x_0, \dots, x_h)).$$

Lemma 1. If equivalent polynomials $R$ and $Q$ are related by relations (13), then equations (10) and (12) are equivalent with respect to the parameter $p$.

It is enough for us not even to find an equation, but at least a system of equivalent Diophantine equations

$$\begin{cases} Q_1(p, x_1, \dots, x_h) = 0, \\ Q_l(p, x_1, \dots, x_h) = 0, \end{cases}$$

equivalent to condition (11) with respect to $p$.

Lemma 2. If

$$Q(p, x_1, \dots, x_h) = \sum_{i=1}^{l} Q_i^2(p, x_1, \dots, x_h),$$

in system (14) is equivalent to equation (12).

It is the Japanese system of an equivalent Diophantine equation equivalent to condition (11) that we will study.

What is a prime number?

A strange question, the reader will be surprised. Everyone knows that a prime number is a number greater than one that is divisible only by one and itself. Of course, this is true, but such a definition is not easy to work with - after all, it assumes that checking the primality of a number consists of trying out an infinite number of potential divisors - all natural numbers except 1. For our purposes, the following definition is more suitable:

a number $p$ is prime if $p > 1$ and $p$ are not divisible by any number less than $p$ and different from 1.

There is no $q \neq 1$ constraint in this definition, and more importantly, it allows for a variable number of H.O.D equations. (1, $p$) = 1, H.O.D. (2, $p$) = 1, ..., H.O.D. (p - 1, $p$) = 1 reduced to one condition:

H.O.D.((p - 1)!, $p$) = 1.

The remark made allows us to write the first system of equations equivalent to condition (11) with respect to the parameter $p$:

$$\begin{cases} p = r + 1, \\ s = r!, \\ H.O.Д. (s, p) = 1. \end{cases}$$

The first of these conditions has the exclusive form of the equivalent Diophantine (moreover, Diophantine) equation, and the third is easily reduced to the same form by introducing two new unknowns:

*) H.O.D. (a, b) is the most common divisor of the numbers $a$ and $b$.

⟦folio 12⟧

Lemma 3. Condition (17) is equivalent to the relative parameters $r$ and $s$ conditions

$$x_1 \cdot s - x_2 \cdot p = 1^*).$$

Since equation (18) is exponentially Diophantine, we only have to find a system of exponentially Diophantine equations equivalent to the relative parameters $r$ and $s$ of condition (16).

How to calculate factorial?

Conditions (16) include $r!$; It is this factorial that “disturbs” us. Recall that factorial functions in the expression for biomp coefficients**): at $t \geq r$

$$C_t^r = \frac{t(t-1) \dots (t-r+1)}{r!},$$

that is

$$r! = \frac{t(t-1) \dots (t-r+1)}{C_t^r}.$$

The polynomial in the numerator has a rather complex structure. Let's try to replace it with a simpler one—namely, the polynomial $t^r$. For $t \geq r$ we have:

$$\frac{t^r}{C_t^r} = \frac{t^r}{t(t-1) \dots (t-r+1)} \times \frac{t(t-1) \dots (t-r+1)}{C_t^r} = \left(1 + \frac{1}{t-1}\right)\left(1 + \frac{2}{t-2}\right) \times \dots \times \left(1 + \frac{r-1}{t-r+1}\right) \cdot r! \geq r!.$$

It's easy to see that

$$r! = \lim_{t \to \infty} \frac{t^r}{C_t^r},$$

(*) Compare this lemma with Lemma 2 from «Kvant» No. 6 for 1972, p. 33.

**) He did not talk about the properties of biomp coefficients «Kvant»; see, for example, No. 6, 1970, p. 17-25, or No. 2 for 1973, p. 27-34.

however, this recording of the factor does not give us anything, since $t$, being a parameter in the original system of equations, can take any, however many more, but finite values. But we will not proceed to the preposition, but will use the integer value $r!$ - from (19) and (20) it follows that for sufficiently large $t$

$$r! = \left[ \frac{t^r}{C_t^r} \right].$$

Lemma 4. Formula (21) is as true as milk $t \geq 2 r^{r+2}$.

Lemma 4 allows us to transform conditions (16) into an equivalent system with respect to parameters $r$ and $s$ (check the equivalence!)

$$\begin{cases} t = 2r^{r+2}, \\ c = C_t^r, \\ t^r = s \cdot c + (x_3 - 1), \\ (x_3 - 1) + x_4 = c. \end{cases}$$

Here conditions (22), (24) and (25) have the required form, and all we have to do is find a system of exponentially Diophantine equations equivalent to condition (23) with respect to the parameters $r$, $t$ and $c$.

So, all we have to do is “get rid” of the biomp coefficient.

Biome coefficients are biome coefficients!

We have just used the expression of biomp coefficients through factorial; but biomp coefficients have many other definitions. Let us now use that

$$(u + 1)^t = \sum_{i=0}^{t} C_t^i u^i.$$

This formula is the definition of biomp coefficients if considered as a majority with respect to $u$. But we need $u$ to be an unknown that takes only one value as a specific solution to the original system.

⟦folio 13⟧

Note that
$$C_t^i \leq \sum_{i=0}^{t} C_t^i = (1+1)^t = 2^t,$$
and thus if
$$u > 2^t,$$
then $C_t^0, C_t^1, \dots, C_t^t$ are the digits in the notation of the number $(u+1)^t$ in the positional number system with the base $u$.
Consequently, the biomp coefficients are uniquely determined by the condition that equality (26) and inequalities (27) and (28) are simultaneously satisfied for at least one value $u$.

Lemma 5. Condition (23) is equivalent to the relative parameters $r, t$ and $c$ of the condition system
$$\begin{cases} u = 2^t + 1, \\ x_5 = u + 1, \\ x_5^t = x_6 u^{r+1} + cu^r + x_7, \\ x_7 + x_8 = u^r, \\ c + x_9 = u. \end{cases}$$

Here all the conditions already have the form we need.

So, we have shown that conditions (11) are equivalent to the relative parameter $p$ system, consisting of exponential Diophantine equations (15), (18), (22), (24), (25), (29) - (33). To obtain the required exponential polynomial, it remains to change the variables $r, s, t, c$ and $u$ into $x_{10}, x_{11}, x_{12}, x_{13}, x_{14}$, combine all the equations into one by Lemma 2 and transform this equation to use the form (10) by Lemma 1.

Next steps
Formula (10) does not explicitly contain the number of its specified prime number. The method described above for constructing the exponential polynomial $R$ does not provide a direct way to include the prime number in formula (10). Using significantly more complex techniques, Martin Davis, Hilary Putnam, and Julia Robinson in 1961 proved a very powerful theorem that has such consequences.

There is an exponential polynomial $P(x_0, \dots, x_k, n)$ such that for every fixed value of the parameter $n$ and arbitrary values ​​of the other variables, the polynomial $P$ takes one positive value, and this value is the $n$th prime number.

In 1970, the author of this article was able to use other results of Julia Robinson to construct the following Diophantine equation:
$$M(a, b, c, z_1, \dots, z_m) = 0,$$
(34) which is solvable if and only if the parameters $a, b$ and $c$ are related by the relation $a = b^c$. This result allows us to implement the word “exponential” in the formulation of the previous theorem, that is, it allows us to construct a polynomial given prime numbers. However, we will talk about this another time. Those readers who are interested in such topics and who are not afraid of difficulties can try to figure it out on their own in the article by the author “Diophantine Multiplicities”, published in the journal “Success of Mathematical Sciences”, XXVII, No. 5, 1972.

Topics for Thought
1. Prove that the varithmetic progressions are 3, 7, 11, . . . and 5, 11, 17, . . . there are infinitely many prime numbers.
2. What is the set of those polynomials whose values ​​lie along the diagonal if the spiral (see p. 9) starts at 1? from some number $u$? from a certain number $u$, and along the spiral there is a member of the arithmetic progression $u, u + v, u + 2v, \dots$?
3. Wilson's theorem states that if $p$ is a prime number, then $(p-1)! + 1$ is divisible by $p$. How can you use this result to reduce the number of unknowns in the exponential polynomial $R$ given prime numbers?
4. Construct an exponential polynomial $S(x_0, \dots, x_h)$, which defines the set of twin prime numbers, that is, such that if $S(x_0, \dots, x_h) > 0$, then both numbers $S(x_0, \dots, x_h) - 1$ and $S(x_0, \dots, x_h) + 1$ are prime, and vice versa, if $s-1$ and $s+1$ are prime numbers, then $S(x_0, \dots, x_h) = s$ for some $x_0, \dots, x_h$.
5. Construct an exponential polynomial $T(q, x_0, \dots, x_m)$ such that if $q$ is a prime number, then there are numbers $x_0, \dots, x_m$ such that $T(q, x_0, \dots, x_m) > 0$;
if $q$ is a prime number and $T(q, x_0, \dots, x_m) > 0$, then $T(q, x_0, \dots, x_m)$ is the prime number following $q$;
if $q$ is not a prime number, then always $T(q, x_0, \dots, x_m) \leq 0$.

This exponential polynomial gives the "formula for the next prime number".
