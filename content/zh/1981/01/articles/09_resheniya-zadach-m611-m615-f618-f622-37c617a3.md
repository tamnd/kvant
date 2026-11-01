---
id: 1981-1-resheniya-zadach-m611-m615-f618-f622-37c617a3
issue: kvant_1981_1
year: 1981
number: "1"
title: 问题解决方案M611—M615； F618—F622
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 34
page_labels: 28, 29, 31, 32
tag: JXXY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5862633e43e99043d423dafa87a84866eaaa8fbdbe0f36b172482b427663a260
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/09_resheniya-zadach-m611-m615-f618-f622-37c617a3.md
source_content_sha256: f3ec660cbfca09844f8de1c10b534533b46637f60ba477db7888118c5b1c4423
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

问题解决方案
M611—M615; F618—F622

M611。 On the chord AB of a circle with center O, take an arbitrary point M. Through points A, M and O, draw a circle intersecting the first circle at points A and C. Prove that $|MB| = |MC|$.

让$\widehat{ABC} = \beta$。 Then $\widehat{AOC} = 2\beta$, since $\widehat{ABC}$ and $\widehat{AOC}$ are inscribed and, respectively, central angles based on the same arc AC of the given (black - see 图) circle.

On the other hand, $\widehat{AMC}$ and $\widehat{AOC}$ are inscribed angles subtended by the same arc AC of the constructed (blue) circle (located in the non-black circle).因此$\widehat{AMC} = 2\beta$。

$AMC$是三角形MBC的外角。所以，$\widehat{MCB} = \widehat{AMC} - \widehat{MBC} = \beta$。从 $\widehat{MCB} = \widehat{AMC}$ 开始，接着$|MB| = |MC|$。

This solution is suitable (unlike some solutions sent by readers) for any location of the point M on [AB], except for the case when M coincides with the midpoint of the chord AB.在最后一种情况下，蓝色圆圈接触黑色圆圈，点 A 和 C 合并，等式 $|MB| = |MC|$ 变为等式 $|MB| = |MA|$。

考虑一下，如果 M 取于线段 AB 的延续，那么已证明的命题是否仍为真。

N·瓦西里耶夫

M612。自然数的递增序列 ($a_n$) 使得$a_{n+1} \leq 10a_n$。 Prove that if all the numbers $a_n$ are written side by side (without spaces or commas), then the resulting sequence of numbers will not be periodic.

Let us assume that we have a periodic sequence of digits and that the length of the period (the number of digits in it) is equal to T. It is easy to see that the number $a_{n+1}$ can be “longer” than the number $a_n$ by no more than one digit (and, of course, not shorter).由于序列 ($a_n$) 返回，因此它包含大于 $a_1$ 长度的任意长度的数字。因此，其中有一个错误的数字$a_m$，其长度$kT$是周期的倍数（参见图）。 The first $kT$ digits of $a_{m+1}$ must match the digits of $a_m$, so $a_{m+1}$ has one more digit ($a_{m+1} > a_m$), and it must have a zero ($10a_m \geq a_{m+1}$).但是条目 $a_m$ 中的第一个数字为零，这当然是不可能的。

请注意，如果条件 $a_{n+1} \leq 10a_n$ 替换为稍微弱一点的： $a_{n+1} \leq 10a_n + 1$ 或者 $a_{n+1} \leq (10 + \varepsilon)a_n$， 在哪里 $\varepsilon$ 是任意正数，那么所得的数字序列可能是周期性的。

I·克鲁莫娃

M613。在三角形ABC的边上，向外侧构造相似的三角形ADB、BEC和CFA($|AD|/|DB| = = |BE|/|EC| = = |CF|/|FA| = k$，$ADB = BEC = CFA = \alpha$)。证明a）线段AC、DC、BC、EF的中点是平行四边形的顶点； b) 这个平行四边形有两个整数a，边长比等于k。

让我们用$\vec{a}'$表示从向量$\vec{a}$逆时针旋转角度a获得的向量。 (It is known that $(k\vec{a})' = k\vec{a}'$ for any number $k$, $(\vec{a} + \vec{b})' = \vec{a}' + \vec{b}'$, and in general, for any number of terms, $(\vec{a} + \vec{b} + \dots + \vec{c})' = \vec{a}' + \vec{b}' + \dots + \vec{c}'$.) Let us introduce the vectors $\vec{DA} = \vec{a}$, $\vec{EB} = \vec{b}$, $\vec{FC} = \vec{c}$ (see 图).

