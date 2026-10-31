---
id: 1972-4-resheniya-6891eefe
issue: kvant_1972_4
year: 1972
number: "4"
title: 问题解决方案M96—M100； F108—F115
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 54
page_labels: 42, 43, 44, 45, 48, 49, 51, 52
tag: U9OT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 52d99205dd3ab4c86984918cc53058a4081ea1628c80987dae45b1bedc98b0b9
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/13_resheniya-6891eefe.md
source_content_sha256: 578c4d5b93a0f2487395e9dfb036395cbc2881800982bdfff7d2f57a390ba796
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

解决方案

本期我们发布问题M96—M100的解决方案

M96

已知有五个正数，其中任意三个数的和减去另外两个数的和，其差将为正数。证明所有十个这样的差异的乘积不超过给定五个数字的乘积的平方。

令 $a_1, a_2, a_3, a_4, a_5$ 为给定数字然后$(a_1+a_2+a_3-a_4)(a_1+a_3+a_4-a_2-a_5)=a_1^2-(a_2+a_5-a_3-a_4)^2\leq a_1^2$。

同理，证明$(a_2+a_3+a_1-a_4-a_5)\times(a_2+a_4+a_5-a_3-a_1)\leq a_2^3$，
$(a_3+a_4+a_2-a_5-a_1)\times(a_3+a_5+a_1-a_4-a_2)\leq a_3^2$,
$(a_4+a_5+a_3-a_1-a_2)\times(a_4+a_1+a_2-a_5-a_3)\leq a_4^2$,
$(a_5+a_1+a_4-a_2-a_3)\times(a_5+a_2+a_3-a_1-a_4)\leq a_5^2$.

仍然需要增加这些不平等，问题就解决了。

证明一个更一般的说法：如果给定 $2n+1$ 正数，任意 $n+1$ 数之和与 $n$ 剩余正数之和之差，则所有 $C_{2n+1}^n$ 此类差值的乘积 $B$ 与所有 $2n+1$ 给定数字的乘积 $A$ 通过不等式相关

$$B^n\leq A^{C_{2n+1}^n}$$

M97

在具有底边 $AB=a$ 和 $CD=b$ 的梯形 $ABCD$ 中，绘制一条线段 $A_1B_1$ 连接对角线的中点。在生成的梯形$A_1B_1CD$中，再次绘制线段$A_2B_2$，连接对角线的中点，依此类推（图1）。一个数字有可能在长度$AB, A_1B_1, A_2B_2, \dots$的序列中出现两次吗？这个序列是单调的（递增还是递减？）它是否趋于某种极限？

设$A_1$和$B_1$为梯形对角线$AC$和$BD$的中点，$E$和$F$为边的中点-

⟦folio 43⟧

外侧 AD 和 BC (图 2)。由于$A_1F$是三角形ACB的中线，$B_1F$是三角形DCB的中线，则点$A_1$和$B_1$位于线段EF上，

$$a_1 = A_1B_1 = |A_1F - B_1F| = \left| \frac{a-b}{2} \right|.$$

（无论$a$和$b$哪个数字更大，这个公式都成立。）同理证明

$$a_{n+1} = \left| \frac{a_n - b}{2} \right|,$$

(1)

其中 $a_n = A_nB_n$ ($n=1, 2, 3, \dots$) 是我们感兴趣的序列。因此，问题被简化为关于由（1）与原始项$a_0 = a > 0$的对应关系确定的序列的代数问题。

如果$a_n > b$，则$a_{n+1} = \frac{a_n - b}{2} < a_n - b$。

因此，如果$a > b$，那么序列中的每一项都会比前一项至少小$b$，直到遇到$a_m$使得$a_m \leq b$（如果$a \leq b$，那么我们放入$m=0$，$a_m = a_0 = a$；许多读者只考虑了这种情况；《数学问题》一书中只考虑了它*）。

所以，我们现在只考虑$n \geq m$。

