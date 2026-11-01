---
id: 1976-2-sukonnik-gornshteyn-prostoy-otvet-v-slozhnoy-zadache-edb188a9
issue: kvant_1976_2
year: 1976
number: "2"
title: “复杂”问题的简单答案
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: R33P
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 3c03bac969f3bf5cf136c49908e5644b1aaa4444200858cea901cba12747383c
prompt_sha256: draft-1
translated_from: content/ru/1976/02/articles/13_sukonnik-gornshteyn-prostoy-otvet-v-slozhnoy-zadache-edb188a9.md
source_content_sha256: a89877da8f813be4e46cd67feec7cc2052cc769082f344efe0b3816fe512257f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

“复杂”问题的简单答案

本文再次提出了平面问题应该如何解决的问题——“代数”还是“纯几何”？ *) 当然，对比这两种方法是没有道理的；准备入学考试的主要任务是学习如何将它们结合起来。 “纯几何”解决方案的概念并不总是可取的——除非它足够快地浮现在脑海中。我们只是想警告未来的申请人不要在相对简单的几何问题中进行令人费解的计算，这些问题可以使用“纯几何”思想轻松解决。本文讨论的问题允许不同的、有时非常麻烦的解决方案，尽管答案总是简单的。通过他们的例子，你可以很容易地看出能够“几何地”思考并应用广为人知的平面论定理是多么重要。当然，找到简单的几何解决方案需要一些创造力。 “正确解决问题”的能力是一门艺术，只有不断发展几何思维和直觉才能掌握。为此，请解决尽可能多的问题，并记住日本人的解决问题是一个创造性的过程。

*) 另请参阅 S. V. Romanov 和 I. F. Shara G. 的文章“解决几何问题的代数方法”，«Kvant»，1975 年，第 11 期。

我们先从这两个问题开始。

问题 1（MAI，1973）。在直角三角形中，其中一个锐角等于 α。在由降低到其上的高度的底部形成的锡安段上，如直径一样，构造半圆，位于给定三角形的同一侧。这些半圆内封闭的卡梅特段的长度的名称。

第一个决定。令 $CAB$ 为给定三角形（角 $A$ 为直角），$AD$ 其高度，点 $E$ 和 $F$ 为半圆与边 $AC$ 和 $AB$ 的交点（参见 图 1）。显然是$(DE) \perp (AC)$和$(DF) \perp (AB)$。波佐托穆

$$\begin{cases} |DF|^2 = |AF| \cdot |FB|, \\ |DE|^2 = |AE| \cdot |EC|. \end{cases}$$

让我们引入未知数：$x = |DF| = |AE|$和$y = |AF| = |DE|$。

然后，用$|AC| = b$和$|AB| = c$表示，我们得到系统：

$$\begin{cases} x^2 = y(c - y), \\ y^2 = x(b - x), \end{cases}$$

在哪里

$$x = \frac{bc^2}{b^2 + c^2}, \quad y = \frac{b^2c}{b^2 + c^2}.$$

但

$$|FB| = c - y = \frac{c^3}{b^2 + c^2}, \quad |EC| = b - x = \frac{b^3}{b^2 + c^2}.$$

⟦folio 47⟧

因此，

$$\frac{|FB|}{|EC|} = \frac{c^3}{b^3}.$$

但$\frac{c}{b} = \text{tg}\alpha$意味着$\frac{|FB|}{|EC|} = \text{tg}^3\alpha$。

第二个解决方案。注意

$$\widehat{DCE} = \widehat{DAF} = \widehat{BDF} = x.$$

因为

$$\frac{|FB|}{|EC|} = \frac{|DF| \cdot \text{tg}\alpha}{|EC|} = \frac{(|AF| \cdot \text{tg}\alpha) \cdot \text{tg}\alpha}{|EC|} = \frac{|DE| \cdot \text{tg}^2\alpha}{|EC|} = \text{tg}^3\alpha.$$

我们看到，要获得答案，不需要引入任何未知数或组成代数系统 - 只需注意列出的三个角度全等就足够了。

