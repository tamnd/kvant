---
id: 1984-10-skvortsova-nado-li-delat-proverku-7b23fd12
issue: kvant_1984_10
year: 1984
number: "10"
title: Is it necessary to do a check?
authors:
  - Скворцова М. Г.
rubric: shkola-v-kvante
page_first: 33
page_last: 34
page_labels: 31-32
tag: FUL9
lang: en
source: kvant_digital
extraction: vision
content_sha256: ffbeedb9268043dc07859cd8bb9a8dfd6a2e492e8ea48aa27629a4bb5ee8995d
prompt_sha256: draft-1
translated_from: content/ru/1984/10/articles/14_skvortsova-nado-li-delat-proverku-7b23fd12.md
source_content_sha256: 3bd94cb876705137b74d093a2dd17db193585bb7c324f6d5dbbef5f486bcea18
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

After this he was asked if there was another way to obtain this formula. After thinking a little, he wrote down cos 3α=±√1−sin² 3α=..., but quickly realized that nothing good would come of this path.

But in this case, differentiation helps again. Differentiating both sides of equality (3) with respect to α, we obtain

3 cos 3α=3 cos α−12 sin² α cos α=
=3 cos α−12(1−cos² α) cos α,
whence cos 3α=4 cos³ α−3 cos α.

Exercises

1. Knowing that sin 5x=16 sin⁵ x−20 sin³ x+5 sin x, obtain a formula expressing cos 5x in terms of cos x.

2. Using differentiation, obtain from the “simple” identity 2 sin 2α sin α+cos 3α=cos α another, “more complex” identity.

3. The well-known formula is a sin x+b cos x=
=√a²+b² sin(x+φ), where the angle φ is determined from the condition sin φ=b/√a²+b², cos φ=a/√a²+b².
Obtain from this formula the formula for a cos x−b sin x.

V. E. Olkhov

Is it necessary to do a check?

Schoolchildren often ask the question: “We found the roots of the equation, do we need to check?” Checking the roots just in case, “for reliability” (substituting them into a given equation), is, of course, useful, in any case, when this does not lead to more difficult calculations than the solution itself. But this is not what is meant here - the oven is about testing related to the possibility of “proneness building roots”. Schoolchildren know that without doing such a check, they can sometimes get the wrong answer (“an extra root”). Moreover, even if the answer turns out to be correct, the teacher or examiner sometimes declares the solution incomplete if there is no check. But when? In what cases is it necessary to check? Let's try to answer this question.

1. In cases where the roots were found using the simplest “ready-made” formulas (such as formulas for solving linear and quadratic equations or equations of the form cos x=a,

log₂ x=a, b⁻=a, etc.), the check need not be done.

For example, as a rule, there is no point in checking the roots obtained using the formula

x₁,₂ = -b ± √b²−4ac/2a

for the quadratic equation ax²+bx+c=0. (However, if the roots turn out to be intact or rational, the check is done quickly and there is no harm in it.)

However, when using such formulas, you should be aware of the conditions under which they can be used. Thus, formula (1) can be used under the conditions a≠0, b²−4ac≥0. Unfortunately, there are often cases when schoolchildren say that at a=0 the equation ax²+bx+c=0 has no roots, since the famous name on the right side of formula (1) vanishes. At the same time, they forget that when a=0 this equation will not be quadratic and has a root x=-c/b, unless, of course, b≠0.

The answer x=±arccos 2+2πk, k∈Z for the equation cos x=2 is considered to be a gross error, since the formula x=±arccos a+2πk, k∈Z for the roots of the equation cos x=a can only be used for |a|≤1.

2. More often, when solving an equation, we arrive at a lot of transformations; in this case, these equations are replaced each time with some new one, and the new equation, naturally, may have other roots. If, during the transformation of an equation, a new equation is replaced that has all the roots of the previous one and only them (that is, the equation is transformed so that no loss or gain of roots occurs), then such equations are called equivalent.

It is well known that

