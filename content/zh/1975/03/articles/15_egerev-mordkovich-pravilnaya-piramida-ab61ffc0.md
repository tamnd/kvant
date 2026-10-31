---
id: 1975-3-egerev-mordkovich-pravilnaya-piramida-ab61ffc0
issue: kvant_1975_3
year: 1975
number: "3"
title: 正确的金字塔
authors:
  - Егерев В. К.
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 63
page_last: 67
page_labels: 61, 62, 64, 65
tag: O49A
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 269763c5f2f665781879abfce666e22d3c5bcb25510081032b14708711e1ee32
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/15_egerev-mordkovich-pravilnaya-piramida-ab61ffc0.md
source_content_sha256: 50f9f644a6aabe83388106292ceeb28b52f6b10a212dbf1a592ac8b51b921242
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 61⟧

正确的参数
V.K.埃格列夫、A.G.莫德科维奇

许多几何问题的解决都具有固有的人为性，这导致德国百年哲学家叔本华指责几何学使用“捕鼠器证明”。事实上，几何问题的解法包含很少的模式，并且常常给人一种把戏的印象。更重要的是要知道解决这些问题时仍然使用的少量“标准”技术。我们杂志的页面上已经讨论了一些技术（例如，参见 I. A. Kushi 的文章“辅助元素的方法”，«Kvant»，1974 年，第 2 期）。本文讨论另一种这样的技术。

2. Paramid 中角度之间的关系

图1显示了正方聚酰胺SABCD...的一部分，SH-高度，SK-边心。让我们引入以下符号：

α——侧边与底座平面的夹角；
β——侧边与基面的夹角；
γ——横切侧肋间夹角；
φ——横切侧面之间的角度。

1. 「平底锅法」
让我们从一个小寓言开始吧。有人向安德烈解释了如何煮鸡蛋：“将平底锅从指甲上取下，倒入水，放入鸡蛋，点燃煤气，将平底锅放在煤气灶上，水沸腾5分钟后将其取出。” Andryusha 就是这样做的，一切都很顺利。但有一天我们早上醒来，安德烈看到锅里已经倒了水，煤气正在燃烧。想了想，他打开煤气，倒掉水，把锅挂在钉子上，然后按照老师教的去做。

尽管这种行为十分荒谬，但返回的方法

⟦figure⟧
| 角度 | 比率 | | 角度变化区 | 角度之间的连接 |
|---|---|---|---|---|
| α; φ | $\sin \alpha = \mathrm{ctg}\dfrac{\varphi}{2}\,\mathrm{ctg}\dfrac{\pi}{n}$ | (1) | $0 < \alpha < \dfrac{\pi}{2}$ | |
| α; γ | $\cos \alpha = \sin\dfrac{\gamma}{2}\Big/\sin\dfrac{\pi}{n}$ | (2) | $0 < \beta < \dfrac{\pi}{2}$ | $\gamma < \pi - 2\alpha$ |
| α; β | $\mathrm{tg}\,\alpha = \mathrm{tg}\,\beta \cdot \cos\dfrac{\pi}{n}$ | (3) | $0 < \gamma < \dfrac{2\pi}{n}$ | $\alpha < \beta$ |
| β; γ | $\cos \beta = \mathrm{tg}\dfrac{\gamma}{2}\,\mathrm{ctg}\dfrac{\pi}{n}$ | (4) | $\pi - \dfrac{2\pi}{n} < \varphi < \pi$ | |
| β; φ | $\mathrm{tg}\,\beta = \dfrac{\sqrt{2}\cos\dfrac{\varphi}{2}}{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}$ | (5) | | $\varphi > \pi - 2\beta$ |
| γ; φ | $\sin\dfrac{\gamma}{2} = \dfrac{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\varphi}{2}}$ | (6) | | |

如果在正金字塔中已知其中一个角度，则可以找到其他三个角度。表中显示了六个比率。让我们证明其中的一些。

(1) (α; )。考虑三角形$LMC$和$LMD$，我们得到

$\mathrm{tg}\dfrac{\varphi}{2} = \dfrac{CL}{LM}$，$\sin \alpha = \dfrac{LM}{LD}$。方法，

$\mathrm{tg}\dfrac{\varphi}{2}\sin\alpha = \dfrac{CL}{LD} = \mathrm{tg}\,\angle CDL =$

$= \mathrm{tg}\left(\dfrac{\pi}{2} - \dfrac{\pi}{n}\right) = \mathrm{ctg}\dfrac{\pi}{n}$.

(2)(α；γ)。考虑三角形$AHS$和$AKS$，我们得到

$\cos\alpha = \dfrac{AH}{AS}$，$\sin\dfrac{\gamma}{2} = \dfrac{AK}{AS}$。方法，

