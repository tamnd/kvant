---
id: 1980-9-ob-ornamentah-ae3cd5df
issue: kvant_1980_9
year: 1980
number: "9"
title: 【关于饰品】
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 59
page_labels: "57"
tag: 37LY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 34bfa4595603464b758fc121654984bebc67235858e9b204f67982c572166c27
prompt_sha256: draft-1
translated_from: content/ru/1980/09/articles/20_ob-ornamentah-ae3cd5df.md
source_content_sha256: 04ed7cd213e78b20fb40d3ecb379f1049d3cb9ee5ee3b424afcc038f7022e6c9
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

底边为$\Delta x$，高分别为$y(a)$、$y(a + \Delta x)$、$y(a + 2\Delta x)$。然后使用程序0->X计算图9上近似阴影的面积； 0->积分； 0.01->德尔塔；再见$X = < 2$::(10)
积分+三角*
((X-1)!2+1)->积分； X+德尔塔->X
全部

当然，十年级的学生不会感到惊讶，因为执行程序（10）所获得的面积被称为“INTEGRAL”。学校数学课程（《代数与分析入门10》第101段）中说，非负连续函数的区间是相应线性边界曲线的面积。因此，程序(10)是最简单的数值插值程序的典型示例。

该程序中使用的数值插入方法称为直线法：在循环体中，计算直线元素的面积，并从中添加计算出的计算面积的近似值。正是 DELTA 步骤以及所选梯形方法的结果：所得区域由基本梯形 (图 10) 组成。

任务 9.5。采样与(10)相同积分的计算，梯形法。

此类程序允许近似计算任意函数的面积：以两个（或多个）函数的形式表示复杂函数的面积就足够了，其中每个函数的面积都由某个插值直接计算。因此，在 图 11 处，两个辛康达很容易可见 - “上部”$y = 3\sin \frac{x}{3} + \pi$ 的极点和“底部”$y = \sin x + \pi$ 的一个半周期。

*任务 9.6。编写一个程序，计算图11上阴影的函数面积（不要编写计算正弦的程序，假设它已经存在：只需调用SIN(X)即可访问它）。

于。珀文

我们的封面

一个器官通常被称为形状奇异的funkru，其自组合群（见«Kvant»，1980，No.7，p.4）包含至少一个不同于相同的位移。

虽然“形态的奇异”无法准确描述，但这个器官的“定义”却有着相当明确的含义。封面的第二页描绘了几个东方管风琴，以及其中包含的自我组合组（当然，假设该图案无限地向左和右延伸）。
