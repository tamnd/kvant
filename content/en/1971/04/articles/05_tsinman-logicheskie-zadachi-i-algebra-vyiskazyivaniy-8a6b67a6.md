---
id: 1971-4-tsinman-logicheskie-zadachi-i-algebra-vyiskazyivaniy-8a6b67a6
issue: kvant_1971_4
year: 1971
number: "4"
title: Logic problems and propositional algebra
authors:
  - Цинман Л. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14, 16, 17
tag: R5P5
lang: en
source: kvant_digital
extraction: vision
content_sha256: cdf1f77cff5c090293a79f2ec7031b431c45f52cd5d0975b9aa07d251dceff1f
prompt_sha256: draft-1
translated_from: content/ru/1971/04/articles/05_tsinman-logicheskie-zadachi-i-algebra-vyiskazyivaniy-8a6b67a6.md
source_content_sha256: 5ea05d0c4bf6f5c2873a6eb158d6f236416380caeb63477f9ef71aff442ff630
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Logic problems and propositional algebra

L. L. Tsinman

Let's start with the formulation of several logical problems.

Task 1. After the parent-teacher meeting, one of the parents approached the teacher.

“You didn’t name my son among the good students,” he said. “But my Fedya is an excellent student and, moreover, the best athlete in the class.”

“Yes, you’re right,” answered the teacher. “But we consider a good student to be a student who studies well, is disciplined, helps those who are lagging behind in their studies, and, in addition, participates in the work of a scientific circle or engages in argument.” And your Fedya...

What else was the teacher going to say to Fyodor Palais?

Problem 2. Once, therefore, it was necessary to simultaneously interrogate three witnesses: Claude, Jacques and Dick. Their testimony was contradicted by others, and each of them was accused of lying. Claude said that Jacques was lying, Jacques accused Dick of lying, and Dick insisted, therefore, not to believe either Claude or Jacques. But therefore he quickly brought them out into the open without asking them a single question. Which of the witnesses answered the truth?

Problem 3. One man was captured by savages and was imprisoned in a dungeon with two exits. The leader of the savages offered the captive the following chance of salvation: “One exit leads to freedom, and the other leads to certain death. You can choose anyone. We help my witness make a choice. He'll stay here

would answer one question - any one we wish to ask him. But I warn myself: if this guard is in a good mood, then he is telling the truth, but if he is in a bad mood, then he is lying!

After a moment of reflection, the assembled loyik asked one question, after which he unmistakably chose the exit that led to freedom. What was that question?

Logical problems similar to those listed often appear in popular science publications. Solving them does not require any special knowledge from the field of logic, only fairly well-developed logical thinking is required. But imagine a person who takes on the solution of some numerical problem (movement, pouring) and does not know how to freely do algebraic transformations and solve equations. You find yourself in approximately the same position when solving logical problems without using an auxiliary apparatus, which is called propositional algebra or algebra of logic (as opposed to the algebra of numbers studied at school).

The purpose of the article is to introduce the reader to the initial information from this necessity of algebra and, using the knowledge gained, to solve the problems formulated above. Note, however, that propositional algebra is not only used to solve logical problems (this is just one of its applications), but it is also important

⟦folio 16⟧

Negation of a statement
The notation for the negation of a statement is $A : \bar{A}$. The negation of the statement $A$ corresponds to the statement “not $A$” (“it is not true that $A$”). Therefore, it is determined by the following truth table:

| $A$ | $\bar{A}$ |
| :--- | :--- |
| 1 | 0 |
| 0 | 1 |

Using the introduced operations in statement algebra, complex algebraic expressions can be constructed from individual statements $A, B, C$..., for example: $\bar{A} \vee B; \bar{A} \wedge B; (A \vee \bar{B}) \wedge C$.

As in numerical algebra, the condition is that the operation of multiplication is older than the operation of addition. This allows you to avoid writing some parentheses. Now the expression

$((A \wedge B) \vee ((\bar{A} \vee B) \wedge C))$

can be rewritten in the form

$A \wedge B \vee (\bar{A} \vee B) \wedge C$.

If you know the meaning of each statement included in an algebraic expression, then using truth tables you can find the value of this algebraic expression. Let us find, for example, the values ​​of the algebraic expression $\bar{A} \vee \bar{B}$ for all possible values ​​of its components $A$ and $B$:

| $A$ | $B$ | $\bar{A}$ | $\bar{B}$ | $\bar{A} \vee \bar{B}$ |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 1 | 0 | 0 | 0 |
| 1 | 0 | 0 | 1 | 1 |
| 0 | 1 | 1 | 0 | 1 |
| 0 | 0 | 1 | 1 | 1 |

First, the third and fourth columns are filled in using the values ​​in the first two columns, and then the last column is filled in according to the definition of addition. This table is called the truth table for the expression $\bar{A} \vee \bar{B}$.

Now let's build a truth table for $\bar{A} \wedge \bar{B}$:

| $A$ | $B$ | $\bar{A} \wedge \bar{B}$ |
| :--- | :--- | :--- |
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

The following columns in the above tables turned out to be the same. This means that for any values ​​of the statements $A$ and $B$ the expressions $\bar{A} \vee \bar{B}$ and $\bar{A} \wedge \bar{B}$ take on the same meanings. We will call such algebraic expressions equivalent. To record equivalence, the identity sign is used:

$$\bar{A} \wedge \bar{B} \equiv \bar{A} \vee \bar{B}$$

These two equivalent expressions have the same meaningful meaning, but expressed in different words.

Indeed, if $A$ and $B$ are some statements, then $\bar{A} \wedge \bar{B}$ expresses the complex statement “it is not true that both given statements are true”, and $\bar{A} \vee \bar{B}$ expresses the complex statement “at least one of the given statements is false”.

Algebraic expressions in which the last column in the truth table consists of ones (of zeros) will also be called truly true (equivalently false) and denoted by the letter $H$ (letter $J$).

Using a truth table, it is always easy to determine whether two given algebraic expressions are equivalent or not.

Let us present the simplest equivalences, some of which we

⟦folio 17⟧

In what follows we will use them as rules.

1. $A \wedge B \equiv B \wedge A$.
2. $A \vee B \equiv B \vee A$.
3. $(A \wedge B) \wedge C \equiv A \wedge (B \wedge C)$.
4. $(A \vee B) \vee C \equiv A \vee (B \vee C)$.
5. $A \wedge (B \vee C) \equiv (A \wedge B) \vee (A \wedge C)$.
6. $A \vee (B \wedge C) \equiv (A \vee B) \wedge (A \vee C)$.
7. $A \wedge A \equiv A$.
8. $A \vee A \equiv A$.
9. $\overline{A} \wedge \overline{B} \equiv \overline{A} \vee \overline{B}$.
10. $\overline{A} \vee \overline{B} \equiv \overline{A} \wedge \overline{B}$.
11. $\overline{A} \equiv A$.
12. $A \wedge \overline{A} \equiv \overline{J}$.
13. $A \vee \overline{A} \equiv \overline{H}$.
14. $A \wedge \overline{J} \equiv \overline{J}$.
15. $A \vee \overline{H} \equiv \overline{H}$.
16. $A \wedge \overline{H} \equiv A$.
17. $A \vee \overline{J} \equiv A$.

If we imagine the substantive meaning of rules 1-17 as we did above with rule 9, then these equivalences will become obvious and easy to remember.

Some of the listed rules, namely 1-5, are similar to the well-known properties of the operations of addition and multiplication in numerical algebra. Therefore, in propositional algebra we can perform algebraic transformations similar to those we do in numerical algebra. In particular, we can “multiply” two algebraic statements using the rule for multiplying a polynomial by a polynomial.

But propositional algebra also has its own specific rules, for example 6.

**Solution to problem 1**

Let us introduce notation for the statement:

$A$: “Fedya is a good student”;
$B$: “Fedya is disciplined”;
$C$: “Fedya helps those who are behind in their studies”;
$D$: “Fedya participates in the work of a scientific circle”;
$E$: “Fedya plays sports.”

Now the statement “Fedya is a good student,” according to the “defined” good student, this teaching,

body, can be written like this:

$A \cup B \cup C$ ($D \cup E$).

In the language of propositional algebra, this complex statement will take the form of an algebraic expression

$A \wedge B \wedge C \wedge (D \vee E)$.

The teacher claims that “it is not true that (Fedya is a good student)”, that is

$$\{A \wedge B \wedge C \wedge (D \vee E)\} = 1.$$

Let us now transform the algebraic expression on the left side, first according to rule 9 (though in this case the negation is above the logical product of the four components, but it is easy to see that the equivalence of 9 remains valid in this more general form), and then according to rule 10:

$$\begin{align*}
\{A \vee \overline{B} \vee \overline{C} \vee (D \vee E)\} &= 1; \\
\{A \vee \overline{B} \vee \overline{C} \vee \overline{D} \wedge \overline{E}\} &= 1.
\end{align*}$$

Fedin Popau will claim (and the teacher agreed with him) that

$$\{A\} = 1$$

(Fedya is an excellent student!), and also

$$\{E\} = 1$$

(Fedya is the best skier in the class!). Then in (1) the first and last two terms are false and they can be discarded according to rules 17 and 14.

We get that

$$\{B \vee \overline{C}\} = 1.$$

This means that the teacher wanted to complain with Fedya either because Fedya is undisciplined, or because he does not help those who are behind in their studies (or maybe Fedya has become both of these shortcomings at once).

**Solution to problem 2**

Let us denote the testimony of witnesses Claude, Jacques and Dick correspondingly by the letters $K$, $J$, $D$. We do not know which of these readings are true and which are false. But we know the following:

1) either Claude told the truth, and then Jacques lied, or Claude lied, and then Jacques told the truth;
