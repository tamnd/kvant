---
id: 1984-4-resheniya-zadach-m841-m845-f852-f857-8edfd005
issue: kvant_1984_4
year: 1984
number: "4"
title: 问题解决方案M841—M845； F852—F857
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 42
page_labels: 35-40
tag: NBKU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 47b1dddbffd3539a56ff7869f9dc146d0dd4ed606344851084ca445449bbbf4b
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/11_resheniya-zadach-m841-m845-f852-f857-8edfd005.md
source_content_sha256: 3b83419bc6145553bff88363038eaba26e714176af68dae7dae59e23e8e31f1c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

isochorically heated to its initial temperature, which requires the amount of heat $Q=125$ J. Determine $c_x$.

A. A. Sheronov

P871. An initially uncharged capacitor of capacity $C$ is connected consecutively to a battery of EMF of tension $U_0$ and a coil of inductivity $L$. The current in the coil first increases, then decreases. At the moment when the current banishes, the capacitor is disconnected and then reconnected with the ends interchanged.

What maximal current will then flow through the coil. How will the current change if the reconnection process is repeated 1984 times? The circuit’s resistance is negligible.

A. R. Zilberman

P872. A long sled, sliding on very slippery ice, reaches an ice-free section of the road and stops before travelling half its length. Then a sharp push restores the sled’s previous velocity, and it stops again. What is the relationship between 1) the slowing down times in the first and second cases? 2) the distances travelled while slowing down?

S. S. Krotov

问题解决方案

M841 — M845; F852 — F857

这个简单的问题有多种解决方案。让我们只给出其中之一。令$a$和$b$为边的长度，$c$为给定三角形$ABC$的斜边长度； $A_1, B_1$ 和 $C_1$ 是内切圆侧面的切点（参见 图）。根据从一点画圆的切线相等的定理，$|AB_1| = |AC_1|$、$|BC_1| = |BA_1|$和$|CA_1| = |CB_1|$。由此可见

$$|AC_1| = \frac{c+b-a}{2}, \quad |BC_1| = \frac{c+a-b}{2}.$$

因为

$$|AC_1| \cdot |BC_1| = \frac{1}{4} (c+b-a)(c-(b-a)) = \frac{1}{4} (c^2-(b-a)^2) = \frac{1}{4} (c^2-b^2-a^2+2ab) = \frac{ab}{2} = S_{\triangle ABC}$$

（我们使用毕达哥拉斯定理）。

对于任意三角形$ABC$，类似的计算可得出以下公式：

$$S_{\triangle ABC} = |AC_1| \cdot |BC_1| \cdot \text{ctg} (\widehat{C}/2).$$

V·N·杜布罗夫斯基

a) 这是一个相当著名的陈述——对第 6) 点的提示；可以使用将正弦之和与余弦之差转换为乘积的标准公式轻松证明：

$$\sin \alpha + \sin \beta + \sin \gamma = 2 \sin \frac{\alpha+\beta}{2} \cos \frac{\alpha-\beta}{2} + 2 \sin \frac{\gamma}{2} \cos \frac{\gamma}{2} = 2 \sin \frac{\gamma}{2} \left( \cos \frac{\gamma}{2} - \cos \frac{\alpha-\beta}{2} \right) =$$

b) 三角形的值$\widehat{A}$、$\widehat{B}$、$\widehat{C}$满足

⟦folio 36⟧

健康）状况
$$\frac{\sin \hat{A} + \sin \hat{B} + \sin \hat{C}}{\cos \hat{A} + \cos \hat{B} + \cos \hat{C}} = \sqrt{3}.$$
证明其中至少有一个等于60°。

$$= 4 \sin \frac{\gamma}{2} \sin \frac{\alpha - \beta - \gamma}{4} \sin \frac{\alpha + \gamma - \beta}{4} = -4 \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2}$$
（后者是条件$\alpha + \beta + \gamma = 0$的转变）。

6) 从$\sqrt{3} = \frac{\sin 60^\circ}{\cos 60^\circ}$开始，条件可以重写如下：
$$\sin \hat{A} \cos 60^\circ - \cos \hat{A} \sin 60^\circ + \sin \hat{B} \cos 60^\circ - \cos \hat{B} \sin 60^\circ = 0$$
或者
$$\sin (\hat{A} - 60^\circ) + \sin (\hat{B} - 60^\circ) + \sin (\hat{C} - 60^\circ) = 0.$$
将a)点的陈述应用到角度$\hat{A} - 60^\circ$、$\hat{B} - 60^\circ$和$\hat{C} - 60^\circ$，我们得到
$$\sin \frac{\hat{A} - 60^\circ}{2} \cdot \sin \frac{\hat{B} - 60^\circ}{2} \cdot \sin \frac{\hat{C} - 60^\circ}{2} = 0,$$
即，角度$\hat{A}$、$\hat{B}$、$\hat{C}$至少其中之一等于60°。
L·D·库尔扬奇克

