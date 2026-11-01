---
id: 1987-6-kaymin-proverka-pravilnosti-algoritmov-5b0634d4
issue: kvant_1987_6
year: 1987
number: "6"
title: Validation of algorithms
authors:
  - Каймин В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 46
page_labels: 43-44
tag: 60RP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 22b05e34c41c7a2646a35de5ae7f2df8cf83fea3759ec0376652c56a716ea784
prompt_sha256: draft-1
translated_from: content/ru/1987/06/articles/13_kaymin-proverka-pravilnosti-algoritmov-5b0634d4.md
source_content_sha256: 976608c1a4b86dc63d732d5e46e0ce5902694fc59ce1609d49540b2a361adf38
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

Validation of algorithms

Candidate of Technical Sciences
V. A. KAIMIN

Is programming an art, a science, or a craft? Is it possible to write programs and guarantee that there are no errors in them? These two questions are the subject of hot scientific debate, conflict and service research. Let's try to figure it out.

There are three approaches to compiling a program for computers.

The first approach - we call it traditional - consists of writing a program in some programming language (BASIC, FORTRAN, PL/1, COBOL, etc.) immediately according to the meaningful formulations of the tasks:

Programming languages ​​typically have an English vocabulary, and programs in these languages ​​are difficult to read, understand, and learn for non-native English speakers. When compiling a program in traditional practice, a large number of errors are almost always introduced into them, and the program compiler strives to get on the computer as soon as possible and begin debugging the program.

The number of errors in a program is never known in advance, and therefore no one knows when debugging of the program will end. Moreover, when program authors claim that their programs are fully debugged, these programs usually still contain errors.

The second approach to programming, which is commonly called structured programming, consists of carefully thinking through the logic for solving a problem and creating structured algorithms. We advise you to write down these algorithms in the school algorithmic language from your textbook and only after that translate the program recording into one of the programming languages. The program design diagram can be

⟦folio 44⟧

depict like this:

With this approach, it is easy to separate syntax and algorithmic errors. Syntax errors (violations of programming language rules) can only appear if the program is incorrectly coded using algorithms. Algorithmic errors (violations in the logic of problem solving) arise when compiling algorithms; their search and correction can be carried out according to the descriptions of the algorithms before writing and testing the program on a computer.

The third approach, which we call systematic constructive programs, is developmental. It can be schematically represented by the following diagram:

This approach is described in more detail in «Kvant» (1986, No. 10, p. 47 and No. 11, p. 40).

Testing a computer program involves carefully planned tests to ensure that the machines operate in accordance with the program script. Verification consists of checking all the main special cases of problem statements, checking boundary conditions, checking the program's reactions to invalid data and unacceptable human actions. On this side - related to the script of dialogue programs (see «Kvant», 1986, No. 11, p. 40) - we will not go into more detail here.

Identifying errors and justifying the correctness of the program with this approach is carried out through logical reasoning, the whole of which is evidence - will or will the program not give the required results and messages? A complete guarantee of the absence of errors is possible only if there are mathematical formulations of the problems being solved and a detailed description of the scenario for working with a computer.

In this situation, we call a program correct if, given any valid initial data, it generates results that strictly correspond to the scenario for any user actions. A program contains errors if it is possible to specify such data that the machine produces results that contradict the scenario for setting the problems being solved, or its operation does not correspond to the description of the program scenario.

We will look here at several examples of justifying the correctness of individual program fragments written in school algorithmic language (we omit part of the program title for brevity).

Example 1 (computation problem).

alg "calculate x⁵"
start v := x x
v := v · v
y := v · x

results
v₁ = x · x,
v₂ = v₁ · v₁,
y = v₂ · x.

Please note that several values ​​are not described for the variable v during the operation of the algorithm, so in recording the results we first write the letter v with numeric indices. Based on this program we do the following

Statement. y = x⁵.

Proof. From the description of the results of performing operations we have
y = v₂ · x = (v₁ · v₁) · x =
= ((x · x) · (x · x)) · x = x⁵.

Example 2 (algorithm taking into account branching).

alg "calculate |x|"
start if x > 0
then y := x
else y := -x

results
x for x > 0,
-x for x ≤ 0.

Statement. This program always gives y = |x|.

The proof is carried out by analyzing the case. When x > 0, the first alternative is executed. As a result of adding the value will become equal to y = x, which corresponds to the definition
