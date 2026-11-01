---
id: 1979-9-shirshov-ob-odnoy-kombinatornoy-zadache-2740f62d
issue: kvant_1979_9
year: 1979
number: "9"
title: About one combinatorial problem
authors:
  - Ширшов А. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 22
page_labels: 19-20
tag: ZY85
lang: en
source: kvant_digital
extraction: vision
content_sha256: 74608ac4a2228602f65860543840caff49bc6f5fdec295ca7187de115021c5fb
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/08_shirshov-ob-odnoy-kombinatornoy-zadache-2740f62d.md
source_content_sha256: 75bff3984250d2b738cc4f0aa1c9d700fa0e8943551a96ccd3f1b0451c34f7dd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

A. Shirtsov

About one combinatorial problem

As you well know, general multiplication is associative: $(ab)c=a(bc)$ for any numbers. Associative and multiplication of functions: $(f(x)g(x))z(x)=f(x)(g(x)z(x))$.

However, in a number of branches of mathematics, non-associative “multiplications” are considered. If multiplication is non-associative, it comes only with parentheses to indicate the order of operation, just as it comes with school examples involving addition and multiplication or division.

Consider the words $a_1a_2a_3...a_n$. In how many ways can the parentheses be placed in it so that the non-associative “product” of these “letters” can be calculated? Let us denote the number of such ways by $\varphi(n)$. It is clear that $\varphi(1)=1$ and $\varphi(2)=1$. For the three-letter word $a_1a_2a_3$, there are two “good” parenthesis arrangements: $(a_1a_2)a_3$ and $a_1(a_2a_3)$. For four-letter letters, there are five such arrangements: $a_1(a_2(a_3a_4))$, $a_1((a_2a_3)a_4)$, $(a_1a_2)(a_3a_4)$, $((a_1a_2)a_3)a_4$ and $(a_1(a_2a_3))a_4$. Therefore $\varphi(3)=2$, $\varphi(4)=5$. (Show yourself that $\varphi(5)=14$, $\varphi(6)=42$.) The numbers $\varphi(n)$ are called Catalan numbers. In «Kvant» No. 7 for 1978, these numbers were discussed in detail. The connection between these numbers and the placement of brackets is also mentioned there. In this note I want to give a simple proof of the following formula for numbers

$$\varphi(n) = \frac{1}{2n-1} C_{2n-1}^{n-1}.$$ (*)

(From this formula it follows that the number $\frac{1}{2n-1} C_{2n-1}^{n-1}$ is an integer for all $n$.)

First, I need to introduce the concept of cyclic comparable words. It's easier to start with an example. From the symbols $a_1, a_2, a_3$, taken one at a time, two classes of cyclic comparable words can be formed:

$$\{a_1a_2a_3, a_2a_3a_1, a_3a_1a_2\}$$

And

$$\{a_1a_3a_2, a_3a_2a_1, a_2a_1a_3\}.$$

To get these classes, you need to write the symbols $a_1, a_2, a_3$ in a circle, like on a watch dial, and then start writing clockwise from any of the symbols.

Let us now give a precise definition. Two words $A$ and $B$ are said to be cyclically comparable if

$$A = b_1b_2...b_kb_{k+1}...b_n$$

$$B = b_kb_{k+1}...b_nb_1b_2...b_{k-1}.$$

Let us now proceed as follows. Each non-associative word (as we will call words with correctly placed parentheses) from the symbols $a_1, a_2, ..., a_n$ will be associated with an associative word (that is, a word without parentheses) from the symbols $a_1, ..., a_n$, $p$ according to the following rule: $a_i \rightarrow a_i$ and, if $u \rightarrow A$, $v \rightarrow B$, then $u \cdot v \rightarrow ABp$. For example, $a_1a_2 \rightarrow a_1a_2p$, $a_1(a_2a_3) \rightarrow a_1a_2a_3pp$, $a_1((a_2a_3)a_4) \rightarrow a_1a_2a_3pa_4pp$, $(a_1a_2)(a_3a_4) \rightarrow a_1a_2pa_3a_4pp$.

