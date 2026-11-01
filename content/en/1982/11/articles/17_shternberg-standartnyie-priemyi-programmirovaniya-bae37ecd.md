---
id: 1982-11-shternberg-standartnyie-priemyi-programmirovaniya-bae37ecd
issue: kvant_1982_11
year: 1982
number: "11"
title: Standard Programming Techniques
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 64
page_last: 66
page_labels: 62, 64
tag: B1OF
lang: en
source: kvant_digital
extraction: vision
content_sha256: dbdbbc23ad94a2463eef8bb5740caea8b04b68115908433abb919bfb10fe2c18
prompt_sha256: draft-1
translated_from: content/ru/1982/11/articles/17_shternberg-standartnyie-priemyi-programmirovaniya-bae37ecd.md
source_content_sha256: b71b60a5fe3f3f12f5a315692abc813abd608d8dd15bc9e94e4aa8b6d49f50ad
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 62⟧

The Art of Programming

Standard programming techniques
Lesson 2. Linear search

Search problems are one of the most common: they arise when constructing translators and in many programs, large and small, that you encounter. If the search is in a file, or if the array being searched is unordered (that is, the value of an element cannot tell where it is located), then the only possible type of search is a linear search, in which the programming information is carried out from beginning to end, element by element. Further, the array is ordered, but has a small length; there is no point in using anything more complex than linear search. Thus, all three preparatory tasks*)

*) See Lesson 1, «Kvant» No. 10.

Solutions
In all solutions: x is the given value, k is the desired index

a)
Problem 1 (first one that fits)
i:=1; k:=0;
while (i<=n) AND (k=0) do
begin
if a[i]=x then k:=i;
i:=i+1
end;

b)
for k:=1 to n do
if a[k]=x then goto 7;
k:=0;
7:...

Problem 2 (last one suitable)

k:=0;
for i:=1 to n do
if a[i]=x then k:=i;

problem 3 (mth suitable)
k:=0; i:=1; j:=0;
while (i<=n) AND (k=0) do
begin j:=j+1;
if j=m then k:=i
end;
i:=i+1
end;

j:=0;
for k:=1 to n do
if a[k]=x then
begin j:=j+1;
if j=m then goto 7;
end;
k:=0;
7:...

62

⟦folio 64⟧

Fig. 1.

Fig. 2.

Fig. 3.

first they cut along those mutually perpendicular planes passing through its center - it turned out 8 pieces; then they made a fourth, oblique cut, which divided all these pieces, except for the “back” one, into two - it turned out 15 pieces, but one of them (namely the central one - the most foldable part of the pulp of the front “eight”) does not have a crust. There are 14 crusts left from this arb. Other cutting options are also possible.

Editor-in-Chief - Academician I. K. Kikoin
First Deputy Editor-in-Chief - Academician A. N. Kolmogorov
Deputy editors-in-chief: M. N. Danilcheva, V. A. Leshkovtsev, Yu. P. Solovyov

Editorial collection: L. G. Aslamazov, M. I. Bashmakov, V. E. Belonuchkin, V. G. Boltyansky, A. A. Borovoy, Yu. M. Bruk, V. V. Vavilov, N. B. Vasiliev, S. M. Voronin, V. V. Gnedenko, V. L. Gutenkhmer, N. P. Dolbilin, V. N. Dubrovsky, A. N. Zemlyakov, A. R. Zilberman, S. M. Kozel, S. S. Krotov, L. D. Kudryavtsev, A. A. Minailov, E. M. Nikishin, S. P. Novikov, M. K. Potapov, V. G. Razumovsky, N. A. Rodina, N. H. Rozov, A. P. Savin, Ya. A. Smorodinsky, A. B. Sosinsky, V. M. Uroev, V. A. Fabrikant

Editorial Board: A. M. Baldin, S. T. Belyaev, B. B. Bukhovtsev, E. P. Velikikhov, I. Ya. Verchenko, B. V. Vozdvijzhensky, G. V. Dorofeev, N. A. Ermolaeva, A. P. Ershov, Yu. B. Ivanov, L. V. Kantorovich, P. L. Kapitsa, V. A. Kirillin, G. L. Kotkin, R. N. Kuzmin, A. A. Logunov, V. V. Mozhaev, V. A. Orlov, N. A. Patrikeeva, A. V. Peryshkin, R. Z. Sagdeev, S. L. Sobolev, A. L. Stasenko, I. K. Surin, E. L. Surkov, L. D. Faddeev, V. V. Firsov, G. N. Yakovlev.

The number was issued:
B. Galkin, L. Denisenko, M. Dubach,
N. Kuzmin, E. Nazarov, A. Permin, E. Tenchurina

Editorial Head L. Chernova
Art editor T. Makarova
Proofreader M. Medvedskaya

103006, Moscow, K-6, st. Gorky, 32/1,
«Kvant», tel. 251-82-42

Delivered to set 9/17/82. Signed for publication on November 3, 1982.
Offset printing
Paper 70×108 1/16. Phys. oven 4
Conditional oven l. 5.60 Academic ed. l. 7.15 T-20908
Price 40 kopecks. Order 2378 Circulation 175,067 copies.

Order of the Red Labor Order
Chekhov Printing Plant
VO "Soizpolgrafprom"
State Committee of the USSR
for publishing and printing affairs
and book trade
Chekhov, Moscow region
