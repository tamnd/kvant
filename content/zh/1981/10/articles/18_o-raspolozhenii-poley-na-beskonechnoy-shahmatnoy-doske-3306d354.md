---
id: 1981-10-o-raspolozhenii-poley-na-beskonechnoy-shahmatnoy-doske-3306d354
issue: kvant_1981_10
year: 1981
number: "10"
title: 【论无限棋盘上的棋盘排列】
rubric: raznoe
page_first: 59
page_last: 59
page_labels: "57"
tag: K4HB
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 82108d423f02b2ad0ca29ebf7c38b55bcbafd17fba62cf11e26c56e6e0dbb9d6
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/18_o-raspolozhenii-poley-na-beskonechnoy-shahmatnoy-doske-3306d354.md
source_content_sha256: 1f3c8ce12c1ff573e7916c1650c079a3c71c84bc6902546168a6334d1771c593
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

让我们从结果开始吧。输入数字 n。

程序余数（输出、输入）；
var n，总和：整数；
begin
read(n);
summa:=n mod 2+n mod 3+
+n mod 5;
writeln('SUM=', 总和)
任务 15.1。满足$\phi_0=0$、$\phi_1=1$递推关系$\phi_{n+1}=\phi_n+\phi_{n-1}$的自然数称为斐波那契数：1, 1, 2, 3, 5, 8, 13, ...
*) 如需更多详细信息，请参阅 N. N. Vorobyov“斐波那契数列”（系列“流行数学讲座”，M.，“Nauka”，1978 年）或 «Kvant»，1979 年，第 5 期，第 17 页。 53.

编写一个程序，根据两个相邻数字$\phi_1$和$\phi_2$的值，得到以下三个数字——$\phi_3$、$\phi_4$、$\phi_5$。打印所有五个数字——两个原始数字和三个结果。输出数字$\phi_1$和$\phi_2$。

如果原来的数字是8和13，程序会打印什么？
任务 15.2。 图 8 显示了活塞的横截面 - 具有三个环形凹槽和端表面上的最终凹槽的气缸区域。活塞尺寸如图所示。编写一个程序来计算这部分的体积。圆柱体的体积可通过公式 $v_u=\pi R^2 h$ 求出，圆锥体的体积可通过公式 $v_k=\frac{1}{3}\pi R^2 h$ 求出，其中 $R$ 是底面半径，$h$ 是圆柱体和圆锥体的高度。提供值$R$和$h$。

字典
程序-程序
开始-开始
端对端
const - 常量
var - 变量
类型-类型
布尔 - 逻辑
整数 - 整体
char - 字母（符号）
真实-真实
假-假
真-真
AND - 和
或 - 或
不 - 不

N·尤纳曼

我们的封面

在无限棋盘上，“骑士 2-3”可以通过 $n$ 步（$n=1, 2, 3, \dots$）从给定的“中心”方格 $O$ 到达，这些方格是如何定位的？ （“骑士2-3”在一个方向上的2个方格上使用字母$\Gamma$移动，在垂直方向上移动3个。）我们将这位骑士从$O$到$X$的最小移动次数称为从$O$到$X$的距离。在封面的第一页上，距离中心 $O$ $n$ 的字段涂有不同的颜色（参见图）。

您可以通过在一大张格子纸上依次标记马 2-3 可以在 1 步、然后 2 步、3 步等中从中心方格到达的单元格来检查封面上的图。您将确信，对于马 2-3 来说，图片比通常的马 1-2 复杂得多（此类马的“距离”在本期发表的 D. Cohen 的文章中描述）：仅朝向村庄的移动是“内部漏洞”的填补，并且可以追踪在下一步移动中保留的一般模式。尝试回答这些问题。对于$n \geq 8$（对于$n \leq 7$，您可以制作一个表格，使用封面，对于$n \geq 8$，您可以写一个通用公式），有多少个单元格距离$O$为$n$？单元格 (0;0) 和 (x;y) 之间的距离（在“cond 2-3”度量中）是多少（对于$x \leq 12$和$y \leq 12$，这可以从封面中找到）？
