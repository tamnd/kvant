---
id: 1978-2-semenov-rukopis-naydennaya-v-saragose-d80ec67a
issue: kvant_1978_2
year: 1978
number: "2"
title: 萨拉戈萨发现的手稿
authors:
  - Семёнов С.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10-13
tag: UOMA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 28b8345a91984f5af9032afe043c78ababd1d005caae0796b38f454b15518c6c
prompt_sha256: draft-1
translated_from: content/ru/1978/02/articles/05_semenov-rukopis-naydennaya-v-saragose-d80ec67a.md
source_content_sha256: 1c8c00fe45870f97fccaf1e35be9bb942fa6ef6e7bbd4baff4af0a73c235df5e
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

在萨拉戈萨发现的手册

最近，在西班牙萨拉戈萨市的发掘过程中，考古人员发现了一座古代图书馆，属于曾经著名的苏阿斯贸易家族。在其他书籍中，有一本家族史。现在，我们将向读者介绍这份手稿的其中一个片段，因为它包含一个有趣的现代数学问题的表述。所以...

“已经到了一个谨慎的人应该照顾事业继承人和延续者的年龄，苏亚雷斯决定收留他的儿子阿隆索和洛佩斯，看看他们有多大能力取代他。儿子们没有出现，苏亚雷斯对他们说了以下的话：“孩子们！我打算代表你们每个人在十年内向一些可靠的企业捐款10万雷亚尔。这个生意每天会给大家带来20%的涨幅，而你只能管理这个数额，而不能管理资金本身。您可以在年底将这笔钱的一部分添加到您的资本中，其余的则可以随意使用。你的目标是在10年内花尽可能多的钱来满足你的需要，或者赚钱只是为了以后花。告诉我，你将如何管理你的收入？”

第一个回应是长子阿隆索，他以轻浮和奢侈而闻名于城外：“父亲！我会一下子花掉我所有的收入，因为我不

⟦folio 11⟧

我认为担心增加不属于我的资本是没有意义的！”

相反，洛佩兹是一位谦虚贤惠的青年。他这样回答他的父亲：“父亲，我会在九年里只做现在在家做的事情，并将我的收入加入到我的资本中。第十年，我将花费20%用于准备。我希望这将是一笔很大的数目，因为由于我的投资，资本将大幅增加。”

听到儿子们的回答，商人老爷子皱起了眉头，显然他对这个答案并不满意。当他的儿子们开始向他寻求建议时，他说：“我的孩子们，极度浪费和极度节俭一样不合理，但正确的解决办法是在这两个极端之间找到的。考虑到这一点，我会把一半的收入添加到资本中，照顾它的增长，一半用于我的需要。我发现，你们还不够聪明，而且没有能力取代我做生意。”第二天，苏亚雷斯命令儿子们准备出发，穿越比利牛斯山脉，前往遥远的巴黎，向巴黎著名科学家学习数学和其他科学……”

这里我们将翻译“历史文献”中的引述，因为我们感兴趣的问题已经被表述出来，甚​​至已经提出了三种不同的解决方案。首先，我们来比较一下这些解决方案的有效性。奥托（S）、阿隆索（A）和洛佩斯（L）在10年里花费的金额很容易计算（最好是他们自己能做，其余的可以使用本文的公式（2）和（3））。即，

$$S = \left( \left( 1 + \frac{1}{10} \right)^{10} - 1 \right) 10^5 \approx 159374 \text{ реал},$$
$$A = 2 \cdot 10^5 = 200000 \text{ реал}$$
$$L = \frac{1}{6} \left( \left( 1 + \frac{1}{5} \right)^5 \right)^2 10^5 \approx 103169 \text{ реал}.$$

比较结果是矛盾的。结果节俭的洛佩兹提出了最坏的解决方案，而轻浮的阿隆索则比他谨慎而经验丰富的父母更好地处置自己的收入！确保看似合理的论点最终证明是骗人的。也许我们的最佳解决方案与提出的所有三个解决方案不同？让我们试着弄清楚这一点。

