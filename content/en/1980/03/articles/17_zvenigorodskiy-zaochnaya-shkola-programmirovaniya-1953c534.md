---
id: 1980-3-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1953c534
issue: kvant_1980_3
year: 1980
number: "3"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 54
page_labels: 48, 50, 51, 52
tag: DFKN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 310fbd2eaa9ccf4bebef8ac763e2e9ff50179a4db72b4bf16fe3c72f9a816cbb
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/17_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1953c534.md
source_content_sha256: ac00f557c2a00bcaebfe967195039cf9becfb5b890f19667b7a56b467de820a1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Correspondence School of Programming

Lesson 7: Functions, graphs, local and texts on Rapier

Functions and graphs

In Lesson 6 («Kvant», No. 2) we studied the description of procedures in the Rapier language. At the same time, we considered only those procedures in which the result name was not specified. However, the syntax diagram provides a version of the procedure description that uses the result name. We will now deal with such procedures.

A procedure whose description contains a result name is called a function in Rapier language. The value of a function is the value that is assigned to the result name (that is, the name following the => sign) after using the function. This value, generally speaking, depends on the values ​​of the parameters specified in the procedure header.

Let's first see what the computer does when it is first given a description of a function. For example, if the program says:

PERC QUAT X => RES;
2*X! 2—5*X+10 —> RES; KSC;

The computer will select a memory block, giving it the initiative.

Now let's see how the machine will call the function stored in memory. It is important to remember that, unlike a normal procedure, a function call can occur within an expression. For example, if in the same program there were such prescripts:

28.5 — > A;
5*(A+KBAT(2)) — > C;

The computer will first write the number 28.5 into a memory block named A (that is, it will assign the name A the value 28.5). To fulfill the second requirement, the computer must add the value of expressions A and KBAT(2). The computer will simply read the first of them in a memory block named A. The second expression is a function call. To find out its value, the computer must find a description of this function in memory, assign it as a parameter (in our case, parameter X will be assigned the value 2), execute all the operators and read the value of the result names. It is easy to calculate that the name RES will receive the value 8. This number will be used as the value of the KBAT(2) expression. Eventually name C will get the value 182.5.

More complex expressions with functions are also possible: KBAT(2+KBAT(1*(-KBAT(2))))

Task 7.1. Calculate the value of this expression.

The Rapier language has standard functions SIN (X), COS (X), EXP (X), LN (X), ARCTAN (X) and some others. The value of the exponential function EXP(X) will be $e^X$, where $e \approx 2.71828$, the word ARCTAN denotes arctigen, LN denotes natural logarithm. Students in grades six and seven have not yet

⟦folio 50⟧

