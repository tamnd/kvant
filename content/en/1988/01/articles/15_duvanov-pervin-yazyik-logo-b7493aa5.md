---
id: 1988-1-duvanov-pervin-yazyik-logo-b7493aa5
issue: kvant_1988_1
year: 1988
number: "1"
title: Language Logo
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 56
page_labels: 51-54
tag: XSHH
lang: en
source: kvant_digital
extraction: vision
content_sha256: aef6a973739cae5e63009fae1ffb45942563cafef9c1145f3910873b91fa946a
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/15_duvanov-pervin-yazyik-logo-b7493aa5.md
source_content_sha256: c623e1e50e0f76c39d585841df4e930b941160e53b7358fcff55fb0f955d7efe
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

Language Logo
A. A. DUVANOV, Y. A. PERVIN

Lesson 4:
Data structure in Logo

Algorithmic language and logo
Those readers who study information at school probably compare the algorithmic language described in the textbook and the one they know from «Kvant» Logo. It is easy to see the similarities of both languages ​​in graphics tools, condition commands, and assignment commands. The relationship between cycles in Logo and algorithmic language is more complicated. It is easy to move from the FOR loop in an algorithmic language to the REPEAT loop. Thus, you can calculate the volume of a “pyramid” made up of several wheels using the FOR loop:

V:=0
FOR R OT 10 TO 50 STEP 10
NC
V:=V+3.14*R**2*H
CC

This is programmed in Logo like this:
DO” V 0
REPEAT 5
[DO” V ADD MULTIPLY MULTIPLY R R H 3.14 V]

But the BYE cycle, which exists in the algorithmic language, has no direct analogue in Logo. In such a loop, a condition is always written after the word WHILE. This condition is the key that opens the entrance to the body of the loop: if the condition is true, then the loop commands are executed and the condition is checked again; if the condition is violated, the machine proceeds to execute the command following the cycle. The school computer science textbook provides an algorithm for calculating GCD using the WHILE loop. In order to implement actions in Logo that are repeated not a fixed number of times, but depending on

⟦folio 52⟧

some condition (including a variable), you need to use resources. Use this support to complete your next assignment.

Task 1. Write a function in Logo to calculate the gcd of two numbers.

The main similarity between the algorithmic language and Logo is the ability to compose descriptions of a complex action from simpler ones. Such descriptions in Logo are called *procedures*, and in algorithmic language - auxiliary algorithms. The concepts of *function* in common languages ​​are just as close.

It is important, however, to remain different. One such difference is the way the function value is returned to the calling program. In Logo, use the command *RETURN α* for this. It finishes executing the function and returns the value of the expression α to the program. There are no special backtrackers in an algorithmic language. The function exits after the last command is executed. As a result, it returns the value of a special variable VALUE, which has the same type as the function type.

Most programming languages ​​have the ability to represent and process literal values, as they are called in an algorithmic language. In Logo there is a simple name for this type of execution - “word”. A word is a finite ordered sequence of characters other than space. The word in the program is represented as a habit, which is not included in the count of word characters. The word can be empty - there is not a single character in such a word, its designation is a quote followed by a space (in an algorithmic language, a literal variable turns out to be a pair of quotes). Examples of Logo words: “NADIA - there are 4 letters in a word; “U - a separate symbol is considered a word consisting of this one symbol; "1918-1988 - words of 9 characters.

Early words were used to represent variable names. With the command *MAKE "CAGE 1* the variable *CELL* gets the value 1. The command *MAKE "CAGE" "ELEPHANT* makes the value of the variable *CAGE* of the word *ELEPHANT*. In an algorithmic language, the last command would have the form: *CAGE:="ELEPHANT"*

Such different words!

Imagine a conversation between two boys. Seryozha says:

— *ABBA* is the name I gave to my dogs.

“It’s a funny name,” says Anton, “but how do you spell it?”

- “ABBA” is like this: first “A”, then “B”, another “B” and at the end again “A”.

- Does she know her name? — Anton is interested to know.

Seryozha is happy to demonstrate his dog’s abilities:

- Well, of course! *ABBA*! Here she is!

Three times in this conversation the word *ABBA* was used and each time in a different role. *ABBA* is the name of a dog; "ABBA" is a word that is a sequence of letters in string order; *ABBA*! - this is the command the dog immediately returns to his household. In spoken language, different uses of words can be marked by intonation. If such a conversation needs to be recorded, then to distinguish the different roles of the word, a special designation will be required - punctuation marks.

In Logo, things are exactly the same. To determine the meaning of the example words used in the program, there are also syntactic rules:

⟦folio 53⟧

- a double is placed before the name of a quantity in order to indicate the value taken by this quantity at the current moment; so : MARK is the value of the MARK variable;

— quotation marks are placed before a word that is a string of characters; by the position of such a word in the command (by context) the meaning of the designated word is judged; So, in the assignment command MAKE "CELL" the words in the last position - "EPLEPHANT with a quote at the beginning - is the letter 常数ta, and the words in the previous position - "CELL - is the name of the variable CELL; compare the command MAKE "CAGE:ELEPHANT", where the variable CAGE gets the value that the variable named ELEPHANT had;

— calls to procedures and functions (as well as commands and operations) are not preceded by doubles or quotation marks; the notation CAGE : ELEPHANT means calling the CAGE procedure with the ELEPHANT parameter.

Let's start processing lists

