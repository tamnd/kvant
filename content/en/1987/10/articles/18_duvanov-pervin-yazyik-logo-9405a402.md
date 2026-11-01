---
id: 1987-10-duvanov-pervin-yazyik-logo-9405a402
issue: kvant_1987_10
year: 1987
number: "10"
title: Language Logo
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 54
page_labels: 48-52
tag: HEWM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6541c94ef99dfd80fce74c41c095af8f1d8c46cba19c864d73f8380e5eadc5c6
prompt_sha256: draft-1
translated_from: content/ru/1987/10/articles/18_duvanov-pervin-yazyik-logo-9405a402.md
source_content_sha256: 7b9e26209b22843c535383eb9c0f7a337eca072c9275763713387469ce76b7a3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

About the opening
All-round correspondence
programming schools

The Institute of Software Systems of the USSR Academy of Sciences opens an all-round correspondence school programming for schoolchildren and vocational school students, intersubstantialization of information, computers and programming. The goal of the School is to talk about the problems and prospects of information and basic programming techniques and areas of its application, to show ways of writing programs in several programming languages. Generally speaking, prior knowledge of computer science is not assumed, and yet in those cases where the authors of the lessons find it useful to compare a particular software tool with the algorithmic language on the basis of which the school course “Fundamentals of Computer Science and Computer Science”, grades 9-10, is built, the School lessons will not repeat the contents of the school textbook. The first four lessons of the School will be published in «Kvant».

Each lesson will include problems from several problems, the solutions of which should be sprinkled no later than a month after receiving the assignment. The School's curriculum is designed for two years.

The Correspondence School lesson is designed for students who do not have computer technology. Nevertheless, anyone who has the opportunity to check the correctness of his solution on a computer available to him is advised not to neglect this opportunity.

Those wishing to take part in the work of the All-Union Correspondence School of Programming must, before receiving the 11th issue of the journal, send their applications in the following form:

Language Logo

A. A. DUVANOV, Y. A. PERVIN

Lesson 1: Travels of the Turtle (simple Logo commands)

— Can you control the TV?
- Certainly! You need to turn it on to the network, select the desired channel, adjust the image and sound.
Just as easily, you can probably control a hair bike, a gas stove, a telephone and other familiar performers.
We live in a performer's world. All kinds of machines and mechanisms,

devices, simple and complex. We ourselves often act as performers. Executors are also restrictions, such as mail, kidney, store. In this executive world, one special type stands out - electronic computers. Their special role is to help manage other performers, very different in purpose and design. In this case, the computer acts as a mediator. A person from a machine remote control sets a program of actions for the performer in a special language of human-machine communication - a programming language. The machine's task is to convert phrases of this language into control signals and transmit them to the performer.

⟦folio 49⟧

What is the point of this mediation? Firstly, the programming language is much closer to natural language than electronic, magnetic or mechanical influences on the performer. Secondly, the machine allows you to memorize the program and “remember” it whenever you need it. Thirdly, using a programming language, you can specify not only simple sequences of commands, but also more complex actions: the performer can execute some commands only if certain conditions are met - conditional commands; the execution of others consists of repeated repetition of an action group - a cycle command. In fact, the computer has enormous speed - up to a billion operations per second or more; she does not know the established ones and, although she has an “iron”, but completely capable character: she is not familiar with resentment, arrogance, irritability and other purely human defects.

The first four lessons of the Correspondence School of Programming will introduce you to programming in the Logo language. This language is designed to control various simple executors. We will focus on one of them, traditionally called the Turtle. This performer lives on a plane. He can use it in different directions, leaving a trail behind him. You can imagine this performer realistically made of metal and plastic.

However, often such a performer is visible only on the display screen. It should be noted that this is a fairly typical situation. Many useful and necessary performers exist only in the form of models programmed on a computer. Their behavior can be observed on the screen. it may seem that they are useless because they are intangible, like signs. This opinion can be refuted by simply listing several actively used performers that exist only “inside” the machine.

- Mathematician. Capable of quickly and accurately performing enormous arithmetic and algebraic calculations.

— Text editor. Allows you to store, convert texts and print them in the required format.

— Editor figure. A convenient tool for creating pictures on the screen, including multitypes.

- Vomiter. Store ready-made figure, counting results, programs on magnetic tape or magnetic disk; maintains the archive.

