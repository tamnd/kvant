---
id: 1985-7-uspenskiy-semenov-reshimyie-i-nereshimyie-algoritmicheskie-problemyi-5cc3054a
issue: kvant_1985_7
year: 1985
number: "7"
title: Solvable and Unsolvable Algorithmic Problems
authors:
  - Успенский В. А.
  - Семёнов А. Л.
rubric: osnovnye-stati
rubric_sub: Основные статьи
page_first: 11
page_last: 17
page_labels: 9-15
tag: 01S7
lang: en
source: kvant_digital
extraction: vision
content_sha256: b466a1159e84c78f0c9606374ecb0010409369c4ab98230889b107aff4a7a185
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/05_uspenskiy-semenov-reshimyie-i-nereshimyie-algoritmicheskie-problemyi-5cc3054a.md
source_content_sha256: 844ff57fa59d28894c472be2803f9967f9104e0ff1ec67fad92ef7cc12780d3a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

Decisive
and unsolvable
algorithmic
problems

Professor
V. A. USPENSKY,
Doctor of Physical and Mathematical Sciences
A. L. SEMENOV

Algorithms

We all know how to add multi-digit numbers - we learn this in childhood. Let us ask ourselves, what is our teaching? When in E. Ionesco's play "The Lesson" a student demonstrates substitution abilities for a variable of ten-digit numbers, the shocked teacher learned that her method was very simple - she had learned the (infinite!) multiplication table for all numbers. Apparently, our method is of a different kind. We know a single finite method that allows us to solve an infinite number of problems. In our case, the infinite set is formed by the problem of finding the sum: for each pair of numbers there is its own problem. The method is uniform because it is the same for all tasks. The method is finite in the sense that it can be expressed in a finite number of words (and if this were not so, then this method could not be taught!). As you know, this method is called “column addition” and consists in the fact that one number (for example, 8257) is signed blue under another (for example, 64) with the expression of the right edge (that is, like this: 64/8357, and not, say, like this: 64/8357) and then begins the sequential application of the table for adding single-digit numbers (which must be subtracted in advance) with transfer, where necessary, to the next digit. As a result of this, the number 8421 will be formed.

Here we have not so much outlined the method as recalled it, being assured that it is known. However, it would be useful for the reader to write down this method on paper in its entirety so that it can be understood and used by a person who does not previously know how to add multi-digit numbers. The exercise that we proposed to the reader is formulated in scientific language as follows: write down an algorithm that solves

⟦folio 10⟧

number addition problem. We will further formulate this and other problems of constructing algorithms, indicating what is required of the algorithm, approximately in the following form:

**Problem. Given: two arbitrary natural numbers. Required: find their sum.**

This form of notation will serve as a signal to us that the solution to the problem is not to find its own separate way to calculate the result for each two numbers, but to find a single general method that is suitable for all pairs of numbers, that is, to find an algorithm (in this case, an addition algorithm).

In this article, by algorithm we will understand any finite system of rules that defines a computational procedure. This process begins with the presentation (submission to the input of the algorithm) of an arbitrary (but selected from a set fixed for a given algorithm) initial data. The process can end with the receipt of a complete result defined by this initial data; then the result is said to be the output of the algorithm. However, the process can continue indefinitely; the result of the algorithm does not always exist. For example, an algorithm that calculates the quotient of two numbers as a decimal fraction may not end up working (so 1:3=0.33333...).

The concept of an algorithm is one of the basic concepts of mathematics. The theory of algorithms, together with mathematical logic, forms the functional theoretical basis for the construction and use of computer technology. The specific beginning of algorithms for certain problems makes it possible to solve these problems on a computer.

The term “algorithm” itself is remarkable. In fact, are there many scientific terms that include a geographical name? Such a name cannot be immediately smoothed out in the “algorithm” layer, but it is there - this is the name of the city “Khorezm”. After all, the term “algorithm” is based on the name of al-Khorezmi (which means “from Khorezm”), a great mathematician of the 9th century. The largest mathematicians and algorithms from all over the world paid tribute to the fundamental role of al-Khorezmi, having gathered in September 1979 in the Khorezm region of Uzbekistan, in the city of Urgench, where they discussed issues of the theory of algorithms and its applications at the present stage. One of its organizers, Academician A.P. Ershov, said something similar about this meeting in Urgench (see «Kvant», 1984, No. 8, p. 29).

