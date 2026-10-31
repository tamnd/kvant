---
id: 1973-9-resheniya-zadach-m179-m183-f193-f197-2c65d950
issue: kvant_1973_9
year: 1973
number: "9"
title: 问题解决方案M179—M183； F193—F197
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 39
page_labels: 27, 28, 30, 31, 32, 33, 34, 36, 37
tag: MP96
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 44afc153336a1d9b1d6c4aa19078efa2bb65973658071e5dfc8994c75d45a1cf
prompt_sha256: draft-1
translated_from: content/ru/1973/09/articles/10_resheniya-zadach-m179-m183-f193-f197-2c65d950.md
source_content_sha256: f25b808aad68a4139c0b2a1d9811d574fccfae0cada82efd14ec7d82278299eb
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

问题解决方案
M179—M183; F193—F197

M179。对于每个非直接有用三角形$T$，我们用$H(T) = T_1$表示其顶点是三角形$T$的底和高的三角形；通过$T_2 = H(T_1)$一个三角形，其顶点是三角形$T_1$的底；再让$T_3 = H(T_2)$，$T_4 = H(T_3)$，...

三角形 $T$ 的内角应该是多少？
a) 三角形 $H(T)$ 是锐角吗？
b) 在序列$T_1, T_2, T_3, \dots$中我们画一个直角三角形$T_n$（在这种情况下$H(T_n) = T_{n+1}$未定义）？
c) 三角形$T_1 = H(T)$ 与三角形$T$ 相似吗？
e)* 对于每个$n = 1, 2, 3, \dots$，我们指出存在多少个不相似的其他三角形$T$，其中$T_n$与$T$相似。

设$AA_1, BB_1$和$CC_1$为三角形$T$的高。三角形$A_1B_1C_1$的顶点$A_1, B_1, C_1$处的角$\alpha_1, \beta_1, \gamma_1$（分别）用三角形$ABC$的顶点$A, B, C$处的角$\alpha, \beta, \gamma$表示如下：

$$\alpha_1 = \pi - 2\alpha, \quad \beta_1 = \pi - 2\beta, \quad \gamma_1 = \pi - 2\gamma,$$

(11)

图 1.

图 2.

⟦folio 28⟧

s ($\alpha, \beta, \gamma$)。显然我们只能考虑案例
$$\alpha \geqslant \beta \geqslant \gamma$$
(2).

任何三角形的角度都可以用字母$\alpha, \beta$和$\gamma$表示，从而满足不等式（2）。

如果$\alpha < \frac{\pi}{2}$（所有角都是锐角），那么，由于从（2）得出不等式$2\pi - \alpha \leqslant 2\pi - \beta \leqslant 2\pi - \gamma$，对于三角形$T_1$和$T$的相似性，必须满足等式系统
$$\pi - 2\alpha = \gamma, \quad \pi - 2\beta = \beta, \quad \pi - 2\gamma = \alpha,$$
在哪里
$$\alpha = \beta = \gamma = \frac{\pi}{3}.$$

如果$\alpha > \frac{\pi}{2}$，那么从（2）我们只能使用$2\beta \geqslant 2\gamma$这一事实，并且必须考虑角度$\alpha_1, \beta_1$和$\gamma_1$之间的三种可能的关系：$2\beta \geqslant 2\gamma \geqslant 2\alpha - \pi, \quad 2\beta \geqslant 2\alpha - \pi \geqslant 2\gamma$和$2\alpha - \pi \geqslant 2\beta \geqslant 2\gamma$。其中第一个通向系统
$$2\beta = \alpha, \quad 2\gamma = \beta, \quad 2\alpha - \pi = \gamma,$$
在那里我们找到了一个有趣的解决方案：
$$\alpha = \frac{4\pi}{7}, \quad \beta = \frac{2\pi}{7}, \quad \gamma = \frac{\pi}{7},$$

另外两个，很容易检查，导致“表达”解决方案（其中一个角度形成于零），这不适合我们，正如他们所说，“不落在允许值的范围内”。

