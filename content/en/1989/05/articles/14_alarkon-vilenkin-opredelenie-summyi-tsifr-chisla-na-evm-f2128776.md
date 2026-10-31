---
id: 1989-5-alarkon-vilenkin-opredelenie-summyi-tsifr-chisla-na-evm-f2128776
issue: kvant_1989_5
year: 1989
number: "5"
title: Determining the sum of digits of a number on a computer
authors:
  - Аларкон Е. Х.
  - Виленкин А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 68
page_last: 69
page_labels: 66-67
tag: 77EJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2ea2530968ca4b50ee65e9344e5941e3ae9223ea5e4516298426975d0eefc32f
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/14_alarkon-vilenkin-opredelenie-summyi-tsifr-chisla-na-evm-f2128776.md
source_content_sha256: 7c4aa991e3727c5f60e324b01992aa1ff88adce33ef564ce3ac1a30e0f3c6f8d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 66⟧

Determining the sum of digits of a number on a computer

E. H. ALARCON,
A. N. VILENKIN

At a preparatory department of one type, future applicants were offered the following task.

The sum of the digits of the key pages is 3684. Find the number of pages in this book.

How to solve this problem? And how can you teach a computer or microcalculator to solve this problem? The first thing that comes to mind is to teach from page 1 and add to the sum S (initially equal to 0) the digits that the next page number is written down until we reach 3684. To do this, we must first teach the computer to extract from the page number the digits that this number is written down. For example, from the number n=128 you need to get three numbers: 1, 2, 8 (we will limit ourselves to three-digit numbers). Let's use the function [x] - “integer part of x”. It is available on computers and MK-61; on other (programmable) microcalculators it can be implemented using the following subroutine.

Line no. Command code
80 1 01
81 + 10
82 X→Π 43
83 KΠ→X Γ3
84 Π→X 63
85 B/O 52

The operation of this subroutine is based on the fact that the indirect indication command from the RG3 register not only decreases the contents of RG3 by 1, but also decreases it to an integer, unless the contents of RG3 are greater than 1 and are displayed with a natural comma position. Of course, the RG3 register should not be used in the main program. When accessing a subroutine, the original number must be in the X register, and the result will also be obtained there. (Otherwise, command 79 V↑ 52 must be provided.)

To get the number of hundreds of a three-digit number n, take [n/100]. This will be exactly the integer number of hundreds contained in the number n. Let's denote it by R2:

R2=[n/100].

Next, let’s remove hundreds from the number n, without touching the tens and ones, and to do this, subtract [n/100]·100 from the number n, let this be the number m. It is two-digit and contains tens and ones of the number n. (So, if n=128, then m=28.) What to do with it is already clear:

R1=[m/10]

will be the number of tens, and

R0=m-[m/10]·10

— number of units. Now we write a subroutine for calculating the sum of the digits of the number n, i.e. the sum R0+R1+R2, and the main program for calculating the sum (loop through k from 1 to n) of the digits of page numbers from 1 to n. Let's run it to calculate the sum of the digits of the number

⟦folio 67⟧

ditch the pages of “Kwan” (n=80) and let’s see what happens.

If the program is installed on the computer, the answer will be obtained quickly. But it is clear that the operating time of a computer depends on n - the larger n, the more the computer will work. You can try everything in the program, print the results and stop when you get the number 3684 (or more), run this program for a sufficiently large n and get the answer to the original problem.

If the program is installed on a microcalculator, then the operating time will be 10-13 minutes, because the processing cycle for one page number takes 7-10 seconds, and there are 80 pages.

But in 10 minutes we can already find the original amount, without adding up all the numbers of all the page numbers. Let's first look for the sum of units. Here we need to add the numbers 1, 2, 3, 4, 5, 6, 7, 8, 9, 0 and again 1, 2, ..., such sums will be used from 01 to 80). 1+2+...+9=45, 45×8=360. With tens it is even easier: one will appear 10 times (from 10 to 19), as will two, and three... up to seven inclusive. Only 8 tens will appear only once. We get the sum of the number of tens in the form (1+2+...+7)·10+8=288. Total: 288+360=648 - initial amount. The microcalculator will soon give it.

Now it is clear that the method of simply adding the numbers of a microcalculator will add to the number 3684 in about an hour. This is too long. Is it possible to put on a microcalculator the calculation of the sum of the digits of pages from 1 to n in the same way that we looked for the sum of digits of the pages of “Kwan”? The number of calculations using this method is almost independent of n, so the operating time will be short.

Let's try. Let the number of pages be n and written in numbers i, j, k. This is denoted as follows: n=ijk. Let first i=0, j=0 (n is a single-digit number). Then the original sum is equal to k(k+1)/2 - this is the sum of the arithmetic progression 1, 2, ..., k. Let's denote this sum f1(k): f1(k)=k(k+1)/2. In particular, f1(9)=45.

Let now n=jk and j≠0 (n is a two-digit number). We will divide the required sum into two parts: from 01 to (j−1)9 and from j0 to jk. We calculate the first sum in the same way as we calculated the sum of the digits of the Kwan page numbers: ones - 45j, tens - 10(j−1)j/2. In the second sum, k+1 is a number, the sum of the number of tens is j(k+1), the sum of units is f1(k), except the sum f2(jk) has the form

f2(jk)=45j+5j(j−1)+j(k+1)+f1(k)=j(5j+41+k)+f1(k).

In particular, f2(99)=900 (this will be useful later), the formula “works” for single-digit numbers (j=0).

Let now n=ijk and i≠0. Again, we divide the sum into two parts: from 001 to (i−1)99 and from i00 to ijk. We count the first amount. Tens and ones (together) give i·f2(99)=900i (is it clear why?). Hundreds give 100(i−1)i/2 (each hundreds digit is used 100 times). We count the second amount. Hundreds give i(10j+k+1), and tens and ones give f2(jk). The required sum f3(ijk) has the form

f3(ijk)=900i+50i(i−1)+i(10j+k+1)+f2(jk)=i(50i+10j+k+851)+f2(jk).

This formula “works” for both two-digit numbers (i=0) and single-digit numbers (i=j=0).

So, the formulas are obtained. They can be easily installed even on a programmable microcalculator, and after entering the number n into it, it will calculate the initial amount in 15 seconds, for example: f3(96)=849, f3(200)=1902, etc.

Having gained in speed, we lost something. Now we can no longer run the program and wait until it reaches the number 3684. What to do is to use the trial and error method (sometimes called the “poke method”). Let's point at the number 200 - not enough. Let's try f3(400)=4204 - a lot. Let's try f3(300)=3003 - not enough. And so on until it reaches the original one.

(For the end see p. 70)
