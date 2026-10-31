---
id: 1973-7-stolyarov-dvizhenie-zaryazhennyih-chastits-v-elektricheskom-pole-16d19785
issue: kvant_1973_7
year: 1973
number: "7"
title: 带电粒子在电场中的运动
authors:
  - Столяров И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 37
page_last: 43
page_labels: 35, 36, 37, 38, 39, 41
tag: GKHO
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9915bb8c6ad6ab96d67fdc9c0f0fd0d29e8a2030d7f8ca369bd26ea172ac880c
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/09_stolyarov-dvizhenie-zaryazhennyih-chastits-v-elektricheskom-pole-16d19785.md
source_content_sha256: 079c1cc8f256c6d5628880e853ed83797a0127ba2c896c5904487eaae98738f7
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

带电粒子在电场中的运动

物体运动的性质（其轨迹的类型、公式、物体的运动和速度对时间的依赖性的表达等）并不取决于作用在物体上的力的性质。它仅取决于该力如何依赖于身体的坐标和时间。因此，表面上不同的问题，其中力的依赖性（例如，对坐标的依赖性）是相同的，今天以相同的方式解决。这使我们能够在解决涉及电场中带电粒子运动的许多问题时，利用我们对其他“类比”场中物体运动的了解。

例如，考虑以下问题。

问题 1. 当考虑一个带有端到端扁平僧侣的房子时，水平均匀带电扁平电子速度等于 $v_0$，矢量$v_0$ 与垂直方向形成角度 a (图 1)。平面的电荷密度为$\sigma$。如果我们穿过平面，电子的轨迹是什么？当电子位于平面下方距离 b 时，电子的速度是多少？

图 1.

求解问题时，忽略重力和电子对沿线电荷分布的影响。

解决方案。一个非有限平面，表面电荷密度 $\sigma$ 均匀充电，产生一个方向均匀的场

$$E = \frac{\sigma}{2\varepsilon_0},$$

在板的上方和下方，矢量指向不同的方向。因此，在考虑电子运动时，分别考虑板上方和下方电子的运动是方便的。

在方向$E$的均匀电场中，恒定的力作用在电子上

$$F = eE,$$

（其中 $e = -1,6 \cdot 10^{-19} \text{ к} - \text{заряд электрона}).$ 该力向电子提供恒定的加速度

$$a = \frac{F}{m} = \frac{e}{m} E,$$

$$a = \frac{e}{m} E = \frac{e\sigma}{2\varepsilon_0 m}$$

（m 是电子质量）。但是，正如我们所知，随着粒子在地球表面附近运动的恒定加速度，重力可以被认为是恒定的。因此，在我们的例子中，电子的移动方式与从地球以与地平线成一定角度抛出的粒子的移动方式相同。特别是，这意味着电子的轨迹将是抛物线。更准确地说，不是抛物线，而是两条抛物线放在一起：

⟦folio 36⟧

一个在平面上方，另一个在平面下方。自由落体加速度 $g$ 的作用由加速度 $a$ 发挥。为了回答该问题的其他问题，我们需要考虑两种情况：a）极板带负电，b）极板带正电。

让我们考虑情况a)。在这种情况下，电场的方向矢量指向平面，而电子的加速度$a$指向远离平面。电子运动的几种可能的轨迹（对于不同的$\sigma$值）如图2所示。如果“自由落体”$a$的加速度很大，那么电子可能无法到达平面。由于电子初速度的垂直分量等于$v_y = v_0 \cos \alpha$，则其“上升”的最大高度$H$等于

$$H = \frac{v_y^2}{2a} = \frac{(v_0 \cos \alpha)^2}{2a} = \frac{(v_0 \cos \alpha)^2 \varepsilon_0 m}{\varepsilon \sigma}.$$

如果$H < d$，则意味着电子不应到达极板。在这种情况下，电子接近平面的最小距离为

$$h = d - H = d - \frac{(v_0 \cos \alpha)^2 \varepsilon_0 m}{\varepsilon \sigma}.$$

在$H = d$，电子轨迹接触平面，在$H > d$，电子将穿过平面。在电子运动轨迹板下方将有另一条抛物线。

因此，由于这里的加速度是远离板的，因此电子将始终远离它。

让我们看看电子将在什么时候穿过金属板以及此时的速度。为此，我们写下电子运动方程。构造了电子速度在 $X$ (图 2) 轴上的投影，并且等于 $v_x = v_0 \sin \alpha$。因此，电子的坐标$x$随时间按规律变化

$$x = v_x t = v_0 \sin \alpha \cdot t.$$ (4)

由于电子$a$的加速度沿着轴$Y$，因此坐标$y$随时间变化如下：

