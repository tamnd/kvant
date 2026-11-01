---
id: 1982-6-byistryiy-o-sokraschenii-pokazateley-3bb7848f
issue: kvant_1982_6
year: 1982
number: "6"
title: About reducing indicators
authors:
  - Быстрый И. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 42
page_labels: "40"
tag: U0X8
lang: en
source: kvant_digital
extraction: vision
content_sha256: ac73dab6d0e3dc3f035353a201d497895c30b101452c790ff1ba380aca0d78a1
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/11_byistryiy-o-sokraschenii-pokazateley-3bb7848f.md
source_content_sha256: 97d0817ea44aadd3d1e3f65dcc81eab0db92e29c280e004bc19d4e30c7e9735b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

About reducing indicators

In the current textbook “Algebra 8” (M., “Prosveshchenie”, editions 1979 and later), the nth root of a is a number whose nth degree is equal to a. (Here n is an arbitrary natural number, in part 1.) Therefore, a positive number a with even n has two roots of the nth degree of a - positive (it is denoted by $\sqrt{a}$) and negative (-$\sqrt{a}$). For odd n, any number a has one root (denoted by $\sqrt{a}$). Finally, for any natural number n $\sqrt{0} = 0$.

Reducing exponents for non-negative a does not cause any difficulties: $\sqrt[n]{a^m} = \sqrt[n]{a^m}$ (clause 26 of the mentioned manual). But for arbitrary a (particularly when a is an expression containing a variable), the situation is more subtle. You know well that $\sqrt{a^2} = |a|$ (here m=n=1, k=2). In the general case,

$$\sqrt[n]{a^m} = \begin{cases} \sqrt[n]{|a|}^m, \text{ если } mk \text{ четно и } m \text{ нечетно} \\ \sqrt[n]{a^m} \text{ во всех остальных случаях} \end{cases}$$

For example, $\sqrt[4]{a^2} = \sqrt{|a|}$ and $\sqrt[6]{a^2} = \sqrt[3]{|a|}$ (the equality $\sqrt[6]{a^2} = \sqrt[3]{a}$ is true only for a≥0, although both expressions $\sqrt[6]{a^2}, \sqrt[3]{a}$ are defined for any a!).

Let us show how the rule for reducing exponents is applied using the example of a system of irrational equations

$$\begin{cases} \sqrt{x+y} + \sqrt[3]{x-y} = 6 \\ \sqrt[6]{(x+y)^3(x-y)^2} = 8 \end{cases}$$

For any x and y, we obtain two solutions to system (5): (12; 4), (34; -30).

Solving the auxiliary system

$$\begin{cases} u+v = 6 \\ u \cdot v = 8 \end{cases}$$

we obtain two solutions: $u_1 = 4$, $v_1 = 2$ and $u_2 = 2$, $v_2 = 4$. Solving systems

$$\begin{cases} \sqrt{x+y} = 4 \\ \sqrt[3]{x-y} = 2 \end{cases}$$

has no solutions (why?),

$$\sqrt[3]{(x+y)^3(x-y)^2} = \sqrt[6]{(x+y)^3(x-y)^2}$$

Amendment

In the article by L. Pontryagin “Complex numbers” («Kvant», 1982, No. 3), due to the fault of the editor, typos were introduced into the proof of formula (11), making it difficult to understand. We freely formulate this part of the proof (p. 5-6): “From formula (9) it follows without precedence

$$iz = i \cdot (x+iy) = x \cdot i + y(-1) = xR_d(1) + yR_d(i) = R_d(x \cdot 1 + y \cdot i) = R_d(x+iy) = R_d(z).$$

Thus, formula (11) is proven for a = $\frac{\pi}{2}$.

Let now a be an arbitrary real number. For z = cos a + i sin a we get

$$z \cdot i = i \hat{z} = R_d(\hat{z}) = R_d(\cos a + i \sin a) = \cos(a + \frac{\pi}{2}) + i \sin(a + \frac{\pi}{2}) = R_a(\cos \frac{\pi}{2} + i \sin \frac{\pi}{2}) = R_a(i).$$

Thus, formula (11) is proven for z = i. In addition, in the article by the same author “The Fundamental Theorem of Algebra” («Kvant», 1982, No. 4), due to the fault of the printing house on p. 9 printed $f(z) = f(\bar{z})$ together correctly $f(z) = f(\bar{z})$.
