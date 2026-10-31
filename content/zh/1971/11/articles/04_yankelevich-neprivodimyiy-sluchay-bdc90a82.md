---
id: 1971-11-yankelevich-neprivodimyiy-sluchay-bdc90a82
issue: kvant_1971_11
year: 1971
number: "11"
title: “不可简化”的情况
authors:
  - Янкелевич В. Г.
rubric: osnovnye-stati
page_first: 22
page_last: 22
page_labels: "20"
tag: 6BS0
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f2d643d864cf52b6c9171da95c2f099c855fa1c0a6f6fa3a08dbf91032442bcb
prompt_sha256: draft-1
translated_from: content/ru/1971/11/articles/04_yankelevich-neprivodimyiy-sluchay-bdc90a82.md
source_content_sha256: 14442e66a19a0ba9a1ae5f763e3c415e96021d33360f96d79e3e14c3a3a5edf6
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

V·G·扬克列维奇

我们的读者，七年级学生 Misha Balkin，问道：“我在参考书中看到了求解三次方程 $x^3 + px + q = 0$ 的卡丹公式：

$$x = \sqrt[3]{\frac{q}{2} + \sqrt{D}} + \sqrt[3]{\frac{q}{2} - \sqrt{D}},$$

其中$D = \left(\frac{p}{3}\right)^3 + \left(\frac{q}{2}\right)^2$。

但在我看来，这个公式并不总是可用。例如，如果我们想使用这个公式求方程 $x^3 - x = 0$ ($p = -1, q = 0$) 的根，我们得到

$$x = \sqrt[3]{\sqrt{-\frac{1}{27}}} + \sqrt[3]{-\sqrt{-\frac{1}{27}}}.$$

这是某种最小数，方程有三个冠：0、1 和 -1。这个矛盾如何成立？>

编辑相信这个问题的答案将会引起我们许多读者的兴趣。我们正在发表一篇由来自库斯塔奈市的 10 年级学生 V. G. Yankelevch 撰写的文章，他讲述了当卡尔达诺夫公式在平方根符号下产生负数时如何求解三次方程。

早在 16 世纪，人们就发现了一个通用公式，可以表达三次方程的解

$$x^3 + px^2 + qx + r = 0$$

(1)

使用算术运算和根知识通过其系数。该公式（称为 Del Ferro 公式或 Tartaglia-Cardano 公式）可以写成如下：

$$x = \sqrt[3]{\frac{c}{54} + \sqrt{\frac{D}{108}}} + \sqrt[3]{\frac{c}{54} - \sqrt{\frac{D}{108}}} - \frac{p}{3},$$

(2)

其中$c = 2p^3 - 9pq + 27r$； $D = p^2q^2 - 4q^3 - 4p^3r + 18pqr - 27r^2$。后来，复数的概念一形成，我们就清楚这个公式可以让我们用任何（复数）系数$p, q, r$获得方程（1）的所有解。但是，不幸的是，即使方程的所有系数都是一般的动作数，那么要使用公式（2）找到（下文称为动作！）解，您必须提取这些数字；当 $D > 0$ 时就会出现这种困难（当方程具有三个不同的实根时正是这种情况）。

考虑具有实判别式和正判别式 $D^*$) 的三次方程 (1)。

我们将证明任何方程（1）都可以简化为以下形式的方程

$$ay^3 - 3by^2 - 3ay + b = 0,$$

(3)

其中$a$和$b$是实数，$a \neq 0$。

首先我们证明方程(3)有根

$$y_1 = \tg \frac{\varphi}{3},$$

$$y_2 = \tg \frac{\varphi + 2\pi}{3},$$

$$y_3 = \tg \frac{\varphi + 4\pi}{3},$$

*) $D$ 称为多项式 $x^3 + px^2 + qx + r$ 的判别式。可以证明$D = (x_1 - x_2)^2 (x_2 - x_3)^2 (x_3 - x_1)^2$，其中$x_1, x_2, x_3$是方程（1）的根。若系数$p, q, r$为实数且$D < 0$，则方程有两个共轭复数根和一个实数根，可立即由式（2）求得。
