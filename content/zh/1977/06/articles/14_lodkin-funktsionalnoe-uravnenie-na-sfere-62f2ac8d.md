---
id: 1977-6-lodkin-funktsionalnoe-uravnenie-na-sfere-62f2ac8d
issue: kvant_1977_6
year: 1977
number: "6"
title: 球面上的函数方程
authors:
  - Лодкин А. А.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 60
page_labels: 57-58
tag: EK09
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1162841cb3078df1e63445b972595431fad4fa079d3f233896e713dce7686847
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/14_lodkin-funktsionalnoe-uravnenie-na-sfere-62f2ac8d.md
source_content_sha256: 1e36c50f100705fe5d4f7edcd3a66919f10c370331b4ffd6a9b1dff26563173b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

A·洛德金

球面上的函数方程

在这篇笔记中，我们将解决在全联盟数学奥林匹克竞赛第二届（研究）X 类中向十年级学生提出的一个问题。这个问题被放在《给Kvanta的作业》（«Kvant»，1976年，第10期，M410）中。让我们回顾一下它的表述。

在半径为 1 的球体上画一个大圆，我们称之为等圆。我们使用其他地理术语会很方便：条纹、子午线、平行线。

a) 让我们在这个球体上定义一个函数 f，为球体上的每个点分配从该点到赤道平面的距离的平方。检查该函数是否具有以下属性：

如果$M_1, M_2, M_3$是球体三个相互垂直的半径的端点，则$f(M_1) + f(M_2) + f(M_3) = 1$。 (*)

在以下所有段落中，f 是球面上的任意非负函数，它在等角线的所有点处消失并具有属性 (*)。

b) 令 M 和 N 为位于北条纹和赤道之间的同一子午线上的点。让我们证明，如果点 M 比点 N 距离赤平面更远，则$f(M) \geq f(N)$。

c) 令M和N为球体的任意点。让我们证明，如果点 M 距离赤平面比 N 更远，则$f(M) \geq f(N)$。

2) 证明函数 f 与 a) 部分描述的函数一致。

问题a）的解决方案

问题a)实际上出现在学校教科书“几何10”中（§ 43，问题14）。这是她的解决方案。让我们给出一个矩形基础（框架）$\vec{OM}_1, \vec{OM}_2, \vec{OM}_3$。考虑向量 $\vec{OP}$，其中 P 是球体的条纹。令 F (M) 表示向量 $\vec{OM}$ 与 $\vec{OP}: F(M) = (\vec{OM} \cdot \vec{OP})^2$ 标量积的平方。显然，F 与 a) 部分中提到的函数相同。向量$\vec{OP}$在基$\vec{OM}_1, \vec{OM}_2, \vec{OM}_3$中的坐标非常印度，等于点$M_1, M_2, M_3$到赤平面的距离。但向量 $\vec{OP}$ 的标量平方等于 1。这为我们提供了球体上的对应函数，在等角线的所有点处都等于 0，并且具有属性 (*)。

解决问题 b) 和 c)

显然，问题的b）点是由c）推导出来的；因此，我们立即证明b)点的说法。

图 1.

⟦folio 58⟧

根据条件 (*)，函数 $f$ 在球体直径相对的点处取相同的值。因此，我们只考虑北半球点的函数值就足够了。

因此，令 $M$ 和 $N$ 为北半球的两点。让我们证明，如果$M$比$N$距赤道平面更远，则$f(M) \geq f(N)$。

证明。该距离是最北点为 $M$ 的大圆的周长。设 $\Gamma_M$ 为该圆位于北半球的部分。

我们首先假设$N$也位于$\Gamma_M$上。我们还用$N'$表示灵魂$\Gamma_M$的点$[ON'] \perp [ON]$，并用$M'$表示灵魂$\Gamma_M$与赤道的两个交点之一。然后从 (*) 得出等式 $f(N) + f(N') = f(M) + f(M')$，因为 $[OM] \perp [OM']$ 和点 $M, M', N, N'$ 位于同一平面，因此对于点 $M, M'$ 和 $N, N'$，“第三”点将相同：垂直于圆$\Gamma_M$ 平面的半径端点。从$f(M') = 0$开始，然后$f(M) \geq f(N)$。

现在让点$N$位于$\Gamma_M$以南的北半球区域。然后在$\Gamma_M$上找到一点$Q$，使得大圆$\Gamma_Q$的圆弧穿过$N$（图2）。将前面的计算应用到点$M$和$Q$、$N$的参数上，我们得到不等式$f(M) \geq f(Q) \geq f(N)$。

如果$N$位于$\Gamma_M$以北，那么从$M$“下降”到$N$可能需要两步以上。让我们将分别通过点 $M$ 和 $N$ 的子午平面 $m$ 和 $n$ 之间的角度 $\lambda$ 分成子午平面 $m_1, \dots, m_{k-1}$ (图 3) 的 $k$ 等份。让我们沿着弧线$\Gamma_M$离开$M$，并在该弧线与子午线$m_1$的交点$M_1$处，我们转向弧线$\Gamma_{M_1}$。到达$\Gamma_{M_1}$与$m_2$的交点$M_2$后，我们转向$\Gamma_{M_2}$，依此类推。旅程的最后一点将是$n$的$M_h$点。你，非常印度人，注意到$k$越大，下降轨迹越“平坦”。不难证明，$M_h$点的纬度$\varphi(M_h)$在$M_h$的帮助下可以适当逼近$\varphi(M)$（注意$tg\varphi(M_h) = tg\varphi(M_{k-1})\cos \frac{\lambda}{k} = \dots = tg\varphi(M)$），如果$k$足够大，就会在$N$以北。从$M_h$下降到$N$需要两步以上。

函数 $f(M)$ 仅取决于纬度

让我们用 $\Pi_x$ 表示距赤道面 $Vx$ 的平行线。为了解决问题$r$，我们会遇到这样一个问题。

引理。如果$x+y+z=1$，我们可以构造一条直线
