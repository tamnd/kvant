---
id: 1972-8-adelson-velskiy-bernshteyn-gerver-kto-poedet-v-rio-0159f0fd
issue: kvant_1972_8
year: 1972
number: "8"
title: Who will go to Rio?
authors:
  - Адельсон-Вельский Г. М.
  - Бернштейн И. Н.
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: BEF3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9a6ab6611af1f9c2bd86ebebe4ee30823bf84d4e38fe04f4c0377f59d6ce48dd
prompt_sha256: draft-1
translated_from: content/ru/1972/08/articles/03_adelson-velskiy-bernshteyn-gerver-kto-poedet-v-rio-0159f0fd.md
source_content_sha256: 31fb15c8ec7ff27d2d77864bef3cf076c7aec41e186d914defa8b00d0d84c944
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Who will go to Ryuo

G. M. Adelson-Velsky,
I. N. Bershtein,
M. L. Gerver

The problem discussed in this article is not at all of a specific chess - or indeed sports - nature. It could, for example, be formed like this: from $n$ pairs of unequal weight stones, display them in descending order $k$ heaviest, using only two-piece scales without weights, using the minimum weighing number. But here is a formulation that has a perfect mathematical meaning: create a program for a computer that, with a minimum number of comparisons, would select the largest $n$ pairwise unequal numbers $k$ and arrange them in descending order *).

The clause on pairwise inequality of numbers (or stones) automatically ensures the fulfillment of the condition: if $a > b$ and $b > c$, then $a > c$. You don’t need to be an experienced Bolshisky player to understand that there is actually nothing like that in sports and that, say, Fischer’s loss to Petrosyan at the pretenders’ tournament in Curacao and Spassky’s win in the decisive game of the world championship match with Petrosyan do not at all predetermine the outcome of the Spassky-Fischer match.

Let us note, however, that the Olympic system (loser is eliminated) is based precisely on the assumptions formed at the beginning of the article. By the way, the “usual” Olympic scheme, according to which the loser in the final is immediately declared the second prize-winner (and the winner of the meeting of the losing semi-finalists is declared third), is only a worse version of the “VOMI Rules”!

The task that the authors talk about, as already mentioned, is of a completely serious nature. (By the way, its solution, despite all its apparent “elementaryness,” was obtained only quite recently, which, of course, is of particular interest to our journal). The author found it more pleasant and fun to present it in “chess” language...

Chapter 1. VOMI Rules

It's finished! The chess cities of Vasyuki are finally allowed to participate in the World Olympiad in Rue de Janey.

*) The article deals only with the case $k=3$ (the general case is discussed in Problem No. 3).

ro. It turned out, as usual, at the last moment, and now a qualifying round must be held in a matter of days and the three strongest should be chosen from 128 amateur chess players. Two of them (champion and second prize-winner) will play for Vasya’s team

⟦folio 4⟧

third place winners, just spend
$$127 + 6 + 6 = 139$$
parties.

Chapter II. Could it be shorter?

Are VOMI rules good? Is it possible to determine the 1st, 2nd and 3rd winners in fewer games?

§ 1. Management’s opinion, chance and fate

Even before the perfection, let the management of the Four Horses Club form the opinion that the strongest chess player is A, the second best is B, and the third is C. And let the goal of the perfection be to verify that this is actually true.

Such a check cannot be carried out in less than 127 games, since all chess players, except the champion, must lose at least one game. And for 127 games, it is possible: 125 “outsiders” (all except A, B and C) play 124 “knockout” games (after each game the loser is eliminated), then the winner plays with C and loses *), C loses *) B and C will lose *) A. As a matter of fact, it is not even necessary to know the winners firsthand: they can be guessed by chance, so sometimes (“if you’re lucky”) three winners are determined by 127 games.

