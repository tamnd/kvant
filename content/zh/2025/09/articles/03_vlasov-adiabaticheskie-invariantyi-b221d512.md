---
id: 2025-9-vlasov-adiabaticheskie-invariantyi-b221d512
issue: kvant_2025_9
year: 2025
number: "9"
title: 绝热不变量
authors:
  - Власов А. И.
rubric: osnovnye-stati
page_first: 4
page_last: 12
page_labels: 3, 5, 7, 9, 9, 10
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 587fe22b0e880c1434a2d0845f6afb4e52d94cc31ef24b5260fa29f5f0879d09
prompt_sha256: draft-1
translated_from: content/ru/2025/09/articles/03_vlasov-adiabaticheskie-invariantyi-b221d512.md
source_content_sha256: 090262fa8d89ce36d16537db7064403fca2aede39338fdedf1e60bffe9125784
translation_model: draft
translation_run: zh-draft-2026-11-05
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

管理不变量
弗拉索夫

希望这有意义
“绝热”和“不变”这两个词的理解
高中生十个，并且支持
我们先来描述一下它的出现历史
“绝热不变量”的概念和研究
受到伟大物理学家和数学家的启发，
致力于解决这个非常美丽的问题——
嗯。让我们从简单的任务开始，其主题是
问题和解决方法将是我们的新
绝热问题的基本介绍
第一个不变量。我们先来看看
让我们试着去理解。数学问题是——
孩子不是很复杂，但假设有任意知识和计算最简单积分的能力。我们将得到一台电脑
请帮助我们检查并提供解决方案的图解说明。
一开始这是一个非常简单的任务。
任务 1. 非常缓慢但坚定
小冰球沿着主冰球运动
水平面有限
两个垂直的墙（图1）。

图 1

左边的墙会堆积，右边的墙会堆积
以常数开始向左移动
速度明显低于第一次
冰球的初始速度 (u << v₀)。确定如果壁之间的距离减小成凹槽，则垫圈的动能变化多少次？所有影响都是完全弹性的。

让我们确定下一次击球时冰球速度的变化。让我们移动到移动墙的坐标系。冰球以速度 (v + u) 接近墙壁

并以相同的模量去除速度（绝对弹性冲击后）。恢复固定缺勤制度
导致结果

Δv = 2u.

下一次打击会在一段时间后到来
（如果我们考虑速度和显示的变化
站在小墙之间
等级）

τ = $\frac{2x}{v}$.

在时间间隔 Δt 内，这是显着的
比时间 τ 长，壁面移动了少量 Δx，经历了更多次数的冲击
沟渠Δn。大约考虑 τ 的值
恒定值，我们得到

Δx = uΔt, Δt = $\frac{\Delta x}{u}$, Δn = $\frac{\Delta t}{\tau}$ = $\frac{\Delta x}{u}$ $\frac{v}{2x}$.

这段时间的速度变化

Δv = - $\frac{\Delta xv}{u \cdot 2x}$ · 2u.

这里的减号表明当
增加壁之间的距离 (Δx > 0)，速度会降低，并且当
随着距离的减小，速度会增加。从最后的关系我们发现
在系统“卷起”的过程中：

Δvx + Δxv = 0, Δ(vx) = 0, vx = inv.

利用这个不变量，很容易获得问题的答案。我们写出不变量的方程（守恒定律）：

v₀x₀ = vx,

在哪里

v = v₀ $\frac{x_0}{x}$ = nv₀ → $\frac{E_K}{E_{0K}} = n^2$.

⟦folio 3⟧

---
running_head:
folio:
---

请注意，所得的不变量可以用能量和运动周期来表示：
$$vx = inv \rightarrow px = inv \rightarrow E\tau = inv.$$
看看同相运动的电脑图片（图2）很有趣

图 2
空间（坐标和脉冲的空间是理论振荡的凹槽空间）。为了说明墙的运动，它做得很快。在 10 个移动周期内，墙壁之间的距离减少了一半。一周期运动的相轨迹是一个矩形，其面积（$S = mv_0x_0 = 2$）根据发现的不变量保持恒定。
以下问题的历史与伟大物理学家的名字有关：瑞利、洛伦兹、爱因斯坦。

