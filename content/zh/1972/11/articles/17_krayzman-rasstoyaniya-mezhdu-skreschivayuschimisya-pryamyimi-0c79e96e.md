---
id: 1972-11-krayzman-rasstoyaniya-mezhdu-skreschivayuschimisya-pryamyimi-0c79e96e
issue: kvant_1972_11
year: 1972
number: "11"
title: 交叉线之间的距离
authors:
  - Крайзман М. Л.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 59
page_labels: 52, 53, 55, 56, 57
tag: LCTW
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8af2d3011342aed7d42f5d3417b144b74306ab1ecdc4d6c3002eca48d77b0ec3
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/17_krayzman-rasstoyaniya-mezhdu-skreschivayuschimisya-pryamyimi-0c79e96e.md
source_content_sha256: 0cb9ee8930dec4a6307f3d7eb919f56b7f2c1743de70493d810d69dc5dd922db
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

考虑直线交叉的机制

克赖兹曼

在解决计算相交线之间距离的问题时，区分两种情况很有用：

1) 与垂直线相交；
2) 交叉直线而不是垂直线。

如果交叉线$a$和$b$是垂直的（第一种情况），那么检查其中一条交叉线的最简单方法是平面$\alpha$，垂直于另一条线（图1；从线$a$上的任意点$M$垂线$OM$下降到线$b$，平面$\alpha$由两条相交线$a$和$MO$确定，因为$b \perp a$由条件确定，$b \perp OM$由构造确定，因此，$b \perp \alpha$由直线和平面的垂直度推广）。然后，从平面$\alpha$与直线$b$的交点$O$，需要将垂线$ON$降低到直线$a$、$ON$上——不包括距离。

示例 1. 确定边为 $a$ 的立方体的对角线与与其相交的面的对角线之间的距离。

解决方案。我们将确定 $B_1D$ 和 $D_1C$ (图 2) 之间的距离。由于$D_1C \perp DC_1$和$DC_1$是$B_1D$在平面$DD_1C_1C$上的投影，因此$D_1C \perp B_1D$（根据三垂线广义定理）。从$D_1C \perp DC_1$和$D_1C \perp B_1D$的对应关系可以得出（基于直线和平面的垂直度）$D_1C \perp DB_1C_1$。设$O$为$D_1C$和$DC_1$的交点。让我们从垂直于$OK$的点$O$下降到$B_1D$、$OK$——消除交叉线$B_1D$和$D_1C$的距离。我们去找他吧。为此，我们将直角三角形 $OKD$ 和 $B_1DC_1$ 替换为类似于 $OK: B_1C_1 = OD: B_1D$。从这里

$$OK = \frac{a\sqrt{6}}{6}.$$

⟦folio 53⟧

在继续讨论下一个示例之前，我们先证明一个定理，该定理表示两个面相互重新分布的三角形角度之间的关系。

定理1.如果三角形角的两个面相互重新分布，则与二维直角相对的面的平面角的余弦等于与二维直角相对的面的平面角的余弦的乘积。

证明。 图 3 层。 ASB ⊥ pl。 BSC，⇒ ASC = α，⇒ ASB = β，⇒ BSC = γ。我们要证明cos α = cos β · cos γ。为此，我们从边 SA 上的点 M 开始，将重新分配 MO 降至 BS，将 MN 降至 SC。让我们连接点 N 和 O。根据三个再分​​配器定理，SC ⊥ NO。由 △SMO 和 △SON 得

$$\cos \beta = \frac{SO}{SM}, \quad \cos \gamma = \frac{SN}{SO}.$$

变量是这些等式：cos β · cos γ = $\frac{SN}{SM}$，我们从 △SNM 中找到 cos α：cos α = $\frac{SN}{SM}$。因此cos α = cos β · cos γ。定理已被证明。

示例 2. 三棱柱的每条边都等于 α。然而，从侧边缘开始，它与底座的侧面形成角度，每个角度都等于 α。确定该边与与其相交的底座边之间的距离。

解决方案。需要确定AA₁和BC之间的距离（图4）。众所周知，如果从角的顶点发出的斜率

$$\text{Рис. 3.}$$

该角的各边所成的角相等，则该角在平面上的斜投影就是该角的二等分线。因此AO是角BAC的二等分线。但△ABC是正确的，AD二分线的延长就是这个三角形的高度，因此AD⊥BC。通过三个再分配器 BC ⊥ AA₁ 的广义定理，并基于直线和平面 BC ⊥ pl 的再分配广义准则。 DAA₁。让我们从 D 点将再分配器 DK 降到 AA₁； DK 是 BC 和 AA₁ 之间所需的距离。令 ⇒ A₁AO = x;将定理 1 应用于三角形角 AA₁DC，可得： cos ⇒ A₁AC = cos ⇒ A₁AD · cos ⇒ DAC； cos α = cos x cos 30°。从这里

