---
id: 1989-4-chulaevskiy-preobrazovanie-pekarya-83390604
issue: kvant_1989_4
year: 1989
number: "4"
title: Baker Conversion
authors:
  - Чулаевский В. А.
rubric: raznoe
page_first: 21
page_last: 24
page_labels: 19-22
tag: 52LL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3dfff9c5701d279edb3054f5e26fe7a45e7f5180b9855216985581badf22452f
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/03_chulaevskiy-preobrazovanie-pekarya-83390604.md
source_content_sha256: 7675891de8984f884deb8a1fe71ea3da9daf29273c1bb9ed677c90fe3f3252c4
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

BAKER'S TRANSFORMATION

Candidate of Physical and Mathematical Sciences
V. A. CHULAEVSKY

If we have to hear the words “probability”, “randomness”, then, please, most often we remember the game of flip flops, throwing dice or shuffling cards. And the term “gambling” itself comes from the French word hasard, which means “case”. Attempts to find hidden mechanisms that control the situation have been made at all times. However, as a rule, they ended sadly - remember Pushchin’s Hermann! And is there anything in common between complete predestination (“three, seven, ace”) and randomness? Let's not rush to answer, but for now, let's do... cooking.

Unsalted pie problem. So let's bake a pie. Let's open the cookbook and choose a recipe to suit your taste. We replace the dough, wait until it rises, and roll it out into a square with a rolling pin. Let's start with the filling... Wait, we didn't add salt to the dough. Well, let's try to correct our mistake: take a teaspoon of salt and... Oh, how sloppy! All the salt poured into the corner of the future pie (Fig. 1). But this should not confuse us (as, indeed, the fact that the “square” in our drawings “looks” like a right angle). The experience of bakers comes to the rescue: we stretch the square twice horizontally, the mode in half vertically and again make the square as shown in figure 2.

What we did with the square is sometimes called the baker's transformation. Any housewife knows that in this way you can make the dough very homogeneous. But how many times do you think this procedure needs to be repeated so that the salt poured into the corner is distributed almost equally among all the pieces of the future pie - two? Ten? one hundred? a thousand?

Baker transformation geometry. Let's divide the square in half vertically. Let's play the following game: we choose a point in the square and, if after the baker's transformation it ends up in the left half of the square, we win, otherwise we lose.

“A game for kindergarten,” you say. — It is quite obvious that the point must be chosen on two vertical stripes shaded at figure 2, a.

Right. We will have to complicate the rules of the game; Having selected a point, we repeat the baker’s transformation 10 times and only after that we look at which half of the square it falls into. Now the winning strategy column is not visible. To find a set of points for an arbitrary n that, after applying the baker’s transformation n times, ends up in the left half of the square, it is convenient to trace the movement of the point under the influence of the inverse

⟦folio 20⟧

Fig. 3

a baker's transformation, i.e., a baker's transformation carried out in a figurative manner. What it looks like is shown in figure 3. Applying this after repeating the baker's transformation $n$ times. And although the “winning” set is clearly indicated, it is worth making a mistake in determining the abscissa of the point on $2^{-n-1}$ (and this value is quite

transforming several times in a row to a single square, the left half of which is shaded, we get the sequence of pictures shown in figure 4. At the $n$-th step, all vertical stripes of width $2^{-n-1}$ with odd numbers, if counted from left to right, turn out to be shaded. It is these points that will go to the left half of the square

Fig. 4.

20

⟦folio 21⟧

but is small even for small values ​​of n), and we lost. The presence of even a small error makes the game very similar to a toss: after all, the winning set always has an area of ​​1/2, so if you choose a point at random, the probability of winning is also 1/2.