$$y = v_0 \cos \alpha \cdot t + \frac{at^2}{2}.$$ (5)

在时间$t = t_1$，电子穿过板、$y = y_1 = d$和$x = x_1$。将这些值$t$、$x$和$y$代入方程（4）和（5），我们得到：

$$x_1 = v_0 \sin \alpha \cdot t_1,$$

$$d = v_0 \cos \alpha \cdot t_1 + \frac{at^2}{2}.$$ (6)

求解这个方程组，我们发现

$$t_1 = \frac{-v_0 \cos \alpha + \sqrt{v_0^2 \cos^2 \alpha + 2ad}}{a}$$

$$x_1 = v_0 \sin \alpha \cdot \frac{-v_0 \cos \alpha + \sqrt{v_0^2 \cos^2 \alpha + 2ad}}{a}$$

*) 求解方程 (6) 的第二个，我们丢弃了 $t_1$ 的第二个较大的根。这个方程使我们能够确定频率坐标 $y$ 等于 $d$ 的时刻。如果板距离很远并且电子在运动过程中没有穿过它，那么这个值$y$将重复两次：第一次是电子“上升”时，第二次是电子“下降”时。电子“返回”过程中坐标$y = d$的值对应于$t_1$的二阶根，等于

$$-v_0 \cos \alpha - \sqrt{v_0^2 \cos^2 \alpha + 2ad}$$

⟦folio 37⟧

在 $H = d$ ($2ad = -v_0^2 \cos^2 \alpha$) 处，电平面的轨迹在点 $x_2 = -\frac{v_0^2 \sin \alpha \cos \alpha}{a} = -\frac{v_0^2 \sin 2\alpha}{2a}$ 处接触板。这是与地平线成一定角度的物体飞行距离的一半。

为了求出电子在任何时刻的速度，你只需要求出此时它的速度的垂直分量$v_y$，从$v_x = \text{const}$开始。值$v_y$根据公式随时间变化

$$v_y = v_0 \cos \alpha + at.$$

时间$t = t_1$

$$v_y = v_0 \cos \alpha + at_1 = \sqrt{v_0^2 \cos^2 \alpha + 2ad}.$$

此时电流的速度为

$$v_1 = \sqrt{v_x^2 + v_y^2} = \sqrt{v_0^2 + 2ad} = \sqrt{v_0^2 + \frac{e\sigma d}{\varepsilon_0 m}}.$$

为了找到电的速度，可以进行不同的计算——利用物体动能的变化始终等于作用在物体上的力所做的功这一事实。这意味着

$$\frac{mv_1^2}{2} - \frac{mv_0^2}{2} = Eed.$$

从这里

$$v_1 = \sqrt{v_0^2 + \frac{2Eed}{m}} = \sqrt{v_0^2 + \frac{e\sigma d}{\varepsilon_0 m}}.$$

该速度是在垂直角度 $\beta$ 处得出的，使得

$$\sin \beta = \frac{v_x}{v_1} = \frac{v_0}{\sqrt{v_0^2 + \frac{e\sigma d}{\varepsilon_0 m}}} \sin \alpha.$$

同理，可求出当电极位于板下方且距离板$b$时，其速度为$v'$。由于在板下方，作用在电镀上的力

让我们解决另一个明显的分布问题。

问题 2. 我们将一个电子以 $v_0$ 的速度放入扁平电容器的中间，方向平行于电容器的极板。电容器极板之间的距离为$d$，极板长度为$L$。如果电容器被充电到交换之间的差$U$，则相对于第一个初始运动方向，电子将从电容器扫走多少距离$l$？当由电容器制成时，$v$ 电的速度是多少？借柔之力，假装。

解决方案。电容器场是均匀的。因此，电的内部电容器的移动方式与地平线抛出的物体的移动方式相同。

⟦folio 38⟧

在均匀重力场中进行计数。自由落体加速度沿 $Y$ (图 4) 轴方向，等于

$$a = \frac{eE}{m} = -\frac{e}{m} \frac{U}{d} (E < 0).$$

电子沿 $X$ 轴以恒定速度 $v_x = v_0$ 移动。因此，一段时间后电子就会飞出电容器

$$t = \frac{L}{v_0}.$$

这段时间他沿着$Y$轴笑向远方

$$l = \frac{at^2}{2} = -\frac{1}{2} \frac{eU}{md} \left(\frac{L}{v_0}\right)^2.$$

电子离开电容器时的速度可使用能量守恒定律求得：

$$\frac{mv^2}{2} - \frac{mv_0^2}{2} = Eel,$$

$$v = \sqrt{v_0^2 + \frac{2Eel}{m}} = \sqrt{v_0^2 + \left(\frac{eUL}{mdv_0}\right)^2}.$$

