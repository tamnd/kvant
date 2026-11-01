---
id: 1985-1-resheniya-zadach-m884-m885-f894-f897-f2d7ab77
issue: kvant_1985_1
year: 1985
number: "1"
title: 问题M884、M885的解决方案； F894—F897
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 47
page_last: 52
page_labels: 45-50
tag: UR8E
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1f07ded4789cf02cf3c56c01fd64c337a441b040d2a46f9d1dbee8268c06b86a
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/18_resheniya-zadach-m884-m885-f894-f897-f2d7ab77.md
source_content_sha256: 5e7d673b062898cb85afa82ef515fc654c726eb2fc15769cea185b3c55bfb476
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

mirror, the lens and the object are enclosed in a case made of translucent plastic (Fig. 2). This system generates two images of the object and an image of the lens. Both images of the object have the same size, independently of the distance between the lens and the object. What is the enlargement of the lens' image?

E. P. Kuznetsov

问题解决方案

M884, M885; F894—F897

该解基于以下考虑：如果$A(a; f(a))$和$B(b; f(b))$是函数图（图1）上的两点，则对角线为$AB$的矩形$\Pi(A, B)$覆盖了从$A$到$B$的图部分，其面积$S$满足不等式$2\sqrt{S} \leq l+h$，其中$l=b-a$是其底边的长度，$h=f(b)-f(a)$是其高度；这个不等式本质上是关于论证平均值和几何平均值$\sqrt{lh} \leq (l+h)/2$的不等式。

这种考虑可以通过两种方式使用。我们暂时假设$f(0) = 0$，$f(1) = 1$。

1) 让我们将函数$f$扩展到整个正值，使其保持连续且单调（例如，我们可以将$f(x) = x$与$x > 1$放在一起）。令 $A_0$ 为图形的起点（坐标为 $(0; 0)$）。我们还考虑一下图上的点$A_1, ..., A_m$，使得矩形$\Pi(A_{i-1}; A_i)$、$i=1, 2, ..., n$的面积等于$1/n^2$；这些点的存在显然是由函数$f$的连续性和单调性得出的。对于每个矩形，底长和高的总和不小于$2\sqrt{1/n^2}=2/n$，因此点$A_n$的坐标之和（相等，对应于所有矩形的底长和高的总和）不小于2。因此，这些坐标中至少有一个不小于1，这意味着构造的$n$矩形覆盖了图表。

2) 让我们在函数$f$的图形上从$B_0$$(0; 0)$开始选择点$B_0, B_1, ..., B_n$，使得每个矩形$\Pi(B_{i-1}, B_i)$、$i=1, ..., n$的底边长度和高度之和等于$2/n$。 （容易看出$B_i$是$y=2i/n-x$线与图形的交点，特别是$B_n$是图形的终点——点$(1; 1)$；参见图2。）凭借上述估计，每个矩形的面积不超过$1/n^2$。如有必要，放大它们，使它们的面积完全相等

⟦folio 46⟧

1/n²，我们得到了所需的覆盖范围。

如果 f(0) > 0 或 f(1) < 1，我们用垂直线段补充图形，将点 (0; 0) 与其起点 (0; f(0)) 和 (1; 1) 与其终点 (1; f(1)) 连接起来 (图 3)。您将得到一条连接点 (0; 0) 和 (1; 1) 的连续曲线，上述两种解释都可以实际应用而无需更改。

同一个例子允许我们陈述任何（可能不连续）函数 f 的问题：在不连续点，图形通过一段（图 4 处的红色段）补充为连续曲线。然而，这种情况下的严格论证有点超出了学校课程的范围。

N.B.瓦西里耶夫，
V.N.杜布罗夫斯基，
于S.奥列夫科夫

**M885*。对于每个自然数 n，我们用 p(n) 表示 n 划分为自然被加数之和的数量（仅被加数顺序不同的划分被认为是相同的）。给定分区中数字分区的集合称为其解析。

a) 证明编号为 n 的所有分区的价差之和 q(n) 等于 1 + p(1) + p(2) + ... + p(n-1)。

b) 证明该和不大于 √2n p(n)。

4-4
4-3+1 ↔ 1-1
4-2+2 ↔ 2-2
4-2+1+1 ↔ 2-1+1
4-1+3 ↔ 3-3
4-1+2+1 ↔ 3-2+1
4-1+1+1+1 ↔ 3-1+1+1

