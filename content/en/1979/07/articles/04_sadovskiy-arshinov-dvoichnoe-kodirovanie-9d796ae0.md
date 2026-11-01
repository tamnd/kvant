---
id: 1979-7-sadovskiy-arshinov-dvoichnoe-kodirovanie-9d796ae0
issue: kvant_1979_7
year: 1979
number: "7"
title: Binary coding
authors:
  - Садовский Л. Е.
  - Аршинов М. Н.
rubric: osnovnye-stati
page_first: 16
page_last: 22
page_labels: 14-20
tag: EP49
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3b80f24e26a35d6260c4a512c5f06bd65d37aad3ea86d75842b3af7e0877a399
prompt_sha256: draft-1
translated_from: content/ru/1979/07/articles/04_sadovskiy-arshinov-dvoichnoe-kodirovanie-9d796ae0.md
source_content_sha256: 0cd952f807cd4305f759389dbb70cc2efec7f4d696a2f961361d1f8b26f2ab08
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

Binary coding

How are messages transmitted over communication lines? The diagram of such a transmission is presented at figure.

The encoding device associates each transmitted message with a certain combination of signals (acceptable for transmission over a given communication channel), called a code. The operation of transmitting a message into a sequence of different signals is called encoding, the reverse transformation, which composes the transmitted message from the received signals, is called decoding. Codes that use two different chips are called double codes. Telephone dialect codes are Morse and Baudot. In Morse code, each letter is associated with a specific sequence of short-term (called washers) and long-term (world) current pulses. In the Baudot code, each letter is associated with a specific sequence of a patch of elementary signals - a pulse and a pause.

The coding process, when there are different types, the requirements for them, and many related problems are studied by the theory of information and coding. It combines probabilistic, algebraic and combinatorial methods.

Here we dwell only on some specific issues of coding, and we refer interested readers to special books - for example, A. M. Yaglom and I. M. Yaglom “Probability and Information” (M., “Hayka”, 1973), W. Peterson “Error-Correcting Codes (M., “Mir”, 1964), W. Peterson, E. Weldon “Error-Correcting Codes (M., “Mir”, 1964), W. Peterson, E. Weldon “Error-Correcting Codes (M., “Mir”, 1964), "World", 1976).

We ask - we answer

Dual coding is based on a very simple principle. Let's explain it using this problem.

Someone has thought of a number between 0 and 7. The guesser is allowed to ask questions, the answers to which are given only in the form of “yes” or “no”. How many questions can you ask to know for sure the intended number?

The most trouble-free way (this is what a child would probably do) is to sort through the numbers in a random way, finding

⟦folio 15⟧

good luck. With a very strong impact, it can store even one question, but if you are unlucky, you can get as many as seven. Therefore, let’s give up hope for instant success and try to build such a system of questions so that any of the answers to them - “yes” or “no” - gives us the same (empty, albeit incomplete) information about the intended number, and the number of questions is minimal.

For example, the first question might be: “Is the intended number between 0 and 3?” Both answers - “yes” and “no” - bring us equally closer to the goal: in general cases, there remain four possibilities for an unknown number (originally they were to be sung).

If an affirmative answer is received to the first question, then the second time you can ask: “Is the intended number zero or one?}; if the answer was negative, we ask: “Isn’t the intended number a four or a five?”

In any case, after answering the second question, there is a choice of two possibilities. In order to make this last choice, one question is enough. So, to guess the intended number, whatever it might be, three questions are enough.

If each of the two possible answers “yes” or “no” is conditionally designated by the symbols “0” and “1”, then the answer is written as a sequence consisting of 0 and 1. So, for example, if in the example discussed above the intended number was zero, then the answer to each of the three questions will be “yes”. Three “yes” correspond to the sequence 000.

If the number “3” was conceived, then the answers will be: yes, no, no. That is, the “three” corresponds to the sequence 011. Based on the results of the answers, you can create Table 1 below. Those of you who are familiar with the double number system will recognize in the bottom line the double notation of the corresponding numbers in the top line.

Note that together the sets of numbers from 0 to 7 can be considered any possible set, and we can define each of them

Table 1

⟦folio 16⟧

encode sequences of 0s and 1s of length 3. Sequences of 0s and 1s can encode any finite set of messages.

