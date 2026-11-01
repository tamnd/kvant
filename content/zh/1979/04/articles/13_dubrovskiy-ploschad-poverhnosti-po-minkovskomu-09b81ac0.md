---
id: 1979-4-dubrovskiy-ploschad-poverhnosti-po-minkovskomu-09b81ac0
issue: kvant_1979_4
year: 1979
number: "4"
title: 根据闵可夫斯基表面积
authors:
  - Дубровский В. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 35
page_last: 38
page_labels: 33-36
tag: JNA8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 925ddd329466ebfd9dcd74d02c07c8bed61715201d25ee064597a375a5a98e3c
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/13_dubrovskiy-ploschad-poverhnosti-po-minkovskomu-09b81ac0.md
source_content_sha256: 98f55a6e39e0e0e1b508ee05f4cecd4e995031ad8b6848f186d8c44c7a8ee803
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

根据闵可夫斯基表面积

道路的长度等于其面积除以宽度。
（摘自针对小学生的讲座）

在之前关于表面积的注释（«Kvant»，1978，第 5 期）中，我们讨论了如何不定义它。我们在那里表明，多面体表面的展开和近似都不适合此目的。

本文将提出一种确定表面积的正确方法，该方法由杰出的德国物理学家和数学家 G. Minkowski（1864-1909）发明。它的定义是通用且简单的。它可以让您轻松计算空间面积。在《几何10》中，这个定义用于求球体的面积（第69节）以及圆柱体、圆锥体和球截的表面积（第六章附录）。

闵可夫斯基定义的思想非常明确。让我们想象一个厚度恒定的层“包围”表面。直观上很明显，它的体积$V(\delta)$（2δ是层的厚度）约等于$2\delta \cdot S$，其中$S$是所考虑的表面面积。计算完$V(\delta)/2\delta$的值后，我们会找到$S$值的近似值，而$\delta$值越小，近似值越好。

让我们将这个想法转化为数学语言。 “厚度恒定的层”的数学等价物是图形邻域的概念*)。让我们用 nyatcha 来定义它。设$\Phi$为空间中的任意图形，$\delta$为正数。距离$\Phi$不超过$\delta$、$\rho(P \Phi) \leq \delta$的空间点$P$的集合$\Phi_\delta$称为图$\Phi$的(闭*))δ-邻域。

为了明确定义，我们需要定义点到图形的距离的概念。点$P$到图形$\Phi$的距离$\rho(P, \Phi)$也意味着数字$d$，这意味着任何以$P$为圆心且半径小于$d$的球与$\Phi$没有公共点，但以$P$为圆心且半径大于$d$的球确实如此。

然而，可以在没有到 $\Phi$ 距离的概念的情况下定义图形的 δ 邻域。事实证明，这个定义等价于：图形$\Phi$的δ-邻域是空间点$P$的集合$\Phi_\delta$，使得每个中心为$P$且半径大于$d$的球都与$\Phi$有公共点。想清楚了。

如果在点到图形的距离的定义中，我们将“空间”和“球”替换为“平面”和“圆”，那么我们就得到了平面上图形的δ邻域的定义。如果没有另外说明，我们将考虑空间邻域。

练习
1. a) 求该线段的平面和空间δ邻域。证明第一个的面积和第二个的体积相等，分别为$2\delta d + \pi\delta^2$和$\pi\delta^2 d + \frac{4}{3}\pi\delta^3$，其中$d$是线段的长度。
6) 对半径为 $R > \delta$ 的圆解决相同的问题（在本例中，答案是：$4\pi R$ 和 $2\pi^2 R\delta^2$）。
2. 求空间中正六边形的 δ 邻域。证明$V(\delta)/2\delta$，其中$V(\delta)$是体积，在$\delta \rightarrow 0$趋于六边形的面积。

现在让我们给出这个注释的基本定义：面积$\Pi$称为极限

$$S(\Pi) = \lim_{\delta \to 0} \frac{V(\Pi_\delta)}{2\delta},$$

*）由于我们只考虑封闭邻域，因此下文中将省略附加的“封闭”。

⟦folio 34⟧