We will, however, assume that nothing more is known about the strength of chess players and that we “don’t know.” Moreover, let us imagine that Evil Fate (or an agent of the opponents - whatever you want) influences the outcome of each game so that the perfect one lasts as long as possible. We will show that in this case it is impossible to choose the 1st, 2nd and 3rd winners among 128 chess players in less than 139 games, no matter how **) the frivolous severnonia is carried out.

*) If he wins, then it means that the management was mistaken, and what to do next is unclear.
**) Of course, in accordance with proposals 1-5 of Chapter I.

§ 2. Statement of the theorem

Let us immediately examine the actual case when there are 128, and any number of chess players in perfect sections. Let's denote it by n. Let us also introduce the following notation. Let N be an arbitrary number; for some integers l the inequality $2^l \geq N$ holds. Let us denote by l [N] the smallest of these integers.

Examples.

1. Since $2^3 < 10 < 2^4$, then l [10] = 4.
2. If $2^{k-1} < N \leq 2^k$, then l [N] = k.
3. Soon we will need to know what l[N] is equal to if N = 128·127. Since $128 = 2^7$ and $2^6 < 127 < 2^7$, then $2^{13} < 128·127 < 2^{14}$, whence l [128 127] = 14.

Theorem. To determine 1-20, 2-20 and 3-20 winners among n chess players, you need to cheese no less than

$$P(n) = l[n(n-1)] + n-3$$
parties.

According to him. Another way to formulate this theorem is as follows.

Let it be allowed to check a maximum of R games, where

$$R < l[n(n-1)] + n-3.$$

Then (regardless of whatever rules the severnonia is carried out) the results of the games may turn out to be such that after R games it is still not possible to determine the 1st, 2nd and 3rd winners.

If n = 128, then l[n(n-1)] = l[128·127] = 14 (see example 3). This means that P(128) = 14 + 128 - 3 = 139. Thus, from the formulated theorem it follows that to determine the 1st, 2nd and 3rd winners among 128 chess players, no less than 139 games are needed. In 139 games they can be determined using the VOMI rule - so VOMI rules are good!

§ 3. In the accounting department of Evil Rock

In § 1 of this chapter, we warned that Evil Rock is trying to delay the severnonia qualifiers. Now

⟦folio 5⟧

we indicate a strategy, following which, he will ensure that the 1st, 2nd and 3rd prizes are determined among $n$ chess players at least

$$P(n) = l \left[ n(n-1) \right] + n-3$$

parties.

About the limit 1. We will call any pair of chess players $(A, B)^*$ commando. We emphasize that the commands $(A, B)$ and $(B, A)$ are different; $A$ plays in team $(A, B)$ on the first board, and in team $(B, A)$ on the second.

Before the start of the competition, all teams compete at the site in Olympida. How many are there?

Before the tournament, each of the $n$ chess players has a chance to play on the first board. At the same time, he can lead the $n-1$ team (any chess player except himself can be second to him). Thus, the number of all commanders is $n$ ($n-1$).

As the competition progresses, the number of teams vying for a seat in Rio gradually decreases (until exactly one such team remains).

Suppose several games have already been played in Turin. Based on their results, we will divide all participants into 3 groups. The first group includes everyone who has not lost a single game. To the second - those who lost exactly one game, and necessarily to the chess player of the first group. To the third - all the rest (those who lost more than one game or one game - each player not from the first group).

In the right. Check that in this situation the following teams are vying for a seat in Rio:

1) all teams $(A, B)$, in which $A$ are from the first group, and $B$ from the second, and the only game that $B$ lost was lost to $A$;

2) all teams $(C, D)$, as well as $C$ and $D$, are from the first group.

Check that no other teams are competing at the Olympida site.

*) The “team” consists of two, not three people: the reserve player is not included in the team (this is more convenient for presentation).

(Indication. Let $B$ lose to $A$, then $B$ will not become the champion, and can become the second prize-winner only on the condition that $A$ turns out to be the champion. Thus, $B$ will no longer be able to lead any team and only in one team - in $(A, B)$ - can he enter as the second participant.)

