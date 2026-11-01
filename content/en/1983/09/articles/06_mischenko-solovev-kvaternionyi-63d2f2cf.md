---
id: 1983-9-mischenko-solovev-kvaternionyi-63d2f2cf
issue: kvant_1983_9
year: 1983
number: "9"
title: Quaternions
authors:
  - Мищенко А. С.
  - Соловьёв Ю. П.
rubric: osnovnye-stati
page_first: 12
page_last: 17
page_labels: 10, 12, 15
tag: "53E6"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5cfe6de111158fd7d393654f04b5490ae2c11b7a9189e2e23d6f95b97e010b4f
prompt_sha256: draft-1
translated_from: content/ru/1983/09/articles/06_mischenko-solovev-kvaternionyi-63d2f2cf.md
source_content_sha256: 28ccf4314866eef9ef628861bd22c24f72e413467cff2592728804f25a9796ca
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

Quaternions

Doctor of Physical and Mathematical Sciences
A. S. MISHENKO,
Candidate of Physical and Mathematical Sciences
Y. P. SOLOVIEV

From the editor. INTRODUCTION TO THE YEAR “Quait”
talked a lot about numbers. About complex numbers (No. 2, p. 16), about their history (No. 6, p. 10), about the representation of real numbers in the form of whole fractions (No. 5, p. 16 and No. 6, p. 26), about algebraic and transcendental numbers (No. 7, p. 2).
This series ends with the article published below (which, however, does not require familiarity with the previous ones). It deals with quaternions - numbers containing complex, and therefore all other, numbers. You will learn a little about the applications of quaternions and about the free history of their creation, the starting point of which was the desire to introduce algebraic structure (addition and, most importantly, multiplication) into geometric objects (various sets of points).

How to make numbers from dots?

If we are talking about points on a line, it’s simple. By selecting the beginning of the report (“zero”) and the scale with the direction (“unit”), you can obtain a numerical axis from a straight line and thereby turn each point into a real number—its coordinate (Fig. 1).

With points on a plane it is more difficult. By selecting the beginning of the report (“zero”) and a pair of perpendicular axes, you can associate each point on the plane with a pair of its coordinates (x; y). In order to make each such pair - a doublet - a number, you need to learn how to “add” and “multiply” these doublets, and in such a way that the grafting properties of addition and multiplication are preserved (commutative, associative and distributed laws, the presence of inverse operations - division and subtraction).

So addition is simple. It is natural to add doublets as vectors -

⟦folio 12⟧

The vector product $v_3 = v_1 \times v_2$ of non-zero vectors $v_1, v_2$ is a vector perpendicular to the plane passing through the vectors $v_1, v_2$, having a direction determined by the rule of the right hand” (Fig. 3), and a length $|v_1| \cdot |v_2|$.

$\sin(v_1, v_2)$. For further note that if the vectors $v_1, v_2$ are given properties by coordinates in a rectangular coordinate system:

$$v_1 = (\alpha_1; \beta_1; \gamma_1)$$
$$v_2 = (\alpha_2; \beta_2; \gamma_2),$$

That
$$v_1 \times v_2 = (\beta_1 \gamma_2 - \beta_2 \gamma_1; \gamma_1 \alpha_2 - \gamma_2 \alpha_1; \alpha_1 \beta_2 - \alpha_2 \beta_1).$$

(4)

The vector product operation was not suitable for Hamilton, since it does not have an inverse. For example, if $v_1 = v_2 \neq 0$, then the angle $(v_1, v_2)$ between these vectors is zero. This means that the length of the vector product $v_3 = v_1 \times v_2$ is equal to zero, that is, the vector $v_3$ itself is zero. If the operation of division by a nonzero vector always existed, then we have $(v_1 \times v_2):v_2 = v_1 \neq 0$, while $v_1 \times v_2 = 0$ and therefore $(v_1 \times v_2):v_2 \neq 0$. The resulting contradiction shows that division by $v_2$ is impossible.

It cannot but arouse respect and admiration that, despite disappointment and failures, Hamilton did not give up hope and for ten years, with guilty persistence, has been trying to solve the task set for himself. And although the problem was never solved (and could not be solved - we will explain why later), ten years of work was not in vain. One fine day in 1843, Hamilton suddenly decided to use not triplets (triplets of numbers), but fours, or, as he immediately dubbed them, quaternines, to determine multiplication. Here's how it will happen.

