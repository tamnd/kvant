---
id: 1973-4-kordemskiy-etomu-vidu-zadach-bolee-1600-let-5e9c80ef
issue: kvant_1973_4
year: 1973
number: "4"
title: This type of problem is over 1600 years old
authors:
  - Кордемский Б. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 43
page_labels: 38-41
tag: IHY9
lang: en
source: kvant_digital
extraction: vision
content_sha256: ba41c95432297e65b87c296d8dc62755cbfc0a5f590ad9ad5dc93fc00ed3409d
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/09_kordemskiy-etomu-vidu-zadach-bolee-1600-let-5e9c80ef.md
source_content_sha256: 4428854d1d86f94823418fd208783314e1652734c5ed7f296a0301ac10a31e00
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

This type of problem is over 1600 years old

B. A. Kordemsky

The plot and form of recording the problem changed, solutions were accumulated, but the essence remained unchanged: find the integer (usually natural) $x$ and $y$, satisfying the equation
$$ax + by = c$$
(1)
With. given by integer coefficients $a$, $b$ and $c$.

Maybe $c$ is Sheherezda's 1001 tales, and we are interested in how many nights it will take Sheherezda to tell all her tales if she tells 5 tales in $x$ nights, and 3 tales in $y$ nights.

Fabulous ones will obviously require $x+y$ nights, where $x$ and $y$ are the natural roots of the equation $5x+3y=1001$.

Or maybe $c$ is 10 $p$. 01 $\kappa$., which some spent on $x$ trips by bus (5 kopecks per trip) and $y$ trips by tram (3 kopecks per trip). The answer to the question of how many trips have been made is contained in the same equation $5x+3y=1001$.

The roots of this equation also tell us about those points on the line

Fig. 1.

$5x+3y=1001$ (see figure), both coordinates of which are natural numbers (or integers in some other problem).

Equations in which only integer values ​​of the unknowns are isolated from the set of solutions are often called Diophantine in honor of the famous mathematician of the 2nd-3rd centuries. Diophanthus from Alexandria.

Theoretical issues related to the conditions for the existence of integer, in particular, natural solutions to an equation of the form $ax+by=c$, are considered in the article by V. N. Vaguten “Euclidean Algorithm and the Basic Theory of Arithmetic” («Kvant» No. 6, 1972). We will not study this theory, but will attend to the solution of a specific equation $5x+3y=1001$ in order to show, using this example, various techniques that help find integer solutions to the equation *).

Solution using the “inventive schoolboy” method

We divide both sides of the equation $5x+3y=1001$ by a smaller coefficient: $\frac{5}{3}x+y=\frac{1001}{3}$; on the right and follow the whole parts:
$$x+\frac{2}{3}x+y=333+\frac{2}{3};$$
$$x+y+\frac{2(x-1)}{3}=333.$$ (2)

Since $x$ and $y$ are integers, then $\frac{x-1}{3}$ must also be integer; we put $\frac{x-1}{3}=t$; then $x=3t+1$. Substituting into (2), we get
$$3t+1+y+2t=333; y=332-5t.$$

In the mentioned article, V. N. Vagutena proves that the expressions obtained for $x$ and $y$ are “general solutions”, that is, they contain

*) Let us only recall that the existence of integer solutions to equation (1) guarantees the GCD conditions ($a,b)=1$, so that equation $5x+3y=1001$ has solutions in integers.

⟦folio 39⟧

contain all integer solutions to a given equation.

Giving the parameter $t$ the value $t = 0, 1, 2, \dots, 66$, we find 67 pairs of possible natural roots of this equation.

Now let us further assume that Scheherazade would like to distribute her thousand and one tales among as many nights as possible *). This requirement is satisfied by max $(x + y)$, which is the greatest of the sums of pairs of roots of the equation. We have $x + y = 333 - 2t$; Obviously, max $(x + y)$ is achieved at $t = 0$.

So, Scheherazade will tell her tales in at most 333 nights, if she tells 3 tales for 332 nights and 5 tales for only one night. She can shorten the period of her “work” and bring it to 201 nights, if only 2 times (with the maximum ability of an inventive schoolchild), you received $x + y + \frac{4y - 1}{3} = 77$. How should we now calculate and act in order to express the approach first $y$, and then $x$ through the whole $t$?

Solution using the method of an “inventive mathematician” **)

For the equation $ax + by = c$, the procedure is as follows: find the remainder $m$ when $a$ is divided by $b$ (let $a > b$) and the remainder $n$ when $c$ is divided by $b$; if $n = 0$, then we immediately get $x = bt$, $y = \frac{c}{b} - at$, $t = 0, \pm 1, \pm 2, \dots$;

*) Of course, provided that every night she tells either three or five fairy tales.
**) The inventor of the method, Taylor L. F., “Numbers”, London, 1970, did not give it a name.

