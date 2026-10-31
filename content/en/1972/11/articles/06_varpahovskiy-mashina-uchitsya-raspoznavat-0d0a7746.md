---
id: 1972-11-varpahovskiy-mashina-uchitsya-raspoznavat-0d0a7746
issue: kvant_1972_11
year: 1972
number: "11"
title: The machine learns to recognize
authors:
  - Варпаховский А. С.
rubric: osnovnye-stati
page_first: 20
page_last: 22
page_labels: 18, 20
tag: H4M0
lang: en
source: kvant_digital
extraction: vision
content_sha256: f42b084aced6fd96e1421f05fe7d02e343405102bd8e3ad389507619acb0230e
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/06_varpahovskiy-mashina-uchitsya-raspoznavat-0d0a7746.md
source_content_sha256: 31b20b3684b09a125ba15fa773479c8f2f9abef7e5633f9abce7c7f8b4d9595b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

As you very much know, to solve any problem on an electronic computer (computer), the machine must be “informed” the initial data of the solution and the program of actions that need to be performed on this data *). Having received such information, the computer carries out the proposed actions on the data (“thinks”) and as a result obtains the desired solution.

Today's computers have learned to “think” very well, but are still extremely slow in perceiving (“reading”) the necessary preliminary information: they resemble a first-grader who does well in arithmetic, but is far behind in reading.

Every computer is built from a certain (very large!) number of “elements” that can be in two different states; For clarity, you can imagine each such element as a light bulb, which is either turned off (state 0) or on (state 1). Therefore, everything that is communicated to the machine must first be “translated” into the language of zeros and ones. Any information - be it a set of numbers, a control system or a chess position - is “recorded” in the machine in the form of suitable sequences of zeros and ones. To store and record the necessary information, the computer is first specialized in a device - memory. Computer memory is a set of cells consisting of a certain number of elements each (say, six). In any cell you can write any sequence of zeros and ones (the number of different such sequences is 2⁶=64).

Let’s say, for example, that the machine needs to “tell” the number 19. To do this, the number 19 is first assigned a certain code in the form of a sequence of zeros and ones: 010011 *). Then this code is applied to a special tape (punched tape): holes are punched in the right places on this tape. Finally, the tape is introduced into a machine, which, in accordance with the holes on the tape, converts the elements of the cell allocated for recording a given number into the required states. The process is schematically depicted in figure 1.

It is easy to imagine how much time it takes to produce a tape, how labor-intensive the process turns out to be when the machine needs to communicate more data. How can we simplify and automate data transfer to a machine? Is it not possible to give the machine the information it needs in a general form (say, in the form of directed text), leaving the encoding to the machine itself? In principle, of course, it is possible. But for this

*) See, for example, the articles by R. S. Guter “What Machines Can Do” («Kvant» No. 5, 1970) and “Human Language and the Language of Machines” («Kvant» No. 10, 1971).

⟦folio 20⟧

Fig. 3.

in 10 consecutive memory locations as shown in figure 3.

All other stages are entered into the machine's memory in the same way. In the process of reading, each letter being read is checked for sequence at all stages. When checking at the next stage, the machine compares the contents of each cell (colored or uncolored of this cell) with the state of the corresponding element of the memory cell and counts the total number of “differences”. After comparing with all stages, the machine selects the one for which the number of differences is the smallest; the code of the selected letter is transferred to the next memory cell, and the machine proceeds to reading the next letter.

This mechanical reading of a predetermined font was quite reliable, although errors cannot be ruled out even in this case. It is not difficult, for example, to imagine that the letter “C” may, due to various irregularities, turn out to be “closer” to the stage of the letter “o” than to its own. Additional difficulties are associated with the introduction of capital letters and punctuation marks (full stop, comma, etc.).

The main inconvenience of this reading system is its inflexibility: if you change the font a little, the reading ceases to be correct. This happens because with this method of reading, the computer distinguishes letters not by the characteristic features of their shape, but by the specific way they are written. The letter “O” from another font may differ significantly from the stage one in the correspondence of its parts: be narrower, have larger curves, etc. The number of discrepancies (when compared with the step letter “O”) then turns out to be very large, and the machine can “confuse” the letter “O” with some other letter. Consequently, when switching to another font, new stages must be introduced into the machine, forcing the machine to “learn” the alphabet anew each time.

It is desirable, of course, to force the machine to correctly recognize letters solely by their structure, structure - so that even significant differences in the correspondence of the parts of the letter do not affect the reading result. Here, however, lie the main difficulties, which are especially clearly manifested when reading handwritten texts. For example, even the same person writes the letter “a” differently in different cases, not to mention different ones. And if a person, breaking up any text, resorts to the help of numerous semantic, logical and grammatical connections, then the machine for such assistance, generally speaking, unnecessarily and properly relies only on its “sight.”

In order to imagine what problems arose here and how one could approach their solution, let us dwell on a simple example of handwritten text written in Morse code. In this case, there are always two characters: “dot” and “dash” (not counting all kinds of gaps of different lengths between characters and groups of characters). The main difficulty is that some “dots” in one “Morzis” may be longer than the non-octatory “dashes” in another. For this reason, it is impossible to first machine an exact representation: all signs whose length is less than a given number l must be considered dots, all other signs - dashes. It is possible, however, to make it so that, based on a sufficiently long text of one Morse code, the machine itself determines such a boundary number l. After all, every Morse has the lengths of all