**M843。在三角形 ABC 的顶点，AA1、BB1 和 CC1 在其一侧的平面上的重新分布已恢复，其长度等于三角形的相应高度。证明平面 ABC1、BB1 和 CC1 在平面 ABC 上的重分布落在三角形 ABC 的内切圆的圆心处，并且长度等于其半径。

◆ 设 $Q$ 为平面 ABC1、BB1 和 CC1 的交点，$O$ 为 ABC 平面上的投影，$P$ $O$ 为三角形一条边的投影，用于定义 - 在线 BC 上。显然，三角形QOP与三角形$A_1AH$类似，其中$AH$是三角形ABC的高（见图1）。因此，$|OP|:|OQ| = |AH|:|AA_1| = 1$，即$|OP| = |OQ|$。同样证明点$O$到线$AB$和$AC$的距离也等于$|OQ|$。但这也意味着$O$是内切圆的圆心，$a$$|OQ|$是它的半径。

让我们给出点$Q$到平面ABC的距离$d$与线段AA1、BB1和CC1的长度$a$、$b$和$c$之间的一般对应关系：
$$\frac{d}{a} + \frac{d}{b} + \frac{d}{c} = 1$$ 或 $d = \frac{abc}{ab + bc + ca}$。

图 1.
图 2.

自己证明一下，如果$a$、$b$、$c$是三角形的高长，那么$d$就是它的内切圆的半径。 图2说明了二维情况下类似对应关系的证明。

V.N.杜布罗夫斯基，
A.A.亚古扬茨

**M844。 a) 证明任意自然数$a$都可以直接表示为以下形式
$a = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_n \cdot n!$, (1)
食物 $a_k$ - 整数，$0 \leq a_k \leq k$，$a_n \neq 0$。 （根据定义，$k! = 1 \cdot 2 \cdot \dots \cdot k$，$1! = 1$。）
b) * 证明任意有理数$r$,$0 < r < 1$都可以

◆ a) 让我们展示如何在给定数字 $a$ 的情况下找到表示形式中的首项系数 $a_n$
$$a = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)! + a_n \cdot n!$$
(*)
其中$0 \leq a_k \leq k$、$a_n \neq 0$及其编号$n$。
从边距中的第一点（参见第 37 页）可以得出，对于系数 $a_k$ 的指示值
$a' = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)! \leq$
$\leq 1 \cdot 1! + 2 \cdot 2! + \dots + (n-1) \cdot (n-1)! < n!$,
另外，$n! \leq a_n \cdot n! \leq n \cdot n!$。对于每个自然数$a$，都可以找到唯一的$n$，使得$a$位于区间$n! \leq a < (n+1)!$内；这唯一地确定了表示中的 $n$ -

⟦folio 37⟧

以形式表示
$$r = \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!},$$
(2)
食物 $b_k$ - 整数，$0 \leq b_k \leq k$，$b_n \neq 0$。
c) 在表格(1)中输入数字$a=1984$，在表格(2)中输入数字$r=19/84$。

$$1 \cdot 1! + 2 \cdot 2! + \dots + n \cdot n! = (2! - 1!) + (3! - 2!) + \dots + ((n+1)! - n!) = (n+1)! - 1$$

他们 （*）。通过将这个区间划分为$n$个区间（每个$n!$长），我们找到唯一可能的值$a_n$作为$a : a_n \cdot n! \leq a < (a_n+1)n!$落在的区间数；换句话说，$a_n$是$a$除以$n! : a = a_n \cdot n! + a'$的部分商，其中$0 \leq a' < n!$（$a_n = [a/n!]$，其中$[x]$是$x$的整数部分）。

类似地，我们可以找到 $a'$ 表示中的首项系数
$$a' = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)!$$
所需表示（*）的存在性和唯一性的形式证明可以通过数学归纳法来证明：对于$a=1$，该陈述是显而易见的，并且我们的推理表明，如何从对于小于$a$的数字为真的假设出发，得出对于给定的$a$它也为真。

