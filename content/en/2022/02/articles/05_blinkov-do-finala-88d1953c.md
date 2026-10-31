---
id: 2022-2-blinkov-do-finala-88d1953c
issue: kvant_2022_2
year: 2022
number: "2"
title: Until the final
authors:
  - Блинков А. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 53
page_labels: 47, 51
tag: 5KE5
lang: en
source: kvant_digital
extraction: native
content_sha256: bf842b1f76ee3ccff1a8cf4cc2852b6254c98419d6576573670e8645f3bbf6b4
prompt_sha256: draft-1
translated_from: content/ru/2022/02/articles/05_blinkov-do-finala-88d1953c.md
source_content_sha256: a46cc5eedad3a6f948f555f535f6a5e47f5d1c7e7572bcb722de9837cb4bdb4e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Until the final

MATHEMATICAL CIRCLE

A. BLINKOV

At the personal Olympiad of the XXVI Tournament named after A.P. Savin, schoolchildren in grades 5–6 were offered the following task. Task 1. The school table tennis tournament was held according to the following system: at each stage the players split into pairs and played one game, at the next stage they again split into pairs and played one game (pairs were not repeated) and so on. A student who lost twice was eliminated from the tournament. If at any stage the number of participants was odd, then one of them advanced to the next stage without playing. How many people participated in the tournament if 29 games were played before the final, in which two people had to play? The same problem, but with the added question - “How many people participated in the tournament if 30 games were played before the final, in which two people had to play?” – entered at number 15 in the A.P. Savin Competition (see «Kvant» No. 11-12 for 2021). To the surprise of the jury, who considered the problem simple, few solved it. Therefore, before presenting the solution, let us turn to the “classical problem” in a slightly modified formulation. Problem 2. In a boxing tournament held according to the Olympic system (the loser is eliminated), 29 fights were held, not counting the final. How many boxers took part in the tournament? Solution. In each of the fights that went to the final, one boxer lost and was eliminated from the tournament. In the final, two people who had not lost before met each other, which means that there were 29 + 2 = 31 participants in total.

Exercise 1. 66 boxers participated in the tournament according to the same rules. How many fights were held before the final?

The main conclusion is that to solve problem 2 there is no need to analyze exactly how the battles took place. This also applies to task 1.

DOI: https://doi.org/10.4213/kvant20220205

⟦column⟧

Solution to Problem 1. Each of the schoolchildren who reached the final either did not lose at all or lost one game. Therefore, the rest account for 29, 28 or 27 lost games. Since the student dropped out after two lost games, there could not be 29 or 27 games, and the number of dropouts was 28: 2 14. This means that only 16 schoolchildren could participate in the tournament. The problem is solved. Note that in this case there is no need to give an example describing exactly how the tournament took place and show that the received answer is achieved, since the condition says that the tournament took place, and the received answer is the only one. But the situation will change if 30 games were played in such a tournament before the final. Indeed, reasoning in a similar way, we find that the share of those who dropped out was 30, 29 or 28 games. Then $30^{:} 2 2 17$ or $28^{:} 2 2 16$ schoolchildren could participate in the tournament. In this case, it is necessary to show that both obtained answers are possible. Let's do this for 17 participants. One of the schoolchildren, without playing, went to the second stage, at which one of the schoolchildren, who won the first stage, “rested,” and the rest, who won the first stage and the participants who had not played before, met with the losers, changing opponents, and won again. Then, after the second stage, 8 participants dropped out, and 9 participants remained without defeats. The next two stages followed a similar pattern, after which there were 5 schoolchildren left who had no defeats. The results of the fifth, sixth, seventh and eighth stages are shown in Table 1 (the index corresponds to the stage number). Thus, participants 1 and 2 reached the final, and $8 + 8 +^{4} +^{4} + 2 + 2 + 1 + 1 = 30$ games were played.

Exercise 2. Give a similar example for 16 participants in a tournament in which 30 games were played.

From a mathematical point of view, there are no errors in the given example, but in reality, tournaments using the specified system are held according to rules that more strictly regulate

⟦folio 47⟧

MATHEMATICAL

order of pairing. Let us present the first part of the rules of the tournament, the holding system of which is called Double Elimination. The tournament is divided into two brackets - upper and lower (winners' bracket and losers' bracket). All participants start the tournament in the upper bracket. Participants are divided into pairs, which play among themselves in the first round. The winners of the first round advance to the second round of the upper bracket. The losers move to the lower bracket. In the lower bracket, the tournament begins with the second round. From this round onwards, games are played simultaneously in both brackets, but no one must play the same opponent twice. The winner in the upper bracket moves on to the next round in the same bracket. The loser of the upper bracket moves on to the next round in the lower bracket. The winner in the lower bracket moves on to the next round in the same bracket. The loser in the lower bracket is eliminated from the tournament. With this approach, the example given does not work, since already in the second round participants from different grids meet each other. Moreover, if at each stage the players were divided into pairs, then such a tournament would be impossible to hold at all! Indeed, after the second stage, the number of participants in the lower bracket will significantly exceed the number in the upper one, so at some point there will be one participant left in the upper bracket who will not have a pair, and in the lower bracket there will be at least two. It is convenient to show this using the example of 16 participants (see Table 2, pairs of numbers - number

Table 2 of participants in the upper and lower brackets, respectively). The second part of the rules, which has several varieties, comes to the rescue. The simplest of them is this. At some stages, games are played only in the lower bracket until the number of participants in both brackets is equal. After two participants remain in both brackets, at the next stage two pairs are formed, in each of which a participant from the upper bracket meets a participant from the top bracket.

