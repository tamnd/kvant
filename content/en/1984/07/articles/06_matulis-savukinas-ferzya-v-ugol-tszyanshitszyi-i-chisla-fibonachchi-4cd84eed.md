---
id: 1984-7-matulis-savukinas-ferzya-v-ugol-tszyanshitszyi-i-chisla-fibonachchi-4cd84eed
issue: kvant_1984_7
year: 1984
number: "7"
title: “Queen to the corner”, “jianshizi” and Fibonacci numbers
authors:
  - Матулис А. Ю.
  - Савукинас А. Ю.
rubric: osnovnye-stati
rubric_sub: Основные статьи
page_first: 20
page_last: 23
page_labels: 18, 21
tag: 9F80
lang: en
source: kvant_digital
extraction: vision
content_sha256: 408eea7d93e23459609db44d1e8ca0e5a32077a8dc13c6219b4320bcc5682b1d
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/06_matulis-savukinas-ferzya-v-ugol-tszyanshitszyi-i-chisla-fibonachchi-4cd84eed.md
source_content_sha256: 46af658af070043cb2e3a12f4973c92c21d6c6c1b3cfb832556ce15b0f87ad35
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

“Queen to the corner”, “Jianshits” and Fibonacci numbers

A. Y. MATULIS, A. Y. SAVUKINAS

We want to introduce you to another, rather unexpected, application of Fibonacci numbers, which are described in the article by I. M. Yaglom on p. 15-18 of this issue of the magazine.

We will see that Fibonacci numbers help build theories on the ancient Chinese game Jianshizi and the related game Queen to Corner. This game has already been devoted to an article by I.M. Yaglom («Kvant», 1971, No. 2, p. 4) and A. Orlov («Kvant», 1977, No. 3, p. 41).

Here we outline a slightly different approach to solving the same problem.

“Jianshitsy” and “Queen in the corner”

The conditions of the ancient game “Jianshitsi” (selected stones) are as follows. There are two piles of stones (or some other objects, such as matches). Two players take turns choosing stones from these piles, and in one move you can either take either the number of stones from one (whichever corner) pile, or equally from both piles at once. The one who takes the last stone wins.

We need to find the right win-win game.

Let there be a stones in one pile and b stones in the second. Let us match the numbers (a, b) to the square of the (infinite!) chessboard shown at figure 1 and place the queen in the square (a, b).

It is easy to see that each move in the game “Jianshitsi” corresponds to a certain move of the queen: if the player takes k stones from the first pile, then the queen moves k squares to the left; if the player takes l stones from the second pile, the queen will move l cells down; if he takes m stones from each pile, the queen will move m squares diagonally to the left and down.

So, together with the game “Jianshitsi”, we can consider the game “Queen in the corner” with the following rule: there is a queen on an infinite chessboard. Two players take turns moving the queen so that it approaches the corner square (0, 0), that is, in one move it is possible to move the queen any number of cells either to the left, or down, or diagonally to the left and down. The one who brings the queen to the field (0, 0) wins.

figure 1 shows the course of the game starting in cell (12, 14), where red arrows indicate the moves of the first player, and blue arrows indicate the moves of the second; The first player won here.

It is clear that any game of the game “Jianshitsi” corresponds to a certain game of the game “Queen to the corner”, and a game of the game “Queen to the corner” corresponds to a game of “Jianshitsi”. Therefore, in the future we will only talk about the game “Queen to corner”.

Losing fields

figure 2 shows an infinite chessboard, on which some squares are marked with a “—” sign. We will also call these fields losing fields. It is not difficult to see that if one of the players places his queen on the displaced square with each move, then he will win.

