---
id: 1979-12-tsalenko-kombinatornyie-zadachi-informatsionnogo-poiska-e4f63efb
issue: kvant_1979_12
year: 1979
number: "12"
title: Combinatorial problems of information retrieval
authors:
  - Цаленко М. Ш.
rubric: osnovnye-stati
page_first: 8
page_last: 14
page_labels: 6-12
tag: MD59
lang: en
source: kvant_digital
extraction: vision
content_sha256: e4e63e84feebee927b3986df422d77eaacec85e3f8869caf38e8ffe7f2045278
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/06_tsalenko-kombinatornyie-zadachi-informatsionnogo-poiska-e4f63efb.md
source_content_sha256: 12d604c92f15ac84ccee7c48c2adb69e79db730b6515e8b9479803bf1b1d3634
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 6⟧

M. Tsalenko

Combinatorial problems of information retrieval

The scientific and technological revolution currently taking place in industrialized countries is closely related to the emergence and development of electronic computers (computers). Modern computers can perform millions of arithmetic operations per second. However, computers are also invading areas of human activity in which there are no large and complex calculations and which would be far from mathematics. Library science provides an instructive example. Currently, it is explained why computers began to be widely used in libraries and what interesting and difficult mathematical problems arise in this case.

1. What is information retrieval?

Large modern libraries house millions of books, magazines, newspapers and other printed materials. In order not to get confused in this huge collection of literature, library staff create a reference system from catalogs with annotated cards.

Telery imagines a reader who has come to the library to read some popular book about solving equations in radicals. He may know that many mathematicians have worked on this difficult problem and that its solution is associated with the names of Abel and Galois, but his mathematical education is not sufficient to read special

⟦folio 7⟧

literature. Thus, the appearance of our reader in the library leads to the so-called information request: “FIND POPULAR LITERATURE ABOUT SOLVING EQUATIONS IN RADICALAX,” and before the reader satisfies his curiosity, he must solve the problem of information search: among all the books stored in the library, find the one that will most satisfy him. This is where the catalog system comes to his aid. In the thematic catalog he will find a section containing a list of books on mathematics, and inside it - a part containing a list of books on algebra. And among the catalog cards of this part, you need to select those that indicate the literature you are looking for.

Now let's do some simple calculations. Let’s assume that it takes an average of only 20 seconds to familiarize yourself with the card. This means that the reader works very quickly: it is estimated that it takes about 10 seconds to perform one arithmetic operation. If a reader has to look through 200 cards, he will spend about 67 minutes just selecting the literature that interests him. This turnover is an involuntary part of the general process of searching for information of interest to readers. The process itself is called information retrieval; The calculation shows that when searching for information using catalogs, a significant part of the time is spent unproductively. Since readers of the largest libraries visit hundreds of cities in one day, and their information requests can be more complex than in the example above, involuntary time spent during information search is expressed in hundreds and thousands of hours.

To illustrate the complexity of information retrieval, let us give one more figure. There are now over 750 magazines and other periodicals all over the world devoted solely to computer technology. This means that during the year ten thousand articles are published in various languages, occupying hundreds of thousands of printed pages, which relate to only one area of ​​​​human activity. However, this area is suitable for specialists of various specialties: engineers, physicists, chemists, mathematicians, sociologists, philosophers and many others. It is very difficult to understand the growing flow of literature, find the necessary information, use it in your work and not repeat already completed work. The catalog system turns out to be insufficient, and special information institutes are being created in many countries around the world.

2. Computers and information retrieval

A remarkable feature of a computer is its ability to “read” and compare words, to determine whether they are the same or different. The fact is that to write any word in the Russian language you need to be able to form only 33 letters. On the other hand, computers can easily recognize sequences of ones and zeros. Let us consider, as is customary in many modern computers, all sequences of ones and zeros that have exactly the same number of terms in all of them. For example, this will also include the sequences:

00000000, 01010101, 11110000
(for brevity, no comma is placed between members of the sequences).

Since each sequence has exactly eight terms, and any term is zero or one, the total number of sequences considered is 2⁸=256. Let us agree to write together the first letters a, b, c, 2, d, e of the Russian alphabet according to the sequence:

10000000, 11000000, 11100000, 11110000, 10100000, 10010000

We emphasize that we consider each sequence as one, not eight characters. Now, with the help of new symbols, you can write words in such a way that they can be

⟦folio 8⟧

