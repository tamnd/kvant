---
id: 1982-4-ryizhik-nado-li-iskat-odz-b963f0a3
issue: kvant_1982_4
year: 1982
number: "4"
title: 我需要寻找 ODZ 吗？
authors:
  - Рыжик В. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 41
page_last: 43
page_labels: 39-41
tag: 47CN
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 606a19d0aa7106ffca80b6400c4e87ad72c0e66c9c12fd28f683e05952aa538a
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/11_ryizhik-nado-li-iskat-odz-b963f0a3.md
source_content_sha256: 81dd66010d4e40efd4df7ed9280eba0384974d191d22212fba303ef4ef0bcde6
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

我需要寻找 ODZ 吗？

高考传统的题型是方程、不等式、系统（方程或不等式）。

众多针对学童和申请者的手册，在解决问题时，往往给出无条件的建议：“首先我们寻找ODZ！”显然，这一建议的呼应是悬挂在列宁格勒一所职业学校的艺术认可“记住ODZ！”。

首先，我们注意到目前的学校教科书中没有ODZ这个缩写。 “可接受值区域”一词的意思是“定义区域”。

根据定义，方程或不等式的 OD 是其左侧和右侧 OD 的交集。

那么，有必要从日本ODZ开始求解方程（不等式、系统）吗？在求解方程（不等式、系统）时是否有必要寻找 ODZ，尤其是从日本 ODZ 开始求解？一般来说，即在入学考试中通常提出的大多数方程（不等式、系统）中，不需要从日本ODZ开始求解；有时，在一些专门选择的或更困难的方程（不等式、系统）中，从日本 ODZ 开始求解是有用的。

一般来说，没有必要

$$\sqrt{x^2-3x+4}=1-3x. \tag{1}$$

方程（1）等价于系统

$$\begin{cases} x^2-3x+4=(1-3x)^2 \\ 1-3x\geq 0, \end{cases}$$

这已经不难解决了。 （顺便说一下，决定方程（1）的 ODZ 的不等式 $x^2-3x+4\geq 0$ 由系统（2）中包含的方程得出。）如果需要，您还可以从方程（1）移动到导出*）方程 $x^2-3x+4=(1-3x)^2$ 并检查找到的根。 （将方程（1）和与其等价的系统（2）一起求解后，当然不需要进行检查。）这个例子：不是等价的，而是推论的，并且在考虑的其他例子中必须牢记进行检查。

很容易证明任何形式的方程

$$\sqrt{f(x)}=g(x) \tag{3}$$

相当于系统

$$\begin{cases} f(x)=[g(x)]^2 \\ g(x)\geq 0. \end{cases}$$

的确。若$x_0$为式(3)的根，即数值方程$\sqrt{f(x_0)}=g(x_0)$有效，则$f(x_0)=[g(x_0)]^2$和$g(x_0)\geq 0$；这意味着$x_0$是系统(4)的一个解。反之，如果$x_0$是系统(4)的解，即数值方程$f(x_0)=[g(x_0)]^2$和$g(x_0)\geq 0$有效，则$\sqrt{f(x_0)}=\sqrt{[g(x_0)]^2}=|g(x_0)|$；从$g(x_0)\geq 0$、$|g(x_0)|=g(x_0)$开始；因此，$x_0$是方程（3）的根。

在等式（1）中，搜索 ODZ 会导致不必要的但很容易执行的计算。然而，对于习惯于总是寻找学历的申请人来说，有时会出现难以克服的困难。因此，建立 ODZ 方程 $\sqrt{x^3-x+1}=\sqrt{1-x}$，相反，他无法处理不等式 $x^3-x+1\geq 0$，而该方程等于

$$*) См. п. 74 пособия «Алгебра и начала ana-лиза 9—10» (М., «Просвещение», 1981).$$

⟦folio 40⟧

强烈要求系统
$$\begin{cases} x^3 - x + 1 = 1 - x \\ 1 - x \geqslant 0, \end{cases}$$

立即解决。

一般来说，任何$\sqrt{f(x)} = \sqrt{g(x)}$形式的方程都相当于每个系统的“选择”
$$\begin{cases} f(x) = g(x) \\ f(x) \geqslant 0 \end{cases}$$