1) when transferring terms of an equation from one part to another,
2) when adding the same number to both sides of an equation,
3) When both sides of the equation are multiplied by the same non-zero number, the original number and the transformation of the equation are equivalent. They are also equivalent if the transformation consists of applying identities that are valid for the set of all real numbers, for example, the identities of the abbreviated

⟦folio 32⟧

multiplication, sine and cosine sum formulas, etc.

When all these transformations are applied, equivalent equations are obtained each time. Therefore, after finding the roots, checking them is not a mandatory step in solving the problem.

Let us solve, for example, this way the equation
$$\sqrt{3} \cos x - \sin x - 1 = 0.$$ (2)
Dividing both sides of the equation by 2, we get the equation
$$\frac{\sqrt{3}}{2} \cos x - \frac{1}{2} \sin x - \frac{1}{2} = 0,$$ (3)
equivalent equation (2). Because
$$\cos \frac{\pi}{6} = \frac{\sqrt{3}}{2}, \sin \frac{\pi}{6} = \frac{1}{2},$$ then equation (3) will be rewritten in the form
$$\cos x \cos \frac{\pi}{6} - \sin x \sin \frac{\pi}{6} - \frac{1}{2} = 0.$$
Applying the cosine formula for the sum of two angles from right to left, we obtain the equation
$$\cos \left(x + \frac{\pi}{6}\right) - \frac{1}{2} = 0,$$ (4)
equivalent equation (3).
Adding $\frac{1}{2}$ to both sides of the equation, we obtain the equation
$$\cos \left(x + \frac{\pi}{6}\right) = \frac{1}{2},$$ (5)
equivalent equation (4).
The solution to the simplest equation (5) will be written as follows:
$$x + \frac{\pi}{6} = \frac{\pi}{3} + 2k\pi, \quad k \in \mathbb{Z},$$
$$x + \frac{\pi}{6} = -\frac{\pi}{3} + 2n\pi, \quad n \in \mathbb{Z},$$
where
$$x = \frac{\pi}{6} + 2k\pi, \quad k \in \mathbb{Z},$$
$$x = -\frac{\pi}{2} + 2n\pi, \quad n \in \mathbb{Z}.$$
Since all the transformations performed were equivalent, checking the found roots is not necessary.
3. However, not every equation can be solved using only equivalent transformations. It is much more common to use unequal transformations. When applying such transformations, in general, you can lose some roots of the original equation or *gain* construction roots, that is, roots that are not the roots of the original equation. Most often, such transformations are based on the use of formulas that are not valid for all actions $x$. In this case, in part, the domain of definition of the equation “changes”.
If, for example, the formulas
$$\log_3 x^2 = 2 \log_3 x,$$ (6)
$$\sin 2x = \frac{2 \mathrm{tg} x}{1 + \mathrm{tg}^2 x}$$ (7)
take “from left to right” (that is, replace the left side of the formula with the right), then the roots of the original equation may be lost; Therefore, such transformations without additional considerations are unacceptable.
For example, the equation
$$\log_3 x^2 = 2$$ (8)
has two roots: $x_1 = 3, x_2 = -3$. However, if we apply formula (6) “from left to right”, we obtain the equation
$$2 \log_3 x = 2,$$
having only one root: $x_1 = 3$. Consequently, as a result of applying formula (6) “from left to right,” the root of equation (8) was lost. Note that when applying formula (6), it is possible to lose all negative roots. With formula (7) the situation is simpler. It can be used, but you should additionally check whether numbers of the form $\frac{\pi}{2} + \pi k, k \in \mathbb{Z}$ are roots for which $tg x$ is not defined.
4. If we apply formula (6) “from right to left,” then the loss of roots will not occur, but the addition of constructed roots may occur, and therefore it is necessary to check the roots and discard those that turn out to be constructed.
Extraneous roots can also appear when both parts of the equation arise in degrees, when both parts of the equation are potentiated, and during a number of other transformations. Therefore, if any of these transformations were applied, then it is necessary to check the found roots and discard the constructed roots.
Example. *Solve the equation*
$$x - 3 = \sqrt{x - 1}.$$ (9)
