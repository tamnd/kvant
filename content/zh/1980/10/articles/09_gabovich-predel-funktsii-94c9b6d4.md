---
id: 1980-10-gabovich-predel-funktsii-94c9b6d4
issue: kvant_1980_10
year: 1980
number: "10"
title: 功能限制
authors:
  - Габович И. Г.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 44
page_labels: 40-42
tag: J474
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7aa225a9d23cf44d9e97b1c6f6778e5a86da859682b1613e63f018aad0f5c058
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/09_gabovich-predel-funktsii-94c9b6d4.md
source_content_sha256: f3800ae08a98529689b21112f34ea6fc744ef252449c9beaae6a865811267511
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

I·加博维奇

功能限制

“函数极限”的概念是学校数学课程中最重要的概念之一。通过它，定义了“连续性”和“导数”。

我们以两种方式制定主要定义（《代数与分析原理 9》手册第 38 节）。

首先在“算术”语言中：数字$b$被称为函数$f$的极限，而$x$趋于$a$，如果对于任何$\varepsilon > 0$存在$\delta > 0$，使得对于所有$x$满足双重不等式*）

$$0 < |x - a| < \delta,$$

不平等成立

$$|f(x) - b| < \varepsilon.$$

为了用“几何”语言给出函数极限的定义，我们引入了一个学校教科书中没有的术语。众所周知，点$a \in R$的邻域称为$]a - \delta; a + \delta[$形式的区间，其中$\delta$是任意正数。让我们将点$a \in R$的穿孔邻域作为其邻域，从该点$a$本身被抛出（“穿孔”），即$]a - \delta; a[U]a; a + \delta[$形式的“破碎”集。现在函数极限的定义可以如下形成：数字$b$称为函数$f$的极限，其中$x$趋于$a$，如果有任何

$$*) |x - a| > 0 \iff x \neq a.$$

点 $b$ 的邻域 $B$ 存在点 $a$ 的穿孔邻域 $A$，使得 $f(A) \subset B$ (图 1)。

因此，不要求不等式（2）对于$x = a$也成立。 $a$处的函数$f$甚至可能没有被定义——这不会以任何方式影响它的极限，因为$x$趋向于$a$。例如，函数$\frac{x^2 - 9}{x - 3}$未在$x = +3$定义，但其极限在$x \rightarrow +3$存在。

一个更一般的例子：函数$\frac{\Delta f(x_0)}{\Delta x}$在$\Delta x = 0$处始终未定义，但其在$\Delta x \rightarrow 0$处的极限“经常”存在（在点$x_0$处称为任意函数$f$）。

然而，“很多时候”不等式 (2) 也满足 $x = a$；如果同时$b = f(a)$，则称函数$f$在点$a$连续。

如果形式的声明

$$\lim_{x \rightarrow 1} f(x) = b$$

从定义无限地证明结果，任何$\varepsilon > 0$都需要找到相应的$\delta > 0$，或者至少证明这样一个$\delta > 0$存在。

示例 1. 让我们证明

$$\lim_{x \rightarrow \frac{1}{7}} (3 - 2x) = \frac{19}{7}.$$

对于这些“参与者”$(f(x) = 3 - 2x, a = \frac{1}{7}, b = \frac{19}{7})$ 不等式 (2) 的形式为

$$|3 - 2x - \frac{19}{7}| < \varepsilon.$$

为了找到所需的$\delta$，让我们“揭示”不等式（4）并构造

⟦folio 41⟧

xia“裸露”$x$。不等式(4)等价于不等式

$$\left| -2x + \frac{2}{7} \right| < \varepsilon,$$
$$-\varepsilon < -2x + \frac{2}{7} < \varepsilon,$$
$$-\frac{2}{7} - \varepsilon < -2x < -\frac{2}{7} + \varepsilon,$$
$$\frac{1}{7} + \frac{\varepsilon}{2} > x > \frac{1}{7} - \frac{\varepsilon}{2},$$
$$\frac{1}{7} - \frac{\varepsilon}{2} < x < \frac{1}{7} + \frac{\varepsilon}{2}.$$

现在我们“瓦解”不等式（5）并得到形式（1）的不等式：

