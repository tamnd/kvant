---
id: 1990-9-barg-litsyin-chto-est-fortuna-ili-kak-ne-proigrat-v-sportprognoz-d9193dcd
issue: kvant_1990_9
year: 1990
number: "9"
title: What is Fortune, or How not to lose at Sportprognoz
authors:
  - Барг А.
  - Лицын С.
rubric: osnovnye-stati
page_first: 10
page_last: 17
page_labels: 8, 9, 12, 13, 14, 15
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6d5585d4189486ec6d8f51b030caf57ceb3c0c028e020b0dbece14fbee5aa5e2
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/04_barg-litsyin-chto-est-fortuna-ili-kak-ne-proigrat-v-sportprognoz-d9193dcd.md
source_content_sha256: fae5acd0058fe2231f8a564936db00526acfea9f607d24a3164168ba54ed830b
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 8⟧

---
running_head:
folio:
---

WHAT IS
FORTUNE,

or
How not to lose at
"Sportproznoz"

Candidate of Technical Sciences
A. BARG,
Candidate of Technical Sciences
S. LITSYN

⟦folio 9⟧

---
running_head:
folio:
---

School folklore contains a story about a man who, using a computer, developed a system for the game “Sportloto” and won a fortune. The man has not seen this, and it is unlikely that it exists, since there is no known winning strategy for this game. In other words, it is impossible to specify a way of playing in which the amount won will always be greater than the money spent on buying cards. The strategies we offer are no exception. However, there are many interesting mathematical problems associated with “Sportloto” and other word games. We will tell you about some of them.

As a rule, “Sportloto” and “Sportprognoz” are associated with the task of calculating the probability of guessing a certain number of correct numbers (results). We will not return to these well-known questions, but will only say that the probability of guessing six numbers out of forty-nine *) $p(49,6) \approx 7 \cdot 10^{-8}$; in the same notation $p(49,5) \approx 2 \cdot 10^{-5}$, $p(49,4) \approx 10^{-3}$, $p(36,5) \approx 3 \cdot 10^{-6}$ (you can prove this yourself).

Rules of the game

“Sportprognoz” is played as follows. 13 matches are selected from the calendar of sports accomplishments, the outcome of which, according to the lottery organizers, is difficult to predict. The player must make a forecast of the results of these matches, putting a “1” in each of the 13 cells of the table if he believes that the home team will win, “2” - the visiting team and “0” in case of a draw. After the results of the matches become known, the winnings are determined

*) Currently there are 45 numbers in the Sportloto card. When the authors were younger and addicted to Sportsloto, the card contained 49 numbers.

Prizes are divided among those who guess at least 11 results and increase with the number of correct predictions on the card. Each forecast will be represented by a 13-dimensional vector (i.e., a string of 13 digits) with components 0, 1, and 2. For example, the vector $x=(1,1,0,2,2,1,2,0,0,0,1,1,2)$ will taste the away win in matches 4, 5, 7, and 13, the home win in matches 1, 2, 6, 11, and 12, and nothing in the remaining matches.

In the game "Sportloto" you need to guess 6 out of 49 or 5 out of 36 numbers. Cards that indicate at least 3 of the numbers drawn as a result of a random draw are considered winning. The forecast in this case can be described by a 49 (36) dimensional vector containing “0” in 43 (31) positions and “1” in the remaining 6 (5) positions. The numbers of single positions correspond to the predicted number.

In each draw, one player can offer several forecast options. Let us call a set of these options a $l$-system if, regardless of the outcome of the draw, there is at least one among them in which at least $l$ results are correctly guessed. For us, only $l$-systems with $11 \leq l \leq 13$ for “Sportprognoz” and with $3 \leq l \leq 6$ (5) for “Sportloto” are of interest. Obvious examples of $l$-systems with a maximum $l$ are obtained by filling in all possible forecast options. These systems are not very interesting, if only because the number of “Sportprognoz” cards filled out in this case is 1,594,323, i.e., you need to spend about half a million rubles and about two years of continuous (half a minute per card) work. For Sportloto the corresponding numbers are larger. Keep in mind that even after completing the filling, you cannot be sure that the amount of gain exceeds the costs incurred. For smaller $l$ we will also try to think of systems in which the total number of options could be smaller.

So, if you play according to the system, then at least one of your predictions

⟦folio none⟧

---
running_head:
folio:
---

