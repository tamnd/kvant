---
id: 1989-11-shvartsman-evm-i-elektrosvyaz-449d318c
issue: kvant_1989_11
year: 1989
number: "11"
title: Computers and telecommunications
authors:
  - Шварцман В. О.
rubric: raznoe
rubric_sub: Разное
page_first: 51
page_last: 58
page_labels: 49-56
tag: QNIT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 043bf919c5d99359a316d01ef5f71482594a3ebc408fb85ade9777d6afde150a
prompt_sha256: draft-1
translated_from: content/ru/1989/11/articles/15_shvartsman-evm-i-elektrosvyaz-449d318c.md
source_content_sha256: ac8498fc04b32e096d059ad6e8a303d1cdf5af24d778b821ce4441c8b8853a89
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

computer
and telecommunications

Doctor of Technical Sciences
V. O. SHVARTSMAN

The need for transmission, storage and processing of information arose along with human-equivalent society. At the dawn of their development, people communicated with the help of sound or light signals (screaming, whistling, hitting a drum, gong, bonfires, torches). The need to transmit not only signals “alarm”, “danger”, “attack”, “clears”, but also more complex messages led to the use of codes when different messages differed in the number of sound or optical signals, the frequency of their appearance, and the length of pauses between signals. At the same time, methods and means of storing information were created and improved. From notches with an ax on trees and cave walls, man moved on to rock paintings, clip art, hieroglyphs and, finally, to letters and numbers written on paper first with a pencil, fountain pen, and then with a printing press or typewriter. Even later, punching devices appeared, with the help of which messages were written on paper cards and tapes in the form of a combination of answers.

But a revolution in the field of information transmission and storage took place only when electrical engineering began to be used for this. Already at the beginning of the last century, attempts were made to use the property of electric current to quickly spread through wires to transmit messages. Message receivers based on electrostatic and electrochemical effects turned out to be expensive, complex, and cumbersome.

⟦folio 50⟧

They are unstable in operation and have not received practical application. The telegraph, based on the magnetic action of electric current, has been dominant for over 150 years, and only in recent years has it been replaced by electronic systems. The phone is somewhat younger - it is a little over 100 years old. After the discovery of radio communications, electromagnetic waves began to be widely used to transmit messages. Achievements in photographic technology, magnetic recording, and in recent years, head-finishing, have produced new storage media. So progress in the field of transmission and storage of information has been continuous. And the processing of this information until the middle of the 20th century remained the destiny of man. Various mechanical devices such as abacus, arithmeters and slide rules, and by the end of the 19th century, computers and tabulators only slightly speeded up calculations.

A revolution in the field of information processing took place in the middle of the 20th century, when advances in electronics made it possible to create electronic computers - computers. At first, computers were intended to solve mathematical problems (calculations, hence the name - computers), but soon the main area of ​​their application became information processing in various automated control systems and reference and information systems, united by a common term: information processing systems. In this regard, there was even a proposal to call computers not computers, but electronic machines. But in the literature, the abbreviation COMPUTER is increasingly being replaced by the foreign word “computer,” although the literal translation of this word is “computer.”

In the first decade of the existence of computers, people came to them with their tasks and took away the results of calculations. The capabilities of computers grew, the scale of the problems solved on them grew too, and it soon turned out that the delivery of initial information to the computer, and the processing results to subscribers using traditional transport means, in many cases negates the time gains obtained from solving a problem using a computer. In addition, very often these initial data already have the form of electrical signals that are not generally transmitted by mail. Therefore, at the beginning of the sixteenth century, the transmission of messages by electrical communication to a computer or from a computer. Unlike traditional telecommunication services, in which the source and recipient of information is a person, when transmitting data these functions are performed by a computer, which imposes a number of specific requirements on the data transmission service (DTS).

What should be required from SPD?

In a computer, any information (symbols, texts, images) is presented in a single form - digital (as a sequence of zeros and ones). Therefore, the telecommunication system in SPD must transmit digital information. A very important characteristic of SPD is the delivery time of a message of a certain length from the source to the recipient, since information significantly depends on the time of its receipt. The SPD must ensure delivery of a message of the required volume at a given time.

Both the volume of messages transmitted and the time requirements for their delivery can vary greatly. When transmitting planned or statistical information, message volumes can reach millions of bytes*), and the required time can be up to

