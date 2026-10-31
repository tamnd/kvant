---
id: 1972-1-smyishlyaev-primenenie-neravenstva-bunyakovskogo-koshi-k-resheniyu-nekotoryih-zadach-4eddf0cd
issue: kvant_1972_1
year: 1972
number: "1"
title: Bunyakovsky-Cauchy不等式在解决一些问题中的应用
authors:
  - Смышляев В. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 37
page_labels: 33-35
tag: JGDA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 6284fa09094a41a61a0792208344680cbb20adfa3fa58495f320bbdd11acc5f1
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/10_smyishlyaev-primenenie-neravenstva-bunyakovskogo-koshi-k-resheniyu-nekotoryih-zadach-4eddf0cd.md
source_content_sha256: 9b976d943064d630a31970e004510ea330f1ab265b10352048963699184178c8
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

在解决许多数学问题时，会使用所谓的 Bunyakovsky-Cauchy 不等式

$$\sum_{i=1}^{n} a_i b_i \leq \sqrt{\sum_{i=1}^{n} a_i^2} \cdot \sqrt{\sum_{i=1}^{n} b_i^2} \quad (a_i > 0, b_i > 0).$$

让我们首先给出这个不等式的一个小但非常简单的证明。令 $$\sqrt{\sum_{i=1}^{n} a_i^2} = A, \quad \sqrt{\sum_{i=1}^{n} b_i^2} = B.$$ 那么我们需要证明

$$\frac{\sum_{i=1}^{n} a_i b_i}{AB} \leq 1.$$

使用不等式$xy \leq \frac{1}{2}(x^2+y^2)$，我们写出以下整数：

$$\frac{\sum_{i=1}^{n} a_i b_i}{AB} = \sum_{i=1}^{n} \left(\frac{a_i}{A} \cdot \frac{b_i}{B}\right) \leq$$

$$\leq \sum_{i=1}^{n} \frac{1}{2} \left[ \left(\frac{a_i}{A}\right)^2 + \left(\frac{b_i}{B}\right)^2 \right] = \frac{1}{2} \left( \frac{1}{A^2} \sum_{i=1}^{n} a_i^2 + \frac{1}{B^2} \sum_{i=1}^{n} b_i^2 \right) = 1.$$

这意味着不平等 (*)。众所周知，当

$$\frac{a_1}{A} = \frac{b_1}{B}, \quad \frac{a_2}{A} = \frac{b_2}{B}, \dots, \quad \frac{a_n}{A} = \frac{b_n}{B},$$

也就是说，当

$$\frac{a_1}{b_1} = \frac{a_2}{b_2} = \dots = \frac{a_n}{b_n}.$$

现在让我们展示如何应用不等式 (*)。

⟦folio 34⟧

1. 找到函数的最大值
$$y = a \sin x + b \cos x$$
$$\left(a > 0, b > 0, 0 < x < \frac{\pi}{2}\right).$$

解决方案。由于不等式 (*)，我们有
$$y = a \sin x + b \cos x \leqslant \sqrt{a^2 + b^2} \cdot \sqrt{\sin^2 x + \cos^2 x} = \sqrt{a^2 + b^2}.$$
条件下达到最大值
$$\frac{a}{b} = \frac{\sin x}{\cos x},$$ 即当
$$tg x = \frac{a}{b}.$$

2. 可变型变压器的设计必须使其十字形铁芯尽可能多地填充圆形绕组的内部空腔。如果线圈半径为 $R$，图 处所示的磁芯横截面尺寸应为多少？
解决方案。令$\Rightarrow AOB = \alpha$，则
$$\frac{1}{4} S = y^2 - (y - x)^2 = 2xy - x^2 = R^2 \left(2 \sin \alpha \cos \alpha - \sin^2 \alpha\right).$$
因此$S = 2R^2 \left(2 \sin 2\alpha + \cos 2\alpha - 1\right)$。让我们使用不等式 (*)：
$$S \leqslant 2R^2 \left(\sqrt{2^2 + 1^2} \cdot \sqrt{\sin^2 2\alpha + \cos^2 2\alpha} - 1\right) = 2R^2 \left(\sqrt{5} - 1\right).$$
因此，$S_{\max} = 2R^2 \left(\sqrt{5} - 1\right)$达到
$$\frac{\sin 2\alpha}{\cos 2\alpha} = \frac{2}{1},$$ 从 $\alpha = \frac{1}{2}$ arctg 2 开始。

