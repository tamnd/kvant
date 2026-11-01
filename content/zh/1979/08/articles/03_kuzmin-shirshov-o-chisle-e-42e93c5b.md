---
id: 1979-8-kuzmin-shirshov-o-chisle-e-42e93c5b
issue: kvant_1979_8
year: 1979
number: "8"
title: 关于数字 e
authors:
  - Кузьмин Е. Н.
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 5
page_last: 10
page_labels: 3, 4, 6, 7, 8
tag: 9KKE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 85e626c4574bb5a17196a39d64843e5599727582622af618705c1f2f13c00282
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/03_kuzmin-shirshov-o-chisle-e-42e93c5b.md
source_content_sha256: 1f0814c7955b733281e991b0fb138da56f98c980f31e0857d49fe5f443a6ba38
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 3⟧

关于数字 e

1. e是什么？

在学校，早在五年级的时候，你就会接触到数字π，它有着非常悠久的历史，它的起源已经在古代世界的时间迷雾中消失了*)。然后你在八年级、九年级、十年级时遇到了他。你只有在十年级结束时才会遇到数字 e。然而，这个非凡的数字随着数学分析的发展在18世纪开始使用，在现代数学中扮演着几乎更重要的角色。

在教科书中，数字 e 给出了两种定义。在第二个（我们不需要第一个）中，数字 e 是序列 $x_n = \left(1 + \frac{1}{n}\right)^n$ 的极限。让我们证明这个极限是存在的。

引理 1. 对于任意 m, n

$$\left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{m}\right)^{m+1}.$$

(1)

使用著名的柯西不等式很容易证明不等式（1）：

$$\sqrt[n]{a_1 \cdot a_2 \cdot \dots \cdot a_n} < \frac{a_1 + a_2 + \dots + a_n}{n},$$

(2)

其中$a_1, a_2, \dots, a_n$为正数，其中存在不同的数**）。来自 (2)

$$\sqrt[n]{1 + \frac{1}{n}} \left(1 - \frac{1}{m+1}\right)^{m+1} < \frac{n \left(1 + \frac{1}{n}\right) + (m+1) \left(1 - \frac{1}{m+1}\right)}{m+n+1} = 1,$$

从何而来 $$\left(1 + \frac{1}{n}\right)^n \left(1 - \frac{1}{m+1}\right)^{m+1} < 1$$ 和 $$\left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{m}\right)^{m+1}.$$

引理 2. 序列 $(x_n)$ 递增。

证明。让我们用 $y_n$ 表示 $\left(1 + \frac{1}{n}\right)^n+1$。根据引理1，$x_{n(n+2)} < y_{n+1}$，即

$$\left(1 + \frac{1}{n(n+2)}\right)^{n(n+2)} < \left(1 + \frac{1}{n+1}\right)^{n+2}.$$

*) 关于数字 π 的许多有趣的细节可以在 F. Kymen 的书和“数字 π 的历史”（M.，“Nauka”，1971）中找到。另请参阅 A. Zvonkin 的文章“什么是 π？” （«Kvant»，1978 年，第 11 期）。

**）尝试自己证明这一点。您还可以阅读他在第 14 页上的证明。 26.

⟦folio 4⟧

方法，

$$\left(1 + \frac{1}{n(n+2)}\right)^n < 1 + \frac{1}{n+1}.$$

因此，$$\left(1 + \frac{1}{n(n+2)}\right)^n = \frac{(n+1)^2n}{n^n(n+2)^n} < \frac{n+2}{n+1}.$$

因此 $$\left(\frac{n+1}{n}\right)^n < \left(\frac{n+2}{n+1}\right)^{n+1}$$ 或 $$x_n < x_{n+1}.$$

根据引理 1、2 和 Weierstrass 定理，可以得出序列 $(x_n)$ 有极限。该极限的符号 $e$ 由 L. Euler (1707–1783) 引入。

锻炼。证明 $$\lim_{n \to \infty} y_n = e$$ 以及任意 $m, n$

$$x_n < e < y_m.$$

数字$e$也可以定义为序列$s_n = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{n!}$的极限。让我们证明一下。根据牛顿公式

$$x_n = 1 + n \cdot \frac{1}{n} + \frac{n(n-1)}{2!} \cdot \frac{1}{n^2} + \dots + \frac{n(n-1) \cdot \dots \cdot (n-k+1)}{k!} \cdot \frac{1}{n^k} + \dots + \frac{1}{n^n} = 1 + 1 + \frac{1}{2!} \left(1 - \frac{1}{n}\right) + \dots + \frac{1}{k!} \left(1 - \frac{1}{n}\right) \times \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{k-1}{n}\right) \times \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{n-1}{n}\right).$$

