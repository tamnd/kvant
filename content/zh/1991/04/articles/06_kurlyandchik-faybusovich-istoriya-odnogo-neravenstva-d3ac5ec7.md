---
id: 1991-4-kurlyandchik-faybusovich-istoriya-odnogo-neravenstva-d3ac5ec7
issue: kvant_1991_4
year: 1991
number: "4"
title: 一种不平等的故事
authors:
  - Курляндчик Л. Д.
  - Файбусович А.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14-18
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a4e1d00c95350ca7f0c08be0dd8da5d31cd02b3f8e91cddc805c73de30677cea
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/06_kurlyandchik-faybusovich-istoriya-odnogo-neravenstva-d3ac5ec7.md
source_content_sha256: 91483fcc90a0097db1297611af9ead109a0b438142ab5a35a3a8e8499e8c3d6b
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 14⟧

---
running_head:
folio:
---

我们来谈谈不平等
$$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_{n-1}}{x_n+x_1} + \frac{x_n}{x_1+x_2} \geq \frac{n}{2}),$$
该问题由美国数学家夏皮罗于1954年在《美国数学月刊》上首次提出。这个问题引起了世界各地许多数学家的关注。一位北方学童（读者«Kvant»！）Volodya Drinfeld 对其解决方案做出了非常重要的贡献，他后来成为菲尔兹奖获得者**）。
1958年，剑桥大学的莫德尔教授证明了$n \leqslant 6$的不等式。面对$n=7$情况的根本困难，他推测$n=7$的不等式不成立。奇怪的是，如果他设法证明他的假设，即找到七个数字 $x_1, x_2, \dots, x_7$ ，其总和将小于 7/2，那么立即可以得出，不等式对于所有 $n \geqslant 7$ 并不成立。让我们证明一下。首先我们介绍一下记号
$$f_n(x_1, x_2, \dots, x_n) = \frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2},$$
这将为我们节省很多空间。然后我们注意到
$$f_n(x_k, x_{k+1}, \dots, x_n, x_1, x_2, \dots, x_{k-1}) = f_n(x_1, x_2, \dots, x_n),$$
也就是说，如果围绕周期重新排列不等式左侧包含的数字，则不等式左侧不会改变。因此，这种不平等和其他不平等，
*) 本文中的所有变量均为非负且分母为正。
**) «Kvant» 在 1990 年第 6 期谈到了菲尔兹奖及其获奖者。

具有这种性质的称为循环的。
检查一下
$$f_{n+2}(x_1, x_2, \dots, x_n, x_1, x_2) = f_n(x_1, x_2, \dots, x_n) + 1.$$
由此可见，如果
$$f_n(x_1, x_2, \dots, x_n) < \frac{1}{2} n,$$
那
$$f_{n+2}(x_1, x_2, \dots, x_n, x_1, x_2) < \frac{1}{2} (n+2).$$
现在检查一下
$$f_{n+1}(x_1, \dots, x_i, x_i, \dots, x_n) - f_n(x_1, x_2, \dots, x_n) - \frac{1}{2} = \frac{(x_i - x_{i-1})(x_i - x_{i+1})}{2x_i(x_i + x_{i+1})},$$
在这种情况下，应该假设$x_{n+1} = x_1$和$x_{n+2} = x_2$。由此可见，如果
$$(x_i - x_{i-1})(x_i - x_{i+1}) \leqslant 0,$$
那
$$f_{n+1}(x_1, \dots, x_i, x_i, \dots, x_n) < \frac{1}{2} (n+1)$$
在$f_n(x_1, x_2, \dots, x_n) < \frac{1}{2} n$。

但在$n$为奇数的情况下，需要找到一个$(x_i - x_{i-1})(x_i - x_{i+1}) \leqslant 0$对应的$i$，因为如果对于所有$i$，满足不等式$(x_i - x_{i-1})(x_i - x_{i+1}) > 0$，那么，这些不等式的变量，我们将得到$(x_1 - x_2)^2(x_2 - x_3)^2 \dots (x_n - x_1)^2 < 0$。由于 7 是奇数，因此对于 $n=8$ 和所有偶数 $n$ 来说，不等式不成立，并且前面的推理将确保奇数 $n$ 得到这个结果。

然而，1961年，来自贝尔格莱德的数学家德耶科维奇驳斥了这一假设。

⟦folio 15⟧

---
running_head:
folio:
---

Mordell 位置，证明 $n=8$ 的不等式。 1967年，巴西数学家诺沃萨德发表了$n=10$的证明。 1974年，苏联数学家V. I. Levin和E. K. Godunova证明了$n=12$的不等式。