Operations modulo 3 and l-systems
The 3-system constructed in the previous paragraph has a number of red properties (discovered in the 40s by the American scientist Richard Hamming), which require a slight digression to explain.
We are dealing with vectors whose components can take values ​​from the set $Z_3 = \{0,1,2\}$. Elements of $Z_3$ can be added and multiplied in such a way that the result will again be elements from the same set. To do this, it is enough to perform a general addition or multiplication, find the remainder of dividing the result by 3 (as they say, bring it modulo 3). For example, $5 \equiv 2(\text{mod } 3), -2 \equiv 1(\text{mod } 3)$.
Using these operations, we can define the addition of ternary vectors. We define the sum of the vectors $a$ and $b$ as the vector $c$, each coordinate of which is the sum modulo 3 of the corresponding coordinates of the vectors $a$ and $b$. For example, $(0,1,1,2) + (1,2,1,1) = (1,0,2,0)$. Let us define the product of a vector and a ternary number $v \in Z_3$ as a vector whose coordinates are obtained by multiplying the coordinates of the vector by $v$ modulo 3. For example, $2 \cdot (1,0,2,2) = (2,0,1,1)$. In mathematics, such collections of vectors with the operations of addition and multiplication by a number defined on them are called vector spaces.

Exercise 2. Check that the 3-system $C_0$ introduced in the previous paragraph has the following properties: for any vector $a \in C_0$ and constant $v \in Z_3$ the product $va$ also takes $C_0$; for any two vectors $a, b \in C_0$ their sum is also a vector from $C_0$. Such systems are called linear.

Operations modulo 3 allow us to give a brief description of the 3-system $C_0$. First, note that the first coordinates $(x_1, x_2)$ of vectors from $C_0$ can be any pair of ternary numbers. Let's call this pair the ternary number of the vector. The values ​​of the two remaining coordinates $x_3$ and $x_4$ can be calculated using the following rule (actions modulo 3):

$$x_3 = x_1 + x_2, \quad x_4 = x_1 + 2x_2$$

(1) (check!).

Exercise 3. Is it possible to choose other vector coordinates as a number? What kind will then be and has the right (1)?

4. Show that if an arbitrary (same) vector is added to all vectors of the $C_0$ system, then its properties as a $l$-system will not change.

5. Using the result of Exercise 4, show that in the system $C_0$ you can include any directional vector (the forecast that seems most plausible to you).

Let's assume that you filled out the cards in accordance with the $C_0$ system. The official newspaper publishes the results of the matches included in the circulation (vector $y$). How to quickly find the winning card (the fact that it exists follows from the properties of the system)? An obvious, but sometimes not the best way is to compare the results of the draw with all the completed cards and find the most excellent score.

To describe a faster method, rearranging equation (1) in equivalent form:

$$x_1 + x_2 + 2x_3 = 0, \quad x_1 + 2x_2 + 2x_4 = 0.$$

Our method will be based on the fact that the coordinates of each coordinate of the system $C_0$ satisfy equations (2). If $y$ satisfies (2), it belongs to the system $C_0$, and its corresponding card can be found by its ternary number. Otherwise, $y$ differs from some vector $c = (c_1, c_2, c_3, c_4) \in C_0$ in the same coordinate. Let its number be $j$. Let's find $S_1 = y_1 + y_2 + 2y_3$ and $S_2 = y_1 + 2y_2 + 2y_4$.

Exercise 6. Show that the winning card $c$ can be found as follows:

a) if $S_1 = 0$ and $S_2 \neq 0$, then $j = 4$; if $S_2 = 0$ and $S_1 \neq 0$, then $j = 3$ (in general cases $c_j = y_j + S_i$, where $i = 1$ or $2$ is the non-zero index $S_i$);

b) if $S_1 \neq 0$ and $S_2 \neq 0$, then for $S_1S_2 = 1$ $j = 1$, and $c_1 = y_1 + 2S_i$ (i - any). At $S_1S_2 = 2$ $j = 2$, and $c_2 = y_2 + 2S_1 = y_2 + S_2$.

Example Sentence 1. Use the previous equation to determine the nearest card if the match results are represented by the vector $y = (2,1,2,1)$. Then $S_1 = 1$, $S_2 = 0$. Turning to case a), we obtain $j = 3$, and $c_3 = y_3 +$

⟦folio 12⟧

---
running_head:
folio:
---

