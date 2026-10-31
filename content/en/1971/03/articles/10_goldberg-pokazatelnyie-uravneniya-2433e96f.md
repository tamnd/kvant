---
id: 1971-3-goldberg-pokazatelnyie-uravneniya-2433e96f
issue: kvant_1971_3
year: 1971
number: "3"
title: Exponential equations
authors:
  - Гольдберг В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 46
page_labels: 40, 42, 44
tag: CXZ5
lang: en
source: kvant_digital
extraction: vision
content_sha256: b42b0bac4d8ed48fa708dc7086f9e9f2bf23c15ce037282d8dec92053eb0f5c0
prompt_sha256: draft-1
translated_from: content/ru/1971/03/articles/10_goldberg-pokazatelnyie-uravneniya-2433e96f.md
source_content_sha256: 5b2b526b7d2b78203652fcd32e22df10f73482e630b32ccf6a1a6a8ebcaf5cfb
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Exponential equations are usually called equations in which the unknown quantity is contained in the exponent (but the bases do not contain it).

Solving exponential equations is based on the following power property:

if two powers with the same positive base different from one are equal, then their exponents are equal.

According to this property, the simplest exponential equation

$$a^x = b \quad (a > 0, a \neq 1, b > 0)$$

is solved as follows:

$$a^x = a^{\log_a b}, \quad x = \log_a b.$$

The difficulty in solving exponential equations is often that you need to be able to see the common basis of the left and right sides of the equation. If in Eq.

$$\left(\frac{4}{9}\right)^x \cdot \left(\frac{27}{8}\right)^{x-1} = \frac{2}{3}$$

the common base $\frac{2}{3}$ (or $\frac{3}{2}$) of the left and right sides immediately catches the eye, then in the equations

$$(0,4)^{x-1} = (6,25)^{6x-5}$$

To find the common base $\frac{2}{5}$ (or $\frac{5}{2}$), you must first convert the decimal fractions to ordinary ones. (Complete the solutions to the given examples; in equation (1) you will receive the answer $x=2$, and in equation (2) $x = \frac{11}{13}$.)

To reduce many exponential equations to the simplest, the following formula is often useful:

$$a^p \cdot b^p = (ab)^p.$$

Example 1: Solve the equation

$$\sqrt{3^x} \cdot \sqrt{5^x} = 225.$$

Solution e. We write the equation in the form

$$3^x \cdot 5^x = 225.$$

Using formula (3), we get

$$15^x = 15^2,$$

where do we find $x=4$.

Example 2: Solve the equation

$$2^3x \cdot 5^x = 1600.$$

Solution e. We have the following integer equivalent equations:

$$(2^3)x \cdot 5^x = 1600, \quad 8^x \cdot 5^x = 1600, \quad 40^x = 40^2, \quad x=2.$$

It is easy to reduce to the simplest equation the form

$$a^{\varphi(x)} = 1 \quad (a > 0, a \neq 1).$$

To do this, it is enough to represent one as $a$ to the zeroth power: $1 = a^0$.

Example 3: Solve the equation

$$5^{x^2+x-2} = 1.$$

Solution e. We successively find

$$5^{x^2+x-2} = 5^0, \quad x^2+x-2=0, \quad x_1=-2, \quad x_2=1.$$

⟦folio 42⟧

Example 9. Solve the equation
$$3 \cdot 16^x + 36^x = 2 \cdot 81^x.$$
Solved and e. We see that in this equation the bases 16, 36, 81 form a geometric progression and are raised to the same power $x$. To solve, divide both sides of the equation by $81^x$. We get
$$3 \cdot \left(\frac{4}{9}\right)^{2x} + \left(\frac{4}{9}\right)^x = 2.$$
Denoting $\left(\frac{4}{9}\right)^x$ by $y$, we arrive at the quadratic equation $3y^2 + y - 2 = 0$ with roots $y_1 = -1, y_2 = \frac{2}{3}$. We consider two cases:
a) $\left(\frac{4}{9}\right)^x = -1$ (no solutions);
b) $\left(\frac{4}{9}\right)^x = \frac{2}{3}, \left(\frac{2}{3}\right)^{2x} = \left(\frac{2}{3}\right)^1, 2x = 1, x = \frac{1}{2}$.
Example 10. Solve the equation
$$27^x + 12^x = 2 \cdot 8^x.$$
This equation is close to the one just considered: the exponent of the bases is the same, but bases 27, 12 and 8 do not form a geometric progression. The numbers 27, 18, 12, and 8 form a geometric progression—we can assume that the term containing $18^x$ enters the equation with a coefficient of zero.

Solved and e. Delimm all terms on $8^x$, we get
$$\left(\frac{3}{2}\right)^{3x} + \left(\frac{3}{2}\right)^x = 2.$$
Denoting $\left(\frac{3}{2}\right)^x$ by $y$, we arrive at the cubic equation
$$y^3 + y - 2 = 0,$$
the left side of which can be easily factorized:
$$(y^3 - 1) + (y - 1) = 0,$$
$$(y - 1)(y^2 + y + 2) = 0.$$

The only real root of this equation $y = 1$ leads to the equation $\left(\frac{3}{2}\right)^x = 1$, from which we find $x = 0$.

