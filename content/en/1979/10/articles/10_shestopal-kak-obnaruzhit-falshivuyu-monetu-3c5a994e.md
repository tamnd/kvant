---
id: 1979-10-shestopal-kak-obnaruzhit-falshivuyu-monetu-3c5a994e
issue: kvant_1979_10
year: 1979
number: "10"
title: How to spot a counterfeit coin
authors:
  - Шестопал Г. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 27
page_labels: 21-25
tag: KGYW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0b75cc9c7085296c1cb93e1fc633f27e44390d79a6f63b91bc7b04aaba79bd94
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/10_shestopal-kak-obnaruzhit-falshivuyu-monetu-3c5a994e.md
source_content_sha256: bf7393e7736d5d546416399243966ccc15f27de1d92d4764543d0cbab32f87ff
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

G. Shestomal

How to spot a counterfeit coin

Imagine that a pile of identical-looking coins is poured onto a table, but you are told that one of these coins is counterfeit. It is different in weight from the other coins, but you are not told whether it is lighter or heavier. An hourly scale without mushrooms is at your disposal. How should you proceed to isolate this coin and find out its type (that is, find out whether it is lighter or heavier) in a minimum number of weighings?

Many of you have probably already solved this problem for 12 coins. One of the solutions to this problem is shown on figure. The possible outcome of the first weighing corresponds to three different options for choosing coins for the second weighing. (On figure the coins are resized, the letters l and t are read accordingly, light and heavy.)

A characteristic feature of this solution is the dependence of the choice of coins for the next weighing on the result of the previous one.

Let us now pose the problem in general form.

There are $m \geq 3$ coins of the same type. All coins, except one, have the same weight, and one differs from them in weight, but it is not known in which direction. What is the smallest number of weighings on a clock scale without zip that can be used to find this coin and find out its min? *)

This problem attracted the attention of many mathematicians more than a few years ago, mainly:

*) Obviously, for values ​​$m < 3$ the problem does not make sense to solve: for $m = 1$ the coin will be counterfeit, but of an unknown type; at $m = 2$ the coins will have different weights, and it is impossible to choose a counterfeit one.

⟦folio 22⟧

in England and the USA. In 1945, in the English magazine “The Mathematical Gazette”, let’s say in its direction «Kvant», a solution to this problem appeared. Its author, R. L. Goodstein, subsequently became a famous expert in the field of mathematical logic.

Goodstein provides a method for identifying a counterfeit coin and its type in $n \geq 3$ weighings if the number of coins

$$m \leq \frac{1}{2} \left( 3^n - 2n + 3 \right)$$

(note that for $n = 3$ $m \leq 12$).

However, it turned out that for $n > 3$ his solution is not the best: in $n$ weighings one can isolate a counterfeit coin and determine its type from a large number of coins:

$$m \leq \frac{1}{2} \left( 3^n - 3 \right).$$

This was discovered by several mathematical scientists, insignificant from each other, and in the following year, 1946, the same magazine published a fairly long list of their names and the different levels of success available in the search for a counterfeit coin. In the same issue of the magazine, the best solution was published - the solution of F. J. Dyson, the future famous theoretical physicist.

Dyson's idea is based on the use of a ternary number system: all coins are marked with specially selected ternary numbers - markers that make it possible to conveniently reflect the progress of successive weighings. Particularly attractive with this solution method is the independence of the choice of coin for subsequent weighing from the result of the previous one.

In subsequent years, other solutions to this problem were published *), and Dyson's method was unheard of forgotten.

Pozny is interested in talking about him in detail.

All Dyson solutions can be divided into two stages.

*) Nalrimer, in the book by A. Yaglom, II. Yaglom “Probability and Information” (M., “Nauka”, 1973).

A. If

$$m = \frac{1}{2} \left( 3^n - 3 \right), n = 2, 3, \dots,$$

then to isolate one counterfeit coin from the total number of $m$ coins and determine its type, it is enough to perform $n$ weighings.

B. If the number of coins

$$m < \frac{1}{2} \left( 3^n - 3 \right), m \geq 3,$$

then to achieve the same goal $n$ weighings will also be sufficient.

Let's consider each stage separately.

First stage

Let the number of coins be $m = \frac{1}{2} \left( 3^n - 3 \right)$.