（从（3）也可以清楚地看出序列$(x_n)$正在增加。）通过消除括号中的因子，我们将增加等式（4）右侧的每一项。因此，$x_n < s_n$（在$n > 1$）。

我们现在修复任意 $k > 1$。假设$n > k$，我们丢弃等式（3）右侧的所有项，从$(k+2)$开始。我们得到

$$x_n > 1 + 1 + \frac{1}{2!} \left(1 - \frac{1}{n}\right) + \dots + \frac{1}{k!} \left(1 - \frac{1}{n}\right) \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{k-1}{n}\right).$$

对于$n \to \infty$（和固定的$k$），不等式（4）的右侧趋于$s_k$。传递到不等式（4）的极限，我们得到$e \geqslant s_k$。所以，$x_n < s_n \leqslant e$。从$$\lim_{n \to \infty} x_n = e$$我们得到$$\lim_{n \to \infty} s_n = e.$$因此，

$$e = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{n!} + \dots.$$

使用序列$(s_n)$来计算数字$e$的近似值比序列$(x_n)$方便得多。我们来估计一下差异 $e - s_n$。来自 (5)

$$e - s_n = \frac{1}{(n+1)!} + \frac{1}{(n+2)!} + \dots =$$

$$= \frac{1}{(n+1)!} \left[ 1 + \frac{1}{n+2} + \frac{1}{(n+2)(n+3)} + \dots \right] <$$

$$< \frac{1}{(n+1)!} \left[ 1 + \frac{1}{n+2} + \frac{1}{(n+2)^2} + \dots \right] =$$

$$= \frac{1}{(n+1)!} \cdot \frac{1}{1 - \frac{1}{n+2}} = \frac{n+2}{(n+1)^2 \cdot n!} < \frac{1}{n \cdot n!}.$$

⟦folio none⟧

得到的结果可以写成等式

$$e = s_n + \frac{\theta_n}{n \cdot n!} \quad (0 < \theta_n < 1).$$

由(6)很容易得出$e$数的无理数。事实上，假设$e = \frac{p}{q}$。那么$q!e$是一个整数。从 (6) $n=a$ 开始

$$q!e = q! + q! + \frac{q!}{2!} + \dots + \frac{q!}{q!} + \frac{\theta_q}{q}.$$

结果发现$\frac{\theta_q}{q}$是一个整数，这显然是错误的。这是数字 $e$ 的第一位小数。

$$e = 2,718281828459045\dots$$

2. 关于分区的问题

数字$e$是数学分析和函数论的宠儿，在一些组合问题中却出人意料地出现。让我们考虑一个这样的问题。

让我们从一个例子开始。二元素集$\{a_1, a_2\}$可以通过两种方式划分为不相交的子集（当谈到划分时，它们被称为类）：这是“逐地”划分$\{a_1\}, \{a_2\}$和退化“整数”划分$\{a_1, a_2\}$。对于任何 $n$ 元素集，都存在类似的分区（对于 $n>2$）。在 $n=3$ 处，又添加了三个分区 (图 1)。

让我们表示由$\tau(n)$ *）设置的$n$元素的分区号。

显然$\tau(0) = \tau(1) = 1$。正如我们刚才提到的，$\tau(2) = 2$，$\tau(3) = 5$。对于任意 $n$，$\tau(n)$ 等于多少？能否给出一些简单的$\tau(n)$公式？

正如组合问题中常见的情况，很容易找到将 $\tau(n)$ 与 $k < n$ 的值$\tau(k)$ 相关的递推关系。

让$M = \{a_1, a_2, \dots, a_n\}$。让我们根据元素 $a_1$ 属于给定分区的类的元素数量 $k$ 对集合 $M$ 的所有分区进行排序。数字$k$可以等于1,2,...,$n$。对于固定的$k$，这样的分区数量显然等于$C_{n-1}^{k-1}\tau(n-k)$。

因此，$\tau(n) = \sum_{k=1}^{n} C_{n-1}^{k-1}\tau(n-k)$。很容易检查

$$\sum_{k=1}^{n} C_{n-1}^{k-1}\tau(n-k) = \sum_{k=0}^{n-1} C_{n-1}^{k-1}\tau(k).$$

当然，

