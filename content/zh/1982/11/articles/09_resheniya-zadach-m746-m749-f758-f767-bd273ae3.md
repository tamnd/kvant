---
id: 1982-11-resheniya-zadach-m746-m749-f758-f767-bd273ae3
issue: kvant_1982_11
year: 1982
number: "11"
title: 问题解决方案M746—M749； F758—F767
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 42
page_labels: 29, 30, 32, 33, 34, 35, 36, 38, 39, 40
tag: BAZA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4f37e986f3ab64767aece1f3280411776c70107cda25b375e9c92184aa6fabbf
prompt_sha256: draft-1
translated_from: content/ru/1982/11/articles/09_resheniya-zadach-m746-m749-f758-f767-bd273ae3.md
source_content_sha256: c6ba27411217320a91f91365e0d3d620259ddb78d3af6f859c260e7aea76a53f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 29⟧

P786. Forces of attraction between molecules act in a nonideal single atom gas. Assuming that the potential energy of molecular interaction is proportional to the gas density, i.e. $\Pi = \alpha \frac{N}{V}$, where $N$ is the number of gas molecules, $V$ the volume of gas, $\alpha$ a coefficient ($\alpha < 0$). Find the difference between the molar heat capacities at constant pressure ($c_p$) and at constant volume ($c_V$).

V. Tugushev

P787. The voltage of a source varies linearly. At the initial moment it was zero. The switch $K$ can be used to connect the source to the circuit shown on figure Pric. 2, p. 27). At what moment should the switch be turned on to make the current in the circuit constant? The resistance is $R$, the capacity is $C$.

A. Zilberman

问题解决方案

M746。将纸正方形沿着穿过其中心的特定直线$l$对折成（非凸）九部分系统。如何绘制直线 $l$ 以便：
a) 由此产生的九部分面积是否最大？
b)* 它是否包含一个半径尽可能最大的圆？

图 1.

图 2.

令正方形对折的直线$l$与其水平边形成角度$\alpha (0 \leqslant \alpha \leqslant 45^\circ)$，则正方形的边长为$2q$。

a) 如果将正方形沿直线$l$折叠得到的图形补充一个对称的图形（相对于正方形$O$的中心或相对于直线$l$ - 没关系！），那么你就得到了图1所示的多边形 - 正方形与角度$2\alpha$的曲面的并集。它有四个对称轴。为了找出它的面积何时最大，我们注意到它可以通过一个额外的正方形 $2q \times 2q$ 和四个相同的粉红色直角三角形来获得。它们的斜边$c$和边$a, b$很容易找到，然后注意$a + b + c = 2q$，$a = c \sin 2\alpha$，$b = c \cos 2\alpha$，$c = 2q / (1 + \sin 2\alpha + \cos 2\alpha) = 2q / (1 + \sqrt{2} \cos(45^\circ - 2\alpha))$；三角形的面积为$q(q - c)$，当斜边$c$最小时，在$\alpha = 22,5^\circ$处最大。因此，图 1 处的 16 边形在具有 8 个对称轴（图 2）的“星”形时，其最大面积为$8q^2(2 - \sqrt{2})$；同样角度$a = 22,5^\circ$，它的一半面积最大。

6) 答案：复正方形中最大的圆位于$\alpha_0 = 2$ arctg $2 - 90^\circ \approx 36,87^\circ$；它的半径$r_0$等于$5q/8$，对应的直线$l$以1:7的比例划分正方形的边。几何实验有助于证实这个答案：如果每个$2^\circ$或$3^\circ$（从$\alpha = 0^\circ$到$\alpha = 45^\circ$）更精确地构造出相应的图形（可以方便地从纸板上剪出一个更大的正方形，用按钮在中心刺穿它并用它来构造正方形的主面和表面，并用圆规和尺子为每个$\alpha$构建一个更大的圆“），你可以相当准确地绘制最大圆$r$的半径对$\alpha$（图3）的依赖性。在该函数的图形上，突出显示了几个点$a_i$ - 线段$0^\circ \leqslant \alpha \leqslant 45^\circ$被分为5块，每块上的最大圆由不同的几何条件确定，因此其半径由不同的（有时非常繁琐）公式表示。然而，$\alpha_0$也是这些奇点之一，因此在点$a_0$处，函数$r = r(\alpha)$不是任意的，必须在不同的部分上单独评估它。

