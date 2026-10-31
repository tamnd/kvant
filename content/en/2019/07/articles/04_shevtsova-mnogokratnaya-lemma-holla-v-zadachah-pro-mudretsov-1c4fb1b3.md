---
id: 2019-7-shevtsova-mnogokratnaya-lemma-holla-v-zadachah-pro-mudretsov-1c4fb1b3
issue: kvant_2019_7
year: 2019
number: "7"
title: Multiple Hall Lemma in Sage Problems
authors:
  - Шевцова М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 33
page_labels: 28, 30, 31
tag: TJ4H
lang: en
source: kvant_digital
extraction: native
content_sha256: 2938b434b718124e7032f5a347144fefc07ba8a43aa3d77a6bd740e5c3f31d1d
prompt_sha256: draft-1
translated_from: content/ru/2019/07/articles/04_shevtsova-mnogokratnaya-lemma-holla-v-zadachah-pro-mudretsov-1c4fb1b3.md
source_content_sha256: 2c70edc58a314a5e86ebcb3aba5c85b79fe619a557755fec675d4aa21f5c9f26
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

Multiple Hall Lemma in Sage Problems

M.SHEVTSOVA

Introduction

Problems involving cooperative algorithms (in other words, sage problems) are traditionally considered quite difficult. The fact is that it is often very difficult to come up with an appropriate strategy of action that guarantees success for the sages (for example, when guessing the colors of the caps they are wearing); There are no general considerations that allow us to build the necessary strategies. Of course, there are standard ideas for numbering, encoding, etc., but how exactly to number, encode and thereby convey the necessary information has to be invented anew each time. In this article we will talk about an interesting approach to such problems, in which there is no need to come up with such action strategies. It seems incredible, but there is a way to prove the existence of a strategy without explicitly presenting it! The same ideas apply to problems about magicians: you can prove that a trick is possible without revealing how it is performed! We'll learn how to do this by looking at a classic combinatorial result: Hall's lemma.

Ordinary and multiple Hall lemmas

Let's start with the formulation of the classical Hall lemma. Let's imagine that boys and girls came to dance in the evening. Some of the boys and girls know each other. As often happens, every young man wants to dance only with someone he knows.

DOI: https://doi.org/10.4213/kvant20190705

⟦column⟧

him a girl. The question is, will all the boys be able to invite the girls they know to dance? It turns out that there is a simple necessary and sufficient condition, under which every boy will find a partner (although, perhaps, some girls will be left without a partner). This is the essence of Hall's lemma. Theorem 1. Hall Lemma. Consider a bipartite graph, where the vertices of the first part are boys, and the vertices of the second part are girls. Let's connect a boy and a girl with an edge if they know each other. Let us assume that any k boys know at least k girls, for any k from 1 to the total number of boys. Then all the boys will be able to invite girls they know to the dance. There are many different ways to prove Hall's lemma. We will present a classical proof, which is also called the alternating chain method. Other proofs can be found in article [1]. Proof. Let's assume the opposite: let all the boys not be able to dance with the girls they know. Let's consider the largest number of dancing couples that can be formed. Next, let's look at a young man who is not included in these pairs. He begins to organize his secret society. On the first day, only he is in this society. Every next day, every young man who enters this society invites all the girls he knows there, and they bring their dance partners (if any) there.

Exercises

1. Prove that sooner or later a girl who has not had a partner will come into society. 2. Prove that in this case it is possible to divide the boys and girls into pairs so that the number of pairs increases. 3. Derive Hall's lemma from here.

The essence of Hall's lemma is to establish correspondences between two types of objects (boys and girls) when certain conditions of connection between these objects are met. There are not many statements like this in combinatorics, and Hall's lemma is perhaps the most powerful of them. To practice using it, try solving the following problems.

⟦folio 28⟧

KVAN T 2019/№7

Exercises

4. Each of two equal squares is divided into 100 equal parts. Prove that you can stack these squares and pierce them at 100 points so that each of the 100 parts of each square is pierced. 5. 7 squares were cut out of a chessboard. Prove that on the remaining squares you can place 8 rooks that do not attack each other. Note. Consider a bipartite graph whose vertices are the rows (first part) and columns (second part) of a given table.

