---
id: 1973-6-egorov-ploschad-pod-giperboloy-logarifm-i-eksponenta-68b39411
issue: kvant_1973_6
year: 1973
number: "6"
title: 双曲线、对数和指数下的面积
authors:
  - Егоров А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 40
page_labels: 30, 31, 32, 34, 36, 38
tag: HOPC
lang: zh
source: kvant_digital
extraction: vision
content_sha256: cc9d491c1169e419df5d81136ec9857bf12d1f73ee7fbe445154d689c78d65f1
prompt_sha256: draft-1
translated_from: content/ru/1973/06/articles/07_egorov-ploschad-pod-giperboloy-logarifm-i-eksponenta-68b39411.md
source_content_sha256: 68280c9140ddf60c9fdcac91d25e8cc07632bfd85813ae1daaadb811489a7063
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

1. 介绍。
对数的定义

在学校里，指数函数$x \rightarrow a^x$是在幂运算的几次推广之后被研究的：首先确定自然指数的次数，然后确定有理指数，最后确定无理指数。然后对数定义为指数函数的反函数。

我们会做对的：我们将立即从对数的定义开始，然后继续讨论反函数 - “指数”。我们现在给出的定义使得研究这些函数的基本属性并获得对物理应用特别重要的估计成为可能，并演示了数学中使用已知函数构造新函数的常用方法之一。

这样一个众所周知的函数就是函数$x \rightarrow \frac{1}{x}$，其图形$y = \frac{1}{x}$就是我们熟悉的双曲线。

定义。令 $b$ 为正数。让我们用$\ln b$表示其模型等于由函数图像$y = \frac{1}{x}$、横坐标轴$y = 0$以及直线$x = 1$和$x = b$限制的函数面积的数字，如果$b > 1$（图1，a）则符号为平，如果$b < 1$为负号（图1，b）；如果$b = 1$，则$\ln b = 0$。

函数$b \rightarrow \ln b$称为自然对数。

我们很快就会发现$\ln b$实数是数$b$以$e$为底的对数，其中$e = 2,71828\dots$是一个替代数学常数，这已经在«Kvant»中讨论过（参见L. G. Limenov的文章“On the number $e$ and $n$” in No.5 for 1972）。

对于熟悉积分的人来说（例如，根据«Kvant»第9期Yu. I. Ionin的文章），我们对对数的定义可以表述如下：

$$\ln b = \begin{cases} \int \frac{1}{x} dx, \text{ если } b > 1, \\ 0, \text{ если } b = 1, \\ -\int \frac{1}{x} dx, \text{ если } 0 < b < 1. \end{cases}$$

我们有时会参考《论数$e$》和《积分》两篇文章，但只是为了比较：读者不需要事先了解它。想要详细、严格地遵循所有论点并解决问题（它们包含文章内容的重要部分）的读者将需要了解实数的基本属性 *)。然而，斯塔-

*) 例如，参见 B. E. Weizza 和 I. T. Demidov 的试用教科书“代数和分析的开始”，9 年级，M.，“Prosveshchenie”，1969 年。

⟦folio 31⟧

图 1.
如果可能的话，它的编写方式应使有关对数和指数性质的基本事实可以被理解，仅使用有关实数、连续性、极限等的幼稚想法，而无需深入研究与这些概念的严格定义相关的微妙之处。

2. 正方形
应该严格定义的概念之一是面积的概念。事实上，我们需要解释一下“曲线梯形”的面积是什么意思（参见图1）。毕竟，在学校我们只讨论多边形、圆形及其各部分的面积，而我们的梯形的一侧受到双曲线的限制。

在这里，我们将限制自己将面积替换为一个函数，它可以在足够宽的函数类上定义（此类包括多边形、所有凸有界函数以及我们的“梯形”），以便满足条件：

1) 任何函数的面积都是非负数；
2) 等（全等）函数的面积相等；
3) 如果一个函数被分成两部分，每一部分的面积都确定，那么这些面积的总和等于所有函数的面积；

图 2.
4) 矩形边$a$和$b$的面积等于$ab$。

我们不会描述可以定义这样的函数$S$的函数类，但我们将通过条件1-4证明“曲线梯形”$a \leq x \leq b$的面积$S$； $0 \leq y \leq \frac{1}{x}$ (图 2) 是唯一确定的。

