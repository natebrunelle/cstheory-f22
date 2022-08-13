---
title: Week 1 Guide | The proof is in the pancakes
...



# Welcome to cs3102!

The main goals for the first week are:

- Set up the cohorts, and have each group get to know each other and
  figure out how you will work well together to ensure everyone in
  your cohort succeeds in the course and has a good experience
  learning with others.

- Re-awaking the mathematical thinking skills you have (hopefully)
  developed previously, and start applying them to problems in theory
  of computing.

- Understand the relationship between functions and cardinalities of sets, including infinite sets.


# Reading

The main textbook we will use is [Introduction to Theoretical Computer Science](https://introtcs.org/public/index.html) by Boaz
Barak. We will refer to this as the "TCS" book.

This is an open textbook, you can download the full PDF from
[https://files.boazbarak.org/introtcs/lnotes_book.pdf](https://files.boazbarak.org/introtcs/lnotes_book.pdf)
and contribute to the book by submitting Issues and Pull Requests at
[_https://github.com/boazbk/tcs_](https://github.com/boazbk/tcs). (See
the [Syllabus](/syllabus.html#grading) section on "Bonus Points" for a bit of
extra motivation for doing this, if just making the world better for
future generations of Theory of Computing students isn't enough
already.)

For Week 1, you should read these two chapters from the TCS book:

<blockquote>

[Chapter 0: Introduction](https://introtcs.org/public/lec_01_introduction.html) [[PDF](https://files.boazbarak.org/introtcs/lec_01_introduction.pdf)]  
[Chapter 1: Mathematical Background](https://introtcs.org/public/lec_00_1_math_background.html) [[PDF](https://files.boazbarak.org/introtcs/lec_00_1_math_background.pdf)] (you can skip 1.4.8 and 1.4.9 on _Asymptotics and Big-O Notation_ for now; we will go into more depth on this later in the course)  
</blockquote>


# Problem Set


These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). 

[PS0 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps0_blank.pdf)

# Writeup

This write-up
is due by **11:59pm** on Monday January 31.

Unlike with future weeks, this week your problem set is primarily intended to familiarize you with LaTeX[^future], a document-editing programming language.

This page will walk you through how to get started with Latex.

[^future]:To Quote Leslie Lamport (the creator LaTeX) "One of the hardest things about LaTeX is deciding how to pronounce it. This is also one of the few things I'm not going to tell you about LaTeX, since pronunciation is best determined by usage, not fiat. TeX is usually pronounced teck, making lah-teck, and lay-teck the logical choices; but language is not always logical, so lay-tecks is also possible."

## Register for Overleaf

Visit [https://www.overleaf.com](https://www.overleaf.com) and register for an Overleaf account (if you don’t already have one). UVA has a site license to Overleaf, so if you register with your @virginia.edu email address you will have full access to all the Overleaf features for free.

## Set Up Your Repository

Create your own copy of the ps0 repository by following these steps:

1. Download the [Week 1 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps0.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps0.zip* you downloaded in step 1

## Edit the File

1. Look in `ps0.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. If you get stuck, check out [overleaf's tutorials](https://overleaf.com/learn/latex/Tutorials).
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Then, try rebuilding the PDF by clicking *Recompile*. You should see many things disappear and other things reappear


## Download and Submit

1. Click on `PDF` in the left-hand size menu in overleaf
1. Click `recompile`, and make sure the pdf appears as you'd expected
1. Download the pdf to your machine, name it `ps0.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.



# Optional Videos 

If you missed the live first meeting on January 19, you can watch it here: [January 19 lecture video]().

## Previous Semester videos

In past semesters when courses were held online, we created a collection of videos for asynchronous instruction. In case those are helpful to you this semester, I'm identifying which ones will parallel content we're covering each week. Watching these videos is strictly optional. All content you're expected to know for this semester will be at least mentioned in class (and then reinforced in the readings). Anything mentioned exclusively in the pre-made videos is not required content for this semester.


You can play all the week 1 videos using the playlist:
[**Week 1 Playlist**](https://www.youtube.com/watch?v=CFsqeqP3V5w&list=PLZ9Gk_8DtbmHJyZ0O2v0K7gGRZN_hI14a)

### An Introduction to Problem Solving
<p>
Proofs and Pancakes (25:01)<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/CFsqeqP3V5w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

### Discrete Math Background

If there are discrete match concepts which you feel you might be rusty on, these videos are intended as a refresher. Feel free to skip if you're comfortable with these things.

#### High Level Overview

Professor Harry Porter Has a great video that briefly touches many of the topics from discrete math that you're expected to know for this course. You're definitely welcome to watch the whole thing, but I've identified what I think are the most important pieces:

- Sets: [0:00-3:21](https://youtu.be/TOsMcgIK95k)
- Functions and Relations [3:21-9:10](https://youtu.be/TOsMcgIK95k?t=201)
- Boolean Logic [26:10-31:18](https://youtu.be/TOsMcgIK95k?t=1570)
- First Order Logic [31:18-34:43](https://youtu.be/TOsMcgIK95k?t=1878)
- Proof Vocabulary [34:44-37:46](https://youtu.be/TOsMcgIK95k?t=2084)
- Overview of Proof Techniques [37:48-end](https://youtu.be/TOsMcgIK95k?t=2268)

#### Brief but Deeper

<p>
Sets (11:11)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/zjU7hE1oOW8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

<p>
Functions (09:06)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/4Q6ltygaeL4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

### Motivating The Math We'll Use

We just talked about a lot of math in the previous videos. In the next couple of videos we're discussing why we need to use that math, and how it's going to fit into a course about computing.


<p>
Why bother with infinity? (07:14)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/9ek-avkVhhs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


<p>
What do we compute on, exactly? (15:41)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/W-JdmJjLL5E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

## Natural Numbers

<p>
Natural Numbers (03:12)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/iQ84622B1Ig" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


## Induction

<p>
Induction (11:37)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/UXy7ZTGZHe0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>

## Countability


<p>
Countability (09:30)<br>
<iframe width="560" height="315" src="https://youtube.com/embed/dgwRtm8WGig" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
</p>


