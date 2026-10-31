---
id: 2017-5-shvetsov-polyara-24cbf096
issue: kvant_2017_5
year: 2017
number: "5"
title: 波拉拉
authors:
  - Швецов Д. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 41
page_labels: 37, 39
tag: 391J
lang: zh
source: kvant_digital
extraction: native
content_sha256: bc678fd4988a2f02c15692455949ea6f427570d02fc023166c70f488367e1f51
prompt_sha256: draft-1
translated_from: content/ru/2017/05/articles/06_shvetsov-polyara-24cbf096.md
source_content_sha256: 6669ae4ee676a6fdfba8899fc9529f4fa278d37ee28cc6979f10b10ab3db7738
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

数学圈

波拉拉

什维佐夫

让我们从一个非常简单的问题开始：如何构造从点 P 到给定圆 $\omega$ 的切线？让我们回想一下，这里的标准构造如下：我们找到圆心 O（如何？），然后构造一个直径为 OP 的圆 $\omega_{1}$，现在是圆的交点 $\omega, \omega_{1}$ 并设置切线（图1）。

⟦column⟧

任意割线分别与圆相交于 A、B 点和 C、D 点。令 AC 和 BD 线相交于 E 点，BC 线和 AD 相交于 Q 点（图2）。现在，最后让直线QE与圆$\omega$相交于点$P_{1}$和$P_{2}$，那么直线$PP_{1}$和$PP_{2}$相切！因此，您可以仅使用一把尺子构建从 P 点到圆 $\omega$ 的切线。注意，第一步割线的选择是绝对任意的，但最终还是得到了切线，即点$P_{1}$和$P_{2}$的位置并不取决于四边形ABCD的选择。我们发现所有这样的四边形的对角线的交点都位于同一条直线上（图3）。

⟦figure⟧

图 1

该构造基于切线的基本属性符号 - 绘制到切点的半径垂直于切线，因此该构造看起来很可能并不令人惊讶。但如果你拒绝使用指南针，那么一切都会变得更加有趣。所以，让我们通过给定圆$\omega$外的任意点P画两个点

⟦figure⟧

图 3

所有这些观察结果都可以用定理的形式表述，其基本证明就是本文的主题。$^{1}$ 主要定理。令圆$\omega$内接四边形ABCD的延长线AB、CD交于点P，BC、AD的延长线交于点Q，对角线AC、BD交于点E。令从P引至圆$\omega$的切线与圆$P_{1}$相交，

1 最自然的证明之一

图 2

主要定理使用射影几何。

⟦folio 37⟧

数学

⟦figure⟧

图 4

圆圈

⟦column⟧

⟦figure⟧

图 6

$P_{2}$。那么点 $P_{1}, P_{2}, E, Q$ 位于同一条直线上 (图4)。

沙里金问题

早在1985年，第二十六届国际数学奥林匹克竞赛的参赛者就被提出了以下问题，该问题的作者是杰出的几何学家伊戈尔·费多罗维奇·沙里金（Igor Fedorovich Sharygin，1937-2004）。任务。让三角形PAD、PBC的外接圆第二次相交于M点，如图5。则$\angle$PMO$= 90 ^\circ$，其中O为zom，足以证明四边形PMYX是循环的。 Note that $\angle$ MDP $= \angle$ MAP as inscribed angles subtended by one arc MP, and similarly $\angle$ MCP $= \angle$ MBP (图7). From the equality of pairs of angles, the similarity of triangles MDC and MAB follows. MX 和

⟦figure⟧

图 7

⟦figure⟧

图 5

四边形ABCD的外心$\omega$。证明一下。解决方案。 The statement of the problem is equivalent to the fact that point M lies on a circle with diameter OP. On the other hand, a circle with diameter OP passes through the midpoints of the X, Y segments AB and CD, since $OX \perp AB$ and $OY \perp CD$ (图6).这边走

MY are medians in similar triangles, so triangles MYC and MXB are similar. From the last similarity it follows that the angles are equal: $\angle$ MYP $= \angle$ MXP, which implies that the quadrilateral PMYX is inscribed.至此，问题的表述得证。

根轴和主定理的证明

⟦folio 39⟧

数学

圆圈

QE 与直线 $P_{1} P_{2}$ 重合。 But the points $P_{1}$ and $P_{2}$ are obviously symmetrical with respect to the straight line PO, hence $P_{1} P_{2} \perp PO$.因此，$QE \perp PO$。同样，$PE \perp QO$。因此，E点是三角形POQ的高的交点（换句话说，四元组P、Q、E、O是正交中心，即这些点中的每一个都是顶点在其余三个点的三角形的正交中心）。具体来说，$OE \perp PQ$（图10）。

⟦figure⟧

图 10

接下来怎么办？

主要定理的构造是如此普遍，以至于它的一些对象已经赢得了自己的名字。因此，点 P 称为线 $P_{1} P_{2}$ 的极点，线 $P_{1} P_{2}$ 本身称为点 P 的极点。这样，每个点（极点）都与自己唯一的线（极点）相关联，这种对应关系称为极点。极坐标对应在解决最困难的问题方面有着非常广泛的应用。为了快速有效地介绍该主题，我们建议选择一系列问题 [1]，您可以在其中找到许多有趣的示例。令人惊讶的是，如果我们用椭圆、双曲线或抛物线 (图11) 替换圆，则用一根标尺构造切线的过程完全相同。乍一看，我们的证明在这种情况下似乎毫无用处，但实际上，提到的所有三种情况（椭圆、双曲线和抛物线）都可以简化为圆形的情况。

⟦figure⟧

图 11

你！为此，使用所谓的投影变换。例如，您可以在一本详细的书中阅读有关它们的内容 [2]。最后，我们注意到整个情节的基础是 Sharygin 问题，这是一种完全不同的方法，以及它与其他几何学珍珠的联系，可以在这篇精彩的文章 [3] 中找到。

⟦column⟧

文学

1. P.A.科热夫尼科夫。极性匹配。 (http://geometry.ru/persons/kozhevnikov/极地.pdf) 2. I.Ya.Yaglom。几何变换。第 2 卷。 – M.：Nauka，1955 年。(http://www.math.ru/lib/files/djvu/yaglom/ tom2.djvu) 3. V. Protasov。大约两个骑自行车的人和一个樱桃核。 – «Kvant»，2008 年，第 3 期。（http://geometry.ru/articles/protasovbycicle.pdf）