图2、4-7显示了随着$\alpha$从$0^\circ$变为$45^\circ$，最大圆“演化”的一些阶段。看着它们，就不难想象剩下的了：对于$\alpha = 0^\circ$，任何接触正方形一半长方形边长的圆都是合适的；在

⟦folio 30⟧

0° < α < α₁ 圆与直线 l = (MN)、MB 和 CK 相交，点 L 位于其外侧；对于 α = α₁ 点 L 落在圆上； α₁<α<α2的情况如图4所示；对于 α2 ≤ α ≤ α₃，圆与 l 相切并经过 L 和 K 点，对于 α = α2，它在 K 点相切 (CK)，对于 α = α₃，它在 L 点相切 (MC)；这包括“星号”(图2)；其余情况如图 5、6 和 7 所示。

让我们证明圆的半径始终不大于 5q/8，并且仅当 α = α₀ 时才相等。我们将省略推理的一些细节，但从图中的铭文中重建它们并不困难。

对于 α₀ ≤ α ≤ 45°，一切都很简单：最大圆在 O 点与直线 l 相切，并与五边形的两侧相切，与相对直线 OK 对称；其半径r为(图7)

$$r = q \mathrm{tg}(45° - \alpha/2) / \cos \alpha = q/2 \cos^2(45° - \alpha/2) = q/(\cos(90° - \alpha) + 1)$$

并且，显然，随着 α 从 45° 减小到 α₀ 增大（从 (2 - √2)q 到 5q/8）； α₀和r₀的值可以由图6处的三角形ONQ和ONK确定。

α较小的情况也不会造成任何困难：显然，只要最大圆接触（CK），其直径就不会超过|MC| （图4）。如果|MC| < 5q/4，即 α < arctan 1/4 ≈ 14.43°，则更是如此 r ≤ 1/2 |MC| <5q/8。

对于最大圆经过 L 点的 α 值，即 α₁ ≤ α ≤ α₃，作为其半径的估计，我们可以取经过 K、L 和 O 点的圆的半径（参见 图 4），等于 |KL|/2 sin KO L = c/2 sin 45° = q/(\sqrt{2}/2 + cos(45° - 2α))（参见a）点的解决方案）。在 cos(45° - 2α) ≥ 8/5 - √2/2 ≈ 0.8929 时，该半径不超过 5q/8，即 9.12° < α < 35.88°。由于该间隔与前一个间隔重叠，因此检查从 0° 到至少 α₃ 的所有 α 值。

仍有待证明在 [α₃; 上] r < r₀ = 5q/8 α₀]，其中最大的圆位于如 图 5 所示。让我们固定一个半径为 r₀ 的圆，并证明如果我们将折叠的正方形附加到其上，使其内切于角度 CMO，则点 K 将位于圆内部（或对于 α = α₀ 而言位于其上）。这意味着在我们的图形中不可能放置一个大半径的圆。

我们将在最低点 T (图 8) 处水平绘制与半径为 r₀ 的圆相切的边 MO。为了构造点 K = K(α)，需要从点 T 向左关闭长度为 r₀tg(45° + α/2) 的线段 TM（回想一下 OMC = 90° - α），然后检查与 MO 成 45° 角的长度为 q√2/cos α 的线段 MK（△OMK 是等边矩形，|OM| = q/cos α）。当α=α₀时，K点落在圆的顶点；随着 α 减小，它以等于两个速度矢量和的速度移动：一个沿着直线 MO，指向右侧，其值 u = r₀|tg(45° + α/2)|' = r₀/2 cos²(45° + α/2) = r₀/(1 - sin α)，另一个 - 沿着直线 K(α)M(α) - 向后和向下指向，其大小等于 v = q√2|(1/cos α)'| = q√2sin α/(1 - sin²α) （α₀ - α≥ 0 值混合）。我们只对α₀附近的一小部分α值感兴趣；但即使我们继续将 K 点移动到 α = 0°，它也不会超出圆，因为在 α = 0° √2 q = |MK| 时< r₀(√2 + 1)。如果我们还注意到 u/v 比率随着减小而返回

⟦folio 32⟧

$$= |\vec{a}| \left( \sin \frac{\pi}{2} - \sin \left( -\frac{\pi}{2} \right) \right) = 2 |\vec{a}|.$$

因为

