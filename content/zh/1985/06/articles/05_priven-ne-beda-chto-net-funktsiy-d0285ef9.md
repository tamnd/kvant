---
id: 1985-6-priven-ne-beda-chto-net-funktsiy-d0285ef9
issue: kvant_1985_6
year: 1985
number: "6"
title: 没有功能也没关系
authors:
  - Привень А. И.
rubric: osnovnye-stati
page_first: 22
page_last: 23
page_labels: 20-21
tag: 98KK
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a47b52b81a1047d082846e8507a6fc62a74dbeef25601f97e422525d029e6712
prompt_sha256: draft-1
translated_from: content/ru/1985/06/articles/05_priven-ne-beda-chto-net-funktsiy-d0285ef9.md
source_content_sha256: afbc0fb7973d3f52ed2058a81911e87181b9e64736e91051958fa0fe67bc76b8
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

没有功能也没关系

A.I.普里文

——爸爸，你知道吗，玛莎·西多洛娃的父母买了一台全新的“电子BZ-36”，有功能。而其他人也有这样的...
——什么，你的“电子BZ-30”不好用？
“它可以工作，但它没有任何功能：它只进行算术运算并描述根。”在九年级，我们有鼻烟和余弦、对数、指数函数。我无法随身携带 Bradis 桌子！
——没有功能也没关系。你想和我们一起成为一名数学家，所以你必须报到。您是否听说过关于粗面粉的泰勒级数？那就听听吧...

如何计算对数

首先，一点理论。你当然知道

$$\lim_{x \to 0} (1+x)^{1/x} = e.$$

如果 $x$ 接近 0，则该等式满足足够的精度。然后我们得到 $(1+x)^{1/x} \approx e$，或 $1+x \approx e^x$，由此而来

$$\ln(1+x) \approx x,$$

(1) 即，将数减一，得到其自然对数。如果数字很大呢？
很简单。毕竟

$$\ln a = \ln (a^{N/N}) = N \ln (a^{1/N}).$$

如果$N$足够大（具体值我们后面会讲），那么$a^{1/N} \approx 1$和$\ln (a^{1/N}) \approx a^{1/N} - 1$。

在机器上，如果$N=2^n$很容易计算$a^{1/N}$ - 您只需按$\sqrt{}$键$n$次。然后要找到原始对数，您需要减一并乘以相应的二：

$$\ln a = \ln a^{N/N} = N \ln a^{1/N} \approx (a^{1/N} - 1) \cdot N.$$

剩下的就是找到最优值$N$。由等式(1)可得

$$\ln (1+x)^{1/2} = \frac{1}{2} \ln (1+x) \approx \frac{1}{2} x \approx \ln \left(1 + \frac{1}{2} x\right),$$

那是

$$\left(1+x\right)^{1/2} = \sqrt{1+x} \approx 1 + \frac{1}{2} x.$$

要评估该等式的准确性，请使用泰勒公式*。前三个术语对我们来说就足够了：

$$f(a+x) = f(a) + xf'(a) + \frac{x^2}{2!} f''(a) + \dots$$

在我们的例子中$a=1$； $f(a+x) = \sqrt{1+x}$；

$$f(a) = \sqrt{a} = 1; f'(a) = \frac{1}{2\sqrt{a}} = \frac{1}{2};$$

$$f''(a) = -\frac{1}{4a^{3/2}} = -\frac{1}{4},$$

即$\sqrt{1+x} \approx 1 + \frac{x}{2} - \frac{x^2}{8}$；

$x \to 0$处的剩余项可以被丢弃。

因此，式(3)的误差约等于$x^2/8$。让我们设置误差值$\Delta = 5 \cdot 10^{-9}$。这些是不影响8位计算器读数的大多数值。

那么就很简单了：$\Delta = \frac{x^2}{8} = 5 \cdot 10^{-9}$，$x=2 \cdot 10^{-4}$。该值 $x$ 应提供最小误差。因此，使用公式$\ln 2 = 2^{12} (2^{1/2^12} - 1) = 4096 \times 0.0001691$计算得出的$ln 2$值等于0.693207，加上表中的0.693147。

