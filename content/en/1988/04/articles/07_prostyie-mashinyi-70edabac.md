---
id: 1988-4-prostyie-mashinyi-70edabac
issue: kvant_1988_4
year: 1988
number: "4"
title: '[Simple machines]'
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 42
page_last: 45
page_labels: 40, 42, 43
tag: 1TTV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9c7a1299326bbb3318e0db478c242bfff80d8eeff9a2521ea28134d2ff66ab17
prompt_sha256: draft-1
translated_from: content/ru/1988/04/articles/07_prostyie-mashinyi-70edabac.md
source_content_sha256: b511239560201fbd0b23ea60547c73a803ca3a5eeb9ead0b0cd2949f37bbd4e9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

40

Archimedes let the Isseo machine go
Putarch

Issues and tasks

1. In what direction will the coils shown at figure move under the influence of a small force F?

2. Steel balls are balanced on a weightless lever. Will the balance be disrupted if the balls are submerged?

Issues and tasks

4. The lever is balanced, as shown at figure, by the forces F₁ and F₂. Will the force F₃ upset the equilibrium?

5. They try to move the bars from their place with a lever. Will each of the bars move if their masses are the same?

Issues and tasks

7. The boy pulls himself up and uses a stationary block. Does he gain in strength?

8. What should be the angle at the base of the wedge so that it can be used to tip the load?

⟦folio 42⟧

are called by a double number system. On punched tape used in a computer for storing and transmitting information, the first 9 digits look like this:

The number 0 corresponds to a space. Small test points in the middle of the punched paper tape serve to move and fix it.

For those who are not familiar with the double number system, let us inform you that it, like the decimal system, is a positional system: the value of the value of a number depends on the digits included in the number and on their places in the writing of the number. And if in the decimal system 10 units of the previous digit make up a unit of the next digit, then in the binary system the unit of the next digit is made up of two units of the previous one. Therefore, to write numbers in the double system, only two digits are enough - 0 and 1:

$$1=1_2, 2=10_2, 3=11_2, 4=100_2,$$
$$5=101_2, 6=110_2, \dots$$

(the small number 2 to the right of the number means that the entry was made in the double number system).

Compare these records with the punched tape at figure, you will see that a breakdown on the punched tape corresponds to the number 1 and its absence corresponds to the number 0.

The machine reads the entries on the punched tape using photocells: they mark test responses using light shining through the responses (in non-trial areas, the tape blocks the photocell from the light source).

The so-called band code is based on a similar principle.

Many of you, probably, paid attention to the striped rectangle found on the labels of various imported goods (Fig. 1):

Fig. 1.

What do these stripes mean? It turns out that they are used to record the location of attention - the product code. The computer located in the cash register reads the code using photocells (to do this, either hold a plate with the code in a special place on the cash register, or use a “pencil reader” connected to the cash register to read the code). This way the computer receives information about the product being sold. In accordance with it, he produces from his memory the price of the product, and he remembers that a copy of this product was purchased. As a result, at every moment it is known how many copies of which product were purchased and for what amount, and which product still needs to be delivered to the sales floor.

But how does the stripe code work?

Using stripes, you can write a number the same way as on punched tape: a thin black stripe is 1, and a thin white stripe is 0 (Fig. 2). But the number can be represented in different ways. You can simply write it in the dual number system (for example, the number 5 762 752 950 is written in the dual system like this: 101 010 111 011 111 001 010 000 110 110 110₂). Or you can write each digit in the double system - then there will be four stripes per digit, and then represent the number by a set of stripes obtained.

Fig. 2.

In the example given at figure 1, each digit is also written separately, but not in the double system, but in a different way. Each number corresponds to seven symbols 0 and 1. The code consists of two parts - left and right, the numbers in the left and right parts are written in accordance with the table (see p. 43).

Let's look first at the left side of the table. It can be seen that the recording of each number begins with 0 and ends with 1; these signs do not characterize numbers, but serve to separate

⟦folio 43⟧

one number from another. The number itself contains 5 characters, and they are chosen so that any two numbers appear in at least two places. It is easy to see that the entry of numbers on the right side of the “symmetry” table is the entry on the left, namely, instead of the number 0, the number 1 is in the corresponding place, and together 1 is worth 0.

On figure 1, each number corresponds to the described combination of seven stripes located above it. Everything we said applies to “short” stripes. The first three “long” stripes, the middle and last stripes (their corresponding sets of 101) are indicators of the beginning, middle and end of the cipher. The long stripes that follow the trays first correspond to the number located on the side to the left (number 0 on figure1). Likewise, the long stripes in front of the last treyar stripes correspond to the number located on the side to the right (number 6 on figure1).

These "side" numbers serve to protect the reading from errors. Their values ​​are similar so that three times the sum of the numbers in the even places, added together with the sum of the numbers in the odd places, is divisible by 10. The summation is done from left to right; It is believed that the number on the left side is at zero (the value that we should). In our case (see Fig. 1)

$$3 \cdot (0 + 7 + 2 + 5 + 9 + 0) + (5 + 6 + 7 + 2 + 5 + 6) = 100.$$

If the computer reads one of the numbers incorrectly, it will immediately detect the error. The computer will not be able to detect an error only if it reads at least two digits incorrectly, and in such a way that the errors are “compensated” and the resulting amount is again divided by 10. But the likelihood of this happening is extremely low.

This error-proofness is very important, otherwise the computer might charge the buyer the price of, say, a box of chocolates for a loaf of bread.

Error protection is also built into the standard form of writing a postal code. You can read about this in the article by tenth grader Y. Karpov “Optimal postal code encoding” («Kvant», No. 11, 1987).

In conclusion, we note that recently a lot of people write the field like this: Ø. These are professional programmers. The fact is that in a computer program, letters and numbers can move quite arbitrarily. To distinguish zero from the letter 0, the notation Ø was introduced. These systems have possible errors when using the Latin font. And when using the Russian font, it will be possible to confuse the letter 3 with the number 3, and the letter CH with the number 4. Is it possible that these numbers will “change”?
