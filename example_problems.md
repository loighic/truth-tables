---
title: example problems
---


# Carnap: MSU example problems


This page contains the different kinds of problems that are given to students in Mississippi State's Intro to Logic course along with some typical instructions.

---

Be sure to submit each problem. The `✓` indicates that the problem has been checked, not that it has been submitted.

---

For problem 1, type the main logical operator for the given TFL sentence in the space provided. Use ~, v, & , ->, and <->.<br>
Hit `enter` (not &ldquo;Submit&rdquo;).<br> 
Type the main logical operator for the sub-sentence that's in red. Hit `enter`.<br> 
Repeat until finished. (You're finished when the box turns green and the check mark appears).<br>
**Then submit the problem.**

1. For problem 1, type the main logical operator for the given TFL sentence in the space provided. Use ~, v, & , ->, and <->.
2. Hit `enter` (not &ldquo;Submit&rdquo;).
3. Type the main logical operator for the sub-sentence that's in red. Hit `enter`.
4. Repeat until finished. (You're finished when the box turns green and the check mark appears).
5. **Then submit the problem.**


~~~{.SynChecker .Match system="magnusSL"  points="10" late-credit="8"}
1 (R & ~T)
~~~

You can use the previous problem as a guide for completing this truth table. First, fill in the columns under the atomic sentences. Then, fill in the columns under the logical operators in the ***reverse order*** that you selected them above. 

That is, first, fill in the column under the operator that you entered last. Then, fill in the column under the operator that you entered second-to-last, etc.

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
2 (R & ~T)
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="10" late-credit="8"}
3 P <-> ~Q :|-: Q -> ~P
~~~

~~~{.QualitativeProblem .MultipleChoice options="check" points="10" late-credit="8"}
4 Which one of the following is correct about P &LeftRightArrow; ~Q &vdash; Q &rarr; ~P, the argument in the previous problem?
|* This argument is valid.
| This  argument is invalid.
~~~


~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="10" late-credit="8"}
5 S & T, Q v R, ~R :|-: Q & T
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---