你也可以反方向思考：先求$a_1$，然后$a_2$，等等。在这种情况下，$a_1$是$a$除以2的余数，$a_2$是$(a-a_1 \cdot 1!)/2$除以3的余数，一般情况下，$a_k$是$(a-a_1 \cdot 1! - \dots - a_{k-1} \cdot (k-1)!)/k!$除以的余数$k+1$。

这两种方法都允许我们推导出以下 $a_k$ 的通用公式：
$$a_k = [a/k!] - [a/(k+1)!] (k+1).$$

6) 我们将按顺序分割段 [0; 1]：在第 1 步 - 分成 2 个等份，在第 2 步将两个形成的线段中的每一个 - 分成 3 个等份，等等。一般来说，在第 $(k-1)$ 步获得的每个线段的第 $k$ 步，我们分成 $k+1$ 等份。很明显，在第$k$步之后，段[0; 1] 将被分成 $(k+1)$ 等份。

考虑分割点$r$，它首先出现在第$n$步（显然是$r=m/(n+1)!$，其中$m$不能被$n+1$整除）。该点与左侧最接近它的第$(n-1)$步的点的距离为$b_n/(n+1)!$，其中$b_n$是整数$0 < b_n \leq n$。反过来，第 $(n-1)$ 步的点距离最左边的第 $(n-2)$ 步的点$b_{n-1}/n!$，其中 $0 \leq b_{n-1} \leq n-1$，依此类推。结果，我们得到表示
$$r = \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!}, 0 \leq b_k \leq k, b_n \neq 0.$$

(**)

它唯一的结果是，对于 (**) 中的任何 $b_1, \dots, b_n$ 集合，数字
$$\frac{b_1}{2!}, \frac{b_1}{2!} + \frac{b_2}{3!}, \dots, \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!}$$

因此，不迟于分区的第 1、2、...、$n$ 步骤获得，并且（由于不等式$0 \leq b_k \leq k$）它们中的每一个在同一步骤的所有数字中最接近下一个的左侧。

仍然需要注意的是，任何与区间 [0;0; 不同的数字 $r=p/q$ 1] 将在不晚于第 $(q-1)$ 步（从 $r=p(q-1)/q!$ 开始）处出现为分区点。

事实上，在这个解决方案中，系数$b_1, \dots, b_n$是从$b_n$开始顺序确定的：如果$b_n, \dots, b_k$已经找到，那么$b_{k-1}$就是（整数！）数除法的余数
$$\left(r - \frac{b_n}{(n+1)!} - \dots - \frac{b_k}{(k+1)!}\right) \cdot k!$$至$k$。想想如何才能找到
从 $b_1$ 开始拨这些系数。检查以下公式是否正确：
$$b_k = [r \cdot (k+1)!] - [r \cdot k!](k+1)$$
（您可以在页边空白处使用第二个身份）。

c) 答案：1984 = 2 2！ + 3·3！ + 2·4！ + 4·5！ + 2 6!, 19/84 = 1/3! + 1/4！ + 2/5！ + 6/7！。根据 a) 和 b) 点的解很容易找到这些表示。

V·E·科洛索夫

答案：对于任何偶数$n$。

图2展示了如何从任意偶数个$n$角（角$4 \times n$）形成中心对称图形。相反，让我们证明，任何中心对称图形 $f$ 只能包含偶数个角度。让我们给出两个证明。

⟦folio 38⟧

第一个是基于传统的奥林匹克理念——色彩和平等。图形$\Phi$的对称中心$O$是对应方格的对称中心之一，即要么是它的节点，要么是两个相邻节点之间的线段的中间，或者是单元格的中心。最后，图中的单元格数量为奇数，但可以被 4 整除。我们将平面画上“蓝色条纹”，如 图 3 所示。那么图中 $\Phi$ 中蓝色单元格的数量将为偶数。 （根据中心$O$的位置，对称性的每个蓝色细胞是白色的 - 至于图3、$a$上的中心$O_1$和$O_2$，然后$\Phi$中的蓝色细胞数等于细胞总数的一半，是四的倍数；或者对称性的每个蓝色细胞是另一种蓝色 - 至于图 3、$a$上的点$O_3$。）但是在网格上的任何矩形$4 \times 1$中，蓝色单元格的数量是偶数（图 3，$a$），并且在任何角上它是奇数（图 3，$6$）。因此，角的数量必须是偶数。

