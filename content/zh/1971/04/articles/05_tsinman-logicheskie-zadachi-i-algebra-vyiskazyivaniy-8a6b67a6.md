---
id: 1971-4-tsinman-logicheskie-zadachi-i-algebra-vyiskazyivaniy-8a6b67a6
issue: kvant_1971_4
year: 1971
number: "4"
title: 逻辑问题和命题代数
authors:
  - Цинман Л. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14, 16, 17
tag: R5P5
lang: zh
source: kvant_digital
extraction: vision
content_sha256: eaa0063c5fe5790817378b13b13c2e5dd2d2af6dfbf6f314ddb57c1248378eff
prompt_sha256: draft-1
translated_from: content/ru/1971/04/articles/05_tsinman-logicheskie-zadachi-i-algebra-vyiskazyivaniy-8a6b67a6.md
source_content_sha256: 5ea05d0c4bf6f5c2873a6eb158d6f236416380caeb63477f9ef71aff442ff630
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

逻辑问题和命题代数

L·L·钦曼

让我们从几个逻辑问题的表述开始。

任务 1. 家长会后，一位家长找到老师。

“你没有把我儿子列为好学生，”他说。 “但我的费迪亚是一名优秀的学生，而且还是班上最好的运动员。”

“是的，你说得对。”老师回答道。 “但我们认为一个好学生是一个学习好的学生，遵守纪律，帮助那些学习落后的人，此外，还参与科学界的工作或参与争论。”还有你的费迪亚...

老师还要对费奥多·帕莱说什么呢？

问题 2. 因此，有一次需要同时讯问三名证人：克劳德、雅克和迪克。他们的证词遭到其他人的反驳，每个人都被指控撒谎。克劳德说雅克在撒谎，雅克指责迪克撒谎，因此迪克坚持不相信克劳德或雅克。但他很快就把他们公开了，没有问他们任何问题。哪个证人回答了真相？

问题3. 一名男子被野人俘虏，并被关在一个有两个出口的地牢里。野蛮人的首领为俘虏提供了以下拯救的机会：“一个出口通向自由，另一个出口则导致死亡。你可以选择任何人。我们帮助我的证人做出选择。他会留在这里

会回答一个问题——任何我们想问他的问题。但我警告自己：如果这个警卫心情好，那么他说的是真话，但如果他心情不好，那么他就是在说谎！

沉思片刻后，聚集在一起的洛伊克问了一个问题，然后他明确地选择了通向自由的出口。那个问题是什么？

与所列出的逻辑问题类似的逻辑问题经常出现在科普出版物中。解决这些问题不需要任何逻辑领域的特殊知识，只需要相当发达的逻辑思维。但是想象一下，一个人负责解决一些数值问题（运动、浇注），但不知道如何自由地进行代数变换和求解方程。在不使用辅助工具的情况下解决逻辑问题时，您会发现自己处于大致相同的位置，这称为命题代数或逻辑代数（与学校学习的数字代数相对）。

本文的目的是向读者介绍代数必要性的初步信息，并利用所获得的知识来解决上述问题。但请注意，命题代数不仅用于解决逻辑问题（这只是其应用之一），而且它也很重要

⟦folio 16⟧

否定陈述
语句否定的符号是$A : \bar{A}$。语句$A$的否定对应于语句“not $A$”（“$A$不是真的”）。因此，由如下真值表确定：

| $A$ | $\bar{A}$ |
| :--- | :--- |
| 1 | 0 |
| 0 | 1 |

使用语句代数中引入的运算，可以从各个语句$A, B, C$...构造复杂的代数表达式，例如：$\bar{A} \vee B; \bar{A} \wedge B; (A \vee \bar{B}) \wedge C$。

与数值代数一样，条件是乘法运算比加法运算更古老。这使您可以避免编写一些括号。现在的表达

$((A \wedge B) \vee ((\bar{A} \vee B) \wedge C))$

可以重写为以下形式

$A \wedge B \vee (\bar{A} \vee B) \wedge C$.

如果您知道代数表达式中包含的每个语句的含义，那么使用真值表您可以找到该代数表达式的值。例如，让我们找到代数表达式 $\bar{A} \vee \bar{B}$ 及其分量 $A$ 和 $B$ 所有可能值的值：

| $A$ | $B$ | $\bar{A}$ | $\bar{B}$ | $\bar{A} \vee \bar{B}$ |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 1 | 0 | 0 | 0 |
| 1 | 0 | 0 | 1 | 1 |
| 0 | 1 | 1 | 0 | 1 |
| 0 | 0 | 1 | 1 | 1 |

首先，使用前两列中的值填充第三列和第四列，然后根据加法的定义填充最后一列。该表称为表达式 $\bar{A} \vee \bar{B}$ 的真值表。

现在让我们为 $\bar{A} \wedge \bar{B}$ 构建一个真值表：

| $A$ | $B$ | $\bar{A} \wedge \bar{B}$ |
| :--- | :--- | :--- |
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

