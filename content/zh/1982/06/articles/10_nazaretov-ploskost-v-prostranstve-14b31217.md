---
id: 1982-6-nazaretov-ploskost-v-prostranstve-14b31217
issue: kvant_1982_6
year: 1982
number: "6"
title: 太空中的飞机
authors:
  - Назаретов А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 41
page_labels: 38-39
tag: PQ64
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2404d7b37a44c15e02ff8b9706be37f0d70c86075b3b2c73cb466c8413075189
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/10_nazaretov-ploskost-v-prostranstve-14b31217.md
source_content_sha256: 6defcf130fd5ae6cf8c1ce87316714793a5352a86d729e394d8f421e183bbe60
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

空间平坦度

教科书《几何9-10》第45节证明，任意一次方程*)$ax+by+cz+d=0$的图是垂直于坐标为$(a; b; c)$的向量的平面。

由此可见，由方程定义的平面

$$a_1x+b_1y+c_1z+d_1=0 \quad (1)$$
$$a_2x+b_2y+c_2z+d_2=0 \quad (2)$$

当且仅当存在 $\lambda$ 使得 $a_2=\lambda a_1$、$b_2=\lambda b_1$、$c_2=\lambda c_1$ 时，它们是并行的。

显然，方程（1）、（2）的平面重合当且仅当存在$\lambda$使得$a_2=\lambda a_1$，$b_2=\lambda b_1$，$c_2=\lambda c_1$，$d_2=\lambda d_1$。

再次划线。从一次方程到平面（其图）的过渡是明确的：每个一次方程都是满足某个平面的唯一平面的图。 （他们说“具有方程 $ax+by+cz+d=0$ 的平面”，甚至“平面 $ax+by+cz+d=0$”。）从平面（在坐标空间中）到方程的反向转换一点也不明确：每个平面都可以给出无限组方程；如果平面 $\Delta$ 是方程的图形

py $ax+by+cz+d=0$，那么它也是任意方程$(\lambda a)x+(\lambda b)y+(\lambda c)z+(\lambda d)=0$的图。这些方程中的每一个都称为 $\Delta$ 平面方程。

在手册的同一段中证明了在每个平面的坐标空间中存在一个某一次方程的图。

特别是，穿过点$M(x_1; y_1; z_1)$并垂直于（非零）向量$\vec{n}=(a; b; c)$的平面方程为$a(x-x_1)+b(y-y_1)+c(z-z_1)=0$。

如果“以一般形式”重复手册中同一段落中问题 28 的解决方案，我们得到点 $K(x_0; y_0; z_0)$ 到平面 $ax+by+cz+d=0$ 的距离等于

$$\frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}.$$

任务 1（MGMI，1981）。写出垂直于轴 $Ox$、垂直于坐标 $(1; 0; 0)$ 的向量的平面方程。因此，所需方程的形式为$1(x-3)+0(y-2)+0(z-4)=0$或$x-3=0$、$x=3$。然而，答案的最后一种形式可以无需演示即可传达。

任务 2（MIET，1981）。求平行平面 $x-y+2z-4=0$ 和 $x-y+2z-10=0$ 之间的距离。

所需距离显然等于从平面$x-y+2z-4=0$的任意点（例如从点$K(0; 0; 2)$）到平面$x-y+2z-10=0$的距离。使用现成的公式，我们得到答案$\sqrt{6}$。

任务 3（MIIVT，1980）。求通过点 $M(0; 1; 0)$、$N(1; 1; 1)$ 和 $K(0; 0; 1)$ 的平面方程。

设 $ax+by+cz+d=0$ 为原方程。将点$M, N, K$的坐标代入其中，我们得到一个三方程组，其中有四个

⟦folio 39⟧

图 1.

图 2.

图 3.

未知：

$$\begin{cases}
b+d=0 \\
a+b+c+d=0 \\
c+d=0
\end{cases}$$

因此$b=-d, c=-d, a=d$。这意味着所需方程的形式为 $dx-dy-dz+d=0$ 或（因为 $a, b$ 和 $c$ 不同时等于 $0, d \neq 0$）$x-y-z+1=0$。

问题 4（MGMI，1981）。写出穿过 Ox 和点 M(3; 2; 4) 的平面的方程。

例如，穿过 Ox 的平面包含点 (1; 0; 0) 和 (2; 0; 0) - 问题已简化为前一个问题。然而，我们可以立即报告穿过 Ox 的平面方程的形式为 $by+cz=0$。

问题 5（MEPhI，1978）。点A(1;0;3)、B(-1;3;4)和C(1;2;1)属于平面α。对于什么 k 值，点 M(k; 2; 5) 也属于平面 α？

我们找到ABC平面的方程（问题3）并将M点的坐标代入其中。稍微短一些，利用向量$\vec{AB}, \vec{AC}$和$\vec{AM}$的共面性，将向量$\vec{AM}$展开为向量$\vec{AB}$和$\vec{AC}$：$\vec{AM}=\mu \vec{AB}+\nu \vec{AC}$；将这个向量等式重写为坐标形式后，我们得到了一个包含第三个变量 μ、ν、k 的三个方程组。

问题 6（MIHM，1981）。找到平面 $-3y+z+2=0$ 和 $2y+z-5=0$ 之间的 uelem。

我们将使用垂直于这些平面的向量之间的角度 β 找到所需的角度 α。角度α和β可以不重合。根据定义（几何 9-10，第 38 节）$0^\circ \leq \alpha \leq 90^\circ$。根据定义（“几何 9-10”，第 24 节），向量之间的角度 β 包含在 $0^\circ$ 和 $180^\circ$ 之间。显然 (图 1)、$\alpha=\beta$ 或 $\alpha=180^\circ-\beta$。因此$\cos \alpha=|\cos \beta|$。

任务 7（MISIS，1980）。求通过点 A(0;0;0)、B(1;1;1) 和 C(3;2;1) 的平面与通过点 A(0;0;0)、B(1;1;1) 和 D(3;1;2) 的平面之间的平面。

首先，我们找到平面 ABC 和 ABD 的方程（问题 3），然后找到它们的方程（问题 5）。

问题 8（MIIVT，1981）。对于右四级缺口，侧边长度与底边长度之比等于2。求缺口与平面BC$_1$D的对角线BD$_1$。

让我们引入一个如图2所示的坐标系并设置$|AB|=a$。接下来，我们依次求出B点、C$_1$、D点的坐标，平面BC$_1$D的方程（问题3），D$_1$点的坐标和向量$\vec{BD}_1$。
