---
id: 1980-11-zalgaller-zadacha-o-treugolnikah-s-obschim-osnovaniem-652d2e9d
issue: kvant_1980_11
year: 1980
number: "11"
title: 共底三角形问题
authors:
  - Залгаллер В. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 17
page_last: 20
page_labels: 15-18
tag: A8NV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 170c9510243bb0e54527dca2dd07adce275a74320ee21c18a99d379a7702484d
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/06_zalgaller-zadacha-o-treugolnikah-s-obschim-osnovaniem-652d2e9d.md
source_content_sha256: 67f10cb09c95036037b7e692591d9fe695173d2afb9467aafd62d3a4fb6a4e69
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 15⟧

任务
关于三角形
有共同点

1978年《«Kvant»》第五期中，提出了以下问题的几何解法：平面上的两个三角形有一个公共底，它们的顶点$C_1, C_2$不同且位于底的同一侧；证明顶点$C_1$和$C_2$之间的距离大于这些三角形内切圆的中心$O_1$和$O_2$之间的距离。

两年来，编辑们收到了很多关于这项有趣而艰巨的任务的留言。然而，我们的读者没有一个能够找到考虑到顶点相对位置的所有可能性的证明。

我们放置了两个证据；第一个是由哈尔科夫数学家 A. I. Medyannik 发明的，第二个是问题作者 V. A. Zalgaller 和 A. A. Ivanov 提出的证明，并根据院士 A. V. Pogorelov 的建议进行了简化。

第一个证明

我们需要三角形角平分线的以下性质（“几何 6-8”，问题 914）：如果 AD 是三角形角 A 的平分线

囚犯$ABC$（$D \in [BC]$），然后$\frac{|BD|}{|DC|} = \frac{|AB|}{|AC|}$。

设点 O 为内接于 $\triangle ABC$ 的圆 (图 1) 的中心。让我们用向量 $\vec{a} = \vec{BC}, \vec{b} = \vec{AC}, \vec{c} = \vec{AB}$ 及其长度 $a, b, c$ 来表达向量 $\vec{O} = AO$。

很容易看出$\vec{\varrho} = \frac{|AO|}{|AD|} \cdot \vec{AD} = \frac{|AO|}{|AD|} \left( \vec{c} + \frac{|BD|}{|DC|} \vec{a} \right)$。

根据平分线$\frac{|DC|}{|BC|} = \frac{|BD|}{|DC|} + \frac{|BD|}{|DC|} = \frac{c}{b+c}$的性质。

类似地（$BO$是角B的平分线），

$\frac{|AO|}{|AD|} = \frac{1}{1 + \frac{|OD|}{|AO|}} = \frac{1}{1 + \frac{|BD|}{c}}$.

从$\frac{|BD|}{|DC|} = \frac{c}{b}$和$|BD| + |DC| = a$我们得到$|BD| = \frac{ac}{b+c}$。

因此$\frac{|AO|}{|AD|} = \frac{b+c}{a+b+c}$。

利用$\vec{a} = -(\vec{b} + \vec{c})$，我们得到最终的$\vec{\varrho} = \frac{b\vec{c} - c\vec{b}}{p}$，

(1)

其中$p = a + b + c$。

现在让我们开始解决问题。让我们用 $d = |C_1C_2|$ 和三角形 $ABC_1, ABC_2$ 的边长来表示向量 $\vec{d}_0 = O_1O_2$ 的长度。

据已证明（见图2）

$\vec{d}_0 = \vec{\varrho}_2 - \vec{\varrho}_1 = \frac{b_2\vec{c} - c\vec{b}}{p_2} + \frac{c\vec{b}_1 - b_1\vec{c}}{p_1}$,

图 1.

⟦folio 16⟧

其中$p_1 = a_1 + b_1 + c$，$p_2 = a_2 + b_2 + c$。

计算$\vec{d}_0 \cdot \vec{d}_0 = d_0^2$，经过简单变换我们得到
$$p_1^2 p_2^2 d_0^2 = p_1^2 cb_2 [2cb_2 - 2(\vec{b}_2 \vec{c})] +$$
$$+ p_2^2 cb_1 [2cb_1 - 2(\vec{b}_1 \vec{c})] +$$
$$+ 2p_1 p_2 [cb_2(\vec{b}_1 \vec{c}) - c^2(\vec{b}_1 \vec{b}_2)] -$$
$$- b_1 b_2 c^2 + cb_1(\vec{b}_2 \vec{c})].$$

