---
id: 1982-8-resheniya-zadach-m721-m730-f733-f742-9579a45b
issue: kvant_1982_8
year: 1982
number: "8"
title: 问题解决方案M721—M730； F733—F742
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 50
page_labels: 34, 36, 37, 38, 41, 42, 43, 44, 45, 46, 47, 48
tag: O92T
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4b562d280539c2d372f3f430e1309d23fe50558c12e11ffbf2930941aa7063f5
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/11_resheniya-zadach-m721-m730-f733-f742-9579a45b.md
source_content_sha256: 3b1ebca7d4b03d6ab54e6074339ffdd71f163ada6d5a8003f522e02d85655b45
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

key $K$ at the moment $t=0$ to a source of alternating tension $u=U_M \cos \omega t$. Determine the current in the solenoid as a function of time. Construct the graph of this function. The diod and the solenoid are assumed ideal, the inner resistance of the source may be neglected. (10).

V. Skorovarov

P772. An interplanetary space-ship made a soft landing on the Moon. The ship has the form of a disk of radius $r=4\text{m}$, its surface is covered by black (non-reflecting) paint. Can the landing on the Moon be observed from the largest telescope in the world, the Soviet telescope BTA with object lens diameter $D=6\text{m}$, if a photographic plate is placed in the focal plane to take a picture of the area of the Moon where the landing is to take place. Assume that clearly noticeable contrast of the image on the photo (i.e. the minimal relative difference of the dark and light parts of the image) is $k=0.05$. The distance from Earth to Moon is $L=4 \times 10^5\text{km}$; the picture is taken in light with wavelength $\lambda=0.6\text{mkm}$. Estimate the size of letters arranged by astronauts on the moon surface that can be read from the Earth using the BTA telescope. (10)

S. Kozel

问题解决方案

M721—M730; F733—F742

M721。三角形的每条边均分为 3 个相等的部分。分割点是两个三角形的顶点，两个三角形的交点是一个六边形。如果给定三角形的面积为 $S$，则求该六边形的面积。

答案：$\frac{2}{9} S$。让我们证明这个三角形可以分为 27 个大小相等的三角形，其中 6 个组成任务中要解决的六边形。令 $K, L, M, N, P, Q$ 为分割三角形 $ABC$ 边的点，如条件中所指定（参见 图）。请注意，线段$KM$和$QN$、$QL$和$PM$、$KP$和$LN$是平行的，并且对应于该三角形的中线。例如，线段$KM$与介质$AD$平行，因为$\frac{|BK|}{|BA|} = \frac{|BM|}{|BD|} = \frac{2}{3}$，因此准备了三角形$BKM$和$BAD$。从分割点绘制与介质平行的剩余线段以及中线本身，我们获得所需的分区。*）事实上，六边形被分为 6 个全等三角形（在 图 - 头上），另外 12 个三角形（白色）与它们全等，其余 9 个（红色）大小相等。 （比如说，三角形$MEN$和$MFE$的面积相等，因为它们的边$EN$和$EF$是拥塞的，并且从顶点$M$下降到这些边的高度是相同的。）因此，六边形的面积是$6 \cdot \frac{S}{6+12+9} = \frac{2}{9} S$。

A·埃多罗夫

M722。在圆周围的点 $A_1, A_2, \dots, A_n$ 处，数字 1, 2, ..., $n$ 将以某种顺序分散。 a) 证明$n$数差模型之和不小于2n—2。 b) 对于多少种排列来说，这个总和等于 2n-2？

让数字1和$n$分别位于点$A_i$和$A_j$。我们将使用 图 计算相邻数字之间的差异：每个箭头开头的数字从末尾的数字中减去。

*）为了使解决方案完美，我们还必须证明我们构建的线段实际上是三部分相交，如图所示。例如，让 $H$ 为 $[KP]$ 和 $[LQ]$ 的交点。然后以$A$为中心准备三角形$LHP$和$BGC$，因此$H \in [AD]$（G是中线的交点）。同样，$[LN]$和$[MP]$的交点$E$位于$AD$上，因为三角形$MEN$和$BGC$是以$D$为中心准备的，等等。

⟦folio 36⟧

显然，数字之和$b_1, b_2, \dots, b_{k+1}$都不属于集合$A$。证明了集合$B$的存在性。

凭借引理，要陈述问题的答案，只需证明自然数所有可能幂的集合$S = \{a^k | a \geq 1, k \geq 2\}$的密度为零。

让我们估计不超过 $n$ 的 $v_n(S)$ 度数。如果$a^k \leq n$，则$a \leq \sqrt[k]{n}$。因此，$k$次方不超过$n$的自然数最多有$[\sqrt[k]{n}]$个，其中$[x]$是数$x$的整数部分。特别是，对于$k > m = [\log_2 n]$来说，只有一个这样的数字——一。因此，

$$v_n(S) \leq \frac{[\sqrt{n}] + [\sqrt[3]{n}] + \ldots + [\sqrt[n]{n}]}{n} \leq \frac{\sqrt{n} \log_2 n}{n} = \frac{\log_2 n}{\sqrt{n}}.$$

传递到 $n \to \infty$ 处的极限，我们得到

