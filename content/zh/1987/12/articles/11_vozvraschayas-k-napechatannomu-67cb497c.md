---
id: 1987-12-vozvraschayas-k-napechatannomu-67cb497c
issue: kvant_1987_12
year: 1987
number: "12"
title: 返回打印
rubric: smes
page_first: 44
page_last: 44
page_labels: "42"
tag: TB2U
lang: zh
source: kvant_digital
extraction: vision
content_sha256: dd3b02c64c4a554a25caee6e118177caf3227a0df2e0cc53bb5d5e0da651fcb6
prompt_sha256: draft-1
translated_from: content/ru/1987/12/articles/11_vozvraschayas-k-napechatannomu-67cb497c.md
source_content_sha256: 67fa16ebe7ef1f3c2612077dfde479ae206b4f2efc5c665d94c93a2bfe5bf085
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

这是名称参数
...
返回α
结尾
这里“name”是函数的名称，“parameters”是操作数参数的列表（可能为空），α是一个表达式。

让我们举例说明在绘制花瓣为直角三角形、边等于 A 和 B (图 4) 的花朵时如何使用程序员创建的函数。首先，我们创建一个程序来绘制茎，组织四个花瓣的绘制，并将海龟返回到其原始位置：

这是一朵花:A:B
（*画史蒂夫*）
向前抽 3 * ：向左 65
向前 2 * :5 向左 65
（*画一朵花*）
重复 4 花瓣 :A :B 右 90
（*返回起始位置*）
不要向左画：65 BACK 2 *：A
右 65 后 3 * :A
结尾
在这里和将来我们将使用括号“(*”和“*”来写注释 - 记录在程序中，但不被机器消息处理。花瓣绘制游戏以平局结束，然后两个部分得分相等。如果理解所有部分都玩了相同数量的游戏，部分 - 彼此都玩过，则该陈述和解决方案将是正确的。（如果没有这个，解决方案的第一步是进入系统评分，其中1为获胜，0为0平局为-1，负为-1，无法正确判断初始分数，从下面的例子可以看出：四局A、B、B、G由Г进行，B和Г没有进行比赛，其余比赛均以平局结束。）

回到方向

正如许多读者所知，M1047题的表述需要澄清（该题的解答已发表于«Kvant»第10期）。问题需要证明，如果在都灵进行的比赛中有超过 3/4 的比赛以平局告终，那么其余两个部分的得分相同。如果理解所有部分都玩了相同数量的游戏，并且部分地互相玩游戏，则该陈述和解决方案将是正确的。 （如果没有这个，解决方案的第一步 - 过渡到胜1分，平0分，负1分的计分系统 - 就无法正确判断初始分数，从下面的例子可以看出：四个部分A、B、B、G由Г进行，B和Г没有相互比赛，其余比赛以平局结束。）