为此，我们将线段 $[a, b]$ 分成 $n$ 相等的部分，并构造两个“楼梯” - 由在轴 $Ox$ 上以 $\frac{b-a}{n}$ 为底的矩形组成的阶梯函数，其中一个包含我们的曲线梯形，另一个包含在其中 (图 2)。令$S'_n$和$S''_n$为这些“楼梯”$^*$的面积）。显然$S'_n < S < S''_n$。另一方面，很明显

$$S''_n - S'_n = \frac{b-a}{n} (a^{-1} - b^{-1}),$$

也就是说，对于足够大的$n$，$S''_n$和$S'_n$之间的差可以任意小。因此，对于所有$n$，只有一个数$S$包含在$S'_n$和$S''_n$之间（也可以看出，随着$n$的增加，序列$S'_n$和$S''_n$都趋近于$S$，即$S$是它们的共同极限）。

*) 我们可以使用条件 3 和 4 确定这些区域。

⟦folio 32⟧

3. 自然对数的主要性质

该属性由以下公式表示

$$\ln x_1 x_2 = \ln x_1 + \ln x_2$$

(1)

（在 $x_1 > 0$ 和 $x_2 > 0$）

表示乘积的自然对数等于因子的自然对数之和。

在证明式（1）之前，我们先建立函数$y = \frac{1}{x}$曲线梯形的一个重要性质。

让我们用 $S[A, B]$ 表示顶点为 $A, B$ (图 3) 的弯曲梯形的面积。那么，如果$b > a > 0$和$k$是任意正数，那么(图 4)

$$S[a, b] = S[ka, kb].$$

(2)

为了证明这一点，让我们考虑平面的变换，其中包括从轴 $Oy$ 拉伸 $k$ 倍，并向轴 $Ox$ 滑动 $k$ 倍，即，将点 $(x, y)$ 带到点 $(kx, \frac{y}{k})$ (图 5) 的变换。很容易看出这是一个转换：

$$\int_a^b \frac{1}{x} \, dx = \int_k^a \frac{1}{x} \, dx.$$

⟦folio 34⟧

5. 参展商

可以证明我们前面几段研究的函数取的都是实值*）。在这种情况下，当然，每个值都只取一次，也就是说，对于任何 $x$，方程 $\ln y = x$ 都有唯一解。对于数字 $y$（该方程的解），该符号被接受

$$y = \exp x.$$

由此产生的新函数 $x \rightarrow \exp x$ 是函数 $x \rightarrow \ln x$ 的逆函数，称为指数函数。

请注意，根据指数的定义，等式

$$\exp (\ln x) = \ln (\exp x) = x.$$ (6)

图形$y = \exp x$与图形$y = \ln x$关于直线$y = x$对称。事实上，由于$y = \exp x$等价于$\ln y = x$，所以指数的图是由对数图通过平面变换得到的，其中点$(x, y)$到点$(y, x)$，并且这个变换相对于直线$y = x$（图8**））是对称的。

*）我们不会证明这一点，但请注意，“从连续性消息”来看，这几乎是显而易见的。这个事实的严格证明可以用与证明任意 $a \geq 0$ 存在$\sqrt{a}$ 大致相同的方式进行。

**）为了验证这个数字的正确性，你应该证明$\ln x < x$对于所有$x > 0$。

因此，指数是在整个数轴$-\infty < x < +\infty$上定义的递增函数，并取正值。此外，当$x$无限增加时，指数呈现明显更大的值，并且当$x$趋向于$-\infty$时，指数趋于零。

6. 指数的主要性质

该属性由以下公式表示：

$$\exp \left( x_1 + x_2 \right) = \exp x_1 \cdot \exp x_2.$$ (7)

为了证明这一点，我们将使用自然对数和对应关系（6）的主要性质。由于$\ln y_1 y_2 = \ln y_1 + \ln y_2$，那么对于$y_1 = \exp x_1$和$y_2 = \exp x_2$，我们得到$\ln y_1 y_2 = x_1 + x_2$，即$y_1 \cdot y_2 = \exp \left( x_1 + x_2 \right)$或$\exp x_1 \cdot \exp x_2 = \exp \left( x_1 + x_2 \right)$。

从 exp 的基本属性（或从 ln 函数的相应属性）很容易推出：

$$\exp (-x) = \frac{1}{\exp x}$$

和

$$\exp \left( x_1 + x_2 + \dots + x_n \right) = \exp x_1 \cdot \exp x_2 \dots \cdot \exp x_n).$$

让我们用 $e$ 来表示数字 exp1。换句话说，$e$是方程$\ln e = 1$的解。

利用指数的主要性质，我们证明对于有理数 $x = \frac{m}{n}$ exp $x = e^x$。

