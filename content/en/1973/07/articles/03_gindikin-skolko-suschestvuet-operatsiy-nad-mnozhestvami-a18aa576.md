---
id: 1973-7-gindikin-skolko-suschestvuet-operatsiy-nad-mnozhestvami-a18aa576
issue: kvant_1973_7
year: 1973
number: "7"
title: How many set operations are there?
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 12
page_labels: 2-10
tag: P4BN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3bf3cb2f903ad8b06815a606bd6be30b6d81bcddcec7f7a31fbe35680eb7a9a6
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/03_gindikin-skolko-suschestvuet-operatsiy-nad-mnozhestvami-a18aa576.md
source_content_sha256: f5a05fa782bad692bb5725bd50237e1cc18f2a96dbdcadab600d0637e94adba2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

S. G. Gindikin
How many set operations are there?

Sets can consist not only of numbers, but also of people, cars, animals, plants, etc. In life, sets are usually called by different names. So, for example, speaking not a lot of cows, but a hundred cows, not a lot of horses, but a mabun of horses, not a lot of tools, but a set of tools, etc.

These words are taken from a mathematics textbook for fourth grade. You probably know that you can perform the operations of union and intersection on sets, which are sometimes called addition and multiplication of a set. Have you ever heard of any other set operations? Maybe you know what the difference of a set or their symmetric difference is? How many operations on sets are there at all? Is their number finite or infinite? In order to answer these questions, first of all we need to understand what should be called an operation on sets? We give a general definition of such operations and talk about some of their interesting properties. More difficult things are discussed in the text, typed in small font (this part of the text can be omitted during the first reading).

1. Union and intersection
Recall that the union $A \cup B$ of the set $A, B$ consists of elements included in at least one of the set $A, B$, and the intersection $A \cap B$ consists of elements that are included in both of these sets. The formation of union and intersection or figure 1 will be constructed, on which the “circles” symbolize the sets on which the operation will be performed, and the shaded area corresponds to the set that is obtained as a result of the operation. It is noteworthy that sets can be of the most diverse nature, and yet these diagrams are very convenient for studying operations on them.

Both operations under consideration have the following two properties:
$A \cup B = B \cup A; \ A \cap B = B \cap A$ (commutative),
$A \cup (B \cup C) = (A \cup B) \cup C;$
$A \cap (B \cap C) = (A \cap B) \cap C$ (associativity).

Commutativity is very much from the definitions (see Fig. 1). figure will help you prove associativity 2. The placement of parentheses dictates the order in which the operations must be performed. Figure suggests that in whichever of the above orders the debinding operations are performed, the result will be a set consisting of

⟦folio 3⟧

Elements included in at least one of our sets. Similarly, in the case of intersection, a set is obtained consisting of elements included in each of our sets. We advise the reader to conduct careful reasoning, and we do not rule out that it will not be too easy to translate into words what is very/noof figure.

Associativity allows, for example, in the case of a union when performing an operation on sets $A_1, \dots, A_n$ multiple times, not to fix the order in which the operations are performed using parentheses, and to speak simply about the union $n$ of the set $A_1 \cup A_2 \cup \dots \cup A_n$; this set consists of elements containing $A_1, \dots, A_n$ in at least one of the set. The commutative law shows that the order $A_1, A_2, \dots, A_n$ can be changed as desired.

In the numerical case, addition and multiplication are connected to each other by the following relation: $a (b + c) = ab + ac$ (distributivity of multiplication relative to addition). This ratio allows you to subtract the common factor out of the bracket and open the brackets. For a set of such relations there are two:

$$A \cap (B \cup C) = (A \cap B) \cup (A \cap C);$$
$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C).$$

figure 3 shows diagrams illustrating these relationships. To prove, for example, the first of them, it is enough to note that the set standing both on the right and on the left consists of elements included in the set $A$ and at least one of the sets $B$ or $C$. Note that in some cases the second relation would have the form $a + bc = (a + b) (a + c)$, which, of course, is not true.

