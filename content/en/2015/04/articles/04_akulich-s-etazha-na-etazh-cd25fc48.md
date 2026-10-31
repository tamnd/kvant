---
id: 2015-4-akulich-s-etazha-na-etazh-cd25fc48
issue: kvant_2015_4
year: 2015
number: "4"
title: From floor to floor
authors:
  - Акулич И. Ф.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 28
page_last: 29
page_labels: 26-27
tag: TBU5
lang: en
source: kvant_digital
extraction: native
content_sha256: e84bc43bd9527dee543f3439bb67698ebccaee342ee43e2fe70f9017fe0e078c
prompt_sha256: draft-1
translated_from: content/ru/2015/04/articles/04_akulich-s-etazha-na-etazh-cd25fc48.md
source_content_sha256: 5879422694ba2adf4d911004865ecdec743deaefcda8206587a25f73a01663fa
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

KVANT 2015/№4

The outer ring of the bearing rolls on balls (or rollers), which roll on the inner ring of the bearing. True, real bearings have one more part – it’s called a cage.

⟦figure⟧

Fig. 4

- Separator? “I know that,” Buratino was inspired. – When I was at Malvina’s

⟦column⟧

on her birthday, she treated her guests to strawberries and cream. She took milk, passed it through a separator, and cream was obtained. The separator separates the cream from the milk. Why is there a separator in the bearing? – The word “separator” can be used in different cases. The separator in a ball bearing is a kind of lattice that separates one ball (or roller) from another and directs their movement,” answered Papa Carlo.

- Now everything is clear to me! - Buratino exclaimed cheerfully.

From floor to floor

I. AKULICH

AS soon as HUMANITY BEGAN TO BUILD multi-storey buildings, numerous very diverse problems about them appeared. Perhaps the most spectacular was proposed to forensic doctors in 1914 by the unforgettable Joseph $Швейк^{1}$: “There is a four-story house, each floor has eight windows, on the roof there are two dormer windows and two chimneys, each floor has two tenants. Now tell me, gentlemen, in what year did the doorman’s grandmother die? The problem makes a strong impression, and perhaps that is why no one has solved it yet. However, we will not consider such problems - we will limit ourselves to those that can be overcome using a regular school mathematics course. For example, this one (author - M. Rolova): Five friends met on the first floor of a large building near the elevator. Zhenya said: “If you count from here, then I live higher than you, Vova, twice, higher than Petya three times, higher than Andrey four times higher and higher than Tanya six times.” “You noticed this very well,” Andrey responded, “and you, Petya, knock your dumbbells over my head more quietly.” What floor does Andrey live on? Let's estimate how many floors above the first Zhenya can live. This number (natural, of course) must be simultaneously divisible by 2, 3, 4 and 6, and therefore by their least common multiple, equal to 12. Therefore, the number of the floor on which Zhenya lives can be written as 12k + 1, where k is some natural number. From here it is easy to find out that Vova lives on the (6k + 1)th floor, Petya lives on the (4k + 1)th floor, Andrey lives on the (3k + 1)th floor, and Tanya lives on the (2k + 1)th floor. Somehow there are a lot of possibilities, but the dumbbells mentioned in the condition come to the rescue here. It follows from the condition that Petya lives directly above Andrey - i.e. 1 floor higher. And since (4k + 1) – – (3k + 1) = k, then k = 1. So, Zhenya lives on the 13th floor, Vova – on the 7th, Petya – on the 5th, Andrey – on the 4th and Tanya – on the 3rd floor. In the following problem, the elevator is not just mentioned, but also actively used (author - A. Spivak):

1 Jaroslav Hasek. "The adventures of the good soldier Schweik during the World War." Part one, chapter III.

The elevator in a 100-story building is damaged. It can either rise 79 floors up when you press one button, or go down 21 floors when you press another. When there are less than 79 floors above, the elevator will not go up, and similarly - down. The elevator departs from the first floor. What is the least number of times the buttons must be pressed for the elevator to return to the first floor? Let's estimate the number of clicks from below. Suppose we had to press the button to go up to 79 floors m times and press the button to go down to 21 floors n times. In total, the elevator thus rose from its original position to 79m - 21n floors. But the elevator eventually returned to the same 1st floor! Therefore 79m – 21n = 0, and 79m = 21n. Since the numbers 79 and 21 are relatively prime, m is divisible by 21, and n is divisible by 79. Therefore, their sum is at least 79 + + 21 = 100. This means that the button must be pressed at least 100 times. Due to the fact that 79 + 21 = 100, there is not a single floor to which you can arrive both from above and from below, and there is not a single floor from which you can leave both up and down. This means that no matter what floor we are on, we can say exactly which floor was the previous one and which will be the next. Therefore, for the passenger, the problem is solved automatically, and there is no need to even track which floor the elevator went to after the next press. All you need to do is press the buttons randomly (exactly one of the two will work every time) and count the number of movements. We will prove that after the hundredth movement you can go out - the goal will be achieved. We reason using the “by contradiction” method. Let's assume the opposite - that, having started from the 1st floor and completed 100 moves, we ended up not on the 1st floor. We have already proven that we could not have ended up on the 1st floor before the 100th move, so among the floors that the elevator visited after each of the hundred moves, there is no 1st floor. But then the elevator visited one of the remaining floors at least twice (there are only 99 of them, and there are more movements!). Let us choose the moment when the elevator first re-entered a certain floor. The previous floor from which the elevator arrived is uniquely defined, which means that the elevator visited it twice. It’s a contradiction – after all, we chose the moment when the second hit occurred for the first time. So the assumption

