---
id: 1980-1-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-4fcf1ae9
issue: kvant_1980_1
year: 1980
number: "1"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 56
page_labels: 52-54
tag: 5JAV
lang: en
source: kvant_digital
extraction: vision
content_sha256: ceace9c7885b4a2446c6b76f968b88eeadeed3d5ca45927e7cfdc3f9927661ae
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/23_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-4fcf1ae9.md
source_content_sha256: 0d749d66114057743d373cc22bfe759990f777c693284291ec67321713d4959e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

The “Art of Programming” section has been published in our magazine since issue No. 9 last year. Its purpose is twofold: firstly, to clarify general issues related to computers - what an algorithm and a program are, what a computer’s memory and processor are, how a person and a machine interact; secondly, teach some machine languages, teach how to write programs and debug them on real computers.

The Correspondence School of Programming is designed to develop these skills (see «Kvant», 1979, No. 9). New signatures «Kvant» can be included starting with this lesson if they independently become familiar with the basic ideas of programming in the Robik language («Kvant», 1979, No. 9-11).

We remind our old students and inform new ones that all assignments of one issue should be completed IN ONE STUDENT NOTEBOOK (and not on separate sheets!) and sent to us by a simple (NOT REGISTERED!) letter (not by post) no later than the 20th of the next place, writing the words “QUANTUM” on the envelope in the lower right corner, to the address: 630090, Novosibirsk 90, Nuuki Avenue 6, Computer Science Center of the Siberian Branch of the Academy of Sciences, Department of Computer Science, Correspondence School of Programming. Please include a self-addressed envelope with a 6-point reply stamp in your shipment.

New students should attach a statement to assignment 5 of lesson, written according to the model indicated in «Kvant», 1979, No. 9, p. 45.

Correspondence School of Programming

Lesson 5: Basic operators of the Rapier language

In previous lessons, we were introduced to the educational language Robik, designed to teach basic programming concepts and the most important skills needed to solve problems on a computer. Today we are starting to study a new, significantly more powerful language that allows us to solve not only educational, but also practical, important scientific and industrial problems.

Before reading further, test yourself by answering the following questions:

1. What is a prescription? procedure? operator? directive?

2. How to describe and call procedures in Robik?

3. How to compose and read syntax diagrams?

4. What is a name? What could be the meaning of the name? How to assign a new meaning to a name?

5. How to write down and how to carry out the grafting order? seal order? conditions and cyclic prescription?

6. What are parameters and what are they used for?

If any of these questions caused you difficulties, go to the materials of lessons 1-4 («Kvant», 1979, No. 9-11).

Basic rules of the Rapier language

The basic rules of the Rapier language are very similar to the rules of Robic. Any program consists of sentences; Each of them is followed by a semicolon. Prescriptions consist of individual words. Words in most programming languages, including Robik and Rapik, mean numbers, texts, names, special characters (for example, brackets,

⟦folio 53⟧

signs of arithmetic operations, etc.) and so-called keywords (for example, the words IF, THEN, ELSE in the conditions of the Robik operator). The rules for writing in Rapier are mostly familiar to you from Robik:

Names consist of letters and numbers, and the first character in the name must be a letter, for example:

A5, HARE, LEAD, PATH, TIME.

The number of characters in a name can be any, but the machine distinguishes names by the first six characters, so from its point of view, names

CROCODILE, CROCODILE5, CROCODE and CROCODILE

- it's the same name. To avoid errors, it is not recommended to use names longer than six characters in a program unless absolutely necessary. In addition, it is prohibited to use names that coincide with keywords. The word IF, for example, cannot be a name.

Texts consist of any characters enclosed in apostrophes:

'THIS IS TEXT ON A RAPIER'
'A+B+C9090=33/—/'.

Numbers are made up of digits; To separate the integer part from the fractional part, a dot is used:

2.521 21393 2345.00098

Numbers must have no more than 12 digits.

We will become familiar with special characters and keywords as we study individual sentences.

