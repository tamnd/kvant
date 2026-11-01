---
id: 1978-11-zemlyakov-orlov-trehfaznyiy-tok-913badfa
issue: kvant_1978_11
year: 1978
number: "11"
title: 三相电流
authors:
  - Земляков А. Н.
  - Орлов В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 35
page_last: 38
page_labels: 33-36
tag: JXFS
lang: zh
source: kvant_digital
extraction: vision
content_sha256: d8c64182e8099ce804893f5028271ffe45a336ee3072b24d43d33fa39d72b4c2
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/15_zemlyakov-orlov-trehfaznyiy-tok-913badfa.md
source_content_sha256: da219adb2950d17715526b80ea1d0952ffff6d46dcaefcb5e4c07ccd31a24ed0
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

以及相同的频率 $\omega$ 和幅度 $A$，但相位差异很大，以至于它们的矢量图的末端形成正三角形（参见 图 3 上的 $\triangle P_1P_2P_3$）。

两个“相”之间（例如，第一相和第二相之间）的电压也是谐波振荡。它等于这些相位对应的谐波振荡之间的差。因此，它的矢量图就是矢量图$\overrightarrow{OP}_1$和$\overrightarrow{OP}_2$（图3）的差。这意味着该方向的振幅$A_{12}$等于正三角形的边长$P_1P_2P_3$。 “相位”（例如，第一）和“零”之间方向的幅度$A_{10}$是矢量$\overrightarrow{OP}_1$的长度，即正三角形$P_1P_2P_3$的高度$\frac{2}{3}$。

因此，振幅$A_{12}$与$A_{10}$的比率等于

$$\frac{220}{127} \text{ равно } \sqrt{3} \text{ только при } 6 \text{ и жено. Отсюда вытекает, что если первое направление в цепи равно в точности } 220 \text{ В, то второе равно } 127 \text{ В, а } \frac{220}{\sqrt{3}} \text{ В. В результате же сети случайные отклонения направления все равно преосходят } \left| \frac{220}{127} - \sqrt{3} \right|.$$

A.泽姆利亚科夫、B.奥尔洛夫

三相电流

工业发电机（例如安装在水力发电厂的发电机）实际上不仅提供交流电（即根据谐波定律$i(t) = A \cos(\omega t + \varphi)$变化的电流），而且提供三相电流。在本说明的第一部分中，我们将讨论如何获得这样的“三相”电流，在第二部分中，我们将讨论为什么它适合在电动机中使用。正如前面的注释，相同的数学例子在这里起着决定性的作用：谐波振荡矢量图的相加。

1. 交流发电机

如果接线框架在均匀磁场中均匀旋转，则通过框架的磁感应通量将按照和谐定律变化：

$$\Phi(t) = (\vec{B} \cdot \vec{n}) \cdot S = BS \cos \omega t,$$

其中$\vec{B}$是磁感应矢量，$S$是框架限制的面积，

⟦folio 34⟧

图 1.

图 2.

图 3.

$\vec{n}$是框架平面的单位法线，框架以角速度$\omega$旋转，在时间$t$与向量$\vec{B}$形成角度$\omega t$；我们认为框架的旋转轴垂直于向量 $\vec{B}$ (图 1)。由于洛伦兹力的作用，在场中与框架一起移动的自由电荷开始沿着框架的导体移动，其中将产生等于

$$e = -\Phi'(t) = \omega BS \sin \omega t.$$

框架两端之间的电压也会根据谐波定律而变化，并且根据闭合电路，会产生交变电流：

$$i(t) = I \cos(\omega t + \varphi).$$

这是最简单的发电机模型（参见《物理学》10，第 21 节）。

在工业发电机中，旋转的不是机架，而是磁场，并且 EMF 是在固定绕组中产生的，实际上是在三个彼此成 $120^\circ$ 角度 (图 2) 的相同绕组中产生的。这导致产生的电振荡相对于彼此异相 $2\pi/3$ - 在右侧，对于感应电动势，我们可以写成：

$$e_1 = \sin \omega t,$$
$$e_2 = \sin \left(\omega t + \frac{2\pi}{3}\right),$$
$$e_3 = \sin \left(\omega t + \frac{4\pi}{3}\right)$$