The first of relations (2) shows that any sequence of unions and intersections can be transformed into such a sequence of these operations that first all intersections are performed, and then unions. Make sure, for example, that $(A \cup B) \cap ((C \cap D) \cup E)$ can be converted to $(A \cap C \cap D) \cup (A \cap E) \cup (B \cap C \cap D) \cup (B \cap E)$. You can also do it in such a way that all joins will be performed first (use the second relation). Think through similar transformations in the numerical case.

2. Difference and symmetric difference

The difference $A \setminus B$ of the sets $A$ and $B$ is called the set consisting of those elements $A$ that are not included in $B$ (Fig. 4). The difference is not a symmetric difference. To prove, for example, the first of them, it is enough to note that the set standing both on the right and on the left consists of elements included in the set $A$ and at least one of the sets $B$ or $C$. Note that in some cases the second relation would have the form $a + bc = (a + b) (a + c)$, which, of course, is not true.

The first of the relations (2) shows that any sequence of unions and intersections can be transformed into such a sequence of these operations that first all intersections are performed, and then unions. Make sure, for example, that $(A \cup B) \cap ((C \cap D) \cup E)$ can be converted to $(A \cap C \cap D) \cup (A \cap E) \cup (B \cap C \cap D) \cup (B \cap E)$. You can also do it in such a way that all intersections will be performed first (use the second relation). Think through similar transformations in the numerical case.

⟦folio 4⟧

It is neither a commutative nor an associative operation. figure 5 will help you prove this. Note also that difference is not the inverse operation of union (which, as we have already said, is sometimes called addition of a set). You will be convinced of this by proving the following relation:

$$(A \setminus B) \cup B = A \cup B;$$
$$(A \setminus B) \cup (A \cap B) = A.$$

The symmetric difference $A \triangle B$ set $A$ and $B$ consists of elements included in one and only one of the sets $A$ and $B$ (Fig. 6): $A \triangle B = (A \setminus B) \cup (B \setminus A)$. The symmetric difference is a commutative and associative operation. Prove this using figure 7. For the symmetric difference and intersection, the distributive relation holds:

$$A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$$
(see Fig. 8). However, $A \triangle (B \cap C)$ may not be the same as $(A \triangle B) \cap (A \triangle C)$ (see Fig. 9). The situation is analytical numerical. There are deep reasons for this, as we will see.

3. Universal set and complementary set

We will propose in what follows that all the sets under consideration are subsets of some fixed set. We will call it the universal image. If, for example, sets of points on the plane are considered, then the set of all points on the plane is universal; If sets of natural numbers are considered, then the set of all natural numbers is universal.

If the fixed universal set is $I$, then we can talk about an additional $\bar{A}$ set $A$ (up to $I$): $\bar{A} = I \setminus A$, that is, $\bar{A}$ consists of elements $I$ not included in $A$

⟦folio 5⟧

(see Fig. 10). The complementary universal set is empty: $\bar{I} = 0$ (empty set).

The additional operation allows you to link the union and intersection operations as follows:

$$\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}.$$

Indeed, $\bar{A} \cap \bar{B}$ consists of elements included in $\bar{A}$ and $\bar{B}$, that is, not included in either $\bar{A}$ or $\bar{B}$, or, what is the same, not included in the union $\bar{A} \cup \bar{B}$, which is what is asserted. From the obtained correspondence, that

$$\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}, \quad \bar{A} \cap \bar{B} = \bar{A} \cup \bar{B}.$$

(3)

To obtain the first of these correspondences, it is enough to replace that the coincidence of the sets implies the coincidence of their complement and that $\bar{C} = C$ (the complement to will additionally coincide with the original set). To obtain the second, it is necessary to take into account that since $\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}$ is for any $A$ and $B$, then we can take $\bar{A}, \bar{B}$: $\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B} = \bar{A} \cap \bar{B}$ as these sets. Correspondences (3) are called De Morgan's law. They show that union can be expressed in terms of intersection and complement, and intersection can be expressed in terms of union and complement.

