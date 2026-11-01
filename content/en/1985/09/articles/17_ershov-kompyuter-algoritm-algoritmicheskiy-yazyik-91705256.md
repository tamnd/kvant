---
id: 1985-9-ershov-kompyuter-algoritm-algoritmicheskiy-yazyik-91705256
issue: kvant_1985_9
year: 1985
number: "9"
title: Computer - algorithm - algorithmic language
authors:
  - Ершов А. П.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 55
page_labels: 50-53
tag: GUYN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0dc194e688e0e9dda7935304ee2fd5305469bfc9d3ad848bf9374b0b73f1c6ab
prompt_sha256: draft-1
translated_from: content/ru/1985/09/articles/17_ershov-kompyuter-algoritm-algoritmicheskiy-yazyik-91705256.md
source_content_sha256: d27aab288230c1012009924e0dd6a0f0d0952d40a485a170be8e88dbfe4f0078
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

Due to the inclusion of the course “Fundamentals of Information and Computer Science” in the primary school curriculum since the 1985-86 school year, we are resuming the results of the publication in the “Art of Programming” section, opened on pages «Kvant» back in 1979. The materials we publish are intended to clarify, develop and deepen the school curriculum. We will begin this educational code with two articles by a member of our Editorial Council, Academician A.P. Ershov. The main goal of these articles is to teach how to write algorithms correctly. When reading them, you should pay attention to the words typed in italics - these are special informational terms, the exact meaning of which should be checked with a scientist.

Computer – algorithm – algorithmic language

Academician A. P. ERSHOV

Computers today and tomorrow

There is no need to prove how important computers are in our daily life. Already today, computers not only perform all kinds of calculations, they also distribute 苞airplanes, play chess, figure bodies of designed automation, compose music, judge sports performances, diagnose patients, control power plants. Moreover, the role of computers in society is growing more and more rapidly.

Our understanding of them is also changing: they are no longer internal piles of blinking light bulbs in huge cabinets, but rather modest - but elegant - hybrid TVs with a typewriter.

But in fact, a computer is, first of all, the thinnest medium of a silicon crystal, almost the size of a brand, entangled in a thread of the thinnest wires, which in the future will find a place in almost every industrial product. The scientific name for such a crystal is a microprocessor. The industrial production of microprocessors, in my deep conviction, is the most revolutionary technical innovation of the 20th century. And according to some futurologists, in a not very distant future, it will lead to the fact that social production will be mainly carried out by robots and controlled by computers, and most of the population will be busy writing programs to support them.

One way or another, people whose working lives will be spent mainly in the twenty-first century cannot be full-fledged members of society if they do not know how to communicate with a computer, if they have not crossed the threshold of second (computer) literacy. For this purpose, the school has introduced a new course “Fundamentals of Information Computing Technologies”.

The process of solving a scientific or practical problem on a computer is a joint work of man and machine. We'll start with a brief description of the main steps.

⟦folio 51⟧

Stages of solving a problem on a computer
1. Creating an Algorithm
First of all, it is necessary to find a suitable algorithm to solve the problem. Algorithms for server tasks are usually invented and written down by mathematicians or information specialists, sometimes entire teams of scientists. And in simpler cases, this will be done by programs - professional or...beginners. For many problems, good algorithms are already known - examples of such algorithms are in your textbook and will be given on pages «Kvant», but, as a rule, we will find a solution to the problem from the Japanese of a suitable algorithm.

2. Programming
In order for a computer to use the algorithm we have created, it must be written in the form of a program in one of the programming languages ​​that the machine understands. Programs are usually written in languages ​​such as Algorithm, Fortran, Basic, Pacal, Rancha. Ready-made, frequently used programs are stored in libraries of standard programs. In «Kvant» at the beginning we will write algorithms in an algorithmic language, the basics of which are outlined in your textbook.

3. Entering a program into a computer
At the present stage, there are two main ways to enter a written program into a computer. The first, obsolete method of use when working in batch mode: the program writes (encodes) in the form of perforations (holes) on punched cards, and a deck of punched cards is inserted into the machine. The second method is associated with working in interactive mode: the program or operator types the program on the display keyboard and at the same time monitors the correctness of the input on the screen.

4. Debugging the program
Obviously it turns out that the program has errors (this is almost always the case in large programs). Some errors (so-called syntax errors, or blocks) are immediately signaled by the computer when entering the program; others can be detected by the programmer when analyzing the results (testing or running the program). Debugging a program is the process of eliminating errors noticed in it. You cannot do this “manually” (without the help of a computer): to do this, you need to put yourself in the user’s place and try to “scroll through the program” in the simplest situations.

