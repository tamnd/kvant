---
id: 1971-12-raskin-esche-raz-o-mashinnom-perevode-d94bba3f
issue: kvant_1971_12
year: 1971
number: "12"
title: Once again about machine translation
authors:
  - Раскин В. В.
rubric: osnovnye-stati
page_first: 13
page_last: 17
page_labels: 11, 12, 13, 15
tag: CX3N
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6dcd1b98f548ce3c9e540357b75bb912a80e0f3bbb51f1a99a9cee4dffe72896
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/03_raskin-esche-raz-o-mashinnom-perevode-d94bba3f.md
source_content_sha256: 58775ade445f3e1a2048656f0904d9079c115d578cfc5e185854d7868e433b8d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Once again about machine translation

We have already written about the difficulties that arise during machine translation *). As a result of their cunning efforts, the machine has, in general, been taught to cope with most of them.

However, there is also the goal of “placing” the city of more significant difficulties, which we discussed in this article. And they are all connected with the mysterious word “semantics”.

Semantics - the science of the meaning of words

The first semantic difficulty is that the same word can mean different things, and in different languages ​​in different ways: the different meanings assigned to words do not coincide. The Russian word “table” most often needs to be translated into English “table”, but sometimes it means “food” (“food”), and in turn the English “table” should sometimes be translated into the Russian word “table”.
In addition, in all languages ​​there are so-called homonyms - words that are spelled the same but have different meanings:
"Give me the bow!" - and for what - for shooting or for soup?
Further, in different languages, words are endowed with different emotional load and have different ability to be used in the enumerative sense. In Russian and in many other European languages, the word “heart” means, among other things, orran, which the popular consciousness considers to be the main thing and gives the ability to feel and experience.
But in the Kabalaka language (West Africa) this function is performed by the word “liver”; in the Jejonob language (a type of Mayan language in Guatemala) the word denoting the abdominal cavity is used in this sense. Imagine that

*) See «Kvant» No. 9, 1971

⟦folio 12⟧

the machine translates from the Kabbalah language into Russian and gives you the following phrase: “She has a good liver.”
Next trouble. In different languages, the “amounts of meaning” assigned to a given word are not the same. Let's take, for example, the concepts of “brother” and “sister” and compare them with the concepts of “elder and “junior”. We get the following table:

| Concept | Hungarian | Russian language | Malay |
| :--- | :--- | :--- | :--- |
| older brother | batya | bram | sudara |
| younger brother | occs | | |
| older sister | néne | sesstra | |
| younger sister | húg | | |

The Hungarian language expresses each of the four concepts with a separate word, the Russian language “cleans” them two at a time, and the Malay language covers all concepts with one word. It is easy to translate these words from Hungarian into Malay and generally in the direction of the word to the right according to the table. What if, on the contrary, you need to translate the words “sudara” from Malay into Hungarian? The human translator will look at the context here and try to figure out the gender and age of the person designated by this word, and then select the desired Hungarian equivalent. But how to teach this difficult operation to a machine?

Words that are seemingly “the same” for all languages, such as personal pronouns, can have “unusual” meanings that make translation difficult. You will see this now.

Task 1. In the Hanuno language (one of the languages ​​of the Philippines) there are the following pronouns (and only them):

dah - they tah - me and we
kuh - I tam - we (including me)
mih - we (without me) yah - he, she
muh - we yuh - you

By what criteria should these pronouns be classified according to their meaning? Russian pronouns are classified according to the following criteria: number (this feature has two meanings: singular and plural), gender (three meanings: masculine, feminine and neuter), pitso (three meanings).

The system of these features is not suitable for classifying the pronouns of the Hanuno language, since the given pronouns do not differ from each other (Russian “he” and “she” correspond to the same pronoun “yah”); As for person and number, in the Hanuno language more subtle differences are captured than in Russian (for example, together with one Russian pronoun, the first person plural has three).

In this case, it is possible to find more suitable features for classification that satisfy all the semantic differences of the given pronouns.

Given and e. Select such semantic features (and there should be a minimum number of them, and each with exactly two meanings) so that the given pronouns represent all possible combinations of meanings and so that no two combinations are repeated.

⟦folio 13⟧