Incident at Brogem Place

In one of the letters to his son, written in the somewhat stilted style characteristic of that time, Hamilton recalled: “It was the 16th day of October, which was Monday, the day of the meeting of the Council of the Royal Irish Academy, where I was to preside. I was heading there with your mother along the Royal Canal; and, although she spoke to me in separate phrases, I almost did not perceive them, since something was happening latently in my mind. Suddenly, the electrical circuit seemed to close; a spark sparkled that preceded many long years of determining directed thought and work, mine - if it happens, or the work of others, if I am given enough conscious life to report my discovery. I was unable to resist the desire to carve with a knife on the soft stone of the Brohemian place the fundamental formula about the symbols $i, j, k$,

$$i^2 = j^2 = k^2 = ijk = -1,$$

containing a solution to the problem, but, of course, this entry has since been erased. However, a more lasting mention remained in the Book of Records of the Academy Council for that day, where it is stated that I asked and received permission to report on quaternines at the first meeting of the session, which was read accordingly on Monday the 13th of the following month - November.

Definition of quaternions

Quaternions are quadruples of real numbers $(x; y; u; v)$, which can be conveniently written as

$$q = x + yi + uj + vk,$$

⟦folio 15⟧

When multiplying quaternions, the situation is more complicated. If $q_1$ and $q_2$ are scalar quaternions, then their product $q_1 q_2$ is also a scalar quaternion. In the case where $q_1 = x$ is a scalar quaternion and $q_2 = r$ is a vector quaternion, the product $q_1 q_2 = x \cdot (y_i + uj + vk) = (xy)i + (xu)j + (xv)k$ is a vector quaternion and the multiplication operation coincides with the multiplication of the vector $r$ in space by the real number $x$.

And finally, if both quaternions are vector:

$$q_1 = r_1 = y_1 i + u_1 j + vk$$
$$q_2 = r_2 = y_2 i + u_2 j + v_2 k,$$

That

$$q_1 q_2 = -(y_1 y_2 + u_1 u_2 + v_1 v_2) + (u_1 v_2 - v_1 u_2) i + (v_1 y_2 - y_1 v_2) j + (y_1 u_2 - u_1 y_2) k.$$

As can be seen from the last formula, the scalar part of the product $q_1 q_2$ is equal to the scalar product $(r_1, r_2)$ of the vectors $r_1$ and $r_2$ with the opposite sign. The vector part $q_1 q_2$ is our old friend - the vector product $r_1 \times r_2$, written in coordinates (see (4)).

Combining all the considered cases, we obtain a general formula for multiplying quaternions. If $q_1 = x_1 + r_1$ and $q_2 = x_2 + r_2$, then

$$q_1 q_2 = (x_1 x_2 - r_1 \cdot r_2) + (x_1 r_2 + x_2 r_1 + r_1 \times r_2)$$

What about triplets?

Why didn't Hamilton manage to find a satisfactory way to multiply triplets? Not because of insufficient construction or hard work - we have already noted above that the problem of constructing “three-dimensional numbers” cannot be solved. Indeed, it has been proven that there is no process for multiplying points in space that satisfies our requirements (associativity, distributivity with respect to coordinate-wise addition, the possibility of division into non-zero elements). Moreover, all cases are now known when such multiplication can be carried out.

As the German mathematician F. G. Frobenus (1849-1917) proved, there are three of these cases: in dimension one (regular real numbers), in dimension two (complex numbers) and in “dimension four” (quaternions).

What happened next

Hamilton and his subsequent reliance on quaternions. Quaternions were expected to produce the same results as complex numbers, and even better. Indeed, with the help of quaternion calculus, formulas that were perfect in their mathematical beauty were discovered, describing a number of important physical phenomena. But further hopes for the development of algebraic and functional quaternion calculus did not materialize.

For quaternions, the main theorem of algebra about the existence of roots of a polynomial with quaternion coefficients does not hold, but, on the other hand, there is a polynomial with quaternion coefficients in one variable for which any quaternion is a root.

Optimism gave way to skepticism. At the beginning of this century, mathematicians ceased to be interested in quaternions. But time passed, and physicists persistently searched for mathematical formulas for some effects associated with the so-called spin of elementary particles. Quaternions regained recognition when their role in constructing various geometric transformations of space used in quantum physics was understood. The geometric properties of quaternions is a special big topic that we hope to talk about in the future.
