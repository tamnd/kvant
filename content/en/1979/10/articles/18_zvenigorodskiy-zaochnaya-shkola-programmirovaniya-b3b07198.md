---
id: 1979-10-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-b3b07198
issue: kvant_1979_10
year: 1979
number: "10"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 58
page_labels: 54-56
tag: 2IO4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 69c0f331d081906e8f636ad28f7749996cd87c92346885632eef560dc094013a
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/18_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-b3b07198.md
source_content_sha256: b3d06dba08c6bb2554aca318a161e1fcd2cbf628d2652b17c1435fe3e693b363
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

Correspondence School of Programming

Lesson 3: Working with memory. Names and their meanings.

Procedures

When composing a program in large programming languages, including Robik, it is convenient to imagine the memory of a computer or robot as a set of separate blocks (Fig. 1), in each of which you can store a separate program (or part of it), a number, a line of text (remember task 2.4 from the previous lesson - «Kvant», 1979, No. 9, p. 57) or anything else. The name of a memory block (for brevity it is simply called a name; when describing some languages, other words are used in the same sense: identifier) ​​can be described by the following syntax diagram:

Let's decipher this diagram:

The name begins with a letter, followed by a random number of letters and numbers in random order. The set of values ​​of the Digit variable field is described in Lesson 2; for the Letter field we give a verbal definition: the value of this field can be any letter of the Russian or Latin alphabet.

Examples of names:
A15, CROCODILE, SPEED, V, LI, Q06P7, ALPHA

A few examples of typical mistakes when trying to write names: 6A12B (not starting with a letter). AB-1 (the hyphen “-” is not a letter or a number).

BLOCK NAME (this is not one name, but two) 'A5' (the apostrophe is not a letter).

If, for example, the number 15 is placed in a memory block with the name A, then the name A is said to be assigned the value 15.

You can read the meaning of a name as many times as you like, but if we assign a new meaning to this name, then the old one is lost forever. The Robik language has several clauses that allow you to assign meanings to names. The simplest of these is the assignment prescription. The syntax diagram for this instruction is shown in its table on p. 56 of this issue of the magazine. In the variable field "expression" can be either a number, or text, or a name, as specified in the same properties table.

Let's look at some assignment examples:
VALUE 5 ASSIGN NAME A;

Fig. 1

⟦folio 55⟧

VALUE STRING ASSIGN
NAME A;
VALUE 9.81 ASSIGN
NAMED ACCELERATION;
8 ASSIGN NAME A5;
A ASSIGN A5;
VALUE OF A ASSIGN A5;

Check out what all these examples cover in the diagram!

The abbreviated notation used in the last three examples is more convenient and compact than the full one, but at first we would recommend using the full notation in order to remember the meaning of the prescription.

If the value of the variable field “expression” on the left side of the prescription is assigned, i.e., to the left of the word ASSIGN, there is a number or text, then it is this number or this text that will be assigned to the name; indicated on the right. If a name is used as an expression, then the value of this name will be assigned.

Let's try to trace how the contents of memory blocks change when the above instructions are sequentially implemented. To do this, it is advisable for us to draw a table of name values. After performing the first assignment, this table will look like this:

| Name | meaning |
| :--- | :--- |
| A | 5 |

In other words, the name A at this moment has the value 5. After the second assignment, the name A will receive a new value. The old will be irretrievably lost. In the table we depict it like this:

| Name | meaning |
| :--- | :--- |
| A | 'LINE' |

It is most convenient to assign such tables with chalk on a blackboard, erase old values ​​and enter new ones. The expressions “erase from memory” and “record in memory” scales clearly convey the essence of what happened.

After completing the following three instructions, the table will look like this:

| Name | meaning |
| :--- | :--- |
| A | 'LINE' |
| acceleration | 9.81 |
| A5 | 'A' |

Let us now follow the implementation of the last instruction:

VALUE OF A ASSIGN A5;

There is a name on the left side of the prescription, which means we need to use its meaning.

This value will be named A5 along with the old text 'A'. After this assignment, the table takes on the following form:

| Name | meaning |
| :--- | :--- |
| A | 'LINE' |
| acceleration | 9.81 |
| A5 | 'A' |

The value of the “expression” field “works” in the same way in the PRINT instruction, the syntax diagram of which is given in its table: if the expression is a name, then the value of this name will be printed. (Recall that a name, unlike a text, cannot begin with an apostrophe.) For example, executing the instruction PRINT 5, A, A, A, 'A', '', 'A5', '-', A5, 'ALL', the line will appear on the terminal:

⟦folio 56⟧

5STROKASTROKASTROKAA A5-STROKAVSE

Please note that the text is printed without apostrophes!
Task 3.1. Let us find that we relate the computer to the program:
5 ASSIGN A;
'A' ASSIGN TO;
A ASSIGN TO C;
PRINT 'B = ', B, ' C = ', C;

Now it’s time to figure out how one could memorize a program or part of it into the computer’s memory, so as not to type all the instructions anew each time.

A program or part of a program that has a name is called a procedure; Procedures are intended for storage in computer memory.

In order for the computer to remember the program (place it in memory), you need to:
1. Type the instruction REMEMBER PROCEDURE and indicate the name of this procedure.
2. List all the instructions included in the procedure, indicating each of them with a serial number (natural number).

3. Type prescription FINISH PROCEDURE DESCRIPTION.

The syntax diagram “Memorizing the procedure” is shown in its own table (ignore the section of this diagram highlighted in blue for now).

For example, the program for the robotic RD-1 compiled in the first lesson can be remembered under the name CHANGE using the following sequence of instructions:

REMEMBER THE CHANGE PROCEDURE;
10 OPEN THE WINDOW;
20 WET THE RAG;
30 ERASE FROM THE BOARD;
60 SIT DOWN;
40 CLOSE THE WINDOW;
FINISH PROCEDURE DESCRIPTION;

In order for a procedure stored in memory to begin execution, it must be called using the CALL PROCEDURE instruction, the structure of which is shown in its table.

Assignment:
NON-PURPOSE EXPRESSION ASSIGN TO NAME Name
REMEMBER PROCEDURE Procedure name
parameter name natural number prescription
FINISH PROCEDURE DESCRIPTION

Calling the procedure:
CALL PROCEDURE Name EXPRESSION
Correction of the procedure:
CORRECT PROCEDURE Name
natural number prescription
FINISH EXPRESSION
Imprint:
PRINT EXPRESSION
Name
