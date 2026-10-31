---
id: 1972-9-vahovskiy-volyinskiy-nauchimsya-obraschatsya-s-absolyutnoy-velichinoy-1d52a223
issue: kvant_1972_9
year: 1972
number: "9"
title: 让我们学习处理绝对值
authors:
  - Ваховский Е. Б.
  - Волынский А. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
tag: 47WC
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c8867c9d1014e16d30ac904fe318dfa3c8d17f0e037cf16048eb2b01ab297712
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/12_vahovskiy-volyinskiy-nauchimsya-obraschatsya-s-absolyutnoy-velichinoy-1d52a223.md
source_content_sha256: 26405ab24cee8dc14681c254465a6ebfb9f26d7c217876d1dff8d982dd08e7ea
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

让我们学习处理绝对数量

E.B.瓦霍夫斯基、A.B.沃伦斯基

有一场考试正在进行中。向申请人提供了一个三角方程：

$$\sqrt{\cos^2 x - \cos 2x} - 1 = \sin x.$$

在求解过程中，申请人写出了以下方程：

$$\sqrt{\cos^2 x - \cos^2 x + \sin^2 x} - 1 = \sin x,$$

$$\sin x - 1 = \sin x, -1 = 0.$$

申请人表示，由此产生的错误数值相等意味着该方程无解。

答案是不正确的。这可以通过将数字 $x = -\frac{\pi}{6}$ 代入原始方程（结果是根）来轻松验证。

顺便说一句，申请人的错误是一个很常见的错误，那就是并不是每一个可操作的$a$

$$\sqrt{a^2} = a$$

(1)

(特别是在本例中，申请人认为$\sqrt{\sin^2 x} = \sin x$)。

其实唯一的真理都是一样的

$$\sqrt{a^2} = |a|,$$

(2)

而等式 (1) 仅对 $a \ge 0$ 有效（参见 E. S. Kochetkov、E. S. Kochetkov “代数和初等函数”，§ 77）。

因此，通过求解上式，申请人应得到

$$|\sin x| - 1 = \sin x.$$

如果$\sin x \ge 0$，那么最后一个方程将写成如下：$\sin x - 1 = \sin x$，因此$-1 = 0$，在这种情况下没有解。

如果$\sin x < 0$，则$|\sin x| = -\sin x$，得到$-\sin x - 1 = \sin x$，由此得到$\sin x = -\frac{1}{2}$，符合条件$\sin x < 0$。

答案：$x = (-1)^{n+1} \frac{\pi}{6} + \pi n$，其中$n=0, \pm 1, \pm 2, \dots$。

现在让我们仔细看看绝对值的概念。

首先，请注意，数字模型$x$的图形是从数字轴的点$x$到报告开头的简单距离（参见图1）。

上述消息使得解决一大类不等式变得更加容易。

示例 1. 解决不等式

$$|x| < a \quad (a > 0),$$

(3)

$$|x| > a \quad (a > 0).$$

(4)

解决方案。不等式（3）仅由数值轴上那些距离报告开头的距离小于 $a$ 的点满足，即位于 $-a$ 和 $a$ (图 2) 之间的点。

答案：$-a < x < a$。这意味着$x$满足系统

⟦folio 46⟧

不平等

$$\begin{cases} x > -a, \\ x < a. \end{cases}$$

出于类似的原因，不等式（4）的解是满足两个不等式组合的$x$值：$x < -a; x > a$（图3）。

需要注意的是，对于$a \leq 0$，不等式（3）无解。对于 $a < 0$ 来说，所有实数都满足不等式 (4)，对于 $a = 0$ - 除了 $x = 0$ 之外的所有实数都满足。

因此，在这种类型的例子中，我们首先必须对右侧的符号感兴趣。因此，例如，不等式 $|x| < |a|$ 通常通过分析 $a \geq 0$ 和 $a < 0$ 的情况自动求解，假设这是必要的，因为数字 $a$ 位于模符号下方。然而，这里最容易注意到的是$|a| > 0$在$a \neq 0$。从这里我们很容易得到答案：如果$a \neq 0$，则$|a| < x < |a|$，如果$a = 0$，则无解。