$$d(S) = \lim_{n \to \infty} v_n(S) \leq \lim_{n \to \infty} \frac{\log_2 n}{\sqrt{n}} = 0.$$

L·古尔维茨

**M724。数条岩屑沿平面爬行，速度大小相等，方向不同。证明，无论切屑一开始位于什么位置，一段时间后它们都会位于凸多边形的顶点处。**

让在初始时刻 cherenakh 位于点 $A_1, \dots, A_n$，位于半径为圆的圆上 $R$ 以一点为中心 $O$。让我们从重点开始推迟 $O$ Cherenakh 速度矢量 $\vec{v}_1, \dots, \vec{v}_n$。结局很明显 $V_1, \dots, V_n$ 这些向量是一些凸向量的顶点 $n$- 一个内切于半径为圆的三角形 $v$，等于任何插条的速度。让我们建立半径的圆 $e$ 中心在点 $V_1, \dots, V_n$。用很少的 $e$ 任意多边形 $B_1B_2\dots B_n$，其顶点属于这些圆，是非常indo的，同样会是凸的。 （作为 $e$ 例如，您可以采用距点的距离的最小值 $V_i$ 到连接 的直线 $V_i$ 峰，见 图.)

令时间$T$之后位于点$A'_1, \dots, A'_n$，并令在以$O$为中心、系数为$\frac{1}{T}$的雷暴期间，这些点变成点$B_1, \dots, B_n$。让我们证明，对于足够大的$T$，点$B_1, \dots, B_n$落入我们构建的圆中，即$|V_iB_i| < \varepsilon$对于$i=1, \dots, n$。第 $i$ 个手柄在 $T$ 时间内移动的向量 $\overrightarrow{A_iA'}_i$ 等于 $\overrightarrow{Tv}_i$。因此，$\overrightarrow{OA'}_i = \overrightarrow{OA}_i + \overrightarrow{Tv}_i$和$\overrightarrow{OB}_i = \frac{1}{T}\overrightarrow{OA'}_i = \overrightarrow{v}_i + \frac{1}{T}\overrightarrow{OA}_i = \overrightarrow{OV}_i + \frac{1}{T}\overrightarrow{OA}_i$。因此，$|V_iB_i| = \frac{1}{T}|OA_i| \leq R/T$。这意味着在$T > \frac{R}{\varepsilon}$处，点$B_i$落入半径为$e$、中心为$V_1, \dots, V_n$的圆中，多边形$B_1 \dots B_n$将是凸多边形，然后出现核$T$的点$A'_1, \dots, A'_n$将作为凸多边形的顶点。

V·普拉索洛夫

**M725。* 输入 $r_n = \cos^n \frac{\pi}{7} + \cos^n \frac{3\pi}{7} + \cos^n \frac{5\pi}{7}$。查找 $a)$ $r_1$ 和 $r_2$、$b)$ $r_3$ 和 $r_4$。证明$r_n$对于任何$n$都是有理数。

让$c_k = \cos \frac{\pi k}{7}$位于$k=0, \pm 1, \pm 2, \pm 3, \dots$。请注意，$c_k$ 是单个向量 $\vec{e}_k$ 在 $Ox$ 轴上的投影，与射线 $x \geq 0$、$y=0$ 形成角度 $\frac{\pi}{7}$（参见 图）。很容易验证$c_{7+m} = c_{7-m} = -c_m$。

a) 不难证明

$$\vec{e}_1 + \vec{e}_3 + \vec{e}_5 + \vec{e}_7 + \vec{e}_-3 + \vec{e}_-1 = 0$$

（证明之一：当转动角度$\frac{2\pi}{7}$时，这个

⟦folio 37⟧

向量系统回归自身；在这种情况下，总和不会改变，因此等于 0)。

从 (1) 可以立即得出 $c_7 + 2c_1 + 2c_3 + 2c_5 = 0$，即
$$r_1 = c_1 + c_3 + c_5 = -\frac{1}{2} c_7 = \frac{1}{2}.$$

使用众所周知的公式$2\cos^2\alpha = 1 + \cos 2\alpha$，我们得到$2c_1^2 = 1 + c_2$，$2c_3^2 = 1 + c_6$，$2c_5^2 = 1 + c_{10}$，并且从$c_2 = -c_5$，$c_6 = -c_1$，$c_{10} = -c_3$，我们发现
$$r_2 = c_1^2 + c_3^2 + c_5^2 = \frac{1}{2} (3 - c_1 - c_3 - c_5) = \frac{5}{4}.$$

