---
id: 2016-1-gribok-knop-pyatnadtsat-chelovek-na-sunduk-mertvetsa-48363d94
issue: kvant_2016_1
year: 2016
number: "1"
title: Fifteen men on a dead man's chest
authors:
  - Грибок С. В.
  - Кноп К. А.
rubric: osnovnye-stati
page_first: 11
page_last: 22
page_labels: 10, 11, 12, 13, 14, 15, 18, 20
tag: 9GJZ
lang: en
source: kvant_digital
extraction: native
content_sha256: e434e74eb1200035ac9746b8b735673fe9ea22b862892fe26d4a7da4610940a5
prompt_sha256: draft-1
translated_from: content/ru/2016/01/articles/01_gribok-knop-pyatnadtsat-chelovek-na-sunduk-mertvetsa-48363d94.md
source_content_sha256: 6322dd3c5001e1cdda808c6eaf4a5c7d4b38631908fec8637810f60873a566b9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Fifteen men on a dead man's chest

S. GRIBOK, K. KNOP

ALL THE TASKS WE ARE GOING TO TELL YOU ABOUT are connected by a common plot: a crew of pirates wants to divide the gold coins. But before we begin the story, we must take a closer look at pirate logic and its laws. i Under no circumstances does any of the pirates want to end up overboard the ship. i Pirates love gold very much. Each of them acts in such a way as to get as many coins as possible as a result of the division. i No pirate will ever collude with another pirate to jointly beat the others. “Every man for himself” is a rule that every pirate follows. i Every pirate is fluent in logic, and all his actions are logically justified. i All preferences, laws and rules of pirates (including this rule) are known to the pirates themselves. So…

Problem 1

He was an ordinary sea robber, bloodthirsty and merciless, deprived of even that grain of elementary honesty, which thieves are not deprived of. His henchmen, the sailors, were an unbridled crowd of thugs of various nationalities who did not recognize any discipline and any laws, except for one and only one - the law of a fair division of the spoils. R. Sabatini. The Chronicle of Captain Blood

Fifteen pirates from the brig Arabella - the captain, 13 sailors and a cabin boy - found a treasure: a chest containing 100 identical gold coins. To divide the money, the pirates used the following procedure: 1. The captain, as the eldest, proposes his plan for dividing the treasure. 2. All pirates vote on whether to accept this plan. Each of the pirates votes either “yes” or “no”.

In fact, the rigorous formulations of the coin division problems considered here (with the formalization of the rules according to which pirates can make decisions in the voting process) belong to game theory. These productions are very complex and are beyond the scope of our article. The article, by default, assumes that the division process is such that by the time of the next vote, each pirate knows what will happen after the proposal is not accepted. This allows us to reason “from the end”.

⟦column⟧

Brig "Arabella"

3. If all the pirates vote “yes”, then the plan is accepted and the money is divided according to the plan. If at least one of the pirates votes against, then the senior pirate is thrown overboard. After this, the next most senior pirate submits his plan, the pirates vote again, and so on, until finally one of the pirates' plan is accepted. Another feature of the Arabella pirates is their natural kindness. If a pirate's decision to vote up or down has no effect on whether that pirate gets thrown overboard or how much money he gets, then every pirate out of the goodness of his heart will always vote yes. How will the money be divided if pirates use this division method? Whose plan will be adopted? Solution. It is not difficult to figure out that the cabin boy has a simple way to ensure that all the coins go to him. He must vote against any other plan until either one of the pirates offers him all the money, or all the pirates except the cabin boy are overboard. Understanding this and wanting to save his life, the captain himself will offer the cabin boy all the money. Young will agree to this plan out of the goodness of his heart: if the money is already his, why vote against and ruin the captain. The rest of the pirates will also vote “for”, since they won’t get any money anyway. In all the following problems we use the “reverse move” to solve, i.e. reasoning from the end. Therefore, we invite readers to practice their ability to reason this way using simpler subjects.

⟦folio 10⟧

KVANT 2016/№1

Exercises

1. The captain divided the booty among the pirates. First he took 1/16 of all the coins and one more coin for himself. He gave the second pirate 1/16 of the remaining coins and two more, etc. To the fifteenth (the cabin boy) he gave 1/16 of the remaining coins and another 15 coins. It turned out that everyone received equally and all the coins were distributed. How many coins were there in total?

2.

Are you afraid we’ll stick a feather in your side? So answer me, damn it, How do you divide two pints of rum into three? A. Chernin

Three pirates are sitting at the table, in front of each is a mug, some of the mugs are filled with rum (perhaps not equally). The first one poured all his rum equally into the mugs of the others. Then the second one poured his rum equally to the other two (including the first one), and then the third one did the same. In the end, each mug contained the same amount of rum as there was at the beginning. How much rum is in each mug if there are two pints in total?

Now let’s talk about how another team of pirates from the sloop “Bestia” shared the treasure.

Problem 2

- If this brute decided to break his word, do you think he will stop halfway? As soon as we agree to one tenth, rest assured, he will immediately find an excuse not to give us anything at all. R. Sabatini. The Chronicle of Captain Blood

