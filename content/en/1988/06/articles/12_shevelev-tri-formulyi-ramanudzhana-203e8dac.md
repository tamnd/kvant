---
id: 1988-6-shevelev-tri-formulyi-ramanudzhana-203e8dac
issue: kvant_1988_6
year: 1988
number: "6"
title: Ramanujan's three formulas
authors:
  - Шевелёв В. С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 57
page_labels: 52-55
tag: 6MNW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 47b6f474080fd3ed4191dd50f592822fe63d7c1bfc9f1fa061bc03605e35a00f
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/12_shevelev-tri-formulyi-ramanudzhana-203e8dac.md
source_content_sha256: bd0f5d413a30adec4e2bbdba1d45ff2362fd886b1a021dd11ba0a76360344135
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

Ramanujan's three formulas
Candidate of Physical and Mathematical Sciences
V. S. SHEVELEV

Ramanujan's formulas always contain much more than it seems at first glance...

Hardy

In this article we will talk about three remarkable formulas of Ramanujan *), each of which contains three cube roots on the left side:

$$\sqrt[3]{\frac{1}{9}} - \sqrt[3]{\frac{2}{9}} + \sqrt[3]{\frac{4}{9}} = \sqrt[3]{\sqrt[3]{2} - 1},$$

(1)

$$\sqrt[3]{\cos \frac{2\pi}{7}} + \sqrt[3]{\cos \frac{4\pi}{7}} + \sqrt[3]{\cos \frac{8\pi}{7}} =$$

$$= \sqrt[3]{\frac{5 - 3\sqrt[3]{7}}{2}},$$

(2)

These formulas are difficult to confuse with the formulas of any other mathematician: they resemble mysterious juggling with numbers.

The first formula is simpler and proves successive cubes. For us, in addition to natural perception, it is interesting because in the structure of relationships it is very similar to the next two. As for formulas (2) and (3), not everything is so simple here. Here are some interesting quotes about these formulas from V. I. Levin’s brochure**):

“These formulas are very elementary, but very deep. They have a unique internal symmetry, which suggests their existence

**) You can read about the life and work of this unique mathematician in «Kvant» No. 10, 1987.

**) Levin V.I. Ramanujaan. - M.: Knowledge, 1968.

⟦folio 53⟧

Only a mathematician of the highest rank could.” And again: “These exact equalities are, of course, special cases of much more general relations that Ramanujan propagated, but about which he never reported anything...”

We invite the reader to follow the proof of formulas (2) and (3). In some places he will need a pencil and paper. As a reward, he has almost an internal mechanism that controls these beautiful formulas and, apparently, will be able, on his own, to prove several formulas like Ramanujan’s formulas (found by the author - see Exercise 5), and perhaps come up with his own.

Connection with Vieta's formulas

The connection between trigonometry and algebra is easily discernible in Ramanujan's formulas. Let's take a closer look at the numbers

$$\begin{cases} \cos \frac{2\pi}{7}, \cos \frac{4\pi}{7}, \cos \frac{8\pi}{7} \\ \cos \frac{2\pi}{9}, \cos \frac{4\pi}{9}, \cos \frac{8\pi}{9} \end{cases}.$$

First of all, it is striking that the arguments of the cosines form geometric progressions with value 2 in both triplets.

Taking advantage of the transformation

$$\cos \alpha \cos 2\alpha \cos 4\alpha = \frac{\sin 2\alpha \cos 2\alpha \cos 4\alpha}{2 \sin \alpha} = \frac{\sin 4\alpha \cos 4\alpha}{4 \sin \alpha} = \frac{\sin 8\alpha}{8 \sin \alpha},$$

we can establish the following equalities:

$$\cos \frac{2\pi}{7} \cos \frac{4\pi}{7} \cos \frac{8\pi}{7} = \frac{1}{8},$$

$$\cos \frac{2\pi}{9} \cos \frac{4\pi}{9} \cos \frac{8\pi}{9} = -\frac{1}{8}.$$

This is our first success showing that the cosine arguments in Ramanujan's formulas are chosen relatively non-randomly.

Let's now try to find the sums of three cosines. We have:

$$\cos \frac{2\pi}{7} + \cos \frac{4\pi}{7} + \cos \frac{8\pi}{7} =$$

$$= \frac{2 \sin \frac{\pi}{7}}{2 \sin \frac{\pi}{7}} \left( \cos \frac{2\pi}{7} + \cos \frac{4\pi}{7} + \cos \frac{6\pi}{7} \right) =$$

