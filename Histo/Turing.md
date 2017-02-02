# Turing

In 1935 Alan Turing formulated the underlying conception of what computation is while in the process of solving a problem in mathematical logic posed by D. Hilbert.

Leibniz had dreamed of human reason reduced to calculation and of
powerful mechanical engines to carry out calculations. Frege had
provided for the first time a system of rules that could plausibly
account for all of human deductive reasoning,. Gödel, in his doc
dissertation of 1930, had proved that Frege's rules were complete,
answering a question posed by D. Hilbert two years earlier. Hilbert
also sought explicit calculational procedures by means of which it
would always be possible to determine, given a judgment, whether
FRege's rules would enable that conclusion to be derived from those
premises.

the task of finding such procedures come to be known as Hilbert's Entscheinungsproblem
(lit *decision problem*). These procedures are algorithms.

In principle, an algorithm for his ents... would have reduced all human deductive reasoning to brute calculation.

It would have been a fulfillment of Leibniz's dream.

## Discovering what computing is

Turing knew that an algorithm is typically specified by a list of
rules that a person can follow in a precise mechanical manner, like a
recipe in a cookbook.  But he shifted his focus from the rules to what
the person actually did when carrying them out. He was able to show,
by a process of successively stripping away inessential details, that
such a person could be limited to a few extremely simple basic actions
without changing the final outcome of the computation. Turing's next
step was to see that the person could be replaced by a machine capable
of performing these same basic actions,. Then by proving that no
machine performing only those basic actions could determine whether a
given proposed conclusion follows from given premises using Frege's
rules, he was able to conclude that no algorithm for the
entsch.... exists. As a by-product he found a math model of an
all-purpose computing machine.

### Proceso de simplificación, depende dle tiempo

following Turing's thought processes, first center in the epoch,
literally a computer was a person, in particular a woman, why perform
something on a sheet of paper. She could be observed shifting her
attention from what she had written earlier to what she is writing
now, Turing wanted to remove all unimportant details, was she drinking
coffee? Not important. was she writing with a pencil or pen?? Not
relevant. Big or small paper? In fact Turing convinced himself that
while it might be a nuisance to deal with a complicated calc along a
one-dimensional tape, there was no fundamental problem in doing so.

Ex : 1043 x23 = 3129 + 20860 = 23989

Let continue, now restricted to a roll of paper tape. we watch as our
subject glances back and forth along the tape, writing symbols, some
times backing up and erasing symbols so new symbols can be written in
their place. Her decision about what to write next will depend not
only on which symbols she is paying attention to but also on her
current state of mind. Even in the case of our simple multiplication
example, as she notes pairs of digits, her states of mind will
determine whether she multiplies or adds them.

### Seguimos.

A persona carrying a computation in arith, algebra, calculus, or any
other branch of mathematics operates under the following constraints.

* At each stage of computation only a small number of symbols receive
  attention
* The action taken at each such stage depends only on the particular
  symbols receiving attention and on the current state of mind of the
  person carrying out the computation.

How many symbols can a person deal with simultaneously? And how many
are really needed?? As for the first question it surely depends on the
particular persona.

Regarding the second question, the answer is **one**!.

This is because the effect of paring attention to several symbols
simultaneously can always be obtained by paying attention to each of
them single, one at a time. The same for the movement thought the
tape.

This analysis leads to the conclusion that any computation can be
envisioned as proceeding in the following manner:
* Writing symbols in squares on a ruled paper tape.
* At each step the person performing the computation pays attention to
  the symbols written in exactly one of these squares
* Her next action will depend only on this symbol and her state of
  mind
* this next action will consist of writing a symbol on the square to
  which she has been paying attention and then possibly shifting her
  attention to the square immediately to the left or right.

and that is a Turing machine, anything computable by any algorithmic
process can be computed by a Turing machine. so if we can probe that
particular task cannot be accomplished by a Turing machine, we can
conclude that no algorithmic process can accomplish that task.

Turing also create what is called Turing Universal Machines....