The pirates on the Bestia used a different method of sharing: 1. The oldest pirate tells the plan to the others. 2. All pirates vote on whether to accept the elder's plan. Each of the pirates votes either “yes” or “no”. 3. If at least half of the pirates vote “for”, then the plan is accepted and the money is divided according to the plan. If the majority of pirates vote against it, then the senior pirate is thrown overboard. After this, the next most senior pirate outlines his plan, the pirates vote again, and so on, until finally one of the pirates' plan is accepted. The pirates of the Bestia are the same good-natured guys as their colleagues from the Arabella. If a pirate's decision to vote up or down has no effect on whether that pirate gets thrown overboard or how much money he gets, then every pirate always votes up. How will 15 pirates from the sloop Bestia divide 100 coins? Answer: The older pirate will take all the money for himself. Solution. So, “let’s start from the end,” i.e. Let’s put ourselves in the place of the last of the pirates, assuming that it’s his turn. Let 14 plans have already been rejected. Then the cabin boy was left alone, and he takes all the coins:

0 0 0 0 0 0 0 0 0 0 0 0 0 0 100

Now that we have figured out what the cabin boy will do, we can mentally go back a step. Let it be 13

⟦column⟧

plans were rejected. The 14th pirate will vote for any of his plans, and this vote is already enough for him. Therefore, he may not share with the cabin boy and simply take all the coins for himself:

0 0 0 0 0 0 0 0 0 0 0 0 0 100 0

Let's take another step back. How will the 13th pirate reason? To stay alive, he needs two out of three votes. The 14th will be against it in any case, which means that support can only be expected from the cabin boy. But the 14th cabin boy will not leave anything, so even if you don’t give him anything, the peace-loving cabin boy will still vote “for”. Thus, the plan of the 13th pirate

0 0 0 0 0 0 0 0 0 0 0 0 100 0 0 passes by two votes (13th, 15th) against one. The next pirate (12th) also only needs two votes, and at the same time the votes of the 14th and 15th (who will not receive anything from the 13th) are already in his pocket. And since he no longer needs it, he also takes everything for himself: 0 0 0 0 0 0 0 0 0 0 0 100 0 0 0 Continuing to reason in a similar way, we find that the first pirate can also count on the votes of all the other pirates, except the second, for any of his plans. And since he wants to get more money, his plan will be the most greedy possible: 100 0 0 0 0 0 0 0 0 0 0 0 0 0 0

Exercise 3. How will the distribution of coins on the “Bestia” change if the pirates change rule 3: the plan will be considered accepted if all the pirates, except perhaps one, vote “yes”?

Problem 3

- We sent for you, Captain Pike, because we now have one, as they say, common interest - these are these values. They need to be divided as quickly as possible, without unnecessary delay, and then each of us can go wherever anyone needs. R. Sabatini. The Chronicle of Captain Blood

The pirates from the frigate "Valkyrie" differ from the pirates from the "Bestia" in their lack of kindness: if a pirate's decision to vote "for" or "against" does not in any way affect whether this pirate will be thrown overboard and how much money he receives, then his cruel grandmother on his father's side awakens in the pirate, and he votes "against". And as an algorithm for dividing the Valkyries, the rules described in exercise 3 are used: 1. The oldest pirate tells the others his plan. 2. All pirates vote on whether to accept this plan. Each of the pirates votes either “yes” or “no”. 3. If all the pirates, except perhaps one, vote yes, then the plan is accepted and the money is divided according to the plan. If at least two of the pirates vote against it, then the eldest pirate is thrown overboard. After this, the next highest plan is proposed, the pirates vote again, and so on, until one of the pirates' plan is accepted.

⟦folio 11⟧

FIFTEEN

HUMAN

ON

BOX

DEAD MAN

Problem 4

⟦column⟧

Once there was a division of rich booty - And the pirates were furious and howled... Yung suddenly turned pale and grabbed a knife, Because he was deprived. V. Vysotsky. There was a cheerful pink sunrise...

Frigate "Valkyrie"

How will 15 pirates from the Valkyrie divide 100 coins? Answer: 9 0 1 2 3 4 5 6 7 8 9 10 11 12 13 Solution. Let's start arguing for the pirates again from the end. The 14th (second from last) pirate need not worry about his life and the fate of his plan: no matter what he offers, “all but one” is himself. Therefore, he can take all the coins for himself: 0 0 0 0 0 0 0 0 0 0 0 0 0 100 0 The 13th (third from last) pirate already needs to enlist the support of at least one of the last two. Whose? It is clear that not on the 14th: if the plan on the 13th fails, he has the prospect of getting everything. This means that the cabin boy’s support is needed. To get it, it is enough to offer him more than 0, i.e. 1 coin. So he suggests

0 0 0 0 0 0 0 0 0 0 0 0 99 0 1 and, together with the cabin boy, votes “for”. The 12th pirate, who understands this situation, has to ignore the greedy 13th and appease all the following, offering them more than the 13th will give them. So the most he can count on is

