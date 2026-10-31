---
id: 1989-12-mukushev-metod-graficheskih-otsenok-37efb00d
issue: kvant_1989_12
year: 1989
number: "12"
title: 图解评估法
authors:
  - Мукушев Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 58
page_labels: 52-56
tag: SET2
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ce44cf7100eef956b9d93df869298400c7763e2eab07e464cf5b3810317e0573
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/13_mukushev-metod-graficheskih-otsenok-37efb00d.md
source_content_sha256: b037b061a486b0569bc111e8f48a4b36eb5f6c90b5eccfc3a4f74eda99155478
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

图解评估法

V·A·穆库舍夫

研究物理现象和过程有许多不同的方法。其中之一是图形评估方法。它还用于解决特定的物理问题。

图解法一方面使解决问题的各个阶段变得清晰，另一方面使得快速评估所得到的解成为可能，这在解析解繁琐或不可能时尤其重要。

由于图解法是一种近似计算方法，其结果并不准确。然而，使用表格、微型计算器和计算机总是可以提高准确性。通过构建适当的图表，您可以快速获得近似结果并检查它的真实性以及它是否具有物理意义。

文章中提出的问题不太可能在大学入学考试中给出，尽管您无疑可能会遇到具有繁琐解析解的类似问题。

问题 1. 将玩具“Vanka-Vstanka”（图 1）放置在半径为 R 的固定台阶上。玩具的下表面是半径为 r 的球面，玩具的重心 - 点 C - 位于球体半径的中间。如果 R/r=4，玩具可以偏转至初始位置的最大角度 β_max 是多少？

⟦folio 53⟧

当玩具偏离时，例如向右偏离，重心就会发生变化（参见 图 1）。如果同时它位于垂直线$AB$的左侧，穿过支点$A$，那么重心将使玩具返回到平衡位置。如果重心向右$AB$，玩具就会掉落。

让我们将$\alpha$表示为玩具的旋转角度，将$\beta$表示为半径$O'A$的旋转角度。其他$LA$和$KA$相等（无滑点），即$\alpha r = \beta R$，因此$\alpha = \beta \frac{R}{r}$。

从三角形$OAB$我们有

$$\frac{OB}{\sin \beta} = \frac{AO}{\sin (\pi - \alpha - \beta)} = \frac{r}{\sin (\alpha + \beta)} = \frac{r}{\sin (\beta (1 + R/r))},$$

或者

$$OB = \frac{r \sin \beta}{\sin (\beta (R/r + 1))}.$$

如果$OC = \frac{1}{2} r > OB$，即玩具将返回其原始位置。

$$\frac{1}{2} r > \frac{r \sin \beta}{\sin (\beta (R/r + 1))},$$

或者，考虑关系 $R/r = 4$，$\sin 5\beta > 2 \sin \beta$。

为了找到极限角$\beta_{\max}$，我们必须求解三角方程

$$\sin 5\beta_{\max} = 2 \sin \beta_{\max}.$$

为此，我们将构造函数 $y = \sin 5\beta$ 和 $y = 2 \sin \beta$ 的图，并根据这些图的交集 (图 2) 我们会发现

$$\beta_{\max} \approx 0,42 \text{ рад} \approx 23,9^\circ.$$

这意味着在 $-23,9^\circ < \beta < 23,9^\circ$ 时，玩具返回到其初始位置。

问题 2. 一个质量为 $m$ 的立方体放置在主表面上，通过弹簧与墙壁相连，该立方体被第二个质量为 $M$ (图 3) 的立方体从右侧击中。发生绝对弹性冲击，之后第一个立方体开始振动。到现在为止，烧瓶期将过去哪一部分

