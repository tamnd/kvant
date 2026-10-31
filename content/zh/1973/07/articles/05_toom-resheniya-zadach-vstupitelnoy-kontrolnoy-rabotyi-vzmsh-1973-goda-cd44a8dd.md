---
id: 1973-7-toom-resheniya-zadach-vstupitelnoy-kontrolnoy-rabotyi-vzmsh-1973-goda-cd44a8dd
issue: kvant_1973_7
year: 1973
number: "7"
title: VZMSH 1973入门测试工作问题的解决方案
authors:
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 25
page_labels: 21-23
tag: KEAL
lang: zh
source: kvant_digital
extraction: vision
content_sha256: af944150fbcf27391d93f014b9c08c709edba73db55045caa5981082ccf4124b
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/05_toom-resheniya-zadach-vstupitelnoy-kontrolnoy-rabotyi-vzmsh-1973-goda-cd44a8dd.md
source_content_sha256: 0b887c06c00b011c20ed2d4a9fe537f68f45d063e1937ea8f5844dae2ac7d5a8
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

VZMSH 1973入门测试工作问题的解决方案
A·L·图姆

在本期中，我们发布了 1973 年 VZMSH 的介绍性工作中最有趣问题的解决方案（参见 . «Kvant» 第 1 期，1973 年，第 14 页。 49）。

问题2.是否存在$(k+1)$这样的整数？让我们用 $x$ 表示它的第一个数字，用 $y$ 表示划掉后剩下的数字。那么原数就是$10^k x + y$。它在条件上与 57$y$ 一致：

$$10^k x = 56y.$$

因为56能被7整除，所以$x$能被7整除。但$x$是数字，所以是$x = 7$，$y = 10^k/8$。

对于$k \geq 3$，数字$y$是一个整数。通过点击$k = 3$，我们得到可能的答案之一：

$$10^k x + y = 7125.$$

问题 5. 黑板上写着 4 个数字。将它们以所有可能的方式两两相加，得到以下数字和：2、4、9、9、14、16。黑板上写了什么数字？

让我们用 $A$ 表示原始数字中最小的数字，用 $B$ 表示下一个最大的数字，用 $C$ 表示下一个数字，用 $D$ 表示最大的数字。所以，$A \geq B \geq C \geq D$。那么它们的二之和之间存在以下不等式：

$$A + B \leq A + C \left\{ \begin{array}{l} \leq A + D \\ \leq B + C \end{array} \right\} B + D \leq$$

Using these inequalities, it is easy to unambiguously distribute the numerical values ​​given in the conditions between the sums, which is what has been done.从他们四个人身上可以找到答案：

$$A = -1,5; \quad B = 3,5;$$

$$C = 5,5; \quad D = 10,5.$$

有必要检查其余两项金额是否也与条件中规定的相同。

Problem 6. Is it possible to consider 9 numbers: 1, 2, 3, 4, 5, 6, 7, 8, 9 in a circle so that the sum of any three numbers in a row is divisible by 3 and is: a) greater than 9; b) 超过 12 个？

a）这是可能的。例如：1、9、2、7、3、5、4、6、8。

b) 这是不可能的。令每个三元组相邻数字的总和至少为 15。那么，由于所有相邻数字的总和

⟦folio 22⟧

问题7. 三角形ABC 在顶点A 附近转弯后，位置为$AB_1C_1$。让我们证明，如果线AC平分线段$BB_1$，则线$AB_1$平分线段$CC_1$。

让我们用$M$表示线$AC$和$BB_1$的交点。两种情况不同。

a) $M$ 与 $A$ 相同。那么$A$就是线段$BB_1$的中心，因此旋转角度为$180^\circ$。但$A$是线段$CC_1$的中心，当然，$AB_1$平分$CC_1$。

6) $M$ 与 $A$ 不同。然后在三边上$\triangle ABM = \triangle AB_1M$。因此$MAB = MAB_1$。

如果点 $C$ 与点 $M$ 位于 $A$ 的同一侧，则角度 $CAB$ 和 $CAB_1$ 与该角度重合。如果点 $C$ 位于对边，则角度 $CAB$ 和 $CAB_1$ 与其相邻。在这两种情况下

