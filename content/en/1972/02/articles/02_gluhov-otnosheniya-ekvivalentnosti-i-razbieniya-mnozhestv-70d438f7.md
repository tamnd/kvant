---
id: 1972-2-gluhov-otnosheniya-ekvivalentnosti-i-razbieniya-mnozhestv-70d438f7
issue: kvant_1972_2
year: 1972
number: "2"
title: Equivalence relations and partitioning of sets
authors:
  - Глухов М. М.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 5, 6, 8
tag: FFZ5
lang: en
source: kvant_digital
extraction: vision
content_sha256: d25cad821ce7d438ed7f4cfdd54222e215bd4caaa3c61853039dbad2cc9aad70
prompt_sha256: draft-1
translated_from: content/ru/1972/02/articles/02_gluhov-otnosheniya-ekvivalentnosti-i-razbieniya-mnozhestv-70d438f7.md
source_content_sha256: f8c8e459a2e9de884eabbaadb2c0b316ac318bf1069f54c0114d0bbbbc2266df
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

M. M. Shukhol

Misunderstood equivalence
and partitioning of the set

Try to imagine all the variety of semantic relationships of the word “class”: “working class”, “student of the 10th grade”, “kαιota of the 1st grade”, “class of mammals”... No matter how different these relationships may seem, the word “class” in all cases has the same origin - it is always associated with the classification, or partitioning, of any set into disjoint classes. The concept of “class” and its numerous subdivisions (family, type, category, species, variety, genus, category, and others) is widely used in literally all areas of human activity. For example, when we need to study the objects of a set in connection with some of their properties, we strive to divide this set into classes so that all elements of one class behave in the same way with respect to interrelated properties, and then it becomes possible to study a whole class of objects based on one of its representatives.

Thus, biology does not study each plant individually, but divides all plants into classes, families, genera and species, so that when studying, say, the logical family, one flower is constructed as a representative of an entire family (or species). When studying a class by its representative, one usually tries to choose the most simple one from the point of view of other properties (not of interest to us at the moment). Each of us has used this opportunity more than once, for example, when solving an equation, replacing one equation with another, simpler, but having the same roots, that is, contained in the class of equations equivalent to the given one.

To partition a set, that is, to distribute its elements into classes in such a way that each element falls into one and only one class, one usually uses various characteristics inherent in the elements of a given set. For example, the objects depicted in Fig. 1.

⟦folio 4⟧

there were relations of equality (of numbers, figures, functions), relations of “more than” and “less than” for numbers, relations of divisibility for integers, relations of parallelism and perpendicularity for lines and polygons. In everyday life, relationships between people were widespread: relationships of seniority, kinship, neighborhood, partnership, belonging to the same nation, profession.

Now look more closely at one relation, for example, the relation of equality of numbers. Numerical equalities are correct (true) and incorrect (false). For example, the equality 5 = 5 is true, but 5 = 2 is false. If $x_1$ and $x_2$ are unknown numbers, then the equality $x_1 = x_2$ (the statement “$x_1$ is equal to $x_2$”) does not have a specific meaning: it depends on the “unknowns” $x_1, x_2$, is their function: for each specific numerical value $x_1, x_2$ it will be true or false.

In the general case, we will call a biary (or binary *) relation on the set $M$ a statement about the elements of the set $M$, which depends on two variables and turns into a true or false statement when substituting into it the variables of any specific elements from $M$. In general, the relation is written as $x_1\Theta x_2$ ($x_1 = x_2, x_1 < x_2, x_1 \parallel x_2, x_1 \perp x_2$, etc.). Often together "attitude $x_1\Theta x_2$" is simply said "attitude $\Theta$". For example, together “relation $x_1 = x_2$” we say “equality relation”. The term “order relation”, “neighborhood relation”, etc. has a similar meaning. If the relation $a\Theta b$ is true, then it is also said that $a$ and $b$ are related by the relation $\Theta$ or are in the relation $\Theta$. If the relation $\Theta$ has the property that the truth of $a\Theta b$ always implies the truth of $b\Theta a$, then it is called “symmetrine”. (In what follows, we will sometimes call symmetrically “property 1.”) For example, the relations of parallelism and perpendicularity of straight lines are symmetrical, but the relation < on the set of real numbers is not symmetrical (5 < 8 is true, and 8 < 5 is false).

The relation $\Theta$ on the set $M$ is called *reflexin* (“property 2”). if $a\Theta a$ is true for any element $a$ of $M$, and transimitive (“property 3”) if the truths of $a\Theta b$ and $b\Theta c$ entail the truth of $a\Theta c$. For example, the relation of equality of numbers is reflexive and transitive, the relation of perpendicularity of lines is not reflexive and not transitive, and the relation “less than” for numbers is transitive, but not reflexive.

Problem. Find out which of the properties 1-3 have the divisibility relation for integers, the “intersect” relation (that is, would have one common point) for plane lines, and the neighborhood relation for people.

Sickening equivalence

