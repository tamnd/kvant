---
id: 1987-12-duvanov-pervin-yazyik-logo-10c6fc2f
issue: kvant_1987_12
year: 1987
number: "12"
title: Language Logo
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 40
page_last: 43
page_labels: 38-41
tag: 0CGP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a6f6259e0c555317f0c8cfa0a3a41279ae44bc6c63747f396efb103079e6172
prompt_sha256: draft-1
translated_from: content/ru/1987/12/articles/10_duvanov-pervin-yazyik-logo-10c6fc2f.md
source_content_sha256: 06ad9f09150fb71b69255b277de9b8c52a2577a7002ef725479cf3960b1d0f71
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Language Logo
Lesson 3: Recursions, functions

A. A. DUVANOV,
Yu. A. PERVIN

Everything returns to normal
Carrying out the CIRCLE process
(see Lesson 2 in the last issue «Kvant»), The turtle lives one full turn and remains. Enjoy watching her run on the display screen! Therefore, I want to make her spin again and again. Here's how to do it:

THIS IS A CARUSEL :R
CIRCUM :R
CARUSEL :R
END

This procedure has a non-privileged description: it includes a call to the same procedure. A procedure that calls itself is called recursive, and its call is called recursive. You can often and unexpectedly encounter recursions even away from computer science lessons. Artists love figure-jokes: figure shows a tritel watching a TV screen, on which a tritel is visible looking at the screen... etc. An example of “linterature” recursion is a portentous poem about a priest who had a dog.

By calling the recursive procedure CARUSEL, you can see that it is not so good: it makes the poor Turtle run around in circles without stopping... while the car is on.

To stop a Turtle controlled by a recursive procedure, you must be able to find the number of laps completed and compare this variable with a given value. If you take a variable named COUNTER as a lap counter, you can keep track of laps using the command

MAKE “COUNTER:COUNTER+1,
which should be included in the description of the CARUSEL procedure immediately after the call CIRCLE : R (you will apparently have to execute the command at the very beginning for the intended program to work correctly

MAKE “COUNT 0;
Why?).

But in order to compare two values, you need a new one

⟦folio 39⟧

team. The conditional command has the form ECIF conditions [list-1 commands] [list-2 commands]

The lists of commands in square brackets represent one of two possible continuations of the program: in the case when the conditions written after the word ECLI are true, the commands in the first list are executed (and the entire second list is skipped!), and vice versa, if the conditions are false, the first list is skipped and the commands in the second list are executed. A condition (more precisely, simple conditions) are two expressions connected by relation signs “<”, “>”, “>=” (greater than or equal to), “<=” (less than or equal to), “=”, “/=” (not equal). Defining a condition in this way can be either true or false. For example, the conditions of the command ECIF: $R/2 > 3.14*2$ [FORWARD 50] [BACK 50] first calculates the truth of the condition at the current value $R$, and upon receiving a positive answer, sends the Turtle forward, and otherwise sends it back.

A shortened form of command conditions (with one list) is acceptable: IF conditions [list of commands]

Then, if the condition is true, the list command is executed, and if the condition is false, then the machine... does nothing, but simply moves on to executing the next program command, if there is one. We will use this form of command to solve the problem, forcing the Turtle to corner in a circle, for example, 17 times. To do this, you need to write a description of the procedure

this is a WALK :$R$
MAKE "COUNT 0"
CARUSEL :$R$
END

the description of the CARUSEL procedure will look like

this is CARUSEL :$R$
CIRCUM:$R$
MAKE “COUNTER:COUNTER+1”
IF COUNTER<17 [CAROUSEL :$R$]
END

This time, the CAROUSEL procedure, although it remains recursive, is not called every time, but only if the value of the COUNTER variable does not exceed 17. Note that in the WALK process it was necessary to preset the initial value of the counter to zero. Such a program, after completing its work, will leave the COUNTER variable equal to 17. Variables that are not parameters of the procedure and are used both within the procedure and in the program calling it under the same name and with the same values ​​are called global (compare with the definition of a local variable at the previous level). The COUNTER variable in the last example is global. Therefore, the programmer must be aware that a call to the WALK procedure may change the value of the global variable COUNTER that existed before the call. You can get away from this limitation by making the COUNTER a procedure parameter: parameters are always local. This procedure is described

this is CARUSEL :$R$ :COUNTER
CIRCUM:$R$
MAKE “COUNTER:COUNTER+1”
ECIF :COUNTER<17 [CAROUSEL :$R$]
END

Now the WALK returns procedure is not needed. Call CARUSEL 50 0

provides 17-fold movement in a circle with a radius of 50. The program is not spared from assigning the initial value, but now it does this not as a separate command, but as the set value of the actual parameter.