6), c) 让我们证明 $c_1, c_3, c_5$ 是具有有理系数的三次多项式的根。考虑多项式
$$p(x) = (x - c_1)(x - c_3)(x - c_5) = x^3 + a_1 x^2 + a_2 x + a_3,$$
其根是$c_1, c_3$和$c_5$。让我们用它的根来表达这个多项式的系数。打开括号，我们得到
$$a_1 = -(c_1 + c_3 + c_5) = -r_1 = -\frac{1}{2};$$
$$a_2 = c_1 c_3 + c_3 c_5 + c_5 c_1 = \frac{1}{2} ((c_1 + c_3 + c_5)^2 -$$
$$-c_1^2 - c_3^2 - c_5^2) = \frac{r_1^2 - r_2}{2} = \frac{1}{2} \left(\frac{1}{4} - \frac{5}{4}\right) = -\frac{1}{2};$$
$$a_3 = -c_1 c_3 c_5 = -c_1 c_2 c_4 = -\cos \frac{\pi}{7} \cdot \cos \frac{2\pi}{7} \cdot \cos \frac{4\pi}{7} =$$
$$= -\frac{\sin \frac{\pi}{7} \cdot \cos \frac{\pi}{7} \cdot \cos \frac{2\pi}{7} \cdot \cos \frac{4\pi}{7}}{\sin \frac{\pi}{7}} =$$
$$= -\frac{\sin \frac{2\pi}{7} \cdot \cos \frac{2\pi}{7} \cdot \cos \frac{4\pi}{7}}{2 \sin \frac{\pi}{7}} =$$
$$= -\frac{\sin \frac{4\pi}{7} \cdot \cos \frac{4\pi}{7}}{4 \sin \frac{\pi}{7}} = -\frac{\sin \frac{8\pi}{7}}{8 \sin \frac{\pi}{7}} = \frac{1}{8}.$$

所以，对于每个 $j=1, 3, 5$ 等式
$$c_j^3 - \frac{1}{2} c_j^2 - \frac{1}{2} c_j + \frac{1}{8} = 0.$$
这意味着对于任意 $n \geqslant 2$
$$c_j^{n+1} = \frac{1}{2} c_j^n + \frac{1}{2} c_j^{n-1} - \frac{1}{8} c_j^{n-2}.$$
添加三个这样的等式（对于$j=1, 3, 5$），我们得到$r_n = c_1^n + c_3^n + c_5^n$的递归公式
$$r_{n+1} = \frac{1}{2} r_n + \frac{1}{2} r_{n-1} - \frac{1}{8} r_{n-2},$$
如果 $r_n, r_{n-1}, r_{n-2}$ 已知，则允许计算 $r_{n+1}$。因为，由于 a)、$r_1 = \frac{1}{2}, r_2 = \frac{5}{4}$ 和 $r_0 = 3$，我们发现
$$r_3 = \frac{1}{2} \cdot \frac{5}{4} + \frac{1}{2} \cdot \frac{1}{2} - \frac{1}{8} \cdot 3 = \frac{1}{2},$$
$$r_4 = \frac{1}{2} \cdot \frac{1}{2} + \frac{1}{2} \cdot \frac{5}{4} - \frac{1}{8} \cdot \frac{1}{2} = \frac{13}{16}.$$

⟦folio 38⟧

显然，每个$n$的数字$r_n$都是有理数。 （有关该思想在求解中的应用的更多信息，请参阅文章“考虑差异”，«Kvant»，1981 年，第 4 期。）

N·瓦西里耶夫

M726。正则 2n 空间内的点与顶点相连。由此产生的 2n 个三角形交替着色为“单独”和“红色”。证明头部三角形的面积之和等于红色三角形的面积之和：a) 对于 n=4，6) 对于 n=3，c) 对于任意自然数 n。

由于在正多边形中所有边的长度都相等，因此只需证明红色三角形的高度的长度之和等于头部三角形的高度的长度之和（参见图1）。通过将三角形分成与相对边相邻的对，我们立即得到问题的陈述。

图 1. 图 2

对于奇数 n，通过继续 2n 去除的“红色”边，我们获得正确的 n 接收器 (图 2)。以同样方式构造的头部n-sole被充血为红色。头部n套的面积等于头部三角形的高的长度之和乘以其边长的一半。红n兵也是如此。这意味着头部和红色三角形的高度的长度之和相等，同时也说明了问题。

V·普拉索洛夫

M727。证明不等式$a^2+b^2+c^2+2abc<2$，其中a、b、c是三角形周长2的边长。

如果 a、b 和 c 是周长为 2 的三角形的一条边的长度，则 a<1、b<1、c<1（否则三角形的一条边将大于其他两条边的总和）。因此(1-a)(1-b)(1-c)>0。展开括号并变换左边部分，我们得到

$$1 - (a+b+c) + ab+bc+ac - abc = -1 + \frac{a^2+b^2+c^2}{2} + ab+bc+ac - \frac{a^2+b^2+c^2}{2} - abc = -1 + \frac{(a+b+c)^2}{2} - \frac{a^2+b^2+c^2}{2} - abc = 1 - \frac{a^2+b^2+c^2}{2} - abc > 0,$$

这意味着$a^2+b^2+c^2 < 2(1-abc)$。

A·叶戈罗夫

M728。设 A、B、C 为平行平面中与其顶点 P 相邻的顶点，设 Q 为与 P 相对的顶点。证明 a) 距离

⟦folio 41⟧

($a_{n+3} = a_{n+2} = a_{n+1} = a_n = a$)。由上可知，数字$a_n$依次贯穿自然级数的权重。

现在让我们推导 $a_n$ 的显式公式。在和 $a_n = (a_n - a_{n-1}) + (a_{n-1} - a_{n-2}) + \dots + (a_2 - a_1)$ 中，所有项都等于 0 或 1，并且与不超过 $n$ 的第一类数字的数量完全相同。因此，$a_n$等于不超过$n$的第一类数的个数。很容易证明

