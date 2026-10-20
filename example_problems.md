---
title: example problems
---


# Carnap: MSU example problems

---

This page contains the different kinds of problems that are given to students in Mississippi State's Intro to Logic course. Normally, an assignment would only include one or two types of problems. 

---

## Syntax Problems


1. For the syntax problems, type the main logical operator for the given TFL sentence in the space provided. Use ~, v, & , ->, and <->.
2. Hit `enter` (not &ldquo;Submit&rdquo;).
3. Type the main logical operator for the sub-sentence that's in red. Hit `enter`.
4. Repeat until finished. (You're finished when the box turns green and the check mark appears).
5. **Then submit the problem.**


~~~{.SynChecker .Match system="magnusSL"  points="10" late-credit="8"}
1 (R & ~T)
2 (P v Q) -> S
~~~

## Truth Tables

In the next set of problems, you have to fill in truth tables. The TFL sentence is given above the table. For each cell below the sentence letters and logical operators in the table, select T or F from the drop down menu. When you are finished, click on the "Check" button. If there is a mistake, then go back and try to correct it (then repeat the check). If the check reports "Success!", click the "Submit" button. You can only submit when the truth table is complete and correct.

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
3 (P -> (Q v ~Q))
4 (R & ~T)
~~~

~~~{.QualitativeProblem .MultipleChoice options="check" points="10" late-credit="8"}
5 Which one of the following is correct about (R & &not;T), the TFL sentence in the previous problem?
| This sentence is a tautology
| This sentence is a contradiction.
|* This sentence is contingent.
~~~

## Proofs

Construct a proof for the argument given in the space provided. Begin by listing the premises, and then proceed until you reach the conclusion. For each line, if there are no errors, a + will appear on the far right. A ? or a &#x26A0; indicates that there is a mistake on the line. A green bar with a &check; will appear when the proof is correct and complete. You can only submit each proof when it is correct and complete.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"}
6 P -> Q, P :|-: Q
7 S & T, Q v R, ~R :|-: Q & T
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---
