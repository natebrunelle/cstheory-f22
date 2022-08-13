---
title: Week 5 Guide 
...

# Week 5: Syntactic Sugar and Universality

This week, our main goals are:

- Show how simple models of computing can result in complex behavior.
- Begin building a bridge from theoretical models of computing (like straightline programs and boolean circuits) to practical implementations of computing (like Python and integrated circuits).
- Explore the powers and limitations of a model of computing, including being able to understand the details of how to use that model, and why it is defined in the way chosen.


# Reading

Material in this week's lectures parallels with:
 
- [Ch. 3, Defining Computation](https://introtcs.org/public/lec_03_computation.html) of the TOC textbook. We discussed this last week as well, we're looking at this chapter in more detail this week
- [Ch. 4, Syntactic sugar and computing every function](https://introtcs.org/public/lec_03a_computing_every_function.html) from the TOC textbook. In particular, we cover sections 4.1 through 4.3.


# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the February 21 and February 23 lectures.

[PS4 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps4_blank.pdf)

Note that this problem set additionally has a [programming problem](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/adders.py).


## Submission Instructions

### For the PDF

1. Download the [PS4 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps4.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps4.zip* you downloaded in step 1
1. Look in `ps4.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps4.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.

### For the Python Program

1. Download that [adders.py](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/adders.py) file.
1. Implement the bodies of all functions marked with `TODO`. Do not modify any code except for the bodies of those functions (you should change their return statements but not their signatures).
1. Run the code, if it says you passed all the tests (and you followed the instructions) then you can expect full credit for this question! If something was not quite correct then it will tell you the first input it found where it gave the wrong answer.
1. Upload your completed python file to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit. Note that this is listed as a separate assignment from the written (both together will count as your grade for PS4)


# Optional Videos

These are relevant videos from previous semesters. You may find them helpful, but you are not require or expected to watch them. Please be aware that the Spring 2021 semester was much shorter than the Spring 2022 semester, giving us the ability to move a bit slower and cover more depth this semester.


<p>
Syntactic Sugar (9:13)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/kvEb068OvCw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
De-Sugaring (11:40)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/1cTaMbAA8aU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Constructing Conditionals (10:37)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/DYeaX2lmNPI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Lengthening Lookup (12:14)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/d2U25VuOqkw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Cost of LOOKUP (3:33)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/ZRFK2_Ll9b0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


<p>Week 4 Intro<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/zDp_h_yLm1A' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Computing Any Finite Function<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/vE-N_ErO7W0' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Making Zero and One<br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/v3mw1sHrZbo' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br></p>

<p>How Many Gates?<br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/WPllMBJC0q0' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br></p>

