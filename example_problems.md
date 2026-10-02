---
title: example problems
---


# Carnap: MSU example problems

---

This page contains the different kinds of problems that are given to students in Mississippi State's Intro to Logic course. Normally, an assignment would only include or maybe two types of problems. 

---

## Syntax Check Problem


1. For problem 1, type the main logical operator for the given TFL sentence in the space provided. Use ~, v, & , ->, and <->.
2. Hit `enter` (not &ldquo;Submit&rdquo;).
3. Type the main logical operator for the sub-sentence that's in red. Hit `enter`.
4. Repeat until finished. (You're finished when the box turns green and the check mark appears).
5. **Then submit the problem.**


~~~{.SynChecker .Match system="magnusSL"  points="10" late-credit="8"}
1 (R & ~T)
~~~

## Truth Tables

In the next problem, you have to fill in a truth table. The TFL sentence is given above the table. For each cell below the sentence letters and logical operators in the table, select T or F from the drop down menu. When you are finished, click on the "Check" button. A pop-up box will tell you if the table is correct or if it is not. If there is a mistake, then go back and try to correct it (then repeat the check). If the check reports "Success!", hit the "Submit" button. You can only submit when the truth table is complete and correct.

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
2 (R & ~T)
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="10" late-credit="8"}
3 P <-> ~Q :|-: Q -> ~P
~~~

~~~{.QualitativeProblem .MultipleChoice options="check" points="10" late-credit="8"}
4 Which one of the following is correct about P &LeftRightArrow; &not;Q &vdash; Q &rarr; &not;P, the argument in the previous problem?
|* This argument is valid.
| This  argument is invalid.
~~~

## Proofs

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"}
5 P -> Q, P :|-: Q
6 S & T, Q v R, ~R :|-: Q & T
~~~



<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---
