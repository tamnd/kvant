---
id: 1984-9-gornusha-svedem-neravenstvo-k-izvestnomu-df36e552
issue: kvant_1984_9
year: 1984
number: "9"
title: 让我们将不等式减少到已知
authors:
  - Горнуша П. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 53
page_labels: 49, 51
tag: 32W0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f90d237f70010df2a8f3c9849372bfb105edaf483171d434aa513540aa30d791
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/20_gornusha-svedem-neravenstvo-k-izvestnomu-df36e552.md
source_content_sha256: 9f61d923de9c94a6a6990d89885a65b59cfe8fd93b4c587caebf40ed6c739181
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

让我们将不等式减少到已知

P·P·戈努什

入学考试中提供的证明不平等的许多问题都可以在童年转变点的帮助下得到解决，它们的辅助不平等（明显的或先前已知的）属性。我们将在这里考虑此类问题*)。辅助不等式以颜色突出显示，但不便于记忆。您需要能够使用它们（并引入不等式）并能够根据需要导出它们。

每个小学生都知道数字的平方（或数字的平方和）是非负数：

$$a^2 \geq 0, a^2 + b^2 \geq 0, a^2 + b^2 + c^2 \geq 0, \dots$$

(1)

这个简单的事实是解决许多问题的关键。让我们从一个非常简单的开始。

任务 1（KPI，1981）。证明对于任何实数 x、y、z、t，以下不等式成立：

$$4x^2 + 3y^2 + 4z^2 + 5t^2 + 4ax + 3ay + 4az + 5at + 4a^2 \geq 0.$$

解决方案。我们重新排列不等式左边的项以获得平方和：

$$(4x^2 + 4ax + a^2) + (3y^2 + 3ay + 3a^2/4) + (4z^2 + 4az + a^2) + (5t^2 + 5at + 5a^2/4) \geq 0,$$

$$(2x + a)^2 + 3(y + a/2)^2 + (2z + a)^2 + 5(t + a/2)^2 \geq 0.$$

*) 基辅、列宁格勒和莫斯科国立大学（KSU、列宁格勒国立大学和莫斯科国立大学）不同年份提供的作业；在莫斯科电子工程和汽车工程学院（MIEM、MATI）和基辅理工学院（KPI）；我们在大学缩写旁边注明了提出任务的年份。

最后一个不等式非常相似（这是（1）的变体），并且由于它与给定的等价，所以它是一个解问题。

不平等（1）在许多不同领域都存在；例如$(x + y + z)^2 \geq 0, (\sqrt{a} - \sqrt{b})^2 \geq 0, (t - 1)^2 \geq 0$。倒数第二个不等式可以重写为$a + b > 2\sqrt{ab}$（对于$a > 0, b > 0, a \neq b$）或

$$\frac{1}{\sqrt{ab}} > \frac{2}{a + b}$$

(2)

当这种简单的不平等以“伪装”的形式出现时，例如在下面的问题中，能够看到它是很重要的。

问题 2（路易斯安那州立大学，1978 年）。确定差异的符号

$$\left( \frac{1}{\sqrt{1 \cdot 1978}} + \frac{1}{\sqrt{2 \cdot 1977}} + \dots + \frac{1}{\sqrt{k \cdot (1978 - k + 1)}} + \frac{1}{\sqrt{1978 \cdot 1}} \right) - 2 \cdot \frac{1978}{1979}.$$

解决方案。使用不等式 (2) 1978 次，我们可以写出：

$$\frac{1}{\sqrt{1 \cdot 1978}} > \frac{2}{1 + 1978} = \frac{2}{1979};$$

$$\frac{1}{\sqrt{2 \cdot 1977}} > \frac{2}{2 + 1977} = \frac{2}{1979};$$

$$\frac{1}{\sqrt{1978 \cdot 1}} > \frac{2}{1978 + 1} = \frac{2}{1979}.$$

添加这些不等式，我们得到

$$\frac{1}{\sqrt{1 \cdot 1978}} + \frac{1}{\sqrt{2 \cdot 1977}} + \dots + \frac{1}{\sqrt{k \cdot (1978 - k + 1)}} > 2 \cdot \frac{1978}{1979}.$$

这意味着这种差异是正的。

这是主题 $(\sqrt{a} - \sqrt{b})^2 \geq 0$ 的另一个变体。将表达式 $(\sqrt{a} + \sqrt{b})^2$ 添加到这个不等式两边，我们得到

$$(\sqrt{a} + \sqrt{b})^2 \leq (\sqrt{a} - \sqrt{b})^2 + (\sqrt{a} + \sqrt{b})^2 = 2(a + b),$$

⟦folio 51⟧