Indeed, there are $2^3 = 8$ double sequences of length 3 (all of them are given in the table), double sequences of length 4 are twice as many - there are $2^4 = 16$. In general, the number of double sequences of length $n$ is equal to $2^n$. Therefore, if you need to encode zeros and ones, for example, 125 messages, then double sequences of length 7 will be more than enough for this (we have $2^7 = 128$ of them at our disposal). Finally, to encode any number of $M$ messages, double sequences of length $n$ can be used such that $2^n \geq M$.

Fano code

Is it always beneficial to encode messages in words of the same length, as we did above?

Let's imagine that some messages have to be transmitted quite a bit, others - relatively rarely, and still others - in very exceptional cases. It is quite clear that the first best ones should be encoded with short words, leaving longer words for encoding messages that appear less frequently.

In mathematics, a measure of the frequency of occurrence of a message is its probability. Anyone who is not familiar with this concept can imagine the probability of a certain message (message) as the proportion of those cases in which it appears out of the total number of messages (messages) under consideration *). The probability of a message $A$ is denoted by $P(A)$.

Let four messages $A_1, A_2, A_3, A_4$ have probabilities

$$P(A_1) = \frac{1}{2}, P(A_2) = \frac{1}{4}, P(A_3) = P(A_4) = \frac{1}{8}.$$

*) See, for example, the above book by A. Yaglom and I. Yaglom.

This means that among, for example, 1000 messages transmitted, message $A_1$ appears about 500 times, message $A_2$ appears about 250 times, and message $A_3$ and $A_4$ each appear about 125 times.

These messages can easily be encoded in double words of length 2, as shown in the table:

| $A_1$ | $A_2$ | $A_3$ | $A_4$ |
| :--- | :--- | :--- | :--- |
| 00 | 01 | 10 | 11 |

At the same time, the likelihood of their occurrence is not taken into account. Let's do things differently now. Let us divide the messages into two equal groups: the first contains message $A_1$, the second - $A_2$, $A_3$, $A_4$. Let us associate the first group with the symbol “0”, and the second group with the symbol “1”. This is exactly the same as the two principles used in the guessing task. Indeed, the symbol “0” corresponds to the answer “yes” to the question “Does the message belong to the first group?”, and “1” to the answer “no”. The only difference is that previously the entire set was divided into two groups consisting of the same number of elements, now - from different ones. But, as before, the difference is such that both answers “yes” and “no” are equally possible. Continuing in the same spirit, let us divide the set of messages $A_2, A_3, A_4$ again into two equal groups. The first, consisting of one message $A_2$, we match the symbol “0”, the second, which includes messages $A_3$ and $A_4$, we match the symbol 1. Finally, we divide the remaining group of two messages into messages $A_3$ and $A_4$, we match the first symbol 0, the second – 1 (they are equally credible). The process is over. The message $A_1$ at the first step formed an “independent” group, and the symbol 0 was associated with it, which encodes this message. The message $A_2$ formed an independent group in two steps, in the first step it corresponded to the symbol 1, in the second - 0; this means that message $A_2$ is encoded by word 10. Similarly, for

⟦folio 17⟧

messages $A_3$ and $A_4$ we have, respectively, sequences 110 and 111. So, we get the following code table:

| $A_1$ | $A_2$ | $A_3$ | $A_4$ |
| :--- | :--- | :--- | :--- |
| 0 | 10 | 110 | 111 |

This is precisely the coding method proposed by Fano. The question arises: what have we gained in comparison with the uniform code by using the Fano code? To answer this, imagine that messages $A_1$, $A_2$, $A_3$, $A_4$ are transmitted in a continuous stream - 1000 messages in total. Let's calculate how many double symbols will be required to transmit them using the first and second encoding methods.

When using a uniform code, this is not difficult to calculate: for each message there are two characters, which means a total of 2000 characters.

Let us now use the Fano code. Let us remember that out of 1000 messages, the first one appears approximately 500 times, which is encoded with only one character (500 characters), 250 times the message $A_1$ appears, it is encoded with two characters (another 500), on the message $A_3$ and $A_4$, appearing approximately 125 times, makes it necessary to consume another $3 \times 250 = 750$ characters. In total, you need to transmit approximately 1750 characters. Will you win? Certainly. Indeed, in the second case, the transfer will take less time. One can imagine a situation where the benefit from using the Fano code turns out to be greater than in the example given.

Trust but verify

We have established that any finite set of messages can be encoded with codewords of 0 and 1 (binary codewords). The trouble is that errors are possible when transmitting encrypted messages.

