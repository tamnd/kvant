---
id: 1976-10-sadovskiy-arshinov-gruppyi-a695cc76
issue: kvant_1976_10
year: 1976
number: "10"
title: Groups
authors:
  - Садовский Л. Е.
  - Аршинов М. Н.
rubric: osnovnye-stati
page_first: 8
page_last: 14
page_labels: 6-12
tag: Y6VB
lang: en
source: kvant_digital
extraction: vision
content_sha256: dae3b8fa6b65428fc46b0be6e6fc102afba350f100caa346563db1cecd2ab354
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/04_sadovskiy-arshinov-gruppyi-a695cc76.md
source_content_sha256: f0194078460b25ef6fa541a554914aabfd69d307bad793fd5bea1cd17130456d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 6⟧

L. Sadovsky,
M. Artsinov
GROUPS

Twenty-first century mathematics may be very different from ours; Perhaps a student begins studying algebra with the theory of substitution groups, which he could do now if it were not for the established tradition.
Simon Newcombe, 1893

Algebra studies various actions (operations) and the principles that they are subject to. These operations can be defined not only on numbers, polynomials and vectors, which you know from the school course in mathematics and physics, but also on elements of a different nature.
In the article by A. Kolmogorov, you became acquainted with the operation of composition of displacements and the concept of “transformation group”. Here we will talk about an abstract algebraic construction called a group.

It took mathematicians almost years to develop the concept of a group in its modern form. Two hundred years ago, the famous French scientist Joseph-Louis Lagrange (1736-1813), while studying the solution of algebraic equations in radials, actually operated with the concept of a group, although he did not use this term itself. In 1771, he formulated and proved the first essential theorem in group theory.

Lagrange's research was continued by the Norwegian mathematician Niels Henrik Abel and the Frenchman Evariste

⟦folio 7⟧

Galois*), who first coined the term “group”. The elements of the groups he considered were substitutions of the roots of the algebraic equation
$$a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0 = 0.$$
Groups of permutations were also studied by Augustin-Louis Cauchy (1789-1857), Arthur Cayley (1821-1903), Camille Jordan (1838-1922) and other famous mathematicians. The currently accepted definition of a group was proposed by Cayley in 1854.

The property of symmetry, widespread in nature, is closely related to the understandable group. Not only snowflakes, honeycombs, table salt and quartz crystals are symmetrical. Elementary particles also obey the “law of symmetry” - charge conjugation, according to which each particle corresponds to an antiparticle. The basis for the symmetry of the world around us is Galileo’s principles of relative energy, the laws of conservation of energy, momentum, electric charge, etc.

The study of the laws of symmetry, common to its most diverse manifestations, led to the creation of a special mathematical apparatus called group theory.

The definition of a group is based on the concept of a binary operation.

Binary operation
Suppose that each ordered pair $a$ and $b$ of elements of some arbitrary set $G$ is associated with some element $c$ of the same set. Then we say that a binary operation is defined on the set $G$. The result of applying this operation to a given pair of elements, written in symbolic form
$$a * b = c.$$
*) About these mathematical ones, see «Kvant», 1973, No. 10 and 1976, No. 5.

Sometimes a grafting term is chosen for a binary operation, meaning it is addition, multiplication or composition. An example of a binary operation is the composition of movements on a plane.

The product $a * b$ and $b * a$ may be the same or different. In the first case they say that $a$ and $b$ compute (permutate), in the second they do not compute. A binary operation * is called commutative if for any $a, b$ there is $a * b = b * a$, and non-commutative if there is at least one pair of elements $a, b$ for which $a * b \neq b * a$.

Task 1. Check that
a) ordinary addition is a binary operation on the set $Z$ of all integers;
b) multiplication is also a binary operation on the set $Z$.

Thus, on the same set one can, generally speaking, define different binary operations.

Problem 2. Are $Z$ binary operations on the set
a) division;
b) subtraction?
Are these operations commutative?
Problem 3. Are addition, subtraction, multiplication and division binary operations on the set of all odd numbers?

