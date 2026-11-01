---
id: 1979-11-kirillov-klumova-sosinskiy-syurrealnyie-chisla-c6481108
issue: kvant_1979_11
year: 1979
number: "11"
title: Surreal numbers
authors:
  - Кириллов А. А.
  - Клумова И. Н.
  - Сосинский А. Б.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 4, 5, 6, 7, 9
tag: S4UX
lang: en
source: kvant_digital
extraction: vision
content_sha256: c9c897ab2eac876b6b7a11a69d479b2ccc78635ba7d80057b8d6a60e9207e050
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/03_kirillov-klumova-sosinskiy-syurrealnyie-chisla-c6481108.md
source_content_sha256: b079199690a60e0e4b6fad71781274e03926d244e9d141ac64fd895aace43d2d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

Surreal numbers

A. Kirillov, I. Klumova,
A. Sosinsky

The concept of a real number is one of the basic ones in mathematics. It is not surprising, therefore, that many methods are currently known for constructing a rigorous theory of real numbers. Among them, the simple and natural axiomatic method stands out. It consists in the fact that we refuse to answer the question “what is a number?”, but define all numbers at once, describing what properties they have. Properties of these formulations in the form of axioms. It turns out that for the axiomatic definition of real numbers, the 12 axioms given on p. 9.

Of course, there is no guarantee that there will be lenses that meet this set of requirements. Therefore, in addition to the axioms, it is desirable to have a model - a set of objects that satisfy these axioms. However, you know this model of real numbers well - these are infinite decimal fractions.

Relatively recently, the English mathematician John Conway managed to “build” a very interesting model that contains not only all the real numbers, but also many others - with interesting and unusual properties. These numbers - we will call them K-numbers, and Conway calls them sorreal (supermaterial) - satisfy 11 of the 12 axioms mentioned.

We will tell you something about these numbers in our article. Unfortunately, to construct all K-numbers you need the concept of a transfictional number, which is not taught in school. But you can look into their arithmetic at the school level.

Description of K-numbers

In Convey arithmetic, together with the usual numbers 0, 1, 2, ..., 9, only two signs are used: ↑ - CR (up - English) and ↓ - down (down - English). Sets of these symbols are K-numbers.

The set may not contain any characters at all. Below we will see that this set plays the role of zero, so we

⟦folio 3⟧

Let us denote it in advance by 0. The set can be any finite, for example: ↓; ↑↑↓; ↓↑↑↓↑↓; can be any infinite: ↑↓↑↑↑↓ ..., and maybe even “more than infinite” (see the last section). We will mainly operate with finite sets.

If the symbols ↑ and ↓ are viewed as indicating the directions of movement of the I, then each set of “ir” and “add” can be perceived as a “Ponska protocol” corresponding to some K-number, with different “protocols” corresponding to different K-numbers.

Let's compare this to writing a real number as an infinite decimal fraction. Here, too, the desired number x is constructed by successive approximations. But with ordinary successive decimal approximations, we select numbers from below, and not with a mover, as with K-numbers (Fig. 1). In addition, the decimal notation (as opposed to the notation of K-numbers) is ambiguous: 0.99999... is the same as 1.0000...

Let us now explain how to compare K-numbers by magnitude.

Order relation

To compare two K-numbers, you need to write them one below the other and compare the symbols included in their notation in turn (as when establishing the alphabetical order of words in a dictionary; this order of mathematicians is called lexicographic). If the first of the unequal symbols of the number x is the symbol ↑, and the first of the number y is the symbol ↓, then x>y. Another case is possible when the number x is shorter than the number y

*) What is “more is less” for K-numbers and why 0 is the simplest K-number, we will explain in the next section.

Fig. 1.

and constitutes its beginning. Then we write x>y if the first “extra” character in y y is the character ↓, and x<y if this character is ↑*). For example, a fair inequality is ↓<0<↑↑<↑<↑↑↓.

Looking ahead, let's say that all numbers starting with ↑ will be positive (that is, >0) in K-arinetics, and all numbers starting with ↓ will be negative.

For K-numbers, in addition to the order relation (>, =, <), there is one more important relation; Conway calls this relationship “rave” and denotes it with the symbol ←. We will say that a K-number a is equal to a K-number b if a encounters 0 on the way to b (see Fig. 1). In other words, a ←b if a can be obtained from b by “cutting off the tail” - part (from the end) of the arrows ↑ and ↓. For example, ↑ is equal to ↑ or ↑, and 0 is by definition considered the earliest number.

Note that the property “greater than” is not the same as the property “greater than”: for example, the number ↑ is not equal to the number ↑. In the same way, the property “more” does not coincide with the property “greater than” or “greater than”: for example, both numbers ↑ and ↑ are equal to the number ↑, but the first of them is greater than ↑, and the second is less.

*) In particular, the “empty set” 0 is the beginning of any K-number.

⟦folio 4⟧

Main lemma
Let us have two sets of $K$-numbers: $A$ and $B$. We will say that the set $B$ lies in the set $A$ if every number from the set $A$ is less than every number from the set $B$; let's denote it like this: $A < B$. Let's say that the number $c$ is separable from the sets $A$ and $B$ if $a < c < b$ for any $a \in A$ and $b \in B$.

Main lemma. If $A < B$, then there is a $K$-number $c$ separating the sets $A$ and $B$. The average maximum numbers are the earliest. (In what follows, the earliest number separating the sets $A$ and $B$ will be denoted as follows: $\{A:B\}$.)

We called this lemma the main one because it will play a major role in determining the rules of action on the set of $K$-numbers. It is true for any set of $K$-numbers $A$ and $B$. But we will prove it only under the assumption that $A$ and $B$ are finite sets of finite $K$-numbers.

We will search for an element separating the sets $A$ and $B$, sequentially. Since $0$ is the earliest number, let's start there.

If $0$ separates the sets $A$ and $B$, then everything is proven. If not, then on both sides (in the sense of “more is less”) of $0$ it will find either elements from $A$ or elements from $B$. Let these be elements from $A$. Then the separating element cannot be smaller than $0$, i.e. it cannot begin with $\downarrow$; that means it starts with $\uparrow$. The earliest number starting with $\uparrow$ is $\uparrow$. We reason as above: if $\uparrow$ separates $A$ and $B$, then everything is proven. If not, then again on both sides of it it will find elements from $A$ or from $B$; Let us now assume that these are elements from $B$. Then the separating element cannot be greater than $\uparrow$; that means it starts with $\uparrow$. We take $\uparrow$ and continue the same procedure with it, etc. (Fig. 2).

We give you the opportunity to verify that this process (in the case of finite sets $A$ and $B$, consisting of finite $K$-numbers) cannot continue indefinitely and, therefore, leads to a separating number $c$.

To prove it, you can, for example, isolate the most number from $B$ and the most number from $A$ - thereby the proof of the theorem is reduced to the special case when each of the sets $A$ and $B$ consists of one number.

From the construction method itself, it is clear that $c$ is equal to any of the dividing numbers.

The same method of proof can be applied in the general case, but it leads, generally speaking, to an infinite separating $K$-number, and a rigorous proof that the process will “end” (what this means for infinite processes remains to be determined!) requires information from the theory of transfinite numbers.

Definition of addition
Conways defines operations on $K$-numbers, guided by the principle of regularity and simplicity. It consists in the fact that the correct actions are not determined immediately for all numbers, but gradually: first for earlier ones, and then for “later” ones; at

⟦folio 5⟧

In this case, the earliest possible number is selected as the result.

By determining, for example, the sum of two $K$-numbers, we assume that for all earlier terms the sums have already been determined. After this, the second half of the principle applies. To show how this principle “works,” let’s calculate several sums using it. Of course, until we give the principle a clear mathematical formula, these calculations will be somewhat lax.

Since 0 is the earliest number, let’s first “calculate” the sum 0+0. Since there are no results yet, the answer can be any $K$-number. But of all possible answers, you should choose the earliest one. This is 0. So, we have “proved” the equality

$$0+0=0.$$ (1)

Let's now try to check that real 0 has the properties of zero specified in axiome C3 (see p. 9), that is, that

$$0+x=x$$ (2)

for any $K$-number $x$.

Let us introduce some notation for this. Let $x$ be some $K$-number. Let us define by medium $x$ (notation: $x$) the set of all $K$-numbers $y$ earlier than $x$, that is

$$x = \{y | y \in x\}.$$

Slice $x$ is divided into lower media $x$ and upper media $x$ (symbols: $x$ and $x$, respectively). The lower middle $x$ is the set of all $y$ earlier than $x$ and less than $x$:

$$x = \{y | y \in x\}, y < x\},$$

and the upper medium is the set of all $y$ earlier than $x$ but greater than $x$ (see Fig. 2):

$$\bar{x} = \{y | y \in x\}, y > x\}.$$

For example, medium $\bar{x}$ consists of four numbers:

$$\bar{x} = \{0, \uparrow, \downarrow, \uparrow\},$$

and the lower medium is $\bar{x} = \{0, \uparrow, \downarrow\}$, and the upper medium is $\bar{x} = \{0\}$. And here are $\downarrow$ - these are empty sets; at the same time $\bar{x} = \{0\}$.

Let us now use it one more time: we will assume that for $K$-numbers an earlier number than $x$, equality (2) is true (obviously, any number that is equal to $x$ belongs to either $x$ or $x$). Then the sum 0+x is greater than any number from $x$. Thus, the number 0+x separates the set $x$ and $x$ (lower and upper environments $x$). Since, according to Convel's principle, you need to choose the earliest such number, 0+x = $\{x\}: \bar{x}\}$. But $\{x\}: \bar{x}\} = x$ (think about why), that is, 0+x=x.

