---
id: 1987-2-krutogin-puteshestvie-po-mikrokompyuteru-fe4e28ff
issue: kvant_1987_2
year: 1987
number: "2"
title: Journey through the microcomputer
authors:
  - Крутогин Д. Г.
rubric: raznoe
page_first: 21
page_last: 23
page_labels: 19-21
tag: EGC7
lang: en
source: kvant_digital
extraction: vision
content_sha256: a89181ed69123c0794f516c0f9affb93c4c94d2084434c0f7f2f8933d61734f1
prompt_sha256: draft-1
translated_from: content/ru/1987/02/articles/05_krutogin-puteshestvie-po-mikrokompyuteru-fe4e28ff.md
source_content_sha256: 4ad47848f7b6e51777a39825ad1ae3851b34a60658fcbf8fe2ab211b666fcdc4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

JOURNEY
BY MICROCOMPUTER

Captain of Technical Sciences D. G. KRUTOGIN

A year ago, we examined the “construction process” of a large interral scheme (BIS), comparing it with the construction of a city (“Quait”, 1986, No. 2). Then we were mainly interested in technological construction

affairs, and now we invite you to get acquainted with the city itself, its structure, read about individual districts and quarters, explore the architectural sights...

Reflections at the panorama

To get acquainted, let's choose an ultra-large interconnected circuit (VLSI) - for example, a single-chip microeBM microcircuit. Such a circuit contains 10⁵—10⁶ individual transistors. What does a microeBM, or, as it is often called, a microcomputer (MC) do? Firstly, count, i.e. perform

19

⟦folio 20⟧

perform mathematical operations at a fairly high speed - up to a million simple operations per second. We will call simple those few operations that a computer can perform “from birth”; It's basically addition (subtraction) and comparison. To perform complex actions, you must first teach the machine to “convert” these actions into a sequence of simple operations. Secondly, perform logical operations with the same speed. Without delving into the intricacies of logical operations, let's consider a suitable example: you need to create an alphabetical list of a given set of one million names. This is, in general, a simple job that does not require calculations - you need to compare surnames by the first, then second, then third, etc. letters, and based on the comparison results, put the surnames in the list under the corresponding numbers. For a person, this work is tiring, boring, and very long. A computer, including a microcomputer, will do this work quite quickly. Thirdly, a microcomputer can control machines, production units, and processes. This ability to combine the first two, or very simply, the control process can be represented as the calculation of several acceptable options for action, comparison of results and selection of the optimal solution.

It is clear that the most beautiful VLSI is “dead”, useless if it is deprived of a power supply system, means of inputting information (for example, a keyboard) and displaying results (for example, a screen or a printing device). The control computer also needs a communication system with the operating mechanisms. (So, the human brain, our multi-purpose personal computer, is powerless without two-way communication with the eyes, ears, body, hands.)

So, let's construct: VLSI is a powerful computer, its most complex part. It is the VLSI microcomputer that will be the goal of our journey, and, to simplify somewhat, it is the VLSI that we will call the city of MK.

Look at the photo posted on this page (it was taken with a magnification of 1.5): several ten-pins come out of the VLSI package. These are the roads connecting the city of MK with the “peripheries” - this is the somewhat disparaging name for the keyboard, displays, digitizing device, etc., and the roads along which power is supplied to the city - constant voltage (most often it is 5 V). In the case of working with tasks of great complexity or large volume (for example, the same list of a million names), archival, or external, memory is called upon to help; For communication with external storage devices (ESD), output roads are also provided.

Recall that an ultra-large scale integrated circuit is very small. The silicon crystal - the base of the VLSI - has a size of about 5x5 mm, and the VLSI itself in the case and with the leads is a box no larger than 40x25 mm, and it weighs 15-20 g. Therefore, for the convenience of traveling around the city of MK, we suggest you mentally shrink a million times. (In fairy tale literature, this example was used more than once, although the similarity coefficient was lower.) With such a decrease, when our height became 1.5-1.8 microns, a tour of the VLSI MK is the same as, on our ordinary scale, getting to know a city with an area of ​​​​about 30 square kilometers.

Obviously, if there is such an opportunity, cities are left from an elevated point (from the Ostankino cart, from St. Isaac's Cathedral, etc.). We will stop at the edge of the VLSI case at an altitude of about 1000 meters (taking into account the scale!) above the city of MK and start from here.

Down in the valley is our city. It is built on the shore of the Sea of ​​Solid State Physics, near the Bay of Semi-Conductors, and, without a doubt, it is one of the largest settlements on the coast.

⟦folio 21⟧

less often *). The uniqueness of our city, just like, for example, the cities of Sochi or Jurmala, is that it was built to receive and serve a large number of tourists. The permanent population of the city does only this. As often happens, in such a city there are much fewer permanent residents than guests. The city of MK is a new building; similar large ensemble schemes have been created over the past five years. For the first time, a large city built on one site collided. Previously, the task of tourist services was solved by a whole complex of small villages, sometimes located hundreds of kilometers from each other (do not forget to multiply by 10⁻⁶!). Can you imagine how many moves there were?

A word about words

Now we should clarify what kind of tourists we are talking about. Tourists in MK are segments (elements) of information for which the name “machine word” is well suited. These are in no way those spontaneous crowds of individual “savages” who flock to seaside resort towns in the summer. Our tourists are particles of organizational information flow called a programmable computer. The loss of any word threatens to destroy the meaning of the entire program, but there should not be any extra words. (In this respect, a good program is like good poetry.)

Well, who are the permanent residents of the city? These are also machine words, “prescribed”, or recorded, in the MK itself. They are necessary in order to pass the program handling.

Machine words, like general words, carry some specific information. For ourselves, we can divide machine words into two groups: command words (what to do) and data words (which are numbers or logical quantities, what the commands operate on; they are also called operands, after being created with commands). But this is for myself,

*) You have walked along the shores of Semiconductor Bay if you have read the book “Introduction to Semiconductors” by M.E. Levinshtein and G.S. Simin, published in Viblotechek «Kvant» (issue 33, p. 238).

and for MK electronic circuits, any machine word is just a sequence of ones and zeros, or rather, high (usually more than 2.5 V) and low (less than 0.5 V) voltages at the inputs of transistor elements. Thus, machine words are a series of electrical impulses running along the roads and neighborhoods of MK.

The task of each individual pulse is to turn on one or another transistor in the logical or storage element of the computer. In turn, each such inclusion leads to the movement of charge packets—electrons and holes—through the MC crystal. Thus, the information in the MK takes on the physical form of packets of charged particles, which purposefully move along the microcircuit, until, finally, the appearance of directional pulses at the output contacts of the MK notifies the completion of the information processing process and the receipt of the result.

And a little more about words. We usually have almost no difficulty in choosing words to express our thoughts. All computers, including our MK, have a strict order - you can use words of one specific length: for example, from 8 or 16 letters, moreover, the letters are 0 or 1 (such letters are called bits). For comparison, we note that more computers “speak” in words of 64 and 128 bits, and the best microcomputers are still only 32-bit. Of course, words of short words (8- or 16-bit) are less expressive, but much more complete. A “pocket” computer also requires a pocket dictionary!

There are inevitable difficulties in human-machine communication. Composing a program in machine language is a difficult task and requires a certain skill. It is proudly more convenient for us to communicate with a machine in a language that is logical block to human (say, Russian or English). There are several dozen such intermediary languages ​​for the purpose of creation: these are Fortran, Algol, Colol, etc. Well, where several languages ​​are used, you cannot do without a translator... But we will continue the conversation about translators and the translation agency that exists in our city in the next issue.
