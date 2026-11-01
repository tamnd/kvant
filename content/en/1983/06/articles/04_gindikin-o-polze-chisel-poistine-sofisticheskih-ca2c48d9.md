---
id: 1983-6-gindikin-o-polze-chisel-poistine-sofisticheskih-ca2c48d9
issue: kvant_1983_6
year: 1983
number: "6"
title: On the benefits of “truly sophistical” numbers
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 12
page_last: 19
page_labels: 10, 11, 12, 13, 14, 16, 17
tag: TFYS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3782e6e2ed64e29f3cfac1162a05a49de41f967724b10f85b1644458689d9ff7
prompt_sha256: draft-1
translated_from: content/ru/1983/06/articles/04_gindikin-o-polze-chisel-poistine-sofisticheskih-ca2c48d9.md
source_content_sha256: 3d77a7f34ed420a33cc79fc957b00ab80b3ca8714424daac1136a7e07276c41d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

About the benefits of numbers
"most sophistical"
Candidate of Physical and Mathematical Sciences
S. G. GINDIKIN

The centuries-old history of the development of human understanding of numbers is one of the brightest aspects of the development of human culture. In an effort to expand the world of numbers, various motives are intertwined in a difficult to separate way.

Fractions appeared very early - already among the Egyptians and Babylonians - apparently in connection with the transition to smaller fractions of measurement. Their connection with the division of natural numbers was understood more vaguely and secondarily.

The Greeks realized numbers through the process of geometric measurement: this is how they realized the existence of irrational numbers (by not realizing the diagonal of a square and its sides) and built the theory of “magnitude” (as we would say today, the theory of positive real numbers) - one of the pinnacles of Greek geometry. A characteristic touch: only natural numbers were called “numbers,” and their extensions were called “magnitudes.” The computational aspect was relegated to the background and was usually not considered worthy of the scientist's attention. Plato, who energetically ensured that practical problems did not desecrate the true spirit of geometry, laughed at computational ones, “who exchange a unit for a small coin” (are engaged in division).

Negative numbers appeared in the 5th-6th centuries in Indian and Arabic mathematics, where the computational side of the matter came to the fore. And although the possibility of interpreting negative numbers, say, as a debt in problems of commercial content, was realized quite early on, practice has so far

⟦folio 11⟧

She said that they were convenient to use in a cup, which made such an interpretation possible. To greatly simplify, we can say that calculators consider negative numbers as “imaginary”, unreal numbers that are convenient to use in intermediate calculations as a result of subtraction when it is not feasible in the area of ​​positive numbers. At the same time, it is important to make sure that they do not violate the “rules of hygiene”: you can trust the final positive answer. There was no talk of any equality of negative numbers with a positive solution: in the final answer, except for the simplest situations, negative numbers did not appear. Various versions of their names indicate an expressive attitude towards them: “false”, “fictitious”, “absurd”, “impossible”, “minimum”.

However, the latter term later had to “give way” to another class of numbers, which surprisingly appeared in European mathematics simultaneously with the first serious consideration of negative numbers. This historian-mathematician is a parody of Gerolamo Cardano (1501-1576), a bright and controversial personality with a heightened penchant for fantasy and mysticism, which had long drawn him in the wrong direction. However, a more practical and cautious person would hardly have decided at that time on the constructions that mathematics owes to Cardano.

Cardano’s main results relate to the study of the formula for solving the cubic equation, which was first obtained by Ferro (1465–1526) and which Cardano learned from Tartaglia (1500?–1577) (for more details, see my book “Stories about Physics and Mathematics” (M., “Science”, 1981)).

Recall that the general cubic equation $x^3 + ax^2 + bx + c = 0$ can be reduced to the form by replacing $x = y - \frac{a}{3}$

$$x^3 + px + q = 0.$$  (1)

We will look for a solution to equation (1) in the form $x = y_1 + y_2$. Then $x^3 = y_1^3 + y_2^3 + 3xy_1y_2$. Comparing with (1), we see that if $y_1$ and $y_2$ satisfy the equalities $3y_1y_2 = -p$, $y_1^3 + y_2^3 = -q$, then $x = y_1 + y_2$ is a solution to equation (1). Such $y_1$, $y_2$ are easy to find: if $t_1 = y_1^3$, $t_2 = y_2^3$, then by Vieta’s theorem $t_1$ and $t_2$ are the roots of the quadratic equation $t^2 + qt - \frac{p^3}{27} = 0$,

that is, $t_{1,2} = -\frac{q}{2} \pm \frac{q^2}{4} + \frac{p^3}{27}$,

