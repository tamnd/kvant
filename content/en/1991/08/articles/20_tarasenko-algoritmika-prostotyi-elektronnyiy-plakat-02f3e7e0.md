---
id: 1991-8-tarasenko-algoritmika-prostotyi-elektronnyiy-plakat-02f3e7e0
issue: kvant_1991_8
year: 1991
number: "8"
title: Algorithms of simplicity. Electronic poster
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 76
page_last: 78
page_labels: 74-76
lang: en
source: kvant_digital
extraction: vision
content_sha256: f8e95906d7bfca2af38d406f7c2a1102f660565f59ea15c7d64c1a7825a00f1d
prompt_sha256: draft-1
translated_from: content/ru/1991/08/articles/20_tarasenko-algoritmika-prostotyi-elektronnyiy-plakat-02f3e7e0.md
source_content_sha256: 7681736e3ea26820884fd1a0aa49bb6ef1e961368733df89d81da77cd2393010
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 74⟧

---
running_head:
folio:
---

Algorithmika
simplicity
Electronic planat
V. TARASENKO
It's not an easy question,
No more than one thing:
Everything is complicated and simple,
Count it wisely!

“We all learned a little something, somehow.” And not only during the time of A.S. Pushkin. In the not-so-distant yesterday, in the very insignificant today. Apparently, we will study the same principle tomorrow.

If you look at it, it’s not such a flat principle. Who, honestly, can honestly say that they only studied at school? We learn and teach, shape ourselves and educate others in the most seemingly incredible situations. Man is designed in such a way that every day, along with his bread, he must receive and transmit a portion of information. The role of a teacher has not yet passed anyone by! You can become one even at a very early school age. For those who find it difficult to choose objects for their programmatic, pedagogical and social research, we suggest paying attention to older or younger brothers, parents, grandparents, children and inside.

Niklass Wirth, a world-famous scientist from Switzerland, author of the Pascal and Modula-2 programming languages, and a recent guest of the TV program “Dialogue with a Computer,” believes that teaching all children computer literacy to the level of highly qualified programmers would be unrealistic and a recent thing. But it is necessary to show as many children as possible the capabilities of computers and programs, and the sooner the better. We would add that the more business-minded, unhinged, simple and secure the devices are, the smarter it is. We have already agreed with the readers on the use of just such simple computers for business. It would be something to show. So, another program.

If we see a hammer, we immediately know that they are hammering nails with it; if we see a shovel, then we know that they are digging the ground. No one agrees on the purpose of the program unless everything is said about it in advance. Today we present to the reader a demonstration cyclic generator of the first 25 prime numbers. It was shown to Svetlana, a 3rd grade student from the city of Gatchina near Leningrad, who was not burdened by great knowledge and worries about life in the household. And this cheerful creature stopped its entertainment for 10 minutes to get acquainted with the results of the demonstrator’s work. Moreover, I remembered more than half of the presented prime numbers, which I learned about for the first time in my life!

So, before attending directly to the description of the program, we wish you both student and teaching success. We still believe that the majority of our readers are prime number and programming researchers. And every self-respecting researcher is obliged to know not only some of what has been done before him, but also how this relates to his immediate environment.

Program 3. Demonstrator of the first 25 prime numbers

All secondary guns from V3-34 to MK-61 are suitable. Curriculum for programming and mathematics classes of any age category, starting from senior kindergarten groups. The program sequentially presents prime numbers from 2 to 97 inclusive. The principle of a spreadsheet is used, in which all presented numbers are written down in advance and

⟦folio 75⟧

---
running_head:
folio:
---

Text of the program with step-by-step comments

00 V↑ 0E /+ Transfer starting number AND from PrX to PrY
01 2 02 /+ Set
02 6 06 /+ constants 26
03 ↔ 14 /+ PrX:=And and at the same time PrY:=26
04 - 11 /+ N:=26 - I
05 BP 51 /+ Unconditional jump
06 09 09 /+ per step 09
07 2 02 /+ Set
08 5 05 /+ constants 25
09 X→P 0 40 /+ Pr0:=N
10 9 09 /+ Set
11 8 08 /+ constants 98
12 P→X 0 60 /+ PrX:=N
13 3 03 /+ Constant 3
14 × 12 /+ N×3
15 - 11 /+ A=98 - Н×3, starting address of the subroutine
16 X→P 9 49 /+ writing the address A of the subroutine to Pr9
17 Checkpoint 9 —9 /+ Access to the subroutine at address A=Pr9
18 S/P 50 /+ Storp indication of the selected prime number
19 F L0 5Г /+ Pr0=0? Checking the end of a cycle
20 10 10 /+ Go to step 10 if the cycle is not completed
21 BP 51 /+ Unconditional jump if the loop is finished
22 07 07 /+ to step 07

Teams 26-97 consist of 24 groups of 3 teams each, all of them are the same, the first two teams are to dial the next prime number, the third is to return to the main program. To save space, we present only the first and last groups and the numbers collected in intermediate groups.

23 0 00 /+ Recruitment in subprogram
24 2 02 /+ prime number 02
25 B/0 52 /+ Return to main program

Next, dial the numbers 03, 05, 07, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89.

95 9 09 /+ Set in subroutine
96 7 07 /+ prime number 97
97 B/0 52 /+ Return to main program

their selection is controlled by the main part of the program.

Registers and variables used: A=Pr9 - starting address of the blank subroutine; H=Pr0 - additional up to 26th serial number of the next prime number; Of the stack registers, only PrX and PrY are used explicitly.

Description of the algorithm

Based on the given starting number AND of a prime number, using the formula A=98—3×H, where H=26—AND, the starting address A of the subroutine is calculated, displaying this prime number on the indicator, after which the transition to this subroutine is carried out, and after returning from it, the PMC is stopped. Upon subsequent launches of the PMC (using the C/P key), N is automatically decreased by one, as a result of which the following prime number is called up for display; after processing the last prime number (at H=1), the transition to AND=1 of the assignment H:=25 occurs, thereby recording the demonstration process.

Evaluation of program speed: “calculation” of the starting number using the B/O commands, as well as the transition from 97 to 2 is completed in 6 seconds; the next larger prime number is displayed after 4 seconds.

Instructions

After typing the program and switching the PMC to counting mode, press the B/O key. Then dial the number AND the starting prime number (in the range

⟦folio 76⟧

---
running_head:
folio:
---

zone from 1 to 25 inclusive) and press the C/P key; after the PMC stops, the I-th prime number will appear on the indicator. New presses of the S/P key will cause the following prime numbers to appear on the indicator until the last one, and then the first one will appear, etc.

To find out the AND number of the next prime number (after the C/P series), you need to manually execute a sequence of commands

26 P→ХО —
— the indicator will show the value I.

Program 3 is most effective if written to the MK-52's non-volatile memory. For MK-61 and MK-52 this program can be supplemented (starting from step 98) with a subroutine showing the prime number 101. It can be called manually with a sequence of commands

B/O 26 S/P

and the number 101 will appear on the indicator. To return to the main loop after such a call, you need to press the B/O key again. If you want the PMC itself to show this number after 97, and then return to the number 2, then you need to add a program (think about it yourself). Those who will experiment on the “tail” of the PMC memory program must remember that the address counter shows steps 100, 101, 102, etc. in the form -0, -1, -2, etc., but in the program itself these addresses must be generated in a general form, i.e., as 100, 101, 102...

We are confident that our volunteer teacher-programmers themselves understood when it is possible to tell students about the structure of this cyclic demonstrator, and when it is necessary to show only the results of its work. The latter, for example, in kindergarten. Isn't it?
