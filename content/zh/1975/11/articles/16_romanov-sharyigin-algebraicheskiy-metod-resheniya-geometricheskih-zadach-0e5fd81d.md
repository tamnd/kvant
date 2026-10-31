---
id: 1975-11-romanov-sharyigin-algebraicheskiy-metod-resheniya-geometricheskih-zadach-0e5fd81d
issue: kvant_1975_11
year: 1975
number: "11"
title: 解决几何问题的代数方法
authors:
  - Романов С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45-49
tag: PK74
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0a4ccb4f016843371fbc4fb2672efe20680632db6f84827217bd9b4e649a14f2
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/16_romanov-sharyigin-algebraicheskiy-metod-resheniya-geometricheskih-zadach-0e5fd81d.md
source_content_sha256: d4e5d5a3932e4a29df1e6980f7fa61687fb82c87e1c053a5ebf40f084c045eb3
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

解决几何问题的代数方法

S.V.罗曼诺夫、I.F.沙里津

当你在考试中遇到平面问题时，通常不值得浪费时间来寻找几何解或代数解的理性解。当然，几何解通常更优雅，而代数解包含繁琐的表达式，但在考试中，与优化不同，练习解的优雅并不影响成绩。因此，考试中解决几何问题的主要“武器”就是代数方法。这就是我们将在本文中讨论的内容。

首先，我们针对同一问题提出两种解决方案。

问题1.证明$l^2 = ab - mn$(图1)。让我们输入$\Rightarrow ADB = \alpha$。根据三角形 $ABD$ 和 $BDC$ 的余弦定理，我们有：
$$a^2 = l^2 + m^2 - 2ml \cos \alpha,$$
$$b^2 = l^2 + n^2 + 2nl \cos \alpha.$$ (2)
让我们将 (1) 乘以 $n$，将 (2) 乘以 $m$，然后将结果表达式相加。给定$\frac{m}{n} = \frac{a}{b}$，我们可以轻松地将总和转换为$l^2 = ab - mn$的形式。

这就是代数方法。

在阅读以下解决方案之前，请尝试自己解决此几何问题。

因此，这是一个纯粹的几何解决方案。让我们围绕三角形 $ABC$ 画一个圆 (图 2)，并继续做 bissertis，直到它在点 $E$ 处与该圆相交。由著名的定理$mn = l \cdot DE$。另外，根据三角形$BCE$和$ABD$的相似性，它遵循$\frac{a}{l} = \frac{l + DE}{b}$，由此得出$ab = l^2 + l \cdot DE$。将$l \cdot DE$替换为$mn$，我们得到了所需的结果。

图 1.
图 2.

⟦folio 46⟧

当然，这个解决方案比前一个解决方案更短、更优雅，但可能需要相当多的时间才能弄清楚。

代数方法基于某些标准技术。代数方法有两种类型：

a) “直接计数”；
b) “画出一个方程。”

“直接账户”的本质如下。我们将问题条件中指定的量和需要找到的量与整数个中间量连接起来，每个中间量都是通过前面的顺序确定的。

问题 2（密歇根州立大学地理学院，1966 年）。在具有边 a 和 b 以及角 α 的平行四边形中，绘制四个角的 bicsecret。求以 bicsecris (图 3) 为界的四边形的面积。

首先，制定解决问题的计划是有用的，换句话说，写下可以顺序计算的整数元素，将给定的内容与需要找到的内容联系起来。

首先，请注意 MNPQ 是一个平行四边形。让我们依次找到$\triangle ABC$、$\triangle ABM$、$\triangle AMB = \triangle QMN$。然后从$\Delta BCQ$（根据正弦定理）我们从$\Delta BMA - BM$找到BQ，从$\Delta NAD - AN$找到AM。这样就很容易计算出MN和QM以及所需面积$S = QM \cdot MN \cdot \sin \triangle QMN$。

所以，$\triangle ABC = 180^\circ - \alpha$，$\triangle ABM = \frac{180^\circ - \alpha}{2}$，$\triangle AMB = 90^\circ = \triangle QMN$，即MNPQ是一个矩形。 $BQ = a \sin \frac{\alpha}{2}, BM = b \sin \frac{\alpha}{2}, MQ = BQ - BM = (a - b) \sin \frac{\alpha}{2}$等

答案如下：

$$S = \frac{1}{2} (a - b)^2 \sin \alpha.$$

现在让我们举一个涉及“编写方程”的任务的例子。

问题 3（密歇根州立大学地理学院，1973 年）。在给定的平面上有一个直角。圆心在角内，与角的一侧相切，与另一侧相交于 A 点和 B 点，与角平分线相交于 C 点和 D 点； $AB = \sqrt{6}, CD = \sqrt{7}$。求圆的半径。

令 $O$ 为圆心，$R$ 为半径，$M$ 为切点 (图 4)。从中心到 AB 的距离用 x 表示。您可以立即创建第一个方程：$R^2 - x^2 = AN^2$。

