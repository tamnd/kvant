---
id: 1981-9-yaglom-pochti-prostyie-chisla-bfa990c3
issue: kvant_1981_9
year: 1981
number: "9"
title: Almost prime numbers
authors:
  - Яглом И. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 18
page_last: 20
page_labels: 16, 18
tag: KB5V
lang: en
source: kvant_digital
extraction: vision
content_sha256: cbbfaebc6a1f3b8048fcccd210b03040636bc9e4c095fc995119b86c8a237af1
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/08_yaglom-pochti-prostyie-chisla-bfa990c3.md
source_content_sha256: 5fc37459484c466876c44ed226c18412e323d743d26e90af22ebc6a583d0f6c0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Almost prime numbers

How are discoveries made in mathematics? Often - just like in other sciences: the researcher tries to include a noticed fact as a special case in a general pattern. It is not always possible to find this pattern, and a mathematician, like any other researcher, acts by “trial and error.”
How his reasoning might look when it comes to the divisibility of numbers is described in this article.

1. Fermat's Little Theorem

It is clear that the square $n^2$ of the natural number $n$ will be even or odd at the same time as the number $n$ itself. Thus, the numbers $n^2$ and $n$ will always be both even and odd at the same time. But, moreover, this difference is always by 3. In fact, the number $n$ is either divisible by 3 (that is, has the form $3k$), or gives a remainder 1 when divided by 3 (has the form $n=3k+1$), or gives a remainder 2 when divided by 3 (then it can be represented as $n=3k+2=3(k+1)-1=3(k'-1)$).

If $n$ is divisible by 3, then $n^3$ is also divisible by 3. If $n$ has the form $3k \pm 1$, then $n^3=(3k \pm 1)^3=3(9k^3 \pm 9k^2+3k) \pm 1$, that is, $n^3=3l \pm 1$.

In all cases, the difference $n^3-n$ is a multiple of 3. So, we have

Statement 2. The difference $n^3-n$ is divisible by 3 for any $n$.

Exercises
1. Prove statements 1 and 2 by factoring the polynomials $n^2-n$ and $n^3-n$.
2. Prove that the difference $n^3-n$ is divisible by 6 for any $n$.

Statements 1 and 2 inspire hope that this is true.

Hypothesis 1. The difference $n^m-n$ is divisible by $m$ for any $m$ and $n$.

Alas! It is easy to come across a counterexample that refutes this hypothesis: the difference $2^4-2=14$ is not divisible by 4.

Still, I would like to find that the similarity between statements 1 and 2 is not accidental. Let's try to check the difference $n^5-n$. For example, $2^5-2=30$ is divisible by 5. It is easy to establish that this is not random, and is fair.

Statement 3. The difference $n^5-n$ is divisible by 5 for any $n$.

In fact, the number $n$ is either divisible by 5, or when divided by 5 gives one of the remainders 1, 4 (in these cases it can be represented as $5k \pm 1$), or when divided by 5 gives one of the remainders 2, 3 (then $n=5k \pm 2$). If $n$ is divisible by 5, then $n^5$ is divisible by 5. If $n=5k \pm 1$, then

$$n^2=(5k \pm 1)^2=5(5k^2 \pm 2k)+1.$$

If $n=5k \pm 2$, then

$$n^2=(5k \pm 2)^2=5(5k^2 \pm 4k+1)-1.$$

Thus, if $n$ is not divisible by 5, then the number $n^2$ is $5L \pm 1$ and

$$n^4=(5L \pm 1)^2=5(5L^2 \pm 2L)+1$$

gives a remainder of 1 when divided by 5. It follows that the difference $n^4-1$, and therefore the difference $n^5-n=n(n^4-1)$, is divisible by 5.

Now we already have three positive statements. This forces us to continue searching. Difference

⟦folio 18⟧

2. Almost prime numbers

Let us remember how we arrived at Fermat’s little theorem in the previous paragraph. Having fixed $m$, we found out whether all differences $n^m - n$ are divisible by $m$. To form a correct hypothesis, each time we first checked whether the number $2^m - 2$ is divisible by $m$. For all considered simple $m$, the difference $2^m - 2$ was divisible by $m$, for composite ones it was not divisible. Naturally arises

Hyothesis 5. Difference $2^m - 2$ divided by $m$ with simple $m$ and is not divisible - when compound*).

Hypothesis 5 was expressed by ancient Chinese mathematicians - about 2.5 thousand years ago.

In ancient China, as in all other civilizations preceding ancient Greece (Babylon, Ancient Egypt, etc.), mathematics was not a constructive science, but a grid science. The main role in mathematics was played not by conclusions, but by facts, and the question of how this or that fact was established was not considered particularly important: a sufficiently plausible proof could completely replace the proof. Having written out several dozen first numbers $N_m = 2^m - 2$ ($m = 2, 3, 4, \dots$) and checking which of them are divisible by $m$ and which are not, ancient Chinese mathematicians were convinced of the validity of Hypothesis 5 and recorded it as a theorem. However, you and I are not the ancient Chinese. The great Euclid and Archimedes (and even earlier, Pythagoras, Plato, and Aristotle) ​​convinced us that the essence of mathematics lies precisely in the proof of hypothesis 5 and recorded it as a theorem. However，我们没有证据表明 $m \neq 1$ is almost prime if the difference $2^m - 2$ is divisible by $m$.

By virtue of Fermat's little theorem, any prime number is almost prime. Therefore, hypothesis 5 can be reformulated as follows:

Hypothesis 5'. Which almost prime number is prime.

*) The first “half” of Conjecture 5 is, of course, part of the case of Fermat’s theorem.

We have already said that ancient Chinese mathematicians considered the divisibility by $m$ of several tens of the first numbers $N_m$ and did not find refuting examples. Today, with the help of a computer, it would not be difficult to check the divisibility by $m$ of several hundred first numbers $N_m$. However, even here it would not be easy to refute Hypothesis 5: among the first 300 natural numbers we would not find almost prime numbers that are not prime. However, hypothesis 5 is still incorrect, that is, it is true.

Theorem 2. There are almost prime numbers that are not prime.

The smallest such number is 341. It was impossible to find it, but proving that it is almost prime is not at all difficult if we have

Lemma 1. The difference $n^m - 1$ is divisible by $n - 1$ for any $m$ and $n$, following from the point of prime numbers that are not prime.

Lemma 2. The difference $n^m - 1$ is divisible by $n - 1$ for any $m$ and $n$, following from the point of prime numbers that are not prime, and $m_1 > m$.

Indeed, since $m$ is not prime, $m = kL$, where $k > 1$, $L > 1$. Then, by Lemma 1,

$$m_1 = 2^m - 1 = 2^{kL} - 1 = (2^k)^L - 1$$

is divisible by $2^k - 1$. From $L > 1$ follows $2^k - 1 < m_1$. $k > 1$ implies $2^k - 1 > 1$. This means that $m_1$ is not prime.

Since $m$ is almost prime, $m_1 = 2^m - 2 = N_m$ is divisible by $m$: $N_m = mn$. Therefore, by Lemma 1,