a) 如果其中一项与其余项分离（下划线），则将数字 n 除为自然项之和将被称为移位；我们将认为移位的分区（仅在细分顺序上是优秀的）是相同的。 （左边图上都是数字4的偏移分区；突出显示的以红色显示。）注意，如果k是某个分区的扩展（无偏移），则可以从此分区获得k个偏移分区。因此，n的偏移分区总数等于q(n)。另一方面，如果从任何被消除的分区中，除了由单个元素组成的分区之外，删除下划线元素，则结果将是小于n的某个数目的分区。反之亦然，如果 m < n，则从数字 m 的任何分区都可以明确恢复数字 n 的偏移分区：需要将被加数 n-m 添加到数字 m 的分区并在其下划线（在 图 中，数字 4 的偏移分区之间存在一一对应关系，除了分区 4 = 4 和小于 4 的数字分区）。但小于 n 的数字的分区数等于 p(1) + p(2) + ... + p(n-1)。因此，q(n) - 1 = p(1) + p(2) + ... + p(n-1)。

换句话说，这个解决方案的思想可以表述如下：如果我们向数字 m = 1, 2, ..., n-1 的 p(1) + p(2) + ... + p(n-1) 个分区中的每一个添加一项 n-m，那么我们将得到数字 n 的每个分区（除了 trival n=n）与其分布一样多的次数。

6) 只要证明数字 n 的任意划分到自然被加数之和的扩展不超过 √2n 就足够了。我们来证明一下这个说法。令 a₁, ..., aₙ 为某个分区中包含的所有不同项（解析 k），且 0 < a₁ < ... < aₙ。那么，一方面，

⟦folio 47⟧

$$a_1 + a_2 + \dots + a_k \leq n, \text{ а, с другой стороны, } a_1 \geq 1, \quad a_2 \geq 2, \quad \dots, \quad a_k \geq k \quad (\text{действительно, } a_1 \geq 1; \quad a_2 > a_1 \geq 1, \quad \text{следовательно, } a_2 \geq 2; \quad a_3 > a_2 \geq 2, \quad \text{следовательно, } a_3 \geq 3, \quad \text{и т. д.}).$$
因此$n \geq a_1 + a_2 + \dots + a_k \geq 1 + 2 + \dots + k = k(k+1)/2 \geq k^2/2$，即$k \leq \sqrt{2n}$。

于S.奥列夫科夫

F894。其中一个项目计划使用面积为$S=1$公里$^2$的太阳帆用于太阳系中的航天器飞行。当飞行器在地球轨道上绕太阳运行时，帆展开，地球轨道的半径为 $R_3=1,5\cdot 01^8$ 公里。随着进一步的运动，帆不断地垂直于太阳光线，地球轨道上的压力为 $p=10^{-5}$ Pa。
1) 航天器的质量是多少才能飞离太阳系？
2) 飞行器的最大质量是多少才能到达半径为$R_M=2,3\cdot 10^8$公里的火星轨道？不考虑地球和其他行星的引力影响。
太阳质量与引力常数$M_C G=1,3\cdot 10^{11}$ km$^3/c^2$的乘积。

◆ 太阳帆展开时，太阳张力和太阳光线压力作用在装置上。评估这些模式的结果 -

$$F_{\varphi} = G \frac{M_C m}{R_3^2} - p S = G \frac{M_C m}{R_3^2} - \frac{G m R_3^2 p S}{G m R_3^2} = G \frac{(M_C - p SR_3^2/G m) m}{R_3^2}.$$

我们看到，太阳光线的压力似乎降低了装置对太阳的张力强度 - 该力与太阳没有质量 $M_C$ 时的力相同，但有效质量略小，等于

$$M_{\varphi} = M_C - \frac{p SR_3^2}{G m}.$$

利用引入的有效质量，我们可以在不考虑太阳光线压力的情况下进一步解决问题。

航天器在质量为 $M_{\varphi}$ 的物体边界场中的总能量 —

$$E = \frac{mv^2}{2} - G \frac{m M_{\varphi}}{R}.$$

根据能量守恒定律，航天器轨道上任意一点的能量应等于

$$E = \frac{mv^2}{2} - G \frac{m M_{\varphi}}{R_3},$$

其中$v_3$是飞行器在距离太阳$R_3$处张开帆时的速度。我们可以根据太阳力影响下地球轨道上的装置的运动方程找到这个速度：

$$\frac{mv^2}{R_3} = G \frac{m M_C}{R_3^2} \Rightarrow v_3 = \sqrt{G \frac{M_C}{R_3}}.$$

因此，

$$E = G \frac{m}{R_3} \left( \frac{M_C}{2} - M_{\varphi} \right) = G \frac{m}{R_3} \left( \frac{p SR_3^2}{G m} - \frac{M_C}{2} \right).$$

如果$E \geq 0$，即提供，该设备可以飞离太阳系

