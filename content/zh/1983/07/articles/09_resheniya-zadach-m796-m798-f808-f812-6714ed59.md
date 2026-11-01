---
id: 1983-7-resheniya-zadach-m796-m798-f808-f812-6714ed59
issue: kvant_1983_7
year: 1983
number: "7"
title: 问题解决方案M796—M798； F808—F812
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 52
page_labels: 46-50
tag: 13QT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 424a0fdca52a692e3bef142bd618d7b677e886fa275c790f0385ba7f2aa97304
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/09_resheniya-zadach-m796-m798-f808-f812-6714ed59.md
source_content_sha256: 8a8732c598e42cc819acb01b4dec2c8fcafff62bb74b0d85045b4866921eb65f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

the ammeter then? The battery is assumed ideal, the resistance of the wires is 2 Ohm.

A. R. Zilberman

P826. Far-away objects are viewed through a convergent lens of focal distance $F=9$ cm, the eye being located at the distance $a=36$ cm from the lens. Estimate the minimal size of a screen which, if placed behind the lens, would entirely cover the field of vision. Where should the screen be placed?

D. V. Belov

P827. A cube with side $a$ moves with velocity $v=0.8$ c (where $c$ is the velocity of light) in a direction perpendicular to one of its faces. What will we see on a photograph of the cube taken by a far-away camera with a very short exposure, if the optical axis of the camera is perpendicular to a face of the cube and intersects the trajectory of its centre (figure Pric. 3)?

D. Ju. Grigoriev

问题解决方案

M796—M798; F808—F812

答案：$\widehat{APB}=135^\circ$。让我们围绕 $90^\circ$ 上的点 $B$ 旋转 $\triangle ABP$，使顶点 $A$ 与 $C$ 对齐（参见 图）。让顶点$P$到达点$Q$。然后是$|PQ|^2=2|BP|^2=8|AP|^2$（$\triangle BPQ$等头矩形）和$|QC|=|PA|$。因此，$|PQ|^2+|QC|^2=9|AP|^2=|CP|^2$，即$PQC$，是直角三角形，内角为$PQC$。因此$\widehat{APB}=\widehat{CQB}=\widehat{CQP}+\widehat{PQB}=90^\circ+45^\circ=135^\circ$。

还有一种不太人为（但更麻烦）的解决方案使用坐标方法。我们以直线$AB$和$AD$为坐标轴；令$(x, y)$为点$P$的坐标。然后，考虑正方形的边长等于 1，我们得到：$|AP|^2=x^2+y^2$、$|BP|^2=x^2+(1-y)^2$、$|CP|^2=(1-x)^2+(1-y)^2$。根据条件$|AP|^2:|BP|^2:|CP|^2=1:4:9$，从这里很容易找到$x$和$y$，然后找到所需的角度。

L·D·库尔扬奇克

M797*。众所周知，整数平方的最后一位数字只能是数字 0、1、4、5、6 和 9。最后一位数字之前是否可以包含任意一组数字，即对于任意一组$n$数字$a_1, a_2, \dots, a_n$，都可以找到一个平方以数字$a_1a_2\dots a_nb$结尾的整数（其中 b 是上面列出的数字之一）？

答案：不。我们将给出这个事实的两个证明。

第一个证明。令 $A_n$ 为从 $n$ 精确平方数开始的所有组合的数量。我们将证明如果$n \geq 4$则$A_n<10^n$。我们的陈述将由此而来：即使每个组合$a_1, \dots, a_n$只与一个$b$组合被发现，也已经存在$A_n=10^n$。想要得到所有$n$位的平方数结尾，这是非常有必要的；只需考虑 $n$ 位数字的平方就足够了。我们将这些 $10^n$ 数字（从 0 到 $10^n$-1）分成几类，将所有具有相同 $n$ 数字平方结尾的数字收集到一类中（如果 $p^2-q^2$ 能被 $10^n$ 整除，则$p$ 和 $q$ 包含在一类中）。那么$A_n$就等于此类的数量；基于此，我们将估计$A_n$。

让我们分别考虑三组$n$位数字：（1）能被$5^n$（以及$2^n$）整除的数字； (2) 不能被$5^n$整除的奇数（少于$0,5 \cdot 10^n$）； (3) 不能被$5^n$整除的偶数（也比$0,5 \cdot 10^n$少）。与$10^n$相比，第一组的数字数量较少。对我们来说重要的是，当除以 $2^n$ 时，它们会给出两两不同的余数（因为 $k \cdot 5^n-l \cdot 5^n=(k-l) \cdot 5^n$ 不能除以

⟦folio 47⟧

