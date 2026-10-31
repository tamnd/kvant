---
id: 1976-7-orlov-poisk-predmeta-2205ca74
issue: kvant_1976_7
year: 1976
number: "7"
title: Search for an item
authors:
  - Орлов А. И.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 57
page_last: 59
page_labels: 55-57
tag: N087
lang: en
source: kvant_digital
extraction: vision
content_sha256: bddabfefcdf0752f4c7e405b8f3065f866f9ffc022e52ff97a9e5e3f3dabdd08
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/25_orlov-poisk-predmeta-2205ca74.md
source_content_sha256: f8bd252def0238e66b7e4fc8a26a55d37b3c61ddfa7eb9e7b3eeed39775c5612
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

A. Orlov

Ponsk subject

Apartment number

Listen to the story my neighbor Lyusya told me *).

— Our new eight-story house has two entrances. The doors of four apartments open onto each cell. Yesterday the guys met me in the yard and asked me what apartment I live in. I replied:
- You can guess it. He can ask me questions, just keep in mind that I will only answer “yes” or “no.”
One boy immediately said:
- There is nothing wrong. I will ask you if it is true that you live in apartment No. 1, No. 2, No. 3, No. 4, ...
..., No. 63, until you say yes.
And if you say “no” all the time, then you live in apartment No. 64.
I'll need more than sixty-three questions.

But then the girl interrupted him:
- Just think, sixty-three!
Thirty-two questions is enough for me! First I found out which entrance you live in. I’ll ask: “Do you live in the first entrance?” If you answer “yes,” that means the first; If you answer “no” - in the second. And then I’ll go through all the apartments in the entrance in order.
“And fourteen is enough for me!” the smallest one shouted joyfully

from the entire company. “I found out the floor in seven questions, and the apartment on the floor in another seven!”

“What do you think,” Lucy asked me, “how many questions will it take to find out the apartment number?”

I immediately answered Lyusya: “Five questions are not enough, but six are enough.” First I asked:
— Is it true that you live in the first entrance?

Lucy answered: “No,” and I realized that her apartment was located in the second entrance. The second question was trickier:
— Is it true that you live below the floor?
- Yes.
- Is it true that the third is lower?
- No.
- By a third?
- No.

This means that Lucy lives in the second entrance on the fourth floor. I have two questions left for four “suspicious” apartments - No. 45, No. 46, No. 47 and No. 48 (it’s easy to calculate that the doors of these four apartments open onto the fourth floor landing in the second entrance).

— Is it true that your apartment number is greater than 46?
- No.
— Do you live in apartment No. 45?
- No.
“So you live in apartment No. 46,” I said triumphantly.

Did you understand why so few 问卷s were needed? Each of my questions divided the numbers of “suspicious” apartments (those, among which there are numbers for which the answer is “yes”, and numbers for which the answer is “no”. In any case, the number of “suspicious” apartments decreased exactly by half.

It can be proven that it is impossible to achieve certainty in five questions.

⟦folio 56⟧

The following table will help us here:

```
0 0 0 0 0
0 0 0 0 1
0 0 0 1 0
0 0 0 1 1
0 0 1 0 0
1 1 1 1 0
1 1 1 1 1
```

We will write down Lucina’s answers using the numbers 1, 0. If she answers “yes”, we will write “1”, and if no, then “0”. We will write the first answer in the units section, the second in the tens section, and so on. Then we can write down any combination of five answers in ones and zeros; it will be a five-digit number, each digit of which is a zero or a one. Let's write out all such numbers in ascending order - we get our table. There are 32 numbers in total.

Now let's say that we always manage to guess the apartment in five questions. This means that, knowing what five-digit number is made from zeros and ones, we can accurately name the apartment number. But since we have 32 five-digit numbers, we can name only 32 apartments, and not 64, as in the conditions.

Phone number

You want to find out my seven-digit phone number by asking me questions to which I will only answer “yes” or “no.” Come up with a way to guarantee success in the fewest number of questions.

One counterfeit coin

There are 26 identical coins. Among them, one is fake, it is lighter than the rest. There are cup scales (without pointer or weights). What is the smallest weighing number that can be used to find a counterfeit coin?

This problem can be solved in exactly the same way as the previous one. Only you should try to reduce the number of “suspicious” coins by more than half,

⟦folio 57⟧

a in three: after all, each weighing has three possible results - the left cup outweighed, the right cup outweighed, the cups balanced. Therefore, first we put 9 coins on each cup. If the left cup is overweight, then the counterfeit coin is on the right cup; if the right cup outweighs, then the counterfeit coin is on the left cup; if the cups are balanced, then the counterfeit coin is the average of the coins not placed on the scales. This means that after the first weighing, 9 or even 8 “suspicious” coins remain. Then we’ll put three “suspicious” coins on each cup. After the second weighing, three or two “suspicious” coins remain. By placing one of them on the cups, we will find out which coin is counterfeit.

There is no way to definitely detect a counterfeit coin in two weighings, because any of the 26 coins could be counterfeit, and there are only 9 weighted outcomes of the two weighings (each of the three outcomes of the first weighing can be combined with each of the three outcomes of the second), and 9 is less than 26.

Discussion

Do you understand what our tasks have in common? There are apartments, there are coins; there are questions, here there are weighings. And yet they have a lot in common. Both here and there we ask questions: in one case to Lucy, in the other to Libra, and we receive answers: in one case from Lucy, in the other from Libra.

Scientists do the same thing when they conduct an experiment - they ask questions. There is a well-known expression: “A physical experiment is a question that we ask nature.” Of course, not only physicists, but also chemists and biologists—everyone who studies nature—can say this about their experiments. And if you want to be real mathematicians, then you need to be able to ask questions.

Our problems relate to one of the modern branches of mathematics - information theory. For example, what is the fastest way to convey a message about a telephone number if we have only two types of signals at our disposal? This is a typical problem in information theory. You can read more about this theory in the book “Probability and Information” by A. M. Yaglom and I. M. Yaglom (M., “Nauka”, 1973).

Two more fake coins

a) In front of you lie six identical-looking coins, two of which are counterfeit (each of them is 1 e heavier than the real one). You also have a scale without a pointer or scale. These scales, however, are not very sensitive and react to a weight difference of at least 2 e. Find a way to identify both counterfeit coins in four weighings.

6) There are six identical coins. Four of them are real, 4 e each, and two are fake, with a total mass of 8 e: one is slightly heavier, the other is lighter. What is the smallest number of weighings on a cup scale without a pointer or scale required to weigh both counterfeit coins and determine which one is lighter and which one is heavier?

Universal griri

Select the masses of four griri so that they can be used to measure any number of grams from 1 to 40 on a cup scale. (Griri can be placed on both cups.)

Guessing puzzles with obstacles

You will again guess the seven-digit phone number, but now I can give the wrong answer to one of your questions. What questions will you ask then, and what is the least number of questions you will need?