在那些年里，没有数学家试图以一般形式证明不平等。早在 1956 年，英国数学家莱特希尔就指出，一般来说，这个不等式是不成立的。他设法构建了一组二十个数字$x_1, \dots, x_{20}$，使得$f_{20}(x_1, \dots, x_{20}) < 10$。一段时间后，他和苏格兰数学家祖劳夫独立地找到了 $n=14$ 的对应例子。这是其中之一：50, 5, 48, 3, 48, 1, 50, 0, 52, 1, 54, 4, 53, 6。

在奇数 $n$ 的情况下，事情要复杂得多。 1958 年，格拉斯哥数学家兰金证明，对于足够大的奇数$n$，不等式并不成立。

1959 年，我们已经提到过的 Zulauf 证明了奇数 $n \geqslant 53$ 不等式不成立。 1961年，新加坡科学家戴南达提出了$n=27$的对策。英国数学家 Deikin 在 1971 年构造了一个反驳$n=25$的例子。

列宁格勒大学数学寄宿学校的两名学生（其中一位作者的学生）R. Alekseev 和 E. Foshkin 使用计算机独立构建了 $n=25$ 的对策：
32, 0, 37, 0, 43, 0, 50, 0, 59, 8, 62, 21, 55, 29, 44, 32, 33, 31, 24, 30, 16, 29, 10, 29, 4.

最近，1989 年 10 月，美国数学家 Trosch 发表了所有其他 $n$ 的不等式证明，即 13、15、17、19、21 和 23。然而，对于这个来说，证明 $n=23$ 的不等式就足够了，他做到了。

自 1956 年证明不等式 $f_n \geqslant \frac{n}{2}$ 为假以来，人们对它进行了两个方向的研究。首先要找出哪个 $n$ 不等式成立。我们已经报告了此问题的状态。现在我们将继续讨论另一个研究方向。

1957年，兰金证明了不等式$f_n \geqslant \frac{2\sqrt{2}-1}{6} n = \frac{n}{2} \cdot 0,609$成立。 1961年，他的成绩略有提高：$f_n \geqslant \frac{n}{2} \cdot 0,661$。同年，Diananda 证明了$f_n \geqslant \frac{2\sqrt{2}-1}{2} \cdot \frac{n}{2} = \frac{n}{2} \cdot 0,914$。 1962年他证明了$f_n \geqslant \frac{n}{2} \times 0,922$。即，他插入了以下问题：对于任何自然$n$，不等式$f_n \geqslant \gamma \cdot \frac{n}{2}$都成立的最大数$\gamma$是多少。 Volodya Drinfeld 解决的正是这个问题。

这一切都始于1969年第三次全联盟数学优化中，提出证明不等式$\frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2} > \frac{n}{4}$。在所有参与者中，有一名学生能够解决这个问题，他是列宁格勒大学数学寄宿学校的学生 A. Berzinsh，他是三届全联盟优化奖的获奖者。

这里的解决方案是这样的。令$x_{i_1}$为$x_1, x_2, \dots, x_n$中最大的数字； $x_{i_2}$ — $x_{i_1}$ 之后的两个数字中较大的一个； $x_{i_3}$ 是$x_{i_2}$ 之后的两个数字中较大的一个，依此类推。令$k$使得$x_{i_k}$后面的两个数字的最大值为$x_{i_1}$。显然$k \geqslant \frac{n}{2}$，因此
$\frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2} > \frac{x_{i_1}}{2x_{i_2}} +$
$\frac{x_{i_2}}{2x_{i_3}} + \dots + \frac{x_{i_k}}{2x_{i_1}} \geqslant \frac{k}{2} \geqslant \frac{n}{4}$.

最后的总和不小于 $\frac{k}{2}$ 由柯西不等式 $a_1+a_2+\dots+a_k \geqslant k^k \sqrt{a_1a_2 \dots a_k}$ 得出。

⟦folio 16⟧

---
running_head:
folio:
---

此次优化的获胜者之一是哈尔科夫学生沃洛达·德林菲尔德 (Voloda Drinfeld)。作为苏联队的一员，他参加了国际数学优化。该团队的科学领导者是苏联最著名的 naravavents 专家之一，V.I. 教授。莱文。他告诉这些人关于循环不平等的知识，并且在同一年的 1969 年，沃洛德设法找到了所需的值 $\gamma$。没关系$\gamma=0,989$...

