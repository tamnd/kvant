---
id: 1985-2-resheniya-zadach-m886-m890-f898-f902-0ec1d377
issue: kvant_1985_2
year: 1985
number: "2"
title: 问题解决方案M886—M890； F898—F902
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 49
page_labels: 40, 41, 42, 43, 45, 46, 47
tag: 8N8U
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a90bd84cf56b87e763986562e1edcab29781f9cd09d02f0b044e069911ec9a44
prompt_sha256: draft-1
translated_from: content/ru/1985/02/articles/19_resheniya-zadach-m886-m890-f898-f902-0ec1d377.md
source_content_sha256: d07d4d8f0b8e9d69491e443d048065e2b414866c721e7bd893fbe15647788b3c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

P921. A flat capacitor is connected to a source of tension $U$. The capacitor’s plates are of area $S$ each, the distance between them is $d_1$. A metal plate of area $S$, mass $m$ and thickness $d_2$ is pressed against one of the capacitor’s plates (Fig. 4). Then the metal plate is released. With what velocity will it hit the capacitor’s other plate?

P922. In order to get close up of an ant, a photographer added a cylindrical extension to his camera, increasing the distance between the film and the lens by $\Lambda l=7.5$ mm. A well focused picture of the ant was obtained when the distance reading on the camera was $b=1.05$ m (the distance reading does not take the extension into account). The focal distance of the lens is $F=50$ mm. What was the actual distance between the lens and the ant? The lens may be assumed thin.

A. P. Ershov

问题解决方案
M886 — M890; F898 — F902

答案：a）可能（图1）； $s$可以等于$\pm 41, \pm 12; 6)$不能； b）可能（图2）； $s=\pm 8, \pm 24; r)$ 可能； $s=\pm 3968, \pm 11904$。

任务是将一组$4n-4$连续整数分成$n-2$四元组和另外2对数字，使得所有四元组和对中的数字之和相同并且等于$s$。让我们用$c$表示$4n-4$这些数字的两个极端之和——最小的$m$和最大的$M$。 （为了进一步考虑，请注意$M=m+4n-5$，即$c=2m+4n-5$和$m=(c+5)/2-2n, M=(c-5)/2+2n$。）当然，$c$始终是奇数。所有$4n-4$数之和等于$(2n-2)c$，因此，如果我们需要空气的除法，则等式必须满足

$$ns=2(n-1)c.$$

这个必要条件允许我们立即使用$n$能被4整除的情况，特别是$n=4$（问题的第6点））：对于这样的$n$，没有分区，因为（1）的右侧不能被4整除，而左侧可以。

对于奇数$n$（以下所有内容都适用），条件（1）也给出了严格的限制：由于$n$和$n-1$是互质的，并且$n$和$c$是奇数，$c$可以被$n$整除，因此对于奇数奇数$r$，等式必须成立

$$c=nr, \quad s=2(n-1)r.$$

图 3 显示了如何为 $r=1$ 和 $r=3$ 构建所需的分区。两对数字 - “红色”和“黄色” - 具有相同的和 $s$（即点 $s/2$ 处的公共对称中心），其余 $4n-8$ 数字形成 $n-2$ 的四个“蓝色”序列

⟦folio 41⟧

Issled（以及连续的灵魂），其中两个我们认为是上升的，另外两个是下降的。然后这些序列的第一个数字的总和等于第二个数字的总和，第三个数字的总和，依此类推，这样我们就得到了具有相同总和的$n-2$四元组；如果$s$和$c$之间满足对应关系(1)，则所有这些和也等于$s$。 图3所示的例子，对于任何奇数$n$，a和b对应于公式(2)中的$r=3$和$r=1$。 （图1和图2显示了$n=3$和$n=5$的正方形边界的相应填充。）通过更改所有$4n-4$数字的符号（这将导致$s$和$c$的符号发生变化），我们得到了$r=-3$和$r=-1$的示例。