$$|\vec{a}_1| + \dots + |\vec{a}_n| = \frac{1}{2} \int_0^{\pi} \left( a_1(\varphi) + \dots + a_n(\varphi) \right) d\varphi \geqslant$$

$$\geqslant \frac{1}{2} \int_0^{\pi} \left( b_1(\varphi) + \dots + b_m(\varphi) \right) d\varphi = |\vec{b}_1| + \dots + |\vec{b}_m|.$$

现在让 $A'_1, \dots, A'_n$ 和 $O'$ 为点 $A_1, \dots, A_n$ 和 $O$ 在任意直线上的投影（参见 图）。根据引理，我们只需证明

$$p' = |A'_1A'_2| + |A'_2A'_3| + \dots$$

$$\dots + |A'_nA'_1| \geqslant \frac{4}{n} \left( |O'A'_1| + \dots + |O'A'_n| \right).$$

注意$O'A'_1 + \dots + O'A'_n = 0$，因为投影和几个向量的和等于它们的投影之和。因此，以原点$O'$为原点的数轴$l$上的点$A'_1, \dots, A'_n$的坐标构成满足a)点条件的数集。这些数的$a$绝对值之和等于不等式（*）右边的和，其中最大和最小之差就是多边形的投影长度，即其所有边的投影长度之和$p'$的位置。凭借陈述a) $p'/2 \geqslant 2a/n$ 和不等式(*) 被证明。

第二个解决方案。 （这个解是由莫斯科第 18 物理学校 10 年级学生 S. Matyushov 提出的。）对于任意点 $A$

$$\overrightarrow{OA} = \frac{1}{n} \left( (\overrightarrow{OA}_1 + \overrightarrow{A_1A}) + \dots + (\overrightarrow{OA}_n + \overrightarrow{A_nA}) \right) =$$

$$= \frac{1}{n} \left( \overrightarrow{OA}_1 + \dots + \overrightarrow{OA}_n \right) + \frac{1}{n} \left( \overrightarrow{A_1A} + \dots + \overrightarrow{A_nA} \right) =$$

$$= \frac{1}{n} \left( \overrightarrow{A_1A} + \dots + \overrightarrow{A_nA} \right).$$

这立即意味着不平等

$$|OA| \leqslant \frac{1}{n} \left( |AA_1| + \dots + |AA_n| \right).$$

将 $A = A_1, A = A_2, \dots, A = A_n$ 依次代入其中，将所得的所有不等式相加，我们发现

$$d = |OA_1| + \dots + |OA_n| \leqslant \frac{2}{n} \sum |A_iA_j|$$

(**)

（每一项$|A_iA_j|$、$1 \leqslant i < j \leqslant n$都包含在和中一次，因此用多边形所有边和对角线的长度之和来表示）。

对于奇数$n$，有$n$边，$n$对角线切割1个顶点，$n$对角线切割2个顶点，...，$n$对角线切割$\frac{n-3}{2}$顶点。切断$k$顶点的对角线长度不超过从连接对角线两端的多边形边开始的$(k+1)$连线折线的长度。因此，这些对角线的长度之和不超过$(k+1)p$，其中$p$是多边形的周长，(**)重写如下：

$$d \leqslant \frac{2}{n} \left( p + 2p + \dots + \frac{n-1}{2} p \right) = \frac{n^2 - 1}{4n} p,$$

即$p \geqslant \frac{4n}{n^2 - 1} d.$

⟦folio 33⟧

对于偶数$n$，不同之处在于切断$n/2$顶点的对角线数量为$n/2$。由于它们每个的长度不大于$p/2$，从(**)我们得到

$$d \leq \frac{2}{n} (p + 2p + \dots + \frac{n-2}{2} p + \frac{n}{4} p) = \frac{n-2}{4} p + \frac{1}{2} p = \frac{n}{4} p,$$

即$p \geq 4d/n$。

c) 从解到点 6) 可以得出，对于奇数 $n$，估计更准确：$p \geq \frac{4n}{n^2-1} d > \frac{4d}{n}$。无法进一步澄清。事实上，让$n = 2k$或$n = 2k+1$。考虑一个退化的“$n$边形”，其中 $k$ 顶点位于一个点，其余 $n-k$ 顶点位于另一点。很容易看出，这样的“$n$边形”的比率$p/d$恰好等于$n = 2k$的$4/n$和$n = 2k+1$的$4n/(n^2-1)$。很明显，可以稍微扩展其顶点，以便形成“真正的”凸 $n$ 边形，而 $p/d$ 的值与我们指示的边界的差异尽可能小。

