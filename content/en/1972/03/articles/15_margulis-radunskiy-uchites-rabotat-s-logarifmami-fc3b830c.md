---
id: 1972-3-margulis-radunskiy-uchites-rabotat-s-logarifmami-fc3b830c
issue: kvant_1972_3
year: 1972
number: "3"
title: Learn to work with logarithms
authors:
  - Маргулис А. Я.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 57
page_labels: 50-55
tag: YENX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6a4a5c755580a0aff27ae713bf29accb1187bdb76fe1449ad688efbd834b8bd4
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/15_margulis-radunskiy-uchites-rabotat-s-logarifmami-fc3b830c.md
source_content_sha256: 746a80a55cbfb2ad5cdcc9777c72ae441553aa8c434e9707c8cbe2fc3432e429
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

LEARN TO WORK
WITH LOGARITHMES
A. Ya. Margulis, B. A. Radunsky

Definite logarithm

As is known, the logarithm of the number $N$ to the base $a$ ($a > 0; a \neq 1$) is the exponent to which the base $a$ must be raised to obtain a given number $N$, that is, for $a > 0$, $a \neq 1$ $x = \log_a N$, if $a^x = N$.

The mathematical notation for the definition of a logarithm is the so-called basic logarithmic identity:

$$a^{\log_a N} = N \quad (a > 0, a \neq 1, N > 0).$$

Let us recall that any positive number with any base (positive and different from one) has a logarithm, but negative numbers and zero do not have logarithms.

10 corollaries from the main identity

If the numbers $a$ and $b$ are positive and different from one ($M > 0$ and $N > 0$), then the following relations (properties of logarithms) are valid:

$$\log_a MN = \log_a M + \log_a N,$$

$$\log_a \frac{M}{N} = \log_a M - \log_a N,$$

$$\log_a M^\alpha = \alpha \log_a M,$$

$$\log_a N = \frac{\log_b N}{\log_b a},$$

$$\log_b a \times \log_a N = \log_b N,$$

$$\log_a b = \frac{1}{\log_b a},$$

$$\log_a^k N = \frac{1}{k} \log_a N \quad (k \neq 0),$$

$$\log_a^k N^k = \log_a N \quad (k = 0),$$

$$\frac{\log_a N}{\log_a M} = \frac{\log_b N}{\log_b M} \quad (M \neq 1),$$

$$\log_a N \times \log_b M = \log_a M \times \log_b N,$$

$$a^{\log_b c} = c^{\log_b a}.$$

Formulas (1), (2) and (3) are called logarithm rules. They allow you to find the logarithms of the product (1), quotient (2) and degree (or

⟦folio 51⟧

(3). The same formulas allow you to find a number by its logarithm, that is, the product of potentiation.

Formula (4) has a special meaning - it is the formula for moving to a new base. Thanks to this formula, there is no need to have tables of logarithms for different bases: it is enough to have, for example, a table of decimal logarithms to use formula (4) to find the logarithm for any base that intersects with us.

Formula (8) shows that the ratio of the logarithms of two numbers does not depend on the base.

Proofs of formulas (1) - (5) are carried out in a school course *); The reader can easily prove formulas (6) and (7) himself, moving to the base $a$ using formula (4). It is easy to verify the validity of formula (8) if you notice that both its left and right sides are equal to the number $\log_M N$ (why?); formula (9) is simply another representation of equality (8). And here is the rationale for formula (10):

$$a^{\log_b c} = a^{\frac{\log_a c}{\log_a b}} = (a^{\log_a c})^{\log_b a} = c^{\log_b a}.$$

Comment

We proposed that $M > 0$ and $N > 0$. However, when solving logarithmic equations (or inequalities), when the roles of $M$ and $N$ are expressions from the unknown $x$, transformations using the above formulas can lead to unequal equations (inequalities). In such cases, more general formulas should be used **); for example, if $M(x) \cdot N(x) > 0$, then

$$\log_a M(x) \cdot N(x) = \log_a |M(x)| + \log_a |N(x)|.$$

Now we will not consider hairs either. Our goal is to show how the basic properties of logarithms are applied to equations, calculating one logarithm in terms of another, and comparing them in magnitude.

Simplifying expressions containing logarithms

Carefully examine the examples given with pencil and paper; It is important to understand where the formulas listed above are used (we specifically carry out the conversions in detail, but with almost no explanation).

Example 1. Simplify: $\log_3 5 \cdot \log_4 9 \cdot \log_5 2$.

Solution. $\log_3 5 \cdot \log_4 9 \cdot \log_5 2 = \log_3 5 \cdot \log_5 2 \cdot \log_2 3 = \log_3 2 \cdot \log_2 3 = \log_3 3 = 1$.

