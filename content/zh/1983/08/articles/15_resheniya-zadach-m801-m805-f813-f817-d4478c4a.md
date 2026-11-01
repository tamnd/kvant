---
id: 1983-8-resheniya-zadach-m801-m805-f813-f817-d4478c4a
issue: kvant_1983_8
year: 1983
number: "8"
title: 问题解决方案M801—M805； F813—F817
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 52
page_last: 57
page_labels: 50-55
tag: AJ22
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 13693a4a260342e648d396e80d5d6f07426ab1681db4b1c62cb2599d9ede9607
prompt_sha256: draft-1
translated_from: content/ru/1983/08/articles/15_resheniya-zadach-m801-m805-f813-f817-d4478c4a.md
source_content_sha256: 91383e6c037e7d5f10c8575cddd15a527c54b68d1237384629694c98b1fa51eb
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

P832*。将边长为 $a$ 的方形不可变形超导框架水平放置在非均匀磁场中，其空间感应强度为
$$B_x = -kx, B_y = 0, B_z = kz + B_0.$$
The mass of the frame is $m$, its inductivity is $L$. At the initial moment the centre of the frame is at the origin with sides parallel to the $X$ and $Y$ axes. How will the frame move after it is released and where will it be after time $t$?
O. Yu. Nikishina

问题解决方案

M801—M805; F813—F817

注意，数$a \geqslant 1$的整数部分等于小于或等于$a$的自然数的个数。具体来说，$[\sqrt{n}] + [\sqrt[3]{n}] + \dots + [\sqrt[n]{n}] = [\log_2 n] + [\log_3 n] + \dots + [\log_n n]$（$[x]$表示数字$x$的整数部分）。

右侧同样处理：$[\log_m n] - 1$是自然数$x \geqslant 2$使得$x \leqslant \log_m n$，即$m^x \leqslant n$。这就是为什么
$$([\log_2 n] - 1) + ([\log_3 n] - 1) + \dots + ([\log_n n] - 1) = N$$
（对于$m > n$，$y \geqslant 2$，不等式$m^y \leqslant n$显然不成立）。

所以，等号两边都等于$N + n - 1$。
V.V.卡西尔

M802。在三角形ABC的边AB和BC上，与中心边一样，在其外侧构造具有相同顶角$B$的直角三角形APB和BQC。求三角形 PQK 的微笑，其中 $K$ 是边 AC 的中点。

答案：$\hat{P} = \hat{Q} = \beta, \hat{K} = 180^\circ - 2\beta$。

该问题属于相当大的一组问题，这些问题考虑给定形状的三角形（或其他多边形），建立在另一个三角形（或多边形）的边上；其中最著名的可能是所谓的“拿破仑问题”——证明在其外部的任意三角形的边上构造的直角三角形的中心本身形成直角三角形。通常，这些问题可以使用平面变换合成来解决。

考虑两个细分变换 (图 1)：
$$F_p = H_p^k \circ R_p^{90},$$，其中$k = |PB|:|PA|$，是$R_p^{90}$绕$P$旋转$90^\circ$的组合，由中心$P$和系数$k$和$F_q = H_q^k \circ R_q^{90}$准备（这种变换称为旋转几何或螺旋细分）。它们的组合$F = F_q \circ F_p$保留了点$K$（这解释了选择这样的变换；我们稍后会给出证明）。让 $F_p(K) = K_1$ (图 2)，然后$F_q(K_1) = K$。三角形 $KPK_1, KQK_1$ 和 APB 彼此匹配为直角三角形，具有相同的边比 ($|KP|:|PK_1| = |KQ|:|QK_1| = k = |PA|:|PB|$)。由于$KK_1$是三角形$KPK_1$和$KQK_1$的公斜边，它们全等，所以$|KP| = |KQ|$。因此，$\hat{PKQ} = 360^\circ - 2\cdot 90^\circ - 2\beta$，$\hat{KPQ} = \hat{KQP} = (180^\circ - (180^\circ - 2\beta))/2 = \beta$。

尚待证明$K$是细分$F$变换的不动点。注意$F$的以下性质：

⟦folio 51⟧

1) $F$ — 位移（因为相似系数$F$等于$k \cdot \frac{1}{k} = 1$）；

2) 当移动 $F$ 时，任​​何光线都会转向相反的方向（根据逻辑，光线的方向被保留；当旋转时，任何光线旋转的角度等于旋转角度，因此变换过程中任何光线的总旋转角度$F$等于$90^\circ + 90^\circ = 180^\circ$）；

