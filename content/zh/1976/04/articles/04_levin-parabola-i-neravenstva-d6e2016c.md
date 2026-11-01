---
id: 1976-4-levin-parabola-i-neravenstva-d6e2016c
issue: kvant_1976_4
year: 1976
number: "4"
title: 抛物线和不等式
authors:
  - Левин В.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 15, 16, 18
tag: 70UH
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 714505913edf63edb6508a65d23002308a74586864a450d14ffefa807f13e289
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/04_levin-parabola-i-neravenstva-d6e2016c.md
source_content_sha256: 8dfdce4c1d0101a47924301d5af41c652c0193f3c03324a2b61d04a02d585a8b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

V·莱文

抛物线和不等式

所有相同不等式的起源是任何实数的平方都是非负的：$x^2 \geq 0$。这个事实也可以表述如下：函数$y = x^2$（抛物线）的图形不会经过横坐标轴（图 1）下方。不等式$x^2 \geq 0$中的等号仅出现在$x = 0$处（抛物线$y = x^2$在原点接触x轴）。

在这篇文章中，我们将讨论如何基于这种基本的不平等，构建更复杂的不平等。

1. 考虑二次三项式

$$y = Ax^2 + 2Bx + C, \quad A \neq 0;$$

它的图形也是抛物线。让我们找到$x$的所有实值都满足不等式的充要条件

$$Ax^2 + 2Bx + C \geq 0. \quad (1)$$

这些条件很容易找到。首先，$A$必须为正，因为对于$A < 0$来说，总有一些值$x$不依赖于不等式（1）（当然，从$A < 0$的抛物线要么与横坐标轴相交，要么一切都位于轴下方的事实来看，这一点是清楚的）。以$x = x_0 = m + \sqrt{m^2 + m}$为例，其中选择了$m$

图 1.

⟦folio 15⟧

图 2.

$$AC = B^2, \text{ и именно при } x = -\frac{B}{A} \text{ (рис. 2 и 3).}$$

2. 让我们取任意实数

$$a_1, a_2, \dots, a_N; b_1, b_2, \dots, b_N; N \geqslant 1,$$

和一些$x$，并写出以下明显的不等式：

$$(a_1x + b_1)^2 + (a_2x + b_2)^2 + \dots + (a_Nx + b_N)^2 \geqslant 0. \tag{3}$$

可以重写为 $Ax^2 + 2Bx + C \geqslant 0,$

在哪里

$$A = a_1^2 + a_2^2 + \dots + a_N^2,$$

$$B = a_1b_1 + a_2b_2 + \dots + a_Nb_N,$$

$$C = b_1^2 + b_2^2 + \dots + b_N^2.$$

我们假设并非所有 $a_n$ ($n = 1, 2, \dots, N$) 都为零。那么我们可以说$A > 0$。

既然我们知道不等式（3）对于所有实数值都成立​​$x$，那么，根据条件$AC \geqslant B^2$，必然有

$$(a_1^2 + a_2^2 + \dots + a_N^2) \times (b_1^2 + b_2^2 + \dots + b_N^2) \geqslant (a_1b_1 + a_2b_2 + \dots + a_Nb_N)^2. \tag{4}$$

显然，这个不等式成立，有等号，并且当$a_1 = a_2 = \dots = a_N = 0$时，所以我们可以放弃至少有一个$a_n$不同于零的要求。

不等式（4）称为柯西不等式（Augustin Louis Cauchy (1789–1857) - 法国著名数学家）

⟦folio 16⟧

图 4.

则最简单的柯西不等式 (5) 表示为
$$|\vec{a}|^2 \cdot |\vec{b}|^2(\cos \alpha \cos \beta + \sin \alpha \sin \beta)^2 \leqslant \frac{|\vec{a}|^2 \cdot |\vec{b}|^2}{c_1^2}, \dots, \frac{|\vec{a}|^2 \cdot |\vec{b}|^2}{c_N^2}.$$
即 $\cos^2\varphi \leqslant 1$，其中 $\varphi = |\alpha - \beta|$ 是向量 $\vec{a} = (a_1, a_2)$ 和 $\vec{b} = (b_1, b_2)$ 之间的角度。

在任意$N > 2$的情况下，通过在$N$维空间中适当地放置两个向量$(a_1, a_2, \dots, a_N)$和$(b_1, b_2, \dots, b_N)$之间的角度$\varphi$，不等式（K）也可以写成$\cos^2\varphi \leqslant 1$。

3. 柯西不等式有许多应用。我们将用它来推导出其他更复杂的不等式。

考虑两个序列：具有非零项的序列 $a_1, a_2, \dots, a_N$ 和序列 $c_1, c_2, \dots, c_N$。

根据不等式 (K) 我们有
$$(a_1 + a_2 + \dots + a_N)^2 = \left(a_1 c_1 \cdot \frac{1}{c_1} + a_2 c_2 \cdot \frac{1}{c_2} + \dots + a_N c_N \cdot \frac{1}{c_N}\right)^2 \leqslant \left(a_1^2 c_1^2 + a_2^2 c_2^2 + \dots + a_N^2 c_N^2\right) \left(\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2}\right).$$
让我们把
$$\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2} = C_N,$$
将不等式(6)写成形式
$$(a_1 + a_2 + \dots + a_N)^2 \leqslant C_N \left(a_1^2 c_1^2 + a_2^2 c_2^2 + \dots + a_N^2 c_N^2\right).$$
(7)

当且仅当序列$a_1 c_1, a_2 c_2, \dots, a_N c_N$和$\frac{1}{c_1}, \frac{1}{c_2}, \dots, \frac{1}{c_N}$成比例时，(7)中的等号成立（很容易看出，这等价于强比例序列$a_1, a_2, \dots, a_N$和$\frac{1}{c_1^2}, \frac{1}{c_2^2}, \dots, \frac{1}{c_N^2}$）。