如果$a_n \leq b$，则$a_{n+1} = \frac{b - a_n}{2} \leq \frac{b}{2} < b$。

因此，$a_m$之后的序列的所有项都将小于$b$，因此对于所有$n \geq m$

$$a_{n+1} = \frac{b - a_n}{2}.$$

(2)

图 2.

*) E. B. Dynkin、S. A. Molchanov、A. L. Rosenthal、A. K. Tolygu，“数学问题”，编辑。第三，《科学》，1971 年，第 147 题。

图 3. 由条件$a_0 = a$、$a_{n+1} = \left| \frac{a_n - b}{2} \right|$定义的序列$a_n$的项是绿色包围的虚线顶点的横坐标。这条虚线的连线交替平行于轴$Ox$、$Oy$，其顶点交替位于方程$y = x$的直线上和函数$y = \left| \frac{x - b}{2} \right|$的图形上。

图 4.

方程$x = \frac{b - x}{2}$有唯一解$x = \frac{b}{3}$。因此，如果序列$\{a_n\}$有极限，那么它就等于$\frac{b}{3}$。

让$a_m \neq \frac{b}{3}$。让我们输入$a_n = \frac{b}{3} + \delta_n$。那么从(2)可以得出$\frac{b}{3} + \delta_{n+1} = \frac{b}{3} - \frac{\delta_n}{2}$，即

$$\delta_{n+1} = -\frac{\delta_n}{2}$$

(3)

— 当从$n$移动到$n+1$时，差值$a_n - \frac{b}{3} = \delta_n$改变符号并且横坐标值减半。现在一切都清楚了：在序列 $a_n$ 中，任何数字都不能出现两次，每个数字的最后一项比前一项是 $\frac{b}{3}$。这个序列不是单调的，而是趋于极限 $\frac{b}{3}$ (图 3, 4)。

⟦folio 44⟧

图 5.

不幸的是，一些读者写道：“由于序列不是单调的，所以它不会趋于极限。”
这种推理当然是不正确的。让我们用极限的定义来证明

$$\lim_{n \to \infty} a_n = \frac{b}{3}.$$

设$\varepsilon > 0$。那么如果$n > N$，其中$N = N_{(\varepsilon)}$是$2^N \varepsilon > 2^m |\delta_m|$的最小整数，那么$\left| a_n - \frac{b}{3} \right| = |\delta_n| = \frac{|\delta_m|}{2^n - m} < \frac{|\delta_m|}{2^N - m} < \varepsilon$。

至此(4)得证。

当然，即使在 $a_m = \frac{b}{3}$ 的情况下，极限也等于 $\frac{b}{3}$ - 在这种情况下，所有后续项也等于 $\frac{b}{3}$。让我们看看在 $a$ 取什么值时会出现这种情况。如果$m = 0$，则$a = \frac{b}{3}$。如果$m = 1$和$a_1 = \frac{a - b}{2} = \frac{b}{3}$，则$a = \frac{5b}{3}$。

图 6.

一般来说，如果$a_m = \frac{b}{3}$，则$a = a_0$是由$a_m = \frac{b}{3}$应用公式$a_{n-1} = 2a_n + b$$m$次后得到的。因此，很容易检查，$a_m = \frac{b}{3}$的值$a$构成序列$\frac{b}{3}, \frac{5b}{3}, \frac{13b}{3}, \ldots, \frac{(2^k - 3)b}{3}$，...对于这些（且只有这些）值$a$，序列结果是单调的（并且从某个点开始是常数）。

我们还没有单独看到$a_m = b$（同时$a_{m+1} = 0, a_{m+2} = \frac{b}{2}, \ldots$）的情况 - 从代数的角度来看，没有任何适用，但相应的$n = m$和$n = m+1$梯形退化为平行四边形和三角形（点$B_{m+1}$和$C_{m+1}$重合，图5）；从$n = m+2$开始，获得梯形压力，并且一如既往地，$a_n$趋于极限$\frac{b}{3}$。

M98

