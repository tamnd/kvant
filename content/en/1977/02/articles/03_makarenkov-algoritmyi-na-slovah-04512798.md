---
id: 1977-2-makarenkov-algoritmyi-na-slovah-04512798
issue: kvant_1977_2
year: 1977
number: "2"
title: Algorithms in words
authors:
  - Макаренков Ю. А.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
tag: QXP4
lang: en
source: kvant_digital
extraction: vision
content_sha256: ce3de45e0d0d545c5fd24668cfc4d9a1f032be79955732efd77e26a610740fd8
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/03_makarenkov-algoritmyi-na-slovah-04512798.md
source_content_sha256: d1d61b852643309317db1e02efe764d7bb6d4a0990e920cda2ad5c3556afd56f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Algorithms in words

At the end of the nineteenth and beginning of the twentieth centuries, a new object of study appeared in mathematics: strings of symbols taken from a fixed set. In our mathematical literature, cels are also called grouse words.

The famous German mathematician David Hilbert at the beginning of the century proposed a plan to prove the consistency of mathematics by constructing a calculus (that is, a transformation rule) for words. In the early thirties, it was found that “all mathematics” (and even “all arithmetic”) cannot be summed up in one calculus (this is Gödel’s famous theorem). Although Hilbert’s hopes were not fully realized, certain branches of mathematics were “formatized” in this way, and all modern research on the foundations of mathematics begins with a similar formalization. In many branches of mathematics (for example, mathematical linguistics and general algebra) and its applications (for example, programming languages), words have become one of the most important objects of study.

The theory of algorithms was born only in the thirties of our century. Since then, the concept of an algorithm has also become one of the most important in mathematics.

Although the word “algorithm” appears only in the last section of this article, it is all about words and algorithms that work with words.

Introductory example

We fix an equilateral triangle ABC (Fig. 1) on the plane. Let us denote by R the rotation of the plane by 120° counterclockwise around the center O of the triangle (Fig. 2); Let S denote the axial symmetry of the plane with the OB axis (Fig. 3). Each of the transformations R, S maps triangle ABC onto itself. Therefore, they are also called self-alignments of the original triangle. We will call self-combinations R and S elementary.

Let us consider all possible compositions of elementary self-alignments (“Geometry 7”, paragraph 77). Each such composition again, very conveniently, will be some kind of self-combination.

Like the usual operations of addition and multiplication of numbers, the operation of composition of self-combinations has a combinational, or associative, property: if f, g, h are self-combinations, then

$$f \circ g) \circ h = f \circ (g \circ h).$$

(This is true not only for self-alignments of a triangle, but also for arbitrary mappings of any set M into itself!) Therefore, in the “long-

Fig. 1.

In the new compositions of elementary self-combinations, the brackets can be placed in any order, which means that they can not be placed at all. For example,

$$(R \circ S) \circ (R \circ R) = R \circ ((S \circ R) \circ R) = R \circ S \circ R \circ R.$$

Unlike addition and multiplication of numbers, the operation of composition of self-combinations does not have any

⟦folio 3⟧

Fig. 2.
vorya, commutative, or commutative, property. So, in this case $R \circ S \neq S \circ R$ (cf. Fig. 4 and 5).

Let’s write at random some “long” composition of elementary self-combinations:
$$X = S \circ S \circ R \circ S \circ R \circ S \circ R \circ S \circ R.$$ (1)
What can be said about self-alignment $X$?

It is easy to prove that there are six self-alignments of the original triangle: the identity mapping $E$, leaving each point of the plane in place; turn by $120^\circ$ counterclockwise; turn $120^\circ$ clockwise; axial symmetries with axes $OA, OB, OC$. From figure 4 and 5 it is clear that the axial symmetry with the $OA$ axis coincides with the $S \circ R$ composition, and the axial symmetry with the $OC$ axis is the $R \circ S$ composition.

Task. Imagine a clockwise rotation by $120^\circ$ as a composition of elementary self-alignments.

Fig. 3.
So, our randomly written composition (1) is one of the six listed self-combinations. Which one exactly?

Of course, this question is easy to solve purely geometrically: continue with the original triangle all the indicated self-alignments in turn (don’t forget that the notation $f \circ g$ means: first $g$ matches, then $f!$) and look at the final position of the triangle.

