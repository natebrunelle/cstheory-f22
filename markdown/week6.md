---
title: Week 6 Guide 
...

# Week 6: EVAL and Complexity

This week, our main goals are:
- Implement and use the EVAL function. This is our first exposure to a modul of computing which is able to simulate an instance of itself. This idea is fundamental to the practice of computer science, as it enables us to have arbitrarily reprogrammable machines which run with fixed hardware.
- Begin classifying functions by complexity (i.e. resources required to implement them).
- Learn the asymptotic operators (Big-<em>O</em>, &Omega;, and &Theta;) and how to use them correctly.
- Be able to both intuitively understand what functions are in <em>O</em>(<em>f(<em>n</em>)</em>), and to prove membership or non-membership.

# Reading

- [Ch. 5, Code as data, data as code](https://introtcs.org/public/lec_04_code_and_data.html) from the TOC textbook. In particular, we cover sections 5.1 through 5.5. We are skipping the optional section 5.2.1.
- The TCS book does not provide a detailed presentation of the
asymptotic operators, but reviews them in [Section
1.4.8](https://introtcs.org/public/lec_00_1_math_background.html#secbigohnotation). Many
books provide more detailed presentations of these concepts, and lots
of examples. If you would like a more complex textbook explanation,
the course instructors (at least one of them!) recommends this
chapter: [Chapter 7: Cost](https://computingbook.org/Cost.pdf) (from [_Introduction to Computing
Explorations in Language, Logic, and Machines_](https://computingbook.org/)).

# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the February 28 and March 2 lectures.

[PS5 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps5_blank.pdf)

Note that this problem set additionally has a [programming problem](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/eval.py).


## Submission Instructions

### For the PDF

1. Download the [PS5 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps5.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps5.zip* you downloaded in step 1
1. Look in `ps5.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps5.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.

### For the Python Program

1. Download that [adders.py](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/eval.py) file.
1. Implement the bodies of all functions marked with `TODO`. Do not modify any code except for the bodies of those functions (you should change their return statements but not their signatures).
1. Run the code, if it says you passed all the tests (and you followed the instructions) then you can expect full credit for this question! If something was not quite correct then it will tell you the first input it found where it gave the wrong answer.
1. Upload your completed python file to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit. Note that this is listed as a separate assignment from the written (both together will count as your grade for PS5)


# Videos

## March 2 Lecture Videos

Professor Brunelle must be out of town for a conference, and as such there is no in-person lecture for Wednesday March 2. Instead, Please watch the following instructional videos (recorded for Spring 2021).

<p>Introducing Complexity (5:37)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/HOgP-99MFoU' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Introducing SIZE (5:59)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/SfS3nl9O190' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Our First Complexity Proof (11:38)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/SSXy7BbuZGM' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Asymptotic Operators (7:06)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/96XtkxDNDCs' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Understanding Asymptotics (10:40)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/KA8uSlGqc_o' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Big-Oh Examples (17:04)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/iG_BGStzPQE' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Common Misuses of Asymptotic Notation (5:52)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/WLV99-6ep2c' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Some Functions Are Expensive (7:36)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/BavLtSyKlFg' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>Cost of Computing (5:03)<br>
<iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/5H6DvmEzwDY' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


## Optional Videos

The videos below match with content covered on Monday February 28, and therefore should be consider optional.


<p>Introducing EVAL<br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/HTHYjpgyWNY' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br></p>

<p>Representing Programs<br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/RNN-hW9x_8Y' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br></p>



<p>Defining EVAL<br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/5RbgIcs0bEw' frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br></p>