+ $S_1 = 0$. The vector $c = (2,1,0,1) \in C_0$ is found again, located at a distance of 1 from $y$.

For “Sportprognoz” for 4 matches, this method of determining the winning card looks (and is) extremely cumbersome, especially in comparison with a simple search of all nine cards of the system. Its advantages will be explained below.

Let us note one more application of the described system. Suppose that, when filling out the large “Sports Forecast” card, you believe that you know exactly the results of 9 out of 13 matches. You would like to know for sure that in predicting the outcome of the remaining four matches you will be wrong no more than once. Then you should fill in 9 cards with a fixed combination in the known 9 positions and all vectors of the 3-system $C_0$ in the remaining four positions.

Error Correcting Codes

One should not think that the $l$-systems are depicted and studied to obtain large winnings in the logger - mathematicians have more interesting things to do. It turns out that very similar constructions appear, for example, in the theory of message transfer. Let's imagine that a vector of $k$ letters needs to be transmitted over a communication line with interference, each letter of which can take one of $q$ meanings (for messages in Russian $q = 34$ are letters of the alphabet and the space between words). We assume that direct transmission is likely to distort at least one letter of the message, so we would like to have a way to correct errors after reception.

Let's proceed as follows. Let's add several letters to the transmitted vector, depending on the letters of the original message. Such a set of extended messages is called a code, and the number of letters in the extended message (vector code) is denoted by $n$ and called the length of the code. If, when transmitting a code vector in a communication channel, a distortion of $t$ letters occurs, then the pleasant vector is located at a Hamming distance $t$ from the transmitted vector. Based on the received vector, it is required to unambiguously reconstruct the transmitted vector. To do this, the code must satisfy certain properties.

Statement. Code $C$ corrects any $t$ or fewer errors if the sets of vectors from $E_q^n$ located at a distance $\leq t$ from the code vectors do not intersect pairwise.

⟦folio 13⟧

---
running_head:
folio:
---

7. Prove that each such set from the statement contains $V(n, t) = \sum_{i=0}^{l} C_n^i \times (q-1)^i$ vectors $(C_n^i - \text{биномальный коэффициент}, \frac{n!}{(n-i)!i!})$.

8 (Hamming limit). Prove that for any code
$$k \leqslant \log_4 [q^n / V(n, t)]$$
$[x] = \text{целая часть } x$.

(3) If the parameters of the code in (3) are equal, then the code is called perfect.

The mathematical theory of coding, which arose about forty years ago, is a developed and very deep science. At its origins stood Claude Chenon, the already mentioned Richard Hamming, Marcel Golay and other scientists. You can read more about error-correcting codes in the books by Arshinov M. N., Sadovsky L. E. “Codes and Mathematics” (M., “Nauka”, 1983, Library «Kvant», issue 30), Yaglom A. M., Yaglom I. M. “Probability and Information” (M., “Nauka”, 1973).

It is easy to see that perfect $l$-systems coincide with perfect codes. In particular, the 3-system for playing mini-Sportirognoz is a code with $q=3$, $k=2$ and $n=4$ that corrects one error. From the above it follows that this code is linear (in the sense of Exercise 2) and perfect and contains, as it should, $q^k=9$ vectors.

"Sportirognoz-13"
The 3-system proposed above for a trio of four matches can be generalized to the “real” case of 13 matches; this results in a 12-system $C_1$ consisting of $3^{10}=59049$ cards. We will assume that the vector $x \in E_3^{13}$ belongs to the system $C_1$ if its coordinates satisfy the following equation (again operations modulo 3):

$$x_{11} = x_3 + x_4 + x_5 + x_6 + x_7 + x_8 + x_9 + x_{10},$$

$$x_{12} = x_1 + x_2 + x_5 + x_6 + x_7 + 2x_8 + 2x_9 + 2x_{10},$$

$$x_{13} = x_1 + 2x_2 + x_3 + 2x_4 + x_6 + 2x_7 + x_9 + 2x_{10}.$$

As above, we will call the vector number the set of its first nine coordinates.

Exercise 9. Let the number of the vector $x = (x_1, \dots, x_{10}) \in C_1$ be equal to $(x_1, \dots, x_{10}) = (0,1,1,1,2,0,2,1,2,1)$. Find $x$.

Statement. The constructed 12-system is linear and perfect.