So we've almost justified the notation 0 for the empty set. The above statement is now justified that in $K$-arthmetic, numbers starting with $\uparrow$ play the role of positive ones, and numbers starting with $\downarrow$ play the role of negative ones.

Let us now find the sum $\uparrow + \uparrow$. Because $\uparrow = \{0\}, \uparrow + \uparrow$ is greater than $\uparrow$. The earliest number greater than $\uparrow$ is $\uparrow + \uparrow$. That's why

$$\uparrow + \uparrow = \uparrow + \uparrow.$$ (3)

We now have experience solving addition examples: we understand that the sum $x+y$ must be the earliest number that separates the sums with a deficit (that is, the union of the set $x+y$ and $x+y$) and the sum with an excess (the union of the set $\bar{x}+y$ and $x+y$). (Concerning sums with a deficiency and sums with an excess, we believe that their definition has already been reduced.) Thus, the principle of order and simplicity leads us to the following definition of the sum of two numbers:

$$x+y = \{(x|+y) \cup (x+y)\}.$$

(recall that the element $\{A:B\}$, where $A < B$, exists and is uniquely determined).

Formula (4) is a strict expression of Convel's principle for the sum of numbers. To determine addition, you also need to add naval conditions to it - formula (1). In fact, it cannot be proven; it is part of the definition. Using formulas (4) and (1), you can calculate the sum of any $K$-numbers.

⟦folio 6⟧

Now we can check that the addition axims are satisfied in our model (see p. 9).

Let us check, for example, that the addition defined by formula (4) is commutative.

In fact, let us take the first two numbers for which addition is non-commutative *). Their sum is the earliest number separating the amounts with a deficit from the amounts with an excess. Amounts with a deficiency and sums with an excess were commutative (by assumption). This means that the earliest number that separates them also does not depend on the order of addition - we divide the same set of sets and in general cases we take the earliest number among those separating (and it is determined in a unique way - see the main lemma). This means that the sum of our two numbers does not depend on their order, subject to assumption. This means that addition is commutative.

We were actually convinced of the fulfillment of axiom C3 earlier. The C1 axim is more difficult to check than the C2 axim; think how.

Let us now find the sum ↑+↓. Note that ↑| and ↓| - empty sets. Therefore, the answer must be the earliest number greater than ↓ (since ↑|={0}) and smaller than ↑ (since ↓={0}). This number is 0.

So, ↑+↓=0 and ↓ is the opposite (in the sense of axim C4) element for ↑.

Let us denote by ↑n and by ↓n K-numbers consisting of n consecutive corresponding symbols.

Tasks
1. Prove that ↑n + ↑m = ↑n+m, ↓n + ↓m = ↓n+m.
2. Prove that
$$\begin{align*}
\hat{n} + \hat{m} &= \begin{cases}
\hat{n}-m, если n > m; \\
0, если n = m; \\
\hat{m}-n, если n < m.
\end{cases}
\end{align*}$$

From these problems it follows that the number ↑n can be put off with the usual natural number n*), and the number ↓n can be put off with the opposite number (-n). Thus, Conver's numbers contain all common integers!

Problem 3. Prove that if for a given K-number all ↑ are replaced by ↓, and all ↓ by ↑, then you get a number that is its opposite. (For example, ↑↑↓↓↓↓=0.)

It follows from Problem 3 that the Conver model satisfies axiom C4.

Are there dobies?

Let's take the number ↑↓. Let's try to add it to itself. What can be said about the sum ↑↓+↑↓? It must be less than the sum ↑↓+↑, and greater than the number ↑↓. At night the sum is equal to ↑↓+↑, we don’t know. We violated our main principle: to move from earlier to later numbers. You will have to (without any money!) first calculate the amount ↑↓+↑.

This number is less than the number ↑+↑=↑↑ (since ↑|={↑}), and greater than the number ↑+0=↑ (since ↑|={0}), and it is the earliest such number. The earliest number between ↑ and ↑↑ is the number ↑↑↓; therefore ↑↑↓=↑↑↓.

Let's return to the sum ↑↓+↑↓. Now we know that it is contained between the numbers ↑↓ and ↑↑↓. The earliest such number is ↑ (make sure of this!).

So, in K-arthmetic, the number ↑↓ plays the role of a “half”. Similarly, it is established that ↑↑↓ among K-numbers is the same as the common number $\frac{3}{2}$ among real numbers.

