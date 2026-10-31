---
id: 1970-3-mordkovich-koe-chto-o-radikalah-bb0e56db
issue: kvant_1970_3
year: 1970
number: "3"
title: Something about radicals
authors:
  - Мордкович А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 59
page_labels: 53-57
tag: Q3LL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5327cf946f024596aa514ad2fc98dca573157a810db389960da9e34749574f6a
prompt_sha256: draft-1
translated_from: content/ru/1970/03/articles/19_mordkovich-koe-chto-o-radikalah-bb0e56db.md
source_content_sha256: c5413f2dd1175d2141e3351e3944ba75a8dc49cde0d4c495e50ccbfcbff17c45
translation_model: draft
translation_run: en-draft-test
translation_quality: draft
---

⟦folio 53⟧

SOMETHING ABOUT RADICALAX

A. G. MORDKOVICH

“And now,” said the Examiner, “I want to offer you one more task, a very simple one.” Here it is:

Find the sides of a right triangle if it is known that the projection of one kamet on the sinomendus is 6 cm, and the projection of another kamet is 1.5 cm less than the length of this kamet.

... A few minutes later the Applicant goes to the Examiner together.
- Well, how did you solve the problem? - asked the Examiner.
- Yes! - answered the Entrant.
- And what happened?
— The problem has no solution.
- And you can prove it?

- Certainly! Consider triangle ABC (see figure); C is the top of a right angle, CH is the height. Let AC = x, then by condition AH = = x—1.5, and BH = 6.

⟦folio 54⟧

We use the known relation
$$CH^2 = BH \cdot AH$$ or $$CH^2 = 6(x - 1,5).$$

Applying the Pythagorean theorem to the right triangle $ACH$, we obtain

$$\sqrt{AC^2 - CH^2} = AH,$$

that is

$$\sqrt{x^2 - 6(x - 1,5)} = x - 1,5.$$

“Well, so far everything is correct,” the Examiner noted, “although we must say that the solution path chosen was not the most rational.”

“And then,” continued the Entrant, “there are simple calculations left:

$$\sqrt{x^2 - 6x + 9} = x - 1,5; \quad \sqrt{(x - 3)^2} = x - 1,5;$$

$$x - 3 = x - 1,5; \quad -3 = -1,5.$$

Since the last equality is false, the problem has no solution.

“Unfortunately, I must disappoint you,” said the Examiner, “the problem has a solution.” It can be solved, for example, like this: from the known relation $AC^2 = AB \cdot AH$ we have $x^2 = (x + 4,5) (x - 1,5), 3x = 4,5 \cdot 1,5$ and $x = 2,25$, that is, $AC = 2,25$ cm. Then $AB = 6,75$ cm, and $BC = 4\sqrt{2}$ cm.

And, catching the Applicant’s puzzled look, the Examiner added:

- You are apparently interested in where the error is in your reasoning. Well, let's figure it out.

WHERE IS THE ERROR?

“You remember,” the Examiner began, “that I, although with a reservation, approved your geometric reasoning.” So the error could only have occurred in what you called “simple calculations.” More precisely, an error was made when extracting the square root. You did not teach that, according to the meaning of the problem, the quantity $\sqrt{(x - 3)^2}$ must be positive. And in general, in the field of real numbers, the sign $\sqrt{}$ implies the arithmetic, non-negative value of the root. So, $\sqrt{16} = 4$, and you cannot write that $\sqrt{16} = -4$ or $\sqrt{16} = \pm 4$. Therefore, it cannot be said that $\sqrt{a^2} = a$ is always: for $a \geq 0$ this equality is true, but the number $a$ can also be negative! Simplify, for example, $\sqrt{(-3)^2}$:

The applicant wrote:

$$\sqrt{(-3)^2} = \sqrt{9} = 3.$$

- Right. In other words,

$$\sqrt{(-3)^2} = -(-3).$$

And in general, if $a < 0$, then $\sqrt{a^2} = -a$.

Thus,

$$\sqrt{a^2} = \begin{cases} a, если a \geq 0, \\ -a, если a < 0. \end{cases}$$

“I understand,” exclaimed the Applicant, “this can be briefly written as follows: $\sqrt{a^2} = |a|$, because the model $a$ is defined in exactly the same way:

$$|a| = \begin{cases} a, если a \geq 0, \\ -a, если a < 0. \end{cases}$$

- Absolutely right. It’s exactly the same in your problem: you can’t write

⟦folio 55⟧