Example 2. Simplify the expression:

$$N = \frac{\log_a \left[ \frac{1}{2} \log_b a^2 \right] \cdot \lg a \cdot \log_a \frac{1}{2} 100}{\left(\lg a \cdot 2^{\log_2 \lg a}\right)^{\frac{1}{2}} \cdot \lg^{-\frac{1}{2}} a^2}.$$

Solution. Let us first define the range of permissible parameter values: $a > 0$, $a \neq 1$, $b > 0$, $b \neq 1$ (since $a$ and $b$ serve as the bases of logarithms), $a > 1$ (for the existence of $\log_2 \lg a$ there must be $\lg a > 0$, whence $a > 1$), windows

*) See, for example, E. S. Kochetkov, E. S. Kochetkova, Algebra and elementary functions, M., “Enlightenment”, 1970, §§ 183-186.

**) For more details, see G.V. Dorofeev, M.K. Potapov, N.Kh. Rozov, A manual on mathematics for university applicants, M., “Nauka”, 1970.

⟦folio 52⟧

Particularly

$$a > 1; b > 0; b \neq 1.$$

We have
$$\log_a \left[ b^{\frac{1}{2} \log_b a^2} \right] \cdot \lg a \cdot \log_a^{\frac{1}{2}} 100 = \log_a b^{\log_b a} \cdot \lg a \sqrt{2 \log_a 10} =$$
$$= \frac{\log_a a \cdot \lg a \cdot \sqrt{2}}{\sqrt{\lg a}} = \sqrt{2 \lg a}; \quad (\lg a \cdot 2^{\log_2 \lg a})^{\frac{1}{2}} \lg^{-\frac{1}{2}} a^2 =$$
$$= \frac{\sqrt{\lg a \cdot \lg a}}{\sqrt{2 \lg a}} = \sqrt{\frac{\lg a}{2}};$$

finally, $N = \frac{\sqrt{2 \lg a}}{\sqrt{\frac{\lg a}{2}}} = 2.$

Example 3. Let's simplify the expression:
$$\left( b^{\frac{\log_{1000} a}{\lg a}} \cdot a^{\frac{\log_{1000} b}{\lg a}} \right)^3 \log_{ab} (2a + 3b)$$

Solution. The parameters must satisfy the conditions $a > 0; a \neq 1; b > 0; b \neq 1$ (explain why).

We have $b^{\frac{3 \log_{1000} a}{\lg a}} \cdot a^{\frac{3 \log_{1000} b}{\lg b}} = b^{\frac{\lg a}{\lg a}} \cdot a^{\frac{\lg b}{\lg b}} = ab,$
poseable

$$N = (ab)^{\log_{ab} (2a + 3b)} = 2a + 3b.$$

Example 4. Let's simplify the expression:
$$N = \left[ \left( \frac{\log_a^2 b + 1}{2 \log_a b} - 1 \right)^{\frac{1}{2}} + \left( \frac{2 \log_a^2 b + 1}{2 \log_a b} + 1 \right)^{\frac{1}{2}} \right] \sqrt{2} \log_a^{\frac{1}{2}} b.$$

Solution. The parameters must satisfy the following conditions: $a > 0; a \neq 1; b > 0, b \neq 1$ (explain why); furthermore, for $\log_a^{\frac{1}{2}} b$ to exist there must be $\log_a b \geq 0$. Therefore, definitively: $a > 1$ and $b > 1$ or $0 < a < 1$ and $0 < b < 1$. Next,

$$N = \left[ \sqrt{\frac{(\log_a b - 1)^2}{2 \log_a b}} + \sqrt{\frac{(\log_a b + 1)^2}{2 \log_a b}} \right] \sqrt{2 \log_a b} = |\log_a b - 1| + (\log_a b + 1) = \left\{ \begin{array}{l} 2 \log_a b, \text{ если } b \geq a > 1 \text{ или } 0 < b \leq a < 1; \\ 2, \text{ если } a \geq b > 1 \text{ или } 0 < a \leq b < 1. \end{array} \right.$$

Examples 2 and 4 clearly show how important it is to take into account the range of permissible parameter values.

Raising some logarithms through others

Example 5. Given: $\log_{30} 3 = a; \log_{30} 5 = b; \text{ найти } \log_{30} 8.$

Solution. $\log_{30} 8 = 3 \log_{30} 2 = 3 \log_{30} \frac{30}{15} = 3 (\log_{30} 30 - \log_{30} 3) - \log_{30} 5) = 3 (1 - a - b).$

Everything is simple here, because, firstly, the bases of all logarithms are the same and, secondly, you can express the number 2 through numbers, logarithms

⟦folio 53⟧

which are given (or known), that is, through the numbers 30, 3 and 5. Obviously this is not always easy to do.

