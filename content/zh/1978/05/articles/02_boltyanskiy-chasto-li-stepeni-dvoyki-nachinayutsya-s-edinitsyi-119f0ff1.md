---
id: 1978-5-boltyanskiy-chasto-li-stepeni-dvoyki-nachinayutsya-s-edinitsyi-119f0ff1
issue: kvant_1978_5
year: 1978
number: "5"
title: 二的幂经常以一开始吗？
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 4, 6
tag: GLE7
lang: zh
source: kvant_digital
extraction: vision
content_sha256: fafcab13319fd19e65277012f3aa964eacf4a7f52309def58413c4465c8e96d0
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/02_boltyanskiy-chasto-li-stepeni-dvoyki-nachinayutsya-s-edinitsyi-119f0ff1.md
source_content_sha256: 6a0557be44f15c8e056cf405895e1e8f515ea49c1c41fd5d509391b3ac00cdee
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

V·博尔坦斯基

二的幂经常以一开始吗？

问题陈述
以一开头的两个数的中间幂一次又一次出现。它们发生的频率是多少？换句话说，从数字$2^1, 2^2, \ldots, 2^n$中随机选择一个以数字1开头的数字的概率是$a_n/n$。该概率取决于 $n$，即取了多少个 2 的一次幂。限制

$$p_1 = \lim_{n \to \infty} \frac{a_n}{n},$$

（如果存在）称为任意给定自然数能被 3 整除的概率？

1. 数字 $\frac{161}{222}$ 的十进制展开式中的任意一位是 5 的概率是多少？双倍的？

2. 任何给定的自然数是完全平方数的概率是多少？

⟦folio none⟧

超出限制 (1)

在2的幂的两位数中，正好有1（即16）以1开头。在二的三位幂中，恰好有一个数字（即128）以一开头。对于四位数的二的幂也是如此。

一般来说，对于$k > 1$来说，在$k$位的2的幂中，正好有一个是从1开始的。事实上，最小的$k$位的2的幂一定是从1开始的（否则除以2，我们会得到之前的2的幂是$k$位的数）。在 $k$ 位的二的幂中，没有其他以 1 开头的数字：下一个二的幂将首先是 2 或 3，下一个将是更大的数字，直到得到$(k+1)$ 位的数字。

由上可知，如果数字$2^n$是$m$位数，则数字$2^1, 2^2, \dots, 2^n$中正好有$m-1$以1开头的数字，即$a_n = m-1$。但是“数字 $2^n$ 是 $m$ 位”这句话的意思是

$$10^{m-1} \leq 2^n < 10^m,$$

那是

$$m-1 \leq n \lg 2 < m.$$

记住$a_n = m-1$，我们得到

图 1.

$$\lg 2 - \frac{1}{n} < \frac{a_n}{n} \leq \lg 2,$$

因此

$$p_1 = \lim_{n \to \infty} \frac{a_n}{n} = \lg 2 = 0,30103...$$

因此，略多于 30% 的 2 的幂都是从 1 开始的。

3 个阿达奇和

4. 让我们用 $p_q$ 表示任意 2 的幂以数字 $q^*$ 开头的概率。证明等式

$$p_2 + p_3 = p_1, \quad p_4 + p_5 = p_2, \quad p_6 + p_7 = p_3, \quad p_8 + p_9 = p_4.$$

5. 证明$p_4 = 1-3 \lg 2 = 0,096...$

正如您所看到的，2 的幂以数字 4 开头的频率比以数字 1 开头的频率少三倍多 (图 2)。

图 2.

一般任务

给定自然数 $l$ 的任意幂（以十进制表示）以数字 $q$ 开头的概率是多少？

让数字$l^n$以十进制表示法以数字$q$开头，即

$$q \cdot 10^m \leq l^n < (q+1) \cdot 10^m,$$

其中 $m$ 是某个自然数。 Dividing these inequalities by $q \cdot 10^m$ and continuing to rhyme in base 10, we get:

$$0 \leq (n \lg l - \lg q) - m < \lg \frac{q+1}{q}.$$ (2)

由于右边的数小于一（$\frac{q+1}{q} = 1 + \frac{1}{q} \leq 2 < 10$），不等式（2）意味着数$n \lg l - \lg q$的小数部分小于$\lg \frac{q+1}{q}$（记住小数部分）

*) 数字 $p_q$ 的存在由以下推论。

⟦folio 4⟧

数字$x$是数字$x$与其整数部分$\{x\} = x - [x]$的差，整数部分$x$是不超过$x$的最大整数）。相反，如果数字$n \lg l - \lg q$的小数部分小于$\lg \frac{q+1}{q}$，即，如果对于某个自然数$m$满足不等式（2），则$l^n$以十进制数从数字$q$开始。 Thus, the posed problem is equivalent to the following: what is the probability that for an arbitrary natural number $n$

$$\{n \lg l - \lg q\} < \lg \frac{q+1}{q}$$

将帮助我们解决最后一个问题

分数部分定理$x$。设$\alpha, \beta$为实数，$\alpha$为无理数，$I$为区间[0, 1]中包含的某个长度为$h$的区间。到无限序列$\alpha + \beta, 2\alpha + \beta, \dots, n\alpha + \beta, \dots$的距离。 The probability that any given number in this sequence has a fractional part belonging to the interval $I$ is equal to $h$.

首先，请注意，如果$l$是十的幂，那么$l$的所有幂都以数字$1$开头，即在这种情况下问题是微不足道的。