"recognize" the computer. For example, the word
the problem will look like this:
1100000 10010000 10100000 10000000

Of course, this method of recording is inconvenient for humans, but it allows the computer to “read”. At the same time, the machine can read texts in many languages, since it can remember 256 sequences not only of Russian letters, but also numbers, Latin letters and many special characters, for example, arithmetic symbols.

Having taught a person to read, a machine immediately overtakes him in reading speed: if a person needs 67 minutes to read 200 index cards, then a computer copes with this work in a few seconds. When reading, the machine can compare two texts, determine the presence of common words or expressions in them, determine the meaning of individual words, etc.

However, natural languages ​​(Russian, English, German or any other) are very difficult for a machine to “understand”: every thought in them can be expressed in many ways. Therefore, linguistics is developing artificial languages, called information-search languages, which are free from this drawback.

The main part of the information of search languages ​​is a set of concepts, terms, phrases that are constantly used in a specific subject area - in mathematics, chemistry, biology, etc. When compiling an abstract of a book or an abstract of a scientific article, it is possible, together with the proposed natural language, to give a list of those terms that most reflect the content of the book or article. The same can be done with information requests from readers. For example, in the series “Popular Lectures on Mathematics” a brochure by A. G. Kurosh “Algebraic Equations of Higher Degrees” was published. Its abstract could be written as follows:

Complex numbers, solution in radials to equations of the second and third degree, Abe's theorem

on the unsolvability in radials of the general equation of the straight line, approximation, calculation of roots, group, stake, field.

An abstract of the article by B. N. Delaunay “Algebra (theory of algebraic equations)”, placed in the first volume of the collective three-volume work “Matematika, its content, methods and significance”, may look like this:

Solution in radials of the equation of lower ranks, Cardnot's formula, Abey's theorem on the unsolvability in radials of the general equation of the straight line, Galois's theorem, location of the roots of the equation on the complex plane, fundamental theorem of algebra, approximation, calculation of roots.

Let us now remember the reader who wanted to receive literature on solving the equation in radials. His request can be described as follows:

Solution in radials of the equation of lower stellations, Abey's theorem on the unsolvability in radials of the general equation of the straight stellium.

Comparing the query with the two annotations above shows that almost all phrases encountered in it are included in the annotations. Therefore, with a high probability it can be suggested that the brochure of A. G. Kurosh and the articles of B. N. Delaunay contain information that interests the reader.

Now it becomes clear what part of the information search can be transferred to a computer: the machine must check whether the terms and phrases of the query are contained in the annotations of a book or article stored in the library. Terms, concepts, and phrases in the information search are called keywords.

3. Computers must be used effectively

Now let's take a closer look at performing operations on a computer. Every modern computing machine has four chapters

⟦folio 9⟧

nary components: central processor, RAM, external memory and input/output device. The central processor controls the operation of the entire system, and arithmetic and logical operations are performed in it, and a single operation takes millionths of a second. The data (numbers, words) from which the processor operates is located in RAM. It has a relatively small volume because its cost is very high.

Let us remind you that writing a single character (letters, numbers, special sign algorithms) requires an eightfold sequence of ones and zeros. In the RAM of perfect computers, it is usually possible to record 256,000 or 512,000 such sequences, or characters. Is it a lot or a little? As practice shows, a bibliographic card along with an annotation contains 1000-1500 characters. Therefore, at best, about 500 cards can be stored in RAM. It is clear that this is very little.

The remaining cards are placed in external memory, the volume of which is hundreds of times greater than the amount of RAM. However, data transfer takes a thousand times longer than the work of the central processor, which failed during the transfer to the teenager. It is clear that the transfer of data has no direct relation to information consumption and is an unidentifiable waste of time. Thus, the problem arises of reducing the number of accesses to external memory. There are different approaches to solving it. However, one of them leads to a red and difficult mathematical problem, which will be discussed in conclusion.

4. How to reduce the “weight” of many words?

Let $A$ be some set of $n$ elements. The elements will be denoted by small Latin letters $a, b, c, \dots$. We will call an arbitrary subset of elements from $A$ a “word” and together with the traditional notation $\{a, b, c, d\}$ we will write a simple $abcd$; placed, with equal success you can write $bdac$ or $dcab$, etc. A word that has no letters, i.e. an empty word, will not be considered. Therefore there are only $2^n - 1$ words.

