---
id: 1975-7-n-algebraicheskie-zadachi-037c3710
issue: kvant_1975_7
year: 1975
number: "7"
title: 代数问题
authors:
  - Н. В.
rubric: smes
page_first: 22
page_last: 22
page_labels: "20"
tag: YQDH
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8c8fd39d68097200e991912d7f2c65ca57624a4567fea58db60173793e29eee8
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/04_n-algebraicheskie-zadachi-037c3710.md
source_content_sha256: f07930fa59e28cc25979efc3a65b0ce1a8c0acd2f5ce2d4c2564f8dd1218b5bc
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

练习 14. 以类似的方式证明不等式
$$M(A \# B) \leq M(A) + M(B),$$
$$K(A \# B) \leq K(A) + K(B).$$

不等式$P(A \# B) \geq P(A) + P(B)$更难证明（对于不变量$M$和$K$，类似的不等式并不总是成立）。

考虑一个带有 2P ($A \# B$) 个手柄和其上“切割”节点 $A \# B$ 的球体。

例如，根据合成的定义，我们总是可以将节点$A$和$B$“拉开”到彼此相当大的距离，以便通过连接它们的两个平行线段将它们组合成一个合成（图18，a上的$KL$和$MN$）；同时，我们必须“融化”带有手柄的原始球体。

现在让我们画一个平面来分隔节点 $A$ 和 $B$。该平面首先沿着一根“管”切割带手柄的球体，两个线段沿着该“管”连接节点（证明这些线段实际上穿过一根管，而不是穿过两个不同的管！）；让我们密封由“补丁”形成的两个孔，并在其上绘制圆弧，封闭每个节点（图 18 上的圆弧 $PQ$ 和 $RS$，b）。其次，飞机可能会“意外地”在球体的那些带有不包含结线的手柄的部分上切出“孔”；让我们用“补丁”覆盖这些“洞”（这次没有绘制弧线）。

显然，得到的节点$A$和$B$都位于自己的有句柄的球体上并对其进行切割，并且这些球体的句柄数量之和不大于原始球体的句柄数量，即$P(A \# B) = P(A) + P(B)$，这就是所要求的。

练习15.尝试用同样的方法证明不等式$K(A \# B) \geq K(A) + K(B)$。

现在我们已经完成了艰难的旅程。如果您想继续，克罗威尔和福克斯的有趣（如果困难）的书将作为您的指南。

代数问题

1. 证明$x^{13} - 1 = (x - 1)(x^6 - ax^5 + 2x^4 + bx^3 + 2x^2 - ax + 1) \times (x^6 - bx^5 + 2x^4 + ax^3 + 2x^2 - bx + 1)$，其中$a$和$b$是二次方程$z^2 + z - 3 = 0$的根。找到 $x^{17} - 1$ 的类似展开式，选择二次方程 $z^2 + z - 4 = 0$ 的根作为 $a$ 和 $b$。

2. 令 $\alpha, \beta, \gamma$ 为三次方程 $x^3 + bx + c = 0$ 的根。写出一个方程，根为 $\alpha(\beta - \gamma)^2, \beta(\gamma - \alpha)^2, \gamma(\alpha - \beta)^2$。

3. 证明对于任何自然值$r$数字
$$N_1 = r^{r+1} - 2r^r + 1,$$
$$N_2 = 2r^{r-2} - r^{r-3} - 1$$
$(r > 2),$$
$$N_3 = r^{r+1} - 2r + 1,$$
$$N_4 = r^{r-2} + r - 2$$
делятся на целое на $(r - 1)^2$, а числа $N_1$ и $N_2$ делятся на целое на $(r - 1)^3$, если $r$ четно.

4. Доказать, что если $(x + y)(x + z) = bcyz，(y + z)(y + x) = acxz，(z + x)(z + y) = abxy，然后$a + b + c = abc + 2$或$a + b + c = abc - 2$。

5. 证明如果$x + y + z = 0, \frac{x^2}{a} + \frac{y^2}{b} + \frac{z^2}{c} = 0, ayz + bzx + cxy = 0$则$(b + c - a)(a + c - b)(a + b - c) = abc$。

6. 设自然数$D$为这样，当将分数$\frac{1}{D}$转换为小数时，得到周期分数的个数，周期中有$p$位。让我们用$N(n, m)$表示一个自然数，其十进制表示法由00...01形式的$m$组组成，并且在每个组$n - 1$中都有一个零（在最左边的组中，零被省略）。证明如果$n$能被$p$整除，则$N(n, m)$能被$D$整除当且仅当$m$能被$D$整除。

H. B.
