---
id: 1986-9-kovalenko-mikroprotsessor-izmeryaet-800e3b4b
issue: kvant_1986_9
year: 1986
number: "9"
title: The microprocessor measures...
authors:
  - Коваленко М. Д.
rubric: raznoe
page_first: 23
page_last: 24
page_labels: "22"
tag: HZYQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1f2984eadd09aad5fee5b83b991b27b41b6ffbf49affeb3051c8494d99e15a9f
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/07_kovalenko-mikroprotsessor-izmeryaet-800e3b4b.md
source_content_sha256: 5eb2c2bcd29b5ca2f6979e08257debaf53ebfe96a8cb7e500346137b01df07dc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

The microprocessor measures...

M. D. KOVALENKO

What device can you use to measure the temperature of frozen chicken? Of course, with a thermometer! Make an incision in the carcass, insert a thermometer, wait a little... And if this needs to be done quickly, and not spoil the presentation? You ask, what do these questions have to do with the topic of statistics? The most immediate thing that the reader can verify by familiarizing himself with the thermometer devices of the microprocessor era.

Let's start with the temperature sensor. In order to measure quickly, the thermometer is made in the form of a hollow needle, which can be stuck into the carcass without almost spoiling it. A sensor is placed inside the hollow needle - a metal wire, the resistance of which is in a small range of the prohibition temperature on the wire; you can use this form to calculate the temperature. Fast? Not really, even if he has a microcalculator at hand. The use of a microprocessor allows you to significantly speed up the measurement process.

A simplified block diagram of a microprocessor thermometer is shown at figure. A microprocessor (MP) is a computing and control electronic circuit whose role is essentially similar to the role of the brain in an animal organism. Structurally, an MP containing ten thousand transistors is one microcircuit. The MP works with numbers, so a non-continuous, or, as they say, analog signal from the sensor (voltage) must arrive at the MP input converted to digital form. This work is performed by an analog-to-digital converter (ADC). The microprocessor thermometer contains storage devices (3U) of two types: operational (03U) and permanent (P3U). In 03U, numbers and programs can be freely written and read, but after turning off the power, all contents of 03U are erased. In P3U, information is recorded only once, but it is stored “forever.”

How does a thermometer work? Previously, during calibration, constant coefficients a and b are determined and recorded in P3U. MP works

*) Such a sensor is called a resistance thermometer and is rarely used. It is common practice to use thermocouple or semiconductor sensors, but this has little effect on the measurement principle.

⟦folio 22⟧

according to a program also recorded in ROM. A program is a sequence of step commands that the MP executes one by one at a speed of thousands or even millions of steps per second. A conditional temperature measurement program could be something like this (as a result of the program, each of these steps executes several commands):

Step 1. Call up the numbers $a$ and $b$ from ROM.

Step 2. Enter the number from the ADC into the MP (this number is the voltage value $U$).

Step 3. Calculate the temperature using the formula $t=(U-a)/b$ (the result is written to RAM).

Step 4. Display the number recorded in RAM on the digital display.

Step 5: Proceed to Step 2. This program will cause the temperature value to be displayed on the display at thousands of readings per second. Now we can find out the temperature of the fast one (here is the list!). In practice, this frequency is reduced many times for ease of observation. (You could see a similar picture on the display of electronic scales.)

Let's consider a more complex example - a digital voltmeter built by an MP. Its block diagram is approximately the same as that of a thermometer. Suppose we are interested in voltage fluctuations in the network. You need to find out how often during 1 hour the effective voltage value goes beyond 210-230 V. You could solve this problem like this: take a common digital voltmeter with a digital reading device (DLC) and run the voltmeter for measurements at intervals of 1 second. In an hour we will receive a paper tape 3-4 m long with 3600 numbers and, armed with patience, we will begin to count the number of numbers on it that fall outside the interval 210-230 V. Would you like to do this kind of work? Hardly. So let's make MP work! To do this, let’s create a program (as in the first example, these are the program conditions):

Step 1. Clear RAM memory cells with numbers (addresses) $N_1$ and $N_2$, that is, writing zeros to them.

Step 2. Measure the effective value of the network voltage $U$.

Step 3. If $U<210$ or $U>230$, then add one to the contents of the memory cell with address $N_1$.

Step 4. If $210≤U≤230$, then add one to the contents of the memory cell with address $N_2$.

Step 5. Wait 1 second.

Step 6. Proceed to step 2.

As a result of the operation of this program, the RAM cell with address $N_1$ will accumulate the number of measurement results beyond the limits of 210-230 V, and in cell $N_2$ the number of measurement results falling within this interval. This data can be continuously displayed on a digital display, so it is enough to stop the program 1 hour after starting and look at the display to find out how often the mains voltage fluctuates. You can measure a program and make it stop itself after completing a specified number of measurements.

The “menu” of a microprocessor voltmeter usually contains decimal programs: statistical processing of measurement results, searching for maximum and minimum values ​​of inter-Earth voltages, analyzing the formula of periodic signals, etc. These programs, which can contain hundreds of steps, are written in ROM, so there is no need to create programs yourself to work with the devices. You just need to familiarize yourself with the purpose of 2-3 tens of kopkas.

These two simplest examples show the enormous use of devices built by microprocessors: they do not produce “raw” primary data, but processed data, that is, listed in final values. The use of such devices will lead to greater savings in people's labor and an increase in their productivity. However, the most useful application of MP is manifested in control systems in which there is feedback, that is, the occurrence of MP on the controlled object. Such systems include, for example, industrial robots. But this is a topic for special development. In the meantime, when buying frozen chicken in stores, don’t forget to rate it. If the problem is soft, then, of course, everything is clear without MP.
