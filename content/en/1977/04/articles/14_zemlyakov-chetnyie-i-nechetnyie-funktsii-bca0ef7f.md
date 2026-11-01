---
id: 1977-4-zemlyakov-chetnyie-i-nechetnyie-funktsii-bca0ef7f
issue: kvant_1977_4
year: 1977
number: "4"
title: Even and odd functions
authors:
  - Земляков А. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 40
page_last: 43
page_labels: 38-41
tag: 6MLD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8e964256100dcc9221ff0901285d45e06d8961ddb6a34293301f38e218a36344
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/14_zemlyakov-chetnyie-i-nechetnyie-funktsii-bca0ef7f.md
source_content_sha256: ac5ba11609923767434a15873956b72bfe681aa6e6ecdd89af13773fc6dd8062
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Even and odd functions

"Connected to the world,
Eternally clear
Even and odd attracts us"
K. Balmont

This article is addressed to ninth-graders and is an illustration and addition to paragraph 68 of the textbook “Algebra and the beginnings of analysis 9”.

Even functions

Recall that a numerical function $f$ is called integer if the following two conditions are met:

(C) if $x \in D(f)$, then $u - x \in D(f)$, that is, the domain of definition $D(f)$ of the function $f$ symmetrine with respect to the point $0$ on the coordinate line $Ox$;

(H) $f(-x) = f(x)$ for any $x \in D(f)$, that is, at symmetrical (relative to the point $0$ on the axis $Ox$) points $x$ and $-x$ the function $f$ takes the same values.

Examples of four functions: constructive $c$ ($y = c$ for any $x \in \mathbb{R}$), $x^2$, cos $x$.

The graph of the fourth function on the coordinate plane $Oxy$ is symmetrical about the ordinat axis. It is proven this way. If the point $M$ with coordinates $(x_0; y_0)$ belongs to the graph of the function $f$ (Fig. 1), that is, $f(x_0) = y_0$, then, by the definition of the fourth function, $-x_0 \in D(f)$ and $f(-x_0) = y_0$, and then the point $M'$ with coordinates $(-x_0; y_0)$ belongs to the graph of the function $f$. But point $M'$ is just symmetrical to point $M$ relative to axis $Oy$. Thus, along with any point $M$, the graph of the fourth function $f$ also contains the point $M'$, which means that this graph is symmetrical with respect to the ordinat axis.

Even functions

The function $f$ is called odd if the symmetry condition (C) is satisfied (see above) and the following condition of the four functions is also an odd function (prove this yourself).

Odd functions

The function $f$ is called odd if the symmetry condition (C) is satisfied (see above) and the following condition of the four functions is also an odd function (prove this yourself).

It is easy to see that the sum and difference of two odd functions, as well as

⟦folio 39⟧

The product of an odd function and a number are odd functions.

Control questions

1. Is the product of two odd functions even or odd?
2. What function is the product of an even and an odd function?

Neither even nor odd functions

Note that “odd function” is not the same as “odd function” (that is, a function that is not even). As a rule, a function “taken at random” will be neither even nor odd: the graph of an “arbitrary” function is not required to have any symmetry properties.

Example 1. The function $f(x) = \frac{1}{(x+1)}$ is neither even nor odd, since its domain $D(f) = \{x | x \neq -1\}$ does not satisfy the symmetry condition (C): the point $x_0 = 1$ belongs to $D(f)$, and the point $-x_0 = -1$ does not belong to $D(f)$.

Example 2. The function $f(x) = x^2 + x + 1$ is also neither even nor odd. This function is determined by force, and therefore the symmetry condition (C) is satisfied for it, but neither the condition (H) nor the condition (H) is satisfied. Indeed, $f(-x) = x^2 - x + 1$. Putting $x = 1$, we find $f(1) = 1 + 1 + 1 = 3$, $f(-1) = 1 - 1 + 1 = 1$, and $f(-1)$ is not equal to either $f(1)$ or $-f(1)$.

Note also e. The reference to the fact that the expressions for $f(x)$ and $f(-x)$ are “different”, therefore “$f(-x) \neq f(x)$” does not otherwise prove: firstly, expressions completely different in appearance can define the same function; secondly, the assumption “$f(-x) \neq f(x)$” contains the variable $x$, and its truth or falsity depends on the value of $x$ (for example, in the example under consideration at $x = 0$ it is just $f(-x) = f(x)$). Condition (H) for the parity of a function lies in the truth of the statement “for any $x \in D(f)$ the numerical equality $f(-x) = f(x)$” is satisfied, and the statement that condition (H) is not satisfied lies in the truth of the statement, which is the negation of the previous one:

“there is $x \in D(f)$ the numerical equality $f(-x) = f(x)$ is satisfied”, and the statement that condition (H) is not satisfied lies in the truth of the statement, which is the negation of the previous one:

“there is $x \in D(f)$ the numerical equality $f(-x) = f(x)$ is satisfied”, and the statement that condition (H) is not satisfied lies in the truth of the statement, which is the negation of the previous one:

The question arises: why introduce the concepts of even and odd of a function if the “majority” of the function is neither even nor odd? This is what we will explain now.

Physical example

If a physical system has some kind of symmetry, then the functions associated with it often have certain symmetry properties. In the simplest cases, just even or odd functions arise.

Example. On the horizontal rod - axis $Ox$ - there is a single-pod spring, the ends of which are fixed at symmetrical points $x = -d$ and $x = d$, and a washer is attached to the middle of the spring - at point $x = 0$, which moves freely (without friction) along the rod (Fig. 3, a). Let the puck be moved to a point with coordinate $x$. Let us denote by $F(x)$ the magnitude of the force acting on the washer from the side of the spring (more precisely, the projection of this force on the axis $Ox$), and by $U(x)$ the potential energy of the washer in this position. Obviously, the spring does not care whether the washer is retracted to the right or left: the absolute magnitude of the force and potential energy during displacement $x$ and $-x$ are the same, that is

$$|F(-x)| = |F(x)|$$

And

$$U(-x) = U(x).$$

Considering that the force in positions $x$ and $-x$ is directed in opposite directions (see Fig. 3, b, b), we can write

$$F(-x) = -F(x).$$

Thus, from symmetrine considerations alone we obtain the following:

⟦folio 40⟧

1) function $F(x)$, expressing the dependence of force $F$ on mixing $x$, odd;
2) the function $U(x)$, expressing the dependence of potential energy on mixing, is odd.

Mathematical example
Obviously, the power function $f(x) = x^n$, where $n \in \mathbb{N}$, will be even if $n$ is even, and odd if $n$ is odd (in fact, this is where this terminology comes from). An arbitrary polynomial $p(x)$, generally speaking, will be neither an even nor an odd function *). However, it can be represented as the sum of two polynomials $p_+(x)$ and $p_-(x)$, which are the corresponding even and odd functions. For example,

$$p(x) = x^7 + 2x^6 - x^5 - 3x^4 - 13x^2 + x + 17 = p_+(x) + p_-(x),$$

where $p_+(x) = 2x^6 - 3x^4 - 13x^2 + 17$ is the sum of monomials from $p(x)$ containing $x$ to an even power, and $p_-(x) = x^7 - x^5 + x$ is the sum of monomials from $p(x)$ containing $x$ to an odd power.

It turns out that not only a polynomial, but also any function with a symmetric domain of definition can be represented as the sum of an even and odd function!

Theorem
If the function $f$ satisfies the symmetry condition (C), then it can be represented as the sum of two functions - even $f_+(x)$ and odd $f_-(x)$:

$$f(x) = f_+(x) + f_-(x),$$

(1) the domains of definition of composite elements that the function $f$: $D(f_+) = D(f_-) = D(f)$, and this representation is unique.

Proof. Let us assume that the function $f(x)$ is already represented in the form (1) and the functions $f_+$ and $f_-$ satisfy the corresponding

$$f_+(-x) = f_+(x),$$
$$f_-(-x) = -f_-(x).$$

(*) Here and below we consider polynomials in one variable $x$, and we identify the polynomial $p(x)$ with the function $x \rightarrow p(x)$.

Substituting the values ​​$-x$ into formula (1) instead of $x$, from formulas (2) we obtain

$$f(-x) = f_+(x) - f_-(x).$$

(3)

Adding equalities (1) and (3), we obtain

$$f(x) + f(-x) = 2f_+(x),$$

where

$$f_+(x) = \frac{f(x) + f(-x)}{2}.$$

(4a)

Similarly, subtracting (3) from (1), we find

$$f_-(x) = \frac{f(x) - f(-x)}{2}.$$

(46)

Thus, if the function $f$ is representable in the form (1), then the functions $f_+$ and $f_-$ are uniquely found from the function $f$ - using formulas (4). Therefore, if representation (1) exists, then it is unique.

