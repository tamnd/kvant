---
id: 1987-11-golovolomka-chertova-bochka-9a03e844
issue: kvant_1987_11
year: 1987
number: "11"
title: '[魔鬼桶谜题]'
rubric: smes
page_first: 68
page_last: 68
tag: Y1JI
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 05c917a2d83e103a4d368fb56c5c1c0bc9f461b7db6f248e50f76e647de49dc7
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/01_golovolomka-chertova-bochka-9a03e844.md
source_content_sha256: 61afffc7b78aa9f9ef15957ce6527a2e4be55f4d1a13f2219b2e73116cc1de2f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

“魔鬼枪管”是由日本一家生产中央机枪公司的经理横井冈尼发明的。右图为其总体视图，左图为示意图。这位金匠在外部填充了著名的“varikon”和“巴别塔”（参见«Kvant»第6号），但这里球的运动方式有所不同。允许： 1）用两个滚筒同时转动两“层”球；沿图中箭头方向将下滚筒转动 1/5 整圈将表示为 n，上滚筒为 c； 2) 一次移动三个垂直长排的球（每个球 5 个） - 如果顶部有 3 个“额外”球，则向下移动；如果循环（7 个和 5 个元素）则向上移动，即同时移动 12 个球。就这么多了。但更简单的排列是由它们组成的。 BAB$^{-1}$ 例如，换向器 K=A$^{-1}$ 仅移动 7 个球：它生成 3 个循环 5 → 4 → 7 → 5 和一对交换 1 ↔ 2, 3 ↔ 6（数字是图中球的数量）。现在是时候熟悉另一种有助于建设性良好操作的有用技术了——重复。如果执行 K 两次，那么显然，交换 1 ↔ 2 和 3 ↔ 6 将消失，只保留 3 个循环 4 → 5 → 7 → 4。相反，通过三次重复，三次循环将消失，但几次交换将保留。类似地，我们可以从操作 A 或 B 中的两个循环之一中提取：检查 A$^5$ 是 7 循环，A$^7$ 是 5 循环，并查看开关 A$^5$B$^5$A$^{-5}$B$^{-5}$ 的作用， A$^7$B$^7$A$^{-7}$B$^{-7}$。

细心的读者可能会注意到，操作 A 和 B 本质上与第一个数字 «Kvant» 的操作相同，用于类似于“魔鬼桶”的扁平金锤（比较它们的图表！）。但“桶”仍然是一个圆形物体，只需转动滚筒就可以在其中形成循环。这个不太聪明的消息在以下两个操作中“起作用”：

$$\begin{align*}
\downarrow H \uparrow B \downarrow H^{-1} \uparrow B^{-1} \\
(1 \leftrightarrow 2, 5 \leftrightarrow 7, 3 \leftrightarrow 6 \leftrightarrow 4 \leftrightarrow 3; \text{cp. } c \text{ К}) \\
\downarrow B^2 \uparrow H^2 \downarrow B^{-2} \uparrow H^{-2}
\end{align*}$$

正如您所看到的，移动次数的节省是相当可观的！
