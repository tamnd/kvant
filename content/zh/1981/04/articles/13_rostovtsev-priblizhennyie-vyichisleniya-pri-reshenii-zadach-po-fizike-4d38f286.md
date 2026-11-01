---
id: 1981-4-rostovtsev-priblizhennyie-vyichisleniya-pri-reshenii-zadach-po-fizike-4d38f286
issue: kvant_1981_4
year: 1981
number: "4"
title: 解决物理问题时的近似计算
authors:
  - Ростовцев Н. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 44
page_labels: 40-42
tag: U2PI
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 588d5f2b5233b6ef804b4cc50b80dcd2ac5e57584b41b50e344470f8c51df0c0
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/13_rostovtsev-priblizhennyie-vyichisleniya-pri-reshenii-zadach-po-fizike-4d38f286.md
source_content_sha256: f26f600a2c36c4c33a2757acd962c21d7678de490c9ed0816d01b35314d031fa
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

解决物理问题时的近似计算

当开始解决任何物理问题时，首先必须找出哪些现象或过程发挥重要作用，哪些现象或过程发挥不存在的作用。忽视非本质现象必然导致忽视相对较小的量，即近似计算。了解近似计算公式以及使用它们的能力通常可以大大简化计算。

从数学课程可知，$|x|<1$处的表达式$(1+x)^n$可以表示为以下形式

$$(1+x)^n = 1 + nx + \frac{n(n-1)}{1 \cdot 2} x^2 + \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3} x^3 + \dots$$

这里$n$是任意实数。对于自然$n$，该和被转换为$n$次项；所得公式称为牛顿公式。

设表达式$(a+b)^n$，则由(1)

$$(a+b)^n = a^n \left(1 + \frac{b}{a}\right)^n = a^n \left(1 + n \frac{b}{a} + \frac{n(n-1)}{1 \cdot 2} \left(\frac{b}{a}\right)^2 + \dots\right).$$

如果$|b| \ll |a|$，包含$b/a$二次幂及更高次方关系的项，我们可以忽略并将自己限制为仅前两项：

$$(a+b)^n = a^n \left(1 + \frac{b}{a}\right)^n \approx a^n \left(1 + n \frac{b}{a}\right).$$

使用这个近似公式会出现什么错误？为了估计波浪，我们可以假设误差等于展开式中的第三项：

$$\Delta y = a^n \frac{n(n-1)}{1 \cdot 2} \left(\frac{b}{a}\right)^2.$$

在解决物理问题时，通常允许精度高达百分之一的计算。由式(3)可求出$b/a$的最大值，此时计算精度不超过允许尺寸。

三角函数值的近似计算公式非常简单方便。如果以半径表示的角度$α$足够小，则可以取

$$\sin α \approx α,$$

$$tg α \approx α,$$

$$\cos α \approx 1.$$

计算表明，当角度$α$满足条件时，误差不超过百分之一

$$α \leq 23° \approx 4.0 \cdot 10^{-1}$$

为罪感到高兴$α$，

$$α \leq 18° \approx 3.1 \cdot 10^{-1}$$

很高兴tg$α$，

$$α \leq 8° \approx 1.4 \cdot 10^{-1}$$

很高兴cos$α$。

（这可以使用 Bradis 表等进行检查。）

在物理学中，指数函数$y=a^x$很常见。对于$x$的小值，满足近似相等

$$a^x \approx 1 + \frac{\lg a}{0.43} x.$$

现在让我们考虑几个具体问题。

任务 1. 根据图 1 所示的图表，使用电流表和电压表改变导体的电阻$R$。电压表的电阻$R_V \gg R$。找出所犯的错误

⟦folio 41⟧

计算导体的电阻，而不考虑流过电压表的电流。

根据电流表和电压表的读数计算得出的导体电阻（不考虑电压表的电阻）等于

$$R' = \frac{U}{I},$$

其中$U$是电压表上的电压，$I$是流过电流计的电流。

真实电阻为

$$R = \frac{U}{I - I_V} = \frac{U}{I - U/R_V}.$$

您正在寻找的错误

$$\Delta R = R - R' = \frac{U}{I - U/R_V} - \frac{U}{I} = \frac{U}{I} \left( \left( 1 - \frac{U/R_V}{I} \right)^{-1} - 1 \right).$$

从$R_V \gg R$开始，然后$U/R_V \ll I$。应用公式(2)，我们得到

$$\Delta R = R - R' \approx \frac{U}{I} \left( 1 + \frac{U/R_V}{I} - 1 \right) \approx \frac{U^2}{I^2 R_V}.$$

任务 2. 当上升到距地球表面 $h = 1$ 公里的高度时，重力会发生多大的变化？地球半径被认为等于$R = 6400$公里。

地球表面质量$m$的引力等于

$$F_0 = G \frac{mM}{R^2},$$

其中$G$是万有引力常数，$M$是地球的质量。

当我们远离地球表面时，重力会减小，在高度 $h$ 处，重力等于

$$F_1 = G \frac{mM}{(R+h)^2}.$$

从$F_0$和$F_1$的表达式我们发现

$$\frac{F_0 - F_1}{F_0} = 1 - \frac{F_1}{F_0} = 1 - \frac{R^2}{(R+h)^2} = 1 - \frac{1}{(1+h/R)^2} = 1 - \left( 1 + \frac{h}{R} \right)^{-2}.$$

由于$h \ll R$，即$h/R \ll 1$，利用式(2)可得

$$\frac{F_0 - F_1}{F_0} \approx 1 - \left( 1 - 2 \frac{h}{R} \right) = 2 \frac{h}{R} \approx 3 \cdot 10^{-4}.$$

