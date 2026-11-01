---
id: 1987-5-krutogin-kto-upravlyaet-gorodom-mk-bc0dfce9
issue: kvant_1987_5
year: 1987
number: "5"
title: Who runs the city of MK?
authors:
  - Крутогин Д. Г.
rubric: osnovnye-stati
page_first: 18
page_last: 23
page_labels: 16, 17, 18, 20, 21
tag: K8DF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 12a51bca77b1fcfea314ffc86177d2149c211c61e6c82889bfc9dcc004be9f60
prompt_sha256: draft-1
translated_from: content/ru/1987/05/articles/04_krutogin-kto-upravlyaet-gorodom-mk-bc0dfce9.md
source_content_sha256: 97238e5d2b73a5cd5a10d779d70ea23a4e7d6c0ada3e04fdbaf493aa7ef3c910
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

WHO RUNS MK CITY?

(Journey through a microcomputer)

Candidate of Technical Sciences D. G. KRUTOGIN

Today we have to visit the architectural center of our city and at the same time the main production area - in short, the microprocessor. It was no coincidence that we discovered this vision, it was no coincidence that we walked around and around. A microprocessor is as difficult to analyze as an architectural masterpiece. And it’s not so easy to talk about it. We could again draw a plan, list the details of the MP, their interaction in work, but we will do this later. And we will teach you by building in our imagination the simplest microprocessor (SMP) from the most necessary blocks. If it can “work” (in the same place, in the imagination), then, probably, it will not be difficult to complicate it a little in order to get closer to the real architecture and real functions of the MP.

16

⟦folio 17⟧

So where to start? The processor must perform all arithmetic and logical operations. Let us remind you that there are not so many operations: arithmetic - addition taking into account the sign (i.e., subtraction) and multiplication (division) using the c-division of a double number to the right - to the left by an integer number of digits; logical - “AND”, “OR”, “NOT”. These operations are performed in our PMP Arithmetic Logical Unit, abbreviated as ALU. This is already the architectural gem of the city of MK and computer technology in general.

The most important employee

An ALU is a multi-bit (8, 16, and sometimes more) set of adders that, depending on control pulses, can change from arithmetic to logical operations or vice versa. “Kvaant” spoke about the work of a single-valued adder last year (see May issue). And at figure 1 you can see a four-bit (very simple) ALU. Through the data bus wires, bit operands $A$ and $B$ are supplied to inputs $A_0$ - $A_3$ and $B_0$ - $B_3$, results are output from outputs $F_0$ - $F_3$, inputs $S_0$ - $S_3$ are used for control ALU, switch it to certain operations (addition, subtraction, negation, etc.).

Looking at figure 1, imagine a large labyrinth with straight paths. It has eight inputs and four outputs; but, unlike ordinary labyrinths, in this labyrinth a neko (“the name” of this neko is UFC, and we will get to know him a little later) continually moves the walls, changing the configuration of the passages. As a result, the ALU will perform different actions with the same operands for different control signals, and the output will have different responses.

The ALU works with enormous, fantastic speed; what it can do, it does in millionths of a second (and the fastest ALU devices are hundreds of times faster). This quality is very valuable, and we can say that everything else that is in the MK is arranged in such a way that the ALU, if possible, does not fail.

Where do operads come from? Typically from RAM or ROM areas. But, as a rule, you can call them from there only one by one, for example, first $A$, then $B$. This means that while the PMP is waiting for $B$ to appear, the operand $A$ must wait a little somewhere. The closest “receiver” is a special memory register called an accumulator. It has the same number of bits as there are in the ALU. The accumulator not only supplies one operand to the ALU, it also receives the result of the operation - the word $F$. Then the accumulator will transfer this word to RAM or some other memory register within the process, but first it is important to turn things around!