立即找到解决方案。
答案：$p=3; t=\pi+2k\pi \ (k \in \mathbb{Z})$。
xine 从 0 到 π 的单调递减在下面的问题中多次上演（每次使用它时，我们都会看到相应的颜色不等式）。
问题 6（MIEM，1980）。在 $n=1, 2, 3$ 处，比较数字
$\sin^2 1^\circ + \sin^2 4^\circ$ 和 $\sin^2 2^\circ + \sin^2 3^\circ$。
解决方案。 1）$n=1$。让我们将正弦之和转换为乘积：
$\sin 1^\circ + \sin 4^\circ = 2 \sin 2, 5^\circ \cos 1, 5^\circ$,
$\sin 2^\circ + \sin 3^\circ = 2 \sin 2, 5^\circ \cos 0, 5^\circ$.
现在您可以看到第二个数字大于第一个数字，即 $\sin 2, 5^\circ > 0$ 和
$\cos 0, 5^\circ > \cos 1, 5^\circ$.
2) $n=2$。让我们通过双角的余弦来表达正弦的平方
$\sin^2 1^\circ + \sin^2 4^\circ = \frac{1-\cos 2^\circ}{2} + \frac{1-\cos 8^\circ}{2}$,
$\sin^2 2^\circ + \sin^2 3^\circ = \frac{1-\cos 4^\circ}{2} + \frac{1-\cos 6^\circ}{2}$.
让我们证明现在第一个数字更大。为此，只要建立不等式就足够了
$\cos 4^\circ + \cos 6^\circ > \cos 2^\circ + \cos 8^\circ$,
等价于不平等
$2 \cos 5^\circ \cos 1^\circ > 2 \cos 5^\circ \cos 3^\circ$,
$\cos 5^\circ > 0$ 和
$\cos 1^\circ > \cos 3^\circ$.
3) $n=3$。让我们再次证明第一个数字更大。让我们使用公式
$\sin^3 \alpha = \frac{3 \sin \alpha - \sin 3 \alpha}{4}$, (6)
这很容易检查（将$\sin 3\alpha$展开为$\sin(2\alpha + \alpha)$，然后应用$\cos 2\alpha$和$\sin 2\alpha$的公式）。那么问题就简化为证明（等价）不等式
$\sin 9^\circ - \sin 3^\circ + \sin 6^\circ - \sin 12^\circ >$
$> 3 \sin 3^\circ - 3 \sin 1^\circ + 3 \sin 2^\circ - 3 \sin 4^\circ$;
$2 \cos 6^\circ \sin 3^\circ - 2 \cos 9^\circ \sin 3^\circ >$
$> 6 \cos 2^\circ \sin 1^\circ - 6 \cos 3^\circ \sin 1^\circ$;
$\sin 3^\circ \sin 7, 5^\circ \sin 1, 5^\circ >$
$> 3 \sin 1^\circ \sin 2, 5^\circ \sin 0, 5^\circ$.
根据式(6)对左边三角的正弦进行变换，利用$\sin 1^\circ$、$\sin 2, 5^\circ$、$\sin 0, 5^\circ$的正性，可知足以证明不等式
$(3 - 4 \sin^2 1^\circ) (3 - 4 \sin^2 2, 5^\circ) \times (3 - 4 \sin^2 0, 5^\circ) > 3,$
转换为等效形式
$(1 + 2 \cos 2^\circ) (1 + 2 \cos 5^\circ) \times (1 + 2 \cos 1^\circ) > 3,$
这是绝对正确的 - 左边甚至大于 8，因为
$\cos 1^\circ > \cos 2^\circ > \cos 5^\circ > \frac{1}{2}$.
也许分析的例子不正确——毕竟，在每个问题之前，我们对正在解决的不等式更加满意，并查看其解决方案的结果。解决此类问题的艺术和难度恰恰在于在分析问题的过程中看到必要的不平等。因此，我们提供了几个任务供您自行解决（最困难的任务在数据日志末尾标有星号）。但在开始解决它们之前，我们建议您再次查看类似的示例，以便了解如何根据它们的外观来解决问题。

任务
7（关键绩效指标，1981 年）。求表达式的最小值
$x^2 + 4y^2 + 3z^2 + t^2 - 2x - 12y - 6z - 2t$
假设$x, y, z$和$t$取任何实数值。
8（关键绩效指标，1981 年）。求函数的最大值
$y = \frac{11}{2} - \frac{1}{2} \cos 4x - \frac{4 \mathrm{tg} x}{1 + \mathrm{tg}^2 x}$.
9（MIEM，1980）。在 $n=1, 2, 3$ 比较数字
$\cos^2 1^\circ + \cos^2 4^\circ$ 和 $\cos^2 2^\circ + \cos^2 3^\circ$。
10（密歇根州立大学，1980）。证明对于任何实 $p$ 和 $q$，以下不等式成立：
$2(2p - 1)^4 + 1 + (1 - 2(2p - 1))^4 \sin 2t \geq 0$,
并找到所有使该不等式变为等式的数字 $(p, t)$。
11*（关键绩效指标，1976 年）。证明多项式$a^4 - 5a^3 - 6a^2 - a + 9$
不能有负根。
12*（MIEM，1982）。哪个区间 [2; 3], [3,1; 3.3]，[3.6； 4.5]所属号码
$a = \log_6 7 \sqrt[3]{6} - \log_7 \frac{1}{8 \sqrt[3]{49}} + \log_8 \frac{9}{8}$?
13（MIEM，1979）。按编号顺序排列
a) $0; \sqrt{0,8}; 1,2; \frac{11}{30}; 0,91846; \ln \frac{7}{5}$;
b) $1; 0,37; \frac{65}{63}; \frac{61}{59}; \tg 33^\circ; \tg(-314^\circ).$
