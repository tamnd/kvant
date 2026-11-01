---
id: 1988-6-shevelev-tri-formulyi-ramanudzhana-203e8dac
issue: kvant_1988_6
year: 1988
number: "6"
title: 拉马努金的三个公式
authors:
  - Шевелёв В. С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 57
page_labels: 52-55
tag: 6MNW
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c3dbc22f601fa04c81a551614535a583f6dc20acc22398299a3543b66b1da628
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/12_shevelev-tri-formulyi-ramanudzhana-203e8dac.md
source_content_sha256: bd0f5d413a30adec4e2bbdba1d45ff2362fd886b1a021dd11ba0a76360344135
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

拉马努金的三个公式
物理和数学科学候选人
V.S.谢维列夫

拉马努金的公式总是比乍一看包含的内容要多得多......

哈代

在本文中，我们将讨论拉马努金 *) 的三个非凡公式，每个公式的左侧都包含三个立方根：

$$\sqrt[3]{\frac{1}{9}} - \sqrt[3]{\frac{2}{9}} + \sqrt[3]{\frac{4}{9}} = \sqrt[3]{\sqrt[3]{2} - 1},$$

(1)

$$\sqrt[3]{\cos \frac{2\pi}{7}} + \sqrt[3]{\cos \frac{4\pi}{7}} + \sqrt[3]{\cos \frac{8\pi}{7}} =$$

$$= \sqrt[3]{\frac{5 - 3\sqrt[3]{7}}{2}},$$

(2)

这些公式很难与任何其他数学家的公式混淆：它们类似于神秘的数字杂耍。

第一个公式更简单，并且证明了连续的立方体。对于我们来说，除了自然感知之外，它很有趣，因为在关系结构上它与接下来的两者非常相似。至于公式（2）和（3），这里并不是一切都那么简单。以下是 V. I. Levin 手册中关于这些公式的一些有趣引述**)：

“这些公式非常基本，但非常深奥。它们具有独特的内部对称性，这表明它们的存在

**) 您可以在 1987 年第 10 期«Kvant» 中了解这位独特数学家的生活和工作。

**) 莱文 V.I.拉马努金。 - M.：知识，1968。

⟦folio 53⟧

只有最高级别的数学家才能做到。”再说一次：“当然，这些确切的平等是拉马努金所传播的更一般关系的特例，但他从未对此进行过任何报道……”

我们邀请读者遵循公式（2）和（3）的证明。在某些地方，他需要铅笔和纸。作为奖励，他几乎有一个内部机制来控制这些美丽的公式，显然，他将能够独自证明几个公式，如拉马努金公式（由作者发现 - 参见练习 5），也许还可以提出他自己的公式。

与 Vieta 公式的联系

三角函数和代数之间的联系在拉马努金的公式中很容易看出。让我们仔细看看数字

$$\begin{cases} \cos \frac{2\pi}{7}, \cos \frac{4\pi}{7}, \cos \frac{8\pi}{7} \\ \cos \frac{2\pi}{9}, \cos \frac{4\pi}{9}, \cos \frac{8\pi}{9} \end{cases}.$$

首先，令人惊讶的是，余弦的参数在两个三元组中都形成了值为 2 的几何级数。

充分利用转型优势

$$\cos \alpha \cos 2\alpha \cos 4\alpha = \frac{\sin 2\alpha \cos 2\alpha \cos 4\alpha}{2 \sin \alpha} = \frac{\sin 4\alpha \cos 4\alpha}{4 \sin \alpha} = \frac{\sin 8\alpha}{8 \sin \alpha},$$

我们可以建立以下等式：

$$\cos \frac{2\pi}{7} \cos \frac{4\pi}{7} \cos \frac{8\pi}{7} = \frac{1}{8},$$

$$\cos \frac{2\pi}{9} \cos \frac{4\pi}{9} \cos \frac{8\pi}{9} = -\frac{1}{8}.$$

这是我们第一次成功证明拉马努金公式中的余弦参数是相对非随机选择的。

现在让我们尝试求三个余弦的和。我们有：

$$\cos \frac{2\pi}{7} + \cos \frac{4\pi}{7} + \cos \frac{8\pi}{7} =$$

$$= \frac{2 \sin \frac{\pi}{7}}{2 \sin \frac{\pi}{7}} \left( \cos \frac{2\pi}{7} + \cos \frac{4\pi}{7} + \cos \frac{6\pi}{7} \right) =$$