The Turtle performer and the language for its control - Logo - were invented in 1969 by the famous American scientist S. Pipert. Logo quickly gained popularity around the world as a language for initial acquaintance with programming.

The easiest way to start learning programming is in your native language. There are so many versions of Logo: in American schools they use Logo, all of whose commands are written in English; Bulgarian proposers learn their actions using the Bulgarian version of the Logo. In our lessons, naturally, the performer understands only Russian words. The reader who wants to run the program application here on a computer accessible to him should read about this, if the English-language Logo is included in its software.

Attention! We turn on the computer. An image of the performer appears in the center of the screen in the form of a triangle-arrow pointing upward. This is the Turtle. Next to the screen is a keyboard. It’s the same as on a big machine, only the key on it is slightly larger.

Are you ready? The performer is waiting. Here are the first two commands in the Logo language: FORWARD n, BACK n. You can write the abbreviated V together FORWARD and N together BACKWARD, the car will appear. The number n—a command parameter—specifies the number of steps the executor will take. The Turtle has short legs: 10 of its steps - the terms of length units - are approximately 1 cm.

So, let's try to control:

⟦folio 50⟧

It worked! The turtle first moved and then returned to its original position. Traces of her passage remained on the screen.

Here are two more Logo commands: they control turns: RIGHT α, LEFT α. These commands (their valid abbreviations are P and L) force the performer to turn the corresponding one to the right or left by α degrees.

Let's make the Turtle walk along a square path:

The turtle is very obedient! Let's type another command BACK100 on the keyboard. The turtle did not move, but a message appeared on the screen: WHAT IS BACK100?

The fact is that in the Logo language, just like in the Russian language, words are separated by spaces. The machine tried to find the command BACK100 in its memory, but, of course, it was not there.

Let's fix it! We type on the keyboard: BACK 100. Now there is a flag on the screen (Fig. 1).

Problem 1*. Make a program for the Turtle to draw a boat (Fig. 2).

The SVROS command erases scoop marks from the screen and places the performer in the center of the screen with the nose up. Turning on the computer by executing this command. Let's draw an equilateral triangle. Each angle is 60 degrees. So he wants to write a program:

SVROS V 50 P 60
B 50 P 60
B 50 P 60

What do you think will turn out on screen? Triangle? So you were wrong, the Turtle will draw a figure like this (Fig. 3).

Did you see the error? In order for the interior angles of the triangle to be 60 degrees, each time you need to expand the Turtle by 120. This is what the correct program looks like:

SVROS V 50 P 120
B 50 P 120
B 50 P 120

Problem 2*. Describe the boat from problem 1 with a sail (Fig. 4).

The following two commands allow you to move the performer around the screen without leaving a trace (raise the drawing tool - “pencil”) and turn on the trace again at will (lower the pencil): DO NOT DRAW (save HP), DRAW (save P). Note that the operation of lowering the pencil is an integral part of the execution of the SVROS command.

Logo rules do not always coincide with the rules of the native language. If, from the point of view of the Russian language, it is correct to write DO NOT DRAW, then, having received such a command, the computer will again be surprised: WHAT IS NOT?

Problem 3*. What word will the Turtle write on the screen while executing the following program:

SVROS
V 40 L 45 N 20 P 90 V 20 L 45 N 40
HP P 90 V 20 L 90 R
V 40 N 40 P 45 V 50 L 40 N 40
HP P 90 V 20 L 90 R
V 40 P 90 V 30 P 90 V 20 P 90 V 30

I wonder what would happen to Turtle if we continued the incorrect triangle drawing program (see Fig. 1) and wrote:

SVROS V 50 P 60
B 50 P 60
B 50 P 60
B 50 P 60

It is clear that at the end of the path the Turtle is looking up, because it turned 60 degrees 6 times. Moreover, she ends up at the starting point.

⟦folio 51⟧

The turtle drew a regular hexagon! Note that figure is obtained by repeating two commands six times. Logo has a means for recording such repetitions more concisely - the loop command. The command looks like: REPEAT nl.

The number n specifies the number of repetitions. l is a list of commands (loop body), separated by square brackets.

Here's what a program looks like to draw a regular hexagon using the loop command:

RESET REPEAT 6 [B 50 P 60]
Problem 4*. Make a program to draw spruce (Fig. 5).

We forced to use draw a hexagon. Let's try to design: HEXAGON. You're right! The computer will again write the familiar:

WHAT IS A HEXAGON?
In general, everything is correct. After all, we did not tell her that the previously recorded set of commands is called HEXAGON.

You can learn to use the concept of new unfamiliar words and perceive them as commands using another command of the Logo language. A command beginning with the word THIS causes the machine to remember any program - a sequence of commands (or, in particular, one command) ending with the word END. It is to remember, not to perform! Following the word THIS, you need to write the name by which the machine will know the program to be remembered. Yes, record

THIS IS A HEXAGON
REPEAT 6 [B 50 P 60] (1)
END
There is a command for storing the program (here is a state from one command)

REPEAT 6 [B 50 P 60]
When executing the command THIS, the machine does not send any instructions to the performer and, therefore, the Turtle does not move. Indeed, the computer at this time is busy memorizing a program called HEXAGON. Under this we have this program can now be called for execution. To do this, just type the word on the keyboard
HEXAGON
and the Turtle will perform the already familiar drawing. Thus, the machine “learned” a new command - HEXAGON.

A program stored in the machine's memory and having a name by which it can be called for execution is called a procedure. Record (1), including the lines THIS IS A HEXAGON (blanks of the procedure description) and END (end of the description), is a description of the procedure, and the actual command of the program to be remembered (in our example, the line REPEAT 6 [B 50 P 60] is the body of the procedure).

Problem 5*. Make up a proedura drawing a house (Fig. 6).

Let's now try to draw exactly the latter - for example, oty for the stoves (Fig. 7).

Let's divide the drawing into three layers. The CELL procedure will look like:

THIS IS A HONEY HONEY
REPEAT 3 [LAYER]
END

Each layer (Fig. 8) will start drawing at point 1 and end at point 4. This ensures that the layers fit together correctly when executing the loop in the HONEYCOMB program.

THIS IS A LAYER
ROW
PODVODV3
ROW
PODVODV4
END

In the description of the LAYER procedure, calls to three, not yet programmed, procedures ROW, SUPPLY3, SUPPLY4 are used. You cannot call the LAYER proedura until they

⟦folio 52⟧

not described. Let us describe the ROW process:
THIS IS A ROW
REPEAT 8 [HEXAGON SUBMISSION] END

Although, apparently, it is clear what exactly the ROW process is tasked with doing, its description contains a call to another, not yet described, SUIT process. The SUPPLY procedure is necessary to install the Turtle to the place from which it should create a regular hexagon during the drawing of the row:

THIS IS A SUPPORT
NR L 60 N 50
L 60 N 50
P 120 R
END

Approach to point 3 consists of returning to point 1 and moving to point 3:

THIS IS A SUBWAY
HP RETURN
B 50 L 60
B 50 P 60 R
END

The return is made from point A to point 1 by calling the STEP BACK process nine times:

THIS IS A REFUND
REPEAT 9 [STEP BACK]
END

Let us describe the STEP BACK process:

IT'S A STEP BACK
L 120 V 50
P 60 V 50
P 60
END

It remains to describe the processes of PODVOD4:

THIS IS A SUPPORT4
RETURN
B 50 P 60
B 50 L 60
END

That's it! If you now clear the screen: RESET, and issue the command HONEY HONEY, you can see how the performer, carefully following our instructions, draws hexagonal cells.

Problem 6*. Create a program for drawing a) a street of 10 houses, such as in problem 5; 6) a village of five streets.

Problem 7. Create a program that will draw a LOBIC SUBMISSION] END

The example of drawing honeycombs shows a method for designing complex programs, called the “top-down” method in computer science. This method is similar to drawing `дерева` growing with its branches downward (Fig. 9).

When scheduling the HONEYCOMB process, we write a call to the LAYER processor. Now we begin to design the LAYER processor. It cannot do without the procedures RANGE, SUPPLY, SUPPLY4, etc. In other words, we start with the general outline of the problem, introducing commands to call non-existing procedures. Each such new command is described using a procedure, which, in turn, may contain calls to new, undescribed procedures, etc.

The tops of a tree that have no branches growing down are called leaves. For the program to work, all names on the sheets must be valid Logo language commands. In this sense, the tree at figure 9 is not complete.

Task 8. Additional drawing of HONEYCOMB so that the commands of the Logo language are written on the sheets.

Attention! We remind you that only problems 1–6 with asterisks will be checked.