0 0 0 0 0 0 0 0 0 0 0 97 0 1 2

Each subsequent pirate is forced to do the same, increasing the share of all pirates by at least one coin. Thus, when we bring the calculation to the highest (15th from the bottom) pirate, we will get the following distribution of coins:

9 0 1 2 3 4 5 6 7 8 9 10 11 12 13

Exercise 4. a) How will 15 of these pirates divide 20 coins? b) How will N pirates from the Valkyrie divide K coins?

It is noteworthy that only a slight difference in the character of the pirates (the good-natured pirates of the Bestia vote “yes” in a neutral situation, and the stubborn pirates of the Valkyrie vote against) leads to radically different results of the division. The ability of the Valkyrie crew to secure significantly more favorable sharing conditions illustrates an important general principle, the proof of which goes far beyond the scope of this article: social activity leads to an increase in the well-being of society.

One of the pirates, who was a cabin boy on the Valkyrie in those glorious times, many years after the events described, boasted that he had managed to take the entire treasure for himself. - A thousand devils! This miserly captain offered me only 13 coins. Then I see that the skipper is voting against, and he also voted against! And while everyone was staring at me, the skipper had already managed to throw the captain overboard. And after that, as if nothing had happened, the skipper offered me only 12! Well, I voted against it again - and our former skipper immediately flew overboard to the former captain. And then something began to dawn on the next one... A thousand devils! He started saying something five times in a row and each time, without bringing the sentence to a point, he looked at me and got confused... In the end, he offered to give everything to me. To me, a beardless cabin boy! And all the other pirates, constantly looking sideways at me, voted “for”. Of course, after that I couldn’t stay on our frigate for another minute, so I untied the captain’s boat, loaded the chest into it and immediately set sail. Prove that this yoonga’s story is a little untrue. Solution. This story is a perfect illustration of how the ideal world of mathematical problems differs from real life. On real pirate ships, of course, not such things happened, but our tasks initially stipulated the impeccability of pirate logic. As we will see, this leaves no room for blackmail, and therefore the Valkyrie pirates (starting with the captain) had no reason to fear the obstinate cabin boy. Indeed, if (well, what if!) the turn to put forward a plan comes to the second from last pirate, then he does not risk anything, because besides him there is only a cabin boy left. Therefore, in this case the cabin boy will receive nothing. Therefore, he has nothing with which to blackmail the third-from-last pirate at the moment when he introduces his plan. Junga will simply be forced to vote for any of his plans, if only he offers the cabin boy at least one coin. Moreover, the third-from-last pirate also understands this very well, so he will give exactly as much to the cabin boy. But, in fact, he will not have such an opportunity, because all previous pirates understand the impossibility of blackmail (and therefore the lack of need to be afraid of it) in exactly the same way. Therefore, everything will happen exactly as described in the solution to the previous problem, and not as the former cabin boy tried to tell.

Our series of pirate tales would not be complete if we did not tell the story of the pirates from the schooner Gorgon.

⟦folio 12⟧

KVANT 2016/№1

Problem 5

“They won’t check your books, especially since few of my people even know how to read.” But they know well - you force me to be harsh - that your calculations are false. R. Sabatini. Captain Blood's Odyssey

All the pirates on the schooner "Gorgon" are as cruel as those on the "Valkyrie", and for division they use the same method as the crew of the sloop "Bestia": 1. The eldest pirate sets out his plan for division. 2. All pirates vote on whether to accept this plan. Each of the pirates votes either “yes” or “no”.

⟦column⟧

votes, and the vote of the 14th pirate is bought cheapest. To do this, it is enough to give him only one coin, because he will not receive anything from the 13th: 0 0 0 0 0 0 0 0 0 0 0 99 0 1 0 Continuing to reason in a similar way, we find that the senior pirate only needs to share coins with seven others - the third, the fifth, ..., the fifteenth. In this case, they will all vote for his plan, and no one will have to be left out. Thus, the final distribution of coins is 93 0 1 0 1 0 1 0 1 0 1 0 1 0 1 b) Answer: plan of the 94th pirate, counting from the end (7th from the beginning). Solution. When there are only 15 coins, then the logic from point a) works up to 32 pirates. The eldest of the 32 pirates does not receive anything, but shares 15 coins with others and with this (along with his vote) he gains the 16 votes he needs:

0 0 1 0 1 0 … 1 0 1 0

Schooner "Gorgon"

