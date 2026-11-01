---
id: 1986-7-resheniya-zadach-m971-m975-f983-f987-7acaf4b3
issue: kvant_1986_7
year: 1986
number: "7"
title: 问题解决方案M971—M975； F983—F987
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 39
page_last: 46
page_labels: 37-44
tag: ZYPJ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a638155e513022919bad3a4a86918b8ddf771a2a7e3561bc41d81c1015891dac
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/13_resheniya-zadach-m971-m975-f983-f987-7acaf4b3.md
source_content_sha256: 6c77df924fe272135f886792fc7dfc23653e439f2d2d63e4680e35e6b038a8c8
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

pe write the words: "KVANT'S PROBLEMS" and the numbers of all the solved problems; in your letter enclose an unstamped self addressed envelope — we shall use it to send you the correction results. At the end of the academic year we sum up the results of the Kvant problem contest. If you have an original problem to propose for publication, please send it to us under separate cover, in two copies (in Russian or in English), including the solution. On the envelope write NEW PROBLEM IN PHYSICS (or MATHEMATICS).

Problems M991—M995 were proposed to us by the Bulgarian magazine «Matematika».

P1004. A thin uniform rod which can rotate freely in the vertical plane about a horizontal axis passing through its upper extremity hangs motionless above water (see figure Pisc. 2); the length of the rod is $l$, its density $\rho$ ($\rho$ is less than the density of water). Slowly lowering the axis, the rod is immersed in water. Find and plot the dependence between the angle formed by the rod with the vertical and the distance from the axis to water level.

D. V. Belov

P1005. A heater in which a constant temperature $T_1$ is maintained and a refrigerator with inner temperature $T_0 < T_1$ contain coils of wire. The wire from the coil in the refrigerator comes out of it and goes into the heater to the other coil. The coils rotate so that the wire from the cold coil moves toward the hot coil with velocity $v$. The wire section area is $s$, the volume specific heat is $c$. In order to keep the temperatures $T_0$ and $T_1$ constant, it was necessary to increase the power of the heater by $\Delta E_x$ and decrease the production of cold by the refrigerator by the same magnitude. Find $\Delta E_x$.

D. V. Pavlov

P1006. Determine the resistance of the resistor circuit shown on figure Pisc. 3. The resistances are given in ohms.

S. S. Krotov

P1007. A light ray falls on a solid sphere made out of two glass hemispheres of refraction indices $n_1$ and $n_2$ ($n_1 > n_2$). The sphere is rotated with angular velocity $\omega$ about an axis perpendicular to the ray (see figure Pisc. 4). Find the maximal size of the spot obtained on a screen placed directly behind the sphere.

L. G. Markovich

问题解决方案

M971—M975; F983—F987

由于所有球队的胜场总数等于输球场数，并且每队进行了 7 场比赛，因此每队平均胜场数为 3.5 场。因此，至少有一支球队（我们称之为$A$）赢得了至少 4 场比赛。同样，对于输掉 $A$ 的 4 支球队，每支球队之间的比赛平均获胜 1.5 场，因此其中一支球队（我们称之为 $B$）至少战胜了两支球队。这两支球队中，一支（$C$）击败了另一支（$D$）。 $A, B, C, D$ 队组成所需的四支队伍。

很容易看出，问题的表述可以概括为：如果$2^{n-1}$队参加了比赛，那么总是有可能赢得n队$A_1, \dots, A_n$队，从而使他们各自击败数字更高的队。

有趣的是，找出 $N$ 团队参与的任何旅游者所选择的条件至少满足多少 $N$（取决于 $n$）。图 1 和图 2 所示的巡回图（其中箭头从获胜队绘制到失败队）表明，在$n=3, N=3$和$n=4, N=7$，我们的条件不再满足。 （请注意，在两个图中，所有命令都是相等的，并且在 图 1 处。）因此，在这两种情况下，最小允许值 $N$ 是 $2^{n-1}$。读者被要求回答这个问题对于$n=5, 6, \dots$是否成立。

A.T.乌克兰采夫

⟦folio 38⟧

