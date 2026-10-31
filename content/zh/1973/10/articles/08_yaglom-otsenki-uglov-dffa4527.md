---
id: 1973-10-yaglom-otsenki-uglov-dffa4527
issue: kvant_1973_10
year: 1973
number: "10"
title: 角度估计
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 32
page_last: 36
page_labels: 30, 31, 32, 34
tag: PB76
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7297d8b18bbaa64a8e991c7cb20a8b0bb4dddabbe479a5231290280eb0847b01
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/08_yaglom-otsenki-uglov-dffa4527.md
source_content_sha256: a8b0d3a1ad58c0cdc98227e272e685ad6c9e72ec356455b91731866c3eb25b89
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

I. M. Yaelom 角度估计

我们的起点将是以下非空但值得尊敬的问题 1. 令 $A, B, C$ 为平面上的三个任意（不重合）点；我们用$\alpha$、$\beta$和$\gamma$表示三角形$ABC$（moche、$\angle BAC, \angle ABC$和$\angle ACB$）的元素。让$\alpha \geq \gamma \geq \beta$。 $\alpha$、$\gamma$、$\beta$ 有何含义？

这个问题很好地说明了本文的主题：它讨论了以下内容（一般来说，尚未解决！）

主要问题。在数据平面上$n$点$A_1, A_2, \dots, A_n$。让我们用 $\alpha_1, \alpha_2, \dots, \alpha_N$ 表示这些点形成的三角形的角度 *)。让$\alpha_1 \geq \alpha_2 \geq \dots \geq \alpha_N$。我的$\alpha_1, \alpha_2, \dots, \alpha_N$应该有什么含义？

想象一下在解决主要问题时我们可能会遇到什么，让我们解决问题1。

问题1的解决方案

由于$\alpha + \beta + \gamma = 180^\circ = 3 \cdot 60^\circ$，那么三角形的三个角中的大多数不能小于$60^\circ$，并且

*) 当然，数字$N$取决于$n$。不难看出

$$N = 3C_n^3 = 3 \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3} = \frac{n(n-1)(n-2)}{2},$$

其中$C_n^3$是$n$乘以3的组合数，但我们不需要这个公式。

⟦folio 31⟧

如果我们需要尖锐，那么$\gamma < 90^\circ$（三个点位于同一条线上的情况将无法挽救情况，因为在这种情况下$\alpha = 180^\circ$，$\beta = 0^\circ$，$\gamma = 0^\circ$）。然而，$\gamma$可以尽可能接近$90^\circ$（在图3处，最小角度$\beta = \angle BAC$非常小，并且$\angle ABC = \angle ACB \approx 90^\circ$）。因此，

$$60^\circ \leq \alpha \leq 180^\circ, \quad 0^\circ \leq \gamma < 90^\circ, \quad 0^\circ \leq \beta \leq 60^\circ.$$

为了验证问题1*的解决方案，我们仍然需要证明$\alpha$可以在$60^\circ \leq \alpha \leq 180^\circ$内取更多的值（对于角度$\beta$和$\gamma$也是如此）。然而，这部分解决方案非常简单 - 它与三角形$ABC$的构造一致，其中最大角度$\alpha$（或“平均”角度$\gamma$，或最小角度$\beta$）具有在指定限制内​​选择的给定值；您可以自己轻松完成此操作。

问题1解决方案的讨论

首先，让我们改变一下符号。条件是用 $A_1, A_2, A_3$ 表示三角形的顶点，用 $\alpha_1, \alpha_2, \alpha_3$ 表示三角形的角。最大的角度 $\alpha_1, \alpha_2, \alpha_3$ 可以表示如下：

$$\alpha = \max_i \alpha_i,$$

最小的角$\alpha_1, \alpha_2, \alpha_3$是这样的：

$$\beta = \min_i \alpha_i,$$

和$i = 1, 2, 3.$

max是拉丁词*maximum*的缩写——“最大”，即最大的。符号 $i$ under.max 表明 $i$ 正在变化，也就是说，给出了一组值$\alpha_i$（此处为 - $\alpha_1, \alpha_2, \alpha_3$），我们取其中最大的值（而不是，比如说，三角形 $A_1A_2A_3$ 中通常可能的角度中最大的一个 - in

*) 我们在这里提出问题 1 的详细解决方案。解决其他问题的说明位于杂志末尾（但不要看那里 - 首先尝试自己解决问题）。星号标志着更困难的任务；问题编号旁边的简单符号将表明作者不知道解决方案（这并不意味着这个问题很困难；也请考虑一下这个问题）。

在这种情况下，我们将写 max $\alpha$。 Zakmak max $\Delta A_1A_2A_3$ 通常用于有限数中的最大值（此处为三个）。对于无限数量中的最大数量，也可以使用max符号，但这很危险——这里还需要证明这个最大数量存在（见下文）。

min 是拉丁词 *minimum* 的缩写 - “最小”，即最大。

