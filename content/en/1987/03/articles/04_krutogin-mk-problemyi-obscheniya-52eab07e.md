---
id: 1987-3-krutogin-mk-problemyi-obscheniya-52eab07e
issue: kvant_1987_3
year: 1987
number: "3"
title: 'MK: communication problems'
authors:
  - Крутогин Д. Г.
rubric: raznoe
page_first: 16
page_last: 19
page_labels: 14-17
tag: AXO4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6c4f0c364eb1824a2adc955a936ae3fcc3fce2b5c91fbe5f96dec7e5fecfc6f0
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/04_krutogin-mk-problemyi-obscheniya-52eab07e.md
source_content_sha256: 69fd699b2f3559cfe0f1c2143ff15d2bcc02ee6b7728aebcd687802829e54c2c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

MK:
COMMUNICATION PROBLEMS
(Journey through a microcomputer)

Candidate of Technical Sciences D. G. KRUTOGIN

In the previous issue, we took MK on a walk around the city, examined the panorama of the city, and introduced the city’s residents, temporary and permanent. Now is the time to look at the city plan to appreciate its structure. In the schematic plan (figure 1) you can see five large districts connected to each other. We will go through them in the following order: input device (IDU) and output device (UD) areas, random access memory (RAM) area, read-only storage devices

⟦folio 15⟧

(ROM) and finally the microprocessor (MP) area. The visa in the photograph is a real microcomputer crystal, magnified 10 times. This is how it looks independently until the process of manufacturing the circuit and placing it in the case is completed. It is not so easy to indicate the boundaries of regions, especially since the free space on the chip is almost invisible. Therefore, it is more convenient for us to move according to plan. And now let's go...

Area of ​​tridiati stations

On the plan (figure 1) of the visa there is a tourist reception center, or an input device system (IDS) (recall that tourists in MK are machine words combined into programs - delegations). Delegations from different countries arrive here, in the UVV area, using a variety of transport means. For example, from the display keyboard, from external memory tape recorders (VRAM) *), from the display screen or from external sensors. Therefore, the airborne area is a collection of several stations or ports **).

No UVV is not only a station, but also an exemplary tourist office of our city, as well as customs, cutting off incorrect or unacceptable program words, phrases or commands. Input devices are met by tourist delegations, check entry documents, and provide them with translators and accompanying persons (addresses). Finally, the same devices also monitor tourists in the city during their stay.

So: the first task of input, even before analysis and translation, is to unload the transport that delivered the programs to the city, that is, the information input line. To do this, you need to record the received signals (for now just recording, without any processing) in the language in which they were sent. Initially, the input ports perform the writing of the words of the source program. They, in fact, are small blocks of RAM one machine word long, that is, registers. Each register is equipped with a block of logical elements *) - a buffer, which ensures the connection of an empty register to external information lines, and a filled register to the microprocessor. The microprocessor periodically polls the input ports and reloads the words they contain into RAM, after which the ports are ready to write a new word.

Who is in command of the parade?

It should be noted that the UVV is actively involved in all these activities, but the main character is the microprocessor. Under the control of the input program (stored

*) The device of registrars was considered in the PEVT section in «Kvant» No. 4 for 1986; design of logical elements - in «Kvant» No. 2 for 1986.

**) Here the words “port” are not only a literary image, but also a technical term. This is the name given to the part of the microcircuit in the UVV or UVV regions that provides its MK with external devices.

⟦folio 16⟧

in ROM) he cooperates with the UVV, receiving tourist groups.

In general, let us note that when considering the operation of a computer, it is always useful to distinguish between hardware (say, real ports, input outputs, memory cells, etc.) and software, that is, those actions that are performed by individual elements of the microcontroller, supported by certain programs that control the machine at different stages of its operation.

Bot in front of you is a switched off computer. Now you press the "On" button... what? What actions must the machine take to prepare for operation, for input of the user program? Who controls it until you enter your program? Answer: a proprietary program written in ROM called “monitor”. It is given priority immediately after the machine “awakens”. The revived, but unloaded MP seems to send the question to all ends: “What to do? What to do?" And the monitor program is the first to respond: “get ready for input, clear the RAM, call the input program, specify which port is open (from which port) the input will follow...” Then the editor will give up command of the input program, and after the input is completed, the monitor will order the MP to start using user programs. Bot what an important program this is - montor! And besides the montor, MK has several more utility programs.

We speak different languages ​​again

The next task performed during input is translating the user's program text into machine language. Bot here we return to the conversation about translators. The translators live right there in the city, in the PZU area. These are special utility programs called translators (to translate). There are different translators: one is more like simultaneous interpreters, others are more like literary translators.

Synchronizers (or translators-interpreters) translate one next command and send it unrepresented for execution. The translated text is not stored in the memory of the simultaneous interpreter, so when working again from the same program and the same command, the translator-interpreter again does the same work. But sometimes he suddenly refuses to translate; this means that the source program contains an inaccurate, incorrect expression. The interpreter cannot translate the error; it is not in its “dictionary”. Then an error message is sent to the output devices (OUD), even about the nature of the error.

Literary translators (or translators-compilers) work more reliably. Command by command, they rewrite the original program into the language of the microcomputer and occupy it in its RAM. At the end of this work, a complete analogue of the original program is stored in RAM, but in machine language. After finishing the work, this program translator is ready for use, including repeated repetition.

Which translator is more necessary and better? Both are needed. For technology with a machine, for working in dialogue mode, an interpreter is more convenient; it allows you to edit and change any command anywhere in the program. For MK, the interpreter is more convenient because it requires less RAM (for recording) and permanent memory (for storing the “dictionary”). For lengthy, repeated calculations on a large and complex program, a compiler is more convenient, since it works much faster.

No tests and no errors

The next task of the receiving area is the resettlement of the program. For this purpose, a hotel kit called RAM is used - operational filling of devices. We will raise this a little later, but now we note that command words and operand words need to be distributed in different cards of the RAM region. As mentioned earlier, from the “point of view” of the machine they are indistinguishable, and if they are confused during program execution, then the use of the program will be disrupted. So that a command or operand can be easily found at the right time, set inputs supply all the words being settled with addresses, and the address

⟦folio 17⟧

you need to remember it, put it in a kind of “address” book. After this, the machine no longer works with words as such, but with addresses. For example: send the contents of cell No. 95 of RAM to the MP (for example, we allocated cells with numbers from 000 to 199 for commands). Another example: compare the contents of cell No. 286 with zero and enter the larger number in cell No. 286.

And finally, the tourist bureaus of the receiving area coordinate the order of tourists’ stay in the city and order the appropriate services. Agree that for the calculation of two short equations written in five characters, for example,

$$c = a + b, \\
c = tg a^b$$

— completely different preparatory work will be required. On the scale of city life, the first task is as simple as buying a newspaper, the second is more like organizing a folk dance festival. Here you need to find (where? in ROM) programs for calculating power functions, and then tangents of an arbitrary argument. But if tourists want to attend the festival, then it must be organized, these are the working conditions of our city - a tourist center.

Output devices, located on the plan next to input devices, perform many complex functions, but, of course, in the reverse order. They convert machine words - the results of calculations - into a consumer-friendly form (in the form of a table, graphs, text, sound alarm or even speech) and supply control signals to the appropriate output device: display, printing device, sound generators that simulate speech.

Further, the output device is a simple seven-set digital indicator (figure 2), then to control it at the output of the MK there must be a logical circuit containing about a hundred transistors. And on the display of a simple calculator there are usually at least 5-8 such indicators, and even on an electronic watch there are at least four.

So, we got acquainted with the tasks of two districts of the city of MK, but along the way
