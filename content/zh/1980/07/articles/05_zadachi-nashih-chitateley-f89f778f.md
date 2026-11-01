---
id: 1980-7-zadachi-nashih-chitateley-f89f778f
issue: kvant_1980_7
year: 1980
number: "7"
title: 读者的任务
rubric: smes
page_first: 11
page_last: 11
page_labels: "9"
tag: WYCY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: be356c8f223a26d4f48a02ecd00844a5ca5102eb88689294b284eb83e832599e
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/05_zadachi-nashih-chitateley-f89f778f.md
source_content_sha256: 800915d3eb0f1eff4a6d5e1209f3ac381ca677eb01c6d5bc33f20c249e8080ba
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

图 8.

但是，知道了 duhran 角的值（问题 19），您可以尝试粘合所需的正多面体：将一个正则 $n$ 边形以所需的角度粘合到另一个，将第三个正边形粘合到它们上，等等。但是，粘合多面体将“闭合”并且最终不会得到类似于 图 8 中所示的结果的信心在哪里？

存在性可以通过在坐标中实际构造正多面体来证明。让我们将坐标原点放置在围绕未来多面体描述的球体的中心。为了简单起见，我们假设顶点$A$位于横坐标的正半轴上，即坐标为$(R; 0; 0)$，相邻顶点$B_1, \dots, B_k$的横坐标为$x = R \cos \alpha$，其中$\alpha$是从外接球体中心看到边缘的角度。由于多边形$B_1 \dots B_k$是正多边形，并且位于垂直于$(OA)$的平面上，因此我们可以假设点$B_l$的坐标为$(R \cos \alpha; r \cos \frac{2\pi l}{k}; r \sin \frac{2\pi l}{k})$； $l = 1, \dots, k$，其中 $r$ 是多边形 $B_1 \dots B_k$ 的外接圆的半径。例如，在这种情况下，搜索会给出顶点 $A, B_1, \dots, B_5$。其余顶点相对于原点 (图 9) 对称。最简单的坐标表达式在$R = \sqrt{5}$（然后是$R \cos \alpha = 1, r = 2$）处获得：$A = (\sqrt{5}; 0; 0)$； $B_5 = (1; 2; 0)$； $B_1 = \left(1; \frac{\sqrt{5} - 1}{2}; \sqrt{\frac{5 + \sqrt{5}}{2}}\right)$； $B_2 = \left(1; -\frac{1 + \sqrt{5}}{2}; \sqrt{\frac{5 + \sqrt{5}}{2}}\right)$。

 其余点的坐标通过改变符号得到。要检查真实的 icoastra 是否是正确的 icoastra，只需确保所有边都是建设性的就足够了；使用坐标中点之间的距离公式可以很容易地做到这一点。

读者的任务

1. 找到所有满足以下条件的凸四边形：穿过四边形顶点并将其划分的四条线 a) 面积
6) 周长对半，相交于一点。
V. 杜布罗夫斯基、N. Zhuk

2. a) 将正方形内接于正五边形。
• b) 证明正确的

正五边形不能转化为正六边形。
c) 证明对于$n > 5$，正则$n$-边形不能转换为正则$(n + 1)$-边形。

3. 让我们把
$\sin_1(x) = \sin x,$
$\sin_2(x) = \sin(\sin_1(x)),$
$\sin_3(x) = \sin(\sin_2(x)),$
$\cos_1(x) = \cos x,$
$\cos_2(x) = \cos(\cos_1(x)),$
$\cos_3(x) = \cos(\cos_2(x)),$
a) 绘制函数图
$y = \sin_2(x), y = \sin_3(x),$

$y = \cos_2(x), y = \cos_3(x).$
6) 对于什么$n$，方程$\sin_n(x) = \cos_n(x)$在$[0; \pi/2]$上有解？

I·朱克

4. 证明不等式$9r \leq h_a + h_b + h_c \leq \frac{2}{3} \frac{m_a^2 + m_b^2 + m_c^2}{R}$，
其中$h_a, h_b, h_c$是三角形高的长度，$m_a, m_b, m_c$是三角形中线的长度，$r$是插入三角形的圆的半径，$R$是围绕它的外接圆的半径。

M·伊布拉西莫夫