In practice, we will use Hall's lemma in a very specific situation, corresponding to a so-called regular bipartite graph. Let us formulate a separate corresponding statement, which will be the key when solving problems with the sages. Theorem 2. Hall's lemma for a regular graph. Suppose that for some l > 0 each boy knows exactly l girls and each girl knows exactly l boys. Then all the boys will be able to invite girls they know to the dance. In terms of graphs, this statement sounds like this: if in a bipartite graph the degrees of all vertices are the same, then vertices from one part can be associated with exactly one adjacent vertex from another part. Proof. Let us consider arbitrary k boys and prove that they know at least k girls (in this case, our statement follows from Hall’s lemma). Suppose k boys know x girls. Let's count the number of edges coming from these k boys and the number of edges going into x girls they know. It is clear that there are no more ribs coming out of the boys than there are ribs going into the girls. Then kl d ​​xl, whence x t k, which is what needed to be proved.

Exercise 6. A private security company employs n security guards. Every day they need to be distributed across n objects. After k days, it turned out that no one was on duty at the same facility twice. Prove that it is possible to create a schedule for the remaining n – k days so that all guards are on duty once at all objects.

In the future, ideas related to the use of Hall's lemma for solving problems about magicians will be important to us. We will bring

⟦column⟧

We present only one problem on this topic, referring the interested reader to the article [2]. Problem 1 (All-Russian Olympiad in Mathematics, 2007). A magician and an assistant are about to perform such a trick. The spectator writes a sequence of N numbers on the board. The magician's assistant covers two adjacent numbers with a black circle. Then the magician enters. His task is to guess both closed numbers (and the order in which they are located). At what minimum N can the magician agree with his assistant so that the trick is guaranteed to be a success? Answer: 101. Solution. Before moving on to the solution, let's try to understand how we can formalize the magician's guessing of the initial arrangement of numbers. We have a set of initial sets of N digits. One of these sets is written by the spectator and the magician must guess it. These sets will constitute the first share in our bipartite graph. The magician himself sees only part of this set with two numbers hidden by the assistant. These sets will make up the vertices of the second part of the bipartite graph. This simple consideration, which allows us to introduce a bipartite graph into our problem, suggests an estimate for the number N. Consider all the vertices of the second part. There are exactly N 1 $10^{N} 2$ of these vertices. On the other hand, there are exactly $10^{N}$ vertices in the first beat. It is clear that if there are fewer vertices in the second part than in the first, then the trick will fail. Indeed, in this case there will be two starting sets of N numbers, which after closing the numbers will give the same set that the magician will see, so he will not be able to guess the desired set. From here we get the restriction on N:

N 1 $10^{N} 2 t 10^{N}$, from which N t 101. It remains to give an algorithm for the magician’s actions so that he can guess the closed numbers in a sequence of length $N_{0} 101$. This is where we apply Hall's lemma. What do we need to do? We have the vertices of the second beat, which the magician sees, and the vertices of the first beat, which the spectator wishes for. We need to establish a bijection, i.e.

⟦folio 30⟧

KVAN T 2019/№7

Theorem 4. Multiple Hall lemma in the regular case. Consider a bipartite graph, where the vertices of the first part are boys, and the vertices of the second part are girls. Let's connect a boy and a girl with an edge if they know each other. Let us assume that the degrees of all vertices corresponding to boys are the same and equal to m and the degrees of all vertices corresponding to girls are also the same and equal to d. Prove that every boy can dance with ª m º « ¬ d » ¼ girls he knows, and each girl will dance no more than once.

Exercise 7. Prove this theorem.

Sages and Hall's multiple lemma

So, we have found out how to prove the possibility of performing tricks using Hall's lemma: the key consideration is the possibility of establishing an injection between the set of starting states that the magician sees and the set of final (thought by the viewer) states that need to be guessed. An injection is a correspondence such that different starting states are associated with different final states. However, in problems with sages and cooperative strategies the situation is more complicated. Firstly, in the vast majority of such problems, wise men can (and should) make mistakes, i.e. There is simply no such thing as an infallible guess. Secondly, the possibility of errors makes the decoding process ambiguous. In other words, the final situation that can be obtained from the starting one is not unambiguous. But we have Hall’s multiple lemma for just such a case! The key consideration for making Hall's multiple lemma work in sage problems is the following. Suppose that the wise men are given caps of different colors and they need to guess the color of their cap, seeing only the caps of other wise men in front of them. Let's number the wise men and put caps on them in every possible way. Let's arm ourselves with a camera and start photographing them. We will take a photo of each situation from above so that there are

⟦column⟧