在说出V的想法之前。在 Drinfeld 的工作中，我们将展示如何获得问题 M1250 中表述的较弱结果。让我们回忆一下这个问题的条件。

M1250。证明如果$x_1, x_2, \dots, x_n$是正数，则$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_n}{x_1+x_2}$大于$a$ ($\sqrt{2}-1)n$; b) $\frac{5}{12}n$; c) 如果数字$x_1, x_2, \dots, x_n$构成单调序列，则该和不小于$\frac{n}{2}$。

解决方案
a) 每个问题
$\frac{x_i}{x_{i+1}+x_{i+2}} (i=1, 2, \dots, n)$ 将用以下形式表示
$\frac{x_i+\frac{1}{2}x_{i+1}}{x_{i+1}+x_{i+2}} + \frac{\frac{1}{2}x_{i+1}+x_{i+2}}{x_{i+1}+x_{i+2}} -1$.

我们将得到 $2n$ 问题并按参数对它们进行分组 - 第一个分数为 $2n$；第二与第三；第四与第五，依此类推。让我们立即估计形成一对的数字之和：
$\frac{1}{2}x_i+x_{i+1} + \frac{x_i+\frac{1}{2}x_{i+1}}{x_{i+1}+x_{i+2}} \geq$
$\geq 2\sqrt{\frac{\left(\frac{1}{2}x_i+x_{i+1}\right)\left(x_i+\frac{1}{2}x_{i+1}\right)}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$= 2\sqrt{\left(\frac{1}{2}+\frac{x_i+x_{i+1}}{4(x_i+x_{i+1})^2}\right)\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$
$> \sqrt{2} \cdot \sqrt{\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$.

由于 $n$ 数的乘积
$\sqrt{\frac{x_1+x_2}{x_2+x_3}}, \sqrt{\frac{x_2+x_3}{x_3+x_4}} \dots, \sqrt{\frac{x_n+x_1}{x_1+x_2}}$等于1，那么根据柯西不等式可知它们的和不小于$n$。因此原始总和大于$\sqrt{2n}-n=(\sqrt{2}-1)n$。

6) 当证明 a) 点时，我们在每个分数上加一。但为什么需要恰好添加一个呢？让我们添加任意数字 $\alpha$ 并选择 $\beta$ 以使等式成立
$\frac{x_i}{x_{i+1}+x_{i+2}} + \alpha = \frac{x_i+\beta x_{i+1}}{x_{i+1}+x_{i+2}} +$
$+\frac{\alpha(\beta x_{i+1}+x_{i+2})}{x_{i+1}+x_{i+2}}$.

显然$\beta+\alpha\beta=\alpha$，即$\beta=\frac{\alpha}{\alpha+1}$。因此，
$\frac{x_i+\beta x_{i+1}}{x_{i+1}+x_{i+2}} + \frac{\alpha(\beta x_{i+1}+x_{i+1})}{x_{i+1}+x_{i+2}} \geq$
$\geq 2\sqrt{\alpha \frac{\left(x_i+\beta x_{i+1}\right)\left(\beta x_{i+1}+x_{i+1}\right)}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$= 2\sqrt{\alpha \frac{\beta(x_i+x_{i+1})^2+(\beta-1)^2x_i x_{i+1}}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$> 2\sqrt{\alpha \beta \frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}} = \frac{2\alpha}{\sqrt{\alpha+1}} \sqrt{\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$.

方法，
$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_n}{x_1+x_2} >$
$> \frac{2\alpha}{\sqrt{\alpha+1}} \left(\sqrt{\frac{x_1+x_2}{x_2+x_3}} + \sqrt{\frac{x_2+x_3}{x_3+x_4}} + \dots \right.$
$... + \sqrt{\frac{x_n+x_1}{x_1+x_2}}) - \alpha n >$
$> \frac{2\alpha}{\sqrt{\alpha+1}} n - \alpha n = \left(\frac{2\alpha}{\sqrt{\alpha+1}} - \alpha\right) \cdot n$.

如果我们输入$\alpha=\frac{5}{4}$，则$\frac{2\alpha}{\sqrt{\alpha+1}} - \alpha=\frac{5}{12}=0,416$...并且第6)点的陈述被证明。回想一下，a) 部分是通过放入 $\alpha=1$ 获得的。

⟦folio 17⟧

---
running_head:
folio:
---