$$\cos x = \frac{\cos \alpha}{\cos 30^\circ} = \frac{2\sqrt{3}\cos \alpha}{3}.$$

剩下的就是从△AKD中求KD：

$$KD = AD \cdot \sin x = \frac{a\sqrt{3}}{2}\sqrt{1 - \cos^2 x} = \frac{a\sqrt{3}}{2}\sqrt{1 - \frac{4}{3}\cos^2 \alpha} = \frac{a}{2}\sqrt{3 - 4\cos^2 \alpha} = \frac{a}{2}\sqrt{3 - 4\cos^2 \alpha},$$

和$\frac{\pi}{6} < \alpha < \frac{5\pi}{6}$。

现在让我们考虑相交线不重新定义彼此的情况。由于在给定的计算中不需要构造重新定义

⟦folio 55⟧

相交的直线之间。其中一种方法基于三角形矩形的体积定理。

定理2.三角形直线的体积等于其任意两条相交边的长度除以它们之间的距离和它们之间的角度的正弦值的乘积的六分之一。

证明。从平行六面体 $AC_1$ 的任意顶点 ($B_1$) 开始，我们绘制在该顶点 (图 9) 汇聚的面的对角线 $B_1A$、$B_1D_1$、$B_1C$。让我们将这些对角线的末端相互连接起来。我们得到一个平行六面体$B_1AD_1C$，它被称为内切平行六面体，而相反，围绕这个平行六面体描述一个平行六面体（它可以通过通过平行体的相对边缘绘制成对的平行平面来轻松构造）。

平行六面体的体积为：

$$V_{AC_1} = V_{B_1AD_1C} + V_{D_1ADC} + V_{B_1ABC} + V_{AA_1B_1D_1} + V_{CB_1C_1D_1}.$$

因为

$$V_{D_1ADC} = V_{B_1ABC} = V_{AA_1B_1D_1} = V_{CB_1C_1D_1}.$$

（这些平行六面体的底边等于平行六面体底面面积的位置，它们的高度等于平行六面体的高度$h$），则

$$V_{B_1AD_1C} = V_{AC_1} - 4V_{D_1ADC} = V_{AC_1} - 4 \cdot \frac{1}{3} \cdot \frac{1}{2} Sh = V_{AC_1} - \frac{2}{3} Sh = \frac{1}{3} V_{AC_1}.$$

所以，内接三角形平行六面体的体积是三分之一

所述平行六面体的体积，或变换后，

$$V_{B_1AD_1C} = \frac{1}{3} V_{AC_1} = \frac{1}{3} Sh = \frac{1}{3} \left( \frac{1}{2} AC \cdot BD \cdot \sin \varphi \right) \cdot h = \frac{1}{6} AC \cdot B_1D_1 \cdot h \cdot \sin \varphi.$$

在解决相交直线距离问题时，可以根据垂直三角形平行体的性质，使用所描述的平行六面体的特征。例如，尝试自己证明 Paramid 中是否有两个交叉边：

a) 相等，则这些边所在的所述平行六面体的面将是矩形；
b) 相等且垂直，则对应的面是正方形。

示例 5. 在三角形 paramid 中，相对（交叉）边成对地彼此相等，并且相应的边等于 a、b 和 c。寻找他们之间的考虑。

解决方案。所述平行六面体的相对面是直角，因此平行六面体本身将是直角(图10)。交叉边之间所需的距离将等于相对面（即直立平行六面体的边）之间的距离。

⟦folio 56⟧

让我们创建一个方程组：

$$x^2 + y^2 = a^2,$$
$$x^2 + z^2 = b^2,$$
$$y^2 + z^2 = c^2.$$

将它们逐项相加并除以 2，我们得到

$$x^2 + y^2 + z^2 = \frac{a^2 + b^2 + c^2}{2},$$

从最后一个方程中减去每个系统方程并取平方根，我们发现

$$x = \frac{1}{2} \sqrt{2(a^2 + b^2 - c^2)},$$
$$y = \frac{1}{2} \sqrt{2(a^2 + c^2 - b^2)},$$
$$z = \frac{1}{2} \sqrt{2(b^2 + c^2 - a^2)}.$$

例6.对应的三角形帕拉米德的两个混杂的肋条分别为6厘米和8厘米，其他四个肋条各为13厘米。确定该参数的交叉肋之间的距离。

解决方案。由于$AB_1 = B_1C = AD_1 = D_1C$ (图 11)，则平行六面体$AC_1$的所有侧面都是相等的矩形。因此，底边是菱形$ABCD$，而平行六面体本身是直的。因此$d(AC; B_1D_1) = BB_1$，$d(AD_1; B_1C) = d(AB_1; D_1C) = h$，其中$h$是菱形$ABCD$的高度。接下来很容易找到$h = 4,8$厘米，$BB_1 = 12$厘米（自己做）。

用于解决确定交叉线之间的距离问题的代数方法基于以下定理。