There are only two possibilities to move a given triple of elements $a, b, c$ without changing their order: $(a * b) * c$ or $a * (b * c)$. If
$$(a * b) * c = a * (b * c),$$
then the triple of elements $a, b, c$ is called associating; For her, the symbol $a * b * c$ has a certain meaning. If the operations * each triple of elements associates, then the operation itself * is called associating.

Problem 4. Are the following operations associative:
a) composition of movements;
b) addition and multiplication of real (complex) numbers;
b) dividing and raising numbers to the power $(a * n = a^n)$?

⟦folio 8⟧

Group Definition

A set $G$ with a binary operation * defined on it is called a group if three axims are satisfied:

Axiom I (existence of a single element). There is a unique element $e$ of the set $G$ such that

$$e * a = a * e = a$$

for any element $a$ of $G$.

Axiom II (existence of an inverse element). For each element $a$ of the set $G$ there is an element $a^{-1}$ such that

$$a * a^{-1} = a^{-1} * a = e.$$

Axiom III (associativity of a binary operation). For any triple $a, b, c$ elements from $G$ the equality

$$a * (b * c) = (a * b) * c.$$

If a binary operation is commutative, then the group is called Abelian (in honor of Abelai) or commutative, otherwise - non-Abelian or non-commutative.

So, a set turns into a group as soon as a binary operation is given on it, subordinating the three indicated axioms. At the same time, nothing is assumed regarding the very elements of this set: they can be numbers, polynomials, displacements, or objects of some other nature.

Now that the definition of a group has been given, everyone will find that he has been familiar with groups for a long time. In fact, many numerical sets with respect to the general operations of addition and multiplication form a group. Thus, a group is a set of integers with the operation of addition; it is called the add group of integers. This is an Abelian group, its “unit” element is the number: $0 + c = c + 0 = c$, the inverse of an arbitrary number is its opposite: $c + (-c) = 0$.

Fig. 1.

The group is also formed by the set $G$ of all changes that map onto themselves some function (tel) $F$. This group serves as a characteristic of the symmetry of the functions $F$ and is called the group of the symmetric function $F$.

Problem 5. Check that the sets of rational and real numbers with the operation of addition are groups (add groups of rational and real numbers).

Problem 6. Prove that
a) positive rational;
b) positive real numbers form groups when multiplied (multiplicative groups of positive rational and positive real numbers).

Problem 7. Do groups form sets of rational and real numbers with the operation of multiplication?

Three persons of one group

Person first (arithmetic). Let us fix a natural number $n$ ($n \neq 1$) and consider the set (denoted by $T_n$) of remainders when dividing each natural number by $n$. It is clear that there are exactly $n$ different remainders, they are equal to the correspondence 0, 1, 2, . . . , $n-1$. Any two numbers $k$ and $l$, which when divided by $n$ give equal remainders, are called modulo comparable $n$ and write

$$k \equiv l \pmod n.$$

We now expand the set of $N$ natural numbers into $n$ classes according to the following principle.

In the zero class (to denote it it is convenient to use the same number 0) we collect all the numbers that, when divided by $n$, give

⟦folio 9⟧

remainder 0, that is, $a$ such that $a \equiv 0$ (mod $n$).

In the first class, the eigenvalue $a \equiv 1$ (mod $n$), i.e., leaves remainder 1 when divided by $n$.

In general, we place all numbers $a \equiv k$ (mod $n$) into the $k$th class. To denote this class we use the same number $k$ (Fig. 1).

Let us now define a binary operation on the set $Z_n$ of constructed classes. Let $k$ and $l$ be any two classes. Let’s choose any number from each of them, for example, $a$ and $b$: $a \equiv k$ (mod $n$), $b \equiv l$ (mod $n$).

Let's add up the total sum $a+b$ and divide it by $n$. Then the remainder will be either $k+l$ (if $k+l < n$) or $k+l-n$ (if $k+l \geq n$).

This means that the following operation $\oplus$ makes sense (let’s call it “class addition”):

$$k \oplus l = \begin{cases} k+l, & \text{ если } k+l < n, \\ k+l-n, & \text{ если } k+l \geq n. \end{cases}$$

For example, at $n=3$ there are three classes: 0, 1, 2. The addition table for these classes looks like this:

| $\oplus$ | 0 | 1 | 2 |
| :--- | :--- | :--- | :--- |
| 0 | 0 | 1 | 2 |
| 1 | 1 | 2 | 0 |
| 2 | 2 | 0 | 1 |

The set $Z_n$ with respect to the operation $\oplus$ forms a group called group residue modulo $n$. Indeed, all group axioms are satisfied: the neutral element is the zero class; the opposite element of the class $k$ ($k \neq 0$) is the class $n-k$ ($-0=0$). Finally, the $\oplus$ operation is associative (check!).

Face two (geometric). The set of rotations of the plane around the center $O$ of a regular $n$-gon by angles $\alpha$, at which this $n$-gon is mapped onto itself, also forms a group with respect to the operation $\oplus$ composition of a variable. The inverse of $R^\alpha$ is $R^{-\alpha}$:

$$R^\alpha \circ R^{-\alpha} = E.$$

In this group there are $n$ elements (turns $R^{\alpha_k}$, where $\alpha_k = k \cdot \frac{360^\circ}{n}$, $k=0, 1, \dots, n-1$; see Fig. 2), and the correct composition of turns can be written as follows:

$$R^{\alpha_k} \circ R^{\alpha_m} = \begin{cases} R^{\alpha_k+m}, & \text{ если } k+m < n, \\ R^{\alpha_k+m-n}, & \text{ если } k+m \geq n. \end{cases}$$

This is the correct position on the correct (1) addition of classes, using it we could write:

$$R^{\alpha_k} \circ R^{\alpha_m} = R^{\alpha_k+m}.$$

Third person (complex). It can be smoothed out by those who are familiar with complex numbers and operations on them. We are now interested in the set of all complex roots of degree $n$ of ones, that is, the set of solutions to the equation $z^n=1$.

If $z=\cos \alpha+i\sin \alpha$ is the trionometric form of such a number, then, according to the rule of multiplication of complex numbers, $z^n=\cos n\alpha+i\sin n\alpha$. The equality $z^n=1$ holds for $n\alpha=2\pi k$, where $k$ is an integer, so all $n$ distinct roots of unities are given by the formula

$$z_k=\cos \frac{2\pi}{n} k+i\sin \frac{2\pi}{n} k$$

($k=0, 1, \dots, n-1$). Easy to check

⟦folio 10⟧

that the set of all these roots forms a group with the following multiplication rule:

$$z_h \cdot z_l = z_{k \oplus l}.$$

(3)

Let us recall that each complex number $z = r$ (with $\alpha + i \sin \alpha$) with model $r$ and argument $\alpha$ is represented in the rectangular coordinate system by a vector of length $r$, making an angle $\alpha$ with the axis $Ox$. Therefore, the numbers $z_h$ are represented by vectors of length 1 so that every two adjacent vectors make an angle $2\pi/n$ with each other. In other words, the ends of these vectors are placed at the vertices of a regular $n$-gon (Fig. 3).

It is now clear that the group of $n$th roots of ones and the group of rotations $R^{\alpha_k}$ are essentially “not different” and “similar” to the group $Z_n$. In order to clarify the last phrase, one of the most important concepts of mathematics should be introduced.

The concept of isomorphism

Consider any two groups $G$ and $H$. Let us assume that a one-to-one correspondence has been established between the elements of these groups (we denote it by the letter $\varphi$), that is, an inverse mapping $\varphi$ set $G$ onto set $H$ is given. Let us choose an arbitrary pair of elements $a, b$ in $G$; they correspond to some elements $\varphi(a), \varphi(b)$ in $H$. Since $G$ and $H$ are groups, the product $ab \in G$, $\varphi(a) \varphi(b) \in H$, and also $\varphi(ab) \in H$ are defined.

About the limit. The groups $G$ and $H$ are called isomorphic if there is a one-to-one mapping $\varphi$ of the group $G$ onto the group $H$ that preserves the product, that is, such that for any $a, b \in G$ there is $\varphi(a) \varphi(b) = \varphi(ab)$.

This mapping is called an isomorphism.

The isomorphism of two groups will make it clear that the laws that are subject to the operation in both groups are identical, and that every property inherent in the operation in one of the groups is equally

