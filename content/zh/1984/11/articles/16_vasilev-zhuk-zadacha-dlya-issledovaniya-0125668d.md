---
id: 1984-11-vasilev-zhuk-zadacha-dlya-issledovaniya-0125668d
issue: kvant_1984_11
year: 1984
number: "11"
title: 研究问题
authors:
  - Васильев Н. Б.
  - Жук И. К.
rubric: smes
page_first: 45
page_last: 45
page_labels: "43"
tag: XAU9
lang: zh
source: kvant_digital
extraction: vision
content_sha256: e68aba7beb96b74f9fcc7c03e4e8bdf72258305334a14324ba18d777590ddfa9
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/16_vasilev-zhuk-zadacha-dlya-issledovaniya-0125668d.md
source_content_sha256: 4995b347d2fe04ed00c271d86579e9aeb1e93d4c4ce40d4e43c95ada8a654940
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

$$y_{AM}(x_A) = 0 \Rightarrow x_A = -\frac{1}{2g \text{tg} \varphi} (\text{tg} \alpha - \text{tg} \varphi)^2 v_0^2 \cos^2 \alpha.$$

因此，如果物体以 $\alpha > \varphi$ 角度抛出，则影子会沿路径传播（参见 (2)）

$$S_2 = \frac{1}{g} v_0^2 \sin 2\alpha + \frac{1}{g \text{tg} \varphi} (\text{tg} \alpha - \text{tg} \varphi)^2 v_0^2 \cos^2 \alpha.$$

让我们看看这个表达式在 $\alpha$ 的值是多少时最大。为此，我们求导数 $S'(\alpha)$ 并将其等于零：

$$S'(\alpha) = \frac{2}{g} v_0^2 \cos 2\alpha + \frac{1}{g \text{tg} \varphi} v_0^2 (\sin 2\alpha + 2 \text{tg} \varphi \cos 2\alpha - \text{tg}^2 \varphi \sin 2\alpha) = 0,$$

或者

$$(1 - \text{tg}^2 \varphi) \sin 2\alpha = 0 \Rightarrow \sin 2\alpha = 0 \Rightarrow \alpha = 90^\circ$$

（情况$\alpha = 0$不适合我们，因为$\alpha > \varphi$）。

因此，$S_2$在$\alpha = 90^\circ$处最大，即当身体垂直向上抛出时，并且（参见图4）

$$S_{2\max} = 2h_{\max} \text{ctg} \varphi = \frac{1}{g} v_0^2 \text{ctg} \varphi.$$

现在我们找出在什么条件下$S_{2\max} > S_{1\max}$和在什么条件下$S_{2\max} < S_{1\max}$。为此，我们找到关系 $S_{1\max}: S_{2\max}$（参见 (1)）：

$$\frac{S_{1\max}}{S_{2\max}} = \frac{v_0^2 g \sin 2\varphi}{v_0^2 g \text{ctg} \varphi} = 2 \sin^2 \varphi.$$

在 $\varphi = 45^\circ$ 处，该表达式等于 1 ($S_{1\max} = S_{2\max}$) - 阴影在 $\alpha = 45^\circ$ 和 $\alpha = 90^\circ$ 处沿相同路径行进。如果$\varphi < 45^\circ$，则$2 \sin^2 \varphi < 1$ ($S_{1\max} < S_{2\max}$) - 阴影在$\alpha = 90^\circ$处移动最大路径。在 $\varphi > 45^\circ$ 处，正如我们已经说过的，$S_{1\max} = \frac{1}{g} v_0^2$ 和 $S_{1\max}: S_{2\max} = \text{tg} \varphi > 1$ - 阴影在 $\alpha = 45^\circ$ 处移动最大路径。

让我们写下最终答案：

如果$\varphi < 45^\circ$ - 身体必须垂直投掷；
如果$\varphi = 45^\circ$ - 身体必须垂直投掷或与地平线成$45^\circ$角；
如果 $\varphi > 45^\circ$ - 身体必须以与地平线 $45^\circ$ 的角度投掷。

V·A·纳赫辛

问题
用于研究
“相邻数的乘积”
在±1的表中

结合今年全联盟奥林匹克竞赛的两个问题（10年级第5题和9年级第8题；见第47-48页），自然会出现以下更普遍的问题。

对于每个大小为$m \times n$的表$T$，其单元格包含数字1和-1，定义一个新表$P(T)$；在其每个单元格中写入的数字等于表$T$中相邻（与其共享公共边）单元格中的数字的乘积。对于每个 $m$ 和 $n$：

1) 不同的表$T$一定对应不同的表$P(T)$吗？

2) 对于表 $T_1 = P(T)$、$T_2 = P(T_1)$、... 序列中的任意表 $T$ 是否存在一张只有 1 的表？

尝试回答这些问题（显然

我觉得更简单）如下：

“圆柱形”表$m \times n$，其中长度为$m$的两个相对边被认为是粘合的，而对于“环面”，其中两对相对边被认为是粘合的（每对有四个相邻的边）。

请注意，问题 2) 针对的是圆柱体。高度$m = 1$，即圆周上的$n$个单元，理解“量子问题”；在 $n = 2^k$ ($k = 2,3,...$) 处获得肯定答案。

N.V.瓦西里耶夫、I.K.朱克
