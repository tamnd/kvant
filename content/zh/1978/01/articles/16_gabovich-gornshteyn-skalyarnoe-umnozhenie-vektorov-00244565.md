---
id: 1978-1-gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565
issue: kvant_1978_1
year: 1978
number: "1"
title: 标量向量乘法
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 54
page_labels: 47, 49, 50, 51, 52
tag: 1RBG
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 29ac128e0c7c64abfb8efa56dae0685f751003bd9cbcfae11cc20f9ac3cfaaa2
prompt_sha256: draft-1
translated_from: content/ru/1978/01/articles/16_gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565.md
source_content_sha256: 2ce29be6e593c98c2e8a7332d2872ad3e40b5208e0753ac63b0d733546f586d0
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

标量向量乘法是向量代数的基本概念之一。它的性质被广泛应用于证明理论和解决问题。

在本文中，我们将说明在 Z. A. Skopet 编辑的教科书《几何 9》中向量研究的发展过程中，标量向量乘法在解决近年来入学考试中提供的几何问题中的应用。因此，我们不再详细讨论这个问题的理论。让我们继续解决问题。

问题 1。（MIPT，1977）。正三角形特征 $ABCA_1B_1C_1$ 的底边长度为 $a$。正三角形$MNPQ$的顶点$M$和$N$位于通过点$C_1$和$B$的直线上，顶点$P$和$Q$位于直线$A_1C$上。寻找：

1) 识别量；
2) 线段 $MN$ 和 $PQ$ 的中点之间的距离。

解决方案。考虑向量：$\overrightarrow{CA}, \overrightarrow{CB}, \overrightarrow{CC_1}, \overrightarrow{CA_2}$ 和 $\overrightarrow{BC_1}$ (图 1)。让我们表示 $\overrightarrow{CA} = \vec{u}, \overrightarrow{CB} = \vec{v}, \overrightarrow{CC_1} = \vec{h}$ 和 $\overrightarrow{|h|} = h$。由条件$\overrightarrow{|u|} = \overrightarrow{|v|} = a$得出。

由于在正四面体中（实际上，在任何正三角形基体中）任何两个相交的边都是相互垂直的，因此 $\overrightarrow{CA_1} \perp \overrightarrow{BC_1}$。因此$\overrightarrow{CA_1} \cdot \overrightarrow{BC_1} = 0$。但在我们的记法中

$$\overrightarrow{CA_1} = \vec{u} + \vec{h} \text{ и } \overrightarrow{BC_1} = \vec{h} - \vec{v},$$

跟随，

$$(\vec{u} + \vec{h}) \cdot (\vec{h} - \vec{v}) = 0,$$

$$\vec{u} \cdot \vec{h} - \vec{u} \cdot \vec{v} + \vec{h}^2 - \vec{h} \cdot \vec{v} = 0.$$

考虑$\vec{h} \perp \vec{u}, \vec{h} \perp \vec{v}$和$(\vec{u}, \vec{v}) = \frac{\pi}{3}$，我们得到

$$h^2 - \frac{a^2}{2} = 0, \text{ или } h = \frac{a}{\sqrt{2}},$$

其中 是识别量$V = \frac{a^2 \sqrt{3}}{4} \cdot \frac{a}{\sqrt{2}} = \frac{a^3 \sqrt{6}}{8}$。

令$K$和$L$分别为线段$PQ$和$MN$的中点。让我们找到$|KL|$。请注意，$[KL]$是边$PQ$和$MN$（证明本身）的公垂线，即$|KL|$是斜线$CA_1$和$BC_1$之间的距离。

有多种方法可以计算相交线之间的距离。我们将使用标量乘法确定所需的距离。同时，如何

⟦folio 49⟧

既不是$\overrightarrow{HN}$，也不是$\overrightarrow{AB}$。让我们表示：$\overrightarrow{HP} = \vec{p}$、$\overrightarrow{HQ} = \vec{q}$和$\overrightarrow{HR} = \vec{r}$。我们通过$\vec{p}$、$\vec{q}$和$\vec{r}$来表达剩余的向量。显然是$|\vec{p}| = |\vec{q}| = 2$和$|\vec{r}| = 1$。

让

$$|RA| = x |RF|,$$
$$|HB| = y |HN|.$$

然后是$\overrightarrow{RA} = x\overrightarrow{RF}$和$\overrightarrow{HB} = y\overrightarrow{HN}$。

显然，$\overrightarrow{RF} = \frac{1}{2}\vec{p} - \vec{r}$和$\overrightarrow{HN} = \frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}$（[HN]是三角形HPQ的中线）。因为