all the hats are visible, and then we will give the camera to each of the wise men so that he himself can take photographs of all the other wise men whom he sees from his place. Let's consider a bipartite graph in which the vertices of the first part are all the photographs taken by us (in fact, just all possible initial arrangements of caps on the sages), and the second part is all the photographs taken by all the sages. Next, we connect vertex v from the second part with vertex u from the first if photograph v was taken by one of the wise men in situation u. What should wise men do? For every photograph he takes, the sage must try to restore the color of his cap. Of course, in some cases the wise will be wrong. We need to find those wise men who are guaranteed to answer correctly. More precisely, the answers of all the wise men should be evenly distributed across the photographs u, so that each photograph has a sufficient number of correct answers. To do this, we use Hall's multiple lemma. Sages whose points of view are chosen according to a given general photograph u will answer on the assumption that they are in this situation, and therefore correct. Thus, if each photograph u is associated with at least m photographs $u_{1},......, u_{m}$ taken by sages, then in each situation at least m sages will answer correctly. We will determine the number m from the parameters of the problem. Let's see how this scheme works in practice. Problem 2 (Moscow Mathematical Olympiad, 2010). A team of n wise men participates in the game: each of them is put on a hat of one of k colors known in advance, and then, when the whistle blows, all wise men simultaneously choose one scarf for themselves. A team receives as many points as how many of its participants have the same color of hat as their scarf (there are a sufficient number of scarves and hats of any color; during the game, each participant does not see his own hat, but sees the hats of everyone else, but has no right to give out any information before the whistle). What is the greatest number of points the team has planned in advance?

⟦folio 31⟧

MATHEMATICAL

tive plan of action for each of its members, can it be guaranteed to receive? Answer: > n k @. Solution. Consider the graph described above, in which the vertices of the first part are all possible starting positions of the team of wise men (i.e., all possible options for putting k-colored hats on them), and the vertices of the second part are photographs taken by each of the wise men in each possible starting situation. It is clear that in the first part there are $k^{n}$, and in the second there are $nk^{n} 1$ vertices. Each vertex from the first part is connected to n vertices from the second part, since each of the n wise men can see such a seating arrangement. On the other hand, each vertex from the second part is connected to k vertices from the first part, since each sage has k color options for his scarf. Now let's build an algorithm of actions for the wise men, in which they are guaranteed to score > n k @ points. To do this, it is enough to prove that it is possible to associate to each vertex from the first part > n k @ vertices from the second part. Let us use Hall's multiple lemma in the regular case. Let us apply this lemma by assigning to each initial arrangement u sages from the first part m > n k @ vertices from the second part. It is these sages who will answer correctly in the initial arrangement of u. Thus, sages can be guaranteed to score > n k @ points. It remains to prove that more > n k @ points cannot be guaranteed. In fact, this is also explained by the possibility of applying Hall's lemma: if it were possible to associate to each vertex of the first part more > n k @ vertices from the second part, then we simply would not have enough vertices in the second part. Formally, this can be proven as follows. Let's assume that there is a strategy for the sages that guarantees at least > n k @ 1 points. Note that the answer of each sage is uniquely determined by the color of the hats of the other sages. Let's match each photograph from the first part with the point of view of the wise men who answer correctly in this situation. If for each coloring there are more of them > n k @, then

$nk^{n} 1 t k^{n} > n k$ @ 1! $k^{n} > n k$ @ $nk^{n} 1$ is a contradiction. Thus, the maximum

CIRCLE

The total number of points scored by the sages is > n k @.

⟦column⟧

There is a class of problems about sages, where you need to find the highest probability of being guaranteed to guess the color of your cap. Consider, for example, the following modifications of the previous problem.

Exercises

8. In the conditions of the previous problem, we will assume that n < k. What is the maximum probability with which at least one of the wise men will guess the color of his hat? 9. This time the wise men write the expected color of their cap r times, but they do not see what their neighbors wrote. What is the maximum probability that at least one of them will guess correctly in these r attempts that the sages can guarantee?

Problem 3 (Leonard Euler Olympiad, 2013). 99 wise men sat down at a round table. They know that fifty of them put on caps of one of two colors, and the forty-nine others – another (but it is not known in advance which of the two colors there are 50 caps, and which – 49). Each of the sages sees the colors of all caps except his own. All wise men must simultaneously write (each on their own piece of paper) the color of their cap. Will the wise men be able to agree in advance to answer so that at least 74 of them give the correct answers? Answer: yes. Solution. It is clear that if a sage sees 50 caps of the same color, then he has a cap of a different color from the one of which there are 50, i.e. he knows his cap. This means that 49 wise men know the color of their cap and will answer correctly. The remaining 50 wise men, who see 49 caps of one color and 49 of another, will be called unlucky. Let's ensure that 25 of the unlucky wise men guess the cap correctly every time. Consider the graph described above, in which the vertices of the first part are all possible positions of the team of wise men, and the vertices of the second part are photographs taken by each of the unlucky wise men in each possible starting situation. Each vertex from the first beat is connected to 50 of

(Continued on page 34)
