---
id: 1991-6-tarasenko-algoritmika-prostotyi-50-tomov-v-karmane-3140556d
issue: kvant_1991_6
year: 1991
number: "6"
title: Algorithms of simplicity. 50 volumes in your pocket
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 60
page_last: 61
page_labels: 58-59
lang: en
source: kvant_digital
extraction: vision
content_sha256: e532f366f202d53394e534a94273866629bc40f343a10ae32d9719e1f750f7df
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/17_tarasenko-algoritmika-prostotyi-50-tomov-v-karmane-3140556d.md
source_content_sha256: 0d8fd2ae4e401e560557630a36210274de07c65c97ac3371ba4d0a6dd78f5d34
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 58⟧

Simplicity algorithm

50 volumes in your pocket

V. TARASENKO

It’s not an easy question, but believe one thing:
Everything is complicated and simple, Count it wisely!

One day in 1948, when the author of these lines was in the third grade, he bought a wonderful book by G. N. Berman, “Number and the Science of It,” along with some Sunday ice cream. This book has forever made me a lover of integer mathematics, especially prime numbers. This little book will probably be of interest to the outside generation of seekers.

Prime numbers have long been a subject of constant attention to amateurs and professionals. Recall that a prime is a natural number that is different from one and is divisible by only itself and one. The first prime numbers are: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41,... The series of prime numbers is infinite.

In published tables of prime numbers, the general upper limit is 6000, less often 10,000. It is possible to create a table of prime numbers up to 10^8, but it turns out to be a multi-oted edition (about 50 volumes). Is it necessary?

It turns out that it may well be replaced by the “simplest” ones from the world of computers - programmable microcomputers. B3-34, MK-52, MK-54, MK-56, MK-61, weakly equipped with the appropriate program, are able to give an accurate answer to many questions. Let's start with a prime number generator. The program below allows you to generate, starting from a given odd number AND, successive prime numbers. At the same time, it checks that the number AND being studied is not divisible by any odd number in the range from 3 to √I. The program is operational from I=5 to I=99999989 inclusive.

A few words about the form of program description. We believe that we are dealing with that category of readers for whom a slight “sporting” of the material is only helpful and provides greater efficiency. Therefore, our marriages will be minimal - just enough so that the owners of the B3-34 (the inscriptions on the keys of which differ from the inscriptions on the MK-61) can figure out for themselves what they need to press.

Program 1. Sequential Prime Number Generator

All secondary guns from B3-34 to MK-61 are suitable. Variables and registers: D=Pr5 - current odd divisor; And=Pr6 - rated odd using number; PARTIAL=Pr9=I/D - the quotient of dividing I by D (first a real number, and then its integer part).

Description of the algorithm

Set the initial I. For successive odd D, starting from D=3, calculate PART=I/D, then K -

⟦folio 59⟧

---
running_head:
folio:
---

TEXT Programs with step-by-step comments

00 X→Π 6 46 /+ Entering the start AND from PrX into Pr6
01 1 01 /+ Constant 1
02 X→Π 5 45 /+ Entering 1 into Pr5, preparing counter D
03 K P→X 5 Γ5 /+ D : =D + 1, initial phase of counter operation D
04 K P→X 5 Γ5 /+ D : =D + 1; results: newD = starD + 2
05 P→X 6 66 /+ Call I = Pr6 in PrX
06 P→X 5 65 /+ Call D in PrX; And moves to PrY
07 ÷ 13 /+ PART = I/D
08 X→Π 9 49 /+ SEND PRIVATE to Pr9
09 K P→X 9 Γ9 /+ K = integer part of PART
10 P→X 6 66 /+ Call I in PrX
11 P→X 9 69 /+ Call K in PrX; And moves to PrY
12 P→X 5 65 /+ Calling divider D in PrX; PrY = K; PrZ=AND
13 x 12 /+ D×K
14 - 11 /+ OST = I - K×D, remainder of division
15 F X≠0 57 /+ OST≠ 0?
16 24 24 /+ NO (i.e. OST = 0), go to step 24
17 P→X 9 69 /+ YES (i.e. OST ≠ 0), calling an integer PART
18 P→X 5 65 /+ Call D
19 - 11 /+ PrX = PART - D
20 F X<0 5C /+ PART - D < 0?
21 03 03 /+ NO, go to step 03 to new value D
22 P→X 6 66 /+ YES (set D is exhausted)
23 S/P 50 /+ Stop indication I
24 К П→X 6 Γ6 /+ И = И + 1, start of generation of new И
25 K P→X 6 Γ6 /+ И = И + 1, end of generation; new = old + 2
26 VP 51 /+ Unconditional jump
27 01 01 /+ to step 01

the whole part I/D and the rest OST=I-K×D. In the case of OST = 0, proceed to specifying a new value for AND. If D is greater than PART (I is a prime number), then carry out the indication of AND and stop the calculations. Then set new=oldI+2 and proceed to study this AND.

Evaluation of the program's performance: the primality of the number 5 is confirmed in 7 seconds, the primality of the number 99999989 is confirmed in about 7 hours.

The most interesting command in the program is 09. As a result of its execution, the number in Pr9 becomes an integer. This method of selecting an integer part of a number is also applicable to PMK models preceding the MK-61, which nominally do not have the operation of selecting an integer part of a number.

Instructions

After typing the program and switching the PMC to counting mode, press the B/O key. Then dial the initial odd integer AND and press the C/P key, counting will begin; after stopping counting, the indicator shows another prime number. Pressing C/P starts a new cycle of operation, ending with the appearance of a new prime number on the indicator, and so on.

Using this program, you can easily verify that the integer numbers 3, 31, 331, 3331, 33331, 333331, 3333331 are composed of only prime numbers. The beauty of small personal discoveries and victories will fade if we give too many hints and present ready-made results. Therefore, for the next issue of our series, we leave the math lover, researchers#define with a hand-held personal computer calculator and this program.