Note that $A \setminus B = A \cap \bar{B}$, which means $A \triangle B = (A \cap \bar{B}) \cup (\bar{A} \cap \bar{B})$.

4. Law of Duality

The study of operations on sets consists of obtaining various points connecting the operations. We mean statements of the following type. Some sequences of operations are performed on the set $A_1, \dots, A_n$ in two ways, and it is stated that these combinations of operations always (for any $A_1, \dots, A_n$) lead to the coincidence of the sets. All laws (1), (2), (3) are also the same points. It is important to be able to obtain new ones from existing points. For example, we have already actually used the fact that if in a point we replace $A_1, \dots, A_n$ with $\bar{A}_1, \dots, \bar{A}_n$ or go to the complementary in both parts of the points, we will also get dots.

Now we will indicate a very important way to transform points containing the operations of union, intersection and addition (and only these operations).

The law of duality. If at a point containing only the operations of union, intersection and addition, we replace all intersections with unions, and all unions with intersections, then we again obtain points.

Check that in this way, from the commutativity and associativity of the union, we obtain the commutativity and associativity of the intersection, and vice versa, and from one distributive correspondence (2) - another.

We will not give a proof of this statement here, but will give an example of how it can be obtained.

Consider the points

$$A_1 \cap ((A_2 \cup \bar{A}_3) \cap (\bar{A}_4 \cap A_5)) = A_1 \cap (\bar{A}_2 \cap A_3) \cup (\bar{A}_4 \cap A_5),$$

it is easy to check, use De Morgan's laws. Let's go to the complementary point in both parts and replace all $A_1, \dots, A_5$ with $\bar{A}_1, \dots, \bar{A}_5$:

$$\bar{A}_1 \cap ((\bar{A}_2 \cup A_3) \cap (\bar{A}_4 \cap A_5)) = \bar{A}_1 \cap (\bar{A}_2 \cap \bar{A}_3) \cup (\bar{A}_4 \cap \bar{A}_5).$$

Let us now replace all the operations of union and intersection with (3). If we simplify the resulting points, we use the fact that two lines are over one expression

⟦folio 6⟧

We can destroy it, then we get the desired identity:

$$A_1 \cup ((A_2 \cap A_3) \cup (A_4 \cap A_5)) = A_1 \cup (A_2 \cup A_3) \cap (A_4 \cup A_5).$$

A strict proof is carried out from the same messages.

5. What is a set operation?

Try to answer this question yourself, and then compare your conclusions with what is said below.

Specifying an operation on a set means, first of all, indicating a way to construct a third set from two given sets $A$ and $B$; let's denote it by $A \bigcirc B^*$). If we remain in the definition at this point, we will get an immense number of operations. But perhaps you were able to notice that in all the operations that we showed, the question of whether any element is included in $A \bigcirc B$ was completely decided based only on which of the sets $A$, $B$ it is included in and which it is not. Let's include this requirement in the definition of the operation. Let us formulate it in more detail.

If two sets $A$ and $B$ are given, then the universal set $I$ is divided into four disjoint subsets: the set $A \cap B$, consisting of elements contained in the general sets $A$ and $B$; the set $\overline{A} \cap \overline{B}$, consisting of elements that are not included in any of these sets; the set $\overline{A} \cap B$, consisting of elements included in $B$, but not in $A$, and the set $\overline{A} \cap \overline{B}$, consisting of elements included in $A$, but not included in $B$. We will call these sets single sets. Our additional requirement for the operation is that if two elements are in the same dolbe, then he or she is included

*) Of course, $A \bigcirc B$, like $A$, and $B$ must be contained in the universal set $I$.

Fig. 11.