As a rule, it is not in our power to completely eliminate the source of errors. How then can we protect ourselves from their influence and is this even possible for everyone? And if possible, then at what cost?

It turns out that such opportunities - to detect errors and even correct them - exist. But the inevitable price for this is the lengthening of the code words, that is, the addition of a certain number of characters. These symbols no longer carry information about the messages being transmitted, but can provide information about errors that occurred during transmission. In other words, their purpose is to monitor the correct transmission of the code word. The additional characters entered are called control characters (or verification characters).

All one check

The minimum tribute is to add only one verification character to each code word. Let's figure out what we can count on in this case. Let $\alpha_1 \alpha_2 \dots \alpha_n$ be a double codeword ($\alpha_i = 0$ or 1). Apparently, it is advantageous to choose the control character $\alpha_{n+1}$ so that its value is affected by each character of the codeword. The simplest thing is to put $\alpha_{n+1} = \alpha_1 + \alpha_2 + \dots + \alpha_n$ (mod 2) *. This notation means that the test character $\alpha_{n+1}$ is equal to zero if the codeword $\alpha_1 \alpha_2 \dots \alpha_n$ contained an even number of ones, and one otherwise. For example, adding such a check character to the word 1010, we get the word 10100; accordingly, from the word 1110 we get 11101.

Note that all deleted codewords $\alpha_1 \alpha_2 \dots \alpha_n \alpha_{n+1}$ contain a number of ones, that is, $\alpha_1 + \alpha_2 + \dots + \alpha_n + \alpha_{n+1} = 0$ (mod 2). (1)

Let us imagine that during the transmission process, a single error (or even any odd number of errors) is included in the remote codeword $\alpha_1 \alpha_2 \dots \alpha_n \alpha_{n+1}$.

*) You can read about addition “modulo” in N. Vilenkin’s article “Comparisons and classes of residues” («Kvant», 1978, No. 10).

⟦folio 18⟧

side). Then in the exclusive word $\alpha'_1\alpha'_2 \dots \alpha'_n\alpha'_{n+1}$ the number of ones will become odd. This serves as an indicator that the received word contains an error. Of course, we do not need to scrupulously count the number of units; it is enough just to check whether equality (1) is satisfied for the symbols of the accepted word - this is easy to do with the simplest computing device. If equality (1) is satisfied, we consider that the message was transmitted correctly, otherwise we state that an error has occurred, and, if possible, repeat transmission of the codeword is required. But we cannot correct the error on our own. For example, if the "wrong word" 11100 is received, then it is possible that any of the code words were sent:

01100; 10100; 11000; 11110; 11101.

Each of the listed cases corresponds to a single error. Errors can also occur in three or even five characters. It is much worse if there is a double error or even an even number of errors. After all, then the correspondence (1) will not be violated, and we will perceive the distorted word as correct, as a result a false message will be received.

The code described (called a general parity code) therefore allows detection of an odd number of errors, but leads to incorrect decoding if there are an even number of errors. It is preferable to use positomy when the probability of a single error is high enough and errors in a larger number of symbols are very unlikely.

Codes with several check characters are much more often used - this allows not only to detect, but also to correct errors, and not only single ones, but also multiple ones.

Slowest code

The simplest error-correcting technique is to repeat each information symbol several times so that the symbols 0 and 1 are encoded in blocks of $n$ zeros (respectively $n$ ones). When decoding a $n$-letter block that may contain erroneous characters, a decision is made by “majority vote”. If the received block contains more zeros than ones, then it is decoded as 00 ... 0, otherwise - as 11 ... 1. This decoding rule allows you to correctly restore the transmitted symbols if interference in the channel distorts less than half of the symbols in each transmitted block. If the block length $n$ is chosen large enough, then we will practically protect ourselves from possible errors, but the transmission of messages will proceed at a faster pace.

When with a general parity check and a code with repetition - two antipodes. The first one is very fast, but often “frivolous”. The second's ability to correct errors is theoretically limitless, but it does it too slowly.

From the messages expressed earlier, it can be seen that in order to correct errors it is necessary to use words for decoding that are quite different from each other. In this case, it is possible that when transmitting errors, they will most likely remain different, and the distortions do not prevent us from “guessing” the sent word.

Untrained total distance

