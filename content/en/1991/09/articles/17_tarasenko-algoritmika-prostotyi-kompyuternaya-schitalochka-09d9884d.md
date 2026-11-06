---
id: 1991-9-tarasenko-algoritmika-prostotyi-kompyuternaya-schitalochka-09d9884d
issue: kvant_1991_9
year: 1991
number: "9"
title: Algorithms of simplicity. Computer counting rhyme
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
lang: en
source: kvant_digital
extraction: vision
content_sha256: 54ecfd0841acb53da01737eb409bd966d0dc2de838f48640defe95e43edc4f1d
prompt_sha256: draft-1
translated_from: content/ru/1991/09/articles/17_tarasenko-algoritmika-prostotyi-kompyuternaya-schitalochka-09d9884d.md
source_content_sha256: 34817aa8e871bf4203f7a881bd11f06e599859b9e17a4df64c5df94956cd8a79
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 50⟧

---
running_head:
folio:
---

Algorithmika
simplicity

Computer counting rhyme

V. TARASENKO

It's not an easy question,
But believe one thing:
Everything is complicated and simple,
Count it wisely!

Who doesn’t remember the cute fun of early childhood, little rhymes? “The month has emerged from the fog...”, “Eniki-beniki or dumplings...”. In addition to the ability to evoke pleasant memories, they have one more property: the result, or “the draw of who should lead,” is unambiguous in each specific case and is easy to calculate. But by unspoken agreement, the myth of the unpredictability and fairness of the answer in the end was carefully preserved and maintained. This is an indispensable condition for any child's game. Sometimes, in order to successfully print a letter, a special algorithm is predicted.

On this porch sat:
Tsar, prince, king, prince, Shoemaker, tailor. Who are you?
Speak quickly, without thinking!

The one on whom the last stressed syllable falls, without really thinking, blurts out, for example, “tailor.” Then the counting “in verse” is necessarily repeated, starting with “tailor”, and ending with the leading word “tailor”. To keep everything “fair,” sometimes they agree in advance whether to count “clockwise” or “counterclockwise.”
With prime numbers the opposite is true. They always count “clockwise”, i.e. in the direction of increase. And always “from the stove”, from the first prime number two. They use only one “counting table” - Erathofen’s reversible algorithm, sometimes only a little of its visibility.

Prime numbers are distributed unevenly among natural values. Consider something very well known called the “Table of Primes Not Exceeding 6000.” Classic. How many simple ones are there? In A. A. Bukhshtab’s book “Number Theory” (M., “Prosveshcheniye”, 1966), the table is arranged side by side according to the scheme 11×38+10×36+5×1, which gives 783, i.e. approximately three primes for every 23 numbers. Then the 25th prime number should be somewhere around 200, but in fact it is equal to 97. And unfortunately, one cannot quickly say what the 25001st prime number will be, at least approximately, without turning to the help of a computer, although mathematicians have found formulas for approximate estimation of the number of prime numbers that do not exceed a given natural number.

Let's try to “highlight” the situation a little, or it is always better to see once than to hear it once. Let's pose the problem and investigate it using only handheld computing equipment. What is the number of primes in each first hundred numbers after the next power of ten?

Here are the experimental data. At the beginning of each series, the power of ten is given, then in parentheses the number of primes in this series, then the prime numbers themselves in this series, and at the end after a semicolon - the next prime (to save space, only the last two or three digits of each number are given). For such a “review of hundreds,” software tool No. 1 from our first publication (see «Kvant» No. 6) was sufficient for us; only for 10⁸ and larger numbers were calculations carried out on the MK-85 and HP-32S.

⟦folio 51⟧

---
running_head:
folio:
---

Program 4. Prime number generator
Text of the program with step-by-step comments

53 X→Π 6 46 /+ Enter odd old number
54 0 00 /+ Constant 0
55 C/Π 50 /+ Storindication for dialing a number
56 F X≠0 57 /+ PrX≠0?
57 5 55 /+ NO (i.e. PrX=0), go to step 55
58 X→Π 4 44 /+ YES, write serial number to Pr4
59 1 01 /+ Constant 1
60 X→Π 45 45 /+ Zasylak 1 in Pr5
61 K P→X 5 Γ5 /+ Add 1 to counter Pr5
62 K P→X 5 Γ5 /+ Adding 1 more to counter Pr5
63 P→X 6 66 /+ Call in PrX the current test number AND
64 P→X 5 65 /+ Calling the current divider D from Pr5 into PrX
65 ÷ 13 /+ PART=I/D
66 X→Π 9 49 /+ Zasylak PART in Pr9
67 K P→X 9 Γ9 /+ K=integer part of PART
68 P→X 6 66 /+ Call I in PrX
69 P→X 9 69 /+ Call K in PrX; And moves to PrY
70 P→X 5 65 /+ Call D in PrX; PrY=K; PrZ=AND
71 × 12 /+ D×K
72 - 11 /+ OST=I-K×D, remainder of division
73 F X≠0 57 /+ OST≠0?
74 8 4 84 /+ NO (i.e. OST=0), go to step 84
75 P→X 9 69 /+ YES (i.e. OST≠0), calling an integer PART
76 P→X 5 65 /+ Call D from Pr5 to PrX
77 - 11 /+ PrX=PART - D
78 F X<0 5C /+ PART - D<0?
79 6 1 61 /+ NO, go to step 61 to new value D
80 P→X 4 64 /+ YES (set D is exhausted), call number
81 P→X 6 66 /+ Call a prime number
82 C/Π 50 /+ Storindiction of a prime number
83 K P→X 4 Γ4 /+ Adding 1 to the counter Pr4 of the number number
84 K P→X 6 Γ6 /+ Adding 1 to the tested number in Pr6
85 K P→X 6 Γ6 /+ Adding 1 more to the tested number
86 BP 51 /+ Unconditional jump
87 5 9 59 /+ per step 59

10^0 (25): 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97; 101.
10^1 (25): 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97; 101, 103, 107, 109; 113.
10^2 (21): 1, 3, 7, 9, 13, 27, 31, 37, 39, 49, 51, 57, 63, 67, 73, 79, 81, 91, 93, 97, 99; 211.
10^3 (16): 9, 13, 19, 21, 31, 33, 39, 49, 51, 61, 63, 69, 87, 91, 93, 97; 103.
10^4 (11): 7, 9, 37, 39, 61, 67, 69, 79, 91, 93, 99; 103.
10^5 (6): 3, 19, 43, 49, 57, 69; 103.
10^6 (6): 3, 33, 37, 39, 81, 99; 117.
10^7 (2): 19, 79; 103.
10^8 (6): 7, 37, 39, 49, 73, 81; 123.
10^9 (7): 7, 9, 21, 33, 87, 93, 97; 103.
10^10 (4): 19, 33, 61, 97; 103.
10^11 (7): 3, 19, 57, 63, 69, 73, 91; 103.

So, the number of primes in each subsequent system decreases, but they are not uniform: 25, 25, 21, 16, 11, 6, 6, 2, 6, 7, 4, 7, ... And this, in turn, may be a reason for raising new questions and new research. For example: how many primes are there in every thousand naturals, starting from the first? Please also note that out of 12 “cut” studies, seven “end” at 103 and only one starts at one.

A new field requires new tools and amenities. We provide those who wish with a software incremental generator for the MK-61. It is similar to the very first one, but is supplemented by a prime number numerator.

(For the ending see p. 58)