定理3.让数据穿过线$a$和$b$。点 $A_1, A_2, A_3$ 在线 $a$ 上取，垂线 $A_1B_1, A_2B_2, A_3B_3$ 从这些点垂到线 $b$。然后$A_1A_2:A_2A_3 = B_1B_2:B_2B_3$。

证明。让我们通过线 $b$ 画一个任意平面 $\alpha$ (图 12) 并考虑线 $a$ 在该平面上的正交投影；点$A_1, A_2, A_3$的投影分别用$A'_1, A'_2, A'_3$表示。根据平行投影的性质我们有

$$A_1A_2:A_2A_3 = A'_1A'_2:A'_2A'_3.$$

最后一个点从点$B_1, B_2, B_3$分别为$A'_1, A'_2, A'_3$。根据三垂直定理，$A'_1B_1 \perp b, A'_2B_2 \perp b, A'_3B_3 \perp b$，因此$A'_1B_1 \parallel A'_2B_2 \parallel A'_3B_3$。根据两条直线平行线相交定理，我们可以写出：

$$A'_1A'_2:A'_2A'_3 = B_1B_2:B_2B_3.$$

由不主持的等式（1）和（2）得出：

$$A_1A_2:A_2A_3 = B_1B_2:B_2B_3.$$

例 7. 在 paramid SABC 的底部有一个直角垂直三角形 $ABC$，其阳线 $AB = c$ 和等于 $30^\circ$ 的锐角 $BAC$。侧边穿过

⟦folio 57⟧

石头AC垂直于底座平面，另外两个与其形成一个角度，也等于30°。确定 SB 和 AC 之间的距离。

解决方案。让我们求线段 SB 在线段 AC 上的投影。为此，我们从点 S 和 B 将垂线 SO 和 BC 降低到 AC (图 13)，将 SK 降低到 AB；那么 Pr_ACSB = OC。让我们找出比率 $\frac{OC}{SB}$。由等式 $\Rightarrow SKO = \Rightarrow SCO = 30^\circ$ 可知 OK=OC 和 OB 是角 ABC 的黑边。接下来我们找到：$BC = AB \cdot \sin 30^\circ = \frac{1}{2}c$，

$$OC = BC \cdot \mathrm{tg} 30^\circ = \frac{c \sqrt{3}}{6},$$

$$SC = OC \cdot \cos 30^\circ = \frac{1}{3}c,$$

$$SB = \sqrt{SC^2 + BC^2} = \frac{c \sqrt{13}}{6}.$$

因此，

$$\frac{OC}{SB} = \frac{c \sqrt{3}}{6} : \frac{c \sqrt{13}}{6} = \sqrt{\frac{3}{13}}.$$

从SB上的任意一点P，向AC垂线PQ；那么 PB 在 AC 上的投影就是 QC。根据定理3，OC:SB = QC:PB，由此$\frac{QC}{PB} = \sqrt{\frac{3}{13}}$；让$QC = x \sqrt{3}, PB = x \sqrt{13}$。让我们将余弦定理应用到三角形 CPB 上：

$$PC^2 = \frac{c^2}{4} + 13x^2 - 2\frac{c}{2} \cdot x \sqrt{13} \cos \Rightarrow CBP.$$

图 13.

从$\triangle SCB$我们发现

$$\cos \Rightarrow CBS = \frac{CB}{SB} = \frac{c}{2} : \frac{c \sqrt{13}}{6} = \frac{3}{\sqrt{13}},$$

并代入(3)：

$$PC^2 = \frac{c^2}{4} + 13x^2 - cx \sqrt{13} \cdot \frac{3}{\sqrt{13}} = 13x^2 - 3cx + \frac{c^2}{4}.$$

接下来，从$\triangle QPC$我们有

$$QP^2 = CP^2 - QC^2 = 13x^2 - 3cx + \frac{c^2}{4} - 3x^2 = 10x^2 - 3cx + \frac{c^2}{4}.$$

最小值$QP^2$等于交叉线之间距离的平方；我们去找他吧。若$QP^2 = ax^2 + bx + c$，则

$$x_{\min} = -\frac{b}{2a} = \frac{3c}{20}; \quad (QP^2)_{\min} = 10 \cdot \frac{9c^2}{400} - 3c \cdot \frac{3c}{20} + \frac{c^2}{4} = \frac{c^2}{40};$$

$(QP)_{\min} = \frac{c \sqrt{10}}{20}.$

练习

1. 在 paramid SABC 的底部有一个直角三角形 ABC ($\Rightarrow C = 90^\circ$)，其象方 BC = a 和一个外接锐角 α。侧肋相对于基面倾斜角度β。确定斜边 AB 和与其相交的侧边 SC 之间的距离。

2. 正三角形paramid的底边等于a。如果侧缘与底面的倾斜角为 60°，则确定帕拉米达的顶点到与其相交的底面的边之间的距离。

3. 正四边形帕拉米德SABCD的底边等于a，顶点处的平面角等于α。确定该参数的交叉边缘之间的距离。