where

$$x = \sqrt[3]{\frac{-q}{2} + \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}} + \sqrt{\frac{-q}{2} - \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}}$$  (2)

formula (2) is now called the Cardano formula.

Let us now remember that Cardano considers magnitude in terms of positive numbers. (In addition, he did not know algebraic symbols, which made things incredibly difficult, especially when trying to formulate general rules. However, we will not imitate this type of difficulty here.) Posmotu Cardano studies equations separately

$$x^3 + ax = b,$$  (3)

$$x^3 = ax + b,$$  (4)

$$x^3 + b = ax,$$  (5)

where $a$, $b$ are positive. He does not consider the fourth formulaically possible type $x^3 + ax + b = 0$, since such an equation, very indo, does not have (positive!) roots.

Del Ferro came up with the rules for solving (3). Tartaglia rediscovered this rule and came up with decision rules (4); he formulated both rules in the form of a poem, which was communicated to Cardano.

Speaking goes, the oven goes that the solution is sought in the form $x = \sqrt[3]{u} \mp \sqrt[3]{v}$ (minus for (3), plus for (4)), where, respectively, $u \mp v = b$, $uv = \left(\frac{a}{3}\right)^3$ (cf. with (2)).

Equation (3) always has a single real root, and this root is always positive (today it is easy to see this from the graph) and well

⟦folio 12⟧

is easily found according to the specified rule.

In (4) also always has a single positive root $x$, and always $x > \sqrt{a}$ (why?).

If $\Delta = \frac{q^2}{4} + \frac{p^3}{27} = \frac{b^2}{4} - \frac{a^3}{27} \geq 0$ (this is equivalent to $x \leq \frac{4a}{3}$), then the root is found according to formula (2).

In this case there are no other real roots. If $\Delta < 0$, then in (2) under the square radical there is an oriental number and the formula fails. In fact, in this case (it was called *irreducible*), in addition to one positive one, it has two oriental roots (perhaps multiple). Tartaglia undoubtedly knew from examples that even for $\Delta < 0$ a positive root of equation (4) can exist, and Cardano unambiguously asserted the existence of a root in the general case. The irreducible case of equation (4) reached a lot of wills of both Tartaglia and Cardano, but a way to find the root was never found!

As for equation (5), it easily reduces to (4): the roots of (5) differ from the roots of (4) in sign, and, therefore, for $\Delta = \frac{b^2}{4} - \frac{a^3}{27} > 0$ (5) has no positive roots, and for $\Delta < 0$ (in the irreducible case) there are two positive roots (and one orienting one). But this type of reasoning was beyond the capabilities of mathematicians of the 15th century. Tartaglia writes that solution (5) reduces to solution (4), but makes no hint as to the method of reduction.

Cardano came up with a way to go from (5) to (4) that was pretty close to substituting $x = -y$. We are looking for the positive root $x$ of equation (5). Let $y$ be the positive root of equation (4); it always exists, and $y \geq \sqrt{a}$ and, in the irreducible case, $y < \sqrt{\frac{4a}{3}}$. Adding (4) and (5), we obtain $x^3 + y^3 = a(x+y)$, whence $x^2 - xy + y^2 = a(x+y) \neq 0$ in the positive region), $x_{1,2} = \frac{y}{2} \pm a - \frac{3y^2}{4}$. As a result, for $y < \sqrt{\frac{4a}{3}}$, that is, in the irreducible case ($\Delta < 0$), we express through the positive root $y$ of equation (4) two positive roots of equation (5) (their positive follows from inequality $y > \sqrt{a}$). Cardano notes that $y = x_1 + x_2$, that is, in the irreducible case, the positive root of equation (4) is equal to the sum of the positive roots of equation (5).

Thus, by studying equation (5), Cardano managed to stay within the framework of positive roots. But it was precisely as a result of these distances that he understood the role that negative roots play. He realized that equation (5) always has a “false” (negative) root - $y$, that for $\Delta < 0$ the sum of all its roots, including “false”, is equal to zero, that for this equation to be valid for $\Delta = 0$ one must assume that equation (5) has a multiple positive root, that equation (4) in the irreducible case has two “false” roots and that the sum of all its roots in this case is also equal zero.

Cardano generalized the statement about the sum of the roots of an equation that has three roots (counting “false”) to general cubic equations: the sum of the roots differs in sign from the coefficient at $x^2$. (It must be said that Vieta’s famous theorem, relating to the roots of a quadratic equation, was obtained later.) Cardano was the first to work with negative roots, and he not only drew attention to the possibility of considering them - he showed how harmoniously they enter into the theory of algebraic equations. With these results of Cardano, algebra in the modern sense of the word began.

