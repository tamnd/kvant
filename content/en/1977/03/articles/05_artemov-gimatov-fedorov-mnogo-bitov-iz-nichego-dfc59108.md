---
id: 1977-3-artemov-gimatov-fedorov-mnogo-bitov-iz-nichego-dfc59108
issue: kvant_1977_3
year: 1977
number: "3"
title: A lot of bits about nothing
authors:
  - Артёмов С. Н.
  - Гиматов Ю.
  - Фёдоров В.
rubric: osnovnye-stati
page_first: 14
page_last: 16
page_labels: 12-14
tag: 0RN6
lang: en
source: kvant_digital
extraction: vision
content_sha256: aa76a9531c725373e8a113696dfbe788c7a860f977aa666c876dac0f0917f0aa
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/05_artemov-gimatov-fedorov-mnogo-bitov-iz-nichego-dfc59108.md
source_content_sha256: f7f1677797063e01959deffc9ab163b6951ed64d4650985bceaeffb1ab9fc472
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

A lot of bits about nothing

He thought I fell asleep
And I will endure everything in my sleep,
Or thought what I thought
What he thought was “I’m dreaming.”
S. Marshak. From Coventry Patmore.

We bring to the attention of readers a problem that requires a lot of sophisticated logic to solve:

Mathematician R said to mathematicians P and S: “I have two natural numbers in mind. Each of them is greater than one, and their sum is less than cm. I will now tell the mathematician P, in confidence from S, the product of these numbers, and I will tell the mathematician S, in confidence from P, their sum.” He fulfilled his promise and offered to set the planned numbers. The following dialogue will take place between P and S (we denote the statements of P by the letter l with indices, the statements of S by the letter σ):

“Sorry, I can’t say what the intended numbers are.” (π₁)
- I knew in advance that you couldn’t do it. (σ₁)
- But I know them, my dear. (π₂)
- And I know them too. (σ₂)
Now try to puzzle out the numbers you have in mind.

1. Is it really possible to guess them?

At first glance at the problem, it seems unsolvable: how

Bit is a double unit of measurement of information (TSB, 3rd ed., 2 vols.).

Is it possible to guess numbers when nothing is said about them?

Let's try it with an example. Let R ask 7 and 42. Then he told P the number 294, S - 49. Well, what next? P said that he could not guess the numbers he had in mind. Well, of course he can - he only knows their work. Although, however, he also knows that they are natural, more than ones and their sum is less than one hundred. What does this give?

Let us denote the intended numbers by k₀ and l₀, and let, for the sake of definition, k₀ ≤ l₀. Let us also denote the product k₀ · l₀ by p₀, and the sum k₀ + l₀ by s₀.

So, P was informed that p₀ = 294. Then k₀ can be equal to 2, 3, 6, 7 and 14, and l₀ will be equal to, respectively, 147, 98, 49, 42 and 21. The first two values ​​​​for k₀ do not suit us - for them s₀ > 100. Still, there are still three more possibilities. This means that P really cannot guess the intended numbers.

Let's move on. S claims that he knew in advance that P could not guess k₀ and l₀. How did S come to this conclusion? Surely he tried in every possible way to represent the known s₀ as the sum of two admissible terms:

49 = 2 + 47 = 3 + 46 = ...
... = 24 + 25.

R could have intended any of these pairs of numbers. He told P some of the products i · (49 − i), and S claims that from none of them P can guess the numbers he was thinking about.

And if for some i both numbers i, 49 − i are prime? For example, if R asked 2 and 47, then he told P 94, and P can guess the numbers perfectly well.

Therefore, if R gave 7 and 42, then S, having received s₀ = 49, would not have product rights (σ₁). This means that R could not have conceived 7 and 42.

Thus, it is still possible to say something about the intended numbers.

Before the initial shifts, let's think about the direction of movement. However, the guessing method is already visible: take all possible pairs of numbers k₀, l₀, satisfying

⟦folio 13⟧

inequalities
$$2 \leq k_0 \leq l_0 \leq 97,$$
$$4 \leq k_0 + l_0 \leq 99,$$
(1)
(2)

and check whether they “withstand” the dialogue $(\pi_1) - (\sigma_2)$.

Since the search is finite in all cases, in principle it would be possible to act this way. However, solving the problem this way is boring. We are trying to reduce the overkill.