$$\sqrt{(x-3)^2} = (x-3), \text{ потому что } (x-3) \text{ может быть и отрицательным числом.}
\text{Если воспользоваться тем, что } \sqrt{(x-3)^2} = |x-3|, \text{ то приdem к управлению } |x-3| = x-1, 5.$$

Next we should consider two cases: 1) $x-3 \geq 0$; 2) $x-3 < 0$. You only considered the first case, so the conclusion that the problem has no solution was made prematurely. In the second case $|x-3| = -(x-3)$. Then from the equation $-(x-3) = x-1, 5$ we obtain $x = 2, 25$, that is, $AC = 2, 25$ cm.

“Everything is clear,” said the Entrant.
In this case, we will consider our conversation finished. To beg your pardon, let me give you the following advice:

Don't forget that $\sqrt{a^2} = |a|!$

We will discuss this with the Applicant and the Examiner, but we will take the Examiner’s advice into account. In particular, we will use it when solving the following example.

Example 1: Simplify an expression

$$\sqrt{\frac{a+x^2}{x} - 2\sqrt{a}} + \sqrt{\frac{a+x^2}{x} + 2\sqrt{a}}, \text{ если } x > \sqrt{a}.$$

Solution. We have

$$\sqrt{\frac{a+x^2-2x\sqrt{a}}{x}} + \sqrt{\frac{a+x^2+2x\sqrt{a}}{x}} =$$

$$\frac{\sqrt{(V\bar{a}-x)^2}}{\sqrt{x}} + \frac{\sqrt{(V\bar{a}+x)^2}}{\sqrt{x}} = \frac{|V\bar{a}-x|}{V\bar{x}} + \frac{|V\bar{a}+x|}{V\bar{x}}.$$

Since by condition $x > \sqrt{a} \geq 0$, then $|V\bar{a}-x| = -V\bar{a} + x$, $|V\bar{a}+\bar{x}| = \sqrt{a} + x$, and this expression is transformed as follows:

$$\frac{-V\bar{a} + x + \sqrt{a} + x}{\sqrt{x}} = 2\sqrt{x}.$$

A FEW WORDS ABOUT THE PROPERTIES OF RADICALS

When solving examples of actions with radicals, one has to use various properties of radicals. So, in example 1 we used, and quite carefreely, the well-known property:

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{b}.$$

However, it should be taken into account that this equality occurs only in the case when $a \geq 0$ and $b > 0$. If $a$ and $b$ are negative numbers, then the notation $\frac{\sqrt{a}}{b}$ does not make sense in the field of real numbers. In example 1, on our part, no error occurred, since $(V\bar{a}-x)^2 > 0$, $(V\bar{a}+x)^2 > 0$ and, in addition, by condition $x > 0$. But, in any case, from the above we can draw the following conclusion: you must be very careful when revealing the root (of the degree) of a product or a fraction. In the general case, when the sign of $a$ and $b$ is unknown, it is advisable to carry out the following reasoning:

$$\sqrt{\frac{a}{b}} = \sqrt{\frac{|a|}{|b|}} = \sqrt{\frac{|a|}{|b|}}.$$

⟦folio 56⟧

So, if the numbers $a$ and $b$ have the same symbols, then

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{|a|}}{\sqrt{|b|}}$$

and similarly

$$\sqrt{ab} = \sqrt{|a|} \cdot \sqrt{|b|}.$$

Example 2: Simplify

$$\sqrt{\frac{a-\sqrt{x}}{a+\sqrt{x}}} + \sqrt{\frac{a+\sqrt{x}}{a-\sqrt{x}}} - \sqrt{\frac{16}{a^2-x}},$$ if $x = 4(a-1)$.

Solution. Let us express, on the contrary, $a$ through $x$: $a = \frac{x+4}{4}$, and substitute it into this expression. It is converted like this:

$$\sqrt{\frac{x-4\sqrt{x}+4}{x+4\sqrt{x}+4}} + \sqrt{\frac{x+4\sqrt{x}+4}{x-4\sqrt{x}+4}} - \sqrt{\frac{16^2}{(x+4)^2-16x}}$$

$$= \frac{|\sqrt{x}-2|}{|\sqrt{x}+2|} + \frac{|\sqrt{x}+2|}{|\sqrt{x}-2|} - \frac{16}{\sqrt{x^2}-8x+16}$$

$$= \frac{(x-4\sqrt{x}+4) + (x+4\sqrt{x}+4)}{|(\sqrt{x})^2-4|} - \frac{16}{|x-4|} = \frac{2x+8}{|x-4|} - \frac{16}{|x-4|} = 2\frac{x-4}{|x-4|}.$$