Cardano's results were collected in his book “The Great Art or On the Rules of Algebra,” published in 1545. Chapter XXXVII of this book is called “On the Rule for Considering False Unknowns.” And if the first rule in this chapter relates to negative roots, then the second rule says: “The second type of false solution

⟦folio 13⟧

equation is the root of a negative quantity. I'll give you an example. If anyone demands to divide 10 into two parts, which by variable length would be 30 or 40, then it is clear that this case or question is impossible. But we will do this: divide 10 in half, half will be 5; multiplied by itself, it will give 25. Then subtract from 25 what should be obtained by the variable, say 40, as I announced this to you in the chapter on actions in the 4th book; then $m:15$ will remain; if you take $R$ from this and add it to 5 and subtract it from 5, you get parts that, variable among themselves, will give 40. Thus, these parts will be $5p:Rm:15$ and $5m:Rm:15$). This text is not difficult to decipher. We are talking about the equation $x(10-x)=40$, that is $x^2-10x+40=0$. It is stated that its roots will be $5 \pm \sqrt{25-40} = 5 \pm \sqrt{-15}$. The reader can easily restore the notation used by Cardano.

This is how complex numbers first appeared in mathematics, which Cardano calls “pontine sophistical.” Cardano has not used the new numbers at all and seems to be somewhat suspicious of them.

There is one interesting point in all this. It is often suggested (for example, N. Bourbaki) that Cardano invented complex numbers while trying to deal with the irreducible randomness of the cubic equation. The fact is that if in formula (2) at $\Delta<0$ one is not afraid to take the square root of a negative number, then in subsequent operations the minimal parts are destroyed and the result is the correct answer, which is a real number*). Thus, appealing to complex numbers not only makes it possible to justify Cardano’s formula in the general case, but they inevitably arise in the problem of determining the real roots of a cubic equation with real coefficients. It would be very logical if Cardan taught complex numbers for this reason. But there is no evidence that Cardano goes beyond quadratic equations when working with complex numbers. As a result, historical facts often fail to detect “natural” connections!

The connection between complex numbers and irreducible cubic equations was discovered, if not by Cardano, then very soon. This was done by Cardano's immediate successor, the engineer from Bologna Raphael Bombelli (c. 1530-1572), author of the famous Algebra, published in 1572. Among multicharacteristics, the systematic study of complex (and negative) numbers. You can find matches in Bombelli

$$\sqrt[3]{2+\sqrt{-121}}=2+\sqrt{-1},$$

$$\sqrt[3]{52+\sqrt{-2209}}=4+\sqrt{-1}.$$

Interestingly, Bombelli gives a special name for $i$ (“pii de meno”; 1 he calls “pii”). Bombelli confidently applies complex numbers to irreducible cubic equations.

The Cardano formula contains expressions of the form $\sqrt[3]{\alpha \pm \sqrt{\beta}}$, where $\beta$ can be of any sign; These expressions are what Bombelli explores. Let $\sqrt[3]{\alpha \pm \sqrt{\beta}}=u \pm \sqrt{v}$ (which means from (2) $x=2u$). Then $u^3+3uv=a$, $u^2-v=a^3\sqrt{a^2-\beta}$ and, if we put $\gamma=a^3\sqrt{a^2-\beta}$, for $u$, regardless of the sign of $\beta$, the equation $4u^3=3\gamma u+\alpha$ arises. In particular, in the Cardano formula for equation (4) we have $\alpha=\frac{b}{2}$, $\beta=\frac{b}{2})^2-\frac{a}{3})^3$, $\gamma=\frac{a}{3}$.

Now, on the one hand, it is clear how the real root is expressed through cubist roots of complex numbers ($x=2u$), but, on the other hand, the expression for $x$ through real radials still does not work, since the cubist equation $4u^3=$

⟦folio 14⟧

$$au + \frac{b}{2}, \text{ фактически совпадающие (подстановка } x=2u \text{) с исходным уравнением (4).}$$

Later, Leibniz (1646-1716), who studied cubic equations from Bombelli's book, finally realized that in the irreducible case it is impossible to express the roots of the equation in terms of radicals while remaining in the real region.

