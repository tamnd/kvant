---
id: 1979-11-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-cf7aedbc
issue: kvant_1979_11
year: 1979
number: "11"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 49
page_labels: 44-47
tag: FSNL
lang: en
source: kvant_digital
extraction: vision
content_sha256: fad454be1171899c1bc09a30a02ddc76f8260b01fdd0ffb539b7f6abbcf46cfe
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/14_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-cf7aedbc.md
source_content_sha256: 5ee79857822cdc7596987408e2c7018d8ef08d996f7c0043390d52399e4ef030
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

Correspondence School of Programming

Lesson 4: Arthmetic prescriptures of the Robik language.
Conditional and cyclic prescripts.
Procedures with parameters

In the Robik language you can perform arithmetic operations on numbers. For this purpose, the prescriptive words ADD and SUBTRACT are intended, the syntactic diagrams of which are given in their own table (p. 47). The meaning of these pre-scriptures is so obvious that we will not describe their work in detail, limiting ourselves to one small example: ADD 5 TO 10 AND ASSIGN A; SUBTRACT 3 FROM A AND ASSIGN TO B; ADD A WITH B AND ASSIGN TO B;
PRINT 'A-', A, 'B-', B;
This program will print the following line:

$$A = 15B = 27$$

Many may be surprised by the absence of multiplication and division operations in the middle prescripts of the language. The point is that Robik is a learning language, and creating procedures for multiplying and dividing numbers is an excellent learning exercise.

Task 4.1. Describe procedures that increase the value and division of the average prescripts of the language. And many times we assign the same name to the result.

One of the most important prescripts in any programming language is the conditional prescript, the structure of which is depicted in its own table.

Having encountered a conditional predescription in the text of the program, the computer first of all checks the conditions:

it is either false. If the condition is true, only the prescript after the word TO will be used. If the condition is false, only the prescript that appears after the word ELSE will be used (if this word is not in the prescript, then if the condition is false, the conditional prescript is simply skipped in this case).

For example, if the values ​​of the names A and B are some numbers, then predwrite IF A IS GREATER THAN B TO PRINT A ELSE PRINT B; will print the larger of these numbers (if the numbers are equal to each other, the second number will be printed, which otherwise coincides with the first).

Task about a crawling robot

Robot RO-1 must check the strength of joints on a new railway line. Having detected a faulty joint, the robot must report this to the operator on duty located at the station. RO-1 has to carry out all the prescriptive language Robik. In addition, its SPR includes the following prescript:

$$\text{ПРОЕХАТЬ} \quad \text{натуральное число}$$

and the list of acceptable conditions is supplemented by two:

$$\text{СТЫК НЕИСПРАВЕН} \quad \text{К}$$

$$\text{ВПЕРЕДИ ТУПИК} \quad \text{К}$$

The distance between joints is 24 meters. The branch ends in a dead end. Before starting work, the robot installs at the first joint of the branch being checked. Let's create a program.

Solution.

REMEMBER CHECKING PROCEDURE;
10 IF JOINT IS DEFECTIVE TO PRINT 'DEFECTIVE JOINT DETECTED';
20 GO 24 M;
30 CALL PROCEDURE CHECK;
FINISH PROCEDURE DESCRIPTION;
CALL PROCEDURE CHECK;

Let's see how to run this program. We will assume that the first and second joints are in good order, and that something is wrong with the third. When

⟦folio 45⟧

we will call the CHECK procedures for the first time, the robot will begin to execute operator number 10. This is a conditional operator, so PO-1 will first check the conditions:

JOINT IS DEFECTIVE

As we agreed, the first joint is good, so this condition is false and does not require turning everything over again. For the second, serviceable, junction, everything will be repeated exactly, but at the third junction, the condition in the tenth statement turns out to be true and the words appear on the screen of the terminal installed at the station:

FAULTY JOINT DETECTED

After this, the robot will again go to the twentieth operator, travel another 24 meters and start all over again. Everyone's okay. However, one unclear question remains: how long will the robot repeat this procedure? Judging by the program - ad infinitum. In reality, of course, the branch will end somewhere and the robot will run into a dead end. But this is an emergency situation. Let's try to prevent it: for this, it is very important that statements 20 and 30 are executed only in the case when there is no deadlock ahead. If a deadlock is detected, you can, for example, print the following message to the duty operator:

LINE CHECKED. RO-1 FINISHED WORK

Well, let's try to write a program like this:

REMEMBER CHECK;
10 IF THE JOINT IS DEFECTIVE TO PRINT 'DEFECTIVE JOINT DETECTED';
20 IF THERE IS A DEAD END AHEAD THEN PRINT 'LINE'

CHECKED. RO-1 FINISHED WORK. OTHERWISE...
STOP!! What, exactly, is ELSE?

After all, if there is no dead end ahead, we need to execute two statements at once: drive 24 meters and call the CHECK procedure, and, judging by the diagram, after the words TO and OTHERWISE there can only be one sentence.

However, there is a way out: we will describe a new procedure consisting of these two operators, and after the words ELSE we will simply put it in the call of this procedure:

REMEMBER RAIL;
10 ROLL 24 M;
20: CHECK;
FINISH;
REMEMBER CHECK;
10 IF THE JOINT IS DEFECTIVE TO PRINT 'DEFECTIVE JOINT DETECTED';
20 IF THERE IS A DEAD LOCK AHEAD TO PRINT 'LINE CHECKED. RO-1 FINISHED WORK. ELSE: RAIL;
FINISH;
:EXAMINATION;