速度矢量 $v$ 与矢量 $v_0$ 的方向形成角度 $\beta$，使得

$$\cos \beta = \frac{v_0}{v} = \frac{v_0}{\sqrt{v_0^2 + \left(\frac{eUL}{mdv_0}\right)^2}}.$$

正如你所看到的，带电粒子在凝结中的运动问题

$$F = \frac{1}{4\pi\varepsilon_0} \frac{Qq}{r^2},$$

其中$r$是电荷之间的距离。该力沿着连接电荷的线定向，并为电荷提供加速度 $q$

$$a = \frac{1}{4\pi\varepsilon_0} \frac{Qq}{r^2 m}$$

（$m$ 是电荷质量$q$）。

力$F$与电荷之间距离的平方成反比。但万有引力的强度也取决于距离。这意味着，在固定精确电荷的场中，带电粒子的运动方式与物体在距接收中心较远的引力场中运动的方式相同——圆形、椭圆形、抛物线或双曲线，具体取决于粒子的速度。

考试中可能遇到的绝大多数问题，运动的轨迹都是圆形。这些问题需要以与任何其他涉及物体圆周运动的问题相同的方式来解决 - 写出运动方程（P.牛顿定律方程），利用这样的事实：当物体以速度 $v$ 在半径 $R$ 的圆上运动时，其向心加速度等于

$$a = \frac{v^2}{R}.$$

让我们看一个例子。

问题 3. 在氢原子的玻尔-卢瑟福模型中，电子沿着圆周愈合

⟦folio 39⟧

图 5.

带正电的原子核。核电荷$|e|$。如果氢原子的半径为 $r = 0,5 \cdot 10^{-10}$ m，请确定原子中电子的速度和加速度。

解决方案e.让我们写出电子运动方程：

$$\frac{1}{4\pi\varepsilon_0} \frac{e^2}{r^2} = m \frac{v^2}{r},$$

其中$m$是电子的质量，$v$是电子的速度。从这里我们会发现

$$v = \sqrt{\frac{1}{4\pi\varepsilon_0} \frac{e^2}{mr}} \approx 2,2 \cdot 10^6 \text{ m/c.}$$

$$a = \frac{v^2}{r} \approx 9,7 \cdot 10^{22} \text{ m/c}^2.$$

问题 4. 两个相同的强大电荷 $q$ 在半径为 $R$ 的圆周上围绕电荷 $Q$ 移动。在这种情况下，电荷 $q$ 位于单带直径 (图 5) 的末端。电荷的指定速度$q$以及电荷的总动能与瞬时动能之比。

解决方案。费用$Q$和$q$必须有不同的图标，否则费用$q$会飞散。每个电荷 $q$ 都受到一个力的作用

$$F = \frac{1}{4\pi\varepsilon_0} \left( \frac{Qq}{R^2} - \frac{q^2}{(2R)^2} \right).$$

该力赋予每个电荷一个等于$\frac{v^2}{R} = \omega^2 R$的向心加速度，其中$\omega$是电荷的角速度。这就是为什么

$$\frac{1}{4\pi\varepsilon_0} \left( \frac{Qq}{R^2} - \frac{q^2}{(2R)^2} \right) = m\omega^2 R.$$

从这里

$$\omega = \sqrt{\frac{1}{4\pi\varepsilon_0} \left( \frac{Qq}{R^2} - \frac{q^2}{4R^2} \right)} \frac{1}{mR} =$$

$$= \frac{1}{4R} \sqrt{\frac{1}{\pi\varepsilon_0 mR}} \left( 4Qq - q^2 \right).$$

系统的动能是电荷$q$动能之和：

$$W_{\text{киин}} = 2 \frac{mv^2}{2} = m(\omega R)^2 =$$

$$= \frac{1}{16\pi\varepsilon_0 R} \left( 4Qq - q^2 \right).$$

系统的势能在数值上等于将$q$从无穷远变换到距电荷$Q$距离$R$所需的功。要重新定义电荷$Q$领域中的一种电荷，需要执行工作

$$A_1 = -\varphi \cdot q = -\frac{1}{4\pi\varepsilon_0} \frac{Q}{R} q,$$

（f 是距离电荷 $R$ 的电荷场 $Q$ 的电势），并且要重新建立第二个电荷（电话已经在电荷场 $Q$ 和 $q$ 中），有必要做功

$$A_2 = -\frac{1}{4\pi\varepsilon_0} \frac{Q}{R} q + \frac{1}{4\pi\varepsilon_0} \frac{q}{2R} q.$$

系统的波斯尼势能等于

