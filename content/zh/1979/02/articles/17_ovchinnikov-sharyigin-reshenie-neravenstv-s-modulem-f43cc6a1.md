---
id: 1979-2-ovchinnikov-sharyigin-reshenie-neravenstv-s-modulem-f43cc6a1
issue: kvant_1979_2
year: 1979
number: "2"
title: 用模数求解不等式
authors:
  - Овчинников С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: YI3I
lang: zh
source: kvant_digital
extraction: vision
content_sha256: aecf355a8ac1ef27439a43bf558112b04ffc7ac6f723bc118a57a3f8aa2cc0f4
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/17_ovchinnikov-sharyigin-reshenie-neravenstv-s-modulem-f43cc6a1.md
source_content_sha256: c3755d71a3aa205d6354a10a5457da892503273ac46275af27091af76a5b94e9
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

用模型解决不等式

本文概述了一种技术，在某种意义上，该技术将“自动”将包含模型符号下的变量的不等式的解与变量已经不受模型符号约束的系统和不等式组的解相匹配。

让这些是几个不等式 - 例如，为了简单起见，对于具有相同（相同）变量的不等式：

$$f(x) > 0,$$
$$g(x) > 0.$$

让我们用 $A$ 表示不等式 (1) 的解集，用 $B$ 表示不等式 (2) 的解集。

如果需要找到一组同时满足不等式（1）和不等式（2）的数，即求集合$A$和$B$的交集$C = A \cap B$，则不等式（1）、（2）通过一个带括号的数字连接起来

$$\begin{cases} f(x) > 0, \\ g(x) > 0 \end{cases}$$

被称为不等式系统（“代数和分析原理 10”，第 123 段）。

如果要找到满足不等式(1)或不等式(2)的一组数，即并集$D = A \cup B$集合$A$和$B$，则不等式(1)、(2)用方括号连接

$$\begin{cases} f(x) > 0, \\ g(x) > 0 \end{cases}$$

并被称为一组非

特性 *）。

让我们再重复一遍：当他们寻找交叉点时，他们说“系统”；当他们寻找交叉点时，他们说“系统”；当他们寻找交叉点时，他们说“系统”；当他们寻找关联时，他们会说“整体性”。该表显示了三对相应的可理解字符**)。

正如我们现在所看到的，在解决问题时，我们经常必须考虑系统和聚合的组合；为了避免在这种情况下出现错误，您应该小心使用以下符号。

* *

求解模型符号下包含变量的不等式（“揭示”模型）的一般示例如下。基于模型定义

$$|x| = \begin{cases} x, \text{ если } x \geqslant 0, \\ -x, \text{ если } x < 0, \end{cases}$$

变量的允许值集被分为不相交的子集，在每个子集上，包含 .modula 符号的所有函数都保留其符号。此后，解决原始问题就简化为解决一组不等式系统。

举例来说，您需要解决不等式

$$|x-1| + |x-2| > 3+x$$

非相交处数值轴尺寸

*) 与术语“方程组”和“方程组”的定义绝对相似（“代数和分析原理 10”，第 122 段）。

**) 该表可以用一对术语“合取 - 析取”继续；关于这些术语，请参见，例如，«Kvant»，1971 年，第 4 期，第 4 页。 15，或 1947 年，第 12 期，第 15 页。 14，或 1975 年，第 1 期，第 14 页。 29.

⟦folio 49⟧

选择间隔 $|x| < 1$、$-(x-1)-(x-2) > 3+x$、$1 \leqslant x < 2$、$(x-1)-(x-2) > 3+x$、$x \geqslant 2$、$(x-1)+(x-2) > 3+x$。

