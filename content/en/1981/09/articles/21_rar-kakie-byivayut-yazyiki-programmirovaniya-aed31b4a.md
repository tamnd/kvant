---
id: 1981-9-rar-kakie-byivayut-yazyiki-programmirovaniya-aed31b4a
issue: kvant_1981_9
year: 1981
number: "9"
title: What are the different programming languages?
authors:
  - Рар А.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 56
page_labels: 50-54
tag: WJSA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2abd218ae63f4a6ce80ac6873e01b2b5f70852a9c3567886a1b556b5775047f9
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/21_rar-kakie-byivayut-yazyiki-programmirovaniya-aed31b4a.md
source_content_sha256: 39ea9ef0c46e3d87cfed08cfd879ba81a9ee2799e160e6246ab14ee8960066a3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

The Art of Programming

Algol 68

Algol Algol-60
Algol-Cobol Alias
Almo Altran Alfarb
Ambit Amtran AP APL
APT ATF AED Basic Bliss
Boyaz BTspl 2am GPL GPS GPSS Graf
GSL Jovial Jass Dialog Diamag
Diana Dynamo Dis-68 Euclid IPS
IPL CEL Cobol Cogenit Comfort
Comit Coral
LDT Lip Lis
Logo Lolita Lotis
Militran Mirfak
Mary Neliak OSS
PL/360 PL-516
RPG Sidel Sale
Simskrit
Pascal PL/1
PL/11 Rapier
Simula-1
Sirnus
Siboball

FACT
FLAC
formac
fortran
fsl
tsdl tsps
Chile
Ezol
Euler
Epsilon
Yarms
Yakhont

Cork Clue
Lisp
Mamlab
Fashion Mad
PS-440
Refal
Settle
agma
-67

A. Rahr

What are the different programming languages?

From the editor. The article published below is also available to those readers who do not study at the Correspondence School of Programming.
The Correspondence School begins its third and final course in the next issue.

Although the first computers were created only in the forties, nowadays programming languages ​​have developed seemingly and invisibly (an incomplete list of languages ​​is shown on the splash screen for this article).

Students ZShP good value Rapier, we will refer to it in the demolitions. Other readers can ignore these footnotes.

We will begin our story from that distant time when there were no programming languages ​​yet, but only

⟦folio 51⟧

Machine languages

The machine language of a computer is nothing more than a system of its machine instructions (see «Kvant», 1981, No. 4 - “Three-address, uniaddress and... addressless machines”). The rules for the machine’s “understanding” of these commands are embedded in the design of the computer, just as, for example, the design of automation is embedded in the “understanding” of what turning the steering wheel “means.”

Let's give an example of the work of the program used by the language. Let us assume that this programmer must, in the course of solving his problem, calculate at what height $H$ the freely feeding matrix point is located $T$ seconds after the start of the fall, if the initial height of the point is $A_m$, the initial speed is $V_m/c$. The corresponding physical formula is well known:

$$H = 9,81 \cdot T^2/2 + V \cdot T + A,$$

but it is more convenient for the programmer to rewrite it in a different form:

$$H = (9,81 \cdot T/2 + V) \cdot T + A.$$

At the very beginning of working on a program, the programmer must perform “memory allocation” for it, that is, determine the address of the cells that will be used to store certain quantities.

Let, for example, he allocated memory as follows:

| Magnitude | Cell address |
| :--- | :--- |
| Constant 9.81 | 1001 |
| Constant 2 | 1002 |
| Variable $A$ | 1101 |
| Variable $V$ | 1102 |
| Variable $T$ | 1103 |
| Variable $H$ | 1104 |

Let, further, in our machine (this, by the way, is a well-deserved wind of domestic computer technology - the M-220 machine, is still used in some places today) the addition operation has code 01, division - 04, multiplication - 05. Then, in accordance with all of his programs, for example starting from cell 0101, the programmer writes:

$$Y = E'9.81;T,H$$
$$D = E'2';H$$
$$C = H,V,H$$
$$Y = H,T,H$$
$$C = H,A,H$$

(C - addition, Y - multiplication, D - division; using the construction = E'...' a numerical constant is depicted).

