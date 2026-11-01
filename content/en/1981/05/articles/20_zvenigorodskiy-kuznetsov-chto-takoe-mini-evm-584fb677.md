---
id: 1981-5-zvenigorodskiy-kuznetsov-chto-takoe-mini-evm-584fb677
issue: kvant_1981_5
year: 1981
number: "5"
title: What is a minicomputer?
authors:
  - Звенигородский Г. А.
  - Кузнецов Е. А.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 57
page_labels: 53-55
tag: CDC2
lang: en
source: kvant_digital
extraction: vision
content_sha256: e8ddfca7e1ef85aa6d88678fd90e27a4e08b738cdf3f307e07ab205caecba243
prompt_sha256: draft-1
translated_from: content/ru/1981/05/articles/20_zvenigorodskiy-kuznetsov-chto-takoe-mini-evm-584fb677.md
source_content_sha256: 9ff73d19c21a1b90d717634b85c79f33ce9fa997ad313ace7779a479c7bf505a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

What is a minicomputer?

Not so long ago, just 15-20 years ago, a large number of specialists in the field of computer technology believed that the main path of computer development was the creation of supermachines with enormous memory capacity and capable of performing hundreds of millions and even billions of operations per second. At the turn of the sixties, it seemed to many that after one or two decades all the country’s computing needs would be satisfied by several such giants.

The reality turned out to be completely false. Of course, large and ultra-large machines continue to be created and operate successfully in many industries. But along with them (and in some cases, displacing them), computers—minicomputers—have begun to rapidly develop in recent decades.

Not miniator, but minimal Judging by the name, you might think that minicomputers are small, miniator computers. On the one hand, of course, almost all modern mini-computers *) are very modest in size and occupy one or two small cabinets, and some of them fit in a desk drawer. On the other hand, in our age of microelectronics, even the so-called “mainstream computers” do not have much larger gabenty. Then, maybe mini-machines are two computers with low capabilities? Cheap is true, but as for small capabilities, it depends on how you look: in terms of RAM capacity and speed, “mini” are practically not inferior to their “colleagues” of medium power, and in terms of the ability to work with external devices, they are far superior to them.

So what is the peculiarity of mini-cars, why are they placed in a special class?

*) A mini-computer (mini-computer) - a machine capable of using a wide variety of programs - should not be confused with a microcalculator - a pocket or desktop device designed for numerical calculations («Kvant», 1978, No. 4, p. 23).

⟦folio 54⟧

According to N.P. Brusentsov, author of the book “Mini-computers” (M., “Nauka”, 1979), the scribbler “MINI” in the designation of this class of computers refers not to miniatoriums, but to miniature ones. The developers of these machines excluded from their architecture all elements intended to perform calculations for purposes and not necessary for other forms of computer use. These elements include, first of all, the arithmetic unit, which allows you to quickly and accurately perform addition, subtraction, multiplication and division of rational numbers. The large length of the machine word in machines of medium and high power (32, 36, 45 and even 48 double digits) is also associated with providing high power for representing such numbers. To represent other types of data, such a long word is not at all necessary: ​​for any standard symbol, for example, one byte is enough *), and integers found in large steratic problems are carried out in two bytes. Most mini-machines accept words of two bytes (16 bits), and sometimes even less.

Reducing the length of words and eliminating special arithmetic equipment makes it possible to make mini-machines simple in design, and therefore cheaper and more reliable, while maintaining high speed and sufficient memory capacity.

But how do they think?

The reader probably has questions: was the mini-computer really not able to perform accurate calculations with rational numbers? And if they are skilled, how can they do it without arithmetic equipment? How to organize the storage of numbers with high accuracy in a short machine word?

The answer is very simple: if in some task you need to work with such a number, then they are written not in one word, but in several consecutive machine words, and operations on them are performed using procedural machine instructions. Of course, we make such calculations. Computers do not come around very often (this was already discussed in one of the first articles in our section), so “on average” the speed of mini-machines almost does not decrease.

