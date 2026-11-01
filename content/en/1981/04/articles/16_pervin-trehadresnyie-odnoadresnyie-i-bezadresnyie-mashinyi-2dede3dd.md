---
id: 1981-4-pervin-trehadresnyie-odnoadresnyie-i-bezadresnyie-mashinyi-2dede3dd
issue: kvant_1981_4
year: 1981
number: "4"
title: Three-address, one-address and... addressless machines
authors:
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 56
page_labels: 51-54
tag: PAYE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2f893ad5f64787a9119f2ef981515623d86f153708ac6ffc26e9ad9e09d97795
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/16_pervin-trehadresnyie-odnoadresnyie-i-bezadresnyie-mashinyi-2dede3dd.md
source_content_sha256: 53f66de7340630ea777c822cefd5fa7ca89f5339ad4d46f2eedd2227e26646ba
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

Three-address, uni-address and... addressless machines

When readers «Kvant» became acquainted with the operation of the control device*) of a computer, computers with a command format such as that on figure 1 were considered. The address part of the command on this figure is divided into three fields with the addresses of the operands (values ​​involved in the operation).

Operation code 1st address field 2nd address field 3rd address field

Fig. 1.

The first address field contains the address of the first operad of the operation being performed, and the second contains the address of the second operad. The third address field is the result address. All three addresses are the same length. This command format is not necessary for the three-address BESM-2 machine to this day. For example, the command 01 0257 1023 0016 in BESM-2 means adding (operation code - 01) the value stored in the machine word at address 0257 with the value located in the machine word at address 1023, and placing the result in the machine word with address 0016.

When the address of a machine word located in memory is written in the address field of a command (as in the case of BESM-2), the length of the address field is determined by the amount of RAM. For example, in order for 4K = 2¹² = 4096*) machine words from RAM to have different addresses, the length of one address must be at least 12 double digits.

The unicast machine command (Fig. 2) has a different form.

Transaction code Address field

Fig. 2.

Only one address can be specified in the address field of such a command. How can you set the address of the second operad in this case? Where should I send the result? To answer these questions, you need to know that in a single-address machine there is a special register equal in length to a machine word. This register is called an adder. He takes part in performing practical tasks of the command machine. For example, in the codes of another “grandfather” of advanced computers - the single-address machine "Ural-2" - the addition of two numbers stored in memory at addresses 0257 and 1023 and sending the result to address 0016 is performed with the following commands:

02 0257 (sending a number from a machine word with address 0257 to the adder)
01 1023 (adds the contents of the adder with the number stored in the machine word at address 1023; the result is obtained in the adder)
16 0016 (sending a number from the adder in a machine word to address 0016)

One should not think that the program of the same task in a one-address machine is always longer than in a three-address machine. In the majority

*) Here K does not mean a key equal to 1024 bytes, but simply the number 1024 = 2¹⁰.

⟦folio 52⟧

In practical cases (especially when the result of an operation is directly used in the next operation), the program's commitment is small.

Here's an example. In the codes of a three-address machine program, the computational expression $a^2+a-1$ is written as follows:
03 A A B (multiply $a \cdot a$)
01 A B B (addition $a^2+a$)
02 V C V (subtract $(a^2+a)-1$)

where A is the address of the number $a$, the unit is stored at address C, B is the address of the machine word used as an intermediate word. In a single-address machine, the same program looks like this:
02 A (sending the number $a$ to the adder)
06 A (multiply $a \cdot a$; result in adder)
01 A (addition $a^2+a$; result in adder)
03 C (subtraction $a^2+a-1$; result in the adder).

So, the program has increased by only one instruction (did you notice that the last program did not contain intermediate machine words?). But the hardware savings in a single-address machine are significant: after all, the address part of each command becomes shorter.

It is unlikely that after this the reader will find a two-address car surprising (such were the Minsk cars). But it turns out that the car may seem shorter at the first input, but the second one is shorter. But imagine that a computer has two types of RAM: one is a regular, large one, in which a “long” address is needed to indicate the location of a machine word; the other is ultra-fast, with a small number of registers, for an unambiguous indication of which a very “short” address is enough. This is what the computer receives.