*) 1 byte is equal to 8 bits, a bit is a unit of double information. 1 byte - the volume of a message consisting of one character (letter, number, space, etc.).

⟦folio 51⟧

rates are calculated in hours and even days. Delivery time to telephones (volume of about 300 bytes) takes several hours. When a personal computer is working with a central computer or data bank in dialogue mode, delaying a response for more than 2-3 seconds is unacceptable, since longer periods of time make it difficult to retain information in a person’s short-term memory. Even more stringent requirements for the time of message delivery are imposed by control systems for fast processes (for example, air traffic control), in which the time of information delivery must be commensurate with the speed of the process and therefore can vary in fractions of a second.

The value of information is determined not only by the timeliness of its receipt, but also by the accuracy of its transmission, called `достоверностью`. Reliability is characterized by the ratio of the number of erroneously received symbols to the total number of transmitted ones. For example, if the transmitted message contains $10^6$ bytes, and 16 bytes are corrupted during its transmission, then the reliability is $1.6 \times 10^{-5}$.

The requirements for the reliability of SPD are much higher than in traditional cases of electronization. In telephone communication, the reliability of $10^{-3}$ and even $10^{-2}$ is sufficient, and in telephone transmission $10^{-4}$, because often the meaning of the message will be understood correctly by a person even if 10-20% of the characters are distorted. In SPD, distortion of even one character (byte, bit) can lead to incorrect understanding of information and, as a result, a lot of material will be lost.

Reliability requirements in various SPDs range from $10^{-6}$ in most general use cases to $10^{-9} — 10^{-12}$ in banking systems and special management systems. Note that the reliability of the value $10^{-6}$ corresponds to one operation in a book of 400 pages.

Often several computers work together, forming a local or territorial network. At the same time, they must exchange information, i.e., the computer source of information must be given the opportunity, when transmitting messages, to address it to a specific computer recipient of the information. SPD is required to deliver information to a given address, and the probability of sending to the wrong address should be very small, for example, one message per billion transmitted ($10^{-9}$).

Computers as sources and recipients of information in SPD can have different characteristics: different methods of transmitting information, different transmission speeds, different codes. The requirement to ensure the interaction of such computers is equivalent, for example, to the requirement that telephone communications provide common subscribers speaking different languages ​​(which, as is known, not only does not exist, but is not yet expected). And yet, the SPD is required to be able to exchange messages between computers of different types.

Naturally, SPD, like other electronic services, requires high reliability, survivability and efficiency, first and foremost - protection of transmitted data from disclosure, the ability to develop and provide additional services to subscribers.

In order to understand how all these requirements on the part of a computer are met by means of electrons, let us consider how information is transferred between computers.

Computer communication

The general scheme for transmitting information between two computers: the source computer (computer-I) and the recipient computer (computer-P) is shown in figure 1. When the need arises in the computer-I to transmit a message, it is sent in the form of a sequence of pulses from the output device of the computer-I to the SPD, with the help of which it is transmitted.

⟦folio 52⟧

is connected to the computer-P input. The connecting element between the computer-I and the computer-P is the communication channel.

Chains, i.e. pairs of wires of cable communication lines, are used as communication channels when transmitting over short distances (up to 10 km), and over long distances - channels of transmission systems via cable, radio relay or satellite communication systems.

A communications cable is made up of several insulated copper conductors or thin strands of glass (in fiber optic cables) enclosed in a protective sheath. In radio communication lines, unlike cable lines, the propagation of electromagnetic waves occurs not in a closed space (cable), but in an open one. In radio relay lines, the transmission of signals from one point to another is carried out through a number of intermediate points at which the signals are received, heard and transmitted further. In satellite systems, signals from a ground transmitting station are radiated towards an artificial Earth satellite, where they are received, heard and transmitted towards a receiving ground station.

In radio communications, a large number of radio stations operate simultaneously in different frequency ranges without interfering with each other. Such frequency division of channels can be used in SPD, which makes it possible to form many channels on one pair of wires (physical circuit), each of which can simultaneously transmit various information.

Requirements for the parameters of the signals at the output of the computer-I and the input of the computer-P are usually not consistent with the characteristics of the communication channels. In addition, signals in communication channels are subject to interference. As a result, the signal at the output of the communication channel differs to one degree or another from the signal at its input, which can lead to a decrease in reliability below acceptable requirements.