然而，这里存在一个纯粹的“机器”效应：根提取（像其他计算一样）是在最后一个符号存在缺陷的情况下进行的，并且该误差每次都会增加。最终它与数量 $\frac{x^2}{8}$ 重叠，$\Delta$ 的公式变得不适用。此效果由 $n > 10$ 替代，其中 $n = \log_2 N$ 是根提取的次数。因此，在 BZ-30 微型计算器上使用相同的公式计算出相同的 $\ln 2$ 等于 0.69263...By-

*) 泰勒公式请参见上一期 Kwan 中 V. R. Pochuev 的文章。

⟦folio 21⟧

因此，在$n > 10$的情况下，建议接受$x = (3,5 \div 7) \cdot 10^{-4}$。

同样的ln 2，在同一台机器上在$n = 11$处计算，等于0.69304，相对误差为0.014%。

所以，我们找到了计算 ln $a$ 的算法：

$$\ln a = \frac{\ln a}{\ln 10} = \frac{\ln a}{2,303}.$$

对于$2 < a < 10$，表达式给出了相当准确的结果

$$\lg a \approx (a^{2/10} - 1) \cdot 445,$$

其中$445 \approx \frac{2^{10}}{\ln 10}$。

如何计算指数函数

为了计算函数 $e^x$，我们对 ln $a$ 获得的表达式进行变换。我们有 ln $a \approx N (a^{1/N} - 1)$，其中 $N$ 大，这意味着

$$a \approx \left( \frac{\ln a}{N} + 1 \right)^N.$$

进行替换$x = \ln a$，我们得到$a = e^x$，因此

$$e^x \approx \left( \frac{x}{N} + 1 \right)^N = \left( \frac{x}{N} + 1 \right)^{2n}.$$

为了在简单的计算器上快速使用这种对应关系，建议将其转化为整数算法，即不需要写下中间结果的算法。为此，求幂 $N$ （或者 $n$ 每平方次）并且必须通过重复命令序列来执行 $\times =$ 对于型号 B3-30 或

$$\dots \times 1 \times = \dots ,$$

适用于型号 B3-14。在这种情况下，结果始终保留在计算器的“临时存储器”中，因此不需要在每次迭代后重新输入机器。因此，求$e^x$的算法如下（下面的$n$是自然数，而且$N = 2^n$）：

$$x : 2^n + 1 \times =$$

函数 $10^{xn}$ 的计算不同之处仅在于，输入 $2^n$ 后，结果乘以 ln $10 \approx 2,303$。

剩下的就是函数$x^y$。让我们继续：

$$\ln (x^y) = y \ln x = Ny \ln (x^{1/N}) \approx Ny (x^{1/N} - 1).$$

因此，根据式（4）

$$x^y = e^{\ln (x^y)} \approx e^{Ny (x^{1/N} - 1)} \approx \left[ \frac{Ny (x^{1/N} - 1)}{N} + 1 \right]^N = [y (x^{1/N} - 1) + 1]^N.$$

式(5)用程序表示为：

如何计算三角函数

这里泰勒公式给出了正弦和余弦的两个方便的表达式

$$\sin x \approx x - \frac{x^3}{6} = \frac{(x^2 - 6)x}{6};$$

$$\cos x \approx 1 - \frac{x^2}{2} + \frac{x^4}{24} = 1 + \frac{(x^2 - 12)x^2}{24}.$$

第一个对于 $x \leq \frac{\pi}{4}$ 来说足够成立；对于第二个也可以这样说。值 $\frac{x^4}{24}$ 在 $x \geq \frac{\pi}{6}$ 处开始产生明显的影响，在 $x < \frac{\pi}{6}$ 处，您可以通过丢弃第三项来简化 cos $x$ 的公式：

$$\cos x \approx 1 - \frac{x^2}{2}.$$

$x \leq \frac{\pi}{4}$ 约束并不危险，因为三角函数总是可以简化为小于 $\frac{\pi}{4}$ 的参数。

* * *

正如您所看到的，只需一点数学知识 - 最简单的微型计算器就可以计算几乎所有“学校”函数。