因此，我们用值$s$ a) $\pm 4$、$\pm 12$表示$n=3$； c) $\pm 8$、$\pm 24$为$n=5$； d) $\pm 3968$、$\pm 11904$ 代表 $n=1985$（一般来说，$\pm 2(n-1)$、$\pm 6(n-1)$ 代表奇数 $n$）。让我们证明这些值穷尽了问题a)、c)和d)的答案。两对红黄数字之和$2s$不小于四个最小的$m$、$m+1$、$m+2$、$m+3$的总和$4m+6$且不大于四个最小的$M$的总和$4M-6$， $M-1$、$M-2$、$M-3$，从整数$m$到$M$。通过$c$和$n$表达$m$和$M$，并使用公式（2），我们得到

$$2(c+8-4n)=4m+6 \leq 2s \leq 4M-6=2(c-8+4n),$$
$$nr-4n+8 \leq 2r(n-1) \leq nr+4n-8,$$

在哪里

$$-4(n-2) \leq (n-2)r \leq 4(n-2),$$

即$|r| \leq 4$。仍然要记住 $r$ 是奇数。

如果任何读者也能解决 $n=6$ 以及一般情况下 $n=4k+2$ 的这个问题，我们将很高兴熟悉该解决方案并在期刊中报告它。

V. G. Boltyansky、N. V. 瓦西里耶夫

◆ 让直线$AM$ 与第二个圆相交于点$D$（参见图）。显然，只要证明四边形$ABCD$是平行四边形就足够了。

利用两个弦或一个弦和一条切线形成的圆上的一个顶点的角的大小等于该角所包含的角的大小的一半这一事实，我们可以写出两个等式链：

$$\angle ADB = \frac{1}{2} \cup BsM = \angle ABM = \frac{1}{2} \cup AM = \angle CAD,$$

$$\angle ADC = \frac{1}{2} \cup MC = \angle MBC = \frac{1}{2} \cup BfM = \angle BAM$$

（$\cup BfM$和$\cup BsM$是第一个和第二个圆的每个$BM$的值）。角$ADB$和$CAD$相等意味着平行线$AC$和$BD$，角$ADC$和$BAM$相等意味着平行线$AB$和$CD$；这是需要证明的。

I.F.沙里津

⟦folio 42⟧

M888。自然数a、b、c和d满足等式ab=cd。证明数a$^{1984}$+b$^{1984}$+c$^{1984}$+d$^{1984}$是合数。

让我们证明如果ab=cd，则a=uv，​​b=wt，c=uw，d=wt，其中u，v，w，t是一些自然数。

由于 ab 可被 c 整除，因此 c 可以写为 c=uw，其中 u 是 a 的约数，w 是 b 的约数（例如，u 可以是 a 和 c 的最公约数）。那么a=uv，​​b=wt，因此d=vt。剩下的很简单：
$$a^{1984}+b^{1984}+c^{1984}+d^{1984} = (uv)^{1984}+(wt)^{1984}+(uw)^{1984}+(vt)^{1984} = (u^{1984}+t^{1984})(v^{1984}+w^{1984}),$$
而右边的数字显然是合数。

A.V.安詹斯

M889。平面上是否存在 A、B、C 三点，使得对于平面上的任意点 P，线段 PA、PB 和 PC 中至少有一个具有无理数长度？

答：这样的点是存在的。

设A、B为平面上两点，两点之间的距离为$\sqrt{2}$，C为线段AB的中点，P为平面上任意点。

那么$2\vec{PC} = \vec{PA} + \vec{PB}, \vec{AB} = \vec{PB} - \vec{PA}$，即
$$4PC^2 = PA^2 + PB^2 + 2\vec{PA} \cdot \vec{PB},$$
$$AB^2 = PA^2 + PB^2 - 2\vec{PA} \cdot \vec{PB}.$$
添加这些等式，我们得到
$$4PC^2 + AB^2 = 2PA^2 + 2PB^2,$$
并且，由于数AB$^2 = \sqrt{2}$是无理数，因此数PA、PB和PC不能同时是有理数。

