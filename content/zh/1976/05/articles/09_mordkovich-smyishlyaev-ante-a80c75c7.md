---
id: 1976-5-mordkovich-smyishlyaev-ante-a80c75c7
issue: kvant_1976_5
year: 1976
number: "5"
title: 安杰
authors:
  - Мордкович А. Г.
  - Смышляев В. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 45
page_last: 49
page_labels: 43, 44, 46, 47
tag: H4XM
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4cf13b10d4600b605d9691928d74435fc61e123553d10735138a3657dfb5affa
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/09_mordkovich-smyishlyaev-ante-a80c75c7.md
source_content_sha256: c98edfc659a69591a93b61a05ce7406ffc574a69c42c3ae09154164fe475eefe
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

1. 定义

在代数、数论、数学分析和概率论的许多问题中，都会出现不超过给定数字的整数（例如，记住十进制对数的特征的确定）。这样的整数有一个特殊的名称：“数字的整数部分”。

所以，系统的整数部分是最大整数$n$，不超过$x$；数字$x$的整数部分由符号$[x]$或（不太常见）$E(x)$（来自法语Entier（“anteche”）-“整个”）表示。例如，$[2,3]=2$、$[-2,3]=-3$。

如果$n \leqslant x < n+1$和$n$是整数，则$[x]=n$。从 $[x] \leqslant x < [x]+1$ 开始，我们就有了 $0 \leqslant x-[x] < 1$。数字$\alpha=x-[x]$称为数字$x$的小数部分，代表$\{x\}$。所以，$0 \leqslant \{x\} < 1$。显然$x=[x]+\{x\}$。

函数$y=[x]$的图形在图1上描绘，函数$y=\{x\}$在图2上描绘。

2. 一些属性

$1^\circ$。如果$p$是整数，则$[x+p]=[x]+p$。

$2^\circ$。对于任何实数$x$和$y$：$[x+y] \geqslant [x]+[y]$。

证明。我们有$x=[x]+\alpha, 0 \leqslant \alpha < 1; y=[y]+\beta, 0 \leqslant \beta < 1$。然后$x+y=[x]+\alpha+[y]+\beta=[x]+[y]+\gamma$，其中$\gamma=\alpha+\beta$。所以，$0 \leqslant \gamma < 2$。

如果$0 \leqslant \gamma < 1$，则$[x+y]=[x]+[y]$。

如果$1 \leqslant \gamma < 2$，即$\gamma=1+\gamma'$，其中$0 \leqslant \gamma' < 1$，则$x+y=[x]+[y]+1+\gamma'$和$[x+y]=[x]+[y]+1>[x]+[y]$。

扫地。属性$2^\circ$扩展到任意有限数量的项：$[x_1+x_2+\ldots+x_n] \geqslant [x_1]+[x_2]+\ldots+[x_n]$。

图 1. 图 2.

⟦folio 44⟧

3°。如果$[x] = [y]$，则$|x - y| < 1$。
4°。如果$n$是自然数，则$\left[\frac{x}{n}\right] = \left[\frac{x}{n}\right]$。

证明。让我们输入$\left[\frac{x}{n}\right] = a$。然后$a \leqslant \frac{[x]}{n} < a + 1$，或$a \leqslant [x] < n (a + 1)$。

由于数字$an$和$n (a + 1)$是整数，因此数字$x$也必须满足不等式$an \leqslant x < n (a + 1)$，因此$a \leqslant \frac{x}{n} < a + 1$，即$\left[\frac{x}{n}\right] = a$。

3. 方程中的反项
变量位于“整数部分”符号下的方程的解通常与不等式或不等式组的解一致。
让我们看几个例子。
问题 1. 解方程
$$\left[\frac{5 + 6x}{8}\right] = \frac{15x - 7}{5}.$$
解决方案。让我们输入$\frac{15x - 7}{5} = t$。那么$x = \frac{5t + 7}{15}$，方程就变成
$$\left[\frac{10t + 39}{40}\right] = t.$$
从整数部分的定义可以得出$0 \leqslant \frac{10t + 39}{40} - t < 1$。解决这些不等式，我们发现
$$-\frac{1}{30} < t \leqslant 1, 3.$$

图 3.
图 4.

⟦folio 46⟧

任务 5. 证明数字 $C_{1976}^{976}$ 能被$76^2$整除。

解决方案。由于$76 = 2^2 \times 19$，因此要被$76^2$整除，$C_{1976}^{976}$能被$2^4$和$19^2$整除是充分必要的。

我们有$C_{1976}^{976} = \frac{1976!}{976! \cdot 1000!}$。让我们找出指数 $\alpha_1, \alpha_2, \alpha_3$ 和 $\beta_1, \beta_2, \beta_3$ 等于什么，数字 2 和 19 出现在数字 1976!、976! 的素数分解中。和1000！我们有

$$\alpha_1 = \left[ \frac{1976}{2} \right] + \left[ \frac{1976}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{1976}{2^{10}} \right] = 1969,$$

$$\alpha_2 = \left[ \frac{976}{2} \right] + \left[ \frac{976}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{976}{2^{9}} \right] = 971,$$

$$\alpha_3 = \left[ \frac{1000}{2} \right] + \left[ \frac{1000}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{1000}{2^9} \right] = 994$$

$\alpha_1 - \alpha_2 - \alpha_3 = 4$，即$C_{1976}^{976}$能被$2^4$整除。

同样地

$$\beta_1 = \left[ \frac{1976}{19} \right] + \left[ \frac{1976}{19^2} \right] = 109,$$

$$\beta_2 = \left[ \frac{976}{19} \right] + \left[ \frac{976}{19^2} \right] = 53,$$