Hippopotamus in a matchbox

Reducing the length of a machine word poses a problem for minicomputer development that, at first glance, may seem insoluble. This is an addressing problem: how to ensure that a key word of memory can be processed if the length of the command is only 2 bytes? In middle-class machines with a small number of words and a large length of each word, the problem also did not arise.

For example, in one of the most common modern computers in the cala of the sixties - the M-20 machine - there were only 4096 45-bit words. With these parameters, for the address*) of any word, two bits are enough (check this!). Therefore, each instruction on this machine specifies the address of three words, six bits are allocated to write the opcode, allowing 64 different instructions to be encoded, and there is still room left!

In mini-machines, it cannot be accommodated from three addresses: there is not enough space even for one address. Indeed, if the answer for the operation code is only 4 bits (and this is only 16 different commands!), then 12 bits remain for the address, that is, the address of the same 4096 words is removed. But the memory capacity of modern mini-machines is 30 times larger (see table on p. 55), and 16 commands are not enough to work with. If you write a command not in one, but in two or three consecutive words,

*) We remind you that a byte is 8 bits, that is, 8 double digits.

*) See article by Yu. Pervin in the previous issue.

⟦folio 55⟧

va, then it will perform very slowly and the quick solution will be sharply reduced.

Sophisticated computer developers, aimed at solving this problem, are trying to push the behemoth into a matchbox: they are trying to “shove” a huge word address of 256-kilobyte memory into those few bits that remain after placing the operation code. We will point out just a few methods:

1. Addressless commands are used to work with special memory cells - registrations, which are processed very quickly. The CM-1 and CM-2 cars have two such registrations each, the CM-3 and CM-4 have seven.

2. There are several command formats: with a short operation code and a long address part (loading registration, transfer of control) and with a long code, but with a short address. In the latter case, a relative address is usually indicated, that is, a number that must be added to the address of the currently executing command in order to obtain the address of the desired word.

3. Indirect addressing is required: the required address is written in a separate word (then it can occupy all 16 bits), and the address of this word is indicated in the command (for example, using relative addressing).

However, none of these methods allows one program to work with memory exceeding 64 K. Large memory is usually used to work in multi-volume mode: each program is allocated a certain part of memory - a segment (no more than 64 K), and inside this program it is enough to indicate the word address relative to the beginning of the segment. Where are minicomputers used? The answer to this question is not so simple. Please, it would be easier to list those industries where mini-computers are not yet used. Here are just a few examples that will help to some extent imagine the variety of forms of use of these machines:

- management of nuclear and hydroelectric power plants;
- dispatch control of the country's energy systems;
- blast furnace control;
- management of technological processes in non-ferrous metallurgy, mining, cement, pulp and paper, light industry;
- reservation of seats and sale of tickets on the country's airlines (Sirena system);
- management of city bus traffic (in Omsk, Almaty, Voronshilograd);
- metro management (in Leningrad, Kharkov);
- oil pipeline management (for example, the Druzhba oil pipeline);
- in the information and computing centers of the automated control system "Olympida-80".

Our technical guide

SM - Minicomputer system of socialist countries

Indicator
Model
Unit
SM-1
SM-2
SM-3
SM-4

Performance
Directly addressable memory
Word length
Minimum amount of RAM
Maximum amount of RAM
Volume velocity with I/O devices

Thousand ops/sec
K(=1024)
words
bit
400
500
200
700
32
32
32
16
16
16
16
8
64
32
32,64
K bytes
K bytes
64
256
64
248
K words/sec
250
700
800
800

Models CM-1, 2 differences from model CM-3, 4. There are differences in the architecture of machines - in the command system, in addressing methods, in programming systems, in the organization and structure of the input-output system. This means that programs written for computers CM-1, 2 are not suitable for computers CM-3, 4, and vice versa, that is, these computer models are incompatible.