M972。序列$x_1, x_2, \dots$由条件$x_1 = 1/2, x_{n+1} = x_n^2 + x_n(n=1, 2, \dots)$给出。查找数字的完整部分
$$\frac{1}{x_1+1} + \frac{1}{x_2+1} + \dots + \frac{1}{x_{100}+1}.$$

答：1. 显然
$$\frac{1}{x_n+1} = \frac{1}{x_n} - \frac{1}{x_n(x_n+1)} = \frac{1}{x_n} - \frac{1}{x_{n+1}},$$
根据定义，所考虑的总和等于 $1/x_1 - 1/x_{100} = 2 - 1/x_{100}$。序列$x_n$显然返回$x_2 = 3/4$和$x_3 = (3/4)^2 + 3/4 > 1$，因此也返回$x_{100} > 1$，即$1 < 2 - 1/x_{100} < 2$。

A·A·安扬斯

M973。在三角形ABC中，画出了高度AH和平分线BE。证明如果$\angle BEA = 45^\circ$则也$\angle EHC = 45^\circ$。

图 1.

图 2.

证明HE是角AHC的平分线就足够了。
让我们从E点画一条垂直于AC的垂线；设 D 为其与 BC 的交点 (图 1)。三角形 BEA 和 BED 的边 BE 和角度 ($\angle BEA = \angle BED = 45^\circ$) 相等，因此 AE=ED。由于点 A、E、H、D 位于同一圆上（角 AHD 和 AED 之和等于$90^\circ + 90^\circ = 180^\circ$），因此角 AHE 和 EHD 等于等弦 AE 和 ED 所对的内切角。

另一个解决方案基于众所周知的平分线定理：如果 BE 是三角形 ABC 的平分线，则 AE:EC=AB:BC（参见“Quant”，1985，第 2 期，第 29 页）。容易看出逆定理也成立，因此只要证明AH:HC=AB:BC就足够了。用α、β、γ表示三角形在顶点A、B、C处的角度，由正弦定理AB:BC=γ:sin α得到AH:HC=tg γ。但sin α=sin ($\beta + \gamma$)=sin ($90^\circ - \gamma$)=cos γ (因为β/2+γ=∠AEB=45°)，即sin γ:sin α=tg γ。

我们还要注意，问题中考虑的三角形可以通过以下事实来表征：经过 B、H 和 E 点的圆心 O 与 B 点在直线 AC 上的投影 (图 2) 重合。 （这个圆就是所谓的 A 点和 C 点的阿波罗圆，即为其 X 点构建相对的 AX:XB。）从这里可以得到又一个解。

I.F.沙里钦，
V·N·杜布罗夫斯基

M974。两个人正在用时钟下棋。两人都走了 40 步后，两个时钟都显示了 2 小时 30 分钟。
a) 证明游戏中有一个时刻，一个区域的时钟标记其他区域的时钟超过 1 分 50 秒。
b) 是否可以说在某些时刻时差至少为 2 分钟？

a) 任意时刻时钟读数之差的绝对值不超过 t=1 分 50 秒。那么第一个棋手在第一步棋上花费的时间不超过t，并且在接下来的任何一步棋上花费的时间不超过2t（如果棋步的思考时间超过2t，那么在这段时间的开始或结束时时钟读数的差异将大于t）。因此，比赛总时长，等于5小时=300分钟，不超过80 2t-t=159t，即t≥300/159 min>1分50 s。由此产生的矛盾表明，在

⟦folio 39⟧

在某些时候，时钟读数的差异将超过 1 分 50 秒。

6) 答：不。如果游戏中的第一步（更准确地说，用国际象棋术语来说，“半步”）需要 $t_0=300/158$ 分钟，接下来的每一步需要 78 - $2t_0$，最后的第 80 步 - $t_0$，那么每个棋手的总思考时间为 $39 \cdot 2t_0 + t_0 = 79t_0 = 2$ 小时 30 分钟，并且任何时刻时钟读数的差异不超过$t_0 < 2$分钟；差异图显示在第 38 页。

S.V.福明