2$^n$在$1 \leqslant l < k \leqslant 2^n$），因此，在这些残差中，$2^n$处分离的所有可能的残差都出现一次。此外，让$m$是第二组中的一个数。让我们在第一组中找到数字$k_1 \cdot 5^n, k_2 \cdot 5^n, k_3 \cdot 5^n$和$k_4 \cdot 5^n$，它们除以$2^n$时得到与$2m, 2^{n-1}+2m, 2^n-2m$和$2^{n-1}-2m$相同的余数。那么 8 个数字 $m, 10^n-m, 0,5 \cdot 10^n \pm m, k_1 \cdot 5^n-m, k_3 \cdot 5^n+m$ 和 $k_4 \cdot 5^n+m$（它们写在页边空白处）的平方在 $n \geqslant 4$ 处具有相同的 $n$ 数字结尾。事实上，由于$0,25 \cdot 10^n$是整数（$n \geqslant 4$），$k_i$是偶数，并且页边空白中蓝色框中的数字可以被$2^n$整除，所以红色框中的所有数字都可以被$10^n$整除。因此，第二组的数类至少包含8个元素，因此它们的数量小于$0,5 \cdot 10^n/8$。类似地，对于$n \geqslant 4$，第三组的数类至少包含 16 个元素。 （每个类与数字$m$一起包含数字$10^n-m, 0,25 \cdot 10^n \pm m, 0,5 \cdot 10^n \pm m, 0,75 \cdot 10^n \pm m, k_1 \cdot 5^n-m, ..., k_4 \cdot 5^n-m, k_5 \cdot 5^n+m, ..., k_8 \cdot 5^n+m$，其中选择$k_1, ..., k_8$，以便数字$k_1 \cdot 5^n, ..., k_8 \cdot 5^n$除以$2^n$时，得到与数字$2^n, 2^{n-2}+2m, 2^{n-1}+2m, 3 \cdot 2^{n-2}+2m, 2^n-2m, 2^{n-1}-2m, 3 \cdot 2^{n-2}-2m$相同的余数。）因此，组（3）中的类数量小于$0,5 \cdot 10^n/16$，并且总数班级数量$A_n < 2^n + \frac{0,5 \cdot 10^n}{8} + \frac{0,5 \cdot 10^n}{16} = 10^n \left( \frac{1}{5^n} + \frac{1}{16} + \frac{1}{32} \right) \leqslant 10^n \left( \frac{3}{32} + \frac{1}{5^4} \right) = 0,9535 \cdot 10^{n-1} < 10^{n-1}$。

尝试搜索 $\lim_{n \to \infty} A_n/10^{n-1}$。

第二个证明。它比第一个短，但不太尊重。以下事实适用：

如果精确平方的倒数第二位是奇数，则最后一位是 6。

事实上，从等式$(10a+b)^2 = 100a^2 + 20ab + b^2$可以清楚地看出，任何数的平方倒数第二位与其最后一位数的平方倒数第二位具有相同的奇偶性。但在个位数的平方中，倒数第二位只有两种情况是奇数：$4^2 = 16$和$6^2 = 36$。

现在我们将证明一个精确的正方形不能以 005$b$ 结尾。确实，根据已经证明的，这样的平方一定是以0056结尾，那么除以16余数是8，这显然是不可能的（能被4整除的数的平方能被16整除，不能被4整除的数的平方不能被8整除）。

我们邀请读者更详细地独立研究$n=2$和3。证明 a) 对于任何数字 $a_1a_2$ 都存在一个以 $a_1a_2b$ 结尾的精确正方形； b) 当且仅当三位数 $a_1a_2a_3$ 除以 8 时得到的余数不等于 5 或​​ 7 时，精确平方可以以 $a_1a_2a_3b$ 结尾（带有新向量 $b$）。

让我们提出关于这个主题的另一个问题，由 D. Fedorov 发送给编辑：证明 $aa...ab$ 形式的数字，其中 $b=a+1$ 不能是精确的平方。

D·B·福克斯

◆ 首先假设红色线段彼此不相交，然后证明每个红色线段至少与一幅图像相交，即红蓝相交的数量不少于$k$。取任何红色段$AB$和它所包含的朋友之一。上面的红点数量是偶数（因为

⟦folio 48⟧

mi 线段和 2k 蓝色线段 - 到蓝色线段（没有三个线段在一点相交）。证明红色线段与蓝色线段至少有 k 个交点。

图 1.

图 2.

F808。一艘摩托艇位于距离湖岸距离为R的A点，开始转弯，以速度v=18公里/小时，沿着半径为r=R/2的圆行驶；在初始时刻，船的速度指向岸边。在转弯开始后 t=3 分钟时从船上向岸边挥手。波浪从船上沿水面传播的速度为 u=9 km/h。求距离 R。

