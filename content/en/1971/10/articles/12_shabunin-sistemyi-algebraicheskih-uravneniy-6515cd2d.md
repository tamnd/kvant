---
id: 1971-10-shabunin-sistemyi-algebraicheskih-uravneniy-6515cd2d
issue: kvant_1971_10
year: 1971
number: "10"
title: Systems of algebraic equations
authors:
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
tag: ITP5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 445089c68e1a5ef31fc008856e1c025f35505549f512cb9e6335f1bd7560b417
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/12_shabunin-sistemyi-algebraicheskih-uravneniy-6515cd2d.md
source_content_sha256: a2df8d1a6b8629ccd1695d6a446453c3d349e9a29f840cc1c91cbb177d71b323
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Systems of algebraic equations

M. I. Shabunin

At university entrance exams, systems of algebraic equations are first proposed; в частности, такие системы возникают в задачах на составление уравнений. Exam experience shows that many students who come in solve a system of equations cope unsatisfactorily.

The fact is that usually when studying, the question of finding solutions to a system is understood simply as the formal implementation of a series of “usual” algebraic transformations. At the same time, it should be kept in mind that some of the transformation examples may lead to the appearance of extraneous solutions or to the loss of the solution of the original system.

Without appropriate justification for the solution of the system, the logical equations are incomplete. В частности, мы можем не заменить потери некоторых решений. Unfortunately, well-founded, well-presented decisions of the system in the work of applicants are extremely rare.

A detailed presentation of all the important issues relating to the system of equations would require too much space *). Therefore, we will limit ourselves to presenting the basic theoretical principles concerning the solution of three algebraic equations with unknowns, and then consider several examples.

First, let's recall some definitions.

$$\begin{cases}
f_1(x, y, z) = 0, \\
f_2(x, y, z) = 0, \\
f_3(x, y, z) = 0
\end{cases}$$

$$\begin{cases}
f_1 = 0, \\
f_2 = 0, \\
f_3 = 0.
\end{cases}$$

*) The reader can be recommended to study, for example, the book by V. G. Boltyansky, Yu. V. Sidorov and M. I. Shabunin “Lectures and problems in elementary mathematics”, M., “Nauka”, 1971.

systems in which the left side of each equation of the system is a polynomial in unknowns.

A solution to system (1) is a triple of numbers $(x_0, y_0, z_0)$, when substituting the corresponding one instead of $x, y, z$, each equation of system (1) becomes a true numerical equality. Решить систему ознакомает найти все ее решения.

Two systems of equations

$$\begin{cases}
f_1 = 0, \\
f_2 = 0, \\
f_3 = 0.
\end{cases}$$

And

$$\begin{cases}
g_1 = 0, \\
g_2 = 0, \\
g_3 = 0.
\end{cases}$$

⟦folio 46⟧

are called *equivalent* (equivalent) if they have the same solutions, that is, if the solution to system (2) is the solution to system (3) and, conversely, if the solution to system (3) is the solution to system (2). Для обозначения равносильности системы (2) и (3) используется запись «(2) ⟨=⟩ (3)».

Note that if we find all the solutions to system (3), equivalent to system (2), then we have also found all the solutions to system (2). In this case, there is no need to check, that is, there is no need to substitute the values ​​of the unknowns found when solving system (3) into the original system (2).

Equation
$$F(x, y, z) = 0$$
(4)
Let's call it a *consequence* of system (1) if each solution of system (1) satisfies equation (4). Запись «(1) ⟨=⟩ (4)» будет означать, что уравнение (4) есть следствие системы (1).

$$\begin{cases} F_1 = 0, \\ F_2 = 0, \\ F_3 = 0 \end{cases}$$
And
$$\begin{cases} G_1 = 0, \\ G_2 = 0, \\ G_3 = 0, \end{cases}$$

a) each solution to system (1) is a solution to at least one of systems (5), (6);

 The notation “(1) ⟨=⟩ [(5) ∨ (6)]” will mean that system (1) is equivalent to the *set* of systems (5) and (6).

If system (1) is equivalent to a *combination* of systems (5) and (6), then it is possible to solve systems (5), (6) and combine the sets of solutions to these systems; this is the union and dact of all solutions of system (1) (*the totality* of the system appears when considering various cases of type $x > 0$, $x < 0$, $x = 0$).

Let us now formulate several properties that are most often used when solving a system of equations. Мы не будем доказывать эти свойства; Using the given definitions, the reader can easily verify the necessary justification on his own.

