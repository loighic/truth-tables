## truth tables HW 4


Each problem is worth 10 points, and the whole assignment is worth 100 points. Your grade will be put on a 10 point scale when it is posted in Canvas.  

For the truth tables, determine the truth values for each sentence or pair of sentences. Each of the multiple choice questions is about the truth table right before it. The multiple choice questions can only answered once, and, except for the first one, they cannot be checked.

Except for the first one, the multiple choice questions cannot be checked before they are submitted. Be sure to submit each problem. The `✓` in the green bar indicates that the problem has been checked, not that it has been submitted.

---

**Part 1, concepts**

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
5.1 ~(P -> Q), (~P -> ~Q)
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
5.2 Which one of the following is correct about &not;(P &rarr; Q) and (&not;P &rarr; &not;Q), the sentences in the previous problem?
| The sentences are equivalent.
| The sentences are jointly inconsistent.
|* The sentences are jointly consistent (but not equivalent).
~~~

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
5.3 P -> Q, ~(P & ~Q)
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
5.4 Which one of the following is correct about P &rarr; Q and &not;(P & &not;Q), the sentences in the previous problem?
|* The sentences are equivalent.
| The sentences are jointly inconsistent.
| The sentences are jointly consistent (but not equivalent).
~~~

~~~{.TruthTable .Simple system="magnusSL" options="nocounterexample" points="10" late-credit="8"}
5.5 ~(~P -> S), (S v P)
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
5.6 Which one of the following is correct about &not;(&not;P &rarr; S), (S v P), the sentences in the previous problem?
| The sentences are equivalent.
|* The sentences are jointly inconsistent.
| The sentences are jointly consistent (but not equivalent).
~~~

---

**Part 2, validity**

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample" points="10" late-credit="8"}
5.7 P & Q :|-: Q -> P 
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
5.8 Which one of the following is correct about P & Q &vdash; Q &rarr; P, the argument in the previous problem?
|* This argument is valid.
| This  argument is invalid.
~~~


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample" points="10" late-credit="8"}
5.9 P -> Q :|-: ~Q & P
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
5.10 Which one of the following is correct about P &rarr; Q &vdash; &not;Q & P, the argument in the previous problem?
| This argument is valid.
|* This  argument is invalid.
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample" points="10" late-credit="8"}
5.11 P <-> ~T, ~(T v S) :|-: ~P
~~~

~~~{.QualitativeProblem .MultipleChoice options="exam" points="10" late-credit="8"}
5.12 Which one of the following is correct about P &rarr; Q &vdash; &not;Q & P, the argument in the previous problem?
| This argument is valid.
|* This  argument is invalid.
~~~

---

**Part 3, proofs**

5.13 is done for you. Just hit submit.

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
5.13 P :|-: P v T
|1.P	:PR
|2.P v T	:vI 1
~~~

The argument given in 5.14 has two premises, which should be put in the proof as shown. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
5.14 R, S :|-: R & S
|1.R	:PR
|2.S	:PR
|3. 
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
5.15 (S & T) & Q :|-: T & Q
~~~

&copy; 2023 Gregory Johnson 

---