通过选择“更简单”的选项，您通常无需搜索 DZ 即可过关。

方程 $\sqrt{x+4} - \sqrt{x-1} = 1$ 等价于方程
$$\sqrt{x+4} = 1 + \sqrt{x-1},$$
(5)

反过来，这相当于等式
$$x+4 = (1 + \sqrt{x-1})^2.$$

事实上，如果$x_0$是方程（5）的根，那么它当然也是方程（6）的根：serdda中的方程$[f(x)]^2 = [g(x)]^2$，即对于任何$f$和$g$，都是从方程$f(x) = g(x)$导出的。反之，若$x_0$是式（6）的根，即数值等式$x_0 + 4 = (1 + \sqrt{x_0-1})^2$成立，则首先有$x_0 + 4 \geqslant 0$；表示$\sqrt{x_0+4} = \sqrt{(1 + \sqrt{x_0-1})^2} = |1 + \sqrt{x_0-1}|$；从$1 + \sqrt{x_0-1} \geqslant 0$、$|1 + \sqrt{x_0-1}| = 1 + \sqrt{x_0-1}$开始；因此，$x_0$是方程（5）的根。

方程（6）等价于每个方程
$$x+4 = 1 + 2\sqrt{x-1} + x-1,$$
$$\sqrt{x-1} = 2,$$
$$x-1 = 4.$$

当然，方程 $\sqrt{x+3} + \sqrt{3x-2} = 7$ 等价于方程 $\sqrt{x+3} = 7 - \sqrt{3x-2},$ (7)
但是，与前面的情况不同，方程（7）不等于方程$x+3 = (7 - \sqrt{3x-2})^2$；鉴于上面证明的 (3) 和 (4) 的等价性，它等价于系统
$$\begin{cases} x+3 = (7 - \sqrt{3x-2})^2 \\ 7 - \sqrt{3x-2} \geqslant 0 \end{cases}$$
以及，进一步，对于每个系统
$$\begin{cases} x+3 = 49 - 14\sqrt{3x-2} + 3x-2 \\ \sqrt{3x-2} \leqslant 7, \end{cases}$$
$$\begin{cases} 7\sqrt{3x-2} = x+22 \\ \sqrt{3x-2} \leqslant 7, \end{cases}$$
$$\begin{cases} 49(3x-2) = (x+22)^2 \\ 3x-2 \leqslant 49. \\ x+22 \geqslant 0. \end{cases}$$

方程 $\sqrt{x-2} + \sqrt{1-x} = 3$ 可以用类似的方式求解，但在这种情况下，更容易立即说它的 ODZ 是一个空集，因此它有根。

***

让我们继续讨论不平等
$$3\sqrt{6+x-x^2} > 4x-2.$$

不等式(8) 等价于总和
$$\begin{cases} 4x-2 \geqslant 0 \\ 9(6+x-x^2) > (4x-2)^2 \end{cases}$$

$$\begin{cases} 4x-2 < 0 \\ 6+x-x^2 \geqslant 0. \end{cases}$$

（求解系统（9）中的第二个，我们同时找到不等式（8）的ODZ。）

事实上，首先让 $x_0$ 是不等式(8)的解，即数值不等式成立 $3\sqrt{6+x-x^2} > 4x-2$。那么让我们证明一下 $x_0$ 是系统 (9) 之一的解。让我们考虑两种情况： $4x_0-2 \geqslant 0$ 和 $4x_0-2 < 0$。如果 $4x_0-2 \geqslant 0$，然后通过数值不等式的属性之一（如果 $a > b \geqslant 0$ 和 $n \in \mathbb{N}$， 那 $a^n > b^n)$ $9(6+x-x^2) > (4x_0-2)^2$;在这种情况下，我也会审查 $x_0$ 是系统（9）中第一个的解。如果 $4x_0-2 < 0$， 那 $x_0$ 是系统 (9) 的第二个解，因为这是真实且自然的 $\sqrt{6+x-x^2} \geqslant 0$;从 $4x_0-2 < 0$ 应该 $\sqrt{6+x-x^2} > 4x_0-2$， 那是 $x_0$ 又是不等式（8）的解。

很容易证明任何$\sqrt{f(x)} > g(x)$形式的不等式都等价于系统的总体
$$\begin{cases} g(x) \geqslant 0 \\ f(x) > [g(x)]^2 \end{cases}$$

