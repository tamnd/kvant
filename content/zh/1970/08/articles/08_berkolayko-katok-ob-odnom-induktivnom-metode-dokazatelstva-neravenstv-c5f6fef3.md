---
id: 1970-8-berkolayko-katok-ob-odnom-induktivnom-metode-dokazatelstva-neravenstv-c5f6fef3
issue: kvant_1970_8
year: 1970
number: "8"
title: 一种证明不等式的归纳法
authors:
  - Берколайко С. Т.
  - Каток С. Б.
rubric: raznoe
page_first: 35
page_last: 38
page_labels: 33, 34, 36
tag: 77TL
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 3f7b31c468253ea5c010c86cfd3861f310ba7985407297e717e5ef670ae832a4
prompt_sha256: draft-1
translated_from: content/ru/1970/08/articles/08_berkolayko-katok-ob-odnom-induktivnom-metode-dokazatelstva-neravenstv-c5f6fef3.md
source_content_sha256: 6f4d9a2f9d09e38d95b6d58331bf71718fc154ce47859013578e568aa504621a
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

证明不等式的一种归纳法

S.T.贝尔科莱科，
S.B.溜冰场

算术平均和几何平均定理，该定理指出，对于任何正 $x_1, x_2, \dots, x_n$ 不等式

$$\frac{1}{n} (x_1 + x_2 + \dots + x_n) \geq \sqrt{x_1 x_2 \dots x_n},$$

是数学事实之一，其证明比其公式更不为人所知。 （此类的其他例子：在算术中 - 将数字分解为质因数的唯一方法；在几何中 - 三角形的高相交于一点的定理。）同时，有许多不同的方法可以证明这种显着的不等式，包括基本的方法（例如，在[1]（问题268的解决方案）中给出了3个基本证明，在[5]的开头提出了12个不同的证明）。本注释提供了另一个简短的归纳证明，它也适用于其他正不等式。

我们必须证明

$$x_1 + \dots + x_n \geq n (x_1 \dots x_n)^{\frac{1}{n}}$$

(1)

对于所有整数 $n \geq 2$ 和正数 $x_1, \dots, x_n$。

对于 $n=2$，这个不等式如下所示：

$$x_1 + x_2 \geq 2 (x_1 x_2)^{\frac{1}{2}}$$

(2)

并立即从明显的不等式得出

$$(x_1^{\frac{1}{2}} - x_2^{\frac{1}{2}})^2 \geq 0.$$

让我们假设不等式 (1) 对于 $n=k$ 成立，并针对 $n=k+1$ 证明它。

为此，请考虑以下表达式：

$$x_1 + x_2 + \dots + x_k + x_{k+1} + (k-1) (x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}.$$

将此总和分为两项 $k$ 项，并估计其中的哪一项，对 $n=k$ 应用不等式 (1)：

$$x_1 + x_2 + \dots + x_k \geq k (x_1 \dots x_k)^{\frac{1}{k}},$$

$$x_{k+1} + (k-1) (x_1 \dots x_{k+1})^{\frac{1}{k+1}} \geq k (x_{k+1} x_1^{\frac{k-1}{k+1}} \dots x_{k+1}^{\frac{k-1}{k+1}})^{\frac{1}{k}}.$$

我们将$(k-1) (x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}$视为$(k-1)$相同项$(x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}$的总和。

⟦folio 34⟧

将不等式(2)代入上述两个不等式的右边，我们得到

$$k \left(x_1 \dots x_k\right)^{\frac{1}{k}} + k \left(x_{k+1} x_1^{\frac{k-1}{k+1}} \dots x_k^{\frac{k-1}{k+1}}\right)^{\frac{1}{k}} \geq 2k \left(x_1 \dots x_{k+1}\right)^{\frac{1}{k+1}},$$

在哪里

$$x_1 + x_2 + \dots + x_{k+1} \geq (k + 1) \left(x_1 x_2 \dots x_{k+1}\right)^{\frac{1}{k+1}}.$$

为了感受这个代数变换，让我们看看 $n=3$ 是什么样的：

$$x_1 + x_2 + x_3 + \left(x_1 x_2 x_2\right)^{\frac{1}{3}} \geq 2 \left(x_1 x_2\right)^{\frac{1}{2}} + 2 \left(x_1^{\frac{1}{3}} x_2^{\frac{1}{3}} x_3^{\frac{4}{3}}\right)^{\frac{1}{2}} \geq$$

$$\geq 2 \cdot 2 \left[ \left(x_1 x_2\right)^{\frac{1}{2}} \left(x_1^{\frac{1}{3}} x_2^{\frac{1}{3}} x_3^{\frac{4}{3}}\right)^{\frac{1}{2}} \right]^{\frac{1}{2}} \geq 4 \left(x_1 x_2 x_3\right)^{\frac{1}{3}},$$