Indeed, let the vectors $x$ and $y$ satisfy (4), then both $x+y$ and $2x$ satisfy this system of equations. It is somewhat more difficult to prove that the distance between any two vectors of the system $C_1$ is at least three. Distance 2 vectors $x$, $y \in C_1$. If their numbers match, then $x=y$. If the numbers differ in three or more positions, then everything is proven. Let the numbers differ in one position, say $i$th. Then we replace that any $x_i$ ($1 \leqslant i \leqslant 10$) appears with non-zero coefficients in the correct parts of at least two equations of system (4), i.e., at least of the last three coordinates of the vectors $x$ and $y$ will be different. If the numbers of the vectors $x$ and $y$ differ in two positions, say, $i$th and $j$th, then for the proof it is enough to show that they differ in at least one more position. This may not be the case only in the case when the $i$th and $j$th variables enter the correct parts of all equations (4) with the same coefficients. The check shows that such variables do not exist. So, it has been proven that the distance between any vectors $x$, $y \in C_1$ is at least three. Then the set of vectors from $E_3^{13}$ located from $x$ and $y$ at a distance $\leqslant 1$ do not intersect. In accordance with exercises 7, each such set contains 27=3$^3$ vectors. The total number of vectors in the system is equal to the number of different numbers, i.e. $3^{10}$, and the total volume of the disjoint sets corresponding to them is equal to $3^{10} \cdot 3^3 = 3^{13}$, which coincides with the number of all possible cards. Q.E.D.

Exercise 10 (difficult). Quickly come up with a way to find the winning card for the $C_1$ system based on the triage result (compare with Exercise 6). This method allows you to find the winning card much faster than with a full search.

⟦folio 14⟧

---
running_head:
folio:
---

The constructed 12-system is a code with $q=3$, $n=13$, $k=10$, correcting one error. This code is a member of the family of perfect Hamming codes with $q=3$, $n=(3^m-1)/2$, $k=n-m$.

Nonlinear systems

Let's return for a moment to the $C_0$ system for a mini-“Sports forecast”. Let's write all two vectors into the rows of the table. By deleting any column from this table, we obtain a linear system of ninth vectors for Sportprognoz-3. It can be shown that this system is the best among linear ones, that is, it contains the smallest possible number of cards. It turns out that abandoning the linearity condition allows one to incriminate this system. The best nonlinear 2-system for 3 consists of only five vectors. Here it is:
$(0,0,0), (0,1,1), (1,0,1), (1,1,0), (2,2,2)$.

The table shows the records for constructing $l$-systems for $l=n-3$, $n-2$ and $n-1$ at $n \leqslant 13$. For the game “Sports Forecast” only the first two columns will appear, but a more general case is also of interest to mathematicians. Note that any published table is worthy of being published in reputable international mathematical journals. Of course, the systems from this table were built by their authors

Table

| $n$ | $l=n-1$ | $l=n-2$ | $l=n-3$ |
| :--- | :--- | :--- | :--- |
| 1 | 1* | 1* | 1* |
| 2 | 3* | 1* | 1* |
| 3 | 5* | 3* | 1* |
| 4 | 9* | 3* | 3* |
| 5 | 27 | 8 | 3* |
| 6 | 73 | 17 | 6* |
| 7 | 186 | 34 | 12 |
| 8 | 486 | 81 | 27 |
| 9 | 1458 | 219 | 54 |
| 10 | 3645 | 558 | 108 |
| 11 | 10935 | 729* | 243 |
| 12 | 29889 | 2187 | 729 |
| 13 | 59049* | 6561 | 1215 |

* - it is known that it is impossible to incriminate.

not by simple enumeration on a computer (by the way, how to do this? The answer in the general case is unknown), but by the use of general designs leading to a family of systems of various lengths. So if one of the readers is lucky enough to catch the table, the authors are ready to provide assistance in preparing the article. It is better to start the search with lengths $n \geqslant 6$, i.e. the increase at smaller lengths is small.

Wonderful 9-system for 11

When closely observing the table, a star, lonely twinkling in its middle, catches the eye. Here is the wonderful 9-system $C_2$ for 11. Its history and applications would be complex for a fascinating math novel. But first, a few words about heropin itself. This is a linear perfect system. It is not difficult to prove completely if you know that any two vectors of the system are at a distance of at least a heel. Then, as before, the set of ($x_7=3^6$) vectors from $E_3^{11}$ located at a distance $\leqslant 2$ from some point in the system do not intersect. Since each of these sets contains $243=3^5$ vectors, the total volume of these sets coincides with the total number of vectors in $E_3^{11}$.

