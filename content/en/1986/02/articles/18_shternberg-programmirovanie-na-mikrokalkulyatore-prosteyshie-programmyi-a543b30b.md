---
id: 1986-2-shternberg-programmirovanie-na-mikrokalkulyatore-prosteyshie-programmyi-a543b30b
issue: kvant_1986_2
year: 1986
number: "2"
title: 'Programming on a microcalculator: simple programs'
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 48
page_last: 50
page_labels: 46-48
tag: 9WI6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6db6974e04a3120f30918ab6ce034641786e5fb61f5cef3dfa40c399639d4b5b
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/18_shternberg-programmirovanie-na-mikrokalkulyatore-prosteyshie-programmyi-a543b30b.md
source_content_sha256: 925ba80d5790a310410ca8c22349d78e9aca36d620a55099c04a709eb022b1c1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

Programming on a microcalculator: simple programs

Candidate of Physical and Mathematical Sciences L. F. STERNBERG

This article, proposed for ninth-graders, describes how to translate (translate) the simplest (linear) programs written in an educational algorithmic language, in which the programming of a microcalculator (VZ-34, MK-56, MK-54). Thus, if you have access to such a microcalculator, the article will help you connect the school information course with the practice of programming.

Calculator operation. You have a programmable microcalculator in your hands. Can it be considered a computing machine, how small? Let's see.

— Memory capable of storing a program and data? - Yes.
— Is there a processor capable of automatically executing a program stored in memory and processing data without human intervention? - Yes.
— Do you have an input device? - Yes, keyboard.
— Do you have an input device? - Yes, an indicator.

So, a calculator is a computer. Of course, it is low-power and low-speed, but still allows you to perform quite server-side calculations and, what is most important for us, allows you to clearly understand what processes in any computer - both large and small. That's why we're going to program the calculator. But how to program it if it does not understand our algorithmic language, but only understands commands given by pressing a key? This means that we need to learn how to translate algorithms from a convenient notation for us into calculator commands.

What does the calculator itself consist of and what does it have? Its structure*) is shown in figure 1. For now, let’s pay attention to the 14 memory resistors where the data will be stored; they have numbers 0,1...9, a, b, c, d (there weren’t enough numbers - did you take the letters); as well as two operational registers X and Y - it is on the contents of these resistors that operations are performed. We are not interested in other displays of the register. "Lights" connected to the X register indicate that the contents of X are being retrieved on the indicator.

Of course, you have already read the instructions for the calculator; you are also familiar with the engineering (non-programmable) calculator, so we will not describe the purpose of the keys and individual operations**). Let's try to work.

Given three sides of a triangle a=3, b=4, c=5, we need to calculate the cosine theorem for the angle opposite side a.

(Formula: cos a = $\frac{a^2+c^2-b}{2bc}$). We turn on the calculator and work with it in automatic mode, that is, as with a regular engineering calculator: we press the keys, and the calculator performs the following actions:

| Class | Ind. | Comments |
| :--- | :--- | :--- |
| 3 | 3 | enter the value a=3 |
| P 0 | 3 | in P0 (register 0) |
| 4 | 4 | enter the value b=4 |
| P 1 | 4 | in P1 |
| 5 | 5 | enter the value c=5 |
| P 2 | 5 | in P2 |
| Fx² | 25 | we square the value of c and call the value of b in X (c² goes to Y) |
| Fx² | 16 | square b=4 |
| + | 41 | we get b²+c² |
| IP 0 | 3 | call the value of a in X (the previous result is in Y) |
| Fx² | 9 | we get a² |
| — | 32 | get the numerator value and store it in P4 |
| 2 | 2 | starting to calculate 2 b c |
| IP 1 | 4 | ...
| × | 8 | ...
| IP 2 | 5 | ...
| × | 40 | calculated 2 b c |
| IP 4 | 32 | call the numerator in X |
| X→Y | 40 | swap X and Y (you need to divide by the denominator) |
| ÷ | 0.8 | we get the result |

* (The presentation is carried out in relation to the VZ-34, MK-56, MK-54 models).

**(See “Nuki and Life” No. 2, 4, 6, 8, 10, 12 (1984), No. 2, 4, 6 (1985), “Technology for Youth” No. 3 (1985), etc.)

⟦folio 47⟧

Fig. 1.

Now, by pressing the B/O, F, PRG keys, we will switch the calculator to program mode (two zeros will light up on the indicator in place of the order of the number), and then press the same keys in the same sequence, adding at the end the C/P key press (why it is needed, it will be explained further). Now pressing the keyboard will produce a completely different effect: the calculator does not perform the necessary actions, but remembers them. To do this, it has a special memory for commands, consisting of 98 cells, numbered from 0 to 97, and an address counter containing the number of the cell in which the next action will be recorded (see Fig. 1). Using the B/O (return to zero) key, zero is written to the address counter - this is what we see on the indicator after switching to program mode. Pressing a key (or a pair of keys), which in offline mode caused the execution of an action, now causes the numeric code of this action (command) to be written to a memory cell and the address counter to increase by one. The current values ​​of the address counter and the last three commands are visible on the indicator. So, our sequence of actions, turned into commands, ends up in keyboard pairs and is a program for a calculator. You can read it and, if necessary, correct errors - how to do this is well described in the instructions for the calculator.