因此，让我们通过$x_k$、$k=0, \dots, N$表示第$k$年末（从第一次存款的那一刻算起）的资本金额（在没有利息和可能的额外捐款之后）。在我们的问题中，$N=10$，初始贡献的值为$x_0=10^5$。在$(k+1)$年，价值$ax_k$将接近（我们有$a=\frac{1}{5}$），如果该价值的$\lambda_k$份额在$(k+1)$年末添加到资本中，那么该年的增量为$x_{k+1}-x_k=\lambda_k ax_k$（$k=0, \dots, N$）。 (1) 近似$(1-\lambda_k)ax_k$的剩余部分将被花费。

我们影响资本增长过程的能力，或者换句话说，控制这个过程的能力，是选择一个向量的能力——一组有序的数字$\bar{\lambda} = (\lambda_0, \dots, \lambda_{N-1})$，$0 \leqslant \lambda_i \leqslant 1$。这样的向量将进一步称为控制$\bar{\lambda}$，并将完全确定目标函数$F$的值 - $N$年内花费的总金额：

$$F(\bar{\lambda}) = (1-\lambda_0)ax_0 + (1-\lambda_1)ax_1 + \dots + (1-\lambda_{N-1})ax_{N-1}.$$ (2) 问题是找到最好的最优控制$\lambda^{\text{опт}}$，即这样的控制$\lambda^{\text{опт}}$使得对于任何其他控制$\bar{\lambda}$

$$F(\bar{\lambda}) \leqslant F(\bar{\lambda}^{\text{опт}}).$$

让我们记住，最优控制是由阿隆索$(0, \dots, 0)$、洛佩兹-$(1, \dots, 1, 0)$和可敬的商人-$\left(\frac{1}{2}, \dots, \frac{1}{2}\right)$提出的。

也许读者的外在印象是，只有那些继承了丰厚遗产的人才需要这样的管理宝藏？当然不是！这是另一个例子。该农场饲养布莱克堡嘴唇。我们将用$x_k$表示农场的数量，其中$k=0, 1, \dots, N$是年份编号（我们对农场在未来的命运感兴趣）

⟦folio 12⟧

N 年）。 $(k+1)$年年初的后代是$ax_k$（其中$a > 0$是已知数字），该后代的$\lambda_k$份额留在农场，其余的被送到收获森林。因此，关系式（1）成立，$N$年获得的皮张数由式（2）表示。正如你所看到的，这里我们也有一个受控过程，每个时刻$k = 0, 1, \dots, N$的状态由值$x_k$来表征，我们可以通过从“控制区域”（在本例中为段[0, 1]）中选择控制动作$\lambda_k$来影响该过程的进程。任务是找到一种控制方法，以尽可能最好的方式实现既定目标 - 目标函数 $F$ 将达到最大值。当研究工厂的生产问题时（这里$k$是一个完整的生产周期或计划的月份等），当描述几个串联的化学反应器的操作时（$k$是反应器编号）等，类似的“离散时间”中发生的过程的“最优控制”问题也会出现。

开发解决此类问题的方法的数学分支称为最优控制理论。在过去的二十年里，这一理论已经转变为一门强大的现代数学科学，其深刻的理论成果和解决过程控制应用问题的效率令人印象深刻。这一数学思想方向的发展与 L. S. Pontryagin、R. Bellman、V. G. Boltyansky、R. V. Gamkrelidze、E. F. Mishenko、N. N. Krasovsky 等著名数学家的名字有关。然而，我们不会介绍这些作者创建的最优控制的一般理论，而是使用初等数学来研究我们的问题。

我们将式（1）转化为$x_{k+1} = (1 + a\lambda_k)x_k$，$(k = 0, \dots, N-1)$的形式。 (3)

(3)逐项$k = 0, \dots, n-1$的变量，我们以显式形式得到$x_n$对控制$\bar{\lambda} = (\lambda_0, \dots, \lambda_{N-1})$的依赖关系
$$x_n = (1 + a\lambda_0)(1 + a\lambda_1) \dots (1 + a\lambda_{n-1})x_0.$$ (4)