if $n \neq 0$, then multiply $m$ successively by 1, 2, ..., $(b - 1)$ and write down the sequence of remainders from dividing these products by $b$. The resulting sequence will contain the number $n$ (if it is not there, then there will be no integer solution to the equation). The number of the place occupied by the number $n$ in the sequence of residues is one of the possible values ​​$x$.

Let's apply this method to the equation $5x + 3y = 1001$. We have: $m = 2$, $n = 2$, multiply $m = 2$ by each member of the sequence {1; 2}, we get {2; 4}; divide by 3 and write down the remainder: {2; 1}. We note that the number $n = 2$ occupies the first place in this sequence of remainders, therefore $x = 1$. This determines the corresponding value $y = 332$.

An easy and quite general way to solve linear indeterminate equations in two unknowns for number purposes!

But the “inventive mathematician’s method,” unlike the previous method, gave us only one pair of roots: (1; 332). Method defect? Not at all. Consider the formulas for the “general solution” of the problem obtained “by the schoolboy method”: $x = 1 + 3t$, $y = 332 - 5t$.

《Particular solutions》 $x_0 = 1, y_0 = 332$ are the same in the general methods, and the coefficients for $t$ (3 and 5) are determined by the coefficients of the solution to the equation: $3 = b; -5 = -a$. And this is not a coincidence, but a pattern: if $(x_0, y_0)$ is any integer solution of the equation $ax + by = c$, and $a$ and $b$ are coprime, then all its integer solutions are determined by the formulas: $x = x_0 + bt$, $y = y_0 - at$, $t = 0, \pm 1, \pm 2, \dots$.

Solution by “model comparison method”

This is a nice and often fastest way to find integer solutions to the equation $ax + by = c$.

For our whole it is enough to recall that the statement $a \equiv b$ (mod $m$)

⟦folio 40⟧

is equivalent to $a-b$ being divided by $m$, or $a=b+km$ ($a, b$ and $k$ are integers, $m$ is natural).

Further, if $a \equiv b$ (mod $m$), then it is true that $a \equiv b+km$ (mod $m$), where $k$ is any integer $^*$). Let, for example, $3x \equiv 2$ (mod 5), then $3x \equiv 2+2\cdot 5$ (mod 5), $3x \equiv 12$ (mod 5) and $x \equiv 4$ (mod 5).

Note that dividing both sides of the comparison modulo $m$ by a common factor $q$ is only allowed if $q$ and $m$ are relatively prime numbers.

Preliminary example. Let the comparison $11x \equiv 2$ (mod 23) be solved. It is impractical to add 23 to the right side until you get a multiple of 11. You have to look for a lower path. For example, this is suitable: write that $22x \equiv 4$ (mod 23), then subtract $23x$ from the left side; we get $-x \equiv 4$ (mod 23), $x \equiv -4$ (mod 23) and finally $x \equiv 19$ (mod 23).

To solve the equation $5x+3y=1001$ “by modulo comparison method” you need to act like this: $3y=1001-5x; 3y=1001$ (mod 5). Since $1001=200\cdot 5+1$, then $3y \equiv 1$ (mod 5), or $3y \equiv 6$ (mod 5); $y \equiv 2$ (mod 5), therefore $y=2+5k$ ($k=0, \pm 1, \pm 2, \dots$). It is easy to see that this solution is equivalent to getting early

$$y=332-5t \ (t=0, \pm 1, \pm 2, \dots).$$

The solution “by modulo comparison method” should be done like this: $3y=1001-5x; 3y=1001$ (mod 5). Since $1001=200\cdot 5+1$, then $3y \equiv 1$ (mod 5), or $3y \equiv 6$ (mod 5); $y \equiv 2$ (mod 5), therefore $y=2+5k$ ($k=0, \pm 1, \pm 2, \dots$). It is easy to see that this solution is equivalent to getting early

$$y=332-5t \ (t=0, \pm 1, \pm 2, \dots).$$

*) A lot of useful information about comparing integers by modulo is given in the articles by A. A. Egorov “Comparison by modulo and arithmetic of remainders” («Kvant» No. 5, 1970), M. I. Bashmakov “Do you like to tinker with integers” («Kvant» No. 3, 1971) and above the articles of V. N. Vaguten.

equations, in “virgin land”:

$$\frac{a}{b} = [a_0; a_1, a_2, \dots, a_n],$$

calculate the numerator and denominator of the penultimate “matching” fraction $\frac{P_{n-1}}{Q_{n-1}}$ directly or using recurrence formulas

$$P_{k+1} = P_k \cdot a_{k+1} + P_{k-1};$$

$$Q_{k+1} = Q_k \cdot a_{k+1} + Q_{k-1},$$

where $P_0=a_0$, $Q_0=1$ and $P_1=a_0 \cdot a_1+1$ and $Q_1=a_1$, $k=0, 1, 2, \dots$.

The solution to the problem is completed by applying ready-made formulas*), representing the general solution of this equation