$$\beta_3 = \left[ \frac{1000}{19} \right] + \left[ \frac{1000}{19^2} \right] = 54$$

$\beta_1 - \beta_2 - \beta_3 = 2$，即$C_{1976}^{976}$能被$19^2$整除。

因此，$C_{1976}^{976}$可以被$76^2$整除。

5. 「目标点」

通过整数点，我们将理解具有整数坐标$x$和$y$的坐标平面上的点$(x, y)$。我们问如何计算给定平面图形内的整数点数？

任务 6. 直线 $y = \frac{2}{3} x - \frac{1}{2}$、$x = 10$ 和 x 轴 (图 5) 形成的三角形的边和内部有多少个完整的裂片？

解决方案。让我们找到函数$y = \frac{2}{3} x - \frac{1}{2}$对于整数$x = 1, 2, \dots, 10$的值（注意$y = 0$对于$x = \frac{3}{4}$）；我们得到坐标$\frac{1}{6}, \frac{5}{6}, \frac{3}{2}, \frac{13}{6}, \frac{17}{6}, \frac{7}{2}, \frac{25}{6}, \frac{29}{6}, \frac{11}{2}$和$\frac{37}{6}$。很容易说，位于给定三角形内（包括边界上）的整数点总数等于位于横坐标轴上的点平面的这些定标的整数部分之和：

$$\left[ \frac{1}{6} \right] + \left[ \frac{5}{6} \right] + \left[ \frac{3}{2} \right] + \left[ \frac{13}{6} \right] + \left[ \frac{17}{6} \right] + \left[ \frac{7}{2} \right] + \left[ \frac{25}{6} \right] + \left[ \frac{29}{6} \right] + \left[ \frac{11}{2} \right] + \left[ \frac{37}{6} \right] + 10 = 1 + 2 + 2 + 3 + 4 + 4 + 5 + 6 + 10 = 37.$$

答案：37分。

请注意，这个三角形内部只有 37-10-6=21 个整数点。

事实证明，整数点对于证明行动点很有用！

⟦folio 47⟧

任务7.证明可能性
质量

$$\left[ \frac{q}{p} \right] + \left[ \frac{2q}{p} \right] + \left[ \frac{3q}{p} \right] + \dots$$

$$\dots + \left[ \frac{(p-1)q}{p} \right] = \frac{(p-1)(q-1)}{2}$$

（p和q是互质自然数）。

解决方案。我们直接看
顶点为 $O = (0; 0)$、$A = (p; 0)$、$B = (p; q)$、$C = (0; q)$ (图 6) 的三角形。标记矩形内所有整数点$(x, y)$：$1 \leqslant x \leqslant p-1$、$1 \leqslant y \leqslant q-1$（图上的红点）。这些点的数量等于乘积 $(p-1)(q-1)$。

让我们画出矩形的对角线 $OB$；它的方程是$y = \frac{q}{p} x$。由于$p$和$q$是互质的，并且$x = 1$，...，$p-1$，那么$\frac{q}{p} x$形式的数字不是整数，即对角线$OB$上没有整数点，因此在对角线$OB$下的三角形中将有$\frac{(p-1)(q-1)}{2}$红色（整个）点。

另一方面，使用任务6中描述的方法，我们发现这些点的数量等于总和$$\left[ \frac{q \cdot 1}{p} \right] + \left[ \frac{q \cdot (p-1)}{p} \right],$$，因此必须证明身份。

图 6.

练习

1. 构造函数 $y = [-x]$、$y = [2x]$、$y = [\sin x]$ 的图形。
2. 证明行动要点：
a) $$\left[ \frac{n}{k} \right] + \left[ \frac{n+1}{k} \right] + \left[ \frac{n+2}{k} \right] + \dots$$
$$\dots + \left[ \frac{n+k-1}{k} \right] = n,$$
其中$n$和$k$是自然数。
b) $(n+1)(n+2)(n+3) \dots (2n-1)2n = 2^n \cdot (2n-1)!!$.
（$S!!$表示1到$S$的自然数与$S$具有相同奇偶性的乘积：例如$8!! = 2 \cdot 4 \cdot 6 \cdot 8; 9!! = 1 \cdot 3 \cdot 5 \cdot 7 \cdot 9$。）
3. 令$a, b, \dots, l$为自然数，$a+b+\dots+l=n$。证明分数$$\frac{n!}{a!b! \dots l!}$$是整数。
4. 证明如果$[nx] + [ny] = [n(x+y)]$对于所有自然$n$，则$x$或$y$是整数。
5. 素数$p$以什么指数进入数展开式
a) $(2n)!!;$ 6) $(2n+1)!!$.
6. 解方程组：
a) $$\left[ \frac{8x+19}{7} \right] = \frac{16(x+1)}{11};$$
b) $$\left[ \frac{x^2-2}{3} \right] = [x];$$
b) $x^4 - [x+1] = 2$.
7. 行人以5公里/小时的速度行走，每隔4公里停下来。除第四站外，每一站的持续时间为10分钟，第四站的持续时间为1小时。如果该行人凌晨 4 点出发，中午到达该地点，则走了多远？
8. 曲线梯形$a \leqslant x \leqslant b$、$0 \leqslant y \leqslant f(x)$共有多少个整数点，其中$a$、$b$为自然数，$a = f(x)$为线段$[a, b]$上连续且正的函数（位于梯形边界上的整数点也计算在内）？
9. 以原点为圆心、半径为 6.5 的圆中有多少个整数点？
10. 尿液中有 500 个球，从 1 到 500 个。随机抽取的球中的数字是 10、14、21 中任意数字的倍数的概率是多少？