首先，自然$m$exp$m = \exp \left( 1 + 1 + \dots + 1 \right) = \exp 1 \cdot \exp 1 \cdot \dots \cdot \exp 1 = e^m$和exp$(-m) = \frac{1}{\exp m} = \frac{1}{e^m} = e^{-m}$。

因此对于任意整数$m$，exp $m = e^m$。

此外，还含有天然的$n$

$$\exp \left( \frac{1}{n} \right)^n = \exp \left( \frac{1}{n} + \frac{1}{n} + \dots + \frac{1}{n} \right) = \exp 1 = e,$$

⟦folio 36⟧

与 Ox 轴的倾斜角的真切值等于 (图 9)

$$\text{tg} \alpha = \frac{f(x_1) - f(x_0)}{x_1 - x_0}.$$

当点$x_1$接近$x_0$时，割线趋于其极限位置——在点$x_0$处绘制到曲线$y = f(x)$的切线。因此，$x = x_0$处的任意值等于图形在点$(x_0, f(x_0))$处的切线斜率。

让我们尝试计算函数 $f(x) = \ln x$ 的“瞬时”变化率。它在线段$[x_0, x_1]$上的增量等于

$$\ln x_1 - \ln x_0 = \ln \frac{x_1}{x_0} = \ln \left(1 + \frac{x_1 - x_0}{x_0}\right),$$

姿势

$$\frac{\ln x_1 - \ln x_0}{x_1 - x_0} = \frac{1}{x_0} \cdot \frac{\ln(1 + h)}{h},$$

在哪里

$$h = \frac{x_1 - x_0}{x_0}.$$

当$x_1$趋向于$x_0$时，$h$趋向于0。因此，对于较小的$h$，比率$\frac{\ln(1 + h)}{h}$的表现如何还有待观察。

正如我们很快就会看到的，根据我们对对数的定义，很容易获得估计值，由此得出，当 $h$ 接近零时，值 $\frac{\ln(1 + h)}{h}$ 接近 1，即

$$\ln(1 + h) \approx h \text{ (при малых } h).$$

这个公式对于近似计算很重要，也可以重写如下：

$$\exp h \approx 1 + h \text{ (при малых } h).$$

从这里我们推导出对数和指数变化率的基本公式：

$$(\ln x)' = \frac{1}{x}$$

和

$$(\exp x)' = \exp x.$$

9. 单位大小的自然对数的估计

这是对数的主要属性之一：

$$\left| x - \frac{x^2}{x+1} \right| = \left| \frac{x}{x+1} \right| < \left| \ln(1+x) \right| < |x|.$$

为了证明$x > 0$的这些不等式，只需将弯曲梯形$ABCD$的面积与两条直线$AD'CB$和$ADC'B$（图10）的面积进行比较就足够了。事实上，曲梯形的面积等于$\ln(1+x)$，$AD'CB$的面积等于

⟦folio 38⟧

条款

$$e^x = 1 + x + \frac{x^2}{1 \cdot 2} + \dots + \frac{x^k}{1 \cdot 2 \cdot \dots k} + \dots$$

(16)

正如无限几何级数 $1 + x + x^2 + \dots$ 在 $|x| < 1$ 处由函数 $y = \frac{1}{1-x}$ 表示一样。

这种表示法很方便有两个原因。首先，要使用公式 $e^x \approx 1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!}$ 高精度地计算指数（例如，编表时），相对较少的项数就足够了；其次，这种扩展将使您能够更深入地研究指数（例如，证明数字 $e$ 的无理性）（参见问题 11、12）。

我们将限制自己证明$x > 0$的公式（16）。

所以让$T_n(x) = \left(1 + \frac{x}{n}\right)^n$和$S_n(x) = 1 + x + \frac{x^2}{1 \cdot 2} + \dots + \frac{x^n}{n!}$。我们必须证明

$$\lim S_n(x) = \exp x.$$

使用二项式公式我们得到

$$\left(1 + \frac{x}{n}\right)^n = 1 + n \cdot \frac{x}{n} + \frac{n(n-1)}{1 \cdot 2} \frac{x^2}{n^2} + \dots + \frac{x^n}{n!} = 1 + x + \frac{\left(1 - \frac{1}{n}\right) x^2}{1 \cdot 2} + \dots + \frac{\left(1 - \frac{1}{n}\right) x^k}{1 \cdot 2} + \dots + \frac{x^n}{n!}.$$

这个等式右边括号里的数字都小于一。如果用单位替换，则右侧增加
38