Let us now return to the question that interests us: what relations, defined on a certain set $M$, induce *partitioning* of this set into classes? In other words, what properties should relations $\Theta$ have, according to which the set $M$ can be divided into disjoint classes such that

1) any two elements (different or the same) from the same class are in the relation $\Theta$,
2) no two elements from different classes are in the relation $\Theta$?

The answer to this question is:

Theorem. The relation $\Theta$ on the set $M$ can and only can induce a *partition* of the set $M$ when it is reflexive, symmetrical and transimitive.

⟦folio 5⟧

Proof. Let the relation $\Theta$ induce a partition of the set $M$, that is, the sets $M$ can be partitioned into classes satisfying conditions 1) and 2). Whatever element $a$ we take, it belongs to some class of our partition. According to 1), $a$ is in relation to $\Theta$ with itself: $a\Theta a$ is true, so $\Theta$ is reflexive. If, further, $a\Theta b$ is true, then, as follows from 1)–2), the elements $a$ and $b$ belong to the same partition class. Then from 1) it follows that $b\Theta a$ is also true. This means that for any $a, b \in M^*$) from $a\Theta b$ follows $b\Theta a$, that is, the relation $\Theta$ is symmetrical.

Do not read the data until you are sure that the relation $\Theta$ is transitive!

Thus, if the relation $\Theta$ induces a partition of the set $M$, then $\Theta$ is reflexive, symmetric and transitive: properties 1–3 are necessary for $\Theta$ to induce a partition of the set $M$.

Now it is clear why we could not divide a person into groups of people respecting each other and why the relation of perpendicularity did not induce the division of straight planes. The relation of “reflection” and perpendicularity is not transitive (and not reflexive).

Let us now prove sufficient properties 1–3. Let $\Theta$ have properties 1–3, and $a$ be an arbitrary element of the set $M$. Let us denote by $M_a$ the class (set) of all such elements $x$ from $M$ for which $a\Theta x$ is true:

$$M_a = \{x \mid a\Theta x \text{ — истинно}\}.$$

In this way we will obtain a certain set of classes. Since by property 1 $a\Theta a$ is true, then $a \in M_a$ (by definition of the class $M_a$) and, consequently, each element of the set $M$ belongs to at least one of the resulting classes. Let us show that any two classes $M_a, M_b$ either coincide or do not intersect. Indeed, if $M_a$ and $M_b$ have at least one common element $c$, then $a\Theta c$ and $b\Theta c^*$. By property 2, from $b\Theta c$ it follows $c\Theta b$, and from $a\Theta c$ and $c\Theta b$, by property 3 we obtain $a\Theta b$. So $a\Theta b$ is true. Let us now take an arbitrary element $d$ from the class $M_b$. By the definition of the class $M_b$ true $b\Theta d$, and by property 3 from $a\Theta b$ and $b\Theta d$ it follows $a\Theta d$; means $d \in M_a$. So, if $d \in M_b$, then $d \in M_a$. It is similarly proven that from $d \in M_a$ it follows $d \in M_b$ (carry out the corresponding reasoning yourself). This proves that $M_a = M_b$, that is, classes that have at least one common element, coincide. Thus, each element of the set $M$ is contained in some class and different classes do not intersect. This means that we have a partition of the set $M$. Let us show that this partition is real and induces the relation $\Theta$, that is, conditions 1)—2) are satisfied. Let the elements $a$ and $b$ be contained in the same class. Since $a \in M_a$, this means that $b \in M_a$ (in the previous form both to be committed are equal!), that is, $a\Theta b$. So, any two elements from the same class are in relation $\Theta$: condition 1) is satisfied. Now let $a$ and $b$ be two arbitrary elements from different classes, so that $M_a \neq M_b$. If there were $a\Theta b$, then this means that $b \in M_a$, that is, the classes $M_a$ and $M_b$ having at least one element $b$. But then, according to what was proven above, it would be $M_a = M_b$, which contradicts the conditions. This means that $a\Theta b$ is false, that is, elements from different classes are not in the relation $\Theta$ (condition 2 is satisfied). The theorem has been proven.

When fixing the set $M$, elements containing in one class are usually called an equivalence relation, and the classes of the resulting partition themselves are called equivalence classes.

*) The sign ∈ is read “belongs”: $u \in M$ means that $a$ is an element from the set $M$.

⟦folio 6⟧

Now the theorem proved above can be formulated more briefly: the relation $\Theta$ on the set $M$ can and only can induce a partition of the set $M$ when it is an equivalence relation.

Thus, if we want to find out whether some relation $\Theta$ induces a partition of some set $M$, then we need to check whether the relation $\Theta$ is an equivalence relation on $M$.

For example, the set of all circles of a plane falls into classes of concentric circles, since the relation of concentricity of circles is reflexive, symmetrical and transitive. (At the same time, we naturally believe that

**Fig. 3.**

every circle is concentric to itself.) It is also very simply verified that the similarity relation of triangles is reflexive, symmetrical and transitive. Consequently, the set of all triangles is divided into classes of similar triangles.

