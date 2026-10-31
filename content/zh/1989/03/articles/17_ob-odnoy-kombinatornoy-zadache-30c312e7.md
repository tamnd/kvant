---
id: 1989-3-ob-odnoy-kombinatornoy-zadache-30c312e7
issue: kvant_1989_3
year: 1989
number: "3"
title: 【关于一道组合问题】
rubric: nam-pishut
page_first: 60
page_last: 60
page_labels: "58"
tag: 0BFY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e17c20eeef38faecc11ae6749854fb7f8e757adc97c4e98674f6ef56748cf1b8
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/17_ob-odnoy-kombinatornoy-zadache-30c312e7.md
source_content_sha256: 0a793875bf713c05843b63525dab796d2e0d51cd293ae80da3e5631b925a85fc
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 58⟧

例如，点$Q$也位于该圆上。三角形$T_1SQ$和$CQA$相似。因此$\frac{ST_1}{AC} = \frac{T_1Q}{QA}$，但是$AC = QA$（参见陈述8）。因此$ST_1 = T_1Q = r$。

练习 2. 证明以下陈述：

17. 点$K$（参见图3）是三角形$CPQ$的正交。
18. 线 $PS$、$RQ$ 和 $CH$ 相交于点 $K$。
19. $RT = KS = SQ$; $RP = RK = TS$.
20. $RS = CT$.
21. 点$A, R, S, B$位于同一个圆上；点$A, P, T, C$位于同一个圆上。点$B, Q, T, C$也位于同一个圆上。

还有几场比赛

22. $AT_1 \cdot BT_1 = S_{ABC}$.

奈姆普特

许多读者都熟悉$n$元素与$k$的组合数的经典公式：

$$C_k^n = \frac{n!}{k!(n-k)!}.$$

特别是，有$C_k^n$种方法可以从集合$(1, 2, 3, ..., n)$中选择$k$不同的数字。 Novokuznets 的 L. I. Plyukfelder 提出了这样的问题：有多少种方法可以从集合 pa (1, 2, 3, ..., $n$) 中选择 $k$ 数字，使得任意两个所选数字的绝对差不小于 $p$？

我们用 $C_k^n(p)$ 来表示这个数字。 L. I. Plyukfelder 发现的公式具有以下形式：

$$C_k^n(p) = \frac{(n+k-pk+p-1)!}{k!(n-pk+p-1)!}$$

（如果对于某些$n, k, p$，分母中出现负数，则所需的计算不存在）。

对于$p=1$，公式(2)正如人们所期望的那样，变成了(1)，而对于$p=0$，则变成了公式：

$$C_k^n(0) = \frac{(n+k-1)!}{k!(n-1)!}.$$

数字$C_k^n(0)$自然被视为选择$k$的方式的数量，不一定与数据$n$不同的元素；对于这个数字，公式（3）给出了正确的结果。

式(2)的证明可以通过归纳法来验证；我们建议您自己执行此操作。