To connect with previous considerations, we point out that we began to use letters to denote the key words of the information-Japanese language, i.e. terms, concepts, phrases. Their number can be very large, for example on the order of 10,000. The set of keywords can be an abstract or an information request.

Suppose that a certain set of words $M$ is located in external memory $EBM$ and that it is necessary to find all words from $M$ in which the letters $a, b$ and $c$ occur. To cope with this task, you need to “read” all the words from $M$ one by one, having first copied them into RAM. If $M$ is unknown, then the entire set $M$ can be moved there at once. In the general case, such movement is carried out in portions, the size of which is predetermined. Therefore, the number of calls of size $M$ and the size of the transmitted portion. This number could be reduced if words with letters $a, b$ and $c$ were written separately when placing words into external memory. However, for the task: find all words with the letters $b, c$ and $d$ - continued work is useless.

Nevertheless, pre-sorting words when writing them to external memory turns out to be useful if you have in mind not a single query, but all possible queries. We will divide the volume of the set $M$ into parts and place each part in a separate envelope, and on the envelope we will list all the letters found in the positions in the words in the envelope. Now, when searching for words with the letters $a, b$ and $c$, the envelopes on which these letters were written began to be consulted, and then the words from these envelopes were read. Words on envelopes should be placed in such a way that the total number of “opened” envelopes for

⟦folio 10⟧

of all possible queries turned out to be the simplest example. Let the set $M$ consist of only three words $ab, ac$ and $bc$, and the queries we will make must be non-empty subsets of the set $\{a, b, c\}$. then the total number of requests is seven. Let's first put each word in a separate envelope. Then the envelope with the word $ab$ will open three times: when searching for words $a$, words $c$ and words $a$ and $b$. Since all the envelopes are equal, the total number opened is 9. Now let's put the words $ab$ and $ac$ in one envelope, and the word $bc$ in the other. In this case, the first envelope is opened seven times, and the second is still opened three times, and the total number opened is 10.

Finally, let's put all the words in one envelope. Then the total number opened is 7: for each request you need to open an envelope, and there are 7 requests in total. Thus, in our example, it is best to keep $M$ in one envelope. (Would the result change if the words $a$ and $abc$ were added to $M$ or the words $bc$ were removed from $M$?)

We are now ready to consider the general problem. Let $M$ be an arbitrary set of words. The number $k$ of different letters appearing in words from $M$ is called the set level $M$ and is denoted $l(M)$. For example, if

$$M = \{abc, bcd, cde, dea, eab\},$$

(1) then level $M$ is equal to 5.

The weight of the set $M$ is the number $2^l(M) - 1$. In the example above, all $M$ is equal to 31. Clearly, all $M$ is equal to the number of words that can be made from $l(M)$ letters.

The problem that arises when trying to reduce the number of accesses to external computer memory can be formed as follows: for any set of words $M$, specifying a method for partitioning it into such disjoint subsets $S_1, S_2, \dots, S_k$ that the sum of the weights

$$P = (2^l(S_1) - 1) + \dots + (2^l(S_k) - 1) = \sum_{i=1}^{k} (2^l(S_i) - 1)$$

is the smallest.

⟦folio 11⟧

different instances of the same minimal block. In the future, such blocks will have equal rights for us.

Let us now prove one of the theorems that gives an idea of ​​the structure of minimal blocks.

Theorem. Minimal blocks of level 5, consisting of three-letter words, are limited to the following list, up to letter replacement:

$$S_1 = \{abc, bcd, cde, dea, eab\};$$
$$S_2 = \{abc, abd, abe, acd, ace, ade\};$$
$$S_3 = \{abc, abd, abe, acd, ace, bde\}.$$

Proof. Each three-letter word has a weight of $2^3 - 1 = 7$. All of any set at level 5 is equal to 31. Therefore, any block at level 5 contains at least five words: otherwise the sum of the weights of individual words would be less than 31.

Further, in any block of level 5, each letter must appear at least three times. In fact, the empty letter $a$ appears less than three times. then all sets of words that do not contain $a$ do not exceed 15, and the sum of the weights of the words $a$ does not exceed 14. This means that the total sum of weights is less than 29, which contradicts the definition of a block.

Now let's look at two cases.

Case 1. The minimal block $S$ contains five words. Since the number of all letters in $S$ is 15, by virtue of the previous remark, each letter appears exactly three times. For clarity of calculations, let us introduce a square table of exchange $5 \times 5$, in the first column of which the letter $a$ will be written, in the second - $b$, etc. (see tables 1a-1b).