Definition 2. If at some point in the competition, chess player $A$ has won $a$ games, and chess player $B$ has won $b$ games, then we will say that team $(A, B)$ has $a+b$ points. The number $2^{a+b}$ is called the characteristic of the team $(A, B)$.

After each new game, the asset of any team either increases by 1 (if the winner of the game is part of this team) or does not change. The corresponding characteristic of any command is either deleted or remains unchanged.

Definition 3. Let a certain number of games be played. It is convenient to characterize the current situation with the number $M$, which is equal to the sum of the characteristics of all the teams still competing for the site in Olympida.

What is $M$ equal to in the initial situation (before the competition)? No one has won a single game yet, each team has 0 points, the characteristic of any team is $2^0=1$. Thus, the $M$ initial is simply the total number of the command, that is, $M_{\text{начальное}}=n$ ($n-1$).

Lemma. Let in some situations, characterized by the number $M$, a game is played between chess $A$ and $B$. Let us denote by $M_A$ the number characterizing the situation that will arise if $A$ wins, and by $M_B$ the number characterizing the situation in the event of $B$ winning. Then

$$M_A + M_B = 2M,$$

so that although one of the numbers $M_A$ and $M_B$ is not less than $M$.

Proof. Before the game between $A$ and $B$, all teams competing for the site in Olympida are naturally divided into 3 groups.

⟦folio 6⟧

Group I. Commands in which $A$ is included, but $B$ is either not included, or is included after $A^*$).

Group II. Commands in which $B$ is included, but $A$ is either not included, or is included after $B$.

III group. Teams that do not include either $A$ or $B$.

Let us denote by $M_I$, $M_{II}$, $M_{III}$ the sums of characteristics of commands of groups I, II and III (so $M=M_I+M_{II}+M_{III}$).

Let us prove that $M_A=2M_I+M_{III}$. Indeed, after victory $A$, only teams of Groups I and III qualify for victory in Rio; At the same time, in group III the characteristics of teams do not change, but in group I they double.

Similarly, it is proved that

$$M_B = 2M_{II} + M_{III}.$$

So,

$$M_A + M_B = 2(M_I + M_{II} + M_{III}) = 2M.$$

Strategy of Evil Doom. How is the qualifying tournament going? As we know, all games are played sequentially (one after another). The participants of each new game are named depending on the results of all previous games.

Let a certain number of games have already been played, and the next game is called between chess $A$ and $B$. Evil Doom counts the characteristics $M$, $M_A$ and $M_B$ (see lemma); then if $M_A>M_B$, he eliminates so that $A$ wins, and if $M_B>M_A$, so that $B$ wins; if $M_A=M_B$, then he will not be alarmed. Since the larger of the numbers $M_A$ and $M_B$ is completed at least $M$ (by the lemma), then with this strategy the characteristic $M$ does not decrease after each game.

Emphasizing that it is enough for Rock to be Almighty and there is no need to be

*) B is included after $A$ in only one team ($A, B$); this team is included in Group I and placed only on the condition that it still claims to win in Rio.

Omniscient: without delving into the plans of the organizing tournament, he applies the same strategy for any game schedule.

Next, we will show that with this strategy, determining the 1st, 2nd and 3rd winners will require at least

$$P(n) = l[n(n-1)] + n-3$$

parties.

§ 4. Proof of the theorem

Do corvevohany $M_{начальное} = n(n-1)$. What is the value of $M$ when the corvevohany is completed and the 1st, 2nd and 3rd runners-up $X$, $Y$ and $Z$ are determined? One team ($XY$) has been selected for the train to the Olympics. Let us denote by $v$ the number of points in the asset of this team. Then $M_{конецное} = 2^v$.

If Evil Doom followed the strategy described above, then after each game the stat $M$ did not decrease, so $M_{конецное}$ is no less than $M_{начальное}$. Hence $2^v \geq n(n-1)$, that is $v \geq l[n(n-1)]$. Thus, the first two winners $X$ and $Y$ participated in no less than $l[n(n-1)]$ games.