V·普拉索洛夫

M748。 a) 平面上是否可以有有限数量的抛物线，使其内部区域覆盖整个平面？ （我们将抛物线的内部区域称为凸图形，其边界就是该抛物线。）

6)* 空间中有多个不相交的端点。证明它们无法移动，从而覆盖整个空间。 （我们在这里称圆锥为无限凸形，是通过在其 bissertis 周围处理 neotorodo uel 获得的结果。）

图 1.

图 2.

a) 让我们画一条不平行于抛物线任何轴的任意直线。这样的直线只能沿着一个区间与任何抛物线的内部区域相交。事实上，某个坐标系下的抛物线方程具有$y = ax^2$($a > 0$)形式，直线方程具有$y = kx + l$形式；属于抛物线内部的直线上的点的横坐标满足不等式$kx + l > ax^2$，其解集要么为空。或者是区间$x_1 < x < x_2$，其中$x_1$和$x_2$是方程$ax^2 - kx - l = 0$的根。

由此可见，在所画的线上，他将找到不属于抛物线任何内部区域的点。

6) 令$O$为空间中的任意点，$K'$为顶点为$Q$的圆锥体$K$通过将点$Q$平行平移到点$O$而获得的圆锥体。让我们绘制一条任意射线 $l$，其原点位于点 $O$。让我们考虑通过射线 $l$ 和点 $Q$ (图 1) 的平面对端部 $K$ 和 $K'$ 的截面。它与具有平行边的两个角的圆锥体相交；利用这一点，很容易验证光线 $l$ 沿光线与圆锥体 $K$ 相交当且仅当它完全包含在圆锥体 $K'$ 中。否则，射线 $l$ 与圆锥$K$ 沿线段相交或在一点 $Q$ 相交，或者根本不相交。

现在我们将所有端点的顶点相交于点$O$，并证明没有两个圆锥$K'_1$和$K'_2$有公共点$A \neq O$。那么光线 $l = [OA)$ 就包含在它们每一个中。如图所示，在这种情况下，射线 $l$ 沿着某些射线 $l_1$ 与圆锥体 $K_1$ 相交，并沿着射线 $l_2$ 与圆锥体 $K_2$ 相交。但光线 $l_1 \cap l_2$ 属于共同锥体 $K_1$ 和 $K_2$。矛盾。

现在让我们考虑一个中心位于点 $O$ 的球体。它沿着某个“球冠”（图2）与“花束”的每一端相交。由于所有“帽子”并不成对相交，因此它们的总面积小于球体的面积。因此，无论我们如何在球体周围移动它们，都不可能掩盖我们球体的名字。这意味着对于球体上空间中末端的任何位置，它将找到一个未被“盖子”覆盖的点。如果$A$是这样一个点，那么射线$[OA)$只能沿着有限数量的线段与圆锥体相交。因此，在这条射线上它会完全找到不属于任何端点的点。

A·库兹米内赫

⟦folio 34⟧

M749*。 a) 证明如果$x_1, x_2, x_3$是正数，那么
$$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_1} + \frac{x_3}{x_1+x_2} \geq \frac{3}{2};$$
在什么条件下这种不平等会变成平等？
b) 证明如果$x_1, x_2, \dots, x_n (n \geq 4)$是正数，那么
$$\frac{x_1}{x_2+x_n} + \frac{x_2}{x_3+x_1} + \dots + \frac{x_{n-1}}{x_n+x_{n-2}} + \frac{x_n}{x_1+x_{n-1}} \geq 2,$$
此外，只有$n=4$才可能相等。
c) 证明对于$n>4$，b)部分的不等式是精确的，因为对于没有$n$，右侧的数字2不能被更大的数字代替。

图 1.

图 2.