问题 2. 给定一个三角形 ABC。画一个圆，它在长度 h 的高度 AD 的底部与 BC 边相切，并穿过长度 b 的 AC 边的中间。名字就是这个圆的直径。

第一个决定。 图2表示一种可能的排列：圆的直径DF小于高度，圆与边AC相交于两点K和E，其中上点E为中点，并且不与三角形的第二条边相交。

让我们用 x: $|DF| = x$ 表示排除圆的直径，用 y: $|KE| = y$ 表示弦 $KE$ 的长度。

图 2.

将定理应用于切线和割线，以及从一点（分别为 C 和 A）绘制到圆上的两条割线，我们得到

$$|CD|^2 = |CK| \cdot |CE|,$$

$$|AF| \cdot |AD| = |AE| \cdot |AK|.$$

从这里我们有

$$\begin{cases}
b^2 - h^2 = \frac{b}{2} \left( \frac{b}{2} - y \right), \\
h(h - x) = \frac{b}{2} \left( \frac{b}{2} + y \right).
\end{cases}$$

求解该系统的 x，我们找到 $|DF| = x = \frac{b^2}{2h}$。

然而，这个解决方案不能被认为是详尽的——毕竟，其他可能性仍未得到检验（例如，当 $|DF| > |AD|$ 时，第二个交点位于 AC 边的延续上）。对每种情况的分析都会导致不同的系统，而且需要使用不同的定理（在情况 $|DF| > |AD|$ 中，将需要关于两个相交弦的定理）。

现在我们将给出这个问题的另一个几何解；亲自看看它不再取决于圆如何与给定三角形的边相交。

第二个解决方案。让我们将点 E 与点 D 和 F 连接起来。由于 DE 是直角三角形 CAD 斜边的中线，因此我们有： $|DE| = |AE| = \frac{b}{2}$ 和 $\widehat{EDF} = \widehat{EAD}$（等边三角形底角）。因此，直角三角形DEF和ADC是相似的。从这里

$$\frac{|DF|}{|AC|} = \frac{|DE|}{|AD|},$$

或者

$$|DF| = \frac{|AC| \cdot |DE|}{|AD|},$$

那是

$$|DF| = \frac{b^2}{2h}.$$

⟦folio 48⟧

图 3.

使用代数方法解决几何问题通常会导致复杂的无理方程。有时，通过附加消息，可以避免这种情况。这是两个典型的任务。

问题 3（路易斯安那州立大学，1973 年）。如果梯形的底长分别为 6 和 11，其中一条边的长度为 4，底边的角度和为 $\frac{\pi}{2}$，则求梯形的高。

第一个决定。让我们在梯形 $ABCD$ 中画出高度 $BE$ 和 $CF$ (图 3) 并放置$|BE| = |CF| = x$。我们假设$|AB| = 4$。从直角三角形$AEB$我们找到$|AE| = \sqrt{16-x^2}$。这就是为什么

$$|FD| = |AD| - (|AE| + |EF|) = (|AD| - |BC|) - |AE| = 5 - \sqrt{16-x^2}.$$

由于$AD$底角的和为$\frac{\pi}{2}$，所以直角三角形$AEB$和$CF$相似；因此，

$$\frac{|BE|}{|FD|} = \frac{|AE|}{|CF|}.$$

我们得到无理方程

$$\frac{x}{5 - \sqrt{16-x^2}} = \frac{\sqrt{16-x^2}}{x},$$

由此我们可以求出梯形的高度：

$$x = |BE| = 2,4.$$

第二个解决方案。让我们做一个额外的构造：将 $(BK)$ 平行于 $(CD)$ 绘制。我们得到（参见图 3和问题条件）一个直角三角形$ABK$，从中可以很容易地找到梯形的高度：

$$|BE| = \frac{|AB| \cdot |BK|}{|AK|} = \frac{|AB| \cdot \sqrt{|AK|^2 - |AB|^2}}{|AK|} = \frac{|AB| \cdot \sqrt{(|AD| - |BC|)^2 - |AB|^2}}{|AD| - |BC|} = \frac{4 \cdot \sqrt{(11-6)^2 - 16}}{11-6} = 2,4.$$

