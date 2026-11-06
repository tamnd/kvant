---
id: 1991-7-tarasenko-algoritmika-prostotyi-chislovyie-atomyi-ebdf4242
issue: kvant_1991_7
year: 1991
number: "7"
title: Algorithms of simplicity. Numerical "atoms"
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 72
page_last: 74
page_labels: 70-72
lang: en
source: kvant_digital
extraction: vision
content_sha256: 04164c83ec7feb4baf074ddf34129767e0b699ad0cb4b3b6c38c19397e1dfceb
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/23_tarasenko-algoritmika-prostotyi-chislovyie-atomyi-ebdf4242.md
source_content_sha256: c9168032cb242c199641ae7db07f0ecfa72174dc8823174e26820649926f2ca7
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 70⟧

---
running_head:
folio:
---

Algorithmika
simplicity

Numerical "atoms"

V. TARASENKO

It's not an easy question,
But believe one thing:
Everything is complicated and simple,
Count it wisely!

Prime numbers can be called "atoms of the numerical universe." Therefore, as soon as someone begins to “collect primes,” he quickly approaches the problem of decomposing natural numbers into primes. If program No. 1 from the previous number «Kvant» is available, the problem is resolved independently.

If the number under study is even, then first you need to isolate the maximal number from it.
The greatest power of two by successive division by two. This is easy to do on any type of calculator. Now the problem has been reduced to factoring an odd number. The tool we need will be polluted if in the prototype program we replace commands 24-27 with an unconditional jump to the beginning of the program, and at step 16 we replace the address part of the conditional jump command from 24 to 23.

When working with a pollutant program, each time you read the next factor you will have to manually perform three additional key commands. This is definitely inconvenient. The positive side of the “coin” is the almost maximum multiplicity of the main text of the new program, as well as the ease of its removal from the prototype. We will still have simplicity analyzer programs with better service, but more voluminous. Nothing comes for free, including additional conveniences at work.

Program No. 2, like the previous one, is published in a form in which, from our point of view, it can be given to any prepared user without additional fees.

Program 2. Odd number divider analyzer

All secondary guns from B3-34 to MK-61 are suitable. Variables and used registers: D=Pr5 - current odd divisor; И=Pr6 - starting or next odd number; PARTIAL=Pr9=I/D - the quotient of dividing I by D (first a real number, and then its integer part).

Description of the algorithm

Set the initial I. For consecutive odd D, starting from D=3 and until PART>D, calculate PART=I/D, then K - the whole part of I/D and the remainder OCT=I-K×D. In the case of OCT = 0, count D (this is another prime divisor of the testing number), set newI = I/D and proceed to study this I.

⟦folio 71⟧

---
running_head:
folio:
---

If OST≠0 for all tested D, then the tested number itself is simple, the expansion is legal.
Evaluation of the program's performance: the number 11111 has a divisor of 47 in 2 minutes, and the number 10001 has a divisor of 73 in 3 minutes 20 seconds.

Instructions
After typing the program and switching the PMC to counting mode, press the B/O key. Then dial the initial odd integer AND and press the C/P key, counting will begin; after stopping the counting, if the PMC stopped at a non-zero number on the indicator, then the last tested number is simple, the expansion is legal; if the indicator shows 0 (a simple divisor is detected), then perform it manually
P→X 6
P→X 5
and read the number from the indicator (this is the next simple divisor of the number being studied), then press the ÷ key and if the indicator shows 3, then this is the last simple divisor; if the indicator does not show 3, then press the C/P key, after which the search for prime divisors will resume.

A new tool will usually be tested on decent material. We took the powers of two flat and minus one, Fibonacci numbers, rebonites (numbers composed only of ones, see «Kvant» No. 8 for 1989), as well as numbers composed of two ones and several zeros dividing them. The "protocol tested" is given below. We will not comment on them. We are confident that readers will figure it out for themselves.

2^n+1
n expansion

1 3=3
2 5=5
3 9=3 × 3
4 17=17
5 33=3 × 11
6 65=5 × 13
7 129=3 × 43
8 257=257
9 513=3 × 3 × 19
10 1025=5 × 5 × 41
11 2049=3 × 683
12 4097=17 × 241

⟦folio 72⟧

---
running_head:
folio:
---

2^n — 1
n expansion
1 1=1
2 3=3
3 7=7
4 15=3×5
5 31=31
6 63=3×3×7
7 127=127
8 255=3×5×17
9 511=7×73
10 1023=3×11×31
11 2047=23×89
12 4095=3×3×5×7×13

Fibonacci numbers
n expansion
1 1=1
2 1=1
3 2=2
4 3=3
5 5=5
6 8=2×2×2
7 13=13
8 21=3×7
9 34=2×17
10 55=5×11
11 89=89
12 144=2×2×2×2×3×3

(10^n — 1):9
n expansion
1 1=1
2 11=11
3 111=3×37

4 1111=11×101
5 11111=41×271
6 3×7×11×13×37
7 239×4649
8 11×73×101×137
9 3×3×37×333667
10 11×41×271×9091
11 21649×513239
12 3×7×11×13×37×101×9901

10^n — 1 + 1(n > 1)
n expansion
1=1
2 11=11
3 101=101
4 1001=7×11×13
5 73×137
6 11×9091
7 101×9901
8 11×90901
9 17×5882353
10 7×11×13×19×52579
11 101×3541×27961
12 11×11×23×4093×8779

Inside each sequence between ordinal numbers and the decomposition of numbers into simple components of the space of four there are connections, the study of which we provide to the reader and until the next issue of our series we again leave all mathematics lovers alone with a hand-held personal computer calculator and this program.

Dear reader!

Subscription for 1992 begins.
Despite all the crippling difficulties associated with the preparation of the magazine, as well as with the increasing cost of paper, printing and distribution of publications, the editor intends to preserve the face and volume of the magazine «Kvant».
The magazine «Kvant» is not available in retail, so we advise you not to delay subscribing to it.
The cost of one room is 1 rub. 10 k., periodicity of the magazine - 12 issues per year.
It can be written out not necessarily for a year, but for any period and from any month.
Subscriptions are accepted without restrictions at Soyuzpechat agencies, post offices and post offices.

Journal index «Kvant» in the Soyuzpechat catalog 70465.
