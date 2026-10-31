---
id: 1976-11-tsinman-paradoks-issledovatelya-6647ddb9
issue: kvant_1976_11
year: 1976
number: "11"
title: '"The Researcher''s Paradox"'
authors:
  - Цинман Л. Л.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 9, 10, 12
tag: NP93
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4862046fc592cb47a47c4cc95f47b3e132d8ca5aca8c69210788533170a9da20
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/04_tsinman-paradoks-issledovatelya-6647ddb9.md
source_content_sha256: 0bc780ff6114f5a7c0b20f4747d14069ffb43fbabd9f71fa798c957152fe5839
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

L. Tsinman

"Paradox Explorer"

When proving a statement using the method of mathematical induction, a necessary situation arises. Let us illustrate this with two examples.

Example 1

Let us prove by mathematical induction that for all natural numbers $n$ the following statement is true: the sum of the cubes of the first $n$ natural numbers is the square of some natural number.

Let us denote this statement by $A(n)$. Proofs by the method of mathematical induction are carried out, as is known, in two stages.

a) Basis of induction: $A(1)$. Let's make sure $A(1)$ is fair:
$$1^3 = 1^2.$$
6) Induction step: $A(k) \Rightarrow A(k+1)$. Let us assume that for some natural number $k$ the statement $A(k)$ is true, and we will prove that then $A(k+1)$ is also true. So, there is a way to find a natural number $p$ for which
$$1^3 + 2^3 + \ldots + k^3 = p^2.$$ (1)
Let us prove that then there exists a natural number $q$ for which
$$1^3 + 2^3 + \ldots + k^3 + (k+1)^3 = q^2.$$ (2)
From (2) and (1) it follows that we need to prove the existence of such a $q$ for which
$$(k+1)^3 = q^2 - p^2.$$ (3)

But how could this be proven? Naturally, the path to proof is not visible.

So, an attempt to prove our statement by direct application of the method of mathematical induction encountered difficulties in carrying out the induction step.

Let us return again to the consideration of $A(n)$ and check its validity for several initial values ​​$n$:
$$1^3 = 1^2;$$
$$1^3 + 2^3 = 3^2;$$
$$1^3 + 2^3 + 3^2 = 6^2;$$
$$1^3 + 2^3 + 3^3 + 4^3 = 10^2;$$
$$1^3 + 2^3 + 3^3 + 4^3 + 5^3 = 15^2.$$

Taking a closer look at these equalities, we come to the hypothesis: for all natural numbers $n$ the following statement is true: the sum of the cubes of the first $n$ natural numbers is the square of a natural number equal to the sum of these numbers.

Let us denote this statement by $B(n)$. Of course, $B(n)$ carries more information than $A(n)$, and so it is natural to consider it a stronger statement. Having proven $B(n)$, we obtain the validity of $A(n)$ as an obvious consequence.

Let us now try to apply the method of mathematical induction to the proof of the strengthened statement.

a) Justice $B(1)$ has actually already been established:
$$1^3 = 1^2.$$
6) Let us assume that for some natural number $k$ $B(k)$ is true:
$$1^3 + 2^3 + \ldots + k^3 = (1 + 2 + \ldots + k)^2.$$ (4)
Let us prove that then $B(k+1)$ is also true:
$$1^3 + 2^3 + \ldots + k^3 + (k+1)^3 = (1 + 2 + \ldots + k + k + 1)^2.$$ (5)

⟦folio 10⟧

Using equality (4), we can reduce the proof of equality (5) to the proof of equality
$$(k+1)^3 = (1+2+\ldots+k+k+1)^2 - (1+2+\ldots+k)^2 - \left[ \frac{(k+2)(k+1)}{2} \right]^2 - \left[ \frac{(k+1)k}{2} \right]^2 = (k+1)^3.$$

Let us transform the rule of parts of equality (6):
$$(1+2+\ldots+k+k+1)^2 - (1+2+\ldots+k)^2 = \left[ \frac{(k+2)(k+1)}{2} \right]^2 - \left[ \frac{(k+1)k}{2} \right]^2 = (k+1)^3.$$

