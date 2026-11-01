---
id: 1984-1-resheniya-zadach-m826-m830-f837-f841-d49c88d3
issue: kvant_1984_1
year: 1984
number: "1"
title: 问题解决方案M826—M830； F837—F841
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 47
page_last: 53
page_labels: 45-51
tag: K6I8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 16dde53117085b1844ca7766d2444e11de4e33e398513d786785eb213ff27166
prompt_sha256: draft-1
translated_from: content/ru/1984/01/articles/15_resheniya-zadach-m826-m830-f837-f841-d49c88d3.md
source_content_sha256: d41f615c70b9a8c3a3830c238cf50a9f1c864ec76e737a214e99802a7f1767a6
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

and supply them with reasonable numerical values yourself and obtain a numerical answer.

E. I. Palchikov

P855. A charged plate is introduced all the way between the plates of a flat capacitor parallel to them at a distance $b$ from one of the plates (see figure Pisc. 4). The capacitor is connected to the poles of a battery of EMF $6$. Find the force acting on the charged plate if its charge is $q$. The weight of the plate is negligible. The area of the plates is $S$, the distance between them is $d$.

V. P. Borodin, A. P. Ershov

P856. Direct current circulates through a heating spiral of constant resistance. What will be the percentage change in the mean amount of heat emitted by the spiral per second if an alternative (sinusoidal) current, whose amplitude is 10% of the direct current’s value, is also sent through the spiral?

V. G. Dudnikov

P857. A shiny can has a dent which reflects light on a screen. A cooled liquid is poured into the can. The reflected signal noticeably weakens. Explain this phenomenon.

V. G. Dudnikov

问题解决方案

M826—M830; F837—F841

答案：a) 不，6) 是。我们首先要注意的是，如果原始数字是 2, 2, 2 或 3, 3, 3，或者通常任何大于 1 的数字，那么所有后续数字都将大于 1，并且每个新三元组中的最大数字始终比其他两个数字之和小 1。此消息允许您使用最后三个数字来恢复之前的所有数字（第一个数字除外）。

事实上，让$a, b, c$在三元组中来定义$a \leq b \leq c$。那么$c = a + b - 1$和前一个三元组的形式为$a, b, x$。其中最大的数字可以认为是$b$（如果$x > b$，则$x = a + b - 1 = c$）。但随后$b = a + x - 1$。因此，由三元组$a, b, b - a + 1$得到带有$a \leq b \leq c$的三元组$a, b, c$。

使用此规则，我们将从末尾开始恢复板上的所有条目：

(17, 1967, 1983) $\leftarrow$ (17, 1967, 1951) $\leftarrow$ (17, 1935, 1951) $\leftarrow$ ... $\leftarrow$ (17, 15, 31) $\leftarrow$ (17, 15, 3) $\leftarrow$ (13, 15, 3) $\leftarrow$ ... $\leftarrow$ (5, 7, 3) $\leftarrow$ (5, 3, 3).

根据我们的规则，三元组 5, 3, 3 之前必须有包含 1 的三元组 1, 3, 3，这是不可能的。因此，5,3,3就是第一步得到的三元组。 （显然，剩下的三元组不可能在第一步中产生。）显然，三元组5,3,3可以从3,3,3得到，但不能从2,2,2得到。

A·贝尔津斯

M827。已知图1上的四个同步的大小相等。
a) 证明这个图上的三个红色四层也同样大小。

我们需要以下应用程序部分：

引理。令 $P$ 为三角形 KLM 边 KL 上的一点。那么三角形 MKP 和 MPL 的面积之比等于

$$S_{MKP} : S_{MPL} = |KP| : |PL|.$$

（为了证明这一点，只要知道

⟦folio 46⟧

6) 如果一个蓝色三角形的面积为 1，则求一个四边形的面积。

图 1.

图 2.

图 3.

M828*。在无限张方格纸的单元格中，是否有可能使得每个边长沿网格线、大小为 4 × 6 单元格的矩形中的数字之和等于 a) 10； b）1？