命题 I. 设 $\bar{\lambda} = (\lambda_0, \dots, \lambda_{i+1}, \dots, \lambda_{N-1})$ 为某个控制，$0 \leq i \leq N-2$、$\lambda_i < \lambda_{i+1}$，并令控制 $\bar{\lambda}$ 与 $\bar{\lambda}$ 的不同之处在于数字 $\lambda_i$ 和 $\lambda_{i+1}$ 的排列。然后$F(\bar{\lambda}) > F(\bar{\lambda})$。

为了证明这一点，只要追踪当数字$\lambda_i$和$\lambda_{i+1}$转移时，和(2)的项如何变换就足够了。根据公式(4)，$k \leq i-1$下的项$(1 - \lambda_k)ax_k$根本不依赖于$\lambda_i$和$\lambda_{i+1}$，并且非常昂贵并且不会随着这样的重新排列而改变。根据公式 (4)，项 $(1 - \lambda_k)ax_k$ 和 $k > i+1$ 具有以下形式：
$$(1 - \lambda_k)ax_0(1 + a\lambda_0) \dots (1 + a\lambda_{i+1}) \times (1 + a\lambda_{i+1}) \dots (1 + a\lambda_{k-1}),$$
因此，在传输数字$\lambda_i$和$\lambda_{i+1}$时也不会改变。因此，我们只需考虑其余项的总和：
$$(1 - \lambda_i)ax_i + (1 - \lambda_{i+1})ax_{i+1} = (1 - \lambda_i)ax_i + (1 - \lambda_{i+1})(1 + a\lambda_i)ax_i = ax_i[(2 - \lambda_i - \lambda_{i+1}) - a\lambda_i\lambda_{i+1}] + a\lambda_i.$$

$x_i > 0$的值与$\lambda_i$和$\lambda_{i+1}$无关，括号内的表达式传递时不改变，返回方括号内的第二项。因此，$F(\bar{\lambda}) > F(\bar{\lambda})$。

命题二。让 $\bar{\mu}$ 成为某种控制。那么对于任何$n = 0, \dots, N$，存在一个最大控制$\bar{\mu}^{(n)} = (\mu_0^{(n)}, \dots, \mu_N^{(n)})$，使得对于任何$i < n$、$2^\circ F(\bar{\mu}^{(n)}) \geqslant F(\bar{\mu})$，$1^\circ \mu_n^{(i)}$为0或1。

让我们用数学归纳法来证明这个说法。对于$n = 0$，这条语句是显而易见的，因为我们可以放入$\bar{\mu}^{(0)} = \bar{\mu}$，并且语句$1^\circ$和$2^\circ$将自动满足。

假设对于$n = k$，控制异常存在$\bar{\mu}^{(k)} = (\mu_0^{(k)}, \dots, \mu_N^{(k)})$。让我们考虑一个变量 $t$ 的函数 $y(t)$，其定义是线段 [0, 1]，由以下公式给出
$$y(t) = F(\mu_0^{(k)}, \dots, \mu_{k-1}^{(k)}, t, \mu_{k+1}^{(k)}, \dots, \mu_N^{(k)}).$$
从公式（2）和（4）可以立即清楚地看出$y(t)$是$t$的线性函数，即
$$y(t) = At + B$$
对于一些$A$和$B$。请注意，区间 [0, 1] 上的线性函数在 $A < 0$ 时在 0 处达到最大值，在 $A > 0$ 时在 1 处达到最大值，在 $A = 0$ 处它是常数函数。经过-

⟦folio 13⟧

现在就把它放下
$$\mu_k^{(k+1)} = \begin{cases} 0, & A \leqslant 0, \\ 1, & A > 0, \end{cases}$$

以及$\mu_k^{(k+1)} = \mu_i^{(k)}$位于$i \neq k$、$0 \leqslant i \leqslant (N-1)$。对于$n = k + 1$，控制$\overline{\mu}^{(k+1)}$满足条件$1^\circ$和$2^\circ$。事实上，根据指示的假设，数字$\mu_k^{(k+1)}$和$i < k$是零或一，而$\mu_k^{(k+1)}$根据定义是零或一。此外，由于根据数字 $\mu_k^{(k+1)}$ 的定义，对于任何 $t$、$0 \leqslant t \leqslant 1$
$$y(t) \leqslant y(\mu_k^{(k+1)}),$$
然后$F(\overline{\mu}^{(k+1)}) \geqslant F(\overline{\mu}^{(k)})$。根据指示性假设$F(\overline{\mu}^{(k)}) \geqslant F(\overline{\mu})$，因此$F(\overline{\mu}^{(k+1)}) \geqslant F(\overline{\mu})$。证明完毕。