For our purposes, it is significant that this same question can be solved using some algebraic calculation.

It's easy to check that
$$\begin{cases} S \circ R = R \circ R \circ S, \\ R \circ R \circ R = E, \\ S \circ S = E. \end{cases}$$

Moreover, in any composition of self-combinations the identity map $E$ can be omitted.

Since we have to compare the entire calculation, yes-

Fig. 4.
Fig. 5.

⟦folio 4⟧

Treat the composition sign $\circ$ like a dot when multiplying: we won’t write this sign. Equalities (1), (2) will then take the form

$$X = SSRSRSSR,$$

$$\begin{cases} SR = RRS, \\ RRR = E, \\ SS = E. \end{cases}$$

The composition $X$ can be transformed like this:

$$X = SSRSRSSR =$$

$$= (SS)R(SR)(SR)(SS)R =$$

$$= ER(RRS)(RRS)ER =$$

$$= R(RRS)(RRS)R =$$

$$= (RRR)(SR)R(SR) =$$

$$= E(RRS)R(RRS) =$$

$$= (RRS)R(RRS) = RRS(RRR)S =$$

$$= RRSES = RRSS = RR(SS) =$$

$$= RRE = RR.$$

Associative calculus

In the calculation we just carried out, we actually dealt with words (see the first paragraph of the statistic).

In the previous section, the letters $R$ and $S$ had a meaning: they denoted non-specific objects in the field—non-totor self-combinations. Now we will start studying abstract x letters and words - letters and words built from them that do not mean anything. (However, below we will return to the example from the previous section.)

The original set of letters from which words are built is called the alphabet. The number of letters in a word is called its length.

Let our initial alphabet consist of only two letters: $\{a, b\}$. Then there are 4 words of length 2: $aa, ab, ba, bb$; 8 words of length 3, etc. It is also allowed to talk about “one-letter” words, words of length 1; there are only two of them: $a$ and $b$. It is convenient to consider that there are also words that do not contain letters - an empty word. Let words be an analogue of an empty set. It is denoted in Greek by the letter $\Lambda$. Its length, of course, is considered to be 0.

Our “rules of the game” will look like this:

$$\alpha \leftrightarrow \beta,$$

(5)

Fig. 6.

Fig. 7.

where $\alpha$ and $\beta$ are some words. Rule (5) means that in any word you can substitute the word $\beta$ together with $\alpha$ and the word $\alpha$ with $\beta$. Rules of the form (5) are called substitutions.

Let's look at the substitution as an example:

$$abab \leftrightarrow bb.$$

(6)

In the words $\gamma = abababbabb$ the words $abab$ appears in three places (Fig. 6) or, as they say in mathematics, has three occurrences. The word $bb$ has two occurrences in the words $\gamma$ (Fig. 6). By using substitution (6) once, you can get 5 words from the word $\gamma$ (Fig. 7). By the word $abaab$, substitution (6) is not applicable: it does not include either the left or right side of this substitution.

When we evaluate $(10+2) \times (8-3)) : (15-3) = (12\cdot 5):12 = 60:12 = 5$, we are essentially applying substitutions $(10+2) \leftrightarrow 12, (8-3) \leftrightarrow 5, (12\cdot 5) \leftrightarrow 60$, etc.

Type substitution

$$\alpha \leftrightarrow \Lambda$$

(7)

means, firstly, that in any word together $\alpha$ you can “substitute an empty word”, that is, simply throw out the incoming words $\alpha$. If, for example, the substitution

$$bb \leftrightarrow \Lambda$$

(8)

apply in this way to the second in the word $\gamma$, you get the words $abababbaba$. Substitution of the form (7) means, secondly, that in any word between any two letters one can “insert” the words $\alpha$: it is natural to assume that an empty word appears between any letters. In addition, we apply substitution (7) “from right to left”, we can

⟦folio 5⟧

of course, "attribute" words $\alpha$ both in front and behind any word. By using substitution (8) you can get 6 words from the same word $\gamma$ (why?).

To define a “game”, it is necessary to fix some finite set of substitutions. Such a set (together with the alphabet) in mathematical logic is called associative calculus.

