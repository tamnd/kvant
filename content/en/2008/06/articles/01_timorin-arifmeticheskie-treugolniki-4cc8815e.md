---
id: 2008-6-timorin-arifmeticheskie-treugolniki-4cc8815e
issue: kvant_2008_6
year: 2008
number: "6"
title: Arithmetic triangles
authors:
  - Тиморин В. А.
rubric: osnovnye-stati
page_first: 10
page_last: 14
page_labels: 8, 12
tag: WSUW
lang: en
source: kvant_digital
extraction: native
content_sha256: 7a216e6e2a55d0fc11bf8be3366567c438d14e041f0550ba32013feeaa89c850
prompt_sha256: draft-1
translated_from: content/ru/2008/06/articles/01_timorin-arifmeticheskie-treugolniki-4cc8815e.md
source_content_sha256: 88d775964eec083871b0508d7f8ed80622369fd527527669a27c0a8a0030e5f0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

KVANT 2008/№6

Arithmetic triangles

V.TIMORIN Are the squares of the lengths of all its sides integers? It is possible that such triangles are called something else, but I have not come across any name and therefore came up with the name myself. However, arithmetic triangles are extremely important to number theory (and we will see some of their applications in this article). The point is simply that they usually use a different language, more algebraic. In general, number theory studies numbers, not shapes. Therefore, many stories about number theory operate with formulas and almost do not contain figure. But, on the other hand, it is very useful to imagine mathematical objects visually. Therefore, we will talk about triangles. In geometric language, our task is to describe classes of arithmetic triangles. Let's give a few definitions. Note that in any parallelogram, each of its diagonals divides the parallelogram into two equal triangles. We will call all these triangles halves of this parallelogram. Two triangles are called neighbors if they are equal to halves of the same parallelogram, and the first

⟦column⟧

is obtained by drawing one of the diagonals of this parallelogram, and the second - by drawing the other diagonal (Fig.1). Fig.1. Transition to the adjacent triangle - In other words. Triangle ABC is neighboring for mi, the neighbor of a given triangle DBC triangle is obtained like this. First we select one of the sides of the triangle. Then we complete the triangle to a parallelogram so that the selected side is its diagonal. After this, we draw another diagonal in this parallelogram. It divides the parallelogram into two equal triangles - these are the same neighbor to the original triangle (we do not distinguish between equal triangles). Let us prove that any neighbor of an arithmetic triangle will also be arithmetic. It is enough to show that if the squares of the sides and one of the diagonals of a given parallelogram are integer, then the square of the other diagonal is also integer. This follows from the well-known geometric theorem that the sum

Illustration by M. Sumnina

WE CALL THE TRIANGLE ARITHMETICAL, EC-

⟦folio 12⟧

KVANT 2008/№6

nick (a, b, c) has discriminant 4. Therefore, it is equivalent to triangle (1, 2, 1). In particular, the square of any side of a triangle (a, b, c) has the form $x^{2} + y^{2}$, where x and y are coprime integers. For example, a has the form that was required to be proved. W The next exercise is quite complex and requires a good knowledge of the properties of coprime numbers.

Exercise 3. Let $a = x^{2} + y^{2}$, where x and y are coprime. Then all natural divisors of the number a are also represented in this form. Find out whether similar statements are true for $x_{+}^{2} 2 y^{2}, x_{+}^{2} 3 y^{2}, x_{+}^{2} 5 y^{2}$.

The theory we touched on in this article is classical and owes its existence to Lagrange and Gauss. Lagrange and Gauss, however, used a different language. They studied the properties of integers representable by a given quadratic form, i.e. representable as $Ax^{2} +$ Bxy $+ Cy^{2}$ for predetermined integer values ​​A, B, C and for some (arbitrary) integer values ​​x and y. The quadratic form is the expression $Ax^{2} +$ Bxy $+ Cy^{2}$ itself, in which x and y are considered as variables. It all started with Fermat, who described the meanings of the quadratic forms $x^{2} + y^{2}, x^{2} + 2 y^{2}$ and $x^{2} + 3 y^{2}$.

Exercise 4. Can the number 7 be represented as

$x_{+}^{2} y^{2}$ for some integers x and y? What about the number 1007? If a and b can be represented in this way, is this always true for ab? And for a + b?

It turned out that there are large classes of quadratic forms that represent the same numbers. Lagrange and Gauss developed a theory that allowed them to efficiently enumerate and work with these classes.

Exercise 5. Prove that a is representable as $x_{+}^{2} y^{2}$ for some integers x and y if and only if it is representable as $5 u^{2} + 6 uv + 2 v^{2}$ for some integers u and v.

The connection between arithmetic triangles and quadratic forms is as follows. The triangle (a, b, c) is associated with a quadratic form

$ax^{2} + ( a + c - b ) xy + cy^{2}$.

Try to understand why it is such a quadratic form and what its meaning is. To do this, it is useful to tile the plane with triangles equal to the given one. The equivalence of arithmetic triangles has a natural description in the language of quadratic forms. A hint of this description is contained in the following challenging exercise.

Exercise 6. Prove that there exists an arithmetic triangle of side d equivalent to the triangle (a, b, c) if and only if $d_{=} ax_{+}^{2} ( a_{+} c_{-} - b ) xy_{+} cy^{2}$ for some coprime integers x and y.

Interesting material about quadratic forms, the Conway scheme and much more can be found in John Conway’s wonderful book “Quadratic Forms Given to Us in Sensations” (M.: MTsNMO, 2008).

⟦column⟧

In conclusion, we will indicate in which direction further theory can develop. This direction is really actively developing, but people mainly use a different language, more algebraic. It turns out to be important to consider not just arithmetic triangles, but arithmetic triangles with orientation. This means that triangles resulting from each other by reflection are considered different. Triangles obtained from each other by rotation or parallel translation are still identified. This is motivated by the fact that reflection cannot be carried out without leaving the plane. In our notation, triangle (a, b, c) is the same as triangles (b, c, a) and (c, a, b), but, generally speaking, not the same as triangle (b, a, c). The concepts of equivalence and classes are easily transferred to oriented arithmetic triangles. From Gauss's results it follows that oriented arithmetic triangles of the same discriminant can, in a sense, be multiplied. The result of multiplication depends only on the equivalence classes of the factors, and not on the factors themselves. This result is determined only up to equivalence. Thus, multiplication is actually an operation on classes of oriented arithmetic triangles, not on the triangles themselves. Multiplication has the usual properties: commutative (commutativity) and associative (associativity). In addition, you can divide triangles into each other, i.e. There is an inverse operation to multiplication. Note that the number of classes of oriented arithmetic triangles for a given discriminant is still finite. Thus, there is a natural, and having good properties, operation of multiplication on a finite set. This operation is very important for number theory. But its detailed discussion no longer fits into the format of this article. Here's just one remarkable property of triangle multiplication: multiply the class of a triangle with side a by the class of a triangle with side b. Then the resulting class contains a triangle with side ab! This implies the following statement (try to prove it): if the numbers a, b and c are the sides of three equivalent arithmetic triangles, then the number abc is also a side of some arithmetic triangle equivalent to the data. Instead of a list of references for further reading (which would be too long), I will simply list the most important keywords. As already mentioned, the concept of an arithmetic triangle is not used. Instead, they talk about classes of quadratic forms. The operation of multiplying these classes is called composition. Classes are also said to form a group called a class group. There are many books and articles that explain the meaning of these terms and develop further theory.