At the turn of the 17th-17th centuries, the fate of the new numbers was not decided. François Viète (1540-1603), who was often called the “father of algebra” because he began to use algebraic symbols (letter notations for the coefficients of an equation, and not just for unknowns), tried to do without not only complex roots, but also without negative ones. Since he dealt, in particular, with the correspondence between roots and coefficients (Vieta’s theorem), this was not easy for him, but he found a way out. Let's say, if equation (5) has two positive roots $x_1$, $x_2$ and one negative root $x_3$, then Vieta, together with the equalities $x_1+x_2+x_3=0$, $x_1x_2+x_1x_3+x_2x_3=-a$, $x_1x_2x_3=-b$ (now these equalities are called Vieta’s formulas), show that $x_1^2+x_2^2+x_1x_2=a$, $x_1x_2(x_1+x_2)=b$ (prove it!), not involving, unlike the Cardans, neither the third negative root nor the positive root of the auxiliary equation (4). There is an opinion (N. Bourbaki) that the relative conservation of Vieta is due to the fact that he was a strange admirer of the ancients.

We must remember Vieta in connection with his interpretation of the irreducible cubic equation. Viet was a great master of obtaining algebraic correspondences to triometric means. While working on trionometric functions of multiple angles, Viet decided to use the formula $$\cos 3\varphi=4\cos^3\varphi-3\cos\varphi$$ (6) to solve cubic equations. He compared (6) with equation (4). To make this comparison more arbitrary, we make the replacement $a=3r^2$, $b=\alpha r^2$ in (4). In this notation, the irreducible case corresponds to $r>\frac{a}{2}$, which makes the replacement $a=2r \cdot \cos v (0<v<\frac{\pi}{2})$ natural. If we also make a replacement for the unknown $x=2ry$, then (4) turns into the equation

$$4y^3-3y=\cos v,$$