We have come to an understandable distance between code words. The distance (more precisely, the Hamming distance) $ρ(x, y)$ between two codewords $x, y$ is the number of symbols in which they differ. For example, the distance between the words 1010111 and 0110010 is 4 - they differ in the characters in the 1st, 2nd, 5th and 7th places.

The term “distance” for the quantity $ρ(x, y)$ is determined by the fact that it has the basic properties of the general distance between points on a plane or in space (item 4 in “Geometry 6” or item 132 in “Geometry 8”).

⟦folio 19⟧

An important characteristic of a code's proofreading ability is its code distance $d$, which is defined as the minimum distance between different codewords $\min \rho(x, y)$.

It is clear that the greater the code distance, the more correcting abilities a given code has. We can formulate this fact more precisely:

For a code to correct combinations of $t$ (or fewer) errors, it is necessary and sufficient that its code distance be greater than 2$t$.

Indeed, if this is the case, then $\rho(x, y) \geq 2t + 1$ for any codewords $x$ and $y$. If, as a result of distortions, both words turned into one word $z$ (i.e., they became indifferent), then (due to one of the properties of distance - the triangle axiom)

$\rho(x, z) + \rho(z, y) \geq 2t + 1$, and therefore either $\rho(x, z) > t$ or $\rho(z, y) > t$. This means that any errors in $t$ or fewer characters of any codewords $x$ and $y$ leave them still different, and therefore the original can be restored. The converse statement is even easier to prove.

Exercise

1. There are 8 double codewords of length 3. They can be depicted in a spatial coordinate system as the vertices of a cube on side 1. What is the “geometric meaning” of the distance between codewords in this case?

2. Prove that a maximum double code of length 5 (that is, a code whose all codewords are of length 5) with a code distance of 3 contains 4 codewords. Specify this code.

3. Is there a code of length 20 that contains 1000 codewords and corrects a codification of three or fewer errors?

4. Prove that to detect $s$ (or fewer) errors it is necessary and residual that the code distance $d \geq s + 1$.

5. Prove that in order to correct $t$ (or less) errors and at the same time detect $s$ (≥ $t$), it is necessary and residual that the code distance satisfies the inequality $d \geq t + s + 1$.

Hamming code

Let the number of messages that need to be transmitted to the subscriber be 16. To encode them, you can use words of length 4, but then the code will not correct errors. We already know that when using words of length 5, any single error in the code word can be detected, but, alas, cannot be corrected. Two additional characters are also not enough to correct single errors (check this yourself).

But three additional symbols can be used in such a way as to identify and correct any single error.

Let's assume that we managed to specify 16 codewords of length seven - $\alpha_1\alpha_2\alpha_3\alpha_4\alpha_5\alpha_6\alpha_7$, for which, according to model two, the following equalities are satisfied:

$$\begin{cases}
S_1 = \alpha_4 + \alpha_5 + \alpha_6 + \alpha_7 = 0, \\
S_2 = \alpha_2 + \alpha_3 + \alpha_6 + \alpha_7 = 0, \\
S_3 = \alpha_1 + \alpha_3 + \alpha_5 + \alpha_7 = 0.
\end{cases}$$

Then the digit in which a single error was made is indicated by a double notation number $S_1S_2S_3$ (recall that each $S_i$ is a 0 or 1). In particular, for codewords this number is 0 (= 000), which indicates that there is no bit in error.

The statement made follows from the fact that with our encoding (i.e., with our set of code numbers) for a double word of length 7 with a single error $S_1 = 1$ if and only if this error is made in the fourth, fifth, sixth or seventh digit (see (2)), $S_2 = 1$ if and only if the error is in the second, third, sixth or seventh digit, and $S_3 = 1$ - when in the first, third, sixth or seventh.

Let, for example, $S_1 = 1$, $S_2 = 0$, $S_3 = 1$. Then the error is in one of the last four digits ($S_1 = 1$), but there is no error in the last two digits ($S_2 = 0$); this means the error is in the fourth or fifth digit; since $S_3 = 1$, it is in the fifth rank, but $S_1S_2S_3 =$

⟦folio 20⟧

=101 is precisely the double notation of the number 5. The remaining cases are treated similarly.

It remains to find 16 code words that satisfy correspondence (2). To do this, it is enough to replace that if $\alpha_1, \alpha_2, \alpha_3$ and $\alpha_4$ are chosen arbitrarily and mod 2 the equalities hold