让我们给出$OP \perp CD$，$OP = \frac{OE}{\sqrt{2}} = \frac{R - x}{\sqrt{2}}$。现在我们可以创建第二个方程：

$$R^2 - \left( \frac{R - x}{\sqrt{2}} \right)^2 = CP^2.$$

让我们使用 $AN = \frac{\sqrt{6}}{2}$ 这个事实，

⟦folio 47⟧

$$CP = \frac{\sqrt{7}}{2},$$ 并创建一个系统
$$\begin{cases} R^2 - x^2 = \frac{6}{4}, \\ R^2 - \left( \frac{R - x}{\sqrt{2}} \right)^2 = \frac{7}{4}. \end{cases}$$

解决它，我们找到$R = \sqrt{2}$。

当解决涉及“组成方程”的问题时，通常不需要未知数的数量和方程的数量一致。重要的是，在构造方程时，使用由条件产生的所有对应关系。如果满足此要求，则必须由复合系统确定必要的未知数或未知数的组合。

在“直接计数”问题中也可以找到类似的系统。

问题 4. 半径为 $R$ 和 $r$ ($R > r$) 的圆在点 $A$ 处内切。大圆的弦CD垂直于小圆的直径$AB$，$E$是$CD$与半径为$r$的圆的交点，点$E$和$C$位于远​​离$AB$的一侧。求三角形 $AEC$ 的外接圆的半径。

我们用$\varphi$表示$\triangle CEA$，用$a$（图5）表示$AF$。从三角形$CAM$我们得到$AC = \sqrt{2aR}$，与$AE = \sqrt{2ar}$类似。使用三角形 $AEC$ 的正弦定理，我们获得原始半径的值

从三角形$FEA$很容易找到$$\frac{AC}{2 \sin \varphi}.$$sin$\varphi$的值。答案：$\sqrt{Rr}$。

我们必须引入参数$a$、$\varphi$，因为问题的条件并不能确定几何配置是否完整。但这些参数不包含在答案中。

问题 5（MIPT，1967）。在直角三角形$ABC$kamet$AB = 3$，kamet$AC = 6$。半径为 1、2、3 的圆心分别位于点 $A$、$B$ 和 $C$。求与三个给定圆中的每一个外切的圆的半径。

令 $O$ 为所需圆的中心，$x$ 其半径，$\angle OAC = \alpha$ (图 6)。让我们写出三角形$AOC$和$AOB$的余弦定理。我们得到一个方程组
$$\begin{cases} (x+3)^2 = (x+1)^2 + 36 - 12(x+1)\cos \alpha, \\ (x+2)^2 = (x+1)^2 + 9 - 6(x+1)\sin \alpha. \end{cases}$$

通过这些方程表达sin$\alpha$和cos$\alpha$并使用对应关系$\sin^2 \alpha + \cos^2 \alpha = 1$，我们得到一个仅包含一个未知数$x$的方程；解出这个方程，我们得到答案：$x = \frac{8\sqrt{11} - 19}{7}$。

请注意，使用余弦定理来组成方程是最常用的定理之一，并且发挥着整体作用

⟦folio 48⟧

马在解决几何问题中发挥着重要作用；这在很大程度上取决于经验和直觉。

问题 6（MIPT，1966）。地震ABC的平分线AM和BN相交于O点。已知AO = $\sqrt{3}$ MO，NO = $(\sqrt{3}-1)$ BO。查找 ABC 重新学课程。

让我们引入以下未知数 (图 7)：BC = x，AC = y，AB = z。 $\frac{MC}{BM} = \frac{AC}{AB}$，所以 MB = $\frac{zx}{y+z}$，同样 AN = $\frac{yz}{x+z}$。现在，考虑具有平分线 BO 和 AO 的三角形 BMA 和 BAN，很容易得到以下方程组：

$$\begin{cases} \frac{x}{z+y} = \frac{1}{\sqrt{3}}, \\ \frac{y}{x+z} = \sqrt{3}-1. \end{cases}$$

接下来，您可以用一件事物（例如，用 x）表达所有未知数，并使用余弦定理求出三角形的角度 - $30^\circ$、$60^\circ$ 和 $90^\circ$。尝试使用未知的起始角度来解决这个问题，你会发现解决方案变得更加复杂。

需要注意的是，代数方法解决的大多数问题都可以有两种解——“直接计算”和“方程组”；这些方法不会相互影响。

问题7. 在锐角$\alpha$内，取点A，远离p和q处的角的边。求 A 点到角顶点的距离。

设M为AC与OB的交点(图8)，容易看出$\triangle BAM = \alpha$。现在我们找到 MC = q + $\frac{p}{\cos \alpha}$，OC = MC $\cdot$ctg $\alpha$ = $\frac{q \cos \alpha + p}{\sin \alpha}$。我们求出距三角形 AOC 所需的距离 AO：

$$AO = \frac{\sqrt{p^2 + 2pq \cos \alpha + q^2}}{\sin \alpha}.$$

这就是“直接计数”。同时，解决问题“编方程”并不困难，绕过路径的解决方案在多样性上也不逊色。所以，“编出方程式”。

