---
id: 1978-9-klumova-nomogrammyi-iz-vyiravnennyih-tochek-37093a9b
issue: kvant_1978_9
year: 1978
number: "9"
title: 对齐点的列线图
authors:
  - Клумова И. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 32
page_last: 33
page_labels: 30-31
tag: P5CH
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1881f4717dff6b04bc6fe4ca7d38a5ac990f9289439eaca7cb4d46c9ed8fb54a
prompt_sha256: draft-1
translated_from: content/ru/1978/09/articles/09_klumova-nomogrammyi-iz-vyiravnennyih-tochek-37093a9b.md
source_content_sha256: b152c4927633b82917bfad892256829f315cf6429fd9ef3fc4afb434d5c3a738
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

点对齐的列线图

V. Vavilov 的文章（第 22 页）讨论了使用网格列线图的第二步和第三步方程的近似解。我们。 V. M. Bradis 的《四位数数学表》第 83 部分还显示了方程 $x^2 + px + q = 0$ 近似解的列线图（表 XXII）。然而，这不是网格列线图，而是所谓的点对齐列线图。本说明讨论了它是什么、如何获得以及如何使用这样的列线图。

让我们画两条垂直平行直线 - 轴 $p$ 为截止点 $A$ 的起点，轴 $q$ 为截止点 $B$ 的起点（图 1；在此 图 上，线段 $AB$ 由轴 $p$ 重新分布， $q$，但这完全没有必要）。

让我们取任意数 $\alpha$、$\beta$ 和一个正数 $a$。在 $p$ 轴上，我们取点 $C$，坐标为 $-a^{\alpha-\beta}$，在 $q$ 轴上，取点 $D$，坐标为 $-a^\alpha$。让$[AD]\cap \bigcap[BC] = E$。

让我们通过$E$画一条不平行于轴$p$、$q$的任意直线。让我们用$p_0$表示这条线与$p$轴的交点$M$的坐标，并用$q_0$表示$N$与$q$轴的交点。然后

$$a^\alpha + p_0 a^\beta + q_0 = 0,$$

(1)

即数字 a 是方程的根

$$x^\alpha + p_0 x^\beta + q_0 = 0.$$

(2)

线 $MN$ 可以通过以下三种方式之一与轴 $p$、$q$ 相交：$p_0 < 0$、$q_0 > 0$ (图 1)； $p_0 > 0$、$q_0 < 0$（图2）； $p_0 < 0$、$q_0 < 0$ (图 3)。让我们针对 图 1 中描述的情况证明等式（1）（其他两种情况类似处理）。

根据三角形$AEC$和$BED$的相似性，我们有$$\frac{|BD|}{|AC|} = \frac{|DE|}{|AE|},$$，从$$\frac{|DE|}{|AE|} = \frac{a^\alpha}{a^{\alpha-\beta}} = a^\beta.$$进一步，根据三角形$AEM$和$NED$的相似性，可以得出$$\frac{|DN|}{|AM|} = \frac{|DE|}{|AE|},$$，即$$\frac{a^\alpha + q_0}{-p_0} = a^\beta$$（图1），得到（1）。

让我们固定任意 $\alpha$、$\beta$ 并考虑所有可能的方程。

⟦folio 31⟧

图 3.

意见

$$x^\alpha + px^\beta + q = 0.$$ (3)

用于查找此类方程的正根的列线图绘制如下：参数 $a$ 属于每个正数，并且对于每个正数，按如上所述构造点 $E$；由相应参数值放置的结果点通过平滑曲线 $\Gamma$ (图 4) 连接。

如果我们现在想要使用此列线图来近似找到特定方程 $x^\alpha + p_0 x^\beta + q_0 = 0$ 的正根，我们需要在 $p$ 轴上取坐标 $p_0$ 的点 $M$，在 $q$ 轴上取坐标 $q_0$ 的点 $N$，并绘制一条直线 $MN$。直线$MN$与曲线$\Gamma$的每个交点根据(1)给出方程(2)的正根。

现在很清楚为什么以这种方式构建的列线图被称为表达点列线图：与方程的系数$p, q$相对应的点和与方程$x^\alpha + px^\beta + q = 0$所需的正根相对应的点位于同一条直线上。

练习
1. 从表达点构建列线图以找到方程的正根

$$x^m + px^n + q = 0$$

如果$m = 3, n = 2; m = 4, n = 1; m = 4, n = 2; m = 4, n = 3.$