3) $F(A) = C$（$F_P(A) = B$由$F_P$选择，以及$F_Q(B) = C$，因为$BQC = 90^\circ$和$|QC|:|QB| = |PA|:|PB| = 1/k$）。

这意味着$F$是$Z_K$的中心对称，以$K$为中心，特别是$F(K) = K$。

尝试用同样的方法解决“拿破仑问题”。

V·N·杜布罗夫斯基

M803。两个有理数$x$和$y$之和是自然数，它们的倒数$1/x$和$1/y$之和也是自然数。 $x$ 和 $y$ 可能是什么？

答案：$(x, y) = (1, 1), (1/2, 1/2), (2, 2)$。让我们将数字 $x$ 和 $y$ 表示为不可约分数：$x = \frac{a}{b}, y = \frac{c}{d}$。那么$x + y = \frac{ad + bc}{bd}$是一个自然数。因此，$ad + bc$可被$b$整除，并且由于$a$和$b$是互质数，因此$d$可被$b$整除。另一方面，$ad + bc$ 可被$d$整除，因此$b$ 可被$d$整除。由此可见$b = \pm d$。同样，$\frac{1}{x} + \frac{1}{y} = \frac{ad + bc}{ac}$是自然数，所以$a = \pm c$。因此，$x = y$或$x = -y$。第二种情况是不可能的，因为根据条件$x + y \ge 1$。在第一种情况下，$x + y = 2x = 2a/b$和$2/x = 2b/a$是自然数。也就是说，$a$和$b$是二的约数，以及$a/b > 0$。因此，$a/b = 1/1 = 1$，或$a/b = 1/2$，或$a/b = 2/1 = 2$。

A.P.萨文

M804。点$O$是直圆柱体轴线的中点，$A$和$B$是圆柱体下底圆上的对角点，$C$是上底圆上不位于平面$OAB$的圆上的某一点。证明三角形$OABC$（顶点$O$）的两个角之和为2π。

设 $D$ 为圆柱体上底圆上的一点，与点 $C$ (图 1) 径向相对。我们证明具有公共顶点 $O$ 的三面角 $OABC, OBCD, OCDA$ 和 $ODAB$ 两两全等。由于这三个角均共享一条公共边（$OA, OB, OC$ 或 $OD$），并且它们在该边上的二面角之和非常印度等于 2π，因此它们所有 12 个二面角的总和为 $4 \cdot 2\pi = 8\pi$。因此，它们每个的二面角之和，特别是角$OABC$，等于$8\pi/4 = 2\pi$。

为了证明这些三面角的全等，我们注意到三角形$ABCD$的对边两两相等（$|AB| = |CD|$作为全等圆的直径，并且边$AC$和$BD$，以及$AD$和$BC$关于圆柱体相互对称；（参见图） 1). A 由于点 $O$ 与三角形所有顶点$\triangle OAB \cong \triangle OCD, \triangle OAC \cong \triangle OBD$ 和 $\triangle OAD \cong \triangle OBC$ 的距离相等，因此，所考虑的三面角具有相等的平面角度，因此可以通过替换连接边 $AC$ 和 的中点的线来明确证明三面角的共圆性。 $BD$，以及$AD$和$BC$，就像常见的dilinda一样，是三角形$ABCD$的全等轴。

具有全等面的四面体$ABCD$将帮助我们解决这个问题，它具有许多显着的性质。 V. E. Matizen 今年的第 6 期«Kvant» 文章中列出了它的大量属性。

I.K.朱克

⟦folio 52⟧

M805*。 a）在三角形ABC的边BC、CA、AB上，分别选择点A 1 、B 1 、C 1 ，使得线段AA 1 、BB 1 、CC 1 相交于一点。证明 S₁A₁B₁C₁ ≤ S₁ABC/4。

6) 在三角形ABC的面BCD、CDA、BDA、ABC上，分别选择点A₁、B₁、C₁、D₁，使得线段AA₁、BB₁、CC₁、DD₁相交于一点。证明V₁A₁B₁C₁≤V₁ABCD/27。

图 1.

图 2.

图 3.

首先，我们将证明关于三角形面积和四面体体积之间关系的几个简单但非常有用的引理。

(1) 若直线 MM₁ 与直线 KL 相交于点 P(图 1)，则

