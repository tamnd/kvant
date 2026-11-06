---
id: 1991-3-solovev-ogyusten-lui-koshi-i-matematicheskaya-induktsiya-d59001a7
issue: kvant_1991_3
year: 1991
number: "3"
title: 奥古斯丁·路易斯·柯西和数学归纳法
authors:
  - Соловьёв Ю. П.
rubric: osnovnye-stati
page_first: 15
page_last: 16
page_labels: 13-14
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 64fc6496c5db5f188727af0dab64572df204d569d1ad406c2bbae5342205aa53
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/03_solovev-ogyusten-lui-koshi-i-matematicheskaya-induktsiya-d59001a7.md
source_content_sha256: 86fafd5bbe02ce1b27659e76d97ff1b8d2db42a7cf73964a9faabc1e3e22a067
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 13⟧

---
running_head:
folio:
---

奥古斯丁
路易斯·柯西和
数学
就职

物理和数学科学博士
索洛维夫

正数的算术平均值不小于其几何平均值：

$$\frac{x_1+x_2+\ldots+x_n}{n} \geq \sqrt[n]{x_1x_2\ldots x_n}.$$

这个等式的值属于法国数学家 O. Cauchy，于 1821 年发表。从那时起，它传统上被认为是最困难的数值不等式之一。在一个半世纪的时间里，出现了几十种证明这种不平等的不同证据。这个传统是柯西本人开创的。他的证明需要几页复杂的计算。我邀请读者熟悉我所知道的最简单的证明。在我看来，它既美丽又令人尊敬。但首先我们需要稍微重新表述柯西不等式。

为什么要重新表述同样的问题？普通数学家知道，这项活动根本不像看上去那么无用……复杂定理的简单证明通常由大量的重新表述组成。

首先，在我们的不等式中，可怕的右侧第 $n$ 根相加。让我们将这两个部分除以它。单位将保留在右侧，轨迹将是数字的算术平均值。

$$y_1 = \frac{x_1}{\sqrt[n]{x_1x_2\ldots x_n}}, \ldots, y_n = \frac{x_n}{\sqrt[n]{x_1x_2\ldots x_n}}.$$

⟦folio 14⟧

---
running_head:
folio:
---

有条件的话
$$y_1 > 0, \dots, y_n > 0,$$
$$y_1 y_2 \dots y_n = 1$$

有必要证明
$$\frac{y_1 + y_2 + \dots + y_n}{n} \geqslant 1.$$ (*)

现在让我们考虑一下数学索引。我们将逐步证明柯西不等式，每次将$n$加一。对于 $n = 1$ 来说这是显而易见的（并且变成严格相等）。假设我们成功证明了某些 $n$ 的不等式。所以，现在我们需要输出$n + 1$。

指示性步骤
需要证明如果
$$z_1 > 0, \dots, z_n > 0, z_{n+1} > 0,$$
$$z_1 z_2 \dots z_n z_{n+1} = 1,$$
然后$z_1 + \dots + z_n + z_{n+1} \geqslant n + 1$。让我们使用不等式 (*)，我们认为它已针对 $n$ 数得到证明。让$y_1 = z_1, \dots, y_{n-1} = z_{n-1}, y_n = z_n, z_{n+1}$。那么两个条件都满足
$$y_1 > 0, \dots, y_n > 0,$$
$$y_1 y_2 \dots y_n = 1,$$

我们假设不等式$y_1 + \dots + y_n \geqslant n$已经被证明，即
$$z_1 + z_2 + \dots + z_{n-1} + z_n \cdot z_{n+1} \geqslant n.$$

请注意，到目前为止我们只关心重新制定。但证据本身在哪里呢？这里是。

如有必要，我们将调整数字$z_1, \dots, z_{n+1}$的大小，以满足$z_n > 1, z_{n+1} < 1$的要求。 （很明显，如果数字 $z_i$ 不同时等于 1，则其中有两个这样的数字。） 现在，在最后一个公式中，我们记下 $z_n \cdot z_{n+1}$ 与总和 $z_n + z_{n+1}$ 的乘积。为此，我们需要证明$z_n + z_{n+1} \geqslant z_n \cdot z_{n+1} + 1$或$z_n + z_{n+1} - z_n \cdot z_{n+1} - 1 \geqslant 0$。

让我们对左边进行因式分解：
$$z_n (1 - z_{n+1}) - (1 - z_{n+1}) = (z_n - 1) (1 - z_{n+1}) \geqslant 0.$$

此后，从 $z_n > 1, z_{n+1} < 1$ 开始，不等式就很明显了。证明是合法的。

现在简单介绍一下这个证明。唯一没有完成的地方是数字$z_n, z_{n+1}$的选择。总的来说，基本的重新表述和数学归纳法对我们来说是有效的。

蜿蜒
（参见第 11 页开头）

3. 在 Anri Poincaré 的最后一部著作《论几何定理》中可以找到大量的 图 均值漂移，他试图在它们的帮助下证明，将环加工成自身、保留面积并在不同方向上移动 ασ 边界圆，至少有两个不动点。 Bircroft 在 1913 年使用不同的方法证明了庞加莱定理，但 Y. M. Elishberr 在 1978 年使用mean-drov 证明了其对带柄球体映射的推广（不动点的数量，以重数计算，不小于 2g+2，其中 $g$ 是柄的数量）。

以下定理也从均值下降理论得出：

(1) 射影平面上的不可约非自相交主闭曲线至少有三个交点。

(2) 闭合平面曲线至少有 4 个顶点（曲率极值点）。

(3) 如果下一个地点（沿着高速公路）的数量更大，我们称两地点之间的河流断面为正。证明河流过境点的数量不少于断面标志序列中保护标志的数量（图 2 上有 4 个位置的mean-ds 的序列为（+++）、（+ -）、（- +））。