So, equality (6) establishes. Thus, for all $n$ $B(n)$ is proved, and therefore $A(n)$.

Example 2 *)
One day, a teacher gave his students the following homework problem: to prove, by using the method of mathematical induction, that for any natural number $n$ the equality $A(n)$ is true:
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2n-1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2n} < \frac{1}{\sqrt{n}}.$$

Kolya V., sitting at home to prove this equality, accidentally rewrote the conditions of the equality with an error, adding 1 to the denominator. Thus, he took $B(n)$ as proof of a stronger equality:
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2n-1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2n} < \frac{1}{\sqrt{n+1}}.$$

Here is his proof.
a) We make sure that $B(1)$ is fair:
$$\frac{1}{2} < \frac{1}{\sqrt{2}}.$$
6) Let us show that from the validity of $B(k)$ for some natural number $k$
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2k-1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2k} < \frac{1}{\sqrt{k+1}}$$
This equality also holds for $k+1$:
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2k-1)(2k+1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2k} < \frac{1}{\sqrt{k+1}}$$
To do this it is enough to prove that
$$\frac{2k+1}{2k+2} < \frac{\sqrt{k}}{\sqrt{k+1}}.$$

But equality (9) is equivalent to the false equality $k+1 < 0$.

⟦folio 12⟧

There is no solid evidence at all.

Here the skilled reader may want to object. Excuse me, he will say, how, for example, is it possible to show that some geometric construction problems cannot be solved using a compass and a ruler? What's the difference?

But the difference is that in construction problems we are not talking about general constructions, but about molky constructions using a compass and a ruler. In this way, we precisely formulate the means that we are going to use for the solution. And in this case, it becomes possible to somehow describe the class of problems that are solved by these means. Therefore, when we are offered a specific construction task, we can try to determine whether it belongs to this class or not.

At the turn of the 19th and 20th centuries, a method of constructing mathematics was proposed that allows one to obtain proofs in the field directly. Various proofs for this method in the form of formal systems.

Here we will not try to explain exactly what a formal system is. Let's just say that in formal systems, meaningful mathematical statements were written in the form of formulas that were constructed according to precise rules. A formula is called `доказуемой` if it can be derived from `аксиом` (axioms are pre-fixed initial formulas) in a finite number of steps using pre-fixed `правил вывода`. This is the aforementioned clarification of the concept of proof.

Mathematical logic is the study of formal systems *). This article is not the place to write about it. I just emphasize that the solution is general

*) For a schoolchild who wants to get acquainted with mathematical logic, we recommend the books by P. P. Stoll “Sets. Logics. Aximatic Theories" (M., "Provesshie", 1968), E. Mendelson "Introduction to Mathematical Logic" (M., "Hayka", 1971) and P. S. Novikova "Elements of Mathematical Logic" (M., "Hayka", 1973).

asking about paradoxical pairs, as well as many other more important questions (for example, about the consistency of a particular branch of mathematics or about the independence of certain trading aximons) is often possible after preliminary formatting.

**Theorem**

Within the framework of the arithmetic of natural numbers, given in the form of a formal system, it is possible to answer the question posed above. There are several formal arithmetic systems. Let $S$ be one of these systems. The author of the article obtained the following result.

**Theorem. The system $S$ contains paradoxical pairs.**

Point 1 of the definition of a paradoxical pair requires that $A(n)$ be a very strong consequence of $B(n)$. The concept of a very significant consequence, naturally, also requires clarification. In the proof of the formulated theorem of some theories, a specific horse and ction $B(n)$ forms a paradoxical pair with any of its members.

Conjunction of several statements to a complex proposition made up of these statements using the conjunction “and”. Thus, a conjunction of several statements is true if and only if each of these statements is true. It is natural to consider that every conjuncture is its very consequence.

The formation of the theorem shows that in a formatted arithmetic system the real can be confronted with the “researcher’s paradox.” This must also be taken into account when making meaningful calculations using the method of mathematical induction.
