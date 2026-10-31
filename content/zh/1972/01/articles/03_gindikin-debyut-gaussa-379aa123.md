---
id: 1972-1-gindikin-debyut-gaussa-379aa123
issue: kvant_1972_1
year: 1972
number: "1"
title: 高斯登场
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 6
page_last: 11
page_labels: 4, 6, 9
tag: 1VLR
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f3bc2cbd83316e38d70d909b47c50feb206874377b5ac5c45246c2133e5f546b
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/03_gindikin-debyut-gaussa-379aa123.md
source_content_sha256: 1dcf6e90ce4945056dc91c260fee6b2c06366e59678661d3666affe57fbcfc76
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

相当于将半径为1的圆分成$n$等份的问题。将圆分成的弧的弦是正$n$边形的边，每条边的长度为$2\sin \frac{\pi}{n}$ (图 2)。

因此，对于那些 $\sin \frac{\pi}{n}$ 是无理数正方形的 $n$，我们可以用圆和尺子构造正则 $n$ 边形。例如，值$n=3, 4, 5, 6, 10$就满足此条件。对于 $n=3, 4, 6$ 来说，这是众所周知的。

让我们证明 $\sin \frac{\pi}{10}$ 是平方无理数。考虑一个等边三角形$ABC$(图3)，其顶角为$\frac{\pi}{5}=36^\circ$，长度$AB$为1；设$AD$为角$A$的平分线。然后$x=AC=AD=BD=2\sin \frac{\pi}{10}$。

我们有：

$$\frac{BD}{DC}=\frac{AB}{AC}; \frac{x}{1-x}=\frac{1}{x}, x=\frac{\sqrt{5}-1}{2}.$$

这个数是无理数的平方；这样我们就可以构造正十边形的边。

进一步，根据将圆分成 $p_1 p_2$ 等份的可能性

当然，它可以被分成$p_1$相等的部分（部分地，可以构造一个正五边形）。一般来说，相反的陈述是错误的。当它仍然成立时，让我们指出两种特殊情况。

1) 根据将圆分成 $p$ 等份的可能性，得出对于任何 $k$ 将圆分成 $2^k p$ 等份的可能性。

2) 如果我们将圆分成$p_1$等份和$p_2$等份，其中$p_1$和$p_2$互质（例如，$p_1, p_2$是不同的素数），那么圆可以分为$p_1 p_2$等份。

关于复数的几句话

我们对复数知之甚少：复数的运算和几何解释；例如，所有这些都包含在科切特科夫父子的教科书中。假设复数 $z=a+ib$ 与坐标为 $(a, b)$ (图 4) 的点以及以该点为终点、以 $(0, 0)$ 为起点的向量相关联。向量$r=\sqrt{a^2+b^2}$的长度称为给定数的模。复数$z$可以写成三角函数形式：$z=a+bi=r(\cos \varphi+i\sin \varphi)$；角$\varphi$称为数$z$的自变量。

⟦folio 6⟧

方程：首先求解方程（4），其根是方程（3）的对称根（见图 6！）之和$\varepsilon_1 + \varepsilon_4$和$\varepsilon_2 + \varepsilon_3$之和，然后从方程（5）找到方程（3）本身的根。

正是通过这种方式，高斯成功地构造了一个正 17 边形：在这里，根组也被区分出来，根组的总和可以从二次方程中顺序找到。但如何找到这些“好”乐队呢？高斯有一个令人惊奇的方法来回答这个问题......

构造一个正17边形

1796年3月30日是他（高斯）创造性洗礼的日子……高斯已经在他的“原始”根理论的基础上从事单位根的分组工作有一段时间了。然后有一天早上，当我们醒来时，他清楚地意识到，17边形的构造遵循他的理论……这一事件是高斯一生的转折点。他决定不再致力于语言学，而是专门研究数学。

F·克莱因

为了揭示高斯在单位 17 次方根集合中发现的隐藏“对称性”，并使用 immy 将根划分为必要的组，我们引入了新的根编号。我们将 3 进行连续的 0、1、2、... 次幂，并且每次都取结果除以 17 的余数。我们将让读者免于执行这些计算，并将最终结果呈现在表中。第一行包含指数 $k$，其下方是 $3^k$ 除以 17 的余数。

请注意，底行包含从 1 到 16 的所有数字；然后 $3^{16}$ 给出余数 1，然后重复周期性余数（证明它！）

