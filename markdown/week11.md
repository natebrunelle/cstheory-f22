---
title: Week 11 Guide
...

# Goals

This week, we hope you'll become experts at proving functions are
uncomputable (and occasionally, computable). We reinforce the "proof
by reduction" technique, which is a tremendously useful way to prove
properties about problems, and (as you will see in the Algorithms
class) also to develop and analyze algorithmic solutions.

The main goals for Week 11 are to:

- Become more comfortable with proofs by reduction, and awareness the common pitfalls in constructing reduction proofs.
- Learn about Rice's Theorem to help develop more intuition for what is uncomputable.
- Develop a more precise understanding of Turing Machine running time, and how changing details of the specific Turing machine model used can change how efficiently different functions can be implemented.

# Reading

[Chapter 9: _Universality and uncomputability_](https://introtcs.org/public/lec_08_uncomputability.html) [[PDF](https://files.boazbarak.org/introtcs/lec_08_uncomputability.pdf)]

You should have already read through the Section 9.3 (but reread any parts you are confused on), and read the new Sections 9.4 and 9.5 for this week.


# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the April 11 and April 13 lectures.

[PS10 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps10_blank.pdf)

[PS10 [ZIP]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps10.zip)

Note that this problem set does not have a programming portion.


## Submission Instructions


1. Download the [PS10 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps10.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps9.zip* you downloaded in step 1
1. Look in `ps10.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps9.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.


# Optional Videos

These videos mostly cover the same content as was presented in class. Be aware that in some cases the notation used may be different compared to the live-lecture.


<p>Intro (3:58) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/hP9TjCs5vqI' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Decidable, Recognizable, Computable (7:18) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/ZjQHbxCExsg' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>
<p>An Undecidable Problem (8:10) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Bit7FvUzcMU' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>



<p>Proof by Reduction (17:54) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/tEp6j_owBSs' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>HALTS is Undecidable (7:19) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/UObqrnIHHbI' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>
<p>Finite is Undecidable (11:38) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/C4CZoVxJT9o' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>
<p>Prints3 and IsMalware Are Undecidable (5:15) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/5VKf11so0XE' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Rice's Theorem (15:28) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/U1aEDWBNQ3A' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