上层系统的解集是交集$|x| < \infty$； $1[\cap] < \infty$； $0[$，即区间$|x| < \infty$； $0[$，一般系统无解；最后，下系统的解集为交集$[2; +\infty][\cap]; 6 +\infty[$，即区间$|x| < \infty$； $0[$，组合结果集（全部！），我们得到答案：$|x| < \infty$； $0[ \cup ] 6; +\infty[$。

使用这种解决方法，通常需要考虑多种情​​况，有时甚至需要考虑子情况。此外，有时揭示模型会涉及技术困难（参见下面的示例 4）。

* *

上面承诺的例子基于一个简单的定理：

1) $|f(x)| \leqslant g(x)$ $\Leftrightarrow$ $\begin{cases} f(x) \leqslant g(x), \\ f(x) \geqslant -g(x); \end{cases}$
2) $|f(x)| \geqslant g(x)$ $\Leftrightarrow$ $\begin{cases} f(x) \geqslant g(x), \\ f(x) \leqslant -g(x). \end{cases}$

通过“揭示”模型可以很容易地证明这一点。例如，让 $x_0$ 成为不等式 $|f(x)| \leqslant g(x)$ 的解，即 $|f(x_0)| \leqslant g(x_0)$。

然后$g(x_0) \geqslant 0$。如果$f(x_0) \geqslant 0$，则$|f(x_0)| = f(x_0)$和不等式(3)采用$f(x_0) \leqslant g(x_0)$的形式。

从$f(x_0) \geqslant 0$和$g(x_0) \geqslant 0$开始，$f(x_0) \geqslant -g(x_0)$。

不等式(4)、(5)意味着在所考虑的情况下，$x_0$是系统$\begin{cases} f(x) \leqslant g(x), \\ f(x) \geqslant -g(x). \end{cases}$的解，如果$f(x_0) < 0$，则$|f(x_0)| = -f(x_0)$，并且不等式(3)采用$-f(x_0) \leqslant g(x_0)$的形式，这相当于不等式(5)。在这种情况下，由于 $f(x_0) < 0$ 和 $g(x_0) \geqslant 0$，不等式 (4) 成立。

自行完成定理的证明。

当然，当用严格不等式 $<$ 的符号替换严格不等式 $\leqslant$ 的升号时，该定理仍然有效。

* *

示例 1.（莫斯科国立大学格鲁吉亚学院，1977 年）。解决不平等问题
$2|x+1| > x+4$.

解决方案。
$2|x+1| > x+4 \Leftrightarrow \begin{cases} 2x+2 > x+4, \\ 2x+2 < -x-4 \end{cases} \Leftrightarrow \begin{cases} x > 2, \\ x < -2. \end{cases}$

示例 2（莫斯科国立大学地质学院，1977 年）。解决不平等问题
$|x-2| \leqslant 2x^2-9x+9$.

解决方案。
$|x-2| \leqslant 2x^2-9x+9 \Leftrightarrow \begin{cases} x-2 \leqslant 2x^2-9x+9, \\ x-2 \geqslant -2x^2+9x-9 \end{cases} \Leftrightarrow \begin{cases} 2x^2-10x+11 \geqslant 0, \\ 2x^2-8x+7 \geqslant 0. \end{cases}$

所得系统中包含的不等式的解在 图 1 上以不同的宽度表示。取它们的交集，我们得到答案：
$-\infty; \frac{4-\sqrt{2}}{2} \cup \left[ \frac{5+\sqrt{3}}{2}; +\infty \right]$.

让我们回到最初通过“开放”模型解决的不平等问题。

示例 3. 解决不等式
$|x-1| + |x-2| > 3+x$.

图 1.

⟦folio 50⟧

解决方案。应用该定理两次，我们有
$$|x-1|+|x-2| > 3+x \Leftrightarrow
\Leftrightarrow |x-1| > 3+x-|x-2| \Leftrightarrow
\Leftrightarrow \begin{cases} x-1 > 3+x-|x-2|, \\ x-1 < -3-x+|x-2| \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} |x-2| > 4, \\ |x-2| > 2x+2 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x-2 > 4, \\ x-2 < -4, \\ x-2 > 2x+2, \\ x-2 < -2x-2 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x > 6, \\ x < -2, \\ x < -\frac{4}{3}, \\ x < 0 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x \leq 2, \\ 3^x \geq 1, \\ 3^x \geq 9, \\ x \leq 0 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x \leq 2, \\ x \geq 0, \\ x \geq 2, \\ x \leq 0 \end{cases}$$

答案：$]-\infty;0[ \cup ]6;+8[$。

通过“扩展”模型，可以轻松获得之前所有问题的解决方案。下面的例子很难解决，而证明的定理却很容易解决。

示例 4. 解决不等式
$$|3^x+4x-9|-8| \leq 3^x-4x-1.$$

解决方案。再次应用该定理两次：
$$||3^x+4x-9|-8| \leq 3^x-4x-1 \Leftrightarrow
\Leftrightarrow \begin{cases} |3^x+4x-9| \leq 3^x-4x+7, \\ |3^x+4x-9| \geq -3^x+4x+9 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} 3^x+4x-9 \leq 3^x-4x+7, \\ 3^x+4x-9 \geq -3^x+4x-7, \\ 3^x+4x-9 \geq -3^x+4x+9, \\ 3^x+4x-9 \leq 3^x-4x-9 \end{cases}$$
因此，所需的集合等于$[0; 2] \cap (1-\infty; 0] \cup [2; +\infty]$。

答案：$\{0, 2\}$。

我们将以带有参数的不等式结束本注释。

示例 5. 解决不等式
$$|1-|x||<a-x.$$

解决方案。
$$1-|x||<a-x \Leftrightarrow
\Leftrightarrow \begin{cases} 1-|x| < a-x, \\ 1-|x| > -a+x \end{cases}$$

⟦folio 51⟧

已解决的系统
$$\begin{cases} x < \frac{a+1}{2}, \\ a > -1. \end{cases}$$

在 图 4 上，这两个集合的交集被涂上阴影，即相当于原不等式的系统解的集合。由此图已经很容易写出答案了：对于$a \in ] -\infty; -1]$没有解决方案，对于$a \in ] 1; +\infty[$

我们有 $x \in ] -\infty; \frac{a-1}{2}$[$,$ $a \in ] 1; +\infty[$

我们有 $x \in ] -\infty; \frac{a+1}{2}$[$.$

细心的读者可能会注意到以下几点：如果作者已经使用了$Oxa$平面，那么从一开始就可以更容易地在这个平面上描绘函数的图像
$$a=x+|1-|x|$$
然后，查看该图上方的区域，写下答案。这位读者当然是对的。 （图 4 处的红线是函数 $a=x+|1-|x|$ 的图像。）

使用坐标平面的方法非常强大，坐标平面的轴之一是参数值的轴，许多难题都可以在它的帮助下解决。

震惊
求解以下不等式（问题 1-4）：
1. （莫斯科国立大学生物系，1968）$|3x+2| \leq x^2+x$。
2. （莫斯科国立大学物理学院，1974 年）$3|x-1| > (x-1)^2+1$。
3. （莫斯科国立大学格鲁吉亚学院，1977 年）
a) $3|x-1| \leq x+3$;
b) $4|x+2| < 2x+10$;
b) $3|x+1| \geq x+5$.
4. （莫斯科国立大学地质学院，1977）
a) $3x^2-|x-3| > 9x-2$;
b) $x^2+4 \geq |3x-2|-7x$;
b) $x^2-|5x-3| < x<2$.
5. （莫斯科国立大学经济学院政治经济学系，1977）
a) 确定对于哪一个$a$，不等式$3-|x-a| > x^2$ 至少有一个负解。
b) 确定对于哪一个$a$，不等式$2>|x+a|+x^2$ 至少有一个正解。

*) 参见 «Kvant»，1970 年，第 9 期，第 14 页。 19.
