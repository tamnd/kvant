---
id: 1974-2-belskiy-sadovskiy-koltsa-d300a7b8
issue: kvant_1974_2
year: 1974
number: "2"
title: Rings
authors:
  - Бельский А. А.
  - Садовский Л. Е.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 3, 4, 6, 7
tag: 5GQF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 43fc3e12c2f2c4ec01b68beb6176af33ba5c839840fc22c09b37a21760c6ee5a
prompt_sha256: draft-1
translated_from: content/ru/1974/02/articles/04_belskiy-sadovskiy-koltsa-d300a7b8.md
source_content_sha256: df503bdeca982af7aa2e2102d8b4b43dac24bd0a8296ff186a674682c0055705
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

People come into contact with the concept of rings back in high school: for the first time - mastering the operation of adding and multiplying numbers, then - learning to operate with polynomials (polnomials). In both cases, certain rules (axioms) that govern these operations are common. For the sake of studying precisely these general properties of the operations of addition and multiplication (numbers, polynomials or, as we will see later, objects of a different nature) as such, in their internal connection with each other, unrelated to the nature of the elements on which they are performed, the concept of a ring was introduced in algebra.

What is a ring? The precise definition of this object is related to the concept of operation. We will teach from him.

Consider an arbitrary set $M$. We will say that an operation is defined on it if a rule is established according to which any two elements $a$ and $b$ from $M$ are assigned a third element $c$ of the same set. So, for example, if $M$ is the set of all integers (the standard notation $Z$ is accepted for it), then addition $c = a + b$ and multiplication $c = ab$ are two different operations on this set. If, say, $M$ is a set of two distinct elements $a$ and $b$ (general notation $M_2 = \{a, b\}$), then all possible operations on it can be completely described. To do this, you first need to list all possible pairs of elements from $M_2$. Here they are: $(a, a)$, $(a, b)$, $(b, a)$, $(b, b)^*$; then you have to decide which element from $M_2$ belongs to which pair.

It is most convenient to perform a specific operation on a set consisting of

*) Thus, we distinguish between the pairs $(a, b)$ and $(b, a)$, that is, we consider the so-called “ordered pairs”.

Describe a finite number of elements with a table (this method was proposed by the English mathematician A. Cal (1821-1895), after whom the tables are now called Cal tables).

In the left column and in the top line the elements of the set $M$ are written as indicated in Table 1; at the intersection of the row that begins with the element $a$ and the column that begins with the element $b$, the element that is matched by the pair $(a, b)$ under consideration is indicated. For example, if the pair $(a, b)$ is associated with the element $a$, then this circumstance is written as in Table 1'. Further, if the pair $(b, a)$ is matched with the element $b$, then table 1'' is obtained.

Table 1
Table 1'

⟦folio 3⟧

The completed table completely defines the operation. Tables 2-5 give examples of various operations on a set of two elements. It will be useful for the reader to describe in tables all other operations on this set (there are 16 in total; we advise you to find them).

Table 6 shows an example of an operation on the set $M_3 = \{a, b, c\}$ of three elements. Count how many operations exist on $M_3$.

In the random operations known to us from the argument, names are assigned: say, addition, subtraction, multiplication. In the general case, which was just discussed, the operations do not have special names. Only for convenience, this or that operation is sometimes called multiplication, and even less often - addition, although

![Table 1](table1.png)
[Table 2](table2.png)
[Table 3](table3.png)
[Table 4](table4.png)
[Table 5](table5.png)
[Table 6](table6.png)

If during this operation the parameters $(a, b)$ and $(b, a)$ are compared to the same element, that is, $a * b = b * a$, then the elements $a$ and $b$ are said to commute, but with respect to the operation described in Table 3, these same elements do not commute. If an operation also means that all pairs commute with respect to it, then it is said to be commutative. Of course, addition and multiplication of integers are commutative operations; tables 2 and 6 also define commutative operations.

Prove that the Cayley table is a commutative operation of symmetrine with respect to the main diagonal (this is the name given to the line from the upper left corner of the table to the lower right corner).

Let us now formulate in general form one more property that an operation may (or may not) have. Let $a, b$ and $c$ be three (not necessarily

⟦folio 4⟧

different) elements of the set $M$. If $a * (b * c) = (a * b) * c$ is for these elements, then they are called associating.

I emphasize that in both parts of the last equality the elements $a, b, c$, regardless of the placement of brackets, are written out in the same order. In this sense, the triple of elements $a, b, c$ are ordered.