(2)

注意$2(\vec{b}_1 \vec{c}) = a_1^2 - b_1^2 - c^2$，$2(\vec{b}_2 \vec{c}) = a_2^2 - b_2^2 - c^2$；这就是为什么
$$2cb_1 - 2(\vec{b}_1 \vec{c}) = 2cb_1 - a_1^2 + b_1^2 + c^2 =$$
$$= (a_1 + b_1 + c)(b_1 - a_1 + c) =$$
$$= p_1(b_1 - a_1 + c),$$

相似地，
$$2cb_2 - 2(\vec{b}_2 \vec{c}) = p_2(b_2 - a_2 + c).$$

这降低了平等性
(2) $p_1 p_2$。另外，$\vec{d} = \vec{b}_2 - \vec{b}_1$，由此而来$2(\vec{b}_1 \vec{b}_2) = b_1^2 + b_2^2 - d^2$。这就是为什么
(2) 采取形式
$$p_1 p_2 d_0^2 = p_1 cb_2(b_2 - a_2 + c) +$$
$$+ p_2 cb_1(b_1 - a_1 + c) +$$
$$+ [cb_2(a_1^2 - b_1^2 - c^2) - c^2(b_1^2 + b_2^2 - d^2)] -$$
$$- 2b_1 b_2 c^2 + cb_1(a_2^2 - b_2^2 - c^2)],$$
在哪里
$$p_1 p_2(d^2 - d_0^2) =$$
$$= [(a_1 + b_1 + c)(a_2 + b_2 + c) - c^2]d^2 +$$
$$+ [(a_2 - b_2 - c)(a_1 + b_1 + c)b_2 +$$
$$+ (a_1 - b_1 - c)(a_2 + b_2 + c)b_1 +$$
$$+ (b_1^2 - a_1^2 + c^2)b_2 + (b_1^2 + b_2^2)c +$$
$$+ 2b_1 b_2 c + (b_2^2 - a_2^2 + c^2)b_1]c,$$

在方括号内转换后给出
$$p_1 p_2(d^2 - d_0^2) = [(a_1 + b_1)(a_2 + b_2) +$$
$$+ c(a_1 + b_1 + a_2 + b_2)]d^2 +$$
$$+ [c(a_2 - a_1)(b_2 - b_1) +$$
$$+ (a_1 b_2 - b_1 a_2)(a_2 - a_1 + b_1 - b_2)]c.$$

(3)

为了证明$d > d_0$，我们只要验证等式（3）右边为正就足够了。后者由两个术语组成。由于$a_1 + b_1 > c$和$a_2 + b_2 > c$，第一项大于$3c^2 d^2$。仍需检查第二项的绝对值是否小于$3c^2 d^2$。 $|a_2 - a_1| < d$、$|b_2 - b_1| < d$的对应关系很明显。

图 3

因为
$$p_1 p_2(d^2 - d_0^2) > (c^2 + 2c^2)d^2 -$$
$$- |c^2(a_2 - a_1)(b_2 - b_1)| -$$
$$- |a_1 b_2 - b_1 a_2|(|a_2 - a_1| +$$
$$+ |b_2 - b_1|)c > 3c^2 d^2 - c^2 d^2 -$$
$$- 2dc|a_1 b_2 - b_1 a_2| = 2c^2 d^2 -$$
$$- 2dc|a_1 b_2 - b_1 a_2|.$$

下面我们来证明$|a_1 b_2 - b_1 a_2| \leq cd$。

因此，不等式(4)的右边是非负的。

因此，$d > d_0$。

因此，还有待证明以下引理。

引理。设点$C_2$任意位于三角形$ABC_1$平面内。那么(图3)
$$|a_1 b_2 - b_1 a_2| \leq cd.$$

证明。让我们从点 $C_2$ 垂线 $C_2 P$、$C_2 Q$、$C_2 T$ 下降到直线 $BC_1$、$AC_1$、$AB$。

可以围绕四边形 $AQC_2 T$ 描述一个直径为 $AC_2$ 的圆。

从 $Q\hat{A}T = \alpha$ 开始，根据正弦定理，$|QT| = b_2 \sin \alpha$。