Programmers often use the term "data". This term can be considered synonymous with the concept of “information”. Information processed by a machine can be organized in different ways. These are either single characters, or their ordered finite set - words, or an ordered group of words - a list, or some other more complex way of combining characters, words and lists. Information organized in one way or another is called a data structure.

In an algorithmic language, each data structure must be given a special name - a value type - nat, thing, lit, etc. There is no description of types in Logo, but each of the structures of the algorithmic language has its own analogues in Logo. To represent a table and more complex data structures, Logo uses a list, which expands the concept of a tabular value in the algorithmic language.

Processing lists requires completely different operations than argumentative calculations. Suppose you need to fill in the computer memory with information about the students of the class - a list of information for each student. To work with such a structure, it is useful to have operations that allow you to add, delete, find, and change list elements.

Selection of the first element of the structure - FIRST α (or PRV α). The argument of this operation is words or a list, the result is the first element (structures. For example,

PRV "LOGO = "L,
PRV [LOGO PROGRAMMING language]=
= "LOGO

A structure without the first element - EXCEPT THE FIRST α (or KPRV α). The argument of this operation is words or a list, the result is the last element (structures. For example,

KPRV "LOGO = "OGO
KPRV [LOGO PROGRAMMING language] =
[PROGRAMMING Language]

The last element(structure) is the LAST α (or PSL α). The argument of this operation is words or a list, the result is the last element(structure. For example,

PSL "LOGO = "OGO
PSL [LOGO PROGRAMMING language] =
[PROGRAMMING Language]

A structure without the last element - EXCEPT THE LAST α (or KSSL α). The argument of the operation is words or a list, the result is a structure without the last element. For example,

CPSL "LOGO = "LOG
KPSL [LOGO PROGRAMMING language] =
[LOGO PROGRAMMING language]

Including an element at the beginning of (structure - INITIAL αβ (or INTO αβ). The first argument - we include the element, the second - we change (structure. For example,

INITIAL "L" "OGO = "LOGO
TOP "LOGO [PROGRAMMING LANGUAGE] =
[LOGO PROGRAMMING language]

Including an element at the end (structure - AT THE END αβ (or ВКОН αβ). The first argument is to include

⟦folio 54⟧

element, the second is a changeable structure. For example,

VKON "O" LOG = "LOGO
VKON "PROGRAMMING [LOGO Language] = [LOGO PROGRAMMING Language]

Determining the length of a structure is LENGTH α. The argument to this operation is a word or a list; the result is the number of elements in the structure. For example,

"LOGO" LENGTH = 4
LENGTH [LOGO PROGRAMMING LANGUAGE] = 3
LENGTH [[PENS 3] [NOTEBOOKS 2] [PENALS 5]] = 3

To analyze the data structure in Logo, in addition to those previously entered, the following types of structure conditions are used:

Number? WORD? LIST? EMPTY?

These conditions check whether the structure is a number, a word, a list, or is empty.

So, data about class students is stored in the form of a list:

CLASS=
[[IVANOV PETYA POLEVAYA 35 17]
[DANILOV SASHA PUSHKINA 58 2]
...]

You need to make a list of the names of all students in the class. We will get Ivanov’s “dossier” from the CLASS list using the operation PRV :CLASS:

[IVANOV PETYA CHIEF FIELD 35 17]

From this list we again need the first element:

PRV PRV :CLASS = "IVANOV"

We will collect surnames in the FAM list:

MAKE "FAM VKON PRV PRV :CLASS :FAM

(1)

Command (1) removes the FAM list by one element. The word IVANOV is added to its end. What about Petrov? It’s very simple: you need to shorten the CLASS list:

MAKE "CLASS KPRV :CLASS

(2)

and execute command (1) again. What next? Everything is repeated: command (1) is followed by command (2), etc., until the entire CLASS list is exhausted. This is what the description of the required function looks like:

THESE ARE SURNAMES:CLASS:FAM
REPEAT LENGTH :CLASS
[MAKE "FAM VKON PRV PRV
:CLASS :FAM
MAKE "CLASS KPRV :CLASS
]
RETURN :FAM
END

Having compiled such a description, we obtain the desired list of surnames using the command:

OUTPUT LAST NAMES :CLASS []

(3)

The constructed function is not the only one that solves the problem. We can offer a recursive version of it:

THESE ARE SURNAMES:CLASS:FAM
IF EMPTY? :CLASS [RETURN :FAM]
MAKE "FAM VKON PRV PRV :CLASS :FAM
RETURN THE SURNAME KPRV :CLASS :FAM
END

Here's the command:

IF EMPTY? :CLASS [RETURN :FAM ]
ensures that the recursion ends when the CLASS list is exhausted. Team:

DO IT. "FAM VKON PRV PRV :CLASS :FAM

adds another name to the FAM list. Team:

RETURN THE SURNAME KPRV :CLASS :FAM

makes a recursive call to the LAST NAME function with a shortened CLASS list.

Tasks 2 and 3. Write two versions of the ADDRESS function (recursive and with a loop command), which, based on the last name, would give the student’s address as its value. For example, the result of the output ADDRESS: CLASS "IVANOV" should be the list [POLEVAYA 35 17], and the result of the output ADDRESS: CLASS "DANILOV" should be the list [PUSHKINA 58 2].

The function should provide for calling the message [NO SUCH STUDENT] in case of an incorrect last name.

Task 4. Write a function that calculates the number of words in a list. It is clear that the standard LENGTH function will not always equate correctly. For example, the number of elements in the list [[VASYA PETYA] KOLYA] is two, while the number of words is three.

Attention! Read about the further operating procedure of 3ShP on p. 47.
