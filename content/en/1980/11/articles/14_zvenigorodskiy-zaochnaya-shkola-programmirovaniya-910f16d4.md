---
id: 1980-11-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-910f16d4
issue: kvant_1980_11
year: 1980
number: "11"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 46
page_labels: 42-44
tag: 80JC
lang: en
source: kvant_digital
extraction: vision
content_sha256: f92b13ccee00a7a55167d737874bd21504ed7f32236619cf18c8d888f19c7a1b
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/14_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-910f16d4.md
source_content_sha256: 694f68725d6bbb3705d473dc57fdfb892dc69dfa4ff3ac4b12b01953904027ea
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Correspondence School of Programming
Lesson 11: Word Processing on a Computer

The only thing is to change the given title and change some chapters from the first person to the third.

N.V. Gogol. "Overcoat"

Where is word processing used?

Text processing is widespread today in various fields of computer application. For example, most of the tasks that arose during the automated preparation for printing of books, magazines, newspapers and other publications are related to text processing. To process textual information, you can prepare a workpiece, grind and sand the surface of the work, trim both ends, check three holes, cut a thread in one of them and apply a power coating. Come up with an encoding method for the technological instructions and write it down as text.

Task 11.2. To manufacture a part, it is necessary to stamp the workpiece, grind and sand the surface of the work, trim both ends, check three holes, cut a thread in one of them and apply a sealing coating. Come up with an encoding method for the technological instructions and write it down as text.

Task 11.3. Young biologically invented such a system for recording their observations of the behavior of animals in natural conditions: the letter C denotes the animal’s sleep, O - hunting, K - feeding, B - watering, D - fight, I - tsera, U - child care. Describe in words the behavior of the animal represented by the following text:

'OVOXVDKIS'—>THE ANIMAL;

What kind of animal do you think the guys went after: was it a herbaceous animal or a herbaceous one, young or old?

Simple forms of word processing
One of the simplest forms of text processing is counting the number of certain letters or combinations of letters (tasks 4a and 46 of the Programming Olympiad - «Kvant», 1980, No. 3). When preparing printed publications and documents, such a task occurs relatively rarely, but when solving problems from other areas, it occurs very often. For example, in this way you can determine the percentage of valium in the protein, count the number of drills when processing a part, or

⟦folio 43⟧

the number of cases when the animal fell asleep immediately after eating.

Let's describe the COUNT1 function with two parameters - LETTER and TEXT, which will count how many times a given letter appears in the text:

PERCENT COUNT1 LETTER TEXT => COUNTER;
0 —> COUNTER; 1 —> NUMBER;
BYE NUMBER = < (≠ TEXT) ::
IF TEXT[NUMBER] = LETTER
THEN COUNTER + 1 —> COUNTER
ALL;
NUMBER + 1 —> NUMBER;
ALL
KSC;

Check that the value of the function COUNT1('K', TRAIN) is 5.

Task 11.4. Describe the function COUNT2(SEGMENT, TEXT), which counts the number of given segments of sequences of letters in the text. For example, the value of the function COUNT2('KU','COOK') is 2.

Often we have to solve another problem: build a summary table of the number of repetitions of each letter found in the text. It is convenient to represent such a table as a set consisting of tuples of the form <LETTER, NUMBER OF REPEATS>.

For example, for the text “KUKAREKU” the table could look like this: <*<'К',3>, <'У',2>, <'A',1>, <'P',1>, <'E',1>*>.

It is clear that to build a table, you need to look through the entire text and for each of its letters check whether there is a tuple in the table, the first element of which is this letter. If there is such a tuple, then you need to add one to its second element, and if not, you need to add a new tuple to the table, the first element of which is the letter encountered, and the second is one. The corresponding procedure might look like this:

PERC TABLE TEXT => MULTIPLE;
<**> —> MULTIPLE; 1 —> NUMBER;
BYE NUMBER = < (≠ TEXT) ::
TEXT[NUMBER] -> LETTER;
0 —> CONTROL;
FOR A TUPLE OF SETS::
IF TUPLE[1] = LETTER TO
TUPLE[2] + 1 —> TUPLE[2];
1 —> CONTROL
ALL
ALL;
IF CONTROL = 0 TO
MULTIPLE + <LETTER,1> —> MULTIPLE
ALL
ALL
KSC;

Pay attention to the name CONTROL! It had to be introduced in order to check whether the required tuple was among the elements of the MULTIPLE set. You can print such a table in a convenient form, for example, like this:

FOR A TUPLE OF SETS::
PRINT('LETTER',TUPLE[1],
'MEETS',TUPLE[2]'TIME')
ALL;

Editing