⟦folio 52⟧

5. Broadcast of the program
In order for a machine to execute a program entered into it or find an error, it must have a translator from the programming language in which the program is written. A translator—like an electronic translator—transforms program instructions into simple operations directly performed by a machine. Although creating the implementation of translators is a very complex job, requiring highly skilled system programmers, we will do something similar when working with a microcalculator.

6. Program Execution
In the traditional batch mode, the machine performs this stage of work itself, without human help: at colossal speed, the computer performs all the operations provided for by the industry-specific program, one after another. In some interactive programs, the computer can ask questions to the user while it is running and then continue working. One way or another, at this stage the owner is the car; here its superiority over humans in speed, accuracy, and precision is reflected.

7. Output of result
Modern computers are able to present the result of program execution in different forms. The result (number, text, table, figure) can be displayed on the display screen, printed on an ADPU (printing device), or drawn on a sheet of paper with a plotter. Some personal computers are equipped with an electronic sound simulator, on which they “play” the result when the results are a melody.

What if there is no computer?

We are primarily focusing on students who are starting to study information this school year at a school that has not yet established computing classrooms. Such students often ask: why write a program if it won’t run on a real computer anyway?

This question is very similar to this one - why write an essay if it won’t be sent to the printing house anyway? And the answer is approximately the same: computer literacy can be mastered without a machine, just as ordinary literacy can be mastered without typography.

However, your programming activities do not remain in the realm of pure theory in any case. If your school (or use) does not have mainframe computers, some of your programs can be run on a programmable microcalculator (for example, an Elektronka BZ-34 or MK-52), which you must have in your school.

⟦folio 53⟧

However, we will not strive to turn our readers into microcalculator programming virtuosos. The main thing for us will be the search for algorithms that solve certain problems, the ability to write a program in a special algorithmic language, described in your textbook. (As a rule, we will write programs on a microcalculator based on this algorithmic notation, that is, we ourselves will translate (translate) this notation into the operation codes of the calculator.)

Below you will see some examples of algorithms, and in the next article we will talk in more detail about writing them in algorithmic language.

Algorithms

The word “algorithm” comes from the name of the great medieval scientist al-Khorezmi (see “Quant”, 1984, No. 8, p. 29), but the enormous significance of this concept became clear only in the second half of the 20th century in connection with the development of computer technology and information technology. This concept definitely plays a role in mathematics (about this, see “Quant”, 1985, No. 7, p. 9) - the mathematical theory of algorithms is adjacent to one of the most famous areas of mathematics - mathematical logic. However, algorithms are also found in everyday life, moreover, at every step, under such names as “instructions”, “prescription”, “will solve”, “general method of solution” and the like. More precisely, we can say that an algorithm is a concept and an exact representation of a performer to perform a sequence of actions aimed at achieving a specific goal or solving a given problem.

The executor of the algorithm can be a person or an automatic device (computer, calculator, robot) capable of perceiving the order and performing the actions specified in it.

The principles of algorithms are not only many general mathematical techniques, such as adding numbers with a stolnik or algorithm

Euclid for finding N.O.D., but also culinary recipes, instructions on how to travel by public transport to a certain place, many operating manuals, also instructions on how to use an international telephone, individual instructions from military installations. Not every prescription, however, is an algorithm. Known from the world of fairy tales, “Go there, I don’t know where, bring that, I don’t know what,” of course, cannot be considered an algorithm: it is not accurate and understandable enough, and does not indicate a specific sequence of action. The same can be said about the general order to the intelligence officer “Act according to the situation!” The algorithm must provide for all situations that may arise during its execution and clearly indicate what to do in each of them.

Let's look at several examples of problems and algorithms that deliver their solutions.

The problem of finding the remainder. Given natural numbers x and y; you need to find the remainder when dividing x by y.

First algorithm (for the performer - a school student in grades 4-10):
— Write x and y side by side on one line;
- separate them with a corner;
— divide x by y with a corner to the number of units of the dividend (x);
— give the result of the last subtraction as a solution.

Second algorithm (for the performer - first class):
- Compare x and y;
— if x < y, give x as a solution;
— otherwise, I’ll subtract y from x and remember the difference;
— if the difference is less than y, give it as a solution;
