---
id: 1973-5-borovinskiy-zadachi-na-maksimum-i-minimum-bff64bd0
issue: kvant_1973_5
year: 1973
number: "5"
title: 最大和最小任务
authors:
  - Боровинский Л. А.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 48
page_labels: 43-46
tag: FJJE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b96c1830cdc3f01ecf6d9ce87482d89f7a389836a8bfd52227804e1d0f171ecd
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/11_borovinskiy-zadachi-na-maksimum-i-minimum-bff64bd0.md
source_content_sha256: 4dd016b9b5620eca9e1a00d477111249e11e80368e47b408361ad4ce1132b45f
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

任务
最大限度地
和最小值

在日常生活中，在实际问题和科学问题中，经常需要确定什么条件，在确定条件时我们才能获得最多的结果。相反，在其他情况下，有必要知道在什么条件下可以用最少的努力或时间实现目标。这样的条件称为最佳条件。

通常，我们甚至在没有注意到的情况下，利用生活经验和独创性来解决问题以确定最佳条件。然而，兴趣和生活经历可能会产生误导或不准确。充其量，他们会告诉我们提供良好但不是最好结果的条件。为了有效地找到最佳条件，就必须借助武器——数学。

许多物理定律都可以形成一些极端原理，即对某些物理量的极值（最大值或最小值）的要求。例如，我们知道，机械系统的平衡状态可以通过系统势能的极值来求得，在稳定平衡状态下，势能最小，在不稳定平衡状态下，势能最大。任何熟悉费马原理的人，根据该原理，他总是沿着一条需要最少时间的路径跟踪两点，所有几何光学定律都可以从该原理中得出。

人类控制过程的最佳条件与自然生产过程的最佳条件之间存在显着差异。在第一种情况下，最佳条件决定了最有利可图的过程，但不是唯一可能的过程。在第二种情况下，自然法则适用范围内的极值条件决定了该过程的唯一可能或最可能的过程。

涉及确定最佳或极端条件的复杂问题可以使用微分学、表达微积分或线性规划的理论来解决。

然而，有许多确定函数极值的简单问题可以在不使用复杂数学理论的情况下解决。要求解它们，您只需要知道函数元素的属性（例如，二次三项函数或三角函数）。您还可以使用众所周知的理论：

n个正数的几何平均值不大于其算术平均值，即

$$\sqrt[n]{x_1 \cdot x_2 \cdot \cdots \cdot x_n} \leq \frac{x_1 + x_2 + \cdots + x_n}{n},$$

等号出现 moeda 和 molko moeda, koeda

$$x_1 = x_2 = \cdots = x_n.$$

让我们考虑几个具体任务。

问题 1. 来自摩卡源的杂交功率的电子回归装置，例如。 d. c.它等于E，内阻和电源线的电阻加起来为r。设备应具有多大的电阻 R 才能产生最大功率？

⟦folio 44⟧

根据欧姆定律，对于完整电路，电流等于

$$I = \frac{E}{R + r},$$

根据焦耳-楞次定律，分配给电阻$R$的功率等于

$$P = I^2R = \frac{E^2R}{(R + r)^2} = \frac{E^2}{R + 2r + \frac{r^2}{R}}.$$

当$R (R \ll r)$小时，有用功率也小，因为几乎所有从电源获取的功率都在电源线和电源中释放。如果$R$很大（$R \gg r$），则有用功率又很小，因为电路中的电流很小。因此，存在某个值$R$，在该值下有用功率将最大。

考虑表达式

$$R + 2r + \frac{r^2}{R} = 2r + \left(R + \frac{r^2}{R}\right).$$

显然，当该表达式最小时，有用功率达到最大值。给定值$2r$，括号中的$R$和$\frac{r^2}{R}$的乘积不依赖于$R$和常数，因此，根据上述定理，当$R = \frac{r^2}{R}$时，将达到该值的最小值，即$R = r$。

有用功率的最小值等于

$$P_{\max} = \frac{E^2r}{4r^2} = \frac{E^2}{4r}.$$

请注意，在这种情况下，c.p. d.来源仅占50%。因此，建议仅在短时间内从电源获得最大功率，例如当启动器自动运行时。为了更有效地利用电流源的能量储备，电阻$R$必须明显大于$r$。在这种情况下，有用功率将小于最大功率。

同时，但目的是什么？ d.将大于100%。一探究竟。

问题 2. 负载雪橇在施加到柔软中心的力 $F$ 的影响下沿着表面的水平线移动。使雪橇在最小力的作用下发生匀速运动的力$F$的作用线与地平线的长度是多少？雪橇与雪之间的摩擦系数为$k$。

让我们将力 $F$ 分解为水平和垂直分量 $F_x$ 和 $F_y$ (图 1)。雪橇在雪上的法向压力等于雪橇的重量与力的垂直分力$F$之差：

$$N = P - F \sin \alpha. \tag{1}$$

因此摩擦力

$$F_{\tau p} = kN = k(P - F \sin \alpha). \tag{2}$$

雪橇在受到水平力补偿的情况下匀速运动：$F_x = F_{\tau p}$，即

$$F \cos \alpha = k(P - F \sin \alpha). \tag{3}$$

从这里我们可以找到力 $F$ 作为角度 $\alpha$ 的函数：

