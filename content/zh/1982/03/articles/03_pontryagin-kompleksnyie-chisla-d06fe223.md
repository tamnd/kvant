---
id: 1982-3-pontryagin-kompleksnyie-chisla-d06fe223
issue: kvant_1982_3
year: 1982
number: "3"
title: 复数
authors:
  - Понтрягин Л. С.
rubric: osnovnye-stati
page_first: 6
page_last: 7
page_labels: 4-5
tag: EDGX
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 6fdf389c9eb910752d7253788ee07c13fc816767ee32c27a9d1d30dbac019138
prompt_sha256: draft-1
translated_from: content/ru/1982/03/articles/03_pontryagin-kompleksnyie-chisla-d06fe223.md
source_content_sha256: d2dba5eb43244367b7bb3b2bf361ed9a754d8e64008285cfe3d17f158c173ea8
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

现在让我们给自己设定一个任务，扩展数字的概念，或者正如抽象代数中所说，将域 $R$ 扩展到域 $K$，使得在这个新域 $K$ 中方程

$$z^2 + 1 = 0$$

(1)

有一个决定。我们将满足式(1)的场元素$K$表示为$i$。因此，对于 $i$ 我们有

$$i^2 = -1.$$

(2)

由于域$K$包含所有实数和元素$i$，并且由于其中可以进行加法和乘法，因此域$K$应包含关于具有实数系数的$i$的所有可能的多项式，特别是 - 所有一次多项式，即以下形式的表达式

$$z = x + yi = x + iy,$$

其中 $x$ 和 $y$ 是实数。这些表达式称为复数。我们将对它们的操作定义为对多项式的操作，并考虑条件（2）。复数的形式

$$z = x + 0i = x$$

是实数。复数的形式

$$z = 0 + yi = yi$$

该数称为最小数。

令$z_1 = x_1 + y_1 i$、$z_2 = x_2 + y_2 i$为两个复数。根据规定的规则，这些复数的和与积由等式确定

$$z_1 + z_2 = (x_1 + y_1 i) + (x_2 + y_2 i) > = (x_1 + x_2) + (y_1 + y_2) i;$$

$$z_1 z_2 = (x_1 + y_1 i) (x_2 + y_2 i) = x_1 x_2 + (x_1 y_2 + y_1 x_2) i + y_1 y_2 i^2 = (x_1 x_2 - y_1 y_2) + (x_1 y_2 + y_1 x_2) i.$$

当获得最后一个相等时，我们使用结果

$$x_1 z_2 = x_1 x_2 + x_1 y_2 i.$$

(5)

从公式（3）和（4）可以清楚地看出，两个复数的和与积

在所有数字中，还有一个复数。

为了确保减法动作（加法动作的逆动作）存在，只要找到数字$z$（数字$z$的逆数）就足够了，为了确保除法是可能的，$z \neq 0$指示数字$z^{-1}$（数字$z = x + yi$的逆数）就足够了。很容易看出，这些数字是由公式给出的

$$-z = -x - yi,$$

$$z^{-1} = \frac{x}{x^2 + y^2} - \frac{y}{x^2 + y^2} i.$$

因此，每当 $z \neq 0$ 时，$z$ 的倒数$z^{-1}$ 就存在。

**复数的几何表示**

让我们用 $P$ 表示绘图平面，并在其上选择一个直角坐标系 (图 1)。我们将复数 $z = x + yi$ 放置在坐标为 $x, y$ 的点 $z = (x; y)$ 处。我们还用 $z$ 表示从原点 $O$ 到点 $z$ 的向量。因此，字母$z$同时表示一个复数，点$z$表示该复数，向量$z$对应于该复数。在这种情况下，实数的图像落在横坐标轴上 - 因此横坐标轴称为复变量的实平面$P$，数字的数字落在纵坐标轴上 - 因此纵坐标轴称为复变量的$P$平面的最小值。零落在原点。

向量$z$的长度称为复数$z =$的模