A·M·斯林科

M890。这些国家的领土呈边长1000公里的正方形，有51个城市。该国有能力修建11000公里的高速公路。它能够通过高速公路网络连接所有城市吗？

答：是的，可以。我们将指出一种可能的道路铺设方式。让我们铺设一条 1000 公里长的高速公路，穿过该国的一个城市，与边界平行于广场的一侧（图1）。在距离该高速公路两端 100 公里处，我们将在高速公路上标记两个点。在它们之间，彼此相距 200 公里，我们将再放置 3 个点。通过这 5 个点，我们将修建 5 条道路，垂直于之前修建的高速公路和从一个边界到另一个边界的太空路线。现在我们将从每个城市修建一条高速公路，沿着最短的路线将该城市与其中一条已铺设的道路连接起来。每个城市每条新增高速公路长度不超过100公里，高速公路总数不超过50条。因此，所有高速公路的总长度不超过6·1000+50·100=11000公里。

所示的高速公路网并不是最短的。 图 2 显示了更加本地化的高速公路布局的示例。折线的总长度为 5·800+4·200=4800 公里，另外还有 12 个“卷须”，每条长（100$\sqrt{2}$−100）公里。同时接收长度为4800+12·(100$\sqrt{2}$−100)=3600+1200$\sqrt{2}$公里的高速公路网，容易看出，广场上任一点到最近高速公路的距离不超过100公里。因此，为了将51个城市与已经建成的高速公路网连接起来

⟦folio 43⟧

为了解决这个问题，我们使用能量守恒定律。在棍子的初始时刻，与地平线形成角度α，使得sinα=H/2l。初始时刻棒的总能量等于其势能，并且等于

$$U_0 = mg \frac{H}{4}.$$

当一根棍子运动时，任意时刻它的总能量就是它的势能之和

$$U_t = mg \frac{l \sin \beta}{2}$$

（β 是木棍在给定时刻与地平线形成的角度 (图 2)），平移运动的动能

$$E_{t1} = m \frac{v_t^2}{2}$$

（$v_t$是棒质心的速度）和旋转运动的能量$E_{t2}$。根据能量守恒定律

$$U_t + E_{t1} + E_{t2} = U_0,$$

在哪里

$$E_{t1} = \frac{mv_t^2}{2} = U_0 - U_t - E_{t2},$$

和

$$v_t = \sqrt{\frac{2}{m}(U_0 - U_t - E_{t2})}.$$

显然，当$U_t$和$E_{t2}$的值最小时，棒质心的速度$v_t$将最大。

当棒的上端占据最可能的位置时，即当螺纹垂直时，势能最小。同时

$$U_{t_{\min}} = mg \frac{|l - l|}{2}.$$

不难理解，此时棍子只向前移动。事实上，由于棍子是不可伸展的，所以它的任何点的速度在棍子本身的方向上的投影应该是相同的。下点（图 2 上的 C 点）的速度始终指向水平方向，而当螺纹垂直时，上点（图 2 上的 B 点）的速度也为水平方向（因为螺纹不可延伸）。根据棍子不可伸展的条件，可以得出这些速度必须相同并且此时棍子的所有点都必须在移动。

⟦folio 45⟧

在其中缝制一层高度为 $h_1$ (图 4) 的鲁图蒂。该力在数值上等于 图 4 处阴影部分的杯子体积中车辙的重量：

$$F_{p1} = q_1 g \left( \pi R^2 h_1 - V_1 \right),$$

(5)

其中 $V_1$ 是杯子中剩余的钌的体积，等于

$$V_1 = \frac{2}{3} \pi R^3 - \pi \left( R - h_1 \right)^2 \left( R - \frac{R - h_1}{3} \right).$$

(6)

将考虑了(6)的(5)代入平衡条件(4)并求解相对$h_1$的结果方程，我们得到问题第二个问题的答案：

$$h_1 = \sqrt[3]{\frac{3m}{\pi q_1}}.$$

