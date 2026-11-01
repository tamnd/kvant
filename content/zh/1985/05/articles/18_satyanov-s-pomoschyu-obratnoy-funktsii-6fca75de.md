---
id: 1985-5-satyanov-s-pomoschyu-obratnoy-funktsii-6fca75de
issue: kvant_1985_5
year: 1985
number: "5"
title: 使用反函数
authors:
  - Сатьянов П. Г.
rubric: shkola-v-kvante
page_first: 36
page_last: 38
page_labels: 34-36
tag: VBS0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 34000b2e180dee1d073724b382c45562faa80ae69d201d15f50015effb1c40d6
prompt_sha256: draft-1
translated_from: content/ru/1985/05/articles/18_satyanov-s-pomoschyu-obratnoy-funktsii-6fca75de.md
source_content_sha256: e6ee95742c568a747d9781af4ba53003806ccbfdd572ead446dbed2783f61c10
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

数学10

使用反函数

在学校，积分是使用牛顿-莱布尼兹公式计算的。这样如何计算积分

$$I_1 = \int_0^1 \arcsin x \, dx,$$

你需要知道函数$\arcsin x$的反导数，但你不知道。生活怎么样？

让我们转向积分的几何意义：积分就是面积。具体来说，$I_1$是蓝色图1包围的区域的面积。让我们将这个面积求为相应矩形的面积与“黄色区域”的面积$\sigma_1$之间的差。由于函数 $\arcsin x$ 的图形是函数 $\sin x$ 的“反转”图形（通过绕线 $y=x$ 对称获得），因此面积 $\sigma_1$ 等于 $y$ 从 0 到 $\frac{\pi}{2}$ 变化区域中正弦曲线 $x=\sin y$ 下方的面积：

$$\sigma_1 = \int_0^{\frac{\pi}{2}} \sin y \, dy = -\cos y \Big|_0^{\frac{\pi}{2}} = 1.$$

因此，$I_1 = \frac{\pi}{2} - 1$。

现在我们来计算积分

$$I_2 = \int_a^b \ln x \, dx \quad (1<a<b).$$

我们再看一下图(图2)。这次“蓝色区域”$I_2$等于“大矩形”的面积减去“小矩形”的面积和“黄色区域”的面积$\sigma_2$。函数$\ln x$的图形是反函数$e^x$的“倒”图，因此$\sigma_2$是函数$x=e^y$图形下方的区域，在$y$从$\ln a$到$\ln b$变化的区域中：

$$\sigma_2 = \int_a^b e^y \, dy = e^y \Big|_a^b = b-a.$$

⟦folio 35⟧

因此，$I_2 = b \cdot \ln b - a \times \ln a - (b - a) = b \cdot \ln \frac{b}{e} - a \cdot \ln \frac{a}{e}$。

我们已经两次用反函数 ($\sin x, e^x$) 的内部来表示某个函数 (arcsin $x$, ln $x$) 的内部。

$$\ln x \text{ и } e^x - \text{ взимно-образные функции. Но arcsin } x \text{ и sin } x - \text{ не взимно-образные функции (sin } x - \text{ не обратная функция); взимно-образными являются arcsin } x \text{ и sin } x, \text{ рассматриваемый на отрезке } \left[ -\frac{\pi}{2}; \frac{\pi}{2} \right], \text{ или, как говоря математики, } cy\text{ значение функции sin } x \text{ на отрезок } \left[ -\frac{\pi}{2}; \frac{\pi}{2} \right].$$

一般情况下不能这样做吗？例如，如果函数 $f$ 的图形与 图 3 上的形式相同，并且函数 $g$ 是 $[a; b]$ 上 $f$ 的反函数，则从 图 3

$$\int_a^b f(x)dx = b \cdot f(b) - a \cdot f(a) - \int_a^b g(y)dy. \quad (1)$$

不，如果函数$f$的图形具有与图4、a或4、6相同的形式，则不能从图获得等式(1)。这仍然是真的吗？如果属实，如何证明？