3. If at least half of the pirates vote in favor, then the plan is accepted and the money is divided as proposed. If the majority of the pirates vote against it, then the senior pirate is thrown overboard. After this, the next most senior pirate introduces a new plan, the remaining pirates vote again, and so on, until finally one of the pirates' plan is accepted. a) How will 15 Gorgon pirates divide 100 coins? b) Whose plan will be accepted if 100 pirates from the schooner Gorgon need to divide 15 coins? a) Answer: 93 0 1 0 1 0 1 0 1 0 1 0 1 0 1 Solution. As usual, let's start looking at the problem from the end. Even if 13 plans have already been rejected, how does the second-from-last pirate reason? His vote constitutes at least half of the remaining votes, so he may not share with the cabin boy at all. Therefore, he simply takes all the coins for himself: 0 0 0 0 0 0 0 0 0 0 0 0 0 100 0 Let's take a step back. How will the 13th pirate reason? To stay alive, he needs two out of three votes. The 14th will be against it in any case, which means that support can only be expected from the cabin boy. To receive it, the cabin boy only needs to give more than he will receive from the 14th. This means that the cabin boy can leave one coin and take the rest for himself:

0 0 0 0 0 0 0 0 0 0 0 0 99 0 1

The next pirate (12th) also needs two

Let's try to deal with 33 pirates. There are only 15 coins, and in order to survive, the senior pirate must “buy” 16 other people’s votes. It makes no sense for him to give something to those 15 who, with 32 pirates, will receive money, which means he must divide 15 coins between himself and the 17 others. But since he will not be able to give anything to at least two of the 17, these fierce pirates will certainly vote against his plan. Thus, the 33rd pirate will die overboard. The position of the 34th pirate is clearly better, because he has in reserve not only his own voice, but also the voice of the 33rd, who undoubtedly wants the 34th’s plan to pass, otherwise he himself will suffer. He will be able to buy another fifteen votes by offering a coin to any 15 of those 17 that will be left without money when voting according to the plan on the 32nd. We will reflect this moment using a special icon - an asterisk. An asterisk means the pirate may or may not get the money. In this case, 15 of those marked with an asterisk will receive a coin, but the remaining two will not. So, with 34 pirates, the elder's plan is accepted, and the coins are divided like this:

0 0 * * 0 * 0 * … 0 *

The 35th, like the 33rd, will have to dive overboard: he doesn’t have a single other person’s vote “for free”, and he can only buy 15 of the 17 he needs. It’s a little easier for the 36th, but not much: the 35th will vote for his proposal for free, but he needs 18 votes, but he will be able to buy only 15, in total he will get 17, so his fate is also sad. For a similar reason, the 37th is killed. But the 38th manages to survive: he himself, as well as the 37th, 36th and 35th, vote “for”, and he buys another 15 votes in coins, for example, from those who definitely did not receive anything from the 34th. (You could also buy votes from pirates who are marked with asterisks, assuming that each of them would prefer a guaranteed coin at the moment instead of a "star" - not

⟦folio 13⟧

FIFTEEN

HUMAN

guaranteed coin in one of the following plans.) In total, he has 19 votes. The next few pirates also do not survive, and only the 46th has a chance of survival: all the suicide bombers will vote for his plan, starting with the 39th (total 8) and 15 more bought with money from the last 38, in the end he will receive the 23 votes he needs. It is easy to prove by induction that pirates with numbers (counting from the end) $30 + 2^{k}$ survive. But it is impossible to unambiguously establish the distribution of money, because each of the pirates has a fairly free choice of who exactly he will offer the money to.

ON

BOX

DEAD MAN

⟦column⟧

Solution. As usual, let's start looking at the problem from the end. Let 14 plans have already been rejected. Then all the coins are practically in the cabin boy’s pocket. It is enough for him to put forward any plan that the rest of the pirates will not vote for (for example, offer to keep all the money for himself). After this plan is rejected, the cabin boy will receive all the coins:

0 0 0 0 0 0 0 0 0 0 0 0 0 0 100

The sharing methods that we examined in previous tasks have one significant drawback: most pirates can end up overboard, and this has a bad effect on the crew’s combat readiness. Fortunately, among the pirate crews there are also less bloodthirsty ones.

Let's now go back a step. Let 13 plans be rejected. How should the 14th pirate reason? He cannot allow his plan to be rejected, since in this case the cabin boy will take all the coins. This means that he needs a plan that 14 out of 15 pirates will vote for. Young will vote against any of his plans, therefore, the 14th needs everyone else to support his plan. To do this, he must allocate a coin to each of the pirates, except the cabin boy. This will require 13 coins. The 14th pirate will take the remaining 87 coins for himself:

Problem 6

1 1 1 1 1 1 1 1 1 1 1 1 1 87 0

Well, if there is no return to Portland, Let's divide the gold like brothers. B. Okudzhava. Pirate lyrical

The pirates from the corvette Danae were just as brutal as those on the Gorgon and Valkyrie, but they came up with a new way of dividing up the coins that allows the pirates to remain on board and claim a share of the spoils even after their plan is not accepted. 1. The oldest pirate outlines his plan for division. 2. All pirates vote for or against. 3. If all the pirates, except perhaps one, vote in favor, then the plan is accepted and the money is divided as proposed. If at least two of the pirates vote “against”, then the plan is not adopted and voting continues. The next oldest pirate proposes his plan, the pirates vote again, and so on, until one of the pirates' plan is accepted. If none of the plans go through, then the cabin boy will receive all the money. How will 15 Danae pirates divide 100 coins? Answer: 11 11 11 12 0 1 2 3 4 5 6 7 8 9 10