$$\begin{cases}
\alpha_5 = \alpha_2 + \alpha_3 + \alpha_4, \\
\alpha_6 = \alpha_1 + \alpha_3 + \alpha_4, \\
\alpha_7 = \alpha_1 + \alpha_2 + \alpha_4,
\end{cases}$$

then correspondences (2) are true.

The code studied here is a length 7 Hamming code with four informatonic symbols.

In general, the codewords of a double Hamming code that corrects a single error have a length of $2^m - 1$. To determine the position of the error, $m$ checks are then needed, i.e. $m$ test characters. The remaining $2^m - 1 - m$ characters are informational.

List of readers who sent rules for solving problems from the Problem Book «Kvant»

In this issue we publish the names of readers who sent rules for solving problems M516 - M530, F523 - F532 (bold numbers after the last name are the last digits of the numbers of solved problems).

Mathematics

K. Abdukhalikov (Alma-Ata) 16-18, 19a), 20, 21, 26-28; E. Abramchkin (Kuibyshev) 16a); I. Avemisyan (Mulki village, ArmSSR) 18; O. Avrammava (Moscow) 21; A. Adeev (village of Pokrovka AzSSR) 166), 21, 22, 24, 26; S. Aznabaev (Novotroitsk, Orenburg region) 26; V. Hayriyan (Hrazdan) 16a), 6) 18, 20, 22, 24, 26, 27; Z. Alaverdyan (Ijevan) 26; V. Aliev (Tbilisi) 26; V. Andrusevich (Kobrin) 28; R. Ardan (Lviv) 28; K. Aromamyan (Kafan) 26; N. Arutina (Kyiv) 28; A. Akhmetkhozin (Anjan) 27; A. Ashkinazi (Moscow) 16-19; D. Babarikin (Magnitogorsk) 16a); A. Badalyan (Berd village, Armenian SSR) 16, 21-23, 26-28, 30a); B. Baysakalov (Alma-Ata) 166), 18, 19, 21, 24, 26-29; A. Balinsky (Dublyany village, Lviv region) 16, 18, 19, 21-24, 26-28, 30; I. Baranets (Dzerzhinsky village, Moscow region) 26-28; A. Barvinok (Leningrad) 28, 29; A. Barre (Nikolaev)

16a; 6); B. Beun (Moscow) 16, 21; A. Beluosov (Kaliningrad, Moscow region) 26; S. Bespamyatnykh (Artemovsky, Sverdlovsk region) 19a), 24, 27, 28; V. Bobov (Leningrad) 26; N. Bovsunovsky (village of Putlyuvchi, Zhytomyr region) 21; T. Bolotnikov (Kharkov) 16, 18, 19a), 21, 26, 28, 29, 30a); A. Bortsev (Leningrad) 19, 26-28; V. Borovko (Novopoloshk) 26; I. Borodin (Solikamsk) 22, 23; O. Bokhonov (Moscow) 21, 22, 236), 24, 26, 27, 30a); A. Bratsisky (Voronezh) 24; A. Burin (Moscow) 28; A. Vasiliev (Saratov) 16a), 21, 26, 28, 30a); S. Velikovich (Minsk) 28; V. Vinorezadov (Moscow) 16, 18, 19a), 21, 22, 23a), 24, 26-28, 30a); A. Voronov (Moscow) 16; A. Gabovich (Kharkov) 26; E. Gadzhilarov (Tbilisi) 26-28; A. Galenko (Moscow) 16a), 6), 26; E. Galstyan (village of Aygezard ArmSSR) 18; N. Gasilov (Baku) 26; K. Gedalin (Tbilisi) 26; A. Gilman (Moscow) 16, 18, 19, 21, 22, 24, 26-28; L. Gitlin (Vitebsk) 16a), 6), 21, 23; M. Gladina (V. Volochek) 21; Yu. Glukhov (Shelkovo) 166), 18, 21, 28; A. Golovin (Moscow) 21; O. Gordienko (Pavlodar) 16a), 21, 22, 27; M. Gorolev (Belorotsk) 16, 18, 19, 26, 28, 30a); G. Grabarnik (Tashkent) 26, 27, 29, 30a; G. Grabuzhik (Tashkent) 16, 18-24; P. Grigoruk (Gayvoron) 21, 24; N. Gribere (Kyiv) 26, 28; L. Groysman (Kharkov) 28; V. Guba (Vologda) 16, 18-21, 24-29;

(Continued on page 32)