a) 设 $a=x_2+x_3, b=x_3+x_1, c=x_1+x_2$。那么$x_1 = \frac{b+c-a}{2}, x_2 = \frac{a+c-b}{2}, x_3 = \frac{a+b-c}{2}$，不等式左边将改写如下：
$$\frac{b+c-a}{2a} + \frac{a+c-b}{2b} + \frac{a+b-c}{2c} =$$
$$= \frac{1}{2} \left( \frac{b}{a} + \frac{a}{b} \right) + \frac{1}{2} \left( \frac{c}{a} + \frac{a}{c} \right) + \frac{1}{2} \left( \frac{b}{c} + \frac{c}{b} \right) - \frac{3}{2}.$$
由于众所周知的 $x + \frac{1}{x} \geq 2$ 与 $x>0$ 的不等式，该表达式中的每个括号均不小于 2。因此，整个左边至少是3—$\frac{3}{2} = \frac{3}{2}$。由于$x + \frac{1}{x} = 2$仅适用于$x=1$，因此已证明的不等式仅适用于$a=b=c$。
b) 让我们证明$n$ 上的归纳不等式。对于 $n=4$ 显而易见：
$$\frac{x_1}{x_2+x_4} + \frac{x_2}{x_3+x_1} + \frac{x_3}{x_4+x_2} + \frac{x_4}{x_1+x_3} =$$
$$= \frac{x_1+x_3}{x_2+x_4} + \frac{x_2+x_4}{x_1+x_3} \geq 2;$$
当且仅当 $x_1+x_3=x_2+x_4$ 时，平等才可能。
现在让我们证明任意正数 $x_1, \dots, x_{n+1}$ 的不等式，假设它对于任何 $n (n \geq 4)$ 正数都有效。我们选择最小的数字$x_1, \dots, x_{n+1}$。由于它们对称地进入不等式，因此不失一般性，我们可以假设这是 $x_{n+1}$。然后 $x_{n+1}>0$、$x_{n+1} \leq x_n$ 和 $x_{n+1} \leq x_1$，因此
$$\frac{x_1}{x_2+x_{n+1}} + \frac{x_2}{x_3+x_{n+1}} + \dots + \frac{x_n}{x_{n+1}+x_{n-1}} + \frac{x_{n+1}}{x_1+x_{n}} > \frac{x_1}{x_2+x_n} + \frac{x_2}{x_3+x_1} + \dots + \frac{x_n}{x_1+x_{n-1}} \geq 2$$
（最后一个不等式由归纳假设满足）。一路走来，我们发现对于$n>4$来说，平等就是不平等。
c) 数字$x_1, \dots, x_n$方便排成一圈；那么不等式左边的每一项都被认为是这些数字之一除以它相邻的两个数字之和。对于$n=2k$，我们定义$x_i$，如图 1 所示，对于$n=2k+1$，如图 2 所示。
在第一种情况下，我们得到总和
$$2 \left( \frac{1}{q+1} + \frac{q}{q^2+1} + \frac{q^2}{q^3+q} + \dots + \frac{q^{k-1}}{q^{k-1}+q^{k-2}} \right) =$$
$$= 2 \left( 1 + \frac{(k-2)q}{q^2+1} \right),$$
在第二个 -
$$\frac{1}{2q} + 2 \left( \frac{q}{q^2+1} + \frac{q^2}{q^3+q} + \dots + \frac{q^k}{q^k+q^{k-1}} \right) =$$
$$= \frac{1}{2q} + \frac{2(k-1)q}{q^2+1} - \frac{2q}{q+1} =$$

⟦folio 35⟧

$$= 2 + \left( \frac{1}{2q} + \frac{2(k-1)q}{q^2+1} - \frac{2}{q+1} \right).$$

在这两种情况下，如果 $q$ 足够大，左边的值将任意接近 2，因此不等式中的数字 2 不能用更大的数字代替。

A·叶戈罗夫

F758。刚性工件被夹紧在两个平行导轨之间，导轨以速度 $\vec{v}_1$ 和 $\vec{v}_2$ 沿水平方向移动。在某些时刻，工件与导轨的接触点位于垂直于矢量$\vec{v}_1$和$\vec{v}_2$的直线上。此时工件上哪些点的速度绝对值等于$v_1$和$v_2$？

当前位于线段$AB$上的工件点的速度均匀地从点$A$处的$\vec{v}_1$变化到点$B$处的$\vec{v}_2$。因此，此时$O$（见图）点的速度为零。点$O$是瞬时旋转中心。 （由于工件是体积的，因此点 $O$ 位于垂直于绘图平面的瞬时旋转轴上。）显然，给定时刻的速度 $|\vec{v}_1|$ 的工件点位于半径为 $OA$ 的圆上，速度 $|\vec{v}_2|$ 的点位于半径为 $OB$ 的圆上。 （在体积工件中，具有这样速度的点位于半径分别等于 $|OA|$ 和 $|OB|$ 的圆柱面上。）

