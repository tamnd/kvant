---
id: 1970-9-bendukidze-sulakvelidze-vyichislenie-summ-26b17740
issue: kvant_1970_9
year: 1970
number: "9"
title: 计算金额
authors:
  - Бендукидзе А. Д.
  - Сулаквелидзе А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 41
page_labels: 37-39
tag: 77RH
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a1772148e29eeceae9ccbd0cdfd8c7a438a24a040be96d75d77ecd5a66c4248c
prompt_sha256: draft-1
translated_from: content/ru/1970/09/articles/07_bendukidze-sulakvelidze-vyichislenie-summ-26b17740.md
source_content_sha256: 73646112a227d2669d3ffd84430f964c665cd991ebf70b40ebe04d5deec31260
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

计算总和

计算总和是数学中最重要和最有趣的问题之一。有多种计算总和的方法。这篇文章谈到了其中的两个。

1. 在数学及其众多应用中，使用特殊符号来缩写总和。这是 Σ - 希腊字母“sigma”的字母。使用 Σ 符号写出总和通常非常方便。让我们来认识一下这个标志。

给出表格的总和
$$a_1 + a_2 + \dots + a_n.$$
该总和的所有项均由一个字母指定，以区分下标的使用。该金额可缩写如下：

$$\sum_{k=1}^{n} a_k.$$
上面写着：“sigma $a_k$、$k$ 从 1 到 $n$ 变化。”对于这样的表示法，我们采用总和的“典型”被加数，在我们的例子中为$a_k^*$，在其前面写上符号Σ并指示变化的极限$k$。例如，记录

$$\sum_{k=1}^{10} k$$
意思是金额
$$1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10,$$
*) $a_k$ 称为和的公项。

和录音
$$\sum_{k=1}^{n} \frac{1}{k(k+1)}$$

- 数量
$$\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \dots + \frac{1}{(n-1)n} + \frac{1}{n(n+1)}$$.

很容易检查符号 Σ 的以下属性：
$$\sum_{k=1}^{n} 1 = n, \quad \sum_{k=1}^{n} ca_k = c \sum_{k=1}^{n} a_k,$$
$$\sum_{k=1}^{n} (a_k + b_k) = \sum_{k=1}^{n} a_k + \sum_{k=1}^{n} b_k.$$

例如，让我们检查第二个属性。

根据定义
$$\sum_{k=1}^{n} ca_k = ca_1 + ca_2 + \dots + ca_n,$$

因此，根据和的众所周知的性质，我们有：
$$\sum_{k=1}^{n} ca_k = c(a_1 + a_2 + \dots + a_n).$$

但括号里的表达无非是
$$\sum_{k=1}^{n} a_k$$
因此
$$\sum_{k=1}^{n} ca_k = c \sum_{k=1}^{n} a_k.$$

⟦folio 38⟧

以类似的方式检查其余两个属性。

2. 让我们考虑计算以下形式的总和的问题

$$\sum_{k=1}^{n} f(k) = f(1) + f(2) + \dots + f(n),$$

其中$f$是在自然级数的线段$[1, n]$上定义的整数参数的已知函数。

如果我们成功地求解自然级数线段$[1, n+1]$上定义的函数$F$，则这个总和很容易计算，对于所有$k, 1 \leq k \leq n$，等式成立

$$f(k) = F(k+1) - F(k).$$

事实上，依次将$k = 1, 2, \dots, n-1, n$代入这个等式，我们得到：

$$f(1) = F(2) - F(1),$$
$$f(2) = F(3) - F(2),$$
$$f(3) = F(4) - F(3),$$

$$f(n-1) = F(n) - F(n-1),$$
$$f(n) = F(n+1) - F(n).$$

添加这些等式，我们得出以下公式：

$$\sum_{k=1}^{n} f(k) = F(n+1) - F(1).$$

因此，如果找到函数$F$，则可以简单地计算和(1)。

我们来说明一下几何级数的公式（3）。

在 图 1 上，我们需要求和 (1)，简单地用 $\Sigma$ 表示，作为垂直线段的长度。 $f(k)$形式的每一项对应于红色线段的长度，等于绿色线段$F(k+1)$和$F(k)$的长度之差。显然，所有红色线段的长度之和等于第一个和最后一个绿色线段的长度之差。