$$\overrightarrow{RA} = \frac{x}{2}\vec{p} - x\vec{r},$$
$$\overrightarrow{HB} = \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q}.$$

现在让我们通过向量 $\vec{p}, \vec{q}$ 和 $\vec{r}$ 来表达 $\overrightarrow{AB}$：

$$\overrightarrow{AB} = \overrightarrow{AR} + \overrightarrow{RH} + \overrightarrow{HB} = -\overrightarrow{RA} - \overrightarrow{HR} + \overrightarrow{HB} = -\frac{x}{2}\vec{p} + x\vec{r} - \vec{r} + \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q} = \frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}.$$

既然$[AB] \perp [RF]$和$[AB] \perp [HN]$，那么$\overrightarrow{AB} \cdot \overrightarrow{RF} = 0$和$\overrightarrow{AB} \cdot \overrightarrow{HN} = 0$。组成一个系统

$$\begin{cases}
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} - \vec{r}\right) = 0, \\
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}\right) = 0.
\end{cases}$$

从该系统中，考虑到向量 $\vec{p}, \vec{q}$ 和 $\vec{r}$ 相互垂直

⟦folio 50⟧

是有目的的，那么 $\overrightarrow{AC} \cdot \overrightarrow{BM} = 0$ 或
$(\vec{b} - \vec{h}) \cdot (\vec{a} + \vec{h} - \vec{y}) = 0,$
$\vec{a} \cdot \vec{b} + \vec{b} \cdot \vec{h} - \vec{b} \cdot \vec{y} - \vec{a} \cdot \vec{h} -$
$-\vec{h}^2 + \vec{h} \cdot \vec{y} = 0$. (5)

如前所述，$\vec{a} \cdot \vec{h} = \vec{h} \cdot \vec{y} = 0$
同样的基础上$\vec{b} \cdot \vec{h} = 0$。因此，从(5)我们有
$$\vec{a} \cdot \vec{b} - \vec{b} \cdot \vec{y} - \vec{h}^2 = 0,$$
$$ab - by - h^2 = 0,$$
$$y = \frac{ab - h^2}{b}.$$ (6)

(6) 中的值 $y$ 在 (4) 中得到确认
$$h^2 = \frac{a^2b - ah^2}{b},$$

在哪里
$$h = \frac{a\sqrt{b}}{\sqrt{a+b}}.$$

问题 4（乌拉尔国立大学，1971 年）。三角形$AOB$在其平面中绕顶点$O$旋转$90^\circ$，顶点$A$步进到$A'$，顶点$B - bB'$。证明三角形$OAB'$边$AB'$的中位数是三角形$OA'B$的高（同理，三角形$OA'B$中$A'B$边的中位数是$\Delta OAB'$的高）。

