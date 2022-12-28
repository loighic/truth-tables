## truth tables HW 6

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. Your grade will be put on a 10 point scale when it is posted in Canvas.

Determine the truth values for each sentence, and then indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile. 

---


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
6.1 ~(P & Q) :|-: P -> ~Q
6.1 ~(P -> Q) :|-: P & ~Q
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
6.2 (P v Q), ~P :|-: Q & P
6.2 (S v T), ~S :|-: ~T & S
6.2 (A v B), A :|-: ~B & A
~~~


Remember, an argument is `valid` when it is the case that if the premises are true, then the conclusion has to be true. When you are checking for good and bad lines, you are looking for violations of that definition. See chapter 11. 


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
6.3 (P & Q), ~P -> Q :|-: Q
6.3 (P & Q), ~P -> Q  :|-: Q 
6.3 (~P v Q), ~P <-> Q  :|-: Q 
6.3 (P v Q), P -> ~Q  :|-: ~Q 
6.3 (P v ~Q), P -> ~Q :|-: ~Q
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="20" late-credit="16"}
6.4 (P & Q) -> R :|-: P -> R
6.4 (A v B) <-> C :|-: A <-> C
6.4 (P -> Q) v R :|-: P <-> R
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash autoAtoms" points="20" late-credit="16"}
6.5 (P v Q) -> R, ~Q :|-: P->R
6.5 (A v ~B) -> C, B :|-: A->C
6.5 (P & T) -> ~R, T :|-: P->R
~~~

&copy; 2023 Gregory Johnson 

---