in $A \bigcirc B$, or it is not included. In other words, $A \bigcirc B$ is the union of a certain number of slices. The breakdown of the good into slices is illustrated by the diagrams that we drew (in Fig. 11 the corresponding areas are colored in different colors); this is the reason why diagrams are useful in learning operations.

6. How many operations are there on a pair of sets?

Now we can easily answer this question. There are as many different operations as there are different ways to select the segments that make up $A \bigcirc B$. There are 4 segments, and there are 16 different ways of forming $A \bigcirc B$. There are the same number of different subsets in a set of 4 elements (counting the empty set and the entire set). These calculations can be carried out directly, or you can use the following combinatorial lemma, which will be useful to us later.

Lemma. A set of $n$ elements has $2^n$ different subsets.

Proof. Let $N$ be such a set. Let's number its elements somehow. Let us assign to each subset $M$ in $N$ a set of zeros and ones of length $n$, and in the $k$ place we put 1 if the $k$ element of the set $N$ is included in $M$, and 0 otherwise. Such sets are called double sets. Between the names

⟦folio 7⟧

Gestures in $N$ and double sets of length $n$ produce a one-to-one correspondence. In this case, a set of only zeros corresponds to an empty set, and a set of only ones corresponds to all sets $N$. So the number of subsets in $N$ is the same as the number of double sets of length $n$. Let us prove by induction that this number $f(n)$ is equal to $2^n$. At $n = 1$ this is obvious; let $f(n - 1) = 2^{n-1}$. Each set of length $n$ is obtained from a set of length $n - 1$ by adding 0 or 1, that is, from each set of length $n - 1$ two sets of length $n$ are obtained, and hence $f(n) = 2f(n - 1) = 2^n$.

Setting $n = 4$, we get that there are 16 subsets in a 4-element set and hence 16 operations on the two sets. These operations include operations $A \bigcirc B = 0$ (the empty set) for any $A$ and $B$ ($A \bigcirc B$ does not contain any slices) and $A \bigcirc B = I$ for any $A$ and $B$ ($A \bigcirc B$ is the union of all slices). We will denote these operations by 0 and 1, respectively. The operations also include $A \bigcirc B = A$, $A \bigcirc B = B$, $A \bigcirc B = \overline{A}$, $A \bigcirc B = \overline{B}$, since in all four random sets, the one on the right is the union of two slices (for example, $\overline{A} = (\overline{A} \cap B) \cup (\overline{A} \cap \overline{B})$). Let's list the remaining operations:
$A \bigcup B$, $A \cap B$, $A \setminus B$, $B \setminus A$, $A \triangle B$, $A \cup B$, $A \cap B$, $A \setminus B$, $B \setminus A$, $A \triangle B$.

Note that the operations included the formation of lobules *). From the fact that every operation is a union of segments, it follows that every operation can be expressed in terms of union, intersection and addition.

*) To represent the operations that we somewhat frivolously call “partitioning into slices,” there is a completely serious term “perfect disjunctive normal form,” and the slices are called “complete regular elementary conjunctions.”

Fig. 12.

Let us indicate another representation of operations through these three. Let's call the addition to the slice an appendage. By virtue of (3), makeweights correspond to the operations $\overline{A} \cup \overline{B}$, $A \cup B$, $A \cup \overline{B}$, $\overline{A} \cup B$. (This is also easy to verify with drawings). By specifying the operation $A \bigcirc B$, it is possible, in addition to listing which segments are included in $A \bigcirc B$, to indicate which segments are not included in it, and then $A \bigcirc B$ will be the intersection of the makeweights corresponding to these segments. For example, $\overline{A} \cap B = (A \cup B) \cap (\overline{A} \cup \overline{B}) \cap (\overline{A} \cup B)$ look at other examples yourself. The representation of operations in the form of intersection of makeweights *) can be obtained from the representation in the form of union of slices using the law of duality (do it!).

