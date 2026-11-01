---
id: 1984-7-rudnev-marki-posvyaschennyie-d-i-mendeleevu-0f8c55e7
issue: kvant_1984_7
year: 1984
number: "7"
title: Stamps dedicated to D. I. Mendeleev
authors:
  - Рудов В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 10
page_last: 15
page_labels: 8, 13
tag: MATO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 90eea8bda04a02211c144e8074d02db774802d6582ec4088c58f55ea09379fc5
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/04_rudnev-marki-posvyaschennyie-d-i-mendeleevu-0f8c55e7.md
source_content_sha256: 7ced247b473b4fa83ac9a7e829d50893233106485b677e8f1cb04d409bca83eb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

ly due to the spontaneous fission of heavy nuclei. However, there are theoretical proposals that the nuclei of elements with charges 114 and 126 may turn out to be quite stable, so perhaps we will see

Collector's Corner

Stamps dedicated to
D. I. Mendeleev

The Soviet branch repeatedly dedicated various postage signs to the outstanding Russian scientist Dmitry Ivanovich Mendeleev. The first four stamps were issued in 1934, on the centenary of the birth of D. I. Mendeleev. One of them depicts a monument to the great scientist, erected in 1932 in Leningrad. This brand is included in our selection.

In August 1951, a series of sixteen stamps was issued dedicated to outstanding Russian scientists. Middle we see a blue stamp with a portrait of D.I. Mendeleev. The next stamp with his portrait against the backdrop of the Leningrad University building was issued in 1957 on the fifth tenth anniversary of the scientist’s death. In 1969, on the centenary of the periodic system, a new stamp was issued with a portrait of Mendeleev and a postal block with a facsimile of one of the first variants of the periodic system.

Our selection also includes a stamp of the Polish People's Republic dedicated to D. I. Mendeleev.

V. Rudov

8

⟦folio 13⟧

chess position and then, in part, answer the question whether White will win in it.

You've probably already agreed why this hasn't been done yet. The described construction is possible only from the point of view of mathematical abstraction. It is impossible to actually perform it due to the huge number of all chess positions. It has been proven that there is an optimal move in every position. However, there is no known short way (for example, a formula) to find it.

But is it not possible to practically do this, of course, not for all positions, but only for a part - for example, for some endgames?

Small-piece endgames

Using the reverse wave method, the author was able to teach a computer to play in the endgame “king, queen and pawn against king and queen” (KFP-KF), provided that the white pawn is on the g7 square and “king, rook and pawn against king and rook” (KLP-KR) *) with any position of the pawn. This endgame machine not only plays better than a human, but makes the optimal move in every position. Thus, low-figure endgames can be analyzed accurately on a computer.

However, such an analysis is not at all easy to implement, because its complexity is somewhere at the limit of the capabilities of modern computers. Thus, in the KLP-KL endgame it is necessary to consider about a billion positions. And if to record each position

*) The last work was done by a large team under the leadership of V.L. Arlazarov.

spend only a few “bits” (characters 0 or 1 in machine memory), then many positions will take up only the machine’s memory (both “RAM” and “external”). Therefore, for machine analysis of small-figure endgames in modern applications, a number of special techniques are aimed at the economical use of computer resources. We will only briefly focus on one of these techniques (decomposition), using the example of the KLP-KL endgame.

Let us remember that the task of the machine is to rank the graph Δ of all positions, the occurrence of errors when unloading the endgame KLP-KL. Of course, the number of positions in Δ is greater than the number of positions KLP-KL (for example, the exchange of rooks takes us to the endgame KP-K, the movers in queens gives KFL-KL, etc.), but this number is significantly less than the positions in column Γ of the entire chess game. Moreover, the graph Δ itself can be partitioned into parts (this partition is shown in figure 4). The essence of the decomposition method is to rank these parts separately. This technique achieves the goal because the connections between the parts are not too complex: in part, they do not form oriented cycles *) (see Fig. 4). Such a graph is called acyclic.

Problem 2. Prove that the vertices of an acyclic graph can be numbered in such a way that any arc leads from a vertex with a higher number to a vertex with a lower number.

So, the study of the graph Δ was reduced to the study of a series of endgames; however, some are still great.

*) This means that you cannot leave any vertex and, moving in the direction of the arrows, return to it.

Scheme of endgames, errors arising from positions such as KLP-KL when the state of the pieces changes (by capturing or promoting a pawn). For convenience, some endgames have been omitted that do not affect the study of the main endgame KLP-KL.
