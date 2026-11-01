---
id: 1979-4-mozhaev-dvizhenie-zaryazhennyih-chastits-v-elektricheskom-i-magnitnom-polyah-8dc9ecef
issue: kvant_1979_4
year: 1979
number: "4"
title: 带电粒子在电场和磁场中的运动
authors:
  - Можаев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 49
page_labels: 43-47
tag: DFXV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 85a499bae13be66ed863b52c90abb1c4bd42238ab0abc13e29b3ee478a4983b3
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/16_mozhaev-dvizhenie-zaryazhennyih-chastits-v-elektricheskom-i-magnitnom-polyah-8dc9ecef.md
source_content_sha256: b099ccb3584d63e0217f7691f835f87f1448889faa84161e18493e53d68c117c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

带电粒子在电场和磁场中的运动

电场和磁场对带电粒子的作用会导致许多有趣的现象，并广泛应用于现代技术中。例如，控制各种电真空装置中的电子运动、将带电粒子加速到高能、使用静电线和磁力线聚焦粒子，以及根据质谱仪中粒子的远距离电荷来分离粒子。

让我们只考虑最简单的情况 - 带电粒子在均匀且静止（与时间无关）的电场和磁场中的运动。

在方向为$\vec{E}$的电场中，电荷为$q$、质量为$m$的粒子受到电力的作用

$$\vec{F}_{\text{эл}} = q\vec{E},$$

它赋予粒子加速度

$$\vec{a} = \frac{\vec{F}_{\text{эл}}}{m} = \frac{q}{m}\vec{E}.$$

如果$q > 0$，则该加速度沿场方向；如果$q < 0$，则该加速度沿场方向。因此，粒子的正部分开始沿场均匀移动，而负部分开始逆场移动。

让一个粒子从势为 $\varphi_1$ 的点移动到势为 $\varphi_2$ 的点。与此同时，它的动能改变了

$$\Delta W_{\kappa} = -q(\varphi_2 - \varphi_1).$$

这就是为什么可以方便地改变以电子伏为单位的带电粒子的能量（1 eV 是电荷等于电子电荷的粒子在通过 1 伏电势差时获得的能量）。

磁场中移动的带电粒子受到称为洛伦兹力 $\vec{F}_{\pi}$ 的磁力的作用。她的模特

$$|\vec{F}_{\pi}| = q|\vec{v}||\vec{B}| \sin \alpha,$$

其中$q$是粒子的电荷，$\vec{v}$是粒子的速度，$\vec{B}$是磁场感应，$\alpha$是矢量$\vec{v}$和$\vec{B}$之间的角度。该力的一个特征是它始终垂直于粒子的方向运动和磁场的感应。

由于洛伦兹力垂直于粒子的速度，因此该力所做的功为零。因此，如果没有其他力作用在粒子上，当粒子在磁场中运动时，粒子的能量将保持恒定*)。

让我们考虑几个具体任务。

任务 1. 带负电的粒子在均匀电场中运动，使其与电势为 $\varphi_1$ 的等效表面以与法线成 $\alpha_1$ 的角度相交，并与电势为 $\varphi_2$ 的等效表面以$\alpha_2$ (图 1) 的角度相交。众所周知，在场势为零的点，粒子速度为零。找出角 $\alpha_1$ 和 $\alpha_2$ 之间的连接。

如果在势能为零的点，粒子的动能等于 0，则在点 1 和 2

*) 您可以在 Yu 的文章中阅读更多相关内容。扎伊奇科夫“洛伦兹力及其作用”（«Kvant»，1979 年，第 2 期）。

⟦folio 44⟧

图 1.

它将等于对应关系

$$\frac{m \left| \vec{v}_1 \right|^2}{2} = -q\varphi_1$$

和

$$\frac{m \left| \vec{v}_2 \right|^2}{2} = -q\varphi_2,$$

粒子速度比从何而来？

$$\frac{\left| \vec{v}_1 \right|}{\left| \vec{v}_2 \right|} = \sqrt{\frac{\varphi_1}{\varphi_2}}.$$

在$X$轴方向，电力作用在粒子上，因此速度$v_x$的投影将增加：$v_{x_2} > v_{x_1}$。 $Y$轴方向上没有力作用在粒子上；因此，速度投影 $v_y$ 将保持不变：

$$\left| \vec{v}_1 \right| \sin \alpha_1 = \left| \vec{v}_2 \right| \sin \alpha_2,$$

