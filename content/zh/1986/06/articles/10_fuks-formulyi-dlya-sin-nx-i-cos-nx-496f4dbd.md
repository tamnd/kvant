---
id: 1986-6-fuks-formulyi-dlya-sin-nx-i-cos-nx-496f4dbd
issue: kvant_1986_6
year: 1986
number: "6"
title: sin nx 和 cos nx 的公式
authors:
  - Фукс Д. Б.
rubric: shkola-v-kvante
page_first: 27
page_last: 27
page_labels: "25"
tag: A6YA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b94455fc3505cd3e260aa32b55ffeeb13932e8a7084b9cb16300eb61a2b4d306
prompt_sha256: draft-1
translated_from: content/ru/1986/06/articles/10_fuks-formulyi-dlya-sin-nx-i-cos-nx-496f4dbd.md
source_content_sha256: 58395d83c49d768d1bc203714af5b14f08b28ae72127bf189f3faf7c3e88be84
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

Mathematica 9, 10

下面发表的笔记是针对真正的经典和十大经典。对于那些正在准备大学入学考试的人来说，它也很有用。

sin nx 和 cos nx 的公式

建设大学的问题集充满了“多角度”的正弦和余弦，即 sin 7x、cos 9x 等表达式。虽然并不总是如此，但通常将这些表达式写成 sin x 和 cos x 的函数是有用的。原则上，这可以使用求和的正弦和余弦公式完全自动完成，但即使重复使用最简单的公式，也无法避免错误；此外，这可能会浪费时间。下面是编写 sin nx 和 cos nx 公式的简单、易记且可靠的方法。

帕斯卡三角形。读者很可能知道它是什么；尽管如此，让我们回顾一下定义。帕斯卡三角形是一个数表，其第n行包含n+1个自然数。在这种情况下，在顶行有两个单位，对于第 n 行中的每个 n，边缘有单位，而在其他地方有来自第 (n-1) 行的连续对相邻数字的总和 (图 1)。

图 1.

帕斯卡三角形最显着的性质是其第 n 行的数字是多项式 $(x+1)^n$ 的系数：
$(x+1)^1=x+1,$
$(x+1)^2=x^2+2x+1,$
$(x+1)^3=x^3+3x^2+3x+1,$
$(x+1)^4=x^4+4x^3+6x^2+4x+1,$
$(x+1)^5=x^5+5x^4+10x^3+10x^2+5x+1$

他们以前在学校这样做，但现在不这样做了。

公式。写出帕斯卡三角形的第n行。 （顺便说一下，为了找到第 n 行，你不需要计算行数：在第 n 行中，第二位是 n。）将 $\cos^n x$、$\cos^{n-1}x \sin x$、$\cos^{n-2}x \sin^2x$、...、$\sin^n x$ 依次缝到这一行的数字上。在生成的链中，在偶数位置的表达式下划线：第二个、第四个等。在两个单独的行中写出非重读表达式和带下划线的表达式。在生成的两行中，在第二个表达式之前添加一个减号，在第三个表达式之前添加一个减号，在第四个表达式之前添加一个减号，等等。一切都已准备就绪 - 在顶行中编写了 cos nx 的表达式，在底行中编写了 sin nx 的表达式。

措施示例。对于 n=2，帕斯卡三角形的行看起来像 1, 2, 1。我们写：

$$\cos^2x \ 2\cos x \sin x \sin^2x$$

$$\cos 2x=\cos^2x-\sin^2x,$$

$$\sin 2x=2\cos x \sin x.$$

对于 n=3，我们写：

$$\cos^3x \ 3\cos^2x \sin x \ 3\cos x \sin^2x \sin^3x$$

$$\cos 3x=\cos^3x-3\cos x \sin^2x,$$

$$\sin 3x=3\cos^2x \sin x-\sin^3x.$$

读者会在图 2上发现这样得到的几个cos nx 和sin nx 的公式；沿着这个图上的红色虚线，你可以读出帕斯卡三角形的线。

锻炼。知道了帕斯卡三角形的第 n 行，就很容易写出用 tg x 来表示 tg nx 的公式。试试这个。

公式的证明。事实上，这些公式是“莫瓦公式”的结果（«Kvant»，1983，第 2 期，第 19 页，L. S. Pontryagin 的文章“复数”）。但是，为了不提及程序中未包含的内容，