M975。 “棋盘”$n \times n$ 域上有 20 个不同的棋子。众所周知，任何领域的每个人物的领域都不超过20个。
a) 证明对于$n=100$，这些数字可以重新排列，使它们不属于彼此。
b) 另外还需要知道，如果有十二个数字，那么它所在的一组字段也平行移动（到同一向量）。证明对于$n=30$，这 20 个数字可以排列成互不相同。

a) 利用距离，可以将 20 个棋子排列在棋盘上$100 \times 100$，并估计这些排列中至少一个棋子是其他棋子的比例$p$。很容易估计给定棋子$A$将成为给定棋子$B$的编队比例：对于任何位置$A$，棋子$B$都有$100^2-1=9999$自由区域，其中不超过20个棋子受到$A$的攻击；因此，这个分数不超过 $20/9999$。由于（有序）数字对 $(A, B)$ 的数量为 $20 \cdot 19=380$，

$$p \leq 380 \cdot \frac{20}{9999} < 1,$$

存在一些位置，没有数字会有所不同（它们的分数等于 $1-p>0$）。

请注意，我们的估计是相当粗略的 - 我们教授的位置中几个数字不同，与其中存在此​​类数字对的次数一样多。

6) 我们将按顺序将棋子放在棋盘上。如果第一颗棋子已经放置，则第二颗棋子不能放置在：1）第一颗棋子占据的区域，2）第一颗棋子攻击的区域（不超过20个），3）第二颗棋子将成为第一颗棋子的区域。让我们证明第三组也不超过 20 个字段。

设 $\vec{v}_1, \dots, \vec{v}_k$ 为连接第二个图形所占据的区域中心与其所在区域中心的向量。当棋子移动时，这组向量不会改变；其中之一可能超出棋盘的边缘（图中显示了国际象棋马的两个位置的此类向量）。第 2 个数字为第 1 个的字段是通过从第 1 个数字占据的字段中取出向量 $-\vec{v}_1, -\vec{v}_2, \dots, -\vec{v}_k$ 来获得的 - 它们不超过 20 个。

这样，第 2 块的禁区数量不会超过 41 个。如果我们将它放在剩下的其中一个区域上，那么第 3 块的禁区数量不会超过 $2 \cdot 41=82$ 个，以此类推。第 20 块的禁区数量不会超过 $19 \cdot 41=779<900$ 个，因此也可以按照问题的条件放在棋盘上。

请注意我们问题的两点的根本解决方案：与问题 6）的解决方案相比，问题 a）的解决方案对找到所需的安排没有任何帮助 - 正如他们所说，这是“纯粹的存在证明”。

A·K·托利措

⟦folio 40⟧

F983。一块质量为 $m=1$ kg 的块放在粗糙的桌子上；台面上的木块静摩擦系数$\mu_0=1$，滑动摩擦系数$\mu=0.9$。刚度为 $k=1$ N/m 的弹簧连接到块上。弹簧开始沿水平方向下沉，使其自由端以$v=1$ m/s的恒定速度运动（图1）。方块将如何移动？

我们将分阶段考虑系统的运动。

第一阶段：滑块静止，弹簧间隔。这种情况会一直发生，直到在某个时间点 $t_1$ 弹簧张力 ($|kx_1|$) 达到最大静摩擦力值 ($\mu_0mg$)；从这一刻起，木块开始移动。

让我们从哪里找到 $t_1: kx_1=\mu_0mg$ 或 $k(vt_1)=\mu_0mg$

$$t_1=\mu_0\frac{mg}{kv} \approx 10\text{ c}.$$

让我们引入符号$k/m=\omega^2$。然后

$$t_1=\mu_0g/v\omega^2.$$

此时的弹簧距离

$$x_1=vt_1=\mu_0\frac{g}{\omega^2}.$$

第二阶段。从时间$t_1$开始，方块开始移动。让我们在以速度 $\vec{v}$ 移动的坐标系中考虑这种运动。在这个系统中（我们将其表示为$c$），在时间$t_1$，块的速度为$-\vec{v}$，坐标为$x=0$，弹簧的距离为$x_1=vt_1$。在弹力$f_{\text{упр}}=kx_1$和滑动摩擦力$f=\mu mg$的作用下，块体进一步运动，其方向与矢量$\vec{v}$方向相反（这是块体相对于工作台的速度方向，在系统$c$中具有恒定速度$-\vec{v}$）。让我们记住，在弹力和恒力（在本例中为摩擦力）的作用下，身体会发生和谐的振荡：