However, in later machines the registers used to determine the operand address found other uses. In large machines, the address involved in the command directly at the time of execution (the so-called “executive address” does not coincide with the value of the address field, but is calculated as the value of some function. Such a function most often looks like the sum of the value written in the address field (the so-called scenation) and the contents of one register (base) specified in the command, or two registers (base and index). For example, in the BESM-6 machine (if we digress from some unimportant details) the format of most commands is as shown in figure 3.

Fig. 3.

The numbers in the command fields at figure 3 indicate the length of the corresponding field, measured in number of double digits. The BESM-6 RAM contains 32K=2$^{15}$ machine words, and the largest number written in the address field is, in any case, less than 2$^{13}$. And here one of the sixteen $(2^4=16)$ base registers comes to the rescue, exactly the one whose number (address) is indicated in the base register field. The execution address of the commands is the sum of the fifteen-row value stored in the specified base register and the twelve-row offset value. For example, the command

03 004 0231
provided that the third register contains the number 12000, it will add (004 is the addition operation code) the contents of the adder with the number stored at 12000+231=12231 and send the result to the adder. Here 3 is the address (number) of the base register, 12000 is the base, 231 is the offset, 12231 is the executive address. Thus, the base means the starting address of some RAM, and the address of the word needed in this area is obtained by adding an offset to the base. This addressing method is called relative.

It is convenient because it allows you to move programs or

⟦folio 53⟧

parts of the program throughout RAM, so that programs are freed from the need to monitor program changes.

Even more advanced addressing capabilities were obtained in machines of the EC series of computers. The memory of these machines is made up of a community of RAM and a relatively small set (16) of general-purpose registers, and two address fields are most often written in the address part of the command. Therefore, these machines have not one, but three command formats. The first of them - “resistor - resistor” (Fig. 4) - describes

| Operation code | P1 | P2 |
| :--- | :--- | :--- |

Fig. 4.

instructions that operate on numbers stored in registers P1 and P2 and write the result to address P1. The second format is “resistor - memory” (Fig. 5). Here Address 2-20 operad

Fig. 5.

the address of one of the operands (the second) is specified in memory. The executive address is obtained by adding the CM2 mixture with the values ​​stored in the base register B2 and the index register I2. Finally, in memory-to-memory instructions (Fig. 6), both operands are located in main memory. For each of them, the executive address is obtained by adding the mixture with the value of the base register. In addition (this is a feature of the EC series machines), this format specifies the lengths D1 and D2 of the operand fields, which makes it possible to work not only with machine words of a single size, but also with data of a derived length.

Let's return once again to the addressing system, illustrated by drawings. The three-word machine (Fig. 1) is characterized by the fact that all machine words in its memory are coincidentally equivalent in terms of organization and access time. Machines with this property are called linear or, more precisely, machines with a linear memory structure. Already in the general unicast machine (Fig.2), linearity is slightly broken: there is one special register - the adder - which can store information like other machine words of memory, but is very different from them. In particular, this is the only register where the result of an operation can be sent without prior transfers. On machines with base registers (Fig.3), linearity is broken not only by the presence of base and index in the instruction format, but also by the ability to work with words of different lengths. At the same time, all these machines, in principle, retain the linear structure of the main part of the RAM.

But in machines with a stacked memory structure, the principle of linearity has already been dealt a serious blow.

The easiest way to understand what a stack is is to imagine a stack of books on your desk.

Address 1-20 operad Address 2-20 operad

Length 1-20 operad
Length 2-20 operad

⟦folio 54⟧

Fig. 7.

(in English “stack” is the same as “stack”). You can add books to this pile only by placing the last book you are interested in at the very top of the pile. This same book, placed last, also turns out to be the very first available book. Next, you need some book in the middle of the stack, then the first book to take during this search will be the last book placed on top of the stack. A stack is a group of machine words in which only one word is available at any time, namely the one that was last written. This available word on the stack is called the top of the stack, and the rest of the stack is called its body. Adding a word to the stack means creating a new top; the previous top becomes the second element of the stack, part of the body. Popping a word from the stack makes the top of the stack the element that was directly behind the top of the stack before the operation was performed.

If the computer memory is organized in the form of a stack, then for performing many operations it is possible not to specify the address of the operads if they are previously placed at the top of the stack or immediately after it. Thus, the SL instruction, specified only by the operation code (and nothing more!), adds two numbers, one of which is at the top of the stack, and the other is always immediately behind it, and places the result at the top of the stack. As you can see, there is no address part at all in the command. Machines with a stack memory structure are therefore called part without an address and. This term does not mean, of course, that word machines in stack memory do not have addresses. Addresses exist, but after the operads are pushed on the stack, there is no need to provide these addresses in the address portion of most machine instructions.

This is what, for example, a program looks like that calculates the already completed expression $a^2 + a - 1$ in the Elbrus machine, the fastest fourth-generation Soviet stack machine (A is information about the address of the value $a$):

ZGTs1 (loading integer 1 to the top of the stack - Fig. 7, $a$)

SCHEEL A (placing the value located at address A at the top of the stack; the previous top is immersed in the body of the stack - Fig. 7, $b$)

DIVID ("division" of the top: an instance of the value stored at the top of the stack is now written into the word immediately following the top; the rest of the stack has dropped even deeper - Fig. 7, $e$).

DIV (another “division”: the fact is that in further operations three copies of the value $a$ - Fig. 7, $e$) will be required)

UMN (variable number located in the top two words of the stack; the result $a^2$ remains at the top of the stack, and used operads are removed from the stack - Fig. 7, $d$)

SL (addition of numbers located in the top two words of the stack; the result $a^2 + a$ remains at the top of the stack - Fig. 7, $e$)

CALC (subtraction: from the top of the stack - the sum $a^2 + a$ - the 1 located in the stack immediately below the top is subtracted; the result remains at the top of the stack - Fig. 7, $ж$)

The commands of this program are written in a somewhat simplified form and do not give a complete picture of the very rich and flexible Elbrus command system. A separate article will be devoted to the story about this car in one of the following issues «Kvant».