根据条件$\vec{DB} = \frac{1}{k}\vec{a}'$、$\vec{EC} = \frac{1}{k}\vec{b}'$、$\vec{FA} = \frac{1}{k}\vec{c}'$。

从$\vec{AD} + \vec{DB} + \vec{BE} + \vec{EC} + \vec{FC} + \vec{FA} = 0$开始，$\vec{a} + \frac{1}{k}\vec{a}' - \vec{b} + \frac{1}{k}\vec{b}' - \vec{c} + \frac{1}{k}\vec{c}' = 0$，即$\vec{a} + \vec{b} + \vec{c} = \frac{\vec{a}' + \vec{b}' + \vec{c}'}{k} = \frac{1}{k} (\vec{a} + \vec{b} + \vec{c})'$。

用$\vec{u}$表示$\vec{a} + \vec{b} + \vec{c}$，我们得到$\vec{u} - \frac{1}{k}\vec{u}' = 0$。 (*)

由于向量 $\vec{u}$ 和 $\vec{u}'$ 不共线（$\alpha \neq 0$ 和 $\alpha \neq 2\pi$），因此当 $\vec{u} = \vec{0}$ 时，相等 (*) 是可能的。因此$\vec{a} + \vec{b} + \vec{c} = \vec{0}$。

⟦folio 29⟧

此外，由于$Q$是$[DC]$的中间，$P$是$[AC]$的中间（参见图），$\overrightarrow{QP} = \frac{1}{2} \vec{a}$。与$\overrightarrow{QR} = \frac{1}{2} \overrightarrow{DB}$相同。从 $(PQ) \parallel (AD)$ 和 $(QR) \parallel (BD)$ 开始，它紧接着 $PQR = \alpha$。

最后，

$$\overrightarrow{RS} = \overrightarrow{RC} + \overrightarrow{CF} + \overrightarrow{FS} = \frac{1}{2} \overrightarrow{BC} - \vec{c} + \frac{1}{2} \overrightarrow{FE} =$$

$$= \frac{1}{2} \left( -\vec{b} + \frac{1}{k} \vec{b}' \right) - \vec{c} + \frac{1}{2} \left( \vec{c} - \frac{1}{k} \vec{b}' \right) = -\frac{\vec{b} + \vec{c}}{2} = \frac{\vec{a}}{2} = \overrightarrow{QP}$$

因此，四边形$PQRS$是角$PQR$等于$\alpha$且边长比$|PQ|/|RQ| = |AD|/|DB| = k$的平行四边形。

L·库普佐夫

**M614。对于每个自然数$n$，令$S(n)$表示从1到$n$的所有自然数的数字之和（以十进制表示）：

$S(1) = 1, S(2) = 3, S(3) = 6, \dots, S(9) = 45, S(10) = 46, S(11) = 48, S(12) = 51, \dots$

a) 找到$S(100)$。

b) 证明$S(10^k - 1) = 45k \cdot 10^{k-1}(*)$对于所有$k = 1, 2, \dots$

c) 证明对于两个自然数$\overrightarrow{ab}$

$$S(\overrightarrow{ab}) = 5a^2 + ab + 41a + b(b+1)/2.$$

f) 找到一个类似的三位数公式。

e) 计算总和$S(1980)$。

让我们推导出$S(\overrightarrow{a_k a_{k-1} \dots a_1})$的一般公式。 Let's represent this sum in the form of $a_k + 1$ terms, separately calculating it for numbers with the $k$th digit 0, 1, ..., $a_k - 1$ and $a_k$, respectively.

前 $a_k$ 项是明确的：其中，对小于 $k$ 的数字没有任何限制。 If the $k$th digit is equal to $b$ (and $0 \leq b \leq a_k - 1$), then the sum of the digits of all such numbers is equal to $10^{k-1} \cdot b + S(10^{k-1} - 1)$ (the contribution from the $k$th digit and from the remaining digits, respectively). The $(a_k + 1)$th term (when the $k$th digit contains the digit $a_k$) looks like this: $a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1})$ (again the contribution from the $k$th digit and the remaining digits, respectively).

