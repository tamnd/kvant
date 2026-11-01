---
id: 1978-11-integralom-po-schastlivyim-biletam-4a118026
issue: kvant_1978_11
year: 1978
number: "11"
title: 积分——还有幸运门票！
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 55
page_labels: 52-53
tag: DSYF
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 673a9a2172d5e993eae2813df88ac300b72e2c88961d4768979ab64d61a3067b
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/24_integralom-po-schastlivyim-biletam-4a118026.md
source_content_sha256: 5f56c8dd39ef40e15b21e14707705986703f349ca4afbb7e429e1857d19c2645
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

Integalom - 含私人门票！

编辑收到了我们的老读者B. Ivyakin 的来信。他在其中提出了以下问题：
“杂志上发表了好几篇关于幸运彩票的文章，但都没有得到最终的公式。虽然我很清楚，用简单的公式不可能设定出2n位幸运彩票的数量，但在我看来，这样的公式应该存在。我是对还是错？
显然我们不会回答这样模糊的问题。然而，鲍里斯很幸运——收到他的信后，我们立即收到了他问题的两个答案。
我们认为其他读者会对其中包含的公式感兴趣。
（我们提醒您，如果前三位数字之和等于后三位数字之和，则称为幸运彩票。）

幸运券很多吗？您多久遇到一次？

这个问题已经在我们的杂志上讨论过；结果发现，在 100 万张六位数号码（从 000,000 到 999,999）的彩票中，有 55,252 张是幸运彩票，即大约每 18 张彩票中就有一张是幸运彩票。

与数学家往常一样，一个更普遍的问题也得到了解决——关于 $C_{2n}$ 幸运 2n 位数字的数量（很清楚这个概念是什么；例如，0 035 120 115 是一个幸运的第十个数字）。 $C_{2n}$ 的显式公式尚未建立——仅获得了递推关系（«Kvant», 1976, No. 12, p. 68）。

但后来编辑收到了两封信。第一份由 M. Mnatsakanyan 和 A. Melikyan 在二月发送，第二份由 R. Aydagulov 在三月发送。两者都包含相同的 $C_{2n}$ 显式公式。这是这个奇妙的公式：

$$C_{2n} = \frac{1}{\pi} \int_{0}^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^{2n} dx. \tag{1}$$

有趣的是，这个公式是用完全不同的方法得到的：M. Mnatsakanyan 和 A. Melikyan 使用任意函数（即泛函分析），而 R. Aydagulov 使用三角和的方法（解析数论）。不幸的是，他们的证明虽然并不复杂，但仍然超出了学校数学的范围，无法在我们的期刊上发表。现在我们利用上面讨论的递推关系给出公式（1）的基本证明。让我们提醒他们。

为此，我们用 $P_m(s)$ 表示 $m$ 位数字 ($m=1, 2, 3,...$) 的数量，每个数字的数字之和等于 $s$。因此，$P_m(s)=0$位于$s<0$和$s>9m$。显然$P_m(0)=1$。

由于数字总和为 $s$ 的 $m$ 位数字是从数字总和为 $j$（其中 $s-9 \leq j \leq s$）的 $(m-1)$ 位数字获得的，因此我们添加数字 $s-j$，我们可以写

$$P_m(s) = \sum_{j=s-9}^{s} P_{m-1}(j).$$

这就是上面讨论的比例。将$s+1$与$s$一起代入其中，相减后可得

$$P_m(s+1) - P_m(s) = P_{m-1}(s+1) - P_{m-1}(s-9). \tag{2}$$

如何利用这个关系式来计算$P_m(s)$？看一下图 1。如果对于固定的$m$，所有$P_{m-1}(s)$（即所有$(m-1)$行）和第$m$行的至少一个元素$P_m(s_0)$已知，则公式（2）允许向右和向后移动，计算第$m$行的剩余元素行（解释一下！）。但对于任何人$m$

$$P_m(0) = 1 \tag{2'}$$

和

$$P_1(s) = \begin{cases} 1, \text{ если } 0 \leq s \leq 9, \\ 0, \text{ если } s < 0 \text{ или } s > 9. \end{cases} \tag{2''}$$

⟦folio 53⟧

因此，公式(2)、(2′)、(2″)允许我们计算所有数字$P_m(s)$。

让我们取任何部分 2n 位数字，并将最后 $n$ 位替换为其补码，最多为 9。然后我们得到一个 2n 位数字，其数字之和为 9n。很容易理解

$$C_{2n} = P_{2n}(9n).$$

式(3)可以计算$C_{2n}$。

为了证明(1)，我们设

$$\bar{P}_m(s) = \frac{1}{\pi} \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m \cos(9m-2s) x dx.$$

事实证明，

$$\bar{P}_m(s) = P_m(s).$$

从公式(3)、(5)和(4)可以得出(1)。因此，我们只需证明（5），只需检查数 $P_m(s)$ 是否满足等式（2）、（2′）、（2″）即可。将(4)代入(2)，得到对应关系

$$\frac{1}{\pi} \left\{ \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m \left[ \cos(9m-2s-2) x - \cos(9m-2s) \right] dx \right\} = \frac{1}{\pi} \left\{ \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m - 1 \left[ \cos(9m-9-2s-2) x - \cos(9m-9-2s+18) x \right] dx \right\},$$

平等匹配

$$\int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m - 1 \left[ \frac{\sin 10x}{\sin x} \right] \left[ \cos(9m-2s-2) x - \cos(9m-2s-11) x - \cos(9m-2s+9) x \right] dx = 0,$$

这是真的（很容易认为方括号中的三角表达式实际上也等于零）。

因此，满足$\bar{P}_m(s)$的循环对应关系(2)。仍有待检查归纳基础 (2′) 和 (2″)。第二个对应关系可以直接验证（例如，对于$m=1$和$s>9$，被积函数表达式被转换为$x$倍数的角度余弦之和），但是（2′）并不那么容易证明，我们将不得不采取解决方法。

让我们记住，与 (2′) 一起检查第 $m$ 行上的任何其他对应关系就足够了，例如 $\bar{P}_m(10m) = 0$ 这不再是三角变换的困难（但麻烦）练习，我们将把它留给读者。至此，式(5)的证明完毕。

细心的读者可能会问自己这样一个问题：公式（4）从何而来？当然，从公式上讲，我们可以假设我们以与“猜测”公式（1）相同的方式猜测了它。事实上，公式(4)和公式(1)一样，是从M. Mnatsakanyan和A. Melikayan的一封信中摘录出来的，即使用了最终的结果。毕竟，我们的证明方法与 P. Aydagulov 的方法以及 M. Mnatsakanyan 和 A. Melikayan 的方法不同，并不能使发现公式（1）成为可能，而只能让我们检查它。

总之，我们邀请读者以$k$为底，证明以下关于cil系统中cil数个数的公式（1）：

$$C_{2n}^k = \frac{1}{\pi} \int_0^{\pi} \left( \frac{\sin kx}{\sin x} \right)^2n dx.$$