第二个证明基于这样的事实：图形$\Phi$的对称中心$O$也是它的质心（如果我们将其视为均匀板；我们也可以用集中在组成该图形的细胞中心的等质量有限系统来代替$\Phi$）。正如我们上面看到的，至少有一条网格线经过点$O$；让我们将其作为纵坐标轴，并作为横坐标轴（任何前前网格线）。长度单位是笼子的边长。在这些轴中，点$O$的坐标以及任何矩形$4 \times 1$的质心将是整数或获得，即$a/2$形式的数字，其中$a$是整数。角点的质心位于连接构成角点的两个矩形$2 \times 1$ (图 4) 中心的线段的中间，因此其坐标的形式为$b \pm 1/4$（$b$ 是整数）。现在让我们利用这样一个事实：如果我们用其质心替换组成$\Phi$的每个图形（矩形和角度），并在这些中心放置相等的质量，那么所得新系统的中心也落在点$O$处。这意味着$O$点的坐标等于构成$\Phi$的所有图形的质量对应坐标中心的算术平均值。因此，这些中心的横坐标之和，即几个$a/2$形式的数和$n$形式$b \pm 1/4$形式的数之和必须等于0。但这在很大程度上只有 $n$ 才有可能实现。

为了使第二个证明变得完全严格，我们还必须给出质心的精确数学定义，并证明我们对它的性质的使用，例如用其中心代替某一组质量的合法性。 M. B. Balk 和 V. G. Boltyansky 在本期杂志上发表的文章对此进行了详细讨论。

V·G·别洛夫

F852。在水平非导电平面上，不刺穿质量为 $m$ 的均匀负载环。接通感应$\vec{B}$的水平磁场后，重新分布环的平面，环对平面的压力减半。如果环的电荷为 $q$，则环滚动的速度是多少？

环在平面上的压力的变化是由于磁场对环施加了一定的力。让我们找到这个力量。

让我们考虑环上靠近点 $A$ 和 $C$ 的两个直径相对的小部分（参见 图ok）。由于$O$点是环的瞬时旋转中心，因此$A$和$C$点的瞬时速度等于相应的

$$v_A = \frac{v}{R} |OA| = \frac{v}{R} 2R \cos \frac{\alpha}{2} = 2v \cos \frac{\alpha}{2},$$

$$v_C = \frac{v}{R} |OC| = 2v \sin \frac{\alpha}{2},$$

其中 $R$ 是环的半径。向量$\vec{v}_A$和$\vec{v}_C$重新分布相应的线段$OA$和$OC$。设每段费用为$\Delta q$。由于面积很小，这些费用可以认为是精确的。磁场作用在每个电荷上的洛伦兹力等于

$$F_A = \Delta q \cdot B2v \cos \frac{\alpha}{2},$$

$$F_C = \Delta q \cdot B2v \sin \frac{\alpha}{2}.$$

向量 $\vec{F}_A$ 和 $\vec{F}_C$ 沿着线段 $OA$ 和 $OC$ 以及组合定向

⟦folio 39⟧

它们的水平角分别等于

$$\beta = \frac{\alpha}{2} + \left( \frac{\pi}{2} - \alpha \right) = \frac{\pi}{2} - \frac{\alpha}{2},$$

$$\gamma = \frac{\pi}{2} - \left( \frac{\pi - \alpha}{2} \right) = \frac{\alpha}{2}.$$

在水平投影中，作用在两个部分上的合力等于

$$\dot{f}_x = \Delta q \cdot 2Bv \left( \cos \frac{\alpha}{2} \sin \frac{\alpha}{2} - \sin \frac{\alpha}{2} \cos \frac{\alpha}{2} \right) = 0,$$

并投影到垂直方向

$$\dot{f}_y = \Delta q \cdot 2Bv \left( \cos^2 \frac{\alpha}{2} + \sin^2 \frac{\alpha}{2} \right) = \Delta q \cdot 2Bv.$$

类似地考虑每对直径相对的部分，我们发现磁场作用在木桩上的力的水平投影等于零，垂直投影等于

$$F_y = \sum_i F_{yi} = 2vB \sum_i \Delta q_i,$$

其中$\sum_i \Delta q_i$是构成半个环的粒子所有元素的电荷之和，即$\sum_i \Delta q_i = \frac{q}{2}$。因此，

$$F_y = qvB.$$

让我们写下环在垂直投影上的平衡条件：

$$mg = N + qvB.$$

根据问题$N = mg/2$的条件，因此，

$$qvB = mg/2.$$

从这里

$$v = mg/2qB.$$

L·G·马尔科维奇

◆ 当右壁中心施加力$F_1$ 时，当该力等于作用在固定支架上的摩擦力$\mu N'_1$ 时，容器就会移动。所以这些支撑上的地板压力是 -

