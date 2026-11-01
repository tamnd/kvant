---
id: 1984-8-chan-kuang-esli-massyi-zamenit-na-ploschadi-6155aa07
issue: kvant_1984_8
year: 1984
number: "8"
title: 如果用面积代替质量...
authors:
  - Чан Куанг.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 39
page_labels: 35, 37
tag: 18C5
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1e74813db1d626a49c3d6ae9a13699c1a0814138b0a2192ce5bf1a1199259ae7
prompt_sha256: draft-1
translated_from: content/ru/1984/08/articles/05_chan-kuang-esli-massyi-zamenit-na-ploschadi-6155aa07.md
source_content_sha256: 88fb5e49afea399f49698e0ea193cf27cab53f4cbe51a7379f6eda85c0298907
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

如果质量被飞机取代......

陈光

在这篇文章中，我们将证明几个可以安全地归因于初等几何胆结石的定理。毫无疑问，这些定理即使仅仅通过它们的性质，也应该为读者提供方便的表述。但我们在这里讨论它们是出于不同的原因 - 它们将源自一个公式 - 用于计算“转动惯量”的拉格朗日公式。让我们介绍一下服务A、B、C三个点：
$$\alpha |PA|^2 + \beta |PB|^2 + \gamma |PC|^2 = \frac{1}{\mu} (\alpha \beta c^2 + \beta \gamma a^2 + \gamma a b^2) + \mu |PZ|^2;$$
(1)

其中，A、B、C、P 为任意点，α、β、γ 为任意数（理解为集中在 A、B、C 点的“质量”），μ = α + β + γ ≠ 0，a、b、c 为线段 BC、CA、AB 的长度，最后，Z 为 αA、βB、γC 点材料系统的质心，即根据定义，满足以下条件的点：条件
$$\alpha ZA + \beta ZB + \gamma ZC = 0$$
（材料点是一对（点，数），αA，βB和γC是点（A，α），（B，β），（C，γ）材料的关键名称）。原则上，上述内容足以推导公式（1）并理解接下来的内容。但我们仍然建议您阅读 V.N. 的文章。杜布罗夫斯基在上一期杂志的“几何中的惯性矩”中证明了拉格朗日公式（本文中的公式（7）），解释了它与“惯性矩”的关系，并给出了更多它的几何推论，以及质量的必要属性。

⟦folio 37⟧

按$abc \cdot |DA| \cdot |DB| \cdot DC/4RS^2$着色，我们得到
$$-c \cdot |DC| - a \cdot |DA| + b \cdot |DB| = 0,$$
那是
$$|DB| \cdot |AC| = |DA| \cdot |BC| + |AB| \cdot |DC|.$$

踏板三角区
(4) 右侧的表达式看起来相当尴尬，但正如我们稍后将看到的，它具有很好的几何意义。让我们从点 $Z$ 垂线 $ZA_1, ZB_1$ 和 $ZC_1$ 下降到线 $BC, CA$ 和 $AB$ (图 5)。由此产生的三角形$A_1B_1C_1$称为点$Z$的踏板三角形。莱昂哈德·欧拉发现它的面积等于
$$S_{A_1B_1C_1} = \frac{1}{4} \left( 1 - \frac{|OZ|^2}{R^2} \right) S_{ABC}$$
（两个方块都是有方向的！）。让我们从公式（4）得出这个结果。为此，我们将证明$S_aS_bc^2 = abcR \cdot S_{ZA_1B_1}$。将这个等式与 (4) 右侧其他两项的类似等式相加，我们得到：

$$R^2 - |OZ|^2 = \frac{1}{S^2} abcR \left( S_{ZA_1B_1} + S_{ZB_1C_1} \right) + S_{ZC_1A_1}$$
$$= \frac{4R^2}{S_{ABC}} S_{A_1B_1C_1},$$
这相当于欧拉公式。

因此，考虑表达式 $S_aS_bc^2$。显然，$|S_a| = a |ZA_1|/2$、$|S_b| = b |ZB_1|/2$、$c = 2R \sin \widehat{ACB} = 2R \sin A_1ZB_1$（由于角$ACB$和$A_1ZB_1$的边相互垂直，因此它们的大小相等或加起来为$180^\circ$）。因此，
$$|S_aS_bc^2| = abcR \cdot \frac{1}{2} |ZA_1| \|ZB_1| \sin A_1ZB_1 = abcR |S_{ZA_1B_1}|.$$

尚待证明乘积$S_aS_b$的符号与$S_{ZA_1B_1}$的符号一致。通过遍历点 $Z$ 相对于线 $AC$ 和 $BC$ 的四个可能位置（在这些线形成的四个角度中，符号 $S_a, S_b$ 和 $S_{ZA_1B_1}$ 是恒定的），这很容易做到。

总之，我们提出了另一个古老的定理：从三角形外接圆的点到其边（或其延长线）的垂线的底位于一条直线上 - “西蒙直线”（图6）。