证明表中

1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1

其中每个数字等于其上面三个数字的总和，每行（从第三行开始）都有一个偶数。每行（前两行除外）是否包含可被三整除的数字？

我们先来看看能被二整除的问题。在我们的表中，我们将一起写 0，而不是奇数 - 1。然后需要根据相同的规则来编译 0 和 1 的表（每个数字都是上一行中上面三个数字的总和），只需根据规则 $0+0=0, 0+1=1+0=1, 1+1=0$ 执行“模二”​​加法。

第一个基于这样的组合：每行中的最后一个偶数仅取决于前一行中的最后一个偶数是什么，因此这个四元数是周期性重复的（周期为 4，参见图6）*）也就不足为奇了。

*) D. O. Shklyarsky、N. N. Chentsov 和 I. M. Yaglom 编辑的《初等数学问题和定理精选》一书中给出了类似的解决方案。第四，《Nuka》，1965 年，第 10 题。

⟦folio 45⟧

许多读者提出的另一种解决方案是反证法。假设某个字符串完全由 1 组成：

111 ... 111

那么上一行，很容易看出，只能是这样：

100100 ... 001001,

而她面前的人是这样的：

110000110000 ... 000011000011.

但这是不可能的，因为我们表的每一行都有奇数个数字。

至于能被 3 整除，您可以很容易地看到，已经在表的下第四行中了（可以方便地将数字 0 分配给一个单位的顶行）

1 4 10 16 19 16 10 4 1

没有一个数字能被 3 整除（并且所有数字除以 3 时都会余 1）。了解了“模 3”表的结构（在 图 7 上，除以 3 后得到余数 0、1 和 2 的数字分别被黄色、黑色和红色圆圈替换），您可以注意到，相同的属性将包含数字为 1、1+3=4、1+3+3^2=13、1+3+3^2+3^3=40 等的行。

读者在来信中报告了此表中数字的其他属性。可以推断出许多不同的属性；利用表的第 n 行包含多项式的系数这一事实

$$(1+x+x^2)^n = \sum_{k=0}^{2n} B_n^k x^k$$

（操作与“biomp系数的算术”一文大致相同，“Quant”第6期，1970）。例如，立即清楚$\sum_{k=0}^{2n} B_n^k = 3^n$，$\sum_{k=0}^{2n} (-1)^k B_n^k = 1$，并且不难证明$\sum_{k=0}^{n} (B_n^k) = B_{2n}^n$（参见 A. M. 和 I. M. Yaglomov 的书“Non-elementary issues inelementarypresentation”，Gostekhidat，1954）中的问题 61。检查一下

**图 7.**

图 8.

如果 $p$ 是质数，$s < p$ 和 $r < p$，则

$$B_{lp+s}^l B_{m+r}^m \equiv B_{l}^l B_{m}^s + B_{l-1}^l B_{m}^s + p$$ (mod $p$)

（如果$k > 2n$，则$B_{n}^k$被视为等于0）。

问题的解决方案 **M96 - M98** 由阅读器多项式发送。其中至少两个问题由 A. Grizoryan（巴库）、S. Konyazin（萨拉托夫）、A. Merkuryev（列宁格勒）、M. Rozov（明斯克）、M. Preezer（托木斯克）、A. Slinkin（莫斯科）、A. Chernyak（明斯克）、E. Turkevich（切尔诺夫策）、S. Komanov（格鲁吉亚察尔卡村）解决。 SSR），G. Timofeev（萨拉托夫），Yu。 Kisin (Stranaia Russa)、V. Nadezhko (列宁格勒)、A. Blyukhin (克麦罗沃州基谢廖夫斯克)、E. Gundur (沃罗什尔戈夫里亚德)、A. Makarytsev (利沃夫)、I. Shparlinsky (莫斯科)。

**M99**

三角形ABC中AC边最长。证明对于平面上任意一点M AM+CM 不小于BM。什么情况下可以实现平等？

我们首先证明这个引理。

