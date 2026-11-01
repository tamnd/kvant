---
id: 1979-9-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1c81c0ee
issue: kvant_1979_9
year: 1979
number: "9"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 59
page_labels: 52, 53, 54, 55, 57
tag: RFIH
lang: en
source: kvant_digital
extraction: vision
content_sha256: bd409a4d8395dfe92bea9f618ee0ed00316f891e434a663ef20d72f15242c2fd
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/19_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1c81c0ee.md
source_content_sha256: c5b4aad025a878f4e62fad4ebce8e7849ed55b7a4635a36ba72c244d39ba639d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

Laws of programming.
Rules for writing prescripts in the Robik language
Correspondence School of Programming

Lesson 1

Programs written in most modern programming languages ​​consist of separate statements - just like texts in ordinary, “human” languages. Most readers «Kvant» probably remember that almost any preposition in Russian can be classified into one of three large groups: narrative, interrogative and exclamatory prepositions. It will be more convenient for Ham to consider prepositions to be called statements, questions and prescripts. We can say that a question is a proposition that can be answered. Examples of questions:

What is he like, this heffalump? Is it really very angry? Is he following the whistle? And, if so, why? Does he like piglets? And how does he love them?

A statement is a proposition about which it makes sense to ask whether it is true or false. Examples:

Winnie the Pooh lives well in the world!
2+2=4.

Matroskin the cat can’t answer the phone, he’s very busy, he’s lying on the stove.

A prescription is a proposal about which it makes sense to ask: how to implement it? Examples:

Please call Kota Matrosin to the phone!

Lift my eyelids!

Don't open your mouth, Piglet, otherwise soap will get into it.

Please tell me what time it is.

There is a widely known anecdote about a prominent physicist who, after giving a brilliant lecture, asked his employees if they had any questions.

“I don’t understand how you got this formula,” said one of those present.

“This is a statement, not a question,” answered the lecturer. - Do you have a question?

In most programming languages, an independent preposition can also be a preposition: if a robot needs to be given a task (and a program is, by definition, the food of a robot or computer), then each preposition must be such that it can be literally used - it must be a prescript.

You can tell the robot:

- Remember that 2+2=4.

No beccsmentally tell him:

2+2=4.

He simply won't know what to do with such a statement.

A brief statement of this rule is called the first law of programming:

The program consists of prescripts.

Obviously, to compile real programs for specific robots or computers, it is not enough to remember the formulation of the first law, despite its importance: you also need to know what prescripts these particular robots and machines have to use and by what rules these prescripts are written.

The instructions for any computing devices must list the instructions that can be used by these devices. Such a list is called the prescriptive system (abbreviated as SPR).

So: a system of prescripts is a set of prescripts that a robot or computer understands and can use.

For example, a system of prescripts for the robot RD-1, which can use

⟦folio 53⟧

at every school break, the responsibilities of the class monitor may look like this:

Pre-writing system RD-1

OPEN THE WINDOW; WET THE RAG;
CLOSE THE WINDOW; ERASE FROM THE BOARD;
SIT DOWN;

With pre-writing systems, there is a connection to the most important rule, which is called the second law of programming:

In programs for any robots and computers, you can use those and only those prescripts that are in their prescript systems.

A few words about grammatical rules. In programming languages, fortunately, there are much fewer of them than, for example, in the Russian language, but they must be observed very strictly. The computing machine holds back the strictest teacher, and one missing comma can hopelessly ruin the work of a large and beautiful program.

A robot or computer can be taught one or more programming languages. In this case, pre-scripts of this language (languages) are added to their SPR.

General rules prewriting begins on a new line.

2. At the end of the pre-writing there is a semicolon (;).

1. Each prescript starts on a new line.

2. At the end of the pre-writing there is a semicolon (;).

*) The Robik language described here is a shortened version of the Robik-3 language, which is used to teach schoolchildren at the Kharkov and Novosibirsk schools for young programs.

The attentive reader may be surprised by the lack of capitalization rules. This is explained simply: in order for a computer or robot to use prewriting, it must be typed on the keys of a terminal or other similar device, and the letters on the keyboard must be capitalized only; therefore, it is completely indifferent what letters will be written in the magazine; here we will write them in capitals and letters, but when completing our tasks, pre-writings can be written according to the rules of the Russian language: the first letter is capital, then lowercase.

Now, knowing the general rules for writing prescripts in the Robik language, we can compose the first program for the RD-1 robot described above, which must be erased from the docks and checked the class during recess.

Bot example of a correct program:

OPEN THE WINDOW;
WET THE RAG;
ERASE FROM THE BOARD;
CLOSE THE WINDOW;
SIT DOWN;

Task 1.1. Among the examples below are the correct memory requirements and all errors in other programs are listed.

Program A
1. ERASE FROM THE BOARD;
2. WET THE RAG;
3. OPEN THE WINDOW;
4. CLOSE THE WINDOW;
5. SIT DOWN;

Program B
WET THE RAG;
OPEN THE WINDOW;
ERASE FROM THE BOARD;

⟦folio 54⟧

CLOSE THE WINDOW;
SIT DOWN;

Program C
OPEN THE WINDOW;
WET THE RAG;
WIPE FROM THE BOARD;
SWEP THE FLOOR;
SIT AT YOUR DESK;

Program D
OPEN THE WINDOW;
WET THE RAG;
SIT DOWN;

Program E
WET THE RAG
ERASE FROM THE BOARD
SIT DOWN