Example 6. Given: lg196=a; lg56=b; find lg 0.175.

Solution. Representing the number 0.175 in terms of the well-known numbers 196, 56 and 10 is not so easy. Let's convert:

$$\lg 0,175 = \lg \frac{175}{1000} = \lg \frac{7}{40} = \lg 7 - 2 \lg 2 - 1.$$

Thus, the problem was reduced to finding lg7 and lg2.

The conditions of the problem can be written in the form of two equalities:

$$2\lg 2 + 2\lg 7 = a,$$
$$3\lg 2 + \lg 7 = b.$$

Of these is

$$\lg 2 = \frac{2b-a}{4}; \quad \lg 7 = \frac{3a-2b}{4}.$$

Then

$$\lg 0,175 = \frac{3a-2b}{4} - \frac{4b-2a}{4} - 1 = \frac{5a-6b-4}{4}.$$

Example 7. Given: $\log_{14}7=a; \log_{14}5=b; \text{найти } \log_{25}28.$

Solution. In the case of different bases, it is advisable to go to one base:

$$\log_{35}28 = \frac{\log_{14}28}{\log_{14}35} = \frac{\log_{14}2 \cdot 14}{\log_{14}5 \cdot 7} = \frac{1 + \log_{14} \frac{14}{7}}{a+b} = \frac{2-a}{a+b}.$$

Example 8. Given: $\log_{12}27=a; \text{найти } \log_{6}16.$

Solution. $\log_{6}16 = 4\log_{6}2 = 4\frac{\log_{12}2}{\log_{12}6} = \frac{4\log_{12}2}{\log_{12} \frac{12}{2}} = \frac{4\log_{12}2}{1-\log_{12}2}.$

All that remains is to find $\log_{12}2$. According to the conditions of the problem

$$a = \log_{12}27 = 3\log_{12}3 = 3\log_{12} \frac{12}{4} = 3(1-2\log_{12}2).$$

From here $\log_{12}2 = \frac{3-a}{6}$, and then

$$\log_{6}16 = \frac{4 \cdot \frac{3-a}{6}}{1-\frac{3-a}{6}} = \frac{4(3-a)}{3+a}.$$

Comparing logarithms by magnitude

Knowing the properties of the logarithmic function, it is easy to answer the following questions: which of the two numbers is greater: $\log_{2}3$ or $\log_{3}2$?

($\log_{2}3 > \log_{3}2$, or $\log_{2}3 > 1$, and $\log_{3}2 < 1$);

$$\log_{\frac{1}{2}}3 \text{ или } \log_{3}1,1? \quad \left( \log_{\frac{1}{2}}3 < 0, \quad \log_{3}1,1 > 0; \quad \log_{\frac{1}{2}}3 < \log_{3}1,1 \right);$$

$$\log_{3}5 \text{ или } \log_{4}5? \quad (\log_{3}5 > \log_{4}5 - \text{объясните почему});$$

$$\log_{\frac{1}{2}}3 \text{ или } \log_{\frac{1}{2}}4? \quad \left( \log_{\frac{1}{2}}3 > \log_{\frac{1}{2}}4 - \text{объясните почему} \right).$$

When solving more complex examples, in addition to using the properties of the logarithmic function, it will be necessary to perform various transformations.

⟦folio 54⟧

Example 9. (MSU, Faculty of Chemistry, 1969). Without a table, determine which is greater: $\log_{20}80$ or $\log_{80}640$?

Solution. We will use the given logarithms as much as possible and reduce them to the same base:

$$\log_{20}80 = 1 + 2\log_{20}2 = 1 + \frac{2}{\log_{2}20},$$

$$\log_{80}640 = 1 + 3\log_{80}2 = 1 + \frac{3}{\log_{2}80}.$$

It remains to compare the numbers $\frac{2}{\log_{2}20}$ and $\frac{3}{\log_{2}80}$. But $\log_{2}20 > 0; \log_{2}80 > 0$, and $2\log_{2}80 = \log_{2}6400 < 3\log_{2}20 = \log_{2}8000$. Therefore $\frac{2}{\log_{2}20} < \frac{3}{\log_{2}80}$, that is $\log_{20}80 < \log_{80}640$.

Example 10. (MSU, Faculty of Psychology, 1969). Do not use tables, prove that $\log_{3}7 > \log_{7}27$.

Solution. Since $\log_{7}27 = 3\log_{7}3 = \frac{3}{\log_{3}7}$ and $\log_{3}7 > 0$, it is enough to prove that $\log_{3}^27 > 3$ or $\log_{3}7 > \sqrt{3}$ or $7 > 3\sqrt{3}$.

