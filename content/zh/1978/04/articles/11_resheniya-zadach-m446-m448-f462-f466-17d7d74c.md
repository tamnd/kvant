---
id: 1978-4-resheniya-zadach-m446-m448-f462-f466-17d7d74c
issue: kvant_1978_4
year: 1978
number: "4"
title: 问题解决方案M446—M448； F462—F466
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 35
page_labels: 28, 29, 31, 32, 33
tag: 2W0E
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e2a1aa411a3bf3f289f7bfdebcaf0d2e20b3d1d9ab243aa78b636ec68fc84b45
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/11_resheniya-zadach-m446-m448-f462-f466-17d7d74c.md
source_content_sha256: 8ba8ea64040881e232b2d2f99713bb6f47c5bebf440c8c70b7e10b25d34deb82
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

M446。长度为 1 的圆从外侧沿着长度为 $\sqrt{2}$ 的圆滚动。在最初的时刻，圆的接触点用油漆线标记。滚动时，我的画点和另一个外圈都被它们接触到的尿液所画。当动圆绕固定圆转动 100 圈时，固定圆上有多少个不同的点会被弄脏？

图 1.

我们先来看看，在$n$转中，可动圆$b$（长度1）的第一个红点$B$会在固定圆$a$（长度$\sqrt{2}$）上留下多少个红色标记。

让我们沿着直线滚动圆$b$。那么（如果我们将直线上的第一个红点作为报告的开始$O$）点$B$的轨迹将落入非负整数坐标（图1）的点。现在我们从点 $O$ 开始，绕圆 $a$ 缠绕直线。每转一圈对应长度为 $\sqrt{2}$ 的直线段。很明显，直线的不同红点将进入圆$a$的不同点，因为整数$m, k_1 \neq k_2$等于$k_1 - k_2 = m \sqrt{2}$是不可能的（引入的数字$\sqrt{2}$是无理数）。因此，在前 $n$ 转期间，点 $B$ 将留下 $[n \sqrt{2}] + 1$ 痕迹：这正是线段 $[0; n \sqrt{2}]$ 上整数点的数量。

现在让我们尝试考虑一个圆圈和另一个圆圈上留下的所有多条痕迹。乍一看

看起来它们的数量根据旋转次数$n$呈指数增长：每次旋转后，点的平均平面（每单位长度的点数）返回大约两倍 - 毕竟，来自另一个圆的点的痕迹被添加到每个圆上的红点上。然而，这个假设被证明是完全错误的：除了第一个点 $B!$ 落在的那些点之外，圆 $a$ 上不会出现其他红点。事实上，一些空点$B' \in b$在与红点$A' \in a$接触时会被着色。由于$A'$是红色的，因此第一个点$B$已经与其接触。很明显，变为红色后，$B'$ 将击中与 $B$ 在接触 $A'$ 后已经击中的相同点（在旋转方向上与 $A'$ 相距 1, 2, ... 的距离）。

同理可以证明，除了被第一个红点$A \in a$覆盖的点外，圆$b$上不会出现任何点，这样在圆$b$上旋转$n$圈后，就会出现第$(n+1)$个红点。

因此，红点的数量不是呈指数增长，而是仅按照线性规律$[n \sqrt{2}] + 1$增长。

N·瓦西里耶夫

M447。在锐角三角形 $ABC$ 中，线段 $BO$ 和 $CO$（ede $O$ 是省略的圆的中心）延伸，直到它们在点 $D$ 和 $E$ 处与三角形的线 $AC$ 和 $AB$ 相交。原来是$BDE = 50^\circ$，还有$CED = 30^\circ$。您可以使用正弦定理找到三角形 $ABC$ 的角度。让我们输入$EBD = \varphi$。然后$OEB = 100^\circ - \varphi$，$ABC = \varphi + 40^\circ$，$ACB = 90^\circ - \varphi$，

28

⟦folio 29⟧

$OCD = 50^\circ - \varphi, ODC = \varphi + 50^\circ;$因此$0^\circ < \varphi < 50^\circ$。
从三角形$ODE, OBE$和$OCD$我们发现：

$$\frac{\sin 50^\circ}{\sin 30^\circ} = \frac{|OE|}{|OD|} = \frac{|OE|}{|OB|} \cdot \frac{|OC|}{|OD|} = \frac{\sin OBE}{\sin OEB} \cdot \frac{\sin ODC}{\sin OCD} =$$

$$= \frac{\sin \varphi \sin (\varphi + 50^\circ)}{\sin (100^\circ - \varphi) \sin (50^\circ - \varphi)} = 2 \sin 50^\circ,$$

我们必须找到 $\varphi$ ($0^\circ < \varphi < 50^\circ$) 的方程：

