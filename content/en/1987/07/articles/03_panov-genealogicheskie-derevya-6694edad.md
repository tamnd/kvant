---
id: 1987-7-panov-genealogicheskie-derevya-6694edad
issue: kvant_1987_7
year: 1987
number: "7"
title: Family trees
authors:
  - Панов А. А.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 10, 11, 12, 13
tag: 9VI4
lang: en
source: kvant_digital
extraction: vision
content_sha256: dfdf6fe0929b998c47884015ba1c7681dba8105cc51591c90f8a81faf29ea754
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/03_panov-genealogicheskie-derevya-6694edad.md
source_content_sha256: bcc0ed2b54bdb8df8437b0c26460c154739dd644f163613e59f778f378dadf45
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

GENEALOGICAL TREES

A. A. PANOV

This article will talk about mathematical classics - the Euclid algorithm and Pythagorean triplets. Euclid's algorithm is described in Eklid's Elements (circa 300 BC) and was probably known long before that. The history of Pythagorean triplets can be traced back even further. A remarkable monument of human culture is the ancient Avilonian clay table containing fifteen Pythagorean triplets. It dates back to 1700 BC. e.

Here we will try to build dust with these ancient witnesses, to talk about them in the visual “language of trees.” This language proves useful in solving certain equations and indicates what connection exists between Euclid's algorithm and the method of constructing Pythagorean triplets recently proposed by the English mathematician A. Hall.

Euclid's algorithm
The Euclid algorithm is used to find the most common divisor (GCD) of two natural numbers.

Let $(m, n)$ be a pair of positive integers:
1) if $m=n$, then the number $d=m=n$ is the most common divisor of the original pair of numbers, if $m \neq n$, then go to 2);
2) replace the larger number with its difference with the smaller one and go to 1).

You may have been more led to the following version of step 2:

2') replace the larger number with its remainder when divided by the smaller number and go to 1),
but this is a matter of taste.

Problem 0. Prove that both algorithms 1), 2) and 1), 2') lead to the same result.

Note. Remember that division is repeated subtraction.

In any case, Euclid himself speaks of his algorithm as “the constant difference between less and more” (“Principles”, Book 7, Proposition P, translated by D. D. Morduchai-Boltovsky). It is this algorithm, based on repeated subtraction, that will be the object of our research.

Let us demonstrate the operation of the algorithm using a specific example. Let $(m, n)=(20, 12)$. Then, writing the actions of the algorithm from right to left, we get the following chain:

$(4, 4) \leftarrow (8, 4) \leftarrow (8, 12) \leftarrow (20, 12)$.

This means GCD $(20, 12)=4$. Doing the same for the pair $(5, 3)$, we get the chain

$(1, 1) \leftarrow (2, 1) \leftarrow (2, 3) \leftarrow (5, 3)$.

It is clear that each number in the second chain is obtained from the corresponding number in the first chain by dividing by 4.

After understanding this example, answer the following question.

Problem 1. Let $d=НОД (M, N)$. Let's put $m=M/d, n=N/d$. What is the gcd of $(m, n)$ and what is the similarity between the action of the Euclidean algorithm on the pair $(M, N)$ and on the pair $(m, n)$?

In what follows, we will restrict only pairs $(m, n)$ for which the GCD is $(m, n)=1$. We will call such pairs simple pairs.

Genealogy of simple couples
Let's look at another example. Let's apply the Euclidean algorithm to the simple pair $(3, 4)$:

$(1, 1) \leftarrow (2, 1) \leftarrow (3, 1) \leftarrow (3, 4)$.

This chain has a common part with the chain for the pair $(5, 3)$, and therefore they can be combined:

$(3, 1) \leftarrow (3, 4)$
$(2, 3) \leftarrow (5, 3)$

You can add another simple pair $(3, 2)$, and the picture of the condition is:

$(3, 1) \leftarrow (3, 4)$
$(2, 1) \leftarrow (2, 3) \leftarrow (5, 3)$
$(1, 2) \leftarrow (3, 2)$

⟦folio 10⟧

It seems that there must be a general picture outlined by all the simple pairs. To figure out its structure, we could add a few more simple pairs. One way or another, at some point in time, the right question must come to our minds: the path has a simple pair $(m, n)$; from which pairs can arrows go to it?

