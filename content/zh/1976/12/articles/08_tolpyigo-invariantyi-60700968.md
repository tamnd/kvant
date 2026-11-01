---
id: 1976-12-tolpyigo-invariantyi-60700968
issue: kvant_1976_12
year: 1976
number: "12"
title: 不变量
authors:
  - Толпыго А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 26
page_labels: 19, 21, 22, 24
tag: HIKB
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9ef4a67a839876efec0c40ea93fc68ce4173a81f5ca5303b226e91415502c25b
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/08_tolpyigo-invariantyi-60700968.md
source_content_sha256: af98cfd9d62726e3b76cf52876b7f030bad5ac662d26ebb4f54d3cfbe8a4c02b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

不变量

在 «Kvant» 中，已经写过关于使用不变量的选择来解决问题的文章（1976，第 2 期，第 32 页）。本文讨论不变量的概念以及与之相关的一些可能的问题。

1. 问题的一般陈述

借助不变量，可以解决以下类型的问题：集合$M$的数据（我们将其元素称为“位置”）以及从一个位置移动到另一个位置的规则；是否可以通过几步从给定位置$\alpha$移动到另一个给定位置$\beta$？一个更普遍的问题：我们如何确定任意一对位置$\alpha$，$\beta$是否可以分几步从$\alpha$到$\beta$？

显然，所描述的情况具有以下性质：如果从位置$\alpha$可以到达位置$\beta$，从$\beta$可以到达位置$\gamma$，那么从$\alpha$可以到达$\gamma$。这种性质称为传递性。

让我们考虑一个具体的任务。

问题 1. 将圆划分为扇区，其中以某种方式考虑 $n$ 筹码。可以同时移动任意两个芯片：一个 - 顺时针移动一个扇区，另一个 - 沿相反方向移动一个扇区。是否可以从位置$\mu$（其中每个扇区有一个芯片）从位置$\alpha$移动到属于同一扇区的任何其他位置

*) «Kvant», 1972, № 2, c. 2.

⟦folio 21⟧

关键是，如果 $f$ 是一个不变量，那么，一般来说，$f(\alpha) = f(\beta)$ 不会得出任何结论。如果$f(\alpha) \neq f(\beta)$，则位置$\alpha$和$\beta$不相等（这由（1）得出）。如果$f(\alpha) = f(\beta)$，那么位置$\alpha$和$\beta$可以是等价的，也可以是非等价的：不禁止不变量在不同的轨道上取相同的值。 （例如，常量函数，即对 $M$ 中的所有元素取相同值的函数，也是不变的。）

怎么会这样呢？尝试为每个$n$输入4$k$从位置$\mu$移动到位置$v$...由于某种原因它不起作用。让我们尝试找到另一个更微妙的不变量。

Zanuterum 扇区（例如，顺时针）从 1 到 $n$。对于扇区中 $\alpha$ fizek 的任意排列，让我们用 $a_k(\alpha)$ 表示具有排列 $\alpha$ 的第 $k$ 扇区中的 fizek 数量。现在让我们考虑以下函数$q$：
$$q(\alpha) = 1 \cdot a_1(\alpha) + 2 \cdot a_2(\alpha) + 3 \cdot a_3(\alpha) + \dots + n \cdot a_n(\alpha).$$

函数$q$是不变的吗？任意允许的移动 (图 5) 会影响总和 (2) 的 4 项：
$$\dots + i \cdot a_i(\alpha) + (i + 1) \cdot a_{i+1}(\alpha) + \dots + (j - 1) \cdot a_{j-1}(\alpha) + j \cdot a_j(\alpha) + \dots$$

随着 图 5 处描绘的运动，总和 (3) 非常印度式地变成总和
$$\dots + i \cdot [a_i(\alpha) - 1] + (i + 1) \cdot [a_{i+1}(\alpha) + 1] + \dots + (j - 1) \cdot [a_{j-1}(\alpha) + 1] + j \cdot [a_j(\alpha) - 1] + \dots$$

很容易检查两个总和是否相等。所以，$q$是一个不变量！不，我们说过第 $n$ 扇区与第一个扇区接壤。这意味着还有 3 种可能性 (图 6-8)。与刚才类似的计算表明，在图 6 的情况下，$q(\alpha)$ 会减少$n$，在图 7 的情况下会增加$n$。在第三种情况下，$q(\alpha)$当然不会改变。因此，一次移动，函数 $q$ 的值可以改变，但只能改变 $n$。斯莱多瓦-