And now - a small trio: for an arbitrary function $f$ he defined the functions $f_+$ and $f_-$ corresponding to (4).

Then from formulas (4) it follows that, firstly, $f_+(x) + f_-(x) = f(x)$, that is, (1) is satisfied, and, secondly, that the functions $f_+$ and $f_-$ are corresponding, even and odd. For example, let's check condition (H) for the function $f_-$. For arbitrary $x$ we have

$$f_-(-x) = \frac{f(-x) - f(-x)}{2} =$$

$$= \frac{f(x) - f(-x)}{2} =$$

$$= -f_-(x),$$

Q.E.D. The parity of the function $f_+$ is checked in the same way.

Sweeping. The above proof is, as we say, constructive in nature: we not only proved the existence and uniqueness of representation (1), but also indicated formulas (4), by which one can find the even and odd “parts” of a given function.

Control questions

3. Where in the proof is the symmetry assumption $D(f)$ used?

4. According to our theorem, any function with a symmetric domain of definition, including any even (or odd) function, is represented as the sum of its even and odd parts. Find the functions $f_+$ and $f_-$ if

a) $f$-even function;
b) $f$ is an odd function.

⟦folio 41⟧

5. In the “mathematical example” we expanded a certain polynomial $p(x)$ into the sum of an even and odd function, “collecting” into one function all one-year ones containing $x$ to an even power, and into another function - one-year ones containing $x$ to an even power.

Derive this expansion using formulas (4).

6. Prove that if some polynomial is
a) an even function, then it contains one-year ones only with even powers $x$;
6) odd function, then it contains one-year ones only with odd powers $x$.

Exercises

1. Given 11 functions: $f_1(x) = \sqrt{x^2-1}$, $f_2(x) = \sqrt{x+1}$, $f_3(x) = \frac{x^2+1}{x^2-1}$, $f_4(x) = x^2 + \sin x$, $f_5(x) = x^2 \cdot 2^x$, $f_6(x) = x^3 + x^4 - x^2$, $f_7(x) = x^3 + \cos x$, $f_8(x) = x^3 + \mathrm{tg} x$, $f_9(x) = x^3 \cdot \sin x$, $f_{10}(x) = \frac{2^x-1}{2^x+1}$, $f_{11}(x) = \lg(x + \sqrt{x^2+1})$.

Determine which of these functions are even, which are odd, and which are neither even nor odd (then represent them as the sum of an even and an odd function). Give relevant evidence. (When justifying certain properties of parity, do not forget about the replacement after Example 2!)

2. Find all even and all odd functions of the environment:
a) linear functions
$f(x) = ax + b$;
6) square functions
$f(x) = ax^2 + bx + c$;
b) functions of the form
$f(x) = a \cos x + b \sin x$.

3. Express the following functions as the sum of an even and an odd function:
a) $f(x) = x^2 + x - \frac{1}{x} + 2$;
6) $f(x) = \frac{x^2 + 2x + 1}{x^3 - x}$;
b) $f(x) = (x^2 + 2x + 1) \mathrm{tg} x$;
d) $f(x) = 2^x$.

4. It is known that the function $f$ is odd and $0 \in D(f)$. Find $f(0)$.

5. Find all functions $f$ that are both even and odd. (Pre-segments and positive ones on $R$?)
6. Are there all simultaneous functions that are simultaneously
a) even and increasing by $R$;
6) odd and decreasing by $R$;
b) odd and positive by $R$?
7. Can
a) even;
b) odd
the function has exactly
1) one;
2) two;
3) three extreme points?

8. a) Prove that the derivative of an even function is odd, and the derivative of an odd function is even.

6) Are the converse statements true:
1) if $f'(x)$ is an even function, then $f(x)$ is an odd function;
2) if $f'(x)$ is an odd function, then $f(x)$ is an odd function?

9. $(a - e)$. Complete the graph of the function shown on figure 4 to the graph of a certain, continuous function on $R$ and
1) even function;
2) odd function.

In what cases is this not possible? In what cases can this be done in several ways?

10 $(a - e)$. It is known that the function $f$ is defined, even and periodic with period $T = 4$. Reconstruct her schedule according to the fate shown in figure 5. In what cases can this not be done? In what cases can this be done, but it is ambiguous?

11 (10th grade). Plot graphs of the following functions:
a) $y = \arccos(\cos x)$;
6) $y = \arcsin(\sin x)$;
b) $y = \arctg(tg x)$;
d) $y = \arcsin(\cos x)$.