3. 考虑三对实数$(a_1, b_1), (a_2, b_2), (a_3, b_3)$。证明存在一个边长为$a = \sqrt{(a_2 - a_3)^2 + (b_2 - b_3)^2}, \quad b = \sqrt{(a_3 - a_1)^2 + (b_3 - b_1)^2}, \quad c = \sqrt{(a_1 - a_2)^2 + (b_1 - b_2)^2}$的三角形。
解决方案。为了使$a, b$和$c$成为三角形的边，必须满足不等式$a + b > c, b + c > a, a + c > b$，每个不等式都等价于Bunyakovsky-Cauchy不等式。事实上，对应关系 $a + b \geqslant c$ 等价于不等式 $2ab \geqslant c^2 - a^2 - b^2$ 或 $2 \sqrt{(a_2 - a_3)^2 + (b_2 - b_3)^2} \cdot \sqrt{(a_3 - a_1)^2 + (b_3 - b_1)^2} \geqslant (a_1 - a_2)^2 + (b_1 - b_2)^2 - (a_2 - a_3)^2 - (b_2 - b_3)^2 - (a_3 - a_1)^2 - (b_3 - b_1)^2 = 2 \left[ (a_3 - a_1) (a_2 - a_3) + (b_3 - b_1) (b_2 - b_3) \right]$，减去 2 我们得到不等式 (*)。只有当数字$a_3 - a_1, b_3 - b_1$与数字$a_2 - a_3, b_2 - b_3$成比例时才实现平等；检查在这种情况下三角形的顶点必须位于同一条直线上。
类似地可以证明$a + c \geqslant b, b + c \geqslant a$。这意味着边长为 $a, b, c$ 的三角形存在，尽管它可以退化为线段。您可以在几何上构造这个三角形 - 在笛卡尔坐标系中，它的顶点必须放置在坐标为 $(a_1, b_1), (a_2, b_2), (a_3, b_3)$ 的点上。

⟦folio 35⟧

练习

1. 找到函数的最大值
   a) $y = a \sin x + b \sin \left( \frac{\pi}{3} + x \right) + c \sin \left( \frac{\pi}{3} - x \right) \left( a > 0, b > 0, c > 0, 0 < x < \frac{\pi}{3} \right)$;
   b) $z = a \sin (x + y) + b \sin (x - y) + c \sqrt{\cos 2x \cdot \cos 2y}$
      $(a > 0, b > 0, c > 0, 0 < x < \frac{\pi}{4}, 0 < y < \frac{\pi}{4})$;
   c) $u = a \cos x + b \cos y + c \cos z + d \sqrt{2 \cos x \cos y \cos z}$，其中$a, b, c, d$为正数，$x, y, z$为三角形的剩余角；
   d) $u = a \sin x + b \sin y + c \sin z + d \sin t + e \sqrt{2 \cos (x + y) \cdot \cos (y + z) \cdot \cos (z + x)}$，其中$a, b, c, d, e$为正数，$x + y + z + t = 2\pi$；
   e) $y = \frac{(a_1 x_1 + a_2 x_2 + \cdots + a_n x_n)^2}{x_1^2 + x_2^2 + \cdots + x_n^2}$ $(a_i > 0, x_i > 0)$.

2. 求函数$u = \sum_{i=1}^{n} x_i y_i$的最大和最大的值，如果已知$\sum_{i=1}^{n} x_i^2 \leq a^2$、$\sum_{i=1}^{n} y_i^2 \leq b^2$和$a$、$b$都是正数。

3. 证明不平等
   $$\sum_{i=1}^{n} \sqrt{x_i y_i} \leq \sqrt{\sum_{i=1}^{n} x_i} \sqrt{\sum_{i=1}^{n} y_i},$$
   其中所有$x_i$和$y_i$都是正数。

4. 证明不平等
   $$\left( \sum_{i=1}^{n} \sqrt{a_i b_i} \right)^2 \leq \sum_{i=1}^{n} a_i x_i \sum_{i=1}^{n} \frac{b_i}{x_i},$$
   其中所有$a_i, b_i, x_i$都是正数。

5. 证明不平等
   $$\sum_{i=1}^{n} x_i y_i \sum_{i=1}^{n} \frac{x_i}{y_i} \geq \left( \sum_{i=1}^{n} x_i \right)^2,$$
   其中所有$x_i, y_i$都是正数。

6. 半径为$R$的球有一个具有最完整表面的圆柱体。它的半径和高度是多少？
7. 在三角形内，某一点的位置使得从该点到三角形边的距离的平方和最小。用三角形边长表示这些距离并找到该点。
8*) 三角形面的面积为 $S_1, S_2, S_3$ 和 $S_4$。点 $M$ 位于三角形内部，距面的距离分别为 $h_1, h_2, h_3$ 和 $h_4$。
   a) 和在点$M$的什么位置
      $$\frac{S_1}{h_1} + \frac{S_2}{h_2} + \frac{S_3}{h_3} + \frac{S_4}{h_4}$$

最有意义？
6) 证明任何三角形至少有一个点 $M$ 其和 (*) 最小。求这样的点有多少个。

*) 这个问题是由我们的读者 G. Hovhannitsan 从埃里温发送的。