a) 让我们介绍一下图 1 中的表示法。请注意，三角形$A_0C_0$ 和$AA_0C_1$ 的大小相等（它们每个都由三角形$AA_0B_0$ 和其中一个同步三角形组成）。这些三角形有一个共同底$AA_0$，因此它们的顶点$C_0$和$C_1$等于直线$AA_0$，即直线$AA_0$和$C_1C_0$平行。同样，$BB_0 \parallel A_1A_0$和$CC_0 \parallel B_1B_0$。我们来看看梯形 $AA_0C_0C_1$ (图 3)。它的对角线相交于点 $B_0$，边的延续相交于点 $B$。这些点位于连接其底边 $AA_0$ 和 $C_1C_0$ 的中点 $D$ 和 $E$ 的线上。 （事实上，$B_0$是三角形$B_0AA_0$和$B_0C_0C_1$的同位中心，$B$是三角形$BAA_0$和$BC_1C_0$的同位中心。）并且由于这条线平行于$A_1A_0$，点$B_0$是线段的中点$A_1A$。由引理可知$S_{AB_0C_0} = S_{B_0A_1C}$。因此（参见图 1），四边形$AB_0A_0B_1$和$CA_0C_0A_1$的面积相等。类似地证明第三个红色四边形$BC_0B_0C_1$具有相同的面积。

考虑一下如果您只需要三个角度同步三角形的面积相等，那么问题的这一点的陈述是否仍然成立。

6) 答案：红色四边形的面积$s = 1 + \sqrt{5}$。为了创建一个求原始面积 s 的方程，我们使用引理以两种方式表达关系 $|BC_1|:|C_1A|$：

$$|BC_1|:|C_1A| = S_{CBC_1}:S_{CC_1A} = (2s+2):(s+2) = S_{B_0BC_1}:S_{B_0C_1A} = (s/2):1.$$

（这里的解释只需要相等$S_{B_0BC_1} = s/2$。如上所示，点$E$是$C_0C_1$（图3）的中点。从这里，再次使用引理，很容易推导出三角形$B_0BC_1$和$B_0BC_0$大小相等。它们一起形成四边形$BC_0B_0C_1$面积 s)。所以 s 满足方程：

$$s^2 - 2s - 4 = 0,$$

从哪里$s = 1 + \sqrt{5}$。

B. I. Chinik、V. N. 杜布罗夫斯基

◆

答案：a)、6)可能。在这两种情况下，可以通过组合两个更简单的布置来获得期望的布置。

a) 让我们将 1 放在网格的平行对角线上，彼此间隔 4 个单元格（水平或垂直），然后将 0 放在剩余的单元格中 (图 1, a)。那么每个矩形$4 \times 6$中的数字之和将等于6。这是第一种排列。第二个以同样的方式排列，但其中带单位的对角线之间的距离是 6 个单元格（图 1, 6）；对于它，任何矩形$4 \times 6$中的数字之和等于4。现在让我们将一种排列叠加到另一种排列上，并将落入一个单元格的数字相加；非常印度，对于最终排列，数字之和被认为等于 10。

6) 让我们采取与 a) 点相同的排列，但在对角线上以及单位 - 6 个单元格 (图 1, 6)；任意矩形$4 \times 6$中的数字之和将等于4。现在让我们将一种排列叠加到另一种排列上，并将落入一个单元格的数字相加；非常印度，对于最终排列，数字之和被认为等于 10。

我们邀请读者使用相同的想法来证明以下一般性陈述：在无限平面晶格的单元中，整数可以以这样的方式排列，使得给定维度的任何矩形中的数字之和具有相同的给定值。对于

⟦folio 47⟧

M829。证明对于任意 2m+1 个模数不超过 2m−1 的不同整数，有 3 个数字的和等于 0。

让我们通过对 m 的归纳来证明问题的陈述。
当m=1时，这是显而易见的（满足条件的创造性三元组是0、1和-1）。
假设它已针对 2m−1 个数字得到证明，并考虑模数不超过 2m−1 的任何 2m+1 个数字的集合 A。如果它包含 2m−1 个数字，其模数不超过 2m−3，则该陈述来自归纳假设。否则，集合 A 至少包含数 ±(2m−2) 和 ±(2m−1) 中的三个。如有必要，通过更改 A 中所有数字的符号，可以确保这些数字是 2m−1、2m−2 以及 −2m+1（第一种情况）或 −2m+2（第二种情况）。