In addition, at least $(n-3)$ games were played without their participation. Indeed, each of the $(n-3)$ chess players who were not included in the recognized top three had to lose to someone other than $X$ and $Y$ - otherwise he would have claimed third place.

Thus, in total no less than

$$P(n) = l[n(n-1)] + n-3$$

parties. The theorem has been proven.

Chapter III. How to determine the three winners among $n$ chess?

Chapter I presented the rules by which three winners could be determined among 128 chess games. Let us present similar rules for the case of $n$ chess. Let $l[n]=k$, that is

$$2^{k-1} < n \leq 2^k.$$

⟦folio 7⟧

§ 1. Definition of champion

Games are played according to the Optimian system. At the 1st stage, all participants are divided into two groups: in one $2^k$—pairs; in another pair the winner is determined and admitted to the 2nd stage; members of the first group begin the fight immediately from the 2nd stage. Total admitted to stage 2

$$\left(n - 2^{k-1}\right) + \left(2^k - n\right) = 2^{k-1}$$

participants. All stages, starting from the 2nd, “standard”*): the participants of the stage are divided into pairs, in each of the pairs a winner is determined, who is admitted to the next stage. The champion is determined in the financial game at the $k$-th stage. Since each of the $n$ participants, except the champion, loses one game in such a systematic manner, then a total of $(n-1)$ games will be played at the $k$ stages.

§ 2. Determination of the second prize-winner

Chess players who have only lost to the champion are vying for this place. There are no more than $k$; Let's assign them numbers 1, ..., $k$ ($N_2$ i is the one who lost to the champion at the $i$-th stage**).

We play games like this: $N_2$ 1 plays with $N_2$ 2***), then the winner plays with $N_2$ 3, etc. (in total no more than $k-1$ game). The winner of the last game is the second runner-up.

*) The 1st stage, in contrast to the case discussed in the VOMI rules, is “non-standard” (that is, it requires the additional division of participants into groups indicated in this paragraph), if $n$ is not an exact power of two.

**) Note that $N_2$ 1 may not be reached at all (if the champion started the game from the 2nd stage).

***) There is no other stage (see the previous method), and everything starts with the game between $N_2$ 2 and $N_2$ 3.

§ 3. Determination of third place winner

It is easy to check (see § 3 of Chapter I) that the second prize-winner won no more than $k$ games and therefore no more than $k$ people are vying for third place. The strongest of them is finally determined for the $k-1$ game. This is the third prize winner.

§ 4. Conclusions

To find among the $n$ chess players the 1st, 2nd and 3rd prize-winners, just check

$$\left(n-1\right) + \left(k-1\right) + \left(k-1\right) = 2k + n-3 = 2l \left[n\right] + n-3$$

parties. We will denote this number by $Q(n)$.

Chapter IV. Discussion of results

Let $n$ be an integer, $n \geqslant 3$. Let us denote by $I(n)$ a number that satisfies the following two conditions:

1) for $I(n)$ games it is certainly possible to determine the 1st, 2nd and 3rd winners among $n$ chess players.

2) if $R < I(n)$, then the result of the games may turn out to be such that in $R$ games it is not possible to determine the 1st, 2nd and 3rd winners among $n$ chess players.

Then the results obtained in Chapters II and III can be written as the formula

$$P(n) \leqslant I(n) \leqslant Q(n).$$

Let us remind you that

$$P(n) = l \left[n(n-1)\right] + n-3,$$

$$Q(n) = 2l \left[n\right] + n-3,$$

where $l \left[n\right] = k$ at $2^k \geqslant n > 2^{k-1}$.

It can be shown that $Q(n)$ is equal to either $P(n)$ or $P(n)+1$. In the first case $I(n)=P(n)=Q(n)$. In the second case, there are two possibilities for $I(n)$: either $I(n)=P(n)$ or $I(n)=Q(n)$. Both possibilities
