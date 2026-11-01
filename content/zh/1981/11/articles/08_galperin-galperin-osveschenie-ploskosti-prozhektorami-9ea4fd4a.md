---
id: 1981-11-galperin-galperin-osveschenie-ploskosti-prozhektorami-9ea4fd4a
issue: kvant_1981_11
year: 1981
number: "11"
title: 用聚光灯照亮飞机
authors:
  - Гальперин В.
  - Гальперин Г. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 32
page_labels: 28-30
tag: ESJY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7525c2a999aa91f5faa71b630d2142095fffd0837d7e0ec98e264646f9aa4220
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/08_galperin-galperin-osveschenie-ploskosti-prozhektorami-9ea4fd4a.md
source_content_sha256: 68d7dfcd82a8c35d498523f7f6dd46d07ca5d088c5cdd9372582fe989e4adb2a
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

V.加尔佩林，G.加尔佩林

用投影仪覆盖飞机

有趣且困难的���题 M545，其解决方案与本注释相关，在问题的表述和解决方法中是典型的组合几何——处理图形的分区、覆盖、包装问题的几何部分。
让我们回忆一下它的表述：

平面上有 n 个点。需要在这些点放置n个投影仪，每个投影仪照射$\frac{360^\circ}{n}$大小的角度，从而照亮整个平面。证明如果 a) n=3，这对于这些点的任何位置都是可能的； 6)n=4； c) n - 任何自然数（在 a) - c) 投影仪可以旋转的情况下）； d) 现在让投影仪照亮角 $a_1, a_2, \dots, a_n$ ($a_1 + a_2 + \dots + a_n = 360^\circ$) 并排列在一点上，以便它们照亮整个平面。证明可以将*) n 个投影仪中的一个转移到这些点中的每一个，以便整个平面仍然被照亮。

这个问题的历史非常有趣。最简单的特例 6) 是在 1967 年第一届全联盟数学优化会议上提出的。正是在那里，本文的第二位作者遇见了她（当时他还是个学生）。几年后，他发现了更多证据

*) 这意味着投影仪可以平行移动，但不能旋转！

现在让我们考虑相对于点 O 对称的角度。图 2 显示如何引导放置在点 $M_1$ 的投影仪，使其照亮红色阴影的角。类似地，可以对点$M_2$和$M_3$处的投影仪进行定向，以便它们照亮“它们的”角落。

同样的想法——将飞机分成几部分。这样每个投影仪都可以用自己的投影仪组进行照明，这可以应用于情况 c)。

要做到这一点，只需证明以下两个陈述就足够了。

陈述 1. 设 k 个投影仪位于给定角度 $\alpha = k \frac{2\pi}{n}$ 内，其中 $k \leqslant \frac{n}{2}$。然后可以旋转它们，以便它们一起照亮相对于给定顶点（图3）对称的整个角度。

为了通过 k 的表示来证明这个命题，可以方便地使用下面的算术引理。如果$s_1, s_2, \dots, s_k$是非负整数，且$s_1 \geqslant 1$，

图 1.
图 2.

⟦folio 29⟧

$s_k \geq 1$和$s_1 + s_2 + \dots + s_k = k$，则有一个$m < k$，其中$s_1 + \dots + s_m = m$（即$s_{m+1} + \dots + s_k = k - m$）。

最后，仍然需要证明这个相当规律的事实 - 对于偶数和奇数 $n$ 分别进行此操作会更容易。

陈述 2. 如果给定一个平面 $n$ 点 $A_1, A_2, \dots, A_n$，则它可以分为两个半平面，每个半平面包含 $n/2$ 点（如果 $n$ 是偶数），或者分成具有公共顶点和大小为 $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$ 的三个角，其中 $k_1 + k_2 + k_3 = n$ 和 $k_i < n/2$ ($i=1, 2, 3$)，其中每个角包含如果 $n$ 是奇数，则$k_i$ 分。

练习 1. 证明命题 1、引理和命题 2。

之后，根据陈述1，我们用相应的投影仪照射以它们所在的角度相对于公共顶点对称的角，结果整个平面都被照亮了。

改进算法

让我们概述一下解决该点的思路。 G）。让我们以任意方式将投影仪布置在这些点 $M_1, M_2, \dots, M_n$ 处。如果不是整个平面都被照亮，我们将提出另一种“改进”的投影仪布置方法（在这种情况下，布置的“质量”将通过某个数值函数$f$来评估）。由于$M_1, M_2, \dots, M_n$点（等于$n!$）处的投影仪排列数量有限，采用函数$f$值最大的排列，我们会自动照亮整个平面：事实上，如果不是整个平面都被照亮，我们仍然可以“改进”排列，从而得到矛盾。

