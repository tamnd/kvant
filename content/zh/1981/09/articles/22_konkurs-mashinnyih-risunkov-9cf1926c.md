---
id: 1981-9-konkurs-mashinnyih-risunkov-9cf1926c
issue: kvant_1981_9
year: 1981
number: "9"
title: 机器竞赛图
rubric: raznoe
rubric_sub: Разное
page_first: 57
page_last: 58
page_labels: 55-56
tag: Z9WV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f3b2ba4a3d4daaa3177b6757a4ccbb9396ed203e29124a136f89ed3720303396
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/22_konkurs-mashinnyih-risunkov-9cf1926c.md
source_content_sha256: a1a4fb42f6c498aa53c2aa4805b97f0536bca719ef4068b7bb818d1637250e0b
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

数据 - 集*)。以下问题«Kvant»选择Pascal语言进行初步研究。

读者可以在以下文献中更彻底地熟悉本文讨论的语言：Pervin Yu。 A.“Fortran 基础知识”（M.，“Nauka”，1973）。
Lavrov S.S.“通用编程语言（Algol-60）”（M.，“Nauka”，1972）。

*) 慢慢变得负责任的剑杆织机利用了这一新颖性 - 参见«Kvant»，1980，第 3 期，ZShP，第 8 课。

竞赛
机器
图

《«Kvant»》杂志的编辑和苏联科学院西伯利亚分院计算中心宣布，将在使用计算机图形系统的计算机上进行最佳的《图》竞赛。

小学生、职业学校学生均可参加比赛。

写实或程式化的图、装饰品、数学曲线族、曲面图像等。图必须是原创的（竞赛不接受在我们杂志上发表的图的重复），数学兴趣的装饰品和图案必须与自然优点相结合。

对于图，您必须附上程序的完整打印输出、详细的注释、解释数学思想和程序的运行顺序、作者的详细信息 - 姓氏、名字、父名、学校和班级编号、完整的家庭住址。

无法独立访问具有图形空间的计算机的学生可以发送用于构建 图 的程序，并附上大致摘录。程序可以使用 Shpar 系统在 Rapier、Pascal 或 Algol 中执行（参见 «Kvant», 1980, No. 1, p. 56），也可以使用下面描述的图形系统在 Fortran 中执行。程序体积不超过100个操作员，尺寸图不小于100×100毫米且不大于300×300毫米。

在将程序提交给竞赛之前，请仔细手动检查：竞赛参赛作品中的错误将不会被纠正。

竞赛的所有部分（包括函授编程学院的学生及其电影）必须在1981年11月15日之前将作品提交至竞赛地址：630090, Novosibirsk, 90,Computing Center of the Siberian Branch of the USSR Academy of Sciences, School Information Group。

祝您好运！我们等待图和节目！

对于 Fortran 初学者
要从 Fortran 程序访问图形系统，必须遵循以下规则：

1. 在程序开始处必须有一个启动 CALL SBROS 语句，并且在其逻辑完成之前必须有一个 CALL STR 语句。

2. 对于笔直线运动到指定点，使用操作符 CALL LINX(X,Y)，其中 X、Y 是该点的坐标，单位为 mm；如果笔关闭，则执行冷笔画；如果关闭，则会绘制一段。您可以使用 CALL PERO 和 CALL VP 操作符在适当的时刻打开和关闭笔。

3. 要绘制“具有自由端”的线段，您还可以调用模块 CALL OTREZ (XN, YN, XK, YK)，

⟦folio 56⟧

其中参数是线段起点和终点的坐标；该模型本身会在段的起始点打开笔，并在绘制后将其打开。

4. 使用CALL OKR(XC,YC,R)操作符可以画出一整个圆，其中XC、YC是圆心坐标，R是半径，画笔也是自动开启的。可以通过写行 CALL OKRI (XC, YC, R, ALF, DALF) 来画一个朋友；这里ALF是初始圆心角，DALF是圆弧的角顶点，其符号决定了遍历的方向。当然，角度尺寸以度为单位，但度数不是测量出来的。画完弧线后，笔本身不开机；如果需要，可以通过CALL VP操作员来启用；笔在弧线开始时自动打开；如果在访问此模块之前打开它，则会从处理后的点到圆弧的开头绘制一条附加线段。

5. 要以两种或多种颜色或多种线条粗细创建绘图，请使用 CALL NPERA (N) 运算符，其中 N 可以取值 0、1、2、3。该操作员不会打开笔本身，而只会记住接下来应该使用哪支笔。主笔尖被认为是笔尖编号 0；如果程序中没有换笔操作符，它将执行绘图。

已经删除的几个子程序允许您绘制各种图像；必要的计算、逻辑动作、一两个子程序可以用Fortran自行编写。曲线代表一系列小线段； LINX模型可以循环工作。

一般来说，程序不应长于60-100条语句，它应包括外观——应安装什么笔、绘图的预期尺寸、笔的初始位置（但对应于坐标系的原点）。

作为一个例子，这是一个简单绘图的程序（当然，这样的绘图不适合比赛）：

DIMENSION X (1Ø), Y (1Ø)
CALL SBROS
DO 1 K=1,9
CALL LINX (X (K), Y (K))
CALL PERO
CALL VP
DATA X/2Ø., 1Ø., 1Ø., 5Ø., 5Ø., 4Ø., 2Ø., 3Ø., 3Ø./, Y/36., 26, 8., 26., 36., 36., 26., 8./
CALL OTREZ (3Ø., 26, 5Ø., 26.)
CALL NPERA (1)
CALL OKR (2Ø., 26., 5.)
CALL LINX (15., 8.)
CALL PERO
CALL OKR 1(2Ø., 7., 5., 18Ø., —18Ø.)
CALL LINX (25., 8.)
CALL VP
CALL STP
END

而且。对于 EC 系列机器，必须将零划掉。
