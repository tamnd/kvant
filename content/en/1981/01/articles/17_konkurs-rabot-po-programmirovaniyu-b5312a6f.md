---
id: 1981-1-konkurs-rabot-po-programmirovaniyu-b5312a6f
issue: kvant_1981_1
year: 1981
number: "1"
title: Programming competition
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 57
page_labels: 52, 54, 55
tag: EKTO
lang: en
source: kvant_digital
extraction: vision
content_sha256: c597587d783cd0b1ae2b950689eb844c54e57e36efec2af9fdc83a728d7c5f15
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/17_konkurs-rabot-po-programmirovaniyu-b5312a6f.md
source_content_sha256: 2fca978e8f104bdfb0d5b3c689fa870e04a3c3996553cf5654267a8bb663c89a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

There are arithmetic problems. The view of a machine as a super-powerful arithmetic meter is a common misconception of many beginners who start with Fortran or BASIC. A computer is a universal tool for processing all types of symbolic information - graphic, text, control. And only in partial (not the most voluminous) applications of computers are they actually involved in calculating arithmetic expressions. Regular and attentive reader «Kvant», apparently, has already noticed how real this idea sounds on the pages of the “Art of Programming” section.

Programming competition

The Computing Center of the Siberian Branch of the USSR Academy of Sciences and the editors of the journal «Kvant» announce a competition for programming works.

Participation in the competition may take into account correspondence schools of programming, secondary schools and vocational schools. Each work must contain

1) brief information about the authors (last name, first name, patronymic, full home address, school, class, when and where I studied programming);
2) description of the work (statement of the problem, justification of the method for solving it, comments on the program, results obtained);
3) program text and machine calculations (if there are calculations).

Competition entries must be sent no later than April 15 to the address: 630090, Novosibirsk, 90, prosp. Sciences 6, Computing Center SB USSR Academy of Sciences, Department of Informatics, Competition-81.

The winners of the competition will receive an invitation to the VI Summer School of Young Programmers. A review of the most interesting works will be published in our journal.

Ten tasks on the use of arbitrary

(For the beginning, see p. 37)

Problem 10. On figure 10 a graph of the speed v of a rectilinearly moving point is depicted. Having obtained this graph, determine the moment of time t when the acceleration a of this point is equal to 3 m/s².

Note. Construct tangents to the graph of speed with angle

find a coefficient equal to 3. Find the abscissas of the tangent points.

Fig. 10.

⟦folio 54⟧

The table for each planet shows its name, radius (in km), distance from the Sun (in ml. km), the number of satellites, as well as the composition of the atmosphere, specified using a set - a list of names of gases. All this information forms the context of the corresponding object - an element of the SOLAR SYSTEM set.

If now GAZ is taken as a sign in the composition of the atmosphere, and the totality of the remaining elements in the tuples of planets is considered the context, then in these notations it is easy to program task 7 (a, d) of the Programming Olympias («Kvant», 1980, No. 3): from the set of planets of the Solar system, select those whose atmospheres contain carbon dioxide:
<**> —> RES;
for PLANETS from SOLAR SYSTEM ::
IF'CARBON DIOXIDE'
FROM PLANET[5] TO FROM PLANET[5]
TO RES+PLANET—> RES
ALL;
ALL;

The program begins by sending an empty set to REZ; in REZ a set of results is gradually formed. Please note that when solving this problem, we will not need to access individual elements of the set at all. There is no order in which the elements in set (1) are listed.

In this program, many results are stored in the computer's memory. If you want to print the result, you can use the format print operator, the syntax diagram of which looks like this:

Here, expression-1 is the expression whose value (number or text) should be printed, and the value of expression-2 is the number of characters to be printed.

Thus, printing the table of planets is carried out in a cycle:
FOR X FROM RES::
PRINT (X[1]:12,X[2]:6,
X[3]:3,X[4]:2,X[5]:50)
ALL;

(explain how the number of characters to print is chosen here). It is worth saying that one line contains 128 characters, more than is true for modern computer printing devices.

It remains only to add that a printed table should always have a title. But printing the title is not difficult: as a rule, the title is one line.

Task 12.1. Describe the set of students in your class, suggesting that information is known for each of the students: last name, gender, year of birth, starting GTO badge. Write a program that prints

a) the set of all girls in the class;
b) the set of all signifiers of the GTO class.

But what if you need to find all the girls who passed the standards for the GTO badge? One solution immediately catches the eye: write two procedures, one of which, based on the set of students in the class, forms and stores the set GIRL in memory, and the second (already written when solving Problem 12.1) selects an icon from this set. (However, the order of operation of two such procedures can be reversed: first, badges are selected, and then girls are selected from among them.)

Many programming languages ​​(including Rapier) provide the ability to obtain in one “pass”. These capabilities are provided by so-called complex conditions. A complex condition is a collection of several conditions (which are familiar to readers of «Kvant», for example, from conditional statements or Rapier loop operators), connected by the logical operations and (logical multiplication), or (logical addition) and NOT (negation). Combining simple conditions into one complex one is not done arbitrarily, but according to certain rules that can be specified by a diagram.

⟦folio 55⟧

In this syntax diagram, a condition can, of course, be replaced by a complex condition.

Readers of «Kvant» may have already encountered the logical operators AND, OR, NOT. The operators AND and OR are applied to two operands, and the NOT operation is applied to one. The values ​​of the operands and results of all three operations are two different values: true and false, or “+” and “—”, or (which is especially convenient for representation in a machine) 0 and 1. For the operations AND, OR and NOT there is a simple tabular representation (the names A and B indicate the conditions of the operand).

AIB AIB

The operations AND, OR, NOT can be applied to conditions (which also take the values ​​true and false). Thus, (X>2) AND (X<5) means that X falls into the numerical interval 2;5[, and the conditions NOT(GIRL OR (NOT ICON AND BOY)) select the set of all “sports” boys. The same complex condition could be expressed more simply - BOY and BADGE. You can read about ways to transform complex conditions in the book by Yu. A. Shikhanovich “Introduction to Modern Mathematics” (M. “Nauka”, 1965).

Task 12.2. Using complex conditions, compile procedures for selecting from a set of CLASS all boys born in 1965 who are taking the standards for the GTO badge. Print the result table with satisfaction.

The considered do cxx pornsets (SOLAR_SYSTEM, CLASS,...) served as machine representations of two-dimensional tables: one change - the rows are tuples (planets, students, ...), and the second change - the columns are the elements forming the tuples (radii of the planets, gender of the student, ...). Now it won't be difficult to get acquainted with three-dimensional tables. In everyday life, a three-dimensional table is, for example, a book, on each page of which there is one “obvious” two-dimensional table, the required dimension of such a table is the number of pages. Thus, the Bradis tables, known to every schoolchild, can also be depicted as a set of tuples consisting of a numerical value (context) and three characteristics corresponding to it - PAGE, ROW, COLUMN.

Find the value in the third column and fifth row on the second page in such a table to determine the context whose characteristics satisfy the complex condition (PAGE-2) AND (ROW-5) AND (COLUMN-3).

Task 12.3. The class magazine for January contains 8 pages, one page for each of the subjects - Russian language, literature, mathematics, physics, chemistry, geography, foreign language, physical education. The journal page consists of lines, on each of which the student’s name is written and space is provided for 18 assessments - one for each day. Describe your class journal for January and create a program for printing a table of students who received excellent grades in at least one subject on January 28.

And finally, final questions:

Task 12.4. Describe a situation in everyday practice where representing information in a four-dimensional table might be useful. How do you assign such a table to a machine? How to find an element in such a table?

Yu. Pervin, N. Yunerman
