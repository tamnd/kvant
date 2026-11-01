---
id: 1986-10-chisla-mersenna-5bffed1c
issue: kvant_1986_10
year: 1986
number: "10"
title: Mersenne numbers
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 26
page_last: 27
page_labels: 24-25
tag: UWO5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 421dbf592bcf1e0d69049731ecbed7436b03c8e6e1713ab338ecd8c684ebddbb
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/11_chisla-mersenna-5bffed1c.md
source_content_sha256: 91d8703c744903bba4ea1df02e1b9811d13bc9289c2d9e747bec488d84244647
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Mersenne numbers

Mathematics, like most modern sciences, is currently developing at an all-age speed. There are hundreds of mathematical journals published around the world, in which ten thousand scientific papers are published every day. And 350 years ago there were no mathematical journals, and scientists exchanged the results of their research in personal letters. True, there was one person - the French monk Maren Mersenne (1588-1648) who received such letters more than others. Mersenne knew to write about the discovery of a new theorem and establish his priority, since Mersenne, as a rule, informed his other correspondents about this, including R. Descartes, V. Pascal, P. Fermat, H. Heugens and many other scientists of that time.

This activity of Marin Mersenne contributed to the creation of the Academy of Sciences in Paris.

Of Mersenne's own mathematical achievements, the most famous are the numbers of the form $M_n=2^n-1$ he studied.

Anyone who knows what a geometric progression is will immediately notice that $M_n$ is equal to the sum of the first $n$ terms of the geometric progression with the initial term $2^\circ=1$ and is called 2:

$$M_n=2^\circ+2^1+2^2+\dots+2^{n-1}.$$

Mersenne was interested in which of the numbers $M_n=2^n-1$ were prime. This question arose in a problem posed by the ancient Greeks (we will return to it later).

Prime numbers obtained by the formula $2^n-1$ are called Mersenne numbers.

Let's try and touch a little on the problem of finding Mersenne numbers.

Let's calculate the first few numbers $M_n=2^n-1$ and write them in order in a table of four columns. The first worry: numbers that fall into the same column end up on the same digit. Namely, the numbers that fall into the first column are 1, the second - 3, the third - 7 and the fourth - 5 (try strictly

⟦folio 25⟧

justify this observation). This means that the numbers $M_n$ that fall into the fourth column are divisible by 5, and there cannot be Mersenne numbers among them.

It is not difficult to prove the second observation: the numbers falling into the second and fourth columns are divisible by 3. Indeed, the difference of two consecutive numbers $M_{2k}$ and $M_{2k+2}$ with four numbers is equal

$$(2^{2k+2}-1)-(2^{2k}-1)=2^{2k+2}-2^{2k}=3\cdot 2^k.$$

Therefore, if the number $M_{2k}$ is divisible by 3, then $M_{2k+2}$ is also divisible by 3. And the number $M_2$ is equal to three.

Therefore, it makes sense to look for Mersenne numbers (with the exception of $M_2=3$) only in the first and third columns.

A simpler study of the numbers $M_n$ leads to a third observation: if $n$ is a composite number, $n=kl$, $k>1$, $l>1$, then $M_n$ is divisible by $M_k$ and $M_l$. (This follows from the fact that $2^{kl}-1=(2^k)l-1=(2^l)k-1$, and $(x^m-1)=(x-1)(x^{m-1}+x^{m-2}+...+x+1)).$ By the way, the first two also follow from the third observation, since all numbers in the second column are divisible by $M_2=3$, and all numbers in the fourth column are divisible by $M_4=15$.

So, the number $2^n-1$ will be prime only if $n$ is prime.

But for any prime $p$ the number $M_p$ will be prime? The hope for a positive answer collapses very quickly: the number $M_{11}=2047=23\cdot 89$ is already composite.

Mersenne himself indicated all the prime values ​​of $n$, not exceeding 257, for which, in his opinion, the numbers $M_n=2^n-1$ would be prime. However, Mersenne did not provide proof; it was later discovered that his prediction was partly wrong.

Leonard Euler, a member of the St. Petersburg Academy of Sciences, one of the greatest mathematicians of the modern era, is also engaged in the search for Mersenne numbers. In 1750, he discovered the tenth Mersenne number; this is $M_{31}=2147483647$.

If earlier the Japanese calculation of Mersenne numbers was carried out using “handicraft” methods, then in the 20th century computers began to work, counting at enormous speed. In 1952, five new Mersenne numbers were discovered at once: $M_{521}, M_{607}, M_{1279}, M_{2203}$ and $M_{2281}$; they are the corresponding thirteenth to seventeenth Mersenne numbers. The next six Mersenne numbers were found between 1958 and 1963. Finally, in 1971, the 24th Mersenne number $M_{19937}$ was found, in 1978 - the 25th Mersenne number $M_{21701}$, in 1979 - the 26th and 27th Mersenne numbers $M_{23209}$ and $M_{44497}$. The last known Mersenne number was found in 1983: it is $M_{86243}$; but it is not yet known whether it is the 28th Mersenne number.

And in conclusion, let us explain the interest in the Mersenne number. The fact is that they are associated with the so-called perfect numbers (which the ancient Greeks studied) - numbers equal to the sum of all their divisors, different, of course, from the number itself (for example, $6=1+2+3$, $28=1+2+4+7+14$, $496=1+2+4+8+16+31+62+124+248$ - the first three perfect numbers). Euclid also proved (you too!) that if the number $2^n-1$ is prime, then the number $2^{n-1}(2^n-1)$ is perfect. Leonhard Euler proved that all even numbers are perfect? But no one has yet found odd perfect numbers, and no one has yet proven that such numbers do not exist.

Based on materials from Yu. V. Korolev and O. M. Mamedov
