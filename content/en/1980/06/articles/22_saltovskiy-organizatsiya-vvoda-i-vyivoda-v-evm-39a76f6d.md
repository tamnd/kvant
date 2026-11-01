---
id: 1980-6-saltovskiy-organizatsiya-vvoda-i-vyivoda-v-evm-39a76f6d
issue: kvant_1980_6
year: 1980
number: "6"
title: Organization of input and output in a computer
authors:
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 57
page_labels: 48-55
tag: S311
lang: en
source: kvant_digital
extraction: vision
content_sha256: 44f3908fcd7014c5346019f5e3a68b4b44da3cef0b79617aba2f5547e18108b1
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/22_saltovskiy-organizatsiya-vvoda-i-vyivoda-v-evm-39a76f6d.md
source_content_sha256: 0a7a25585594f1bb0a4b57d764b053b9cf158a2a95f4f1cc436b19381b12380e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

A. Saltovsky

Organization of input and output in a computer

This article continues the serial publication about the structure of a computer (“Computer Memory” in “Kvant No. 4” and “How the Processor Works” in “Kvant No. 5”).

Batch and dialog modes
The speed of modern computer processors reaches hundreds of thousands and millions of operations per second. With the help of various technical solutions, information can be exchanged between the processor and memory at the same pace.

The situation is more complicated with the delivery of information to the computer and with the output of calculation results from the machine. These very different functions are performed by input/output devices (I/O).

Direct communication between a person and a computer in the process of so-called “runic” input of programs and data from the console, when each individual machine word is entered into a person’s machine by an operator word, is labor-intensive even with small programs. In this mode of operation there can be no talk of efficient use of computers. The contradiction between the high speed of the processor and memory, on the one hand, and human imperfection, on the other, is resolved in the following two main ways.

In the first method, information intended for input into a computer is prepared in advance on some intermediate information medium, for example, punched cards, punched paper tapes or magnetic tapes. Devices that help perform the preparatory work prior to entering the program and data into the computer are called preparation devices, adding the name of the information -

Photos by V. Polyakov and I. Fedorenko

⟦folio 49⟧

digital media - on punched cards, on punched tape or on magnetic tape (photo 1). The preparation of information on intermediate media can be done without unnecessary haste, since data preparation devices operate independently of the computer and there is no need for compilation at speed with the machine. At the same time, a prepared program (punched on cards or punched tape, or recorded on magnetic tape) can be stored in a computer at a very high speed thanks to a special input reader: for each type of media there is its own specific input device. Compared to “manual” input of information from the computer control panel, the method of preliminary preparation of information allows you to reduce the process of expensive high-speed computer equipment. This mode of entering information into the machine is called batch.

The second method of information input/output is relatively new: its existence is due to the emergence of powerful computers of the latest generations - machines that are faster and have a larger amount of RAM than the machines of the 50s and early 60s. Outwardly, this method differs little from the “manual” input that existed at the dawn of the advent of computers: the means of communication between a person and a machine is the computer control panel, as well as remote consoles connected to the computer - terminals. True, the remote control has been somewhat improved: machine messages are displayed on the television screen in the form of easy-to-read texts. The “responding” part of modern remote controls greatly fills the keyboard of a luxury machine. A person who has had a little “talk” with a machine using such a remote control or terminal very quickly gets used to this form of communication with a computer. Such a remote control terminal can be removed from the car over a long distance. The most common terminals now are remote controls with a television screen and a keyboard - displays (photo 2). Electric typewriters and televisions connected to a computer can also play the same role.

The most important, perhaps, is the fact that in modern computing systems, together with a single remote control (as in machines of the first generations), the number of terminals has grown to several dozen. At the same time, for each of those working at the terminals, the user creates the illusion of single work with the computer: the information that each of the programs requests is immediately displayed on the screen, and the information that the program enters into the computer is immediately placed in the right place in memory. This mode of communication with the machine is called interactive.

Quantum of time
for a “conversation” with a computer

The possibility of rapid interactive dialogue between a person and a computer is based on the fact that the practical “instantaneous” (from the human point of view) reaction of the machine actually occurs over relatively large intervals.

⟦folio 50⟧