Consider all $n$-digit numbers (sets of digits 0, 1, 2) 00 ... 00, 00 ... 01, ..., 22 ... 22. There are $3^n$. We use them to mark coins as follows: as markers we take all the numbers, with the exception of three, consisting of identical numbers: 0 ... 0, 1 ... 1, 2 ... 2.

《Let's build》 all the markers in pairs: in one pair we will “put” two additional markers - those whose numbers correspond to 2 (in other words, additional markers will be those whose sum is equal to 22... 22).

Let's call a marker *right* if it contains the first pair of unequal numbers - 01, 12 or 20. Otherwise, the marker will be called left. Obviously, in each pair of additional markers there is one pair of markers. For example, 12 coins can be “marked” as shown in the table.

Let us denote by $M(i, 0), M(i, 1)$ and $M(i, 2)$ the corresponding set of coins for which the $i$th digit of the corresponding right marker is equal to 0, 1 or 2.

⟦folio 23⟧

It is easy to see that the number of coins in each of the sets $M(i, 0)$, $M(i, 1)$ and $M(i, 2)$ is the same and that these sets have no common elements (see, for example, the table).

Dyson's method of weighing coins is as follows:

The coins are weighed sequentially $n$.

At the $i$th weighing ($i = 1, 2, \dots, n$), all the coins of the set $M(i, 0)$ are placed on the left pan of the scales, and all the coins of the set $M(i, 2)$ are placed on the right pan. The result of each weighing will be denoted by the number 0 if the left pan of the scales outweighed, by the number 1 if both cups have the same weight, and by the number 2 if the right pan weighed (see Fig.). The result of the $i$-weighting will be denoted by $l_i$.

From the numbers $l_1, l_2, \dots, l_n$ we make a marker

$$l = l_1 l_2 \dots l_n^*).$$

It turns out that $l$ is the marker of the counterfeit coin $F$ and if $l$ is the right marker, then $F$ is heavier than the rest of the coin, and if $l$ is the left marker, then $F$ is lighter than the rest of the coin.

Indeed, let's see what produces when $i$-e are produced

*) Prove that this is really a marker, i.e. that the numbers $l_1, l_2, \dots, l_n$ cannot be the same.

$$l_i = 0$$

weighing. As a result of this weighing, the scales either remained in balance or one of the cups was crossed.

If the scales remain in balance, then there is no counterfeit coin on it, therefore, it is in the set $M(i, 1)$. But this means that the $i$th digit of its right (and left) marker is equal to 1, as indicated by the weighting result $l_i = 1$.

If one of the scales is crossed, then the counterfeit coin is on the scale. Let, for example, the right cup be crossed, i.e. $l_i = 2$. This result is possible in two cases:

- the counterfeit coin lies on the right cup (then it is heavier than the other coins), which means that it is in the set $M(i, 2)$, the $i$th digit of its right marker is equal to 2, therefore, the weighing result coincides with the $i$th digit of its right marker;

— the counterfeit coin lies on the left cup (then it is lighter than the other coins), which means that it is in the set $M(i, 0)$, therefore, the $i$-th digit of its right marker is 0 and the result of weighing coincides with the $i$-th digit of its left marker.

The “symmetrical” case is completely analogous, when the left pan of the scale ($l_i = 0$) crosses.

Pozny, indeed, the marker $l = l_1 l_2 \dots l_n$ formed as a result of successive weighings is the marker of a counterfeit coin, with the right one in the case of a heavier coin and the left one in the case of a lighter one, which is what needed to be proven.

It is interesting to note that the type of coin is usually determined by nisse, which is where all the weighings are made - as soon as two different digits appear in the process of forming the marker $l$.

An essential feature of the described method, as already noted by ravnisse, is the fact that the choice of coins for each of the weighing sets does not depend on the results of the previous weighing.

⟦folio 24⟧

For example, for 12 coins marked as shown in the table, you need to do the following three weighings: (1,4,7,10), (3,6,9,12); (3,6,9,10), (2,5,8,12); (3,4,8,12), (2,6,7,11).

Second stage

Let us briefly outline the Dyson method for the case $m < \frac{1}{2} (3^n - 3)$. If in this case markers are assigned to coins arbitrarily, then the sets $M(i, 0)$ and $M(i, 2)$ may contain different numbers of coins. Let us act as a poet as follows. Divide all the markers into groups of six: into one group we include the right markers, which receive from each other by cyclically replacing the numbers $0 \rightarrow 1$, $1 \rightarrow 2$, $2 \rightarrow 0$ and the corresponding left markers.