$$F = \frac{kP}{k \sin \alpha + \cos \alpha}. \tag{4}$$

显然，在式（4）中的值最大的角度$\alpha$值处，力$F$最小。为了确定这个角度，我们对表达式（4）的值进行变换，使得

⟦folio 45⟧

它只包含一个角 $\alpha$ 的三角函数。为此，我们将摩擦系数 $k$ 想象为某个角度 $\varphi$ 的正切：

$$\text{tg} \varphi = k; \quad \varphi = \arctg k;$$

$$\sin \varphi = \frac{k}{\sqrt{1+k^2}}; \quad \cos \varphi = \frac{1}{\sqrt{1+k^2}}.$$

由于给出了$k$，因此可以认为角度$\varphi$是已知的。将 (4) 中的 tg $\varphi$ 代替 $k$ 代入，并将分子和分母乘以 cos $\varphi$，我们得到

$$F = \frac{P \text{tg} \varphi}{\text{tg} \varphi \sin \alpha + \cos \alpha} =$$

$$= \frac{P \sin \varphi}{\sin \varphi \sin \alpha + \cos \alpha \cos \alpha} = \frac{P \sin \varphi}{\cos (\alpha - \varphi)} =$$

$$= \frac{P k}{\sqrt{1+k^2} \cos (\alpha - \varphi)}.$$

现在很明显，当$\cos (\alpha - \varphi) = 1$时，力$F$最小，即

$$\alpha_{\min} = \varphi = \arctg k.$$

在这种情况下，力$F$的最小值等于

$$F_{\min} = \frac{k P}{\sqrt{1+k^2}}.$$

从这个问题的解决方案我们可以得出一个实际的结论：当需要在摩擦系数较高的道路上（例如，如果道路是沙地）提升雪橇上的负载时，需要将雪橇拉得尽可能短。如果摩擦系数小，螺杆就应该长。解释一下这一点。问题3. 点1和点2沿轴$x$和$y$移动到坐标原点（图2）。在$t_0 = 0$幂1时刻距离$s_1 = 10$cm，

![Рис. 2.](image)

图 3.

⟦folio 46⟧

向垂直 BC 的底部移动，然后向浮标游去。以最快速度到达浮标 B 的人获胜。对于一个排序员来说，从岸边的哪个点开始游到浮标最方便，他知道沿着沙滩游泳时他的速度是 13 公里/小时，而他的游泳速度是 5 公里/小时。

令$x$为从C点到运动员开始游向浮标的位置的距离。然后，运动员跑动距离 $L - x$，并溢出距离 $\sqrt{l^2 + x^2}$。从起点 A 到浮标 B 的总行程时间为

$$t = \frac{L - x}{v_1} + \frac{\sqrt{l^2 + x^2}}{v_2}.$$

让线段$x$的长度增加少量$\Delta x$。那么运动时间变得相等

$$t' = \frac{L - (x + \Delta x)}{v_1} + \frac{\sqrt{l^2 + (x + \Delta x)^2}}{v_2}.$$

时间的变化是

$$\Delta t = t' - t = -\frac{\Delta x}{v_1} + \frac{\sqrt{l^2 + (x + \Delta x)^2} - \sqrt{l^2 + x^2}}{v_2} = -\frac{\Delta x}{v_1} + \frac{l^2 + (x + \Delta x)^2 - l^2 - x^2}{v_2[\sqrt{l^2 + (x + \Delta x)^2} + \sqrt{l^2 + x^2}]} = \left\{ \frac{2x + \Delta x}{v_2[\sqrt{l^2 + (x + \Delta x)^2} + \sqrt{l^2 + x^2}]} - \frac{1}{v_1} \right\} \Delta x.$$

图 4.

从$\Delta x \ll x$开始，$\Delta t$的表达式可能会睡过头。然后

$$\Delta t \approx \left\{ \frac{x}{v_2 \sqrt{l^2 + x^2}} - \frac{1}{v_1} \right\} \Delta x.$$

因为$\Delta x > 0$，$\Delta t$的符号与大括号中的表达式的符号匹配。

对于小$x$（$x \to 0$），大括号中的表达式为负，这意味着$t$随着$x$的增加而杀死。当$x \gg l$时，大括号中的表达式为正，时间随着$x$的增加而增加。由于函数$\Delta t$随着$x$的增加而连续变化，因此存在一个值$x_m$，在该值$\Delta t$变为零，即$t$随着$x$的增加而减少被$t$的增加所取代。该值为 $x_m$，对应最短时间 $t$。

所以，

$$\frac{x_m}{v_2 \sqrt{x_m^2 + l^2}} - \frac{1}{v_1} = 0,$$

在哪里

$$x_m = l \frac{v_2}{\sqrt{v_1^2 - v_2^2}}.$$

将所有量的数值代入，我们得到$x_m = 50$ m。

解决方案中未使用长度$L$。但是，有必要了解一下。想想为什么？

战斗

1. 有许多斜面，它们的底相同，等于$b$，但高不同。在什么高度$h$，物体在没有摩擦力的情况下从斜面滑下的时间最短？

2. 跳板的顶点位于距地面高度$H$处，在高度$h$处形成跳板（图4）。在给定高度$H$下，高度$h$应该是多少，以便滑雪者离开跳板后可以飞行最大距离$S$（水平计数）？

忽略空气和空气阻力。