$$Mv_0 = mv_1 + Mv_2, \quad \frac{Mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{Mv_2^2}{2},$$

在哪里

$$v_1 = v_0 \frac{2}{1 + \gamma}, \quad v_2 = v_0 \frac{1 - \gamma}{1 + \gamma}.$$

⟦folio 54⟧

碰撞后，第二个立方体会匀速移动，其坐标会按照规律随时间变化

$$x_2 = v_2 t = v_0 \frac{1-\gamma}{1+\gamma} t.$$

第一个立方体开始按照规律振动

$$x_1 = x_m \sin \omega t.$$

谐波频率

$$\omega = \sqrt{\frac{k}{m}},$$

其中$k$是弹簧刚度。我们根据能量守恒定律找到振荡幅度$x_m$：

$$\frac{m v_1^2}{2} = \frac{k x_m^2}{2} \Rightarrow x_m = \frac{v_1}{\omega} = \frac{2 v_0}{(1+\gamma) \omega}.$$

因此，

$$x_1 = \frac{2 v_0}{(1+\gamma) \omega} \sin \omega t.$$

立方体的第二次碰撞将在$x_1 = x_2$条件下发生，即

$$\frac{2 v_0}{(1+\gamma) \omega} \sin \omega t = v_0 \frac{1-\gamma}{1+\gamma} t.$$

从这里

$$2 \sin \omega t = (1-\gamma) \omega t,$$

或者

$$2 \sin \left(2 \pi \frac{t}{T}\right) = (1-\gamma) 2 \pi \frac{t}{T},$$

其中$T = 2 \pi/\omega$是振荡周期，$t/T$是周期的期望频率。

我们用$\pi t/T = z$来表示它。那么前面的方程的形式为

$$\sin 2z = (1-\gamma) z.$$

对于 $\gamma = 1/2$ 我们得到

$$\sin 2z = \frac{z}{2}.$$

让我们画出函数 $y = \sin 2z$ 和 $y = z/2$ (图 4) 的图形，并从它们的交集我们找到

$$z \approx 1,24$$高兴，$\pi \frac{t}{T} \approx 1,24$，$\frac{t}{T} \approx 0,39$。

如果$m \ll M$，即$\gamma \to 0$，那么我们得到方程

$$\sin 2z = z.$$

他的解决方案是（参见图 4）

$$z \approx 0,95$$高兴，或$\frac{t}{T} \approx 0,30$。

如果立方体的坐标不再重合，也就是说，用图形的语言来说，如果表示第二个立方体的坐标随时间的图的直线不再与正弦曲线相交，则不会发生立方体的第二次碰撞。这对应于从点 $O$ 出现的所有直线以及线 $I$ 和 $II$ 之间的屏蔽区域的位置。第 $I$ 行对应于情况$m/M \to \infty$（入射立方体的质量非常小）。仍然需要找到线 $II$（正弦曲线的切线）的$\gamma$。从图 4 可以看出，这条线对应的是$z \approx 2,24$ rad 值。从这里

$$\gamma = 1 - \frac{\sin 2z}{z} \approx 1,44.$$

因此，为了不发生第二次碰撞，必须满足条件

$$1,44 < \gamma < \infty.$$

问题 3. 活塞泵每次摆动都会捕获一定量的空气。当从容器中抽出空气时，泵进行了四次摆动。容器内的初始压力等于大气压力$p_0$。然后，该泵开始从大气中向容器内供给空气，并进行四次摆动。与此同时，容器内的压力变为

⟦folio 55⟧

是大气压的2倍。找出泵的工作容积与容器容积之间的对应关系。

第一次抽气后，当从容器中抽出空气时，容器内的压力将变得相等

$$p_1 = p_0 \frac{V}{V + V_0},$$

其中$V$为容器容积，$V_0$为活塞泵的工作容积；第二次挥杆后 -

$$p_2 = p_1 \frac{V}{V + V_0} = p_0 \left( \frac{V}{V + V_0} \right)^2$$

等四次摆动后，容器内的压力将为

$$p' = p_0 \left( \frac{V}{V + V_0} \right)^4.$$

当空气在四次摆动后被泵入容器中时，容器中就会建立压力

$$p = p' + \frac{4p_0V_0}{V} = p_0 \left( \left( \frac{V}{V + V_0} \right)^4 + 4 \frac{V_0}{V} \right) = p_0 \left( \left( \frac{1}{1 + V_0/V} \right)^4 + 4 \frac{V_0}{V} \right).$$

另一方面，根据问题的条件$p = 2p_0$。

我们得到方程

$$2p_0 = p_0 \left( \frac{1}{1 + V_0/V} \right)^4 + 4 \frac{V_0}{V}),$$