$$\frac{\sin \varphi \sin (\varphi + 50^\circ)}{\sin (100^\circ - \varphi) \sin (50^\circ - \varphi)} = 2 \sin 50^\circ,$$

等价如下：

$$2 \sin 50^\circ (\cos 50^\circ - \cos (150^\circ - 2 \varphi)) =$$

$$= \cos 50^\circ - \cos (50^\circ + 2 \varphi),$$

$$\sin 20^\circ - \sin (2 \varphi - 40^\circ) + 2 \sin 50^\circ \cos (2 \varphi + 30^\circ) = 0,$$

$$\cos (\varphi - 10^\circ) \sin (30^\circ - \varphi) + \sin 50^\circ \sin (60^\circ - 2 \varphi) = 0,$$

$$\sin (30^\circ - \varphi) (\cos (\varphi - 10^\circ) + 2 \sin 50^\circ \cos (30^\circ - \varphi)) = 0.$$

由于 $\cos(\varphi - 10^\circ)$ 和 $\cos(\varphi - 30^\circ)$ 在 $0^\circ < \varphi < 50^\circ$ 处为正，因此最后一个方程具有单根 $\varphi = 30^\circ$。

因此$A\widehat{BC} = 70^\circ, A\widehat{CB} = 60^\circ$。

接下来，$B\widehat{EC} = 70^\circ \Rightarrow |CE| = |CB|; \quad O\widehat{DC} = 80^\circ \Rightarrow \Rightarrow |CD| = |CO|; \quad A\widehat{DE} = 50^\circ \Rightarrow |EA| = |ED|$。

问题中需要建立的长度等式告诉您三角形 $ABC$ 应该有什么角度。但即使知道答案，也很难得出上面给出的三角解。相反，我们可以以不同的方式进行争论。

首先我们要注意的是，条件 $OED = 30^\circ, ODE = 50^\circ$ 明确地确定答案。真的 （图 3)、如果在以圆心为圆心的圆上 $O$ 总结要点 $B$ 和 $C$ 所以 $B\widehat{OC} = 100^\circ$，然后打乱点 $A$ 沿着弧线 $B'\ C'$ （对称弧 $BC$) 从点 $B'$ 说到点子上 $C'$，然后点 $D \in [B'\ O]$ 即将来临 $O$, 一个 $E \in [OC']$ - 删除自 $O$;在这种情况下，角度值 $ODE$ 会增大，并且角度 $OED$ - 减少;表示仅在一个位置 $A$ 这些数量可以取所需的值（$50^\circ$ 和 $30^\circ$).

现在我们需要证明一个角为$A = 50^\circ, B = 70^\circ, C = 60^\circ$的三角形满足条件，即所有角都如图4所示。这对于其他没有阴影的角来说是很清楚的。证明红色角度具有指示的值有些困难（对其中一个角度做到这一点就足够了）。让我们给出两个证明。

1°。检查 $DE - \text{биссектриса угла } ADB$ 就足够了：

$$\frac{|AE|}{|EB|} = \frac{|AE|}{|EC|} \cdot \frac{|EC|}{|EB|} = \frac{\sin 20^\circ \sin 70^\circ}{\sin 50^\circ \sin 40^\circ} =$$

$$= \frac{2 \sin 20^\circ \cos 20^\circ}{2 \sin 50^\circ \sin 40^\circ} = \frac{\sin 30^\circ}{\sin 50^\circ} = \frac{|AD|}{|DB|}$$.

这里我们再次使用正弦定理。这是一个纯粹的几何证明。

2°。三角形$ECB$具有对称性，因为$C\widehat{EB} = C\widehat{BE}$。令 $K$ 为相对于该轴 (图 5) 与点 $O$ 对称的点。那么三角形$KCD$等于$(|KC| = |OC| = |DC| = a, K\widehat{CD} = 60^\circ)$，因此$|KD| =$

⟦folio 31⟧

F462。如果电子恒温器设置为“尼龙”位置，我的实用程序将定期在$\tau_1 = 10$秒打开并在$\tau_2 = 40$秒关闭。同时，公用设施的表面被加热到$t_1 = 100^\circ C$的温度。如果恒温器设置为“拍手”位置，我的实用程序会定期在 $\tau_1 = 20$ 秒打开，并在 $\tau_2 = 30$ 秒关闭。确定恒温器此位置的实用表面的设定温度 $t_2$。也就是说，如果恒温器发生故障，打开的公用设施会沸腾到什么温度$t_3$。
假设粉笔去除量与温度和环境空气成正比。室温$t_0 = 20^\circ C$。

