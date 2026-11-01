---
id: 1990-1-bashmakov-o-postulate-bertrana-1dfbbf88
issue: kvant_1990_1
year: 1990
number: "1"
title: 关于伯特兰公设
authors:
  - Башмаков М. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 61
page_last: 64
page_labels: 59-62
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0ca58409faeeb32ab873fd2a96024c0149cf280d08f4a55e0c123f1d742619f5
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/14_bashmakov-o-postulate-bertrana-1dfbbf88.md
source_content_sha256: 3e4c9002bab11faa20f58765f1b3761a683d7ad1b84653ffc8f9b2dbaad184e9
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 59⟧

---
running_head:
folio:
---

关于公设
伯特兰
物理和数学科学博士
M·巴什马科夫

在帕夫努蒂·利沃维奇·切比雪夫的 69 部著作中，有两部著作对数论的发展起到了特别重要的作用。他年轻时写的《论确定不超过给定值的素数的个数》和《论素数》等著作，致力于解决数论中最困难的问题——素数的分布。

其中第二个包含不等式，可以非常准确地计算不超过给定值的素数的数量。

读者可能想知道，对数与素数有什么关系？这就是切比雪夫的优点，他指出了如何

但是要估计自然数列给定段中素数的数量，特别是，已经证明了以下事实：在 x 和 2x 之间（其中 x > 1）总是至少有一个素数。这个说法是法国著名数学家贝特朗提出的，他在现有的素数表中对此进行了测试，但无法证明，并接受了这个借口。

我们将追溯切比雪夫导致他做出这些估计的主要思想，然后提出一系列问题，其解决方案将使读者（相当熟悉对数的性质）能够重建切比雪夫的伯特兰赦免证明，并获得不超过给定值的素数数量的不等式。

读者可能想知道，对数与素数有什么关系？这就是切比雪夫的优点，他指出了如何

⟦folio 60⟧

---
running_head:
folio:
---

在研究整数问题时，您可以使用一般分析函数 - 根、对数。如果我们想找出$n$到$2n$区间上是否至少存在一个素数，那么我们可以这样进行：

1) 提出实参$x$的某个函数$y=f(x)$，当$x$遍历相邻素数之间的段时，该函数不会改变其值，并且在传递素数时会取更多值；

2) 证明相对函数$f$的不等式，这将有助于准确估计其增长率。

对于以这种方式选择的函数，当且仅当函数从$n$移动到$2n$时返回$f$时，即$n$和$2n$之间至少有一个素数，差值$f(2n)-f(n)$才是正数。

第一个条件很容易满足。我们可以考虑以下函数：让我们用$\pi(x)$表示不超过$x$的素数数量。

例如，$\pi(1)=0$（1不被视为质数）、$\pi(3)=2$、$\pi(9)=4$、$\pi(9,5)=4$、$\pi(10,9)=4$、$\pi(11)=5$等。

当然，如果我们能证明

$$\pi(2x)-\pi(x)>0,$$

我们将证明，伯特兰将采取行动，因为

$$\pi(2x)-\pi(x)$$

精确表示$x$和$2x$之间包含的素数个数。然而，要给出$\pi(x)$的精确估计并不容易，为了解决这个问题，切比雪夫建议考虑一个函数，当传递时，它会返回一个素数，而不是像$\pi(x)$那样，但更错误。他研究了这个函数

$$\theta(x)=\log 2+\log 3+\log 5+\ldots=\sum_{p\leqslant x}\log p$$

（$\theta(x)=0$ 于 $x<2$）

- 所有素数的对数之和，不超过前一个，伯特兰过程等价于以下不等式：

$$\theta(2x)-\theta(x)>0.$$

(1)

为了估计函数$\theta(x)$并证明(1)，切比雪夫使用了辅助函数$T(x)$：

$$T(x)=\log 2+\log 3+\ldots=\sum_{n\leqslant x}\log n.$$

函数$T(x)$是所有整数的乘积的对数，不超过它们。切比雪夫证明函数 $\theta(x)$ 和 $T(x)$ 通过以下显着的恒等式相关：

$$T(x)=\theta(x)+\theta(\sqrt{x})+\theta(\sqrt[3]{x})+\ldots$$

$$+\theta\left(\frac{x}{2}\right)+\theta\left(\sqrt{\frac{x}{2}}\right)+\theta\left(\sqrt[3]{\frac{x}{2}}\right)+\ldots$$

$$+\theta\left(\frac{x}{3}\right)+\theta\left(\sqrt{\frac{x}{3}}\right)+\theta\left(\sqrt[3]{\frac{x}{3}}\right)+\ldots$$

