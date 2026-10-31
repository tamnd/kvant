---
id: 1972-4-myakishev-reshenie-zadach-po-elektrostatike-zakon-kulona-napryazhennost-elektricheskogo-polya-c5b6571d
issue: kvant_1972_4
year: 1972
number: "4"
title: 解决静电问题。 （库仑定律。电场强度）
authors:
  - Мякишев Г. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 64
page_last: 67
page_labels: 62-65
tag: J2X8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2211d3bde1d89005cf2e0427cf654b2dd0123668815c522f1e4faf8fa937f398
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/16_myakishev-reshenie-zadach-po-elektrostatike-zakon-kulona-napryazhennost-elektricheskogo-polya-c5b6571d.md
source_content_sha256: c498175b14bede88d66c4b9ee9143f8aa303ede7e2d9014a8661c762356ed42c
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 62⟧

解决静电问题
（库仑定律。电场强度）

G.雅.米亚基舍夫

入学考试中经常会出现静电问题。而且，它们的解决方法也有很大不同。

静电学问题（与力学和分子物理学等问题不同）可能会导致与使用不同单位系统相关的额外困难。与 SI 系统一起，绝对单位制继续用于静电学。不同的系统是用于解决问题的基本公式有系数、优良的分权数量和维数。此外，在绝对静电系统SGSE中，静电公式的系数具有最简单的形式。因此，该系统更方便解决静电问题。

库仑定律

第一组问题与库仑定律的非总统适用有关。

在介电常数为$\varepsilon$的均匀介质中，两个带有电荷$q_1$和$q_2$且相距$R$的精确物体与力相互作用

$$F = k \frac{q_1 q_2}{\varepsilon R^2}.$$

(1)

在 SGSE 系统 $k=1$ 和 SI 系统 $k = \frac{1}{4\pi\varepsilon_0}$ 中，其中 $\varepsilon_0 = \frac{1}{4\pi \cdot 10^9} = 8.85 \times 10^{-12} \frac{\phi}{M}$ 是电常数。

SI 电荷单位库仑包含 $3 \cdot 10^9$ SGSE 电荷单位。

库仑力沿着连接带电的线定向

62

图 1

⟦folio 63⟧

因为它与对面成 30° 角。三角形ADE的边DE是$\frac{l}{4}$。 $AC = 2AE = 2\sqrt{\frac{l^2}{4} - \frac{l^2}{16}} = \frac{l\sqrt{3}}{2}$ 边。

来自相邻动作一侧的每个球上的力为 $F_1 = \frac{4q^2}{3l^2}$ (图 2)。任意两个球对第三个球施加的力为

$$F = 2F_1 \cos \alpha = \frac{4q^2}{l^2\sqrt{3}}.$$

当弦张力的水平分量为 $T' = T\sin \alpha = F$ 且垂直分量为 $T'' = T\cos \alpha = mg$ (图 1) 时，球处于平衡状态。因此有 $tg \alpha = \frac{F}{mg}$ 和 $q = \frac{l}{2}\sqrt{mg} \approx 100$ 单位。新加坡证券交易所。

使用库仑定律解决问题时，必须记住该定律涉及精确带电体的相互作用，不适用于任意形状的物体。当物体的几何尺寸明显小于它们之间的距离时，可以认为物体是精确的。因此，当计算两个物体之间的相互作用力时，其中一个或两个物体都不精确，您需要在心里将大物体分成小物体，以便每个元素都可以被视为精确的电荷。

图 2.

图 3.

问题 2. 半径为 $R$ 的细线尖峰携带电荷 $q$。环的中心有一个与$q$、$Q$和$Q \gg q$同名的电荷。确定刺的拉力。

从$Q \gg q$开始，环的各个元素之间的相互作用可以忽略不计。让我们选择一个长度为 $R\alpha$ (图 3) 的小环元素。电荷$Q$的侧面受到力$F = \frac{Q\Delta q}{R^2}$的作用，其中$\Delta q = \frac{q\alpha}{2\pi}$。

环的张力$T$由$F$平衡。从平衡条件来看，考虑到$\alpha$很小，我们有$F = 2T \sin \frac{\alpha}{2} = T\alpha$。

所需拉力为$T = \frac{Qq}{2\pi R^2}$。

该问题已在 SGSE 系统中得到解决。在国际单位制中

$$T = \frac{Qq}{8\pi^2\varepsilon_0 R^2}.$$

⟦folio 64⟧

电场电压

静止带电体之间的相互作用是通过电场进行的。其定量特征是电压矢量$E(x, y, z)$，它是作用在精确电荷上的力与该电荷大小的比值。作用在电荷上的力$q$等于$*$）

$$F = qE. \tag{2}$$

在解决电场电压计算问题时，首先需要确定准确电荷的场电压。是平等的

$$E = \frac{q}{\varepsilon R^2} \text{ в системе } \text{СГСЭ}, \tag{3}$$

$$E = \frac{q}{4\pi\varepsilon_0\varepsilon R^2} \text{ в системе } \text{СИ}.$$

如果存在一组精确的电荷，则场电压等于各个电荷产生的电压的几何和。

为了计算有限尺寸带电体的场电压，必须在心理上将其分解为各个元素，并且必须将所需电压计算为所有元素产生的张力的几何总和。但只有在物体上电荷分布简单对称的情况下，确定电压的问题才能解决