S·克罗托夫

F759。一根长度为 $l$ 且末端带有小质量负载 $m$ 的失重杆铰接在点 $A$ (图 1) 处，并且处于垂直位置，接触质量体 $M$。只需轻轻一推，系统就开始移动。在$m$和$M$之间的比例是多少时，杆在与物体$M$“分离”的那一刻会与地平线形成$α = \pi/6$角？此时身体$M$的速度是多少？忽略趋势。

只要负载接触到物体，物体的速度就等于负载速度的水平投影，物体的加速度等于负载加速度的水平投影。

令 $\vec{a}$ 为负载的总加速度。那么我们可以写：$\vec{a} = \vec{a}_\tau + \vec{a}_u$，其中$\vec{a}_u$是负载沿半径为$l$的圆运动时的向心加速度，即$|\vec{a}_u| = v^2/l$，其中$v$是负载速度的模数。负载加速度的水平投影等于（见图2）

$$a_r = a_\tau \sin \alpha - \frac{v^2}{l} \cos \alpha.$$

身体以这样的加速度移动。身体运动方程 -

$$N = Ma_r = Ma_\tau \sin \alpha - M \frac{v^2}{l} \cos \alpha,$$

其中$N$是来自负载的法向压力。在解除负载$N = 0$的瞬间，并且

$$a_\tau \sin \alpha = \frac{v^2}{l} \cos \alpha.$$

分离瞬间的加速度 $a_\tau$ 仅通过重力传递给负载（参见 图 2）

$$a_\tau = g \cos \alpha.$$

因此，分离瞬间的速度等于

$$v = \sqrt{g l \sin \alpha},$$

⟦folio 36⟧

物体的速度是

$$u = v \sin \alpha = \sin \alpha \sqrt{g l \sin \alpha}.$$

根据能量守恒定律，当杆与地平线成$\alpha$角时，

$$m g l = m g l \sin \alpha + m \frac{v^2}{2} + M \frac{v^2 \sin^2 \alpha}{2}.$$

将分离时刻的$v$表达式和值$\sin \alpha = \sin \frac{\pi}{6} = \frac{1}{2}$代入这个等式，我们找到比率$M/m$：

$$\frac{M}{m} = \frac{2 - 3 \sin \alpha}{\sin^3 \alpha} = 4.$$

当负载被提升时，物体的速度等于

$$u = v \sin \alpha = \frac{1}{2} \sqrt{\frac{g l}{2}}.$$

F760。将质量为 $m_2 = 1$ g 的钢球以 $v = 100$ m/s 的速度放入装有 $m_1 = 20$ g 蔬菜的隔热容器中。开始改变容器内的温度。球对容器壁的冲击以及原子对球的冲击被认为是绝对弹性的。

◆

过了很长一段时间，球就会失去几乎所有的速度（它的质量比绿色原子的质量大很多倍），我们可以假设进入容器的气体的内能变化等于球的初始动能：

$$\frac{m_2 v^2}{2} = \Delta U = \frac{3}{2} N k \cdot \Delta T = \frac{3}{2} k N_A \frac{m_1}{\mu} \cdot \Delta T,$$

(*)

其中$N = N_A \frac{m_1}{\mu}$是容器中绿色原子的数量，$\Delta T$是绿色温度的变化。鉴于$k N_A = R$，从(*)我们发现：

$$\Delta T = \frac{m_2 v^2 \mu}{3 m_1 R} \approx 0,08 \text{ K}.$$

更准确的解决方案应考虑球温度的增加。然后

$$\frac{m_2 v^2}{2} = c m_2 \cdot \Delta T' + \frac{3}{2} \frac{m_1}{\mu} R \cdot \Delta T'$$,

其中$c = 0,5 \cdot 10^3$ J/(kg K)是钢的比热容。 From here comes $\Delta T'$:

$$\Delta T' = \frac{m_2 v^2}{2 \left[ c m_2 + \frac{3}{2} \frac{m_1}{\mu} R \right]} \approx 0,08 \text{ K}.$$

