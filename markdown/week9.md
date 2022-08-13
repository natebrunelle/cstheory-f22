---
title: Week 9 Guide | Not Yet Available.
...

# Goals

This week, we introduce the most important and widely used model of
computation, the Turing machine, and start to address the big question
of what can and cannot be computed by any machine with a finite
description.

The main goals for Week 9 are to:

- Understand what cannot be computed by a finite automaton and why.
- Use and understand Turing Machines as a model of computing.
- Study a definition of computability.
- Explore the powers and limitations of Turing Machines.
- Learn different variations on Turing Machines and how they can be transformed.

# Reading

This week we discuss the material contained in [Chapter 7: Loops and Infinity](https://introtcs.org/public/lec_06_loops.html).

Turing Machines and other similar models of computing are taught in
many different ways in many different places. In addition to the
course materials, you'll find plenty of other presentations of this
material available on youtube, other textbooks, lecture slides from
other universities, blog posts, etc. Please be advised that there are
many subtly different presentations of Turing machines, and so what
you see elsewhere may differ from what we covered, but the key ideas
are universal and should be the same in any good
presentation. Typically minor changes are made to the model either for
convenience of the context, or so real-world running times are more
similar to the running time of the model (more on this in future
weeks).

You can read Turing's paper here: Alan M. Turing, [_On Computable Numbers, with an Application to the
Entscheidungsproblem_](/files/computablenumbers.pdf). 1936.


# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the March 28 and March 30 lectures.

[PS8 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps8_blank.pdf)

[PS8 [ZIP]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps8.pdf)

Note that this problem set does not have a programming portion.

## Submission Instructions


1. Download the [PS8 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps8.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps8.zip* you downloaded in step 1
1. Look in `ps8.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps8.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.


# Optional Videos


<p>Applications of Finite State Automata (6:27) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/fPAxt4LvEaU' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Warm-Up: Life on Mars (2:16) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/zpKVDZB7JiE' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Limitations of Finite Automata (6:40) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/KmAJEKRZaGY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Turing Machines (5:37) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Xx_GeourSOQ' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Turing Machine Example (17:59) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/6S6suD3aRxY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Turing Machine Definition (8:31) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/qH6Ffc9H2js' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>
