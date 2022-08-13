---
title: Week 12+13 Guide
...



# Goals

This week we arrive at the most famous and foundational open problem
in Computer Science (and, arguably, in all of Mathematics, and more
questionably, perhaps of all human creative endeavor): _is it
substantially easier to verify the solution to a (certain very broad
and common type of) problem, than it is to find that solution?_
(stated more formally in computer science as "P = NP?".

The main goals for Week 12 are to:

- Understand how to talk about the hardness ("difficulty") of computing functions.
- Learn about a few examples of problems that appear to have surprisingly different difficulties.
- Be able to talk about the _tractability_ of problems, and understand what computer scientists categorize problems as tractable and intractable the way we do.
- Understand precisely the definition of the complexity class NP, and two different ways of defining it.
- Understand the P=NP question and its significance.

# Reading

This week's content is covered in several chapters in the TCS
book. This is a lot of reading material, but you should consider it
all "optional" this week - you are not expected to read these in
detail, but should find the textbook a useful complement to the
lecture content to have an alternate presenation of the materials and
a refernce for some of the technical details that we do not cover in
depth in the lectures.

[Chapter 12: _Efficient computation: An informal introduction_](https://introtcs.org/public/lec_10_efficient_alg.html) [[PDF](https://files.boazbarak.org/introtcs/lec_10_efficient_alg.pdf)]

[Chapter 13: _Modeling running time_](https://introtcs.org/public/lec_11_running_time.html) [[PDF](https://files.boazbarak.org/introtcs/lec_11_running_time.pdf)]

[Chapter 14: _Polynomial-time reducations_](https://introtcs.org/public/lec_12_NP.html) [[PDF](https://files.boazbarak.org/introtcs/lec_12_NP.pdf)]

[Chapter 15: _NP, NP completeness, and the Cook-Levin Theorem_](https://introtcs.org/public/lec_13_Cook_Levin.html) [[PDF](https://files.boazbarak.org/introtcs/lec_13_Cook_Levin.pdf)]


# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the April 11 and April 13 lectures.

[PS11 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps11_blank.pdf)

[PS11 [ZIP]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps11.zip)

Note that this problem set does not have a programming portion.


## Submission Instructions


1. Download the [PS11 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps11.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps9.zip* you downloaded in step 1
1. Look in `ps10.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps11.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.

# Optional Videos

These videos mostly cover the same content as was presented in class. Be aware that in some cases the notation used may be different compared to the live-lecture. Also, previous semesters covered in one week what we will take two weeks to cover. Therefore, the videos below will also contain material that will not be covered until week 13 for us. It's unclear where the break from week 12 to week 13 will occur, so I've provided all videos below.



<p>"Difficulty" of Functions (9:13) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/PosxxVwgggI' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>RAM Model (7:00) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/tcjSV1QSdn8' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Shortest and Longest Path (11:16) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/g5Zpffr4Wog' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Satisfiability (14:45) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/cMEKwh614mk' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Tractable and Intractable Problems (6:38) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/SspCMbUF6Xs' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Polynomial Time Reductions (13:25) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/rDzdsvVqaDc' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Reducing 3SAT to LongestPath (16:54 total, with 9:30 of that optional [you may skip the proof from 3:35-13:05]) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/KgJnNZm8YuA' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Longest Path Decision Problem (4:11) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/CPqsKxjPFCo' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Nondeterministic TMs and the class NP (23:25) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/ot-H1BKK2ss' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Why do we care whether P=NP? (5:38) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/XSb4E8pJz2M' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>NP Completeness (15:51) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/2MqgnyhhCq8' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