或者

$$\frac{\left| \vec{v}_1 \right|}{\left| \vec{v}_2 \right|} = \frac{\sin \alpha_2}{\sin \alpha_1}.$$

比较点 1 和 2 处粒子速度模型的两个表达式，我们发现鼻烟角 $\alpha_1$ 和 $\alpha_2$ 之间的联系：

$$\frac{\sin \alpha_1}{\sin \alpha_2} = \sqrt{\frac{\varphi_2}{\varphi_1}}.$$

请注意这个事实：如果（如我们所考虑的情况）粒子沿电势增加的方向移动，则粒子轨迹将沿等位面的法线方向偏离。这使得理解非均匀电场中电荷的更复杂运动成为可能，例如电系统聚焦的原理。 图2表示所谓的电气系统线路，由两个同轴圆柱体组成；虚线表示等位面的截面。点$O$是慢电子发散束的源，点$O'$是快电子会聚束的像。

任务 2. 我们将电子飞入扁平电容器板之间的空间，板之间保持放置的 $U=60$ V (图 3) 的恒定差异。确定到达顶板的最小电子速度$\vec{v}_{\min}$。电子的比电荷为$e/m=1,76 \cdot 10^{11}$ K/kg，密度为$\alpha=60^\circ$。

当在电容器中移动时，电子将受到指向电场的恒定电力，即从压印板到正极。因此，电子速度在$Y$轴上的投影将均匀减小，而在$X$轴上的投影将保持恒定。不难证明电子的运动轨迹将是一条抛物线（自己检查一下）。

电子的最小速度将对应于抛物线接触带有电容器的上板时的情况。

⟦folio 45⟧

托拉。这意味着在接触时刻，电子速度的投影$v_y$将等于零。

在点 1 处，电子的动能为 $\frac{m|\vec{v}_{\min}|^2}{2}$，在点 2 处，它等于 $\frac{mv_x^2}{2} = \frac{m(|\vec{v}_{\min}| \sin \alpha)^2}{2}$。另一方面，动能的变化与电容器板之间的电势差相关：$\Delta W_\kappa = -eU^*$)。因此，$\frac{m(|\vec{v}_{\min}| \sin \alpha)^2}{2} - \frac{m|\vec{v}_{\min}|^2}{2} = -eU$。

在哪里
$$|\vec{v}_{\min}| = \sqrt{2 \frac{e}{m} \frac{U}{1 - \sin^2 \alpha}} \approx 9,2 \cdot 10^6 \text{ m/c}.$$

尝试用另一种方式解决这个问题：写下电子沿$X$和$Y$轴的运动方程，并从中找到最小初始速度。

*)通过下文中的$e$我们将了解电子电荷模型。

图 3.

图 4.

问题3. 电磁计“E”发射出一堆单电荷正离子Li$^+$(A=6)。
非子被电场 $u$ 加速，穿过电势差 $U=3000$ V，并进入具有横向磁场 $|\vec{B}| = 3 \cdot 10^{-2}$ T (图 4) 的腔室。求出梁的挠度值$h$。腔室长度 $L=15$ cm，电子电荷 $e=1,6 \cdot 10^{-19}$ C，promon 质量 $m_p=1,67 \cdot 10^{-24}$ e。

经过加速势差$U$后，各自获得动能

$$\frac{m|\vec{v}|^2}{2} = eU,$$

其中 $m$ 是离子的质量，$\vec{v}$ 是离子的速度。从这里

$$|\vec{v}| = \sqrt{\frac{2eU}{m}}.$$

以这样的速度，他进入了一个只有磁场存在的房间。洛伦兹力开始作用于它，这将赋予它向心加速度。由于每个时刻的洛伦兹力垂直于离子的速度，因此它会做圆周运动。该圆的半径可以从离子的运动方程中找到

$$\frac{m|\vec{v}|^2}{R} = e|\vec{v}||\vec{B}|.$$

考虑到$|\vec{v}| = \sqrt{\frac{2eU}{m}}$，我们得到

$$R = \frac{m|\vec{v}|}{e|\vec{B}|} = \frac{1}{|\vec{B}|} \sqrt{\frac{2mU}{e}}.$$

梁偏转量$h$可通过简单的几何计算得出（参见图4）：

$$h = R - \sqrt{R^2 - L^2} \approx 0,02 \text{ м}.$$