问题4. 在正方形$ABCD$的边$AD$和$CD$上，从边3取两个点$M$和$N$，使得折线$MDN$的长度等于正方形。线 $AM$ 和 $BN$ 相交于点 $E$。如果$|NE| = 4$，求线段$ME$的长度。

第一个决定。让我们用 $x$ 表示线段 $DN$ (图 4) 的长度。然后$|DE| = \sqrt{16-x^2}$。根据三角形$NDE$和$BAE$的相似性，我们有

$$\frac{|DN|}{|AB|} = \frac{|DE|}{|AE|},$$

那是

$$\frac{x}{3} = \frac{\sqrt{16-x^2}}{3 + \sqrt{16-x^2}}.$$

该无理方程与以下四次方程有关

$$x^4 - 6x^3 + 2x^2 + 96x - 144 = 0.$$

⟦folio 49⟧

图 5.

左边得到的多项式被分解为两个直角三角形的乘积：$x^2 + 2x - 6$和$x^2 - 8x + 24$。因此$(x^2 + 2x - 6)(x^2 - 8x + 24) = 0$。

该方程有一个正根：

$$x = |DN| = \sqrt{7} - 1.$$

现在我们可以轻松找到

$$|ME| = |MD| + |DE| = 3 - |DN| + \sqrt{16 - |DN|^2} = 3 - \sqrt{7} + 1 + \sqrt{16 - (\sqrt{7} - 1)^2} = 4 - \sqrt{7} + \sqrt{(V\overline{7} + 1)^2} = 5.$$

简单的答案表明还有另一种不太复杂的解决方案。这里是。

第二个解决方案。由于三角形 BCN 和 NDE 相似，则

$$\frac{|BC|}{|CN|} = \frac{|DE|}{|DN|},$$

或者

$$\frac{3}{3 - |DN|} = \frac{|DE|}{|DN|},$$

那是

$$3(|DE| - |DN|) - |DN| \cdot |DE| = 0.$$

考虑到$|MD| = 3 - |DN|$和$|DN|^2 + |DE|^2 = 16$，我们得到

$$|ME| = |MD| + |DE| = (3 - |DN|) + |DE| = \sqrt{(3 - |DN| + |DE|)^2} = \sqrt{9 + 16 + 2 \cdot 0} = 5.$$

凭借一些聪明才智，我们能够摆脱无理方程，根据我们自己的说法，这个方程并不常见！

申请人解决平面问题最常见的方法之一是使用三角学。当然，这是一个非常重要且有用的方法 - 有时引入三角函数是解决问题的自然而合理的途径。但是，在每种具体情况下，您应该考虑是否存在更简单的几何解决方案。这是一个恰当的例子。

问题 5（MSU，计算数学和控制网络学院，1971）。在三角形ABC中，AC边大于AB边，且顶点A处的角度等于α。点 R 取于 AC 边，因此$|AB| = |RC|$。设E为线段AR的中点，D为边BC的中点。求角 CED。

第一个解（三角函数）。让我们用字母 a、b、c 分别表示三角形 ABC 的边长，分别用字母 A、B、C 表示其角的值，并用字母 x 表示所需角 CED 的值。

然后（参见图5）：

$$\widehat{CDE} = 180^\circ - (C + x),$$

$$|CD| = \frac{a}{2},$$

$$|CE| = |CR| + |RE| = c + \frac{b - c}{2} = \frac{b + c}{2}.$$

利用正弦定理求三角形 CDE：

$$\frac{|CE|}{\sin CDE} = \frac{|CD|}{\sin CED},$$

那是

$$\frac{b + c}{\sin (C + x)} = \frac{a}{\sin x};$$

由三角形ABC：

$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C},$$

⟦folio 50⟧

那是
$$\frac{b+c}{\sin B+\sin C} = \frac{a}{\sin A}.$$

将对应关系（1）除以对应关系（2），我们得到
$$\frac{\sin B + \sin C}{\sin(C+x)} = \frac{\sin A}{\sin x},$$
或者，从$B = 180^\circ - (A+C)$开始，
$$\frac{\sin(A+C) + \sin C}{\sin A} = \frac{\sin(C+x)}{\sin x},$$