任务 3. 在相对能量理论中，分析

粒子 $E_k$ 使用公式 $E_k = E - E_0$ 计算，其中 $E$ 是运动粒子的能量，$E_0$ 是静止粒子的能量。证明当粒子速度为$v \ll c$（以光速）时，其动能近似为$m_0 v^2/2$，其中$m_0$是粒子静止时的质量。

根据相对能量理论

$$E = \frac{m_0 c^2}{\sqrt{1 - (v/c)^2}}$$ 和 $E_0 = m_0 c^2.$

从这里

$$E_k = E - E_0 = m_0 c^2 \left( \frac{1}{\sqrt{1 - (v/c)^2}} - 1 \right) = m_0 c^2 \left( \left( 1 - \frac{v^2}{c^2} \right)^{-1/2} - 1 \right).$$

由于$v \ll c$，即$v/c \ll 1$，因此$v^2/c^2 \ll 1$，应用公式（2），我们发现

$$E_k \approx m_0 c^2 \left( 1 + \frac{1}{2} \frac{v^2}{c^2} - 1 \right) = \frac{m_0 v^2}{2}.$$

任务 4. 物体从与地平线成 $\alpha = 7^\circ$ 角的斜面滑动。如果物体在平面上的摩擦系数为$\mu = 3 \cdot 10^{-2}$，求物体的加速度。

三个力作用在沿斜面运动的物体上：垂直向下的重力$m\vec{g}$，沿斜面向上的重力$\vec{F}_{\text{тр}}$，以及垂直于斜面的法向反作用力$\vec{R}$。我们将力投射到坐标轴$OX$和$OY$上，如图2所示，并写出运动方程：

$$mg \sin \alpha - F_{\text{тр}} = ma,$$

$$R - mg \cos \alpha = 0.$$

考虑到

$$F_{\text{тр}} = \mu R,$$

⟦folio 42⟧

从运动方程我们找到物体的加速度模块：
$$a = g(\sin \alpha - \mu \cos \alpha).$$

由于角度为$\alpha < 8^\circ$，我们可以利用公式（4）和（6）并假设$\cos \alpha \approx 1$和$\sin \alpha \approx \alpha$（角度$\alpha$必须用弧度表示）。代入值$\cos \alpha \approx 1$和$\sin \alpha \approx 1,2 \cdot 10^{-1}$，我们得到$a \approx g(1,2 \cdot 10^{-1} - 3 \cdot 10^{-2}) = 8,8 \cdot 10^{-1}$ m/s$^2$。

问题 5. 一克镭在 $t = 1$ 时间内衰变了多少个原子？镭的半衰期为$T = 1600$年。一克镭有 $N_0 = 2,6 \cdot 10^{21}$ 个原子。

如果初始时刻的放射性原子数为$N_0$，则根据放射性衰变定律，经过$t$时间后，未熔化的原子数$N$为

$$N = N_0 2^{-t}.$$

从这里我们可以找到衰变原子的异常编号$n$：

$$n = N_0 - N = N_0 (1 - 2^{-t}).$$

由于$t/T \ll 1$，应用公式(7)，我们得到

$$n \approx N_0 \left(1 - 1 + \frac{\lg 2}{0,43} \frac{t}{T}\right) \approx 3,7 \cdot 10^{10}.$$

请注意，放射性转换器的活度（其中 $3,7 \cdot 10^{10}$ 原子在 1 秒内衰变）被视为活度单位，称为 1 居里。

最后，简单说一下解决问题时的数值计算。记录问题的简要情况，以$a \cdot 10^n$（其中$1 \leq a < 10$）的形式表示所有数值是合理的，并且具有相同的精度。在绝大多数情况下，deve 的数量都很大。然后得到的结果也应该四舍五入到两位有效数字（例如，参见问题 4 的解决方案）。

练习

1. 计算公式$(1+a)^3 \approx 1+3a$和$\sqrt{1-a} \approx 1 - \frac{1}{2}a$的误差不超过0.01时$a$的最大值。

2. 黄铜的线性分布系数$a = 2 \cdot 10^{-5} \text{K}^{-1}$。由于温度升高$\Delta T = 10$ K，24 小时内带有黄铜磁铁的 Chistsy 会落后多远？

3. 确定距离地球 10 公里高度处的重力加速度，如果在地面上则等于 981 厘米/$^2$。地球半径为$R = 6400$公里。

4. 如果 $l \ll L$，则确定点 $B$ (图 3) 处精确电荷$+q$ 和 $-q$ 系统的场方向。

5. 一辆重$m = 2 \cdot 10^3$公斤的汽车从静止出发，上坡，矿井的坡度为$a = 0,02$。行驶了$s = 100$米的距离后，它的速度达到了$v = 32,4$公里/小时。运动阻力系数$k = 0,05$。确定自动机在该运动过程中产生的平均功率。

小宇宙

（关于开始，请参见第 8 页）

对参加竞赛最积极、最密集的学校、非学校机构、院校科技协会代表队，以及为青年技术和研究人员的工作提供有效帮助的企业、机构、大学的分部门和团队将获得荣誉证书，指导工作的教师、界别负责人、科学家和专家中的顾问将获得竞赛获奖者的证书和徽章。

有关比赛组织和进行的所有问题，请联系共青团中央委员会（莫斯科，New Square 6/8，电话：206-84-70、206-89-92）、俄罗斯联邦青年技术教育中央站（电话：289-75-44）、莫斯科皮诺耶尔城市宫殿（电话：139-89-54、 139-84-88）。