正如有兴趣解决这个问题的读者所写的那样，对于 $n = 2, 3, 4$ 以及一般的任何 $n$ 解决方案都可以通过类似但更麻烦的搜索来获得。事实上，原则上我们已将问题简化为代数问题。让我们概述进一步扩展计划的可能性（对于任意自然$n$）。由(1)式归纳可得三角形内角公式

$$\begin{cases}
\alpha_n = s2^n & \alpha + p\pi \\
\beta_n = s2^n & \beta + q\pi \\
\gamma_n = s2^n & \gamma + r\pi,
\end{cases}$$

其中$s$等于$+1$或$-1$，$p, q$和$r$是整数（证明给定$\alpha, \beta$和$\gamma$以及附加条件$\alpha_n \geqslant 0, \beta_n \geqslant 0, \gamma_n \geqslant 0$、$\alpha_n + \beta_n + \gamma_n = \pi$，参数$p, q, r$、$s$由下式确定） (3) 独一无二！）。让我们编写六个系统，将 ($\alpha_n, \beta_n, \gamma_n$) 等同于不同的排列 ($\alpha, \beta, \gamma$)，并求解它们中的每一个。从获得的解（取决于参数$p, q, r, s$）中，我们选择满足条件$\alpha \geqslant \beta \geqslant \gamma$的解。要回答这个问题：存在多少个解（对于给定的$n$），您需要找出有多少个整数解$p, q, r, s$（其中$s = \pm 1$）有六个结果不等式系统。为了实施这个计划，

⟦folio 30⟧

“是”的答案：数字 $n$ 总是大于或等于下一个 $x$。很明显，下一个$x$必须比所有已经使用过的多（否则这题将是唯一的）。

因此，在游戏开始时，你必须一直通知$x$——直到许愿的人第一次说“不”。令 $x_1 < x_2 < x_3 < \dots$ 为猜测者决定命名的序列，直到他收到第一个答案“否”。它必须是无限的，因为 $n$ 可以任意大。

现在来第二个游戏：第$k$题，第一次问的人回答“不”。因此，

$$x_{k-1} \leq n < x_k.$$

然后你可以应用类似于上面描述的策略$S_n$的策略，将剩余的间隙始终分成两半。显然，这最多需要 $|\log_2(x_k - x_{k-1})|$ 个问题。

假设在游戏的第二阶段，即在第一个答案“否”之后，我们就这样玩。仍然需要选择一个单调递增序列$x_k$来完整定义策略。

我们来看三种具体策略，区别仅在于序列$x_k$的选择。

1. 策略$T^1$：$x_k = 10k$。然后，如条件中所述，$f_T(n)$ 的增长大约与$\frac{n}{10}$ 一样多。

2. 策略$T^2$：$x_k = 2^k$。那么第一阶段的题数不超过$|\log_2 n|$，第二阶段的题数不超过$|\log_2 \frac{n}{2}|$。总共大约有 $2\log_2 n$ 个问题。

3. 策略$T^3$：$x_k = 2^{2k}$。现在第一阶段的题目数量已经大幅减少。事实上，让

$$2^{2k-1} \leq n < 2^{2k}.$$

那么游戏第一阶段的题数就等于$k$，不超过

$$k \leq \log_2 \log_2 n + 1,$$

对于较大的 $n$ 来说，它明显小于 $\log_2 n$。在第二阶段我们将消耗大约

$$\log_2(2^{2k} - 2^{2k-1}) \approx \log_2 2^{2k} = 2^k$$

 问题。这是好是坏？这取决于数字$n$。事实证明，对于区间 (2) 中的最多 $n$，该策略明显优于同一区间中的最多 $n$。

让$n = 2^{2k} - 1$。

然后

$$f_T(n) \approx \log_2 \log_2 n + 2^k \approx \log_2 n + \log_2 \log_2 n,$$

对于较大的$n$，第二项要小得多，并且$f_T(n)$与较低估计值$\log_2 n$的比率（参见公式（1））接近于1。

现在让$n = 2^{2k-1}$。那么$f_T^3(n)$的值是一样的，用$n$表示就是

$$f_T^3(n) \approx \log_2 \log_2 n + 2^k \approx 2\log_2 n + \log_2 \log_2 n,$$

