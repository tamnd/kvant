---
id: 1976-5-belyiy-klyuch-k-resheniyu-podobnyie-treugolniki-4febba7c
issue: kvant_1976_5
year: 1976
number: "5"
title: 解题的“关键”是相似三角形
authors:
  - Белый С. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 59
page_last: 62
page_labels: 57, 60
tag: IVDE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 340eaf0f248a043ee2340e51d044d72374ec1744da6488a3b351950f02bfb64b
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/12_belyiy-klyuch-k-resheniyu-podobnyie-treugolniki-4febba7c.md
source_content_sha256: ae70afb25494bd2c06935835b034c8e732a881c5a305b008eb9b82eef55c51f6
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

任何问题（不仅是数学问题！）对我们来说似乎都或多或少困难，直到我们设法找到解决方案的“关键”。在解决几何问题时，这样的“关键”往往是相似三角形。在一个问题中，这样的三角形是在条件中给出的，而在其他问题中，它们是“伪装的”，因此不会立即被注意到；也存在根本不存在这样的三角形的问题；要获得它们，您需要进行一些额外的构造。

“开始‘看到’这样的三角形非常有用——它们通常会让解决问题变得更容易。

在阅读下面讨论的问题的解决方案之前，请尝试自己解决每个问题。

任务 1. 在三角形 ABC 内，取任意一点 O，并通过该点画出与三角形各边平行的三条直线。这些线将三角形 ABC 分成六部分，形成三角形 A'B'C'。

这些三角形内切圆的半径等于$r_1, r_2, r_3$；三角形ABC 内切圆的半径等于r。证明$r = r_1 + r_2 + r_3$。

很明显，所构造的三角形与三角形 ABC 相似（参见 图 1），因此

$$\frac{r_1}{r} = \frac{FO}{AC}; \quad \frac{r_2}{r} = \frac{ED}{AC}; \quad \frac{r_3}{r} = \frac{OH}{AC}.$$

将这些等式逐项相加，我们得到

$$\frac{r_1 + r_2 + r_3}{r} = \frac{FO + ED + OH}{AC} = \frac{AE + ED + DC}{AC} = 1,$$

从哪里$r_1 + r_2 + r_3 = r$。

问题2：证明锐角三角形的高是由连接高的底边的线段形成的三角形的二等分线。

根据三角形$AB'B$和$AC'C$的相似性（参见图2），可以得出$\frac{AC'}{AB'} = \frac{AC}{AB}$，因此三角形$AC'B'$和$ABC$相似，因为它们有一个公共角A，并且包含该角的边成比例。同理，我们可以证明三角形$CA'B'$和$ABC$、$BA'C'$和$ABC$相似。因此，$\triangle AB'C' = \triangle CB'A' = \triangle ABC$，因此$\triangle C'B'B' = \triangle A'B'B'$。同理，证明$A'A$和$C'C$是三角形$A'B'C'$的二等分线。

⟦folio 60⟧

图 8.

问题 8（MIPT，1970）。在ABCD中（AB和CD是碱基）AB = a，CD = b (a < b)。经过顶点 A、B、C 的圆与边 AD 相切。求对角AC。

请注意$\Rightarrow ACD = \Rightarrow BAC$（横向放置）、$\Rightarrow ABC = \Rightarrow CAD$（两者都会改变正弧 AEC，请参见图 8）。因此，三角形ABC和CAD相似。因此$\frac{AB}{AC} = \frac{AC}{DC}$，因此$AC = \sqrt{ab}$。

问题 9（MAI，1972）。在ABCD中，画对角线AC和BD，相交于点F。从顶点C画直线CK，平行于侧面AD，并与BD相交于点L，使得DF = BL。求 AB:CD 比率。

让我们用 $x$ 表示所需的关系。然后根据三角形AFB和CFD的相似性（参见图9），我们得到$\frac{AB}{CD} = \frac{AF}{CF} = \frac{FB}{DF} = \frac{FL + LB}{DF} = \frac{FL + DF}{DF}$，由此得到$\frac{FL}{DF} = x - 1$。另一方面，从三角形ADF和CLF的相似性来看

$$\frac{FL}{DF} = \frac{FC}{AF} = \frac{1}{x}.$$

因此，为了确定 $x$，我们得到二次方程 $x^2 - x - 1 = 0$，由此得出 $x = \frac{1 + \sqrt{5}}{2}$（自 $x > 0$）。

问题 10（MIPT，1973）。在三角形ABC中，通过高BD的底D，平行于边AB画一条直线，直至与边BC相交于点K。如果三角形BDK的面积是三角形ABC面积的$\frac{3}{16}$，则求比值BK:KC。

让我们用 $x$ 表示所需的关系。让我们做深度学习 || BC（参见图 10）并注意$x = \frac{BK}{KC} = \frac{AD}{DC}$。接下来，我们解决使用相似三角形ABC、ALD和DKC的问题：一边是$S_{\triangle ALD} + S_{\triangle DKC} = S_{\triangle ABC} - 2S_{\triangle BDK} = \frac{5}{8} S_{\triangle ABC}$，另一边是$S_{\triangle ALD} + S_{\triangle DKC} = S_{\triangle ABC} \cdot \frac{x^2 + 1}{(x + 1)^2}$，从这里我们得到方程$\frac{x^2 + 1}{(x + 1)^2} = \frac{5}{8}$，或$3x^2 - 10x + 3 = 0$，$x_1 = 3$，$x_2 = \frac{1}{3}$。