In Rapier, unlike Robik, it is allowed to place several sentences on one line or, conversely, to write one sentence in several lines. You can move to a new line anywhere in a sentence, but you cannot break the words of the language.

Pricing instructions

We will teach you how to get acquainted with the sentences of the Rapier language with the sentence of attaching. His syntax diagram is very simple and fills the abbreviated diagram that follows Robic's prescription:

Arrow -> reads “assign”. There is no such sign on the keyboard of regular terminals, so to display an arrow you have to press two keys: “—” (minus) and “>” (greater than).

Unlike Robik, the value of the variable expression field in Rapier can be not only a name, number or string, but also any sequence of numbers and names connected by correctly placed arithmetic operations signs and parentheses. In mathematics, a construction is also called, as is known, an arithmetic expression. (A little later we encountered other varieties of expressions in Rapier.)

The Rapier language uses the following arithmetic symbols:

+ addition
- subtraction
* multiplication
/ division
! exponentiation*)

The order of operations is the same as usual in mathematics; First, exponentiation is performed, then multiplication and division, and lastly, addition and subtraction; in this case, as usual, the presence of parentheses is taken into account. The result of attaching names after the arrow.

It is clear that the special computational operators (ADD, SUBTRACT, etc.) available in Robik turn out to be perfect in Rapier: any calculations can be used in the adding operator itself, and the formulas are written almost the same way as in school mathematics.

*) For example, $A^2$ is written like this: $A!2$.

⟦folio 54⟧

For example, to calculate using the formula
$$y = 2,781 \cdot 250 + 500 - 92,5$$
just write
$$2.781 \cdot 250 + 500 - 92.5 \rightarrow y$$

When moving from mathematical notation to a program on Rapier, it should be taken into account, however, that the multiplication sign in Rapier, unlike ordinary mathematics, cannot be omitted: instead of 2AB you need to write 2*A*B, instead of $(A+B)$ $(A-B)$ you write $(A+B)*(A-B)$.

Task 5.1. Write down in the Rapier language a sequence of instructions for calculation using the formulas:

$$A = 15; \quad B = 24;$$
$$C = 3A + A^3B^2 + (A+B)^5 - \frac{A^6}{25} + 33A^6;$$
$$K = 8C + A^2(A+B+C)^7 - 33 + \frac{(76A-34)}{58} + C^9;$$
$$J = \frac{K^8}{38} + \frac{5A}{8} + (A+K+B)^9 - 76 + 58C;$$

Task 5.2. Make a table of values ​​and determine what the values ​​of these names will be after using the program:
$$2 \rightarrow A; \quad A!2 \rightarrow B;$$
$$B*A + (B+A+B)*A!2+A \rightarrow A$$
$$A*B \rightarrow C$$
$$C*2+B*8+C*2+A/2 \rightarrow A$$

Task 5.3. Write down formulas on Rapier to find the roots X1 and X2 of the quadratic equation*) $Ax^2+Bx+C=0$.

(Hint for sixth and seventh graders: $\sqrt{A}$ can be written as $A^{1/2}$.)

*) We tell the sixth graders this formula: $X_{1,2} = \frac{-B \pm \sqrt{B^2-4AC}}{2A}$.

Conditional sentence and cycle
A conditional and cyclic sentence in Rapier looks like this:

The special sign :: (two colons) in a cyclic sentence reads “repeat”.

The main difference between these diagrams and Robik's diagram, as is easy to notice, is that after the words TO and ELSE in a conditional sentence and after the :: sign in a cyclic sentence, any number of sentences separated by semicolons can appear, and not just one single sentence, as in Robik. The keyword BCE is placed at the end of both sentences.

The condition in the simplest case looks like:

Rapier uses the following comparison signs:
= equal
/ = not equal
> more
< less
> = greater than or equal to
= < less than or equal to

For example, after executing the sentence
ECIF $A>B$ TO $B \rightarrow C$
ELSE $A \rightarrow C$ ALL;
the value of the names $C$ becomes the lesser of the values ​​of the names $A$ and $B$.

Let's take a closer look at how this program works:
