---
id: 1975-9-kaganov-lyubarskiy-otvet-na-vopros-chitatelya-v-krasina-po-state-elektron-izluchaet-fotonyi-af104511
issue: kvant_1975_9
year: 1975
number: "9"
title: '[回答读者V. Krasin关于《电子发射光子》一文的问题]'
authors:
  - Каганов М. И.
  - Любарский Г. Я.
rubric: raznoe
page_first: 47
page_last: 48
page_labels: 45-46
tag: 0DKA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b9091ecc829c24e5f86167a547f61439fa8a8a6398f9bc1ae961c1a17f0dc216
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/12_kaganov-lyubarskiy-otvet-na-vopros-chitatelya-v-krasina-po-state-elektron-izluchaet-fotonyi-af104511.md
source_content_sha256: 485768a8b7b065d64f8ce2a1d58d0d3d6cc1c0a42127406b5e2c8df4a39735ec
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

## 提问 - 我们回答

在本期杂志中，我们回答了读者 V. Krasin（莫斯科一所学校的十年级学生）提出的问题。

亲爱的编辑们！

《电子发射光子》一文（«Kvant»，1974年，第12期）讨论了加速带电粒子如何发射电磁能，并提供了计算这种辐射强度的公式：

$$I = 2e^2a^2/3c^3 \quad (*)$$

（e 是电荷，是粒子的加速度）。

另一方面，给出了沿着弯曲电路流动的直流电的例子，并且据说“这样的电流产生恒定的磁场，但不辐射”。

我读到的内容在我脑海中提出了两个问题：

1) 为什么当电子沿着弯曲导体移动并因此加速时不发射？

2) 即使在电流流过直导体的情况下，也不存在辐射，这是否与金属的经典电子理论相矛盾？根据这一理论，金属中的载流子是自由电子，它们在没有电场的情况下无序地运动。在电场的影响下，有序运动叠加在混沌运动上，使得电子的平均速度不为零。沿导体移动的电子会与晶格的离子发生碰撞，从而为它们提供碰撞期间运动期间积累的所有能量（该能量以热的形式释放）。如果恒定电流流过导体，电子的平均速度不随时间变化。但在碰撞之间的时间间隔内，电子以加速的速度移动，因此它必须辐射。

⟦column⟧

下面我们发布《电子发射光子》一文作者的答案。

产生这些问题的原因是文章中的措辞不准确。

我们先从第二个问题开始。 V. Krasin 简要而正确地描述了电流通过金属的过程。我们将准确地利用他概述的想法进行一个小计算。

考虑承载直流电的直导体。我们选择这个导体的 1 $см^3$，计算电子在这一段导体中移动时在 1 秒$N$ 内发出的能量，并将其与该体积中每秒释放的热量进行比较。由于在碰撞之间每个电子以加速度 $a = eE/m$ 运动（e 是电子的电荷，m 是其质量，E 是电场强度），因此它会释放能量。根据引用文章的公式（1），该辐射的强度等于

$$I = \frac{2e^2a^2}{3c^3} = \frac{2e^4E^2}{3c^3m^2},$$

N电子的辐射强度分别为

$$NI = \frac{2Ne^4E^2}{3c^3m^2}.$$

根据焦耳-楞次定律，电阻为R的导体在1s内放出的热量等于$i^2R$。当前值i

45

⟦folio 46⟧

可以通过电流密度$j$：$i=jS$来表示（$S$为导体的横截面积）。电流密度与电场强度相关：$j = \lambda E$，其中$\lambda$是电导率。 （回想一下 $\lambda = \dfrac{1}{\rho}$，其中 $\rho = \dfrac{RS}{L}$ 是长度为 $L$、横截面为 $S$ 的导体的电阻率。）那么，体积为 $V$ 的 1 $см^3$ 导体中每秒释放的热量是相等的

$$Q = \frac{i^2 R}{V} = \lambda E^2 .$$

让我们根据经典电导率理论，通过电子参数来表达$\lambda$。如果电子定向运动的平均速度为$\bar v$，则电流密度为$j = eN\bar v$。另一方面，$j = \lambda E$，所以$\lambda = \dfrac{eN\bar v}{E}$。

让我们找出速度 $\bar v$ 等于多少。

以加速度 $eE/m$ 移动，在自由路径结束时，电子获得速度 $v_{max} = a\tau = \dfrac{eE}{m}\tau$（$\tau$ 是自由路径时间）。定向运动的平均速度为$\bar v = \dfrac{1}{2} v_{max} = \dfrac{1}{2}\dfrac{eE}{m}\tau$。

时间$\tau$可以求得电子自由程$l$与其热运动速度$v_{\text{т}}$的比值（定向运动速度$\bar v$比混沌运动速度$v_{\text{т}}$小很多倍），即

$$\tau = \frac{l}{v_{\text{т}}} . \qquad \text{Поэтому} \qquad \bar v = \frac{1}{2}\frac{eE}{m}\frac{l}{v_{\text{т}}} .$$

因此，$\lambda = \dfrac{1}{2}\dfrac{e^2 Nl}{mv_{\text{т}}}$。 1 $см^3$ 导体每秒产生热量

$$Q = \frac{1}{2}\frac{e^2 Nl}{mv_{\text{т}}} E^2 .$$

现在让我们计算电子发射的能量与释放的热量的比率：$\dfrac{NI}{Q} = \dfrac{4}{3}\dfrac{e^2 v_{\text{т}}}{mc^3 l}.$

让我们更多地表达这个表达

⟦column⟧

通过引入经典电子半径$r_e = e^2/mc^2$进行视觉表示：

$$\frac{NI}{Q} = \frac{4}{3}\frac{r_e}{l}\cdot\frac{v_{\text{т}}}{c} .$$

让我们估计一下这种关系的严重程度。由于$r_e = 2,5\cdot 10^{-13}$ cm，平均自由程$l$不小于$10^{-6}см$，电子热运动的平均速度为$v_{\text{т}} \approx 10^8$$см/с$，则

$$\frac{NI}{Q} \approx 10^{-9} (!)$$

可以看出，碰撞之间电子的加速运动所产生的辐射是多么小。原则上它可以被检测到，但在大多数实际情况中，这种辐射不起任何作用。

现在我们来看看V. Krasin 信中的第一个问题。让我们考虑弯曲导体，例如，形状像半径为$r$的圆的导电电路。对于电子的混沌运动，导体的形状自然并不重要，因为平均自由程通常明显小于其最小尺寸，尤其是圆的半径$r$（电子在碰撞之间“不知道”导体是否弯曲）。但平均而言，电子当然会做圆周运动，因此加速度为 $\bar v^2/r$。然而，这个加速度非常小，甚至小于碰撞之间的加速度$a = eE/m$。我们来检查一下这个声明。从不等式$\dfrac{eE}{m} \gg \dfrac{\bar v^2}{r}$我们可以得出不等式$\bar v \ll v_{\text{т}}\dfrac{r}{l},$

这显然是满足的，因为$r \gg l$和$v_{\text{т}} \gg \bar v$（可以使用电流密度表达式和$N \approx 10^{22} \div 10^{23}$$см^{-3}$轻松估计$\bar v$的值）。

显然，与弯曲区域中的加速运动相关的辐射当然可以忽略不计。

M.Ts。卡加诺夫，G.亚。柳巴尔斯基