在问题1中，我毫无困难地确定了最大可能值$\alpha$，即

$$\max \alpha = \max \max \alpha_i = 180^\circ,$$

$$\Delta A_1A_2A_3 \quad \Delta A_1A_2A_3 \quad i$$

和最小可能值$\beta$，即

$$\min \beta = \min \min \alpha_i = 0^\circ.$$

这里最有趣的是 $\alpha$ 的最小可能值，即

$$\min \alpha = \min \max \alpha_i = 60^\circ,$$

$$\Delta A_1A_2A_3 \quad \Delta A_1A_2A_3 \quad i$$

这种“极小极大”问题的表述对于现代“纯”数学和（尤其是！）应用数学来说是典型的。

问题 1 的一个重要部分还包括估计 $\gamma$ 的最大可能值（最小的值很容易找到：从 图 2 可以得出最小值 $\gamma = 0^\circ$）。然而，我们在这里感到羞耻：事实证明，所需的最大值$\gamma$不存在：角度$\gamma$可以与$90^\circ$一样接近，但它永远不会等于$90^\circ$。然后数学家说 $90^\circ$ 是 $\gamma$ 的（mon）上界：

$$\sup \gamma = 90^\circ.$$

susup 是拉丁语 *supremum* 的缩写 - “supremum”，即更高。符号sup$x_i = \xi$表示$x_i \leq \xi$对于任何$i$，但$x_i$可以是任何角度

⟦folio 32⟧

接近于 Ψ，即 Ψ 是最小数，不小于任意$x_i$。可以证明，如果数量$x_i$由上有界，即数量至少有一个上限，则这些上限中存在一个最小的（一），即存在sup$x_i$。

符号 inf $x_i$ 的使用方式类似。 Inf是拉丁语infimum的缩写——“infimum”，即较低。

inf $x_i$ 是一个强大的低沿，即不超过任何$x_i$的最大数。在不造成阅读困难的情况下，我们不会在sup、inf、max、min等符号下写$i$、$\Delta A_1 A_2 A_3$等。

不难理解这个 sorpiriz 与什么有关。很明显，max $\alpha_i$ 和 min $\alpha_i$ 存在 - 毕竟，从 $\alpha_1$、$\alpha_2$ 和 $\alpha_3$ 三个角度，人们总是可以选择最大和最小。并且平面上的轨迹$\{A_1, A_2, A_3\}$点的数量是无限的。而这里我们不能再保证一定会有一条轨迹对应角度$\gamma$的最大值。毕竟，我们可以根据需要多次从一个点轨迹移动到另一个点轨迹，这对应于更大的角度$\gamma$值，并且每次都可能发现仍然存在比前一个轨迹更好的轨迹。

原则上，sup $\alpha$、sup $\beta$、sup $\gamma$、inf $\alpha$、inf $\beta$、inf $\gamma$ 都不是足够必要的 - 我们应该将值sup $\alpha = 180^\circ$、sup $\beta = 60^\circ$、inf $\alpha = 60^\circ$ 和 inf 视为幸运达到$\beta = 0^\circ$，即存在最大$\alpha$、最大$\beta$、最小$\alpha$和最小$\beta$。对于值 $\gamma$，正如我们所见，inf $\gamma = 0^\circ$ 已实现，但sup $\gamma = 90^\circ$ 未实现。

类似地，对于数量 $\frac{1}{n}$，其中 $n$ 是自然数，sup $\frac{1}{n} = 1$ 可以实现（在 $n = 1$ 处），但 inf $\frac{1}{n} = 0$ 则不能；因此，数量$\frac{1}{n}$有一个最大值而没有最小值。

最后让我们考虑一下$\alpha$、$\beta$和$\gamma$的最大或最小值在$P_3 = \{A_1, A_2, A_3\}$（或$\{A, B, C\}$）点的哪个具体轨迹上实现的问题。很容易看出，对于单个三重点，即正三角形$ABC$（参见图 1）的顶点，可以实现最小$\alpha$和（同时）最大$\beta$，当然，直到用类似的三角形替换三角形$ABC$，但这不会改变其任何角度。正如我们所知，max $\gamma$ 根本不存在。并且值 max $\alpha$、min $\beta$ 和 min $\gamma$ 是通过无数个不同（进一步不相似）的点三元组实现的，因为 图 2 上的中点可以位于连接其他两个点的线段上的任何位置。

现在我们将继续执行其他任务。

任务 2. a) 令 $P_4 = \{A, B, C, D\}$ 为平面上任意四点系统；我们将 empirim 和 mochikas 定义的 12 个角度中最小的角度值表示为 $\beta$。证明$0^\circ \leq \beta \leq 45^\circ$。

b) 令$P_5$为平面上任意四点系统；我们用 $\beta$ 表示经验角和 mochikas 定义的最小角。证明$0^\circ \leq \beta \leq 36^\circ$。

