---
id: 2023-1-dorichenko-sto-zamkov-i-sto-klyuchey-4ace7cfe
issue: kvant_2023_1
year: 2023
number: "1"
title: One hundred locks and one hundred keys
authors:
  - Дориченко С. А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 35
page_last: 37
page_labels: 33-35
tag: 1P4T
lang: en
source: kvant_digital
extraction: native
content_sha256: 91a19ac91803a158c721af7e0acfc2277f1f0b0d0035172c72b81be940791e06
prompt_sha256: draft-1
translated_from: content/ru/2023/01/articles/02_dorichenko-sto-zamkov-i-sto-klyuchey-4ace7cfe.md
source_content_sha256: 810c137855127851da17a22983feb748af085670f703bb281ceb8872bd2adad8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

"QUANTUM"

FOR

YOUNGER

One hundred locks and one hundred keys

S. DORICHENKO

To Sir Mycroft Holmes I apologize for this disturbing letter, but Sherlock Holmes is in a terrible state at the moment. The lack of things to occupy his mind had an extremely detrimental effect on his health. My friend absolutely needs a challenge. If the criminal world is no longer able to respond to such challenges, then perhaps some logical riddle worthy of this great mind will be salutary? With hope, Doctor Watson

To Dr. John Watson I am eternally grateful for your concern for my brother. Right now I am busy with a mathematical problem and have not yet been able to solve it. It is not entirely forensic, but Moriarty himself poses a challenge here. Perhaps this would interest Sherlock? I am attaching the conditions. Sincerely, Mycroft Holmes

***

- So, Watson, there are 100 identical-looking locks and 100 keys to them, piled up in a heap? – Yes, and exactly one key fits each lock. And you need to find out which lock is opened with which key. “Well, it’s not a pleasant task, but if you have some time and some patience, it’s not difficult to do.” Let's put the locks in a row and start checking the keys... - But in the worst case, this is 10,000 checks! Even if you spend four seconds on one check, that’s 40 thousand seconds – more than 11 hours! – It’s immediately obvious, my friend, that you weren’t taught mathematics well. Are you going to put every key in every lock? - Of course, you might not be lucky all the time.

SCHOOLCHILDREN

⟦column⟧

– But you only need to insert the first key 99 times: if it still doesn’t fit, then it’s from the last lock. - Perhaps. So there are only 9900 checks? - Past again. We will discard the found key-lock pair, and 98 checks will be enough for the second key. - It's true. And the third key will have to be checked no more than 97 times, and so on. It turns out a terrible amount: 99 98 ... 2 1 0. Strange, my hundredth key requires 0 checks? – Of course, his lock will be detected automatically. – What is this amount equal to? – According to legend, little Gauss figured it out almost instantly with the help of a little trick. He took two such sums and divided the terms into 100 pairs 99 0, 98 1, 97 2, ..., 0 99, each pair gives 99. This means that the original sum is $50 ^{99}$, which is 4950 checks. Four seconds per check - exactly five and a half hours. Now leave me - really, these trifles only worsen my condition. - But Holmes, in his diary, Moriarty claims to have found a way to distribute keys faster than 4950 checks, and with a guarantee! True, he did not explain it - they say, the method is so complicated that there is simply not enough space in the diary... - Oh, his passion for cheap effects. Faster than 4950 checks? Holmes fell into a long silence. Incredibly, after some time his face began to come to life, and a familiar sparkle appeared in his eyes. – Very interesting, Watson. Moriarty was a mathematics professor, but it seems he was wrong here. And I will prove it! - Will you prove it? How can this be proven? What if he had a cunning, unknown method... - Watson, are you familiar with mathematical proofs? Let me check on you. Do you agree that you first need to find at least one suitable lock-key pair? - Um... perhaps, yes, since it’s completely unclear how anything else can be done here -

⟦folio 34⟧

KVAN T 2023/№1

vat. Wait... But then everything is clear! If you're completely unlucky, you won't find the first pair faster than in 99 checks, the second - in 98... And here it is, our sum, this is the minimum! - We got caught right away. Why can’t you insert different keys into different locks, do a lot of such checks, and then suddenly understand at once about several keys and locks what goes with what? - This seems implausible... - Do you guarantee that it definitely won’t work out? - Really, I don’t know. “Then you don’t have proof yet.” - How can this be? - Let's try to reason in order. My intuition tells me that there is no algorithm that guarantees success in less than 4950 attempts. And this devil Moriarty claims that there is an algorithm. Well, let's say the professor is right. And we will drive him into a trap - mentally, of course. “But to do this, you have to offer him, even mentally, a set of keys and locks, so that he can’t handle it?” “That’s exactly what we’ll do.” Imagine, we gave him locks and keys. The professor takes some kind of key and inserts