(2)

其中，当参数 $\sqrt[k]{x/m}$ 小于 2 并且值 $\theta(\sqrt[k]{x/m})$ 变为零时，对象的总和。函数 $T$ 自欧拉时代起就为人所知，早在切比雪夫之前，不等式就已被证明，可以相当准确地估计 $T$ 的增长阶数。

从这些不等式中，切比雪夫获得了 $\theta(x)$ 的不等式

$$Ax+v_1(x)<\theta(x)<\frac{6}{5}Ax+v_2(x),$$

(3)

其中 $A$ 是某个常数，大 $x$ 的附加项 $v_1(x)$ 和 $v_2(x)$ 显着小于 $x$。这已经足以证明$x$的不等式$\theta(2x)-\theta(x)>0$大于某些$x_0$（在切比雪夫$x_0=160$中）。对于$x$，较小的$x_0$，还算可以

*) 这里以及下面的所有地方，对数均以 $e$ 为底 - 这些就是所谓的自然对数。

⟦folio 61⟧

---
running_head:
folio:
---

人类思想的进一步发展导致了这样的结果：对于$x \geq 48$$\theta\left(\frac{9}{8}x\right) - \theta(x) > 0$，即从指定位置开始，在$x$和$\frac{9}{8}x$之间，总是至少有一个素数。

您可以通过解决下面的问题 1-5 来更详细地理解切比雪夫的论点。

为了用$\theta(x)$来表达$T(x)$，可以方便地引入另一个辅助函数。令$p^{a_p}$为$p$不超过$x$的最高阶。让我们像这样定义函数$\psi$：

$$\psi(x) = a_2 \log 2 + a_3 \log 3 + a_5 \log 5 + \dots = \sum_{p \leq x} a_p \log p.$$

显然$\psi(x)$是所有整数的最小公倍数的对数，不超过$\psi$。问题1.证明

$$T(x) = \psi(x) + \psi\left(\frac{x}{2}\right) + \psi\left(\frac{x}{3}\right) + \dots$$

现在我们需要连接函数$\psi$和$\theta$。

问题2.证明

$$\psi(x) = \theta(x) + \theta\left(\sqrt{x}\right) + \theta\left(\sqrt[3]{x}\right) + \theta\left(\sqrt[4]{x}\right) + \dots$$

解决了问题 1 和 2 后，您还将建立实数 $e$，对于所有自然数 $n$

$$\left(\frac{n+1}{e}\right)^n < n! < n\left(\frac{n}{e}\right)^n$$

（其中$n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$）。

为了解决这个问题，证明每个数字是有用的

$$a_n = \left(\frac{n+1}{n}\right)^n$$

每个数字的变量

$$b_n = \left(\frac{n+1}{n}\right)^{n+1};$$

由此可见，存在一个数字 $e$ 大于所有 $a_n$ 且小于所有 $b_n$。这就是我们正在寻找的数字（我们的杂志 1971 年第 1 期的最后一页讨论了它的一些属性）。

解决了这个问题后，您还将获得 $T(x)$ 的不等式：

$$(x-1)(\log(x-1) < T(x) < (x+1)\log x-x).$$

切比雪夫本人使用了更精确的不等式。

根据$T(x)$的估计，切比雪夫获得$\psi(x)$的估计，然后获得$\theta(x)$的估计。

为了用 $T$ 表达 $\psi$，切比雪夫替换了以下内容。我们来考虑一下金额

$$S = T(x) - T\left(\frac{x}{2}\right) - T\left(\frac{x}{3}\right) - T\left(\frac{x}{5}\right) + T\left(\frac{x}{30}\right).$$

让我们使用问题 1 的结果并将这个总和简化为以下形式：

$$S = A_1 \psi(x) + A_2 \psi\left(\frac{x}{2}\right) + A_3 \psi\left(\frac{x}{3}\right) + \dots$$

问题 4. 检查系数 $A_1, A_2, A_3$, ... 以 30 为周期变化，并且对于前 30 个值$n$，系数 $A_n$ 形成以下序列：

1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, 0, -1, 0, 1, -1, 1, -1, 0, 0, 1, -1, 0, 0, 0, 0, 1, -1, 1.

由此我们可以看出，和$S$被写成交替级数$S = \psi(x) - \psi\left(\frac{x}{6}\right) + \psi\left(\frac{x}{7}\right) - \psi\left(\frac{x}{10}\right) + \psi\left(\frac{x}{11}\right) - \dots$。

由于 $\psi$ 是非减函数，