I. Let one of the equations of system (1), to determine the first, “split” into two equations, for example, represented in the form
$$g_1(x, y, z) g_2(x, y, z) = 0,$$
Where $g_1$ And $g_2$ - polynomials from $x, y, z$. Then system (1) is equivalent to the combination of the following two systems:
$$\begin{cases} g_1 = 0, \\ f_2 = 0, \\ f_3 = 0 \end{cases} \quad \text{и} \quad \begin{cases} g_2 = 0, \\ f_2 = 0, \\ f_3 = 0. \end{cases}$$

This statement can easily be generalized to the case when two or three equations of system (1) “break up” into several equations.

II. If equation (4) is a consequence of system (1), then, when connecting equation (4) to system (1), we obtain a system {{1}, {4}} of four equations, equivalent to the original one.

III. Let equation (4), a consequence of system (1), “break down” into two equations:
$$F_1(x, y, z) \cdot F_2(x, y, z) = 0,$$
где $F_1$, $F_2$ — многочлены от $x, y, z$. Then system (1) is equivalent to the combination of the following two systems:
$$\begin{cases} f_1 = 0, \\ f_2 = 0, \\ f_3 = 0, \\ F_1 = 0 \end{cases} \quad \text{и} \quad \begin{cases} f_1 = 0, \\ f_2 = 0, \\ f_3 = 0, \\ F_2 = 0. \end{cases}$$

IV. Система уравнения (1) равносильна каждой из следующих системы:
$$\begin{cases} f_1 - f_2 = 0, \\ f_2 - f_3 = 0, \\ f_3 - f_4 = 0; \end{cases} \quad \text{и} \quad \begin{cases} f_1 - f_2 = 0, \\ f_2 - f_3 = 0, \\ f_3 - f_4 = 0; \end{cases}$$

$$\begin{cases} f_1 + f_2 = 0, \\ f_1 + f_3 = 0, \\ f_2 + f_3 = 0 \end{cases}$$

(the ability to add to one equation of the system another number multiplied by the product).

V. Let one of the equations of system (1), for example, its first equation $f_1(x, y, z) = 0$, be equivalent to the equation $x = \varphi(y, z)$ - a polynomial in $y$ and $z$. Then system (1) is equivalent to system
$$\begin{cases} x = \varphi(y, z), \\ f_2[\varphi(y, z), y, z] = 0, \\ f_3[\varphi(y, z), y, z] = 0. \end{cases}$$

⟦folio 47⟧

This statement underlies the method of eliminating unknowns: system (1) is adapted to the control system
$$\begin{cases} f_2[\varphi(y, z), y, z] = 0, \\ f_3[\varphi(y, z), y, z] = 0 \end{cases}$$
with two unknowns $y, z$.

Before moving on to the analysis of examples, we will make one replacement. When considering a specific system, it is not always possible to immediately notice the combination of control data that serves as the “key” to the solution, or to find a transformation method that allows for sufficient simplification. Of course, there are no general solutions for finding a solution to the system. Only sufficiently rich experience can help to “see” those features of the proposed system that make it possible to reduce it to another that can be easily solved.

$$\begin{cases} xy + z^2 = 2, \\ yz + x^2 = 2, \\ xz + y^2 = 2. \end{cases}$$

Solution. Subtracting the first control from the second control of this system and factoring the difference of the left sides into factors, we obtain
$$(x - z)(x - y + z) = 0.$$
Similarly, subtracting the second control from the third control of system (7), we find
$$(y - x)(x + y - z) = 0.$$

$$\begin{cases} (x - z)(x - y + z) = 0, \\ (y - x)(x + y - z) = 0, \\ xz + y^2 = 2. \end{cases}$$

Since the left sides of the first two controls of system (8) are the product of two polynomials, then system (8) is equal to (property I) the set of the following four systems:
$$\begin{cases} x - z = 0, \\ y - x = 0, \\ xz + y^2 = 0; \end{cases}$$

$$\begin{cases} x - z = 0, \\ x + y - z = 0, \\ xz + y^2 = 2; \end{cases}$$

$$\begin{cases} x - y + z = 0, \\ y - x = 0, \\ xz + y^2 = 2; \end{cases}$$

It is clear that each of the resulting four systems is simpler than the original system (7).

Having solved the system $(8_1), (8_2), (8_3), (8_4)$ by the method of eliminating unknowns (property V) and combining the solutions of these systems, we obtain the following eight three numbers:
$$(1, 1, 1), (-1, -1, -1), (\sqrt{2}, 0, \sqrt{2}), (-\sqrt{2}, 0, -\sqrt{2}), (\sqrt{2}, \sqrt{2}, 0), (-\sqrt{2}, -\sqrt{2}, 0), (0, \sqrt{2}, \sqrt{2}), (0, -\sqrt{2}, -\sqrt{2}).$$

