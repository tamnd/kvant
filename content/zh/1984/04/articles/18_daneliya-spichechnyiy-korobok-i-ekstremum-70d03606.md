---
id: 1984-4-daneliya-spichechnyiy-korobok-i-ekstremum-70d03606
issue: kvant_1984_4
year: 1984
number: "4"
title: 火柴盒和极端
authors:
  - Данелия Р. Ш.
rubric: raznoe
page_first: 53
page_last: 53
page_labels: "51"
tag: JRES
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5afc1925ec2c2a03e9fa8d6080417fc36665100cc77452e92b5c1ea08643c7a5
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/18_daneliya-spichechnyiy-korobok-i-ekstremum-70d03606.md
source_content_sha256: ce791749b8ccffe3de4e7d41ad62034e1d7a6bf161fc3e9f0fad13cc4eb52478
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

火柴棍和极端
R.S.丹妮莉亚

当我查看朋友收藏的火柴盒时，我想到了这个问题。他不仅像许多人一样收集标签，还收集整个外壳。您可以看到各种形状和大小的地壳。在浏览软木塞展品时，我想：最“赚钱”的软木塞应该是多大尺寸的？毕竟，这是一个纯粹的数学问题；可以给出以下严格的表述：

声明设计的给定体积 V 的所有匹配壳体（即，由顶部开口的可伸缩壳体和侧面开口的外部部分组成；参见 图 1）的平均值找到确保制造过程中材料成本最低的形状（即，肋条 x:y:z 的比率）（不考虑材料的厚度）。

为了解决这个问题，我们需要以下引理。如果构造三个正变量 a、b、c 的乘积，则当 a = b = c 时，它们的和取最小值。

证明。由于算术平均数和几何平均数不等

$$\frac{a+b+c}{3} \geq \sqrt[3]{abc},$$

(1)

对应关系 abc = k = const 给出 a+b+c ≥ 3√k，并且仅当 a = b = c 时才实现相等。

尽管许多教科书都给出了不等式（1）的证明，但向读者介绍另一种与传统证明不同的证明也没有什么错。

如果我们引入符号

$$x_1 = \frac{a}{\sqrt[3]{abc}}, \quad x_2 = \frac{b}{\sqrt[3]{abc}},$$

$$x_3 = \frac{c}{\sqrt[3]{abc}},$$

那么我们要求不等式写成如下：

$$x_1 + x_2 + x_3 \geq 3,$$

(2)

此外，只有当 x_1 = x_2 = x_3 = 1 时才达到相等。因此，如果乘积 x_1x_2x_3 等于 1，则 x_1 + x_2 + x_3 之和不小于 3，并且仅当 x_1 = x_2 = x_3 = 1 时才等于 3。

事实上，考虑两种可能的情况：

1. 三个x都相等，即x_1 = x_2 = x_3 = 1。很明显，在这种情况下x_1 + x_2 + x_3 = 3。

2. 并非所有 x 都相等。由于它们的乘积等于 1，如果其中一个大于 1，则另一个小于 1。为了定义，我们将：x_1 > 1，x_2 < 1。我们有：

$$(x_1 - 1)(x_2 - 1) < 0 \iff x_1x_2 + 1 < x_1 + x_2 \iff x_1 + x_2 + x_3 > x_1x_2 + x_3 + 1.$$

(3)

但 x_1x_2x_3 = 1，因此

$$x_1x_2 + x_3 + 1 = \frac{1}{x_3} + x_3 + 1 = \frac{1}{x_3} + x_3 - 2 + 3 = \frac{(x_3 - 1)^2}{x_3} + 3 \geq 3.$$

根据 (3)，得出 x_1 + x_2 + x_3 > 3，这是需要证明的。

现在我们可以继续解决我们的问题了。

设壳的尺寸为 x, y, z (图 1)。盒子由两部分组成，第一部分的表面积S_1 = xy + 2xz + 2yz，第二部分S_2 = 2xy + 2xz。总面积（它们的总和）将为 S = 2yz + 3xy + 4xz。

显然，制作壳体所需的材料与S成正比，即我们必须选择x、y、z，使得S最小。为此，我们用以下形式表示 S：

$$S = xyz \left( \frac{2}{x} + \frac{3}{z} + \frac{4}{y} \right)$$

或者，给定等式 xyz = V，

$$S = V \left( \frac{2}{x} + \frac{3}{z} + \frac{4}{y} \right).$$

括号内项的乘积是常数（等于 24/V），因此，根据引理，当项相等时获得最小值，因此 x:y:z = 2:3:4。

因此，当壳体的长、宽、高比例为4：2：3时，材料消耗最少。请注意，工厂通常不遵守此比例（图 2），但也有专门考虑此条件而准备的外壳（图 3）。