第一个案例。让我们将所有从 1 到 2m−2 的数字分成加起来为 2m−1 的对：(1, 2m−2), (2, 2m−4), ..., (m−1, m)，并将从 0 到 −2m+1 的数字分成加起来为 −2m+1 的对：(0, −2m+1), ..., (−m+1, −m)。结果是 2m−1 个对，包含集合 A 中除 2m−1 之外的所有 2m 个数字。因此，虽然集合A中包含一对，但其组成数加起来为c -2m+1 或c 2m-1 至0。

第二个案例。现在让我们考虑 m−2 对 (1, 2m−3), (2, 2m−4), ..., (m−2, m) 与数字 2m−2 之和，以及 m 对 (0, −2m+1), ..., (−m+1, −m) 与数字 −2m+1 之和。这些 2m−2 对包含集合 A 中除 2m−1、2m−2 和 m−1 之外的所有数，即来自 A 的 2m−1 个数。因此，其中一个再次进入集合 A 并给出零和 c −2m+2 或 2m−1。

N·V·卡尔塔佐夫

M830*。学生练习求解二次方程。写出一些方程 x²+p₁x+q₁=0 后，他求解 u，确保它有两个根，组成第二个方程 x²+p2x+q2=0，其中 p2 是第一个方程的较小根，q2 是第一个方程的较大根。如果可能的话，他从第二个方程得出第三个方程，等等。

a) 证明这个练习不能无限期地继续下去。
b) 找到满足方程的二次三项式的最长有限序列。

a) 解决方案基于研究方程系数的符号。设 fₙ(x)=x2+pₙx+qₙ=0 为所考虑序列中的第 3 个方程。让我们证明以下说法：
如果 n≥3 并且方程 fₙ(x)=0 不是最后一个，则数 pₙ 和 qₙ 要么都是正数，要么都是负数。
使用 Vieta，我们用 pₙ 和 qₙ 来表示二次三项式 fₙ−1(x) 的系数。
$$p_{n−1} = -(p_n + q_n), q_{n−1} = p_n q_n.$$

由条件 pₙ<qₙ и pₙ−1<qₙ−1, то есть −(pₙ+qₙ) < <pₙqₙ или qₙ> −pₙ(1+qₙ)。将三项式 fₙx 的正判别式方程添加到这些不等式中，我们得到系统
$$q_n > p_n$$
$$q_n > -p_n(1+q_n)$$
$$4q_n < p_n^2,$$

这是在页边以图形方式解决的。我们的声明立即从图表中得出。 （不过，从代数上证明它并不困难：pₙ≥0≥qₙ的情况是不可能的（qₙ>pₙ）；如果pₙ≤0≤qₙ，则从（2）和（3）我们得到qₙ²>pₙ²（1+qₙ）²>4qₙ（1+qₙ）²或4qₙ³+7qₙ²+4qₙ<0，对于qₙ≥0也是不可能的）。

⟦folio 48⟧

现在让我们假设序列中的方程数量至少为五个。如果方程 $f_5(x) = 0$ 不是最后一个，那么从已证明的陈述和对应关系 (1) 可以看出，只有两种情况是可能的：要么$0 < p_5 < q_5$然后$p_4 < 0 < q_4$，或者$p_5 < q_5 < 0$然后$0 < p_4 < q_4$，然后$p_3 < 0 < q_3$。这两者都与我们的说法相矛盾。因此，所讨论的方程序列将始终被声明，并且不晚于第五步。

6) 答案：二次三项式的最长序列是 5。

从问题 a) 的解可以清楚地看出，根据所示定律不可能组成超过五分之一的方程。下面的例子表明存在一个长度为5的序列（从尾部开始写——按照使用公式（1）构造它更方便的顺序）：$f_5(x) = x^2 - \frac{1}{2}x + 4$，$f_4(x) = x^2 - \frac{7}{2}x - 2$，$f_3(x) = x^2 + \frac{11}{2}x + 7$，$f_2(x) = x^2 - \frac{25}{2}x + \frac{77}{2}$，$f_1(x) = x^2 - 26x - \frac{1925}{4}$。