The next important point is management. We have already noted that the ALU needs to be controlled and its operating order set. This means that our PMP needs appropriate governing bodies. (Here's how to turn things around! Previously, we dismissed the fact that everything is controlled by the processor, but it turns out that someone controls it too.)

"Processor" for a process

Control and command generation device (let's call it UVK)

Fig. 1. Schematic representation of the communication of a four-bit ALU. C - sales indicator sdbila and change of ranks. M - arithmetic - logic switch.

⟦folio 18⟧

It occupies a micro area of ​​similar size in the PMP area. The task of this micropaon is to receive the next command from the program text and decipher it to the level of the simplest pulses supplied to the inputs $S_i$ and $M$ of the arithmetic-logical device.

Basically, the UFK micropaion is built up with logical devices, which are called decryptors. They actually fill the writing cards, the holes of which select several letters of the secret donation from the most random text. And the responder role is to perform different options for connecting the decoder elements to the bus carrying the command text. Although the building elements are typical - these are logical elements *) AND - NOT, OR - NOT, their bizarre architecture makes it possible to implement several dozen combinations that provide control of the PMP. UFC systems control not only the ALU, but also the battery and other areas of the microcontroller. One of the UVK quartols is specialized in servicing input and output systems; it also manages the buffers of the corresponding buses during periods of contact with external devices. Up to a hundred control channels come out of the UFK area.

The next question is where does the UFC receive the decryption command? Of course, from the memory (where the operads come from). But during decoding, formation of microcommands and their use, the command arriving from memory must be located next to the UVK (be at hand), that is, in a special memory register - the command register (PK). There are as many bits in the PK as there are in the ALU and the battery.

It is clear that the battery and PK are the closest, ultra-RAM memory of the processor.

It would be nice if the attentive reader would now draw a block diagram of the part of the PMP described above. Two rectangles, one another, need to be connected by a narrow corridor, in which there is an arrow in two directions - this is the ALU and the battery (A). Below there will be a slightly larger straight line - UVK, the arrows from it go to the ALU and battery. Place the PK square on the right, the arrows from it are directed to the UVK block. Now, above the battery, draw a small but important square - a buffer (B), and then connect the data bus to the buffer and register on the right (for this you will have to make a fork on it). Buffer B (we previously compared it with the traffic police post) can pass data from memory (RAM) in a process, in another state - on the contrary - from the process to RAM. But he also has a third state, when he generally avoids the exchange of data, as if “looking into it.” The buffer “gives” this state (of course, according to the UVK signal!) at the time when a command word arrives via the data bus. As a result, the command ends up in the command register, but not in the ALU. If we now remember that the command and “settled” were in RAM separately from the operads, and were called so as not to get into the arithmetic-logical device, it will become clear how the computer is divided into commands. We'll check that your figure is correct a little later, but now let's get back to the commands. Here’s the question: who calls the next team and when? This duty is performed by another memory register, which is called a programmable counter, or program counter (SC).

These counters are controlled by the same UFK unit. When you start using the program, the address of the first command in order is written to the counter. As soon as this command has entered PK and has begun to be decrypted in UFK, the counter receives an increment signal, for example by one, and thereby records the address of the next command (or the second part of the same command, if it is long).

The same procedure is repeated with the next command, and so on until the stop command. But sometimes the next command contains an instruction for the counter to move not to the next one, but to some other command that is far ahead (or, conversely, behind) the next one. Then it counts-

⟦folio 20⟧

Logical circuits of the deshfrator in the UVK and bus buffer circuits.

Internal communication buses between individual processor elements.

Of course, a real microprocessor is much more complex than our simplest one. It introduces several more important registrations for specialized purposes, provides the ability to restart the program and return to it, as well as different ways to access memory. The overall complexity of the microprocessor structure can be appreciated if we remember that behind each register, adder or deshfrator there are ten or even hundreds of transistors, and there are ten or hundreds of thousands of them in the entire microprocessor.

But let's look at the microprocessor not from an architectural point of view, but from a functional point of view. What does it do in a microcomputer, what does a processor do in large computers? What is a new processor for?

Robot lifter

In the January issue «Kvant» last year, in the article “Elementary Logical Operations,” an example of elevator control was considered: a multi-story building, one or more elevators, one call button on each floor. The elevators are controlled by the command apparatus. In response to the variety of possible task-situations, the device produces one of three solutions: up, down, stop (if there are two elevators, then there are 2 × 3 = 6 independent solutions). Solutions are prepared in advance and exist in the form of an electrical connection diagram for general switches or relays. These connections can be described by logical operations (see figure 4, a): if the “e10” button (floor) OR “e9” (etc.) is turned on AND (at the same time!) the “l12” button is turned on (an empty elevator is on the 12th floor) AND the “stop1” button is NOT turned on (overload!) AND the “stop2” button is NOT turned on (the doors are open!), then the solution to the problem is DOWN. Otherwise - STOP. When the elevator moves to the contacts of the installed switches, the connection diagram changes, and before the tenth floor, NOT “l10” is turned on, i.e. STOP (figure 4, b).

Thus, the command device remembers and compares the call commands, the current state operands, the prohibition commands (they are generally superior to all others!), and then issues a response command. Each command is easily represented: 1 - the button is pressed, 0 - the button is released. This is a double code instilled in us.

A processor (or microprocessor) is a multi-command device, compressed in size to a few square millimeters of a microcircuit. He has not three, but more than a hundred solutions, he compares a lot of data,

Fig. 3. Scheme of the simplest microprocessor. The pink block highlights the main part of the diagram with which we began “construction”.

⟦folio 21⟧

Fig. 4. Elevator control logic.

dozens of prohibitions. The processor sends its responses to hundreds and thousands of different addresses. In a word, it is much more powerful than a modest command apparatus in terms of speed and capabilities, but in terms of the meaning of its action and functions - it is also a command apparatus! Variants of solutions (microcommands) that the microprocessor uses are recorded in the permanent memory of the UVK block. Therefore, finishing the journey around the city, the Microcomputer, reduce the microprocessor with the administrative and cultural district, and the management and team formation device (UFK) to give the status of the city executive committee (operational current management of city life).

Instead of a conclusion

The tasks of the city council, i.e., determining common goals, prospects, the order of execution of work, and implementing the program that the MK users, that is, you and me. Consequently, with all the perfection of the design of computers and microcontrollers, they do not contain a creative principle; it is included in them by a person, included in the form of permanent or replaceable programs.

WHY did we not see in the city of MK from what excursionists are supposed to see? There is no monument to the founders and first builders of the city. There is no place for him in the extreme testiness and rationality of our city. But if there was one, then at its top there would be a place of honor for answers to trem scientists: Michael Faradenko - a physicist who was the first to note the special properties of semiconductors, Charles Babbage - the first “architect” and builder of computers, George Boole - a mathematician, inventor of logical algebra - the science on which computer circuitry is based. These three people may have known each other or lived in England at about the same time.

The second tier of the monument should include ten major scientists: from D. Mendeleev and N. Bohr, J. Frenkel and W. Schottky to the inventors of the transistor - J. Bardeen and W. Bratein.

The third tier of the monument is worthy of housing thousands of engineers from different countries, representatives of several generations of physicists, chemists, mathematicians, metallurgists, technologically, chim labor and talent created a micro-search and a beautiful city. Actually, it is the best monument to their inspired work.