现在让我们在所有控件中突出显示一些特殊的、最简单的类型。即，考虑一个控制$\overline{\theta}^{(m)}$使得
$$\theta_i^{(m)} = \begin{cases} 1 & \text{при } i < m, \\ 0 & \text{при } i \geqslant m, \end{cases}$$
对于一些$m$，$0 \leqslant m \leqslant N$。这种类型的一组控件（我们将进一步称它们为逐步式）包含一个 $(N+1)$ 元素。事实证明，在我们的问题中，在步骤中寻找最优控制就足够了。

定理。对于任何控制$\overline{\lambda}$，都有一个控制$\overline{\omega}$使得$F(\overline{\omega}) \geqslant F(\overline{\lambda})$。

事实上，根据命题 II，存在一个控制 $\overline{\mu} = (\mu_0, \dots, \mu_{N-1})$，使得对于任何 $i = 0, \dots, N-1$ 和 $F(\overline{\mu}) \geqslant F(\overline{\lambda})$，$\mu_i$ 为零或一。此外，我们注意到，如果数字$\mu_0, \dots, \mu_{N-1}$中有一个0，那么通过将其与它后面的数字交换，我们不会根据命题I减少目标函数$F$的值。通过这种排列，所有零都可以移动到定义控制的集合的末尾，即转到某个步骤控制$\overline{\omega}$，并且将满足不等式$F(\overline{\omega}) \geqslant F(\overline{\mu}) \geqslant F(\overline{\lambda})$。定理已被证明。

现在让我们在步进控制中选择最佳的一个。由式(2)和(4)可知
$$F(\overline{\theta}^{(m)}) = (N - m)a(1 + a)^m x_0.$$
震级
$$C_m = \frac{F(\overline{\theta}^{(m+1)})}{F(\overline{\theta}^{(m)})} = (1 + a)\left(1 - \frac{1}{N - m}\right)$$
当$m$发生时减少。让我们用$M$表示第一个大于或等于零的整数和$N-1 - \frac{1}{a}$。
那么，由于数$C_m$的定义和数$M$的选择，不等式
$$C_0 > C_1 > \dots > C_{M-1} > 1 \geqslant C_M > C_{M+1} > \dots > C_{N-1}.$$
因此，
$$F(\overline{\theta}^{(0)}) < \dots < F(\overline{\theta}^{(M)}) \geqslant F(\theta^{(M+1)}) > F(\overline{\theta}^{(M+2)}) > \dots > F(\overline{\theta}^{(N)}).$$
因此，可以选择控制$\overline{\theta}^{(M)}$作为最佳控制。
让我们从“古抄本”回到我们的问题。对于她$N = 10$、$u = \frac{1}{5}$和$M = 4$。因此，控制$\overline{\theta}^{(4)} = (1, 1, 1, 1, 0, \dots, 0)$将是最优的，当以这种方式选择控制时，目标函数的值（十年内花费的总金额）为
$$F(\overline{\theta}^{(4)}) = \left(1 + \frac{1}{5}\right)^4 \times 10^5 \frac{6}{5} \approx 248832 \text{ реал.}$$

因此，我们的主要英雄提出的问题解决方案确实不是最优的。请注意，控制 $\overline{\theta}^{(5)}$ 也是最优的，因为零点通常是在步骤中选择的，而不是唯一的方式。

问题1. $a$和$N$的哪些条件可以保证步骤间最优控制的唯一性？

问题 2. 对于我们的问题，最优控制一定是逐步的吗？

问题 3. 找到最小的年数$N > 10$，使得节俭的洛佩兹$(1, \dots, 1, 0)$的管理仍然比浪费的阿隆索提出的管理$(0, 0, \dots, 0)$更有利可图。
