---
id: 1975-10-stepin-tagi-zade-slova-s-ogranicheniyami-6f547c8b
issue: kvant_1975_10
year: 1975
number: "10"
title: Restricted words
authors:
  - Стёпин А. М.
  - Таги-Заде А. Т.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 34
page_last: 39
page_labels: 32-37
tag: 6MKT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0d77d85ae846b5f6298cc965cb9d35df77ed8b21e8cab5ec6784402e3bcf8c26
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/16_stepin-tagi-zade-slova-s-ogranicheniyami-6f547c8b.md
source_content_sha256: b92b786323ab41e96fca2903003541f6e932cd5ca018d8ac1b4c21482922df72
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Restricted words

A. M. Stepin,
A. T. Tatsi-Zade

This article on the topic is very close to the article by G. A. Gurevich “Repetitionless Sequences,” which was published in «Kvant» No. 9 for this year. The article is devoted to the calculated number (and proof of the existence) of words of any length (including infinite), in a given alphabet with restrictions - along the way, it solves problem M300 from “Zadanika «Kvant», No. 12, 1974. Gurevich calculated the number (and proved the existence) of sequences of any length (and infinite), for which no group of digits occurs twice in a row, and problem M310 was solved.

The combinatorial technique with which problems M300 and M310 (and their generalizations) were solved is widely used in server mathematical science: group theory, algebra theory, algebraic number theory.

We will teach our acquaintance with words and alphabets by analyzing problem M300, proposed in “Task «Kvant», see «Kvant» No. 12 for 1974.

Mission M300

The alphabet consists of three letters a, b, c. Let us call a sequence of any length consisting of these letters a word. When processing words, some letter combinations (two or more in length) are considered prohibited. It is known that in the list of prohibited letter combinations all words have different lengths.

Let us prove that there are words of any length that do not contain forbidden letter combinations.

Task M300 can be given a different – ​​“entertaining” – form:

A certain automatic driver drives around the city with a rectangular layout. Once at the intersection, he either continues to drive straight, or turns left or right (you can’t turn backwards!) - taking into account the fact that traffic rules prohibit some combinations of these stops (left and right) and straight passage.

It is known that all prohibited combinations have a length of at least two (for example, the length of a left-right combination is two) and that there are no different combinations of the same length. It turns out that if the city is large enough and the driver starts in the center, then, despite all the prohibitions, he can drive through any given number of intersections in this city.

It is still convenient to solve the M300 problem in the terminology of “letters” and “words”.

We will call forbidden letter combinations edified words and consider a word good if it does not contain a single edified word within itself. We will sometimes call a set of well-known words a list of prohibitions or restrictions. We call a word that contains at least one paternal word “bad.”

Let us denote the number of good words of length l by $G_l$. To prove the existence of good words of any length, it is enough to show that for any natural l the number $G_l$ is greater than zero. We will now show that for any l there are quite a lot of good words of length l: $G_l \geq 2^l$.

⟦folio 33⟧

We order the offset words by length and denote by $l_i$ the length of the $i$th offset word ($l_i \geq i$).

Lemma 1. For numbers $G_l$ the following inequality holds:

$$G_l \geq 3 \cdot G_{l-1} - \sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i} \cdot i$$

($G_1$, estimated, equal to that; let’s set $G_0$ equal to one).

Proof. Note that all good words of length $l$ are contained among the words obtained by assigning to the right one of the letters $a, b, c$ to good words of length $l-1$. With this attribution, we get $3 \cdot G_{l-1}$ words, among which, in addition to good words, there may also be some flat words of length $l$. Let's estimate their number. Obviously, in the resulting flat word, the offset word can only be at its end, that is, it is structured like this: the last $l_i$ letters form an offset word, and the first $l-l_i$ letters form a good word ($2 \leqslant l_i \leqslant l$). The number of flat words (length $l$) of the described type ending with an offset word of length $l_i$ is not greater than the number of good words of length $l-l_i$, that is, the number $G_{l-l_i}$ (by convention we have only one offset word of length $l_i$). Still, as a result of assigning one of the letters $a, b, c$ to the right to good words of length $l-1$, the result will be no more than $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ flat words. This means that among the received $3 \cdot G_{l-1}$ words of length $l$ there are at least $3 \cdot G_{l-1} - \sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ good words.

*) The sum $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ is, generally speaking, not the same as $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-i}$: in the first sum, the arbitrary sum is summed only over such values $l_i$, $2 \leqslant l_i \leqslant l$, for which in the list of prohibitions there is a suppressed word of the corresponding length $l_i$ (that is, $l_i$ takes, perhaps, not all of the values 2, 3, ..., $l$): So, if there is no eliminated word of length 3 in the list of prohibitions, then in the sum $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ the member $G_{l-3}$ is missing.

