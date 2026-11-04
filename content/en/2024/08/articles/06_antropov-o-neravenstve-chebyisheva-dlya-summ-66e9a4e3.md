---
id: 2024-8-antropov-o-neravenstve-chebyisheva-dlya-summ-66e9a4e3
issue: kvant_2024_8
year: 2024
number: "8"
title: On Chebyshev's inequality for sums
authors:
  - Антропов А. В.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 34
page_labels: "29"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0a0aada181690b7b9935ba115e51547ad41c810959df2fe945221fe4659588fe
prompt_sha256: draft-1
translated_from: content/ru/2024/08/articles/06_antropov-o-neravenstve-chebyisheva-dlya-summ-66e9a4e3.md
source_content_sha256: cba10298d060b51d77d8db37eda3842c379cca16dfc4cd69e02d17d440c497ef
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 29⟧

---
running_head:
folio:
---

About inequality
Chebyshev
for amounts
A. ANTROPOV

IN THIS ARTICLE WE WILL REMEMBER
about the remarkable Chebyshev inequality, let’s talk about its different variations and interpretations, and also give the solution problem M2797 “Quantum Problem” (more precisely, let us note that, in essence, the inequality given in the problem is a special case of Chebyshev’s inequality).

The first Chebyshev inequality for sums.
Let the given non-negative numbers $p_1, p_2, \dots, p_n$ such that $p_1 + p_2 + \dots + p_n = 1$, and two ordered sets of real numbers $a_1 \leq a_2 \leq \dots \leq a_n$, $b_1 \leq b_2 \leq \dots \leq b_n$. Then
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n. \tag{1}$$

"What?! This is not Chebyshev’s inequality!” – the reader can take advantage of the exception. Indeed, in optimal folklore the following inequality is usually called the Chebyshev inequality for sums.

Second Chebyshev inequality for sums.
For ordered sets $a_1 \leq a_2 \leq \dots \leq a_n$, $b_1 \leq b_2 \leq \dots \leq b_n$ satisfied
$$\frac{a_1 + a_2 + \dots + a_n}{n} \cdot \frac{b_1 + b_2 + \dots + b_n}{n} \leq
\leq \frac{a_1 b_1 + a_2 b_2 + \dots a_n b_n}{n}. \tag{2}$$

It is easy to see that weight inequality (1) is a generalization of inequality (2): it suffices to set $p_1 = p_2 = p_3 = \dots = p_n = \frac{1}{n}$.

On the other hand, the following exercise shows that in some senses inequality (1) can be reduced to inequality (2).

Exercise 1. Derive inequality (1) from inequality (2) if $p_1, p_2, \dots, p_n$ are rational.

Note. Let $p_i = m_i / m$, $i = 1, 2, \dots, n$. Unwind for inequality (2) set
$$a_1 = a_1 = \dots = a_1 \leq a_2 = a_2 \leq \dots \leq a_n = a_n,$$
in which there are $m_1$ copies of $a_1$, $m_2$ copies of $a_2$, etc.

Before proving inequality (1), we will show how to use it to solve problem M2797.

First, let's make a general remark.

Comment. Let in inequality (1) all be $a_i \geq 0$ and $b_i \geq 0$. Then it remains true if in the conditions we replace the equality $p_1 + p_2 + \dots + p_n = 1$ with the inequality $p_1 + p_2 + \dots + p_n \leq 1$.

Indeed, let $p = p_1 + p_2 + \dots + p_n \geq 0$ (in the case of $p_1 + p_2 + \dots + p_n = 0$ all $p_i$ are equal to 0 and the inequality is obvious). We put $q_i = \frac{p_i}{p}$, so that $p_1 + p_2 + \dots + p_n = 1$, write inequality (1) with weights $q_i$ and get
$$\frac{p_1 a_1 + p_2 a_2 + \dots + p_n a_n}{p} \cdot \frac{p_1 b_1 + p_2 b_2 + \dots + p_n b_n}{p} \leq
\leq \frac{p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n}{p}.$$

Since the sum $p_i a_i b_i$ is non-negative, and $p \leq 1$, multiplying by $p^2$ gives the required:
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p \left( p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n.$$

The case $p \leq 1$ can also be reduced to $p = 1$ by means of a refinement – ​​by introducing additional variables $a_0 = b_0 = 0$ and an additional weight $p_0 = 1 - \left( p_1 + \dots + p_n \right)$.

Now let's put $p_i = \frac{1}{i(i+1)}$. As extracted, $p_1 + p_2 + \dots + p_n < 1$ for any $n$ (indeed, $p_i = \frac{1}{i} - \frac{1}{i+1}$ and, therefore,
$$p_1 + p_2 + \dots + p_n = \left( 1 - \frac{1}{2} \right) + \left( \frac{1}{2} - \frac{1}{3} \right) + \dots + \left( \frac{1}{n} - \frac{1}{n+1} \right) = 1 - \frac{1}{n+1}).$$