引理。对于平面上任意四点A、B、C、M

$$AC \cdot BM \leq AB \cdot CM + BC \cdot AM$$ (1)

当且仅当 ABCM 是凸循环四边形时（或者当右侧的一项由于某些两点重合而为零时），等式才成立。

引理的证明。让我们选择一个点 P，使得 $\Rightarrow BAP = \Rightarrow CAM$ 和 $\Rightarrow MAP = \Rightarrow CAB$，并且 PA = $\frac{AB \cdot AM}{AC}$ (图 8)。然后 $\triangle BAP \sim \triangle CAM$ （第一个得到 -

⟦folio 48⟧

吸管旋转的位置与其中心不重合。

每根稻草的摩擦力与这些稻草的重量成正比

$$F_1 = m \frac{l - x}{l} gk, \quad F_2 = m \frac{x}{l} gk.$$

现在我们可以写出相对于点 0 的力矩为零的条件：

$$F(l - x) - F_1 \left( \frac{l - x}{2} \right) - F_2 \frac{x}{2} = 0.$$ (1)

代入值$F_1$、$F_2$和$F \approx mgk$（因为根据条件$F$仅略小于$mgk$），我们发现

$$x = \frac{l}{\sqrt{2}}.$$

这个距离小于吸管长度的一半。因此，吸管不会绕中间旋转，而是绕靠近一端的一点旋转。将吸管转到$180^\circ$，蚂蚁会在远处看到它。现在可以重复整个操作，只需将吸管放在另一端即可。等等。

我们还研究一下公式（1）。将$F_1 = m \frac{l - x}{2} gk$和$F_2 = m \frac{x}{l} gk$代入其中并表示$\alpha = \frac{F}{mgk}$，我们得到

$$\alpha = \frac{2x^2 + l^2 - 2lx}{2l(l - x)}.$$

那些知道如何求函数最小值并将其导数等于零的人会发现 $\alpha$ 在 $x = l \left( 1 - \frac{\sqrt{2}}{2} \right) \approx 0,3l$ 处最小。它等于0.43。因此，为了旋转吸管，蚂蚁只需要向一端施加等于 0.43 $mgk$ 的力。

加法正确解：V. Belov (沃洛格达)、I. Bramovskaya (乌索尔耶-西伯尔斯科耶，伊尔库茨克地区)、M. Weinhacher (克里沃罗格)； F. Galtsev（塔什干）； E. Golubev（马莫诺夫，加里宁格勒地区）、D. Grak（斯莫列维奇，明斯克地区）、E. Gromak（新库兹涅茨克）； G.扎伊采夫（加格拉）； L. Knizherman（莫斯科）； S.库兹姆奇（日托米尔）； E. Latyshev (巴库)、A. Levykin (阿穆尔州赖加欣斯克)、S. Legushiin (第聂伯罗彼得罗夫斯克)、M. Preer (托木斯克)、A. Redchenko (苏梅州 Novopetrovka 村)、A. Renkov (克麦罗沃州 Polomshnoye 村)、L. Salina (布拉戈维申斯克)、V. Servakh (伏龙芝)、 N. Fedin (鄂木斯克)、M. Flerov (莫斯科)、G. Shepenko (大卫-戈罗多克，布列斯特地区)、M. Yudson (伏尔加格勒)、S. Chekmarev (莫斯科)。

F109

经实验确定，温度 $m=142$ 冰水呈轻状态，悬浮在房间中央，上升至 $\Delta t=4^\circ$ 半小时后。当有相同数量的冰时，需要10个小时才能拉完。根据这个实验，冰的熔化比热是多少？水的比热容 $c_B=1$ 卡/克

让我们求出半小时内向容器提供的热量$Q$。由于这个热量足以加热水，那么

$$Q = c_B m \Delta t.$$

10 小时内，向容器提供的热量增加了 20 倍。这就是为什么

$$\lambda m = 20 c_B m \Delta t.$$

从这里

