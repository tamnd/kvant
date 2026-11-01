---
id: 1985-6-zaochnaya-olimpiada-po-programmirovaniyu-a0ef6c6c
issue: kvant_1985_6
year: 1985
number: "6"
title: Correspondence Olympiad in Programming
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 28
page_last: 28
page_labels: "26"
tag: E6DL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 011ef10ccc554831c332a0252829fd3716844608ffc4d6381b22c8c68be86586
prompt_sha256: draft-1
translated_from: content/ru/1985/06/articles/07_zaochnaya-olimpiada-po-programmirovaniyu-a0ef6c6c.md
source_content_sha256: aae43f3b178cf5d334348240741c1f85ea2b6eaa6e594539ef66400ecb952579
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Correspondence Olympiad in Programming

On February 17, 1985, the Educational and Production Center for Computer Science in the Oktyabrsky District of Moscow and the Institutes of Electronic Controlled Machines of the USSR Minipibor and Information Problems (sixth) Moscow City Olympid in Programming for schoolchildren, in which about 200 people participated.

The magazine «Kvant» offers all schoolchildren and vocational school students who know how to program (except Moscow) the tasks of this Olympiad as an assignment for the Correspondence Olympiad in Programming. Send your solutions no later than August 1 (by postal ITEMPEL) to the address «Kvant», writing on the envelope: “Programming Olympiad.” The submitted solutions will be evaluated by a jury chaired by Doctor of Physics and Mathematics A. L. Brudno. All participants will be sent feedback on their work. The winners will receive magazine Diplomas «Kvant».

Keep in mind that typos will reduce the score of the solution. Algorithms with excessive action numbers or arrays that can be dispensed with are also reduced in evaluation. Good algorithms and economically written programs increase your grade. In each work, only 3 problems with better solutions are read.

The tasks are listed in descending order of difficulty. Decisions are made in any programming languages. To move forward with the solution, it is necessary to give a complex description of the algorithm.

Tasks

1. Decomposition into terms. Print all the ways the natural number $n$ can be represented by the sum of natural numbers. Rearranging terms in a new way does not count.

2. Equal elements. An array of numbers $P[1:m, 1:n]$ is given. Each row of the array is ordered in ascending order. Find and print the number that appears in all lines, and the inscription NET if there is no such number.

3. Uncompoundable number. An array of natural numbers $M[1:n]$ is given. Find and print the minimum natural number that is not representable by the sum of the array elements $M$. The sum can consist of one term, but each element of the array can appear in it only once.

4. Tetraedae. On the faces of two equal right tetrahedra $M$ and $N$ the numbers $M1, M2, M3, M4$ are written on one, and $N1, N2, N3, N4$ on the other (in the same order). Is it possible to combine tetrahedra so that the same numbers are written on the matching faces? Type DA or NET.

5. The most common number. In the array of numbers $M[1:n]$ find the number that repeats the maximum number of times. If there are several, then one of them.

6. Number systems. The integer array $M[1:9]$ contains the digits (digits) of some natural number in the $i$-ary number system ($M[1]$ is the units digit, etc.). Print the digit of this number in the $j$-ary number system. The numbers $i$ and $j$ are no more than the number ten.

7. Wok diagonal. Find the sum of elements $A[i, j]$ of array $A[1:m, 1:n]$ having a given index difference $i-j=k$. The number $k$ is an integer, but not necessarily positive.

***

Explanation. Here the array $P[1:m, 1:n]$ denotes the array of numbers $P_{ij}$ for $i=1, 2, ..., m$ and $j=1, 2, ..., n$, and the notation $P[i, j]$ denotes the element $P_{ij}$. If it is said that the array $P[1:m, 1:n]$ is given, then the numbers $m, n$ and the values ​​of the array elements are given. The assignments of other arrays have a similar meaning.

In programs (solutions), students enter the extracted values ​​and type them. Some formalize solutions in the form of a subroutine (in an algorithm - procedure, in Forter - subroutine, etc.). In those languages ​​where the size of arrays must be specified by numbers (as in Forter), students choose them arbitrarily.

“Good solutions” must fit (up to a constant factor) into the following quantities: $m \cdot n$ (problem 2), $n^2$ or $n \cdot \log n$ (problems 3 and 5), min {$m, n$} (problem 7), counting $n$ and $m$ as large numbers.
