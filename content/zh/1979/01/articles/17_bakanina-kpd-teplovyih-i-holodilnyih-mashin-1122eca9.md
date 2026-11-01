---
id: 1979-1-bakanina-kpd-teplovyih-i-holodilnyih-mashin-1122eca9
issue: kvant_1979_1
year: 1979
number: "1"
title: 热能和制冷机的效率
authors:
  - Баканина Л. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 54
page_labels: 50-52
tag: QEB7
lang: zh
source: kvant_digital
extraction: vision
content_sha256: ac6d89cb5b5fd38a7d0b01e5b33d7f8d20b88fbd274fa6cd5cd887722e28ec4f
prompt_sha256: draft-1
translated_from: content/ru/1979/01/articles/17_bakanina-kpd-teplovyih-i-holodilnyih-mashin-1122eca9.md
source_content_sha256: 5b7b193f1712fc018a02f627921af9dd2875ff46c3f0c691090517002bf044aa
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

热能和制冷机的效率

加热和制冷机器的效率是多少？能超过100%吗？让我们尝试回答这些问题。

要运行任何热机，您至少需要两个不同温度的储热器。接收较热的储热器（加热器）的热流，机器利用工作热量进行工作，但同时部分热量被分离到较冷的储热器（冰箱）。

热机的效率 η 等于机器所做的功 A 与其加热器接收的热量 Qₙ 之比：

$$\eta = \frac{A}{Q_н}.$$

根据热力学第一定律，

$$A = Q - \Delta U = (Q_н - Q_x) - \Delta U.$$

这里Qₓ是冰箱分离的热量；对于热机来说，环境服务），ΔU 是工质内能的变化。由于所有热机都以封闭循环运行 - 逆卡诺循环（该循环逆时针运行；参见 图 1），则

$$\varepsilon = \frac{T_x}{T_н - T_x}.$$

从该公式可以清楚地看出，ε 可以小于、大于或等于 100%。事实上，有能力建造一种其加热温差的制冷机

*) 您可以阅读更多相关内容，例如 S. Shamsha 和 E. Evenchik 的文章“卡诺循环”（«Kvant»，1977 年，第 1 期）。

⟦folio 51⟧

身体和冰箱之间的温度将大于、小于或等于冰箱的温度。

e 可以超过 100%，这一事实有时会引发一个问题：这是否违反了能量守恒定律？事实上，这与能量守恒定律并不矛盾。从被冷却的物体中获取的热量和从外部做功所消耗的能量根本不会相互转化，而是用于加热（通常在制冷机中这是环境）。

我们来看看一些具体的任务。

问题1.热机，小莫罗什的工作流体是1摩尔理想单原子气体，我们完成图2所示的循环。这台机器的效率被命名。

热机的效率等于

$$\eta = \frac{A}{Q_H}.$$

每个数值周期所做的功$A$等于坐标$p$、$V$所描绘的周期面积（参见图2）：

$$A = \frac{1}{2} p_0 V_0^2.$$

让我们找出气体在循环的哪些部分接收热量以及在哪些部分释放热量。让我们写下任意部分的热力学第一定律：

$$Q_i = \Delta U_i + A_i.$$

一摩尔理想单原子气体具有内能

$$U = \frac{3}{2} RT,$$

在哪里

$$\Delta U_i = \frac{3}{2} R \Delta T_i$$

每个部分内能的变化由温度的变化决定。功$A_i$在数值上等于循环相应部分下的面积。

使用理想气体状态方程 $pV = RT$，我们找到点 1、2、3 处的气体温度：

$$T_1 = \frac{p_0 V_0}{R}, \quad T_2 = \frac{2 p_0 \cdot 2 V_0}{R} = 4 T_1,$$

$$T_3 = \frac{p_0 \cdot 2 V_0}{R} = 2 T_1.$$

