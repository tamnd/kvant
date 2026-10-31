---
id: 1972-5-kudryavskaya-lomakina-priz-mashina-posta-3c57ccb2
issue: kvant_1972_5
year: 1972
number: "5"
title: Post's machine
authors:
  - Кудрявская Н.
  - Ломакина И.
  - Приз С.
rubric: osnovnye-stati
page_first: 10
page_last: 14
page_labels: 8, 10, 12
tag: BO96
lang: en
source: kvant_digital
extraction: vision
content_sha256: 286cf72aa0ed3a511045544c67586813c72d13b96cd64e2ed40e2fe7a3cae58b
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/03_kudryavskaya-lomakina-priz-mashina-posta-3c57ccb2.md
source_content_sha256: 7b1c7af139690e69a04565f81c72428b02917b76df080ac8f0853a7600ac2846
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

Post's machine

In general, I must say, this is not a low car at all. This is, if you like, a drawing of a machine. And it would be even more correct to say - a story about a car. But if you tell, then tell first **).

Thirty-five years ago, two outstanding scientists appeared almost simultaneously in two mathematical journals (in the international “Journal of Symbolic Logic” published in the USA and in the “Proceedings of the London Mathematical Society”): the American Emil L. Post and the Englishman Alain M. Tyorinen,

*) The school is headed by Valentin Nikolaevich Kasatkin, author of the popular books “The ABCs of Cybernetics” and “The Secret of Cybernetics”. At the end of the article we present several problems sent to him.

**) The description of the “Post machine” given here belongs to Yu. A. Gastev.

dedicated to clarifying the concept of an algorithm (or algorithm *) that has long been used in mathematics (and not only in mathematics). An algorithm is a single general method designed to solve a whole series of single-pline problems. Unified - in the sense that, knowing the corresponding algorithm, we can solve each problem from a given series without any additional understanding, as they say, “purely mechanical”, “format”.

“Formally”, “insanely”, “mechanical” - these words often include a rather offensive meaning. And almost always in vain! Judge for yourself: figuring out how to add any multi-digit numbers “in a column” for the first time was, of course, difficult.

*) The method of writing is determined only by traditions and attractions. If the letter θ (“phyta” is the same as the Greek “theta”) was preserved in the Russian language, then everyone would continue to write “algorθm”!

⟦folio 10⟧

not even Gauss needed the general concept of an algorithm. But to understand - and, moreover, to prove that there are unsolvable mass problems (that is, classes of problems that do not admit of any solution, uniform for the entire class *)), without such a general definition, of course, will not be possible.

No less significant is the purely “positive” value of the general concept of an algorithm: understanding the general laws that govern the most diverse algorithms plays a primary role for “machine” mathematics. As is known, a universal electronic computer is “capable of accepting” programs for a wide variety of mathematical (and not only mathematical) problems**). A machine program is an algorithm, only in addition adapted to the characteristics of a given specific machine (or written in a special “programming language”; we allow “broadcasting”, that is, simply translation, into the command languages ​​of different machines).

Already the first works of Thorig and Post, devoted to teaching the concept of algorithm, made it possible to make significant progress in both of these directions. The direct motivation for such studies in both cases was the desire to establish the algorithmic unsolvability of certain mathematical mass problems (and it was Post who was responsible for the first results in this direction). It is curious that both scientists followed essentially the same path (it soon became clear that this path is not the only

*) On algorithmic unsolvable problems, see, for example, the article by F.L. Varrakhovsky and A.N. Kolmogorov “On the solution of Hilbert’s tenth problems” («Kvant», No. 7, 1970).

**) See, for example, the article by R. S. Guter “What machines could do” («Kvant», No. 5, 1970) and “The language of man and the language of machines” («Kvant», No. 10, 1971).

but possible): together with intuitively understandable, but absolutely unsuitable for extracting exact mathematical consequences, talk about “a single society, ready to solve a whole series of similar problems” (see the beginning of this note), Törig and Post put forward the idea of an algorithm as a kind of abstract (mental) “machine”, described in precise mathematical terms and at the same time corresponding to our ideas about the computational process, proceeding according to the rules-commands definition of the standard type.