M·G·亚伯拉罕米扬

F900。描述理想单原子气体通过过程的部分图表已得到验证 (图 1)。体积比例是已知的（它们在 图 1 上表示）。在从状态 1 到状态 2 的整个转变过程中，气体的回馈和接收的量一样多。求气体在此过程中所做的功。

如果过程图被完全指定（图2），那么要确定气体所做的功，只需确定图C12D的面积$S_1$即可。让我们证明面积$S_1$可以用图形M12N的面积$S_2$来表示，这可以从给定的“不完整”图确定。

从图2可以看出，

$$\left| p_1 V_1 \right| + S_1 = \left| p_2 V_2 \right| + S_2 \Rightarrow S_2 = S_1 + \left| p_1 V_1 \right| - \left| p_2 V_2 \right| \left( \left| p_1 V_1 \right|, \left| p_2 V_2 \right| \right) - \text{соответствие площади прямогонников M1CO и N2DO}).$$

由于在整个过程中气体释放的量与接收到的量一样多，因此我们可以从热力学第一定律得出结论：

$$A = -\Delta U,$$

其中$\Delta U$是该过程中气体内能的变化。

对于理想的单原子气体$U = \frac{3}{2} v R T$，所以

$$A = \frac{3}{2} v R \left( T_1 - T_2 \right),$$

其中 $T_1$ 和 $T_2$ 分别是点 1 和 2 处的气体温度。

从门捷列夫-克拉佩龙方程可以得出：

$$p_1 V_1 - p_2 V_2 = v R \left( T_1 - T_2 \right) = \frac{2}{3} A,$$

所以 $\left| p_1 V_1 \right| - \left| p_2 V_2 \right| = \frac{2}{3} S_1$ 和

$$S_1 + \frac{2}{3} S_1 = S_2,$$

在哪里

$$S_1 = \frac{3}{5} S_2.$$

面积$S_2$的值可以从问题条件中指定的图形中确定；使用图表上指定的比例，我们找到 $S_2 \approx 3$ kJ；因此，

$$A \approx 1,8 \text{ кДж.}$$

V·T·卡佩特扬

⟦folio 46⟧

F901。三个相同的电容器，每个电容为C，串联连接到具有电动势E的电池上。充满电后，将它们与电池断开。然后同时连接两个电阻为 R 的电阻，如图所示。每个电阻会产生多少热量？当中间电容器上的电压比电池电动势小 10 倍时，电阻器两端的点是什么？

最重要的是这个电路中的电容没有完全放电。电路中的电流停止后，电容器并联，即它们两端的电压相同。

因此，放电中间电容器等于外部电容器的电流之和，并且由于对称性，它们彼此相等（参见图），

$$I_2 = 2I_1.$$

让我们表示放电结束时电容器上的电压$U_x$。由于每个电容器上的初始电压为$\frac{\varepsilon}{3}$，因此在放电期间，电荷$q_1 = C\left(\frac{\varepsilon}{3} - U_x\right)$将流过电容器，并且电荷$q_2 = C\left(\frac{\varepsilon}{3} + U_x\right)$将流过中间电容器（中间电容器将被充电到相反极性）。显然$q_2 = 2q_1$，即

$$2C\left(\frac{\varepsilon}{3} - U_x\right) = C\left(\frac{\varepsilon}{3} + U_x\right),$$

在哪里

$$U_x = \frac{1}{9} \varepsilon.$$

我们根据能量守恒定律找到每个电阻器上释放的热量：

$$Q_1 = Q_2 = \frac{1}{2}\left(W_{\text{нач}} - W_{\text{кон}}\right) = \frac{1}{2} \cdot 3 \cdot C\left(\frac{\varepsilon}{3}\right)^2 - \frac{1}{2} \cdot 3 \cdot C\left(\frac{\varepsilon}{9}\right)^2 = \frac{2}{27}C\varepsilon^2.$$