（不等式$\sqrt{f(x)} \geqslant g(x)$可以用类似的方式解决。）

通过解决$\sqrt{f(x)} < g(x)$形式的不等式可以更容易地解决这个问题；所以

*) 参见第 17 页的 skoku。重生玩转八零年代 第229节

⟦folio 41⟧

某些不平等相当于一种制度
$$\begin{cases} f(x) < [g(x)]^2 \\ f(x) \geq 0 \\ g(x) > 0. \end{cases}$$

不等式 $\sqrt{x^3-x-1} > \sqrt{x^3-1}$ 等价于系统
$$\begin{cases} x^3-x-1 > x^3-1 \\ x^3-1 \geq 0. \end{cases}$$

任何$\sqrt{f(x)} > \sqrt{g(x)}$形式的不等式都等价于该系统
$$\begin{cases} f(x) > g(x) \\ g(x) \geq 0. \end{cases}$$

***

让我们解决两个更复杂的不等式。 （检查您是否已学会如何证明等价性 - 证明下面的每个等价性。）
$$18\sqrt{2x-3}-9\sqrt{(2x-3)(x-2)} \geq 2\sqrt{x-2}$$
$$18-9\frac{\sqrt{(2x-3)(x-2)}}{\sqrt{2x-3}} \geq 2\frac{\sqrt{x-2}}{\sqrt{2x-3}},$$
$$18-9\frac{\sqrt{x-2}}{\sqrt{2x-3}}-2\left(\frac{\sqrt{x-2}}{\sqrt{2x-3}}\right)^2 \geq 0.$$

辅助不等式$18-9t-2t^2 \geq 0$的解集等于$[-6; \frac{3}{2}]$。因此，不等式(11)等价于不等式
$$0 \leq \frac{\sqrt{x-2}}{\sqrt{2x-3}} \leq \frac{3}{2}$$
$$0 \leq \frac{x-2}{2x-3} \leq \frac{3}{2}$$
$$x-2 \geq 0$$
$$2x-3 > 0$$

（为了编写一个等价于不等式（12）的系统，我们被迫将 ODZ 实际给出的不等式归因于不等式（10））

$$\begin{cases} 0 \leq \frac{x-2}{2x-3} \leq \left(\frac{3}{2}\right)^4 \\ x-2 \geq 0 \\ 2x-3 > 0 \end{cases}$$

进一步的解决方案是显而易见的。
不等式
$$\frac{(x-1)^2}{(3+\sqrt{8+x})^2} > x-7$$
相当于系统的总体
$$\begin{cases} \frac{(x-1)^2}{(3+\sqrt{8+x})^2} > x-7 \\ 3-\sqrt{8+x} = 0 \end{cases}$$
$$\frac{(x-1)^2}{(3+\sqrt{8+x})^2} > x-7$$
$$3-\sqrt{8+x} \neq 0.$$

第一个系统有一个解$x=1$。第二个系统相当于系统

$$\begin{cases} \frac{(x-1)^2}{(3-\sqrt{8+x})^2} > x-7 \\ 3-\sqrt{8+x} \neq 0, \end{cases}$$
$$\frac{(x-1)^2}{(3-\sqrt{8+x})^2} > x-7$$
$$x \neq 1,$$
$$\frac{(3-\sqrt{8+x})^2}{(1-x)^2} > x-7$$
$$x \neq 1,$$
$$\frac{(3-\sqrt{8+x})^2}{(1-x)^2} > x-7$$
$$x \neq 1,$$

我们已经学会了应对不平等$\sqrt{8+x} < 4$。

**有时有用**

解方程
$$\sqrt{2-x}+x-3=\sqrt{x-1}$$
(13)
通过对“sour”进行平方（获得完整的四次方程）。因此，我们首先求出ODZ方程-[1; 2]。在ODZ上
$$\sqrt{2-x}+x-3 \leq \sqrt{2-1}+x-3 = x-2 \leq 0.$$
另一方面，$\sqrt{x-1} \geq 0$。因此，方程(13)等价于系统
$$\begin{cases} \sqrt{2-x}+x-3=\sqrt{x-1} \\ \sqrt{x-1}=0, \end{cases}$$