These eight sets of numbers form the entire set of solutions to the original system (7), since

$$(7) \langle = \rangle (8) \langle = \rangle [(8_1) \vee (8_2) \vee (8_3) \vee (8_4)].$$

Example 2 (MIPT, 1969). Solve control system
$$\begin{cases} x^2y = x + y - z, \\ z^2x = x - y + z, \\ y^2x = y - x + z. \end{cases}$$

Solution. Adding the controls of this system in pairs, we obtain the system
$$\begin{cases} x^2y + z^2x = 2x, \\ x^2y + y^2z = 2y, \\ z^2x + y^2z = 2z, \end{cases}$$

⟦folio 48⟧

which (due to property IV) is equal to system (9). System (10) is simpler than system (9), since each equation of system (10) “splits” into two equations.

System (10) can be rewritten as follows:

$$\begin{cases}
x(z^2+xy-2)=0, \\
y(x^2+yz-2)=0, \\
z(y^2+xz-2)=0;
\end{cases}$$

according to Statement I, it is equal to the system of the totality of the following possible systems:

$$\begin{cases}
x=0, \\
y=0, \\
z=0; \\
(10_1) \\
x=0, \\
x^2+yz-2=0, \\
z=0; \\
(10_3) \\
z^2-xy-2=0, \\
y=0, \\
z=0; \\
(10_4) \\
z^2+xy-2=0, \\
x^2+yz-2=0, \\
z=0; \\
(10_5) \\
x=0, \\
x^2+yz-2=0, \\
y=0, \\
z=0; \\
(10_6) \\
z^2+xy-2=0, \\
y=0, \\
z=0; \\
(10_7) \\
z^2+xy-2=0, \\
x^2+yz-2=0, \\
y=0, \\
z=0; \\
(10_8) \\
z^2+xy-2=0, \\
x^2+yz-2=0, \\
y=0, \\
z=0; \\
(10_9) \\
\end{cases}$$

System (10₁) has solution (0, 0, 0); systems (10₂), (10₃), (10₄) have no solution; system (10₅) has a solution ($\sqrt{2}, \sqrt{2}, 0$), ($-\sqrt{2}, -\sqrt{2}, 0$); system (10₆) has a solution (0, $\sqrt{2}, \sqrt{2}$), (0, $-\sqrt{2}, -\sqrt{2}$); system (10₇) has a solution ($\sqrt{2}, 0, \sqrt{2}$),

(-$\sqrt{2}, 0, -\sqrt{2}$); system (10₈) coincides with system (7), considered in example 1. Since (9) $\langle = \rangle$ (10) $\langle = \rangle$ $[(10_1)\lor(10_2)\lor\dots\lor(10_7)]$,

then the set of all solutions of system (9) is the union of the set of solutions of system (10₁), (10₅), (10₆), (10₇), (7). The result is the above solution to system (7) and another solution (0, 0, 0).

Exercises

1. (MIPT, 1969).
$$\begin{cases}
xy+x+y=7, \\
yz+y+z=-3, \\
xz+x+z=-5.
\end{cases}$$

2. (MIPT, 1970).
$$\begin{cases}
3xy-\frac{16}{xz}=-5, \\
xz+\frac{8}{yz}=4, \\
yz-\frac{3}{xy}=1.
\end{cases}$$

3. (MIPT, 1970).
$$\begin{cases}
4xy+x^2+y^2=1, \\
8xz+x^2+4z^2=-2, \\
8yz+y^2+4z^2=1.
\end{cases}$$

4. (MIPT, 1969).
$$\begin{cases}
2(x^2+y^2)=xyz, \\
10(y^2+z^2)=29xyz, \\
5(z^2+x^2)=13xyz.
\end{cases}$$

Find real solutions to the system of equations:

5. (MIPT, 1969).
$$\begin{cases}
xyz^2=-y-2x, \\
2x^2yz=-y-z, \\
3xy^2z=2x-z.
\end{cases}$$

6. (MIPT, 1969).
$$\begin{cases}
x^3+y^3=19xy+7xz+11yz, \\
x^3+z^3=26(xy+xz+yz), \\
y^3+z^3=47xy+35xz+39yz.
\end{cases}$$

7. (MIPT, 1970).
$$\begin{cases}
3x-6y-8z=xyz^2, \\
2x-5y-7z=-x^2yz, \\
3x-9y-13z=-xy^2z.
\end{cases}$$