Let's take another step back. Let 12 plans be rejected. How will the 13th pirate reason? If his plan is rejected, then the 14th pirate will give him one coin. But one coin is not enough for him, so he should not allow this to happen. To do this, he must give more coins to at least 14 pirates (including himself) than the 14th one would have given them. Thus, pirates with numbers 1 to 12 need to be given 2 coins, and one coin should be given to the cabin boy. The 13th pirate will keep the remaining 75 coins for himself:

2 2 2 2 2 2 2 2 2 2 2 2 75 0 1

The 12th pirate thinks similarly. He gives nothing to the 13th, but gives the rest one coin more than they could get from the 13th. Therefore, pirates with numbers 1 to 11 will receive 3 coins, the 14th pirate will receive one, and the 15th will receive two. You can keep the remaining 64 coins for yourself:

3 3 3 3 3 3 3 3 3 3 3 64 0 1 2

It would be possible to continue in the same spirit and write out the plans of the remaining pirates. But the general pattern is already obvious. The pirate with number X gives each of the pirates with lower numbers 15 - X coins, each pirate with a higher number Y he gives Y - X - 1 coin, and takes the rest of the coins for himself. Thus, the profit of pirate number X is

100 - (X - 1) (15 - X) - (15 - X) (14 - X) 2 coins. Opening the brackets, we get the following expression for the profit of the pirate with number X:

$X^{2} 2 - 3 X 2 + 10$.

The profit must be greater than the number of coins that pirate number X + 1 will allocate to pirate number X in the next step, otherwise his own plan will not bring any benefit to pirate number X. Thus, the following inequality is true:

Corvette "Danae"

$X^{2} 2 - 3 X 2 + 10 > 14 - X$.

⟦folio 14⟧

KVANT 2016/№1

Simplifying, we get

$X^{2} - X > 8$. The smallest natural X for which the inequality holds is 4. Therefore, the 4th pirate's plan will be accepted:

11 11 11 12 0 1 2 3 4 5 6 7 8 9 10

Since the Danae pirates are cruel, each of them will vote against any plan in which he receives no more than he can get from the 4th. Whatever plan the 3rd pirate proposes, he can “take away” the money from only one of the others, and must distribute it among all the others (otherwise he will get at least two offended people, and his plan will fail). But he can only take 12 coins, which, with any division by 14, will lead to the fact that someone will not receive coins. Therefore, no plan of the 3rd will be accepted, even if he proposes the plan that the 4th then proposes (because everyone is cruel, and if the money for “for” and “against” is the same, then they vote “against”)! Likewise, no plans of the first two pirates will be accepted.

Note that the pirates’ trust in democratic decision-making mechanisms is also not as absolute as you might think...

Problem 7

Easterling puffed out his cheeks and made a broad gesture with his huge paw. – What kind of division do you propose? - We need to discuss this. But, in any case, our share cannot be less than one fifth. R. Sabatini. The Chronicle of Captain Blood

On the brigantine Echidna, only the captain and skipper have the right to propose plans for dividing the coins. All other pirates can only vote. Thus, the division algorithm looks like this: 1. The skipper tells everyone else his plan for dividing the coins. 2. Then the captain tells everyone his plan for dividing the coins. 3. All pirates (including the captain and skipper) vote for either the first or second plan. 4. Coins are divided according to the plan with the most votes. It is known that if both plans promise the pirate an equal number of coins, he will vote for the first plan. How will 15 pirates (captain, skipper and 13 sailors) from the Echidna divide 63 coins? Answer: 49 8 1 1 1 1 1 1 0 0 0 0 0 0 0 Solution. As always, let's start understanding the problem from the end. First of all, let's establish the captain's optimal strategy. Consider a group of 14 pirates, excluding the captain. Let us divide them into two groups A and B of 7 pirates each, such that the skipper offered no less coins to each of the pirates in group A than to any pirate from group B. It is easy to see that the captain’s optimal strategy is

⟦column⟧

Brigantine "Echidna"

to take all the money from the 7 “rich” pirates of group A, allocate one coin from this money to each of the 7 “poor” pirates of group B, and take all the other coins for yourself. In this case, all the pirates of group B and the captain himself will vote for the captain's plan. The Pirates of Group A will vote against it, but they will be in the minority. Of course, this strategy only works if the group A pirates have at least 8 coins. Otherwise, the captain will not be able to allocate a coin to each of the 7 pirates of group B and at the same time keep at least one coin for himself, and it will be more profitable for him to agree with the skipper's plan. Now let's analyze the skipper's strategies. He has two possible options. The first is to put the captain in a situation where he is forced to agree with the skipper's plan. To do this, as we found out, it is enough that the 7 pirates to whom the skipper offered the largest number of coins have no more than 7 coins in total. It is not in the skipper's interest to share with other pirates, so he can simply take 7 coins for himself and give the remaining coins to the captain. The captain will put forward some plan that the others will not vote for (for example, keep all the money for himself), after which the skipper's plan will be accepted by a majority of votes: 56 7 0 0 0 0 0 0 0 0 0 0 0 0 0 0 The second possible strategy for the skipper is to allow the captain to put forward a plan that receives a majority of votes, but at the same time the skipper himself will be among those seven pirates to whom the captain will give an additional coin (others in words, will be included in group B). To do this, the skipper must promise 7 pirates (who will be included in group A) more coins than himself. The remaining 6 pirates, who will keep the skipper company in group B, do not have to offer anything. Thus, the skipper's plan looks like this: 0 7 0 0 0 0 0 0 8 8 8 8 8 8 8 The captain will give the skipper and the other 6 pirates one extra coin each, and take the rest of the coins for himself: 49 8 1 1 1 1 1 1 0 0 0 0 0 0 0