$$S_{KLM}: S_{KLM_1} = |MP|: |M_1P|.$$

这是从明显的等式 hₘ:hₘ₁ = |MP|: |M_1P| 得出的，其中 hₘ 和 hₘ₁ 是三角形 KLM 和 KLM₁ 的高度。

(2) 如果点 L₁ 和 M₁ 位于直线 KL 和 KM (图 2) 上，则

$$S_{KLM}: S_{KL_1M_1} = \frac{|KL| \cdot |KM|}{|KL_1| \cdot |KM_1|}.$$

事实上，由于(​​1)，S_{KLM}: S_{KL_1M_1} = (S_{KLM}: S_{KL_1M}) \cdot (S_{KL_1M}: S_{KL_1M_1}) = (|KL|: |KL_1|) \cdot (|KM|: |KM_1|)。

(3) 若直线 NN₁ 与 KLM 平面相交于点 P，则

$$V_{KLMN}: V_{KLMN_1} = |NP|: |N_1P|.$$

（与（1）类似证明。）

(4) 若点 L₁、M₁、N₁ 位于直线 KL、KM、KN 上，则

$$V_{KLMN}: V_{KL_1M_1N_1} = \frac{|KL| \cdot |KM| \cdot |KN|}{|KL_1| \cdot |KM_1| \cdot |KN_1|}$$

（与（2）类似地证明。）

让我们直接解决问题。

a) 设 O 为线段 AA₁、BB₁ 和 CC₁ 的交点； S、Sₐ、Sₑ 和 Sₒ 是三角形 ABC、OBC、OCA 和 OAB (图 3) 的面积。然后通过(1)

$$\frac{|OA|}{|OA_1|} = \frac{|AA_1| - |OA_1|}{|OA_1|} = \frac{S}{S_A} - 1 = \frac{S - S_A}{S_A}.$$

类似的关系也适用于线段 BB₁ 和 CC₁。因此，

$$\frac{|OA_1|}{|OA_1|} = \frac{S_A}{S - S_A}, \frac{|OB_1|}{|OB_1|} = \frac{S_B}{S - S_B}, \frac{|OC_1|}{|OC_1|} = \frac{S_C}{S - S_C}.$$

将$\triangle A_1B_1C_1$的体积按线段OA₁、OB₁和OC₁分成三个三角形，并分别估计每个三角形的面积。

生效 (2)

$$S_{OA_1B_1} = S_{OAB} \cdot \frac{|OA_1| \cdot |OB_1|}{|OA| \cdot |OB|} = S_C \cdot \frac{S_A S_B}{(S - S_A)(S - S_B)} = \frac{S_A S_B S_C}{(S - S_A)(S - S_B)(S - S_C)}.$$

$$\cdot (S - S_C) = k \cdot (S - S_C).$$

将这个等式与三角形 OB₁C₁ 和 OC₁A₁ 的类似等式相加，我们得到：

$$S_{A_1B_1C_1} = k((S - S_C) + (S - S_A) + (S - S_B)) = 2kS.$$ (*)

为了估计 k，我们为 Sₐ 和 Sₑ、Sₑ 和 Sₒ、Sₒ 和 Sₐ 写出“均值不等式”：

$$\sqrt{S_A S_B} \leq \frac{S_A + S_B}{2}, \sqrt{S_B S_C} \leq \frac{S_B + S_C}{2}, \sqrt{S_C S_A} \leq \frac{S_C + S_A}{2}$$

及其变量：

$$S_A S_B S_C \leq (S_A + S_B)(S_B + S_C)(S_C + S_A)/8 = (S - S_C)(S - S_A)(S - S_B)/8.$$ (*)

因此k≤1/8且S₁A₁B₁C₁≤S₁ABC/4。

6) 我们只会给出证明的一般概要——它几乎逐字重复了 a) 点的推理。

设 O 为这些线段的交点，V、Vₐ、Vₑ、Vₒ 和 Vₒ 为三角形 ABCD、OBCD、OCDA、ODAB 和 OABC 的体积 (图 4)。用户引理 (3)

⟦folio 53⟧

F813。三个长度为 a 的失重铰接杆，每个铰接在同一水平线上的 A 点和 B 点（参见图）； $|AB|=2a$。对于悬架关节C，质量为m。当施加到铰链 D 上的最小力是多少时，中间杆将保持水平位置？