Inequality (1) plays a major role in estimating the number $G_l$.

Lemma 2. For any natural number $l'$

$$G_l \geq 2 G_{l-1}.$$

(2)

We will prove Lemma 2 using the method of mathematical induction.

Base of induction: $l = 1$; obviously $G_1 \geq 2 \cdot G_0$.

Induction step: Suppose that inequality (2) holds for all natural $l \leqslant L$, that is

$$\begin{cases} G_L \geq 2 \cdot G_{L-1}, \\ G_{L-1} \geq 2 \cdot G_{L-2}, \\ \dots \\ G_2 \geq 2 \cdot G_1. \end{cases}$$

(2')

Let us prove that $G_{L+1} \geq 2 \cdot G_L$.

From inequalities (2') we have:

$$G_L \geq 2 \cdot G_{L-1} \geq 2^2 \cdot G_{L-2} \geq \dots \geq 2^k \cdot G_{L-k},$$

that is

$$G_{L-k} \leq G_L/2^k,$$

(2'')

where $k = 1, 2, \dots, L$.

Taking into account estimates (2''), inequality (1) and a method for it, we obtain that

$$G_{L+1} \geq 3 \cdot G_L - \sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{L+1-l_i} \geq$$

$$\geq 3 \cdot G_L - \sum_{k=1}^{l} G_{L-k} \geq *$$

$$\geq 3 \cdot G_L - G_L \cdot \sum_{k=1}^{l} \frac{1}{2^k} \geq$$

$$\geq G_L \cdot (3-1) = 2 \cdot G_L,$$

and this was what needed to be proven.

Since $G_{l-1} \geq 2 \cdot G_{l-2}, G_{l-2} \geq 2 G_{l-3}, \dots, G_1 \geq 2 \cdot G_0 = 2$, then $G_l \geq 2^l$, and we get Theorem 1:

For any natural number $l$ in number problem M300 the number of good words of length $l$ is no less than $2^l$:

$$G_l \geq 2^l,$$

(3)

which ends the solution to our problem.

*) Here is the announced amount:

$$\sum_{k=1}^{l} G_{L-k} = G_{L-1} + G_{L-2} + \dots + G_{L-l}.$$

⟦folio 34⟧

Endless words

Now we know that the “dictionary” problem M300 contains good words of any length. Does it have endless long good words?

Now we will prove that if the list of marked words is finite (there are only a finite number of forbidden letter combinations), then there is an infinitely long good word. However, we note right away that in fact the requirement for a finite list of distinct words does not exist: the statement about the existence of an infinitely long good word remains true in the case of an infinite number of prohibitions *).

Let's take the longest parenthetical word (since, by assumption, the number of parenthetical words is finite, this can be done); let its value be equal to $n$. Let us choose the natural $N$ so that $N$ is greater than $n$. Since we have good words of any length, let's take good words of length

*) You can find the proof of this fact in G. A. Gurevich’s article “Repetitionless Sequences” (see «Kvant» No. 9). Gurevich’s article actually proves that from the property “there is an arbitrarily long good word” the property “there is an infinitely long good word” follows, that is, that in fact, the existence of good words of any length is equivalent to the existence of an infinitely long good word. We will prove that in our sentences there is a periodic, non-finite word, and we will indicate a way to construct such a word (we will give, as they say, a construction proof).

$N \cdot (3^N + 1)$, let’s denote it by $A$. Let us divide the words $A$ into $(3^N + 1)$ equal in length parts $B_k$ of length $N$: if

$$A = x_1, x_2, \dots, x_N \cdot (3^N + 1).$$

where $x_i$ is $a$, or $b$, or $c$, then $B_k = x_N \cdot (k - 1) + 1, x_N \cdot (k - 1) + 2, \dots, x_N \cdot k.$

Since $A$ is a good word, every $B_k$ is also a good word of length $N$. But in our alphabet there are only three letters $(a, b, c)$, so there will be no more different good words of length $N$ than $3^N$. We got $(3^N + 1)$ good words $B_k$; This means that among them there are identical ones. Let, for example, $B_{n_1} = B_{n_2}$ and $n_1 < n_2$. Let's take a piece of the word $A$, consisting of parts $B_k$ with numbers $k$ from $n_1$ to $n_2 - 1$ inclusive. This will be a good word $C$ of length $m \geq N$:

$$C = x_N \cdot (n_1 - 1) + 1, \dots, x_N \cdot (n_2 - 1).$$

