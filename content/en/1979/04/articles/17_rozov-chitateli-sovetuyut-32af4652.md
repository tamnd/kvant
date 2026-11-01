---
id: 1979-4-rozov-chitateli-sovetuyut-32af4652
issue: kvant_1979_4
year: 1979
number: "4"
title: Readers advise
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48, 49, 51
tag: EWFA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5761e4413a8ac01d8db6d866217a9064320776d74ca76c5b252c4131e7112261
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/17_rozov-chitateli-sovetuyut-32af4652.md
source_content_sha256: 4b41d528d1684c03336edf6a58375374e881a9d633f5fc61a717da360422ed7e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Reader advise

In the general editorial mail «Kvant» a significant part of the letters from our readers - schoolchildren, teachers, mathematics lovers - concerns the topic of the section “Applicant Practice”. Many of them touch on partial issues; the editors respond to such letters personally by their author. But in a whole series of letters and notes, interesting messages are expressed on various theoretical issues in the school mathematics course, ideas for certain types of exam problems are outlined, useful comments, methodological suggestions, and independently composed problems are communicated. Although the messages and tasks given in such letters are not always new and original, in our opinion, it is advisable to introduce all readers «Kvant» to their content. Not considering it possible to publish these letters and notes in full, the editors have prepared a selection of materials compiled according to ideas and suggestions from the reader of the magazine, with the necessary additional comments. We hope that the questions included in the collection will help applicants to universities.

Fluency in the school mathematics course, which an applicant must demonstrate in the admission exam, implies, in particular, the ability to correctly carry out calculations and correctly transform algebraic expressions. Unfortunately, applicants often have their grades reduced precisely for mistakes made during the conversion process. Such errors, as a rule, do not occur due to insignificance - they are, rather, the result of inattentiveness and negligence, the inability to check oneself, the result of insufficient practice in solving examples that reflect technical training (see «Kvant», 1974, No. 3, pp. 49-50). The essence of this method is that instead of one of the variables included in the algebraic expressions, a certain trigonometric function of the auxiliary angle is substituted, and it is selected so that the original expression is simplified by virtue of well-known trigonometry formulas.

Of course, trigonometric training is useful not only for transforming algebraic expressions, but also in many problems - when solving equations, proving inequalities, etc. A large set of interesting examples of this kind was sent by our reader V. Olkhov (Gorky).

Example 1. Prove Christmas

$$\sqrt{a + \sqrt{b}} = \sqrt{\frac{a + \sqrt{a^2 - b}}{2}} + \sqrt{\frac{a - \sqrt{a^2 - b}}{2}}.$$ (1)

First of all, we note that both sides of equality (1) simultaneously make sense if

$$b \geq 0, a \geq 0, a \geq \sqrt{b};$$ (2)

for these values ​​$a$ and $b$ we will prove our identity. The presence of the expression $a^2 - b$ under the square root suggests the idea of ​​putting

$$b = a^2\sin^2\varphi, \text{ где } 0 \leq \varphi \leq \pi/2,$$ (3) - because then

$$\sqrt{a^2 - b} = a\cos\varphi.$$

Such trigonometric preparation is acceptable, since due to inequalities (2) the fraction $b/a^2$ (at $a \neq 0$) lies between 0 and 1 and it can be taken as the value of the squared sine of a certain angle of the first quarter

⟦folio 49⟧

(if $a=0$, then $b=0$ and identity (1) is very specific).

After substituting (3) for the law, part of equality (1) will be written in the form

$$\sqrt{a} \left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right).$$

At the same time

$$\sqrt{a + \sqrt{b}} = \sqrt{a + a \sin \varphi} = \sqrt{a} \left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right),$$

since $1 + \sin \varphi = \cos^2 \frac{\varphi}{2} + 2 \cos \frac{\varphi}{2} \sin \frac{\varphi}{2} + \sin^2 \frac{\varphi}{2} = \left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right)^2$, and identity (1) is proven.

Example 2. Prove that for $c > 0, a > c, b > c$

$$\sqrt{(a + c)(b + c)} + \sqrt{(a - c)(b - c)} \leq 2 \sqrt{ab}.$$

How is the equal sign achieved in this inequality?

Let us rewrite the inequality being proved in the form

$$\sqrt{\left( 1 + \frac{c}{a} \right)\left( 1 + \frac{c}{b} \right)} + \sqrt{\left( 1 - \frac{c}{a} \right)\left( 1 - \frac{c}{b} \right)} \leq 2.$$ (4)

Since by condition

$$0 < \frac{c}{a} < 1, \quad 0 < \frac{c}{b} < 1,$$

can be put

$$\frac{c}{a} = \cos \alpha, \quad 0 < \alpha < \pi/2,$$

$$\frac{c}{b} = \cos \beta, \quad 0 < \beta < \pi/2.$$

If we perform this trigonometric substitution on the left side of inequality (4), then we can follow:

