---
id: 1983-10-pecherskiy-nx-xn-0b008072
issue: kvant_1983_10
year: 1983
number: "10"
title: n^x = x^n
authors:
  - Печерский Л. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 33
page_last: 33
page_labels: "31"
tag: Q8RI
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a718e19a8b219699090c7dc4131a4e4091ab864ddf402632bb39430f062b1b7c
prompt_sha256: draft-1
translated_from: content/ru/1983/10/articles/10_pecherskiy-nx-xn-0b008072.md
source_content_sha256: f1b91d6d0c974a690a22190dc1258b92be3ef24414064fbddb73868bf27eb1f1
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

$$n^x = X^n$$

L·B·佩切尔斯基

如果$n \in \mathbb{N}$和$n \neq 1$，这个方程有多少个根？

有了开根，一切就变得简单明了：如果 $n$ 是偶数，则方程有一个负根（画一张图！）；如果$n$是奇数，则没有这样的根。

将扎下积极的根。该方程强等于方程

$$\ln (n^x) = \ln (x^n),$$
$$x \cdot \ln n = n \cdot \ln x,$$
$$x \cdot \ln n - n \cdot \ln x = 0.$$

函数 $y(x) = x \cdot \ln n - n \cdot \ln x$ 在 $]0; +\infty[$ 上有多少个零*)？

返回 $y'(x) = \ln n - \frac{n}{x}$ 与 $]0; +\infty[$ 的乘积（绘制图表！）。在$x_0 = \frac{n}{\ln n} y'(x_0) = 0$点；这意味着在$]0; x_0[$$y'(x) < 0$，在$]x_0; +\infty[$$y'(x) > 0$。由于函数$y$在点$x_0$处是非素数，因此$x_0$是它的极小点。在$]0; x_0[$，函数$y$减少，在$[x_0; +\infty[$返回。

函数$y$在点$x_0$有什么符号？

$$y(x_0) = n(1 - \ln n + \ln \ln n).$$

为了确定数字 $y(x_0)$ 的符号，我们检查函数 $z(x) = 1 - \ln x + \ln \ln x$。由于$z'(x) = \frac{1 - \ln x}{x \cdot \ln x}$，$x_1 = e$是函数$z$的极大点，在$]1; e]$$z$返回，在$[e; +\infty[$减小。从$z(x_1) = 0$开始，在定义域$z(x) < 0$的其他点；部分位于$n \in \mathbb{N}$、$n \neq 1$$z(n) < 0$。所以，$y(x_0) < 0$。

函数 $y$ 在 $]0; +\infty[$ 上是非素数，它正在递减。由于“接近零”（例如，显然在 $x < 1$）$y(x) > 0$ 和 $y(x_0) < 0$，因此在区间 $]0; x_0[$ 上，函数 $y$ 恰好有一个零（参见 图）。

让我们证明对于“大”$x$（“在无穷大平面上”）$y(x) > 0$。为此，请考虑函数 $u(x) = \frac{x}{\ln x}$。因为$u'(x) = \frac{\ln x - 1}{\ln^2 x}$，$u$返回到$[e; +\infty[$。如果$n \geq 3$，那么在$x > n \geq 3$

$$\frac{x}{\ln x} > \frac{n}{\ln n},$$
$$x \cdot \ln n > n \cdot \ln x,$$
$$x \cdot \ln n - n \cdot \ln x > 0,$$
$$y(x) > 0.$$

亲自证明对于“大”$x$，$n = 2$$y(x) > 0$。

由于$y(x_0) < 0$、$y$在$[x_0; +\infty[$和$y(x) > 0$上返回，对于“大”$x$，在区间$]x_0; +\infty[$上，函数$y$也恰好有一个零（参见图）。

因此，对于$n \geq 2$，标题中的方程在$]0; +\infty[$上有两个根：一个在$]0; x_0[$上，另一个在$]x_0; +\infty[$上。

顺便说一句，它的根源之一：$x = n$ - 非常认同。

入学考试时会遇到某个方程$f(x) = g(x)$的根数问题。通常，给出的方程是代数平均值无法得到的。在这种情况下，检查方程中包含的函数$f$、$g$通常很有用，在这里使用分析工具是很自然的。
