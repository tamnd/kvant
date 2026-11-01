---
id: 1977-4-zadachi-nashih-chitateley-d80e2264
issue: kvant_1977_4
year: 1977
number: "4"
title: Tasks for our readers
rubric: smes
page_first: 25
page_last: 25
page_labels: "23"
tag: 8SCS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3c55619becf497e78dbabba9877002630b58bb0bea4810d7313dc7c24f00e1b8
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/08_zadachi-nashih-chitateley-d80e2264.md
source_content_sha256: 3b16dc4764931a13b029522d195f8d4951c21c7b42a79d8c9b0c35114ff53c88
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

If $v \neq w$, then using the transformation
$$\langle v, w \rangle \Rightarrow \langle 2v - w, w - v \rangle$$
Let's move from this pair to the pair $\langle v_1, w_1 \rangle$ with smaller components. If $v_1 \neq w_1$, then we will perform this transition again. If $v_2 \neq w_2$, again...
Each time we will get pairs of smaller natural numbers. Therefore, after a finite number of steps we will get a pair $\langle v_l, w_l \rangle$ of identical numbers - according to our rules, the process can only be terminated at such a pair. But, as we already know, then $v_l = w_l = 1$. Let us now note that transitions (*) and (**) are mutually inverse: if $v = 2v - w$, $w = w - v$, then $v = v + w$, $w = v + 2w$. Therefore, our pair $\langle v, w \rangle$ can be obtained from the pair $\langle 1, 1 \rangle$ using (*) in $l$ steps, that is, $\langle v, w \rangle = \langle v_l, w_l \rangle$.

So, the set of solutions to equation (7) consists of pairs $\langle \gamma_{2k-1}, \gamma_{2k} \rangle$.

3. Now we can summarize: $u_k = v_k + w_k = \gamma_{2k+1}$, which means $x_k = u_k v_k = \gamma_{2k} \gamma_{2k+1}$, $y_k = v_k w_k = \gamma_{2k-1} \gamma_{2k}$. The theorem has been proven.

4. One final note. If we want to check our solution and see which $k$ corresponds to line 14, then it turns out that $k = 2$. What does $k = 1$ correspond to? Did we get an extra solution? $k = 1$ corresponds to the equality $C_0^2 = C_1^1$, but three numbers in a row do not seem to be visible. However, in fact they exist, it’s just that the first one - zero - is not written.

Historical information. The equation under consideration has already been found in the mathematical literature, although in a slightly different form. (The American Mathematical Monthly, vol. 37, p. 508, author of the problem - Norman Anning.) Its solution, published in volume 38, p. 351, has nothing in common either in the methods or in the form of the answer with the solution given in this note.

Our Readers' Assignment

1. Two identical automatic cars are driving along the road at the same speed. However, the machine is carrying a heavy load, while the other is empty. If a car starts to slow down at the same time so that it starts spinning (their wheels won’t spin), then which one will stop first?

B. Coan (Moscow)

2. However, the rod is fixed at the center of gravity so that it can easily rotate in a vertical plane. Identical weights are attached to the ends of the rod. Such a system is in a state of equilibrium in any position. And lever scales, on both parts of which there are identical loads, are installed only horizontally. Why do you think?

E. Gudesblam (Odessa)

3. Prove that if in a triangle $ABC$ for the length $a, b, c$ of its sides the inequalities $c > b > a$ and $\beta_A, \beta_B, \beta_C$ are satisfied—the lengths of bissertrises within the heads, $\beta_A', \beta_B', \beta_C'$—the lengths of the heights, then the following equality is valid:

$$\frac{1}{a \beta_A \beta_A'} + \frac{1}{c \beta_C \beta_C'} = \frac{1}{b \beta_B \beta_B'}$$

6) $$\frac{h_a}{\beta_A \beta_A'} + \frac{h_c}{\beta_C \beta_C'} = \frac{h_b}{\beta_B \beta_B'}$$

U. Alla (Võru)