$$x_c=x_{c\text{max}} \sin(\omega t+\varphi)+x_0(\omega=\sqrt{\frac{k}{m}}),$$

其中$x_0$是平衡位置，由条件决定

$$k(x_1-x_0)-\mu mg=0 \Rightarrow$$

$$x_0=x_1-\frac{\mu mg}{k}=x_1-\mu\frac{g}{\omega^2}=\Rightarrow \Delta\mu\frac{g}{\omega^2},$$

其中$\Delta\mu=\mu_0-\mu$。

物块的速度按规律变化

$$v_c=\dot{x}_c'=x_{c\text{max}} \omega \cos(\omega t+\varphi).$$

我们来求 $x_{c\text{max}}$ 和 $\varphi$ 的值。为此，我们将值$t=t_1$、$x_c=x(t_1)=0$、$x'(t_1)=-v$ 代入 (1) 和 (2)：

$$0=x_{c\text{max}} \sin(\omega t_1+\varphi)+\Delta\mu\frac{g}{\omega^2},$$

$$-v=x_{c\text{max}} \omega \cos(\omega t_1+\varphi).$$

让我们以这种形式重写这些方程：

$$x_{c\text{max}} \sin(\omega t_1+\varphi)=-\Delta\mu\frac{g}{\omega^2},$$

$$x_{c\text{max}} \cos(\omega t_1+\varphi)=-\frac{v}{\omega}.$$

通过对（3）和（4）求平方并将结果表达式相加，我们发现：

⟦folio 41⟧

$$x_{c \max}^2 = \frac{(\Delta \mu)^2 g^2}{\omega^4} + \frac{v^2}{\omega^2} \approx 2 \text{ m}^2, \quad x_{c \max} \approx 1,4 \text{ m}.$$

将（3）除以（4），我们得到：

$$tg(\omega t_1 + \varphi) = \Delta \mu \frac{g}{v \omega}$$

$$(\sin(\omega t_1 + \varphi) < 0, \cos(\omega t_1 + \varphi) < 0)$$

在哪里

$$\varphi = \pi + \arctg \frac{\Delta \mu \cdot g}{v \omega} - \omega t_1 \approx \frac{5 \pi}{4}.$$

现在让我们转向静止参考系（在时间 $t_1$ 两个系统中的坐标原点重合）：

$$x = x_c + v(t - t_1) = x_{c \max} \sin(\omega t + \varphi) + v(t - t_1) + \Delta \mu \frac{g}{\omega^2} = \sqrt{2} \sin((t - 10) + \frac{5 \pi}{4}) + (t - 10) + 1 \text{ (м)},$$

$$x' = x_{c \max} \omega \cos(\omega t + \varphi) + v = \sqrt{2} \cos((t - 10) + \frac{5 \pi}{4}) + 1 \text{ (м/c)}.$$

这些方程描述了从时间$t_1$时刻到$t_2$时刻的木块运动，此时木块的速度变为等于0并且滑动摩擦力被静摩擦力取代。此时$t_2$

$$x' = x_{c \max} \omega \cos(\omega t_2 + \varphi) + v = 0.$$

回想一下，角度 $\theta = \omega t_1 + \varphi$ 位于第三季度。随着$t (t > t_1)$的进一步增长，角度将增加，cos $(\omega t + \varphi)$也将增加，因此，速度将增加，保持正值。当$(\omega t + \varphi)$结束于第二（第六）季度时，cos$(\omega t + \varphi)$将为负数，当变成cos$(\omega t_1 + \varphi)$时，区块的速度变为零。因此，

$$t_2 = t_1 + \frac{2 \left( \pi - \arctg \frac{\Delta \mu \cdot g}{v \omega} \right)}{\omega} \approx 15 \text{ c},$$

$$x(t_2) \approx 7 \text{ m}.$$

请注意，弹簧在时刻 $t_2$ 和 $t_1$ 时的张力与以下关系式有关：