$$\tau(n) = \sum_{k=0}^{n-1} C_{n-1}^{k-1}\tau(k).$$

利用公式（7），很容易计算出$\tau(4)=15$、$\tau(5)=52$、$\tau(6)=203$、$\tau(7)=877$、$\tau(8)=4140$——随着$n$的增加，$\tau(n)$的数量也迅速增加。

*) 数字$\tau(n)$称为贝尔数（«Kvant»，1978年，第7号）。

⟦folio 6⟧

我们将使用递归公式（7）来证明一个最喜欢的语句，其中需要检查数字$e$：

$$e \cdot \tau(n) = \frac{1^n}{1!} + \frac{2^n}{2!} + \dots + \frac{k^n}{k!} + \dots \quad (n \geqslant 1)$$

证明。让我们使用数学归纳法。对于 $n=1$，由于 (5)，(8) 为真。现在让我们假设 (8) 对于所有小于某个 $n$ 的数字都成立；让我们证明对于 $n$ 也成立。根据（5）和归纳假设，以下等式成立：

$$e \cdot \tau(0) = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{k!} + \dots$$

$$e \cdot \tau(1) = \frac{1}{1!} + \frac{2}{2!} + \dots + \frac{k}{k!} + \dots$$

$$e \cdot \tau(2) = \frac{1^2}{1!} + \frac{2^2}{2!} + \dots + \frac{k^2}{k!} + \dots$$

$$e \cdot \tau(n-1) = \frac{1^{n-1}}{1!} + \frac{2^{n-1}}{2!} + \dots + \frac{k^{n-1}}{k!} + \dots$$

（自然地，右侧的无限和必须被理解为限制部分和。）让我们将这些等式与对应于 $C_{n-1}^0, C_{n-1}^1, C_{n-1}^2, \dots, C_{n-1}^{n-1}$ 的系数逐项相加。左边根据(7)可得$e \cdot \tau(n)$，右边

$$1 + \frac{\varphi(1)}{1!} + \frac{\varphi(2)}{2!} + \dots + \frac{\varphi(k)}{k!} + \dots$$

其中$\varphi(t) = C_{n-1}^0 + C_{n-1}^1 t + C_{n-1}^2 t^2 + \dots + C_{n-1}^{n-1} t^{n-1} = (1+t)^{n-1}$。

因此，

$$e \cdot \tau(n) = 1 + \frac{2^{n-1}}{1!} + \frac{3^{n-1}}{2!} + \dots + \frac{(k+1)^{n-1}}{k!} + \dots = \frac{1^n}{1!} + \frac{2^n}{2!} + \frac{3^n}{3!} + \dots + \frac{(k+1)^n}{(k+1)!} + \dots$$

Q.E.D.从（8）我们得到一个漂亮的公式

$$\tau(n) = \frac{1}{e} \sum_{k=1}^{\infty} \frac{k^n}{k!}$$

然而，计算 $\tau(n)$ 不方便。下面我们将获得简单（在“非循环”意义上）有限（不通过级数）计算$\tau(n)$的公式。

让我们将给定分区的等级称为它所包含的类的数量。让我们用$c_{n,k}$表示$n$元素集$^*$的秩$k$的分区号。显然，rank只能取值$1,2,\dots,n$；这就是为什么

$$\tau(n) = \sum_{k=1}^{n} c_{n,k}.$$

对于$k>n$，我们设置$c_{n,k}=0$。

对于数$c_{n,k}$，很容易得到递推关系。让$M=\{a_1,a_2,\dots,a_n\}, M'=\{a_2,\dots,a_n\}$。让我们划分集合的分区

$$^*$$

*) 数字 $c_{n,k}$ 称为斯特林数。

⟦folio 7⟧

将等级 $k$ 的属性 $M$ 分为两组：包含单绿集 $\{a_1\}$ 作为分区类的分区，以及不包含该分区类的分区。显然，第一类划分的数量与秩为$k-1$的集合$M'$的划分数量一样多，即$c_{n-1,k-1}$；第二种类型的分区比等级为$k$的集合$M'$的分区多$k$倍（元素$a_1$可以放置在集合$M'$的分区的任何$k$类中），即$k \cdot c_{n-1,k}$。所以，在$n > 1, k > 1$

$$c_{n,k} = c_{n-1,k-1} + k \cdot c_{n-1,k}. \tag{10}$$

让我们证明对于 $n \geqslant 1, k \geqslant 1$

$$c_{n,k} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!}. \tag{11}$$

