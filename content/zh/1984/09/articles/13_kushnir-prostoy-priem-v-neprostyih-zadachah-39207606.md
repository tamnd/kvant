---
id: 1984-9-kushnir-prostoy-priem-v-neprostyih-zadachah-39207606
issue: kvant_1984_9
year: 1984
number: "9"
title: 完成困难任务的简单技巧
authors:
  - Кушнир И. А.
rubric: shkola-v-kvante
page_first: 27
page_last: 28
page_labels: 25-26
tag: MHGB
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 529d7b2108982147eb9b97d7843dc58e3fdd722291c4021210d117b46d5f9098
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/13_kushnir-prostoy-priem-v-neprostyih-zadachah-39207606.md
source_content_sha256: 7d6fd2eebd6007cf4e76de0f29cfaa6b9dedca17e265389e3aa8082e5b69bc7c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

找到满足条件的$Q_T$值

$$\frac{Q-Q_T}{d} = \text{целое число},$$

(1)

其中 $d$ 是找到的值 $Q_T$ 列中的素数。

在第$R=27$行中，条件(1)对应于除数列$d=89$和$d=43$中的表值$Q_T=38$。这些是给定数字 $(89 \times 43=3827)$ 的质因数。

现在让我们分析数字 5251。当我们除以 100 时，我们得到商 $Q=52$ 和余数 $R=51$。对于具有$R>49$的数字，我们将表中的$R$一起输入其“减少”值$R'=100-R$，即本例中的$R'=100-51=49$。在这种情况下，与条件（1）一起，还必须满足以下条件：

$$\frac{Q'+Q_T}{d} = \text{целое число},$$

(2)

其中$Q'=Q+1$。在这种情况下$Q'=52+1=53$。

在行$R=49$中，除数列$d=89$$(53+36=89)$中的$Q_T=36$和除数列$d=59$$(53+6=59)$中的$Q_T=6$满足条件(2)。因此，给定数字的质因数是 $89 \times 59=5251$。

数字是51620。除以20后，剩下的就是分析数字2581。这里是$R=81$。因此，$R'=100-81=19$，$Q=25$。因此，$Q'=25+1=26$。

这里的条件(2)由除数列$d=89$中的$Q_T=63$和除数列$d=29$中的$Q_T=3$钝化。所以，$89 \times 29 \times 20=51620$。

请注意，所有三个数字的公因数是素数 89。

通过表格，不难判断上述数字10607是素数。事实上，在行 $R=07$ 中，没有一个值 $Q_T$ 在从 $Q=106$ 中减去时能够满足条件 (1)。

V.S.基特鲁克

能够应对困难的任务

六年级学生熟悉两个数字之和或差的平方公式。学习如何从代数表达式中分离出完全平方数，“识别”它，然后提取根并不难。这些行动通常有助于解决特定问题。当然，下面给出的问题也可以通过其他方式解决，但是知道如何使用所示的示例可以让申请人“节省”急需的考试时间。

简化表达式

示例 1（密歇根州立大学，机制，1978 年）。差$\sqrt{|40\sqrt{2}-57|}-\sqrt{40\sqrt{2}+57}$是一个整数。找到这个号码。

余所著书中。 V. Nesterenko, S. N. OLEXNIKA, M. K. Potapov “数学入学考试问题”（M., Nauka, 1980），作者用 $x$ 表示所需的数字，发现 $x$ 是数字 10 或 -10 之一，通过比较减法和减法，他们得出结论 $x=-10$ （第 17 页）。 132）。

让我们通过选择一个完整的正方形来解决相同的例子；这个例子对我们以后会有用。

$$A=\sqrt{40\sqrt{2}+57}=\sqrt{25+40\sqrt{2}+32}=\sqrt{(5+4\sqrt{2})^2}=5+4\sqrt{2},$$

$$B=\sqrt{|40\sqrt{2}-57|}=\sqrt{|(5-4\sqrt{2})^2|}=-5+4\sqrt{2}.$$

因此，$B-A=-10$。

示例 2（MSU，机制，1969 年；KPI，1980 年）。简化：

$$\sqrt{x+2\sqrt{x-1}}+\sqrt{x-2\sqrt{x-1}}.$$

解决方案：

$$A=\sqrt{x+2\sqrt{x-1}+1-1}+\sqrt{x-2\sqrt{x-1}+1-1}=\sqrt{(\sqrt{x-1}+1)^2}+\sqrt{(\sqrt{x-1}-1)^2}=|\sqrt{x-1}+1|+|\sqrt{x-1}-1|=\sqrt{x-1}+1+|\sqrt{x-1}-1|.$$

显然$x \geqslant 1$；

a) 对于$2 \geqslant x \geqslant 1$，我们有

⟦folio 26⟧