$$a_n = \left[ \frac{n}{2} \right] - \left[ \frac{n}{4} \right] + \left[ \frac{n}{8} \right] - \dots$$

(1)

（这里非零项的数量是有限的，或者 $n < 2^m$ 在某些 $m$）。为了证明式(1)，我们注意到 $\left[ \frac{n}{2} \right], \left[ \frac{n}{4} \right], \left[ \frac{n}{8} \right], \dots$ 是不超过的数字个数 $n$ 可以被 2, 4, 8, ... 整除，因此，差值 $\left[ \frac{n}{2} \right] - \left[ \frac{n}{4} \right]$ 等于从 1 到 的数字个数 $n$，可被 2 整除且不可被 4 整除， $\left[ \frac{n}{8} \right] - \left[ \frac{n}{16} \right]$ 是从 1 到 $n$，能被 8 整除但不能被 16 整除，等等。

让我们使用公式（1）计算 $n = 3 \cdot 2^k$ $a_n$。如果 $k$ 是奇数，则

$$a_{3 \cdot 2^k} = \frac{3 \cdot 2^k}{2} - \frac{3 \cdot 2^k}{4} + \dots + \frac{3 \cdot 2^k}{2^k} - \left[ \frac{3}{2} \right] =$$

$$= 3(2^{k-1} - 2^{k-2} + \dots + 1) - 1 = 3 \frac{2^k + 1}{3} - 1 = 2^k.$$

请注意，在这种情况下，$n$和$n+2 = 2(3 \cdot 2^{k-1} + 1)$是第一类数字。因此，如果 $k$ 是奇数，则数字 $2^k$ 在我们的序列中出现 2 次。令$k$为偶数。然后又

$$a_{3 \cdot 2^k} = \frac{3 \cdot 2^k}{2} - \frac{3 \cdot 2^k}{4} + \dots + \left[ \frac{3}{2} \right] = 3 \frac{2^k - 1}{3} + 1 = 2^k.$$

但现在$3 \cdot 2^k$是第二类数。因此，$k$为偶数的数字$2^k$在数字$a_n$中重复四次。一路上，我们证明了陈述（d），因为$a_n = n/3$对于所有$n = 3 \cdot 2^k$。

e) 答案：是的。假设$n$能被4整除，则根据公式（1）

$$a_n = \frac{n}{2} - \frac{n}{4} + \left[ \frac{n}{8} \right] - \left[ \frac{n}{16} \right] + \dots = \frac{n}{4} + a_{\frac{n}{4}}.$$

(2)

考虑序列 $a_{n_m}$，其中 $n_m = \frac{4^m - 1}{3}$ 代表 $m = 1, 2, \dots$（$n_m$ 是任何 $m$ 的奇数整数）。请注意$\frac{n_m - 1}{4} = \frac{4^m - 4}{3 \cdot 4} = \frac{4^{m-1} - 1}{3} = n_{m-1}$。因此，根据式（2）对于$n = n_m - 1$

$$a_{n_m} = a_{n_m-1} = n_{m-1} + a_{n_{m-1}}.$$

因此，

$$a_{n_m} = n_{m-1} + n_{m-2} + \dots + n_1 + a_1 = \frac{n_m}{3} - \frac{m}{3}.$$

对于$m = 6000$，我们得到$\left| a_{n_m} - \frac{n_m}{3} \right| = 2000 > 1982$。

e) 请注意，在公式（1）中，不为零的项数等于$v = [\log_2 n]$。这就是为什么

$$\left| a_n - \left( \frac{n}{2} - \frac{n}{4} + \frac{n}{8} \right) \right| \leq v,$$

因为，通过删除整个部分的符号，我们在每一项中都会犯一个小于 1 的错误。几何级数的总和在括号中。计算一下，我们得到

⟦folio 42⟧

$$\left| a_n - \frac{n \left( 1 - \left( -\frac{1}{2} \right)^v \right)}{3} \right| \leq \log_2 n$$

或者
$$\left| \frac{a_n}{n} - \frac{1}{3} + \frac{(-1)^v}{3 \cdot 2^v} \right| \leq \frac{\log_2 n}{n}.$$
并且从 $\frac{(-1)^v}{3 \cdot 2^v} \to 0$ 和 $\frac{\log_2 n}{n} \to 0$ 到 $n \to \infty$ 开始，
$$\lim_{n \to \infty} \frac{a_n}{n} = \frac{1}{3}.$$

V·谢维列夫

F733。长度为 $l$ (图 1) 的哑铃放置在底半径为 $R$ 的“半框架”上。求哑铃小幅振动的周期。

图 1.

图 2.