从哪里$x_1 + x_2 + x_3 \geq 3 \left(x_1 x_2 x_3\right)^{\frac{1}{3}}$。这里使用了三次不等式(2)。

大致以同样的方式可以证明以下不等式：

a) $a_1^p + a_2^p + \dots + a_n^p \geq n \left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^p$,

其中$n$和$p$是自然数，$a_i > 0$ ($i = 1, 2, \dots, n$)；

b) $\sin \alpha_1 + \sin \alpha_2 + \dots + \sin \alpha_n \leq n \sin \left(\frac{\alpha_1 + \alpha_2 + \dots + \alpha_n}{n}\right)$,

其中 $0 < \alpha_i < \frac{\pi}{2}$ ($i = 1, 2, \dots, n$);

b) $\sin \alpha_1 \sin \alpha_2 \dots \sin \alpha_n \leq \sin^n \left(\frac{\alpha_1 + \alpha_2 + \dots + \alpha_n}{n}\right)$,

其中 $0 < \alpha_i < \frac{\pi}{2}$ ($i = 1, 2, \dots, n$);

d) $\frac{1}{a_1^p} + \frac{1}{a_2^p} + \dots + \frac{1}{a_n^p} \geq \frac{n}{\left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^p}$,

其中$p$和$n$是自然数，$a_i > 0$ ($i = 1, 2, \dots, n$)；

e) $(a_1 + b_1) (a_2 + b_2) \dots (a_n + b_n) \geq \left(\sqrt[n]{a_1 a_2 \dots a_n} + \sqrt[n]{b_1 b_2 \dots b_n}\right)^n$,

其中 $a_i > 0, b_i > 0$ ($i = 1, 2, \dots, n$)。

⟦folio 36⟧

换句话说，仅证明 $n=2$ 所需的不等式。

而如果我们证明函数$\lg x$的上凸性（这是不等式（2）证明的证据），那么从我们的定理，作为特例之一，我们得到一个关于算术平均数和几何平均数的定理：

$$\lg \left( \frac{x_1 + \ldots + x_n}{n} \right) \leq \frac{\lg x_1 + \ldots + \lg x_n}{n},$$

IE。

$$\lg \left( \frac{x_1 + \ldots + x_n}{n} \right) \leq \lg \left( x_1 \ldots x_n \right)^{\frac{1}{n}}, \quad \frac{1}{n} \left( x_1 + \ldots + x_n \right) \leq \left( x_1 \ldots x_n \right)^{\frac{1}{n}}.$$

总之，我们将提供一个书籍清单，您可以在其中阅读算术平均和几何平均定理的其他证明。

[1] D. O. Shklyarsky、N. N. Chentsov、I. M. Yaglom，初等数学问题和定理精选，第一部分，M.，“Nauka”，1965 年。

考虑本书中给出的三个证明中的第一个（“通过反向指示”）。

[2] Kretschmar，代数问题书。 M.，《科学》，1968 年。

[3] E. Beckenbach 和 R. Belman，《不平等导论》，M.，“Mir”，1965 年。

[4] G. G. Hardy、D. E. Littelwood、G. Polyana，不平等，伊利诺伊州，1948 年。

[5] E. Beckenbach 和 R. Belman，不平等，M.，“世界”，1965 年。

练习

1. 如果我们将该定理应用于函数$y=x^2$，会产生什么不等式？尝试直接证明这个不等式。

2. 由一般定理不等式 a)-e) 导出。为此需要证明哪些函数是凸的？

3. 再举出几个凸函数的例子，并写下定理 1 应用于这些函数时得出的不等式。

4. 函数 $f$ 在区间 $[a, b]$ 上定义，并具有反函数 $g$。证明如果$f$向上凸，则$g$向下凸，反之亦然。

5. 定义在区间 $[a, b]$ 上的函数 $f(x)$ 是向上凸的。证明对于线段 $[a, b]$ 上的任何点 $x_1, \ldots, x_n$ 和任何正点 $a_1, \ldots, a_n$，以下不等式成立：

$$\frac{a_1 f(x_1) + \ldots + a_n f(x_n)}{a_1 + \ldots + a_n} \leq f\left(\frac{(a_1 x_1 + \ldots + a_n x_n)}{a_1 + \ldots + a_n}\right).$$

（请注意，这个问题是先前证明的定理的推广，该定理是针对 $a_1=a_2=\ldots=a_n=1$ 获得的。）

笔记。为了解决这个问题，您可以使用我们在证明定理时使用的相同技术。

*) 您可以对任何大于一的底数取对数。
**) 参见«Kvant»，第 1 号，第 22 页。
