---
id: 1974-2-kushnir-metod-vspomogatelnogo-elementa-ebce4679
issue: kvant_1974_2
year: 1974
number: "2"
title: 辅助方法
authors:
  - Кушнир И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 53
page_labels: 46, 47, 48, 50, 51
tag: P3SM
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 654f873d2c8a1fc433024cde168f5395724a991860e9207d6b1a7c2d67e0208d
prompt_sha256: draft-1
translated_from: content/ru/1974/02/articles/12_kushnir-metod-vspomogatelnogo-elementa-ebce4679.md
source_content_sha256: 9fff92e5fedd3328d7e0f386d1f0728df2af4390465ac9fa251445d3795ab47e
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

方法
辅助的
元素
I.A.库欣尔

通过引入未在问题条件中直接指定的附加元素，可以促进大量几何问题的解决。这些元素可以是长度、面积、体积、角度。在他们的帮助下，绘制了一个方程，其中未知元素是所需元素，或者借助该元素可以轻松找到所需元素。有时，借助这个元素，画出的不是一个方程，而是问题条件所需的对应关系。

辅助线性元件
在平面问题中，如果所考虑的图形相似，则可以方便地引入线性元素或线性元素的比率。然后，利用比例或辅助几何构造，画出一个方程，将引入的作为方程成员的元素减少，不难找到所需的元素。

让我们考虑一下新西伯利亚国立大学提出的问题解决方案。

问题 1（NSU，1969）。通过三角形内的某一点，画出与三角形各边平行的三条线。这些线将三角形分为六部分，其中三部分是面积为 $S_1, S_2, S_3$ 的三角形。求这个三角形的面积。

开始求解，我们用面积$S_1, S_2, S_3$(图1)代替三角形的相似度，用面积S代替三角形ABC的相似度。另外，小三角形的边长DQ、QE、FK之和等于三角形ABC的边BC的长度。使用这些边作为辅助元素，我们得到方程

$$\frac{\sqrt{S_1}}{\sqrt{S}} = \frac{DQ}{BC}, \frac{\sqrt{S_2}}{\sqrt{S}} = \frac{QE}{BC}, \frac{\sqrt{S_3}}{\sqrt{S}} = \frac{FK}{BC}.$$

让我们把它们加起来：

$$\frac{\sqrt{S_1} + \sqrt{S_2} + \sqrt{S_3}}{\sqrt{S}} = \frac{DQ + QE + FK}{BC} = 1.$$

所以，$S = \left( \sqrt{S_1} + \sqrt{S_2} + \sqrt{S_3} \right)^2$。

如果问题条件中没有给出线性元素，并且需要找出角度之间的关系，建议输入辅助线段。

⟦folio 47⟧

任务 2（密歇根州立大学，物理系，1967 年）。
求等边三角形底角的余弦，已知其高的交点位于三角形的内切圆上。

根据条件，三角形$ABC$($AB = AC$)的重心$H$必须在三角形内部，因此$\angle A < 90^\circ$(图2)。我们引入一个辅助元素$a$——线段$BD$的长度，用$x$表示$\angle ABC$，用$O$表示内切圆的圆心。然后

$$\angle HCD = \frac{\pi}{2} - x, HD = a \mathrm{tg} \left( \frac{\pi}{2} - x \right) = a \mathrm{ctg} x = 2OD, OD = a \mathrm{tg} \frac{x}{2},$$

在哪里

$$\mathrm{ctg} x = 2 \mathrm{tg} \frac{x}{2}, \mathrm{tg}^2 \frac{x}{2} = \frac{1}{5},$$

$$\cos x = \frac{2}{3}.$$

引入一个辅助元素来寻找各种几何量的关系尤为重要。

任务 3（MAN，1968）。正截四边形帕拉米德的大底与其侧边界成$\alpha$角，与通过上下底邻边的平面成$\beta$角。求碱基面积之比。

让我们引入一个辅助元素$a$——paramid大底边的长度（图3）。该基地的面积为$a^2$。上底的边长可以用$a$、$\alpha$、$\beta$来表示。让我们考虑辅助梯形 $EE_1F_1F$，它是由垂直于底边并穿过边 $AB$ 和 $CD$ 中点的平面在 paramid 截面中获得的。让我们介绍更多辅助段$E_1H = h, E_1F_1 = x$。然后

$$HF = \frac{1}{2} (a + x),$$

$$EH = \frac{1}{2} (a - x), h = HF \mathrm{tg} \beta =$$

图 2.

$$= \frac{1}{2} (a + x) \mathrm{tg} \beta = EH \mathrm{tg} \alpha =$$