*）公式（2）总是很简单，但对力$F$的物理理解包含了应该强调的点。电场作用于带电体，向其施加加速度，或者在未向带电体供电时补偿其他力。但这些指控本身并不在战场上发挥任何作用；他们只是创造它。电场不是牛顿力学的对象，因此，力（2）不是牛顿力学意义上的体力。在运动方程（牛顿第二定律）中，它起着与普通机械力相同的作用：重力、弹性、摩擦力。但牛顿第三定律根本不适用。

够简单的。例如，如果电荷对称分布在球体上，则外场强度由公式（3）确定。此外，在$R$下，我们必须记住距球体中心的距离，而不是距其表面的距离。 B. B. Bukhovtsev, Yu 的新教科书“Physics.9”对此给出了基本且相应的不太严格的证明。 L.克里蒙托维奇，G.亚。米亚基舍夫。您还可以看到如何推导带电表面密度为 $\sigma$ 的无尽带电平面的场强公式：

$$E = \frac{2\pi\sigma}{\varepsilon} \left( \text{СГСЭ} \right) \text{ или}$$

$$E = \frac{\sigma}{2\varepsilon_0\varepsilon} \left( \text{СИ} \right). \tag{4}$$

问题3.推导公式（4），基于扁平电容器中的单荚磁场是两块极板电荷产生的场之和，其容量为$C = \frac{\varepsilon S}{4\pi d}$，其中$S$是极板面积，$d$是极板之间的距离。

电容器正、负带电极板的电场不同，且非常显着；此外，它们在电容器内部相加，在电容器外部相互补偿。因此，$E = 2E_1 = \frac{J}{d}$，这里$E_1$是一个板的场，$U$是它们之间的电势差。反过来

$$U = \frac{q}{C} = \frac{4\pi qd}{\varepsilon S} = \frac{4\pi d}{\varepsilon} \left( \text{так как } \sigma = \frac{q}{S} \right),$$

在哪里

$$E_1 = \frac{2\pi\sigma}{\varepsilon}.$$

带电板之间的均匀电场是由带电板中的粒子在地球附近的重力影响下以与普通物体相同的方式移动而产生的。区别在于

⟦folio 65⟧

只是地球给予所有物体相同的加速度$g \approx 980 \text{ cm/sek}^2$，并且电场中粒子的加速度取决于电荷与质量的比率：

$$a = \frac{q}{m} E.$$

(5)

任务 4. 一位数学家表示一个质量为 $m=1$ e 的球，悬挂在长度为 $l=36$ cm 的丝线上。如果向球施加 $q=\pm 20$ 单位的正电荷或负电荷，烧瓶矩阵的周期将如何变化。 SGSE 的电荷，将矩阵置于方向为 $E=10$ 单位的均匀电场中。方向SGSE，梅花直线方向垂直向下。

在没有电场的情况下，烧瓶矩阵的周期为$T_0 = 2\pi \sqrt{\frac{l}{g}} \approx 1,2$秒。在电场中，矩阵的加速度将等于 $g + \frac{q}{m} E$。因此，

$$T_1 = 2\pi \sqrt{\frac{l}{g + \frac{q}{m} E}} = 2\pi \sqrt{\frac{lm}{gm + qE}}.$$

如果$q=+20$单位。 SGSE 充电，然后$T_1 \approx 1,1$ 秒和$T_1-T_0 \approx -0,1$ 秒。

在$q<0$$T_2 \approx 1,35$秒和$T_2-T_0 \approx 0,15$秒的情况下。

任务 5. 在强均匀电场中，将 $E$ 指向点 1 和 2 处的一条梅线上，彼此距离 $l_0$，找到一个质子和一个电子 (图 4)。驾驶员的初始速度为零。运动开始后$t$时间后粒子之间的距离是多少？

我们选择电子所在的点2作为原点，并以电场方向为正方向。忽略粒子之间的相互作用（强场），我们可以认为电子和质子的运动是同等加速的。那么，根据众所周知的运动学公式，$t$时刻的质子坐标将等于

$$x_1 = l_0 + \frac{e}{m_\pi} E \frac{\tau^2}{2},$$

其中 $e$ 是电荷，$m_\pi$ 是质子质量。电子坐标

$$x_2 = -\frac{e}{m_\pi} E \frac{\tau^2}{2},$$

其中$m_\pi$是电子质量。所需距离

$$l = x_1 - x_2 = l_0 + \frac{eE\tau^2}{2} \frac{m_\pi + m_\pi}{m_\pi m_\pi} \approx \approx l_0 + \frac{eE\tau^2}{2m_\pi},$$

从$m_\pi \gg m_\pi$开始。

电场中的导体

在解决大量问题时，您需要了解导体在静电场中的行为。可以看出，导体内部的场方向为零，而在其表面上，场方向垂直于导体。导体内部的电荷也为零；全部集中在导体表面。

表面电荷在尖锐点处最密集，此处表面曲率最大。通过解决以下问题可以获得对此的视觉确认。

任务 6. 半径为 $r$ 和 $R$ 的两个导电球通过长导体连接。如果系统被赋予一定的电荷，请找出表面与球的电荷平面的关系。