time shafts (from the point of view of high-speed computers): 40–100 milliseconds ((40–100) · 10⁻³ s). If a computer is capable, for example, of performing 10⁶ operations per second, then for each one immediately and “immediately” the computer can perform from 40 to 100 thousand operations. If each of the users - programmers - is allocated, for example, a portion of time of 5 milliseconds, then the computer can “advance” the course of the dialogue with each of them by 5000 commands during this time. That is why every user is sure that he is the only one working with the computer. True, part of the computer’s operating time is “taken away” by maintenance and management programs - the operating system. If in our example we assume that the human “immediately” is 100 milliseconds, then approximately the use of this time - 50 milliseconds - will be spent on the operation of the operating system program. Then, based on the calculation that each user is allocated 5 milliseconds of direct access time to work with the computer, we can say that the computer will be able to “simultaneously,” maintaining the illusion of instant responses, communicate with ten programmers. The operating system described here is purely illustrative. It is only important to note that in it computer time is distributed among users in a strictly regulated manner. In this, the operating system is assisted by the machine's electronic clock (the so-called “timer”) and the interrupt system (see “How the Processor Works,” «Kvant», No. 5). Such systems are called time sharing systems.

Operations of elementary exchange of airwaves - Memory

Airborne devices help organize communication between the computer and the outside world. The help lies in the fact that the UVV ensures the transformation of information received from the outside into a form convenient for processing in a computer. UVV also performs the reverse transformation: the solutions to problems obtained by the machine are output from the machine to the printing device. Its common name is

Photo 2.

tion - ATsPU, alphanumeric printing device (photo 3). Modern computers, among their output means, may also have more “exotic” devices - a plotter that depicts figure on paper, stored in encoded form in the computer’s memory; photoguide - a device that uses a light beam to build an image (slide) on photographic film; a film builder that provides output of a series of frames drawn on film, that is, cartoons, etc.

The operation of the airborne device is controlled by input/output commands. They form part of the machine's command system. An I/O command typically contains the following information:

Photo 3.

⟦folio 51⟧

Fig. 1.

— type (usually, number) of the airborne device with which the programmer plans to work;
- nature of work - air-blasts, as a rule, can operate in different modes;
- the amount of information that needs to be transmitted in one direction or another.

In addition, the input/output command contains control information about at which address (at which addresses) in memory there is information intended for output from the computer, or the address (addresses) at which it is necessary to place information coming to the computer from the input device.

Typically, a programmer’s communication with a computer begins and ends with input/output commands. At the very beginning, programs and data are transferred into memory, pre-prepared, for example, on peripheral narfocards. At the end of the communication session, the result is output, for example, to the ADPA. From this simplified diagram it can be seen that while the input/output command is being processed, the control device (CU) connects the memory via an information path to the selected I/O device (Fig. 1).

The information path is the operational short-term storage of information transmitted from device to devices. However, one of its characteristics is width: the amount of simultaneous information transmitted. Since the width of the information path from airborne to airborne

often less than a machine word, the information being prepared for transmission began to be pre-accumulated in special buffer resistors (Fig. 2). For example, modern computers of the EC series allow the exchange of information with memory in double words (64 bits), and the main exchange portion in airborne transmissions - memory is a byte (8 bits). Eight bytes are matched on a 64-bit buffer register, and after the buffer register is full, memory connections are requested.

In early models of cars, at the moment of communication, I restore the memory of the arithmetic logical unit (ALU). At best, the ALU is engaged in counting the amount of transmitted information in bytes or machine words. With the advent of high-speed memory, pauses during which information is assembled or disassembled become available for information exchange between the P and the ALU. This is a significant increase in the efficiency of computers, especially machines operating in multi-program mode.

A channel is a specialized processor

The input-output systems of modern computers should
- convert information to a form convenient for transfer to a computer, and, when necessary, carry out the reverse conversion;

⟦folio 52⟧

- connect to memory to exchange information with the air-blast, and only when it is really necessary, and assemble or disassemble information during pauses;

— provide the ability to parallelize work with other computer devices, in particular with ALU;

— use processor tools only when necessary: ​​for example, to analyze an error situation or to enable I/O operations.

In this case, the method of connecting air-blast devices to the input-output system should, if possible, be universal for different types of air-blast devices.

In modern computers, the listed requirements for input-output systems are implemented by devices called input-output processors. In EC series machines they are called channels.

figure 3 shows the structure diagram of the EC-1060. According to modern concepts, this is a fairly powerful computer, having two channels - sector and multi-amplifier - differing from each other, first of all, in the speed characteristics: for a sector channel, the throughput reaches 1.25 MB (1.25 × 2²⁰ bytes) per second; The sector channel is connected to air-wave speeds - magnetic disk drives (photo 4), tape recorders. The maximum throughput for information flows passing through a multi-type channel is 600 KB (600×2¹⁰ bytes) per second. Low-speed devices are connected to the multitype channel - these are punchers, readers of punched cards and punched tapes, displays, electronic typewriters, and ADPUs.

Channel Command Format

