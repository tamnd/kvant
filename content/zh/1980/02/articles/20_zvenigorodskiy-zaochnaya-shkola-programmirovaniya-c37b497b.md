---
id: 1980-2-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-c37b497b
issue: kvant_1980_2
year: 1980
number: "2"
title: 函授编程学院
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 56
page_labels: 53-54
tag: V4AC
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 2a8ef8bc011c2be24774740e6387962cbea660349dc606b679efefee136b49a8
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/20_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-c37b497b.md
source_content_sha256: 704ad5af7b1d51101a8bc860e7fd70823976bc0192acca7be3a34da5ec9b5293
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

函授编程学院

第 6 课：Rapier 上程序的描述和调用

在本课中，我们将继续学习第五课（«Kvant»，第 1 课）中开始的教育和生产编程语言 Rapier。

Rapier 中的过程描述由下图定义：

标题后面是用分号分隔的语句。

以下是 Rapier 程序描述的示例：

PERC 选择 A B； A+B->C； A*B->D；
IF C>D THEN C->D ELSE D->C ALL;
肯塔基州委员会；

在 Rapier 中调用过程有两种方法。使用第一种方法，您应该将过程的名称写为下一个表示形式，并在其后面加上大括号。如果过程有参数，那么它们的值会在这些括号内以逗号分隔列出，如 Robik 中所示，例如：

选择(10,X+5);

如果没有参数，这个调用方法中仍然需要括号：

重置 （ ）;

如果一个过程最多有一个参数，则可以通过第二种方式调用它：在过程名称前面放置一个点。参数的值（如果有）在点之前指示：

重置; 5. 圆圈；

描述以单词 PERC（而不是 Robik 中的单词 REMEMBER PROCEDURE）开始，后面是过程的名称。如果需要，然后列出参数名称。它们彼此之间用空格隔开；这里不需要 Robik 中使用的括号和逗号。

其后可能是一个箭头 =>，其后指示另一个名称 - 所谓的结果名称。在本课中，我们将了解不使用结果名称的过程。因此，我们将这个构造的分析推迟到下一课。

PROC 一词、过程名称、参数和结果名称组成了所谓的过程标头。后

Rapier提供了大量的标准程序，可以在任何程序中调用。其中特别包括 PRINT 过程，它可以具有任意数量的参数。使用此过程的结果是，所有参数的值将打印在一个新行上，彼此靠近（就像 Robik 语言中的 PRINT 指令一样）。 A. Salikhova 和 N. Sokolova 在杂志上一期的文章中描述的 Shpag 图形系统的所有程序也是标准的。

让我们看一些例子：

1°。假设我们需要在 Rapier 上编写一个程序，使用

⟦folio 54⟧

基于语音系统的程序，这是机器人来说明：

代码 211500000055 SMOG 61M5 第 7 页
日期 06.22.79 63 时间 19.49.31

当然，这可以单独使用射线和引线来完成。然而，在这种情况下，程序将变得相当大。如果我们用 图 替换相同的图形多次重复，它可以显着缩短 - 一个矩形。因此，描述一次 DIRECT 过程就足够了，然后绘制任何所需的矩形。下面的程序有四个参数：X、Y、B和D，X和Y是矩形的左下角坐标，B是矩形的高度，D是矩形的长度：

PERC 直接 X Y IN D；
P(X;Y); L(X+D,Y)； L(X+D；Y+B)；
L(X,Y+B)； L(X,Y)；肯塔基州委员会；

现在执行图的程序可以写得非常简单：
P(50.50)；直接(10,10,30,30);
直接(20,15,5,10);直接(23,23,4,4);
直接(15,30,5,7);直接(28,30,5,7);
直接(17,31,3,3);直接(30,31,3,3);
。结尾;

2°。下一个任务是用垂直和水平方向步长为 5 毫米的矩形网格填充 100 x 100 毫米的尺寸（例如，这样的网格可以用作坐标网格）。在这里使用循环很方便：
P(100,100); 5—>A；当 A=<100::
P(A,0)； L(A,100)； P(0,A); L(100,A),
A+5—>全部； 。结尾;

3°。使用循环的另一个示例是打印乘法表：
2—>A; 2—>B;
打印（'乘法表'），
当 A=<10:: 当 B=<10::