$$A = \sqrt{x-1} + 1 - \sqrt{x-1} + 1 = 2;$$
6) 在 $x \geqslant 2$
$$A = \sqrt{x-1} + 1 + \sqrt{x-1} - 1 = 2\sqrt{x-1}.$$
示例 3（KPI，1980）。简化：
$$\frac{\sin^4 \alpha + \cos^4 \alpha - 1}{\sin^6 \alpha + \cos^6 \alpha - 1}.$$
解决方案：
$$\frac{\sin^4 \alpha + \cos^4 \alpha - 1}{\sin^6 \alpha + \cos^6 \alpha - 1} = \frac{\sin^4 \alpha + \cos^4 \alpha + 2 \sin^2 \alpha \cos^2 \alpha - 2 \sin^2 \alpha \cos^2 \alpha - 1}{\sin^4 \alpha + \cos^4 \alpha + 2 \sin^2 \alpha \cos^2 \alpha - 3 \sin^2 \alpha \cos^2 \alpha - 1} = \frac{(\sin^2 \alpha + \cos^2 \alpha)^2 - 2 \sin^2 \alpha \cos^2 \alpha - 1}{(\sin^2 \alpha + \cos^2 \alpha)^2 - 3 \sin^2 \alpha \cos^2 \alpha - 1} = \frac{2}{3}.$$
解方程
解无理方程时，不要急于求平方；值得一看，看看是否有可能隔离它？
示例 4（KPI，1979）。解方程：
$$\sqrt{x-2} + \sqrt{2x-5} + \sqrt{x+2+3\sqrt{2x-5}} = 7\sqrt{2}.$$
解决方案：
我们有
$$\frac{1}{\sqrt{2}}(\sqrt{2x-5} + 2\sqrt{2x-5} + 1) + \sqrt{2x-5} + 6\sqrt{2x-5} + 9) = \frac{1}{\sqrt{2}}(\sqrt{(\sqrt{2x-5}+1)^2} + \sqrt{(\sqrt{2x-5}+3)^2} = \frac{1}{\sqrt{2}}(|\sqrt{2x-5}+1| + |\sqrt{2x-5}+3|).$$
所以给定的方程等价于方程
$$\frac{1}{\sqrt{2}}(\sqrt{2x-5} + 1 + \sqrt{2x-5} + 3) = 7\sqrt{2}$$
或 $2\sqrt{2x-5} = 10$，来自 $x = 15$。
示例 5（KSU，经济学院，1978 年）。解方程：
$(\sqrt{4+2\sqrt{3}} - \sqrt{4-2\sqrt{3}})^{2x} + 2^{2x+3} = 144.$
解决方案：
我们有
$$\sqrt{4+2\sqrt{3}} = \sqrt{3+2\sqrt{3}} + 1 = \sqrt{(\sqrt{3}+1)^2} = \sqrt{3}+1;$$
类似于$\sqrt{4-2\sqrt{3}} = \sqrt{3}-1$。因此，给定的方程将采用以下形式
$$4^x + 8\cdot 4^x = 144, x = 2.$$
示例 6（MSU，1978 年，语言学院）。选择数字 $\alpha$ 以使方程 $\sqrt{x-\sqrt{3}} + \alpha^2 x^2 + 2\alpha x(\sqrt{6}-\sqrt{3}) = 6\sqrt{2}-9$ 有解。寻找解决方案。
解：设$x_1$为方程根。然后$x_1 \neq 0$和$\sqrt{x_1-\sqrt{3}} + \alpha^2 x_1^2 + 2\alpha x_1(\sqrt{6}-\sqrt{3}) - 6\sqrt{2}+9 = 0$，或者
$$\alpha^2 + 2\alpha \left(\frac{\sqrt{6}-\sqrt{3}}{x_1}\right) + \frac{\sqrt{x_1-\sqrt{3}} + 9 - 6\sqrt{2}}{x_1^2} = 0.$$
让我们选择一个关于数字 $x_1$ 和 $\alpha$ 的完整正方形。我们有
$$\left(\alpha + \frac{\sqrt{6}-\sqrt{3}}{x_1}\right)^2 + \frac{\sqrt{x_1-\sqrt{3}}}{x_1^2} = 0.$$
由于每一项都不是负数，因此$x_1 = \sqrt{3}$和$\alpha = 1 - \sqrt{2}$。
示例 7. 求解方程 $\sin^2 x + \sin^2 y = \sin x \sin y + \sin x \sin y - 1.$
解：该方程等价于：
$(\sin^2 x - 2 \sin x + 1) + (\sin^2 y - 2 \sin y + 1) + (\sin^2 x + \sin^2 y - 2 \sin x \sin y) = 0$，或$(\sin x - 1)^2 + (\sin y - 1)^2 + (\sin x - \sin y)^2 = 0$，从哪里$x = \sin y = 1$，$x = \sin y$。因此，方程的解将是以下形式的任何对
$$x = \frac{\pi}{2} + 2\pi k, y = \frac{\pi}{2} + 2\pi n, k, n \in Z.$$
练习
1. （MSU，1979，经济学院）求解方程：$\log_{3x+7}(9+12x+4x^2) + \log_{2x+3}\times(6x^2+23x+21) = 4.$
2. （KSU，1978，化学学院）求解方程：$(\sqrt{6+2\sqrt{5}} - \sqrt{6-2\sqrt{5}})^{2x} + 2^{2(x+1)} = 320.$
3. （MSU，1965，力学）找到满足方程的所有数字对
$$\cos x + \cos y - \cos(x+y) = \frac{3}{2}.$$
4. （KSU，1973，力学）解决不等式 $\sqrt{x+4\sqrt{x-4}} - \sqrt{x-4\sqrt{x-4}} \geq 3.$
5. (MSU, 1982, 生物学院) 求函数的最大和最大值
$$y(x) = x + \sqrt{(x^2+6x+9)(x^2+2x+1)}$$
在 $[-4; -\frac{5}{4}].$ 段上

I.A.库欣尔