$$N_1 = F_1/\mu.$$

相对于穿过滚轮的轴线的总力矩必须等于零（容器不会翻倒）。因此（见图1）

$$\frac{mg l}{2} - \frac{F_1 l}{2} - N_1 l = 0.$$

从这里，考虑到$N_1 = F_1/\mu$的事实，我们得到：

$$mg = F_1 \left( 1 + \frac{2}{\mu} \right).$$

当向左面中心（图2）施加力$F_2$时，地板对固定支撑件的压力等于$F_2/\mu$。围绕穿过滚子的轴线的总扭矩等于零导致符合相应的扭矩。

$$mg = F_2 \left( \frac{2}{\mu} - 1 \right).$$

（$F_2 > F_1$，因为在第二种情况下，力矩$F_2$会导致固定支架上产生额外负载，从而导致摩擦力增加。）

一起求解 (1) 和 (2)，我们找到 $m$：

$$m = \frac{2F_1 F_2}{g (F_2 - F_1)}.$$

有些冰箱的支撑结构与我们的集装箱相同。它们很容易朝滚轮移动，但朝相反方向移动则困难得多。有时冰箱根本不想滑动，而是开始翻倒。这发生在摩擦系数达到一定值时。对于质量分布均匀的“立方体”冰箱 - $\mu \geq 1$。得到极限值$\mu$

⟦folio 40⟧

F854。估计为了让充气床垫睡在直边下方的中间而必须施加到充气床垫边缘的平均力。床垫没有横向超载。自己设置解决方案所需的数量及其相当现实的数值，并获得数值结果。

让我们估计一下将床垫安装成直角需要做的工作。从数量级上看，可以估算为$A \sim p \cdot \Delta V$，其中$p$是大气压力与床垫内部气压的差值，$\Delta V$是床垫在变形过程中体积的变化。从图可以看出，$\Delta V$约等于三角形$ABC$的面积与床垫宽度$b$的乘积：

$$\Delta V \approx \frac{2d \cdot d}{2} b = d^2 n,$$

其中$d$是床垫的厚度。

另一方面，弯曲床垫的功可以估计为平均力 $F_{cp}$ 和行进距离的乘积：

$$A \approx F_{cp} \frac{2\pi l}{4} \sim F_{cp} l$$

（l是床垫的长度）。

从上面的表达式可以看出

$$A \sim p \cdot \Delta V \sim p d^2 b \sim F_{cp} l,$$

在哪里

$$F_{cp} \sim \frac{p d^2 b}{l}.$$

对于数值计算，您可以输入 $b \approx 0,8$ m、$d \approx 0,15$ m、$l \approx 2$ m。估计$p$比较困难。让我们使用这个想法。如果您用脚站在床垫上，那么它通常会继续接触地面。因此，$p$与人的脚对地面施加的压力具有相同的量级：

$$p \sim \frac{mg}{S} \sim \frac{700 \text{ H}}{0,2 \cdot 0,3 \text{ m}^2} \sim 10^4 \text{ Pa}.$$

我们最终计算出：

$$F_{cp} \sim \frac{10^4 \Pi a \cdot (0,15 \text{ m})^2 \cdot 0,8 \text{ m}}{2 \text{ m}} \sim 10^2 \text{ H},$$

这与我们的日常经验非常吻合。

E·I·帕尔奇科夫

F855。将一个扁平电容器连接到电动势为 $\delta$ 的电池极上，并通过带电极板完全平行于其极板插入，距离电容器其中一个极板的距离为 $b$（参见图）。如果电荷为$q$，求作用在输入板上的力。接下来运行。电容器极板的面积为$S$，电容器极板之间的距离为$d$。

电容器内部的电场是带电荷 $q$ 的极板产生的场与电容器极板的电荷产生的场的总和。例如，这些字段被指定为对应于$E$和$E_1$。 （在图上，字段$E$和$E_1$的方向表示正电荷进入板的情况。）

作用在插入板上的力等于

$$F = q E_1.$$

电压$E_1$可以通过将电容器板之间的电势差写成形式来找到

$$\delta = (E_1 + E)(d - b) + (E_1 - E) b.$$

从这里

$$E_1 = \frac{\delta + E(2b - d)}{d}.$$

代入$E = q/2\varepsilon_0 S$，我们得到：

$$E_1 = \frac{\delta + q(2b - d)}{2S\varepsilon_0}.$$

因此，作用在插入板上的力为