But that's not all. Every language has stable phrases that do not mean exactly what, or even not at all, what the words that make them up mean separately. These are the so-called phraseological units: “beat the baklish,” “don’t think twice,” “play the fool,” etc.

Let's imagine that we have taught the machine to overcome all the difficulties described above. Let's take an English phrase:

«The President said that the article was red herring».
Happy, we are waiting for the translation. And we get:

“The President said that Stamya is a red herring.”
Hm... Got it? Not good. But ask any translator and they will instantly dispel your confusion, because the phrase actually translates like this:
“The President said that this story is a duck (lie, nonsense).”
Immediately everything fell into place. So, we add one more rule to the machine (how many of them are already written there?!): replace the phrase “red herring” with the word “duck” (or even better, since ducks are not only newspaper, but also fried - “lie” or “nonsense”). But there are a lot of phraseological turns, is it really possible to write for every word?
But a person who knows the language translates so easily and simply!

In order to overcome these and other semantic (and not only semantic) difficulties, in order to correctly select the equivalent word in the target language, that is, in order to perform a translation, the machine must remember the meaning of the words. One of the most prominent specialists in machine translation, American linguist V. Yngve writes:

“Machine translation work has encountered a semantic barrier. We had to realize that we will only get targeted automatic translation when the machine can “understand” what it is translating, and this is a really difficult task.”
And in order for the machine to understand what it is translating, the linguist must provide it with information about the meaning of words, give an accurate, formatted and clear semantic record, which the machine can handle in the same way as with a dictionary and processing rules. Machine translation of the present requires linguistics to record this. But...linguists are not yet able to cry on this score.

One of the interesting attempts to formally study semantic plurals. In this case, the approach is to highlight the so-called semantic plurals, that the meaning of each word is a combination of them (similar to how a natural number is decomposed into simple factors or a vector is specified by its coordinates). This idea is illustrated by the following problem.

Problem 2. Given 4 sets of words, each of which is divided into two subsets a and b:
1a) Beast, worms, ciliates, grass, posture;
b) table, ground, book, plane, coat.
2a) Whale, swallow, perch, tiger, ant;
b) wife, entry-level, hairdresser, husband, cashier.
3a) Sparrow, airplane, Baba Yaga, flour, rocket;
b) book, tunnel, already, well, telephone.
4a) Dog, horse, pigeon, donkey, mule;
b) bear, kangaroo, snake, tiger, perch.

⟦folio 15⟧

translator or editor." This definition is given in the book in order to show that machine translation in this sense does not exist at all. The text that the machine produces is so inconvenient and difficult to understand that it has to be subjected to “post-editing,” that is, subsequent editing by a person. 11% of the time during machine translation is spent on inputting material into the machine, 40% on recomposing output phrases, 31% on post-editing, and only 18% of the time remains on the translation itself. Assessing the quality of a translation (survey by an expert) according to the following parameters: accuracy of translation, speed of reading, ease of understanding, giving the following summary assessments (indicators for translation performed by a person are zero; the question of what all these “indicators” are based on and how the experts chose them, fortunately, has nothing to do with the matter):

| | Machine translation | Machine translation | Human translation |
| :--- | :--- | :--- | :--- |
| "raw" | "post-edited" | | |
| Accuracy | —16% | —5% | 0 |
| Speed | —21% | —11% | 0 |
| Understanding | —25% | —23% | 0 |

The main difficulty that reduces all three parameters is unnatural syntactic structures and word order in “raw” machine translation, as well as many translation options for one word. Now a little calculation. Let us denote by

$$\mathcal{U}_\text{ч} = \mathcal{U}_\text{м} - N \cdot P \left( B_\text{м} - B_\text{ч} \right).$$

The finished translation is intended for specialists who spend time reading it, and time is money (salary!), so the formula includes the value $P$. Let's calculate the values ​​of $\mathcal{E}$ and $N$ with average statistical data.

Due to the fact that the “raw” translation takes longer to read, we get an amazing pattern:

| $N$ | 1 | 10 | 15 | 17 | 18 | 20 | 80 | 175 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\mathcal{E}$ | 13,17 | 5,97 | 1,97 | 0,37 | —0,43 | —2,03 | —40,13 | —127,03 |