First of all, let's first not $k_0$ and $l_0$, but their sum $s_0$: for the pair $\langle k_0, l_0 \rangle$ of possible options greater than two thousand, and for $s_0$ - less than a hundred. However, even on this path, any search is long and boring.

2. About the Holbach-Euler hypothesis

What information can be extracted from $(\pi_1)$ and $(\sigma_1)$? What do they mean? $(\pi_1)$ obviously means that $p_0$ does not uniquely decompose into the product of two factors satisfying inequalities (1), (2);

$(\sigma_1)$ means that For any decomposition of the number $s_0$ into the sum of two terms satisfying inequalities (1), their product has the property $(\pi_1')$.

The statement $(\pi_1')$ allows us to discard some products, $(\sigma_1')$ - some sums.

From $(\sigma_1')$ it follows that $s_0$ cannot be represented as a sum of two prime numbers: if $s_0' = q_1 + q_2$, where $q_1, q_2$ are primes, then the number $q_1 \cdot q_2$ uniquely resolves into the product of two factors satisfying inequalities (1), (2), and, therefore, does not have the property $(\pi_1')$.

But any even number that satisfies inequalities (2) can be represented as a sum of two primes (this is proven by sequentially checking the numbers 4, 6, 8, ..., 98).

Therefore, $s_0$ is odd. In addition, $s_0 - 2$ is a composite: otherwise $s_0 = 2 + (s_0 - 2)$ would be represented as the sum of two primes.

simple. After discarding numbers that do not satisfy these two conditions, 24 possibilities remain for $s_0$.

Above we took advantage of the fact that all even numbers from 4 to 98 can be represented as the sum of two primes.

In 1742, a member of the St. Petersburg Academy of Sciences, Christan Holbach, in a letter to Leonhard Euler, proposed that any odd number greater than a heel could be represented as the sum of two prime numbers. In his reply letter, Euler put forward the hypothesis that every even number greater than two can be represented as the sum of two prime numbers. (It is very easy to derive the Holbach conjecture from Euler's hypothesis - do it!)

For almost two hundred years, the hypotheses of Holbach and Euler seemed perfect for proof, although the indirect search of the mathematician Millet tested them to 9,000,000.

In 1930, the remarkable Soviet mathematician L. G. Shinirelman proved the existence of a $k$ such that every natural number $n > 1$ can be represented as a sum of at most $k$ prime numbers. Shinirelm's number $k$ was quite large. It has now been proven that Shinirelm's theorem is true for $k = 20$.

In 1934, academician I.M. Vinogradov proved the existence of a $n_0$ such that any odd number $n > n_0$ can be represented as a sum of three prime numbers. It would seem that in the age of computers it would be possible to instruct a machine to check the “remaining” numbers (from 7 to $n_0$), but the “Vinogradov constant” $n_0$ is so large (according to the latest estimates $n_0 > 2^{216}$) that this check exceeds the capabilities of improving the computer.

No significant success has yet been achieved in proving Euler's hypothesis.

3. Further into the forest

It turns out that $s_0 < 55$ can be derived from $(\sigma_1')$. (3)

Indeed, suppose that $s_0 \geq 55$. Then $s_0$ does not have the property $(\sigma_1')$: it can be decomposed into the sum of two terms satisfying inequalities (1) in such a way that condition $(\pi_1')$ is not satisfied for their product. This decomposition is: $s_0 = (s_0 - 53) + 53$. From $s_0 \geq 55$ follows $s_0 - 53 \geq 2$. The product $(s_0 - 53) \cdot 53$ uniquely resolves into two factors, with the mind of which this is less: since 53 is a prime number, one of the factors is necessarily of the form 53d; since $53 \cdot 2 > 100$, $d = 1$. But by condition $s_0$ has the property $(\sigma_1')$. Contradiction!

⟦folio 14⟧

After (3) for $s_0$ there are already 11 possibilities left:
$$11, 17, 23, 27, 29, 35, 37, 41, 47, 51, 53.$$

Let us now try to establish, without brute force, which of the numbers (4) satisfy the conditions ($\sigma'_1$). Let $s$ be an arbitrary one of the numbers (4). Since $s$ is odd, any expansion of it into a sum has the form $s = 2a + m$. Suppose $s$ does not have the property ($\sigma'_1$). Then he will find a $a$ such that the product $2a \cdot m$ “deciphers” uniquely.

This $a$ cannot equal one, since in this case $s = 2 + m$, and the product $2m$ is doubly decomposed into a product. Indeed, since $m = s - 2$ is a composite odd number, $m = pq$, where $p > 2$ and $q > 2$. Both expansions

$$2m = 2 \cdot pq = 2p \cdot q$$

suitable: $2 + pq = 2 + m = s < 100$ and $2p + q = 2 + pq - (p - 1)(q - 2) < 2 + pq < 100$.

So, $a \geq 2$.

If $a \neq m$, then $s = 2a \cdot m$ and $s = 2m \cdot a$ are two different expansions. Since $2a + m = s < 100$ and $s$ do not have the property ($\sigma'_1$), there must be $2m + a \geq 100$. Since $s = 2a + m \leq 53$, we have $m \leq 53 - 2a$, $2m + a \leq 106 - 3a$. From $2m + a \geq 100$ and $2m + a \leq 106 - 3a$ follows $a \leq 2$. Therefore, $a = 2$. From $2m + a \geq 100$ and $m \leq 53 - 2a$ we now obtain $m = 49$. So, in this case $s = 53$, and the “suspicious” decomposition is $53 = 4 + 49$.

If $a = m$, then $s = 3a$ is divisible by 3. In (4) there are two such numbers: 27 and 51. “Suspicious” are the expansions $27 = 9 + 18$ and $51 = 17 + 34$.

The number 51 really does not have the property ($\sigma'_1$): $51 = 17 + 34$, and the product 17·34 when factored into two factors gives only one sum, less than the drain. Thus, it can be removed from the list of "candidates for $s_0$".

The numbers 27 and 53 satisfy the conditions ($\sigma'_1$): $9 \cdot 18 = 2 \cdot 81$ and $2 + 81 < 100; 4 \cdot 49 = 7 \cdot 28$ and $7 + 28 < 100$.

So, there are 10 candidates left for further study: 11, 17, 23, 27, 29, 35, 37, 41, 47, 53, all of which have the property ($\sigma'_1$).

4. “Then I know them too”

Finally, we use $(\pi_2)$ and $(\sigma_2)$.

We could use $(\pi_2)$ and $(\sigma_2)$ in the same way we did with $(\pi_1)$ and $(\sigma_1)$. We'll try to do without it.

From $(\sigma_2)$ and (3) we can deduce

$$s_0 < 33.$$

Let's assume the opposite: $s_0 \geq 33$. Then $S$, expanding $s_0$ in all possible ways into the sum of two terms, we would have among these expansions $s_0 = (s_0 - 31) + 31 = (s_0 - 29) + 29$.

If $P$ had been told the product of $(s_0 - 31) \cdot 31$, then he could have reported that 31 is a prime number, understood that $(s_0 - 31) \cdot 31$ is uniquely decomposed into the product of two factors whose sum satisfies (3). In this case, $P$ would guess $k_0$ and $l_0$.

$P$ had a similar opportunity if the product $(s_0 - 29) \cdot 29$ had been reported.

This means that in the case of $s = 53$, the “suspicious” decomposition is $53 = 4 + 49$.

If $a = m$, then $s = 3a$ is divisible by 3. In (4) there are two such numbers: 27 and 51. “Suspicious” is the decomposition $27 = 9 + 18$ and $51 = 17 + 34$.

The number 51 really does not have the property ($\sigma'_1$): $51 = 17 + 34$, and the product 17·34 when factored into two factors gives only one sum, less than the drain. Thus, it can be removed from the list of "candidates for $s_0$".

The numbers 27 and 53 satisfy the conditions ($\sigma'_1$): $9 \cdot 18 = 2 \cdot 81$ and $2 + 81 < 100; 4 \cdot 49 = 7 \cdot 28$ and $7 + 28 < 100$.

So, there are 10 candidates left for further study: 11, 17, 23, 27, 29, 35, 37, 41, 47, 53, all of which have the property ($\sigma'_1$).

5. Then we know them too

29 is also not suitable, since, since $29 = 4 + 25 = 16 + 13$: if $P$ had $p_0 = 16 \cdot 13$, he would guess $k_0$ and $l_0$, since among the sum $2^{4-t} + 2^t \cdot 13$ only one is odd; if $P$ had $p_0 = 4 \cdot 25$, he would also guess $k_0$ and $l_0$: among the corresponding sums there are no