问题 2. 瑞利-洛伦兹摆
洛伦兹提出考虑对一种不太寻常的磁体造成损坏的问题：用两个手指夹住悬挂负载的螺纹；通过沿着线在垂直方向上缓慢移动它们，您可以改变磁铁的长度，从而改变它的周期。振动能量会发生什么变化？根据洛伦兹的说法，爱因斯坦的答案几乎立即出现：系统的能量将与振荡频率成比例地变化。尝试解决这个问题，看看这位伟大物理学家的天才。

我们将用一个光滑的小环代替“洛伦兹手指”，通过它会有

数学矩阵的线索已经缝合（图3）。该环非常缓慢地向下移动，减少了矩阵悬架的“工作”部分。为了完全解决这个有趣的问题，我们获得了一个动态振动方程，其值对于计算机建模是必要的。笛卡尔坐标与偏差角之间的关系为
$$x = l\sin\varphi, y = l(1 - \cos\varphi).$$
相对于时间的导数（我们假设螺纹的长度以速度$u$均匀变化）：
$$x' = l'\sin\varphi + l\cos\varphi \cdot \varphi',$$
$$y' = l'(1 - \cos\varphi) + l\sin\varphi \cdot \varphi',$$
$$x'' = 2l'\cos\varphi \cdot \varphi' - l\sin\varphi \cdot \varphi'' + l\cos\varphi \cdot \varphi'',$$
$$y'' = 2l'\sin\varphi \cdot \varphi' + l\cos\varphi \cdot \varphi'' + l\sin\varphi \cdot \varphi'.$$
笛卡尔坐标系中的直径方程：
$$m\left(2l'\cos\varphi \cdot \varphi' - l\sin\varphi \cdot \varphi'' + l\cos\varphi \cdot \varphi''\right) = -T\sin\varphi,$$
$$m\left(2l'\sin\varphi \cdot \varphi' + l\cos\varphi \cdot \varphi'' + l\sin\varphi \cdot \varphi''\right) = T\cos\varphi - mg.$$
求解该系统后（我们将第一个方程乘以 cosφ，将第二个方程乘以 sinφ 并相加），我们得到角动态方程：
$$\varphi'' = -\frac{g}{l_0 - ut}\sin\varphi - 2\frac{u\varphi'}{l_0 - ut}.$$
该微分方程是非线性的（罪魁祸首是正弦）。对于小波动，它被简化：
$$\varphi''(t) = -\frac{g}{l_0 - ut}\varphi - 2\frac{u\varphi'}{l_0 - ut}.$$
但对于小学生来说，其解决方案（interriated）是困难的。让我们来解决这个困难。

⟦folio none⟧

---
running_head:
folio:
---

当缓慢降低（或握住）挂钉时，需要一个力，该力的垂直分量的大小由线的张力和其偏离垂直方向的角度（图5）决定：

$$F = T (1 - \cos \varphi) \approx T \frac{\varphi^2}{2}$$

在小偏转角度下，振动是和谐的：

$$\varphi = \varphi_0 \sin \omega t$$

$$F = T \frac{\varphi_0^2}{2} \sin^2 \omega t = T \frac{\varphi_0^2}{4} (1 - \cos 2\omega t).$$

显然，振荡周期内力的平均值等于（考虑到小振荡$T \approx mg$且余弦内积为0的事实）

$$\bar{F} = mg \frac{\varphi_0^2}{4}$$

移动环所做的功等于振动能量的变化。这种微分形式的等式具有以下形式

$$mg \frac{\varphi_0^2}{4} (-dl) = dE.$$

Delimm 是振动势能 $E = mgl \frac{\varphi_0^2}{2}$ 振幅的方程：

$$-\frac{1}{2} \frac{dl}{l} = \frac{dE}{E}$$.

积分后我们得到不变量：

$$E \sqrt{l} = inv.$$

考虑到振荡周期公式$T = 2\pi \sqrt{\frac{l}{g}}$和公式$T = \frac{2\pi}{\omega}$，不变量可以写成爱因斯坦预测的形式

$$ET \rightarrow \frac{E}{\omega} = inv.$$

现在 - 相空间振荡的传统图像。在矩阵长度恒定的情况下，振动能量守恒。小振幅振荡的守恒定律由以下公式表示（角度变量 $p_\varphi = ml^2\varphi'$ –

⟦folio 5⟧

---
running_head:
folio:
---

摆球相对于悬挂点的动量矩）
$$E = m l^2 \frac{\varphi'^2}{2} + m g l \frac{\varphi^2}{2}.$$
该表达式可以转换为椭圆方程的规范形式：
$$\frac{p^2_\varphi}{2 m l^2 E} + \frac{\varphi^2}{2 E/(m g l)} = 1.$$
得到一个椭圆：
$$a = \sqrt{\frac{2 E}{m g l}}, b = \sqrt{2 m l^2 E}.$$
最有趣的是椭圆曲线所包围的面积的值，它等于不变量：
$$S = \pi a b = E \cdot 2 \pi \sqrt{\frac{l}{g}} = E T = inv.$$
图 6 显示了五次振荡的相位轨迹。改变时
$$\varphi_k$$
摆的长度，轨迹不再是封闭的。这里，为了清楚起见，摆的长度的变化率变大。在这些振荡过程中，钟摆的长度减半。但即使摆的长度以这样的速率变化，在运动期间（被线扫过的区域）的大小也是不变量。
现在是绝热sorriz 的问题。
问题3.质量不稳定会导致什么？
水平弹簧摆的载荷是一个装有液体的圆柱形容器（图7；容器的体积被垂直隔板划分，以防止液位波动）。弹性系数

图 7
弹簧等于 k。我们进行浅垂直运动，盛有水的容器的质量以非常低的恒定质量速度 μ 增加。在初始时刻，振荡速度的幅度等于v0，盛有液体的容器的质量等于m0。确定时间 t >> T 之后摆锤振荡的参数（周期、振幅）。如果质量以相同的速度 μ 缓慢减小（没有原因通过容器侧面的小开口蒸发或泄漏），结果会如何变化？

为了推导不变量，使用动力学和能量方程：
$$-k x = \frac{d}{dt} (m v) = \mu v + m \frac{d v}{d t},$$
$$E = m \frac{v^2}{2} + k \frac{x^2}{2}.$$
让我们写出能量变化：
$$\frac{d E}{d t} = \mu \frac{v^2}{2} + m v \frac{d v}{d t} + k x v.$$
使用动力学方程，我们去掉 kx：
$$\frac{d E}{d t} = \mu \frac{v^2}{2} + m v \frac{d v}{d t} - \left(\mu v + m \frac{d v}{d t}\right) v.$$
变换后我们得到
$$\frac{d E}{d t} = -\mu \frac{v^2}{2}.$$
盛有液体的容器在单独的振荡周期内的速度可以认为是根据调和定律变化的：
$$v = v_0 \sin \sqrt{\frac{k}{m}} t.$$
让我们将这个表达式代入能量变化的公式中：
$$d E = -\mu dt \frac{v_0^2}{2} \sin^2 \sqrt{\frac{k}{m}} t =$$
$$= -\mu dt \frac{v_0^2}{2} \cdot \frac{1}{2} \left(1 - \cos 2 \sqrt{\frac{k}{m}} t\right).$$

⟦folio 7⟧

---
running_head:
folio:
---

相空间（图9）中振荡的计算机轨迹表明，椭圆的面积不守恒（它与质量成比例减小，相轨迹“收缩”）。问题3的解是合法的。

现在我们可以回到“绝热不变量”这个话题了。所考虑的例子证明以下定律是正确的。存在一个周期性过程模式的物理系统，其周期$T$由参数$\lambda$决定。随着该参数 ($\frac{d\lambda}{dt} T \ll \lambda$) 的缓慢变化，对于这样的系统，可以存在所谓的绝热不变量，其值由沿相轨迹一个周期的轮廓的间隔确定：

$$I = \frac{1}{2\pi} \oint pdq.$$

这里$p$和$q$分别是一维系统运动时的广义动量和广义坐标。当参数$\lambda$改变时，相轨迹不再闭合。该间隔（下文中称为相位不变量）在常数 $1/(2\pi)$ 范围内等于半径矢量旋转相位角 $2\pi$ (图 10) 时所扫过的面积。对于简谐振动的系统，不变量可以用一个公式来表示，我们称之为爱因斯坦公式：

$$\frac{E}{\omega} = ET = inv.$$

但人们必须谨慎对待标准不变量存在的信念。具有蒸发质量的武器矩阵问题表明了这一点，其中参数（质量）在不受外部影响的情况下发生变化。

“绝热不变量”这个名称是由 Ehrenfest 提出的。这个名字的原因不仅是因为该过程缓慢，而且相应地也因为该过程的平衡。绝热过程是没有外部传热的过程。量子热力学系统的平均能量可以写成可能能态 $E_i$ 的概率 $p_i$：

$$\bar{E} = \sum_{i=1}^{N} E_i p_i.$$

根据热力学第一定律，能量差分解为两个总和：

$$d\bar{E} = \sum_{i=1}^{N} dE_i p_i + \sum_{i=1}^{N} E_i dp_i = \delta A + \delta Q.$$

这表明“热量”（第二项）负责改变能级的概率，而“功”（第一项）的存在导致能谱的变化。

在绝热过程中，系统不会改变其量子态。不变量（除了第一相之外）是确定量子态的参数。瑞利的弦不变量问题很好地说明了这一点。

问题 4. 瑞利弦

让琴弦在第二模式下进行小幅振动。弦的长度等于波长（二

⟦folio 9⟧

---
running_head:
folio:
---

波腹； 图11）。绳子的左端穿过一个环（绳子的直径略小于环的内径）。环沿着 x 轴非常缓慢地向右移动，改变了绳子长度所做的功。确定当弦长加倍时振动幅度的变化。考虑以下已知量：$\rho$ - 琴弦的线密度，$f$ - 琴弦张力，$y_0$ - 初始振动幅度。

我们先来说说重要的。随着弦长度的绝热变化，其振荡（频率和可能的振幅发生变化）将保持在第二个模型的模式中。数字 $n = 2$ 将是一个不变量。

现在我们给出瑞利不变量的证明（定义）。让我们回顾一下弦振动物理学的基本公式。 $n$模式下的波速、波长、振荡周期分别相等
$$v = \sqrt{\frac{f}{\rho}}, \lambda = 2 \frac{l}{n} = v T, T = 2 \frac{l}{n} \sqrt{\frac{\rho}{f}}.$$
弦点的振动（模型状态$n$）由坐标和时间的函数描述：
$$y(x,t) = y_0 \sin \frac{n\pi}{l} x \cdot \sin \frac{2\pi}{T} t.$$
移动（或保持）环的力取决于绳子在 0 点的倾斜角度，而该角度取决于时间。对于小幅波动
$$F(t) = f\left(1 - \cos \varphi(t)\right) \approx f \frac{\varphi^2}{2}.$$
振动周期内力的平均值（我们认为小振动时弦张力是恒定的）：
$$\bar{F} = f \frac{\varphi^2}{2}.$$
倾斜角度任意确定（在$x = 0$）：
$$tg\varphi = \frac{dy}{dx} \approx \varphi(t) = y_0 \frac{n\pi}{l} \cos \frac{n\pi}{l} x \cdot \sin \frac{2\pi}{T} t = y_0 \frac{n\pi}{l} \sin \frac{2\pi}{T} t.$$
偏差角平方平均值：
$$\bar{\varphi}^2 = \frac{\varphi_0^2}{2} = \frac{1}{2}\left(y_0 \frac{n\pi}{l}\right)^2.$$
因此，平均强度为：
$$\bar{F} = \frac{f}{4}\left(y_0 \frac{n\pi}{l}\right)^2.$$
移动环时的基本工作（“减”考虑了长度的减少）：
$$dA = dE = -\frac{f}{4}\left(y_0 \frac{n\pi}{l}\right)^2 dl.$$
接下来我们需要振动能量的公式。弦元素的动能：
$$dE = \rho dx \frac{y'^2}{2} = \frac{\rho dx}{2}\left(y_0 \cdot \frac{2\pi}{T} \sin \frac{n\pi}{l} x \cdot \cos \frac{2\pi}{T} t\right)^2.$$
沿坐标 $x$ 插入得到
$$E(t) = \frac{\rho}{2}\left(y_0 \cdot \frac{2\pi}{T}\right)^2 \frac{l}{2} \cos^2 \frac{2\pi}{T} t.$$
动能的幅值为余弦平方前面的集合，即
$$E_0 = \frac{\rho}{2}\left(y_0 \cdot \frac{2\pi}{T}\right)^2 \frac{l}{2}.$$
我们将基本功除以能量振幅并得到微分方程
$$\frac{dE}{E} = -\frac{n^2}{4} \frac{fT^2}{\rho l^3} dl.$$
代入周期方程的平方：
$$\frac{dE}{E} = -\frac{dl}{l}.$$

⟦folio 9⟧

---
running_head:
folio:
---

积分后我们得到瑞利（爱因斯坦）不变量：
$$El \rightarrow ET \rightarrow \frac{E}{\omega} = inv.$$
通过将周期代入能量振幅即可找到问题的答案：
$$E = \left( \frac{\pi}{2} y_0 \right)^2 \frac{f}{l} n^2 \rightarrow El = \left( \frac{\pi}{2} y_0 \right)^2 fn^2 = inv.$$
令人惊讶的是，随着弦长度的缓慢（绝热）变化，振荡模式（量子数$n$）和振荡幅度得以保留。相轨迹非常令人惊讶。形式上，偶模态的弦的总动量为零，因此应该确定由两个连续节点限制的区域的相轨迹。这种振荡区域的动量等于
$$p(t) = \rho \int_0^{l/n} y(x,t) dx = \rho y_0 \cdot \frac{2\pi}{T} \cos \left( \frac{2\pi}{T} t \right) \cdot \int_0^{l/n} \sin \left( \frac{n\pi}{l} x \right) dx.$$
经过积分变换，得到振荡区的冲量：
$$p(t) = 2ny_0 \sqrt{\rho f} \cos \frac{2\pi}{T} t.$$
脉冲的幅度与振荡的幅度成正比，因此它也是不变的。因此，弦振荡区的相轨迹不会随着其长度的缓慢减小而改变，仍然是一个简单的闭合椭圆曲线。
现在是非简谐振荡系统的绝热不变量的另一个例子（第一个问题中考虑了最简单的例子）。让我们将其视为 Ehrenfest 的一个示例（非线性主题在他的一部作品中进行了讨论）。
问题 5. 抗引力子蚱蜢
垂直的“重力蚱蜢”采用图12中的设计进行倾斜。光滑的斜面有一个较低的部分反映了台阶。一个小球会周期性地垂直运动，从这一步中产生弹性反射。在最初的那一刻

⟦folio 10⟧

---
running_head:
folio:
---

60°克隆，得到如下结果：相对振幅立方的理论值等于
$$\left(\frac{H}{h}\right)^3 = \frac{1}{\cos \varphi} = 2.$$
计算机返回一个二，小数点后三个零：2,000。
如果我们不怀疑绝热不变量的存在（或者根本不知道它是什么），那么我们将不得不解决能量问题。让我们写下振荡平面小角度旋转的基本功值（在球与反射点距离$x$的某个时刻）：
$$dA = -mg \sin \varphi \cdot xd\varphi.$$
这里的“负”对应于转弯时角度的减小。让我们在运动期间取该值的平均值（我们假设偏差角度是恒定的，因为飞机的旋转速度非常小）。已知重力蚱蜢的时间平均高度为$\bar{x} = (2/3)h$（这很容易证明）。考虑到这个值，
$$d\bar{A} = -\frac{2}{3}mg \sin \varphi \cdot hd\varphi.$$
这项功等于球最大势能的变化：
$$-\frac{2}{3}mg \sin \varphi \cdot hd\varphi = d(mgh \cos \varphi) = mg(dh \cos \varphi - h \sin \varphi \cdot d\varphi),$$

或者
$$3 \frac{dh}{h} = \frac{\sin \varphi}{\cos \varphi} d\varphi.$$
这个方程很容易积分：
$$3 \int_H \frac{dh}{h} = \int_0^0 \frac{\sin \varphi}{\cos \varphi} d\varphi,$$
$$3 \ln \frac{h}{H} = \ln \cos \varphi.$$
结果，我们得到公式(*)。
现在让我们看看这种绝热周期运动 (图 14) 的相轨迹，它遵循以下方程
$$E = mg \cos \varphi \cdot H \left(\frac{\cos \varphi_0}{\cos \varphi}\right)^{1/3} = \frac{p^2}{2m} + mg \sin \varphi \cdot y,$$
或者
$$p = \pm m \sqrt{2gH \left((\cos \varphi_0)^{1/3} (\cos \varphi)^{2/3} - \frac{y}{H} \sin \varphi\right)}.$$
为了清楚起见，飞机的旋转速度做得相当大。飞机在大约 6 次摆动后变得垂直。
解决问题。
（待续）