其中 $V(\Pi_\delta)$ 是其 δ 邻域的体积。
一句警告。当然，极限(1)也可能不存在。可以证明，对于所有“好的”表面，它都存在（在最简单的情况下，我们将计算它）。然而，人们不应该认为从某个图形$\Pi$的存在就可以得出$\Pi$是普遍接受的意义上的表面。此外，对于 Minkowski 平面，等式 $S(\Pi_1 \cup \Pi_2) = S(\Pi_1) + S(\Pi_2)$（在 $\Pi_1 \cap \Pi_2 = \emptyset$）并不总是成立；因此，在问题 4 中考虑该示例。然而，对于“良好”表面，不会出现这样的不便。

计算面积的示例

当然，仅在最简单的情况下可以计算表面积并直接使用上面给出的定义*)。

我们将求出球体、环面（通过围绕不相交的线表示圆而获得的表面）、圆柱体和圆锥体的侧面。这些表面的 δ 邻域的轴向截面的一半如图 1、2、3a、4a 所示。

练习

3. 证明通过表示围绕不与其相交的直线的圆、圆柱体和圆锥体的侧面而获得的曲面的 δ 邻域。该曲线围绕直线 l 的 δ 邻域的轴向截面的一半。

4. 证明在图 1、2、3a、4a 所示的黄色图形的表达过程中出现的物体是对应于表面的 δ 邻域。

1. 领域。显然，半径为 $R$ 的球体 $\Sigma = \Sigma(R)$ 的 δ 邻域体积等于半径为 $R + \delta$ 和 $R - \delta$ 的球体积之差 (图 1)：

$$V(\Sigma_\delta) = \frac{4}{3}\pi[(R + \delta)^3 - (R - \delta)^3] = 2\delta \cdot \frac{4}{3}\pi(3R^2 + \delta^2).$$

将最后一个表达式除以 2δ 并传递到 $\delta \rightarrow 0$ 处的极限，我们发现 $S(\Sigma(R)) = 4\pi R^2$。

2. 托尔。让我们考虑通过使用某些积分公式围绕距离其中心一定距离的直线表示半径为 $r$ 的圆而获得的环面 $T = T(R, r)$。

*) 在更复杂的情况下，可以使用某些积分公式找到表面积。

⟦folio 35⟧

站立$R > r$（图2）。很明显，以它为界的物体是半径为 $R$ 的圆的 $r$ 邻域，根据练习 16) 的结果，其体积等于 $2\pi^2 R r^2$。使用这个公式，很容易找到圆环的 $\delta$ 邻域的体积（参见 图 2）——它等于半径为 $R$ 的圆的半径 $(r + \delta)$ 邻域和 $(r - \delta)$ 邻域：

$$V(T_\delta) = 2\pi^2 R(r + \delta)^2 - 2\pi^2 R(r - \delta)^2 = 2\delta \cdot 4\pi^2 R r.$$

因此，$S(T(R, r)) = 4\pi^2 R r$。

从 图 3a 和 4a 可以清楚地看出，求出圆柱体（尤其是圆锥体）侧面的 $\delta$ 邻域的体积并不像球体和环面那样简单。如果这些邻域稍微“修正”（图 36 和 46），则本质的计算将会被简化。我们将进行计算，使用“修正”，然后证明其有效性。

3. Ts i li 等人。让我们用 $C = C(R, H)$ 表示半径为 $R$、高度为 $H$ 的圆柱体的侧面。其“校正”$\delta$邻域$C'_\delta$ (图 36) 的体积等于半径为 $R + \delta$ 和 $R - \delta$ 且高度 $H$ 相同的圆柱体的体积之差：

