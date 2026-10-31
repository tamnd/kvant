---
id: 1976-3-boltyanskiy-zagadka-aksiomyi-parallelnyih-9d2c81af
issue: kvant_1976_3
year: 1976
number: "3"
title: The mystery of the “parallel axiom”
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 6, 7, 8
tag: ZQ1A
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 5411e00e48c383f99b1516806ecfcb8bd229e8c41fb89de3f0f0041e45f6e963
prompt_sha256: draft-1
translated_from: content/ru/1976/03/articles/03_boltyanskiy-zagadka-aksiomyi-parallelnyih-9d2c81af.md
source_content_sha256: b4b559b14beb2702fab724b685ff3e3e37b3daa7ff0083fabb44503a9d1096c6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## The mystery of the “parallel axiom”

### Unusual association

In one city, an association of collectors was established, uniting philatelists, numismatists, eye of needle collectors, etc. It was decided that the board of the association should consist of an odd number of people (this is convenient for voting). It was also decided that the board would be located in one building, and each person (i.e., board member) would have his own intercom telephone. And in order not to complicate the internal communication device, they decided not to install a switch, but to directly connect each person with telephone lines to any three persons.

“Well,” said one of the founders of the association, “I think this organization of the board’s work is quite convenient.”

“I especially like,” said the second (the famous Collector of mathematical curiosities), “that the work of the board can be described by an abstract axiomatic scheme.” Judge for yourself, we have three initial concepts: “person”, “line”, “connects”, and we want the following *axioms* to be true:

1. *number of persons is odd*;
2. *each line connects exactly two persons*;
3. *each person is connected by lines to exactly three other persons*.

- Well, what is the point of this axiomatics? Can any theorems be derived from it to form a “theory” that reflects the workings of our government?

- Why, if you please! Firstly, axiom 1 shows that at least one person exists (after all, zero is an even number!). Further, axiom 3 convinces us that since there is at least one person, then there will be three others, so that the total number of persons is not less than four. Finally, once again applying axiom 1, we find that *the total number of persons is not less than five*. This is the first theorem of this “theory”.

- Well, this statement, in fact, can be considered a theorem, since you proved it, that is, you logically deduced it from the axioms.

- Or here’s another example of a very simple theorem: *among any five people there will definitely be two who are not connected by a line*.

- Well, this is understandable: otherwise at least four lines would be connected to each of these five.

- Absolutely right! By the way, you said: the line is “connected” to the person. This can be given a clear definition within the framework of our axiomatics. Namely, if $A$ is some person and $l$ is a line connecting it with some other person, then the pair $(A,l)$ will be called *input*.

— And now we can say that each person $A$ participates in exactly three inputs $(A,l_1)$, $(A,l_2)$, $(A,l_3)$. This will mean that three lines $l_1$, $l_2$, $l_3$ are “connected” to $A$ (axiom 3).

- Wonderful! — The Collector of Mathematical Curiosities smiled.

— Continuing your reasoning, we can formulate the following theorem: *the number of all inputs is odd*. After all, persons are an odd number (axiom 1), and each person participates in exactly three inputs.

Suddenly, the Gatherer's face darkened. His voice became dull.

— Unfortunately, it can also be proven that *the number of inputs is even*. After all, each line $l$ (connecting, say, persons $A$ and $B$) participates in two inputs: $(A,l)$ and $(B,l)$, so the number of all inputs is twice the number of all lines.

- Yes, but this contradicts the previous theorem?

——That’s the trouble. It turns out that our axiomatics is *contradictory*, since two theorems that contradict each other can be deduced from it. So our theory burst: the communication system described by axioms 1, 2 and 3 is simply impossible to implement.

### Another axiomatics

- What should we do? Should the number of board members be even? But we really wanted to avoid this!

“Why, there is another way out,” answered the Collector of Mathematical Curiosities. — Let us leave axioms 1 and 2 the same, and replace the third axiom with the following:

1. *each person is connected by lines to exactly four other persons*.

True, you will have to lay a larger number of lines, but the axiomatics will become consistent, and the theorems will be preserved. As before, the total number of persons is at least five; of any six persons there will be two who are not connected by a line; the total number of inputs will be even (and there is no longer any contradiction here). It will be possible to prove further theorems.

- Excuse me, but why are you so sure that there are no contradictions? Yes, the number of inputs is now okay; but perhaps, proving more and more new theorems, we will still someday come across a contradiction. After all, you won’t claim that you know in advance all the theorems that can be proven in a theory based on this new axiomatics! And if so, then who can guarantee the absence of contradictions?

- Oh, I'm quite sure here! Now I will explain to you the reason for such confidence. I hope you don’t doubt the “correctness” of arithmetic?

- I don’t doubt it at all; but what does arithmetic have to do with it?

- And that’s what it has to do with it. Now, from the “material” of arithmetic, I will build, as mathematicians say, a *model* for the axiomatics under consideration. By the way, how many people (approximately) will there be on the board?