to the extent that an operation is inherent in a group isomorphic to it. Therefore, isomorphic groups are called “abstractly equal” and are identified with each other, which leads to the emergence of one abstract group: a group regarding the nature of whose elements no specific assumptions are made.

An example of isomorphic groups is the three groups just considered: the group of residues, and the group of rotations, and the group of roots of units are in fact only three realizations of the same abstract group.

The isomorphism $\psi$ between the rotation group and the group $Z_n$ is the map

$$\psi (R^{\alpha_k}) = k.$$

It is clear that in this case the product of rotations will correspond, as follows from formula (2), to the sum of residues.

The $\varphi'$ isomorphism between the group of rotations of a regular $n$-gon and the group of $n$th roots of ones is established by the correspondence

$$\varphi (R^{\alpha_k}) = z_k.$$

Rule (4), of course, is satisfied; it follows from equality (3).

Problem 8. Establish an isomorphism between the group of $n$th roots of unities and the group $Z_n$ of residues modulo $n$.

Problem 9. Construct an isomorphism between the additive group of all real numbers and the multiplicative group of positive real numbers.

⟦folio 11⟧

Symmetry groups

It is easy to distinguish a symmetrical figure from an asymmetrical one - intuition helps us with this. It tells us that a square is more symmetrical than a rhombus, and a circle is more symmetrical than a rhombus. But intuition alone is not enough. More detailed considerations arise when considering the displacements of space (or plane), for which given figures F will be mapped onto itself. The possibility of such transformations (with the operation of composition of displacements) forms a group called the group of symmetrical figures F. You already know about this from the article by A. Kolmogorov (see p. 4), and we have already given this example of a group. Now we will study the symmetrine groups of some figures.

Let's start with the circle, which since ancient times has seemed to people as the embodiment of perfection and an example of symmetry. With any rotation relative to the center and with mirror reflection relative to an arbitrary diameter, the circle self-aligns. Thus, the circle symmetry group consists of all rotations $R_0^\alpha$ about the center $O$ of the circle and all axial symmetries $S_l$ with axes $l$ passing through the point $O$.

The symmetry group of the ellipse is much smaller - it consists of two axial symmetries relative to mutually perpendicular conjugate diameters of the ellipse (the ellipse is described in «Kvant», 1975, No. 1), rotation $R_0^{180^\circ}$ (central symmetry) around the ellipse and, of course, also an effective mapping $E$. The same will be the symmetry group of the rhombus.

But the square has a larger group of symmetry, which we will now separate.

Let's draw a square on the plane and designate its vertices with the numbers 1, 2, 3, 4. For any self-alignment of the square, each of its vertices ends up in the place of a certain vertex. So, for example, when turning $R_0^{90^\circ}$ ($O$ is the center of the square), vertices 1, 2, 3, 4 will move, respectively, to vertices 2, 3, 4, 1 (Fig. 4): $R_0^{90^\circ}(1) = 2$, $R_0^{90^\circ}(2) = 3$, $R_0^{90^\circ}(3) = 4$, $R_0^{90^\circ}(4) = 1$. This fact can be written differently:

$$1 \rightarrow 2, 2 \rightarrow 3, 3 \rightarrow 4, 4 \rightarrow 1.$$

Similarly, turn $R_0^{180^\circ}$ matches the entry

$$1 \rightarrow 3, 2 \rightarrow 4, 3 \rightarrow 1, 4 \rightarrow 2.$$

What has been said can also be written in veena form, the meaning of which is clear from the previous one:

$$R_0^{90^\circ} = \begin{pmatrix} 1 & 2 & 3 & 4 \\ 2 & 3 & 4 & 1 \end{pmatrix}, R_0^{180^\circ} = \begin{pmatrix} 1 & 2 & 3 & 4 \\ 3 & 4 & 1 & 2 \end{pmatrix}.$$

We have obtained what mathematicians call a substitution: the inverse mapping of the finite set $M$ onto itself (here, the set of four points - the vertices of a square). Having enclosed the elements of this finite set with the numbers 1, 2, ..., $n$, we will add each substitution in the form of a table

