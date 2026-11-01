---
id: 1987-11-duvanov-pervin-yazyik-logo-068ce3a0
issue: kvant_1987_11
year: 1987
number: "11"
title: Language Logo
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 47
page_labels: 42-45
tag: KET6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 360c4105cfc73b4d8edbd0e815d3aae9a829f5a65a819b15b829dd3c8c07f230
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/18_duvanov-pervin-yazyik-logo-068ce3a0.md
source_content_sha256: daea37dfd21fce9016acfc89ca6a07cf289a8ae7cf6a51ab5b2fcb87907d7047
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Language Logo
Lesson 2: Cherenash Academy

A. A. DUVANOV, Y. A. PERVIN

Arithmetic Logo.
The computer, of course, must be able to calculate. We can type the command FORWARD 10+20 on the keyboard. The machine will add 10+20 and send the Turtle 30 steps forward. In all previously entered commands, arithmetic expressions can be used together with a specific number of steps or degrees of rotation. The machine will perform the actions specified in it, round the result to the nearest integer and use this number as a command parameter. So, the performer’s movements will be exactly the same when executing commands
BACK (100+20)/5 and BACK 24
RIGHT 30—200/(2+3) and RIGHT —10
LEFT 20/3 and LEFT 7.

In the Logo language, the following are used as signs of arithmetic operations:

+ addition operation;
— subtraction operation;
* multiplication operation;
/ division operation.

Parentheses serve, as usual, to control the order of actions. Expressions must be “stretched” into a string: (2+7)/5, and “multi-story” entries like $\frac{2+7}{5}$ are not allowed. This limitation is due to the fact that on a computer keyboard all symbols of an expression can only be typed sequentially. All signs in an arithmetic expression must be explicitly specified. Writing FORWARD (3+7)(40+30) will force the machine to recognize:
IT'S UNCLEAR WHAT IT IS (3+7)(40+30)
Correctly you should write: FORWARD (3+7)*(40+30). Decimal fractions in Logo are written as usual, but a dot is used instead of a comma to separate the fractional part.

Cherenakha equally mediates the commands:
FORWARD 2*(48+3)/2. 5 and FORWARD 40
RIGHT 180/3. 14 and RIGHT 57

All these, not entirely inculcating, correct recordings of arithmetic expressions have nothing to do with

⟦folio 43⟧

to the very subject of programming and are associated only with the imperfection of current machines, but because of this they become a severe necessity when it is actually necessary to set a program for a real computer.

Since a computer can count, it is natural that it should display the result of its calculations on the screen. In order to force the machine to print on the screen the result of dividing 25 by 4, just give it the command:
WRITE 25/4

When executing the command, the computer displays the result on the screen: 6.25. Please note, no rounding! The fact is that only the parameters of commands that force the Turtle to move are rounded. And in fact, the leading unit of movement is the number of “steps” - points on the screen, which must be an integer. The machine can already calculate (and produce) the result with very high accuracy.

Task 1 (to practice writing expressions). a) Write the BACK command without operation signs, performing the same actions as the BACK command (42*5/7—15)/7; b) Make the machine calculate an arithmetic expression

$$\frac{5}{6} \left( \frac{21}{0,56} + \frac{6}{19} \cdot 21,31 \right).$$

Much needed names

... My friend's name is Valentina. Isn't it a nice name?
...Kitty-kitty! Feropont, cat, come here.
... The quantity called x cannot take on the value of zero when it is the denominator of the fraction 1/x.
Names serve as a convenient means for identifying people, animals, objects, understandable, manifest, i.e., for highlighting a specific object among others of the same type as it. In programming languages, names are called identifiers. As in mathematics, they represent variables. The identifier in the Logo can be an arbitrary word, such as x1, SIDE or VASYA. An identifier, like a shortcut, places a certain area in the computer memory where the value of a variable is stored. To distinguish when we are talking about a named memory area, and when about its contents, in Logo, in the first case, quotation marks are placed before the variable identifier, and in the second, a colon. So, the entry “X” means the name of the variable X, and the entry :X is the value of this variable.

In Logo there is a special DO command, called the assignment command, with which you can assign values ​​to variables. For example, when executing the DO command, "X :X+1" will cause the value of the variable X to be incremented by 1, so that X will have the value 2.

So, the assignment command has three parts: the required (keyword) word DO, the variable identifier and the expression. This command first evaluates the argument expression. If it contains variables, then these values ​​from the corresponding memory areas are substituted into the expression. The result of the calculation becomes a variable, the identifier of which is located immediately after the word DO. Here's an example:

MAKE "VASYA 2"
MAKE “VASYA:VASYA +1
(variable VASYA gets the value 5). Let's consider another example related to geometry.

⟦folio 44⟧

Fig. 2.
MAKE “SIDE 100” MAKE “ANGLE 180”
REPEAT 4 [H :SIDE R :CORNER/2]
REPEAT 4 [H :SIDE/2 R :CORNER/2]

(two squares nested inside each other are drawn, with the lower left corner aligned).

Problem 2. Write a program to calculate the volume of the hangar shown in figure 1.

Procedures with a parameter