$$= \frac{1}{2 \sin \frac{\pi}{7}} \left( \sin \frac{3\pi}{7} - \sin \frac{\pi}{7} + \sin \frac{5\pi}{7} \right) - \sin \frac{3\pi}{7} + \sin \pi - \sin \frac{5\pi}{7} = -\frac{1}{2};$$

$$\cos \frac{2\pi}{9} + \cos \frac{4\pi}{9} + \cos \frac{8\pi}{9} =$$

$$= \cos \frac{2\pi}{9} + \cos \frac{4\pi}{9} - \cos \frac{\pi}{9} =$$

$$= 2 \cos \frac{3\pi}{9} \cos \frac{\pi}{9} - \cos \frac{\pi}{9} = 0.$$

最后，我们发送以下金额：

$$S_1 = \cos \frac{2\pi}{7} \cos \frac{4\pi}{7} + \cos \frac{2\pi}{7} \cos \frac{8\pi}{7} + \cos \frac{4\pi}{7} \cos \frac{8\pi}{7},$$

$$S_2 = \cos \frac{2\pi}{9} \cos \frac{4\pi}{9} + \cos \frac{2\pi}{9} \cos \frac{8\pi}{9} + \cos \frac{4\pi}{9} \cos \frac{8\pi}{9}.$$

练习 1. 证明 $S_1 = -\frac{1}{2}, S_2 = -\frac{3}{4}$。

现在让我们写出三次方程的 Vieta 公式。如果 $x, y, z$ 是方程的根

$$t^3 + pt^2 + qt + r = 0,$$

那么，众所周知，

$$\begin{cases} x + y + z = -p, \\ xy + xz + yz = q, \\ xyz = -r. \end{cases}$$

让我们将（4）与我们上面获得的拉马努金余弦三元组的等式进行比较，我们得出结论，第一个三元组由方程的根组成

$$t^3 + \frac{1}{2} t^2 - \frac{1}{2} t - \frac{1}{8} = 0,$$

第二个来自方程的根

$$t^3 - \frac{3}{4} t + \frac{1}{8} = 0.$$

这个阶段是我们证明中最重要的阶段。它显示了如何

⟦folio 54⟧

va 公式（2）和（3）中三角测量和代数表达式之间联系的性质。

让我们考虑三个根之和......

现在让我们这样提出问题。给定方程
$$t^3 + pt^2 + qt + r = 0,$$
其根是数字$x, y, z$。我们需要找到它们的立方根之和（我们用 $A$ 表示这个和的立方）：
$$\sqrt[3]{x} + \sqrt[3]{y} + \sqrt[3]{z} = \sqrt[3]{A}.$$
(7)

事实证明，sum (7) 很容易与另一个 sum 一起查找：
$$\sqrt[3]{xy} + \sqrt[3]{xz} + \sqrt[3]{yz} = \sqrt[3]{B}.$$
(8)

将 (7) 和 (8) 两部分相乘，并考虑 Vieta 的公式 (4)，我们得到（请自行检查）：
$$A = -p + 3\sqrt[3]{AB} + 3\sqrt[3]{r},$$
$$B = q - 3\sqrt[3]{ABr} - 3\sqrt[3]{r^2},$$
(10)

将 (9) 乘以 $\sqrt[3]{r}$ 再加上 (10)，我们可以通过 $A$ 表达 $B$：
$$B = q - (A + p)\sqrt[3]{r}.$$
(11)

将其代入(9)，我们得到仅针对$A$的方程：
$$A + p - 3\sqrt[3]{r} = 3\sqrt[3]{A(q - (A + p)\sqrt[3]{r})}.$$
(12)

最后，将方程两边同时立方，得到$A$的三次方程：
$$A^3 + 3(p + 6\sqrt[3]{r})A^2 + 3(p^2 + 3p\sqrt[3]{r} + 9\sqrt[3]{r^2} - 9q)A + (p - 3\sqrt[3]{r})^3 = 0.$$ (11)

简化三次方程

给我们一个三次方程
$$x^3 + 3bx^2 + 3cx + d = 0.$$ (12)

我们将展示如何（在某些情况下特别成功）简化它。

将$x = z - b$代入(12)，我们得到$z$的三次方程，不包含$z^2$（检查！）。此外，如果等式(12)中的$b$和$c$有以下关系
$$b^2 = c,$$
那么$z^1$的项也将从$z$的方程中消失。结果，方程
表达式(12)的形式为
$$z^3 = b^3 - d.$$
回到$x$，我们得到
$$x = \sqrt[3]{b^3 - d} - b.$$ (13)