$$\sqrt{(1 + \cos \alpha)(1 + \cos \beta)} + \sqrt{(1 - \cos \alpha)(1 - \cos \beta)} = 2 \left( \cos \frac{\alpha}{2} \cos \frac{\beta}{2} + \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \right) = 2 \cos \left( \frac{\alpha}{2} - \frac{\beta}{2} \right) \leq 2,$$

which proves inequality (4).

From the above transformation chain it is clear that equality in accordance with (4) is achieved when

$$\cos \left( \frac{\alpha}{2} - \frac{\beta}{2} \right) = 1,$$

i.e. at $\alpha = \beta$; this is only possible with $a = b$ (check it yourself!).

The following irrational equation with a parameter can be easily solved by the standard method - exponentiation; you just need to be careful not to get built roots. We will show how this equation can be solved differently - using trigonometric substitution.

Example 3: Solve the equation

$$\sqrt{p + x} + \sqrt{p - x} = x.$$ (5)

Let us first note that if equation (5) for some value of the parameter $p$ has a root, then this root is a non-negative number (why?). It follows that for $p < 0$ equation (5) has no roots, for $p = 0$ it has one root $x = 0$ and for $p > 0$ the roots must satisfy the inequality $0 < x \leq p$ (prove these statements).

Let's make a trigonometric substitution

$$x = p \cos \psi, \quad 0 \leq \psi < \frac{\pi}{2};$$

then equation (5) will take the form

$$\sqrt{1 + \cos \psi} + \sqrt{1 - \cos \psi} = \sqrt{p} \cos \psi,$$

or

$$\sqrt{2} = \sqrt{p} \left( \cos \frac{\psi}{2} - \sin \frac{\psi}{2} \right)$$

(make calculations). By squaring both sides of the last equation, we get

$$\sin \psi = \frac{p - 2}{p}.$$

We determine from here the value $\psi$ can be selected in the first quarter only when $p \geq 2$; therefore, equation (5) has roots only for values ​​of the parameter $p \geq 2$. For any parameter value that satisfies this condition,

⟦folio 51⟧

wearing

$$\sin \varphi = \frac{b}{\sqrt{a^2 + b^2}}, \cos \varphi = \frac{a}{\sqrt{a^2 + b^2}}$$

(«Kvant», 1976, No. 4, pp. 41-42).

M. Shkalenyuk (Odessa) points out an interesting generalization of formula (7) in his letter. Let us demonstrate this generalization on a specific problem.

Example 5 (MSU, Mechanics and Mathematics, 1965). How many roots does the equation have?

$$\sin x + 2 \sin 2x = 3 + \sin 3x?$$

Using well-known trigonometry formulas, we rewrite the proposed equation in the form

$$\sin 2x - \sin x \cos 2x = \frac{3}{2}.$$

(8)

Now we transform the left part as follows:

$$\sin 2x - \sin x \cos 2x =$$

$$= \sqrt{1 + \sin^2 x} \left[ \frac{1}{\sqrt{1 + \sin^2 x}} \sin 2x - \frac{\sin x}{\sqrt{1 + \sin^2 x}} \cos 2x \right].$$

Since for any $x$

$$\left( \frac{1}{\sqrt{1 + \sin^2 x}} \right)^2 + \left( -\frac{\sin x}{\sqrt{1 + \sin^2 x}} \right)^2 = 1,$$

there exists an angle $\varphi = \varphi(x)$ depending on $x$ such that

$$\frac{1}{\sqrt{1 + \sin^2 x}} = \cos \varphi(x),$$

$$- \frac{\sin x}{\sqrt{1 + \sin^2 x}} = \sin \varphi(x).$$

No then

$$\sin 2x - \sin x \cos 2x =$$

$$= \sqrt{1 + \sin^2 x} \sin (2x + \varphi(x)),$$

so equation (8) is equivalent to equation

$$\sqrt{1 + \sin^2 x} \sin (2x + \varphi(x)) = \frac{3}{2}.$$

Since the left side of the last equation does not exceed $\sqrt{2}$ for all values ​​of $x$, this equation has no roots.

* * *

Our reader V. Kolmykov (Voronezh) suggests finding an error in the “proof” of the following clearly incorrect “theorem”:

10. Theorem. If two planes are parallel, then they coincide.

Proof. Let

$$ax + by + cz + d = 0$$

is the equation of the plane $\alpha$, and

$$Ax + By + Cz + D = 0$$

is the equation of the plane $\beta$, and let $\alpha \parallel \beta$. Due to the parallelism of these planes

$$\frac{A}{a} = \frac{B}{b} = \frac{C}{c},$$

or, if he denotes these relations by $k$, $A = ka$, $B = kb$, $C = kc$.

No then the equation of the plane $\beta$ can be written as

$$ax + by + cz + d = 0.$$

Subtracting equality (9) from equality (10), we obtain that $D = kd$, and therefore equation (10) of the plane $\beta$ can be rewritten in the form

$$ax + by + cz + d = 0.$$

Since this equation coincides with equation (9) of the plane $\alpha$, we obtain $\alpha = \beta$.
