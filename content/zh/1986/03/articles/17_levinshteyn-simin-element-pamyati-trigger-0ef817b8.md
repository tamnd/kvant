---
id: 1986-3-levinshteyn-simin-element-pamyati-trigger-0ef817b8
issue: kvant_1986_3
year: 1986
number: "3"
title: 记忆元件-触发器
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 50
page_labels: "48"
tag: FU5Z
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 983c3666d79ee11765fa3ecc12ea3c69b6a61f593552da6cf270120147430c2e
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/17_levinshteyn-simin-element-pamyati-trigger-0ef817b8.md
source_content_sha256: a8a53fed2ca4fd1e761d84086db18d2c46dc303d4757f2fa24d7365af669ee9f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

七．记忆元件-触发器

我们在上一节逻辑电路（参见«Kvant»，1986，第1、2期）开始讨论了控制普通住宅中电梯运动的设备必须解决的逻辑问题。现在可能是一个很好的时机来提一下，即使是这样一个简单的设备，如果不包含存储元件也无法运行。电梯控制装置的“存储器”中记录了几个数据：电梯释放后，门应保持打开状态多少秒；如果门自动关闭遇到问题怎么办？按下紧急“停止”按钮时的操作顺序是什么？等。除了这些可用数据外，运行数据还被输入并记录到电梯“存储器”中，并在运行过程中发生变化 - 在哪些楼层按下按钮；电梯当前正在移动的位置：向上、向下、静止。

解决复杂问题的计算机内存中记录了数十万甚至数百万数据。正如已经提到的，这些数据以计算机可以感知和处理的形式编写，即使用“零”和“一”（在双数系统中）。*

显然，我们所考虑的计算机技术元素——晶体管，以及基于它们的逻辑电路——本身都不能是存储元素。 All of them, after the cessation of the input pulse, immediately return to their original state.

For a memory element, you need a device that, under the influence of an input pulse, could switch from state “0” to state “1” and back;同时，在输入脉冲终止后，它将填充其状态并可以无限期地保持在该状态（直到下一个切换输入脉冲到达）。

了解触发器工作原理的最简单方法是使用 NOT（反相器）逻辑电路的已知属性。

考虑串联连接的两个逆变器 (图 1)。例如，在第一个反相器的输入处，$U_{bx} = x$可以等于$U^0$（逻辑零）或$U^1$（逻辑一）。例如，第一个逆变器的输出始终为$x$（而不是$x$），即$U_{bx} = U^0$为$U^1$，$U_{bx} = U^1$为$U^0$。先输出电压

*) 幽默的诗“一位非凡的女孩”（第 50 页）将帮助您弄清楚双数和十进制数字系统是如何连接的。