⟦column⟧

goes into some lock... If he guessed right, we immediately change the inside of this lock with some other one so that the key does not fit. - We are gentlemen, not cheaters, and we will not... - Watson, we are only checking that the algorithm works in all cases. Therefore, such a substitution is quite legal - the locks are indistinguishable, and the professor could have come across a lock with a different interior. - What next? – He checks some next key-lock pair. And again, if necessary, we change the insides of the locks among themselves so that this key does not fit either - as long as all the previous checks do not change the result... - But you can’t do this ad infinitum, at some point the next key will definitely fit. - You're right. But wait! Why then check this key? - Sorry, Holmes, I didn’t understand. – Moriarty is not a fool. He has records of all the checks he has made. So far, not a single key has ever worked. And so he inserts key X into lock Y, and - horror of horrors - we can’t change anything

⟦folio 35⟧

"QUANTUM"

FOR

YOUNGER

places, without spoiling the previous results, so that the key does not fit. But then Moriarty himself will understand this! - But how, Holmes? – He can mentally go through all the possible matches of locks and keys. And since there is no match that preserves the results of previous checks, in which key X and lock Y do not fit together, it will detect this. – Why is there no such correspondence? “Otherwise we would have found him and made the result of the next test negative.” – A little tricky... – You shouldn’t doubt it, Watson. But if you want, then we’ll just tell the professor, like a gentleman, that he guessed right and doesn’t have to do this check. - But why, Holmes? – I feel this is important to prove! After all, now we have the right to assume that the professor’s algorithm is as follows: he does a lot of checks, the results are always negative, and at some point he suddenly understands about all the keys, which one belongs to which lock! – About all the keys? - Well, yes. Maybe first about one key or several at once. When everything becomes clear to him about some keys, he does not check them, but acts further according to his own algorithm, doing only those checks that can give a negative result. And we will ensure this negative result. Until he understands everything about all the keys. - And then? – What are your suggestions, my friend? - Not the slightest idea. - It seems that we are moving in the same direction... Then I have a request - for now, develop for the professor a convenient and compact way to record the results of his checks, and I will think a little more. Holmes leaned back in his chair and took a drag from his pipe. About half an hour passed when suddenly... - Eureka! Watson, everything is clear to me. How are you doing? – Like a doctor taking notes regularly

SCHOOLCHILDREN

⟦column⟧

about the condition of my patients, I thought that I could record all the checks in a row in a book. But if you save space, it’s probably better to number the keys and locks and draw a large $таблицу,^{100} u^{100}$ cells. And when checking, say, the pair “6th key, 75th lock,” put a plus in the 6th line in the 75th place if the key fits, and a minus if it doesn’t fit. - Bravo, Watson. This method is extremely convenient. Let me just remind you that Moriarty always puts minuses. He'll supply less than 4950 of them and suddenly he'll understand, right? – Yes, at the end of the algorithm’s work, it will simply highlight all the advantages. Sherlock Holmes winced. – These advantages, they can form a rather chaotic picture... It’s okay, we’ll put it in order now. After all, these 100 pluses are located one in each column and in each row. But notice, Watson - in our table you can rearrange the rows and columns, and nothing will be spoiled - if you rearrange the keys and locks accordingly, right? - Perhaps, yes. “Then we’ll find the plus in the first column and move the row with this plus to the very top, then we’ll find the plus in the second column and put the row with this plus right below the first row, and so on.” – Do you want the pluses to line up neatly diagonally? - Yes. This is not necessary, but it will make the solution especially clear. So, less than 4950 minuses are put in the table, after which the pluses are clearly lined up diagonally, no other options. But what is 4950? How many cells are there in the table? – We have a table of 100 and 100, a total of 10,000 cells. – How many cells are there on the diagonal? - Of course, 100. - This means that there are 9900 cells left for minuses, of which there are less than 4950 - less than half of the number of remaining cells! -What are you getting at, Holmes? – We need to divide the cells into pairs that are symmetrical relative to the diagonal! Here I am