7. Binary tables for operations
Let us assign each slice a double set of two elements: $A \cap B => (1, 1)$, $\overline{A} \cap \overline{B} => (0, 0)$, $\overline{A} \cup B => (0, 1)$, $A \cup \overline{B} => (1, 0)$. Here 1 indicates that the slice is included in the corresponding set ($A$ or $B$), and 0 indicates that it is not included and, therefore, is included in the complement (see Fig. 12). When specifying the operation $A \bigcirc B$, we assign 1 to each slice encoded by such a set, if this slice

*) And there is a Serbian name for this representation; "perfect conjunctive normal form".

⟦folio 8⟧

is included in $A \bigcirc B$, and 0 if not. All this can be written in the form of a table in which the rows will correspond to the slices, and the line, for example, 1,0|0 should be perceived as an encoded entry of the phrase: if an element is included in the first set ($A$) and is not included in the second ($B$), then it is not included in $A \bigcirc B$. Such a table is called a double or Boolean operation table, and it completely specifies the operation. Above is a summary double table of all operations on a set pair.

Pay attention to the table columns corresponding to $A \cap B$, $A \triangle B$ and $\bar{A}$. If $(x, y)$ is a set corresponding to a slice, then in the column for $A \cap B$ there is simply $xy$, in the column for $A \triangle B$ there is the remainder of the division of $x + y$ by 2, and in the column for $\bar{A}$ there is the remainder of the division of $x + 1$ by 2. These operations are performed on the elements $x, y = 0,1$ are called arithmetic operations modulo 2, and for them all the basic laws of general arithmetic operations are preserved (commutativity, associativity, distributiveness of multiplication relative to addition) *). This fact allows us to replace the properties of the symmetric difference.

*) You can read about operations based on the model (arthmetic of remainders) in the magazine «Kvant» No. 5, 1970.

8. Operations on $n$ sets

We have actually already dealt with such operations, but they have always been expressed through operations on set pairs. Now we give a general definition. To specify an operation on a $n$ set means to specify a construction law for a set of any $n$ set $A_1, \dots, A_n$ of a uniquely defined set $f(A_1, \dots, A_n)$, and the question of the inclusion of some element in $f(A_1, \dots, A_n)$ is completely determined by which of the set $A_1, \dots, A_n$ this element is included in and which it is not. Let's put $A^\sigma = A$ at $\sigma = 1$ and $A^\sigma = \bar{A}$ at $\sigma = 0$. Note that the set $A_1^{\sigma_1} \cap A_2^{\sigma_2} \cap \dots \cap A_n^{\sigma_n}$ consists of all elements included in $A_j$ if $\sigma_j = 1$, and not included in $A_j$ if $\sigma_j = 0$. Operation $A_1^{\sigma_1} \cap A_2^{\sigma_2} \cap \dots \cap A_n^{\sigma_n}$ will, as with $n = 2$, be called a slice corresponding to the set $(\sigma_1, \sigma_2, \dots, \sigma_n)$. There are as many slices as there are double sets of length $n$, that is (by Lemma) $2^n$. At figure 13 you see the splitting at $n = 3$.

From the definition of the operation it follows that each operation $f(A_1, \dots, A_n)$ is a flow around a certain number of slices. To assign an operation to each slice, coded in two

⟦folio 9⟧

Fig. 13.

set σ, we put it in correspondence with 1 or 0, depending on whether this piece is included in $f(A_1, \dots, A_n)$ or not. The result of the operation is a double set of length $2^n$ (that’s how many slices there are), which means there are $2^{(2n)}$ different operations on sets. Since in all cases $f(A_1, \dots, A_n)$ is a union of segments, we simultaneously obtain that each operation is expressed through unions, intersections and complements. We get another idea if we consider two and three operations on the parts, they have the form $A_1^{\sigma_1} \cup \dots \cup A_n^{\sigma_n}$. Any operation can be represented as the intersection of makeweights.