Two words are called adjacent in a given associative calculus if one of them can be obtained from the other by a single application of any of the substitutions of this calculus. Two words, $\delta$ and $\eta$, are called equivalent in this calculus if they can be “connected” by a chain of related words, that is, if there are words $\mu_1$, $\mu_2$, ..., $\mu_n$, which are in the chain $\delta$, $\mu_1$, $\mu_2$ ..., $\mu_n$, $\eta$ each word can have its own neighbors. We will denote the equivalence of the words $\delta$, $\eta$ as follows: $\delta \sim \eta$.

Of course, related words are equivalent.

Example 1

Consider in the alphabet $\{a, b\}$ associative calculus with substitutions

$$\begin{cases} ba \leftrightarrow aab, \\ aaa \leftrightarrow \Lambda, \\ bb \leftrightarrow \Lambda. \end{cases}$$

What words are equivalent in this calculus?

For example, $aababbaaaba \sim a$, since in the chain $aababbaaaba$, $aabaaaaaba$, $aabaaba$, $aaaaaba$, $ababa, aaabba, bba, a$ each word is interchanged with its neighbors.

Is it possible to indicate a way to find out for any two words in our alphabet whether they are equivalent or not?

Comparison of equalities (4) with substitutions (9) suggests this method. Consider the equilateral triangle $ABC$ and its self-alignment $R, S$ (p. 2).

For any word $\alpha$ we denote by $T_\alpha$ the composition of elements of self-combinations $R$ and $S$, resulting from replacing the letters $a$ with $R$ and the letters $b$ with $S$ in the words $\alpha$. For example, $T_{ba} = SR$, $T_{abaa} = RSR$.

Since in the composition of self-combinations the effective mapping $E$ also need not be written, we put $T_\Lambda = E$ by definition.

Each composition of self-combination elements can obviously be written in the form $T_\alpha$, where $\alpha$ is some word.

Thus, we have obtained some correspondence between the set of all words in the alphabet $\{a, b\}$ and the set of self-combinations. This correspondence is not inverse: different words can correspond to the same self-combination. For example, $T_{ba} = SR = RRS = T_{aab}$ (cf. figure 5 and 8).

The method we want to propose for establishing the equivalence of arbitrary words is based on three “critiques”:

(A) The left and right sides of each of the calculus substitutions correspond to my own self-combination:

$$\begin{cases} T_{ba} = T_{aab}, \\ T_{aaa} = T_\Lambda, \\ T_{bb} = T_\Lambda. \end{cases}$$

Fig. 8.

⟦folio 6⟧

(B) Any word is equivalent in our calculus to one of the following words: Λ, a, b, aa, ab, aab.
(B) Any two of the words Λ, a, b, aa, ab, aab correspond to different self-alignments.
First of all, let us establish the truth of statements (A) - (B).
Statement (A) follows from equalities (4). Statement (B) is verified geometrically: let us act on the original triangle with self-alignments $T_\Lambda, T_a, T_b, T_{aa}, T_{ab}, T_{aab}$ and see that different results are obtained (see figure 1-3, 9, 4 and 8).
(B) proves the latter. Let $\alpha$ be an arbitrary word. Having applied the first of substitutions (9) to it the required number of times, we will “drive” all $a$ to the beginning. Thus, the word $\alpha$ is equivalent to a word of the form
$$\beta = \underbrace{aa \dots abb \dots b}_{k}$$
$(k \geqslant 0, l \geqslant 0)$. If $l$ is even, then by applying the third of substitutions (9) to $\beta$ the required number of times, we can “remove” all $b$ from $\beta$. In this case, $\beta$, and therefore $\alpha$, is equivalent to a word of the form
$$\gamma' = \underbrace{aa \dots a}_{k}$$
Depending on the remainder when dividing the number $k$ by 3 (it equals 0, 1 or 2)

