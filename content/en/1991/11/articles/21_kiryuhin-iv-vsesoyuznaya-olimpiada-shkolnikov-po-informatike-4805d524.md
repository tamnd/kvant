---
id: 1991-11-kiryuhin-iv-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-4805d524
issue: kvant_1991_11
year: 1991
number: "11"
title: IV All-Union Olympiad for Schoolchildren in Informatics
authors:
  - Кирюхин В. М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 67
page_last: 69
page_labels: 65-67
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8594025c1b328928eed73556b29acc2dbd380059ae8537e796c1912312420147
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/21_kiryuhin-iv-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-4805d524.md
source_content_sha256: 1223992ce4e1e318122bb34b66214868b239394f98db4630000516eb5106724e
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 65⟧

---
running_head:
folio:
---

IV Total
Schoolchildren's Olympiad
according to information

Candidate of Technical Sciences
V. KIRYUKHIN

This year, the final stage of the IV All-Scholastic Olympiad for Schoolchildren, according to information, took place from April 17 to 24 in Vishkek, the capital of resource workers in Kyrgyzstan. This time, 87 schoolchildren from 11 resource groups, as well as the cities of Moscow, St. Petersburg and Vishkek (as host cities of the Olympics) took part in the Olympics. A total of 16 teams represented resource specialists and various regional countries. As always, the largest team was the RSFSR team - 26 people. The minimum possible composition (3 participants) was represented by teams from Kazakhstan, Kyrgyzstan, Latvia, Moldova and Turkmenistan.

Kyrgyzstan greeted the Olympic participants with its unique beauty. All the guys immediately felt that they were welcome guests here. And even the sun smiled welcomingly at times, wishing success in this difficult competition.

The grand opening, which took place in the film hall, was colorful. The organizers did everything to convey to the crowd the inherent national flavor of the resource and create a good mood for the entire period of the Olympics.

As before, the Olympida was carried out in two types, both types being computer-based. Half of the participants chose IBM PC personal computers, and the other half chose Yamaha.

Zhior The entire Olympid was headed by Academician of the Academy of Sciences of Kyrgyzstan resource specialists V.P. Zhivoglyadov. The jury with voting rights included representatives of all participating resource workers, as well as the cities of Moscow and St. Petersburg. A package of problems for the Olympida was prepared by a scientific committee headed by Corresponding Member of the USSR Academy of Sciences F. L. Chernousko, and before each round the Olympida jury selected one problem from this package. The tasks were multi-level, which allowed both very strong participants and less prepared ones to prove themselves. It should be noted that there was a problem with the problems proposed - it required the guys to demonstrate not only the ability to create an algorithm and a workable program, but also to format the problem posed.

Let us present the conditions of the problems.

Task Itura
(authors A. Grudev, F. Chernousko)

A robot manipulator is defined on the coordinate plane, consisting of two sequentially connected links, the lengths of which are L1 and L2. The first hinge link is fixed at the origin of coordinates, the second hinge is connected to the first. At the end of the second link installing the drill. The robot is controlled by rotating the links in the first and second joints with angular velocities, the absolute value of which does not exceed the width $\omega$1 and $\omega$2 (pad/c), respectively. The second link can rotate relative to the first continuous one.

The robot is designed for responsible drilling. Coordinates of drilling points: (x1; y1), (x2; y2), ..., (xN; yN).

At the initial moment, the first link is directed along the positive strip OX, and the second link forms an angle A, away from the OX axis counterclockwise. The time of the responsible drilling operation is fixed and equal to P.

You need to create a program that:

a) gives any sequence of drilling point numbers and the time required for this;

b) produces a sequence of drilling specified points in the shortest possible operating time of the robot and this time itself;

b) for a given time interval (0, T), selects the maximum number of drilled responsible and outputs their sequence.

Applications

1) All input data is integer.

2) The program must enter the initial data either from the input file (A: ROBOT.DAT) or from the keyboard in the form of a sequence: L1, L2, $\omega$1, $\omega$2, A, T, P, N, x1, y1, ..., xN, yN.

Task II round
(author I. Volkov)

Many different words $A=(a1, a2, ..., ak)$, $k \leq 10$ are given. Of the words there are many

⟦folio 66⟧

---
running_head:
folio:
---

$A$, an encrypted text is compiled - a sequence of words written without spaces. Words are non-empty sequences of no more than vosmal Latin letters and can appear in the text an arbitrary number of times. It is necessary to decipher the text, i.e., break it into words of the set $A$. In the decrypted text, words should be separated by spaces.

