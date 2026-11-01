---
id: 1976-9-reznikov-formula-kardano-i-geometriya-fc02c5fd
issue: kvant_1976_9
year: 1976
number: "9"
title: 卡尔达诺公式和几何
authors:
  - Резников А. Г.
rubric: osnovnye-stati
page_first: 19
page_last: 19
page_labels: "17"
tag: HDYH
lang: zh
source: kvant_digital
extraction: publisher
content_sha256: fa56c5a8e4ce093c6ee406e2de97f6fe4754b1dd5c1043eec627cec928ecb8a8
prompt_sha256: draft-1
translated_from: content/ru/1976/09/articles/04_reznikov-formula-kardano-i-geometriya-fc02c5fd.md
source_content_sha256: 9771af932d31ee2d0f12420d734bdb05ba936e40327e75025e65b0e1ed191ef5
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦figure⟧

## 卡尔达诺公式和几何

您熟悉如何使用二次方程 $x^2+px+q=0$ 的系数来确定它有多少个实根。如果$p^2-4q\gt0$，则有两个根，如果$p^2-4q=0$，则有一个根，最后，如果$p^2-4q\lt0$，则没有根。

本期针对三次方程$x^3+px+q=0$推导了类似的条件。利用这个条件，你可以得到一个巧妙的不等式来连接任意三角形的元素。这是如何完成的。

令$ABC$为边长为$a$、$b$、$c$的三角形； $p$是半周长，$S$是面积，$R$、$r$、$r_a$、$r_b$、$r_c$分别是外接圆、内接圆和外圆的半径。事实证明，以下关系是正确的：
$$
r_a+r_b+r_c=4R+r,\quad r_ar_b+r_br_c+r_cr_a=p^2,\quad r_ar_br_c=pS.\tag1
$$

等式 (1) 表示数字 $r_a$、$r_b$、$r_c$ 是以下三次方程的根：
$$
x^3-(4R+r)x^2+p^2x-pS=0.\tag2
$$
这是因为 $r_a$、$r_b$、$r_c$ 是多项式的根
$$
(x-r_a)(x-r_b)(x-r_c)=x^3-(r_a+r_b+r_c)x^2+(r_ar_b+r_br_c+r_cr_a)a-r_ar_br_c.
$$

写下方程（2）的三个根有效的条件后，我们经过简单变换并使用公式$S=pr$，得到以下不等式：
$$
[p^2-(2R^2+10Rr-r^2)]^2\le4R(R-2r)^3.\tag3
$$
由 (3) 可知 $$
R\ge2r\tag4
$$
还有什么$$
|p^2-(2R^2+10Rr-r^2)|\le2\sqrt{R(R-2r)^3}.\tag5
$$
当数字 $r_a$、$r_b$、$r_c$ 中的两个相等时，即当三角形为等腰时，即可实现 (3) 和 (5) 中的相等。

### 练习

1. 证明式(1)。为此，请打印 $S$ 的以下表达式：
$$
S=rp=r_a(p-a)=r_b(p-b)=r_c(p-c)=\dfrac{abc}{4R}=\sqrt{p(p-a)(p-b)(p-c)}.
$$
2. 找出在(4)中实现平等的条件。
3. 证明$16Rr-5r^2\le p^2\le4R^2+4Rr+3r^2$。
4. 研究哪些等腰三角形的数字 $p^2-(2R^2+10Rr-r^2)$ 是非负数。
