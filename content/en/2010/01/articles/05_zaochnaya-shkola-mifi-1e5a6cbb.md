---
id: 2010-1-zaochnaya-shkola-mifi-1e5a6cbb
issue: kvant_2010_1
year: 2010
number: "1"
title: '[MEPhI Correspondence School]'
rubric: informatsiya
rubric_sub: Информация
page_first: 58
page_last: 66
page_labels: 56, 64
tag: 918Z
lang: en
source: kvant_digital
extraction: native
content_sha256: 1906d274f60700de2a399e34869ecc48b7d5250452793514315517f8a95f9079
prompt_sha256: draft-1
translated_from: content/ru/2010/01/articles/05_zaochnaya-shkola-mifi-1e5a6cbb.md
source_content_sha256: 519c6437f6bad50eee0038787d6ae55873e28be3775ef522755ee20969178806
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

KVANT 2010/№1

listeners. Lectures are often interdisciplinary in nature and are devoted to issues far from the traditional areas of general mechanics and robotics. For example, the following topics were presented: the phenomenon of cavitation; mathematical models of management systems for objects of national significance; volcanic eruptions; properties of vision of living beings and their use in creating technical vision systems; various aspects of biomechanics (i.e., science at the intersection of mechanics and biology) - simulators for astronauts, modern materials and their use in bone prosthetics, as well as a only recently developed theory that satisfactorily explains the measurement of blood pressure using a simple device consisting of a rubber inflatable cuff, a bulb and a manometer. Excursions are organized to the unique experimental installations of the Institute of Mechanics of Moscow State University (hydrodynamic tunnel, wind tunnel, hydraulic channel, etc.). Familiarization with modern mechanics and robotics is important not only for schoolchildren, but also for secondary school teachers. Therefore, within the framework of our Program, teacher training courses are held. An important direction of the Program is the creation of a list of research tasks offered to schoolchildren. It currently includes more than 30 tasks. Thus, a competition is announced annually to set up and conduct an experiment to study the properties of dry friction. The list of tasks and the announcement of the competition can be found on the website indicated at the end of the article.

⟦column⟧

To prepare a video course of lectures, they are video recorded and a video library is created - the basis for distance learning (including work with schools for children with disabilities). All of the above activities of the Program for schoolchildren and teachers, carried out at traditional sites, are carried out free of charge. However, by agreement, it is also possible to conduct visiting lectures and seminars, study groups, and other forms of cooperation. Any student can take part in any event of the Program (listening to lectures, participating in a competition, solving problems). Please note that in many areas (competitions, research work, etc.) remote participation is possible. Regularly updated information about all Program events is presented on the website of the Institute of Mechanics http://www.imec.msu.ru/school Our email address: school@imec.msu.ru Postal address for correspondence: 119192 Moscow, Michurinsky Prospekt, 1, Institute of Mechanics of Moscow State University, Scientific educational program in mechanics. We invite all interested individuals and organizations to take part in our Program! The publication was prepared by S. Dovbysh, B. Lokshin, M. Salmina

⟦folio 64⟧

KVANT 2010/№1

Let K, L, M be the midpoints of sides BC, DE, FA, respectively, and P be the midpoint of EI. Then $S_{KLM} > S_{MPB} > S_{ABI} = S_{XYZ}$.

Both inequalities follow from the following obvious statement: Let TUVW be a parallelogram, point R and segment VW lie on opposite sides of line TU. Then

⟦figure⟧

Fig. 7

$S_{RVW} > S_{RTU}$.

(The first inequality uses the parallelogram BKLP, the second uses AIPM.) Note. There is an annoying second case in this problem, which the given solution does not take into account: when the hexagon and the triangle, given in the condition, are oriented differently (i.e., when reading the letters - the names of the vertices - the hexagon is traversed clockwise, and the triangle - counterclockwise). In this case, if we complete our triangle on one of the sides of the hexagon, it will stick out! Here is a sketch of a solution for this case. It is reduced to the first by the following rearrangement of the hexagon (Fig.8). Here