解决方案。令 $C$ 为$[AB']$ (图 4) 的中点。让我们证明$\overrightarrow{OC} \perp \overrightarrow{A'B}$，即$\overrightarrow{OC} \cdot \overrightarrow{A'B} = 0$；我们有

图 4.

图 5.

⟦folio 51⟧

$$DP = \frac{a\sqrt{6}}{3}, \quad |PQ| = |MN| = \frac{a}{2}.$$
令 $\varphi$ 为向量 $\overrightarrow{MN}$ 和 $\overrightarrow{PQ}$ 之间的角度大小。让我们根据两个向量的标量乘法的定义找到 $\varphi$ 的值

$$\cos \varphi = \frac{\overrightarrow{MN} \cdot \overrightarrow{PQ}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

让我们写下下一个等式向量

$$\overrightarrow{MN} = \overrightarrow{MD} + \overrightarrow{DN},$$

$$\overrightarrow{PQ} = \overrightarrow{DQ} - \overrightarrow{DP}.$$

将 (8) 中的值$\overrightarrow{MN}$ 和 $\overrightarrow{PQ}$ 代入 (7)

$$\cos \varphi = \frac{(\overrightarrow{MD} + \overrightarrow{DN}) \cdot (\overrightarrow{DQ} - \overrightarrow{DP})}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} = \frac{\overrightarrow{MD} \cdot \overrightarrow{DQ} + \overrightarrow{DN} \cdot \overrightarrow{DQ} - \overrightarrow{DP} \cdot \overrightarrow{MD}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} + \frac{-\overrightarrow{DN} \cdot \overrightarrow{DP}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

注意$(\overrightarrow{MD}, \overrightarrow{DQ}) = \frac{2}{3}\pi$和$(\overrightarrow{DP}, \overrightarrow{MD}) = \pi - \overrightarrow{MDP}$。显然$\cos MDP = \frac{\sqrt{6}}{3}$和$\cos NDP = \frac{2\sqrt{2}}{3}$。

考虑到上述情况，我们得到

**图 6.**

$$\cos \varphi = \frac{-\frac{a^2}{8} + \frac{a^2}{4} + \frac{a^2}{3} - \frac{4a^2}{9}}{\frac{a}{2} \cdot \frac{a}{2}} = \frac{1}{18}.$$

$\varphi = \arccos \frac{1}{18}$ 是线段 $MN$ 和 $PQ$ 之间的角度。

任务 6（密歇根州立大学，机制，1970 年）。三棱锥每条边的长度$SABC$等于1，$[BD]$是三角形$ABC$的高。等边三角形$BDE$位于与边$AC$成角$\varphi$的平面内，且点$S$和$E$位于平面$ABC$的同一侧。求点 $S$ 和 $E$ 之间的距离。

解决方案。让我们在高度为$EM$的三角形$BDE$中画出(图6)，并连接点$O$和$E$。通过点$M$我们绘制$[MN] \parallel [AC]$和$[MP] \parallel [SO]$。由于线段 $MN$ 和 $AC$ 平行，因此它们与平面 $BDE$ 所成的角度相等。既然$[MN] \perp [BD]$和$[EM] \perp [BD]$，那么$\angle EMN$，很容易理解，就是$[MN]$（因此，$[AC]$）与平面$BDE$，即$\hat{EMN} = \varphi$所成的角度。从$[MP] \parallel [SO]$开始，然后是$[MP] \perp (ABC)$，因此$[MP] \perp [BD]$和$[MP] \perp [MN]$。因此$\hat{EMP} = 90^\circ + \varphi$。显然$\overrightarrow{SE} = \overrightarrow{SO} + \overrightarrow{OM} + \overrightarrow{ME}$。

让我们求向量 $\overrightarrow{SE}$ 的标量平方：

$$\overrightarrow{SE}^2 = \overrightarrow{SO}^2 + \overrightarrow{OM}^2 + \overrightarrow{ME}^2 + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{OM} + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{ME} + 2 \cdot \overrightarrow{OM} \cdot \overrightarrow{ME}.$$

显然$\overrightarrow{SO} \cdot \overrightarrow{OM} = \overrightarrow{OM} \cdot \overrightarrow{ME} = 0$。因为很容易举报，$(\overrightarrow{SO}, \overrightarrow{ME}) = \hat{EMP} = 90^\circ + \varphi$，$|SE|^2 = |SO|^2 + |OM|^2 + |ME|^2 - 2 \cdot |SO| \cdot |ME| \cdot \sin \alpha$。 10）。

但$|SO| = \frac{\sqrt{6}}{3}$就像边长等于1的正三角形的高； $|ME| = \frac{3}{4}$ – 高度如何正确

⟦folio 52⟧

三角形的边距等于 $\frac{\sqrt{3}}{2}$； $|OM| = \frac{\sqrt{3}}{12}$（你自己算一下）。

我们将找到的值$|SO|, |OM|$和$|ME|$代入(10)：

$$|SE|^2 = \left(\frac{\sqrt{6}}{3}\right)^2 + \left(\frac{\sqrt{3}}{12}\right)^2 + \frac{9}{16} - 2 \cdot \frac{\sqrt{6}}{3} \cdot \frac{3}{4} \sin \varphi = \frac{5 - 2\sqrt{6} \sin \varphi}{4},$$

$$|SE| = \frac{1}{2} \sqrt{5 - 2\sqrt{6} \sin \varphi}.$$

问题 7（MIPT，1974。）直角三角形特征 $ABCA_1B_1C_1$ 的底边等于 $a$；点$O$和$O_1$分别是底$ABC$和$A_1B_1C_1$的中心。线段$AO_1$到直线$B_1O_1$的正交投影的长度等于$\frac{5}{6}a$。确定标志的高度。

解决方案。让我们输入$|OO_1| = H$。显然(图7)$|\overrightarrow{AO}| = |\overrightarrow{OB}| = \frac{a\sqrt{3}}{3}$和$|\overrightarrow{OB}_1| = \sqrt{\frac{a^2}{3} + H^2}$。接下来$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |AO_1| \cdot |OB_1| \cdot \cos \varphi$。 (11)

已知一个向量到另一个向量的投影等于第一个向量的长度乘以向量方向之间夹角的余弦，即$\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = |\overrightarrow{AO}_1| \times \cos \varphi = |\overrightarrow{AO}_1| \cdot \cos \varphi$。

根据问题条件

$$\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = \frac{5a}{6}.$$

因此，等式(11)写为：

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |OB_1| \cdot \frac{5a}{6}.$$

让我们写下以下等式：

$$\overrightarrow{AO}_1 = \overrightarrow{AO} + \overrightarrow{OO_1},$$

$$\overrightarrow{OB}_1 = \overrightarrow{OB} + \overrightarrow{BB_1}.$$

因此，

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = (\overrightarrow{AO} + \overrightarrow{OO_1}) \cdot (\overrightarrow{OB} + \overrightarrow{BB_1}) = \overrightarrow{AO} \cdot \overrightarrow{OB} + \overrightarrow{AO} \cdot \overrightarrow{BB_1} + \overrightarrow{OO_1} \cdot \overrightarrow{OB} + \overrightarrow{OO_1} \cdot \overrightarrow{BB_1}.$$

由于 $\overrightarrow{AO} \perp \overrightarrow{BB_1}$ 和 $\overrightarrow{OO_1} \perp \overrightarrow{OB}$，则 $\overrightarrow{AO} \cdot \overrightarrow{BB_1} = \overrightarrow{OO_1} \cdot \overrightarrow{OB} = 0.$

此外，$\overrightarrow{OO_1} = \overrightarrow{BB_1}$因此$\overrightarrow{OO_1} \cdot \overrightarrow{BB_1} = |OO_1|^2$，

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = \overrightarrow{AO} \cdot \overrightarrow{OB} + |OO_1|^2 = \frac{a\sqrt{3}}{3} \cdot \frac{a\sqrt{3}}{3} \cdot \frac{1}{2} + H^2 = \frac{a^2}{6} + H^2.$$

我们将找到的值$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1$和$|OB_1|$代入(12)$\frac{a^2}{6} + H^2 = \frac{5a}{6} \sqrt{\frac{a^2}{3} + H^2}$，从而得到$108H^4 = -39a^2H^2 - 22a^4 = 0$。从$H > 0$开始，然后$H = \frac{a\sqrt{6}}{3}$。

1（MIPT，1977）。直角三角形特征 $ABCA_1B_1C_1$ 的底边是一个等边直角三角形，边为 $|AC| = |BC| = a$。正四面体$MNPQ$的顶点$M$和$N$位于直线$CA_1$上，顶点$P$和$Q$位于直线$AB_1$上。求：1）直线体积； 2) 线段$MN$和$PQ$中点之间的距离。

2（MIPT，1977）。立方体边长$ABCDA_1B_1C_1D_1$等于$a$。点$E$是边$AD$的中间。正四面体$MNPQ$的顶点$M$和$N$位于直线$ED_1$上，顶点$P$和$Q$位于经过点$A_1$并与直线$BC$相交的直线上$R$。

求：1）关系$|BR| : |BC|$； 2) 线段$MN$和$PQ$中点之间的距离。

