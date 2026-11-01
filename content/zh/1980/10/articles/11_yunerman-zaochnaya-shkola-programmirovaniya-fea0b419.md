---
id: 1980-10-yunerman-zaochnaya-shkola-programmirovaniya-fea0b419
issue: kvant_1980_10
year: 1980
number: "10"
title: 函授编程学院
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 51
page_labels: 47-49
tag: I2VE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 41f02b5f6ab0d1c589c6c101ade4ec1394f4d088a81ce7a835f99161764e6c91
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/11_yunerman-zaochnaya-shkola-programmirovaniya-fea0b419.md
source_content_sha256: b0b86e95690d1c1224b5ec152dce8a5530aa814cbe833d86059125db38a774cc
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

函授编程学院
第10课：极坐标系中的编程问题

本课程的材料面向 8 至 10 年级的学生。对于小学生来说，该材料被认为是可选的。

关于极坐标系
为了确定平面上一点的位置，有多种坐标系。与您从学校教科书上知道的系统（称为 `dekartовой`）一起，它使用 `полярную` 坐标系来解决许多问题。

平面上一点的极坐标是两个数字，确定该点相对于某个固定点 $O$ 的位置，称为 `полюсом`，而不是

$$\rho = \sqrt{x^2 + y^2}, \quad \sin \varphi = \frac{y}{\sqrt{x^2 + y^2}},$$

在逆变换过程中 - 根据公式

$$x = \varphi \cos \varphi, \quad y = \varphi \sin \varphi.$$

阿基米德螺线
假设我们需要构造一条曲线，该曲线由一个点以恒定速度 $v$ 沿着绕极点 $O$ 以恒定角速度 $\omega$ 旋转的射线来描述。该曲线的极坐标方程为

$$\rho = a\varphi,$$

其中$a = \frac{v}{\omega}$。曲线 (1) 称为 `спирали Архимеда` (图 3)。

要使用 Shpar 图形系统在计算机上构造阿基米德螺线，可以方便地使用 POLAR 程序（«Kvant»，1980，第 1 期，第 56 页）。

亲自检查用 Rapier 语言编写的程序 (2)，图 阿基米德螺线（循环 BYE 的面在面 $5 \times 2\pi$ 中选择，提供 p-

⟦folio 48⟧

推动螺旋圈的跟部）。请记住，使用“应用程序”和“梁”程序时，第一个直径充当极半径，第二个直径充当极角。
P(100,100); H(50.50);
。极性; 2->A； 0->FI；
3.1416->PI； P(0,0);
(2)
当 FI<10*PI::
FI+0.01->FI；
L(A*FI,FI)
全部;
。结尾;
任务 10.1。编写一个程序来构造由方程描述的曲线：
a) $\varphi = a (1 + \cos \varphi)$ – 心形，
b) $\varphi = \frac{a}{\varphi}$ 是双曲螺线。

“花”一家人
封面第二页再现了电脑图制作的“花”家族。该族曲线在极坐标中的方程具有以下形式
$\varphi = A \sin B \varphi$.
(3)

任务 10.2。
1) 系数$A$由什么决定？
2) 各个花瓣以什么顺序出现？
3) 如果在方程（3）中我们用|sin Vf|代替sin Vf，图会如何变化？

4) 花瓣的数量与系数B的值有何关系？
分别考虑B为偶数和B为奇数的情况。
5) 如何组织循环以便：
a) 按照封面上显示的顺序画“花”（恢复程序）？
b) 在“花”家族中仅描绘那些具有参数 B 的非人类值的花？
b) 画出一族只有B的整数值的“花”？
（无需在图片下方编写说明文字。）

正六边形
在编程奥林匹克（«Kvant»，1980年，第3号）中，提出了两个问题，如果使用极坐标系，则更容易解决。
第一个问题（问题 3）的表述如下：创建一个程序来描绘一个正 16 边形，其中绘制所有不通过中心的对角线。
考虑一个极坐标系，极点位于多边形 $O$ 的中心，极轴 $OX$ 沿着射线 $OA_{16}$ (图 4)。
让我们找到这个多边形顶点的极坐标。第一个坐标（极坐标尺寸）

⟦folio 49⟧

所有顶点的 dius) 都相同，等于外接圆 R 的半径，第二个坐标（极角）由公式 $\varphi_K = (\pi/8)*K$ 计算，其中 K 为顶点数。

要画出所需的图形，需要将编号为N（1≤N<16）的顶点与除编号为（N+8）的顶点之外的所有编号大于N的顶点连接起来（毕竟是连接编号为N和N+8的顶点经过中心的线段）。如果我们将每个顶点 N 与所有其他顶点连接，那么每个线段将被绘制两次。

给参数 R 不同的值，我们将获得类似的正 16 边形。

过程参数可以是任何算术表达式。例如，在APPROACH和BEAM过程中，对应点的坐标是使用表达式预先计算的。在 FRAME 和 BEGIN 过程中，表达式用作参数，以确保多边形正确定位，严格位于绘图区域的中间。根据带有参数 K 的 DIAG 过程，顶点编号 N 将连接到顶点编号 K。 PERCENT DIAG K；
P(R,N*PI/8);
L(R,K*PI/8);
肯塔基州委员会；
最终程序如下所示：
50—>R;
P(2*R+50,2*R+50);
H(R+25，R+25)； 3.1416—>PI；
。极性; 1—>N；
再见，N<16::
1+N—>K;
再见 K<16::
如果 K/=N+8 TO
诊断（K）； K+1—>K
全部;
N+1—>N
全部;
。结尾;
该程序的结果是图5。

任务 10.3。编写一个程序来绘制正确的 N 墙。