⟦folio 27⟧

"QUANTUM"

FOR

YOUNGER

was incorrect, and after the 100th move the elevator would be exactly on the 1st floor, which was what needed to be proven. From our reasoning it is clear that in the course of moving to a given goal (i.e., the initial position), the elevator will visit all floors of the house. This, by the way, allows us to conclude that regardless of the original floor, you can return to the same place in exactly 100 elevator movements. In addition to floors, problems about multi-storey buildings also involve entrances and apartments. In this case, by default it is assumed that floors are numbered from bottom to top, starting from $единицы.^{2}$ Entrances are also numbered in order. All landings (unless otherwise specifically stated in the text) are by default assumed to be identically arranged (with the same number of apartments on the floor), and the apartments are numbered in a row, starting from the first: first in the first entrance on the first floor, then on the second, third, and so on until the last floor, then the numbering continues from the first floor of the second entrance and further up... However, we all know this well from ourselves: after all, many of us live in high-rise buildings! It is this standard generally accepted scheme that allows you not to mention unnecessary details, which allows you to make the condition more compact. For example: Seventh-grader Petya moved to a new five-story house, whose 1st and 2nd floors in the 2nd and 3rd entrances are occupied by a warehouse. There are no more than four apartments on each landing. Petya's apartment number is 31. What floor does Petya live on? The problem was invented back in the seventies of the last century, when such houses were built to the right and $налево.^{3}$ But that’s not the point. The words “...no more than four apartments” are confusing. How much exactly? Unknown. There's nothing you can do, you'll have to consider all options. Well, let’s draw a schematic diagram of a five-story building and arrange the apartment numbers in it, while “capturing” the 31st apartment - after all, what’s next doesn’t interest us (we’ll simply paint over the spaces occupied by the ill-fated warehouse in black and skip the numbering). So, if there is one apartment on each floor, then it all looks like this:

2 Abroad in some countries - from scratch, but we are like that

no possibilities to consider $будем.^{3}$ There is nothing surprising: according to building codes, houses no higher than five floors do not require an elevator - an obvious savings!

SCHOOLCHILDREN

As you can see, if there are one apartment on each floor, then the 31st apartment is on the fifth floor. And if there are 2, 3 or 4 apartments, then accordingly we have:

⟦column⟧

Surprisingly, but true: in all cases, apartment 31 is located on the fifth floor. So the answer is clear, despite some vagueness of the condition. What, you didn’t like the use of brute force? Of course, the method is not very attractive, but no worse than others. However, it is not always required. For example, this problem (author - A. Kovaldzhi): Sasha invited Petya to visit, saying that he lives in the 10th entrance in apartment 333, but forgot to say the floor. Approaching the house, Petya discovered that the house was nine stories high. Which floor should he go to? The key to the decision is estimating the possible number of apartments per floor. If there are no more than three apartments on a floor, then in total there are no more than $3 \cdot 9 \cdot 10 = 270$ in ten entrances, i.e. There will be no apartment 330 in the 10th entrance. If there are at least five apartments, then in the first nine entrances there will be at least $5 \cdot 9 \cdot 9 = 405$ apartments, so again the 333rd apartment does not fall into the 10th entrance. This means there’s no escape – there are 4 apartments on each floor. Then in the first nine entrances there are 4 ◊ 9 ◊ 9 = 324 apartments, and in the 10th entrance the apartment numbers start from 325. And from here it is simply determined that Petya needs to go up to the third floor. But here is a task for which the main thing is to choose the right approach (author - A. Khamitdulin): Kolya and Vitya live in the same house. There are four apartments on each floor in all the entrances of their building. Kolya lives on the fifth floor in apartment No. 83, and Vitya lives on the third floor in apartment No. 169. How many floors are there in their house? Let the house have E floors. Let us denote the number of entrances from the first to the one in which Kolya lives (not counting the entrance in which he lives) by K. Then in all of Kolya’s previous entrances there are only 4EK apartments. Let’s add here the apartments of Kolya’s entrance up to and including Kolya’s own apartment. There are only $4 \cdot 4 = 16$ apartments on the four floors below it. How long is it on Kolya’s floor? It is not difficult to figure out that the largest apartment number on each floor is divisible by 4. Therefore, the most