⟦folio 52⟧

Already in this example, both the convenience of the author and the disadvantages are visible. On the one hand, the program no longer cares about any addresses. By changing a program or combining several programs in one, so that different ones do not have the same name, and may not pay attention to their movement in memory. But, on the other hand, texts in autorok are still too close to texts in machine language; actions in it are too small and unusual for mathematics.

No matter how low the level of the author, programs written in it cannot be directly perceived by the machine, and they, like programs written in any other programming language, must be translated into machine language before use. For such translation (broadcast), special programs have been developed - translators. Translators from auto-records are called assemblers. The proximity of the author to machine language ensures the comparative simplicity of the assembler.

Fortran and ALGOL

The first machine-independent language was Fortran, intended for programming computing tasks. It was created in 1956 in the USA. In 1958-1960 A group of mathematicians from different countries developed the ALGOL-60 language for the same purposes. These two languages ​​are still widely spoken throughout the world. A huge number of programs from various fields of application of computational mathematics are written on them. These languages ​​differ from each other in many ways, but we will not touch on their differences here. Let's return to our example instead. We will be pleased to know that to calculate the original value, just one operator is now sufficient:

$$H = (9,81 * T/2 + V) * T + A$$

(example written in Fortran).

Along with the usual variable objects of the languages ​​under consideration, there can also be arrays - one-dimensional, two-dimensional, etc. A one-dimensional array is a numeric sequence of a certain length*. A two-dimensional array is a sequence consisting of one-dimensional arrays of the same length, etc. The array must be described in the program; such a description must fully define its dimensions. Let, for example, a Fortran program describe a certain two-dimensional array named TABLE and the description of this array indicates its dimensions: 3 in the first dimension and 4 in the second**. It is convenient to think of this array as a table (matrix) of 3 rows and 4 columns, filled with numbers (array elements). At some points in the use of the program, this matrix may be, for example, like this:

$$-4 \quad 0 \quad 5 \quad 8$$

$$6 \quad -2 \quad 4 \quad 3$$

$$0 \quad 0 \quad 15 \quad 11$$

The element at the intersection of the I-th row and the J-th column is specified by a variable with indices TABLE (I, J). You can perform the same actions on a variable with indexes as on ordinary variables, so a couple of operators

$$K = 2$$

TABLE (1,1)-TABLE (K+1,4)+TABLE (K,K)

will replace the top left element of the matrix with the number 9.

In the ALGOL-60 and Fortran languages, there are operator conditions that allow you to determine the further course of use of the program depending on the current values ​​of certain variables, as well as loop operators that perform repeated use of certain parts of the program***. ALGOL-60 has procedures that allow

*) On Rappier, one-dimensional arrays are called tuples (see «Kvant», 1980, No. 3, 3ШП, lesson 8).
**) On Rappier there are 3 components of a tuple, each of which has 4 elements.
***) For similar means in Rappier, see «Kvant», 1980, No. 9, 3ШП, lesson 9.

⟦folio 53⟧

able to call the execution of the same group of operators in different places in the program *); There are similar tools (subroutines) in Forteran.

Another Varian pandemonium

Following the creation of Forter, more and more new programming languages ​​began to emerge in different countries. Now, sorry, they must be counted in the hundreds. In connection with this abundance of languages, the biblical story of the Babylonian Pandemonium is often recalled. According to this legend, the inhabitants of Babylon decided to build a tower (pillar) up to the sky. But nothing came of it. God, not wanting to allow people into heaven, divided the single whole language into the languages ​​of different peoples, and the builders ceased to understand each other. The title screen for the article shows the new Tower of Babel.

There are two reasons for such intensive linguistic creativity. Firstly, computers are universal computing devices designed to solve arbitrary problems that arise in a wide variety of areas of human activity. Of course, all these problems can be solved using machine languages, but we have seen that this is very difficult. The languages ​​Forteran and Algol-60, while greatly facilitating the programming of general computing tasks, are poorly suited for other tasks. Therefore, specialized languages ​​began to appear for more and more new classes of tasks, sometimes very narrow and specific. Secondly, it is significant that programming is a very young area of ​​human activity. Much in it has not yet been established, and therefore programs are created, invented, tested, selecting the most suitable language means for certain purposes. And these problems ultimately