CIRCLE

⟦column⟧

com from below. If both “top” participants win, they play the final. If both lose at the next stage, they change opponents and the winners of these pairs advance to the finals. If one of them wins, then a pair of participants with one defeat each is formed, the winner of which advances to the final and plays with the one who has no defeats. Note that the above rules almost automatically ensure that no one should play the same opponent twice. Then the tournament, in which 16 participants played 30 games until the final, could be held as shown in Table 3 (in the first line - the number of participants

Table of 3 players in each grid, in the second - the number of games in each grid; at stage 6, the participants from the upper bracket first lost to the lower ones and swapped opponents, after which the winners of the pairs advanced to the finals).

Exercise 3. Give an example to show that in a tournament with 17 players, 30 games could be played before the final, according to the rules given above.

In conclusion, let’s compare tournaments using the Olympic system and the Double Elimination system for 16 participants. According to the Olympic system, until the final there are 3 stages and 14 games are played, and according to the system with elimination after two defeats there are 6 or 7 stages in which 28, 29 or 30 games are played, i.e. in the second case, there are at least twice as many stages and parties. Those interested can investigate whether these patterns hold true for tournaments with an arbitrary number of participants, starting, for simplicity, with a tournament in which there are $2^{n}$ participants.

⟦folio 51⟧

OLYMPICS

the one with air; The heat flow through a cardboard disk is proportional to the temperature difference between its surfaces and proportional to the area of ​​the disk. A. Apolonsky

⟦column⟧

Consider the ship's flow rate constant (the commander can choose any flow rate value). Do not take into account the change in the mass of the ship; the acceleration of free fall is equal to g. A.Hare

Problem 2. Heavy piston In a vertical closed vessel of variable cross-section there are two cylindrical compartments: the lower one with a cross-sectional area $S_{1} S$ and height $h_{1} h$, upper with cross-sectional area $S_{2} 3 S$ and height $h_{2} 3 h$ (Fig. 10). The lower compartment is tightly and hermetically sealed with a movable heat-conducting piston (the piston is not glued, but gas does not penetrate into the space between the piston and the supports), which can move inside the upper compartment with minimal friction. Fig. 10 divisions. Both compartments contain the same amount Q of gas at temperature $T_{0}$. The gas throughout the vessel is slowly heated. When the gas temperature reaches $величины_{0}^{2T}$, the piston comes off the supports. 1) What is the mass of the piston? 2) At what height h c from the lower base of the vessel will the piston be in equilibrium? All gas temperature is maintained $равной_{0}^{2T}.^{3)}$ The gas in the vessel begins to slowly cool. At what $температуре^{T}$ Will the piston go back down on the supports? Note. The gas temperature above and below the piston is always maintained the same. A.Hare

Problem 4. And Snell again A drawing was found in Snell’s archive. Over time, the ink has partially faded and only 4 dots remain visible, two of which are actual point sources $S_{1}$ And $S_{2}$, and the remaining two – D and E – are their images (Fig. 11). From the description of the drawing it follows that the images were created by a single lens. Find by constructing using a compass and a line Fig. 11 lines (without divisions) all possible positions of the lens, its type and focal length. A. Evseev, V. Slovobyanin

Problem 3. Soft landing The spacecraft must land on an atmosphereless planet and touch its surface at a speed not exceeding $v_{п}$, which can be absorbed by the shock absorbers. At $высоте^{h}$ above the surface of the planet, the ship's commander turned on the braking jet engine, creating a thrust force directed upward. What was the magnitude of the ship's $скорость^{v}$ at that moment, directed vertically downward, if it turned out that during the landing process it consumed a minimal amount of fuel? (If there are several such speeds, then indicate them all.) The mass flow rate P of the fuel and the speed u of the outflow of gases relative to the cores are equal to 7 W. Determine the total power released by the resistors in the circuit shown in figure 13. The characteristics of all elements of the circuits are not specified, but the elements designated identically on the diagrams have the same characteristics. The sources can be considered ideal. A. Konovalov

Problem 5. Total power In the circuit shown in figure 12, the total power allocated to the resistive

⟦figure⟧

Fig. 12

⟦figure⟧

Fig. 13

Grade 11 Problem 1. Triangle and film Light rods OA and AB are hingedly connected to each other (Fig. 14). End O of rod OA is hinged on a smooth knitting needle, and at end B of rod AB a small oil ring is attached using a hinge.