对于类型(3)和(4)的不等式，有一些不包含绝对值符号的不等式。

示例 2. 求解不等式 $4 < x^2 < 9$。

解决方案。让我们提取不等式所有三个部分的平方根（算术）。由此产生的等价不等式 $2 < |x| < 3$ 可以使用图形表示轻松求解 (图 4)。

答案：$-3 < x < -2; 2 < x < 3$。

实施例 3（MSU，mek.mat.，1966）。解决不平等问题

$$|3^{tg\pi x} - 3^{1-tg\pi x}| \geq 2.$$

解决方案。这个不等式相当于两个不等式的组合：$3^{tg\pi x} - 3^{1-tg\pi x} \leq -2; 3^{tg\pi x} - 3^{1-tg\pi x} \geq 2$。

用$y$表示$3^{tg\pi x}$，我们得到一组不等式：

$$y - \frac{3}{y} \leq -2; y - \frac{3}{y} \geq 2 (y > 0).$$

⟦folio 47⟧

解决方案。首先，我们需要去掉绝对星等的符号。然而，要做到这一点，您需要知道模数符号下的数字 $1 - x$ 和 $x^2 - x - 6$ 的符号是什么。但$x$这个数字是多少，事先并不知道，所以需要分几种情况来分析。为了以最经济的方式做到这一点，我们对三项式 $x^2 - x - 6$ 进行因式分解，并以以下形式表示这个不等式

$$\frac{6x - |x+2| |x-3|}{|x-1|} \leq 3 + 5x.$$

由于总是$|x-1| \geq 0$，所以这个不等式等价于系统

$$\begin{cases} 6x - |x+2| |x-3| \leq \\ \leq (3+5x) |x-1|, \\ x \neq 1. \end{cases}$$

要求解系统 (5)，请在数轴上绘制点 $-2, 1$ 和 $3$ (图 5)，这会将其分为偶数区域。对于数字$x$，从每个这样的区域可以清楚地看出数字$x+2, x-1, x-3$有什么符号。

例如，如果点 $x$ 位于最左侧区域 $(x < -2)$，则$|x+2| = -(x+2), |x-1| = 1 - x, |x-3| = 3 - x$。因此，我们的不平等相当于四个系统的组合：

$$\begin{cases} x < -2, \\ 6x - (x+2)(x-3) \leq (3+5x)(1-x); \\ -2 \leq x < 1, \\ 6x + (x+2)(x-3) \leq (3+5x)(1-x); \\ 1 < x \leq 3, \\ 6x + (x+2)(x-3) \leq (3+5x)(x-1); \\ x > 3; \\ 6x - (x+2)(x-3) \leq (3+5x)(x-1). \end{cases}$$

第一个系统无解。系统其余部分的解决方案：

$$-\frac{3}{2} \leq x < 1, \quad 1 < x \leq 3, \quad x > 3$$

分别。最终答案：$$-\frac{3}{2} \leq x < 1, \quad x > 1.$$

让我们继续讨论下一类与绝对值相关的问题。

考虑$|A| \leq B$形式的不等式，其中$A$和$B$是一些包含未知$x$的表达式。

由于我们在示例 1 中给出的信息，该不等式等价于系统

$$\begin{cases} B \geq 0, \\ -B \leq A \leq B, \end{cases}$$

或系统的整体：

$$\begin{cases} A \geq 0, \\ A \leq B; \quad A < 0, \\ -A \leq B. \end{cases}$$

同理，不等式$|A| \geq B$等价于系统的总体

$$\begin{cases} B < 0, \\ A - \text{любое}; \quad B \geq 0, \\ A \leq -B, \quad A \geq B, \end{cases}$$

或系统的整体

$$\begin{cases} A \geq 0, \\ A \geq B; \quad A < 0, \\ -A \geq B. \end{cases}$$

在这种类型的每个具体示例中，必须确定最有用的路径。

示例 5. 解决不等式

$$5 + 2 \cos 2x \leq 3 \quad |2 \sin x - 1|.$$

解决方案。这里直接使用第一种方法，因为$5 + 2 \cos 2x > 0$适用于所有$x$。所提出的不等式等价于一组不等式：