$$W_{\text{пот}} = A_1 + A_2 =$$

$$= \frac{1}{4\pi\varepsilon_0} \left( \frac{q^2}{2R} - 2 \frac{Qq}{R} \right),$$

和

$$\frac{W_{\text{киин}}}{W_{\text{пот}}} = -\frac{1}{2}.$$

问题 5. 质量为 $m$ 的带电粒子在椭圆轨道 (图 6) 上围绕电荷 $Q$ 运动。粒子的电荷为$q$。电荷$Q$与粒子之间的最小距离为$r$，最大为$R$。绕着电荷$Q$转一圈需要$T$需要多长时间？

解决方案。电荷 $Q$ 作用在来自电荷的粒子上的力

⟦folio 41⟧

距离它 $l$ 处有电荷 $+q$ (图 7)。电荷$q$被释放。他能达到的最大速度是多少？

解决方案。电荷 $q$ 受到两种力的作用 - 力 $F_1$ 与电荷 $Q$: $F_1 = \frac{1}{4\pi\varepsilon_0} \frac{Qq}{x^2}$ 相互作用（x 是电荷之间的距离），以及力 $F_2$ 与场 $E$ 相互作用：

$$F_2 = Eq.$$

如果在初始时刻$F_1 > F_2$，即$\frac{1}{4\pi\varepsilon_0} \frac{qQ}{l^2} > Eq$，则电荷$q$释放后，它会向右移动，如果$F_1 < F_2$则向左移动。为了确定这种情况，让我们考虑情况$F_1 > F_2$。多重作用力 $F_1$ 和 $F_2$ 向装药 $q$ 提供加速度 $a = \frac{F_1 + F_2}{m}$，方向为沿着力 $F_1$ ($a = \frac{F_1 - F_2}{2}$) 的作用线运动开始。 $F_2$ 力并不取决于炸药的位置，但 $F_1$ 力会随着炸药之间距离的增加而产生杀伤力。当震级为 $F_2$ 时，多重作用力 $F_1$ 和 $F_2$ 将指向冲锋 $Q$ 并导致冲锋 $q$ 的速度降低。显然，充电速度$q$在$F_1 = F_2$时最大，即当

$$\frac{1}{4\pi\varepsilon_0} \frac{Qq}{x^2} = Eq.$$

此时电荷$q$和$Q$之间的距离为

$$x_1 = \sqrt{\frac{Q}{4\pi\varepsilon_0 E}}.$$

为了及时找到此时的充电速度$q$，我们使用能量守恒定律：

$$-\Delta W_{\text{пот}} = \Delta W_{\text{кини}}$$

或者

$$(\varphi_1 - \varphi_2)q = \frac{mv^2}{2},$$

其中$\varphi_1$、$\varphi_2$是点$x = l$和$x = x_1$的势。但

$$\varphi_1 - \varphi_2 = -E(x_1 - l) +$$

图 7.

$$+\left(\frac{Q}{4\pi\varepsilon_0}l - \frac{Q}{4\pi\varepsilon_0 x_1}\right) =$$

$$= (x_1 - l)\left(-E + \frac{Q}{4\pi\varepsilon_0 x_1}\right) =$$

$$= \left(\sqrt{\frac{Q}{4\pi\varepsilon_0 E}} - l\right)\left(-E + \frac{1}{l}\sqrt{\frac{QE}{4\pi\varepsilon_0}}\right).$$

因为

$$v = \sqrt{\frac{2q}{m}\left(\sqrt{\frac{Q}{4\pi\varepsilon_0 E}} - l\right)} \times \sqrt{\left(-E + \frac{1}{l}\sqrt{\frac{QE}{4\pi\varepsilon_0}}\right)}.$$

练习

1. 如果数学矩阵的质量球$m$带有电荷$q$，并且将磁铁置于强度$E$（场垂直或水平）的均匀电场中，则数学矩阵的振荡周期会改变多少次？
2. 彼此相距$l_1 = 5$厘米的质子以多大的最小相对速度才能相互接近$l_2 = 10^{-4}$厘米的距离？
3. 平板电容器的其中一个极板之间距离为 $d = 10$ mm 的极板被 RENT 射线“照射”，以 $v = 10^6$ m/s 的速度从其中撕裂出光电子。电子被收集在第二块板上。如果每秒有 $n = 10^{13}$ 个电子从极板的每平方厘米中喷射出来，光流需要多长时间才能停止？
4. 在半径为$R$的带电固定球体中，有一个小孔，电荷$q$通过该小孔飞入其中，并沿球体的半径移动。如果距球体 $l$ 的距离为 $v$，且球体的电荷为 $Q$，则该电荷在球体中心的速度是多少？