So, for example, the elements $b, a, b$ of $M_2$ with respect to the operation described in Table 3 are associative, but with respect to the operation from Table 5 they are not associative (check this!). An operation with respect to which all triples of elements of the set $M$ are associative is called associative. Addition and multiplication of integers are not only commutative, but also associative operations. It will be useful for the reader to come up with an example of such an operation that would be commutative, but not associative.

Now we are ready to define a ring. Kolcho is a set $M$ with two specific operations. One of them is usually called addition and denotes the element comparable to its pairs $(a, b)$ by $a + b$, and the other is usually called multiplication and denoted the element compared to pairs $(a, b)$ by $ab$. The specificity of these operations lies in the following five requirements that apply to them:

addition must be commutative and associative, that is, for all pairs $(a, b)$ and for all simple $(a, b, c)$ elements from $M$ there must be equality:

1) $a + b = b + a$;
2) $(a + b) + c = a + (b + c)$;
3) in the set $M$ there must exist a maximal element 0 such that $a + 0 = a$ for all $a$ of $M$; in this case, element 0 is called zero;
4) for every $a$ of $M$ there must exist a maximal element $c$ of $M$ such that $a + c = 0$; the element $c$ is called zero and multiplication first. If you look closely, the following circumstance becomes clear:

industrial element $a$ and often denoted by - $a$ (so in this case $c = -a$);

5) There is only one thing required from multiplication: it must be distributively related to addition, that is, for any $a, b, c$ from $M$ the equalities must take place

$$a (b + c) = ab + ac;$$
$$b + c) a = ba + ca$$

(it is necessary to distinguish between these two equalities because multiplication is not assumed to be commutative). This property is often called “distributive multiplication with respect to addition.”

That's what a ring is. It is very important to keep in mind that from requirements 1) - 4) it follows that “uniqueness” of zero and “uniqueness of the opposite element” follow. This means the following: a) if $0_1$ and $0_2$ are two elements of the ring $M$ that satisfy requirements 3), then $0_1 = 0_2$; 6) if $a + c_1 = a + c_2 = 0$, then $c_1 = c_2$. In other words: there is only one zero in the ring, and each element of the ring has only one opposite element. Indeed, by virtue of 1) and 3):

$$0_1 = 0_1 + 0_2 = 0_2 + 0_1 = 0_2.$$

This proves a). Further, if to both sides of the equality

$$a + c_1 = a + c_2$$

add, say, $c_1$, then you get

$$c_1 + (a + c_1) = c_1 + (a + c_2),$$

or, by virtue of 2),

$$(c_1 + a) + c_1 = (c_1 + a) + c_2,$$

or, due to the fact that $a + c_1 = c_1 + a = 0$, we get

$$0 + c_1 = 0 + c_2,$$

or $c_1 = c_2$, which proves 6).

Examples of rings are the set of all integers that we already know, the set of all different numbers, the set of all polynomials with real coefficients with respect to the general operations of addition and multiplication. If you look closely, the following circumstance becomes clear:

⟦folio 6⟧

us, $a_2 + b_2 = n(q'_2 + q'_2) + r' + r''$, and again
$$\overline{a_2 + b_2} = r' + r''.$$
Therefore, $\overline{a_1 + b_1} = \overline{a_2 + b_2}$, which is what needed to be proved.

So, one operation on $Z_n$ is defined. It is called addition, and the result of applying it to the two remainders of $Z_n$, as already mentioned, is called the sum.

Proposition 1. Addition on $Z_n$ satisfies requirements 1) - 4) listed in the definition of flask.

Proof. Thanks to equality (3), which was discussed in detail above, the commutativity and associativity of the introduced direct addition follows from the commutativity and associativity of the addition of integers. Axim 3) on the existence of zero is satisfied due to the existence of the remainder $\overline{0}$ (it is given by numbers that are multiples of $n$): $\overline{a} + \overline{0} = \overline{a} + 0 = \overline{a}$. Finally, the opposite of the remainder $\overline{a}$ serves, very indo, the remainder $-\overline{a}$, so that $-\overline{a} = -\overline{a}$, and axiom 4) also holds.

Here are some tables of addition in $Z_n$ (see tables 7-8).

Let us now introduce multiplication into $Z_n$. Set for $\overline{a}, \overline{b}$ from $Z_n$
$$\overline{ab} = \overline{ab}$$ (4)
and call $\overline{ab}$ the product of $\overline{a}$ and $\overline{b}$, and the action itself is called multiplication. Of course, in this case, too, you need to prove that the definition is correct, that is, you need to verify the following:

shem:
if $\overline{a}_1 = \overline{a}_2$ and $\overline{b}_1 = \overline{b}_2$, then $\overline{a_1b_1} = \overline{a_2b_2}$.