让我们用 $b_{n,k}$ 表示正确的特定解 (11)。如果$k=1$，则$b_{n,1} = 1 = c_{n,1}$。如果$k > 1$和$n=1$，那么

$$b_{1,k} = \sum_{s=0}^{k-1} \frac{(-1)^s}{s! (k-s-1)!} = \frac{1}{(k-1)!} \sum_{s=0}^{k-1} (-1)^s C_{k-1}^s = \frac{1}{(k-1)!} (1-1)^{k-1} = 0 = c_{1,k}.$$

如果最后有$k > 1$和$n > 1$，那么

$$b_{n,k} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-2} \cdot (k-s)}{s! (k-s-1)!} = k \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-2}}{s! (k-s-1)!} + \sum_{s=0}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2} \cdot s}{s! (k-s-1)!} = k \cdot b_{n-1,k} + \sum_{s=1}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2}}{s! (k-s-1)!} = k \cdot b_{n-1,k} + \sum_{s=0}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2}}{s! (k-s-1)!} = k \cdot b_{n-1,k} + b_{n-1,k-1}.$$

因此，数$c_{n,k}$和$b_{n,k}$满足形式(10)的相同重租关系；此外，它们的“初始值”：$k=1$（和任何$n \geqslant 1$）和$n=1$（和任何$k \geqslant 1$）一致。因此，对于任意 $n \geqslant 1$ 和 $k \geqslant 1$，有 (图 2)、$c_{n,k} = b_{n,k}$。

来自 (9) 和 (11)

$$\tau(n) = \sum_{k=1}^{n} \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!}. \tag{12}$$

让我们用 $t$ 表示 $k-s$；然后$1 \leqslant t \leqslant n$。对于双和 (12) 中的固定 $t$，$s$ 可以在 0 到 $n-t$ 之间变化。收集$t^{n-1}$的系数，利用式(12)将其转化为以下形式

$$\tau(n) = \sum_{t=1}^{n} \left( \sum_{s=0}^{n-t} \frac{(-1)^s}{s!} \right) \frac{t^{n-1}}{(t-1)!}.$$

⟦folio 8⟧

具有明确组合意义的数字$c_{n,k}$出乎意料地出现在涉及多项式的代数问题中。

让我们设置 $x^{(1)} = x, x^{(2)} = x (x-1), x^{(3)} = x (x-1)(x-2)$ 等。多项式 1、$x^{(1)}, x^{(2)}, \dots, x^{(n)}$ 的次数分别为 0、1、2、...、$n$。因此，任何$x$次不高于$n$的多项式都可以唯一地表示为这些多项式的和（带有一些系数）。尤其，

$$x^n = a_{n,1}x^{(1)} + a_{n,2}x^{(2)} + \dots + a_{n,n}x^{(n)}$$

(13)

对于某些数字$a_{n,k}$，$(n \geqslant 1, 1 \leqslant k \leqslant n)$。对于$k > n$，我们输入$a_{n,k} = 0$。结果是$a_{n,k} = c_{n,k}$。让我们证明一下。

在(13)中设置$x = 1$，我们得到$a_{n,1} = 1 = c_{n,1}$。如果$k > 1$和$n = 1$，则$a_{1,k} = 0 = c_{1,k}$。现在让$k > 1$和$n > 1$。

$$x^n = \sum_{k=1}^{n} a_{n,k} x^{(k)} = x \cdot x^{n-1} = x \cdot \sum_{i=1}^{n-1} a_{n-1,i} x^{(i)} = \sum_{i=1}^{n-1} a_{n-1,i} x^{(i)} \left[ (x-i) + i \right] =$$

$$= \sum_{i=1}^{n-1} a_{n-1,i} \left[ x^{(i)} (x-i) + ix^{(i)} \right] = \sum_{i=1}^{n-1} a_{n-1,i} \left[ x^{(i+1)} + ix^{(i)} \right] = \sum_{i=1}^{n-1} a_{n-1,i} x^{(i+1)} +$$

$$+ \sum_{i=1}^{n-1} a_{n-1,i} ix^{(i)}$$

比较$x^{(k)}$处的系数，我们得到$a_{n,k} = a_{n-1,k-1} + k \cdot a_{n-1,k}$。如上所述，对于所有 $n, k$，$a_{n,k} = c_{n,k}$ 是成立的。

法律没有这个规定。证明等式：

$$\tau(n-1) = \sum_{t=0}^{n-1} (-1)^t C_{n-1}^t \tau(n-t).$$