事实证明答案几乎是一样的。

◆

流过电压表$B_2$的电流$I_3$等于流过电流表$A_1$和$A_2$的电流之差：

$$I_3 = I_1 - I_2 = 0,2 \text{ мA}.$$

在这种情况下，电压表读数为$B_2 - U_2 = 0,25 \text{ B}$。因此，电压表$B_2$和$B_1$的电阻

$$R_{B1} = R_{B2} = U_2/I_3 = 12,5 \cdot 10^2 \text{ Ом}.$$

流过电压表的电流$B_1 - I_1 = 1,1 \text{ мA}$；在这种情况下，电压表$B_1$显示

⟦folio 38⟧

F764。冲击波是沿X轴（图1）方向以高速v传播的高压区域；在波浪到来的那一刻，压力从p0急剧上升到2p0。波传播路径上有一个楔子，楔子的尺寸用图2表示，楔子的质量为m。冲击波阵面通过楔块后立即获得的速度是多少？假设楔子获得的速度远小于波传播的速度；摩擦力可以忽略不计。

$$v_A = \frac{v}{2\sqrt{1 - \left(\frac{d}{2R}\right)^2}}$$

S·克罗托夫

让我们选择沿 X 轴的参考原点，如图 2 所示。然后作用在楔块上的力仅取决于冲击波前的 x 坐标。该力的水平投影等于

$$F_x = p_0 c x \ t g a = \frac{p_0 c x a}{b} = \frac{p_0 c v t a}{b},$$

其中 x = vt 是从波开始穿过楔块开始的时间 t 时波前的坐标。在给定时间施加到楔块的加速度等于

$$a_t = \frac{F_X}{m} = \frac{p_0 c a}{b m} \ v t.$$

在t0时刻，当波前到达楔块的最远边缘时，即波前坐标等于b=vt0时，楔块的加速度为

$$a_t0 = \frac{p_0 c a}{m}.$$

图 1.

图 2.

由于楔块与时间呈线性关系，为了计算 t0 时刻楔块的速度 u，我们使用平均加速度值 acp = \frac{p_0 ca}{2m}：

$$u = a_{cp} t_0 = \frac{p_0 abc}{2mv}.$$

当楔块的重量置于压力增加的区域时，作用在楔块上的净力将为零。

可以看出，条件 u << v 意味着

$$p_0 \ll 2mv^2/abc.$$

A·布丁

F765。目前，地球上所有利用人类的能源的功率为ΔP=10^{13}W，太阳能进入地球的功率为P0=i\theta^{17}W。过热到什么程度ΔT

我们假设受热体发出的功率P与绝对温度T的依赖程度P=σT^n，其中σ是一些比例系数。然后对于辐射体 T1 和 T2 的两个温度，我们得到：

$$P_1 = \sigma T_1^n, \quad P_2 = \sigma T_2^n, \quad \frac{P_1}{P_2} = \left(\frac{T_1}{T_2}\right)^n.$$

⟦folio 39⟧

地球表面是由陆地能源驱动的吗？如果环境信息的最大过热度不应超过值 $\Delta T_{\text{max}} = 0,1$ K，则最大允许值 $\Delta P_{\text{max}}$ 是多少？众所周知，物体的绝对温度每增加2倍，单位时间发出的能量就会增加16倍。

从这里使用问题的数据很容易获得$n = 4$。

所以，$P = \sigma T^4$。现在你可以写：

$$P_0 + \Delta P = \sigma (T_0 + \Delta T)^4 \approx \sigma T_0^4 (1 + 4 \frac{\Delta T}{T_0} + \dots).$$

从$\Delta T/T_0 \ll 1$开始，第二个和更高阶的项可以在最后一个表达式中被丢弃。然后我们得到：

$$\Delta P = 4P_0 \frac{\Delta T}{T_0}.$$

从这里开始是：

$$\Delta P = \frac{\Delta P}{4P_0} T_0 \approx 10^{-2} \text{ K},$$

$$\Delta P_{\text{max}} = 4P_0 \frac{\Delta T_{\text{max}}}{T_0} \approx 10^{14} \text{ Bt}.$$

这样一来，人类使用的地球上所有能源的威力最多只能增加10倍。 （当然，这不适用于使用太阳能的来源。）

S·科泽尔