$$= \frac{1}{2} (a - x) \mathrm{tg} \alpha.$$

我们得到方程$(a + x) \mathrm{tg} \beta = (a - x) \mathrm{tg} \alpha$，由此

$$x = \frac{a \sin (\alpha - \beta)}{\sin (\alpha + \beta)},$$

$$\frac{s}{S} = \frac{x^2}{a^2} = \frac{\sin^2 (\alpha - \beta)}{\sin^2 (\alpha + \beta)}.$$

辅助元素 - 面积或体积

引入面积和体积作为辅助元素与引入线性元素类似。通过比较图形各个部分的面积和体积，可以获得问题的相对未知数的方程或必要的对应关系。最好找到那些面积和体积，它们的总和（差）给出给定图形的面积，以及面积的比率

⟦folio 48⟧

这些图形的线性元素要么是所需的，要么是必要对应关系的组成部分。

问题 4（密歇根州立大学，力学和数学，1960 年）。通过正三角形的链画一条平行于底边的直线。在内三角形的这条线上取任意一点M。证明M点到三角形底边的距离是M点到三角形各边距离的算术平均值。

令 $h_1, h_2, h_3$ 分别为点 M 到三角形 BC、AB、AC 边的距离 (图 4)。显然，$S_{\triangle AMB} + S_{\triangle CMB} + S_{\triangle AMC} = S_{\triangle ABC}$，或者$ah_1 + ah_2 + ah_3 = ah$，其中$a$是三角形ABC的边，$h$是它的高。所以$h = h_1 + h_2 + h_3$，但是$h_1 = \frac{h}{3}$，所以$h_2 + h_3 = h - h_1 = \frac{2}{3}h = 2h_1$，$h_1 = \frac{h_2 + h_3}{2}$。

问题 5. 给定一个外接圆的四边形 ABCD。证明从圆链到相对顶点的距离的平方与在 emix 顶点处收敛的边的乘积有关。

记号在图5上给出。需要证明$\frac{x^2}{y^2} = \frac{ad}{bc}$。

三角形AOD和BOC的高相等，所以

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{d}{b}.$$

另一边，

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{xv \sin \varphi_5}{yz \sin \varphi_6}.$$

让我们证明$\sin \varphi_5 = \sin \varphi_6$。为此，请注意 $\varphi_1 + \varphi_2 + \varphi_3 + \varphi_4 = \pi$（这是四边形所有角度之和的正数）、$\varphi_1 + \varphi_2 + \varphi_5 = \pi$、$\varphi_4 + \varphi_3 + \varphi_6 = \pi$。由此可见$\varphi_5 + \varphi_6 = \pi$、$\sin \varphi_5 = \sin \varphi_6$，由式(2)可得

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{xv}{yz}.$$

从对应关系（1）和（2'）我们有$\frac{xv}{gz} = \frac{d}{b}$，类似于$\frac{xz}{yv} = \frac{a}{c}$。改变最后两个等式，我们得到

$$\frac{x^2}{y^2} = \frac{ad}{bc},$$

将其中第一个除以第二个，我们得到

$$\frac{v^2}{z^2} = \frac{cd}{ab}.$$

我们来分析一个辅助元素是体积的问题。

*) 有关面积法的其他材料可以在杂志 «Kvant»，1971 年，第 12 期中阅读。

⟦folio 50⟧

图 8.

测角函数，然后引入辅助角。然后，利用正弦或余弦定理，求解三角形，找到其分量，将某个条件写成方程的形式。

任务 8（密歇根州立大学，力学和数学，1962 年）。在三角形的 emodret 平面上通过正三角形的链绘制任意直线。证明从三角形顶点到同一条直线的距离平方和不取决于直线的选择。

设点 $O$ 为三角形 $ABC$ (图 8) 的中心。点$D, E, F$分别是顶点$A, B, C$在直线$l$上的投影，$R$是三角形$ABC$外接圆的半径。我们引入一个辅助角$\varphi$，表示为$\Rightarrow BOE$。然后

$$\Rightarrow AOD = \Rightarrow AOB - \Rightarrow BOD = \varphi - \frac{\pi}{3}.$$

（自己检查方括号中的总和是否为 $\frac{3}{2}$）。

任务 9（MIPT，1967）。在直轴 ABCD 的底边，绘制一个与上底边$A_1B_1C_1D_1$相交的平面。三面角 $B$ 和 $D_1$ 包含接触平面且半径为 $r = \frac{a}{5}$、$R = \frac{a}{4}$ 的球。说出平行六面体的高度。

