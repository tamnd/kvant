---
id: 1982-8-pervin-odnazhdyi-vecherom-v-seme-programmista-c5de1e53
issue: kvant_1982_8
year: 1982
number: "8"
title: One evening in the programmer's family
authors:
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 64
page_labels: 60, 62
tag: C9YW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 16dc2cf6a326b881c3ddb0b563ff7774d96675ac6d80ce6a8a2f728c1792f093
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/17_pervin-odnazhdyi-vecherom-v-seme-programmista-c5de1e53.md
source_content_sha256: 9d03b6d6b154c2ca323ed611c9b2a6280e2653631893415338d1f53c3a6a422b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 60⟧

One evening in the programmer's family

Programmer Ferstov has four children - Nadya, Timur, Egor and Dina. They are all interested in programming. On the evening in question, dad looked into the children’s room.

— Do you want to take this one apart on programming?
— A study on programming? - the guys asked in unison. - Do such things exist?
- Of course, there are. These are small programs that contain some tricks. The solution to this is to compile a program on a given topic, or to find a carefully hidden error, or to check the actions of a ready-made program. This is exactly what I want to offer you. In the program variables i: integer;
array m[1:2] : int;
i ← 1; m[1] ← 4; m[2] ← 5;
zilch(m[i]);
you see a call to the procedure zilch, which has the following description procedure zilch(x:int);
m[i] ← m[i] + 1;
i ← i + 1;
x ← x - 1
end;
Please determine what values ​​m[1] and m[2] will get as a result of this program.
- Is that all?
- All.
- But it’s so simple...
The father did not have time to answer. The phone rang.

- Ferstov is listening!
At the other end of the line, someone was in a hurry to tell about the latest events in Ferstov’s laboratorium. His face is serious.
- Fine. I'll be there now. Let's figure it out.
“Guys,” he said to the children, “I’m running to the Computing Center on time.” There is an error in my transport. I'll find it, fix it, and come back right away. In the meantime, help with the programming.
And before the children even had time to ask him their questions, Ferstov was already running up the stairs, buttoning his jacket as he went. The guys began to discuss the task.
- What kind of country language is this? - said Nadya. — It’s not too bad for Pascal: all the keywords are Russian. And not the Rapier - look how funny the arrows are.
“There’s nothing to be surprised at,” answered the judicious Yegor. - There are different languages. Although there are unusual symbols here, everything is clear: the arrow from right to left is an assignment like in Pascal, only designated differently; A binary between integers in square brackets separates the bounds of index changes in the array. So let's get down to business right away.
Everyone armed themselves with a pencil and paper, and for some time businesslike silence reigned.
- Ready! - Timur was the first to shout. - m[1] is equal to 3, and m[2] is equal to 5.
“Nothing of the kind,” objected the elder sister Nadya, “both quantities, m[1] and m[2] are equal to five.”
“You are both wrong,” said Yegor. — The answer is: m[1] = 4, m[2] = 5.
The youngest, Dina, a little timid before the authority of her older sister and brothers, said quietly:
— And I got m[1] = 5, m[2] = 4.
Fortunately, dad actually returned quickly. The children immediately surrounded him, vying with each other to offer their solutions.
“Let’s take things in order,” suggested the report. - Come on, eldest, start!

⟦folio 62⟧

programs stand $m[i]$. By the time the last statement of the procedure $n_{uuik}i=2$, and; therefore, the last statement of the procedure will be executed like this:

$$m[2] \leftarrow m[2] - 1.$$

And since $m[2]$ was set at the beginning of $m[2]=5$, then after the completion of the procedure and the entire program $m[2]=4$.

With $m[1]$ it is quite simple: having been set at the beginning of the program $m[1]=4$, this value is increased by 1 by the action of the first statement of the procedure $n_{uuik}$.

The explanations were written down, and the children silently looked at each other: “Daddy will reward one of them!”

- Well done, guys! You did a good job. You are all right. The fact is that you knew nothing about the language in which the program was written, and therefore, the method of passing parameters allowed in this language. By the way, such a language does not exist in reality: I invented it specifically for our management. And in each of the implementations of existing languages, one or more permitted ways of passing parameters is always defined. Thus, in the familiar Rapier, parameters from the calling program to the called procedures can be passed only by value. And in the ALGOL-60 language, I also use this method by writing (sometimes it is also called transfer by name). Moreover, passing by spelling is considered in ALGOL to be the most natural way of communicating between procedures, so passing by spelling is assumed for passed parameters “by default”. And in those cases in which it is necessary to use passing by value, before the names of the passed parameters when describing them in the called ALGOL-60 procedures, the keyword `value` (value) must be written.

In a language such as Algol-$W$, among several acceptable ones, the method that Timur used is the method of conveying the result value. Parameters passed to a procedure in this way are marked in its header with the keyword `value-result` (value-result). Forteran, for example, allows the method of passing parameters by address (or sometimes called passing by reference).

In Pascal, parameters are most often passed by value (which “by default” is not specifically noted in any way), and when passing by reference is used - passing a parameter-variable, before the names of the corresponding parameters it is necessary to write the words `var` in the header of the procedure description. Read about it in Lesson 20 of Coding Correspondence School. And if you want to learn more about the various methods of passing parameters, then I will recommend you, for example, the book by T. Prat “Programming Languages: Development and Implementation,” published by the Mir publishing house in 1979. You will find it on the shelf above my desk.

I must tell you that the variety of results you received is explained not only by different ways of passing parameters. Then, when the parameter is a simple variable (and not indexed, as in our example), all methods will give the same result. And only complex data structures are transmitted in different ways in different ways.

Let's summarize. Before programming access to procedures, you need to know what methods of passing parameters are allowed in the selected language (and perhaps even change the choice of language based on the transmission method you prefer); you also need to know the rules for formatting the corresponding method of transmission in the language. Clear?

“I see,” Nadya answered for everyone. The rest according to the book

And Yegor said words that completely ordered his father:

- You know what: I’ll come up with this one for you on programming too. About the recursive procedure!

- Well done, come on. Only this new one is for tomorrow. It's late today.
