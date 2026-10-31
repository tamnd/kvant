---
id: 1989-3-kurlyandchik-pryamougolnyiy-treugolnik-4a166efa
issue: kvant_1989_3
year: 1989
number: "3"
title: 直角三角形
authors:
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 58
page_last: 59
page_labels: 56-57
tag: UCKI
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 61ecc622f166cdeac6275f91b2480f63028f2dd3ebadc6968b9312206e6a2aca
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/16_kurlyandchik-pryamougolnyiy-treugolnik-4a166efa.md
source_content_sha256: deb9b3c39689e8bf6e6835800cea0413d64b6c341df3da81a1dbe8edb21a5c10
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

直角三角形
L.D.库尔扬奇克

关于直角三角形有哪些有趣的事情？乍一看，什么也没有——关于他的一切似乎都被人知道了。不过，我们不要着急。阅读本文，您将看到这个简单图形的许多有趣且重要的属性。也许你们中的一些人会发现这里没有提到的其他属性。

几乎显而易见的关系

因此，设ABC为直角三角形，H点为从直角C（图1）顶点下降的高的底边。像往常一样，我们引入符号
AB=c, AC=b, BC=a, AH=b', BH=a',
CH=h,
∠A=α, ∠B=β.

让我们回忆一下您在学校学到的简单陈述和关系。
1. 三角形 BCH、ACH 和 ABC 两两相似
2. a²=a'c, b²=b'c.
顺便说一句，根据关系 2，勾股定理如下：
a²+b²=a'c+b'c=c(a'+b')=c².
3. h²=a'b', h=ab/c.
4. 设 R 为内切圆的圆心，r 为其半径 (图 2)。

图 1.

⟦folio 57⟧

然后$r = \frac{a+b-c}{2}$。

证明。请注意，四边形 $RKCL$ 是正方形，我们使用切线段相等：$c = a - r + b - r$，因此$r = \frac{a+b-c}{2}$。

5. $\angle ARB = 180^\circ - \frac{1}{2} \angle A - \frac{1}{2} \angle B = 135^\circ$.

更复杂的语句

让我们将圆内接于三角形 $ACH$ 和 $BCH$ (图 3)。设它们的半径分别为$r_1$和$r_2$

6. $r + r_1 + r_2 = h$.

证明。我们有$r = \frac{a+b-c}{2}$、$r_1 = \frac{h+b'-b}{2}$、$r_2 = \frac{h+a'-a}{2}$。添加这些表达式，我们就得到了我们需要的东西。

7. $r^2 = r_1^2 + r_2^2$.

证明。根据三角形$ACH$和$ABC$的相似性，可以得出$\frac{r_1}{r} = \frac{b}{c} = \cos \alpha$，此外还有$\frac{r_2}{r} = \frac{a}{c} = \cos \beta = \sin \alpha$。所以，$r_1 = r \cos \alpha$，$r_2 = r \sin \alpha$。因此，$r_1^2 + r_2^2 = r^2$。

8. $AC = AQ$, $BC = BP$.

证明。第一个等式来自角度 $\angle CQA = \angle BCQ + \angle B = \frac{1}{2} \alpha + \beta = \angle ACH + \angle HCQ = \beta + \frac{1}{2} \alpha = \angle ACQ$ 的等式链。第二个等式可以用类似的方法证明。

9. 点$T$（参见图3）是三角形$CRS$的高（垂心）与三角形$CPQ$的外心的交点。

图 2.

证明。 BS 和 AT 是角 B 和 A 的平分线。这意味着线 BS 和 AT 分别垂直于 CP 和 CQ，并且平分这些线段。

10. 直线$T_1R$和$T_1S$平行于相应的BC和AC。

证明。从点 $T_1$ 开始，我们将垂线 $T_1R_2$ 降低到 AC (图 4)。设$R^*$为$TR_2$与AT的交点。让我们证明$R^* = R$。

三角形$ATT_1$和$AR^*R_2$相似。因此$\frac{R^*R_2}{TT_1} = \frac{AR_2}{AT_1} = \cos \alpha$，因此$R^*R_2 = TT_1 \cos \alpha = r \cos \alpha = r_1$，即点$R^*$位于角A的平分线上，并且与AC相距距离$r_1$，但这意味着$R^* = R$。同理，证明$T_1S \parallel AC$。

练习 1. 自己证明以下命题：

11. 线PS 平行于AT 并且线RQ 平行于BT。

12. 三角形ATB、BSC和ARC相似。

13. 点 H 和 T_1 位于直径为 RS 的圆上。

14. $ST_1 = RT_1$.

证明。由于$\triangle T_1RR_1$是直角且$\angle RT_1R_1 = \beta$，我们有$T_1R \sin \beta = r_1 = r \sin \beta$，因此有$T_1R = r$。类似地可以证明$T_1S = r$。

15. $CU = CV$.

证明。三角形$ST_1R$是等边直角三角形。因此$\angle TS_1R = \angle CUV = 45^\circ$。这意味着三角形 $CUV$ 是等边三角形。

16. 点 Q、S、T、R、P 位于以点 $T_1$ 为圆心、半径为 $r$ 的圆上。

证明。点 S 和 R 位于该圆上。让我们证明一下