让哑铃相对平衡位置（图2）旋转一个小角度$\alpha$；点$B$是杆与接收芯的接触点； $A\hat{O}B = \alpha$（表面粗糙，哑铃不打滑）。产生的力矩往往会使哑铃返回到平衡位置。由于角度$\alpha$很小，我们可以假设哑铃球将沿着半径为圆的弧线运动
$$r_1 \approx \frac{l}{2} - |AB| = \frac{l}{2} - R\alpha, \quad r_2 = \frac{l}{2} + R\alpha.$$
球的速度将分别相等。
$$v_1 = x_1' = (r_1\alpha)' = \alpha' \left( \frac{l}{2} - 2R\alpha \right), \quad v_2 = x_2' = (r_2\alpha)' = \alpha' \left( \frac{l}{2} + 2R\alpha \right).$$
哑铃的总能量保持恒定，等于其偏离平衡位置最大时刻的势能$\Pi_0$。当哑铃从平衡位置倾斜$\alpha$角度时，其能量等于
$$\Pi_1 + K = mg(R + x_2) + mg(R - x_1) + \frac{mv_1^2}{2} + \frac{mv_2^2}{2} = m \frac{l^2(\alpha')^2}{4} + 2mgR \left( 1 + \frac{\alpha^2}{2} \right) = \Pi_0$$
（m是每个球的质量；我们认为杆是未知的；在计算$v_1^2$和$v_2^2$时我们忽略了$\alpha^2(\alpha')^2$阶项）。让我们区分一下我们得到的结果：
$$\frac{ml^2\alpha' \alpha''}{2} + 2mgR\alpha' = 0,$$
在哪里
$$\alpha'' = - \frac{4gR}{l^2} \alpha.$$
由此产生的方程是频率为 $\omega = \sqrt{4gR/l^2}$ 的谐振方程。因此，哑铃小幅振荡的周期等于
$$T = \frac{2\pi}{\omega} = \pi l \sqrt{\frac{1}{gR}}.$$
A·弗罗洛夫

F734。一根绳子，一端固定在圆柱体侧面，半径为$r$，在圆柱体上缠绕$k$次

作用在负载上的绳索的张力垂直于负载的速度。因此，负载速度的绝对值保持恒定且等于$v$。
考虑绳索被拉动时的运动

⟦folio 43⟧

(k是整数)。 zruz 连接到 vervika 的自由端。负载的速度 v 沿圆柱体半径方向 (图 1)。需要多长时间所有绳子才能再次缠绕在圆筒上？气缸固定在主表面上。

图 1.

完全从气缸上松开，负载位于 C 点 (图 2)。在很短的时间Δt内，负载将移动到C'点。由于Δt很小，所以整根绳子旋转的角度α也很小，

$$\alpha = \frac{v \cdot \Delta t}{l} = \frac{\Delta l}{r} \Rightarrow rv \cdot \Delta t = l \cdot \Delta l = \Delta \left( \frac{l^2}{2} \right).$$

从最后一个等式我们可以找到长度为 l 的整根绳子缠绕在圆柱体上的时间：

图 2.

$$t = \frac{l^2}{2rv}.$$ 在相同的时间内，绳索从气缸中松开，负载最终到达 B 点（参见图 2）。负载从 B 点移动到 C 点所需的时间等于 τ = πl/v。

因此，将长度为 l = 2πrk 的绳索从圆筒上解开并再次缠绕在其上后，完整的绳索等于

$$T = 2t + \tau = \frac{4\pi^2k^2r}{v} + \frac{2\pi^2rk}{v} = \frac{2\pi^2kr}{v} (2k + 1).$$

B·穆库舍夫

F735。两个相同的电感器通过开关 K1 和 K2 连接到具有恒定 EMF 和内阻 r 的源（参见 图ok）。在激活的初始时刻，两个键都是打开​​的。然后先关闭键 K1，然后关闭键 K2。确定开关K2闭合瞬间流经开关K1的电流大小，若已知开关K2闭合后，流经开关K1的稳态电流为流经开关K2的稳态电流的两倍。忽略线圈的有源电阻。

◆

关闭钥匙 K1 后，通过线圈 1 的电流（参见图nok）将增加。令在开关K2闭合的瞬间，该电流的大小等于I0。关闭K2键后，线圈两端的方向将相等。忽略线圈的有功电阻，我们可以将该条件写成以下形式

$$L \frac{dI_1}{dt} = L \frac{dI_2}{dt},$$

其中L是线圈的电感，I1和I2分别是开关K2闭合后匝中任意时刻的线圈1和2中的点。相同的条件可以写成另一种形式：

$$\frac{d(I_1 - I_2)}{dt} = 0,$$ 或 I1 - I2 = 常数，

也就是说，在运行期间（两个开关均闭合）任何时刻线圈中电流的绝对值之差保持恒定。我们根据初始条件，即连接钥匙 K2 的时刻，求出 I1 - I2 的差值。此时I1=I0，I2=0；因此，I1 - I2 = I0。

在稳定状态下，线圈将是准确的；让我们将它们表示为 I_{yct.1} 和 I_{yct.2}。线圈两端以及电池两端的电位差将为零。若此时电池流过电流I6，则

$$\varepsilon - I_6 r = 0.$$

因此，在稳定状态下，通过电池的流量将等于 I6 = ε/r。根据电荷守恒条件我们可以写出

$$I_{yct.1} + I_{yct.2} = I_6 = \varepsilon/r.$$

(1)

维持绝对电流值充电的条件

⟦folio 44⟧

通过线圈还​​可以设置其电流；这就是为什么

$$I_{\text{уст. 1}} - I_{\text{уст. 2}} = I_0.$$

(2)

联立方程(1)和(2)可得

$$I_{\text{уст. 1}} = \frac{I_0 + \mathcal{E}}{r}, \quad I_{\text{уст. 2}} = \frac{\mathcal{E}}{r - I_0}.$$

使用给定的对应关系设置它们的电流 - $I_{\text{уст. 1}} / I_{\text{уст. 2}} = 2$ - 我们找到 $I_0$：

$$I_0 = \mathcal{E} / 3r.$$

V·莫扎耶夫

F736。一束电子落在一根均匀的棒上，棒的两端都接地，每秒有相同数量的电子击中棒的每厘米长度。棒的电阻为R。接地段的电流等于I。求棒A中部与其末端B之间的电位差（见图1）。

F737。平行光束通过板 P 时发生散射。对于任何穿过板的光线，偏离原始方向的最大角度为 α。在板后放置一个焦距为F（图1）的聚光镜L，可获得的最小亮点半径是多少？

由于棒是均匀的，流过它的电流相对于 A 点对称。因此，在 A 点电流为零，即 $I_A = 0$。

让我们在心里将杆的AB 部分分成N 个相同的部分。令第一个（从 A 点开始）部分结束时电流等于 $I_1$。那么在第 k 段结束时，电流为 $I_k = kI_1$；第N段结束时，即B点，电流为$I_N = NI_1$。同时，电流$I_N$等于接地段电流I的一半，即$NI_1 = I/2$。因此$I_1 = I/2N$。

每段电阻为$R/2N$，第k段电压降为

$$U_k = I_kR/2N = kI_1R/2N = kIR/4N^2.$$

A 点和 B 点之间的电位差等于所有 N 个部分上的电压降之和。因此，

$$U_{AB} = \sum_{k=1}^{N} U_k = \frac{IR}{4N^2} \sum_{k=1}^{N} k = \frac{IR}{8} \frac{N+1}{N} \xrightarrow{N \to \infty} \frac{IR}{8}.$$

N·迪坎斯基

让我们找到镜头后面的照明区域的边界。其特性取决于透镜的尺寸（孔径半径）、光束的半径以及板与透镜之间的距离。令这些参数等于r、R和s的对应关系。

在 $r > R + stg\alpha$ 处，所有被板散射的光线都落在透镜上 (图 2)。在透镜后面，照明区域的边界由光线 $I'$ 和 $4'$ 形成（光线 1 和 4 的折射结果，由入射到透镜上的散射光束的边界确定）。边界的断点位于 A、B、C 意识下方。A 点位于透镜平面内，距轴 $R + stg\alpha$ 处。点 B，即光线 $I'$ 和 $3'$ 的交点，位于焦平面内，因为入射到透镜上的光线 1 和 3 是平行的。 B点到轴线的距离为$Ftg\alpha$。点 C — 光线$3'$ 和 $4'$ 的交点 — 位于散射板清晰图像的平面内，因为从板的一个点发出的光线都聚集在这里。因此，C点是位于

⟦folio 45⟧

距轴的距离为 $R$，距透镜平面的距离为 $s$。因此，$C$到轴的距离是$RF/(s-F)$（自己计算）。

点名称位于最接近断裂轴的平面上；因此它的半径等于距离 $R+s tg \alpha$、$F tg \alpha$ 和 $RF/(s-F)$ 中的最小值。因此，屏幕必须位于靠近镜头的位置，或者位于焦平面中，或者位于板的清晰图像的平面中。请注意，在 $s<F$ 处，镜头后面的光线 $3'$ 和 $4'$ 不相交（板图像最小），仅保留扭结 $A$ 和 $B$。

在 $r<R-s tg \alpha$ 处，透镜后面的照明区域的边界由“限制”穿过透镜边缘的光线 (图 3) 形成。边界断裂位于透镜平面中距轴 $r$ 的距离（点 $A_1$）处，以及焦平面中距轴 $F tg \alpha$ 的距离（点 $B_1$）处，如前所述。没有大的突破。值$r$和$F tg \alpha$中的最小值给出了最小点的半径。

最后，在中间情况 $R+s tg \alpha>r>R-s tg \alpha$ (图 4) 中，边界断裂位于镜头平面、焦平面和板的清晰图像平面中，距离分别为 $r$、$F tg \alpha$ 和 $RF/(s-F)$。

对于足够小的$\alpha$，在所有这些情况下，最小的光斑将位于焦平面中，并且该光斑的半径$F tg \alpha$既不取决于第一束的半径，也不取决于透镜的直径。有趣的是，这种在焦平面附近的电子束压缩（称为交叉）被用在电子示波器中，以形成狭窄、集中的电子束。

沃罗比耶夫

F738。粒子以恒定的速度沿一个方向移动。粒子速度从柱冷端的值 $v_1$ 均匀增加到柱尾的值 $v_2$。在某个时刻，粒子占据一段长度为 $l_0$ 的线段，同时每单位长度有 $n_0$ 个粒子。时间 $t$ 后，柱尾每单位长度有多少个粒子？

让粒子在时间 0 占据一段长度为 $l_0$ 的线段。在时间 $t$ 内，柱头的粒子将移动 $v_1 t$，柱尾的粒子将移动 $v_2 t$（图 1）。后面的粒子快速移动，并将列开头的粒子向上推。第一部分和最后一部分之间的对价将在时间$t$减少$(v_2-v_1) t$并且变得相等

$$l = l_0 - (v_2 - v_1) t.$$

所有粒子占据的线段长度的减少由线段末端和开头的粒子速度差决定。对于柱中任意两个颗粒之间的间隙也是如此。

假设在初始时刻，有两个粒子距离$\Delta x_0$。那么他们的速度差就是

$$\Delta v = \frac{(v_2 - v_1)}{l_0} \Delta x_0$$

（因为粒子速度朝着柱尾均匀增加）。时间$t$的粒子之间的考虑将减少$\Delta v t$并且变得相等

⟦folio 46⟧

$$\Delta x = \Delta x_0 - \Delta v \cdot t = \left( 1 - \frac{(v_2 - v_1) t}{l_0} \right) \Delta x_0.$$

正如我们所看到的，任何两个粒子之间的距离随着时间的推移而减小相同的倍数；因此，颗粒沿柱保持均匀分布。换句话说，到达每单位长度柱子的粒子数$n$在任何位置都是相同的，就像在初始时刻一样。

要找到 $n$，请将部分 $n_0 l_0$ 的总数除以时间 $t$ 时的列长度：

$$n = \frac{n_0 l_0}{l_0 - (v_2 - v_1) t} = \frac{n_0}{1 - \frac{(v_2 - v_1) t}{l_0}}.$$

在 图 2 处，显示了$n(t)$ 的依赖性。随着时间$k$接近时刻$t_0 = l_0/(v_2 - v_1)$，粒子浓度$n$无限增加，并在$t > t_0$改变符号，绝对值进一步减小。这种行为$n(t)$并不难理解：到$t_0$时刻，所有粒子都会聚集在一个点上——这对应于无限集中；此后，当后面的粒子超过前面的粒子时，粒子的顺序将发生变化 - 这通过 $n$ 符号的变化来表示。

沃罗比耶夫

F739。在高度为$H$、底面积为$S$的圆柱形连接中，每秒有大量水$M$从水平管道流入。底部有一个小孔。容器中的水面上躺着一朵薄薄的莱卡丁香。从某一时刻开始，容器中的水位高度变得恒定并且等于$h_0$。确定水从孔中流出的速度。

在稳定状态下，作用在海绵上的梦是平衡的。落下的水对海绵施加力

$$F = \frac{M \cdot \Delta t \cdot \sqrt{2g(H - h_0)}}{\Delta t} = M \sqrt{2g(H - h_0)}.$$

这个力确实及时起作用$\Delta t$

$$\Delta A = F \cdot \Delta x = F \frac{\Delta V}{S} = F \frac{M \cdot \Delta t}{\rho S}.$$

根据能量守恒定律

$$\Delta A + \Delta \Pi = \Delta K,$$

或者

$$\Delta A + M \cdot \Delta t \cdot g \cdot h_0 = M \cdot \Delta t \cdot \frac{v_1^2 - v_2^2}{2},$$

其中$v$是水落在海绵上的速度，$v_1$是水从孔中流出的速度。由于孔很小，$v^2 \ll v_1^2$。最后我们得到

$$\frac{F}{\rho S} + g h_0 = \frac{1}{2} v_1^2,$$

在哪里

$$v_1 = \sqrt{2 g h_0 + \frac{2 M}{\rho S} \sqrt{2 g(H - h_0)}}.$$

I·奥梅尔扬

F740。该容器含有氦气和氧气的混合物。在温度$t = -2^\circ C$和压力$p = 0,9$大气压下，该混合物的密度为$Q = 0,44 \text{ кel/м}^3$。如果容器中的一半氧分子被除去，它会是什么样子？

令$1 \text{ m}^3$混合物含有$v_1$摩尔氦气和$v_2$摩尔氧气。那么体积$V = 1 \text{ m}^3$中的总摩尔数等于

$$v = v_1 + v_2 = \frac{p V}{RT} = \frac{0,9 \cdot 10^5 \cdot 1}{8,3 \cdot 271} \approx 40 \text{ mol}.$$

该体积中混合物的质量等于

$$m = m_1 + m_2 = \mu_1 v_1 + \mu_2 v_2 = \rho V = 0,44 \text{ кг}.$$

求解方程组

⟦folio 47⟧

$$\begin{align*}
v_1 + v_2 &= 40, \\
4 \cdot 10^{-3} v_1 + 32 \cdot 10^{-3} v_2 &= 0,44,
\end{align*}$$

我们找到$v_1$和$v_2$：

$$v_1 = 30 \text{ моль}, \quad v_2 = 10 \text{ моль}.$$

如果从容器中除去一半的氧分子，则总摩尔数变为$v' = 35 \text{ моль}$。这种情况下容器内的压力$p'$可从对应关系$p/p' = v/v'$中找到：

$$p' = p \frac{v'}{v} = 0,9 \cdot 10^5 \cdot \frac{35}{40} \approx 0,79 \cdot 10^5 \text{ Па.}$$

A·齐伯曼

F741。我们将两个容量为 1 μF 的电容器串联连接至方向为 220 V、频率为 50 Hz 的交流电。电阻值为$R = 100 \text{ кОм}$的电阻器与其中一个电容器并联（参见图ok）。求热功率。

◆ 给定频率$f = 50$ Hz 下的电容电阻等于

$$Z_C = \frac{1}{2\pi f C} \approx 3 \cdot 10^3 \text{ Ом}.$$

由于电阻的阻值为$R = 10^6 \text{ Ом}$，即

$$R \gg Z_C, \text{ можно считать, что } U_R \approx U/2 = 110 \text{ В (U — напряжение сети)}. \text{Takим образом, тепловая мощность равна}$$
$$P = U_R^2/R \approx 0,12 \text{ Вт.}$$

A·齐伯曼

F742。具有原始横截面的玻璃容器安装在两个焦距 $F$ 垂直于透镜光轴 (图 1) 的聚光透镜之间。精密光源$S$位于透镜$J_1$的焦平面上。当容器为空时，在位于透镜$J_2$焦平面的屏幕E上观察源图像。容器中充满透明液体，如图所示

球面波从精确的光源$S$传播，即波前（恒相位面）具有以点$S$为中心的球体形状。通过透镜$J_1$后，正面变得平坦（因为点$S$位于透镜$J_1$的焦点）。因为前部平行于透镜所在的平面以及容器的侧壁。如果容器是空的，那么在穿过容器之后，波前仍将平行于容器壁。平行于透镜主轴的光束将施加到透镜$J_2$，并且光源$S$的图像将位于透镜的右焦点处。

当容器充满变化的（高度）折射率时，穿过容器后空间中波前的方向会发生变化。为了在这种情况下找到前面，我们使用

图 1.

图 2.

⟦folio 48⟧

折射率随高度变化，遵循$n(y) = n_0 + \alpha y$定律。液层厚度为$L$。屏幕上的源图像将垂直移动多少？在光束直径范围内，折射率随酱汁深度的变化被认为很小。

休更斯-菲涅尔原理。根据这一原理，光线穿过酱体后的正面将是一个二次波的包络线，其来源位于酱体的左侧壁上。

让我们找到当来自酱体左壁上距其底部 (图 2) 高度 $h$ 的源的次级波到达酱体右壁时前沿的位置。这些波传播距离 $L$ 的时间 $t$ 等于

$$t = \frac{L}{c/n(h)} = L \frac{n_0 + \alpha h}{c},$$

其中$c$是真空中的光速，$n(h) = n_0 + \alpha h$是$y = h$高度处液体的折射率。从酱汁左壁上高度为 $y < h$ 的源传播相同距离的 $L$ 波将及时传播

$$t_1 = L \frac{n_0 + \alpha y}{c} < t$$

（我们假设$\alpha > 0$）。因此，在时间$t$这些波将传播到酱汁的右侧一段距离

$$l(y) = (t - t_1)c = L\alpha(h - y).$$

数量 $l(y)$ 是 $y$ 的线性函数。因此，光穿过酱汁后，二次波的包络线，即波前，将是一个以一定角度倾斜于酱汁侧壁的平面，使得（参见图2）

$$tg\varphi = l(y)/(h - y) = L\alpha.$$

因此，与透镜光轴成角度$\varphi$倾斜的平行光线光束将落在透镜$\varPi_2$上。光源$S$的图像将在远处的镜头$\varPi_2$的焦平面上获得

$$\delta = F \cdot tg\varphi = FL\alpha$$

从镜头的轴线。使用 $\alpha < 0$ 图像将沿轴移动相同的量。

V·莫扎耶夫

Matematika
魔方

（关于开头，请参见第 22 页）

12. “重新绘制的立方体” 基本操作是相同的，但是 1）在每个中心立方体上绘制一个箭头，记录其转动； 2）将立方体涂成三种颜色，使得零状态下相对面的颜色相同。

13. “魔法平行六面体$n \times m \times k$”。从标题中应该可以明显看出这款游戏的描述。当然，并不是每个脸都只能旋转$180^\circ$，而且不仅是脸，还可以表达内部的大象。与$n, m, k \leq 3$对应的另外9个选项绝不是微不足道的。变奏$3 \times 3 \times 2$在匈牙利以“多米诺”的名义进行。最近，$4 \times 4 \times 4$魔方开始在匈牙利生产，并被冠以“Rubik’s Places”的美妙名字！

14. “魔方$3 \times 3 \times 3$”。 （对于那些稍微熟悉四维几何的人。）

15. “神奇的多面体”。不同颜色的球位于任意多面体的顶点和边的中间（颜色的数量等于多面体的顶点和边的总数）。只需一步，您就可以循环地重新排列一侧的所有球。这里的状态完全由排列$s$和$t$描述。

16. 《魔法地球体》零态是一个规则的地球面体，每个面都涂有四种颜色中的一种。当“旋转面”时，4个角和6个边“元素”会移动，其形状将不被指定。重要的是，除了排列之外，还必须考虑它们的方向。使用八面体、十二面体和二十面体获得的其他选项。