⟦folio 15⟧

FIFTEEN

HUMAN

So, the first strategy will bring the skipper 7 coins, while the second will allow him to get 8 coins. Thus, the skipper will prefer the second strategy.

Problem 8

In the port of Cape Town, with a hole in the side, “Jeanette” adjusted the rigging. P. Gandelman. In Cape Town port

On the barque Jeanette, as on the Echidna, sailors do not have the right to put forward plans. Only senior pirates can do this. The division algorithm is as follows: 1. The first pirate tells his division plan. 2. The second pirate tells his plan - the “alternative”. 3. The plan and the alternative are compared. If a plan gives at least two pirates at least as many coins as the alternative, then the alternative is rejected. If the alternative gives more money to all but perhaps one of the pirates, then the plan is rejected and the alternative becomes the plan. Then the next pirate voices a new alternative and so on. 4. After all the senior pirates have spoken, the coins are divided according to plan. 5 senior pirates and 10 sailors from the Jeannette share 105 coins. How can the first pirate get 14 coins?

Bark "Jeanette"

Solution. The rules in this problem seem quite confusing, but you can notice the following: if some plan promises one of the pirates 14 coins, and each of the other pirates no more than 13 coins, then there is only one alternative that can replace this plan (i.e., better than the plan for all but one of the pirates): take all the money from the owner of 14 coins and divide it one by one among the others. Now consider the plan 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14. The only best alternative to it is 1 2 3 4 5 6 7 8 9 10 11 12 13 14 0. It is easy to see that this is the same plan, cyclically shifted by one position. To capitalize on this property, the first pirate puts forward this plan:

10 9 8 7 6 5 4 3 2 1 0 14 13 12 11

ON

BOX

DEAD MAN

⟦column⟧

Thus, he keeps 10 coins for himself and offers the other senior pirates 9, 8, 7 and 6 coins respectively. A sequence of alternatives, each of which is better than the previous one and replaces it, is constructed in a unique way: 11 10 9 8 7 6 5 4 3 2 1 0 14 13 12

12 11 10 9 8 7 6 5 4 3 2 1 0 14 13

13 12 11 10 9 8 7 6 5 4 3 2 1 0 14

14 13 12 11 10 9 8 7 6 5 4 3 2 1 0 It is easy to see that the shares of each of the five senior pirates are growing. Thus, each of them is interested in putting forward these 4 alternatives one after another. The final plan will be the last of them. Thus, the first pirate will become richer by 14 coins.

Problems to be solved independently The amounts received became larger and larger. And at the very end, after five or six erroneous, crossed-out calculations, the total was summed up and signed at the bottom: “Bons’ share.” R. L. Stevenson. Treasure Island

On average, these tasks are more complex than those discussed above. 1. How will the division on the Danae change if the pirates change rule 3: the plan will be considered accepted if more than half of the pirates vote in favor? To solve the problem, we need to clarify how a pirate decides which plan to put forward if there are several different plans, each of which will bring this pirate the same number of coins. In this case, we will assume that the choice of plan occurs randomly (for example, a pirate throws a coin to choose between two plans of equal value). 2. How will the solution to the previous problem change if, in the case of a choice between equivalent plans, the pirate “Danai” always prefers the plan that leaves more coins for the older pirates? 3. How exactly will the coins be divided in problem 5 b) (“Gorgon” with a large team and a small supply of gold), if the choice between equal plans is made in the same way as in the previous problem 2? 4. How much money will the navigator on the brigantine “Echidna” receive as a result of dividing K coins between 2 M + 1 pirates? 5**. On the yacht “Cinderella” the crew consists of only three – the captain, the skipper and the cabin boy. The treasure they found contained only 15 coins. Therefore, they agreed that they would first listen to all three plans, and only then would they choose. So, everyone takes turns, starting with the captain and ending with the cabin boy, offering their own options for sharing. Then all three vote at the same time - each chooses the plan in which he gets more coins. If there are several such plans, he will vote for the first one. The plan that receives more than one vote is accepted and the treasure is divided accordingly. However, if there is no such plan, then no one gets anything (the entire treasure is thrown overboard). How will the coins be divided? What will be the distribution if the decision can only be made unanimously?

⟦folio 18⟧

