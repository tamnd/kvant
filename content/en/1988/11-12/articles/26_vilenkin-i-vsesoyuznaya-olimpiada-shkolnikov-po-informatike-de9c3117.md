---
id: 1988-11-12-vilenkin-i-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-de9c3117
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: I All-Union Olympiad for Schoolchildren in Informatics
authors:
  - Виленкин А. Н.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 84
page_last: 86
page_labels: 82-84
tag: Z98W
lang: en
source: kvant_digital
extraction: vision
content_sha256: b5dd6d1eeb9c13740138843db072954debb8f72bad290a8fb4ef3e1a77bebee0
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/26_vilenkin-i-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-de9c3117.md
source_content_sha256: e959b3397dafd94ad51728a7eee0dddfd52a1bd473bdd4623c7e0c0da1579a7e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 82⟧

I All-Russian Olympiad for Schoolchildren in Computer Science

A. N. VILENKIN

The final stage of the I All-Union Olympiad for schoolchildren in computer science was held in Sverdlovsk from April 13 to April 20, 1988. 80 schoolchildren from all union resource centers came together to test their strength.

The grand opening of the Olympiad took place on April 14 at the Ural Palace of Culture - modern, simple and comfortable. The participants of the Olympiad were greeted by the head of the department of science and educational institutions of the regional CPSU A.G. Zhdanovich, academician G.S. Poselov, representative of the central organizing committee of the All-Union Olympiad for schoolchildren T.A. Sarycheva and others. Zhorgi Olympiad was headed by academician N. N. Krasovsky, the organizing committee was deputy. Chairman of Sverdlovsk Public Education A. A. Leonov. On the same day, schoolchildren began to get acquainted with the computer technology on which they had to work. Sverdlovsk residents presented more than 80 Robotron-1715 computers for the Olympiad. Almost everyone had to work without working, which put the Olympiad participants in an equal position. On the other hand, these computers were the ones from which the participants of the Olympiad were promised to work, and in two days (April 14 and 16) the technical work was completed.

The Olympics took place in two rounds. The theoretical round took place on April 15. 4 problems were proposed, the solution to which took three and a half hours. At the same time, algorithms were allowed to be written in any fairly common programming language (algorithmic information language, Pascal, Rapier, BASIC, Algol, Fortran, C, etc.). The task of composing an algorithm was considered solved if the presented algorithm was correct. Additional points were awarded for the simplicity and originality of the algorithm, justification for its correctness, the presence of comments, and for efficiency (low operating time, using memory). When checking a task, the score (0-5 points) was multiplied by a coefficient characterizing the difficulty of the task (it depends on the number of participants who solved this problem); this coefficient is given in parentheses after the problem number.

Theoretical type problems

T1 (*7). The algorithm is given:
alg problemsal (integer n)
arg n
start int k, i
k:=n
i:=2
while k≠1
nc
if remainder (k, i)=0
then print (i)
k:=k/i
otherwise i:=i+1
All
kts
con

The print (i) command prints the number i; remainder (k, i) is the remainder when k is divided by i. What numbers will be printed when using the problemal(n) algorithm for an integer n≥1? Justify your answer.

T2 (*6). For a rectangle whose sides are parallel to the coordinate axes, we will specify the coordinates of its lower left and upper right corners. (In total, therefore, for the rectangle problem you will need 4 numbers). Two rectangles Pr1 and Pr2 are given. Determine the area of ​​that part of the rectangle Pr1 that is not included in Pr2. (The algorithm must be suitable for all options for the location of Pr1 and Pr2.)

T3 (*9). The country has n cities, numbered from 1 to n; There are air connections between some of them. The table is_flight [1:n, 1:n], contains information about flights: is_flight [i, j] equals 1 if i≠j and there is a flight from city i to city j, and equals 0 otherwise. (The flight does not have intermediate stops; the presence of a flight from i to j does not guarantee the availability of a flight from j to i). It is known that:
1) from any city you can get to any other (possibly with transfers);
2) There are as many flights arriving in any city as there are departing (the i-th column of the table has_flight the same number of units, the column is in the i-th row).
Prove that you can fly out of a small city and use exactly

