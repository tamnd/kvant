---
id: 1972-4-vasilev-rasstanovka-kubikov-535a6248
issue: kvant_1972_4
year: 1972
number: "4"
title: Arrangement of cubes
authors:
  - Васильев Н. Б.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6, 8, 9
tag: 61ON
lang: en
source: kvant_digital
extraction: vision
content_sha256: be4774f01efc60cc28a50f2622ce68e35c021f4ff31a822174b344aa5f197a5e
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/04_vasilev-rasstanovka-kubikov-535a6248.md
source_content_sha256: 69f9ba39e1d9e8d19cb33283116262e2bf8439f6141d2b78790c911f724c2c97
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

Fig. 4.

Let's call a layer a set of cells whose centers lie in a plane parallel to one of the faces of the dock, and a line - a set of cells whose centers lie on a straight line parallel to an edge; a layer consists of $n^2$ cells, a line - of $n$ cells. Let's draw the projection of the dock onto one of the faces, say, onto the plane $Ox_1x_2$ (front view) and on each field of the resulting dock $n \times n$ we write the number of the layer in which the rook occurs, projecting onto this field. Then the arrangement of rooks shown in figure 3 will be written as shown in figure 4 (we will not encounter situations where there is more than one rook in one line, so dockki $n \times n$ will write no more than one number on each square). Note that on figure 4, for every empty field in the row and column at the intersection of which it stands, all the numbers appear: 1, 2 and 3. This means that every dock field $3 \times 3 \times 3$ that is not in the $x_3$ direction will be either in the $x_1$ direction or in the $x_2$ direction.

So, we are convinced that $A_3 \leq 5$. The fact that $A_3 \geq 4$ has already been proven (see (1)). The question arises: what is $A_3$ equal to: 4 or 5? We provide readers with the opportunity to diversify

take the case $n=3, n=4$, etc., and then go straight to the general case.

Exercise that 4 rooks cannot be placed so that they are only dockku $3 \times 3 \times 3$; 6) indicates an example of the placement of 8 rooks, which would be $4 \times 4 \times 4$ in total; in the document that $A_4=8$.

General case. Formulation of the result

In our task, perhaps the most difficult thing is to come up with the correct hypothesis: what is equal to $A_n$. This answer is already much easier to construct an example (that is, estimate $A_n$ from above), and prove that it is impossible to get by with fewer rooks. And the answer is:

$$A_n = \begin{cases} \frac{n^2}{2}, \text{ если } n \text{ четно}, \\ \frac{n^2 + 1}{2}, \text{ если } n \text{ нечетно}. \end{cases}$$

Specifically, $A_4=8$, $A_5=13, \dots, A_{10}=50$.

Examples of the "optimal" arrangement of $A_n$ rooks are clear from figure 5, $a$ ($n$ even) and 5, $b$ ($n$ odd). It is easy to check that all fields that do not exist in the $x_3$ direction exist either in the $x_1$ or in the $x_2$ direction: in each “cross” - a row and column at the intersection of which there is an empty field - all numbers from 1 to $n$ occur.

It remains to prove that with fewer rooks they cannot capture the entire dock.

First proof

Let the $M$ rooks be placed so that they are from all squares docked. From all the layers, choose the one in which the number of rooks is minimal (if there are several such layers, is it possible). We can assume that it is located parallel to the plane $Ox_1x_2$. Let's denote this layer by $S$, and the number of rooks in it by $m$. Let these $m$ rooks be from $m_1$ rows in the direction of $x_1$ and $m_2$ rows in the direction $x_2$ (we can assume that $m_1 \geq m_2$; of course, $m \geq m_1$ and $m \geq m_2$). Then

⟦folio 8⟧

Second proof

Lemma. Let $n \times n$ be integer non-negative numbers in the table so that if some field contains 0, then the sum of all numbers in the row and column at the intersection of which this field stands is not less than $n$. then the sum of all numbers in the table is not less than $\frac{n^2}{2}$ (and therefore, if all the numbers in the table are integers, then if $n$ is odd, this sum is not less than $\frac{n^2+1}{2}$).