KVANT 2016/№1

the same. Leaving the nucleus along with a beta particle (electron), the neutron takes on those parts of energy, momentum and angular momentum that are necessary to comply with conservation laws... My friend Debye, however, wrote to me that it is better not to think about this problem, just as you should not think about, for example, new taxes. But as unlikely as it may be, since there is no experimental evidence, I will still venture to put forward this hypothesis. If you don't take risks, you won't win." A year later, in 1931, Pauli published an article about this mysterious particle, which should save the laws of conservation, but its mass had already been proposed to be much less than the mass of the electron. And in 1932, Chadwick experimentally proved that the atomic nucleus contains massive neutral particles - neutrons, and during beta decay they do not fly out of the nucleus. This discovery brought Chadwick the Nobel Prize (1935). Now the hypothetical Pauli particle - the savior of conservation laws - had to be given a different name. This was done in 1932 not by himself, but by the young Italian physicist Enrico Fermi, a future Nobel laureate, right at a lecture on general physics to first-year students at the University of Rome (which, by the way, was attended by student Bruno Pontecorvo). Fermi effusively called this particle a neutron, a small neutron, which in Italian was “neutrino.” So, the conservation laws were saved on paper. There is only a small catch - to catch this particle, prove experimentally that it exists, and measure its energy and momentum in beta decay. With the development of nuclear physics, it became clear that there are processes of neutrino production, but nothing was known about capture processes. Finally, in the 1960s, some such processes were predicted. Individual nuclei had discrete energy levels that were suitable for capturing neutrinos whose energies were theoretically known. True, the probability of capture, according to calculations, remained very small. Therefore, the first experiments began to be carried out where there are a lot of neutrinos - near operating nuclear reactors. And in 1975 in the USA, F. Raines and K. Cowan achieved success. They used the reaction of electron antineutrino capture by chlorine to produce an isotope of argon and a positron (antielectron). Since the positrons immediately disappeared, annihilating with the first electrons that came across, the number of argon atoms produced was determined to count the absorbed antineutrinos. This was also not an easy task, because very little argon was produced. After three months of operation of the installation, only about 5000 argon atoms were formed in it (about 40 capture events occurred per day). Of course, it was impossible to weigh this on any scales; the amount of argon was determined by its radioactivity. This experiment went down in the history of physics under the name “Poltergeist”, literally translated as “hectic spirit”, and in modern free translation as “drummer”. This (or this) drum, however, brought Reines the Nobel Prize in 1995, when the scientist turned 85 years old (the other author of the discovery did not live to see the award). Why was there such a long break? The fact is that when they began to refine and repeat the work of Reines, it became possible to capture solar neutrinos in a similar way. And it turned out that terrestrial experiments always produced several times fewer neutrinos than solar astronomy expected. Suspicions arose about errors in solar physics. But in all other respects its consequences were justified by experience. Again, the neutrino presented physicists with a riddle - a “headache,” as they began to say

⟦column⟧

Bruno Pontecorvo at that time. And it was then that Pontecorvo put forward his brilliant guess about the “hypostases” of the neutrino and the oscillations of its various flavors. According to this hypothesis, any neutrino exists in three forms - physicists so far designate these forms simply as numbers 1, 2, 3. The forms have different masses and different propagation speeds. According to wave-particle duality, they are characterized by de Broglie waves of different lengths. Let us note that if they had no mass, then the speeds would be equal to the speed of light and there could be no talk of any de Broglie waves. When propagating in one direction, de Broglie waves of three hypostases interfere and form regular maxima. These maxima are the flavors of neutrinos. Thus, if, when absorbed by the nucleus of an electron, the generated neutrino had an electronic flavor, then, due to the fact that it consists of three hypostases, after some time of movement it will become a muon neutrino, and after some time - a tau neutrino. And this will repeat itself all the time. This kind of werewolf is a mysterious neutrino. And the experiments were initially aimed only at capturing (“catching”) electron neutrinos. Muon neutrinos and tau neutrinos were simply not detected in experiments. This is how the “missing” of two-thirds of solar neutrinos occurs. But it all looked beautiful on paper, in theory. Experimental testing of Pontecorvo's hypothesis required much greater accuracy of neutrino experiments. It is necessary that neutrino capture events occur much more often, at least every second. Obviously, the only way for this is a significant increase at one point (in one laboratory) in the number of installations where neutrinos can be captured. Estimated calculations showed that the substance should be at least several tens of tons. And besides, all this should happen where the appearance of any other particles except neutrinos will be excluded. And cosmic radiation - both solar and coming from the depths of space - gives rise to whole “showers” ​​of particles in the earth’s atmosphere. This means that neutrino-catching installations must be located deep underground (or underwater), which significantly increases the cost of such experiments. In the 80s of the last century, the only element suitable in terms of nuclear energy levels for capturing solar neutrinos was gallium. When a gallium nucleus captures a neutrino, a germanium isotope nucleus and an electron are formed. Germanium can be chemically separated from gallium, and by its emission one can judge its quantity and, therefore, the number of captured neutrinos. Gallium is usually contained as a very non-