program:
5.21*3 —> A; 2*A—> B;
QUACUBE (2)—> C;
PRINT('A=', A, 'B=', B, C=', C);

He will probably be very surprised when the computer prints:
A=4 B=8 C=8,
after all, he wanted to assign completely different meanings to the names A and B!

To avoid such troubles, you can declare the names used in the procedure using the following statement (the sign “indicates a blank):

For example, a QACUBE procedure with name declaration would look like this:
PERC QUACUBE X=>Y;
NAMES A'B;
X!2—> A; X!3—> B;
IF A>B TO A—>Y ELSE B—>Y ALL; KSC;

Declared names are known only within the procedure and do not affect other parts of the program. This means, firstly, that after using the procedure, the meanings of these names cannot be read. Secondly, if there are other names with the same designation in the program, then their meanings will not change when using the procedure. For example, if the above program is used with a new version of the QUACUBE procedure, then the computer will print
A=15.63 B=31.26 C=8,
that is, exactly what the second programmer needed.

Procedure parameters and result name have the same properties as declared names, so there is no need to declare them.

Names known only within a procedure are called local (that is, local, internal)

names. If a procedure must be used many times in a large program, then all the names in it should be made local - then there will be no random coincidences in the name designations. This is how all standard procedures and functions are organized.

Working with texts

If the words "guard" are tracked well, the result will be "hurray".

Rapier language expressions can include not only numbers, but also texts, as well as names whose meanings are texts. Of course, common arithmetic operations - addition, subtraction, multiplication, division, etc. - are not applied to them. At the same time, there are special operations for working with texts:

1. Concatenation (“gluing”) of texts. This operation is denoted by a + sign, just like addition. For example, after following the instructions 'IL'—>A; 'CODE'—>B;
'KPO'+B+A—>C;

the value of names C will be the text 'CROCODILE'.

2. Determining the length of the text, that is, the number of characters in it. This operation is indicated by the sign ≠. For example:
≠ 'CROCODILE'—>A;
'BUNNY'—>B;
≠ B+≠ 'SQUIRREL'—>K;
PRINT('A=', A,'K=', K);

according to this program the computer will print:
A=8 K=11

3. Cutting out a section of text. This is perhaps the most interesting operation on texts. It can be described by this diagram:

The value of names must be text, and the values ​​of expressions in square brackets must be natural numbers. These numbers are considered the starting and

⟦folio 51⟧

the final symbols of the expressed area. If one expression is specified in parentheses, one character with the corresponding number is expressed. For example, let the following assignments be made:
'CROCODILE'—>K; 'DOE'—>L;
'OWL'—>C;
'TREE'—>E;

then the value of the expression K [4:6] will be the text 'CODE', the value of the expression L [2] will be the text 'A', and the value of the expression K [4:5] + K[2:3] + C[3:4] will be the text 'COW'.

Task 7.5. Find the value of an expression
S[1] + L[2] + K[2] + K[6] + E[1:2] + L[4] + E[3:4]

Expressions above texts can also be used in sentence conditions. Let's try, for example, to describe a function whose parameter is text, and the result is the quantitative letter 'A' in this text:
PERC LETTER TEK=>RES;
NAMES NUMBER;
0—>RES; 1—>NUMBER;
BYE NUMBER=<(≠TEK)::
IF TEK [NUMBER]='A' TOP+1—>RES ALL;
NUMBER +1—>NUMBER;
ALL;
KSC;

The operation of cutting a section of text, unlike most other operations, can be used to the right of the assignment arrow. In this way, you can change the meanings of individual letters and sections of text. Let, for example, the meaning of the name K be the text 'CROCODILE'. Then after the assignment 'I'—>K[3]

the value of this name will be the text 'CRACKODIL', and after the next assignment
K[1:3]≥K[4:6];

the value of this name will be the text 'QRAKRAIL'.

Task 7.6. “Edit the text 'GUARD' so that it turns out 'HURRAH'.

Lesson 8: Sets and tuples on Rappier

In the article about the IV All-World Summer School for Young Programmers («Kvant», 1979, No. 2), we already wrote why sets, tuples and other complex data types are needed. The eighth lesson of the correspondence school is devoted to a description of the means of working with sets and tuples in the Rappier language.

Specifying a set

The meanings of any names in the Rappira language, in combination with numbers, texts and descriptions of procedures, can be complex data structures: sets and tuples.

The set is indicated by angle brackets with asterisks: “* and *”. Inside the brackets, all elements of the set are listed, separated by commas. For example, after completing the order
"*1, 'YOUNG PROGRAMMER', 2, 'QUANTUM'*"—>A;
the meaning of the names A will become a set. The elements of this set are the numbers 1 and 2 and the texts 'YOUNG PROGRAMMER' and 'QUANTUM'.

Anything that can be the meaning of a name in Rappier can also be an element of a set. In part, elements of one set can be other sets:
“*1, 2, “*4, 5, TEXT*””—>B;

In this example, the value of names B is a set of three elements: two numbers and one set.

If a name or a more complex expression is specified in the list of elements of a set, then the value of such an expression will become an element of the set; for example, after completing an order
5—>A; 10—>V;
'GUARD'—>S;
«*A, 4, 40*A+B, C[5]+
C[3:4]*»—>A;

the meaning of names A will be set
"*5, 4, 210, 'HURRAH'*"
Task 8.1. What will be the values ​​of the names A and B after executing

⟦folio 52⟧

Nenya programs:
'CROCODILE' + " + 'GENE' -> A;
= A -> B;
(*A[(B+1)/2-3] + A[(B-1)/2+1] +
A[≠A-1] + A[3] + A[B] +
A[6] + A[2], A[4] + A[11] +
A[2*3] + A[8/4], A[2*2+2] +
A[1+1] + A[B] + A[4:5] +
A[B-1]*) -> A;
(*A, B+1, B+10*) -> B;

Set comparison and membership check
Sets and their names can be used in conditions (in cyclic and conditional sentences).
In particular, two sets can be compared using the = sign. As you know from a school mathematics course, two sets are considered equal if they consist of the same elements, regardless of the order in which these elements are listed: sets
(*'UNKNOW', 'GRUM',
'ZNAYKA'*),
(*'ZNAYKA', 'UNKNOW',
'GRUMBLE'*)

are equal to each other, but the sets (*1, 2, 3*) and (*1 (*2, 3*)*) are not equal.
The PRINT procedure prints the set in the same form in which it is written in the program (that is, all elements are printed in angle brackets with asterisks separated by commas, while the texts will be printed without quotes). The order of the elements when printed can be arbitrary, so it is impossible to imagine in advance, for example, whether the set QUARTET from task 8.2 below will be printed as (*DONKEY, GOAT, MONKEY, BEAR*)

or
(*BEAR, DONKEY, GOAT, MONKEY*)

or something else.

Task 8.2. What does the machine note using a program like this:
(*1, 2*) -> X; (*'MONKEY', 'DONKLE', 'GOAT', 'BEAR'*) -> KBAPTET; (*X, KBAPTET*) ->

MIX1; (**KBAPTET, (*1+1, 1*), KBAPTET*) -> MIXTURE2; IF MIX1 = MIX2 THEN PRINT ('WHATEVER YOU SIT...')
ELSE PRINT ('2*2=4') ALL;
IF KBAPTET = MIXTURE2 TO PRINT ('FROM CHANGING PLACES OF COMPANDS') ELSE PRINT ('PRODUCT DOES NOT CHANGE') ALL;

The condition for an element to belong to a set is written using the keyword IZ, which corresponds to the symbol ∈ in general mathematical notation. For example, the condition

'BEAR' FROM KBAPTET

will be true only if among the elements of the set KBAPTET there is the text 'BEAR'.

Set Operations
The operation of union of a set is denoted in Rapier by the sign +, and the intersection of a set by the sign *. For example, according to the program (*17, 1, 8, 27, 36, 5*) -> CIRCULATIONS; (*5, 25, 11, 17, 35, 4*) -> CIRCULATION2; PRINT('UNION=', CIRCULATION1 + CIRCULATION2); PRINT('INTERSECTION=', CIRCULATION1 * CIRCULATION2); The computer will print:

UNION =
= (*17, 1, 5, 25, 11, 36, 27, 4, 35, 8*) INTERSECTION = (*5, 17*)

The sign - denotes the difference of the set: all elements present in the second set are removed from the first set; for example, according to the program:

(*'LION', 'WOLF', 'FOX', 'HARE'*) -> (*'SQUIRREL', 'HARE', 'RABBIT'*) -> PREDATOR; PRINT(PREDATOR);

will be printed:

(**WOLF, FOX, LION*)

The number of elements of a set is indicated by the ≠ sign, as for texts. For example, that identical elements in a set are counted only once, so the cardinality of the set

(*'CROCODILE', 'GENA'*),
(*1, 1, 2, 1, 2, 1+1, 1, 1, 3-1, 3-2*)
is the same and equal to 2.