We are going to show the reader the most significant and illustrative examples of unsolvable algorithmic problems, that is, algorithmic problems for which there is no solution. By contrast, these examples will contain ones where there is an algorithm (although sometimes very complex) or the question of whether there is an algorithm has not yet been resolved.

**Solving algebraic equations**

Let's write out the equation

$$x^2 + 2 = y^3$$

(1)

and we will be interested in his decisions. The solution in this case is a pair of numbers (a; b), subject to the condition $a^2 + 2 = b^3$, for example, the pair (5; 3).

When solving any equation, you must always know exactly what numbers can be used as its solution. If, for example, the solution to the equation should be the increase in the number of goats in such and such a herd over such and such a period, will we be satisfied with the answer “two thirds” (but the answer “minus ten” will be meaningful: it means that the number of goats in the herd, unfortunately, has not increased, but decreased). For equation (1), one can be interested in its real solutions, that is, parameters of real numbers, located solutions, that is, parameters of located numbers, integer solutions, that is, parameters of integers. Equation (1) has infinitely many real solutions: it is enough to take any a and put b = $\sqrt[3]{a^2 + 2}$, then the pair (a; b) will be solutions (question to the reader: is it possible to take any b and put a = $\sqrt{b^3 - 2}$?). It is not difficult to prove that (1) has infinitely many located solutions; here is one of them: (0.383; 0.129). There are only two solutions: (5; 3) and (−5; 3). However, this is not easy to prove.

Solving an equation in integers seems to be a very ancient task (Pythagoras himself studied it in the 6th century BC) and, in the general case, a very difficult task. The main difficulty is to find out whether a given equation has at least one integer solution. For example, it is unknown (at least it was unknown until comparison)

⟦folio 11⟧

recently) do the equations $x^3+y^3+z^3=30$ and $x^4+y^4+z^4=u^4$ have solutions for number purposes.

A challenge for the reader. For each of the equations $x^4+y^4=5z^2$, $3x^2-y^2=1$, $x^2+y^3=z^4$, find some solution in numerical terms or prove that such a solution does not exist.

Note. You can read about these and other equations for number purposes in popular brochures: Gelfond A. O. “Solving equations for number purposes,” M., 1952. (series “Popular Lectures on Mathematics,” issue 8); Serpisky V. “On solving equations for number purposes”, M., 1961.

The problem “to be able to find out from an arbitrary algebraic equation with coefficients whether it has a numerical solution” is one of the twenty-three so-called “Hilbert problems”. What's the problem?

When David Hilbert (1862–1943), one of the greatest mathematicians of the 20th century, prepared his paper at the World Congress of Mathematics in Paris in 1900, he selected 23 problems from various areas of mathematics. These problems were his attempt “to penetrate into the upcoming conditions of our science and the secrets of its development in its infancy.” This attempt turned out to be extremely successful and valuable. And to this day, the solution (hereinafter referred to as particular) of any Hilbert problem is regarded throughout the world as the highest mathematical achievement. Gilbert considered the obligatory requirement for a real fundamental jam to be “the ability to present its contents to the first person you meet.” The problem of determining the existence of integer solutions is made up of the tenth problem from Hilbert's list. The reader can judge for himself the extent to which its formulation is social. We will now formulate Hilbert's tenth problem according to the standards adopted here.

