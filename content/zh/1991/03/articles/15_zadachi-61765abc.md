---
id: 1991-3-zadachi-61765abc
issue: kvant_1991_3
year: 1991
number: "3"
title: 任务
rubric: konkurs-imeni-a-p-savina
rubric_sub: Конкурс имени А. П. Савина
page_first: 50
page_last: 51
page_labels: 48-49
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 0602e90153651f27f43356e357029bed2634995f717a3b5edefb59ef9afb9b52
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/15_zadachi-61765abc.md
source_content_sha256: e7af640bb052c5c49933e5c87b3887f2c382d03fa637f55eb5ce77f8d1716292
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 48⟧

任务

19. 等边三角形ABC位于平面上。指出该平面上所有三角形 ABM 和 ASM 都是等边的点 $M$。

A·萨文

20. 安德烈 (Andrey) 根据自己的判断将一堆 200 根火柴分为 6 堆（每堆至少包含一根火柴），然后是鲍里斯 (Boris)。使其中两堆中的火柴数量相等，从一堆中取出几根火柴。我们将鲍里斯·安德烈 (Boris Andrey) 的比赛场数称为“鲍里斯·安德烈 (Boris Andrey)”。鲍里斯力争参加尽可能少的比赛。安德烈应该怎样打才能确保自己获得最大可能的胜利呢？

X·海莫夫

21. 在棋盘上，横线和竖线分别编号为 1 到 8。 棋盘上放置 8 个车，使它们不相邻。对于每个车，我们计​​算它所在的水平线和垂直线的数量的乘积。让我们计算这些乘积的总和。证明对于与给定的车中心对称的车排列，以类似的方式获得的总和等于原始的总和。

普罗伊兹沃洛夫

⟦folio 49⟧

---
running_head:
folio:
---

事实上，总函数$f(x)+g(x)$的最小值是在线段$[a; b]$的某个点达到的。此时，函数$f(x)$和$g(x)$的值不小于它们的最小值。显然，如果在同一点达到最小值 $f(x)$ 和 $g(x)$，不平等就会变成平等。

$n$ 函数的情况完全相同：

$$\min f_1(x) + \dots + \min f_n(x) \leqslant \leqslant \min (f_1(x) + \dots + f_n(x)).$$

通过归纳法很容易得到证明。在右侧，我们将一次选择一个函数：$\min (f_1(x) + \dots + f_n(x)) \geqslant \min (f_1(x) + \dots + f_{n-1}(x)) + \min f_n(x)$等等。

二次函数和二次不等式的最小值

让我们从 $f(x)=ax^2+2bx$ 形式的二次函数开始，其中 $a>0$。要找到最小值，请选择一个完整的正方形

$$ax^2+2bx=a\left(x^2+2\frac{b}{a}x+\frac{b^2}{a^2}-\frac{b^2}{a^2}\right)=a\left(\left(x+\frac{b}{a}\right)^2-\frac{b^2}{a}\right)=a\left(x+\frac{b}{a}\right)^2-\frac{b^2}{a}.$$

因此，在 $x=-\frac{b}{a}$ 处达到最小值，并且等于 $f\left(-\frac{b}{a}\right)=-\frac{b^2}{a}$。

现在到 $n$ 函数

$$f_1(x)=a_1x^2+2b_1x,$$
$$f_2(x)=a_2x^2+2b_2x,$$
$$\dots$$
$$f_n(x)=a_nx^2+2b_nx$$

让我们接受我们的基本不平等。函数 $f(x)$ 的最小值为 $x=$
