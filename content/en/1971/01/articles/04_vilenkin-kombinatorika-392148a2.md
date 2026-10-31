---
id: 1971-1-vilenkin-kombinatorika-392148a2
issue: kvant_1971_1
year: 1971
number: "1"
title: Combinatorics
authors:
  - Виленкин Н. Я.
rubric: osnovnye-stati
page_first: 15
page_last: 20
page_labels: 13, 14, 15, 18
tag: RMT7
lang: en
source: kvant_digital
extraction: vision
content_sha256: ca2ccc73d8dfeb2fb66e4a23bb929b21e5ec0e7c7bf4e5d98a7e8d77283f897e
prompt_sha256: draft-1
translated_from: content/ru/1971/01/articles/04_vilenkin-kombinatorika-392148a2.md
source_content_sha256: ffa07a6cfcaad7123ade77cc474309bd65814a6ebeb40fc5c2340142047fe3b9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Probably every reader «Kvant» is familiar with the great excitement before a major sporting competition - be it the World Cup in football or the “match of the century” in chess. Further, from those who do not quite accurately remember the castling rules, you can hear thoughtful substitutions like “I would put Porttish, not Larsen, on the first board of the world team.” Chess experts and fans argue about the chances of victory between Smyslov and Keres, and football fans almost come to blows when discussing the possible outcome of the match between the national teams of Brazil and England.

Very often, before such competitions, newspapers announce a knowledge competition, offering to guess both the outcome of the competition as a whole (predict who will get the “Golden Goddess”, or the score with which the USSR chess team will defeat the world team), and the outcomes of individual compositions. At first glance, there is a very simple way to win such a competition: send as many letters to the editor as there are theoretically possible outcomes of the competition, and in each letter give one of the options. At least one letter will hit the target!

But the matter is not at all that simple - there are too many options. Of course, if you only need to predict the score with which the match of the century will end, then it is enough to send 81 letters: 40 games were played, and the USSR national team could score any number of points from 0 (brrr...) to 40 (that would be great!). But if you also need to indicate the outcome of the match on each board (at least predict who will win it), then the number of possible options grows κατάstrophically.

Problems in which it is necessary to find the number of possible options for a particular operation, a particular event, arise in a variety of areas of human activity. These problems are called combinatorics now in school and are not taught, it is studied as an elective).

1. Sum and product rules. The basis for solving combinatorial problems are two simple rules - the correct sum and the correct product.

Sum rule. If we have $m$ ways to choose element $a$ and (independently) $n$ ways to choose element $b$, then the choice “either $a$ or $b$” can be made in $m+n$ ways.

For example, if there are 5 apples and 9 pears on a plate, then the choice “apple or pear” can be made in 14 ways - choose either one of 5 apples or one of 9 pears.

The correct work is somewhat more difficult. It deals with the selection of a pair of elements $(a, b)^*$.

Product rule. If we have at our disposal $m$ ways to select element $a$ and $n$ ways to select element $b$, then the pair $(a,b)$ can be selected in $mn$ ways.

Thus, if there are 5 apples and 9 pears on a plate, then the pair (apple, pear) can be selected in $5\cdot 9=45$ ways.

*) Two pairs obtained from each other by rearranging elements are considered different, for example, the pair (1, 4) is considered not to coincide with the pair (4,1).

⟦folio 14⟧

To verify the validity of the product rule, we denote all ways of choosing the element $a$ by $a_1, \dots, a_m$, and all ways of choosing the element $b$ by $b_1, \dots, b_n$. Then all the pairs that can be made from these elements are arranged in the following table of $m$ rows and $n$ columns:

$$(a_1, b_1), \dots, (a_1, b_n),$$
$$(a_m, b_1), \dots, (a_m, b_n).$$

In this table there are just $mn$ pars.

Note that sometimes the choices are more complex - you must first select the element $a$, and then, depending on this choice, the element $b$. But if the element $a$ can be chosen in $m$ ways, and after each can be chosen in $n$ ways, then the number of distinct pairs $(a, b)$ is again $mn$. Prove it yourself.

Of course, it may be that we need to make not two, but several choices. In this case, you need to run through the number of options for each choice. In other words, it follows the rules correctly.

If the element $a_1$ can be chosen in $n_1$ ways, the element $a_2$ in $n_2$ ways, the element $a_k$ in $n_k$ ways, then the set $(a_1, \dots, a_k)$ can be chosen in $n_1 \dots n_k$ ways (in this case, sets that are distinct from each other only by the order of the elements are considered different).

Now we can already solve the problem of the number of possible outcomes of the match of the century. Each board could have 3 outcomes: win, draw and defeat. Since the number of the board is 10, there could be $3^{10} = 59049$ different outcomes. And if you need to imagine not only the outcome of each winner, but also his score, then the answer will be $9^{10}$.

Using product rules, you can also solve quite complex problems in which additional conditions are imposed on the choice of options.

Example. There are 33 different letters in the Russian alphabet. How many words containing 5 letters can you form if you do not allow words in which two identical letters appear in a row?

Of course, “words” here have a different meaning than in philological terms - such “words” as abbed or ababa are allowed. But words like *quarrel*, *press*, *aachen* are not allowed - they contain two identical letters in a row.

