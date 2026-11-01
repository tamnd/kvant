---
id: 1980-5-pervin-saltovskiy-kak-rabotaet-protsessor-50b6574b
issue: kvant_1980_5
year: 1980
number: "5"
title: How the processor works
authors:
  - Первин Ю. А.
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 63
page_labels: 56-61
tag: QZG4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6774dd27b17ed35a4661958314924b0c1c68ff82ce61f79b6ef4a3e87cd317c1
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/22_pervin-saltovskiy-kak-rabotaet-protsessor-50b6574b.md
source_content_sha256: 80c0214044bd370f850d24b87624ef1b652843e9ec97835c76eb462be1ba493f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

How the processor works

Computer architecture

A modern electronic computer is a complex complex of devices and elements, admired for its technological perfection and variety of physical principles of operation. Let's look at the machine through the eyes of a programmer: let's get acquainted with its main devices, their purpose, the connections that exist between them, and the principles of operation of these devices.

The simplified block diagram (Fig. 1) shows the following devices that make up the computer:

— The Arithmetic Logic Unit (ALU) performs arithmetic and logical operations on the data coming from the Memory. ALUs included in modern computers can perform many or more different actions (operations). In addition to the usual arithmetic ones - add, subtract, multiply, divide - the set of operations that the ALU has contains operations that allow you to edit information. The main task of this device is to convert information received from Memory.

- Memory (P) (or storage device - see «Kvant», 1980, No. 4) stores data, as well as information that controls all work in the computer, i.e. the program.

— Input-output devices (IOU) are the organs of communication between a machine and a person. With the help of a computer, a person enters the program and data necessary for executing the program into a computer, and also receives the results in a form convenient for further work: tables, graphs, diagrams and drawings. The input devices are the eyes and ears of the machine, and the output devices are its tongue and hands.

— The control device (CU) coordinates the operation of the computer as a whole and leads “diplomats” in mutual communication between individual devices.

Arithmetic and logical operations are performed in ALUs at high speeds, estimated in modern computers from hundreds of thousands to tens of millions of operations per second. To ensure high speed of machine operation as a whole, processes associated with the transfer of information between devices - changing data, receiving a new task, recording the result - are fully automated; this is what the CU controls. The control device is a kind of director of the ensemble of devices that make up the computer. The “music score” for the director is a program previously recorded in memory. Each measure of the piece, played under the guidance of the UU, is a complete elementary action: adding two numbers, comparing two quantities, etc. It is the UU that “sets up”

⟦folio 57⟧

The ALU orders to perform a specific operation, “takes care” that the information necessary for this operation is retrieved from memory, and does not “forget” to write the result into memory at the end of the action or send it to the airborne controller.

In the family of devices that make up a computer, the most technically complex are the relative memory of the control unit and the ALU. The fact is that the control unit not only “sets up” the ALU to perform a certain operation, for example, comparing two values, but is also “interested” in the result; depending on the value of this result, a decision is made about the further execution of the program. The relationship between the ALU and the control unit is called a process.

The logical organization of a machine is called architecture. Presented at figure 1, the architecture is considered classical. It was proposed in 1947 by the American scientist Von Neumann and contains the main features of modern architectural solutions for computers.

What is control information?

To a first approximation, the operation of a computer can be represented as follows:

— control information is retrieved from memory. As a rule, this is the content of one of its cells - one machine word. This control word encodes comprehensive instructions about the actions of the machine’s devices for the next period of time - for one cycle of its operation;

— The control unit deciphers the information contained in the control word, and, depending on the meaning of this word, issues orders for specific actions to the computer device participating in the operation;

— after the devices perform the work assigned to them, they report this to the Controller; then either the next control words will be retrieved from memory, or two

Fig. 2. Approximate format of a three-address command.

More information flows into the computer will be suspended.

The control word is called a command. A sequence of commands represents a machine language program. Commands and data intended for processing, as well as the results obtained, are stored in memory.

Each memory cell, including the cell storing the command, has an address (the number of this cell). Any information is searched for by address in memory, just as a book is searched in a library by its index, and a coat left for storage in a wardrobe is searched by the issued number.