$$\frac{p SR_3^2}{G m} - \frac{M_C}{2} \geq 0.$$

从这里开始，设备位于

⟦folio 48⟧

或许：

$$m \leq \frac{2pSR_3^2}{GM_C} \approx 3,46 \cdot 10^3 \text{ кг.}$$

质量较大时，该装置将在封闭轨道上移动。

让装置的轨道与火星轨道接触一定质量$m_1$。 (Of all possible masses $m$, at which the apparatus reaches the orbit of Mars (crosses it), $m_1$ is the maximum.) In this case, the orbit of the apparatus is an ellipse, the major axis of which is equal to $R_3+R_M$ (see 图).在接触点处，车辆的速度垂直于车辆的半径矢量。

根据能量守恒定律

$$\frac{m_1v_3^2}{2} - G \frac{m_1M_3\phi}{R_3} = \frac{m_1v_2^2}{2} - G \frac{m_1M_3\phi}{R_M} \Rightarrow v_3^2 - v_M^2 = 2GM_3\phi \left( \frac{1}{R_3} - \frac{1}{R_M} \right).$$

根据开普勒第二定律

$$v_3R_3 = v_MR_M \Rightarrow v_M = v_3 \frac{R_3}{R_M}.$$

将$v_M$的表达式代入(*)并考虑到$v_3 = \sqrt{G \frac{M_C}{R_3}}$，经过多次变换我们得到：

$$2M_3\phi R_M = M_C(R_M + R_3),$$

或者

$$2 \left( M_C - \frac{pSR_3}{Gm} \right) R_M = M_C(R_M + R_3).$$

从这里我们找到设备可以到达火星轨道的最大质量$m_1$

$$m_1 = \frac{2pSR_3^2}{GM_C} \frac{R_M}{R_M-R_3} \approx 10^4 \text{ кг.}$$

V.A.达尼林

F895。 One of the legends about the origin of the asteroid belt goes back to the ancient Rechensk legend about the son of the sun Gelyus - Phaethon, struck by Zeus (Jupiter).根据这一理论，法兹顿行星应该是由一群石群形成的，它们距离木星非常近。在木星门户群的影响下，该群分裂成独立的群——小行星。估计蜂群半径约为 10⁴ 公里；该群的质量（小行星的总质量）比木星的质量小 10⁶ 倍。

在开始瓦解之前，虫群必须移动到距离木星中心多远？

让我们看看距离木星最近的区块。蜂群的崩溃意味着该团块与蜂群中心之间的距离将会增加。

整个蜂群以加速度落在木星上，这是由木星吸引力赋予的：

$$ma_1 = G \frac{mM}{R^2} \Rightarrow a_1 = G \frac{M}{R^2},$$

其中$m$是虫群的质量，$M$是木星的质量，$R$是虫群中心与木星之间的距离。该块在木星吸引力和整个群体对其施加的吸引力的影响下移动。物块向木星移动的加速度为

$$a_2 = G \frac{M}{(R-r)^2} - G \frac{m}{r^2};$$

其中 $r$ 是群体的半径。如果$a_2 > a_1$，则块与群体中心之间的距离将随时间增加

⟦folio 49⟧

人类——蜂群瓦解。从这个条件我们得到：

$$\frac{M}{(R-r)^2} - \frac{m}{r^2} > \frac{M}{R^2}.$$

使用$r < R$，我们发现：

$$\frac{2rM}{R^3} > \frac{m}{r^2} \Rightarrow R < r^3 \sqrt{\frac{2M}{m}} \approx 1,26 \cdot 10^6 \text{ км}.$$

V·E·贝隆奇金

F896。密闭容器内有饱和水、100℃的蒸汽和剩余的水。蒸汽质量$M = 100 \text{ г}$，水质量$m = 1 \text{ г}$。加热容器直至所有水蒸发。容器应该加热到什么温度？这需要多少热量？温度每升高1℃，饱和水蒸气的压力增加3.7kPa。水的蒸发比热为$r = 2,25 \cdot 10^6$J/kg，水蒸汽的比热为$c_V = 1,38 \cdot 10^3$J/(kg·K)。

◆ 让我们首先确定容器必须加热到什么温度才能使所有的水蒸发。

让我们写出在容器中水和蒸汽的初始条件下蒸汽的状态方程为$p_2 + \Delta p$。根据问题条件$\Delta p = \alpha \cdot \Delta T$，其中$\alpha = 3,7$ kPa/K。利用这一点，我们写出温度$T_2$下蒸汽的状态方程：

$$p_2 V = \frac{M + m}{\mu} RT_2,$$

或者

$$(p_1 + \alpha \cdot \Delta T) V = \frac{M + m}{\mu} R (T_1 + \Delta T).$$

