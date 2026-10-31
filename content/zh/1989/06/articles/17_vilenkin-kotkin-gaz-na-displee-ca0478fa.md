---
id: 1989-6-vilenkin-kotkin-gaz-na-displee-ca0478fa
issue: kvant_1989_6
year: 1989
number: "6"
title: 显示气体
authors:
  - Виленкин А. Н.
  - Коткин Г. Л.
rubric: raznoe
rubric_sub: Разное
page_first: 63
page_last: 63
page_labels: "61"
tag: M9G4
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e2f37456b67a4a86965dbac906bc804c862d6d4ce48a93dd4e9936e0aa9d6bea
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/17_vilenkin-kotkin-gaz-na-displee-ca0478fa.md
source_content_sha256: 7342104db835310ce43043f9ad1434a6b72978cb0bf071476ba5275061a33a61
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 61⟧

显示气体

A.N.维伦金，
物理和数学科学候选人
G·L·科金

这篇笔记是另一篇文章“大矿球的气体”（参见第 2 页），讲述了如何创建一个程序来模拟几个大矿球的运动。描述以读者可以信任特定编程语言的程序的形式呈现。

“Gas”程序（我们就这么称呼它）被合理地分为七个块：变量描述和数据准备、初始启动、屏幕准备、大矿石影响计算、新坐标计算、屏幕上显示信息、模型控制单元。

变量描述和数据准备。为了描述该系统，将使用以下变量： N - 球的数量； a是每个球的半径； T——时间计数器（初始时刻T=∅），T∘——时间步长； A1和A2是屏幕边界。这些变量的值最好在程序中设置，以便可以更改它们（通过编辑程序），但不必为每个实验输入。

每个球的状态由 4 个变量描述：球中心的 x 和 y 坐标以及速度分量 vx 和 vy。所有这些变量都应该被描述为一个数组 R(4, N)，因为它们的计算公式是相同的。对于旧的球位置，您将需要 RS(2, N) 阵列。

初次启动。该块包括请求球的中心坐标和速度分量的初始值。在这里您可以设置 T∘ - 过程的“步骤”。

屏幕准备。高分辨率图形模式下的显示是由“点”组成的 xy 坐标平面的一部分，其整数坐标包含在一定限制内（例如，1≤x≤256、1≤y≤192）。屏幕边界由变量 A1 和 A2 指定，但必须注意避免球不仅落在这些边界之外，而且也不要落入桌子边界的图像中。所以在这个块中需要将显示切换到高分辨率模式，例如绘制桌子的边界并计算球中心位置的边界（例如G1=1+a+1，G2=A1-a-1）。

计算影响较大。在该块中，需要计算第一张桌子的力矩TC，以开关值K的形式描述桌子的类型，以值N1、N2的形式描述桌子球的数量，使得该块的结果如下：第一张桌子是桌子N1，其中K=1-有水平墙，K=2-有垂直墙，K=3-有球N2。

实际中，首先要设置一个大的TC，N1=∅，N2=∅，K=∅。然后循环（按球数）