Each group contains three right markers and three left markers. Let us highlight the group containing the right markers $00 \ldots 01, 11 \ldots 12, 22 \ldots 20$. Divide the coins into groups of three as long as possible and mark them as follows. Monetam from one group we compare pairs of markers from one group, and for the remainder, if there is one, we use pairs of markers from the selected group. If there is one coin left that is not included in the triplets, then match the right marker $11 \ldots 12$ to it, and if there are two, then the right markers $00 \ldots 01$ and $22 \ldots 20$ (and the corresponding left markers).

With this marking, the first $n — 1$ weighings will be started on the right. Please let us know how to perform the final weighing yourself.

The Dyson method is described. Let us now make sure that in a certain sense it is presence. Namely, we will show that if from $m$ coins it is possible to select $n$ a counterfeit coin by weighing and determine its type, then $2m \leq 3^n — 3$. Of course, we will not take into account the possibility of “luck”: with it, two weighings may be enough to identify a counterfeit coin from any number of coins.

So let's assume that $n$ weighting is sufficient.

Let's number the coins with the numbers $1,2, \ldots, m$ and prepare $2m$ pieces of paper. Let's write all possible options on them: the first coin is lighter, the first coin is heavier, the second coin is lighter, etc. It is clear that in this case all $2m$ pieces of paper will be used and not a single one of the possible options will be missed. We will denote, as we stated above, the result of weighing by the numbers $0, 1$ or $2$. Each weighing shows that some of the possible answers are inappropriate, and some remain suspect. We will select coins for the first weighing. Without actually doing it, we will write on each piece of paper the result of the first weighing that leaves it under suspicion. It is clear that on each piece of paper one of the numbers $0, 1$ or $2$ will be written. Thus, all the papers will be divided into three groups. Therefore, the largest group contains no less than $2m/3$ pieces of paper. This means that no matter how we organize the first weigh-in, it may turn out that after it no less than $2m/3$ pieces of paper will remain under suspicion.

Likewise, the second weighing will sort this suspicious group into three subgroups. Therefore, the most numerous of them will contain at least $2m/9$ pieces of paper. In the same way, after $n$ weighing, we can get $2m/3^n$ suspicious pieces of paper in one group. Therefore, if $2m/3^n > 1$, then the counterfeit coin and its type, generally speaking, cannot be determined by $n$ weighing. Therefore $n$ weighing is sufficient, then $2m \leq 3^n$.

But that's not all! We haven't dealt with the case of $2m = 3^n — 1$ yet (the even number $2m$ cannot equal either $3^n — 2$ or $3^n$). For him, the above messages are not enough.

⟦folio 25⟧

Let's take a closer look at the first weigh-in. It is clear that the number of pieces of paper on which the number 0 is written is equal to the number of pieces of paper on which the number 2 is written. Let there be $p$ pieces of each, then 1 will be written on $2m - 2p$ pieces of paper.

Note that $p$ is an even number. Indeed, if there are $k$ coins on the left and right sides of the scales, then $p = 2k$. If $p$ or $2m - 2p$ is greater than $3^{n-1}$, then, according to consideration, the remaining $n - 1$ weighing may not be enough to determine the required piece of paper. If $p = 2k \leq 3^{n-1}$ and $2m - 2p \leq 3^{n-1} - 1$, then since $3^{n-1} - 1$ is an odd number, $p \leq 3^{n-1} - 1$, $2m - 2p \leq 3^{n-1} - 1$. But then $2m = (2m - 2p) + 2p \leq 3^{n-1} - 1 + 2(3^{n-1} - 1) = 3^n - 3$. So, if $n$ weighing is enough, then $2m \leq 3^n - 3$.

In conclusion, there are several problems that can be solved by the Dyson method.

List of readers who sent rules for solving problems from the Problem Book «Kvant»

(For the beginning, see pp. 7, 14)