⟦folio 22⟧

因此，$q(v) = l \cdot n$和$r(v) = 0$（无论$n$和$l$是什么）。另一边，
$$a_1(\mu) = a_2(\mu) = \dots = a_n(\mu) = 1.$$
方法，
$$q(\mu) = 1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2}.$$
如果$n = 2m$，则$q(\mu) = n \cdot m + m$和$r(\mu) = m \neq 0$。因此，如果 $n$ 是偶数，我们就得到 $r(\mu) \neq r(v)$。因此，即使对于 $n$，位置 $\mu$ 和 $v$ 也不相等。
如果$n = 2m + 1$，则$q(\mu) = n \cdot (m+1)$和$r(\mu) = 0$。因此，即使是$n$，我们也有：$r(\mu) - r(v)$。事实证明，即使对于$n$，位置$\mu$和$v$的等价性问题仍然悬而未决。

3. 通用不变量

如果不变式 $f$ 在非等价位置取不同的值，我们称其为通用的：
如果$\alpha \neq \beta$，则$f(\alpha) \neq f(\beta)$。
因此，对于通用不变量 $f$
如果$f(\alpha) = f(\beta)$，则$\alpha \sim \beta$。
通用不变量在每个轨道上都有自己的值。因为对于通用不变量
$$\alpha \sim \beta \iff f(\alpha) = f(\beta),$$
任何一对位置的通用不变量使我们能够确定它们是否相等。
如何检查 neokot 不变量 $f$ 是否具有通用性？没有通用的方法。下面的简单定理可以提供帮助。
如果 $a)$ 存在位置 $\delta_1, \delta_2, \dots, \delta_l$，使得每个位置 $\alpha \in M$ 等价于其中一个位置，并且 $b)$ 不变量 $f$ 至少采用 $l$ 个不同的值，则 $f$ 是通用不变量，并且位置 $\delta_i, \delta_j (i \neq j)$ 不是两两等价的。
从 $a)$ 可以看出，最多有 $l$ 轨道。从 $b)$ 可以看出，至少有 $l$ 轨道。因此，正好有 $l$ 轨道。再次从$b)$得出不变式$f$恰好采用$l$值和值，$f$是通用的。最后，从 $a)$ 可以得出，位置 $\delta_1, \delta_2, \dots, \delta_l$ 采用不同的轨道，因此不是两对等价的。

任务1（结束）。让我们证明不变式 $r$ 是通用的。让我们用$\delta_i$表示以下物理排列：一个物理位于$i$扇区，所有其余物理位于$n$扇区。当然，在$\delta_n$下，我们将配对安排，其中所有$n$物理量都在$n$扇区中。

很容易报告，任何排列都相当于位置$\delta_1, \delta_2, \dots, \delta_n$之一。事实上，$a$是空的——物理单位的任意排列。让我们尝试收集$n$扇区中的所有$n$物理单元。为此，我们将转动第一个 fizek，直到将其驱动到第 $n$ 扇区；同时，按照规则，我们将第二个菲泽克向相反的方向移动。然后，我们将第二个 fizek 驱动到第 $n$ 个扇区，将第三个 fizek 向相反方向移动，依此类推 - 直到第 $(n-1)$ 个 fizek。当我们将$n-1$物理驱动到$n$扇区时，$n$物理将位于某个$i$扇区$(i=1, 2, \dots, n)$中。这意味着$\alpha \sim \delta_i$。

我们来数一下$r(\delta_i)$。在$i \neq n$：
$$\begin{cases} a_1(\delta_i) = a_2(\delta_i) = \dots = a_{i-1}(\delta_i) = \\ = a_{i+1}(\delta_i) = \dots = a_{n-1}(\delta_i) = 0, \\ a_i(\delta_i) = 1, \\ a_n(\delta_i) = n-1. \end{cases}$$
因此，$q(\delta_i) = i \cdot 1 + n \cdot (n-1)$和$r(\delta_i) = i$。另外，$q(\delta_n) = n \cdot n$和$r(\delta_n) = 0$。因此，不变的 $r$ 至少需要 $n$ 值。