Please, the most interesting text tasks arise when processing “real” texts: printed images, documents, programs in various programming languages, etc. The use of a computer allows you to easily and quickly edit such texts, make any corrections and changes to them, print in any format, and sometimes in any font (in one of the articles we will tell you more about preparing printed images on a computer).

A typical example of an editing task is task 4c of Olympida: “Everywhere in the text with the name ORDER, replace the words 'KAPIAN IVANOV' with 'MAJOR IVANOV'.” Most of the participants in the Olympias did not fully cope with this task, but almost no one paid attention to one subtlety: when looking for places where it was necessary to make a replacement, it was necessary to look for the segment “KAPIAN IVANOV” (with a space after the last name!), and not just “KAPIAN IVANOV”, otherwise, for example, Captain Ivanovsky, if his last name appears in the order, also turns out to be a major.

The task of replacing words in the text, taking into account different grammatical forms (in our example, the words “KAPIAN IVANOV” can appear in different meanings) is much more difficult to program. However, Gogol’s Akaki Akakievich, as we know, also failed to cope with this task. This kind of editing of complex texts is conveniently carried out in dialogue mode, when a human operator looks through the text and looks for places where it is necessary to make text replacements (sometimes such a search can take place with a “hint” from the machine), and the replacements themselves are performed by a computer.

To work in this mode, it is convenient to describe in advance the procedures for performing the most common operations (searching for the desired piece of text, replacing, deleting, inserting, outputting to the terminal, etc.),

⟦folio 44⟧

and then use these procedures as directives during dialogue.

Task 11.5. Describe the REPLACE(TEXT,STAR,NEW) process, which will replace certain character assignments with a given text segment in a text named TEXT. The second parameter of this process is the text segment to be replaced, and the third parameter is the replacement segment.

Note and e: If the length of the old and new text segments do not match, string concatenation must be used to correctly replace it. For example, if the word “KRONDIL”, located in the text with the name BARMALEY, starting from the 128th position, needs to be corrected to “CROCODILE”, then this can be done like this:
BARMALEY[1:130] + 'KO'
+ BARMALEY[132:(≠BARMALEY)]
-> BARMALEY;
If you try to use a simple assignment instead, you will not be able to fix the error: after the assignment 'KO'-> BARMALEY[131:131];
it will turn out to be "CROCDIL".

The REPLACE procedure allows you to correct errors and make changes to the text. But you need to use it carefully so that new errors do not arise. Let's look at a simple example. Suppose that in the text with the name textbook you had to print the following format:
SIN (X) + COS (X) = S;

While viewing this text on the terminal screen, the operator noticed an error. The line looked like this:
SIN (S) + COS (X) = S;
The operator tried to fix it and typed the following directive:
REPLACE(textbook,'S','X');
Looking through this place again, he was surprised to find that the format had taken on a completely strange look:
XIN (X) + COS (X) = X.

The reason is clear: all the letters “S” in the textbook (and not only in this line!) have been replaced by “X”.

Task 11.6. Write the correct REPLACE directive to correct the first initial option.

this line (possibly affecting other parts of the claim text).

If an entire book or large program is stored in memory as one long text, then editing such text is not so convenient. With each correction, it is necessary to check that the section of text being replaced or discarded is not repeated in any other place. Of course, such a check can be entrusted to a machine (using the above procedure COUNT2), but usually it is more convenient to simply indicate the exact location of the correction. To do this, large text is divided into short sections of 50-60 characters - lines, and the lines are made up of a tuple. Each line is completely visible on the terminal screen, so choosing the right correction is very easy: you don’t need to worry about the safety of the rest of the text. In the REPLACE directive, with this method of representing text, another parameter appears - the number of the line in which the replacement needs to be made.

* Task 11.7. Create a process to check the correct placement of brackets in the format represented by text named FORM. Parentheses are considered to be placed correctly if it is possible to establish a one-to-one correspondence between the opening and closing parentheses such that each opening parenthesis corresponds to the closing one after it. ()()()() is an example of correct placement of parentheses. Here are examples of incorrect placement: )(),()(),()(),()(),()().

Note and f: To solve this problem it is convenient to use a simple example called the Rutishauser algorithm. Let's assign the name COUNTER the value 0 and look through the FORMS text from left to right. Having found a closing bracket, we will subtract one from the value of the name COUNTER, and having found an opening bracket, we will add one. If at the end of the review the name COUNTER is positive, then the closing parentheses are missing. If, while viewing this name, it becomes negative at least once, it means that the parentheses are placed incorrectly. If during review it did not become negative and by the end it is equal to zero, then everything is in order (prove it!).

G. Zvenitsgorodsky