To reduce signal distortion at the input and output of the channel, special signal conversion devices are used, and to increase reliability, error protection devices (RCDs) are introduced. These devices, together with transmission control devices, form a transmitter, including between the computer-I and the communication channel, and a successor, including between the communication channel and the computer-P.

During a telephone conversation, one of the interlocutors, having mumbled a phrase, asks the other to repeat it again. In SPD, error detection, request for repetition and repetition of the distorted part of the message must be carried out automatically by the receiver and transmitter. This is done using error detection codes in combination with feedback. To enclose all the main characters displayed in a computer (uppercase and lowercase letters, Russian and Latin, numbers and punctuation marks), it is enough to use a seven-digit code that allows $2^7 = 128$ code combinations. It uses the code combination 1100001 to transmit the letter A. If, as a result of interference and distortion in the channel, it is received in the form 1110001, then the recipient will be given the letter Y. To detect errors, not a seven-, but an eight-digit code is used: the original code combination is supplemented in the RCD with a zero or a one so that the number of ones in the code combination is even. In this case, to transfer

⟦folio 53⟧

Fig. 2.

letters A use the code combination 11000011 (the last character is entered by the transmitter) and if 11100011 is received, the receiver detects an error (the number of ones in the received code combination is odd). The rejected code combination is not issued in the computer-P, and through the feedback channel the receiver sends a request to the transmitter for its retransmission.

To ensure the secrecy of transmitted data, it can be protected. Encryption and decryption are also done by the SPD transmitter and receiver using a certain algorithm using a welded part (key). The key can be transmitted over a separate channel.

The most commonly used communication channels are the so-called voice-frequency channels used for telephone communications. They have a frequency band of 300-3400 Hz and carry out data transmission at speeds of 4800 and 9600 bps, and in some cases up to 16,000 bps. To coordinate the computer and the communication channel, the SPD transmitter includes a modulator that converts the sequence of rectangular pulses received from the computer into a series of sinusoidal signals with frequencies from 300 to 3400 Hz. The SPD receiver demodulator performs the inverse conversion (see Fig. 1). Transmission to the SPD is carried out, as a rule, in general directions, therefore, in each terminal installation of the SPD there is a modeler and a demodulator, combined into a single device - a modem. Many types of modems have been developed using different modulation methods with corresponding data rates.

Amplitude modulation consists in the fact that transmission 1 from the computer-I corresponds to a sending in the communication channel of a segment of a sinusoidal signal of determining duration, and transmission 0 corresponds to a pause (of the same duration). This modulation allows you to create SPD only at low speeds (200-600 bit/s).

To achieve a data transfer rate of 600-1200 bit/s, frequency modulation is used, in which a sinusoidal signal of one frequency is sent to transmit 1 from the computer-I in the communication channel, and another frequency is sent to transmit 0 (for example, 1100 and 2100 Hz).

Data transmission rates above 1200 bit/s are ensured by phase modulation, in which transmission 1 from the computer-I corresponds to sending a sinusoidal signal of one frequency in the communication channel, and transmission 0 to another (for example, 180° and 0°; see Fig. 2).

If higher transmission speeds are required, it uses broadband channels with frequency bands of 48, 240, 1200 kHz.

But it is also possible to transmit data via a telephone channel at speeds of up to 64,000 bps. For this purpose, time division of channels is used, when, for example, different pairs of computers take turns exchanging information over one communication channel.

In the channels of a time division system (they are called digital), the information carried is a sequence of pulses. Built-in SPD transmission signal conversions superimpose pulses from the computer onto these pulses. In this case, modems are not required.

When a large number of computers interact, the task of organizing the exchange of information between them will arise. If you use a separate computer for each pair of computer-I - computer-P

⟦folio 54⟧

Fig. 3.

cash PD, then for communication $n$ computers will require $n(n-1)/2$ two-way channels and $n-1$ input-output for each computer (Fig. 3), and the useful time of each channel and input-output of the computer will, as a rule, be small. But you can get around it with one input-output for each computer and a smaller number of channels. As an example, figure 4 shows a computer network with one information distribution node and a total of $n$ channels, allowing each computer to be connected to any other. The task of such a node, called a switching node, is to organize a connection that allows messages to be transmitted to the computer-P address specified by the computer-I. Therefore, modern communication networks are a collection of communication channels, switching nodes and subscriber devices (Fig. 5). And in each of these components a technical computer is widely used.

Computer for communication