上表中的以下各列结果是相同的。这意味着对于语句$A$和$B$的任何值，表达式$\bar{A} \vee \bar{B}$和$\bar{A} \wedge \bar{B}$具有相同的含义。我们将这样的代数表达式称为等价的。为了记录等价性，使用身份符号：

$$\bar{A} \wedge \bar{B} \equiv \bar{A} \vee \bar{B}$$

这两个等价表达具有相同的含义，但用不同的词语表达。

事实上，如果$A$和$B$是一些陈述，那么$\bar{A} \wedge \bar{B}$表示复杂陈述“两个给定陈述都为真不是真的”，$\bar{A} \vee \bar{B}$表示复杂陈述“至少一个给定陈述为假”。

真值表中最后一列由 1（或 0）组成的代数表达式也称为真真（相当于假），并用字母 $H$（字母 $J$）表示。

使用真值表，总是很容易确定两个给定的代数表达式是否等价。

让我们提出最简单的等价物，其中一些我们

⟦folio 17⟧

接下来我们将使用它们作为规则。

1. $A \wedge B \equiv B \wedge A$.
2. $A \vee B \equiv B \vee A$.
3. $(A \wedge B) \wedge C \equiv A \wedge (B \wedge C)$.
4. $(A \vee B) \vee C \equiv A \vee (B \vee C)$.
5. $A \wedge (B \vee C) \equiv (A \wedge B) \vee (A \wedge C)$.
6. $A \vee (B \wedge C) \equiv (A \vee B) \wedge (A \vee C)$.
7. $A \wedge A \equiv A$.
8. $A \vee A \equiv A$.
9. $\overline{A} \wedge \overline{B} \equiv \overline{A} \vee \overline{B}$.
10. $\overline{A} \vee \overline{B} \equiv \overline{A} \wedge \overline{B}$.
11. $\overline{A} \equiv A$.
12. $A \wedge \overline{A} \equiv \overline{J}$.
13. $A \vee \overline{A} \equiv \overline{H}$.
14. $A \wedge \overline{J} \equiv \overline{J}$.
15. $A \vee \overline{H} \equiv \overline{H}$.
16. $A \wedge \overline{H} \equiv A$.
17. $A \vee \overline{J} \equiv A$.

如果我们像上面对规则 9 所做的那样想象规则 1-17 的实质含义，那么这些等价物将变得明显且易于记住。

列出的一些规则，即 1-5，与数值代数中加法和乘法运算的众所周知的属性类似。因此，在命题代数中，我们可以执行类似于数值代数中的代数变换。特别是，我们可以使用多项式与多项式相乘的规则来“乘”两个代数语句。

但命题代数也有其特定的规则，例如6。

**问题1的解决方案**

让我们引入该语句的符号：

$A$：“Fedya 是个好学生”；
$B$：“Fedya 遵守纪律”；
$C$：“Fedya帮助那些学习落后的人”；
$D$：“Fedya 参与科学界的工作”；
$E$：“Fedya 喜欢运动。”

现在，“费迪亚是一个好学生”这一说法，根据“定义的”好学生，这个教学，

体，可以这样写：

$A \cup B \cup C$ ($D \cup E$).

在命题代数的语言中，这个复杂的陈述将采用代数表达式的形式

$A \wedge B \wedge C \wedge (D \vee E)$.

老师声称“这不是真的（Fedya 是个好学生）”，即

$$\{A \wedge B \wedge C \wedge (D \vee E)\} = 1.$$

现在让我们首先根据规则 9 变换左侧的代数表达式（虽然在这种情况下，否定位于四个分量的逻辑乘积之上，但很容易看出 9 的等价性在这种更一般的形式中仍然有效），然后根据规则 10：

$$\begin{align*}
\{A \vee \overline{B} \vee \overline{C} \vee (D \vee E)\} &= 1; \\
\{A \vee \overline{B} \vee \overline{C} \vee \overline{D} \wedge \overline{E}\} &= 1.
\end{align*}$$

费丁·波波 (Fedin Popau) 会声称（老师也同意他的观点）

$$\{A\} = 1$$

（Fedya 是一名优秀的学生！），而且

$$\{E\} = 1$$

（Fedya 是班上最好的滑雪者！）。那么在(1)中，前两项是假的，可以根据规则17和14将其丢弃。

我们明白了

$$\{B \vee \overline{C}\} = 1.$$

这意味着老师想向Fedya抱怨，要么是因为Fedya不遵守纪律，要么是因为他不帮助那些学习落后的人（或者也许Fedya同时成为这两个缺点）。

**问题2的解决方案**

让我们用字母$K$、$J$、$D$相应地表示证人克劳德、雅克和迪克的证词。我们不知道这些读数哪些是真实的，哪些是错误的。但我们知道以下几点：

1) 要么克劳德说真话，然后雅克说谎，要么克劳德说谎，然后雅克说真话；
