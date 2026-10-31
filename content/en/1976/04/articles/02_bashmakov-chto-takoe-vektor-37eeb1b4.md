---
id: 1976-4-bashmakov-chto-takoe-vektor-37eeb1b4
issue: kvant_1976_4
year: 1976
number: "4"
title: What is a vector?
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2-4
tag: DR01
lang: en
source: kvant_digital
extraction: vision
content_sha256: e14117f0395350051e9084d84ec97b9a0d45897c8fed4efb0f421325118d06d5
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/02_bashmakov-chto-takoe-vektor-37eeb1b4.md
source_content_sha256: 929a841e83f7064a97d883c048cc729411d4d955747343b2d549b34e9025c980
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

What is a vector?

The word "vector" is found in mathematics, physics and applied disciplines. These words denote completely different objects that are not similar to each other. Thus, in a school geometry textbook, the concept of a vector is combined with the concept of a parallel transport (plane or space). In physics, when describing a series of quantities, they say that they have a vector character - such as the speed of mechanical movement, the force of attraction, the direction of the magnetic field. What is it that is common that allows all these objects to be called the same? How do you need to build a mathematical theory in order to obtain a concept that serves the needs of both mathematics and physics? This is what the article talks about.

1. Vector space

Mathematics has a wonderful way of defining a new concept by describing its properties. So, for example, instead of directly defining what a real number is (using decimal fractions or something else), most books list their basic properties, which are used in the future. This approach - it is called axiomatic - is very common in modern mathematics. The school geometry course is structured exactly like this. They will build similarly with vectors - they list the general properties inherent in all vector quantities, which are found both in mathematics and in its applications.

As always with the axiomatic approach, we will define not what a single, isolated “vector” is, but the totality of vectors at once - a vector space.

A vector space is a set M with two operations that satisfy a certain requirement *). However, these operations (usually called addition) assign a third element to each pair a, b of elements of the set M (this element is called the sum of elements a and b and denotes a + b). The second operation assigns to each element a of the set M and to each real number λ an element of the set M called the product of the element a and the number λ (this “product” is denoted by λa).

Let us list the requirements (vector space axioms) that these operations must satisfy:

1°. The addition of vectors obeys the combinational (associative) and commutative (commutative) laws:
$$x + (y + z) = (x + y) + z;$$
$$x + y = y + x.$$

2°. There is a zero vector: 0, such that x + 0 = x.

3°. For each vector there is a vector whose sum with the original vector is the zero vector.
$$4^\circ. (\lambda_1 \lambda_2)x = \lambda_1(\lambda_2x).$$
$$5^\circ. (\lambda_1 + \lambda_2)x = \lambda_1x + \lambda_2x.$$
$$6^\circ. \lambda(x + y) = \lambda x + \lambda y.$$
$$7^\circ. 1 \cdot x = x.$$

Here x, y, z are arbitrary vectors, $\lambda, \lambda_1$ and $\lambda_2$ are any real numbers.

2. Examples of space vectors

The vectors that are important to us are directed segments on a plane. However, to arrange a vector pro-
*) Compare with the definition of flask in «Kvant», 1974, No. 2, p. 4.

⟦folio 3⟧

the journey is not at all easy. So we'll start with simpler examples.

1. Linear functions
Let's consider all possible linear functions (given to the set R of all real numbers). Each such function is given equal to: $x \rightarrow ax + b$. It is clear that the sum of two linear functions is again a linear function. In the same way, if you multiply a linear function by a number, you get a linear function again. Moreover, all axims $1^\circ - 7^\circ$ are satisfied, and thus, the set of linear functions with these operations is a vector space.

2. Parallel transfers
Let us consider the set of all parallel translations of the plane. They can be added, sequentially performed one after another, multiplied by numbers. This is the vector space you encounter at school.

3. Row space
Consider fixed-length strings $n$ of real numbers: $(a_1, a_2, \dots, a_n)$. Let's define adding strings and multiplying them by numbers element-by-element:
$$(a_1, a_2, \dots, a_n) + (b_1, b_2, \dots, b_n) = (a_1 + b_1, a_2 + b_2, \dots, a_n + b_n);$$
$\lambda (a_1, a_2, \dots, a_n) = (\lambda a_1, \lambda a_2, \dots, \lambda a_n)$. Obviously, strings of length $n$ with such defined operations form a vector space.