the word $\gamma'$ using the second of substitutions (9) is transformed into one of the words $\Lambda, a, aa$. If $l$ is odd, then $\beta$ and $\alpha$ are equivalent to a word of the form
$$\gamma'' = \underbrace{aa \dots ab}_{k}.$$
Depending on the same remainder of the word $\gamma''$ is translated into one of the words $b, ab, aab$.
From (A), it obviously follows that adjacent words correspond to the same self-combination. This means that this is also true for equivalent words:
$$\alpha \sim \beta \Rightarrow T_\alpha = T_\beta.$$ (10)
From (B), (B) and (10) we get the converse:
$$T_\alpha = T_\beta \Rightarrow \alpha \sim \beta.$$ (11)
Let $T_\alpha = T_\beta$. By (B), each of the words $\alpha, \beta$ is equivalent to one of the words $\Lambda, a, b, aa, ab, aab$. Let's put $\alpha \sim \alpha', \beta \sim \beta'$, where $\alpha', \beta' \in \{\Lambda, a, b, aa, ab, aab\}$. From (10) $T_\alpha' = T_\alpha$ and $T_\beta' = T_\beta$. Taking into account $T_\alpha = T_\beta$ we get $T_\alpha' = T_\beta'$. Then from (B) $\alpha' = \beta'$. Therefore, $\alpha \sim \beta$.
From (10) and (11) it follows
$$\alpha \sim \beta \Leftrightarrow T_\alpha = T_\beta.$$ (12)
Look again at the proof of statement (12) and you will see that this proof rests only on (A) - (B). Once (A) - (B) have been established, no further reference to calculus substitutions is necessary.

⟦folio 7⟧

Now, after establishing (12), we can finally offer the promised method: the path must be tested for the equivalence of the words $\alpha$ and $\beta$; act on triangle $ABC$ with self-alignments $T_{\alpha}$ and $T_{\beta}$; if you get the same result, then $T_{\alpha} = T_{\beta}$ and, therefore, by (12) $\alpha$ and $\beta$ are equivalent; otherwise, again due to (12), they are not equivalent.

Example 2

Let us now consider associative calculus with substitutions in the same alphabet $\{a, b\}$:

$$\begin{cases} ab \leftrightarrow ba, \\ aa \leftrightarrow \Lambda, \\ bb \leftrightarrow \Lambda. \end{cases}$$

For this calculus it is easy to indicate two ways of declaring equivalence.

First way

This method is similar to the method from Example 1. We fix some rectangle $ABCD$ (Fig. 10) on the plane. Let us denote by $S_1$ the axial symmetry of the plane with the axis $OM$ passing through the center of symmetry of the rectangle $O$ parallel to the side $AB$ (Fig. 11); by $S_2$ we denote axial symmetry with the axis $ON$ (Fig. 12). Both of these symmetries are self-alignments of the original rectangle. We will call the self-combinations $S_1$ and $S_2$ elementary.

As in Example 1, we will consider all possible compositions of elementary self-combinations.

This time we will obtain the self-alignment $T_{\alpha}$ from the word $\alpha$ by replacing the letter $a$ with $S_1$, the letter $b$ with $S_2$.

Again, three “pillars” are fulfilled:

(A) The left and right sides of each of the calculus substitutions correspond to the application of (13) substitution (13), find eton words equivalent to the words $\alpha$ and $\beta$ (how this is done is described in proof (B) from Example 1); if $\alpha$ and $\beta$ turn out to be equivalent to the same eton word, then $\alpha \sim \beta$; otherwise $\alpha$ and $\beta$ are not equivalent.

In the language of A. Tolygo’s article “Invariants” («Kvant», 1976, No. 12), the second method can be stated as follows: for any word

$$\begin{cases} T_{ab} = T_{ba}, \\ T_{aa} = T_{\Lambda}, \\ T_{bb} = T_{\Lambda}. \end{cases}$$

(B) Any word is equivalent in our calculus to one of four words: $\Lambda$, $a$, $b$, $ab$.

(B) We love two of the words $\Lambda$, $a$, $b$, $ab$ corresponding to different self-alignments.

From (A) - (B), as above, we deduce

$$\alpha \sim \beta \iff T_{\alpha} = T_{\beta}.$$

This means that the equivalence of arbitrary words $\alpha$, $\beta$ is established as in Example 1: act on the rectangle $ABCD$ by transformations $T_{\alpha}$ and $T_{\beta}$; if we get the same result, then $\alpha \sim \beta$; otherwise $\alpha$ and $\beta$ are not equivalent.

Second way

Taking a closer look at substitutions (13), you can notice that they save one of the enamel words $\Lambda$, $a$, $b$, $ab$.

