---
id: 1986-7-tabov-ob-odnom-sposobe-zadaniya-okruzhnosti-2b086133
issue: kvant_1986_7
year: 1986
number: "7"
title: 关于定义圆的一种方法
authors:
  - Табов Й. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 27
page_last: 28
page_labels: 25-26
tag: A831
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5d08d4891fccbcf9524f7fe4c9d89bc64d1686fd6b512a0839ddd0ceae3da026
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/08_tabov-ob-odnom-sposobe-zadaniya-okruzhnosti-2b086133.md
source_content_sha256: 3c1a0234563263fbc6ca5388bbd0eaffddee3189fc7af1a803f89c82e6d28928
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

关于定义圆的一种方法

I.B.塔博夫 (NRV)

如您所知，圆被定义为距固定点 O 等距离的点的轨迹。但是还有许多其他方法来定义圆。我们将在这里看看其中之一。

设 P 为一个点，l 为从该点发出的射线。在同样从点 P 发出并与射线 l 形成锐角或直角 φ 的射线 m 上，我们标记位于距 P 距离 a cos φ 处的点 M，其中 a 是固定正数 (图 1)。

定理。当角度 φ 在 -π/2 到 π/2 范围内变化时，M 点形成一个直径为 a 的圆，穿过 P 点，关于射线 l 对称。

（使用加号我们以逆时针方向绘制角度，使用减号我们以顺时针方向绘制角度。）

证明。设 R 为圆上与点 P 直径相对的点，设 M 为任意点

我们的圈子（图2）。则∠PMR=π/2，即

PM=PR · cos (∠MPR)=a cos φ.

（严格来说，M=R（φ=0）和M=P（φ=±π/2）的情况需要单独考虑，我们将其留给读者。）因此，圆上的所有点都属于我们的几何轨迹，并且由于圆与每条射线m相交，因此所考虑的几何轨迹不包含任何其他点。定理已被证明。

注意，如果在几何位置的描述中，将表达式 a cos φ 替换为表达式 a cos (φ+δ)（当然，将角 φ 为锐角或直角的条件替换为 cos (φ+δ)≥0 的条件），我们就得到一个直径为 a 的、穿过点 P 且相对于与 l 形成角度 δ (图 3) 的射线对称的圆。

最后，如果我们写出表达式 a sin φ （并且条件 sin φ≥0）来代替表达式 a cos φ （并且条件 sin φ≥0），那么我们就得到了一个直径为 a 的圆，该圆在点 P (图 4) 处与射线 l 相切。

让我们通过解决一个非标准问题来证明我们观察的有用性。

问题 1. 给定一个等边直角三角形 A₀A₁A2，其顶点 A₀ 为直角。对于三角形 A₀A₁A2 外接圆上的任意点 C，我们在射线 A₀C 上标记点 M，使得

A₀M=A₁C+A₂C-A₀C.

求M点的轨迹。

⟦folio 26⟧

解决方案。我们将圆的直径设为 1，用 φ 表示角度 CA₀O，其中 O 是圆的中心。那么，显然 (图 5)，
A₀C=cos φ,
A₁C=|sin (φ+π/4)|,
A₂C=|sin (φ-π/4)|.

让我们考虑三种情况。

1. -π/4≤φ≤π/4。然后
A₀M=sin (φ+π/4)−sin (φ−π/4)−cos φ=√2cos φ−cos φ=(\sqrt{2}-1)cos φ.

因此，轨迹的相应部分将是直径为 √2−1 的圆弧，穿过点 A₀ 并相对于射线 A₀O (图 5) 对称。由于角度 φ 穿过区间 [−π/4; π/4] 长度为 π/2（而不是上面的 π），我们发现该弧等于直径为 √2−1 的半圆（在 图 5 处以红色突出显示）。

2. π/4<φ<π/2。然后
A₀M=sin (φ+π/4)+sin (φ−π/4)−cos φ=√2sin φ−cos φ=√3(√2/3sin φ−√1/3cos φ)=√3cos (φ+δ),
其中 δ=arccos(−√1/3)。因此，对应于该 φ 值的轨迹部分将是一个直径为 √3 的圆弧，穿过点 A₀ 并相对于射线 A₀O 对称。

问题1的最终答案如图7所示。

任务 2. 给定一个多边形 A₀A₁A2......Aₙ，内接于圆 c。对于圆 c 的任意点 C，我们在射线 A₀C 上标记点 M，使得
A₀M=|x₀·A₀C+x₁·A₁C+...+xₙ·AₙC|,
其中 x₀、x₁、...、xₙ 是一些数字。
求点 M 描述为 C 穿过圆 c 的集合。

任务3（这是“问题书«Kvant»中的任务M853，参见«Kvant»，1984年，第3号）。正方形ABCD围绕其固定中心愈合。找到描述线段PQ中点的集合，其中P是从D点到固定线l绘制的垂线的底边，Q是边AB的中点。