让我们引入未知数$\triangle AOC = \varphi$，AO = x。检查了三角形 AOB 和 AOC 后，我们构建了一个包含两个未知数的两个方程组：

$$\begin{cases} x \sin \varphi = q, \\ x \sin (\alpha - \varphi) = p. \end{cases}$$

自己解决这个系统。

如果您再次仔细查看文章中给出的示例，很容易注意到几乎所有示例中都使用了许多几何考虑因素进行了一些附加构造。因此，求解平面

⟦folio 49⟧

图 9.

代数方法，我们不应该忘记这是一个平面问题，而不是代数问题，也就是说，不能使用许多几何考虑因素，因为它们通常会原谅解决方案。否则，您可以将一个简单的几何问题变成一个更麻烦的代数问题，例如，与同一招生手册的作者一起解决以下问题时就是这种情况。

任务 8（密歇根州立大学地理学院，1969 年）。在平衡梯形ABCD中，底AD=12，BC=6，梯形的高为4。Design_AC将梯形的角BAD分成角BAC和CAD。这些角度中哪个更大？

上述手册中提出的该问题的解决方案如下。令 $\Rightarrow BAC = \alpha$ (图 9), $\Rightarrow CAD = \beta$。您可以先计算$tg \Rightarrow BAD = tg(\alpha + \beta)$，然后计算$tg \beta$，最后使用三角公式求出$tg \alpha$。比较$tg \alpha$和$tg \beta$，我们就得到了问题中提出的问题的答案。同时，一个重要的解决方案是注意$\Rightarrow BCA = \beta$和$AB = 5$（根据毕达哥拉斯定理）。从三角形 $ABC > \beta$ 开始，因为在三角形中，较大的边与较大的边相对。

练习
1（密歇根州立大学地理学院，1966 年）。在平衡梯形中，底边为 $a$ 和 $b$，二边形与底边的角度为 $\alpha$。求连接对角线交点与梯形边中线的线段长度。

2（密歇根州立大学，物理学家，1963 年）。在半径为 $R$ 的圆中，通过直径为 $M$ 的点，以与直径成 $\varphi$ 的角度绘制弦 $AB$；同时$BM : AM = p : q$。通过点 $B$ 绘制垂直于给定直径的弦 $BC$，并将点 $C$ 连接到点 $A$。求三角形$ABC$的面积。

3（密歇根州立大学经济学院，1968 年）。在梯形$ABCD$中，大底$a$处的角度为$\alpha$和$\beta$，梯形的高度为$h$。令$O_1, O_2, O_3, O_4$分别为三角形$ABC, BCD, CDA, DAB$的外接圆的圆心。求四边形$O_1O_2O_3O_4$的面积。

4. 半径为 $R$ 和 $r$ 的圆相交。让我们为它们画一条共同的切线。令圆的交点$A$与切点$B$和$C$位于中心线的相对两侧。求三角形 $ABC$ 的外接圆的半径。

5（密歇根州立大学，机械工程，1968 年）。在凸四边形$ABCD$中，角$ABC$的二等分线与边$AD$相交于点$M$，并且从顶点$A$到边$BC$的垂线与$BC$相交于点$N$，因此$BN = NC$和$AM = 2MD$。如果四边形 $ABCD$ 的周长为 $5 + \sqrt{3}$、$\Rightarrow BAD = 90^\circ$、$\Rightarrow ABC = 60^\circ$，求其边长和面积。

6（MIPT，1967）。半径为 $R$ 和 $r$ 的圆在点 $A$ 处内切。求正三角形 $ABC$ 的边，其顶点 $B$ 和 $C$ 分别位于半径为 $R$ 和 $r$ 的圆上。

7. 直线$l$分别与等腰三角形$ABC$的侧边$AB$和$BC$相交于点$M$和$N$。已知$\frac{AM}{BM} = m$、$\frac{CN}{BN} = n$。求直线除以从顶点 $B$ 垂下的三角形高的比率。

8（密歇根州立大学，物理学家，1969）。在三角形 $ABC$ ($AB \neq AC$) 中，从顶点 $B$ 和 $C$ 到边 $AC$ 和 $AB$ 绘制的中线。因此，与这些边成反比。如果 $BC = a$、$\Rightarrow BAC = a$，求三角形的边 $AC$ 和 $AB$。

9（密歇根州立大学，机械工程，1971 年）。你可以在四边形$ABCD$上写字，然后在它周围画一个圆。这个四边形的对角线互相垂直。如果圆的半径为$R$和$AB = 2BC$，求其面积。

10（密歇根州立大学，物理学家，1974 年）。从边 1 开始有两个相同的正三角形 $ABC$ 和 $CDE$ 位于平面上，因此它们只有一个公共点 $C$ 和 $\Rightarrow BCD < \pi/3$。点$K$是$AC$的中间，$L$是$CE$的中间，$M$是$BD$的中间。三角形$KLM$的面积等于$\sqrt{3}/5$。找到$BD$。
