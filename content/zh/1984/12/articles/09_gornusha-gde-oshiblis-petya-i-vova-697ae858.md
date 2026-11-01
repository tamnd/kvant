---
id: 1984-12-gornusha-gde-oshiblis-petya-i-vova-697ae858
issue: kvant_1984_12
year: 1984
number: "12"
title: Petya和Vova哪里出了问题？
authors:
  - Горнуша П. П.
rubric: shkola-v-kvante
page_first: 24
page_last: 24
page_labels: "22"
tag: 1C4F
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 790a5956c6bd17209c7d0db6464aabf85460624d1621e1a4ea078d3d664daab6
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/09_gornusha-gde-oshiblis-petya-i-vova-697ae858.md
source_content_sha256: 5330ec7836970cc4d8aac0f4d4dd873132606387113f113b28a5781a3b6e83a4
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

数学
8, 9, 10

下面发表的文章《Petya和Vova哪里出了问题？》适合八年级学生，“几何有助于解决方程” - 九年级学生和三面体街道 - 十年级学生。这种划分在某种程度上是任意的，因为这些笔记中的每一个不仅对指定班级的学生有用。

Petya和Vova哪里出了问题？

Petya 和 Vova 两个朋友正在求解最优方程组
$$\begin{cases}
(x^2 - xy + y^2)(x - y) = 1 + y^3, \\
(x^2 + xy + y^2)(x + y) = 1 - y^3.
\end{cases}$$

Petya 将第二个方程替换为方程的乘积：
$$\begin{cases}
(x^2 - xy + y^2)(x - y) = 1 + y^3, \\
(x^3 - y^3)(x^3 + y^3) = 1 - y^6,
\end{cases}$$

那是
$$\begin{cases}
(x^2 - xy + y^2)(x - y) = 1 + y^3, \\
x^6 - y^6 = 1 - y^6.
\end{cases}$$

从第二个方程$x = \pm 1$，我打开它并得到答案：$(1; 0); (-1; -1)$。

Vova 将第一个方程替换为方程的乘积：
$$\begin{cases}
x^6 - y^6 = 1 - y^6, \\
(x^2 + xy + y^2)(x + y) = 1 - y^3,
\end{cases}$$

在哪里
$$\begin{cases}
x = \pm 1, \\
(x^2 + xy + y^2)(x + y) = 1 - y^3.
\end{cases}$$

答案是：$(1; 0); (-1; 1)$。

奥运会结束后，他们深入研究了答案，结果非常惊讶。谁错了？
P.P.戈尔努沙

几何有助于解方程

在某些情况下，您可以执行以下操作，而不是转换方程：将问题翻译成几何语言，然后以不同的方式写出生成的几何条件；结果：简单的方程结果。现在我们考虑两个这样的例子，在每个例子中，原方程都等价于“某些点位于同一条直线上”的条件；通过适当地写出这个条件，我们得到一个更简单的方程，我们将求解该方程。

问题 1. 求解方程 $\sqrt{15 - 12\cos x} + \sqrt{7 - 4\sqrt{3}\sin x} = 4$，其中 $0^\circ < x < 90^\circ$。

解决方案。让我们给出方程的形式：
$$\sqrt{(\sqrt{12})^2 + (\sqrt{3})^2 - 2\cdot\sqrt{12}\cdot\sqrt{3}\cos x} + \sqrt{(\sqrt{3})^2 + 2^2 - 2\cdot\sqrt{3}\cdot2\cdot\cos(90^\circ - x)} = 4.$$ (1)

图 1 显示包含$|AC| = \sqrt{12}, |BC| = 2, ACD = x, DCB = 90^\circ - x; |CD| = \sqrt{3}, |AB| = 4$ 的矩形。 (1) 左边第一项等于$|AD|$，第二项等于$|DB|$。但从$|AD| + |DB| = |AB|$开始，就意味着$D \in [AB]$。因此，该方程可以用方程 $\sqrt{12}\cdot\sqrt{3}\sin x + \sqrt{3}\cdot2\cdot\sin(90^\circ - x) = 2\cdot\sqrt{12}$ (2) 代替

（自$S_{ACD} + S_{DCB} = S_{ACB}$），或
$$6\sin x + 2\sqrt{3}\cos x = 4\sqrt{3},$$

这比原来的问题更容易解决。

我们有：$\frac{\sqrt{3}}{2}\sin x + \frac{1}{2}\cos x = 1$，即$\sin(x + 30^\circ) = 1$，由此而来$x = 60^\circ$。

然后是其他事情。严格来说，需要证明式(2)蕴涵式(1)。让我们展示一下。从方程（2）得出$S_{ACD} + S_{DCB} = S_{ACB}$，因此$|AD| + |DB| = |AB|$，这被写在方程（1）中。

图 1.
图 2.