Problem 1 (Hilbert's tenth problem). Given: an arbitrary algebraic equation with objective coefficients. Required: find out whether this equation has a solution for numerical purposes.

The required algorithm: in 1970, the Soviet mathematician Yu. V. Matiyasevich proved the impossibility of an algorithm that solves this problem (see «Kvant», 1970, No. 7, p. 39).

In connection with the formulation of the problem, it is appropriate to make a replacement applied not only to it, but, with appropriate changes, in other cases. There is an algorithm for finding some solution to any equation that is known to have a solution! An effective algorithm is this: you just need to substitute all sets of natural numbers into the equation. Eventually a set will be found that satisfies the equation.

Let us present several natural modifications of the first problem.

Problem 2. Given: an arbitrary algebraic equation with objective coefficients. Required: find out whether this equation has a solution in real numbers.

The algorithm you are looking for: exists!

The solution to Problem 2 was obtained by the famous user Alfred Tarski in the 40s of the 20th century. The application of this result will be discussed further. In fact, Tarski constructed a more general algorithm that allows one to determine whether systems of equalities and inequalities have a solution.

To assess the degree of non-triviality of Tarski's algorithm, try to solve the following problem. Given an arbitrary algebraic equation with all coefficients and one unknown, you need to find out whether it has a solution in real numbers. (It is clear that this problem is a simple special case of Problem 2). If the degree of the equation is odd, you can immediately answer that the root of the equation exists. What if it's a couple?

Problem 3. Given: an arbitrary algebraic equation with objective coefficients. Required: find out whether this equation has a solution in rational numbers.

The algorithm you are looking for: whether it exists or not is unknown.

Look how close the formulations of our problems 1, 2 and 3 are to each other: these formulations differ in only one word. And how, nevertheless, the answers to the question whether there is or not a corresponding algorithm are different. The concept is amazing!

⟦folio 12⟧

Converting words

In mathematics, words are any finite sequences of symbols. For example, 1985 is a word of length 4. Words not only do not have to have any meaning, but even be pronounceable. So, BRDROBSH is a word made of Russian letters (and, moreover, of length 8), although not a word of the Russian language. Typically, the input data for algorithms is words. When an algorithm is defined, a set of letters is also defined, that is, symbols that make up the words given to it as input. Such a set is called an alphabet. The alphabets in which texts are written in natural languages ​​and programming languages, and books are printed, contain no more than a few hundred letters. Multi-digit numbers involved in “school” algorithms are words in a ten-letter alphabet consisting of the letters 0, 1, 2, ..., 9; these letters, as you know, are called numbers; and to write decimal fractions, in addition to these ten digits, another letter is used - a comma.

Modern computers work with double words consisting of the letters 0 and 1. To illustrate the flexibility and capacity of the concept of “word,” note that a pair of words can be encoded as one word, for example, by placing between the members of the pair a letter that is not part of the alphabet in which these members are written. Thus, it is enough to consider words as initial data for algorithms, but there is no need to consider pairs, triplets, etc. of words in this capacity. Let us also note that it is often convenient to look at words of floor length; it is called an empty word because it contains no letters at all.

Many of you have played the following game. A task is given, for example, “transfer the wolf to the goat.” Solution:

What is one remodeling step? - In replacing any letter of an already obtained word with any other letter of the Russian alphabet, and so that the resulting object (a word in the mathematical sense of the word) turns out to be a meaningful word of the Russian language.

Now let's simplify the game - let's forget that among all the letter sequences the words of the Russian language are highlighted. We will consider all (in the mathematical sense, that is, both meaningful and meaningless) words in the Russian alphabet to be equal. Is it then possible to transform a wolf into a goat? Well, now it's quite easy:

WOLF→KOLK→GOAT→GOAT

Maybe now any word can be changed into any word? Of course not - the words must be the same length. But this condition is enough!

Problem. Given: two words in the Russian alphabet. You need to find out whether one of the other is a sequence of letter-by-letter substitutions.

The required algorithm: compare the lengths of words, if they match, then the answer is YES, if they do not match, then the answer is NO.

Note that the initial problem is to remake one given word of the Russian language; it is also very rare to only have a (finite!) dictionary of all the words of the Russian language that can be used in the game, and enough time and paper. A simple calculation shows that this problem can be practically solved on today's computers.

Now, having forgotten again about the Russian language (but not about the Russian alphabet) and under the words of the concept of arbitrary finite sequences of Russian letters, the conditions of the problem are complete; it is called an empty word because it contains no letters at all.

Transforming a word in one step will, as before, consist in the fact that anywhere in the word we replace the section that is allowed to be replaced with what it is allowed to be replaced with. In this case, all permitted substitutions are two-sided: if section X is allowed to be replaced with section Y, then section Y is also allowed to be replaced with section X. For example, if

⟦folio 13⟧

Since the allowed substitutions are the same as we just chose, then the transformation in one step can be like this: BAAB - BBBBB, or like this: BAB - ABAB, or like this: BABA - BAAAA.

Problem. Given: two words in the Russian alphabet. Required: find out whether one can be transferred to another, use the following system of permitted substitutions:

AB BB AY BY DBA DYB BBA
BA BB YA YB BD YD BBA

Searched algorithm: does not exist. This was proven by the Soviet mathematician G.S. Tseytin, who came up with the indicated system of substitutions.

A similar problem in general form (that is, any system of allowed substitutions) was first posed by the famous Norwegian mathematician Axel Thueve in 1914. He himself proved the existence of the algorithm in a number of special cases.

Thue especially highlighted the case when in every allowed substitution one of the terms is an empty word, and thus, every allowed substitution consists in the fact that you can insert the word indicated in the replacement into any place in an existing word or cross it out. For example, by inserting and crossing out the words AB and BA, you can get BABAB from the word ABBBA. Trying to construct the required algorithm for inserting and deleting AB and BA, that is, for such a list of allowed substitutions:

AB
empty word
VA
empty word

(Even this simplest example is important for the branch of algebra called “group theory.”)

For any set of allowed insertions and deletions, an algorithm exists that determines whether one word can be transferred to another. This was shown by the Soviet mathematician S.I. Adyan in 1966.

Elementary geometry

We do not have the opportunity here to give a detailed definition of what elementary geometry is in a strict sense, clarified with the help of mathematical logic. We will try, however, to give an approximate description. The initial concepts of elementary geometry are points, straight lines, planes, segments, circles, spheres, relations “to lie on”, “to lie between”, “to be congested”, etc. The formation of new concepts is allowed - but without the use of ellipses and the phrase “and so on” (at this point the strict mathematical-logical idea of ​​elementary geometry diverges from the fuzzy traditional one). For example, the concept of a triangle belongs to elementary geometry: after all, a triangle can be defined as three segments $A_1A_2$, $A_3A_4$, $A_5A_6$, such as $A_2=A_3$, $A_4=A_5$, $A_6=A_1$. But the general concept of a broken line does not belong to elementary geometry, because its definition involves ellipsis and the words “and so on”: a broken line is a set of segments in $A_1A_2$, $A_3A_4$,... (ellipsis here!), $A_{n-1}$, $A_n$, such that $A_2=A_3$, $A_4=A_5$, etc.

Problem. Given: a statement of elementary geometry. Required: check if it is true.

Required algorithm: exists.

The existence of the algorithm was essentially established by Tarski in the 40s of our century. It follows quite simply from the existence of the Tarski algorithm mentioned earlier. The connection between the problems of algebra and geometry was discovered a long time ago (analytic geometry), and naturally it extends to algorithmic problems.

Tarski's result looks, and indeed is, extremely strong and even paradoxical. It turns out that there is a large area of ​​classical mathematics (namely, elementary geometry), which is traditionally believed to require subtle intelligence and certainly does not correspond to the type of calculations, and at the same time there is an algorithm that can check the truth of theorems of this area (and if necessary, then look for their proof). The only consolation is that Tarski's algorithm is not real: it requires an incredibly long time for its implementation.

It is useful to imagine how “close” those geometric statements begin for which, despite the existence of a general algorithm,

⟦folio 14⟧

rhythm, their truth or falsity is now unknown.

Here is one clear example. Let's take a mover of round cans of the same diameter (equal to, say, 10 cm). We want to pack them, standing them up, in a round box. This can be done, for example, as shown in figure 1). However, you can arrange the jars more closely - so that you get a box that is smaller than its size. For example, as shown in figure 2. Finally, the packaging shown in figure 3 allows you to use an even smaller box. The question is, is it possible to find a round box with an even smaller diameter that would fit all our jars? The questionnaire does not know the answer, although this answer can be obtained using the Tarski algorithm: we need to apply this algorithm to the statement that the third packing is the best, and see what happens as a result. YES or NO. However, this method is not implemented, since it takes astronomically longer time to obtain the result of the algorithm.

An example of a proof of indecisiveness

Let's assume that we are working in a Computing Center. This center has a wonderful Computing Machine. It can perform calculations on any program $p$ written in some Programming Language, that is, using the input data $m$ it finds the result $p(m)$ of program $p$ (if, of course, it is defined).

Programs can be re-ordered (for example, in alphabetical order, because each program can be considered a word in the symbols of the Programming Language), creating a Library in all programs:

$$p_1, p_2, p_3, \dots, p_n, \dots$$

It is best to deal with programs $p$ that, given any input given $m$, produce the result $p(m)$. This is, for example, the standard program for calculating the function $y=m^2+5m-6$. Unfortunately, there are also programs that, for certain values ​​of the input data, do not finish their work; they “go in cycles,” as the programs say. Thus, a program for calculating the decimal notation of the function $y=m/3$ does not produce results for, say, $m=10$.

This is a very unpleasant circumstance. After all, if we enter such a program into the Computing Machine along with such “bad” initial data, the work of the Computing Machine will not end at all, and we will only waste expensive Machine Time.

To avoid this, it would be nice to have some procedure (algorithm!), which, based on the program number, would prepare in advance whether the program with this number will give a result or not with the selected input data.

Problem. Given: an arbitrary pair of natural numbers $(n, m)$. Required: construct an algorithm that will find out whether the $n$-th program $p_n$ terminates given the input $m$.

The algorithm we are looking for: does not exist, and we will now prove it.

Proof. (Diazonal Cantopa). Let's assume that the required algorithm A exists. Let's create a table of all the programs and source data:

⟦folio 15⟧

Let's consider the program $\bar{p}$, the result of which is “not the same as on the diagonal”, that is, we are determined by correcting

$$\bar{p}(m) = \begin{cases} p_m(m) + 1, & \text{ если } p_m(m) \text{ определено, } 0 \\ 0, & \text{ если } p_m(m) \text{ не определено.} \end{cases}$$

This is a real program, that is, $p$ is calculated using an algorithm. (Specifically, this: we check the condition $p_m(m)$ determined by the algorithm $A$, if it is satisfied, we calculate $p_m(m)$ and add one, if not, we assume $\bar{p}(m) = 0$). But then $\bar{p}$ is included in the list of all Viblotekka programs, under some number. Let's denote this number by $k$ and consider $p_k(k)$ (diagonal element!).

If $p_k(k)$ is undefined, then $\bar{p}(k) = 0$ and therefore $\bar{p}(k) \neq p_k(k)$.

If $p_k(k)$ is defined, then $\bar{p}(k) = p_k(k) + 1 \neq p_k(k)$.

In both cases, $\bar{p}(k) \neq p_k(k)$, which is impossible, or $\bar{p}$ and $p_k$ are the same program. This contradiction completes the proof.

The reader might want to know why the above proof is called Cantor's "diagonal". The fact is that the elegant method of proof used here was invented by the German mathematician Georg Cantor (1845-1918), the founder of set theory. True, Cantor established a completely different statement. Namely, that the set of real numbers cannot be confused by natural numbers, that is, make a list of all real numbers: $a_1, a_2, a_3, \dots$ (The reader, who saw this result a long time ago - “after all, there are more real numbers than natural numbers”, we advise you to prove that all rational numbers can be confused - although they are also “proudly larger than natural numbers”).

Following Cantor, we will prove (by contradiction) that even the set of real numbers on the interval [0,1] cannot be confused. Let's assume that we managed to do this. Let's arrange our numbers, suppose the number is 0,abc where $a$ is any digit other than $a_1$; $b$ — any number other than $b_2$; $c$ is any number other than $c_3$, etc. Contradiction!

Let's take some stock. We got acquainted with the concept of an algorithm - the most important concept of modern mathematics and computer science. Of course, many specific algorithms (for example, the column addition algorithm or the Euclid algorithm for finding a general measure) were known for a very long time, but a general idea of ​​the algorithm was formed only in the first half of the 20th century. Any attempt to use computers to solve any problems begins with the construction of an algorithm that solves these problems. As long as there is no such algorithm, it is impossible to compose a program for a computer. And if it turns out that an algorithm is needed and cannot exist, then it is pointless to try to compose a program. Therefore, the result about the impossibility of certain algorithms has a very practical meaning. In addition, the reasoning leading to the establishment of such an impossibility allows us to penetrate deeper into the nature of the very concept of “algorithm”.

The reader may have a question: can any algorithm be run in a computer program? Answer: theoretically yes. The word “theoretically” here means that the answer is in the affirmative, if we allow programs of any suitable length (to write which there is not enough paper, ink and pencils on the entire Earth) and for any length of time (trillion years). Note that assumptions of this kind are deeply rooted in mathematics. (We allow polygons with any number of sides. We believe that the column addition algorithm allows numbers of any size, although we are aware that if the weakened ones have larger signs than the Atoms in the Earth, then it is not entirely clear how to write such terms, and the number of balls when adding them will turn out to be astronomically large...) In addition, the capabilities of computer technology are constantly growing. If the first computers performed hundreds of operations per second, and were controlled by programs composed of tens of commands, then the fast modern machines reach hundreds of millions of operations per second, and the size of their programs is up to hundreds of thousands of commands. It’s nice to think that the machine’s capabilities will increase tenfold every five years. Of course, however, the estimates and dimensions of the algorithm and the number of balls it operates are of paramount importance. But this is a topic for separate server discussions.
