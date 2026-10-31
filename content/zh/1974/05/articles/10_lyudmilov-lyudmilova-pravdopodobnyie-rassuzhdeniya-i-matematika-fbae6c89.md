---
id: 1974-5-lyudmilov-lyudmilova-pravdopodobnyie-rassuzhdeniya-i-matematika-fbae6c89
issue: kvant_1974_5
year: 1974
number: "5"
title: 合理的推理和数学
authors:
  - Людмилов Д. С.
  - Людмилова С. Д.
rubric: raznoe
page_first: 45
page_last: 49
page_labels: 43-47
tag: J448
lang: zh
source: kvant_digital
extraction: vision
content_sha256: df01c603e6f786f7c5d2bee62c61b67e32d8a37199a9d948288db8e87ada468f
prompt_sha256: draft-1
translated_from: content/ru/1974/05/articles/10_lyudmilov-lyudmilova-pravdopodobnyie-rassuzhdeniya-i-matematika-fbae6c89.md
source_content_sha256: af303c822711c19aa5cc96cb9bd9dfe75df1ebc5aa787d7c55f050e68e03b292
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

合理的推理和数学

D.S.柳德米洛夫, S.D.柳德米洛娃

“当你写下某件事非常印度化时，你可能会这么想。但是，一个月、两个月或六个月后，当你在手稿中再次阅读它时，你还会继续数数吗？......
当你欠朋友或参加研讨会时，这个地方是否被认为非常印度化？或者有人在你通知后提出问题并提出问题吗？你说服了他还是迷惑了他？对这些反问句的回答仅限于使用“显然”一词。如果还有其他规则，最重要的是我们知道它；违反这条规则是数学错误最常见的来源：确保“显而易见”是正确的。”
P.R.哈尔莫斯。如何写数学文章。

由直觉推动的合理推理在数学研究和寻找问题解决方案中发挥着重要作用。如果数学家没有从数学直觉中得到“提示”，他将更难找到新数学问题的解决方案。

对于有办法解决问题的学生来说也是如此。寻找解决方案是提出各种假设及其一致的数学测试。

不……小心点！数学的严谨性不应被低估，直觉也不应被高估。非常直观的东西并不总是正确的。

穿越

让我们看一个值得尊敬的例子，它展示了为什么数学家努力严格证明“显而易见的”。

P. Yu的书里就有这样的问题。 Germanovich“通信数学问题集”（M.，Uchpedgiz，1960）。

3.5 m 宽的通道有一个转弯 (图 1)。如果有两个，如何组织穿越它

图 1.
图 2.

⟦folio 44⟧

板子，但每块板子的长度只有3m？

作者对问题的解决方案如图2所示。从这个图来看，作者假设：

(1) 第一块板的 A 边和 B 边应靠在沟渠的边缘上（我们假设板不弯曲）；
(2)第一块板AB应与沟渠边缘形成45°角；
(3)第二块板CD必须垂直于AB(C点为沟对角顶点)。
(4) 指定尺寸的板的任何排列都是可能的（因此，确保交叉）。

所有这些假设在直觉上都是合理的，对吗？但是...让我们检查一下。

第一个惊喜

让我们从假设 4 开始。很容易相信它的有效性：使用 图 2 中所示的方法，使用板的额外 2.5 m (6 m - 3.5 m) 真的不可能得到不足的 0.5 m (3.5 m - 3 m) 吗？

不过，让我们计算一下。从 图 2 我们有：

$$OC = 3,5\sqrt{2} \text{ m}, \quad OD = \frac{1}{2}AB = 1,5 \text{ m},$$

$$CD = OC - OD = (3,5\sqrt{2} - 1,5) \text{ m}.$$

如果满足不等式则交叉是可能的

$$3,5\sqrt{2} - 1,5 \leq 3$$

图 3.

图 4.

或 3.5\sqrt{2} \leq 4.5，因此 7\sqrt{2} \leq 9，但这是不正确的。因此实际上CD > 3 m！

由此可见，不可能穿越吗？还没有，因为这个选择是在满足前三个假设的前提下做出的。也许还有另一种提供交叉的木板排列方式？

第二个惊喜

从 图 3 可以清楚地看出，假设 1 是正确的：事实上，如果第一块木板的一端 A（或两端）没有位于沟渠的最边缘，那么这块木板可以移动到更高的位置。

不难证实假设3：如果第二块板CD不垂直于AB（见图4），那么它就必须更长。

图 5.

⟦folio 45⟧

图 6.

仍有待检验假设2。
乍一看，这个假设似乎得到了证实。事实上，考虑第一块板的两个位置（图 5）：$MN$（$\Rightarrow MNO = 45^\circ$）和$AB$（$\Rightarrow ABO \neq 45^\circ$）。设$CD \perp MN$、$CP \perp AB$、$K$为$CP$和$MN$的交点。很明显，$CP > CD$，因为$CP > CK$和$CK > CD$（斜边大于边）。

