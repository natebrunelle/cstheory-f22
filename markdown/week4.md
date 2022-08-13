---
title: Week 4 Guide 
...

# Week 4: Circuits

This week, our main goals are:

- Show how simple models of computing can result in complex behavior.
- Begin building a bridge from theoretical models of computing (like straightline programs and boolean circuits) to practical implementations of computing (like Python and integrated circuits).
- Explore the powers and limitations of a model of computing, including being able to understand the details of how to use that model, and why it is defined in the way chosen.
- Learn how to compare models of computing to one another


# Reading

Material in this week's lectures parallels with:
 
- [Ch. 3, Defining Computation](https://introtcs.org/public/lec_03_computation.html) of the TOC textbook. We discussed this last week as well, we're looking at this chapter in more detail this week
- [Ch. 4, Syntactic sugar and computing every function](https://introtcs.org/public/lec_03a_computing_every_function.html) from the TOC textbook. In particular, we cover sections 4.1 through 4.3.

# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the February 14 and February 16 lectures.

[PS3 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps3_blank.pdf)

Note that this problem set additionally has a [programming problem](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/straightline.py).


## Submission Instructions

### For the PDF

1. Download the [PS3 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps3.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps2.zip* you downloaded in step 1
1. Look in `ps2.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps3.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.

### For the Python Program

1. Download that [straightline.py](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/straightline.py) file.
1. Implement the bodies of all functions marked with `TODO`. Do not modify any code except for the bodies of those functions (you should change their return statements but not their signatures).
1. Run the code, if it says you passed all the tests (and you followed the instructions) then you can expect full credit for this question! If something was not quite correct then it will tell you the first input it found where it gave the wrong answer.
1. Upload your completed python file to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit. Note that this is listed as a separate assignment from the written (both together will count as your grade for PS3)


# Optional Videos

These are relevant videos from previous semesters. You may find them helpful, but you are not require or expected to watch them. Please be aware that the Spring 2021 semester was much shorter than the Spring 2022 semester, giving us the ability to move a bit slower and cover more depth this semester.
<p>
The Story So Far (02:54)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/LA-CooHwl4w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


**This video introduces graphs, including their definition, notation, and vocabulary. If you feel comfortable with graphs already, I encourage you to skip this video.**
<p>
Introduction to Graphs (15:43)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/bUyWLT5MKEw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


<p>
Components of a Computing Model (1:58)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/EmcUU6jJ6sA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Representing Circuits (14:42)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/JxkfGPglKnk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Circuit Execution (12:41)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/9BoHFu6STIE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Syntactic Sugar (9:13)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/kvEb068OvCw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>