也就是说，大约两个超出了较低的估计值 (1)。因此，对于$n$的这些值，策略$T^3$并不比策略$T^2$好。

这个位置由 图 7 处的图表说明。在此图表中，红线通常描绘了上面证明的较低估计值：$\log_2 n$（该图表具有定性、粗略的性质，并不假装准确）。

阶梯式黑线代表函数$f_T^3(n)$的图形。该函数在类型 (2) 的每个区间上都是常数。到这个时间间隔结束时，较低的估计值几乎赶上了它，但是这里 $f_T^3(n)$，比如说，被削弱了并且变得大约是原来的两倍。

问题出现了：是否存在一种策略 $T^4$ 使得所有 $n$ 的 $f_T^4(n)$ 与较低的估计值相差不大？ （预计时间表$f_T^4(n)$在下一段中给出。）

我们现在描述一个策略$T^4$使得

$$\lim_{n \to \infty} \frac{f_T^4(n)}{\log_2 n} = 1,$$

也就是说，对于大型 $n$ 策略，$f_T^4(n)$ 相对超出下限 $\log_2 n$ 的部分为零。

游戏的第一阶段，前面是一系列数字

$$x_k = 2^{2k}.$$

假设我们第一次收到第$k$问题的答案“否”，那么在哪里

$$2^{2k-1} \leq n < 2^{2k}.$$

让我们描述一下游戏第二阶段的策略$T^4$。让我们将 $n$ 分配给区间 (2) 中的每个

图 7.

⟦folio 31⟧

“重量”等于$\frac{1}{n}$。我们现在将以这样的方式提出问题，即大约将 $n$ 仍然可以取的值的数量除以一半，而是将它们的权重之和除以一半。

让我们计算一下在区间 (2) 中调试任意 $n$ 大约需要多少个问题。让我们输入$m=2^{2k-1}$。最初，权重之和约等于

$$\frac{1}{m} + \frac{1}{m+1} + \cdots + \frac{1}{m^2} \approx$$

$$\approx \left(1 + \frac{1}{2} + \cdots + \frac{1}{m^2}\right) -$$

$$- \left(1 + \cdots + \frac{1}{m}\right) \approx \ln(m^2) - \ln m =$$

$$= \ln m \leqslant \ln n.$$

如果我们猜测$n$，那么我们会将权重之和变为值$\frac{1}{n} \cdot$，这意味着权重之和将减少大约$n\ln n$倍。假设我们每次都能将其精确地分成两半。然后就被花掉了

$$\log_2 n\ln n = \log_2 n + \log_2 \ln n \approx \log_2 n$$

Vortsov（大 $n$ 的第二项明显小于第一项）。由于通常不可能将权重之和准确地分成两半，因此问题数量实际上会稍多一些。可以证明（但这比较困难）它仍然不超过

$$\log_2 n + \text{const}\log_2 \log_2 n$$

 $n$

$$\log_2 n + \text{const}\log_2 \log_2 n$$

沃尔佐夫。

很容易证明这个函数满足我们承诺满足的条件（3）。

J.M.巴津、A.L.图姆

**M 181. 一块软木塞的最小长度是多少，才能用来形成边长为 10 厘米的正方体框架？**（软木塞可以沿着一条边通过两次，具体取决于 $90^\circ$ 和 $180^\circ$，但不能被折断。）

回答。您需要至少 150 厘米的软木塞。

根据软木框架，如何有这个长度——如图 8所示。现在我们需要证明软木框架小于边长为10厘米的正方体的长度？

（让我们假设我们只能在立方体的顶点弯曲软木塞，并且我们已经制作了某种框架，并且软木塞的起点和终点

图 8.

在立方体的顶点。让我们计算一下该帧中的边数。当然，我们不会计算立方体的边（有 12 个），而是计算由孔组成的边。在框架中，恰好有一个孔开始的顶点和孔结束的顶点（这些顶点可能重合）。我们将这些顶点称为结束顶点，并将所有其余顶点称为经过顶点。每个经过的顶点都与偶数条边相邻。事实上，虫子既然进入了这个顶点，就必然要从这个顶点出来。因此，至少有四根肋骨与其相邻。至少三个肋与终端顶点相邻。因此，边的总数不少于$\frac{6 \cdot 4 + 2 \cdot 3}{2} = 15$。事实上，每条边都与两个顶点相邻，因此如果编号为 $i$ 的顶点与 $c_i$ 边（$i = 1, 2, \ldots, 8$）相邻，则 $c_1 + c_2 + \ldots + c_8$ 等于边数的两倍。因此，框架中至少有15根肋条，并且由于一根肋条的长度为10厘米，因此至少需要150厘米的孔。