M.V.萨皮尔

F837。为了改变零件的速度，使用了激光风速计，其中移动的粒子被方程的两个相交的激光系数照亮，这两个系数既不是所考虑序列中的第一个，也不是第二个，也不是最后一个。

F837。为了改变零件的速度，使用了激光风速计，其中移动的粒子被方程的两个相交的激光系数照亮，这两个系数既不是所考虑序列中的第一个，也不是第二个，也不是最后一个。

让我们选择坐标系$XOY$，如图2所示，对于坐标为$x$和$y$的任意点$a$，我们找到对应于我们的光束并到达该点的两个平面波的相位差$\Delta\varphi$。设坐标$x = 0$、$y = 0$处第一波的相位等于$\varphi_0$，即$\varphi_1(0, 0) = \varphi_0$。该波的前沿描绘在 图 2 直线 $N_{10}$ 上，穿过点 (0; 0)；通过点 (x; y) 的该波的前沿由直线 $N_1$ 表示。显然，该波对应的射线到达点(0; 0)和(x; y)的路径差$\Delta_1$等于直线$N_{10}$和$N_1$之间的距离，即等于线段$OB$。从简单的几何考虑来看，可以找到该段，从而找到 $\Delta_1$：

$$\Delta_1 = |OB| = x \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2}.$$

因此，$(x; y)$点的波相位等于$\varphi_1(x, y) = \varphi_0 - \frac{2\pi}{\lambda} (x \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2})$，

其中$\lambda$是波长。

同样，我们将第二束光对应的波的相位放在坐标$(d; 0)$等于$\Psi_0$的点上，即$\varphi_2(d, 0) = \Psi_0$（这里$d$是点$O$和$O'$之间的距离）。在图2处，通过点$(d; 0)$的第二波前沿由直线$N_{20}$描绘，通过点$(x; y)$的第二波前沿由直线$N_2$描绘。路径差$\Delta_2$等于线段$O'C$，即等于

$$\Delta_2 = |O'C| = (d - x) \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2}.$$

因此，第二波在$(x, y)$点的相位等于

⟦folio 49⟧

$$\varphi_2(x, y) = \Psi_0 - \frac{2\pi}{\lambda} \left( (d - x) \sin \frac{\alpha}{2} + y \cos \frac{\alpha}{2} \right).$$

$(x: y)$点两束光波之间的相位差$\Delta\varphi(x, y)$等于

$$\Delta\varphi(x, y) = \varphi_1(x, y) - \varphi_2(x, y) = \varphi_0 - \Psi_0 - \frac{2\pi}{\lambda} \left( 2x \sin \frac{\alpha}{2} - d \sin \frac{\alpha}{2} \right).$$

从$\Delta\varphi(x, y)$的结果表达式可以看出，两束光束的波之间的相移仅取决于坐标$x$。令两束波的振幅相等且等于$A$。光束相交区域的光强分布将具有形式 $I(x) = 2A^2(1 + \cos \Delta\varphi) = 2A^2 \left( 1 + \cos \left( \varphi_0 - \Psi_0 - \frac{2\pi}{\lambda} \left( 2x \sin \frac{\alpha}{2} - d \sin \frac{\alpha}{2} \right) \right) \right).$

该周期函数沿 $X$ 轴有一个周期 $\Delta x$，可从条件中找到

$$\frac{2\pi}{\lambda} 2 \cdot \Delta x \cdot \sin \frac{\alpha}{2} = 2\pi \Rightarrow \Delta x = \frac{\lambda}{2 \sin \frac{\alpha}{2}}.$$

如果颗粒尺寸小于$\Delta x$，并且颗粒沿$X$轴以速度$v$匀速运动，那么从颗粒反射并被光电池捕获的光的强度将随时间周期性变化，周期为$T = \Delta x/v$或频率为$v = v/\Delta x$。将找到的表达式替换为 $\Delta x$，从最后一个等式中我们发现：

$$v = \frac{\lambda v}{2 \sin \frac{\alpha}{2}} = \frac{0.63 \times 10^{-6} \cdot 320 \cdot 10^3}{2 \cdot 0.5} \text{ m/c} \approx 0.2 \text{ m/c}.$$