（解释）。相应的电流系统称为*三相*；它于 1888 年由俄罗斯电气工程师 M. O. Dolivo-Dobrovolsky 提出，现已在世界各地使用。为什么需要三相电流系统？有什么好处？

首先，我们将解释负载如何连接到三相发电机。如果将相同的负载连接到所有这些绕组 (图 3a)，则所有三个电路中的电流幅度将相同

⟦folio 35⟧

和相同的：

$$i_1 = I \cos(\omega t + \varphi),$$
$$i_2 = I \cos(\omega t + \varphi + \frac{2\pi}{3}),$$
$$i_3 = I \cos(\omega t + \varphi + \frac{4\pi}{3}).$$

使用矢量图*) (图 4) 将这些简谐振动相加，我们得到：$i_1 + i_2 + i_3 = 0$。因此，如果电线$X$、$Y$和$Z$组合成一根电线（如图36），那么其中的电流将为零！这正是电流从三相发电机传输的方式 - 沿着 $A$、$B$、$C$ 线并通过中性线 0。对于对称负载（如上所述），不需要中性线，但如果片段不对称，例如在房屋中的照明网络中 (图 5)，则中性线“补偿”电流中将出现一根细线。

三相电流系统提供的主要优点是三相电动机的简单性，我们现在将考虑其工作原理。

2. 交流电机

让频率为$\omega$的交流电流过绕组$L$。然后产生交变磁场，使绕组$L$（图 6）的轴线近似均匀且沿$n$方向，磁场感应也按调和律变化，因此感应矢量可写为以下形式

$$\vec{B} = B \cos \omega t \cdot \vec{n}.$$

如果将一个封闭的金属框架$K$放置在轴$n$附近，旋转轴垂直于$n$（图6），那么框架内将产生感应电流，并且安培力将作用在其上（“物理9”，第120段），

*) 参见“物理学 10”，第 26 段； “代数和分析的开始 10”，第 82 段，例如。 69-70； «Kvant»，1976 年，第 11 号，艺术。 “谐波振动的增加。”

⟦folio 36⟧

方向垂直于方向电流和矢量 $\vec{B}$。这些力产生扭矩，使框架绕其轴线转动。然而，在框架垂直于$n$轴的位置，这个扭矩为零；为了开始旋转，需要将框架从这个位置移开——使用计算出的框架将通过惯性通过这个位置，尽管不均匀，但它会旋转。这些是单相交流电动机的工作原理。

事实证明，如果将三相电流连接到彼此成$120^\circ$角度的那些绕组上，如图7所示，则磁场会舔过大小恒定的绕组对称轴的0交点，并以角速度$\omega$匀速旋转。

为了证明这一点，我们求出绕组 $AX, BY, CZ$ 中的电流产生的磁感应矢量之和 $\vec{B} = \vec{B}_1 + \vec{B}_2 + \vec{B}_3$：

$$\vec{B}_1 = B \cos \omega t \cdot \vec{n}_1,$$
$$\vec{B}_2 = B \cos \left( \omega t + \frac{2\pi}{3} \right) \cdot \vec{n}_2,$$
$$\vec{B}_3 = B \cos \left( \omega t + \frac{4\pi}{3} \right) \cdot \vec{n}_3,$$

其中$\vec{n}_i$是相应的单位法线。让我们在穿过绕组轴的平面上引入坐标系，使轴$Ox$沿着矢量$\vec{n}_1$；该系统中向量 $\vec{n}_2$ 的坐标将为（参见 图 8）

$$\vec{n}_1 = (1; 0),$$
$$\vec{n}_2 = \left( -\frac{1}{2}; -\frac{\sqrt{3}}{2} \right),$$
$$\vec{n}_3 = \left( -\frac{1}{2}; \frac{\sqrt{3}}{2} \right).$$

使用向量 $\vec{B}_i$ 的公式，可从此处找到总和 $\vec{B}_1 + \vec{B}_2 + \vec{B}_3 = \vec{B}$：

$$B_x = B \cos \omega t - \frac{1}{2} B \cos \left( \omega t + \frac{2\pi}{3} \right) - \frac{1}{2} B \cos \left( \omega t + \frac{4\pi}{3} \right),$$