Press F, ABT to return the calculator to offline mode. By pressing B/O, we will write a zero to the address counter (we do not see this zero on the indicator, but it will be written to the counter). Now the PP key will be pressed. Each press causes the execution of one command from the calculator pair - namely the one whose address is in the address counter; after this, the value in the counter increases by one and the next time you press it, the next command will be executed, the indicator will sequentially display the same values ​​that are given in the table. After the 22nd press we will see the result - 0.8.

This way you can check the program, but this is how it should be executed. To execute the program, there is a third mode - automatic. Press B/O, enter zero into the address counter, and press the C/P (Stop/Start) key. Now the calculator will also select one command from a pair, execute them and increment the address counter, but will no longer remain after each command. The results on the indicator will flash so quickly that they cannot be seen. In order to see the final result, you need to leave the automatic operation - for this we wrote the C/P command at the end of the program - when it is executed, the calculator goes from automatic to offline mode and you can see the result.

So, our performer - a microcalculator - can work
— in offline mode, executing commands as they are given from the keyboard;
— in program mode, storing commands given from the keyboard;
— in automatic mode, executing commands into memory.

⟦folio 48⟧

Transitions from modes to modes are completed using classes F, PRG, AVT and SP as shown in figure 2.

We program a linear algorithm. Our performer understands the entire peculiar language - the language of classy clicks; for us, recording in an algorithmic language is more convenient and accustomed (see «Kvant» 1985, No. 9, 10). To successfully program a classifier, we need to learn how to translate a program from an algorithmic language into a classifier language - as professional programs say: translate it into classifier code (from the English translate - translate). Generally speaking, a modern computer understands all the original code, but it has its own “built-in” translator that translates a program from a programming language into its code. For the classifier, this will have to be done manually.

Let's write our program in an algorithmic language.

alg COSINE
(things a, b, c, k)
apr a, b, c
res k
start weight k
k := b² + c² - a² / 2bc

con

Let us now formulate the translation (broadcast) rules.

1. Using the service word vesh (the classifier has no other types of variables), we will distribute memory registers for variables, recording in the table which register corresponds to a given variable.

2. To request a value, the classifier must stay and wait for the person to type the desired value, then run it into the appropriate register, then wait for the next value, etc. Thus, apr is programmed with a sequence of memory send instructions, separated by C/P instructions.

3. The assignment is programmed in a very different way.

4. If the deserved word results in only one parameter, there is no need to translate the result. If there are several such parameters, then at the end of the program, before the word con, you need to program the output of these parameters with a sequence of commands to call the X register

entered values, each of which is followed by a C/P command that applies the calculations.

5. Con is programmed by the C/P command.

Note that there may be several C/P commands in a program. When switching to automatic mode by command C/P, the address counter contains the address of the next command (this can be checked by pressing F, PRG, that is, it will go into program mode when the value of the address counter is visible on the indicator, then you will need to return to automatic mode by pressing F, ABT); If you now press C/P, then the command begins to be executed, the address of which is in the address counter, that is, the next one after C/P - the one calculated further.

Let's develop our program.

Address Code Com

a — P0
b — P1
c — P2
k — P3

00 40 P0
01 50 C/P
02 41 P1
03 50 C/P
04 42 P2

05 61 IP 1
06 22 F x²
07 62 IP 2
08 22 F x²

09 10 +
10 22 F x²
12 11 —
13 44 P4
14 02 2

15 61 IP 1
16 12

17 62 IP 2
18 12
19 64 IP 4
20 14 X↔Y

21 13 ÷

alg COSINE
things a, b, c, k)
alg a, b, c
res k

[Then enter a, b, c.] [Before the first sending you don’t have to put C/P (before the Russian program the classifier is in automatic mode), you need to enter the values ​​of a and press C/P]
k := (b² + c² - a²)/(2bc)
[We work strictly according to the formula: calculate the value of b², then c², add, etc.]
[It is clear that we will get the result, but we can do it faster: after entering X in the register, we can immediately use it.] [You can combine several commands, if you count like this: k := (b² + c² - a²)/2/b/c and program the value to 2, then to b and finally to c.]
We get the result. Don't forget to turn off the classifier!

So, it works according to purely format rules, we will get a program for the classifier, but it will not be optimal. On the one hand, on (For the end, see p. 57)