⟦folio 83⟧

Theoretical tour.
Machine tour.
Winners of the Olympiad and prize winners «Kvant» (from left to right): S. Kovalev, V. Kalashnikov, V. Zavalishin, G. Nischanov, I. Ovcharenko, S. Kalinitsenko, M. Plukas, A. Vashillo.

⟦folio 84⟧

once on each flight, return to the same city. Create an algorithm for finding such a route.

(There is an algorithm that requires the execution of no more than $Cn^4$ commands for some constant $C$, independent of $n$).

T4 (*10). 3,000,000 people with different surnames stood at each other's heads. Everyone, except the first, wrote on a piece of paper the last name of the person standing in front of him and his own last name. All 2,999,999 pieces of paper were mixed and the information (ordered pairs of surnames) was recorded on magnetic tape. How can you quickly find out the last name of the 1,234,567th person? At your disposal is a computer with a small RAM (64 KB) and a limited number of tape recorders (≤32).

The machine tour was held on April 17 at the training and production plant No. 9 and the Ural State University; programs could be written in BASIC or Pascal. In machine-type estimation problems, the result is available; using the computer was just a means. Additional assessment points include a statement of the solution method, its rationale, comments on the program, etc.

Machine tour problem

M1 (*3). The sequence of positive integers $a_0, a_1, a_2, \dots$ is constructed as follows: if $a_n$ is even, then $a_{n+1}=a_n/2$; if $a_n$ is odd, then $a_{n+1}=3a_n+1$.

Find the minimum $n$ for which $a_n=1$ if
a) $a_0=27$;
b) $a_0=2 000 007$.

M2 (*13). For each positive integer $n$ we will consider all possible representations of it in the form of the sum of one or several positive integer terms. Make a table in which for each $n$ the number of such representations is indicated (without taking into account the order: representations $3=2+1$ and $3=1+2$ are considered the same). For example, for $n=4$ such representations $5(4, 3+1, 2+2, 2+1+1, 1+1+1+1)$. (The further the table is filled out, the higher the work will be graded).

The analysis of the problems was carried out on the morning of April 18, and the appeal was considered in the evening of the same day. On April 19, a combinatorial festival took place at the Ural Palace of Culture. The Olympic participants, of course, brought with them a lot

floppy disks and cassettes with programs, and they wanted to show their programs, look at others and, perhaps, exchange software products. This is exactly the process dello at the festival. The organizers provided the schoolchildren and team leaders with different computers, and all available programs were demonstrated in action. Arrange 纵impads also showed their development programs for high school students.

The cultural program included a visit to Sverdlovsk museums and theaters, a circus, and a trip to the Europe-Asia border.

The awarding of the winner and the closing of the Olympiad took place on the evening of April 19. 5 schoolchildren received I degree diplomas (they scored 125-156 points), 9 schoolchildren received II degree diplomas (87-116 points) and 15 schoolchildren received III degree diplomas (59-78 points). 10 participants of the Olympiad were awarded special recognitions from scientific and public organizations, including prizes from the magazine «Kvant» for high mathematical culture of work - Zavalishin V. (Moscow, school No. 542), Kalinichenko S. (Kyiv, school No. 145), Kovalev S. (Gorky, school No. 40) and Ovcharenko I. (Khabarovsk, s.sh. No. 32).

What else remains to be said about this, the first All-Union Olympiad for schoolchildren in information? We must, first of all, congratulate and thank everyone who, at least to some extent, helped to overcome all the difficulties and organize and conduct the Olympics. We must congratulate the winner; in the very first corners of our country, Olympic work is intensifying in the field of information. The top of the Olympic school is marked.