我们来实施这个计划吧。现在，投影仪是任意角度 $a_i$，具有公共顶点 $O$、$0 < a_i < \pi$、$a_1 + a_2 + \dots + a_n = 2\pi$，并且每个投影仪都照亮某个凸 $n$ 边形 $A_1A_2\dots A_n$ (图 4)、$A_i \overrightarrow{OA_{i+1}} = a_i$ 的一侧。让我们从点 $O$ 到多边形各边（或其延伸线）的垂线 $OH_i$；让$|OH_i| = h_i$。

考虑向量 $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$。显然$|\vec{e}_i| = \frac{1}{h_i}$(图5)。

投影仪在点 $M_1, M_2, \dots, M_n$ 的排列对应于向量 $\vec{e}_1, \vec{e}_2, \dots, \vec{e}_n$ 在这些点的排列（我们似乎将向量 $\vec{e}_i$ 附加到投影仪 $a_i$ 并将它们重新排列在一起作为一个整体）。

乍一看，我们未来需要的唯一几何事实“证明”了向量 $\vec{e}_i$ 的选择，如下：

引理。让放置在点$M$的投影仪$a_p$照亮点$N$，但投影仪$a_q$不照亮。然后$\overrightarrow{MN} \cdot \vec{e}_p > \overrightarrow{MN} \cdot \vec{e}_q$。

证明。让$\overrightarrow{MN} = \vec{v}$。让我们从点 $O$ 绘制向量 $\overrightarrow{OP} = \vec{v}$ (图 6)。射线[OP]与多边形$A_1A_2\dots A_n$的第$p$边相交于$K$，但不与第$q$边相交，投影仪的距离为$s_k \geq 1$和$s_1 + s_2 + \dots + s_k = k$，则存在$m < k$，其中$s_1 + \dots + s_m = m$（即$s_{m+1} + \dots + s_k = k - m$）。

最后，仍然需要证明这个相当规律的事实 - 对于偶数和奇数 $n$ 分别进行此操作会更容易。

陈述 2. 如果给定一个平面 $n$ 点 $A_1, A_2, \dots, A_n$，那么它可以分为两个半平面，每个半平面包含 $n/2$ 点，如果 $n$ 是偶数，或者分成具有公共顶点和大小 $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$ 的三个角，其中 $k_1 + k_2 + k_3 = n$ 和 $k_i < n/2$ ($i=1, 2, 3$)，它们中的每一个都照亮内部某个凸$n$边形$A_1A_2\dots A_n$ (图 4), $A_i \overrightarrow{OA_{i+1}} = a_i$。让我们从点 $O$ 到多边形各边（或其延伸线）的垂直线 $OH_i$；让$|OH_i| = h_i$。

考虑向量 $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$。显然$|\vec{e}_i| = \frac{1}{h_i}$(图5)。

图 6.

投影仪 $a_p$ 照亮点 $N$，但投影仪 $a_q$ 不照亮。

有两种可能性：1) 射线 [OP] 不与第 $q$ 边所在的直线相交，2) 射线 [OP] 在某个点 $R$ 与该直线相交。

在第一种情况下，它非常重要，因为$\vec{v} \cdot \vec{e}_p > 0$和$\vec{v} \cdot \vec{e}_q \leq 0$。

在第二种情况下，它非常重要，因为$\vec{v} \cdot \vec{e}_p > 0$和$\vec{v} \cdot \vec{e}_q \leq 0$。

射线[OP]在某个点$K$与多边形$A_1A_2\dots A_n$的第$p$边相交，但不与第$q$边相交，投影仪的距离为$s_k \geq 1$和$s_1 + s_2 + \dots + s_k = k$，则有$m < k$，因此它们被$n/2$点照亮，如果$n$ 是偶数，或者分成具有共同顶点和大小 $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$ 的三个角，其中 $k_1 + k_2 + k_3 = n$ 和 $k_i < n/2$ ($i=1, 2, 3$)，它们中的每一个都照亮某个凸面 $n$ 边形 $A_1A_2\dots A_n$ (图 4)、$A_i \overrightarrow{OA_{i+1}} = a_i$。让我们从点 $O$ 到多边形各边（或其延伸线）的垂直线 $OH_i$；让$|OH_i| = h_i$。

考虑向量 $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$。显然$|\vec{e}_i| = \frac{1}{h_i}$(图5)。

⟦folio 30⟧

现在让我们根据平面上的点$N$以及点$M_1, M_2, \dots, M_n$处投影仪的排列$\sigma$来介绍数量$f_{\sigma}(N)$，如下：

$$f_{\sigma}(N) = \overrightarrow{M_1} N \cdot \overrightarrow{e_{\sigma(1)}} + \overrightarrow{M_2} N \cdot \overrightarrow{e_{\sigma(2)}} + \dots + \overrightarrow{M_n} N \cdot \overrightarrow{e_{\sigma(n)}}$$