Let us add the same word $C$ to the word $C$ on the right. We get words $D$ of length $2m$:

$$D = x_N \cdot (n_1 - 1) + 1, \dots, x_N \cdot (n_2 - 1),$$

$$x_N \cdot (n_1 - 1) + 1, \dots, x_N \cdot (n_2 - 1).$$

Let's prove that $D$ is a good word.

Let us assume the opposite: $D = CC$ is a flat word; then it contains some kind of parenthetical word. Obviously this is a catchphrase

⟦folio 35⟧

can only be found in the region of “gluing” of two good words $C$, so that its intersection with the “right” and “left” words $C$ is not empty. But $B_{n_1} = B_{n_2}$ or on any marked word is replaced by $N$; This means that this marked word must lie in the region of “gluing together” parts $B_{n_2}-1$ and $B_{n_1}$ of the good word $A$, but this cannot happen, and, therefore, the word $D$ is good.

It is clear that an infinite periodic word $CC \dots C$ with period $C$ will also be good, and this, in fact, gives everything that is needed.

So, our automatic can drive around the city for an infinitely long time without violating traffic rules!

Interesting example

Let us return to inequality (1), with the proof of which we began the solution problem M300; let's rewrite it like this:

$$G_l - 3 \cdot G_{l-1} + \sum_{l_i, 2 \leqslant l_i \leqslant l} G_{l-l_i} \geqslant 0.$$ (4)

How accurate is this inequality? Is it possible to replace the “≥” sign in it with the “=” sign? Generally speaking, it’s impossible, and here’s why.

Number $3 \cdot G_{l-1}$ is the number of words obtained by adding length to the right to good words $l-1$ one of the letters $a, b, c$; among such words there are all good words of length $l$. Subtracting from the number $3 \cdot G_{l-1}$ numbers $G_{l-l_i}$, Where $l_i$ - some of the values ​​2, 3, ..., $l$ (possibly all meanings), we thereby, as it were, cross out the lengths from the constructed words $l$ all those flat words that are obtained if a good word of length $l-l_i$ add marked word length $l_i$. But it may turn out that some flat word of length $l$ appears to be crossed out several times from the list $3 \cdot G_{l-1}$ the resulting words. If among our $3 \cdot G_{l-1}$ words length $l$ there are no words resulting from good words of length $l-l_i$ by adding a marking word of length to the right $l_i$, then accordingly the number $G_{l-l_i}$ There is no need to subtract at all.

However, under some additional conditions on the list of prohibitions together with recurrent inequalities (4) for the numbers $G_l$ ($l$ - any) similar recurrence equalities will be fulfilled:

$$G_l - 3 \cdot G_{l-1} + \sum_{l_i, 2 \leqslant l_i \leqslant l} G_{l-l_i} = 0.$$ (4')

In such cases, $G_l$ is written explicitly as a function of $l$, and for each specific value $l$ the number $G_l$ can be calculated.

In particular, from the above it follows that for the validity of recurrent equalities (4'), the following two conditions are sufficient:

1. Among words of length $l$, obtained by assigning on the right one of the letters $a, b, c$ to good words of length $l-1$, finding all words obtained from good words of length $l-l_i$ by assigning on the right a marked word of length $l_i$ (it is supposed to be in the list of prohibitions).

2. Each positive word of length $l$ obtained by a maximum of attribution (of one letter) is represented in the form of some good word (smaller length) and a marked word in a unique way.

Condition 2° is satisfied if no marked word in the list of prohibitions is the end of any other marked word.

Exercise 1. Check that for the alphabet of three letters and the list of marked words $ab, acb, accb, \dots, ac\dots cb$ the conditions 1° and 2° are satisfied, and that for the numbers $G_l$ the recurrence relations are also valid:

$$G_l - 3 \cdot G_{l-1} + G_{l-2} + \dots + G_{l-s} = 0.$$ (5)

(s is the length of the longest marked word).

If the list of prohibitions in exercise 1 is limited to two marked words $ab$

*) Equations of the form $G_l + b_1 G_{l-1} + b_2 G_{l-2} + \dots + b_s G_{l-s} = 0$ ($b_1, \dots, b_s$ are some constants) are called finite-difference equations; You can read about methods for solving them in A. O. Gelfon’s book “Calculus of Finite Differences.” M., “Science”, Chapter V, § 4, paragraph 2.

⟦folio 36⟧

and acb, then we get the equation
$$G_l - 3 \cdot G_{l-1} + G_{l-2} + G_{l-3} = 0. \quad (5')$$
We will look for a solution to equation (5') in the form
$$G_l = \lambda^l. \quad (5'')$$
Substituting (5'') into (5'), we obtain the equation
$$\lambda^3 - 3\lambda^2 + \lambda + 1 = 0,$$
having three different roots:
$$\lambda_1 = 1, \quad \lambda_2 = 1 + \sqrt{2}, \quad \lambda_3 = 1 - \sqrt{2}.$$
The general solution to equation (5') is written as follows:
$$G_l = C_1 + C_2 (1 + \sqrt{2})^l + C_3 (1 - \sqrt{2})^l,$$
where $C_1, C_2$ and $C_3$ are constants determined from the initial conditions:
$$G_0 = 1, \quad G_1 = 3, \quad G_2 = 8.$$
This results in a system for determining $C_1, C_2, C_3$:
$$\begin{cases}
C_1 + C_2 + C_3 = 1, \\
C_1 + C_2 (1 + \sqrt{2}) + C_3 (1 - \sqrt{2}) = 3, \\
C_1 + C_2 (3 + 2\sqrt{2}) + C_3 (3 - 2\sqrt{2}) = 8,
\end{cases}
$$from which it is located
$$C_1 = -\frac{1}{2}, \quad C_2 = \frac{3}{4} + \frac{\sqrt{2}}{2}, \\
C_3 = \frac{3}{4} - \frac{\sqrt{2}}{2},$$
Means,
$$G_l = -\frac{1}{2} + \left(\frac{3}{4} + \frac{\sqrt{2}}{2}\right) \cdot (1 + \sqrt{2})^l + \left(\frac{3}{4} - \frac{\sqrt{2}}{2}\right) \cdot (1 - \sqrt{2})^l$$
(in part, $G_3 = 20$).

Generalization problem M300

Let the alphabet consist of $n$ letter $a_1, a_2, \dots, a_n$, and in the list of eliminated words (at least two in length) there are more than $m$ different words of the same length.

Now we will prove that, under certain restrictions on the primes $n$ and $m$, such a “word” will contain arbitrarily long good words, and for each natural $l$ ($l$ is the length of the word) - again, quite a lot.

As with the solution problem M300 (for M300 we have: $n=3, m=1$) we first need to prove it.

Lemma 3. If the conditions of the “generalized problem M300” are satisfied for the numbers $G_l$ and the length $l$ is also true:
$$G_l \geq n \cdot G_{l-1} - \sum_{i=1}^{n-1} m_i \cdot G_{l-i}, \quad (6)$$
In other words, $m_i$ denotes the number of removed words of length $l_i$ ($G_1$, very indo, is equal to $n$, and $G_0$ is again set to 1).

Lemma 3 is proved by exactly the same reasoning as Lemma 1 (see p. 33); We won’t prove it.

Since, by the condition of each, $m_i$ is not greater than $m$ (in what follows we will consider $m = \max\{m_i\}$ and call $m$ the multiplicity of the system of constraints), then
$$G_l \geq n \cdot G_{l-1} - m \cdot \sum_{i=1}^{n-1} G_{l-i}. \quad (7)$$
The next step after Lemma 3 is the proof of the important Lemma 4:
$$m \leq \left(\frac{n-1}{2}\right)^2, \quad (8)$$
mo. there is some $\lambda > 1$ such that for any natural $l$
$$G_{l+1} \geq \lambda \cdot G_l. \quad (9)$$
Lemma 4, like Lemma 2 of the first paragraph, is proved by the method of mathematical induction using inequality (7) and correspondences (2') and (2''), in which the number “2” is replaced by the letter “λ” (see p. 33). The indicative transition from $L$ to $L+1$ is possible because the square relative $\lambda$ inequality
$$n - \frac{m}{\lambda - 1} \geq \lambda$$ with a non-negative (due to (8)) discriminant
$$\left[ \left(\frac{n-1}{2}\right)^2 - m \right]$$ has a solution
$$\lambda_1, 2 = \frac{n+1}{2} \pm \sqrt{\left(\frac{n-1}{2}\right)^2 - m}.$$
Since $G_1 = n \cdot G_0$ (recall that $G_0 = 1$) and
$$n \geq \frac{n+1}{2} + \sqrt{\left(\frac{n-1}{2}\right)^2 - m},$$
That
$$G_1 \geq \left(\frac{n+1}{2} + \sqrt{\left(\frac{n-1}{2}\right)^2 - m}\right) \cdot G_0,$$
and the number $\lambda > 1$ exists is proven.
Finally, similar to Theorem 1, we will obtain Theorem 2:
If in the conditions of “generalized problem M300” $m \leq \left(\frac{n-1}{2}\right)^2$, then

### Blocking restrictions

Is restriction (8) on the multiplicity of the prohibition system necessary at all?

We have already seen that the condition $m \leqslant \left(\frac{n-1}{2}\right)^2$ is sufficient for the existence of an arbitrarily long good word. This condition cannot, generally speaking, be weakened. In fact, for $n = 2$ for an alphabet of two letters $a$ and $b$ we obtain the multiplicity condition $m \leqslant \frac{1}{4}$. Let's put $m = 1$ and take the following three words as marked:

$$ab,\ aaa,\ bbbb.$$

Let us prove that then there are no good words longer than five. A system of prohibitions for which there are no good words of any length will be called *blocking*.

Proof (by contradiction).

Suppose there is a good word of length 6. It ends with the letter $a$, or the letter $b$.

If this word ends with the letter $b$, then since the combination $ab$ is prohibited, then our “good” word consists only of the letters $b$, which cannot be the case, since the combination $bbbb$ is prohibited.

Let this good word (length 6) end with a beech $a$; Let's consider its penultimate letter: - if it is $b$, then all the other letters (5 pieces) should be $b$ - but this should not be. This means our word ends in $aa$. Let us now take the third letter from the end of our word: if it is again $a$, then the prohibition $aaa$ affects, but if it is $b$, then the remaining letters (4 pieces) are also $b$, and the prohibition $bbbb$ affects.

Let us give another example of a blocking system of prohibitions - for an alphabet of three letters $a$, $b$, $c$. For such an alphabet, condition (8) gives us that $m$ should be no more than 1. Putting $m = 2$, i.e., assuming that we can mark two words of the same length, we take the following words as marked:

$$ab,\ ac;\ bcb,\ bcc;\ aaaa,\ bbbb;\ ccccc.$$

Exercise 2. Prove that these marked words form a blocking constraint on good words.

What is the maximum length of a good word in this case?

From the examples considered for $n = 2$ and 3 it follows that there is a blocking system of prohibitions with multiplicity $m$ such that

$$\left(\frac{n-1}{2}\right)^2 < m \leqslant \left(\frac{n-1}{2}\right)^2 + 1.$$

⟦column⟧

But for an arbitrary natural number $n$ and an integer $m$, where

$$\left(\frac{n-1}{2}\right)^2 < m \leqslant \left(\frac{n-1}{2}\right)^2 + 1,$$

the existence of a boxing system of prohibitions for an alphabet of $n$ letters with multiplicity $m$ has not been proven. Let us prove that for an alphabet of $n$ letters $a_1,\ \ldots,\ a_n$ a blocking system of prohibitions with multiplicity $m = \frac{n\,(n-1)}{2}$ exists. Indeed, let us take such a system of prohibitions

(1) $a_1a_2$, (2) $a_1a_3$, . . . , $(n-1)\ a_1a_n$,

$(n)\ a_2a_3$, . . . , $\left(\frac{n\,(n-1)}{2}\right) a_{n-1}a_n$.

Then there will be no good words of length greater than $2n$, and the only good word of length $2n$ will be the word

$$a_na_na_{n-1}a_{n-1}\ldots a_1a_1.$$

But, of course, in each specific case it all depends on how the system of prohibitions is structured. It is sufficient, for example, for an alphabet of two letters $a$, $b$ $(n = 2)$ and $m = 1$ to take the marked words

$$aa,\ aba,\ abaa,\ abaab,\ \ldots,$$

how do we get that there is even an infinitely long, periodic word $bb\ldots b\ldots$. Moreover, you can take $m$ equal to even four (and certainly two and three), and as marked words, for example:

$$aa,\ ab,\ ba,\ aab,\ aba,\ baa,\ aaa,$$

and we will again get an infinite good word $bb\ldots b\ldots$.

In conclusion, we invite readers who are interested in the “problem of good words” to solve the problems.

1. Prove that for the alphabet $a$, $b$ there is no system of blocking constraints consisting of less than three words.

2. Prove that in the case of $n = 3$ and $m = 2$ there is no boxing system of fewer than six marked words.

3. Prove that if for the alphabet $a$, $b$, $c$ the words $ca$, $cb$, $ba$ are marked, then $G_l$ grows like $l^2$.

4. Prove that $G_{l_1+l_2} \leqslant G_{l_1} \cdot G_{l_2}$.

5. Prove that for an alphabet of $n$ letters there exists a blocking constraint system with multiplicity $m$ such that

$$\frac{n\,(n-2)}{2} + 2 \leqslant m < \frac{n\,(n-2)}{2} + 3.$$

⟦folio 37⟧