Since for any two enamel words either the parity of the number letter $a$ or the parity of the number letter $b$ are different (see Fig. 13), enamel words are not pairwise equivalent.

Therefore, the equivalence of arbitrary words $\alpha$, $\beta$ is simple: applying substitution (13), find eton words equivalent to the words $\alpha$ and $\beta$ (how this is done is described in proof (B) from Example 1); if $\alpha$ and $\beta$ turn out to be equivalent to the same eton word, then $\alpha \sim \beta$; otherwise $\alpha$ and $\beta$ are not equivalent.

In the language of A. Tolygo’s article “Invariants” («Kvant», 1976, No. 12), the second method can be stated as follows: for any word

⟦folio 8⟧

α let us set

$$f_1(\alpha) = \begin{cases}
0, если число букв a в слова α четно,
1 в противном случае;
\end{cases}$$

$$f_2(\alpha) = \begin{cases}
0, если число букв b в слова α четно,
1 в противном случае.
\end{cases}$$

The functions $f_1, f_2$ form a complete system of invariants. Therefore, the equivalence of arbitrary words α, β is recognized as follows: count the values ​​of the functions $f_1$ and $f_2$ on α and β; if equal

$$\begin{cases}
f_1(\alpha) = f_1(\beta),
f_2(\alpha) = f_2(\beta)
\end{cases}$$

will be fulfilled, α~β; otherwise α and β are not equivalent.

Try solving the problem from example 1 in the second way, i.e. using invariants. This is much more difficult than example 2.

The algorithm does not always exist

The problem of finding ways to establish the equivalence of words in associative calculi was posed in 1914 by the Norwegian mathematician Thue. Thue himself also indicated methods for associative calculi of a certain special type.

In 1946 and 1947, the Soviet mathematician Andrei Andreevich Markov and the American mathematician Emil Post independently constructed associative calculi, for which there is also no method.

Until now, in our country we have avoided the word “algorithm”. In mathematics, an algorithm is an exact representation for solving a certain class of problems. This phrase in no case can be considered as a specific concept of an algorithm - after all, the words “exact representation” are not some kind of mathematical term and do not have an unambiguous meaning.

Until mathematicians were engaged in constructing specific algorithms, they made do with the loose description of this concept given above. But in the first decades of the 20th century, many classes of problems accumulated for which no algorithm could be found. Mathematicians began to suspect that it was not a lack of ingenuity. The thought occurred to them: what if for this or that class of problems the algorithm simply doesn’t work? What if it simply doesn't exist?

In order to prove that an algorithm does not exist, a vague concept is no longer enough; this concept must be clarified. This clarification was made in the mid-thirties of our century *).

Only after this clarification did it become possible in principle to prove the non-existence of the algorithm. The first proof of this kind was given by the American logician Alonzo Church.

The calculus constructed by A. A. Markov and E. Post was cumbersome: they contained hundreds of substitutions. Mathematicians began to look for simpler examples of associative calculi with an unsolvable equivalence problem. Grigory Samuilovich Tseytin put rekord in this direction: he constructed such a calculus with only 7 substitutions **).

Tseitin proved that for calculus in the alphabet {a, b, c, d, e} with substitutions

$$\begin{cases}
ac \leftrightarrow ca,
ad \leftrightarrow da,
bc \leftrightarrow cb,
bd \leftrightarrow db,
eca \leftrightarrow ae,
edb \leftrightarrow be,
abac \leftrightarrow abace
\end{cases}$$

There is no algorithm for recognizing word equivalence.

It is interesting that calculi with a decidable and calculus with an undecidable equivalence problem “lie side by side.” In the brochure of B. A. Trakhtenbrot “Algorithms and machine problem solving” (Moscow, Fizmatgiz, 1960) Tseytin’s calculus was also given *)

*) You can read about this in §§ 7, 13 of B. A. Trakhtenbrot’s brochure “Algorithms and Computing Automata” (Moscow, “Soviet Radio”, 1974) and on p. 9-13 of the book “Tybioring machines and recursive functions” (Moscow, “Mir”, 1972).

**) His rekord was used and covered by Yuri Vladimirovich Matiyasevich, who constructed such a calculus using three substitutions. Unfortunately, they are too long to include here.