$$CAB_1 = CAB = C_1AB_1,$$
即$AB_1$是$A$在$\triangle CAC_1$中的二等角。既然是等距，那么$AB_1$也是中位数，这就是需要证明的。

问题 8. 将数字 203 想象为几个正和 max 的和，这样这些和的乘积就可以是 203。

所需的数字甚至可以视为整数：

$$203 = 29 + 7 + 1 \dots + 1 = 167 \text{ раз} = 29 \cdot 7 \cdot 1 \dots 1. 167 \text{ раз}$$

（对于非整数还有许多其他答案）。

问题 10. 4 条不同的直线可以将平面分为多少部分？我们将其应用于每种情况。

如果所有线都是平行的，则有五个部分。让我们证明在所有其他情况下至少有八个部分。 Let us draw such a large circle that all intersection points are inside it (see 图 1, where everything inside the circle is not drawn for clarity).八个未交叉的圆圈从中出现，进入八个区域。让我们证明所有这些区域都属于不同的部分。让我们假设两个区域属于同一部分（图 1 上的区域$A$ 和$B$）。那么连接它们的四个环属于两条平行线（参见图1）。但随后另一条线与它们相交，仍然将 $A$ 与 $B$ 分开。

现在让我们估计最大可能的零件数量。我们将一一进行线路。一般而言更容易推理：让上飞机

⟦folio 23⟧

图 3.

$n$直线已经进行过，我们正在进行$n + 1$次。显然，它上面不超过$n$个交点，将其分成不超过$n + 1$块。每一块将一些部分分成两部分。因此，零件数量增加不超过$n + 1$。对于一个直线部分总是有两个，因此对于四个，不再有直线部分

$$2 + 2 + 3 + 4 = 11.$$

因此，要么有五个部分，要么至少有八个且不再相同。 图 2 中的例子表明所有这些情况都是可能的。

笔记。其他解决方案也是可能的：一种或另一种帐户搜索。 Our reasoning can easily be restored to the case of $n$ lines and allows us to prove that the number of parts is either equal to $n + 1$, or not less than $2n$ and not more than $\frac{1}{2} (n^2 + n + 2)$.然而，对于大 $n$ ，并非该项目中的所有数字都是可能的。 （哪些数字是可能的，哪些不是未知的）。

问题 11。早上，Kolya 和 Olya 决定给氢气浇水。科利亚打开水龙头，给他的喷壶装满水，紧接着奥利亚就把她的喷壶放在小溪下面。 Kolinaleika 需要 15 秒，Olina 需要 10 秒。装满喷壶后，每个孩子无需启动即可倒氢气。水从 Kolinoilika 落下需要 60 秒，从 Olina 落下需要 45 秒。 As soon as the milk tank turns out to be empty, each time we change it, we substitute it under a stream of water, and if at this moment we start the water with another, then we will prove until the tap is free, and immediately begin to fill the water tank.当一个人没有拿起他的莱卡时。当人不打水时，水会倒入水龙头下的桶中。如果没有人接水，15分钟内桶就会被装满。如果Kolya和Olya一直在倒氢气，打开水龙头需要多长时间才能将桶装满？就像水从桶的边缘被抽出来一样，谁会是我之后第一个打水的人？

这个问题可以用图来方便地解决。我们来画一张科尔和奥利亚的行动时间表。填充肺部将用移除表示，浇水用红色表示，等待用黑色表示。方便的取刻度如下：一个单元格内有5秒。 The beginning of the graph is shown at 图 3. If you complete the graph to the 50th cell, you will notice that the 48th cell essentially coincides with the 2nd (Kolya 5 s fills his lung, and Olya waits); 49日与3日重合； 50 号 - 从 4 号开始，依此类推。因此，Kolya 和 Olya 的动作将每 46 个单元（230 秒）定期重复一次。该图显示，在一个时期内，超过 29 个单元格将水倒入桶中。由于 15 分钟对应 180 个单元格，并且 180 = $6 \cdot 29 + 6$，因此必须经过 6 个完整周期和第 7 个周期的一部分，直到桶装满。

根据第一期的图表，我们确定这部分是 11 个单元格。总共，直到桶装满为止，会经过$6 \cdot 46 + 11 = 287$个细胞，即23分55秒。使用同一张图，我们看到奥利亚将是第一个在肺部充满水后向其充满水的人。