(1) ($\sigma(i)$是放置在$M_i$点的投影机的编号)。

下面的主要陈述表明，函数$f_{\sigma}(N)$可以表征排列的“质量”。

陈述3.如果排列$\sigma$中的点$N$没有被照亮，则存在投影仪m的排列使得$f_{\tau}(N) > f_{\sigma}(N)$。

证明。让我们首先提出一个算法，允许我们“改进”排列$\sigma$。

让投影仪$\alpha_i$位于点$M_i$。让投影仪$\alpha_1$站在$M_1$点，不照射点$N$。让我们把它移开一段时间，在$M_1$点我们将穿过投影仪，然后投影仪将重新照亮点$N$。

练习 2. 证明这样的投影仪存在。

让它成为投影仪$\alpha_2$。现在，在投影仪$\alpha_2$所在的点$M_2$，什么也没有。让我们将剩余的投影仪 $n-1$ 之一放置在此处，它将照亮点 $N$。让它成为投影仪$\alpha_3$。现在让我们将投影仪 $\alpha_4$ 放置在点 $M_3$ 处，然后将被 $N$ 照亮，在点 $M_4$ 处放置投影仪 $\alpha_5$ 等等，直到形成一个循环（图 7）：这意味着在点 $M_k$ 处投影仪 $\alpha_{k+1}$ 相交，指向$M_{k+1}$ - 投影仪$\alpha_{k+2}$，指向$s$ - 投影仪$\alpha_k$ ($s > k$)。我们将把投影仪 $\alpha_1, \alpha_2, \dots, \alpha_{k-1}$ 返回到原来的位置（具有相同编号的点）。结果，点$N$将被每个投影仪$\alpha_k, \alpha_{k+1}, \dots, \alpha_s$照亮（因为点$N$没有被照亮，$s \geq k+1$）。

让我们看看数字$f(N)$发生了怎样的变化。和(1)中除$k, k+1, \dots, s$以外的数字的项没有改变。从引理可以看出，所有带有数字 $k, k+1, \dots, s$ 的项在指定的重新排列后都增加了。

因此，命题3得证。确实，$f_{\sigma}$的值还不能直接用来评估排列$\sigma$的“质量”——毕竟，它取决于点$N$。这就是奇妙之处。

陈述4.对于任意两点$N_1$和$N_2$，差值$f_{\sigma}(N_1) - f_{\sigma}(N_2)$不依赖于投影仪的布置。

证明。 $f_{\sigma}(N_1) - f_{\sigma}(N_2) = \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_1 \cdot \overrightarrow{e_{\sigma(i)}} - \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_2 \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} (\overrightarrow{M_{\sigma(i)}} N_1 - \overrightarrow{M_{\sigma(i)}} N_2) \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} \overrightarrow{N_2} N_1 \cdot \overrightarrow{e_{\sigma(i)}} = c$。

和$\sum_{i=1}^{n} \overrightarrow{e_{\sigma(i)}}$是一个常数向量（不依赖于排列），$N_2 N_1$也是一个固定向量，因此$c$数不依赖于投影仪的排列，这是需要证明的。

这意味着函数$f_{\sigma}(N)$可以用函数$f_{\sigma} = f_{\sigma}(N) + \overrightarrow{N_0} \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_0 \cdot \overrightarrow{e_{\sigma(i)}}$代替，其中$N_0$是平面上的任意固定点。

数字$f_{\sigma}$不再依赖于点$N$，并且会随着我们描述的每个排列而增加。

这个想法因此得到了充分实现：发现了一种仅取决于投影仪布置的“质量函数”，并且展示了如果某个点没有被照亮，如何增加其价值。由于在某些排列$\omega$中，数字$f_{\omega}$是最大的，因此在排列$\omega$中，整个平面都被照亮。

练习 3. 证明投影仪问题的空间变体。

a) 在空间中的任意 8 个点，您可以放置​​边线（具有直角平角的三面角（参见 图 8，a）），以便它们覆盖整个空间。

b) 在空间中给出一个凸多面体，其面为$\Gamma_1, \Gamma_2, \dots, \Gamma_n$，其内部有一个点$O$，以及$n$点$M_1, M_2, \dots, M_n$。每个面 $\Gamma_i$ 定义一个顶点为 $O$ 的多面角 $\alpha_i$。在$O$点有$n$投影仪，第$i$投影仪$1 \leq i \leq n$照亮多面角$\alpha_i$（从而整个空间被完全照亮（图8，b））。证明投影仪可以移动到点$M_1, M_2, \dots, M_n$，使得整个空间仍然被照亮。