好的，最终对于 $S(\overrightarrow{a_k \dots a_1})$ 我们得到

$$S(\overrightarrow{a_k \dots a_1}) = a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1}) +$$

$$+ 10^{k-1}(0 + 1 + \dots + (a_k - 1)) + a_k \cdot S(10^{k-1} - 1) =$$

$$= a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1}) + 5 \cdot 10^{k-2}a_k(a_k - 1) +$$

$$+ a_k \cdot S(10^{k-1} - 1).$$

剩下的就是计算$S(10^{k-1} - 1)$。如果我们使用已经导出的公式，我们得到

$$S(10^{k-1} - 1) = 9 \cdot 10^{k-2} + S(10^{k-2} - 1) + 5 \cdot 10^{k-3} \cdot 9 \cdot 8 +$$

$$+ 9 \cdot S(10^{k-2} - 1) = 10 \cdot S(10^{k-2} - 1) + 45 \cdot 10^{k-2}.$$

如果我们认为已经证明了

$$S(10^{k-2} - 1) = 45(k - 2) \cdot 10^{k-3},$$

我们得到公式

$$S(10^{k-1} - 1) = 45(k - 1) \cdot 10^{k-2},$$

证明(*)（见第6项）$k = 1$的条件就足够了。

我们有 $S(10 - 1) = 45 \cdot 1 \cdot 10^\circ = 45$ - 公式 (*) 是正确的。所以，$S(10^k - 1) = 45k \cdot 10^{k-1}$ - 我们已经证明了问题的陈述 6)。

对于两个值，这给出

$$S(\overrightarrow{a_2 a_1}) = a_2(a_1 + 1) + S(a_1) + 5a_2(a_2 - 1) +$$

$$+ 45a_2 = a_2(5a_2 + a_1 + 41) + \frac{a_1(a_1 + 1)}{2} -$$

- 请参阅任务中的段落。

对于三位数

$$S(\overrightarrow{a_3 a_2 a_1}) = a_3((\overrightarrow{a_2 a_1} + 1) + 900 + 50(a_3 - 1)) + S(\overrightarrow{a_2 a_1}) =$$

$$= a_3(50a_3 + \overrightarrow{a_2 a_1} + 851) + a_2(5a_2 + a_1 + 41) + \frac{a_1(a_1 + 1)}{2}.$$

（特别是$S(100) = 901$）。

最后，

$$S(1980) = 980 + 1 + 45 \cdot 3 \cdot 10^2 + S(980) =$$

$$= 13500 + 981 + 9(450 + 80 + 851) + 8(40 + 41) = 27558.$$

I·克鲁莫娃

⟦folio 31⟧

我们说$F = 10$厘米。该点在垂直于主光轴的平面内以$h = 5$cm的距离混合。镜头应该移动多少以及移动到哪里才能使所选的发光点返回到原来的位置？

沿与点移动方向相反的方向移动。

当将点$A$移动到点$A'$时，镜头的光学中心必须从点$O$移动到点$O'$，使得点$A', B, O'$位于同一条直线上。在镜头的新位置，其光轴$N'N'$应与直线$NN$平行。

由图可知，透镜光心必须混合的距离$x$满足条件

$$\frac{x}{h} = \frac{f}{d-f} \Rightarrow x = \frac{hf}{d-f}.$$

我们使用发散透镜公式找到未加权值$f$：

$$\frac{1}{d} - \frac{1}{f} = -\frac{1}{F} \Rightarrow f = \frac{dF}{d+F}.$$

因此，

$$x = \frac{hF}{d} = 1,25 \text{ см.}$$

A. 伊泽列宁、S. 马尼达、V. 索利特

F620。如果将质量大于$m$的物体放在方桌中央，桌腿就会断裂。在桌子上找到一组点，您可以在其中放置质量为 $m/2$ 的物体，而不必担心打破桌子。

为防止桌腿折断，每条腿所受的力不应大于 $m/4$ （这是根据问题的条件得出的）。看看实力如何 $f_1$ 作用于腿部 $I$ (图 1)、当工作台上有质量负载时 $m/2$ 在有坐标的点 $x, y$ （该点作为起点 $I$).