高斯注意到的模式是以下定理的一个特例：对于每个素数$p$，都有一个数字$l$，称为原根，这样在$l^k$除以$p$的余数中，可以找到所有数字1、2、...、$p-1$。这个事实首先由欧拉（Euler，1707-1783）注意到，但只有勒让德（Legendre，1752-1833）能够证明这一点；高斯获得了其他证明，但很可能在 1796 年他还没有普遍定理，而是通过对特定数字进行计算发现了给定的经验事实。这是一个非常重要的情况，不考虑根本性的情况，就很难正确理解高斯早期作品的本质。

让我们为根$\varepsilon_h$、$k=3^l$分配一个新数，即$l$，我们

桌子

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 3 | 9 | 10 | 13 | 5 | 15 | 11 | 16 | 14 | 8 | 7 | 4 | 12 | 2 | 6 | 1 |

⟦folio 9⟧

附录一。

现在我们来证明 17 次根的平方无理数。请注意，$\varepsilon_k \varepsilon_l = \varepsilon_k + l$（如果$k + l \geq 17$，则$k + l$ 被其除以 17 的余数替换）、$\varepsilon_k = (\varepsilon_1)^k$。让我们用表格重新对单位根进行编号，即将$\varepsilon_{[l]}$和$\varepsilon_k$一起写（见公式（1）），其中$l$是表中$k$上方的数字。我们将根分为几组，如图 8所示。我们将求出现在一个矩形（图 8）中的根的总和，从大矩形移动到较小的矩形。首先，我们注意到

$$\varepsilon_1 + \varepsilon_2 + \ldots + \varepsilon_{16} = \varepsilon_0 + \varepsilon_1 + \ldots + \varepsilon_{15} = -1.$$

（例如，您可以通过将此表达式视为几何级数的总和来验证这一点。）因此，我们找到了最大矩形（0 号）中的根的总和。

让我们用$\sigma_m, r$表示$\varepsilon_k$与$k$的总和，除以$m$时得到余数$r$。让我们考虑下一个矩形（No.1）对应的根的总和。

我们得到

$$\sigma_{2,0} = \varepsilon_0 + \varepsilon_2 + \varepsilon_4 + \ldots + \varepsilon_{14},$$

$$\sigma_{2,1} = \varepsilon_1 + \varepsilon_3 + \varepsilon_5 + \ldots + \varepsilon_{15}.$$

很明显

$$\sigma_{2,0} + \sigma_{2,1} = \varepsilon_0 + \varepsilon_1 + \ldots + \varepsilon_{15} = -1.$$

可以证明

$$\sigma_{2,0} \cdot \sigma_{2,1} = 4 (\varepsilon_0 + \varepsilon_1 + \ldots + \varepsilon_{15}) = -4^*.$$

现在，利用 Vieta 定理，我们可以创建一个根为 $\sigma_{2,0}, \sigma_{2,1}$ 的二次方程：

$$x^2 + x - 4 = 0; \quad x_{1,2} = \frac{-1 \pm \sqrt{17}}{2}.$$

要区分根，请使用图 7。在每个和中，都包含根及其共轭。很明显，$\sigma_{2,0} > \sigma_{2,1}$（在第一种情况下，您需要将根$\varepsilon_1, \varepsilon_2, \varepsilon_4, \varepsilon_8$的实部相加并加倍，在第二种情况下 - $\varepsilon_3, \varepsilon_5, \varepsilon_6, \varepsilon_7$）。所以，

$$\sigma_{2,0} = \frac{\sqrt{17} - 1}{2}, \quad \sigma_{2,1} = \frac{-\sqrt{17} - 1}{2}.$$

让我们考虑 图 8 上对应于以下矩形（No.2）的根之和：

$$\sigma_{4,0} = \varepsilon_0 + \varepsilon_4 + \varepsilon_8 + \varepsilon_{12},$$

$$\sigma_{4,1} = \varepsilon_1 + \varepsilon_5 + \varepsilon_9 + \varepsilon_{13},$$

$$\sigma_{4,2} = \varepsilon_2 + \varepsilon_6 + \varepsilon_{10} + \varepsilon_{14},$$

$$\sigma_{4,3} = \varepsilon_3 + \varepsilon_7 + \varepsilon_{11} + \varepsilon_{15}.$$

*) 你可以验证这一点，电线是直接改变的，考虑到$\varepsilon_k \cdot \varepsilon_l = \varepsilon_k + l$，使用图7很方便。但是，附录2将指出一种方法来避免这些繁琐的计算。