So, it turned out that, firstly, there is a finite number of operations on $n$ sets, and, secondly, all these operations can be expressed in terms of operations on set pairs - union, intersection and complement $^*$). This explains that in many questions of set theory we are limited to considering these three operations. However, taking into account (3), we can limit ourselves to two operations: union and additional or intersection and additional.

There are other possibilities for choosing the basic operations through which all other operations are expressed. Consider, for example, the operation $A \cap B$. If you take

*) Consider the additional as an operation on one set ($n=1$).

as $A$ and $B$ the same set $C$, then we get $\overline{C}$. By performing these two operations in sequence, we obtain $A \cap B$. But any operation can be expressed through intersection and complement. This means that any operation can be expressed through a single operation $\overline{A \cap B}$. Check that all operations can also be expressed through the operation $A \cup B$. These two remarkable operations are called Schaefer operations. Prove that $\overline{A} \cup B$, $\overline{C}$ or $\overline{A} \cup B$, 0 can be chosen as systems of basic operations.

9. Monotonous operations.

Can all operations be expressed through unions and intersections without resorting to additional ones? It turns out not. In order to verify this, you need to find some property that all operations represented through union and intersection possess, but there are operations that do not possess this property. As we noted in point 1 when discussing correspondence (2), it is always possible to change the order of union and intersection so that intersections are performed first, and then unions. The possibility of such a representation is imposed for the purpose of definition on the set of slices of which $f(A_1, \dots, A_n)$ can consist if $f(A_1, \dots, A_n)$ is expressed through unions and intersections. The set of these segments must be arranged as follows: there are subsets $M_1, \dots, M_k$ in the set $N = \{1, 2, \dots, n\}$ and a segment substituting $\sigma = (\sigma_1, \dots, \sigma_n)$ is included in $f(A_1, \dots, A_n)$ if and only if either $\sigma_j = 1$ for all $j \in M_1$, or $\sigma_j = 1$ for all $j \in M_2$, and so on. For example, in the case of $(A_1 \cap A_3 \cap \bigcap A_5) \cup A_4 \cup (A_2 \cap A_5)$ we have: $M_1 = \{1, 3, 5\}, M_2 = \{4\}, M_3 = \{2, 5\}$. It is not difficult to see that such collections of sets are characterized by the fact that, together with each set $\sigma$, they contain all sets $\sigma'$, in which all those places in which $\sigma$ contains ones also have ones (we will symbolically denote this as follows: $\sigma' \geq \sigma$). Now it is clear that, for example, the operation $A \setminus B = A \cap B$ does not have this property: it coincides with the only part corresponding to the set (1, 0), and $(1, 1) \geq (1, 0)$ corresponds to the part not included in $A \setminus B$. Operations that are expressed through unions and intersections, as well as 0, 1, will be called multirelative. Obviously, the complement is also a slightly decimal operation: counting $n = 1$, we see that $A$ coincides with the fraction for $\sigma = (0) \leq \sigma' = (1)$.

⟦folio 10⟧

10. Linear operations

Every operation can be expressed in terms of $A \cap B, A \triangle B, I$. Indeed, $\overline{A} = A \triangle I$, $A \cup B = (A \cap B) \triangle (A \triangle B)$, and in section 8 we proved that any operation is expressed through intersection and addition. Let us explore this fact from the point of view of the arithmetic interpretation of operations. Let $f(A_1, \dots, A_n)$ be an arbitrary operation; Let's look at its binary table (see paragraph 7). Let us denote by $\tilde{f}(x_1, \dots, x_n)$ the value in this table corresponding to the binary set $(x_1, \dots, x_n)$.