Doing arithmetic and wondering about names, we completely overwhelmed our Turtle, who draws very skillfully... if he is controlled correctly. Let's teach the Turtle to draw such a “pyramid” (Fig. 2).

The problem is solved by calling the PYRAMID procedure, the description of which has the form
this is a PYRAMID
PRIMOGLYNIK 1
HP V 10 P 90 V 20 L 90 R
PRIMOUGLYNIK2
NR V 10 P 90 V 10 L 90 R
PRIMOUGLYNIK3
NR V 10 P 90 V 5 L 90 R
PRIMOUGLYNIK4
END

Four “rectangular” procedures are used here:
this is PYRAMIDIC1
REPEAT 2 [B 10 P 90 B 80 P 90]
END
this is PYRAMIDIC2
REPEAT 2 [B 10 P 90 B 40 P 90]
END
this is PYRAMIDIC3
REPEAT 2 [B 10 P 90 B 20 P 90]
END
this is PYRAMIDIC4
REPEAT 2 [B 10 P 90 B 10 P 90]
END

They are very similar to each other.
In this case, you can write just one procedure with a parameter placed in the header of the procedure description and named, for example, SIDE. Then in the description of the procedure, together with the size of the side of the rectangle, the name SIDE will appear, denoting the value from the memory area placed in this way.

this is a PIMO CORNER: SIDE
REPEAT 2 [H 10 R 90 H :SIDE R 90]
END

A procedure parameter, which is the name of a variable, is called a procedure description parameter, or its formal parameter.

Our procedure is called for use using the command
PRIMOGLYNIK α,
where α is an arithmetic expression (specifically a number) called the actual procedure parameter, or call parameter. The call occurs like this: the formal parameter SIDE is allocated an area of ​​free memory (possibly different for each call); the actual parameter is calculated and its value is placed in the area allocated for the formal parameter; the commands of the procedure body are executed; after this, the memory area temporarily allocated for the parameter is declared free.

A variable for which memory space is allocated to each different one at the time a procedure is called is called a local variable of that procedure. The formal parameters of a procedure in Logo are local variables.

Several procedures below use formal parameters; this is not described for the program calling these procedures. Indeed, formal parameters are local, which means that, being occupied during execution, some memory is freed at its completion and can be used under any (including the same) name in other procedures. Thus, the local format allows you to distribute the compilation of a complex program, including the necessary text content of programmers. In the following example

this is A :X :Y
FORWARD :X RIGHT :Y FORWARD :X END
MAKE T 45
A :T :T*2
variables X, Y are formal, and expressions :T and :T*2 are actual parameters of procedure A. Corresponding

⟦folio 45⟧

The relationship between formal and actual parameters is positional: the first formal parameter corresponds to the first actual parameter, the second to the second, etc.

Let's return now to our primer. This is PRAMIDE
RECTANGLE 80
HP V 10 P 90 V 20 L 90 R
RECTANGLE 40
NR V 10 P 90 V 10 L 90 R
RECTANGLE 20 (1)
NR V 10 P 90 V 5 L 90 R
RECTANGLE 10
END

Problem 3. In program (1), the call to the RECTANGLE procedure is repeated four times, albeit with a different but regularly changing actual parameter. After analyzing the patterns of the program, write a description of the procedure with the parameter PRAMID:BASE, where the call to the RECTANGLE procedure would be carried out inside the loop. Suggest at least two options for this procedure. Explain which one and why you think is better. Use your program to draw base 120.

Programmers always try, whenever possible, to make their programs universal.

Task 4. Expand the capabilities of the previous program by describing a procedure that will draw a bridge with an arbitrary ring height. Using your new program, draw figure, composed of two primaids (Fig. 3).

Regular polygons

Drawing regular polygons with three, four, fifth, ... sides (Fig. 4), it is easy to see that with the possibility of the number of sides, the figure becomes more and more “round”. On a regular hexagon it is already done exactly like on a wheel, if it is small enough (Fig. 5)!

The angle of a regular $n$-gon is 180-360/$n$ degrees. This means that Cherenakha, after drawing each side, must rotate by an additional angle equal to 360/$n$ degrees. Here is a description of the procedure for constructing an arbitrary regular $n$-gon:

This is the CORRECT : $N$ :SIDE
REPEAT : $N$ :SIDE R 360/$N$

CALL
CORRECT 4 100
will draw a square with side 100 on the screen, and call
CORRECT 8 20
is a regular 360-gon with side 20. Finally, figure of a regular 360-gon with side 1 is a challenge
CORRECT 360 1

This is the presence of an approximation of a circle created by Cherenakha, which cannot turn at angles less than 1 degree, and move distances less than 1 snail's step. The length of this circle is 360 steps, and the radius is $R = 360/2 \pi$, i.e. approximately 57 steps. Its radius can be increased if the side is enlarged when using the RIGHT procedure. But you can reduce the radius only by reducing the number of sides of the polygon.

Task 5. Come up with a CIRCLE procedure with one parameter RADIUS. It should draw the possibility of a given radius. Cherenakhi's location on the screen is used as the center of a circle that the performer must return to after completing the drawing.