F814。半径为 R 的球位于小车的光滑水平表面上。小车开始以速度 $v_0$ 移动。在球落地时开始水平投影球的速度。

和（4）（代替a）部分中的（1）和（2）），很容易证明$V_{A1B1C1D1} = 3kV$，
（参见（*）），其中
$$k = \frac{V_A V_B V_C V_D}{(V - V_A)(V - V_B)(V - V_C)(V - V_D)}.$$

所有四行的“均值不平等”变量由数字 $V_A, V_B, V_C$ 和 $V_D$ 组成：
$$\sqrt[3]{V_A V_B V_C} \leq \frac{1}{3} (V_A + V_B + V_C) = \frac{1}{3} \Pi V - V_D), \dots, \text{ получим}$$
（参见 (**)），即 $k \leq 1/81$，因此为 $V_{A1B1C1D1} \leq V_{ABCD}/27$。

R·P·乌沙科夫

◆
由于关节 C 处于平衡状态，因此作用在其上的力之和为零。因此（参见图），
$$(m + m_\omega)g \sin \alpha = T_2 \cos \alpha,$$
(1)
其中 $m_\omega$ 是铰链的质量。由铰链 D 的平衡条件和水平中杆条件可知
$$T_2 \cos \alpha = F \cos \beta + m_\omega g \sin \alpha.$$ (2)
由(1)和(2)我们得到
$$F = \frac{T_2 \cos \alpha - m_\omega g \sin \alpha}{\cos \beta} = \frac{mg \sin \alpha}{\cos \beta} \geq mg \sin \alpha.$$
因此，中间杆保持水平位置的最小力$\vec{F}_{\min}$的横坐标值等于$mg \sin \alpha = mg/2$，并且垂直于杆BD。

S·K·斯特罗科夫

让我们提出这个问题的另一个解决方案，由读者 A.P. Zubatkin 发送。

作用在系统上的外力为：从“天花板”侧面施加在A点和B点的反作用力，分别等于相应的$|\vec{T}_1|$和$|\vec{T}_3|$，并沿杆AC和BD方向；施加在铰链上的重力$m_\omega g$；力$mg$，等于负载的重量；作用于铰链 D 的力 $\vec{F}$。由于系统处于平衡状态，因此围绕任意点的所有力的力矩总和必须等于 0。让我们写出 O 点的条件（参见图）：
$$mg a \sin \alpha + m_\omega g a \sin \alpha = Fa \cos \beta + m_\omega g a \sin \alpha.$$
从这里
$$F = \frac{mg \sin \alpha}{\cos \beta} \Rightarrow F_{\min} = mg \sin \alpha = mg/2, \vec{F} \perp [BD].$$

◆
让我们考虑一个球在参考系中以速度 $\vec{v}_0$ 的运动。在这个系统中，球以速度 $v_0$ 移动。从球中心正好位于车边缘上方的那一刻起，直到球中心脱离那一刻，它以接触点为圆心沿半径为R的圆运动（同时球不绕其自身中心旋转）。让我们找到分离时刻的角度 α（参见 图）。为此，我们将使用能量守恒定律和牛顿第二定律。
令 u 为分离时刻球中心的速度。然后
$$\frac{mu^2}{2} = \frac{mv_0^2}{2} + mgR(1 - \cos \alpha) \quad (m - масса шара)$$

⟦folio 54⟧

（能量守恒定律），
$$\frac{mu^2}{R} = mg \cos \alpha$$

（牛顿第二定律）。由(1)和(2)我们发现
$$\cos \alpha = \frac{1}{3} \left( \frac{v_0^2}{gR} + 2 \right), u = \sqrt{\frac{1}{3} \left( v_0^2 + 2gR \right)}.$$
从$\cos \alpha \leq 1$开始，很明显，在$v_0^2 \geq gR$，当球的中心位于车的极值点上方时，立即发生分离，并且球落到地板上时的速度$u_r$的水平投影将等于0。如果$v_0^2 < gR$，那么
$$u_r = v_0 - u \cos \alpha = v_0 - \frac{1}{3Rg} \sqrt{\frac{1}{3} \left( v_0^2 + 2gR \right)^3}.$$
A·R·齐伯曼

F815。将半径$r=0,2$毫米、长度$l=8$厘米的毛细管下端浸入水中，水温恒定且等于$0^\circ C$。毛细管上端温度为$t_0=100^\circ C$。表中给出了水的表面张力系数$\sigma(t)$的温度依赖性。毛细管中的水会上升到多高？毛细管的电导率远大于其中水的电导率；与周围身体交换的影响可以忽略不计。