F766。对于高科技灯，使用了非线性电容器（它充满了电介质，其介电值取决于场电压）。电压$U$ 与电容器电荷$Q$ 的关系图如图 1 所示。电容器由电池$c$ $U_0 = 300$ V 通过电阻为$R = 10$ kOhm 的电阻充电。求 vysshiki 的最大能量。估计 1 分钟内的最大塔数。假设在高电压下电容器完全放电。最小初始电压为$U_1 = 250$V。

最大搜索能量在数值上等于曲线图下方的面积$U(Q)$，受值$U = U_0 = 300$ V 限制（在本例中为$Q \approx 0,3$ K；参见图 1）。为了计算该面积，我们将曲线 $U(Q)$ 划分为多个部分，在这些部分上，$U(Q)$ 的相关性可以近似视为线性。在每个这样的区域下，面积在数值上等于 $U_i \cdot \Delta Q_i$。因此，最大搜索能量为（参见图1）

$$W \approx \left( \frac{140}{2} \cdot 0,05 + \frac{140 + 200}{2} \cdot 0,075 + \frac{200 + 300}{2} \cdot 0,175 \right) \text{ Дж} = 60 \text{ Дж}.$$

公式 $I \cdot \Delta t = \Delta Q$ 提出了一种查找电容器从 0 到 250 V 充电时间的简便方法，其中 $\Delta t = \Delta Q/I$ 和

$$t_{\text{обш}} = \sum \frac{1}{I} \cdot \Delta Q.$$

我们来画一张 $1/I$ 对 $Q$ (图 2) 的依赖关系图。给定值 $Q$ 处的电流根据 图 1 处的图表：

图 1.

$$I = \frac{U_0 - U}{R}.$$

曲线图下方的面积受值$I = 200$ A、$Q = 0,2$ C 的限制，在数值上等于电容器的高度

$$t_{\text{обш}} \approx \left( \frac{33 + 100}{2} \cdot 0,125 + \frac{100 + 200}{2} \cdot 0,075 \right) c \approx 20 \text{ c}.$$

⟦folio 40⟧

F767。在其中一项发电项目中，建议利用海流和地球磁场。该项目将包括以下内容。

将两块水平金属板放置在海中，一块位于另一块上方，距离$l=100$米；每个板块的面积为$S=1$km$^2$。海水的电阻率为$\varrho=0,25$欧姆·米，在板块之间自西向东以$v=1$米/秒的速度流动。地球磁场在某一特定地点是均匀的，方向是从南到北；场感应为 $B=10^{-4}$ T。确定每个连接到极板的电压可以释放的最大电功率。

海水具有明显的非导电性，因此当带电离子在地球磁场中移动时，它们会从洛伦兹场偏转到其中一个水平板。结果，该板上将出现未补偿的电荷，并且板之间出现电场。该场以与洛伦兹力相反的力作用于纳子。电荷在其中一个板上的填充将会发生，直到这些电荷的电场平衡洛伦兹力的作用。请注意，要发生这种平衡，在板之间流动的离子总数中的一小部分偏离到其中一个板就足够了。

确定水平板之间没有电流时产生的电压$\mathcal{E}$，即所得“发电机”的电动势。如果 $q$ 是 ins 的电荷，那么在平衡条件下

$$qvB=q\mathcal{E}/L \Rightarrow \mathcal{E}=vBL.$$

如果板连接到外部负载$R$，则电流$I$将流过它；而板间海水的阻力。等于$\varrho L/S$，将起到生成发电机内阻的作用。

让我们确定负载中释放的功率：

$$P=I^2R=\frac{\mathcal{E}^2R}{(\varrho L/S+R)^2}.$$

为了确定最大功率，使用以下数学事实：对于任何$x>0$，满足不等式

$$x+1/x \geq 2, (x+1/x)^2 \geq 4.$$

在幂公式中，我们将括号中的幂$\varrho L/R/S$带入分母：

$$P=\frac{\mathcal{E}^2R}{\varrho L/R/S(\varrho L/S+RS/L\varrho)^2}.$$

在最后一个公式中，分母括号中的表达式大于或等于 4。因此，对于最大幂，我们有：

$$P_{\max}=\mathcal{E}^2S/4\varrho L=\frac{v^2B^2LS}{4\varrho}=1 \text{ Вт}.$$

（注意，该公式对应于外部负载等于发电机内阻的情况。）