$$V(C'_\delta) = \pi H \left[ (R + \delta)^2 - (R - \delta)^2 \right] = 2\delta \cdot 2\pi R H,$$

因为

$$S(C(R, H)) = \lim_{\delta \to 0} \frac{V(C'_\delta)}{2\delta} = 2\pi R H.$$

4. 锥体。设 $R$ 为圆锥底面半径，$\alpha$ 为圆锥体轴线与母线之间的角度，$K = K(R, \alpha)$ 为圆锥体侧面。那么物体的体积 $K'_\delta$ (图 46) 等于圆锥体 $R + \frac{\delta}{\cos \alpha}$ 和 $R - \frac{\delta}{\cos \alpha}$ 以及相同角 $\alpha$ 的体积之差。很容易看出

$$V(K'_\delta) = \frac{1}{3} \pi \text{ctg} \alpha \left( R + \frac{\delta}{\cos \alpha} \right)^3 - \frac{1}{3} \pi \text{ctg} \alpha \left( R - \frac{\delta}{\cos \alpha} \right) = 2\delta \frac{\pi}{\sin \alpha} \left( R^2 + \frac{\delta^2}{3 \cos^2 \alpha} \right).$$

因此，$S(K(R, \alpha)) = \frac{\pi R^2}{\sin \alpha}$。

如果与角度 $\alpha$ 一起给出生成圆锥体的长度 $l$，则从 $l = \frac{R}{\sin \alpha}$ 开始，对于平面，公式为 $S(K) = \pi R l$。

现在让我们证明用$C'_\delta$和$K'_\delta$替换邻域$C_\delta$和$K_\delta$的有效性。显然，当且仅当量$v(\delta) = \frac{V(\Pi_\delta) - V(\Pi'_\delta)}{2\delta}$在$\delta \to 0$处趋于零时，用某个体$\Pi'_\delta$替换公式（1）中的邻域$\Pi_\delta$不会影响结果。根据模型，体积$V(C'_\delta)$和$V(C'_\delta)$、$V(K_\delta)$和$V(K'_\delta)$的差异并没有明显超过分别旋转图5a和图5b中的矩形$Q_1$和$Q_2$获得的物体体积。找到这些体积后（请注意，为此我们可以使用公式（2）），我们发现在圆柱体的情况下为$|v(\delta)| \leq 4\pi R \delta$，在圆锥体的情况下为$|v(\delta)| \leq \left( \frac{4\pi R}{\cos \alpha} + \frac{\pi \delta}{\sin \alpha} \right)\delta$。因此，一般情况下$\lim_{\delta \to 0} v(\delta) = 0$。

概括

令某个集合$\Phi$有一个终点和一个正极限$\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{2\delta}$；

那么，显然，当用$c\delta^n$替换分母$2\delta$时，这个极限将在$n < 1$处消失，并在$n > 1$处趋于无穷大。在意义的定义中，这个属性是特定于表面的。很容易理解，对于物体来说，这样的边界值已经是 $n = 0$，对于线来说 - $n = 2$。

特别是，在后一种情况下，接受以下定义

⟦folio 36⟧

定义：根据闵可夫斯基（空间）的直线$L$的长度称为极限$\lim_{\delta \to 0} \frac{V(L_\delta)}{\pi \delta^2}$。

这个定义的直观理由是，重新分布线 $L$ 的邻域 $L_\delta$ 的部分是一个半径为 $\delta$（面积 $\pi \delta^2$）的圆，因此体积 $L_\delta$ 必须等于 $\pi \delta^2$ 与线 $L$ 长度的乘积。使用控制 1 的结果，检查 Minkowski 的定义是否给出了线段和圆的长度所需的值。

不太有意义，但完全有意义的是考虑$n=0$和$n=3$的值$\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{c \delta^n}$，其中$c$是正确选择的常量（参见问题7）。

类似的定义可以在平面上给出，其中最有趣的情况是$n=1$：数量$\lim_{\delta \to 0} \frac{S(L_\delta)}{2\delta}$，其中$S(L_\delta)$是曲线$L$的（平坦）$\delta$邻域的面积，自然被视为线$L$的长度（参见题词）。

进一步的概括涉及 $n>3$ 的 $n$ 维空间，我们当然不会详细讨论它们。

3 个阿达奇和

1. 证明图形 $\Phi$ 的 $\delta$ 邻域并不总是半径为 $\delta$ 且中心位于该图形各点的所有球的并集。

2. 给出两个不同数字$\Phi$和$\Phi'$的示例，使得$\Phi_\delta = \Phi_\delta'$：a) 对于某些$\delta$； b) 对于所有$\delta$。

3. 证明凸$n$边形的$\delta$邻域的体积等于$2\delta \cdot S + \pi \delta^2 \cdot P + \frac{4}{3} \pi \delta^3$，其中$S$是其面积，$P$是其半周长。

4. 设$Q$是位于平面$Oxy$中的一个正方形，$Q_1$是其坐标$x$和$y$所在的点的集合，$Q_2$是其其余点。证明所有这些集合都有 Minkowski 面积，并且有 $S(Q) = S(Q_1) = S(Q_2)$，因此有 $S(Q_1 \cup Q_2) < S(Q_1) + S(Q_2)$，尽管集合 $Q_1$ 和 $Q_2$ 不相交。

5. 求表面积，我们通过表达围绕它所对弦的其他圆来获得。

6. 求一个物体的表面积，该物体是两个半径为 $R$ 的（足够长的）圆柱体的交点，这两个圆柱体的轴穿过一个公共点并且相互垂直。

7. 选择常数 $c_1$ 和 $c_2$，使极限 a) $\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{c_1}$ b) $\lim_{\delta \to 0} \frac{V(\Phi_\delta)}{c_2 \delta^3}$ 具有有意义的几何意义。对于哪个数字 $\Phi$ 是正数？

提交正确解决方案的读者名单...

（开头部分请参见第 32 页）

V. Berkum (第聂伯罗彼得罗夫斯克) 18, 19; A. Boldyrev (阿拉木图) 19; V.博洛特尼科夫（哈尔科夫）10、12、14-17、19、22； G. 鲍里索夫（托门地区共青城定居点）11、12、15、17； A.布罗丁（基辅）11、12； O.布尔塞宁（巴甫洛达尔）18； M. Valeiko（基辅）9、10； O. Vasiliev（楚瓦什苏维埃社会主义自治共和国乌玛定居点）9； S.瓦西里耶夫（加里宁）10； A. Velko（明斯克地区糖厂村）18； D.沃尔德科（多尔戈普鲁德内）18、19、22； F. Gabasov（p/o Nasibash Bashk ASSR）18； M. Gavrilov（莫斯科地区 Chernogolovka 村）9-14、16、19； M.Goltsman（第聂伯罗彼得罗夫斯克）10、11、15、20； I.戈皮茨（新西伯利亚）9、10、14、15； I. 格鲁兹别尔 (彼尔姆) 9, 13; E. Davidov（梁赞地区 Poplevno 村）13； I.丹尼洛夫斯基（高尔基）19； V. Jaloyan（亚美尼亚苏维埃社会主义共和国Urtsadzor村）15； V.迪杜赫（利沃夫）10； A. Dremin（莫斯科地区 Chernogolovka 村）11、15、18、22； M. Ermolaev (科斯特罗马) 16;五、志林（阿尔泰地区哈巴里村）15、18；于。 Zhuk（莫斯科）13、15； V.朱可夫（阿巴扎）19、20、22； K.朱可夫（莫斯科）13、15； D.扎哈罗夫（莫斯科）18； A.泽姆斯科夫（Ukhta）18； E.祖丁（亚历山德罗夫）10、11、13-17、22； E.伊文科（文尼察）18； K.伊林（维尔纽斯）18； S.卡拉什尼科夫（梁赞）10； A.卡普兰（Sumgant）18； V.凯尔曼（莫斯科）19； O.基里连科（Balashina）22； A.克柳科夫（车里雅宾斯克）13； V. Kovtunenko (基辅) 9, 10; E.科赞（第聂伯罗彼得罗夫斯克）10、15、16； M. Kokov（Bateh KVASSR 村）9； V.科莫夫（亚历山德罗夫）10、11、13、14、16-19、22； A.科罗贝尼科夫（巴拉绍夫）10； A.科斯特罗夫（Semiluki）20； O.克拉维茨（沃罗涅日）19； R.克里斯图尔（鲍布里克）16； E.库兹明（切诺维茨）9、18、19； A.库普林（莫斯科）9-12、18-20、22； V. Kuryan（顿河畔罗斯托夫）11-13、15、17、19、20； V. Lashkin（基辅）12、15、18、22； A.列昂诺维奇（利达）16； V.林科夫（卡卢加）10； D. Lyudmirsky（基辅）10、17-19、22；于。马卡洛夫 (p/o Chagoda, 沃洛格达地区) 18; S.马拉马诺夫（列宁格勒）15、18； I.马尼采夫（斯卢茨克）18； A. Matyukas（议会）15、16、19； L. Marukhlenko（莫斯科地区 Staraya Kupavna 村）12； S.梅德韦杰夫（莫斯科）10、11； V.米库洛夫（巴甫洛达尔）20； A.Motselner（斯维尔德洛夫斯克）20； A.莫洛托维奇科夫（Teykovo）16； S.Murachtsev（马哈奇卡）10；

（最后见第51页）