F463。两块浮冰以相同绝对值的随机速度移动，一个向北，另一个向西。确实，在两个浮冰上的任何时刻，都可以以这样的方式布置时钟，使得秒针末端相对于地球的速度相等，并且对于每个时刻，只有一种这样的布置。如果每只秒针的长度为 1 厘米，请确定浮冰每天移动多远。时钟表盘水平放置。

设 $P$ 为熨斗释放的功率。那么及时$\tau_1$能量就会在其中释放出来
$$W_1 = P\tau_1.$$
在$\tau_1 + \tau_2$时间内，utigot释放能量
$$W_2 = \alpha (t_1 - t_0) (\tau_1 + \tau_2),$$
其中$\alpha$是比例系数。
在稳定的熨斗温度 $W_1 = W_2$ 下：
$$P\tau_1 = \alpha (t_1 - t_0) (\tau_1 + \tau_2).$$
(1)

同理，在温控器设置为“棉”位置的模式下，
$$P\tau'_1 = \alpha (t_2 - t_0) (\tau'_1 + \tau'_2).$$
(2)

将(1)中的值$P$代入(2)，可得$t_2$：
$$t_2 = \frac{\tau'_1}{\tau_1} \frac{(t_1 - t_0)(\tau_1 + \tau_2)}{\tau'_1 + \tau'_2} + t_0 = 180^\circ C.$$
使用类似的计算和计算，我们找到$t_3$：
$$t_3 = 420^\circ C.$$
V·斯科罗瓦罗夫

箭头末端相对于地球的速度$v$等于浮冰速度$v_1$和箭头末端相对于浮冰的速度$v_2$的矢量和。

设图 9 上的向量$\vec{OA}$为浮冰的速度；向量 $\vec{AB'}$、$\vec{AB''}$、$\vec{AB'''}$ 是在某些时钟方向上指针末端相对于浮冰的速度。那么向量$\vec{OB'}$、$\vec{OB''}$、$\vec{OB'''}$分别是箭头末端相对于地球的速度。

很明显，对于向量$\vec{AB}$（$\vec{AB'}$，$\vec{AB''}$，...）的所有可能方向，点$B$（$B'$，$B''$，...）的几何轨迹是一个以点$A$为中心的球体（时钟的水平位置是一个圆）。在这样的“速度空间”中，可能的速度 $v$ 被描述为对应于球（或圆）上的点 $O$ 并结束于点 $B$。第二个浮冰的构造有所不同，它将浮冰速度矢量旋转 $90^\circ$。

图 9.

图 10.

⟦folio 32⟧

修正案

在«Kvant»第3期中，由于印刷厂的错误，图至解决方案���题 M445（见第35页，图8）被错误地复制。 图 应该是这样的：

图10 显示了同时构建两个浮冰的结构。向量$\overrightarrow{OA}$和$\overrightarrow{OA'}$是浮冰的速度，圆$S$和$S'$是向量$\vec{v}$和$\vec{v}'$末端的几何位置，浮冰速度的值与箭头末端之间的对应关系不同。如果箭头末端的速度太小，则圆 $(S_1$ 和 $S_1')$ 没有公共点，并且对于时钟的任何方向，速度 $\vec{v}$ 和 $\vec{v}'$ 都不能相等。圆$S_3$和$S_3'$对应于方向不唯一的情况。

问题的条件对应于切圆$S_2$和$S_2'$所描绘的情况。从图可以看出，本例中为$\left| \vec{v} \right| = \left| \vec{v}_2 \right|$，浮冰的速度为$\left| \vec{v}_1 \right| = \left| \vec{v}_2 \right| V^2$。秒针每 60 秒转一圈，因此其尖端速度为 $\left| \vec{v}_2 \right| = 2\pi l/60 \approx 0,105$ 厘米/秒（$l=1$ 厘米为秒针的长度）。对于浮冰的速度，我们得到 $\left| \vec{v}_1 \right| \approx 0,15$ cm/s≈130 m/天。

V·贝洛努金

F464。 图 11 显示了两个闭环：ABBA 和 ABGA。两个循环均以理想的单原子时间进行。

1) 指出我们在周期的哪些部分收到以及我们在哪些部分给予menlo。
2) 哪个循环效率更高？多少次？

考虑 ABC 循环。从$pV$图中可以清楚地看出$T_B > T_B > T_A$。因此，在区段AB和BV中气体接收气体，并且在区段BA中气体被释放。在这种情况下，在AB部分，气体被加热而不做功（$\Delta V=0$），而在BV和BA部分，气体所做的功等于（每个周期气体内能的变化为零）

$$A_1 = Q_{AB} + Q_{BB} + Q_{BA} \quad (Q_{BA} < 0).$$