To solve this example, we will select the letters one by one - first the first, then the second, the fourth, the fifth, and then choose in 33 ways - after all, we have at our disposal all 33 letters of the Russian alphabet. But the second letter can be chosen in only 32 ways - after all, it must be different from the first. You can choose the third letter in 32 ways - it must be different from the second; The fourth and fifth letters can also be chosen in 32 ways. And in total we get $33 \cdot 32 \cdot 32 \cdot 32 = 34603008$ different words that satisfy the given condition.

2. k-subsets. Using the sum and product rules, you can solve various combinatorics problems. But this is not always convenient, just as solving any geometric problem with axioms is not always convenient. Along with the axioms, we use the geometric theorem, which allows us to shorten the solution to the problem. In the same way, in combinatorics there are several simple, “standard” problems, to which it is often possible to reduce solutions to other problems.

These problems are formulated in the language of set theory. If the reader is not familiar with what a “set”, “element of a set”, “intersection of a set”, “union of a set” is, we refer him to the literature, a list of which is given at the end of the article. However, we will use only the simplest concepts of set theory, which will now be studied in the 4th and 5th grades of high school, and as an example we will take a set of four elements and select its subsets and words made up of the elements of this set (Fig. 1-5).

⟦folio 15⟧

Fig. 1. Let the set $N$ consist of four elements: knight, bishop, queen and rook.

Let's solve the following problem. 5 students take the swimming test. The test is passed if the student swims 100 meters (any time). If the student comes to catch him, then the test is not passed. In how many ways can a swim end?

Various cases are possible. It may be assumed that all students will be good swimmers, or it may be that all five will have to be rescued. The total number of outcomes can be calculated like this. Let's arrange all the students in some order, say alphabetically: Andreev, Borisov, Voldin, Grigoriev, Dmitriev. For each of them there are two possibilities - either he passes the test or he doesn’t. In the first case, we will assign the number 1 to this student, and in the second case, the number 0. Then the outcome of the game will be expressed as a sequence of length 5 from zeros and ones. For example, the sequence 0, 1, 1, 0, 1 means that only Borisov, Voldin and Dmitriev swim well enough. And if only Grigoriev takes the test, then the report on the outcome of the competition will look like this: 0, 0, 0, 1, 0. The sequence 0, 0, 0, 0 means that not a single student reached the finish line.

Thus, the problem of the number of outcomes of a game has been reduced to the following: how many sequences of length 5 can be counted from the numbers 0 and 1? The answer to this problem is given by the correct product: since at each place in the sequence we have a choice of two possibilities, then the total number of outcomes is $2 \cdot 2 \cdot 2 \cdot 2 = 32$. So, there are 32 possible outcomes of the swim.

In the analyzed problem, we needed to find out how many subsets can be counted from the set $N$: {Andreev, Borisov, Voldin, Grigoriev, Dmitriev}.

In this case, an empty subset was allowed, as well as a subset coinciding with the entire set $N$. The answer turned out to be $32 = 2^5$. In the same way it is proved that if a set $N$ contains $n$ elements, then it has $2^n$ subsets. The same result can be proven using mathematical induction.

In the Olympic Games they do it this way: the top two qualify for the finals. Let's find out how many outcomes the competition can have in this case. Mathematically, the problem is formulated as follows: in how many ways can you select 2 elements from a set containing 5 elements? It is easy to check that this can be done in 10 ways (write down all these methods yourself). But this “direct search” method is only suitable for a small number of participants. I would like to have a formula that allows me to immediately answer the question. So, we need to solve the following problem.

How many $k$-subsets are there in the set $N$ of $n$ elements?

Here we say "$k$-subset" together with "a subset containing $k$ elements" for brevity.

The choice of a subset from a given set $N$ can be found in the following way. Let's put the elements of the set $N$ into a bag, and then put our hand into this bag and pull out a subset. Of course, all $k$ elements of the subset are pulled out at once and no reasonable order can be established for them.

⟦folio 18⟧

Fig. 5. There are $P_4=4!=24$ permutations of elements of the set $N$.

It is necessary to pull out from it one by one the elements of this set. But this time we will not return these elements to the bag, but will place them in a row. After $k$ selections we will again have the $k$-word $(a_1, \dots, a_n)$, but this time there are no duplicates among the elements $a_1, \dots, a_n$ *). In another way, we can say that $k$-words without repetitions are ordered $k$-subsets of the set $N$.

The number of $k$-words without repetitions of $n$ elements is denoted by $A_n^k$. It immediately follows from the product rule that

$$A_n^k=n(n-1)\dots(n-k+1).$$

In fact, the first element can be selected in $n$ ways, the second - only in $n-1$ ways, because you cannot take an already selected element. The third element can be selected in $n-2$ ways, ..., $k-1-(n-k+1)$ ways.

*) Such $k$-words are called placements without repetitions.

This means that the total number of real ways is expressed by formula (3).

For example, if out of 10 commission members it is necessary to appoint a representative, his substitute and a secretary, then this can be done in $10\cdot 9\cdot 8\cdot 720$ ways.

5. Rearrangements. If the elements of the set $N$ are pulled out from the bag and laid out in a row one after another (and not a single element is returned back), then in the end all the elements of the set $N$ turn out to be located in some order. In this case we speak of permutations without repetitions of $n$ elements. Thus, a permutation of $n$ elements is a $k$-word without repetitions of $n$ elements. Polyag in formula (3) $k=n$, we find that the number of permutations of $n$ elements is $n!$. It is represented by the symbol $P_n$. So,

$$P_n=n!$$

6. Permutations with repetitions. We already know that from $n$ “letters” we can