Problem 2. Prove that if an arrow goes from the pair $(M, N)$ to the pair $(m, n)$ in the Euclidean algorithm, then either $M=m+n$, $N=n$, or $M=m$, $N=m+n$.

This problem prompts us to introduce two transformations $t_1$ and $t_2$ that take the pair $(m, n)$ into pairs
$$t_1(m, n)=(m+n, n),$$
$$t_2(m, n)=(m, m+n).$$
(1).

Now we can move in reverse order. Let's start with the pair $(1, 1)$ and apply both transformations $t_1$ and $t_2$ to it ($t_1$ acts on the upward arrow, $t_2$ on the downward arrow). We get two new pairs - $(2, 1)$ and $(1, 2)$. For each of them we again apply $t_1$ and $t_2$, etc.

Each pair here generates two new pairs, and this process continues for the first time ad infinitum. As you would expect, figure 1 contains the entire previous picture as fragments, only the arrows here are facing the other direction.

Fig. 1.

Problem 3. Prove that any pair $(m, n)$ on figure 1 is simple.

Problem 4. Prove that every simple pair is contained on figure 1 and, moreover, only once.

After these problems, it is natural to call what is depicted in figure 1 a family tree of simple pairs.

Problem 5. Let the pair $(m, n)$ lie on the family tree at figure 1. There is a unique path connecting it with the initial pair $(1, 1)$. Show that moving along this path against the arrows corresponds to applying the Euclidean algorithm to the pair $(m, n)$.

So, the family tree on figure 1 contains all simple pairs. Applying the Euclidean algorithm to the pair $(m, n)$ is equivalent to moving along the tree against the arrows.

Equation $XY=Z^2$
Let's now change the topic and try to find all the integer solutions to the $(X, Y, Z)$ equation
$$XY=Z^2.$$

We restrict only positive $X, Y, Z$. Example: $X=3$, $Y=12$, $Z=6$.

It would seem, what to talk about? For a given $Z$, finding a solution to the equation is a property of decomposing the number $Z^2$ into two factors, and for each $Z$ you can even calculate the number of the solution.

Problem 6. Let us fix $Z$ and the path $Z=p_1^{a_1}p_2^{a_2}...p_l^{a_l}$—the decomposition of $Z$ into simple factors. Prove that the solution number of equation (2) is $(2a_1+1)(2a_2+1)...(2a_l+1)$.

However, I want to offer a different point of view.

Problem 7. Let $(X, Y, Z)$ be the solution to equation (2); prove that for $d>0$ the triple $(dX, dY, dZ)$ is also a solution. Let $(X, Y, Z)$ be a solution to equation (2) and GCD $(X, Y)=d$; prove that $(X/d, Y/d, Z/d)$ is also a solution to equation (2) and at the same time gcd $(X/d, Y/d)=1$.

Thus, when searching for all solutions $(X, Y, Z)$ of equation (2), we can limit ourselves to only those for which GCD $(X, Y)=1$; Let's call them primitive. All the rest are obtained from primitive ones by simple multiplication.

Problem 8. Let $(X, Y, Z)$ be a primitive solution to equation (2). Prove that there is a simple pair $(m, n)$ such that $X=m^2$, $Y=n^2$, $Z=mn$.

It is now clear that the correspondences $X=m^2$, $Y=n^2$, $Z=mn$ (3) provide a one-to-one correspondence between the simple pairs $(m, n)$ and the primitive solutions $(X, Y, Z)$ of equation (2).

This means that we can take full advantage of our previous results on simple pairs. For example, using correspondence (3), we replace each simple pair $(m, n)$ by figure 1 with the corresponding primitive solution $(X, Y, Z)$. It is natural to call the resulting tree a geneological tree of primitive solutions to equation (2). It contains everything without

⟦folio 11⟧

exceptions are primitive solutions. It is possible to propose a more direct and convenient way to construct this tree.

Task 9. Let the pair $(m, n)$ generate, using (3), the solution $(X, Y, Z)$. Let us denote the solution generated by the pair $t_1(m, n) = (m+n, n)$ by $T_1(X, Y, Z)$ and the solution generated by $t_2(m, n) = (m, m+n)$ by $T_2(X, Y, Z)$. Prove that

$$T_1(X, Y, Z) = (X+Y+2Z, Y, Y+Z),$$
$$T_2(X, Y, Z) = (X, X+Y+2Z, X+Z).$$

