---
id: 1973-4-kogan-veroyatnostnyie-zadachi-9f84f6bc
issue: kvant_1973_4
year: 1973
number: "4"
title: Probabilistic problems
authors:
  - Коган Б. Ю.
rubric: raznoe
page_first: 61
page_last: 61
page_labels: "59"
tag: YCRV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1f2889a364730afb1c7770752ea2e14923115b472f727d68fc09fc3feba11aa1
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/17_kogan-veroyatnostnyie-zadachi-9f84f6bc.md
source_content_sha256: 9ee1959fc5c95e1de2722bb0d9c447862d8b5cfb40dba2e6a5191b7e20aed042
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

Task 7. Do the digits of a three-digit or four-digit prime number form an arithmetic progression with a positive difference? If modum, but find all the numbers too.

Solution. Suppose that the digits of a number form an arithmetic progression.

For a three-digit number, the sum of the digit $x, x+d, x+2d$ is equal to $S = x + (x+d) + (x+2d) = 3x + 3d$ and is divisible by 3, that is, the number formed by these digits is divisible by 3 and cannot be prime.

For a four-digit number, the sum of the digit $x, x+d, x+2d, x+3d$ is equal to
$$x + x + d + x + 2d + x + 3d = 2(2x + 3d).$$

$x$ cannot be equal to 3, since then we will get a number divisible by 3. Since $x + 3d$ is a digit of a number, then $x + 3d \leqslant 9$ and $d$ can be equal to 2 or 1.

Let $d = 2$. Then $x \leqslant 3$; $x = 3$ is not suitable; $x = 2$ is also not suitable, since the result is an even number; with $x = 1$ we get the composite number 1357.

Let $d = 1$. Considering the numbers 1234, 2345,..., 6789, we find among them one prime number 4567.

Emphasizing
1. The sum of three numbers forming a geometric progression is 26. If we add the corresponding 1, 6 and 3 to these numbers, we get three numbers forming an arithmetic progression. Find the original numbers.
2. Prove that in an arithmetic progression between each two consecutive terms it is possible to place $k$ numbers such that the entire sequence forms an arithmetic progression.
3. Can the numbers $\sqrt{3}, 2$ and $\sqrt{8}$ be members of an arithmetic progression?
4. Find the sum of the first $n$ terms of the sequence
   7, 77, 777, ...
5. Calculate Sum
   $$1^2 - 2^2 + 3^2 - 4^2 + \dots + (-1)^{m-1} m^2.$$
6. For what $x$ do the numbers $\lg 2, \lg (2^x - 1)$ and $\lg (2^x + 3)$, taken in the indicated order, form an arithmetic progression?

Problem probability

1. The first box contains 50 white balls, and the second box contains 10 white and 10 black balls. Someone takes one ball from any box. What is the probability that the ball he takes will be white? While solving this problem, the student said: “Since there are 60 white balls and 10 black balls, then the required probability is 6/7.” Is this true?

2. (Pascal's problem). Two equally skilled players play a game with no outcome. They made equal bets and the conditions were that the one with the equal number of 10 games won would receive all the money. The game was turned over at 9:8 and could not be continued. How should they divide the money?

3. It is known about the neokot family that there are two children, one of them is a boy. What is more likely: that the second child is a boy or a girl?

4. There is an unlimited number of balls: one with number 1, another with number 2, the third with number 3, etc. Players $A$ and $B$ take one ball at a time and look at their numbers. The winner is the one who gets the ball with the lower number.

Let's see what the chances of winning are for player $A$. Suppose he subtracted ball number $k$. Since there is a finite number of numbers less than $k$, and an infinite number of numbers greater than $k$, then the player $A$’s winning is much more likely than his loss. But since this same reasoning can be proven with respect to player $B$, we come to the conclusion that each player has a significant advantage over the other. Why did this happen?

B. Yu. Kozan
