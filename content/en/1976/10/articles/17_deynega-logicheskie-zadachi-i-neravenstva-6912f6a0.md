---
id: 1976-10-deynega-logicheskie-zadachi-i-neravenstva-6912f6a0
issue: kvant_1976_10
year: 1976
number: "10"
title: Logic problems and inequalities
authors:
  - Дейнега А. В.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 59
page_last: 61
page_labels: 57-59
tag: 4TND
lang: en
source: kvant_digital
extraction: vision
content_sha256: 99901eaa0f1db93552078ef751aa4ee02cff94955b248b0e9557c869975cec31
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/17_deynega-logicheskie-zadachi-i-neravenstva-6912f6a0.md
source_content_sha256: e4b82ebf33880903ea9940a02e22093e03bf864ea168d197a99950ec28493926
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

Logic problems and inequalities

Having completed his homework, fifth-grader Voloda began solving logical problem No. 1291 from the textbook “Matematika, 5” (M., 1976), assigned for homework on a mathematical circle. Here she is.

Three runners took part in the modern bez: Avdeev, Vasiliev and Semenov. First, one spectator said that Avdeev would be the first to arrive, the second - that Semyonov would not be the last, and the third - that Vasilyev would not be the first to arrive. After the race, it turned out that one spectator had left, and the other two had made a mistake. How did the singing end?

Time passed, and Voloda still could not solve the problem. Finally, he turned to his older sister Natasha for help.

- Think for yourself! - said the sister, minding her own business.

- So I kept thinking... please... I don’t turn to you often...

“Okay,” according to Natasha. “But let’s solve the problem using inequalities.” Fine?

- I don’t mind, but how is it - inequality? The teacher didn’t show it like that, we solved logical ones... - Voloda was surprised.

- So what? And we will decide in our own way. First, let’s denote the place occupied by Avdeev by a, by Vasilyev by b, by Semenov by c. There were three runners, so each of them could take 1st, 2nd or 3rd place.

This means that a, b and c can only be equal to 1, 2 or 3. Think about how to write this in the form of inequalities? Between what natural numbers is a located? b? c?

Voloda thought and wrote down: 1 ≤ a ≤ 3, 1 ≤ b ≤ 3, 1 ≤ c ≤ 3.

“That’s right,” said the sister. “Now let’s try to write down the conditions of the problem using the quantities a, b and c.” The problem says “Avdeev will arrive first,” so a = 1. Then “Semyonov will not be the last,” which means he can take 1st or 2nd place, therefore, as you yourself already agreed, we write c = 1 or c = 2. How to express this using inequalities?

“I understand,” said Voloda. “We must write it like this: 1 ≤ c ≤ 2. Then the sentence “Vasiliev will not arrive first” will be written similarly: 2 ≤ b ≤ 3.”

- Very good. Let's write down everything we got together:

$$\begin{cases}
(1) a = 1, \\
(2) 1 \leq c \leq 2, \\
(3) 2 \leq b \leq 3.
\end{cases}$$

We will call such a record a “system”. But this system does not yet express everything in the problem. For example, we have not yet used the fact that “one spectator left, and the other two made a mistake.” How can we write this data using inequalities?

- Inequalities?... I can’t imagine...

⟦folio 58⟧

Look. The words “guessed” and “wrong” express opposite logical “actions”; they reflect each other:
“guessed” - “not wrong”
“I was wrong” - “I didn’t guess.”
As we can see, this is done using private NOTs.
As for our task, let’s create a table:

| Direct statement | Opposite statement |
| :--- | :--- |
| And equal to $B(A=B)$ | A is not equal to $B(A \neq B)$; $A > B$ or $A < B$ |
| And more $B(A > B)$ | And no more $B(A \leq B)$ |
| And less than $B(A < B)$ | And no less than $B(A \geq B)$ |
| Opposite statement | Direct statement |

Using this table, Natasha continues, we can translate the phrase “one of the three spectators guessed the place occupied by the runner, while the other two were mistaken” into the language of inequalities. Let's try to do it ourselves.
Volodya coped with this task, we present his notes.
If viewer I guessed right, but spectators II and III were wrong (see system (*)):

$$\begin{cases} a = 1, \\ c = 3, \\ b = 1. \end{cases}$$

If viewer II guessed correctly, but spectators I and III were wrong:

$$\begin{cases} 2 \leq a \leq 3, \\ 1 \leq c \leq 2, \\ b = 1. \end{cases}$$

If viewer III guessed correctly, but spectators I and II were wrong:

$$\begin{cases} 2 \leq a \leq 3, \\ c = 3, \\ 2 \leq b \leq 3. \end{cases}$$

“That’s right,” said the system. “Now look: the first system is no good...

- Yes, this is immediately obvious: there are $a = 1$ and $b = 1$ in it, but Avdeev and Vasiliev could not take the same places. And the second... it follows from it that $b = 1$, $c = 2$, $a = 3$. She's good! Let's see now... who took first place? Nobody? This means that the third system is not suitable either.

So,” Volodya proclaimed, “a perfect record with the following result: Vasiliev took first place, Semenov - second, Avdeev - third.

“Well, now one more task,” said Natasha, taking out some book *).

Anya, Varya and Klava went to the demonstration. One of them was in

*) I. Ya. Depman, Stories about old and new algebra, L., 1967, p. 122.

⟦folio 59⟧

red dress, friend - in white, premium - in blue. When asked what kind of dress each girl was wearing, they gave the answer: Anya was in red, Varya was not in red, Klava was not in blue. In this answer, one of the three statements is true, two are false. What dress did each girl wear?

- And also with the help of inequalities? - asked Voloda.
- Certainly! - answered the sister.
“But I don’t know what’s bigger—blue, red or white,” Voloda was indignant, “and in general this is a completely different task, nothing like the previous one.”
“Okay, I’ll give you a little help,” said Natasha. “Let’s number the colors.” The red empty color will be the first, the white will be the second, and the blue will be the third.
“Ah... Then I can probably solve the problem,” Voloda said after a little hesitation. “I will denote by a the color of Anya’s board, by b the color of Varya’s board, and by c the color of Klava’s board.” Now I will write down the conditions using inequalities
$$\begin{cases} a=1, \\ 2 \leq b \leq 3, \\ 1 \leq c \leq 2, \end{cases}$$

- Look, Natasha! But it turned out to be the same system! And in the same way, we need to consider three cases in which one statement is true and the other two are false. This means that without solving the problem, I can immediately say that a=3, b=1, and c=2. Anya was in a blue dress, Varya was in red, and Klava was in white!

“That’s absolutely right,” answered the sister. “Perhaps the most important advantage of mathematics is revealed here: completely different problems written in its language can become one and the same problem.” Thus, having solved one of them, we obtain a solution to the remaining problems. When you grow up, you will see that various problems from physics, chemistry, economics, biology often turn out to be the same mathematical problem.

Well, now solve two more problems without my help.

1. After writing a test in mathematics, the sisters told their parents:
Sveta A.—This time I wrote “5”.
Lyuda A.—I didn’t write “3.”
Ira.—I didn’t write “5.”
After checking the work, it turned out that the sisters received different positive ratings and out of three statements, one was correct, the rest were incorrect. What grades did Sveta, Lyuda and Ira get for the test?

2. Three brothers have the ranks of captain, senior sergeant. Of the three statements “Alexey is a sergeant major,” “Vladimir is not a sergeant major,” and “Semyon is not a sergeant,” only one is true. What are the rank issues for the brothers?