Tasks
4. Find the sums ↑↓↓+↑↓↓; ↑↓↓+↑↓↓; ↑↓↓+↑↓↓.
5. Which number usually corresponds to K-numbers:
a) ↑↓↓, ↑↓↓, ↑↑↓, ↑↑↑, ↑↑↑, ↑↑↑
b) ↓↑, ↓↑↑, ↓↑↑;
b) in general, numbers of the form
$$\begin{align*}
n \text{ «цр»} m \text{ «down»}
\end{align*}$$

*) If taken as one; ↑ really plays the role of a unit in Conver's arfmetic, but we cannot be sure of this, since we do not provide a definition of multiplication in this country.

⟦folio 7⟧

We will suggest from in problem 5:
The K-number ↑↓↓ is the same as $\frac{1}{4}$ in R, the K-number ↑↓↑ is the same as $\frac{3}{4}$, ↑↓↓ is $\frac{1}{8}$, ↑↓↓ is $\frac{3}{8}$, etc.

Problems 4 and 5 allow us to guess what real numbers usually correspond to all general finite sets ↑ and ↓. These are the so-called double-rational numbers (that is, rational numbers whose denominator is a power of two). Try to prove this statement.

What's next?

So, we found out that among the K-numbers there are all ordinary integers (these are either finite collections of ↑ alone or ↓ alone), as well as all other doubly rational numbers (they correspond to all possible finite collections, among which there are combinations ↑↓ or ↑↑).

If K-numbers are depicted as a “tree” as in figure 3, then the integer K-numbers appear “at the edges” of this tree, and the double-rational ones are inside it.

But what about the rest of the numbers? After all, we promised that among the K-numbers there are all real numbers, but for now it is not even clear what to do with rational numbers whose denominator is not a power of two. The whole point here is that we do not yet see the whole set of K-numbers: after all, we limited ourselves to the distance of only finite sets of “tsr” - “down”, defined addition for them and learned to solve simple problems (at the level of 2-3 grades of school). But we also need to define multiplication, and at the same time clarify the question of the existence of an inverse element for any non-zero K-number (see axiomy Y4). And it turns out that already to determine

⟦folio 9⟧

hasn't changed. However, this is not so: the new symbol ↑ follows all the previous ones (Fig. 4!) Therefore, ↑ and ↑ are different K-numbers.
Problem 9. What does the entry ↑↓ represent?
Answer: $\omega$ ↑. Hint: Calculate the sum ↑↓↑.

Among the numbers “longer than infinite” there are some quite intricate ones. Try, for example, to guess which of the entries in the right half of the circle on figure 5 corresponds to the K-number on the left half.

If you are interested in the K-number argument and would like to learn more about it, write to us.

Application

I. Axioms of addition.
For any two elements $a \in R$, $b \in R$ we determine the sum $a+b \in R$, and:
C1. $(a+b)+c=a+(b+c)$ (associativity).
C2. $a+b=b+a$ (commutative).
C3. There is an element 0 such that for any $a \in R$ the correspondence $a+0=a$ (the existence of zero) holds.
C4. For every element $a \in R$ there is an element $(-a) \in R$ such that $a+(-a)=0$ (existence of an arbitrary element).
II. Axioms of multiplication.
For any two elements $a \in R$, $b \in R$ we define the product $a \cdot b \in R$, so that:
Y1. $(ab)c=a(bc)$ (associativity).
Y2. $ab=ba$ (commutative).
Y3. There is an element 1 such that for any $a \in R$ we have the equality $a \cdot 1=a$ (existence of unity).

U4. For every element $a \in R$ other than zero, there exists an element $a^{-1} \in R$ such that $a \cdot a^{-1}=1$ (existence of an inverse element).

III. An axiom establishing the connection between addition and multiplication.
S—U. $a(b+c)=ab+ac$ (distributivity).

A set with the operations of addition and multiplication defined on it and possessing the listed properties is called a field by mathematicians (see «Kvant», 1977, No. 5, p. 45).

IV. Axioms of order.
P1. For each element $a \in R$ we have equal numbers of correspondences $a>0$, $a=0$, $0>a$.

P2. If $a>0$ and $b>0$, then $a+b>0$ and $ab>0$.

By definition, it is believed that $a>b$ if and only if $a-b>0$.

A field in which axioms P1 and P2 are satisfied and the order relation > is defined by the formula $a>b \Rightarrow a-b>0$ is called an ordered field.

The last group of axioms that define action numbers consists of just one axiom of a completely different nature.

V. The Axiom of Polota.
A non-empty set of real numbers bounded above.

This means that if for a non-empty set $A \subset R$ there is an element that is greater (or equal) to all elements of this set, then among such elements there is the largest one.

An ordered field for which the Polotte axiom holds is called a complete ordered field.

It has been proven that the listed 12 axioms uniquely define the set of real numbers. Thus, the real numbers are the only complete ordered field. K-numbers do not satisfy the last axiom.
