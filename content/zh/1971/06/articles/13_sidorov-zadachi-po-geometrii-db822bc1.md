---
id: 1971-6-sidorov-zadachi-po-geometrii-db822bc1
issue: kvant_1971_6
year: 1971
number: "6"
title: 几何问题
authors:
  - Сидоров Ю. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 56
page_labels: 52-54
tag: 2HFM
lang: zh
source: kvant_digital
extraction: vision
content_sha256: bbe8cdf3dbdf7b1752dab15afbbb6c181ad1d386c93a978ea2ce627501ac314f
prompt_sha256: draft-1
translated_from: content/ru/1971/06/articles/13_sidorov-zadachi-po-geometrii-db822bc1.md
source_content_sha256: 254cb9c2d31a9d8d8482a4d25f78af58e2ecff34f7d2e7f48042abd81cf92f88
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

于。 V·西多罗夫

在院校的申请考试中，大量的篇幅专门用于几何问题。大多数问题的条件表述得很简单：在某些几何图形中，指定了几个元素或元素之间的对应关系，需要找到一个未知元素或元素之间的未知对应关系。

这样的“标准”任务条件是每个申请者都能理解的。然而，几何问题及其解决方案的例子是如此多样化，以至于不可能提出任何方便的分类来找出每个特定问题的解决方案。这就是为什么教科书和教具中几乎没有对解题方法的描述。要学习如何解决几何问题，需要对几何基本定理有扎实的知识和良好的理解，最主要的是不断练习和定期解决各种问题。

近年来，大多数小学生仅以“代数方式”解决几何问题，具体包括以下几种。几何图形的未知元素用$x$、$y$、$z$、...表示，并计算已知元素和未知元素之间的若干对应关系。然后求解所得到的代数和三角方程组，并根据问题的条件找到这些元素或对应关系。

这种解决几何问题的格式化方法通常是最简单的方法之一，可以让您快速获得答案。自然地，可能会有这样的愿望来解决所有问题。然而，一个毫不犹豫地学会了将任何几何问题“转化”为代数问题的申请人，如果发现他的解决方法没有达到预期的结果，那么在申请考试中就会遇到难以克服的困难。

几乎每个问题都可以通过不同的方式解决。那些找到最短、最优雅的解决问题的方法的申请人的作品受到高度评价。只有广泛且持续的培训才能让您学会找到最多样化的解决方案。成功选择未知数、方便的绘图、附加的几何结构和简洁的解决方案设计有助于正确理解问题并找到解决问题的最简单方法。我们来看一下具体的例子。

在 MIPT 数学笔试中，提出了以下问题。

1. 三角形ABC的平分线AM和BN相交于O点。已知$AO = \sqrt{3}MO$，$NO = (\sqrt{3} - 1)BO$。命名为三角形ABC。

许多申请人试图通过以下方式解决这个问题。

⟦folio 53⟧

令 $AB=a$、$\Rightarrow BAC=x$、$\Rightarrow ABC=y$ (图 1)。让我们求三角形 $ABN$ 的线段 $AN$ 的长度（根据三角形内角二等分线的性质和正弦定理）：

$$AN = AB \frac{NO}{BO} = a (\sqrt{3} - 1) = \frac{a \sin \frac{y}{2}}{\sin \left(x + \frac{y}{2}\right)}$$

同样，从三角形$ABM$我们发现：

$$BM = \frac{a}{\sqrt{3}} = \frac{a \sin \frac{x}{2}}{\sin \left(\frac{x}{2} + y\right)}$$

由此，得到方程组：

$$\begin{cases} \sin \left(\frac{x}{2} + y\right) = \sqrt{3} \sin \frac{x}{2}, \\ (\sqrt{3} - 1) \sin \left(x + \frac{y}{2}\right) = \sin \frac{y}{2}. \end{cases}$$

大多数以这种方式解决问题的申请人都无法找到这个相当复杂的系统的解决方案。但糟糕的并不是他们没有解决由此产生的系统，而是他们没有尝试寻找另一种方法来解决这个问题。这个问题用下面的方式（也是代数的）更容易解决。

设$AB=x$，$BC=y$，$AC=z$。由三角形$ABM$和$ABN$，根据三角形内角二等分线的性质，可得：

$$\frac{BM}{AB} = \frac{MO}{AO} = \frac{1}{\sqrt{3}},$$

$$\frac{AN}{AB} = \frac{NO}{BO} = \sqrt{3} - 1.$$