Just as the actions of a computer are determined by the programming that controls it, the work of a specialized processor - a channel - is controlled by a channel program intended for memory. A channel program consists of a sequence of channel commands, each of which causes the channel

⟦folio 53⟧

fulfill the definition of work. In some cases, not by processing, but by transporting information. The typical channel command format is represented by figure 4. The main fields in this format are:

— command field (operation code);
since the input/output device can operate in different modes, the command field encodes the nature of the work that the selected channel and the corresponding airwave must perform; the most typical operations are “Read” and “Write”;

— data address field, that is, a field in which the starting address of an array of information intended for transportation through the channel from the air-blast (or to the air-wave) is recorded;

— a field of attributes in which certain details of the information involved in the exchange are specified.

Processing a command in a channel
The ES computer command system also contains input/output commands, but unlike input/output commands, they represent only the initial execution of an input/output operation. So, for example,

The input/output command in the ES computer, which is called I/O Started, is reflected in the computer as follows:

— first a command from memory to the command register; The processor’s control unit “recognizes” it, that is, it determines that the oven is responding specifically to the command to start I/O; then, using the information contained in the address command, the numbers of the channel and input/output device with which the exchange is to begin are determined (Fig. 5a);

— each of the airwaves connected to the channel has its own number; when any of the input/output devices belongs to its own number, then it “confirms” receipt of the invitation to communicate; “confirmation” information contains information that the airborne device with such a number is really ready for operation (in particular, it is not disconnected from the network); While performing the initial sample sampling process, the channel simultaneously accesses one of the fixedly allocated memory cells - the channel address word (ACK) is stored there; The ACK is sent to the channel; the ACK, in particular, contains the starting address of the channel program (Fig. 56), which is to be used in the process of information exchange;

— the channel accesses memory at the address specified in ACK, and

Free ranks
Teams
Data address
Signs
Counter
0 18 31 32 36 48 63
Fig. 4.
CHANNEL
Microseconds
N°1 Airborne
N°2 Airborne
N°3 Airborne
Team NBB
Command register
Channel selection
to Air Force No. 2
Fig. 5a.

⟦folio 54⟧

gets the first channel command from the channel program; however, this program may consist of a single channel command (Fig. 5c);

— the channel begins decoding the channel command; it sends the command (bits 0-7 of the channel command) to the airborne device, which “recognized” its number at the very beginning of the “engagement” of the processor with the channel; if the airborne device is capable of executing the proposed command, then it will “respond” to the channel, allowing the “pumping” of information (Fig. 5g);

— after this, the processor “evaluates” the channel and processes other information; the channel “charged” with information management works with memory, making memory available to the processor from time to time;

— when the channel normally processes the first channel command (without recording any equipment breakdowns, any jammed punched cards, etc.), the progress of further operation of the channel will be determined by managing information in the attributes field (Fig. 4) of the channel command; in particular, if the “Command Chain” attribute or the “Data Chain” attribute is indicated in it, then the connection of the channel with the memory can continue; their relations in this case do not concern the processor (Fig. 5d);

— if the information is completed, then the channel restarts the processor’s work; Before transferring, the channel prepares a “channel state word” (CCW) in a buffer register, in which it reports in encoded form all the conditions of the end of the communication session, the request for transfer is sent to the processor and at the same time the CSC is written to one of the fixed memory cells; operating system decrypted

⟦folio 55⟧

determines the circumstances of the end and, depending on them, makes a decision: for example, continue work or print a request to the operator to change the magnetic tape reel to magnetic, etc.

Despite the fact that retrieving a channel command is reminiscent of composing a meaningful fairy tale: a needle is in an egg, an egg is in a duck, a duck is in a hare..., the efficiency of such an I/O organization is extremely high.

CONTROL OF INFORMATION EXCHANGE
All processes of information transfer to the computer are controlled. For control, each information path is accompanied by additional bits, which are called control bits. Their purpose is an additional amount of bits transmitted in a given period of time (cycle), up to an odd number. For example,

a zero byte is accompanied by a one in the check bit. Thus, 9 wires are used to transmit a byte (the ninth is identical to the bit). The control bit is formed in the information source using a special logic circuit; The information receiver, having received the byte, also generates a control bit. The transmission of information is considered successfully completed if the control bits of the source and receiver match. This control method is called “modulo 2 convolution”. It is easy to see that this method does not detect errors in an even number of bits. There are hardware control methods that allow you to catch double errors.

WHAT TO READ NEXT:

1. FLORES A. Organization of computers. (M., "Mir", 1972).
2. FLORES A. External computer devices (M., “Mir”, 1977).
