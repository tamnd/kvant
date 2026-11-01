---
id: 1980-7-evm-na-olimpiade-5fa392b2
issue: kvant_1980_7
year: 1980
number: "7"
title: Computers at the Olympics
rubric: raznoe
rubric_sub: Разное
page_first: 33
page_last: 37
page_labels: 31, 32, 34, 35
tag: N98R
lang: en
source: kvant_digital
extraction: vision
content_sha256: e2344511286f24b34d32232235f237173fd2b7f51e3df7525e0702ca1b8e4678
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/11_evm-na-olimpiade-5fa392b2.md
source_content_sha256: 80473de9113fda7a008c54e760b06d4b0fae98afb0161d9ce7bbbed7cb99659b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

Computer at Olympiad

The sports applications of computers are unusually wide - from statistical analysis of the results of a football championship to drawing defense and attack schemes, from drawing up a schedule for a basketball tournament to processing the results of monitoring the psychophysiological state of athletes, from predicting the results of sports games to drawing up protocols for boxing matches.

At the XXII Olympic Games in Moscow, computers will be full members of the Organizing Committee, panels of judges, and press centers.

The section “The Art of Programming” of the Olympiad issue «Kvant» presents a story about two ordinary Olympiad problems solved by computers at the forefront of sports battles - at the judges' tables in the buckle sector of the stadium and on the fencing track. Here are algorithms for two tasks related to the processing of operational documents of sports conditions. These algorithms were at one time programmed in Cobol and BASIC - programming languages ​​that are familiar to a number of our readers, but, in any case, have not yet been described on the pages of the Quantum Correspondence School of Programming.

We propose to create a program for each of these algorithms in the Rapier language, which is familiar to the reader «Kvant» from lessons 5-8 of the Correspondence School of Programming («Kvant», 1980, No. 1-3). You can send your programs to the same address to which you write to the Correspondence School.

Robik and Rapier, which you took in the Correspondence School lessons, are interactive programming languages: you can compose, run and correct programs in these languages ​​directly from the terminal console.

In the program examples given in the Correspondence School lessons, it is assumed that the author of the program, or, in any case, a user familiar with the relevant programming language, is working at the terminal. The articles published in this issue talk about the programs used by judges and athletes, that is, users who, as a rule, are not familiar with programming.

Therefore, the dialogue should be organized so that the user does not have to think about assignments, procedure calls and other features of the program. If, while the program is running, you need to find out from the user the meaning of a certain name, you must use the standard INPUT function. For example, if in some process the operator

ENTER(0)→SURNAME;

then an invitation to dialogue will appear on the terminal screen - the “-” symbol, and the machine will wait for the user to type the desired text on the keyboard. This text will be considered the result of the function, that is, it will be assigned the name LAST NAME.

If the number 0 is specified as a parameter of the INPUT function, as in the example above, then on the pages of the Quantum Correspondence School program the text is considered, that is, lines are added to it on the right and left. If, for example, the user typed the words IVANOV in response to the invitation, then the value of names SURNAME will be the text 'IVANOV', and if the user types 510, the value of names will be the text '510'.

In the event that you need to ask the user for a number with which you will then perform some arithmetic operations, the parameter

⟦folio 32⟧

The ENTER function must be one, not zero.

Let's give an example of a small procedure using the INPUT function and a log of the user's dialogue with the computer when performing this procedure.

Let's say you need to fill in your last name, old number, and country name. It is convenient to fill in information about each section in the form of a tuple, and information about all sections forms such tuples. Let's give this set the name LIST. In the example below, the text being printed by the machine is in red font.