A. Petrosli (Yerevan) 6a; L. Petrusevich (village Kozly, Minsk region) 6; I. Pikovsky (Kyiv) 3; A. Podvyaznikov (Mosalsk) 7; V. Podstritsan (Lviv) 6, 8, 1; A. Popelokhin (Kyiv) 6, 7; A. Popov (Moscow) 7; V. Pomanov (Novosibirsk) 3; S. Poshekhonov (Engels) 7; G. Purichamishili (Tbinis) 6a; B. Rabinovich (Tula) 6, 7, 1, 3, 4; V. Radchenko (Kyiv) 6a, 2-4; M. Reitman (Moscow) 6a, 7, 2; S. Rekhvashili (Pavlodar) 6; I. Roizman (town of Kalinovka, Vinnytsia region) 6-8; N. Rubinmeshin (Leningrad) 6a; B. Rublev (Kyiv) 2, 3; I. Savenkov (urban settlement Levye Gory, Saratov region) 6, 7; G. Samelson (Leningrad) 3; M. Sevryuk (Moscow) 6-9, 1-3; P. Selivanov (Semipalatinsk) 6a, 7, 2; A. Sivatsky (Leningrad) 6a, 7, 9, 0, 2, 3; A. Smirnov (Kurgan) 6, 7; A. Smyslov (Konkovo) 6; A. Sromin (Leningrad) 6, 7; S. Smadinitsenko (Moscow) 6—8, 3; F. Sukoev (Tashkent) 6-9; N. Sumovsky (Lviv) 7, 8; O. Taven (Minsk) 6a, 7; K. Tatalyan (Yerevan) 6; L. Tener (village of Yaltushkov, Vinnytsia region) 6, 7; K. Terekhov (Ryazan) 6a; V. Titenko (village of Bluzha, Minsk region) 7; A. Ulivanov (Gorky) 9; V. Umansky (Baku) 6, 7; R. Ushakov (Kyiv) 3; D. Faingauz (Leningrad) 6, 7, 0; V. Farber (Baku) 3; A. Famullayev (Baku) 3; N. Fedin (Omsk) 2; A. Fedorov (Moscow) 7, 3; O. Horuzhsky (Chernivtsi) 7; S. Khosid (Alma-Ata) 6a, 7; Z. Tsikhistavi (Telavi) 3; I. Chernaya (Leningrad) 3; O. Chechel (Moscow) 6—8, 1, 4; A. Shatsyan (Yerevan) 7; P. Shaprin (Kyiv) 7; N. Sharomet (Moscow) 6, 7, 2, 4; Yu. Shirman (Kharkov) 6; G. Shteren (Orsk) 6a; M. Yakovlev (Kemerovo) 2; A. Yalytsev (Tula) 6, 7; L. Yanovskaya (Kharkov) 7; A. Yatsenko (Tbilisi) 7.

F and zika

Almost all readers coped with tasks F539 and F542. The remaining problems were solved correctly:

V. Abidzhaev (Lviv) 33; E. Alexandrova (Glazov) 35, 40, 41; Yu. Anisimov (Toropetsk district, Kalinin region) 35; A. Arbamsky (Blagoveshchensk-on-Amur) 40, 41; A. Bazirov (village Kirovka AzSSR) 40; L. Baraz (Sverdlovsk) 38-41; I. Baranets (Dzerzhinsky village, Moscow region) 38-41; A. Barzikin (Chernogolovka village, Moscow region) 33, 35-41; A. Belousov (Kaliningrad) 36; A. Vasiliev (Võru) 40, 41; D. Vinogradov (Dzerzhinsk) 35; M. Gavrilov (Chernogolovka village, Moscow region) 35, 38—44, 47; M. Goltsman (Dnepropetrovsk) 43, 44, 47; I. Gopchi (Novosibirsk) 38, 41; V. Gorpinenko (Kolchugino) 40; I. Danilovsky (Gorky) 33, 38; V. Didukh (Lviv) 35, 37, 38, 40-44, 47; S. Dovbishch (Moscow) 33, 35, 38—41, 47; S. Dovzhenko (Donetsk) 34-36, 38-41; E. Emelyanov (Moscow) 43, 47; A. Ermolin (Petrozavodsk) 36, 38; V. Zhordochki (Orsk) 38; A. Zhuravlev (Leningrad) 38-41; E. Zernysh (Kuzmovka village, Leningrad region) 40, 41; E. Zudin (Alexandrov) 34, 35, 37, 40, 41-44, 46; S. Zuev (Chernogolovka village, Moscow region) 40; A. Iovasha (For the end, see p. 38)