目前尚不清楚如何证明某个区间的等式 (1)。让我们尝试证明第一个差异的相应陈述。注意(1)$b$至$x$：

$$\int_a^b f(t)dt =$$

$$= x \cdot f(x) - a \cdot f(a) - \int_a^b g(y)dy \quad (2)$$

（为了简单起见，我们还将内部化变量$x$替换为$t$；内部值与内部化变量的指定非常无关：

$$\int_a^b f(x)dx = \int_a^b f(t)dt = \int_a^b f(z)dz = \dots).$$

众所周知，函数$\int_a^b f(t)dt$是连续函数$f$的反导数（“代数与分析原理9-10”，问题1046）。因此，如果等式 (2) 为真，则函数

$$x \cdot f(x) - a \cdot f(a) - \int_a^b g(y)dy,$$

或者，相同之处在于函数常数的不同

$$\Phi(x) = x \cdot f(x) - \int_a^b g(y)dy, \quad (3)$$

也将是 $f$ 的反导数。

为了检查这是否正确，我们需要对等式 (3) 的右侧进行微分。因此我们要求函数$f$是可微的。

函数$\int_a^b g(y)dy$包含在等式(3)的右侧，是函数$z = f(x)$和函数$\int_a^b g(y)dy$的组合。自从

$$\left( \int_a^b g(y)dy \right)' = g(z), \quad (4)$$

根据成分微分规则

$$\left( \int_a^b g(y)dy \right)' = g(f(x)) \cdot f'(x).$$

由于函数$g$是$f$、$g(f(x)) = x$的逆函数。因此，

$$\left( \int_a^b g(y)dy \right)' = x \cdot f'(x).$$

波塞托姆

⟦folio 36⟧

考虑定理 1，使用 Newton-Leibniz 公式我们得到

$$\int_{a}^{b} f(x)dx = \Phi(x) \Big|_{a}^{b} =$$

$$= [x \cdot f(x) - \int_{a}^{x} g(y)dy] \Big|_{a}^{b} =$$

$$= b \cdot f(b) - \int_{a}^{b} g(y)dy -$$

$$- a \cdot f(a) + \int_{a}^{b} g(y)dy =$$

$$= b \cdot f(b) - a \cdot f(a) - \int_{a}^{b} g(y)dy,$$

Q.E.D.

例如，函数$y = \frac{1}{1+\sqrt{x}}$可微且可逆]0； +∞[ (图 5)。很容易计算出它的反函数就是函数$x = \left(\frac{1}{y} - 1\right)^2 (0 < y \leq 1)$。这就是为什么

$$\int_{0}^{1} \frac{dx}{1+\sqrt{x}} = \frac{1}{2} - \int_{1}^{1/2} \left(\frac{1}{y} - 1\right)^2 dy =$$

$$= \frac{1}{2} + \int_{1/2}^{1} \left(\frac{1}{y} - 1\right)^2 dy =$$

$$= \frac{1}{2} + \int_{1/2}^{1} \left(\frac{1}{y^2} - \frac{2}{y} + 1\right)dy =$$

$$= \frac{1}{2} + \left(-\frac{1}{y} - 2 \ln y + y\right) \Big|_{1/2}^{1} = 2 \ln \frac{e}{2}.$$

本文的主要目的是展示制作绘图并整合类似的几何概念有多么有用（尝试在没有绘图的情况下“打开”公式（1）！）。套用凯撒的名言，这个想法可以表达如下：“德鲁，看到，证明！”

练习。
2. 求 [1; 上的反导数+∞[ 对于函数 $a) y = \sqrt{x^2 - 1} + x, 6) y = \sqrt{x^2 - 1}$。
3. 计算a) $\int_{-1}^{0} \arcsin \sqrt{x} dx,$ b) $\int_{0}^{1} \sqrt{\frac{x}{x+1}} dx$。

萨蒂亚诺夫