Let us present equations connecting the ternary number ($x_1, x_2, \dots, x_6$) of any vector $x$ belonging to the system $C_2$ with the remaining fifth of its coordinates:

$$x_7=x_1+x_3+2x_4+2x_5+x_6,$$
$$x_8=x_1+x_2+x_4+2x_5+2x_6,$$
$$x_9=x_1+2x_2+x_3+x_5+2x_6,$$
$$x_{10}=x_1+2x_2+2x_3+x_4+x_6,$$
$$x_{11}=x_1+x_2+2x_3+2x_4+x_5.$$

This system is the same as a perfect code with parameters $q=3$, $n=11$, $k=6$, correcting two errors. It is called the Golay code in honor of the mathematician who discovered and published it in 1949. To specify the code using the system of equation (5), Golay had to use the theory of so-called quadratic residues. However, in the summer

⟦folio 15⟧

---
running_head:
folio:
---

In 1989, they found out that this code (how well the system for the game “Sportprognoz”) was opened and published in 1947 in the physical sports newspaper “Veikaya” *). The author of this discovery, Juhani Virtakallo, is not a mathematician and, deliberately, did not know that square subtractions must be used to construct the code. He wrote: “This system of 729 columns came to my mind during the days of small winnings at Sportprognoz.” Apparently, we are dealing with an example of true Ramanujan insight (see the article by S. G. Gindikin in «Kvant» No. 10 for 1987).

In addition to this ternary system, M. Golay in his 1949 work described another linear perfect system - a 20-system $C_3$ of length 23 with vectors of zeros and ones - a code with parameters $q=2$, $n=23$, $k=12$, correcting 3 errors. This system contains $2^{12}=4096$ vectors and could be useful for “Sportprognoz” on the 23rd trip in the game of no draws.

Exercise 11. Using the results of controls 7 and 8, show that system $C_3$ is perfect (and therefore contains the most possible number of cards among systems with such parameters).

The discovery made by Virtakallo is all the more surprising since for $q=3$ there are no other nontrivial perfect $l$-systems with $l \leqslant n-2$ for any values ​​of $n$. At $l=n-1$ there are also systems with the parameters given at the end of the previous paragraph. For $q=2$, the list of nontrivial perfect systems with $l \leqslant n-1$ is exhausted by the 20-systems $C_3$ and the family of $(n-1)$-systems with $n=2^m-1$ and $k=n-m$. These two statements follow from the global theorem on perfect codes, proven only in the early 70s.

Mathematical problems arising in connection with the Golay codes $C_2$ and $C_3$,

*) In Finland, when filling out the “Sportprognoz” card in 1947, it was required to submit the results of 12 matches (teler - 13). A card was considered a winner if at least 10 results were correct. Therefore, the $C_2$ system could be used if the player knew the results of one match for sure.

usually quite difficult. Next, the task of quickly (non-brute force) finding the winning card of the system $C_2$ based on the known result of the weight draw is not easy. Those who want to try their hand at this difficult (albeit solved) problem should use the control system (5) and act in two exercises 6 and 9. Maybe you will be able to discover some new way to solve this problem?

The last problem that we want to touch upon here in connection with “Sportforecast” will arise in the case when the player assumes that in $t$ of $n$ matches any of three outcomes is possible - a draw, a win and one of the teams will pass, and in $b=n-t$ matches it is almost impossible for it to win. (For example, in a football match between Barcelona (Madrid) and Zvezda (Perm), one of the teams can, at best, count on a draw.) Let us denote by $E_{2,3}(b,t)$ the set of vectors of length $b+t$, in which the first $b$ coordinates take values 0 or 1, and the last $t$ take values 0.1 or 2. The $l$-system $C$ for a mixed “Sports forecast” should consist of such vectors from $E_{2,3}(b,t)$ that for any vector $a \in E_{2,3}(b,t)$ there is a vector $c \in C$ located from $a$ at a Hamming distance of no more than $l$.

Exercises
12. Show that at a distance $\leqslant l$ from a fixed vector $a \in E_{2,3}(b,t)$ there are $E_{2,3}^n,w$ double vectors of length $n$ containing exactly $w$ units. We don't know any good systems for "Sportp"; one can get a simple inequality showing that any such system must contain quite a lot of cards. Their number, of course,
