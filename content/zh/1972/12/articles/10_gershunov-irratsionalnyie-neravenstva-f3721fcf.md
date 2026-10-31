---
id: 1972-12-gershunov-irratsionalnyie-neravenstva-f3721fcf
issue: kvant_1972_12
year: 1972
number: "12"
title: 非理性的不平等
authors:
  - Гершунов Е. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 52
page_labels: 49-50
tag: 2ERT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 961f4ab56a28578336e4e2f9920fa576d9ca675a3f20092f0fb211d8f1896a03
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/10_gershunov-irratsionalnyie-neravenstva-f3721fcf.md
source_content_sha256: 5c7afdf3eed208611ead835628c935cc1c612e3d9805aa743d6b91c642c0eab1
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

非理性不平等

E·M·格舒诺夫

在大学入学考试中，越来越多的例子或问题被提供，其主要或构成要素是根号下包含未知量的不等式（无理不等式）。实践表明，大多数申请者很难解决非理性不平等问题。显然，其原因是学校课程和数学教科书不包含这个主题。

本文并不完整涵盖与解决非理性不平等相关的所有问题。这里的主要焦点是解决涉及二次根式的无理不等式。

让我们首先证明以下定理，该定理在解决无理不等式中起着重要作用。

定理。如果$f(x) \geq 0$和$\partial(x) \geq 0$，则不等式$f(x) \geq g(x)$和$[f(x)]^2 \geq [g(x)]^2$是等价的。

证明。我们需要确定差异的符号

$$[f(x)]^2 - [g(x)]^2.$$ (1)

我们将 (1) 分解为因子：

$$[f(x)]^2 - [g(x)]^2 = [f(x) + g(x)][f(x) - g(x)].$$ (2)

右侧第一个因子根据条件为非负数。如果为正，则差值 (1) 的符号与 (2) 中第二个因子的符号一致，如果 $f(x) + g(x) = 0$，则$f(x) = 0$ 和 $g(x) = 0$，并且不等式再次相等。

很容易证明，如果非严格不等式$\geq$的所有符号都替换为

穿在严格不等号$>$上（自己证明）。

示例 1. 解决不等式

$$\sqrt{4 + 3x - x^2} < 2.$$

解决方案。首先我们定义OD3：$-1 \leq x \leq 4$。不等式的左边是非负的，右边是正的，所以让我们两边都平方。我们得到一个等价的不等式系统

$$\begin{cases} -1 \leq x \leq 4, \\ 3x - x^2 < 0, \\ -1 \leq x \leq 4, \\ x > 3, x < 0. \end{cases}$$

答案：$3 < x \leq 4$，$-1 \leq x < 0$。

示例 2：解决不等式

$$\sqrt{4 + 3x - x^2} > -2.$$

解决方案。 OD3 相同：$-1 \leq x \leq 4$。请注意，在 OD3 中，不等式的左侧为非负，右侧为负，因此无法证明该定理。但这是没有必要的。事实上，根式具有算术值，因此，它在 OD3 中的任何值都满足这个不等式。因此答案是$-1 \leq x \leq 4$。

示例 3. 解决不等式

$$\sqrt{x^2 - 5x + 4} < x - 3.$$

解决方案。 OD3：$x \geq 4$，$x \leq 1$。由于右侧包含未知量，我们将依次考虑两种情况：

1) $x - 3 > 0$, $2) x - 3 \leq 0$.

在第一种情况下我们将使用

⟦folio 50⟧

证明定理并获得等价系统
$$\begin{cases} x \geq 4, & x \leq 1, \\ x - 3 > 0, \\ x^2 - 5x + 4 < (x - 3)^2, \end{cases}$$

从哪里$4 \leq x < 5$。

在第二种情况下，原始不等式无解，因为根的算术值不能小于非正数。

答案：$4 \leq x < 5$。

示例 4. 解决不等式
$$\sqrt{x^2 - 5x - 24} > x - 2.$$

解决方案。 ODZ：$x \geq 8, x \leq -3$。让我们考虑两种情况：1) $x - 2 \geq 0$，2) $x - 2 < 0$。

在第一种情况下，右边是非负的，利用该定理，我们得到一个不等式组
$$\begin{cases} x \geq 8, & x \leq -3, \\ x - 2 \geq 0, \\ x^2 - 5x - 24 > (x - 2)^2, \end{cases}$$

没有解决方案。

在第二种情况下，根据偶次根的定义，原始不等式在整个允许值范围内得到满足。解决系统
$$\begin{cases} x - 2 < 0, \\ x \geq 8, x \leq -3, \end{cases}$$

我们找到答案：$x \leq -3$。

示例 5. 解决不等式
$$\sqrt{x - 2} + \sqrt{x - 1} > \sqrt{x + 3}.$$

解决方案。 ODZ：$x \geq 2$。由于不等式两边均为正，利用主定理，我们得到等价的等式系统
$$\begin{cases} x \geq 2, \\ 2 \sqrt{(x - 1)(x - 2)} > 6 - x. \end{cases}$$

我们通过考虑两种情况来解决这个系统：
$$\begin{cases} x \geq 2, \\ 6 - x \geq 0, \\ 4(x^2 - 3x + 2) > (6 - x)^2, \end{cases}$$

从哪里$\sqrt{\frac{28}{3}} < x \leq 6$，和
$$\begin{cases} 6 - x < 0 \\ x \geq 2 \end{cases}$$

从哪里$x > 6$。

答案：$x > \sqrt{\frac{28}{3}}$。

示例 6. 解决不等式
$$\frac{\sqrt{x^2 - x - 2}}{x^2 + 2x + 3} > 0.$$

解决方案。 ODZ 由自由基的存在条件确定：$x \geq 2, x \leq -1$。在 $x > 2, x < -1$ 处，分数的分子取正值，因此我们继续使用等效系统
$$\begin{cases} x > 2, x < -1, \\ x^2 + 2x + 3 > 0. \end{cases}$$

对于$x$的任何实数，系统的第二个不等式都满足，由此我们得到答案：$x > 2, x < -1$。

练习

解决不等式：
1. $\frac{x - 7}{\sqrt{4x^2 - 19x + 12}} < 0$.
2. $x < \sqrt{2 - x}$.
3. $x + 1 > \sqrt{x + 2}$.
4. $\sqrt{4 + 3x - x^2} < x - 1$.
5. $\sqrt{2x^2 - 8x + 7} < x - 2$.
6. $\sqrt{\frac{4}{x^2} - \frac{3}{4}} > \frac{2}{x} - 1$.
7. $\sqrt{2x - 6} + \sqrt{x + 4} > 5$.
8. $\sqrt{\frac{x + 1}{2 - x}} < 3$.
9. $\frac{1 - \sqrt{1 - 8x^2}}{2x} < 1$.
10. $\sqrt{x^2 - 3x + 2} > 2 - x$.
11. $\sqrt{\sin x} + \sqrt{\cos x} > 1$.
12. $\frac{2x}{\sqrt{2x + 9}} < \sqrt{2x + 1} - 1$.
13. $(x - 3)\sqrt{x^2 + 4} \leq x^2 - 9$.
14. $\sqrt{x^2 - 16} / |x| - |x - 2| < 0$.