Let, in fact, be $a_i = q'_i n + r'$, $i = 1, 2$, and $b_j = q'_j n + r'$, $j = 1, 2$. Then
$$\overline{a_1b_1} = \overline{(q'_1 n + r')(q'_1 n + r'')} = \overline{n (nq'_1 q'_1 + r'q'_1 + r''q'_1) + r'r''} = \overline{r'r''}$$
$$\overline{a_2b_2} = \overline{n (nq'_2 q'_2 + r'q'_2 + r''q'_2) + r'r''} = \overline{r'r''}$$.

Proposition 2. Multiplication by $Z_n$ satisfies aximms 5) - 8) listed in the definition of flask.

Proof. The distributive connection with addition, as well as the commutativity and associativity of multiplication follow, thanks to (4), from similar properties of multiplication of integers. The role of one for multiplication is played by the remainder $\overline{1}$.

So, $Z_n$ is a commutative, associative and unity quantity.

Multiplication in any flask $R$ is essentially characterized by the cases in which the equality turns out to be true
$$ab = 0.$$ (5)
So, for example, in flask $Z$ integers

⟦folio 7⟧

numbers, equality (5) is satisfied only when either $a = 0$ or $b = 0$. A similar statement is true for $Z_3$ (see Table 9). But in the ring $Z_6$, for example, equality (5) is valid for $a = \overline{2}$ and $b = \overline{3}$, that is, the product of non-zero factors turns out to be equal to zero here. It is customary to say that an element $a$ of a ring $R$ is a zero divisor if $a \neq 0$ and if there is an element $b \neq 0$ in $R$ such that $ab = 0$. Thus, the remainder $\overline{2}$ in $Z_6$ is a zero divisor; on the other hand, at a distance above the ring $Z$ and $Z_3$ there are no zero divisors at all.

Along with equality (5), multiplication in a ring is also characterized by

| | $\bar{0}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ |
| $\bar{1}$ | $\bar{0}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ |
| $\bar{2}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ |
| $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ |
| $\bar{4}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ |
| $\bar{5}$ | $\bar{0}$ | $\bar{5}$ | $\bar{4}$ | $\bar{3}$ | $\bar{2}$ | $\bar{1}$ |

Table 10. Multiplication by $Z_4$

numbers, equality (5) is satisfied only when either $a = 0$ or $b = 0$. A similar statement is true for $Z_3$ (see Table 9). But in the ring $Z_6$, for example, equality (5) is valid for $a = \overline{2}$ and $b = \overline{3}$, that is, the product of non-zero factors turns out to be equal to zero here. It is customary to say that an element $a$ of a ring $R$ is a zero divisor if $a \neq 0$ and if there is an element $b \neq 0$ in $R$ such that $ab = 0$. Thus, the remainder $\overline{2}$ in $Z_6$ is a zero divisor; on the other hand, at a distance above the ring $Z$ and $Z_3$ there are no zero divisors at all.

Along with equality (5), multiplication in a ring is also characterized by

| | $\bar{0}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ |
| $\bar{1}$ | $\bar{0}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ |
| $\bar{2}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ |
| $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ |
| $\bar{4}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ |
| $\bar{5}$ | $\bar{0}$ | $\bar{5}$ | $\bar{4}$ | $\bar{3}$ | $\bar{2}$ | $\bar{1}$ |

Table 11. Multiplication by $Z_6$

Such elements are called inverses. In the ring $Z$ the set of inverse elements consists of only 1 and -1; in the ring $Z_3$ all elements except 0 are inverse, and in the ring $Z_6$ only the remainders $\bar{1}$ and $\bar{5}$ are inverse, so that $\bar{5} \cdot \bar{5} = \bar{1}$. (The reader is advised to check that in $Z_6$ all other elements of $x$ are not inverses.)

We thus became acquainted with the concept of a ring, examined the simplest examples and the first structures of the characterization of this new object: zero divisors and inverse elements. Teler, you can begin to study such important issues as, for example, the question of simple elements of a ring and decomposition into prime factors. We do not set this goal for ourselves now: it is natural to devote a separate conversation to it.

In conclusion, here are a few tasks to solve on your own.

1. Prove that the set of polynomials with real coefficients with common addition and multiplication is a ring without a zero divisor. What is the set of inverse elements of this ring?

2. Make addition and multiplication tables in $Z_5$ and $Z_7$ and prove that not only do these collections not have a zero divisor, but also that every non-zero element in them is an inverse.

3. Prove that any ring $Z_p$ with a prime number $p$ has the properties mentioned in the previous problem.

4. Prove that in the ring $Z_n$ every nonzero element is either its inverse or is not a zero divisor.

5. Prove Statement 4 for any ring that has a unique ring, consists of a finite number of elements, and is associative.