类似地考虑四边形$C_1 PC_2 Q$和$PC_2 TB$，我们得到$|PQ| = d \sin \gamma$和$|PT| = a_2 \sin \beta$。

令 $R$ 为三角形 $AC_1 B'$ 的外接圆的半径。根据正弦定理，$\sin \gamma = \frac{c}{2R}$、$\sin \beta = \frac{b_1}{2R}$、$\sin \alpha = \frac{a_1}{2R}$。术后$|QT| = \frac{a_1 b_2}{2R}$、$|PT| = \frac{a_2 b_1}{2R}$、$|PQ| = \frac{cd}{2R}$。

三角不等式意味着$|PT| - |QT| \leq |PQ|$；这就是为什么

⟦folio 17⟧

图 4

mu 将表达式代入 $|QT|$、$|PT|$、$|PQ|$ 并简化后，我们得到

$$|a_1b_2-a_2b_1| \leq cd.$$

第二次证明

在底$AB$固定的情况下，我们将顶点$C$沿着线段$C_1C_2$从$C_1$均匀移动到$C_2$。在这种情况下，内切圆的圆心$O$将沿着从$O_1$到$O_2$的某个路径移动。

引理。当顶点$C$以非零速度移动时，中心$O$以较低的速度移动。

从这个引理可以得出，当$C$以恒定速度经过线段$C_1C_2$时，点$O$在每个时刻都以较低的速度移动，将从$O_1$到$O_2$经过更短的路径。而且，直接路径$|O_1O_2|$比$|C_1C_2|$短。

在证明引理之前，让我们考虑以下内容。如果顶点 $C$ 以速度 $\vec{v} \neq 0$ 移动，则沿三角形各边运行的光线 $BC$ 和 $AC$ 以一些角速度 $\omega_1$ 和 $\omega_2$ 旋转，并且这些速度中至少有一个不为零。让我们就符号达成一致：如果梁顺时针旋转，我们认为角速度为正，如果梁逆时针旋转，我们认为角速度为负。

速度$\vec{v}$和$\omega_1$、$\omega_2$相关。如果我们从点 $C$ 移除向量 $\vec{v} = \vec{CT}$ (图 4)，那么它在垂直于射线 $BC$ 的方向上的投影长度 $|CP|$ 等于$|\omega_1| \cdot |BC|$。 （这是因为

图 5

点$C$的总运动速度由其与旋转射线$BC$一起运动的速度和沿该射线运动的速度组成。）类似地，$\vec{v}$到垂直于射线$AC$方向的投影的长度$|CQ|$等于$|\omega_2| \cdot |AC|$。可以围绕四边形$CPTQ$画一个圆。而且，$\vec{v}$等于这个圆的直径。

对于中心$O$的运动速度$\vec{v}_0$也可以进行类似的构造，只是在这种情况下将$[BC)$、$[AC)$替换为$[BO)$、$[AO)$，并将$\omega_1$、$\omega_2$替换为$\frac{\omega_1}{2}$、$\frac{\omega_2}{2}$。

速度$\omega_1$、$\omega_2$至少其中之一不为零。此外，同时改变$\omega_1$、$\omega_2$的符号会反转$\vec{v}$和$\vec{v}_0$的方向，而不会改变$\vec{v}$和$\vec{v}_0$的大小。因此，在证明不等式$\|\vec{v}\| > \|\vec{v}_0\|$时，不失一般性，我们可以假设$\omega_1 > 0$，并分别考虑$\omega_2 > 0$、$\omega_2 = 0$、$\omega_2 < 0$三种情况。

