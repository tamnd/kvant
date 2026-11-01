---
id: 1983-3-gik-figuryi-v-bezopasnosti-816454dd
issue: kvant_1983_3
year: 1983
number: "3"
title: 数字是安全的
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 67
page_last: 67
tag: ZZBY
lang: zh
source: kvant_digital
extraction: vision
content_sha256: cfde0de72b76528fb15dae22c65fc623f458064b6ea08a1ad492f0a981aa4a1b
prompt_sha256: draft-1
translated_from: content/ru/1983/03/articles/02_gik-figuryi-v-bezopasnosti-816454dd.md
source_content_sha256: cb9415ee92c690ea9c91fa19b589d32a467359d97e414185be700fff9a1fac1a
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

安全数据

One of the most popular combinators of problems on a chessboard is to place on it the greatest number of certain pieces that do not threaten each other, as well as counting the number of indicated arrangements.这两个问题不仅适用于一般的 8x8 棋盘，也适用于任何大小为 nxn 的方棋盘。其中一些问题的解决方案是众所周知的，另一些则非常复杂且尚未得到解决。

皇后区。在一块公共棋盘上，您可以放置​​ 8 个皇后，这样它们就不会互相威胁。排列数为92种，其中12种为基本排列（我在«Kvant»，1983年第1期中谈到过这一点）。

Obviously, there are n×n more than n queens on the board that do not threaten each other, so we can arrange as much as possible. It turns out that for all n except n=2 and n=3, the maximum number of queens that is safe is equal to n (on a 2x2 board there is one queen, on a 3x3 board there are two queens).这个事实的证明并不十分简单；它可以在各种数学书籍中找到。 The numbers of corresponding solutions are known only for n≤14, and computers were used to find them.

烦恼。 The maximum number of rooks that do not threaten each other is also n, and the number of formations is n!=1·2···n.

大象。 n×n 棋盘上互不威胁的象的最大数量为 2n-2 (n>1)。主教可以沿着整个第一条水平线和最后一条水平线放置，不包括角点。

总共有 2^n 种排列。

康妮。 Obviously, placing 32 knights on one white or one black square on a common board, we will get two placements of knights that do not threaten each other. Let's make sure that it is possible to arrange more than sweets that have these properties, and that it has all two options. Let the knights be placed in the required manner on the board. Let's take advantage of the fact that on an 8x8 board there is a closed knight route across the entire board. Since in this route, after each square with a knight from our arrangement there must be a free square, knights cannot occupy more than half of the board! If the millstone of the board is filled with knights, then these 32 knights must follow one through the chosen route, i.e., they are located on fields of the same color.

类似地，证明了对于偶数n，棋盘上最多可以放置n^2/2个互不威胁的马，对于奇数n-(n^2+1)/2个马。在第一种情况下，可以有两种一体式阵型，而在第二种情况下，只有一种（骑士站在棋盘上颜色较大的方格上）。

国王。让我们以 n=2k 的形式表示数字 n，或者相应地，n=2k-1。可以证明，在n×n的棋盘上，不存在相互威胁，即不相邻的k^2个王较少。在一块公共棋盘上，16 个国王（k=4）按要求的方式排列成 287571 种方式。例如，可以将国王放置在偶数或奇数等级的所有单连方块上。棋盘上排列数 n×n 的一般公式是未知的。

棋子。让我们再次以 n=2k 或 n=2k-1 的形式表示数字 n。然后在 n×n 板上你可以放置 nk 个棋子，其中任何一个都不会攻击另一个。您可以使用 pawn 来填充水平方向（穿过一个）或垂直方向（穿过一个），但也可能有其他排列。尝试自己找出允许的排列数量（至少在 8×8 的棋盘上）。

下面的人物排列由 G. Duden 创作，是独一无二的。

棋盘上不互相威胁的皇后、车和象的最大数量同时减少。棋盘上还有21个骑士（他们不会互相攻击），并且在棋盘的空闲黑色方块上你还可以放置8个国王，它们不会互相攻击。

竞争问题

在该杂志的马特洛夫斯基号中，按照传统，我们提供了两道由已婚国际象棋作曲家编写的问题。奇怪的是，这两种立场的作者在上学时都将其合理化。

5. （K. Saghatelyan，1957）。 3步即可将死。

6. （L.维辛斯卡娅，1964）。 2步即可将死。

发送答案的截止日期是1983年5月25日（信封上注明：“国际象棋比赛«Kvant»，任务5、6”）。