From the lemma you need an estimate for $A_n$ it’s easy: just project the board onto one of the faces and write in which field of the resulting table $n \times n$ how many rooks were projected into it. It is clear that the conditions of the lemma for the resulting table will be satisfied.

It remains to prove the lemma. We will not do this, since this lemma has already appeared recently in «Kvant»: paradoxically, it was proposed last year as a separate problem at the International Olympiad (see «Kvant» No. 12, 1971). Unfortunately, the second proof of our problem, and thus the lemma, was not discussed at the analysis of the problem at the All-Union Olympiad, so neither the leaders of the Soviet team knew this lemma (otherwise they, of course, would have added it so that it would not be offered to schoolchildren as too well-known), nor the participants of our team (otherwise they all solved it flawlessly).

So, the main task discussed in points a), b) and c) conditions, solutions.

Notes on generalizations

As for the more general problem formulated in paragraph r), a similar problem not for a “three-dimensional” but for a “k-dimensional” board ($k \geq 4$), here the final result is not known. For the minimum number of $A_n^k$ rooks, there are only $n \times n \times \dots \times n$ boards (we keep the chess terminology, but for example that now the $x$ square is a set of $k$ numbers ($x_1, x_2, \dots, x_k$),

where each $k$ takes a value from 1 to $n$), it is easy to obtain estimates similar to (1), (2):

$$A_n^k \leq n^{k-1}, A_n^k \geq \frac{n^k}{k(n-1)+1}.$$

Have razzhene 4. Prove these inequalities. Try to improve the score $n^{k-1}$ using the same considerations as in Exercise 2.

Since $A_n^2=n$ and $A_n^3$ are equal to $\frac{n^2}{2}$ or $\frac{n^2+1}{2}$, the hypothesis is that $A_n^k$ is close to $\frac{n^{k-1}}{k-1}$. This hypothesis, along with others, was discussed by Olympic participants and jury members not only during the Olympics, but also after it. However, the most interesting results were reported to us by D. Grigoriev, a graduate of the Physics and Mathematics School at Leningrad University, and our reader V. Ginzburg: they (independently) managed to prove that if $M$ rooks were the entire board and no two were different, then $M \geq \frac{n^{k-1}}{k-1}$ (we place the proof at the end of the article). Apparently, this result is true even without the additional assumption highlighted in italics, that is, the inequality $A_n^k \geq \frac{n^{k-1}}{k-1}$ is true, and, as the examples showed, for $n > k$ this estimate is quite close to the exact one (or even coincides exactly with it).

However, the estimate $\frac{n^{k-1}}{k-1}$ depends is not "very accurate" for all $n$ and $k$.

For example, if $n=2$, then $\frac{n^{k-1}}{k-1} = \frac{2^{k-1}}{k-1}$, and the “rough” estimate $\frac{n^k}{k(n-1)+1} = \frac{2^k}{k+1}$ turned out to be the best (for $k>3$); for large $k$ the number $\frac{2^k}{k+1}$ is applied twice as much as $\frac{2}{k-1}$.

The razzhene has 5. Find $A_2^4, A_3^4, A_2^5$.

Some words about code problems

One problem, very close in our formulation, is significantly premature—premature because it is important for applications. In “chess terms” it sounds like this: which is the most

⟦folio 9⟧