If $l$ is not a power of ten, then the number $\alpha = \lg l$ is the difference.根据分数部分定理，序列 $n \lg l - \lg q$ ($n = 1, 2, \dots$) 中的任意数字具有属于区间 $$\left[0, \lg \frac{q+1}{q}\right],$$ 的小数部分的概率等于 $$\lg \frac{q+1}{q}.$$ 这给出了上述问题的解决方案：任意全局数字 $l$（不是 10 的幂）以数字 $q$ 开头的概率，等于$$\lg \frac{q+1}{q}.$$

请注意，该概率与 $l!$ 无关。例如，二的幂和三的幂同样经常（即概率为 lg 2）以数字 1 开头。

3 个阿达奇和

6. 证明如果自然数$l$不是10的幂，那么数字$\lg l$是可以玩的。

7. 计算问题 4 中给出的概率 $p_2, \dots, p_9$。给出其中包含的等式的新证明。

8. 任意 2 的幂以数字 1000 (图 3) 开头的概率是多少？

图 3.

9. $l$（不是十的幂）的任意幂以数字组合$q_1 q_2 \dots q_r$（其中$q_1 \neq 0$）开头的概率是多少？由此推断，数字$l$的幂可以以数字$q_1 q_2 \dots q_r$（$q_1 \neq 0$）的组合开始。

10. 证明下列命题：

a) $l$ 的任意幂（不是 10 的幂）第二位为 0 的概率等于

$$p_0^{(2)} = \lg(11 \cdot 21 \cdot 31 \cdot \dots \cdot 91) - \lg(9!) - 9.$$

提示：$p_0^{(2)}$ 是$l$ 的任意幂以组合 10, 20, ..., 90 开始的概率之和。

6) 对于 $l$ 的任意幂（不是 10 的幂），第 $k$（左起）数字为 $q$（其中 $k > 1$、$q = 0, 1, \dots, 9$）的概率为：

$$p_k^{(2)} = \sum_{i=10}^{k-1} \lg \left(1 + \frac{1}{q+10i}\right).$$

11*。利用问题10、6)的结果，证明$\lim_{k \to \infty} p_k^{(2)} = 1/10$。因此，对于足够大的 $k$，每个小角度的概率 $p_k^{(2)}, p_1^{(2)}, \dots, p_9^{(2)}$ 都不同于 1/10。

⟦folio 6⟧

第二级数项，即它们的差值小于 0.000001 的模型？

16. 我们将所有半径为 $\varepsilon$ 的圆的并集称为欢乐森林，圆心是具有整数坐标的点。证明如果一条直线与x轴形成角度$\varphi$，且其正切是无理数，那么它必然与森林相交（无论$\varepsilon$；图5有多小）。

定理的证明

现在让我们继续证明小数部分定理。

让我们取一个任意自然数$r$。点$\frac{1}{r}, \frac{2}{r}, \dots, \frac{r-1}{r}$将线段$[0, 1]$分割成长度为$\frac{1}{r}$的$r$线段。我们将这些片段称为“细胞”，并将数字 $\alpha, 2\alpha, \dots, (r+1)\alpha$ 的小数部分称为“野兔”*）。由于有$r$“细胞”和$r+1$“野兔”，那么就有两只“野兔”落入一个细胞，即存在自然的$p'$和$p''$（$p' > p''$），使得数字$p' \alpha$和$p'' \alpha$的小数部分相差小于$\frac{1}{r}$。这意味着 $|(p' \alpha - p'' \alpha) - m| < \frac{1}{r}$ 对于某个整数 $m$。 By putting $p = p' - p''$, we can write: $|p \alpha - m| = \varepsilon$, where $\varepsilon < \frac{1}{r}$. Note that $\varepsilon \neq 0$, since $\alpha$ is irrational. Let us denote by $s$ the smallest natural number greater than $\frac{1}{\varepsilon}$, i.e. $s - 1 \leqslant \frac{1}{\varepsilon} < s$.

考虑等差数列的 $s$ 连续项，差值 $p \alpha$：

$$\gamma + p \alpha, \gamma + 2p \alpha, \dots, \gamma + sp \alpha,$$

(3) 其中 $\gamma$ 是某个实数。让我们用 $x_1, x_2, \dots, x_s$ 表示数字 (3) 的小数部分。由于等式 $|p \alpha - m| = \varepsilon$，数字 $x_1, x_2, \dots, x_s$ 彼此间隔 $\varepsilon$ (图 6)。由于不等式$\frac{1}{s} < \varepsilon \leqslant \frac{1}{s-1}$，点之间的距离$x_1$

*) 该术语与狄利克雷原理相关 («Kvant», 1977, No. 2, p. 17)。分数部分定理可以称为“无限数量野兔的狄利克雷原理”。

图 6.

并且$x_s$是图6，比$\varepsilon$小6。由上可知，落在长度为$h$的线段$l$上的点$x_1, x_2, \dots, x_s$的数量包含在数字$\frac{h}{\varepsilon} - 1$和$\frac{h}{\varepsilon} + 2$之间，即$sh-2$和$sh+2$之间（注意$h < 1$）。

现在让我们取一些等差数列的$ps$连续项$b_1, b_2, \dots, b_{ps}$，差为$\alpha$（即$b_{i+1} = b_i + \alpha$）。让我们把它们排列成表格；它代表形式(3)的级数。由于行数为$p$，因此所考虑的级数$b_1, b_2, \dots, b_{ps}$的小数部分落在区间$l$中的那些项的数量包含在数字$p (sh-2)$和$p (sh+2)$之间。

最后，令$n$为大于$rps$的任意自然数。将$n$除以$ps$，得到余数，得到$n = lps + q$，其中$l \geqslant r$，$0 \leqslant q < ps$。因此，从数字 $\alpha + \beta, 2\alpha + \beta, \dots, n\alpha + \beta$ 中，我们可以取出 $l$ 乘以 $ps$ 等差数列的连续项，差值 $\alpha$，