F809。一个圆柱形罐子充满了密度为 q 的液体。罐体顶部用半径为 R 的盖子紧密封闭。罐体底部有一个面积为 s 的孔，用质量为 m 的塞子封闭（参见 图）。

它们中的任何一个都必须通过线段连接到同一弧上的一点），因此，该弧上的蓝色点的数量是奇数。因此，从其开始的蓝色线段之一必须与 AB 相交。

Telery 将表明，任何红色和蓝色线段的系统都可以被“解开”——用一种新的系统取代，其中红色线段不成对相交，而不会增加红蓝相交的数量。设 AC 和 BD 为相交的红色线段。让我们将它们替换为红色线段 AB 和 CD (图 1)。很明显，与线段 AB 或线段 CD 相交的任何线段（红色或蓝色）与 AC 和 BD 具有相同数量的共同交点。因此，替换时，红蓝相交的数量并没有增加，但红蓝相交的数量至少减少了1。经过几次这样的操作，我们得到了一个红色线段不成对相交的线段系统，并且红蓝相交的数量不超过原来的数量，同时正如一开始所证明的，不小于k。

构建具有 k 个红蓝交叉点 (图 2) 的线段系统示例很容易。

S.V.福明

◆ 将船视为波浪源，从船轨迹的每个点传播，我们会找到波浪到达岸边的 C 点。 C点的位置由波浪传播速度与船速在“向岸”方向（X轴图）的投影相等的条件确定：

$$u = v_x = v \sin \alpha \Rightarrow \sin \alpha = u/v = 1/2,$$

即$\alpha = 30^\circ$。从C点到岸边的考虑是

$$l = R - r \cos \alpha = R - \frac{R}{2} \cos \alpha = R \left( 1 - \frac{1}{2} \cos \alpha \right).$$

波浪从 C 点传播到岸边所需的时间 t₁ 为

$$t_1 = l/u = \frac{R}{u} \left( 1 - \frac{1}{2} \cos \alpha \right).$$

船从 A 点到 C 点所需时间 t2 为

$$t_2 = \frac{2\pi r}{v} \cdot \frac{60^\circ}{360^\circ} = \frac{\pi R}{6v}.$$

转弯开始后，波浪到达岸边的总时间等于

$$t = t_1 + t_2 = \frac{R}{u} \left( 1 - \frac{1}{2} \cos \alpha \right) + \frac{\pi R}{6v}.$$

从这里我们找到从A点到海岸的R：

$$R = \frac{6tuv}{3v (2 - \cos \alpha) + \pi u} \approx 545 \text{ м.}$$

A.I.布兹丁

◆ 同一深度的旋转罐中液体的压力在容器中心和壁处会有所不同——压力随着远离中心而增加。让我们看看墙壁上的压力与中心的压力有多少差异。

让我们在心里选择一个横截面积为 σ 的水平细液柱（参见 图）。

⟦folio 49⟧

要将塞子从水箱中拔出，需要施加力 f。水箱可以以多大的最大角速度绕垂直轴旋转而不使塞子被抛出？

该工作台的质心沿半径为 $R/2$ 的圆移动。让我们写出凳子的运动方程：

$$\varrho R \omega^2 \frac{R}{2} = \Delta p \cdot \sigma$$

（$\varrho R \sigma$是斯托尔尼克的质量，$\Delta p \cdot \sigma$是作用在斯托尔尼克右侧和左侧的压力的结果）。因此，壁上流体的压力大于顶部中心的压力

$$\Delta p = \frac{1}{2} \varrho \omega^2 R^2.$$

对于波斯尼来说，从液体一侧作用在塞子上的力等于

$$F = s \left( p_0 + \varrho g H + \frac{1}{2} \varrho \omega^2 R^2 \right),$$

其中$p_0$是大气压力，$H$是罐的高度。

让我们写出交通拥堵的方程：

$$m \omega^2 R = p_0 s + F_{\text{тр}} - s \left( p_0 + \varrho g H + \frac{1}{2} \varrho \omega^2 R^2 \right).$$

由条件可知，塞子在$F_{\text{тр}} = f + s \varrho g H$处飞出油箱。考虑到这一点，我们找到插头飞出的旋转角速度：

$$\omega = \sqrt{\frac{f}{m R + \frac{1}{2} s \varrho R^2}}.$$

科莫夫

F810。有一个工作温度$t_H = 700^\circ\text{C}$的刀具。环境温度 - $t_0 = 20^\circ\text{C}$。必须从刀具中带走多少热量才能蒸发 $m = 3$ kkw。水，切到沸点（$t_1 = 100^\circ\text{C}$）？切削水比温度$r = 2,26$MJ/kg。