Variation. We have already forgotten that there will be a failed pie in the kitchen. However, time was not wasted. Now we know that fixing the matter is not at all difficult. It is enough to repeat the baker's transformation 15-20 times, and the dough will be salted almost evenly. Let's follow the evolution of the roundly salted section of the pie - figure 5. You can start not only with a square, but also with a figure of any shape. In any case, after a small number of repetitions, the image of this figure will be evenly “smeared” over the square. More precisely, it can be formulated like this. Let us denote the baker's transformation by T,

⟦folio 22⟧

and the paths $A$ and $B$ are two figures of non-zero area lying inside the square, for example two polygons. Then, as $n$ increases, the ratio of the areas $(T^n(A) \cap B)/$ to the areas $(A)$ tends to the fraction of the area of ​​the set $B$ from the area of ​​the entire square. This means that for large $n$ the chances of getting from $A$ to $B$ in $n$ steps under the influence of $T$ practically do not depend on $A$, i.e. on the initial position of the point, but the set $B$ depends only on the area.

The property we have formed is called *change*. It means that any figure spreads evenly over the square over time.

**Some formulas.** I would like to learn how to describe the baker's transformation using formulas. The halving involved in the definition of transformation suggests that a dual number system may be useful in such a description. Recall that each number $\alpha$ from the interval $[0;1)$ can be written as $0, \alpha_1 \alpha_2 \alpha_3...$, where each $\alpha_i$ is equal to 0 or 1. This notation means that $\alpha = \alpha_1/2 + \alpha_2/2^2 + \alpha_3/2^3 +...$; for example, 1/2 can be written in the double system as 0.1, and 1/3 as 0.010101... The geometric meaning of such a notation follows. Divide the interval $[0;1)$ in half. If $\alpha_1 = 0$, then the number $\alpha$ lies in the left half of the interval: $[0;1/2)$, and if $\alpha_1 = 1$, then in the right half: $[1/2;1)$. Let $\alpha_1 = 0$ for definiteness. Then $\alpha_2$ indicates in which half of the interval $[0;1/2)$ lies $\alpha$ - on the left ($\alpha_2 = 0$) or on the right ($\alpha_2 = 1$). All other double entry digits have a similar meaning.

**Exercises**

1. Prove that $1/3 = 0,010101$...

Hint: use the formula for the sum of an infinite geometric progression: $q + q^2 + q^3 +... = q/(1-q)$.

2. Write 1/7 as a double fraction.

3. Write 0.110110110... as an objective fraction.

Let's take the point $m$ in the unit square $K = \{(x;y):0 \leqslant x < 1, 0 \leqslant y < 1\}$ with coordinates $(x;y)$, written in double form: $x = 0, x_1 x_2..., y = 0, y_1 y_2...$. Let's see how the double notation of the coordinates of the point $m$ changes if the baker's transformation is applied to it. If $x_1 = 0$, i.e. $m$, is located in the left half of the square, then its abscissa will double. It is for this reason that we prefixed the double notation of the decimal number: in the decimal number system it is very simple to multiply fractions by 10 - just move the fraction relative to the decimal point to the left by 1 position, and in the double exact number system multiplication by 2 works the same way.

So, the abscissa of the point $T(m)$ is equal to 0, $x_2 x_3...$. If $x_1 = 1$, then at the first stage of the baker’s transformation (Fig. 2, b) the point $m$ will go to the point with the abscissa $1, x_2 x_3...$, and after cutting (Fig. 2, e) it will move by 1 to the left, so in this case the abscissa of the point $T(m)$ is equal to 0, $x_2 x_3...$. Let us now follow the change in the ordinate of the point $m$. At the first stage, it will be halved: $y \rightarrow 0,0 y_1 y_2...$, and then either remain unchanged (at $x_1 = 0$) or increase by 1/2 (at $x_1 = 1$). This means that we can write that the ordinate of the point $T(m)$ is equal to 0, $x_1 y_1 y_2...$. For clarity, let’s write the coordinates of point $m$ in one line as follows:

$$m \leftrightarrow (\dots y_3 y_2 y_1, x_1 x_2 x_3...).$$