Example 11. Solve the equation
$$5 \cdot 2^{3x - 3} - 3 \cdot 2^{5 - 3x} + 7 = 0.$$
Solved and e. Let us rewrite the equation in the form
$$\frac{5}{8} \cdot 2^{3x} - \frac{96}{2^{3x}} + 7 = 0.$$
Let's denote $2^{3x}$ by $y$, then we get:
$$\frac{5}{8} y - \frac{96}{y} + 7 = 0,$$
$$5y^2 + 56y - 768 = 0,$$
$$y_1 = -19,2; y_2 = 8.$$
a) $2^{3x} = -19,2$ - the equation has no solution.
b) $2^{3x} = 8, 2^{3x} = 2^3, 3x = 3, x = 1.$
In the example above, the product of the bases is equal to one, and this is immediately noticeable; in the following example this fact is not so easy to notice *).

Example 12. Solve the equation
$$\left(\sqrt{5 + 2\sqrt{6}}\right)^x + \left(\sqrt{5 - 2\sqrt{6}}\right)^x = 10.$$
Solved and e. Multiply the bases:
$$\sqrt{5 + 2\sqrt{6}} \cdot \sqrt{5 - 2\sqrt{6}} = \sqrt{25 - 24} = 1.$$
If we denote $\left(\sqrt{5 + 2\sqrt{6}}\right)^x$ by $y$, then $\left(\sqrt{5 - 2\sqrt{6}}\right)^x = \frac{1}{\left(\sqrt{5 + 2\sqrt{6}}\right)^x} = \frac{1}{y}$. Hence
*) Note that the equations analyzed in examples 11 and 12 can be attributed to the same type as the equations in examples 9 and 10: the bases of the degree 2, 1, $\frac{1}{2}$ and $\sqrt{5 + 2\sqrt{6}}$, 1, $\sqrt{5 - 2\sqrt{6}}$ form a geometric progression and are raised to the same dependence on the $x$ degree.

⟦folio 44⟧

4. $4^x - 3^{x-\frac{1}{2}} = 3^{x+\frac{1}{2}} - 2^{2x-1}$.
5. $3 \cdot 2^x + 2 \cdot 3^x = 2^{x+3} + 3^{x-2}$.
6. $9^x - 2^{x+\frac{1}{2}} = 2^{x+\frac{7}{2}} - 3^{2x-1}$.
7. $3^{x+1} + 3^{x-1} + 3^{x-2} = 5^x + 5^{x-1} + 5^{x-2}$.
8. $9^{x-1} + 3^x = 2 \cdot 3^1, 5^x$.
9. $4^x + \sqrt{x^2-2} - 5 \cdot 2^{x-1} + \sqrt{x^2-2} = 6$.
10. $8^x + 18^x = 2 \cdot 27^x$.
11. $3^{1-x} - 3^{1+x} + 9^x + 9^{-x} = 6$.
12. $\sqrt[x]{\left(\frac{2}{3}\right)^3} - \sqrt[x]{\left(\frac{3}{2}\right)^3} - \sqrt[x]{\frac{2}{3}} + \sqrt[x]{\frac{3}{2}} = 3$.
13. $6 \sqrt[x]{9} - 13 \sqrt[x]{6} + 6 \sqrt[x]{4} = 0$.
14. $4^x = 2 \cdot 14^x + 3 \cdot 49^x$.
15. $(\sqrt{a + \sqrt{a^2-1}})^x + (\sqrt{a - \sqrt{a^2-1}})^x = 2a$ ($a > 1$).

Check that the equation of Example 12 is obtained from this equation at $a = 5$. Write what form this equation takes at $a = \sqrt{2}, \sqrt{3}, 2, 3, 4, 6$.

16. $2^x - 3^{\frac{x}{2}} = 1$.
17. $(\sin 1)^x + (\cos 1)^x = 1$.
18. $3^{x-1} + 5^{x-1} = 34$.
19. $5^{\sqrt{x}} + 12^{\sqrt{x}} = 13^{\sqrt{x}}$.
20. $10^{x^2} = 2 \cdot 100^x$.
21. $2^{x+3} - 3^{x^2} - 2 = 3^{x^2} + 1 - 2^{x-1}$.
22. $3^{x^2} + 4^{x^2} = 5^{x^2}$.
23. $x^{\sqrt{x}} = (\sqrt{x})^x$.
24. $x^{\sqrt{x^2}} = (\sqrt{x})^x$.
25. $8^x + 9 \cdot 2^{x+2} = 208$.

(For a start, see page 31.)

The next important step in the assimilation of electromagnets was made by the American physicist Joeph Henry in 1827. He is the first to contract for an iron core, not just one, but many layers of wiring, and the turns themselves are laid close to each other. It is possible that this would have been allowed by others, but at that time there was no wiring covered with insulation. Henry was the first to do such wiring. Insulated wires were not on sale then, and much later, of course. According to Henry's employee, the inventor of the telephone, F. Morse, even in 1837, only ... milliners used non-bare wires to make the frames of ladies' hats. Henry made the wires covered with insulation himself. As an insulating material, he used strips of silk cut from ... his wife's outfits (in those days, women wore long and fluffy clothes). This is how insulated wires first appeared and were used. Judging by Henry's electromagnets preserved in the museum, he had to wind silk strips around a lot of the wiring. But already in 1831 he could report that his largest electromagnet was capable of holding a load of 930 kilograms!
