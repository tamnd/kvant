---
id: 1989-9-gotman-dubrovskiy-o-svoystvah-tsentra-okruzhnosti-21e17723
issue: kvant_1989_9
year: 1989
number: "9"
title: 关于外圆圆心的性质
authors:
  - Готман Э. Г.
  - Дубровский В. Н.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 41
page_labels: 38-39
tag: 8DH8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7c0cefa0f87f2f9568bee0203b4a3466f23e74144eb838f0208d4e3b8d97edd7
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/05_gotman-dubrovskiy-o-svoystvah-tsentra-okruzhnosti-21e17723.md
source_content_sha256: 82e73ce52bc777efee73c82ee3e1bc74c318b303db4ca216e8074baed1567906
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

关于外圆圆心的性质

在本文中，我们将提供问题 M1146 的解决方案。这个任务本身并不困难。但经过仔细检查，其背后出现了一长串概括。

M1146。 K点是等边三角形ABC的边AB的中点。点 M 和 N 在边 AC 和 BC 上取，使得 ∠MKN=60°。证明三角形MCN的周长等于三角形ABC周长的一半。

让我们立即看一个一般情况。令 K 为大小为 γ 的角 MCN 平分线上的点，点 K 和 C 位于 MN 的相对两侧 (图 1)。那么下面的条件是等价的：

(1) ∠MKN=(π−γ)/2,
(2) MN=PM+QM，其中P和Q是K点在角两侧的投影。

由此在γ=60°（图2）处得到问题M1146：此时，等式（1）中的角度MKN等于60°，性质（2）等价于等式CM+MN+NC=CP+CQ=2CK cos 30°=3AB/2，即问题的表述。顺便请注意，在 γ = 90° 时会出现问题 M851（参见 1984 年的«Kvant» No. 3）。

(1)和(2)等价的证明之一可以通过检查K点(图3)圆中角度π−γ的△KPM来获得。结果，它会到达△KQL（∠PKQ=π−γ），其中L是直线CN上的某个点，并且∠MKL=∠MKQ+∠QKL=

= ∠MKQ+∠PKM=π−γ, NL=NQ+QL=NQ+MP。因此，条件(1)和(2)均等价于三角形MKN和LKN相等。事实上，这些三角形具有公共边 ​​KN 和等边 KM 和 KL，此外，由于 (1) - 等角 (∠MKN=(π−γ)/2 和 ∠LKN=∠LKM=∠LKM−∠NKM=π−γ-(π−γ)/2，以及由于 (2) - 等边 MN 和 NL=NQ+QL=NQ+MP。

(1)和(2)等价的第二个证明揭示了K点的几何意义。事实证明，条件(1)和(2)意味着

(3) K是三角形CMN的外圆的中心，即与边MN相切并延伸到边CM和CN的圆。

事实上，如果K是这个圆的中心，那么P和Q就是它与直线CM和CN的切点。设R为圆与MN(图4)的切点，则显然MP=MR，NQ=NR，因此满足性质(2)。由三角形KPM和KRM、KQM和KRN等式可知∠MKN=∠PKQ/2=(π−γ)/2，即满足条件(1)。相反，例如令K点满足条件(1)。让我们在角 MCN 中插入一个以 K 为圆心的圆，并在其上画一条与 MN 平行的切线 M′N′。根据已证明，∠M′KN′=(π−γ)/2 = ∠MKN，但这只有在M′=M、N′=N时才有可能。因此，从(1)可得出(3)。同样证明由(2)可得(3)。

⟦folio 39⟧

因此，对于以 $K$ 为中心的角 $C$ 内切的圆的所有切线 $MN$，从角顶点的一侧绘制，构造了角 $MKN$ 的大小以及三角形 $CMN$ 的周长（并且分别相等，$(\pi - \gamma)/2$ 和 $CP + CQ = 2CK \cos(\gamma/2)$）。所有这些线段的另一个常数值是点 $M$ 和 $N$ 除线段 $CP$ 和 $CQ$ 的比率的乘积：

$$\frac{CM \cdot CN}{MP \cdot NQ} = \frac{1}{\sin^2(\gamma/2)}$$

为了证明这一点，我们将$MK$和$NK$替换为三角形$CMN$的外角$PMN$和$QNM$的平分线（参见图4）。让我们放入$\angle CMN = \alpha$，$\angle CNM = \beta$，然后从三角形$PKM$和$CKM$我们得到$\angle PKM = \alpha/2$，$\angle CKM = \beta/2$。

根据正弦定理

$$\frac{CM}{MP} = \frac{\sin(\beta/2)}{\sin(\alpha/2) \sin(\gamma/2)}$$

$$\frac{CN}{NP} = \frac{\sin(\alpha/2)}{\sin(\beta/2) \sin(\gamma/2)}$$

从这些等式可以得出 (4)。

如果我们绘制线段 $PQ$ 并距离三角形 $RUV$，则我们的配置的另一个美丽属性就会显现出来，其中 $U$ 和 $V$ 是 $PQ$ 与 $KM$ 和 $KN$ (图 5) 的交点：

$$U \cap V = \text{основания высот треугольника } KMN, \text{ причем треугольник } RUV \text{ подобен треугольнику } CNM \text{ с коэффициентом } 1/\sin(\gamma/2).$$

让我们使用相似变换概述证明。首先，我们画出三角形 $CMN$ 的所有（内角和外角）角的平分线，并注意，除了 $K$ 之外，还有两个交点 - 中心 $K_1$ 和 $K_2$

三角形$CMN$的两个变形圆（参见图5）。由于相邻角的平分线是外周线，因此点 $C, M, N$ 是三角形 $KK_2K_1$ 高的底边。因此，我们只需表示系数为$k = \sin(\gamma/2)$的相似变换，将$\triangle KK_1K_2$变换为$\triangle KNM$，同时将$\triangle MNC$变换为$\triangle VUR$。这种变换是角$MKN$的对称相对平分线$l$与中心$K$和系数$k$的合成$F$。

事实上，在这种情况下，转换

$$1^\circ$$点$K$保持原位，线$KK_1$和$KK_2$相互交叉，以及$F(K_1) = N$、$F(K_2) = M$（输入$KN/KK_1 = KM/KK_2 = \cos \angle MKN = \sin(\gamma/2) = k$）；

$$2^\circ$$ $F(C) = R$（因为 $F(\triangle KK_1K_2) = \triangle KNM$、$KC$ 和 $KR$ 是这些三角形的高度）；

$$3^\circ$$线$KP$进入线$KC$（它们相对于$l$对称）和$F(R) = E$，其中$E$是$KC$和$PQ$（$KE/KR = KE/KP = \cos \angle PKC = k$）的交点，因此。

$$4^\circ$$直线$MN$与直线$PQ$相交，即$F(M) = V$、$F(N) = U$。

尝试独立找到命题（5）的“传统”证明（带有辅助圆、计数角度等），并解决以下问题。

1. 证明条件(4)和(5)与(1)、(2)和(3)等价。

2. 表明，如果在我们的配置中，我们从一开始就从线 $MN$ 上取与点 $C$ 同侧的点 $K$，则条件 (2)、(4)、(5) 仍然彼此等效，条件也是如此

$$\begin{align*}
(1') & \angle MKN = (\pi + \gamma)/2 \\
(3') & K - центр вписанной окружности треугольника CMN.
\end{align*}$$

E.G.戈特曼、V.N.杜布罗夫斯基
