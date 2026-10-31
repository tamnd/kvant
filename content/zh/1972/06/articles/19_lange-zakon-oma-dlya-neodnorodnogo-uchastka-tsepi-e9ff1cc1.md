---
id: 1972-6-lange-zakon-oma-dlya-neodnorodnogo-uchastka-tsepi-e9ff1cc1
issue: kvant_1972_6
year: 1972
number: "6"
title: 电路非均匀部分的欧姆定律
authors:
  - Ланге В. Н.
rubric: ekzamenatsionnye-materialy
rubric_sub: Экзаменационные материалы
page_first: 61
page_last: 62
page_labels: 59-60
tag: B2MJ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 47b1aa491c2135ec870d17c7ddb7b83317856dc637280b3418ad3e435d0a9e48
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/19_lange-zakon-oma-dlya-neodnorodnogo-uchastka-tsepi-e9ff1cc1.md
source_content_sha256: 54785fcab857f77c49d81c3625e0c43a2f7245a3b42b9ac8f87339b5d5aab225
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

一段电路的欧姆定律允许人们扩大流过该电路的电流强度，其形式如下：

$$I = \frac{U}{R}.$$

式中，$R$为该路段的电阻，$U$为该路段的电位起点与终点之差，即

$$U = \varphi_1 - \varphi_2.$$

然而，以这种形式写成的法律并不总是适用。为了证明这一点，考虑由源组成的最简单的电路

$$\begin{array}{c}
I \\
R
\end{array}$$

图 1.

电动势$E$、内阻$r$和电阻$R$（图1）的电流。将此链分为两部分$ARB$和$BEA$。当应用于$ARB$节时，公式（1）给出：

$$I_R = \frac{U_{AB}}{R} = \frac{\varphi_A - \varphi_B}{R}.$$

我们尝试使用相同的公式（1）来计算当前强度，搜索$BEA$部分。它的起点和终点是对应的点$B$和$A$。这就是为什么

$$I_E = \frac{U_{BA}}{r} = \frac{\varphi_B - \varphi_A}{r}.$$

如果不注意符号，式（2）和式（3）的分子是重合的，而分母一般来说是不同的。因此，我们必须得出结论

$$I_R \neq I_E,$$

当然，这并没有错，因为在非娱乐电路中，各处的电流强度必须相同。产生误差的原因是公式（1）仅适用于电路的同质部分，即不包含电流源（原电池、电池、介质机、光电池等）的部分。第 $BEA$ 部分是非均匀的 - 它包含一个带有 e 的电流源。 d. c.

对于电路的非均匀部分，欧姆定律的公式是什么样的？事实证明，可以从闭路欧姆定律轻松获得所需的表达式

$$I = \frac{E}{R + r}.$$

让我们将等式（4）简化为一个公分母：

$$IR + Ir = E.$$

第一项包括与均匀面积$ARB$相关的量（参见图1），并且基于等式（1）我们可以写出

$$IR = U_{AB} = \varphi_A - \varphi_B.$$

则式(5)可改写为：

$$Ir = E + (\varphi_B - \varphi_A),$$

在哪里

$$I = \frac{E + (\varphi_B - \varphi_A)}{r} = \frac{E + U_{BA}}{r}.$$

在推导公式（6）时，我们考虑了电路的非均匀部分，其电阻由源的内阻组成。一般来说

⟦folio 60⟧

电路的不均匀部分可能包含不同的电阻（部分地，有时应考虑导线的电阻），然后将公式（6）写成形式

$$I = \frac{(\varphi_1 - \varphi_2) + E}{R_\pi},$$

其中$R_\pi$是截面的总阻力。

根据公式（7），闭路和链的均匀部分的欧姆定律作为特殊情况如下。

事实上，对于闭合链$\varphi_1 = \varphi_2$（因为在这种情况下“部分”的开始和结束是重合的）。那么由式(7)可得

$$I = \frac{E}{R_\pi}.$$

在链 $E = 0$ 均质截面的情况下，公式 (7) 的形式为

$$I = \frac{\varphi_1 - \varphi_2}{R}.$$

（这里$R$不再包含源的内阻。）

使用式（7）解决问题时，应记住e。 d.s.如果当沿着链的同质部分从起点到终点移动时，我们首先经过负条纹，然后经过正条纹，则被认为是正的。如果求解电流大小的结果得到负值，则这意味着该部分电路中的电流以“反向”方向流动，即从该部分的末尾流向开头。

现在让我们考虑几个可以使用公式（7）轻松解决的问题。

任务 1. 确定流经图像到图 2 部分$AB$ 的电流。电动势来源

图 2.

昵称$E = 20 \text{ } \theta$，内阻$r = 1 \text{ } \omega$；点$A$和$B$分别为$\varphi_A = 15 \text{ } \theta$、$\varphi_B = 5 \text{ } \theta$的潜力；导线电阻$R = 3 \text{ } \omega$。

解决方案。考虑点$A$为该段的起点，点$B$为终点，因此取e。 d.s.加上减号，由式(7)可得：

$$I = \frac{(15\theta - 5\theta) - 20\theta}{3\omega + 1\omega} = -2,5 \text{ } a.$$

负号表示电流沿$B \rightarrow A$方向流动，即从电势较低的点流向电势较高的点。顺便说一句，电流的这种“不自然”行为通常在所有电流源内观察到。

任务 2. 两个元素“朝向”彼此连接 (图 3)。确定电势电流 $A$ 和 $B$ 之间的差

图 3.

（在电池端子处）如果$E_1 = 1,4 \text{ } \theta$，$r_1 = 0,4 \text{ } \omega$； $E_2 = 1,8 \text{ } \theta$，$r_2 = 0,6 \text{ } \omega$。

解决方案。公式（7）应用于第$AE_2B$部分给出

$$I = \frac{(\varphi_A - \varphi_B) + E_2}{r_2}.$$

对于第 $BE_1A$ 部分，我们有

$$I = \frac{(\varphi_B - \varphi_A) - E_1}{r_1} = -\frac{(\varphi_A - \varphi_B) + E_1}{r_1}.$$

由于两个部分中的电流相同（目标是无分支的），因此我们可以使这些表达式的右侧相等并求解所得方程：
