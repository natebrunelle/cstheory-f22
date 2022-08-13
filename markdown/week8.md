---
title: Week 8 Guide
...

# Goals

The main goals for Week 8 are to:

- Understand the proof that Regular Expressions are equivalent in power to Deterministic Finite Automata. This is a long proof, split over 4 videos, but is something we hope everyone understands in detail. The methods used in the proof are similar to ones we have seen before in showing equivalence of NAND-Circ and Boolean circuits, but is a fair bit more complex. This general method of showing equivalence is something we will see again in this class, and you will encounter many more times in other classes and work that you will do.

- Become familiar with the power and strangeness of nondeterminism. For finite automata, we prove this week that despite is seeming super-power, nondeterministic finite automata cannot compute any functions (or recognize any languages) that cannot be computed by deterministic finite automata. The main topic for Weeks 8-11 will be considering this question for more powerul computing models (which is the most famous open problem in computer science).


# Reading

This week continues with the material in [Chapter 6: Functions with
Infinite domains, Automata, and Regular
expressions](https://introtcs.org/public/lec_05_infinite.html) that we
started on last week.

[Section 6.4.2](https://introtcs.org/public/lec_05_infinite.html#regdfaequivsec)
of the book includes a proof that regular expressions are equivalent
in power to deterministic finite automata, but it is quite different
from the proof we do in the videos. Ambitious students are encouraged
to understand both proofs, and to consider the advantages and
disadvantages of the approach taken in the book compared to our
approach (which is the one done more traditionally in theory of
computation courses, at least going back to Mike Sipser's courses in
the 1980s).

There are many books (and other videos) that do present material
similar to what is in the videos this week, but we are not assigning
any additional readings.

# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the March 14 and March 16 lectures.

[PS7 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps7_blank.pdf)

[PS7 [ZIP]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps7.pdf)

Note that this problem set has a programming portion. The directions for that are included below.

## Written Instructions


1. Download the [PS7 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps7.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps7.zip* you downloaded in step 1
1. Look in `ps7.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps7.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.

## Programming Instructions

Before you begin on this assignment, you will need to download three python files and place them in the same project:

- [NFA.py](/files/ps/NFA.py)
- [regex.py](/files/ps/regex.py)
- [ps7.py](/files/ps/ps7.py)


The `NFA` program implements nfa simulation and various closure constructions. The `regex` program defines a class that reads regular expressions and converts them to NFAs. The `ps7` program contains example uses of the `NFA` and `regex` functionality, and also contains the stub for the `huntingtons` function you must implement.

You'll need to use the following functions (example usage of all of them are in `ps7.py`). You may not use the built-in python re library (as this behaves differently from and is more powerful than the regular expressions we defined in class).

- `regex.regex_to_NFA(the_regex)`: If `the_regex` is a string, the function `regex_to_NFA` found in `regex.py` returns and NFA that computes the language indicated by `the_regex`
- `the_nfa.execute(the_string)`: If `the_nfa` is an instance of the `NFA` class defined in `NFA.py`, then invoking the class method `execute` on string `the_string` will return a Boolean value indicating whether or not `the_string` belonged to the language of the NFA.
- `the_nfa.toDot()`: If `the_nfa` is an instance of the `NFA` class defined in `NFA.py`, then invoking the class method `toDot()` will result in a dot (which is a graph specification language) description of the NFA being printed to standard out. You can then copy-paste that description here to see the actual NFA: [https://dreampuf.github.io/GraphvizOnline/](https://dreampuf.github.io/GraphvizOnline/)

### What to do

First, read through all of `ps7.py` and follow the instructions therein to make sure you understand what's going on. After this you'll implement the `huntingtons` function.

For the `huntingtons` function you're asked to implement, the idea is for you to use regular expressions to diagnose whether a person has Huntington's disease by looking at their genome.

A dna sequence is a string of the characters a, t, g, c, representing the sequence of nucleotides that comprise an individual's dna molecules. Very often, the human genome has regions where the same nucleotide sequences repeat many times. Sometimes, certain numbers of these repeats will result in a genetic disorder.
        
Huntington's Disease is caused by having too many consecutive copies of the sequence "cag". By looking at a dna sequence, we can categorize how a person might be affected by Huntington's in the following way:
        
- An individual with less than 26 sequential repeats of "cag" in their genome is considered to be "normal".
- An individual with between 26 and 35 repeats of "cag" is considered to be a "carrier", and may give the disease to their children.
- An individual with between 36 and 39 repeats is said to be "at risk", and may or may not ever show symptoms.
- An individual with 40 or more repeats is said to be "affected", and will eventually show symptoms of the disease.

Your `huntingtons` function should take a dna sequence (a string from the alphabet a,g,t,c) and determine the classification for the individual (i.e. normal, carrier, at risk, or affected). To do this, define a regex for each category, convert each to a nfa, then check which category the given dna sequence falls into. Once you have determined the category, the function should return the appropriate string of: "normal", "carrier", "at risk", or "affected"
        
Note that the dna sequence may have characters before/after the "cag" repeats.
            
[Source describing Huntingtons](https://en.wikipedia.org/wiki/Huntington%27s_disease).

# Optional Videos

<p>Nondeterministic Nathans (1:23) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/hd809qBaNYY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Warm-Up: Complementing the XOR Language (5:54) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Se4LhD_NTk8' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Equivalence of Regular Expressions and FSAs (6:12) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Vcv6dR3__g8' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Proving FSAs are as Powerful as Regular Expressions (Part 1: Proof Strategy) (4:35) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/IGPKOmACoes' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Proving FSAs are as Powerful as Regular Expressions (Part 2: Bases, Union) (22:55) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/aA47ceLSuoc' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Nondeterminism (11:14) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Qu8NsFh2Ss4' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Nondeterministic Finite Automata (NFAs) (13:48) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/5fk2ej5jU8c' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Equivalence of NFAs and DFAs (10:01) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/iO-0KWSJs3A' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Proving FSAs are as Powerful as Regular Expressions (Part 3: Concatenation) (14:58) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/84tXODX8RGo' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Proving FSAs are as Powerful as Regular Expressions (Part 4: Kleene Star) (8:21) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/xV7nnli95tw' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>