4. Square triplexes
The set of square triplices $\{ax^2 + bx + c\}$ (the numbers $a, b, c$ can also be zeros) also forms a vector space with respect to the general operations of adding polynomials and multiplying them by numbers.

5. Polynomials
The set of all polynomials with the same operations also forms a vector space.

6. Functions
All functions defined on some numerical set A form a vector space with respect to the general operations of A, which is formed first on the number B (i.e., a directed segment belonging to the second class is laid off from B), and if point C is the end of the second segment, then AC is a directed segment belonging to the class corresponding to the sum of vectors. It is up to us to independently prove that this definition of the sum is correct, i.e. that the result does not depend on which directed segment from the first class we choose. Give a graphical definition of multiplication by a number. (Handling free vectors is difficult because

⟦folio 4⟧

that each of them represents a whole class of directed segments. Graphically, we always depict each class with one segment, which we can choose at our discretion. Therefore, we have to check that the result does not depend on the arbitrary representatives we choose.

3. Coordinates

Let's return to our first example - the vector space of linear functions.

Let's consider two functions:
$$f_1: x \rightarrow x,$$
$$f_2: x \rightarrow 1.$$

Any function $f: x \rightarrow ax+b$ can be represented as a linear combination of these functions: $f=af_1+bf_2$. The pair of numbers $(a, b)$ is called the coordinates of the linear function $f$.

The remarkable thing is that when adding linear functions, their coordinates add up like lines:
$$f_1: x \rightarrow ax+b \leftrightarrow (a, b),$$
$$f_2: x \rightarrow cx+d \leftrightarrow (c, d),$$
$$f_1+f_2: x \rightarrow (a+c)x+(b+d) \leftrightarrow (a+c,b+d);$$
But
$$(a+c,b+d)=(a,b)+(c,d).$$

Let's give a few more examples. In the vector space of parallel translations of the plane, you can choose two parallel translations (for example, into two non-parallel vectors of length 1), into which any translation is decomposed; the coefficients of this expansion are called the coordinates of the corresponding transfer.

Consider in the vector space of strings of length $n=4$ strings
$$f_1=(1,0,0,0), f_2=(0,1,0,0),$$
$$f_3=(0,0,1,0), f_4=(0,0,0,1).$$

We can represent any string $f=(a_1,a_2,a_3,a_4)$ as
$$f=a_1f_1+a_2f_2+a_3f_3+a_4b_4;$$
the numbers $(a_1,a_2,a_3,a_4)$ are called the coordinates of the row $f$.

In the vector space of square trinomials, for an arbitrary trinomial $f=ax^2+bx+c$ we have:
$$f=af_1+bf_2+cf_3,$$
$$f_1=x, f_2=x^2, \dots, f_n=x^n, \dots.$$

Then any polynomial $F$ can be written as a finite linear combination of the chosen polynomials; the coefficients of the expansion of the polynomial $F$ into the polynomials $f_0, f_1, \dots$ are its coordinates:
$$F(x)=a_mx^m+a_{m-1}x^{m-1}+...$$
$$...+a_1x+a_0=a_mf_m+a_{m-1}f_{m-1}+...$$
$$...+a_1f_1+a_0f_0 \leftrightarrow (a_m,a_{m-1},...,a_1,a_0).$$

Now we can ask a number of questions. How to choose a system of vectors in a given space into which any vector of this space can be decomposed? When can these systems be chosen as the final one? To what extent is the decomposition unique? And how are the expansion coefficients related to different systems of vectors?

The answers to these questions are provided by the branch of mathematics known as linear algebra. Here's a quick look at some of the results.

1. Inversion vector spaces are finite-dimensional and infinite-dimensional. In finite-dimensional systems, there are finite systems of vectors into which any vector in space can be expanded. In our examples, the spaces of linear functions, quadratic trinomials, strings, parallel translations, and free vectors are finite-dimensional. The spaces of all polynomials and all functions are infinite-dimensional.

2. For a finite-dimensional space, we can specify the smallest number $n$ such that there are $n$ vectors into which any vector in the space can be expanded. This number $n$ is called the dimension of space. Thus, the space of linear functions has dimension 2, the space of square trinomials
