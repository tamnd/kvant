---
id: 1991-3-ovsienko-analiz-i-neravenstva-06e3a05e
issue: kvant_1991_3
year: 1991
number: "3"
title: Analysis and inequalities
authors:
  - Овсиенко В. Ю.
rubric: osnovnye-stati
page_first: 17
page_last: 20
page_labels: 15-18
lang: en
source: kvant_digital
extraction: vision
content_sha256: 76641a882f9e38a3fa156040836d71865ffa1389231f79fda84d7b53be3b7fb4
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/04_ovsienko-analiz-i-neravenstva-06e3a05e.md
source_content_sha256: 2f35a29dd075e24fb8d1a98b1ec75356db3dd214be9edd3c298577401661398b
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 15⟧

---
running_head:
folio:
---

ANALYSIS AND
INEQUALITIES

Candidate of Physical and Mathematical Sciences
V. OVSIENKO

Henri Poincaré said that mathematics is a way of saying the same thing about doing different things. This especially applies to mathematical analysis, which, like a master key in the hands of an experienced burglar, provides “universal keys to all doors”...

We will talk about three different tasks that we will solve in the same way. The solution will be based on a statement well known from the school course: if the derivative of a certain function is greater than zero, then this function is increasing (and vice versa, if the derivative is less than zero, then it is decreasing).

Inequalities for sine and cosine

Inequalities

$$\sin x < x,$$
$$\cos x > 1 - \frac{x^2}{2},$$

valid for $x > 0$ (Fig. 1), geometric ones are generally proven (in school). Analytical proof, however, is much simpler and does not require much ingenuity.

Let's start with the first inequality. The function $y_1(x) = \sin x$ and $y_2(x) = x$ are the same in nULE. Therefore, it is enough to prove that at $x > 0$ the second function grows faster than the first (i.e., that $y(x) = x - \sin x$ is an increasing function at $x > 0$). But the derivative of $y'(x) = 1 - \cos x$ is greater than zero at $x > 0$. The inequality has been proven.

To prove the second inequality, we will do exactly the same.

The function $y(x) = \cos x - 1 + \frac{x^2}{2}$ is equal to zero at $x = 0$. Its derivative is $y'(x) = -\sin x + x$. Thus, $y'(x) > 0$ with $x > 0$ (due to the first

⟦folio 16⟧

---
running_head:
folio:
---

inequality!), i.e. the function is increasing and, therefore, positive.

Exercises
1. Prove that for $x > 0$
a) $\sin x > x - \frac{x^3}{6}$,
b) $\cos x < 1 - \frac{x^2}{2} + \frac{x^4}{24}$.

Note. Do as before. After differentiation, use the previous inequalities.
2. Continue the chain of inequalities obtained to sin $x$ and cos $x$.

Inequalities in a triangle

For a triangle with angles $\alpha, \beta, \gamma$ (Fig. 2) the following inequality holds:
$$\sin \alpha + \sin \beta + \sin \gamma \leq \frac{3\sqrt{3}}{2}.$$

Let's prove it. First, note that the equality holds if the triangle is regular ($\alpha = \beta = \gamma = 60^\circ$).

Let the triangle be equilateral and its angles equal to $\alpha = 60^\circ + x, \beta = \gamma = 60^\circ - \frac{x}{2}$, where $x$ is some number such that $-60^\circ < x < 120^\circ$. then the expression $\sin \alpha + \sin \beta + \sin \gamma$ is a function of $x$:
$$f(x) = \sin (60^\circ + x) + 2\sin \left(60^\circ - \frac{x}{2}\right).$$
Her product is $f'(x) = \cos (60^\circ + x) - \cos \left(60^\circ - \frac{x}{2}\right)$. It is clear that $f'(x) > 0$ at $-60^\circ < x < 0$ and $f'(x) < 0$ at $0 < x < 120^\circ$. Therefore, the function $f(x)$ has a maximum at point $x = 0$ and the smaller the further $x$ is from zero.

Now let the function $\alpha$ change the angles $\beta$ and $\gamma$: $\beta = \delta - x$, $\gamma = \delta + x$. Then the original expression will again be a function of $x$:
$$f(x) = \sin (\delta - x) + \sin (\delta + x) + \sin \alpha.$$
Her work is $f'(x) = \cos (\delta + x) - \cos (\delta - x)$. Again, $f'(x)$ is greater than zero for negative $x$ and less than zero for positive $x$. In other words, the more the triangle differs from the equilateral triangle, the smaller the expression $\sin \alpha + \sin \beta + \sin \gamma$.