图 1.

⟦folio 5⟧

$$= x + yi \text{ и обозначется } |z|:
|z| = \sqrt{x^2 + y^2}.$$

满足条件$|z| = 1$的复数$z$形成一个以原点为圆心、半径为1的圆。数字 1 就位于这个圆上。从点 1 开始，我们沿圆逆时针方向画一条给定长度 $\varphi$ 的圆弧。我们用 $(\varphi)$ 表示该行的末尾。如果$\varphi$是负数，则要得到$(\varphi)$，需要从点1顺时针方向减去弧长$|\varphi|$。众所周知，点$(\varphi)$的横坐标称为cos$\varphi$，纵坐标称为sin$\varphi$。因此，复数 $(\varphi)$ 由下式给出

$$(\varphi) = \cos \varphi + i \sin \varphi.$$

因此，任何复数$z$，根据模型等于1，都可以写成形式（6）。如果$z$是一个任意复数，其模型$|z| = \varphi$不同于0，那么根据模型，$z/\varphi$是一个复数，等于1，因此可以写成形式（6）。来自平等

$$\frac{z}{\varphi} = \cos \varphi + i \sin \varphi$$

我们得到

$$z = \varphi (\cos \varphi + i \sin \varphi).$$

记录(7)称为复数的三角公式。数字$\varphi$称为复数的参数。如果复数 $z$ 的模型 $\varphi$ 与零不同，则参数 $\varphi$ 最多确定项 $2\pi k$，其中 $k$ 是整数。如果复数的模型$\varphi$等于0，则公式（7）也成立，但此时复数的自变量根本没有定义。

数字$\rho$和$\varphi$称为点$z$的极坐标。

现在让我们给出复数作用的几何来源。

从公式（3）和（5）可以看出，复数与实数相加和相乘，就像向量一样。

复数相加的几何意义非常明确：向量$z_1 + z_2$是基于向量$z_1$和$z_2$构建的平行四边形的对角线。这导致了一个重要的不平等

$$|z_1 + z_2| \leq |z_1| + |z_2|.$$

为了给出复数乘法的几何源，您需要使用向量或复数的旋转运算。将向量$z$逆时针旋转角度$\alpha$，我们得到一些新向量，记为$R_\alpha(\alpha)$。从几何角度来看，旋转运算 $R_\alpha$ 具有以下性质：如果 $a$ 是实数，则

$$R_\alpha(az) = aR_\alpha(z),$$

$$R_\alpha(z_1 + z_2) = R_\alpha(z_1) + R_\alpha(z_2).$$

从这两个公式可以看出，如果 $a_1$ 和 $a_2$ 是两个实数，则对应关系 $R_\alpha(a_1z_1 + a_2z_2) = a_1R_\alpha(z_1) + a_2R_\alpha(z_2)$ 成立。

还可以立即明确的是

$$R_\alpha(1) = \cos \alpha + i \sin \alpha.$$

现在让我们证明，将复数$z = x + yi$旋转角度$\alpha$相当于将其乘以复数$\cos \alpha + i \sin \alpha$，即

$$R_\alpha(z) = (\cos \alpha + i \sin \alpha)z.$$

为此，我们首先单独考虑通过角度 $d = \frac{\pi}{2}$ 的旋转。在这种情况下，$\cos d + i \sin d = i$，等式 (11) 的形式为$R_dz = iz$。一方面，几何估计$R_d(1) = i, R_d(i) = -1$。另一方面，$i \cdot 1 = i, i \cdot i = -1$。因此，

$$R_d(1) = i \cdot 1, R_d(i) = i \cdot i.$$

由式(9)直接得出

$$iz = i \cdot (x + iy) = x \cdot i + y(-1) = xR_d(1) + yR_d(i) = R_d(x \cdot 1 + y \cdot 1) = R_d(x + iy) = R_d(z).$$

由此，式(11)对于$\alpha = \frac{\pi}{2}$得证。
