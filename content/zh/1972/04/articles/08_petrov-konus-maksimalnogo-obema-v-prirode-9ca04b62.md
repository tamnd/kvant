---
id: 1972-4-petrov-konus-maksimalnogo-obema-v-prirode-9ca04b62
issue: kvant_1972_4
year: 1972
number: "4"
title: 自然界中体积最大的圆锥体
authors:
  - Петров С. М.
rubric: osnovnye-stati
page_first: 30
page_last: 31
page_labels: 28-29
tag: R5N8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 746557c9a51948c6caa2bf60aad85cd8f2271d1807c79bef060724b2199e3faa
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/08_petrov-konus-maksimalnogo-obema-v-prirode-9ca04b62.md
source_content_sha256: e4b894ec4054244fc90e418fef41694f59e9e3299307b9f9930afe8252b96237
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

自然界中体积最大的圆锥体

S·M·彼得罗夫

考虑一个众所周知的问题：
问题1.圆锥体轴向截面顶点处的值等于$\alpha$。在其侧面的展开中找到中心 ueol $\beta$。

解决方案。让我们在 图 1 上描绘圆锥体的轴向截面，并在 图 2 上描绘其发展。我们记下 $*$)，即 $2\pi R = \beta L$ 或

$$\beta = 2\pi \frac{R}{L} = 2\pi \sin \frac{\alpha}{2}. \tag{1}$$

问题 2. 给定一个半径为 $L$ (图 2) 的圆。从中切出一个体积最大的圆锥体。

解决方案。我们有（参见图1）

$$V = \frac{1}{3} \pi R^2 H = \frac{1}{3} \pi \left(L \sin \frac{\alpha}{2}\right)^2 \times L \cos \frac{\alpha}{2} = \frac{1}{3} \pi L^3 \sin^2 \frac{\alpha}{2} \cos \frac{\alpha}{2}. \tag{2}$$

如果我们固定母线$L$并改变角度$\alpha$，则体积$V$将与函数同时达到最大值

$$y = \sin^2 \frac{\alpha}{2} \cos \frac{\alpha}{2}, \tag{3}$$

其中$0 < \alpha < \pi$。

*) 当然，角度以弧度为单位测量。

让我们更改一下变量：

$$\sin \frac{\alpha}{2} = u.$$

然后

$$y = u^2 \sqrt{1 - u^2} = \sqrt{u^4 (1 - u^2)} = \sqrt{\frac{1}{2} u^2 u^2 (2 - 2u^2)}.$$

从$u^2 + u^2 + (2 - 2u^2) = 2 = \text{const}$开始，部首表达式将在$u^2 = u^2 = 2 - 2u^2$处达到其最大值$*$)。因此$u^2 = \frac{2}{3}$，并且

$$\sin \frac{\alpha}{2} = \frac{\sqrt{6}}{3}, \tag{4}$$

$\alpha = 2 \arcsin \frac{\sqrt{6}}{3} \approx 2 \arcsin \frac{2,44949}{3} \approx 2 \arcsin 0,8165 = 2 \cdot 54^\circ 44' = 109^\circ 28'$. \tag{5}

考虑到（1）和（4），我们发现

$$\beta = 2\pi \frac{\sqrt{6}}{3} = \frac{2\pi \sqrt{6}}{3} \approx 120^\circ \cdot 2,44949 \approx 293^\circ 56'.$$ \tag{6}

*) 参见 A.P. Savin 的文章“最大值、最小值和平均值定理”，«Kvant» No. 11，1970。

⟦folio 29⟧

让我们计算圆锥体的最大体积。为此，我们将 (4) 中找到的 sin $\frac{\alpha}{2}$ 值代入 (2)：

$$V_{\text{max}} = \frac{1}{3} \pi L^3 \left( \frac{\sqrt{6}}{3} \right)^2 \sqrt{1 - \left( \frac{\sqrt{6}}{3} \right)^2} = \frac{1}{3} \pi L^3 \cdot \frac{2}{3} \cdot \frac{\sqrt{3}}{3} = \frac{2 \pi L^3 \sqrt{3}}{27} = 0,4030 L^3$$

有趣的是，这种锥体是在自然界中发现的，当然，具有一定的近似值。这是一个物理示例。

任务 3. 让一个电子灯泡能够沿着垂直直线 OB (图 3) 移动（例如在方块上）。为了在 A 点获得最多的照明光，应将其放置在距水平面 OA 多远的位置？

解决方案。已知照度$E$与光线入射角的余弦（$\Rightarrow BAN = \frac{\alpha}{2}$）成正比，与距离的平方（$AB = L$）成反比，即

$$E = C \cdot \frac{\cos \frac{\alpha}{2}}{L^2},$$

其中$C$取决于灯的光强度。

考虑到$L = \frac{R}{\sin \frac{\alpha}{2}}$，我们将式(8)简化为形式

$$E = \frac{C}{R^2} \sin^2 \frac{\alpha}{2} \cos \frac{\alpha}{2}.$$

我们注意到$E$是一个比例函数（3），也就是说，这个问题已经简化为问题2。

因此，如果将灯泡放置在最大体积的圆锥体的顶部，那么其底部的圆周将接收最多的照明（！）。

最后，还有一种现象。

L. A. Tsvetkov 的组织化学教科书（Enlightenment, M., 1969, p. 16）中有：

“碳原子的所有价键都指向四面体的顶点，彼此距离相等，它们之间的角度为109°28′。”

让我们检查一下圆锥体最亮的照明是否也出现在这里？

设正确的四面体$SABC$（图4）的中心$O$有一个碳原子，四个价态指向它的顶点。让我们证明三角形 $AOS, BOS$ 是最大体积圆锥体的主要部分，即右侧，

$$\sin \frac{\alpha}{2} = \frac{\sqrt{6}}{3}.$$

让我们用 $\alpha$ 表示 $\Rightarrow AOS$。我们先做$ON \perp AS$，然后做$\Rightarrow NOS = \frac{\alpha}{2}$。接下来，$\triangle AO_1S \sim \triangle ONS$（显然）。因此$\Rightarrow SAO_1 = \Rightarrow NOS = \frac{\alpha}{2}$。

如果我们用$a$表示地体的边缘，则$AO_1 = \frac{a \sqrt{3}}{3}$，

$$SO_1 = \sqrt{AS^2 - AO_1^2} = \frac{\sqrt{6}}{3}.$$

因此，

$$\sin \frac{\alpha}{2} = \sin \Rightarrow NOS = \sin \Rightarrow SAO_1 =$$

$$= \frac{SO_1}{AS} = \frac{a \sqrt{6}}{3a} = \frac{\sqrt{6}}{3},$$

对应式(4)。

有趣的是函数的图形

$$y = \sin^2 x \cos x,$$

我们呈现给读者。