那是
$$\frac{2\sin\left(\frac{A}{2} + C\right)\cos\frac{A}{2}}{2\sin\frac{A}{2}\cos\frac{A}{2}} = \frac{\sin(C+x)}{\sin x},$$
在哪里
$$x = \frac{A}{2} = \frac{\alpha}{2}.$$

第二个解决方案（几何）。我们现在甚至将提出两个几何解决方案。

1°。让我们在三角形$ABC$中画一条中线$DF$。我们有
$$|FE| = |CE| - |CF| = \frac{b+c}{2} - \frac{b}{2} = \frac{c}{2} = |DF|,$$
也就是说，三角形$DFE$是等腰三角形。波兹尼
$$\widehat{CED} = \frac{1}{2}\widehat{CFD} = \frac{1}{2}\widehat{CAB} = \frac{\alpha}{2}.$$

2°。让我们对三角形$ABC$的角$A$进行除角$AK$。然后
$$\frac{|CK|}{|CA|} = \frac{a}{b+c}.$$
还有$\frac{|CD|}{|CE|} = \frac{a}{b+c}$，这意味着三角形$CDE$和$CKA$相似，并且线段$DE$平行于$AK$。
因此，$\widehat{CED} = \widehat{CAK} = \frac{\alpha}{2}$。

难道用“三角学”的方法解决这个问题还不能称得上是成功吗？ - 两种几何解决方案当然都更加优雅。但从某种意义上说，它们更加困难 - 毕竟，有必要签订额外的合同

练习
1（路易斯安那州立大学，1973 年）。在矩形 $ABCD$ 中，我们有：$|AB| = a$、$|AD| = b$ ($a > b$)。在$AB$边上找到$\angle CED \cong \angle AED$对应的点$E$。
2（新西伯利亚州立大学，1967 年）。在平凸四边形$ABCD$中，点$E, F, K, L$是边$AB, BC, CD, DA$的中点。线段$EK$和$FL$将该四边形分成四个较小的四边形。证明这些顶点位于点 $A$ 和 $C$ 的四边形的面积之和等于其他两个四边形的面积之和。
3（新西伯利亚州立大学，1974 年）。在梯形$ABCD$中，边$CD$垂直于底$AD$、$|BC| = a$、$|AD| = b$、$a < b$。基于$AD$，有一个点$M$，使得($MB$)垂直于($AC$)，($MC$)垂直于($BD$)。求梯形的高度。
4（MIPT，1970）。给定一个梯形 $ABCD$，底边为 $|AB| = a$、$|CD| = b$ ($a < b$)。通过顶点 $A, B$ 和 $C$ 的圆接触 [AD]。求对角线 $AC$ 的长度。
5（MIPT，1973）。半径为 $R$ 和 $r$ ($R > r$) 的两个圆在点 $A$ 处有外切线。通过在大圆上取的点 $B$，绘制一条直线，在点 $C$ 处与小圆相交。如果弦 $AB$ 的长度等于 $a$，求线段 $BC$ 的长度。
6（MIPT，1973）。在等梯形 $ABCD$ 中，底角 $AD$ 等于 $\frac{24}{25}$。半径为$R$的圆与底$AD$、边$AB$相切并经过顶点$C$；它分别在$BC$和$CD$边上切断了全等线段$MC$和$NC$。求线段 $BM$ 的长度。
7（密歇根州立大学，比诺法克，1973）。圆中有两个直径$AB$和$CD$，$M$是某个点。已知$|AM| = 15$、$|BM| = 20$和$|CM| = 24$。 $|DM|$等于什么？
8（密歇根州立大学地质学院，1974 年）。给定一个直角三角形 $ABC$，其顶点 $C$ 为直角。角度$CAB$等于$\alpha$。角 $ABC$ 的小角与边 $AC$ 相交于点 $K$。在边 $BC$ 上，作为直径，构造一个圆，该圆与斜边 $AB$ 相交于点 $M$。求角度 $AMK$。