Let's take one less obvious example. Let $Q$ be the set of all fractions of the form $\frac{a}{b}$, where $a, b$ are integers and $b \neq 0$. For each fraction $\frac{a}{b}$ we determine the class $Q_{a,b}$, assigning the fraction $\frac{c}{d}$ to this class if and only if $ad = bc$. Will the result be a division of all fractions into disjoint classes?

We have defined some relation $\Theta$ on the set $Q$:

$$\frac{a}{b} \Theta \frac{c}{d}$$ if and only if $ad = bc.$

Let us find out whether $\Theta$ is an equivalence relation.

1. Reflect. For any fraction $\frac{a}{b} \frac{a}{b} \Theta \frac{a}{b}$, since $ab = ba$.

2. Symmetry. If $\frac{a}{b} \Theta \frac{c}{d}$, then $ad = bc$, or $cb = da$. The last equality means that $\frac{c}{d} \Theta \frac{a}{b}$.

3. Transitivity. Let $\frac{a}{b} \Theta \frac{c}{d}$ and $\frac{c}{d} \Theta \frac{e}{f}$, that is, $ad = bc$ and $cf = de$. Multiplying the last equality by $f$ and $b$, respectively, we get:

$$adf = bcf, \ bcf = bde.$$

Hence we have $adf = bde$ and $af = be$ (can be shortened to $d$, since $d \neq 0$!). But $af = be$ just means that $\frac{a}{f} \Theta \frac{e}{f}$.

Thus, $\Theta$ is an equivalence relation and therefore the set of all fractions falls into disjoint classes of equivalent (or, as they say in school, equal in magnitude) fractions. So, having an equivalence relation on a certain set, we can divide this set into classes. But you can also do the opposite: first divide the set into classes, and then determine the equivalence relation, considering by definition two elements to be equivalent if and only if they belong to the same class of the partition in question.

For example, this is how the attitude of “being classmates” appears: first, children new to school are divided (almost arbitrarily) into classes, and then children who find themselves in the same class are called classmates.

**Isn’t it possible to save money?**

If we often have to check whether a given relation is reflexive, symmetrical and transitive, then naturally

⟦folio 8⟧

a set of cosmonauts on the Voskhod and Voskhod-2 spaceships, a set of “parts of the world” (without Antarctica!), etc. Already from this small list it is clear that one class includes sets of very different natures and the only thing common to all of them is that they are all of equal power, that is, any one of them can be uniquely mapped onto any other. Now we will form the definition of a natural number: by a natural number we call any class of equally powerful finite sets.

At first, such a definition can be quite surprising: such a seemingly simple thing as a natural number is defined through something cumbersome and hard to see - through an entire class of sets! However, if you really think about this definition and get used to it, you will agree that it really reflects the “quantitative essence” of the concept of a natural number. This definition reveals the so-called abstraction of identification: first we divide all finite sets into classes of equal sets, then we “identify” all sets of one class and think of the result of this identification as a certain natural number.

Since each class of equipower sets is completely determined by any of its representatives, we can speak of a natural number determined by any set of a given class. The number defined by the set $M$ is denoted by $|M|$ and is called the order, or cardinality, of the set $M$. For natural numbers, you can introduce a notation system that is not associated with specific sets. Of course, this can be done in different ways. Historically, this was the case: different peoples had different notation systems and named natural numbers. (This is discussed in more detail in the article by I.M. Yaglom “Systems of Numbers”, see «Kvant», No. 6, 1970). Adhering to the currently generally accepted notation system and named, we can say that the number 1 (one) is the class of a set equal to the set of capitals of the Soviet Union, the number 2 (two) is the class of a set equal to the set of human eyes, and so on. By adding one more element to any finite set, we get a new set that is not equal to the original one. Carrying out this process, we will obtain an infinite sequence of sets that are not equal to each other and the natural numbers determined by it:

1, 2, 3, ...

Rashchina says that a rational number is a fraction of the form $\frac{a}{b}$, where $a, b$ are integers and $b \neq 0$. However, such a definition is not complete, since it does not immediately follow from it whether, for example, the numbers $1/2$ and $3/6$ are equal or not. Therefore, it comes immediately to add: the rational numbers $\frac{a}{b}$ and $\frac{c}{d}$ are equal if and only if $ad = bc$. As a result, it turns out that a rational number is not just a fraction, but a whole class of fractions. Thus, the concept of a rational number is introduced more carefully as follows.

Consider the set $Q$ of all fractions and define on $Q$ the relation $\Theta$ by putting $\frac{a}{b} \Theta \frac{c}{d}$ if and only if $ad = bc$. We have already shown above that $\Theta$ is an equivalence relation and, therefore, the set $Q$ will develop into disjoint classes. We will call any two fractions of the same class of the specified partition accumulative. Now we can formulate a definition: a rational number is any class of equivalent fractions. After everything said earlier about the definition of a natural number, we define a rational number as a class of fractions in a very simple way.