⟦column⟧

but above, we can prevent Ali Baba from equalizing all the numbers in the marked places. We will construct Ali Baba's winning algorithm for $2^{k}$ places inductively. The basis for k = 1 is obvious. Let us have an algorithm $A_{m}$ for m places. Let's build $A_{2m}$. Let's start with special cases. Let us divide the circle into m pairs of opposite places and establish a correspondence between the pairs for 2m and the places for m. 1) Let us know that the numbers in each pair are equal. Let's apply the $A_{m}$ algorithm, replacing places in whole pairs. It is clear that when the lock opened there, it will open here too. 2) Let us know that the parity of the sum in each pair is the same. Let's use $A_{m}$ for pairs. If it did not open, then all the amounts were odd. But by changing both numbers of a pair, we do not change the parity. This means that all amounts remain odd. Let's change m digits in a row (let's call this operation D). Now all sums are even. Once again using $A_{m}$ for pairs, we will open the lock. Let's call the algorithm for this case B. 3) Now apply $A_{m}$ for pairs in a different way: the goal is to make sums in pairs of the same parity. As before, at each step we select a set of pairs according to $A_{m}$, but we change only one digit in each selected pair. Let's call the algorithm C. It guarantees that at some step (we don't know which) the parities of the sums will coincide. The door, of course, will not open. But we will cheat: after each step C we apply B, and then D. If the parity sums match, B will open the door, otherwise BD will not change the parity of the sums.

©

NUMBER HAS BEEN PREPARED

S.A. Dorichenko, A.A. Egorov, E.M. Epifanov, S.P. Konovalov, A.Yu. Kotova, V.A. Tikhomirova, A.I. Chernoutsan

⟦figure⟧

Fig. 8

$AC_{1} = CB, C_{1} D_{1} = EF, BF_{1} = FA, F_{1} E_{1} = DC$. From here it easily follows that $K_{1} L_{1} = LK, K_{1} M_{1} = MK, L_{1} M_{1} = ML$, i.e. the middle triangle has not changed. 7. At $N = 2^{k}, k = 0, 1, 2,$ ... Replace the barrels with zeros and ones standing in a circle. Let $N \ne 2^{k}, k = 0, 1, 2,$ ... Let us show that if there is bad luck, Ali Baba will never open the cave. We can assume that we are playing against Ali Baba, rotating the circle, and that he tells us in advance where he will change the numbers on each (including the first) move. Let us first consider the case when N is odd. Let's place zeros and ones on the circle so that Ali Baba does not win with his first (known to us) move (i.e., so that after his move there are both zeros and ones on the circle). Let Ali Baba choose certain k places for replacement on the next move. He will win only if these k places coincide with either the set of all zeros or the set of all ones. But the number of zeros is not equal to the number of ones (the sum of the numbers is odd!). This means that there are not k numbers of some numbers. Having driven such a number to one of the selected k places by turning, we will not allow Ali Baba to win on the next move. The case when N is even but has an odd divisor m is reduced to the following. Let's mark m equally spaced places on the big circle and forget about the rest. Acting as described

NUMBER ISSUED

D.N.Grishukova, A.E.Patskhveria, V.M.Khlebnikova, P.I.Chernusky

FICTION EDITOR

E.V.Morozova

COMPUTER GROUP

E.A.Mitchenko, L.V.Kalinicheva

The magazine «Kvant» is registered with the Russian Press Committee. Reg. St. No. 0110473

Editorial address: 119296 Moscow, Leninsky Prospekt, 64-A, «Kvant» Tel.: 930-56-48 E-mail: admin@kvant.info, math@kvant.info, phys@kvant.info Website: kvant.info

Printed at OJSC Order of the Red Banner of Labor "Chekhov Printing Plant" 142300 Chekhov, Moscow region, Website: www.chpk.ru E-mail: marketing@chpk.ru Fax: 8(49672) 6-25-36, fax: 8(499) 270-73-00 Multi-channel service sales department: 8(499) 270-73-59