$$\lambda = 20 c_B \Delta t = 80 \text{ кал/г}.$$

这个问题的正确解决方案已经获得了大约100名读者。

F110

如果电压表与上电阻$r_1$（图 11）并联，则显示$u_1=6$v，如果与下电阻$r_2$并联，则显示$u_2=4$v，如果与$A$和$B$连接，则显示$u=12$v。电阻 $r_1$ 和 $r_2$ 上的实际压降是多少？

源的内阻小到可以忽略不计。

当电压表连接到$A$和$B$点时，其读数等于ed。和。来源。因此，如果电压表接电阻$r_1$，电压表内阻为$r$，则电路中有电流流过

$$I = \frac{u}{r_2 + \frac{r_1 r}{r_1 + r}}.$$ (1)

这意味着

$$u_1 = \frac{u}{r_2 + \frac{r_1 r}{r_1 + r}}.$$ (1)

图 11.

⟦folio 49⟧

完全一样

$$u_2 = \frac{u}{r_1 + \frac{r_2 r}{r_2 + r}} \frac{r_2 r}{r_2 + r}.$$

将最终方程（1）除以方程（2），我们得到

$$\frac{u_1}{u_2} = \frac{r_1}{r_2}.$$

因此，$$\frac{r_1}{r_2} = \frac{6}{4} = \frac{3}{2}.$$

当电压表关闭时，电阻$r_1$和$r_2$方向的压降等于$u=12$in。由于电阻比已知，不难找到电阻上$u'_1$和$u'_2$方向的压降：

$$u'_1 + u'_2 = u, \quad \frac{u'_1}{u'_2} = \frac{r_1}{r_2}.$$

从这里

$$u'_1 = \frac{u r_1}{r_1 + r_2} = \frac{u}{1 + \frac{r_2}{r_1}} = 7,2b;$$

$$u'_2 = u - u'_1 = 4,8b.$$

正确的解决方案由以下人员发送：P. Anenko（奥伦堡地区 Totskoe 村）、E. Doltsov（莫斯科）、A. Kachilson（图拉地区新莫斯科斯克）、S. Kuzmchi（日托米尔）、E. Lamyshev（巴库）、A. Levykin（阿穆尔地区 Raigakhinsk）、A. Mamula（基辅地区 Dybintsy 村）、V. Peresedov (波维斯特涅沃)、M. Preezer (托木斯克)、L. Rudtser (哈尔科夫)、L. Salnitsa (布拉戈维申斯克)、A. Sboev (梅德韦多克定居点，基洛夫地区)、P. Sereev (格罗兹尼)、Sh. Slenoy (切尔诺夫策)、N. Tkachenko (第聂伯罗彼得罗夫斯克)、I. Turishchev (克鲁泡特金，克拉斯诺达尔边疆区)、N. Fedin (鄂木斯克)、G. Tsibenko (斯拉维扬斯克，顿涅茨克地区)、L. Tsiferblat (利沃夫)、V. Shabunin (莫斯科)、E. Shakhnovich (加里宁地区)、R. Shzaanov（柳别尔齐，莫斯科地区），I. Yurtsenko（基辅）。

F111

有一根含有爆炸性物质的均质绳索。绳索的燃烧速度为$v$，冲击波沿冲击传播的速度为$c$。找到需要沿其展开绳索的线的形状，以便来自绳索所有点的波同时流向给定点。

是否有可能对爆炸表面进行同样的操作并获得具有高能量密度的下降球面波？

如果冲击波的传播速度大于绳索的燃烧速度，则不可能将绳索展开以使冲击波从绳索的所有点同时流向给定点。如果$v=c$，那么很长的绳索必须沿着穿过给定点的直线延伸。对于$v>c$来说，答案并不是那么多。

让我们更详细地看看这个案例。

