---
title: Week 7 Guide
...

# Week 7: Automata and Regex

The main goals for Week 7 are to:

- Synthesize what we have learned about finite computation in the first 5 weeks, and start exploring unbounded computation.

- Appreciate the connection between functions and languages, and the different ways of talking about computation.

- Understand and be able to formally define a Finite State Automaton, and to reason about the language accepted (or function computed) by a Deterministic Finite Automaton.

- Be able to reason about the power of a DFA and understand deeply the proof that DFAs are strictly more powerful than Boolean circuits.

- Understand how to interpret Regular Expressions, define them formally, and reason about their capabilities.


# Reading

This week focuses on material in [Chapter 6: Functions with Infinite
domains, Automata, and Regular
expressions](https://introtcs.org/public/lec_05_infinite.html). Our
presentation in the videos differs from how things are presented in
the textbook (our way of defining a DFA is closer to the Alternate
Definition mentioned in Remark 6.3 than the way Definition 6.2 defines
a DFA; the book's presentation on regular expressions is similar to
ours, but not identical). Astute readers and viewers are encouraged to
look for places where the differences matter, or if they are only
cosmetic.

# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the March 14 and March 16 lectures.

[PS6 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps6_blank.pdf)

Note that this problem set does not have a programming portion.

## Submission Instructions


1. Download the [PS6 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps6.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps6.zip* you downloaded in step 1
1. Look in `ps6.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps6.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.

# Optional Videos

<p>Week 6 Intro (12:28) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/73FNVUv0CUA' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Warm-up: Questions about Strings (4:01) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/O5aonOdyxec' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Functions and Languages (11:16) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/VvdjLr5GNsg' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>



<p>Beyond Finite Functions (8:23) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/YMgUTfl1718' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Finite Automaton for XOR (6:28) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Us4zrlmIOaY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Formalizing Finite State Automata (3:29) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/kgTxZlRPGqw' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Power of Deterministic Finite Automata (8:15) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/FMi_pZp6NrY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Regular Expressions (17:27) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/LE9Jns4DUnU' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Optional Bonus Video: The Lasagna Language (7:00) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/xeKX-WsINbw' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>



