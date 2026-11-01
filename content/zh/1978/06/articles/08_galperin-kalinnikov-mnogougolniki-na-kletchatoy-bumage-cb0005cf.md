---
id: 1978-6-galperin-kalinnikov-mnogougolniki-na-kletchatoy-bumage-cb0005cf
issue: kvant_1978_6
year: 1978
number: "6"
title: 方格纸上的多边形
authors:
  - Гальперин В.
  - Калинников В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 43
page_labels: 38-41
tag: D6II
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7c782b9c8ec00b73711edc265720cf886e02fac4aba980c6ad205abb073398e9
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/08_galperin-kalinnikov-mnogougolniki-na-kletchatoy-bumage-cb0005cf.md
source_content_sha256: 1fa091d5ac66f1ce01abb9d67f51ba5574eb45700b317905e2c1b555b49618cd
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

方格纸上的多边形

是否可以在方格纸上绘制给定形状的多边形，并将其所有顶点放置在网格节点上？一般来说 - 这是不可能的。例如，从正多边形中，只能用这种方式绘制正方形。对于哪些多边形可以近似完成，即通过将顶点放置在与节点的角度有多近的位置？事实证明 - 对于每个人来说。
这篇由学生撰写的笔记展示了为什么以及如何做到这一点。

令$\vec{a}$和$\vec{b}$为非零且非线性向量，$O$为某个点；那么所有这些点的集合$\Pi$

图 1.

图 2.

图 3.

图 4.

⟦folio 39⟧

此外，A. Egorov 的文章证明*)除了三角形、正方形和六边形之外，没有任何正多边形可以写入任何格子中。同样清楚的是，通常，任意形状的预定多边形不能被写入任何格子中。

由于将多边形拟合到晶格中的问题在大多数情况下会导致负面结果，因此很自然地削弱它：要求顶点仅近似落入节点中。让我们给出一个精确的定义：

如果存在一个与其相似的多边形（具有自然相似系数），且每个顶点与晶格节点之一的距离小于 ε（图 5），则该多边形将被 ε 添加到晶格 Π 中。请注意，当 ε = 0 时，获得了上面给出的内切度定义，而对于较大的 ε（大于节点之间的距离），该定义是没有意义的。

如果我们首先假设相似系数是自然的，那么它也将变得毫无意义。通过使该系数足够接近 0，可以将整个多边形收缩到一个晶格点附近。有了自然的相似系数（并且ε足够小），多边形的任意两个顶点显然不能落入同一节点的ε邻域内。

此外，我们会说多边形被清除了

*) «Kvant», 1974, № 12, c. 30.

图 5.

图 6.

⟦folio 40⟧

图 7.

和$\{n\sqrt{3}\}$，其中$m > n$是自然数。那么$(m-n)\sqrt{3}$与整体的差异小于$\frac{1}{N}$，因此小于$\varepsilon$。令$k$等于$m-n$，我们就得到了所需要的。

该定理已被证明，但还有一个更普遍的事实。

基本定理。固定多边形适合任何网格。

请注意，c) ���题 M475 点是该定理的一个特例。

证明。给定一个格子$\Pi$、一个数$\varepsilon > 0$和一个多边形$\Phi$。

让我们证明，在具有自然系数$N$的某种相似性下，多边形$\Phi$进入多边形$\Phi'$，使得所有顶点$\Phi'$与晶格节点的距离小于$\varepsilon$。

考虑多边形的顶点 $A$。让以中心$O$和系数$k$为中心的相似性将点$A$变换为$A_k$和$\overrightarrow{OA} = x_A \overrightarrow{a} + y_A \overrightarrow{b}$，其中$\overrightarrow{a}$和$\overrightarrow{b}$是生成晶格的向量。然后$\overrightarrow{OA}_k = k(x_A \overrightarrow{a} + y_A \overrightarrow{b}) = (kx_A) \overrightarrow{a} + (ky_A) \overrightarrow{b}$。

如果$(kx_A)$和$(ky_A)$每个坐标与整体相差小于$c.\varepsilon$，则满足$A_k$距格子节点（图7）小于$\varepsilon$的条件，其中$c$是与$k$无关的系数：

$$\text{можно, например, взять } c = \frac{1}{2\max(|\overrightarrow{a}|, |\overrightarrow{b}|)}$$

确实，让$\overrightarrow{OF} = \overrightarrow{ma} + \overrightarrow{nb}$。

图 8.

那么如果