$$f(t_1) - \mu mg = -(f(t_2) - \mu mg) \Rightarrow f(t_2) = 2 \mu mg - f(t_1).$$

但是$f(t_1) = \mu_0 mg$；这就是为什么

$$f(t_2) = mg(2 \mu - \mu_0) < \mu_0 mg.$$

这意味着在时刻$t_2$，块保持不变并且不会移动，直到时刻$t_3$，此时$f(t_3)$变得相等

⟦folio 42⟧

对 $\mu_0 mg$ 取模。时间间隔$t_3 - t_2$显然等于

$$t_3 - t_2 = \frac{f(t_3) - f(t_2)}{kv} = \frac{2(\mu_0 - \mu)g}{v\omega^2} \approx 2\text{ c.}$$

然后重复循环，使得$t_4 - t_3 = t_2 - t_1$等。函数$x(t)$和$x'(t)$的图形如图2和图3所示（参见第41页）。

I.I.马津

F984。当科尔克开车时，托罗普有时会卡在劈开的原木中。遇到这种情况，应该按照图1所示的方式进行，或者按照图2所示的方式进行，哪种方法更有效呢？

图 1.

图 2.

图 3.

当斧头进入原木时，斧头两侧的原木之间的裂缝会增加：这些翼片在垂直于斧头“颈部”的方向上有斜坡；树中存在弹簧变形的累积。当这种变形达到某个“最大承受”值时，原木就会破裂（劈裂）。

我们假设在第一种情况和第二种情况中，在击中“铁砧”之前，斧头+原木系统具有相同的能量。当撞击砧座时，部分能量转化为热量。在第一种情况下（下面的树），影响是非弹性的，在第二种情况下，影响是弹性的。这意味着在第一种情况下，撞击过程中的能量损失 ($\Delta E_1$) 大于第二种情况 ($\Delta E_2$)。剩余的能量用于抵抗斧头和圆木相互运动期间的摩擦力以及增加圆木中的弹簧变形能量。让我们写下这个能量平衡：

$$E'_1 = E - \Delta E_1 = A_1 + U_1,$$
$$E'_2 = E - \Delta E_2 = A_2 + U_2.$$

由上可知，$E'_2 > E'_1$，即$A_2 + U_2 > A_1 + U_1$。

显然，如果$U_2 > U_1$，那么第二种方法更有效。

对于斧头相对于原木从相同初始位置的相同运动，即对于相同的值$A$（$A_1 = A_2$），显然是$U_2 > U_1$。让我们证明数量 $A$ 和 $U$ 彼此成正比。

做功 $A$ 是抵抗摩擦力进行的，当斧头相对于原木移动时，摩擦力会发生变化，因为法向反作用力 $N_t$ (图 3)。能量$U_t$等于斧头对树的法向压力所做的功。任何时刻的该力在数值上都等于法向反作用力$N_t$。综上所述，很明显，条件$A_2 + U_2 > A_1 + U_1$意味着$A_2 > A_1$和$U_2 > U_1$，因此第二种方法——用斧头敲击铁砧——更有效。

T·S·佩特洛娃

F985。将倒置的试管$A$浸入装有液体乙醚的容器中。他们立即从它开始

⟦folio 43⟧

气泡出来。气泡被“收集”在试管 B 中，试管 B 最初完全充满乙醚（参见图nok），其长度是试管 A 长度的两倍。在这种情况下，第一初始体积的乙醚的 2/3 从试管 B 中排出。房间内的温度保持在 20 °C，压力等于正常大气压。解释这个过程发生了几个毫米点。艺术。）。当试管A内的乙醚停止蒸发时，即当试管A内的压力等于饱和蒸气压$p_H$且总压为$p_H + p_B = p_0$时，即$p_B$为气压时，气泡将不再冒出。

试管 B 中也必须满足类似的条件。在这种情况下，试管 A 中占据体积 $V_0$ 的空气将占据试管 B 中的体积 $\frac{4}{3}V_0$。利用波义耳-马鲁特定律，我们可以写出：

$$p_0V_0 = p_B(V_0 + \frac{4}{3}V_0) = \frac{7}{3}p_BV_0,$$