It is easy to understand that for every non-associative word of length $k$ from symbols $a_i$ there corresponds some associative word of length $2k-1$, in which $p$ occurs $k-1$ times. The converse, finite, is false. For example, the words $ppa_1a_2a_3$ or $a_1pa_2a_3p$ cannot be obtained using the described procedure. However, the following statement is true:

Lemma. Let $A$ be some associative word of length $2n-1$, co-

⟦folio 20⟧

holding each of the symbols $a_i$ ($i=1, 2, \dots, n$) once and the symbol $p$ $n-1$ times. Then there is one and only one cyclically comparable word $A$ (possibly itself) associative word that corresponds to some non-associative word of length $n$ from characters $a_1, a_2, \dots, a_n$.

This lemma is similar in nature to many simple problems published in «Kvant». I will give its proof only for the sake of presentation.

Obviously, in the class of cyclic words comparable to $A$, it makes sense to consider only those that do not begin with the symbol $p$, but end with the symbol $p$. These, of course, exist. In such a $A_1$ - this is also easy to understand - there is a subword (part of a word) of the form $a_i a_j p$, corresponding to the non-associative word $a_i a_j$. Let's denote this piece of the word $A_1$ by $a_i$. We have received a word that contains $a_1, a_2, \dots, a_n$, does not include $a_j$, and the symbol $p$ appears $n-2$ times. The proof of the lemma follows from simple induction with respect to the number $n$.

The basis for induction is to consider words like $a_1 a_2 p$ or similar.

So, the lemma is proven. Now formula (*) becomes almost obvious. In fact, among $2n-1$ places we can choose in exactly $C_{2n-1}^{n-1}$ ways the arrangement $n-1$ of the symbol $p$, and in the remaining places we can arrange the symbols $a_1, a_2, \dots, a_n$ in such a way that in a cyclic comparable “good” associative word the indices $y_i$ are in the order of their sequential increase from 1 to $n$. Since in each class of cyclic comparable words of length $2n-1$ there are exactly $2n-1$ times and the terms of their (why?) elements are $\varphi(n) = \frac{1}{2n-1} C_{2n-1}^{n-1}$.

Formula (*) has been proven.

In conclusion, I want to tell you about the interactive history produced with this task.

The popular American mathematical magazine “The American Mathematical Monthly” (AMM for short) in 1935 published the problem of the famous mathematician G. Birkhoff (No. 3674) in the following formulation:

Show that for every positive k the expression $\varphi(k) = \frac{1}{2k-1} C_{2k-1}^{k-1}$ is an integer; prove the validity of the recurrence relation

$\varphi(k) = \varphi(1) \varphi(k-1) + \varphi(2) \varphi(k-2) + \dots + \varphi(k-1)\varphi(1)$.

It is easy to understand that G. Birkhoff, dealing with similar issues, arrived at formula (*) empirically. Recurrent correspondence, on closer examination, is very indo.

This problem was solved using fairly powerful means of mathematical analysis in October 1935.

Therefore, it seemed to me that the scales of the page in the same magazine for 1941 saw the printed problem (No. 3954) of another good famous mathematician O. Ore:

From three elements $a, b, c$, given in the specified order, it is possible to compose $\varphi(3)=2$ the product of $(ab)c$ and $a(bc)$, unless we assume that the law of associativity holds. Analogously, from the four elements $a, b, c, d$ one can compose the product $\varphi(4)=5$

$[(ab)c]d, [a(bc)]d, a[(bc)d], a[b(cd)], (ab)(cd)$.

Find a general expression $\varphi(n)$ for $n$ multipliers.

In this formulation, this problem was solved in the same year, 1941. I did not get acquainted with the solution, since it very closely followed from a simple reference to the previous problem.

Now here's what's interesting. In 1957, the editors of AMM decided to devote a separate issue of the magazine to the memos of O. Dunkel, who headed the problems department for many years. A jury composed of 25 well-known mathematical problems from those submitted to this journal for inclusion in the corresponding issue. To my surprise, both of these tasks were independently chosen.

(For the end see p. 32)