考虑$x_1 \geqslant x_2 \geqslant \dots \geqslant x_n$的情况。让我们证明这里有一个对应关系
$$f_n(x_1, x_2, \dots, x_n) \geqslant$$
$$\geqslant f_{n-1}(x_1, x_2, \dots, x_{n-1}) + \frac{1}{2}.$$
事实上，同样的事情也成立：
$$f_n(x_1, x_2, \dots, x_n) - f_{n-1}(x_1, x_2, \dots, x_{n-1}) =$$
$$= \frac{(x_{n-2} - x_{n-1})(x_1 - x_n)}{(x_{n-1} + x_n)(x_1 + x_{n-1})} +$$
$$+ \frac{(x_1 - x_n)(x_{n-1} - x_n)(x_1 - x_{n-1})}{2(x_{n-1} + x_n)(x_1 + x_{n-1})} +$$
$$+ \frac{(x_{n-1} - x_n)(x_2 - x_n)}{(x_1 + x_2)(x_1 + x_n)} + \frac{1}{2}.$$
但所有项都是非负的（来自序列$x_1, x_2, \dots, x_n$的单调性）。所以，
$$f_n(x_1, x_2, \dots, x_n) \geqslant f_{n-1}(x_1, x_2, \dots, x_{n-1}) +$$
$$+ \frac{1}{2} \geqslant f_{n-2}(x_1, x_2, \dots, x_{n-2}) + 1 \geqslant \dots$$
$$\geqslant f_2(x_1, x_2) + \frac{n-2}{2} =$$
$$= \frac{x_1}{x_1 + x_2} + \frac{x_2}{x_2 + x_1} + \frac{n-2}{2} = \frac{n}{2}.$$
现在考虑$x_1 \leqslant x_2 \leqslant \dots \leqslant x_n$的情况。注意
$$f_n(x_1, x_2, \dots, x_n) = \frac{x_1 + x_2}{x_2 + x_3} + \dots + \frac{x_n + x_1}{x_1 + x_2} -$$
$$- n + \frac{x_2}{x_1 + x_2} + \frac{x_3}{x_2 + x_3} + \dots + \frac{x_n}{x_n + x_1}.$$
但第一个和不小于 $n$，因为所有项的乘积等于 1。因此，足以证明
$$g_n(x_1, x_2, \dots, x_n) = \frac{x_2}{x_1 + x_2} +$$
$$+ \frac{x_3}{x_2 + x_3} + \dots + \frac{x_n}{x_{n-1} + x_n} + \frac{x_1}{x_n + x_1} \geqslant \frac{n}{2}.$$
为此，我们将证明
$$g_n(x_1, x_2, \dots, x_n) - g_{n-1}(x_1, x_2, \dots, x_{n-1}) -$$
$$- \frac{1}{2} = \frac{x_n}{x_{n-1} + x_n} + \frac{x_1}{x_n + x_1} - \frac{x_1}{x_{n-1} + x_1} -$$
$$- \frac{1}{2} = \frac{(x_{n-1} - x_1)(x_n - x_{n-1})(x_n - x_1)}{2(x_{n-1} + x_n)(x_n + x_1)(x_1 + x_{n-1})} \geqslant 0.$$
所以，
$$g_n(x_1, x_2, \dots, x_n) \geqslant$$
$$\geqslant g_{n-1}(x_1, x_2, \dots, x_{n-1}) + \frac{1}{2} \geqslant$$
$$\geqslant g_{n-2}(x_1, x_2, \dots, x_{n-2}) + 1 \geqslant \dots$$
$$\dots \geqslant g_2(x_1, x_2) + \frac{n-2}{2} =$$
$$= \frac{x_2}{x_1 + x_2} + \frac{x_1}{x_2 + x_1} + \frac{n-2}{2} = \frac{n}{2}$$
现在我们将介绍 V. Drinfeld 对他的结果的证明。它基于两个显着的不平等。
第一个涉及两组$n$正数$a_1, a_2, \dots, a_n$和$b_1, b_2, \dots, b_n$。考虑表达式 $a_1b_1 + a_2b_2 + \dots + a_nb_n$。声明是，如果数字的编号满足 $a_1 \geqslant a_2 \geqslant \dots \geqslant a_n$ 和 $b_1 \geqslant b_2 \geqslant \dots \geqslant b_n$，则该表达式取最大值；如果
$$a_1 \geqslant a_2 \geqslant \dots \geqslant a_n, a b_1 \leqslant b_2 \leqslant \dots \leqslant b_n.$$
第二个不等式称为詹森不等式，与凸函数有关。如果函数$\varphi(x)$在$[a; b]$上的凸函数，如果$[a; b]$的任何线段$[x_1; x_2]$上的值在图上低于连接点$(x_1; \varphi(x_1))$和$(x_2; \varphi(x_2))$的线段（图1）。这个定义可以写成不等式
$$\varphi(\alpha x_1 + (1 - \alpha)x_2) \leqslant \alpha \varphi(x_1) + (1 - \alpha) \varphi(x_2).$$