$$-\frac{\varepsilon}{2} < x - \frac{1}{7} < \frac{\varepsilon}{2},$$
$$|x - \frac{1}{7}| < \frac{\varepsilon}{2}.$$

我们的目标已经足够了。因此，对于 $\delta = \frac{\varepsilon}{2}$，(4) 由 $0 < |x - \frac{1}{7}| < \delta$ 推出。在此示例中，不等式 (2) = (4) 对于 $x = a$ 也成立；因为 $\delta$ 显然可以从 $] 0; \frac{\varepsilon}{2}]$ 中取出任何数字。

然而，第二个评论是正确的并且具有一般性：如果对于某些 $\varepsilon_0 > 0$ 某些 $\delta_0 > 0$ 是合适的，即从 $0 < |x - a| < \delta_0$ (6)

流出

$$|f(x) - b| < \varepsilon_0,$$

那么，当然，任何$\delta \in ]0; \delta_0[$也适用于这个$\varepsilon_0 > 0$：如果$0 < |x - a| < \delta$，则从$\delta < \delta_0$遵循（6），因此遵循（7）。

例 2. 让我们证明 $\lim_{x \to -2} \frac{5}{x} = -\frac{5}{2}$。

在这种情况下，不等式 (2) 的形式为

$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon.$$

让我们再走同样的路吧。不等式(8)等价于不等式

$$\left| \frac{5}{x} + \frac{5}{2} \right| < \varepsilon,$$
$$-\varepsilon < \frac{5}{x} + \frac{5}{2} < \varepsilon,$$
$$-\frac{5}{2} - \varepsilon < \frac{5}{x} < -\frac{5}{2} + \varepsilon.$$

为了达到“暴露”$x$的目的，我们需要将1项逐项划分为二重不等式的各部分（9）；但这只有在不等式的所有部分都具有相同符号的情况下才能完成，因为词不等式的相应属性表示：如果$a < b$和数字$a, b$具有相同的符号（简而言之：$ab > 0$），则$\frac{1}{a} > \frac{1}{b}$（证明这个陈述！）。 $-\frac{5}{2} - \varepsilon < 0$。因此，我们需要不等式（9）的其余两部分为负数。需要$-\frac{5}{2} + \varepsilon < 0$或$\varepsilon < \frac{5}{2}$就足够了。

所以，让我们从 $\varepsilon < \frac{5}{2}$ 开始（注意这个地方 - 我们稍后会再讨论这个）。那么不等式（9）的所有部分都是负的。这就是为什么

$$\frac{1}{-\frac{5}{2} - \varepsilon} > \frac{x}{5} > \frac{1}{-\frac{5}{2} + \varepsilon},$$
$$\frac{5}{-\frac{5}{2} - \varepsilon} > x > \frac{5}{-\frac{5}{2} + \varepsilon},$$
$$\frac{5}{-\frac{5}{2} + \varepsilon} < x < \frac{5}{-\frac{5}{2} - \varepsilon},$$
$$\frac{10}{-5 + 2\varepsilon} < x < \frac{10}{-5 - 2\varepsilon}.$$

$x$“暴露”。现在我们需要从 (10) 获得形式 (1) 的不等式：

$$|x - (-2)| < \delta,$$
$$-\delta < x - (-2) < \delta,$$
$$-2 - \delta < x < -2 + \delta.$$

来自（10）：

$$-2 + \frac{10}{-5 + 2\varepsilon} + 2 < x < -2 +$$
$$+ \frac{10}{-5 - 2\varepsilon} + 2,$$
$$-2 - \frac{4\varepsilon}{5 - 2\varepsilon} < x < -2 + \frac{4\varepsilon}{5 + 2\varepsilon}.$$

到目前为止，不等式（12）并不完全具有形式（11）。在$\varepsilon < \frac{5}{2}$

$$\frac{4\varepsilon}{5 - 2\varepsilon} > \frac{4\varepsilon}{5 + 2\varepsilon}.$$

⟦folio 42⟧

方法，

$$-2 - \frac{4\varepsilon}{5-2\varepsilon} < -2 - \frac{4\varepsilon}{5+2\varepsilon}. \tag{13}$$

让我们粗化一下不等式 (12)：

$$-2 - \frac{4\varepsilon}{5+2\varepsilon} < x < -2 + \frac{4\varepsilon}{5+2\varepsilon}. \tag{14}$$

由(13)可知，若$x$满足不等式(14)，则也满足不等式(12)(见图2)。但是（14）已经具有形式（11）。伊兹 (14)

$$|x - (-2)| < \frac{4\varepsilon}{5+2\varepsilon}.$$

因此，如果 $\varepsilon < \frac{5}{2}$，则从 $0 < |x - (-2)| < \delta$ 得出$\delta = \frac{4\varepsilon}{5+2\varepsilon}$ (8)。

但我们需要证明对于任何 $\varepsilon > 0$ 都存在这样的 $\delta > 0$，并且我们仅针对 $\varepsilon < \frac{5}{2}$ 证明了这一点。然而，本质上，这已经足够了，因为对于 $\varepsilon \geq \frac{5}{2}$ 来说，同样的 $\delta$ 就可以了！

事实上，让 $\varepsilon_1 \geq \frac{5}{2}$；任意的$\varepsilon_2 < \frac{5}{2}$和$\delta_2 = \frac{4\varepsilon_2}{5+2\varepsilon_2}$都是可能的；根据证明从

$$0 < |x - (-2)| < \delta_2$$

流出$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon_2;$$

但是$\varepsilon_2 < \frac{5}{2} \leq \varepsilon_1$；方法，

$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon_1.$$

这个评论具有一般性：事实证明，我们总是可以寻找$\delta$，而不是所有$\varepsilon > 0$，而是所有小于我们选择的任何正数的正$\varepsilon$。

当然，在这个例子中，对于 $x = a$ 来说，不等式 (2) = (8) 成立。

示例 3. 让我们证明一下

$$\lim_{x \to 0} \left( x \cdot \sin \frac{1}{x} \right) = 0.$$

图 2.

在这种情况下，不等式 (2) 的形式为

$$|x \cdot \sin \frac{1}{x} - 0| < \varepsilon,$$

$$|x \cdot \sin \frac{1}{x}| < \varepsilon. \tag{15}$$

如果在这个例子中我们立即遵循与前面相同的路径，我们将无法达到目标：$x$，我们将无法“暴露”。因此，让我们从“粗化”不等式开始（15）：因为$$\left| \sin \frac{1}{x} \right| \leq 1,$$

$$|x \sin \frac{1}{x}| \leq |x|. \tag{16}$$

从 (16) 可以看出，与 (15) 一起搜索 $\delta$ 就足以得到不等式 $$|x| < \varepsilon.$$ 因为在我们的例子中不等式 (1) 具有$0 < |x| < \delta$ 的形式，很明显我们可以将 $\varepsilon$ 作为所寻找的 $\delta$。

在此示例中，$x = a = 0$ 的不等式 (2) = (15) 当然不成立：$x = 0$ 的函数 $x \sin \frac{1}{x}$ 未定义。

请记住我们使用过两次的“粗化”示例 - 它通常很有用。

在我们考虑的例子中，找到 $\delta$ 并不会导致函数变大；通过直接求$\delta$来直接证明命题(3)当然是不可能的。在这种情况下，理论可以提供帮助。

让我们举一个“非学校”理论的例子。该定理也成立：如果 $$\lim_{x \to a} f(x) = 0, \lim_{x \to a} g(x) = 0$$ 存在且 $$\lim_{x \to a} \frac{f'(x)}{g'(x)},$$ 存在，则 $u$ $$\lim_{x \to a} \frac{f(x)}{g(x)} u$$ 存在

$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}.$$

该定理称为*洛皮塔尼亚规则*。根据这个规则：

$$\lim_{x \to 0} \frac{e^x - e^{-x}}{\ln(e - x) + x - 1} =$$

$$= \lim_{x \to 0} \frac{e^x + e^{-x}}{-1 - \frac{1}{e} + 1} = \frac{2}{1 - \frac{1}{e}} = \frac{2e}{e - 1}.$$
