---
id: 1981-7-saltovskiy-es-evm-semeystvo-universalnyih-vyichislitelnyih-mashin-6d925e82
issue: kvant_1981_7
year: 1981
number: "7"
title: ES Computers - a family of universal computers
authors:
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 55
page_labels: 51-53
tag: U4AA
lang: en
source: kvant_digital
extraction: vision
content_sha256: f63f943a806c7bea987b56b9bb4add32021c51093b9ac0657d2f217d5e1e0406
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/21_saltovskiy-es-evm-semeystvo-universalnyih-vyichislitelnyih-mashin-6d925e82.md
source_content_sha256: ab3ac8c67b985195a5ca9ab2cea4dcc1ed01eab580d747253680a239eb30e513
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

A. Saltovsky

ES computer family
universal
computing
cars

Currently, mainframe computers are usually designed and manufactured in families. Each member of the family has the same basic technical characteristics for the whole family, but differs from its “relatives” in performance.

In the USSR and socio-economic countries, the most widely used family of general purpose computers is the EC series (Unified System). Big ten types of computers in this series, having different performance, are compatible in terms of using programs and data. The family has a wide range of peripheral devices used in almost all machines of the series. All machines have the same design and technological principles of construction.

The main goal that was set when designing the family was to cover as many areas of computer application as possible. so that the cost of machines and the cost of their manufacture are in equivalent correspondence with the speed of solution, the importance and complexity of solving problems. The same purpose is served by a single family of software, the cost of which today exceeds the cost of hardware. It is fundamentally important in such conditions to have a common input-output interface - a standardized set of technical and software means of communication between the channel and external devices, which makes it possible to organize the exchange of information between them in a standard form; this allows the use of a wide variety of external devices in one computer.

Family composition

Since 1969, when an agreement was reached between the CMEA countries on cooperation in the field of computer technology, in a relatively short period of time, EC computer models of the first stage - Row-1 - were developed, and since 1973, the development of more advanced models of this series - Row-2 - began.

Today the family composition looks like this:

small computers:
models - EC-1010, EC-1020, EC-1021;
speed - 10÷100 thousand operations per second;
RAM capacity - 64÷512 kilobytes;

medium computers:
models - EC-1022, EC-1030, EC-1032, EC-1033, EC-1035, EC-1040, EC-1045, EC-1055;
speed - 80÷500 thousand operations per second;
RAM capacity - 128-2048 kilobytes;

mainframe computers:
models - EC-1050, EC-1052, EC-1060, EC-1065;
speed - 500 thousand ÷ 3 million operations per second;
RAM capacity - 512÷8192 kilobytes.

Unity of external devices

Information input and output devices used in modern computers are numerous and varied. This is the ATsPU (alphanumeric

⟦folio 52⟧

first printing devices), and punched card input devices, and punched tape input-input devices. In recent years, devices for direct, interactive communication between the operator and a computer have become widely used - electronic typewriters and alphanumeric displays *). All these devices exist in the EC family of computers. EC computer input devices are single-circuit: each of them can be connected with equal success to any of the machines in the family. Cherry storage devices, which in the EC family of computers are represented by magnetic disks and magnetic tape drives, are connected to machines in the same way. Thanks to the standard interface, they can be used in different models, regardless of their performance. The difference is usually purely quantitative: more

*) More details about external devices are described in the article “Organization of input and input into a computer” («Kvant», 1980, No. 6).

Machines with greater productivity have a powerful fleet of external devices. For example, the volume of external memory on magnetic disks is 15 ÷ 100 metabytes for low-performance EC computers, and for machines with higher performance it reaches several hundred metabytes.

Unity of architecture

The “family” continuity of various EC computer models is clearly visible in the diagram (see figure), which shows a number of devices required for each model.

As an example, the general structure of the EC computer model Row-2 is considered.

The main elements of the EC computer architecture Row-2 are as follows: 1) processor; 2) RAM; 3) input-input channel; 4) control of cherry devices; 5) external devices.

The core of the system is the central processor («Kvant», 1980, No. 5).

⟦folio 53⟧

The internal organization of the litter process may differ from one model to another. This is because the performance of a model reflects the cost of its production. By analogy with, say, shipbuilding, we can say that it is not at all necessary to give the hull of a pleasure boat icebreaking strength - each has its own functions.

Software compatibility between machines of different models of the EC computer family is ensured by the fact that for all models the same command system is implemented and the same data structure is used (see the article “Three-address, uniaddress and... addressless machines” in No. 4 «Kvant» for this year). In particular, each processor in EC computers has 16 general purpose registers and 4 floating point registers*) to ensure increased calculation accuracy, and the latest models of EC computers (Series-2) have sixteenth control registers in the processors; these registrations are inaccessible to ordinary programs, but are actively used by the control program to organize and control the computational process.

A mandatory accessory of all processes of the EC computer model is the program status word register. The program status word, which is stored in this 64-bit register, is intended to control the sequence of instruction execution known from RAM.

Data exchange between RAM and external devices is achieved using a channel (a specialized input-output processor - see the mentioned article in «Kvant», 1980, No. 6). Process intervention in this processor is minimal - it starts the operation and analyzes the result at the end of its execution.

*) This means that the comma before the trial part of the number can be placed in different places in the register.

Software Unity

The EC computer command system, uniform for the entire family, allows for a wide range of operations on high-precision numerical data required in scientific tasks and in accounting and economic applications, and on derived symbols characteristic of text information processing tasks.

The same general line of standardization within the family and universal application is also visible in programming systems in high-level languages, which are based on the programming languages ​​Fortran, Cobol, Algams, PL/1. Nowadays, many users of EC machines have the opportunity to work in Pascal. This language will be discussed in detail at the Correspondence School of Programming after the summer holidays.

Speaking about programming the compatibility of machines of the family, it is important to note that not all programs written for EC computers Row-2 will work on EC computers Series-1, since the older models of the family contain an additional command group, implemented only on these latest models. But EC computer programs Row-1 can be processed on EC computers Row-2 without any changes. In this case, they talk about programming continuity “from bottom to top.”

Currently, EC computers represent the development of a system of computers in social countries, a system that has become widely used in all sectors of the national economy. The development of new generations of the family continues. The main devices of designers are now aimed at both increasing productivity and reducing costs. This is primarily due to the transition to a new design and technological base - large integrated circuits.