一起求解 (1) 和 (2)，我们找到 $\Delta T$：

$$\Delta T = \frac{m T p}{M T a - M p - m p} \approx 0,29 \text{ K}.$$

因此，为了蒸发所有的水，必须将肥皂水加热到 100.20 °C 的温度。为此所需的热量可以从热平衡方程中找到：

$$Q = r m + c_V (M + m) \cdot \Delta T \approx 2290 \text{ Дж}.$$

A.I.布兹丁

◆ 让我们写出$A$和$B$点的质点运动方程：

$$m a_A = q E_A, \quad m a_B = q E_B.$$

由此可见

$$\frac{a_A}{a_B} = \frac{E_A}{E_B},$$

that is, the ratio of particle accelerations at points $A$ and $B$ is equal to the ratio of the directional field created by the polyring at these points.另一方面，从问题的条件我们实际上知道了$A$和$B$点的势场关系。确实，根据能量守恒定律

$$\frac{m v_A^2}{2} = q \varphi_A, \quad \frac{m v_B^2}{2} = q \varphi_B$$

（因为在无穷远粒子能量为零），并且

⟦folio 50⟧

$$\frac{\varphi_A}{\varphi_B} = \frac{v_A^2}{v_B^2} = n^2.$$

让我们尝试通过已知的关系$\varphi_A/\varphi_B$来表达关系$E_A/E_B$。

该体积在精神上被分成许多元素部分，每个部分的电荷为$\Delta Q$（$Q$是整个半环的电荷）。 Let $\Delta \varphi_B$ and $\Delta E_B$ be, respectively, the potential and intensity of the field created at point $B$ by a section that is located at a distance $Q$ from this point (see 图).然后

$$\Delta \varphi_B = k \frac{\Delta Q}{\varphi} = k \frac{\Delta Q}{2r \cos \alpha}, \quad \Delta E_B = k \frac{\Delta Q}{\varphi^2} = k \frac{\Delta Q}{4r^2 \cos^2 \alpha}.$$

向量 $\vec{E}_B$ 在水平轴 $x$ 上的投影等于

$$\Delta E_{Bx} = \Delta E_B \cos \alpha = k \frac{\Delta Q}{4r^2 \cos \alpha} = \frac{\Delta \varphi_B}{2r}.$$

从对称信息可以清楚地看出，点 $B$ 处的场强 $\vec{E}_B$ 沿着 $x$ 轴。 Consequently, the value $E_B$ is equal to the sum of the projections $\Delta E_{Bx}$ of the field strengths created by all elementary sections, that is

$$E_B = \sum \Delta E_{Bx} = \sum \frac{\Delta \varphi_B}{2r} = \frac{\varphi_B}{2r}.$$

关于$\varphi_A$和$E_A$的值，则

$$\varphi_A = \frac{Q}{r}, \quad E_A = \frac{2Q}{\pi r^2} = \frac{2\varphi_A}{\pi r}$$

（自己获取这些匹配项）。

因此，$E_A/E_B = 4\varphi_A/\pi\varphi_B$，$A$和$B$点处的质点加速度之比等于

$$\frac{a_A}{a_B} = \frac{4}{\pi} \frac{\varphi_A}{\varphi_B} = \frac{4}{\pi} n^2.$$

V·T·卡佩特扬

**顶夸克和顶虎**

（开头部分请参见第 41 页）

可以根据所有带电粒子动量的测量结果来猜测。由于记录的事件与实际上静止的$W$玻色子的衰变相关，因此衰变中所有粒子的总动量应等于零。然而，测量到的带电粒子动量结果不为零，

由此得出中微子存在的结论。

尼鲍利埃对相关事件的可靠解码是，在质子与反质子碰撞期间，诞生了由两个夸克组成的部分——顶夸克$t$和美丽的反夸克$b$。顶夸克根据该方案衰变

$$t \rightarrow b + \mu^+ + v$$

（这里 $\mu^+$ 是正 mu-meon），$b$ 和 $b$ 代表两个粒子束。现在我们必须等待结果。

据估计，顶夸克的质量对应于大约 40 GeV 的能量（钙原子核的质量！）。*）当然，这小于小虎崽的质量，甚至还小于刚出生的小虎崽的质量，但在“粒子动物园”中，顶夸克是一个记录保持者。

我同意。

*) 如果我们假设 ispilon 介子的质量等于两个 $b$ 夸克的质量 (5 GeV + 5 GeV = 10 GeV)，并且新生儿的质量 (≈ 50 GeV) 等于 $b$ 夸克和顶夸克的质量，则可以得到顶夸克质量的估计。