$$= \frac{1}{2 \sin \frac{\pi}{7}} \left( \sin \frac{3\pi}{7} - \sin \frac{\pi}{7} + \sin \frac{5\pi}{7} \right) - \sin \frac{3\pi}{7} + \sin \pi - \sin \frac{5\pi}{7} = -\frac{1}{2};$$

$$\cos \frac{2\pi}{9} + \cos \frac{4\pi}{9} + \cos \frac{8\pi}{9} =$$

$$= \cos \frac{2\pi}{9} + \cos \frac{4\pi}{9} - \cos \frac{\pi}{9} =$$

$$= 2 \cos \frac{3\pi}{9} \cos \frac{\pi}{9} - \cos \frac{\pi}{9} = 0.$$

Finally, we send the following amounts:

$$S_1 = \cos \frac{2\pi}{7} \cos \frac{4\pi}{7} + \cos \frac{2\pi}{7} \cos \frac{8\pi}{7} + \cos \frac{4\pi}{7} \cos \frac{8\pi}{7},$$

$$S_2 = \cos \frac{2\pi}{9} \cos \frac{4\pi}{9} + \cos \frac{2\pi}{9} \cos \frac{8\pi}{9} + \cos \frac{4\pi}{9} \cos \frac{8\pi}{9}.$$

Exercise 1. Prove that $S_1 = -\frac{1}{2}, S_2 = -\frac{3}{4}$.

Let us now write Vieta's formulas for the cubic equation. If $x, y, z$ are the roots of the equation

$$t^3 + pt^2 + qt + r = 0,$$

then, as is known,

$$\begin{cases} x + y + z = -p, \\ xy + xz + yz = q, \\ xyz = -r. \end{cases}$$

Let us compare (4) with the equalities that we obtained above for Ramanujan triples of cosines, we conclude that the first triple consists of the roots of the equation

$$t^3 + \frac{1}{2} t^2 - \frac{1}{2} t - \frac{1}{8} = 0,$$

and the second is from the roots of the equation

$$t^3 - \frac{3}{4} t + \frac{1}{8} = 0.$$

This stage is the most important in our proof. It shows how

⟦folio 54⟧

va nature of the connection between trionometric and algebraic expressions in formulas (2) and (3).

Let's consider the sum of three roots...

Let us now pose the problem like this. Given the equation
$$t^3 + pt^2 + qt + r = 0,$$
whose roots are the numbers $x, y, z$. We need to find the sum of their cube roots (we denote the cube of this sum by $A$):
$$\sqrt[3]{x} + \sqrt[3]{y} + \sqrt[3]{z} = \sqrt[3]{A}.$$
(7)

It turns out that sum (7) is easy to look for together with another sum:
$$\sqrt[3]{xy} + \sqrt[3]{xz} + \sqrt[3]{yz} = \sqrt[3]{B}.$$
(8)

Cube both parts (7), and then (8) and taking into account Vieta’s formulas (4), we obtain (check it yourself):
$$A = -p + 3\sqrt[3]{AB} + 3\sqrt[3]{r},$$
$$B = q - 3\sqrt[3]{ABr} - 3\sqrt[3]{r^2},$$
(10)

Multiplying (9) by $\sqrt[3]{r}$ and adding with (10), we express $B$ through $A$:
$$B = q - (A + p)\sqrt[3]{r}.$$
(11)

Substituting this into (9), we obtain an equation only for $A$:
$$A + p - 3\sqrt[3]{r} = 3\sqrt[3]{A(q - (A + p)\sqrt[3]{r})}.$$
(12)

Finally, by cubeing both sides of the equation, we obtain the following cubic equation for $A$:
$$A^3 + 3(p + 6\sqrt[3]{r})A^2 + 3(p^2 + 3p\sqrt[3]{r} + 9\sqrt[3]{r^2} - 9q)A + (p - 3\sqrt[3]{r})^3 = 0.$$ (11)

Simplifying the cubic equation

Let us be given a cubic equation
$$x^3 + 3bx^2 + 3cx + d = 0.$$ (12)

We will show how - in some cases especially successfully - it can be simplified.

Substituting $x = z - b$ into (12), we obtain a cubic equation for $z$, not containing $z^2$ (check!). Moreover, if $b$ and $c$ in equations (12) are related by the relations
$$b^2 = c,$$
then the term with $z^1$ will also disappear from the equations for $z$. As a result, the equation
expression (12) will take the form
$$z^3 = b^3 - d.$$
Returning to $x$, we get
$$x = \sqrt[3]{b^3 - d} - b.$$ (13)