— I think at least 30 people.

- Wonderful! Let us agree to consider the numbers 1, 2, $\ldots$, 36, 37 as “persons”.

It is convenient to place them on a circle (Fig. 1) so that after 37 “next” there is the number 1. Now we will call pairs of numbers “lines”, and only those pairs in which the numbers are either next to each other or one after another on this circle. For example, “lines” would be the pairs $(1;3)$, $(4;5)$, $(37;2)$; but the pair $(3;6)$ will not be a “line” - the numbers are too far from each other.

⟦figure⟧
Fig. 1

⟦figure⟧
Fig. 2

- I think I understand what you want. In this, as you said, model, there are 37 “persons”, i.e. an odd number (axiom 1). Each line connects exactly two persons (axiom 2), since a pair consists of two numbers. In addition, it is clear that in each “person” there are exactly four lines (axiom 3); this can be explained by the diagram shown in figure 2. This means that in this model all axioms 1, 2, 3 are satisfied. However, why does this guarantee the consistency of the axiomatics under consideration?

- Well, this model is “made” of numbers! If two contradictory theorems could be deduced from axioms 1, 2 and 3, then this contradiction would also appear in this model. It turns out that when reasoning about numbers, we could get a contradiction. But, it seems, you don’t doubt the infallibility of arithmetic?

- Well, I understand your arguments. And let me repeat them, so to speak, in general terms. You are considering two theories, $P$ and $Q$. Theory $P$ (arithmetic was taken as it) is beyond doubt and is considered as unshakable and infallible. Theory $Q$ is a new theory defined by a list of axioms. We need to obtain guarantees of the consistency of the theory $Q$. For this purpose, the following technique is used: from the concepts of theory $P$, as from “building material”, they try to construct a model of theory $Q$, i.e., a scheme in which all the axioms of theory $Q$ are satisfied; if this can be done, then the consistency of the theory $Q$ is proven.

### Strange geometry

— We have moved somewhat away from discussing issues related to the collectors association. But since I collect mathematical curiosities, I now want to offer you one of them: a rather unusual model of geometry.

- I’ll be happy to “take a look” at this curiosity.

— Imagine that one point $O$ is removed from the plane (or, as mathematicians say, *knocked out*) (it exists, of course, but we don’t seem to consider it a “point”). However, we will continue to consider all other points (other than $O$) as points.

- Is this the whole trick?

- Just a moment of patience. We will now call each circle passing through this punctured point $O$ “*straight*” (we will also include “*circles of infinite radius*”, i.e. straight lines passing through $O$). figure 3 shows several “straight lines”.

- This is already unusual. We take obviously curved lines and declare them “straight”. But why is this?

⟦figure⟧
Fig. 3

⟦figure⟧
Fig. 4

— Let’s, for example, draw a “straight line” through two points $A$ and $B$. How to do this?

— You want the “line” to pass through the points $A$ and $B$. In addition, since this is a “straight line”, then it must also pass through the point $O$. This means that we need to draw a circle through three points $A$, $B$, $O$ (Fig. 4). Every student can do this.

- But such a “direct” *exists* and, moreover, *only one*. Do you agree?

- Yes, because three points uniquely define a circle.

- This means that in this model the axiom is fulfilled: *a straight line passes through two different points and, moreover, only one*.

“I think I’m beginning to be interested in your curiosity.”

— Now look at figure 5. It shows a triangle $ABC$. To find the sum of the angles of this triangle, we can take the sum of the marked angles at the point $O$. And these angles together make up a straight angle. This means that in this model *the sum of the angles of a triangle is* $2d$.

⟦figure⟧
Fig. 5

⟦figure⟧
Fig. 6

- Amazing!

- Note also that in this model, through a point lying outside a given “line” there passes the only “line” that does not intersect this one. This will be a circle tangent to the given “straight line” at the point $O$ (Fig. 6): after all, the point $O$ is considered to be punctured, so that the two depicted “straight lines” do not have common points.

— It turns out that in this model the “parallel axiom” is also satisfied?

- Absolutely right. And in general, in this model all the axioms (and therefore theorems) of the geometry that is studied in school are fulfilled (it is called *Euclidean geometry*, named after the scientist who gave a systematic presentation of it over 2000 years ago). True, I did not fully describe the model. It was not said how to measure lengths, which triangles should be considered isosceles, etc. In addition, it is necessary to add another point $\infty$ to complete this model. But the essence of the matter is clear: we have built a model of ordinary (Euclidean) geometry.

- What happens? The original theory $P$ is geometry, and from the “material” of this theory a model of the same theory is built?

- Absolutely fair! I brought this model only to show that it is not so strange to consider curved lines as “straight” in some model.

### The tragedy of Lobachevsky

- And now - another exhibit from the collection of mathematical wonders. We are talking about geometry discovered by the great Russian mathematician N. I. Lobachevsky.