平行六面体 (图 9) 的对角线部分 $DBB_1D_1$ 将穿过球 $O$ 和 $O_1$ 的中心。设$L$和$L_1$为球与平行六面体底面的接触点，$N$和$N_1$为球与给定平面的接触点（我们还不知道它们是否位于平行六面体中）

图 9.

⟦folio 51⟧

或者在里面，但我们不需要它），OF和$O_1E_1$是角NOL和$N_1O_1L_1$的二线（点$F$是BD的中间），$EE_1$是平行六面体的高度，$OL = ON = r$，$O_1L_1 = O_1N_1 = R$。让我们输入 $\Rightarrow BFE_1 = 2\alpha$、$L_1E_1 = x$、$E_1B_1 = y$、$FE = z$。然后

$$h = z \mathrm{tg} 2\alpha, \quad z = FB - BE = \frac{a \sqrt{2}}{2} - y, \quad y = a \sqrt{2} - x - D_1L_1 = a \sqrt{2} - x - R \sqrt{2} \quad \text{и} \quad z = x + R \sqrt{2} - \frac{a \sqrt{2}}{2} = x - \frac{a \sqrt{2}}{4}.$$

根据三角形$O_1L_1E_1$和$OLF$的相似性，可以得出$\frac{x}{R} = \frac{FL}{r}$、$FL = FB - LB = \frac{a \sqrt{2}}{2} - r \sqrt{2} = \frac{3a \sqrt{2}}{10}; \quad x = \frac{3}{8} a \sqrt{2}, \quad z = \frac{a \sqrt{2}}{8}$。

从三角形$OLF$有$\mathrm{tg} \alpha = \frac{r}{FL} = \frac{\sqrt{2}}{3}$，从$h = \frac{3}{14} a$。

问题 10（密歇根州立大学，力学和数学，1963 年）。正三角形平行六面体的侧边等于$b$，侧边之间的角度等于$\varphi$。找到底座的一侧。

让我们从点 $B$ 和 $C$ 到侧边 AS (图 10) 放置垂线。很容易验证这两条垂线的底是一个点$D$（证明），因此是$\star BDC = \varphi$。

我们引入辅助角$\star BAS = \alpha$并画出边心线SK

图 10.

金字塔。显然$AB = 2AK = 2b \cos \alpha$。因此，要解决这个问题，计算$\cos \alpha$就足够了。由于$\alpha < 90^\circ$，那么从三角形$BAD$我们有$\alpha = \arcsin \frac{BD}{AB}$。

反过来，线段 $BD$ 的长度由三角形 $BLD$ 确定（DL 是三角形 $BDC$ 的高度）：

$$BD = \frac{BL}{\sin \frac{\varphi}{2}} = \frac{AB}{2 \sin \frac{\varphi}{2}}.$$

$\alpha = \arcsin \frac{1}{2 \sin \frac{\varphi}{2}}$，来自

$$AB = b \sqrt{4 - \frac{1}{\sin^2 \frac{\varphi}{2}}}.$$

保姆有权利

1（MIPT，1969）。圆内接于三角形 $ABC$，在点 $D$ 处与边 $AB$ 相切，在点 $E$ 处与边 $BC$ 相切。求三角形的内角，如果

$$\frac{BD}{AD} = \frac{1}{2}, \frac{BE}{CE} = \frac{1}{3}.$$

2（MIPT，1969）。在正四面体$ABCD$中，线段$MN$连接边$AC$的中点与面$BDC$的中心，点$E$位于边$AB$的中点。求线段 $MN$ 和 $DE$ 之间的角度。

3（莫斯科工程物理学院，1971）。在底边为 $a$ 和 $b$ 的梯形中，通过对角线的交点画一条平行于底边的直线。求该直线被梯形各边截断的线段的长度。

4（MIET，1970）。给定一个三角形$ABC$，在$AC$边上取一个点$E$，以便$AE : EC = a$，在$AB$边上取一个点$D$，以便$AD : DB = b$。进行了$CD$和$BE$段。求所得四边形的面积与给定三角形的面积之比。

5（密歇根州立大学，物理学家，1969）。帕拉酰胺刻在一个球中，其侧边等于 $c$。它的底面是一个矩形，其边通过侧面的平面以$\alpha$和$\beta$弧度对向球的截面。确定外接球的半径。

6（密歇根州立大学，力学和数学，1961）。在半径为$R$的圆上，给出两个点$A$和$B$，它们之间的距离为$l$。如果点 $C$ 也位于该圆上，则 $AC^2 + BC^2$ 之和可取的最大值是多少？

7（NSU，力学和数学，1969）。正四边形Param的侧边二面角等于$\alpha$，内接球的半径等于$R$。找到 paramid 的完整表面。