$$\begin{cases} x = (-1)^{n-1} \cdot c \cdot Q_{n-1} + b \cdot t, \\ y = (-1)^{n} \cdot c \cdot P_{n-1} - a \cdot t, \\ t = 0; \pm 1; \pm 2, \dots. \end{cases}$$

Let's look at equation $5x+3y=1001$ one last time. Let's do a detailed transformation of the number $\frac{5}{3}$ into a continued fraction:

$$\frac{-5}{3} \left| \frac{3}{1} \right| \dots a_0=1,$$

$$\frac{-3}{2} \left| \frac{2}{1} \right| \dots a_1=1,$$

$$\frac{2}{2} \left| \frac{1}{2} \right| \dots a_2=2,$$

whence $\frac{5}{3} = [1; 1, 2]$. Let's make a “suitable” fraction

$$\frac{P_0}{Q_0} = \frac{a_0}{1} = 1; \quad \frac{P_1}{Q_1} = a_0 + \frac{1}{a_1} = \frac{2}{1};$$

$$\frac{P_2}{Q_2} = a_0 + \frac{1}{a_1 + \frac{1}{a_2}} = \frac{5}{3}$$

(the last suitable fraction is not needed, in addition, it is always equal to given

*) The derivation of these formulas can be found in special textbooks, or, for example, in the book “Encyclopedia of Elementary Mathematics”, book one, 1951 (article by A. Ya. Khinchin “Elements of Number Theory”). Continued fractions are also discussed in N. M. Beskin’s article “Continued Fractions” («Kvant» No. 1, 1970).

⟦folio 41⟧

noah fraction; we performed the calculation only to fill in the way of indefinitely composing “fitting” fractions).

Since here $n = 2$, the numerator $P_{n-1}$ and denominator $Q_{n-1}$ of the penultimate “suitable” fraction are equal, respectively

$$P_{n-1} = P_1 = 2; \quad Q_{n-1} = Q_1 = 1.$$

Everything is ready to apply formulas (3): $x = -1 \cdot 1001 \cdot 1 + 3t, y = 1 \cdot 1001 \cdot 2 - 5t, t = 0, \pm 1, \pm 2, \dots$.

Finally, $x = -1001 + 3t, y = 2002 - 5t, t = 0, \pm 1, \pm 2, \dots$.

By the appearance of the solution, it seems that a different result was obtained again, not being preserved with the previous ones, but it is easy to detect its equivalence to all previous records of the general solution of the equation under consideration. Thus, $x = 1$ and $y = 332$ are obtained from here at $t = 334$. Now let's solve one more problem.

After the shipwreck

Five sailors landed on the island and by evening collected a bunch of coconuts. The division was postponed until the morning. One of them woke up at night, counted the dobtsych, treated the monkey to one nut, and took exactly $\frac{1}{5}$ portion of the remaining nuts, after which he went back to bed and quickly fell asleep. During the night, one after another, the rest of the sailors did the same; Moreover, each was unaware of the actions of his predecessors. The next morning they divided the remaining nuts equally, but this time there was no extra nut left for the monkey. How many nuts did the sailors collect?

Solution. Let us denote the required number of nuts by $x$. Expressing the sequential actions of sailors with equations, we get $x = 5a + 1; 4a = 5b + 1; 4b = 5c + 1; 4c = 5d + 1; 4d = 25y + 1$ (think about the meaning of the proposed equations).

This system reduces to one indeterminate equation

$$256x = 2101 + 15625y.$$

A structured solution in integers to this cumbersome equation will be a pleasant reward for patiently familiarizing yourself with the four proposed methods - you can choose the most effective one for a given task. The answer to this problem is: $x = 3121$ is the most possible natural value of $x$.

Sweeping. In M. Gardner's book "Mathematical Puzzles and Amusements" (World, 1971), which contains this problem, it is written that it "is among the most frequently solved, but most amenable to solution of Diophantine puzzles" (p. 234). When this problem appeared in one newspaper in 1926 (without a solution or an answer), then for 20 years after that there was a continuous flow of letters to the newspaper either with a request to provide an answer, or with a version of their own solutions.

Battles

1. Find integer solutions to the equation $10x + 21y = 23$ using each of the described methods.
2. Find a two-digit number whose total number of units is 13 less than triple the number of tens.
3. A number of excursionists, placed equally in 5 buses (each bus carrying no more than 54 people), were delivered to the station. There they were joined by 7 more people, and all the excursionists were distributed equally in 14 varonas. How many tourists were there in total?
4. Are there, for example, $13x - 5y + 96 = 0$ points with integer coordinates that do not exceed the number 10 in absolute value?
5. Let $n$ be a natural number. Find integer solutions to the equation

$$nx + (n + 1)y = 2n + 1.$$

6. It is necessary to pour 15 liters of liquid into bottles of 0.5 liters and 0.8 liters so that all used bottles are full. How many bottles of both are required?
7. Prove that for any odd $x$ the comparison $x^2 \equiv 1$ (mod 8) holds, that is, the square of any odd integer when divided by eight leaves a remainder of one.
