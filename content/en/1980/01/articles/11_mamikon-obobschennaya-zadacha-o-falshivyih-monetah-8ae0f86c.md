---
id: 1980-1-mamikon-obobschennaya-zadacha-o-falshivyih-monetah-8ae0f86c
issue: kvant_1980_1
year: 1980
number: "1"
title: Generalized counterfeit coin problem
authors:
  - Мамикон М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 31
page_labels: 27-29
tag: VL1B
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4d01c7b424c6fad3712016ba8a08e49a6334f95bd3ba1b6d65bcc2f75b5286e1
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/11_mamikon-obobschennaya-zadacha-o-falshivyih-monetah-8ae0f86c.md
source_content_sha256: 78cd4539c8b1737a14fa9ae97bcd2e37926da8155f4bf679adf87465add3ecf2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

M. Mamikon

Generalized counterfeit coin problem

Many readers are well aware of the following classic counterfeit coin problem, which has the advantage of being solvable:

Bag of Counterfeit Coins Problem

There are N bags and each of them contains a sufficient number of coins. All bags, except one, contain the same “normal” coins, while in one bag all the coins are fake. All normal coins are known and it is known that a counterfeit 1 gram coin is easily normal. It is required to detect a bag of counterfeit coins using one weighing on a scale with weights.

Here's how to solve this problem. The bags are numbered sequentially and from each bag a number of coins is taken equal to the number of this bag. The total weight of all coins taken in this way will “fall short” of the weight of the same number of normal coins (which we know) by the number of grams equal to the number of the exact bag that contains counterfeit coins*).

While tinkering with this problem, I came to the more surprising conclusion that one weighting could solve a more complex problem:

*) This problem can be solved - albeit more cunningly - in the case when all the normal coins are unknown and there are no different weights. Think how.

⟦folio 28⟧

Several bags of counterfeit coins problem

Suppose that in the conditions of the previous problem there is not one, but several bags of counterfeit coins, and their number is unknown. It is required to detect all these bags using one Vanya suspension on scales with weights.

Having solved this problem, I dared to make further conditions. The problem turned out to be solvable under even more surprising conditions:

The sack problem
with heavy and light coins
Among the N bags there are a small (unknown) number of bags with heavy coins and a small number (the same unknown) number of bags with light coins. A line coin is 1 glacier than normal, and a heavy one, on the contrary, is 1 glacier than normal. It is required, using one weighing of coins on scales with weights, to find out which bags contain normal coins, which are heavy, and which are light. (Recall that inside a given bag all the coins are of the same weight and that all normal coins are known.)

The solvability of this problem also inspired me to further generalization, which was already heading by itself. So far we have actually considered problems about two or three grades (types) of coins, so it naturally follows

The sack problem
with difference coins

Let there be N bags and each one contains enough coins. There are different types of coins, but each bag contains only one type of coins. The number of bags of coins of this type is arbitrary, and we do not know it. Coins of different grades differ from each other in weight, and by an integer number of grams. All coins of each grade are modified. It is required with the help of one suspension of vanya on scales with a

Using the scales, determine what grade the coins in each bag belong to.

We invite the reader to try an independent solution to the previous problem before moving on to the solution to the generalized problem of counterfeit coins presented below.

Solving the bag problem
with difference coins

We number the bags sequentially from 0 to N—1. Let us denote all the lightest coins by m. Let the bag number j contain coins of weight m+Δj, that is, Δj determines the type of coin in the j-th bag. Let, depending on the type of coin, the values ​​Δ can take (integer) values ​​0, 1, 2,..., less than k, that is, no number of types of coins are equal to k.

Now let’s take from the bag with number j a number of coins equal to kj, that is, from the first bag - one coin, from the second - k,..., from the last - kN−1 coins. There will be a total of coins taken

$$M = \sum_{j=0}^{N-1} k^j = 1 + k + k^2 + \dots + k^{N-1} = \frac{k^N - 1}{k - 1}.$$

Their total weight S on the scales will be equal to

$$S = \sum_{j=0}^{N-1} (m + \Delta_j) k_j = m \sum_{j=0}^{N-1} k^j + \sum_{j=0}^{N-1} \Delta_j k^j = m \cdot M + \sum_{j=0}^{N-1} \Delta_j k^j.$$

Since Δj < k is always, the second sum on the right side

$$\Delta = \sum_{j=0}^{N-1} \Delta_j k^j = \Delta_0 + \Delta_1 k + \Delta_2 k^2 + \dots + \Delta_{N-1} k^N - 1$$

represents the conversion of the number Δ from the decimal number system (in which the scale operates) into a number system with a base equal to k. In this system, Δ is written as a number with the following sequence:

⟦folio 29⟧

value of numbers:
$$\Delta \rightarrow \Delta_{N-1} \Delta_{N-2} \dots \Delta_{2} \Delta_{1} \Delta_{0}.$$

We see that each digit of this entry shows the grade of the coin in the sequence of bags, taken in reverse order. This state is the essence of our decision.

So, from the total weight S of all selected M coins, we subtract the values ​​Mm - the weight of the same number of coins of the lightest grade and the remaining number $\Delta = S - Mm$ is transferred to the number system with the base $k$ (we expand it into powers $k$, starting from the beginning). Then we get a number of the form (*). Its $j$th digit from the end (counting from zero) shows the grade of the $\Delta_j$ coin in the bag numbered $j$.

Example

The table below shows the weights of the coins contained in the five bags. At the top, the bags are numbered from right to left (this is the reverse order), and below the bags are the types of coins. They are what we are looking for.

| bag number $j$ | 4 | 3 | 2 | 1 | 0 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $11\text{ r}$ | $12\text{ r}$ | $10\text{ r}$ | $12\text{ r}$ | $10\text{ r}$ | $10\text{ r}$ |
| $1$ | $2$ | $0$ | $2$ | $0$ | $0$ |
| $81$ | $27$ | $9$ | $3$ | $1$ | $1$ |

In this case, $k=3$ and the number of coins taken corresponds to the degrees, as shown in the last row of the table. We all took $M=121$ coin. Their total weight on the scales will be equal to $S=1351$ g. Subtracting the values ​​of $M \cdot m=121 \cdot 10$, we obtain $\Delta=141$ g. Converting $\Delta$ to the ternary system
$$\Delta = 1 \cdot 3^4 + 2 \cdot 3^3 + 0 \cdot 3^2 + 2 \cdot 3^1 + +0 \cdot 3^2,$$
we obtain the number $\overline{12020}$, the sequence of digits of which coincides with the original sequence of varieties given in the table.

If $k=10$, then there is no need to transfer $\Delta$ from one number system to another. For case $k=3$ there are several differences from our interpretation of the solution to the problem. We leave it to the reader to find it.

A little history

The classic problem of one bag of counterfeit coins can be found in many popular mathematics books. It is said that during the Second World War, the British “dropped” this problem on German soldiers in order to deorganize them and that they lost more than 40,000 man-hours trying to solve it.

The book by D. Bizam and J. Herceg “Multi-world logic” (M., “Mir”, 1978) also considers the case of two bags of counterfeit coins and provides a solution to this problem using two weighings.

The classic counterfeit coin problem has recently found application in coding and information theory to detect errors in code.