$\dfrac{\sin\dfrac{\gamma}{2}}{\cos\alpha} = \dfrac{AK}{AH} = \sin \angle AHK = \sin\dfrac{\pi}{n}$.

(3)(α；β)。考虑三角形$AHS$和$SHK$，我们得到$\mathrm{tg}\,\alpha =$

$= \dfrac{SH}{AH}$，$\mathrm{tg}\,\beta = \dfrac{SH}{KH}$。所以，$\dfrac{\mathrm{tg}\,\alpha}{\mathrm{tg}\,\beta} =$

⟦column⟧

$= \dfrac{KH}{AH} = \cos \angle AHK = \cos\dfrac{\pi}{n}$.

让我们注意这些公式的一些结果。

由 (1) 可知 $\mathrm{ctg}\dfrac{\varphi}{2} = \sin\alpha \times$

$\times\, \mathrm{ctg}\left(\dfrac{\pi}{2} - \dfrac{\pi}{n}\right)$。但$\sin\alpha < 1$意味着

$\dfrac{\varphi}{2} > \dfrac{\pi}{2} - \dfrac{\pi}{n}$ 或 $\varphi > \pi - \dfrac{2\pi}{n}$。

由(2)可知$\sin\dfrac{\gamma}{2} = \cos\alpha \sin\dfrac{\pi}{n}$。

但 $\cos\alpha < 1$ 意味着 $0 < \dfrac{\gamma}{2} < \dfrac{\pi}{n}$ 或

$0 < \gamma < \dfrac{2\pi}{n}$。从同样的公式可以得出，

$$\dfrac{\sin\dfrac{\gamma}{2}}{\sin\left(\dfrac{\pi}{2} - \alpha\right)} = \sin\dfrac{\pi}{n} < 1,$$

什么

那是，

$\dfrac{\gamma}{2} < \dfrac{\pi}{2} - \alpha$ 或 $\gamma < \pi - 2\alpha$。

由 (3) 可知 $\dfrac{\mathrm{tg}\,\alpha}{\mathrm{tg}\,\beta} = \cos\dfrac{\pi}{n} < 1$,

$0 < \alpha < \beta$从何而来（一般来说这是显而易见的）。

⟦folio 62⟧

⟦folio 64⟧

问题 6. 已知 $a$ 和 $\gamma$，找出 $S$。

使用“平底锅法”很容易解决这个问题：利用公式（4）和（8），我们得到

$$S = \frac{na^2\, \mathrm{ctg}\dfrac{\gamma}{2}}{4}.$$

但也许直接解决问题更容易：

$$S = n \cdot S_{\triangle ASB} = n \cdot \frac{1}{2}AB \cdot SK =$$

$$n \cdot \frac{1}{2}a \cdot \frac{a}{2}\mathrm{ctg}\frac{\gamma}{2} = \frac{na^2\, \mathrm{ctg}\dfrac{\gamma}{2}}{4}.$$

问题 7. 已知 $a$ 和 $\alpha$，找出 $S$。

由式(3)可得关系式

$$\cos\beta = \frac{\cos\dfrac{\pi}{n}}{\sqrt{\mathrm{tg}^2\alpha + \cos^2\dfrac{\pi}{n}}}$$

（一探究竟！）。因此，

$$S = \frac{na^2\sqrt{\mathrm{tg}^2\alpha + \cos^2\dfrac{\pi}{n}}}{4\sin\dfrac{\pi}{n}}$$

问题 8. 已知 $a$ 和 $\varphi$，找出 $S$。

由式(5)可知

$$\cos\beta = \frac{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\pi}{n}}$$

（查看！）。利用式(8)，我们得到

$$S = \frac{\sqrt{2}\, na^2\cos\dfrac{\pi}{n}}{4\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}.$$

## 5. 计算外接球的半径

问题 9. 已知 $a$ 和 $\alpha$，找出 $R$。

众所周知，总是可以描述一个接近正金字塔的球；它的中心$O$位于金字塔高度$SH$与垂线的交点

⟦column⟧

$FO$ 到侧边缘，通过边缘 $AS$ 的中间 $F$ 绘制（参见 图 2）。然后$\angle SOF =$
$= \angle SAH = \alpha$。我们有$AS = \dfrac{AH}{\cos\alpha} =$
$= \dfrac{a}{2\sin\dfrac{\pi}{n}\cos\alpha}$; $\quad R = OS = \dfrac{FS}{\sin\alpha} =$
$= \dfrac{AS}{2\sin\alpha};$

$$R = \frac{a}{2\sin\dfrac{\pi}{n}\sin 2\alpha}. \tag{9}$$

问题 10. 已知 $a$ 和 $\beta$，找出 $R$。

由式(3)可知