PERCENT RECORD;
<* *> -> LIST;
PRINT('INSERT THE NUMBER OF PARTICIPANTS');
ENTER (1) -> NUMBER; 1 -> COUNTER;
BYE COUNTER = <NUMBER::
PRINT('PARTICIPANT'S LAST NAME');
ENTER (0) -> LAST NAME;
PRINT('START NUMBER');
PRINT('COUNTRY'); ENTER(0) ->

COUNTRY;
COUNTER+1 —> COUNTER;
— LIST+<*<SURNAME, NUMBER.
COUNTRY>*>—LIST;
ALL
KSC:
NOTE:
SPECIFY THE NUMBER OF PARTICIPANTS
—3
PARTICIPANT'S LAST NAME
— IVANOV
STARTING NUMBER
—15
COUNTRY
—USSR
PARTICIPANT'S LAST NAME
— LEROY
STARTING NUMBER
—17
COUNTRY
-FRANCE

As a result, a set of LISTS will be formed: <*< IVANOV, 15, USSR>, <LEROY, 17, FRANCE>*>

Please note that we do not show here an example of a program that prints a list of sites. Programming beautiful, “formatted” calculations is quite a serious task, which will be considered in the Correspondence School lessons of the program in «Kvant» after the summer holidays. But this does not prevent you, of course, from trying to find ways to beautifully display lists, tables, and protocols.

So, try to apply your knowledge of Rapra and the input rules that were told to you today. Readers who submit the best sports programs will be awarded Olympic souvenirs.

Introducing the authors speaking today in the “Art of Programming” section:

Yu. A. Pervin, candidate of technical sciences, senior researcher at the Computing Center of the Siberian Branch of the USSR Academy of Sciences, a judge of the republican category in athletics, wrote about high jumps;

Ilona Lapushonok, a third-year student at the Moscow Institute of Physics and Technology, a member of the Siberian fencing club “Victoria”, talks about fencing; She made a program for her club’s tourists when she was in 10th grade at 130 schools in Novosibirsk.

⟦folio 34⟧

The list of athletes called for an attempt may be incomplete: according to the rules, some participants can pass the initial height.

If the called participant fails the attempt, the judge enters a check “—”, which is recorded by the program in the places provided for marking the results of the corresponding attempts at this height.

An unsuccessful attempt is marked by the judge, who enters the “×” symbol. If “×” is at the same height, it means that the participant failed to cope with this height and finished the competition (this information is stored in the machine’s memory

This is converted to the following mark “.”).

If a participant gives up one or two remaining attempts and moves them to the next height, then at the next height he can receive the mark “.” after, corresponding, two or one nudacc. The result of an athlete who has completed the competition is considered to be the highest height he achieved. Service mark "." (“finished”) allows the computer to invite only participants who continue the competition to jump (they do not have the “.” mark). After completing all jumps, before counting the results, mark "." must be erased.

A successful attempt - conquering a height - the judge marks with water the symbol “√”.

The data structure can be easily described, so use the protocol form (see table). The hero of the novel by I. Ilf and E. Petrov “The Golden Calf” could take part in such a city competition. The sports results, of course, are significantly lower than the Olympic ones: after all, neither the highly active O. Bender, nor the caring A. Koreiko, who cared about his sports form, ever laid claim to Olympic medals. This program, compiled according to the intended specifications, can equally successfully service

Protocol of the high jump competition for recess in Chernomorsk
Olympus Stadium, July 19, 1980

| No. | Participant's last name | Start number | Sports club | Results |
| :--- | :--- | :--- | :--- | :--- |
| 1. | Ptiburdukov | 114 | Pegasus | X X V X X V X V |
| 2. | Bender | 116 | Antelope | — — — X V V V |
| 3. | Lokhankin | 117 | Crow's word | — — — V V V |
| 4. | Berlaga | 118 | Hercules | V V V V X X V X X X |
| 5. | Borisholsky | 122 | Hercules | V V V X X V X X X |
| 6. | Bomze | 123 | Hercules | X V X X X X X X |
| 7. | Koreiko | 124 | Hercules | V V X X V X X X |
| 8. Panikovsky | 127 | Antelope | X X V V V V V |
| 9. Giggenshivili | 128 | Crow's word | V V V V X X V X X |

Chief judge of the competition
A. Balaganov

⟦folio 35⟧

Live both transfer school and the Olympic Games.

To describe the data, it is useful to use the concepts introduced in the Rapier language («Kvant», 1980, No. 2). A few recommendations:

— The result of each participant at the same height, that is, information about his completion of, generally speaking, three attempts, is represented as a tuple

"HEIGHT, 'ATTEMPTS'"

here HEIGHT is the value (in centimeters) of the height under the bar, and 'ATTEMPTS' is a string consisting of three characters; the meanings of these characters can be the signs “×”, “√”, “—” or space; if ATTEMPTS contain information about only one or two attempts (for example, the height was taken on the first attempt, therefore, there is no need to accurately or mark in place the remaining attempts of this height), then a space is written in place of the remaining attempts, for example:

<190, '××√'>, <195, '√—'>, <200, '——'>

(the symbol “—” is an image of an insignificant space).

— The totality of the results of one participant is represented by a tuple whose name is RESULTS, and whose elements are individual results.

— Each line of the protocol is information about one participant; they form a tuple called PARTICIPANT:

<№, LAST NAME, START NUMBER, SPORTS CLUB, RESULTS, BEST RESULT, PLACE>

- The collection of PARTICIPANT tuples forms a set with the name PROTOCOL, which, in fact, represents the result of the program - this is a set printed in the form of a completed table.

— The PARTICIPANT tuple is necessary only to generate the final result; for intermediate stages, information about the participant must be supplemented

a) a one-character string SERVICE MARK, the values ​​of which can be “.”, “!”, “*” or a space.

6) integer value NUMBER OF FAILED ATTEMPTES,

c) the integer value TOTAL NUMBER OF ATTEMPTES;
the last two values ​​are used in the program when applying rules 3 and 4 for the distribution of places.

Try to create a program on Rapila that processes protocols for high jump competitions and consists of three (unequal) parts:

1) entering the permanent part of the protocol - serial numbers, surnames and start numbers of participants, their club affiliation;

2) entering competition results - filling out the central part of the protocol;

3) distribution of participants by place - filling out the last columns of the protocol.

To program the second part of the program, it will be useful to analyze the printout of fragments of the dialogue between the judge and the computer that takes place at our competitions (his messages are typed in red for identification):

— 175
PTIBURDUKOV JUMPS No. 114
"PEGASUS"
FIRST ATTEMPT
GET READY BERLAGA No. 118

— ×
BERLAGA JUMPS No. 118
"HERCULES"
FIRST ATTEMPT
GET READY
BORISOHLEBSKY No. 122

— √

...
GIGIENISHVILI JUMPS
№ 128
"CROW WORD"
THIRD ATTEMPT

— ×
PARTICIPANT GIGIENISHVILI
№ 128
COMPETITION FINISHED