Note also that $x > 4$ if $a > 2$, and $x < 4$ if $1 \leqslant a < 2$.

Final answer:

2 if $a > 2$,
- 2 if $1 \leqslant a < 2$.

We used - and this is often useful - the following property of the module: for all $a$ and $b$

$$|a| \cdot |b| = |ab|, \quad |a|^2 = a^2.$$

And now we will dwell on one more important property of the root.

Example 3: Simplify

$$\sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[5]{3\sqrt{2}-2\sqrt{5}}.$$

Solution. People often think like this. Using the well-known property of the root, you can show the root of the second factor by multiplying by 2 and at the same time squaring the subordinate expression; we get

$$\sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[5]{3\sqrt{2}-2\sqrt{5}}$$

$$= \sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[10]{(3\sqrt{2}-2\sqrt{5})^2}$$

$$= \sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[10]{19^2-(6\sqrt{10})^2} = \sqrt[10]{1} = 1.$$

But there is a mistake here! The correct answer is minus one. The point is that $3\sqrt{2}-2\sqrt{5} < 0$ because $(3\sqrt{2})^2 = 18 < (2\sqrt{5})^2 = 20$.

Therefore, it is not true that $\sqrt[5]{3\sqrt{2}-2\sqrt{5}} = \sqrt[10]{(3\sqrt{2}-2\sqrt{5})^2}$, but it is true that $\sqrt[5]{3\sqrt{2}-2\sqrt{5}} = -\sqrt[5]{2\sqrt{5}-3\sqrt{2}} = -\sqrt[10]{(2\sqrt{5}-3\sqrt{2})^2}$.

Example 4: Simplify $\sqrt[8]{(\pi^2-10)^4}$.

⟦folio 57⟧

Here, too, it would be incorrect to simply divide the indicator of the root and radical expression by 4:

$$\sqrt[8]{(\pi^2 - 10)^4} = \sqrt{\pi^2 - 10}$$

(the result does not make sense because $\pi^2 < 10$). The following equality is true:

$$\sqrt[8]{(\pi^2 - 10)^4} = \sqrt{10 - \pi^2}.$$

As a result, we come to the following conclusion:

Using the basic properties of radicals in cases where you are not sure that the root contains a positive number, you need to ensure that, firstly, the result obtained makes sense (if necessary, the modulus sign will help us out) and, secondly, that the result obtained has the same sign as the first analogous expression.

TASKS

1. List the conditions under which the following equalities are true ($k$ and $n$ are natural numbers):

a) $$\sqrt[n]{-a} = -\sqrt[n]{a};$$
e) $$a \cdot \sqrt[n]{b} = \sqrt[n]{a^n b};$$
6) $$\sqrt[n]{a^n} = a;$$
g) $$\sqrt[n]{a} = \sqrt[n]{a^k};$$
b) $$(\sqrt[n]{a})^n = a;$$
h) $$\sqrt[k]{\sqrt[n]{a}} = \sqrt[k]{a};$$
d) $$\sqrt[n]{a \cdot b} = \sqrt[n]{a} \cdot \sqrt[n]{b};$$
i) $$(\sqrt[n]{a})^k = \sqrt[n]{a^k};$$
e) $$\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{n \sqrt[n]{b}};$$
j) if $a < b$, then $$\sqrt[n]{a} < \sqrt[n]{b}$$.

2. Simplify the following expressions:

a) $$(\sqrt{\frac{a+1}{a-1}} + \sqrt{\frac{a-1}{a+1}}) \cdot (\sqrt{\frac{a+1}{a-1}} - \sqrt{\frac{a-1}{a+1}});$$
6) $$\sqrt{\frac{3y+x^3}{2x}} + \sqrt{3xy} - \sqrt{\frac{3y+x^3}{2x}} - \sqrt{3xy};$$
b) $$\frac{(4a^2m^{-2} + a^{-2}m^2 - 4)^{-1/2}}{2ma (m^2 - a^2)^{-1/2}} \cdot \left(2 \sqrt{m^4 - \frac{a^2}{m^{-2}}} - \frac{2a^2}{\sqrt{1 - a^2}m^{-2}}\right);$$
d) $$\frac{a + \sqrt{2 + \sqrt{5}} \cdot \sqrt[12]{(9 - 4\sqrt{5})^3}}{\sqrt[3]{2 - \sqrt{5}} \cdot \sqrt[6]{9 + 4\sqrt{5}} - \sqrt[3]{a^2} + \sqrt[3]{a}}.$$