因此$BM = \frac{x}{\sqrt{3}}, AN = x (\sqrt{3} - 1)$。从三角形$ABC$我们有：

$$\frac{AN}{CN} = \frac{AB}{BC}, \quad \frac{BM}{CM} = \frac{AB}{AC},$$

那是

$$\begin{cases} \frac{x (\sqrt{3} - 1)}{z - x (\sqrt{3} - 1)} = \frac{x}{y}, \\ \frac{x}{y \sqrt{3} - x} = \frac{x}{z}. \end{cases}$$

从这个方程组可以发现：$y = x \sqrt{3}, z = 2x$。由此得出 $x^2 + y^2 = z^2$ 以及毕达哥拉斯定理的逆命题 $\Rightarrow ABC = \frac{\pi}{2}$。

因此，

$$\Rightarrow BAC = \arcsin \frac{y}{z} = \frac{\pi}{3},$$

$$\Rightarrow ACB = \frac{\pi}{6}.$$

我们再考虑一个问题。

2. 在三角形$ABC$的边$BC$上有一个点$M$，在$AC$边上有一个点$N$，使得$MN \parallel AB$。已知$AB=AN=1$厘米，$CM = \sqrt{3}$厘米。求线段 $MN$ 的长度。

很自然地尝试通过以下方式解决这个问题。让我们用 $x$ (图 2) 表示 $MN$。然后 $CN = \sqrt{3} - x^2$ 并根据三角形的相似度我们得到方程

$$\frac{\sqrt{3} - x^2}{1 + \sqrt{3} - x^2} = x,$$

可以很容易地转换为$x^4 - 2x^3 - x^2 + 6x - 3 = 0$的形式。

这个方程很难找到解，因此我们必须尝试寻找另一种方法来解决这个问题。在-

⟦folio 54⟧

图 2.

例如，问题2可以如下解决。

让我们用$x$表示$MN$，用$y$表示$CN$。那么很容易得到如下方程组：

$$\begin{cases} x^2 + y^2 = 3, \\ \frac{y + 1}{y} = \frac{1}{x}. \end{cases}$$

从该系统的第二个方程我们发现：

$$y - x = xy, \quad x^2 + y^2 - 2xy = x^2y^2.$$

从该方程中减去系统的第一个方程，我们得到：

$$(xy)^2 + 2xy - 3 = 0, \quad xy = -1 \pm 2.$$

考虑到$x > 0, y > 0$，我们得到系统

$$\begin{cases} xy = 1, \\ y - x = 1, \end{cases}$$

从中我们找到答案：

$$x = \frac{1}{2} (\sqrt{5} - 1) (\text{см}).$$

从所考虑的例子中，很清楚如何成功地选择未知数

图 3.

数量有助于以代数方式简化几何问题的解决。让我们给出一些问题的例子，对于这些问题来说，进行额外的几何构造是有用的。

3. 斜方肌$ABCD$侧边$AB$垂直于底面，对角线互相垂直$u \frac{AD}{BC} = k$。求出比率 $\frac{BD}{AC}$。

解决了并且e。通过点 $B$，我们画一条与对角线 $AC$ 平行的线，直到它与线 $AD$ 相交于点 $M$ (图 3)。那么，根据三角形$BMD$直角顶点垂线的性质定理，我们有

$$BD = \sqrt{DM \cdot AD},$$

$$BM = \sqrt{DM \cdot AM}.$$

考虑到$AC = BM, AM = BC$，我们发现

$$\frac{BD}{AC} = \frac{BD}{BM} = \frac{\sqrt{DM \cdot AD}}{\sqrt{DM \cdot AM}} = \sqrt{\frac{AD}{BC}} = \sqrt{k}.$$

4. 三角形$ABC$的边$AC$和$BC$分别有点$N$和$M$，因此

$$\frac{AN}{CN} = n, \quad \frac{BM}{CM} = m.$$

线 $AM$ 和 $BN$ 相交于点 $O$。

寻找关系

$$\frac{AO}{MO} u \frac{BO}{NO}.$$

解决了并且e。我们来执行 $MK \parallel BN$ (图 4)。根据三角形$BCN$和$CKM$的相似度我们找到$CK$：

$$CK = CN \frac{CM}{BC} = CN \frac{CM}{CM + BM} = CN \frac{1}{1 + m}.$$

因此，

$$KN = CN - CK = CN \left(1 - \frac{1}{1 + m}\right) = CN \frac{m}{1 + m}.$$