$$S = \psi(x) - \left(\psi\left(\frac{x}{6}\right) - \psi\left(\frac{x}{7}\right)\right) - \left(\psi\left(\frac{x}{10}\right) - \psi\left(\frac{x}{11}\right)\right) \dots \leqslant \psi(x).$$

类比诺

$$S = \psi(x) - \psi\left(\frac{x}{6}\right) + \left(\psi\left(\frac{x}{7}\right)\right) - \psi\left(\frac{x}{10}\right) + \dots \geqslant \psi(x) - \psi\left(\frac{x}{6}\right).$$

从（2）我们立即获得$\psi$的不等式，从而估计其大小，因为我们知道$T$的不等式并获得$\psi$到$S$的估计，即$T$值的组合。该估计将具有以下形式：$\psi(x) \geqslant A_1(x) + \omega_1(x)$，其中$\omega_1$比$x$增长得更慢，即

$$\lim_{x \to \infty} \frac{\omega_1(x)}{x} = 0.$$

要从上面得到估计，您需要去掉 $\psi\left(\frac{x}{6}\right)$。将不等式（6）应用于$\frac{x}{6}, \frac{x}{6^2}, \frac{x}{6^3}$等并相加，我们发现$\psi(x) \leqslant A_2x + w_2(x)$类型的$\psi(x)$不等式，其中$w_2$比$x$增长得更慢。

问题 5. 证明

$$\psi(x) - 2\psi\left(\sqrt{x}\right) \leqslant \theta(x) \leqslant \psi\left(\sqrt{x}\right).$$

由此我们已经获得了必要的估计（3）。

切比雪夫的结果不仅表明伯特兰的行为是正确的，更重要的是，它们产生了不等式，可以很好地估计函数$\pi(x)$：

$$c_1 \frac{x}{\log x} < \pi(x) < c_2 \frac{x}{\log x},$$

其中 $c_1$ 和 $c_2$ 为非正数。

⟦folio 62⟧

---
running_head:
folio:
---

常量*)。您可以通过解决以下问题来证明这种不等式。

问题 6. 证明
$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$

*) 这里的对数可以是任何底数 $a$，大于一；从 $a$ 仅取决于常量的值 $c_1$ 和 $c_2$， 因为 $\log_b x$ 获得自 $\log_a x$ 乘以一个常数 $\log_a b$。使用自然对数更自然，因为它是函数 $x/\log_e x$ 相等的 $\pi(x)$ 在逃 $x$， IE。 $$\lim_{x \to \infty} \frac{\pi(x)}{x/\log_e x} = 1.$$ 这在很久以后才被证明，从切比雪夫本人的工作中只能得出以下结论： $\pi(x)$ 到 $x/\log_e x$ 介于 0.921 和 1.106 之间，如果极限为 $x \to \infty$ 存在，则它等于一。

水面上的波浪和 N. Roerich 的《海外客人》

（参见第 24 页开头）

那么角度$\alpha$呢？所有受访者都一致认为它位于$90^\circ < 2\alpha < 180^\circ$范围内（图中的船很典型）。因此，
$$\frac{\sqrt{2}}{2} = \sin 45^\circ < \sin \alpha < \sin 90^\circ = 1.$$ (7)

现在我们已经具备了估算船速和表面波的一切条件。

结果

将(5)、(6)、(7)中的$h$、$\lambda$、$\sin \alpha$代入式(1)、(2)，得
$$v \geq \sqrt{\frac{2 \cdot 9,8 \text{ m/c}^2 \cdot 0,26 \text{ m}}{1 \div \sqrt{2}/2}} \approx 5,1 \div 7,25 \text{ m}^2/\text{c}^2 \approx 2,25 \div 2,7 \text{ m/c},$$ (8)

$$u = \sqrt{\frac{9,8 \text{ m/c}^2 \cdot 0,34 \text{ m}}{2\pi}} \approx 0,7 \text{ m/c}.$$ (9)

现在我们惊讶地发现对应关系（8）和（9）与不等式（4）不相容。事实上，从船头波浪的高度来看，船的漂浮速度$v$与2.25 m/s没有什么不同，如果我们关注图中几乎同心的波浪的圆形表面，船的速度应该远小于这些波浪的速度$u = 0,7 \text{ m/c}$，而后者已经小于$v$。

有了一定的外观，你会在其他艺术作品中发现许多类似的物理误差（显然，这是由于他有自己的一套规则和法则）。那么你不仅可以爱不释手，获得审美上的满足，还可以和你的小弟弟一起谈论物理定律，用非常吸引人的插图。