All this means that the family tree on figure 2 arises directly from the transformation of $T_1$ and $T_2$. We start from the next solution (1, 1, 1) and begin to apply the transformations $T_1$ and $T_2$ on it. An arrow going up corresponds to action $T_1$, an arrow going down corresponds to action $T_2$.

Fig. 2.

Figure 2 looks very attractive and allows us to get a clear idea of ​​the structure of the set of all primitive solutions to equation (2). But still, equation $XY=Z^2$, as we have already said, allows for a simpler approach. Therefore, let's move on to consider a more meaningful example.

Pythagoron triples

So the equation
$$X^2+Y^2=Z^2.$$
Its positive integer solutions $(X, Y, Z)$ are called *Pythagoron triples*. The very first example of a Pythagorean triple is, of course, the triple (3, 4, 5). We would also like to build a decision tree for this equation - a family tree of Pythagorean triplets, similar to the one in figure 2. How to do this? If we follow what was done for equation $XY=Z^2$, then we need:

(I) among all Pythagorean triplets, select primitive ones;

(II) for primitive Pythagorean triples $(X, Y, Z)$ write down suitable correspondences $X=X(m,n), Y=Y(m,n), Z=Z(m,n)$ to similar correspondences (3);

(III) construct a family tree for pairs $(m, n)$ and replace each pair $(m, n)$ on it with the triple $(X(m, n), Y(m, n), Z(m, n))$ generated by it.

What is connected with points (I) and (II) has long been known. We will report the necessary facts without any comments or evidence, referring the reader, if necessary, to the article by S. M. Voronin and A. G. Kulagin («Kvant», 1987, No. 1, p. 11).

A Pythagorean triple $(X, Y, Z)$ is called *primitive* if GCD $(X, Y)=1$ and $X$ is odd and $Y$ is even. The triple (3, 4, 5), for example, is primitive.

It is known that for any Pythagorean triple $(x, y, z)$ there is a unique primitive Pythagorean triple $(X, Y, Z)$ and a unique natural number $d$ such that either $(x, y, z)=(dX, dY, dZ)$ or $(x, y, z)=(dY, dX, dZ)$. Thus, having enumerated all primitive Pythagoron triples, we get the opportunity to enumerate all general pythagoron triples.

An integer pair $(m, n)$ is called *primitive* if $m>n, n>0$, gcd $(m, n)=1$ and numbers $m, n$ have different parities. The pair (2, 1), for example, is primitive.

It is known that the correspondences $X=m^2-n^2, Y=2mn, Z=m^2+n^2$ (4) provide a one-to-one correspondence between the set of all primitive pairs and the set of all primitive Pythagorean triples. The pair (2, 1), for example, with the help of correspondences (4) generates the triple (3, 4, 5).

As for point (III) of our program for constructing a family tree, it was implemented by the English mathematician A. Hall.

Genealogy of Pythagorean triplets

In a short note published in 1970 in the Mathematical Gazette, A. Hall suggests

⟦folio 12⟧

The following is a method for constructing a family tree for primitive pairs and primitive Pythagorean troeks. Three transformations $t_1, t_2$ and $t_3$ are introduced:

$$t_1(m, n) = (2m - n, m),$$
$$t_2(m, n) = (2m + n, m),$$
$$t_3(m, n) = (m + 2n, n).$$

Using these transformations, starting with the pair (2, 1), a family tree is built. Here the upward direction corresponds to the transformation $t_1$, the horizontal direction corresponds to the transformation $t_2$, and the downward direction corresponds to the transformation $t_3$.

Problem 10. Let the pair $(m, n)$ generate a Pythagorean triple $(X, Y, Z)$ using correspondences (4). The Pythagorean triple generated by the pair $t_1$ $(m, n)$ is denoted by $T_1(X, Y, Z)$; the triple generated by the pair $t_2$ $(m, n)$, through $T_2(X, Y, Z)$; finally, the triple generated by the pair $t_3$ $(m, n)$ through $T_3(X, Y, Z)$. Prove that

$$T_1(X, Y, Z) = (X - 2Y + 2Z, 2X - Y + 2Z, 2X - 2Y + 3Z),$$
$$T_2(X, Y, Z) = (X + 2Y + 2Z, 2X + Y + 2Z, 2X + 2Y + 3Z),$$
$$T_3(X, Y, Z) = (-X + 2Y + 2Z, -2X + Y + 2Z, -2X + 2Y + 3Z).$$