不等式(7)中的系数$C_N$称为不等式常数*)。

(7) 型最有趣的不等式是那些对于任意 $N$: $C_N < C$ 其常数都小于特定数字 $C$ 的不等式。如果有限制，这将是正确的

$$\lim_{N \to \infty} C_N = \lim_{N \to \infty} \left(\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2}\right) = C,$$
也就是说，如果一个无穷级数
$$\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2} + \dots = \sum_{n=1}^{\infty} \frac{1}{c_n^2}$$
收敛到总和$C^*$。

例子。让我们输入$c_n = n$，$n = 1, 2, \dots, N$。

那么不等式 (7) 将采用 $(a_1 + a_2 + \dots + a_N)^2 \leqslant C_N \left(a_1^2 + 2^2 a_2^2 + 3^2 a_3^2 + \dots + N^2 a_N^2\right)$ (8) 的形式
与常数
$$C_N = 1 + \frac{1}{2^2} + \dots + \frac{1}{N^2}.$$

*) 一个常数，因为 $C_N$ 对于所有序列 $a_1, a_2, \dots, a_N$ 都是相同的。

**) 关于极限，参见 M. Gerver 的文章“极限上的 20 个问题”，《Quant》，1974 年，第 3 期；关于无穷级数 - 同一作者的文章“从改变术语的位置......”，《Quant》，1974年，第9期。

⟦folio 18⟧

其中$\alpha_n$是线段$OM_{n-1}$和$OM_n$、$n = 1, 2, \dots, N$之间的角度值。
因此，我们可以写出等式
$$t = \sqrt{t^2 + (n-1)^2} \quad \sqrt{t^2 + n^2} \sin \alpha_n$$
从中
$$\sin \alpha_n = \frac{t}{\sqrt{t^2 + (n-1)^2} \sqrt{t^2 + n^2}} > \frac{t}{t^2 + n^2},$$
那是
$$\frac{t}{t^2 + n^2} < \sin \alpha_n, n = 1, 2, \dots, N.$$
然后
$$C_N = \frac{t}{t^2 + 1} + \frac{t}{t^2 + 2^2} + \dots$$
$$\dots + \frac{t}{t^2 + N^2} < \alpha_1 + \alpha_2 + \dots$$
$$\dots + \alpha_N < \frac{\pi}{2},$$
我们得到了不平等
$$(a_1 + a_2 + \dots + a_N)^2 < \frac{\pi}{2} \left( tP + \frac{1}{t} Q \right),$$
对于 $t$ 的任何正值均有效。

让我们把 $t = \sqrt{\frac{Q}{P}}$;通过选择$tP + \frac{1}{t} Q = 2\sqrt{PQ}$，我们得到卡尔森不等式，通常写成以下形式
$$(a_1 + a_2 + \dots + a_N)^4 < \pi^2 (a_1^2 + a_2^2 + \dots + a_N^2) (a_1^2 + 2^2 a_2^2 + \dots + N^2 a_N^2).$$

这个不等式对于任何 $N \geqslant 1$ 都有效；可以推广到无穷级数。在这个不等式 CONSTANTA $\pi^2$ 中 —

*) 这里提出的卡尔森不等式的推导（除了基本估计$C_N$）属于著名的英国数学家戈弗雷·哈罗德·哈代（Godfrey Harold Hardy，1877-1947）。

准确，但我们无法提供这一事实的简单证明。

卡隆不等式中所得常数 $\pi^2$ 的准确性意味着上述以角度 $\alpha_n$ 表示的基本估计 $C_N$ 并不太粗略。

卡隆的不等式有许多概括。我们只给出其中两个，但没有证明（符号$\Sigma$表示$n$从1到$N$的求和或无穷级数，即$n$从1到$\infty$的求和）：
$$(\Sigma a_n)^6 < 54 (\Sigma a_n^2) (\Sigma na^2) (\Sigma n^2 a_n^2),$$
$$(\Sigma a_n)^15 < 300 000 (\Sigma a_n^3) \times (\Sigma na^3) (\Sigma n^2 a_n^3) (\Sigma n^4 a_n^3).$$

在这些不等式中，常数 54 以及相应的 300,000 都是精确的。在实践中
1. 让
$$a_1^2 + a_2^2 + \dots + a_n^2 = 1$$
$$b_1^2 + b_2^2 + \dots + b_n^2 = 1.$$
该表达式的含义在什么范围内
$$a_1 b_1 + a_2 b_2 + \dots + a_n b_n?$$
2. 证明对于任意正 $a_1, a_2, \dots, a_n$
$$(a_1 + a_2 + a_3 + \dots + a_k)^2 \leqslant k (a_1^2 + a_2^2 + \dots + a_k^2).$$
什么时候遵守平等？
4. 证明对于非负 $a_1, \dots, a_k, b_1, \dots, b_k$：
$$\sqrt{a_1 b_1} + \sqrt{a_2 b_2} + \dots + \sqrt{a_k b_k} \leqslant \sqrt{a_1 + a_2 + \dots + a_k} \times \sqrt{b_1 + b_2 + \dots + b_k}.$$
5. 霍尔德不等式。
令$p > 1$和$\frac{1}{p} + \frac{1}{q} = 1$（$p$和$q$是有理正数）。证明
$$a_1 b_1 + a_2 b_2 + \dots + a_k b_k \leqslant \left( a_1^p + a_2^p + \dots + a_k^p \right)^{\frac{1}{p}} \times \left( b_1^q + b_2^q + \dots + b_k^q \right)^{\frac{1}{q}}.$$