Task 1. Rewrite the CAROUSEL procedure so that the Turtle can run around any given number of circles.

In the last lesson, we saw that whenever the number of identical actions to be repeated is known, we can use the REPEAT command. This means we can do this in our Fig. 1.

⟦folio 40⟧

a simple task - a Turtle walk around the circle.

Task 2. Change the CARUSEL program again, eliminating the recursion and using the loop command.

"Recursive" figure on p. We will not program 38. But part of it - rectangles inside rectangles (Fig. 1) - is easy to query:

THIS IS A RECURSION :SIDE
REPEAT 2 [B: R SIDE 90 V
1.5 * :SIDE P 90]
NS V:SIDE / 2 P 90 V
1.5 * :SIDE / 2 L 90 RUR
MAKE “SIDE:SIDE * 0.4
RECURSION :SIDE
END

This routine will draw nested rectangles without stopping. The very last (but endlessly repeatable!) rectangle is drawn with the minimum SIDE value, at which the condition SIDE > 1 is still satisfied. How to stop the procedure?

Figure 2, a-z are performed by the recursive procedure SPIRAL with two parameters.

Problem 3. Follow the description of the SPIRAL procedure, reproducing figure 2, a-z.

Procedures and functions

Let us introduce the concept of *prescription* as a certain order given to a machine in a form understandable to it. We will call such instructions as FORWARD, forcing the machine to perform certain actions without calculating the results, *commands*, and also, like “+”, calculating values ​​- *operations*.

The set of counter commands in Logo is relatively small. By describing procedures, we announce new commands to the machine. For example, you can enter the command
SQUARE α
I draw a square from side α (α is an arithmetic expression). To do this, it is enough to know the description in the computer memory

THIS IS A SQUARE :A
REPEAT 4 [FORWARD :A RIGHT 90]
END

When executing a command (or procedure), the computer performs some actions - moves the Turtle, displays messages on the screen, organizes repetitions. When performing the ico operation, the machine not only performs the prescribed actions, but also (this is the main thing!) produces as a result a certain single value (sum, difference, ...).

We have already used arithmetic operations: addition, subtraction, multiplication, division. For more complex mathematical calculations, operations that calculate the values ​​of functions are required. In Logo, operations are also written in the form name α, (1)
where “name” is the function identifier, α is the expression that the function acts on, i.e., the operand of the operation. Operations and functions can have more than one operand.

Here are a few names reserved in the Logo to denote function elements: SIN - sine, COS - cosine, TAN - tangent, ARCTAN - arctigen, SQRT - square root, RND - function that generates a random number.

For example, the expression
$$\frac{\mathrm{tg} 2 + \sqrt{\sin a + 2}}{2}$$

will switch to Logo in the form
$$\frac{TAN 2 + SQRT(SIN :A + 2)}{2}.$$

The RND expression can be used as a case of random numbers from the interval (0; N-1).

For the familiar operations “+”, “—”, “*”, “/”, Logo also provides names: ADD for “+”, SUBTRACT for “—”, MULTIPLY for “*”, DIVIDE for “/”. These operations can also be written in form (1) with two operand parameters:
name αβ (α and β are arithmetic expressions).

⟦folio 41⟧

Thus, the expression $x+1$ can be written in the form
ADDITION :x1
To write expression (2) there is an equivalent:
SECTIONS FOLDED TAN 2 SQRT
ADD SIN :A 2 2

(the distance is externally consistent with notation forms (3) and (5)!). The recording of expressions in the form (4), when the name of the operation is placed before the operator, is called *prefix*, in contrast to the more familiar, *infix* recording, when the name (sign) of the operation is placed between the operator. For example, $2+3$ is an infix form of notation,
ADDITION 2 3 is a prefix form of writing the same operation.

Task 4. Rewrite the expression
$$\frac{\sqrt{\sin^2 a + \cos^2 a}}{a+1}$$

to Logo, using the prefix notation form.

The form of writing operations (1) and (4) makes them clearly applicable to commands and procedure calls. However, the ADD :A :B program (as well as :A+:B) will cause confusion on the computer - what to do with the result obtained? To avoid mistakes, remember that operations can only be used in expressions; For example:

![Diagram](image)

The LIMIT procedure uses Logo's built-in square root function SQRT. However, you can create your own functions in Logo, just as you do when describing procedures. The only difference between function descriptions and procedure descriptions is the mandatory presence of the RETURN $\alpha$ command in the function description.

This command returns the value of the expression $\alpha$ to the calling program as a result.

So, the description of the user (created by the programmer) function has the form

Fig. 3. Fig. 4.

Fig. 5.