◆ 令$x$ 为毛细管中水柱的高度。毛细管的温度以及该高度处的水的温度显然是：
$$t_x = t_0 \frac{x}{l}.$$
毛细管中的水通过表面张力保持。如果$\sigma(t_x)$是温度$t_x$下的表面张力系数，则
$$x = \frac{2\sigma(t_x)}{\varrho g r},$$
其中$\varrho$是水的密度。从这里开始是
$$\sigma(t_x) = \frac{\varrho g r x}{2} = \frac{\varrho g r l t_x}{2 t_0}.$$
最大水位上升温度$t_x$

<table><thead><tr><th>$t,^\circ C$</th><th>$\sigma, \frac{\text{mH}}{M}$</th></tr></thead><tbody><tr><td>0</td><td>76</td></tr><tr><td>20</td><td>73</td></tr><tr><td>50</td><td>67</td></tr><tr><td>90</td><td>60</td></tr></tbody></table>

⟦folio 55⟧

F816。在图所示电路中，电阻的阻值相同且等于$R = 60$欧姆，二极管是理想的。产生 $U = 12$ V 电压的电池将连接到$A$ 和 $B$ 点，持续 $t_1 = 1$ 秒。然后，将条带放置到位，将电池连接到电路，持续 $t_2 = 5$ 秒。求电路中释放的热量。

问题的条件没有说明哪些条带将电池连接到点$A$和$B$持续时间$t_1$，因此我们将考虑两种可能的连接选项。

1) 首先，“平”电池连接到点$A$，“负”电池连接到点$B$。由于二极管是理想的，因此它们的电阻为零，并且所有三个电阻器都彼此并联。电路的总电阻为$R_1 = R/3 = 20$欧姆。在时间$t_1$期间，电路中将释放热量

$$Q_1 = \frac{U^2}{R_1} t_1 = 7,2 \text{ Дж.}$$

当条带放置到位时，没有电流流过二极管，并且所有三个电阻器都串联连接。电路的总电阻等于$R_2 = 3R = 180$欧姆。在时间$t_2$期间，电路中将释放热量

$$Q_2 = \frac{U^2}{R_2} t_2 = 4 \text{ Дж.}$$

热链中的排放总量等于$Q = Q_1 + Q_2 = 11,2 \text{ Дж.}$。

2) 如果首先将电池的“负极”连接到点$A$，“平”连接到点$B$，则

$$Q_1' = \frac{U^2}{3R} t_1 \approx 0,8 \text{ Дж.}$$

$$Q_2' = \frac{3U^2}{R} t_2 \approx 36 \text{ Дж.}$$

$$Q' = Q_1' + Q_2' \approx 36,8 \text{ Дж.}$$

L.II。巴卡尼纳

F817。 图表示折射率$n$对坐标的依赖性。一束狭窄的单色光束落在介质 $I$ 和 $II$ 之间的界面上。光以什么角度进入介质 III？

根据折射定律，沿着光线的轨迹，值 $n(x) \cdot \sin \alpha_x$ 保持恒定（这里 $\alpha_x$ 是光线在界面上的入射角，对应于坐标 $x$）。由于折射率在第二介质中首先减小，因此随着轨迹接近边界（对应于坐标$x_1$），入射角$\alpha_x$将增加。在这种情况下，光束路径的切线将接近垂直方向。如果第二介质中的入射角达到$90^\circ$，则光束将不会离开该介质。如果即使在坐标为 $x_1$ 的边界处（其中 $n(x_1)$ 值最小），入射角也小于 $90^\circ$，则光束将从介质 II 移动到介质 III。

设在某个初始入射角$\alpha_0$（$\alpha_0$是介质$I$和$II$之间的界面上的入射角），光束在边界$x_1$上的入射角达到$90^\circ$。然后

$$n_1 \sin \alpha_0 = n(x_1) \cdot \sin 90^\circ \Rightarrow \sin \alpha_0 = \frac{1,2}{1,4} \approx 0,86, \alpha_0 \approx 60^\circ.$$

因此，在角度 $\alpha \geq \alpha_0$ 时，光线将无法进入介质 III。光线以角度 $0 \leq \alpha < 60^\circ$ 传输到介质 III 中。

V·V·莫扎耶夫