$$3 (2 \sin x - 1) \leq -5 - 2 \cos 2x; \quad 3 (2 \sin x - 1) \geq 5 + 2 \cos 2x.$$

这些不等式中的每一个，在代入 $\cos 2x = 1 - 2 \sin^2 x$ 后，都与 sin $x$ 成平方关系。考虑到不等式 $|\sin x| \leq 1$ 来解决它们，我们得到了集合

$$\sin x \leq -\frac{1}{2}, \quad \sin x \geq 1.$$

⟦folio 48⟧

答案：$2\pi n - \frac{5}{6} \pi \leqslant x \leqslant -\frac{\pi}{6} + 2\pi n, \quad x = \frac{\pi}{2} + 2\pi k, \quad \text{где } n, \quad k = 0, \quad \pm 1, \dots$

示例 6. 求解不等式 $|x^3 - 8| \leqslant x^3 + x + 8$。

解决方案。这里第一种方法根本不适用，因为我们没有机会解决不等式$x^3 + x + 8 \geqslant 0$。第二种方法将问题简化为系统整体

$$\begin{cases} x^3 - 8 \geqslant 0, \\ x^3 + x + 8 \geqslant x^3 - 8; \\ x^3 - 8 < 0, \\ x^3 + x + 8 \geqslant -x^3 + 8, \end{cases}$$

这又归结为系统的整体性

$$\begin{cases} x \geqslant 2, \\ x \geqslant -16; \end{cases}$$

$$\begin{cases} x < 2, \\ x(2x^2 + 1) \geqslant 0. \end{cases}$$

第一个解：$x \geqslant 2$，第二个解：$0 \leqslant x < 2$。

答案：$x \geqslant 0$。

很容易验证方程 $|A| = B$ 也可以通过两种方式求解；就相当于系统

$$\begin{cases} B \geqslant 0, \\ \pm B = A, \end{cases}$$

或者

$$\begin{cases} A \geqslant 0; \\ A = B; \end{cases}$$

$$\begin{cases} A < 0, \\ -A = B. \end{cases}$$

实施例 7（MAI，1970）。解方程：

$$x - \frac{|3x - 2|}{5} = 3 - \frac{2x - 5}{3}$$.

解决方案。经过简单变换我们得到

$$3 |3x - 2| = 25x - 70$$.

我们使用第一种方法。方程相当于系统的总体后

$$\begin{cases} 25x - 70 \geqslant 0, \\ 3(3x - 2) = 25x - 70; \\ 25x - 70 \geqslant 0, \\ 3(3x - 2) = -25x + 70. \end{cases}$$

第一个系统$x = 4$的解；第二个系统不兼容。

答案：$x = 4$。

实施例 8（密歇根州立大学物理学院，1963 年）。该方程最常见的解是：

$$\begin{cases} x^2 - \frac{3}{2}x - 1 = -x^2 - 4x + \beta. \end{cases}$$

解决方案。在这种情况下，第一种方法，包括右边的符号，是不方便的，因为参数$\beta$不仅会出现在方程中，而且还会出现在相应的不等式中。我们使用第二种方法。

所提出的方程等效于以下一组系统：

$$\begin{cases} x^2 - \frac{3}{2}x - 1 \geqslant 0, \\ x^2 - \frac{3}{2}x - 1 = -x^2 - 4x + \beta; \end{cases}$$

$$\begin{cases} x^2 - \frac{3}{2}x - 1 < 0, \\ -(x^2 - \frac{3}{2}x - 1) = -x^2 - 4x + \beta. \end{cases}$$

第一个系统还原为系统

$$\begin{cases} x \leqslant -\frac{1}{2}, x \geqslant 2, \\ x_1 = \frac{-5 - \sqrt{57 + 32\beta}}{8}, \\ x_2 = \frac{-5 + \sqrt{57 + 32\beta}}{8}. \end{cases}$$

从$x_1 < 0$开始，我们必须满足不等式$x_1 \leqslant -\frac{1}{2}, x_2 \leqslant -\frac{1}{2}, x_2 \geqslant 2$。

将它们的表达式代入$x_1$和$x_2$并求解关于$\beta$的无理不等式，我们得到
