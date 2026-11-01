---
id: 1980-7-kotov-semeystvo-kubicheskih-parabol-eaaa0b52
issue: kvant_1980_7
year: 1980
number: "7"
title: 三次抛物线族
authors:
  - Котов Ю. В.
rubric: raznoe
rubric_sub: Разное
page_first: 20
page_last: 20
page_labels: "18"
tag: 8QPV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 41446ca7614dbdba62ffb99266e0fed7a397a373e4543a4f341a3ecbfa78f8b2
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/07_kotov-semeystvo-kubicheskih-parabol-eaaa0b52.md
source_content_sha256: 0c87d5cc85b5a22d9dac2c8e93dc5752aaf717863869c570b38a230e60eae553
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

三次抛物线族

看封面的第二页，一族169条三次抛物线组成了一个梅花图案，其“作者”是一台计算机。本文将探讨如何在实践中使用此类曲线。

在计算机图形学中，首先需要绘制平滑的曲线。有时，这必须通过确定与给定方程相对应的曲线来完成。在其他情况下，曲线首先替换其分量Δx₃，Δy₃）。众所周知，斜率等于 kᵢ = Δyᵢ/Δxᵢ。因此，我们需要根据四个初始条件（两点的位置和两点切线的斜率）分别绘制构成通用曲线的其他四个。我应该为此选择什么类型的曲线？从分析意义上来说，这应该是一条“四参数”曲线，也就是说，粗略地说，它的方程应该有4个系数。要获得特定的弧线，需要确定这四个系数的对应值并表示变元的变化区间。对于我们的问题，最简单的解决方案可能是三次抛物线的弧，或更准确地说，是三次多项式图的一部分：

y = A + B · x + C · x² + D · x³.

知道起点和终点的坐标以及这些点的切线方向，很容易获得四个方程组来确定系数 A、B、C、D。

这种构造波浪曲线的简单方法是通用的。具有垂直切线的点对于它来说是“不可访问的”。即使分成一系列圆弧，也很难绘制闭合或自相交的线。但是，当然，数学家程序员有更多狡猾和先进的方法来构造各种曲线。

我们的封面上是三次多项式圆弧的机器绘图（图 旋转 90°）。 13 个顶部点中的每一个都通过弧线连接到 13 个底部点。在 26 个初始点中的每一个处，指定一个相切连接。弧线相交，意外地形成了带有一排排“结”的花边图案。想想为什么会发生这种事。包含“结”的水平线是如何定位的？