Which exact definition of an algorithm is accepted - Tyoriga, Post, or that belonging to someone else (the best known are the definitions of K. Gödel, A. Church, S. K. Kleene, A. A. Markov, A. N. Kolmogorov) - is unimportant: it soon became clear that all these definitions are equivalent in the definition sense. Therefore, the choice of any one of these teachings as the initial definition is not for the mathematical side of the matter, but for the convenience of presentation.

“Tyorig’s machine” is described in both service and popular books *).

The “Post machine” was less fortunate in this regard, perhaps because this “machine”, being simpler than the “Tyorig machine”, precisely for this reason requires, generally speaking, a more cumbersome command system to perform a specific task. Apart from a single article by Post himself, this teaching of the concept of algorithm is described, in fact, only in one place: in a series of four articles by V. A. Uspensky in the magazine “Matematika at School” for 1967. Referring the reader to these very interesting (and clearly written) articles, we now provide only the most basic information about the “Post machine” necessary for further understanding.

*) Of these numbers, we first of all recommend to the reader the book by B. A. Trakhtenbrot “Algorithms and machine problem solving”, Fizmatiz, 1960, 2nd ed.

⟦folio 12⟧

1) machine doit do an impossible command (printing a mark in a canceled section or erasing a mark from an empty section) - the so-called ineffective stop;
2) machine doit do stop command - the result of the stop;
3) neither of the first two cases will come true - the machine will work indefinitely.
Example 1. In the program
1. ⇒2
2. ξ 3
3. stop,
applied to an empty tape, an ineffective stop will occur already at the second step. (so until the prescribed third command, the resultant stop is still not done).
Example 2. Program
1. ⇒2
2. ⇒3
3. stop,
applied to an empty tape will perform as follows: the carriage will move two sections to the right of the one being viewed, after which the machine will stop.
Example 3. If the program
1. ∨ 2
2. ⇒3
3. ⇒1
apply to an empty tape, then the machine will print, starting from the section being viewed, one label at a time, and will not stop at all.
The reader will find further examples in the already mentioned statues of V. A. Uspensky.
We will now give the floor to the participants of the school of young cybernetics of the “Small Academy of Sciences”, 9th grade students of Bakhchisarai school No. 2 Natasha Kudryavskaya, Ira Lomakina and Svetlana Priz, who will tell you about their experience of learning programming using Post machines (the work of which, in a highly simplified form, will reproduce the work of any modern universal computer). The girls tested their programs on a program made by a Higher Education employee.

Fusion center of the Simferopol Pedagogical Institute of a metal model, attached keys, toggle switches, plugs and other indispensable attributes of “cybernetic machines”. The “tape” in this “operating model” consists of electronic light bulbs (40 pieces; going beyond the limits of the tape is qualified as an unsuccessful stop of the machine), and the marked sections light up, and the marked sections go out *).

It is very interesting to program and see how, obeying your program, the machine solves problems. The command counter allows you to see which command is currently running. The program is first written on paper, and then, using plugs, it is recorded on the typesetting field of the machines (each command has its own double code). The machine does not work (in automatic mode) very quickly, so all actions are clearly visible; execution of the program can be paused.

It is interesting to observe how the machine acts as the content of a person in various games. We also solve problems in creating programs that the machine cannot use **). Here is an example of such a program. Game conditions: there are 26 marks in a row on the tape, the leftmost of which is visible with a card. The person and the machine take turns (the person always starts the game), erasing no more than four marks during their turn. The one who erases the last mark loses. If the conditions

*) We deliberately did not dwell on all these impressive details, so as not to distract the reader from the day’s work; The difference between the “electronic model of Post’s machine” and the “match paper” model described above is approximately the same as the difference between store receipts printed on an electronic or manual cash register and those written out by hand.
**) That is, he always wins: all these games are such that they do not allow a draw outcome.