Let us check in which case the condition $b^2 = c$ is satisfied for equation (11). Comparing it with (12), we have:
$$b = p + 6\sqrt[3]{r},$$
$$c = p^2 + 3p\sqrt[3]{r} + 9\sqrt[3]{r^2} - 9q,$$
and the condition $b^2 = c$ takes the form:
$$3\sqrt[3]{r^2} + p\sqrt[3]{r} + q = 0.$$ (14)

Now comes an exciting moment: after all, the numbers $p, q$ and $r$ are known for the equation whose roots are Ramanujan triples of cosines (see formulas (5) and (6))!

For the first three: $p = 1/2$, $q = -1/2$, $r = -1/8$; for the second triple: $p = 0$, $q = -3/4$, $r = 1/8$. Substituting these values ​​into (14), we obtain numerical equalities! But in this case, according to (13) (at $x = A$, $b = p + 6\sqrt[3]{r}$, $d = (p - 3\sqrt[3]{r})^3$),
$$A = \sqrt[3]{b^3 - d} - b.$$
In the case of the first three, $b = \frac{1}{2} - 3 = -\frac{5}{2}$, $d = \left(\frac{1}{2} + \frac{3}{2}\right)^3 = 8$, so
$$A = \frac{-3\sqrt{189} + 5}{2} = \frac{5 - 3\sqrt{7}}{2}.$$
In the case of the second triple $b = 3$, $d = \left(-\frac{3}{2}\right)^3 = -\frac{27}{8}$ and
$$A = \sqrt[3]{27 + \frac{27}{8}} - 3 = \frac{3\sqrt[3]{9} - 6}{2}.$$

These are not like radical expressions of the right-hand sides of Ramanujan's formulas (2) and (3). Therefore, the proof is complete.

Exercise 2. Putting $\sqrt[3]{x} = u$, $\sqrt[3]{y} = v$, $\sqrt[3]{z} = w$, prove that condition (14) for $u, v, w$ not equal to 0 is equivalent to the condition
$$u^3 + v^3 + w^3 + \frac{(uv)^2}{w} + \frac{(uw)^2}{v} + \frac{(vw)^2}{u} + 3uvw = 0.$$ (15)

From our proof it follows that condition (15) is satisfied by the cubic roots of Ramanujan

⟦folio 55⟧

cosines (first and second triples). It is easy to check directly that it is also satisfied by the triple of numbers

$$u = \sqrt[3]{\frac{1}{9}}, v = -\sqrt[3]{\frac{2}{9}}, w = \sqrt[3]{\frac{4}{9}}.$$

Thus, equalities (1), (2), (3) are based on the general condition (15).

Perhaps Ramanujan knew other triplets of numbers ($u, v, w$) satisfying condition (15).

Exercise 3. Show that, together with the numbers $u, v, w$, condition (15) is satisfied by: a) the numbers $\frac{1}{u}, \frac{1}{v}, \frac{1}{w}$;
6) numbers $\sqrt[3]{u^3+uvw}, \sqrt[3]{v^3+uvw}, \sqrt[3]{w^3+uvw}$.

Exercise 4. Prove that if condition (15) is satisfied, then the equality is true

$$\left( \frac{u}{v} + \frac{v}{u} + \frac{u}{w} + \frac{w}{u} + \frac{w}{v} \right)^3 + 6 = \left( \frac{u}{v} \right)^3 + \left( \frac{v}{u} \right)^3 + \left( \frac{u}{w} \right)^3 + \left( \frac{w}{v} \right)^3.$$

Check, for example, (16) for the triple of numbers $u = \sqrt[3]{\frac{1}{9}}, v = -\sqrt[3]{\frac{2}{9}}, w = \sqrt[3]{\frac{4}{9}}$. Is it possible, on the contrary, to derive (15) from (16)?

Exercise 5. Prove the equalities:

$$1^\circ. \sqrt[3]{\sec \frac{2\pi}{7}} + \sqrt[3]{\sec \frac{4\pi}{7}} + \sqrt[3]{\sec \frac{8\pi}{7}} = \sqrt[3]{8-6\sqrt[3]{7}};$$

$$2^\circ. \sqrt[3]{\sec \frac{2\pi}{9}} + \sqrt[3]{\sec \frac{4\pi}{9}} + \sqrt[3]{\sec \frac{8\pi}{9}} = \sqrt[3]{6(\sqrt[3]{9}-1)};$$

$$3^\circ. \sqrt[3]{\sec 2+\sec \frac{2\pi}{7}} + \sqrt[3]{\sec 2+\sec \frac{4\pi}{7}} + \sqrt[3]{\sec 2+\sec \frac{8\pi}{7}} = \sqrt[3]{6\sqrt[3]{7}-10};$$

$$4^\circ. \sqrt[3]{\frac{1}{2}+\cos \frac{2\pi}{7}} +$$