我们在哪里可以找到$p_B = \frac{3}{7}p_0$。现在很容易确定乙醚的饱和蒸气压：

$$p_H = p_0 - p_B = \frac{4}{7}p_0 \approx 430 \text{ мм pt. ст.}$$

A.I.布兹丁

位于板表面的金属原子（钨和铂）与CO分子中的碳原子具有不饱和化学键。羟基氧化碳与清洁金属表面的相互作用导致C原子和表面金属原子之间形成牢固的化学键。该反应伴随着热量的释放。在这种情况下，碳氧在金属表面形成单层，对于位于板表面的每个金属原子，有一个CO分子，并且分子轴垂直于金属表面（图1）。

在片晶表面附近，可以识别两个平面$P_1$和$P'_1$，彼此相距$l$，并分别穿过碳原子和氧原子的中心。我们假设正电荷（偶极子电荷$+\Delta q$）位于从电荷平面$+\sigma_1$表面起的$P_1$平面内，负电荷位于从电荷平面$-\sigma_1$表面起的$P'_1$平面内（图2）。

类似地，在钨板表面附近有两个不同的带电平面$P_2$和$P'_2$，分别与带电平面$+\sigma_2$和$-\sigma_2$表面不同。

因此，钨板与板之间电势差$U$的计算简化为确定不同带电平面的两个参数之间的电势差：

$$U = \frac{\sigma_1}{\varepsilon_0} l - \frac{\sigma_2}{\varepsilon_0} l = \frac{\sigma_1 - \sigma_2}{\varepsilon_0} l. \tag{1}$$

⟦folio 44⟧

金属的平均原子数，以及它们在其表面单位面积上的位置（原子表面密度γ），是通过原子体积密度比来确定的

$$\gamma = n^{2/3},$$

其中$n$是金属原子的体积密度。反过来，原子的体积密度等于

$$n = \frac{\rho N_A}{M},$$

其中$\rho$是金属的密度，$N_A$是阿伏伽德罗数，$M$是金属的摩尔质量。很明显

$$\sigma = \Delta q \gamma.$$

考虑到关系式 (2)—(4)，我们将所需的电势差表示为以下形式

$$U = \frac{\Delta q \cdot l}{\varepsilon_0} N_A^{2/3} \left( \left( \frac{\rho_W}{M_w} \right)^{2/3} - \left( \frac{\rho_{Pt}}{M_{Pt}} \right)^{2/3} \right).$$

代入数值（$\varepsilon_0 = 8,85 \times 10^{-12} \text{ Ф/m}$、$N_A = 6,02 \cdot 10^{23} \text{ mol}^{-1}$、$\rho_W = 19,1 \times 10^3 \text{ кг/m}^3$、$\rho_{Pt} = 21,5 \cdot 10^3 \text{ кг/m}^3$、$M_W = 0,184 \text{ кг/mоль}$、$M_{Pt} = 0,195 \text{ кг/mоль}$），我们得到$U = 24 \text{ мВ}$。

总之，应该指出的是，在解决问题时进行了简化——我们没有教导在晶体结构中，钨和铂的原子以一定的顺序排列，因此，在不同的环境中，其表面上出现不同数量的金属原子。因此，式（2）需要针对金属表面原子排列的每种具体情况进行澄清。此外，在表面的不同平面上，原子具有不同的化合价，这一点也必须考虑在内。

E. N. 尤诺索夫、I. V. 亚明斯基

F987。在列维坦的画作《三月》中，晴朗的阳光下树木在雪地上投下的阴影是蓝色的。 （从物理角度来看）将它们引导为黑色、无色（黑色或灰色）不是更正确吗？

地球表面任何区域的照明都是由直射阳光和大气中散射的阳光共同产生的。如您所知，阴影边界定义了直射阳光无法到达的区域。如果一般光线没有落入该区域，则相应区域将是无色（黑色）。

在晴朗的晴天（天空中几乎没有云），漫射到地球上的阳光“具有蓝色色调”（天空的颜色）。落入“直接”阴影区域时，该光从白色雪盖反射而没有明显吸收（这是白雪的特性），并使阴影呈现蓝色。积雪越清晰，所描述的效果就越明显。

A·S·布托夫