Let's try to imagine how RD-1 will use our program. Let's assume that the robot is sitting at a desk in the classroom, and the Videoton-340 terminal is installed on the next desk. Dialogue starting robot. As soon as you press the switch, its first message appears on the terminal screen:
HELLO! I AM ROBOT RD-1!
I'M READY TO WORK!
After this, the robot displays an asterisk (*), which means that it is ready to receive the first prescription. We are recruiting

OPEN THE WINDOW;
After the semicolon, press the “ETX” key (this is an abbreviation of the English words “end of text” - end of text). Robot reads the line on the terminal screen and starts using it: gets up from its place, goes to the window, etc. When the order is fulfilled, the robot will stop and an asterisk will appear on the screen again. And so on until the end of the program.

If the system of regulations is small, it is often convenient to number the regulations and use these numbers to manage the complete text together. We will call such protected instructions commands. And the system of instructions turns into a system of commands. As an example, we give the command system of the Kibik self-propelled vehicle:

Command Instruction text

1 DRIVE 100 METERS
2 TURN RIGHT
3 TURN LEFT
0 FINISH JOB

Unlike the requirements of the Robik language, such commands can be written on one line. The program notation is compact, but difficult to understand: 1113113112111211211211211210.

Task 1.2. On a sheet of paper measuring 10 by 10 cm, draw the path traveled by Kibik when using this program, if the best coordinates are located in the lower left corner, the axis is parallel to the sides of the sheet, the scale is 1: 10000 (1 cm is 100 m), and at the initial moment Kibik is at a point with coordinates (800, 500) (in meters) and is directed upward, m. e. along the positive direction of the ordinam axis.

It is important to take into account that turns are performed by Kibik on the spot, and the right and left sides are determined by him in relation to the direction of his movement.

Task 1.3. Determine what program Kibik was executing if his path turned out to be maxim, as shown in figure 6*). The initial conditions, figure, are reduced by half.

Fig. 6.

*) Figure 6 was drawn by the plotter of the Shpar system (we will talk about this system in one of the following issues). Pupils of grades 3-4 A. Ershov, S. Pustoshilov and A. Filatova from the Novosibirsk School of Young Programmers were given the answer to task 1.3; Based on this answer, they compiled a program for Shpar’s graphic system, according to which figure 6 was drawn, i.e., Kibik’s work was “modelled.”

⟦folio 55⟧

Flexible Prescription Systems, Syntax Diagrams, and Variable Fields

Lesson 2

For general-purpose computers and robots that have large systems of instructions, the object of their instructions is of great importance. Until now, we have set the SPR in a “hard” way: by directly listing all permissible instructions. It is clear that this is far from the best way: defining large sets in a rigid way is inconvenient or impossible. It is impossible to describe in this way, for example, even the addition of arbitrary integers. After all, for each pair of numbers being added, a separate prescription must be provided in the SPR.

However, from the mathematics course we know that enumeration is not the only way to define a set. Much more often, a “flexible” description is used: a formula or rules are written that allow one to obtain all the elements of a set or check whether a non-actor object belongs to this set. The second lesson is devoted to one of the “flexible” ways of describing DSS - syntactic diagrams.

A syntax diagram is a rule for constructing a prescription, given in graphical form. The diagram shows which parts can be used to construct a prescription and in what order these parts should be arranged. A syntax diagram consists of individual fields connected by arrows. Each such field (usually a word, number or sign) is part of the prescription, and the arrows show in what order these parts can be connected. Each diagram has a starting point, denoted H, and an ending point, denoted K.

In order to obtain prescription rules using a syntactic diagram, you need to check

any path from the starting point to the ending point, moving strictly in the direction of the arrows, and writing down in a row all the fields encountered along this path. For example, syntax diagrams for the Kibik entry, described at the end of the first lesson, might look like this:

SCHEME 2

Please note that the second diagram describes two instructions at once: turn right and turn left. Since there are two ways to go from the starting point to the ending point, the program chooses the option that needs to be used in each specific case.

Another way to obtain different prescriptions from one diagram is to use variable fields.

A variable field is a part of a diagram that, when compiling a program, must be replaced with another text from a non-specified set. On syntactic diagrams, variable fields are denoted by ovals, and words and characters that need to be exactly rewritten into the program text (the so-called field post-wash) are denoted by a rectangle.

For example, in the DSS of one of the robots the following diagram may appear:

SCHEME 3

⟦folio 57⟧

Task 2.4. A variable field is described by the following diagram:

SCHEME 6

Here, a character is a letter, number, or any symbol available on the terminal keyboard, with the exception of the anostrophe (').

Example text:
'THIS IS THE CORRECT TEXT'
Give four examples of correct text and determine whether the diagram allows blank text'

Task 2.5. The variable field real number in the Robik language is described by the diagram:

SCHEME 7

(In programming languages, it is customary to separate the integer part from the fractional part using a period, and not a comma, as in school mathematics.) Which of the following real numbers are obtained from this diagram:
5.3—52.0 10.00000+50—54. +2,11/25.
Give four examples of correct notation for real numbers in Robik.

Task 2.6. Draw a synchronic diagram to describe the general mathematical form of writing real numbers. Please note that in mathematics an integer is a special case of a real number, but in Robik this is not the case: numbers without a fractional part should not be written off with a diagram.

Task 2.7. Draw a diagram for a variable field in Robik whose value can be an integer or a real number.

Task 2.8. The system of the prescribed robot Kibik-2 is described by the diagram:

SCHEME 8

Kibik-2 is located at point A (800, 500) and is deployed along the positive direction of the ordinate axis. He must visit points: B (800, 800), C (300, 200), D (925, 931) and return to point A.

After approaching the next point, Kibik-2 should display a message about this on the terminal, for example:
'I ARRIVED AT POINT A'
Create a program.

G. Zvenitsgorodsky