令 图 12 处的红色曲线为线，绳索必须沿着该线展开，以便爆炸波同时冲向点 $O$。让我们选择直线 $A$ 和 $B$ 上的两个接近点，使得曲线 $AB$ 可以被视为一条直线（为此，线段 $AB$ 必须远小于从点 $O$ 到点 $A$ 和 $B$ 的距离 $r_0$ 和 $r_1$）。线段$AB$构建的时间将表示为$\tau$。然后$AB=v\tau$。 $AB$小意味着$\tau$小。在 $\tau \rightarrow 0$ 处，点 $B$ “趋向”点 $A$，并且线段 $AB$ 的方向 - 趋向于点 $A$ 处红色曲线的切线方向。

让我们找到形成半径为 $OA$ 的线段 $AB$ 的角度 $\alpha$。为此，请关闭半径 $OA$（等于半径 $r_2$ 的长度）处的线段 $OC$，并绘制线段 $BC$。由于线段$AB$较小，因此线段$BC$与另一个半径为$r_1$、以点$O$为圆心且角度$ACB$接近直线的圆重合（且在$\tau \rightarrow 0$$\Rightarrow ACB \rightarrow \frac{\pi}{2}$处）。这意味着

$$\cos \alpha = \frac{AC}{AB}.$$

但是$AB=v\tau$和$AC=r_0-r_1$。由于爆炸波从$B$点传播的时间应比波从$A$点传播的时间小m，则$r_1=r_0-c\tau$。因此，$AC=r_0-r_0+c\tau=c\tau$ 和

$$\cos \alpha = \frac{c\tau}{v\tau} = \frac{c}{v}.$$

因此，红色曲线的切线和从点 $O$ 到曲线点所画的半径所成的角度并不取决于曲线到点 $O$ 的距离，并且红色曲线以相同的角度 $\alpha = \arccos \frac{c}{v}$ 与离开点 $O$ 的所有光线相交。这样的房产

⟦folio 51⟧

图 14.

通过计算每个平面的光线的入射和折射，我们可以得出光线在每个平面中传播的角度与光线从空气落在其上的角度相同

$$\frac{\sin \beta_1}{\sin \gamma_i} = n_i$$

特别是从这里开始，在穿过整个平面堆栈后，光线将平行于其原始方向射出：

$$n_{k+1} = 1 \text{ и } \frac{\sin \beta_1}{\sin \gamma_{k+1}} = 1, \text{ то есть}$$

$$\beta_1 = \gamma_{k+1}$$

光束的混合显然等于其在各个平面中的混合之和

$$h = h_1 + h_2 + \dots + h_k$$

让我们找到混合物 $h_i$ (图 14)。为此，首先从三角形 ADB 中找到 $AB$：

$$AB = \frac{AD}{\cos \gamma_i} = \frac{d}{\cos \gamma_i}$$

现在从三角形ACB我们得到

$$h_i = AB \cdot \sin (\beta_1 - \gamma_i)$$

$$= d \frac{\sin (\beta_1 - \gamma_i)}{\cos \gamma_i}$$

$$= d (\sin \beta_1 - \cos \beta_1 \mathrm{tg} \gamma_i)$$

从$tg \gamma_i = \frac{\sin \gamma_i}{\sqrt{1 - \sin^2 \gamma_i}}$开始

$$= \frac{\sin \beta_1}{n_i} \sqrt{1 - \left(\frac{\sin \beta_1}{n_i}\right)^2} = \frac{\sin \beta_1}{\sqrt{n_i^2 - \sin^2 \beta_1}}$$

那么$h_i = d \sin \beta_1 \left(1 - \frac{\cos \beta_1}{\sqrt{n_i^2 - \sin^2 \beta_1}}\right)$

$$= d \cos \alpha \left(1 - \frac{\sin \alpha}{\sqrt{n_i^2 - \cos^2 \alpha}}\right)$$

总光束混合为

$$h = h_1 + h_2 + \dots + h_k$$