In fact, it is impossible to move from any displaced square by moving the queen to a displaced square. For example, from any undisplaced field you can move to a displaced field in one move. Therefore, by placing your queen on a displaced square, you force your opponent to retire from the displaced square. On your next move, you can step again onto the displaced square (closer to the (0, 0) field, and so on. Eventually you will step onto the displaced square (0, 0) and win.

You can specify the rules by which offset fields are consistently obtained. First the field (0, 0) is removed. This field can be reached from any vertical field a=0, horizontal b=0 and diagonal a=b. The nearest unexamined fields are fields (1, 2) and (2, 1). One of these fields can be reached from any vertical fields a=1, a=2, horizontal

⟦folio 21⟧

Main theorem

Now we can forget all the considerations that led us to the written expressions for the losing fields ($a_n, b_n$), and immediately form the following main theorem.

Theorem 1. Let $u = \frac{1+\sqrt{5}}{2}$, $v = u^2 = u + 1 = \frac{3+\sqrt{5}}{2}$. The field $(a, b)$, where $b > a$, is losing if and only if there is a natural number $n$ such that $a = [nu], b = [nv]$. If such a natural $n$ does not exist, then the position is winning.

Proof. Consider the sequence of points

$$(a_1, b_1), (a_2, b_2), \dots, (a_n, b_n), \dots,$$

where $a_n = [nu], b_n = [nv]$, and prove that this sequence satisfies properties 1 and 2 (see p. 19). Let's start with property 1.

First, let's make sure that all numbers $a_1, b_1, a_2, b_2, \dots$ are distinct. The numbers $a_i = [iu]$ are different, as are $u > 1$. For the same reason ($v > 1$) the numbers $b_j = [jv]$ are different. Let's assume that some two of the numbers $a_j$ and $b_j$ are the same. This means $[iu] = [jv] = k$. Therefore, $iu = k + \delta$, where $0 < \delta_1 < 1$, $jv = k + \delta_2$, where $0 < \delta_2 < 1$. Dividing the first equality by $u$, the second by $v$, and then adding the resulting equalities, we arrive at the equality

$$i + j = \frac{k}{u} + \frac{k}{v} + \frac{\delta_1}{u} + \frac{\delta_2}{v} = k + \frac{\delta_1}{u} + \frac{\delta_2}{v},$$

from which it follows that

$$0 < i + j - k = \frac{\delta_1}{u} + \frac{\delta_2}{v} < \frac{1}{u} + \frac{1}{v} = 1,$$

which is impossible, since the number $i + j - k$ is an integer.

Now we will prove that every natural number occurs in the sequence $a_1, b_1, a_2, b_2, \dots, a_n, b_n, \dots$.

Let $N$ be an arbitrary natural number.

There are exactly $\left[ \frac{N}{u} \right]$ numbers $a_i = [iu]$, less than $N$. (These are numbers with numbers $i = 1, 2, \dots, \left[ \frac{N}{u} \right]$.) Exactly $\left[ \frac{N}{v} \right]$ of numbers $b_j = [jv]$, less than $N$. (numbers with numbers $j = 1, 2, \dots, \left[ \frac{N}{v} \right]$.) In total there are $a_i$ and $b_j$, less than $N$, there are $\left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right]$, and since $\frac{N}{u}$ and $\frac{N}{v}$ are not integers, $\frac{N}{u} - 1 + \frac{N}{v} < \left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right] < \frac{N}{u} + \frac{N}{v}$, that is

$$N - 2 < \left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right] < N.$$

Thus, $\left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right] = N - 1$. But this means that there are exactly as many numbers of the form $a_i$ and $b_j$, less than $N$, as there are natural numbers, less than $N$. Since the numbers $a_i$ and $b_j$ are all distinct, property 1 of the sequence $(a_1 b_1), (a_2 b_2), \dots, (a_n b_n)$, ... is proven.

Property 2 can be easily proven:

$$b_n - a_n = [vn] - [un] = [(u + 1)n] - [vn] - [un] = [nu] + n - [un] = n.$$

Thus, the main theorem is completely proven.

Fibonacci numbers appear

According to the main theorem, to determine the losing pair with number $n$, one must multiply $n$ by an irrational number given as an infinite decimal fraction. It is possible that such multiplication is not clear to you, especially if you do not have an adding machine. How to determine losing pairs $(a_n, b_n)$ usually only by operations on natural numbers?

The following property of losing pairs can serve this purpose:

3. If $(a_n, b_n)$ is an arbitrary pair, then the pairs $(b_n - 1, a_n + b_n - 1)$ and $(b_n + 1, a_n + b_n + 2)$ are also arbitrary.

Moreover, based on the initial field $(0, 0)$ or the first field $(1, 2)$, we can construct, using property 3, all losing pairs.

Let us outline the proof of property 3.

Exercise 2. Prove that for losing pairs $(a_n, b_n)$ and $(a_{n+1}, b_{n+1}): 2 \leq b_{n+1} - b_n \leq 3$, and $1 \leq a_{n+1} - a_n \leq 2$.

From the results of Exercise 2 it follows that the numbers $b_n - 1$ and $b_n + 1$ are not large numbers of losing pairs. By property 1, there exist $k$ and $l$ such that $a_k = b_n - 1$, $a_l = b_n + 1$. Let's see what $k$ and $l$ are equal to.

By property 2, the number of any pair is equal between the larger and smaller of the numbers of this pair.

On the other hand, from property 1 it follows that the number of any canceled pair $(a_k, b_k)$ and its equality is less than the number $a_k$ and the number of all non-zero pairs $b_l < a_k$. At $a_l = b_n - 1$ the number of numbers $b_l$, less than the number $a_l$, is $n - 1$. This means $k = b_n - 1 - (n - 1) = a_n$. Therefore, the pair $(b_n - 1, b + a_n - 1)$ is marked.

Exercise 3. Prove that the pair $(b_n + 1, a_n + b_n + 2)$ is cancelable for every cancelable pair $(a_n, b_n)$.

Exercise 4. Prove that any excellent pair $(a_n, b_n)$ can be obtained from the pair $(0, 0)$ or the pair $(1, 2)$ by sequentially applying several operations described by Property 3.

(For the end see p. 29)