V·V·莫扎耶夫

F838。 1844年，著名数学家和天文学家贝塞尔发现天狼星自身的运动（与地球哈布罗特的运动无关）大致遵循正弦曲线（图1）。从直线路径最大增加$a = 2,3''$，周期$T = 50$年。贝塞尔提出（18年后这一点被直接观测证实）天狼星路径的弯曲是由卫星（一颗较弱的恒星）的抛光造成的。如果主恒星（天狼星 $A$）的质量为 $M = 2,3M_C$，求卫星（天狼星 $B$）的质量 $m$ 与太阳质量 $M_C$ 的比率。众所周知，从天狼星角度$\beta = 0,376''$可以看到地球轨道的半径。假设轨道是恒星友伴，并且飞机

从问题的条件可以清楚地看出，$a$是从地球观察时天狼星轨道$A$半径的角大小。考虑到$a$和$\beta$的角度较小，我们可以写出天狼星$A$（$R$）和地球（$R_0$）轨道半径的对应关系（见图2）：

$$\frac{R}{R_0} = \frac{a}{\beta}.$$

天狼星系统的组件围绕质心旋转。天狼星 $B$ 轨道的半径 $r$ 为

$$r = \frac{M}{m} R.$$

因此，组件之间的距离等于 $R + r$。

让我们写出天狼星 $A$ 和地球（地球质量 $m_0$，地球年 $T_0$）的运动方程（牛顿 II 定律）：

$$M \left( \frac{2\pi}{T} \right)^2 R = G \frac{Mm}{(R+r)^2},$$

$$m_0 \left( \frac{2\pi}{T_0} \right)^2 R_0 = G \frac{M_C m_0}{R_0^2}.$$

我们将方程（3）除以方程（4）：

⟦folio 50⟧

$$\left(\frac{T_0}{T}\right)^2 \frac{R}{R_0} = \frac{m}{M_C} \frac{R_0^2}{(R+r)^2}.$$

可以方便地引入无量纲量$\mu = \frac{m}{M_C}$、$\tau = \frac{T}{T_0}$、$\varrho = \frac{R}{R_0}$。然后，考虑到对应关系（2），方程（5）被变换为形式

$$\frac{(\mu + M/M_C)^2}{\mu^3} = \frac{\tau^2}{\varrho^3}.$$

没有$M/M_C = 2,3$、$\varrho = \alpha/\beta \approx 6,1$（对应于（1））、$\tau = 50$。因此，

$$\frac{(\mu + 2,3)^2}{\mu^3} = \frac{\tau^2}{(\alpha/\beta)^3} \approx 11.$$

选择是：

$$\mu = m/M_C \approx 1.$$

V·E·贝洛楚金

F839。如果将六角形铅笔放置在与水平面成角度 a 且垂直于其母线（平面与水平面的交线）的斜面上，铅笔就会摇晃。如果你把它平行于母线，它就会卷起来。铅笔轴与斜面母线 (图 1) 之间的 φ 在什么条件下会处于平衡状态？

由问题条件可知，铅笔在斜面上的滑动摩擦系数$\mu$满足条件$\mu \geqslant \text{tg} \alpha$。事实上，垂直于母线放置的铅笔处于平衡状态，这意味着$mg \sin \alpha = F_{\tau p}$，其中$mg$是重力，$F_{\tau p}$是摩擦力。但是$F_{\tau p} \leqslant \mu mg \cos \alpha$。因此，$mg \sin \alpha \leqslant \mu mg \cos \alpha$，因此$\mu \geqslant \text{tg} \alpha$。

这意味着在角度$\varphi$的任何值下，铅笔都不会沿着斜面滑动。

当重力矢量“超出”铅笔和斜面之间的接触区域（在 图 2 时，该区域受到保护）时，铅笔有时可能会以$\varphi_0$这样的角度滚落。为了找到这个角度，我们将铅笔的质心投影到斜面上 - 图 2 上的点 $A$ - 并标记穿过质心的垂直线与斜面的交点 - 点 $B$。显然，在铅笔不同方向的情况下，如果其质心保持不变，点$A$和$B$将保持不动，而如果铅笔六边形横截面的边等于$2a$，则$|AB| = 2a \sin \alpha$。