令 $f_2, f_3, f_4$ 分别为作用在腿 $II, III, IV$ 上的力。显然，力 $f_1$ 和 $f_2$ 的作用相当于力 $f_{1-2} = f_1 + f_2$ 作用在坐标为 {0; 的点 $A$ 处； $y$}，力$f_3$和$f_4$的作用相当于力$f_{3-4} = f_3 + f_4$施加在点$B$坐标为{$l$; $y$}（桌子边长为$l$）。让我们写出该表的平衡条件：

$$f_{1-2} + f_{3-4} = \frac{mg}{2},$$

$$f_{1-2} x = f_{3-4} (l - x).$$

从这里

$$f_1 + f_2 = f_{1-2} = \frac{mg}{2} \frac{l-x}{l}.$$

另一方面，$f_1 y = f_2 (l - y)$，从哪里

$$f_1 = f_2 \frac{l-y}{y}.$$

由(1)和(2)我们发现

$$f_1 = \frac{mg}{2} \frac{(l-x)(l-y)}{l^2}.$$

为防止腿折断，必须满足以下条件：

$$f_1 = \frac{mg}{2} \frac{(l-x)(l-y)}{l^2} < \frac{mg}{4},$$

也就是说，质量载荷 $m/2$ 可以位于其坐标与关系式相关的点上

$$y > l \left(1 - \frac{l}{2(l-x)}\right).$$

仅显示函数$y(x) = l \left(1 - \frac{l}{2(l-x)}\right)$的图形

⟦folio 32⟧

F621。将缠绕在星形线轴上的线头扔到墙上（参见图）。线以恒定速度 v 被拉动。当线与垂直方向形成角度 a 时，卷轴中心移动的速度是多少？线圈的外半径为R，内半径为r。

如果线如图图所示被拉动，线轴将向右滚动，同时绕着运动和旋转运动的线速度顺时针旋转，线每个方向的角速度ω等于v：

$$v_0 \sin \alpha - \omega r = v$$

（v₀ 是所需速度的模数）。由于线圈没有沿水平面滑动，C 点相应速度的投影之和为零：

$$v_0 - \omega R = 0.$$

由此产生的方程给出

$$v_0 = v \frac{R}{R \sin \alpha - r}.$$

显然，当 R \sin \alpha = r 时（这对应于点 A、B、C 位于同一直线上的情况），v₀ 的表达式就失去了意义。另请注意，找到的表达式描述了线圈向右（当点 B 位于直线 AC 左侧且 R \sin \alpha > r 时）和向左（当点 B 位于直线 AC 右侧且 R \sin \alpha < r 时）的运动。

S·克罗托夫

F622。如果 t₁ = 0°C 时的饱和蒸汽压为 p₁ = 6·10²Pa，t2 = 35°C 时的饱和蒸汽压为 p2 = 5.5 ×，则在温度 t₁ = 0°C 且湿度为 95% 时，云中的绝对空气湿度（空气密度）或在 t2 = 35°C 且湿度为 40% 时，云中的绝对空气湿度（空气密度）大多少倍。 10帕？

相对湿度α下的水蒸气压等于

$$p = \alpha p_H,$$

其中 p_H 是给定温度下的饱和蒸气压。我们从气体状态方程中找到水蒸气的密度（绝对湿度）：

$$pV = \frac{m}{\mu} RT \Rightarrow \varrho = \frac{m}{V} = \frac{\mu p}{RT} = \frac{\mu a p_H}{RT}.$$

在指定条件下（α2 = 0.4，T2 = 308 K，p_H2 = p2 = 5.5 103Pa，α1 = 0.95，T1 = 273 K，p_H1 = p1 = 6 102Pa），零时和夜时的水蒸气密度比 q2/q1 等于

$$\frac{q_2}{q_1} = \frac{\alpha_2 p_2}{\alpha_1 p_1} \cdot \frac{T_1}{T_2} \approx 3,4.$$

因此，干燥的 nyubr（湿度 40%）中空气中的水蒸气含量是未加工的 nyubr（湿度 95%）中的 3.4 倍。

V·贝洛努金