If we express $f$ in terms of $A \cap B, A \triangle B, I$, then for $f$ an expression arises through arithmetic operations modulo 2. By opening the brackets and bringing similar terms, we obtain a representation for $\tilde{f}$ as a polynomial in $x_1, \dots, x_n$. Considering that $x_j$ take values ​​0, 1, and as a result only the remainder of dividing the value of the polynomial by 2 is taken, we can greatly simplify the form of the polynomial. Firstly, we can assume that all non-zero coefficients are equal to 1 (2x is divided by 2), and secondly, the variables $x_j$ will appear in monomials no higher than the first power $(x^2 = x$ for $x = 0, 1)$.

Let us now examine operations of this type: $f(A_1, A_2, \dots, A_n) = A_1 \triangle A_2 \triangle \dots \triangle A_n$. (In the recording we used commutative and associative $A \triangle B$; see paragraph 2.) The resulting set consists of such elements that are included in the odd number of the set $A_1, \dots, A_n$, and then we will call these operations oddity idikars. It is easy to verify this statement directly (for $n = 2, 3$, see Fig. 6, 7), and it can be noted that in this case $\tilde{f}(x_1, \dots, x_n) = x_1 + \dots + x_n$ modulo 2. This shows that, for example, the intersection $A \cap B$ cannot be expressed through the symmetric difference, since $A \cap B$ consists of elements that fall into two sets. If we add operation 1, we get more parity indicators $A_1 \triangle \dots \triangle A_n \triangle I$; they will be assigned polynomials of the first degree $x_1 + \dots + x_n + 1$. Again, we will not be able to express the intersection, since the elements that are not included in either $A$ or $B$ are not included in $A \cap B$. We will call the operations expressed through $A \triangle B$ and $I$ (that is, even and odd indicators) linear operations, and the remaining operations - non-linear. These terms are associated with the polynomials corresponding to these operations.

11. Description of the basic operation system

By a system of basic operations we understand such systems of operations that all other operations are expressed through them.

We already have several examples of a basic operations system. Moreover, in the previous two paragraphs we proved that the sets $\{A \cap B, A \cup B\}$, $\{A \triangle B, I\}$ cannot be taken as systems of basic operations. At the same time, we obtained the necessary conditions for such systems; they must necessarily contain incompletion and neotonic operations. It is remarkable that necessary and sufficient conditions are given in the same terms. We will not do this in the most general system. We will say that assumption 01 is satisfied for an operation system if this system contains 0 and 1.

Post's theorem. A system of operations satisfying Assumption 01 can be taken as a system of basic operations of the model and only the model when it contains neotonic and neotonic operations.

There is a general formulation of Post's theorem for any systems (without assumption 01); Moreover, the number of conditions of the theorem, then without assumption 01 they must be in paragraphs 9, 10. Obviously, they are preserved even under condition 01, since 0 and 1 are monotonic and linear operations $(A \triangle A = 0)$.

It will be sufficient to follow from the two problems below.

Task 1. Prove that under assumption 01, from any neotononic operation one can obtain an additional operation.

Let $f$ be a neonotonic operation and let $f(A_1, \dots, A_n)$ be included only corresponding to $\sigma$, and only corresponding to $\sigma' \geq \sigma$ not be included. Then, if in the $j$th place and in $\sigma$ and $\sigma'$ there is a 0, then instead of $A_j$ we substitute the empty set, but if both here and there there is a 1, then we substitute the universal set $I$. In other places, since $\sigma' \geq \sigma$, in $\sigma$ there is a 0, and in $\sigma' - 1$. Let us substitute the same set $A$ instead of these $A_j$. Then the must answering $\sigma$ turns into $A$, and the must answering $\sigma'$ turns into $A$. The resulting operation $\varphi(A)$ will be the same as $A$, since $\varphi(A)$ contains $A$ and does not contain $A$.

Task 2. Prove that under assumption 01, intersection can be expressed through any neonotonic operation and complement.

Try to solve this problem yourself. Our solution is given on p. 58.

*) See the book Gindikin S.G., Algebra of Logic in Problems, M., “Nauka”, 1972.