因此，在 ABBA 循环中

$$\eta_1 = \frac{A_1}{Q_{AB} + Q_{BB}}.$$

考虑 ABGA 循环。从$pV$图中可以清楚地看出$T_B > T_G > T_A$，因此在AB部分气体接收tello，而在BG和GA部分释放气体。在HA部分，气体确实起作用

$$A_2 = Q_{AB} + Q_{BG} + Q_{GA} \quad (Q_{BG}, Q_{GA} < 0),$$

所以

$$\eta_2 = \frac{A_2}{Q_{AB}}.$$

我们来比较一下$\eta_1$和$\eta_2$的值。从$pV$图中可以清楚地看出$A_1 = A_2$（因为每个周期所做的功在数值上等于周期图所限制的图形面积），因此

$$\frac{\eta_1}{\eta_2} = \frac{Q_{AB}}{Q_{AB} + Q_{BB}},$$

从$Q_{AB} + Q_{BB} > Q_{BA}$开始，然后$\eta_2 > \eta_1$。

我们来计算一下比率$\frac{\eta_1}{\eta_2}$。为此，我们找到 $Q_{AB}$、$Q_{BB}$ 和 $Q_{AB}$。

根据$pV$图$Q_{AB} = \Delta U_{AB}$，其中$\Delta U_{AB}$为AB段气体内能的变化。对于一摩尔单原子理想气体$\Delta U_{AB} = \frac{3}{2}R \times (T_B - T_A)$。从气体状态方程我们找到$T_B = \frac{2p_0V_0}{R}$，$T_A = \frac{p_0V_0}{R}$。因此，

⟦folio 33⟧

$$Q_{AB} = \Delta U_{AB} = \frac{3}{2} R \left( \frac{2 p_0 V_0}{R} - \frac{p_0 V_0}{R} \right) = \frac{3}{2} p_0 V_0.$$

在第 $BB$ $Q_{BB} = \Delta U_{BB} + A_{BB}$ 部分，其中

$$\Delta U_{BB} = \frac{3}{2} R (T_B - T_B) =$$

$$= \frac{3}{2} R \left( \frac{2 p_0 3 V_0}{R} - \frac{2 p_0 V_0}{R} \right) = 6 p_0 V_0$$

（一摩尔），

$$A_{BB} = 2 p_0 2 V_0 = 4 p_0 V_0.$$

因此，

$$Q_{BB} = 6 p_0 V_0 + 4 p_0 V_0 = 10 p_0 V_0,$$

$$Q_{AB} + Q_{BB} = 11,5 p_0 V_0.$$

但是$Q_{AB} = -Q_{BA}$，

$$Q_{BA} = A_1 - (Q_{AB} + Q_{BB}) =$$

$$= p_0 V_0 - 11,5 p_0 V_0 = -10,5 p_0 V_0,$$

所以

$$Q_{AB} = 10,5 p_0 V_0.$$

所以，

$$\frac{\eta_1}{\eta_2} = \frac{Q_{AB}}{Q_{AB} + Q_{BB}} = \frac{10,5}{11,5} \approx \frac{21}{23}.$$

A·齐伯曼

F465。在高压电声发生器中，电荷通过介电质延展传输，并对半径为 $R = 1,5$ m (图 12) 的高压电声电极充电。如果皮带速度为 $v = 20$ m/s，其宽度为 $l = 1$ m，请估计从此类发电机可以获得的电压和电压的最大值。当电场电压$E_0 = 30$ kV/cm时，可能会击穿。

发生器高压球形电极所能带电的最大电势由空气的电气强度决定：电极表面附近的电场电压不能超过值$E_0 = 30$kV/cm，此时发生击穿，即

$$E_{\max} = E_0.$$

因此，每个电极的最大可能电势为

$$\varphi_{\max} = E_{\max} R = E_0 R = 4,5 \cdot 10^6 \text{ B}.$$

（这种对应关系是根据库仑定律和库仑场势的表达式得出的。）

发电机所能获得的最大电流也由空气的电气强度决定。让我们用 $\sigma$ 表示由铒传输的电荷的表面密度。则铼表面附近的电场电压为$E = \frac{\sigma}{2\varepsilon_0}$。该值不应超过$E_0$。因此，胶带上可能的最大表面电荷密度等于

$$\sigma_{\max} = 2\varepsilon_0 E_0.$$

最大电流显然等于Lenium单位时间内传输的最大电荷，即

$$I_{\max} = \sigma_{\max} lv = 2\varepsilon_0 E_0 lv \approx 10^{-3} \text{ A}.$$

上述计算说明了为什么静电发生器必须很大。

S·科泽尔