$$\sin 2\alpha \cdot \frac{2\,\mathrm{tg}\,\alpha}{1+\mathrm{tg}^2\alpha} = \frac{2\,\mathrm{tg}\,\beta\cos\dfrac{\pi}{n}}{1+\mathrm{tg}^2\beta\cos^2\dfrac{\pi}{n}}.$$

利用式(9)，我们得到

$$R = \frac{a\left(1+\mathrm{tg}^2\beta\cos^2\dfrac{\pi}{n}\right)}{2\sin\dfrac{2\pi}{n}\,\mathrm{tg}\,\beta}.$$

问题 11. 已知 $a$ 和 $\gamma$，找出 $R$。

由式(2)可知

$$\sin\alpha = \frac{\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\pi}{n}} \text{ (проверь-}$$

那些！），以及$\sin 2\alpha = 2\sin\alpha\cos\alpha =$

$$= \frac{\sqrt{2}\sin\dfrac{\gamma}{2}\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}{\sin^2\dfrac{\pi}{n}}.$$

方法，

$$R = \frac{a}{2\sin\dfrac{\pi}{n}\sin 2\alpha} =$$

$$= \frac{\sqrt{2}\,a\sin\dfrac{\pi}{n}}{4\sin\dfrac{\gamma}{2}\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}$$

⟦folio 65⟧

图 2. 图 3.

公式

$$R = \frac{\sqrt{2} \sin \frac{\varphi}{2} \mathrm{tg} \frac{\varphi}{2} \mathrm{tg} \frac{\pi}{n}}{4 \sqrt{1 - \cos \varphi - \cos \frac{2\pi}{n}}},$$

通过$a$和$\varphi$表达$R$，证明。

6. 计算内切球的半径

众所周知，球总是可以刻在规则的paramid中；它的中心 $O$ 位于 paramid 的高度 $SH$ 与角 $SKH$ (图 3) 的平分线的交点。因此，在给定角度$\beta$的情况下，最容易计算内切球的半径；我们将从这个案例中进行教学。

问题 12. 已知 $a$ 和 $\beta$，找出 $r$。

我们有$r = OH = KH \cdot \mathrm{tg} \frac{\beta}{2}$；

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \mathrm{tg} \frac{\beta}{2}. \tag{10}$$

问题 13. 已知 $a$ 和 $\alpha$，找出 $r$。

由式(3)可知

$$\mathrm{tg} \frac{\beta}{2} = \frac{\sqrt{\cos^2 \frac{\pi}{n} + \mathrm{tg}^2 \alpha - \cos \frac{\pi}{n}}}{\mathrm{tg} \alpha}.$$

由式(10)我们可得

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \mathrm{tg} \frac{\beta}{2} =$$

$$\frac{a \mathrm{ctg} \frac{\pi}{n} \left( \sqrt{\cos^2 \frac{\pi}{n} + \mathrm{tg}^2 \alpha - \cos \frac{\pi}{n}} \right)}{2 \mathrm{tg} \alpha}.$$

问题 14. 已知 $a$ 和 $\gamma$，找出 $r$。

由式(4)、(10)可得

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \cdot \frac{\sin \left( \frac{\pi}{n} - \frac{\gamma}{2} \right)}{\sin \left( \frac{\pi}{n} + \frac{\gamma}{2} \right)}.$$

自己找出表达式 $r$ 到 $a$ 和 $\varphi$。

你对吧

1. （莫斯科工程物理学院，1973）。如果正三角形帕拉米德侧面之间的二面角等于 $\alpha$，则求该正三角形帕拉米德的底面和侧面之间的二面角。
2. （UDN，1973）。规则 4 角形聚酰胺侧边的二面角等于 $\alpha$。求侧边处的二面角等于 $2\alpha$。求出帕拉酰胺的体积。
4. （USU，1973）。正三角形帕拉米德的高为$h$，高底到侧边的距离为$a$。确定 paramid 侧面之间的二面角。
5. （马蒂，1973）。正六边形帕拉酰胺侧面的每个等角都等于$\varphi$。高度中间到侧边的距离为$l$。求出 paramid 的高度。
6. （梅，1973）。正四方帕拉酰胺的高度为$h$，相邻侧面之间的平面角为$\varphi$。求侧面积。
7. （UDN，1973）。围绕半径为$R$的球外接的正四方帕拉米德的底边等于$a$。找到 paramid 的完整表面。
8. （NSU，力学，1969）。正四棱酰胺的侧边二面角等于$\alpha$，内接球的半径为$R$。找到 paramid 的完整表面。
9. （亚皮，1973）。正四方 Paramidian 内接于半径为 $R$ 的球，其顶点处的平面角等于 $\alpha$。求出帕拉酰胺的体积。
10. （来自读者来信）求paramid$SABC$的体积，如果高度与底面倾斜$30^\circ$角度，$\triangle ABC$是等边，半径为$r$的内接圆，$SC = OC$和$SO \perp BA$。

G.M-va