根据定理，不变式 $r$ 是通用的，并且位置 $\delta_1, \delta_2, \dots, \delta_n$ 不是两两等价的。

由于 $r$ 是普适不变量，
$$\alpha \sim \beta \iff r(\alpha) = r(\beta).$$

⟦folio 24⟧

当且仅当位置 α 和 β 相等时同时发生。

这个定义的本质是什么？如果位置α和β相等，则由于$f_1, f_2, \dots, f_k$是不变量，系统(5)的各个等式仍然满足。 “朝这个方向”画布与此无关。如果不变量 $f_1, f_2, \dots, f_k$ 是通用的，则位置 α 和 β 的等价性将从系统 (5) 的任何等式中得出。我们没有给出它们的通用性，但是需要系统（5）的同时执行来改变α和β的位置。这正是画布概念的本质。因此，虽然某些不变量$f_1, f_2, \dots, f_k$可以在非等价位置α、β处取相同的值，但它们上的集合$\langle f_1, f_2, \dots, f_k \rangle$的值是不同的。

一个完整的不变量系统是全称不变量概念的推广：如果$f$是一个全称不变量，那么由一个不变量组成的系统$\langle f \rangle$当然是完整的。

问题 3. 整数被写入 2x2 表中。首先，在任何表中允许同时：一个数字加 2，从另一个数字得出 2，其次，在任何行中同时：一个数字加 3，从另一个数字得出 3。哪些表是等效的？

让我们考虑三个函数：对于任何表

$$\alpha = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

让我们用$p(\alpha)$表示总和$a + b + c + d$，用$q(\alpha)$表示数字$a + b$除以2的余数，用$r(\alpha)$表示数字$a + c$除以3的余数。函数$p, q, r$是不变量。证明任意表 α 与表 等价并不难

$$\begin{pmatrix} 0 & q(\alpha) \\ r(\alpha) & p(\alpha) - q(\alpha) - r(\alpha) \end{pmatrix}.$$

因此，从等式

$$\begin{cases} p(\alpha) = p(\beta), \\ q(\alpha) = q(\beta), \\ r(\alpha) = r(\beta) \end{cases}$$

(6)

由此可见，表 α 和 β 等效于同一个表，因此彼此等效。相反：表 α 和 β 的等价性是等式 (6)，因为 $p, q$ 和 $r$ 是不变量。因此，$\langle p, q, r \rangle$是一个完整的系统。

规则 8. 解决表 $n \times n$ 的问题，其中允许与问题 3 中相同的转换。很自然地期望有 2$n$-1 个不变量的完整系统。

规则 9. 如果 $f_1, f_2, \dots, f_k$ 是不变量并且 $g$ 是 $k$ 个参数的数值函数，则函数 $h$：

$$h(\alpha) = g(f_1(\alpha), f_2(\alpha), \dots, f_k(\alpha))$$

(7) 是一个不变量（参见练习 2）。一探究竟。

规则 10. 如果 $h$ 是一个不变量，$\langle f_1, f_2, \dots, f_k \rangle$ 是一个完整的不变量系统，则还有一个由 $k$ 参数组成的数值函数 $g$，它满足 (7)（参见练习 3）。证明一下。

规则11.集合$M$是数平面上的点的集合，即实数对$\langle x, y \rangle$的集合。唯一有效的转换是$\langle x, y \rightarrow \langle y, x \rangle$。让

$$\begin{cases} f_1(x, y) = xy, \\ f_2(x, y) = x + y. \end{cases}$$

证明$\langle f_1, f_2 \rangle$是一个完整的不变量系统。

规则 12. 集合 $M$ 是空间中的一组点或一组实数轨迹 $\langle x, y, z \rangle$。允许过渡 $\langle x, y, z \rightarrow \langle y, x, z \rangle$ 和 $\langle x, y, z \rightarrow \langle x, z, y \rangle$。让

$$f_1(x, y, z) = xyz,$$

$$f_2(x, y, z) = xy + yz + zx,$$

$$f_3(x, y, z) = x + y + z.$$

证明$\langle f_1, f_2, f_3 \rangle$是一个完整的不变量系统。

规则 13. 集合$M$ 由所有可能的实数集合（或元组）$\langle x_1, x_2, x_3, \dots, x_n \rangle$ 组成（n 是固定的）。允许交换任意两个相邻数字的位置。找到一个完整的不变量系统。