问题 4. 弱发散电子束以速度 $v$ 离开点$O$，并在感应强度为 $\vec{B}$ (图 5) 的纵向磁场中移动。在磁感应模型的什么值下，光束将聚焦到距离点 $O$ $L$ 的屏幕“E”上？

⟦folio 46⟧

让我们考虑单个电子的运动，其速度矢量位于 图 5 平面内，并与矢量 $\vec{B}$ 形成角度 $\alpha$。

由于电子仅受到洛伦兹力的影响，洛伦兹力在场方向上的投影为零，因此电子速度在该方向上的投影将保持恒定，等于$|\vec{v}| \cos \alpha$。

在垂直于矢量$\vec{B}$的平面上，电子将以等于$|\vec{v}| \sin \alpha$的线速度做圆周运动。让我们写出电子在圆周上的运动方程：

$$\frac{m(|\vec{v}| \sin \alpha)^2}{R} = e |\vec{v}| |\vec{B}| \sin \alpha.$$

从这里我们可以找到圆的半径 $R$ 和旋转周期 $T$：

$$R = \frac{m |\vec{v}| \sin \alpha}{e |\vec{B}|},$$

$$T = \frac{2\pi R}{|\vec{v}| \sin \alpha} = \frac{2\pi m}{e |\vec{B}|}.$$

同时，电子以速度$|\vec{v}| \cos \alpha$均匀地穿过场。

如果在时间$\tau = \frac{L}{|\vec{v}| \cos \alpha}$之后，电子最终到达点$O'$（参见图5），这将意味着它已经完成了整数$n$整转：

$$\tau = nT,$$

或者

$$\frac{L}{|\vec{v}| \cos \alpha} = n \frac{2\pi m}{e |\vec{B}_n|},$$

其中$n=1, 2, 3, \ldots$。结果，我们获得了一组离散的磁感应矢量模型值，在该值处电子将达到点$O'$：

$$|\vec{B}_n| = \frac{2\pi m |\vec{v}| \cos \alpha}{e L} n.$$

严格来说，聚焦场的值取决于角度$\alpha$。然而，在小角度 $\cos \alpha \approx 1$ 和

$$|\vec{B}_n| \approx \frac{2\pi m |\vec{v}|}{e L} n.$$

问题 5. 正数

⟦folio 47⟧

它会逐渐失去速度并被磁场弯曲得越来越厉害（参见图6）。在轨迹的最低点，粒子$v_z$的速度投影为零，其总速度最小。此时轨迹的曲率半径最小，粒子向上的加速度最大。

然后粒子开始沿着场$\vec{E}$向上运动，其速度会增加，轨迹的曲率半径也会随之增加。在某些时刻，粒子速度变得等于初始速度$\vec{v}_0$。

结果，粒子将沿 $X$ 轴“漂移”。其运动轨迹是气旋。 图 6 显示了$\left|\vec{v}_0\right| > 2 \left|\vec{E}\right| / \left|\vec{B}\right|$ 情况下的粒子轨迹。

（严格的计算表明，沿旋风分离器的运动可以表示为沿$X$轴、速度为$\left|\vec{v}\right| = \frac{\left|\vec{E}\right|}{\left|\vec{B}\right|}$的匀速运动和在$XZ$平面上的圆周运动的叠加。）

练习

1. 两个带电粒子以相等的速度 $\left|\vec{v}\right| = 10^9$ cm/c 同时飞入扁平电容器 (图 7)。

确定粒子将在电容器电场 $\vec{E}$ 的哪个方向发生碰撞。粒子的比电荷绝对值相等$(e/m = 1,76.10^{11}$C/kg)，但符号相反。电容极板之间的距离为$d = 1$cm； $h = 5$厘米；粒子的入射角$\alpha = 45^\circ$。

2. 在氢原子的行星模型（根据卢瑟福-玻尔）中，假设电子围绕一个小而重的带正电的原子核（质子）在圆形轨道上旋转。如果已知必须额外给予电子以将其从原子中移除（能量电离）的最小能量等于 $W = 2,2.10^{-18}$ J，则确定氢原子的半径。电子和质子的电荷等于 $e = 1,6.10^{-19}$ Cl。

3. 在确定同位素状态的装置（质谱仪）中，原子量为 $A_1 = 39$ 和 $A_2 = 41$ 的单电荷钾离子首先受到电加速
