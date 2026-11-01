---
id: 1986-3-rozhdestvenskiy-hlebutin-programmirovanie-na-mikrokalkulyatore-vetvlenie-i-tsikl-1e2df95b
issue: kvant_1986_3
year: 1986
number: "3"
title: 'Programming on a microcalculator: branching and looping'
authors:
  - Рождественский В. В.
  - Хлебутин С. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 47
page_last: 49
page_labels: 45-47
tag: NRUB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1c388c0304fccdb2e3648d2c7975c9a1879d2ec67508d603a3dbee398eed3e8e
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/16_rozhdestvenskiy-hlebutin-programmirovanie-na-mikrokalkulyatore-vetvlenie-i-tsikl-1e2df95b.md
source_content_sha256: b6c380b4b6ce5d8c1b12f2e17fe65c59e0f3240a9d8258effbe38e50cdd69436
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

Programming on a microcalculator: branching and looping

V. V. ROZHDESTVENSKY,
S. G. KHLEBUTIN

This note is intended primarily for ninth-graders studying the course “Fundamentals of Information and Computing Technologies” and having access to a programmable microcalculator.

In the previous issue «Kvant» I talk about how the simplest programs written in an educational algorithmic language can be “translated into codes of a programmable microcalculator,” that is, such programs can be automatically converted into a list of commands for a microcalculator (see the article by L. F. Sternberg “Programming on a microcalculator: the simplest programs”). Here we continue this story. We are talking about the translation of two main constructs of an algorithmic language: branching and looping. The presentation is carried out in relation to the Elektronka MK-54 microcalculator, but with minor changes it can be attached to other models of domestic programmable calculators.

First of all, let's see how the calculator works in automatic mode, that is, when the program is executed without human intervention. To control the selection of a command from memory, a special cell called an address counter is used.

This cell can contain any program memory address.

If you press the C/P key in auto mode, this orders the calculator to start automatic operation. This means that the calculator analyzes the contents of the program memory cell to which the address counter points, performs one or another operation and changes the contents of the address counter. Such actions are called program cycles. Consistently executing cycles, the program counts until it encounters STOP commands.

If there are no transition operations in the program, then during the execution of one clock cycle the value of the address counter is increased by one. Transition operations are designed specifically to change the contents of the address counter for our device. How do jump commands work?

Let's consider the commands BP and Fx∨0, where ∨ denotes one of the signs of the comparison operation: <, =, ≥, ≠. For these commands to work, it is necessary to use two memory cells: one to store the command code and the next to store some address.

The operation of the BP command is carried out as follows: the calculator places in the address counter the address that we have written in the next cell of the BP code.

The Fx∨0 command does the following: if the x∨0 condition is satisfied, then the old contents of the address counter are increased by two; if the condition is not satisfied, then the address from the cell next to the Fx∨0 command code is placed in the address counter.

Example 1. Let's monitor the change in the address counter during the stream execution of the following program (see tables below).

⟦folio 46⟧

So, we see that the presence of jump operations makes it possible to disrupt the natural (in the order of addresses) sequence of the command, and this is precisely what is necessary when programming the “loop” and “branch” constructs.

"Cycle" design
In algorithmic language, such a construction looks like this:
while the condition
nc
series
kts
To facilitate the transition of the “cycle” construction to the calculator language, we will write it in a slightly different form, namely:
Bye
v ∨ 0
series
kts
Here v is an argumentative expression, ∨ is one of the comparison signs described above.
We propose the following scheme for transitioning a loop operator from an algorithmic language to a calculator language (here X denotes the top of the stack):

Note that the command K NOP (no operation), although it does not entail any action, is convenient for establishing a correspondence between keywords (bye, kts). algorithmic language and calculator commands, and also makes it easier to follow the logic of the program. Aligning records vertically is convenient for finding jump addresses and for reading a program.

Example 2. Let's develop a program to calculate m=n!

In educational algorithmic language, the program looks like this:

alg factorial (integer m, n)
arg n
res m
start intact
input n
m:=1
i:=1
while i<n
nc
i:=i+1
m:=m*i
kts
output m

con
Please note that we have inserted two additional commands into the body of the program (input and output) - they make translation easier.
The program can now be broadcast. First, we describe the storage location of variables in the form of a table.

Variables n m i
Memory RgO Rg1 Rg2

The rendered program looks like this:

Addresses Commands Codes
00 C/P 50
01 X→PO 40
02 1 01
03 X→P1 41
04 1 01
05 X→P2 42
06 K NOP 54
07 P→X2 62
08 P→X0 60
09 - 11
10 F x<0 5C
11 22 22
12 P→X2 62
13 1 01
14 + 10
15 X→P2 42
16 P→X1 61
17 P→X2 62
18 X 12
19 X→P1 41
20 BP 51
21 06 06
22 K NOP 54
23 P→X1 61
24 C/P 50

⟦folio 47⟧

Branching design
In algorithmic language this construction is written as follows:
if condition
then episode 1
otherwise episode 2
All
For convenience of translation in the calculator language, we will write it like this:
If
v ∨ 0
episode 1
otherwise
episode 2
All
We offer the following translation scheme:

For a “shortened” branch operator (if... then... all), the translation scheme could be like this:

Example 3. Let's develop a program to find the larger of two numbers a and b.

In algorithmic language, this program can be written as follows (as above, for ease of translation we have introduced additional input and output commands):

alg bid (things a, b, y)
apr a, b
res y

beginning
input a, b
if a ≥ b
then y := a
otherwise y := b
All
output y

con
Let's write out the addresses of the variables in the form of a table:

Variables a b y
Memory Rg a Rg b Rg 0

The program broadcasts as follows:

Addresses Commands Codes Algorithmic language
00 C/P 50
01 X→Pa 4-
02 C/P 50
03 X→Пb 4L
04 KNOP 54
05 P→Ha 6-
06 P→Xb 6L
07 — 11
08 F x ≥ 0 59
09 14 14
10 P→Ha 6-
11 X→P0 40
12 BP 51
13 17 17
14 KNOP 54
15 P→Xb 6L
16 X→P0 40
17 KNOP 54
18 P→X0 60
19 C/P 50

In conclusion, we note that translation schemes may be better or worse, but their very presence allows translation to be carried out automatically and almost without errors. Thus, if a program in an algorithmic language is written correctly, then bringing it to a calculator is not at all difficult.

Amendment
In the first issue «Kvant» for this year, an operation was allowed under the conditions of problem 2 of option I on page 52. The inequality in the conditions should be read as follows: log $\frac{1}{4} - 3x$ > 0.