*) For information about procedures in Rapier, see «Kvant», 1980, No. 2, 3ШП, lesson 6.

useful because they make it possible to evaluate and compare different approaches with a view to using them in future, more advanced languages. And languages ​​that are not used naturally die out.

Let us now take a closer look at the individual Cyrillics of the new Tower of Babel and consider first

Specialized languages

Computational tasks are also different. These can be engineering and scientific-technical problems in which it is necessary to perform a large number of calculations on a relatively small amount of data. Algol-60 and Forteran are well suited for these purposes. There are also accounting, economic and accounting tasks where arbitrary operations are simple, but large and complexly organized information must be processed, for example, payroll records. For such tasks, the Cobol language was developed back in 1960. Programs in Cobol specify the format (way of arrangement) of information on input and output documents and determine, using phrases close to phrases in the English (or Russian) language, what actions must be performed on numerical values ​​and on texts included in this information.

At the same time, tasks in which the processing of texts or other non-numeric (symbolic) information occupies a central place are also common. One of the lessons of the Correspondence School of Programming («Kvant», 1980, No. 11) was devoted to such problems, but we will somewhat expand the topic of this lesson by mentioning two more circles of problems.

Thus, we can say that Algol-60, Forteran and Cobol know arithmetic, but do not know algebra: they are able to calculate the value of the expression $x^2 - y^2$ when specifying the value of $x$ and $y$, but they are not able to transform this expression into $(x+y)(x-y)$. We collided

⟦folio 54⟧

here with one of the important tasks of processing symbolic information - formal transformations.

Another range of tasks is the application of programming to programming itself. Programs written in any language require various types of editing and, most importantly, transplication, translation into machine language. But programs are texts, and all these tasks belong to the field of word processing, which is often complex and specific. There are many languages ​​designed to work with texts. Nanoball is the most famous of them.

Some programming languages ​​are characterized not so much by their areas of application as by the structure of the data being processed. This is Liss, a language specifically designed for working with information organized in a list. A list differs from a one-dimensional array in that it is more flexible. Its length is not fixed in advance, it can be replenished anywhere with new elements, and elements can be deleted from any place. In practical terms, this means that the elements of the list are not located close to each other in memory (as is usually the case for arrays), but each element is provided with a link indicating where the next element is located. It is clear that local changes in the list do not lead to the memory modification of the list - only individual links change.

Universal languages

Since the mid-60s, along with the desire to create specialized programming languages, an opposite desire arose: universal languages ​​began to appear, suitable for any task - engineering or accounting, editorial or translation - with a derived structure of the processed information.

The use here of the understanding of the expression “universal language” is not generally accepted.

We can immediately say that in modern times there can be no winner between specialized and universal languages. Both languages ​​are good in some conditions and bad in others. If a programmer often has to move from one class of problems to another, or if within the same task it is necessary, say, to perform complex calculations and edit text, then, of course, it is necessary to use a universal language. On the other hand, it is clear that there is no point in launching a bulky universal tool if you are dealing with some limited type of work. Among the universal programming languages, PL/1, Algol-68, Settle and Pascal are mentioned.

Roughly speaking, we can say that PL/1 comes from Fortan, and the predecessor of Algol-68 was Algol-60. PL/1 and ALGOL-68 can work with data organized by weight in a complex way. For example, you can define an array whose elements are lists, each of which consists sequentially of an integer, a string of characters, a numeric array, a word of an integer, etc. Algol-68 is also characterized by the fact that the programmer can in his program give a language operation (for example, addition with its usual + sign) a new or additional meaning (for example, allowed addition of arrays), as well as define new operations. The programmer can also, by defining a new set of operations needed for some class of problems, make this set available to all programs that solve problems of this class. Thus, ALGOL-68 turns out to be a self-expanding language and (since new operations can appear) at the same time self-adjusting (for a specific area of ​​application).

The main feature of the Settle language is the use of a new type