在第1-2段中，气体温度升高（$\Delta T_{12} > 0$），气体做正功（气体膨胀）；因此，气体在该区域接收热量。在部分 2-3 和 3-1 中，气体温度很高，在部分 2-3 中根本没有做功，在部分 3-1 中它是负值（气体被撇走，从外部做功） - 这意味着在这些部分中气体不接收热量。

因此，气体仅在第 1-2 部分接收热量：

$$Q_H = Q_{12} = \Delta U_{12} + A_{12} = \frac{9}{2} p_0 V_0 + \frac{3}{2} p_0 V_0 = 6 p_0 V_0.$$

然后最后

$$\eta = \frac{A}{Q_H} = \frac{1/2 p_0 V_0}{6 p_0 V_0} = \frac{1}{12} \approx 8^{0.0}.$$

问题2. 理想的制冷机有一个储存$0^\circ C$的水作为冰箱，一个储存沸水作为切割机。必须做哪些功才能将刀具变成蒸汽？ LVDA比热$\lambda = 340$kJ/kg，

⟦folio 52⟧

图 3.

水汽化比热$L = 2260$kJ/kg。

理想的制冷机按逆卡诺循环运行，其性能系数为

$$\varepsilon = \frac{T_X}{T_H - T_X} = \frac{273 \text{ K}}{100 \text{ K}} = 2,73.$$

1公斤水结冰时放出热量

$$Q_X = \lambda m = 340 \text{ кДж}.$$

完成的工作

$$A = \frac{Q_X}{\varepsilon} \approx 125 \text{ кДж}.$$

加热器将接收热量

$$Q_H = Q_X + A \approx 465 \text{ кДж},$$

因此，油会变成蒸汽。

$$m_1 = \frac{Q_H}{L} \approx 0,2 \text{ кг}.$$

问题3.上世纪中叶，天使物理学家汤姆森提出了所谓动态加热的想法。燃烧莫利沃的燃烧室充当热机的切割器；该机器的冰箱在加热系统中燃烧水。通过获得工作，我们将操作制冷机。对于制冷机，加热系统中的水用切割机燃烧，并用冷储备，从腔室中取出梅洛，并燃烧erunto水。假设两台机器都以理想循环运行并忽略测量，请确定当 1 千克摩尔被压缩时，加热系统中的水将接收多少摩尔。莫利夫燃烧比热$q$，热机僧侣中的温度$t_1 = 200^\circ\text{C}$，加热系统中的水温$t_2 = 60^\circ\text{C}$，erunto水的温度$t_3 = 10^\circ\text{C}$。

为了更清楚地想象汤姆逊的想法，我们画一个动态加热的图（图3）。

现在我们进行必要的计算。

这些机器是理想的，也就是说，它们按照卡诺循环工作。因此，热机的效率为

$$\eta = \frac{T_1 - T_2}{T_1} = \frac{140 \text{ K}}{473 \text{ K}} \approx 0,3,$$

性能系数

$$\varepsilon = \frac{T_3}{T_2 - T_3} = \frac{283 \text{ K}}{50 \text{ K}} \approx 5,7.$$

当1公斤燃料被丢弃在燃烧室中时，释放能量$Q_H = q$。热机所做的功等于

$$A = \eta Q_H = \eta q,$$

加热系统中传递的热量系数等于

$$Q_1 = q - A = (1 - \eta) q.$$

制冷机从地下水中获取热量系数

$$Q_X = \varepsilon A = \varepsilon \eta q.$$

供暖系统中的水接收热量系数

$$Q_2 = Q_X + A = \eta (1 + \varepsilon) q.$$

总共，加热系统中的水接收热量系数

$$Q = Q_1 + Q_2 = (1 + \varepsilon \eta) q \approx 2,7q.$$

因此，动态加热系统原则上（如果忽略损失）允许在加热系统中传输水，其热系数大于燃料燃烧期间燃烧室中释放的热系数！这里不是违反了热力学第一定律吗？绝不：“多余”的热量是从地下水中获取的。事实上，热量从地下水中被带走

$$Q_X = \varepsilon A = \varepsilon \eta q,$$

- 区分$Q$和$q$。

（结局见第54页）
