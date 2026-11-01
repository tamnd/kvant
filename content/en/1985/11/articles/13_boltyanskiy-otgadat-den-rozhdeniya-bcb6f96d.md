---
id: 1985-11-boltyanskiy-otgadat-den-rozhdeniya-bcb6f96d
issue: kvant_1985_11
year: 1985
number: "11"
title: Guess the birthday
authors:
  - Болтянский В. Г.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 30
page_last: 32
page_labels: 28-30
tag: C0A0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 71052c544420335dd332f0eb0cf95ead31bc8ae6ccd925234799688189c08829
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/13_boltyanskiy-otgadat-den-rozhdeniya-bcb6f96d.md
source_content_sha256: c53b1f01603da90705b1c2855b6796997b2db7b4c9ff1cfb611386bdb376bcbb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

Guess the birthday

Corresponding Member
Academy of Pedagogical Sciences of the USSR
V. G. BOLTYANSKY

A small note with the following title: “Guess the birthday,” is in Ya. I. Perelman’s book “Entertaining Algebra.” This note describes a certain number trick. This is what it consists of.

Imagine that an acquaintance of your father’s comes to see you, whose date of birth you do not know. Invite him to multiply the number of his birth by 12, the number of the month in which he was born, multiply by 31, and then add the resulting products. Let him tell you what he did. It turns out that by taking the sum of these two products, you can find out both required numbers (day and month of birth). You can see how this trick is performed in Ya. I. Perelman’s book. Now we will tell you another way to perform the same trick; This method was suggested by Pedro dela Risco Padron, a Cuban reader of Ya. I. Perelman’s book.

Let us denote by $x$ the birth date of the visiting acquaintance, and by $y$ the number of the month of his birth. A friend tells you the amount $12x+31y$. Let's consider two cases: a) $y$ is even; b) $y$ is odd.

a) $y$ is even, that is, $y=2k$. Then $12x+31y=12x+62k=$
$$=12(x+5k)+2k=12(x+5k)+y.$$
This shows that the number $12x+31y$ has the same remainder when divided by 12 (we denote it by $r$) as the number $y$. The number $y$ generally takes values ​​from 1 to 12, and in our case ($y$ is even) $y$ can be equal to 2, 4, 6, 8, 10 or 12. It is understood that $y=12$ when $r=0$. If $r \neq 0$ and $r$ are even, we have $y=r$.

b) $y$ is odd, that is, $y=2k+1.$

Then
$$12x+31y=12x+31(2k+1)=
=12(x+5k)+2k+7=
=12(x+5k+2)+y+6,$$
whence it is clear that the number $12x+31y$ has the same remainder $r$ from division by 12 as the number $y+6$, that is, $y$ either coincides with the number $r-6$ or differs from it by 12. This means that if $r$ is odd and $r>6$, then $y=r-6$; if $r$ is odd and $r<6$, then $r-6$ is negative, and therefore $y=(r-6)+12=r+6$.

This is where Pedro dela Risco Padron proposes to perform the trick:

1) if $r$ is even, but $r \neq 0$, then $y=r$;
2) if $r=0$, then $y=12$;
3) if $r$ is odd and $r>6$, then $y=r-6$;
4) if $r$ is odd and $r<6$, then $y=r+6$.

Find out $y$ and calculate the product $31y$, you subtract this product from the number $12x+31y$ given to you, find the number $12x$, after which, dividing the result by 12, find $x$. Date of birth has been determined.

Now let's look at this trick from a different point of view. A year contains 365 or 366 days, and any of them could be the birthday of a friend of my father's. Thus, the “volume” of possible reported information is equal to 366. If instead of the expression $12x+31y$ another expression were taken, and such that for two different days of the year the expression would receive the same values, then such an expression would be inappropriate for performing the trick. Having received this value, you would not be able to determine on which of the two days corresponding to this value of the expression the birthday occurs. The expression $12x+31y$ was taken because for all 366 days of the year (leap year) it takes on different numerical values.

But $12x+31y$ is not the only expression that has this property. The expressions $12x+35y$, $12x+37y$, $2x+31y$, $3x+31y$, $4x+31y$, $12x+7y$, $12x+5y$, $12x+y$ and others have the same property. For example, taking the expression $12x+y$, you can offer a simplified version of the trick: multiply the number of birth by 12, add the number of the month of birth and report the result. And the “algorithm” for performing a trick is as follows:

⟦folio 29⟧

the simplified version will be completely simple: you need to determine the remainder $r$ from dividing the reported number $12x+y$ by 12, and then for $r \neq 0$ we have $y=r$, and for $r=0$ there will be $y=12$. True, such a simplified version of the trick is easy to solve.

Finally, you can take the expression $100x+y$, and then the date of dividing is determined quite simply and uninteresting（《trivial》，as mathematicians say): the number of hundreds is equal to the number of division, and the last two digits give the place of division. For example, for the date July 16 (that is, $x=16$, $y=7$) we have $100x+y=1607$; now it’s enough to put a period, that is, write 07/16, and you get a method of writing the date, often used on documents (only they add another year: 07/16/72).