Let's try to detail the “convenient” approximation for the irrational exponent. Namely, using the fact that $\sqrt{3} < 1,75 = \frac{7}{4}$, let us compare $7$ and $3^{\frac{7}{4}}$, that is, $7^4$ and $3^7$. From it $7^4 = 2401 > 3^7 = 2187$ is introduced, followed by $7 > 3^{\frac{7}{4}} > 3^{\sqrt{3}}$, and then $\log_{3}7 > \log_{7}27$.

Example 11. Without a table, determine which is greater: $\log_{5}7$ or $\log_{13}17$?

Solution. Reduction to one basis does not give anything good. However, this example is solved by the previous two. Note that $1 < \log_{5}7 < 2$, $1 < \log_{13}17 < 2$. Let's compare the numbers then

$$\log_{5}7 - 1 = \log_{5}7 - \log_{5}5 = \log_{5}\frac{7}{5}$$

And

$$\log_{13}17 - 1 = \log_{13}17 - \log_{13}13 = \log_{13}\frac{17}{13}.$$

But $\log_{5}\frac{7}{5} > \log_{13}\frac{7}{5} > \log_{13}\frac{17}{13}$ (explain why), and then $\log_{5}7 > \log_{13}17$.

Example 12. Prove that for any natural number $n > 1$

$$\log_{n}(n+1) > \log_{n+1}(n+2).$$

Solution. Obviously $\frac{n+1}{n} = 1 + \frac{1}{n} > \frac{n+2}{n+1} = 1 + \frac{1}{n+1}$. Therefore, using the properties of the logarithmic function, we have (for $n > 1$)

$$\log_{n}\frac{n+1}{n} > \log_{n+1}\frac{n+1}{n} > \log_{n+1}\frac{n+2}{n+1}.$$

Transforming the left and right sides, we immediately obtain that

$$\log_{n}(n+1) > \log_{n+1}(n+2).$$

From here it follows, for example, that

$$\log_{2}3 > \log_{3}4 > \dots > \log_{k+1}(k+2).$$

⟦folio 55⟧

Reception 13. (MSU, Faculty of Philology, 1969). Prove, without using tables, that $\log_2 3 > \log_3 5$.

Solution. The method used in the previous two examples cannot be directly applied (check this). Therefore, we will do this: $\log_2 3 = \log_8 27$;

$$\log_3 5 = \log_9 25, \text{ а } \frac{27}{8} > \frac{25}{9}.$$

Next, $\log_8 \frac{27}{8} > \log_9 \frac{27}{8} > \log_9 \frac{25}{9}$ or $\log_8 27 - 1 > \log_9 25 - 1$, hence $\log_2 3 > \log_3 5$.

Exercises

Simplify the following expressions:

1. $\frac{1}{5} \left( 2a^{\log_2 b} + 3b^{\log \sqrt{2}} \sqrt{a} \right)$.
2. $\left[ 1 + 2^{\frac{\lg a}{\lg \sqrt{2}}} - a^{1 + \frac{1}{\log_4 a^2}} \right]^{\frac{1}{2}} - 3 \log_3 2 \times \log_4 3 \cdot \log_5 4 \cdot \log_6 5 \cdot \log_7 6 \cdot \log_8 7$.
3. $\sqrt{\log_a b + \log_b a + 2 \cdot \log_{ab} a} \cdot \log_a^2 b$.

Calculate without using a table:

4. $2^{\sqrt{\log_2 3}} - 3^{\sqrt{\log_3 2}}$.
5. (MSU, Faculty of Psychologists, 1971).
$$\frac{\log_3 135}{\log_{15} 3} - \frac{\log_3 5}{\log_{405} 3}$$.
6. Compute $\log_6 32$ if $\log_12 2 = a$.
7. Compute $\log_5 0,18$ if $\lg 2 = a$, $\lg 3 = b$.
8. Compute $\log_{25} 24$ if $\log_8 15 = \alpha$, $\log_{12} 18 = \beta$.
Without the help of a table, determine which is greater:

9. $\log_2 3$ or $\log \frac{1}{4}$?
10. $\log_4 5$ or $\log \frac{1}{16}$?
11. $\log_5 7$ or $\log_8 3$?
12. $\log_2 3$ or $\log_5 8$?
13. (MSU, mechanism, 1971). $3 \log_{16} 1862 + \log_{16} 1866$ or $\log_2 1863$?
14. (MSU, Faculty of Chemistry, 1969). $\log_{189} 1323$ or $\log_6 147$?
15. (MSU, Faculty of Psychologists, 1969). Prove, without using tables, that $\log_3 16 > \log_16 729$.
16. (MSU, Faculty of Philology, 1969). Prove, without using tables, that $\log_5 14 > \log_7 18$.