— As far as I know, he constructed a geometry in which through a point one can draw more than one parallel to a given line (Fig. 7).

⟦figure⟧
Fig. 7

- Right. And although all of Lobachevsky’s reasoning was logically flawless, during his lifetime he never achieved recognition of his ideas. The conclusions were too unusual.

- For example?

- Well, for example, parallel lines come closer together (Fig. 8). It is even possible to construct an “infinite triangle” whose sides are parallel in pairs (Fig. 9). And although figure 9 shows curved lines, in Lobachevsky’s geometry there are straight lines that are located exactly like this. Further, the sum of the angles of a triangle is always less than $2d$, etc., etc.

⟦figure⟧
Fig. 8

⟦figure⟧
Fig. 9

- But this is not really true!!!

- Here, here! Lobachevsky's contemporaries said the same thing. And he understood that the point here is whether the geometry that is obtained from the axioms underlying it is contradictory or not; in addition, the talk: “in reality, everything is not so” is based only on the fact that a small part of space is accessible to our observations, where the differences between Euclidean geometry and its geometry are not noticeable (they lie beyond the accuracy of measurements). And, by the way, modern physics increasingly confirms this.

- Marvelous. But, as far as I understand, you wanted to talk about a purely mathematical confirmation of the correctness of Labachevsky’s geometry?

— More precisely, about its *consistency*.

- Oh, I understand! Apparently, you want to say that from the “material” of some theory $P$, the correctness of which we have no doubt, it is possible to construct a *model of Lobachevsky geometry*?

- Absolutely right! And this theory $P$ is Euclidean geometry! It turns out that from the “material” of Euclid’s geometry it is possible to construct a model of Lobachevsky’s geometry.

- So what, Lobachevsky knew about this?

- No; but he built another wonderful model. He managed to construct a model of Euclidean geometry from the “material” of his geometry.

- So, if everyone were confident in the infallibility of Lobachevsky’s geometry and doubted the correctness of Euclid’s geometry, then with this model it would be possible to convince everyone that Euclid’s geometry is also consistent! But it would be desirable for everything to be the other way around.

### Belated justice

- You now see that Lobachevsky understood well what a model was and how the consistency of its geometry could be proven. It was necessary, having accepted Euclidean geometry as the initial theory $P$, to build from its “material” a model of the theory $Q$ - Lobachevsky geometry. But Lobachevsky failed to do this. Such models were found only after the death of the scientist.

- Who did this?

- Beltrami, Cayley, Klein, Poincaré and other scientists.

- So, are these models very complex?

- No. This is how, for example, the model found by the outstanding French mathematician Henri Poincaré is constructed. In this model, only points lying inside some circle $K$ are considered. “Straight lines” are defined as follows: a circle (or straight line) is taken that intersects the circumference of the circle $K$ at a right angle, and the part of this circle lying inside $K$ is declared “straight”. figure 10 shows several “straight lines” in this model.

⟦figure⟧
Fig. 10

- This model is a bit like the Euclidean geometry model that we talked about earlier. There, too, circles were taken as “straight lines”.

⟦figure⟧
Fig. 11

⟦figure⟧
Fig. 12

- And, please note, in this model it can also be proven that there is only one “straight line” passing through two points. We can consider triangles in this model (Fig. 11). And figure 12 shows that through a point outside the “line” $a$ one can draw *infinitely many* “lines” that do not intersect with the “line” $a$. Two of them (those that touch the straight line $a$ on the boundary of the circle $K$, i.e., as if at “points at infinity”) are parallel to the straight line $a$. Well, figure 13 shows an “infinite triangle”, the sides of which are parallel in pairs. In short, this is precisely the model of Lobachevsky geometry. Of course, I have not described this model completely: it is necessary to indicate how lengths are measured, determine which figures are considered equal (congruent), etc. But in general terms, the model is built exactly like this.

⟦figure⟧
Fig. 13

⟦figure⟧
Fig. 14

—Have other scientists, whose names you named, built the same model?

- Oh no! Now many different models of Lobachevsky geometry are known. For example, in the works of Klein and Cayley, a model was constructed in which only points lying inside a certain circle $K$ are also considered, but they consider the *chords* of this circle (without ends) to be “straight lines”. On this model it is even easier to see that through a point outside the “line” $a$ there are infinitely many “lines” that do not intersect with $a$ (Fig. 14). However, angles, for example, are measured more difficult in this model than in the Poincaré model.

- Yes, your “mathematical wonders” are very interesting. Now we understand the significance of the discovery of N. I. Lobachevsky, who not only constructed a completely unusual geometry, but also laid the foundation for finding more and more new “geometries”. I heard that mathematics now considers many different spaces and geometries, and they are applied in physics and other fields. There are probably many amazing spaces, geometries, and mathematical “worlds” in your collection?

- Yes, of course. But we'll talk about this some other time.
