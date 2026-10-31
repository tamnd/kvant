---
id: 2016-4-zaslavskiy-futbolnyie-turniryi-i-arifmeticheskie-progressii-d4a5b32e
issue: kvant_2016_4
year: 2016
number: "4"
title: Football tournaments and arithmetic progressions
authors:
  - Заславский А. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 23
page_labels: 20-21
tag: 5SZ3
lang: en
source: kvant_digital
extraction: native
content_sha256: 3e75ab8b1b02cf23093f529b337c1584778eaef97914cd7cde4a50ff6ab6960b
prompt_sha256: draft-1
translated_from: content/ru/2016/04/articles/02_zaslavskiy-futbolnyie-turniryi-i-arifmeticheskie-progressii-d4a5b32e.md
source_content_sha256: 720ec65ff540fae60adf0e6158945dae63f2c22438f5c82152ba5cf80a923599
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

KVANT 2016/№4

Football tournaments and arithmetic progressions

In 2012, at the LXXV Moscow Mathematical Olympiad, the following problem was proposed. 75 teams participated in the one-round football tournament (win – 3 points, draw – 1, loss – 0). What is the smallest possible points gap between the first and last teams if no two teams are tied in points? Since the minimum gap between adjacent teams is one point, it is obvious that the gap between the first and last teams cannot be less than 74 points. However, it is quite difficult to understand whether this estimate is achievable. To find out, it's natural to start by looking at tournaments with a small number of participants. Having gone through all the tournaments with 2 or 3 participants, it is easy to make sure that the ones you are looking for are not among them. But it is possible to build such a tournament for 4 teams (Table 1).

Table 1

Attempts are also successful for the next few values ​​of the number of commands n. Therefore, the assumption arises that corresponding tournaments exist for all n > 3. This is indeed so; more precisely, the following statement is true. For any $n \ge 4$ there is a round-robin tournament of n teams, in which teams score n – 2, n – 1, n, …, 2n – 3 points. Let's prove it by induction. For n = 4, we have already built the required tournament. Let's assume that we have such a tournament for n teams, and we will show how to add one new team to it. Let's order the old teams in descending order of points and let the new team win against the first, lose against the second and third, win against the fourth, lose against the fifth and sixth, etc. (with a period of 3) until she has one, two or three teams left to play (depending on the remainder of n when divided by 3). In the first case, the new team plays with the last one in a draw. In the second, he plays a draw with the penultimate one and loses to the last one, in the third, he plays a draw with the last one, loses to the penultimate one and wins against the third one from the bottom. By direct calculation we are convinced that in all three cases we get the distribution of points we need.

⟦column⟧

natural d points scored by teams can form an arithmetic progression with the difference d? For completeness, we can let d be 0, in which case the desired tournament obviously exists (for example, if all games end in a draw). For all n, the case d = 3 is possible (if the first team wins against everyone, the second - against everyone except the first, etc.). It is also clear that the difference cannot be greater than 3 (why?). Thus, what remains for us next is to study the case d = 2. Let's start again with small values ​​of n. For n = 2 and n = 3 there are no required tournaments, for n = 4 there are (Table 2).

Table 2

But with n = 5 it is impossible to build a tournament. Let us prove that this is truly impossible. If the points scored form an arithmetic progression with a difference of 2, then their sum is divided by 5. Since the total number of games in a five-team tournament is ten, we obtain that the sum of the points scored is 30 if all games ended in a victory for one of the teams, and each draw reduces this sum by 1. Therefore, 0, 5 or 10 games must end in a draw. If there are no draws, then the number of points for each team is a multiple of 3 and a difference of 2 is impossible, and with 10 draws, all teams score 4 points. Consider the case of 5 draws. Then the total amount is 25, i.e. teams must score 9, 7, 5, 3 and 1 point. But there is only one way to score 9, 7, 5 and 1 points in four games: respectively, three wins and one loss; two wins, one draw and one loss; one win, two draws and one loss; one draw and three defeats. Since the total number of wins must equal the total number of defeats, the remaining team must have equal wins and losses, which is impossible with 3 points. Continuing to consider small values ​​of n, we are convinced that for n = 6, n = 7 and n = 8 the required tournaments exist (Tables 3, 4, 5).

Table 3

Exercise 1: Check it out.

Now let's generalize the problem and pose the following question. M2419. There are n teams participating in a one-round football tournament. A team receives 3 points for a win, 1 point for a draw, and 0 points for a loss. At what

After experimenting with a few more values ​​of n, we can formulate the following hypothesis. 1) For all even n = 2m, $m \ge 2$, there is a tournament in which teams score m – 1, m + 1, m + 3, …, 5m – 3 points.

⟦folio 21⟧

PROBLEM WORKER

"QUANTA"

Table 4

Table 5

Table 7

⟦column⟧

The operation of adding two commands can be performed for any odd n. Let all the old teams, except the last two, score 3 points against the new ones, and the last two – one each, and if the remainder of dividing n by 3 is 0 or 2, then both of these teams score their points against one of the new teams, and if 1, then against different teams. Then you can distribute the points between the new teams so that one of them will be in first place, and the other will be in third place.

Exercise 3. Prove it.

2) For all odd $n = 2m + 1, m \ge 3$, there is a tournament in which teams score m – 1, m + + 1, m + 3, …, 5m – 1 points. Let us prove that this is indeed the case. Let's start with the even case. Since we have already built tournaments for 4, 6 and 8 teams, it is enough to show how to add six new teams to a 2k team tournament. Let each of the top k old teams lose to the first new team and win against the other five new ones, and let each of the bottom k old teams, on the contrary, win against the first new team and lose to the other five new ones. New teams play among themselves, as in the example for 6 teams. It is not difficult to verify that the result will be the desired distribution of points.

Exercise 2. Do a check.

Let's move on to the odd case. First, we'll show you how to add two more teams to a seven-team tournament. Let the new teams play with the old ones as shown in Table 6 (on the top line are the points scored by the old teams in games with each other).

Table 6

Then the old teams have 17, 15, 13, 11, 9, 5 and 3 points, and the new teams have 19 and 4 points. If now the first new team A loses to team B, then we get the desired tournament for 9 teams. Let us now add two more teams to this tournament (Table 7). And again let the first new team C lose to the second new team D. As a result, we get the desired tournament of 11 teams.

However, since we already have tournaments for 7, 9 and 11 teams, it is easier to proceed similarly to the even case and add six more new teams to the 2k+1 team tournament. Let each of the top k old teams lose to the first new team and defeat the rest, and let each of the bottom k, on the contrary, win against the first new one and lose to the other five. Finally, let the average old team lose to the first three new ones and win against the remaining three new ones. Let the new teams play among themselves as shown in Table 8.

Table 8

As a result, we obtain the desired distribution of points. The statement has been fully proven.

Exercise 4. Make sure of this.

Now we can summarize and give a complete answer to the question posed: for d = 0 and d = 3, the required tournament exists for all n, for d = 1 - for all n, except 2 and 3, for d = 2 - for all n, except 2, 3 and 5. In conclusion, we suggest thinking about how the answer will change if, instead of football, we consider tournaments in other sports, for example volleyball, where if one of the teams wins with a score of 3:0 or 3:1, the winning and losing teams receive 3 and 0 points respectively, and with a score of 3:2 - 2 and 1. A. Zaslavsky