Write a program that:
a) determines whether for a given set $A$ there is a text that can be deciphered in more than one way;
b) if such a text exists, then excludes the minimum number of words from the set $A$ so that any text can be decrypted unambiguously, and prints the excluded words (if such an excluded set is not the only one, then displays all options);
b) for the entered text, decrypts it using the initial input set $A$, and if there is not a unique decryption, then displays all options.

Sequence of I/O operations:
— input of the set $A$:
“enter k”〈К〉
“enter a1”〈a1〉
“enter ak”〈ak〉
— message output:
“ambiguously decipherable text exists”
or
“does not exist”
— if the text exists, then the message output:
“throw away”〈word list〉
— enter text no more than forty characters long in the form:
“tekst”〈tekst〉
— output of decryption results:
〈tekst〉→〈decrypted text〉.

Examples
1) $A=(B, C)$ - any text is decrypted unambiguously.
2) $A=(B, C, BC)$ - there is a text that can be decrypted in two ways:
BBC→B BC
or
BBC→В В С.
Žorny optimized together with a commission to review the participants’ work assessed each type of task based on 100 points. When assessing the results, I take into account the ability of schoolchildren to formalize the proposed task, the ability to algorithmize, i.e., to develop the best algorithm and justify its reliability, the ability to program the resulting algorithm using one of the programming systems: BASIC, Turbo-Pascal, Turbo-C. By the way, most schoolchildren program in Pascal.

Of the two problems proposed for optimization, the problem of the first type turned out to be the most difficult. When solving it, it was important to identify inaccessible points, indicate the need to move the robot from one position to another, and also justify the need for a complete search to obtain the correct answer. In addition, this problem offers a number of interesting heuristics that significantly increase the efficiency of the algorithm in determining the combination of input data.

Unfortunately, no optimization student was able to solve this problem in full. The best results here were added by A. Guzeev from Perm (56 points), D. Zhukov from Moscow (56 points) and S. Gershtein from Yekaterinburg (52 points). Only 30% of schoolchildren received 20 points or higher for this problem - as it turned out, many participants simply had poor mathematics and physics skills, which did not allow them to even begin to develop an algorithm for solving the problem.

The second type of problem is more accessible to formalization, and therefore the results were better. A. Sukhanov from St. Petersburg received the maximum number of points - 72 - for this problem. D. Uvarov from Novokuznets and A. Skovortsov from Yubileiny, Dnepropetrovsk region received 52 points each.

Of course, the relatively poor results obtained by participants in solving these optimization problems can be partly explained by their complexity. However, we will not limit ourselves to just this explanation. Firstly, the level of complexity of the problem corresponded to international optimizations, and it would probably be wrong for us to lower this bar lower. Secondly, in theoretical terms, many participants found the right idea for solving each problem. There was not enough time for implementation. All this suggests that the intellectual abilities of the majority of participants are quite high, but the lack of necessary practice in working with personal computers did not allow them to bring their existing ideas to their logical conclusion,

⟦folio 67⟧

---
running_head:
folio:
---

t. e. get workable programs.
Despite all the difficulties, the days of accomplishment quickly flew by, and it was time to sum up the results. As always, there were many different prizes for the winners of the Olympiad, in addition, each participant received a souvenir gift from the organizers.
This year, for the first time, the results were summed up separately in two categories: grades 8-10 and grades 11. The best performer in the overall standings at this Olympiad was A. Sukhanov (122 points), who received a Corvette personal computer as his medal. He is followed by A. Guzeev (90 points) and D. Uvarov (89 points). As at previous Olympiads, schoolchildren from St. Petersburg were ahead in the team competition. It’s amazing that among the prizes there were also girls - A. Pratusevich and A. Kosov-
skaya received second and third degree diplomas, respectively.
Based on the results of the past Olympiad, the jury recommended including A. Sukhanov and D. Kim among the candidates for this year’s international Olympiad. To prepare for the next international Olympiad, which will be held in 1992 in Germany, all schoolchildren of non-graduating classes who received first and second degree diplomas were included as candidates for the USSR national team. They will be invited to participate in winter training camps to be held next year.
In conclusion, I would like to thank the organizers of the Olympiad, who did everything possible to hold such a technically complex competition, and also wish all participants even greater success in the difficult field of computer science.