⟦folio 18⟧

---
running_head:
folio:
---

Jensen 不等式指出，对于在区间 $[a; b]$ 上凸的任何函数 $\varphi(x)$、来自该区间的任意一组点 $x_1, x_2, \ldots, x_n$，以及任意一组正数 $p_1, p_2, \ldots, p_n$（其总和等于 $1 (p_1 + p_2 + \ldots + p_n = 1)$），该关系成立

$$\varphi(p_1 x_1 + \ldots + p_n x_n) \leqslant \leqslant p_1 \varphi(x_1) + \ldots + p_n \varphi(x_n).$$

让我们继续给出证明。让我们表示$\frac{x_{i+1}}{x_i} = k_i$和$\frac{x_1}{x_n} = k_n$。让我们按升序排列结果数字$k_i$，并用$m_j$表示结果序列的整数。现在考虑两个序列：

$$\frac{1}{m_1}, \frac{1}{m_2}, \ldots, \frac{1}{m_n} \text{ и} \frac{1}{1 + m_n}, \frac{1}{1 + m_{n-1}}, \ldots, \frac{1}{1 + m_2}, \frac{1}{1 + m_1}.$$

一是单调杀戮，二是单调增加。利用我们的第一个不等式，我们得到

$$\frac{x_1}{x_2 + x_3} + \frac{x_2}{x_3 + x_4} + \ldots + \frac{x_n}{x_1 + x_2} = \frac{1}{k_1(k_2 + 1)} + \frac{1}{k_2(k_3 + 1)} + \ldots + \frac{1}{k_n(k_1 + 1)} \geqslant \frac{1}{m_1(m_n + 1)} + \frac{1}{m_2(m_{n-1} + 1)} + \ldots + \frac{1}{m_n(m_1 + 1)}.$$

(*)

我们表示 $m_i \cdot m_{n-i+1} = c_i$ 和

$$r_i = \frac{1}{m_i(m_{n-i+1} + 1)} + \frac{1}{m_{n-i+1}(m_i + 1)},$$

然后

$$r_i = \frac{1}{c_i} \left(1 + \frac{c_i - 1}{(1 + m_i)(1 + m_{n-i+1})}\right).$$

由于$(1 + m_i)(1 + m_{n-i+1}) \geqslant (1 + \sqrt{c_i})^2$，那么

$$r_i \geqslant \left\{ \begin{array}{l l} \frac{1}{c_i}, & c_i \geqslant 1, \\ \frac{2}{c_i + \sqrt{c_i}}, & c_i < 1. \end{array} \right.$$

让我们输入$c_i = e^{y_i}$。根据不等式 (*) 和 (**) 我们有

$$\frac{2}{n} \sum_{i=1}^{n} \frac{x_i}{x_{i+1} + x_{i+2}} \geqslant \geqslant \frac{1}{n} \left( \sum_{c_i \geqslant 1} e^{-y_i} + \sum_{c_i < 1} 2\left(e^{\frac{x}{2}} + e^{y_i}\right)^{-1} \right).$$

设$g$为不超过$y = e^{-x}$和$y = 2\left(e^{\frac{x}{2}} + e^{x}\right)^{-1}$函数的最凸函数。然后根据不等式 (***)，由于 Jensen 不等式，我们有

$$\frac{2}{n} \sum_{i=1}^{n} \frac{x_i}{x_{i+1} + x_{i+2}} \geqslant \geqslant \frac{1}{n} \sum_{i=1}^{n} g(y_i) \geqslant g\left(\frac{y_1 + y_2 + \ldots + y_n}{n}\right) = g(0).$$

这就证明了$\gamma \geqslant g(0)$。

进一步，通过相当优雅的解释，证明了$g(0) = \gamma$。

让公切线连接点 $(x_1; e^{-x_1})$ 和 $(x_2; 2\left(e^{\frac{x}{2}} + e^{x_2}\right)^{-1})$ (图 2)。函数$g$的图像由三部分组成：$x \geqslant x_1$处的$y = e^{-x}$、$x \leqslant x_2$处的$y = 2\left(e^{x} + e^{\frac{x}{2}}\right)^{-1}$以及它们在$x_2 \leqslant x \leqslant x_1$处的公切线。切线与纵坐标轴的交点的纵坐标为$\gamma$。
