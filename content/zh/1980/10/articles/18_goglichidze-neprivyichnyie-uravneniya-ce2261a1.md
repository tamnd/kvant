---
id: 1980-10-goglichidze-neprivyichnyie-uravneniya-ce2261a1
issue: kvant_1980_10
year: 1980
number: "10"
title: 不寻常的方程
authors:
  - Гогличидзе Н.
rubric: smes
page_first: 63
page_last: 63
page_labels: "61"
tag: 2EZV
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 15274ad2219e78eba5ce61396b4acb84e2c0a4b481d857f060a3a0d904405868
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/18_goglichidze-neprivyichnyie-uravneniya-ce2261a1.md
source_content_sha256: db0a60994d25300db1efac0ea69ffb635fc0122bf5538d6456cb35f007208c2d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 61⟧

该空间中任意两个（不同）单元格之间的距离为 1 或 2。

在 图 2 上，该空间中可用的半径为 1 的球显示为绿色。整个棋盘是一个半径为 2、中心位于任意单元格的球（顺便说一下，它也可以被认为是任意半径$r > 2!$的球）。

示例 2. 让我们定义实数之间的距离 $x, y$ 如下 (图 3)：

$$\rho(x, y) = \begin{cases} \sqrt{x^2 + y^2}, & \text{ если } x \neq y, \\ 0, & \text{ если } x = y. \end{cases}$$

很容易检查是否再次满足所有距离轴。在这个空间中有一个半径为 0 的球 $r$ 是一个段 $[-r; r]$。为了 $a \neq 0$ 带中心的球 $a$ 半径 $r > |a|$ 构建如下所示 图 4. 因此对于 $a \neq 0$ 带中心的球 $a$ 半径 $r > a\sqrt{2}$ 其内部有一个中心（图 5)、与 $r = |a|\sqrt{2}$ 中心位于球的边界上（图 6），在 $|a| < r < |a|\sqrt{2}$ 中心位于球的外侧（图 7).在 $r = |a|$ 球由两个点组成：0 和 $a$;最后，在 $0 < r < |a|$ 球仅由点本身组成 $a$ （所以每个点 $a \neq 0$ “单独”是一个球）。在这个空间中有一个“增加”的球序列

$$K_1 \subset K_2 \subset K_3 \subset \dots$$

($K_{n+1} \neq K_n$) 降序排列

$$|O_2B| < |O_1A|$$

$$r_1 > r_2 > r_3 > \dots$$

M·阿什卡洛娃

不寻常的方程

让我们将数字集$A$与数字$b$的和定义为$a + b$形式的数字集，其中$a \in A$。集合$A - b$、$A \cdot b$、$A:b$ 的定义类似。例如：

$$\{1, 5, 10\} + 3 = \{4, 8, 13\},$$

$$\{2, 4, 6, 8, 10, \dots\}: 2 = \{1, 2, 3, 4, 5, \dots\}.$$

现在我们可以编写“带有集合的方程”，其中变量的“寻求”值是数值集。例如，很容易看出一组数字是方程的根

$$X + 2 = X,$$

(1)

数字集 $2^p(p \in \mathbb{Z})$ 是方程的根

$$X \cdot 2 = X.$$

顺便说一句，这些“单变量一次方程”中的每一个都有无限多个根。式(1)等于式$X - 2 = X$的盐，式(2)等于式$X:2 = X$。

现在让我们定义一个数字集的平方如下：

$$A^2 = \{a^2 | a \in A\}.$$

现在您可以编写并求解“二次”方程。方程

$$X^2 = X$$

再次有无限多个根（集合 $\{..., \sqrt{2}, \sqrt{2}, 2, 4, 16, \dots\}$ 是其根之一），并且方程

$$X^2 + 1 = X$$

无根*）。 （这可以很容易地推出，如果$A$是它的根，$a \in A$，那么$\sqrt{a-1} \in A$。）（发言者说她不知道$a, b, c$方程$aX^2 + c = X \cdot b$有根。）

H·戈利齐泽

*) 空集除外。 （编者注）
