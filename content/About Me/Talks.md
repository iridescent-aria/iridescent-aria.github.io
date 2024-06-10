---
title: Talks
---
# Mario is Hard - Jan '24

This talk was given in the [CMI student seminar series](https://sites.google.com/view/cmistudentseminars/home) as an introduction to reductions and NP-hardness targeted at first year undergraduates. The talk introduced the basic ideas with some examples, then described the result in [this](https://arxiv.org/pdf/1203.1895) paper by Aloupis, Demaine, Guo, and Viglietta that deciding whether a (suitably generalized) Mario level is winnable is NP-hard. See the slides for the talk [[mario-reductions-website.pdf|here]].

# Two-Way Timed Automata - Nov '23

This talk was given as the final examination for a course on timed automata. The talk summarized the results of [this](https://www.cis.upenn.edu/~alur/Focs92.html) paper by Alur and Henzinger on two-way timed automata. Briefly, two-way timed automata can be thought of as machines which treat their input timed words as a timed _log_, going back and forth across the input instead of reading letters one by one. In particular, clocks no longer _elapse_ time, but rather function as devices which store timestamps of letters.

The main two themes of the paper are as follows. First, that two-way timed automata are very intractable in general, but bounding the number of passes that a deterministic two-way timed automaton can make over the word leads to a well-behaved class of languages. Second, the paper presents a temporal logic which is connected with two-way deterministic timed automata.

The slides for the talk are available [[2tas-talk-website.pdf|here]].

# Decipher Title Via Googling Cantor, Halting, Computability, Cardinality - Aug '23

This talk was given in the [CMI student seminar series](https://sites.google.com/view/cmistudentseminars/home) as a survey of some of the famous diagonalization arguments in mathematics and computer science, culminating in a sketch of the proof of Gödel's first incompleteness theorem (as in supplementary lecture K in Dexter Kozen's _Automata and Computability_). As a broader theme, the talk also looked at self-reference and how things can go horribly wrong once systems get the ability to talk about themselves.

This was a blackboard talk.

As an aside, the reason that the title is so long-winded is that if one takes the $k^{\text{th}}$ letter of the $k^{\text{th}}$ word in the title, and arranges them in order, the word spelt out is 'diagonal'! In other words, writing the words one below the other, and circling the diagonal, spells out the word 'diagonal'!
