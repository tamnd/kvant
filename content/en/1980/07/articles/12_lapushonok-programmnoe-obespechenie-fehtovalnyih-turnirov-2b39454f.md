---
id: 1980-7-lapushonok-programmnoe-obespechenie-fehtovalnyih-turnirov-2b39454f
issue: kvant_1980_7
year: 1980
number: "7"
title: Fencing tournament software
authors:
  - Лапушонок И.
rubric: raznoe
rubric_sub: Разное
page_first: 38
page_last: 39
page_labels: 36-37
tag: 1XOT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 01a62241c1b4a45425085ef209b8c1f7067db733936f06316923e32a9d7d8475
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/12_lapushonok-programmnoe-obespechenie-fehtovalnyih-turnirov-2b39454f.md
source_content_sha256: 69373ecc3c5d9120ffc799811371ed649756ab23143da07b03cf566c2d365270
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

I. Lapushonok

Fencing tour software

In modern fencing, all participants are divided into initial groups (bullets), in which they fight each other in the established order. There can be from five to ten people in a bullet, and it is desirable that all bullets have an equal number of sportsmen. The place taken by the participant in the pool is determined by the number of victories, and in case of an equal number of victories - by the coefficient $k$:

$$k = \frac{\text{нанесенные уколи}}{ \text{полученные уколи}}$$

Determining the number of personal participants from each pool (usually 3 or 4) goes to the next stage. In the next stage, the participants are again divided into bullets (if there are more than ten participants) and fight again. When the next stage consists of less than 10 people, it is declared financial and the winner of it is declared the winner of the tournament.

The advanced fencing software consists of the following procedures:

— calculation of possible variants of bullets (PULLKA);
— entering the names of participants and recording them in the set (PARTICIPANTS);
— distribution of participants’ names by pools (GROUPS);
— determining the order of battles for each bullet and recording the results of these battles in a motorcade (SCOUNT);
— counting the number of victories of each participant and ultimately the place in the pool (POINTS);
— issuing a bulletin protocol (PROTOCOL);

— recording the participants of the next stage in the set (STAGE);
— control procedure CONTROL with the INTERRUPTION procedure (re-fight).

Interactive system. It was originally written in BASIC. We suggest that the reader repeat these programs on Rapier.

Control over the progress of progress and the inclusion of procedures in the required sequence is carried out by the MANAGEMENT procedure.

SEMI FORMAL This program could be described like this:

PROCESS MANAGEMENT;
.PARTICIPANTS;
1—> SIGN;
WHILE SIGN > = 0::
.BULLET; .GROUPS;
FOR ALL GROUPS::
.CHECK; .POINTS; PROTOCOL
ALL;
IF THE NUMBER OF PARTICIPANTS <10
THEN SIGN —1—> SIGN
OTHERWISE .STAGE
ALL
ALL;
CHECKING THE NEED
PROCEDURE CALL INTERRUPTION
KSC;

There are only two places here that are not formal (from Rapier’s point of view). They are in italics. First, this is the FOR ALL GROUPS line::

meaning the mandatory, repeating execution of all three subsequent procedures COUNTING, POINTS and PROTOCOL for all bullets of the same level; your task is to implement this informal prescription using the Rapier means known to you.

Secondly, the lines CHECKING THE NEED FOR CALLING THE PROCEDURE INTERRUPTION

It will not be difficult for you to expand into a formatted description of the conditions of the IF operator, taking into account that the INTERRUPTION procedure starts working if 2-4 participants (any pair of them, three or even four) have an equal number of wins and equal odds.

In addition, in the description of the CONTROL procedure, it seems necessary to be specific. The transferred NUMBER OF PARTICIPANTS is entered by the judges at the beginning of the program (in the PARTICIPANTS procedure) and can be changed (reduced) only during the COUNTING procedure. The transferred SIGN is used to fix the family bullet.

The PARTICIPANTS procedure is used to initially enter and fill in the names of participants. They are entered from the terminal in the order established by drawing lots (for the programmer

⟦folio 37⟧

it is important that the order in the list of participants is precisely known by the time it is entered into memory). The GROUP procedure selects the composition of the bullet from the recorded participants. For example, the first bullet will include participants whose surnames were entered, say, with the numbers 1, 7, 13, 19, 25, 31, 37. Before the bullet starts, a printout is issued - the numbers and surnames of the participants. Example:

Bullet 1
No. 1 IVANOV D.
No. 2 VOLKOV I.
No. 3 KUZNETSOV M.
No. 4 LEBEDEV A.
No. 5 LVIV V.

Nibolie is interested in the procedures PULL, SCORE and POINTS, since they reflect the specifics of fencing tournaments. POOL displays possible options for dividing participants into bullets. An example of a machine issuing this procedure:

HOW MANY PEOPLE DO TAKE PART IN THE TOURNAMENT?
— 43
6 PEOPLE IN EACH OF 6 GROUPS AND 7 PEOPLE IN EACH OF 1 GROUPS.
7 PEOPLE IN EACH OF 5 GROUPS AND 8 PEOPLE IN EACH OF 1 GROUPS.
5 PEOPLE IN EACH OF 5 GROUPS AND 6 PEOPLE IN EACH OF 3 GROUPS.

Here the judge entered only one number - 43.

SCORE displays a table of the order of battles for each bullet. In addition, this procedure directly prescribes the introduction of battles, calls the participants to the road, announces the next battle, accepts the results, and records them in the motorcade. The same tuple also uses POINTS in the process, which calculates the number of victories, odds, and places.

Below is a printout of the table of battles and the progress of the tournament with a record of the results and, in the process, POINTS, which calculates the number of victories, odds, and places.

Below is a printout of the table of battles and the progress of the tournament with a record of the results and, in the process, POINTS, which calculates the number of victories, odds, and places.

ORDER OF FIGHTS FOR 5 PARTICIPANTS 1-2, 3-4, 5-1, 2-3, 5-4, 1-3, 2-5, 4-1, 3-5, 4-2,*)
FOR TRAIN 1-2 GET READY 3-4
RESULT?
— 3,5
FOR TRAIN 3—4 GET READY 5—1
RESULT?
— 5,0
...**)
LAST PAIR 4-2
RESULT?
— 5,3

The protocol drawn up based on the results of this bullet is shown in the table.

Participants No. 1 2 3 4 5 P NU PU M
Ivanov D. 1 * 3 5 2 0 1 10 19 5
Volkov I. 2 5 * 5 3 1 2 14 21 3
Kuznetsov M. 3 4 3 * 5 1 1 13 15 4
Lebedev A. 4 5 5 0 * 3 2 13 15 2
Lvov V. 5 5 5 5 * 4 20 5 1

P - number of victories
NU - number of injections given
PU - number of injections received
M - place

*) In fact, the computer prints these numbers in a column without commas.
**) Here, similarly, the computer prints the results of the battles of seven more pairs.