现在我们需要证明，如果我们在肋条的内部点处弯曲插头，那么仍然不可能制作出小于150厘米的框架插头。这个问题可以简化为前一个问题，如下：在不通知孔的长度的情况下，可以重新切割任何框架，以便所有柱子最终都位于顶点。我们不会描述这种交替，而只会展示它出现的几张图片（参见图9，$a - \delta$；它们描绘了立方体的某个边缘，为了清晰起见，覆盖它的孔被扩大了）。

⟦folio 32⟧

图 9.

$$\frac{a}{b+c+d} + \frac{b}{a+c+d} + \frac{c}{a+b+d} + \frac{d}{a+b+c} \geq \frac{4}{3};$$

c) $a_1, a_2, a_3, \dots, a_n$ - 正数 ($n \geq 2$)，可以

$$\frac{a_1}{a_2+a_3+\dots+a_n} + \frac{a_2}{a_1+a_3+\dots+a_n} + \dots + \frac{a_n}{a_1+a_2+\dots+a_{n-1}} \geq \frac{n}{n-1}.$$

让我们立即解决问题(c)。我们用$s$表示总和$a_1 + a_2 + \dots + a_n$，用$b_i$表示数字$s - a_i$。在这个符号中我们需要证明

$$\frac{s - b_1}{b_1} + \frac{s - b_2}{b_2} + \dots + \frac{s - b_n}{b_n} \geq \frac{n}{n-1}.$$

这个不等式等价于：

$$s \left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right) \geq \frac{n}{n-1} + n = \frac{n^2}{n-1}.$$

(1)

现在让我们使用众所周知的算术平均值和几何平均值之间的关系（参见 «Kvant»，1970，第 8 期，第 33 页）：如果 $c_1, c_2, \dots, c_n$ 是非负数，则

$$\frac{c_1 + c_2 + \dots + c_n}{n} \geq \sqrt[n]{c_1 c_2 \dots c_n}.$$

(2)

由此可知

$$\left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right)^n \geq \frac{1}{b_1 b_2 \dots b_n}$$

还有那个$b_1 b_2 \dots b_n \leq \left( \frac{b_1 + b_2 + \dots + b_n}{n} \right)^n$。

从这两个不等式可以得出

$$\left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right)^n \geq \left( \frac{n}{b_1 + b_2 + \dots + b_n} \right)^n$$

最后，

$$\frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \geq \frac{n^2}{b_1 + b_2 + \dots + b_n}.$$

但

$$b_1 + b_2 + \dots + b_n = ns - a_1 - a_2 - \dots - a_n = (n-1)s,$$

在哪里

$$s \left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right) \geq \frac{sn^2}{s(n-1)} = \frac{n^2}{n-1}.$$

不等式(1)已被证明。

现在让我们提出一些消息，借助它们我们可以证明关系式（2）。让$c_1 + c_2 + \dots + c_n = 1$。 （这并不限制一般性。）让我们假设对于这些数字，关系（2）被违反，即

$$\frac{c_1 + c_2 + \dots + c_n}{n} < \sqrt[n]{c_1 c_2 \dots c_n}.$$

令数字 $c_i$ 的平均值不相等。然后在中间的$c_i$有两个数字 - 我们可以假设它们是$c_1$和$c_2$ - 这样$c_1 < \frac{1}{n}$，$c_2 > \frac{1}{n}$。注意$c'_1 = \frac{1}{n}$上的$c_1$，$c'_2 = c_1 + c_2 - \frac{1}{n}$上的$c_2$。那么对于数字$c'_1 = \frac{1}{n}, c'_2 = c_1 + c_2 - \frac{1}{n}$，关系式（2）也将被违反。这个事实的证据是不等式$\frac{1}{n} \left( c_1 + c_2 - \frac{1}{n} \right) > c_1 c_2$（在$c_1 < \frac{1}{n}, c_2 > \frac{1}{n}$）， - 你自己可以轻松应对这种不等式。

 $c_1 = c_2 = \dots = c_n = \frac{1}{n}$ $c_1, c_2, \dots, c_n$ $\frac{1}{n}, \frac{1}{n}, \dots, \frac{1}{n}$

