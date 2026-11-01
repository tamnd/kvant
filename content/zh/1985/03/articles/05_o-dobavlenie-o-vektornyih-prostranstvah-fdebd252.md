---
id: 1985-3-o-dobavlenie-o-vektornyih-prostranstvah-fdebd252
issue: kvant_1985_3
year: 1985
number: "3"
title: 关于向量空间的附录
authors:
  - О. М.
rubric: smes
page_first: 7
page_last: 7
page_labels: "5"
tag: XW5N
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b68f936d4dfd0bb9a4babb947b7bce4ab5287f0b665ea6efe5ff2a0bbe9c87ce
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/05_o-dobavlenie-o-vektornyih-prostranstvah-fdebd252.md
source_content_sha256: 5c0643f2224f9ded0b39cbde8d0b7a4ca86525478ee2cecb2e49cae96ac75eed
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

$$k^2 = -1; \quad ki = -ik = j; \quad jk = -kj = i.$$
因此，对于值 $i, j, k$ (85)

满足适用于四元数单位的所有条件（参见 «Kvant» No. 2，第 11 页）。如果现在$I$的任何元素$z$线性依赖于值$i, j, k$，则$L$与所有四元数的集合一致。

仍然需要考虑$L$包含与值$i, j, k$线性无关的元素$z$的情况。让我们把（见（59））

$$iz = a_1 + z_1; \quad jz = a_2 + z_2; \quad kz = a_3 + z_3.$$ (86)

我们也把

$$l = a(z + a_1i + a_2j + a_3k).$$ (87)

很容易检查，对于实数 $a \neq 0$ 的任意值，值 $l$ 属于 $I$ 并且不等于 0。我们选择数字$a$以满足条件

$$l^2 = -1.$$ (88)

从对应关系（80）可以得出：

$$il = -li; \quad jl = -lj; \quad kl = -lk.$$ (89)

现在考虑数量$ilj$。我们有

$$ilj = i(-jl) = -kl; \quad ilj = -lij = -lk = kl.$$ (90)

因此，我们得出$-kl = kl$的结论，从$(kl)^2 = -1$开始这是不可能的。所以，我们遇到了一个矛盾——弗罗贝努斯定理已被证明。

关于向量空间的附录

考虑三维空间中所有向量的集合 $V_3$，原点位于固定点 $O$。如果我们在空间中引入一个坐标系$x_0, x_1, x_2$，原点位于$O$，则任何向量$v \in V_3$都可以唯一表示为以下形式

$$v = x_0i_0 + x_1i_1 + x_2i_2,$$ (1)

ede $i_0, i_1, i_2$ 是$Ox_0, Ox_1, Ox_2$ 轴的唯一向量，$x_0, x_1, x_2$ 是一些数字（称为向量$v$ 的坐标）。向量相加时，它们的坐标相加，向量乘以一个数时，它的坐标乘以这个数，即

$$v + v' = (x_0i_0 + x_1i_1 + x_2i_2) + (x'_0i_0 + x'_1i_1 + x'_2i_2) =$$

$$= (x_0 + x'_0)i_0 + (x_1 + x'_1)i_1 + (x_2 + x'_2)i_2;$$ (2)

$$av = a(x_0i_0 + x_1i_1 + x_2i_2) =$$

$$= (ax_0)i_0 + (ax_1)i_1 + (ax_2)i_2.$$ (3)

引入坐标后，我们可以假设空间 space 中的向量是数字 $(x_0, x_1, x_2)$ 的三元组，而忘记它们的几何原点。有了那个

该研究的方法变成了纯粹的代数方法，并且基于公式（1）-（3）。

代数方法可以轻松确定变化次数大于三的向量空间。也就是说，对于任何 $n \geq 1$，n 维（算术）向量空间是$v = (x_1, x_2, \dots, x_n)$ $n$ 实数的集合，其中引入了加法运算：

$$u + v = (x_1, x_2, \dots, x_n) + (y_1, y_2, \dots, y_n) =$$

$$= (x_1 + y_1, x_2 + y_2, \dots, x_n + y_n) = w$$ (4)

乘以数字 $a \in R$：

$$au = a(x_1, x_2, \dots, x_n) =$$

$$= (ax_1, ax_2, \dots, ax_n).$$ (5)

在这种情况下，集合 $(x_1, x_2, \dots, x_n)$ 称为 $n$ 维向量。它们可以写成 $(x_1i_1 + x_2i_2 + \dots + x_ni_n)$ 形式或$x_0 + x_1i_1 + \dots + x_{n-1}i_n$ 形式，正如 L. S. Pontryagin 的文章中所做的那样（参见第 2 页）。

研究 $n$ 维向量空间时的主要概念是线性相关：如果存在数字 $a_1, a_2, \dots, a_k$，且不全部等于 0，则一组向量 $v_1, v_2, \dots, v_k$ 被称为线性相关，使得

$$a_1v_1 + a_2v_2 + \dots + a_kv_k = 0.$$

可以证明，$n$维空间中任何超过$n$向量的集合都是线性相关的；另外，在这个空间中你可以指定一组$n$线性无关向量（这样的一组取决于基），例如一组$i_1 = (1, 0, 0, \dots, 0), i_2 = (0, 1, 0, \dots, 0), \dots, i_n = (0, 0, \dots, 0, 1).$

练习

1. 证明本附录开头的斜体关于$V_3$的陈述。
2. 证明空间中的两个向量是线性相关的当且仅当它们位于同一条直线上时，以及三个向量 - 当它们位于同一平面上时。
3. 证明（几何）空间中的任何四个都是线性相关的。
4*。证明 $n$ 维空间中的任何 $n+1$ 向量都是线性相关的。
5*。证明次数小于或等于四维算术向量空间体积的多项式集合，其基础可以是多项式 $x^3, x^2, x, 1$。

O.M.