$$\begin{pmatrix} 1 & 2 & 3 & 4 & ... & n \\ a_1 & a_2 & a_3 & a_4 & ... & a_n \end{pmatrix},$$

the bottom line contains the same numbers as the top line, but in a different order. Substitution, therefore, consists in the fact that each element $a_k$ from $M$ is associated with a unique element $b_k$ from the same set, and different elements $a_k$ correspond to different $b_k$.

⟦folio 12⟧

With this point of view, different entries can be taken for the same substitution, for example:

$$\begin{pmatrix} 1 & 2 & 3 & 4 \\ 3 & 2 & 1 & 4 \end{pmatrix}, \begin{pmatrix} 2 & 3 & 1 & 4 \\ 2 & 1 & 3 & 4 \end{pmatrix}, \begin{pmatrix} 1 & 3 & 2 & 4 \\ 3 & 1 & 2 & 4 \end{pmatrix}.$$

Typically, the elements of the top row are arranged in a natural order, and therefore, in general, a substitution of $n$ elements is written in the form

$$\begin{pmatrix} 1 & 2 & \dots & n \\ a_1 & a_2 & \dots & a_n \end{pmatrix}.$$

Let $\sigma$ and $\tau$ be two permutations of the set $M$. The product $\tau \circ \sigma$ of the substitution $\sigma$ by $\tau$ is the substitution $\omega$ that arises as a result of the sequential execution of first $\sigma$ and then $\tau$. Thus, if $\sigma$ matches the element $a$ with $b$, and $\tau$ matches the element $b$ with $c$, then the product $\tau \circ \sigma$ with the element $a$ matches $c$. The product depends on the order of the components. Indeed, if $\tau$ maps the element $a$ to the element $d$, and $\sigma$ maps $f$ to the element $d$, then the product $\sigma \circ \tau$ maps $a$ to $f$.

Identity substitution

$$e = \begin{pmatrix} 1 & 2 & \dots & n \\ 1 & 2 & \dots & n \end{pmatrix},$$

does not change the arrangement of elements, plays the role of a unit. For each permutation $\omega$ there is a unique inverse $\omega^{-1}$ such that $\omega \circ \omega^{-1} = \omega^{-1} \circ \omega = e$.

Task 10. Prove that the definition above, multiplication of substitutions, is associative.

Task 11. Show that the substitution $\omega^{-1}$ arises from the given one if its top and bottom rows are interchanged.

The set of permutations of $n$ elements forms a group (invertible mappings of a finite set $M$ onto itself), it is called the “symmetric group of $n$th degree” and is denoted by $S_n$.

Task 12. Write down the substitutions corresponding to the axial symmetrims of the square (Fig. 5) $S_{(24)}$, $S_{(13)}$, $S_l$, $S_m$ and the rotation $R_0^{270^\circ}$ (here (24) is a straight line passing through points 2, 4, etc.).

Task 13. Prove that the group of permutations of four elements consists of 24 elements.

Task 14. Make sure that not each of these substitutions can be matched with a self-aligning square.

The subsequent problem shows that there are less than 24 elements in the symmetry group of a square - each self-alignment of a square corresponds to a substitution (4 vertices of the square), but not every substitution corresponds to a self-alignment of a square.

This is how a square differs from a triangle: a triangle’s symmetry group consists of six elements and the substitutions of 3 vertices of the triangle are also six, and the symmetry group of a triangle is isomorphic to the group of substitutions of 3 elements.

Note that the symmetry group of a square (as well as a triangle) is non-commutative:

$$S_{(13)} \circ S_l = R_0^{-90^\circ} \neq R_0^{90^\circ} = S_l \circ S_{(13)}.$$

Task 15. Find all the variable planes that map the square onto itself (there will be a total of them in everything).

Task 16. Make a table of compositions of a variable plane that map the square onto itself (similar to the multiplication table for numbers from 1 to 9).

Task 17. Prove that the number of different permutations of a set of $n$ elements is $n!$ ($n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$).

In conclusion, we note that the properties and structure of abstract and concrete realizing groups are studied mathematically by a discipline called group theory, which has not found wide application in many branches of mathematics, theoretical physics, chemistry, crystallography, communication theory and other sciences.
