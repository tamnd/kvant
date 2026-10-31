---
id: 1973-5-ryivkin-periodicheskie-funktsii-1eb5e13d
issue: kvant_1973_5
year: 1973
number: "5"
title: 周期函数
authors:
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 41
page_labels: 38-39
tag: 2AAY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 68d7d81acd9f32b2e04c601926d9206086118f2c05b2d8088f37972130597a8a
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/08_ryivkin-periodicheskie-funktsii-1eb5e13d.md
source_content_sha256: adf87a46f9e8b5062c38c196cc97f30b1b911651c28a4cf80153e0ffca2b3285
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

周期函数

定义

你们显然都知道什么是周期函数。然而，为了研究其性质，仍然有必要给出其严格的定义。事实证明，这并不是那么容易做到的。例如，这里有一个定义和它的“后果”。

定义。如果存在一个数字 $T \neq 0$，且对于该函数$f(x+T) = f(x)$ 域中的 $x$ 的所有值，则称函数 $y = f(x)$ 为周期性函数。

现在让我们证明引理1：

如果$T > 0$是函数$f(x)$的周期，则$-T$可以是该函数的周期。

证明包括写出一系列等式：

$$f(x-T) = f[(x-T)+T] = f(x).$$

事实上，$T$是函数$f(x)$的周期，因此，如果将其添加到参数$x-T$，则函数的值不会改变（第一个相等）。剩下的就是打开括号并得到$f(x)$。

在继续阅读之前，请尝试找出该证明中的错误。

这里进行的所有推理都是正确的。只是它们并不意味着$-T$是$f(x)$的周期。如果您还没有发现证明中的错误，请考虑函数$\sin(\sqrt{x+2\pi})^2$。它的域是$x \geq 0$，并且对于来自该域的任何$x$

$$\sin(\sqrt{x+2\pi})^2 = \sin(\sqrt{x})^2,$$

也就是说，从制定的定义来看，$2\pi$就是周期

功能。同时，$-2\pi$将不是它的句点，因为左侧$x = 0$函数$\sin(\sqrt{x})^2$未定义，例如$\sin(\sqrt{0-2\pi})^2$不存在。

现在证明的错误也很明显了：在考虑值$f(x-T)$之前，需要确定这个值存在，而事实并非如此。这就是为什么可以构造一个反驳例子。

为了证明引理 1，需要对周期函数进行不同的定义。

定义 1. 定义至少一个点的函数 $f(x)$ 称为周期函数，如果存在数字 $T \neq 0$（称为周期），使得对于该函数定义域中的任何 $x$

a) 数字$x-T$和$x+T$也属于其定义域：

b) $f(x+T) = f(x)$。

有了这个定义，上述引理1的证明就成立了。

使用周期函数的定义，您可以确定特定函数是否是周期函数。

例1. 证明函数$y = \sin lg x$不是周期函数。

很容易确定这个事实 - 只要注意到这个函数是为所有 $x > 0$ 定义的，而不是为所有 $x \leq 0$ 存在的。因此，无论我们选择$T > 0$，我们的函数都将定义在$x = T/2$，并且不会

⟦folio 39⟧

定义在$x = \frac{T}{2} - T = -\frac{T}{2}$，即不是周期性的。

例 2. 证明该函数
$$\cos x + \sin (x \sqrt{2})$$
- 不是周期性的。

设一个数$T \neq 0$使得
$$\cos (x + T) + \sin [\sqrt{2} (x + T)] \equiv \cos x + \sin (\sqrt{2} x)$$
对于每个人$x$。让我们将$x = 0$和$x = -T$放入这个恒等式中；那么我们得到以下两个等式：
$$\begin{cases} \cos T + \sin (\sqrt{2} T) = 1 & (1) \\ \cos T - \sin (\sqrt{2} T) = 1. & (2) \end{cases}$$
从(1)和(2)的对应关系可以得出$\cos T = 1$和$\sin (\sqrt{2} T) = 0$，从而得到$T = 2\pi k$和$T = \pi n/\sqrt{2}$。将这些值相等（$T \neq 0$，因此$k \neq 0$，$n \neq 0$），我们找到$\sqrt{2} = n/2k$，即$\sqrt{2} - \text{рациональное число}.$。由此产生的矛盾证明函数$\cos x + \sin (\sqrt{2} x)$不是周期性的。

例 3. 证明函数 $y = 3\sin x + \sin 2x$ 是周期函数。

显然他们是这样推理的。设 $T$ 为该函数的周期。然后平等
$$3\sin (x + T) + \sin 2 (x + T) = 3\sin x + \sin 2x$$
必须满足所有$x$，包括$x = 0$。利用这个，我们得出 $T$ 的方程：
$$3\sin T + \sin 2T = 0,$$
（即$(3 + 2\cos T) \sin T = 0$。由于括号内的表达式不会归零，$\sin T = 0$，$T = k\pi$。
然而，以这种方式找到的值$T$根本不是函数的周期。通过从对应（1）到对应（2），我们放松了对（1）中包含的$T$的限制。毕竟，第一个对应关系必须对所有 $x$ 有效，而第二个对应关系则确保其仅对 $x = 0$ 有效。因此，我们已经确定所考虑的函数的所有周期都包含在 $x = k\pi$ 形式的数字中。然而，这并不意味着所有这种类型的数字都是它的句点。

接下来，因为
$$3\sin \frac{\pi}{2} + \sin \left(2 \cdot \frac{\pi}{2}\right) = 3,$$
$$3\sin \left(\frac{\pi}{2} + \pi\right) + \sin 2 \left(\frac{\pi}{2} + \pi\right) = -3,$$
即$f\left(\frac{\pi}{2}\right) \neq f\left(\frac{\pi}{2} + \pi\right)$，则n将不是函数的周期。数字$2\pi$和$2k\pi$形式的所有数字都是它的句点，通过直接验证很容易验证。

主要时期

定义2. 周期函数$f(x)$的最小正周期称为基本周期。

一些比较细心的读者可能会立即反对：在给某个东西命名之前，最好先确定某个对象的存在。在证明了周期函数的斯诺性质之后，我们将研究主周期的存在性。

引理2. 如果$T_1$和$T_2$是函数$f(x)$和$T_1 + T_2 \neq 0$的周期，则$T_1 + T_2$是$f(x)$的周期。

证明。让$y = x + T_1$。由于$T_1$是函数$f$的周期，所以mo$f(y)$与$f(x)$同时存在。 $T_2$ 也是周期$f$。因此，$f(y + T_2)$也存在$f(y + T_2) = f(y) = f(x + T_1) = f(x)$，即$f(x + T_1 + T_2) = f(x)$。

根据条件，$T_1 + T_2 \neq 0$。所以