A team is most often composed of several components (Fig. 2).

The nature of the information management that the team supplies to the computer is being determined prematurely. In general, this is a small part of the command format, occupying 6-8 bits for many computer models. In addition to the operation, the command contains the following control information:

— the address part, including the data on which the operation must be performed, and the address of the result;

— the address of the next command is explicitly or implicitly specified, which will need to be retrieved from memory and accepted for use after executing the current (currently executing) command.

What does the machine consist of?

Various machine devices are combinations of a large number of elements - “bricks”. The variety of elements, however, is not so great. Therefore, for a more detailed acquaintance with the operation of computer devices, it is necessary to find out the reasons for the action of these elements. Examining the memory device («Kvant», 1980, No. 4), the reader,

⟦folio 58⟧

Apparently, he drew attention to the discrete nature of the information stored in the machine: ultimately, all properties are divided into two states, called 0 and 1. Different designs of elements can only give different technical implementations that guarantee recognition of two such states. For example, two voltage levels - "high" and "low" - can be recognized by electronic circuits so that "high" means one and "low" means zero.

One of the simplest elements designed to fill one bit of information is a trigger, which is very similar in principle to a general two-position switch, with the only difference being that it is controlled not manually, but by a single electrical signal arriving at its input: if the trigger is in the zero state, then it “remembers” this state until the next single signal arrives; if the trigger was in a single state, then a single signal received at its input “resets” it to a zero state, which is also stored for an indefinitely long time until the arrival of the next single signal.

The ability of a trigger to store information is widely used in various storage devices, the simplest of which is a resistor - a group of triggers combined for the operational storage of a fixed number of bits, in particular a machine word. The register is a convenient means for pre-storing information. With the help of resistors, information exchanges between computer devices, often operating at different speeds, are effectively coordinated.

In the process of executing commands, the control switches control signals and information flows. Switching is carried out using various electronic circuits. The simplest and most common of them are:

- coincidence circuit (“and”) - a signal corresponding to the value “1” will appear at the output of the “and” circuit only when the value of all input signals corresponds to the value “1” (Fig. 3a);

- assembly circuit (“or”) - this circuit is less “sensitive” to the characteristics of the input information: the value “1” appears at its output every time when at least one input the value “1” appears (Fig. 36);

— the inverter circuit (“not”) produces an output value opposite to the input. Received

⟦folio 59⟧

Fig. 4a. Selection of commands. Fig. 46. Decryption of the operation code. Fig. 4c. Transferring the 1st term to the ALU.

With the help of inverters, the “negative” image of information (Fig. 3c) is used, in particular, to perform the subtraction operation.

The elements “and”, “or”, “not” are used when creating functional blocks, which are components of a computer device: with the help of these elements it is possible to create devices with any predetermined properties. A characteristic feature of the menial work of functional blocks is their narrow specialization, ensuring that each block performs a strict set of responsibilities. The following functional blocks have found wide application in the creation of individual computer devices:

— adder — the heart of the ALU; the adder receives double representations of two numbers as inputs and produces a double representation of their sum as output;

- encoder - converts a signal at one of its inputs into a corresponding set of output signals (for example, into an operation code);

- decoder - performs the opposite function of the encoder, that is, for each input combination of signals it outputs a signal to only one output line; the decoder is used, for example,

in the control unit to decipher the command operation code;

— counter — counts the number of discrete signals that appear at its input; A counter, like a register, consists of a finite number of flip-flops.

The processor executes the command

The processes occurring in the machine when executing commands are illustrated in Figures 4a-4e. These are a kind of still images of an event, which consists of the execution of one command. Processes, as can be seen from the “chaas”, appear in each picture and occur over time. The high overall speed of computer operation required strict regulation of the time for each information exchange separately. The machine's metronome, its internal clocks, is the so-called clock particle generator.

Before starting work, the computer operator prepares starting information from the console - the address of the command, the performer in this program is the very first. The “start” order that the operator gives to the machine relates primarily to the control unit (Fig. 4a). Further events unfold as follows:

— first of all, the ad-

⟦folio 60⟧

res of the first executed command of the program; This determines the location in memory from which the command being processed can be retrieved;
— having received an order to start work, the control unit transfers the contents of the program counter to memory as the address of the information being sought;
- this transfer is accompanied by an order for memory to “issue the contents of the specified cell to the command register”;
- after that, a command is read from a memory cell with an address equal to the contents of the SC and placed in the command resistor (PK);
— The control unit, using a decoder, deciphers the command’s operation code and, setting up the ALU to perform the operation (in our example, “add two numbers,” begins working out the command algorithm (Fig. 46));
— the address of the first term (the first address in the address part of the command located in PK) is transferred to the memory; The control unit needs to output the contents of this address to the ALU; The transfer point in this transfer is the read information resistor (RSI) (Fig. 4v);
— after the ALU accepts the contents of the RSI as the first term, the control unit begins sampling the next term. To do this, the number of the cell storing the second term (the second address in the address part of the command from the RK) will be transferred to memory, and the contents of this cell will be transferred through the RSI to the ALU (Fig. 4g);
— having received both terms, the ALU, using an adder, performs an addition operation and transmits the result to the recorded information resistor (REI) (Fig. 4d);
— the final execution of the command is the recording of the contents of the RZI (result) at the result address (the third address in the address part of the command in the Republic of Kazakhstan) (Fig. 4e).

How is the order in which commands are executed determined?

The next command will be retrieved from memory automatically: the completion of the command is recorded by adding 1 to the contents of the program counter, so the next command to be executed will be the one stored in the adjacent, next cell. Two special commands can change this sequence: unconditional jump and conditional jump. Their main purpose is to change the contents of the program counter. An unconditional jump command contains in its address part information about the address of the next command. This

⟦folio 61⟧

information replaces (displaces) the contents of the command counter, regardless of any situation that might have occurred during the execution of the previous command. For example, a result condition command selects one or another command as the next one: the address of possible next commands is present (explicitly or implicitly) in the address portion of the condition command.

Why are interruptions needed during program execution?

In addition to the deliberate way of changing the sequence of commands, which the programs provide with unconditional and conditional jump commands, there are “hardware” (internal machine) ways of changing the usual sequence, which allow, according to some important and extraordinary principles, to interrupt the execution of the program and begin the execution of another program. When a principle that causes an interrupt appears, the contents of the program counter first change: it receives the interrupt address. The fact is that usually each class is assigned its own fixed address; it is usually "found" using an encoder. The fixed interrupt addresses contain instructions for jumping to a subroutine (processing the corresponding interrupt). These commands are “close relatives” of the already well-known unconditional transfer command. The remarkable combination of software and hardware designed to quickly respond to emergency events is called an interrupt system. The actions of this union are aimed at “photographing” the events occurring in the computer at the moment the interruption occurs. "Photography" helps restore the machine to sequence mode after the interruption principle has been satisfied or eliminated. Those-

The phone call interrupts the reading of the book, and after talking with the recipient, you return to the book. Specifically for the book, not for the samovar. Moreover, you continue reading exactly from the page on which reading was interrupted. The computer “recognizes” the reason for the interruption in the same way as you recognize the voice of one of your friends.

There can be many reasons for an interruption. Here are some of them:
— the machine constantly monitors the accuracy of transmitted or received information: an error is detected;
— processing failure occurred;
- there is an error in the program.
The ability to interrupt while using a program allows you to control processes using a computer, the occurrence of which is difficult to predict.

Is it that simple?

Talking about the events that occur in the process during the execution of the program, we agreed with the help of a computer processes that allow us to manage control information - command (Fig. 2) - state from the operation code and three addresses in the address part. It is not difficult to understand that this type of command has an impact on the entire process of computer operation. Machines with this command format are called "three-address". However, three-address machines are not the only class of computers. In the next issues of Kvast we will introduce you to computers of different addresses - one- and two-address, half-address and even “addressless” machines. On these machines, executing a command like addition is, of course, more difficult.
