---
id: 2019-7-romanov-yubiley-teoremyi-rayskogo-e3400595
issue: kvant_2019_7
year: 2019
number: "7"
title: 赖斯基定理周年纪念日
authors:
  - Романов А.
rubric: osnovnye-stati
page_first: 12
page_last: 14
page_labels: 11-12
tag: PUP5
lang: zh
source: kvant_digital
extraction: native
content_sha256: d0790606a1711dc0ee497049739ae57732a4fbd3ecde701e5317883dc2cdf9ce
prompt_sha256: draft-1
translated_from: content/ru/2019/07/articles/01_romanov-yubiley-teoremyi-rayskogo-e3400595.md
source_content_sha256: ed163731a6a90dd67969094266626e07e129a5645108be689d0df1822a5181f5
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

赖斯基定理周年纪念日

罗曼诺夫

50

几年前，学生 Dmitry Raisky [1] 的一篇文章提交给《数学笔记》杂志，该文章在解决 Hadwiger [2] 提出的问题上取得了重大进展。德米特里证明了以下定理：当用三种颜色对平面进行着色时（将其划分为三个不相交的集合），您始终可以选择实现所有距离的颜色，即对于任何正 d，在距离 d 处有两个点以所选颜色着色。 Raisky 定理是 Moser 兄弟在 1961 年证明的定理的显着强化，即当一个平面用三种颜色着色时，在距离为 1 的地方将有两个相同颜色的点。在准备发表文章 [1] 时，该定理被推广到 N 维空间并进行了重大编辑。结果，学生的作品变得难以阅读，并且对于年轻的数学家来说难以理解。在这里我尝试重现原始解决方案。我很感谢 N.N.康斯坦丁诺夫，他在 1971 年告诉我赖斯基定理的证明。康斯坦丁诺夫帮助德米特里准备了这篇文章，如果没有他的参与，这篇文章的发表几乎是不可能的。

⟦column⟧

以这种方式定义的乘积最多包含 $n_{◊} k$ 个不同的向量，因为不同对的向量之和可以是 $совпадать.^{Лемма} 1.$ 如果我们考虑 k 光束以任意角度旋转，则仅对于有限数量的旋转角度，固定 n 光束和旋转的 k 光束的乘积将包含少于 $n_{◊} k$ 个不同向量。事实上，可以仅以有限数量的方式从n光束中选择两个不同的矢量a、b，并从k光束中选择两个不同的矢量c、d。对于每个这样的四元组向量，考虑 k 光束旋转角度 D 并比较向量 $a_{+} c_{D}$ 和 $b_{+} d_{D}$ 的总和。由于圆最多有两点相交，因此最多有两个角度 D 可以使这些和相等，从而证明引理 $1.^{Лемма} 2.$ 如果 n 束和 k 束的乘积包含 n ◊ k 个不同的向量，则这些向量的 n ◊ k 端形成 k 指针平行平移得到的 n 个图形，并得到 k 个图形

辅助引理

假设平面上有 n 个不同点组成的图形——一个 n 指针。 Let's choose one of these points and call an n-beam a set of vectors going out from this point to all points of the n-pointer (one of the vectors of the n-beam is a null vector). Let us define the product of an n-beam and a k-beam as a bundle of vectors a + c, where vector a is taken from the n-beam, and c from the k-beam.

DOI: https://doi.org/10.4213/kvant20190702

⟦figure⟧

图 1

由 n 点 (图1) 的平行平移定义。

定理的证明

Suppose that the statement is false and there is a coloring of the plane in three colors for which it is impossible to choose a color in which all distances are realized.那么对于这本涂色书，每种颜色都有

⟦folio 11⟧

周年纪念日

定理

两点之间不可能存在的距离是颜色。考虑 Moser 兄弟提出的 7 点探针，Raisky 将其称为“探针”(图2)。所有绘制的线段的长度均为 1。通过简单的枚举，您可以验证是否从

天堂

⟦column⟧

in any probe for color 1 out of 7 points there are no more than two colors 1, in any probe for color 2 out of 7 points there are no more than two colors 2, and in any probe for color 3 out of 7 points there are no more than two colors 3. Thus, no more than $2_{◊} 7^{2}$ points can be colored in each color, in total no more than $6_{◊} 7^{2}$ points out of $7^{3}$ can be colored.证明完毕。

多维案例

⟦figure⟧

图 2