The inequality is proven because a triangle can be obtained from an equilateral triangle by first changing the angle $\alpha$, and then $\beta$ and $\gamma$. We are convinced that with such a change the expression $\sin \alpha + \sin \beta + \sin \gamma$ will decrease all the time.

Exercise 3. Prove the inequalities
a) $\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$,
b) $\sin \alpha \cdot \sin \beta \cdot \sin \gamma \leq \frac{3\sqrt{3}}{8}$,
b) $\cos \alpha \cdot \cos \beta \cdot \cos \gamma \leq \frac{1}{8}$,
if $\alpha, \beta, \gamma$ is some triangle.

Cauchy's inequality

For any non-negative numbers $a_1, ..., a_n$ the following inequality holds:
$$\frac{a_1 + ... + a_n}{n} \geq \sqrt[n]{a_1 \cdot ... \cdot a_n}$$

between the arithmetic mean and the geometric mean. It is called Cauchy's inequality. We will prove it using the same method, i.e. by calculating an arbitrary function of some function.

To warm up, let's start with the proof of a very simple case $n = 2$.

⟦folio 17⟧

---
running_head:
folio:
---

$\frac{a+b}{2} \geqslant \sqrt{ab}$
proves in a variety of geometric ways (including very beautiful ones). We will work out our method on it. Let for definition $a \leqslant b$. Then $b=a+x$, where $x$ is some non-negative number. The expression $\frac{a+b}{2} - \sqrt{ab}$ becomes a function of $x$, having the form $f(x) = \frac{2a+x}{2} - \sqrt{a(a+x)}$.
For $x=0$ the function is $f(x)=0$, its product is $f'(x) = \frac{1}{2} - \frac{1}{2} \sqrt{\frac{a}{a+x}} > 0$.
Therefore, the function $f(x)$ is increasing, i.e., the arithmetic mean is greater than the geometric mean, the greater the difference $b-a=x$.
Now let's prove Cauchy's inequality in the general case. In fact, this proof is a repetition of the previous one. We only need the value of the derivative of the function $\sqrt[n]{x^k} = x^{\frac{k}{n}}$. It is calculated in the school textbook: $\left( x^{\frac{k}{n}} \right)' = \frac{k}{n} x^{\frac{k}{n}-1}$.
Let for definition $a_1 \leqslant a_2 \leqslant \dots \leqslant a_n$. It is clear that for $a_1 = \dots = a_n$ our inequality turns into equality. We will take $n$ identical numbers $a_1, a_1, \dots, a_1$ and increase them (starting from the second), but not in one step, but in $(n-1)$ steps. In the first step -
$$a_1, a_1+z, \dots, a_1+z$$
(where $a_1+z=a_2$),
in the second step -
$$a_1, a_2, a_2+y, \dots, a_2+y$$
(where $a_2+y=a_3$).
We will end up with a set of numbers $a_1, a_2, \dots, a_n$.
We will prove that at any step the difference between the arithmetic mean and the geometric mean increases

⟦folio 18⟧

---
running_head:
folio:
---

We have been running this section from issue to issue since the founding of the magazine. The problems published in it are non-standard, but their solution does not require knowledge beyond the scope of the school curriculum. The most difficult tasks are marked with asterisks. After creating a task, we usually indicate who proposed it to us. Of course, not all of these problems are published for the first time.
Solutions to the problem from this issue should be sent no later than May 15, 1991 to the address: 103006, Moscow K-6, st. Gorky, 32/1, «Kvant».
Send solutions to problems from different issues of the magazine or in different subjects (mathematics and physics) in different envelopes. On the envelope, in the “To” column, write: “Problem «Kvant» No. 3 - 91” and the numbers of the problems whose solutions you are sending, for example “M1271” or “F1278”.
In the column “...sender’s address”, please write your first and last name separately. Include an envelope with your address written on it (you will receive the results of the decision review in this envelope).
Please send the conditions of each original problem proposed for publication in a separate envelope in duplicate along with your solution to this problem (mark on the envelope: “Problem «Kvant», new problem in physics” or “...new problem in mathematics”).
At the beginning of each letter, please indicate the school number and class in which you will study.