让我们检查一下在哪种情况下方程 (11) 满足条件 $b^2 = c$。与式（12）比较，可得：
$$b = p + 6\sqrt[3]{r},$$
$$c = p^2 + 3p\sqrt[3]{r} + 9\sqrt[3]{r^2} - 9q,$$
条件 $b^2 = c$ 的形式为：
$$3\sqrt[3]{r^2} + p\sqrt[3]{r} + q = 0.$$ (14)

现在是一个激动人心的时刻：毕竟，数字$p, q$和$r$是已知的方程，其根是余弦的拉马努金三元组（参见公式（5）和（6））！

对于前三个：$p = 1/2$、$q = -1/2$、$r = -1/8$；对于第二个三元组：$p = 0$，$q = -3/4$，$r = 1/8$。将这些值代入(14)，我们得到数值等式！但在这种情况下，根据（13）（在$x = A$，$b = p + 6\sqrt[3]{r}$，$d = (p - 3\sqrt[3]{r})^3$），
$$A = \sqrt[3]{b^3 - d} - b.$$
对于前三个，$b = \frac{1}{2} - 3 = -\frac{5}{2}$，$d = \left(\frac{1}{2} + \frac{3}{2}\right)^3 = 8$，所以
$$A = \frac{-3\sqrt{189} + 5}{2} = \frac{5 - 3\sqrt{7}}{2}.$$
对于第二个三元组$b = 3$、$d = \left(-\frac{3}{2}\right)^3 = -\frac{27}{8}$ 和
$$A = \sqrt[3]{27 + \frac{27}{8}} - 3 = \frac{3\sqrt[3]{9} - 6}{2}.$$

这些与拉马努金公式（2）和（3）右侧的激进表达式不同。因此，证明完成。

练习2.代入$\sqrt[3]{x} = u$、$\sqrt[3]{y} = v$、$\sqrt[3]{z} = w$，证明$u, v, w$不等于0的条件(14)与该条件等价
$$u^3 + v^3 + w^3 + \frac{(uv)^2}{w} + \frac{(uw)^2}{v} + \frac{(vw)^2}{u} + 3uvw = 0.$$ (15)

根据我们的证明，拉马努金的立方根满足条件 (15)

⟦folio 55⟧

余弦（第一和第二个三元组）。很容易直接检查是否也满足三倍数

$$u = \sqrt[3]{\frac{1}{9}}, v = -\sqrt[3]{\frac{2}{9}}, w = \sqrt[3]{\frac{4}{9}}.$$

因此，等式(1)、(2)、(3)基于一般条件(15)。

也许拉马努金知道其他满足条件（15）的三元组数（$u, v, w$）。

练习 3. 证明，与数字 $u, v, w$ 一起，条件 (15) 满足： a) 数字 $\frac{1}{u}, \frac{1}{v}, \frac{1}{w}$；
6) 数字$\sqrt[3]{u^3+uvw}, \sqrt[3]{v^3+uvw}, \sqrt[3]{w^3+uvw}$。

练习 4. 证明如果满足条件 (15)，则等式成立

$$\left( \frac{u}{v} + \frac{v}{u} + \frac{u}{w} + \frac{w}{u} + \frac{w}{v} \right)^3 + 6 = \left( \frac{u}{v} \right)^3 + \left( \frac{v}{u} \right)^3 + \left( \frac{u}{w} \right)^3 + \left( \frac{w}{v} \right)^3.$$

例如，检查 (16) 中是否有三元组 $u = \sqrt[3]{\frac{1}{9}}, v = -\sqrt[3]{\frac{2}{9}}, w = \sqrt[3]{\frac{4}{9}}$。相反，是否可以从 (16) 推导出 (15)？

练习 5. 证明等式：

$$1^\circ. \sqrt[3]{\sec \frac{2\pi}{7}} + \sqrt[3]{\sec \frac{4\pi}{7}} + \sqrt[3]{\sec \frac{8\pi}{7}} = \sqrt[3]{8-6\sqrt[3]{7}};$$

$$2^\circ. \sqrt[3]{\sec \frac{2\pi}{9}} + \sqrt[3]{\sec \frac{4\pi}{9}} + \sqrt[3]{\sec \frac{8\pi}{9}} = \sqrt[3]{6(\sqrt[3]{9}-1)};$$

$$3^\circ. \sqrt[3]{\sec 2+\sec \frac{2\pi}{7}} + \sqrt[3]{\sec 2+\sec \frac{4\pi}{7}} + \sqrt[3]{\sec 2+\sec \frac{8\pi}{7}} = \sqrt[3]{6\sqrt[3]{7}-10};$$

$$4^\circ. \sqrt[3]{\frac{1}{2}+\cos \frac{2\pi}{7}} +$$