然而，线段$MN$和$CP$可能不相交；对应的板子位置如图 6 所示。请注意图 $CD \geq CP$。前面的推理不成立。显然，非总统几何地检验假设2并不容易。

让我们尝试用代数的方式来计算这个问题。让我们用$a$表示通道的宽度，用$l$（$a > l$）表示每块板的长度，用$\alpha$（图7）表示$\Rightarrow ABO$，我们将考虑值$a$和$l$常量，以及值$\alpha$变量。假设 2 表明，线段 $CP$ ($CP \perp AB$) 的最小长度在 $\alpha = 45^\circ$ 处实现。因此，我们需要将$y = CP$表示为$\alpha$的函数。

让我们执行 $ECF \parallel AB$ 和 $OLK \perp AB$ (图 7)。然后

$$EF = EC + CF = \frac{a}{\cos \alpha} + \frac{a}{\sin \alpha}; \quad OF = EF \cos \alpha = a + \frac{a \cos \alpha}{\sin \alpha}; \quad OK = OF \sin \alpha = a \sin \alpha + a \cos \alpha; \quad OB = AB \cos \alpha = l \cos \alpha; \quad OL = OB \sin \alpha = l \cos \alpha \sin \alpha; \quad y = LK = CP = OK$$

$-OL = a \sin \alpha + a \cos \alpha - l \sin \alpha \cos \alpha$.

让我们检查一下函数 $y(\alpha)$ 的最大值和最小值。让

$$x = \sin \alpha + \cos \alpha = \sqrt{2} \sin (45^\circ + \alpha).$$

那么$x^2 = 1 + 2 \sin \alpha \cos \alpha$，

$$\sin \alpha \cos \alpha = \frac{x^2 - 1}{2},$$

$$y(x) = ax - \frac{l(x^2 - 1)}{2} = \frac{-lx^2}{2} + ax + \frac{l}{2}.$$

如果函数$y(x)$的定义域不受限制，那么它不会有最小值，但在$x = \frac{a}{l}$（图8）处有最大值。

该最大值等于

$$\frac{1}{2} \left( -l \frac{a^2}{l^2} + 2a \frac{a}{l} + l \right) = \frac{a^2 + l^2}{2l}.$$

然而，函数$y(x)$的定义域是有限的，$x = \sqrt{2} \sin (\alpha + 45^\circ)$和$0 \leq \alpha \leq 90^\circ$也是如此。

函数$x(\alpha)$在$\alpha = 0^\circ$处具有最小值$x = 1$（当$\alpha = 0^\circ$时实现该最小值——板$AB$始终位于同一个承载器上），在$\alpha = 45^\circ$处具有最大值$x = \sqrt{2}$。由此得出函数$y = f(x)$的定义：$1 \leq x \leq \sqrt{2}^*$。

*) 事实上，对于$\alpha$，接近$0^\circ$ ($90^\circ$) 和$AB$，小于$\alpha$，图 7 上的点$P$ 将位于延续$AB$ 上，即，在 bereru 上，长度小于 $CP$ 的棋盘将是必需的，但如果板$CP$的末端$P$位于bereru上，则$CP$在$\alpha = 0^\circ$处最小，并且与$y(x)$在$x = 1$处重合。

⟦folio 46⟧

横坐标轴上的点 $x = 1$ 始终位于点 $x = 0$ 和 $x = \frac{a}{l}$ ($a > l$) 之间。点 $x = \sqrt{2}$ 可以占据两个位置：点 $x = \frac{a}{l}$ 的左侧 (图 9) 或该点的右侧 (图 10)。

在这两种情况下，函数 $f(x)$ 的图形都是点 $x = 1$ 和 $x = \sqrt{2}$ 之间的弧 $AB$ 抛物线。

在第一种情况$\left(\frac{a}{l} \geq \sqrt{2}\right)$，函数$y(x)$在$x = \sqrt{2}$（$\alpha = 45^\circ$）处达到等于$a\sqrt{2} - \frac{l}{2}$的最大值（！），在$x = 1$处达到等于$a$（图9）的最小值；在这种情况下交叉是不可能的，因为对于任何$1 < x \leq \sqrt{2}$都会有$y > a$）。

我们得到的结果与直觉预期完全相反！ 图 6 不针对泵源。如果$\frac{a}{l} \geq \sqrt{2}$，那么在$\alpha = 45^\circ$处，点$C$到第一个访问点的距离$CP$不是最小的，而是最大的！根据我自己的说法，提出假设 2 的直觉非常漂亮地欺骗了我们。另外，在$l \leq \frac{a\sqrt{2}}{2}$处（例如在$a = 3,5$米，$l \approx 2,4$米）处的不可能性很难直观地预测，尽管很明显对$l$应该有某种限制，但对于非常小的$l$来说，穿越是不可能的。

让我们继续研究