选择这七个点中的任意三个，则有两个选定的点由线段连接。莫泽定理立即由此得出。对于每种颜色，我们都会有自己的 7 点探针，其中该颜色中将缺少距离，而不是 1 个。让我们在平面上选择一个任意点，并考虑从该点发出的光束的所有矢量。让我们对颜色进行任意编号，并考虑颜色 1 的探针。在三个 7 点探针中的每一个中，选择 7 个点之一，例如 $A_{4}$。然后每个探头都有自己的 7 束。根据引理 1，我们将颜色 2 的 7 点探针旋转一个角度，使得 7 光束 1 和 2 的乘积包含 $7^{2}$ 个不同的向量（它是 49 光束），并将颜色 3 的 7 点探针旋转这样的角度，使得 49 光束和该 7 光束的乘积包含 $7^{3}$ 个不同的向量。根据引理 2，这些 $7^{3}$ 向量的末端 - $7^{3}$ 平面上的不同点 - 形成颜色 3 的 49 个探针，它们还形成颜色 2 的 49 个探针和颜色 1 的 49 个探针。为了完成证明，只需注意：

Raisky 的文章提供了 n 维空间定理的证明：让集合 $A_{1}, A_{2},^{…}, A_{n} +_{1}$ 形成 n 维欧几里德空间 $R^{n} (n >$ 1) 的覆盖；那么其中有一个集合 $A_{i}$ ，对于每个 d > 0，该集合中有一对点，它们之间的距离等于 d。为了证明这种形式的定理，除了构建$R^{n}$中的探针和引理1的证明之外，不需要新的想法。为了不牺牲表示的可访问性，我们考虑三维空间的情况；对于大尺寸来说，困难纯粹是技术上的。 （请注意，在 Raisky 的文章中，证明经过了重大编辑；在这里我尝试重现原始版本。）让我们为 $R^{3}$ 构建一个探针。 Raisky 将主轴称为由边 d 和另一个点 b 组成的正四面体的四个顶点组成的 5 点顶点，相对于面 (图3) 对称于其顶点之一（顶点 a）。他将探针称为 9 点探针，由两个主轴获得，通过顶点 a 组合并旋转，使得这些主轴的点 b 之间的距离也等于 d (图4)。 图3

⟦folio 12⟧

科万特 2019/7

⟦column⟧

Lemma 2 changes slightly. n束和k束的乘积包含n k 个向量，考虑到重数，这些向量的n k 端形成n个k指针平行平移得到的图形，以及n个指针平行平移得到的k个图形。 Each point of the product of sheaves occurs in these figures as many times as the multiplicity of the point. With this approach, the multidimensional case differs from the two-dimensional case only in the design of the probe.

最高估计

⟦figure⟧

图 4

Obviously, such a spindle rotation exists. The proof of Lemma 1 needs minor modification. For a given n-pointer, choose a plane in $R^{3}$ so that the projection of the n-pointer onto this plane contains n different points.让我们选择 k 指针相对于该平面的初始位置（旋转），使其投影包含 k 个不同的点。 On the plane we have an n-beam and a k-beam, for which Lemma 1 is valid.让我们考虑原始 k 梁绕垂直于所选平面的直线的旋转。平面上的投影包含 $n_{◊} k$ 个不同的向量，这证明了$R^{3}$ 的引理 1。 The rest of the proof remains unchanged.

在 Raisky 的文章发表之前，已知有 7 种颜色的平面着色，其中距离为 1 的任意两点都被着色为不同的颜色。 This coloring is based on dividing the plane into equal regular hexagons. S.B. Stechkin 注意到（并且在 Raisky 的许可下，将其插入到文章中）飞机可以分为 6 组，这样并不是每个组都能实现所有距离。 The design element consists of 4 regular hexagons and 8 regular triangles. By means of parallel transfers, the entire plane is paved with this element, as shown in Fig.

The proposed proof does not use ideas missing from Raisky's original version. It turns out that we can refuse to consider rotations that make the points not coincident (Lemma 1).相反，n束和k束的乘积的每个向量可以被分配重数——用于从n束中选择向量和从k束中选择向量的选项的数量，其中向量的总和一致。

⟦figure⟧

图 5

图5.所有三角形都是开放的，六边形的底部和右侧顶点不属于这些图形。如果我们将三角形的边设为 1，那么距离 $d_{1} = 2$ 在集合 $A_{1},^{…}, A_{4}$ 上的实现并不相等

（续第 23 页）