neck number of rooks can be placed on a $k$-dimensional board $n \times n \times \dots \times n$ so that they are not each other? (Another option: so that no field is double?) In other words: what set $Y$ of sets $y = (y_1, y_2, \dots, y_k)$ can be composed so that a) every two sets in $Y$ differ in more than one coordinate, or b) every set $x = (x_1, x_2, \dots, x_k)$, in the set $Y$ there is at most one set $y$, different from $x$ in only one coordinate? The formation of tasks directly relates to the theory of information science, or more precisely, to its section - the theory of error-correcting codes. This theory deals with problems of this type: to compose a set of $Y$ “words” $(y_1, y_2, \dots, y_k)$ such that if, when transmitting one of these words (say, by telephone or via a communication channel in a computer) it is included in some “letter”, then this error could be detected, and even better, corrected, that is, the transmitted “words” could be restored. Therefore, the set $Y$ that satisfies condition a) is called a “single error detection code”, and the set satisfying condition b) is called a “single error correcting code”. You see that in mathematics the word “code” is not used in exactly the same way as in the spin books.

In law b. Let $B_n^k$ be the maximum number of rooks that can be placed on a $k$-dimensional board $n \times n \times \dots \times n$ so that they are not each other a) Which number is greater: $B_n^k$ or $A_n^k$? b) Find $B_n^2, B_n^3, B_n^4$.

The theory of codes is perhaps the most striking example of the application of modern algebra in a field that, at first glance, is far from being directly related to technical applications. Having devoted many scientific works and several thick books to her, she is developing rapidly and deserves specialization of acquaintance.

*) W. Peterson. Codes that guide errors, "Mir", 1964; E. Berlekham p Algebraic Coding Theory, "World", 1971.

Application

Theorem. Let $X$ be the set of all tuples $x = (x_1, x_2, \dots, x_k+1)$, where each of the $k+1$ coordinates $x$ takes $n$ values: $1, 2, \dots, n$; $Y$ is a subset of $X$ such that (1) any two sets of $Y$ differ in at least two coordinates and (2) for each $x$ of $X$ there is a set $y$ of $Y$ that differs from $x$ in at most one coordinate. Then there are at most $n^k/k$ elements in $Y$.

Proof. Let $\alpha(x)=1$ if $x$ belongs to $Y$, and $\alpha(x)=0$ if not. Let's put $\beta(x)=\beta(x_1, x_2, \dots, x_k)$:

$$\sum_{i=1}^{k} \alpha(x_i, x_j, \dots, x_k) = \sum_{i=1}^{k} \alpha(x_i, x_j, \dots, x_k) = \sum_{i=1}^{k} \beta(x_i, x_j, \dots, x_k)$$

(“Shortened” sets of $k$ and $(k-1)$ coordinates we will denote by the same letter $x$, remembering that the arguments $\beta$ always have $x_{k+1}$ thrown out, and $y \gamma_i - x_{k+1}$, and $x_i$. By condition (1) $\beta(x) \leq 1$ for any $x$. By condition (2), if $\beta(x)=0$ for some $x$, then $\sum_{i=1}^{k} \gamma_i(x) \geq n$ for this $x$ Therefore, for all $x$ without exception.

$$\sum_{i=1}^{k} \gamma_i(x) (1-\beta(x)) \geq n (1-\beta(x))$$

Let us sum up all such inequalities corresponding to $n^k$ different sets $(x_1, x_2, \dots, x_k)$. We denote this summation by the letter $\Sigma'$, and the summation over all coordinates except $x_i$ by $\Sigma'_i$. Let the total number of elements $Y$ be different $M$. Then, since $\Sigma'_i(x)=M$ and $\Sigma'_i(y)=M$ for each $i$, we get

$$\sum_{i=1}^{k} (nM - \sum_{i=1}^{k} \gamma_i^2(x)) \geq n^{k+1}-nM$$

Since the sum of squares $N$ of real numbers is not less than the square sums divided by $N$, the left-hand side is at most

$$\sum_{i=1}^{k} (nM - \sum_{i=1}^{k} \gamma_i^2(x)) \leq \sum_{i=1}^{k} \left( nM - \frac{(\sum_{i=1}^{k} \gamma_i(x))^2}{n^{k-1}} \right) = knM - \frac{kM^2}{n^{k-1}}.$$

Thus, the inequality is true

$$knM - \frac{kM^2}{n^{k-1}} \geq n^{k+1}-nM,$$

whence $M \leq n^{k/k}$.