案例 1. 让 $\omega_2 > 0$。让我们转向 $90^\circ$ 四边形 $CPTQ$ 围绕点 $C$ 定位 $CP'TQ'$ (图 5)、四边形 $OP_0T_0Q_0$ - 大约 $O$ 定位 $OP'_0T'_0Q'_0$，我们将进行 $(P'_0P'') \parallel (Q'_0Q'') \parallel (OC)$。积分 $P''$ 和 $Q''$ 将片段分成两半 $CP'$, $CQ'$， 因为 $|CP'| / |CB| = \omega_1$, 一个 $|OP'| / |OB| = \frac{\omega_1}{2}$.

自从 $\vec{v}$ - 围绕三角形绘制的圆的直径 $CP'Q'$, 一个 $\vec{v}_0$ - 三角形外接圆的直径 $CP'Q'$, 一个 $\vec{v}_0$ - 三角形外接圆的直径 $CP'Q'$, 一个 $\vec{v}_0$ - 所描述的圆的直径

⟦folio 18⟧

图 6

图 7.

在 $OP'_0Q'_0$ 附近拉雪橇，我们有
$$|\vec{v}| = \frac{|P'_0Q'|}{\sin \gamma} = \frac{|P''Q''|}{\sin \frac{\gamma}{2} \cos \frac{\gamma}{2}},
$$
$$|\vec{v}_0| = \frac{|P'_0Q'|}{\sin \left(\frac{\pi}{2} + \frac{\gamma}{2}\right)} = \frac{|P'_0Q'|}{\cos \frac{\gamma}{2}}.$$

线段 $P'_0Q'_0$ 相对于平分线 $CO$ 的倾斜度比射线 $AO$、$BO$ 之一更陡，甚至比 $AC$ 和 $BC$ 更陡，后者以角度 $\frac{\gamma}{2}$ 倾斜于 $CO$。因此，平行线$P'_0P''$和$Q'_0Q''$之间的距离超过$|P'_0Q'_0| \sin \frac{\gamma}{2}$。

此外，$|P''Q''| > |P'_0Q'_0| \sin \frac{\gamma}{2}$与(5)一起得到$|\vec{v}| > |\vec{v}_0|$。

情况 2. 设 $\omega_2 = 0$ (图 6)；然后$|CP| = \omega_1 |BC|$，$|OP_0| = \omega_1/2$，从何而来$|\vec{v}| = \frac{\omega_1}{\sin \gamma} |BC|$，$|\vec{v}_0| =$

$$\frac{\omega_1}{2 \sin \frac{\gamma}{2}} |BO|.$$

但是$|BC| > |BO|$（因为$\angle BOC$很愚蠢）和$\sin \gamma < 2 \sin \frac{\gamma}{2}$，因此$|\vec{v}| > |\vec{v}_0|$。

情况 3. 设 $\omega_2 < 0$。与情况 1 一样，我们将四边形 $CPTQ$、$OP_0T_0Q_0$ 旋转 $90^\circ$ 到位置 $CP'T'Q'$、$OP'_0T'Q'_0$ (图 7) 并绘制$(P'_0P'') \parallel (Q'_0Q'') \parallel (BD) \parallel (OC)$。点 $P''$、$Q''$ 再次位于线段 $CP'$、$CQ'$ 的中点。

这次又来了
$$|\vec{v}| = \frac{|P'_0Q'|}{\sin (\pi - \gamma)} = \frac{|P''Q''|}{\sin \frac{\gamma}{2} \cos \frac{\gamma}{2}},
$$
$$|\vec{v}_0| = \frac{|P'_0Q'|}{\sin \left(\frac{\pi}{2} - \frac{\gamma}{2}\right)} = \frac{|P'_0Q'|}{\cos \frac{\gamma}{2}},
$$
为了确保$|\vec{v}| > |\vec{v}_0|$，在这种情况下我们只需要检查
$$|P''Q''| > |P'_0Q'_0|.$$

让我们准备以 $C$ 为中心的线段 $P''Q''$，以便它进入某个线段 $BM$。同样，让我们​​准备以 $O$ 为中心的线段 $P'_0Q'_0$，以便它进入某个线段 $BN$。重要的是烹饪系数相同。因此，要证明(6)，只需验证$|BM| > |BN|$即可。但后者从三角形$BNM$在顶点$N$处有钝角这一事实可以清楚地看出。事实上，如果$N$位于直线$BD$的左侧，则$M\widehat{NB} > \widehat{COB} > \frac{\pi}{2}$，如果$N$位于$BD$的右侧，则$M\widehat{NB} > M\widehat{NO} = \widehat{COA} > \frac{\pi}{2}$。引理已得证。

评论。从引理很容易推导出不等式$|O_1O_2| < |C_1C_2|$被保留，首先，如果$C_1$，$C_2$位于直线$AB$的不同边，其次，如果具有公共底$AB$的三角形$ABC_1$，$ABC_2$位于空间中的不同平面。

问题。让我们固定三角形 paramid 的底部并移动其顶部。内切球的中心移动速度会比顶点移动速度慢吗？