由于中间电容器被充电到相反的极性，因此电压$\varepsilon/10$将在其上两次 - 在从$\varepsilon/3$放电到0期间以及在从0到$\varepsilon/9$充电期间。对于第一种情况，根据欧姆定律，

$$U_{t1} + \frac{\varepsilon}{10} = RI_{t1}$$

(1)

（$U_{t1}$——此时外部电容上的电压）；此时流过外部电容器和中间电容器的电荷与以下比率相关

$$C\left(\frac{\varepsilon}{3} - U_{t1}\right) = \frac{1}{2}C\left(\frac{\varepsilon}{3} - \frac{\varepsilon}{10}\right).$$

(2)

同时求解 (1) 和 (2)，我们发现在第一种情况下流过电阻的电流 $I_{t1}$：

$$I_{t1} = \frac{19}{60}\frac{\varepsilon}{R}.$$

为第二种情况编写类似的方程 -

$$U_{t2} - \frac{\varepsilon}{10} = RI_{t2}, \quad C\left(\frac{\varepsilon}{3} - U_{t2}\right) = \frac{1}{2}C\left(\frac{\varepsilon}{3} + \frac{\varepsilon}{10}\right),$$

- 我们发现：

$$I_{t2} = \frac{1}{60}\frac{\varepsilon}{R}.$$

A.R.齐伯曼

⟦folio 47⟧

F902。两个厚度为 d 的平坦层在整个体积中均匀地带电，电荷密度为 -ρ u +ρ。带负电荷 -e 且质量为 m 的粒子与带正电的层相邻，其速度 v 与层表面成 α 角（参见 图）。
1) 粒子以什么速度不能穿透带负电的层？
2) 在这种情况下，经过多少时间以及距 A 点多远的距离，粒子离开带正电层？

让我们选择一个 XY 坐标系，如 图 所示。我们可以立即注意到，粒子沿 Y 轴的运动将以速度 v cos α 均匀运动（我们忽略重力的影响）。带电层作用在粒子上的力沿 X 轴方向，并且 x 坐标点处的力由在 图 区域（与层的相对界面平面对称）上旋转的电荷确定。事实上，具有不同大小电荷的非阴影区域的影响得到了补偿，因为空间电荷区域可以被想象为一组具有表面电荷的平面，并且由带电平面产生的场不取决于到它的距离。出于同样的原因，我们可以假设坐标为 x 的点处的场由位于该点左侧和右侧的表面电荷 -ρx 和 +ρx 的带电平面确定。该场的电压等于

$$E = 2 \frac{\rho x}{2 \varepsilon_0} = \frac{\rho x}{\varepsilon_0}.$$

这意味着当粒子位于坐标为 x 的点时，作用在粒子上的力等于

$$F_x = -e \frac{\rho x}{\varepsilon_0},$$

质点在X轴方向的运动方程为

$$x'' = - \frac{e \rho}{m \varepsilon_0} x$$

是频率为$\omega_0 = \sqrt{e \rho/m \varepsilon_0}$的简谐振动方程。据了解，如果这些振荡的幅度小于 d，则粒子将不会渗透到负电荷区域。满足该条件的粒子的最大速度 v_pr 由等式确定

$$v_{пр} \sin \alpha = \omega_0 d = d \sqrt{\frac{e \rho}{m \varepsilon_0}};$$

从这里

$$v_{пр} = \frac{d}{\sin \alpha} \sqrt{\frac{e \rho}{m \varepsilon_0}}.$$

以速度 v < v_{pr} ，粒子渗入正层一定深度，然后被“推出”。粒子在层内停留的时间 t 是频率为 $\omega_0$ 的振荡周期的一半，即

$$t = \frac{T}{2} = \pi \sqrt{\frac{m \varepsilon_0}{e \rho}};$$

在此期间，颗粒将在一定距离内垂直混合

$$y = t v \cos \alpha = \pi v \sqrt{\frac{m \varepsilon_0}{e \rho}} \cos \alpha.$$

在距 A 点的这个距离处，粒子将飞出带正电的层。

A.I.布兹丁