3（MIPT，1969）。在正四面体$ABCD$中，线段$MN$连接边$AC$的中点与面$BCD$的中心，点$E$位于边$AB$的中点。求线段 $MN$ 和 $DE$ 之间的角度。

4（莫斯科国立大学物理学院，1963 年）。两条线段 – 长度为 $a$ 的$AB$ 和长度为 $b$ 的$CD$ 位于斜线上，它们之间的角度为 $a$。这些线的长度为 $c$ 的公共垂线的底$O$ 和$O_1$ 将线段$AB$ 和$CD$ 分开，从而得到$|OA| : |OB| = 2:3$ 和$|OO_1| : |C_1D| = 3:2$。求线段 $BD$ 和 $BC$ 的长度。

5（来自任务 3FTSH）。在正四角矩形$SABCD$中，边$SA$和$BC$的公垂线长度为$d$，其底边以1:3的比例划分线段$BC$。确定直线的体积。

6（基辅理工学院，1977 年）。在直线 $ABCD$ 的平面上给出一个点 $M$。证明$\overrightarrow{MA} \cdot \overrightarrow{MC} = \overrightarrow{MB} \cdot \overrightarrow{MD}$。

7（1974 年举重联盟奥运会）。给定一个正方形$ABCD$。点$P$和$Q$分别位于边$AB$和$BC$，以及$|BP| = |BQ|$。设 $H$ 为从点 $B$ 到线段 $PC$ 的垂线的底边。证明角$DHQ$是直角。
