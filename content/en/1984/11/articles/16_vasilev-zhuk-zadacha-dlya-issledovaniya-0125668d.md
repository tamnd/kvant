---
id: 1984-11-vasilev-zhuk-zadacha-dlya-issledovaniya-0125668d
issue: kvant_1984_11
year: 1984
number: "11"
title: Research problem
authors:
  - Васильев Н. Б.
  - Жук И. К.
rubric: smes
page_first: 45
page_last: 45
page_labels: "43"
tag: XAU9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 47feb6b835b3a70a6345cdf9e48a03d03ee1db35438ad5a8b27398ee884ba20b
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/16_vasilev-zhuk-zadacha-dlya-issledovaniya-0125668d.md
source_content_sha256: 4995b347d2fe04ed00c271d86579e9aeb1e93d4c4ce40d4e43c95ada8a654940
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

$$y_{AM}(x_A) = 0 \Rightarrow x_A = -\frac{1}{2g \text{tg} \varphi} (\text{tg} \alpha - \text{tg} \varphi)^2 v_0^2 \cos^2 \alpha.$$

Thus, if a body is thrown at an angle $\alpha > \varphi$, then the shadow travels the path (see (2))

$$S_2 = \frac{1}{g} v_0^2 \sin 2\alpha + \frac{1}{g \text{tg} \varphi} (\text{tg} \alpha - \text{tg} \varphi)^2 v_0^2 \cos^2 \alpha.$$

Let's see at what values ​​of $\alpha$ this expression is maximal. To do this, we find the derivative $S'(\alpha)$ and equate it to zero:

$$S'(\alpha) = \frac{2}{g} v_0^2 \cos 2\alpha + \frac{1}{g \text{tg} \varphi} v_0^2 (\sin 2\alpha + 2 \text{tg} \varphi \cos 2\alpha - \text{tg}^2 \varphi \sin 2\alpha) = 0,$$

or

$$(1 - \text{tg}^2 \varphi) \sin 2\alpha = 0 \Rightarrow \sin 2\alpha = 0 \Rightarrow \alpha = 90^\circ$$

(case $\alpha = 0$ does not suit us, since $\alpha > \varphi$).

Therefore, $S_2$ is maximum at $\alpha = 90^\circ$, that is, when the body is thrown vertically upward, and (see Fig. 4)

$$S_{2\max} = 2h_{\max} \text{ctg} \varphi = \frac{1}{g} v_0^2 \text{ctg} \varphi.$$

Now we find out under what conditions $S_{2\max} > S_{1\max}$ and under what $S_{2\max} < S_{1\max}$. To do this, we find the relation $S_{1\max}: S_{2\max}$ (see (1)):

$$\frac{S_{1\max}}{S_{2\max}} = \frac{v_0^2 g \sin 2\varphi}{v_0^2 g \text{ctg} \varphi} = 2 \sin^2 \varphi.$$

At $\varphi = 45^\circ$ this expression is equal to 1 ($S_{1\max} = S_{2\max}$) - the shadow travels the same paths at $\alpha = 45^\circ$ and at $\alpha = 90^\circ$. If $\varphi < 45^\circ$, then $2 \sin^2 \varphi < 1$ ($S_{1\max} < S_{2\max}$) - the shadow travels the maximum path at $\alpha = 90^\circ$. At $\varphi > 45^\circ$, as we have already said, $S_{1\max} = \frac{1}{g} v_0^2$, and $S_{1\max}: S_{2\max} = \text{tg} \varphi > 1$ - the shadow travels the maximum path at $\alpha = 45^\circ$.

Let's write down the final answer:

if $\varphi < 45^\circ$ - the body must be thrown vertically;
if $\varphi = 45^\circ$ - the body must be thrown either vertically or at an angle $45^\circ$ to the horizon;
if $\varphi > 45^\circ$ - the body must be thrown at an angle $45^\circ$ to the horizon.

V. A. Nakhshin

Problem
for research
"product of neighboring numbers"
in table of ±1

In connection with two problems of this year’s All-Union Olympiad (No. 5 for grade 10 and No. 8 for grade 9; see pp. 47-48), the following more general questions naturally arise.

For each table $T$ of size $m \times n$, the cells of which contain the numbers 1 and -1, defining a new table $P(T)$; in each of its cells a number is written equal to the product of the numbers in the neighboring (sharing a common side with it) cells in table $T$. For each $m$ and $n$:

1) Do different tables $T$ necessarily correspond to different tables $P(T)$?

2) for any table $T$ in the sequence of tables $T_1 = P(T)$, $T_2 = P(T_1)$, ... will there be a table of one?

Try to answer these questions (apparently

I think simpler) as follows:

the “cylindrical” table $m \times n$, in which two opposite sides of length $m$ are considered glued, and for the “torus”, in which two pairs of opposite sides are considered glued (each with four neighboring ones).

Note that question 2) is for a cylinder. heights $m = 1$, that is, for $n$ cells along the circumference, understands the “Quantum problem”; a positive answer to it is obtained at $n = 2^k$ ($k = 2,3,...$).

N. V. Vasiliev, I. K. Zhuk