The most widespread use of computers is in switching devices. The reason for this is that the function of switching communication devices over a network also follows the classical algorithm of computer operation and the properties of the following basic operations:

receiving a message from a communication channel and recording it in memory;

logical processing of the message, for example, recoding;

reading a message from memory (if necessary at a different speed) and transmitting it to a given address in another communication channel.

The use of a computer provides functional flexibility, control and automation of troubleshooting, cost accounting and provision of additional services to subscribers, such as: abbreviated dialing for more frequently called subscribers (3 digits together 7), putting a call on hold when the subscriber is busy, transferring to another number, etc.

An equally widespread computer is used to build terminal devices: for error protection, signal conversion, control, diagnostics, and control of connection establishment processes.

As in other technical branches, computers are widely used in communications to automate scientific research, design and construction, and manage economic and social processes.

Modern information computing systems are a combination of computer technology (message processing) and communications (message transmission). The development of technical computers and communications led to the creation of new telecommunication services - telematic services. However, one such service is Teletex, designed for preparing and transmitting letters over the telephone network. The subscriber installation consists of a personal computer and a signal conversion device with an automatic ringing device. It ensures the preparation of letter operators and their editing, filling out prepared letters for their subsequent

⟦folio 55⟧

transmission over the telephone network, automatic (without operator participation) transmission and reception of letters, automatic correction of errors that have arisen in the communication channel, automatic execution of a wide range of orthogonal functions (compilation of transmission and reception logs, assignment of incoming and outgoing numbers, generation of the sender's screen, etc.), printing of received letters.

The equipment provides high speed information transfer - one page of text at a speed of 2400 bps is transmitted in 10-12 seconds. Taking into account the connection setup time over the telephone network, each business letter can be transmitted to the recipient in 1-2 minutes.

The capabilities of the Teletex service can be significantly increased with the planned installation of specialized computers in the future, the memory of which is divided into separate sections - boxes. Each user (subscriber) of the service who rents a box (or several boxes) can at any convenient time, for example during periods of least network load, enter messages into the box and receive information from it. This service, by analogy with an inscription on a slate board available for public viewing, is called a “black board”.

It is possible to “browse” receive a box message by printing a summary of the contents of letters, including targeted ones, for example, only messages received from a specific subscriber, or messages on a specific issue (a keyword is indicated, for example, “email”).

Another service - Videotex - is an information and correction system that provides communication between users located with the appropriate software (Fig. 6). This computer stores information intended for users. An important element of the data bank is the so-called service center, whose task includes determining the validity of a call received from a user via the telephone network, charging services, ensuring interaction with the user’s terminal equipment, as well as other tasks.

The Videotex service is intended for the widest circles of the population, therefore the terminal equipment is usually carried out to the maximum

⟦folio 56⟧

but simple. This equipment consists of a logical block with a keyboard, a modem and a conventional bit TV that performs display functions. The telephone network is used as a communication network, and specially designed devices with a custom keyboard or a bit-based personal computer are used as a logical block with a keyboard.

The user, installed in the data bank, requests from it information of a very different nature.

The Videotex service transmits information about news (city, country, foreign news), weather, sports and cultural events, provides addresses and telephone numbers of various institutions, advertises

services of enterprises in the state and cooperative sectors, etc. We will also mention various kinds of useful advice (on housekeeping, gardening, medicine), offers from employers in the state and cooperative sectors, education (school, adult, retraining, advanced training, etc.), entertainment (TV games).

The Videotex system can also be used to make all kinds of purchases, reserve tickets, etc. The user has access to not only the information stored in the Videotex system data bank. Pieces of information of a specialized nature can be stored in other banks, for example, in trade, supply data banks, etc. The Videotex system data bank accesses specialized data banks as requests arise from users. For this purpose, appropriate communications have been established between banks.

As it spreads throughout the country, the Videotex service will acquire new capabilities: exchange of information between users (and not just between data banks and users), exchange of information between users of the Videotex service and other telematics services.

Thus, the effective use of computers is unthinkable without quick and reliable access to information to and from them. And this can only be provided by a network of electrons. On the other hand, a modern communication network cannot work without a computer. The idea of ​​mutual and consistent cooperation between communications and computers was very figuratively expressed by the American specialist in information systems R. Fano: “The marriage between computers and communications was served, the connection was over, the honeymoon was over, and the spouses began to feel more and more how they began to depend on each other.”
