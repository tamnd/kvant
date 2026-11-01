---
id: 1990-2-formulyi-tipa-ramanudzhana-obobschenie-odnogo-tozhdestva-f4d6bc8d
issue: kvant_1990_2
year: 1990
number: "2"
title: '[拉马努金型公式。一个身份的概括]'
rubric: nam-pishut
rubric_sub: Нам пишут
page_first: 45
page_last: 45
page_labels: "43"
lang: zh
source: kvant_digital
extraction: vision
content_sha256: dadec0c7067a2f7cb1e9ed68d0d098bae1a768ca9f946e20f1c7770d7b0d4d91
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/12_formulyi-tipa-ramanudzhana-obobschenie-odnogo-tozhdestva-f4d6bc8d.md
source_content_sha256: 899bd57b21161995980ee351d4c4bbad80e7eb8a2ea49037b4b21f659332862d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

---
running_head:
folio:
---

因此，在样本中，流动沿着条带，电场方向与电流成一定角度，并且由等于 $E_1 = U_0/L$ 的纵向分量和等于 $E_2 = U/d$ 的横向分量组成。 $X$ 和 $Y$ 轴上的方向性投影分别相等

$$E_x = (E_1 - E_2) \cos 45^\circ = \frac{E_1 - E_2}{\sqrt{2}},$$

$$E_y = (E_1 + E_2) \cos 45^\circ = \frac{E_1 + E_2}{\sqrt{2}}.$$

然后对于当前密度预测我们可以写

$$j_x = \sigma_x E_x = \sigma_x \frac{E_1 - E_2}{\sqrt{2}},$$

$$j_y = \sigma_y E_y = \sigma_y \frac{E_1 + E_2}{\sqrt{2}}.$$

由于电流沿带状流动，$j_x = j_y$，即

$$\sigma_x \frac{E_1 - E_2}{\sqrt{2}} = \sigma_y \frac{E_1 + E_2}{\sqrt{2}}.$$

这意味着所需的电导率等于

$$\frac{\sigma_x}{\sigma_y} = \frac{E_1 + E_2}{E_1 - E_2} = \frac{U_0/L + U/d}{U_0/L - U/d}.$$

A·乌兹丁

《拉马努金的三个公式》一文（«Kvant»第6期，1988）包含了许多有趣的三角函数公式。这些公式的作者，V.S. Shevelev 又给我们发了两个这种类型的公式：

$$\sqrt{\frac{\cos 2\pi}{4\pi}} + \sqrt{\frac{\cos \pi}{2\pi}} + \sqrt{\frac{\cos 2\pi}{8\pi}} +$$

$$+ \sqrt{\frac{\cos \pi}{2\pi}} + \sqrt{\frac{\cos 4\pi}{8\pi}} + \sqrt{\frac{\cos 2\pi}{4\pi}} = -\sqrt{3}7,$$

$$\sqrt{\frac{\cos 2\pi}{4\pi}} + \sqrt{\frac{\cos 4\pi}{8\pi}} + \sqrt{\frac{\cos 2\pi}{8\pi}} +$$

$$+ \sqrt{\frac{\cos 8\pi}{2\pi}} + \sqrt{\frac{\cos 4\pi}{8\pi}} + \sqrt{\frac{\cos 2\pi}{4\pi}} = -\sqrt{3}9.$$

尝试使用“拉马努金的三个公式”一文的方法来证明这些美丽的公式。 1988年«Kvant»第10期，在“选定的学校问题”部分，第2号下，发表了一个问题，其中指出对于$xyz = 1$

$$\frac{1}{1+x+xy} + \frac{1}{1+y+yz} + \frac{1}{1+z+zx} = 1.$$

来自罗斯托夫地区的 A. M. Kolesnikov 发现了以下概括。令 $x_1, x_2, \dots, x_n$ 为满足 $x_1 x_2 \dots x_n = 1$ 的数字。然后

$$\frac{1}{1+x_1+x_2+x_3+x_4+\dots+x_n} + \frac{1}{1+x_2+x_3+x_4+\dots+x_n} + \dots + \frac{1}{1+x_n+x_1+x_2+\dots+x_n} = 1.$$

证明是通过添加 $n$ 非常强的等式获得的：

$$\frac{x_1 x_2 \dots x_i}{1+x_1+x_2+\dots+x_n-1} = \frac{1}{1+x_{i+1}+x_{i+1}x_{i+2}+\dots+x_{i+1}x_{i+2}}.$$

其中 $i=1, 2, \dots, n$，根据定义$x_{n+j} = x_j$。