⟦folio 20⟧

KVANT 2016/№1

Installation of Super-Kamiokande. The neutrino detector is smaller.) And then the electron begins to lose energy - it emits an electromagnetic wave, the front of which has the form $конуса.^{2}$ When this front crosses the photocell, a photocurrent pulse appears. It is very weak, so it must be amplified by a special device - a photomultiplier. The photomultiplier detects the radiation energy, and therefore the energy of the electron emitted during the capture of a neutrino. The reaction of the photomultiplier depends on the direction of movement of these electrons. In the SNO facility, 9,500 photomultiplier tubes were installed on the surface of a sphere containing heavy water. The results of this installation made it possible to count both the number of captures caused by only electron neutrinos and the number of captures caused by all three flavors of neutrinos. They turned out, with good accuracy, to be 3 times larger. The clear conclusion from this fact is this: despite the fact that only electron neutrinos are born in the depths of the Sun, on the way to Canada they oscillate, turning into other flavors. Pontecorvo's hypothesis about neutrino oscillations and, therefore, the presence of mass in them was reliably confirmed, which brought the leader and inspirer of the project, Arthur MacDonald, a Nobel Prize. While these events were unfolding in Canada, far from this place, in Japan, 290 kilometers from Tokyo in an abandoned zinc mine in 1986, the modernized Super-Kamiokande installation (named after the area near Mount Kamio) began operating. And although in many ways these two installations are similar and the purpose of their work was the same, the Japanese laboratory registers completely different neutrinos - not solar, but atmospheric-cosmic muon neutrinos, born quite close, in the upper atmosphere of the Earth at an altitude of 20-30 kilometers. It was discovered earlier that muon neutrinos of such energy have some probability of causing a small pogrom in the electron cloud of an ordinary water molecule, in

2 The radiation of electrons moving in a substance faster than the speed of light in this substance is called Cherenkov radiation, named after the physicist P.A. Cherenkov who discovered it in 1934. Cherenkov and theoretical physicists I.E. Tamm and I.M. Frank, who explained this phenomenon, became Nobel laureates in 1958. This was the first Nobel Prize in physics received by scientists in our country.

⟦column⟧

as a result of which the molecule ejects a fast mu-meson (muon), thereby becoming an ion. A muon is very similar to an electron; in the same way, moving in water faster than the speed of light in it, it produces Cherenkov radiation, which is detected by photomultipliers. Super-Kamiokande is even larger than the SNO installation. It is a cylinder with a diameter of about 40 meters and the same height. The cylinder is filled with ordinary water, but thoroughly purified from all impurities. There are 11,146 photomultipliers located on the inner surface of the cylinder. As in SNO, there is a huge electrical, radio-electronic and computer support for the operation of photomultipliers and processing of the received data. The main result of the work of this laboratory was the discovery of the fact that the number of absorbed neutrinos depends on the direction of their motion. Those particles that moved from top to bottom turned out to be twice as many as those that moved from below. The latter, before falling into the trap, had to pass through the entire globe. They didn’t get stuck along the way, since there was almost no water there, and neutrinos with such energies have no other options for disappearing. Conclusion: on their way through the globe, the neutrinos managed to oscillate so that only half of the initial muon neutrinos remained. The other half turned around, becoming tau neutrinos, which, even if they created pogrom for the water molecule, produced not a mu meson, but a tau meson. But the photomultipliers did not react to the Cherenkov radiation of the tau meson, which has a different mass. Chronologically, this was the first evidence of oscillations, although not solar, but atmospheric-cosmic neutrinos. In these experiments it was even possible to estimate the mass of muon neutrinos and tauneutrinos. Note that it was here on November 23, 1987, at the same moment in time, that all the photomultiplier tubes seemed to go crazy - they registered a huge number of neutrinos coming from the supernova explosion cloud. In 2015, 15 years after the publication of the successful results of the work, the head of the team of this laboratory, Takaaki Kajita, became a Nobel laureate along with Arthur MacDonald. However, he and his team had to endure a severe shock - on November 12, 2001, the glass shell of one photomultiplier tube could not withstand the pressure of water and cracked. Since there must be a deep vacuum in the internal space of this device, the destruction was explosive in nature, and the resulting shock wave led to the destruction of 7,000 photomultiplier tubes and other equipment. In 5 years, everything was built anew, and in an improved version, the Super-Kamiokande II installation continues to operate successfully to this day. The question arises - why? The results are obtained, the neutrino oscillates. We can say that he alone exists in three forms, each of which is also a neutrino. Neutrinos have a lot... In fact, there are many more questions that still have no answer. Hypotheses have emerged about other neutrino flavors, in addition to the three already known. One of them, the “sterile neutrino,” can bring closer the solution to dark matter, the other, the “Majorana neutrino,” will help unravel the asymmetry of matter and antimatter in the Universe. So, perhaps, more than once on the pages of «Kvant» there will be articles about Nobel Prizes for neutrinos, this almost free particle.