或者

$$2 - 4x = \left( \frac{1}{1 + x} \right)^4,$$

其中$x = V_0/V$。让我们构建函数图 (图 5)

$$y = 2 - 4x \text{ и } y = \frac{1}{(1 + x)^4}$$

从它们的交叉点我们发现

$$x \approx 0,44, \text{ т. е. } \frac{V_0}{V} \approx 0,44.$$

问题4. 为了确定未知电容器$C_x$的电容，组装了图6所示的电路。电容器$C_o$的电容已知。电容器$C_o$使用钥匙$K_1$使用钥匙$K_2$结果是$U_4$。由于通过毫安的电流是奇数，因此很容易确定

$$\frac{U_2}{R_2} = \frac{U_4}{R_1},$$

其中$U_2$是电阻$R_2$两端的压降。另一边，

$$U_2 = U_0 - U_4.$$

⟦folio 56⟧

从这里

$$\frac{U_4}{U_0} = \frac{R_1}{R_1 + R_2}.$$

最初，电容器$C_x$有电荷$q_x = C_x U_0$。在 $K_1$ 到位置 3 的第一个倾斜处，该电荷分布在 $C_x$ 和 $C_0$ 之间，并且公共电容器上的电压变得相等

$$U_1 = \frac{q_x}{C_x + C_0} = \frac{C_x U_0}{C_x + C_0}.$$

将$K_2$倾斜至位置5后，电容器$C_0$完全放电，电容器$C_x$上仍残留电荷

$$q_1 = C_x U_1 = \frac{C_x^2 U_0}{C_x + C_0}.$$

第二次倾斜 $K_2$ 到位置 4 后，电容器上的电压为

$$U_2 = \frac{q_1}{C_x + C_0} = U_0 \left( \frac{C_x}{C_x + C_0} \right)^2,$$

经过四种倾向之后——

$$U_4 = U_0 \left( \frac{C_x}{C_x + C_0} \right)^4.$$

让我们表示$\beta = C_x / (C_x + C_0)$，然​​后

$$\frac{U_4}{U_0} = \beta^4.$$

交换电阻并重复整个过程后，您可以编写类似于方程式（1）和（2）的方程式：

$$\frac{U_3}{U_0} = \frac{R_2}{R_1 + R_2},$$

$$\frac{U_3}{U_0} = \beta^3,$$

其中$U_3$是三次反转$K_2$后电容器$C_x$上的电压。从方程（1）和（3）我们得到

$$\frac{U_4}{U_0} + \frac{U_3}{U_0} = \frac{R_1}{R_1 + R_2} + \frac{R_2}{R_1 + R_2} = 1,$$

方法，

$$\beta^4 + \beta^3 = 1.$$

让我们绘制函数 (图 7)

$$y = \beta^4 \text{ и } y = 1 - \beta^3$$

从它们的交叉点我们发现

$$\beta \approx 0,82.$$

然后最后

$$C_x = \frac{\beta}{1 - \beta} C_0 \approx \frac{0,82}{1 - 0,82} \times 100 \text{ мкФ} \approx 450 \text{ мкФ}.$$

练习

1. 缠绕半径为 $r$ 的固定盘的螺纹形成半圆 (图 8)。线的一端固定在点$A$，线的另一端连接有重物，该重物固定在点$B$（点$A$和$B$位于同一垂直线上）。当重物到达其最高位置时，在某些时候重物会释放与圆盘接触？第三个是疏忽了。

2. doxa 位于半径为 $R$ (图 9) 的固定圆形半硅上。 Doxy 厚度$h$，长度$2l$，$R = h$。 doxa 可以从水平位置脱离到多大的最大角度 ($\varphi_{\pi p}$)，从而返回到其初始状态？摩擦力很大。假设半滑体位于无限水平面上且$2l/R = 4$，求doxa在与水平位置的最大偏差时是否返回到其初始状态。