当直接将加热器的热量传递给水时，为了蒸发大量的水$m$，需要从加热器接收热量$Q_0 = mr$。

让我们尝试利用以下事实来降低该值：如果温差不是 VELK，热泵（即以逆循环方式运行的热机）可以以较低的机械能成本将大量热能从冷体泵送到热体。

让我们想象一个用于蒸发水的设备，由理想热机$M$和理想热泵$H$组成，按图1所示打开。机器从加热器获取热量$Q_1$，并将热量$Q_2$传递给热水，同时做功$A$。热泵$H$，使用功$A$，从环境中获取热量$Q_3$，并将热量$Q_4$传递给热水。

我们来计算一下总热量$Q_2 + Q_4$，我们得到了水。机器的效率系数$M$等于

$$\eta = \frac{A}{Q_1} = \frac{T_H - T_1}{T_H}.$$

从这里

$$A = Q_1 \frac{T_H - T_1}{T_H}, \quad Q_2 = Q_1 \frac{T_1}{T_H}.$$

由于热泵$H$是一个逆循环运行的理想热机，我们可以用类似的方式来写它

$$\frac{A}{Q_4} = \frac{T_1 - T_0}{T_1} \Rightarrow Q_4 = A \frac{T_1}{T_1 - T_0} = Q_1 \frac{(T_H - T_1) T_1}{T_H (T_1 - T_0)}.$$

因此，

$$Q_2 + Q_4 = Q_1 \frac{T_1}{T_H} \frac{T_H - T_0}{T_1 - T_0}.$$

⟦folio 50⟧

为了蒸发水，传递给水的总热量必须等于$Q_2 + Q_4 = Q_0$。因此，机器M必须从加热器获取热量

$$Q_1 = Q_0 \frac{T_H(T_1 - T_0)}{T_1(T_H - T_0)} \approx 0.31 \text{ mr.}$$

因此，当使用理想的热泵（冰箱）$Q_1$时，蒸发水所需的热量显着减少。

根据热泵效率公式可知，在$\frac{T_1 - T_0}{T_1} \ll 1$时，可以利用环境的热能（用于蒸发、加热等），同时消耗少量的机械能、电能或任何其他非物质能。然而，在实践中，热泵（冰箱）还远未达到理想状态，其作为加热元件的应用尚未广泛普及。

有趣的是，如果机器 M 在热量和环境 (图 2) 之间运行，就会出现结果 (*)。

O·S·拉宾诺维奇

F811。在半波整流器的一般电路中（图1）$C = 1000$μF，$R = 500$欧姆。网络频率$v = 50$赫兹。假设二极管是理想的，求：
1) 电阻$R$上的电压纹波系数$k = \frac{\Delta U}{U}$的大小；
2) 如果在电阻上串联一个电感$L = 100$ Hz，系数$k$会减少多少倍？

图 1.

图 2.

1) 在选定的参数$C$和$R$下，电容器的电荷变化很小，因此电容器的放电电流可以认为是恒定的。然后

$$\Delta U = \frac{\Delta q}{C} = \frac{I \cdot \Delta t}{C} = \frac{U \cdot \Delta t}{RC}.$$

方法，

$$k = \frac{\Delta U}{U} = \frac{\Delta t}{RC}.$$

如果电容器放电一点，则在网络正电压最大时刻（图2）再充电，即

$$\Delta t = T = \frac{1}{v}.$$

因此，

$$k = \frac{1}{vRC} = 0.04.$$

2) 当连接电感器时，纹波系数会变得更小（大电感：$2\pi vL \gg R$）。负载电流更可以被认为是恒定的；这意味着根据与第一种情况相同的规律，电容器上的电压将较小。在这种情况下，线圈上的电压几乎会补偿电容器上电压的变化。根据抛物线定律，在网络周期内通过线圈的电流会较小（根据线性定律感应电动势），并且最大电流值将在周期的中间：

$$\mathcal{E} = \frac{\Delta U}{T} t \quad (\text{при } t \in [nT, (n+1)T])$$

$$I = l_0 - \frac{\Delta U}{T} \frac{1}{L} \frac{1}{2} t^2.$$

这种情况下的纹波由电流的变化决定：$\Delta U_1 = R \cdot \Delta I$。自从

$$\Delta I = I_{\max} - I_{\min} = \frac{1}{2} \frac{\Delta U}{LT} \frac{T^2}{4} = \frac{1}{8} \frac{UT^2}{LRC}$$

($\Delta U = \frac{UT}{RC}$)，我们最终得到：