Suppose that a certain pair of letters, for example $a$ and $b$, occurs only once. Then the situation arises, depicted in table 1a. Let us denote by $c$ the letter that is included in the first word. This letter must meet $a$ and $b$ one more time: if it met $a$ two more times, then the last two rows of the table would contain the same word, which is impossible. Therefore, from table 1a we move to table 16.

It is clear that the words ade and bde need to be placed in the third and fifth rows of the table. But then you should put $d$ (or $e$) in the second line, and $e$ (or $d$) in the fourth line; due to the symmetry between $a$ and $b$ on table 16, both possibilities are equal. Table 1c provides a candidate for the minimum block. The constructed set of words $S$ is a real minimal block, since any subset of three words has a weight of 31. It becomes $S_1$ if $d$ is replaced by $e$, $e$ by $a$ and $a$ by $d$.

No pair of letters can appear three times, since there are not enough letters for the fifth word; Therefore, we can only assume that each pair of letters will appear twice. However, this option is also impossible: the letters $a$, $b$ and $c$ can only be placed as shown in Table 2, and there are not enough letters for the last word.

Case 2. The minimum block $S$ contains six words. Then in words

Table 2.

⟦folio 12⟧

There are only 18 letters from $S$. The number 18 can be represented in the following ways as the sum of five terms, each of which is equal to 3, 4, 5 or 6:
a) $18=6+3+3+3+3$;
b) $18=5+4+3+3+3$;
c) $18=4+4+4+3+3$.

In method a) one letter, for example $a$, will appear six times. Therefore $S$ is the same as $S_2$; We assume that the reader can independently prove that $S_2$ is a minimal block.

Let's move on to method 6). For definiteness, let the path encounter the letter $a$ once, and the letter $b$ four times. then we immediately get table 3a. In lines four and five, one of the letters: $c$, $d$ or $e$ appears twice; let's denote it by $c$. The sixth line can only contain the word $bde$, and as a result we arrive at table 36.

Table 3a. Table 36.

To prove that the constructed set of words $S_3$ is a block, it is enough to note that in $S$ any subset of level 4 contains no more than three words, and the remaining words form a subset of level 5 and therefore the sum of the weights cannot be less than $36=15+7\times 3$, and the weight of $S$ is equal to 31. Minimality follows from the fact that, no matter which word is removed, the remaining words contain a letter $a$ will occur at least four times, which cannot happen in Level 5 blocks of fifth words due to the first case.

Let's move on to method b). Let the letters $a$, $b$ and $c$ appear four times each. then either some pair of these letters will appear three times, or any pair will appear exactly twice. In accordance with this, we come to tables 4a and 46 (up to the change of letters).

The first construction of the set is a block, but a non-minimal one: after removing the word $abc$ from it, you get a block of type $S_1$. The second set is not a block at all, since it is the union of its level 4 subsets {abd, acd, bcd} and {abe, ace, bce}, and for this partition the sum of the weights is $30<31$.

Now it remains to prove that there are no other minimal blocks of level 5 consisting of three letter words. If the set $S$ contains nine or ten words, then at least one letter will appear six times, and therefore $S$ contains a block of type $S_2$. This means that $S$ is always the minimum block.

If there are seven or eight words in $S$ and not a single letter appears six times, then there will always be a pair of letters, say $a$ and $b$, such that $a$ will appear five times, $b$ at least four times, and the pair $a$, $b$ will appear three times (check!). Therefore, consider (make sure of this!) that $S$ includes the following five words: $abc$, $abd$, $abe$, $acd$, $ace$. To them you must add at least two words from the following four: $bcd$, $bce$, $bde$, $cde$. If one of the words $bde$ or $cde$ is added, then $S$ will contain a minimal block of type $S_3$. If the words $bcd$ and $bce$ are added, then the words from $S$ will not contain the pair of letters $d$ and $e$, which cannot be in the block (see problem 3 below).

Task 1.
1. Describe all the minimum blocks of level 5 using two letter words.
2. The set $S'$ is obtained from the set $S$ by adding the newest letter to them. Prove that if $S$ is a minimal block, then $S'$ is a minimal block.
3. If the words of block $S$ contain the letters $a$ and $b$, then in $S$ there is a word containing $a$ and $b$.

4.**. Describe all the minimum blocks of levels 6 and 7 from three letter words.
5*. Prove that there are no level 8 blocks of three letter words.