c) 令$P_6$为平面上任意四点系统；我们用 $\beta$ 表示经验角和 mochikas 定义的最小角。证明$0^\circ \leq \beta \leq 30^\circ$。

对于平面上的哪些四点、跟点和六点系统，所达到的角度$\beta$的最大和最小值？

开始解决问题 2. 假设所考虑的点已被埋入地下

⟦folio 34⟧

这个结果与 7 点系统相同（也许这里 inf α = 120°，u min α 也不存在）。

让我们再次转向主问题中出现的平面上$n$点的“一般”系统$P_n = \{A_1, A_2, \dots, A_n\}$；我们用 $\alpha$ 表示这些点定义的最多角度，用 $\beta$ 表示最多。显然，由于 $\alpha$ 最可能的值等于 180°，而 $\beta$ 最可能的值是 0°，那么估计角度 $\alpha$ 和 $\beta$ 的任务就是找到 sûр $\beta$（我们用 $\beta$ 或平面表示该值；当然，它取决于$n$，- 由 $\beta(n)$) 和 inf $\alpha$（我们用 $\alpha$ 或 $\alpha(n)$ 表示该值）。求$\beta(n)$的几个值：

$$\beta(n) = \frac{180^\circ}{n},$$

并且这个值总是可以实现的（参见问题3）。然而，求值$\alpha(n)$的问题并不是那么简单，尚未以通用形式得到解决。问题 4 和 5 表明 $\alpha(4) = 90^\circ$、$\alpha(5) = 108^\circ$ 和 $\alpha(6) = \alpha(7) = \alpha(8) = 120^\circ$；在这种情况下，已经实现了值$\alpha(4), \alpha(5)$和$\alpha(6)$，但尚未实现值$\alpha(7)$和$\alpha(8)$。

确定$\alpha(n)$值的问题首先由美国几何学家L.布卢门撒尔提出；它的解决方案是由匈牙利数学家 P. Erdős*) 和 G. Szekeres 完成的。 P. Erdős 提出，对于所有 $n \geq 6$ $\alpha(n) = \frac{k-1}{k} \cdot 180^\circ$，其中 $2^{k-1} \leq n \leq 2^k$，并且只有 $n = 6$ 才能实现该值 $\alpha(n)$。然而，到目前为止才被证明

$$\alpha(2^k) = \frac{k-1}{k} \cdot 180^\circ$$ $k \geq 2$

*) Pál Erdős 是一位著名的现代匈牙利数学家。埃尔多什在数学各个领域（数论、数学分析、概率论、几何等）拥有许多引人注目的成果；由于他的活动，迄今未解决的问题数量只增不减，但他提出的新问题多于他解决的旧问题。

如果$2^{k-1} < n < 2^k$（其中$k \geq 3$），那么$\frac{k-1}{k} \cdot 180^\circ \geq \alpha(n) > \frac{k-2}{k-1} \cdot 180^\circ$（后者的估计甚至可以稍微加强）。

现在让我们转向该问题所涉及的其余角度。

问题6.设$P_4$为平面上任意四点系统； $\alpha = \alpha^{(1)}$和$\alpha^{(2)}$是这些点指定的九个角度中最大的两个，$a = \beta = \beta^{(1)}$和$\beta^{(2)}$是两个最小的角度；同时$\alpha^{(1)} \geq \alpha^{(2)}$，$\beta^{(1)} \leq \beta^{(2)}$。证明

a) $72^\circ \leq \alpha^{(2)} \leq 180^\circ$;
b) $0^\circ \leq \beta^{(2)} \leq 45^\circ$.

$\alpha^{(2)}$和$\beta^{(2)}$的最大和最小值是在哪些点系中实现的？

问题 7. 证明对于所有 $n \geq 2$ max $\alpha(i) = 180^\circ$ 对于 $1 \leq i \leq \frac{n(n-1)(n-2)}{6}$，

$$u \min \alpha^{(i)} = 0^\circ$$ $P_n$

$$\frac{n(n-1)(n-2)}{6} < j \leq N = \frac{n(n-1)(n-2)}{2}$$

因此，所有$N$角度$\alpha^{(i)}$的估计问题表明了值inf$\alpha^{(i)}$的确定，其中

$$1 \leq i \leq \frac{n(n-1)(n-2)}{6}$$

（inf $\alpha^{(i)}$ 可以用符号 $\alpha^{(i)}(n)$ 表示）和sup $\beta^{(i)}$ 当

$$1 \leq j \leq \frac{n(n-1)(n-2)}{3}$$

*) 请注意$\frac{n(n-1)(n-2)}{6} + \frac{n(n-1)(n-2)}{3} = \frac{n(n-1)(n-2)}{2} = N$。我们还要指出，待确定的数量$\beta^{(i)}$总是从属间数量$\alpha^{(i)}$的两倍，例如：$n = 3$为2和1，$n = 4$为8和4，等等。