Now, using the transformation $T_1, T_2, T_3$, we will build another family tree, but it already started with a triple (3, 4, 5).

Hall's remarkable result is that the family tree on figure 3 contains all primitive pairs without exception; This means that the family tree on figure 4 contains all pairs (2, 1) without exception.

Each pair $(m, n)$ to figure 3 matches exactly one arrow. For the transformation $u_1, u_2, u_3$ this corresponds to the following fact.

Problem 13. Let the pair $(M, N)$ be primitive and $(M, N) \neq (2, 1)$. Prove that then only one of the three pairs $(m, n) = u_i(M, N)$, $i = 1, 2, 3$ will be primitive. At the same time $m + n < M + N$.

And finally, the final one

Problem 14. Prove that every primitive pair is contained on the family tree on figure 3 and only once (as well as every primitive Pythagogian triple on figure 4).

Other genealogists

In 1978, an article by E. Selmar was published in the Scandinavian mathematical journal Normat, in which it was established that there are

⟦folio 13⟧

two more geneological trees containing all primitive Pythagorean trikes without exceptions or repetitions (Fig. 5).

The first of them is constructed using the transformation
$$T_1(X, Y, Z) = (2X - Y + Z, 2X + 2Y + 2Z, 2X + Y + 3Z),$$
$$T_2(X, Y, Z) = (2X + Y + Z, 2X - 2Y + 2Z, 2X - Y + 3Z),$$
$$T_3(X, Y, Z) = (2X + Y - Z, -2X + 2Y + 2Z, -2X + Y + 3Z).$$

Second - using transformation
$$T_1(X, Y, Z) = (X - 2Y + 2Z, 2X - Y + 2Z, 2X - 2Y + 3Z),$$
$$T_2(X, Y, Z) = (2X + Y + Z, 2X - 2Y + 2Z, 2X - Y + 3Z),$$
$$T_3(X, Y, Z) = (-2X + 3Y + 3Z, -6X + 2Y + 6Z, -6X + 3Y + 7Z).$$

Pythagorean trikes have invariably attracted the attention of mathematicians for thousands of years. But we see that this topic has not exhausted itself, and new interesting facts continue to be discovered here.

Summing up
In connection with what has been said, there are several questions that need to be, if not resolved, then at least asked. For example, why do control $XY = Z^2$ have two arrows from each solution, and three on the family tree for $X^2 + Y^2 = Z^2$? Further, why were three geneological trees built for control $X^2 + Y^2 = Z^2$, and only one for control $XY = Z^2$, and are there other trees for these controls? Finally, how would the transformations $T_1$, $T_2$, $T_3$ be found, allowing one to construct geneological trees for Pythagorean trikes?

Our construction of the family tree for control $XY = Z^2$ is directly related to the Euclidean algorithm and appears to be quite motivated, which cannot be said about control $X^2 + Y^2 = Z^2$. However, there is a connection between these departments that justifies attempts to do for one of them what was done for the other. Indeed, let us write the control $X^2 + Y^2 = Z^2$ in the form $Z^2 - X^2 = Y^2$ and factorize the left-hand side: $(Z - X)(Z + X) = Y^2$. Having made the replacement $U = Z - X$, $V = Z + X$, $W = Y$, we arrive at control $UV = W^2$. Thus, there is a replacement that transfers control $X^2 + Y^2 = Z^2$ to control $XY = Z^2$.

There is also a goal of a series of controls that can be replaced, transforming them into $XY = Z^2$. Such controls will be, say, $X^2 + Y^2 = 2Z^2$ and $X^2 + 3Y^2 = Z^2$. You can try to build family trees for these departments as well.

It is necessary to say about one more replacement control - Markov control:
$$X^2 + Y^2 + Z^2 = 3XYZ.$$

It already has a property that is inherent to us - all its solutions, except for two very low ones (1, 1, 1) and (2, 1, 1), are organized into a geneological tree. This is described in detail in the magnifying article by M. G. Krein («Kvant», 1985, No. 4, p. 13). This tree is quite similar to the family tree for management $XY = Z^2$. Is there any connection between these controls? What other controls have similar properties?

So there's something else to think about here.