$$= d \cos \alpha \left( k - \frac{\sin \alpha}{\sqrt{n_1^2 - \cos^2 \alpha}} - \frac{\sin \alpha}{\sqrt{n_2^2 - \cos^2 \alpha}} - \dots - \frac{\sin \alpha}{\sqrt{n_k^2 - \cos^2 \alpha}} \right)$$

$$= d \cos \alpha \left( k - \sin \alpha \sum_{i=1}^{k} \frac{1}{\sqrt{n_i^2 - \cos^2 \alpha}} \right)$$

正确的解决方案由 V. Belov (沃洛格达)、E. Dollov (莫斯科)、A. Mamula (Dybintsy，基辅地区)、V. Mukhanov (Kanash UASSR)、S. Pomashev (乌里扬诺夫斯克)、M. Premer (托木斯克)、L. Rudtser (哈尔科夫)、A. Sboev (Medvedok 村，基洛夫地区)、P. Sereev 发送（格罗兹尼），Sh。 Blind（切尔诺夫策）、N. Tkachenko（第聂伯罗彼得罗夫斯克）、A. Udaltsov（加里宁格勒，莫斯科地区）、N. Fedin（鄂木斯克）、S. Fillenko（扎波罗热）、G. Filkovsky（巴库）、M. Flerov（莫斯科）、S. Chekmarev（莫斯科）、G. Shenemko（大卫-戈罗多克，布列斯特）地区）。

F113

容器里装满了一半的水，其中漂浮着一块冰。将煤油倒在冰上，冰的上层距酱汁底部$h$的高度（图15）。当冰融化时这个高度会如何变化？

在一块冰完全被煤油覆盖的情况下（如图所示），问题就解决得很简单。

让我们在精神上固定住一块冰的外壳并融化冰。显然，形成的水的体积将小于冰的体积。因此，容器中的总体液位将下降。

现在假设煤油没有覆盖冰。

显然，如果容器中只有水和冰，那么冰融化后水位不会变化。确实，由于酱汁底部的压力等于酱汁内容物的重量，并且当冰融化时它不会改变，因此酱汁底部的压力不会改变。这意味着酱汁底部的压力不会改变。但冰不会对底部施加直接压力 - 它会漂浮。因此，底部的压力等于水压

$$P = \rho_B g h_B$$

冰融化后压力也等于水压

$$P = \rho_B g h_B'$$

这意味着$h_B = h_B'$。

⟦folio 52⟧

图 15.

在我们的例子中，底部的压力也没有改变。但现在等于这么多水和煤油的压力之和

$$P = \rho_B g h_1 + \rho_K g (h - h_1) = (\rho_B - \rho_K) g h_1 + \rho_K g h'$$

如果冰融化后容器内的水位为$h'_1$，煤油位为$h'$，则

$$(\rho_B - \rho_K) g h'_1 + \rho_K g h' = (\rho_B - \rho_K) g h_1 + \rho_K g h'$$

设水中冰的体积等于$V_1$，煤油中冰的体积等于$V_2$，冰的质量等于$m$。让我们想象一下，除去冰后，我们离开其失重的外壳，并将水和煤油倒入其中，使它们在外壳中的液位与容器中的水位一致。很明显，这个壳将处于平衡状态。但这意味着水壳受到阿基米德浮力$F$，等于倒入壳中的液体的重量

$$F = \rho_B g V_1 + \rho_K g V_2$$

如果冰本身放入壳内，则力$F$不会改变。但冰会浮起来。这意味着 $F = mg$ 和

$$\rho_B g V_1 + \rho_K g V_2 = mg.$$

如果容器中只有冰和水，那么水中的冰体积为$V'_1$，

$$\rho_B g V'_1 = mg.$$

从公式（1）和（2）可以看出，在我们的例子中，水中的体积$V_1$小于$V'_1$，即小于浸入水中且上方没有煤油的情况下的冰。但在后一种情况下，正如我们所展示的，容器中的水位不会改变。这意味着冰融化时形成的水恰好充满冰淹没部分的体积$V'_1$。

在我们的例子中，冰融化时形成的水的体积是相同的，但是体积
