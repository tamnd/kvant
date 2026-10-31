---
id: 1989-12-kiryuhin-i-mezhdunarodnaya-olimpiada-po-informatike-7cd3837c
issue: kvant_1989_12
year: 1989
number: "12"
title: I International Olympiad in Informatics
authors:
  - Кирюхин В. М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 66
page_last: 67
page_labels: 64-65
tag: CHJV
lang: en
source: kvant_digital
extraction: vision
content_sha256: e8e8d6a62456d16c8bc51ab713c8d9a2af34c4ba9a472a68eba1ddb42bc8f9c9
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/16_kiryuhin-i-mezhdunarodnaya-olimpiada-po-informatike-7cd3837c.md
source_content_sha256: c5d45dbc59ffb2ca15f87664978e7cf8b6f519ad72157c7209719d94fd43cf33
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 64⟧

I International Olympiad in Computer Science

Candidate of Technical Sciences
V. M. KIRYUKHIN

This year, according to the decision of UNESCO, adopted on September 24, 1987, the I International Olympiad in Informatics was held. The Olympiad was held from May 15 to 20 in the People's Republic of Bulgaria, in the city of Pravets, and was timed to coincide with the third international congress “Children in the Information Age”.
Thirteen countries (Bulgaria, Hungary, Vietnam, East Germany, Greece, Zimbabe, China, Cuba, Poland, the Soviet Union, Germany, Czechoslovakia and Yugoslavia) sent their schoolchildren, whose age did not exceed 19 years, to the first International Olympiad in Informatics. According to the regulations of the Olympiad, each team could include a maximum of trope schoolchildren. All countries, with the exception of Hungary and Yugoslavia, took advantage of this right. Teams from Hungary and Yugoslavia were represented by two participants; Two teams from Bulgaria as the organizing country participated in the Olympiad. In addition, in addition to the national team of the Soviet Union, the team of Pereslavl-Zalessky and the team of the USSR Embassy in France also received an invitation to participate in the Olympiad.
The composition of the Soviet Union team was determined based on the results of the spring training camp, which took place in early May at the Youth Center of the Komsomol Central Committee “Olympian” in Khimki, and the II All-Union Olympiad in Informatics. As a result, our country was represented in Bulgaria by Ilya Dogolyatsky and Lev Novik, students of school No. 239 in Leningrad, and Andris Chaipyatis, students of school No. 28 in Kaunas. The team leader was the author of this article.

The Olympics were held in one round. At its meeting, the international jury, headed by Professor P. Kenderov (NRB) and which also included the leaders of all the teams, selected one of six pre-prepared problems. This problem was proposed for solution to all participants.

Task I MY
Given a sequence of 2N cells. The two adjacent ones are empty, and the rest contain N-1 symbols A and N-1 symbols B.
Example for N=5:

A | B | B | A | A | B | IN

Moving rule: the contents of any two adjacent non-empty cells can be moved to empty cells while maintaining their order.

Goal: Using the rules of movement, achieve a configuration in which all symbols A are located to the left of all symbols B. The location of empty cells after movement does not matter.

Exercise. Write a program that:
1) enters the initial configuration from the keyboard in the form of a sequence of symbols A, B and zeros for empty cells, and also simulates movements;
2) for a given initial configuration, defines at least one movement plan that can achieve the goal, or reports that no such plan exists (the output must contain the initial configuration, intermediate configurations after each step, and the final configuration);
3) finds some plan that reaches integer in the minimum number of steps.

Results: Provide at least one solution for the example above.

Four hours were allotted to solve the problem. Each participant was provided with a personal computer “Pravets-16” with the appropriate peripherals. They were also allowed to use their personal computers in the process of solving the problem, and the team of Germany and the USSR Embassy in France worked on the nomykomotechnics provided by them.

Each participant of the Olympiad had the right, when performing a task, to work with any software system included in the personal software

⟦folio 65⟧

computers: C, Pascal, BASIC, Logo, etc. Since when choosing the optimal task, taking into account its independence from the architecture of a particular personal computer, there was no need to use specialized software packages.

Upon completion of the solution to the optimization of each task, taking into account its independence from the architecture of a specific personal computer, the need to use specialized software packages and the results of its implementation obtained using a personal computer, as well as a floppy disk with the latest version of the program, source text and test results.

The decision was verified by members of the coordination commission and team leaders. The final summing up was carried out at a meeting of the international jury.

In the process of checking the tasks, programs were tested using four specialized members of the coordination commission and team leaders. The final summing up was carried out at a meeting of the international jury.

The decision was verified by members of the coordination commission and team leaders. The final summing up was carried out at a meeting of the international jury.

In the process of checking the tasks, programs were tested using four specialized members of the coordination commission and team leaders. The final summing up was carried out at a meeting of the international jury.

The winning optimization programs were also tested at $N > 5$ in order to further evaluate the effectiveness of the algorithm, although this was not entirely easy for the members of the international jury to do.

The solution to each optimization consideration during the execution of individual points of the task is to evaluate the corresponding 10, 40 and 40 points. The jury left 10 points at its disposal to encourage an original solution, technical programming and design of the program, etc.

When assessing the first task, 10 points began for the correct organization of data entry and the presence of a check for the correctness of the source data. For the second, finding at least one plan was scored 15 points or 20 points for finding if all plans were found; another 20 points were given for displaying a message about the lack of a solution. As for the third task, 15 points were given for the presence in the program of an attempt to minimize the number of steps and