让我们看看如果$1 < \frac{a}{l} < \sqrt{2}$，穿越是否总是可能的。在这种情况下，函数 $y(x)$ 的最大值等于 $\frac{a^2 + l^2}{2l}$ (图 10)。我对这个函数的最小值不感兴趣。该函数在 $x = 1$ 或 $x = \sqrt{2}$ 处达到最小值。令 $y(1) \leq y(\sqrt{2})$ (图 10)。从$y(1) = a$，$y(\sqrt{2}) = a\sqrt{2} - \frac{l}{2}$，然后$a\sqrt{2} - \frac{l}{2} \geq a$，因此$\frac{a}{l} \geq \frac{\sqrt{2} + 1}{2}$。因此，在 $\frac{\sqrt{2} + 1}{2} \leq \frac{a}{l} < \sqrt{2}$ 处交叉是不可行的，因为在 $1 < x \leq \sqrt{2}$ 处将有 $y(x) > a$ (图 9)。仍有待考虑情况$1 < \frac{a}{l} < \frac{\sqrt{2} + 1}{2}$。

在本例中$y(\sqrt{2}) = a\sqrt{2} - \frac{l}{2} - \frac{l}{2} < a = y(1)$，函数$y(x)$的最小值为$a\sqrt{2} - \frac{l}{2}$ (图 11)，并在$x = \sqrt{2}$、$\alpha = 45^\circ$处实现。如果该最小值不超过第二个点的长度$l$，即$a\sqrt{2} - \frac{l}{2} \leq l$或$\frac{a}{l} \leq \frac{3\sqrt{2}}{4} (< \frac{\sqrt{2} + 1}{2})$，则发生交叉。

准备中，我们发现$\frac{a}{l} > \frac{3\sqrt{2}}{4}$是不可能穿越的

⟦folio 47⟧

并且可以与

$$\frac{a}{l} \leq \frac{3\sqrt{2}}{4}.$$ (*)

自$\frac{3,5}{3} > \frac{3\sqrt{2}}{4}$以来，关系$\frac{a}{l} = \frac{3,5}{3}$不满足条件(*)。

从不等式$\frac{3,5}{l} \leq \frac{3\sqrt{2}}{4}$我们发现如果$l \geq \frac{7\sqrt{2}}{3} \approx 3,3$m则交叉是可能的。

几何交叉的不可能性将表明被第一和第二码头“扫出”的点集不相交（图12）。

如果$\frac{a}{l} = \frac{3\sqrt{2}}{4}$，则这些集合只有一个公共点。

如果$\frac{a}{l} < \frac{3\sqrt{2}}{4}$，则指示集合的交集区域包含无限个点集。

如果$\frac{a}{l}$比$\frac{3\sqrt{2}}{4}$更接近1（集合的相交面积足够大），则第一个码头可以放置在与海岸不成$45^\circ$角度的位置，而第二个码头 - 不垂直于第一个码头，您甚至可以将其末端移离角度顶部（点$C$）。

结果

从上述内容中可以得出什么结论？我们所有的推理是否都支持假设 2 的直观预测是正确的这一事实？

我们已经看到假设 2 在公式中

a) 第一个棋盘距离$C$，如果$\alpha = 45^\circ$，
不正确。在措辞上

b) 如果可以穿越($\frac{a}{l} \leq \frac{3\sqrt{2}}{4}$)，那么第一块木板就在我们距$C$的距离处，如果$\alpha = 45^\circ$，

假设 2 成立。然而，这个结果很难直观地预测。

与所考虑的问题相关，出现了新的有趣的问题。以下是其中一些。

练习

1. 如果每个码头的覆盖范围应为 20 厘米（每端 10 厘米），那么两块相同的板（通道宽度为 3.5 m）的最小长度是可以交叉的？

2. 使用两块不同长度的木板推导穿过宽度为 $a$ 的通道的可能性的条件：$m$ 和 $n$（$m < a$，$n < a$）。特别是，如果$a = 3,5$米和$m + n = 6$米，找出是否可以穿越。

3*。您可以使用三块木板穿过食物通道。 $a$、$b$、$c$ 板的长度是多少？三块 3 m 的木板够吗？*)

4*。航道的两个分支具有不同的宽度：$a$（$m$）和$b$（$m$）（$a > b$），并且有两个长度相同或不同的码头：$m$和$n$ - 其中一个小于$b$。推导出交叉可能性的充要条件。

5*。通道的分支形成任意（而非直角）角度$\varphi$，其宽度为$a$和$b$，码头具有不同的长度（$m$和$n$）。什么条件下可以穿越？

文学

1. D. Polya，数学和合理推理，伊利诺伊州，1957 年。

2. D. Polya，数学发现，M.，“科学”，1970 年。

3. D. Polya，《如何解决问题》，M.，Uchredgiz，1957 年。

4. G. D. Balk，M. B. Balk，合理性测试。 «Kvant»，1972 年，第 1 号。

*) 不需要解决任务3-5；他们的解决方案非常困难、繁琐，并且需要超出学校课程的知识。