Then, by virtue of the replacement above,
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n.$$

This is the inequality we need. Problem M2797 solved.

⟦folio none⟧

---
running_head:
folio:
---

greater than or equal to the product of their mathematical expectations:
$$\mathbb{E}f \cdot \mathbb{E}g \leq \mathbb{E}(fg).$$
(1")

The essence of this inequality is easier to understand if you know what the correlation of two random variables is. Correlation takes values ​​from $[-1; 1]$ and measures how dependent the quantities are, in particular, if the quantities are independent, then their correlation is zero, and for highly dependent quantities the correlation is close to 1.

Formal correlation is defined as follows. For the values ​​$f$ and $g$, the coefficient cov($f,g$) is introduced - this is the mathematical expectation of the product of deviations of the values ​​$f$ and $g$ from their average values. And the correlation between the values ​​$f$ and $g$ is assumed to be equal
$$\frac{\text{cov}(f,g)}{\sqrt{\text{cov}(f,f)} \cdot \sqrt{\text{cov}(g,g)}}.$$
By temporarily introducing the notations $M_f = \mathbb{E}f$ and $M_g = \mathbb{E}g$, we can write
$$\text{cov}(f,g) = \mathbb{E}\left((f - M_f)(g - M_g)\right).$$
Let's ask ourselves: when is the expression $(f - M_f)(g - M_g)$ positive? The answer is clear: either when both functions $f$ and $g$ are simultaneously greater than their average values, or when both are simultaneously less. Informally speaking, cov($f,g$) measures the degree of similarity of a function.

Let's return to inequality (1"). It turns out that the difference between the right and left sides is equal to

cov($f,g$). Really,
cov($f,g$) = $\mathbb{E}\left((f - M_f)(g - M_g)\right) =
= \mathbb{E}\left(fg - M_fg - M_gf + M_fM_g\right) =
= \mathbb{E}(fg) - M_f\mathbb{E}g - M_g\mathbb{E}f + M_fM_g =
= \mathbb{E}(fg) - \mathbb{E}f \cdot \mathbb{E}g$,

where the penultimate equality follows from the linearity of the mathematical expectation, and the last one follows from the definitions of $M_f$ and $M_g$.

It turns out that Chebyshev's inequality (1') generally reflects a logical message about the similarity of monotonic functions.

In conclusion, for readers familiar with integers, we present a continuous version of Chebyshev’s inequality. In this case, the inequality has the same probability-theoretic meaning and reflects the same informal thesis about the similarity of monotonic functions.

Chebyshev's third inequality (for monotone functions). Let $f(x)u g(x)$ be two non-decreasing (or two non-increasing) functions defining on the interval $[a; b]$. Then
$$\int_a^b f(x)dx \cdot \int_a^b g(x)dx \leq \frac{1}{b-a} \int_a^b f(x)g(x)dx.$$
Exercise 3*.
a) Derive Chebyshev’s inequalities for sums from Chebyshev’s integral inequality.
b) Derive (by passing to the limit from integral sums to an integral) from Chebyshev’s inequality for sums the integral inequality.

(For the beginning, see p. 13)

claims that this is how yellow turns out. So why argue with him?>

I was confused. I didn't know what to say. Finally, I answered, “I have been studying light all my life. And I believe that by mixing red and white, it is impossible to get yellow - you can only get pink.”

So, I went to the hardware store, bought some paint, and brought it back to the restaurant. The painter came down from the second floor, and the owner also came to look. I placed the cans of red on an old chair and the painter began mixing paints. He took red paint, added white - it still seemed to me that the color was pink - he mixed a little more paint. After that, he muttered something in the input: “I usually used a small tube of red paint to enhance the effect - then it would turn out yellow.”

- A! - I said. - Certainly! If you add yellow, you get yellow, but without it nothing will work.

The painter went back to painting the room.

The owner of the restaurant said: “This guy has the audacity to argue with a man who has been studying light all his life!”

From the book “You are certainly a joke, Master Feynman!”

⟦folio none⟧

---
running_head:
folio:
---

Find the fluxion [i.e. derivative] and half-
live it equal to zero.
Isaac Newton
...[derivative] expresses that negation
the point of the path along which the body moves
beyond the distance they will travel
due to his previous movement.
Leonard Euler
All those who love analysis [mathematical] with
will be pleased to see that the mechanics
is becoming a new branch of analysis...
Joseph Louis Lagrange
Don't bother me with your math
Coy: derivative is speed!
William Thomson (Kelvin)

Newton posed a general question: how does the speed of a free body change under the action of an arbitrary given force?... This problem... requires a new mathematical app-
paratha specially created for this purpose
Newton...

Albert Einstein
...the complex process of finding an arbitrary one is also called differentiation. ...When you become more accustomed to new words, the idea itself will become more clear to you.

Richard Feynman
