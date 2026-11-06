---
id: 1991-3-alekseev-kurlyandchik-summa-minimumov-i-minimum-summyi-4eb277f4
issue: kvant_1991_3
year: 1991
number: "3"
title: 最低金额和最低金额
authors:
  - Алексеев Р.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 51
page_last: 53
page_labels: 49, 51
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 665f82ad7a069680251b93fd486a8c59eb9602ed80e6f329ae2ec680ad51a6d7
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/16_alekseev-kurlyandchik-summa-minimumov-i-minimum-summyi-4eb277f4.md
source_content_sha256: d44734c71d310315eace7ed1bc3e7f2c04120a36de3509418ad32267b4a4db3d
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 49⟧

最低金额和最低金额

R·阿列克谢耶夫，
L·库尔扬奇克

本文将讨论一种可以证明许多显着不等式的通用方法。最初的想法非常简单。两个任意函数 $f(x)$ 和 $g(x)$，定义在某个线段 $[a,b]$ 上，在不同点 (图 1) 达到最小值（一般来说）。不平等是公平的

$$\min f(x)+\min g(x) \leqslant \min (f(x)+g(x)).$$

图 1.

⟦folio 51⟧

---
running_head:
folio:
---

6) $(a_1^p + \ldots + a_n^p)^p \cdot (b_1^q + \ldots + b_n^q)^q \geq a_1 b_1 + \ldots + a_n b_n$ 如果 $p > 0$、$q > 0$ 与 $\frac{1}{p} + \frac{1}{q} = 1$ 相同（霍尔德不等式）。

解决方案。像往常一样，让我们​​考虑 $n$ 函数
$$f_1(x; y) = a_1 x + b_1 y,$$
$$f_n(x; y) = a_n x + b_n y.$$

最重要的是选择我们考虑功能的正确集合。毕竟，我们的函数是在平面上定义的，我们可以在任何图形上找到最小值！

a) 考虑一个半径为 1、中心位于原点 (图 2) 的圆。几何线性函数$f(x; y) = ax + by$是什么意思？这是坐标为 $(a; b)$ 和 $(x; y)$ 的向量的标量积。但标量积是向量长度与向量之间夹角余弦的乘积。 The cosine of the angle is minimal for collinear vectors, and the length of the vector $(x; y)$ does not change if the end of the vector lies on the circle.这意味着函数 $f(x; y)$ 的最小值是在坐标为 $(x_0; y_0)$、共线 $(a; b)$ (图 3) 的向量上实现的。这样的向量等于$(x_0; y_0) = \left( \frac{a}{\sqrt{a^2 + b^2}}; \frac{b}{\sqrt{a^2 + b^2}} \right)$，标量积等于$(x_0; y_0) \cdot (a; b) = \sqrt{a^2 + b^2}$。

所以，在圆的情况下
$$\min (ax + by) = \sqrt{a^2 + b^2}.$$

现在我们不需要花费任何代价来证明不平等a)。左边包含函数$f_1, \ldots, f_n$的最小值

图 3.
在圆上，右边是它们之和的最小值。

6) 让我们取一个由点 $(x; y)$ 组成的集合，其中
$$x^{\frac{1}{p}} \cdot y^{\frac{1}{q}} = 1.$$

让我们找到该集合上函数 $f(x; y) = ax + by$ 的最小值。当然，我们可以解决这个不完全简单的分析问题（我们建议读者尝试这样做），但幸运的是，我们积累的知识储备使我们能够避免这种情况。让我们使用练习 3 中的不等式 b)：

$$ax + by = \frac{1}{p} \cdot pax + \frac{1}{q} \cdot qby \geqslant \frac{1}{p} \cdot (qby)^{\frac{1}{q}} = (pa)^{\frac{1}{p}} \cdot (qb)^{\frac{1}{q}}.$$

检查是否满足$\frac{x}{y} = \frac{b}{a}$。因此，我们集合上函数 $f(x; y)$ 的最小值等于 $(pa)^{\frac{1}{p}} \cdot (qb)^{\frac{1}{q}}$。如果我们设置$a = \frac{c^p}{p}$、$b = \frac{d^q}{q}$（即，我们采用线性函数$\frac{c^p}{p} x + \frac{d^q}{q} y$），那么这个最小值就等于cd。好吧，如果我们对每个函数都做同样的事情$f_1, \ldots, f_n$：

$$a_1 = \frac{c^p}{p}, b_1 = \frac{d^q}{q}, \ldots,$$

$$..., a_n = \frac{c^p}{p}, b_n = \frac{d^q}{q},$$

那么我们就得到了霍尔德不等式！

现在让我们将柯西-布尼亚科夫斯基不等式与以下不等式进行比较

（结局见第55页）