⟦folio 33⟧

图 10.

$$ (n-1) \left( \frac{s-b_1}{b_1} + \dots + \frac{s-b_n}{b_n} \right) \geq n. $$
 $b_1 + \dots + b_n = (n-1) s$
$$ (n-1) \frac{s-b_1}{b_1} = \frac{b_1 + b_2 + \dots + b_n - (n-1) b_1}{b_1} = \frac{b_2 + \dots + b_n}{b_1} - (n-2) = \frac{b_2}{b_1} + \frac{b_3}{b_1} + \dots + \frac{b_n}{b_1} - (n-2). $$
 $(n-1) \frac{s-b_i}{b_i}$  $n$

 $\frac{b_i}{b_j}$
$$ \frac{b_i}{b_j} + \frac{b_j}{b_i} \geq 2 $$
 $i$  $j$ ($1 \leq i < j \leq n$
$$ C_n^2 = \frac{n(n-1)}{2}, $$

$$ (n-1) \left( \frac{s-b_1}{b_1} + \dots + \frac{s-b_n}{b_n} \right) \geq C_n^2 \cdot 2 - (n-2) n = n^2 - n - n^2 + 2n = n. $$
 $b_1 = \dots = b_n$ $a_1 = \dots = a_n$

图 11.

M183 $a$  $b$ ($a < b$ $90^\circ$ $-45^\circ$.

图  $ABCD$ $AB \parallel CD$ $AB = a$, $CD = b$, $BC = x$, $AD = y$ $E$  $CD$  $ABCE$  $AE = x$, $DE = b - a$ $ADE$
$$ xy \sin 45^\circ = (b - a) h, $$
(1)
 $h$
$$ (b - a)^2 = x^2 + y^2 - 2xy \cos 45^\circ. $$
(2)
 $AOB$, $BOC$, $COD$, $DOA$
$$ x^2 + y^2 = a^2 + b^2 $$
(3)
$\cos 45^\circ = \sin 45^\circ$):
$$ (b - a)^2 = a^2 + b^2 - 2(b - a)h. $$

$$ h = \frac{ab}{b - a}. $$

图  $\frac{b}{a} \geq 1 + \sqrt{2}$.

F193

⟦folio 34⟧

让我们考虑沿系统主光轴运行的平行光束，该系统由聚光透镜组成。通过第一个透镜后，光束变得会聚，通过第二个透镜后，光束变得更加会聚，依此类推。如果透镜的数量足够多，那么光束就会被包含在系统内部的一个点中。此后，光束发散，但其发散度会越来越小，直到变成平行；那么一切都会重复。射线的大致路线 图 12、a.

对于第二种情况，当系统由交替的会聚和发散透镜组成时（参见。 图 如图12，b）所示，光线轨迹的“周期”比第一种情况大得多，因为会聚透镜和散射透镜对光束的影响是相反的。

为了确定，透镜之间的距离取等于$1/3$焦距。对于任意光束以及焦距和透镜之间的距离之间的其他关系，原则上所有差异都保持相同。

F194 $\varphi_0 = 0$?

 $u = U_0 \sin \omega t$ $E = E_0 \sin \omega t$ $q$  $F = Eq$

⟦folio 36⟧

$$\frac{k(l_0 - l)^2}{2} = \frac{k(l_1 - l_0)^2}{2} + m_1g(l_1 - l)$$

($l_1$

$$l_1 = l_0 - \frac{m_1g}{k} + \sqrt{\left(l_0 - \frac{m_1g}{k}\right)^2 + l\left(l - 2l_0 + \frac{2m_1g}{k}\right)}$$

$$\Delta l = l_1 - l$$

$$\Delta x_{\text{цм}} = \frac{\Delta l m_1}{m_1 + m_2}$$

F196 $R$  $I_0$ $n$ $\varphi$

 $I$

$$I = en_0 v S$$

 $e$  $n_0$  $S$  $v$

$$n_0 = \frac{n}{2\pi RS}$$

$$I = \frac{en}{2\pi R} v$$

$$v_0 = \frac{2\pi R I_0}{ne}$$

 $\varphi$

$$E = \varphi$$

质子转一圈，电场对其做功$Ee$，受质子动能变化的影响：

$$\frac{mv^2}{2} - \frac{mv_0^2}{2} = Ee$$

（$m$ 是质子质量 $^*$）。

从这里我们可以找到质子在加速器室中旋转一圈后的速度：

$$v = \sqrt{v_0^2 + \frac{2Ee}{m}}$$

那么腔室中的电流将是这样的：

$$I = \frac{ne}{2\pi R} \sqrt{\left(\frac{2\pi R}{ne} I_0\right)^2 + 2\varphi \frac{e}{m}} = I_0 \sqrt{1 + \frac{n^2 e^3 \varphi}{2\pi^2 R^2 m I_0^2}}$$

I.Sh.斯洛博杰茨基

F197。在一根质量为 $m$ 的粉笔上，位于弹簧系数为 $k$ 的粗糙表面的地平线上，在时间 $t = 0$ 时刻，与时间成比例的力开始以与地平线成$\alpha$ 的角度作用。求t秒后身体运动的速度$v$。

将身体视为质点，作用在其上的力的距离 (图 15)。这就是万有引力mg、支撑反作用力$N$、力$f = At$（更方便说说它的分量$f_1 = At$ cos $\alpha$ 和$f_2 = At$ sin $\alpha$）

图 15.

⟦folio 37⟧

 $f_{\text{Tp}} = kN$ $f_1$ $f_{\text{Tp}} = kN = k(mg - At \sin \alpha)$ $t$.

 $t$ (图 16).

 $t_1$  $f_1$

$$At_1 \cos \alpha = kmg - kAt_1 \sin \alpha,$$

$$t_1 = \frac{kmg}{A(\cos \alpha + k \sin \alpha)}.$$

 $t_2$

$$N = mg - At_2 \sin \alpha = 0$$

$$t_2 = \frac{mg}{A \sin \alpha}.$$

 $\tau$ $t_1 < \tau < t_2$.

 $kA \sin \alpha \geq A \cos \alpha$ $t_2 - t_1$

 $\tau = t_1 + t'$ ($t'$  $t_1$)

$$A (t_1 + t') \cos \alpha + kA (t_1 + t') \sin \alpha - kmg - ma,$$

 $a$

图 17.

 $t_1$

$$a = \frac{A \cos \alpha + kA \sin \alpha}{m} t'.$$

 $a(t)$ (图  $v$  $\tau = t_1 + t'$

$$v = \frac{a(\tau - t_1)}{2} = \frac{(A \cos \alpha + kA \sin \alpha)(\tau - t_1)^2}{2m} = \frac{[\tau A(\cos \alpha + k \sin \alpha) - kmg]^2}{2mA(\cos \alpha + k \sin \alpha)}.$$

 图  $N = mg + At \sin \alpha$  $f_{\text{Tp}}$).

 $t_1$

$$At_1 \cos \alpha - kmg - kAt_1 \sin \alpha = 0;$$

$$t_1 = \frac{kmg}{A \cos \alpha - kA \sin \alpha}.$$

然而，在这种情况下，正值$t_1$仅在$A \cos \alpha > kA \sin \alpha$时出现。在$A \cos \alpha \leq kA \sin \alpha$，时间为$t_1 < 0$，没有任何运动发生。

$f_2$成分的增加可能会导致身体的破坏（这可能发生在时间$t_1$之前）。如果物体没有塌陷并且$t_1$有一个有限值，那么对于$\tau = t_1 + t'$时刻的速度$v$，我们得到的值：

$$v = \frac{[\tau A(\cos \alpha - k \sin \alpha) - kmg]^2}{2mA(\cos \alpha - k \sin \alpha)}.$$

A.V.乌斯蒂诺娃
