## truth tables, assignment 7a (at-home)

---

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. Your grade will be put on a 10 point scale when it is posted in Canvas.

<span style="color:blue">**Do this alone, and don't discuss it with anyone who hasn't done it.**</span>

Determine the truth values for each sentence, and then indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile. 

---


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
7.1 ~(P & Q) :|-: P -> ~Q
7.1 ~(P -> Q) :|-: P & ~Q
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
7.2 (P v Q), ~P :|-: Q & P
7.2 (S v T), ~S :|-: ~T & S
7.2 (M v P), M :|-: ~P & M
~~~


Remember, an argument is `valid` when it is the case that if the premises are true, then the conclusion has to be true. When you are checking for good and bad lines, you are looking for violations of that definition. See chapter 10. 


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
7.3 (P & Q), ~P -> Q :|-: Q
7.3 (P & Q), ~P -> Q  :|-: Q 
7.3 (~P v Q), ~P <-> Q  :|-: Q 
7.3 (P v Q), P -> ~Q  :|-: ~Q 
7.3 (P v ~Q), P -> ~Q :|-: ~Q
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
7.4 (P & Q) -> R :|-: P -> R
7.4 (M v P) <-> T :|-: M <-> T
7.4 (P -> Q) v R :|-: P <-> R
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash autoAtoms" points="20" late-credit="16"}
7.5 (P v Q) -> R, ~Q :|-: P->R
7.5 (M v ~P) -> T, P :|-: M->T
7.5 (P & T) -> ~R, T :|-: P->R
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>


---
