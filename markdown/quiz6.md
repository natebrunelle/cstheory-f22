---
title: Quiz 6 | P vs NP and Uncomputability
...

Currently, the deadline for this quiz (and all quiz re-takes) is set to 5:00pm on Friday December 9. This does not mean that you must submit this quiz in advance of that deadline. Instead, you may request any new deadline you would like between the default deadline and 5pm on December 16 (this is the end time of the university's official final exam time for the course, so by policy I cannot allow you to submit any later than that).

Be advised that once your deadline has passed and you have submitted something, you will not be able to select a new deadline for that quiz. You will be able to request a new quiz deadline for any quiz you have not yet submitted (regardless of whether the deadline has already passed). Prof. Brunelle will be processing extensions each morning beginning November 30, so if you submit in the afternoon then you may not see the deadline change that day. You can assume any extension requested for a deadline before 5pm on December 16 will be granted.

# Topics Covered


This quiz contains 3 questions:

1. One requiring using Rice's Theorem, or else identifying that it cannot be used.
1. One requiring you to use the definitions of various complexity classes we've discussed and reason about how reductions among problems belonging to these class can/cannot be used to resolve the question of whether P=NP.
1. One requiring you to show a problem is NP-Hard via proof by reduction.

Similar problems to these were seen in problem sets 9 and 10.

To help you prepare:

- Because we cancelled Quiz 5 this semester, the content covered on this Quiz 6 will include a mix of content from quizzes 5 and 6 from Spring 2022. Here are [Spring 2022 quiz 5](files/ps/quiz5_s22.pdf) and [Spring 2022 quiz 6](files/ps/quiz6_s22.pdf), as well as sample solutions for each: [quiz 5 sample solutions](files/ps/quiz5_sols.pdf) and [quiz 6 sample solutions](files/ps/quiz6_sols.pdf).
- Here are sample solutions for [PS9](files/ps/ps9_sols.pdf), and [PS10](files/ps/ps10_sols.pdf).



# Collaboration Policy

This quiz is open-note, closed internet, and closed-collaborator. To see additional details on what this policy, please refer to the [syllabus](/syllabus.html).

# The Quiz

You can view the quiz [here](/files/ps/quiz6_blank.pdf).

This quiz has the same submission procedure you saw for the problem sets:

1. Download the [Quiz6 template](files/ps/quiz6.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *quiz6.zip* you downloaded in step 1
1. Look in `quiz6.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `quiz6.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.