$$|m|\overrightarrow{a}| - kx_A|\overrightarrow{a}| \leq \frac{\varepsilon}{2} \text{ и } |n|\overrightarrow{b}| - ky_A|\overrightarrow{b}| < \frac{\varepsilon}{2}, \text{ то } |A_kF| = |A_hF| = |\overrightarrow{OF} - \overrightarrow{OA}_k| = |m\overrightarrow{a} + n\overrightarrow{b} - kx_A\overrightarrow{a} - ky_A\overrightarrow{b}| = |(m - kx_A)\overrightarrow{a}| + (n - ky_A)\overrightarrow{b}| \leq |(m - kx_A)\overrightarrow{a}| + |(n - ky_A)\overrightarrow{b}| + |m\overrightarrow{a}| - kx_A|\overrightarrow{a}| + |n|\overrightarrow{b}| - ky_A|\overrightarrow{b}| < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon.$$

但不等式$|m|\overrightarrow{a}| - kx_A|\overrightarrow{a}| < \frac{\varepsilon}{2}$和$|n|\overrightarrow{b}| - ky_A|\overrightarrow{b}| < \frac{\varepsilon}{2}$等价于不等式$|m - kx_A| < \frac{\varepsilon}{2|a|}$和$|n - ky_A| < \frac{\varepsilon}{2|b|}$。因此，如果$kx_A$和$ky_A$与整数相差小于$\frac{\varepsilon}{2\max(|\overrightarrow{a}|, |\overrightarrow{b}|)}$，则下一个节点$F$为$|A_hF| < \varepsilon$，这就是所需要的。

我们需要多边形 $\Phi'$ 的顶点落入晶格节点的 $\varepsilon$ 邻域内。如果所有数字$Nx_A, Ny_A, Nx_B, Ny_B$，...与整数相差小于$c.\varepsilon$，则每个数字$m\alpha_i$（其中$i = 1, 2, ..., n$）与整数相差小于$\varepsilon$； $\alpha$ 等于 $\sqrt{3}$ 不存在）。克罗内卡定理指出，对于任意长度的集合 $\alpha_1, \alpha_2, ..., \alpha_n$ 以及某个自然数 $m$，数字 $\alpha_i$ 一次与整数的差异不小于 $\varepsilon$。

让我们继续证明克罗内卡定理。

考虑 $n$ 序列：

$$\{\alpha_1\}, \{2\alpha_1\}, \{3\alpha_1\}, ..., \{k\alpha_1\}, \dots$$

$$\{\alpha_2\}, \{2\alpha_2\}, \{3\alpha_2\}, ..., \{k\alpha_2\}, \dots$$

$$\{\alpha_n\}, \{2\alpha_n\}, \{3\alpha_n\}, ..., \{k\alpha_n\}, \dots$$

⟦folio 41⟧

一些 $k_1 < k_2 \leq M^n + 1$ 组会匹配。在这种情况下，数字$m = k_2 - k_1$满足条件，因为$\{m\alpha_i\} = \{(k_2 - k_1)\alpha_i\} = \{k_2\alpha_i - k_1\alpha_i\}$、$\{k_1\alpha_i\}$和$\{k_2\alpha_i\}$处于长度小于$\varepsilon$的一个半常域中，因此$m\alpha_i$与整数的距离小于$\varepsilon$。定理已被证明。

六个针穿过平面上的网格。还可以考虑空间网格。它们的定义方式与平面向量相同，只是您需要采用三个非共面向量 (图 9)，而不是两个非裁剪向量。以与上面对多边形和平面晶格所做的相同的方式，确定空间晶格中多边形的内接性和几乎内接性。正多边形 (图 10) 的哪个脚跟适合整数*) 空间晶格？答案如下：

问题 4. 立方体、四面体和八面体适合一个整数晶格。

问题 5. 十二面体和二十面体不适合任何晶格。

问题 6. 给定空间中的一族平行平面，使得该族的相邻平面之间的距离相等。是否有可能在空间中排列a）一个二十面体，b）一个十二面体，使得它们的顶点位于族的平面上？

我们收到了关于将正多边形刻入空间晶格的全面答案。对于几乎铭文，我们也得到了一个全面的答案，与平案相同：

问题 7. 任何多边形几乎都适合空间中的任何格子。

这些序列的所有成员都属于区间 [0; 1[.将此区间分成长度小于 $\varepsilon$ 的片段（半段）：

$$\begin{align*}
0; \frac{1}{M} \mid ; \left[\frac{1}{M}; \frac{2}{M}\right] \mid \dots \mid \left[\frac{M-1}{M}; 1\right] \\
\mathrm{где} M - \mathrm{натуральное}, M > \frac{1}{\varepsilon} \quad (\mathrm{тогда} \frac{1}{M} < \varepsilon). \end{align*}$$

现在让我们为序列的每个成员分配区间 [0; 1[，它位于其中。

然后，对于每个自然数$k$，将定义对应于点$\{k\alpha_1\}$、$\{k\alpha_2\}, \dots, \{k\alpha_n\}$的有序半普遍集合。但由于只考虑了$M$半普遍，而每个集合包括$n$半普遍，那么不同的此类集合的数量为$M^n$。如果$k$的范围是从1到$M^n + 1$，那么对于