只要$B$点位于六边形区域内，铅笔就不会滚动。

让我们记下滚动部分的条件：

$$\frac{|AD|}{\cos \varphi_0} = |AB_0|,$$

或$$\frac{\alpha}{\cos \varphi_0} = a\sqrt{3} \text{tg} \alpha.$$

从这里

$$\varphi_0 = \arccos \frac{1}{\sqrt{3} \text{tg} \alpha}.$$

因此，如果角度$\varphi$满足条件

$$\arccos \frac{1}{\sqrt{3} \text{tg} \alpha} \leqslant \varphi \leqslant \frac{\pi}{2},$$

⟦folio 51⟧

铅笔处于平衡状态。显然，角度$\varphi_0$的表达式在$tg\alpha > \frac{1}{\sqrt{3}}$条件下才有意义。事实上，平行于母线放置的铅笔向下滚动意味着$tg\alpha > \frac{1}{\sqrt{3}}$（你自己展示一下）。

克罗托夫

F840。在 $10 \times 10$ 厘米的扁平盒子中水平排列，随机放置 $N=1000$ 质量为 $m=0,5$ 米的小钢球。盒子开始以 $v_0=10$ m/s 的速度垂直于其中一个侧壁移动。考虑到球对盒子壁和其他球对其他物体的影响是绝对弹性的，确定： a) 在前 10 秒内球将传递到每个侧壁的冲量； b) 盒子急剧制动后，在接下来的 10 秒内，墙壁会受到什么冲量。

当盒子开始移动并撞击球时，它们获得速度$2\vec{v}_0$，经过时间$\tau_1 = a/v_0$（a是盒子的一侧）后，所有的球都开始移动（这个时间实际上要少一些，因为有些球可能由于相互碰撞，在墙壁到达它们之前就开始移动）。在球彼此之间以及与墙壁的多次碰撞之后，球的速度将具有最任意的方向。

考虑与盒子相关的参考框架中的后续内容会更方便。在这个系统中，球的平均速度（矢量）为零，并且由于盒子的速度不会随条件而变化，因此球的总能量保持不变，平均每个球的能量$mv_0^2/2$。这与气体分子通过小孔飞入空容器的行为非常相似，最初具有均匀的定向速度，一段时间后它们已经完全混乱地移动。

任务条件中指定的时间（10 秒）是否足够长以使球的运动变得紧张还有待观察。为此，我们找到球碰撞之间的近似平均时间。我们假设在此期间$\tau_{cp}$，直径为$d$的球以速度$v_0$沿直线移动。然后他“扫过”区域$S = 2dv_0\tau_{cp}$，其中（平均而言）只有一个球的中心落在随机分布的其他球的中心之外。这些剩下的球占了$a^2$的面积（a是盒子的边长）。这意味着时间 $\tau_{cp}$ 碰撞唯一性的条件如下所示：

$$\frac{a^2}{N-1} = 2dv_0\tau_{cp} \Rightarrow \tau_{cp} = \frac{a^2}{2dv_0(N-1)}$$

让我们找到球的直径，了解它的质量和钢密度：

$$d = \sqrt[3]{\frac{6m}{\pi q}} \approx 5 \cdot 10^{-4} \text{ м} = 0,5 \text{ мм}$$

因此，碰撞之间的平均时间为 $\sim 1 \cdot 10^{-3}$ s。显然，考虑到时间$\tau_1 = a/v_0 = 10^{-2}$s，“混沌化”时间不会超过0.015-0.020s，也就是说，它只是给定间隔10s的一小部分。因此，我们可以近似地假设球始终处于紧张运动状态。那么每面墙上的冲击次数是相同的。为了计算撞击的数量，球垂直于与我们相交的墙壁的运动至关重要。让我们表示球在这个方向上的速度$v_x$。短时间$\Delta t$的打击次数等于

$$\Delta n = \frac{v_x \cdot \Delta t \cdot a}{a^2} \cdot \frac{1}{2} N = \frac{v_x N}{2a} \cdot \Delta t.$$

这意味着在 $T = 10$ s 时间内，打击次数等于
