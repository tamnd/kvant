---
id: 1986-11-kaymin-postroenie-dialogovyih-algoritmov-75c24f3b
issue: kvant_1986_11
year: 1986
number: "11"
title: Construction of dialogue algorithms
authors:
  - Каймин В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 42
page_last: 50
page_labels: 40, 41, 42, 48
tag: 3UBX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1a7f9d713760db9095bc4ff13f2fa71089c331fd15f446048a5edac22d3f4df8
prompt_sha256: draft-1
translated_from: content/ru/1986/11/articles/15_kaymin-postroenie-dialogovyih-algoritmov-75c24f3b.md
source_content_sha256: 6af7a6b607da63621e3ce6b77fc9c97bcdb94fc23690430485bc8812293874bb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Construction of dialogue algorithms

Candidate of Technical Sciences
V. A. KAIMIN

This note is intended primarily for tenth-graders studying the course “Fundamentals of Information and Computing Technologies,” but it will also be useful to all those who deal with personal computers.

The dialogue between a person and a computer is in many ways similar to the dialogue between two persons. A dialogue between two persons is an exchange of messages, phrases, gestures and exclamations. The dialogue between people and computers is more like a conversation between people on the phone or, more precisely, on a video phone. Messages (information) from the computer are usually displayed on the TV screen connected to the computer. In response to computer messages, a person enters commands, answers or requests through a keyboard similar to that of a typewriter. In response to human actions, the computer displays new messages on the screen and waits for the input of new commands, data or requests.

Dialogue programs, depending on their purpose, can be divided into gaming, educational, business and instrumental. Game programs are used for entertainment in your free time from work or study. Curricula are used to teach schoolchildren or students. Business programs are used to solve production problems, accumulate and process information. Tool programs are used to create new programs.

Any dialogue program is based on certain rules and algorithms for conducting dialogue. Mandatory rules for conducting any dialogue are:

1. inform (“Good afternoon”
2. request("Your name", name)
3. output("2·2=", x, "?")

The “report” command specifies a standard phrase communicated to a dialogue partner; in the example above, this is the phrase “Good afternoon.” The “request” command contains two arguments: the first argument is the request phrase that is passed to the partner, and the second argument is the name of the variable where the response will be written (a phrase or a number, depending on the type of the variable). Commands of the “output” type can contain one or more arguments - these are either phrases or names of variables from which the message is drawn - “output”. We will add these three commands to the algorithmic language from the textbook. Let's give an example of constructing a dialogue algorithm. (To save space, part of the program title has been omitted here and below.)

Alg dating
beginning
« inform ("Good afternoon"
request("Your name =", name)
output (“Nice to meet you”, name!)
con

Example dialogue:

As the next example, consider a simple dialog algorithm for a guessing game. Two persons participate in the game: the first person guesses a certain integer x in the range from 1 to 100, and the second person tries to guess it by indicating the numbers: p₁, p₂,.... In response to the presentation of the number, the first person says:

⟦folio 41⟧

“excellent”, “little” or “many” depending on the correspondence between the specified and intended numbers. The games end with the words “well done”, “clever girl” immediately after the intended number has been worked out.

The algorithm for conducting a dialogue for the first person (it will be a computer) and an example of the dialogue are given below. The algorithm uses a special function “x := random (a, b)”, which produces some random integer between a and b.

alggra: guess
beginning
x: = random(1, 100)
sosbi (“guess the number”)
report (“from 1 to 100”)
request("number ==", p)
while p≠x
neither
if p<x,
then inform (“little”)
inchae inform (“a lot”)
All
request("number ==", p)
ki
sosbi (“excellent”)
sosbi (“well done, smart girl”)
con
Example dialogue (given x=67):

Guess the number
from 1 to 100
number = ? 50
few
number = ? 75
many

number=? 62
few
number=? 67
Great
well done, smart girl

The second person can select hypothesis numbers in many ways. The best method guarantees guessing numbers for a given range from 1 to 100 in 7 steps. This method is based on the principle of dividing the interval in half (see «Kvant» No. 10, p. 49).

The compilation of dialogue algorithms and the construction of dialogue programs for computers can be systematized (cf. «Kvant» No. 10, p. 47). An additional step in the systematic design of dialogue algorithms and programs is the preliminary compilation of a dialogue script.

A dialogue script is a description of the totality of all messages that are provided to a dialogue partner, and the system of reactions in response to his messages. For a unified description of a set of messages in an informatics, a specialized, but not complex, notation system is used. Let's consider it using the example of a description of the “game: guess” scenario.

Scenario "game: guess"

Here p is an integer

Here the variable element of the text (second person messages) is circled in red. The red frame contains a variable part of the text that describes the first person’s responses to the next hypothesis number. Answers are indicated in curly brackets on the right, which are selected depending on certain conditions (comparison of the mystery and the indicated numbers). The curly brackets of the trace indicate parts of the texts that are repeated (here these are repetitions of “request-answer” when guessing numbers).

Drawing up algorithms and programs with a preliminary description of the scenario allows you to think in advance about the clarity, logical coherence and tactfulness in the dialogue.

⟦folio 42⟧

ha, since this is a property not so much of the algorithm, but of the script. Moreover, the presence of a complete description of the scenario and descriptions of methods for solving the assigned problems allows us to systematically process the presence and absence of errors in the algorithms.

As an illustration, we present the construction of a dialogue algorithm for solving the problem of “throwing a ball into a basket,” which turns into a game of two people.

The first player holds the basket and tells the second player the distance to the basket. The second player selects the initial speed and angle of throwing the ball and reports this data to the first person. In response, the first player reports “hit”, or “undershoot” or “overshoot” with a value in meters.

Problem: Throwing a ball into a basket
Given:
L—distance to basket (m)
V₀ - initial speed (m/s)
α₀ — throwing angle (erad)
D – basket diameter (m)
Required: hit - sign of hit r - remaining distance (m)
Connection:
r = |L - l| (remaining distance)
hit = {r < D/2} (hit condition)
l = V₀ t (flight range)
0 = V₀ t - gt²/2 (hit condition)
V₀ = V₀ cos(α₀ π/180) (horizontal speed (t = 0))
V₀ = V₀ · sin(α₀ · π/180) (vertical speed (t = 0))
g = 9.81 (gravitational acceleration)

At
{D > 0 (positive basket width)
V₀ > 0 (velocity positivity)
0° < α₀ < 90° (angle tolerance)
Method
hit = ||L - l| < D/2 (hit condition)
r = |L - l| (remaining distance)
l = v₀² · sin(2α₀ · π/180)/g (flight range)
g = 9.81 (gravitational acceleration)

In the game scenario below, multiple games can be played. In each game, the first person sets the distance to the basket, fills the second person with data on the initial speed and angle of the throw, and reports the results. If the physical data is meaningless - negative or zero speed, or a negative or too large angle, then the first person reports “strange speed” or “incredible angle” and requests the data again.

Scenario "Ball game"

Below is an algorithm for conducting dialogue for the first player. This algorithm consists of three parts: the first part ensures unloading of the batch, the second part organizes a separate batch, the third part organizes mathematical calculations.

The second player's strategy can be built in many ways. The simplest of them is the “trial and error” method. However, the real strategy is to carry out mathematical calculations based on knowledge of physical laws that allow one to achieve victory in a given problem on the first try.

alg "throwing balls into a basket"
start lint game
thingsL, D
report (“throwing balls into a basket”)
D := random (0.1; 0.5)
output (basket diameter =>; D)
game:=yes
so far game:=yes
neither
L:=random (10; 250)
output("distance to basket=>; L)
throwing a ball into a basket
request (“shall we trample again? [yes/no]”, game)
kii
report (“thanks for playing”)
con

(For the ending, see page 48.)

⟦folio 48⟧

we get the answer: the required area is equal to $(7\sqrt{3}-\pi)/3$.

Of course, the six problems given above do not exhaust all types of problems on the coordinate plane that have been offered (in the last 10 years) at the entrance exams at MIPT. We tried to analyze the most unambiguous section - problems on tangents to graphs of functions - for the reason that quite recently a large article devoted to just such problems was published in «Kvant» (see «Kvant», 1986, No. 3, p. 51). So that readers have a more complete picture, we invite them to solve the following problem on their own:

1 (1984). Through the point $M$ (5; 6) a tangent to the parabola $y=6x^2/25$ is drawn, intersecting the abscissa axis at the point $N$, and the ordinate axis at the point $P$. Find the radius of the circle inscribed in triangle $NOP$ ($O$ is the origin).

2 (1979). Tangents are drawn to the parabola $y=\frac{1}{2}x^2+\frac{5}{2}$ at two of its points, intersecting at point $A$ and intersecting the x-axis at points $B$ and $C$. Triangle $ABC$ is equilateral, and its angle $ABC$ is equal to $2\pi/3$. Find the area of ​​this triangle.

3 (1978). On the coordinate plane, two straight lines $y=-x$ and $y=5x-6$ are given. Find: 1) the values ​​of $a$ and $b$ for which both given lines are tangent to the parabola $y=x^2+ax+b$; 2) coordinates of the touch points.

4 (1982). At points $A$ and $B$ parabolas $y=x^2-3x+1$ tangents are drawn, the angular coefficient of one of the tangents is equal to 1.

Construction of dialogue algorithms

(For the beginning, see p. 40.)

Alg. "throwing a ball into a basket"
apr. weight $L, D$
start lit hit
weight $v0, a0, l$
hit:=no
Got it so far:=no
beggar
query("throwing angle", $a0$)
request("initial speed", $v0$)
choice
at $v0\leqslant0$
hit:=no
output("strange speed")
at $a0\leqslant0$ or $a0\geqslant90$
hit:=no
output (“strange corner”)
inchete

hit calculation
choice
when hit:=yes
conclusion (“well done, got it”)
at $l<L$
output ("undershoot", $r$, "meters")
at $l>L$
output("flight", $r$, "meters")
All
All
kts
con
Alg. "hit calculation"
apr. weight $D, L, v0, a0$
cut: lit hit
weight $r$
start $g, l$
$g:=9,81$
$l:=(v0)^2\cdot\sin(2\cdot a0\cdot\pi/180)/g$
$r:=L-l$
if $r<D/2$
then I got it:=yes
hit the mark:=no
All
con