示例 1. 计算总和

$$\frac{1}{1.2} + \frac{1}{2.3} + \frac{1}{3.4} + \dots + \frac{1}{n(n+1)},$$

那是

$$\sum_{k=1}^{n} \frac{1}{k(k+1)}.$$

这里

$$f(k) = \frac{1}{k(k+1)},$$

并且，由于很容易检查，它可以表示为以下差异：

$$f(k) = \frac{1}{k} - \frac{1}{k+1}.$$

因此，如果我们表示

$$F(k) = -\frac{1}{k},$$

那么对于所有自然$k$都满足公式（2）：

$$f(k) = F(k+1) - F(k).$$

应用式(3)，我们容易得到

$$\sum_{k=1}^{n} \frac{1}{k(k+1)} = 1 - \frac{1}{n+1} = \frac{n}{n+1}.$$

示例 2. 求以下等比级数的项之和：

$$q, q^2, q^3, \dots, q^n \quad (q \neq 1).$$

这里$f(k) = q^k$，并且使用等式$q^{k+1} - q^k = q^k(q-1)$，我们可以写

$$q^k = \frac{q^{k+1}}{q-1} - \frac{q^k}{q-1}.$$

由此我们可以看出，我们可以把

$$F(k) = \frac{q^k}{q-1},$$

因此

$$\sum_{k=1}^{n} q^k = \frac{q^{n+1}}{q-1} - \frac{q}{q-1} = \frac{q^{n+1}-q}{q-1}.$$

我们得到了众所周知的公式。

⟦folio 39⟧

示例 3. 计算总和
$$\sum_{k=1}^{n} \sin kx (x \neq 2\pi n).$$
很容易检查
$$\sin kx = \frac{\cos(k-0,5)x - \cos(k+0,5)x}{2\sin 0,5x},$$
那是
$$\sin kx = F(k+1) - F(k),$$
在哪里
$$F(k) = -\frac{\cos(k-0,5)x}{2\sin 0,5x}.$$
现在，根据式（3），经过简单变换我们得到
$$\sum_{k=1}^{n} \sin kx = \frac{\sin 0,5(n+1)x \sin 0,5nx}{2\sin 0,5x}.$$
读者本人确信公式（3）提供了计算总和（1）的有效方法。主要是找到函数$F$。不幸的是，这通常不是一件容易的事，有时甚至是难以克服的。
3. 现在给出两个有限的数字序列
$$u_1, u_2, \dots, u_n,$$
和
$$v_1, v_2, \dots, v_n$$
你需要计算金额
$$\sum_{k=1}^{n} u_k v_k.$$
这里经常有用的一种变换是由被取代的挪威数学家阿贝尔指出的。设 $V_k$ 为序列 (4) 的前 $k$ 项之和，即
$$V_k = \sum_{i=1}^{k} v_i = v_1 + v_2 + \dots + v_k.$$
显然$v_1 = V_1$；如果$k > 1$，那么
$$v_h = V_h - V_{h-1}.$$

因为
$$\sum_{k=1}^{n} u_k v_k = u_1 v_1 + u_2 v_2 + \dots + u_n v_n = u_1 V_1 + u_2 (V_2 - V_1) + \dots + u_n (V_n - V_{n-1})$$
打开括号并将术语按两项分组，我们得到
$$\sum_{k=1}^{n} u_k v_k = (u_1 - u_2) V_1 + (u_2 - u_3) V_2 + \dots + (u_{n-1} - u_n) V_{n-1} + u_n V_n$$
或者最后：
$$\sum_{k=1}^{n} u_k v_k = u_n V_n - \sum_{k=1}^{n-1} (u_{k+1} - u_k) V_k.$$ (5)
该方法的几何解释在 图 2 处给出。$u_k v_k$ 形式的每一项对应于矩形（绿色）的面积。 $(u_{k+1} - u_k) V_n$ 形式的项对应于红色矩形的面积。表达式$u_n V_n$是整个矩形的面积。此后，公式（5）变得非常明显。

示例 4. 计算总和
$$1^2 + 2^2 + \dots + n^2.$$
让我们表示 $S$ 所求的量，并用符号 $\Sigma$ 将其写下来：
$$S = \sum_{k=1}^{n} k^2.$$