Tasks
1. Do the described trick with yourself and “guess” your birthday using the expressions: a) $100x+y$; b) $12x+y$; b) $12x+31y$.
2. Prove that if the natural numbers $a, b$ satisfy the inequality $31a+12b \leq 366$, then the expression $ax+by$ does not allow the trick described.
3. Prove that if the natural numbers $a, b$ satisfy the inequality $a<12$ and $b<31$, then the expression $ax+by$ does not allow this trick to be performed.
4. Prove that each of the expressions a) $x+31y$, b) $16x+31y$; b) $12x+7y$ is suitable for performing the described trick.

Editorial. In connection with this note, let us recall another interesting trick. This is an elegant problem, invented many years ago by D. B. Fuchs. True, in this problem we are not talking about the days of separation or days in general, but it also requires guessing several numbers.

Two spinners play a number guessing game. The first one thinks of 10 on the natural numbers (we denote them by $x_1, \dots, x_{10}$). The second one tries to calm them down, ask questions. As a question, he offers the first one his 10 natural numbers - let’s denote them by $a_1, \dots, a_{10}$. The first one in response tells him what the expression $a_1x_1+...+a_{10}x_{10}$ is equal to. Having heard the answer, the second participant asked the next question - similar to the first, but with a different $a_1, \dots, a_{10}$. And so on. In what is the smallest number of questions that can solve all the numbers $x_1, \dots, x_{10}$?

This problem was once invented for the Moscow Mathematical Olympiad, but was not included in it: members of the Olympiad Organizing Committee could not resist offering it first to each other, then to their acquaintances, and the problem became widely known. The answer is much more varied than it might seem at first glance: it turns out that only two questions are required (!).

For the first question, let's take $a_1 = ...=a_{10}=1$. In answer to this question we get the sum $x_1+...+x_{10}$, which is greater than each of $x_1, \dots, x_{10}$ (that's all that matters). Let us now take $m$ such that the number written as one with $m$ zeros is not less than the answer to the first question, and ask the following question: $a_1=1, a_2=10...0, a_3=10...0, a_4=10...0, ..., a_{10}=10...0$. In response, we will receive a long number, in which the first intended number will be written in the last $m$ digits (to which, perhaps, several zeros are assigned at the beginning), in the next ones from the end

⟦folio 30⟧

m digits - the second number, then the third, etc.

Example: $x_1=4, x_2=11, x_3=21, x_4=14, x_5=9, x_6=7, x_7=1, x_8=12, x_9=3, x_{10}=11$. Answer to the first question: 90. Second question: $a_1=1, a_2=100, a_3=10000, \dots, a_{10}=10...0$.

The answer to the second question: 11031201070914211104. Taking two digits from the end, we get the intended numbers: 04, 11, 21, ...

Three significant works of Albert Einstein
(For the beginning, see p. 26)

molecules hitting it from the opposite side, and then a certain force acts on the particle, causing it to move. The direction of this force changes randomly, so the direction of movement of the particle also changes randomly. Einstein developed a simple but very powerful method that made it possible to “follow” a particle making this kind of movement.

This work of Einstein is one of the most convincing confirmations of the molecular kinetic theory.

The third in order, but not in importance, Einstein’s work, published in the same journal “Annalen der Physik” and in the same 1905, is called “Towards the electronic science of moving bodies.” The article was received by the editor on June 30, 1905. This work provides a practical, complete presentation of the special theory of the relative theory of the relative.

(However, in the same year and in the same journal, another short and important work by Einstein was written, “Does the inertia of a body depend on the energy it contains?”, dedicated to the deducible correspondence between the mass of a body and its energies.)

It is difficult to talk about the relative theory of relative theory briefly, and a detailed story is impossible due to the limited space of this article. Let us only add that with the advent of this theory is associated a radical revision of the basic concepts that form physics, such as time, space, length, duration, energy, momentum, mass, etc. In terms of its significance for the natural world, the appearance of the theory of the relative theory of the relative theory can be compared with the appearance of Newtonian mechanics two centuries earlier.

It seems incredible that one person could make three columns in a year, healing the consequences of work in three different areas of physics (quantum theory of radiation, molecular-kinetic theory, relative theory).

It should be said that although we now highly appreciate Einstein's work in 1905, not everyone then immediately understood its significance. In particular, the founder of quantum physics, Max Planck, must agree with those ideas about the nature of light that were expressed by Einstein in the first of three meanings of his 1905 paper. However, some of the greatest physicists of that time recognized them immediately. Marie Curie was also average:

“I sincerely admired the works that were published by Mr. Einstein on issues of modern theoretical physics. I think, however, that physiomatists recognize that this is work of the highest class. In Brussels at a scientific competition, in which they participated and the depth of knowledge! We know that Mr. Einstein is still very young, but this gives us the right to place the highest hopes on him, to see in him one of the greatest theoretical future figures.”

These hopes were fully justified.

V. M. Bolotovsky