(which, by virtue of (6), satisfies $y=\cos \frac{v}{3}$, that is, for (4) we obtain an expression for the positive root $x_1=2r \cdot \cos \frac{v}{3}$. It is clear that two negative roots are equal to $x_{2,3}=2r \cdot \cos \left(\pm \frac{2\pi}{3}+\frac{v}{3}\right)$ and that for equation (5) similar calculations are correct, only $\frac{\pi}{2}<v<\pi$ and $x_1$ are negative roots, and $x_2,x_3$ are negative (compare these representations for the roots with the method of Kardanov moving from the roots of equation (4) to the roots of equation (5)).

Let's abandon the imitation of antiquity for a while and rewrite Vieta's formula in notation (1), (2). If $\Delta=\frac{q^2}{4}+\frac{p^3}{27}<0$ (irreducible case), then, in particular, $p<0$. Poling $r=\sqrt{-p/3}$, $\alpha=\frac{3q}{p}$ (then $2r>a$), $v=\arccos \frac{\alpha}{2r}$, we finally get

$$x=2\sqrt{-p/3}\cos \left(\frac{2\pi k}{3}+\frac{\arccos \frac{3q\sqrt{3}}{2p\sqrt{-p}}}{3}\right)$$

Vieth performs all calculations in the field of real numbers, but his representation of roots involves not only algebraic operations, but also trigonometric functions. His formula does not contradict the fact that there is no algebraic representation of the roots of an irreducible cubic equation. Vieta's formula is undoubtedly suitable for computational help:

⟦folio 16⟧

agree with Girard: at that time the “usefulness” of complete numbers did not manifest itself in any way.

The theorem about the roots of an equation of the $n$th degree also appears on the “algebraic” pages of the signs of Rene Descartes’s “Geometry” (1596-1650), published in 1637 in Leiden (in the same place as Girard’s book). This book lays the foundations of analytical geometry, but the text dealing with general algebraic equations is also very readable. Descartes does not use letter designations for coefficients (as Viète did) and is forced to encroach on the statement with examples; Descartes introduced the notation $x$ for the unknown and from it comes the modern notation for powers $x^3$, $x^4$ (however, together $x^2$ is still written $xx$). “So, know,” writes Descartes, “that in each equation there can be as many different roots, that is, values ​​of an unknown quantity, as the latter has dimensions.”
The exponent here is called “dimension”, because the geometric interpretation of the degree (square, cube) still comes to the fore. Further: “No, sometimes it is heard that some of these roots are false, or less than nothing.” As one would expect from the creator of analytical geometry, Descartes confidently handles negative numbers. He clearly states the statement, now called `теоремой Безу` (who lived much later - in the 18th century), for both positive and negative roots, which makes it possible to understand the degree of the equation if the root is known. After this, Descartes writes: “However, both true and false roots are not always real, but sometimes they are only minimal (“imaginaires”; hence the term “minimum” - S.G.), that is, you can always imagine as many roots as I said, but sometimes there is no value that would correspond to the root that is imagined. So, for example, in the equation $x^3 - 6xx + 13x - 10\infty$ (Descartes used the sign $\infty$ together already

existing =) one can imagine three roots, but among them only one is real, namely 2; as for the other two, they can be notified, reduced or multiplied in the way I just explained, but for all that they remain only minimal.”

Let us pay attention to two facts: Descartes does not try to divide the left side of the equation by $x$—and for the complex root $\alpha$ and, accordingly, is not ready to consider equations with complex coefficients (complex numbers play a service role). Descartes can be understood in such a way that complex numbers can be positive and negative, that is, he does not yet understand that complex numbers can be naturally ordered! This error of the great scientist shows how vague the ideas about complex numbers were. We have provided extracts from Descartes to demonstrate in the most advanced version the ideas about algebraic equations and complex numbers that had developed by the middle of the 17th century.

And then, for almost a century and a half, the best mathematical scientists were concentrated on creating mathematical analysis. Algebra, which then actually coincided with the theory of algebraic equations, was studied little, and algebraic results looked modest in comparison with analytical achievements. It can be said that the excellence of mathematicians is mainly in their turn to algebra in connection with the needs of analysis and analytical geometry. Let's add up that the expansion of polynomials into polytels was needed to interpret rational fractions. And we started to get used to complex numbers. In connection with the needs of analysis, even logarithms of complex numbers were considered.

In 1746, D'Alembert published a proof of the fundamental theorem of algebra with some problems, but with a "true core" (Gauss). With the work of Lagrange (1736–1813), a new era began in the theory of algebraic equations. Show-

⟦folio 17⟧

It is noteworthy that both Lagrange and Euler (1707–1783) paid significant attention to the study of the Cardan formula in the complex domain. Euler considers the elementary functions of a complex variable and discovers an orderly connection between exponential and trigonometric functions. This was a fundamental step, since previously complex numbers were associated only with algebraic equations.

Back at the beginning of the 18th century, an important example was discovered when compla roots can not only be introduced for a painting, but are associated with a specific actual task. Cotes and Muav discovered a connection between the equation $x^n-1=0$ and the classical problem of dividing a circle into $n$ equal parts. This connection is very simple if you know the geometric interpretation of compil numbers (the $n$ complic roots of 1 are the vertices of a regular $n$-gon).

Gauss (1777–1855) may have already known this interpretation when he used the connection with the equation $x^{17}-1=0$ to construct a regular 17-gon in 1796. However, in his publication, as well as in his dissertation in 1798, devoted to the first rigorous proof of the fundamental theorem of algebra (it has a purely real formulation: any polynomial with real coefficients can be expanded into a product of the same polynomials of no higher than the second degree), he prefers not to use compilation numbers. In 1811, in a letter to Bessel, Gauss wrote: “Just as all real quantities can be represented by an infinite straight line, one can imagine the region of all quantities, real and mini, by means of an infinite plane, where each point, defined by its abscissa $a$ and its ordinate $b$, is represented at the same time by the magnitude $a+ib$.” Gauss published this result only in 1831. Similar results of Gauss's lesser-known contemporaries remained almost unsubstituted: J. Arron (1806), K. Wessel (1798, the work remained unknown for a hundred years). In the creation of mathematicians, the geometric interpretation of complex numbers turned an imaginary object into a real one (by the way, the term “complex number” was proposed by Gauss).

The history of mathematics in the 19th century can no longer be separated from complex numbers. Gauss, Cauchy, Jacobi, Abel, Riemann show that the transition to the analysis of functions of a complex variable makes it possible to discover the most profound facts that cannot be seen in the real domain.

In geometry, “imaginary” elements appeared a hundred years later than in algebra. Gerard Desargues (1593-1662) discovered that if one introduces “imaginary” infinite distant points at which parallel lines “intersect”, then parallelism actually turns into a special case of intersection. Here the picture is in many ways reminiscent of the situation with complex numbers, which made it possible to avoid considering exceptional cases. Victor Poncelet (1788-1867) almost two years later (this was in Saratov, in captivity after the War of 1812) showed that all circles “pass” through two complex infinitely distant points. This was the moment when complex numbers appeared in geometry. Many believed that they contradicted genuine geometric intuition (the famous geometer Jacob Steiner (1796-1863) called them “ghosts”, “the kingdom of shadows”). And yet there was no choice - too many (real) geometric facts became clear from a complex point of view.

Triva has shown a complex number to occupy an infinite position in mathematics. Perhaps this is not so much compared to ten centuries, which showed the absence of negative numbers. However, in school mathematics the position of complex numbers (as opposed to negative numbers) remains fragile to this day.