Let’s complicate the task: suppose that the robot must print the number of the faulty joint every time. Check that this program, for example, is suitable for this:

VALUE 1 ASSIGN NAME H;
REMEMBER RAIL;
10 ROLL 24 M;
20 ADDITION 1 WITH N AND ASsign NAME TO N;
30: CHECK;
FINISH;
REMEMBER CHECK;
10 IF THE JOINT IS DEFECTIVE THEN PRINT 'JOINT NUMBER',H, 'DEFECTIVE'.
20 IF THERE IS A DEAD LOCK AHEAD TO PRINT 'LINE CHECKED. RO-1 FINISHED WORK. ELSE: RAIL;
FINISH;
:EXAMINATION;

Task 4.2. Robot PO-1 must also check society

⟦folio 46⟧

All joints are on a new branch. Having detected a faulty joint, the robot must indicate its number and distance to it (in meters). After completing the check, you need to place the joint when multiplying two natural numbers in the following form:

REMEMBER ACCOUNT;
10 ADD 1 TO MF AND ASSIGN TO MF;
20 ADD A WITH PR AND ASSIGN PR;
30 IF COUNT EQUAL TO THEN PRINT PR: ELSE COUNT;
FINISH;
REMEMBER MULTIPLY;
10 0 ASSIGN MF;
20 0 ASSIGN PR;
30 IF COUNT EQUAL TO THEN PRINT OTHERWISE: COUNT;
FINISH;

This procedure multiplies the values ​​of the names A and B and prints the product. Check this out with specific examples.

We have already encountered programs several times in which it was necessary to repeat the implementation of one or more instructions many times. This is not accidental: it is precisely such repetitive actions that it is advisable to entrust to automata, which is why repetition is very common among problems solved on a computer.

Until cxx, we organized repeating actions using operator conditions and procedure calls: a repeating procedure called itself until the comparison was successful. However, in Robik and in most other languages ​​there is a special instruction for organizing repetition - the Cyclic instruction (see the corresponding diagram - p. 47).

The way this construct works is that the clause after the word REPEAT will be used over and over again as long as the condition remains true. In other words, the machine works with this prescription like this: first, as in the conditions of the prescription, it is checked successfully. If it is false, then the order is not executed at all.

If the condition is true, then the instruction following the word REPEAT is executed, after which it is checked again successfully. If it remains true, then the prescription is fulfilled again - and so on until the condition is condensed. If and when it does not become false (and this is the case if the program is written incorrectly), then the machine will carry out the instructions again and again until it turns off or crashes - an unpleasant situation called looping will arise. We will come across examples in the following lessons.

Using the cyclic operator, the multiplication test can be written a little more elegantly:

REMEMBER ACCOUNT;
10 ADD 1 TO MF AND ASSIGN TO MF;
20 ADD A WITH PR AND ASSIGN PR;
FINISH;
REMEMBER MULTIPLY;
10 ASSIGN MF;
20 ASSIGN PR;
30 UNTIL THE COUNT IS LESS IN REPEAT :COUNT;
40 PRINT PRINT:
FINISH;

However, this procedure also has significant drawbacks: it only overwrites the values ​​of the names A and B. In order to overwrite the values ​​of other names, or just two numbers, they must be added to the names A and B.

This is not sufficient if you use the parameter mechanism. Parameters are the names that are listed in parentheses after the procedure name in the REMEMBER directive (look at the Procedure Remembering diagram in #10, page 57). The meanings of these names are listed in the same brackets when selecting a procedure. For example, if described

⟦folio 47⟧

Addition:
ADD expression C expression
AND ASSIGN name ;
TO

Subtraction:
SUBTRACT expression FROM expression
AND ASSIGN name ;
TO

Conditional offer:
IF condition TO unconditional clause
ELSE sentence K

Cyclic offer:
BYE condition REPEAT sentence K

Condition:
MORE LESS EQUAL NOT EQUAL

Beggarly words RABBIT start like this:
REMEMBER RABBIT (A, B, C);
then when calling this procedure we can write:

CALL PROSTER RABBIT
(10, 'TAIL', NOM);

In this case, name A will be given the value 10, name B will be given the value 'TAIL', and name C will be given the same value as the name NOM.

Let's try to describe the MULTIPLY procedure again - this time using parameters (the COUNT procedure remains unchanged):

REMEMBER MULTIPLY (A, B);
10 0 ASSIGN MF;
20 0 ASSIGN PR;
30 UNTIL THE COUNT IS LESS IN REPEAT: COUNT;
40 PRINT PR;
FINISH;

Now, in order for the variability to be 47 and 34, it is enough to write:
MULTIPLY(47, 34);
And calling the same procedure to re-

multiplying the values ​​of the names T and K will look like this:
:MULTIPLY (T, K);

Task 4.3. Describe the process of CASE with two parameters. The procedure must print both and the remainder of the division of the first parameter by the second, for example, when calling
:DEL(28.5);
The computer should print:
QUANTIATE=5, REMAINDER=3

Task 4.4. Describe a GCD procedure with two parameters for calculating the most common divisor of two natural numbers (see «Kvant», 1970, No. 9, p. 48).

So, we got acquainted with the basic constructions of the Robik language. Of course, this is an educational, simplified language, you can’t write a large program in it, but also concepts like operators and directives, and values, procedures and parameters, conditions, operators and loops, assignment and printing instructions will be very useful to us when studying more useful and interesting languages.

G. Zvenitsorodsky
