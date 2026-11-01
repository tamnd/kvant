---
id: 1987-1-savin-na-krugi-svoi-0ddfc2bb
issue: kvant_1987_1
year: 1987
number: "1"
title: Back to square one
authors:
  - Савин А. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 26
page_last: 28
page_labels: 24-26
tag: D9A9
lang: en
source: kvant_digital
extraction: vision
content_sha256: cf35a44ba7cc71d0f6923c939ed4114515aee6052c192596507b8f9261f1fcc6
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/07_savin-na-krugi-svoi-0ddfc2bb.md
source_content_sha256: 98c16695b69b2e67634b13c24a2642f9a4d14b760d995e37959b3321faf75703
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Back to normal
What will happen if...

Candidate of Physical and Mathematical Sciences
A. P. SAVIN

As a child, I really loved the kaleidoscope.
You look into the magic tube and see a magnificent brain. A small turn - and a new pattern, another turn - and again a new and new pattern.

When I first got my hands on a Rubik's Cube, at first I was interested in just spinning it, like I had previously spun a kaleidoscope, admiring the play of colors on its facets. However, I soon became bored with the random spinning. After several hours of trying to open the “cutter” of solving the cube on my own, I took out the number «Kvant» *) and, after spending about another hour, the cube was solved.

Now I began to handle the cube more carefully so that it could be easily returned to the “assembled” position. I twisted one side once (Fig. 1), again, again and again - the cube was solved again.

What happens if you rotate two adjacent faces in turn, say, in the same direction? First-second time, first-second two, first-second three... (Fig. 2). At this time I already knew that after a few pairs of rotations the cube would “assemble” again. My fingers began to set, I lost count, but the cube still didn’t “assemble.”

Only after 105 pairs of rotations did the cube collect its colors on the faces.

But how did I know that such a moment would come? I just thought a little before this. Although the cube has many different positions, there is a finite number. If so, then it cannot end up in a new position every time; sooner or later a position will appear in which the cube has already been. Let us denote this position by the letter A, and the “assembled” position by the letter E (Fig. 3, p. 27). After a couple of rotations, the cube moves from state A to state B, then from state B to state C, etc., until it again finds itself in position A and everything begins to repeat itself again. As mathematicians say, the positions of the cube will be repeated periodically.

Let's formulate the result obtained, already abstracting from the cube - the object for which it was obtained.

If an object can be in a finite number of states and there is a certain operation that unambiguously transforms which state into a new one, then by consistently applying this operation, we obtain a periodic repeating sequence of the object’s state.

*) See «Kvant», 1983, No. 9, p. 33-36.

⟦folio 25⟧

This statement sounds like a law of nature or a mathematical theorem. In fact, that's how it is. Moreover, with this statement we can get very interesting results.

But first, I’ll discuss the law about the Rubik’s cube. Let us note one more feature of our operation: for any state of unambiguous definition, the “previous” state. Namely, you should turn in the other direction, first the second, and then the first face of the cube. Let's look at figure 4 (p. 27). Moving from position A “backwards”, starting from the first position A, after a few steps we will arrive at position E; This means that from the second position A in the same number of steps we will get to position E. Thus, between the first and second positions of the cube A we must find the position E - our own cube.

These are the thoughts that flashed through my head before I began to rotate the cube according to the described rule. Of course, the number of pairs of rotations could be very large, because the Rubik's cube has an extremely large number of elements - 43,252,003,274,489,856,000. I tried to rotate the faces in different directions - the first one clockwise, and the second one counterclockwise. In this case, the return occurs after 63 pairs of moves, and if you rotate three adjacent faces in one direction one at a time, the cycle will close after 80 turns.

Anyone who has a Rubik's cube can get acquainted with other sets of turns. Well, for those who don’t have one, take paper, a pencil, and we’ll start experimenting with numbers. Of course, it wouldn’t fit a microcalculator or a personal computer, but you can do without them.

Let's divide 136 by 11. By the way, do you know the test for divisibility by 11? No? Remember, this is useful. A number is divisible by 11 if the difference between the sum of the digits in odd places and the sum of the digits in even places is divisible by 11. In our case (1+6)-3=4, therefore, 136 is not divisible by 11.

What will happen if we start sharing a corner? Take a look at figure 5 (p. 26). It is easy to notice that the numbers after the decimal point are repeated periodically. Such a decimal fraction will be infinite and is called a periodic decimal fraction. It is written like this: 12, (36) - a repeating set of numbers is enclosed in brackets.

When dividing what other integers do periodic decimal fractions appear? Any, as long as the divisor is different from zero, and we will consider the final decimal fraction to be infinite, continuing it after the last digit with zeros. Why? To prove this, it will be very convenient for us to use the previously formulated general statement. As the object under consideration, let’s take the difference below the line. In our example it will first be 2, then 4, then 7, again 4, again 7, etc. Consider the operation we are performing

⟦folio 26⟧

with this object. First, you should add one more digit, then subtract from the resulting number the most multiple of the divisor, but not exceeding this number, write down the difference - this will be the converted number.

At first, the operation depends on the dividend, since we assign the figure depends on the dividend, but after a few steps (in our case, from the second step), only zero is assigned to the right. After this, we find ourselves in the conditions of operation of the law we formulated. An object is a number, it can be in a finite number of states: accepted non-negative integer values, less than the divisor. The operation is defined; it unambiguously converts one number to another. This means that the sequence of numbers obtained will be periodically repeated. It follows that the numbers in the partial will begin to repeat periodically. Our statement has been proven.

What happens if you take the sum of its digits from a number, take the sum of its digits from the resulting number again, etc.? Let’s add it up, for the number 1987 everything is clear:
1987→25→7→7→7→...

What about other numbers? It is easy to notice that every number is greater than the sum of its digits (the only exception is single-digit numbers), therefore, after applying the operation of taking the sum of digits, the number will decrease until it becomes single-digit, and a single-digit number with our operation turns into an equal number. Thus, we received proof of periodicity (with period 1) we obtain sequences starting from a certain place.

What number will be repeated? This question is easy to answer without writing out the sequence itself. This will be the remainder of the first number divided by 9 if the number itself is not divisible by 9, and 9 if it is divisible by 9. Why? Based on divisibility by 9. True, you know it in a “truncated” form: “in order for a number to be divisible by 9, the sum of its digits must be divisible by 9.” However, there is a stronger statement: the number itself and the sum of its digits have the same remainder when divided by 9.

Now it is clear that each subsequent number will have the same remainder when divided by 9 as the initial one. Among single-digit numbers, all have different remainders when divided by 9, except 0 and 9, but a number other than zero has a sum of digits that is also different from zero. This is where our statement follows. A periodic sequence with period 1 is called a fixed-point sequence.

What happens if a number does not have a sum of digits, but a sum of squares of digits? Let's try again for the number 1987 (Fig. 7). We found that the sequence 145, 42, 20, 4, 16, 37, 58, 89 will be repeated periodically.

Let's take the number 133 (Fig. 8). Here the “fixed point” is 1 (the period of the sequence is 1).

But is it necessary for periodic sequences to arise when calculating the sum of squares of digits? And if so, which ones?
